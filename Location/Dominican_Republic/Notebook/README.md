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

Total: 120

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Apple         | MacBookPro8,1               | [9ba8148878](https://linux-hardware.org/?probe=9ba8148878) | Dec 25, 2021 |
| Apple         | MacBookPro8,1               | [e110e5c127](https://linux-hardware.org/?probe=e110e5c127) | Dec 25, 2021 |
| Acer          | Aspire 5733Z                | [ea7511ce8d](https://linux-hardware.org/?probe=ea7511ce8d) | Dec 24, 2021 |
| Apple         | MacBookPro8,1               | [8e773bb4e5](https://linux-hardware.org/?probe=8e773bb4e5) | Dec 23, 2021 |
| Apple         | MacBookPro8,1               | [9f084a2062](https://linux-hardware.org/?probe=9f084a2062) | Dec 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9b89720cb4](https://linux-hardware.org/?probe=9b89720cb4) | Dec 14, 2021 |
| Lenovo        | G505s 20255                 | [b32fd5f07f](https://linux-hardware.org/?probe=b32fd5f07f) | Dec 07, 2021 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [d1843d03ba](https://linux-hardware.org/?probe=d1843d03ba) | Dec 04, 2021 |
| Lenovo        | ThinkPad T410 2537N99       | [a77255409f](https://linux-hardware.org/?probe=a77255409f) | Dec 02, 2021 |
| Lenovo        | ThinkPad T410 2537N99       | [ef02c2fb6c](https://linux-hardware.org/?probe=ef02c2fb6c) | Dec 02, 2021 |
| Lenovo        | G505s 20255                 | [4dd5733d57](https://linux-hardware.org/?probe=4dd5733d57) | Nov 20, 2021 |
| Lenovo        | G505s 20255                 | [8d3228452b](https://linux-hardware.org/?probe=8d3228452b) | Nov 20, 2021 |
| Lenovo        | ThinkPad T470 20HD004AUS    | [80fb4514c5](https://linux-hardware.org/?probe=80fb4514c5) | Oct 23, 2021 |
| Dell          | Latitude E6410              | [bd65cdda08](https://linux-hardware.org/?probe=bd65cdda08) | Oct 08, 2021 |
| Apple         | MacBook2,1                  | [7b2dcf44d9](https://linux-hardware.org/?probe=7b2dcf44d9) | Sep 08, 2021 |
| HP            | Pavilion dv6                | [5038083b91](https://linux-hardware.org/?probe=5038083b91) | Sep 07, 2021 |
| Apple         | MacBook2,1                  | [9627be57cd](https://linux-hardware.org/?probe=9627be57cd) | Aug 31, 2021 |
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
| Samsung       | RV420/RV520/RV720/E3530/... | [f1dca4815b](https://linux-hardware.org/?probe=f1dca4815b) | Oct 14, 2020 |
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
| Dell          | Vostro A860                 | [d061339806](https://linux-hardware.org/?probe=d061339806) | Jun 28, 2020 |
| Dell          | Inspiron 1545               | [093c4d226c](https://linux-hardware.org/?probe=093c4d226c) | Jun 28, 2020 |
| HP            | 250 G3                      | [1862b881c0](https://linux-hardware.org/?probe=1862b881c0) | Jun 23, 2020 |
| Acer          | Aspire one 1-431            | [80f65d1ab4](https://linux-hardware.org/?probe=80f65d1ab4) | Jun 23, 2020 |
| Acer          | Aspire one 1-431            | [5994ea3a38](https://linux-hardware.org/?probe=5994ea3a38) | Jun 09, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [4003a55819](https://linux-hardware.org/?probe=4003a55819) | Jun 03, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [db44dbab00](https://linux-hardware.org/?probe=db44dbab00) | May 30, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [0a9a57202f](https://linux-hardware.org/?probe=0a9a57202f) | May 30, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [131d3a17f3](https://linux-hardware.org/?probe=131d3a17f3) | May 30, 2020 |
| Dell          | Vostro A860                 | [35d08abb65](https://linux-hardware.org/?probe=35d08abb65) | May 20, 2020 |
| Dell          | Latitude E6410              | [4e98eb67c5](https://linux-hardware.org/?probe=4e98eb67c5) | May 19, 2020 |
| Dell          | Latitude 3340               | [a8795064a1](https://linux-hardware.org/?probe=a8795064a1) | May 18, 2020 |
| Dell          | Latitude 3340               | [a07d882043](https://linux-hardware.org/?probe=a07d882043) | May 18, 2020 |
| Dell          | Latitude E6430              | [4316261d97](https://linux-hardware.org/?probe=4316261d97) | May 15, 2020 |
| Dell          | Latitude E6430              | [eef205a77d](https://linux-hardware.org/?probe=eef205a77d) | May 14, 2020 |
| HP            | G60                         | [90ec25f151](https://linux-hardware.org/?probe=90ec25f151) | May 13, 2020 |
| HP            | G60                         | [4b065ffe24](https://linux-hardware.org/?probe=4b065ffe24) | May 13, 2020 |
| HP            | G60                         | [0b84216baf](https://linux-hardware.org/?probe=0b84216baf) | May 13, 2020 |
| Dell          | Inspiron 3521               | [1b33a3d155](https://linux-hardware.org/?probe=1b33a3d155) | May 03, 2020 |
| Dell          | Latitude E6430              | [5a74b9f950](https://linux-hardware.org/?probe=5a74b9f950) | May 03, 2020 |
| Dell          | Latitude E6430              | [0eda848aff](https://linux-hardware.org/?probe=0eda848aff) | May 03, 2020 |
| Dell          | Latitude E6430              | [ef841f6edb](https://linux-hardware.org/?probe=ef841f6edb) | May 03, 2020 |
| Dell          | Latitude E6430              | [31e36437f4](https://linux-hardware.org/?probe=31e36437f4) | May 03, 2020 |
| Dell          | Latitude E6410              | [125cc5d7fd](https://linux-hardware.org/?probe=125cc5d7fd) | Apr 26, 2020 |
| Dell          | Latitude 3330               | [4033fca5eb](https://linux-hardware.org/?probe=4033fca5eb) | Mar 22, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | [185bf79f49](https://linux-hardware.org/?probe=185bf79f49) | Feb 08, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | [ee967f9ecb](https://linux-hardware.org/?probe=ee967f9ecb) | Feb 08, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | [cb7950841c](https://linux-hardware.org/?probe=cb7950841c) | Feb 07, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | [ee38ece603](https://linux-hardware.org/?probe=ee38ece603) | Feb 06, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | [3b934e6808](https://linux-hardware.org/?probe=3b934e6808) | Feb 05, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | [3212549df1](https://linux-hardware.org/?probe=3212549df1) | Feb 05, 2020 |
| Lenovo        | Z50-75 80EC                 | [661a8243a3](https://linux-hardware.org/?probe=661a8243a3) | Feb 01, 2020 |
| Lenovo        | Z50-75 80EC                 | [ee353d9346](https://linux-hardware.org/?probe=ee353d9346) | Feb 01, 2020 |
| Apple         | MacBookPro8,1               | [51c3c0bb31](https://linux-hardware.org/?probe=51c3c0bb31) | Jan 07, 2020 |
| Apple         | MacBookPro8,1               | [4df330ed80](https://linux-hardware.org/?probe=4df330ed80) | Jan 07, 2020 |
| Apple         | MacBookPro5,5               | [e4a03527b5](https://linux-hardware.org/?probe=e4a03527b5) | Dec 11, 2019 |
| Toshiba       | Satellite C55-A             | [a760ea9cb2](https://linux-hardware.org/?probe=a760ea9cb2) | Nov 14, 2019 |
| Toshiba       | Satellite C55-A             | [b2477d7154](https://linux-hardware.org/?probe=b2477d7154) | Nov 07, 2019 |
| Apple         | MacBookPro5,5               | [ee99851054](https://linux-hardware.org/?probe=ee99851054) | Oct 21, 2019 |
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
| Ubuntu 20.04        | 15        | 22.06%  |
| Ubuntu 18.04        | 7         | 10.29%  |
| Ubuntu 21.10        | 2         | 2.94%   |
| Pop!_OS 20.10       | 2         | 2.94%   |
| OpenMandriva 4.2    | 2         | 2.94%   |
| Linux Mint 20.3     | 2         | 2.94%   |
| Linux Mint 20.1     | 2         | 2.94%   |
| Debian 11           | 2         | 2.94%   |
| ArcoLinux Rolling   | 2         | 2.94%   |
| Xubuntu 19.10       | 1         | 1.47%   |
| Xubuntu 18.04       | 1         | 1.47%   |
| Void Linux Rolling  | 1         | 1.47%   |
| Ubuntu Budgie 22.04 | 1         | 1.47%   |
| Ubuntu Budgie 21.10 | 1         | 1.47%   |
| Ubuntu Budgie 20.04 | 1         | 1.47%   |
| Ubuntu 21.04        | 1         | 1.47%   |
| Ubuntu 19.04        | 1         | 1.47%   |
| Solus 4.1           | 1         | 1.47%   |
| Pop!_OS 21.04       | 1         | 1.47%   |
| Pop!_OS 20.04       | 1         | 1.47%   |
| OpenMandriva 4.3    | 1         | 1.47%   |
| Manjaro 21.1.2      | 1         | 1.47%   |
| Manjaro 20.1        | 1         | 1.47%   |
| Lubuntu 21.04       | 1         | 1.47%   |
| LMDE 4              | 1         | 1.47%   |
| Linux Mint 20.2     | 1         | 1.47%   |
| Linux Mint 20       | 1         | 1.47%   |
| Linux Mint 19.3     | 1         | 1.47%   |
| Kubuntu 20.04       | 1         | 1.47%   |
| KDE neon 20.04      | 1         | 1.47%   |
| Fedora 34           | 1         | 1.47%   |
| Fedora 33           | 1         | 1.47%   |
| Fedora 32           | 1         | 1.47%   |
| Fedora 31           | 1         | 1.47%   |
| Fedora 30           | 1         | 1.47%   |
| Elementary 6        | 1         | 1.47%   |
| Debian 10           | 1         | 1.47%   |
| Clear Linux 36250   | 1         | 1.47%   |
| Clear Linux 34500   | 1         | 1.47%   |
| Arch Rolling        | 1         | 1.47%   |
| Arch                | 1         | 1.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 25        | 37.31%  |
| Linux Mint    | 7         | 10.45%  |
| Fedora        | 5         | 7.46%   |
| Pop!_OS       | 4         | 5.97%   |
| Ubuntu Budgie | 3         | 4.48%   |
| OpenMandriva  | 3         | 4.48%   |
| Debian        | 3         | 4.48%   |
| Xubuntu       | 2         | 2.99%   |
| Manjaro       | 2         | 2.99%   |
| Clear Linux   | 2         | 2.99%   |
| ArcoLinux     | 2         | 2.99%   |
| Arch          | 2         | 2.99%   |
| Void Linux    | 1         | 1.49%   |
| Solus         | 1         | 1.49%   |
| Lubuntu       | 1         | 1.49%   |
| LMDE          | 1         | 1.49%   |
| Kubuntu       | 1         | 1.49%   |
| KDE neon      | 1         | 1.49%   |
| Elementary    | 1         | 1.49%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-48-generic         | 4         | 5.19%   |
| 5.4.0-42-generic         | 3         | 3.9%    |
| 5.13.0-22-generic        | 3         | 3.9%    |
| 5.4.0-77-generic         | 2         | 2.6%    |
| 5.4.0-52-generic         | 2         | 2.6%    |
| 5.4.0-33-generic         | 2         | 2.6%    |
| 5.3.0-51-generic         | 2         | 2.6%    |
| 5.9.12-xanmod1           | 1         | 1.3%    |
| 5.9.11-arch2-1           | 1         | 1.3%    |
| 5.9.1-arch1-1            | 1         | 1.3%    |
| 5.8.8-arch1-1            | 1         | 1.3%    |
| 5.8.15-301.fc33.x86_64   | 1         | 1.3%    |
| 5.8.12_1                 | 1         | 1.3%    |
| 5.8.0-38-generic         | 1         | 1.3%    |
| 5.7.10-201.fc32.x86_64   | 1         | 1.3%    |
| 5.6.19-158.current       | 1         | 1.3%    |
| 5.4.60-2-MANJARO         | 1         | 1.3%    |
| 5.4.15-200.fc31.x86_64   | 1         | 1.3%    |
| 5.4.0-7642-generic       | 1         | 1.3%    |
| 5.4.0-74-generic         | 1         | 1.3%    |
| 5.4.0-72-generic         | 1         | 1.3%    |
| 5.4.0-39-generic         | 1         | 1.3%    |
| 5.4.0-29-generic         | 1         | 1.3%    |
| 5.4.0-28-generic         | 1         | 1.3%    |
| 5.4.0-26-generic         | 1         | 1.3%    |
| 5.4.0-109-generic        | 1         | 1.3%    |
| 5.4.0-105-generic        | 1         | 1.3%    |
| 5.3.0-61-generic         | 1         | 1.3%    |
| 5.3.0-46-generic         | 1         | 1.3%    |
| 5.3.0-42-generic         | 1         | 1.3%    |
| 5.3.0-28-generic         | 1         | 1.3%    |
| 5.3.0-19-generic         | 1         | 1.3%    |
| 5.17.4-1139.native       | 1         | 1.3%    |
| 5.16.7-desktop-1omv4003  | 1         | 1.3%    |
| 5.13.13-1-MANJARO        | 1         | 1.3%    |
| 5.13.0-7614-generic      | 1         | 1.3%    |
| 5.13.0-35-generic        | 1         | 1.3%    |
| 5.13.0-19-generic        | 1         | 1.3%    |
| 5.12.9-051209-generic    | 1         | 1.3%    |
| 5.12.14-300.fc34.x86_64  | 1         | 1.3%    |
| 5.11.15-arch1-2          | 1         | 1.3%    |
| 5.11.12-desktop-1omv4002 | 1         | 1.3%    |
| 5.11.0-7614-generic      | 1         | 1.3%    |
| 5.11.0-41-generic        | 1         | 1.3%    |
| 5.11.0-40-generic        | 1         | 1.3%    |
| 5.11.0-37-generic        | 1         | 1.3%    |
| 5.11.0-31-generic        | 1         | 1.3%    |
| 5.11.0-27-generic        | 1         | 1.3%    |
| 5.11.0-25-generic        | 1         | 1.3%    |
| 5.11.0-16-generic        | 1         | 1.3%    |
| 5.10.19-1032.native      | 1         | 1.3%    |
| 5.10.14-desktop-1omv4002 | 1         | 1.3%    |
| 5.10.0-9-amd64           | 1         | 1.3%    |
| 5.10.0-10-amd64          | 1         | 1.3%    |
| 5.0.10-300.fc30.x86_64   | 1         | 1.3%    |
| 5.0.0-37-generic         | 1         | 1.3%    |
| 5.0.0-32-generic         | 1         | 1.3%    |
| 5.0.0-31-generic         | 1         | 1.3%    |
| 5.0.0-23-generic         | 1         | 1.3%    |
| 5.0.0-15-generic         | 1         | 1.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 30%     |
| 5.3.0   | 6         | 8.57%   |
| 5.13.0  | 6         | 8.57%   |
| 5.11.0  | 6         | 8.57%   |
| 5.0.0   | 3         | 4.29%   |
| 5.10.0  | 2         | 2.86%   |
| 4.19.0  | 2         | 2.86%   |
| 5.9.12  | 1         | 1.43%   |
| 5.9.11  | 1         | 1.43%   |
| 5.9.1   | 1         | 1.43%   |
| 5.8.8   | 1         | 1.43%   |
| 5.8.15  | 1         | 1.43%   |
| 5.8.12  | 1         | 1.43%   |
| 5.8.0   | 1         | 1.43%   |
| 5.7.10  | 1         | 1.43%   |
| 5.6.19  | 1         | 1.43%   |
| 5.4.60  | 1         | 1.43%   |
| 5.4.15  | 1         | 1.43%   |
| 5.17.4  | 1         | 1.43%   |
| 5.16.7  | 1         | 1.43%   |
| 5.13.13 | 1         | 1.43%   |
| 5.12.9  | 1         | 1.43%   |
| 5.12.14 | 1         | 1.43%   |
| 5.11.15 | 1         | 1.43%   |
| 5.11.12 | 1         | 1.43%   |
| 5.10.19 | 1         | 1.43%   |
| 5.10.14 | 1         | 1.43%   |
| 5.0.10  | 1         | 1.43%   |
| 4.19.8  | 1         | 1.43%   |
| 4.18.0  | 1         | 1.43%   |
| 4.15.0  | 1         | 1.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 23        | 32.86%  |
| 5.11    | 8         | 11.43%  |
| 5.13    | 7         | 10%     |
| 5.3     | 6         | 8.57%   |
| 5.8     | 4         | 5.71%   |
| 5.10    | 4         | 5.71%   |
| 5.0     | 4         | 5.71%   |
| 5.9     | 3         | 4.29%   |
| 4.19    | 3         | 4.29%   |
| 5.12    | 2         | 2.86%   |
| 5.7     | 1         | 1.43%   |
| 5.6     | 1         | 1.43%   |
| 5.17    | 1         | 1.43%   |
| 5.16    | 1         | 1.43%   |
| 4.18    | 1         | 1.43%   |
| 4.15    | 1         | 1.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 65        | 97.01%  |
| i686   | 2         | 2.99%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 31        | 46.27%  |
| KDE5       | 7         | 10.45%  |
| Unknown    | 7         | 10.45%  |
| XFCE       | 6         | 8.96%   |
| X-Cinnamon | 6         | 8.96%   |
| Budgie     | 4         | 5.97%   |
| KDE        | 3         | 4.48%   |
| MATE       | 1         | 1.49%   |
| LXQt       | 1         | 1.49%   |
| dwm        | 1         | 1.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 59        | 88.06%  |
| Wayland | 5         | 7.46%   |
| Unknown | 3         | 4.48%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 42        | 62.69%  |
| SDDM    | 7         | 10.45%  |
| GDM     | 7         | 10.45%  |
| TDM     | 4         | 5.97%   |
| LightDM | 4         | 5.97%   |
| GDM3    | 3         | 4.48%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 35        | 51.47%  |
| es_DO   | 18        | 26.47%  |
| Unknown | 7         | 10.29%  |
| es_ES   | 3         | 4.41%   |
| es_MX   | 2         | 2.94%   |
| en_CA   | 2         | 2.94%   |
| fr_FR   | 1         | 1.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 41        | 61.19%  |
| EFI  | 26        | 38.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 56        | 83.58%  |
| Overlay | 5         | 7.46%   |
| Btrfs   | 4         | 5.97%   |
| Xfs     | 1         | 1.49%   |
| Unknown | 1         | 1.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 44        | 65.67%  |
| GPT     | 18        | 26.87%  |
| MBR     | 5         | 7.46%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 58        | 85.29%  |
| Yes       | 10        | 14.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 46        | 68.66%  |
| Yes       | 21        | 31.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 21        | 31.34%  |
| Lenovo              | 13        | 19.4%   |
| Hewlett-Packard     | 11        | 16.42%  |
| ASUSTek Computer    | 5         | 7.46%   |
| Apple               | 4         | 5.97%   |
| Acer                | 3         | 4.48%   |
| Samsung Electronics | 2         | 2.99%   |
| Toshiba             | 1         | 1.49%   |
| TODOS INDUSTRIAL    | 1         | 1.49%   |
| SAELITE             | 1         | 1.49%   |
| Nuvision            | 1         | 1.49%   |
| MSI                 | 1         | 1.49%   |
| Google              | 1         | 1.49%   |
| Fujitsu             | 1         | 1.49%   |
| EVOO                | 1         | 1.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Dell Latitude E6430                               | 2         | 2.99%   |
| Dell Latitude E6410                               | 2         | 2.99%   |
| Apple MacBookPro8,1                               | 2         | 2.99%   |
| Toshiba Satellite C55-A                           | 1         | 1.49%   |
| TODOS INDUSTRIAL Easytouch_2022_V1                | 1         | 1.49%   |
| Samsung RV420/RV520/RV720/E3530/S3530/E3420/E3520 | 1         | 1.49%   |
| Samsung 905S3G/906S3G/915S3G/9305SG               | 1         | 1.49%   |
| SAELITE ES1AU11                                   | 1         | 1.49%   |
| Nuvision NES11                                    | 1         | 1.49%   |
| MSI CR70 2M/CX70 2OC/CX70 2OD                     | 1         | 1.49%   |
| Lenovo Z50-75 80EC                                | 1         | 1.49%   |
| Lenovo ThinkPad W540 20BHS0GB06                   | 1         | 1.49%   |
| Lenovo ThinkPad T480s 20L7CTO1WW                  | 1         | 1.49%   |
| Lenovo ThinkPad T470 20HD004AUS                   | 1         | 1.49%   |
| Lenovo ThinkPad T410 2537N99                      | 1         | 1.49%   |
| Lenovo ThinkPad P43s 20RH0013US                   | 1         | 1.49%   |
| Lenovo ThinkPad E470 20H1006DUS                   | 1         | 1.49%   |
| Lenovo ThinkBook 14s-IWL 20RM                     | 1         | 1.49%   |
| Lenovo Legion 5 15ARH05 82B5                      | 1         | 1.49%   |
| Lenovo IdeaPad 330S-15IKB 81F5                    | 1         | 1.49%   |
| Lenovo IdeaPad 320-15IKB 80XL                     | 1         | 1.49%   |
| Lenovo G505s 20255                                | 1         | 1.49%   |
| Lenovo G40-70 20369                               | 1         | 1.49%   |
| HP ProBook 6470b                                  | 1         | 1.49%   |
| HP Pavilion ze2000 (EC201UA#ABA)                  | 1         | 1.49%   |
| HP Pavilion Gaming Laptop 15-dk0xxx               | 1         | 1.49%   |
| HP Pavilion dv6                                   | 1         | 1.49%   |
| HP Notebook                                       | 1         | 1.49%   |
| HP Laptop 15-bw0xx                                | 1         | 1.49%   |
| HP G60                                            | 1         | 1.49%   |
| HP ENVY Laptop 13-ad0xx                           | 1         | 1.49%   |
| HP EliteBook 8540w                                | 1         | 1.49%   |
| HP EliteBook 8460p                                | 1         | 1.49%   |
| HP 250 G3                                         | 1         | 1.49%   |
| Google Winky                                      | 1         | 1.49%   |
| Fujitsu LIFEBOOK AH562                            | 1         | 1.49%   |
| EVOO EV-C-116-7                                   | 1         | 1.49%   |
| Dell Vostro A860                                  | 1         | 1.49%   |
| Dell Vostro 5471                                  | 1         | 1.49%   |
| Dell Latitude E6540                               | 1         | 1.49%   |
| Dell Latitude E6530                               | 1         | 1.49%   |
| Dell Latitude E6420                               | 1         | 1.49%   |
| Dell Latitude E5530 non-vPro                      | 1         | 1.49%   |
| Dell Latitude D830                                | 1         | 1.49%   |
| Dell Latitude D620                                | 1         | 1.49%   |
| Dell Latitude 3340                                | 1         | 1.49%   |
| Dell Latitude 3330                                | 1         | 1.49%   |
| Dell Inspiron N5050                               | 1         | 1.49%   |
| Dell Inspiron 5570                                | 1         | 1.49%   |
| Dell Inspiron 5555                                | 1         | 1.49%   |
| Dell Inspiron 5521                                | 1         | 1.49%   |
| Dell Inspiron 3541                                | 1         | 1.49%   |
| Dell Inspiron 3521                                | 1         | 1.49%   |
| Dell Inspiron 1545                                | 1         | 1.49%   |
| ASUS ZenBook Pro Duo UX581GV_UX581GV              | 1         | 1.49%   |
| ASUS X553MA                                       | 1         | 1.49%   |
| ASUS TUF Gaming FX505DV_FX505DV                   | 1         | 1.49%   |
| ASUS T100TA                                       | 1         | 1.49%   |
| ASUS K53E                                         | 1         | 1.49%   |
| Apple MacBookPro5,5                               | 1         | 1.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 12        | 17.91%  |
| Dell Inspiron              | 7         | 10.45%  |
| Lenovo ThinkPad            | 6         | 8.96%   |
| HP Pavilion                | 3         | 4.48%   |
| Acer Aspire                | 3         | 4.48%   |
| Lenovo IdeaPad             | 2         | 2.99%   |
| HP EliteBook               | 2         | 2.99%   |
| Dell Vostro                | 2         | 2.99%   |
| Apple MacBookPro8          | 2         | 2.99%   |
| Toshiba Satellite          | 1         | 1.49%   |
| TODOS INDUSTRIAL Easytouch | 1         | 1.49%   |
| Samsung RV420              | 1         | 1.49%   |
| Samsung 905S3G             | 1         | 1.49%   |
| SAELITE ES1AU11            | 1         | 1.49%   |
| Nuvision NES11             | 1         | 1.49%   |
| MSI CR70                   | 1         | 1.49%   |
| Lenovo Z50-75              | 1         | 1.49%   |
| Lenovo ThinkBook           | 1         | 1.49%   |
| Lenovo Legion              | 1         | 1.49%   |
| Lenovo G505s               | 1         | 1.49%   |
| Lenovo G40-70              | 1         | 1.49%   |
| HP ProBook                 | 1         | 1.49%   |
| HP Notebook                | 1         | 1.49%   |
| HP Laptop                  | 1         | 1.49%   |
| HP G60                     | 1         | 1.49%   |
| HP ENVY                    | 1         | 1.49%   |
| HP 250                     | 1         | 1.49%   |
| Google Winky               | 1         | 1.49%   |
| Fujitsu LIFEBOOK           | 1         | 1.49%   |
| EVOO EV-C-116-7            | 1         | 1.49%   |
| ASUS ZenBook               | 1         | 1.49%   |
| ASUS X553MA                | 1         | 1.49%   |
| ASUS TUF                   | 1         | 1.49%   |
| ASUS T100TA                | 1         | 1.49%   |
| ASUS K53E                  | 1         | 1.49%   |
| Apple MacBookPro5          | 1         | 1.49%   |
| Apple MacBook2             | 1         | 1.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2017 | 8         | 11.94%  |
| 2014 | 8         | 11.94%  |
| 2011 | 8         | 11.94%  |
| 2013 | 7         | 10.45%  |
| 2012 | 7         | 10.45%  |
| 2019 | 5         | 7.46%   |
| 2008 | 4         | 5.97%   |
| 2020 | 3         | 4.48%   |
| 2018 | 3         | 4.48%   |
| 2010 | 3         | 4.48%   |
| 2009 | 3         | 4.48%   |
| 2021 | 2         | 2.99%   |
| 2015 | 2         | 2.99%   |
| 2007 | 2         | 2.99%   |
| 2006 | 1         | 1.49%   |
| 2005 | 1         | 1.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 67        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 66        | 98.51%  |
| Enabled  | 1         | 1.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 66        | 98.51%  |
| Yes  | 1         | 1.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 24        | 35.82%  |
| 4.01-8.0   | 15        | 22.39%  |
| 8.01-16.0  | 10        | 14.93%  |
| 16.01-24.0 | 8         | 11.94%  |
| 1.01-2.0   | 4         | 5.97%   |
| 2.01-3.0   | 3         | 4.48%   |
| 32.01-64.0 | 2         | 2.99%   |
| 24.01-32.0 | 1         | 1.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 29        | 39.73%  |
| 2.01-3.0 | 23        | 31.51%  |
| 3.01-4.0 | 11        | 15.07%  |
| 4.01-8.0 | 6         | 8.22%   |
| 0.51-1.0 | 4         | 5.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 50        | 74.63%  |
| 2      | 17        | 25.37%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 52.24%  |
| No        | 32        | 47.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 85.07%  |
| No        | 10        | 14.93%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 97.01%  |
| No        | 2         | 2.99%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 68.66%  |
| No        | 21        | 31.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Dominican Republic | 67        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Santo Domingo Este         | 40        | 57.14%  |
| Santiago de los Caballeros | 9         | 12.86%  |
| La Romana                  | 2         | 2.86%   |
| Bayahibe                   | 2         | 2.86%   |
| Santa Cruz de Barahona     | 1         | 1.43%   |
| San Pedro de Macorís      | 1         | 1.43%   |
| San Cristobal              | 1         | 1.43%   |
| Nagua                      | 1         | 1.43%   |
| Los Hidalgos               | 1         | 1.43%   |
| Las Terrenas               | 1         | 1.43%   |
| Guaymate                   | 1         | 1.43%   |
| Galvan                     | 1         | 1.43%   |
| Ensanche Ozama             | 1         | 1.43%   |
| El Mamey                   | 1         | 1.43%   |
| Constanza                  | 1         | 1.43%   |
| ConcepciГіn de la Vega   | 1         | 1.43%   |
| Boca Chica                 | 1         | 1.43%   |
| Bavaro                     | 1         | 1.43%   |
| BanГ­                    | 1         | 1.43%   |
| Arroyo Hondo               | 1         | 1.43%   |
| Anton Sanchez              | 1         | 1.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 16        | 21     | 20.25%  |
| Toshiba                   | 10        | 12     | 12.66%  |
| WDC                       | 9         | 11     | 11.39%  |
| Samsung Electronics       | 9         | 10     | 11.39%  |
| SanDisk                   | 8         | 11     | 10.13%  |
| Hitachi                   | 7         | 8      | 8.86%   |
| Unknown                   | 3         | 4      | 3.8%    |
| Kingston                  | 3         | 3      | 3.8%    |
| Transcend                 | 2         | 2      | 2.53%   |
| SK Hynix                  | 2         | 2      | 2.53%   |
| PNY                       | 1         | 1      | 1.27%   |
| OCZ                       | 1         | 1      | 1.27%   |
| Micron/Crucial Technology | 1         | 1      | 1.27%   |
| Micron Technology         | 1         | 1      | 1.27%   |
| LITEONIT                  | 1         | 2      | 1.27%   |
| Intel                     | 1         | 1      | 1.27%   |
| Indilinx                  | 1         | 1      | 1.27%   |
| Hewlett-Packard           | 1         | 1      | 1.27%   |
| FORESEE                   | 1         | 1      | 1.27%   |
| Unknown                   | 1         | 1      | 1.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 2         | 2.47%   |
| Toshiba MQ01ACF050 500GB            | 2         | 2.47%   |
| Toshiba MK3275GSX 320GB             | 2         | 2.47%   |
| Seagate ST9250315AS 250GB           | 2         | 2.47%   |
| Seagate ST500LM000-1EJ162 500GB     | 2         | 2.47%   |
| Seagate ST1000LM049-2GH172 1TB      | 2         | 2.47%   |
| Sandisk NVMe SSD Drive 256GB        | 2         | 2.47%   |
| Samsung SSD 860 EVO 500GB           | 2         | 2.47%   |
| WDC WDS100T2G0A-00JH30 1TB SSD      | 1         | 1.23%   |
| WDC WD5000LPLX-08ZNTT0 500GB        | 1         | 1.23%   |
| WDC WD3200LPVX-75V0TT0 320GB        | 1         | 1.23%   |
| WDC WD3200BEVT-75A23T0 320GB        | 1         | 1.23%   |
| WDC WD2500BEVT-75A23T0 250GB        | 1         | 1.23%   |
| WDC WD1600BEVT-75ZCT1 160GB         | 1         | 1.23%   |
| WDC WD10SPZX-24Z10T0 1TB            | 1         | 1.23%   |
| WDC WD10JPVX-60JC3T1 1TB            | 1         | 1.23%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 1.23%   |
| Unknown MMC Card  16GB              | 1         | 1.23%   |
| Unknown MMC Card  128GB             | 1         | 1.23%   |
| Transcend TS256GSSD340 256GB        | 1         | 1.23%   |
| Transcend TS128GSSD370S 128GB       | 1         | 1.23%   |
| Toshiba NVMe SSD Drive 1024GB       | 1         | 1.23%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1.23%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1.23%   |
| Toshiba MK6475GSX 640GB             | 1         | 1.23%   |
| Toshiba MK3276GSX 320GB             | 1         | 1.23%   |
| Toshiba MK2556GSY 250GB             | 1         | 1.23%   |
| SK Hynix HCG8e  64GB                | 1         | 1.23%   |
| SK Hynix C2S3T/240G 240GB SSD       | 1         | 1.23%   |
| Seagate ST9750420AS 752GB           | 1         | 1.23%   |
| Seagate ST9500325AS 500GB           | 1         | 1.23%   |
| Seagate ST9320325AS 320GB           | 1         | 1.23%   |
| Seagate ST640LM000 HM641JI 640GB    | 1         | 1.23%   |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1.23%   |
| Seagate ST320LT007-9ZV142 320GB     | 1         | 1.23%   |
| Seagate ST2000LM007-1R8174 2TB      | 1         | 1.23%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1.23%   |
| Seagate Expansion+ 2TB              | 1         | 1.23%   |
| Seagate BUP Slim BK 1TB             | 1         | 1.23%   |
| Seagate BUP BK 4TB                  | 1         | 1.23%   |
| SanDisk X110 2.5 7MM 256GB SSD      | 1         | 1.23%   |
| SanDisk SDSSDXP240G 240GB           | 1         | 1.23%   |
| SanDisk SDSSDX120GG25 120GB         | 1         | 1.23%   |
| SanDisk SDSSDH3 512G                | 1         | 1.23%   |
| SanDisk SDSSDA120G 120GB            | 1         | 1.23%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD | 1         | 1.23%   |
| Samsung SSD 860 EVO 1TB             | 1         | 1.23%   |
| Samsung SSD 850 EVO 500GB           | 1         | 1.23%   |
| Samsung SSD 850 EVO 250GB           | 1         | 1.23%   |
| Samsung NVMe SSD Drive 1024GB       | 1         | 1.23%   |
| Samsung MZVLB512HBJQ-000L2 512GB    | 1         | 1.23%   |
| Samsung MZVLB256HAHQ-000L2 256GB    | 1         | 1.23%   |
| Samsung MZMTD128HAFV-000 128GB SSD  | 1         | 1.23%   |
| PNY CS900 240GB SSD                 | 1         | 1.23%   |
| OCZ VERTEX 256GB SSD                | 1         | 1.23%   |
| Micron/Crucial NVMe SSD Drive 1TB   | 1         | 1.23%   |
| Micron NVMe SSD Drive 512GB         | 1         | 1.23%   |
| LITEONIT LCT-128M3S 128GB SSD       | 1         | 1.23%   |
| Kingston SA400S37960G 960GB SSD     | 1         | 1.23%   |
| Kingston SA400S37240G 240GB SSD     | 1         | 1.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 16        | 21     | 40%     |
| Toshiba | 9         | 11     | 22.5%   |
| WDC     | 8         | 10     | 20%     |
| Hitachi | 7         | 8      | 17.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 6         | 9      | 25%     |
| Samsung Electronics | 6         | 7      | 25%     |
| Kingston            | 3         | 3      | 12.5%   |
| Transcend           | 2         | 2      | 8.33%   |
| WDC                 | 1         | 1      | 4.17%   |
| SK Hynix            | 1         | 1      | 4.17%   |
| PNY                 | 1         | 1      | 4.17%   |
| OCZ                 | 1         | 1      | 4.17%   |
| LITEONIT            | 1         | 2      | 4.17%   |
| Hewlett-Packard     | 1         | 1      | 4.17%   |
| FORESEE             | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 38        | 50     | 50.67%  |
| SSD     | 22        | 29     | 29.33%  |
| NVMe    | 9         | 9      | 12%     |
| MMC     | 5         | 6      | 6.67%   |
| Unknown | 1         | 1      | 1.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 56        | 76     | 76.71%  |
| NVMe | 9         | 9      | 12.33%  |
| MMC  | 5         | 6      | 6.85%   |
| SAS  | 3         | 4      | 4.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 42        | 56     | 70%     |
| 0.51-1.0   | 15        | 19     | 25%     |
| 1.01-2.0   | 2         | 2      | 3.33%   |
| 3.01-4.0   | 1         | 2      | 1.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 25        | 35.71%  |
| 251-500        | 14        | 20%     |
| 501-1000       | 11        | 15.71%  |
| 1-20           | 5         | 7.14%   |
| 21-50          | 4         | 5.71%   |
| 51-100         | 4         | 5.71%   |
| 1001-2000      | 3         | 4.29%   |
| Unknown        | 2         | 2.86%   |
| More than 3000 | 1         | 1.43%   |
| 2001-3000      | 1         | 1.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 31        | 40.79%  |
| 21-50     | 17        | 22.37%  |
| 101-250   | 9         | 11.84%  |
| 51-100    | 8         | 10.53%  |
| 251-500   | 3         | 3.95%   |
| 501-1000  | 3         | 3.95%   |
| 1001-2000 | 2         | 2.63%   |
| Unknown   | 2         | 2.63%   |
| 2001-3000 | 1         | 1.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Toshiba MK3276GSX 320GB        | 1         | 1      | 14.29%  |
| Toshiba MK3275GSX 320GB        | 1         | 1      | 14.29%  |
| Seagate ST9750420AS 752GB      | 1         | 1      | 14.29%  |
| Seagate ST2000LM007-1R8174 2TB | 1         | 1      | 14.29%  |
| Hitachi HTS727550A9E364 500GB  | 1         | 1      | 14.29%  |
| Hitachi HTS725032A9A364 320GB  | 1         | 1      | 14.29%  |
| Hitachi HTS547575A9E384 752GB  | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 42.86%  |
| Toshiba | 2         | 2      | 28.57%  |
| Seagate | 2         | 2      | 28.57%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 42.86%  |
| Toshiba | 2         | 2      | 28.57%  |
| Seagate | 2         | 2      | 28.57%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 7      | 100%    |

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
| Detected | 47        | 70     | 67.14%  |
| Works    | 16        | 18     | 22.86%  |
| Malfunc  | 7         | 7      | 10%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 49        | 72.06%  |
| AMD                          | 10        | 14.71%  |
| Samsung Electronics          | 3         | 4.41%   |
| Sandisk                      | 2         | 2.94%   |
| Toshiba America Info Systems | 1         | 1.47%   |
| Nvidia                       | 1         | 1.47%   |
| Micron/Crucial Technology    | 1         | 1.47%   |
| Micron Technology            | 1         | 1.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 9         | 12.33%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 6         | 8.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 6         | 8.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 8.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 5         | 6.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 4.11%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 4.11%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 4.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 4.11%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 3         | 4.11%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 4.11%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 2.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 2         | 2.74%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 2.74%   |
| Toshiba America Info Systems NVMe Controller                                           | 1         | 1.37%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.37%   |
| Sandisk PC SN520 NVMe SSD                                                              | 1         | 1.37%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 1.37%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 1         | 1.37%   |
| Micron Non-Volatile memory controller                                                  | 1         | 1.37%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 1.37%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 1.37%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 1.37%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 1.37%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.37%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 1         | 1.37%   |
| AMD IXP SB4x0 IDE Controller                                                           | 1         | 1.37%   |
| AMD FCH IDE Controller                                                                 | 1         | 1.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 46        | 66.67%  |
| NVMe | 9         | 13.04%  |
| IDE  | 8         | 11.59%  |
| RAID | 6         | 8.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 56        | 83.58%  |
| AMD    | 11        | 16.42%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz               | 2         | 2.99%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 2         | 2.99%   |
| Intel Core i7-2620M CPU @ 2.70GHz               | 2         | 2.99%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 2         | 2.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 2.99%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 2         | 2.99%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 2         | 2.99%   |
| Intel Core i5-2415M CPU @ 2.30GHz               | 2         | 2.99%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 2         | 2.99%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 2         | 2.99%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz     | 1         | 1.49%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz          | 1         | 1.49%   |
| Intel Pentium CPU B950 @ 2.10GHz                | 1         | 1.49%   |
| Intel Genuine CPU U4100 @ 1.30GHz               | 1         | 1.49%   |
| Intel Core i9-9980HK CPU @ 2.40GHz              | 1         | 1.49%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 1.49%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 1         | 1.49%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 1         | 1.49%   |
| Intel Core i7-2640M CPU @ 2.80GHz               | 1         | 1.49%   |
| Intel Core i7 CPU M 620 @ 2.67GHz               | 1         | 1.49%   |
| Intel Core i5-9300H CPU @ 2.40GHz               | 1         | 1.49%   |
| Intel Core i5-7300U CPU @ 2.60GHz               | 1         | 1.49%   |
| Intel Core i5-4300M CPU @ 2.60GHz               | 1         | 1.49%   |
| Intel Core i5-3340M CPU @ 2.70GHz               | 1         | 1.49%   |
| Intel Core i5-3337U CPU @ 1.80GHz               | 1         | 1.49%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 1.49%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 1         | 1.49%   |
| Intel Core i5 CPU M 560 @ 2.67GHz               | 1         | 1.49%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 1         | 1.49%   |
| Intel Core i5 CPU M 460 @ 2.53GHz               | 1         | 1.49%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 1         | 1.49%   |
| Intel Core i3-3227U CPU @ 1.90GHz               | 1         | 1.49%   |
| Intel Core i3-2375M CPU @ 1.50GHz               | 1         | 1.49%   |
| Intel Core i3-2310M CPU @ 2.10GHz               | 1         | 1.49%   |
| Intel Core i3 CPU M 350 @ 2.27GHz               | 1         | 1.49%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz            | 1         | 1.49%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz            | 1         | 1.49%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz            | 1         | 1.49%   |
| Intel Core 2 CPU T7600 @ 2.33GHz                | 1         | 1.49%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                | 1         | 1.49%   |
| Intel Celeron N4120 CPU @ 1.10GHz               | 1         | 1.49%   |
| Intel Celeron CPU N3350 @ 1.10GHz               | 1         | 1.49%   |
| Intel Celeron CPU N3050 @ 1.60GHz               | 1         | 1.49%   |
| Intel Celeron CPU N2840 @ 2.16GHz               | 1         | 1.49%   |
| Intel Celeron CPU N2830 @ 2.16GHz               | 1         | 1.49%   |
| Intel Celeron CPU N2820 @ 2.13GHz               | 1         | 1.49%   |
| Intel Celeron CPU 2970M @ 2.20GHz               | 1         | 1.49%   |
| Intel Atom CPU Z3775 @ 1.46GHz                  | 1         | 1.49%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 1         | 1.49%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx   | 1         | 1.49%   |
| AMD Quad-Core Processor (up to 1.4GHz)          | 1         | 1.49%   |
| AMD Mobile Sempron Processor 3000+              | 1         | 1.49%   |
| AMD A6-3430MX APU with Radeon HD Graphics       | 1         | 1.49%   |
| AMD A4-6210 APU with AMD Radeon R3 Graphics     | 1         | 1.49%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 1         | 1.49%   |
| AMD A10-7300 Radeon R6, 10 Compute Cores 4C+6G  | 1         | 1.49%   |
| AMD A10-5750M APU with Radeon HD Graphics       | 1         | 1.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 20        | 29.85%  |
| Intel Core i7           | 11        | 16.42%  |
| Intel Celeron           | 9         | 13.43%  |
| Intel Core i3           | 5         | 7.46%   |
| Intel Core 2 Duo        | 3         | 4.48%   |
| Intel Core 2            | 2         | 2.99%   |
| AMD Ryzen 7             | 2         | 2.99%   |
| AMD A8                  | 2         | 2.99%   |
| AMD A10                 | 2         | 2.99%   |
| Intel Pentium Dual-Core | 1         | 1.49%   |
| Intel Pentium Dual      | 1         | 1.49%   |
| Intel Pentium           | 1         | 1.49%   |
| Intel Genuine           | 1         | 1.49%   |
| Intel Core i9           | 1         | 1.49%   |
| Intel Atom              | 1         | 1.49%   |
| AMD Quad-Core           | 1         | 1.49%   |
| AMD Mobile Sempron      | 1         | 1.49%   |
| AMD A6                  | 1         | 1.49%   |
| AMD A4                  | 1         | 1.49%   |
| AMD A12                 | 1         | 1.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 48        | 71.64%  |
| 4      | 16        | 23.88%  |
| 8      | 2         | 2.99%   |
| 1      | 1         | 1.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 67        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 41        | 61.19%  |
| 1      | 26        | 38.81%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 65        | 97.01%  |
| 32-bit         | 1         | 1.49%   |
| Unknown        | 1         | 1.49%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 20.9%   |
| 0x206a7    | 8         | 11.94%  |
| 0x306a9    | 6         | 8.96%   |
| 0x806e9    | 4         | 5.97%   |
| 0x1067a    | 4         | 5.97%   |
| 0x806ea    | 3         | 4.48%   |
| 0x40651    | 3         | 4.48%   |
| 0x07030105 | 3         | 4.48%   |
| 0x706a1    | 2         | 2.99%   |
| 0x6f6      | 2         | 2.99%   |
| 0x306c3    | 2         | 2.99%   |
| 0x30678    | 2         | 2.99%   |
| 0x20652    | 2         | 2.99%   |
| 0x806ec    | 1         | 1.49%   |
| 0x6fd      | 1         | 1.49%   |
| 0x506c9    | 1         | 1.49%   |
| 0x406c3    | 1         | 1.49%   |
| 0x20655    | 1         | 1.49%   |
| 0x10676    | 1         | 1.49%   |
| 0x08600103 | 1         | 1.49%   |
| 0x08108102 | 1         | 1.49%   |
| 0x0700010f | 1         | 1.49%   |
| 0x0600611a | 1         | 1.49%   |
| 0x06003106 | 1         | 1.49%   |
| 0x06001119 | 1         | 1.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 12        | 17.91%  |
| SandyBridge   | 8         | 11.94%  |
| IvyBridge     | 8         | 11.94%  |
| Haswell       | 6         | 8.96%   |
| Westmere      | 5         | 7.46%   |
| Silvermont    | 5         | 7.46%   |
| Penryn        | 5         | 7.46%   |
| Puma          | 3         | 4.48%   |
| Goldmont plus | 3         | 4.48%   |
| Core          | 3         | 4.48%   |
| Zen+          | 1         | 1.49%   |
| Zen 2         | 1         | 1.49%   |
| Steamroller   | 1         | 1.49%   |
| Piledriver    | 1         | 1.49%   |
| K8 Hammer     | 1         | 1.49%   |
| K10 Llano     | 1         | 1.49%   |
| Jaguar        | 1         | 1.49%   |
| Goldmont      | 1         | 1.49%   |
| Excavator     | 1         | 1.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 52        | 68.42%  |
| AMD    | 15        | 19.74%  |
| Nvidia | 9         | 11.84%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 9.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 8.64%   |
| Intel UHD Graphics 620                                                                   | 4         | 4.94%   |
| Intel HD Graphics 620                                                                    | 4         | 4.94%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 4.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 4.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 3.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 3.7%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 3.7%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 2.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 2.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 2.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 2.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2.47%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.47%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 2.47%   |
| Nvidia TU117M                                                                            | 1         | 1.23%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 1.23%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 1         | 1.23%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.23%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 1.23%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                            | 1         | 1.23%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.23%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.23%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.23%   |
| Intel HD Graphics 500                                                                    | 1         | 1.23%   |
| Intel Haswell Integrated Graphics Controller                                             | 1         | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.23%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 1.23%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.23%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.23%   |
| AMD Temash [Radeon HD 8250/8280G]                                                        | 1         | 1.23%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 1.23%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 1.23%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 1.23%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.23%   |
| AMD RS480M [Mobility Radeon Xpress 200]                                                  | 1         | 1.23%   |
| AMD Richland [Radeon HD 8650G]                                                           | 1         | 1.23%   |
| AMD Renoir                                                                               | 1         | 1.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.23%   |
| AMD Mullins [Radeon R3 Graphics]                                                         | 1         | 1.23%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 1         | 1.23%   |
| AMD Kaveri [Radeon R6 Graphics]                                                          | 1         | 1.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 45        | 67.16%  |
| 1 x AMD        | 8         | 11.94%  |
| Intel + Nvidia | 4         | 5.97%   |
| 1 x Nvidia     | 3         | 4.48%   |
| Intel + AMD    | 3         | 4.48%   |
| 2 x AMD        | 2         | 2.99%   |
| AMD + Nvidia   | 2         | 2.99%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 60        | 89.55%  |
| Proprietary | 6         | 8.96%   |
| Unknown     | 1         | 1.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 50        | 74.63%  |
| 0.51-1.0   | 6         | 8.96%   |
| 0.01-0.5   | 6         | 8.96%   |
| 1.01-2.0   | 3         | 4.48%   |
| 3.01-4.0   | 2         | 2.99%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 16        | 21.05%  |
| LG Display              | 11        | 14.47%  |
| Samsung Electronics     | 10        | 13.16%  |
| BOE                     | 9         | 11.84%  |
| Chimei Innolux          | 8         | 10.53%  |
| Chi Mei Optoelectronics | 4         | 5.26%   |
| Apple                   | 4         | 5.26%   |
| Dell                    | 3         | 3.95%   |
| Hewlett-Packard         | 2         | 2.63%   |
| ZTR                     | 1         | 1.32%   |
| Westinghouse            | 1         | 1.32%   |
| Vizio                   | 1         | 1.32%   |
| Sony                    | 1         | 1.32%   |
| Philips                 | 1         | 1.32%   |
| PANDA                   | 1         | 1.32%   |
| LG Philips              | 1         | 1.32%   |
| Lenovo                  | 1         | 1.32%   |
| InnoLux Display         | 1         | 1.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 2         | 2.63%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 2.63%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 2.63%   |
| ZTR LCD Monitor ZTR0001 1366x768 256x144mm 11.6-inch                     | 1         | 1.32%   |
| Westinghouse EUM24F1G1 WDT1E64 1920x1080 530x300mm 24.0-inch             | 1         | 1.32%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                      | 1         | 1.32%   |
| Sony TV SNY1703 1360x768 1600x900mm 72.3-inch                            | 1         | 1.32%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch     | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SDC5544 1920x1080 344x194mm 15.5-inch    | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch     | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SAM0B32 1366x768 607x345mm 27.5-inch     | 1         | 1.32%   |
| Philips HDMI TV PHL4650 1280x768 576x324mm 26.0-inch                     | 1         | 1.32%   |
| PANDA LC116LF1L02 NCP000F 1920x1080 256x144mm 11.6-inch                  | 1         | 1.32%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch              | 1         | 1.32%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch             | 1         | 1.32%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 1         | 1.32%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 1         | 1.32%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch              | 1         | 1.32%   |
| LG Display LCD Monitor LGD03AE 1366x768 345x194mm 15.6-inch              | 1         | 1.32%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 1         | 1.32%   |
| LG Display LCD Monitor LGD0357 1600x900 382x215mm 17.3-inch              | 1         | 1.32%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch              | 1         | 1.32%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch              | 1         | 1.32%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch                  | 1         | 1.32%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch         | 1         | 1.32%   |
| Hewlett-Packard E221c HWP3093 1920x1080 497x292mm 22.7-inch              | 1         | 1.32%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch                | 1         | 1.32%   |
| Dell P2212H DELA07E 1920x1080 531x299mm 24.0-inch                        | 1         | 1.32%   |
| Dell P2210H DELD026 1920x1080 480x270mm 21.7-inch                        | 1         | 1.32%   |
| Dell 1707FP DEL4013 1280x1024 340x270mm 17.1-inch                        | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 344x193mm 15.5-inch         | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch         | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 344x194mm 15.5-inch         | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1469 1366x768 309x174mm 14.0-inch          | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1352 1366x768 293x165mm 13.2-inch          | 1         | 1.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 1         | 1.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO1557 1366x768 344x193mm 15.5-inch | 1         | 1.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO1469 1366x768 309x174mm 14.0-inch | 1         | 1.32%   |
| Chi Mei Optoelectronics L08 CMO1511 1024x768 304x228mm 15.0-inch         | 1         | 1.32%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                    | 1         | 1.32%   |
| BOE LCD Monitor BOE085F 3840x1100 340x100mm 14.0-inch                    | 1         | 1.32%   |
| BOE LCD Monitor BOE0791 1920x1080 309x173mm 13.9-inch                    | 1         | 1.32%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                    | 1         | 1.32%   |
| BOE LCD Monitor BOE06B7 1920x1080 294x165mm 13.3-inch                    | 1         | 1.32%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 1         | 1.32%   |
| BOE LCD Monitor BOE0623 1366x768 256x144mm 11.6-inch                     | 1         | 1.32%   |
| BOE LCD Monitor BOE05F0 1366x768 309x173mm 13.9-inch                     | 1         | 1.32%   |
| BOE LCD Monitor BOE05B0 1366x768 309x173mm 13.9-inch                     | 1         | 1.32%   |
| AU Optronics LCD Monitor AUOD0ED 1920x1080 344x193mm 15.5-inch           | 1         | 1.32%   |
| AU Optronics LCD Monitor AUO5544 1280x800 303x189mm 14.1-inch            | 1         | 1.32%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 1         | 1.32%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch            | 1         | 1.32%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 1         | 1.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 33        | 45.83%  |
| 1920x1080 (FHD)  | 20        | 27.78%  |
| 1280x800 (WXGA)  | 7         | 9.72%   |
| 1600x900 (HD+)   | 5         | 6.94%   |
| 3840x2160 (4K)   | 2         | 2.78%   |
| 3840x1100        | 1         | 1.39%   |
| 1360x768         | 1         | 1.39%   |
| 1280x768         | 1         | 1.39%   |
| 1280x1024 (SXGA) | 1         | 1.39%   |
| 1024x768 (XGA)   | 1         | 1.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 34        | 45.33%  |
| 13      | 13        | 17.33%  |
| 14      | 10        | 13.33%  |
| 11      | 6         | 8%      |
| 24      | 2         | 2.67%   |
| 17      | 2         | 2.67%   |
| 72      | 1         | 1.33%   |
| 40      | 1         | 1.33%   |
| 34      | 1         | 1.33%   |
| 31      | 1         | 1.33%   |
| 22      | 1         | 1.33%   |
| 21      | 1         | 1.33%   |
| 20      | 1         | 1.33%   |
| Unknown | 1         | 1.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 63.01%  |
| 201-300     | 14        | 19.18%  |
| 401-500     | 3         | 4.11%   |
| 351-400     | 3         | 4.11%   |
| 501-600     | 2         | 2.74%   |
| 801-900     | 1         | 1.37%   |
| 701-800     | 1         | 1.37%   |
| 601-700     | 1         | 1.37%   |
| 1501-2000   | 1         | 1.37%   |
| Unknown     | 1         | 1.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 55        | 83.33%  |
| 16/10   | 7         | 10.61%  |
| 5/4     | 1         | 1.52%   |
| 4/3     | 1         | 1.52%   |
| 3.40    | 1         | 1.52%   |
| Unknown | 1         | 1.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 45.33%  |
| 81-90          | 17        | 22.67%  |
| 51-60          | 7         | 9.33%   |
| 71-80          | 5         | 6.67%   |
| 201-250        | 4         | 5.33%   |
| 501-1000       | 2         | 2.67%   |
| More than 1000 | 1         | 1.33%   |
| 351-500        | 1         | 1.33%   |
| 151-200        | 1         | 1.33%   |
| 141-150        | 1         | 1.33%   |
| 121-130        | 1         | 1.33%   |
| Unknown        | 1         | 1.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 35        | 48.61%  |
| 121-160       | 20        | 27.78%  |
| 51-100        | 10        | 13.89%  |
| 1-50          | 3         | 4.17%   |
| 161-240       | 2         | 2.78%   |
| More than 240 | 1         | 1.39%   |
| Unknown       | 1         | 1.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 56        | 82.35%  |
| 2     | 9         | 13.24%  |
| 0     | 2         | 2.94%   |
| 3     | 1         | 1.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 34        | 32.38%  |
| Realtek Semiconductor           | 31        | 29.52%  |
| Qualcomm Atheros                | 18        | 17.14%  |
| Broadcom                        | 11        | 10.48%  |
| Qualcomm Atheros Communications | 2         | 1.9%    |
| Marvell Technology Group        | 2         | 1.9%    |
| Broadcom Limited                | 2         | 1.9%    |
| Nvidia                          | 1         | 0.95%   |
| Lenovo                          | 1         | 0.95%   |
| JCM                             | 1         | 0.95%   |
| Dell                            | 1         | 0.95%   |
| AMD                             | 1         | 0.95%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 14        | 10.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 11        | 8.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 6         | 4.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 5         | 3.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 4         | 3.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 3.1%    |
| Intel 82577LM Gigabit Network Connection                                              | 4         | 3.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 3         | 2.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 2.33%   |
| Intel Wireless 7260                                                                   | 3         | 2.33%   |
| Intel Wireless 3165                                                                   | 3         | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.55%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 2         | 1.55%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 1.55%   |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 1.55%   |
| Intel Ethernet Connection I217-LM                                                     | 2         | 1.55%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 1.55%   |
| Intel Centrino Advanced-N 6235                                                        | 2         | 1.55%   |
| Intel Centrino Advanced-N 6200                                                        | 2         | 1.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 2         | 1.55%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                     | 2         | 1.55%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 1.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 0.78%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 1         | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 1         | 0.78%   |
| Realtek 802.11n WLAN Adapter                                                          | 1         | 0.78%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                              | 1         | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1         | 0.78%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                              | 1         | 0.78%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.78%   |
| Nvidia MCP79 Ethernet                                                                 | 1         | 0.78%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 1         | 0.78%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                                  | 1         | 0.78%   |
| Lenovo Thinkpad USB LAN                                                               | 1         | 0.78%   |
| JCM UBA                                                                               | 1         | 0.78%   |
| Intel Wireless 7265                                                                   | 1         | 0.78%   |
| Intel Wireless 3160                                                                   | 1         | 0.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 0.78%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 0.78%   |
| Intel Ethernet Connection I218-LM                                                     | 1         | 0.78%   |
| Intel Ethernet Connection (6) I219-V                                                  | 1         | 0.78%   |
| Intel Ethernet Connection (4) I219-V                                                  | 1         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 1         | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 1         | 0.78%   |
| Intel Centrino Wireless-N 6150                                                        | 1         | 0.78%   |
| Intel Centrino Wireless-N 2230                                                        | 1         | 0.78%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 0.78%   |
| Intel Centrino Wireless-N + WiMAX 6150                                                | 1         | 0.78%   |
| Intel 82579V Gigabit Network Connection                                               | 1         | 0.78%   |
| Dell Wireless 5630 (EVDO-HSPA) Mobile Broadband Mini-Card                             | 1         | 0.78%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                                      | 1         | 0.78%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                               | 1         | 0.78%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                       | 1         | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 47.06%  |
| Qualcomm Atheros                | 16        | 23.53%  |
| Realtek Semiconductor           | 8         | 11.76%  |
| Broadcom                        | 8         | 11.76%  |
| Qualcomm Atheros Communications | 2         | 2.94%   |
| Dell                            | 1         | 1.47%   |
| Broadcom Limited                | 1         | 1.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 5         | 7.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 4         | 5.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 5.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 3         | 4.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 4.35%   |
| Intel Wireless 7260                                                                   | 3         | 4.35%   |
| Intel Wireless 3165                                                                   | 3         | 4.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 2.9%    |
| Qualcomm Atheros AR9271 802.11n                                                       | 2         | 2.9%    |
| Intel Wireless 8265 / 8275                                                            | 2         | 2.9%    |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 2.9%    |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 2.9%    |
| Intel Centrino Advanced-N 6235                                                        | 2         | 2.9%    |
| Intel Centrino Advanced-N 6200                                                        | 2         | 2.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 2         | 2.9%    |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 2.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 1.45%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 1.45%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 1.45%   |
| Realtek 802.11n WLAN Adapter                                                          | 1         | 1.45%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.45%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 1.45%   |
| Intel Wireless 7265                                                                   | 1         | 1.45%   |
| Intel Wireless 3160                                                                   | 1         | 1.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 1.45%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 1.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 1.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 1         | 1.45%   |
| Intel Centrino Wireless-N 6150                                                        | 1         | 1.45%   |
| Intel Centrino Wireless-N 2230                                                        | 1         | 1.45%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 1.45%   |
| Intel Centrino Wireless-N + WiMAX 6150                                                | 1         | 1.45%   |
| Dell Wireless 5630 (EVDO-HSPA) Mobile Broadband Mini-Card                             | 1         | 1.45%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                             | 1         | 1.45%   |
| Broadcom BCM43228 802.11a/b/g/n                                                       | 1         | 1.45%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 1         | 1.45%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller                   | 1         | 1.45%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 1.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 1.45%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 1         | 1.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 27        | 46.55%  |
| Intel                    | 17        | 29.31%  |
| Broadcom                 | 5         | 8.62%   |
| Qualcomm Atheros         | 4         | 6.9%    |
| Marvell Technology Group | 2         | 3.45%   |
| Nvidia                   | 1         | 1.72%   |
| Lenovo                   | 1         | 1.72%   |
| Broadcom Limited         | 1         | 1.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 24.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 18.97%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 10.34%  |
| Intel 82577LM Gigabit Network Connection                          | 4         | 6.9%    |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 3.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.72%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.72%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.72%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.72%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.72%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.72%   |
| Lenovo Thinkpad USB LAN                                           | 1         | 1.72%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.72%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.72%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.72%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.72%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.72%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.72%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.72%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.72%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express  | 1         | 1.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 65        | 52.42%  |
| Ethernet | 57        | 45.97%  |
| Modem    | 2         | 1.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 58        | 64.44%  |
| Ethernet | 32        | 35.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 55        | 82.09%  |
| 1     | 10        | 14.93%  |
| 0     | 2         | 2.99%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 67        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 43.48%  |
| Qualcomm Atheros Communications | 9         | 19.57%  |
| Dell                            | 5         | 10.87%  |
| Apple                           | 4         | 8.7%    |
| IMC Networks                    | 3         | 6.52%   |
| Realtek Semiconductor           | 2         | 4.35%   |
| Broadcom                        | 2         | 4.35%   |
| Hewlett-Packard                 | 1         | 2.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 11        | 23.91%  |
| Qualcomm Atheros  Bluetooth Device             | 4         | 8.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 3         | 6.52%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 3         | 6.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3         | 6.52%   |
| Dell BCM20702A0 Bluetooth Module               | 3         | 6.52%   |
| Apple Bluetooth Host Controller                | 3         | 6.52%   |
| Intel AX200 Bluetooth                          | 2         | 4.35%   |
| IMC Networks Bluetooth Radio                   | 2         | 4.35%   |
| Realtek RTL8723B Bluetooth                     | 1         | 2.17%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 2.17%   |
| Qualcomm Atheros Bluetooth USB Host Controller | 1         | 2.17%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 2.17%   |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 2.17%   |
| IMC Networks Bluetooth                         | 1         | 2.17%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 2.17%   |
| Dell Wireless 360 Bluetooth                    | 1         | 2.17%   |
| Dell Wireless 350 Bluetooth                    | 1         | 2.17%   |
| Broadcom HP Portable SoftSailing               | 1         | 2.17%   |
| Broadcom BCM43142 Bluetooth 4.0                | 1         | 2.17%   |
| Apple Bluetooth HCI                            | 1         | 2.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 54        | 72.97%  |
| AMD    | 12        | 16.22%  |
| Nvidia | 7         | 9.46%   |
| Sony   | 1         | 1.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 10.23%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 9.09%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 7.95%   |
| AMD FCH Azalia Controller                                                                         | 7         | 7.95%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 5.68%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 5.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 3.41%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 3.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 3.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 3.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 3.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 3.41%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 3.41%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 2.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 2.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 2.27%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 2.27%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 2.27%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1         | 1.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 1.14%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.14%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.14%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.14%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.14%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.14%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 1.14%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 1         | 1.14%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.14%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 1.14%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 1.14%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 12        | 36.36%  |
| Samsung Electronics | 8         | 24.24%  |
| Micron Technology   | 5         | 15.15%  |
| Ramaxel Technology  | 2         | 6.06%   |
| Unknown (ABCD)      | 1         | 3.03%   |
| Unknown             | 1         | 3.03%   |
| Sesame              | 1         | 3.03%   |
| Nanya Technology    | 1         | 3.03%   |
| Kingston            | 1         | 3.03%   |
| A-DATA Technology   | 1         | 3.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s                | 2         | 5.71%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                         | 1         | 2.86%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 2.86%   |
| SK Hynix RAM Module 8GB SODIMM DDR3 1600MT/s                        | 1         | 2.86%   |
| SK Hynix RAM Module 2GB SODIMM DDR2 667MT/s                         | 1         | 2.86%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 2.86%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 2.86%   |
| SK Hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s           | 1         | 2.86%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 2.86%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 2.86%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 2.86%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 1         | 2.86%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s          | 1         | 2.86%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 2.86%   |
| SK Hynix RAM H9CCNNNBJTALAR-NUD 4096MB Row Of Chips LPDDR3 1867MT/s | 1         | 2.86%   |
| Sesame RAM S939A2SGS-ITR 8GB SODIMM DDR3 1600MT/s                   | 1         | 2.86%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 1         | 2.86%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s               | 1         | 2.86%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 2.86%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 2.86%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 1         | 2.86%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 1         | 2.86%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 1         | 2.86%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s              | 1         | 2.86%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s              | 1         | 2.86%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 2.86%   |
| Ramaxel RAM RMT3010EC58E8F1333 2GB SODIMM DDR3 1600MT/s             | 1         | 2.86%   |
| Ramaxel RAM RMT1970ED48E8F1066 2GB SODIMM DDR3 1067MT/s             | 1         | 2.86%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4096MB SODIMM DDR3 1600MT/s             | 1         | 2.86%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s               | 1         | 2.86%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s            | 1         | 2.86%   |
| Micron RAM 16ATF2G64HZ-2G3H1 16GB SODIMM DDR4 2400MT/s              | 1         | 2.86%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s              | 1         | 2.86%   |
| A-DATA RAM AD73I1B1674EU 2GB SODIMM DDR3 1334MT/s                   | 1         | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 13        | 50%     |
| DDR4   | 8         | 30.77%  |
| SDRAM  | 2         | 7.69%   |
| LPDDR4 | 1         | 3.85%   |
| LPDDR3 | 1         | 3.85%   |
| DDR2   | 1         | 3.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 25        | 96.15%  |
| Row Of Chips | 1         | 3.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 15        | 48.39%  |
| 8192  | 7         | 22.58%  |
| 2048  | 5         | 16.13%  |
| 16384 | 4         | 12.9%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 11        | 36.67%  |
| 2667  | 5         | 16.67%  |
| 2400  | 4         | 13.33%  |
| 4199  | 2         | 6.67%   |
| 3266  | 1         | 3.33%   |
| 3200  | 1         | 3.33%   |
| 2133  | 1         | 3.33%   |
| 1867  | 1         | 3.33%   |
| 1334  | 1         | 3.33%   |
| 1333  | 1         | 3.33%   |
| 1067  | 1         | 3.33%   |
| 667   | 1         | 3.33%   |

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
| Chicony Electronics                    | 9         | 15.79%  |
| Sunplus Innovation Technology          | 6         | 10.53%  |
| Realtek Semiconductor                  | 6         | 10.53%  |
| Microdia                               | 6         | 10.53%  |
| Suyin                                  | 5         | 8.77%   |
| IMC Networks                           | 5         | 8.77%   |
| Syntek                                 | 4         | 7.02%   |
| Apple                                  | 4         | 7.02%   |
| Silicon Motion                         | 3         | 5.26%   |
| Ricoh                                  | 2         | 3.51%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.51%   |
| Sonix Technology                       | 1         | 1.75%   |
| Primax Electronics                     | 1         | 1.75%   |
| Logitech                               | 1         | 1.75%   |
| Alcor Micro                            | 1         | 1.75%   |
| Acer                                   | 1         | 1.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                               | 4         | 7.02%   |
| Chicony Integrated Camera                                                  | 3         | 5.26%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 3.51%   |
| Microdia Dell Integrated HD Webcam                                         | 2         | 3.51%   |
| IMC Networks Integrated Camera                                             | 2         | 3.51%   |
| Apple FaceTime HD Camera                                                   | 2         | 3.51%   |
| Syntek Integrated Camera                                                   | 1         | 1.75%   |
| Syntek EasyCamera                                                          | 1         | 1.75%   |
| Suyin VGA Webcam                                                           | 1         | 1.75%   |
| Suyin TOSHIBA Web Camera - HD                                              | 1         | 1.75%   |
| Suyin HP TrueVision HD                                                     | 1         | 1.75%   |
| Suyin Acer/Lenovo Webcam [CN0316]                                          | 1         | 1.75%   |
| Suyin 1.3M HD WebCam                                                       | 1         | 1.75%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 1         | 1.75%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 1.75%   |
| Sonix HP Webcam-101                                                        | 1         | 1.75%   |
| Silicon Motion WebCam SCB-0385N                                            | 1         | 1.75%   |
| Silicon Motion WebCam SC-10HDD13335N                                       | 1         | 1.75%   |
| Silicon Motion Real HD WebCam                                              | 1         | 1.75%   |
| Ricoh Integrated Webcam                                                    | 1         | 1.75%   |
| Ricoh HD Webcam                                                            | 1         | 1.75%   |
| Realtek USB2.0 camera                                                      | 1         | 1.75%   |
| Realtek Integrated Webcam HD                                               | 1         | 1.75%   |
| Realtek Integrated Webcam                                                  | 1         | 1.75%   |
| Realtek Integrated Camera                                                  | 1         | 1.75%   |
| Realtek HP Wide Vision HD Camera                                           | 1         | 1.75%   |
| Realtek HP Truevision HD                                                   | 1         | 1.75%   |
| Primax HP HD Webcam [Fixed]                                                | 1         | 1.75%   |
| Microdia Sonix USB 2.0 Camera                                              | 1         | 1.75%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                     | 1         | 1.75%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 1.75%   |
| Microdia Integrated Webcam                                                 | 1         | 1.75%   |
| Logitech QuickCam Pro 4000                                                 | 1         | 1.75%   |
| IMC Networks UVC VGA Webcam                                                | 1         | 1.75%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.75%   |
| IMC Networks USB2.0 HD IR UVC WebCam                                       | 1         | 1.75%   |
| Chicony USB2.0 HD UVC WebCam                                               | 1         | 1.75%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 1.75%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 1.75%   |
| Chicony HP Webcam [2 MP Macro]                                             | 1         | 1.75%   |
| Chicony HP TrueVision HD                                                   | 1         | 1.75%   |
| Chicony FJ Camera                                                          | 1         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 1.75%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 1         | 1.75%   |
| Apple Built-in iSight                                                      | 1         | 1.75%   |
| Alcor Micro USB 2.0 Camera                                                 | 1         | 1.75%   |
| Acer Lenovo EasyCamera                                                     | 1         | 1.75%   |

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
| Broadcom    | 5         | 62.5%   |
| O2 Micro    | 2         | 25%     |
| Alcor Micro | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 25%     |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 12.5%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 46        | 68.66%  |
| 1     | 18        | 26.87%  |
| 2     | 3         | 4.48%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 9         | 37.5%   |
| Chipcard              | 7         | 29.17%  |
| Graphics card         | 3         | 12.5%   |
| Storage               | 1         | 4.17%   |
| Net/wireless          | 1         | 4.17%   |
| Multimedia controller | 1         | 4.17%   |
| Card reader           | 1         | 4.17%   |
| Bluetooth             | 1         | 4.17%   |

