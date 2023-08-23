Debian 12 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Debian 12.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian_12/Desktop/README.md) and [notebooks](/Dist/Debian_12/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 1295

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | GL552VW                     | Notebook    | [6986ca63da](https://linux-hardware.org/?probe=6986ca63da) | Aug 12, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [108dae1eae](https://linux-hardware.org/?probe=108dae1eae) | Aug 12, 2023 |
| Dell          | Latitude E6430              | Notebook    | [8037585070](https://linux-hardware.org/?probe=8037585070) | Aug 12, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [475b07d2dc](https://linux-hardware.org/?probe=475b07d2dc) | Aug 12, 2023 |
| CWWK          | CW-J6-6L                    | Desktop     | [8321dcc5ea](https://linux-hardware.org/?probe=8321dcc5ea) | Aug 12, 2023 |
| Dell          | 0FDT3J A01                  | Server      | [fce762afa4](https://linux-hardware.org/?probe=fce762afa4) | Aug 12, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [618857a4ae](https://linux-hardware.org/?probe=618857a4ae) | Aug 12, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [dad31fab00](https://linux-hardware.org/?probe=dad31fab00) | Aug 12, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [4f6d84a4dd](https://linux-hardware.org/?probe=4f6d84a4dd) | Aug 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [8d7674c3b3](https://linux-hardware.org/?probe=8d7674c3b3) | Aug 11, 2023 |
| HP            | Pavilion dv5                | Notebook    | [41c7682f98](https://linux-hardware.org/?probe=41c7682f98) | Aug 11, 2023 |
| HP            | Pavilion dv5                | Notebook    | [a8f62e42dc](https://linux-hardware.org/?probe=a8f62e42dc) | Aug 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [a064a2d5fd](https://linux-hardware.org/?probe=a064a2d5fd) | Aug 11, 2023 |
| MSI           | G33M                        | Desktop     | [65de454e8b](https://linux-hardware.org/?probe=65de454e8b) | Aug 11, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [91ecb8253e](https://linux-hardware.org/?probe=91ecb8253e) | Aug 11, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [0384e8a950](https://linux-hardware.org/?probe=0384e8a950) | Aug 11, 2023 |
| Avell High... | A40 LIV                     | Notebook    | [9bc62c7eec](https://linux-hardware.org/?probe=9bc62c7eec) | Aug 11, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [e45562b838](https://linux-hardware.org/?probe=e45562b838) | Aug 10, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | Desktop     | [a0350a164c](https://linux-hardware.org/?probe=a0350a164c) | Aug 10, 2023 |
| PC Special... | NH5xAx                      | Notebook    | [891b5ec398](https://linux-hardware.org/?probe=891b5ec398) | Aug 10, 2023 |
| Lenovo        | ThinkPad T410 25372E6       | Notebook    | [69c4723b51](https://linux-hardware.org/?probe=69c4723b51) | Aug 10, 2023 |
| Dell          | 0VXN67 A01                  | Desktop     | [4fbd39d860](https://linux-hardware.org/?probe=4fbd39d860) | Aug 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S29D00    | Notebook    | [a728658683](https://linux-hardware.org/?probe=a728658683) | Aug 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [c87b299407](https://linux-hardware.org/?probe=c87b299407) | Aug 10, 2023 |
| ASRock        | Z68 Pro3                    | Desktop     | [f949a6e2a5](https://linux-hardware.org/?probe=f949a6e2a5) | Aug 09, 2023 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [3d9112e038](https://linux-hardware.org/?probe=3d9112e038) | Aug 09, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [b95e28ab5d](https://linux-hardware.org/?probe=b95e28ab5d) | Aug 09, 2023 |
| Lenovo        | G460 20041                  | Notebook    | [709445c691](https://linux-hardware.org/?probe=709445c691) | Aug 09, 2023 |
| Unknown       | AB07H                       | Desktop     | [d0b6bc1fce](https://linux-hardware.org/?probe=d0b6bc1fce) | Aug 09, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [9fcf84ff7c](https://linux-hardware.org/?probe=9fcf84ff7c) | Aug 09, 2023 |
| Supermicro    | X8ST3                       | Desktop     | [13099babf6](https://linux-hardware.org/?probe=13099babf6) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [72655a5d65](https://linux-hardware.org/?probe=72655a5d65) | Aug 08, 2023 |
| Dell          | Inspiron 7537               | Notebook    | [61093a9af1](https://linux-hardware.org/?probe=61093a9af1) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [965f96493c](https://linux-hardware.org/?probe=965f96493c) | Aug 08, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [6f5e2be121](https://linux-hardware.org/?probe=6f5e2be121) | Aug 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [c06b23398a](https://linux-hardware.org/?probe=c06b23398a) | Aug 08, 2023 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [ab74b5c684](https://linux-hardware.org/?probe=ab74b5c684) | Aug 08, 2023 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [85ffbedac4](https://linux-hardware.org/?probe=85ffbedac4) | Aug 08, 2023 |
| Avell High... | A40 LIV                     | Notebook    | [4022d66d9a](https://linux-hardware.org/?probe=4022d66d9a) | Aug 08, 2023 |
| Lenovo        | ThinkPad T530 2394EN6       | Notebook    | [d348a65379](https://linux-hardware.org/?probe=d348a65379) | Aug 07, 2023 |
| Echips Imp... | NQ15E                       | Notebook    | [7d5e97a545](https://linux-hardware.org/?probe=7d5e97a545) | Aug 07, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [36c52dfe36](https://linux-hardware.org/?probe=36c52dfe36) | Aug 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [543719cf07](https://linux-hardware.org/?probe=543719cf07) | Aug 07, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [be823adc05](https://linux-hardware.org/?probe=be823adc05) | Aug 07, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [f895d0afe3](https://linux-hardware.org/?probe=f895d0afe3) | Aug 07, 2023 |
| Acer          | Aspire TC-605               | Desktop     | [f3bac278d5](https://linux-hardware.org/?probe=f3bac278d5) | Aug 07, 2023 |
| Acer          | Aspire V5-121               | Notebook    | [4b8b0f132d](https://linux-hardware.org/?probe=4b8b0f132d) | Aug 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E02    | Notebook    | [a3e3489451](https://linux-hardware.org/?probe=a3e3489451) | Aug 07, 2023 |
| Supermicro    | X8DTU-LN4+                  | Server      | [4e56bb1720](https://linux-hardware.org/?probe=4e56bb1720) | Aug 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [7e185ae211](https://linux-hardware.org/?probe=7e185ae211) | Aug 07, 2023 |
| ASRock        | B460M Pro4                  | Desktop     | [66f1fd8cc5](https://linux-hardware.org/?probe=66f1fd8cc5) | Aug 07, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [053d461635](https://linux-hardware.org/?probe=053d461635) | Aug 06, 2023 |
| Apple         | MacBook7,1                  | Notebook    | [38d285144e](https://linux-hardware.org/?probe=38d285144e) | Aug 06, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | Notebook    | [55e9e43f37](https://linux-hardware.org/?probe=55e9e43f37) | Aug 06, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [17d44b6d2c](https://linux-hardware.org/?probe=17d44b6d2c) | Aug 06, 2023 |
| ASRock        | Q1900M                      | Desktop     | [51f69dffd5](https://linux-hardware.org/?probe=51f69dffd5) | Aug 06, 2023 |
| HP            | Presario CQ57               | Notebook    | [cd84f6fa01](https://linux-hardware.org/?probe=cd84f6fa01) | Aug 06, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [d754d51977](https://linux-hardware.org/?probe=d754d51977) | Aug 06, 2023 |
| Dell          | Latitude E5440              | Notebook    | [326ba9627a](https://linux-hardware.org/?probe=326ba9627a) | Aug 06, 2023 |
| BESSTAR Te... | GB1                         | Mini pc     | [2058978754](https://linux-hardware.org/?probe=2058978754) | Aug 06, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [d039bb9d5c](https://linux-hardware.org/?probe=d039bb9d5c) | Aug 06, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [9c2b1b1da7](https://linux-hardware.org/?probe=9c2b1b1da7) | Aug 06, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [ed642341d8](https://linux-hardware.org/?probe=ed642341d8) | Aug 06, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [456ac6507d](https://linux-hardware.org/?probe=456ac6507d) | Aug 05, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [6622cd2887](https://linux-hardware.org/?probe=6622cd2887) | Aug 05, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [39140ff7de](https://linux-hardware.org/?probe=39140ff7de) | Aug 05, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [fc1d6007aa](https://linux-hardware.org/?probe=fc1d6007aa) | Aug 05, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [deff4c99b6](https://linux-hardware.org/?probe=deff4c99b6) | Aug 05, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [8511f4c245](https://linux-hardware.org/?probe=8511f4c245) | Aug 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [5a0ec66589](https://linux-hardware.org/?probe=5a0ec66589) | Aug 05, 2023 |
| Sony          | VGN-NS11S_S                 | Notebook    | [8ad31bd20c](https://linux-hardware.org/?probe=8ad31bd20c) | Aug 05, 2023 |
| Shuttle       | DS47D                       | Notebook    | [7d1ceb9b3a](https://linux-hardware.org/?probe=7d1ceb9b3a) | Aug 05, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [04a083671d](https://linux-hardware.org/?probe=04a083671d) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [76662ba2c9](https://linux-hardware.org/?probe=76662ba2c9) | Aug 05, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [3c7626751d](https://linux-hardware.org/?probe=3c7626751d) | Aug 04, 2023 |
| Acer          | Veriton M2632G V:1.0        | Desktop     | [b66051af86](https://linux-hardware.org/?probe=b66051af86) | Aug 04, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [5157c58f81](https://linux-hardware.org/?probe=5157c58f81) | Aug 04, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [cd16d74fc1](https://linux-hardware.org/?probe=cd16d74fc1) | Aug 04, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [ac23fbd687](https://linux-hardware.org/?probe=ac23fbd687) | Aug 04, 2023 |
| Dell          | Latitude E6400              | Notebook    | [ca61145546](https://linux-hardware.org/?probe=ca61145546) | Aug 04, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [12948b89f6](https://linux-hardware.org/?probe=12948b89f6) | Aug 04, 2023 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [c125911c18](https://linux-hardware.org/?probe=c125911c18) | Aug 04, 2023 |
| ASUSTek       | M4A785T-M                   | Desktop     | [f297c8efa8](https://linux-hardware.org/?probe=f297c8efa8) | Aug 04, 2023 |
| HP            | 8620                        | Mini pc     | [3203f90412](https://linux-hardware.org/?probe=3203f90412) | Aug 04, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [7cacb46425](https://linux-hardware.org/?probe=7cacb46425) | Aug 04, 2023 |
| Dell          | XPS 9320                    | Notebook    | [140f8f8b2e](https://linux-hardware.org/?probe=140f8f8b2e) | Aug 04, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [701c63b20d](https://linux-hardware.org/?probe=701c63b20d) | Aug 04, 2023 |
| Dell          | 0WXD1Y A00                  | Server      | [fab223d590](https://linux-hardware.org/?probe=fab223d590) | Aug 04, 2023 |
| Sony          | VGN-FW373D                  | Notebook    | [535f0edf33](https://linux-hardware.org/?probe=535f0edf33) | Aug 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [51ad22a795](https://linux-hardware.org/?probe=51ad22a795) | Aug 03, 2023 |
| Dell          | Vostro 3405                 | Notebook    | [db4954c21d](https://linux-hardware.org/?probe=db4954c21d) | Aug 03, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [a3f6a98176](https://linux-hardware.org/?probe=a3f6a98176) | Aug 03, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | Notebook    | [6bc628f4e6](https://linux-hardware.org/?probe=6bc628f4e6) | Aug 03, 2023 |
| Google        | Enguarde                    | Notebook    | [663e44ce58](https://linux-hardware.org/?probe=663e44ce58) | Aug 03, 2023 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [de2d8bc0e8](https://linux-hardware.org/?probe=de2d8bc0e8) | Aug 03, 2023 |
| Intel         | NUC10i3FNB K61362-302       | Mini pc     | [341ea8b96e](https://linux-hardware.org/?probe=341ea8b96e) | Aug 03, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [3aa878541c](https://linux-hardware.org/?probe=3aa878541c) | Aug 03, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [cef74aa3cb](https://linux-hardware.org/?probe=cef74aa3cb) | Aug 03, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [1317097350](https://linux-hardware.org/?probe=1317097350) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [8036065591](https://linux-hardware.org/?probe=8036065591) | Aug 03, 2023 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [6d7ac5bfd2](https://linux-hardware.org/?probe=6d7ac5bfd2) | Aug 03, 2023 |
| Intel         | NUC7i3BNB J22859-303        | Mini pc     | [53976b8021](https://linux-hardware.org/?probe=53976b8021) | Aug 03, 2023 |
| Samsung       | 305U1A                      | Notebook    | [f65d34a8fb](https://linux-hardware.org/?probe=f65d34a8fb) | Aug 03, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [909896213c](https://linux-hardware.org/?probe=909896213c) | Aug 02, 2023 |
| ASUSTek       | 1015BX                      | Notebook    | [4770dbfc22](https://linux-hardware.org/?probe=4770dbfc22) | Aug 02, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [fd259f2acd](https://linux-hardware.org/?probe=fd259f2acd) | Aug 02, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [a1f99c3e4d](https://linux-hardware.org/?probe=a1f99c3e4d) | Aug 02, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4e092275e4](https://linux-hardware.org/?probe=4e092275e4) | Aug 02, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [0ae0b35097](https://linux-hardware.org/?probe=0ae0b35097) | Aug 02, 2023 |
| Dell          | Vostro 5515                 | Notebook    | [0e031a4729](https://linux-hardware.org/?probe=0e031a4729) | Aug 02, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [89f3f7544e](https://linux-hardware.org/?probe=89f3f7544e) | Aug 02, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [9ce9b8ab52](https://linux-hardware.org/?probe=9ce9b8ab52) | Aug 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2d046d70cc](https://linux-hardware.org/?probe=2d046d70cc) | Aug 02, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [5f9df619f5](https://linux-hardware.org/?probe=5f9df619f5) | Aug 02, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [d4c5149060](https://linux-hardware.org/?probe=d4c5149060) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [291bf82303](https://linux-hardware.org/?probe=291bf82303) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [7a9c57ad84](https://linux-hardware.org/?probe=7a9c57ad84) | Aug 02, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [dfb33be517](https://linux-hardware.org/?probe=dfb33be517) | Aug 01, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [1abb46d019](https://linux-hardware.org/?probe=1abb46d019) | Aug 01, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [7203f5ba4d](https://linux-hardware.org/?probe=7203f5ba4d) | Aug 01, 2023 |
| Intel         | NUC10i3FNB K61362-302       | Mini pc     | [ed16f197f0](https://linux-hardware.org/?probe=ed16f197f0) | Aug 01, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [b53d4c2fad](https://linux-hardware.org/?probe=b53d4c2fad) | Aug 01, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [d3250ef8d7](https://linux-hardware.org/?probe=d3250ef8d7) | Aug 01, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [1e963cc76b](https://linux-hardware.org/?probe=1e963cc76b) | Aug 01, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [3367a6e149](https://linux-hardware.org/?probe=3367a6e149) | Aug 01, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [06279baf34](https://linux-hardware.org/?probe=06279baf34) | Aug 01, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [30389578ca](https://linux-hardware.org/?probe=30389578ca) | Aug 01, 2023 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | Notebook    | [a9232da3e4](https://linux-hardware.org/?probe=a9232da3e4) | Jul 31, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [dd24507513](https://linux-hardware.org/?probe=dd24507513) | Jul 31, 2023 |
| Google        | Hanawl                      | Soc         | [08995c0e52](https://linux-hardware.org/?probe=08995c0e52) | Jul 31, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [9e297e7c8e](https://linux-hardware.org/?probe=9e297e7c8e) | Jul 31, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [de727e7124](https://linux-hardware.org/?probe=de727e7124) | Jul 31, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [3ea3ff2535](https://linux-hardware.org/?probe=3ea3ff2535) | Jul 31, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [7a8510c7fd](https://linux-hardware.org/?probe=7a8510c7fd) | Jul 31, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [1859204a6f](https://linux-hardware.org/?probe=1859204a6f) | Jul 31, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [c5205f5512](https://linux-hardware.org/?probe=c5205f5512) | Jul 30, 2023 |
| Dell          | Latitude E5270              | Notebook    | [ae07c57989](https://linux-hardware.org/?probe=ae07c57989) | Jul 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [a15a3cfa70](https://linux-hardware.org/?probe=a15a3cfa70) | Jul 30, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [43624df7d4](https://linux-hardware.org/?probe=43624df7d4) | Jul 30, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [87a4b835cf](https://linux-hardware.org/?probe=87a4b835cf) | Jul 30, 2023 |
| MSI           | B250 PC MATE                | Desktop     | [9163341ff4](https://linux-hardware.org/?probe=9163341ff4) | Jul 30, 2023 |
| Lenovo        | ThinkPad Edge E430 32543... | Notebook    | [b30651e46f](https://linux-hardware.org/?probe=b30651e46f) | Jul 30, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0YW0... | Notebook    | [3ff995e8b7](https://linux-hardware.org/?probe=3ff995e8b7) | Jul 30, 2023 |
| ASUSTek       | Zephyrus S GX701GX_GX701... | Notebook    | [69da742061](https://linux-hardware.org/?probe=69da742061) | Jul 30, 2023 |
| Lenovo        | ThinkPad X201 3680BF5       | Notebook    | [dd11ccaaad](https://linux-hardware.org/?probe=dd11ccaaad) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [d1a4b2769a](https://linux-hardware.org/?probe=d1a4b2769a) | Jul 29, 2023 |
| Unknown       | Generic RK322x Tv Box       | Other       | [db0911c516](https://linux-hardware.org/?probe=db0911c516) | Jul 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [d1bf55b135](https://linux-hardware.org/?probe=d1bf55b135) | Jul 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [ea8a893b11](https://linux-hardware.org/?probe=ea8a893b11) | Jul 29, 2023 |
| Acer          | Swift SF315-52G             | Notebook    | [aca997f2b5](https://linux-hardware.org/?probe=aca997f2b5) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [ce140941bc](https://linux-hardware.org/?probe=ce140941bc) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [19850c3ad1](https://linux-hardware.org/?probe=19850c3ad1) | Jul 29, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [7207a12cd1](https://linux-hardware.org/?probe=7207a12cd1) | Jul 29, 2023 |
| ASRock        | A620M-HDV/M.2+              | Desktop     | [ea91ff9db6](https://linux-hardware.org/?probe=ea91ff9db6) | Jul 28, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [f591b4a83a](https://linux-hardware.org/?probe=f591b4a83a) | Jul 28, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [ec65662265](https://linux-hardware.org/?probe=ec65662265) | Jul 28, 2023 |
| Dell          | 05GD68 A00                  | Desktop     | [47759e14b4](https://linux-hardware.org/?probe=47759e14b4) | Jul 28, 2023 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [b277fcda26](https://linux-hardware.org/?probe=b277fcda26) | Jul 28, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [7595472fb4](https://linux-hardware.org/?probe=7595472fb4) | Jul 28, 2023 |
| Dell          | Latitude 7480               | Notebook    | [4287f8186f](https://linux-hardware.org/?probe=4287f8186f) | Jul 28, 2023 |
| Chitech Sh... | Tibuta_MasterPad-W100       | Notebook    | [202a9be7b7](https://linux-hardware.org/?probe=202a9be7b7) | Jul 28, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [3a3d1b8e9e](https://linux-hardware.org/?probe=3a3d1b8e9e) | Jul 28, 2023 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [7adc21dcee](https://linux-hardware.org/?probe=7adc21dcee) | Jul 28, 2023 |
| Gigabyte      | B550M AORUS PRO AX          | Desktop     | [f53eed4658](https://linux-hardware.org/?probe=f53eed4658) | Jul 28, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [2e2b9a12a6](https://linux-hardware.org/?probe=2e2b9a12a6) | Jul 28, 2023 |
| Gigabyte      | P55-UD3L                    | Desktop     | [82a3947c74](https://linux-hardware.org/?probe=82a3947c74) | Jul 28, 2023 |
| AZW           | MINI S 10                   | Desktop     | [3501ec2e9a](https://linux-hardware.org/?probe=3501ec2e9a) | Jul 28, 2023 |
| Casper        | EXCALIBUR G770              | Notebook    | [1b416b9f01](https://linux-hardware.org/?probe=1b416b9f01) | Jul 28, 2023 |
| Dell          | Precision 3520              | Notebook    | [bc2e0ff018](https://linux-hardware.org/?probe=bc2e0ff018) | Jul 28, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [d52776a0a8](https://linux-hardware.org/?probe=d52776a0a8) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [9cbedced8b](https://linux-hardware.org/?probe=9cbedced8b) | Jul 28, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [1950bcc818](https://linux-hardware.org/?probe=1950bcc818) | Jul 28, 2023 |
| Dell          | System XPS L702X            | Notebook    | [5e9f83aa10](https://linux-hardware.org/?probe=5e9f83aa10) | Jul 28, 2023 |
| Acer          | Aspire A315-21G             | Notebook    | [0a4e1c4510](https://linux-hardware.org/?probe=0a4e1c4510) | Jul 28, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [83a69f246c](https://linux-hardware.org/?probe=83a69f246c) | Jul 28, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [2c6617e2f9](https://linux-hardware.org/?probe=2c6617e2f9) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [23183da982](https://linux-hardware.org/?probe=23183da982) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [77d42f4b5c](https://linux-hardware.org/?probe=77d42f4b5c) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [e8abbb213e](https://linux-hardware.org/?probe=e8abbb213e) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [bb4812527c](https://linux-hardware.org/?probe=bb4812527c) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [2b7085bd2b](https://linux-hardware.org/?probe=2b7085bd2b) | Jul 27, 2023 |
| MSI           | Z97A GAMING 7               | Desktop     | [cf2d32f045](https://linux-hardware.org/?probe=cf2d32f045) | Jul 27, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [8674c464bd](https://linux-hardware.org/?probe=8674c464bd) | Jul 27, 2023 |
| Google        | Vortininja                  | Notebook    | [70f9ee30d3](https://linux-hardware.org/?probe=70f9ee30d3) | Jul 27, 2023 |
| Intel         | X99H                        | Desktop     | [1e85498a86](https://linux-hardware.org/?probe=1e85498a86) | Jul 27, 2023 |
| Acer          | Aspire A315-23G             | Notebook    | [4d7b874be2](https://linux-hardware.org/?probe=4d7b874be2) | Jul 27, 2023 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [23d71a87d0](https://linux-hardware.org/?probe=23d71a87d0) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [a375e21964](https://linux-hardware.org/?probe=a375e21964) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [d0e6321772](https://linux-hardware.org/?probe=d0e6321772) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [28ea1c85d1](https://linux-hardware.org/?probe=28ea1c85d1) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [3fd18c9a77](https://linux-hardware.org/?probe=3fd18c9a77) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [d974298840](https://linux-hardware.org/?probe=d974298840) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [b06f493001](https://linux-hardware.org/?probe=b06f493001) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [894bb319dc](https://linux-hardware.org/?probe=894bb319dc) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [7ec6d64d2f](https://linux-hardware.org/?probe=7ec6d64d2f) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [09662b0f5d](https://linux-hardware.org/?probe=09662b0f5d) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [3c8721254c](https://linux-hardware.org/?probe=3c8721254c) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [7dfa96789f](https://linux-hardware.org/?probe=7dfa96789f) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [c538742db7](https://linux-hardware.org/?probe=c538742db7) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [9da53986f9](https://linux-hardware.org/?probe=9da53986f9) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [c950f7dbc1](https://linux-hardware.org/?probe=c950f7dbc1) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [dcf4ead958](https://linux-hardware.org/?probe=dcf4ead958) | Jul 26, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [0552cb3e44](https://linux-hardware.org/?probe=0552cb3e44) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [759b0f997f](https://linux-hardware.org/?probe=759b0f997f) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [a1ef57fb8e](https://linux-hardware.org/?probe=a1ef57fb8e) | Jul 26, 2023 |
| ASRock        | A320M Pro4                  | Desktop     | [9ecdd1e4d3](https://linux-hardware.org/?probe=9ecdd1e4d3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [f45c4baaa3](https://linux-hardware.org/?probe=f45c4baaa3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [7abbda5ed3](https://linux-hardware.org/?probe=7abbda5ed3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [67036356d3](https://linux-hardware.org/?probe=67036356d3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [5a134aede2](https://linux-hardware.org/?probe=5a134aede2) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [28c92b6f8d](https://linux-hardware.org/?probe=28c92b6f8d) | Jul 26, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [0217675942](https://linux-hardware.org/?probe=0217675942) | Jul 26, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [808dae186a](https://linux-hardware.org/?probe=808dae186a) | Jul 26, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [68ec8c0bdf](https://linux-hardware.org/?probe=68ec8c0bdf) | Jul 26, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [b45586c5cf](https://linux-hardware.org/?probe=b45586c5cf) | Jul 26, 2023 |
| Gigabyte      | GA-A55M-S2HP                | Other       | [5b1e00b374](https://linux-hardware.org/?probe=5b1e00b374) | Jul 26, 2023 |
| Dell          | Precision 3520              | Notebook    | [2502fbaef2](https://linux-hardware.org/?probe=2502fbaef2) | Jul 26, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [725aae77c4](https://linux-hardware.org/?probe=725aae77c4) | Jul 26, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [f67be57cba](https://linux-hardware.org/?probe=f67be57cba) | Jul 26, 2023 |
| Dell          | Vostro 3405                 | Notebook    | [82a990b785](https://linux-hardware.org/?probe=82a990b785) | Jul 26, 2023 |
| Dell          | Vostro 3405                 | Notebook    | [dc97ca175a](https://linux-hardware.org/?probe=dc97ca175a) | Jul 25, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [ae244aab21](https://linux-hardware.org/?probe=ae244aab21) | Jul 25, 2023 |
| Google        | Droid                       | Notebook    | [ae803483c2](https://linux-hardware.org/?probe=ae803483c2) | Jul 25, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [835ca23b88](https://linux-hardware.org/?probe=835ca23b88) | Jul 25, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f01ec95642](https://linux-hardware.org/?probe=f01ec95642) | Jul 25, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [321bdf6295](https://linux-hardware.org/?probe=321bdf6295) | Jul 25, 2023 |
| Acer          | Aspire 3610                 | Notebook    | [b40dd6ad17](https://linux-hardware.org/?probe=b40dd6ad17) | Jul 25, 2023 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [9fbb932f79](https://linux-hardware.org/?probe=9fbb932f79) | Jul 25, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [b75ed54995](https://linux-hardware.org/?probe=b75ed54995) | Jul 25, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [d60f3de4c7](https://linux-hardware.org/?probe=d60f3de4c7) | Jul 25, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [bf88e1114e](https://linux-hardware.org/?probe=bf88e1114e) | Jul 25, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [69b707119e](https://linux-hardware.org/?probe=69b707119e) | Jul 25, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [24b688cbfd](https://linux-hardware.org/?probe=24b688cbfd) | Jul 25, 2023 |
| Intel         | D34010WYK H14771-304        | Desktop     | [c5960175bc](https://linux-hardware.org/?probe=c5960175bc) | Jul 25, 2023 |
| Dell          | Latitude 3420               | Notebook    | [18d920dab2](https://linux-hardware.org/?probe=18d920dab2) | Jul 24, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [fd441fa52f](https://linux-hardware.org/?probe=fd441fa52f) | Jul 24, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [eb0aac9c32](https://linux-hardware.org/?probe=eb0aac9c32) | Jul 24, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [7076b096fd](https://linux-hardware.org/?probe=7076b096fd) | Jul 24, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [ae6caf81d7](https://linux-hardware.org/?probe=ae6caf81d7) | Jul 24, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [e1de4fabc7](https://linux-hardware.org/?probe=e1de4fabc7) | Jul 24, 2023 |
| Timi          | A7S                         | Notebook    | [d0bcd36416](https://linux-hardware.org/?probe=d0bcd36416) | Jul 24, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [15c9141aa3](https://linux-hardware.org/?probe=15c9141aa3) | Jul 24, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [b54465e0da](https://linux-hardware.org/?probe=b54465e0da) | Jul 23, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [ea2f3666ba](https://linux-hardware.org/?probe=ea2f3666ba) | Jul 23, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [f2e2436cf1](https://linux-hardware.org/?probe=f2e2436cf1) | Jul 23, 2023 |
| Radxa         | ROCK 5B                     | Soc         | [9f1e03d74d](https://linux-hardware.org/?probe=9f1e03d74d) | Jul 23, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [a3350e1d80](https://linux-hardware.org/?probe=a3350e1d80) | Jul 23, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [17f482e878](https://linux-hardware.org/?probe=17f482e878) | Jul 23, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [8c41263814](https://linux-hardware.org/?probe=8c41263814) | Jul 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [d957d5efe0](https://linux-hardware.org/?probe=d957d5efe0) | Jul 22, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [9d0eeb96a8](https://linux-hardware.org/?probe=9d0eeb96a8) | Jul 22, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [467cc30f89](https://linux-hardware.org/?probe=467cc30f89) | Jul 22, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [8dbf2477d3](https://linux-hardware.org/?probe=8dbf2477d3) | Jul 22, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [cafa1082f8](https://linux-hardware.org/?probe=cafa1082f8) | Jul 22, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [4bd62a58b8](https://linux-hardware.org/?probe=4bd62a58b8) | Jul 22, 2023 |
| Unknown       | Generic RK322x Tv Box       | Other       | [18c7d0154b](https://linux-hardware.org/?probe=18c7d0154b) | Jul 22, 2023 |
| HP            | Presario CQ57               | Notebook    | [2c1bcfe898](https://linux-hardware.org/?probe=2c1bcfe898) | Jul 22, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [2cad6d3cb7](https://linux-hardware.org/?probe=2cad6d3cb7) | Jul 22, 2023 |
| Dell          | Latitude 5580               | Notebook    | [06c9677557](https://linux-hardware.org/?probe=06c9677557) | Jul 22, 2023 |
| HP            | ENVY Laptop 17-ch2xxx       | Notebook    | [7d88a01e49](https://linux-hardware.org/?probe=7d88a01e49) | Jul 22, 2023 |
| HP            | 635                         | Notebook    | [bb148a8b2b](https://linux-hardware.org/?probe=bb148a8b2b) | Jul 21, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [08f1fe3568](https://linux-hardware.org/?probe=08f1fe3568) | Jul 20, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [cc299998bb](https://linux-hardware.org/?probe=cc299998bb) | Jul 20, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [7527ca0197](https://linux-hardware.org/?probe=7527ca0197) | Jul 20, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [d366e7101c](https://linux-hardware.org/?probe=d366e7101c) | Jul 20, 2023 |
| ASUSTek       | T100TAM                     | Notebook    | [43cb18f0ee](https://linux-hardware.org/?probe=43cb18f0ee) | Jul 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [cb0ad6375e](https://linux-hardware.org/?probe=cb0ad6375e) | Jul 20, 2023 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [311144e138](https://linux-hardware.org/?probe=311144e138) | Jul 20, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [da6bb4265c](https://linux-hardware.org/?probe=da6bb4265c) | Jul 20, 2023 |
| Notebook      | N650DU                      | Notebook    | [c04f4faa06](https://linux-hardware.org/?probe=c04f4faa06) | Jul 19, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e1bfe97e63](https://linux-hardware.org/?probe=e1bfe97e63) | Jul 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [524d69b498](https://linux-hardware.org/?probe=524d69b498) | Jul 19, 2023 |
| Acer          | Aspire 7739Z                | Notebook    | [3e75dec5e0](https://linux-hardware.org/?probe=3e75dec5e0) | Jul 19, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [9672a393c9](https://linux-hardware.org/?probe=9672a393c9) | Jul 19, 2023 |
| Dell          | 05XKKK A05                  | Server      | [3e627de1a2](https://linux-hardware.org/?probe=3e627de1a2) | Jul 19, 2023 |
| Acer          | Extensa 215-22              | Notebook    | [fc3dadd5bc](https://linux-hardware.org/?probe=fc3dadd5bc) | Jul 19, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [cdad3aa931](https://linux-hardware.org/?probe=cdad3aa931) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [bddb3e26c1](https://linux-hardware.org/?probe=bddb3e26c1) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [a4584a139f](https://linux-hardware.org/?probe=a4584a139f) | Jul 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [ce80e4d17f](https://linux-hardware.org/?probe=ce80e4d17f) | Jul 18, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [3ef8cdcacb](https://linux-hardware.org/?probe=3ef8cdcacb) | Jul 18, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [69cc1eb6f6](https://linux-hardware.org/?probe=69cc1eb6f6) | Jul 18, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [5facab887b](https://linux-hardware.org/?probe=5facab887b) | Jul 18, 2023 |
| ASUSTek       | P8H61-MX                    | Desktop     | [c68138ca5c](https://linux-hardware.org/?probe=c68138ca5c) | Jul 18, 2023 |
| HP            | Pavilion 15                 | Notebook    | [a5485bb7e0](https://linux-hardware.org/?probe=a5485bb7e0) | Jul 18, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [c6da4f3b1e](https://linux-hardware.org/?probe=c6da4f3b1e) | Jul 18, 2023 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [c2ac257f6e](https://linux-hardware.org/?probe=c2ac257f6e) | Jul 18, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [a6c81d2b9e](https://linux-hardware.org/?probe=a6c81d2b9e) | Jul 18, 2023 |
| Lenovo        | ThinkPad L580 20LW000WGE    | Notebook    | [1b210ca778](https://linux-hardware.org/?probe=1b210ca778) | Jul 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [35d510901b](https://linux-hardware.org/?probe=35d510901b) | Jul 18, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [9bd188ee9b](https://linux-hardware.org/?probe=9bd188ee9b) | Jul 18, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [9d9ff78d29](https://linux-hardware.org/?probe=9d9ff78d29) | Jul 18, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [801b25d335](https://linux-hardware.org/?probe=801b25d335) | Jul 18, 2023 |
| Foxconn       | 2A8C                        | Desktop     | [539fb9855b](https://linux-hardware.org/?probe=539fb9855b) | Jul 18, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [58e48b61c2](https://linux-hardware.org/?probe=58e48b61c2) | Jul 17, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [d75cfffdca](https://linux-hardware.org/?probe=d75cfffdca) | Jul 17, 2023 |
| MSI           | 2A9C                        | Desktop     | [676f61f0c9](https://linux-hardware.org/?probe=676f61f0c9) | Jul 17, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [fc5b33ac00](https://linux-hardware.org/?probe=fc5b33ac00) | Jul 17, 2023 |
| Unknown       | TU-142                      | Notebook    | [d62ade82c2](https://linux-hardware.org/?probe=d62ade82c2) | Jul 17, 2023 |
| MSI           | 2A9C                        | Desktop     | [87dd24dabe](https://linux-hardware.org/?probe=87dd24dabe) | Jul 17, 2023 |
| HP            | Pavilion dm1                | Notebook    | [135bb20fbd](https://linux-hardware.org/?probe=135bb20fbd) | Jul 17, 2023 |
| Acer          | Aspire A515-57T             | Notebook    | [dd4a3bf595](https://linux-hardware.org/?probe=dd4a3bf595) | Jul 17, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [65a6e11166](https://linux-hardware.org/?probe=65a6e11166) | Jul 17, 2023 |
| Acer          | Aspire A315-23G             | Notebook    | [df26ae3dab](https://linux-hardware.org/?probe=df26ae3dab) | Jul 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [ab43e6b8ef](https://linux-hardware.org/?probe=ab43e6b8ef) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [6b52cef555](https://linux-hardware.org/?probe=6b52cef555) | Jul 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [29ed3e238d](https://linux-hardware.org/?probe=29ed3e238d) | Jul 16, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | Notebook    | [899c1452e4](https://linux-hardware.org/?probe=899c1452e4) | Jul 16, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | Notebook    | [497e6c5432](https://linux-hardware.org/?probe=497e6c5432) | Jul 16, 2023 |
| Dell          | Dimension 4500S             | Desktop     | [f10ee5f25d](https://linux-hardware.org/?probe=f10ee5f25d) | Jul 16, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [cd9bfc68b6](https://linux-hardware.org/?probe=cd9bfc68b6) | Jul 16, 2023 |
| SIRAGON       | LM-C100                     | Notebook    | [daef084233](https://linux-hardware.org/?probe=daef084233) | Jul 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [1625385cef](https://linux-hardware.org/?probe=1625385cef) | Jul 16, 2023 |
| Dell          | Latitude D610               | Notebook    | [791cabd713](https://linux-hardware.org/?probe=791cabd713) | Jul 16, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [151797320d](https://linux-hardware.org/?probe=151797320d) | Jul 16, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [e760f4570f](https://linux-hardware.org/?probe=e760f4570f) | Jul 16, 2023 |
| Google        | Guado                       | Desktop     | [4216aa46a6](https://linux-hardware.org/?probe=4216aa46a6) | Jul 16, 2023 |
| Lenovo        | ThinkPad T440p 20AN0069U... | Notebook    | [02af27da78](https://linux-hardware.org/?probe=02af27da78) | Jul 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d43ad7594c](https://linux-hardware.org/?probe=d43ad7594c) | Jul 16, 2023 |
| Dell          | Latitude E6330              | Notebook    | [6adb67344f](https://linux-hardware.org/?probe=6adb67344f) | Jul 15, 2023 |
| Google        | Guado                       | Desktop     | [9a3e217e78](https://linux-hardware.org/?probe=9a3e217e78) | Jul 15, 2023 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [7e088e838b](https://linux-hardware.org/?probe=7e088e838b) | Jul 15, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1VD0... | Notebook    | [b62ed55325](https://linux-hardware.org/?probe=b62ed55325) | Jul 15, 2023 |
| Dell          | Latitude 7490               | Notebook    | [6811ebe45a](https://linux-hardware.org/?probe=6811ebe45a) | Jul 15, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [bd2e85e3ce](https://linux-hardware.org/?probe=bd2e85e3ce) | Jul 15, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [ce378ce93b](https://linux-hardware.org/?probe=ce378ce93b) | Jul 15, 2023 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [b048c3ee50](https://linux-hardware.org/?probe=b048c3ee50) | Jul 15, 2023 |
| Gigabyte      | Z490M GAMING X              | Desktop     | [fc51c8fd14](https://linux-hardware.org/?probe=fc51c8fd14) | Jul 15, 2023 |
| Gigabyte      | Z490M GAMING X              | Desktop     | [1222689443](https://linux-hardware.org/?probe=1222689443) | Jul 15, 2023 |
| Biostar       | FX9830M                     | Desktop     | [db3c95d18d](https://linux-hardware.org/?probe=db3c95d18d) | Jul 15, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [c76e3df311](https://linux-hardware.org/?probe=c76e3df311) | Jul 14, 2023 |
| Lenovo        | ThinkPad T530 2429HD6       | Notebook    | [1c48702f3c](https://linux-hardware.org/?probe=1c48702f3c) | Jul 14, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [de6db92e0a](https://linux-hardware.org/?probe=de6db92e0a) | Jul 14, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [236c9f5565](https://linux-hardware.org/?probe=236c9f5565) | Jul 14, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [f3723937e1](https://linux-hardware.org/?probe=f3723937e1) | Jul 14, 2023 |
| Lenovo        | ThinkPad X220 4290FC1       | Notebook    | [d6c0ccb8f1](https://linux-hardware.org/?probe=d6c0ccb8f1) | Jul 14, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [e5efd1b971](https://linux-hardware.org/?probe=e5efd1b971) | Jul 14, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [9404c94281](https://linux-hardware.org/?probe=9404c94281) | Jul 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [a63f044df1](https://linux-hardware.org/?probe=a63f044df1) | Jul 14, 2023 |
| HP            | Pavilion dm1                | Notebook    | [3b05c5dc5c](https://linux-hardware.org/?probe=3b05c5dc5c) | Jul 14, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [dc3059f5b9](https://linux-hardware.org/?probe=dc3059f5b9) | Jul 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [e790a3c22f](https://linux-hardware.org/?probe=e790a3c22f) | Jul 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [dae11c33ed](https://linux-hardware.org/?probe=dae11c33ed) | Jul 14, 2023 |
| Google        | Blorb                       | Notebook    | [6bbcc9b8f3](https://linux-hardware.org/?probe=6bbcc9b8f3) | Jul 14, 2023 |
| Supermicro    | X9DRT                       | Server      | [b95f28343e](https://linux-hardware.org/?probe=b95f28343e) | Jul 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [14f7ea4a48](https://linux-hardware.org/?probe=14f7ea4a48) | Jul 13, 2023 |
| Dell          | XPS 17 9730                 | Notebook    | [b074a1deb3](https://linux-hardware.org/?probe=b074a1deb3) | Jul 13, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [b52ebf4fc9](https://linux-hardware.org/?probe=b52ebf4fc9) | Jul 13, 2023 |
| Google        | Reks                        | Notebook    | [680b857c0d](https://linux-hardware.org/?probe=680b857c0d) | Jul 13, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [7d2bb16563](https://linux-hardware.org/?probe=7d2bb16563) | Jul 13, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [b054249d03](https://linux-hardware.org/?probe=b054249d03) | Jul 13, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [2551062f30](https://linux-hardware.org/?probe=2551062f30) | Jul 13, 2023 |
| ASUSTek       | P10S-I Series               | Desktop     | [109d52a9be](https://linux-hardware.org/?probe=109d52a9be) | Jul 13, 2023 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [9a192c4a0b](https://linux-hardware.org/?probe=9a192c4a0b) | Jul 13, 2023 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [34ec75d601](https://linux-hardware.org/?probe=34ec75d601) | Jul 13, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [56b110f152](https://linux-hardware.org/?probe=56b110f152) | Jul 13, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [ad9fd505fa](https://linux-hardware.org/?probe=ad9fd505fa) | Jul 13, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [1d6544e56b](https://linux-hardware.org/?probe=1d6544e56b) | Jul 12, 2023 |
| Toshiba       | Satellite S75-B             | Notebook    | [ee71e28c8f](https://linux-hardware.org/?probe=ee71e28c8f) | Jul 12, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [603a591fcb](https://linux-hardware.org/?probe=603a591fcb) | Jul 12, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [66c5696981](https://linux-hardware.org/?probe=66c5696981) | Jul 12, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8b8ef12b03](https://linux-hardware.org/?probe=8b8ef12b03) | Jul 12, 2023 |
| Acer          | Aspire 5820TG               | Notebook    | [86cfbf79ce](https://linux-hardware.org/?probe=86cfbf79ce) | Jul 12, 2023 |
| MSI           | FX603                       | Notebook    | [a2c598f9eb](https://linux-hardware.org/?probe=a2c598f9eb) | Jul 12, 2023 |
| MSI           | SUMMIT E13FlipEvo A12MT     | Notebook    | [90faae34f3](https://linux-hardware.org/?probe=90faae34f3) | Jul 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [15c5dec8dc](https://linux-hardware.org/?probe=15c5dec8dc) | Jul 12, 2023 |
| Intel         | NUC11ATBC4 M53051-303       | Mini pc     | [ea706db679](https://linux-hardware.org/?probe=ea706db679) | Jul 12, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [e40c69408d](https://linux-hardware.org/?probe=e40c69408d) | Jul 11, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [e49876314d](https://linux-hardware.org/?probe=e49876314d) | Jul 11, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [9fc68063e3](https://linux-hardware.org/?probe=9fc68063e3) | Jul 11, 2023 |
| Dell          | Latitude 7275               | Notebook    | [0647894f7f](https://linux-hardware.org/?probe=0647894f7f) | Jul 11, 2023 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [3e733151f2](https://linux-hardware.org/?probe=3e733151f2) | Jul 11, 2023 |
| HP            | ProBook 4730s               | Notebook    | [0b6a6c7260](https://linux-hardware.org/?probe=0b6a6c7260) | Jul 11, 2023 |
| HP            | EliteBook 645 14 inch G9... | Notebook    | [65f4b4e813](https://linux-hardware.org/?probe=65f4b4e813) | Jul 11, 2023 |
| Foxconn       | G33M03                      | Desktop     | [487435e6e7](https://linux-hardware.org/?probe=487435e6e7) | Jul 11, 2023 |
| Unknown       | HP Chromebook 14            | Notebook    | [63b183aa51](https://linux-hardware.org/?probe=63b183aa51) | Jul 11, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [ad7b13940b](https://linux-hardware.org/?probe=ad7b13940b) | Jul 11, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [e1700a0ab4](https://linux-hardware.org/?probe=e1700a0ab4) | Jul 11, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [cbcf43d3dd](https://linux-hardware.org/?probe=cbcf43d3dd) | Jul 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [84088522ca](https://linux-hardware.org/?probe=84088522ca) | Jul 11, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [a761bfffd2](https://linux-hardware.org/?probe=a761bfffd2) | Jul 11, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [47ea5a35cb](https://linux-hardware.org/?probe=47ea5a35cb) | Jul 11, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [0ae95a7985](https://linux-hardware.org/?probe=0ae95a7985) | Jul 10, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [73b13fd5eb](https://linux-hardware.org/?probe=73b13fd5eb) | Jul 10, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [ca0b773fe8](https://linux-hardware.org/?probe=ca0b773fe8) | Jul 10, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [de6111a05e](https://linux-hardware.org/?probe=de6111a05e) | Jul 10, 2023 |
| Loongson      | LS3A5000-7A2000-1w-EVB-V... | Desktop     | [97348ef480](https://linux-hardware.org/?probe=97348ef480) | Jul 10, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [6593286092](https://linux-hardware.org/?probe=6593286092) | Jul 10, 2023 |
| Acer          | Aspire 4937                 | Notebook    | [fe9bfd5f77](https://linux-hardware.org/?probe=fe9bfd5f77) | Jul 10, 2023 |
| ASUSTek       | Maximus VI IMPACT           | Desktop     | [ce682089cb](https://linux-hardware.org/?probe=ce682089cb) | Jul 10, 2023 |
| Unknown       | Generic RK322x Tv Box       | Other       | [a5da218315](https://linux-hardware.org/?probe=a5da218315) | Jul 10, 2023 |
| Acer          | Aspire 4937                 | Notebook    | [d4dadd2e77](https://linux-hardware.org/?probe=d4dadd2e77) | Jul 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [707f0b8eeb](https://linux-hardware.org/?probe=707f0b8eeb) | Jul 10, 2023 |
| HP            | 2B38                        | Desktop     | [94e5178425](https://linux-hardware.org/?probe=94e5178425) | Jul 10, 2023 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [a14d8855bc](https://linux-hardware.org/?probe=a14d8855bc) | Jul 10, 2023 |
| Dell          | OptiPlex 9020               | Notebook    | [3384a64b67](https://linux-hardware.org/?probe=3384a64b67) | Jul 10, 2023 |
| Fujitsu       | LIFEBOOK U727               | Notebook    | [ce095d85c9](https://linux-hardware.org/?probe=ce095d85c9) | Jul 09, 2023 |
| HP            | Pro x2 612 G1 Tablet USA... | Notebook    | [c10c965a51](https://linux-hardware.org/?probe=c10c965a51) | Jul 09, 2023 |
| Acer          | Aspire V3-372T              | Notebook    | [566ff1d23e](https://linux-hardware.org/?probe=566ff1d23e) | Jul 09, 2023 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [64e129ec04](https://linux-hardware.org/?probe=64e129ec04) | Jul 09, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [c2e76ab704](https://linux-hardware.org/?probe=c2e76ab704) | Jul 09, 2023 |
| ASUSTek       | VivoBook S14 X430UA         | Notebook    | [fdb15c83de](https://linux-hardware.org/?probe=fdb15c83de) | Jul 09, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [59f06e2baf](https://linux-hardware.org/?probe=59f06e2baf) | Jul 09, 2023 |
| Acer          | Aspire V3-372T              | Notebook    | [f2a9fbdf50](https://linux-hardware.org/?probe=f2a9fbdf50) | Jul 09, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [39fe220963](https://linux-hardware.org/?probe=39fe220963) | Jul 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [1e27d93bb4](https://linux-hardware.org/?probe=1e27d93bb4) | Jul 09, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [d5fa70cfda](https://linux-hardware.org/?probe=d5fa70cfda) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | Desktop     | [89e81df1b9](https://linux-hardware.org/?probe=89e81df1b9) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | Desktop     | [0eaaaced27](https://linux-hardware.org/?probe=0eaaaced27) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | Desktop     | [a208acb623](https://linux-hardware.org/?probe=a208acb623) | Jul 08, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [3bf9689ee5](https://linux-hardware.org/?probe=3bf9689ee5) | Jul 08, 2023 |
| Dell          | 0CU409                      | Desktop     | [196ea8332b](https://linux-hardware.org/?probe=196ea8332b) | Jul 08, 2023 |
| Unknown       | Unknown                     | Soc         | [e31f4bb359](https://linux-hardware.org/?probe=e31f4bb359) | Jul 08, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [5810f4f1f8](https://linux-hardware.org/?probe=5810f4f1f8) | Jul 08, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [59c2893e1a](https://linux-hardware.org/?probe=59c2893e1a) | Jul 08, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [6a739102d0](https://linux-hardware.org/?probe=6a739102d0) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [ae008e5343](https://linux-hardware.org/?probe=ae008e5343) | Jul 07, 2023 |
| ASRock        | B550 Taichi Razer Editio... | Desktop     | [c5578cae9e](https://linux-hardware.org/?probe=c5578cae9e) | Jul 07, 2023 |
| HP            | 2B4B                        | Desktop     | [9b9e0f8037](https://linux-hardware.org/?probe=9b9e0f8037) | Jul 07, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e9709930a9](https://linux-hardware.org/?probe=e9709930a9) | Jul 07, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | Notebook    | [96d1578908](https://linux-hardware.org/?probe=96d1578908) | Jul 07, 2023 |
| HP            | 2B4B                        | Desktop     | [9198ca9615](https://linux-hardware.org/?probe=9198ca9615) | Jul 07, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [abb4e75faa](https://linux-hardware.org/?probe=abb4e75faa) | Jul 07, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | Notebook    | [5d03b4b2ad](https://linux-hardware.org/?probe=5d03b4b2ad) | Jul 07, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [93f50211c2](https://linux-hardware.org/?probe=93f50211c2) | Jul 07, 2023 |
| Dell          | 0HC3G4 A00                  | Mini pc     | [66d756d3c4](https://linux-hardware.org/?probe=66d756d3c4) | Jul 06, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [905af6686d](https://linux-hardware.org/?probe=905af6686d) | Jul 06, 2023 |
| Dell          | Latitude 7430               | Notebook    | [743d41d534](https://linux-hardware.org/?probe=743d41d534) | Jul 06, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [71b3710ae4](https://linux-hardware.org/?probe=71b3710ae4) | Jul 06, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [5b085b711b](https://linux-hardware.org/?probe=5b085b711b) | Jul 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [f99a1ccf8f](https://linux-hardware.org/?probe=f99a1ccf8f) | Jul 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [37f1a0082b](https://linux-hardware.org/?probe=37f1a0082b) | Jul 06, 2023 |
| HP            | 8860 A                      | Desktop     | [5bc7810c4b](https://linux-hardware.org/?probe=5bc7810c4b) | Jul 06, 2023 |
| Lenovo        | ThinkPad T470 20HES05500    | Notebook    | [12b31081e2](https://linux-hardware.org/?probe=12b31081e2) | Jul 06, 2023 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [95d2ae1051](https://linux-hardware.org/?probe=95d2ae1051) | Jul 06, 2023 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [4f6d2375a3](https://linux-hardware.org/?probe=4f6d2375a3) | Jul 06, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [c1d387dfc5](https://linux-hardware.org/?probe=c1d387dfc5) | Jul 06, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [f255433162](https://linux-hardware.org/?probe=f255433162) | Jul 06, 2023 |
| Dell          | Precision M6800             | Notebook    | [4b8d02d04a](https://linux-hardware.org/?probe=4b8d02d04a) | Jul 06, 2023 |
| Dell          | Precision M6800             | Notebook    | [239c3ea2b9](https://linux-hardware.org/?probe=239c3ea2b9) | Jul 06, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [d6153317bf](https://linux-hardware.org/?probe=d6153317bf) | Jul 05, 2023 |
| Samsung       | 770Z5E/780Z5E               | Notebook    | [2d38e98c83](https://linux-hardware.org/?probe=2d38e98c83) | Jul 05, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [41366bcd54](https://linux-hardware.org/?probe=41366bcd54) | Jul 05, 2023 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [7e3ad6f5a7](https://linux-hardware.org/?probe=7e3ad6f5a7) | Jul 05, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9d57d6a85f](https://linux-hardware.org/?probe=9d57d6a85f) | Jul 05, 2023 |
| Gigabyte      | MZBSWAP-00                  | Desktop     | [4e61ff196e](https://linux-hardware.org/?probe=4e61ff196e) | Jul 05, 2023 |
| ASRock        | 990FX Killer                | Desktop     | [696e4c24d1](https://linux-hardware.org/?probe=696e4c24d1) | Jul 05, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [7a15493631](https://linux-hardware.org/?probe=7a15493631) | Jul 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [3707ca3e1d](https://linux-hardware.org/?probe=3707ca3e1d) | Jul 05, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [fc1c7254b3](https://linux-hardware.org/?probe=fc1c7254b3) | Jul 04, 2023 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [8c224974f3](https://linux-hardware.org/?probe=8c224974f3) | Jul 04, 2023 |
| MSI           | Creator 15M A9SD            | Notebook    | [84c85a8969](https://linux-hardware.org/?probe=84c85a8969) | Jul 04, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [79c5344e62](https://linux-hardware.org/?probe=79c5344e62) | Jul 04, 2023 |
| Google        | Lick                        | Notebook    | [f2b9397a8b](https://linux-hardware.org/?probe=f2b9397a8b) | Jul 04, 2023 |
| Acer          | Aspire C24-1651             | All in one  | [d19d72db11](https://linux-hardware.org/?probe=d19d72db11) | Jul 04, 2023 |
| MSI           | Z170A GAMING M3             | Desktop     | [ebd5d13804](https://linux-hardware.org/?probe=ebd5d13804) | Jul 04, 2023 |
| Acer          | Aspire 6930                 | Notebook    | [772d3d7f4a](https://linux-hardware.org/?probe=772d3d7f4a) | Jul 04, 2023 |
| HP            | Pavilion dv6                | Notebook    | [517e6b81c1](https://linux-hardware.org/?probe=517e6b81c1) | Jul 04, 2023 |
| iEi           | SAT3 V1.03                  | Desktop     | [fa5767b5f5](https://linux-hardware.org/?probe=fa5767b5f5) | Jul 03, 2023 |
| Lenovo        | IdeaPadFlex 5 16ABR8 82X... | Convertible | [9330835392](https://linux-hardware.org/?probe=9330835392) | Jul 03, 2023 |
| HP            | 0AECh D                     | Desktop     | [bd8035963a](https://linux-hardware.org/?probe=bd8035963a) | Jul 03, 2023 |
| Dell          | 0D24M8 A01                  | Desktop     | [8ad2509708](https://linux-hardware.org/?probe=8ad2509708) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [73146ccba2](https://linux-hardware.org/?probe=73146ccba2) | Jul 03, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [cac603cdf3](https://linux-hardware.org/?probe=cac603cdf3) | Jul 03, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [5f6fc07aaa](https://linux-hardware.org/?probe=5f6fc07aaa) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [19a254cdee](https://linux-hardware.org/?probe=19a254cdee) | Jul 03, 2023 |
| Unknown       | AB07H                       | Desktop     | [868ad2b334](https://linux-hardware.org/?probe=868ad2b334) | Jul 03, 2023 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | Notebook    | [18230f7c64](https://linux-hardware.org/?probe=18230f7c64) | Jul 03, 2023 |
| Acer          | Aspire C24-1651             | All in one  | [b93a479e9b](https://linux-hardware.org/?probe=b93a479e9b) | Jul 02, 2023 |
| Intel         | NUC13ANBi7 M89645-202       | Mini pc     | [3482361f0c](https://linux-hardware.org/?probe=3482361f0c) | Jul 02, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [a8caf9af8e](https://linux-hardware.org/?probe=a8caf9af8e) | Jul 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [4055aa6f2b](https://linux-hardware.org/?probe=4055aa6f2b) | Jul 02, 2023 |
| Dell          | Latitude 3410               | Notebook    | [11d9814008](https://linux-hardware.org/?probe=11d9814008) | Jul 02, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | Notebook    | [4708f2b480](https://linux-hardware.org/?probe=4708f2b480) | Jul 02, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [61bc4ee589](https://linux-hardware.org/?probe=61bc4ee589) | Jul 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [54987b03a1](https://linux-hardware.org/?probe=54987b03a1) | Jul 02, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [3fe182f682](https://linux-hardware.org/?probe=3fe182f682) | Jul 02, 2023 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [12a82e799d](https://linux-hardware.org/?probe=12a82e799d) | Jul 01, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [eb4b65c767](https://linux-hardware.org/?probe=eb4b65c767) | Jul 01, 2023 |
| Supermicro    | X8ST3                       | Desktop     | [91e094e5c8](https://linux-hardware.org/?probe=91e094e5c8) | Jul 01, 2023 |
| HP            | Pavilion dv7                | Notebook    | [e10b64716f](https://linux-hardware.org/?probe=e10b64716f) | Jul 01, 2023 |
| Supermicro    | X8ST3                       | Desktop     | [f1eddf9437](https://linux-hardware.org/?probe=f1eddf9437) | Jul 01, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [c55a78c98a](https://linux-hardware.org/?probe=c55a78c98a) | Jul 01, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [d0fc2ea58e](https://linux-hardware.org/?probe=d0fc2ea58e) | Jul 01, 2023 |
| Dell          | Inspiron 7720               | Notebook    | [9d8f40247e](https://linux-hardware.org/?probe=9d8f40247e) | Jul 01, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [8b5dc3456b](https://linux-hardware.org/?probe=8b5dc3456b) | Jul 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [0aed51f639](https://linux-hardware.org/?probe=0aed51f639) | Jul 01, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [55bfc9f544](https://linux-hardware.org/?probe=55bfc9f544) | Jul 01, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [4a51b35cb8](https://linux-hardware.org/?probe=4a51b35cb8) | Jul 01, 2023 |
| Dell          | Latitude 3500               | Notebook    | [8e82f9abda](https://linux-hardware.org/?probe=8e82f9abda) | Jul 01, 2023 |
| Dell          | 0HC3G4 A00                  | Mini pc     | [c111f0f4be](https://linux-hardware.org/?probe=c111f0f4be) | Jul 01, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [1df7c65f40](https://linux-hardware.org/?probe=1df7c65f40) | Jul 01, 2023 |
| Acer          | Aspire V5-123               | Notebook    | [8507833f22](https://linux-hardware.org/?probe=8507833f22) | Jul 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [eea1d9623c](https://linux-hardware.org/?probe=eea1d9623c) | Jun 30, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [39a8ee4269](https://linux-hardware.org/?probe=39a8ee4269) | Jun 30, 2023 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [b2d81d6e67](https://linux-hardware.org/?probe=b2d81d6e67) | Jun 30, 2023 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [befac7b8de](https://linux-hardware.org/?probe=befac7b8de) | Jun 30, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [a5f3a5ad14](https://linux-hardware.org/?probe=a5f3a5ad14) | Jun 30, 2023 |
| Lenovo        | ThinkPad T495 20NK000XBR    | Notebook    | [2b5e40efaa](https://linux-hardware.org/?probe=2b5e40efaa) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430s 23554L7      | Notebook    | [501b0860c8](https://linux-hardware.org/?probe=501b0860c8) | Jun 30, 2023 |
| ASRock        | Z68 Pro3 Gen3               | Desktop     | [9fc143ab80](https://linux-hardware.org/?probe=9fc143ab80) | Jun 30, 2023 |
| Dell          | G3 3590                     | Notebook    | [5c7312fed9](https://linux-hardware.org/?probe=5c7312fed9) | Jun 30, 2023 |
| ASRock        | G31M-GS                     | Desktop     | [3bd67e0f9f](https://linux-hardware.org/?probe=3bd67e0f9f) | Jun 30, 2023 |
| Lenovo        | ThinkPad L512 44444NG       | Notebook    | [300a79aa88](https://linux-hardware.org/?probe=300a79aa88) | Jun 30, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [921821fda8](https://linux-hardware.org/?probe=921821fda8) | Jun 30, 2023 |
| Dell          | Inspiron 7373               | Convertible | [e7edaad244](https://linux-hardware.org/?probe=e7edaad244) | Jun 30, 2023 |
| ASUSTek       | K52F                        | Notebook    | [98e9b448c7](https://linux-hardware.org/?probe=98e9b448c7) | Jun 30, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [a3de72d73c](https://linux-hardware.org/?probe=a3de72d73c) | Jun 29, 2023 |
| Dell          | 0PU052                      | Desktop     | [b4fde65c68](https://linux-hardware.org/?probe=b4fde65c68) | Jun 29, 2023 |
| Lenovo        | ThinkPad T440p 2000CT0      | Notebook    | [10c852dc38](https://linux-hardware.org/?probe=10c852dc38) | Jun 29, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [25a1aaf938](https://linux-hardware.org/?probe=25a1aaf938) | Jun 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | Notebook    | [a50310948a](https://linux-hardware.org/?probe=a50310948a) | Jun 29, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [a996f391dc](https://linux-hardware.org/?probe=a996f391dc) | Jun 29, 2023 |
| Dell          | Latitude 3500               | Notebook    | [e1831984f8](https://linux-hardware.org/?probe=e1831984f8) | Jun 28, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d6823d5ec7](https://linux-hardware.org/?probe=d6823d5ec7) | Jun 28, 2023 |
| Aquarius      | NS585                       | Notebook    | [52a07593c9](https://linux-hardware.org/?probe=52a07593c9) | Jun 28, 2023 |
| HP            | Pavilion dv6                | Notebook    | [7fe9e439c0](https://linux-hardware.org/?probe=7fe9e439c0) | Jun 28, 2023 |
| Aquarius      | NS585                       | Notebook    | [b2f86e98f9](https://linux-hardware.org/?probe=b2f86e98f9) | Jun 28, 2023 |
| HP            | 21B4 A01                    | Desktop     | [50656fb7ec](https://linux-hardware.org/?probe=50656fb7ec) | Jun 28, 2023 |
| HP            | 21B4 A01                    | Desktop     | [4d9322819d](https://linux-hardware.org/?probe=4d9322819d) | Jun 28, 2023 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [04d1ab025a](https://linux-hardware.org/?probe=04d1ab025a) | Jun 28, 2023 |
| ASUSTek       | ZenBook Pro 15 UX550GEX_... | Notebook    | [56eef68e89](https://linux-hardware.org/?probe=56eef68e89) | Jun 28, 2023 |
| OEM           | Unknown                     | Desktop     | [0448bbee67](https://linux-hardware.org/?probe=0448bbee67) | Jun 28, 2023 |
| Acer          | Aspire A315-23G             | Notebook    | [1c07c9f0b8](https://linux-hardware.org/?probe=1c07c9f0b8) | Jun 28, 2023 |
| ASUSTek       | X99-WS/IPMI                 | Desktop     | [fff4bc4f46](https://linux-hardware.org/?probe=fff4bc4f46) | Jun 28, 2023 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [bc9d733b89](https://linux-hardware.org/?probe=bc9d733b89) | Jun 27, 2023 |
| Dell          | 0H1TR9 A00                  | All in one  | [b4be8eaa80](https://linux-hardware.org/?probe=b4be8eaa80) | Jun 27, 2023 |
| Lenovo        | 1048 SDK0K17763 WIN 1801... | Desktop     | [d903758323](https://linux-hardware.org/?probe=d903758323) | Jun 27, 2023 |
| Supermicro    | X9DRT                       | Server      | [807e745cb1](https://linux-hardware.org/?probe=807e745cb1) | Jun 27, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [8112f38f33](https://linux-hardware.org/?probe=8112f38f33) | Jun 27, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [765d0708eb](https://linux-hardware.org/?probe=765d0708eb) | Jun 26, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | Notebook    | [5a062be874](https://linux-hardware.org/?probe=5a062be874) | Jun 26, 2023 |
| Dell          | 0PU052                      | Desktop     | [34eaa7185d](https://linux-hardware.org/?probe=34eaa7185d) | Jun 26, 2023 |
| ASUSTek       | M4A78T-E                    | Desktop     | [7b60ea1445](https://linux-hardware.org/?probe=7b60ea1445) | Jun 26, 2023 |
| Gigabyte      | H310MD2P-CF                 | Desktop     | [1ad319cfc7](https://linux-hardware.org/?probe=1ad319cfc7) | Jun 26, 2023 |
| HP            | EliteBook 835 13 inch G1... | Notebook    | [e43818af40](https://linux-hardware.org/?probe=e43818af40) | Jun 26, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [87962635d3](https://linux-hardware.org/?probe=87962635d3) | Jun 26, 2023 |
| LG Electro... | 17Z90R-G.AD79F              | Notebook    | [0d641b84fe](https://linux-hardware.org/?probe=0d641b84fe) | Jun 26, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [0ee45fd3e8](https://linux-hardware.org/?probe=0ee45fd3e8) | Jun 26, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [b8a3042b9d](https://linux-hardware.org/?probe=b8a3042b9d) | Jun 26, 2023 |
| Aquarius      | NS585                       | Notebook    | [25af22ec30](https://linux-hardware.org/?probe=25af22ec30) | Jun 26, 2023 |
| Aquarius      | NS585                       | Notebook    | [8e957a70f0](https://linux-hardware.org/?probe=8e957a70f0) | Jun 26, 2023 |
| Aquarius      | NS585                       | Notebook    | [bb09ae1f8d](https://linux-hardware.org/?probe=bb09ae1f8d) | Jun 26, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [07d9cc6d71](https://linux-hardware.org/?probe=07d9cc6d71) | Jun 26, 2023 |
| Apple         | MacBook2,1                  | Notebook    | [f5c0a2fd49](https://linux-hardware.org/?probe=f5c0a2fd49) | Jun 26, 2023 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [0dc147bd7c](https://linux-hardware.org/?probe=0dc147bd7c) | Jun 26, 2023 |
| Leader        | SC8-PRO                     | Stick pc    | [ad54f075f6](https://linux-hardware.org/?probe=ad54f075f6) | Jun 26, 2023 |
| Lenovo        | ThinkPad T430 34766TT       | Notebook    | [06ad7b4a25](https://linux-hardware.org/?probe=06ad7b4a25) | Jun 26, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [dfc817892b](https://linux-hardware.org/?probe=dfc817892b) | Jun 26, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | Notebook    | [ed89cd0d05](https://linux-hardware.org/?probe=ed89cd0d05) | Jun 26, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | Notebook    | [62665eec25](https://linux-hardware.org/?probe=62665eec25) | Jun 26, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [aeb1c6b8d2](https://linux-hardware.org/?probe=aeb1c6b8d2) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [0a233c34b3](https://linux-hardware.org/?probe=0a233c34b3) | Jun 26, 2023 |
| Avell High... | A70 HYB                     | Notebook    | [3ccdaf3c82](https://linux-hardware.org/?probe=3ccdaf3c82) | Jun 26, 2023 |
| ASUSTek       | E403SA                      | Notebook    | [bdc47269c3](https://linux-hardware.org/?probe=bdc47269c3) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX B760-F GAMING ... | Desktop     | [117bfb7088](https://linux-hardware.org/?probe=117bfb7088) | Jun 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | Notebook    | [cee2bb11dc](https://linux-hardware.org/?probe=cee2bb11dc) | Jun 25, 2023 |
| JINGSHA       | Unknown                     | Desktop     | [2ae6ac9599](https://linux-hardware.org/?probe=2ae6ac9599) | Jun 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [14cc9e067f](https://linux-hardware.org/?probe=14cc9e067f) | Jun 25, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [06f1256f88](https://linux-hardware.org/?probe=06f1256f88) | Jun 25, 2023 |
| Biostar       | X370GTN                     | Desktop     | [80b2b1d180](https://linux-hardware.org/?probe=80b2b1d180) | Jun 25, 2023 |
| Intel         | H55                         | Desktop     | [993c041483](https://linux-hardware.org/?probe=993c041483) | Jun 25, 2023 |
| Dell          | Latitude E6430              | Notebook    | [be9b6c75da](https://linux-hardware.org/?probe=be9b6c75da) | Jun 25, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [a87db20468](https://linux-hardware.org/?probe=a87db20468) | Jun 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [a7df01b153](https://linux-hardware.org/?probe=a7df01b153) | Jun 24, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [fe084d5ddb](https://linux-hardware.org/?probe=fe084d5ddb) | Jun 24, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | Notebook    | [a8420bc87d](https://linux-hardware.org/?probe=a8420bc87d) | Jun 24, 2023 |
| Gigabyte      | EP45C-DS3R                  | Desktop     | [655d9d950d](https://linux-hardware.org/?probe=655d9d950d) | Jun 24, 2023 |
| HP            | 872E                        | Mini pc     | [d59093e79e](https://linux-hardware.org/?probe=d59093e79e) | Jun 24, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [2c09eb930c](https://linux-hardware.org/?probe=2c09eb930c) | Jun 23, 2023 |
| ASUSTek       | K30BF_M32BF                 | Desktop     | [46a7aaf9f1](https://linux-hardware.org/?probe=46a7aaf9f1) | Jun 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [3cc7c77a76](https://linux-hardware.org/?probe=3cc7c77a76) | Jun 23, 2023 |
| Irbis         | NB131                       | Convertible | [9898b376fe](https://linux-hardware.org/?probe=9898b376fe) | Jun 23, 2023 |
| HP            | 8470p EliteBook             | Notebook    | [da3719515b](https://linux-hardware.org/?probe=da3719515b) | Jun 23, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [46d748a0a1](https://linux-hardware.org/?probe=46d748a0a1) | Jun 23, 2023 |
| Foxconn       | G31MXP FAB:1.1              | Desktop     | [9ed9153958](https://linux-hardware.org/?probe=9ed9153958) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [3cdf59359c](https://linux-hardware.org/?probe=3cdf59359c) | Jun 23, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [5298e132fc](https://linux-hardware.org/?probe=5298e132fc) | Jun 23, 2023 |
| Foxconn       | nT-iBT18/nT-iBT19/nT-iBT... | Desktop     | [51b5eb0fa2](https://linux-hardware.org/?probe=51b5eb0fa2) | Jun 23, 2023 |
| Dell          | 0HC3G4 A00                  | Mini pc     | [23723983da](https://linux-hardware.org/?probe=23723983da) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [b5576af3f8](https://linux-hardware.org/?probe=b5576af3f8) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [911336b572](https://linux-hardware.org/?probe=911336b572) | Jun 23, 2023 |
| ASUSTek       | K30BF_M32BF                 | Desktop     | [655b20a34b](https://linux-hardware.org/?probe=655b20a34b) | Jun 23, 2023 |
| Lenovo        | ThinkPad X230 2325SRQ       | Notebook    | [fd42553eea](https://linux-hardware.org/?probe=fd42553eea) | Jun 22, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [9ab87d56a7](https://linux-hardware.org/?probe=9ab87d56a7) | Jun 22, 2023 |
| ASUSTek       | X45U                        | Notebook    | [63a491a160](https://linux-hardware.org/?probe=63a491a160) | Jun 22, 2023 |
| Acer          | Aspire X1700                | Desktop     | [aac17ef2f2](https://linux-hardware.org/?probe=aac17ef2f2) | Jun 22, 2023 |
| AMI           | Intel                       | Desktop     | [1a4a632d56](https://linux-hardware.org/?probe=1a4a632d56) | Jun 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [abbb1b897d](https://linux-hardware.org/?probe=abbb1b897d) | Jun 22, 2023 |
| ASRock        | NUC-TGL                     | Desktop     | [6dcb1eb43d](https://linux-hardware.org/?probe=6dcb1eb43d) | Jun 22, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [b8e19a16f9](https://linux-hardware.org/?probe=b8e19a16f9) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7117d51b53](https://linux-hardware.org/?probe=7117d51b53) | Jun 21, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [2e32510f57](https://linux-hardware.org/?probe=2e32510f57) | Jun 21, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [9841bf505c](https://linux-hardware.org/?probe=9841bf505c) | Jun 21, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [9f3829c99f](https://linux-hardware.org/?probe=9f3829c99f) | Jun 21, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [379e3473e2](https://linux-hardware.org/?probe=379e3473e2) | Jun 21, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [8a2a9fd293](https://linux-hardware.org/?probe=8a2a9fd293) | Jun 21, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [d661316023](https://linux-hardware.org/?probe=d661316023) | Jun 21, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [b652abc634](https://linux-hardware.org/?probe=b652abc634) | Jun 21, 2023 |
| HP            | 1588h                       | Desktop     | [abe5412cf6](https://linux-hardware.org/?probe=abe5412cf6) | Jun 21, 2023 |
| HP            | 1588h                       | Desktop     | [f08e230cd3](https://linux-hardware.org/?probe=f08e230cd3) | Jun 21, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [197d2f4c7c](https://linux-hardware.org/?probe=197d2f4c7c) | Jun 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [8a61f834dd](https://linux-hardware.org/?probe=8a61f834dd) | Jun 21, 2023 |
| Dell          | Vostro 5490                 | Notebook    | [10d1aeda8b](https://linux-hardware.org/?probe=10d1aeda8b) | Jun 21, 2023 |
| Lenovo        | 310C SDK0J40697 WIN 3305... | Mini pc     | [0aa3b8d433](https://linux-hardware.org/?probe=0aa3b8d433) | Jun 21, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [dc5a63aacc](https://linux-hardware.org/?probe=dc5a63aacc) | Jun 20, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [c7e1912b55](https://linux-hardware.org/?probe=c7e1912b55) | Jun 20, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [53f708517b](https://linux-hardware.org/?probe=53f708517b) | Jun 20, 2023 |
| Google        | Stout                       | Notebook    | [cb67ad655e](https://linux-hardware.org/?probe=cb67ad655e) | Jun 20, 2023 |
| ASRock        | B760 Pro RS/D4              | Desktop     | [bf19dd1c4b](https://linux-hardware.org/?probe=bf19dd1c4b) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [1742a525de](https://linux-hardware.org/?probe=1742a525de) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [cfc9cd338e](https://linux-hardware.org/?probe=cfc9cd338e) | Jun 20, 2023 |
| Dell          | 0RW203                      | Desktop     | [6872d8e6c5](https://linux-hardware.org/?probe=6872d8e6c5) | Jun 20, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [9b75bc9f7e](https://linux-hardware.org/?probe=9b75bc9f7e) | Jun 20, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [c3f77cf346](https://linux-hardware.org/?probe=c3f77cf346) | Jun 20, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [a0862de551](https://linux-hardware.org/?probe=a0862de551) | Jun 19, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [3cfd8a448c](https://linux-hardware.org/?probe=3cfd8a448c) | Jun 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [42fd301e8b](https://linux-hardware.org/?probe=42fd301e8b) | Jun 19, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [4c2f50a608](https://linux-hardware.org/?probe=4c2f50a608) | Jun 19, 2023 |
| Lenovo        | IdeaPad S340-15APITouch ... | Notebook    | [fe617b45f8](https://linux-hardware.org/?probe=fe617b45f8) | Jun 19, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [c40116d0de](https://linux-hardware.org/?probe=c40116d0de) | Jun 19, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [b0f066ab7e](https://linux-hardware.org/?probe=b0f066ab7e) | Jun 18, 2023 |
| Dell          | Latitude E7450              | Notebook    | [addda016c8](https://linux-hardware.org/?probe=addda016c8) | Jun 18, 2023 |
| Intel         | H81                         | Desktop     | [5cda43eb30](https://linux-hardware.org/?probe=5cda43eb30) | Jun 18, 2023 |
| Xunlong       | Orange Pi Lite              | Soc         | [f7e41df8d6](https://linux-hardware.org/?probe=f7e41df8d6) | Jun 18, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [e7fdb650cd](https://linux-hardware.org/?probe=e7fdb650cd) | Jun 18, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [fe3b7abf1d](https://linux-hardware.org/?probe=fe3b7abf1d) | Jun 17, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [4b1b2457a4](https://linux-hardware.org/?probe=4b1b2457a4) | Jun 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [e4c418382a](https://linux-hardware.org/?probe=e4c418382a) | Jun 17, 2023 |
| HP            | 2B38                        | Desktop     | [b84e03e083](https://linux-hardware.org/?probe=b84e03e083) | Jun 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [26b4c05332](https://linux-hardware.org/?probe=26b4c05332) | Jun 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S10T0... | Notebook    | [a3dd392c51](https://linux-hardware.org/?probe=a3dd392c51) | Jun 17, 2023 |
| Dell          | Latitude 9420               | Convertible | [c60ca4bcc4](https://linux-hardware.org/?probe=c60ca4bcc4) | Jun 17, 2023 |
| Dell          | Latitude E6400              | Notebook    | [0f8aca3e72](https://linux-hardware.org/?probe=0f8aca3e72) | Jun 17, 2023 |
| Unknown       | Unknown                     | Soc         | [92f385e306](https://linux-hardware.org/?probe=92f385e306) | Jun 17, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [d9e1222bc3](https://linux-hardware.org/?probe=d9e1222bc3) | Jun 17, 2023 |
| ASUSTek       | P5K Premium                 | Desktop     | [dddb2b8bdf](https://linux-hardware.org/?probe=dddb2b8bdf) | Jun 17, 2023 |
| Dell          | Latitude 9420               | Convertible | [444f324394](https://linux-hardware.org/?probe=444f324394) | Jun 16, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [9cdeeb06de](https://linux-hardware.org/?probe=9cdeeb06de) | Jun 16, 2023 |
| ASRock        | B760 Pro RS/D4              | Desktop     | [6767dd6968](https://linux-hardware.org/?probe=6767dd6968) | Jun 16, 2023 |
| Lenovo        | ThinkPad P51 20HJS1SF00     | Notebook    | [664ae7a0f2](https://linux-hardware.org/?probe=664ae7a0f2) | Jun 16, 2023 |
| Dell          | 0XM089 A00                  | Server      | [c52b7c8444](https://linux-hardware.org/?probe=c52b7c8444) | Jun 16, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [ec1b8c4ef4](https://linux-hardware.org/?probe=ec1b8c4ef4) | Jun 16, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [b9bf7ea3c2](https://linux-hardware.org/?probe=b9bf7ea3c2) | Jun 16, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b05e4ee752](https://linux-hardware.org/?probe=b05e4ee752) | Jun 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [f1294224ee](https://linux-hardware.org/?probe=f1294224ee) | Jun 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [9b8a05d0f9](https://linux-hardware.org/?probe=9b8a05d0f9) | Jun 15, 2023 |
| Acer          | TravelMate 8172             | Notebook    | [569fde2487](https://linux-hardware.org/?probe=569fde2487) | Jun 15, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [2db615249d](https://linux-hardware.org/?probe=2db615249d) | Jun 15, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [138e2807af](https://linux-hardware.org/?probe=138e2807af) | Jun 15, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [5d8061c350](https://linux-hardware.org/?probe=5d8061c350) | Jun 15, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [aafa9250df](https://linux-hardware.org/?probe=aafa9250df) | Jun 15, 2023 |
| Lenovo        | B590 20206                  | Notebook    | [f7e4f16796](https://linux-hardware.org/?probe=f7e4f16796) | Jun 15, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [91787f8dfb](https://linux-hardware.org/?probe=91787f8dfb) | Jun 15, 2023 |
| ASUSTek       | M4A78T-E                    | Desktop     | [5ec4b74af2](https://linux-hardware.org/?probe=5ec4b74af2) | Jun 15, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [a708d51992](https://linux-hardware.org/?probe=a708d51992) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [eb0ba3c881](https://linux-hardware.org/?probe=eb0ba3c881) | Jun 15, 2023 |
| HP            | 2820h                       | Desktop     | [77b54a0343](https://linux-hardware.org/?probe=77b54a0343) | Jun 14, 2023 |
| HP            | 2820h                       | Desktop     | [40e65d7a30](https://linux-hardware.org/?probe=40e65d7a30) | Jun 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [65298dde46](https://linux-hardware.org/?probe=65298dde46) | Jun 14, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [b980e4f162](https://linux-hardware.org/?probe=b980e4f162) | Jun 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [294cbcd9cd](https://linux-hardware.org/?probe=294cbcd9cd) | Jun 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [11fa244fa5](https://linux-hardware.org/?probe=11fa244fa5) | Jun 14, 2023 |
| Intel         | DG41TY AAE47335-203         | Desktop     | [4f1d844d48](https://linux-hardware.org/?probe=4f1d844d48) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [3117d89b20](https://linux-hardware.org/?probe=3117d89b20) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [3feaf0bd19](https://linux-hardware.org/?probe=3feaf0bd19) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [5fc5be3367](https://linux-hardware.org/?probe=5fc5be3367) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [aba284328c](https://linux-hardware.org/?probe=aba284328c) | Jun 14, 2023 |
| Dell          | XPS M1530                   | Notebook    | [252d777fa0](https://linux-hardware.org/?probe=252d777fa0) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [b899120507](https://linux-hardware.org/?probe=b899120507) | Jun 14, 2023 |
| Acer          | TravelMate 5742Z            | Notebook    | [abf5dbde31](https://linux-hardware.org/?probe=abf5dbde31) | Jun 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [051cebacd1](https://linux-hardware.org/?probe=051cebacd1) | Jun 14, 2023 |
| Dell          | Latitude 7480               | Notebook    | [375fb09bca](https://linux-hardware.org/?probe=375fb09bca) | Jun 14, 2023 |
| Acer          | Aspire A315-23G             | Notebook    | [18a5adccb6](https://linux-hardware.org/?probe=18a5adccb6) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [221a4431e2](https://linux-hardware.org/?probe=221a4431e2) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [85abf9e475](https://linux-hardware.org/?probe=85abf9e475) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [40df819ebb](https://linux-hardware.org/?probe=40df819ebb) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [9ed186ba56](https://linux-hardware.org/?probe=9ed186ba56) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [e073b99b63](https://linux-hardware.org/?probe=e073b99b63) | Jun 13, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f444f44a49](https://linux-hardware.org/?probe=f444f44a49) | Jun 13, 2023 |
| Samsung       | 750XED                      | Notebook    | [8997330d6a](https://linux-hardware.org/?probe=8997330d6a) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [2a4d82175c](https://linux-hardware.org/?probe=2a4d82175c) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [1df32db310](https://linux-hardware.org/?probe=1df32db310) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [9949220d98](https://linux-hardware.org/?probe=9949220d98) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [d801927769](https://linux-hardware.org/?probe=d801927769) | Jun 13, 2023 |
| Shuttle       | FM10 V10                    | Desktop     | [f1396e2cce](https://linux-hardware.org/?probe=f1396e2cce) | Jun 13, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [d85ad203ff](https://linux-hardware.org/?probe=d85ad203ff) | Jun 13, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [06c6c417c9](https://linux-hardware.org/?probe=06c6c417c9) | Jun 13, 2023 |
| ECS           | G31T-M9                     | Desktop     | [ba2a738c96](https://linux-hardware.org/?probe=ba2a738c96) | Jun 13, 2023 |
| Sony          | SVE11116FGW                 | Notebook    | [4c34707bef](https://linux-hardware.org/?probe=4c34707bef) | Jun 13, 2023 |
| Sony          | SVE11116FGW                 | Notebook    | [a048cbcdeb](https://linux-hardware.org/?probe=a048cbcdeb) | Jun 13, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | Desktop     | [86ab821b84](https://linux-hardware.org/?probe=86ab821b84) | Jun 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [f578df0eb9](https://linux-hardware.org/?probe=f578df0eb9) | Jun 13, 2023 |
| Intel         | JSL MRD                     | Desktop     | [8943f697bc](https://linux-hardware.org/?probe=8943f697bc) | Jun 13, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [a515b0dbf7](https://linux-hardware.org/?probe=a515b0dbf7) | Jun 12, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | Notebook    | [20b91b813f](https://linux-hardware.org/?probe=20b91b813f) | Jun 12, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [331ac1da01](https://linux-hardware.org/?probe=331ac1da01) | Jun 12, 2023 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [dad1ea59a4](https://linux-hardware.org/?probe=dad1ea59a4) | Jun 12, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [8e5a09ba99](https://linux-hardware.org/?probe=8e5a09ba99) | Jun 12, 2023 |
| Dell          | Latitude 3320               | Notebook    | [e467a71dac](https://linux-hardware.org/?probe=e467a71dac) | Jun 12, 2023 |
| Dell          | Latitude 3320               | Notebook    | [ec4f04b63e](https://linux-hardware.org/?probe=ec4f04b63e) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | Notebook    | [7a4183e095](https://linux-hardware.org/?probe=7a4183e095) | Jun 12, 2023 |
| ASRock        | H310CM-HDV                  | Desktop     | [a810b267ef](https://linux-hardware.org/?probe=a810b267ef) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | Notebook    | [2051db7014](https://linux-hardware.org/?probe=2051db7014) | Jun 12, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [9ac2f1ed7e](https://linux-hardware.org/?probe=9ac2f1ed7e) | Jun 12, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [f39a1874f7](https://linux-hardware.org/?probe=f39a1874f7) | Jun 12, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [8e9562dd9a](https://linux-hardware.org/?probe=8e9562dd9a) | Jun 11, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [6b1f9dec93](https://linux-hardware.org/?probe=6b1f9dec93) | Jun 11, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [f30be06897](https://linux-hardware.org/?probe=f30be06897) | Jun 11, 2023 |
| Dell          | Inspiron 5481               | Convertible | [ff9d9d8929](https://linux-hardware.org/?probe=ff9d9d8929) | Jun 11, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [756a317dd6](https://linux-hardware.org/?probe=756a317dd6) | Jun 11, 2023 |
| Lenovo        | G565 4385                   | Notebook    | [2fd61f3fc5](https://linux-hardware.org/?probe=2fd61f3fc5) | Jun 11, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [ceb7680734](https://linux-hardware.org/?probe=ceb7680734) | Jun 11, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0aeb6a400a](https://linux-hardware.org/?probe=0aeb6a400a) | Jun 11, 2023 |
| ASUSTek       | ZenBook UX334FAC_UX334FA    | Notebook    | [ba762c6d80](https://linux-hardware.org/?probe=ba762c6d80) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [8b88702b69](https://linux-hardware.org/?probe=8b88702b69) | Jun 11, 2023 |
| ASUSTek       | P7H55D-M PRO                | Desktop     | [6049b3d69d](https://linux-hardware.org/?probe=6049b3d69d) | Jun 10, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | Desktop     | [88955e82f2](https://linux-hardware.org/?probe=88955e82f2) | Jun 10, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [b3e01203b0](https://linux-hardware.org/?probe=b3e01203b0) | Jun 10, 2023 |
| Dell          | Latitude 5480               | Notebook    | [5b3fb0b4f8](https://linux-hardware.org/?probe=5b3fb0b4f8) | Jun 09, 2023 |
| ECS           | G31T-M9                     | Desktop     | [d8ca98b733](https://linux-hardware.org/?probe=d8ca98b733) | Jun 09, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [fb883c82bc](https://linux-hardware.org/?probe=fb883c82bc) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b2c39972c2](https://linux-hardware.org/?probe=b2c39972c2) | Jun 09, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [e54b5ce7da](https://linux-hardware.org/?probe=e54b5ce7da) | Jun 09, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [576a624a1b](https://linux-hardware.org/?probe=576a624a1b) | Jun 09, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [f1100ce875](https://linux-hardware.org/?probe=f1100ce875) | Jun 08, 2023 |
| ASUSTek       | M4A78T-E                    | Desktop     | [fa22309a62](https://linux-hardware.org/?probe=fa22309a62) | Jun 08, 2023 |
| HP            | G62                         | Notebook    | [fb9522ceac](https://linux-hardware.org/?probe=fb9522ceac) | Jun 08, 2023 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [4797a4c2f9](https://linux-hardware.org/?probe=4797a4c2f9) | Jun 08, 2023 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [53833409d1](https://linux-hardware.org/?probe=53833409d1) | Jun 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [ef71a1641b](https://linux-hardware.org/?probe=ef71a1641b) | Jun 08, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [b2c6247a0e](https://linux-hardware.org/?probe=b2c6247a0e) | Jun 07, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [2ff7b71aed](https://linux-hardware.org/?probe=2ff7b71aed) | Jun 06, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [10ecbb2117](https://linux-hardware.org/?probe=10ecbb2117) | Jun 06, 2023 |
| Fujitsu       | FMVNA4NE-                   | Notebook    | [626a677331](https://linux-hardware.org/?probe=626a677331) | Jun 06, 2023 |
| ECS           | G31T-M9                     | Desktop     | [8bb444bdd6](https://linux-hardware.org/?probe=8bb444bdd6) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [2ec944c5d0](https://linux-hardware.org/?probe=2ec944c5d0) | Jun 05, 2023 |
| Aquarius      | NS585                       | Notebook    | [b3f11e4a53](https://linux-hardware.org/?probe=b3f11e4a53) | Jun 05, 2023 |
| Fujitsu       | FMVNA4NE-                   | Notebook    | [b1c1176a5b](https://linux-hardware.org/?probe=b1c1176a5b) | Jun 05, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [8896a460d4](https://linux-hardware.org/?probe=8896a460d4) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [d392dff6bb](https://linux-hardware.org/?probe=d392dff6bb) | Jun 05, 2023 |
| ECS           | G31T-M9                     | Desktop     | [630360ab38](https://linux-hardware.org/?probe=630360ab38) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [991c5472ac](https://linux-hardware.org/?probe=991c5472ac) | Jun 05, 2023 |
| Unknown       | Unknown                     | Soc         | [9cb76f0184](https://linux-hardware.org/?probe=9cb76f0184) | Jun 04, 2023 |
| Unknown       | Unknown                     | Soc         | [7e2052896c](https://linux-hardware.org/?probe=7e2052896c) | Jun 04, 2023 |
| Dell          | Latitude 5420               | Notebook    | [9085f3c8f7](https://linux-hardware.org/?probe=9085f3c8f7) | Jun 04, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [eb51cb6dcf](https://linux-hardware.org/?probe=eb51cb6dcf) | Jun 03, 2023 |
| Acer          | Aspire A115-31              | Notebook    | [338f025bce](https://linux-hardware.org/?probe=338f025bce) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [5387bcbf7d](https://linux-hardware.org/?probe=5387bcbf7d) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [881df8f45c](https://linux-hardware.org/?probe=881df8f45c) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [0dd3be3300](https://linux-hardware.org/?probe=0dd3be3300) | Jun 03, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [8933e1b0ad](https://linux-hardware.org/?probe=8933e1b0ad) | Jun 03, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [2a67b74a26](https://linux-hardware.org/?probe=2a67b74a26) | Jun 02, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [2f7bb21988](https://linux-hardware.org/?probe=2f7bb21988) | Jun 02, 2023 |
| HC Technol... | HCAR357-NR                  | Desktop     | [58f698b10a](https://linux-hardware.org/?probe=58f698b10a) | Jun 02, 2023 |
| MSI           | G31TM-P21                   | Desktop     | [964377db0b](https://linux-hardware.org/?probe=964377db0b) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [853bd25ca5](https://linux-hardware.org/?probe=853bd25ca5) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [3a9fb692f1](https://linux-hardware.org/?probe=3a9fb692f1) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [9b549fe65a](https://linux-hardware.org/?probe=9b549fe65a) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [db685837d0](https://linux-hardware.org/?probe=db685837d0) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [968b38e0b9](https://linux-hardware.org/?probe=968b38e0b9) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [c9a04d8da0](https://linux-hardware.org/?probe=c9a04d8da0) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [238931757a](https://linux-hardware.org/?probe=238931757a) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [e190e991a6](https://linux-hardware.org/?probe=e190e991a6) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [0816e77499](https://linux-hardware.org/?probe=0816e77499) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [ff143ac918](https://linux-hardware.org/?probe=ff143ac918) | Jun 02, 2023 |
| Aquarius      | NS585                       | Notebook    | [6f93385917](https://linux-hardware.org/?probe=6f93385917) | Jun 02, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [bd3a6c5bd8](https://linux-hardware.org/?probe=bd3a6c5bd8) | Jun 02, 2023 |
| Aquarius      | NS585                       | Notebook    | [091267ec3a](https://linux-hardware.org/?probe=091267ec3a) | Jun 02, 2023 |
| Aquarius      | NS585                       | Notebook    | [7534819f94](https://linux-hardware.org/?probe=7534819f94) | Jun 02, 2023 |
| Lenovo        | S40-70 80GQ                 | Notebook    | [9a3fbc7388](https://linux-hardware.org/?probe=9a3fbc7388) | Jun 02, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [07e5342fb8](https://linux-hardware.org/?probe=07e5342fb8) | Jun 02, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [f3b666f725](https://linux-hardware.org/?probe=f3b666f725) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [1cf7ec0aa5](https://linux-hardware.org/?probe=1cf7ec0aa5) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [7f9d81bd57](https://linux-hardware.org/?probe=7f9d81bd57) | Jun 01, 2023 |
| Aquarius      | NS585                       | Notebook    | [ffa7425b95](https://linux-hardware.org/?probe=ffa7425b95) | Jun 01, 2023 |
| Aquarius      | NS585                       | Notebook    | [fafcbbe90e](https://linux-hardware.org/?probe=fafcbbe90e) | Jun 01, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [ffc6b5e345](https://linux-hardware.org/?probe=ffc6b5e345) | Jun 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [412c6d4af8](https://linux-hardware.org/?probe=412c6d4af8) | May 31, 2023 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [670044aef5](https://linux-hardware.org/?probe=670044aef5) | May 31, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [717c7884c8](https://linux-hardware.org/?probe=717c7884c8) | May 31, 2023 |
| ECS           | G31T-M9                     | Desktop     | [f227323587](https://linux-hardware.org/?probe=f227323587) | May 31, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [f2c67ed13d](https://linux-hardware.org/?probe=f2c67ed13d) | May 31, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [80afc31c99](https://linux-hardware.org/?probe=80afc31c99) | May 30, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [c56271ea6a](https://linux-hardware.org/?probe=c56271ea6a) | May 30, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [a0ffb7fd40](https://linux-hardware.org/?probe=a0ffb7fd40) | May 30, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [446d026ac1](https://linux-hardware.org/?probe=446d026ac1) | May 30, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [66de62e958](https://linux-hardware.org/?probe=66de62e958) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [c8e0efc288](https://linux-hardware.org/?probe=c8e0efc288) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [da399dc7cc](https://linux-hardware.org/?probe=da399dc7cc) | May 29, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [80c2e03e4e](https://linux-hardware.org/?probe=80c2e03e4e) | May 29, 2023 |
| ECS           | G31T-M9                     | Desktop     | [8f4cd5b132](https://linux-hardware.org/?probe=8f4cd5b132) | May 29, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [ffe8469edc](https://linux-hardware.org/?probe=ffe8469edc) | May 29, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [e9f274ad89](https://linux-hardware.org/?probe=e9f274ad89) | May 29, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [62a5559050](https://linux-hardware.org/?probe=62a5559050) | May 29, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [a9c147d701](https://linux-hardware.org/?probe=a9c147d701) | May 29, 2023 |
| ASRock        | J4105-ITX                   | Desktop     | [570bc894da](https://linux-hardware.org/?probe=570bc894da) | May 29, 2023 |
| HP            | EliteBook 735 G6            | Notebook    | [18b33e6fc7](https://linux-hardware.org/?probe=18b33e6fc7) | May 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [9e0fc265de](https://linux-hardware.org/?probe=9e0fc265de) | May 29, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [108833c92b](https://linux-hardware.org/?probe=108833c92b) | May 29, 2023 |
| Dell          | Latitude 7480               | Notebook    | [9eb2396796](https://linux-hardware.org/?probe=9eb2396796) | May 28, 2023 |
| Unknown       | Unknown                     | Soc         | [0f85a652ad](https://linux-hardware.org/?probe=0f85a652ad) | May 28, 2023 |
| Gigabyte      | Z690 AERO G                 | Desktop     | [5d4d7c7ef4](https://linux-hardware.org/?probe=5d4d7c7ef4) | May 27, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [447ea38d26](https://linux-hardware.org/?probe=447ea38d26) | May 27, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [57dcd55314](https://linux-hardware.org/?probe=57dcd55314) | May 27, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [bcdfc5a2bf](https://linux-hardware.org/?probe=bcdfc5a2bf) | May 27, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [68cb8bdf49](https://linux-hardware.org/?probe=68cb8bdf49) | May 27, 2023 |
| Aquarius      | NS585                       | Notebook    | [a87c8d46b6](https://linux-hardware.org/?probe=a87c8d46b6) | May 27, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [6b8c135c5d](https://linux-hardware.org/?probe=6b8c135c5d) | May 27, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [4862d28e3f](https://linux-hardware.org/?probe=4862d28e3f) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [92836191e9](https://linux-hardware.org/?probe=92836191e9) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [0d449702e3](https://linux-hardware.org/?probe=0d449702e3) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [a5fbe0c1ba](https://linux-hardware.org/?probe=a5fbe0c1ba) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [f9fd99a8b7](https://linux-hardware.org/?probe=f9fd99a8b7) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [6c87853f8c](https://linux-hardware.org/?probe=6c87853f8c) | May 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [9b93292db9](https://linux-hardware.org/?probe=9b93292db9) | May 26, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [138348e6eb](https://linux-hardware.org/?probe=138348e6eb) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [388eed2f8e](https://linux-hardware.org/?probe=388eed2f8e) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [1bc02afebc](https://linux-hardware.org/?probe=1bc02afebc) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [485617123a](https://linux-hardware.org/?probe=485617123a) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [d1933e40f4](https://linux-hardware.org/?probe=d1933e40f4) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [db84f366d0](https://linux-hardware.org/?probe=db84f366d0) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [4d7f19ec5b](https://linux-hardware.org/?probe=4d7f19ec5b) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [adb7acad13](https://linux-hardware.org/?probe=adb7acad13) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [897503110a](https://linux-hardware.org/?probe=897503110a) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [7ddbfedd32](https://linux-hardware.org/?probe=7ddbfedd32) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [96202d100a](https://linux-hardware.org/?probe=96202d100a) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [faa830a26c](https://linux-hardware.org/?probe=faa830a26c) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [03d0e0d8d7](https://linux-hardware.org/?probe=03d0e0d8d7) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [f76e433d68](https://linux-hardware.org/?probe=f76e433d68) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [610a5f2bb3](https://linux-hardware.org/?probe=610a5f2bb3) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [f10a5bd0f9](https://linux-hardware.org/?probe=f10a5bd0f9) | May 26, 2023 |
| Dell          | Latitude 3520               | Notebook    | [bfa8a18cb5](https://linux-hardware.org/?probe=bfa8a18cb5) | May 26, 2023 |
| eMachines     | E725                        | Notebook    | [a4be8012a8](https://linux-hardware.org/?probe=a4be8012a8) | May 26, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [7a40f97a17](https://linux-hardware.org/?probe=7a40f97a17) | May 26, 2023 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [66ff968642](https://linux-hardware.org/?probe=66ff968642) | May 25, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [387793dfb2](https://linux-hardware.org/?probe=387793dfb2) | May 25, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [142c9c4384](https://linux-hardware.org/?probe=142c9c4384) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [7b4b86c1ea](https://linux-hardware.org/?probe=7b4b86c1ea) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [15c2f741bf](https://linux-hardware.org/?probe=15c2f741bf) | May 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [82a0d45251](https://linux-hardware.org/?probe=82a0d45251) | May 25, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [45ac56e70c](https://linux-hardware.org/?probe=45ac56e70c) | May 25, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [ac28804681](https://linux-hardware.org/?probe=ac28804681) | May 25, 2023 |
| ASUSTek       | E35M1-M                     | Desktop     | [c62d813dd9](https://linux-hardware.org/?probe=c62d813dd9) | May 24, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [3898315bde](https://linux-hardware.org/?probe=3898315bde) | May 24, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [f8ef460648](https://linux-hardware.org/?probe=f8ef460648) | May 23, 2023 |
| Gigabyte      | M61PME-S2                   | Desktop     | [e147bb9d5e](https://linux-hardware.org/?probe=e147bb9d5e) | May 23, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [17f5577d63](https://linux-hardware.org/?probe=17f5577d63) | May 23, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [d06b734926](https://linux-hardware.org/?probe=d06b734926) | May 23, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [3ee24557f7](https://linux-hardware.org/?probe=3ee24557f7) | May 23, 2023 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [266235dc3b](https://linux-hardware.org/?probe=266235dc3b) | May 23, 2023 |
| ASRock        | H270 Performance            | Desktop     | [b3f7fdc329](https://linux-hardware.org/?probe=b3f7fdc329) | May 23, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [d784b0822d](https://linux-hardware.org/?probe=d784b0822d) | May 22, 2023 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [6ba02717d9](https://linux-hardware.org/?probe=6ba02717d9) | May 22, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [91aa0c376a](https://linux-hardware.org/?probe=91aa0c376a) | May 22, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [98f94bccb6](https://linux-hardware.org/?probe=98f94bccb6) | May 22, 2023 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [71fc64d684](https://linux-hardware.org/?probe=71fc64d684) | May 22, 2023 |
| Intel         | NUC12WSBi5 M46425-304       | Mini pc     | [b2ed9436de](https://linux-hardware.org/?probe=b2ed9436de) | May 22, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d4460792c6](https://linux-hardware.org/?probe=d4460792c6) | May 21, 2023 |
| Lenovo        | ThinkPad T410s 2904FAG      | Notebook    | [742f2c09c5](https://linux-hardware.org/?probe=742f2c09c5) | May 21, 2023 |
| Terrans Fo... | AMD                         | Notebook    | [8087d42d0e](https://linux-hardware.org/?probe=8087d42d0e) | May 21, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [473ea193d5](https://linux-hardware.org/?probe=473ea193d5) | May 21, 2023 |
| Unknown       | Unknown                     | Soc         | [d40c7d6729](https://linux-hardware.org/?probe=d40c7d6729) | May 21, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [979f49012c](https://linux-hardware.org/?probe=979f49012c) | May 21, 2023 |
| Acer          | Aspire 5253                 | Notebook    | [f28727e594](https://linux-hardware.org/?probe=f28727e594) | May 21, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a4528c4521](https://linux-hardware.org/?probe=a4528c4521) | May 20, 2023 |
| Acer          | Aspire 5739G                | Notebook    | [23a84a79ed](https://linux-hardware.org/?probe=23a84a79ed) | May 20, 2023 |
| Acer          | Aspire 5739G                | Notebook    | [2ae6c83437](https://linux-hardware.org/?probe=2ae6c83437) | May 20, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [919ed7f9e1](https://linux-hardware.org/?probe=919ed7f9e1) | May 20, 2023 |
| HP            | 1905                        | Desktop     | [1ce2caa771](https://linux-hardware.org/?probe=1ce2caa771) | May 19, 2023 |
| HP            | 1905                        | Desktop     | [de8cea1b10](https://linux-hardware.org/?probe=de8cea1b10) | May 19, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [51827f5ae5](https://linux-hardware.org/?probe=51827f5ae5) | May 19, 2023 |
| HP            | Elite x2 1013 G3            | Tablet      | [0da06960ac](https://linux-hardware.org/?probe=0da06960ac) | May 19, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [0f034f50a0](https://linux-hardware.org/?probe=0f034f50a0) | May 19, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [cdb86f0326](https://linux-hardware.org/?probe=cdb86f0326) | May 19, 2023 |
| Acer          | Aspire 5253                 | Notebook    | [fa328bbd9c](https://linux-hardware.org/?probe=fa328bbd9c) | May 19, 2023 |
| ASRock        | X299 Taichi XE              | Desktop     | [deae8ee190](https://linux-hardware.org/?probe=deae8ee190) | May 19, 2023 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [8c80042f1e](https://linux-hardware.org/?probe=8c80042f1e) | May 19, 2023 |
| Avell High... | A40 LIV                     | Notebook    | [d1e00e62c4](https://linux-hardware.org/?probe=d1e00e62c4) | May 19, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [d4c89434ae](https://linux-hardware.org/?probe=d4c89434ae) | May 18, 2023 |
| Toshiba       | Satellite C855-22N          | Notebook    | [f5ccfb46ea](https://linux-hardware.org/?probe=f5ccfb46ea) | May 18, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [94bf603662](https://linux-hardware.org/?probe=94bf603662) | May 18, 2023 |
| Aquarius      | NS585                       | Notebook    | [dc2b351b40](https://linux-hardware.org/?probe=dc2b351b40) | May 18, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [5e003a073d](https://linux-hardware.org/?probe=5e003a073d) | May 18, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [058907d9d3](https://linux-hardware.org/?probe=058907d9d3) | May 18, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | Notebook    | [66f184855c](https://linux-hardware.org/?probe=66f184855c) | May 17, 2023 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [dce4e8be7c](https://linux-hardware.org/?probe=dce4e8be7c) | May 17, 2023 |
| Acer          | TravelMate X514-51          | Notebook    | [24465d2184](https://linux-hardware.org/?probe=24465d2184) | May 17, 2023 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [a65ace49b0](https://linux-hardware.org/?probe=a65ace49b0) | May 17, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [bd8552e2d6](https://linux-hardware.org/?probe=bd8552e2d6) | May 17, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [b9410e67b1](https://linux-hardware.org/?probe=b9410e67b1) | May 17, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAA... | Notebook    | [5e4e802b87](https://linux-hardware.org/?probe=5e4e802b87) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [966e89afc3](https://linux-hardware.org/?probe=966e89afc3) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [b4bd4b7d23](https://linux-hardware.org/?probe=b4bd4b7d23) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [3089c7ab46](https://linux-hardware.org/?probe=3089c7ab46) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [a587179a2f](https://linux-hardware.org/?probe=a587179a2f) | May 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | Notebook    | [0fd753db6d](https://linux-hardware.org/?probe=0fd753db6d) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [8ab7fe837d](https://linux-hardware.org/?probe=8ab7fe837d) | May 16, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [9505c6130c](https://linux-hardware.org/?probe=9505c6130c) | May 16, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [4ea868b4d1](https://linux-hardware.org/?probe=4ea868b4d1) | May 15, 2023 |
| Gigabyte      | B760 AORUS ELITE AX         | Desktop     | [b1ab3ebdd4](https://linux-hardware.org/?probe=b1ab3ebdd4) | May 15, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c12ae2e393](https://linux-hardware.org/?probe=c12ae2e393) | May 15, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [36cb64f82a](https://linux-hardware.org/?probe=36cb64f82a) | May 15, 2023 |
| Unknown       | Unknown                     | Soc         | [8fa49f6af8](https://linux-hardware.org/?probe=8fa49f6af8) | May 14, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [7b8c68cfcf](https://linux-hardware.org/?probe=7b8c68cfcf) | May 13, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [878a94a7c7](https://linux-hardware.org/?probe=878a94a7c7) | May 13, 2023 |
| Gigabyte      | Z690 AERO G                 | Desktop     | [a199ff9b72](https://linux-hardware.org/?probe=a199ff9b72) | May 13, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | Notebook    | [a25f9e8d93](https://linux-hardware.org/?probe=a25f9e8d93) | May 13, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | Notebook    | [d2ba323017](https://linux-hardware.org/?probe=d2ba323017) | May 13, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [89747b6213](https://linux-hardware.org/?probe=89747b6213) | May 12, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [a2a47b4c35](https://linux-hardware.org/?probe=a2a47b4c35) | May 12, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [de18c72638](https://linux-hardware.org/?probe=de18c72638) | May 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2a1dfd0d0c](https://linux-hardware.org/?probe=2a1dfd0d0c) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [17510fcd4f](https://linux-hardware.org/?probe=17510fcd4f) | May 12, 2023 |
| HP            | Elite x360 830 13 inch G... | Convertible | [5ab21854e6](https://linux-hardware.org/?probe=5ab21854e6) | May 12, 2023 |
| HP            | Elite x360 830 13 inch G... | Convertible | [c5c05f7e4c](https://linux-hardware.org/?probe=c5c05f7e4c) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [6eb320d381](https://linux-hardware.org/?probe=6eb320d381) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [4bbb20185b](https://linux-hardware.org/?probe=4bbb20185b) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [f89a68e432](https://linux-hardware.org/?probe=f89a68e432) | May 12, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E02    | Notebook    | [d90b0e6626](https://linux-hardware.org/?probe=d90b0e6626) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [a07acb448b](https://linux-hardware.org/?probe=a07acb448b) | May 12, 2023 |
| Lenovo        | ThinkPad X260 20F600A7MS    | Notebook    | [67daafed56](https://linux-hardware.org/?probe=67daafed56) | May 12, 2023 |
| HP            | Elite x360 830 13 inch G... | Convertible | [d835755922](https://linux-hardware.org/?probe=d835755922) | May 12, 2023 |
| HP            | ProBook 6470b               | Notebook    | [7f1a6e0d48](https://linux-hardware.org/?probe=7f1a6e0d48) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [f4df381f0e](https://linux-hardware.org/?probe=f4df381f0e) | May 12, 2023 |
| Lenovo        | ThinkPad T440 20B7S2SM00    | Notebook    | [8f6bd394c4](https://linux-hardware.org/?probe=8f6bd394c4) | May 12, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | Notebook    | [ba177fa007](https://linux-hardware.org/?probe=ba177fa007) | May 12, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [f5d0a04a09](https://linux-hardware.org/?probe=f5d0a04a09) | May 12, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [bdcd2a3f9c](https://linux-hardware.org/?probe=bdcd2a3f9c) | May 12, 2023 |
| HP            | 829A                        | Mini pc     | [e51b2da826](https://linux-hardware.org/?probe=e51b2da826) | May 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [92a39a22a2](https://linux-hardware.org/?probe=92a39a22a2) | May 12, 2023 |
| Dell          | XPS 9315                    | Notebook    | [d53e7f5d92](https://linux-hardware.org/?probe=d53e7f5d92) | May 11, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [72aed73d34](https://linux-hardware.org/?probe=72aed73d34) | May 11, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [8ed39df8c1](https://linux-hardware.org/?probe=8ed39df8c1) | May 10, 2023 |
| Dell          | Precision 5520              | Notebook    | [5dfdbeff37](https://linux-hardware.org/?probe=5dfdbeff37) | May 10, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [0625860f59](https://linux-hardware.org/?probe=0625860f59) | May 10, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [0f4b4bd536](https://linux-hardware.org/?probe=0f4b4bd536) | May 10, 2023 |
| ECS           | G31T-M9                     | Desktop     | [25fd5432f0](https://linux-hardware.org/?probe=25fd5432f0) | May 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [c3902a3649](https://linux-hardware.org/?probe=c3902a3649) | May 10, 2023 |
| Supermicro    | X9DRW                       | Server      | [a36aa5e1ee](https://linux-hardware.org/?probe=a36aa5e1ee) | May 10, 2023 |
| Supermicro    | X8DTU                       | Server      | [c3f047a095](https://linux-hardware.org/?probe=c3f047a095) | May 10, 2023 |
| Supermicro    | X8DTU                       | Server      | [5898cc1b65](https://linux-hardware.org/?probe=5898cc1b65) | May 10, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [e61f99e96e](https://linux-hardware.org/?probe=e61f99e96e) | May 10, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [b904defc14](https://linux-hardware.org/?probe=b904defc14) | May 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [9b21cbbca0](https://linux-hardware.org/?probe=9b21cbbca0) | May 09, 2023 |
| Avell High... | A40 LIV                     | Notebook    | [c4c4a1fe74](https://linux-hardware.org/?probe=c4c4a1fe74) | May 09, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [1f874eaf6d](https://linux-hardware.org/?probe=1f874eaf6d) | May 08, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [401db07b93](https://linux-hardware.org/?probe=401db07b93) | May 08, 2023 |
| ASRock        | B760 Pro RS/D4              | Desktop     | [cf7cf903c0](https://linux-hardware.org/?probe=cf7cf903c0) | May 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [36334e327a](https://linux-hardware.org/?probe=36334e327a) | May 08, 2023 |
| HP            | 1589                        | Desktop     | [be15d33d32](https://linux-hardware.org/?probe=be15d33d32) | May 07, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | Notebook    | [7998abcdcd](https://linux-hardware.org/?probe=7998abcdcd) | May 07, 2023 |
| HP            | 829A                        | Mini pc     | [eba2b6ce4e](https://linux-hardware.org/?probe=eba2b6ce4e) | May 06, 2023 |
| GPD           | G1618-04                    | All in one  | [1ac75759ce](https://linux-hardware.org/?probe=1ac75759ce) | May 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e0357a19f3](https://linux-hardware.org/?probe=e0357a19f3) | May 05, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [d016282342](https://linux-hardware.org/?probe=d016282342) | May 05, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [27a1a2533b](https://linux-hardware.org/?probe=27a1a2533b) | May 05, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [be7c8943ce](https://linux-hardware.org/?probe=be7c8943ce) | May 05, 2023 |
| Unknown       | Unknown                     | Soc         | [043c078caf](https://linux-hardware.org/?probe=043c078caf) | May 05, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [4cc44f819d](https://linux-hardware.org/?probe=4cc44f819d) | May 05, 2023 |
| Avell High... | A40 LIV                     | Notebook    | [5745ae021d](https://linux-hardware.org/?probe=5745ae021d) | May 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [4ecbee26b1](https://linux-hardware.org/?probe=4ecbee26b1) | May 04, 2023 |
| Aquarius      | NS585                       | Notebook    | [817d9a6b62](https://linux-hardware.org/?probe=817d9a6b62) | May 04, 2023 |
| Aquarius      | NS585                       | Notebook    | [c629501448](https://linux-hardware.org/?probe=c629501448) | May 03, 2023 |
| Lenovo        | ThinkPad T495 20NK000XBR    | Notebook    | [c7ca4b1477](https://linux-hardware.org/?probe=c7ca4b1477) | May 03, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [0d7dd6a0c1](https://linux-hardware.org/?probe=0d7dd6a0c1) | May 03, 2023 |
| MSI           | Unknown                     | Notebook    | [917d7a7fc9](https://linux-hardware.org/?probe=917d7a7fc9) | May 03, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [a60578cfe2](https://linux-hardware.org/?probe=a60578cfe2) | May 02, 2023 |
| Aquarius      | NS585                       | Notebook    | [e6922e974c](https://linux-hardware.org/?probe=e6922e974c) | May 02, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [60d40b601b](https://linux-hardware.org/?probe=60d40b601b) | May 02, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [5195c623c0](https://linux-hardware.org/?probe=5195c623c0) | May 02, 2023 |
| Toshiba       | Satellite X200              | Notebook    | [e1674b1234](https://linux-hardware.org/?probe=e1674b1234) | May 02, 2023 |
| Google        | Homestar (rev4+)            | Soc         | [9184b7f306](https://linux-hardware.org/?probe=9184b7f306) | May 02, 2023 |
| Sony          | VPCF13WFX                   | Notebook    | [6500c354c7](https://linux-hardware.org/?probe=6500c354c7) | May 01, 2023 |
| Lenovo        | Slim 9 14IAP7 82T1          | Notebook    | [fe1b421c9d](https://linux-hardware.org/?probe=fe1b421c9d) | May 01, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1b2adc0ae5](https://linux-hardware.org/?probe=1b2adc0ae5) | May 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [d85b7a2592](https://linux-hardware.org/?probe=d85b7a2592) | Apr 30, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [7262375294](https://linux-hardware.org/?probe=7262375294) | Apr 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [0a9a85f5f0](https://linux-hardware.org/?probe=0a9a85f5f0) | Apr 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [83b10185e8](https://linux-hardware.org/?probe=83b10185e8) | Apr 29, 2023 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [88d774df0d](https://linux-hardware.org/?probe=88d774df0d) | Apr 29, 2023 |
| Aquarius      | NS585                       | Notebook    | [b23696ca41](https://linux-hardware.org/?probe=b23696ca41) | Apr 28, 2023 |
| sunxi         | FriendlyArm NanoPi M1       | Soc         | [dcfa7042da](https://linux-hardware.org/?probe=dcfa7042da) | Apr 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [5f5809c40f](https://linux-hardware.org/?probe=5f5809c40f) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [2474e8e580](https://linux-hardware.org/?probe=2474e8e580) | Apr 27, 2023 |
| ASUSTek       | Z97M-PLUS/BR                | Desktop     | [3255acf414](https://linux-hardware.org/?probe=3255acf414) | Apr 27, 2023 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [d395c6168d](https://linux-hardware.org/?probe=d395c6168d) | Apr 27, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [2093399e21](https://linux-hardware.org/?probe=2093399e21) | Apr 27, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [2dcf65cf8e](https://linux-hardware.org/?probe=2dcf65cf8e) | Apr 26, 2023 |
| HP            | 8309                        | Desktop     | [cde28bd710](https://linux-hardware.org/?probe=cde28bd710) | Apr 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M640... | Notebook    | [0234325d36](https://linux-hardware.org/?probe=0234325d36) | Apr 26, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [a343d9158a](https://linux-hardware.org/?probe=a343d9158a) | Apr 26, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [fa21ed6900](https://linux-hardware.org/?probe=fa21ed6900) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [a0983c89d8](https://linux-hardware.org/?probe=a0983c89d8) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [5d9edb6ed4](https://linux-hardware.org/?probe=5d9edb6ed4) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [972d7f6e4a](https://linux-hardware.org/?probe=972d7f6e4a) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [c89bbd8bc0](https://linux-hardware.org/?probe=c89bbd8bc0) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [a6e5a5f3d1](https://linux-hardware.org/?probe=a6e5a5f3d1) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [b6dac5b058](https://linux-hardware.org/?probe=b6dac5b058) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [1563889dac](https://linux-hardware.org/?probe=1563889dac) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [9bdbad2ab7](https://linux-hardware.org/?probe=9bdbad2ab7) | Apr 25, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_12/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 6.1.0-9-amd64                   | 284       | 27.57%  |
| 6.1.0-10-amd64                  | 222       | 21.55%  |
| 6.1.0-4-amd64                   | 174       | 16.89%  |
| 6.1.0-7-amd64                   | 91        | 8.83%   |
| 6.1.0-6-amd64                   | 45        | 4.37%   |
| 6.1.0-3-amd64                   | 36        | 3.5%    |
| 6.1.0-5-amd64                   | 32        | 3.11%   |
| 6.1.0-8-amd64                   | 16        | 1.55%   |
| 6.2.16-3-pve                    | 9         | 0.87%   |
| 6.1.0-10-686-pae                | 7         | 0.68%   |
| 6.0.0-6-amd64                   | 6         | 0.58%   |
| 6.0.0-2-amd64                   | 5         | 0.49%   |
| 6.2.16-6-pve                    | 4         | 0.39%   |
| 6.2.16-4-pve                    | 4         | 0.39%   |
| 6.1.0-7-rt-amd64                | 3         | 0.29%   |
| 6.1.0-11-amd64                  | 3         | 0.29%   |
| 5.15.0-starfive                 | 3         | 0.29%   |
| 6.4.3-1-liquorix-amd64          | 2         | 0.19%   |
| 6.3.0-1-amd64                   | 2         | 0.19%   |
| 6.2.16-2-pve                    | 2         | 0.19%   |
| 6.1.0-9-686-pae                 | 2         | 0.19%   |
| 6.1.0-2-amd64                   | 2         | 0.19%   |
| 6.0.0-4-amd64                   | 2         | 0.19%   |
| 6.0.0-0.deb11.6-amd64           | 2         | 0.19%   |
| 5.15.94-starfive2               | 2         | 0.19%   |
| 5.10.0-23-amd64                 | 2         | 0.19%   |
| 5.10.0-21-amd64                 | 2         | 0.19%   |
| 6.4.7-1-liquorix-amd64          | 1         | 0.1%    |
| 6.4.6-1-liquorix-amd64          | 1         | 0.1%    |
| 6.4.2-surface                   | 1         | 0.1%    |
| 6.4.2-rk322x                    | 1         | 0.1%    |
| 6.4.2-edwardron-amd64           | 1         | 0.1%    |
| 6.4.0-asahi-00515-g35564c906fa6 | 1         | 0.1%    |
| 6.4.0-1mx-ahs-amd64             | 1         | 0.1%    |
| 6.4.0-1-amd64                   | 1         | 0.1%    |
| 6.4.0-01280-g7116cae43716       | 1         | 0.1%    |
| 6.3.9-i7                        | 1         | 0.1%    |
| 6.3.9-1-liquorix-amd64          | 1         | 0.1%    |
| 6.3.8-1-liquorix-amd64          | 1         | 0.1%    |
| 6.3.7-surface                   | 1         | 0.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 6.1.0    | 897       | 89.61%  |
| 6.2.16   | 20        | 2%      |
| 6.0.0    | 16        | 1.6%    |
| 5.10.0   | 10        | 1%      |
| 6.3.0    | 5         | 0.5%    |
| 6.4.0    | 4         | 0.4%    |
| 5.15.0   | 4         | 0.4%    |
| 6.4.2    | 3         | 0.3%    |
| 6.1.11   | 3         | 0.3%    |
| 6.4.3    | 2         | 0.2%    |
| 6.3.9    | 2         | 0.2%    |
| 6.2.8    | 2         | 0.2%    |
| 6.2.11   | 2         | 0.2%    |
| 6.1.38   | 2         | 0.2%    |
| 6.1      | 2         | 0.2%    |
| 5.15.94  | 2         | 0.2%    |
| 6.4.7    | 1         | 0.1%    |
| 6.4.6    | 1         | 0.1%    |
| 6.3.8    | 1         | 0.1%    |
| 6.3.7    | 1         | 0.1%    |
| 6.3.5    | 1         | 0.1%    |
| 6.3.3    | 1         | 0.1%    |
| 6.3.10   | 1         | 0.1%    |
| 6.1.9    | 1         | 0.1%    |
| 6.1.27   | 1         | 0.1%    |
| 6.1.26   | 1         | 0.1%    |
| 6.1.25   | 1         | 0.1%    |
| 6.1.13   | 1         | 0.1%    |
| 6.1.12   | 1         | 0.1%    |
| 5.19.0   | 1         | 0.1%    |
| 5.16.0   | 1         | 0.1%    |
| 5.15.95  | 1         | 0.1%    |
| 5.15.90  | 1         | 0.1%    |
| 5.15.108 | 1         | 0.1%    |
| 5.10.142 | 1         | 0.1%    |
| 5.10.136 | 1         | 0.1%    |
| 5.10.113 | 1         | 0.1%    |
| 5.10.110 | 1         | 0.1%    |
| 4.19.0   | 1         | 0.1%    |
| 4.14.180 | 1         | 0.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 908       | 90.8%   |
| 6.2     | 24        | 2.4%    |
| 6.0     | 16        | 1.6%    |
| 5.10    | 14        | 1.4%    |
| 6.3     | 12        | 1.2%    |
| 6.4     | 11        | 1.1%    |
| 5.15    | 8         | 0.8%    |
| 6       | 2         | 0.2%    |
| 5.19    | 1         | 0.1%    |
| 5.16    | 1         | 0.1%    |
| 4.19    | 1         | 0.1%    |
| 4.14    | 1         | 0.1%    |
| 4.1     | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 963       | 96.78%  |
| i686        | 12        | 1.21%   |
| aarch64     | 8         | 0.8%    |
| riscv64     | 5         | 0.5%    |
| armv7l      | 5         | 0.5%    |
| ppc64       | 1         | 0.1%    |
| loongarch64 | 1         | 0.1%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 307       | 30.67%  |
| Unknown          | 275       | 27.47%  |
| KDE5             | 179       | 17.88%  |
| XFCE             | 84        | 8.39%   |
| X-Cinnamon       | 52        | 5.19%   |
| MATE             | 36        | 3.6%    |
| LXQt             | 12        | 1.2%    |
| LXDE             | 12        | 1.2%    |
| i3               | 11        | 1.1%    |
| GNOME Flashback  | 6         | 0.6%    |
| Cinnamon         | 6         | 0.6%    |
| GNOME Classic    | 3         | 0.3%    |
| GNUstep          | 2         | 0.2%    |
| Enlightenment    | 2         | 0.2%    |
| dwm              | 2         | 0.2%    |
| xmonad           | 1         | 0.1%    |
| Trinity          | 1         | 0.1%    |
| sway             | 1         | 0.1%    |
| Phosh:GNOME      | 1         | 0.1%    |
| Pantheon         | 1         | 0.1%    |
| openbox          | 1         | 0.1%    |
| lightdm-xsession | 1         | 0.1%    |
| KDE              | 1         | 0.1%    |
| Cutefish         | 1         | 0.1%    |
| Budgie           | 1         | 0.1%    |
| bspwm            | 1         | 0.1%    |
| awesome          | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 398       | 39.68%  |
| Wayland | 314       | 31.31%  |
| Unknown | 229       | 22.83%  |
| Tty     | 62        | 6.18%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 453       | 45.21%  |
| GDM3    | 229       | 22.85%  |
| LightDM | 165       | 16.47%  |
| SDDM    | 141       | 14.07%  |
| Ly      | 3         | 0.3%    |
| LXDM    | 3         | 0.3%    |
| XDM     | 2         | 0.2%    |
| SLiM    | 2         | 0.2%    |
| GREETD  | 2         | 0.2%    |
| GDM     | 2         | 0.2%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 323       | 32.43%  |
| ru_RU   | 211       | 21.18%  |
| de_DE   | 82        | 8.23%   |
| en_GB   | 64        | 6.43%   |
| fr_FR   | 44        | 4.42%   |
| Unknown | 40        | 4.02%   |
| pt_BR   | 24        | 2.41%   |
| es_ES   | 21        | 2.11%   |
| en_CA   | 19        | 1.91%   |
| sv_SE   | 16        | 1.61%   |
| zh_CN   | 13        | 1.31%   |
| en_IN   | 12        | 1.2%    |
| it_IT   | 11        | 1.1%    |
| C       | 11        | 1.1%    |
| pl_PL   | 10        | 1%      |
| en_AU   | 8         | 0.8%    |
| es_AR   | 6         | 0.6%    |
| hu_HU   | 4         | 0.4%    |
| fr_BE   | 4         | 0.4%    |
| en_NZ   | 4         | 0.4%    |
| en_IE   | 4         | 0.4%    |
| de_AT   | 4         | 0.4%    |
| nl_NL   | 3         | 0.3%    |
| fi_FI   | 3         | 0.3%    |
| es_VE   | 3         | 0.3%    |
| es_MX   | 3         | 0.3%    |
| es_CL   | 3         | 0.3%    |
| en_ZA   | 3         | 0.3%    |
| en_IL   | 3         | 0.3%    |
| en_DK   | 3         | 0.3%    |
| be_BY   | 3         | 0.3%    |
| tr_TR   | 2         | 0.2%    |
| pt_PT   | 2         | 0.2%    |
| ko_KR   | 2         | 0.2%    |
| es_PE   | 2         | 0.2%    |
| de_CH   | 2         | 0.2%    |
| ca_ES   | 2         | 0.2%    |
| zh_TW   | 1         | 0.1%    |
| zh_SG   | 1         | 0.1%    |
| uk_UA   | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 528       | 53.01%  |
| BIOS | 468       | 46.99%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 672       | 67.47%  |
| Overlay | 234       | 23.49%  |
| Btrfs   | 54        | 5.42%   |
| Xfs     | 12        | 1.2%    |
| Tmpfs   | 12        | 1.2%    |
| Zfs     | 8         | 0.8%    |
| Ext2    | 2         | 0.2%    |
| F2fs    | 1         | 0.1%    |
| Ext3    | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 577       | 57.82%  |
| MBR     | 239       | 23.95%  |
| Unknown | 182       | 18.24%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 871       | 87.1%   |
| Yes       | 129       | 12.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 626       | 62.79%  |
| Yes       | 371       | 37.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 173       | 17.39%  |
| Lenovo                               | 161       | 16.18%  |
| Hewlett-Packard                      | 107       | 10.75%  |
| Dell                                 | 103       | 10.35%  |
| Gigabyte Technology                  | 74        | 7.44%   |
| ASRock                               | 47        | 4.72%   |
| MSI                                  | 46        | 4.62%   |
| Acer                                 | 44        | 4.42%   |
| Aquarius                             | 29        | 2.91%   |
| Apple                                | 27        | 2.71%   |
| Unknown                              | 20        | 2.01%   |
| Intel                                | 19        | 1.91%   |
| Google                               | 11        | 1.11%   |
| HUAWEI                               | 10        | 1.01%   |
| Fujitsu                              | 8         | 0.8%    |
| Samsung Electronics                  | 7         | 0.7%    |
| Supermicro                           | 6         | 0.6%    |
| HONOR                                | 6         | 0.6%    |
| Toshiba                              | 5         | 0.5%    |
| Sony                                 | 5         | 0.5%    |
| Foxconn                              | 5         | 0.5%    |
| Microsoft                            | 4         | 0.4%    |
| ECS                                  | 4         | 0.4%    |
| eMachines                            | 3         | 0.3%    |
| Biostar                              | 3         | 0.3%    |
| Timi                                 | 2         | 0.2%    |
| Techvision                           | 2         | 0.2%    |
| Shuttle                              | 2         | 0.2%    |
| Shenzhen Meigao Electronic Equipment | 2         | 0.2%    |
| Schenker                             | 2         | 0.2%    |
| PC Specialist                        | 2         | 0.2%    |
| Notebook                             | 2         | 0.2%    |
| LG Electronics                       | 2         | 0.2%    |
| GPD                                  | 2         | 0.2%    |
| BESSTAR Tech                         | 2         | 0.2%    |
| AZW                                  | 2         | 0.2%    |
| Avell High Performance               | 2         | 0.2%    |
| ASRockRack                           | 2         | 0.2%    |
| AMI                                  | 2         | 0.2%    |
| Xunlong                              | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                            | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Aquarius NS585                                  | 29        | 2.91%   |
| ASUS All Series                                 | 28        | 2.81%   |
| Unknown                                         | 24        | 2.41%   |
| ASRock H470M-HVS                                | 20        | 2.01%   |
| Lenovo ThinkCentre M55p 8808D8U                 | 12        | 1.21%   |
| ASUS PRIME B450M-K                              | 10        | 1.01%   |
| Gigabyte H81M-S2V                               | 8         | 0.8%    |
| Gigabyte A320M-S2H V2                           | 7         | 0.7%    |
| MSI MS-7996                                     | 6         | 0.6%    |
| Apple MacBookAir7,2                             | 6         | 0.6%    |
| Lenovo ThinkPad L14 Gen 2 20X1004CMX            | 4         | 0.4%    |
| Lenovo ThinkPad L13 Yoga Gen 2 20VK0019US       | 4         | 0.4%    |
| ECS G31T-M9                                     | 4         | 0.4%    |
| Dell Precision 5570                             | 4         | 0.4%    |
| ASUS S20 K29                                    | 4         | 0.4%    |
| ASUS ProArt X670E-CREATOR WIFI                  | 4         | 0.4%    |
| HUAWEI BOHK-WAX9X                               | 3         | 0.3%    |
| HONOR NMH-WCX9                                  | 3         | 0.3%    |
| HP Laptop 15s-eq2xxx                            | 3         | 0.3%    |
| HP EliteBook 840 G5                             | 3         | 0.3%    |
| HP EliteBook 840 G3                             | 3         | 0.3%    |
| HP Elite x360 830 13 inch G9 2-in-1 Notebook PC | 3         | 0.3%    |
| Gigabyte M56S-S3                                | 3         | 0.3%    |
| Dell Latitude 7480                              | 3         | 0.3%    |
| ASUS ROG STRIX X570-E GAMING                    | 3         | 0.3%    |
| ASUS PRIME B450M-A                              | 3         | 0.3%    |
| Techvision TVI7309X                             | 2         | 0.2%    |
| Supermicro X8ST3                                | 2         | 0.2%    |
| MSI MS-7C37                                     | 2         | 0.2%    |
| Microsoft Surface Go                            | 2         | 0.2%    |
| Lenovo Yoga 7 14ARB7 82QF                       | 2         | 0.2%    |
| Lenovo ThinkStation P520 30BFS44D00             | 2         | 0.2%    |
| Lenovo ThinkPad L13 Gen 2 20VJS6RY00            | 2         | 0.2%    |
| Lenovo ThinkPad 13 2nd Gen 20J10046US           | 2         | 0.2%    |
| Lenovo IdeaPad 5 14ALC05 82LM                   | 2         | 0.2%    |
| HUAWEI MACHD-WXX9                               | 2         | 0.2%    |
| HUAWEI BOHB-WAX9                                | 2         | 0.2%    |
| HP ProBook 640 G2                               | 2         | 0.2%    |
| HP ProBook 640 G1                               | 2         | 0.2%    |
| HP ProBook 440 14 inch G9 Notebook PC           | 2         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 91        | 9.15%   |
| ASUS PRIME         | 34        | 3.42%   |
| Dell Latitude      | 30        | 3.02%   |
| Aquarius NS585     | 29        | 2.91%   |
| Acer Aspire        | 29        | 2.91%   |
| ASUS All           | 28        | 2.81%   |
| Unknown            | 24        | 2.41%   |
| Lenovo ThinkCentre | 21        | 2.11%   |
| Lenovo IdeaPad     | 20        | 2.01%   |
| HP EliteBook       | 20        | 2.01%   |
| ASRock H470M-HVS   | 20        | 2.01%   |
| Dell Inspiron      | 19        | 1.91%   |
| ASUS VivoBook      | 17        | 1.71%   |
| Dell XPS           | 16        | 1.61%   |
| HP ProBook         | 12        | 1.21%   |
| HP Pavilion        | 12        | 1.21%   |
| ASUS ROG           | 12        | 1.21%   |
| Lenovo Yoga        | 10        | 1.01%   |
| Dell Precision     | 10        | 1.01%   |
| HP Laptop          | 9         | 0.9%    |
| Gigabyte H81M-S2V  | 8         | 0.8%    |
| Dell Vostro        | 8         | 0.8%    |
| ASUS TUF           | 8         | 0.8%    |
| HP ENVY            | 7         | 0.7%    |
| Gigabyte A320M-S2H | 7         | 0.7%    |
| Dell OptiPlex      | 7         | 0.7%    |
| ASUS ZenBook       | 7         | 0.7%    |
| Apple MacBookAir7  | 7         | 0.7%    |
| MSI MS-7996        | 6         | 0.6%    |
| Dell PowerEdge     | 6         | 0.6%    |
| Acer Nitro         | 6         | 0.6%    |
| Toshiba Satellite  | 5         | 0.5%    |
| HP Elite           | 5         | 0.5%    |
| Microsoft Surface  | 4         | 0.4%    |
| HP ZBook           | 4         | 0.4%    |
| HP ProDesk         | 4         | 0.4%    |
| HP OMEN            | 4         | 0.4%    |
| Gigabyte X570      | 4         | 0.4%    |
| Gigabyte B550M     | 4         | 0.4%    |
| Gigabyte B450M     | 4         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 126       | 12.66%  |
| 2022    | 120       | 12.06%  |
| 2019    | 100       | 10.05%  |
| 2020    | 93        | 9.35%   |
| 2018    | 80        | 8.04%   |
| 2012    | 56        | 5.63%   |
| 2017    | 48        | 4.82%   |
| 2014    | 44        | 4.42%   |
| 2013    | 43        | 4.32%   |
| 2016    | 38        | 3.82%   |
| 2009    | 37        | 3.72%   |
| 2015    | 33        | 3.32%   |
| 2011    | 33        | 3.32%   |
| 2010    | 33        | 3.32%   |
| 2023    | 31        | 3.12%   |
| 2008    | 27        | 2.71%   |
| 2007    | 27        | 2.71%   |
| Unknown | 21        | 2.11%   |
| 2005    | 3         | 0.3%    |
| 2006    | 1         | 0.1%    |
| 2002    | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 502       | 50.45%  |
| Desktop        | 394       | 39.6%   |
| Convertible    | 31        | 3.12%   |
| Mini pc        | 24        | 2.41%   |
| System on chip | 14        | 1.41%   |
| All in one     | 9         | 0.9%    |
| Server         | 9         | 0.9%    |
| Tablet         | 8         | 0.8%    |
| Other          | 2         | 0.2%    |
| Phone          | 1         | 0.1%    |
| Stick pc       | 1         | 0.1%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 908       | 90.98%  |
| Enabled  | 90        | 9.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 984       | 98.89%  |
| Yes  | 11        | 1.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 244       | 24.42%  |
| 8.01-16.0       | 184       | 18.42%  |
| 16.01-24.0      | 170       | 17.02%  |
| 32.01-64.0      | 150       | 15.02%  |
| 3.01-4.0        | 131       | 13.11%  |
| 64.01-256.0     | 45        | 4.5%    |
| 1.01-2.0        | 28        | 2.8%    |
| 24.01-32.0      | 19        | 1.9%    |
| 2.01-3.0        | 15        | 1.5%    |
| 0.51-1.0        | 9         | 0.9%    |
| More than 256.0 | 2         | 0.2%    |
| 0.01-0.5        | 1         | 0.1%    |
| Unknown         | 1         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 220       | 21.53%  |
| 4.01-8.0    | 212       | 20.74%  |
| 2.01-3.0    | 204       | 19.96%  |
| 0.51-1.0    | 179       | 17.51%  |
| 3.01-4.0    | 113       | 11.06%  |
| 8.01-16.0   | 47        | 4.6%    |
| 0.01-0.5    | 29        | 2.84%   |
| 16.01-24.0  | 8         | 0.78%   |
| 24.01-32.0  | 4         | 0.39%   |
| 32.01-64.0  | 3         | 0.29%   |
| 64.01-256.0 | 2         | 0.2%    |
| Unknown     | 1         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 658       | 65.73%  |
| 2      | 211       | 21.08%  |
| 3      | 67        | 6.69%   |
| 4      | 30        | 3%      |
| 6      | 11        | 1.1%    |
| 5      | 10        | 1%      |
| 0      | 5         | 0.5%    |
| 8      | 3         | 0.3%    |
| 7      | 3         | 0.3%    |
| 29     | 1         | 0.1%    |
| 27     | 1         | 0.1%    |
| 10     | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 782       | 78.51%  |
| Yes       | 214       | 21.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 829       | 83.23%  |
| No        | 167       | 16.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 702       | 70.34%  |
| No        | 296       | 29.66%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 609       | 61.08%  |
| No        | 388       | 38.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Russia      | 225       | 22.5%   |
| USA         | 144       | 14.4%   |
| Germany     | 111       | 11.1%   |
| France      | 49        | 4.9%    |
| Brazil      | 37        | 3.7%    |
| UK          | 35        | 3.5%    |
| Sweden      | 30        | 3%      |
| Spain       | 30        | 3%      |
| Canada      | 27        | 2.7%    |
| Poland      | 24        | 2.4%    |
| Italy       | 24        | 2.4%    |
| China       | 17        | 1.7%    |
| India       | 14        | 1.4%    |
| Netherlands | 13        | 1.3%    |
| Austria     | 12        | 1.2%    |
| Switzerland | 11        | 1.1%    |
| Australia   | 11        | 1.1%    |
| Turkey      | 10        | 1%      |
| Argentina   | 10        | 1%      |
| Hungary     | 8         | 0.8%    |
| Finland     | 8         | 0.8%    |
| Czechia     | 8         | 0.8%    |
| Indonesia   | 7         | 0.7%    |
| Belgium     | 7         | 0.7%    |
| Romania     | 6         | 0.6%    |
| Norway      | 6         | 0.6%    |
| New Zealand | 6         | 0.6%    |
| Mexico      | 6         | 0.6%    |
| Belarus     | 6         | 0.6%    |
| Singapore   | 5         | 0.5%    |
| Israel      | 5         | 0.5%    |
| Venezuela   | 4         | 0.4%    |
| Portugal    | 4         | 0.4%    |
| Greece      | 4         | 0.4%    |
| Chile       | 4         | 0.4%    |
| Ukraine     | 3         | 0.3%    |
| Slovakia    | 3         | 0.3%    |
| Morocco     | 3         | 0.3%    |
| Madagascar  | 3         | 0.3%    |
| Latvia      | 3         | 0.3%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Voronezh          | 171       | 16.9%   |
| Bangor            | 37        | 3.66%   |
| Moscow            | 26        | 2.57%   |
| Saltsjoe-Boo      | 16        | 1.58%   |
| Berlin            | 10        | 0.99%   |
| Vienna            | 9         | 0.89%   |
| Paris             | 9         | 0.89%   |
| Toronto           | 8         | 0.79%   |
| St Petersburg     | 7         | 0.69%   |
| Stockholm         | 6         | 0.59%   |
| Manchester        | 6         | 0.59%   |
| Madrid            | 6         | 0.59%   |
| London            | 6         | 0.59%   |
| Frankfurt am Main | 6         | 0.59%   |
| Wroclaw           | 5         | 0.49%   |
| Singapore         | 5         | 0.49%   |
| Gladbeck          | 5         | 0.49%   |
| Bonn              | 5         | 0.49%   |
| Zurich            | 4         | 0.4%    |
| Sydney            | 4         | 0.4%    |
| Prague            | 4         | 0.4%    |
| Marseille         | 4         | 0.4%    |
| Istanbul          | 4         | 0.4%    |
| Hamburg           | 4         | 0.4%    |
| Brasília         | 4         | 0.4%    |
| Beijing           | 4         | 0.4%    |
| Strasbourg        | 3         | 0.3%    |
| Shenzhen          | 3         | 0.3%    |
| Seattle           | 3         | 0.3%    |
| Samara            | 3         | 0.3%    |
| Ottawa            | 3         | 0.3%    |
| Nuremberg         | 3         | 0.3%    |
| Munich            | 3         | 0.3%    |
| Montreal          | 3         | 0.3%    |
| Hyderabad         | 3         | 0.3%    |
| Hofheim am Taunus | 3         | 0.3%    |
| Helsinki          | 3         | 0.3%    |
| Dublin            | 3         | 0.3%    |
| Budapest          | 3         | 0.3%    |
| Barcelona         | 3         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 224       | 291    | 15.94%  |
| WDC                         | 215       | 337    | 15.3%   |
| Seagate                     | 125       | 174    | 8.9%    |
| Toshiba                     | 80        | 94     | 5.69%   |
| Crucial                     | 76        | 87     | 5.41%   |
| SanDisk                     | 73        | 84     | 5.2%    |
| Kingston                    | 63        | 70     | 4.48%   |
| Unknown                     | 55        | 72     | 3.91%   |
| SK hynix                    | 46        | 50     | 3.27%   |
| A-DATA Technology           | 45        | 61     | 3.2%    |
| Hitachi                     | 33        | 37     | 2.35%   |
| Micron Technology           | 31        | 32     | 2.21%   |
| Intel                       | 27        | 29     | 1.92%   |
| Netac                       | 26        | 27     | 1.85%   |
| HGST                        | 17        | 19     | 1.21%   |
| Apple                       | 15        | 19     | 1.07%   |
| KIOXIA                      | 14        | 16     | 1%      |
| Kingston Technology Company | 14        | 18     | 1%      |
| SPCC                        | 12        | 13     | 0.85%   |
| China                       | 11        | 13     | 0.78%   |
| Transcend                   | 10        | 11     | 0.71%   |
| Phison                      | 9         | 9      | 0.64%   |
| SSSTC                       | 8         | 8      | 0.57%   |
| LITEON                      | 8         | 8      | 0.57%   |
| JMicron Technology          | 8         | 8      | 0.57%   |
| Intenso                     | 8         | 8      | 0.57%   |
| Silicon Motion              | 7         | 9      | 0.5%    |
| Phison Electronics          | 7         | 9      | 0.5%    |
| Unknown                     | 7         | 7      | 0.5%    |
| PNY                         | 6         | 7      | 0.43%   |
| Hewlett-Packard             | 6         | 8      | 0.43%   |
| Plextor                     | 5         | 5      | 0.36%   |
| Patriot                     | 5         | 5      | 0.36%   |
| KIOXIA-EXCERIA              | 5         | 5      | 0.36%   |
| OCZ                         | 4         | 4      | 0.28%   |
| Micron/Crucial Technology   | 4         | 4      | 0.28%   |
| Gigabyte Technology         | 4         | 4      | 0.28%   |
| Fujitsu                     | 4         | 4      | 0.28%   |
| YMTC                        | 3         | 3      | 0.21%   |
| TO Exter                    | 3         | 4      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| A-DATA SU800 512GB SSD                              | 29        | 1.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 19        | 1.23%   |
| Netac SSD 240GB                                     | 19        | 1.23%   |
| Crucial CT480BX500SSD1 480GB                        | 17        | 1.1%    |
| WDC WD5000AAKX-60U6AA0 500GB                        | 15        | 0.97%   |
| Toshiba HDWD110 1TB                                 | 14        | 0.91%   |
| Kingston SA400S37480G 480GB SSD                     | 14        | 0.91%   |
| Samsung SSD 980 PRO 1TB                             | 13        | 0.84%   |
| Crucial CT240BX500SSD1 240GB                        | 13        | 0.84%   |
| Crucial CT500MX500SSD1 500GB                        | 11        | 0.71%   |
| Kingston SA400S37240G 240GB SSD                     | 10        | 0.65%   |
| Seagate ST1000DM003-1ER162 1TB                      | 9         | 0.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 9         | 0.58%   |
| Samsung SSD 980 1TB                                 | 8         | 0.52%   |
| Samsung SSD 870 EVO 500GB                           | 8         | 0.52%   |
| Samsung SSD 860 EVO 500GB                           | 8         | 0.52%   |
| Samsung MZVLB512HBJQ-000L7 512GB                    | 8         | 0.52%   |
| Crucial CT1000MX500SSD1 1TB                         | 8         | 0.52%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                | 7         | 0.45%   |
| Samsung SSD 970 EVO Plus 1TB                        | 7         | 0.45%   |
| Samsung SSD 850 EVO 500GB                           | 7         | 0.45%   |
| Kingston SA400S37120G 120GB SSD                     | 7         | 0.45%   |
| Hitachi HDS728080PLA380 40Y9028LEN 80GB             | 7         | 0.45%   |
| Unknown                                             | 7         | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 6         | 0.39%   |
| Unknown SD/MMC/MS PRO 128GB                         | 6         | 0.39%   |
| Seagate ST1000LM035-1RK172 1TB                      | 6         | 0.39%   |
| Seagate ST1000DM010-2EP102 1TB                      | 6         | 0.39%   |
| SanDisk NVMe SSD Drive 1TB                          | 6         | 0.39%   |
| Samsung SSD 970 EVO Plus 500GB                      | 6         | 0.39%   |
| Samsung SSD 860 EVO 250GB                           | 6         | 0.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 6         | 0.39%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 5         | 0.32%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 5         | 0.32%   |
| Toshiba DT01ACA100 1TB                              | 5         | 0.32%   |
| Seagate ST4000DM004-2CV104 4TB                      | 5         | 0.32%   |
| Samsung SSD 980 500GB                               | 5         | 0.32%   |
| Samsung SSD 860 EVO 1TB                             | 5         | 0.32%   |
| Samsung PM9A1 NVMe 1024GB                           | 5         | 0.32%   |
| Kingston SV300S37A120G 120GB SSD                    | 5         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 150       | 249    | 36.95%  |
| Seagate             | 120       | 168    | 29.56%  |
| Toshiba             | 56        | 69     | 13.79%  |
| Hitachi             | 33        | 37     | 8.13%   |
| HGST                | 17        | 19     | 4.19%   |
| Unknown             | 6         | 6      | 1.48%   |
| JMicron Technology  | 4         | 4      | 0.99%   |
| Fujitsu             | 4         | 4      | 0.99%   |
| Apple               | 4         | 4      | 0.99%   |
| Samsung Electronics | 3         | 3      | 0.74%   |
| Maxtor              | 2         | 2      | 0.49%   |
| WALRAM              | 1         | 1      | 0.25%   |
| USB                 | 1         | 1      | 0.25%   |
| SYMTEC              | 1         | 1      | 0.25%   |
| Hewlett-Packard     | 1         | 2      | 0.25%   |
| External            | 1         | 1      | 0.25%   |
| DELLBOSS            | 1         | 1      | 0.25%   |
| Unknown             | 1         | 1      | 0.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 83        | 101    | 17.44%  |
| Crucial             | 66        | 71     | 13.87%  |
| Kingston            | 46        | 52     | 9.66%   |
| A-DATA Technology   | 34        | 47     | 7.14%   |
| SanDisk             | 33        | 39     | 6.93%   |
| WDC                 | 31        | 41     | 6.51%   |
| Netac               | 25        | 26     | 5.25%   |
| China               | 11        | 13     | 2.31%   |
| SPCC                | 10        | 10     | 2.1%    |
| Intel               | 10        | 10     | 2.1%    |
| SK hynix            | 9         | 9      | 1.89%   |
| Apple               | 9         | 9      | 1.89%   |
| Transcend           | 8         | 9      | 1.68%   |
| Intenso             | 8         | 8      | 1.68%   |
| Toshiba             | 7         | 8      | 1.47%   |
| Micron Technology   | 6         | 7      | 1.26%   |
| LITEON              | 6         | 6      | 1.26%   |
| PNY                 | 5         | 6      | 1.05%   |
| Plextor             | 5         | 5      | 1.05%   |
| OCZ                 | 4         | 4      | 0.84%   |
| TO Exter            | 3         | 4      | 0.63%   |
| Patriot             | 3         | 3      | 0.63%   |
| Hewlett-Packard     | 3         | 3      | 0.63%   |
| GOODRAM             | 3         | 3      | 0.63%   |
| Gigabyte Technology | 3         | 3      | 0.63%   |
| Team                | 2         | 2      | 0.42%   |
| Seagate             | 2         | 2      | 0.42%   |
| LITEONIT            | 2         | 2      | 0.42%   |
| Lexar               | 2         | 2      | 0.42%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.42%   |
| AMD                 | 2         | 2      | 0.42%   |
| Wibtek              | 1         | 1      | 0.21%   |
| Wellcomm            | 1         | 1      | 0.21%   |
| V-GeN               | 1         | 1      | 0.21%   |
| TrekStor            | 1         | 1      | 0.21%   |
| Timetec             | 1         | 2      | 0.21%   |
| T-FORCE             | 1         | 2      | 0.21%   |
| SSSTC               | 1         | 1      | 0.21%   |
| SSD                 | 1         | 1      | 0.21%   |
| S3+                 | 1         | 1      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 438       | 562    | 33.93%  |
| SSD     | 426       | 545    | 33%     |
| HDD     | 357       | 573    | 27.65%  |
| MMC     | 55        | 69     | 4.26%   |
| Unknown | 15        | 17     | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 641       | 1057   | 54.23%  |
| NVMe | 436       | 556    | 36.89%  |
| MMC  | 55        | 69     | 4.65%   |
| SAS  | 50        | 84     | 4.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 468       | 587    | 57.21%  |
| 0.51-1.0   | 225       | 293    | 27.51%  |
| 1.01-2.0   | 53        | 87     | 6.48%   |
| 3.01-4.0   | 30        | 63     | 3.67%   |
| 4.01-10.0  | 20        | 56     | 2.44%   |
| 2.01-3.0   | 17        | 22     | 2.08%   |
| 10.01-20.0 | 5         | 10     | 0.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 205       | 20.4%   |
| 101-250        | 203       | 20.2%   |
| 251-500        | 198       | 19.7%   |
| 501-1000       | 125       | 12.44%  |
| 1001-2000      | 76        | 7.56%   |
| More than 3000 | 57        | 5.67%   |
| 1-20           | 44        | 4.38%   |
| 51-100         | 40        | 3.98%   |
| 21-50          | 35        | 3.48%   |
| 2001-3000      | 22        | 2.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 316       | 31.26%  |
| Unknown        | 205       | 20.28%  |
| 101-250        | 122       | 12.07%  |
| 21-50          | 115       | 11.37%  |
| 51-100         | 86        | 8.51%   |
| 251-500        | 58        | 5.74%   |
| 501-1000       | 47        | 4.65%   |
| 1001-2000      | 38        | 3.76%   |
| More than 3000 | 17        | 1.68%   |
| 2001-3000      | 7         | 0.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB          | 12        | 12     | 9.09%   |
| WDC WD3200AAJS-00L7A0 320GB           | 3         | 3      | 2.27%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 3         | 3      | 2.27%   |
| Seagate ST9500325AS 500GB             | 3         | 3      | 2.27%   |
| Seagate ST3250410AS 250GB             | 3         | 3      | 2.27%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 2         | 2      | 1.52%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 2      | 1.52%   |
| Seagate ST2000DX001-1CM164 2TB        | 2         | 3      | 1.52%   |
| Maxtor STM3160815AS 160GB             | 2         | 2      | 1.52%   |
| LITEON CV8-8E128-HP 128GB SSD         | 2         | 2      | 1.52%   |
| Kingston SA400S37240G 240GB SSD       | 2         | 2      | 1.52%   |
| Hitachi HDS721050CLA362 500GB         | 2         | 3      | 1.52%   |
| ZHITAI TiPlus5000 512GB               | 1         | 1      | 0.76%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 2      | 0.76%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.76%   |
| WDC WD80EMAZ-00WJTA0 8TB              | 1         | 11     | 0.76%   |
| WDC WD800AAJS-60WAA0 80GB             | 1         | 1      | 0.76%   |
| WDC WD7500BPKX-80HPJT0 752GB          | 1         | 1      | 0.76%   |
| WDC WD5000LPVT-08G33T1 500GB          | 1         | 1      | 0.76%   |
| WDC WD5000AAKX-08U6AA0 500GB          | 1         | 1      | 0.76%   |
| WDC WD40EFRX-68N32N0 4TB              | 1         | 3      | 0.76%   |
| WDC WD400UE-22HCT0 40GB               | 1         | 1      | 0.76%   |
| WDC WD400BD-60LRA0 40GB               | 1         | 1      | 0.76%   |
| WDC WD400BB-75CAA0 40GB               | 1         | 1      | 0.76%   |
| WDC WD3200BPVT-80ZEST0 320GB          | 1         | 1      | 0.76%   |
| WDC WD3200BEVT-00A0RT0 320GB          | 1         | 1      | 0.76%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1         | 1      | 0.76%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1         | 1      | 0.76%   |
| WDC WD2500AAKX-001CA0 250GB           | 1         | 1      | 0.76%   |
| WDC WD2500AAKS-00VSA0 250GB           | 1         | 2      | 0.76%   |
| WDC WD2500AAJS-00YZCA0 250GB          | 1         | 1      | 0.76%   |
| WDC WD2500AAJS-00B4A0 250GB           | 1         | 1      | 0.76%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 1      | 0.76%   |
| WDC WD1600YS-18SHB2 160GB             | 1         | 1      | 0.76%   |
| WDC WD1600AAJS-00B4A0 160GB           | 1         | 1      | 0.76%   |
| WDC WD10JPVX-08JC3T5 1TB              | 1         | 1      | 0.76%   |
| WDC WD10EZEX-00WN4A0 1TB              | 1         | 1      | 0.76%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1         | 1      | 0.76%   |
| WDC WD10EARS-00MVWB0 1TB              | 1         | 1      | 0.76%   |
| WDC WD10EALX-009BA0 1TB               | 1         | 1      | 0.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 44        | 59     | 33.85%  |
| Seagate             | 22        | 25     | 16.92%  |
| Hitachi             | 9         | 10     | 6.92%   |
| SK hynix            | 8         | 8      | 6.15%   |
| Samsung Electronics | 7         | 7      | 5.38%   |
| Toshiba             | 6         | 6      | 4.62%   |
| HGST                | 6         | 6      | 4.62%   |
| SanDisk             | 4         | 4      | 3.08%   |
| Kingston            | 4         | 4      | 3.08%   |
| Crucial             | 4         | 4      | 3.08%   |
| Intel               | 3         | 3      | 2.31%   |
| Maxtor              | 2         | 2      | 1.54%   |
| LITEON              | 2         | 2      | 1.54%   |
| A-DATA Technology   | 2         | 2      | 1.54%   |
| ZHITAI              | 1         | 1      | 0.77%   |
| SSSTC               | 1         | 1      | 0.77%   |
| ShiJi               | 1         | 3      | 0.77%   |
| Mushkin             | 1         | 1      | 0.77%   |
| Micron Technology   | 1         | 1      | 0.77%   |
| KingSpec            | 1         | 1      | 0.77%   |
| JMicron Technology  | 1         | 1      | 0.77%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 41        | 55     | 46.07%  |
| Seagate             | 22        | 25     | 24.72%  |
| Hitachi             | 9         | 10     | 10.11%  |
| Toshiba             | 6         | 6      | 6.74%   |
| HGST                | 6         | 6      | 6.74%   |
| Samsung Electronics | 2         | 2      | 2.25%   |
| Maxtor              | 2         | 2      | 2.25%   |
| JMicron Technology  | 1         | 1      | 1.12%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 83        | 107    | 66.94%  |
| SSD  | 30        | 31     | 24.19%  |
| NVMe | 11        | 13     | 8.87%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Seagate ST31000528AS 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 684       | 1113   | 62.58%  |
| Detected | 285       | 500    | 26.08%  |
| Malfunc  | 122       | 151    | 11.16%  |
| Failed   | 1         | 1      | 0.09%   |
| Limited  | 1         | 1      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 576       | 44.17%  |
| AMD                            | 192       | 14.72%  |
| Samsung Electronics            | 153       | 11.73%  |
| SanDisk                        | 77        | 5.9%    |
| SK hynix                       | 35        | 2.68%   |
| Kingston Technology Company    | 30        | 2.3%    |
| Micron Technology              | 25        | 1.92%   |
| Phison Electronics             | 24        | 1.84%   |
| ASMedia Technology             | 24        | 1.84%   |
| Toshiba America Info Systems   | 19        | 1.46%   |
| ADATA Technology               | 17        | 1.3%    |
| Nvidia                         | 16        | 1.23%   |
| Micron/Crucial Technology      | 16        | 1.23%   |
| KIOXIA                         | 14        | 1.07%   |
| JMicron Technology             | 12        | 0.92%   |
| Silicon Motion                 | 10        | 0.77%   |
| Marvell Technology Group       | 10        | 0.77%   |
| Solid State Storage Technology | 7         | 0.54%   |
| Yangtze Memory Technologies    | 5         | 0.38%   |
| LSI Logic / Symbios Logic      | 4         | 0.31%   |
| Broadcom / LSI                 | 4         | 0.31%   |
| Adaptec                        | 4         | 0.31%   |
| MAXIO Technology (Hangzhou)    | 3         | 0.23%   |
| Biwin Storage Technology       | 3         | 0.23%   |
| VIA Technologies               | 2         | 0.15%   |
| Transcend                      | 2         | 0.15%   |
| Silicon Image                  | 2         | 0.15%   |
| Seagate Technology             | 2         | 0.15%   |
| Lite-On Technology             | 2         | 0.15%   |
| Apple                          | 2         | 0.15%   |
| Union Memory (Shenzhen)        | 1         | 0.08%   |
| Shenzhen Longsys Electronics   | 1         | 0.08%   |
| Realtek Semiconductor          | 1         | 0.08%   |
| Radian Memory Systems          | 1         | 0.08%   |
| Netac Technology               | 1         | 0.08%   |
| Loongson Technology            | 1         | 0.08%   |
| Jiangsu Huacun Elec.           | 1         | 0.08%   |
| INNOGRIT                       | 1         | 0.08%   |
| IBM                            | 1         | 0.08%   |
| HighPoint Technologies         | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 138       | 9.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 62        | 4.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 59        | 3.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 47        | 3.18%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 43        | 2.91%   |
| Intel Comet Lake SATA AHCI Controller                                          | 38        | 2.57%   |
| AMD 400 Series Chipset SATA Controller                                         | 36        | 2.43%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 34        | 2.3%    |
| Intel Volume Management Device NVMe RAID Controller                            | 31        | 2.09%   |
| Samsung NVMe SSD Controller 980                                                | 28        | 1.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 26        | 1.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 24        | 1.62%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 24        | 1.62%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 23        | 1.55%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 22        | 1.49%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 19        | 1.28%   |
| Intel Tiger Lake-LP SATA Controller                                            | 19        | 1.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 19        | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 19        | 1.28%   |
| AMD 500 Series Chipset SATA Controller                                         | 19        | 1.28%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 18        | 1.22%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 16        | 1.08%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 14        | 0.95%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 14        | 0.95%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 14        | 0.95%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 13        | 0.88%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 12        | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 11        | 0.74%   |
| Kingston Company Company Non-Volatile memory controller                        | 11        | 0.74%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 11        | 0.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 11        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 11        | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 11        | 0.74%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 9         | 0.61%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 9         | 0.61%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 9         | 0.61%   |
| Intel 82Q963/Q965 PT IDER Controller                                           | 9         | 0.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 0.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 9         | 0.61%   |
| AMD 300 Series Chipset SATA Controller                                         | 9         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 689       | 53.12%  |
| NVMe | 432       | 33.31%  |
| IDE  | 102       | 7.86%   |
| RAID | 66        | 5.09%   |
| SAS  | 6         | 0.46%   |
| SCSI | 2         | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 712       | 71.56%  |
| AMD               | 262       | 26.33%  |
| ARM               | 10        | 1.01%   |
| sifive,u74-mc     | 4         | 0.4%    |
| Qualcomm          | 2         | 0.2%    |
| Unknown           | 2         | 0.2%    |
| Loongson          | 1         | 0.1%    |
| CHRP IBM,8233-E8B | 1         | 0.1%    |
| CentaurHauls      | 1         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i3-9100 CPU @ 3.60GHz              | 29        | 2.91%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 24        | 2.41%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 21        | 2.11%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 16        | 1.61%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 13        | 1.31%   |
| Intel Core 2 CPU 6400 @ 2.13GHz               | 12        | 1.2%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 12        | 1.2%    |
| Intel 12th Gen Core i5-1235U                  | 11        | 1.1%    |
| Intel Core i3-4130 CPU @ 3.40GHz              | 10        | 1%      |
| Intel Celeron N4020 CPU @ 1.10GHz             | 10        | 1%      |
| AMD Ryzen 5 3350G with Radeon Vega Graphics   | 10        | 1%      |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 9         | 0.9%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 8         | 0.8%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 0.8%    |
| Intel 12th Gen Core i7-12700H                 | 8         | 0.8%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 0.8%    |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 7         | 0.7%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 0.7%    |
| Intel Core i5-5250U CPU @ 1.60GHz             | 7         | 0.7%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 7         | 0.7%    |
| AMD Ryzen 5 5600H with Radeon Graphics        | 7         | 0.7%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 6         | 0.6%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 0.6%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 6         | 0.6%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 6         | 0.6%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 6         | 0.6%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 6         | 0.6%    |
| AMD Ryzen 5 5600X 6-Core Processor            | 6         | 0.6%    |
| Intel Pentium CPU G4400 @ 3.30GHz             | 5         | 0.5%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 0.5%    |
| Intel Core i7-7600U CPU @ 2.80GHz             | 5         | 0.5%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 5         | 0.5%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 0.5%    |
| Intel Core i5-9400 CPU @ 2.90GHz              | 5         | 0.5%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 5         | 0.5%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.5%    |
| Intel 12th Gen Core i7-1260P                  | 5         | 0.5%    |
| Intel 12th Gen Core i7-1255U                  | 5         | 0.5%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 5         | 0.5%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 5         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Other                   | 161       | 16.16%  |
| Intel Core i5           | 152       | 15.26%  |
| Intel Core i7           | 137       | 13.76%  |
| Intel Core i3           | 77        | 7.73%   |
| AMD Ryzen 5             | 73        | 7.33%   |
| AMD Ryzen 7             | 68        | 6.83%   |
| Intel Pentium           | 50        | 5.02%   |
| Intel Celeron           | 42        | 4.22%   |
| Intel Core 2 Duo        | 34        | 3.41%   |
| Intel Xeon              | 26        | 2.61%   |
| AMD Ryzen 9             | 26        | 2.61%   |
| AMD Ryzen 3             | 16        | 1.61%   |
| Intel Core 2            | 15        | 1.51%   |
| Intel Pentium Dual-Core | 14        | 1.41%   |
| AMD Ryzen 5 PRO         | 11        | 1.1%    |
| AMD FX                  | 8         | 0.8%    |
| AMD E                   | 8         | 0.8%    |
| AMD Ryzen 7 PRO         | 7         | 0.7%    |
| Intel Atom              | 5         | 0.5%    |
| Intel Pentium Silver    | 4         | 0.4%    |
| Intel Core 2 Quad       | 4         | 0.4%    |
| AMD Athlon 64 X2        | 4         | 0.4%    |
| AMD A6                  | 4         | 0.4%    |
| Intel Core i9           | 3         | 0.3%    |
| AMD Athlon              | 3         | 0.3%    |
| Intel Pentium M         | 2         | 0.2%    |
| Intel Pentium Gold      | 2         | 0.2%    |
| Intel Pentium 4         | 2         | 0.2%    |
| ARM Allwinner           | 2         | 0.2%    |
| AMD Ryzen 3 PRO         | 2         | 0.2%    |
| AMD Phenom II X4        | 2         | 0.2%    |
| AMD GX                  | 2         | 0.2%    |
| AMD EPYC                | 2         | 0.2%    |
| AMD E2                  | 2         | 0.2%    |
| AMD Athlon II X4        | 2         | 0.2%    |
| AMD Athlon II X3        | 2         | 0.2%    |
| AMD Athlon II           | 2         | 0.2%    |
| AMD A4                  | 2         | 0.2%    |
| Intel Xeon Silver       | 1         | 0.1%    |
| Intel Pentium D         | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 339       | 34.07%  |
| 4       | 324       | 32.56%  |
| 8       | 113       | 11.36%  |
| 6       | 100       | 10.05%  |
| 12      | 32        | 3.22%   |
| 10      | 25        | 2.51%   |
| 14      | 16        | 1.61%   |
| 16      | 15        | 1.51%   |
| 1       | 15        | 1.51%   |
| Unknown | 7         | 0.7%    |
| 3       | 4         | 0.4%    |
| 24      | 3         | 0.3%    |
| 22      | 1         | 0.1%    |
| 20      | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 978       | 98.29%  |
| 2       | 10        | 1.01%   |
| Unknown | 7         | 0.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 673       | 67.5%   |
| 1       | 316       | 31.7%   |
| Unknown | 7         | 0.7%    |
| 4       | 1         | 0.1%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 977       | 98.19%  |
| Unknown        | 11        | 1.11%   |
| 32-bit         | 5         | 0.5%    |
| 64-bit         | 2         | 0.2%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 275       | 27.47%  |
| 0x306c3    | 59        | 5.89%   |
| 0x806c1    | 42        | 4.2%    |
| 0x1067a    | 33        | 3.3%    |
| 0x906eb    | 30        | 3%      |
| 0x08108109 | 27        | 2.7%    |
| 0xa0655    | 22        | 2.2%    |
| 0x906a4    | 21        | 2.1%    |
| 0x906a3    | 21        | 2.1%    |
| 0x306a9    | 20        | 2%      |
| 0x206a7    | 19        | 1.9%    |
| 0x806e9    | 18        | 1.8%    |
| 0x806ea    | 17        | 1.7%    |
| 0x0a50000d | 17        | 1.7%    |
| 0x506e3    | 16        | 1.6%    |
| 0x806ec    | 15        | 1.5%    |
| 0x40651    | 15        | 1.5%    |
| 0x0a50000c | 14        | 1.4%    |
| 0x906ea    | 12        | 1.2%    |
| 0x906e9    | 12        | 1.2%    |
| 0x6f2      | 12        | 1.2%    |
| 0x306d4    | 12        | 1.2%    |
| 0x20655    | 12        | 1.2%    |
| 0x08608103 | 12        | 1.2%    |
| 0x406e3    | 11        | 1.1%    |
| 0x706a8    | 10        | 1%      |
| 0x0a601203 | 10        | 1%      |
| 0x08600106 | 10        | 1%      |
| 0x90672    | 8         | 0.8%    |
| 0x0a20120a | 8         | 0.8%    |
| 0x10676    | 7         | 0.7%    |
| 0x30678    | 6         | 0.6%    |
| 0x0a404102 | 6         | 0.6%    |
| 0x08701021 | 6         | 0.6%    |
| 0x906c0    | 5         | 0.5%    |
| 0x08101016 | 5         | 0.5%    |
| 0x0810100b | 5         | 0.5%    |
| 0x0800820d | 5         | 0.5%    |
| 0xb0671    | 4         | 0.4%    |
| 0x806d1    | 4         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 154       | 15.46%  |
| Haswell          | 93        | 9.34%   |
| Unknown          | 85        | 8.53%   |
| Zen 3            | 65        | 6.53%   |
| Alderlake Hybrid | 59        | 5.92%   |
| TigerLake        | 55        | 5.52%   |
| Penryn           | 50        | 5.02%   |
| Skylake          | 48        | 4.82%   |
| Zen+             | 44        | 4.42%   |
| Zen 2            | 39        | 3.92%   |
| IvyBridge        | 38        | 3.82%   |
| CometLake        | 37        | 3.71%   |
| SandyBridge      | 29        | 2.91%   |
| Westmere         | 24        | 2.41%   |
| Core             | 24        | 2.41%   |
| Zen              | 18        | 1.81%   |
| Broadwell        | 18        | 1.81%   |
| Goldmont plus    | 17        | 1.71%   |
| Silvermont       | 13        | 1.31%   |
| Bobcat           | 12        | 1.2%    |
| K10              | 11        | 1.1%    |
| Excavator        | 9         | 0.9%    |
| IceLake          | 8         | 0.8%    |
| Tremont          | 7         | 0.7%    |
| Piledriver       | 7         | 0.7%    |
| Nehalem          | 7         | 0.7%    |
| K8 Hammer        | 4         | 0.4%    |
| Goldmont         | 4         | 0.4%    |
| P6               | 3         | 0.3%    |
| NetBurst         | 3         | 0.3%    |
| Jaguar           | 3         | 0.3%    |
| K10 Llano        | 2         | 0.2%    |
| Bonnell          | 2         | 0.2%    |
| Steamroller      | 1         | 0.1%    |
| Puma             | 1         | 0.1%    |
| Gracemont        | 1         | 0.1%    |
| Bulldozer        | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 554       | 49.55%  |
| AMD                        | 283       | 25.31%  |
| Nvidia                     | 262       | 23.43%  |
| Matrox Electronics Systems | 12        | 1.07%   |
| ASPEED Technology          | 5         | 0.45%   |
| Zhaoxin                    | 1         | 0.09%   |
| Loongson Technology        | 1         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 50        | 4.38%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 38        | 3.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 38        | 3.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 31        | 2.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 29        | 2.54%   |
| Intel UHD Graphics 620                                                      | 25        | 2.19%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 25        | 2.19%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 22        | 1.93%   |
| AMD Lucienne                                                                | 22        | 1.93%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 21        | 1.84%   |
| Intel HD Graphics 620                                                       | 21        | 1.84%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 20        | 1.75%   |
| AMD Renoir                                                                  | 20        | 1.75%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 19        | 1.66%   |
| Nvidia GF108 [GeForce GT 730]                                               | 18        | 1.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 18        | 1.58%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 18        | 1.58%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 17        | 1.49%   |
| Intel Core Processor Integrated Graphics Controller                         | 15        | 1.31%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 14        | 1.23%   |
| Intel HD Graphics 630                                                       | 13        | 1.14%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 13        | 1.14%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 13        | 1.14%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 13        | 1.14%   |
| AMD Barcelo                                                                 | 13        | 1.14%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 12        | 1.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 11        | 0.96%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 11        | 0.96%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 11        | 0.96%   |
| Intel HD Graphics 530                                                       | 10        | 0.88%   |
| AMD Rembrandt [Radeon 680M]                                                 | 10        | 0.88%   |
| AMD Raphael                                                                 | 10        | 0.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 9         | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 9         | 0.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 8         | 0.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 7         | 0.61%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 7         | 0.61%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 7         | 0.61%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 7         | 0.61%   |
| Intel HD Graphics 6000                                                      | 7         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 428       | 42.93%  |
| 1 x AMD                 | 224       | 22.47%  |
| 1 x Nvidia              | 144       | 14.44%  |
| Intel + Nvidia          | 95        | 9.53%   |
| AMD + Nvidia            | 22        | 2.21%   |
| Other                   | 20        | 2.01%   |
| 2 x AMD                 | 17        | 1.71%   |
| Intel + AMD             | 17        | 1.71%   |
| 1 x Matrox              | 12        | 1.2%    |
| 2 x Intel               | 9         | 0.9%    |
| 1 x ASPEED              | 4         | 0.4%    |
| 2 x Nvidia              | 1         | 0.1%    |
| 1 x Zhaoxin             | 1         | 0.1%    |
| 1 x Loongson Technology | 1         | 0.1%    |
| AMD + Matrox            | 1         | 0.1%    |
| AMD + ASPEED            | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 698       | 70.01%  |
| Unknown     | 206       | 20.66%  |
| Proprietary | 93        | 9.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 728       | 72.87%  |
| 0.01-0.5   | 79        | 7.91%   |
| 1.01-2.0   | 49        | 4.9%    |
| 3.01-4.0   | 44        | 4.4%    |
| 7.01-8.0   | 36        | 3.6%    |
| 0.51-1.0   | 32        | 3.2%    |
| 5.01-6.0   | 9         | 0.9%    |
| 8.01-16.0  | 8         | 0.8%    |
| 2.01-3.0   | 6         | 0.6%    |
| 16.01-24.0 | 6         | 0.6%    |
| 4.01-5.0   | 1         | 0.1%    |
| 0          | 1         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 115       | 12.76%  |
| Samsung Electronics     | 93        | 10.32%  |
| BOE                     | 82        | 9.1%    |
| Chimei Innolux          | 77        | 8.55%   |
| LG Display              | 64        | 7.1%    |
| Dell                    | 50        | 5.55%   |
| Goldstar                | 35        | 3.88%   |
| Hewlett-Packard         | 33        | 3.66%   |
| BenQ                    | 28        | 3.11%   |
| Ancor Communications    | 28        | 3.11%   |
| Lenovo                  | 25        | 2.77%   |
| Apple                   | 23        | 2.55%   |
| Acer                    | 23        | 2.55%   |
| Sharp                   | 22        | 2.44%   |
| Philips                 | 18        | 2%      |
| PANDA                   | 17        | 1.89%   |
| AOC                     | 17        | 1.89%   |
| InfoVision              | 15        | 1.66%   |
| Iiyama                  | 10        | 1.11%   |
| ASUSTek Computer        | 9         | 1%      |
| ViewSonic               | 6         | 0.67%   |
| Sony                    | 6         | 0.67%   |
| Sceptre Tech            | 6         | 0.67%   |
| Chi Mei Optoelectronics | 6         | 0.67%   |
| Unknown                 | 6         | 0.67%   |
| LG Electronics          | 5         | 0.55%   |
| CSO                     | 5         | 0.55%   |
| Mi                      | 4         | 0.44%   |
| LG Philips              | 4         | 0.44%   |
| HKC                     | 4         | 0.44%   |
| RTK                     | 3         | 0.33%   |
| Vizio                   | 2         | 0.22%   |
| Unknown                 | 2         | 0.22%   |
| Toshiba                 | 2         | 0.22%   |
| SAC                     | 2         | 0.22%   |
| Panasonic               | 2         | 0.22%   |
| NEC Computers           | 2         | 0.22%   |
| MStar                   | 2         | 0.22%   |
| MSI                     | 2         | 0.22%   |
| MiTAC                   | 2         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Ancor Communications ASUS VS229 ACI22D3 1920x1080 475x267mm 21.5-inch | 15        | 1.62%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 10        | 1.08%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 6         | 0.65%   |
| Unknown                                                               | 6         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 5         | 0.54%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.43%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 4         | 0.43%   |
| AU Optronics LCD Monitor AUO592D 1920x1080 293x165mm 13.2-inch        | 4         | 0.43%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch               | 3         | 0.32%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 3         | 0.32%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 3         | 0.32%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3         | 0.32%   |
| Mi Redmi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                | 3         | 0.32%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 3         | 0.32%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 3         | 0.32%   |
| Hewlett-Packard 23xi HWP3032 1920x1080 510x290mm 23.1-inch            | 3         | 0.32%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 3         | 0.32%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 3         | 0.32%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN13C6 1920x1200 286x178mm 13.3-inch      | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 3         | 0.32%   |
| BenQ PD2700U BNQ802E 3840x2160 597x336mm 27.0-inch                    | 3         | 0.32%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 3         | 0.32%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 0.32%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.32%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 3         | 0.32%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.32%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 3         | 0.32%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 3         | 0.32%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 3         | 0.32%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                | 3         | 0.32%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 3         | 0.32%   |
| ViewSonic VA2446 SERIES VSC732E 1920x1080 521x293mm 23.5-inch         | 2         | 0.22%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 2         | 0.22%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 0.22%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 211x141mm 10.0-inch               | 2         | 0.22%   |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch               | 2         | 0.22%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 2         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 425       | 49.42%  |
| 1366x768 (WXGA)    | 105       | 12.21%  |
| 3840x2160 (4K)     | 57        | 6.63%   |
| 2560x1440 (QHD)    | 48        | 5.58%   |
| 1920x1200 (WUXGA)  | 35        | 4.07%   |
| 1600x900 (HD+)     | 33        | 3.84%   |
| 1440x900 (WXGA+)   | 14        | 1.63%   |
| Unknown            | 14        | 1.63%   |
| 1680x1050 (WSXGA+) | 12        | 1.4%    |
| 1280x800 (WXGA)    | 12        | 1.4%    |
| 1280x1024 (SXGA)   | 12        | 1.4%    |
| 2560x1600          | 10        | 1.16%   |
| 3840x2400          | 9         | 1.05%   |
| 3440x1440          | 8         | 0.93%   |
| 2880x1800          | 8         | 0.93%   |
| 2560x1080          | 5         | 0.58%   |
| 3000x2000          | 4         | 0.47%   |
| 1360x768           | 4         | 0.47%   |
| 4480x1440          | 3         | 0.35%   |
| 3840x1600          | 3         | 0.35%   |
| 1920x540           | 3         | 0.35%   |
| 7680x2160          | 2         | 0.23%   |
| 3840x1200          | 2         | 0.23%   |
| 3456x2160          | 2         | 0.23%   |
| 2736x1824          | 2         | 0.23%   |
| 2288x1287          | 2         | 0.23%   |
| 2160x1440          | 2         | 0.23%   |
| 1920x1280          | 2         | 0.23%   |
| 1800x1200          | 2         | 0.23%   |
| 800x1280           | 1         | 0.12%   |
| 7280x2160          | 1         | 0.12%   |
| 6400x2160          | 1         | 0.12%   |
| 6400x1440          | 1         | 0.12%   |
| 5760x2160          | 1         | 0.12%   |
| 3840x1100          | 1         | 0.12%   |
| 3840x1080          | 1         | 0.12%   |
| 3286x1080          | 1         | 0.12%   |
| 3200x1800 (QHD+)   | 1         | 0.12%   |
| 3072x1920          | 1         | 0.12%   |
| 2966x900           | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 193       | 21.64%  |
| 13      | 129       | 14.46%  |
| 14      | 86        | 9.64%   |
| 24      | 75        | 8.41%   |
| 27      | 71        | 7.96%   |
| 21      | 60        | 6.73%   |
| 23      | 48        | 5.38%   |
| Unknown | 36        | 4.04%   |
| 17      | 31        | 3.48%   |
| 31      | 18        | 2.02%   |
| 12      | 17        | 1.91%   |
| 11      | 16        | 1.79%   |
| 34      | 13        | 1.46%   |
| 16      | 13        | 1.46%   |
| 20      | 11        | 1.23%   |
| 19      | 11        | 1.23%   |
| 18      | 10        | 1.12%   |
| 22      | 8         | 0.9%    |
| 32      | 6         | 0.67%   |
| 72      | 4         | 0.45%   |
| 40      | 4         | 0.45%   |
| 26      | 4         | 0.45%   |
| 84      | 3         | 0.34%   |
| 52      | 3         | 0.34%   |
| 10      | 3         | 0.34%   |
| 142     | 2         | 0.22%   |
| 48      | 2         | 0.22%   |
| 46      | 2         | 0.22%   |
| 37      | 2         | 0.22%   |
| 85      | 1         | 0.11%   |
| 75      | 1         | 0.11%   |
| 67      | 1         | 0.11%   |
| 54      | 1         | 0.11%   |
| 49      | 1         | 0.11%   |
| 43      | 1         | 0.11%   |
| 39      | 1         | 0.11%   |
| 38      | 1         | 0.11%   |
| 28      | 1         | 0.11%   |
| 8       | 1         | 0.11%   |
| 7       | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 342       | 38.86%  |
| 501-600        | 184       | 20.91%  |
| 201-300        | 111       | 12.61%  |
| 401-500        | 93        | 10.57%  |
| 351-400        | 40        | 4.55%   |
| Unknown        | 36        | 4.09%   |
| 601-700        | 23        | 2.61%   |
| 701-800        | 20        | 2.27%   |
| 1501-2000      | 9         | 1.02%   |
| 1001-1500      | 9         | 1.02%   |
| 801-900        | 8         | 0.91%   |
| More than 2000 | 2         | 0.23%   |
| 101-200        | 1         | 0.11%   |
| 901-1000       | 1         | 0.11%   |
| 1-100          | 1         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 608       | 76%     |
| 16/10   | 108       | 13.5%   |
| Unknown | 30        | 3.75%   |
| 21/9    | 15        | 1.88%   |
| 3/2     | 14        | 1.75%   |
| 5/4     | 11        | 1.38%   |
| 4/3     | 6         | 0.75%   |
| 32/9    | 2         | 0.25%   |
| 1.00    | 2         | 0.25%   |
| 3.40    | 1         | 0.13%   |
| 0.67    | 1         | 0.13%   |
| 0.58    | 1         | 0.13%   |
| 0.45    | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 192       | 21.52%  |
| 81-90          | 154       | 17.26%  |
| 201-250        | 149       | 16.7%   |
| 301-350        | 74        | 8.3%    |
| 71-80          | 58        | 6.5%    |
| 351-500        | 38        | 4.26%   |
| Unknown        | 36        | 4.04%   |
| 151-200        | 35        | 3.92%   |
| 251-300        | 31        | 3.48%   |
| 121-130        | 24        | 2.69%   |
| More than 1000 | 19        | 2.13%   |
| 51-60          | 17        | 1.91%   |
| 61-70          | 16        | 1.79%   |
| 111-120        | 15        | 1.68%   |
| 141-150        | 13        | 1.46%   |
| 501-1000       | 11        | 1.23%   |
| 41-50          | 3         | 0.34%   |
| 131-140        | 3         | 0.34%   |
| 1-40           | 2         | 0.22%   |
| 91-100         | 2         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 294       | 33.87%  |
| 51-100        | 223       | 25.69%  |
| 101-120       | 177       | 20.39%  |
| 161-240       | 94        | 10.83%  |
| Unknown       | 36        | 4.15%   |
| More than 240 | 29        | 3.34%   |
| 1-50          | 15        | 1.73%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 633       | 63.11%  |
| 0     | 218       | 21.73%  |
| 2     | 135       | 13.46%  |
| 3     | 17        | 1.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 561       | 38.82%  |
| Intel                             | 497       | 34.39%  |
| Qualcomm Atheros                  | 97        | 6.71%   |
| Broadcom                          | 59        | 4.08%   |
| MediaTek                          | 43        | 2.98%   |
| ASIX Electronics                  | 20        | 1.38%   |
| Broadcom Limited                  | 18        | 1.25%   |
| Nvidia                            | 15        | 1.04%   |
| Qualcomm                          | 13        | 0.9%    |
| TP-Link                           | 12        | 0.83%   |
| Ralink Technology                 | 12        | 0.83%   |
| Marvell Technology Group          | 12        | 0.83%   |
| Aquantia                          | 7         | 0.48%   |
| Sierra Wireless                   | 6         | 0.42%   |
| Xiaomi                            | 5         | 0.35%   |
| D-Link                            | 4         | 0.28%   |
| ASUSTek Computer                  | 4         | 0.28%   |
| Ralink                            | 3         | 0.21%   |
| NetGear                           | 3         | 0.21%   |
| Mellanox Technologies             | 3         | 0.21%   |
| Google                            | 3         | 0.21%   |
| DisplayLink                       | 3         | 0.21%   |
| Qualcomm Atheros Communications   | 2         | 0.14%   |
| Microsoft                         | 2         | 0.14%   |
| Lenovo                            | 2         | 0.14%   |
| Ericsson Business Mobile Networks | 2         | 0.14%   |
| Emulex                            | 2         | 0.14%   |
| Dell                              | 2         | 0.14%   |
| American Megatrends               | 2         | 0.14%   |
| 3Com                              | 2         | 0.14%   |
| Wacom                             | 1         | 0.07%   |
| U-Blox                            | 1         | 0.07%   |
| SysKonnect                        | 1         | 0.07%   |
| Spreadtrum Communications         | 1         | 0.07%   |
| Solarflare Communications         | 1         | 0.07%   |
| Samsung Electronics               | 1         | 0.07%   |
| Raspberry Pi                      | 1         | 0.07%   |
| QinHeng Electronics               | 1         | 0.07%   |
| OPPO Electronics                  | 1         | 0.07%   |
| OpenMoko                          | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 383       | 22.57%  |
| Intel Wi-Fi 6 AX200                                               | 49        | 2.89%   |
| Intel Wireless 8265 / 8275                                        | 45        | 2.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 42        | 2.47%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 40        | 2.36%   |
| Intel Wi-Fi 6 AX201                                               | 39        | 2.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 37        | 2.18%   |
| Realtek RTL8125 2.5GbE Controller                                 | 36        | 2.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 33        | 1.94%   |
| Intel Ethernet Controller I225-V                                  | 22        | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 21        | 1.24%   |
| Intel Wireless 7260                                               | 21        | 1.24%   |
| Intel Ethernet Connection (4) I219-LM                             | 20        | 1.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 19        | 1.12%   |
| Intel I211 Gigabit Network Connection                             | 18        | 1.06%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 17        | 1%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 17        | 1%      |
| Realtek RTL8152 Fast Ethernet Adapter                             | 17        | 1%      |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 17        | 1%      |
| ASIX AX88179 Gigabit Ethernet                                     | 17        | 1%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 16        | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 16        | 0.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 16        | 0.94%   |
| Intel Wireless 8260                                               | 16        | 0.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 14        | 0.82%   |
| Intel Ethernet Connection I217-LM                                 | 14        | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 14        | 0.82%   |
| Intel Ethernet Connection (13) I219-V                             | 13        | 0.77%   |
| Intel 82566DM Gigabit Network Connection                          | 12        | 0.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 0.65%   |
| Intel Wireless 7265                                               | 11        | 0.65%   |
| Intel Ethernet Connection (2) I219-V                              | 10        | 0.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 10        | 0.59%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 9         | 0.53%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 9         | 0.53%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 9         | 0.53%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 9         | 0.53%   |
| Realtek 802.11ac NIC                                              | 8         | 0.47%   |
| Intel Wireless-AC 9260                                            | 8         | 0.47%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 389       | 52.21%  |
| Realtek Semiconductor             | 116       | 15.57%  |
| Qualcomm Atheros                  | 78        | 10.47%  |
| Broadcom                          | 42        | 5.64%   |
| MediaTek                          | 41        | 5.5%    |
| Broadcom Limited                  | 16        | 2.15%   |
| Ralink Technology                 | 12        | 1.61%   |
| TP-Link                           | 11        | 1.48%   |
| Qualcomm                          | 10        | 1.34%   |
| Sierra Wireless                   | 6         | 0.81%   |
| D-Link                            | 4         | 0.54%   |
| ASUSTek Computer                  | 4         | 0.54%   |
| Ralink                            | 3         | 0.4%    |
| NetGear                           | 3         | 0.4%    |
| Qualcomm Atheros Communications   | 2         | 0.27%   |
| Marvell Technology Group          | 2         | 0.27%   |
| Wacom                             | 1         | 0.13%   |
| Microsoft                         | 1         | 0.13%   |
| Linksys                           | 1         | 0.13%   |
| Fibocom                           | 1         | 0.13%   |
| Ericsson Business Mobile Networks | 1         | 0.13%   |
| Edimax Technology                 | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 49        | 6.52%   |
| Intel Wireless 8265 / 8275                                     | 45        | 5.99%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 40        | 5.33%   |
| Intel Wi-Fi 6 AX201                                            | 39        | 5.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 33        | 4.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 21        | 2.8%    |
| Intel Wireless 7260                                            | 21        | 2.8%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 17        | 2.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 17        | 2.26%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 17        | 2.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 16        | 2.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 16        | 2.13%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 16        | 2.13%   |
| Intel Wireless 8260                                            | 16        | 2.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 14        | 1.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 14        | 1.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 11        | 1.46%   |
| Intel Wireless 7265                                            | 11        | 1.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 10        | 1.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 9         | 1.2%    |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 9         | 1.2%    |
| Intel Gemini Lake PCH CNVi WiFi                                | 9         | 1.2%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 9         | 1.2%    |
| Realtek 802.11ac NIC                                           | 8         | 1.07%   |
| Intel Wireless-AC 9260                                         | 8         | 1.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 8         | 1.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 0.93%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 7         | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 0.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 6         | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 0.8%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 6         | 0.8%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 6         | 0.8%    |
| Intel Alder Lake-S PCH CNVi WiFi                               | 6         | 0.8%    |
| Intel 700 Series Chipset Family Wi-Fi                          | 6         | 0.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 6         | 0.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 0.67%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 5         | 0.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 0.67%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 5         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 514       | 56.42%  |
| Intel                     | 247       | 27.11%  |
| Qualcomm Atheros          | 28        | 3.07%   |
| Broadcom                  | 23        | 2.52%   |
| ASIX Electronics          | 20        | 2.2%    |
| Nvidia                    | 15        | 1.65%   |
| Marvell Technology Group  | 10        | 1.1%    |
| Aquantia                  | 7         | 0.77%   |
| Xiaomi                    | 5         | 0.55%   |
| Qualcomm                  | 3         | 0.33%   |
| Mellanox Technologies     | 3         | 0.33%   |
| Google                    | 3         | 0.33%   |
| DisplayLink               | 3         | 0.33%   |
| MediaTek                  | 2         | 0.22%   |
| Lenovo                    | 2         | 0.22%   |
| Emulex                    | 2         | 0.22%   |
| Broadcom Limited          | 2         | 0.22%   |
| American Megatrends       | 2         | 0.22%   |
| 3Com                      | 2         | 0.22%   |
| TP-Link                   | 1         | 0.11%   |
| SysKonnect                | 1         | 0.11%   |
| Spreadtrum Communications | 1         | 0.11%   |
| Solarflare Communications | 1         | 0.11%   |
| Samsung Electronics       | 1         | 0.11%   |
| OPPO Electronics          | 1         | 0.11%   |
| Motorola PCS              | 1         | 0.11%   |
| Microsoft                 | 1         | 0.11%   |
| Microchip Technology      | 1         | 0.11%   |
| Loongson Technology       | 1         | 0.11%   |
| JMicron Technology        | 1         | 0.11%   |
| IBM                       | 1         | 0.11%   |
| Huawei Technologies       | 1         | 0.11%   |
| Hewlett-Packard           | 1         | 0.11%   |
| D-Link System             | 1         | 0.11%   |
| Attansic Technology       | 1         | 0.11%   |
| Apple                     | 1         | 0.11%   |
| Accton Technology         | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 383       | 41.18%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 42        | 4.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 37        | 3.98%   |
| Realtek RTL8125 2.5GbE Controller                                   | 36        | 3.87%   |
| Intel Ethernet Controller I225-V                                    | 22        | 2.37%   |
| Intel Ethernet Connection (4) I219-LM                               | 20        | 2.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 19        | 2.04%   |
| Intel I211 Gigabit Network Connection                               | 18        | 1.94%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 17        | 1.83%   |
| ASIX AX88179 Gigabit Ethernet                                       | 17        | 1.83%   |
| Intel Ethernet Connection I217-LM                                   | 14        | 1.51%   |
| Intel Ethernet Connection (13) I219-V                               | 13        | 1.4%    |
| Intel 82566DM Gigabit Network Connection                            | 12        | 1.29%   |
| Intel Ethernet Connection (2) I219-V                                | 10        | 1.08%   |
| Intel Ethernet Connection I219-LM                                   | 8         | 0.86%   |
| Intel Ethernet Connection (4) I219-V                                | 8         | 0.86%   |
| Intel Ethernet Connection I218-LM                                   | 7         | 0.75%   |
| Intel Ethernet Connection I217-V                                    | 7         | 0.75%   |
| Intel Ethernet Connection (5) I219-LM                               | 6         | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                               | 6         | 0.65%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 5         | 0.54%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 5         | 0.54%   |
| Intel I210 Gigabit Network Connection                               | 5         | 0.54%   |
| Intel Ethernet Connection (16) I219-V                               | 5         | 0.54%   |
| Intel 82579V Gigabit Network Connection                             | 5         | 0.54%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                   | 5         | 0.54%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5         | 0.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 4         | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                            | 4         | 0.43%   |
| Nvidia MCP79 Ethernet                                               | 4         | 0.43%   |
| Nvidia MCP61 Ethernet                                               | 4         | 0.43%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 4         | 0.43%   |
| Intel Ethernet Connection I219-V                                    | 4         | 0.43%   |
| Intel 82577LM Gigabit Network Connection                            | 4         | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 3         | 0.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 3         | 0.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 3         | 0.32%   |
| Nvidia MCP65 Ethernet                                               | 3         | 0.32%   |
| Intel I350 Gigabit Network Connection                               | 3         | 0.32%   |
| Intel Ethernet Controller I226-V                                    | 3         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 829       | 53.62%  |
| WiFi     | 701       | 45.34%  |
| Modem    | 12        | 0.78%   |
| Unknown  | 4         | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 542       | 52.93%  |
| WiFi     | 482       | 47.07%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 479       | 48.04%  |
| 1     | 458       | 45.94%  |
| 3     | 23        | 2.31%   |
| 0     | 23        | 2.31%   |
| 4     | 9         | 0.9%    |
| 6     | 3         | 0.3%    |
| 9     | 1         | 0.1%    |
| 7     | 1         | 0.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 748       | 74.73%  |
| Yes  | 253       | 25.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 344       | 55.66%  |
| Realtek Semiconductor           | 69        | 11.17%  |
| Qualcomm Atheros Communications | 30        | 4.85%   |
| Foxconn / Hon Hai               | 27        | 4.37%   |
| Apple                           | 25        | 4.05%   |
| IMC Networks                    | 21        | 3.4%    |
| Cambridge Silicon Radio         | 18        | 2.91%   |
| Broadcom                        | 18        | 2.91%   |
| Lite-On Technology              | 17        | 2.75%   |
| ASUSTek Computer                | 9         | 1.46%   |
| Realtek                         | 8         | 1.29%   |
| MediaTek                        | 8         | 1.29%   |
| Dell                            | 5         | 0.81%   |
| Hewlett-Packard                 | 4         | 0.65%   |
| TP-Link                         | 2         | 0.32%   |
| Toshiba                         | 2         | 0.32%   |
| Micro Star International        | 2         | 0.32%   |
| USI                             | 1         | 0.16%   |
| Ralink Technology               | 1         | 0.16%   |
| Marvell Semiconductor           | 1         | 0.16%   |
| Integrated System Solution      | 1         | 0.16%   |
| HTC (High Tech Computer)        | 1         | 0.16%   |
| Fujitsu                         | 1         | 0.16%   |
| Foxconn International           | 1         | 0.16%   |
| Edimax Technology               | 1         | 0.16%   |
| Dynex                           | 1         | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 99        | 16.02%  |
| Intel AX201 Bluetooth                               | 68        | 11%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 63        | 10.19%  |
| Realtek Bluetooth Radio                             | 61        | 9.87%   |
| Intel AX200 Bluetooth                               | 45        | 7.28%   |
| Intel Bluetooth Device                              | 39        | 6.31%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 18        | 2.91%   |
| Qualcomm Atheros  Bluetooth Device                  | 17        | 2.75%   |
| Apple Bluetooth USB Host Controller                 | 14        | 2.27%   |
| Foxconn / Hon Hai Wireless_Device                   | 12        | 1.94%   |
| Foxconn / Hon Hai Bluetooth Device                  | 12        | 1.94%   |
| Intel AX210 Bluetooth                               | 11        | 1.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 9         | 1.46%   |
| IMC Networks Bluetooth Radio                        | 9         | 1.46%   |
| MediaTek Wireless_Device                            | 8         | 1.29%   |
| IMC Networks Wireless_Device                        | 8         | 1.29%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 1.13%   |
| Realtek 802.11ac WLAN Adapter                       | 7         | 1.13%   |
| Apple Bluetooth Host Controller                     | 7         | 1.13%   |
| Lite-On Wireless_Device                             | 6         | 0.97%   |
| Lite-On Bluetooth Device                            | 6         | 0.97%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 0.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 0.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 0.65%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 0.65%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 0.65%   |
| Dell BCM20702A0 Bluetooth Module                    | 4         | 0.65%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.49%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.49%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 3         | 0.49%   |
| ASUS ASUS USB-BT500                                 | 3         | 0.49%   |
| TP-Link UB500 Adapter                               | 2         | 0.32%   |
| Broadcom HP Portable SoftSailing                    | 2         | 0.32%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.32%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 0.32%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.32%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.32%   |
| Apple Bluetooth HCI                                 | 2         | 0.32%   |
| USI Bluetooth Device                                | 1         | 0.16%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 678       | 51.76%  |
| AMD                                          | 290       | 22.14%  |
| Nvidia                                       | 198       | 15.11%  |
| C-Media Electronics                          | 24        | 1.83%   |
| Logitech                                     | 14        | 1.07%   |
| Realtek Semiconductor                        | 8         | 0.61%   |
| Lenovo                                       | 8         | 0.61%   |
| Creative Labs                                | 7         | 0.53%   |
| ASUSTek Computer                             | 6         | 0.46%   |
| GN Netcom                                    | 5         | 0.38%   |
| Generalplus Technology                       | 5         | 0.38%   |
| Micro Star International                     | 4         | 0.31%   |
| Kingston Technology                          | 4         | 0.31%   |
| JMTek                                        | 4         | 0.31%   |
| Hewlett-Packard                              | 4         | 0.31%   |
| Focusrite-Novation                           | 4         | 0.31%   |
| Texas Instruments                            | 3         | 0.23%   |
| SteelSeries ApS                              | 3         | 0.23%   |
| Plantronics                                  | 3         | 0.23%   |
| Blue Microphones                             | 3         | 0.23%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.15%   |
| Samson Technologies                          | 2         | 0.15%   |
| Razer USA                                    | 2         | 0.15%   |
| Creative Technology                          | 2         | 0.15%   |
| CMX Systems                                  | 2         | 0.15%   |
| Audient                                      | 2         | 0.15%   |
| Zhaoxin                                      | 1         | 0.08%   |
| Yamaha                                       | 1         | 0.08%   |
| VIA Technologies                             | 1         | 0.08%   |
| USB MICROPHONE                               | 1         | 0.08%   |
| Tdlasunnic                                   | 1         | 0.08%   |
| Schiit Audio                                 | 1         | 0.08%   |
| OPPO Electronics                             | 1         | 0.08%   |
| Microsoft                                    | 1         | 0.08%   |
| Loongson Technology                          | 1         | 0.08%   |
| Jieli Technology                             | 1         | 0.08%   |
| Global Sun Technology                        | 1         | 0.08%   |
| Giga-Byte Technology                         | 1         | 0.08%   |
| FUXIN                                        | 1         | 0.08%   |
| Fujitsu                                      | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 156       | 9.67%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 82        | 5.08%   |
| Intel Sunrise Point-LP HD Audio                                            | 72        | 4.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 67        | 4.15%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 55        | 3.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 52        | 3.22%   |
| Intel Cannon Lake PCH cAVS                                                 | 47        | 2.91%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 44        | 2.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 38        | 2.36%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 36        | 2.23%   |
| AMD Starship/Matisse HD Audio Controller                                   | 34        | 2.11%   |
| Intel Comet Lake PCH cAVS                                                  | 30        | 1.86%   |
| Nvidia GF108 High Definition Audio Controller                              | 29        | 1.8%    |
| Nvidia TU106 High Definition Audio Controller                              | 27        | 1.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 24        | 1.49%   |
| Intel 200 Series PCH HD Audio                                              | 24        | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 23        | 1.43%   |
| Intel Haswell-ULT HD Audio Controller                                      | 21        | 1.3%    |
| Intel 8 Series HD Audio Controller                                         | 21        | 1.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 21        | 1.3%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 21        | 1.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 20        | 1.24%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 20        | 1.24%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 20        | 1.24%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 19        | 1.18%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 19        | 1.18%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 19        | 1.18%   |
| Intel Comet Lake PCH-LP cAVS                                               | 17        | 1.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 17        | 1.05%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 15        | 0.93%   |
| Intel Broadwell-U Audio Controller                                         | 15        | 0.93%   |
| Nvidia GP107GL High Definition Audio Controller                            | 14        | 0.87%   |
| Intel Alder Lake-S HD Audio Controller                                     | 12        | 0.74%   |
| AMD FCH Azalia Controller                                                  | 12        | 0.74%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 12        | 0.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 11        | 0.68%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 11        | 0.68%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 11        | 0.68%   |
| Nvidia GA104 High Definition Audio Controller                              | 10        | 0.62%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 10        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 185       | 20.67%  |
| SK hynix                                | 142       | 15.87%  |
| Kingston                                | 116       | 12.96%  |
| Crucial                                 | 95        | 10.61%  |
| Micron Technology                       | 88        | 9.83%   |
| Unknown                                 | 79        | 8.83%   |
| Corsair                                 | 26        | 2.91%   |
| G.Skill                                 | 25        | 2.79%   |
| A-DATA Technology                       | 20        | 2.23%   |
| Hikvision                               | 18        | 2.01%   |
| Elpida                                  | 15        | 1.68%   |
| Unknown (ABCD)                          | 9         | 1.01%   |
| Ramaxel Technology                      | 9         | 1.01%   |
| Patriot                                 | 8         | 0.89%   |
| Micro Memory Bank                       | 8         | 0.89%   |
| Unknown                                 | 8         | 0.89%   |
| Team                                    | 5         | 0.56%   |
| Nanya Technology                        | 4         | 0.45%   |
| Smart                                   | 3         | 0.34%   |
| ff                                      | 3         | 0.34%   |
| ASint Technology                        | 3         | 0.34%   |
| AMD                                     | 3         | 0.34%   |
| 4ea5                                    | 3         | 0.34%   |
| Transcend                               | 2         | 0.22%   |
| Toshiba                                 | 2         | 0.22%   |
| Silicon Power Computer & Communications | 2         | 0.22%   |
| V-Color                                 | 1         | 0.11%   |
| Unknown (768A)                          | 1         | 0.11%   |
| Unknown (0x7FFF)                        | 1         | 0.11%   |
| Unknown (0x198)                         | 1         | 0.11%   |
| Unknown (0x0E9D)                        | 1         | 0.11%   |
| Unknown (06CE)                          | 1         | 0.11%   |
| Shenzhen Mic                            | 1         | 0.11%   |
| PKI                                     | 1         | 0.11%   |
| Patriot Memory (PDP Systems)            | 1         | 0.11%   |
| Neo Forza                               | 1         | 0.11%   |
| KLEVV                                   | 1         | 0.11%   |
| A Force                                 | 1         | 0.11%   |
| <Invalid>                               | 1         | 0.11%   |
| 48spaces                                | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s                          | 29        | 3.04%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s                          | 18        | 1.89%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM 1866MT/s                                 | 15        | 1.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                            | 12        | 1.26%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                            | 11        | 1.15%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s                              | 10        | 1.05%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                           | 8         | 0.84%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s                         | 8         | 0.84%   |
| Micro Memory Bank RAM FFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFF 2GB DIMM DDR2 667MT/s | 8         | 0.84%   |
| Unknown                                                                          | 8         | 0.84%   |
| Unknown RAM Module 2GB DIMM SDRAM                                                | 7         | 0.73%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s                 | 7         | 0.73%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                           | 7         | 0.73%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s                            | 7         | 0.73%   |
| Patriot RAM PSD38G13332 8GB DIMM DDR3 1333MT/s                                   | 6         | 0.63%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                             | 6         | 0.63%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s                           | 6         | 0.63%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                             | 5         | 0.52%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s                           | 5         | 0.52%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                            | 5         | 0.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                            | 5         | 0.52%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                            | 5         | 0.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s                      | 5         | 0.52%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s                              | 5         | 0.52%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s                            | 5         | 0.52%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s                             | 5         | 0.52%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                             | 4         | 0.42%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                                             | 4         | 0.42%   |
| Unknown RAM Module 1GB DIMM SDRAM                                                | 4         | 0.42%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                           | 4         | 0.42%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s                     | 4         | 0.42%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                            | 4         | 0.42%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                            | 4         | 0.42%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                            | 4         | 0.42%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s                            | 4         | 0.42%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                             | 4         | 0.42%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                                       | 4         | 0.42%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s                            | 4         | 0.42%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                                      | 4         | 0.42%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                         | 3         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 405       | 50.94%  |
| DDR3    | 183       | 23.02%  |
| LPDDR4  | 38        | 4.78%   |
| DDR5    | 37        | 4.65%   |
| DDR2    | 36        | 4.53%   |
| Unknown | 27        | 3.4%    |
| SDRAM   | 23        | 2.89%   |
| LPDDR3  | 23        | 2.89%   |
| LPDDR5  | 15        | 1.89%   |
| DDR     | 8         | 1.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 404       | 50.37%  |
| DIMM         | 311       | 38.78%  |
| Row Of Chips | 73        | 9.1%    |
| Unknown      | 7         | 0.87%   |
| Chip         | 5         | 0.62%   |
| RIMM         | 1         | 0.12%   |
| FB-DIMM      | 1         | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 335       | 39.04%  |
| 4096  | 197       | 22.96%  |
| 16384 | 138       | 16.08%  |
| 2048  | 97        | 11.31%  |
| 32768 | 45        | 5.24%   |
| 1024  | 36        | 4.2%    |
| 512   | 8         | 0.93%   |
| 256   | 1         | 0.12%   |
| 64    | 1         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 152       | 18.1%   |
| 2667    | 137       | 16.31%  |
| 1600    | 106       | 12.62%  |
| 2400    | 57        | 6.79%   |
| 2133    | 44        | 5.24%   |
| 1333    | 38        | 4.52%   |
| 667     | 26        | 3.1%    |
| 3600    | 23        | 2.74%   |
| Unknown | 23        | 2.74%   |
| 4800    | 22        | 2.62%   |
| 4267    | 19        | 2.26%   |
| 800     | 19        | 2.26%   |
| 6400    | 17        | 2.02%   |
| 1867    | 17        | 2.02%   |
| 1866    | 17        | 2.02%   |
| 1334    | 16        | 1.9%    |
| 1067    | 11        | 1.31%   |
| 4333    | 10        | 1.19%   |
| 1066    | 10        | 1.19%   |
| 3266    | 9         | 1.07%   |
| 2666    | 7         | 0.83%   |
| 6000    | 4         | 0.48%   |
| 5600    | 4         | 0.48%   |
| 5200    | 4         | 0.48%   |
| 4199    | 3         | 0.36%   |
| 3933    | 3         | 0.36%   |
| 3733    | 3         | 0.36%   |
| 3400    | 3         | 0.36%   |
| 3000    | 3         | 0.36%   |
| 8400    | 2         | 0.24%   |
| 4266    | 2         | 0.24%   |
| 3800    | 2         | 0.24%   |
| 3534    | 2         | 0.24%   |
| 2933    | 2         | 0.24%   |
| 2866    | 2         | 0.24%   |
| 2048    | 2         | 0.24%   |
| 1800    | 2         | 0.24%   |
| 1639    | 2         | 0.24%   |
| 5800    | 1         | 0.12%   |
| 5354    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 6         | 28.57%  |
| Hewlett-Packard     | 4         | 19.05%  |
| Canon               | 4         | 19.05%  |
| Samsung Electronics | 2         | 9.52%   |
| Dymo-CoStar         | 2         | 9.52%   |
| Zebra               | 1         | 4.76%   |
| Seiko Epson         | 1         | 4.76%   |
| Pantum              | 1         | 4.76%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Canon MF3010                           | 2         | 9.52%   |
| Zebra Printer                          | 1         | 4.76%   |
| Seiko Epson L6290 Series               | 1         | 4.76%   |
| Samsung M2070 Series                   | 1         | 4.76%   |
| Samsung M2020 Series                   | 1         | 4.76%   |
| Pantum P2500W series                   | 1         | 4.76%   |
| HP Officejet 4500 G510a-f              | 1         | 4.76%   |
| HP LaserJet P2035                      | 1         | 4.76%   |
| HP LaserJet 1022                       | 1         | 4.76%   |
| HP ENVY 5540 series                    | 1         | 4.76%   |
| Dymo-CoStar DYMO LabelWriter DUO       | 1         | 4.76%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1         | 4.76%   |
| Canon PIXMA iP4300 Printer             | 1         | 4.76%   |
| Canon MF4010 series                    | 1         | 4.76%   |
| Brother MFC-L2710DW series             | 1         | 4.76%   |
| Brother HL-L2390DW                     | 1         | 4.76%   |
| Brother HL-3040CN series               | 1         | 4.76%   |
| Brother HL-1110 series                 | 1         | 4.76%   |
| Brother DCP-7030                       | 1         | 4.76%   |
| Brother DCP-7010                       | 1         | 4.76%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 3         | 50%     |
| Seiko Epson     | 2         | 33.33%  |
| Hewlett-Packard | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]   | 1         | 16.67%  |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 16.67%  |
| HP ScanJet 82x0C                              | 1         | 16.67%  |
| Canon CanoScan N670U/N676U/LiDE 20            | 1         | 16.67%  |
| Canon CanoScan LiDE 210                       | 1         | 16.67%  |
| Canon CanoScan LiDE 110                       | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 119       | 21.25%  |
| IMC Networks                           | 58        | 10.36%  |
| Bison Electronics                      | 53        | 9.46%   |
| Microdia                               | 43        | 7.68%   |
| Quanta                                 | 34        | 6.07%   |
| Realtek Semiconductor                  | 32        | 5.71%   |
| Logitech                               | 30        | 5.36%   |
| Luxvisions Innotech Limited            | 21        | 3.75%   |
| Sunplus Innovation Technology          | 19        | 3.39%   |
| Apple                                  | 17        | 3.04%   |
| Acer                                   | 17        | 3.04%   |
| Microsoft                              | 14        | 2.5%    |
| Lite-On Technology                     | 14        | 2.5%    |
| Syntek                                 | 13        | 2.32%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 2.32%   |
| Suyin                                  | 9         | 1.61%   |
| Silicon Motion                         | 5         | 0.89%   |
| Lenovo                                 | 5         | 0.89%   |
| Generalplus Technology                 | 5         | 0.89%   |
| Sonix Technology                       | 4         | 0.71%   |
| Jieli Technology                       | 4         | 0.71%   |
| SunplusIT                              | 3         | 0.54%   |
| Ricoh                                  | 3         | 0.54%   |
| icSpring                               | 3         | 0.54%   |
| KYE Systems (Mouse Systems)            | 2         | 0.36%   |
| ALi                                    | 2         | 0.36%   |
| Alcor Micro                            | 2         | 0.36%   |
| Z-Star Microelectronics                | 1         | 0.18%   |
| ValueHD                                | 1         | 0.18%   |
| Tobii Technology AB                    | 1         | 0.18%   |
| Sony Electronics                       | 1         | 0.18%   |
| Samsung Electronics                    | 1         | 0.18%   |
| Ruision                                | 1         | 0.18%   |
| Primax Electronics                     | 1         | 0.18%   |
| OmniVision Technologies                | 1         | 0.18%   |
| Magic Control Technology               | 1         | 0.18%   |
| Importek                               | 1         | 0.18%   |
| Image Processor                        | 1         | 0.18%   |
| HRY                                    | 1         | 0.18%   |
| GEMBIRD                                | 1         | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 34        | 5.95%   |
| Bison BisonCam, NB Pro                              | 29        | 5.08%   |
| Microdia Integrated_Webcam_HD                       | 25        | 4.38%   |
| IMC Networks Integrated Camera                      | 18        | 3.15%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 15        | 2.63%   |
| Realtek Integrated_Webcam_HD                        | 14        | 2.45%   |
| Chicony HP HD Camera                                | 11        | 1.93%   |
| Syntek Integrated Camera                            | 10        | 1.75%   |
| Sunplus Integrated_Webcam_HD                        | 10        | 1.75%   |
| Chicony HD Webcam                                   | 10        | 1.75%   |
| Logitech Webcam C270                                | 9         | 1.58%   |
| Bison Integrated Camera                             | 9         | 1.58%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 8         | 1.4%    |
| Chicony HD User Facing                              | 8         | 1.4%    |
| Quanta HD User Facing                               | 7         | 1.23%   |
| Lite-On Integrated Camera                           | 7         | 1.23%   |
| Acer Integrated Camera                              | 7         | 1.23%   |
| Logitech HD Pro Webcam C920                         | 6         | 1.05%   |
| Quanta HP TrueVision HD Camera                      | 5         | 0.88%   |
| Microsoft LifeCam HD-3000                           | 5         | 0.88%   |
| IMC Networks ov9734_azurewave_camera                | 5         | 0.88%   |
| Apple FaceTime HD Camera (Built-in)                 | 5         | 0.88%   |
| Sonix USB2.0 HD UVC WebCam                          | 4         | 0.7%    |
| Quanta ov9734_techfront_camera                      | 4         | 0.7%    |
| Quanta HP HD Camera                                 | 4         | 0.7%    |
| Luxvisions Innotech Limited Integrated Camera       | 4         | 0.7%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 4         | 0.7%    |
| Jieli USB PHY 2.0                                   | 4         | 0.7%    |
| Generalplus GENERAL WEBCAM                          | 4         | 0.7%    |
| Chicony USB2.0 Camera                               | 4         | 0.7%    |
| Chicony USB 2.0 Camera                              | 4         | 0.7%    |
| Chicony Integrated Camera (1280x720@30)             | 4         | 0.7%    |
| Chicony HP Wide Vision HD Camera                    | 4         | 0.7%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 4         | 0.7%    |
| Apple Built-in iSight                               | 4         | 0.7%    |
| Realtek USB Camera                                  | 3         | 0.53%   |
| Realtek Integrated Webcam                           | 3         | 0.53%   |
| Microdia Integrated Webcam                          | 3         | 0.53%   |
| Luxvisions Innotech Limited HP HD Camera            | 3         | 0.53%   |
| Luxvisions Innotech Limited HP 5MP Camera           | 3         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 42        | 35.9%   |
| Validity Sensors                   | 36        | 30.77%  |
| Shenzhen Goodix Technology         | 19        | 16.24%  |
| Elan Microelectronics              | 5         | 4.27%   |
| Upek                               | 4         | 3.42%   |
| STMicroelectronics                 | 3         | 2.56%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 1.71%   |
| LighTuning Technology              | 2         | 1.71%   |
| Focal-systems.Corp                 | 2         | 1.71%   |
| AuthenTec                          | 2         | 1.71%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 18        | 15.38%  |
| Shenzhen Goodix  Fingerprint Device                                        | 15        | 12.82%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 9.4%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 5.98%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 5.13%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 5.13%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 3.42%   |
| Synaptics UWP WBDI Device                                                  | 4         | 3.42%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 3.42%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 2.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 2.56%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 2.56%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 2.56%   |
| Elan ELAN:ARM-M4                                                           | 3         | 2.56%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.71%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 1.71%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.71%   |
| Synaptics UWP WBDI                                                         | 2         | 1.71%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 1.71%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.71%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 1.71%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.71%   |
| Unknown                                                                    | 2         | 1.71%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.85%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.85%   |
| Synaptics WBDI                                                             | 1         | 0.85%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.85%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.85%   |
| AuthenTec AES1600                                                          | 1         | 0.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 17        | 39.53%  |
| Broadcom              | 16        | 37.21%  |
| Lenovo                | 3         | 6.98%   |
| Upek                  | 2         | 4.65%   |
| Realtek Semiconductor | 2         | 4.65%   |
| Yubico.com            | 1         | 2.33%   |
| SCM Microsystems      | 1         | 2.33%   |
| O2 Micro              | 1         | 2.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 16        | 37.21%  |
| Broadcom 5880                                                                | 5         | 11.63%  |
| Broadcom 58200                                                               | 5         | 11.63%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 9.3%    |
| Lenovo Integrated Smart Card Reader                                          | 3         | 6.98%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.65%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 4.65%   |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 4.65%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 2.33%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 2.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2.33%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 2.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 534       | 53.19%  |
| 1     | 394       | 39.24%  |
| 2     | 65        | 6.47%   |
| 3     | 8         | 0.8%    |
| 5     | 2         | 0.2%    |
| 4     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 235       | 45.99%  |
| Fingerprint reader       | 115       | 22.5%   |
| Net/wireless             | 38        | 7.44%   |
| Chipcard                 | 35        | 6.85%   |
| Multimedia controller    | 33        | 6.46%   |
| Camera                   | 24        | 4.7%    |
| Communication controller | 7         | 1.37%   |
| Bluetooth                | 7         | 1.37%   |
| Unassigned class         | 5         | 0.98%   |
| Sound                    | 4         | 0.78%   |
| Network                  | 3         | 0.59%   |
| Wireless                 | 2         | 0.39%   |
| Storage/raid             | 1         | 0.2%    |
| Storage                  | 1         | 0.2%    |
| Net/ethernet             | 1         | 0.2%    |

