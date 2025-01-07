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

Total: 230

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f84abc56e9](https://linux-hardware.org/?probe=f84abc56e9) | Nov 08, 2024 |
| Lenovo        | Unknown                     | [18084edb88](https://linux-hardware.org/?probe=18084edb88) | Nov 06, 2024 |
| Intel         | TU45C                       | [f7640d1ac4](https://linux-hardware.org/?probe=f7640d1ac4) | Oct 31, 2024 |
| Lenovo        | Unknown                     | [0fdc4e7dac](https://linux-hardware.org/?probe=0fdc4e7dac) | Oct 31, 2024 |
| Apple         | MacBookAir7,2               | [c57cc10b49](https://linux-hardware.org/?probe=c57cc10b49) | Oct 11, 2024 |
| Dell          | Inspiron 3520               | [f5cdd77427](https://linux-hardware.org/?probe=f5cdd77427) | Sep 17, 2024 |
| Dell          | Latitude E6420              | [a37423865a](https://linux-hardware.org/?probe=a37423865a) | Sep 15, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2d1f00b430](https://linux-hardware.org/?probe=2d1f00b430) | Sep 14, 2024 |
| HP            | Laptop 15-ef0xxx            | [0886f6bb06](https://linux-hardware.org/?probe=0886f6bb06) | Sep 11, 2024 |
| Chuwi         | HeroBook Air                | [09a139dbbe](https://linux-hardware.org/?probe=09a139dbbe) | Sep 04, 2024 |
| Chuwi         | HeroBook Air                | [163bdd4e80](https://linux-hardware.org/?probe=163bdd4e80) | Sep 04, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [d738fd6aec](https://linux-hardware.org/?probe=d738fd6aec) | Sep 03, 2024 |
| HP            | Compaq Presario CQ60        | [4a61316ba0](https://linux-hardware.org/?probe=4a61316ba0) | Aug 25, 2024 |
| Acer          | Aspire E5-576               | [50e12f89a7](https://linux-hardware.org/?probe=50e12f89a7) | Aug 15, 2024 |
| Lenovo        | ThinkPad T490 20N3S64200    | [14ae99c097](https://linux-hardware.org/?probe=14ae99c097) | Aug 14, 2024 |
| GPU Compan... | GWTC51427                   | [55c2e1921f](https://linux-hardware.org/?probe=55c2e1921f) | Aug 08, 2024 |
| Dell          | System XPS L321X            | [c8e8aa60ed](https://linux-hardware.org/?probe=c8e8aa60ed) | Jul 31, 2024 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [49142dd027](https://linux-hardware.org/?probe=49142dd027) | Jul 27, 2024 |
| Dell          | Latitude 3330               | [bee203920a](https://linux-hardware.org/?probe=bee203920a) | Jul 27, 2024 |
| Dell          | Inspiron 3135               | [36c80b438d](https://linux-hardware.org/?probe=36c80b438d) | Jul 22, 2024 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [4e94f5fb5f](https://linux-hardware.org/?probe=4e94f5fb5f) | Jul 20, 2024 |
| Dell          | Latitude E6430              | [ec7d5a0740](https://linux-hardware.org/?probe=ec7d5a0740) | Jul 14, 2024 |
| Unknown       | Unknown                     | [1b0d823c81](https://linux-hardware.org/?probe=1b0d823c81) | Jul 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5d75a25d73](https://linux-hardware.org/?probe=5d75a25d73) | Jun 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [efce3d02b0](https://linux-hardware.org/?probe=efce3d02b0) | Jun 30, 2024 |
| ASUSTek       | G75VW                       | [7b448890f8](https://linux-hardware.org/?probe=7b448890f8) | Jun 22, 2024 |
| Acer          | Aspire A515-45              | [f21d4210a9](https://linux-hardware.org/?probe=f21d4210a9) | Jun 14, 2024 |
| Dell          | Latitude E6430              | [042ef58af8](https://linux-hardware.org/?probe=042ef58af8) | May 30, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [594a2b53a8](https://linux-hardware.org/?probe=594a2b53a8) | May 25, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [194d8ef52c](https://linux-hardware.org/?probe=194d8ef52c) | May 25, 2024 |
| Apple         | MacBookPro11,1              | [74efedec18](https://linux-hardware.org/?probe=74efedec18) | May 15, 2024 |
| Dell          | Inspiron 5535               | [9d93f7fd83](https://linux-hardware.org/?probe=9d93f7fd83) | May 12, 2024 |
| Dell          | Inspiron 5535               | [d23167b52c](https://linux-hardware.org/?probe=d23167b52c) | May 09, 2024 |
| ASUSTek       | X550CA                      | [5038e329fc](https://linux-hardware.org/?probe=5038e329fc) | May 06, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [5078c26f9c](https://linux-hardware.org/?probe=5078c26f9c) | Apr 24, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [f9582b6020](https://linux-hardware.org/?probe=f9582b6020) | Apr 24, 2024 |
| Apple         | MacBookPro8,1               | [60291310ee](https://linux-hardware.org/?probe=60291310ee) | Apr 22, 2024 |
| TODOS INDU... | Aprix_2022_V1               | [97ae5afa87](https://linux-hardware.org/?probe=97ae5afa87) | Apr 05, 2024 |
| Apple         | MacBookAir7,2               | [fd278af3a5](https://linux-hardware.org/?probe=fd278af3a5) | Mar 31, 2024 |
| TODOS INDU... | Aprix_2022_V1               | [e5e980e4f5](https://linux-hardware.org/?probe=e5e980e4f5) | Mar 30, 2024 |
| Acer          | Aspire 4752                 | [bb522b4ec1](https://linux-hardware.org/?probe=bb522b4ec1) | Mar 26, 2024 |
| Apple         | MacBookAir7,2               | [17be6d540f](https://linux-hardware.org/?probe=17be6d540f) | Feb 16, 2024 |
| ASUSTek       | X540YA                      | [8ab328c73b](https://linux-hardware.org/?probe=8ab328c73b) | Feb 15, 2024 |
| Google        | Lulu                        | [c081ea57a2](https://linux-hardware.org/?probe=c081ea57a2) | Feb 11, 2024 |
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
| Ubuntu 20.04        | 17        | 10.83%  |
| Ubuntu 22.04        | 9         | 5.73%   |
| Ubuntu 18.04        | 7         | 4.46%   |
| Arch Rolling        | 7         | 4.46%   |
| Fedora 40           | 6         | 3.82%   |
| Fedora 38           | 5         | 3.18%   |
| OpenMandriva 4.3    | 4         | 2.55%   |
| Manjaro             | 4         | 2.55%   |
| Fedora 36           | 4         | 2.55%   |
| Zorin 16            | 3         | 1.91%   |
| Ubuntu 24.04        | 3         | 1.91%   |
| Fedora 39           | 3         | 1.91%   |
| Fedora 37           | 3         | 1.91%   |
| Debian 12           | 3         | 1.91%   |
| Debian 11           | 3         | 1.91%   |
| Ubuntu 21.10        | 2         | 1.27%   |
| Pop!_OS 20.10       | 2         | 1.27%   |
| OpenMandriva 4.2    | 2         | 1.27%   |
| OpenMandriva 23.08  | 2         | 1.27%   |
| Linux Mint 20.3     | 2         | 1.27%   |
| Linux Mint 20.1     | 2         | 1.27%   |
| KDE neon 22.04      | 2         | 1.27%   |
| Kali 2023.4         | 2         | 1.27%   |
| Kali 2023.3         | 2         | 1.27%   |
| ArcoLinux Rolling   | 2         | 1.27%   |
| Zorin 17            | 1         | 0.64%   |
| Xubuntu 19.10       | 1         | 0.64%   |
| Xubuntu 18.04       | 1         | 0.64%   |
| Void Linux Rolling  | 1         | 0.64%   |
| Ubuntu MATE 22.04   | 1         | 0.64%   |
| Ubuntu Budgie 22.04 | 1         | 0.64%   |
| Ubuntu Budgie 21.10 | 1         | 0.64%   |
| Ubuntu Budgie 20.04 | 1         | 0.64%   |
| Ubuntu 23.04        | 1         | 0.64%   |
| Ubuntu 22.10        | 1         | 0.64%   |
| Ubuntu 21.04        | 1         | 0.64%   |
| Ubuntu 19.04        | 1         | 0.64%   |
| Solus 4.1           | 1         | 0.64%   |
| Pop!_OS 22.04       | 1         | 0.64%   |
| Pop!_OS 21.04       | 1         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 40        | 26.32%  |
| Fedora        | 23        | 15.13%  |
| OpenMandriva  | 11        | 7.24%   |
| Linux Mint    | 10        | 6.58%   |
| Manjaro       | 8         | 5.26%   |
| Debian        | 8         | 5.26%   |
| Arch          | 8         | 5.26%   |
| Kali          | 7         | 4.61%   |
| Pop!_OS       | 5         | 3.29%   |
| Zorin         | 4         | 2.63%   |
| Ubuntu Budgie | 3         | 1.97%   |
| Lubuntu       | 3         | 1.97%   |
| KDE neon      | 3         | 1.97%   |
| Xubuntu       | 2         | 1.32%   |
| LMDE          | 2         | 1.32%   |
| Kubuntu       | 2         | 1.32%   |
| Clear Linux   | 2         | 1.32%   |
| ArcoLinux     | 2         | 1.32%   |
| Void Linux    | 1         | 0.66%   |
| Ubuntu MATE   | 1         | 0.66%   |
| Solus         | 1         | 0.66%   |
| MX            | 1         | 0.66%   |
| Gabian        | 1         | 0.66%   |
| Endless       | 1         | 0.66%   |
| Elementary    | 1         | 0.66%   |
| blendOS       | 1         | 0.66%   |
| Archcraft     | 1         | 0.66%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 5.4.0-48-generic                    | 4         | 2.33%   |
| 5.16.7-desktop-1omv4003             | 4         | 2.33%   |
| 5.4.0-42-generic                    | 3         | 1.74%   |
| 5.13.0-22-generic                   | 3         | 1.74%   |
| 6.8.0-41-generic                    | 2         | 1.16%   |
| 6.6.15-amd64                        | 2         | 1.16%   |
| 6.5.0-kali3-amd64                   | 2         | 1.16%   |
| 6.4.8-desktop-2omv2390              | 2         | 1.16%   |
| 6.1.0-21-amd64                      | 2         | 1.16%   |
| 5.4.0-77-generic                    | 2         | 1.16%   |
| 5.4.0-52-generic                    | 2         | 1.16%   |
| 5.4.0-33-generic                    | 2         | 1.16%   |
| 5.3.0-51-generic                    | 2         | 1.16%   |
| 5.19.0-46-generic                   | 2         | 1.16%   |
| 5.15.0-76-generic                   | 2         | 1.16%   |
| 5.15.0-58-generic                   | 2         | 1.16%   |
| 5.15.0-53-generic                   | 2         | 1.16%   |
| 5.15.0-41-generic                   | 2         | 1.16%   |
| 6.9.9-amd64                         | 1         | 0.58%   |
| 6.9.7-desktop-1omv2490              | 1         | 0.58%   |
| 6.9.4-200.fc40.x86_64               | 1         | 0.58%   |
| 6.9.10-200.fc40.x86_64              | 1         | 0.58%   |
| 6.8.7-300.fc40.x86_64               | 1         | 0.58%   |
| 6.8.5-301.fc40.x86_64               | 1         | 0.58%   |
| 6.8.11-300.fc40.x86_64              | 1         | 0.58%   |
| 6.8.0-76060800daily20240311-generic | 1         | 0.58%   |
| 6.8.0-40-generic                    | 1         | 0.58%   |
| 6.8.0-39-generic                    | 1         | 0.58%   |
| 6.6.9-200.fc39.x86_64               | 1         | 0.58%   |
| 6.6.8-200.fc39.x86_64               | 1         | 0.58%   |
| 6.6.8-2-MANJARO                     | 1         | 0.58%   |
| 6.6.6-200.fc39.x86_64               | 1         | 0.58%   |
| 6.6.26-1-MANJARO                    | 1         | 0.58%   |
| 6.6.2-desktop-1omv2390              | 1         | 0.58%   |
| 6.6.10-76060610-generic             | 1         | 0.58%   |
| 6.6.1-arch1-1                       | 1         | 0.58%   |
| 6.5.8-200.fc38.x86_64               | 1         | 0.58%   |
| 6.5.7-200.fc38.x86_64               | 1         | 0.58%   |
| 6.5.6-300.fc39.x86_64               | 1         | 0.58%   |
| 6.5.6-200.fc38.x86_64               | 1         | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 12.88%  |
| 5.15.0  | 14        | 8.59%   |
| 5.13.0  | 9         | 5.52%   |
| 6.5.0   | 6         | 3.68%   |
| 5.3.0   | 6         | 3.68%   |
| 5.11.0  | 6         | 3.68%   |
| 6.8.0   | 5         | 3.07%   |
| 5.19.0  | 5         | 3.07%   |
| 5.16.7  | 4         | 2.45%   |
| 5.10.0  | 4         | 2.45%   |
| 6.1.0   | 3         | 1.84%   |
| 5.0.0   | 3         | 1.84%   |
| 6.6.8   | 2         | 1.23%   |
| 6.6.15  | 2         | 1.23%   |
| 6.5.6   | 2         | 1.23%   |
| 6.4.8   | 2         | 1.23%   |
| 4.19.0  | 2         | 1.23%   |
| 6.9.9   | 1         | 0.61%   |
| 6.9.7   | 1         | 0.61%   |
| 6.9.4   | 1         | 0.61%   |
| 6.9.10  | 1         | 0.61%   |
| 6.8.7   | 1         | 0.61%   |
| 6.8.5   | 1         | 0.61%   |
| 6.8.11  | 1         | 0.61%   |
| 6.6.9   | 1         | 0.61%   |
| 6.6.6   | 1         | 0.61%   |
| 6.6.26  | 1         | 0.61%   |
| 6.6.2   | 1         | 0.61%   |
| 6.6.10  | 1         | 0.61%   |
| 6.6.1   | 1         | 0.61%   |
| 6.5.8   | 1         | 0.61%   |
| 6.5.7   | 1         | 0.61%   |
| 6.5.5   | 1         | 0.61%   |
| 6.4.6   | 1         | 0.61%   |
| 6.4.14  | 1         | 0.61%   |
| 6.3.7   | 1         | 0.61%   |
| 6.3.0   | 1         | 0.61%   |
| 6.2.7   | 1         | 0.61%   |
| 6.2.14  | 1         | 0.61%   |
| 6.2.12  | 1         | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 23        | 14.29%  |
| 5.15    | 16        | 9.94%   |
| 6.5     | 11        | 6.83%   |
| 5.13    | 10        | 6.21%   |
| 6.6     | 9         | 5.59%   |
| 6.8     | 8         | 4.97%   |
| 5.19    | 8         | 4.97%   |
| 5.11    | 8         | 4.97%   |
| 5.10    | 7         | 4.35%   |
| 5.3     | 6         | 3.73%   |
| 6.1     | 5         | 3.11%   |
| 6.9     | 4         | 2.48%   |
| 6.4     | 4         | 2.48%   |
| 6.2     | 4         | 2.48%   |
| 6.10    | 4         | 2.48%   |
| 5.8     | 4         | 2.48%   |
| 5.16    | 4         | 2.48%   |
| 5.0     | 4         | 2.48%   |
| 6.11    | 3         | 1.86%   |
| 5.9     | 3         | 1.86%   |
| 4.19    | 3         | 1.86%   |
| 6.3     | 2         | 1.24%   |
| 6.0     | 2         | 1.24%   |
| 5.18    | 2         | 1.24%   |
| 5.12    | 2         | 1.24%   |
| 5.7     | 1         | 0.62%   |
| 5.6     | 1         | 0.62%   |
| 5.17    | 1         | 0.62%   |
| 4.18    | 1         | 0.62%   |
| 4.15    | 1         | 0.62%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 146       | 97.99%  |
| i686   | 3         | 2.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 69        | 44.23%  |
| KDE5          | 29        | 18.59%  |
| XFCE          | 15        | 9.62%   |
| X-Cinnamon    | 10        | 6.41%   |
| Unknown       | 10        | 6.41%   |
| KDE6          | 5         | 3.21%   |
| Budgie        | 4         | 2.56%   |
| LXQt          | 3         | 1.92%   |
| KDE           | 3         | 1.92%   |
| MATE          | 2         | 1.28%   |
| sway          | 1         | 0.64%   |
| qtile         | 1         | 0.64%   |
| LXDE          | 1         | 0.64%   |
| Hyprland      | 1         | 0.64%   |
| GNOME Classic | 1         | 0.64%   |
| DWM           | 1         | 0.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 99        | 64.71%  |
| Wayland | 48        | 31.37%  |
| Unknown | 5         | 3.27%   |
| Tty     | 1         | 0.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 75        | 49.02%  |
| SDDM    | 23        | 15.03%  |
| LightDM | 18        | 11.76%  |
| GDM3    | 17        | 11.11%  |
| GDM     | 16        | 10.46%  |
| TDM     | 4         | 2.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 82        | 52.9%   |
| es_DO   | 38        | 24.52%  |
| C       | 7         | 4.52%   |
| Unknown | 7         | 4.52%   |
| es_MX   | 6         | 3.87%   |
| es_ES   | 6         | 3.87%   |
| es_US   | 4         | 2.58%   |
| en_CA   | 2         | 1.29%   |
| ru_RU   | 1         | 0.65%   |
| fr_HT   | 1         | 0.65%   |
| fr_FR   | 1         | 0.65%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 80        | 52.29%  |
| EFI  | 73        | 47.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 105       | 68.63%  |
| Btrfs   | 24        | 15.69%  |
| Overlay | 12        | 7.84%   |
| Tmpfs   | 7         | 4.58%   |
| Xfs     | 2         | 1.31%   |
| Zfs     | 1         | 0.65%   |
| F2fs    | 1         | 0.65%   |
| Unknown | 1         | 0.65%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 76        | 50%     |
| GPT     | 64        | 42.11%  |
| MBR     | 12        | 7.89%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 129       | 86%     |
| Yes       | 21        | 14%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 112       | 74.67%  |
| Yes       | 38        | 25.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 42        | 28.19%  |
| Hewlett-Packard     | 25        | 16.78%  |
| Lenovo              | 23        | 15.44%  |
| ASUSTek Computer    | 13        | 8.72%   |
| Apple               | 10        | 6.71%   |
| Acer                | 8         | 5.37%   |
| Unknown             | 5         | 3.36%   |
| Google              | 3         | 2.01%   |
| VTEX                | 2         | 1.34%   |
| TODOS INDUSTRIAL    | 2         | 1.34%   |
| Samsung Electronics | 2         | 1.34%   |
| MSI                 | 2         | 1.34%   |
| EVOO                | 2         | 1.34%   |
| Toshiba             | 1         | 0.67%   |
| SAELITE             | 1         | 0.67%   |
| Nuvision            | 1         | 0.67%   |
| LG Electronics      | 1         | 0.67%   |
| Intel               | 1         | 0.67%   |
| GPU Company         | 1         | 0.67%   |
| Fujitsu             | 1         | 0.67%   |
| Eluktronics         | 1         | 0.67%   |
| ECS                 | 1         | 0.67%   |
| Chuwi               | 1         | 0.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 6         | 4.03%   |
| Dell Latitude E6430                               | 3         | 2.01%   |
| Dell Latitude E6420                               | 3         | 2.01%   |
| Apple MacBookPro8,1                               | 3         | 2.01%   |
| Apple MacBookAir7,2                               | 3         | 2.01%   |
| VTEX NOTEBOOK                                     | 2         | 1.34%   |
| Lenovo IdeaPad 330S-15IKB 81F5                    | 2         | 1.34%   |
| HP Pavilion Notebook                              | 2         | 1.34%   |
| HP Pavilion Gaming Laptop 15-dk0xxx               | 2         | 1.34%   |
| HP Laptop 15-dy1xxx                               | 2         | 1.34%   |
| HP EliteBook 8460p                                | 2         | 1.34%   |
| EVOO EV-C-116-7                                   | 2         | 1.34%   |
| Dell Latitude E6540                               | 2         | 1.34%   |
| Dell Latitude E6410                               | 2         | 1.34%   |
| Dell Latitude 5590                                | 2         | 1.34%   |
| Dell Latitude 3330                                | 2         | 1.34%   |
| Dell Inspiron 5570                                | 2         | 1.34%   |
| Dell Inspiron 5555                                | 2         | 1.34%   |
| Toshiba Satellite C55-A                           | 1         | 0.67%   |
| TODOS INDUSTRIAL Easytouch_2022_V1                | 1         | 0.67%   |
| TODOS INDUSTRIAL Aprix_2022_V1                    | 1         | 0.67%   |
| Samsung RV420/RV520/RV720/E3530/S3530/E3420/E3520 | 1         | 0.67%   |
| Samsung 905S3G/906S3G/915S3G/9305SG               | 1         | 0.67%   |
| SAELITE ES1AU11                                   | 1         | 0.67%   |
| Nuvision NES11                                    | 1         | 0.67%   |
| MSI GE62 6QC                                      | 1         | 0.67%   |
| MSI CR70 2M/CX70 2OC/CX70 2OD                     | 1         | 0.67%   |
| LG 17ZT90P-G.AX33U1                               | 1         | 0.67%   |
| Lenovo Z50-75 80EC                                | 1         | 0.67%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES1M500          | 1         | 0.67%   |
| Lenovo ThinkPad W540 20BHS0GB06                   | 1         | 0.67%   |
| Lenovo ThinkPad T490 20N3S7BC02                   | 1         | 0.67%   |
| Lenovo ThinkPad T490 20N3S64200                   | 1         | 0.67%   |
| Lenovo ThinkPad T480s 20L7CTO1WW                  | 1         | 0.67%   |
| Lenovo ThinkPad T470 20HD004AUS                   | 1         | 0.67%   |
| Lenovo ThinkPad T420s 41732BU                     | 1         | 0.67%   |
| Lenovo ThinkPad T410 2537N99                      | 1         | 0.67%   |
| Lenovo ThinkPad P43s 20RH0013US                   | 1         | 0.67%   |
| Lenovo ThinkPad E470 20H1006DUS                   | 1         | 0.67%   |
| Lenovo ThinkBook 14s-IWL 20RM                     | 1         | 0.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 24        | 16.11%  |
| Dell Inspiron              | 14        | 9.4%    |
| Lenovo ThinkPad            | 10        | 6.71%   |
| Lenovo IdeaPad             | 7         | 4.7%    |
| Acer Aspire                | 7         | 4.7%    |
| HP Pavilion                | 6         | 4.03%   |
| Unknown                    | 6         | 4.03%   |
| HP Laptop                  | 5         | 3.36%   |
| ASUS VivoBook              | 4         | 2.68%   |
| HP ProBook                 | 3         | 2.01%   |
| HP EliteBook               | 3         | 2.01%   |
| Apple MacBookPro8          | 3         | 2.01%   |
| Apple MacBookAir7          | 3         | 2.01%   |
| VTEX NOTEBOOK              | 2         | 1.34%   |
| EVOO EV-C-116-7            | 2         | 1.34%   |
| Dell Vostro                | 2         | 1.34%   |
| Toshiba Satellite          | 1         | 0.67%   |
| TODOS INDUSTRIAL Easytouch | 1         | 0.67%   |
| TODOS INDUSTRIAL Aprix     | 1         | 0.67%   |
| Samsung RV420              | 1         | 0.67%   |
| Samsung 905S3G             | 1         | 0.67%   |
| SAELITE ES1AU11            | 1         | 0.67%   |
| Nuvision NES11             | 1         | 0.67%   |
| MSI GE62                   | 1         | 0.67%   |
| MSI CR70                   | 1         | 0.67%   |
| LG 17ZT90P-G.AX33U1        | 1         | 0.67%   |
| Lenovo Z50-75              | 1         | 0.67%   |
| Lenovo ThinkBook           | 1         | 0.67%   |
| Lenovo Legion              | 1         | 0.67%   |
| Lenovo G505s               | 1         | 0.67%   |
| Lenovo G40-70              | 1         | 0.67%   |
| Intel TU45C                | 1         | 0.67%   |
| HP Stream                  | 1         | 0.67%   |
| HP OMEN                    | 1         | 0.67%   |
| HP Notebook                | 1         | 0.67%   |
| HP G60                     | 1         | 0.67%   |
| HP ENVY                    | 1         | 0.67%   |
| HP Compaq                  | 1         | 0.67%   |
| HP 255                     | 1         | 0.67%   |
| HP 250                     | 1         | 0.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 17        | 11.41%  |
| 2019 | 15        | 10.07%  |
| 2013 | 15        | 10.07%  |
| 2011 | 14        | 9.4%    |
| 2014 | 12        | 8.05%   |
| 2012 | 12        | 8.05%   |
| 2017 | 11        | 7.38%   |
| 2020 | 8         | 5.37%   |
| 2016 | 8         | 5.37%   |
| 2018 | 7         | 4.7%    |
| 2007 | 6         | 4.03%   |
| 2010 | 5         | 3.36%   |
| 2008 | 5         | 3.36%   |
| 2015 | 4         | 2.68%   |
| 2022 | 3         | 2.01%   |
| 2009 | 3         | 2.01%   |
| 2023 | 2         | 1.34%   |
| 2006 | 1         | 0.67%   |
| 2005 | 1         | 0.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 149       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 143       | 95.97%  |
| Enabled  | 6         | 4.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 146       | 97.99%  |
| Yes  | 3         | 2.01%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 48        | 32%     |
| 4.01-8.0   | 45        | 30%     |
| 8.01-16.0  | 26        | 17.33%  |
| 16.01-24.0 | 17        | 11.33%  |
| 2.01-3.0   | 5         | 3.33%   |
| 1.01-2.0   | 4         | 2.67%   |
| 32.01-64.0 | 3         | 2%      |
| 24.01-32.0 | 2         | 1.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 54        | 31.95%  |
| 2.01-3.0  | 50        | 29.59%  |
| 3.01-4.0  | 35        | 20.71%  |
| 4.01-8.0  | 22        | 13.02%  |
| 0.51-1.0  | 6         | 3.55%   |
| 8.01-16.0 | 2         | 1.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 113       | 74.83%  |
| 2      | 37        | 24.5%   |
| 3      | 1         | 0.66%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 93        | 62%     |
| Yes       | 57        | 38%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 108       | 72%     |
| No        | 42        | 28%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 147       | 98.66%  |
| No        | 2         | 1.34%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 74.67%  |
| No        | 38        | 25.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Dominican Republic | 149       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Santo Domingo Este         | 77        | 48.73%  |
| Santo Domingo              | 26        | 16.46%  |
| Santiago de los Caballeros | 15        | 9.49%   |
| La Romana                  | 6         | 3.8%    |
| Concepción de la Vega     | 6         | 3.8%    |
| Santo Domingo Oeste        | 3         | 1.9%    |
| Cabarete                   | 3         | 1.9%    |
| Santa Cruz de Barahona     | 2         | 1.27%   |
| Nagua                      | 2         | 1.27%   |
| Constanza                  | 2         | 1.27%   |
| Alejandro Bass             | 2         | 1.27%   |
| Sosua, Cabarete            | 1         | 0.63%   |
| San Pedro de Macorís      | 1         | 0.63%   |
| San Juan                   | 1         | 0.63%   |
| San Isidro                 | 1         | 0.63%   |
| San Cristobal              | 1         | 0.63%   |
| Punta Cana                 | 1         | 0.63%   |
| Puerto Plata               | 1         | 0.63%   |
| Monte Llano                | 1         | 0.63%   |
| Los Hidalgos               | 1         | 0.63%   |
| Guaymate                   | 1         | 0.63%   |
| Cancino                    | 1         | 0.63%   |
| Boca Chica                 | 1         | 0.63%   |
| Baní                      | 1         | 0.63%   |
| Bajos de Haina             | 1         | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 27        | 35     | 14.92%  |
| Samsung Electronics         | 20        | 22     | 11.05%  |
| Toshiba                     | 16        | 20     | 8.84%   |
| SanDisk                     | 14        | 18     | 7.73%   |
| WDC                         | 13        | 16     | 7.18%   |
| Hitachi                     | 11        | 13     | 6.08%   |
| Unknown                     | 9         | 10     | 4.97%   |
| Kingston                    | 9         | 9      | 4.97%   |
| SK hynix                    | 7         | 9      | 3.87%   |
| Apple                       | 6         | 12     | 3.31%   |
| China                       | 5         | 6      | 2.76%   |
| AirDisk                     | 4         | 4      | 2.21%   |
| Intel                       | 3         | 5      | 1.66%   |
| FORESEE                     | 3         | 4      | 1.66%   |
| Unknown                     | 3         | 3      | 1.66%   |
| Transcend                   | 2         | 2      | 1.1%    |
| SPCC                        | 2         | 2      | 1.1%    |
| Micron/Crucial Technology   | 2         | 2      | 1.1%    |
| Micron Technology           | 2         | 2      | 1.1%    |
| KIOXIA                      | 2         | 3      | 1.1%    |
| Indilinx                    | 2         | 2      | 1.1%    |
| HGST                        | 2         | 2      | 1.1%    |
| Crucial                     | 2         | 3      | 1.1%    |
| A-DATA Technology           | 2         | 2      | 1.1%    |
| Wibtek                      | 1         | 1      | 0.55%   |
| UMIS                        | 1         | 1      | 0.55%   |
| Supersonic                  | 1         | 1      | 0.55%   |
| SABRENT                     | 1         | 1      | 0.55%   |
| PNY                         | 1         | 1      | 0.55%   |
| OCZ                         | 1         | 1      | 0.55%   |
| Netac                       | 1         | 1      | 0.55%   |
| MSI                         | 1         | 1      | 0.55%   |
| MaiChai                     | 1         | 1      | 0.55%   |
| LITEONIT                    | 1         | 2      | 0.55%   |
| Kingston Technology Company | 1         | 1      | 0.55%   |
| Hewlett-Packard             | 1         | 1      | 0.55%   |
| Eluktro                     | 1         | 1      | 0.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 4         | 2.14%   |
| AirDisk 128GB SSD                                   | 4         | 2.14%   |
| Unknown MMC Card  16GB                              | 3         | 1.6%    |
| Toshiba MQ04ABF100 1TB                              | 3         | 1.6%    |
| Seagate ST500LT012-1DG142 500GB                     | 3         | 1.6%    |
| Seagate ST500LM021-1KJ152 500GB                     | 3         | 1.6%    |
| Seagate ST500LM000-1EJ162 500GB                     | 3         | 1.6%    |
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 1.6%    |
| FORESEE 128GB SSD                                   | 3         | 1.6%    |
| Unknown                                             | 3         | 1.6%    |
| Unknown MMC Card  128GB                             | 2         | 1.07%   |
| Toshiba MQ01ACF050 500GB                            | 2         | 1.07%   |
| Toshiba MK3275GSX 320GB                             | 2         | 1.07%   |
| Seagate ST9250315AS 250GB                           | 2         | 1.07%   |
| Seagate ST1000LM049-2GH172 1TB                      | 2         | 1.07%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 2         | 1.07%   |
| SanDisk NVMe SSD Drive 256GB                        | 2         | 1.07%   |
| Samsung SSD 860 EVO 500GB                           | 2         | 1.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 2         | 1.07%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 1.07%   |
| Kingston SA400S37120G 120GB SSD                     | 2         | 1.07%   |
| Kingston OM8PCP3512F-AB 512GB                       | 2         | 1.07%   |
| Intel HBRPEKNX0101AHO 16GB                          | 2         | 1.07%   |
| Intel HBRPEKNX0101AH 256GB                          | 2         | 1.07%   |
| Indilinx IND-S3N80P/128G 128GB                      | 2         | 1.07%   |
| Hitachi HTS725032A9A360 320GB                       | 2         | 1.07%   |
| HGST HTS725050A7E630 500GB                          | 2         | 1.07%   |
| Crucial CT250MX200SSD3 250GB                        | 2         | 1.07%   |
| China 128GB SSD                                     | 2         | 1.07%   |
| Apple SSD SM0256G 256GB                             | 2         | 1.07%   |
| Wibtek W800S 512GB SSD                              | 1         | 0.53%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                      | 1         | 0.53%   |
| WDC WD5000LPLX-08ZNTT0 500GB                        | 1         | 0.53%   |
| WDC WD3200LPVX-75V0TT0 320GB                        | 1         | 0.53%   |
| WDC WD3200BEVT-75A23T0 320GB                        | 1         | 0.53%   |
| WDC WD2500BEVT-75A23T0 250GB                        | 1         | 0.53%   |
| WDC WD2500BEVS-22UST0 250GB                         | 1         | 0.53%   |
| WDC WD2500BEKT-60A25T1 250GB                        | 1         | 0.53%   |
| WDC WD1600BEVT-75ZCT1 160GB                         | 1         | 0.53%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 1         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 33     | 38.81%  |
| Toshiba             | 15        | 19     | 22.39%  |
| Hitachi             | 11        | 13     | 16.42%  |
| WDC                 | 10        | 13     | 14.93%  |
| HGST                | 2         | 2      | 2.99%   |
| Samsung Electronics | 1         | 1      | 1.49%   |
| SABRENT             | 1         | 1      | 1.49%   |
| Apple               | 1         | 1      | 1.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 14     | 19.4%   |
| SanDisk             | 8         | 11     | 11.94%  |
| Kingston            | 7         | 7      | 10.45%  |
| China               | 5         | 6      | 7.46%   |
| Apple               | 4         | 5      | 5.97%   |
| AirDisk             | 4         | 4      | 5.97%   |
| FORESEE             | 3         | 4      | 4.48%   |
| Transcend           | 2         | 2      | 2.99%   |
| SPCC                | 2         | 2      | 2.99%   |
| SK hynix            | 2         | 2      | 2.99%   |
| Crucial             | 2         | 3      | 2.99%   |
| A-DATA Technology   | 2         | 2      | 2.99%   |
| Wibtek              | 1         | 1      | 1.49%   |
| WDC                 | 1         | 1      | 1.49%   |
| Supersonic          | 1         | 1      | 1.49%   |
| Seagate             | 1         | 2      | 1.49%   |
| PNY                 | 1         | 1      | 1.49%   |
| OCZ                 | 1         | 1      | 1.49%   |
| Netac               | 1         | 1      | 1.49%   |
| MSI                 | 1         | 1      | 1.49%   |
| MaiChai             | 1         | 1      | 1.49%   |
| LITEONIT            | 1         | 2      | 1.49%   |
| Hewlett-Packard     | 1         | 1      | 1.49%   |
| Eluktro             | 1         | 1      | 1.49%   |
| Unknown             | 1         | 1      | 1.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 64        | 83     | 37.65%  |
| SSD     | 61        | 77     | 35.88%  |
| NVMe    | 31        | 45     | 18.24%  |
| MMC     | 12        | 13     | 7.06%   |
| Unknown | 2         | 2      | 1.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 116       | 156    | 70.73%  |
| NVMe | 31        | 45     | 18.9%   |
| MMC  | 12        | 13     | 7.32%   |
| SAS  | 5         | 6      | 3.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 91        | 122    | 75.21%  |
| 0.51-1.0   | 25        | 32     | 20.66%  |
| 1.01-2.0   | 4         | 4      | 3.31%   |
| 3.01-4.0   | 1         | 2      | 0.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 54        | 34.18%  |
| 251-500        | 31        | 19.62%  |
| 501-1000       | 25        | 15.82%  |
| 51-100         | 14        | 8.86%   |
| 1-20           | 13        | 8.23%   |
| 1001-2000      | 7         | 4.43%   |
| 21-50          | 6         | 3.8%    |
| 2001-3000      | 4         | 2.53%   |
| Unknown        | 3         | 1.9%    |
| More than 3000 | 1         | 0.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 66        | 39.76%  |
| 21-50     | 31        | 18.67%  |
| 51-100    | 26        | 15.66%  |
| 101-250   | 22        | 13.25%  |
| 251-500   | 6         | 3.61%   |
| 1001-2000 | 5         | 3.01%   |
| 501-1000  | 5         | 3.01%   |
| Unknown   | 3         | 1.81%   |
| 2001-3000 | 2         | 1.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500LM021-1KJ152 500GB   | 3         | 3      | 18.75%  |
| WDC WD2500BEKT-60A25T1 250GB      | 1         | 1      | 6.25%   |
| Toshiba MK6465GSXN 640GB          | 1         | 1      | 6.25%   |
| Toshiba MK3276GSX 320GB           | 1         | 1      | 6.25%   |
| Toshiba MK3275GSX 320GB           | 1         | 1      | 6.25%   |
| Seagate ST9750420AS 752GB         | 1         | 1      | 6.25%   |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 6.25%   |
| Seagate ST500LM000-1EJ162 500GB   | 1         | 1      | 6.25%   |
| Seagate ST2000LM007-1R8174 2TB    | 1         | 1      | 6.25%   |
| Samsung Electronics HM500LI 500GB | 1         | 1      | 6.25%   |
| Hitachi HTS727550A9E364 500GB     | 1         | 1      | 6.25%   |
| Hitachi HTS725032A9A364 320GB     | 1         | 1      | 6.25%   |
| Hitachi HTS547575A9E384 752GB     | 1         | 1      | 6.25%   |
| HGST HTS725050A7E630 500GB        | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 43.75%  |
| Toshiba             | 3         | 3      | 18.75%  |
| Hitachi             | 3         | 3      | 18.75%  |
| WDC                 | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| HGST                | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 43.75%  |
| Toshiba             | 3         | 3      | 18.75%  |
| Hitachi             | 3         | 3      | 18.75%  |
| WDC                 | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| HGST                | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 16     | 100%    |

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
| Detected | 93        | 150    | 59.62%  |
| Works    | 46        | 53     | 29.49%  |
| Malfunc  | 16        | 16     | 10.26%  |
| Failed   | 1         | 1      | 0.64%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 103       | 63.98%  |
| AMD                          | 23        | 14.29%  |
| Samsung Electronics          | 9         | 5.59%   |
| SanDisk                      | 7         | 4.35%   |
| SK hynix                     | 4         | 2.48%   |
| Kingston Technology Company  | 3         | 1.86%   |
| Nvidia                       | 2         | 1.24%   |
| Micron/Crucial Technology    | 2         | 1.24%   |
| Micron Technology            | 2         | 1.24%   |
| KIOXIA                       | 2         | 1.24%   |
| Union Memory (Shenzhen)      | 1         | 0.62%   |
| Toshiba America Info Systems | 1         | 0.62%   |
| Marvell Technology Group     | 1         | 0.62%   |
| Apple                        | 1         | 0.62%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 22        | 12.87%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 19        | 11.11%  |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 14        | 8.19%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 12        | 7.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 5.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 5.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 2.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 2.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 2.34%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 2.34%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 1.75%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 3         | 1.75%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 3         | 1.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.75%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 2         | 1.17%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 2         | 1.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.17%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.17%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 1.17%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 2         | 1.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.17%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 2         | 1.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.17%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 2         | 1.17%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 1         | 0.58%   |
| Toshiba America Info Systems XG3 NVMe SSD Controller                           | 1         | 0.58%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.58%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 1         | 0.58%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 1         | 0.58%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                          | 1         | 0.58%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 1         | 0.58%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 0.58%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.58%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                   | 1         | 0.58%   |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 1         | 0.58%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 0.58%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                      | 1         | 0.58%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.58%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 1         | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 102       | 61.82%  |
| NVMe | 31        | 18.79%  |
| RAID | 21        | 12.73%  |
| IDE  | 11        | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 122       | 81.88%  |
| AMD    | 27        | 18.12%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4120 CPU @ 1.10GHz             | 8         | 5.33%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 2.67%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 4         | 2.67%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 2%      |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 3         | 2%      |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 2%      |
| Intel Core i3-8130U CPU @ 2.20GHz             | 3         | 2%      |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 2%      |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.33%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 1.33%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 1.33%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 1.33%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.33%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 1.33%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 1.33%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 2         | 1.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.33%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.33%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.33%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 2         | 1.33%   |
| Intel Core i3-2375M CPU @ 1.50GHz             | 2         | 1.33%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 2         | 1.33%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.33%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.33%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.33%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 1.33%   |
| AMD A4-6210 APU with AMD Radeon R3 Graphics   | 2         | 1.33%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.67%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.67%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.67%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 0.67%   |
| Intel Genuine CPU U4100 @ 1.30GHz             | 1         | 0.67%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.67%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.67%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.67%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.67%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.67%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 0.67%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 42        | 28%     |
| Intel Core i7           | 24        | 16%     |
| Intel Celeron           | 23        | 15.33%  |
| Intel Core i3           | 14        | 9.33%   |
| Other                   | 6         | 4%      |
| AMD Ryzen 5             | 6         | 4%      |
| Intel Core 2 Duo        | 4         | 2.67%   |
| AMD Ryzen 7             | 4         | 2.67%   |
| AMD A8                  | 3         | 2%      |
| AMD A6                  | 3         | 2%      |
| AMD A10                 | 3         | 2%      |
| Intel Pentium           | 2         | 1.33%   |
| Intel Core 2            | 2         | 1.33%   |
| Intel Atom              | 2         | 1.33%   |
| AMD A4                  | 2         | 1.33%   |
| Intel Pentium Dual-Core | 1         | 0.67%   |
| Intel Pentium Dual      | 1         | 0.67%   |
| Intel Genuine           | 1         | 0.67%   |
| Intel Core i9           | 1         | 0.67%   |
| AMD Sempron             | 1         | 0.67%   |
| AMD Ryzen 3             | 1         | 0.67%   |
| AMD Quad-Core           | 1         | 0.67%   |
| AMD Mobile Sempron      | 1         | 0.67%   |
| AMD E2                  | 1         | 0.67%   |
| AMD A12                 | 1         | 0.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 91        | 60.67%  |
| 4      | 48        | 32%     |
| 6      | 4         | 2.67%   |
| 8      | 3         | 2%      |
| 1      | 3         | 2%      |
| 10     | 1         | 0.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 149       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 100       | 67.11%  |
| 1      | 49        | 32.89%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 147       | 98.66%  |
| 32-bit         | 1         | 0.67%   |
| Unknown        | 1         | 0.67%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 45.45%  |
| 0x206a7    | 11        | 7.14%   |
| 0x306a9    | 7         | 4.55%   |
| 0x806e9    | 5         | 3.25%   |
| 0x40651    | 5         | 3.25%   |
| 0x806ea    | 4         | 2.6%    |
| 0x706a1    | 4         | 2.6%    |
| 0x1067a    | 4         | 2.6%    |
| 0x706a8    | 3         | 1.95%   |
| 0x306c3    | 3         | 1.95%   |
| 0x30678    | 3         | 1.95%   |
| 0x07030105 | 3         | 1.95%   |
| 0x806ec    | 2         | 1.3%    |
| 0x6f6      | 2         | 1.3%    |
| 0x506e3    | 2         | 1.3%    |
| 0x20655    | 2         | 1.3%    |
| 0x20652    | 2         | 1.3%    |
| 0x10676    | 2         | 1.3%    |
| 0x08600103 | 2         | 1.3%    |
| 0x08108109 | 2         | 1.3%    |
| 0x906ea    | 1         | 0.65%   |
| 0x806c1    | 1         | 0.65%   |
| 0x6fd      | 1         | 0.65%   |
| 0x506c9    | 1         | 0.65%   |
| 0x406c3    | 1         | 0.65%   |
| 0x106ca    | 1         | 0.65%   |
| 0x08608103 | 1         | 0.65%   |
| 0x08608102 | 1         | 0.65%   |
| 0x08108102 | 1         | 0.65%   |
| 0x07030106 | 1         | 0.65%   |
| 0x0700010f | 1         | 0.65%   |
| 0x06006705 | 1         | 0.65%   |
| 0x0600611a | 1         | 0.65%   |
| 0x06006110 | 1         | 0.65%   |
| 0x06003106 | 1         | 0.65%   |
| 0x06001119 | 1         | 0.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 23        | 15.44%  |
| SandyBridge     | 16        | 10.74%  |
| Goldmont plus   | 14        | 9.4%    |
| IvyBridge       | 13        | 8.72%   |
| Haswell         | 12        | 8.05%   |
| Silvermont      | 7         | 4.7%    |
| Zen+            | 6         | 4.03%   |
| Westmere        | 6         | 4.03%   |
| Penryn          | 6         | 4.03%   |
| Broadwell       | 6         | 4.03%   |
| TigerLake       | 5         | 3.36%   |
| Puma            | 5         | 3.36%   |
| Skylake         | 4         | 2.68%   |
| IceLake         | 3         | 2.01%   |
| Excavator       | 3         | 2.01%   |
| Core            | 3         | 2.01%   |
| Unknown         | 3         | 2.01%   |
| Zen 2           | 2         | 1.34%   |
| Piledriver      | 2         | 1.34%   |
| Jaguar          | 2         | 1.34%   |
| Zen 3           | 1         | 0.67%   |
| Steamroller     | 1         | 0.67%   |
| K8 Hammer       | 1         | 0.67%   |
| K8 & K10 hybrid | 1         | 0.67%   |
| K10 Llano       | 1         | 0.67%   |
| Goldmont        | 1         | 0.67%   |
| CometLake       | 1         | 0.67%   |
| Bonnell         | 1         | 0.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 116       | 67.84%  |
| AMD    | 31        | 18.13%  |
| Nvidia | 24        | 14.04%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 8.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 14        | 7.95%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 6.82%   |
| Intel UHD Graphics 620                                                                   | 8         | 4.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 3.98%   |
| Intel HD Graphics 620                                                                    | 6         | 3.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 3.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.84%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 2.84%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 2.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 2.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.27%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.7%    |
| Intel Iris Plus Graphics G7                                                              | 3         | 1.7%    |
| Intel HD Graphics 6000                                                                   | 3         | 1.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.7%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 1.14%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.14%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.14%   |
| Intel HD Graphics 530                                                                    | 2         | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.14%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.14%   |
| AMD Temash [Radeon HD 8250/8280G]                                                        | 2         | 1.14%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 2         | 1.14%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.14%   |
| AMD Mullins [Radeon R3 Graphics]                                                         | 2         | 1.14%   |
| AMD Lucienne                                                                             | 2         | 1.14%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.57%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.57%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.57%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 1         | 0.57%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.57%   |
| Nvidia GM204M [GeForce GTX 960 OEM / 970M]                                               | 1         | 0.57%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.57%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.57%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.57%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 98        | 65.77%  |
| 1 x AMD        | 21        | 14.09%  |
| Intel + Nvidia | 14        | 9.4%    |
| 1 x Nvidia     | 6         | 4.03%   |
| Intel + AMD    | 4         | 2.68%   |
| AMD + Nvidia   | 4         | 2.68%   |
| 2 x AMD        | 2         | 1.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 133       | 89.26%  |
| Proprietary | 11        | 7.38%   |
| Unknown     | 5         | 3.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 121       | 79.61%  |
| 0.01-0.5   | 11        | 7.24%   |
| 1.01-2.0   | 10        | 6.58%   |
| 0.51-1.0   | 7         | 4.61%   |
| 3.01-4.0   | 2         | 1.32%   |
| 2.01-3.0   | 1         | 0.66%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 37        | 22.42%  |
| LG Display              | 23        | 13.94%  |
| BOE                     | 21        | 12.73%  |
| Chimei Innolux          | 19        | 11.52%  |
| Samsung Electronics     | 14        | 8.48%   |
| Apple                   | 9         | 5.45%   |
| Dell                    | 8         | 4.85%   |
| Chi Mei Optoelectronics | 5         | 3.03%   |
| InfoVision              | 4         | 2.42%   |
| Hewlett-Packard         | 3         | 1.82%   |
| Philips                 | 2         | 1.21%   |
| PANDA                   | 2         | 1.21%   |
| Lenovo                  | 2         | 1.21%   |
| KDC                     | 2         | 1.21%   |
| Goldstar                | 2         | 1.21%   |
| ZTR                     | 1         | 0.61%   |
| Westinghouse            | 1         | 0.61%   |
| Vizio                   | 1         | 0.61%   |
| Viotek                  | 1         | 0.61%   |
| Unknown (XXX)           | 1         | 0.61%   |
| STA                     | 1         | 0.61%   |
| Sony                    | 1         | 0.61%   |
| MSI                     | 1         | 0.61%   |
| LG Philips              | 1         | 0.61%   |
| InnoLux Display         | 1         | 0.61%   |
| CSO                     | 1         | 0.61%   |
| AOC                     | 1         | 0.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 4         | 2.42%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch           | 4         | 2.42%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch         | 4         | 2.42%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 1.82%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch           | 2         | 1.21%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 2         | 1.21%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.21%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.21%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.21%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 1.21%   |
| AU Optronics LCD Monitor AUO11EC 1366x768 344x193mm 15.5-inch         | 2         | 1.21%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch         | 2         | 1.21%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 2         | 1.21%   |
| ZTR LCD Monitor ZTR0001 1920x1080 344x194mm 15.5-inch                 | 1         | 0.61%   |
| Westinghouse EUM24F1G1 WDT1E64 1920x1080 530x300mm 24.0-inch          | 1         | 0.61%   |
| Vizio D32x-D1 VIZ1005 1920x1080 698x392mm 31.5-inch                   | 1         | 0.61%   |
| Viotek GN32DA VTK3200 2560x1440 698x393mm 31.5-inch                   | 1         | 0.61%   |
| Unknown (XXX) DTV XXX0030 1600x1200 708x398mm 32.0-inch               | 1         | 0.61%   |
| STA LCD Monitor STA0001 1366x768 256x144mm 11.6-inch                  | 1         | 0.61%   |
| Sony TV SNY1703 1360x768                                              | 1         | 0.61%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC5544 1920x1080 344x194mm 15.5-inch | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC4642 1366x768 309x174mm 14.0-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SAM0B32 1366x768 607x345mm 27.5-inch  | 1         | 0.61%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch   | 1         | 0.61%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch              | 1         | 0.61%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch              | 1         | 0.61%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 0.61%   |
| PANDA LC116LF1L02 NCP000F 1920x1080 256x144mm 11.6-inch               | 1         | 0.61%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch               | 1         | 0.61%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch           | 1         | 0.61%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch         | 1         | 0.61%   |
| LG Display LCD Monitor LGD0695 2560x1600 366x229mm 17.0-inch          | 1         | 0.61%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch          | 1         | 0.61%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch          | 1         | 0.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 72        | 45.86%  |
| 1920x1080 (FHD)    | 48        | 30.57%  |
| 1280x800 (WXGA)    | 8         | 5.1%    |
| 1600x900 (HD+)     | 7         | 4.46%   |
| 3840x2160 (4K)     | 5         | 3.18%   |
| 1440x900 (WXGA+)   | 3         | 1.91%   |
| 1280x1024 (SXGA)   | 3         | 1.91%   |
| 2560x1600          | 2         | 1.27%   |
| 1680x1050 (WSXGA+) | 2         | 1.27%   |
| 3840x1100          | 1         | 0.64%   |
| 3440x1440          | 1         | 0.64%   |
| 2560x1440 (QHD)    | 1         | 0.64%   |
| 1360x768           | 1         | 0.64%   |
| 1280x768           | 1         | 0.64%   |
| 1024x768 (XGA)     | 1         | 0.64%   |
| 1024x600           | 1         | 0.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 72        | 43.9%   |
| 13      | 28        | 17.07%  |
| 14      | 17        | 10.37%  |
| 11      | 13        | 7.93%   |
| 17      | 7         | 4.27%   |
| 31      | 4         | 2.44%   |
| 22      | 3         | 1.83%   |
| 21      | 3         | 1.83%   |
| 34      | 2         | 1.22%   |
| 24      | 2         | 1.22%   |
| 23      | 2         | 1.22%   |
| 19      | 2         | 1.22%   |
| 72      | 1         | 0.61%   |
| 40      | 1         | 0.61%   |
| 32      | 1         | 0.61%   |
| 27      | 1         | 0.61%   |
| 20      | 1         | 0.61%   |
| 18      | 1         | 0.61%   |
| 12      | 1         | 0.61%   |
| 10      | 1         | 0.61%   |
| Unknown | 1         | 0.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 96        | 59.26%  |
| 201-300     | 31        | 19.14%  |
| 351-400     | 12        | 7.41%   |
| 401-500     | 8         | 4.94%   |
| 501-600     | 5         | 3.09%   |
| 601-700     | 4         | 2.47%   |
| 701-800     | 3         | 1.85%   |
| 801-900     | 1         | 0.62%   |
| 1501-2000   | 1         | 0.62%   |
| Unknown     | 1         | 0.62%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 127       | 85.23%  |
| 16/10   | 15        | 10.07%  |
| 5/4     | 3         | 2.01%   |
| 4/3     | 1         | 0.67%   |
| 3.40    | 1         | 0.67%   |
| 21/9    | 1         | 0.67%   |
| Unknown | 1         | 0.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 71        | 43.29%  |
| 81-90          | 35        | 21.34%  |
| 51-60          | 14        | 8.54%   |
| 71-80          | 9         | 5.49%   |
| 201-250        | 9         | 5.49%   |
| 351-500        | 6         | 3.66%   |
| 121-130        | 6         | 3.66%   |
| 151-200        | 4         | 2.44%   |
| 141-150        | 2         | 1.22%   |
| 501-1000       | 2         | 1.22%   |
| More than 1000 | 1         | 0.61%   |
| 61-70          | 1         | 0.61%   |
| 41-50          | 1         | 0.61%   |
| 301-350        | 1         | 0.61%   |
| 91-100         | 1         | 0.61%   |
| Unknown        | 1         | 0.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 67        | 41.88%  |
| 121-160       | 58        | 36.25%  |
| 51-100        | 24        | 15%     |
| 161-240       | 5         | 3.13%   |
| 1-50          | 3         | 1.88%   |
| More than 240 | 2         | 1.25%   |
| Unknown       | 1         | 0.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 127       | 84.11%  |
| 2     | 20        | 13.25%  |
| 0     | 3         | 1.99%   |
| 3     | 1         | 0.66%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 72        | 31.3%   |
| Realtek Semiconductor           | 70        | 30.43%  |
| Qualcomm Atheros                | 33        | 14.35%  |
| Broadcom                        | 21        | 9.13%   |
| Broadcom Limited                | 7         | 3.04%   |
| Ralink Technology               | 6         | 2.61%   |
| Qualcomm Atheros Communications | 3         | 1.3%    |
| Nvidia                          | 2         | 0.87%   |
| Marvell Technology Group        | 2         | 0.87%   |
| Lenovo                          | 2         | 0.87%   |
| Dell                            | 2         | 0.87%   |
| ZTopInc                         | 1         | 0.43%   |
| Ralink                          | 1         | 0.43%   |
| MediaTek                        | 1         | 0.43%   |
| JCM                             | 1         | 0.43%   |
| Huawei Technologies             | 1         | 0.43%   |
| Google                          | 1         | 0.43%   |
| Edimax Technology               | 1         | 0.43%   |
| DisplayLink                     | 1         | 0.43%   |
| ASIX Electronics                | 1         | 0.43%   |
| AMD                             | 1         | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 28        | 10.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 20        | 7.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12        | 4.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 9         | 3.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 8         | 2.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 8         | 2.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 7         | 2.53%   |
| Intel Wireless 7260                                                    | 7         | 2.53%   |
| Ralink MT7601U Wireless Adapter                                        | 5         | 1.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 1.81%   |
| Intel Wireless 7265                                                    | 5         | 1.81%   |
| Intel Wireless 3165                                                    | 5         | 1.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 5         | 1.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 4         | 1.44%   |
| Intel Wi-Fi 6 AX201                                                    | 4         | 1.44%   |
| Intel Wi-Fi 6 AX200                                                    | 4         | 1.44%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 1.44%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 4         | 1.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 4         | 1.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3         | 1.08%   |
| Realtek 802.11n WLAN Adapter                                           | 3         | 1.08%   |
| Qualcomm Atheros AR9271 802.11n                                        | 3         | 1.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 3         | 1.08%   |
| Intel Wireless 8265 / 8275                                             | 3         | 1.08%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 1.08%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 1.08%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 1.08%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.08%   |
| Intel Centrino Ultimate-N 6300                                         | 3         | 1.08%   |
| Intel Centrino Advanced-N 6235                                         | 3         | 1.08%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 1.08%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 3         | 1.08%   |
| Broadcom BCM43142 802.11b/g/n                                          | 3         | 1.08%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 2         | 0.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2         | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 2         | 0.72%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 2         | 0.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 0.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 68        | 41.98%  |
| Qualcomm Atheros                | 29        | 17.9%   |
| Realtek Semiconductor           | 28        | 17.28%  |
| Broadcom                        | 17        | 10.49%  |
| Ralink Technology               | 6         | 3.7%    |
| Broadcom Limited                | 5         | 3.09%   |
| Qualcomm Atheros Communications | 3         | 1.85%   |
| Dell                            | 2         | 1.23%   |
| ZTopInc                         | 1         | 0.62%   |
| Ralink                          | 1         | 0.62%   |
| MediaTek                        | 1         | 0.62%   |
| Edimax Technology               | 1         | 0.62%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 5.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 4.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 4.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 4.29%   |
| Intel Wireless 7260                                                     | 7         | 4.29%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 3.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 3.07%   |
| Intel Wireless 7265                                                     | 5         | 3.07%   |
| Intel Wireless 3165                                                     | 5         | 3.07%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 3.07%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 2.45%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 2.45%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 2.45%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter    | 4         | 2.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 2.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.84%   |
| Realtek 802.11n WLAN Adapter                                            | 3         | 1.84%   |
| Qualcomm Atheros AR9271 802.11n                                         | 3         | 1.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 1.84%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.84%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.84%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.84%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 1.84%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.84%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 1.23%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.23%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.23%   |
| Intel Wireless 8260                                                     | 2         | 1.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.23%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.23%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.23%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.23%   |
| ZTopInc 802.11n NIC                                                     | 1         | 0.61%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.61%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 52        | 46.43%  |
| Intel                    | 33        | 29.46%  |
| Broadcom                 | 8         | 7.14%   |
| Qualcomm Atheros         | 7         | 6.25%   |
| Nvidia                   | 2         | 1.79%   |
| Marvell Technology Group | 2         | 1.79%   |
| Lenovo                   | 2         | 1.79%   |
| Broadcom Limited         | 2         | 1.79%   |
| Huawei Technologies      | 1         | 0.89%   |
| Google                   | 1         | 0.89%   |
| DisplayLink              | 1         | 0.89%   |
| ASIX Electronics         | 1         | 0.89%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 28        | 25%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 20        | 17.86%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12        | 10.71%  |
| Intel 82577LM Gigabit Network Connection                               | 4         | 3.57%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 2.68%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 2.68%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 2.68%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 2.68%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 2.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 1.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 1.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 1.79%   |
| Lenovo Thinkpad LAN                                                    | 2         | 1.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.89%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.89%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.89%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.89%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.89%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.89%   |
| Nvidia MCP77 Ethernet                                                  | 1         | 0.89%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 0.89%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.89%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 0.89%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.89%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 0.89%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 0.89%   |
| Intel 82579V Gigabit Network Connection                                | 1         | 0.89%   |
| Huawei E353/E3131                                                      | 1         | 0.89%   |
| Google Pixel 6                                                         | 1         | 0.89%   |
| DisplayLink USB3 TO HDMI                                               | 1         | 0.89%   |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                      | 1         | 0.89%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 0.89%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1         | 0.89%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 0.89%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 0.89%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express       | 1         | 0.89%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express            | 1         | 0.89%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1         | 0.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 147       | 57.42%  |
| Ethernet | 107       | 41.8%   |
| Modem    | 2         | 0.78%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 123       | 80.92%  |
| Ethernet | 29        | 19.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 103       | 69.13%  |
| 1     | 41        | 27.52%  |
| 0     | 5         | 3.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 131       | 86.18%  |
| Yes  | 21        | 13.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 48        | 42.86%  |
| Qualcomm Atheros Communications | 16        | 14.29%  |
| IMC Networks                    | 12        | 10.71%  |
| Realtek Semiconductor           | 11        | 9.82%   |
| Apple                           | 9         | 8.04%   |
| Dell                            | 7         | 6.25%   |
| Broadcom                        | 5         | 4.46%   |
| Lite-On Technology              | 3         | 2.68%   |
| Hewlett-Packard                 | 1         | 0.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 23        | 20.54%  |
| Qualcomm Atheros  Bluetooth Device                | 8         | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 8         | 7.14%   |
| IMC Networks Bluetooth Radio                      | 8         | 7.14%   |
| Realtek  Bluetooth 4.2 Adapter                    | 6         | 5.36%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 5         | 4.46%   |
| Intel AX201 Bluetooth                             | 5         | 4.46%   |
| Apple Bluetooth Host Controller                   | 5         | 4.46%   |
| Intel AX200 Bluetooth                             | 4         | 3.57%   |
| Realtek Bluetooth Radio                           | 3         | 2.68%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 3         | 2.68%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 3         | 2.68%   |
| Dell BCM20702A0 Bluetooth Module                  | 3         | 2.68%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 3         | 2.68%   |
| Apple Bluetooth USB Host Controller               | 3         | 2.68%   |
| Intel Wireless-AC 3168 Bluetooth                  | 2         | 1.79%   |
| Realtek RTL8723B Bluetooth                        | 1         | 0.89%   |
| Realtek 802.11ac WLAN Adapter                     | 1         | 0.89%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 1         | 0.89%   |
| Qualcomm Atheros Bluetooth USB Host Controller    | 1         | 0.89%   |
| Lite-On Wireless_Device                           | 1         | 0.89%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 1         | 0.89%   |
| Lite-On Atheros AR3012 Bluetooth                  | 1         | 0.89%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 0.89%   |
| IMC Networks Bluetooth Device                     | 1         | 0.89%   |
| IMC Networks Bluetooth                            | 1         | 0.89%   |
| IMC Networks BCM20702A0                           | 1         | 0.89%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 1         | 0.89%   |
| HP Broadcom 2070 Bluetooth Combo                  | 1         | 0.89%   |
| Dell Wireless 360 Bluetooth                       | 1         | 0.89%   |
| Dell Wireless 355 Bluetooth                       | 1         | 0.89%   |
| Dell Wireless 350 Bluetooth                       | 1         | 0.89%   |
| Dell DW375 Bluetooth Module                       | 1         | 0.89%   |
| Broadcom HP Portable SoftSailing                  | 1         | 0.89%   |
| Broadcom BCM2045B (BDC-2.1)                       | 1         | 0.89%   |
| Apple Bluetooth HCI                               | 1         | 0.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 120       | 71.43%  |
| AMD                    | 27        | 16.07%  |
| Nvidia                 | 14        | 8.33%   |
| Logitech               | 2         | 1.19%   |
| Texas Instruments      | 1         | 0.6%    |
| Sony                   | 1         | 0.6%    |
| M-Audio                | 1         | 0.6%    |
| Generalplus Technology | 1         | 0.6%    |
| C-Media Electronics    | 1         | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 17        | 8.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 15        | 7.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 14        | 6.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 6.76%   |
| AMD FCH Azalia Controller                                                                         | 11        | 5.31%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 11        | 5.31%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 4.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 3.38%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 3.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 2.9%    |
| Intel Broadwell-U Audio Controller                                                                | 6         | 2.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 2.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 2.42%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 2.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 2.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.93%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.45%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.45%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.45%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.45%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.97%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.97%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.97%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.97%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.48%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1         | 0.48%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.48%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.48%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.48%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.48%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.48%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.48%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 24        | 26.67%  |
| Samsung Electronics | 23        | 25.56%  |
| Micron Technology   | 11        | 12.22%  |
| Unknown (ABCD)      | 7         | 7.78%   |
| Crucial             | 6         | 6.67%   |
| Kingston            | 4         | 4.44%   |
| Unknown             | 3         | 3.33%   |
| Ramaxel Technology  | 3         | 3.33%   |
| Nanya Technology    | 2         | 2.22%   |
| A-DATA Technology   | 2         | 2.22%   |
| Unknown             | 2         | 2.22%   |
| Sesame              | 1         | 1.11%   |
| PNY                 | 1         | 1.11%   |
| Heoriady            | 1         | 1.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 7         | 7.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 3.23%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 3         | 3.23%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.15%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 2.15%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 2.15%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 2         | 2.15%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.15%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 2.15%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 2.15%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s             | 2         | 2.15%   |
| A-DATA RAM AD73I1B1674EU 2GB SODIMM DDR3 1334MT/s                | 2         | 2.15%   |
| Unknown                                                          | 2         | 2.15%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.08%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 1.08%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 1.08%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.08%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                     | 1         | 1.08%   |
| SK hynix RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 1.08%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s         | 1         | 1.08%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.08%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.08%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.08%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.08%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.08%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.08%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.08%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.08%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.08%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.08%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.08%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.08%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.08%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.08%   |
| Sesame RAM S939A2SGS-ITR 8GB SODIMM DDR4 2667MT/s                | 1         | 1.08%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 1         | 1.08%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s              | 1         | 1.08%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.08%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 1         | 1.08%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 1.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 28        | 39.44%  |
| DDR4   | 23        | 32.39%  |
| LPDDR4 | 11        | 15.49%  |
| SDRAM  | 4         | 5.63%   |
| LPDDR3 | 2         | 2.82%   |
| DDR2   | 2         | 2.82%   |
| DRAM   | 1         | 1.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 64        | 91.43%  |
| Row Of Chips | 5         | 7.14%   |
| DIMM         | 1         | 1.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 28        | 35.9%   |
| 8192  | 25        | 32.05%  |
| 2048  | 16        | 20.51%  |
| 16384 | 8         | 10.26%  |
| 1024  | 1         | 1.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 20        | 24.69%  |
| 2400  | 14        | 17.28%  |
| 2667  | 11        | 13.58%  |
| 1333  | 8         | 9.88%   |
| 3200  | 6         | 7.41%   |
| 2133  | 5         | 6.17%   |
| 4199  | 3         | 3.7%    |
| 1334  | 3         | 3.7%    |
| 4267  | 2         | 2.47%   |
| 3266  | 2         | 2.47%   |
| 1067  | 2         | 2.47%   |
| 667   | 2         | 2.47%   |
| 2048  | 1         | 1.23%   |
| 1867  | 1         | 1.23%   |
| 975   | 1         | 1.23%   |

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
| Chicony Electronics                    | 23        | 17.83%  |
| Microdia                               | 21        | 16.28%  |
| Sunplus Innovation Technology          | 15        | 11.63%  |
| IMC Networks                           | 14        | 10.85%  |
| Realtek Semiconductor                  | 10        | 7.75%   |
| Suyin                                  | 9         | 6.98%   |
| Apple                                  | 6         | 4.65%   |
| Syntek                                 | 4         | 3.1%    |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.1%    |
| Silicon Motion                         | 3         | 2.33%   |
| Ricoh                                  | 3         | 2.33%   |
| Quanta                                 | 2         | 1.55%   |
| Primax Electronics                     | 2         | 1.55%   |
| icSpring                               | 2         | 1.55%   |
| Bison Electronics                      | 2         | 1.55%   |
| Sonix Technology                       | 1         | 0.78%   |
| Samsung Electronics                    | 1         | 0.78%   |
| OmniVision Technologies                | 1         | 0.78%   |
| MacroSilicon                           | 1         | 0.78%   |
| Logitech                               | 1         | 0.78%   |
| Lite-On Technology                     | 1         | 0.78%   |
| globaloptics                           | 1         | 0.78%   |
| Generalplus Technology                 | 1         | 0.78%   |
| Alcor Micro                            | 1         | 0.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 7         | 5.43%   |
| Sunplus Integrated_Webcam_HD                                   | 6         | 4.65%   |
| Microdia HP Integrated Webcam                                  | 6         | 4.65%   |
| IMC Networks Integrated Camera                                 | 5         | 3.88%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 4         | 3.1%    |
| Microdia Integrated_Webcam_HD                                  | 3         | 2.33%   |
| Microdia Dell Integrated HD Webcam                             | 3         | 2.33%   |
| IMC Networks HP TrueVision HD Camera                           | 3         | 2.33%   |
| Chicony USB2.0 HD UVC WebCam                                   | 3         | 2.33%   |
| Chicony HP TrueVision HD                                       | 3         | 2.33%   |
| Apple FaceTime HD Camera                                       | 3         | 2.33%   |
| Syntek Lenovo EasyCamera                                       | 2         | 1.55%   |
| Suyin Laptop_Integrated_Webcam_HD                              | 2         | 1.55%   |
| Suyin Integrated_Webcam_HD                                     | 2         | 1.55%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 2         | 1.55%   |
| Realtek USB2.0 camera                                          | 2         | 1.55%   |
| Realtek Integrated Webcam HD                                   | 2         | 1.55%   |
| Realtek Integrated Webcam                                      | 2         | 1.55%   |
| Microdia Sonix USB 2.0 Camera                                  | 2         | 1.55%   |
| Microdia Integrated Webcam                                     | 2         | 1.55%   |
| Chicony Integrated HP HD Webcam                                | 2         | 1.55%   |
| Chicony HD User Facing                                         | 2         | 1.55%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 1.55%   |
| Syntek Integrated Camera                                       | 1         | 0.78%   |
| Syntek EasyCamera                                              | 1         | 0.78%   |
| Suyin VGA Webcam                                               | 1         | 0.78%   |
| Suyin TOSHIBA Web Camera - HD                                  | 1         | 0.78%   |
| Suyin HP TrueVision HD                                         | 1         | 0.78%   |
| Suyin Acer/Lenovo Webcam [CN0316]                              | 1         | 0.78%   |
| Suyin 1.3M HD WebCam                                           | 1         | 0.78%   |
| Sunplus Laptop_Integrated_Webcam_HD                            | 1         | 0.78%   |
| Sunplus Laptop_Integrated_Webcam_1.3M                          | 1         | 0.78%   |
| Sunplus Integrated_Webcam_FHD                                  | 1         | 0.78%   |
| Sunplus HP Wide Vision HD                                      | 1         | 0.78%   |
| Sunplus HD WebCam                                              | 1         | 0.78%   |
| Sunplus ASUS Webcam                                            | 1         | 0.78%   |
| Sunplus 1.3M HD WebCam                                         | 1         | 0.78%   |
| Sonix HP Webcam-101                                            | 1         | 0.78%   |
| Silicon Motion WebCam SCB-0385N                                | 1         | 0.78%   |
| Silicon Motion WebCam SC-10HDD13335N                           | 1         | 0.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 38.89%  |
| Synaptics                  | 5         | 27.78%  |
| Elan Microelectronics      | 3         | 16.67%  |
| STMicroelectronics         | 1         | 5.56%   |
| Shenzhen Goodix Technology | 1         | 5.56%   |
| LighTuning Technology      | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 4         | 22.22%  |
| Validity Sensors VFS471 Fingerprint Reader        | 2         | 11.11%  |
| Elan ELAN:ARM-M4                                  | 2         | 11.11%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 5.56%   |
| Validity Sensors VFS491                           | 1         | 5.56%   |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 5.56%   |
| Validity Sensors Synaptics WBDI                   | 1         | 5.56%   |
| Validity Sensors Fingerprint scanner              | 1         | 5.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 5.56%   |
| STMicroelectronics Fingerprint Reader             | 1         | 5.56%   |
| Shenzhen Goodix  FingerPrint Device               | 1         | 5.56%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 5.56%   |
| Elan ELAN:Fingerprint                             | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 9         | 69.23%  |
| O2 Micro    | 2         | 15.38%  |
| Alcor Micro | 2         | 15.38%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 30.77%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 15.38%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 15.38%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 15.38%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 7.69%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 7.69%   |
| Broadcom 58200                                                               | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 105       | 69.08%  |
| 1     | 37        | 24.34%  |
| 2     | 10        | 6.58%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 18        | 31.58%  |
| Chipcard              | 11        | 19.3%   |
| Graphics card         | 10        | 17.54%  |
| Multimedia controller | 7         | 12.28%  |
| Net/wireless          | 4         | 7.02%   |
| Storage               | 3         | 5.26%   |
| Card reader           | 2         | 3.51%   |
| Camera                | 1         | 1.75%   |
| Bluetooth             | 1         | 1.75%   |

