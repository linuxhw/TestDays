Linux in Kazakhstan - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Kazakhstan.

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

Total: 547

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [10501c1c92](https://linux-hardware.org/?probe=10501c1c92) | Dec 26, 2024 |
| Acer          | Aspire A515-57              | [c09f54f867](https://linux-hardware.org/?probe=c09f54f867) | Dec 17, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [ee4dd3336d](https://linux-hardware.org/?probe=ee4dd3336d) | Nov 29, 2024 |
| Acer          | Nitro AN515-55              | [410a568ba4](https://linux-hardware.org/?probe=410a568ba4) | Nov 20, 2024 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [1860ba92b8](https://linux-hardware.org/?probe=1860ba92b8) | Nov 17, 2024 |
| Acer          | Nitro AN515-46              | [561df0051a](https://linux-hardware.org/?probe=561df0051a) | Nov 15, 2024 |
| Acer          | Nitro ANV15-41              | [41a8d79a11](https://linux-hardware.org/?probe=41a8d79a11) | Nov 14, 2024 |
| Acer          | Aspire A315-59              | [ef0b873549](https://linux-hardware.org/?probe=ef0b873549) | Oct 29, 2024 |
| ASUSTek       | X553MA                      | [ea7d1235b1](https://linux-hardware.org/?probe=ea7d1235b1) | Oct 28, 2024 |
| Samsung       | 300E4C/300E5C/300E7C        | [3ee9dc7745](https://linux-hardware.org/?probe=3ee9dc7745) | Oct 22, 2024 |
| HP            | Laptop 15s-eq2xxx           | [e022107a17](https://linux-hardware.org/?probe=e022107a17) | Oct 14, 2024 |
| ASUSTek       | ASUS Vivobook Pro 15 N65... | [caabd0867c](https://linux-hardware.org/?probe=caabd0867c) | Oct 11, 2024 |
| Acer          | Predator PH317-56           | [96bdb2ab93](https://linux-hardware.org/?probe=96bdb2ab93) | Sep 30, 2024 |
| Acer          | Aspire E5-575G              | [4cec70b2ed](https://linux-hardware.org/?probe=4cec70b2ed) | Sep 16, 2024 |
| Acer          | Aspire E5-575G              | [72effb4ee2](https://linux-hardware.org/?probe=72effb4ee2) | Sep 16, 2024 |
| ASUSTek       | ASUS Vivobook S 16 S5606... | [088c823b60](https://linux-hardware.org/?probe=088c823b60) | Aug 31, 2024 |
| HUAWEI        | MCLF-XX                     | [8380049b51](https://linux-hardware.org/?probe=8380049b51) | Aug 20, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1502CVA... | [42e09214a4](https://linux-hardware.org/?probe=42e09214a4) | Aug 18, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9d1f60f81a](https://linux-hardware.org/?probe=9d1f60f81a) | Aug 17, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1502CVA... | [e8511ac05e](https://linux-hardware.org/?probe=e8511ac05e) | Aug 02, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [d60f72815e](https://linux-hardware.org/?probe=d60f72815e) | Jul 23, 2024 |
| Acer          | Aspire E5-573G              | [183db55de5](https://linux-hardware.org/?probe=183db55de5) | Jul 22, 2024 |
| HP            | Laptop 15s-fq5xxx           | [0bdf8eae36](https://linux-hardware.org/?probe=0bdf8eae36) | Jul 12, 2024 |
| ASUSTek       | X541SA                      | [9c8da1caab](https://linux-hardware.org/?probe=9c8da1caab) | Jul 04, 2024 |
| Lenovo        | LOQ 15AHP9 83DX             | [529a1bbe93](https://linux-hardware.org/?probe=529a1bbe93) | Jul 03, 2024 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [901ec74a46](https://linux-hardware.org/?probe=901ec74a46) | Jun 24, 2024 |
| HP            | Pavilion Notebook           | [d206663ba5](https://linux-hardware.org/?probe=d206663ba5) | Jun 14, 2024 |
| Samsung       | 3570R/370R/470R/450R/510... | [1a4d2729dd](https://linux-hardware.org/?probe=1a4d2729dd) | Jun 12, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [4578b34174](https://linux-hardware.org/?probe=4578b34174) | Jun 08, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [cc1ed9cea2](https://linux-hardware.org/?probe=cc1ed9cea2) | Jun 08, 2024 |
| HP            | Pavilion dv6                | [424bc18b37](https://linux-hardware.org/?probe=424bc18b37) | Jun 03, 2024 |
| YiFang        | NXW9QC132                   | [50d779752e](https://linux-hardware.org/?probe=50d779752e) | May 29, 2024 |
| HP            | Pavilion Notebook           | [f573f86638](https://linux-hardware.org/?probe=f573f86638) | May 18, 2024 |
| Acer          | Nitro AN515-54              | [763bcd2c5c](https://linux-hardware.org/?probe=763bcd2c5c) | May 12, 2024 |
| Lenovo        | G575 20081                  | [581885ea87](https://linux-hardware.org/?probe=581885ea87) | May 11, 2024 |
| Unknown       | Apple MacBook Air (M1, 2... | [bf21e1d142](https://linux-hardware.org/?probe=bf21e1d142) | May 11, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [9c7ba4a173](https://linux-hardware.org/?probe=9c7ba4a173) | May 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [91ed38bf6d](https://linux-hardware.org/?probe=91ed38bf6d) | May 08, 2024 |
| Dell          | Latitude 7490               | [5e80dec6c8](https://linux-hardware.org/?probe=5e80dec6c8) | May 01, 2024 |
| HUAWEI        | BOHB-WAX9                   | [fd94025498](https://linux-hardware.org/?probe=fd94025498) | Apr 23, 2024 |
| HP            | Victus by Gaming Laptop ... | [4ffd3e632b](https://linux-hardware.org/?probe=4ffd3e632b) | Apr 22, 2024 |
| HP            | Unknown                     | [9415eb2f3c](https://linux-hardware.org/?probe=9415eb2f3c) | Apr 14, 2024 |
| Acer          | AO756                       | [79847ca0b1](https://linux-hardware.org/?probe=79847ca0b1) | Apr 11, 2024 |
| Acer          | One S1002                   | [801033acf2](https://linux-hardware.org/?probe=801033acf2) | Mar 25, 2024 |
| Acer          | One S1002                   | [7f3114ec4e](https://linux-hardware.org/?probe=7f3114ec4e) | Mar 24, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [433fee63bc](https://linux-hardware.org/?probe=433fee63bc) | Mar 24, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [bbb4a23341](https://linux-hardware.org/?probe=bbb4a23341) | Mar 24, 2024 |
| Lenovo        | Legion R9000P ARX8 82WM     | [458c974b3b](https://linux-hardware.org/?probe=458c974b3b) | Mar 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [faca2983cf](https://linux-hardware.org/?probe=faca2983cf) | Mar 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [2152124e4d](https://linux-hardware.org/?probe=2152124e4d) | Mar 19, 2024 |
| Valve         | Jupiter                     | [930838ef76](https://linux-hardware.org/?probe=930838ef76) | Mar 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [299b810e81](https://linux-hardware.org/?probe=299b810e81) | Mar 06, 2024 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [aeee54cee7](https://linux-hardware.org/?probe=aeee54cee7) | Feb 27, 2024 |
| ASUSTek       | X555LAB                     | [126dbc29f9](https://linux-hardware.org/?probe=126dbc29f9) | Feb 26, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [3015e2635f](https://linux-hardware.org/?probe=3015e2635f) | Feb 25, 2024 |
| HP            | Victus by Gaming Laptop ... | [46e3558e2c](https://linux-hardware.org/?probe=46e3558e2c) | Feb 23, 2024 |
| HP            | Victus by Gaming Laptop ... | [32aa95befd](https://linux-hardware.org/?probe=32aa95befd) | Feb 23, 2024 |
| Dell          | Latitude 5540               | [c5a3f8e55f](https://linux-hardware.org/?probe=c5a3f8e55f) | Feb 16, 2024 |
| Lenovo        | ThinkPad X240 20AMS1E201    | [469bc2a33d](https://linux-hardware.org/?probe=469bc2a33d) | Feb 11, 2024 |
| Acer          | Aspire A315-58              | [7053f118d5](https://linux-hardware.org/?probe=7053f118d5) | Feb 09, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [48cf9448c1](https://linux-hardware.org/?probe=48cf9448c1) | Feb 09, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e94976b6d9](https://linux-hardware.org/?probe=e94976b6d9) | Feb 01, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | [dd92e4a676](https://linux-hardware.org/?probe=dd92e4a676) | Jan 29, 2024 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [ffc3c06598](https://linux-hardware.org/?probe=ffc3c06598) | Jan 29, 2024 |
| Lenovo        | G500 20236                  | [312fc3b893](https://linux-hardware.org/?probe=312fc3b893) | Jan 28, 2024 |
| Acer          | Aspire E1-570               | [7def6b176c](https://linux-hardware.org/?probe=7def6b176c) | Jan 19, 2024 |
| Acer          | Aspire E1-570               | [47a1e9c03c](https://linux-hardware.org/?probe=47a1e9c03c) | Jan 19, 2024 |
| ASUSTek       | K50IJ                       | [2626e31d7a](https://linux-hardware.org/?probe=2626e31d7a) | Jan 14, 2024 |
| Valve         | Jupiter                     | [96faa10437](https://linux-hardware.org/?probe=96faa10437) | Jan 11, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [62a2d8032e](https://linux-hardware.org/?probe=62a2d8032e) | Jan 06, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [710f99bd78](https://linux-hardware.org/?probe=710f99bd78) | Jan 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7fdd8a3f38](https://linux-hardware.org/?probe=7fdd8a3f38) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a1fd8cc737](https://linux-hardware.org/?probe=a1fd8cc737) | Dec 26, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [775e2dfe26](https://linux-hardware.org/?probe=775e2dfe26) | Dec 19, 2023 |
| ASUSTek       | N56DP                       | [736ba321d5](https://linux-hardware.org/?probe=736ba321d5) | Dec 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [f4c923a84a](https://linux-hardware.org/?probe=f4c923a84a) | Dec 16, 2023 |
| Samsung       | R428/P428                   | [bcfc7ba90f](https://linux-hardware.org/?probe=bcfc7ba90f) | Dec 09, 2023 |
| Valve         | Jupiter                     | [2c693deae3](https://linux-hardware.org/?probe=2c693deae3) | Dec 07, 2023 |
| Lenovo        | G500 20236                  | [6d0f07a930](https://linux-hardware.org/?probe=6d0f07a930) | Dec 05, 2023 |
| Acer          | Aspire V3-772               | [622055b29a](https://linux-hardware.org/?probe=622055b29a) | Dec 02, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [d5d85d7080](https://linux-hardware.org/?probe=d5d85d7080) | Nov 27, 2023 |
| ASUSTek       | ROG Strix G834JY_G834JY     | [26a2d5750f](https://linux-hardware.org/?probe=26a2d5750f) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [8416c7e558](https://linux-hardware.org/?probe=8416c7e558) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [9aada56395](https://linux-hardware.org/?probe=9aada56395) | Nov 23, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [c6e62720db](https://linux-hardware.org/?probe=c6e62720db) | Nov 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1aa00f4008](https://linux-hardware.org/?probe=1aa00f4008) | Nov 17, 2023 |
| Dell          | Vostro 3500                 | [860fc63d0d](https://linux-hardware.org/?probe=860fc63d0d) | Nov 09, 2023 |
| HONOR         | NBR-WAX9                    | [173692c48a](https://linux-hardware.org/?probe=173692c48a) | Nov 08, 2023 |
| Lenovo        | ThinkPad T430 23475H2       | [3dcdf3830e](https://linux-hardware.org/?probe=3dcdf3830e) | Nov 07, 2023 |
| Dell          | Latitude E7270              | [07d72d2a9d](https://linux-hardware.org/?probe=07d72d2a9d) | Oct 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [1bd81ebf81](https://linux-hardware.org/?probe=1bd81ebf81) | Oct 24, 2023 |
| HP            | Pavilion Laptop 15-eh3xx... | [d2a1f0ba6e](https://linux-hardware.org/?probe=d2a1f0ba6e) | Oct 24, 2023 |
| HP            | Pavilion Notebook           | [ffeaa7da2f](https://linux-hardware.org/?probe=ffeaa7da2f) | Oct 21, 2023 |
| HONOR         | NBR-WAX9                    | [5966a36809](https://linux-hardware.org/?probe=5966a36809) | Oct 21, 2023 |
| HP            | Pavilion Notebook           | [9d49844572](https://linux-hardware.org/?probe=9d49844572) | Oct 20, 2023 |
| Acer          | Aspire 5750G                | [ae0eccc095](https://linux-hardware.org/?probe=ae0eccc095) | Oct 18, 2023 |
| Acer          | Predator PH317-56           | [2089e200d9](https://linux-hardware.org/?probe=2089e200d9) | Oct 12, 2023 |
| Acer          | Aspire 5750G                | [56bdc382d5](https://linux-hardware.org/?probe=56bdc382d5) | Oct 10, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [30b0879baa](https://linux-hardware.org/?probe=30b0879baa) | Oct 07, 2023 |
| Acer          | Predator PH317-56           | [3adaae9e9e](https://linux-hardware.org/?probe=3adaae9e9e) | Oct 06, 2023 |
| Acer          | Predator PH317-54           | [8745400c59](https://linux-hardware.org/?probe=8745400c59) | Oct 06, 2023 |
| HP            | Notebook                    | [02403b0967](https://linux-hardware.org/?probe=02403b0967) | Oct 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [7ebc133bf7](https://linux-hardware.org/?probe=7ebc133bf7) | Oct 02, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [b8ace5a2d6](https://linux-hardware.org/?probe=b8ace5a2d6) | Oct 02, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [11cbffaee6](https://linux-hardware.org/?probe=11cbffaee6) | Oct 02, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [ec1384a424](https://linux-hardware.org/?probe=ec1384a424) | Sep 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [d958b4e16a](https://linux-hardware.org/?probe=d958b4e16a) | Sep 29, 2023 |
| HONOR         | NBR-WAX9                    | [68556b1e09](https://linux-hardware.org/?probe=68556b1e09) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | [056de6b9b3](https://linux-hardware.org/?probe=056de6b9b3) | Sep 27, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [14d87bfb5d](https://linux-hardware.org/?probe=14d87bfb5d) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [6f676cd559](https://linux-hardware.org/?probe=6f676cd559) | Sep 18, 2023 |
| Dell          | Inspiron 5520               | [91404ec81d](https://linux-hardware.org/?probe=91404ec81d) | Sep 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [83021c4304](https://linux-hardware.org/?probe=83021c4304) | Sep 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [9ea0aa4b28](https://linux-hardware.org/?probe=9ea0aa4b28) | Sep 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [ea096b699b](https://linux-hardware.org/?probe=ea096b699b) | Sep 04, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [f92734bf2b](https://linux-hardware.org/?probe=f92734bf2b) | Sep 03, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [0140ea0642](https://linux-hardware.org/?probe=0140ea0642) | Aug 26, 2023 |
| ASUSTek       | X541SA                      | [109de7a1ae](https://linux-hardware.org/?probe=109de7a1ae) | Aug 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [fdd24243bf](https://linux-hardware.org/?probe=fdd24243bf) | Aug 22, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [49662a8ac9](https://linux-hardware.org/?probe=49662a8ac9) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c946b79f5a](https://linux-hardware.org/?probe=c946b79f5a) | Aug 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [d8caf086ad](https://linux-hardware.org/?probe=d8caf086ad) | Aug 04, 2023 |
| Dell          | Vostro 3500                 | [5f63621af2](https://linux-hardware.org/?probe=5f63621af2) | Aug 04, 2023 |
| Acer          | Aspire A515-57              | [87c4730d07](https://linux-hardware.org/?probe=87c4730d07) | Aug 03, 2023 |
| Acer          | Aspire 5560                 | [86868232f0](https://linux-hardware.org/?probe=86868232f0) | Jul 27, 2023 |
| Dell          | Vostro 3500                 | [69cc1eb6f6](https://linux-hardware.org/?probe=69cc1eb6f6) | Jul 18, 2023 |
| Acer          | Aspire A315-51              | [9d3efe2fa2](https://linux-hardware.org/?probe=9d3efe2fa2) | Jul 18, 2023 |
| Acer          | Aspire E1-531               | [77e5715691](https://linux-hardware.org/?probe=77e5715691) | Jul 12, 2023 |
| Lenovo        | G505s 20255                 | [4ec56be6a5](https://linux-hardware.org/?probe=4ec56be6a5) | Jul 03, 2023 |
| Lenovo        | G505s 20255                 | [107c99d5ee](https://linux-hardware.org/?probe=107c99d5ee) | Jul 03, 2023 |
| Lenovo        | G505s 20255                 | [0617f8b2f0](https://linux-hardware.org/?probe=0617f8b2f0) | Jul 02, 2023 |
| Lenovo        | G505s 20255                 | [2940c0be7d](https://linux-hardware.org/?probe=2940c0be7d) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [8a833d8c52](https://linux-hardware.org/?probe=8a833d8c52) | Jun 25, 2023 |
| Acer          | Aspire A315-51              | [0e6960c76b](https://linux-hardware.org/?probe=0e6960c76b) | Jun 22, 2023 |
| Acer          | Aspire A315-51              | [981385c200](https://linux-hardware.org/?probe=981385c200) | Jun 22, 2023 |
| HP            | Laptop 15-rb0xx             | [067eeb10e5](https://linux-hardware.org/?probe=067eeb10e5) | Jun 19, 2023 |
| HUAWEI        | BOM-WXX9                    | [130605379e](https://linux-hardware.org/?probe=130605379e) | Jun 15, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [dd2a8a9559](https://linux-hardware.org/?probe=dd2a8a9559) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [a6d6fdfe4f](https://linux-hardware.org/?probe=a6d6fdfe4f) | Jun 02, 2023 |
| Acer          | Aspire ES1-523              | [bd06482a4e](https://linux-hardware.org/?probe=bd06482a4e) | May 27, 2023 |
| HP            | Notebook                    | [3467291a26](https://linux-hardware.org/?probe=3467291a26) | May 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [02df3a407e](https://linux-hardware.org/?probe=02df3a407e) | May 03, 2023 |
| HP            | Pavilion Notebook           | [168b3cf595](https://linux-hardware.org/?probe=168b3cf595) | Apr 29, 2023 |
| ASUSTek       | X55VD                       | [16ef8c0549](https://linux-hardware.org/?probe=16ef8c0549) | Apr 27, 2023 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [61408603be](https://linux-hardware.org/?probe=61408603be) | Apr 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0187ac7a0c](https://linux-hardware.org/?probe=0187ac7a0c) | Apr 19, 2023 |
| Acer          | Aspire A515-57              | [ea0055d848](https://linux-hardware.org/?probe=ea0055d848) | Apr 14, 2023 |
| Dell          | G5 5590                     | [9c1f2f432b](https://linux-hardware.org/?probe=9c1f2f432b) | Apr 11, 2023 |
| HP            | Notebook                    | [41f9931a45](https://linux-hardware.org/?probe=41f9931a45) | Apr 07, 2023 |
| HP            | Notebook                    | [a344d6edef](https://linux-hardware.org/?probe=a344d6edef) | Apr 05, 2023 |
| GPD           | G1621-02                    | [7d000ab41b](https://linux-hardware.org/?probe=7d000ab41b) | Mar 31, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [252d340923](https://linux-hardware.org/?probe=252d340923) | Mar 30, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [3173dc99b6](https://linux-hardware.org/?probe=3173dc99b6) | Mar 27, 2023 |
| Lenovo        | G570 20079                  | [8657b8d645](https://linux-hardware.org/?probe=8657b8d645) | Mar 21, 2023 |
| ASUSTek       | X55VDR                      | [b4eb9dbf58](https://linux-hardware.org/?probe=b4eb9dbf58) | Mar 20, 2023 |
| ASUSTek       | N56DP                       | [c49dee996b](https://linux-hardware.org/?probe=c49dee996b) | Mar 19, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [f7727e4bcb](https://linux-hardware.org/?probe=f7727e4bcb) | Mar 17, 2023 |
| HP            | 245 14 inch G9 Notebook ... | [03edff3e6f](https://linux-hardware.org/?probe=03edff3e6f) | Mar 16, 2023 |
| HP            | Laptop 15s-eq3xxx           | [a08a3c36ab](https://linux-hardware.org/?probe=a08a3c36ab) | Feb 28, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [ed67c567d2](https://linux-hardware.org/?probe=ed67c567d2) | Feb 28, 2023 |
| GPD           | G1621-02                    | [5d584fa1cf](https://linux-hardware.org/?probe=5d584fa1cf) | Feb 14, 2023 |
| HP            | Laptop 15s-eq3xxx           | [36dd5f42fc](https://linux-hardware.org/?probe=36dd5f42fc) | Feb 11, 2023 |
| Acer          | Aspire A315-51              | [b644932b49](https://linux-hardware.org/?probe=b644932b49) | Feb 06, 2023 |
| Acer          | Aspire E5-575G              | [30e2a88930](https://linux-hardware.org/?probe=30e2a88930) | Feb 05, 2023 |
| HP            | Laptop 15s-eq3xxx           | [ba7531b9db](https://linux-hardware.org/?probe=ba7531b9db) | Feb 05, 2023 |
| HP            | Laptop 15s-eq3xxx           | [72228118bb](https://linux-hardware.org/?probe=72228118bb) | Feb 05, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [bd19e14a45](https://linux-hardware.org/?probe=bd19e14a45) | Feb 02, 2023 |
| HP            | Laptop 15s-eq3xxx           | [e9525c9a86](https://linux-hardware.org/?probe=e9525c9a86) | Jan 31, 2023 |
| HP            | Laptop 15s-eq3xxx           | [e6cb9d8296](https://linux-hardware.org/?probe=e6cb9d8296) | Jan 31, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [8512c1d0cc](https://linux-hardware.org/?probe=8512c1d0cc) | Jan 31, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [a732875be3](https://linux-hardware.org/?probe=a732875be3) | Jan 29, 2023 |
| ASUSTek       | N56DP                       | [a746d3fd78](https://linux-hardware.org/?probe=a746d3fd78) | Jan 27, 2023 |
| HP            | Laptop 15s-eq3xxx           | [b00e46e17f](https://linux-hardware.org/?probe=b00e46e17f) | Jan 23, 2023 |
| HP            | Laptop 15s-eq3xxx           | [1a9aaa1cb2](https://linux-hardware.org/?probe=1a9aaa1cb2) | Jan 22, 2023 |
| HP            | Laptop 15s-eq3xxx           | [4ed27b0b56](https://linux-hardware.org/?probe=4ed27b0b56) | Jan 22, 2023 |
| HP            | Laptop 15s-eq3xxx           | [0ba680dd8f](https://linux-hardware.org/?probe=0ba680dd8f) | Jan 22, 2023 |
| HP            | Laptop 15s-eq3xxx           | [d2d30c8d6f](https://linux-hardware.org/?probe=d2d30c8d6f) | Jan 21, 2023 |
| HP            | Laptop 15s-eq3xxx           | [07cf342b4f](https://linux-hardware.org/?probe=07cf342b4f) | Jan 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | [78791e5b9e](https://linux-hardware.org/?probe=78791e5b9e) | Jan 20, 2023 |
| Acer          | Swift SF113-31              | [de76cee99a](https://linux-hardware.org/?probe=de76cee99a) | Jan 16, 2023 |
| Lenovo        | IdeaPad Z510 20287          | [71f6d9b711](https://linux-hardware.org/?probe=71f6d9b711) | Jan 12, 2023 |
| Lenovo        | G500 20236                  | [6a873e3df8](https://linux-hardware.org/?probe=6a873e3df8) | Jan 12, 2023 |
| Unknown       | Unknown                     | [cbd401e3c6](https://linux-hardware.org/?probe=cbd401e3c6) | Jan 11, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [70d5242ad0](https://linux-hardware.org/?probe=70d5242ad0) | Jan 01, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [3111141139](https://linux-hardware.org/?probe=3111141139) | Dec 26, 2022 |
| Acer          | Aspire A315-51              | [b53beddded](https://linux-hardware.org/?probe=b53beddded) | Dec 23, 2022 |
| Acer          | Aspire A315-51              | [4fc8630d91](https://linux-hardware.org/?probe=4fc8630d91) | Dec 22, 2022 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [bbc48ee483](https://linux-hardware.org/?probe=bbc48ee483) | Dec 20, 2022 |
| Acer          | Aspire A315-51              | [8777d682b0](https://linux-hardware.org/?probe=8777d682b0) | Dec 20, 2022 |
| Acer          | Aspire A315-51              | [faf7ad4c29](https://linux-hardware.org/?probe=faf7ad4c29) | Dec 19, 2022 |
| Acer          | Aspire A315-51              | [116b321e68](https://linux-hardware.org/?probe=116b321e68) | Dec 16, 2022 |
| Lenovo        | ThinkPad X240 20AL007AMZ    | [8290c7e597](https://linux-hardware.org/?probe=8290c7e597) | Dec 16, 2022 |
| Acer          | Aspire A315-51              | [5f2e420614](https://linux-hardware.org/?probe=5f2e420614) | Dec 15, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [6ae6d710b7](https://linux-hardware.org/?probe=6ae6d710b7) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [b56f450d6d](https://linux-hardware.org/?probe=b56f450d6d) | Dec 10, 2022 |
| Acer          | Aspire A315-51              | [1b1e1ae174](https://linux-hardware.org/?probe=1b1e1ae174) | Dec 08, 2022 |
| Acer          | Aspire A315-51              | [26828f578e](https://linux-hardware.org/?probe=26828f578e) | Dec 05, 2022 |
| Toshiba       | TECRA S11                   | [3d2414e47b](https://linux-hardware.org/?probe=3d2414e47b) | Nov 30, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [ef6247e6fd](https://linux-hardware.org/?probe=ef6247e6fd) | Nov 28, 2022 |
| Dell          | Precision M6400             | [05f69c6917](https://linux-hardware.org/?probe=05f69c6917) | Nov 28, 2022 |
| GPD           | G1621-02                    | [d6b679024c](https://linux-hardware.org/?probe=d6b679024c) | Nov 26, 2022 |
| GPD           | G1621-02                    | [f0e9e8442c](https://linux-hardware.org/?probe=f0e9e8442c) | Nov 26, 2022 |
| Acer          | Aspire A315-51              | [e08bf40900](https://linux-hardware.org/?probe=e08bf40900) | Nov 25, 2022 |
| Acer          | Aspire A315-51              | [a636cfb9ff](https://linux-hardware.org/?probe=a636cfb9ff) | Nov 24, 2022 |
| Acer          | Swift SF314-58G             | [9e729e43a7](https://linux-hardware.org/?probe=9e729e43a7) | Nov 20, 2022 |
| Dell          | Latitude 5520               | [c658158f10](https://linux-hardware.org/?probe=c658158f10) | Nov 15, 2022 |
| Dell          | Latitude 5520               | [6e0490d1bf](https://linux-hardware.org/?probe=6e0490d1bf) | Nov 14, 2022 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [d584008808](https://linux-hardware.org/?probe=d584008808) | Nov 14, 2022 |
| Lenovo        | G500 20236                  | [b156c32896](https://linux-hardware.org/?probe=b156c32896) | Nov 12, 2022 |
| Chuwi         | CoreBook XPro               | [0a0932246f](https://linux-hardware.org/?probe=0a0932246f) | Nov 09, 2022 |
| Acer          | Aspire A315-51              | [d5c179046a](https://linux-hardware.org/?probe=d5c179046a) | Nov 07, 2022 |
| Lenovo        | G500 20236                  | [76d6e74fad](https://linux-hardware.org/?probe=76d6e74fad) | Nov 07, 2022 |
| Acer          | Aspire A315-51              | [eaa9bcaadb](https://linux-hardware.org/?probe=eaa9bcaadb) | Oct 31, 2022 |
| Acer          | Aspire A315-51              | [7b016c85d8](https://linux-hardware.org/?probe=7b016c85d8) | Oct 31, 2022 |
| Acer          | Aspire A315-51              | [17faa0d40a](https://linux-hardware.org/?probe=17faa0d40a) | Oct 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [8b68d25121](https://linux-hardware.org/?probe=8b68d25121) | Oct 26, 2022 |
| Acer          | Aspire A315-51              | [244d93ab06](https://linux-hardware.org/?probe=244d93ab06) | Oct 21, 2022 |
| Acer          | Aspire A315-51              | [dc26121480](https://linux-hardware.org/?probe=dc26121480) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [4c95f64c92](https://linux-hardware.org/?probe=4c95f64c92) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [2740d3c96e](https://linux-hardware.org/?probe=2740d3c96e) | Oct 16, 2022 |
| Lenovo        | ThinkPad X230 23257BG       | [6c8a42718a](https://linux-hardware.org/?probe=6c8a42718a) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [54d1a0ebb2](https://linux-hardware.org/?probe=54d1a0ebb2) | Oct 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [7969631063](https://linux-hardware.org/?probe=7969631063) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [f5e933eaac](https://linux-hardware.org/?probe=f5e933eaac) | Oct 10, 2022 |
| Acer          | Swift SF314-511             | [6270245e93](https://linux-hardware.org/?probe=6270245e93) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [2ac8b7a157](https://linux-hardware.org/?probe=2ac8b7a157) | Oct 03, 2022 |
| ASUSTek       | X550CL                      | [ded047597e](https://linux-hardware.org/?probe=ded047597e) | Sep 28, 2022 |
| Sony          | VGN-FW245J                  | [ab3391f43e](https://linux-hardware.org/?probe=ab3391f43e) | Sep 18, 2022 |
| Chuwi         | UBook XPro                  | [b695b65d86](https://linux-hardware.org/?probe=b695b65d86) | Sep 10, 2022 |
| HP            | ProBook 640 G4              | [b76e5a62e8](https://linux-hardware.org/?probe=b76e5a62e8) | Sep 06, 2022 |
| HONOR         | NBR-WAX9                    | [7e2c842043](https://linux-hardware.org/?probe=7e2c842043) | Aug 25, 2022 |
| Lenovo        | ThinkPad E470 20H1006HRT    | [ff4adb2f7d](https://linux-hardware.org/?probe=ff4adb2f7d) | Jul 20, 2022 |
| Sony          | VPCEA3M1R                   | [0bdfc50874](https://linux-hardware.org/?probe=0bdfc50874) | Jul 16, 2022 |
| HP            | ProBook 645 G3              | [5c37a32531](https://linux-hardware.org/?probe=5c37a32531) | Jul 04, 2022 |
| Acer          | Aspire A315-55KG            | [223d853d4e](https://linux-hardware.org/?probe=223d853d4e) | Jun 29, 2022 |
| HP            | ProBook 430 G4              | [4b4944017c](https://linux-hardware.org/?probe=4b4944017c) | Jun 25, 2022 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [83c0821672](https://linux-hardware.org/?probe=83c0821672) | Jun 25, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [822554f0be](https://linux-hardware.org/?probe=822554f0be) | Jun 23, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [3ddae75872](https://linux-hardware.org/?probe=3ddae75872) | Jun 22, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [47b04cd99f](https://linux-hardware.org/?probe=47b04cd99f) | Jun 21, 2022 |
| Lenovo        | ThinkPad T430 2349NM8       | [44e08ed5c6](https://linux-hardware.org/?probe=44e08ed5c6) | Jun 04, 2022 |
| Dell          | Inspiron 7577               | [3709bf11a9](https://linux-hardware.org/?probe=3709bf11a9) | Jun 01, 2022 |
| Acer          | Aspire 5750G                | [e04f02de57](https://linux-hardware.org/?probe=e04f02de57) | May 23, 2022 |
| Acer          | Aspire 5750G                | [eb1685b47e](https://linux-hardware.org/?probe=eb1685b47e) | May 22, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [a44f38fd50](https://linux-hardware.org/?probe=a44f38fd50) | May 21, 2022 |
| Acer          | Aspire 5750G                | [910cae5e1e](https://linux-hardware.org/?probe=910cae5e1e) | May 21, 2022 |
| IBM           | ThinkPad T43 2668F5G        | [af59841e31](https://linux-hardware.org/?probe=af59841e31) | May 18, 2022 |
| Lenovo        | V14-ADA 82C6                | [5f3fea62ab](https://linux-hardware.org/?probe=5f3fea62ab) | May 16, 2022 |
| Acer          | Aspire 5750G                | [d60d62217c](https://linux-hardware.org/?probe=d60d62217c) | May 10, 2022 |
| Acer          | Aspire 5750G                | [1c49000609](https://linux-hardware.org/?probe=1c49000609) | May 09, 2022 |
| Acer          | Aspire 5750G                | [7e229f1bb3](https://linux-hardware.org/?probe=7e229f1bb3) | May 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [20420f0426](https://linux-hardware.org/?probe=20420f0426) | May 02, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [f0f822fa1b](https://linux-hardware.org/?probe=f0f822fa1b) | Apr 25, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [0324fe4cc6](https://linux-hardware.org/?probe=0324fe4cc6) | Apr 23, 2022 |
| Acer          | Aspire 5750G                | [37a57a968f](https://linux-hardware.org/?probe=37a57a968f) | Apr 19, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [32371c52a6](https://linux-hardware.org/?probe=32371c52a6) | Apr 13, 2022 |
| Dell          | Latitude 3520               | [4398aa2a03](https://linux-hardware.org/?probe=4398aa2a03) | Apr 06, 2022 |
| HP            | ProBook 6570b               | [cf1305eacc](https://linux-hardware.org/?probe=cf1305eacc) | Apr 06, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [d406cb4819](https://linux-hardware.org/?probe=d406cb4819) | Apr 05, 2022 |
| HP            | Pavilion 17                 | [e3071e1f70](https://linux-hardware.org/?probe=e3071e1f70) | Apr 02, 2022 |
| Acer          | Aspire A315-34              | [6f53445c9d](https://linux-hardware.org/?probe=6f53445c9d) | Mar 05, 2022 |
| Acer          | Aspire A315-41G             | [565ef5309f](https://linux-hardware.org/?probe=565ef5309f) | Feb 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [823e19e6d3](https://linux-hardware.org/?probe=823e19e6d3) | Feb 19, 2022 |
| Acer          | Aspire A315-41G             | [21e91da000](https://linux-hardware.org/?probe=21e91da000) | Feb 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ed75c609e4](https://linux-hardware.org/?probe=ed75c609e4) | Feb 16, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [470a550d41](https://linux-hardware.org/?probe=470a550d41) | Feb 16, 2022 |
| Lenovo        | ThinkPad T460 20FMS2TG0D    | [f51933de6d](https://linux-hardware.org/?probe=f51933de6d) | Feb 10, 2022 |
| Lenovo        | ThinkPad T490 20N20009RT    | [538c4fb88c](https://linux-hardware.org/?probe=538c4fb88c) | Jan 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [a6a7106d83](https://linux-hardware.org/?probe=a6a7106d83) | Jan 26, 2022 |
| Samsung       | N100SP                      | [47ec2e67d9](https://linux-hardware.org/?probe=47ec2e67d9) | Jan 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0b4b86fd4d](https://linux-hardware.org/?probe=0b4b86fd4d) | Dec 30, 2021 |
| HP            | Pavilion 15                 | [7248fa574f](https://linux-hardware.org/?probe=7248fa574f) | Dec 20, 2021 |
| Fujitsu       | LIFEBOOK AH531              | [b294d0719f](https://linux-hardware.org/?probe=b294d0719f) | Dec 14, 2021 |
| Dell          | XPS 13 9310                 | [38cf5730b3](https://linux-hardware.org/?probe=38cf5730b3) | Dec 08, 2021 |
| Dell          | XPS 13 9310                 | [4501078e9a](https://linux-hardware.org/?probe=4501078e9a) | Dec 08, 2021 |
| ASUSTek       | K50IE                       | [985ed9e52c](https://linux-hardware.org/?probe=985ed9e52c) | Dec 05, 2021 |
| ASUSTek       | X51RL                       | [0aeee18806](https://linux-hardware.org/?probe=0aeee18806) | Nov 19, 2021 |
| HP            | Pavilion 15                 | [d6caf6dd12](https://linux-hardware.org/?probe=d6caf6dd12) | Nov 17, 2021 |
| HP            | Pavilion 15                 | [581a56e963](https://linux-hardware.org/?probe=581a56e963) | Nov 17, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [924d961707](https://linux-hardware.org/?probe=924d961707) | Nov 12, 2021 |
| HP            | Laptop 17-ca1xxx            | [61fe4e654d](https://linux-hardware.org/?probe=61fe4e654d) | Nov 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [67a9ba5988](https://linux-hardware.org/?probe=67a9ba5988) | Oct 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [9145964032](https://linux-hardware.org/?probe=9145964032) | Oct 30, 2021 |
| ASUSTek       | N56DP                       | [7332da68ec](https://linux-hardware.org/?probe=7332da68ec) | Oct 25, 2021 |
| HP            | Pavilion Sleekbook 15 PC    | [10a67c9e23](https://linux-hardware.org/?probe=10a67c9e23) | Oct 16, 2021 |
| Acer          | Aspire A315-55KG            | [79534f4c8c](https://linux-hardware.org/?probe=79534f4c8c) | Oct 10, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [1103bd0a01](https://linux-hardware.org/?probe=1103bd0a01) | Oct 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [008072f061](https://linux-hardware.org/?probe=008072f061) | Oct 05, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [96463d6903](https://linux-hardware.org/?probe=96463d6903) | Sep 16, 2021 |
| Lenovo        | ThinkPad T480 20L6SBGK00    | [fc6636e0b5](https://linux-hardware.org/?probe=fc6636e0b5) | Sep 09, 2021 |
| HP            | ProBook 4320s               | [94f189cea1](https://linux-hardware.org/?probe=94f189cea1) | Aug 29, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [45ec27282a](https://linux-hardware.org/?probe=45ec27282a) | Aug 23, 2021 |
| HP            | Pavilion dm1                | [ac0e534d86](https://linux-hardware.org/?probe=ac0e534d86) | Aug 01, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [2a645d9cba](https://linux-hardware.org/?probe=2a645d9cba) | Jul 27, 2021 |
| HP            | Laptop 15s-fq2xxx           | [2f259b4ae2](https://linux-hardware.org/?probe=2f259b4ae2) | Jul 26, 2021 |
| HP            | EliteBook 8470p             | [8bfc663f48](https://linux-hardware.org/?probe=8bfc663f48) | Jul 26, 2021 |
| HP            | 635                         | [06f1ff97b5](https://linux-hardware.org/?probe=06f1ff97b5) | Jul 24, 2021 |
| Elenberg      | EL_T1011                    | [c2e05805b1](https://linux-hardware.org/?probe=c2e05805b1) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | [d977beba9e](https://linux-hardware.org/?probe=d977beba9e) | Jul 22, 2021 |
| HP            | 15                          | [fcc367258f](https://linux-hardware.org/?probe=fcc367258f) | Jul 17, 2021 |
| Unknown       | Unknown                     | [b7fe3d0d08](https://linux-hardware.org/?probe=b7fe3d0d08) | Jul 16, 2021 |
| Lenovo        | ThinkPad T580 20L9S0D100    | [e7f9397916](https://linux-hardware.org/?probe=e7f9397916) | Jul 02, 2021 |
| Acer          | Aspire A715-75G             | [1d185733d4](https://linux-hardware.org/?probe=1d185733d4) | Jun 24, 2021 |
| Acer          | Mandolin                    | [c5a4b06851](https://linux-hardware.org/?probe=c5a4b06851) | Jun 13, 2021 |
| ASUSTek       | TUF Gaming FX504GM_FX80G... | [6b37e8a34b](https://linux-hardware.org/?probe=6b37e8a34b) | May 25, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [e74c6f6436](https://linux-hardware.org/?probe=e74c6f6436) | May 16, 2021 |
| Lenovo        | ThinkPad Edge E530 3259C... | [b79dcdb648](https://linux-hardware.org/?probe=b79dcdb648) | May 03, 2021 |
| Lenovo        | ThinkPad Edge E530 3259C... | [b02527f8e5](https://linux-hardware.org/?probe=b02527f8e5) | May 03, 2021 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [1a6e48b6a6](https://linux-hardware.org/?probe=1a6e48b6a6) | Apr 29, 2021 |
| ASUSTek       | GL553VE                     | [b4f123b6df](https://linux-hardware.org/?probe=b4f123b6df) | Apr 20, 2021 |
| Acer          | AO722                       | [6d09f4a364](https://linux-hardware.org/?probe=6d09f4a364) | Apr 20, 2021 |
| ASUSTek       | X550LA                      | [69647941af](https://linux-hardware.org/?probe=69647941af) | Apr 20, 2021 |
| Acer          | AOHAPPY2                    | [1ab9a823ac](https://linux-hardware.org/?probe=1ab9a823ac) | Apr 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [895cfbdea8](https://linux-hardware.org/?probe=895cfbdea8) | Mar 31, 2021 |
| HP            | ENVY m6                     | [1f794c0fc3](https://linux-hardware.org/?probe=1f794c0fc3) | Mar 29, 2021 |
| Dell          | Inspiron 3793               | [324235179d](https://linux-hardware.org/?probe=324235179d) | Mar 19, 2021 |
| ASUSTek       | S301LA                      | [c8c4934145](https://linux-hardware.org/?probe=c8c4934145) | Mar 17, 2021 |
| Acer          | Predator PH317-54           | [0e97801264](https://linux-hardware.org/?probe=0e97801264) | Mar 12, 2021 |
| Acer          | Nitro AN515-44              | [c58e02d129](https://linux-hardware.org/?probe=c58e02d129) | Mar 07, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [9924631e4c](https://linux-hardware.org/?probe=9924631e4c) | Feb 23, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [fb1f894d4f](https://linux-hardware.org/?probe=fb1f894d4f) | Feb 22, 2021 |
| Acer          | Aspire A715-75G             | [4e22c88014](https://linux-hardware.org/?probe=4e22c88014) | Feb 18, 2021 |
| Sony          | VGN-NR430E                  | [62beb0a340](https://linux-hardware.org/?probe=62beb0a340) | Feb 04, 2021 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [e5c078c0d7](https://linux-hardware.org/?probe=e5c078c0d7) | Jan 23, 2021 |
| Acer          | Aspire A315-55KG            | [c62e2ea4ae](https://linux-hardware.org/?probe=c62e2ea4ae) | Jan 22, 2021 |
| Acer          | Aspire V3-551G              | [16932ea052](https://linux-hardware.org/?probe=16932ea052) | Jan 13, 2021 |
| Acer          | Aspire V3-551G              | [b697976568](https://linux-hardware.org/?probe=b697976568) | Jan 13, 2021 |
| Acer          | Extensa 2519                | [bc19a19f7c](https://linux-hardware.org/?probe=bc19a19f7c) | Dec 22, 2020 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [cd5bccf387](https://linux-hardware.org/?probe=cd5bccf387) | Dec 13, 2020 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f6edf147c0](https://linux-hardware.org/?probe=f6edf147c0) | Dec 13, 2020 |
| Acer          | Nitro AN515-52              | [7041c80e3b](https://linux-hardware.org/?probe=7041c80e3b) | Nov 28, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d081baf21f](https://linux-hardware.org/?probe=d081baf21f) | Nov 22, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f149c45438](https://linux-hardware.org/?probe=f149c45438) | Nov 21, 2020 |
| Dell          | G3 3500                     | [d6386ecea5](https://linux-hardware.org/?probe=d6386ecea5) | Nov 07, 2020 |
| Lenovo        | G580 20157                  | [29bf11dd7c](https://linux-hardware.org/?probe=29bf11dd7c) | Nov 03, 2020 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [fec4f6d683](https://linux-hardware.org/?probe=fec4f6d683) | Oct 31, 2020 |
| Acer          | Nitro AN515-52              | [f6e1215c02](https://linux-hardware.org/?probe=f6e1215c02) | Oct 22, 2020 |
| ASUSTek       | U47A                        | [b7c3bb57cf](https://linux-hardware.org/?probe=b7c3bb57cf) | Oct 20, 2020 |
| HP            | Pavilion 17                 | [d016742bce](https://linux-hardware.org/?probe=d016742bce) | Oct 20, 2020 |
| HP            | 250 G3                      | [100536aea2](https://linux-hardware.org/?probe=100536aea2) | Oct 17, 2020 |
| Lenovo        | Y720-15IKB 80VR             | [3ec85a9391](https://linux-hardware.org/?probe=3ec85a9391) | Oct 15, 2020 |
| ASUSTek       | X540SA                      | [1f6a3f87d7](https://linux-hardware.org/?probe=1f6a3f87d7) | Sep 29, 2020 |
| Dell          | Inspiron 3521               | [e9482aee87](https://linux-hardware.org/?probe=e9482aee87) | Sep 28, 2020 |
| HP            | 250 G3                      | [c0207d3878](https://linux-hardware.org/?probe=c0207d3878) | Sep 24, 2020 |
| HP            | 250 G6 Notebook PC          | [71b1302861](https://linux-hardware.org/?probe=71b1302861) | Sep 24, 2020 |
| Dell          | Inspiron 1420               | [4b713d932f](https://linux-hardware.org/?probe=4b713d932f) | Sep 10, 2020 |
| Lenovo        | ThinkPad E580 20KS004GRK    | [0a7dbcc4b4](https://linux-hardware.org/?probe=0a7dbcc4b4) | Sep 09, 2020 |
| HP            | Pavilion 17                 | [994f18c32f](https://linux-hardware.org/?probe=994f18c32f) | Sep 09, 2020 |
| Acer          | Aspire ES1-523              | [e335200dd8](https://linux-hardware.org/?probe=e335200dd8) | Sep 04, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9968af0598](https://linux-hardware.org/?probe=9968af0598) | Aug 25, 2020 |
| ASUSTek       | 1001HA                      | [7935f0bc4a](https://linux-hardware.org/?probe=7935f0bc4a) | Aug 23, 2020 |
| MSI           | Prestige 14 A10SC           | [b6c1db4e4f](https://linux-hardware.org/?probe=b6c1db4e4f) | Aug 23, 2020 |
| MSI           | Prestige 14 A10SC           | [5b434b68bf](https://linux-hardware.org/?probe=5b434b68bf) | Aug 23, 2020 |
| Lenovo        | G580 20157                  | [db44f2aca3](https://linux-hardware.org/?probe=db44f2aca3) | Aug 22, 2020 |
| Packard Be... | EasyNote TE11HC             | [81c427fc6a](https://linux-hardware.org/?probe=81c427fc6a) | Aug 09, 2020 |
| Dell          | Latitude E6440              | [a023894374](https://linux-hardware.org/?probe=a023894374) | Aug 01, 2020 |
| MSI           | Prestige 14 A10SC           | [790a29d708](https://linux-hardware.org/?probe=790a29d708) | Jul 28, 2020 |
| HP            | ProBook 450 G7              | [10566660a8](https://linux-hardware.org/?probe=10566660a8) | Jul 17, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b762726155](https://linux-hardware.org/?probe=b762726155) | Jul 08, 2020 |
| Dell          | Inspiron 5567               | [812155ca3b](https://linux-hardware.org/?probe=812155ca3b) | Jun 29, 2020 |
| Acer          | Aspire A315-51              | [61c053a60a](https://linux-hardware.org/?probe=61c053a60a) | May 31, 2020 |
| Acer          | Aspire A315-51              | [b524806f7a](https://linux-hardware.org/?probe=b524806f7a) | May 31, 2020 |
| Acer          | Aspire A315-51              | [1509883885](https://linux-hardware.org/?probe=1509883885) | May 31, 2020 |
| Acer          | Aspire A315-51              | [5d042bc26a](https://linux-hardware.org/?probe=5d042bc26a) | May 31, 2020 |
| Acer          | Aspire A315-51              | [5c70b2f02d](https://linux-hardware.org/?probe=5c70b2f02d) | May 31, 2020 |
| Dell          | Inspiron N5110              | [d2c4164b1c](https://linux-hardware.org/?probe=d2c4164b1c) | May 24, 2020 |
| HP            | Pavilion g6                 | [470074b671](https://linux-hardware.org/?probe=470074b671) | May 14, 2020 |
| Acer          | TravelMate 5742G            | [3b5409d855](https://linux-hardware.org/?probe=3b5409d855) | May 08, 2020 |
| HP            | Pavilion g6                 | [c2f0ff23ad](https://linux-hardware.org/?probe=c2f0ff23ad) | May 02, 2020 |
| ASUSTek       | U47A                        | [3b85d1aeb4](https://linux-hardware.org/?probe=3b85d1aeb4) | Apr 20, 2020 |
| HP            | Compaq 6510b (GB867EA#AC... | [ebb74b0be7](https://linux-hardware.org/?probe=ebb74b0be7) | Apr 06, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [b44935169f](https://linux-hardware.org/?probe=b44935169f) | Mar 31, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | [57ade58668](https://linux-hardware.org/?probe=57ade58668) | Mar 22, 2020 |
| Lenovo        | V330-14IKB 81B0             | [7ad6b7b58b](https://linux-hardware.org/?probe=7ad6b7b58b) | Mar 22, 2020 |
| HP            | Laptop 15-da0xxx            | [d2ab3b608a](https://linux-hardware.org/?probe=d2ab3b608a) | Mar 07, 2020 |
| HP            | Laptop 15-bs0xx             | [c219a39d00](https://linux-hardware.org/?probe=c219a39d00) | Mar 05, 2020 |
| HP            | Laptop 15-bs0xx             | [6f409ce91c](https://linux-hardware.org/?probe=6f409ce91c) | Mar 05, 2020 |
| Dell          | Inspiron 5770               | [fd882c0a0a](https://linux-hardware.org/?probe=fd882c0a0a) | Mar 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [dc2a796221](https://linux-hardware.org/?probe=dc2a796221) | Mar 01, 2020 |
| HP            | Presario CQ57               | [3de9f386b3](https://linux-hardware.org/?probe=3de9f386b3) | Feb 19, 2020 |
| Acer          | Aspire V5-572P              | [e87893d9ae](https://linux-hardware.org/?probe=e87893d9ae) | Feb 17, 2020 |
| HP            | ProBook 430 G5              | [1a22c7e1bd](https://linux-hardware.org/?probe=1a22c7e1bd) | Feb 16, 2020 |
| HP            | Presario CQ57               | [e89b7e8846](https://linux-hardware.org/?probe=e89b7e8846) | Feb 14, 2020 |
| Acer          | Aspire XXXX                 | [ce7f974b21](https://linux-hardware.org/?probe=ce7f974b21) | Feb 11, 2020 |
| Packard Be... | EasyNote TE11HC             | [fc9249082d](https://linux-hardware.org/?probe=fc9249082d) | Feb 08, 2020 |
| HP            | Laptop 15-bw0xx             | [52e1f3b9aa](https://linux-hardware.org/?probe=52e1f3b9aa) | Feb 07, 2020 |
| HP            | Compaq nx6310 (EY512ES#A... | [7131bc7839](https://linux-hardware.org/?probe=7131bc7839) | Jan 29, 2020 |
| Fujitsu       | LIFEBOOK AH531              | [d48f36b5c1](https://linux-hardware.org/?probe=d48f36b5c1) | Jan 28, 2020 |
| HP            | Mini 110-3500               | [70d6715873](https://linux-hardware.org/?probe=70d6715873) | Jan 28, 2020 |
| HP            | Compaq nx6310 (EY512ES#A... | [5aa6704ff1](https://linux-hardware.org/?probe=5aa6704ff1) | Jan 16, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [76fd2a40e6](https://linux-hardware.org/?probe=76fd2a40e6) | Jan 10, 2020 |
| ASUSTek       | G46VW                       | [17b6106770](https://linux-hardware.org/?probe=17b6106770) | Dec 27, 2019 |
| ASUSTek       | G46VW                       | [d589eb2b88](https://linux-hardware.org/?probe=d589eb2b88) | Dec 27, 2019 |
| Dell          | Inspiron 3521               | [a0554a7e66](https://linux-hardware.org/?probe=a0554a7e66) | Dec 25, 2019 |
| HP            | Pavilion g6                 | [2b1a415af5](https://linux-hardware.org/?probe=2b1a415af5) | Dec 12, 2019 |
| Lenovo        | V580c 20160                 | [a90c5bff19](https://linux-hardware.org/?probe=a90c5bff19) | Dec 11, 2019 |
| Acer          | Aspire A517-51G             | [73dafbb15e](https://linux-hardware.org/?probe=73dafbb15e) | Nov 25, 2019 |
| Acer          | Aspire A517-51G             | [73d25e486f](https://linux-hardware.org/?probe=73d25e486f) | Nov 25, 2019 |
| Lenovo        | G505s 20255                 | [f50938f6b5](https://linux-hardware.org/?probe=f50938f6b5) | Nov 24, 2019 |
| Dell          | Latitude 7280               | [d18e59c26a](https://linux-hardware.org/?probe=d18e59c26a) | Nov 23, 2019 |
| Dell          | Latitude 7280               | [53190bc040](https://linux-hardware.org/?probe=53190bc040) | Nov 23, 2019 |
| Lenovo        | G505s 20255                 | [d93b73ac97](https://linux-hardware.org/?probe=d93b73ac97) | Nov 22, 2019 |
| Acer          | TravelMate 7750G            | [51f6c04c3c](https://linux-hardware.org/?probe=51f6c04c3c) | Oct 30, 2019 |
| Sony          | VPCEH2M1R                   | [7f2ba2a282](https://linux-hardware.org/?probe=7f2ba2a282) | Oct 22, 2019 |
| HP            | Presario CQ57               | [fee13f8ed2](https://linux-hardware.org/?probe=fee13f8ed2) | Oct 08, 2019 |
| Fujitsu       | LIFEBOOK AH531              | [0aea361308](https://linux-hardware.org/?probe=0aea361308) | Sep 09, 2019 |
| Fujitsu       | LIFEBOOK AH531              | [65b6a535e2](https://linux-hardware.org/?probe=65b6a535e2) | Sep 09, 2019 |
| ASUSTek       | X540SA                      | [90108d8974](https://linux-hardware.org/?probe=90108d8974) | Sep 08, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [60161c7891](https://linux-hardware.org/?probe=60161c7891) | Aug 28, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [e79b69efe5](https://linux-hardware.org/?probe=e79b69efe5) | Aug 20, 2019 |
| ASUSTek       | X541SC                      | [6458c4f07b](https://linux-hardware.org/?probe=6458c4f07b) | Jul 22, 2019 |
| HP            | Compaq nc6320 (ES479EA#A... | [cf41ab5f1a](https://linux-hardware.org/?probe=cf41ab5f1a) | Jul 15, 2019 |
| Acer          | Aspire E5-575G              | [e4b342382f](https://linux-hardware.org/?probe=e4b342382f) | Jul 06, 2019 |
| Lenovo        | G500 20236                  | [166081ce08](https://linux-hardware.org/?probe=166081ce08) | Jul 04, 2019 |
| Acer          | Aspire E5-575G              | [0446579039](https://linux-hardware.org/?probe=0446579039) | Jun 26, 2019 |
| Dell          | Inspiron 3521               | [03073baad2](https://linux-hardware.org/?probe=03073baad2) | Jun 21, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [13304c8b21](https://linux-hardware.org/?probe=13304c8b21) | Jun 20, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [78913150c4](https://linux-hardware.org/?probe=78913150c4) | Jun 20, 2019 |
| ASUSTek       | X541SC                      | [021030c4a5](https://linux-hardware.org/?probe=021030c4a5) | May 26, 2019 |
| HP            | Pavilion dv6                | [7a702bbcca](https://linux-hardware.org/?probe=7a702bbcca) | May 18, 2019 |
| Acer          | Aspire E5-575G              | [933bd023a3](https://linux-hardware.org/?probe=933bd023a3) | May 07, 2019 |
| ASUSTek       | X550CA                      | [bee231aa07](https://linux-hardware.org/?probe=bee231aa07) | May 07, 2019 |
| Lenovo        | G500 20236                  | [780fb49d18](https://linux-hardware.org/?probe=780fb49d18) | May 04, 2019 |
| ASUSTek       | X102BA                      | [a7f7276e3d](https://linux-hardware.org/?probe=a7f7276e3d) | May 02, 2019 |
| Dell          | Inspiron 3521               | [d8da30496e](https://linux-hardware.org/?probe=d8da30496e) | May 01, 2019 |
| Dell          | Inspiron 3521               | [4030941deb](https://linux-hardware.org/?probe=4030941deb) | Apr 29, 2019 |
| ASUSTek       | X751LN                      | [9cf06d20fa](https://linux-hardware.org/?probe=9cf06d20fa) | Apr 24, 2019 |
| ASUSTek       | X541SC                      | [0837a78e1f](https://linux-hardware.org/?probe=0837a78e1f) | Apr 24, 2019 |
| Dell          | Inspiron 3521               | [5c7abc670f](https://linux-hardware.org/?probe=5c7abc670f) | Apr 22, 2019 |
| ASUSTek       | X751LN                      | [5ca452f41e](https://linux-hardware.org/?probe=5ca452f41e) | Apr 22, 2019 |
| HP            | ProBook 470 G4              | [5e83946400](https://linux-hardware.org/?probe=5e83946400) | Apr 12, 2019 |
| Fujitsu Si... | AMILO Li 1818               | [9a3017958a](https://linux-hardware.org/?probe=9a3017958a) | Apr 03, 2019 |
| Toshiba       | Satellite P105              | [fed8975477](https://linux-hardware.org/?probe=fed8975477) | Mar 04, 2019 |
| Lenovo        | IdeaPad Z500 20202          | [f100f0f205](https://linux-hardware.org/?probe=f100f0f205) | Feb 24, 2019 |
| Toshiba       | Satellite C660              | [6badaf723c](https://linux-hardware.org/?probe=6badaf723c) | Jan 20, 2019 |
| Toshiba       | Satellite C660              | [aa10ea857e](https://linux-hardware.org/?probe=aa10ea857e) | Jan 15, 2019 |
| ASUSTek       | K50IE                       | [82bb70f126](https://linux-hardware.org/?probe=82bb70f126) | Jan 02, 2019 |
| HP            | Pavilion g6                 | [dfee480fdd](https://linux-hardware.org/?probe=dfee480fdd) | Jan 01, 2019 |
| HP            | Pavilion g6                 | [00e7757462](https://linux-hardware.org/?probe=00e7757462) | Jan 01, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [88c4e3862d](https://linux-hardware.org/?probe=88c4e3862d) | Dec 27, 2018 |
| Acer          | Aspire E5-575G              | [7d028bb762](https://linux-hardware.org/?probe=7d028bb762) | Dec 25, 2018 |
| Acer          | Aspire E5-575G              | [14806ac400](https://linux-hardware.org/?probe=14806ac400) | Dec 14, 2018 |
| Packard Be... | DOT S                       | [a0fe87d229](https://linux-hardware.org/?probe=a0fe87d229) | Nov 24, 2018 |
| Packard Be... | DOT S                       | [6267c7c58d](https://linux-hardware.org/?probe=6267c7c58d) | Nov 24, 2018 |
| ASUSTek       | X540SA                      | [9f31b05c88](https://linux-hardware.org/?probe=9f31b05c88) | Nov 23, 2018 |
| Lenovo        | Yoga 300-11IBR 80M1         | [d07d21914f](https://linux-hardware.org/?probe=d07d21914f) | Oct 27, 2018 |
| ASUSTek       | U47A                        | [0d064a18d0](https://linux-hardware.org/?probe=0d064a18d0) | Oct 24, 2018 |
| ASUSTek       | U47A                        | [5171edd107](https://linux-hardware.org/?probe=5171edd107) | Oct 24, 2018 |
| HP            | EliteBook 6930p             | [3a9c8124dd](https://linux-hardware.org/?probe=3a9c8124dd) | Oct 23, 2018 |
| HP            | EliteBook 8530p             | [51ba7cee66](https://linux-hardware.org/?probe=51ba7cee66) | Oct 17, 2018 |
| HP            | Pavilion g6                 | [ffb346f134](https://linux-hardware.org/?probe=ffb346f134) | Sep 24, 2018 |
| HP            | Pavilion dv6                | [884d5eb5ec](https://linux-hardware.org/?probe=884d5eb5ec) | Sep 16, 2018 |
| HP            | Pavilion dv6                | [622662ba7d](https://linux-hardware.org/?probe=622662ba7d) | Sep 14, 2018 |
| Unknown       | Unknown                     | [f45f9ee7ff](https://linux-hardware.org/?probe=f45f9ee7ff) | Sep 05, 2018 |
| Unknown       | Unknown                     | [07345cdc85](https://linux-hardware.org/?probe=07345cdc85) | Aug 29, 2018 |
| Lenovo        | B50-70 20384                | [b89c577552](https://linux-hardware.org/?probe=b89c577552) | Aug 26, 2018 |
| HP            | ProBook 450 G5              | [8252f20153](https://linux-hardware.org/?probe=8252f20153) | Aug 18, 2018 |
| Dell          | Inspiron 3520               | [84a1a01ff9](https://linux-hardware.org/?probe=84a1a01ff9) | Aug 12, 2018 |
| Lenovo        | G580 20157                  | [b70545cbac](https://linux-hardware.org/?probe=b70545cbac) | Aug 02, 2018 |
| Toshiba       | Portable PC                 | [3f35fe94d9](https://linux-hardware.org/?probe=3f35fe94d9) | Jul 30, 2018 |
| Lenovo        | G510 20238                  | [71278987a9](https://linux-hardware.org/?probe=71278987a9) | Jul 20, 2018 |
| HP            | Compaq CQ58                 | [19369b35ae](https://linux-hardware.org/?probe=19369b35ae) | Jul 20, 2018 |
| Lenovo        | Y50-70 20378                | [62a23cd320](https://linux-hardware.org/?probe=62a23cd320) | Jul 11, 2018 |
| HP            | Compaq CQ58                 | [99fa20eba0](https://linux-hardware.org/?probe=99fa20eba0) | Jun 21, 2018 |
| Lenovo        | G580 20157                  | [a202b59883](https://linux-hardware.org/?probe=a202b59883) | Jun 19, 2018 |
| HP            | Compaq CQ58                 | [cb1791cebb](https://linux-hardware.org/?probe=cb1791cebb) | Jun 16, 2018 |
| Sony          | VPCEB1E1R                   | [a75927fc48](https://linux-hardware.org/?probe=a75927fc48) | Jun 03, 2018 |
| Sony          | VPCEB1E1R                   | [37813189cc](https://linux-hardware.org/?probe=37813189cc) | Jun 02, 2018 |
| Sony          | VPCEB1E1R                   | [408dcf71ce](https://linux-hardware.org/?probe=408dcf71ce) | May 25, 2018 |
| Lenovo        | B50-70 20384                | [c35dc55ced](https://linux-hardware.org/?probe=c35dc55ced) | May 22, 2018 |
| Samsung       | R518                        | [0e9bb77f12](https://linux-hardware.org/?probe=0e9bb77f12) | May 17, 2018 |
| Acer          | TravelMate 7750G            | [0d5442243c](https://linux-hardware.org/?probe=0d5442243c) | Apr 13, 2018 |
| HP            | EliteBook 2560p             | [2674660d30](https://linux-hardware.org/?probe=2674660d30) | Mar 18, 2018 |
| Acer          | Predator G3-572             | [c888fc259c](https://linux-hardware.org/?probe=c888fc259c) | Feb 28, 2018 |
| Acer          | Aspire E1-571G              | [ff7067b051](https://linux-hardware.org/?probe=ff7067b051) | Feb 24, 2018 |
| ASUSTek       | X550LA                      | [f416c6d195](https://linux-hardware.org/?probe=f416c6d195) | Feb 11, 2018 |
| Lenovo        | IdeaPad Y580                | [e648c1db32](https://linux-hardware.org/?probe=e648c1db32) | Feb 10, 2018 |
| Sony          | VGN-NW320F                  | [5b4a5cecc3](https://linux-hardware.org/?probe=5b4a5cecc3) | Jan 24, 2018 |
| Sony          | VGN-NW320F                  | [8d00903b16](https://linux-hardware.org/?probe=8d00903b16) | Jan 24, 2018 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [d9f6c2c974](https://linux-hardware.org/?probe=d9f6c2c974) | Jan 21, 2018 |
| HP            | EliteBook 8440p             | [0358601780](https://linux-hardware.org/?probe=0358601780) | Jan 18, 2018 |
| Lenovo        | V580c 20160                 | [4bc6c74b55](https://linux-hardware.org/?probe=4bc6c74b55) | Jan 13, 2018 |
| Acer          | Aspire E1-571G              | [b60cd6ffc3](https://linux-hardware.org/?probe=b60cd6ffc3) | Jan 12, 2018 |
| Dell          | Inspiron M5110              | [bbf43310e5](https://linux-hardware.org/?probe=bbf43310e5) | Jan 05, 2018 |
| Lenovo        | G510 20238                  | [e84d800dfe](https://linux-hardware.org/?probe=e84d800dfe) | Jan 03, 2018 |
| Lenovo        | G510 20238                  | [b322595c10](https://linux-hardware.org/?probe=b322595c10) | Jan 03, 2018 |
| Lenovo        | B590 20208                  | [519ce95e23](https://linux-hardware.org/?probe=519ce95e23) | Dec 27, 2017 |
| ASUSTek       | K52Jc                       | [ae0972b81d](https://linux-hardware.org/?probe=ae0972b81d) | Dec 27, 2017 |
| Lenovo        | V580c 20160                 | [973d383d71](https://linux-hardware.org/?probe=973d383d71) | Dec 27, 2017 |
| ASUSTek       | K52Jc                       | [ee5e52dede](https://linux-hardware.org/?probe=ee5e52dede) | Dec 26, 2017 |
| Dell          | Inspiron N5110              | [2045f82e75](https://linux-hardware.org/?probe=2045f82e75) | Dec 24, 2017 |
| Lenovo        | V580c 20160                 | [8b68d694a7](https://linux-hardware.org/?probe=8b68d694a7) | Dec 21, 2017 |
| HP            | ProBook 4720s               | [ab0b647716](https://linux-hardware.org/?probe=ab0b647716) | Dec 09, 2017 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [f2eec3b185](https://linux-hardware.org/?probe=f2eec3b185) | Dec 03, 2017 |
| ASUSTek       | X51RL                       | [701211da24](https://linux-hardware.org/?probe=701211da24) | Dec 02, 2017 |
| Dell          | Inspiron M5110              | [ee88f09ebb](https://linux-hardware.org/?probe=ee88f09ebb) | Nov 30, 2017 |
| Acer          | Aspire 5750G                | [9d18d205df](https://linux-hardware.org/?probe=9d18d205df) | Nov 11, 2017 |
| ASUSTek       | X58L                        | [de2da19087](https://linux-hardware.org/?probe=de2da19087) | Oct 20, 2017 |
| ASUSTek       | K55VD                       | [295b4e18de](https://linux-hardware.org/?probe=295b4e18de) | Sep 24, 2017 |
| Dell          | Inspiron N5050              | [072cf329f6](https://linux-hardware.org/?probe=072cf329f6) | Sep 22, 2017 |
| HP            | Pavilion 17                 | [5226a4b68c](https://linux-hardware.org/?probe=5226a4b68c) | Sep 12, 2017 |
| Dell          | Inspiron 3558               | [a10105f81f](https://linux-hardware.org/?probe=a10105f81f) | Sep 12, 2017 |
| ASUSTek       | K52JV                       | [786ab76c2d](https://linux-hardware.org/?probe=786ab76c2d) | Aug 09, 2017 |
| Sony          | VPCCB2S1R                   | [b5723ad5f5](https://linux-hardware.org/?probe=b5723ad5f5) | Aug 08, 2017 |
| Lenovo        | G580 20157                  | [a1a09287ab](https://linux-hardware.org/?probe=a1a09287ab) | Aug 06, 2017 |
| Lenovo        | IdeaPad Y580                | [258ed6aea6](https://linux-hardware.org/?probe=258ed6aea6) | Jul 27, 2017 |
| Lenovo        | IdeaPad Y580                | [493ba2eb0c](https://linux-hardware.org/?probe=493ba2eb0c) | Jul 27, 2017 |
| Lenovo        | G510 20238                  | [2613154d7e](https://linux-hardware.org/?probe=2613154d7e) | Jul 24, 2017 |
| eMachines     | E725                        | [05bce34fc0](https://linux-hardware.org/?probe=05bce34fc0) | Jul 23, 2017 |
| Acer          | Aspire V3-551G              | [92da3895dc](https://linux-hardware.org/?probe=92da3895dc) | Jul 18, 2017 |
| Dell          | Inspiron 5559               | [3753d1a422](https://linux-hardware.org/?probe=3753d1a422) | Jul 18, 2017 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [a62f8e0f39](https://linux-hardware.org/?probe=a62f8e0f39) | Jul 15, 2017 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [0a1ff9ae9c](https://linux-hardware.org/?probe=0a1ff9ae9c) | Jul 14, 2017 |
| Dell          | Inspiron 5759               | [40852e37a5](https://linux-hardware.org/?probe=40852e37a5) | Jul 12, 2017 |
| HP            | Pavilion dm3                | [008097ceb1](https://linux-hardware.org/?probe=008097ceb1) | May 30, 2017 |
| Dell          | Inspiron 3558               | [c7a96bfff1](https://linux-hardware.org/?probe=c7a96bfff1) | May 28, 2017 |
| Dell          | Inspiron 3558               | [11b4a60b6b](https://linux-hardware.org/?probe=11b4a60b6b) | May 28, 2017 |
| Lenovo        | G500 20236                  | [60a1eab059](https://linux-hardware.org/?probe=60a1eab059) | May 26, 2017 |
| HP            | Compaq 6710b (KE120EA#AC... | [278110b61f](https://linux-hardware.org/?probe=278110b61f) | May 22, 2017 |
| Fujitsu Si... | AMILO Pi 3540               | [e8829d83b4](https://linux-hardware.org/?probe=e8829d83b4) | May 05, 2017 |
| Fujitsu Si... | AMILO Pi 3540               | [dd2f72474b](https://linux-hardware.org/?probe=dd2f72474b) | May 02, 2017 |
| Acer          | Aspire E5-511G              | [0110e34364](https://linux-hardware.org/?probe=0110e34364) | May 01, 2017 |
| HP            | ENVY TS 17                  | [74e650e784](https://linux-hardware.org/?probe=74e650e784) | Apr 30, 2017 |
| Unknown       | Unknown                     | [f5351462b1](https://linux-hardware.org/?probe=f5351462b1) | Apr 28, 2017 |
| Dell          | Inspiron 5521               | [92a991bcec](https://linux-hardware.org/?probe=92a991bcec) | Apr 17, 2017 |
| Dell          | Inspiron 5521               | [534d340a7a](https://linux-hardware.org/?probe=534d340a7a) | Apr 17, 2017 |
| Dell          | Inspiron 5521               | [add5384359](https://linux-hardware.org/?probe=add5384359) | Apr 16, 2017 |
| Dell          | Inspiron M5110              | [331bda6305](https://linux-hardware.org/?probe=331bda6305) | Apr 01, 2017 |
| Dell          | Inspiron M5110              | [6d2fc341c7](https://linux-hardware.org/?probe=6d2fc341c7) | Apr 01, 2017 |
| ASUSTek       | N56DP                       | [c4a63674e5](https://linux-hardware.org/?probe=c4a63674e5) | Feb 18, 2017 |
| Fujitsu       | LIFEBOOK A530               | [a03d8130fe](https://linux-hardware.org/?probe=a03d8130fe) | Feb 06, 2017 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [c288b514d5](https://linux-hardware.org/?probe=c288b514d5) | Jan 22, 2017 |
| ASUSTek       | N53SM                       | [26849207d6](https://linux-hardware.org/?probe=26849207d6) | Jan 19, 2017 |
| Dell          | Inspiron 7720               | [7dff83e247](https://linux-hardware.org/?probe=7dff83e247) | Jan 04, 2017 |
| Lenovo        | ThinkPad Edge E530 3259C... | [58cb3c3ef1](https://linux-hardware.org/?probe=58cb3c3ef1) | Dec 23, 2016 |
| Lenovo        | ThinkPad Edge E530 3259C... | [8af0bb111e](https://linux-hardware.org/?probe=8af0bb111e) | Dec 20, 2016 |
| Lenovo        | G565 20071                  | [e6972d050f](https://linux-hardware.org/?probe=e6972d050f) | Dec 16, 2016 |
| Toshiba       | TECRA M5                    | [b4743ce437](https://linux-hardware.org/?probe=b4743ce437) | Dec 12, 2016 |
| Packard Be... | DOT S                       | [815f65352b](https://linux-hardware.org/?probe=815f65352b) | Dec 01, 2016 |
| Toshiba       | Satellite C650              | [06c50a161c](https://linux-hardware.org/?probe=06c50a161c) | Nov 29, 2016 |
| ASUSTek       | 1225C                       | [57787e36c2](https://linux-hardware.org/?probe=57787e36c2) | Nov 28, 2016 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [1ed00b7813](https://linux-hardware.org/?probe=1ed00b7813) | Nov 27, 2016 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [45b5c7374e](https://linux-hardware.org/?probe=45b5c7374e) | Nov 27, 2016 |
| Lenovo        | ThinkPad X201 3626MJ5       | [e13b0d2ee7](https://linux-hardware.org/?probe=e13b0d2ee7) | Nov 25, 2016 |
| HP            | 530                         | [b4ade385fd](https://linux-hardware.org/?probe=b4ade385fd) | Nov 24, 2016 |
| Toshiba       | Satellite 5200              | [a79789524b](https://linux-hardware.org/?probe=a79789524b) | Nov 02, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Kazakhstan/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| ROSA R11                     | 27        | 7.01%   |
| ROSA R8.1                    | 25        | 6.49%   |
| ROSA R10                     | 25        | 6.49%   |
| Ubuntu 22.04                 | 19        | 4.94%   |
| ROSA R9                      | 16        | 4.16%   |
| Ubuntu 20.04                 | 15        | 3.9%    |
| Arch Rolling                 | 15        | 3.9%    |
| ROSA R8                      | 14        | 3.64%   |
| ROSA 12.4                    | 10        | 2.6%    |
| KDE neon 20.04               | 9         | 2.34%   |
| Ubuntu 18.04                 | 8         | 2.08%   |
| ROSA R11.1                   | 8         | 2.08%   |
| Debian 11                    | 8         | 2.08%   |
| Ubuntu 24.04                 | 5         | 1.3%    |
| Pop!_OS 22.04                | 5         | 1.3%    |
| OpenMandriva 4.2             | 5         | 1.3%    |
| Ubuntu 23.10                 | 4         | 1.04%   |
| KDE neon 22.04               | 4         | 1.04%   |
| Fedora 39                    | 4         | 1.04%   |
| Fedora 38                    | 4         | 1.04%   |
| EndeavourOS Rolling          | 4         | 1.04%   |
| Debian 12                    | 4         | 1.04%   |
| Ubuntu 23.04                 | 3         | 0.78%   |
| Slackware 15.0               | 3         | 0.78%   |
| ROSA 12.3                    | 3         | 0.78%   |
| ROSA 12.2                    | 3         | 0.78%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.78%   |
| OpenMandriva 24.07           | 3         | 0.78%   |
| Manjaro                      | 3         | 0.78%   |
| Fedora 37                    | 3         | 0.78%   |
| Fedora 36                    | 3         | 0.78%   |
| Arch                         | 3         | 0.78%   |
| Ubuntu 22.10                 | 2         | 0.52%   |
| Ubuntu 18.10                 | 2         | 0.52%   |
| SteamOS 3.5.7                | 2         | 0.52%   |
| OpenMandriva 23.03           | 2         | 0.52%   |
| OpenMandriva 23.01           | 2         | 0.52%   |
| Manjaro 22.0.0               | 2         | 0.52%   |
| Linux Mint 21.3              | 2         | 0.52%   |
| Linux Mint 21.2              | 2         | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| ROSA         | 121       | 33.06%  |
| Ubuntu       | 58        | 15.85%  |
| Fedora       | 20        | 5.46%   |
| Endless      | 18        | 4.92%   |
| Arch         | 17        | 4.64%   |
| OpenMandriva | 15        | 4.1%    |
| KDE neon     | 15        | 4.1%    |
| Debian       | 14        | 3.83%   |
| Manjaro      | 13        | 3.55%   |
| Linux Mint   | 11        | 3.01%   |
| Kubuntu      | 9         | 2.46%   |
| Pop!_OS      | 8         | 2.19%   |
| openSUSE     | 4         | 1.09%   |
| EndeavourOS  | 4         | 1.09%   |
| Elementary   | 4         | 1.09%   |
| SteamOS      | 3         | 0.82%   |
| Slackware    | 3         | 0.82%   |
| CentOS       | 3         | 0.82%   |
| Zorin        | 2         | 0.55%   |
| Ubuntu Unity | 2         | 0.55%   |
| Nobara       | 2         | 0.55%   |
| ArcoLinux    | 2         | 0.55%   |
| Xubuntu      | 1         | 0.27%   |
| Ubuntu MATE  | 1         | 0.27%   |
| Trisquel     | 1         | 0.27%   |
| Rocky Linux  | 1         | 0.27%   |
| Peppermint   | 1         | 0.27%   |
| Parrot       | 1         | 0.27%   |
| NixOS        | 1         | 0.27%   |
| MX           | 1         | 0.27%   |
| Lunaos       | 1         | 0.27%   |
| Lubuntu      | 1         | 0.27%   |
| LMDE         | 1         | 0.27%   |
| Kali         | 1         | 0.27%   |
| Gentoo       | 1         | 0.27%   |
| Finnix       | 1         | 0.27%   |
| Ctlos        | 1         | 0.27%   |
| Clear Linux  | 1         | 0.27%   |
| antiX        | 1         | 0.27%   |
| ALT Linux    | 1         | 0.27%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                           | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| 4.15.0-desktop-45.1rosa-x86_64    | 17        | 4.12%   |
| 4.9.60-nrj-desktop-1rosa-x86_64   | 16        | 3.87%   |
| 4.9.20-nrj-desktop-1rosa-x86_64   | 14        | 3.39%   |
| 4.1.34-nrj-desktop-2rosa-x86_64   | 7         | 1.69%   |
| 4.9.124-nrj-desktop-1rosa-x86_64  | 6         | 1.45%   |
| 5.10.14-desktop-1omv4002          | 5         | 1.21%   |
| 4.9.9-nrj-desktop-1rosa-x86_64    | 5         | 1.21%   |
| 4.1.38-nrj-desktop-2rosa-x86_64   | 5         | 1.21%   |
| 4.1.34-nrj-desktop-2rosa-i586     | 5         | 1.21%   |
| 6.1.20-generic-2rosa2021.1-x86_64 | 4         | 0.97%   |
| 5.10.0-8-amd64                    | 4         | 0.97%   |
| 4.9.95-nrj-desktop-2rosa-x86_64   | 4         | 0.97%   |
| 4.9.41-nrj-desktop-1rosa-x86_64   | 4         | 0.97%   |
| 4.9.20-nrj-desktop-1rosa-i586     | 4         | 0.97%   |
| 4.9.155-nrj-desktop-1rosa-x86_64  | 4         | 0.97%   |
| 6.8.0-49-generic                  | 3         | 0.73%   |
| 6.8.0-40-generic                  | 3         | 0.73%   |
| 6.2.0-39-generic                  | 3         | 0.73%   |
| 5.4.83-generic-2rosa-x86_64       | 3         | 0.73%   |
| 5.11.0-35-generic                 | 3         | 0.73%   |
| 4.9.111-nrj-desktop-2rosa-x86_64  | 3         | 0.73%   |
| 4.15.0-desktop-47.2rosa-x86_64    | 3         | 0.73%   |
| 6.8.0-45-generic                  | 2         | 0.48%   |
| 6.5.6-76060506-generic            | 2         | 0.48%   |
| 6.5.0-26-generic                  | 2         | 0.48%   |
| 6.4.6-76060406-generic            | 2         | 0.48%   |
| 6.4.11-desktop-1omv2390           | 2         | 0.48%   |
| 6.2.6-desktop-1omv2390            | 2         | 0.48%   |
| 6.2.0-34-generic                  | 2         | 0.48%   |
| 6.2.0-26-generic                  | 2         | 0.48%   |
| 6.10.0-desktop-1omv2490           | 2         | 0.48%   |
| 6.1.58-generic-1rosa2021.1-x86_64 | 2         | 0.48%   |
| 6.1.46-generic-2rosa2021.1-x86_64 | 2         | 0.48%   |
| 6.1.1-desktop-1omv2290            | 2         | 0.48%   |
| 6.1.0-13-amd64                    | 2         | 0.48%   |
| 5.8.0-44-generic                  | 2         | 0.48%   |
| 5.8.0-14-generic                  | 2         | 0.48%   |
| 5.4.32-generic-2rosa-x86_64       | 2         | 0.48%   |
| 5.4.0-42-generic                  | 2         | 0.48%   |
| 5.4.0-39-generic                  | 2         | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.15.0  | 29        | 7.06%   |
| 5.4.0   | 19        | 4.62%   |
| 4.9.20  | 18        | 4.38%   |
| 5.15.0  | 17        | 4.14%   |
| 4.9.60  | 17        | 4.14%   |
| 4.1.34  | 12        | 2.92%   |
| 5.11.0  | 11        | 2.68%   |
| 6.2.0   | 10        | 2.43%   |
| 6.8.0   | 9         | 2.19%   |
| 6.5.0   | 9         | 2.19%   |
| 5.10.0  | 9         | 2.19%   |
| 6.1.0   | 8         | 1.95%   |
| 5.3.0   | 7         | 1.7%    |
| 5.19.0  | 7         | 1.7%    |
| 5.0.0   | 7         | 1.7%    |
| 4.9.9   | 7         | 1.7%    |
| 4.9.124 | 6         | 1.46%   |
| 4.1.38  | 6         | 1.46%   |
| 5.8.0   | 5         | 1.22%   |
| 5.10.14 | 5         | 1.22%   |
| 4.9.155 | 5         | 1.22%   |
| 4.18.0  | 5         | 1.22%   |
| 6.1.20  | 4         | 0.97%   |
| 4.9.95  | 4         | 0.97%   |
| 4.9.41  | 4         | 0.97%   |
| 4.9.111 | 4         | 0.97%   |
| 6.6.2   | 3         | 0.73%   |
| 6.2.6   | 3         | 0.73%   |
| 6.11.7  | 3         | 0.73%   |
| 6.1.52  | 3         | 0.73%   |
| 6.1.1   | 3         | 0.73%   |
| 5.4.83  | 3         | 0.73%   |
| 5.4.32  | 3         | 0.73%   |
| 5.13.0  | 3         | 0.73%   |
| 4.19.0  | 3         | 0.73%   |
| 4.13.0  | 3         | 0.73%   |
| 6.9.3   | 2         | 0.49%   |
| 6.9.10  | 2         | 0.49%   |
| 6.8.9   | 2         | 0.49%   |
| 6.8.7   | 2         | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 58        | 14.83%  |
| 4.15    | 29        | 7.42%   |
| 6.1     | 28        | 7.16%   |
| 5.4     | 28        | 7.16%   |
| 5.15    | 26        | 6.65%   |
| 5.10    | 21        | 5.37%   |
| 4.1     | 20        | 5.12%   |
| 6.2     | 17        | 4.35%   |
| 6.5     | 16        | 4.09%   |
| 6.8     | 15        | 3.84%   |
| 6.6     | 11        | 2.81%   |
| 5.11    | 11        | 2.81%   |
| 5.19    | 10        | 2.56%   |
| 5.8     | 9         | 2.3%    |
| 6.4     | 7         | 1.79%   |
| 5.3     | 7         | 1.79%   |
| 5.0     | 7         | 1.79%   |
| 4.18    | 6         | 1.53%   |
| 6.9     | 5         | 1.28%   |
| 6.7     | 5         | 1.28%   |
| 6.11    | 5         | 1.28%   |
| 5.14    | 5         | 1.28%   |
| 5.17    | 4         | 1.02%   |
| 5.13    | 4         | 1.02%   |
| 4.19    | 4         | 1.02%   |
| 6.3     | 3         | 0.77%   |
| 6.10    | 3         | 0.77%   |
| 5.9     | 3         | 0.77%   |
| 5.16    | 3         | 0.77%   |
| 4.13    | 3         | 0.77%   |
| 6.0     | 2         | 0.51%   |
| 5.6     | 2         | 0.51%   |
| 5.18    | 2         | 0.51%   |
| 5.12    | 2         | 0.51%   |
| 4.16    | 2         | 0.51%   |
| 5.7     | 1         | 0.26%   |
| 5.1     | 1         | 0.26%   |
| 4.4     | 1         | 0.26%   |
| 4.20    | 1         | 0.26%   |
| 3.14    | 1         | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 331       | 92.98%  |
| i686    | 23        | 6.46%   |
| aarch64 | 1         | 0.28%   |
| Unknown | 1         | 0.28%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 116       | 30.77%  |
| KDE4            | 89        | 23.61%  |
| KDE5            | 76        | 20.16%  |
| Unknown         | 22        | 5.84%   |
| XFCE            | 15        | 3.98%   |
| X-Cinnamon      | 13        | 3.45%   |
| KDE             | 13        | 3.45%   |
| LXQt            | 8         | 2.12%   |
| KDE6            | 7         | 1.86%   |
| Pantheon        | 3         | 0.8%    |
| Unity           | 2         | 0.53%   |
| MATE            | 2         | 0.53%   |
| i3              | 2         | 0.53%   |
| Hyprland        | 2         | 0.53%   |
| sway            | 1         | 0.27%   |
| Openbox         | 1         | 0.27%   |
| LXDE            | 1         | 0.27%   |
| GNOME Flashback | 1         | 0.27%   |
| COSMIC          | 1         | 0.27%   |
| Cinnamon        | 1         | 0.27%   |
| awesome         | 1         | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 266       | 72.28%  |
| Wayland | 88        | 23.91%  |
| Unknown | 9         | 2.45%   |
| Tty     | 5         | 1.36%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 101       | 26.86%  |
| KDM            | 89        | 23.67%  |
| SDDM           | 82        | 21.81%  |
| GDM3           | 38        | 10.11%  |
| GDM            | 37        | 9.84%   |
| LightDM        | 22        | 5.85%   |
| TDM            | 4         | 1.06%   |
| XDM            | 1         | 0.27%   |
| SLiM           | 1         | 0.27%   |
| COSMIC-GREETER | 1         | 0.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 119       | 32.51%  |
| en_US       | 116       | 31.69%  |
| ru_RU       | 112       | 30.6%   |
| C           | 8         | 2.19%   |
| ru_RU.UTF_8 | 4         | 1.09%   |
| en_GB       | 3         | 0.82%   |
| tr_TR       | 1         | 0.27%   |
| kk_KZ       | 1         | 0.27%   |
| en_IN       | 1         | 0.27%   |
| en_IL       | 1         | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 195       | 52.85%  |
| BIOS | 174       | 47.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 231       | 62.6%   |
| Unknown | 75        | 20.33%  |
| Btrfs   | 36        | 9.76%   |
| Overlay | 19        | 5.15%   |
| Tmpfs   | 5         | 1.36%   |
| Xfs     | 2         | 0.54%   |
| F2fs    | 1         | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 153       | 41.24%  |
| Unknown | 129       | 34.77%  |
| MBR     | 89        | 23.99%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 325       | 88.32%  |
| Yes       | 43        | 11.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 264       | 71.16%  |
| Yes       | 107       | 28.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 83        | 23.31%  |
| ASUSTek Computer    | 71        | 19.94%  |
| Hewlett-Packard     | 66        | 18.54%  |
| Acer                | 54        | 15.17%  |
| Dell                | 31        | 8.71%   |
| Toshiba             | 7         | 1.97%   |
| Sony                | 7         | 1.97%   |
| Samsung Electronics | 6         | 1.69%   |
| Fujitsu             | 5         | 1.4%    |
| Unknown             | 5         | 1.4%    |
| Valve               | 3         | 0.84%   |
| Packard Bell        | 3         | 0.84%   |
| HUAWEI              | 3         | 0.84%   |
| Fujitsu Siemens     | 3         | 0.84%   |
| Chuwi               | 2         | 0.56%   |
| YiFang              | 1         | 0.28%   |
| MSI                 | 1         | 0.28%   |
| IBM                 | 1         | 0.28%   |
| HONOR               | 1         | 0.28%   |
| GPD                 | 1         | 0.28%   |
| eMachines           | 1         | 0.28%   |
| Elenberg            | 1         | 0.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo G500 20236                        | 8         | 2.25%   |
| Unknown                                  | 6         | 1.69%   |
| HP Pavilion g6                           | 5         | 1.4%    |
| Acer Aspire E5-575G                      | 5         | 1.4%    |
| Valve Jupiter                            | 3         | 0.84%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2      | 3         | 0.84%   |
| Lenovo G510 20238                        | 3         | 0.84%   |
| HP Pavilion dv6                          | 3         | 0.84%   |
| Fujitsu LIFEBOOK AH531                   | 3         | 0.84%   |
| ASUS VivoBook_ASUSLaptop X1505VA_X1505VA | 3         | 0.84%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR     | 3         | 0.84%   |
| Acer Aspire 5750G                        | 3         | 0.84%   |
| Packard Bell DOT S                       | 2         | 0.56%   |
| Lenovo ThinkPad Edge E530 3259CEG        | 2         | 0.56%   |
| Lenovo ThinkBook 15 G3 ACL 21A4          | 2         | 0.56%   |
| Lenovo ThinkBook 14 G2 ITL 20VD          | 2         | 0.56%   |
| Lenovo Legion Y540-15IRH-PG0 81SY        | 2         | 0.56%   |
| Lenovo IdeaPad Z570 HuronRiver Platform  | 2         | 0.56%   |
| Lenovo G505s 20255                       | 2         | 0.56%   |
| HP Presario CQ57                         | 2         | 0.56%   |
| HP Pavilion Gaming Laptop 15-cx0xxx      | 2         | 0.56%   |
| HP Compaq CQ58                           | 2         | 0.56%   |
| Dell Vostro 3500                         | 2         | 0.56%   |
| Dell Inspiron N5110                      | 2         | 0.56%   |
| ASUS X51RL                               | 2         | 0.56%   |
| ASUS VivoBook_ASUSLaptop K6500ZC_K6500ZC | 2         | 0.56%   |
| ASUS ASUS EXPERTBOOK B1502CVA_B1502CVA   | 2         | 0.56%   |
| Acer Aspire V3-551G                      | 2         | 0.56%   |
| Acer Aspire ES1-523                      | 2         | 0.56%   |
| Acer Aspire A715-75G                     | 2         | 0.56%   |
| Acer Aspire A515-57                      | 2         | 0.56%   |
| Acer Aspire A315-51                      | 2         | 0.56%   |
| YiFang NXW9QC132                         | 1         | 0.28%   |
| Toshiba TECRA S11                        | 1         | 0.28%   |
| Toshiba TECRA M5                         | 1         | 0.28%   |
| Toshiba Satellite P105                   | 1         | 0.28%   |
| Toshiba Satellite C660                   | 1         | 0.28%   |
| Toshiba Satellite C650                   | 1         | 0.28%   |
| Toshiba Satellite 5200                   | 1         | 0.28%   |
| Toshiba Portable PC                      | 1         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 34        | 9.55%   |
| ASUS VivoBook         | 28        | 7.87%   |
| Lenovo IdeaPad        | 26        | 7.3%    |
| HP Pavilion           | 18        | 5.06%   |
| Dell Inspiron         | 18        | 5.06%   |
| Lenovo ThinkPad       | 14        | 3.93%   |
| HP ProBook            | 11        | 3.09%   |
| Lenovo Legion         | 9         | 2.53%   |
| HP Laptop             | 9         | 2.53%   |
| Lenovo G500           | 8         | 2.25%   |
| ASUS ASUS             | 8         | 2.25%   |
| Lenovo ThinkBook      | 7         | 1.97%   |
| Dell Latitude         | 7         | 1.97%   |
| HP Compaq             | 6         | 1.69%   |
| Acer Nitro            | 6         | 1.69%   |
| Unknown               | 6         | 1.69%   |
| HP EliteBook          | 5         | 1.4%    |
| Fujitsu LIFEBOOK      | 5         | 1.4%    |
| ASUS ROG              | 5         | 1.4%    |
| Toshiba Satellite     | 4         | 1.12%   |
| Valve Jupiter         | 3         | 0.84%   |
| Lenovo G510           | 3         | 0.84%   |
| Acer Swift            | 3         | 0.84%   |
| Acer Predator         | 3         | 0.84%   |
| Toshiba TECRA         | 2         | 0.56%   |
| Packard Bell DOT      | 2         | 0.56%   |
| Lenovo G505s          | 2         | 0.56%   |
| HP Victus             | 2         | 0.56%   |
| HP Presario           | 2         | 0.56%   |
| HP ENVY               | 2         | 0.56%   |
| HP 250                | 2         | 0.56%   |
| Fujitsu Siemens AMILO | 2         | 0.56%   |
| Dell Vostro           | 2         | 0.56%   |
| ASUS Zenbook          | 2         | 0.56%   |
| ASUS X51RL            | 2         | 0.56%   |
| Acer TravelMate       | 2         | 0.56%   |
| YiFang NXW9QC132      | 1         | 0.28%   |
| Toshiba Portable      | 1         | 0.28%   |
| Sony VPCEH2M1R        | 1         | 0.28%   |
| Sony VPCEB1E1R        | 1         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 41        | 11.52%  |
| 2011    | 33        | 9.27%   |
| 2013    | 32        | 8.99%   |
| 2021    | 29        | 8.15%   |
| 2022    | 25        | 7.02%   |
| 2020    | 24        | 6.74%   |
| 2019    | 23        | 6.46%   |
| 2017    | 21        | 5.9%    |
| 2016    | 19        | 5.34%   |
| 2018    | 17        | 4.78%   |
| 2010    | 17        | 4.78%   |
| 2023    | 14        | 3.93%   |
| 2015    | 14        | 3.93%   |
| 2008    | 14        | 3.93%   |
| 2009    | 8         | 2.25%   |
| 2014    | 7         | 1.97%   |
| 2007    | 7         | 1.97%   |
| 2024    | 5         | 1.4%    |
| 2006    | 2         | 0.56%   |
| Unknown | 2         | 0.56%   |
| 2005    | 1         | 0.28%   |
| 2003    | 1         | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 356       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 331       | 92.2%   |
| Enabled  | 28        | 7.8%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 356       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 99        | 27.27%  |
| 3.01-4.0    | 84        | 23.14%  |
| 8.01-16.0   | 66        | 18.18%  |
| 16.01-24.0  | 51        | 14.05%  |
| 1.01-2.0    | 20        | 5.51%   |
| 2.01-3.0    | 16        | 4.41%   |
| 32.01-64.0  | 14        | 3.86%   |
| 0.51-1.0    | 6         | 1.65%   |
| 24.01-32.0  | 4         | 1.1%    |
| 64.01-256.0 | 2         | 0.55%   |
| Unknown     | 1         | 0.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 117       | 29.47%  |
| 2.01-3.0   | 82        | 20.65%  |
| 0.51-1.0   | 66        | 16.62%  |
| 3.01-4.0   | 53        | 13.35%  |
| 4.01-8.0   | 51        | 12.85%  |
| 8.01-16.0  | 21        | 5.29%   |
| 0.01-0.5   | 4         | 1.01%   |
| Unknown    | 2         | 0.5%    |
| 16.01-24.0 | 1         | 0.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 283       | 77.75%  |
| 2      | 75        | 20.6%   |
| 3      | 6         | 1.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 223       | 62.64%  |
| Yes       | 133       | 37.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 310       | 87.08%  |
| No        | 46        | 12.92%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 348       | 97.48%  |
| No        | 9         | 2.52%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 286       | 79.22%  |
| No        | 75        | 20.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Kazakhstan | 356       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Almaty          | 121       | 31.35%  |
| Nur-Sultan      | 47        | 12.18%  |
| Astana          | 27        | 6.99%   |
| Pavlodar        | 21        | 5.44%   |
| Karaganda       | 21        | 5.44%   |
| Ust-Kamenogorsk | 18        | 4.66%   |
| Kostanay        | 18        | 4.66%   |
| Aktobe          | 18        | 4.66%   |
| Aktau           | 11        | 2.85%   |
| Taraz           | 10        | 2.59%   |
| Petropavl       | 9         | 2.33%   |
| Kyzylorda       | 9         | 2.33%   |
| Shymkent        | 6         | 1.55%   |
| Rudnyy          | 6         | 1.55%   |
| Semey           | 5         | 1.3%    |
| Atyrau          | 5         | 1.3%    |
| Ridder          | 4         | 1.04%   |
| Temirtau        | 3         | 0.78%   |
| Oral            | 3         | 0.78%   |
| Kokshetau       | 3         | 0.78%   |
| Ekibastuz       | 3         | 0.78%   |
| Taiynsha        | 2         | 0.52%   |
| Stepnogorsk     | 2         | 0.52%   |
| Soran           | 2         | 0.52%   |
| Shchūchīnsk   | 2         | 0.52%   |
| Balqash         | 2         | 0.52%   |
| Taldykorgan     | 1         | 0.26%   |
| Līsakovsk      | 1         | 0.26%   |
| Kaskelen        | 1         | 0.26%   |
| Karagandy       | 1         | 0.26%   |
| Kapshagay       | 1         | 0.26%   |
| GГјlshat      | 1         | 0.26%   |
| Chiili          | 1         | 0.26%   |
| Almaty Oblysy   | 1         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 63        | 78     | 14.35%  |
| Seagate                     | 57        | 79     | 12.98%  |
| Samsung Electronics         | 39        | 50     | 8.88%   |
| Toshiba                     | 35        | 45     | 7.97%   |
| Kingston                    | 29        | 33     | 6.61%   |
| Hitachi                     | 21        | 23     | 4.78%   |
| Unknown                     | 20        | 25     | 4.56%   |
| Micron Technology           | 20        | 23     | 4.56%   |
| Sandisk                     | 18        | 19     | 4.1%    |
| HGST                        | 16        | 18     | 3.64%   |
| SK hynix                    | 15        | 18     | 3.42%   |
| Intel                       | 15        | 15     | 3.42%   |
| Transcend                   | 11        | 14     | 2.51%   |
| KIOXIA                      | 7         | 10     | 1.59%   |
| GeIL                        | 5         | 5      | 1.14%   |
| Apacer                      | 5         | 7      | 1.14%   |
| A-DATA Technology           | 5         | 6      | 1.14%   |
| Team                        | 4         | 4      | 0.91%   |
| Plextor                     | 4         | 4      | 0.91%   |
| Netac                       | 4         | 4      | 0.91%   |
| Fujitsu                     | 4         | 5      | 0.91%   |
| Crucial                     | 4         | 4      | 0.91%   |
| China                       | 4         | 4      | 0.91%   |
| Phison                      | 3         | 3      | 0.68%   |
| Gigabyte Technology         | 3         | 3      | 0.68%   |
| Silicon Motion              | 2         | 2      | 0.46%   |
| Kingston Technology Company | 2         | 2      | 0.46%   |
| HS-SSD-E100                 | 2         | 2      | 0.46%   |
| BIWIN                       | 2         | 2      | 0.46%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.23%   |
| TS512GSS                    | 1         | 1      | 0.23%   |
| StoreJet                    | 1         | 1      | 0.23%   |
| Realtek Semiconductor       | 1         | 1      | 0.23%   |
| Qumo                        | 1         | 1      | 0.23%   |
| Phison Electronics          | 1         | 1      | 0.23%   |
| OCZ                         | 1         | 1      | 0.23%   |
| O2 Micro                    | 1         | 1      | 0.23%   |
| KingSpec                    | 1         | 1      | 0.23%   |
| KingDian                    | 1         | 1      | 0.23%   |
| Kingchuxing                 | 1         | 2      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 16        | 3.56%   |
| Seagate ST1000LM035-1RK172 1TB                       | 12        | 2.67%   |
| Toshiba MQ01ABD100 1TB                               | 8         | 1.78%   |
| Toshiba MQ04ABF100 1TB                               | 7         | 1.56%   |
| Kingston SA400S37480G 480GB SSD                      | 7         | 1.56%   |
| Intel SSDPEKNU512GZ 512GB                            | 7         | 1.56%   |
| Toshiba MQ01ABF050 500GB                             | 6         | 1.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB                  | 6         | 1.33%   |
| HGST HTS541010A9E680 1TB                             | 6         | 1.33%   |
| SanDisk NVMe SSD Drive 512GB                         | 5         | 1.11%   |
| Kingston SA400S37240G 240GB SSD                      | 5         | 1.11%   |
| WDC WD10SPZX-21Z10T0 1TB                             | 4         | 0.89%   |
| Seagate ST9320325AS 320GB                            | 4         | 0.89%   |
| Seagate ST500LT012-1DG142 500GB                      | 4         | 0.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 4         | 0.89%   |
| Samsung MZALQ512HALU-000L2 512GB                     | 4         | 0.89%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                        | 4         | 0.89%   |
| Kingston SA400S37120G 120GB SSD                      | 4         | 0.89%   |
| WDC WD3200BPVT-22JJ5T0 320GB                         | 3         | 0.67%   |
| Unknown MMC Card  4GB                                | 3         | 0.67%   |
| Transcend TS120GSSD220S 120GB                        | 3         | 0.67%   |
| SK hynix NVMe SSD Drive 512GB                        | 3         | 0.67%   |
| Seagate ST500LT012-9WS142 500GB                      | 3         | 0.67%   |
| Intel NVMe SSD Drive 512GB                           | 3         | 0.67%   |
| Hitachi HTS547550A9E384 500GB                        | 3         | 0.67%   |
| Hitachi HTS543232A7A384 320GB                        | 3         | 0.67%   |
| WDC WD7500BPVT-22HXZT3 752GB                         | 2         | 0.44%   |
| WDC WD7500BPVT-08HXZT3 752GB                         | 2         | 0.44%   |
| WDC WD5000LPLX-00ZNTT0 500GB                         | 2         | 0.44%   |
| WDC WD5000LPCX-24VHAT0 500GB                         | 2         | 0.44%   |
| WDC WD5000LPCX-21VHAT0 500GB                         | 2         | 0.44%   |
| WDC WD3200BPVT-22ZEST0 320GB                         | 2         | 0.44%   |
| WDC WD10SPZX-24Z10 1TB                               | 2         | 0.44%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 2         | 0.44%   |
| Unknown SD32G  32GB                                  | 2         | 0.44%   |
| Unknown NCard  32GB                                  | 2         | 0.44%   |
| Unknown MMC Card  32GB                               | 2         | 0.44%   |
| Unknown MMC Card  16GB                               | 2         | 0.44%   |
| Transcend TS128GSSD230S 128GB                        | 2         | 0.44%   |
| Toshiba MK5059GSXP 500GB                             | 2         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 57        | 79     | 29.53%  |
| WDC                 | 54        | 68     | 27.98%  |
| Toshiba             | 33        | 40     | 17.1%   |
| Hitachi             | 21        | 23     | 10.88%  |
| HGST                | 16        | 18     | 8.29%   |
| Samsung Electronics | 5         | 5      | 2.59%   |
| Fujitsu             | 4         | 5      | 2.07%   |
| StoreJet            | 1         | 1      | 0.52%   |
| JMicron Technology  | 1         | 1      | 0.52%   |
| HGST HTS            | 1         | 1      | 0.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 23        | 26     | 24.73%  |
| Transcend           | 11        | 14     | 11.83%  |
| Team                | 4         | 4      | 4.3%    |
| SanDisk             | 4         | 4      | 4.3%    |
| Samsung Electronics | 4         | 6      | 4.3%    |
| Plextor             | 4         | 4      | 4.3%    |
| Netac               | 4         | 4      | 4.3%    |
| Crucial             | 4         | 4      | 4.3%    |
| China               | 4         | 4      | 4.3%    |
| Apacer              | 4         | 6      | 4.3%    |
| Gigabyte Technology | 3         | 3      | 3.23%   |
| GeIL                | 3         | 3      | 3.23%   |
| A-DATA Technology   | 3         | 4      | 3.23%   |
| WDC                 | 2         | 2      | 2.15%   |
| SK hynix            | 2         | 2      | 2.15%   |
| Micron Technology   | 2         | 2      | 2.15%   |
| Intel               | 2         | 2      | 2.15%   |
| Unknown             | 1         | 1      | 1.08%   |
| Qumo                | 1         | 1      | 1.08%   |
| OCZ                 | 1         | 1      | 1.08%   |
| KingSpec            | 1         | 1      | 1.08%   |
| KingDian            | 1         | 1      | 1.08%   |
| Kingchuxing         | 1         | 2      | 1.08%   |
| HS-SSD-E100         | 1         | 1      | 1.08%   |
| GOODRAM             | 1         | 1      | 1.08%   |
| BIWIN               | 1         | 1      | 1.08%   |
| AMD R5SL            | 1         | 1      | 1.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 185       | 241    | 44.15%  |
| NVMe    | 124       | 158    | 29.59%  |
| SSD     | 87        | 105    | 20.76%  |
| MMC     | 18        | 22     | 4.3%    |
| Unknown | 5         | 5      | 1.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 244       | 338    | 61.62%  |
| NVMe | 124       | 158    | 31.31%  |
| MMC  | 18        | 22     | 4.55%   |
| SAS  | 10        | 13     | 2.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 174       | 228    | 64.68%  |
| 0.51-1.0   | 92        | 115    | 34.2%   |
| 1.01-2.0   | 3         | 3      | 1.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 109       | 28.31%  |
| 101-250        | 88        | 22.86%  |
| 501-1000       | 70        | 18.18%  |
| 1-20           | 38        | 9.87%   |
| 51-100         | 29        | 7.53%   |
| 1001-2000      | 25        | 6.49%   |
| 21-50          | 15        | 3.9%    |
| More than 3000 | 4         | 1.04%   |
| Unknown        | 4         | 1.04%   |
| 2001-3000      | 3         | 0.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 173       | 43.91%  |
| 21-50     | 62        | 15.74%  |
| 101-250   | 57        | 14.47%  |
| 51-100    | 44        | 11.17%  |
| 251-500   | 29        | 7.36%   |
| 501-1000  | 19        | 4.82%   |
| 1001-2000 | 6         | 1.52%   |
| Unknown   | 4         | 1.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 3      | 5.26%   |
| Hitachi HTS543232A7A384 320GB       | 3         | 3      | 5.26%   |
| Toshiba MQ01ABF050 500GB            | 2         | 2      | 3.51%   |
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 3.51%   |
| Toshiba MK5059GSXP 500GB            | 2         | 3      | 3.51%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 9      | 3.51%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 4      | 3.51%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 2      | 3.51%   |
| Samsung Electronics HM321HI 320GB   | 2         | 2      | 3.51%   |
| HGST HTS541010A9E680 1TB            | 2         | 3      | 3.51%   |
| WDC WD7500BPVT-08HXZT3 752GB        | 1         | 1      | 1.75%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1         | 1      | 1.75%   |
| WDC WD5000LPCX-21VHAT0 500GB        | 1         | 6      | 1.75%   |
| WDC WD3200BPVT-75ZEST0 320GB        | 1         | 1      | 1.75%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 1         | 1      | 1.75%   |
| WDC WD3200BEVT-80A0RT0 320GB        | 1         | 1      | 1.75%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 1      | 1.75%   |
| WDC WD20NPVT-00Z2TT0 2TB            | 1         | 1      | 1.75%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 1      | 1.75%   |
| Toshiba MQ04ABF100 1TB              | 1         | 1      | 1.75%   |
| Toshiba MK5065GSX 500GB             | 1         | 1      | 1.75%   |
| Toshiba MK3263GSX 320GB             | 1         | 1      | 1.75%   |
| Toshiba MK2552GSX 250GB             | 1         | 1      | 1.75%   |
| Toshiba MK1637GSX 160GB             | 1         | 1      | 1.75%   |
| Team L3 EVO SSD 120GB               | 1         | 1      | 1.75%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 1.75%   |
| Seagate ST9320325AS 320GB           | 1         | 1      | 1.75%   |
| Seagate ST9250410AS 250GB           | 1         | 1      | 1.75%   |
| Seagate ST9120822AS 120GB           | 1         | 1      | 1.75%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 2      | 1.75%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 1.75%   |
| Plextor PX-128M6S 128GB SSD         | 1         | 1      | 1.75%   |
| Hitachi HTS725050A9A364 500GB       | 1         | 1      | 1.75%   |
| Hitachi HTS722020K9SA00 200GB       | 1         | 1      | 1.75%   |
| Hitachi HTS547575A9E384 752GB       | 1         | 1      | 1.75%   |
| Hitachi HTS547550A9E384 500GB       | 1         | 2      | 1.75%   |
| Hitachi HTS545050A7E380 500GB       | 1         | 1      | 1.75%   |
| Hitachi HTS543216L9SA00 160GB       | 1         | 1      | 1.75%   |
| Hitachi HTS542512K9SA00 120GB       | 1         | 1      | 1.75%   |
| Hitachi HTS541680J9SA00 80GB        | 1         | 1      | 1.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 25     | 26.32%  |
| Hitachi             | 12        | 13     | 21.05%  |
| Toshiba             | 11        | 12     | 19.3%   |
| WDC                 | 9         | 14     | 15.79%  |
| HGST                | 6         | 7      | 10.53%  |
| Samsung Electronics | 2         | 2      | 3.51%   |
| Team                | 1         | 1      | 1.75%   |
| Plextor             | 1         | 1      | 1.75%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 25     | 27.27%  |
| Hitachi             | 12        | 13     | 21.82%  |
| Toshiba             | 11        | 12     | 20%     |
| WDC                 | 9         | 14     | 16.36%  |
| HGST                | 6         | 7      | 10.91%  |
| Samsung Electronics | 2         | 2      | 3.64%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 52        | 73     | 96.3%   |
| SSD  | 2         | 2      | 3.7%    |

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
| Works    | 199       | 275    | 51.42%  |
| Detected | 134       | 181    | 34.63%  |
| Malfunc  | 54        | 75     | 13.95%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 262       | 61.79%  |
| AMD                          | 43        | 10.14%  |
| Samsung Electronics          | 31        | 7.31%   |
| SanDisk                      | 20        | 4.72%   |
| Micron Technology            | 18        | 4.25%   |
| SK hynix                     | 13        | 3.07%   |
| Kingston Technology Company  | 9         | 2.12%   |
| KIOXIA                       | 6         | 1.42%   |
| Phison Electronics           | 5         | 1.18%   |
| Toshiba America Info Systems | 3         | 0.71%   |
| ADATA Technology             | 3         | 0.71%   |
| Union Memory (Shenzhen)      | 2         | 0.47%   |
| Solidigm                     | 2         | 0.47%   |
| Silicon Motion               | 2         | 0.47%   |
| Realtek Semiconductor        | 1         | 0.24%   |
| O2 Micro                     | 1         | 0.24%   |
| Nvidia                       | 1         | 0.24%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.24%   |
| Biwin Storage Technology     | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 41        | 8.78%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 34        | 7.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 30        | 6.42%   |
| Intel Volume Management Device NVMe RAID Controller                              | 22        | 4.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 20        | 4.28%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 14        | 3%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 13        | 2.78%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 13        | 2.78%   |
| Intel Tiger Lake-LP SATA Controller                                              | 12        | 2.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 10        | 2.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 10        | 2.14%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 9         | 1.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 9         | 1.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 8         | 1.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 1.71%   |
| Micron 2400 NVMe SSD (DRAM-less)                                                 | 7         | 1.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 1.5%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 6         | 1.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 6         | 1.28%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 6         | 1.28%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 6         | 1.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 1.28%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 6         | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 1.28%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 5         | 1.07%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation            | 5         | 1.07%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 1.07%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 1.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 1.07%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 1.07%   |
| SK hynix BC511 NVMe SSD                                                          | 4         | 0.86%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 4         | 0.86%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 4         | 0.86%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 0.86%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 4         | 0.86%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 4         | 0.86%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 3         | 0.64%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 3         | 0.64%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 3         | 0.64%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 3         | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 256       | 56.76%  |
| NVMe | 124       | 27.49%  |
| RAID | 41        | 9.09%   |
| IDE  | 30        | 6.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 282       | 79.21%  |
| AMD     | 73        | 20.51%  |
| Unknown | 1         | 0.28%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 10        | 2.81%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 2.81%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 1.69%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 6         | 1.69%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 1.4%    |
| Intel Core i3-3110M CPU @ 2.40GHz             | 5         | 1.4%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 5         | 1.4%    |
| Intel 12th Gen Core i5-12500H                 | 5         | 1.4%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 1.4%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.12%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 1.12%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.12%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 1.12%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 1.12%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 1.12%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.12%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 4         | 1.12%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 3         | 0.84%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 0.84%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.84%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 0.84%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.84%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 3         | 0.84%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 0.84%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 0.84%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 3         | 0.84%   |
| Intel 13th Gen Core i5-13500H                 | 3         | 0.84%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 3         | 0.84%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 0.84%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 3         | 0.84%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 0.84%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 3         | 0.84%   |
| AMD Custom APU 0405                           | 3         | 0.84%   |
| AMD A8-4500M APU with Radeon HD Graphics      | 3         | 0.84%   |
| AMD A10-4600M APU with Radeon HD Graphics     | 3         | 0.84%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 2         | 0.56%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 0.56%   |
| Intel Genuine CPU T2400 @ 1.83GHz             | 2         | 0.56%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 87        | 24.44%  |
| Other                   | 46        | 12.92%  |
| Intel Core i7           | 39        | 10.96%  |
| Intel Core i3           | 37        | 10.39%  |
| Intel Celeron           | 24        | 6.74%   |
| AMD Ryzen 7             | 15        | 4.21%   |
| AMD Ryzen 5             | 14        | 3.93%   |
| Intel Pentium           | 12        | 3.37%   |
| Intel Atom              | 11        | 3.09%   |
| Intel Core 2 Duo        | 10        | 2.81%   |
| AMD Ryzen 9             | 7         | 1.97%   |
| AMD Ryzen 3             | 6         | 1.69%   |
| AMD E                   | 5         | 1.4%    |
| AMD A8                  | 5         | 1.4%    |
| Intel Genuine           | 4         | 1.12%   |
| AMD A10                 | 4         | 1.12%   |
| Intel Pentium Dual-Core | 3         | 0.84%   |
| Intel Core 2            | 3         | 0.84%   |
| AMD A4                  | 3         | 0.84%   |
| Intel Pentium Dual      | 2         | 0.56%   |
| Intel Core              | 2         | 0.56%   |
| AMD E1                  | 2         | 0.56%   |
| AMD A6                  | 2         | 0.56%   |
| Intel Pentium Silver    | 1         | 0.28%   |
| Intel Pentium M         | 1         | 0.28%   |
| Intel Pentium Gold      | 1         | 0.28%   |
| Intel Mobile Pentium 4  | 1         | 0.28%   |
| Intel Core Duo          | 1         | 0.28%   |
| Intel Core 2 Quad       | 1         | 0.28%   |
| Intel Celeron Dual-Core | 1         | 0.28%   |
| AMD PRO A8              | 1         | 0.28%   |
| AMD E2                  | 1         | 0.28%   |
| AMD C-60                | 1         | 0.28%   |
| AMD Athlon II           | 1         | 0.28%   |
| AMD Athlon              | 1         | 0.28%   |
| AMD A12                 | 1         | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 181       | 50.84%  |
| 4       | 97        | 27.25%  |
| 8       | 21        | 5.9%    |
| 6       | 21        | 5.9%    |
| 1       | 11        | 3.09%   |
| 12      | 9         | 2.53%   |
| 10      | 7         | 1.97%   |
| 16      | 3         | 0.84%   |
| Unknown | 3         | 0.84%   |
| 24      | 2         | 0.56%   |
| 14      | 1         | 0.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 355       | 99.72%  |
| Unknown | 1         | 0.28%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 261       | 73.31%  |
| 1       | 92        | 25.84%  |
| Unknown | 3         | 0.84%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 340       | 95.51%  |
| 32-bit         | 8         | 2.25%   |
| Unknown        | 7         | 1.97%   |
| 64-bit         | 1         | 0.28%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 99        | 26.98%  |
| 0x306a9    | 29        | 7.9%    |
| 0x206a7    | 27        | 7.36%   |
| 0x806e9    | 14        | 3.81%   |
| 0x806c1    | 12        | 3.27%   |
| 0x40651    | 10        | 2.72%   |
| 0x806ea    | 9         | 2.45%   |
| 0x06001119 | 9         | 2.45%   |
| 0x906ea    | 8         | 2.18%   |
| 0x306c3    | 8         | 2.18%   |
| 0x20655    | 8         | 2.18%   |
| 0x0a50000c | 8         | 2.18%   |
| 0x806ec    | 6         | 1.63%   |
| 0x406e3    | 6         | 1.63%   |
| 0x1067a    | 6         | 1.63%   |
| 0xa0652    | 5         | 1.36%   |
| 0x0a50000d | 5         | 1.36%   |
| 0x706e5    | 4         | 1.09%   |
| 0x706a1    | 4         | 1.09%   |
| 0x6fd      | 4         | 1.09%   |
| 0x406c4    | 4         | 1.09%   |
| 0x30661    | 4         | 1.09%   |
| 0x20652    | 4         | 1.09%   |
| 0x08608103 | 4         | 1.09%   |
| 0x906a3    | 3         | 0.82%   |
| 0x6e8      | 3         | 0.82%   |
| 0x30678    | 3         | 0.82%   |
| 0x10676    | 3         | 0.82%   |
| 0x0a404102 | 3         | 0.82%   |
| 0x08108102 | 3         | 0.82%   |
| 0x03000027 | 3         | 0.82%   |
| 0xb06a2    | 2         | 0.54%   |
| 0x906e9    | 2         | 0.54%   |
| 0x806eb    | 2         | 0.54%   |
| 0x6fa      | 2         | 0.54%   |
| 0x6f6      | 2         | 0.54%   |
| 0x6ec      | 2         | 0.54%   |
| 0x306d4    | 2         | 0.54%   |
| 0x106ca    | 2         | 0.54%   |
| 0x10661    | 2         | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 55        | 15.41%  |
| IvyBridge         | 36        | 10.08%  |
| SandyBridge       | 31        | 8.68%   |
| Unknown           | 31        | 8.68%   |
| TigerLake         | 20        | 5.6%    |
| Haswell           | 19        | 5.32%   |
| Alderlake Hybrid  | 16        | 4.48%   |
| Silvermont        | 15        | 4.2%    |
| Zen 3             | 14        | 3.92%   |
| Westmere          | 12        | 3.36%   |
| Penryn            | 12        | 3.36%   |
| Core              | 12        | 3.36%   |
| Skylake           | 9         | 2.52%   |
| Piledriver        | 9         | 2.52%   |
| IceLake           | 7         | 1.96%   |
| CometLake         | 7         | 1.96%   |
| Bonnell           | 7         | 1.96%   |
| Zen+              | 6         | 1.68%   |
| P6                | 6         | 1.68%   |
| Bobcat            | 6         | 1.68%   |
| Goldmont plus     | 5         | 1.4%    |
| Excavator         | 4         | 1.12%   |
| Zen 2             | 3         | 0.84%   |
| K10 Llano         | 3         | 0.84%   |
| Broadwell         | 3         | 0.84%   |
| Puma              | 2         | 0.56%   |
| Jaguar            | 2         | 0.56%   |
| Zen               | 1         | 0.28%   |
| NetBurst          | 1         | 0.28%   |
| Meteorlake Hybrid | 1         | 0.28%   |
| K10               | 1         | 0.28%   |
| Goldmont          | 1         | 0.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 259       | 52.97%  |
| Nvidia | 123       | 25.15%  |
| AMD    | 107       | 21.88%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 34        | 6.59%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 29        | 5.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 18        | 3.49%   |
| Intel HD Graphics 620                                                                    | 16        | 3.1%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 2.33%   |
| Intel UHD Graphics 620                                                                   | 11        | 2.13%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 1.94%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 10        | 1.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 1.74%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 1.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 1.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 1.74%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 8         | 1.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 1.55%   |
| AMD Rembrandt [Radeon 680M]                                                              | 8         | 1.55%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 1.36%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 1.36%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 7         | 1.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 1.36%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 7         | 1.36%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.16%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.16%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 6         | 1.16%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 1.16%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                      | 6         | 1.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1.16%   |
| AMD Lucienne                                                                             | 6         | 1.16%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 5         | 0.97%   |
| Nvidia GF119M [GeForce 610M]                                                             | 5         | 0.97%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 5         | 0.97%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 0.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 0.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 0.97%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 5         | 0.97%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.97%   |
| AMD Barcelo                                                                              | 5         | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.78%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 0.78%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 4         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 144       | 40.22%  |
| Intel + Nvidia | 88        | 24.58%  |
| 1 x AMD        | 48        | 13.41%  |
| Intel + AMD    | 25        | 6.98%   |
| AMD + Nvidia   | 19        | 5.31%   |
| 1 x Nvidia     | 17        | 4.75%   |
| 2 x AMD        | 15        | 4.19%   |
| Other          | 1         | 0.28%   |
| 2 x Intel      | 1         | 0.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 289       | 80.28%  |
| Proprietary | 55        | 15.28%  |
| Unknown     | 16        | 4.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 163       | 44.66%  |
| 1.01-2.0   | 90        | 24.66%  |
| 0.01-0.5   | 61        | 16.71%  |
| 3.01-4.0   | 23        | 6.3%    |
| 0.51-1.0   | 16        | 4.38%   |
| 5.01-6.0   | 7         | 1.92%   |
| 7.01-8.0   | 4         | 1.1%    |
| 8.01-16.0  | 1         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 81        | 21.43%  |
| LG Display              | 62        | 16.4%   |
| BOE                     | 55        | 14.55%  |
| Chimei Innolux          | 48        | 12.7%   |
| Samsung Electronics     | 47        | 12.43%  |
| Chi Mei Optoelectronics | 20        | 5.29%   |
| Acer                    | 9         | 2.38%   |
| Hewlett-Packard         | 6         | 1.59%   |
| PANDA                   | 4         | 1.06%   |
| Valve                   | 3         | 0.79%   |
| Quanta Display          | 3         | 0.79%   |
| LG Philips              | 3         | 0.79%   |
| Lenovo                  | 3         | 0.79%   |
| Goldstar                | 3         | 0.79%   |
| Unknown                 | 2         | 0.53%   |
| Toshiba                 | 2         | 0.53%   |
| Sony                    | 2         | 0.53%   |
| SAC                     | 2         | 0.53%   |
| Philips                 | 2         | 0.53%   |
| InfoVision              | 2         | 0.53%   |
| HannStar                | 2         | 0.53%   |
| CSO                     | 2         | 0.53%   |
| CPT                     | 2         | 0.53%   |
| ViewSonic               | 1         | 0.26%   |
| Unknown (XXX)           | 1         | 0.26%   |
| Sharp                   | 1         | 0.26%   |
| Seiko/Epson             | 1         | 0.26%   |
| Mi                      | 1         | 0.26%   |
| KDC                     | 1         | 0.26%   |
| Iiyama                  | 1         | 0.26%   |
| Gigabyte Technology     | 1         | 0.26%   |
| Dell                    | 1         | 0.26%   |
| Daewoo                  | 1         | 0.26%   |
| BenQ                    | 1         | 0.26%   |
| ASUSTek Computer        | 1         | 0.26%   |
| AOC                     | 1         | 0.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 9         | 2.37%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 8         | 2.11%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 1.58%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 5         | 1.32%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 5         | 1.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 5         | 1.32%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 5         | 1.32%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 4         | 1.05%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 4         | 1.05%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 1.05%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 3         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 3         | 0.79%   |
| BOE LCD Monitor BOE0A9B 2560x1600 344x215mm 16.0-inch                    | 3         | 0.79%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 3         | 0.79%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 0.79%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                    | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch     | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3253 1366x768 344x194mm 15.5-inch     | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 340x190mm 15.3-inch     | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4180 2880x1620 344x194mm 15.5-inch    | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4178 3200x2000 344x215mm 16.0-inch    | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch    | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch     | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                        | 2         | 0.53%   |
| SAC LED MONITOR SAC952D 1920x1080 443x249mm 20.0-inch                    | 2         | 0.53%   |
| Quanta Display LCD Monitor QDS0033 1024x768 304x228mm 15.0-inch          | 2         | 0.53%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.53%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch              | 2         | 0.53%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch              | 2         | 0.53%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 2         | 0.53%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 0.53%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 2         | 0.53%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 2         | 0.53%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 2         | 0.53%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 2         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 147       | 40.61%  |
| 1920x1080 (FHD)    | 134       | 37.02%  |
| 1600x900 (HD+)     | 14        | 3.87%   |
| 1280x800 (WXGA)    | 11        | 3.04%   |
| 2560x1600          | 9         | 2.49%   |
| 2560x1440 (QHD)    | 7         | 1.93%   |
| 1920x1200 (WUXGA)  | 5         | 1.38%   |
| 1024x600           | 5         | 1.38%   |
| 2880x1620          | 4         | 1.1%    |
| 1680x1050 (WSXGA+) | 4         | 1.1%    |
| 1440x900 (WXGA+)   | 4         | 1.1%    |
| 800x1280           | 3         | 0.83%   |
| 3200x2000          | 2         | 0.55%   |
| 1400x1050          | 2         | 0.55%   |
| 1280x1024 (SXGA)   | 2         | 0.55%   |
| 1024x768 (XGA)     | 2         | 0.55%   |
| 3840x2160 (4K)     | 1         | 0.28%   |
| 3440x1440          | 1         | 0.28%   |
| 2880x1800          | 1         | 0.28%   |
| 2288x1287          | 1         | 0.28%   |
| 2240x1400          | 1         | 0.28%   |
| 2160x1440          | 1         | 0.28%   |
| 1360x768           | 1         | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 226       | 59.47%  |
| 14      | 25        | 6.58%   |
| 17      | 23        | 6.05%   |
| 13      | 20        | 5.26%   |
| 16      | 14        | 3.68%   |
| 21      | 9         | 2.37%   |
| 27      | 8         | 2.11%   |
| 24      | 7         | 1.84%   |
| 12      | 6         | 1.58%   |
| 10      | 6         | 1.58%   |
| 31      | 5         | 1.32%   |
| 23      | 4         | 1.05%   |
| 18      | 4         | 1.05%   |
| 11      | 4         | 1.05%   |
| Unknown | 4         | 1.05%   |
| 19      | 3         | 0.79%   |
| 7       | 3         | 0.79%   |
| 22      | 2         | 0.53%   |
| 142     | 1         | 0.26%   |
| 54      | 1         | 0.26%   |
| 46      | 1         | 0.26%   |
| 43      | 1         | 0.26%   |
| 40      | 1         | 0.26%   |
| 34      | 1         | 0.26%   |
| 32      | 1         | 0.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 272       | 71.58%  |
| 351-400        | 30        | 7.89%   |
| 201-300        | 25        | 6.58%   |
| 501-600        | 18        | 4.74%   |
| 401-500        | 15        | 3.95%   |
| 601-700        | 6         | 1.58%   |
| Unknown        | 4         | 1.05%   |
| 1-100          | 3         | 0.79%   |
| 801-900        | 2         | 0.53%   |
| 701-800        | 2         | 0.53%   |
| 1001-1500      | 2         | 0.53%   |
| More than 2000 | 1         | 0.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 299       | 85.43%  |
| 16/10   | 35        | 10%     |
| 4/3     | 5         | 1.43%   |
| 0.67    | 3         | 0.86%   |
| 3/2     | 2         | 0.57%   |
| Unknown | 2         | 0.57%   |
| 6/5     | 1         | 0.29%   |
| 5/4     | 1         | 0.29%   |
| 21/9    | 1         | 0.29%   |
| 1.00    | 1         | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 227       | 59.74%  |
| 81-90          | 36        | 9.47%   |
| 121-130        | 20        | 5.26%   |
| 201-250        | 19        | 5%      |
| 111-120        | 11        | 2.89%   |
| 71-80          | 9         | 2.37%   |
| 301-350        | 8         | 2.11%   |
| 351-500        | 7         | 1.84%   |
| 41-50          | 6         | 1.58%   |
| 61-70          | 5         | 1.32%   |
| 151-200        | 5         | 1.32%   |
| 51-60          | 4         | 1.05%   |
| Unknown        | 4         | 1.05%   |
| 1-40           | 3         | 0.79%   |
| 141-150        | 3         | 0.79%   |
| 131-140        | 3         | 0.79%   |
| 501-1000       | 3         | 0.79%   |
| 91-100         | 3         | 0.79%   |
| More than 1000 | 2         | 0.53%   |
| 251-300        | 2         | 0.53%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 147       | 39.1%   |
| 121-160       | 133       | 35.37%  |
| 51-100        | 60        | 15.96%  |
| 161-240       | 26        | 6.91%   |
| 1-50          | 5         | 1.33%   |
| Unknown       | 4         | 1.06%   |
| More than 240 | 1         | 0.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 307       | 85.04%  |
| 2     | 46        | 12.74%  |
| 0     | 8         | 2.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 228       | 37.44%  |
| Intel                             | 139       | 22.82%  |
| Qualcomm Atheros                  | 104       | 17.08%  |
| Broadcom                          | 33        | 5.42%   |
| MediaTek                          | 31        | 5.09%   |
| Broadcom Limited                  | 14        | 2.3%    |
| Ralink                            | 11        | 1.81%   |
| Xiaomi                            | 7         | 1.15%   |
| Marvell Technology Group          | 7         | 1.15%   |
| TP-Link                           | 4         | 0.66%   |
| ASIX Electronics                  | 4         | 0.66%   |
| Huawei Technologies               | 3         | 0.49%   |
| Hewlett-Packard                   | 3         | 0.49%   |
| Ralink Technology                 | 2         | 0.33%   |
| Qualcomm Atheros Communications   | 2         | 0.33%   |
| OPPO Electronics                  | 2         | 0.33%   |
| JMicron Technology                | 2         | 0.33%   |
| Google                            | 2         | 0.33%   |
| DisplayLink                       | 2         | 0.33%   |
| Samsung Electronics               | 1         | 0.16%   |
| Qualcomm Technologies             | 1         | 0.16%   |
| Lenovo                            | 1         | 0.16%   |
| ICS Advent                        | 1         | 0.16%   |
| HTC (High Tech Computer)          | 1         | 0.16%   |
| Fujitsu Siemens Computers         | 1         | 0.16%   |
| Ericsson Business Mobile Networks | 1         | 0.16%   |
| ASUSTek Computer                  | 1         | 0.16%   |
| Android                           | 1         | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 133       | 19.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 52        | 7.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 25        | 3.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 24        | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 17        | 2.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 16        | 2.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 15        | 2.16%   |
| Intel Wi-Fi 6 AX201                                                     | 15        | 2.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 15        | 2.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 2.01%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 13        | 1.87%   |
| Intel Wireless 8265 / 8275                                              | 13        | 1.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 1.73%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 9         | 1.29%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 1.15%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 8         | 1.15%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 1.01%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 7         | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 6         | 0.86%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 0.86%   |
| Intel Centrino Wireless-N 2230                                          | 6         | 0.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 0.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 6         | 0.86%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 5         | 0.72%   |
| Realtek RTL8125 2.5GbE Controller                                       | 5         | 0.72%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 5         | 0.72%   |
| Intel Wireless 7260                                                     | 5         | 0.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 0.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 0.72%   |
| Broadcom BCM43227 802.11b/g/n                                           | 5         | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 4         | 0.58%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 4         | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 4         | 0.58%   |
| Realtek Killer E2600 GbE Controller                                     | 4         | 0.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.58%   |
| Intel Wireless 3160                                                     | 4         | 0.58%   |
| Intel WiFi Link 5100                                                    | 4         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 137       | 38.38%  |
| Qualcomm Atheros                | 90        | 25.21%  |
| Realtek Semiconductor           | 53        | 14.85%  |
| MediaTek                        | 26        | 7.28%   |
| Broadcom                        | 25        | 7%      |
| Ralink                          | 11        | 3.08%   |
| Broadcom Limited                | 6         | 1.68%   |
| TP-Link                         | 2         | 0.56%   |
| Ralink Technology               | 2         | 0.56%   |
| Qualcomm Atheros Communications | 2         | 0.56%   |
| Qualcomm Technologies           | 1         | 0.28%   |
| Fujitsu Siemens Computers       | 1         | 0.28%   |
| ASUSTek Computer                | 1         | 0.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 25        | 7%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 24        | 6.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 17        | 4.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 16        | 4.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 15        | 4.2%    |
| Intel Wi-Fi 6 AX201                                                     | 15        | 4.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 15        | 4.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 3.92%   |
| Intel Wireless 8265 / 8275                                              | 13        | 3.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 3.36%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 9         | 2.52%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 2.24%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 1.96%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 1.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.68%   |
| Intel Centrino Wireless-N 2230                                          | 6         | 1.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 1.68%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 5         | 1.4%    |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 5         | 1.4%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.4%    |
| Intel Wireless 7260                                                     | 5         | 1.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.4%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 1.4%    |
| Broadcom BCM43227 802.11b/g/n                                           | 5         | 1.4%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 4         | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.12%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.12%   |
| Intel Wireless 3160                                                     | 4         | 1.12%   |
| Intel WiFi Link 5100                                                    | 4         | 1.12%   |
| Intel Centrino Wireless-N 135                                           | 4         | 1.12%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 4         | 1.12%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 4         | 1.12%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.84%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.84%   |
| Intel Wireless 7265                                                     | 3         | 0.84%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 3         | 0.84%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 3         | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 203       | 62.27%  |
| Qualcomm Atheros         | 33        | 10.12%  |
| Intel                    | 31        | 9.51%   |
| Broadcom                 | 11        | 3.37%   |
| Broadcom Limited         | 9         | 2.76%   |
| Xiaomi                   | 7         | 2.15%   |
| Marvell Technology Group | 7         | 2.15%   |
| MediaTek                 | 5         | 1.53%   |
| ASIX Electronics         | 4         | 1.23%   |
| TP-Link                  | 2         | 0.61%   |
| OPPO Electronics         | 2         | 0.61%   |
| JMicron Technology       | 2         | 0.61%   |
| Huawei Technologies      | 2         | 0.61%   |
| Google                   | 2         | 0.61%   |
| DisplayLink              | 2         | 0.61%   |
| Samsung Electronics      | 1         | 0.31%   |
| ICS Advent               | 1         | 0.31%   |
| HTC (High Tech Computer) | 1         | 0.31%   |
| Android                  | 1         | 0.31%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 133       | 40.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 52        | 15.81%  |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 13        | 3.95%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 7         | 2.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 6         | 1.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 1.82%   |
| Realtek RTL8125 2.5GbE Controller                                              | 5         | 1.52%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 4         | 1.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 1.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 4         | 1.22%   |
| Realtek Killer E2600 GbE Controller                                            | 4         | 1.22%   |
| Intel Ethernet Connection (4) I219-LM                                          | 4         | 1.22%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 0.91%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 0.91%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 0.91%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 3         | 0.91%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 0.91%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 3         | 0.91%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 0.91%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.61%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.61%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.61%   |
| OPPO CPH2477                                                                   | 2         | 0.61%   |
| MediaTek Infinix SMART 5                                                       | 2         | 0.61%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.61%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 2         | 0.61%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.61%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.61%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.61%   |
| Intel Ethernet Connection (23) I219-V                                          | 2         | 0.61%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.61%   |
| Huawei E353/E3131                                                              | 2         | 0.61%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 2         | 0.61%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.61%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 2         | 0.61%   |
| TP-Link USB 10/100 LAN                                                         | 1         | 0.3%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.3%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.3%    |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.3%    |
| Realtek PCIe GbE Family Controller                                             | 1         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 347       | 52.18%  |
| Ethernet | 309       | 46.47%  |
| Modem    | 8         | 1.2%    |
| Unknown  | 1         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 286       | 77.93%  |
| Ethernet | 81        | 22.07%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 290       | 81.46%  |
| 1     | 62        | 17.42%  |
| 0     | 4         | 1.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 345       | 96.64%  |
| Yes  | 12        | 3.36%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 103       | 35.89%  |
| IMC Networks                    | 42        | 14.63%  |
| Realtek Semiconductor           | 34        | 11.85%  |
| Qualcomm Atheros Communications | 24        | 8.36%   |
| Lite-On Technology              | 20        | 6.97%   |
| Broadcom                        | 17        | 5.92%   |
| Foxconn / Hon Hai               | 15        | 5.23%   |
| Ralink                          | 8         | 2.79%   |
| Hewlett-Packard                 | 8         | 2.79%   |
| Toshiba                         | 6         | 2.09%   |
| Foxconn International           | 3         | 1.05%   |
| Ralink Technology               | 2         | 0.7%    |
| ASUSTek Computer                | 2         | 0.7%    |
| Realtek                         | 1         | 0.35%   |
| Cambridge Silicon Radio         | 1         | 0.35%   |
| Askey Computer                  | 1         | 0.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 31        | 10.8%   |
| Intel AX201 Bluetooth                             | 22        | 7.67%   |
| Realtek Bluetooth Radio                           | 21        | 7.32%   |
| IMC Networks Wireless_Device                      | 19        | 6.62%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 17        | 5.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 13        | 4.53%   |
| IMC Networks Bluetooth Radio                      | 13        | 4.53%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 10        | 3.48%   |
| Ralink RT3290 Bluetooth                           | 8         | 2.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 8         | 2.79%   |
| Intel AX211 Bluetooth                             | 8         | 2.79%   |
| Realtek  Bluetooth 4.2 Adapter                    | 7         | 2.44%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 6         | 2.09%   |
| Intel AX200 Bluetooth                             | 6         | 2.09%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 6         | 2.09%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter      | 6         | 2.09%   |
| Broadcom HP Portable Valentine                    | 5         | 1.74%   |
| Qualcomm Atheros  Bluetooth Device                | 4         | 1.39%   |
| IMC Networks Bluetooth Device                     | 4         | 1.39%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 4         | 1.39%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR              | 4         | 1.39%   |
| Toshiba Integrated Bluetooth HCI                  | 3         | 1.05%   |
| Realtek RTL8821A Bluetooth                        | 3         | 1.05%   |
| Realtek 802.11ac WLAN Adapter                     | 3         | 1.05%   |
| Qualcomm Atheros Bluetooth                        | 3         | 1.05%   |
| Lite-On Bluetooth Device                          | 3         | 1.05%   |
| Lite-On Atheros AR3012 Bluetooth                  | 3         | 1.05%   |
| Intel Wireless-AC 3168 Bluetooth                  | 3         | 1.05%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 3         | 1.05%   |
| Intel AX210 Bluetooth                             | 3         | 1.05%   |
| Foxconn International BCM43142A0 Bluetooth module | 3         | 1.05%   |
| Foxconn / Hon Hai Wireless_Device                 | 3         | 1.05%   |
| HP Broadcom 2070 Bluetooth Combo                  | 2         | 0.7%    |
| Foxconn / Hon Hai Bluetooth Device                | 2         | 0.7%    |
| Broadcom HP Portable SoftSailing                  | 2         | 0.7%    |
| Broadcom BCM20702A0                               | 2         | 0.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 2         | 0.7%    |
| ASUS BT-270 Bluetooth Adapter                     | 2         | 0.7%    |
| Toshiba RT Bluetooth Radio                        | 1         | 0.35%   |
| Toshiba Integrated Bluetooth                      | 1         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 275       | 63.66%  |
| AMD                   | 83        | 19.21%  |
| Nvidia                | 58        | 13.43%  |
| Razer USA             | 3         | 0.69%   |
| C-Media Electronics   | 3         | 0.69%   |
| Focusrite-Novation    | 2         | 0.46%   |
| Realtek Semiconductor | 1         | 0.23%   |
| Pixart Imaging        | 1         | 0.23%   |
| JMTek                 | 1         | 0.23%   |
| Huawei Technologies   | 1         | 0.23%   |
| Hewlett-Packard       | 1         | 0.23%   |
| GYROCOM C&C           | 1         | 0.23%   |
| ELMCU                 | 1         | 0.23%   |
| Unknown               | 1         | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 47        | 9.11%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 42        | 8.14%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 38        | 7.36%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 21        | 4.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 20        | 3.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 3.88%   |
| AMD FCH Azalia Controller                                                                         | 16        | 3.1%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 15        | 2.91%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 2.33%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 12        | 2.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 2.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 2.33%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 12        | 2.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 1.94%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 1.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 1.74%   |
| AMD Trinity HDMI Audio Controller                                                                 | 9         | 1.74%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 1.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 8         | 1.55%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 1.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 1.55%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 7         | 1.36%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 1.36%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 1.36%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 1.36%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 6         | 1.16%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 6         | 1.16%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.16%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.16%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.16%   |
| Nvidia AD107 High Definition Audio Controller                                                     | 5         | 0.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 0.97%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 0.78%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 0.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 0.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.58%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.58%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 86        | 26.79%  |
| SK hynix                     | 79        | 24.61%  |
| Micron Technology            | 34        | 10.59%  |
| Unknown                      | 27        | 8.41%   |
| Kingston                     | 23        | 7.17%   |
| Ramaxel Technology           | 15        | 4.67%   |
| A-DATA Technology            | 11        | 3.43%   |
| Nanya Technology             | 6         | 1.87%   |
| G.Skill                      | 6         | 1.87%   |
| Crucial                      | 6         | 1.87%   |
| Transcend                    | 3         | 0.93%   |
| Elpida                       | 3         | 0.93%   |
| Unknown (ABCD)               | 2         | 0.62%   |
| Qimonda                      | 2         | 0.62%   |
| GeIL                         | 2         | 0.62%   |
| ASint Technology             | 2         | 0.62%   |
| V-Color                      | 1         | 0.31%   |
| Unknown (D386)               | 1         | 0.31%   |
| Unknown (8CAB)               | 1         | 0.31%   |
| Unifosa                      | 1         | 0.31%   |
| Toshiba                      | 1         | 0.31%   |
| Team                         | 1         | 0.31%   |
| SHARETRONIC                  | 1         | 0.31%   |
| Qumo                         | 1         | 0.31%   |
| ProMos/Mosel Vitelic         | 1         | 0.31%   |
| Patriot Memory (PDP Systems) | 1         | 0.31%   |
| Hikvision                    | 1         | 0.31%   |
| Corsair                      | 1         | 0.31%   |
| Atermiter                    | 1         | 0.31%   |
| Apacer                       | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 1.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.49%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 1.49%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 5         | 1.49%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 1.49%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 5         | 1.49%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.19%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.19%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.19%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.19%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s          | 4         | 1.19%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 4         | 1.19%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.9%    |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1600MT/s        | 3         | 0.9%    |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s            | 3         | 0.9%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.9%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.9%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.9%    |
| Samsung RAM M471A2G44BM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.9%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.9%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.9%    |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 3         | 0.9%    |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s          | 3         | 0.9%    |
| A-DATA RAM AD73I1C1674EV 4GB SODIMM DDR3 1334MT/s                | 3         | 0.9%    |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 2         | 0.6%    |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 0.6%    |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 0.6%    |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 2         | 0.6%    |
| Unknown RAM Module 1024MB SODIMM DDR                             | 2         | 0.6%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 2         | 0.6%    |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s            | 2         | 0.6%    |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.6%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.6%    |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.6%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.6%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.6%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.6%    |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.6%    |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 2         | 0.6%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 2         | 0.6%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 122       | 46.56%  |
| DDR4   | 89        | 33.97%  |
| DDR2   | 17        | 6.49%   |
| DDR5   | 14        | 5.34%   |
| SDRAM  | 7         | 2.67%   |
| LPDDR4 | 7         | 2.67%   |
| LPDDR5 | 2         | 0.76%   |
| LPDDR3 | 2         | 0.76%   |
| DDR    | 2         | 0.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 246       | 93.18%  |
| Row Of Chips | 17        | 6.44%   |
| DIMM         | 1         | 0.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 94        | 31.86%  |
| 8192  | 92        | 31.19%  |
| 2048  | 53        | 17.97%  |
| 16384 | 31        | 10.51%  |
| 1024  | 19        | 6.44%   |
| 32768 | 5         | 1.69%   |
| 512   | 1         | 0.34%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 82        | 28.08%  |
| 3200    | 48        | 16.44%  |
| 2667    | 29        | 9.93%   |
| 1334    | 26        | 8.9%    |
| 2400    | 19        | 6.51%   |
| 1333    | 15        | 5.14%   |
| Unknown | 13        | 4.45%   |
| 4800    | 11        | 3.77%   |
| 667     | 9         | 3.08%   |
| 2133    | 5         | 1.71%   |
| 5600    | 4         | 1.37%   |
| 1067    | 4         | 1.37%   |
| 4267    | 3         | 1.03%   |
| 3266    | 3         | 1.03%   |
| 2048    | 3         | 1.03%   |
| 800     | 3         | 1.03%   |
| 6400    | 2         | 0.68%   |
| 4266    | 2         | 0.68%   |
| 4199    | 2         | 0.68%   |
| 1867    | 2         | 0.68%   |
| 975     | 2         | 0.68%   |
| 533     | 2         | 0.68%   |
| 8400    | 1         | 0.34%   |
| 1066    | 1         | 0.34%   |
| 666     | 1         | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 2         | 28.57%  |
| Hewlett-Packard        | 2         | 28.57%  |
| Xerox                  | 1         | 14.29%  |
| Seiko Epson            | 1         | 14.29%  |
| Panasonic (Matsushita) | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Xerox WorkCentre 6015B               | 1         | 14.29%  |
| Seiko Epson L805 Series              | 1         | 14.29%  |
| Samsung ML-1640 Series Laser Printer | 1         | 14.29%  |
| Samsung M2020 Series                 | 1         | 14.29%  |
| Panasonic (Matsushita) KX-MB1500RU   | 1         | 14.29%  |
| HP LaserJet 1020                     | 1         | 14.29%  |
| HP LaserJet 1018                     | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model          | Notebooks | Percent |
|----------------|-----------|---------|
| HP Scanjet 200 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 71        | 23.2%   |
| IMC Networks                           | 44        | 14.38%  |
| Quanta                                 | 34        | 11.11%  |
| Realtek Semiconductor                  | 25        | 8.17%   |
| Sunplus Innovation Technology          | 16        | 5.23%   |
| Bison Electronics                      | 16        | 5.23%   |
| Suyin                                  | 15        | 4.9%    |
| Cheng Uei Precision Industry (Foxlink) | 14        | 4.58%   |
| Syntek                                 | 10        | 3.27%   |
| Microdia                               | 10        | 3.27%   |
| Sonix Technology                       | 7         | 2.29%   |
| Luxvisions Innotech Limited            | 5         | 1.63%   |
| Lite-On Technology                     | 5         | 1.63%   |
| Silicon Motion                         | 4         | 1.31%   |
| Acer                                   | 4         | 1.31%   |
| Samsung Electronics                    | 3         | 0.98%   |
| Ricoh                                  | 3         | 0.98%   |
| Z-Star Microelectronics                | 2         | 0.65%   |
| Shinetech                              | 2         | 0.65%   |
| Primax Electronics                     | 2         | 0.65%   |
| Logitech                               | 2         | 0.65%   |
| ALi                                    | 2         | 0.65%   |
| Alcor Micro                            | 2         | 0.65%   |
| SiGma Micro                            | 1         | 0.33%   |
| Shine-optics                           | 1         | 0.33%   |
| Nebraska Furniture Mart                | 1         | 0.33%   |
| Lenovo                                 | 1         | 0.33%   |
| Importek                               | 1         | 0.33%   |
| GEMBIRD                                | 1         | 0.33%   |
| BillionPixels                          | 1         | 0.33%   |
| Apple                                  | 1         | 0.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam             | 15        | 4.89%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 10        | 3.26%   |
| Chicony HD WebCam                             | 9         | 2.93%   |
| IMC Networks Integrated Camera                | 8         | 2.61%   |
| Quanta HD User Facing                         | 7         | 2.28%   |
| Sunplus HD WebCam                             | 6         | 1.95%   |
| Quanta HD WebCam                              | 6         | 1.95%   |
| Chicony Integrated Camera                     | 6         | 1.95%   |
| Bison Lenovo Integrated Webcam                | 6         | 1.95%   |
| Syntek Integrated Camera                      | 5         | 1.63%   |
| Realtek Lenovo EasyCamera                     | 5         | 1.63%   |
| Chicony Lenovo EasyCamera                     | 5         | 1.63%   |
| Syntek Lenovo EasyCamera                      | 4         | 1.3%    |
| Suyin 1.3M HD WebCam                          | 4         | 1.3%    |
| Sonix USB2.0 FHD UVC WebCam                   | 4         | 1.3%    |
| Quanta VGA WebCam                             | 4         | 1.3%    |
| Microdia Integrated_Webcam_HD                 | 4         | 1.3%    |
| Lite-On Integrated Camera                     | 4         | 1.3%    |
| Chicony USB2.0 VGA UVC WebCam                 | 4         | 1.3%    |
| Chicony Integrated Camera (1280x720@30)       | 4         | 1.3%    |
| Chicony HP Truevision HD                      | 4         | 1.3%    |
| Chicony Fujitsu Integrated Camera             | 4         | 1.3%    |
| Chicony EasyCamera                            | 4         | 1.3%    |
| Bison Integrated Camera                       | 4         | 1.3%    |
| Suyin HP Truevision HD                        | 3         | 0.98%   |
| Sunplus Asus Webcam                           | 3         | 0.98%   |
| Sonix USB2.0 HD UVC WebCam                    | 3         | 0.98%   |
| Samsung Galaxy series, misc. (MTP mode)       | 3         | 0.98%   |
| Realtek USB Camera                            | 3         | 0.98%   |
| Realtek Integrated_Webcam_HD                  | 3         | 0.98%   |
| Realtek Acer 640 x 480 laptop camera          | 3         | 0.98%   |
| Quanta HP Wide Vision HD Camera               | 3         | 0.98%   |
| Quanta ACER HD User Facing                    | 3         | 0.98%   |
| Microdia Laptop_Integrated_Webcam_HD          | 3         | 0.98%   |
| IMC Networks Lenovo EasyCamera                | 3         | 0.98%   |
| Chicony VGA WebCam                            | 3         | 0.98%   |
| Chicony USB2.0 HD UVC WebCam                  | 3         | 0.98%   |
| Chicony USB2.0 0.3M UVC WebCam                | 3         | 0.98%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 3         | 0.98%   |
| Suyin Integrated_Webcam_HD                    | 2         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 15        | 26.79%  |
| Shenzhen Goodix Technology         | 8         | 14.29%  |
| Synaptics                          | 7         | 12.5%   |
| Elan Microelectronics              | 6         | 10.71%  |
| AuthenTec                          | 6         | 10.71%  |
| Upek                               | 5         | 8.93%   |
| STMicroelectronics                 | 4         | 7.14%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 5.36%   |
| LighTuning Technology              | 2         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 6         | 10.71%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 5         | 8.93%   |
| Shenzhen Goodix  FingerPrint Device                             | 5         | 8.93%   |
| STMicroelectronics Fingerprint Reader                           | 4         | 7.14%   |
| Validity Sensors Fingerprint scanner                            | 3         | 5.36%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 3         | 5.36%   |
| Elan ELAN:ARM-M4                                                | 3         | 5.36%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 3         | 5.36%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 3.57%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 2         | 3.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 3.57%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 3.57%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 2         | 3.57%   |
| Elan ELAN:Fingerprint                                           | 2         | 3.57%   |
| AuthenTec AES2810                                               | 2         | 3.57%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 1.79%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 1.79%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 1         | 1.79%   |
| Synaptics  WBDI                                                 | 1         | 1.79%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 1         | 1.79%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 1         | 1.79%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 1         | 1.79%   |
| Shenzhen Goodix FingerPrint                                     | 1         | 1.79%   |
| Elan WBF Fingerprint Sensor                                     | 1         | 1.79%   |
| AuthenTec Fingerprint Sensor                                    | 1         | 1.79%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 40%     |
| Alcor Micro | 3         | 30%     |
| Upek        | 1         | 10%     |
| O2 Micro    | 1         | 10%     |
| Lenovo      | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 3         | 30%     |
| Broadcom 58200                                             | 2         | 20%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 10%     |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 10%     |
| Lenovo Integrated Smart Card Reader                        | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 10%     |
| Broadcom 5880                                              | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 239       | 64.77%  |
| 1     | 107       | 29%     |
| 2     | 17        | 4.61%   |
| 3     | 4         | 1.08%   |
| 4     | 2         | 0.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 56        | 36.84%  |
| Graphics card            | 43        | 28.29%  |
| Net/wireless             | 21        | 13.82%  |
| Chipcard                 | 9         | 5.92%   |
| Bluetooth                | 9         | 5.92%   |
| Multimedia controller    | 4         | 2.63%   |
| Camera                   | 4         | 2.63%   |
| Communication controller | 3         | 1.97%   |
| Wireless                 | 1         | 0.66%   |
| Modem                    | 1         | 0.66%   |
| Card reader              | 1         | 0.66%   |

