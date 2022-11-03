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

Total: 119

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04        | 16        | 20.25%  |
| Ubuntu 18.04        | 7         | 8.86%   |
| Fedora 36           | 4         | 5.06%   |
| Debian 11           | 3         | 3.8%    |
| Ubuntu 22.04        | 2         | 2.53%   |
| Ubuntu 21.10        | 2         | 2.53%   |
| Pop!_OS 20.10       | 2         | 2.53%   |
| OpenMandriva 4.3    | 2         | 2.53%   |
| OpenMandriva 4.2    | 2         | 2.53%   |
| Linux Mint 20.3     | 2         | 2.53%   |
| Linux Mint 20.1     | 2         | 2.53%   |
| ArcoLinux Rolling   | 2         | 2.53%   |
| Xubuntu 19.10       | 1         | 1.27%   |
| Xubuntu 18.04       | 1         | 1.27%   |
| Void Linux Rolling  | 1         | 1.27%   |
| Ubuntu Budgie 22.04 | 1         | 1.27%   |
| Ubuntu Budgie 21.10 | 1         | 1.27%   |
| Ubuntu Budgie 20.04 | 1         | 1.27%   |
| Ubuntu 21.04        | 1         | 1.27%   |
| Ubuntu 19.04        | 1         | 1.27%   |
| Solus 4.1           | 1         | 1.27%   |
| Pop!_OS 21.04       | 1         | 1.27%   |
| Pop!_OS 20.04       | 1         | 1.27%   |
| Manjaro 21.1.2      | 1         | 1.27%   |
| Manjaro 20.1        | 1         | 1.27%   |
| Lubuntu 21.04       | 1         | 1.27%   |
| LMDE 4              | 1         | 1.27%   |
| Linux Mint 21       | 1         | 1.27%   |
| Linux Mint 20.2     | 1         | 1.27%   |
| Linux Mint 20       | 1         | 1.27%   |
| Linux Mint 19.3     | 1         | 1.27%   |
| Kubuntu 20.04       | 1         | 1.27%   |
| KDE neon 20.04      | 1         | 1.27%   |
| Fedora 34           | 1         | 1.27%   |
| Fedora 33           | 1         | 1.27%   |
| Fedora 32           | 1         | 1.27%   |
| Fedora 31           | 1         | 1.27%   |
| Fedora 30           | 1         | 1.27%   |
| Elementary 6        | 1         | 1.27%   |
| Debian 10           | 1         | 1.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 28        | 35.9%   |
| Fedora        | 9         | 11.54%  |
| Linux Mint    | 8         | 10.26%  |
| Pop!_OS       | 4         | 5.13%   |
| OpenMandriva  | 4         | 5.13%   |
| Debian        | 4         | 5.13%   |
| Ubuntu Budgie | 3         | 3.85%   |
| Xubuntu       | 2         | 2.56%   |
| Manjaro       | 2         | 2.56%   |
| Clear Linux   | 2         | 2.56%   |
| ArcoLinux     | 2         | 2.56%   |
| Arch          | 2         | 2.56%   |
| Void Linux    | 1         | 1.28%   |
| Solus         | 1         | 1.28%   |
| Lubuntu       | 1         | 1.28%   |
| LMDE          | 1         | 1.28%   |
| Kubuntu       | 1         | 1.28%   |
| KDE neon      | 1         | 1.28%   |
| Elementary    | 1         | 1.28%   |
| Archcraft     | 1         | 1.28%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-48-generic        | 4         | 4.44%   |
| 5.4.0-42-generic        | 3         | 3.33%   |
| 5.13.0-22-generic       | 3         | 3.33%   |
| 5.4.0-77-generic        | 2         | 2.22%   |
| 5.4.0-52-generic        | 2         | 2.22%   |
| 5.4.0-33-generic        | 2         | 2.22%   |
| 5.3.0-51-generic        | 2         | 2.22%   |
| 5.16.7-desktop-1omv4003 | 2         | 2.22%   |
| 5.15.0-41-generic       | 2         | 2.22%   |
| 5.9.12-xanmod1          | 1         | 1.11%   |
| 5.9.11-arch2-1          | 1         | 1.11%   |
| 5.9.1-arch1-1           | 1         | 1.11%   |
| 5.8.8-arch1-1           | 1         | 1.11%   |
| 5.8.15-301.fc33.x86_64  | 1         | 1.11%   |
| 5.8.12_1                | 1         | 1.11%   |
| 5.8.0-38-generic        | 1         | 1.11%   |
| 5.7.10-201.fc32.x86_64  | 1         | 1.11%   |
| 5.6.19-158.current      | 1         | 1.11%   |
| 5.4.60-2-MANJARO        | 1         | 1.11%   |
| 5.4.15-200.fc31.x86_64  | 1         | 1.11%   |
| 5.4.0-7642-generic      | 1         | 1.11%   |
| 5.4.0-74-generic        | 1         | 1.11%   |
| 5.4.0-72-generic        | 1         | 1.11%   |
| 5.4.0-39-generic        | 1         | 1.11%   |
| 5.4.0-29-generic        | 1         | 1.11%   |
| 5.4.0-28-generic        | 1         | 1.11%   |
| 5.4.0-26-generic        | 1         | 1.11%   |
| 5.4.0-109-generic       | 1         | 1.11%   |
| 5.4.0-105-generic       | 1         | 1.11%   |
| 5.3.0-61-generic        | 1         | 1.11%   |
| 5.3.0-46-generic        | 1         | 1.11%   |
| 5.3.0-42-generic        | 1         | 1.11%   |
| 5.3.0-28-generic        | 1         | 1.11%   |
| 5.3.0-19-generic        | 1         | 1.11%   |
| 5.19.7-arch1-1          | 1         | 1.11%   |
| 5.19.14-200.fc36.x86_64 | 1         | 1.11%   |
| 5.19.12-200.fc36.x86_64 | 1         | 1.11%   |
| 5.18.17-200.fc36.x86_64 | 1         | 1.11%   |
| 5.18.13-200.fc36.x86_64 | 1         | 1.11%   |
| 5.18.11-200.fc36.x86_64 | 1         | 1.11%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 25.3%   |
| 5.13.0  | 8         | 9.64%   |
| 5.3.0   | 6         | 7.23%   |
| 5.11.0  | 6         | 7.23%   |
| 5.15.0  | 3         | 3.61%   |
| 5.10.0  | 3         | 3.61%   |
| 5.0.0   | 3         | 3.61%   |
| 5.16.7  | 2         | 2.41%   |
| 4.19.0  | 2         | 2.41%   |
| 5.9.12  | 1         | 1.2%    |
| 5.9.11  | 1         | 1.2%    |
| 5.9.1   | 1         | 1.2%    |
| 5.8.8   | 1         | 1.2%    |
| 5.8.15  | 1         | 1.2%    |
| 5.8.12  | 1         | 1.2%    |
| 5.8.0   | 1         | 1.2%    |
| 5.7.10  | 1         | 1.2%    |
| 5.6.19  | 1         | 1.2%    |
| 5.4.60  | 1         | 1.2%    |
| 5.4.15  | 1         | 1.2%    |
| 5.19.7  | 1         | 1.2%    |
| 5.19.14 | 1         | 1.2%    |
| 5.19.12 | 1         | 1.2%    |
| 5.18.17 | 1         | 1.2%    |
| 5.18.13 | 1         | 1.2%    |
| 5.18.11 | 1         | 1.2%    |
| 5.17.4  | 1         | 1.2%    |
| 5.13.13 | 1         | 1.2%    |
| 5.12.9  | 1         | 1.2%    |
| 5.12.14 | 1         | 1.2%    |
| 5.11.15 | 1         | 1.2%    |
| 5.11.12 | 1         | 1.2%    |
| 5.10.19 | 1         | 1.2%    |
| 5.10.14 | 1         | 1.2%    |
| 5.0.10  | 1         | 1.2%    |
| 4.19.8  | 1         | 1.2%    |
| 4.18.0  | 1         | 1.2%    |
| 4.15.0  | 1         | 1.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 23        | 28.05%  |
| 5.13    | 9         | 10.98%  |
| 5.11    | 8         | 9.76%   |
| 5.3     | 6         | 7.32%   |
| 5.10    | 5         | 6.1%    |
| 5.8     | 4         | 4.88%   |
| 5.0     | 4         | 4.88%   |
| 5.9     | 3         | 3.66%   |
| 5.19    | 3         | 3.66%   |
| 5.15    | 3         | 3.66%   |
| 4.19    | 3         | 3.66%   |
| 5.18    | 2         | 2.44%   |
| 5.16    | 2         | 2.44%   |
| 5.12    | 2         | 2.44%   |
| 5.7     | 1         | 1.22%   |
| 5.6     | 1         | 1.22%   |
| 5.17    | 1         | 1.22%   |
| 4.18    | 1         | 1.22%   |
| 4.15    | 1         | 1.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 75        | 96.15%  |
| i686   | 3         | 3.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 36        | 45.57%  |
| KDE5       | 9         | 11.39%  |
| XFCE       | 8         | 10.13%  |
| X-Cinnamon | 7         | 8.86%   |
| Unknown    | 7         | 8.86%   |
| Budgie     | 4         | 5.06%   |
| KDE        | 3         | 3.8%    |
| sway       | 1         | 1.27%   |
| MATE       | 1         | 1.27%   |
| LXQt       | 1         | 1.27%   |
| LXDE       | 1         | 1.27%   |
| DWM        | 1         | 1.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 66        | 83.54%  |
| Wayland | 10        | 12.66%  |
| Unknown | 3         | 3.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 45        | 57.69%  |
| SDDM    | 9         | 11.54%  |
| GDM     | 9         | 11.54%  |
| LightDM | 6         | 7.69%   |
| GDM3    | 5         | 6.41%   |
| TDM     | 4         | 5.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 44        | 55.7%   |
| es_DO   | 19        | 24.05%  |
| Unknown | 7         | 8.86%   |
| es_ES   | 3         | 3.8%    |
| es_MX   | 2         | 2.53%   |
| en_CA   | 2         | 2.53%   |
| fr_FR   | 1         | 1.27%   |
| C       | 1         | 1.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 44        | 56.41%  |
| EFI  | 34        | 43.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 63        | 80.77%  |
| Btrfs   | 6         | 7.69%   |
| Overlay | 5         | 6.41%   |
| Xfs     | 2         | 2.56%   |
| F2fs    | 1         | 1.28%   |
| Unknown | 1         | 1.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 47        | 60.26%  |
| GPT     | 24        | 30.77%  |
| MBR     | 7         | 8.97%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 67        | 84.81%  |
| Yes       | 12        | 15.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 54        | 69.23%  |
| Yes       | 24        | 30.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 26        | 33.33%  |
| Lenovo              | 13        | 16.67%  |
| Hewlett-Packard     | 11        | 14.1%   |
| ASUSTek Computer    | 6         | 7.69%   |
| Acer                | 5         | 6.41%   |
| Apple               | 4         | 5.13%   |
| Samsung Electronics | 2         | 2.56%   |
| MSI                 | 2         | 2.56%   |
| EVOO                | 2         | 2.56%   |
| Toshiba             | 1         | 1.28%   |
| TODOS INDUSTRIAL    | 1         | 1.28%   |
| SAELITE             | 1         | 1.28%   |
| Nuvision            | 1         | 1.28%   |
| Google              | 1         | 1.28%   |
| Fujitsu             | 1         | 1.28%   |
| ECS                 | 1         | 1.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| EVOO EV-C-116-7                                   | 2         | 2.56%   |
| Dell Latitude E6540                               | 2         | 2.56%   |
| Dell Latitude E6430                               | 2         | 2.56%   |
| Dell Latitude E6420                               | 2         | 2.56%   |
| Dell Latitude E6410                               | 2         | 2.56%   |
| Dell Inspiron 5570                                | 2         | 2.56%   |
| Apple MacBookPro8,1                               | 2         | 2.56%   |
| Toshiba Satellite C55-A                           | 1         | 1.28%   |
| TODOS INDUSTRIAL Easytouch_2022_V1                | 1         | 1.28%   |
| Samsung RV420/RV520/RV720/E3530/S3530/E3420/E3520 | 1         | 1.28%   |
| Samsung 905S3G/906S3G/915S3G/9305SG               | 1         | 1.28%   |
| SAELITE ES1AU11                                   | 1         | 1.28%   |
| Nuvision NES11                                    | 1         | 1.28%   |
| MSI GE62 6QC                                      | 1         | 1.28%   |
| MSI CR70 2M/CX70 2OC/CX70 2OD                     | 1         | 1.28%   |
| Lenovo Z50-75 80EC                                | 1         | 1.28%   |
| Lenovo ThinkPad W540 20BHS0GB06                   | 1         | 1.28%   |
| Lenovo ThinkPad T480s 20L7CTO1WW                  | 1         | 1.28%   |
| Lenovo ThinkPad T470 20HD004AUS                   | 1         | 1.28%   |
| Lenovo ThinkPad T410 2537N99                      | 1         | 1.28%   |
| Lenovo ThinkPad P43s 20RH0013US                   | 1         | 1.28%   |
| Lenovo ThinkPad E470 20H1006DUS                   | 1         | 1.28%   |
| Lenovo ThinkBook 14s-IWL 20RM                     | 1         | 1.28%   |
| Lenovo Legion 5 15ARH05 82B5                      | 1         | 1.28%   |
| Lenovo IdeaPad 330S-15IKB 81F5                    | 1         | 1.28%   |
| Lenovo IdeaPad 320-15IKB 80XL                     | 1         | 1.28%   |
| Lenovo G505s 20255                                | 1         | 1.28%   |
| Lenovo G40-70 20369                               | 1         | 1.28%   |
| HP ProBook 6470b                                  | 1         | 1.28%   |
| HP Pavilion ze2000 (EC201UA#ABA)                  | 1         | 1.28%   |
| HP Pavilion Gaming Laptop 15-dk0xxx               | 1         | 1.28%   |
| HP Pavilion dv6                                   | 1         | 1.28%   |
| HP Notebook                                       | 1         | 1.28%   |
| HP Laptop 15-bw0xx                                | 1         | 1.28%   |
| HP G60                                            | 1         | 1.28%   |
| HP ENVY Laptop 13-ad0xx                           | 1         | 1.28%   |
| HP EliteBook 8540w                                | 1         | 1.28%   |
| HP EliteBook 8460p                                | 1         | 1.28%   |
| HP 250 G3                                         | 1         | 1.28%   |
| Google Winky                                      | 1         | 1.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 16        | 20.51%  |
| Dell Inspiron              | 8         | 10.26%  |
| Lenovo ThinkPad            | 6         | 7.69%   |
| Acer Aspire                | 5         | 6.41%   |
| HP Pavilion                | 3         | 3.85%   |
| Lenovo IdeaPad             | 2         | 2.56%   |
| HP EliteBook               | 2         | 2.56%   |
| EVOO EV-C-116-7            | 2         | 2.56%   |
| Dell Vostro                | 2         | 2.56%   |
| Apple MacBookPro8          | 2         | 2.56%   |
| Toshiba Satellite          | 1         | 1.28%   |
| TODOS INDUSTRIAL Easytouch | 1         | 1.28%   |
| Samsung RV420              | 1         | 1.28%   |
| Samsung 905S3G             | 1         | 1.28%   |
| SAELITE ES1AU11            | 1         | 1.28%   |
| Nuvision NES11             | 1         | 1.28%   |
| MSI GE62                   | 1         | 1.28%   |
| MSI CR70                   | 1         | 1.28%   |
| Lenovo Z50-75              | 1         | 1.28%   |
| Lenovo ThinkBook           | 1         | 1.28%   |
| Lenovo Legion              | 1         | 1.28%   |
| Lenovo G505s               | 1         | 1.28%   |
| Lenovo G40-70              | 1         | 1.28%   |
| HP ProBook                 | 1         | 1.28%   |
| HP Notebook                | 1         | 1.28%   |
| HP Laptop                  | 1         | 1.28%   |
| HP G60                     | 1         | 1.28%   |
| HP ENVY                    | 1         | 1.28%   |
| HP 250                     | 1         | 1.28%   |
| Google Winky               | 1         | 1.28%   |
| Fujitsu LIFEBOOK           | 1         | 1.28%   |
| ECS ClassMate              | 1         | 1.28%   |
| ASUS ZenBook               | 1         | 1.28%   |
| ASUS X553MA                | 1         | 1.28%   |
| ASUS VivoBook              | 1         | 1.28%   |
| ASUS TUF                   | 1         | 1.28%   |
| ASUS T100TA                | 1         | 1.28%   |
| ASUS K53E                  | 1         | 1.28%   |
| Apple MacBookPro5          | 1         | 1.28%   |
| Apple MacBook2             | 1         | 1.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2014 | 9         | 11.54%  |
| 2013 | 9         | 11.54%  |
| 2011 | 9         | 11.54%  |
| 2017 | 8         | 10.26%  |
| 2019 | 7         | 8.97%   |
| 2012 | 7         | 8.97%   |
| 2020 | 4         | 5.13%   |
| 2010 | 4         | 5.13%   |
| 2008 | 4         | 5.13%   |
| 2021 | 3         | 3.85%   |
| 2018 | 3         | 3.85%   |
| 2009 | 3         | 3.85%   |
| 2016 | 2         | 2.56%   |
| 2015 | 2         | 2.56%   |
| 2007 | 2         | 2.56%   |
| 2006 | 1         | 1.28%   |
| 2005 | 1         | 1.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 78        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 75        | 96.15%  |
| Enabled  | 3         | 3.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 77        | 98.72%  |
| Yes  | 1         | 1.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 26        | 33.33%  |
| 4.01-8.0   | 21        | 26.92%  |
| 8.01-16.0  | 10        | 12.82%  |
| 16.01-24.0 | 9         | 11.54%  |
| 2.01-3.0   | 4         | 5.13%   |
| 1.01-2.0   | 4         | 5.13%   |
| 32.01-64.0 | 3         | 3.85%   |
| 24.01-32.0 | 1         | 1.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 33        | 38.37%  |
| 2.01-3.0 | 26        | 30.23%  |
| 3.01-4.0 | 14        | 16.28%  |
| 4.01-8.0 | 8         | 9.3%    |
| 0.51-1.0 | 5         | 5.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 57        | 73.08%  |
| 2      | 21        | 26.92%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 40        | 51.28%  |
| Yes       | 38        | 48.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 84.62%  |
| No        | 12        | 15.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 97.44%  |
| No        | 2         | 2.56%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 69.23%  |
| No        | 24        | 30.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Dominican Republic | 78        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Santo Domingo Este         | 51        | 63.75%  |
| Santiago de los Caballeros | 8         | 10%     |
| La Romana                  | 4         | 5%      |
| Santo Domingo              | 2         | 2.5%    |
| Santa Cruz de Barahona     | 2         | 2.5%    |
| Sosua, Cabarete            | 1         | 1.25%   |
| Santo Domingo Oeste        | 1         | 1.25%   |
| San Pedro de Macorís      | 1         | 1.25%   |
| San Cristobal              | 1         | 1.25%   |
| Punta Cana                 | 1         | 1.25%   |
| Los Hidalgos               | 1         | 1.25%   |
| Guaymate                   | 1         | 1.25%   |
| Constanza                  | 1         | 1.25%   |
| Concepción de la Vega     | 1         | 1.25%   |
| Boca Chica                 | 1         | 1.25%   |
| Baní                      | 1         | 1.25%   |
| Bajos de Haina             | 1         | 1.25%   |
| Alejandro Bass             | 1         | 1.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 19        | 24     | 20.43%  |
| WDC                       | 10        | 13     | 10.75%  |
| Toshiba                   | 10        | 12     | 10.75%  |
| Samsung Electronics       | 9         | 10     | 9.68%   |
| SanDisk                   | 8         | 11     | 8.6%    |
| Hitachi                   | 7         | 8      | 7.53%   |
| Kingston                  | 5         | 5      | 5.38%   |
| Unknown                   | 4         | 5      | 4.3%    |
| SK hynix                  | 4         | 5      | 4.3%    |
| Unknown                   | 3         | 3      | 3.23%   |
| Transcend                 | 2         | 2      | 2.15%   |
| FORESEE                   | 2         | 2      | 2.15%   |
| SPCC                      | 1         | 1      | 1.08%   |
| PNY                       | 1         | 1      | 1.08%   |
| OCZ                       | 1         | 1      | 1.08%   |
| Micron/Crucial Technology | 1         | 1      | 1.08%   |
| Micron Technology         | 1         | 1      | 1.08%   |
| LITEONIT                  | 1         | 2      | 1.08%   |
| Intel                     | 1         | 1      | 1.08%   |
| Indilinx                  | 1         | 1      | 1.08%   |
| Hewlett-Packard           | 1         | 1      | 1.08%   |
| A-DATA Technology         | 1         | 1      | 1.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Seagate ST500LM000-1EJ162 500GB  | 3         | 3.16%   |
| Unknown                          | 3         | 3.16%   |
| Unknown MMC Card  32GB           | 2         | 2.11%   |
| Toshiba MQ01ACF050 500GB         | 2         | 2.11%   |
| Toshiba MK3275GSX 320GB          | 2         | 2.11%   |
| Seagate ST9250315AS 250GB        | 2         | 2.11%   |
| Seagate ST1000LM049-2GH172 1TB   | 2         | 2.11%   |
| SanDisk NVMe SSD Drive 256GB     | 2         | 2.11%   |
| Samsung SSD 860 EVO 500GB        | 2         | 2.11%   |
| FORESEE 128GB SSD                | 2         | 2.11%   |
| WDC WDS100T2G0A-00JH30 1TB SSD   | 1         | 1.05%   |
| WDC WD5000LPLX-08ZNTT0 500GB     | 1         | 1.05%   |
| WDC WD3200LPVX-75V0TT0 320GB     | 1         | 1.05%   |
| WDC WD3200BEVT-75A23T0 320GB     | 1         | 1.05%   |
| WDC WD2500BEVT-75A23T0 250GB     | 1         | 1.05%   |
| WDC WD2500BEVS-22UST0 250GB      | 1         | 1.05%   |
| WDC WD1600BEVT-75ZCT1 160GB      | 1         | 1.05%   |
| WDC WD10SPZX-24Z10T0 1TB         | 1         | 1.05%   |
| WDC WD10JPVX-60JC3T1 1TB         | 1         | 1.05%   |
| WDC WD10JPCX-24UE4T0 1TB         | 1         | 1.05%   |
| Unknown MMC Card  64GB           | 1         | 1.05%   |
| Unknown MMC Card  16GB           | 1         | 1.05%   |
| Unknown MMC Card  128GB          | 1         | 1.05%   |
| Transcend TS256GSSD340 256GB     | 1         | 1.05%   |
| Transcend TS128GSSD370S 128GB    | 1         | 1.05%   |
| Toshiba NVMe SSD Drive 1024GB    | 1         | 1.05%   |
| Toshiba MQ01ABF050 500GB         | 1         | 1.05%   |
| Toshiba MQ01ABD100 1TB           | 1         | 1.05%   |
| Toshiba MK6475GSX 640GB          | 1         | 1.05%   |
| Toshiba MK3276GSX 320GB          | 1         | 1.05%   |
| Toshiba MK2556GSY 250GB          | 1         | 1.05%   |
| SPCC Solid State Disk 512GB      | 1         | 1.05%   |
| SK hynix SC311 SATA 256GB SSD    | 1         | 1.05%   |
| SK hynix NVMe SSD Drive 256GB    | 1         | 1.05%   |
| SK hynix HCG8e  64GB             | 1         | 1.05%   |
| SK hynix C2S3T/240G 240GB        | 1         | 1.05%   |
| Seagate ST9750420AS 752GB        | 1         | 1.05%   |
| Seagate ST9500325AS 500GB        | 1         | 1.05%   |
| Seagate ST9320325AS 320GB        | 1         | 1.05%   |
| Seagate ST640LM000 HM641JI 640GB | 1         | 1.05%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 19        | 24     | 43.18%  |
| WDC     | 9         | 12     | 20.45%  |
| Toshiba | 9         | 11     | 20.45%  |
| Hitachi | 7         | 8      | 15.91%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 6         | 9      | 20%     |
| Samsung Electronics | 6         | 7      | 20%     |
| Kingston            | 4         | 4      | 13.33%  |
| Transcend           | 2         | 2      | 6.67%   |
| SK hynix            | 2         | 2      | 6.67%   |
| FORESEE             | 2         | 2      | 6.67%   |
| WDC                 | 1         | 1      | 3.33%   |
| SPCC                | 1         | 1      | 3.33%   |
| PNY                 | 1         | 1      | 3.33%   |
| OCZ                 | 1         | 1      | 3.33%   |
| LITEONIT            | 1         | 2      | 3.33%   |
| Hewlett-Packard     | 1         | 1      | 3.33%   |
| A-DATA Technology   | 1         | 1      | 3.33%   |
| Unknown             | 1         | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 42        | 55     | 47.73%  |
| SSD     | 27        | 35     | 30.68%  |
| NVMe    | 11        | 12     | 12.5%   |
| MMC     | 7         | 8      | 7.95%   |
| Unknown | 1         | 1      | 1.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 64        | 87     | 75.29%  |
| NVMe | 11        | 12     | 12.94%  |
| MMC  | 7         | 8      | 8.24%   |
| SAS  | 3         | 4      | 3.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 49        | 66     | 72.06%  |
| 0.51-1.0   | 16        | 20     | 23.53%  |
| 1.01-2.0   | 2         | 2      | 2.94%   |
| 3.01-4.0   | 1         | 2      | 1.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 29        | 35.8%   |
| 251-500        | 16        | 19.75%  |
| 501-1000       | 13        | 16.05%  |
| 1-20           | 6         | 7.41%   |
| 51-100         | 6         | 7.41%   |
| 21-50          | 4         | 4.94%   |
| 1001-2000      | 3         | 3.7%    |
| Unknown        | 2         | 2.47%   |
| More than 3000 | 1         | 1.23%   |
| 2001-3000      | 1         | 1.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 35        | 39.77%  |
| 21-50     | 20        | 22.73%  |
| 51-100    | 12        | 13.64%  |
| 101-250   | 10        | 11.36%  |
| 251-500   | 3         | 3.41%   |
| 501-1000  | 3         | 3.41%   |
| 1001-2000 | 2         | 2.27%   |
| Unknown   | 2         | 2.27%   |
| 2001-3000 | 1         | 1.14%   |

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
| Detected | 51        | 77     | 62.96%  |
| Works    | 22        | 26     | 27.16%  |
| Malfunc  | 8         | 8      | 9.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 58        | 71.6%   |
| AMD                          | 12        | 14.81%  |
| Samsung Electronics          | 3         | 3.7%    |
| SanDisk                      | 2         | 2.47%   |
| Toshiba America Info Systems | 1         | 1.23%   |
| SK hynix                     | 1         | 1.23%   |
| Nvidia                       | 1         | 1.23%   |
| Micron/Crucial Technology    | 1         | 1.23%   |
| Micron Technology            | 1         | 1.23%   |
| Kingston Technology Company  | 1         | 1.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 11        | 12.79%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 9         | 10.47%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 6         | 6.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 6.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 6         | 6.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 5         | 5.81%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 4         | 4.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 3.49%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 3.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 3.49%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 3.49%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 2         | 2.33%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 2.33%   |
| Toshiba America Info Systems NVMe Controller                                           | 1         | 1.16%   |
| SK hynix Gold P31 SSD                                                                  | 1         | 1.16%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.16%   |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 1.16%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 1.16%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 1         | 1.16%   |
| Micron Non-Volatile memory controller                                                  | 1         | 1.16%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 1.16%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 1.16%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 1         | 1.16%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.16%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 1.16%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 1.16%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 1.16%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 1         | 1.16%   |
| AMD IXP SB4x0 IDE Controller                                                           | 1         | 1.16%   |
| AMD FCH IDE Controller                                                                 | 1         | 1.16%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 53        | 64.63%  |
| NVMe | 11        | 13.41%  |
| RAID | 9         | 10.98%  |
| IDE  | 9         | 10.98%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 65        | 83.33%  |
| AMD    | 13        | 16.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 5.13%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 4         | 5.13%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 3.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 2.56%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 2         | 2.56%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 2.56%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 2.56%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 2.56%   |
| Intel Core i5-2415M CPU @ 2.30GHz           | 2         | 2.56%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 2.56%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.28%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 1.28%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 1.28%   |
| Intel Genuine CPU U4100 @ 1.30GHz           | 1         | 1.28%   |
| Intel Core i9-9980HK CPU @ 2.40GHz          | 1         | 1.28%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 1.28%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 1.28%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 1.28%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 1.28%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 1.28%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 1.28%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 1.28%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 1.28%   |
| Intel Core i5-4310M CPU @ 2.70GHz           | 1         | 1.28%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.28%   |
| Intel Core i5-3340M CPU @ 2.70GHz           | 1         | 1.28%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 1.28%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.28%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.28%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 1.28%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 1         | 1.28%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 1.28%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 1         | 1.28%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 1.28%   |
| Intel Core i3-3227U CPU @ 1.90GHz           | 1         | 1.28%   |
| Intel Core i3-2375M CPU @ 1.50GHz           | 1         | 1.28%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 1         | 1.28%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 1         | 1.28%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 1         | 1.28%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz        | 1         | 1.28%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 25        | 32.05%  |
| Intel Core i7           | 12        | 15.38%  |
| Intel Celeron           | 11        | 14.1%   |
| Intel Core i3           | 5         | 6.41%   |
| Intel Core 2 Duo        | 3         | 3.85%   |
| Intel Core 2            | 2         | 2.56%   |
| Intel Atom              | 2         | 2.56%   |
| AMD Ryzen 7             | 2         | 2.56%   |
| AMD Ryzen 5             | 2         | 2.56%   |
| AMD A8                  | 2         | 2.56%   |
| AMD A10                 | 2         | 2.56%   |
| Intel Pentium Dual-Core | 1         | 1.28%   |
| Intel Pentium Dual      | 1         | 1.28%   |
| Intel Pentium           | 1         | 1.28%   |
| Intel Genuine           | 1         | 1.28%   |
| Intel Core i9           | 1         | 1.28%   |
| AMD Quad-Core           | 1         | 1.28%   |
| AMD Mobile Sempron      | 1         | 1.28%   |
| AMD A6                  | 1         | 1.28%   |
| AMD A4                  | 1         | 1.28%   |
| AMD A12                 | 1         | 1.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 54        | 69.23%  |
| 4      | 19        | 24.36%  |
| 8      | 2         | 2.56%   |
| 1      | 2         | 2.56%   |
| 6      | 1         | 1.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 78        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 49        | 62.82%  |
| 1      | 29        | 37.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 76        | 97.44%  |
| 32-bit         | 1         | 1.28%   |
| Unknown        | 1         | 1.28%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 17.95%  |
| 0x206a7    | 9         | 11.54%  |
| 0x306a9    | 6         | 7.69%   |
| 0x40651    | 5         | 6.41%   |
| 0x806ea    | 4         | 5.13%   |
| 0x806e9    | 4         | 5.13%   |
| 0x706a1    | 4         | 5.13%   |
| 0x1067a    | 4         | 5.13%   |
| 0x306c3    | 3         | 3.85%   |
| 0x07030105 | 3         | 3.85%   |
| 0x6f6      | 2         | 2.56%   |
| 0x30678    | 2         | 2.56%   |
| 0x20652    | 2         | 2.56%   |
| 0x806ec    | 1         | 1.28%   |
| 0x6fd      | 1         | 1.28%   |
| 0x506e3    | 1         | 1.28%   |
| 0x506c9    | 1         | 1.28%   |
| 0x406c3    | 1         | 1.28%   |
| 0x20655    | 1         | 1.28%   |
| 0x106ca    | 1         | 1.28%   |
| 0x10676    | 1         | 1.28%   |
| 0x08608102 | 1         | 1.28%   |
| 0x08600103 | 1         | 1.28%   |
| 0x08108109 | 1         | 1.28%   |
| 0x08108102 | 1         | 1.28%   |
| 0x0700010f | 1         | 1.28%   |
| 0x0600611a | 1         | 1.28%   |
| 0x06003106 | 1         | 1.28%   |
| 0x06001119 | 1         | 1.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 13        | 16.67%  |
| SandyBridge   | 9         | 11.54%  |
| Haswell       | 9         | 11.54%  |
| IvyBridge     | 8         | 10.26%  |
| Westmere      | 5         | 6.41%   |
| Silvermont    | 5         | 6.41%   |
| Penryn        | 5         | 6.41%   |
| Goldmont plus | 5         | 6.41%   |
| Puma          | 3         | 3.85%   |
| Core          | 3         | 3.85%   |
| Zen+          | 2         | 2.56%   |
| Zen 2         | 1         | 1.28%   |
| Steamroller   | 1         | 1.28%   |
| Skylake       | 1         | 1.28%   |
| Piledriver    | 1         | 1.28%   |
| K8 Hammer     | 1         | 1.28%   |
| K10 Llano     | 1         | 1.28%   |
| Jaguar        | 1         | 1.28%   |
| Goldmont      | 1         | 1.28%   |
| Excavator     | 1         | 1.28%   |
| Bonnell       | 1         | 1.28%   |
| Unknown       | 1         | 1.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 61        | 68.54%  |
| AMD    | 18        | 20.22%  |
| Nvidia | 10        | 11.24%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 8.51%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 8.51%   |
| Intel UHD Graphics 620                                                                   | 5         | 5.32%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 5.32%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 5.32%   |
| Intel HD Graphics 620                                                                    | 4         | 4.26%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 4.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 4.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 3.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 3.19%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 2.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 2.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 2.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 2.13%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.13%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 2.13%   |
| Nvidia TU117M                                                                            | 1         | 1.06%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 1.06%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 1         | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.06%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.06%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 1.06%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                            | 1         | 1.06%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.06%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.06%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.06%   |
| Intel HD Graphics 530                                                                    | 1         | 1.06%   |
| Intel HD Graphics 500                                                                    | 1         | 1.06%   |
| Intel Haswell Integrated Graphics Controller                                             | 1         | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.06%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.06%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 1.06%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.06%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.06%   |
| AMD Temash [Radeon HD 8250/8280G]                                                        | 1         | 1.06%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 1.06%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 1.06%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 1.06%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.06%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 52        | 66.67%  |
| 1 x AMD        | 10        | 12.82%  |
| Intel + Nvidia | 5         | 6.41%   |
| Intel + AMD    | 4         | 5.13%   |
| 1 x Nvidia     | 3         | 3.85%   |
| 2 x AMD        | 2         | 2.56%   |
| AMD + Nvidia   | 2         | 2.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 71        | 91.03%  |
| Proprietary | 6         | 7.69%   |
| Unknown     | 1         | 1.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 57        | 73.08%  |
| 0.01-0.5   | 7         | 8.97%   |
| 1.01-2.0   | 6         | 7.69%   |
| 0.51-1.0   | 6         | 7.69%   |
| 3.01-4.0   | 2         | 2.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 19        | 21.35%  |
| LG Display              | 12        | 13.48%  |
| BOE                     | 12        | 13.48%  |
| Samsung Electronics     | 10        | 11.24%  |
| Chimei Innolux          | 10        | 11.24%  |
| Chi Mei Optoelectronics | 5         | 5.62%   |
| Dell                    | 4         | 4.49%   |
| Apple                   | 4         | 4.49%   |
| Hewlett-Packard         | 2         | 2.25%   |
| ZTR                     | 1         | 1.12%   |
| Westinghouse            | 1         | 1.12%   |
| Vizio                   | 1         | 1.12%   |
| Unknown (XXX)           | 1         | 1.12%   |
| Sony                    | 1         | 1.12%   |
| Philips                 | 1         | 1.12%   |
| PANDA                   | 1         | 1.12%   |
| LG Philips              | 1         | 1.12%   |
| Lenovo                  | 1         | 1.12%   |
| KDC                     | 1         | 1.12%   |
| InnoLux Display         | 1         | 1.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 2.25%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch           | 2         | 2.25%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 2.25%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 2.25%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 2.25%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch         | 2         | 2.25%   |
| ZTR LCD Monitor ZTR0001 1366x768 256x144mm 11.6-inch                  | 1         | 1.12%   |
| Westinghouse EUM24F1G1 WDT1E64 1920x1080 530x300mm 24.0-inch          | 1         | 1.12%   |
| Vizio D32x-D1 VIZ1005 1920x1080 698x392mm 31.5-inch                   | 1         | 1.12%   |
| Unknown (XXX) V56 XXX0030 1920x1080 708x398mm 32.0-inch               | 1         | 1.12%   |
| Sony TV SNY1703 1360x768 1600x900mm 72.3-inch                         | 1         | 1.12%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SDC5544 1920x1080 344x194mm 15.5-inch | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SAM0B32 1366x768 610x350mm 27.7-inch  | 1         | 1.12%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch              | 1         | 1.12%   |
| PANDA LC116LF1L02 NCP000F 1920x1080 256x144mm 11.6-inch               | 1         | 1.12%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD03AE 1366x768 345x194mm 15.6-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD0357 1600x900 382x215mm 17.3-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch           | 1         | 1.12%   |
| Lenovo LCD Monitor LEN4035 1280x800 304x190mm 14.1-inch               | 1         | 1.12%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 1         | 1.12%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch      | 1         | 1.12%   |
| Hewlett-Packard E221c HWP3093 1920x1080 497x292mm 22.7-inch           | 1         | 1.12%   |
| Hewlett-Packard 2009 HWP2827 1600x900 442x249mm 20.0-inch             | 1         | 1.12%   |
| Dell P2212H DELA07E 1920x1080 531x299mm 24.0-inch                     | 1         | 1.12%   |
| Dell P2210H DELD026 1920x1080 477x268mm 21.5-inch                     | 1         | 1.12%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                     | 1         | 1.12%   |
| Dell 1707FP DEL4013 1280x1024 338x270mm 17.0-inch                     | 1         | 1.12%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 1         | 1.12%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 39        | 46.43%  |
| 1920x1080 (FHD)  | 24        | 28.57%  |
| 1280x800 (WXGA)  | 7         | 8.33%   |
| 1600x900 (HD+)   | 5         | 5.95%   |
| 3840x2160 (4K)   | 2         | 2.38%   |
| 1280x1024 (SXGA) | 2         | 2.38%   |
| 3840x1100        | 1         | 1.19%   |
| 1360x768         | 1         | 1.19%   |
| 1280x768         | 1         | 1.19%   |
| 1024x768 (XGA)   | 1         | 1.19%   |
| 1024x600         | 1         | 1.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 40        | 45.45%  |
| 13      | 14        | 15.91%  |
| 14      | 11        | 12.5%   |
| 11      | 8         | 9.09%   |
| 24      | 2         | 2.27%   |
| 17      | 2         | 2.27%   |
| 72      | 1         | 1.14%   |
| 40      | 1         | 1.14%   |
| 34      | 1         | 1.14%   |
| 32      | 1         | 1.14%   |
| 31      | 1         | 1.14%   |
| 22      | 1         | 1.14%   |
| 21      | 1         | 1.14%   |
| 20      | 1         | 1.14%   |
| 19      | 1         | 1.14%   |
| 10      | 1         | 1.14%   |
| Unknown | 1         | 1.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 54        | 62.79%  |
| 201-300     | 17        | 19.77%  |
| 351-400     | 4         | 4.65%   |
| 401-500     | 3         | 3.49%   |
| 701-800     | 2         | 2.33%   |
| 501-600     | 2         | 2.33%   |
| 801-900     | 1         | 1.16%   |
| 601-700     | 1         | 1.16%   |
| 1501-2000   | 1         | 1.16%   |
| Unknown     | 1         | 1.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 66        | 84.62%  |
| 16/10   | 7         | 8.97%   |
| 5/4     | 2         | 2.56%   |
| 4/3     | 1         | 1.28%   |
| 3.40    | 1         | 1.28%   |
| Unknown | 1         | 1.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 40        | 45.45%  |
| 81-90          | 19        | 21.59%  |
| 51-60          | 9         | 10.23%  |
| 71-80          | 5         | 5.68%   |
| 201-250        | 4         | 4.55%   |
| 351-500        | 2         | 2.27%   |
| 151-200        | 2         | 2.27%   |
| 501-1000       | 2         | 2.27%   |
| More than 1000 | 1         | 1.14%   |
| 41-50          | 1         | 1.14%   |
| 141-150        | 1         | 1.14%   |
| 121-130        | 1         | 1.14%   |
| Unknown        | 1         | 1.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 40        | 47.06%  |
| 121-160       | 26        | 30.59%  |
| 51-100        | 12        | 14.12%  |
| 1-50          | 3         | 3.53%   |
| 161-240       | 2         | 2.35%   |
| More than 240 | 1         | 1.18%   |
| Unknown       | 1         | 1.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 65        | 82.28%  |
| 2     | 11        | 13.92%  |
| 0     | 2         | 2.53%   |
| 3     | 1         | 1.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 38        | 31.15%  |
| Realtek Semiconductor           | 36        | 29.51%  |
| Qualcomm Atheros                | 22        | 18.03%  |
| Broadcom                        | 12        | 9.84%   |
| Qualcomm Atheros Communications | 2         | 1.64%   |
| Marvell Technology Group        | 2         | 1.64%   |
| Lenovo                          | 2         | 1.64%   |
| Broadcom Limited                | 2         | 1.64%   |
| Ralink Technology               | 1         | 0.82%   |
| Nvidia                          | 1         | 0.82%   |
| MediaTek                        | 1         | 0.82%   |
| JCM                             | 1         | 0.82%   |
| Dell                            | 1         | 0.82%   |
| AMD                             | 1         | 0.82%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 16        | 10.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 12        | 8%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 7         | 4.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 6         | 4%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 5         | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 5         | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 2.67%   |
| Intel Wireless 7260                                                                   | 4         | 2.67%   |
| Intel Wireless 3165                                                                   | 4         | 2.67%   |
| Intel 82577LM Gigabit Network Connection                                              | 4         | 2.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 2%      |
| Intel Ethernet Connection I217-LM                                                     | 3         | 2%      |
| Intel Centrino Advanced-N 6235                                                        | 3         | 2%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 2         | 1.33%   |
| Realtek 802.11n WLAN Adapter                                                          | 2         | 1.33%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 2         | 1.33%   |
| Lenovo Thinkpad LAN                                                                   | 2         | 1.33%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 1.33%   |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 1.33%   |
| Intel Ethernet Connection I218-LM                                                     | 2         | 1.33%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 1.33%   |
| Intel Centrino Advanced-N 6200                                                        | 2         | 1.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 2         | 1.33%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                     | 2         | 1.33%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 1.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 0.67%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.67%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 1         | 0.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 1         | 0.67%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 0.67%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 0.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 1         | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                              | 1         | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1         | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                              | 1         | 0.67%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 45%     |
| Qualcomm Atheros                | 19        | 23.75%  |
| Realtek Semiconductor           | 10        | 12.5%   |
| Broadcom                        | 9         | 11.25%  |
| Qualcomm Atheros Communications | 2         | 2.5%    |
| Ralink Technology               | 1         | 1.25%   |
| MediaTek                        | 1         | 1.25%   |
| Dell                            | 1         | 1.25%   |
| Broadcom Limited                | 1         | 1.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 6         | 7.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 5         | 6.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 5         | 6.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 4.94%   |
| Intel Wireless 7260                                                                   | 4         | 4.94%   |
| Intel Wireless 3165                                                                   | 4         | 4.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 3.7%    |
| Intel Centrino Advanced-N 6235                                                        | 3         | 3.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 2.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 2         | 2.47%   |
| Realtek 802.11n WLAN Adapter                                                          | 2         | 2.47%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 2         | 2.47%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 2.47%   |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 2.47%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 2.47%   |
| Intel Centrino Advanced-N 6200                                                        | 2         | 2.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 2         | 2.47%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 2.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 2.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 1.23%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 1.23%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.23%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 1.23%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 1.23%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.23%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 1.23%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 1         | 1.23%   |
| Intel Wireless 7265                                                                   | 1         | 1.23%   |
| Intel Wireless 3160                                                                   | 1         | 1.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 1.23%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 1.23%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 1         | 1.23%   |
| Intel Centrino Wireless-N 6150                                                        | 1         | 1.23%   |
| Intel Centrino Wireless-N 2230                                                        | 1         | 1.23%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 1.23%   |
| Intel Centrino Wireless-N + WiMAX 6150                                                | 1         | 1.23%   |
| Dell Wireless 5630 (EVDO-HSPA) Mobile Broadband Mini-Card                             | 1         | 1.23%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                             | 1         | 1.23%   |
| Broadcom BCM43228 802.11a/b/g/n                                                       | 1         | 1.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 30        | 44.78%  |
| Intel                    | 20        | 29.85%  |
| Broadcom                 | 6         | 8.96%   |
| Qualcomm Atheros         | 5         | 7.46%   |
| Marvell Technology Group | 2         | 2.99%   |
| Lenovo                   | 2         | 2.99%   |
| Nvidia                   | 1         | 1.49%   |
| Broadcom Limited         | 1         | 1.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 23.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 17.91%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 10.45%  |
| Intel 82577LM Gigabit Network Connection                          | 4         | 5.97%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 4.48%   |
| Lenovo Thinkpad LAN                                               | 2         | 2.99%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.99%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.49%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.49%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.49%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.49%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.49%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.49%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.49%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.49%   |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                 | 1         | 1.49%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.49%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.49%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.49%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express  | 1         | 1.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 76        | 52.78%  |
| Ethernet | 66        | 45.83%  |
| Modem    | 2         | 1.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 76.54%  |
| Ethernet | 19        | 23.46%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 63        | 80.77%  |
| 1     | 12        | 15.38%  |
| 0     | 3         | 3.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 78        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 42.59%  |
| Qualcomm Atheros Communications | 10        | 18.52%  |
| Dell                            | 5         | 9.26%   |
| IMC Networks                    | 4         | 7.41%   |
| Apple                           | 4         | 7.41%   |
| Realtek Semiconductor           | 3         | 5.56%   |
| Lite-On Technology              | 2         | 3.7%    |
| Broadcom                        | 2         | 3.7%    |
| Hewlett-Packard                 | 1         | 1.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 13        | 24.07%  |
| Qualcomm Atheros  Bluetooth Device             | 5         | 9.26%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 4         | 7.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 3         | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3         | 5.56%   |
| Dell BCM20702A0 Bluetooth Module               | 3         | 5.56%   |
| Apple Bluetooth Host Controller                | 3         | 5.56%   |
| Intel AX200 Bluetooth                          | 2         | 3.7%    |
| IMC Networks Bluetooth Radio                   | 2         | 3.7%    |
| Realtek RTL8723B Bluetooth                     | 1         | 1.85%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 1.85%   |
| Realtek Bluetooth Radio                        | 1         | 1.85%   |
| Qualcomm Atheros Bluetooth USB Host Controller | 1         | 1.85%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 1.85%   |
| Lite-On Wireless_Device                        | 1         | 1.85%   |
| Lite-On Atheros AR3012 Bluetooth               | 1         | 1.85%   |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 1.85%   |
| IMC Networks Bluetooth Device                  | 1         | 1.85%   |
| IMC Networks Bluetooth                         | 1         | 1.85%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 1.85%   |
| Dell Wireless 360 Bluetooth                    | 1         | 1.85%   |
| Dell Wireless 350 Bluetooth                    | 1         | 1.85%   |
| Broadcom HP Portable SoftSailing               | 1         | 1.85%   |
| Broadcom BCM43142 Bluetooth 4.0                | 1         | 1.85%   |
| Apple Bluetooth HCI                            | 1         | 1.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 63        | 74.12%  |
| AMD    | 14        | 16.47%  |
| Nvidia | 7         | 8.24%   |
| Sony   | 1         | 1.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 8.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 8.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 7.69%   |
| AMD FCH Azalia Controller                                                                         | 7         | 6.73%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 4.81%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 4.81%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 4.81%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 4.81%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 4.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 3.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 3.85%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 3.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 2.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 2.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2.88%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 1.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.92%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.92%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.92%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1         | 0.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.96%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.96%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.96%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.96%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.96%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.96%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 0.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.96%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 0.96%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 1         | 0.96%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.96%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.96%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 15        | 35.71%  |
| Samsung Electronics | 10        | 23.81%  |
| Micron Technology   | 5         | 11.9%   |
| Unknown (ABCD)      | 2         | 4.76%   |
| Ramaxel Technology  | 2         | 4.76%   |
| Nanya Technology    | 2         | 4.76%   |
| Kingston            | 2         | 4.76%   |
| Unknown             | 1         | 2.38%   |
| Sesame              | 1         | 2.38%   |
| A-DATA Technology   | 1         | 2.38%   |
| Unknown             | 1         | 2.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 4.44%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 4.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 4.44%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 4.44%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s             | 2         | 4.44%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 2.22%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 2.22%   |
| SK hynix RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 2.22%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.22%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.22%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.22%   |
| SK hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 2.22%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.22%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.22%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 2.22%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 2.22%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 2.22%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.22%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 2.22%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 2.22%   |
| Sesame RAM S939A2SGS-ITR 8192MB SODIMM DDR4 2667MT/s             | 1         | 2.22%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 2.22%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 1         | 2.22%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.22%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 2.22%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 2.22%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 2.22%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 2.22%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 2.22%   |
| Ramaxel RAM RMT3010EC58E8F1333 2048MB SODIMM DDR3 1600MT/s       | 1         | 2.22%   |
| Ramaxel RAM RMT1970ED48E8F1066 2GB SODIMM 1067MT/s               | 1         | 2.22%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 2.22%   |
| Nanya RAM NT2GT64U8HD0BN-AD 2GB SODIMM DDR2 2048MT/s             | 1         | 2.22%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 1         | 2.22%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 2.22%   |
| Micron RAM 16ATF2G64HZ-2G3H1 16GB SODIMM DDR4 2400MT/s           | 1         | 2.22%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s                 | 1         | 2.22%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 1         | 2.22%   |
| A-DATA RAM AD73I1B1674EU 2GB SODIMM DDR3 1334MT/s                | 1         | 2.22%   |
| Unknown                                                          | 1         | 2.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 15        | 44.12%  |
| DDR4   | 11        | 32.35%  |
| SDRAM  | 3         | 8.82%   |
| LPDDR4 | 3         | 8.82%   |
| LPDDR3 | 1         | 2.94%   |
| DDR2   | 1         | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 32        | 94.12%  |
| Row Of Chips | 1         | 2.94%   |
| DIMM         | 1         | 2.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 18        | 47.37%  |
| 8192  | 8         | 21.05%  |
| 2048  | 7         | 18.42%  |
| 16384 | 5         | 13.16%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 13        | 33.33%  |
| 2667  | 7         | 17.95%  |
| 2400  | 6         | 15.38%  |
| 4199  | 2         | 5.13%   |
| 2133  | 2         | 5.13%   |
| 1333  | 2         | 5.13%   |
| 3266  | 1         | 2.56%   |
| 3200  | 1         | 2.56%   |
| 2048  | 1         | 2.56%   |
| 1867  | 1         | 2.56%   |
| 1334  | 1         | 2.56%   |
| 1067  | 1         | 2.56%   |
| 667   | 1         | 2.56%   |

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
| Chicony Electronics                    | 11        | 16.67%  |
| Microdia                               | 9         | 13.64%  |
| Sunplus Innovation Technology          | 7         | 10.61%  |
| Realtek Semiconductor                  | 6         | 9.09%   |
| IMC Networks                           | 6         | 9.09%   |
| Suyin                                  | 5         | 7.58%   |
| Syntek                                 | 4         | 6.06%   |
| Apple                                  | 4         | 6.06%   |
| Silicon Motion                         | 3         | 4.55%   |
| Ricoh                                  | 3         | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.03%   |
| Sonix Technology                       | 1         | 1.52%   |
| Primax Electronics                     | 1         | 1.52%   |
| Logitech                               | 1         | 1.52%   |
| globaloptics                           | 1         | 1.52%   |
| Alcor Micro                            | 1         | 1.52%   |
| Acer                                   | 1         | 1.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD               | 5         | 7.58%   |
| Chicony Integrated Camera                  | 3         | 4.55%   |
| Syntek Lenovo EasyCamera                   | 2         | 3.03%   |
| Microdia Sonix USB 2.0 Camera              | 2         | 3.03%   |
| Microdia Integrated Webcam                 | 2         | 3.03%   |
| Microdia Dell Integrated HD Webcam         | 2         | 3.03%   |
| IMC Networks USB2.0 HD UVC WebCam          | 2         | 3.03%   |
| IMC Networks Integrated Camera             | 2         | 3.03%   |
| Apple FaceTime HD Camera                   | 2         | 3.03%   |
| Syntek Integrated Camera                   | 1         | 1.52%   |
| Syntek EasyCamera                          | 1         | 1.52%   |
| Suyin VGA Webcam                           | 1         | 1.52%   |
| Suyin TOSHIBA Web Camera - HD              | 1         | 1.52%   |
| Suyin HP TrueVision HD                     | 1         | 1.52%   |
| Suyin Acer/Lenovo Webcam [CN0316]          | 1         | 1.52%   |
| Suyin 1.3M HD WebCam                       | 1         | 1.52%   |
| Sunplus Laptop_Integrated_Webcam_HD        | 1         | 1.52%   |
| Sunplus Laptop_Integrated_Webcam_FHD       | 1         | 1.52%   |
| Sonix HP Webcam-101                        | 1         | 1.52%   |
| Silicon Motion WebCam SCB-0385N            | 1         | 1.52%   |
| Silicon Motion WebCam SC-10HDD13335N       | 1         | 1.52%   |
| Silicon Motion Real HD WebCam              | 1         | 1.52%   |
| Ricoh Laptop_Integrated_Webcam_FHD         | 1         | 1.52%   |
| Ricoh Integrated Webcam                    | 1         | 1.52%   |
| Ricoh HD Webcam                            | 1         | 1.52%   |
| Realtek MTD camera                         | 1         | 1.52%   |
| Realtek Integrated Webcam HD               | 1         | 1.52%   |
| Realtek Integrated Webcam                  | 1         | 1.52%   |
| Realtek Integrated Camera                  | 1         | 1.52%   |
| Realtek HP Wide Vision HD Camera           | 1         | 1.52%   |
| Realtek HP Truevision HD integrated webcam | 1         | 1.52%   |
| Primax HP HD Webcam [Fixed]                | 1         | 1.52%   |
| Microdia Laptop_Integrated_Webcam_E4HD     | 1         | 1.52%   |
| Microdia Laptop_Integrated_Webcam_2M       | 1         | 1.52%   |
| Microdia Integrated_Webcam_HD              | 1         | 1.52%   |
| Logitech QuickCam Pro 4000                 | 1         | 1.52%   |
| IMC Networks UVC VGA Webcam                | 1         | 1.52%   |
| IMC Networks USB2.0 HD IR UVC WebCam       | 1         | 1.52%   |
| globaloptics Integrated Camera 2M          | 1         | 1.52%   |
| Chicony USB2.0 HD UVC WebCam               | 1         | 1.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 66.67%  |
| Synaptics                  | 2         | 22.22%  |
| Shenzhen Goodix Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 11.11%  |
| Validity Sensors VFS491                           | 1         | 11.11%  |
| Validity Sensors VFS471 Fingerprint Reader        | 1         | 11.11%  |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 11.11%  |
| Validity Sensors Synaptics WBDI                   | 1         | 11.11%  |
| Validity Sensors Fingerprint scanner              | 1         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 11.11%  |
| Shenzhen Goodix  FingerPrint Device               | 1         | 11.11%  |

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
| 0     | 55        | 70.51%  |
| 1     | 19        | 24.36%  |
| 2     | 4         | 5.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 9         | 33.33%  |
| Chipcard              | 8         | 29.63%  |
| Graphics card         | 3         | 11.11%  |
| Storage               | 2         | 7.41%   |
| Multimedia controller | 2         | 7.41%   |
| Net/wireless          | 1         | 3.7%    |
| Card reader           | 1         | 3.7%    |
| Bluetooth             | 1         | 3.7%    |

