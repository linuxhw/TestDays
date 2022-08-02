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

Total: 110

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04        | 16        | 22.22%  |
| Ubuntu 18.04        | 7         | 9.72%   |
| Ubuntu 21.10        | 2         | 2.78%   |
| Pop!_OS 20.10       | 2         | 2.78%   |
| OpenMandriva 4.2    | 2         | 2.78%   |
| Linux Mint 20.3     | 2         | 2.78%   |
| Linux Mint 20.1     | 2         | 2.78%   |
| Fedora 36           | 2         | 2.78%   |
| Debian 11           | 2         | 2.78%   |
| ArcoLinux Rolling   | 2         | 2.78%   |
| Xubuntu 19.10       | 1         | 1.39%   |
| Xubuntu 18.04       | 1         | 1.39%   |
| Void Linux Rolling  | 1         | 1.39%   |
| Ubuntu Budgie 22.04 | 1         | 1.39%   |
| Ubuntu Budgie 21.10 | 1         | 1.39%   |
| Ubuntu Budgie 20.04 | 1         | 1.39%   |
| Ubuntu 22.04        | 1         | 1.39%   |
| Ubuntu 21.04        | 1         | 1.39%   |
| Ubuntu 19.04        | 1         | 1.39%   |
| Solus 4.1           | 1         | 1.39%   |
| Pop!_OS 21.04       | 1         | 1.39%   |
| Pop!_OS 20.04       | 1         | 1.39%   |
| OpenMandriva 4.3    | 1         | 1.39%   |
| Manjaro 21.1.2      | 1         | 1.39%   |
| Manjaro 20.1        | 1         | 1.39%   |
| Lubuntu 21.04       | 1         | 1.39%   |
| LMDE 4              | 1         | 1.39%   |
| Linux Mint 20.2     | 1         | 1.39%   |
| Linux Mint 20       | 1         | 1.39%   |
| Linux Mint 19.3     | 1         | 1.39%   |
| Kubuntu 20.04       | 1         | 1.39%   |
| KDE neon 20.04      | 1         | 1.39%   |
| Fedora 34           | 1         | 1.39%   |
| Fedora 33           | 1         | 1.39%   |
| Fedora 32           | 1         | 1.39%   |
| Fedora 31           | 1         | 1.39%   |
| Fedora 30           | 1         | 1.39%   |
| Elementary 6        | 1         | 1.39%   |
| Debian 10           | 1         | 1.39%   |
| Clear Linux 36250   | 1         | 1.39%   |
| Clear Linux 34500   | 1         | 1.39%   |
| Arch Rolling        | 1         | 1.39%   |
| Arch                | 1         | 1.39%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 27        | 38.03%  |
| Linux Mint    | 7         | 9.86%   |
| Fedora        | 7         | 9.86%   |
| Pop!_OS       | 4         | 5.63%   |
| Ubuntu Budgie | 3         | 4.23%   |
| OpenMandriva  | 3         | 4.23%   |
| Debian        | 3         | 4.23%   |
| Xubuntu       | 2         | 2.82%   |
| Manjaro       | 2         | 2.82%   |
| Clear Linux   | 2         | 2.82%   |
| ArcoLinux     | 2         | 2.82%   |
| Arch          | 2         | 2.82%   |
| Void Linux    | 1         | 1.41%   |
| Solus         | 1         | 1.41%   |
| Lubuntu       | 1         | 1.41%   |
| LMDE          | 1         | 1.41%   |
| Kubuntu       | 1         | 1.41%   |
| KDE neon      | 1         | 1.41%   |
| Elementary    | 1         | 1.41%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-48-generic         | 4         | 4.88%   |
| 5.4.0-42-generic         | 3         | 3.66%   |
| 5.13.0-22-generic        | 3         | 3.66%   |
| 5.4.0-77-generic         | 2         | 2.44%   |
| 5.4.0-52-generic         | 2         | 2.44%   |
| 5.4.0-33-generic         | 2         | 2.44%   |
| 5.3.0-51-generic         | 2         | 2.44%   |
| 5.9.12-xanmod1           | 1         | 1.22%   |
| 5.9.11-arch2-1           | 1         | 1.22%   |
| 5.9.1-arch1-1            | 1         | 1.22%   |
| 5.8.8-arch1-1            | 1         | 1.22%   |
| 5.8.15-301.fc33.x86_64   | 1         | 1.22%   |
| 5.8.12_1                 | 1         | 1.22%   |
| 5.8.0-38-generic         | 1         | 1.22%   |
| 5.7.10-201.fc32.x86_64   | 1         | 1.22%   |
| 5.6.19-158.current       | 1         | 1.22%   |
| 5.4.60-2-MANJARO         | 1         | 1.22%   |
| 5.4.15-200.fc31.x86_64   | 1         | 1.22%   |
| 5.4.0-7642-generic       | 1         | 1.22%   |
| 5.4.0-74-generic         | 1         | 1.22%   |
| 5.4.0-72-generic         | 1         | 1.22%   |
| 5.4.0-39-generic         | 1         | 1.22%   |
| 5.4.0-29-generic         | 1         | 1.22%   |
| 5.4.0-28-generic         | 1         | 1.22%   |
| 5.4.0-26-generic         | 1         | 1.22%   |
| 5.4.0-109-generic        | 1         | 1.22%   |
| 5.4.0-105-generic        | 1         | 1.22%   |
| 5.3.0-61-generic         | 1         | 1.22%   |
| 5.3.0-46-generic         | 1         | 1.22%   |
| 5.3.0-42-generic         | 1         | 1.22%   |
| 5.3.0-28-generic         | 1         | 1.22%   |
| 5.3.0-19-generic         | 1         | 1.22%   |
| 5.18.13-200.fc36.x86_64  | 1         | 1.22%   |
| 5.18.11-200.fc36.x86_64  | 1         | 1.22%   |
| 5.17.4-1139.native       | 1         | 1.22%   |
| 5.16.7-desktop-1omv4003  | 1         | 1.22%   |
| 5.15.0-41-generic        | 1         | 1.22%   |
| 5.13.13-1-MANJARO        | 1         | 1.22%   |
| 5.13.0-7614-generic      | 1         | 1.22%   |
| 5.13.0-44-generic        | 1         | 1.22%   |
| 5.13.0-35-generic        | 1         | 1.22%   |
| 5.13.0-28-generic        | 1         | 1.22%   |
| 5.13.0-19-generic        | 1         | 1.22%   |
| 5.12.9-051209-generic    | 1         | 1.22%   |
| 5.12.14-300.fc34.x86_64  | 1         | 1.22%   |
| 5.11.15-arch1-2          | 1         | 1.22%   |
| 5.11.12-desktop-1omv4002 | 1         | 1.22%   |
| 5.11.0-7614-generic      | 1         | 1.22%   |
| 5.11.0-41-generic        | 1         | 1.22%   |
| 5.11.0-40-generic        | 1         | 1.22%   |
| 5.11.0-37-generic        | 1         | 1.22%   |
| 5.11.0-31-generic        | 1         | 1.22%   |
| 5.11.0-27-generic        | 1         | 1.22%   |
| 5.11.0-25-generic        | 1         | 1.22%   |
| 5.11.0-16-generic        | 1         | 1.22%   |
| 5.10.19-1032.native      | 1         | 1.22%   |
| 5.10.14-desktop-1omv4002 | 1         | 1.22%   |
| 5.10.0-9-amd64           | 1         | 1.22%   |
| 5.10.0-10-amd64          | 1         | 1.22%   |
| 5.0.10-300.fc30.x86_64   | 1         | 1.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 28%     |
| 5.13.0  | 8         | 10.67%  |
| 5.3.0   | 6         | 8%      |
| 5.11.0  | 6         | 8%      |
| 5.0.0   | 3         | 4%      |
| 5.10.0  | 2         | 2.67%   |
| 4.19.0  | 2         | 2.67%   |
| 5.9.12  | 1         | 1.33%   |
| 5.9.11  | 1         | 1.33%   |
| 5.9.1   | 1         | 1.33%   |
| 5.8.8   | 1         | 1.33%   |
| 5.8.15  | 1         | 1.33%   |
| 5.8.12  | 1         | 1.33%   |
| 5.8.0   | 1         | 1.33%   |
| 5.7.10  | 1         | 1.33%   |
| 5.6.19  | 1         | 1.33%   |
| 5.4.60  | 1         | 1.33%   |
| 5.4.15  | 1         | 1.33%   |
| 5.18.13 | 1         | 1.33%   |
| 5.18.11 | 1         | 1.33%   |
| 5.17.4  | 1         | 1.33%   |
| 5.16.7  | 1         | 1.33%   |
| 5.15.0  | 1         | 1.33%   |
| 5.13.13 | 1         | 1.33%   |
| 5.12.9  | 1         | 1.33%   |
| 5.12.14 | 1         | 1.33%   |
| 5.11.15 | 1         | 1.33%   |
| 5.11.12 | 1         | 1.33%   |
| 5.10.19 | 1         | 1.33%   |
| 5.10.14 | 1         | 1.33%   |
| 5.0.10  | 1         | 1.33%   |
| 4.19.8  | 1         | 1.33%   |
| 4.18.0  | 1         | 1.33%   |
| 4.15.0  | 1         | 1.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 23        | 30.67%  |
| 5.13    | 9         | 12%     |
| 5.11    | 8         | 10.67%  |
| 5.3     | 6         | 8%      |
| 5.8     | 4         | 5.33%   |
| 5.10    | 4         | 5.33%   |
| 5.0     | 4         | 5.33%   |
| 5.9     | 3         | 4%      |
| 4.19    | 3         | 4%      |
| 5.18    | 2         | 2.67%   |
| 5.12    | 2         | 2.67%   |
| 5.7     | 1         | 1.33%   |
| 5.6     | 1         | 1.33%   |
| 5.17    | 1         | 1.33%   |
| 5.16    | 1         | 1.33%   |
| 5.15    | 1         | 1.33%   |
| 4.18    | 1         | 1.33%   |
| 4.15    | 1         | 1.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 69        | 97.18%  |
| i686   | 2         | 2.82%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 34        | 47.89%  |
| KDE5       | 8         | 11.27%  |
| Unknown    | 7         | 9.86%   |
| XFCE       | 6         | 8.45%   |
| X-Cinnamon | 6         | 8.45%   |
| Budgie     | 4         | 5.63%   |
| KDE        | 3         | 4.23%   |
| MATE       | 1         | 1.41%   |
| LXQt       | 1         | 1.41%   |
| DWM        | 1         | 1.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 61        | 85.92%  |
| Wayland | 7         | 9.86%   |
| Unknown | 3         | 4.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 43        | 60.56%  |
| GDM     | 9         | 12.68%  |
| SDDM    | 7         | 9.86%   |
| TDM     | 4         | 5.63%   |
| LightDM | 4         | 5.63%   |
| GDM3    | 4         | 5.63%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 38        | 52.78%  |
| es_DO   | 19        | 26.39%  |
| Unknown | 7         | 9.72%   |
| es_ES   | 3         | 4.17%   |
| es_MX   | 2         | 2.78%   |
| en_CA   | 2         | 2.78%   |
| fr_FR   | 1         | 1.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 42        | 59.15%  |
| EFI  | 29        | 40.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 59        | 83.1%   |
| Overlay | 5         | 7.04%   |
| Btrfs   | 5         | 7.04%   |
| Xfs     | 1         | 1.41%   |
| Unknown | 1         | 1.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 45        | 63.38%  |
| GPT     | 21        | 29.58%  |
| MBR     | 5         | 7.04%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 60        | 83.33%  |
| Yes       | 12        | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 48        | 67.61%  |
| Yes       | 23        | 32.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 22        | 30.99%  |
| Lenovo              | 13        | 18.31%  |
| Hewlett-Packard     | 11        | 15.49%  |
| ASUSTek Computer    | 5         | 7.04%   |
| Acer                | 5         | 7.04%   |
| Apple               | 4         | 5.63%   |
| Samsung Electronics | 2         | 2.82%   |
| Toshiba             | 1         | 1.41%   |
| TODOS INDUSTRIAL    | 1         | 1.41%   |
| SAELITE             | 1         | 1.41%   |
| Nuvision            | 1         | 1.41%   |
| MSI                 | 1         | 1.41%   |
| Google              | 1         | 1.41%   |
| Fujitsu             | 1         | 1.41%   |
| EVOO                | 1         | 1.41%   |
| ECS                 | 1         | 1.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Dell Latitude E6430                               | 2         | 2.82%   |
| Dell Latitude E6410                               | 2         | 2.82%   |
| Apple MacBookPro8,1                               | 2         | 2.82%   |
| Toshiba Satellite C55-A                           | 1         | 1.41%   |
| TODOS INDUSTRIAL Easytouch_2022_V1                | 1         | 1.41%   |
| Samsung RV420/RV520/RV720/E3530/S3530/E3420/E3520 | 1         | 1.41%   |
| Samsung 905S3G/906S3G/915S3G/9305SG               | 1         | 1.41%   |
| SAELITE ES1AU11                                   | 1         | 1.41%   |
| Nuvision NES11                                    | 1         | 1.41%   |
| MSI CR70 2M/CX70 2OC/CX70 2OD                     | 1         | 1.41%   |
| Lenovo Z50-75 80EC                                | 1         | 1.41%   |
| Lenovo ThinkPad W540 20BHS0GB06                   | 1         | 1.41%   |
| Lenovo ThinkPad T480s 20L7CTO1WW                  | 1         | 1.41%   |
| Lenovo ThinkPad T470 20HD004AUS                   | 1         | 1.41%   |
| Lenovo ThinkPad T410 2537N99                      | 1         | 1.41%   |
| Lenovo ThinkPad P43s 20RH0013US                   | 1         | 1.41%   |
| Lenovo ThinkPad E470 20H1006DUS                   | 1         | 1.41%   |
| Lenovo ThinkBook 14s-IWL 20RM                     | 1         | 1.41%   |
| Lenovo Legion 5 15ARH05 82B5                      | 1         | 1.41%   |
| Lenovo IdeaPad 330S-15IKB 81F5                    | 1         | 1.41%   |
| Lenovo IdeaPad 320-15IKB 80XL                     | 1         | 1.41%   |
| Lenovo G505s 20255                                | 1         | 1.41%   |
| Lenovo G40-70 20369                               | 1         | 1.41%   |
| HP ProBook 6470b                                  | 1         | 1.41%   |
| HP Pavilion ze2000 (EC201UA#ABA)                  | 1         | 1.41%   |
| HP Pavilion Gaming Laptop 15-dk0xxx               | 1         | 1.41%   |
| HP Pavilion dv6                                   | 1         | 1.41%   |
| HP Notebook                                       | 1         | 1.41%   |
| HP Laptop 15-bw0xx                                | 1         | 1.41%   |
| HP G60                                            | 1         | 1.41%   |
| HP ENVY Laptop 13-ad0xx                           | 1         | 1.41%   |
| HP EliteBook 8540w                                | 1         | 1.41%   |
| HP EliteBook 8460p                                | 1         | 1.41%   |
| HP 250 G3                                         | 1         | 1.41%   |
| Google Winky                                      | 1         | 1.41%   |
| Fujitsu LIFEBOOK AH562                            | 1         | 1.41%   |
| EVOO EV-C-116-7                                   | 1         | 1.41%   |
| ECS ClassMate                                     | 1         | 1.41%   |
| Dell Vostro A860                                  | 1         | 1.41%   |
| Dell Vostro 5471                                  | 1         | 1.41%   |
| Dell Latitude E6540                               | 1         | 1.41%   |
| Dell Latitude E6530                               | 1         | 1.41%   |
| Dell Latitude E6420                               | 1         | 1.41%   |
| Dell Latitude E5530 non-vPro                      | 1         | 1.41%   |
| Dell Latitude E5440                               | 1         | 1.41%   |
| Dell Latitude D830                                | 1         | 1.41%   |
| Dell Latitude D620                                | 1         | 1.41%   |
| Dell Latitude 3340                                | 1         | 1.41%   |
| Dell Latitude 3330                                | 1         | 1.41%   |
| Dell Inspiron N5050                               | 1         | 1.41%   |
| Dell Inspiron 5570                                | 1         | 1.41%   |
| Dell Inspiron 5555                                | 1         | 1.41%   |
| Dell Inspiron 5521                                | 1         | 1.41%   |
| Dell Inspiron 3541                                | 1         | 1.41%   |
| Dell Inspiron 3521                                | 1         | 1.41%   |
| Dell Inspiron 1545                                | 1         | 1.41%   |
| ASUS ZenBook Pro Duo UX581GV_UX581GV              | 1         | 1.41%   |
| ASUS X553MA                                       | 1         | 1.41%   |
| ASUS TUF Gaming FX505DV_FX505DV                   | 1         | 1.41%   |
| ASUS T100TA                                       | 1         | 1.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 13        | 18.31%  |
| Dell Inspiron              | 7         | 9.86%   |
| Lenovo ThinkPad            | 6         | 8.45%   |
| Acer Aspire                | 5         | 7.04%   |
| HP Pavilion                | 3         | 4.23%   |
| Lenovo IdeaPad             | 2         | 2.82%   |
| HP EliteBook               | 2         | 2.82%   |
| Dell Vostro                | 2         | 2.82%   |
| Apple MacBookPro8          | 2         | 2.82%   |
| Toshiba Satellite          | 1         | 1.41%   |
| TODOS INDUSTRIAL Easytouch | 1         | 1.41%   |
| Samsung RV420              | 1         | 1.41%   |
| Samsung 905S3G             | 1         | 1.41%   |
| SAELITE ES1AU11            | 1         | 1.41%   |
| Nuvision NES11             | 1         | 1.41%   |
| MSI CR70                   | 1         | 1.41%   |
| Lenovo Z50-75              | 1         | 1.41%   |
| Lenovo ThinkBook           | 1         | 1.41%   |
| Lenovo Legion              | 1         | 1.41%   |
| Lenovo G505s               | 1         | 1.41%   |
| Lenovo G40-70              | 1         | 1.41%   |
| HP ProBook                 | 1         | 1.41%   |
| HP Notebook                | 1         | 1.41%   |
| HP Laptop                  | 1         | 1.41%   |
| HP G60                     | 1         | 1.41%   |
| HP ENVY                    | 1         | 1.41%   |
| HP 250                     | 1         | 1.41%   |
| Google Winky               | 1         | 1.41%   |
| Fujitsu LIFEBOOK           | 1         | 1.41%   |
| EVOO EV-C-116-7            | 1         | 1.41%   |
| ECS ClassMate              | 1         | 1.41%   |
| ASUS ZenBook               | 1         | 1.41%   |
| ASUS X553MA                | 1         | 1.41%   |
| ASUS TUF                   | 1         | 1.41%   |
| ASUS T100TA                | 1         | 1.41%   |
| ASUS K53E                  | 1         | 1.41%   |
| Apple MacBookPro5          | 1         | 1.41%   |
| Apple MacBook2             | 1         | 1.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2014 | 9         | 12.68%  |
| 2013 | 8         | 11.27%  |
| 2011 | 8         | 11.27%  |
| 2017 | 7         | 9.86%   |
| 2012 | 7         | 9.86%   |
| 2019 | 6         | 8.45%   |
| 2008 | 4         | 5.63%   |
| 2021 | 3         | 4.23%   |
| 2020 | 3         | 4.23%   |
| 2018 | 3         | 4.23%   |
| 2010 | 3         | 4.23%   |
| 2009 | 3         | 4.23%   |
| 2015 | 2         | 2.82%   |
| 2007 | 2         | 2.82%   |
| 2016 | 1         | 1.41%   |
| 2006 | 1         | 1.41%   |
| 2005 | 1         | 1.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 71        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 69        | 97.18%  |
| Enabled  | 2         | 2.82%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 70        | 98.59%  |
| Yes  | 1         | 1.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 25        | 35.21%  |
| 4.01-8.0   | 17        | 23.94%  |
| 8.01-16.0  | 10        | 14.08%  |
| 16.01-24.0 | 9         | 12.68%  |
| 1.01-2.0   | 4         | 5.63%   |
| 2.01-3.0   | 3         | 4.23%   |
| 32.01-64.0 | 2         | 2.82%   |
| 24.01-32.0 | 1         | 1.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 30        | 38.46%  |
| 2.01-3.0 | 23        | 29.49%  |
| 3.01-4.0 | 14        | 17.95%  |
| 4.01-8.0 | 7         | 8.97%   |
| 0.51-1.0 | 4         | 5.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 54        | 76.06%  |
| 2      | 17        | 23.94%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 50.7%   |
| No        | 35        | 49.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 84.51%  |
| No        | 11        | 15.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 97.18%  |
| No        | 2         | 2.82%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 70.42%  |
| No        | 21        | 29.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Dominican Republic | 71        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Santo Domingo Este         | 45        | 61.64%  |
| Santiago de los Caballeros | 8         | 10.96%  |
| La Romana                  | 4         | 5.48%   |
| Santa Cruz de Barahona     | 2         | 2.74%   |
| Sosua, Cabarete            | 1         | 1.37%   |
| Santo Domingo Oeste        | 1         | 1.37%   |
| Santo Domingo              | 1         | 1.37%   |
| San Pedro de Macorís      | 1         | 1.37%   |
| San Cristobal              | 1         | 1.37%   |
| Punta Cana                 | 1         | 1.37%   |
| Los Hidalgos               | 1         | 1.37%   |
| Guaymate                   | 1         | 1.37%   |
| Constanza                  | 1         | 1.37%   |
| Concepción de la Vega     | 1         | 1.37%   |
| Boca Chica                 | 1         | 1.37%   |
| Baní                      | 1         | 1.37%   |
| Bajos de Haina             | 1         | 1.37%   |
| Alejandro Bass             | 1         | 1.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 17        | 22     | 20.48%  |
| Toshiba                   | 10        | 12     | 12.05%  |
| WDC                       | 9         | 12     | 10.84%  |
| Samsung Electronics       | 9         | 10     | 10.84%  |
| SanDisk                   | 8         | 11     | 9.64%   |
| Hitachi                   | 7         | 8      | 8.43%   |
| Unknown                   | 3         | 4      | 3.61%   |
| SK hynix                  | 3         | 3      | 3.61%   |
| Kingston                  | 3         | 3      | 3.61%   |
| Transcend                 | 2         | 2      | 2.41%   |
| FORESEE                   | 2         | 2      | 2.41%   |
| SPCC                      | 1         | 1      | 1.2%    |
| PNY                       | 1         | 1      | 1.2%    |
| OCZ                       | 1         | 1      | 1.2%    |
| Micron/Crucial Technology | 1         | 1      | 1.2%    |
| Micron Technology         | 1         | 1      | 1.2%    |
| LITEONIT                  | 1         | 2      | 1.2%    |
| Intel                     | 1         | 1      | 1.2%    |
| Indilinx                  | 1         | 1      | 1.2%    |
| Hewlett-Packard           | 1         | 1      | 1.2%    |
| Unknown                   | 1         | 1      | 1.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 2         | 2.35%   |
| Toshiba MQ01ACF050 500GB            | 2         | 2.35%   |
| Toshiba MK3275GSX 320GB             | 2         | 2.35%   |
| Seagate ST9250315AS 250GB           | 2         | 2.35%   |
| Seagate ST500LM000-1EJ162 500GB     | 2         | 2.35%   |
| Seagate ST1000LM049-2GH172 1TB      | 2         | 2.35%   |
| SanDisk NVMe SSD Drive 256GB        | 2         | 2.35%   |
| Samsung SSD 860 EVO 500GB           | 2         | 2.35%   |
| FORESEE 128GB SSD                   | 2         | 2.35%   |
| WDC WDS100T2G0A-00JH30 1TB SSD      | 1         | 1.18%   |
| WDC WD5000LPLX-08ZNTT0 500GB        | 1         | 1.18%   |
| WDC WD3200LPVX-75V0TT0 320GB        | 1         | 1.18%   |
| WDC WD3200BEVT-75A23T0 320GB        | 1         | 1.18%   |
| WDC WD2500BEVT-75A23T0 250GB        | 1         | 1.18%   |
| WDC WD1600BEVT-75ZCT1 160GB         | 1         | 1.18%   |
| WDC WD10SPZX-24Z10T0 1TB            | 1         | 1.18%   |
| WDC WD10JPVX-60JC3T1 1TB            | 1         | 1.18%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 1.18%   |
| Unknown MMC Card  16GB              | 1         | 1.18%   |
| Unknown MMC Card  128GB             | 1         | 1.18%   |
| Transcend TS256GSSD340 256GB        | 1         | 1.18%   |
| Transcend TS128GSSD370S 128GB       | 1         | 1.18%   |
| Toshiba NVMe SSD Drive 1024GB       | 1         | 1.18%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1.18%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1.18%   |
| Toshiba MK6475GSX 640GB             | 1         | 1.18%   |
| Toshiba MK3276GSX 320GB             | 1         | 1.18%   |
| Toshiba MK2556GSY 250GB             | 1         | 1.18%   |
| SPCC Solid State Disk 512GB         | 1         | 1.18%   |
| SK hynix NVMe SSD Drive 256GB       | 1         | 1.18%   |
| SK hynix HCG8e  64GB                | 1         | 1.18%   |
| SK hynix C2S3T/240G 240GB SSD       | 1         | 1.18%   |
| Seagate ST9750420AS 752GB           | 1         | 1.18%   |
| Seagate ST9500325AS 500GB           | 1         | 1.18%   |
| Seagate ST9320325AS 320GB           | 1         | 1.18%   |
| Seagate ST640LM000 HM641JI 640GB    | 1         | 1.18%   |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1.18%   |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 1.18%   |
| Seagate ST320LT007-9ZV142 320GB     | 1         | 1.18%   |
| Seagate ST2000LM007-1R8174 2TB      | 1         | 1.18%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1.18%   |
| Seagate Expansion 1TB               | 1         | 1.18%   |
| Seagate BUP Slim BK 1TB             | 1         | 1.18%   |
| Seagate BUP BK 4TB                  | 1         | 1.18%   |
| SanDisk X110 2.5 7MM 256GB SSD      | 1         | 1.18%   |
| SanDisk SDSSDXP240G 240GB           | 1         | 1.18%   |
| SanDisk SDSSDX120GG25 120GB         | 1         | 1.18%   |
| SanDisk SDSSDH3 512G                | 1         | 1.18%   |
| SanDisk SDSSDA120G 120GB            | 1         | 1.18%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD | 1         | 1.18%   |
| Samsung SSD 860 EVO 1TB             | 1         | 1.18%   |
| Samsung SSD 850 EVO 500GB           | 1         | 1.18%   |
| Samsung SSD 850 EVO 250GB           | 1         | 1.18%   |
| Samsung NVMe SSD Drive 1024GB       | 1         | 1.18%   |
| Samsung MZVLB512HBJQ-000L2 512GB    | 1         | 1.18%   |
| Samsung MZVLB256HAHQ-000L2 256GB    | 1         | 1.18%   |
| Samsung MZMTD128HAFV-000 128GB SSD  | 1         | 1.18%   |
| PNY CS900 240GB SSD                 | 1         | 1.18%   |
| OCZ VERTEX 256GB SSD                | 1         | 1.18%   |
| Micron/Crucial NVMe SSD Drive 1TB   | 1         | 1.18%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 17        | 22     | 41.46%  |
| Toshiba | 9         | 11     | 21.95%  |
| WDC     | 8         | 11     | 19.51%  |
| Hitachi | 7         | 8      | 17.07%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 6         | 9      | 23.08%  |
| Samsung Electronics | 6         | 7      | 23.08%  |
| Kingston            | 3         | 3      | 11.54%  |
| Transcend           | 2         | 2      | 7.69%   |
| FORESEE             | 2         | 2      | 7.69%   |
| WDC                 | 1         | 1      | 3.85%   |
| SPCC                | 1         | 1      | 3.85%   |
| SK hynix            | 1         | 1      | 3.85%   |
| PNY                 | 1         | 1      | 3.85%   |
| OCZ                 | 1         | 1      | 3.85%   |
| LITEONIT            | 1         | 2      | 3.85%   |
| Hewlett-Packard     | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 39        | 52     | 49.37%  |
| SSD     | 24        | 31     | 30.38%  |
| NVMe    | 10        | 10     | 12.66%  |
| MMC     | 5         | 6      | 6.33%   |
| Unknown | 1         | 1      | 1.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 59        | 80     | 76.62%  |
| NVMe | 10        | 10     | 12.99%  |
| MMC  | 5         | 6      | 6.49%   |
| SAS  | 3         | 4      | 3.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 44        | 59     | 69.84%  |
| 0.51-1.0   | 17        | 21     | 26.98%  |
| 3.01-4.0   | 1         | 2      | 1.59%   |
| 1.01-2.0   | 1         | 1      | 1.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 26        | 35.14%  |
| 251-500        | 16        | 21.62%  |
| 501-1000       | 11        | 14.86%  |
| 1-20           | 6         | 8.11%   |
| 21-50          | 4         | 5.41%   |
| 51-100         | 4         | 5.41%   |
| 1001-2000      | 3         | 4.05%   |
| Unknown        | 2         | 2.7%    |
| More than 3000 | 1         | 1.35%   |
| 2001-3000      | 1         | 1.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 32        | 40%     |
| 21-50     | 19        | 23.75%  |
| 101-250   | 9         | 11.25%  |
| 51-100    | 9         | 11.25%  |
| 251-500   | 3         | 3.75%   |
| 501-1000  | 3         | 3.75%   |
| 1001-2000 | 2         | 2.5%    |
| Unknown   | 2         | 2.5%    |
| 2001-3000 | 1         | 1.25%   |

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
| Detected | 48        | 72     | 64.86%  |
| Works    | 18        | 20     | 24.32%  |
| Malfunc  | 8         | 8      | 10.81%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 52        | 71.23%  |
| AMD                          | 11        | 15.07%  |
| Samsung Electronics          | 3         | 4.11%   |
| SanDisk                      | 2         | 2.74%   |
| Toshiba America Info Systems | 1         | 1.37%   |
| SK hynix                     | 1         | 1.37%   |
| Nvidia                       | 1         | 1.37%   |
| Micron/Crucial Technology    | 1         | 1.37%   |
| Micron Technology            | 1         | 1.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 10        | 12.82%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 7         | 8.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 6         | 7.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 7.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 5         | 6.41%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 4         | 5.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 4         | 5.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 3.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 3.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 3.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 3.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 2.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 2         | 2.56%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 2.56%   |
| Toshiba America Info Systems NVMe Controller                                           | 1         | 1.28%   |
| SK hynix Gold P31 SSD                                                                  | 1         | 1.28%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.28%   |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 1.28%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 1.28%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 1         | 1.28%   |
| Micron Non-Volatile memory controller                                                  | 1         | 1.28%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 1.28%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 1.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 1.28%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 1.28%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 1.28%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 1.28%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.28%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.28%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 1         | 1.28%   |
| AMD IXP SB4x0 IDE Controller                                                           | 1         | 1.28%   |
| AMD FCH IDE Controller                                                                 | 1         | 1.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 49        | 66.22%  |
| NVMe | 10        | 13.51%  |
| IDE  | 8         | 10.81%  |
| RAID | 7         | 9.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 59        | 83.1%   |
| AMD    | 12        | 16.9%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-4210U CPU @ 1.70GHz               | 4         | 5.63%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 3         | 4.23%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 2         | 2.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 2         | 2.82%   |
| Intel Core i7-2620M CPU @ 2.70GHz               | 2         | 2.82%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 2         | 2.82%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 2.82%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 2         | 2.82%   |
| Intel Core i5-2415M CPU @ 2.30GHz               | 2         | 2.82%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 2         | 2.82%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz     | 1         | 1.41%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz          | 1         | 1.41%   |
| Intel Pentium CPU B950 @ 2.10GHz                | 1         | 1.41%   |
| Intel Genuine CPU U4100 @ 1.30GHz               | 1         | 1.41%   |
| Intel Core i9-9980HK CPU @ 2.40GHz              | 1         | 1.41%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 1.41%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 1         | 1.41%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 1         | 1.41%   |
| Intel Core i7-2640M CPU @ 2.80GHz               | 1         | 1.41%   |
| Intel Core i7 CPU M 620 @ 2.67GHz               | 1         | 1.41%   |
| Intel Core i5-9300H CPU @ 2.40GHz               | 1         | 1.41%   |
| Intel Core i5-7300U CPU @ 2.60GHz               | 1         | 1.41%   |
| Intel Core i5-4300M CPU @ 2.60GHz               | 1         | 1.41%   |
| Intel Core i5-3340M CPU @ 2.70GHz               | 1         | 1.41%   |
| Intel Core i5-3337U CPU @ 1.80GHz               | 1         | 1.41%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 1.41%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 1         | 1.41%   |
| Intel Core i5 CPU M 560 @ 2.67GHz               | 1         | 1.41%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 1         | 1.41%   |
| Intel Core i5 CPU M 460 @ 2.53GHz               | 1         | 1.41%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 1         | 1.41%   |
| Intel Core i3-3227U CPU @ 1.90GHz               | 1         | 1.41%   |
| Intel Core i3-2375M CPU @ 1.50GHz               | 1         | 1.41%   |
| Intel Core i3-2310M CPU @ 2.10GHz               | 1         | 1.41%   |
| Intel Core i3 CPU M 350 @ 2.27GHz               | 1         | 1.41%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz            | 1         | 1.41%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz            | 1         | 1.41%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz            | 1         | 1.41%   |
| Intel Core 2 CPU T7600 @ 2.33GHz                | 1         | 1.41%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                | 1         | 1.41%   |
| Intel Celeron N4120 CPU @ 1.10GHz               | 1         | 1.41%   |
| Intel Celeron CPU N3350 @ 1.10GHz               | 1         | 1.41%   |
| Intel Celeron CPU N3050 @ 1.60GHz               | 1         | 1.41%   |
| Intel Celeron CPU N2840 @ 2.16GHz               | 1         | 1.41%   |
| Intel Celeron CPU N2830 @ 2.16GHz               | 1         | 1.41%   |
| Intel Celeron CPU N2820 @ 2.13GHz               | 1         | 1.41%   |
| Intel Celeron CPU 2970M @ 2.20GHz               | 1         | 1.41%   |
| Intel Atom CPU Z3775 @ 1.46GHz                  | 1         | 1.41%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 1         | 1.41%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx   | 1         | 1.41%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 1         | 1.41%   |
| AMD Quad-Core Processor (up to 1.4GHz)          | 1         | 1.41%   |
| AMD Mobile Sempron Processor 3000+              | 1         | 1.41%   |
| AMD A6-3430MX APU with Radeon HD Graphics       | 1         | 1.41%   |
| AMD A4-6210 APU with AMD Radeon R3 Graphics     | 1         | 1.41%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 1         | 1.41%   |
| AMD A10-7300 Radeon R6, 10 Compute Cores 4C+6G  | 1         | 1.41%   |
| AMD A10-5750M APU with Radeon HD Graphics       | 1         | 1.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 22        | 30.99%  |
| Intel Core i7           | 11        | 15.49%  |
| Intel Celeron           | 10        | 14.08%  |
| Intel Core i3           | 5         | 7.04%   |
| Intel Core 2 Duo        | 3         | 4.23%   |
| Intel Core 2            | 2         | 2.82%   |
| AMD Ryzen 7             | 2         | 2.82%   |
| AMD A8                  | 2         | 2.82%   |
| AMD A10                 | 2         | 2.82%   |
| Intel Pentium Dual-Core | 1         | 1.41%   |
| Intel Pentium Dual      | 1         | 1.41%   |
| Intel Pentium           | 1         | 1.41%   |
| Intel Genuine           | 1         | 1.41%   |
| Intel Core i9           | 1         | 1.41%   |
| Intel Atom              | 1         | 1.41%   |
| AMD Ryzen 5             | 1         | 1.41%   |
| AMD Quad-Core           | 1         | 1.41%   |
| AMD Mobile Sempron      | 1         | 1.41%   |
| AMD A6                  | 1         | 1.41%   |
| AMD A4                  | 1         | 1.41%   |
| AMD A12                 | 1         | 1.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 51        | 71.83%  |
| 4      | 16        | 22.54%  |
| 8      | 2         | 2.82%   |
| 6      | 1         | 1.41%   |
| 1      | 1         | 1.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 71        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 44        | 61.97%  |
| 1      | 27        | 38.03%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 69        | 97.18%  |
| 32-bit         | 1         | 1.41%   |
| Unknown        | 1         | 1.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 19.72%  |
| 0x206a7    | 8         | 11.27%  |
| 0x306a9    | 6         | 8.45%   |
| 0x40651    | 5         | 7.04%   |
| 0x806e9    | 4         | 5.63%   |
| 0x1067a    | 4         | 5.63%   |
| 0x806ea    | 3         | 4.23%   |
| 0x706a1    | 3         | 4.23%   |
| 0x07030105 | 3         | 4.23%   |
| 0x6f6      | 2         | 2.82%   |
| 0x306c3    | 2         | 2.82%   |
| 0x30678    | 2         | 2.82%   |
| 0x20652    | 2         | 2.82%   |
| 0x806ec    | 1         | 1.41%   |
| 0x6fd      | 1         | 1.41%   |
| 0x506c9    | 1         | 1.41%   |
| 0x406c3    | 1         | 1.41%   |
| 0x20655    | 1         | 1.41%   |
| 0x10676    | 1         | 1.41%   |
| 0x08608102 | 1         | 1.41%   |
| 0x08600103 | 1         | 1.41%   |
| 0x08108102 | 1         | 1.41%   |
| 0x0700010f | 1         | 1.41%   |
| 0x0600611a | 1         | 1.41%   |
| 0x06003106 | 1         | 1.41%   |
| 0x06001119 | 1         | 1.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 12        | 16.9%   |
| SandyBridge   | 8         | 11.27%  |
| IvyBridge     | 8         | 11.27%  |
| Haswell       | 8         | 11.27%  |
| Westmere      | 5         | 7.04%   |
| Silvermont    | 5         | 7.04%   |
| Penryn        | 5         | 7.04%   |
| Goldmont plus | 4         | 5.63%   |
| Puma          | 3         | 4.23%   |
| Core          | 3         | 4.23%   |
| Zen+          | 1         | 1.41%   |
| Zen 2         | 1         | 1.41%   |
| Steamroller   | 1         | 1.41%   |
| Piledriver    | 1         | 1.41%   |
| K8 Hammer     | 1         | 1.41%   |
| K10 Llano     | 1         | 1.41%   |
| Jaguar        | 1         | 1.41%   |
| Goldmont      | 1         | 1.41%   |
| Excavator     | 1         | 1.41%   |
| Unknown       | 1         | 1.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 55        | 68.75%  |
| AMD    | 16        | 20%     |
| Nvidia | 9         | 11.25%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 9.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 8.24%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 5.88%   |
| Intel UHD Graphics 620                                                                   | 4         | 4.71%   |
| Intel HD Graphics 620                                                                    | 4         | 4.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 4.71%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 4.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 4.71%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 3.53%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 2.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 2.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 2.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 2.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2.35%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.35%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 2.35%   |
| Nvidia TU117M                                                                            | 1         | 1.18%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 1.18%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 1         | 1.18%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.18%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 1.18%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                            | 1         | 1.18%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.18%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.18%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.18%   |
| Intel HD Graphics 500                                                                    | 1         | 1.18%   |
| Intel Haswell Integrated Graphics Controller                                             | 1         | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.18%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 1.18%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.18%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.18%   |
| AMD Temash [Radeon HD 8250/8280G]                                                        | 1         | 1.18%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 1.18%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 1.18%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 1.18%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.18%   |
| AMD RS480M [Mobility Radeon Xpress 200]                                                  | 1         | 1.18%   |
| AMD Richland [Radeon HD 8650G]                                                           | 1         | 1.18%   |
| AMD Renoir                                                                               | 1         | 1.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.18%   |
| AMD Mullins [Radeon R3 Graphics]                                                         | 1         | 1.18%   |
| AMD Lucienne                                                                             | 1         | 1.18%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 1         | 1.18%   |
| AMD Kaveri [Radeon R6 Graphics]                                                          | 1         | 1.18%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 48        | 67.61%  |
| 1 x AMD        | 9         | 12.68%  |
| Intel + Nvidia | 4         | 5.63%   |
| 1 x Nvidia     | 3         | 4.23%   |
| Intel + AMD    | 3         | 4.23%   |
| 2 x AMD        | 2         | 2.82%   |
| AMD + Nvidia   | 2         | 2.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 64        | 90.14%  |
| Proprietary | 6         | 8.45%   |
| Unknown     | 1         | 1.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 53        | 74.65%  |
| 0.01-0.5   | 7         | 9.86%   |
| 0.51-1.0   | 6         | 8.45%   |
| 1.01-2.0   | 3         | 4.23%   |
| 3.01-4.0   | 2         | 2.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 17        | 20.99%  |
| LG Display              | 11        | 13.58%  |
| BOE                     | 11        | 13.58%  |
| Samsung Electronics     | 10        | 12.35%  |
| Chimei Innolux          | 8         | 9.88%   |
| Dell                    | 4         | 4.94%   |
| Chi Mei Optoelectronics | 4         | 4.94%   |
| Apple                   | 4         | 4.94%   |
| Hewlett-Packard         | 2         | 2.47%   |
| ZTR                     | 1         | 1.23%   |
| Westinghouse            | 1         | 1.23%   |
| Vizio                   | 1         | 1.23%   |
| Sony                    | 1         | 1.23%   |
| Philips                 | 1         | 1.23%   |
| PANDA                   | 1         | 1.23%   |
| LG Philips              | 1         | 1.23%   |
| Lenovo                  | 1         | 1.23%   |
| KDC                     | 1         | 1.23%   |
| InnoLux Display         | 1         | 1.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 2.47%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 2.47%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 2.47%   |
| ZTR LCD Monitor ZTR0001 1366x768 256x144mm 11.6-inch                     | 1         | 1.23%   |
| Westinghouse EUM24F1G1 WDT1E64 1920x1080 530x300mm 24.0-inch             | 1         | 1.23%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                      | 1         | 1.23%   |
| Sony TV SNY1703 1360x768 1600x900mm 72.3-inch                            | 1         | 1.23%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch     | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SDC5544 1920x1080 344x194mm 15.5-inch    | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch     | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SAM0B32 1366x768 610x350mm 27.7-inch     | 1         | 1.23%   |
| Philips PHL 15"XGATV PHL4650 1024x768 304x228mm 15.0-inch                | 1         | 1.23%   |
| PANDA LC116LF1L02 NCP000F 1920x1080 256x144mm 11.6-inch                  | 1         | 1.23%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch             | 1         | 1.23%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 1         | 1.23%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 1         | 1.23%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD03AE 1366x768 345x194mm 15.6-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD0357 1600x900 382x215mm 17.3-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch              | 1         | 1.23%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch                  | 1         | 1.23%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                     | 1         | 1.23%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch         | 1         | 1.23%   |
| Hewlett-Packard E221c HWP3093 1920x1080 497x292mm 22.7-inch              | 1         | 1.23%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch                | 1         | 1.23%   |
| Dell P2212H DELA07E 1920x1080 531x299mm 24.0-inch                        | 1         | 1.23%   |
| Dell P2210H DELD026 1920x1080 477x268mm 21.5-inch                        | 1         | 1.23%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                        | 1         | 1.23%   |
| Dell 1707FP DEL4013 1280x1024 338x270mm 17.0-inch                        | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 344x193mm 15.5-inch         | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch         | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 344x194mm 15.5-inch         | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN1469 1366x768 309x174mm 14.0-inch          | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN1352 1366x768 293x165mm 13.2-inch          | 1         | 1.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 1         | 1.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1557 1366x768 344x193mm 15.5-inch | 1         | 1.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1469 1366x768 309x174mm 14.0-inch | 1         | 1.23%   |
| Chi Mei Optoelectronics L08 CMO1511 1024x768 304x228mm 15.0-inch         | 1         | 1.23%   |
| BOE LCD Monitor BOE0A56 1920x1080 344x194mm 15.5-inch                    | 1         | 1.23%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                    | 1         | 1.23%   |
| BOE LCD Monitor BOE085F 3840x1100 340x100mm 14.0-inch                    | 1         | 1.23%   |
| BOE LCD Monitor BOE0791 1920x1080 309x173mm 13.9-inch                    | 1         | 1.23%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                    | 1         | 1.23%   |
| BOE LCD Monitor BOE06B7 1920x1080 294x165mm 13.3-inch                    | 1         | 1.23%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE0623 1366x768 256x144mm 11.6-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE05F6 1366x768 309x173mm 13.9-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE05F0 1366x768 309x173mm 13.9-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE05B0 1366x768 309x173mm 13.9-inch                     | 1         | 1.23%   |
| AU Optronics LCD Monitor AUOD0ED 1920x1080 344x193mm 15.5-inch           | 1         | 1.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 36        | 46.75%  |
| 1920x1080 (FHD)  | 21        | 27.27%  |
| 1280x800 (WXGA)  | 7         | 9.09%   |
| 1600x900 (HD+)   | 5         | 6.49%   |
| 3840x2160 (4K)   | 2         | 2.6%    |
| 1280x1024 (SXGA) | 2         | 2.6%    |
| 3840x1100        | 1         | 1.3%    |
| 1360x768         | 1         | 1.3%    |
| 1280x768         | 1         | 1.3%    |
| 1024x768 (XGA)   | 1         | 1.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 36        | 45%     |
| 13      | 14        | 17.5%   |
| 14      | 10        | 12.5%   |
| 11      | 7         | 8.75%   |
| 24      | 2         | 2.5%    |
| 17      | 2         | 2.5%    |
| 72      | 1         | 1.25%   |
| 40      | 1         | 1.25%   |
| 34      | 1         | 1.25%   |
| 31      | 1         | 1.25%   |
| 22      | 1         | 1.25%   |
| 21      | 1         | 1.25%   |
| 20      | 1         | 1.25%   |
| 19      | 1         | 1.25%   |
| Unknown | 1         | 1.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 49        | 62.82%  |
| 201-300     | 15        | 19.23%  |
| 351-400     | 4         | 5.13%   |
| 401-500     | 3         | 3.85%   |
| 501-600     | 2         | 2.56%   |
| 801-900     | 1         | 1.28%   |
| 701-800     | 1         | 1.28%   |
| 601-700     | 1         | 1.28%   |
| 1501-2000   | 1         | 1.28%   |
| Unknown     | 1         | 1.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 59        | 83.1%   |
| 16/10   | 7         | 9.86%   |
| 5/4     | 2         | 2.82%   |
| 4/3     | 1         | 1.41%   |
| 3.40    | 1         | 1.41%   |
| Unknown | 1         | 1.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 36        | 45%     |
| 81-90          | 18        | 22.5%   |
| 51-60          | 8         | 10%     |
| 71-80          | 5         | 6.25%   |
| 201-250        | 4         | 5%      |
| 151-200        | 2         | 2.5%    |
| 501-1000       | 2         | 2.5%    |
| More than 1000 | 1         | 1.25%   |
| 351-500        | 1         | 1.25%   |
| 141-150        | 1         | 1.25%   |
| 121-130        | 1         | 1.25%   |
| Unknown        | 1         | 1.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 37        | 48.05%  |
| 121-160       | 22        | 28.57%  |
| 51-100        | 11        | 14.29%  |
| 1-50          | 3         | 3.9%    |
| 161-240       | 2         | 2.6%    |
| More than 240 | 1         | 1.3%    |
| Unknown       | 1         | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 59        | 81.94%  |
| 2     | 10        | 13.89%  |
| 0     | 2         | 2.78%   |
| 3     | 1         | 1.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 31.53%  |
| Realtek Semiconductor           | 34        | 30.63%  |
| Qualcomm Atheros                | 19        | 17.12%  |
| Broadcom                        | 11        | 9.91%   |
| Qualcomm Atheros Communications | 2         | 1.8%    |
| Marvell Technology Group        | 2         | 1.8%    |
| Broadcom Limited                | 2         | 1.8%    |
| Nvidia                          | 1         | 0.9%    |
| MediaTek                        | 1         | 0.9%    |
| Lenovo                          | 1         | 0.9%    |
| JCM                             | 1         | 0.9%    |
| Dell                            | 1         | 0.9%    |
| AMD                             | 1         | 0.9%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 16        | 11.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 11        | 8.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 6         | 4.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 5         | 3.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 5         | 3.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 2.94%   |
| Intel Wireless 7260                                                                   | 4         | 2.94%   |
| Intel 82577LM Gigabit Network Connection                                              | 4         | 2.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 3         | 2.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 2.21%   |
| Intel Wireless 3165                                                                   | 3         | 2.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 2         | 1.47%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 2         | 1.47%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 1.47%   |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 1.47%   |
| Intel Ethernet Connection I218-LM                                                     | 2         | 1.47%   |
| Intel Ethernet Connection I217-LM                                                     | 2         | 1.47%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 1.47%   |
| Intel Centrino Advanced-N 6235                                                        | 2         | 1.47%   |
| Intel Centrino Advanced-N 6200                                                        | 2         | 1.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 2         | 1.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                     | 2         | 1.47%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 0.74%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.74%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 1         | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 1         | 0.74%   |
| Realtek 802.11n WLAN Adapter                                                          | 1         | 0.74%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                              | 1         | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1         | 0.74%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                              | 1         | 0.74%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.74%   |
| Nvidia MCP79 Ethernet                                                                 | 1         | 0.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 1         | 0.74%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 1         | 0.74%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                                  | 1         | 0.74%   |
| Lenovo Thinkpad LAN                                                                   | 1         | 0.74%   |
| JCM UBA                                                                               | 1         | 0.74%   |
| Intel Wireless 7265                                                                   | 1         | 0.74%   |
| Intel Wireless 3160                                                                   | 1         | 0.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 0.74%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 0.74%   |
| Intel Ethernet Connection (6) I219-V                                                  | 1         | 0.74%   |
| Intel Ethernet Connection (4) I219-V                                                  | 1         | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 1         | 0.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 0.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 1         | 0.74%   |
| Intel Centrino Wireless-N 6150                                                        | 1         | 0.74%   |
| Intel Centrino Wireless-N 2230                                                        | 1         | 0.74%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 0.74%   |
| Intel Centrino Wireless-N + WiMAX 6150                                                | 1         | 0.74%   |
| Intel 82579V Gigabit Network Connection                                               | 1         | 0.74%   |
| Dell Wireless 5630 (EVDO-HSPA) Mobile Broadband Mini-Card                             | 1         | 0.74%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                                      | 1         | 0.74%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                               | 1         | 0.74%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 45.83%  |
| Qualcomm Atheros                | 17        | 23.61%  |
| Realtek Semiconductor           | 9         | 12.5%   |
| Broadcom                        | 8         | 11.11%  |
| Qualcomm Atheros Communications | 2         | 2.78%   |
| MediaTek                        | 1         | 1.39%   |
| Dell                            | 1         | 1.39%   |
| Broadcom Limited                | 1         | 1.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 5         | 6.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 5         | 6.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 5.48%   |
| Intel Wireless 7260                                                                   | 4         | 5.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 3         | 4.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 4.11%   |
| Intel Wireless 3165                                                                   | 3         | 4.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 2.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 2         | 2.74%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 2         | 2.74%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 2.74%   |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 2.74%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 2.74%   |
| Intel Centrino Advanced-N 6235                                                        | 2         | 2.74%   |
| Intel Centrino Advanced-N 6200                                                        | 2         | 2.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 2         | 2.74%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 2.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 1.37%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 1.37%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 1.37%   |
| Realtek 802.11n WLAN Adapter                                                          | 1         | 1.37%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.37%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 1.37%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 1         | 1.37%   |
| Intel Wireless 7265                                                                   | 1         | 1.37%   |
| Intel Wireless 3160                                                                   | 1         | 1.37%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 1.37%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 1.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 1.37%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 1         | 1.37%   |
| Intel Centrino Wireless-N 6150                                                        | 1         | 1.37%   |
| Intel Centrino Wireless-N 2230                                                        | 1         | 1.37%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 1.37%   |
| Intel Centrino Wireless-N + WiMAX 6150                                                | 1         | 1.37%   |
| Dell Wireless 5630 (EVDO-HSPA) Mobile Broadband Mini-Card                             | 1         | 1.37%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                             | 1         | 1.37%   |
| Broadcom BCM43228 802.11a/b/g/n                                                       | 1         | 1.37%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 1         | 1.37%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller                   | 1         | 1.37%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 1.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 1.37%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 1         | 1.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 29        | 47.54%  |
| Intel                    | 18        | 29.51%  |
| Broadcom                 | 5         | 8.2%    |
| Qualcomm Atheros         | 4         | 6.56%   |
| Marvell Technology Group | 2         | 3.28%   |
| Nvidia                   | 1         | 1.64%   |
| Lenovo                   | 1         | 1.64%   |
| Broadcom Limited         | 1         | 1.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 26.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 18.03%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 9.84%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 6.56%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 3.28%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.28%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 3.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.64%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.64%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.64%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.64%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.64%   |
| Lenovo Thinkpad LAN                                               | 1         | 1.64%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.64%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.64%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.64%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.64%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.64%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.64%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.64%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express  | 1         | 1.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 69        | 52.67%  |
| Ethernet | 60        | 45.8%   |
| Modem    | 2         | 1.53%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 57        | 77.03%  |
| Ethernet | 17        | 22.97%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 58        | 81.69%  |
| 1     | 11        | 15.49%  |
| 0     | 2         | 2.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 71        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 42%     |
| Qualcomm Atheros Communications | 9         | 18%     |
| Dell                            | 5         | 10%     |
| Apple                           | 4         | 8%      |
| Realtek Semiconductor           | 3         | 6%      |
| IMC Networks                    | 3         | 6%      |
| Lite-On Technology              | 2         | 4%      |
| Broadcom                        | 2         | 4%      |
| Hewlett-Packard                 | 1         | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 12        | 24%     |
| Qualcomm Atheros  Bluetooth Device             | 4         | 8%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 3         | 6%      |
| Intel Centrino Bluetooth Wireless Transceiver  | 3         | 6%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3         | 6%      |
| Dell BCM20702A0 Bluetooth Module               | 3         | 6%      |
| Apple Bluetooth Host Controller                | 3         | 6%      |
| Intel AX200 Bluetooth                          | 2         | 4%      |
| IMC Networks Bluetooth Radio                   | 2         | 4%      |
| Realtek RTL8723B Bluetooth                     | 1         | 2%      |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 2%      |
| Realtek Bluetooth Radio                        | 1         | 2%      |
| Qualcomm Atheros Bluetooth USB Host Controller | 1         | 2%      |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 2%      |
| Lite-On Wireless_Device                        | 1         | 2%      |
| Lite-On Atheros AR3012 Bluetooth               | 1         | 2%      |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 2%      |
| IMC Networks Bluetooth                         | 1         | 2%      |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 2%      |
| Dell Wireless 360 Bluetooth                    | 1         | 2%      |
| Dell Wireless 350 Bluetooth                    | 1         | 2%      |
| Broadcom HP Portable SoftSailing               | 1         | 2%      |
| Broadcom BCM43142 Bluetooth 4.0                | 1         | 2%      |
| Apple Bluetooth HCI                            | 1         | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 57        | 73.08%  |
| AMD    | 13        | 16.67%  |
| Nvidia | 7         | 8.97%   |
| Sony   | 1         | 1.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 9.47%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 8.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 7.37%   |
| AMD FCH Azalia Controller                                                                         | 7         | 7.37%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 5.26%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 5.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 5.26%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 5.26%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 4.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 3.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 3.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 3.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 3.16%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 3.16%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 2.11%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 2.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 2.11%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.11%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 2.11%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1         | 1.05%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 1.05%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.05%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 1.05%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.05%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.05%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.05%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.05%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.05%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 1.05%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 1         | 1.05%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.05%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 1.05%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 1.05%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 13        | 35.14%  |
| Samsung Electronics | 9         | 24.32%  |
| Micron Technology   | 5         | 13.51%  |
| Ramaxel Technology  | 2         | 5.41%   |
| Kingston            | 2         | 5.41%   |
| Unknown (ABCD)      | 1         | 2.7%    |
| Unknown             | 1         | 2.7%    |
| Sesame              | 1         | 2.7%    |
| Nanya Technology    | 1         | 2.7%    |
| A-DATA Technology   | 1         | 2.7%    |
| Unknown             | 1         | 2.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 5.13%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s             | 2         | 5.13%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 2.56%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 1         | 2.56%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 2.56%   |
| SK hynix RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 2.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.56%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.56%   |
| SK hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 2.56%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.56%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.56%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 2.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.56%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2400MT/s        | 1         | 2.56%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 2.56%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.56%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 2.56%   |
| Sesame RAM S939A2SGS-ITR 8192MB SODIMM DDR3 1600MT/s             | 1         | 2.56%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 2.56%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 1         | 2.56%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.56%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 2.56%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 1         | 2.56%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s        | 1         | 2.56%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 2.56%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 2.56%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 2.56%   |
| Ramaxel RAM RMT3010EC58E8F1333 2GB SODIMM DDR3 1600MT/s          | 1         | 2.56%   |
| Ramaxel RAM RMT1970ED48E8F1066 2GB SODIMM DDR3 1067MT/s          | 1         | 2.56%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 2.56%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 1         | 2.56%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 2.56%   |
| Micron RAM 16ATF2G64HZ-2G3H1 16GB SODIMM DDR4 2400MT/s           | 1         | 2.56%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s                 | 1         | 2.56%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 1         | 2.56%   |
| A-DATA RAM AD73I1B1674EU 2GB SODIMM DDR3 1334MT/s                | 1         | 2.56%   |
| Unknown                                                          | 1         | 2.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 15        | 51.72%  |
| DDR4   | 8         | 27.59%  |
| SDRAM  | 2         | 6.9%    |
| LPDDR4 | 2         | 6.9%    |
| LPDDR3 | 1         | 3.45%   |
| DDR2   | 1         | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 93.1%   |
| Row Of Chips | 1         | 3.45%   |
| DIMM         | 1         | 3.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 16        | 47.06%  |
| 8192  | 8         | 23.53%  |
| 2048  | 6         | 17.65%  |
| 16384 | 4         | 11.76%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 13        | 39.39%  |
| 2667  | 5         | 15.15%  |
| 2400  | 5         | 15.15%  |
| 4199  | 2         | 6.06%   |
| 3266  | 1         | 3.03%   |
| 3200  | 1         | 3.03%   |
| 2133  | 1         | 3.03%   |
| 1867  | 1         | 3.03%   |
| 1334  | 1         | 3.03%   |
| 1333  | 1         | 3.03%   |
| 1067  | 1         | 3.03%   |
| 667   | 1         | 3.03%   |

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
| Chicony Electronics                    | 11        | 18.03%  |
| Microdia                               | 7         | 11.48%  |
| Sunplus Innovation Technology          | 6         | 9.84%   |
| Realtek Semiconductor                  | 6         | 9.84%   |
| Suyin                                  | 5         | 8.2%    |
| IMC Networks                           | 5         | 8.2%    |
| Syntek                                 | 4         | 6.56%   |
| Apple                                  | 4         | 6.56%   |
| Silicon Motion                         | 3         | 4.92%   |
| Ricoh                                  | 2         | 3.28%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.28%   |
| Sonix Technology                       | 1         | 1.64%   |
| Primax Electronics                     | 1         | 1.64%   |
| Logitech                               | 1         | 1.64%   |
| globaloptics                           | 1         | 1.64%   |
| Alcor Micro                            | 1         | 1.64%   |
| Acer                                   | 1         | 1.64%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                               | 4         | 6.56%   |
| Chicony Integrated Camera                                                  | 3         | 4.92%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 3.28%   |
| Microdia Integrated Webcam                                                 | 2         | 3.28%   |
| Microdia Dell Integrated HD Webcam                                         | 2         | 3.28%   |
| IMC Networks Integrated Camera                                             | 2         | 3.28%   |
| Apple FaceTime HD Camera                                                   | 2         | 3.28%   |
| Syntek Integrated Camera                                                   | 1         | 1.64%   |
| Syntek EasyCamera                                                          | 1         | 1.64%   |
| Suyin VGA Webcam                                                           | 1         | 1.64%   |
| Suyin TOSHIBA Web Camera - HD                                              | 1         | 1.64%   |
| Suyin HP TrueVision HD                                                     | 1         | 1.64%   |
| Suyin Acer/Lenovo Webcam [CN0316]                                          | 1         | 1.64%   |
| Suyin 1.3M HD WebCam                                                       | 1         | 1.64%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 1         | 1.64%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 1.64%   |
| Sonix HP Webcam-101                                                        | 1         | 1.64%   |
| Silicon Motion WebCam SCB-0385N                                            | 1         | 1.64%   |
| Silicon Motion WebCam SC-10HDD13335N                                       | 1         | 1.64%   |
| Silicon Motion Real HD WebCam                                              | 1         | 1.64%   |
| Ricoh Integrated Webcam                                                    | 1         | 1.64%   |
| Ricoh HD Webcam                                                            | 1         | 1.64%   |
| Realtek MTD camera                                                         | 1         | 1.64%   |
| Realtek Integrated Webcam HD                                               | 1         | 1.64%   |
| Realtek Integrated Webcam                                                  | 1         | 1.64%   |
| Realtek Integrated Camera                                                  | 1         | 1.64%   |
| Realtek HP Wide Vision HD Camera                                           | 1         | 1.64%   |
| Realtek HP Truevision HD integrated webcam                                 | 1         | 1.64%   |
| Primax HP HD Webcam [Fixed]                                                | 1         | 1.64%   |
| Microdia Sonix USB 2.0 Camera                                              | 1         | 1.64%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                     | 1         | 1.64%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 1.64%   |
| Logitech QuickCam Pro 4000                                                 | 1         | 1.64%   |
| IMC Networks UVC VGA Webcam                                                | 1         | 1.64%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.64%   |
| IMC Networks USB2.0 HD IR UVC WebCam                                       | 1         | 1.64%   |
| globaloptics Integrated Camera 2M                                          | 1         | 1.64%   |
| Chicony USB2.0 HD UVC WebCam                                               | 1         | 1.64%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 1.64%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 1.64%   |
| Chicony HP Webcam [2 MP Macro]                                             | 1         | 1.64%   |
| Chicony HP TrueVision HD                                                   | 1         | 1.64%   |
| Chicony HD WebCam                                                          | 1         | 1.64%   |
| Chicony HD User Facing                                                     | 1         | 1.64%   |
| Chicony FJ Camera                                                          | 1         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 1.64%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 1         | 1.64%   |
| Apple Built-in iSight                                                      | 1         | 1.64%   |
| Alcor Micro USB 2.0 PC cam                                                 | 1         | 1.64%   |
| Acer Lenovo EasyCamera                                                     | 1         | 1.64%   |

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
| 0     | 49        | 69.01%  |
| 1     | 19        | 26.76%  |
| 2     | 3         | 4.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 9         | 36%     |
| Chipcard              | 7         | 28%     |
| Graphics card         | 3         | 12%     |
| Multimedia controller | 2         | 8%      |
| Storage               | 1         | 4%      |
| Net/wireless          | 1         | 4%      |
| Card reader           | 1         | 4%      |
| Bluetooth             | 1         | 4%      |

