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

Total: 172

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion Notebook           | [f23e44229f](https://linux-hardware.org/?probe=f23e44229f) | Nov 03, 2023 |
| Apple         | MacBookPro14,2              | [346fad17ff](https://linux-hardware.org/?probe=346fad17ff) | Oct 27, 2023 |
| Apple         | MacBookPro14,2              | [481d6c83fb](https://linux-hardware.org/?probe=481d6c83fb) | Oct 27, 2023 |
| LG Electro... | 17ZT90P-G.AX33U1            | [0d53262cff](https://linux-hardware.org/?probe=0d53262cff) | Oct 23, 2023 |
| Unknown       | Unknown                     | [6fdc093168](https://linux-hardware.org/?probe=6fdc093168) | Oct 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [d14e5830b2](https://linux-hardware.org/?probe=d14e5830b2) | Oct 16, 2023 |
| Dell          | Latitude E7440              | [7813372525](https://linux-hardware.org/?probe=7813372525) | Sep 11, 2023 |
| Dell          | Inspiron 3543               | [74e5f6b8a5](https://linux-hardware.org/?probe=74e5f6b8a5) | Sep 08, 2023 |
| Dell          | Inspiron 3543               | [d4df00af33](https://linux-hardware.org/?probe=d4df00af33) | Sep 08, 2023 |
| Dell          | XPS M1330                   | [ce3d41b222](https://linux-hardware.org/?probe=ce3d41b222) | Aug 27, 2023 |
| Dell          | Latitude E7250              | [7418a0dc06](https://linux-hardware.org/?probe=7418a0dc06) | Aug 12, 2023 |
| Dell          | Latitude 5590               | [466fdce7aa](https://linux-hardware.org/?probe=466fdce7aa) | Aug 01, 2023 |
| HP            | Pavilion Notebook           | [e50470a456](https://linux-hardware.org/?probe=e50470a456) | Jul 22, 2023 |
| Acer          | AN515-44                    | [171bd20f26](https://linux-hardware.org/?probe=171bd20f26) | Jul 19, 2023 |
| Acer          | AN515-44                    | [c40876ce5f](https://linux-hardware.org/?probe=c40876ce5f) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ebed32abef](https://linux-hardware.org/?probe=ebed32abef) | Jul 19, 2023 |
| Samsung       | RV420/RV520/RV720/E3530/... | [25f8458274](https://linux-hardware.org/?probe=25f8458274) | Jul 17, 2023 |
| Samsung       | RV420/RV520/RV720/E3530/... | [287b00885d](https://linux-hardware.org/?probe=287b00885d) | Jul 02, 2023 |
| HP            | Laptop 15-dy1xxx            | [93e28671fa](https://linux-hardware.org/?probe=93e28671fa) | Jun 18, 2023 |
| ASUSTek       | G750JM                      | [da1f33a87b](https://linux-hardware.org/?probe=da1f33a87b) | Jun 11, 2023 |
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
| Ubuntu 20.04        | 16        | 13.91%  |
| Ubuntu 22.04        | 8         | 6.96%   |
| Ubuntu 18.04        | 7         | 6.09%   |
| Fedora 38           | 5         | 4.35%   |
| OpenMandriva 4.3    | 4         | 3.48%   |
| Fedora 36           | 4         | 3.48%   |
| Manjaro             | 3         | 2.61%   |
| Fedora 37           | 3         | 2.61%   |
| Debian 11           | 3         | 2.61%   |
| Arch Rolling        | 3         | 2.61%   |
| Zorin 16            | 2         | 1.74%   |
| Ubuntu 21.10        | 2         | 1.74%   |
| Pop!_OS 20.10       | 2         | 1.74%   |
| OpenMandriva 4.2    | 2         | 1.74%   |
| OpenMandriva 23.08  | 2         | 1.74%   |
| Linux Mint 20.3     | 2         | 1.74%   |
| Linux Mint 20.1     | 2         | 1.74%   |
| ArcoLinux Rolling   | 2         | 1.74%   |
| Xubuntu 19.10       | 1         | 0.87%   |
| Xubuntu 18.04       | 1         | 0.87%   |
| Void Linux Rolling  | 1         | 0.87%   |
| Ubuntu MATE 22.04   | 1         | 0.87%   |
| Ubuntu Budgie 22.04 | 1         | 0.87%   |
| Ubuntu Budgie 21.10 | 1         | 0.87%   |
| Ubuntu Budgie 20.04 | 1         | 0.87%   |
| Ubuntu 23.04        | 1         | 0.87%   |
| Ubuntu 22.10        | 1         | 0.87%   |
| Ubuntu 21.04        | 1         | 0.87%   |
| Ubuntu 19.04        | 1         | 0.87%   |
| Solus 4.1           | 1         | 0.87%   |
| Pop!_OS 21.04       | 1         | 0.87%   |
| Pop!_OS 20.04       | 1         | 0.87%   |
| OpenMandriva 23.01  | 1         | 0.87%   |
| MX 21               | 1         | 0.87%   |
| Manjaro 22.0.0      | 1         | 0.87%   |
| Manjaro 21.1.2      | 1         | 0.87%   |
| Manjaro 20.1        | 1         | 0.87%   |
| Lubuntu 21.04       | 1         | 0.87%   |
| LMDE 4              | 1         | 0.87%   |
| Linux Mint 21.2     | 1         | 0.87%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 35        | 30.97%  |
| Fedora        | 17        | 15.04%  |
| Linux Mint    | 10        | 8.85%   |
| OpenMandriva  | 9         | 7.96%   |
| Manjaro       | 6         | 5.31%   |
| Pop!_OS       | 4         | 3.54%   |
| Debian        | 4         | 3.54%   |
| Arch          | 4         | 3.54%   |
| Ubuntu Budgie | 3         | 2.65%   |
| Zorin         | 2         | 1.77%   |
| Xubuntu       | 2         | 1.77%   |
| KDE neon      | 2         | 1.77%   |
| Clear Linux   | 2         | 1.77%   |
| ArcoLinux     | 2         | 1.77%   |
| Void Linux    | 1         | 0.88%   |
| Ubuntu MATE   | 1         | 0.88%   |
| Solus         | 1         | 0.88%   |
| MX            | 1         | 0.88%   |
| Lubuntu       | 1         | 0.88%   |
| LMDE          | 1         | 0.88%   |
| Kubuntu       | 1         | 0.88%   |
| Kali          | 1         | 0.88%   |
| Endless       | 1         | 0.88%   |
| Elementary    | 1         | 0.88%   |
| Archcraft     | 1         | 0.88%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-48-generic        | 4         | 3.15%   |
| 5.16.7-desktop-1omv4003 | 4         | 3.15%   |
| 5.4.0-42-generic        | 3         | 2.36%   |
| 5.13.0-22-generic       | 3         | 2.36%   |
| 6.4.8-desktop-2omv2390  | 2         | 1.57%   |
| 5.4.0-77-generic        | 2         | 1.57%   |
| 5.4.0-52-generic        | 2         | 1.57%   |
| 5.4.0-33-generic        | 2         | 1.57%   |
| 5.3.0-51-generic        | 2         | 1.57%   |
| 5.19.0-46-generic       | 2         | 1.57%   |
| 5.15.0-76-generic       | 2         | 1.57%   |
| 5.15.0-58-generic       | 2         | 1.57%   |
| 5.15.0-53-generic       | 2         | 1.57%   |
| 5.15.0-41-generic       | 2         | 1.57%   |
| 6.5.8-200.fc38.x86_64   | 1         | 0.79%   |
| 6.5.7-200.fc38.x86_64   | 1         | 0.79%   |
| 6.5.6-200.fc38.x86_64   | 1         | 0.79%   |
| 6.5.0-kali2-amd64       | 1         | 0.79%   |
| 6.4.6-arch1-1           | 1         | 0.79%   |
| 6.4.14-200.fc38.x86_64  | 1         | 0.79%   |
| 6.3.7-x64v2-xanmod1-1   | 1         | 0.79%   |
| 6.2.7-arch1-1           | 1         | 0.79%   |
| 6.2.14-300.fc38.x86_64  | 1         | 0.79%   |
| 6.2.12-1-MANJARO        | 1         | 0.79%   |
| 6.2.0-20-generic        | 1         | 0.79%   |
| 6.1.5-200.fc37.x86_64   | 1         | 0.79%   |
| 6.1.1-desktop-1omv2290  | 1         | 0.79%   |
| 6.0.6-300.fc37.x86_64   | 1         | 0.79%   |
| 6.0.14-300.fc37.x86_64  | 1         | 0.79%   |
| 5.9.12-xanmod1          | 1         | 0.79%   |
| 5.9.11-arch2-1          | 1         | 0.79%   |
| 5.9.1-arch1-1           | 1         | 0.79%   |
| 5.8.8-arch1-1           | 1         | 0.79%   |
| 5.8.15-301.fc33.x86_64  | 1         | 0.79%   |
| 5.8.12_1                | 1         | 0.79%   |
| 5.8.0-38-generic        | 1         | 0.79%   |
| 5.7.10-201.fc32.x86_64  | 1         | 0.79%   |
| 5.6.19-158.current      | 1         | 0.79%   |
| 5.4.60-2-MANJARO        | 1         | 0.79%   |
| 5.4.15-200.fc31.x86_64  | 1         | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 17.65%  |
| 5.15.0  | 12        | 10.08%  |
| 5.13.0  | 8         | 6.72%   |
| 5.3.0   | 6         | 5.04%   |
| 5.11.0  | 6         | 5.04%   |
| 5.19.0  | 5         | 4.2%    |
| 5.16.7  | 4         | 3.36%   |
| 5.10.0  | 4         | 3.36%   |
| 5.0.0   | 3         | 2.52%   |
| 6.4.8   | 2         | 1.68%   |
| 4.19.0  | 2         | 1.68%   |
| 6.5.8   | 1         | 0.84%   |
| 6.5.7   | 1         | 0.84%   |
| 6.5.6   | 1         | 0.84%   |
| 6.5.0   | 1         | 0.84%   |
| 6.4.6   | 1         | 0.84%   |
| 6.4.14  | 1         | 0.84%   |
| 6.3.7   | 1         | 0.84%   |
| 6.2.7   | 1         | 0.84%   |
| 6.2.14  | 1         | 0.84%   |
| 6.2.12  | 1         | 0.84%   |
| 6.2.0   | 1         | 0.84%   |
| 6.1.5   | 1         | 0.84%   |
| 6.1.1   | 1         | 0.84%   |
| 6.0.6   | 1         | 0.84%   |
| 6.0.14  | 1         | 0.84%   |
| 5.9.12  | 1         | 0.84%   |
| 5.9.11  | 1         | 0.84%   |
| 5.9.1   | 1         | 0.84%   |
| 5.8.8   | 1         | 0.84%   |
| 5.8.15  | 1         | 0.84%   |
| 5.8.12  | 1         | 0.84%   |
| 5.8.0   | 1         | 0.84%   |
| 5.7.10  | 1         | 0.84%   |
| 5.6.19  | 1         | 0.84%   |
| 5.4.60  | 1         | 0.84%   |
| 5.4.15  | 1         | 0.84%   |
| 5.19.7  | 1         | 0.84%   |
| 5.19.14 | 1         | 0.84%   |
| 5.19.12 | 1         | 0.84%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 23        | 19.49%  |
| 5.15    | 14        | 11.86%  |
| 5.13    | 9         | 7.63%   |
| 5.19    | 8         | 6.78%   |
| 5.11    | 8         | 6.78%   |
| 5.3     | 6         | 5.08%   |
| 5.10    | 6         | 5.08%   |
| 6.5     | 4         | 3.39%   |
| 6.4     | 4         | 3.39%   |
| 6.2     | 4         | 3.39%   |
| 5.8     | 4         | 3.39%   |
| 5.16    | 4         | 3.39%   |
| 5.0     | 4         | 3.39%   |
| 5.9     | 3         | 2.54%   |
| 4.19    | 3         | 2.54%   |
| 6.1     | 2         | 1.69%   |
| 6.0     | 2         | 1.69%   |
| 5.18    | 2         | 1.69%   |
| 5.12    | 2         | 1.69%   |
| 6.3     | 1         | 0.85%   |
| 5.7     | 1         | 0.85%   |
| 5.6     | 1         | 0.85%   |
| 5.17    | 1         | 0.85%   |
| 4.18    | 1         | 0.85%   |
| 4.15    | 1         | 0.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 109       | 97.32%  |
| i686   | 3         | 2.68%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 51        | 44.74%  |
| KDE5       | 22        | 19.3%   |
| XFCE       | 12        | 10.53%  |
| X-Cinnamon | 8         | 7.02%   |
| Unknown    | 8         | 7.02%   |
| Budgie     | 4         | 3.51%   |
| KDE        | 3         | 2.63%   |
| MATE       | 2         | 1.75%   |
| sway       | 1         | 0.88%   |
| LXQt       | 1         | 0.88%   |
| LXDE       | 1         | 0.88%   |
| DWM        | 1         | 0.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 86        | 74.78%  |
| Wayland | 25        | 21.74%  |
| Unknown | 4         | 3.48%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 57        | 50%     |
| SDDM    | 16        | 14.04%  |
| GDM3    | 13        | 11.4%   |
| LightDM | 12        | 10.53%  |
| GDM     | 12        | 10.53%  |
| TDM     | 4         | 3.51%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 66        | 56.41%  |
| es_DO   | 30        | 25.64%  |
| Unknown | 7         | 5.98%   |
| es_ES   | 5         | 4.27%   |
| es_MX   | 3         | 2.56%   |
| en_CA   | 2         | 1.71%   |
| C       | 2         | 1.71%   |
| ru_RU   | 1         | 0.85%   |
| fr_FR   | 1         | 0.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 57        | 50.89%  |
| EFI  | 55        | 49.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 79        | 69.3%   |
| Btrfs   | 17        | 14.91%  |
| Overlay | 11        | 9.65%   |
| Tmpfs   | 3         | 2.63%   |
| Xfs     | 2         | 1.75%   |
| F2fs    | 1         | 0.88%   |
| Unknown | 1         | 0.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 58        | 50.88%  |
| GPT     | 47        | 41.23%  |
| MBR     | 9         | 7.89%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 95        | 84.07%  |
| Yes       | 18        | 15.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 83        | 73.45%  |
| Yes       | 30        | 26.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 35        | 31.25%  |
| Hewlett-Packard     | 20        | 17.86%  |
| Lenovo              | 18        | 16.07%  |
| ASUSTek Computer    | 9         | 8.04%   |
| Acer                | 6         | 5.36%   |
| Apple               | 5         | 4.46%   |
| Samsung Electronics | 2         | 1.79%   |
| MSI                 | 2         | 1.79%   |
| Google              | 2         | 1.79%   |
| EVOO                | 2         | 1.79%   |
| Unknown             | 2         | 1.79%   |
| VTEX                | 1         | 0.89%   |
| Toshiba             | 1         | 0.89%   |
| TODOS INDUSTRIAL    | 1         | 0.89%   |
| SAELITE             | 1         | 0.89%   |
| Nuvision            | 1         | 0.89%   |
| LG Electronics      | 1         | 0.89%   |
| Fujitsu             | 1         | 0.89%   |
| Eluktronics         | 1         | 0.89%   |
| ECS                 | 1         | 0.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Lenovo IdeaPad 330S-15IKB 81F5                    | 2         | 1.79%   |
| HP Pavilion Notebook                              | 2         | 1.79%   |
| HP Laptop 15-dy1xxx                               | 2         | 1.79%   |
| HP EliteBook 8460p                                | 2         | 1.79%   |
| EVOO EV-C-116-7                                   | 2         | 1.79%   |
| Dell Latitude E6540                               | 2         | 1.79%   |
| Dell Latitude E6430                               | 2         | 1.79%   |
| Dell Latitude E6420                               | 2         | 1.79%   |
| Dell Latitude E6410                               | 2         | 1.79%   |
| Dell Latitude 5590                                | 2         | 1.79%   |
| Dell Inspiron 5570                                | 2         | 1.79%   |
| Dell Inspiron 5555                                | 2         | 1.79%   |
| Apple MacBookPro8,1                               | 2         | 1.79%   |
| Unknown                                           | 2         | 1.79%   |
| VTEX NOTEBOOK                                     | 1         | 0.89%   |
| Toshiba Satellite C55-A                           | 1         | 0.89%   |
| TODOS INDUSTRIAL Easytouch_2022_V1                | 1         | 0.89%   |
| Samsung RV420/RV520/RV720/E3530/S3530/E3420/E3520 | 1         | 0.89%   |
| Samsung 905S3G/906S3G/915S3G/9305SG               | 1         | 0.89%   |
| SAELITE ES1AU11                                   | 1         | 0.89%   |
| Nuvision NES11                                    | 1         | 0.89%   |
| MSI GE62 6QC                                      | 1         | 0.89%   |
| MSI CR70 2M/CX70 2OC/CX70 2OD                     | 1         | 0.89%   |
| LG 17ZT90P-G.AX33U1                               | 1         | 0.89%   |
| Lenovo Z50-75 80EC                                | 1         | 0.89%   |
| Lenovo ThinkPad W540 20BHS0GB06                   | 1         | 0.89%   |
| Lenovo ThinkPad T490 20N3S7BC02                   | 1         | 0.89%   |
| Lenovo ThinkPad T480s 20L7CTO1WW                  | 1         | 0.89%   |
| Lenovo ThinkPad T470 20HD004AUS                   | 1         | 0.89%   |
| Lenovo ThinkPad T420s 41732BU                     | 1         | 0.89%   |
| Lenovo ThinkPad T410 2537N99                      | 1         | 0.89%   |
| Lenovo ThinkPad P43s 20RH0013US                   | 1         | 0.89%   |
| Lenovo ThinkPad E470 20H1006DUS                   | 1         | 0.89%   |
| Lenovo ThinkBook 14s-IWL 20RM                     | 1         | 0.89%   |
| Lenovo Legion 5 15ARH05 82B5                      | 1         | 0.89%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4              | 1         | 0.89%   |
| Lenovo IdeaPad 320-15IKB 80XL                     | 1         | 0.89%   |
| Lenovo IdeaPad 3 15ALC6 82KU                      | 1         | 0.89%   |
| Lenovo G505s 20255                                | 1         | 0.89%   |
| Lenovo G40-70 20369                               | 1         | 0.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 21        | 18.75%  |
| Dell Inspiron              | 11        | 9.82%   |
| Lenovo ThinkPad            | 8         | 7.14%   |
| Lenovo IdeaPad             | 5         | 4.46%   |
| HP Pavilion                | 5         | 4.46%   |
| Acer Aspire                | 5         | 4.46%   |
| HP Laptop                  | 4         | 3.57%   |
| HP EliteBook               | 3         | 2.68%   |
| ASUS VivoBook              | 3         | 2.68%   |
| HP ProBook                 | 2         | 1.79%   |
| EVOO EV-C-116-7            | 2         | 1.79%   |
| Dell Vostro                | 2         | 1.79%   |
| Apple MacBookPro8          | 2         | 1.79%   |
| Unknown                    | 2         | 1.79%   |
| VTEX NOTEBOOK              | 1         | 0.89%   |
| Toshiba Satellite          | 1         | 0.89%   |
| TODOS INDUSTRIAL Easytouch | 1         | 0.89%   |
| Samsung RV420              | 1         | 0.89%   |
| Samsung 905S3G             | 1         | 0.89%   |
| SAELITE ES1AU11            | 1         | 0.89%   |
| Nuvision NES11             | 1         | 0.89%   |
| MSI GE62                   | 1         | 0.89%   |
| MSI CR70                   | 1         | 0.89%   |
| LG 17ZT90P-G.AX33U1        | 1         | 0.89%   |
| Lenovo Z50-75              | 1         | 0.89%   |
| Lenovo ThinkBook           | 1         | 0.89%   |
| Lenovo Legion              | 1         | 0.89%   |
| Lenovo G505s               | 1         | 0.89%   |
| Lenovo G40-70              | 1         | 0.89%   |
| HP OMEN                    | 1         | 0.89%   |
| HP Notebook                | 1         | 0.89%   |
| HP G60                     | 1         | 0.89%   |
| HP ENVY                    | 1         | 0.89%   |
| HP 255                     | 1         | 0.89%   |
| HP 250                     | 1         | 0.89%   |
| Google Winky               | 1         | 0.89%   |
| Google Kip                 | 1         | 0.89%   |
| Fujitsu LIFEBOOK           | 1         | 0.89%   |
| Eluktronics P670RE3        | 1         | 0.89%   |
| ECS ClassMate              | 1         | 0.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2014 | 12        | 10.71%  |
| 2019 | 11        | 9.82%   |
| 2011 | 11        | 9.82%   |
| 2021 | 10        | 8.93%   |
| 2017 | 10        | 8.93%   |
| 2013 | 10        | 8.93%   |
| 2012 | 8         | 7.14%   |
| 2018 | 7         | 6.25%   |
| 2020 | 6         | 5.36%   |
| 2010 | 5         | 4.46%   |
| 2008 | 5         | 4.46%   |
| 2016 | 4         | 3.57%   |
| 2015 | 4         | 3.57%   |
| 2009 | 3         | 2.68%   |
| 2022 | 2         | 1.79%   |
| 2007 | 2         | 1.79%   |
| 2006 | 1         | 0.89%   |
| 2005 | 1         | 0.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 112       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 108       | 96.43%  |
| Enabled  | 4         | 3.57%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 110       | 98.21%  |
| Yes  | 2         | 1.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 33        | 29.2%   |
| 3.01-4.0   | 33        | 29.2%   |
| 8.01-16.0  | 21        | 18.58%  |
| 16.01-24.0 | 13        | 11.5%   |
| 2.01-3.0   | 4         | 3.54%   |
| 1.01-2.0   | 4         | 3.54%   |
| 32.01-64.0 | 3         | 2.65%   |
| 24.01-32.0 | 2         | 1.77%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 44        | 35.77%  |
| 2.01-3.0  | 35        | 28.46%  |
| 3.01-4.0  | 22        | 17.89%  |
| 4.01-8.0  | 15        | 12.2%   |
| 0.51-1.0  | 6         | 4.88%   |
| 8.01-16.0 | 1         | 0.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 81        | 71.68%  |
| 2      | 32        | 28.32%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 65        | 57.52%  |
| Yes       | 48        | 42.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 80.36%  |
| No        | 22        | 19.64%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 110       | 98.21%  |
| No        | 2         | 1.79%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 72.57%  |
| No        | 31        | 27.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Dominican Republic | 112       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Santo Domingo Este         | 67        | 57.76%  |
| Santiago de los Caballeros | 13        | 11.21%  |
| Santo Domingo              | 8         | 6.9%    |
| La Romana                  | 5         | 4.31%   |
| Concepción de la Vega     | 5         | 4.31%   |
| Santa Cruz de Barahona     | 2         | 1.72%   |
| Cabarete                   | 2         | 1.72%   |
| Alejandro Bass             | 2         | 1.72%   |
| Sosua, Cabarete            | 1         | 0.86%   |
| Santo Domingo Oeste        | 1         | 0.86%   |
| San Pedro de Macorís      | 1         | 0.86%   |
| San Cristobal              | 1         | 0.86%   |
| Punta Cana                 | 1         | 0.86%   |
| Los Hidalgos               | 1         | 0.86%   |
| Guaymate                   | 1         | 0.86%   |
| Constanza                  | 1         | 0.86%   |
| Cancino                    | 1         | 0.86%   |
| Boca Chica                 | 1         | 0.86%   |
| Baní                      | 1         | 0.86%   |
| Bajos de Haina             | 1         | 0.86%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 24        | 31     | 17.78%  |
| Samsung Electronics         | 18        | 19     | 13.33%  |
| Toshiba                     | 13        | 16     | 9.63%   |
| WDC                         | 11        | 14     | 8.15%   |
| SanDisk                     | 9         | 12     | 6.67%   |
| Hitachi                     | 9         | 10     | 6.67%   |
| Kingston                    | 8         | 8      | 5.93%   |
| Unknown                     | 6         | 7      | 4.44%   |
| SK hynix                    | 6         | 7      | 4.44%   |
| Intel                       | 3         | 5      | 2.22%   |
| Unknown                     | 3         | 3      | 2.22%   |
| Transcend                   | 2         | 2      | 1.48%   |
| SPCC                        | 2         | 2      | 1.48%   |
| Micron/Crucial Technology   | 2         | 2      | 1.48%   |
| Micron Technology           | 2         | 2      | 1.48%   |
| FORESEE                     | 2         | 2      | 1.48%   |
| China                       | 2         | 3      | 1.48%   |
| AirDisk                     | 2         | 2      | 1.48%   |
| UMIS                        | 1         | 1      | 0.74%   |
| PNY                         | 1         | 1      | 0.74%   |
| OCZ                         | 1         | 1      | 0.74%   |
| LITEONIT                    | 1         | 2      | 0.74%   |
| Kingston Technology Company | 1         | 1      | 0.74%   |
| Indilinx                    | 1         | 1      | 0.74%   |
| HGST                        | 1         | 1      | 0.74%   |
| Hewlett-Packard             | 1         | 1      | 0.74%   |
| Eluktro                     | 1         | 1      | 0.74%   |
| Apple                       | 1         | 2      | 0.74%   |
| A-DATA Technology           | 1         | 1      | 0.74%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST500LM000-1EJ162 500GB                   | 3         | 2.14%   |
| Seagate ST1000LM035-1RK172 1TB                    | 3         | 2.14%   |
| Unknown                                           | 3         | 2.14%   |
| Unknown MMC Card  32GB                            | 2         | 1.43%   |
| Unknown MMC Card  16GB                            | 2         | 1.43%   |
| Unknown MMC Card  128GB                           | 2         | 1.43%   |
| Toshiba MQ04ABF100 1TB                            | 2         | 1.43%   |
| Toshiba MQ01ACF050 500GB                          | 2         | 1.43%   |
| Toshiba MK3275GSX 320GB                           | 2         | 1.43%   |
| Seagate ST9250315AS 250GB                         | 2         | 1.43%   |
| Seagate ST500LT012-1DG142 500GB                   | 2         | 1.43%   |
| Seagate ST500LM021-1KJ152 500GB                   | 2         | 1.43%   |
| Seagate ST1000LM049-2GH172 1TB                    | 2         | 1.43%   |
| SanDisk NVMe SSD Drive 256GB                      | 2         | 1.43%   |
| Samsung SSD 860 EVO 500GB                         | 2         | 1.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 1.43%   |
| Kingston SA400S37240G 240GB SSD                   | 2         | 1.43%   |
| Kingston SA400S37120G 120GB SSD                   | 2         | 1.43%   |
| Intel HBRPEKNX0101AHO 16GB                        | 2         | 1.43%   |
| Intel HBRPEKNX0101AH 256GB                        | 2         | 1.43%   |
| FORESEE 128GB SSD                                 | 2         | 1.43%   |
| AirDisk 128GB SSD                                 | 2         | 1.43%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                    | 1         | 0.71%   |
| WDC WD5000LPLX-08ZNTT0 500GB                      | 1         | 0.71%   |
| WDC WD3200LPVX-75V0TT0 320GB                      | 1         | 0.71%   |
| WDC WD3200BEVT-75A23T0 320GB                      | 1         | 0.71%   |
| WDC WD2500BEVT-75A23T0 250GB                      | 1         | 0.71%   |
| WDC WD2500BEVS-22UST0 250GB                       | 1         | 0.71%   |
| WDC WD2500BEKT-60A25T1 250GB                      | 1         | 0.71%   |
| WDC WD1600BEVT-75ZCT1 160GB                       | 1         | 0.71%   |
| WDC WD10SPZX-24Z10T0 1TB                          | 1         | 0.71%   |
| WDC WD10JPVX-60JC3T1 1TB                          | 1         | 0.71%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 1         | 0.71%   |
| Unknown MMC Card  64GB                            | 1         | 0.71%   |
| UMIS RPJTJ256MEE1OWX 256GB                        | 1         | 0.71%   |
| Transcend TS256GSSD340 256GB                      | 1         | 0.71%   |
| Transcend TS128GSSD370S 128GB                     | 1         | 0.71%   |
| Toshiba NVMe SSD Drive 1024GB                     | 1         | 0.71%   |
| Toshiba MQ01ABF050 500GB                          | 1         | 0.71%   |
| Toshiba MQ01ABD100 1TB                            | 1         | 0.71%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 29     | 41.07%  |
| Toshiba             | 12        | 15     | 21.43%  |
| WDC                 | 10        | 13     | 17.86%  |
| Hitachi             | 9         | 10     | 16.07%  |
| Samsung Electronics | 1         | 1      | 1.79%   |
| HGST                | 1         | 1      | 1.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 12     | 24.44%  |
| Kingston            | 7         | 7      | 15.56%  |
| SanDisk             | 6         | 9      | 13.33%  |
| Transcend           | 2         | 2      | 4.44%   |
| SPCC                | 2         | 2      | 4.44%   |
| SK hynix            | 2         | 2      | 4.44%   |
| FORESEE             | 2         | 2      | 4.44%   |
| China               | 2         | 3      | 4.44%   |
| AirDisk             | 2         | 2      | 4.44%   |
| WDC                 | 1         | 1      | 2.22%   |
| Seagate             | 1         | 2      | 2.22%   |
| PNY                 | 1         | 1      | 2.22%   |
| OCZ                 | 1         | 1      | 2.22%   |
| LITEONIT            | 1         | 2      | 2.22%   |
| Hewlett-Packard     | 1         | 1      | 2.22%   |
| Eluktro             | 1         | 1      | 2.22%   |
| A-DATA Technology   | 1         | 1      | 2.22%   |
| Unknown             | 1         | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 53        | 69     | 41.73%  |
| SSD     | 41        | 52     | 32.28%  |
| NVMe    | 23        | 28     | 18.11%  |
| MMC     | 9         | 10     | 7.09%   |
| Unknown | 1         | 1      | 0.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 87        | 117    | 70.73%  |
| NVMe | 23        | 28     | 18.7%   |
| MMC  | 9         | 10     | 7.32%   |
| SAS  | 4         | 5      | 3.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 66        | 89     | 71.74%  |
| 0.51-1.0   | 22        | 27     | 23.91%  |
| 1.01-2.0   | 3         | 3      | 3.26%   |
| 3.01-4.0   | 1         | 2      | 1.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 36        | 30.77%  |
| 251-500        | 21        | 17.95%  |
| 501-1000       | 20        | 17.09%  |
| 1-20           | 12        | 10.26%  |
| 51-100         | 11        | 9.4%    |
| 1001-2000      | 6         | 5.13%   |
| 21-50          | 4         | 3.42%   |
| 2001-3000      | 4         | 3.42%   |
| Unknown        | 2         | 1.71%   |
| More than 3000 | 1         | 0.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 48        | 38.71%  |
| 21-50     | 24        | 19.35%  |
| 51-100    | 19        | 15.32%  |
| 101-250   | 14        | 11.29%  |
| 251-500   | 5         | 4.03%   |
| 1001-2000 | 5         | 4.03%   |
| 501-1000  | 5         | 4.03%   |
| 2001-3000 | 2         | 1.61%   |
| Unknown   | 2         | 1.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500LM021-1KJ152 500GB   | 2         | 2      | 14.29%  |
| WDC WD2500BEKT-60A25T1 250GB      | 1         | 1      | 7.14%   |
| Toshiba MK6465GSXN 640GB          | 1         | 1      | 7.14%   |
| Toshiba MK3276GSX 320GB           | 1         | 1      | 7.14%   |
| Toshiba MK3275GSX 320GB           | 1         | 1      | 7.14%   |
| Seagate ST9750420AS 752GB         | 1         | 1      | 7.14%   |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 7.14%   |
| Seagate ST500LM000-1EJ162 500GB   | 1         | 1      | 7.14%   |
| Seagate ST2000LM007-1R8174 2TB    | 1         | 1      | 7.14%   |
| Samsung Electronics HM500LI 500GB | 1         | 1      | 7.14%   |
| Hitachi HTS727550A9E364 500GB     | 1         | 1      | 7.14%   |
| Hitachi HTS725032A9A364 320GB     | 1         | 1      | 7.14%   |
| Hitachi HTS547575A9E384 752GB     | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 42.86%  |
| Toshiba             | 3         | 3      | 21.43%  |
| Hitachi             | 3         | 3      | 21.43%  |
| WDC                 | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 42.86%  |
| Toshiba             | 3         | 3      | 21.43%  |
| Hitachi             | 3         | 3      | 21.43%  |
| WDC                 | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 14     | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HTS545050B9SA00 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 70        | 108    | 59.83%  |
| Works    | 32        | 37     | 27.35%  |
| Malfunc  | 14        | 14     | 11.97%  |
| Failed   | 1         | 1      | 0.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 81        | 66.94%  |
| AMD                          | 18        | 14.88%  |
| Samsung Electronics          | 6         | 4.96%   |
| SK hynix                     | 3         | 2.48%   |
| SanDisk                      | 3         | 2.48%   |
| Micron/Crucial Technology    | 2         | 1.65%   |
| Micron Technology            | 2         | 1.65%   |
| Kingston Technology Company  | 2         | 1.65%   |
| Union Memory (Shenzhen)      | 1         | 0.83%   |
| Toshiba America Info Systems | 1         | 0.83%   |
| Nvidia                       | 1         | 0.83%   |
| Apple                        | 1         | 0.83%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 13.18%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 15        | 11.63%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 7.75%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 8         | 6.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 5.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 5.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 3.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 3.1%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 3.1%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 3.1%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 2.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 2.33%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 2         | 1.55%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 2         | 1.55%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.55%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 2         | 1.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.55%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 2         | 1.55%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 1         | 0.78%   |
| Toshiba America Info Systems XG3 NVMe SSD Controller                           | 1         | 0.78%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1         | 0.78%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                          | 1         | 0.78%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 0.78%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 0.78%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.78%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 0.78%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                      | 1         | 0.78%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 1         | 0.78%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                 | 1         | 0.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.78%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 0.78%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 1         | 0.78%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 0.78%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 0.78%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 0.78%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 0.78%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 75        | 60.48%  |
| NVMe | 23        | 18.55%  |
| RAID | 16        | 12.9%   |
| IDE  | 10        | 8.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 92        | 82.14%  |
| AMD    | 20        | 17.86%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 3.57%   |
| Intel Celeron N4120 CPU @ 1.10GHz           | 4         | 3.57%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 4         | 3.57%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 2.68%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 3         | 2.68%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.79%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 2         | 1.79%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.79%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 2         | 1.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.79%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.79%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 1.79%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 1.79%   |
| Intel Core i5-2415M CPU @ 2.30GHz           | 2         | 1.79%   |
| Intel Core i3-8130U CPU @ 2.20GHz           | 2         | 1.79%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 2         | 1.79%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 1.79%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 2         | 1.79%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 1.79%   |
| AMD A4-6210 APU with AMD Radeon R3 Graphics | 2         | 1.79%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.89%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 0.89%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.89%   |
| Intel Genuine CPU U4100 @ 1.30GHz           | 1         | 0.89%   |
| Intel Core i9-9980HK CPU @ 2.40GHz          | 1         | 0.89%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.89%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.89%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.89%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 0.89%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 0.89%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 1         | 0.89%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 0.89%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 0.89%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 0.89%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 0.89%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 0.89%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 0.89%   |
| Intel Core i5-7267U CPU @ 3.10GHz           | 1         | 0.89%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 0.89%   |
| Intel Core i5-4310M CPU @ 2.70GHz           | 1         | 0.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 32        | 28.57%  |
| Intel Core i7           | 20        | 17.86%  |
| Intel Celeron           | 15        | 13.39%  |
| Intel Core i3           | 10        | 8.93%   |
| Intel Core 2 Duo        | 4         | 3.57%   |
| AMD Ryzen 5             | 4         | 3.57%   |
| AMD Ryzen 7             | 3         | 2.68%   |
| AMD A10                 | 3         | 2.68%   |
| Other                   | 2         | 1.79%   |
| Intel Core 2            | 2         | 1.79%   |
| Intel Atom              | 2         | 1.79%   |
| AMD A8                  | 2         | 1.79%   |
| AMD A6                  | 2         | 1.79%   |
| AMD A4                  | 2         | 1.79%   |
| Intel Pentium Dual-Core | 1         | 0.89%   |
| Intel Pentium Dual      | 1         | 0.89%   |
| Intel Pentium           | 1         | 0.89%   |
| Intel Genuine           | 1         | 0.89%   |
| Intel Core i9           | 1         | 0.89%   |
| AMD Ryzen 3             | 1         | 0.89%   |
| AMD Quad-Core           | 1         | 0.89%   |
| AMD Mobile Sempron      | 1         | 0.89%   |
| AMD A12                 | 1         | 0.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 73        | 65.18%  |
| 4      | 30        | 26.79%  |
| 6      | 4         | 3.57%   |
| 8      | 3         | 2.68%   |
| 1      | 2         | 1.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 112       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 76        | 67.86%  |
| 1      | 36        | 32.14%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 110       | 98.21%  |
| 32-bit         | 1         | 0.89%   |
| Unknown        | 1         | 0.89%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 29.82%  |
| 0x206a7    | 11        | 9.65%   |
| 0x306a9    | 7         | 6.14%   |
| 0x806e9    | 5         | 4.39%   |
| 0x40651    | 5         | 4.39%   |
| 0x806ea    | 4         | 3.51%   |
| 0x706a1    | 4         | 3.51%   |
| 0x1067a    | 4         | 3.51%   |
| 0x306c3    | 3         | 2.63%   |
| 0x30678    | 3         | 2.63%   |
| 0x07030105 | 3         | 2.63%   |
| 0x806ec    | 2         | 1.75%   |
| 0x706a8    | 2         | 1.75%   |
| 0x6f6      | 2         | 1.75%   |
| 0x506e3    | 2         | 1.75%   |
| 0x20655    | 2         | 1.75%   |
| 0x20652    | 2         | 1.75%   |
| 0x10676    | 2         | 1.75%   |
| 0x08600103 | 2         | 1.75%   |
| 0x806c1    | 1         | 0.88%   |
| 0x6fd      | 1         | 0.88%   |
| 0x506c9    | 1         | 0.88%   |
| 0x406c3    | 1         | 0.88%   |
| 0x106ca    | 1         | 0.88%   |
| 0x08608103 | 1         | 0.88%   |
| 0x08608102 | 1         | 0.88%   |
| 0x08108109 | 1         | 0.88%   |
| 0x08108102 | 1         | 0.88%   |
| 0x0700010f | 1         | 0.88%   |
| 0x06006705 | 1         | 0.88%   |
| 0x0600611a | 1         | 0.88%   |
| 0x06006110 | 1         | 0.88%   |
| 0x06003106 | 1         | 0.88%   |
| 0x06001119 | 1         | 0.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 19        | 16.96%  |
| SandyBridge   | 11        | 9.82%   |
| Haswell       | 11        | 9.82%   |
| IvyBridge     | 9         | 8.04%   |
| Goldmont plus | 8         | 7.14%   |
| Westmere      | 6         | 5.36%   |
| Silvermont    | 6         | 5.36%   |
| Penryn        | 6         | 5.36%   |
| Puma          | 4         | 3.57%   |
| Zen+          | 3         | 2.68%   |
| Skylake       | 3         | 2.68%   |
| IceLake       | 3         | 2.68%   |
| Excavator     | 3         | 2.68%   |
| Core          | 3         | 2.68%   |
| Zen 2         | 2         | 1.79%   |
| TigerLake     | 2         | 1.79%   |
| Broadwell     | 2         | 1.79%   |
| Unknown       | 2         | 1.79%   |
| Zen 3         | 1         | 0.89%   |
| Steamroller   | 1         | 0.89%   |
| Piledriver    | 1         | 0.89%   |
| K8 Hammer     | 1         | 0.89%   |
| K10 Llano     | 1         | 0.89%   |
| Jaguar        | 1         | 0.89%   |
| Goldmont      | 1         | 0.89%   |
| CometLake     | 1         | 0.89%   |
| Bonnell       | 1         | 0.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 87        | 66.92%  |
| AMD    | 25        | 19.23%  |
| Nvidia | 18        | 13.85%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 10        | 7.41%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 9         | 6.67%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 8         | 5.93%   |
| Intel UHD Graphics 620                                                    | 7         | 5.19%   |
| Intel HD Graphics 620                                                     | 6         | 4.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 4.44%   |
| Intel Core Processor Integrated Graphics Controller                       | 5         | 3.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 5         | 3.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 4         | 2.96%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 3         | 2.22%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 2.22%   |
| Intel Iris Plus Graphics G7                                               | 3         | 2.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 2.22%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.48%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 2         | 1.48%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 2         | 1.48%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 2         | 1.48%   |
| Intel HD Graphics 5500                                                    | 2         | 1.48%   |
| Intel HD Graphics 530                                                     | 2         | 1.48%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 1.48%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                       | 2         | 1.48%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 2         | 1.48%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.48%   |
| AMD Mullins [Radeon R3 Graphics]                                          | 2         | 1.48%   |
| AMD Lucienne                                                              | 2         | 1.48%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.74%   |
| Nvidia GT216GLM [Quadro FX 880M]                                          | 1         | 0.74%   |
| Nvidia GP108GLM [Quadro P520]                                             | 1         | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                               | 1         | 0.74%   |
| Nvidia GM204M [GeForce GTX 960 OEM / 970M]                                | 1         | 0.74%   |
| Nvidia GM108M [GeForce MX130]                                             | 1         | 0.74%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 0.74%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.74%   |
| Nvidia GM107M [GeForce GTX 860M]                                          | 1         | 0.74%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 1         | 0.74%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 0.74%   |
| Nvidia G86M [GeForce 8400M GS]                                            | 1         | 0.74%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                             | 1         | 0.74%   |
| Nvidia C79 [GeForce 9400M]                                                | 1         | 0.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 73        | 65.18%  |
| 1 x AMD        | 15        | 13.39%  |
| Intel + Nvidia | 10        | 8.93%   |
| 1 x Nvidia     | 4         | 3.57%   |
| Intel + AMD    | 4         | 3.57%   |
| AMD + Nvidia   | 4         | 3.57%   |
| 2 x AMD        | 2         | 1.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 101       | 90.18%  |
| Proprietary | 9         | 8.04%   |
| Unknown     | 2         | 1.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 87        | 76.99%  |
| 0.01-0.5   | 9         | 7.96%   |
| 1.01-2.0   | 7         | 6.19%   |
| 0.51-1.0   | 7         | 6.19%   |
| 3.01-4.0   | 2         | 1.77%   |
| 2.01-3.0   | 1         | 0.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 28        | 22.05%  |
| BOE                     | 20        | 15.75%  |
| LG Display              | 17        | 13.39%  |
| Chimei Innolux          | 15        | 11.81%  |
| Samsung Electronics     | 13        | 10.24%  |
| Dell                    | 7         | 5.51%   |
| Chi Mei Optoelectronics | 5         | 3.94%   |
| Apple                   | 4         | 3.15%   |
| InfoVision              | 2         | 1.57%   |
| Hewlett-Packard         | 2         | 1.57%   |
| ZTR                     | 1         | 0.79%   |
| Westinghouse            | 1         | 0.79%   |
| Vizio                   | 1         | 0.79%   |
| Unknown (XXX)           | 1         | 0.79%   |
| Sony                    | 1         | 0.79%   |
| Philips                 | 1         | 0.79%   |
| PANDA                   | 1         | 0.79%   |
| MSI                     | 1         | 0.79%   |
| LG Philips              | 1         | 0.79%   |
| Lenovo                  | 1         | 0.79%   |
| KDC                     | 1         | 0.79%   |
| InnoLux Display         | 1         | 0.79%   |
| Goldstar                | 1         | 0.79%   |
| AOC                     | 1         | 0.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 3         | 2.36%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch           | 2         | 1.57%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.57%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch           | 2         | 1.57%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.57%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.57%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 1.57%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch         | 2         | 1.57%   |
| AU Optronics LCD Monitor AUO11EC 1366x768 344x193mm 15.5-inch         | 2         | 1.57%   |
| ZTR LCD Monitor ZTR0001 1366x768 309x173mm 13.9-inch                  | 1         | 0.79%   |
| Westinghouse EUM24F1G1 WDT1E64 1920x1080 530x300mm 24.0-inch          | 1         | 0.79%   |
| Vizio E241i-B1 VIZ1005 1920x1080 521x293mm 23.5-inch                  | 1         | 0.79%   |
| Unknown (XXX) Philco XXX0030 1600x1200 708x398mm 32.0-inch            | 1         | 0.79%   |
| Sony TV SNY1703 1360x768 1600x900mm 72.3-inch                         | 1         | 0.79%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC5544 1920x1080 344x194mm 15.5-inch | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC4642 1366x768 309x174mm 14.0-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SAM0B32 1366x768 607x345mm 27.5-inch  | 1         | 0.79%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch              | 1         | 0.79%   |
| PANDA LC116LF1L02 NCP000F 1920x1080 256x144mm 11.6-inch               | 1         | 0.79%   |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                    | 1         | 0.79%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD0695 2560x1600 366x229mm 17.0-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD03AE 1366x768 345x194mm 15.6-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD0357 1600x900 382x215mm 17.3-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch           | 1         | 0.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 54        | 45.38%  |
| 1920x1080 (FHD)    | 39        | 32.77%  |
| 1280x800 (WXGA)    | 7         | 5.88%   |
| 1600x900 (HD+)     | 6         | 5.04%   |
| 3840x2160 (4K)     | 2         | 1.68%   |
| 1680x1050 (WSXGA+) | 2         | 1.68%   |
| 1280x1024 (SXGA)   | 2         | 1.68%   |
| 3840x1100          | 1         | 0.84%   |
| 3440x1440          | 1         | 0.84%   |
| 2560x1600          | 1         | 0.84%   |
| 1360x768           | 1         | 0.84%   |
| 1280x768           | 1         | 0.84%   |
| 1024x768 (XGA)     | 1         | 0.84%   |
| 1024x600           | 1         | 0.84%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 59        | 46.83%  |
| 13      | 19        | 15.08%  |
| 14      | 14        | 11.11%  |
| 11      | 8         | 6.35%   |
| 17      | 6         | 4.76%   |
| 22      | 3         | 2.38%   |
| 34      | 2         | 1.59%   |
| 24      | 2         | 1.59%   |
| 21      | 2         | 1.59%   |
| 72      | 1         | 0.79%   |
| 40      | 1         | 0.79%   |
| 32      | 1         | 0.79%   |
| 31      | 1         | 0.79%   |
| 27      | 1         | 0.79%   |
| 23      | 1         | 0.79%   |
| 20      | 1         | 0.79%   |
| 19      | 1         | 0.79%   |
| 12      | 1         | 0.79%   |
| 10      | 1         | 0.79%   |
| Unknown | 1         | 0.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 80        | 64.52%  |
| 201-300     | 18        | 14.52%  |
| 351-400     | 9         | 7.26%   |
| 401-500     | 6         | 4.84%   |
| 501-600     | 4         | 3.23%   |
| 701-800     | 3         | 2.42%   |
| 801-900     | 1         | 0.81%   |
| 601-700     | 1         | 0.81%   |
| 1501-2000   | 1         | 0.81%   |
| Unknown     | 1         | 0.81%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 97        | 85.84%  |
| 16/10   | 10        | 8.85%   |
| 5/4     | 2         | 1.77%   |
| 4/3     | 1         | 0.88%   |
| 3.40    | 1         | 0.88%   |
| 21/9    | 1         | 0.88%   |
| Unknown | 1         | 0.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 58        | 46.03%  |
| 81-90          | 27        | 21.43%  |
| 51-60          | 9         | 7.14%   |
| 201-250        | 8         | 6.35%   |
| 71-80          | 5         | 3.97%   |
| 121-130        | 5         | 3.97%   |
| 351-500        | 3         | 2.38%   |
| 151-200        | 2         | 1.59%   |
| 501-1000       | 2         | 1.59%   |
| More than 1000 | 1         | 0.79%   |
| 61-70          | 1         | 0.79%   |
| 41-50          | 1         | 0.79%   |
| 301-350        | 1         | 0.79%   |
| 141-150        | 1         | 0.79%   |
| 91-100         | 1         | 0.79%   |
| Unknown        | 1         | 0.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 54        | 44.26%  |
| 121-160       | 43        | 35.25%  |
| 51-100        | 17        | 13.93%  |
| 1-50          | 3         | 2.46%   |
| 161-240       | 3         | 2.46%   |
| More than 240 | 1         | 0.82%   |
| Unknown       | 1         | 0.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 93        | 82.3%   |
| 2     | 17        | 15.04%  |
| 0     | 2         | 1.77%   |
| 3     | 1         | 0.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 58        | 32.95%  |
| Realtek Semiconductor           | 56        | 31.82%  |
| Qualcomm Atheros                | 26        | 14.77%  |
| Broadcom                        | 17        | 9.66%   |
| Ralink Technology               | 4         | 2.27%   |
| Broadcom Limited                | 3         | 1.7%    |
| Qualcomm Atheros Communications | 2         | 1.14%   |
| Marvell Technology Group        | 2         | 1.14%   |
| Lenovo                          | 2         | 1.14%   |
| Dell                            | 2         | 1.14%   |
| Nvidia                          | 1         | 0.57%   |
| MediaTek                        | 1         | 0.57%   |
| JCM                             | 1         | 0.57%   |
| AMD                             | 1         | 0.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 23        | 10.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 7.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 4.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 3.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 2.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 2.8%    |
| Intel Wireless 7260                                               | 6         | 2.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.34%   |
| Intel Wireless 3165                                               | 5         | 2.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.87%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 1.87%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.87%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 1.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 1.4%    |
| Intel Wireless 8265 / 8275                                        | 3         | 1.4%    |
| Intel Wireless 7265                                               | 3         | 1.4%    |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.4%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.4%    |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.4%    |
| Intel Centrino Advanced-N 6235                                    | 3         | 1.4%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.4%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.93%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.93%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 0.93%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.93%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 0.93%   |
| Lenovo Thinkpad LAN                                               | 2         | 0.93%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.93%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.93%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 0.93%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.93%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.93%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.93%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 0.93%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.93%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 45.83%  |
| Qualcomm Atheros                | 22        | 18.33%  |
| Realtek Semiconductor           | 19        | 15.83%  |
| Broadcom                        | 14        | 11.67%  |
| Ralink Technology               | 4         | 3.33%   |
| Qualcomm Atheros Communications | 2         | 1.67%   |
| Dell                            | 2         | 1.67%   |
| MediaTek                        | 1         | 0.83%   |
| Broadcom Limited                | 1         | 0.83%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 8         | 6.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 6         | 4.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 6         | 4.96%   |
| Intel Wireless 7260                                                                   | 6         | 4.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 5         | 4.13%   |
| Intel Wireless 3165                                                                   | 5         | 4.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 3.31%   |
| Intel Wi-Fi 6 AX200                                                                   | 4         | 3.31%   |
| Ralink MT7601U Wireless Adapter                                                       | 3         | 2.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 2.48%   |
| Intel Wireless 8265 / 8275                                                            | 3         | 2.48%   |
| Intel Wireless 7265                                                                   | 3         | 2.48%   |
| Intel Centrino Advanced-N 6235                                                        | 3         | 2.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 3         | 2.48%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 3         | 2.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 2         | 1.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.65%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 2         | 1.65%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 1.65%   |
| Realtek 802.11n WLAN Adapter                                                          | 2         | 1.65%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 2         | 1.65%   |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 1.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 2         | 1.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 1.65%   |
| Intel Centrino Wireless-N 2230                                                        | 2         | 1.65%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 1.65%   |
| Intel Centrino Advanced-N 6200                                                        | 2         | 1.65%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 1.65%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 2         | 1.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 0.83%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.83%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 1         | 0.83%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 1         | 0.83%   |
| Intel Wireless 8260                                                                   | 1         | 0.83%   |
| Intel Wireless 3160                                                                   | 1         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 44        | 48.35%  |
| Intel                    | 28        | 30.77%  |
| Qualcomm Atheros         | 6         | 6.59%   |
| Broadcom                 | 6         | 6.59%   |
| Marvell Technology Group | 2         | 2.2%    |
| Lenovo                   | 2         | 2.2%    |
| Broadcom Limited         | 2         | 2.2%    |
| Nvidia                   | 1         | 1.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 23        | 25.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 18.68%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 9.89%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 4.4%    |
| Intel Ethernet Connection I218-LM                                 | 3         | 3.3%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 3.3%    |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 3.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.2%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 2.2%    |
| Lenovo Thinkpad LAN                                               | 2         | 2.2%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.2%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.1%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.1%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.1%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.1%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.1%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.1%    |
| Nvidia MCP79 Ethernet                                             | 1         | 1.1%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.1%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.1%    |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.1%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.1%    |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.1%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.1%    |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.1%    |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.1%    |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                 | 1         | 1.1%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.1%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.1%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.1%    |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express  | 1         | 1.1%    |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 1         | 1.1%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 110       | 54.73%  |
| Ethernet | 89        | 44.28%  |
| Modem    | 2         | 1%      |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 91        | 79.13%  |
| Ethernet | 24        | 20.87%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 86        | 76.79%  |
| 1     | 23        | 20.54%  |
| 0     | 3         | 2.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 103       | 90.35%  |
| Yes  | 11        | 9.65%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 45.12%  |
| Qualcomm Atheros Communications | 13        | 15.85%  |
| IMC Networks                    | 8         | 9.76%   |
| Realtek Semiconductor           | 7         | 8.54%   |
| Dell                            | 6         | 7.32%   |
| Broadcom                        | 4         | 4.88%   |
| Apple                           | 4         | 4.88%   |
| Lite-On Technology              | 2         | 2.44%   |
| Hewlett-Packard                 | 1         | 1.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 19        | 23.17%  |
| Qualcomm Atheros  Bluetooth Device             | 8         | 9.76%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 5         | 6.1%    |
| IMC Networks Bluetooth Radio                   | 5         | 6.1%    |
| Realtek  Bluetooth 4.2 Adapter                 | 4         | 4.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 4         | 4.88%   |
| Intel AX200 Bluetooth                          | 4         | 4.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 3         | 3.66%   |
| Intel AX201 Bluetooth                          | 3         | 3.66%   |
| Dell BCM20702A0 Bluetooth Module               | 3         | 3.66%   |
| Apple Bluetooth Host Controller                | 3         | 3.66%   |
| Realtek Bluetooth Radio                        | 2         | 2.44%   |
| Intel Wireless-AC 3168 Bluetooth               | 2         | 2.44%   |
| Broadcom BCM43142 Bluetooth 4.0                | 2         | 2.44%   |
| Realtek RTL8723B Bluetooth                     | 1         | 1.22%   |
| Qualcomm Atheros Bluetooth USB Host Controller | 1         | 1.22%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 1.22%   |
| Lite-On Wireless_Device                        | 1         | 1.22%   |
| Lite-On Atheros AR3012 Bluetooth               | 1         | 1.22%   |
| IMC Networks Bluetooth Device                  | 1         | 1.22%   |
| IMC Networks Bluetooth                         | 1         | 1.22%   |
| IMC Networks BCM20702A0                        | 1         | 1.22%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 1.22%   |
| Dell Wireless 360 Bluetooth                    | 1         | 1.22%   |
| Dell Wireless 355 Bluetooth                    | 1         | 1.22%   |
| Dell Wireless 350 Bluetooth                    | 1         | 1.22%   |
| Broadcom HP Portable SoftSailing               | 1         | 1.22%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 1.22%   |
| Apple Bluetooth HCI                            | 1         | 1.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 90        | 71.43%  |
| AMD                 | 21        | 16.67%  |
| Nvidia              | 11        | 8.73%   |
| Logitech            | 2         | 1.59%   |
| Sony                | 1         | 0.79%   |
| C-Media Electronics | 1         | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 9.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 6.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 6.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 5.19%   |
| AMD FCH Azalia Controller                                                                         | 8         | 5.19%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 5.19%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 4.55%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 3.9%    |
| Intel 8 Series HD Audio Controller                                                                | 6         | 3.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 3.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 3.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 3.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 2.6%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.95%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.95%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.95%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.95%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 1.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.3%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.3%    |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.3%    |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.3%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.3%    |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1         | 0.65%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.65%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.65%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.65%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.65%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.65%   |
| Logitech Logi USB Headset                                                                         | 1         | 0.65%   |
| Logitech H390 headset with microphone                                                             | 1         | 0.65%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 21        | 30%     |
| Samsung Electronics | 17        | 24.29%  |
| Micron Technology   | 10        | 14.29%  |
| Unknown (ABCD)      | 4         | 5.71%   |
| Kingston            | 4         | 5.71%   |
| Crucial             | 4         | 5.71%   |
| Unknown             | 2         | 2.86%   |
| Ramaxel Technology  | 2         | 2.86%   |
| Nanya Technology    | 2         | 2.86%   |
| A-DATA Technology   | 2         | 2.86%   |
| Sesame              | 1         | 1.43%   |
| Unknown             | 1         | 1.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 5.48%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 4.11%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 3         | 4.11%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 2.74%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.74%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 2.74%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 2.74%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s             | 2         | 2.74%   |
| A-DATA RAM AD73I1B1674EU 2GB SODIMM DDR3 1334MT/s                | 2         | 2.74%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.37%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 1.37%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.37%   |
| SK hynix RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 1.37%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s          | 1         | 1.37%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.37%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.37%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.37%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.37%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.37%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.37%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.37%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.37%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.37%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.37%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.37%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.37%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.37%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.37%   |
| Sesame RAM S939A2SGS-ITR 8GB SODIMM DDR3 2667MT/s                | 1         | 1.37%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 1         | 1.37%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 4199MT/s                 | 1         | 1.37%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 1         | 1.37%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 1         | 1.37%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.37%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.37%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.37%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.37%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.37%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 1.37%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 1.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 23        | 42.59%  |
| DDR4   | 18        | 33.33%  |
| LPDDR4 | 7         | 12.96%  |
| SDRAM  | 3         | 5.56%   |
| DDR2   | 2         | 3.7%    |
| LPDDR3 | 1         | 1.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 50        | 92.59%  |
| Row Of Chips | 3         | 5.56%   |
| DIMM         | 1         | 1.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 25        | 41.67%  |
| 8192  | 17        | 28.33%  |
| 2048  | 11        | 18.33%  |
| 16384 | 7         | 11.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 18        | 28.57%  |
| 2400  | 10        | 15.87%  |
| 2667  | 9         | 14.29%  |
| 1333  | 6         | 9.52%   |
| 3200  | 4         | 6.35%   |
| 2133  | 3         | 4.76%   |
| 1334  | 3         | 4.76%   |
| 4199  | 2         | 3.17%   |
| 3266  | 2         | 3.17%   |
| 4267  | 1         | 1.59%   |
| 2048  | 1         | 1.59%   |
| 1867  | 1         | 1.59%   |
| 1067  | 1         | 1.59%   |
| 975   | 1         | 1.59%   |
| 667   | 1         | 1.59%   |

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
| Chicony Electronics                    | 18        | 18.37%  |
| Microdia                               | 14        | 14.29%  |
| IMC Networks                           | 11        | 11.22%  |
| Sunplus Innovation Technology          | 10        | 10.2%   |
| Realtek Semiconductor                  | 8         | 8.16%   |
| Suyin                                  | 7         | 7.14%   |
| Apple                                  | 5         | 5.1%    |
| Syntek                                 | 4         | 4.08%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.08%   |
| Silicon Motion                         | 3         | 3.06%   |
| Ricoh                                  | 3         | 3.06%   |
| Quanta                                 | 2         | 2.04%   |
| Primax Electronics                     | 2         | 2.04%   |
| Sonix Technology                       | 1         | 1.02%   |
| OmniVision Technologies                | 1         | 1.02%   |
| MacroSilicon                           | 1         | 1.02%   |
| Logitech                               | 1         | 1.02%   |
| globaloptics                           | 1         | 1.02%   |
| Bison Electronics                      | 1         | 1.02%   |
| Alcor Micro                            | 1         | 1.02%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                   | 6         | 6.12%   |
| Chicony Integrated Camera                                      | 5         | 5.1%    |
| IMC Networks Integrated Camera                                 | 4         | 4.08%   |
| Microdia Integrated_Webcam_HD                                  | 3         | 3.06%   |
| Microdia HP Webcam-101                                         | 3         | 3.06%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 3         | 3.06%   |
| Syntek Lenovo EasyCamera                                       | 2         | 2.04%   |
| Realtek Integrated Webcam HD                                   | 2         | 2.04%   |
| Microdia Sonix USB 2.0 Camera                                  | 2         | 2.04%   |
| Microdia Integrated Webcam                                     | 2         | 2.04%   |
| Microdia Dell Integrated HD Webcam                             | 2         | 2.04%   |
| IMC Networks HP TrueVision HD Camera                           | 2         | 2.04%   |
| Chicony USB2.0 HD UVC WebCam                                   | 2         | 2.04%   |
| Chicony Integrated HP HD Webcam                                | 2         | 2.04%   |
| Chicony HP Truevision HD                                       | 2         | 2.04%   |
| Chicony HD User Facing                                         | 2         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 2.04%   |
| Apple FaceTime HD Camera                                       | 2         | 2.04%   |
| Syntek Integrated Camera                                       | 1         | 1.02%   |
| Syntek EasyCamera                                              | 1         | 1.02%   |
| Suyin VGA Webcam                                               | 1         | 1.02%   |
| Suyin TOSHIBA Web Camera - HD                                  | 1         | 1.02%   |
| Suyin Laptop_Integrated_Webcam_HD                              | 1         | 1.02%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 1.02%   |
| Suyin HP TrueVision HD                                         | 1         | 1.02%   |
| Suyin Acer/Lenovo Webcam [CN0316]                              | 1         | 1.02%   |
| Suyin 1.3M HD WebCam                                           | 1         | 1.02%   |
| Sunplus Laptop_Integrated_Webcam_HD                            | 1         | 1.02%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 1.02%   |
| Sunplus Integrated_Webcam_FHD                                  | 1         | 1.02%   |
| Sunplus HP Wide Vision HD                                      | 1         | 1.02%   |
| Sonix HP Webcam-101                                            | 1         | 1.02%   |
| Silicon Motion WebCam SCB-0385N                                | 1         | 1.02%   |
| Silicon Motion WebCam SC-10HDD13335N                           | 1         | 1.02%   |
| Silicon Motion Real HD WebCam                                  | 1         | 1.02%   |
| Ricoh Laptop_Integrated_Webcam_FHD                             | 1         | 1.02%   |
| Ricoh Integrated Webcam                                        | 1         | 1.02%   |
| Ricoh HD Webcam                                                | 1         | 1.02%   |
| Realtek USB2.0 camera                                          | 1         | 1.02%   |
| Realtek LG Camera                                              | 1         | 1.02%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 46.67%  |
| Synaptics                  | 3         | 20%     |
| Elan Microelectronics      | 2         | 13.33%  |
| STMicroelectronics         | 1         | 6.67%   |
| Shenzhen Goodix Technology | 1         | 6.67%   |
| LighTuning Technology      | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader        | 2         | 13.33%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 13.33%  |
| Elan ELAN:ARM-M4                                  | 2         | 13.33%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 6.67%   |
| Validity Sensors VFS491                           | 1         | 6.67%   |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 6.67%   |
| Validity Sensors Synaptics WBDI                   | 1         | 6.67%   |
| Validity Sensors Fingerprint scanner              | 1         | 6.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 6.67%   |
| STMicroelectronics Fingerprint Reader             | 1         | 6.67%   |
| Shenzhen Goodix  FingerPrint Device               | 1         | 6.67%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 66.67%  |
| O2 Micro    | 2         | 16.67%  |
| Alcor Micro | 2         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 16.67%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 8.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 8.33%   |
| Broadcom 58200                                                               | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 78        | 69.03%  |
| 1     | 27        | 23.89%  |
| 2     | 8         | 7.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 15        | 34.88%  |
| Chipcard              | 10        | 23.26%  |
| Graphics card         | 7         | 16.28%  |
| Net/wireless          | 3         | 6.98%   |
| Multimedia controller | 3         | 6.98%   |
| Storage               | 2         | 4.65%   |
| Card reader           | 1         | 2.33%   |
| Camera                | 1         | 2.33%   |
| Bluetooth             | 1         | 2.33%   |

