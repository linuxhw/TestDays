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

Total: 186

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | X540YA                      | [b3641f90e8](https://linux-hardware.org/?probe=b3641f90e8) | Jan 12, 2024 |
| Apple         | MacBookPro14,2              | [0d3413c236](https://linux-hardware.org/?probe=0d3413c236) | Jan 09, 2024 |
| HP            | Stream Laptop 14-ax0XX      | [4434600249](https://linux-hardware.org/?probe=4434600249) | Jan 01, 2024 |
| HP            | ProBook 11 G2               | [6cf8228f10](https://linux-hardware.org/?probe=6cf8228f10) | Dec 31, 2023 |
| HP            | ProBook 11 G2               | [3ad144c68e](https://linux-hardware.org/?probe=3ad144c68e) | Dec 28, 2023 |
| Apple         | MacBookAir7,2               | [03b1209523](https://linux-hardware.org/?probe=03b1209523) | Dec 24, 2023 |
| Apple         | MacBookAir7,2               | [b7f3ca9ba4](https://linux-hardware.org/?probe=b7f3ca9ba4) | Dec 23, 2023 |
| VTEX          | NOTEBOOK                    | [972b407abc](https://linux-hardware.org/?probe=972b407abc) | Dec 22, 2023 |
| Apple         | MacBookPro14,2              | [e13dae2abd](https://linux-hardware.org/?probe=e13dae2abd) | Dec 20, 2023 |
| Unknown       | Unknown                     | [176fc09667](https://linux-hardware.org/?probe=176fc09667) | Dec 08, 2023 |
| Unknown       | Unknown                     | [cbabf31d17](https://linux-hardware.org/?probe=cbabf31d17) | Dec 07, 2023 |
| Dell          | Latitude E6420              | [dab1a90459](https://linux-hardware.org/?probe=dab1a90459) | Nov 22, 2023 |
| Unknown       | Unknown                     | [5e4b279442](https://linux-hardware.org/?probe=5e4b279442) | Nov 16, 2023 |
| Unknown       | Unknown                     | [2db8bb3ceb](https://linux-hardware.org/?probe=2db8bb3ceb) | Nov 14, 2023 |
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
| Ubuntu 20.04        | 16        | 12.9%   |
| Ubuntu 22.04        | 8         | 6.45%   |
| Ubuntu 18.04        | 7         | 5.65%   |
| Fedora 38           | 5         | 4.03%   |
| OpenMandriva 4.3    | 4         | 3.23%   |
| Fedora 36           | 4         | 3.23%   |
| Arch Rolling        | 4         | 3.23%   |
| Zorin 16            | 3         | 2.42%   |
| Manjaro             | 3         | 2.42%   |
| Fedora 37           | 3         | 2.42%   |
| Debian 11           | 3         | 2.42%   |
| Ubuntu 21.10        | 2         | 1.61%   |
| Pop!_OS 20.10       | 2         | 1.61%   |
| OpenMandriva 4.2    | 2         | 1.61%   |
| OpenMandriva 23.08  | 2         | 1.61%   |
| Linux Mint 20.3     | 2         | 1.61%   |
| Linux Mint 20.1     | 2         | 1.61%   |
| Kali 2023.4         | 2         | 1.61%   |
| Kali 2023.3         | 2         | 1.61%   |
| Fedora 39           | 2         | 1.61%   |
| ArcoLinux Rolling   | 2         | 1.61%   |
| Xubuntu 19.10       | 1         | 0.81%   |
| Xubuntu 18.04       | 1         | 0.81%   |
| Void Linux Rolling  | 1         | 0.81%   |
| Ubuntu MATE 22.04   | 1         | 0.81%   |
| Ubuntu Budgie 22.04 | 1         | 0.81%   |
| Ubuntu Budgie 21.10 | 1         | 0.81%   |
| Ubuntu Budgie 20.04 | 1         | 0.81%   |
| Ubuntu 23.04        | 1         | 0.81%   |
| Ubuntu 22.10        | 1         | 0.81%   |
| Ubuntu 21.04        | 1         | 0.81%   |
| Ubuntu 19.04        | 1         | 0.81%   |
| Solus 4.1           | 1         | 0.81%   |
| Pop!_OS 21.04       | 1         | 0.81%   |
| Pop!_OS 20.04       | 1         | 0.81%   |
| OpenMandriva 23.01  | 1         | 0.81%   |
| MX 21               | 1         | 0.81%   |
| Manjaro 23.1.1      | 1         | 0.81%   |
| Manjaro 22.0.0      | 1         | 0.81%   |
| Manjaro 21.1.2      | 1         | 0.81%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 35        | 28.93%  |
| Fedora        | 18        | 14.88%  |
| Linux Mint    | 10        | 8.26%   |
| OpenMandriva  | 9         | 7.44%   |
| Manjaro       | 7         | 5.79%   |
| Debian        | 5         | 4.13%   |
| Arch          | 5         | 4.13%   |
| Pop!_OS       | 4         | 3.31%   |
| Kali          | 4         | 3.31%   |
| Zorin         | 3         | 2.48%   |
| Ubuntu Budgie | 3         | 2.48%   |
| Xubuntu       | 2         | 1.65%   |
| KDE neon      | 2         | 1.65%   |
| Clear Linux   | 2         | 1.65%   |
| ArcoLinux     | 2         | 1.65%   |
| Void Linux    | 1         | 0.83%   |
| Ubuntu MATE   | 1         | 0.83%   |
| Solus         | 1         | 0.83%   |
| MX            | 1         | 0.83%   |
| Lubuntu       | 1         | 0.83%   |
| LMDE          | 1         | 0.83%   |
| Kubuntu       | 1         | 0.83%   |
| Endless       | 1         | 0.83%   |
| Elementary    | 1         | 0.83%   |
| Archcraft     | 1         | 0.83%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-48-generic        | 4         | 2.92%   |
| 5.16.7-desktop-1omv4003 | 4         | 2.92%   |
| 5.4.0-42-generic        | 3         | 2.19%   |
| 5.13.0-22-generic       | 3         | 2.19%   |
| 6.5.0-kali3-amd64       | 2         | 1.46%   |
| 6.4.8-desktop-2omv2390  | 2         | 1.46%   |
| 5.4.0-77-generic        | 2         | 1.46%   |
| 5.4.0-52-generic        | 2         | 1.46%   |
| 5.4.0-33-generic        | 2         | 1.46%   |
| 5.3.0-51-generic        | 2         | 1.46%   |
| 5.19.0-46-generic       | 2         | 1.46%   |
| 5.15.0-76-generic       | 2         | 1.46%   |
| 5.15.0-58-generic       | 2         | 1.46%   |
| 5.15.0-53-generic       | 2         | 1.46%   |
| 5.15.0-41-generic       | 2         | 1.46%   |
| 6.6.9-200.fc39.x86_64   | 1         | 0.73%   |
| 6.6.8-200.fc39.x86_64   | 1         | 0.73%   |
| 6.6.8-2-MANJARO         | 1         | 0.73%   |
| 6.6.6-200.fc39.x86_64   | 1         | 0.73%   |
| 6.6.1-arch1-1           | 1         | 0.73%   |
| 6.5.8-200.fc38.x86_64   | 1         | 0.73%   |
| 6.5.7-200.fc38.x86_64   | 1         | 0.73%   |
| 6.5.6-200.fc38.x86_64   | 1         | 0.73%   |
| 6.5.0-kali2-amd64       | 1         | 0.73%   |
| 6.4.6-arch1-1           | 1         | 0.73%   |
| 6.4.14-200.fc38.x86_64  | 1         | 0.73%   |
| 6.3.7-x64v2-xanmod1-1   | 1         | 0.73%   |
| 6.3.0-kali1-amd64       | 1         | 0.73%   |
| 6.2.7-arch1-1           | 1         | 0.73%   |
| 6.2.14-300.fc38.x86_64  | 1         | 0.73%   |
| 6.2.12-1-MANJARO        | 1         | 0.73%   |
| 6.2.0-20-generic        | 1         | 0.73%   |
| 6.1.5-200.fc37.x86_64   | 1         | 0.73%   |
| 6.1.1-desktop-1omv2290  | 1         | 0.73%   |
| 6.0.6-300.fc37.x86_64   | 1         | 0.73%   |
| 6.0.14-300.fc37.x86_64  | 1         | 0.73%   |
| 5.9.12-xanmod1          | 1         | 0.73%   |
| 5.9.11-arch2-1          | 1         | 0.73%   |
| 5.9.1-arch1-1           | 1         | 0.73%   |
| 5.8.8-arch1-1           | 1         | 0.73%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 16.28%  |
| 5.15.0  | 13        | 10.08%  |
| 5.13.0  | 8         | 6.2%    |
| 5.3.0   | 6         | 4.65%   |
| 5.11.0  | 6         | 4.65%   |
| 5.19.0  | 5         | 3.88%   |
| 5.16.7  | 4         | 3.1%    |
| 5.10.0  | 4         | 3.1%    |
| 6.5.0   | 3         | 2.33%   |
| 5.0.0   | 3         | 2.33%   |
| 6.6.8   | 2         | 1.55%   |
| 6.4.8   | 2         | 1.55%   |
| 4.19.0  | 2         | 1.55%   |
| 6.6.9   | 1         | 0.78%   |
| 6.6.6   | 1         | 0.78%   |
| 6.6.1   | 1         | 0.78%   |
| 6.5.8   | 1         | 0.78%   |
| 6.5.7   | 1         | 0.78%   |
| 6.5.6   | 1         | 0.78%   |
| 6.4.6   | 1         | 0.78%   |
| 6.4.14  | 1         | 0.78%   |
| 6.3.7   | 1         | 0.78%   |
| 6.3.0   | 1         | 0.78%   |
| 6.2.7   | 1         | 0.78%   |
| 6.2.14  | 1         | 0.78%   |
| 6.2.12  | 1         | 0.78%   |
| 6.2.0   | 1         | 0.78%   |
| 6.1.5   | 1         | 0.78%   |
| 6.1.1   | 1         | 0.78%   |
| 6.0.6   | 1         | 0.78%   |
| 6.0.14  | 1         | 0.78%   |
| 5.9.12  | 1         | 0.78%   |
| 5.9.11  | 1         | 0.78%   |
| 5.9.1   | 1         | 0.78%   |
| 5.8.8   | 1         | 0.78%   |
| 5.8.15  | 1         | 0.78%   |
| 5.8.12  | 1         | 0.78%   |
| 5.8.0   | 1         | 0.78%   |
| 5.7.10  | 1         | 0.78%   |
| 5.6.19  | 1         | 0.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 23        | 18.11%  |
| 5.15    | 15        | 11.81%  |
| 5.13    | 9         | 7.09%   |
| 5.19    | 8         | 6.3%    |
| 5.11    | 8         | 6.3%    |
| 5.10    | 7         | 5.51%   |
| 6.5     | 6         | 4.72%   |
| 5.3     | 6         | 4.72%   |
| 6.6     | 4         | 3.15%   |
| 6.4     | 4         | 3.15%   |
| 6.2     | 4         | 3.15%   |
| 5.8     | 4         | 3.15%   |
| 5.16    | 4         | 3.15%   |
| 5.0     | 4         | 3.15%   |
| 5.9     | 3         | 2.36%   |
| 4.19    | 3         | 2.36%   |
| 6.3     | 2         | 1.57%   |
| 6.1     | 2         | 1.57%   |
| 6.0     | 2         | 1.57%   |
| 5.18    | 2         | 1.57%   |
| 5.12    | 2         | 1.57%   |
| 5.7     | 1         | 0.79%   |
| 5.6     | 1         | 0.79%   |
| 5.17    | 1         | 0.79%   |
| 4.18    | 1         | 0.79%   |
| 4.15    | 1         | 0.79%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 116       | 97.48%  |
| i686   | 3         | 2.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 56        | 45.53%  |
| KDE5       | 25        | 20.33%  |
| XFCE       | 13        | 10.57%  |
| X-Cinnamon | 8         | 6.5%    |
| Unknown    | 8         | 6.5%    |
| Budgie     | 4         | 3.25%   |
| KDE        | 3         | 2.44%   |
| MATE       | 2         | 1.63%   |
| sway       | 1         | 0.81%   |
| LXQt       | 1         | 0.81%   |
| LXDE       | 1         | 0.81%   |
| DWM        | 1         | 0.81%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 89        | 72.95%  |
| Wayland | 29        | 23.77%  |
| Unknown | 4         | 3.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 61        | 50%     |
| SDDM    | 17        | 13.93%  |
| LightDM | 14        | 11.48%  |
| GDM3    | 13        | 10.66%  |
| GDM     | 13        | 10.66%  |
| TDM     | 4         | 3.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 68        | 54.84%  |
| es_DO   | 32        | 25.81%  |
| Unknown | 7         | 5.65%   |
| es_ES   | 5         | 4.03%   |
| es_MX   | 4         | 3.23%   |
| C       | 4         | 3.23%   |
| en_CA   | 2         | 1.61%   |
| ru_RU   | 1         | 0.81%   |
| fr_FR   | 1         | 0.81%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 61        | 51.26%  |
| BIOS | 58        | 48.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 84        | 68.85%  |
| Btrfs   | 19        | 15.57%  |
| Overlay | 11        | 9.02%   |
| Tmpfs   | 3         | 2.46%   |
| Xfs     | 2         | 1.64%   |
| Zfs     | 1         | 0.82%   |
| F2fs    | 1         | 0.82%   |
| Unknown | 1         | 0.82%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 62        | 51.24%  |
| GPT     | 50        | 41.32%  |
| MBR     | 9         | 7.44%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 102       | 85%     |
| Yes       | 18        | 15%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 89        | 74.17%  |
| Yes       | 31        | 25.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 35        | 29.41%  |
| Hewlett-Packard     | 22        | 18.49%  |
| Lenovo              | 18        | 15.13%  |
| ASUSTek Computer    | 10        | 8.4%    |
| Apple               | 6         | 5.04%   |
| Acer                | 6         | 5.04%   |
| Unknown             | 4         | 3.36%   |
| VTEX                | 2         | 1.68%   |
| Samsung Electronics | 2         | 1.68%   |
| MSI                 | 2         | 1.68%   |
| Google              | 2         | 1.68%   |
| EVOO                | 2         | 1.68%   |
| Toshiba             | 1         | 0.84%   |
| TODOS INDUSTRIAL    | 1         | 0.84%   |
| SAELITE             | 1         | 0.84%   |
| Nuvision            | 1         | 0.84%   |
| LG Electronics      | 1         | 0.84%   |
| Fujitsu             | 1         | 0.84%   |
| Eluktronics         | 1         | 0.84%   |
| ECS                 | 1         | 0.84%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 4         | 3.36%   |
| VTEX NOTEBOOK                                     | 2         | 1.68%   |
| Lenovo IdeaPad 330S-15IKB 81F5                    | 2         | 1.68%   |
| HP Pavilion Notebook                              | 2         | 1.68%   |
| HP Laptop 15-dy1xxx                               | 2         | 1.68%   |
| HP EliteBook 8460p                                | 2         | 1.68%   |
| EVOO EV-C-116-7                                   | 2         | 1.68%   |
| Dell Latitude E6540                               | 2         | 1.68%   |
| Dell Latitude E6430                               | 2         | 1.68%   |
| Dell Latitude E6420                               | 2         | 1.68%   |
| Dell Latitude E6410                               | 2         | 1.68%   |
| Dell Latitude 5590                                | 2         | 1.68%   |
| Dell Inspiron 5570                                | 2         | 1.68%   |
| Dell Inspiron 5555                                | 2         | 1.68%   |
| Apple MacBookPro8,1                               | 2         | 1.68%   |
| Toshiba Satellite C55-A                           | 1         | 0.84%   |
| TODOS INDUSTRIAL Easytouch_2022_V1                | 1         | 0.84%   |
| Samsung RV420/RV520/RV720/E3530/S3530/E3420/E3520 | 1         | 0.84%   |
| Samsung 905S3G/906S3G/915S3G/9305SG               | 1         | 0.84%   |
| SAELITE ES1AU11                                   | 1         | 0.84%   |
| Nuvision NES11                                    | 1         | 0.84%   |
| MSI GE62 6QC                                      | 1         | 0.84%   |
| MSI CR70 2M/CX70 2OC/CX70 2OD                     | 1         | 0.84%   |
| LG 17ZT90P-G.AX33U1                               | 1         | 0.84%   |
| Lenovo Z50-75 80EC                                | 1         | 0.84%   |
| Lenovo ThinkPad W540 20BHS0GB06                   | 1         | 0.84%   |
| Lenovo ThinkPad T490 20N3S7BC02                   | 1         | 0.84%   |
| Lenovo ThinkPad T480s 20L7CTO1WW                  | 1         | 0.84%   |
| Lenovo ThinkPad T470 20HD004AUS                   | 1         | 0.84%   |
| Lenovo ThinkPad T420s 41732BU                     | 1         | 0.84%   |
| Lenovo ThinkPad T410 2537N99                      | 1         | 0.84%   |
| Lenovo ThinkPad P43s 20RH0013US                   | 1         | 0.84%   |
| Lenovo ThinkPad E470 20H1006DUS                   | 1         | 0.84%   |
| Lenovo ThinkBook 14s-IWL 20RM                     | 1         | 0.84%   |
| Lenovo Legion 5 15ARH05 82B5                      | 1         | 0.84%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4              | 1         | 0.84%   |
| Lenovo IdeaPad 320-15IKB 80XL                     | 1         | 0.84%   |
| Lenovo IdeaPad 3 15ALC6 82KU                      | 1         | 0.84%   |
| Lenovo G505s 20255                                | 1         | 0.84%   |
| Lenovo G40-70 20369                               | 1         | 0.84%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 21        | 17.65%  |
| Dell Inspiron              | 11        | 9.24%   |
| Lenovo ThinkPad            | 8         | 6.72%   |
| Lenovo IdeaPad             | 5         | 4.2%    |
| HP Pavilion                | 5         | 4.2%    |
| Acer Aspire                | 5         | 4.2%    |
| HP Laptop                  | 4         | 3.36%   |
| Unknown                    | 4         | 3.36%   |
| HP ProBook                 | 3         | 2.52%   |
| HP EliteBook               | 3         | 2.52%   |
| ASUS VivoBook              | 3         | 2.52%   |
| VTEX NOTEBOOK              | 2         | 1.68%   |
| EVOO EV-C-116-7            | 2         | 1.68%   |
| Dell Vostro                | 2         | 1.68%   |
| Apple MacBookPro8          | 2         | 1.68%   |
| Toshiba Satellite          | 1         | 0.84%   |
| TODOS INDUSTRIAL Easytouch | 1         | 0.84%   |
| Samsung RV420              | 1         | 0.84%   |
| Samsung 905S3G             | 1         | 0.84%   |
| SAELITE ES1AU11            | 1         | 0.84%   |
| Nuvision NES11             | 1         | 0.84%   |
| MSI GE62                   | 1         | 0.84%   |
| MSI CR70                   | 1         | 0.84%   |
| LG 17ZT90P-G.AX33U1        | 1         | 0.84%   |
| Lenovo Z50-75              | 1         | 0.84%   |
| Lenovo ThinkBook           | 1         | 0.84%   |
| Lenovo Legion              | 1         | 0.84%   |
| Lenovo G505s               | 1         | 0.84%   |
| Lenovo G40-70              | 1         | 0.84%   |
| HP Stream                  | 1         | 0.84%   |
| HP OMEN                    | 1         | 0.84%   |
| HP Notebook                | 1         | 0.84%   |
| HP G60                     | 1         | 0.84%   |
| HP ENVY                    | 1         | 0.84%   |
| HP 255                     | 1         | 0.84%   |
| HP 250                     | 1         | 0.84%   |
| Google Winky               | 1         | 0.84%   |
| Google Kip                 | 1         | 0.84%   |
| Fujitsu LIFEBOOK           | 1         | 0.84%   |
| Eluktronics P670RE3        | 1         | 0.84%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 13        | 10.92%  |
| 2014 | 12        | 10.08%  |
| 2019 | 11        | 9.24%   |
| 2011 | 11        | 9.24%   |
| 2017 | 10        | 8.4%    |
| 2013 | 10        | 8.4%    |
| 2012 | 8         | 6.72%   |
| 2018 | 7         | 5.88%   |
| 2016 | 7         | 5.88%   |
| 2020 | 6         | 5.04%   |
| 2010 | 5         | 4.2%    |
| 2008 | 5         | 4.2%    |
| 2015 | 4         | 3.36%   |
| 2009 | 3         | 2.52%   |
| 2007 | 3         | 2.52%   |
| 2022 | 2         | 1.68%   |
| 2006 | 1         | 0.84%   |
| 2005 | 1         | 0.84%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 119       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 115       | 96.64%  |
| Enabled  | 4         | 3.36%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 117       | 98.32%  |
| Yes  | 2         | 1.68%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 39        | 32.5%   |
| 4.01-8.0   | 34        | 28.33%  |
| 8.01-16.0  | 21        | 17.5%   |
| 16.01-24.0 | 13        | 10.83%  |
| 2.01-3.0   | 4         | 3.33%   |
| 1.01-2.0   | 4         | 3.33%   |
| 32.01-64.0 | 3         | 2.5%    |
| 24.01-32.0 | 2         | 1.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 46        | 34.85%  |
| 2.01-3.0  | 37        | 28.03%  |
| 3.01-4.0  | 26        | 19.7%   |
| 4.01-8.0  | 16        | 12.12%  |
| 0.51-1.0  | 6         | 4.55%   |
| 8.01-16.0 | 1         | 0.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 88        | 73.33%  |
| 2      | 32        | 26.67%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 71        | 59.17%  |
| Yes       | 49        | 40.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 75.83%  |
| No        | 29        | 24.17%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 117       | 98.32%  |
| No        | 2         | 1.68%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 73.33%  |
| No        | 32        | 26.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Dominican Republic | 119       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Santo Domingo Este         | 68        | 54.4%   |
| Santiago de los Caballeros | 14        | 11.2%   |
| Santo Domingo              | 12        | 9.6%    |
| La Romana                  | 5         | 4%      |
| Concepción de la Vega     | 5         | 4%      |
| Cabarete                   | 3         | 2.4%    |
| Santa Cruz de Barahona     | 2         | 1.6%    |
| Constanza                  | 2         | 1.6%    |
| Alejandro Bass             | 2         | 1.6%    |
| Sosua, Cabarete            | 1         | 0.8%    |
| Santo Domingo Oeste        | 1         | 0.8%    |
| San Pedro de Macorís      | 1         | 0.8%    |
| San Juan                   | 1         | 0.8%    |
| San Cristobal              | 1         | 0.8%    |
| Punta Cana                 | 1         | 0.8%    |
| Los Hidalgos               | 1         | 0.8%    |
| Guaymate                   | 1         | 0.8%    |
| Cancino                    | 1         | 0.8%    |
| Boca Chica                 | 1         | 0.8%    |
| Baní                      | 1         | 0.8%    |
| Bajos de Haina             | 1         | 0.8%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 24        | 31     | 16.67%  |
| Samsung Electronics         | 18        | 19     | 12.5%   |
| Toshiba                     | 14        | 17     | 9.72%   |
| WDC                         | 11        | 14     | 7.64%   |
| SanDisk                     | 9         | 12     | 6.25%   |
| Hitachi                     | 9         | 10     | 6.25%   |
| Kingston                    | 8         | 8      | 5.56%   |
| Unknown                     | 7         | 8      | 4.86%   |
| SK hynix                    | 6         | 7      | 4.17%   |
| AirDisk                     | 4         | 4      | 2.78%   |
| Intel                       | 3         | 5      | 2.08%   |
| China                       | 3         | 4      | 2.08%   |
| Unknown                     | 3         | 3      | 2.08%   |
| Transcend                   | 2         | 2      | 1.39%   |
| SPCC                        | 2         | 2      | 1.39%   |
| Micron/Crucial Technology   | 2         | 2      | 1.39%   |
| Micron Technology           | 2         | 2      | 1.39%   |
| Indilinx                    | 2         | 2      | 1.39%   |
| FORESEE                     | 2         | 2      | 1.39%   |
| Apple                       | 2         | 7      | 1.39%   |
| UMIS                        | 1         | 1      | 0.69%   |
| Supersonic                  | 1         | 1      | 0.69%   |
| SABRENT                     | 1         | 1      | 0.69%   |
| PNY                         | 1         | 1      | 0.69%   |
| OCZ                         | 1         | 1      | 0.69%   |
| LITEONIT                    | 1         | 2      | 0.69%   |
| Kingston Technology Company | 1         | 1      | 0.69%   |
| HGST                        | 1         | 1      | 0.69%   |
| Hewlett-Packard             | 1         | 1      | 0.69%   |
| Eluktro                     | 1         | 1      | 0.69%   |
| A-DATA Technology           | 1         | 1      | 0.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| AirDisk 128GB SSD                                 | 4         | 2.68%   |
| Unknown MMC Card  32GB                            | 3         | 2.01%   |
| Toshiba MQ04ABF100 1TB                            | 3         | 2.01%   |
| Seagate ST500LM000-1EJ162 500GB                   | 3         | 2.01%   |
| Seagate ST1000LM035-1RK172 1TB                    | 3         | 2.01%   |
| Unknown                                           | 3         | 2.01%   |
| Unknown MMC Card  16GB                            | 2         | 1.34%   |
| Unknown MMC Card  128GB                           | 2         | 1.34%   |
| Toshiba MQ01ACF050 500GB                          | 2         | 1.34%   |
| Toshiba MK3275GSX 320GB                           | 2         | 1.34%   |
| Seagate ST9250315AS 250GB                         | 2         | 1.34%   |
| Seagate ST500LT012-1DG142 500GB                   | 2         | 1.34%   |
| Seagate ST500LM021-1KJ152 500GB                   | 2         | 1.34%   |
| Seagate ST1000LM049-2GH172 1TB                    | 2         | 1.34%   |
| SanDisk NVMe SSD Drive 256GB                      | 2         | 1.34%   |
| Samsung SSD 860 EVO 500GB                         | 2         | 1.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 1.34%   |
| Kingston SA400S37240G 240GB SSD                   | 2         | 1.34%   |
| Kingston SA400S37120G 120GB SSD                   | 2         | 1.34%   |
| Intel HBRPEKNX0101AHO 16GB                        | 2         | 1.34%   |
| Intel HBRPEKNX0101AH 256GB                        | 2         | 1.34%   |
| Indilinx IND-S3N80P/128G 128GB                    | 2         | 1.34%   |
| FORESEE 128GB SSD                                 | 2         | 1.34%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                    | 1         | 0.67%   |
| WDC WD5000LPLX-08ZNTT0 500GB                      | 1         | 0.67%   |
| WDC WD3200LPVX-75V0TT0 320GB                      | 1         | 0.67%   |
| WDC WD3200BEVT-75A23T0 320GB                      | 1         | 0.67%   |
| WDC WD2500BEVT-75A23T0 250GB                      | 1         | 0.67%   |
| WDC WD2500BEVS-22UST0 250GB                       | 1         | 0.67%   |
| WDC WD2500BEKT-60A25T1 250GB                      | 1         | 0.67%   |
| WDC WD1600BEVT-75ZCT1 160GB                       | 1         | 0.67%   |
| WDC WD10SPZX-24Z10T0 1TB                          | 1         | 0.67%   |
| WDC WD10JPVX-60JC3T1 1TB                          | 1         | 0.67%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 1         | 0.67%   |
| Unknown MMC Card  64GB                            | 1         | 0.67%   |
| UMIS RPJTJ256MEE1OWX 256GB                        | 1         | 0.67%   |
| Transcend TS256GSSD340 256GB                      | 1         | 0.67%   |
| Transcend TS128GSSD370S 128GB                     | 1         | 0.67%   |
| Toshiba NVMe SSD Drive 1024GB                     | 1         | 0.67%   |
| Toshiba MQ01ABF050 500GB                          | 1         | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 29     | 40.35%  |
| Toshiba             | 13        | 16     | 22.81%  |
| WDC                 | 10        | 13     | 17.54%  |
| Hitachi             | 9         | 10     | 15.79%  |
| Samsung Electronics | 1         | 1      | 1.75%   |
| HGST                | 1         | 1      | 1.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 12     | 21.57%  |
| Kingston            | 7         | 7      | 13.73%  |
| SanDisk             | 6         | 9      | 11.76%  |
| AirDisk             | 4         | 4      | 7.84%   |
| China               | 3         | 4      | 5.88%   |
| Transcend           | 2         | 2      | 3.92%   |
| SPCC                | 2         | 2      | 3.92%   |
| SK hynix            | 2         | 2      | 3.92%   |
| FORESEE             | 2         | 2      | 3.92%   |
| WDC                 | 1         | 1      | 1.96%   |
| Supersonic          | 1         | 1      | 1.96%   |
| Seagate             | 1         | 2      | 1.96%   |
| SABRENT             | 1         | 1      | 1.96%   |
| PNY                 | 1         | 1      | 1.96%   |
| OCZ                 | 1         | 1      | 1.96%   |
| LITEONIT            | 1         | 2      | 1.96%   |
| Hewlett-Packard     | 1         | 1      | 1.96%   |
| Eluktro             | 1         | 1      | 1.96%   |
| Apple               | 1         | 1      | 1.96%   |
| A-DATA Technology   | 1         | 1      | 1.96%   |
| Unknown             | 1         | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 54        | 70     | 40.3%   |
| SSD     | 45        | 58     | 33.58%  |
| NVMe    | 23        | 32     | 17.16%  |
| MMC     | 10        | 11     | 7.46%   |
| Unknown | 2         | 2      | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 93        | 124    | 70.99%  |
| NVMe | 23        | 32     | 17.56%  |
| MMC  | 10        | 11     | 7.63%   |
| SAS  | 5         | 6      | 3.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 70        | 95     | 72.16%  |
| 0.51-1.0   | 24        | 29     | 24.74%  |
| 1.01-2.0   | 2         | 2      | 2.06%   |
| 4.01-10.0  | 1         | 2      | 1.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 40        | 32%     |
| 501-1000       | 22        | 17.6%   |
| 251-500        | 21        | 16.8%   |
| 1-20           | 12        | 9.6%    |
| 51-100         | 11        | 8.8%    |
| 1001-2000      | 6         | 4.8%    |
| 21-50          | 5         | 4%      |
| 2001-3000      | 4         | 3.2%    |
| Unknown        | 3         | 2.4%    |
| More than 3000 | 1         | 0.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 50        | 37.59%  |
| 21-50     | 26        | 19.55%  |
| 51-100    | 23        | 17.29%  |
| 101-250   | 14        | 10.53%  |
| 251-500   | 5         | 3.76%   |
| 1001-2000 | 5         | 3.76%   |
| 501-1000  | 5         | 3.76%   |
| Unknown   | 3         | 2.26%   |
| 2001-3000 | 2         | 1.5%    |

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
| Detected | 75        | 117    | 60%     |
| Works    | 35        | 41     | 28%     |
| Malfunc  | 14        | 14     | 11.2%   |
| Failed   | 1         | 1      | 0.8%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 85        | 66.93%  |
| AMD                          | 19        | 14.96%  |
| Samsung Electronics          | 7         | 5.51%   |
| SK hynix                     | 3         | 2.36%   |
| SanDisk                      | 3         | 2.36%   |
| Micron/Crucial Technology    | 2         | 1.57%   |
| Micron Technology            | 2         | 1.57%   |
| Kingston Technology Company  | 2         | 1.57%   |
| Union Memory (Shenzhen)      | 1         | 0.79%   |
| Toshiba America Info Systems | 1         | 0.79%   |
| Nvidia                       | 1         | 0.79%   |
| Apple                        | 1         | 0.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 18        | 13.33%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 15        | 11.11%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 11        | 8.15%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 11        | 8.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 5.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 5.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 2.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 2.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 2.96%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 2.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 2.22%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 2         | 1.48%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 2         | 1.48%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.48%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.48%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 2         | 1.48%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.48%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 2         | 1.48%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 1         | 0.74%   |
| Toshiba America Info Systems XG3 NVMe SSD Controller                           | 1         | 0.74%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1         | 0.74%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                          | 1         | 0.74%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 0.74%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 0.74%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 0.74%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.74%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 0.74%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                      | 1         | 0.74%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 1         | 0.74%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                 | 1         | 0.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.74%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 0.74%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 1         | 0.74%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 0.74%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 0.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 0.74%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 0.74%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 81        | 62.31%  |
| NVMe | 23        | 17.69%  |
| RAID | 16        | 12.31%  |
| IDE  | 10        | 7.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 98        | 82.35%  |
| AMD    | 21        | 17.65%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron N4120 CPU @ 1.10GHz           | 7         | 5.88%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 3.36%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 4         | 3.36%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 2.52%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 3         | 2.52%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.68%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 2         | 1.68%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.68%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 2         | 1.68%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.68%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.68%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 1.68%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 1.68%   |
| Intel Core i5-2415M CPU @ 2.30GHz           | 2         | 1.68%   |
| Intel Core i3-8130U CPU @ 2.20GHz           | 2         | 1.68%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 2         | 1.68%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 1.68%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 2         | 1.68%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 1.68%   |
| AMD A4-6210 APU with AMD Radeon R3 Graphics | 2         | 1.68%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.84%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 0.84%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.84%   |
| Intel Genuine CPU U4100 @ 1.30GHz           | 1         | 0.84%   |
| Intel Core i9-9980HK CPU @ 2.40GHz          | 1         | 0.84%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.84%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.84%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.84%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 0.84%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 0.84%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 1         | 0.84%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 0.84%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 0.84%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 0.84%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 0.84%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 0.84%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 0.84%   |
| Intel Core i5-7267U CPU @ 3.10GHz           | 1         | 0.84%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 0.84%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 1         | 0.84%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 33        | 27.73%  |
| Intel Core i7           | 20        | 16.81%  |
| Intel Celeron           | 19        | 15.97%  |
| Intel Core i3           | 11        | 9.24%   |
| Intel Core 2 Duo        | 4         | 3.36%   |
| AMD Ryzen 5             | 4         | 3.36%   |
| AMD Ryzen 7             | 3         | 2.52%   |
| AMD A10                 | 3         | 2.52%   |
| Other                   | 2         | 1.68%   |
| Intel Core 2            | 2         | 1.68%   |
| Intel Atom              | 2         | 1.68%   |
| AMD A8                  | 2         | 1.68%   |
| AMD A6                  | 2         | 1.68%   |
| AMD A4                  | 2         | 1.68%   |
| Intel Pentium Dual-Core | 1         | 0.84%   |
| Intel Pentium Dual      | 1         | 0.84%   |
| Intel Pentium           | 1         | 0.84%   |
| Intel Genuine           | 1         | 0.84%   |
| Intel Core i9           | 1         | 0.84%   |
| AMD Ryzen 3             | 1         | 0.84%   |
| AMD Quad-Core           | 1         | 0.84%   |
| AMD Mobile Sempron      | 1         | 0.84%   |
| AMD E2                  | 1         | 0.84%   |
| AMD A12                 | 1         | 0.84%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 76        | 63.87%  |
| 4      | 34        | 28.57%  |
| 6      | 4         | 3.36%   |
| 8      | 3         | 2.52%   |
| 1      | 2         | 1.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 119       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 78        | 65.55%  |
| 1      | 41        | 34.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 117       | 98.32%  |
| 32-bit         | 1         | 0.84%   |
| Unknown        | 1         | 0.84%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 32.79%  |
| 0x206a7    | 11        | 9.02%   |
| 0x306a9    | 7         | 5.74%   |
| 0x806e9    | 5         | 4.1%    |
| 0x40651    | 5         | 4.1%    |
| 0x806ea    | 4         | 3.28%   |
| 0x706a1    | 4         | 3.28%   |
| 0x1067a    | 4         | 3.28%   |
| 0x706a8    | 3         | 2.46%   |
| 0x306c3    | 3         | 2.46%   |
| 0x30678    | 3         | 2.46%   |
| 0x07030105 | 3         | 2.46%   |
| 0x806ec    | 2         | 1.64%   |
| 0x6f6      | 2         | 1.64%   |
| 0x506e3    | 2         | 1.64%   |
| 0x20655    | 2         | 1.64%   |
| 0x20652    | 2         | 1.64%   |
| 0x10676    | 2         | 1.64%   |
| 0x08600103 | 2         | 1.64%   |
| 0x806c1    | 1         | 0.82%   |
| 0x6fd      | 1         | 0.82%   |
| 0x506c9    | 1         | 0.82%   |
| 0x406c3    | 1         | 0.82%   |
| 0x106ca    | 1         | 0.82%   |
| 0x08608103 | 1         | 0.82%   |
| 0x08608102 | 1         | 0.82%   |
| 0x08108109 | 1         | 0.82%   |
| 0x08108102 | 1         | 0.82%   |
| 0x07030106 | 1         | 0.82%   |
| 0x0700010f | 1         | 0.82%   |
| 0x06006705 | 1         | 0.82%   |
| 0x0600611a | 1         | 0.82%   |
| 0x06006110 | 1         | 0.82%   |
| 0x06003106 | 1         | 0.82%   |
| 0x06001119 | 1         | 0.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 19        | 15.97%  |
| SandyBridge   | 11        | 9.24%   |
| Haswell       | 11        | 9.24%   |
| Goldmont plus | 11        | 9.24%   |
| IvyBridge     | 9         | 7.56%   |
| Silvermont    | 7         | 5.88%   |
| Westmere      | 6         | 5.04%   |
| Penryn        | 6         | 5.04%   |
| Puma          | 5         | 4.2%    |
| Skylake       | 4         | 3.36%   |
| Zen+          | 3         | 2.52%   |
| IceLake       | 3         | 2.52%   |
| Excavator     | 3         | 2.52%   |
| Core          | 3         | 2.52%   |
| Broadwell     | 3         | 2.52%   |
| Zen 2         | 2         | 1.68%   |
| TigerLake     | 2         | 1.68%   |
| Unknown       | 2         | 1.68%   |
| Zen 3         | 1         | 0.84%   |
| Steamroller   | 1         | 0.84%   |
| Piledriver    | 1         | 0.84%   |
| K8 Hammer     | 1         | 0.84%   |
| K10 Llano     | 1         | 0.84%   |
| Jaguar        | 1         | 0.84%   |
| Goldmont      | 1         | 0.84%   |
| CometLake     | 1         | 0.84%   |
| Bonnell       | 1         | 0.84%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 93        | 67.88%  |
| AMD    | 26        | 18.98%  |
| Nvidia | 18        | 13.14%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 7.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 7.04%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 6.34%   |
| Intel UHD Graphics 620                                                                   | 7         | 4.93%   |
| Intel HD Graphics 620                                                                    | 6         | 4.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 4.23%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 3.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 3.52%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.82%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 2.11%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.11%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 2.11%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2.11%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.41%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 1.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.41%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.41%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.41%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.41%   |
| Intel HD Graphics 530                                                                    | 2         | 1.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.41%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.41%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 2         | 1.41%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.41%   |
| AMD Mullins [Radeon R3 Graphics]                                                         | 2         | 1.41%   |
| AMD Lucienne                                                                             | 2         | 1.41%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.7%    |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.7%    |
| Nvidia GP108GLM [Quadro P520]                                                            | 1         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.7%    |
| Nvidia GM204M [GeForce GTX 960 OEM / 970M]                                               | 1         | 0.7%    |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.7%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.7%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.7%    |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.7%    |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.7%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.7%    |
| Nvidia G86M [GeForce 8400M GS]                                                           | 1         | 0.7%    |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                            | 1         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 79        | 66.39%  |
| 1 x AMD        | 16        | 13.45%  |
| Intel + Nvidia | 10        | 8.4%    |
| 1 x Nvidia     | 4         | 3.36%   |
| Intel + AMD    | 4         | 3.36%   |
| AMD + Nvidia   | 4         | 3.36%   |
| 2 x AMD        | 2         | 1.68%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 108       | 90.76%  |
| Proprietary | 9         | 7.56%   |
| Unknown     | 2         | 1.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 93        | 77.5%   |
| 0.01-0.5   | 10        | 8.33%   |
| 1.01-2.0   | 7         | 5.83%   |
| 0.51-1.0   | 7         | 5.83%   |
| 3.01-4.0   | 2         | 1.67%   |
| 2.01-3.0   | 1         | 0.83%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 30        | 22.22%  |
| BOE                     | 20        | 14.81%  |
| LG Display              | 18        | 13.33%  |
| Chimei Innolux          | 15        | 11.11%  |
| Samsung Electronics     | 13        | 9.63%   |
| Dell                    | 7         | 5.19%   |
| Chi Mei Optoelectronics | 5         | 3.7%    |
| Apple                   | 5         | 3.7%    |
| InfoVision              | 4         | 2.96%   |
| Hewlett-Packard         | 3         | 2.22%   |
| ZTR                     | 1         | 0.74%   |
| Westinghouse            | 1         | 0.74%   |
| Vizio                   | 1         | 0.74%   |
| Unknown (XXX)           | 1         | 0.74%   |
| STA                     | 1         | 0.74%   |
| Sony                    | 1         | 0.74%   |
| Philips                 | 1         | 0.74%   |
| PANDA                   | 1         | 0.74%   |
| MSI                     | 1         | 0.74%   |
| LG Philips              | 1         | 0.74%   |
| Lenovo                  | 1         | 0.74%   |
| KDC                     | 1         | 0.74%   |
| InnoLux Display         | 1         | 0.74%   |
| Goldstar                | 1         | 0.74%   |
| AOC                     | 1         | 0.74%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| InfoVision M116NWR1 R0 IVO0489 1366x768 256x144mm 11.6-inch           | 4         | 2.96%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 3         | 2.22%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch           | 2         | 1.48%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.48%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.48%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.48%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch         | 2         | 1.48%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch         | 2         | 1.48%   |
| AU Optronics LCD Monitor AUO11EC 1366x768 344x193mm 15.5-inch         | 2         | 1.48%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch         | 2         | 1.48%   |
| ZTR LCD Monitor ZTR0001 1366x768 309x173mm 13.9-inch                  | 1         | 0.74%   |
| Westinghouse EUM24F1G1 WDT1E64 1920x1080 530x300mm 24.0-inch          | 1         | 0.74%   |
| Vizio E24-C1 VIZ1005 1920x1080 521x293mm 23.5-inch                    | 1         | 0.74%   |
| Unknown (XXX) DTV XXX0030 1600x1200 708x398mm 32.0-inch               | 1         | 0.74%   |
| STA LCD Monitor STA0001 1366x768 256x144mm 11.6-inch                  | 1         | 0.74%   |
| Sony TV SNY1703 1360x768 1600x900mm 72.3-inch                         | 1         | 0.74%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC5544 1920x1080 344x194mm 15.5-inch | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4642 1366x768 309x174mm 14.0-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SAM0B32 1366x768 607x345mm 27.5-inch  | 1         | 0.74%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch              | 1         | 0.74%   |
| PANDA LC116LF1L02 NCP000F 1920x1080 256x144mm 11.6-inch               | 1         | 0.74%   |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                    | 1         | 0.74%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD0695 2560x1600 366x229mm 17.0-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD0508 1366x768 309x174mm 14.0-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD03AE 1366x768 345x194mm 15.6-inch           | 1         | 0.74%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 60        | 47.24%  |
| 1920x1080 (FHD)    | 40        | 31.5%   |
| 1280x800 (WXGA)    | 7         | 5.51%   |
| 1600x900 (HD+)     | 6         | 4.72%   |
| 3840x2160 (4K)     | 2         | 1.57%   |
| 1680x1050 (WSXGA+) | 2         | 1.57%   |
| 1280x1024 (SXGA)   | 2         | 1.57%   |
| 3840x1100          | 1         | 0.79%   |
| 3440x1440          | 1         | 0.79%   |
| 2560x1600          | 1         | 0.79%   |
| 1440x900 (WXGA+)   | 1         | 0.79%   |
| 1360x768           | 1         | 0.79%   |
| 1280x768           | 1         | 0.79%   |
| 1024x768 (XGA)     | 1         | 0.79%   |
| 1024x600           | 1         | 0.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 62        | 46.27%  |
| 13      | 20        | 14.93%  |
| 14      | 15        | 11.19%  |
| 11      | 10        | 7.46%   |
| 17      | 6         | 4.48%   |
| 22      | 3         | 2.24%   |
| 34      | 2         | 1.49%   |
| 24      | 2         | 1.49%   |
| 23      | 2         | 1.49%   |
| 21      | 2         | 1.49%   |
| 72      | 1         | 0.75%   |
| 40      | 1         | 0.75%   |
| 32      | 1         | 0.75%   |
| 31      | 1         | 0.75%   |
| 27      | 1         | 0.75%   |
| 20      | 1         | 0.75%   |
| 19      | 1         | 0.75%   |
| 12      | 1         | 0.75%   |
| 10      | 1         | 0.75%   |
| Unknown | 1         | 0.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 84        | 63.64%  |
| 201-300     | 21        | 15.91%  |
| 351-400     | 9         | 6.82%   |
| 401-500     | 6         | 4.55%   |
| 501-600     | 5         | 3.79%   |
| 701-800     | 3         | 2.27%   |
| 801-900     | 1         | 0.76%   |
| 601-700     | 1         | 0.76%   |
| 1501-2000   | 1         | 0.76%   |
| Unknown     | 1         | 0.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 103       | 85.83%  |
| 16/10   | 11        | 9.17%   |
| 5/4     | 2         | 1.67%   |
| 4/3     | 1         | 0.83%   |
| 3.40    | 1         | 0.83%   |
| 21/9    | 1         | 0.83%   |
| Unknown | 1         | 0.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 61        | 45.52%  |
| 81-90          | 29        | 21.64%  |
| 51-60          | 11        | 8.21%   |
| 201-250        | 9         | 6.72%   |
| 71-80          | 5         | 3.73%   |
| 121-130        | 5         | 3.73%   |
| 351-500        | 3         | 2.24%   |
| 151-200        | 2         | 1.49%   |
| 501-1000       | 2         | 1.49%   |
| More than 1000 | 1         | 0.75%   |
| 61-70          | 1         | 0.75%   |
| 41-50          | 1         | 0.75%   |
| 301-350        | 1         | 0.75%   |
| 141-150        | 1         | 0.75%   |
| 91-100         | 1         | 0.75%   |
| Unknown        | 1         | 0.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 58        | 44.62%  |
| 121-160       | 46        | 35.38%  |
| 51-100        | 18        | 13.85%  |
| 1-50          | 3         | 2.31%   |
| 161-240       | 3         | 2.31%   |
| More than 240 | 1         | 0.77%   |
| Unknown       | 1         | 0.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 99        | 82.5%   |
| 2     | 18        | 15%     |
| 0     | 2         | 1.67%   |
| 3     | 1         | 0.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 61        | 33.33%  |
| Realtek Semiconductor           | 58        | 31.69%  |
| Qualcomm Atheros                | 26        | 14.21%  |
| Broadcom                        | 17        | 9.29%   |
| Ralink Technology               | 5         | 2.73%   |
| Broadcom Limited                | 4         | 2.19%   |
| Qualcomm Atheros Communications | 2         | 1.09%   |
| Marvell Technology Group        | 2         | 1.09%   |
| Lenovo                          | 2         | 1.09%   |
| Dell                            | 2         | 1.09%   |
| Nvidia                          | 1         | 0.55%   |
| MediaTek                        | 1         | 0.55%   |
| JCM                             | 1         | 0.55%   |
| AMD                             | 1         | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 23        | 10.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 18        | 8.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 4.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 8         | 3.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 6         | 2.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 6         | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 6         | 2.7%    |
| Intel Wireless 7260                                                    | 6         | 2.7%    |
| Intel Wireless 3165                                                    | 5         | 2.25%   |
| Ralink MT7601U Wireless Adapter                                        | 4         | 1.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4         | 1.8%    |
| Intel Wireless 7265                                                    | 4         | 1.8%    |
| Intel Wi-Fi 6 AX200                                                    | 4         | 1.8%    |
| Intel 82577LM Gigabit Network Connection                               | 4         | 1.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 3         | 1.35%   |
| Intel Wireless 8265 / 8275                                             | 3         | 1.35%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 1.35%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 1.35%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.35%   |
| Intel Centrino Advanced-N 6235                                         | 3         | 1.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 3         | 1.35%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 3         | 1.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 0.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.9%    |
| Realtek RTL8723DE Wireless Network Adapter                             | 2         | 0.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2         | 0.9%    |
| Realtek RTL8188EE Wireless Network Adapter                             | 2         | 0.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 0.9%    |
| Realtek 802.11n WLAN Adapter                                           | 2         | 0.9%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.9%    |
| Qualcomm Atheros AR9271 802.11n                                        | 2         | 0.9%    |
| Lenovo Thinkpad LAN                                                    | 2         | 0.9%    |
| Intel Wireless 8260                                                    | 2         | 0.9%    |
| Intel Wi-Fi 6 AX201                                                    | 2         | 0.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 2         | 0.9%    |
| Intel Gemini Lake PCH CNVi WiFi                                        | 2         | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 0.9%    |
| Intel Centrino Wireless-N 2230                                         | 2         | 0.9%    |
| Intel Centrino Ultimate-N 6300                                         | 2         | 0.9%    |
| Intel Centrino Advanced-N 6200                                         | 2         | 0.9%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 58        | 45.67%  |
| Qualcomm Atheros                | 22        | 17.32%  |
| Realtek Semiconductor           | 21        | 16.54%  |
| Broadcom                        | 14        | 11.02%  |
| Ralink Technology               | 5         | 3.94%   |
| Qualcomm Atheros Communications | 2         | 1.57%   |
| Dell                            | 2         | 1.57%   |
| Broadcom Limited                | 2         | 1.57%   |
| MediaTek                        | 1         | 0.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 8         | 6.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 6         | 4.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 6         | 4.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 6         | 4.69%   |
| Intel Wireless 7260                                                                   | 6         | 4.69%   |
| Intel Wireless 3165                                                                   | 5         | 3.91%   |
| Ralink MT7601U Wireless Adapter                                                       | 4         | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 3.13%   |
| Intel Wireless 7265                                                                   | 4         | 3.13%   |
| Intel Wi-Fi 6 AX200                                                                   | 4         | 3.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 2.34%   |
| Intel Wireless 8265 / 8275                                                            | 3         | 2.34%   |
| Intel Centrino Advanced-N 6235                                                        | 3         | 2.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 3         | 2.34%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 3         | 2.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 2         | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.56%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 2         | 1.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 2         | 1.56%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 1.56%   |
| Realtek 802.11n WLAN Adapter                                                          | 2         | 1.56%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 2         | 1.56%   |
| Intel Wireless 8260                                                                   | 2         | 1.56%   |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 1.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 2         | 1.56%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 2         | 1.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 1.56%   |
| Intel Centrino Wireless-N 2230                                                        | 2         | 1.56%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 1.56%   |
| Intel Centrino Advanced-N 6200                                                        | 2         | 1.56%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 1.56%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 2         | 1.56%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.78%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 1         | 0.78%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 1         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 45        | 48.91%  |
| Intel                    | 28        | 30.43%  |
| Qualcomm Atheros         | 6         | 6.52%   |
| Broadcom                 | 6         | 6.52%   |
| Marvell Technology Group | 2         | 2.17%   |
| Lenovo                   | 2         | 2.17%   |
| Broadcom Limited         | 2         | 2.17%   |
| Nvidia                   | 1         | 1.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 23        | 25%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 18        | 19.57%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 9.78%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 4.35%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 3.26%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 3.26%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 3.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 2.17%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 2.17%   |
| Lenovo Thinkpad LAN                                                    | 2         | 2.17%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 2.17%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 1.09%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 1.09%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.09%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 1.09%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 1.09%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.09%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 1.09%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 1.09%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 1.09%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.09%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.09%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 1.09%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 1.09%   |
| Intel 82579V Gigabit Network Connection                                | 1         | 1.09%   |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                      | 1         | 1.09%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 1.09%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1         | 1.09%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.09%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express       | 1         | 1.09%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express            | 1         | 1.09%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 117       | 55.98%  |
| Ethernet | 90        | 43.06%  |
| Modem    | 2         | 0.96%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 98        | 80.33%  |
| Ethernet | 24        | 19.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 87        | 73.11%  |
| 1     | 28        | 23.53%  |
| 0     | 4         | 3.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 107       | 88.43%  |
| Yes  | 14        | 11.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 45.45%  |
| Qualcomm Atheros Communications | 13        | 14.77%  |
| IMC Networks                    | 9         | 10.23%  |
| Realtek Semiconductor           | 8         | 9.09%   |
| Dell                            | 6         | 6.82%   |
| Apple                           | 5         | 5.68%   |
| Broadcom                        | 4         | 4.55%   |
| Lite-On Technology              | 2         | 2.27%   |
| Hewlett-Packard                 | 1         | 1.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 21        | 23.86%  |
| Qualcomm Atheros  Bluetooth Device             | 8         | 9.09%   |
| IMC Networks Bluetooth Radio                   | 6         | 6.82%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 5         | 5.68%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 5         | 5.68%   |
| Realtek  Bluetooth 4.2 Adapter                 | 4         | 4.55%   |
| Intel AX200 Bluetooth                          | 4         | 4.55%   |
| Realtek Bluetooth Radio                        | 3         | 3.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 3         | 3.41%   |
| Intel AX201 Bluetooth                          | 3         | 3.41%   |
| Dell BCM20702A0 Bluetooth Module               | 3         | 3.41%   |
| Apple Bluetooth Host Controller                | 3         | 3.41%   |
| Intel Wireless-AC 3168 Bluetooth               | 2         | 2.27%   |
| Broadcom BCM43142 Bluetooth 4.0                | 2         | 2.27%   |
| Realtek RTL8723B Bluetooth                     | 1         | 1.14%   |
| Qualcomm Atheros Bluetooth USB Host Controller | 1         | 1.14%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 1.14%   |
| Lite-On Wireless_Device                        | 1         | 1.14%   |
| Lite-On Atheros AR3012 Bluetooth               | 1         | 1.14%   |
| IMC Networks Bluetooth Device                  | 1         | 1.14%   |
| IMC Networks Bluetooth                         | 1         | 1.14%   |
| IMC Networks BCM20702A0                        | 1         | 1.14%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 1.14%   |
| Dell Wireless 360 Bluetooth                    | 1         | 1.14%   |
| Dell Wireless 355 Bluetooth                    | 1         | 1.14%   |
| Dell Wireless 350 Bluetooth                    | 1         | 1.14%   |
| Broadcom HP Portable SoftSailing               | 1         | 1.14%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 1.14%   |
| Apple Bluetooth USB Host Controller            | 1         | 1.14%   |
| Apple Bluetooth HCI                            | 1         | 1.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 96        | 71.64%  |
| AMD                 | 22        | 16.42%  |
| Nvidia              | 11        | 8.21%   |
| Logitech            | 2         | 1.49%   |
| Texas Instruments   | 1         | 0.75%   |
| Sony                | 1         | 0.75%   |
| C-Media Electronics | 1         | 0.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 9.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 11        | 6.71%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 6.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 6.1%    |
| AMD FCH Azalia Controller                                                                         | 9         | 5.49%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 4.88%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 4.88%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 3.66%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 3.66%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 3.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 3.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 3.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 2.44%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.83%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.83%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.83%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.83%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.83%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.83%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.83%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 1.22%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.22%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.22%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.22%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.61%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1         | 0.61%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.61%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.61%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.61%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.61%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Logitech Logi USB Headset                                                                         | 1         | 0.61%   |
| Logitech H390 headset with microphone                                                             | 1         | 0.61%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 21        | 28.77%  |
| Samsung Electronics | 18        | 24.66%  |
| Micron Technology   | 10        | 13.7%   |
| Unknown (ABCD)      | 6         | 8.22%   |
| Kingston            | 4         | 5.48%   |
| Crucial             | 4         | 5.48%   |
| Unknown             | 2         | 2.74%   |
| Ramaxel Technology  | 2         | 2.74%   |
| Nanya Technology    | 2         | 2.74%   |
| A-DATA Technology   | 2         | 2.74%   |
| Sesame              | 1         | 1.37%   |
| Unknown             | 1         | 1.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 6         | 7.89%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 3.95%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s            | 3         | 3.95%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 2.63%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 2         | 2.63%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 2.63%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 2         | 2.63%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s              | 2         | 2.63%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s                | 2         | 2.63%   |
| A-DATA RAM AD73I1B1674EU 2GB SODIMM DDR3 1334MT/s                   | 2         | 2.63%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 1         | 1.32%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                         | 1         | 1.32%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                        | 1         | 1.32%   |
| SK hynix RAM Module 2GB SODIMM DDR2 667MT/s                         | 1         | 1.32%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s             | 1         | 1.32%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.32%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.32%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 1.32%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 1.32%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.32%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s        | 1         | 1.32%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 1.32%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 1         | 1.32%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 1         | 1.32%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 1.32%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 1         | 1.32%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s    | 1         | 1.32%   |
| Sesame RAM S939A2SGS-ITR 8GB SODIMM DDR3 2667MT/s                   | 1         | 1.32%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s          | 1         | 1.32%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                         | 1         | 1.32%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 1         | 1.32%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s               | 1         | 1.32%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s            | 1         | 1.32%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 1.32%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 1.32%   |
| Samsung RAM M471B5173BH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 1.32%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.32%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 1         | 1.32%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 1         | 1.32%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s              | 1         | 1.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 24        | 42.11%  |
| DDR4   | 18        | 31.58%  |
| LPDDR4 | 9         | 15.79%  |
| SDRAM  | 3         | 5.26%   |
| DDR2   | 2         | 3.51%   |
| LPDDR3 | 1         | 1.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 53        | 92.98%  |
| Row Of Chips | 3         | 5.26%   |
| DIMM         | 1         | 1.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 25        | 39.06%  |
| 8192  | 20        | 31.25%  |
| 2048  | 12        | 18.75%  |
| 16384 | 7         | 10.94%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 19        | 28.79%  |
| 2400  | 12        | 18.18%  |
| 2667  | 9         | 13.64%  |
| 1333  | 6         | 9.09%   |
| 3200  | 4         | 6.06%   |
| 2133  | 3         | 4.55%   |
| 1334  | 3         | 4.55%   |
| 4199  | 2         | 3.03%   |
| 3266  | 2         | 3.03%   |
| 4267  | 1         | 1.52%   |
| 2048  | 1         | 1.52%   |
| 1867  | 1         | 1.52%   |
| 1067  | 1         | 1.52%   |
| 975   | 1         | 1.52%   |
| 667   | 1         | 1.52%   |

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
| Chicony Electronics                    | 20        | 19.23%  |
| Microdia                               | 18        | 17.31%  |
| IMC Networks                           | 11        | 10.58%  |
| Sunplus Innovation Technology          | 10        | 9.62%   |
| Realtek Semiconductor                  | 8         | 7.69%   |
| Suyin                                  | 7         | 6.73%   |
| Apple                                  | 5         | 4.81%   |
| Syntek                                 | 4         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.85%   |
| Silicon Motion                         | 3         | 2.88%   |
| Ricoh                                  | 3         | 2.88%   |
| Quanta                                 | 2         | 1.92%   |
| Primax Electronics                     | 2         | 1.92%   |
| Sonix Technology                       | 1         | 0.96%   |
| OmniVision Technologies                | 1         | 0.96%   |
| MacroSilicon                           | 1         | 0.96%   |
| Logitech                               | 1         | 0.96%   |
| globaloptics                           | 1         | 0.96%   |
| Bison Electronics                      | 1         | 0.96%   |
| Alcor Micro                            | 1         | 0.96%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                   | 6         | 5.77%   |
| Microdia HP Integrated Webcam                                  | 6         | 5.77%   |
| Chicony Integrated Camera                                      | 5         | 4.81%   |
| IMC Networks Integrated Camera                                 | 4         | 3.85%   |
| Microdia Integrated_Webcam_HD                                  | 3         | 2.88%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 3         | 2.88%   |
| Chicony HP TrueVision HD                                       | 3         | 2.88%   |
| Syntek Lenovo EasyCamera                                       | 2         | 1.92%   |
| Microdia Sonix USB 2.0 Camera                                  | 2         | 1.92%   |
| Microdia Integrated Webcam                                     | 2         | 1.92%   |
| Microdia Dell Integrated HD Webcam                             | 2         | 1.92%   |
| IMC Networks HP TrueVision HD Camera                           | 2         | 1.92%   |
| Chicony USB2.0 HD UVC WebCam                                   | 2         | 1.92%   |
| Chicony Integrated HP HD Webcam                                | 2         | 1.92%   |
| Chicony HD User Facing                                         | 2         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 1.92%   |
| Apple FaceTime HD Camera                                       | 2         | 1.92%   |
| Syntek Integrated Camera                                       | 1         | 0.96%   |
| Syntek EasyCamera                                              | 1         | 0.96%   |
| Suyin VGA Webcam                                               | 1         | 0.96%   |
| Suyin TOSHIBA Web Camera - HD                                  | 1         | 0.96%   |
| Suyin Laptop_Integrated_Webcam_HD                              | 1         | 0.96%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 0.96%   |
| Suyin HP TrueVision HD                                         | 1         | 0.96%   |
| Suyin Acer/Lenovo Webcam [CN0316]                              | 1         | 0.96%   |
| Suyin 1.3M HD WebCam                                           | 1         | 0.96%   |
| Sunplus Laptop_Integrated_Webcam_HD                            | 1         | 0.96%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 0.96%   |
| Sunplus Integrated_Webcam_FHD                                  | 1         | 0.96%   |
| Sunplus HP Wide Vision HD                                      | 1         | 0.96%   |
| Sonix HP Webcam-101                                            | 1         | 0.96%   |
| Silicon Motion WebCam SCB-0385N                                | 1         | 0.96%   |
| Silicon Motion WebCam SC-10HDD13335N                           | 1         | 0.96%   |
| Silicon Motion Real HD WebCam                                  | 1         | 0.96%   |
| Ricoh Laptop_Integrated_Webcam_FHD                             | 1         | 0.96%   |
| Ricoh Integrated Webcam                                        | 1         | 0.96%   |
| Ricoh HD Webcam                                                | 1         | 0.96%   |
| Realtek USB Camera                                             | 1         | 0.96%   |
| Realtek LG Camera                                              | 1         | 0.96%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 0.96%   |

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
| 0     | 84        | 69.42%  |
| 1     | 29        | 23.97%  |
| 2     | 8         | 6.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 15        | 33.33%  |
| Chipcard              | 10        | 22.22%  |
| Graphics card         | 8         | 17.78%  |
| Multimedia controller | 4         | 8.89%   |
| Net/wireless          | 3         | 6.67%   |
| Storage               | 2         | 4.44%   |
| Card reader           | 1         | 2.22%   |
| Camera                | 1         | 2.22%   |
| Bluetooth             | 1         | 2.22%   |

