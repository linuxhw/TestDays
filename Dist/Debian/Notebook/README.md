Debian - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Debian.

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

Total: 7620

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | GL552VW                     | [6986ca63da](https://linux-hardware.org/?probe=6986ca63da) | Aug 12, 2023 |
| Acer          | Swift SF314-512             | [7158f3e437](https://linux-hardware.org/?probe=7158f3e437) | Aug 12, 2023 |
| Dell          | Vostro 3500                 | [2ec62f31c9](https://linux-hardware.org/?probe=2ec62f31c9) | Aug 12, 2023 |
| Dell          | Latitude E6430              | [8037585070](https://linux-hardware.org/?probe=8037585070) | Aug 12, 2023 |
| HP            | ZBook 17 G3                 | [475b07d2dc](https://linux-hardware.org/?probe=475b07d2dc) | Aug 12, 2023 |
| Unknown       | Unknown                     | [2e76349d2c](https://linux-hardware.org/?probe=2e76349d2c) | Aug 12, 2023 |
| Unknown       | Unknown                     | [8d7674c3b3](https://linux-hardware.org/?probe=8d7674c3b3) | Aug 11, 2023 |
| HP            | Pavilion dv5                | [41c7682f98](https://linux-hardware.org/?probe=41c7682f98) | Aug 11, 2023 |
| HP            | Pavilion dv5                | [a8f62e42dc](https://linux-hardware.org/?probe=a8f62e42dc) | Aug 11, 2023 |
| Unknown       | Unknown                     | [a064a2d5fd](https://linux-hardware.org/?probe=a064a2d5fd) | Aug 11, 2023 |
| Dell          | Inspiron 3531               | [0384e8a950](https://linux-hardware.org/?probe=0384e8a950) | Aug 11, 2023 |
| Avell High... | A40 LIV                     | [9bc62c7eec](https://linux-hardware.org/?probe=9bc62c7eec) | Aug 11, 2023 |
| HP            | Laptop 15s-eq2xxx           | [e45562b838](https://linux-hardware.org/?probe=e45562b838) | Aug 10, 2023 |
| ASUSTek       | 1005PE                      | [088a155ec9](https://linux-hardware.org/?probe=088a155ec9) | Aug 10, 2023 |
| Acer          | Swift SF314-512             | [e168ac1e62](https://linux-hardware.org/?probe=e168ac1e62) | Aug 10, 2023 |
| PC Special... | NH5xAx                      | [891b5ec398](https://linux-hardware.org/?probe=891b5ec398) | Aug 10, 2023 |
| Lenovo        | ThinkPad T410 25372E6       | [69c4723b51](https://linux-hardware.org/?probe=69c4723b51) | Aug 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S29D00    | [a728658683](https://linux-hardware.org/?probe=a728658683) | Aug 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c87b299407](https://linux-hardware.org/?probe=c87b299407) | Aug 10, 2023 |
| Acer          | Aspire A515-57              | [b95e28ab5d](https://linux-hardware.org/?probe=b95e28ab5d) | Aug 09, 2023 |
| Lenovo        | G460 20041                  | [709445c691](https://linux-hardware.org/?probe=709445c691) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [72655a5d65](https://linux-hardware.org/?probe=72655a5d65) | Aug 08, 2023 |
| Dell          | Inspiron 7537               | [61093a9af1](https://linux-hardware.org/?probe=61093a9af1) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [965f96493c](https://linux-hardware.org/?probe=965f96493c) | Aug 08, 2023 |
| HONOR         | HYM-WXX                     | [6f5e2be121](https://linux-hardware.org/?probe=6f5e2be121) | Aug 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [c06b23398a](https://linux-hardware.org/?probe=c06b23398a) | Aug 08, 2023 |
| Acer          | Aspire E5-573G              | [305061b67e](https://linux-hardware.org/?probe=305061b67e) | Aug 08, 2023 |
| Avell High... | A40 LIV                     | [4022d66d9a](https://linux-hardware.org/?probe=4022d66d9a) | Aug 08, 2023 |
| Lenovo        | ThinkPad T530 2394EN6       | [d348a65379](https://linux-hardware.org/?probe=d348a65379) | Aug 07, 2023 |
| Echips Imp... | NQ15E                       | [7d5e97a545](https://linux-hardware.org/?probe=7d5e97a545) | Aug 07, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [36c52dfe36](https://linux-hardware.org/?probe=36c52dfe36) | Aug 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [543719cf07](https://linux-hardware.org/?probe=543719cf07) | Aug 07, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [be823adc05](https://linux-hardware.org/?probe=be823adc05) | Aug 07, 2023 |
| Acer          | Aspire V5-121               | [4b8b0f132d](https://linux-hardware.org/?probe=4b8b0f132d) | Aug 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E02    | [a3e3489451](https://linux-hardware.org/?probe=a3e3489451) | Aug 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [7e185ae211](https://linux-hardware.org/?probe=7e185ae211) | Aug 07, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [053d461635](https://linux-hardware.org/?probe=053d461635) | Aug 06, 2023 |
| Apple         | MacBook7,1                  | [38d285144e](https://linux-hardware.org/?probe=38d285144e) | Aug 06, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | [55e9e43f37](https://linux-hardware.org/?probe=55e9e43f37) | Aug 06, 2023 |
| Dell          | Inspiron 5547               | [8f33c0cf28](https://linux-hardware.org/?probe=8f33c0cf28) | Aug 06, 2023 |
| HP            | Presario CQ57               | [cd84f6fa01](https://linux-hardware.org/?probe=cd84f6fa01) | Aug 06, 2023 |
| GPU Compan... | GWNR71517                   | [d754d51977](https://linux-hardware.org/?probe=d754d51977) | Aug 06, 2023 |
| Dell          | Latitude E5440              | [326ba9627a](https://linux-hardware.org/?probe=326ba9627a) | Aug 06, 2023 |
| Dell          | Latitude 5290 2-in-1        | [b4cc5c436c](https://linux-hardware.org/?probe=b4cc5c436c) | Aug 06, 2023 |
| HP            | ENVY Laptop 17-ch1xxx       | [89119ae1fc](https://linux-hardware.org/?probe=89119ae1fc) | Aug 06, 2023 |
| HP            | EliteBook 840 G3            | [9c2b1b1da7](https://linux-hardware.org/?probe=9c2b1b1da7) | Aug 06, 2023 |
| Dell          | Inspiron 15 3511            | [217bd70a25](https://linux-hardware.org/?probe=217bd70a25) | Aug 06, 2023 |
| Acer          | Aspire E5-553G              | [39140ff7de](https://linux-hardware.org/?probe=39140ff7de) | Aug 05, 2023 |
| Acer          | Aspire A315-59              | [fc1d6007aa](https://linux-hardware.org/?probe=fc1d6007aa) | Aug 05, 2023 |
| Acer          | Aspire A315-59              | [deff4c99b6](https://linux-hardware.org/?probe=deff4c99b6) | Aug 05, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2f529a830c](https://linux-hardware.org/?probe=2f529a830c) | Aug 05, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [9d00f10bab](https://linux-hardware.org/?probe=9d00f10bab) | Aug 05, 2023 |
| HUAWEI        | MACHD-WXX9                  | [8511f4c245](https://linux-hardware.org/?probe=8511f4c245) | Aug 05, 2023 |
| Acer          | Swift SF314-512             | [ca109297da](https://linux-hardware.org/?probe=ca109297da) | Aug 05, 2023 |
| Sony          | VGN-NS11S_S                 | [8ad31bd20c](https://linux-hardware.org/?probe=8ad31bd20c) | Aug 05, 2023 |
| Shuttle       | DS47D                       | [7d1ceb9b3a](https://linux-hardware.org/?probe=7d1ceb9b3a) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [76662ba2c9](https://linux-hardware.org/?probe=76662ba2c9) | Aug 05, 2023 |
| ASUSTek       | N501JW                      | [e7d254dbe5](https://linux-hardware.org/?probe=e7d254dbe5) | Aug 04, 2023 |
| Dell          | Latitude E6400              | [ca61145546](https://linux-hardware.org/?probe=ca61145546) | Aug 04, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [12948b89f6](https://linux-hardware.org/?probe=12948b89f6) | Aug 04, 2023 |
| HP            | ProBook 640 G2              | [7cacb46425](https://linux-hardware.org/?probe=7cacb46425) | Aug 04, 2023 |
| Dell          | XPS 9320                    | [140f8f8b2e](https://linux-hardware.org/?probe=140f8f8b2e) | Aug 04, 2023 |
| Sony          | VGN-FW373D                  | [535f0edf33](https://linux-hardware.org/?probe=535f0edf33) | Aug 04, 2023 |
| HP            | Lantis                      | [2c917365b3](https://linux-hardware.org/?probe=2c917365b3) | Aug 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [51ad22a795](https://linux-hardware.org/?probe=51ad22a795) | Aug 03, 2023 |
| Dell          | Vostro 3405                 | [db4954c21d](https://linux-hardware.org/?probe=db4954c21d) | Aug 03, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | [6bc628f4e6](https://linux-hardware.org/?probe=6bc628f4e6) | Aug 03, 2023 |
| Google        | Enguarde                    | [663e44ce58](https://linux-hardware.org/?probe=663e44ce58) | Aug 03, 2023 |
| Dell          | Inspiron 5566               | [21d7f13381](https://linux-hardware.org/?probe=21d7f13381) | Aug 03, 2023 |
| Acer          | Nitro AN515-57              | [cef74aa3cb](https://linux-hardware.org/?probe=cef74aa3cb) | Aug 03, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [1317097350](https://linux-hardware.org/?probe=1317097350) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [8036065591](https://linux-hardware.org/?probe=8036065591) | Aug 03, 2023 |
| Samsung       | 305U1A                      | [f65d34a8fb](https://linux-hardware.org/?probe=f65d34a8fb) | Aug 03, 2023 |
| ASUSTek       | 1015BX                      | [4770dbfc22](https://linux-hardware.org/?probe=4770dbfc22) | Aug 02, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a1f99c3e4d](https://linux-hardware.org/?probe=a1f99c3e4d) | Aug 02, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [433a85501a](https://linux-hardware.org/?probe=433a85501a) | Aug 02, 2023 |
| HP            | EliteBook 840 G3            | [0ae0b35097](https://linux-hardware.org/?probe=0ae0b35097) | Aug 02, 2023 |
| Dell          | Vostro 5515                 | [0e031a4729](https://linux-hardware.org/?probe=0e031a4729) | Aug 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | [2d046d70cc](https://linux-hardware.org/?probe=2d046d70cc) | Aug 02, 2023 |
| Samsung       | 300E5M/300E5L               | [d4c5149060](https://linux-hardware.org/?probe=d4c5149060) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [291bf82303](https://linux-hardware.org/?probe=291bf82303) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [7a9c57ad84](https://linux-hardware.org/?probe=7a9c57ad84) | Aug 02, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [dfb33be517](https://linux-hardware.org/?probe=dfb33be517) | Aug 01, 2023 |
| HP            | EliteBook 840 G3            | [b53d4c2fad](https://linux-hardware.org/?probe=b53d4c2fad) | Aug 01, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [d3250ef8d7](https://linux-hardware.org/?probe=d3250ef8d7) | Aug 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | [4a4ac95dcc](https://linux-hardware.org/?probe=4a4ac95dcc) | Aug 01, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | [1e963cc76b](https://linux-hardware.org/?probe=1e963cc76b) | Aug 01, 2023 |
| ASUSTek       | G750JX                      | [06279baf34](https://linux-hardware.org/?probe=06279baf34) | Aug 01, 2023 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | [a9232da3e4](https://linux-hardware.org/?probe=a9232da3e4) | Jul 31, 2023 |
| Lenovo        | Flex 2-14 20404             | [dd24507513](https://linux-hardware.org/?probe=dd24507513) | Jul 31, 2023 |
| Google        | Kevin                       | [ca1037f6ca](https://linux-hardware.org/?probe=ca1037f6ca) | Jul 31, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [961a4eebbd](https://linux-hardware.org/?probe=961a4eebbd) | Jul 31, 2023 |
| Packard Be... | H17HV                       | [de2003d390](https://linux-hardware.org/?probe=de2003d390) | Jul 31, 2023 |
| HP            | ProBook 640 G2              | [9e297e7c8e](https://linux-hardware.org/?probe=9e297e7c8e) | Jul 31, 2023 |
| Dell          | Inspiron 15 3511            | [3ea3ff2535](https://linux-hardware.org/?probe=3ea3ff2535) | Jul 31, 2023 |
| NEC Comput... | PC-VY22GXZCA                | [180d6cf97d](https://linux-hardware.org/?probe=180d6cf97d) | Jul 31, 2023 |
| Apple         | MacBookAir3,1               | [1859204a6f](https://linux-hardware.org/?probe=1859204a6f) | Jul 31, 2023 |
| Apple         | MacBookPro5,5               | [f201460a34](https://linux-hardware.org/?probe=f201460a34) | Jul 30, 2023 |
| Dell          | Inspiron 5547               | [f3de23350d](https://linux-hardware.org/?probe=f3de23350d) | Jul 30, 2023 |
| Dell          | Inspiron 5547               | [3be466c09c](https://linux-hardware.org/?probe=3be466c09c) | Jul 30, 2023 |
| Apple         | MacBookPro6,2               | [c5205f5512](https://linux-hardware.org/?probe=c5205f5512) | Jul 30, 2023 |
| Dell          | Latitude E5270              | [ae07c57989](https://linux-hardware.org/?probe=ae07c57989) | Jul 30, 2023 |
| Apple         | MacBookPro8,2               | [ffda715e5e](https://linux-hardware.org/?probe=ffda715e5e) | Jul 30, 2023 |
| Apple         | MacBookPro9,1               | [3b030b25ac](https://linux-hardware.org/?probe=3b030b25ac) | Jul 30, 2023 |
| Lenovo        | ThinkPad X220 42914XG       | [053a30cc87](https://linux-hardware.org/?probe=053a30cc87) | Jul 30, 2023 |
| HP            | ProBook 640 G2              | [87a4b835cf](https://linux-hardware.org/?probe=87a4b835cf) | Jul 30, 2023 |
| Lenovo        | ThinkPad Edge E430 32543... | [b30651e46f](https://linux-hardware.org/?probe=b30651e46f) | Jul 30, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0YW0... | [3ff995e8b7](https://linux-hardware.org/?probe=3ff995e8b7) | Jul 30, 2023 |
| ASUSTek       | Zephyrus S GX701GX_GX701... | [69da742061](https://linux-hardware.org/?probe=69da742061) | Jul 30, 2023 |
| Lenovo        | ThinkPad X201 3680BF5       | [dd11ccaaad](https://linux-hardware.org/?probe=dd11ccaaad) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [d1a4b2769a](https://linux-hardware.org/?probe=d1a4b2769a) | Jul 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [d1bf55b135](https://linux-hardware.org/?probe=d1bf55b135) | Jul 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [ea8a893b11](https://linux-hardware.org/?probe=ea8a893b11) | Jul 29, 2023 |
| Sony          | SVS13A1Z9RN                 | [533b3018ea](https://linux-hardware.org/?probe=533b3018ea) | Jul 29, 2023 |
| Acer          | Swift SF315-52G             | [aca997f2b5](https://linux-hardware.org/?probe=aca997f2b5) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [ce140941bc](https://linux-hardware.org/?probe=ce140941bc) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [19850c3ad1](https://linux-hardware.org/?probe=19850c3ad1) | Jul 29, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [7207a12cd1](https://linux-hardware.org/?probe=7207a12cd1) | Jul 29, 2023 |
| Dell          | Latitude 5520               | [5151c4275a](https://linux-hardware.org/?probe=5151c4275a) | Jul 29, 2023 |
| VALE          | Notebook Classic C140       | [ec65662265](https://linux-hardware.org/?probe=ec65662265) | Jul 28, 2023 |
| HP            | Pavilion Gaming Laptop      | [b277fcda26](https://linux-hardware.org/?probe=b277fcda26) | Jul 28, 2023 |
| HP            | Victus by Gaming Laptop ... | [7595472fb4](https://linux-hardware.org/?probe=7595472fb4) | Jul 28, 2023 |
| Dell          | Latitude 7480               | [4287f8186f](https://linux-hardware.org/?probe=4287f8186f) | Jul 28, 2023 |
| Chitech Sh... | Tibuta_MasterPad-W100       | [202a9be7b7](https://linux-hardware.org/?probe=202a9be7b7) | Jul 28, 2023 |
| Casper        | EXCALIBUR G770              | [1b416b9f01](https://linux-hardware.org/?probe=1b416b9f01) | Jul 28, 2023 |
| Dell          | Precision 3520              | [bc2e0ff018](https://linux-hardware.org/?probe=bc2e0ff018) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [9cbedced8b](https://linux-hardware.org/?probe=9cbedced8b) | Jul 28, 2023 |
| Dell          | System XPS L702X            | [5e9f83aa10](https://linux-hardware.org/?probe=5e9f83aa10) | Jul 28, 2023 |
| Acer          | Aspire A315-21G             | [0a4e1c4510](https://linux-hardware.org/?probe=0a4e1c4510) | Jul 28, 2023 |
| Apple         | MacBookPro5,2               | [2c6617e2f9](https://linux-hardware.org/?probe=2c6617e2f9) | Jul 27, 2023 |
| Acer          | Extensa 215-32              | [18d32a6c36](https://linux-hardware.org/?probe=18d32a6c36) | Jul 27, 2023 |
| Compaq        | PRESARIOCQ18                | [c528c90b50](https://linux-hardware.org/?probe=c528c90b50) | Jul 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [6e7d094f7f](https://linux-hardware.org/?probe=6e7d094f7f) | Jul 27, 2023 |
| Dell          | Inspiron 5720               | [8674c464bd](https://linux-hardware.org/?probe=8674c464bd) | Jul 27, 2023 |
| Google        | Vortininja                  | [70f9ee30d3](https://linux-hardware.org/?probe=70f9ee30d3) | Jul 27, 2023 |
| Acer          | Aspire A315-23G             | [4d7b874be2](https://linux-hardware.org/?probe=4d7b874be2) | Jul 27, 2023 |
| Fujitsu       | LIFEBOOK U748               | [23d71a87d0](https://linux-hardware.org/?probe=23d71a87d0) | Jul 26, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [0552cb3e44](https://linux-hardware.org/?probe=0552cb3e44) | Jul 26, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [b2dd23136f](https://linux-hardware.org/?probe=b2dd23136f) | Jul 26, 2023 |
| Dell          | XPS 13 7390                 | [0217675942](https://linux-hardware.org/?probe=0217675942) | Jul 26, 2023 |
| Dell          | Precision 3520              | [2502fbaef2](https://linux-hardware.org/?probe=2502fbaef2) | Jul 26, 2023 |
| Acer          | Swift SF314-512             | [856e36fa9c](https://linux-hardware.org/?probe=856e36fa9c) | Jul 26, 2023 |
| Dell          | Vostro 3405                 | [82a990b785](https://linux-hardware.org/?probe=82a990b785) | Jul 26, 2023 |
| Dell          | Vostro 3405                 | [dc97ca175a](https://linux-hardware.org/?probe=dc97ca175a) | Jul 25, 2023 |
| HP            | ProBook 640 G2              | [ae244aab21](https://linux-hardware.org/?probe=ae244aab21) | Jul 25, 2023 |
| Apple         | MacBookPro5,5               | [9cf2abf318](https://linux-hardware.org/?probe=9cf2abf318) | Jul 25, 2023 |
| Google        | Droid                       | [ae803483c2](https://linux-hardware.org/?probe=ae803483c2) | Jul 25, 2023 |
| Dell          | XPS 13 9370                 | [835ca23b88](https://linux-hardware.org/?probe=835ca23b88) | Jul 25, 2023 |
| HP            | Laptop 15-db0xxx            | [f01ec95642](https://linux-hardware.org/?probe=f01ec95642) | Jul 25, 2023 |
| Dell          | XPS 13 9370                 | [321bdf6295](https://linux-hardware.org/?probe=321bdf6295) | Jul 25, 2023 |
| Acer          | Aspire 3610                 | [b40dd6ad17](https://linux-hardware.org/?probe=b40dd6ad17) | Jul 25, 2023 |
| MSI           | Katana GF66 11UG            | [bd45023e8e](https://linux-hardware.org/?probe=bd45023e8e) | Jul 25, 2023 |
| HP            | Laptop 15-fc0xxx            | [5c52eecd16](https://linux-hardware.org/?probe=5c52eecd16) | Jul 25, 2023 |
| SANTECH       | NHx0DB,DE                   | [80aa11a7e8](https://linux-hardware.org/?probe=80aa11a7e8) | Jul 25, 2023 |
| Dell          | Latitude 3420               | [18d920dab2](https://linux-hardware.org/?probe=18d920dab2) | Jul 24, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [fd441fa52f](https://linux-hardware.org/?probe=fd441fa52f) | Jul 24, 2023 |
| ASUSTek       | X541UV                      | [eb0aac9c32](https://linux-hardware.org/?probe=eb0aac9c32) | Jul 24, 2023 |
| Acer          | Nitro AN515-57              | [ae6caf81d7](https://linux-hardware.org/?probe=ae6caf81d7) | Jul 24, 2023 |
| Acer          | Aspire A515-45              | [e1de4fabc7](https://linux-hardware.org/?probe=e1de4fabc7) | Jul 24, 2023 |
| Timi          | A7S                         | [d0bcd36416](https://linux-hardware.org/?probe=d0bcd36416) | Jul 24, 2023 |
| Dell          | Inspiron 15 3511            | [980ed56abe](https://linux-hardware.org/?probe=980ed56abe) | Jul 24, 2023 |
| MSI           | Alpha 15 B5EEK              | [ea2f3666ba](https://linux-hardware.org/?probe=ea2f3666ba) | Jul 23, 2023 |
| Dell          | Latitude E7250              | [4b91b375d4](https://linux-hardware.org/?probe=4b91b375d4) | Jul 23, 2023 |
| Dell          | Latitude 7480               | [acad753aa8](https://linux-hardware.org/?probe=acad753aa8) | Jul 23, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | [a3350e1d80](https://linux-hardware.org/?probe=a3350e1d80) | Jul 23, 2023 |
| Acer          | Aspire A315-21              | [17f482e878](https://linux-hardware.org/?probe=17f482e878) | Jul 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d957d5efe0](https://linux-hardware.org/?probe=d957d5efe0) | Jul 22, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [467cc30f89](https://linux-hardware.org/?probe=467cc30f89) | Jul 22, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [bbd3181f1f](https://linux-hardware.org/?probe=bbd3181f1f) | Jul 22, 2023 |
| HP            | EliteBook 840 G1            | [cafa1082f8](https://linux-hardware.org/?probe=cafa1082f8) | Jul 22, 2023 |
| HP            | Presario CQ57               | [2c1bcfe898](https://linux-hardware.org/?probe=2c1bcfe898) | Jul 22, 2023 |
| Dell          | Inspiron 3558               | [2cad6d3cb7](https://linux-hardware.org/?probe=2cad6d3cb7) | Jul 22, 2023 |
| Dell          | Latitude 5580               | [06c9677557](https://linux-hardware.org/?probe=06c9677557) | Jul 22, 2023 |
| HP            | ENVY Laptop 17-ch2xxx       | [7d88a01e49](https://linux-hardware.org/?probe=7d88a01e49) | Jul 22, 2023 |
| HP            | 635                         | [bb148a8b2b](https://linux-hardware.org/?probe=bb148a8b2b) | Jul 21, 2023 |
| ASUSTek       | K72Jr                       | [cdb9b29f94](https://linux-hardware.org/?probe=cdb9b29f94) | Jul 21, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [031d46c9d0](https://linux-hardware.org/?probe=031d46c9d0) | Jul 21, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | [fc45e9b064](https://linux-hardware.org/?probe=fc45e9b064) | Jul 21, 2023 |
| Acer          | Swift SF314-512             | [d82c78621f](https://linux-hardware.org/?probe=d82c78621f) | Jul 20, 2023 |
| Lenovo        | ThinkPad T520 42435UG       | [820630ba9e](https://linux-hardware.org/?probe=820630ba9e) | Jul 20, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [7527ca0197](https://linux-hardware.org/?probe=7527ca0197) | Jul 20, 2023 |
| HP            | Pavilion Notebook           | [d366e7101c](https://linux-hardware.org/?probe=d366e7101c) | Jul 20, 2023 |
| ASUSTek       | T100TAM                     | [43cb18f0ee](https://linux-hardware.org/?probe=43cb18f0ee) | Jul 20, 2023 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [311144e138](https://linux-hardware.org/?probe=311144e138) | Jul 20, 2023 |
| Shanghai Z... | ZXE CRB                     | [da6bb4265c](https://linux-hardware.org/?probe=da6bb4265c) | Jul 20, 2023 |
| Notebook      | N650DU                      | [c04f4faa06](https://linux-hardware.org/?probe=c04f4faa06) | Jul 19, 2023 |
| Acer          | Swift SF314-43              | [6f00498896](https://linux-hardware.org/?probe=6f00498896) | Jul 19, 2023 |
| HP            | Pavilion 15                 | [e1bfe97e63](https://linux-hardware.org/?probe=e1bfe97e63) | Jul 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [524d69b498](https://linux-hardware.org/?probe=524d69b498) | Jul 19, 2023 |
| Acer          | Aspire 7739Z                | [3e75dec5e0](https://linux-hardware.org/?probe=3e75dec5e0) | Jul 19, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [9672a393c9](https://linux-hardware.org/?probe=9672a393c9) | Jul 19, 2023 |
| HP            | Pavilion 17                 | [bf76e4c333](https://linux-hardware.org/?probe=bf76e4c333) | Jul 19, 2023 |
| Acer          | Extensa 215-22              | [fc3dadd5bc](https://linux-hardware.org/?probe=fc3dadd5bc) | Jul 19, 2023 |
| Acer          | Nitro AN515-57              | [cdad3aa931](https://linux-hardware.org/?probe=cdad3aa931) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [bddb3e26c1](https://linux-hardware.org/?probe=bddb3e26c1) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [a4584a139f](https://linux-hardware.org/?probe=a4584a139f) | Jul 19, 2023 |
| HP            | EliteBook 8570p             | [8e456f1108](https://linux-hardware.org/?probe=8e456f1108) | Jul 18, 2023 |
| Lenovo        | ThinkPad T520 42435UG       | [f789cd31fa](https://linux-hardware.org/?probe=f789cd31fa) | Jul 18, 2023 |
| MSI           | GF63 Thin 11UC              | [3ef8cdcacb](https://linux-hardware.org/?probe=3ef8cdcacb) | Jul 18, 2023 |
| Dell          | Vostro 3500                 | [69cc1eb6f6](https://linux-hardware.org/?probe=69cc1eb6f6) | Jul 18, 2023 |
| Google        | Lillipup                    | [7f7ba76942](https://linux-hardware.org/?probe=7f7ba76942) | Jul 18, 2023 |
| HP            | Pavilion 15                 | [a5485bb7e0](https://linux-hardware.org/?probe=a5485bb7e0) | Jul 18, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [c6da4f3b1e](https://linux-hardware.org/?probe=c6da4f3b1e) | Jul 18, 2023 |
| Lenovo        | ThinkPad L580 20LW000WGE    | [1b210ca778](https://linux-hardware.org/?probe=1b210ca778) | Jul 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [35d510901b](https://linux-hardware.org/?probe=35d510901b) | Jul 18, 2023 |
| HP            | Laptop 17-cp0xxx            | [9d9ff78d29](https://linux-hardware.org/?probe=9d9ff78d29) | Jul 18, 2023 |
| Toshiba       | Satellite L755              | [da4d6e8a5c](https://linux-hardware.org/?probe=da4d6e8a5c) | Jul 18, 2023 |
| MSI           | GF63 Thin 11UC              | [f4fc84ba4b](https://linux-hardware.org/?probe=f4fc84ba4b) | Jul 17, 2023 |
| ASUSTek       | X505BA                      | [fcd96492f0](https://linux-hardware.org/?probe=fcd96492f0) | Jul 17, 2023 |
| Unknown       | TU-142                      | [d62ade82c2](https://linux-hardware.org/?probe=d62ade82c2) | Jul 17, 2023 |
| Dell          | Inspiron 16 7610            | [6d77ef17a0](https://linux-hardware.org/?probe=6d77ef17a0) | Jul 17, 2023 |
| HP            | Pavilion dm1                | [135bb20fbd](https://linux-hardware.org/?probe=135bb20fbd) | Jul 17, 2023 |
| Acer          | Aspire A515-57T             | [dd4a3bf595](https://linux-hardware.org/?probe=dd4a3bf595) | Jul 17, 2023 |
| Acer          | Aspire A315-23G             | [df26ae3dab](https://linux-hardware.org/?probe=df26ae3dab) | Jul 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [ab43e6b8ef](https://linux-hardware.org/?probe=ab43e6b8ef) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [6b52cef555](https://linux-hardware.org/?probe=6b52cef555) | Jul 16, 2023 |
| Dell          | Latitude E6440              | [c1de0cf4d1](https://linux-hardware.org/?probe=c1de0cf4d1) | Jul 16, 2023 |
| Dell          | Latitude E6320              | [0087a8e5cf](https://linux-hardware.org/?probe=0087a8e5cf) | Jul 16, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [65e4fb1356](https://linux-hardware.org/?probe=65e4fb1356) | Jul 16, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | [899c1452e4](https://linux-hardware.org/?probe=899c1452e4) | Jul 16, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | [497e6c5432](https://linux-hardware.org/?probe=497e6c5432) | Jul 16, 2023 |
| HP            | Laptop 14s-dq2xxx           | [cd9bfc68b6](https://linux-hardware.org/?probe=cd9bfc68b6) | Jul 16, 2023 |
| SIRAGON       | LM-C100                     | [daef084233](https://linux-hardware.org/?probe=daef084233) | Jul 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [1625385cef](https://linux-hardware.org/?probe=1625385cef) | Jul 16, 2023 |
| Dell          | Latitude D610               | [791cabd713](https://linux-hardware.org/?probe=791cabd713) | Jul 16, 2023 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [02af27da78](https://linux-hardware.org/?probe=02af27da78) | Jul 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d43ad7594c](https://linux-hardware.org/?probe=d43ad7594c) | Jul 16, 2023 |
| Dell          | Latitude E6330              | [6adb67344f](https://linux-hardware.org/?probe=6adb67344f) | Jul 15, 2023 |
| Lenovo        | ThinkPad X260 20F5S04B00    | [8d3168b6c4](https://linux-hardware.org/?probe=8d3168b6c4) | Jul 15, 2023 |
| Acer          | Aspire R7-371T              | [c4f6270bdb](https://linux-hardware.org/?probe=c4f6270bdb) | Jul 15, 2023 |
| SLIMBOOK      | PROX15-AMD                  | [7e088e838b](https://linux-hardware.org/?probe=7e088e838b) | Jul 15, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1VD0... | [b62ed55325](https://linux-hardware.org/?probe=b62ed55325) | Jul 15, 2023 |
| Dell          | Latitude 7490               | [6811ebe45a](https://linux-hardware.org/?probe=6811ebe45a) | Jul 15, 2023 |
| Apple         | MacBookPro14,3              | [bd2e85e3ce](https://linux-hardware.org/?probe=bd2e85e3ce) | Jul 15, 2023 |
| HUAWEI        | KLVL-WXXW                   | [c76e3df311](https://linux-hardware.org/?probe=c76e3df311) | Jul 14, 2023 |
| Lenovo        | ThinkPad T530 2429HD6       | [1c48702f3c](https://linux-hardware.org/?probe=1c48702f3c) | Jul 14, 2023 |
| Coradir       | Coradir/ES10IS5             | [571080a9d5](https://linux-hardware.org/?probe=571080a9d5) | Jul 14, 2023 |
| Lenovo        | ThinkPad X220 4290FC1       | [d6c0ccb8f1](https://linux-hardware.org/?probe=d6c0ccb8f1) | Jul 14, 2023 |
| HP            | ProBook 640 G2              | [e5efd1b971](https://linux-hardware.org/?probe=e5efd1b971) | Jul 14, 2023 |
| HP            | EliteBook 840 G5            | [02b5ea8525](https://linux-hardware.org/?probe=02b5ea8525) | Jul 14, 2023 |
| HP            | Pavilion dm1                | [3b05c5dc5c](https://linux-hardware.org/?probe=3b05c5dc5c) | Jul 14, 2023 |
| Dell          | Inspiron 15 3511            | [e6d47a005f](https://linux-hardware.org/?probe=e6d47a005f) | Jul 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [e790a3c22f](https://linux-hardware.org/?probe=e790a3c22f) | Jul 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [dae11c33ed](https://linux-hardware.org/?probe=dae11c33ed) | Jul 14, 2023 |
| Google        | Blorb                       | [6bbcc9b8f3](https://linux-hardware.org/?probe=6bbcc9b8f3) | Jul 14, 2023 |
| Lenovo        | ThinkPad X260 20F5S04B00    | [ae8ecf10e7](https://linux-hardware.org/?probe=ae8ecf10e7) | Jul 13, 2023 |
| Lenovo        | V14-IIL 82C4                | [42aba63af0](https://linux-hardware.org/?probe=42aba63af0) | Jul 13, 2023 |
| HP            | 245 G8                      | [07eefc20b0](https://linux-hardware.org/?probe=07eefc20b0) | Jul 13, 2023 |
| Valve         | Jupiter                     | [14f7ea4a48](https://linux-hardware.org/?probe=14f7ea4a48) | Jul 13, 2023 |
| Dell          | XPS 17 9730                 | [b074a1deb3](https://linux-hardware.org/?probe=b074a1deb3) | Jul 13, 2023 |
| Google        | Reks                        | [680b857c0d](https://linux-hardware.org/?probe=680b857c0d) | Jul 13, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [7d2bb16563](https://linux-hardware.org/?probe=7d2bb16563) | Jul 13, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [b054249d03](https://linux-hardware.org/?probe=b054249d03) | Jul 13, 2023 |
| MSI           | Alpha 15 A4DEK              | [9a192c4a0b](https://linux-hardware.org/?probe=9a192c4a0b) | Jul 13, 2023 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [34ec75d601](https://linux-hardware.org/?probe=34ec75d601) | Jul 13, 2023 |
| Dell          | Latitude E6330              | [58ec0684cd](https://linux-hardware.org/?probe=58ec0684cd) | Jul 13, 2023 |
| MSI           | Stealth 16Studio A13VG      | [ab3683571a](https://linux-hardware.org/?probe=ab3683571a) | Jul 13, 2023 |
| Acer          | Aspire A515-52              | [56b110f152](https://linux-hardware.org/?probe=56b110f152) | Jul 13, 2023 |
| Acer          | Aspire A515-52              | [ad9fd505fa](https://linux-hardware.org/?probe=ad9fd505fa) | Jul 13, 2023 |
| Toshiba       | Satellite S75-B             | [ee71e28c8f](https://linux-hardware.org/?probe=ee71e28c8f) | Jul 12, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [603a591fcb](https://linux-hardware.org/?probe=603a591fcb) | Jul 12, 2023 |
| Google        | Lillipup                    | [b7b430e7b4](https://linux-hardware.org/?probe=b7b430e7b4) | Jul 12, 2023 |
| Positivo      | Mobile                      | [463636c0a2](https://linux-hardware.org/?probe=463636c0a2) | Jul 12, 2023 |
| Lenovo        | G570 4334                   | [27a207ead6](https://linux-hardware.org/?probe=27a207ead6) | Jul 12, 2023 |
| Acer          | Aspire 5820TG               | [86cfbf79ce](https://linux-hardware.org/?probe=86cfbf79ce) | Jul 12, 2023 |
| MSI           | FX603                       | [a2c598f9eb](https://linux-hardware.org/?probe=a2c598f9eb) | Jul 12, 2023 |
| MSI           | SUMMIT E13FlipEvo A12MT     | [90faae34f3](https://linux-hardware.org/?probe=90faae34f3) | Jul 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [15c5dec8dc](https://linux-hardware.org/?probe=15c5dec8dc) | Jul 12, 2023 |
| Dell          | XPS 13 9380                 | [e40c69408d](https://linux-hardware.org/?probe=e40c69408d) | Jul 11, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [9fc68063e3](https://linux-hardware.org/?probe=9fc68063e3) | Jul 11, 2023 |
| Dell          | Latitude 7275               | [0647894f7f](https://linux-hardware.org/?probe=0647894f7f) | Jul 11, 2023 |
| Fujitsu       | LIFEBOOK E780               | [ab432dcb0e](https://linux-hardware.org/?probe=ab432dcb0e) | Jul 11, 2023 |
| HP            | ProBook 4730s               | [0b6a6c7260](https://linux-hardware.org/?probe=0b6a6c7260) | Jul 11, 2023 |
| HP            | EliteBook 645 14 inch G9... | [65f4b4e813](https://linux-hardware.org/?probe=65f4b4e813) | Jul 11, 2023 |
| Unknown       | HP Chromebook 14            | [63b183aa51](https://linux-hardware.org/?probe=63b183aa51) | Jul 11, 2023 |
| HP            | EliteBook 1040 G4           | [d7209e7141](https://linux-hardware.org/?probe=d7209e7141) | Jul 11, 2023 |
| Dell          | Inspiron 7560               | [a761bfffd2](https://linux-hardware.org/?probe=a761bfffd2) | Jul 11, 2023 |
| HP            | ZBook 15 G6                 | [47ea5a35cb](https://linux-hardware.org/?probe=47ea5a35cb) | Jul 11, 2023 |
| HP            | EliteBook 1040 G4           | [33aa3fcdbc](https://linux-hardware.org/?probe=33aa3fcdbc) | Jul 10, 2023 |
| Acer          | Aspire 4937                 | [fe9bfd5f77](https://linux-hardware.org/?probe=fe9bfd5f77) | Jul 10, 2023 |
| Acer          | Aspire 4937                 | [d4dadd2e77](https://linux-hardware.org/?probe=d4dadd2e77) | Jul 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [707f0b8eeb](https://linux-hardware.org/?probe=707f0b8eeb) | Jul 10, 2023 |
| HP            | Victus by Laptop 16-e1xx... | [a14d8855bc](https://linux-hardware.org/?probe=a14d8855bc) | Jul 10, 2023 |
| Dell          | OptiPlex 9020               | [3384a64b67](https://linux-hardware.org/?probe=3384a64b67) | Jul 10, 2023 |
| Fujitsu       | LIFEBOOK U727               | [ce095d85c9](https://linux-hardware.org/?probe=ce095d85c9) | Jul 09, 2023 |
| HP            | Pro x2 612 G1 Tablet USA... | [c10c965a51](https://linux-hardware.org/?probe=c10c965a51) | Jul 09, 2023 |
| Acer          | Aspire V3-372T              | [566ff1d23e](https://linux-hardware.org/?probe=566ff1d23e) | Jul 09, 2023 |
| Toshiba       | PORTEGE Z30-C               | [f9d1d19d05](https://linux-hardware.org/?probe=f9d1d19d05) | Jul 09, 2023 |
| MSI           | Modern 14 B11MOU            | [c2e76ab704](https://linux-hardware.org/?probe=c2e76ab704) | Jul 09, 2023 |
| ASUSTek       | VivoBook S14 X430UA         | [fdb15c83de](https://linux-hardware.org/?probe=fdb15c83de) | Jul 09, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [59f06e2baf](https://linux-hardware.org/?probe=59f06e2baf) | Jul 09, 2023 |
| Acer          | Aspire F5-573G              | [10cf2c3aa5](https://linux-hardware.org/?probe=10cf2c3aa5) | Jul 09, 2023 |
| Acer          | Aspire V3-372T              | [f2a9fbdf50](https://linux-hardware.org/?probe=f2a9fbdf50) | Jul 09, 2023 |
| HP            | EliteBook 8560p             | [39fe220963](https://linux-hardware.org/?probe=39fe220963) | Jul 09, 2023 |
| Dell          | Inspiron N4050              | [d5fa70cfda](https://linux-hardware.org/?probe=d5fa70cfda) | Jul 08, 2023 |
| Acer          | TravelMate P215-53          | [5810f4f1f8](https://linux-hardware.org/?probe=5810f4f1f8) | Jul 08, 2023 |
| Apple         | MacBookPro14,3              | [6a739102d0](https://linux-hardware.org/?probe=6a739102d0) | Jul 08, 2023 |
| Dell          | Vostro 15 3535              | [8b67e5b282](https://linux-hardware.org/?probe=8b67e5b282) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [ae008e5343](https://linux-hardware.org/?probe=ae008e5343) | Jul 07, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | [96d1578908](https://linux-hardware.org/?probe=96d1578908) | Jul 07, 2023 |
| HP            | EliteBook 1040 G4           | [cbc100e6b1](https://linux-hardware.org/?probe=cbc100e6b1) | Jul 07, 2023 |
| HP            | EliteBook 1040 G4           | [3177785c7f](https://linux-hardware.org/?probe=3177785c7f) | Jul 07, 2023 |
| HP            | ProBook 430 G1              | [abb4e75faa](https://linux-hardware.org/?probe=abb4e75faa) | Jul 07, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [5d03b4b2ad](https://linux-hardware.org/?probe=5d03b4b2ad) | Jul 07, 2023 |
| Lenovo        | ThinkPad T450s 20BWS0PJ0... | [2345d00757](https://linux-hardware.org/?probe=2345d00757) | Jul 07, 2023 |
| Lenovo        | Flex 2-14 20404             | [93f50211c2](https://linux-hardware.org/?probe=93f50211c2) | Jul 07, 2023 |
| HUAWEI        | BOM-WXX9                    | [905af6686d](https://linux-hardware.org/?probe=905af6686d) | Jul 06, 2023 |
| Dell          | Latitude 7430               | [743d41d534](https://linux-hardware.org/?probe=743d41d534) | Jul 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [37f1a0082b](https://linux-hardware.org/?probe=37f1a0082b) | Jul 06, 2023 |
| Lenovo        | ThinkPad T470 20HES05500    | [12b31081e2](https://linux-hardware.org/?probe=12b31081e2) | Jul 06, 2023 |
| HONOR         | BOHK-WAX9X                  | [95d2ae1051](https://linux-hardware.org/?probe=95d2ae1051) | Jul 06, 2023 |
| HONOR         | BOHK-WAX9X                  | [4f6d2375a3](https://linux-hardware.org/?probe=4f6d2375a3) | Jul 06, 2023 |
| Apple         | MacBookAir7,2               | [c1d387dfc5](https://linux-hardware.org/?probe=c1d387dfc5) | Jul 06, 2023 |
| Dell          | XPS 15 9520                 | [f255433162](https://linux-hardware.org/?probe=f255433162) | Jul 06, 2023 |
| Dell          | Precision M6800             | [4b8d02d04a](https://linux-hardware.org/?probe=4b8d02d04a) | Jul 06, 2023 |
| Dell          | Precision M6800             | [239c3ea2b9](https://linux-hardware.org/?probe=239c3ea2b9) | Jul 06, 2023 |
| Apple         | MacBookPro14,3              | [d6153317bf](https://linux-hardware.org/?probe=d6153317bf) | Jul 05, 2023 |
| Samsung       | 770Z5E/780Z5E               | [2d38e98c83](https://linux-hardware.org/?probe=2d38e98c83) | Jul 05, 2023 |
| Apple         | MacBook5,2                  | [41366bcd54](https://linux-hardware.org/?probe=41366bcd54) | Jul 05, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9d57d6a85f](https://linux-hardware.org/?probe=9d57d6a85f) | Jul 05, 2023 |
| Dell          | Inspiron 15-3565            | [69d01e9a98](https://linux-hardware.org/?probe=69d01e9a98) | Jul 05, 2023 |
| HP            | ProBook 450 G5              | [7a15493631](https://linux-hardware.org/?probe=7a15493631) | Jul 05, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [fc1c7254b3](https://linux-hardware.org/?probe=fc1c7254b3) | Jul 04, 2023 |
| NEC Comput... | PC-VK27MBZCG                | [5db0d02025](https://linux-hardware.org/?probe=5db0d02025) | Jul 04, 2023 |
| MSI           | Creator 15M A9SD            | [84c85a8969](https://linux-hardware.org/?probe=84c85a8969) | Jul 04, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [79c5344e62](https://linux-hardware.org/?probe=79c5344e62) | Jul 04, 2023 |
| Google        | Lick                        | [f2b9397a8b](https://linux-hardware.org/?probe=f2b9397a8b) | Jul 04, 2023 |
| ASUSTek       | G750JX                      | [10f49d74ef](https://linux-hardware.org/?probe=10f49d74ef) | Jul 04, 2023 |
| HP            | EliteBook 6930p             | [b7328dc212](https://linux-hardware.org/?probe=b7328dc212) | Jul 04, 2023 |
| Acer          | Aspire 6930                 | [772d3d7f4a](https://linux-hardware.org/?probe=772d3d7f4a) | Jul 04, 2023 |
| HP            | Pavilion dv6                | [517e6b81c1](https://linux-hardware.org/?probe=517e6b81c1) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [73146ccba2](https://linux-hardware.org/?probe=73146ccba2) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [19a254cdee](https://linux-hardware.org/?probe=19a254cdee) | Jul 03, 2023 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | [18230f7c64](https://linux-hardware.org/?probe=18230f7c64) | Jul 03, 2023 |
| HP            | EliteBook 840 G3            | [ed37dd6278](https://linux-hardware.org/?probe=ed37dd6278) | Jul 03, 2023 |
| Fujitsu       | LIFEBOOK E780               | [2eb6c4356c](https://linux-hardware.org/?probe=2eb6c4356c) | Jul 02, 2023 |
| HONOR         | NMH-WCX9                    | [a8caf9af8e](https://linux-hardware.org/?probe=a8caf9af8e) | Jul 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | [4055aa6f2b](https://linux-hardware.org/?probe=4055aa6f2b) | Jul 02, 2023 |
| Dell          | Latitude 3410               | [11d9814008](https://linux-hardware.org/?probe=11d9814008) | Jul 02, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [4708f2b480](https://linux-hardware.org/?probe=4708f2b480) | Jul 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [54987b03a1](https://linux-hardware.org/?probe=54987b03a1) | Jul 02, 2023 |
| HP            | Laptop 15-dw3xxx            | [3fe182f682](https://linux-hardware.org/?probe=3fe182f682) | Jul 02, 2023 |
| HP            | Pavilion dv7                | [e10b64716f](https://linux-hardware.org/?probe=e10b64716f) | Jul 01, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [b98b20a82c](https://linux-hardware.org/?probe=b98b20a82c) | Jul 01, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [1cc2f89c1a](https://linux-hardware.org/?probe=1cc2f89c1a) | Jul 01, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [6484578658](https://linux-hardware.org/?probe=6484578658) | Jul 01, 2023 |
| HP            | EliteBook 2570p             | [c55a78c98a](https://linux-hardware.org/?probe=c55a78c98a) | Jul 01, 2023 |
| ASUSTek       | X541UV                      | [d0fc2ea58e](https://linux-hardware.org/?probe=d0fc2ea58e) | Jul 01, 2023 |
| Dell          | Inspiron 7720               | [9d8f40247e](https://linux-hardware.org/?probe=9d8f40247e) | Jul 01, 2023 |
| ASUSTek       | X541UV                      | [8b5dc3456b](https://linux-hardware.org/?probe=8b5dc3456b) | Jul 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [0aed51f639](https://linux-hardware.org/?probe=0aed51f639) | Jul 01, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [55bfc9f544](https://linux-hardware.org/?probe=55bfc9f544) | Jul 01, 2023 |
| Apple         | MacBookPro14,3              | [4a51b35cb8](https://linux-hardware.org/?probe=4a51b35cb8) | Jul 01, 2023 |
| Dell          | Latitude 3500               | [8e82f9abda](https://linux-hardware.org/?probe=8e82f9abda) | Jul 01, 2023 |
| HUAWEI        | BOM-WXX9                    | [4d4d992cb0](https://linux-hardware.org/?probe=4d4d992cb0) | Jul 01, 2023 |
| HP            | 255 G8 Notebook PC          | [3c3ddffa8b](https://linux-hardware.org/?probe=3c3ddffa8b) | Jul 01, 2023 |
| Acer          | Aspire V5-123               | [8507833f22](https://linux-hardware.org/?probe=8507833f22) | Jul 01, 2023 |
| ASUSTek       | K501UX                      | [a7fb172b7d](https://linux-hardware.org/?probe=a7fb172b7d) | Jun 30, 2023 |
| Apple         | MacBookAir7,2               | [cb1bcce659](https://linux-hardware.org/?probe=cb1bcce659) | Jun 30, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [39a8ee4269](https://linux-hardware.org/?probe=39a8ee4269) | Jun 30, 2023 |
| HP            | EliteBook 850 G1            | [a5f3a5ad14](https://linux-hardware.org/?probe=a5f3a5ad14) | Jun 30, 2023 |
| Lenovo        | ThinkPad T495 20NK000XBR    | [2b5e40efaa](https://linux-hardware.org/?probe=2b5e40efaa) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430s 23554L7      | [501b0860c8](https://linux-hardware.org/?probe=501b0860c8) | Jun 30, 2023 |
| Dell          | G3 3590                     | [5c7312fed9](https://linux-hardware.org/?probe=5c7312fed9) | Jun 30, 2023 |
| Lenovo        | ThinkPad L512 44444NG       | [300a79aa88](https://linux-hardware.org/?probe=300a79aa88) | Jun 30, 2023 |
| ASUSTek       | T100TA                      | [921821fda8](https://linux-hardware.org/?probe=921821fda8) | Jun 30, 2023 |
| ASUSTek       | K52F                        | [98e9b448c7](https://linux-hardware.org/?probe=98e9b448c7) | Jun 30, 2023 |
| Acer          | Aspire V3-772               | [0fae87e118](https://linux-hardware.org/?probe=0fae87e118) | Jun 29, 2023 |
| Acer          | TravelMate P449-G2-M        | [b9291d6951](https://linux-hardware.org/?probe=b9291d6951) | Jun 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | [62ff10cadc](https://linux-hardware.org/?probe=62ff10cadc) | Jun 29, 2023 |
| Lenovo        | ThinkPad T440p 2000CT0      | [10c852dc38](https://linux-hardware.org/?probe=10c852dc38) | Jun 29, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [25a1aaf938](https://linux-hardware.org/?probe=25a1aaf938) | Jun 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | [a50310948a](https://linux-hardware.org/?probe=a50310948a) | Jun 29, 2023 |
| HP            | Pavilion dv6                | [b6c2bcb025](https://linux-hardware.org/?probe=b6c2bcb025) | Jun 29, 2023 |
| Dell          | Latitude 3500               | [e1831984f8](https://linux-hardware.org/?probe=e1831984f8) | Jun 28, 2023 |
| Dell          | Latitude 7370               | [cb11921012](https://linux-hardware.org/?probe=cb11921012) | Jun 28, 2023 |
| Aquarius      | NS585                       | [52a07593c9](https://linux-hardware.org/?probe=52a07593c9) | Jun 28, 2023 |
| HP            | Pavilion dv6                | [7fe9e439c0](https://linux-hardware.org/?probe=7fe9e439c0) | Jun 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [4a4411b820](https://linux-hardware.org/?probe=4a4411b820) | Jun 28, 2023 |
| Aquarius      | NS585                       | [b2f86e98f9](https://linux-hardware.org/?probe=b2f86e98f9) | Jun 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [2ed2f000d3](https://linux-hardware.org/?probe=2ed2f000d3) | Jun 28, 2023 |
| ASUSTek       | ZenBook Pro 15 UX550GEX_... | [56eef68e89](https://linux-hardware.org/?probe=56eef68e89) | Jun 28, 2023 |
| Acer          | Aspire A315-23G             | [1c07c9f0b8](https://linux-hardware.org/?probe=1c07c9f0b8) | Jun 28, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [ab4772fd2e](https://linux-hardware.org/?probe=ab4772fd2e) | Jun 28, 2023 |
| Lenovo        | ThinkPad X280 20KF001RUK    | [a1da72b9a5](https://linux-hardware.org/?probe=a1da72b9a5) | Jun 27, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [8112f38f33](https://linux-hardware.org/?probe=8112f38f33) | Jun 27, 2023 |
| Coradir       | Coradir/ES10IS5             | [d2d1f5b2a5](https://linux-hardware.org/?probe=d2d1f5b2a5) | Jun 27, 2023 |
| HP            | Laptop 15-ef1xxx            | [765d0708eb](https://linux-hardware.org/?probe=765d0708eb) | Jun 26, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | [5a062be874](https://linux-hardware.org/?probe=5a062be874) | Jun 26, 2023 |
| ASUSTek       | K53SJ                       | [fe211e4239](https://linux-hardware.org/?probe=fe211e4239) | Jun 26, 2023 |
| HP            | EliteBook 835 13 inch G1... | [e43818af40](https://linux-hardware.org/?probe=e43818af40) | Jun 26, 2023 |
| LG Electro... | 17Z90R-G.AD79F              | [0d641b84fe](https://linux-hardware.org/?probe=0d641b84fe) | Jun 26, 2023 |
| Acer          | Aspire A515-56              | [0ee45fd3e8](https://linux-hardware.org/?probe=0ee45fd3e8) | Jun 26, 2023 |
| Coradir       | Coradir/ES10IS5             | [d6a1e61945](https://linux-hardware.org/?probe=d6a1e61945) | Jun 26, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [b8a3042b9d](https://linux-hardware.org/?probe=b8a3042b9d) | Jun 26, 2023 |
| Aquarius      | NS585                       | [25af22ec30](https://linux-hardware.org/?probe=25af22ec30) | Jun 26, 2023 |
| Aquarius      | NS585                       | [8e957a70f0](https://linux-hardware.org/?probe=8e957a70f0) | Jun 26, 2023 |
| Aquarius      | NS585                       | [bb09ae1f8d](https://linux-hardware.org/?probe=bb09ae1f8d) | Jun 26, 2023 |
| HP            | OMEN by Laptop              | [07d9cc6d71](https://linux-hardware.org/?probe=07d9cc6d71) | Jun 26, 2023 |
| Apple         | MacBook2,1                  | [f5c0a2fd49](https://linux-hardware.org/?probe=f5c0a2fd49) | Jun 26, 2023 |
| HP            | Compaq Mini 110c-1100       | [0dc147bd7c](https://linux-hardware.org/?probe=0dc147bd7c) | Jun 26, 2023 |
| Lenovo        | ThinkPad T430 34766TT       | [06ad7b4a25](https://linux-hardware.org/?probe=06ad7b4a25) | Jun 26, 2023 |
| Dell          | XPS 15 7590                 | [dfc817892b](https://linux-hardware.org/?probe=dfc817892b) | Jun 26, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [ed89cd0d05](https://linux-hardware.org/?probe=ed89cd0d05) | Jun 26, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [62665eec25](https://linux-hardware.org/?probe=62665eec25) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0a233c34b3](https://linux-hardware.org/?probe=0a233c34b3) | Jun 26, 2023 |
| Dell          | XPS 15 9530                 | [9c925666a5](https://linux-hardware.org/?probe=9c925666a5) | Jun 26, 2023 |
| Dell          | XPS 15 9530                 | [ea814b3f7b](https://linux-hardware.org/?probe=ea814b3f7b) | Jun 26, 2023 |
| Avell High... | A70 HYB                     | [3ccdaf3c82](https://linux-hardware.org/?probe=3ccdaf3c82) | Jun 26, 2023 |
| ASUSTek       | E403SA                      | [bdc47269c3](https://linux-hardware.org/?probe=bdc47269c3) | Jun 25, 2023 |
| HP            | Laptop 14-dq0xxx            | [695dd94347](https://linux-hardware.org/?probe=695dd94347) | Jun 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [cee2bb11dc](https://linux-hardware.org/?probe=cee2bb11dc) | Jun 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | [14cc9e067f](https://linux-hardware.org/?probe=14cc9e067f) | Jun 25, 2023 |
| Dell          | Inspiron 5593               | [06f1256f88](https://linux-hardware.org/?probe=06f1256f88) | Jun 25, 2023 |
| Dell          | Latitude E6430              | [be9b6c75da](https://linux-hardware.org/?probe=be9b6c75da) | Jun 25, 2023 |
| Toshiba       | IS 1413G                    | [a87db20468](https://linux-hardware.org/?probe=a87db20468) | Jun 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [a7df01b153](https://linux-hardware.org/?probe=a7df01b153) | Jun 24, 2023 |
| Dell          | Inspiron 1720               | [60c2ef3b92](https://linux-hardware.org/?probe=60c2ef3b92) | Jun 24, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [fe084d5ddb](https://linux-hardware.org/?probe=fe084d5ddb) | Jun 24, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | [a8420bc87d](https://linux-hardware.org/?probe=a8420bc87d) | Jun 24, 2023 |
| Acer          | Aspire VN7-591G             | [356b066ca9](https://linux-hardware.org/?probe=356b066ca9) | Jun 24, 2023 |
| Google        | Kip                         | [4e1bfd359e](https://linux-hardware.org/?probe=4e1bfd359e) | Jun 24, 2023 |
| HP            | EliteBook 830 G5            | [2b61a56610](https://linux-hardware.org/?probe=2b61a56610) | Jun 24, 2023 |
| Dell          | XPS 15 9570                 | [2c09eb930c](https://linux-hardware.org/?probe=2c09eb930c) | Jun 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [3cc7c77a76](https://linux-hardware.org/?probe=3cc7c77a76) | Jun 23, 2023 |
| HP            | 8470p EliteBook             | [da3719515b](https://linux-hardware.org/?probe=da3719515b) | Jun 23, 2023 |
| Acer          | Predator PH315-54           | [46d748a0a1](https://linux-hardware.org/?probe=46d748a0a1) | Jun 23, 2023 |
| Lenovo        | Edge 15 80H1                | [aff25effc2](https://linux-hardware.org/?probe=aff25effc2) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | [6d8c00ff02](https://linux-hardware.org/?probe=6d8c00ff02) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | [1c1a2724f4](https://linux-hardware.org/?probe=1c1a2724f4) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [3cdf59359c](https://linux-hardware.org/?probe=3cdf59359c) | Jun 23, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [5298e132fc](https://linux-hardware.org/?probe=5298e132fc) | Jun 23, 2023 |
| Acer          | Aspire A515-55              | [bf6de06fb9](https://linux-hardware.org/?probe=bf6de06fb9) | Jun 23, 2023 |
| VIT           | P2423                       | [19242b2ddb](https://linux-hardware.org/?probe=19242b2ddb) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | [b5576af3f8](https://linux-hardware.org/?probe=b5576af3f8) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | [911336b572](https://linux-hardware.org/?probe=911336b572) | Jun 23, 2023 |
| Lenovo        | ThinkPad X230 2325SRQ       | [fd42553eea](https://linux-hardware.org/?probe=fd42553eea) | Jun 22, 2023 |
| ASUSTek       | X45U                        | [63a491a160](https://linux-hardware.org/?probe=63a491a160) | Jun 22, 2023 |
| Dell          | Inspiron 1525               | [1cdf3502e8](https://linux-hardware.org/?probe=1cdf3502e8) | Jun 21, 2023 |
| Dell          | Inspiron 1525               | [7bbc89ec0f](https://linux-hardware.org/?probe=7bbc89ec0f) | Jun 21, 2023 |
| Dell          | Latitude E5550              | [72f4d53246](https://linux-hardware.org/?probe=72f4d53246) | Jun 21, 2023 |
| Apple         | MacBookPro10,1              | [9841bf505c](https://linux-hardware.org/?probe=9841bf505c) | Jun 21, 2023 |
| Apple         | MacBookAir7,2               | [9f3829c99f](https://linux-hardware.org/?probe=9f3829c99f) | Jun 21, 2023 |
| Apple         | MacBookAir7,2               | [379e3473e2](https://linux-hardware.org/?probe=379e3473e2) | Jun 21, 2023 |
| Apple         | MacBookAir7,2               | [8a2a9fd293](https://linux-hardware.org/?probe=8a2a9fd293) | Jun 21, 2023 |
| Dell          | Inspiron 5570               | [d661316023](https://linux-hardware.org/?probe=d661316023) | Jun 21, 2023 |
| Lenovo        | IdeaPadFlex 15 20309        | [76fbd356a0](https://linux-hardware.org/?probe=76fbd356a0) | Jun 21, 2023 |
| Dell          | Latitude E5550              | [e1fdcf84b3](https://linux-hardware.org/?probe=e1fdcf84b3) | Jun 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [8a61f834dd](https://linux-hardware.org/?probe=8a61f834dd) | Jun 21, 2023 |
| Dell          | Vostro 5490                 | [10d1aeda8b](https://linux-hardware.org/?probe=10d1aeda8b) | Jun 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [291796e3e4](https://linux-hardware.org/?probe=291796e3e4) | Jun 21, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [dc5a63aacc](https://linux-hardware.org/?probe=dc5a63aacc) | Jun 20, 2023 |
| Apple         | MacBook6,1                  | [c7e1912b55](https://linux-hardware.org/?probe=c7e1912b55) | Jun 20, 2023 |
| Apple         | MacBook5,2                  | [53f708517b](https://linux-hardware.org/?probe=53f708517b) | Jun 20, 2023 |
| Google        | Stout                       | [cb67ad655e](https://linux-hardware.org/?probe=cb67ad655e) | Jun 20, 2023 |
| Packard Be... | EasyNote TE11HC             | [6bbc56b36c](https://linux-hardware.org/?probe=6bbc56b36c) | Jun 20, 2023 |
| Dell          | Latitude E7450              | [4760bb7306](https://linux-hardware.org/?probe=4760bb7306) | Jun 20, 2023 |
| Apple         | MacBookPro5,5               | [16c4045c3b](https://linux-hardware.org/?probe=16c4045c3b) | Jun 20, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [c3f77cf346](https://linux-hardware.org/?probe=c3f77cf346) | Jun 20, 2023 |
| Acer          | TravelMate P449-G2-M        | [98626bde6c](https://linux-hardware.org/?probe=98626bde6c) | Jun 20, 2023 |
| Dell          | Latitude 3410               | [1e0348842a](https://linux-hardware.org/?probe=1e0348842a) | Jun 19, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [a0862de551](https://linux-hardware.org/?probe=a0862de551) | Jun 19, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [3cfd8a448c](https://linux-hardware.org/?probe=3cfd8a448c) | Jun 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [42fd301e8b](https://linux-hardware.org/?probe=42fd301e8b) | Jun 19, 2023 |
| Lenovo        | IdeaPad S340-15APITouch ... | [fe617b45f8](https://linux-hardware.org/?probe=fe617b45f8) | Jun 19, 2023 |
| Toshiba       | TECRA R850                  | [c40116d0de](https://linux-hardware.org/?probe=c40116d0de) | Jun 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d8d9101ef6](https://linux-hardware.org/?probe=d8d9101ef6) | Jun 19, 2023 |
| Packard Be... | EasyNote TE11HC             | [33785e2493](https://linux-hardware.org/?probe=33785e2493) | Jun 18, 2023 |
| Dell          | Latitude E7450              | [addda016c8](https://linux-hardware.org/?probe=addda016c8) | Jun 18, 2023 |
| HP            | EliteBook 2530p             | [7d246caf6f](https://linux-hardware.org/?probe=7d246caf6f) | Jun 18, 2023 |
| HP            | EliteBook 8440p             | [4b1b2457a4](https://linux-hardware.org/?probe=4b1b2457a4) | Jun 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [e4c418382a](https://linux-hardware.org/?probe=e4c418382a) | Jun 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [26b4c05332](https://linux-hardware.org/?probe=26b4c05332) | Jun 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S10T0... | [a3dd392c51](https://linux-hardware.org/?probe=a3dd392c51) | Jun 17, 2023 |
| Dell          | Latitude E6400              | [0f8aca3e72](https://linux-hardware.org/?probe=0f8aca3e72) | Jun 17, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [d9e1222bc3](https://linux-hardware.org/?probe=d9e1222bc3) | Jun 17, 2023 |
| Dell          | Precision M2800             | [e9f259595a](https://linux-hardware.org/?probe=e9f259595a) | Jun 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [9cdeeb06de](https://linux-hardware.org/?probe=9cdeeb06de) | Jun 16, 2023 |
| Acer          | Aspire E1-571               | [19e270cab0](https://linux-hardware.org/?probe=19e270cab0) | Jun 16, 2023 |
| Acer          | Aspire E1-571               | [e4b27c6a92](https://linux-hardware.org/?probe=e4b27c6a92) | Jun 16, 2023 |
| Lenovo        | ThinkPad P51 20HJS1SF00     | [664ae7a0f2](https://linux-hardware.org/?probe=664ae7a0f2) | Jun 16, 2023 |
| Dell          | Latitude D620               | [8dc25931d7](https://linux-hardware.org/?probe=8dc25931d7) | Jun 16, 2023 |
| Dell          | Latitude D620               | [819f346812](https://linux-hardware.org/?probe=819f346812) | Jun 16, 2023 |
| HONOR         | NMH-WCX9                    | [ec1b8c4ef4](https://linux-hardware.org/?probe=ec1b8c4ef4) | Jun 16, 2023 |
| Dell          | Latitude E6400              | [7c59595887](https://linux-hardware.org/?probe=7c59595887) | Jun 16, 2023 |
| HUAWEI        | NBD-WXX9                    | [b9bf7ea3c2](https://linux-hardware.org/?probe=b9bf7ea3c2) | Jun 16, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [b05e4ee752](https://linux-hardware.org/?probe=b05e4ee752) | Jun 15, 2023 |
| HP            | Laptop 14-cm0xxx            | [67ed3346c2](https://linux-hardware.org/?probe=67ed3346c2) | Jun 15, 2023 |
| Unknown       | Unknown                     | [f1294224ee](https://linux-hardware.org/?probe=f1294224ee) | Jun 15, 2023 |
| HP            | Laptop 14-cm0xxx            | [07f1089ee7](https://linux-hardware.org/?probe=07f1089ee7) | Jun 15, 2023 |
| HUAWEI        | NBD-WXX9                    | [b55662cc58](https://linux-hardware.org/?probe=b55662cc58) | Jun 15, 2023 |
| Unknown       | Unknown                     | [9b8a05d0f9](https://linux-hardware.org/?probe=9b8a05d0f9) | Jun 15, 2023 |
| Acer          | TravelMate 8172             | [569fde2487](https://linux-hardware.org/?probe=569fde2487) | Jun 15, 2023 |
| Apple         | MacBookAir7,2               | [2db615249d](https://linux-hardware.org/?probe=2db615249d) | Jun 15, 2023 |
| Apple         | MacBookAir7,2               | [138e2807af](https://linux-hardware.org/?probe=138e2807af) | Jun 15, 2023 |
| Apple         | MacBookAir7,1               | [5d8061c350](https://linux-hardware.org/?probe=5d8061c350) | Jun 15, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [aafa9250df](https://linux-hardware.org/?probe=aafa9250df) | Jun 15, 2023 |
| Medion        | E6214                       | [71b2e69534](https://linux-hardware.org/?probe=71b2e69534) | Jun 15, 2023 |
| Lenovo        | B590 20206                  | [f7e4f16796](https://linux-hardware.org/?probe=f7e4f16796) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [eb0ba3c881](https://linux-hardware.org/?probe=eb0ba3c881) | Jun 15, 2023 |
| Toshiba       | Satellite L45-B             | [4cc6199522](https://linux-hardware.org/?probe=4cc6199522) | Jun 15, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [65298dde46](https://linux-hardware.org/?probe=65298dde46) | Jun 14, 2023 |
| HONOR         | BBR-WAX9                    | [b980e4f162](https://linux-hardware.org/?probe=b980e4f162) | Jun 14, 2023 |
| Dell          | Latitude 5480               | [677cb87f98](https://linux-hardware.org/?probe=677cb87f98) | Jun 14, 2023 |
| Dell          | XPS M1530                   | [252d777fa0](https://linux-hardware.org/?probe=252d777fa0) | Jun 14, 2023 |
| Acer          | TravelMate 5742Z            | [abf5dbde31](https://linux-hardware.org/?probe=abf5dbde31) | Jun 14, 2023 |
| Apple         | MacBookPro5,5               | [b639a64b45](https://linux-hardware.org/?probe=b639a64b45) | Jun 14, 2023 |
| Dell          | Latitude 7480               | [375fb09bca](https://linux-hardware.org/?probe=375fb09bca) | Jun 14, 2023 |
| Acer          | Aspire A315-23G             | [18a5adccb6](https://linux-hardware.org/?probe=18a5adccb6) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [e073b99b63](https://linux-hardware.org/?probe=e073b99b63) | Jun 13, 2023 |
| HP            | Pavilion Notebook           | [f444f44a49](https://linux-hardware.org/?probe=f444f44a49) | Jun 13, 2023 |
| Samsung       | 750XED                      | [8997330d6a](https://linux-hardware.org/?probe=8997330d6a) | Jun 13, 2023 |
| Fujitsu       | LIFEBOOK E780               | [b8631b65c4](https://linux-hardware.org/?probe=b8631b65c4) | Jun 13, 2023 |
| HP            | Pavilion dv7                | [3c113d457b](https://linux-hardware.org/?probe=3c113d457b) | Jun 13, 2023 |
| Sony          | SVE11116FGW                 | [4c34707bef](https://linux-hardware.org/?probe=4c34707bef) | Jun 13, 2023 |
| Sony          | SVE11116FGW                 | [a048cbcdeb](https://linux-hardware.org/?probe=a048cbcdeb) | Jun 13, 2023 |
| Acer          | TravelMate P449-G2-M        | [97b6ba8bd6](https://linux-hardware.org/?probe=97b6ba8bd6) | Jun 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [f578df0eb9](https://linux-hardware.org/?probe=f578df0eb9) | Jun 13, 2023 |
| Dell          | Inspiron 1521               | [b4a1eae7be](https://linux-hardware.org/?probe=b4a1eae7be) | Jun 12, 2023 |
| Apple         | MacBookPro12,1              | [a515b0dbf7](https://linux-hardware.org/?probe=a515b0dbf7) | Jun 12, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | [20b91b813f](https://linux-hardware.org/?probe=20b91b813f) | Jun 12, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [675f082570](https://linux-hardware.org/?probe=675f082570) | Jun 12, 2023 |
| HP            | EliteBook 840 G5            | [331ac1da01](https://linux-hardware.org/?probe=331ac1da01) | Jun 12, 2023 |
| Hampoo        | Cherry Trail CR V200        | [d2ee0bc234](https://linux-hardware.org/?probe=d2ee0bc234) | Jun 12, 2023 |
| HP            | EliteBook 2530p             | [8e5a09ba99](https://linux-hardware.org/?probe=8e5a09ba99) | Jun 12, 2023 |
| Fujitsu       | LIFEBOOK A514               | [45b16c1cdf](https://linux-hardware.org/?probe=45b16c1cdf) | Jun 12, 2023 |
| Fujitsu       | LIFEBOOK A514               | [1da963b3f4](https://linux-hardware.org/?probe=1da963b3f4) | Jun 12, 2023 |
| Dell          | Latitude 3320               | [e467a71dac](https://linux-hardware.org/?probe=e467a71dac) | Jun 12, 2023 |
| Dell          | Latitude 3320               | [ec4f04b63e](https://linux-hardware.org/?probe=ec4f04b63e) | Jun 12, 2023 |
| MSI           | GE62 6QC                    | [5581a5c589](https://linux-hardware.org/?probe=5581a5c589) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | [7a4183e095](https://linux-hardware.org/?probe=7a4183e095) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | [2051db7014](https://linux-hardware.org/?probe=2051db7014) | Jun 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [9ed0a99c90](https://linux-hardware.org/?probe=9ed0a99c90) | Jun 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [5bc42066ca](https://linux-hardware.org/?probe=5bc42066ca) | Jun 12, 2023 |
| Dell          | Inspiron 5515               | [9ac2f1ed7e](https://linux-hardware.org/?probe=9ac2f1ed7e) | Jun 12, 2023 |
| Dell          | Inspiron 3501               | [8e9562dd9a](https://linux-hardware.org/?probe=8e9562dd9a) | Jun 11, 2023 |
| Lenovo        | ThinkPad T420s 4175A16      | [3d23465019](https://linux-hardware.org/?probe=3d23465019) | Jun 11, 2023 |
| Lenovo        | G565 4385                   | [2fd61f3fc5](https://linux-hardware.org/?probe=2fd61f3fc5) | Jun 11, 2023 |
| MSI           | Prestige 15 A10SC           | [ceb7680734](https://linux-hardware.org/?probe=ceb7680734) | Jun 11, 2023 |
| ASUSTek       | ZenBook UX334FAC_UX334FA    | [ba762c6d80](https://linux-hardware.org/?probe=ba762c6d80) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [8b88702b69](https://linux-hardware.org/?probe=8b88702b69) | Jun 11, 2023 |
| Dell          | Latitude 7440               | [f63ada6c61](https://linux-hardware.org/?probe=f63ada6c61) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | [a62438daef](https://linux-hardware.org/?probe=a62438daef) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | [fab548c31e](https://linux-hardware.org/?probe=fab548c31e) | Jun 10, 2023 |
| IT Channel... | N8xEJEK                     | [51a7e3f5b4](https://linux-hardware.org/?probe=51a7e3f5b4) | Jun 10, 2023 |
| Acidanther... | MacBookPro15,2              | [fb30b2eb35](https://linux-hardware.org/?probe=fb30b2eb35) | Jun 10, 2023 |
| Intel         | powered classmate PC        | [e530f037c6](https://linux-hardware.org/?probe=e530f037c6) | Jun 09, 2023 |
| Dell          | Latitude 5480               | [5b3fb0b4f8](https://linux-hardware.org/?probe=5b3fb0b4f8) | Jun 09, 2023 |
| Digibras      | NH4CU03                     | [c66d30943e](https://linux-hardware.org/?probe=c66d30943e) | Jun 09, 2023 |
| Acer          | TravelMate P215-53          | [9536bf547a](https://linux-hardware.org/?probe=9536bf547a) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK U7411              | [ab35c95b72](https://linux-hardware.org/?probe=ab35c95b72) | Jun 09, 2023 |
| Acer          | TravelMate P449-G2-M        | [6b42200bee](https://linux-hardware.org/?probe=6b42200bee) | Jun 09, 2023 |
| HP            | G42                         | [fe8d2be276](https://linux-hardware.org/?probe=fe8d2be276) | Jun 08, 2023 |
| HP            | Laptop 14-cm0xxx            | [f1100ce875](https://linux-hardware.org/?probe=f1100ce875) | Jun 08, 2023 |
| HP            | G42                         | [4f33462d46](https://linux-hardware.org/?probe=4f33462d46) | Jun 08, 2023 |
| Acer          | TravelMate P449-G2-M        | [0fa009ad04](https://linux-hardware.org/?probe=0fa009ad04) | Jun 08, 2023 |
| MSI           | GE60 2PL                    | [e1d118e2d2](https://linux-hardware.org/?probe=e1d118e2d2) | Jun 08, 2023 |
| HP            | G62                         | [fb9522ceac](https://linux-hardware.org/?probe=fb9522ceac) | Jun 08, 2023 |
| Acer          | Aspire 7741                 | [09b2301e59](https://linux-hardware.org/?probe=09b2301e59) | Jun 08, 2023 |
| Lenovo        | ThinkPad X131e 3374A17      | [d992393271](https://linux-hardware.org/?probe=d992393271) | Jun 08, 2023 |
| Lenovo        | ThinkPad X131e 3374A17      | [dd385507aa](https://linux-hardware.org/?probe=dd385507aa) | Jun 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ef71a1641b](https://linux-hardware.org/?probe=ef71a1641b) | Jun 08, 2023 |
| HP            | Pavilion 17                 | [da809f90cc](https://linux-hardware.org/?probe=da809f90cc) | Jun 07, 2023 |
| Dell          | Latitude 5530               | [1e3452635f](https://linux-hardware.org/?probe=1e3452635f) | Jun 07, 2023 |
| HP            | ProBook 4530s               | [bdb6739deb](https://linux-hardware.org/?probe=bdb6739deb) | Jun 07, 2023 |
| Intel         | HURONRIVER                  | [57035a777c](https://linux-hardware.org/?probe=57035a777c) | Jun 07, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [490ae0bc1c](https://linux-hardware.org/?probe=490ae0bc1c) | Jun 07, 2023 |
| MSI           | Pulse GL66 12UDK            | [8c9a9eb310](https://linux-hardware.org/?probe=8c9a9eb310) | Jun 06, 2023 |
| HP            | Pavilion g7                 | [f8cccf0fec](https://linux-hardware.org/?probe=f8cccf0fec) | Jun 06, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [be9987ca28](https://linux-hardware.org/?probe=be9987ca28) | Jun 06, 2023 |
| Fujitsu       | FMVNA4NE-                   | [626a677331](https://linux-hardware.org/?probe=626a677331) | Jun 06, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [c20dd8572a](https://linux-hardware.org/?probe=c20dd8572a) | Jun 05, 2023 |
| HP            | ENVY Laptop 13-ba0xxx       | [22143d333a](https://linux-hardware.org/?probe=22143d333a) | Jun 05, 2023 |
| Aquarius      | NS585                       | [b3f11e4a53](https://linux-hardware.org/?probe=b3f11e4a53) | Jun 05, 2023 |
| Fujitsu       | FMVNA4NE-                   | [b1c1176a5b](https://linux-hardware.org/?probe=b1c1176a5b) | Jun 05, 2023 |
| Dell          | Latitude 3410               | [820e62c9d3](https://linux-hardware.org/?probe=820e62c9d3) | Jun 04, 2023 |
| MSI           | GL75 Leopard 10SER          | [24111ade43](https://linux-hardware.org/?probe=24111ade43) | Jun 04, 2023 |
| Dell          | Latitude 3410               | [12515d41c8](https://linux-hardware.org/?probe=12515d41c8) | Jun 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [1352a1d7c7](https://linux-hardware.org/?probe=1352a1d7c7) | Jun 04, 2023 |
| ASUSTek       | Q502LA                      | [679a477085](https://linux-hardware.org/?probe=679a477085) | Jun 04, 2023 |
| Clevo         | M670SRU                     | [0935f74d34](https://linux-hardware.org/?probe=0935f74d34) | Jun 04, 2023 |
| Clevo         | M670SRU                     | [e163d57d56](https://linux-hardware.org/?probe=e163d57d56) | Jun 04, 2023 |
| AVITA         | NS14A8                      | [a576b4d5cc](https://linux-hardware.org/?probe=a576b4d5cc) | Jun 04, 2023 |
| Dell          | Latitude 5420               | [9085f3c8f7](https://linux-hardware.org/?probe=9085f3c8f7) | Jun 04, 2023 |
| Toshiba       | WT8-A                       | [01e8918ef6](https://linux-hardware.org/?probe=01e8918ef6) | Jun 04, 2023 |
| Acer          | Aspire 5738                 | [138d22e03e](https://linux-hardware.org/?probe=138d22e03e) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [a10a42a44d](https://linux-hardware.org/?probe=a10a42a44d) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [e58b2a1237](https://linux-hardware.org/?probe=e58b2a1237) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [ce54d0192d](https://linux-hardware.org/?probe=ce54d0192d) | Jun 04, 2023 |
| Lenovo        | ThinkPad E420 1141R79       | [7f66bf0045](https://linux-hardware.org/?probe=7f66bf0045) | Jun 03, 2023 |
| Apple         | MacBookPro9,2               | [eb51cb6dcf](https://linux-hardware.org/?probe=eb51cb6dcf) | Jun 03, 2023 |
| Acer          | Aspire V3-372               | [1200863830](https://linux-hardware.org/?probe=1200863830) | Jun 03, 2023 |
| Acer          | Aspire A115-31              | [338f025bce](https://linux-hardware.org/?probe=338f025bce) | Jun 03, 2023 |
| Apple         | MacBookPro7,1               | [b1513dc005](https://linux-hardware.org/?probe=b1513dc005) | Jun 03, 2023 |
| HP            | Laptop 14-cm0xxx            | [8933e1b0ad](https://linux-hardware.org/?probe=8933e1b0ad) | Jun 03, 2023 |
| Acer          | Aspire E5-772G              | [5bd684bed6](https://linux-hardware.org/?probe=5bd684bed6) | Jun 02, 2023 |
| Acer          | Aspire E5-772G              | [f454cdf394](https://linux-hardware.org/?probe=f454cdf394) | Jun 02, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [b546b2e7f1](https://linux-hardware.org/?probe=b546b2e7f1) | Jun 02, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2a67b74a26](https://linux-hardware.org/?probe=2a67b74a26) | Jun 02, 2023 |
| Apple         | MacBookPro5,5               | [9bf36ef4a5](https://linux-hardware.org/?probe=9bf36ef4a5) | Jun 02, 2023 |
| HP            | ZBook 15 G6                 | [2f7bb21988](https://linux-hardware.org/?probe=2f7bb21988) | Jun 02, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [174ffa62e4](https://linux-hardware.org/?probe=174ffa62e4) | Jun 02, 2023 |
| Aquarius      | NS585                       | [6f93385917](https://linux-hardware.org/?probe=6f93385917) | Jun 02, 2023 |
| Dell          | Inspiron 5567               | [bd3a6c5bd8](https://linux-hardware.org/?probe=bd3a6c5bd8) | Jun 02, 2023 |
| Aquarius      | NS585                       | [091267ec3a](https://linux-hardware.org/?probe=091267ec3a) | Jun 02, 2023 |
| Aquarius      | NS585                       | [7534819f94](https://linux-hardware.org/?probe=7534819f94) | Jun 02, 2023 |
| Lenovo        | S40-70 80GQ                 | [9a3fbc7388](https://linux-hardware.org/?probe=9a3fbc7388) | Jun 02, 2023 |
| Dell          | Latitude E6430              | [b129765265](https://linux-hardware.org/?probe=b129765265) | Jun 02, 2023 |
| HP            | EliteBook 840 G6            | [81ec1cc134](https://linux-hardware.org/?probe=81ec1cc134) | Jun 01, 2023 |
| Dell          | Latitude E5510              | [4a0bc9e53f](https://linux-hardware.org/?probe=4a0bc9e53f) | Jun 01, 2023 |
| Dell          | System Inspiron N4110       | [ea09e45a4f](https://linux-hardware.org/?probe=ea09e45a4f) | Jun 01, 2023 |
| Aquarius      | NS585                       | [ffa7425b95](https://linux-hardware.org/?probe=ffa7425b95) | Jun 01, 2023 |
| Aquarius      | NS585                       | [fafcbbe90e](https://linux-hardware.org/?probe=fafcbbe90e) | Jun 01, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [ffc6b5e345](https://linux-hardware.org/?probe=ffc6b5e345) | Jun 01, 2023 |
| Dell          | Latitude E5510              | [9457826049](https://linux-hardware.org/?probe=9457826049) | Jun 01, 2023 |
| Positivo      | C500                        | [8dba4589fe](https://linux-hardware.org/?probe=8dba4589fe) | Jun 01, 2023 |
| ASUSTek       | X200LA                      | [ae3925153d](https://linux-hardware.org/?probe=ae3925153d) | May 31, 2023 |
| ASUSTek       | 1225B                       | [769a6736f1](https://linux-hardware.org/?probe=769a6736f1) | May 31, 2023 |
| Unknown       | Unknown                     | [412c6d4af8](https://linux-hardware.org/?probe=412c6d4af8) | May 31, 2023 |
| Fujitsu       | LIFEBOOK E780               | [8459f7cfee](https://linux-hardware.org/?probe=8459f7cfee) | May 31, 2023 |
| Apple         | MacBookPro16,1              | [717c7884c8](https://linux-hardware.org/?probe=717c7884c8) | May 31, 2023 |
| HP            | EliteBook 840 G4            | [46ccbd2d62](https://linux-hardware.org/?probe=46ccbd2d62) | May 31, 2023 |
| HP            | EliteBook 840 G4            | [b90cb27f97](https://linux-hardware.org/?probe=b90cb27f97) | May 31, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [5f8bd19e3d](https://linux-hardware.org/?probe=5f8bd19e3d) | May 31, 2023 |
| Acer          | TravelMate P449-G2-M        | [41177ef027](https://linux-hardware.org/?probe=41177ef027) | May 31, 2023 |
| Dell          | Latitude 5411               | [8583aa2091](https://linux-hardware.org/?probe=8583aa2091) | May 31, 2023 |
| ASUSTek       | K52Jc                       | [ad0b57d7c6](https://linux-hardware.org/?probe=ad0b57d7c6) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | [e065b72b88](https://linux-hardware.org/?probe=e065b72b88) | May 31, 2023 |
| ASUSTek       | K52Jc                       | [7709d9fd16](https://linux-hardware.org/?probe=7709d9fd16) | May 31, 2023 |
| Dell          | Latitude E5510              | [52e1023195](https://linux-hardware.org/?probe=52e1023195) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | [52047d2230](https://linux-hardware.org/?probe=52047d2230) | May 31, 2023 |
| Dell          | Latitude E5510              | [aa0f6a81b6](https://linux-hardware.org/?probe=aa0f6a81b6) | May 30, 2023 |
| HP            | Laptop 17-ca0xxx            | [3222c41173](https://linux-hardware.org/?probe=3222c41173) | May 30, 2023 |
| Chuwi         | HeroBook Air                | [80afc31c99](https://linux-hardware.org/?probe=80afc31c99) | May 30, 2023 |
| Lenovo        | ThinkPad T460 20FMS4LL00    | [7519448ca8](https://linux-hardware.org/?probe=7519448ca8) | May 30, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [ad3464fd76](https://linux-hardware.org/?probe=ad3464fd76) | May 30, 2023 |
| Acer          | Aspire A315-58              | [66de62e958](https://linux-hardware.org/?probe=66de62e958) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [c8e0efc288](https://linux-hardware.org/?probe=c8e0efc288) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [da399dc7cc](https://linux-hardware.org/?probe=da399dc7cc) | May 29, 2023 |
| Fujitsu       | LIFEBOOK E780               | [aac95cf765](https://linux-hardware.org/?probe=aac95cf765) | May 29, 2023 |
| Dell          | Latitude E5470              | [77d85b619e](https://linux-hardware.org/?probe=77d85b619e) | May 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [deaa4b357c](https://linux-hardware.org/?probe=deaa4b357c) | May 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [af312b5e91](https://linux-hardware.org/?probe=af312b5e91) | May 29, 2023 |
| Dell          | Latitude E6530              | [26f783c383](https://linux-hardware.org/?probe=26f783c383) | May 29, 2023 |
| HP            | EliteBook 735 G6            | [18b33e6fc7](https://linux-hardware.org/?probe=18b33e6fc7) | May 29, 2023 |
| Lenovo        | ThinkPad W530 2447GH2       | [f902d43115](https://linux-hardware.org/?probe=f902d43115) | May 29, 2023 |
| Acer          | Aspire A515-56              | [108833c92b](https://linux-hardware.org/?probe=108833c92b) | May 29, 2023 |
| Dell          | Latitude E6530              | [a47a934500](https://linux-hardware.org/?probe=a47a934500) | May 29, 2023 |
| HP            | Laptop 17-ca0xxx            | [4b53ed4ede](https://linux-hardware.org/?probe=4b53ed4ede) | May 29, 2023 |
| Dell          | Latitude 7480               | [9eb2396796](https://linux-hardware.org/?probe=9eb2396796) | May 28, 2023 |
| Lenovo        | Edge 15 80H1                | [75fdd71ca1](https://linux-hardware.org/?probe=75fdd71ca1) | May 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d5a3141562](https://linux-hardware.org/?probe=d5a3141562) | May 28, 2023 |
| HP            | EliteBook 840 G1            | [c256cd6942](https://linux-hardware.org/?probe=c256cd6942) | May 28, 2023 |
| HP            | Mini 110-3700               | [0f9528a8d2](https://linux-hardware.org/?probe=0f9528a8d2) | May 28, 2023 |
| HP            | G42                         | [7b9612a51a](https://linux-hardware.org/?probe=7b9612a51a) | May 27, 2023 |
| ASUSTek       | X550CA                      | [3ad8935a92](https://linux-hardware.org/?probe=3ad8935a92) | May 27, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [447ea38d26](https://linux-hardware.org/?probe=447ea38d26) | May 27, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [57dcd55314](https://linux-hardware.org/?probe=57dcd55314) | May 27, 2023 |
| Aquarius      | NS585                       | [a87c8d46b6](https://linux-hardware.org/?probe=a87c8d46b6) | May 27, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [9b93292db9](https://linux-hardware.org/?probe=9b93292db9) | May 26, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JU... | [0696598319](https://linux-hardware.org/?probe=0696598319) | May 26, 2023 |
| ASUSTek       | K53SV                       | [357c1fd091](https://linux-hardware.org/?probe=357c1fd091) | May 26, 2023 |
| Dell          | Latitude 3520               | [bfa8a18cb5](https://linux-hardware.org/?probe=bfa8a18cb5) | May 26, 2023 |
| Fujitsu       | FMVA42ERKS                  | [91fa73184c](https://linux-hardware.org/?probe=91fa73184c) | May 26, 2023 |
| eMachines     | E725                        | [a4be8012a8](https://linux-hardware.org/?probe=a4be8012a8) | May 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [4c3aa6334b](https://linux-hardware.org/?probe=4c3aa6334b) | May 26, 2023 |
| Acer          | Aspire A315-42              | [d229a8eb01](https://linux-hardware.org/?probe=d229a8eb01) | May 26, 2023 |
| Acer          | Aspire V3-551               | [316db578fe](https://linux-hardware.org/?probe=316db578fe) | May 25, 2023 |
| Aquarius      | NS585                       | [82a0d45251](https://linux-hardware.org/?probe=82a0d45251) | May 25, 2023 |
| Acer          | Aspire E5-575               | [45ac56e70c](https://linux-hardware.org/?probe=45ac56e70c) | May 25, 2023 |
| Dell          | Latitude 7220 Rugged Ext... | [442b7239c8](https://linux-hardware.org/?probe=442b7239c8) | May 24, 2023 |
| Dell          | Latitude E5430 non-vPro     | [278fefa10a](https://linux-hardware.org/?probe=278fefa10a) | May 24, 2023 |
| Notebook      | W54_55SU1,SUW               | [25b79c51e2](https://linux-hardware.org/?probe=25b79c51e2) | May 23, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [f8ef460648](https://linux-hardware.org/?probe=f8ef460648) | May 23, 2023 |
| HP            | 530                         | [70600de142](https://linux-hardware.org/?probe=70600de142) | May 23, 2023 |
| Dell          | Latitude E5430 non-vPro     | [6ab7e9c82d](https://linux-hardware.org/?probe=6ab7e9c82d) | May 23, 2023 |
| Acer          | Nitro AN515-45              | [d784b0822d](https://linux-hardware.org/?probe=d784b0822d) | May 22, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [44b6477648](https://linux-hardware.org/?probe=44b6477648) | May 22, 2023 |
| ASUSTek       | N56VB                       | [0e982abd6b](https://linux-hardware.org/?probe=0e982abd6b) | May 22, 2023 |
| Unknown       | Unknown                     | [2b3ef0afc4](https://linux-hardware.org/?probe=2b3ef0afc4) | May 22, 2023 |
| HP            | Laptop 15-da0xxx            | [82f235bfbb](https://linux-hardware.org/?probe=82f235bfbb) | May 22, 2023 |
| HP            | Laptop 14-dq0xxx            | [4438fdd9b2](https://linux-hardware.org/?probe=4438fdd9b2) | May 22, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [0ab3a9817b](https://linux-hardware.org/?probe=0ab3a9817b) | May 21, 2023 |
| Dell          | Inspiron 5570               | [ca85d5aafa](https://linux-hardware.org/?probe=ca85d5aafa) | May 21, 2023 |
| Lenovo        | ThinkPad T410s 2904FAG      | [742f2c09c5](https://linux-hardware.org/?probe=742f2c09c5) | May 21, 2023 |
| Terrans Fo... | AMD                         | [8087d42d0e](https://linux-hardware.org/?probe=8087d42d0e) | May 21, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [473ea193d5](https://linux-hardware.org/?probe=473ea193d5) | May 21, 2023 |
| Dell          | Inspiron 3451               | [e69cefc8da](https://linux-hardware.org/?probe=e69cefc8da) | May 21, 2023 |
| Acer          | Aspire 5253                 | [f28727e594](https://linux-hardware.org/?probe=f28727e594) | May 21, 2023 |
| Acer          | Aspire 5739G                | [23a84a79ed](https://linux-hardware.org/?probe=23a84a79ed) | May 20, 2023 |
| Lenovo        | ThinkPad W510 4391DK3       | [ac8db768ce](https://linux-hardware.org/?probe=ac8db768ce) | May 20, 2023 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | [e6e79ac2ca](https://linux-hardware.org/?probe=e6e79ac2ca) | May 20, 2023 |
| Acer          | Aspire 5739G                | [2ae6c83437](https://linux-hardware.org/?probe=2ae6c83437) | May 20, 2023 |
| Dell          | Latitude E5430 non-vPro     | [51827f5ae5](https://linux-hardware.org/?probe=51827f5ae5) | May 19, 2023 |
| Dell          | Latitude 5411               | [8929285bca](https://linux-hardware.org/?probe=8929285bca) | May 19, 2023 |
| Acer          | Aspire 5253                 | [fa328bbd9c](https://linux-hardware.org/?probe=fa328bbd9c) | May 19, 2023 |
| Avell High... | A40 LIV                     | [d1e00e62c4](https://linux-hardware.org/?probe=d1e00e62c4) | May 19, 2023 |
| Dell          | Vostro 15 3515              | [6b5bc55aeb](https://linux-hardware.org/?probe=6b5bc55aeb) | May 18, 2023 |
| Dell          | Vostro 15 3515              | [e26f4ecf2f](https://linux-hardware.org/?probe=e26f4ecf2f) | May 18, 2023 |
| Lenovo        | ThinkPad X200s 7470WUB      | [e5ad235f60](https://linux-hardware.org/?probe=e5ad235f60) | May 18, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [5d69cc1112](https://linux-hardware.org/?probe=5d69cc1112) | May 18, 2023 |
| Toshiba       | Satellite C855-22N          | [f5ccfb46ea](https://linux-hardware.org/?probe=f5ccfb46ea) | May 18, 2023 |
| Aquarius      | NS585                       | [dc2b351b40](https://linux-hardware.org/?probe=dc2b351b40) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | [0c6bb22a24](https://linux-hardware.org/?probe=0c6bb22a24) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | [e042bb19ba](https://linux-hardware.org/?probe=e042bb19ba) | May 18, 2023 |
| Acer          | Aspire A514-54              | [26dc842484](https://linux-hardware.org/?probe=26dc842484) | May 18, 2023 |
| Dell          | Latitude E7450              | [3000905b05](https://linux-hardware.org/?probe=3000905b05) | May 18, 2023 |
| Dell          | Latitude E7450              | [10f138711f](https://linux-hardware.org/?probe=10f138711f) | May 18, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [66f184855c](https://linux-hardware.org/?probe=66f184855c) | May 17, 2023 |
| Apple         | MacBookPro12,1              | [4aadc89f41](https://linux-hardware.org/?probe=4aadc89f41) | May 17, 2023 |
| Acer          | TravelMate X514-51          | [24465d2184](https://linux-hardware.org/?probe=24465d2184) | May 17, 2023 |
| Dell          | Latitude E5430 non-vPro     | [a1fb71ff2f](https://linux-hardware.org/?probe=a1fb71ff2f) | May 17, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAA... | [5e4e802b87](https://linux-hardware.org/?probe=5e4e802b87) | May 17, 2023 |
| Apple         | MacBookPro12,1              | [8aef05613d](https://linux-hardware.org/?probe=8aef05613d) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [966e89afc3](https://linux-hardware.org/?probe=966e89afc3) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [b4bd4b7d23](https://linux-hardware.org/?probe=b4bd4b7d23) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [3089c7ab46](https://linux-hardware.org/?probe=3089c7ab46) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [a587179a2f](https://linux-hardware.org/?probe=a587179a2f) | May 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [0fd753db6d](https://linux-hardware.org/?probe=0fd753db6d) | May 16, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | [0f9a26db5f](https://linux-hardware.org/?probe=0f9a26db5f) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [8ab7fe837d](https://linux-hardware.org/?probe=8ab7fe837d) | May 16, 2023 |
| Lenovo        | ThinkPad T490 20N2004JAD    | [c765eed46d](https://linux-hardware.org/?probe=c765eed46d) | May 16, 2023 |
| Dell          | Latitude 5521               | [9f671f21c1](https://linux-hardware.org/?probe=9f671f21c1) | May 16, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | [56056f7c9a](https://linux-hardware.org/?probe=56056f7c9a) | May 15, 2023 |
| Acer          | AO532h                      | [6cfe2a58cc](https://linux-hardware.org/?probe=6cfe2a58cc) | May 15, 2023 |
| Acer          | Aspire 7745G                | [c1bcc07617](https://linux-hardware.org/?probe=c1bcc07617) | May 15, 2023 |
| Acer          | Aspire 7745G                | [7b0f6f3dc2](https://linux-hardware.org/?probe=7b0f6f3dc2) | May 15, 2023 |
| Dell          | G15 5510                    | [5624d414be](https://linux-hardware.org/?probe=5624d414be) | May 15, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | [c82f72f0e2](https://linux-hardware.org/?probe=c82f72f0e2) | May 15, 2023 |
| Lenovo        | B590 20206                  | [70b604bc30](https://linux-hardware.org/?probe=70b604bc30) | May 14, 2023 |
| Lenovo        | ThinkPad Edge E530 3259C... | [cd0a78ce39](https://linux-hardware.org/?probe=cd0a78ce39) | May 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7978974828](https://linux-hardware.org/?probe=7978974828) | May 14, 2023 |
| ASUSTek       | N56VB                       | [87d2f8b907](https://linux-hardware.org/?probe=87d2f8b907) | May 14, 2023 |
| ASUSTek       | N56VB                       | [7e2caae7ea](https://linux-hardware.org/?probe=7e2caae7ea) | May 14, 2023 |
| Lenovo        | B50-70 20384                | [1d3db7b456](https://linux-hardware.org/?probe=1d3db7b456) | May 14, 2023 |
| Lenovo        | B50-70 20384                | [9459f4eae8](https://linux-hardware.org/?probe=9459f4eae8) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [2be4ad0e3d](https://linux-hardware.org/?probe=2be4ad0e3d) | May 14, 2023 |
| Dell          | Latitude 7410               | [542e1d7f7b](https://linux-hardware.org/?probe=542e1d7f7b) | May 14, 2023 |
| AMI           | Intel                       | [958f5ffc92](https://linux-hardware.org/?probe=958f5ffc92) | May 14, 2023 |
| AMI           | Intel                       | [0c9a68a20c](https://linux-hardware.org/?probe=0c9a68a20c) | May 13, 2023 |
| HP            | EliteBook 840 G5            | [7b8c68cfcf](https://linux-hardware.org/?probe=7b8c68cfcf) | May 13, 2023 |
| Fujitsu       | LIFEBOOK E5410              | [c62a002948](https://linux-hardware.org/?probe=c62a002948) | May 13, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [a25f9e8d93](https://linux-hardware.org/?probe=a25f9e8d93) | May 13, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [d2ba323017](https://linux-hardware.org/?probe=d2ba323017) | May 13, 2023 |
| HUAWEI        | BOHB-WAX9                   | [89747b6213](https://linux-hardware.org/?probe=89747b6213) | May 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [bf54c69e0c](https://linux-hardware.org/?probe=bf54c69e0c) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [17510fcd4f](https://linux-hardware.org/?probe=17510fcd4f) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [b9b6adb18a](https://linux-hardware.org/?probe=b9b6adb18a) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [80dc4be517](https://linux-hardware.org/?probe=80dc4be517) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [6eb320d381](https://linux-hardware.org/?probe=6eb320d381) | May 12, 2023 |
| HP            | ProBook 640 G1              | [4bbb20185b](https://linux-hardware.org/?probe=4bbb20185b) | May 12, 2023 |
| HP            | ProBook 640 G1              | [f89a68e432](https://linux-hardware.org/?probe=f89a68e432) | May 12, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E02    | [d90b0e6626](https://linux-hardware.org/?probe=d90b0e6626) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [a07acb448b](https://linux-hardware.org/?probe=a07acb448b) | May 12, 2023 |
| Lenovo        | ThinkPad X260 20F600A7MS    | [67daafed56](https://linux-hardware.org/?probe=67daafed56) | May 12, 2023 |
| HP            | ProBook 6470b               | [7f1a6e0d48](https://linux-hardware.org/?probe=7f1a6e0d48) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [f4df381f0e](https://linux-hardware.org/?probe=f4df381f0e) | May 12, 2023 |
| Lenovo        | ThinkPad T440 20B7S2SM00    | [8f6bd394c4](https://linux-hardware.org/?probe=8f6bd394c4) | May 12, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [ba177fa007](https://linux-hardware.org/?probe=ba177fa007) | May 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [9201edcfb8](https://linux-hardware.org/?probe=9201edcfb8) | May 12, 2023 |
| Toshiba       | Satellite Pro C660          | [848eedb681](https://linux-hardware.org/?probe=848eedb681) | May 12, 2023 |
| Lenovo        | ThinkPad T470 20HD0001MX    | [65b165e2f1](https://linux-hardware.org/?probe=65b165e2f1) | May 12, 2023 |
| HUAWEI        | MACHD-WXX9                  | [f5d0a04a09](https://linux-hardware.org/?probe=f5d0a04a09) | May 12, 2023 |
| Apple         | MacBook10,1                 | [d26983a399](https://linux-hardware.org/?probe=d26983a399) | May 12, 2023 |
| HP            | ProBook 450 G7              | [ba542c09f2](https://linux-hardware.org/?probe=ba542c09f2) | May 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [f02c2abaab](https://linux-hardware.org/?probe=f02c2abaab) | May 11, 2023 |
| Dell          | XPS 9315                    | [d53e7f5d92](https://linux-hardware.org/?probe=d53e7f5d92) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7d19994aa2](https://linux-hardware.org/?probe=7d19994aa2) | May 11, 2023 |
| Dell          | Precision 5520              | [5dfdbeff37](https://linux-hardware.org/?probe=5dfdbeff37) | May 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [eb6941b1b8](https://linux-hardware.org/?probe=eb6941b1b8) | May 10, 2023 |
| Dell          | XPS 15 9560                 | [b904defc14](https://linux-hardware.org/?probe=b904defc14) | May 09, 2023 |
| HP            | 250 G6 Notebook PC          | [f612c54f9c](https://linux-hardware.org/?probe=f612c54f9c) | May 09, 2023 |
| HP            | 250 G6 Notebook PC          | [9c14434a99](https://linux-hardware.org/?probe=9c14434a99) | May 09, 2023 |
| Unknown       | Unknown                     | [4a0ccb88d2](https://linux-hardware.org/?probe=4a0ccb88d2) | May 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [9b21cbbca0](https://linux-hardware.org/?probe=9b21cbbca0) | May 09, 2023 |
| Lenovo        | ThinkPad T530 2394CE2       | [d232fefed2](https://linux-hardware.org/?probe=d232fefed2) | May 09, 2023 |
| Avell High... | A40 LIV                     | [c4c4a1fe74](https://linux-hardware.org/?probe=c4c4a1fe74) | May 09, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [1f874eaf6d](https://linux-hardware.org/?probe=1f874eaf6d) | May 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [36334e327a](https://linux-hardware.org/?probe=36334e327a) | May 08, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [967e39a2d3](https://linux-hardware.org/?probe=967e39a2d3) | May 08, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYFR    | [f945ec106e](https://linux-hardware.org/?probe=f945ec106e) | May 07, 2023 |
| HP            | 255 G3                      | [d95f6211dc](https://linux-hardware.org/?probe=d95f6211dc) | May 07, 2023 |
| ASUSTek       | K73SJ                       | [13b8c8be10](https://linux-hardware.org/?probe=13b8c8be10) | May 07, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [7998abcdcd](https://linux-hardware.org/?probe=7998abcdcd) | May 07, 2023 |
| Dell          | Vostro 15-3568              | [08b1152328](https://linux-hardware.org/?probe=08b1152328) | May 07, 2023 |
| Acer          | Aspire AV15-51              | [9d7736a816](https://linux-hardware.org/?probe=9d7736a816) | May 06, 2023 |
| Lenovo        | IdeaPad Y480 20131          | [d625664bee](https://linux-hardware.org/?probe=d625664bee) | May 06, 2023 |
| Unknown       | Unknown                     | [dd406112de](https://linux-hardware.org/?probe=dd406112de) | May 06, 2023 |
| HP            | Laptop 15s-fq5xxx           | [8ce0b92713](https://linux-hardware.org/?probe=8ce0b92713) | May 06, 2023 |
| Lenovo        | Mixx-700-12ISK 80QL         | [14bc666ec3](https://linux-hardware.org/?probe=14bc666ec3) | May 06, 2023 |
| Acer          | Aspire 7741                 | [25f9d02593](https://linux-hardware.org/?probe=25f9d02593) | May 06, 2023 |
| Lenovo        | ThinkPad T410 2537CC5       | [10de9f17e1](https://linux-hardware.org/?probe=10de9f17e1) | May 06, 2023 |
| Acer          | TravelMate P215-53          | [f7c7c572e4](https://linux-hardware.org/?probe=f7c7c572e4) | May 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e0357a19f3](https://linux-hardware.org/?probe=e0357a19f3) | May 05, 2023 |
| Dell          | Inspiron 5770               | [c545869ec5](https://linux-hardware.org/?probe=c545869ec5) | May 05, 2023 |
| Lenovo        | ThinkPad T15p Gen 2i 21A... | [064df1260c](https://linux-hardware.org/?probe=064df1260c) | May 05, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [d016282342](https://linux-hardware.org/?probe=d016282342) | May 05, 2023 |
| Dell          | Latitude D630               | [0bef13413f](https://linux-hardware.org/?probe=0bef13413f) | May 05, 2023 |
| Avell High... | A40 LIV                     | [5745ae021d](https://linux-hardware.org/?probe=5745ae021d) | May 05, 2023 |
| Acer          | Aspire A515-52G             | [4f2fbcc26f](https://linux-hardware.org/?probe=4f2fbcc26f) | May 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2660b0df6d](https://linux-hardware.org/?probe=2660b0df6d) | May 04, 2023 |
| Aquarius      | NS585                       | [817d9a6b62](https://linux-hardware.org/?probe=817d9a6b62) | May 04, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [b68f20e323](https://linux-hardware.org/?probe=b68f20e323) | May 04, 2023 |
| Notebook      | W54_55SU1,SUW               | [fbcadee14f](https://linux-hardware.org/?probe=fbcadee14f) | May 03, 2023 |
| Notebook      | W54_55SU1,SUW               | [f9071ed10e](https://linux-hardware.org/?probe=f9071ed10e) | May 03, 2023 |
| Aquarius      | NS585                       | [c629501448](https://linux-hardware.org/?probe=c629501448) | May 03, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f636b7c230](https://linux-hardware.org/?probe=f636b7c230) | May 03, 2023 |
| HP            | EliteBook 640 14 inch G9... | [fc1bd7fffc](https://linux-hardware.org/?probe=fc1bd7fffc) | May 03, 2023 |
| HP            | EliteBook 640 14 inch G9... | [c8373114ef](https://linux-hardware.org/?probe=c8373114ef) | May 03, 2023 |
| Lenovo        | ThinkPad T495 20NK000XBR    | [c7ca4b1477](https://linux-hardware.org/?probe=c7ca4b1477) | May 03, 2023 |
| Lenovo        | ThinkPad T470 20HES63400    | [6628ac6681](https://linux-hardware.org/?probe=6628ac6681) | May 03, 2023 |
| HP            | Notebook                    | [c6316b5a64](https://linux-hardware.org/?probe=c6316b5a64) | May 03, 2023 |
| Dell          | Precision 7510              | [1e73564cf9](https://linux-hardware.org/?probe=1e73564cf9) | May 03, 2023 |
| MSI           | Unknown                     | [917d7a7fc9](https://linux-hardware.org/?probe=917d7a7fc9) | May 03, 2023 |
| Dell          | Latitude 5414               | [6922f7db46](https://linux-hardware.org/?probe=6922f7db46) | May 03, 2023 |
| HP            | OMEN by Laptop              | [a60578cfe2](https://linux-hardware.org/?probe=a60578cfe2) | May 02, 2023 |
| Aquarius      | NS585                       | [e6922e974c](https://linux-hardware.org/?probe=e6922e974c) | May 02, 2023 |
| Dell          | Latitude D630               | [d8ee0e7ca8](https://linux-hardware.org/?probe=d8ee0e7ca8) | May 02, 2023 |
| Toshiba       | Satellite X200              | [e1674b1234](https://linux-hardware.org/?probe=e1674b1234) | May 02, 2023 |
| Dell          | Latitude 7370               | [c984360af7](https://linux-hardware.org/?probe=c984360af7) | May 02, 2023 |
| Dell          | Latitude 7370               | [295b50d5b2](https://linux-hardware.org/?probe=295b50d5b2) | May 02, 2023 |
| MSI           | Katana GF76 12UEK           | [5af5d6aec3](https://linux-hardware.org/?probe=5af5d6aec3) | May 01, 2023 |
| AXDIA Inte... | MYBOOK 14 PRO               | [3174c98e9c](https://linux-hardware.org/?probe=3174c98e9c) | May 01, 2023 |
| Sony          | VPCF13WFX                   | [6500c354c7](https://linux-hardware.org/?probe=6500c354c7) | May 01, 2023 |
| Lenovo        | Slim 9 14IAP7 82T1          | [fe1b421c9d](https://linux-hardware.org/?probe=fe1b421c9d) | May 01, 2023 |
| Acer          | Aspire E1-571               | [e03d5ff056](https://linux-hardware.org/?probe=e03d5ff056) | Apr 30, 2023 |
| HP            | ProBook 655 G3              | [07e2cc77f8](https://linux-hardware.org/?probe=07e2cc77f8) | Apr 30, 2023 |
| HP            | ProBook 655 G3              | [638e747fb1](https://linux-hardware.org/?probe=638e747fb1) | Apr 30, 2023 |
| HP            | Compaq Mini CQ10-500        | [9a1134210f](https://linux-hardware.org/?probe=9a1134210f) | Apr 30, 2023 |
| Positivo      | Q464C                       | [8e41593bd3](https://linux-hardware.org/?probe=8e41593bd3) | Apr 30, 2023 |
| HP            | 255 G8 Notebook PC          | [7262375294](https://linux-hardware.org/?probe=7262375294) | Apr 30, 2023 |
| Dell          | Inspiron MXC061             | [2d1ab773dd](https://linux-hardware.org/?probe=2d1ab773dd) | Apr 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [0a9a85f5f0](https://linux-hardware.org/?probe=0a9a85f5f0) | Apr 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [83b10185e8](https://linux-hardware.org/?probe=83b10185e8) | Apr 29, 2023 |
| COPELION I... | QX-250 Series               | [409821566f](https://linux-hardware.org/?probe=409821566f) | Apr 29, 2023 |
| Lenovo        | ThinkPad X280 20KESBC402    | [0d5b86146e](https://linux-hardware.org/?probe=0d5b86146e) | Apr 29, 2023 |
| Aquarius      | NS585                       | [b23696ca41](https://linux-hardware.org/?probe=b23696ca41) | Apr 28, 2023 |
| Dell          | Latitude E7450              | [6afa2ff009](https://linux-hardware.org/?probe=6afa2ff009) | Apr 28, 2023 |
| Dell          | Latitude D630               | [a3c3e09675](https://linux-hardware.org/?probe=a3c3e09675) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [2474e8e580](https://linux-hardware.org/?probe=2474e8e580) | Apr 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [69d1f17b35](https://linux-hardware.org/?probe=69d1f17b35) | Apr 27, 2023 |
| ARDOR GAMI... | PD5x_7xPNP_PNR_PNN_PNT      | [e61f528ba5](https://linux-hardware.org/?probe=e61f528ba5) | Apr 27, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [2093399e21](https://linux-hardware.org/?probe=2093399e21) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [73141c5006](https://linux-hardware.org/?probe=73141c5006) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [0cb164ac2f](https://linux-hardware.org/?probe=0cb164ac2f) | Apr 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | [198fa6162e](https://linux-hardware.org/?probe=198fa6162e) | Apr 27, 2023 |
| IGEL Techn... | M340C                       | [40970f0528](https://linux-hardware.org/?probe=40970f0528) | Apr 26, 2023 |
| ARDOR GAMI... | PD5x_7xPNP_PNR_PNN_PNT      | [cec3a72c8a](https://linux-hardware.org/?probe=cec3a72c8a) | Apr 26, 2023 |
| Dell          | Latitude D630               | [850df6e76f](https://linux-hardware.org/?probe=850df6e76f) | Apr 26, 2023 |
| Google        | Terra                       | [b22deb9f09](https://linux-hardware.org/?probe=b22deb9f09) | Apr 26, 2023 |
| Dell          | Latitude E6440              | [f5cdf825fa](https://linux-hardware.org/?probe=f5cdf825fa) | Apr 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M640... | [0234325d36](https://linux-hardware.org/?probe=0234325d36) | Apr 26, 2023 |
| HP            | ENVY 15                     | [1f50420c44](https://linux-hardware.org/?probe=1f50420c44) | Apr 26, 2023 |
| HP            | 250 G6 Notebook PC          | [90e4883dca](https://linux-hardware.org/?probe=90e4883dca) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | [c3c972facf](https://linux-hardware.org/?probe=c3c972facf) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | [f993513cd3](https://linux-hardware.org/?probe=f993513cd3) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d8088982c3](https://linux-hardware.org/?probe=d8088982c3) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [4cffa55fb1](https://linux-hardware.org/?probe=4cffa55fb1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | [e6380a2186](https://linux-hardware.org/?probe=e6380a2186) | Apr 26, 2023 |
| HP            | Laptop 15                   | [34a2ebf6a1](https://linux-hardware.org/?probe=34a2ebf6a1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | [872138980a](https://linux-hardware.org/?probe=872138980a) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2122bd37a5](https://linux-hardware.org/?probe=2122bd37a5) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [af7b14d259](https://linux-hardware.org/?probe=af7b14d259) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7fbd802154](https://linux-hardware.org/?probe=7fbd802154) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ffe6065419](https://linux-hardware.org/?probe=ffe6065419) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [94ddc76aae](https://linux-hardware.org/?probe=94ddc76aae) | Apr 26, 2023 |
| Lenovo        | ThinkPad T530 23594ZC       | [7aec73dfa1](https://linux-hardware.org/?probe=7aec73dfa1) | Apr 25, 2023 |
| Lenovo        | ThinkPad X200 7459KM3       | [cbea785e27](https://linux-hardware.org/?probe=cbea785e27) | Apr 25, 2023 |
| Aquarius      | NS585                       | [a0983c89d8](https://linux-hardware.org/?probe=a0983c89d8) | Apr 25, 2023 |
| Aquarius      | NS585                       | [5d9edb6ed4](https://linux-hardware.org/?probe=5d9edb6ed4) | Apr 25, 2023 |
| Aquarius      | NS585                       | [972d7f6e4a](https://linux-hardware.org/?probe=972d7f6e4a) | Apr 25, 2023 |
| Aquarius      | NS585                       | [c89bbd8bc0](https://linux-hardware.org/?probe=c89bbd8bc0) | Apr 25, 2023 |
| Aquarius      | NS585                       | [a6e5a5f3d1](https://linux-hardware.org/?probe=a6e5a5f3d1) | Apr 25, 2023 |
| Aquarius      | NS585                       | [b6dac5b058](https://linux-hardware.org/?probe=b6dac5b058) | Apr 25, 2023 |
| Aquarius      | NS585                       | [1563889dac](https://linux-hardware.org/?probe=1563889dac) | Apr 25, 2023 |
| Aquarius      | NS585                       | [9bdbad2ab7](https://linux-hardware.org/?probe=9bdbad2ab7) | Apr 25, 2023 |
| Aquarius      | NS585                       | [e30d7dde7b](https://linux-hardware.org/?probe=e30d7dde7b) | Apr 25, 2023 |
| Aquarius      | NS585                       | [68527a900f](https://linux-hardware.org/?probe=68527a900f) | Apr 25, 2023 |
| Aquarius      | NS585                       | [ce99b27fb4](https://linux-hardware.org/?probe=ce99b27fb4) | Apr 25, 2023 |
| Aquarius      | NS585                       | [fc377acae2](https://linux-hardware.org/?probe=fc377acae2) | Apr 25, 2023 |
| Aquarius      | NS585                       | [ed32f24d6e](https://linux-hardware.org/?probe=ed32f24d6e) | Apr 25, 2023 |
| Aquarius      | NS585                       | [ea60267a5b](https://linux-hardware.org/?probe=ea60267a5b) | Apr 25, 2023 |
| Aquarius      | NS585                       | [f71897bf76](https://linux-hardware.org/?probe=f71897bf76) | Apr 25, 2023 |
| Aquarius      | NS585                       | [7aa4561ca5](https://linux-hardware.org/?probe=7aa4561ca5) | Apr 25, 2023 |
| Aquarius      | NS585                       | [385ce8cd93](https://linux-hardware.org/?probe=385ce8cd93) | Apr 25, 2023 |
| Aquarius      | NS585                       | [3fc8926a1a](https://linux-hardware.org/?probe=3fc8926a1a) | Apr 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [9e6ce2eb71](https://linux-hardware.org/?probe=9e6ce2eb71) | Apr 25, 2023 |
| Aquarius      | NS585                       | [58306d0266](https://linux-hardware.org/?probe=58306d0266) | Apr 25, 2023 |
| Acer          | Aspire E5-576G              | [9ca5902786](https://linux-hardware.org/?probe=9ca5902786) | Apr 25, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [aa1b58a2a2](https://linux-hardware.org/?probe=aa1b58a2a2) | Apr 24, 2023 |
| HP            | ProBook 4520s               | [b680525b61](https://linux-hardware.org/?probe=b680525b61) | Apr 24, 2023 |
| HP            | ProBook 4520s               | [e4ce7aed55](https://linux-hardware.org/?probe=e4ce7aed55) | Apr 24, 2023 |
| Apple         | MacBookPro5,5               | [de825a326c](https://linux-hardware.org/?probe=de825a326c) | Apr 24, 2023 |
| Dell          | Inspiron 5537               | [971055139b](https://linux-hardware.org/?probe=971055139b) | Apr 24, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | [32546113c8](https://linux-hardware.org/?probe=32546113c8) | Apr 24, 2023 |
| Hampoo        | Cherry Trail CR V200        | [f3d90b0d4a](https://linux-hardware.org/?probe=f3d90b0d4a) | Apr 23, 2023 |
| HP            | 15                          | [fd68fb06af](https://linux-hardware.org/?probe=fd68fb06af) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | [45d7bd0907](https://linux-hardware.org/?probe=45d7bd0907) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | [c7367bfdff](https://linux-hardware.org/?probe=c7367bfdff) | Apr 23, 2023 |
| Acer          | Aspire E1-571G              | [0e2671ee2e](https://linux-hardware.org/?probe=0e2671ee2e) | Apr 23, 2023 |
| Toshiba       | Satellite C70D-A            | [adee59c351](https://linux-hardware.org/?probe=adee59c351) | Apr 23, 2023 |
| Toshiba       | Satellite C70D-A            | [c5c43186bc](https://linux-hardware.org/?probe=c5c43186bc) | Apr 23, 2023 |
| Dell          | G15 5520                    | [238c8f53aa](https://linux-hardware.org/?probe=238c8f53aa) | Apr 22, 2023 |
| Dell          | Latitude E6330              | [b532a9756c](https://linux-hardware.org/?probe=b532a9756c) | Apr 22, 2023 |
| Dell          | G15 5520                    | [07751c950a](https://linux-hardware.org/?probe=07751c950a) | Apr 22, 2023 |
| HP            | Laptop 15s-du3xxx           | [45af810de1](https://linux-hardware.org/?probe=45af810de1) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5f61e3a174](https://linux-hardware.org/?probe=5f61e3a174) | Apr 21, 2023 |
| Acer          | Nitro AN515-45              | [91f538e2ab](https://linux-hardware.org/?probe=91f538e2ab) | Apr 21, 2023 |
| Lenovo        | IdeaPad S510p 20298         | [8a1e6b7f32](https://linux-hardware.org/?probe=8a1e6b7f32) | Apr 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [036616c992](https://linux-hardware.org/?probe=036616c992) | Apr 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [3caa3d5076](https://linux-hardware.org/?probe=3caa3d5076) | Apr 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [8c8d2eb3b5](https://linux-hardware.org/?probe=8c8d2eb3b5) | Apr 21, 2023 |
| HP            | ZBook Power 15.6 inch G8... | [cb40e046d8](https://linux-hardware.org/?probe=cb40e046d8) | Apr 21, 2023 |
| Dell          | Precision 3550              | [7434822402](https://linux-hardware.org/?probe=7434822402) | Apr 21, 2023 |
| Toshiba       | Satellite X200              | [15035835d0](https://linux-hardware.org/?probe=15035835d0) | Apr 20, 2023 |
| Toshiba       | Satellite Pro NB10-A-125    | [3a77f344af](https://linux-hardware.org/?probe=3a77f344af) | Apr 20, 2023 |
| ASUSTek       | X550CA                      | [cb5f73ff63](https://linux-hardware.org/?probe=cb5f73ff63) | Apr 20, 2023 |
| HP            | Notebook                    | [7174065ed3](https://linux-hardware.org/?probe=7174065ed3) | Apr 20, 2023 |
| Aquarius      | NS585                       | [753222f54f](https://linux-hardware.org/?probe=753222f54f) | Apr 20, 2023 |
| Aquarius      | NS585                       | [be0bc2be01](https://linux-hardware.org/?probe=be0bc2be01) | Apr 20, 2023 |
| Acer          | Aspire E3-111               | [9af253f4e0](https://linux-hardware.org/?probe=9af253f4e0) | Apr 20, 2023 |
| HP            | EliteBook 830 G5            | [6090be709d](https://linux-hardware.org/?probe=6090be709d) | Apr 20, 2023 |
| Aquarius      | NS585                       | [f7f0464c39](https://linux-hardware.org/?probe=f7f0464c39) | Apr 20, 2023 |
| Aquarius      | NS585                       | [8393642230](https://linux-hardware.org/?probe=8393642230) | Apr 20, 2023 |
| Aquarius      | NS585                       | [a5b9a09e63](https://linux-hardware.org/?probe=a5b9a09e63) | Apr 20, 2023 |
| Medion        | P17605                      | [b68359f3d1](https://linux-hardware.org/?probe=b68359f3d1) | Apr 20, 2023 |
| HP            | Laptop 15-db0xxx            | [9ab965fcb8](https://linux-hardware.org/?probe=9ab965fcb8) | Apr 19, 2023 |
| Lenovo        | ThinkPad T500 2055WAB       | [4e293261bb](https://linux-hardware.org/?probe=4e293261bb) | Apr 19, 2023 |
| HP            | ProBook 450 G2              | [3b8c115c1a](https://linux-hardware.org/?probe=3b8c115c1a) | Apr 19, 2023 |
| Toshiba       | Satellite Pro A100          | [4240870be8](https://linux-hardware.org/?probe=4240870be8) | Apr 19, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [f691871296](https://linux-hardware.org/?probe=f691871296) | Apr 19, 2023 |
| Acer          | Swift SF314-57              | [5fc25cc033](https://linux-hardware.org/?probe=5fc25cc033) | Apr 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [d669bcc680](https://linux-hardware.org/?probe=d669bcc680) | Apr 19, 2023 |
| HP            | 255 G8 Notebook PC          | [699e2a2a80](https://linux-hardware.org/?probe=699e2a2a80) | Apr 18, 2023 |
| Tactus        | GeoBook 140                 | [704da241f5](https://linux-hardware.org/?probe=704da241f5) | Apr 18, 2023 |
| Dell          | Vostro 5402                 | [e492c87b46](https://linux-hardware.org/?probe=e492c87b46) | Apr 18, 2023 |
| Dell          | Vostro 5402                 | [b15f47258b](https://linux-hardware.org/?probe=b15f47258b) | Apr 18, 2023 |
| PC Special... | NV4XMB,ME,MZ                | [65c0a28c58](https://linux-hardware.org/?probe=65c0a28c58) | Apr 18, 2023 |
| Lenovo        | IdeaPad S510p 20298         | [7f0be1868e](https://linux-hardware.org/?probe=7f0be1868e) | Apr 18, 2023 |
| MSI           | Prestige 15 A12UC           | [0f4c1e1ac3](https://linux-hardware.org/?probe=0f4c1e1ac3) | Apr 18, 2023 |
| Toshiba       | Satellite Pro C850-1J2      | [e5c63957a2](https://linux-hardware.org/?probe=e5c63957a2) | Apr 18, 2023 |
| ASUSTek       | G551JW                      | [65f6143e36](https://linux-hardware.org/?probe=65f6143e36) | Apr 18, 2023 |
| Lenovo        | ThinkPad L540 20AUA39QJP    | [180ef53338](https://linux-hardware.org/?probe=180ef53338) | Apr 18, 2023 |
| Lenovo        | ThinkPad L540 20AUA39QJP    | [fd3b20c292](https://linux-hardware.org/?probe=fd3b20c292) | Apr 18, 2023 |
| LG Electro... | 17Z90Q-K.AA78A1             | [594a7fa16b](https://linux-hardware.org/?probe=594a7fa16b) | Apr 18, 2023 |
| IBM           | ThinkPad R51 1836Q4U        | [ebec8b53eb](https://linux-hardware.org/?probe=ebec8b53eb) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [94f62c41e5](https://linux-hardware.org/?probe=94f62c41e5) | Apr 17, 2023 |
| LG Electro... | P530-KE6BK                  | [b1f0863c79](https://linux-hardware.org/?probe=b1f0863c79) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [d5db24c28d](https://linux-hardware.org/?probe=d5db24c28d) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [89eb2b2c32](https://linux-hardware.org/?probe=89eb2b2c32) | Apr 17, 2023 |
| Dell          | Latitude 5420               | [4f3345aced](https://linux-hardware.org/?probe=4f3345aced) | Apr 16, 2023 |
| Acer          | Swift SF314-41              | [8c42a0aba8](https://linux-hardware.org/?probe=8c42a0aba8) | Apr 16, 2023 |
| Dell          | XPS 13 9305                 | [838519057f](https://linux-hardware.org/?probe=838519057f) | Apr 16, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | [d532f6fdbd](https://linux-hardware.org/?probe=d532f6fdbd) | Apr 16, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [c622c73721](https://linux-hardware.org/?probe=c622c73721) | Apr 16, 2023 |
| HP            | Notebook                    | [7614984f1d](https://linux-hardware.org/?probe=7614984f1d) | Apr 15, 2023 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [8ca60a45fe](https://linux-hardware.org/?probe=8ca60a45fe) | Apr 15, 2023 |
| HP            | EliteBook 850 G4            | [984cf8fd47](https://linux-hardware.org/?probe=984cf8fd47) | Apr 14, 2023 |
| Acer          | Aspire E5-575G              | [39afaea9e3](https://linux-hardware.org/?probe=39afaea9e3) | Apr 14, 2023 |
| HP            | Laptop 17-cp0xxx            | [6fdb6931f0](https://linux-hardware.org/?probe=6fdb6931f0) | Apr 14, 2023 |
| HP            | 255 G8 Notebook PC          | [58ec498e8f](https://linux-hardware.org/?probe=58ec498e8f) | Apr 14, 2023 |
| Acer          | Extensa 5635Z               | [b3c99bf352](https://linux-hardware.org/?probe=b3c99bf352) | Apr 14, 2023 |
| Notebook      | N7x0WU                      | [5d37070bf0](https://linux-hardware.org/?probe=5d37070bf0) | Apr 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [6af1f492c4](https://linux-hardware.org/?probe=6af1f492c4) | Apr 14, 2023 |
| Lenovo        | Flex 2-14 20404             | [c76a516113](https://linux-hardware.org/?probe=c76a516113) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | [9ab8e04a20](https://linux-hardware.org/?probe=9ab8e04a20) | Apr 14, 2023 |
| Acer          | AO756                       | [58efd2f87f](https://linux-hardware.org/?probe=58efd2f87f) | Apr 14, 2023 |
| Toshiba       | Satellite L850              | [15de4db91b](https://linux-hardware.org/?probe=15de4db91b) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | [1a327ce647](https://linux-hardware.org/?probe=1a327ce647) | Apr 13, 2023 |
| Dell          | G15 5510                    | [6b4ef54307](https://linux-hardware.org/?probe=6b4ef54307) | Apr 13, 2023 |
| Dell          | Inspiron 1525               | [bc3ccff50c](https://linux-hardware.org/?probe=bc3ccff50c) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [60f7db51fa](https://linux-hardware.org/?probe=60f7db51fa) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e9708d65e9](https://linux-hardware.org/?probe=e9708d65e9) | Apr 13, 2023 |
| Acer          | Aspire A315-51              | [c3962286cb](https://linux-hardware.org/?probe=c3962286cb) | Apr 13, 2023 |
| Apple         | MacBookPro5,5               | [401c4d8143](https://linux-hardware.org/?probe=401c4d8143) | Apr 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | [abedf2741f](https://linux-hardware.org/?probe=abedf2741f) | Apr 12, 2023 |
| HP            | ZBook 15 G3                 | [5411d789c3](https://linux-hardware.org/?probe=5411d789c3) | Apr 12, 2023 |
| Dell          | Latitude 5490               | [38ebdedf58](https://linux-hardware.org/?probe=38ebdedf58) | Apr 12, 2023 |
| HP            | Pavilion dv6                | [09b80dd551](https://linux-hardware.org/?probe=09b80dd551) | Apr 12, 2023 |
| HP            | Pavilion dv7                | [4363479bf0](https://linux-hardware.org/?probe=4363479bf0) | Apr 12, 2023 |
| Dell          | Inspiron 15-3567            | [23c158b19b](https://linux-hardware.org/?probe=23c158b19b) | Apr 12, 2023 |
| Lenovo        | ThinkPad E470 20H2S00700    | [ea2aa5245d](https://linux-hardware.org/?probe=ea2aa5245d) | Apr 11, 2023 |
| Samsung       | 550XCJ/550XCR               | [c074d665d9](https://linux-hardware.org/?probe=c074d665d9) | Apr 11, 2023 |
| Samsung       | 550XCJ/550XCR               | [845a04c326](https://linux-hardware.org/?probe=845a04c326) | Apr 11, 2023 |
| Packard Be... | EasyNote_MX45               | [95935443c0](https://linux-hardware.org/?probe=95935443c0) | Apr 11, 2023 |
| ASUSTek       | X550JF                      | [dff4654bd2](https://linux-hardware.org/?probe=dff4654bd2) | Apr 11, 2023 |
| Acer          | Aspire E1-571G              | [45a3503764](https://linux-hardware.org/?probe=45a3503764) | Apr 11, 2023 |
| Acer          | Aspire 5738                 | [c039220e20](https://linux-hardware.org/?probe=c039220e20) | Apr 11, 2023 |
| Aquarius      | NS585                       | [6f4b987640](https://linux-hardware.org/?probe=6f4b987640) | Apr 11, 2023 |
| Samsung       | 550XDA                      | [e1d5d2f193](https://linux-hardware.org/?probe=e1d5d2f193) | Apr 11, 2023 |
| Dell          | Inspiron 15 5510            | [5d84a5a711](https://linux-hardware.org/?probe=5d84a5a711) | Apr 10, 2023 |
| Apple         | MacBookAir7,2               | [94efe20a0f](https://linux-hardware.org/?probe=94efe20a0f) | Apr 10, 2023 |
| Dell          | Latitude 3320               | [b7c2bb88b3](https://linux-hardware.org/?probe=b7c2bb88b3) | Apr 10, 2023 |
| Dell          | Latitude 3320               | [436e7b8903](https://linux-hardware.org/?probe=436e7b8903) | Apr 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S0CE1M    | [eb794b0dc7](https://linux-hardware.org/?probe=eb794b0dc7) | Apr 10, 2023 |
| Lenovo        | ThinkPad L470 20J4000LGE    | [fec574fe0d](https://linux-hardware.org/?probe=fec574fe0d) | Apr 10, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | [885fff9ddb](https://linux-hardware.org/?probe=885fff9ddb) | Apr 10, 2023 |
| Lenovo        | ThinkPad L470 20J4000LGE    | [f97c4e6d47](https://linux-hardware.org/?probe=f97c4e6d47) | Apr 10, 2023 |
| Samsung       | RF511/RF411/RF711           | [ea4fdd80e6](https://linux-hardware.org/?probe=ea4fdd80e6) | Apr 09, 2023 |
| Lenovo        | ThinkPad X220 4291LR6       | [ea86227d59](https://linux-hardware.org/?probe=ea86227d59) | Apr 09, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [8d4288ca33](https://linux-hardware.org/?probe=8d4288ca33) | Apr 09, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Debian 11                       | 3338      | 60.56%  |
| Debian 10                       | 854       | 15.49%  |
| Debian 12                       | 502       | 9.11%   |
| Debian Testing                  | 357       | 6.48%   |
| Debian 9                        | 146       | 2.65%   |
| Debian                          | 139       | 2.52%   |
| Debian Unstable                 | 128       | 2.32%   |
| Debian 11-updates               | 27        | 0.49%   |
| Debian 8                        | 10        | 0.18%   |
| Debian Sid                      | 4         | 0.07%   |
| Debian Testing/unstable         | 2         | 0.04%   |
| Debian 22                       | 2         | 0.04%   |
| Debian Testing-proposed-updates | 1         | 0.02%   |
| Debian 99                       | 1         | 0.02%   |
| Debian 23                       | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Debian | 5299      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.10.0-8-amd64    | 585       | 9.67%   |
| 5.10.0-10-amd64   | 491       | 8.11%   |
| 5.10.0-20-amd64   | 242       | 4%      |
| 5.10.0-21-amd64   | 238       | 3.93%   |
| 5.10.0-18-amd64   | 177       | 2.92%   |
| 5.10.0-9-amd64    | 173       | 2.86%   |
| 6.1.0-9-amd64     | 171       | 2.83%   |
| 5.10.0-7-amd64    | 171       | 2.83%   |
| 5.10.0-16-amd64   | 167       | 2.76%   |
| 5.10.0-19-amd64   | 162       | 2.68%   |
| 5.10.0-13-amd64   | 151       | 2.5%    |
| 6.1.0-10-amd64    | 134       | 2.21%   |
| 5.10.0-11-amd64   | 105       | 1.73%   |
| 5.10.0-23-amd64   | 101       | 1.67%   |
| 4.19.0-9-amd64    | 85        | 1.4%    |
| 4.19.0-6-amd64    | 82        | 1.35%   |
| 5.10.0-14-amd64   | 80        | 1.32%   |
| 5.10.0-17-amd64   | 73        | 1.21%   |
| 4.19.0-13-amd64   | 69        | 1.14%   |
| 4.19.0-8-amd64    | 68        | 1.12%   |
| 5.10.0-15-amd64   | 53        | 0.88%   |
| 4.19.0-16-amd64   | 53        | 0.88%   |
| 6.1.0-7-amd64     | 52        | 0.86%   |
| 4.19.0-10-amd64   | 52        | 0.86%   |
| 5.15.0-2-amd64    | 51        | 0.84%   |
| 5.10.0-2-amd64    | 49        | 0.81%   |
| 4.19.0-12-amd64   | 47        | 0.78%   |
| 4.19.0-14-amd64   | 42        | 0.69%   |
| 5.10.0-6-amd64    | 41        | 0.68%   |
| 5.10.0-22-amd64   | 41        | 0.68%   |
| 5.10.0-12-amd64   | 41        | 0.68%   |
| 6.1.0-4-amd64     | 40        | 0.66%   |
| 4.19.0-17-amd64   | 40        | 0.66%   |
| 4.9.0-8-amd64     | 39        | 0.64%   |
| 5.18.0-2-amd64    | 31        | 0.51%   |
| 5.10.0-3-amd64    | 31        | 0.51%   |
| 6.1.0-6-amd64     | 28        | 0.46%   |
| 6.0.0-6-amd64     | 27        | 0.45%   |
| 5.19.0-1-amd64    | 27        | 0.45%   |
| 5.10.0-13-686-pae | 26        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 3140      | 55.57%  |
| 4.19.0   | 655       | 11.59%  |
| 6.1.0    | 512       | 9.06%   |
| 6.0.0    | 147       | 2.6%    |
| 4.9.0    | 120       | 2.12%   |
| 5.18.0   | 106       | 1.88%   |
| 5.15.0   | 92        | 1.63%   |
| 5.9.0    | 74        | 1.31%   |
| 5.19.0   | 69        | 1.22%   |
| 5.16.0   | 69        | 1.22%   |
| 5.4.0    | 64        | 1.13%   |
| 5.7.0    | 59        | 1.04%   |
| 5.8.0    | 56        | 0.99%   |
| 5.14.0   | 53        | 0.94%   |
| 5.6.0    | 45        | 0.8%    |
| 5.17.0   | 39        | 0.69%   |
| 6.3.0    | 28        | 0.5%    |
| 5.3.0    | 19        | 0.34%   |
| 5.5.0    | 16        | 0.28%   |
| 6.4.0    | 12        | 0.21%   |
| 5.2.0    | 12        | 0.21%   |
| 4.18.0   | 12        | 0.21%   |
| 3.16.0   | 8         | 0.14%   |
| 6.2.16   | 6         | 0.11%   |
| 5.12.0   | 6         | 0.11%   |
| 5.10.10  | 4         | 0.07%   |
| 6.4.3    | 3         | 0.05%   |
| 6.4.2    | 3         | 0.05%   |
| 6.3.4    | 3         | 0.05%   |
| 6.2.8    | 3         | 0.05%   |
| 5.3.5    | 3         | 0.05%   |
| 5.17.5   | 3         | 0.05%   |
| 5.15.107 | 3         | 0.05%   |
| 5.13.19  | 3         | 0.05%   |
| 5.13.0   | 3         | 0.05%   |
| 5.11.0   | 3         | 0.05%   |
| 5.10.60  | 3         | 0.05%   |
| 5.0.0    | 3         | 0.05%   |
| 6.3.9    | 2         | 0.04%   |
| 6.3.10   | 2         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 3166      | 56.13%  |
| 4.19    | 659       | 11.68%  |
| 6.1     | 521       | 9.24%   |
| 6.0     | 155       | 2.75%   |
| 4.9     | 123       | 2.18%   |
| 5.15    | 118       | 2.09%   |
| 5.18    | 111       | 1.97%   |
| 5.9     | 80        | 1.42%   |
| 5.4     | 76        | 1.35%   |
| 5.19    | 74        | 1.31%   |
| 5.16    | 73        | 1.29%   |
| 5.7     | 62        | 1.1%    |
| 5.8     | 61        | 1.08%   |
| 5.14    | 58        | 1.03%   |
| 5.6     | 49        | 0.87%   |
| 5.17    | 48        | 0.85%   |
| 6.3     | 36        | 0.64%   |
| 5.3     | 24        | 0.43%   |
| 6.4     | 20        | 0.35%   |
| 5.5     | 19        | 0.34%   |
| 5.2     | 18        | 0.32%   |
| 6.2     | 14        | 0.25%   |
| 5.13    | 12        | 0.21%   |
| 4.18    | 12        | 0.21%   |
| 5.12    | 9         | 0.16%   |
| 5.11    | 9         | 0.16%   |
| 3.16    | 8         | 0.14%   |
| 3.10    | 4         | 0.07%   |
| 5.1     | 3         | 0.05%   |
| 5.0     | 3         | 0.05%   |
| 4.17    | 2         | 0.04%   |
| 4.15    | 2         | 0.04%   |
| 4.14    | 2         | 0.04%   |
| 5.4.104 | 1         | 0.02%   |
| 5.15.6  | 1         | 0.02%   |
| 4.4     | 1         | 0.02%   |
| 4.20    | 1         | 0.02%   |
| 4.13    | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |
| 4.10    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 5057      | 95.42%  |
| i686    | 228       | 4.3%    |
| armv7l  | 10        | 0.19%   |
| aarch64 | 4         | 0.08%   |
| i586    | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 1496      | 27.5%   |
| Unknown           | 1271      | 23.36%  |
| KDE5              | 723       | 13.29%  |
| XFCE              | 717       | 13.18%  |
| MATE              | 235       | 4.32%   |
| X-Cinnamon        | 209       | 3.84%   |
| LXDE              | 161       | 2.96%   |
| Cinnamon          | 151       | 2.78%   |
| KDE               | 115       | 2.11%   |
| i3                | 98        | 1.8%    |
| LXQt              | 79        | 1.45%   |
| GNOME Flashback   | 39        | 0.72%   |
| lightdm-xsession  | 27        | 0.5%    |
| openbox           | 16        | 0.29%   |
| Budgie            | 16        | 0.29%   |
| GNOME Classic     | 15        | 0.28%   |
| trinity           | 14        | 0.26%   |
| sway              | 5         | 0.09%   |
| Enlightenment     | 5         | 0.09%   |
| Dwm               | 5         | 0.09%   |
| bspwm             | 5         | 0.09%   |
| awesome           | 5         | 0.09%   |
| ICEWM             | 4         | 0.07%   |
| Fluxbox           | 4         | 0.07%   |
| Cutefish          | 3         | 0.06%   |
| BunsenLabs        | 3         | 0.06%   |
| xmonad            | 2         | 0.04%   |
| x-session-manager | 2         | 0.04%   |
| Unity             | 2         | 0.04%   |
| KDE4              | 2         | 0.04%   |
| GNUstep           | 2         | 0.04%   |
| default           | 2         | 0.04%   |
| wmaker-common     | 1         | 0.02%   |
| Pantheon          | 1         | 0.02%   |
| mwm               | 1         | 0.02%   |
| matchbox          | 1         | 0.02%   |
| jwm               | 1         | 0.02%   |
| i3-gaps           | 1         | 0.02%   |
| Deepin            | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 3037      | 56.15%  |
| Wayland     | 1137      | 21.02%  |
| Unknown     | 1014      | 18.75%  |
| Tty         | 216       | 3.99%   |
| Unspecified | 4         | 0.07%   |
| Web         | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2070      | 38.05%  |
| GDM     | 996       | 18.31%  |
| LightDM | 946       | 17.39%  |
| SDDM    | 678       | 12.46%  |
| GDM3    | 373       | 6.86%   |
| TDM     | 310       | 5.7%    |
| XDM     | 20        | 0.37%   |
| SLiM    | 13        | 0.24%   |
| NODM    | 10        | 0.18%   |
| LXDM    | 8         | 0.15%   |
| KDM     | 8         | 0.15%   |
| Ly      | 4         | 0.07%   |
| GREETD  | 2         | 0.04%   |
| WDM     | 1         | 0.02%   |
| SU      | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1643      | 30.53%  |
| Unknown | 1000      | 18.58%  |
| ru_RU   | 366       | 6.8%    |
| de_DE   | 356       | 6.62%   |
| fr_FR   | 305       | 5.67%   |
| en_GB   | 246       | 4.57%   |
| pt_BR   | 181       | 3.36%   |
| es_ES   | 152       | 2.82%   |
| it_IT   | 144       | 2.68%   |
| pl_PL   | 108       | 2.01%   |
| en_CA   | 68        | 1.26%   |
| C       | 56        | 1.04%   |
| es_MX   | 50        | 0.93%   |
| en_AU   | 49        | 0.91%   |
| en_IN   | 47        | 0.87%   |
| zh_CN   | 45        | 0.84%   |
| es_AR   | 38        | 0.71%   |
| en_IE   | 32        | 0.59%   |
| es_CL   | 29        | 0.54%   |
| hu_HU   | 28        | 0.52%   |
| sv_SE   | 27        | 0.5%    |
| de_CH   | 21        | 0.39%   |
| pt_PT   | 19        | 0.35%   |
| fi_FI   | 19        | 0.35%   |
| es_VE   | 19        | 0.35%   |
| nl_NL   | 18        | 0.33%   |
| de_AT   | 16        | 0.3%    |
| cs_CZ   | 16        | 0.3%    |
| es_CO   | 15        | 0.28%   |
| en_NZ   | 15        | 0.28%   |
| tr_TR   | 14        | 0.26%   |
| ja_JP   | 14        | 0.26%   |
| fr_BE   | 12        | 0.22%   |
| en_ZA   | 12        | 0.22%   |
| ko_KR   | 11        | 0.2%    |
| en_SG   | 11        | 0.2%    |
| ru_UA   | 9         | 0.17%   |
| fr_CH   | 9         | 0.17%   |
| ca_ES   | 9         | 0.17%   |
| sk_SK   | 8         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 3282      | 61.28%  |
| BIOS | 2074      | 38.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 3849      | 72.24%  |
| Overlay | 1105      | 20.74%  |
| Btrfs   | 175       | 3.28%   |
| Unknown | 78        | 1.46%   |
| Xfs     | 49        | 0.92%   |
| Tmpfs   | 19        | 0.36%   |
| Zfs     | 17        | 0.32%   |
| Ext2    | 15        | 0.28%   |
| Rootfs  | 10        | 0.19%   |
| Ext3    | 6         | 0.11%   |
| Aufs    | 4         | 0.08%   |
| F2fs    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 3312      | 61.54%  |
| Unknown | 1039      | 19.31%  |
| MBR     | 1031      | 19.16%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4452      | 82.92%  |
| Yes       | 917       | 17.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3971      | 74.15%  |
| Yes       | 1384      | 25.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1175      | 22.17%  |
| Hewlett-Packard        | 796       | 15.02%  |
| Dell                   | 780       | 14.72%  |
| Apple                  | 662       | 12.49%  |
| ASUSTek Computer       | 479       | 9.04%   |
| Acer                   | 361       | 6.81%   |
| Google                 | 152       | 2.87%   |
| Toshiba                | 91        | 1.72%   |
| MSI                    | 89        | 1.68%   |
| Samsung Electronics    | 79        | 1.49%   |
| Aquarius               | 48        | 0.91%   |
| Sony                   | 45        | 0.85%   |
| HUAWEI                 | 45        | 0.85%   |
| Unknown                | 45        | 0.85%   |
| Notebook               | 31        | 0.59%   |
| Fujitsu                | 31        | 0.59%   |
| Medion                 | 17        | 0.32%   |
| Positivo               | 14        | 0.26%   |
| Panasonic              | 14        | 0.26%   |
| Packard Bell           | 14        | 0.26%   |
| Intel                  | 14        | 0.26%   |
| TUXEDO                 | 13        | 0.25%   |
| Timi                   | 13        | 0.25%   |
| IBM                    | 13        | 0.25%   |
| Alienware              | 13        | 0.25%   |
| LG Electronics         | 11        | 0.21%   |
| HONOR                  | 11        | 0.21%   |
| Clevo                  | 11        | 0.21%   |
| PC Specialist          | 8         | 0.15%   |
| Fujitsu Siemens        | 8         | 0.15%   |
| Razer                  | 7         | 0.13%   |
| GPU Company            | 7         | 0.13%   |
| eMachines              | 7         | 0.13%   |
| System76               | 6         | 0.11%   |
| SLIMBOOK               | 6         | 0.11%   |
| Gigabyte Technology    | 6         | 0.11%   |
| Chuwi                  | 6         | 0.11%   |
| Avell High Performance | 6         | 0.11%   |
| Schenker               | 5         | 0.09%   |
| NEC Computers          | 4         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBook5,2                      | 355       | 6.7%    |
| Apple MacBookAir7,2                   | 79        | 1.49%   |
| Apple MacBookAir7,1                   | 77        | 1.45%   |
| Google Enguarde                       | 74        | 1.4%    |
| Unknown                               | 58        | 1.09%   |
| Apple MacBook2,1                      | 57        | 1.08%   |
| Aquarius NS585                        | 48        | 0.91%   |
| HP Notebook                           | 27        | 0.51%   |
| Lenovo ThinkPad E475 20H40006US       | 24        | 0.45%   |
| Google Terra                          | 23        | 0.43%   |
| Apple MacBook4,1                      | 23        | 0.43%   |
| HP Pavilion g6                        | 17        | 0.32%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US | 16        | 0.3%    |
| Acer Aspire A315-23                   | 16        | 0.3%    |
| ASUS 1005HA                           | 15        | 0.28%   |
| Google Reks                           | 14        | 0.26%   |
| HP Laptop 15-db0xxx                   | 13        | 0.25%   |
| HP EliteBook 840 G3                   | 13        | 0.25%   |
| Dell Latitude E7440                   | 13        | 0.25%   |
| Dell Latitude 7480                    | 13        | 0.25%   |
| Dell Latitude E6430                   | 12        | 0.23%   |
| HP Pavilion dv6                       | 11        | 0.21%   |
| HP EliteBook 8460p                    | 11        | 0.21%   |
| HP 255 G8 Notebook PC                 | 11        | 0.21%   |
| Dell Latitude E7450                   | 11        | 0.21%   |
| Dell Inspiron 5570                    | 10        | 0.19%   |
| HP Pavilion Notebook                  | 9         | 0.17%   |
| HP Laptop 15s-eq2xxx                  | 9         | 0.17%   |
| HP 250 G7 Notebook PC                 | 9         | 0.17%   |
| Dell XPS 13 9310                      | 9         | 0.17%   |
| Dell Latitude E6420                   | 9         | 0.17%   |
| Dell Latitude 5420                    | 9         | 0.17%   |
| Dell Inspiron 15-3567                 | 9         | 0.17%   |
| Samsung 300E4C/300E5C/300E7C          | 8         | 0.15%   |
| HP Pavilion Gaming Laptop 15-ec2xxx   | 8         | 0.15%   |
| HP Laptop 15-db1xxx                   | 8         | 0.15%   |
| HP EliteBook 840 G1                   | 8         | 0.15%   |
| Dell XPS 13 7390                      | 8         | 0.15%   |
| Dell Latitude E6330                   | 8         | 0.15%   |
| Dell Latitude 7490                    | 8         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 774       | 14.61%  |
| Apple MacBook5    | 356       | 6.72%   |
| Dell Latitude     | 306       | 5.77%   |
| Acer Aspire       | 236       | 4.45%   |
| Dell Inspiron     | 229       | 4.32%   |
| Lenovo IdeaPad    | 207       | 3.91%   |
| HP EliteBook      | 169       | 3.19%   |
| Apple MacBookAir7 | 156       | 2.94%   |
| HP Pavilion       | 123       | 2.32%   |
| HP Laptop         | 107       | 2.02%   |
| HP ProBook        | 103       | 1.94%   |
| Dell XPS          | 82        | 1.55%   |
| ASUS VivoBook     | 75        | 1.42%   |
| Google Enguarde   | 74        | 1.4%    |
| Toshiba Satellite | 71        | 1.34%   |
| Dell Vostro       | 65        | 1.23%   |
| Dell Precision    | 60        | 1.13%   |
| Unknown           | 58        | 1.09%   |
| Apple MacBook2    | 57        | 1.08%   |
| Aquarius NS585    | 48        | 0.91%   |
| HP Compaq         | 43        | 0.81%   |
| HP ZBook          | 34        | 0.64%   |
| ASUS ZenBook      | 34        | 0.64%   |
| HP 250            | 32        | 0.6%    |
| Lenovo Legion     | 30        | 0.57%   |
| ASUS ASUS         | 29        | 0.55%   |
| Acer TravelMate   | 29        | 0.55%   |
| Acer Nitro        | 28        | 0.53%   |
| HP Notebook       | 27        | 0.51%   |
| Fujitsu LIFEBOOK  | 27        | 0.51%   |
| Acer Swift        | 26        | 0.49%   |
| Lenovo ThinkBook  | 25        | 0.47%   |
| HP 255            | 24        | 0.45%   |
| Google Terra      | 23        | 0.43%   |
| Apple MacBook4    | 23        | 0.43%   |
| HP ENVY           | 20        | 0.38%   |
| ASUS ROG          | 20        | 0.38%   |
| HP OMEN           | 19        | 0.36%   |
| Lenovo Yoga       | 15        | 0.28%   |
| ASUS TUF          | 15        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 511       | 9.64%   |
| 2009    | 507       | 9.57%   |
| 2021    | 477       | 9%      |
| 2020    | 477       | 9%      |
| 2018    | 338       | 6.38%   |
| 2012    | 334       | 6.3%    |
| 2016    | 326       | 6.15%   |
| 2017    | 324       | 6.11%   |
| 2011    | 323       | 6.1%    |
| 2015    | 299       | 5.64%   |
| 2013    | 272       | 5.13%   |
| 2014    | 246       | 4.64%   |
| 2022    | 240       | 4.53%   |
| 2010    | 205       | 3.87%   |
| 2008    | 161       | 3.04%   |
| 2007    | 134       | 2.53%   |
| 2006    | 37        | 0.7%    |
| 2005    | 26        | 0.49%   |
| 2023    | 22        | 0.42%   |
| Unknown | 16        | 0.3%    |
| 2004    | 11        | 0.21%   |
| 2003    | 11        | 0.21%   |
| 2002    | 2         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 5299      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4873      | 91.49%  |
| Enabled  | 453       | 8.51%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5132      | 96.83%  |
| Yes  | 168       | 3.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1408      | 26.32%  |
| 3.01-4.0    | 1013      | 18.94%  |
| 16.01-24.0  | 874       | 16.34%  |
| 8.01-16.0   | 840       | 15.7%   |
| 1.01-2.0    | 577       | 10.79%  |
| 32.01-64.0  | 311       | 5.81%   |
| 2.01-3.0    | 108       | 2.02%   |
| 0.51-1.0    | 84        | 1.57%   |
| 64.01-256.0 | 60        | 1.12%   |
| 24.01-32.0  | 51        | 0.95%   |
| 0.01-0.5    | 21        | 0.39%   |
| Unknown     | 2         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2154      | 37.88%  |
| 2.01-3.0   | 1201      | 21.12%  |
| 4.01-8.0   | 782       | 13.75%  |
| 3.01-4.0   | 607       | 10.67%  |
| 0.51-1.0   | 558       | 9.81%   |
| 8.01-16.0  | 213       | 3.75%   |
| 0.01-0.5   | 139       | 2.44%   |
| 16.01-24.0 | 17        | 0.3%    |
| Unknown    | 7         | 0.12%   |
| 32.01-64.0 | 4         | 0.07%   |
| 24.01-32.0 | 4         | 0.07%   |
| 0          | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4169      | 77.55%  |
| 2      | 1027      | 19.1%   |
| 3      | 119       | 2.21%   |
| 0      | 34        | 0.63%   |
| 4      | 20        | 0.37%   |
| 5      | 5         | 0.09%   |
| 7      | 2         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3508      | 65.94%  |
| Yes       | 1812      | 34.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4323      | 81.27%  |
| No        | 996       | 18.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5191      | 97.87%  |
| No        | 113       | 2.13%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4262      | 79.87%  |
| No        | 1074      | 20.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 1330      | 24.93%  |
| Germany     | 513       | 9.61%   |
| Russia      | 422       | 7.91%   |
| France      | 376       | 7.05%   |
| Brazil      | 267       | 5%      |
| Spain       | 217       | 4.07%   |
| Italy       | 198       | 3.71%   |
| Poland      | 155       | 2.9%    |
| UK          | 126       | 2.36%   |
| Canada      | 93        | 1.74%   |
| Netherlands | 91        | 1.71%   |
| Switzerland | 72        | 1.35%   |
| Mexico      | 72        | 1.35%   |
| India       | 70        | 1.31%   |
| Sweden      | 67        | 1.26%   |
| China       | 65        | 1.22%   |
| Argentina   | 60        | 1.12%   |
| Australia   | 59        | 1.11%   |
| Ukraine     | 57        | 1.07%   |
| Turkey      | 52        | 0.97%   |
| Hungary     | 46        | 0.86%   |
| Portugal    | 45        | 0.84%   |
| Belgium     | 44        | 0.82%   |
| Austria     | 43        | 0.81%   |
| Czechia     | 39        | 0.73%   |
| Chile       | 36        | 0.67%   |
| Greece      | 35        | 0.66%   |
| Finland     | 35        | 0.66%   |
| Norway      | 33        | 0.62%   |
| Romania     | 31        | 0.58%   |
| Indonesia   | 27        | 0.51%   |
| Colombia    | 26        | 0.49%   |
| Japan       | 25        | 0.47%   |
| Ireland     | 25        | 0.47%   |
| Venezuela   | 23        | 0.43%   |
| New Zealand | 20        | 0.37%   |
| Bulgaria    | 20        | 0.37%   |
| Thailand    | 19        | 0.36%   |
| Denmark     | 19        | 0.36%   |
| Belarus     | 18        | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Bangor            | 628       | 11.12%  |
| Dover-Foxcroft    | 229       | 4.05%   |
| Voronezh          | 162       | 2.87%   |
| Moscow            | 74        | 1.31%   |
| Paris             | 65        | 1.15%   |
| St Petersburg     | 54        | 0.96%   |
| Berlin            | 50        | 0.89%   |
| Madrid            | 42        | 0.74%   |
| Seville           | 39        | 0.69%   |
| Sao Paulo         | 38        | 0.67%   |
| Warsaw            | 37        | 0.65%   |
| Munich            | 33        | 0.58%   |
| Vienna            | 29        | 0.51%   |
| Milan             | 27        | 0.48%   |
| Hamburg           | 27        | 0.48%   |
| Amsterdam         | 27        | 0.48%   |
| London            | 23        | 0.41%   |
| Barcelona         | 22        | 0.39%   |
| Prague            | 21        | 0.37%   |
| Istanbul          | 21        | 0.37%   |
| Frankfurt am Main | 19        | 0.34%   |
| Budapest          | 19        | 0.34%   |
| Zurich            | 18        | 0.32%   |
| Sydney            | 18        | 0.32%   |
| Brasília         | 18        | 0.32%   |
| Athens            | 18        | 0.32%   |
| Dublin            | 17        | 0.3%    |
| Mexico City       | 16        | 0.28%   |
| Singapore         | 15        | 0.27%   |
| Saltsjoe-Boo      | 15        | 0.27%   |
| Lisbon            | 15        | 0.27%   |
| Helsinki          | 15        | 0.27%   |
| Toronto           | 14        | 0.25%   |
| Perm              | 14        | 0.25%   |
| Cologne           | 14        | 0.25%   |
| Rome              | 13        | 0.23%   |
| Melbourne         | 13        | 0.23%   |
| Leipzig           | 13        | 0.23%   |
| Bangkok           | 13        | 0.23%   |
| San Jose          | 12        | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 950       | 1210   | 14.84%  |
| WDC                       | 719       | 885    | 11.23%  |
| Seagate                   | 575       | 687    | 8.98%   |
| Toshiba                   | 478       | 532    | 7.47%   |
| Unknown                   | 412       | 531    | 6.44%   |
| Kingston                  | 351       | 425    | 5.48%   |
| SanDisk                   | 317       | 390    | 4.95%   |
| Fujitsu                   | 293       | 302    | 4.58%   |
| SK hynix                  | 253       | 308    | 3.95%   |
| Crucial                   | 243       | 294    | 3.8%    |
| Apple                     | 192       | 245    | 3%      |
| Hitachi                   | 173       | 199    | 2.7%    |
| Micron Technology         | 156       | 170    | 2.44%   |
| Intel                     | 154       | 190    | 2.41%   |
| A-DATA Technology         | 138       | 269    | 2.16%   |
| HGST                      | 129       | 149    | 2.02%   |
| KIOXIA                    | 70        | 84     | 1.09%   |
| China                     | 41        | 47     | 0.64%   |
| LITEON                    | 38        | 46     | 0.59%   |
| Unknown                   | 35        | 38     | 0.55%   |
| Intenso                   | 30        | 39     | 0.47%   |
| Transcend                 | 29        | 36     | 0.45%   |
| SPCC                      | 27        | 32     | 0.42%   |
| PNY                       | 27        | 34     | 0.42%   |
| Phison                    | 27        | 36     | 0.42%   |
| Silicon Motion            | 26        | 31     | 0.41%   |
| Patriot                   | 23        | 25     | 0.36%   |
| SSSTC                     | 22        | 22     | 0.34%   |
| JMicron Technology        | 21        | 22     | 0.33%   |
| LITEONIT                  | 20        | 24     | 0.31%   |
| Team                      | 18        | 20     | 0.28%   |
| SABRENT                   | 18        | 19     | 0.28%   |
| Netac                     | 14        | 19     | 0.22%   |
| GOODRAM                   | 14        | 16     | 0.22%   |
| OCZ                       | 13        | 15     | 0.2%    |
| Micron/Crucial Technology | 13        | 13     | 0.2%    |
| Lenovo                    | 10        | 12     | 0.16%   |
| Hewlett-Packard           | 10        | 11     | 0.16%   |
| ADATA Technology          | 10        | 10     | 0.16%   |
| Plextor                   | 9         | 9      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB       | 238       | 3.63%   |
| Apple SSD AP0128H 121GB              | 77        | 1.17%   |
| Seagate ST1000LM035-1RK172 1TB       | 74        | 1.13%   |
| Apple SSD SM0128G 121GB              | 73        | 1.11%   |
| Kingston SA400S37240G 240GB SSD      | 66        | 1.01%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 59        | 0.9%    |
| Kingston SA400S37120G 120GB SSD      | 57        | 0.87%   |
| Toshiba MK1655GSXF 160GB             | 52        | 0.79%   |
| A-DATA SU800 512GB SSD               | 50        | 0.76%   |
| Toshiba MQ01ABD100 1TB               | 47        | 0.72%   |
| HGST HTS721010A9E630 1TB             | 45        | 0.69%   |
| Toshiba MK1653GSX 160GB              | 43        | 0.66%   |
| Toshiba MQ04ABF100 1TB               | 40        | 0.61%   |
| Crucial CT500MX500SSD1 500GB         | 40        | 0.61%   |
| Unknown AGND3R  16GB                 | 39        | 0.59%   |
| Toshiba MQ01ABF050 500GB             | 38        | 0.58%   |
| Unknown MMC Card  32GB               | 36        | 0.55%   |
| Unknown                              | 35        | 0.53%   |
| Kingston SA400S37480G 480GB SSD      | 34        | 0.52%   |
| Samsung SSD 860 EVO 500GB            | 33        | 0.5%    |
| Unknown HAG2e  16GB                  | 32        | 0.49%   |
| Samsung SSD 850 EVO 250GB            | 32        | 0.49%   |
| Samsung SSD 970 EVO Plus 1TB         | 30        | 0.46%   |
| Crucial CT1000MX500SSD1 1TB          | 30        | 0.46%   |
| Seagate ST500LT012-1DG142 500GB      | 28        | 0.43%   |
| Seagate ST1000LM048-2E7172 1TB       | 27        | 0.41%   |
| Unknown SDW16G  16GB                 | 25        | 0.38%   |
| Unknown MMC Card  64GB               | 25        | 0.38%   |
| Samsung SSD 860 EVO 1TB              | 25        | 0.38%   |
| Seagate ST9500325AS 500GB            | 24        | 0.37%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 23        | 0.35%   |
| Samsung SSD 860 EVO 250GB            | 23        | 0.35%   |
| Kingston SV300S37A120G 120GB SSD     | 23        | 0.35%   |
| HGST HTS725050A7E630 500GB           | 22        | 0.34%   |
| Samsung SSD 980 1TB                  | 21        | 0.32%   |
| Samsung SSD 850 EVO 500GB            | 21        | 0.32%   |
| Crucial CT240BX500SSD1 240GB         | 21        | 0.32%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 20        | 0.31%   |
| WDC WD10SPZX-24Z10 1TB               | 19        | 0.29%   |
| Seagate ST1000LM049-2GH172 1TB       | 19        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 554       | 662    | 27.7%   |
| WDC                 | 409       | 469    | 20.45%  |
| Toshiba             | 349       | 382    | 17.45%  |
| Fujitsu             | 293       | 302    | 14.65%  |
| Hitachi             | 173       | 199    | 8.65%   |
| HGST                | 129       | 149    | 6.45%   |
| Samsung Electronics | 35        | 37     | 1.75%   |
| Unknown             | 16        | 19     | 0.8%    |
| JMicron Technology  | 12        | 12     | 0.6%    |
| ASMT                | 6         | 13     | 0.3%    |
| IBM/Hitachi         | 5         | 6      | 0.25%   |
| Intenso             | 4         | 5      | 0.2%    |
| Apple               | 3         | 4      | 0.15%   |
| SILICONMOTION       | 2         | 2      | 0.1%    |
| WALRAM              | 1         | 1      | 0.05%   |
| USB3.0              | 1         | 1      | 0.05%   |
| Unknown (CF)        | 1         | 1      | 0.05%   |
| SYMTEC              | 1         | 1      | 0.05%   |
| QNAP                | 1         | 2      | 0.05%   |
| PHD 3.0             | 1         | 1      | 0.05%   |
| Maxone              | 1         | 1      | 0.05%   |
| IBM                 | 1         | 1      | 0.05%   |
| Hewlett-Packard     | 1         | 1      | 0.05%   |
| External            | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 418       | 523    | 20.12%  |
| Kingston            | 271       | 340    | 13.04%  |
| SanDisk             | 219       | 278    | 10.54%  |
| Crucial             | 217       | 264    | 10.44%  |
| Apple               | 102       | 117    | 4.91%   |
| A-DATA Technology   | 100       | 215    | 4.81%   |
| WDC                 | 91        | 118    | 4.38%   |
| Micron Technology   | 59        | 65     | 2.84%   |
| SK hynix            | 52        | 60     | 2.5%    |
| Intel               | 45        | 49     | 2.17%   |
| China               | 41        | 47     | 1.97%   |
| Toshiba             | 35        | 39     | 1.68%   |
| LITEON              | 32        | 37     | 1.54%   |
| Transcend           | 26        | 33     | 1.25%   |
| Intenso             | 24        | 31     | 1.15%   |
| PNY                 | 23        | 29     | 1.11%   |
| SPCC                | 21        | 25     | 1.01%   |
| Patriot             | 20        | 22     | 0.96%   |
| LITEONIT            | 20        | 24     | 0.96%   |
| Team                | 17        | 19     | 0.82%   |
| OCZ                 | 13        | 15     | 0.63%   |
| Netac               | 13        | 18     | 0.63%   |
| GOODRAM             | 11        | 13     | 0.53%   |
| Plextor             | 9         | 9      | 0.43%   |
| Lexar               | 8         | 9      | 0.38%   |
| LDLC                | 8         | 8      | 0.38%   |
| KingSpec            | 8         | 8      | 0.38%   |
| Apacer              | 8         | 8      | 0.38%   |
| Unknown             | 8         | 8      | 0.38%   |
| KingDian            | 7         | 7      | 0.34%   |
| Seagate             | 6         | 6      | 0.29%   |
| Hewlett-Packard     | 6         | 8      | 0.29%   |
| Corsair             | 6         | 6      | 0.29%   |
| TO Exter            | 5         | 6      | 0.24%   |
| Gigabyte Technology | 5         | 5      | 0.24%   |
| Lenovo              | 4         | 4      | 0.19%   |
| KIOXIA-EXCERIA      | 4         | 5      | 0.19%   |
| FORESEE             | 4         | 4      | 0.19%   |
| Dogfish             | 4         | 7      | 0.19%   |
| BIWIN               | 4         | 4      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1952      | 2272   | 31.82%  |
| SSD     | 1938      | 2626   | 31.59%  |
| NVMe    | 1742      | 2281   | 28.39%  |
| MMC     | 439       | 561    | 7.16%   |
| Unknown | 64        | 72     | 1.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3507      | 4739   | 59.76%  |
| NVMe | 1728      | 2256   | 29.45%  |
| MMC  | 439       | 561    | 7.48%   |
| SAS  | 194       | 256    | 3.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2736      | 3432   | 71.36%  |
| 0.51-1.0   | 991       | 1325   | 25.85%  |
| 1.01-2.0   | 84        | 106    | 2.19%   |
| 4.01-10.0  | 16        | 23     | 0.42%   |
| 3.01-4.0   | 6         | 11     | 0.16%   |
| 2.01-3.0   | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1539      | 28.03%  |
| 251-500        | 1170      | 21.31%  |
| Unknown        | 820       | 14.93%  |
| 501-1000       | 716       | 13.04%  |
| 51-100         | 356       | 6.48%   |
| 1001-2000      | 296       | 5.39%   |
| 1-20           | 268       | 4.88%   |
| 21-50          | 204       | 3.72%   |
| 2001-3000      | 64        | 1.17%   |
| More than 3000 | 58        | 1.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2019      | 35.61%  |
| Unknown        | 820       | 14.46%  |
| 21-50          | 738       | 13.02%  |
| 101-250        | 735       | 12.96%  |
| 51-100         | 593       | 10.46%  |
| 251-500        | 393       | 6.93%   |
| 501-1000       | 240       | 4.23%   |
| 1001-2000      | 83        | 1.46%   |
| More than 3000 | 22        | 0.39%   |
| 2001-3000      | 16        | 0.28%   |
| 0              | 11        | 0.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB        | 25        | 25     | 4.68%   |
| Seagate ST9500325AS 500GB             | 13        | 13     | 2.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 11        | 13     | 2.06%   |
| Hitachi HTS543216L9SA02 160GB         | 11        | 11     | 2.06%   |
| Toshiba MQ01ABD100 1TB                | 9         | 9      | 1.69%   |
| Toshiba MK1653GSX 160GB               | 9         | 9      | 1.69%   |
| Toshiba MK1655GSXF 160GB              | 8         | 8      | 1.5%    |
| Seagate ST9500420AS 500GB             | 8         | 8      | 1.5%    |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 7         | 9      | 1.31%   |
| Seagate ST500LM021-1KJ152 500GB       | 7         | 7      | 1.31%   |
| Hitachi HTS545050B9A300 500GB         | 7         | 7      | 1.31%   |
| Seagate ST1000LM035-1RK172 1TB        | 6         | 7      | 1.12%   |
| HGST HTS725050A7E630 500GB            | 6         | 7      | 1.12%   |
| HGST HTS541010A9E680 1TB              | 6         | 6      | 1.12%   |
| Toshiba MQ01ABF050 500GB              | 5         | 5      | 0.94%   |
| Seagate ST500LT012-9WS142 500GB       | 5         | 6      | 0.94%   |
| Hitachi HTS542512K9SA00 120GB         | 5         | 6      | 0.94%   |
| WDC WD1600BUDT-63DPZY0 160GB          | 4         | 4      | 0.75%   |
| Seagate ST9320325AS 320GB             | 4         | 4      | 0.75%   |
| Seagate ST500LM000-SSHD-8GB           | 4         | 4      | 0.75%   |
| Seagate ST320LT007-9ZV142 320GB       | 4         | 6      | 0.75%   |
| Kingston SV300S37A120G 120GB SSD      | 4         | 4      | 0.75%   |
| Kingston SA400S37240G 240GB SSD       | 4         | 4      | 0.75%   |
| Hitachi HTS547575A9E384 752GB         | 4         | 4      | 0.75%   |
| Crucial CT275MX300SSD1 275GB          | 4         | 4      | 0.75%   |
| Toshiba MQ04ABF100 1TB                | 3         | 3      | 0.56%   |
| SK hynix HFS256G39MND-2300A 256GB SSD | 3         | 4      | 0.56%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 3         | 3      | 0.56%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 3         | 3      | 0.56%   |
| Seagate ST9250315AS 250GB             | 3         | 4      | 0.56%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 0.56%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 3         | 3      | 0.56%   |
| Samsung Electronics SSD 870 EVO 500GB | 3         | 3      | 0.56%   |
| Kingston SA400S37120G 120GB SSD       | 3         | 4      | 0.56%   |
| Hitachi HTS547550A9E384 500GB         | 3         | 3      | 0.56%   |
| Hitachi HTS543232A7A384 320GB         | 3         | 3      | 0.56%   |
| Hitachi HTS542516K9SA00 160GB         | 3         | 3      | 0.56%   |
| HGST HTS721010A9E630 1TB              | 3         | 4      | 0.56%   |
| HGST HTS545050A7E680 500GB            | 3         | 3      | 0.56%   |
| HGST HTS545050A7E380 500GB            | 3         | 3      | 0.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 109       | 119    | 20.45%  |
| Hitachi             | 77        | 83     | 14.45%  |
| Toshiba             | 66        | 67     | 12.38%  |
| WDC                 | 49        | 53     | 9.19%   |
| Fujitsu             | 40        | 40     | 7.5%    |
| HGST                | 32        | 34     | 6%      |
| Samsung Electronics | 27        | 29     | 5.07%   |
| SK hynix            | 26        | 29     | 4.88%   |
| Kingston            | 18        | 19     | 3.38%   |
| SanDisk             | 14        | 16     | 2.63%   |
| Micron Technology   | 13        | 14     | 2.44%   |
| Intel               | 12        | 13     | 2.25%   |
| Crucial             | 11        | 12     | 2.06%   |
| A-DATA Technology   | 10        | 11     | 1.88%   |
| LITEONIT            | 3         | 4      | 0.56%   |
| LITEON              | 3         | 3      | 0.56%   |
| SSSTC               | 2         | 2      | 0.38%   |
| KingSpec            | 2         | 2      | 0.38%   |
| JMicron Technology  | 2         | 2      | 0.38%   |
| IBM/Hitachi         | 2         | 2      | 0.38%   |
| Corsair             | 2         | 2      | 0.38%   |
| Apple               | 2         | 3      | 0.38%   |
| Unknown             | 2         | 2      | 0.38%   |
| Team                | 1         | 1      | 0.19%   |
| ShiJi               | 1         | 4      | 0.19%   |
| Plextor             | 1         | 1      | 0.19%   |
| Lenovo              | 1         | 1      | 0.19%   |
| KingDian            | 1         | 1      | 0.19%   |
| IBM                 | 1         | 1      | 0.19%   |
| GOODRAM             | 1         | 1      | 0.19%   |
| DGM                 | 1         | 1      | 0.19%   |
| China               | 1         | 1      | 0.19%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 109       | 119    | 27.95%  |
| Hitachi             | 77        | 83     | 19.74%  |
| Toshiba             | 65        | 66     | 16.67%  |
| WDC                 | 48        | 52     | 12.31%  |
| Fujitsu             | 40        | 40     | 10.26%  |
| HGST                | 32        | 34     | 8.21%   |
| Samsung Electronics | 14        | 14     | 3.59%   |
| IBM/Hitachi         | 2         | 2      | 0.51%   |
| JMicron Technology  | 1         | 1      | 0.26%   |
| IBM                 | 1         | 1      | 0.26%   |
| Apple               | 1         | 2      | 0.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 387       | 414    | 73.02%  |
| SSD     | 120       | 130    | 22.64%  |
| NVMe    | 22        | 28     | 4.15%   |
| Unknown | 1         | 1      | 0.19%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 11.11%  |
| Toshiba MQ04ABF100 1TB                          | 1         | 1      | 11.11%  |
| Toshiba MK6465GSX 640GB                         | 1         | 1      | 11.11%  |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 11.11%  |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 11.11%  |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 11.11%  |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 11.11%  |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 11.11%  |
| Crucial CT500P2SSD8 500GB                       | 1         | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 2      | 22.22%  |
| Seagate             | 2         | 2      | 22.22%  |
| Samsung Electronics | 2         | 2      | 22.22%  |
| WDC                 | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 2      | 11.11%  |
| Crucial             | 1         | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3607      | 4890   | 63.36%  |
| Detected | 1549      | 2338   | 27.21%  |
| Malfunc  | 527       | 573    | 9.26%   |
| Failed   | 9         | 10     | 0.16%   |
| Limited  | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3216      | 54.14%  |
| Samsung Electronics              | 599       | 10.08%  |
| AMD                              | 514       | 8.65%   |
| Nvidia                           | 382       | 6.43%   |
| SanDisk                          | 306       | 5.15%   |
| SK hynix                         | 188       | 3.16%   |
| Toshiba America Info Systems     | 102       | 1.72%   |
| Micron Technology                | 97        | 1.63%   |
| Kingston Technology Company      | 88        | 1.48%   |
| Apple                            | 86        | 1.45%   |
| KIOXIA                           | 69        | 1.16%   |
| Phison Electronics               | 49        | 0.82%   |
| ADATA Technology                 | 48        | 0.81%   |
| Micron/Crucial Technology        | 39        | 0.66%   |
| Silicon Motion                   | 38        | 0.64%   |
| Solid State Storage Technology   | 27        | 0.45%   |
| Union Memory (Shenzhen)          | 14        | 0.24%   |
| Silicon Integrated Systems [SiS] | 13        | 0.22%   |
| Realtek Semiconductor            | 8         | 0.13%   |
| Lite-On Technology               | 7         | 0.12%   |
| MAXIO Technology (Hangzhou)      | 6         | 0.1%    |
| Yangtze Memory Technologies      | 5         | 0.08%   |
| Shenzhen Longsys Electronics     | 5         | 0.08%   |
| Lenovo                           | 5         | 0.08%   |
| Seagate Technology               | 4         | 0.07%   |
| VIA Technologies                 | 3         | 0.05%   |
| ULi Electronics                  | 3         | 0.05%   |
| Silicon Image                    | 3         | 0.05%   |
| Marvell Technology Group         | 3         | 0.05%   |
| Jiangsu Huacun Elec.             | 3         | 0.05%   |
| Biwin Storage Technology         | 3         | 0.05%   |
| ASMedia Technology               | 2         | 0.03%   |
| Transcend                        | 1         | 0.02%   |
| JMicron Technology               | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |
| Adaptec                          | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 445       | 7%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 423       | 6.65%   |
| Nvidia MCP79 AHCI Controller                                                   | 365       | 5.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 351       | 5.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 245       | 3.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 237       | 3.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 222       | 3.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 164       | 2.58%   |
| Intel Volume Management Device NVMe RAID Controller                            | 161       | 2.53%   |
| Samsung NVMe SSD Controller 980                                                | 136       | 2.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 130       | 2.04%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 125       | 1.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 111       | 1.75%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 101       | 1.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 96        | 1.51%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 93        | 1.46%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 92        | 1.45%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 87        | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 87        | 1.37%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 85        | 1.34%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 83        | 1.3%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 82        | 1.29%   |
| Intel Tiger Lake-LP SATA Controller                                            | 82        | 1.29%   |
| Intel Comet Lake SATA AHCI Controller                                          | 79        | 1.24%   |
| Apple S1X NVMe Controller                                                      | 78        | 1.23%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 76        | 1.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 72        | 1.13%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 64        | 1.01%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 63        | 0.99%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 61        | 0.96%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 55        | 0.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 55        | 0.86%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 52        | 0.82%   |
| Intel SSD 660P Series                                                          | 51        | 0.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 49        | 0.77%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 48        | 0.75%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 47        | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 40        | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 39        | 0.61%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 39        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3627      | 58.68%  |
| NVMe | 1735      | 28.07%  |
| IDE  | 411       | 6.65%   |
| RAID | 407       | 6.58%   |
| SCSI | 1         | 0.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 4511      | 85.11%  |
| AMD          | 769       | 14.51%  |
| ARM          | 13        | 0.25%   |
| CentaurHauls | 5         | 0.09%   |
| Unknown      | 2         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 357       | 6.73%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 148       | 2.79%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 107       | 2.02%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 96        | 1.81%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 82        | 1.55%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 76        | 1.43%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 75        | 1.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 74        | 1.39%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 73        | 1.38%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 65        | 1.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 65        | 1.23%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 63        | 1.19%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 62        | 1.17%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 60        | 1.13%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 55        | 1.04%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 53        | 1%      |
| Intel Core i5-2520M CPU @ 2.50GHz             | 52        | 0.98%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 50        | 0.94%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 48        | 0.9%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 46        | 0.87%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 46        | 0.87%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 46        | 0.87%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 42        | 0.79%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 39        | 0.74%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 38        | 0.72%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 36        | 0.68%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 34        | 0.64%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 32        | 0.6%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 31        | 0.58%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 31        | 0.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 31        | 0.58%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 31        | 0.58%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 30        | 0.57%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 29        | 0.55%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 28        | 0.53%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 27        | 0.51%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 26        | 0.49%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 26        | 0.49%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 26        | 0.49%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 26        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1280      | 24.13%  |
| Intel Core i7           | 996       | 18.78%  |
| Intel Core 2 Duo        | 571       | 10.77%  |
| Other                   | 472       | 8.9%    |
| Intel Celeron           | 371       | 6.99%   |
| Intel Core i3           | 355       | 6.69%   |
| AMD Ryzen 5             | 220       | 4.15%   |
| Intel Atom              | 149       | 2.81%   |
| AMD Ryzen 7             | 144       | 2.71%   |
| Intel Pentium           | 99        | 1.87%   |
| Intel Core 2            | 73        | 1.38%   |
| AMD Ryzen 7 PRO         | 50        | 0.94%   |
| AMD A6                  | 40        | 0.75%   |
| Intel Pentium M         | 35        | 0.66%   |
| Intel Pentium Dual-Core | 33        | 0.62%   |
| AMD A4                  | 29        | 0.55%   |
| Intel Genuine           | 27        | 0.51%   |
| AMD Ryzen 3             | 25        | 0.47%   |
| Intel Pentium Dual      | 22        | 0.41%   |
| AMD Ryzen 9             | 22        | 0.41%   |
| AMD Ryzen 5 PRO         | 22        | 0.41%   |
| AMD A8                  | 22        | 0.41%   |
| AMD E                   | 19        | 0.36%   |
| AMD E1                  | 18        | 0.34%   |
| AMD A10                 | 16        | 0.3%    |
| AMD E2                  | 15        | 0.28%   |
| Intel Celeron M         | 14        | 0.26%   |
| Intel Pentium Silver    | 12        | 0.23%   |
| Intel Core i9           | 11        | 0.21%   |
| Intel Pentium 4         | 9         | 0.17%   |
| Intel Core m3           | 8         | 0.15%   |
| AMD Turion 64 X2 Mobile | 7         | 0.13%   |
| AMD Athlon              | 7         | 0.13%   |
| AMD A12                 | 7         | 0.13%   |
| Intel Xeon              | 6         | 0.11%   |
| AMD C-60                | 6         | 0.11%   |
| AMD C-50                | 6         | 0.11%   |
| AMD Athlon II           | 6         | 0.11%   |
| Intel Core m7           | 5         | 0.09%   |
| Intel Celeron Dual-Core | 5         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2906      | 54.79%  |
| 4      | 1544      | 29.11%  |
| 6      | 296       | 5.58%   |
| 8      | 240       | 4.52%   |
| 1      | 205       | 3.87%   |
| 10     | 45        | 0.85%   |
| 14     | 39        | 0.74%   |
| 12     | 26        | 0.49%   |
| 16     | 2         | 0.04%   |
| 3      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5298      | 99.98%  |
| 2      | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3567      | 67.25%  |
| 1      | 1736      | 32.73%  |
| 4      | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5101      | 96.23%  |
| 32-bit         | 126       | 2.38%   |
| Unknown        | 72        | 1.36%   |
| 64-bit         | 2         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1186      | 21.86%  |
| 0x1067a    | 468       | 8.63%   |
| 0x306d4    | 266       | 4.9%    |
| 0x306a9    | 246       | 4.53%   |
| 0x206a7    | 230       | 4.24%   |
| 0x806ec    | 208       | 3.83%   |
| 0x806c1    | 206       | 3.8%    |
| 0x806e9    | 149       | 2.75%   |
| 0x806ea    | 143       | 2.64%   |
| 0x40651    | 139       | 2.56%   |
| 0x406e3    | 132       | 2.43%   |
| 0x30678    | 125       | 2.3%    |
| 0x306c3    | 92        | 1.7%    |
| 0x906ea    | 80        | 1.47%   |
| 0x20655    | 78        | 1.44%   |
| 0x406c4    | 74        | 1.36%   |
| 0xa0652    | 73        | 1.35%   |
| 0x6f6      | 68        | 1.25%   |
| 0x0a50000c | 68        | 1.25%   |
| 0x08108109 | 63        | 1.16%   |
| 0x08600106 | 59        | 1.09%   |
| 0x08608103 | 57        | 1.05%   |
| 0x906a3    | 54        | 1%      |
| 0x706e5    | 50        | 0.92%   |
| 0x10676    | 50        | 0.92%   |
| 0x906eb    | 48        | 0.88%   |
| 0x08108102 | 47        | 0.87%   |
| 0x706a8    | 45        | 0.83%   |
| 0x6fd      | 44        | 0.81%   |
| 0x106ca    | 41        | 0.76%   |
| 0x906a4    | 40        | 0.74%   |
| 0x806eb    | 40        | 0.74%   |
| 0x506e3    | 39        | 0.72%   |
| 0x06006705 | 37        | 0.68%   |
| 0x906e9    | 35        | 0.65%   |
| 0x106c2    | 34        | 0.63%   |
| 0x506c9    | 33        | 0.61%   |
| 0x0600611a | 31        | 0.57%   |
| 0x6d8      | 30        | 0.55%   |
| 0x20652    | 28        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 964       | 18.16%  |
| Penryn           | 560       | 10.55%  |
| IvyBridge        | 337       | 6.35%   |
| Haswell          | 315       | 5.94%   |
| SandyBridge      | 313       | 5.9%    |
| Broadwell        | 304       | 5.73%   |
| Silvermont       | 261       | 4.92%   |
| TigerLake        | 259       | 4.88%   |
| Skylake          | 249       | 4.69%   |
| Unknown          | 169       | 3.18%   |
| Core             | 162       | 3.05%   |
| Westmere         | 146       | 2.75%   |
| Zen+             | 138       | 2.6%    |
| Zen 2            | 118       | 2.22%   |
| Zen 3            | 109       | 2.05%   |
| CometLake        | 102       | 1.92%   |
| Excavator        | 94        | 1.77%   |
| Bonnell          | 94        | 1.77%   |
| Icelake          | 83        | 1.56%   |
| Alderlake Hybrid | 78        | 1.47%   |
| Goldmont plus    | 75        | 1.41%   |
| P6               | 74        | 1.39%   |
| Bobcat           | 47        | 0.89%   |
| Goldmont         | 44        | 0.83%   |
| Zen              | 37        | 0.7%    |
| Puma             | 30        | 0.57%   |
| Jaguar           | 23        | 0.43%   |
| K8 Hammer        | 19        | 0.36%   |
| K10 Llano        | 17        | 0.32%   |
| Tremont          | 16        | 0.3%    |
| Piledriver       | 15        | 0.28%   |
| NetBurst         | 14        | 0.26%   |
| Nehalem          | 14        | 0.26%   |
| K10              | 13        | 0.24%   |
| Steamroller      | 7         | 0.13%   |
| K8 & K10 hybrid  | 7         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3849      | 60.2%   |
| Nvidia                           | 1479      | 23.13%  |
| AMD                              | 1049      | 16.41%  |
| Silicon Integrated Systems [SiS] | 8         | 0.13%   |
| Zhaoxin                          | 4         | 0.06%   |
| VIA Technologies                 | 2         | 0.03%   |
| S3 Graphics                      | 2         | 0.03%   |
| Neomagic                         | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 355       | 5.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 312       | 4.68%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 281       | 4.22%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 230       | 3.45%   |
| Intel UHD Graphics 620                                                                   | 211       | 3.17%   |
| Intel HD Graphics 620                                                                    | 180       | 2.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 180       | 2.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 176       | 2.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 157       | 2.36%   |
| Intel HD Graphics 6000                                                                   | 156       | 2.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 149       | 2.24%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 144       | 2.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 144       | 2.16%   |
| Intel HD Graphics 5500                                                                   | 133       | 2%      |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 119       | 1.79%   |
| AMD Renoir                                                                               | 114       | 1.71%   |
| Intel Core Processor Integrated Graphics Controller                                      | 113       | 1.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 112       | 1.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 111       | 1.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 111       | 1.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 105       | 1.58%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 91        | 1.37%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 83        | 1.25%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 80        | 1.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 79        | 1.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 79        | 1.19%   |
| AMD Lucienne                                                                             | 79        | 1.19%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 69        | 1.04%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 56        | 0.84%   |
| Intel HD Graphics 630                                                                    | 51        | 0.77%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 50        | 0.75%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 49        | 0.74%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 49        | 0.74%   |
| Intel HD Graphics 530                                                                    | 48        | 0.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 48        | 0.72%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 45        | 0.68%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 42        | 0.63%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 40        | 0.6%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 39        | 0.59%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 36        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2816      | 53.02%  |
| Intel + Nvidia     | 847       | 15.95%  |
| 1 x AMD            | 733       | 13.8%   |
| 1 x Nvidia         | 543       | 10.22%  |
| Intel + AMD        | 168       | 3.16%   |
| AMD + Nvidia       | 87        | 1.64%   |
| 2 x AMD            | 61        | 1.15%   |
| Other              | 26        | 0.49%   |
| 2 x Intel          | 9         | 0.17%   |
| 1 x SiS            | 8         | 0.15%   |
| 1 x Zhaoxin        | 4         | 0.08%   |
| 2 x Nvidia         | 2         | 0.04%   |
| 1 x VIA            | 2         | 0.04%   |
| 1 x S3 Graphics    | 2         | 0.04%   |
| Intel + 2 x Nvidia | 2         | 0.04%   |
| 1 x Neomagic       | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 4618      | 86.41%  |
| Proprietary | 383       | 7.17%   |
| Unknown     | 343       | 6.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 3885      | 72.39%  |
| 0.01-0.5       | 790       | 14.72%  |
| 1.01-2.0       | 290       | 5.4%    |
| 3.01-4.0       | 164       | 3.06%   |
| 0.51-1.0       | 163       | 3.04%   |
| 5.01-6.0       | 33        | 0.61%   |
| 7.01-8.0       | 29        | 0.54%   |
| 2.01-3.0       | 10        | 0.19%   |
| More than 64.0 | 1         | 0.02%   |
| 8.01-16.0      | 1         | 0.02%   |
| 0              | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1024      | 17.9%   |
| BOE                     | 746       | 13.04%  |
| LG Display              | 693       | 12.12%  |
| Apple                   | 660       | 11.54%  |
| Chimei Innolux          | 651       | 11.38%  |
| Samsung Electronics     | 471       | 8.23%   |
| Dell                    | 150       | 2.62%   |
| Lenovo                  | 140       | 2.45%   |
| Sharp                   | 121       | 2.12%   |
| Goldstar                | 106       | 1.85%   |
| Chi Mei Optoelectronics | 96        | 1.68%   |
| InfoVision              | 81        | 1.42%   |
| Hewlett-Packard         | 70        | 1.22%   |
| PANDA                   | 67        | 1.17%   |
| BenQ                    | 56        | 0.98%   |
| Philips                 | 52        | 0.91%   |
| AOC                     | 43        | 0.75%   |
| LG Philips              | 37        | 0.65%   |
| Iiyama                  | 36        | 0.63%   |
| HannStar                | 36        | 0.63%   |
| Acer                    | 36        | 0.63%   |
| Ancor Communications    | 34        | 0.59%   |
| CSO                     | 33        | 0.58%   |
| Unknown                 | 25        | 0.44%   |
| ViewSonic               | 22        | 0.38%   |
| Sony                    | 19        | 0.33%   |
| CPT                     | 17        | 0.3%    |
| Eizo                    | 14        | 0.24%   |
| ASUSTek Computer        | 12        | 0.21%   |
| Quanta Display          | 10        | 0.17%   |
| Panasonic               | 8         | 0.14%   |
| NEC Computers           | 8         | 0.14%   |
| MSI                     | 7         | 0.12%   |
| LGD                     | 6         | 0.1%    |
| Toshiba                 | 5         | 0.09%   |
| Pixio                   | 5         | 0.09%   |
| InnoLux Display         | 5         | 0.09%   |
| TMX                     | 4         | 0.07%   |
| Fujitsu Siemens         | 4         | 0.07%   |
| AGO                     | 4         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                 | 210       | 3.63%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 191       | 3.3%    |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                 | 54        | 0.93%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 46        | 0.8%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 45        | 0.78%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 45        | 0.78%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 44        | 0.76%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 42        | 0.73%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                 | 38        | 0.66%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                 | 29        | 0.5%    |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 29        | 0.5%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 28        | 0.48%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 28        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 27        | 0.47%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 26        | 0.45%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 25        | 0.43%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 24        | 0.42%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 23        | 0.4%    |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                 | 22        | 0.38%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 21        | 0.36%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 20        | 0.35%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 19        | 0.33%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 18        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 18        | 0.31%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 17        | 0.29%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 17        | 0.29%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 17        | 0.29%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 17        | 0.29%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 16        | 0.28%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 16        | 0.28%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 15        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 14        | 0.24%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 14        | 0.24%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch       | 14        | 0.24%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch        | 14        | 0.24%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 14        | 0.24%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch       | 14        | 0.24%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 14        | 0.24%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 13        | 0.22%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 13        | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2096      | 38.84%  |
| 1366x768 (WXGA)    | 1467      | 27.18%  |
| 1280x800 (WXGA)    | 591       | 10.95%  |
| 1600x900 (HD+)     | 230       | 4.26%   |
| 3840x2160 (4K)     | 157       | 2.91%   |
| 1440x900 (WXGA+)   | 152       | 2.82%   |
| 2560x1440 (QHD)    | 118       | 2.19%   |
| 1920x1200 (WUXGA)  | 117       | 2.17%   |
| 1024x600           | 72        | 1.33%   |
| 2560x1600          | 43        | 0.8%    |
| 1280x1024 (SXGA)   | 43        | 0.8%    |
| 1680x1050 (WSXGA+) | 38        | 0.7%    |
| 3840x2400          | 29        | 0.54%   |
| 2560x1080          | 28        | 0.52%   |
| 2880x1800          | 23        | 0.43%   |
| 1360x768           | 22        | 0.41%   |
| 3440x1440          | 21        | 0.39%   |
| 2288x1287          | 21        | 0.39%   |
| 1024x768 (XGA)     | 20        | 0.37%   |
| 3200x1800 (QHD+)   | 11        | 0.2%    |
| 2160x1440          | 9         | 0.17%   |
| Unknown            | 9         | 0.17%   |
| 1600x1200          | 8         | 0.15%   |
| 3840x1080          | 6         | 0.11%   |
| 1400x1050          | 6         | 0.11%   |
| 1280x720 (HD)      | 5         | 0.09%   |
| 3072x1920          | 4         | 0.07%   |
| 2256x1504          | 4         | 0.07%   |
| 1920x540           | 4         | 0.07%   |
| 3840x1200          | 3         | 0.06%   |
| 3840x1100          | 3         | 0.06%   |
| 3456x2160          | 3         | 0.06%   |
| 2880x1920          | 3         | 0.06%   |
| 2304x1440          | 3         | 0.06%   |
| 2240x1400          | 3         | 0.06%   |
| 1920x1280          | 3         | 0.06%   |
| 1024x576           | 3         | 0.06%   |
| 800x1280           | 2         | 0.04%   |
| 3000x2000          | 2         | 0.04%   |
| 2880x1620          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1789      | 31.27%  |
| 13      | 1259      | 22.01%  |
| 14      | 739       | 12.92%  |
| 17      | 318       | 5.56%   |
| 11      | 303       | 5.3%    |
| 24      | 207       | 3.62%   |
| 12      | 205       | 3.58%   |
| 27      | 149       | 2.6%    |
| 23      | 132       | 2.31%   |
| 21      | 113       | 1.98%   |
| 10      | 73        | 1.28%   |
| 18      | 49        | 0.86%   |
| Unknown | 49        | 0.86%   |
| 16      | 47        | 0.82%   |
| 34      | 43        | 0.75%   |
| 19      | 34        | 0.59%   |
| 31      | 31        | 0.54%   |
| 142     | 21        | 0.37%   |
| 22      | 21        | 0.37%   |
| 25      | 16        | 0.28%   |
| 20      | 15        | 0.26%   |
| 72      | 12        | 0.21%   |
| 40      | 11        | 0.19%   |
| 32      | 11        | 0.19%   |
| 54      | 9         | 0.16%   |
| 84      | 8         | 0.14%   |
| 8       | 8         | 0.14%   |
| 29      | 6         | 0.1%    |
| 28      | 6         | 0.1%    |
| 26      | 6         | 0.1%    |
| 46      | 5         | 0.09%   |
| 48      | 4         | 0.07%   |
| 52      | 3         | 0.05%   |
| 49      | 3         | 0.05%   |
| 43      | 3         | 0.05%   |
| 33      | 2         | 0.03%   |
| 65      | 1         | 0.02%   |
| 58      | 1         | 0.02%   |
| 55      | 1         | 0.02%   |
| 47      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2955      | 52.1%   |
| 201-300        | 1404      | 24.75%  |
| 501-600        | 464       | 8.18%   |
| 351-400        | 374       | 6.59%   |
| 401-500        | 210       | 3.7%    |
| 601-700        | 63        | 1.11%   |
| 701-800        | 55        | 0.97%   |
| Unknown        | 49        | 0.86%   |
| 1001-1500      | 31        | 0.55%   |
| More than 2000 | 21        | 0.37%   |
| 1501-2000      | 20        | 0.35%   |
| 801-900        | 13        | 0.23%   |
| 101-200        | 9         | 0.16%   |
| 901-1000       | 2         | 0.04%   |
| 1-100          | 2         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3879      | 75.87%  |
| 16/10   | 1000      | 19.56%  |
| 21/9    | 46        | 0.9%    |
| 5/4     | 42        | 0.82%   |
| 4/3     | 40        | 0.78%   |
| 3/2     | 35        | 0.68%   |
| Unknown | 31        | 0.61%   |
| 1.00    | 21        | 0.41%   |
| 32/9    | 4         | 0.08%   |
| 2.65    | 4         | 0.08%   |
| 3.40    | 3         | 0.06%   |
| 3.20    | 3         | 0.06%   |
| 6/5     | 1         | 0.02%   |
| 3.73    | 1         | 0.02%   |
| 1.96    | 1         | 0.02%   |
| 0.67    | 1         | 0.02%   |
| 0.58    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1782      | 31.24%  |
| 81-90          | 1668      | 29.24%  |
| 201-250        | 366       | 6.42%   |
| 71-80          | 321       | 5.63%   |
| 51-60          | 306       | 5.36%   |
| 121-130        | 253       | 4.44%   |
| 61-70          | 199       | 3.49%   |
| 301-350        | 153       | 2.68%   |
| 351-500        | 94        | 1.65%   |
| 251-300        | 86        | 1.51%   |
| 151-200        | 81        | 1.42%   |
| 41-50          | 73        | 1.28%   |
| 141-150        | 68        | 1.19%   |
| More than 1000 | 59        | 1.03%   |
| Unknown        | 49        | 0.86%   |
| 111-120        | 44        | 0.77%   |
| 131-140        | 41        | 0.72%   |
| 501-1000       | 27        | 0.47%   |
| 91-100         | 23        | 0.4%    |
| 1-40           | 11        | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2359      | 42.13%  |
| 101-120       | 1842      | 32.9%   |
| 51-100        | 801       | 14.31%  |
| 161-240       | 362       | 6.47%   |
| More than 240 | 119       | 2.13%   |
| 1-50          | 67        | 1.2%    |
| Unknown       | 49        | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 4208      | 77.67%  |
| 2     | 789       | 14.56%  |
| 0     | 335       | 6.18%   |
| 3     | 84        | 1.55%   |
| 5     | 1         | 0.02%   |
| 4     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2676      | 31.38%  |
| Realtek Semiconductor             | 2363      | 27.71%  |
| Qualcomm Atheros                  | 1085      | 12.72%  |
| Broadcom                          | 782       | 9.17%   |
| Nvidia                            | 376       | 4.41%   |
| Broadcom Limited                  | 271       | 3.18%   |
| Marvell Technology Group          | 153       | 1.79%   |
| MediaTek                          | 105       | 1.23%   |
| ASIX Electronics                  | 67        | 0.79%   |
| Ralink                            | 64        | 0.75%   |
| TP-Link                           | 46        | 0.54%   |
| Dell                              | 42        | 0.49%   |
| Sierra Wireless                   | 40        | 0.47%   |
| Samsung Electronics               | 36        | 0.42%   |
| Lenovo                            | 34        | 0.4%    |
| Ralink Technology                 | 32        | 0.38%   |
| Qualcomm                          | 31        | 0.36%   |
| JMicron Technology                | 31        | 0.36%   |
| Xiaomi                            | 28        | 0.33%   |
| Ericsson Business Mobile Networks | 27        | 0.32%   |
| DisplayLink                       | 20        | 0.23%   |
| Huawei Technologies               | 18        | 0.21%   |
| Hewlett-Packard                   | 18        | 0.21%   |
| Fibocom                           | 14        | 0.16%   |
| Silicon Integrated Systems [SiS]  | 12        | 0.14%   |
| Qualcomm Atheros Communications   | 9         | 0.11%   |
| OPPO Electronics                  | 9         | 0.11%   |
| NetGear                           | 9         | 0.11%   |
| Cypress Semiconductor             | 8         | 0.09%   |
| Attansic Technology               | 7         | 0.08%   |
| ASUSTek Computer                  | 7         | 0.08%   |
| ICS Advent                        | 6         | 0.07%   |
| Apple                             | 6         | 0.07%   |
| U-Blox                            | 5         | 0.06%   |
| Motorola PCS                      | 5         | 0.06%   |
| Microchip Technology              | 5         | 0.06%   |
| Edimax Technology                 | 5         | 0.06%   |
| D-Link                            | 5         | 0.06%   |
| AMD                               | 5         | 0.06%   |
| Spreadtrum Communications         | 4         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 1428      | 14%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 404       | 3.96%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 368       | 3.61%   |
| Nvidia MCP79 Ethernet                                                                 | 365       | 3.58%   |
| Intel Wireless 8265 / 8275                                                            | 228       | 2.24%   |
| Intel Wireless 7260                                                                   | 228       | 2.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 226       | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 225       | 2.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 204       | 2%      |
| Intel Wi-Fi 6 AX200                                                                   | 189       | 1.85%   |
| Intel Wireless 7265                                                                   | 188       | 1.84%   |
| Intel Wi-Fi 6 AX201                                                                   | 182       | 1.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 164       | 1.61%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 163       | 1.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 143       | 1.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 131       | 1.28%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 130       | 1.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 128       | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 124       | 1.22%   |
| Intel Wireless 8260                                                                   | 123       | 1.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 117       | 1.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 112       | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 100       | 0.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 93        | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 91        | 0.89%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 86        | 0.84%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 80        | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 78        | 0.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 77        | 0.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 75        | 0.74%   |
| Intel Ethernet Connection I219-LM                                                     | 69        | 0.68%   |
| Intel Wireless 3165                                                                   | 66        | 0.65%   |
| Intel Ethernet Connection I218-LM                                                     | 66        | 0.65%   |
| Intel Ethernet Connection (4) I219-V                                                  | 65        | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 62        | 0.61%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 60        | 0.59%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 59        | 0.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 56        | 0.55%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 56        | 0.55%   |
| ASIX AX88179 Gigabit Ethernet                                                         | 56        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2527      | 46.52%  |
| Qualcomm Atheros                      | 967       | 17.8%   |
| Realtek Semiconductor                 | 673       | 12.39%  |
| Broadcom                              | 661       | 12.17%  |
| Broadcom Limited                      | 224       | 4.12%   |
| MediaTek                              | 98        | 1.8%    |
| Ralink                                | 64        | 1.18%   |
| Sierra Wireless                       | 40        | 0.74%   |
| Ralink Technology                     | 32        | 0.59%   |
| TP-Link                               | 27        | 0.5%    |
| Dell                                  | 27        | 0.5%    |
| Qualcomm                              | 17        | 0.31%   |
| Fibocom                               | 14        | 0.26%   |
| Qualcomm Atheros Communications       | 9         | 0.17%   |
| NetGear                               | 9         | 0.17%   |
| ASUSTek Computer                      | 7         | 0.13%   |
| Ericsson Business Mobile Networks     | 5         | 0.09%   |
| Edimax Technology                     | 5         | 0.09%   |
| Hewlett-Packard                       | 4         | 0.07%   |
| D-Link                                | 3         | 0.06%   |
| Wilocity                              | 2         | 0.04%   |
| Quectel Wireless Solutions            | 2         | 0.04%   |
| Microsoft                             | 2         | 0.04%   |
| D-Link System                         | 2         | 0.04%   |
| Belkin Components                     | 2         | 0.04%   |
| 3Com                                  | 2         | 0.04%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| Z-Com                                 | 1         | 0.02%   |
| Winbond Electronics                   | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| Marvell Technology Group              | 1         | 0.02%   |
| Cinterion                             | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 368       | 6.73%   |
| Intel Wireless 8265 / 8275                                                            | 228       | 4.17%   |
| Intel Wireless 7260                                                                   | 228       | 4.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 225       | 4.12%   |
| Intel Wi-Fi 6 AX200                                                                   | 189       | 3.46%   |
| Intel Wireless 7265                                                                   | 188       | 3.44%   |
| Intel Wi-Fi 6 AX201                                                                   | 182       | 3.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 164       | 3%      |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 163       | 2.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 143       | 2.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 131       | 2.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 130       | 2.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 128       | 2.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 124       | 2.27%   |
| Intel Wireless 8260                                                                   | 123       | 2.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 117       | 2.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 112       | 2.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 100       | 1.83%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 93        | 1.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 91        | 1.67%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 80        | 1.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 78        | 1.43%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 77        | 1.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 75        | 1.37%   |
| Intel Wireless 3165                                                                   | 66        | 1.21%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 60        | 1.1%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 56        | 1.02%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 56        | 1.02%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 50        | 0.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 50        | 0.92%   |
| Intel Wireless-AC 9260                                                                | 49        | 0.9%    |
| Broadcom BCM43142 802.11b/g/n                                                         | 47        | 0.86%   |
| Intel Centrino Ultimate-N 6300                                                        | 46        | 0.84%   |
| Intel Wireless 3160                                                                   | 43        | 0.79%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 39        | 0.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 38        | 0.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 36        | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 35        | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 35        | 0.64%   |
| Intel Centrino Advanced-N 6200                                                        | 35        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2114      | 46.66%  |
| Intel                            | 1095      | 24.17%  |
| Nvidia                           | 376       | 8.3%    |
| Qualcomm Atheros                 | 243       | 5.36%   |
| Broadcom                         | 162       | 3.58%   |
| Marvell Technology Group         | 152       | 3.35%   |
| ASIX Electronics                 | 67        | 1.48%   |
| Broadcom Limited                 | 50        | 1.1%    |
| Lenovo                           | 34        | 0.75%   |
| JMicron Technology               | 31        | 0.68%   |
| Xiaomi                           | 28        | 0.62%   |
| DisplayLink                      | 20        | 0.44%   |
| TP-Link                          | 19        | 0.42%   |
| Samsung Electronics              | 17        | 0.38%   |
| Qualcomm                         | 13        | 0.29%   |
| Silicon Integrated Systems [SiS] | 12        | 0.26%   |
| Huawei Technologies              | 12        | 0.26%   |
| OPPO Electronics                 | 9         | 0.2%    |
| Cypress Semiconductor            | 8         | 0.18%   |
| MediaTek                         | 7         | 0.15%   |
| Attansic Technology              | 7         | 0.15%   |
| ICS Advent                       | 6         | 0.13%   |
| Hewlett-Packard                  | 6         | 0.13%   |
| Apple                            | 6         | 0.13%   |
| Microchip Technology             | 5         | 0.11%   |
| Spreadtrum Communications        | 4         | 0.09%   |
| Motorola PCS                     | 4         | 0.09%   |
| Google                           | 3         | 0.07%   |
| VIA Technologies                 | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.04%   |
| National Semiconductor           | 2         | 0.04%   |
| LG Electronics                   | 2         | 0.04%   |
| D-Link                           | 2         | 0.04%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.02%   |
| ULi Electronics                  | 1         | 0.02%   |
| MosChip Semiconductor            | 1         | 0.02%   |
| Linksys                          | 1         | 0.02%   |
| LeEco                            | 1         | 0.02%   |
| HTC (High Tech Computer)         | 1         | 0.02%   |
| Foxconn / Hon Hai                | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1428      | 31.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 404       | 8.81%   |
| Nvidia MCP79 Ethernet                                             | 365       | 7.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 226       | 4.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 204       | 4.45%   |
| Intel Ethernet Connection (4) I219-LM                             | 86        | 1.88%   |
| Intel Ethernet Connection I219-LM                                 | 69        | 1.51%   |
| Intel Ethernet Connection I218-LM                                 | 66        | 1.44%   |
| Intel Ethernet Connection (4) I219-V                              | 65        | 1.42%   |
| Intel Ethernet Connection (3) I218-LM                             | 62        | 1.35%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 59        | 1.29%   |
| ASIX AX88179 Gigabit Ethernet                                     | 56        | 1.22%   |
| Intel 82577LM Gigabit Network Connection                          | 49        | 1.07%   |
| Intel 82567LM Gigabit Network Connection                          | 42        | 0.92%   |
| Intel Ethernet Connection (6) I219-V                              | 41        | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 39        | 0.85%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 39        | 0.85%   |
| Intel Ethernet Connection I217-LM                                 | 37        | 0.81%   |
| Intel Ethernet Connection I219-V                                  | 35        | 0.76%   |
| Intel Ethernet Connection (13) I219-V                             | 35        | 0.76%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 33        | 0.72%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 31        | 0.68%   |
| Intel Ethernet Connection (10) I219-V                             | 27        | 0.59%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 26        | 0.57%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 25        | 0.55%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 24        | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 22        | 0.48%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 21        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 21        | 0.46%   |
| Intel Ethernet Connection (6) I219-LM                             | 21        | 0.46%   |
| Intel 82579V Gigabit Network Connection                           | 21        | 0.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 20        | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 20        | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 20        | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 17        | 0.37%   |
| Intel Ethernet Connection (16) I219-V                             | 17        | 0.37%   |
| Intel Ethernet Connection (13) I219-LM                            | 17        | 0.37%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 16        | 0.35%   |
| Intel Ethernet Connection (7) I219-LM                             | 16        | 0.35%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 15        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5194      | 53.73%  |
| Ethernet | 4319      | 44.68%  |
| Modem    | 145       | 1.5%    |
| Unknown  | 8         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3992      | 71.32%  |
| Ethernet | 1605      | 28.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3896      | 73.4%   |
| 1     | 1280      | 24.11%  |
| 0     | 81        | 1.53%   |
| 3     | 49        | 0.92%   |
| 5     | 1         | 0.02%   |
| 4     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4413      | 82.1%   |
| Yes  | 962       | 17.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1923      | 44.72%  |
| Apple                           | 645       | 15%     |
| Realtek Semiconductor           | 392       | 9.12%   |
| Qualcomm Atheros Communications | 367       | 8.53%   |
| Broadcom                        | 205       | 4.77%   |
| Lite-On Technology              | 163       | 3.79%   |
| IMC Networks                    | 163       | 3.79%   |
| Foxconn / Hon Hai               | 116       | 2.7%    |
| Dell                            | 68        | 1.58%   |
| Hewlett-Packard                 | 50        | 1.16%   |
| Cambridge Silicon Radio         | 48        | 1.12%   |
| Toshiba                         | 30        | 0.7%    |
| ASUSTek Computer                | 30        | 0.7%    |
| Realtek                         | 28        | 0.65%   |
| Ralink                          | 19        | 0.44%   |
| Foxconn International           | 10        | 0.23%   |
| Ralink Technology               | 8         | 0.19%   |
| Alps Electric                   | 6         | 0.14%   |
| MediaTek                        | 5         | 0.12%   |
| Fujitsu                         | 4         | 0.09%   |
| Taiyo Yuden                     | 3         | 0.07%   |
| USI                             | 2         | 0.05%   |
| Micro Star International        | 2         | 0.05%   |
| Chicony Electronics             | 2         | 0.05%   |
| Askey Computer                  | 2         | 0.05%   |
| Unknown                         | 1         | 0.02%   |
| Smart Modular Technologies      | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Opticis                         | 1         | 0.02%   |
| Marvell Semiconductor           | 1         | 0.02%   |
| Edimax Technology               | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |
| Belkin Components               | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 825       | 19.16%  |
| Intel AX201 Bluetooth                               | 362       | 8.41%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 352       | 8.18%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 301       | 6.99%   |
| Realtek Bluetooth Radio                             | 258       | 5.99%   |
| Qualcomm Atheros  Bluetooth Device                  | 212       | 4.92%   |
| Intel AX200 Bluetooth                               | 180       | 4.18%   |
| Apple Bluetooth USB Host Controller                 | 165       | 3.83%   |
| Realtek  Bluetooth 4.2 Adapter                      | 86        | 2%      |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 1.77%   |
| Intel Bluetooth Device                              | 68        | 1.58%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 57        | 1.32%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 51        | 1.18%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 48        | 1.11%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 47        | 1.09%   |
| IMC Networks Bluetooth Radio                        | 46        | 1.07%   |
| Foxconn / Hon Hai Bluetooth Device                  | 46        | 1.07%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 44        | 1.02%   |
| Apple Bluetooth Host Controller                     | 44        | 1.02%   |
| Broadcom BCM2045B (BDC-2.1)                         | 42        | 0.98%   |
| Lite-On Bluetooth Device                            | 40        | 0.93%   |
| IMC Networks Bluetooth Device                       | 40        | 0.93%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 39        | 0.91%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 37        | 0.86%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 34        | 0.79%   |
| Intel Wireless-AC 3168 Bluetooth                    | 34        | 0.79%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 34        | 0.79%   |
| IMC Networks Wireless_Device                        | 34        | 0.79%   |
| Intel AX210 Bluetooth                               | 28        | 0.65%   |
| Realtek 802.11ac WLAN Adapter                       | 24        | 0.56%   |
| Lite-On Atheros AR3012 Bluetooth                    | 24        | 0.56%   |
| Lite-On Wireless_Device                             | 22        | 0.51%   |
| Realtek RTL8723B Bluetooth                          | 21        | 0.49%   |
| HP Broadcom 2070 Bluetooth Combo                    | 21        | 0.49%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 21        | 0.49%   |
| Dell DW375 Bluetooth Module                         | 21        | 0.49%   |
| Dell BCM20702A0 Bluetooth Module                    | 21        | 0.49%   |
| Ralink RT3290 Bluetooth                             | 19        | 0.44%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 19        | 0.44%   |
| Broadcom HP Portable SoftSailing                    | 15        | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4054      | 65.65%  |
| Nvidia                                       | 895       | 14.49%  |
| AMD                                          | 851       | 13.78%  |
| C-Media Electronics                          | 44        | 0.71%   |
| Realtek Semiconductor                        | 33        | 0.53%   |
| Logitech                                     | 32        | 0.52%   |
| Lenovo                                       | 32        | 0.52%   |
| Texas Instruments                            | 19        | 0.31%   |
| Plantronics                                  | 19        | 0.31%   |
| GN Netcom                                    | 17        | 0.28%   |
| Hewlett-Packard                              | 14        | 0.23%   |
| Silicon Integrated Systems [SiS]             | 13        | 0.21%   |
| Generalplus Technology                       | 11        | 0.18%   |
| ASUSTek Computer                             | 9         | 0.15%   |
| JMTek                                        | 8         | 0.13%   |
| Creative Technology                          | 8         | 0.13%   |
| Zoran Co. Personal Media Division (Nogatech) | 6         | 0.1%    |
| Focusrite-Novation                           | 6         | 0.1%    |
| Kingston Technology                          | 5         | 0.08%   |
| Zhaoxin                                      | 4         | 0.06%   |
| RODE Microphones                             | 4         | 0.06%   |
| Razer USA                                    | 4         | 0.06%   |
| Dell                                         | 4         | 0.06%   |
| CMX Systems                                  | 4         | 0.06%   |
| VIA Technologies                             | 3         | 0.05%   |
| ULi Electronics                              | 3         | 0.05%   |
| Sennheiser Communications                    | 3         | 0.05%   |
| Microsoft                                    | 3         | 0.05%   |
| BEHRINGER International                      | 3         | 0.05%   |
| Apple                                        | 3         | 0.05%   |
| Yamaha                                       | 2         | 0.03%   |
| XMOS                                         | 2         | 0.03%   |
| SteelSeries ApS                              | 2         | 0.03%   |
| Sony                                         | 2         | 0.03%   |
| SAVITECH                                     | 2         | 0.03%   |
| M-Audio                                      | 2         | 0.03%   |
| Fujitsu                                      | 2         | 0.03%   |
| ESS Technology                               | 2         | 0.03%   |
| Conexant Systems                             | 2         | 0.03%   |
| Blue Microphones                             | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 616       | 8.24%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 483       | 6.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 399       | 5.34%   |
| Nvidia MCP79 High Definition Audio                                                                | 367       | 4.91%   |
| Intel Broadwell-U Audio Controller                                                                | 304       | 4.07%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 300       | 4.01%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 257       | 3.44%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 257       | 3.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 250       | 3.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 186       | 2.49%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 185       | 2.48%   |
| Intel 8 Series HD Audio Controller                                                                | 185       | 2.48%   |
| Intel Cannon Lake PCH cAVS                                                                        | 172       | 2.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 171       | 2.29%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 162       | 2.17%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 158       | 2.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 158       | 2.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 153       | 2.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 129       | 1.73%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 123       | 1.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 113       | 1.51%   |
| AMD FCH Azalia Controller                                                                         | 110       | 1.47%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 105       | 1.41%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 102       | 1.36%   |
| AMD Kabini HDMI/DP Audio                                                                          | 98        | 1.31%   |
| Intel Comet Lake PCH cAVS                                                                         | 91        | 1.22%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 90        | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 86        | 1.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 75        | 1%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 73        | 0.98%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 62        | 0.83%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 58        | 0.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 57        | 0.76%   |
| Intel CM238 HD Audio Controller                                                                   | 57        | 0.76%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 53        | 0.71%   |
| AMD High Definition Audio Controller                                                              | 49        | 0.66%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 45        | 0.6%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 44        | 0.59%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 42        | 0.56%   |
| AMD Wrestler HDMI Audio                                                                           | 38        | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 1397      | 27.52%  |
| Samsung Electronics | 1351      | 26.62%  |
| Micron Technology   | 589       | 11.6%   |
| Kingston            | 358       | 7.05%   |
| Unknown             | 342       | 6.74%   |
| Crucial             | 247       | 4.87%   |
| Elpida              | 145       | 2.86%   |
| A-DATA Technology   | 105       | 2.07%   |
| Ramaxel Technology  | 97        | 1.91%   |
| Corsair             | 53        | 1.04%   |
| Nanya Technology    | 52        | 1.02%   |
| Smart               | 40        | 0.79%   |
| Unknown (ABCD)      | 39        | 0.77%   |
| GOODRAM             | 26        | 0.51%   |
| G.Skill             | 22        | 0.43%   |
| Transcend           | 21        | 0.41%   |
| Unknown             | 20        | 0.39%   |
| Team                | 17        | 0.33%   |
| Teikon              | 10        | 0.2%    |
| Silicon Power       | 9         | 0.18%   |
| ASint Technology    | 9         | 0.18%   |
| Apacer              | 9         | 0.18%   |
| Patriot             | 8         | 0.16%   |
| 48spaces            | 8         | 0.16%   |
| Smart Brazil        | 6         | 0.12%   |
| Timetec             | 5         | 0.1%    |
| ff                  | 5         | 0.1%    |
| AMD                 | 5         | 0.1%    |
| 4ea5                | 5         | 0.1%    |
| Qimonda             | 4         | 0.08%   |
| PNY                 | 4         | 0.08%   |
| Neo Forza           | 4         | 0.08%   |
| Wilk                | 3         | 0.06%   |
| Kllisre             | 3         | 0.06%   |
| Infineon            | 3         | 0.06%   |
| Goldkey             | 3         | 0.06%   |
| fef5                | 3         | 0.06%   |
| CSX                 | 3         | 0.06%   |
| Avant               | 3         | 0.06%   |
| Unknown (89F7)      | 2         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 265       | 4.95%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 1.27%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 68        | 1.27%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 63        | 1.18%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 51        | 0.95%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 50        | 0.93%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 48        | 0.9%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 45        | 0.84%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 44        | 0.82%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 44        | 0.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 44        | 0.82%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 42        | 0.78%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 42        | 0.78%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 41        | 0.77%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 41        | 0.77%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 40        | 0.75%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 37        | 0.69%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 36        | 0.67%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 36        | 0.67%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 35        | 0.65%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 31        | 0.58%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 31        | 0.58%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 31        | 0.58%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 30        | 0.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 29        | 0.54%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.54%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 27        | 0.5%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 26        | 0.49%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 26        | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 25        | 0.47%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 25        | 0.47%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 25        | 0.47%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.47%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 24        | 0.45%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 24        | 0.45%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 24        | 0.45%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 23        | 0.43%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 21        | 0.39%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 21        | 0.39%   |
| Micron RAM EDF8132A3MA-GD-F 2GB LPDDR3 1600MT/s                  | 21        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1753      | 39.93%  |
| DDR3    | 1467      | 33.42%  |
| DDR2    | 615       | 14.01%  |
| LPDDR4  | 165       | 3.76%   |
| LPDDR3  | 153       | 3.49%   |
| SDRAM   | 90        | 2.05%   |
| DDR     | 46        | 1.05%   |
| DDR5    | 32        | 0.73%   |
| Unknown | 30        | 0.68%   |
| LPDDR5  | 27        | 0.62%   |
| DRAM    | 11        | 0.25%   |
| RAM     | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 3983      | 90.46%  |
| Row Of Chips | 305       | 6.93%   |
| Unknown      | 67        | 1.52%   |
| Chip         | 33        | 0.75%   |
| DIMM         | 15        | 0.34%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1561      | 32.66%  |
| 4096  | 1229      | 25.71%  |
| 2048  | 717       | 15%     |
| 1024  | 575       | 12.03%  |
| 16384 | 527       | 11.03%  |
| 32768 | 104       | 2.18%   |
| 512   | 46        | 0.96%   |
| 256   | 17        | 0.36%   |
| 128   | 2         | 0.04%   |
| 8072  | 1         | 0.02%   |
| 384   | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 1103      | 23.52%  |
| 2667    | 793       | 16.91%  |
| 3200    | 725       | 15.46%  |
| 800     | 395       | 8.42%   |
| 2400    | 294       | 6.27%   |
| 2133    | 211       | 4.5%    |
| 1334    | 195       | 4.16%   |
| 667     | 190       | 4.05%   |
| 1333    | 145       | 3.09%   |
| Unknown | 114       | 2.43%   |
| 1067    | 70        | 1.49%   |
| 4267    | 63        | 1.34%   |
| 1867    | 55        | 1.17%   |
| 3266    | 44        | 0.94%   |
| 4800    | 34        | 0.73%   |
| 4199    | 33        | 0.7%    |
| 1066    | 32        | 0.68%   |
| 6400    | 27        | 0.58%   |
| 533     | 23        | 0.49%   |
| 975     | 22        | 0.47%   |
| 2048    | 21        | 0.45%   |
| 8400    | 17        | 0.36%   |
| 4266    | 14        | 0.3%    |
| 400     | 11        | 0.23%   |
| 3733    | 9         | 0.19%   |
| 333     | 9         | 0.19%   |
| 1866    | 8         | 0.17%   |
| 266     | 8         | 0.17%   |
| 2666    | 4         | 0.09%   |
| 933     | 4         | 0.09%   |
| 2933    | 3         | 0.06%   |
| 5600    | 2         | 0.04%   |
| 1776    | 2         | 0.04%   |
| 1639    | 2         | 0.04%   |
| 3000    | 1         | 0.02%   |
| 2134    | 1         | 0.02%   |
| 1596    | 1         | 0.02%   |
| 200     | 1         | 0.02%   |
| 166     | 1         | 0.02%   |
| 133     | 1         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 12        | 36.36%  |
| Canon               | 5         | 15.15%  |
| Xerox               | 4         | 12.12%  |
| Brother Industries  | 4         | 12.12%  |
| Samsung Electronics | 2         | 6.06%   |
| Kyocera             | 2         | 6.06%   |
| Xiaomi              | 1         | 3.03%   |
| STMicroelectronics  | 1         | 3.03%   |
| Seiko Epson         | 1         | 3.03%   |
| Pantum              | 1         | 3.03%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Xerox B205                                                | 4         | 11.76%  |
| Xiaomi MiMouse 2                                          | 1         | 2.94%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 2.94%   |
| Seiko Epson L120 Series                                   | 1         | 2.94%   |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 2.94%   |
| Samsung CLX-3300 Series                                   | 1         | 2.94%   |
| Pantum P2500W series                                      | 1         | 2.94%   |
| Kyocera FS-1120MFP                                        | 1         | 2.94%   |
| Kyocera ECOSYS P2335d                                     | 1         | 2.94%   |
| HP OfficeJet 3830 series                                  | 1         | 2.94%   |
| HP LaserJet P1102                                         | 1         | 2.94%   |
| HP LaserJet P1005                                         | 1         | 2.94%   |
| HP LaserJet 1200                                          | 1         | 2.94%   |
| HP LaserJet 1160 series                                   | 1         | 2.94%   |
| HP LaserJet 1150                                          | 1         | 2.94%   |
| HP LaserJet 1022                                          | 1         | 2.94%   |
| HP LaserJet 1020                                          | 1         | 2.94%   |
| HP Ink Tank 110 series                                    | 1         | 2.94%   |
| HP EWS UPD                                                | 1         | 2.94%   |
| HP DeskJet 2620 All-in-One Printer                        | 1         | 2.94%   |
| HP Deskjet 2540 series                                    | 1         | 2.94%   |
| HP DeskJet 2130 series                                    | 1         | 2.94%   |
| Canon PIXMA MX920 Series                                  | 1         | 2.94%   |
| Canon LBP3010/LBP3018/LBP3050                             | 1         | 2.94%   |
| Canon LBP2900                                             | 1         | 2.94%   |
| Canon G3010 series                                        | 1         | 2.94%   |
| Canon CanoScan LiDE 300                                   | 1         | 2.94%   |
| Brother PT-9500PC                                         | 1         | 2.94%   |
| Brother MFC-L2707DW                                       | 1         | 2.94%   |
| Brother HL-L2340D series                                  | 1         | 2.94%   |
| Brother DCP-7010                                          | 1         | 2.94%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 42.86%  |
| Seiko Epson     | 5         | 35.71%  |
| Mustek Systems  | 2         | 14.29%  |
| Hewlett-Packard | 1         | 7.14%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 120                           | 2         | 14.29%  |
| Canon CanoScan LiDE 110                           | 2         | 14.29%  |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]       | 1         | 7.14%   |
| Seiko Epson GT-9800F [Perfection 3200]            | 1         | 7.14%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]     | 1         | 7.14%   |
| Seiko Epson GT-7700U [Perfection 1240U]           | 1         | 7.14%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 7.14%   |
| Mustek Systems SNAPSCAN e22                       | 1         | 7.14%   |
| Mustek Systems BearPaw 2400 CU Plus               | 1         | 7.14%   |
| HP Scanjet 200                                    | 1         | 7.14%   |
| Canon CanoScan LIDE 25                            | 1         | 7.14%   |
| Canon CanoScan LiDE 220                           | 1         | 7.14%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1011      | 24.26%  |
| IMC Networks                           | 461       | 11.06%  |
| Microdia                               | 343       | 8.23%   |
| Realtek Semiconductor                  | 334       | 8.01%   |
| Quanta                                 | 306       | 7.34%   |
| Bison Electronics                      | 268       | 6.43%   |
| Sunplus Innovation Technology          | 230       | 5.52%   |
| Acer                                   | 140       | 3.36%   |
| Cheng Uei Precision Industry (Foxlink) | 131       | 3.14%   |
| Suyin                                  | 130       | 3.12%   |
| Lite-On Technology                     | 107       | 2.57%   |
| Syntek                                 | 93        | 2.23%   |
| Luxvisions Innotech Limited            | 89        | 2.14%   |
| Apple                                  | 75        | 1.8%    |
| Silicon Motion                         | 60        | 1.44%   |
| Logitech                               | 54        | 1.3%    |
| Alcor Micro                            | 43        | 1.03%   |
| Lenovo                                 | 38        | 0.91%   |
| Ricoh                                  | 33        | 0.79%   |
| Z-Star Microelectronics                | 20        | 0.48%   |
| Sonix Technology                       | 19        | 0.46%   |
| Primax Electronics                     | 19        | 0.46%   |
| Samsung Electronics                    | 14        | 0.34%   |
| ALi                                    | 13        | 0.31%   |
| Importek                               | 11        | 0.26%   |
| icSpring                               | 11        | 0.26%   |
| SunplusIT                              | 9         | 0.22%   |
| OmniVision Technologies                | 8         | 0.19%   |
| Genesys Logic                          | 8         | 0.19%   |
| Microsoft                              | 6         | 0.14%   |
| MacroSilicon                           | 5         | 0.12%   |
| Intel                                  | 5         | 0.12%   |
| GEMBIRD                                | 5         | 0.12%   |
| Y Media                                | 4         | 0.1%    |
| Generalplus Technology                 | 4         | 0.1%    |
| Sunplus Technology                     | 3         | 0.07%   |
| Pixart Imaging                         | 3         | 0.07%   |
| ARC International                      | 3         | 0.07%   |
| Tobii Technology AB                    | 2         | 0.05%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 273       | 6.5%    |
| Microdia Integrated_Webcam_HD                       | 166       | 3.95%   |
| IMC Networks Integrated Camera                      | 151       | 3.6%    |
| Realtek Integrated_Webcam_HD                        | 126       | 3%      |
| IMC Networks USB2.0 HD UVC WebCam                   | 106       | 2.53%   |
| Chicony HD Webcam                                   | 89        | 2.12%   |
| Sunplus Integrated_Webcam_HD                        | 82        | 1.95%   |
| Quanta Chromebook HD Camera                         | 71        | 1.69%   |
| Bison BisonCam, NB Pro                              | 61        | 1.45%   |
| Chicony HP HD Camera                                | 60        | 1.43%   |
| Acer Integrated Camera                              | 57        | 1.36%   |
| Bison Integrated Camera                             | 55        | 1.31%   |
| Syntek Integrated Camera                            | 52        | 1.24%   |
| Quanta HP TrueVision HD Camera                      | 45        | 1.07%   |
| Chicony USB2.0 HD UVC WebCam                        | 45        | 1.07%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 44        | 1.05%   |
| Lite-On Integrated Camera                           | 42        | 1%      |
| Quanta HD User Facing                               | 40        | 0.95%   |
| Microdia Integrated Webcam                          | 37        | 0.88%   |
| Bison SunplusIT Integrated Camera                   | 35        | 0.83%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 33        | 0.79%   |
| Chicony HD User Facing                              | 32        | 0.76%   |
| Sunplus HD WebCam                                   | 31        | 0.74%   |
| Quanta HP HD Camera                                 | 30        | 0.71%   |
| Chicony Integrated Camera (1280x720@30)             | 30        | 0.71%   |
| Lite-On HP HD Camera                                | 29        | 0.69%   |
| Realtek USB Camera                                  | 28        | 0.67%   |
| Chicony HP TrueVision HD Camera                     | 28        | 0.67%   |
| Quanta VGA WebCam                                   | 27        | 0.64%   |
| Realtek Integrated Webcam                           | 25        | 0.6%    |
| Chicony USB2.0 Camera                               | 25        | 0.6%    |
| Bison Lenovo EasyCamera                             | 25        | 0.6%    |
| Chicony EasyCamera                                  | 23        | 0.55%   |
| Chicony USB 2.0 Camera                              | 22        | 0.52%   |
| Chicony HP Truevision HD                            | 22        | 0.52%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 22        | 0.52%   |
| Apple Built-in iSight                               | 22        | 0.52%   |
| Acer BisonCam,NB Pro                                | 22        | 0.52%   |
| Chicony Lenovo EasyCamera                           | 21        | 0.5%    |
| Bison Lenovo Integrated Webcam                      | 21        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 291       | 33.07%  |
| Synaptics                          | 272       | 30.91%  |
| Shenzhen Goodix Technology         | 116       | 13.18%  |
| AuthenTec                          | 53        | 6.02%   |
| Upek                               | 52        | 5.91%   |
| Elan Microelectronics              | 44        | 5%      |
| LighTuning Technology              | 26        | 2.95%   |
| STMicroelectronics                 | 18        | 2.05%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 0.45%   |
| Focal-systems.Corp                 | 2         | 0.23%   |
| Samsung Electronics                | 1         | 0.11%   |
| Microsoft                          | 1         | 0.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 120       | 13.64%  |
| Shenzhen Goodix  Fingerprint Device                                        | 73        | 8.3%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 59        | 6.7%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 59        | 6.7%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 55        | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 46        | 5.23%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 39        | 4.43%   |
| Elan ELAN:Fingerprint                                                      | 25        | 2.84%   |
| Validity Sensors Synaptics WBDI                                            | 24        | 2.73%   |
| Shenzhen Goodix Fingerprint Reader                                         | 24        | 2.73%   |
| AuthenTec AES2810                                                          | 22        | 2.5%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 21        | 2.39%   |
| Shenzhen Goodix FingerPrint                                                | 19        | 2.16%   |
| Elan ELAN:ARM-M4                                                           | 19        | 2.16%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 18        | 2.05%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 17        | 1.93%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 17        | 1.93%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 16        | 1.82%   |
| Synaptics Fingerprint reader [HP G6]                                       | 16        | 1.82%   |
| STMicroelectronics Fingerprint Reader                                      | 16        | 1.82%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 1.59%   |
| Validity Sensors VFS491                                                    | 13        | 1.48%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 10        | 1.14%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 1.14%   |
| Validity Sensors VFS Fingerprint sensor                                    | 10        | 1.14%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 10        | 1.14%   |
| Validity Sensors Fingerprint scanner                                       | 10        | 1.14%   |
| Synaptics UWP WBDI Device                                                  | 9         | 1.02%   |
| Synaptics  WBDI                                                            | 9         | 1.02%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 8         | 0.91%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 7         | 0.8%    |
| Upek TCS5B Fingerprint sensor                                              | 6         | 0.68%   |
| Synaptics WBDI                                                             | 6         | 0.68%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 0.68%   |
| Synaptics UWP WBDI                                                         | 5         | 0.57%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 0.57%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 5         | 0.57%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 0.45%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 0.45%   |
| Unknown                                                                    | 4         | 0.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 183       | 39.35%  |
| Alcor Micro               | 167       | 35.91%  |
| Upek                      | 33        | 7.1%    |
| O2 Micro                  | 31        | 6.67%   |
| Lenovo                    | 31        | 6.67%   |
| Gemalto (was Gemplus)     | 5         | 1.08%   |
| Yubico.com                | 3         | 0.65%   |
| Clay Logic                | 3         | 0.65%   |
| SCM Microsystems          | 2         | 0.43%   |
| Aladdin Knowledge Systems | 2         | 0.43%   |
| Advanced Card Systems     | 2         | 0.43%   |
| OmniKey                   | 1         | 0.22%   |
| Cherry                    | 1         | 0.22%   |
| C3PO                      | 1         | 0.22%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 164       | 35.27%  |
| Broadcom BCM5880 Secure Applications Processor                               | 53        | 11.4%   |
| Broadcom 58200                                                               | 48        | 10.32%  |
| Broadcom 5880                                                                | 45        | 9.68%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 35        | 7.53%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 33        | 7.1%    |
| Lenovo Integrated Smart Card Reader                                          | 31        | 6.67%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 26        | 5.59%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 1.08%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 0.65%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.65%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 0.65%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.43%   |
| Clay Logic Nitrokey Start                                                    | 2         | 0.43%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.43%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.43%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.22%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.22%   |
| OmniKey CardMan 4321                                                         | 1         | 0.22%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.22%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.22%   |
| C3PO LTC31v2                                                                 | 1         | 0.22%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.22%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.22%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 3087      | 57.07%  |
| 1     | 1751      | 32.37%  |
| 2     | 450       | 8.32%   |
| 3     | 102       | 1.89%   |
| 4     | 11        | 0.2%    |
| 5     | 7         | 0.13%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 875       | 30.37%  |
| Graphics card            | 717       | 24.89%  |
| Chipcard                 | 428       | 14.86%  |
| Net/wireless             | 266       | 9.23%   |
| Multimedia controller    | 262       | 9.09%   |
| Camera                   | 76        | 2.64%   |
| Bluetooth                | 67        | 2.33%   |
| Card reader              | 42        | 1.46%   |
| Storage                  | 38        | 1.32%   |
| Communication controller | 38        | 1.32%   |
| Sound                    | 22        | 0.76%   |
| Net/ethernet             | 18        | 0.62%   |
| Network                  | 11        | 0.38%   |
| Modem                    | 7         | 0.24%   |
| Flash memory             | 6         | 0.21%   |
| Wireless                 | 2         | 0.07%   |
| Unassigned class         | 2         | 0.07%   |
| Firewire controller      | 2         | 0.07%   |
| Tv card                  | 1         | 0.03%   |
| Storage/ide              | 1         | 0.03%   |

