Debian 11 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Debian 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 3952

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [1165717061](https://linux-hardware.org/?probe=1165717061) | Feb 28, 2023 |
| TUXEDO        | Aura 15 Gen2                | [26a7db2ed8](https://linux-hardware.org/?probe=26a7db2ed8) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [3fa4d926e0](https://linux-hardware.org/?probe=3fa4d926e0) | Feb 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | [b4bfab8974](https://linux-hardware.org/?probe=b4bfab8974) | Feb 28, 2023 |
| HP            | ProBook 6570b               | [3692011e3f](https://linux-hardware.org/?probe=3692011e3f) | Feb 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [83a611b1ab](https://linux-hardware.org/?probe=83a611b1ab) | Feb 27, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [ccac327e17](https://linux-hardware.org/?probe=ccac327e17) | Feb 27, 2023 |
| Dell          | Latitude 5400               | [b788c61c95](https://linux-hardware.org/?probe=b788c61c95) | Feb 27, 2023 |
| Dell          | Latitude 3510               | [de938c4962](https://linux-hardware.org/?probe=de938c4962) | Feb 27, 2023 |
| ASUSTek       | K52F                        | [fa30ea101a](https://linux-hardware.org/?probe=fa30ea101a) | Feb 27, 2023 |
| HP            | Pavilion g6                 | [41e4ef16e4](https://linux-hardware.org/?probe=41e4ef16e4) | Feb 26, 2023 |
| Panasonic     | CF-31WEUEEBE                | [40782ba0a7](https://linux-hardware.org/?probe=40782ba0a7) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430 2349GUU       | [95cc420bd5](https://linux-hardware.org/?probe=95cc420bd5) | Feb 26, 2023 |
| Medion        | BEAST X25                   | [3263e2862a](https://linux-hardware.org/?probe=3263e2862a) | Feb 26, 2023 |
| HP            | 250 G7 Notebook PC          | [9e587033a4](https://linux-hardware.org/?probe=9e587033a4) | Feb 26, 2023 |
| HP            | Compaq 6730b (FU594ES#AB... | [810cdb1ad1](https://linux-hardware.org/?probe=810cdb1ad1) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | [28bb1541b4](https://linux-hardware.org/?probe=28bb1541b4) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | [8906540d72](https://linux-hardware.org/?probe=8906540d72) | Feb 26, 2023 |
| Lenovo        | ThinkPad X13s Gen 1 21BX... | [633fb08804](https://linux-hardware.org/?probe=633fb08804) | Feb 26, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [3b2a19c835](https://linux-hardware.org/?probe=3b2a19c835) | Feb 26, 2023 |
| HP            | ProBook 445 G7              | [f2671a0f62](https://linux-hardware.org/?probe=f2671a0f62) | Feb 25, 2023 |
| ASUSTek       | X551CA                      | [c8ead0e580](https://linux-hardware.org/?probe=c8ead0e580) | Feb 25, 2023 |
| Unknown       | T3 MRD                      | [ae88920ea5](https://linux-hardware.org/?probe=ae88920ea5) | Feb 25, 2023 |
| Acer          | Nitro AN517-55              | [76e7c1c236](https://linux-hardware.org/?probe=76e7c1c236) | Feb 25, 2023 |
| HUAWEI        | WRT-WX9                     | [d49316c5e8](https://linux-hardware.org/?probe=d49316c5e8) | Feb 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [67e31f8e42](https://linux-hardware.org/?probe=67e31f8e42) | Feb 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [2bb4e30118](https://linux-hardware.org/?probe=2bb4e30118) | Feb 25, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [f1db9ad466](https://linux-hardware.org/?probe=f1db9ad466) | Feb 25, 2023 |
| Acer          | Aspire A315-54              | [ff08a846b0](https://linux-hardware.org/?probe=ff08a846b0) | Feb 25, 2023 |
| Unknown       | Unknown                     | [2c5d6ab621](https://linux-hardware.org/?probe=2c5d6ab621) | Feb 25, 2023 |
| HP            | Pavilion g6                 | [5cde621e0a](https://linux-hardware.org/?probe=5cde621e0a) | Feb 24, 2023 |
| Acer          | AO756                       | [ca83ee78ec](https://linux-hardware.org/?probe=ca83ee78ec) | Feb 24, 2023 |
| Lenovo        | KaiTian N70z G1d            | [cbc8e4e008](https://linux-hardware.org/?probe=cbc8e4e008) | Feb 24, 2023 |
| ASUSTek       | X551CA                      | [62b46afbb8](https://linux-hardware.org/?probe=62b46afbb8) | Feb 24, 2023 |
| Toshiba       | IS 1412                     | [c2ca1fb2f3](https://linux-hardware.org/?probe=c2ca1fb2f3) | Feb 24, 2023 |
| HP            | Presario CQ57               | [b41de6d094](https://linux-hardware.org/?probe=b41de6d094) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | [3f28f459bf](https://linux-hardware.org/?probe=3f28f459bf) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | [8ed4158090](https://linux-hardware.org/?probe=8ed4158090) | Feb 24, 2023 |
| Dell          | Latitude D620               | [fba80b099d](https://linux-hardware.org/?probe=fba80b099d) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [5da2f709bb](https://linux-hardware.org/?probe=5da2f709bb) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [bf32299a30](https://linux-hardware.org/?probe=bf32299a30) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [54279e4e30](https://linux-hardware.org/?probe=54279e4e30) | Feb 24, 2023 |
| HP            | EliteBook Folio 9480m       | [788e0929de](https://linux-hardware.org/?probe=788e0929de) | Feb 24, 2023 |
| Samsung       | N150P                       | [662488621d](https://linux-hardware.org/?probe=662488621d) | Feb 24, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [885478dd47](https://linux-hardware.org/?probe=885478dd47) | Feb 23, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [53eb80a44b](https://linux-hardware.org/?probe=53eb80a44b) | Feb 23, 2023 |
| Lenovo        | ThinkPad T410 2537CS0       | [8d4b399341](https://linux-hardware.org/?probe=8d4b399341) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [53d46c67f9](https://linux-hardware.org/?probe=53d46c67f9) | Feb 23, 2023 |
| LincPlus      | P2                          | [5d4e528621](https://linux-hardware.org/?probe=5d4e528621) | Feb 23, 2023 |
| Lenovo        | ThinkPad E14 20RA0036HV     | [eef601ff61](https://linux-hardware.org/?probe=eef601ff61) | Feb 23, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [09070f52bb](https://linux-hardware.org/?probe=09070f52bb) | Feb 23, 2023 |
| Dell          | Inspiron 5566               | [0233d7525d](https://linux-hardware.org/?probe=0233d7525d) | Feb 22, 2023 |
| Fujitsu       | LIFEBOOK E753               | [8fa3315cca](https://linux-hardware.org/?probe=8fa3315cca) | Feb 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [8227fec538](https://linux-hardware.org/?probe=8227fec538) | Feb 22, 2023 |
| Acer          | Aspire A315-54              | [7cf8754a48](https://linux-hardware.org/?probe=7cf8754a48) | Feb 22, 2023 |
| Acer          | AO756                       | [58f52941c7](https://linux-hardware.org/?probe=58f52941c7) | Feb 22, 2023 |
| ASUSTek       | X556UQ                      | [8f645fa6fc](https://linux-hardware.org/?probe=8f645fa6fc) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470 20HDS1DL03    | [25e1a3f801](https://linux-hardware.org/?probe=25e1a3f801) | Feb 21, 2023 |
| Dell          | Latitude E6430              | [80c9785ef0](https://linux-hardware.org/?probe=80c9785ef0) | Feb 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | [1c0772ccd7](https://linux-hardware.org/?probe=1c0772ccd7) | Feb 21, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [6ab7953740](https://linux-hardware.org/?probe=6ab7953740) | Feb 20, 2023 |
| Notebook      | PB50_70RF,RD,RC             | [b24f005b1d](https://linux-hardware.org/?probe=b24f005b1d) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | [19d29283ed](https://linux-hardware.org/?probe=19d29283ed) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | [8d1bb46519](https://linux-hardware.org/?probe=8d1bb46519) | Feb 20, 2023 |
| Acer          | Extensa 2520G               | [823c5829a9](https://linux-hardware.org/?probe=823c5829a9) | Feb 20, 2023 |
| Lenovo        | ThinkPad T430 2349PZG       | [7bd3c5a555](https://linux-hardware.org/?probe=7bd3c5a555) | Feb 20, 2023 |
| Acer          | Aspire V5-573G              | [376b35f5b6](https://linux-hardware.org/?probe=376b35f5b6) | Feb 20, 2023 |
| Dell          | Latitude E7270              | [4eb17c846c](https://linux-hardware.org/?probe=4eb17c846c) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | [234358d23e](https://linux-hardware.org/?probe=234358d23e) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | [1b75d34b95](https://linux-hardware.org/?probe=1b75d34b95) | Feb 20, 2023 |
| Notebook      | W54_55SU1,SUW               | [5a296bed7f](https://linux-hardware.org/?probe=5a296bed7f) | Feb 19, 2023 |
| Acer          | Nitro AN515-55              | [3158f1e0d5](https://linux-hardware.org/?probe=3158f1e0d5) | Feb 18, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [8907f179e9](https://linux-hardware.org/?probe=8907f179e9) | Feb 18, 2023 |
| Lenovo        | ThinkPad E480 20KN001QGE    | [008f40a707](https://linux-hardware.org/?probe=008f40a707) | Feb 18, 2023 |
| Dell          | Latitude E5450              | [56827b29dc](https://linux-hardware.org/?probe=56827b29dc) | Feb 18, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | [32f5d5e200](https://linux-hardware.org/?probe=32f5d5e200) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [4bf1ccfe74](https://linux-hardware.org/?probe=4bf1ccfe74) | Feb 17, 2023 |
| Apple         | MacBookPro9,1               | [4ab4c99cab](https://linux-hardware.org/?probe=4ab4c99cab) | Feb 17, 2023 |
| Dell          | System XPS L702X            | [81f9738975](https://linux-hardware.org/?probe=81f9738975) | Feb 16, 2023 |
| Apple         | MacBookAir6,2               | [46aafc59c4](https://linux-hardware.org/?probe=46aafc59c4) | Feb 16, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [a4fd7cdaa8](https://linux-hardware.org/?probe=a4fd7cdaa8) | Feb 16, 2023 |
| HP            | EliteBook 2530p             | [5398361b68](https://linux-hardware.org/?probe=5398361b68) | Feb 16, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [73787e9141](https://linux-hardware.org/?probe=73787e9141) | Feb 16, 2023 |
| Google        | Grunt                       | [89c633c2c1](https://linux-hardware.org/?probe=89c633c2c1) | Feb 15, 2023 |
| ASUSTek       | K53U                        | [e9a6a69e01](https://linux-hardware.org/?probe=e9a6a69e01) | Feb 15, 2023 |
| Unknown       | T3 MRD                      | [df134a8199](https://linux-hardware.org/?probe=df134a8199) | Feb 14, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [e9faf4ce80](https://linux-hardware.org/?probe=e9faf4ce80) | Feb 14, 2023 |
| Acer          | Aspire V5-572G              | [7f360258ff](https://linux-hardware.org/?probe=7f360258ff) | Feb 14, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [977650806e](https://linux-hardware.org/?probe=977650806e) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [f6bcdb7c6b](https://linux-hardware.org/?probe=f6bcdb7c6b) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [345021f7f6](https://linux-hardware.org/?probe=345021f7f6) | Feb 14, 2023 |
| Lenovo        | ThinkPad P51 20HJS0AR16     | [ad0f22fe34](https://linux-hardware.org/?probe=ad0f22fe34) | Feb 14, 2023 |
| HP            | Laptop 15s-du3xxx           | [4750f3ad3a](https://linux-hardware.org/?probe=4750f3ad3a) | Feb 13, 2023 |
| Dell          | Latitude D630               | [04c083db36](https://linux-hardware.org/?probe=04c083db36) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | [6fe738fa6d](https://linux-hardware.org/?probe=6fe738fa6d) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | [122eded37e](https://linux-hardware.org/?probe=122eded37e) | Feb 13, 2023 |
| Google        | Droid                       | [435ab67598](https://linux-hardware.org/?probe=435ab67598) | Feb 12, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [89c31e6f8c](https://linux-hardware.org/?probe=89c31e6f8c) | Feb 12, 2023 |
| Unknown       | Unknown                     | [72ce8d1929](https://linux-hardware.org/?probe=72ce8d1929) | Feb 12, 2023 |
| HP            | EliteBook 850 G1            | [54e092f58f](https://linux-hardware.org/?probe=54e092f58f) | Feb 12, 2023 |
| HUAWEI        | CREM-WXX9                   | [09266b8b06](https://linux-hardware.org/?probe=09266b8b06) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | [a541cb52eb](https://linux-hardware.org/?probe=a541cb52eb) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | [35563886e8](https://linux-hardware.org/?probe=35563886e8) | Feb 12, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [b54b603772](https://linux-hardware.org/?probe=b54b603772) | Feb 12, 2023 |
| Apple         | MacBookPro10,2              | [4a6ea9bd99](https://linux-hardware.org/?probe=4a6ea9bd99) | Feb 12, 2023 |
| Apple         | MacBookPro10,2              | [063d6eb482](https://linux-hardware.org/?probe=063d6eb482) | Feb 12, 2023 |
| Lenovo        | Z50-70 20354                | [3932889971](https://linux-hardware.org/?probe=3932889971) | Feb 11, 2023 |
| Notebook      | MAM2120                     | [300a622d96](https://linux-hardware.org/?probe=300a622d96) | Feb 11, 2023 |
| Lenovo        | Z710 20250                  | [94ee6da4d3](https://linux-hardware.org/?probe=94ee6da4d3) | Feb 11, 2023 |
| HP            | Pavilion g6                 | [27323a90bb](https://linux-hardware.org/?probe=27323a90bb) | Feb 11, 2023 |
| Acer          | Predator G9-793             | [8c11736bf0](https://linux-hardware.org/?probe=8c11736bf0) | Feb 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [20a75bea61](https://linux-hardware.org/?probe=20a75bea61) | Feb 11, 2023 |
| HP            | Pavilion g6                 | [35b93693a5](https://linux-hardware.org/?probe=35b93693a5) | Feb 10, 2023 |
| Dell          | Latitude 7370               | [30c62c9e44](https://linux-hardware.org/?probe=30c62c9e44) | Feb 10, 2023 |
| Dell          | Latitude 7370               | [b4e7a5cb63](https://linux-hardware.org/?probe=b4e7a5cb63) | Feb 10, 2023 |
| ASUSTek       | N751JX                      | [fd591a3e67](https://linux-hardware.org/?probe=fd591a3e67) | Feb 10, 2023 |
| Novatech      | NL40_50CU                   | [cca307c7db](https://linux-hardware.org/?probe=cca307c7db) | Feb 10, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [7ac6f508b2](https://linux-hardware.org/?probe=7ac6f508b2) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [8239d80ae0](https://linux-hardware.org/?probe=8239d80ae0) | Feb 10, 2023 |
| IBM           | ThinkPad T43 18714AG        | [0730c9228d](https://linux-hardware.org/?probe=0730c9228d) | Feb 10, 2023 |
| Acer          | Aspire ES1-111M             | [82eea49fcd](https://linux-hardware.org/?probe=82eea49fcd) | Feb 09, 2023 |
| Acer          | Aspire ES1-111M             | [accbac47d5](https://linux-hardware.org/?probe=accbac47d5) | Feb 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [02adcb8587](https://linux-hardware.org/?probe=02adcb8587) | Feb 09, 2023 |
| Acer          | Aspire E1-571               | [fe1dac78bb](https://linux-hardware.org/?probe=fe1dac78bb) | Feb 09, 2023 |
| Dell          | Latitude E7250              | [e3c1b1e038](https://linux-hardware.org/?probe=e3c1b1e038) | Feb 09, 2023 |
| Lenovo        | Legion Y520-15IKBN 80WK     | [ec17af9e06](https://linux-hardware.org/?probe=ec17af9e06) | Feb 09, 2023 |
| AMI           | Cherry Trail CR             | [e7eab93323](https://linux-hardware.org/?probe=e7eab93323) | Feb 09, 2023 |
| Dell          | Latitude E6330              | [291e0fd64f](https://linux-hardware.org/?probe=291e0fd64f) | Feb 08, 2023 |
| HUAWEI        | CREM-WXX9                   | [965758f3ea](https://linux-hardware.org/?probe=965758f3ea) | Feb 08, 2023 |
| Acer          | Aspire A515-52G             | [e521c55b1a](https://linux-hardware.org/?probe=e521c55b1a) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [cc897fe72d](https://linux-hardware.org/?probe=cc897fe72d) | Feb 08, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | [9f6079baf2](https://linux-hardware.org/?probe=9f6079baf2) | Feb 08, 2023 |
| Dell          | Inspiron 5555               | [f5aeb173ba](https://linux-hardware.org/?probe=f5aeb173ba) | Feb 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [def4679f84](https://linux-hardware.org/?probe=def4679f84) | Feb 07, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | [db2f72084a](https://linux-hardware.org/?probe=db2f72084a) | Feb 07, 2023 |
| Panasonic     | CF-54-1                     | [32a2acc07e](https://linux-hardware.org/?probe=32a2acc07e) | Feb 07, 2023 |
| Samsung       | R530/R730                   | [f212e58647](https://linux-hardware.org/?probe=f212e58647) | Feb 07, 2023 |
| Samsung       | R530/R730                   | [9ccb976ccd](https://linux-hardware.org/?probe=9ccb976ccd) | Feb 07, 2023 |
| Dell          | Latitude E7250              | [b4a7701aa4](https://linux-hardware.org/?probe=b4a7701aa4) | Feb 07, 2023 |
| Dell          | Precision 5570              | [d279e97c00](https://linux-hardware.org/?probe=d279e97c00) | Feb 07, 2023 |
| Toshiba       | Satellite C655              | [a0c2eb7db1](https://linux-hardware.org/?probe=a0c2eb7db1) | Feb 07, 2023 |
| Google        | Terra                       | [edfe00266c](https://linux-hardware.org/?probe=edfe00266c) | Feb 06, 2023 |
| SLIMBOOK      | Essential15L                | [e2af97d5d3](https://linux-hardware.org/?probe=e2af97d5d3) | Feb 06, 2023 |
| ASUSTek       | X71Q                        | [c89b078e8f](https://linux-hardware.org/?probe=c89b078e8f) | Feb 06, 2023 |
| Aquarius      | NS585                       | [e9deef3f9e](https://linux-hardware.org/?probe=e9deef3f9e) | Feb 06, 2023 |
| Lenovo        | ThinkPad X250 20CLS2TQ22    | [112a65a03e](https://linux-hardware.org/?probe=112a65a03e) | Feb 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [413341361a](https://linux-hardware.org/?probe=413341361a) | Feb 05, 2023 |
| Toshiba       | Satellite C660              | [b2247eafed](https://linux-hardware.org/?probe=b2247eafed) | Feb 05, 2023 |
| Acer          | Aspire A317-53              | [2f56f41681](https://linux-hardware.org/?probe=2f56f41681) | Feb 05, 2023 |
| Google        | Ampton                      | [74d5b6aa4d](https://linux-hardware.org/?probe=74d5b6aa4d) | Feb 05, 2023 |
| Google        | Ampton                      | [2785bde3f9](https://linux-hardware.org/?probe=2785bde3f9) | Feb 05, 2023 |
| HP            | 255 G3                      | [dfa2e96880](https://linux-hardware.org/?probe=dfa2e96880) | Feb 05, 2023 |
| Apple         | MacBookAir7,2               | [29d133e858](https://linux-hardware.org/?probe=29d133e858) | Feb 05, 2023 |
| Acer          | Aspire E1-772               | [147ad71a27](https://linux-hardware.org/?probe=147ad71a27) | Feb 05, 2023 |
| Notebook      | W65_67SJ                    | [870af12011](https://linux-hardware.org/?probe=870af12011) | Feb 05, 2023 |
| Lenovo        | G50-45 80E3                 | [229050fbe5](https://linux-hardware.org/?probe=229050fbe5) | Feb 05, 2023 |
| ASUSTek       | F5SL                        | [1e5bb7661e](https://linux-hardware.org/?probe=1e5bb7661e) | Feb 04, 2023 |
| Lenovo        | G50-45 80E3                 | [885ad2ae95](https://linux-hardware.org/?probe=885ad2ae95) | Feb 04, 2023 |
| Toshiba       | Satellite P775              | [df8aa8c06a](https://linux-hardware.org/?probe=df8aa8c06a) | Feb 04, 2023 |
| Lenovo        | ThinkPad T440p 20ANS09W0... | [17f9df8f2c](https://linux-hardware.org/?probe=17f9df8f2c) | Feb 03, 2023 |
| Lenovo        | V310-15IKB 80T3             | [a39fb673c7](https://linux-hardware.org/?probe=a39fb673c7) | Feb 03, 2023 |
| HP            | Pavilion 15                 | [5909dd08e7](https://linux-hardware.org/?probe=5909dd08e7) | Feb 03, 2023 |
| Aquarius      | NS585                       | [7e944d88b3](https://linux-hardware.org/?probe=7e944d88b3) | Feb 03, 2023 |
| HP            | ProBook 450 G7              | [ae290fa64e](https://linux-hardware.org/?probe=ae290fa64e) | Feb 03, 2023 |
| HP            | ProBook 450 G7              | [7820377760](https://linux-hardware.org/?probe=7820377760) | Feb 03, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [2f2c8adb0c](https://linux-hardware.org/?probe=2f2c8adb0c) | Feb 02, 2023 |
| Apple         | MacBook5,2                  | [6d7a27b213](https://linux-hardware.org/?probe=6d7a27b213) | Feb 02, 2023 |
| Google        | Babymega                    | [2a8b81c6f4](https://linux-hardware.org/?probe=2a8b81c6f4) | Feb 02, 2023 |
| Dell          | Vostro 3580                 | [7efc294bac](https://linux-hardware.org/?probe=7efc294bac) | Feb 02, 2023 |
| Lenovo        | ThinkPad E495 20NE001GMX    | [29660bbd04](https://linux-hardware.org/?probe=29660bbd04) | Feb 02, 2023 |
| Dell          | Latitude 7480               | [8a7e0b16d5](https://linux-hardware.org/?probe=8a7e0b16d5) | Feb 02, 2023 |
| Dell          | Latitude E6520              | [548b13cd43](https://linux-hardware.org/?probe=548b13cd43) | Feb 02, 2023 |
| Timi          | Mi Laptop Pro 15            | [9deaff7467](https://linux-hardware.org/?probe=9deaff7467) | Feb 02, 2023 |
| Lenovo        | ThinkPad 13 20J10046US      | [85b9d54087](https://linux-hardware.org/?probe=85b9d54087) | Feb 02, 2023 |
| Apple         | MacBook5,2                  | [b8c8ed32e5](https://linux-hardware.org/?probe=b8c8ed32e5) | Feb 01, 2023 |
| Samsung       | 600B4B/600B5B               | [d3cf4446d5](https://linux-hardware.org/?probe=d3cf4446d5) | Feb 01, 2023 |
| Apple         | MacBookAir7,2               | [352c998936](https://linux-hardware.org/?probe=352c998936) | Feb 01, 2023 |
| Toshiba       | Satellite P775              | [c03f7668ac](https://linux-hardware.org/?probe=c03f7668ac) | Feb 01, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | [ac78478b3b](https://linux-hardware.org/?probe=ac78478b3b) | Feb 01, 2023 |
| HP            | Notebook                    | [3cea0a0519](https://linux-hardware.org/?probe=3cea0a0519) | Jan 31, 2023 |
| Fujitsu       | LIFEBOOK S751               | [35948f3b5e](https://linux-hardware.org/?probe=35948f3b5e) | Jan 31, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [3f17be7a85](https://linux-hardware.org/?probe=3f17be7a85) | Jan 30, 2023 |
| MSI           | GE60 0NC/GE60 0ND           | [a7ef98ea02](https://linux-hardware.org/?probe=a7ef98ea02) | Jan 30, 2023 |
| Acer          | Aspire 5552                 | [f1168775a7](https://linux-hardware.org/?probe=f1168775a7) | Jan 30, 2023 |
| Sony          | PCG-Z1VA(UC)                | [db4f48132e](https://linux-hardware.org/?probe=db4f48132e) | Jan 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [933e5a5b96](https://linux-hardware.org/?probe=933e5a5b96) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | [7017fcf775](https://linux-hardware.org/?probe=7017fcf775) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | [9afa780018](https://linux-hardware.org/?probe=9afa780018) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 42915CG       | [d058eeaad5](https://linux-hardware.org/?probe=d058eeaad5) | Jan 29, 2023 |
| HP            | ZBook 17 G3                 | [a1b5cdf1db](https://linux-hardware.org/?probe=a1b5cdf1db) | Jan 28, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a88e343a83](https://linux-hardware.org/?probe=a88e343a83) | Jan 28, 2023 |
| ASUSTek       | UX410UAR                    | [e9ac16c8ef](https://linux-hardware.org/?probe=e9ac16c8ef) | Jan 28, 2023 |
| Dell          | Inspiron 3581               | [8c8db10ac2](https://linux-hardware.org/?probe=8c8db10ac2) | Jan 28, 2023 |
| HP            | ProBook 430 G6              | [24fd7df5b6](https://linux-hardware.org/?probe=24fd7df5b6) | Jan 28, 2023 |
| HP            | EliteBook 640 14 inch G9... | [bbdf827cef](https://linux-hardware.org/?probe=bbdf827cef) | Jan 27, 2023 |
| Acer          | Aspire 7750G                | [0b05244a15](https://linux-hardware.org/?probe=0b05244a15) | Jan 27, 2023 |
| Dell          | Latitude E7440              | [9ba078f6ab](https://linux-hardware.org/?probe=9ba078f6ab) | Jan 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | [c83903fdc8](https://linux-hardware.org/?probe=c83903fdc8) | Jan 27, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [376c580dcb](https://linux-hardware.org/?probe=376c580dcb) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [d3adeb692c](https://linux-hardware.org/?probe=d3adeb692c) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [46b1227255](https://linux-hardware.org/?probe=46b1227255) | Jan 27, 2023 |
| MSI           | Creator 17 B11UE            | [fcf56cfe4d](https://linux-hardware.org/?probe=fcf56cfe4d) | Jan 27, 2023 |
| Dell          | Latitude 5420               | [379a2dc9ab](https://linux-hardware.org/?probe=379a2dc9ab) | Jan 26, 2023 |
| Dell          | Latitude 5420               | [eec8ef8ddb](https://linux-hardware.org/?probe=eec8ef8ddb) | Jan 26, 2023 |
| Google        | Careena                     | [75ca1a25dd](https://linux-hardware.org/?probe=75ca1a25dd) | Jan 26, 2023 |
| Apple         | MacBookPro10,1              | [4643f751cf](https://linux-hardware.org/?probe=4643f751cf) | Jan 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [3b96eac8a9](https://linux-hardware.org/?probe=3b96eac8a9) | Jan 25, 2023 |
| Panasonic     | FZ55-2                      | [dd9ddb12b6](https://linux-hardware.org/?probe=dd9ddb12b6) | Jan 25, 2023 |
| Lenovo        | ThinkPad X220 4291IR6       | [cc41fa5174](https://linux-hardware.org/?probe=cc41fa5174) | Jan 25, 2023 |
| Samsung       | R710                        | [17a3e2ddd9](https://linux-hardware.org/?probe=17a3e2ddd9) | Jan 25, 2023 |
| HP            | ZBook 15 G3                 | [0bde1ca99a](https://linux-hardware.org/?probe=0bde1ca99a) | Jan 24, 2023 |
| Packard Be... | EasyNote MH36               | [07ba548a55](https://linux-hardware.org/?probe=07ba548a55) | Jan 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [fd6d2ec3c2](https://linux-hardware.org/?probe=fd6d2ec3c2) | Jan 23, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [c8ec385a88](https://linux-hardware.org/?probe=c8ec385a88) | Jan 23, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [5648fbf4a0](https://linux-hardware.org/?probe=5648fbf4a0) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [62ac206f7e](https://linux-hardware.org/?probe=62ac206f7e) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [5c7625e3f8](https://linux-hardware.org/?probe=5c7625e3f8) | Jan 23, 2023 |
| Fujitsu       | LIFEBOOK S751               | [ff727a3560](https://linux-hardware.org/?probe=ff727a3560) | Jan 22, 2023 |
| Fujitsu       | LIFEBOOK S751               | [df0676ac87](https://linux-hardware.org/?probe=df0676ac87) | Jan 22, 2023 |
| Dell          | G3 3579                     | [63298dcee9](https://linux-hardware.org/?probe=63298dcee9) | Jan 22, 2023 |
| Danew         | Dbook 131                   | [08911c133e](https://linux-hardware.org/?probe=08911c133e) | Jan 22, 2023 |
| Clevo         | W150ER                      | [ba5d06437c](https://linux-hardware.org/?probe=ba5d06437c) | Jan 21, 2023 |
| Google        | Phaser                      | [557e69c5f1](https://linux-hardware.org/?probe=557e69c5f1) | Jan 21, 2023 |
| HP            | EliteBook Folio 9480m       | [cf1b67c224](https://linux-hardware.org/?probe=cf1b67c224) | Jan 21, 2023 |
| HP            | EliteBook 840 G3            | [06f6499264](https://linux-hardware.org/?probe=06f6499264) | Jan 21, 2023 |
| Dell          | Latitude 5501               | [d31f972a20](https://linux-hardware.org/?probe=d31f972a20) | Jan 20, 2023 |
| Lenovo        | G505 20240                  | [c591d80181](https://linux-hardware.org/?probe=c591d80181) | Jan 20, 2023 |
| UMAX          | VisionBook 12Wr             | [0707d617f7](https://linux-hardware.org/?probe=0707d617f7) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490s 20NYS3SX0... | [3e08ab25c6](https://linux-hardware.org/?probe=3e08ab25c6) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [80cb1c8239](https://linux-hardware.org/?probe=80cb1c8239) | Jan 19, 2023 |
| Lenovo        | ThinkPad E470 20H1004SMX    | [0d8528f0d2](https://linux-hardware.org/?probe=0d8528f0d2) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0efa802a32](https://linux-hardware.org/?probe=0efa802a32) | Jan 19, 2023 |
| Dell          | XPS 15 9500                 | [606ba17221](https://linux-hardware.org/?probe=606ba17221) | Jan 19, 2023 |
| Insyde        | Braswell                    | [18526fdbe2](https://linux-hardware.org/?probe=18526fdbe2) | Jan 19, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [20749dc72f](https://linux-hardware.org/?probe=20749dc72f) | Jan 19, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [db998abdae](https://linux-hardware.org/?probe=db998abdae) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [368ed9c856](https://linux-hardware.org/?probe=368ed9c856) | Jan 18, 2023 |
| Novatech      | NL40_50CU                   | [395dab7c43](https://linux-hardware.org/?probe=395dab7c43) | Jan 18, 2023 |
| HP            | Compaq 6910p                | [61d820a040](https://linux-hardware.org/?probe=61d820a040) | Jan 18, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [7b62e27d7a](https://linux-hardware.org/?probe=7b62e27d7a) | Jan 18, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | [393e6cd6d2](https://linux-hardware.org/?probe=393e6cd6d2) | Jan 18, 2023 |
| HP            | EliteBook 820 G4            | [430b938694](https://linux-hardware.org/?probe=430b938694) | Jan 18, 2023 |
| HP            | EliteBook 2170p             | [46705d578e](https://linux-hardware.org/?probe=46705d578e) | Jan 18, 2023 |
| HP            | EliteBook 840 G4            | [952c81c314](https://linux-hardware.org/?probe=952c81c314) | Jan 18, 2023 |
| Dell          | Latitude 5500               | [e0ae9cb026](https://linux-hardware.org/?probe=e0ae9cb026) | Jan 17, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [99e10e5d0f](https://linux-hardware.org/?probe=99e10e5d0f) | Jan 17, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [624f47d1e3](https://linux-hardware.org/?probe=624f47d1e3) | Jan 17, 2023 |
| HP            | Compaq 6730b (GW687AV)      | [e967b291d5](https://linux-hardware.org/?probe=e967b291d5) | Jan 17, 2023 |
| Dell          | Inspiron 5502               | [43c4f532aa](https://linux-hardware.org/?probe=43c4f532aa) | Jan 17, 2023 |
| Positivo      | CHT14B                      | [ab4518f121](https://linux-hardware.org/?probe=ab4518f121) | Jan 16, 2023 |
| Dell          | Inspiron 15-3567            | [020e19b05d](https://linux-hardware.org/?probe=020e19b05d) | Jan 16, 2023 |
| Lenovo        | ThinkPad T490s 20NX0076M... | [4c896e2c0e](https://linux-hardware.org/?probe=4c896e2c0e) | Jan 16, 2023 |
| Dell          | Inspiron 5502               | [9403074843](https://linux-hardware.org/?probe=9403074843) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [47d090108d](https://linux-hardware.org/?probe=47d090108d) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [219091b4e0](https://linux-hardware.org/?probe=219091b4e0) | Jan 15, 2023 |
| Apple         | MacBookAir5,1               | [f316bddcf2](https://linux-hardware.org/?probe=f316bddcf2) | Jan 15, 2023 |
| Acer          | Swift SF314-510G            | [b929f53536](https://linux-hardware.org/?probe=b929f53536) | Jan 15, 2023 |
| Dell          | Inspiron 15-3567            | [5426686264](https://linux-hardware.org/?probe=5426686264) | Jan 15, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [0ec206a07d](https://linux-hardware.org/?probe=0ec206a07d) | Jan 15, 2023 |
| HP            | EliteBook 8570w             | [53eb92efda](https://linux-hardware.org/?probe=53eb92efda) | Jan 15, 2023 |
| Lenovo        | ThinkPad T470 20HES0MV00    | [7e3b019181](https://linux-hardware.org/?probe=7e3b019181) | Jan 14, 2023 |
| HP            | Pavilion g6                 | [7d44980bca](https://linux-hardware.org/?probe=7d44980bca) | Jan 14, 2023 |
| Lenovo        | ThinkPad W520 4284W2U       | [576a509224](https://linux-hardware.org/?probe=576a509224) | Jan 14, 2023 |
| HP            | Laptop 14s-dk0xxx           | [6efb68b8da](https://linux-hardware.org/?probe=6efb68b8da) | Jan 14, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [0899d995dd](https://linux-hardware.org/?probe=0899d995dd) | Jan 14, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [f862a7e702](https://linux-hardware.org/?probe=f862a7e702) | Jan 14, 2023 |
| HP            | Pavilion g6                 | [7672e1178a](https://linux-hardware.org/?probe=7672e1178a) | Jan 14, 2023 |
| Unknown       | Unknown                     | [ce69bfd81b](https://linux-hardware.org/?probe=ce69bfd81b) | Jan 13, 2023 |
| HP            | ProBook 445 G7              | [baf20b6914](https://linux-hardware.org/?probe=baf20b6914) | Jan 13, 2023 |
| ASUSTek       | X450LD                      | [859eb05149](https://linux-hardware.org/?probe=859eb05149) | Jan 13, 2023 |
| HP            | Compaq 6735b                | [01878ee027](https://linux-hardware.org/?probe=01878ee027) | Jan 12, 2023 |
| Dell          | Inspiron 3521               | [694d5be301](https://linux-hardware.org/?probe=694d5be301) | Jan 12, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [d4691b9969](https://linux-hardware.org/?probe=d4691b9969) | Jan 12, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [2316d5dc8b](https://linux-hardware.org/?probe=2316d5dc8b) | Jan 12, 2023 |
| Lenovo        | ThinkPad T470p 20J7S1JT0... | [856d91c1ca](https://linux-hardware.org/?probe=856d91c1ca) | Jan 12, 2023 |
| Dell          | Precision M4400             | [27da7825fb](https://linux-hardware.org/?probe=27da7825fb) | Jan 12, 2023 |
| Dell          | Inspiron 3421               | [055d61383e](https://linux-hardware.org/?probe=055d61383e) | Jan 12, 2023 |
| Acer          | Swift SF314-56              | [46aebbe972](https://linux-hardware.org/?probe=46aebbe972) | Jan 11, 2023 |
| SLIMBOOK      | PRO                         | [551a4bd378](https://linux-hardware.org/?probe=551a4bd378) | Jan 11, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [6c67fc3995](https://linux-hardware.org/?probe=6c67fc3995) | Jan 11, 2023 |
| Aquarius      | NS585                       | [6fbcdf4d2f](https://linux-hardware.org/?probe=6fbcdf4d2f) | Jan 10, 2023 |
| HP            | Mini 110-1000               | [05c4656700](https://linux-hardware.org/?probe=05c4656700) | Jan 10, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [8367c27d81](https://linux-hardware.org/?probe=8367c27d81) | Jan 10, 2023 |
| HP            | 15                          | [f6b287dae1](https://linux-hardware.org/?probe=f6b287dae1) | Jan 10, 2023 |
| Acer          | Nitro AN517-54              | [8ea20821c8](https://linux-hardware.org/?probe=8ea20821c8) | Jan 10, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | [8d0b4a504d](https://linux-hardware.org/?probe=8d0b4a504d) | Jan 09, 2023 |
| Acer          | Aspire A515-54G             | [dea6736468](https://linux-hardware.org/?probe=dea6736468) | Jan 09, 2023 |
| Acer          | Aspire one 1-131            | [06c3411258](https://linux-hardware.org/?probe=06c3411258) | Jan 08, 2023 |
| HP            | ZBook 15 G3                 | [648dcae4c6](https://linux-hardware.org/?probe=648dcae4c6) | Jan 08, 2023 |
| ASUSTek       | K53U                        | [63849b1b5a](https://linux-hardware.org/?probe=63849b1b5a) | Jan 08, 2023 |
| Apple         | MacBookAir7,2               | [a4e777ea7d](https://linux-hardware.org/?probe=a4e777ea7d) | Jan 08, 2023 |
| Acer          | Aspire 7745G                | [9119962d1f](https://linux-hardware.org/?probe=9119962d1f) | Jan 07, 2023 |
| Gigabyte      | G5 GE                       | [d6a4584809](https://linux-hardware.org/?probe=d6a4584809) | Jan 07, 2023 |
| Dell          | Latitude 2110               | [9910f8985b](https://linux-hardware.org/?probe=9910f8985b) | Jan 07, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [9776545fc4](https://linux-hardware.org/?probe=9776545fc4) | Jan 06, 2023 |
| Toshiba       | Satellite C55Dt-A           | [f3cfb5dbb5](https://linux-hardware.org/?probe=f3cfb5dbb5) | Jan 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [9b0a8d487e](https://linux-hardware.org/?probe=9b0a8d487e) | Jan 06, 2023 |
| &#er &&       | Aspire 5100                 | [26da9e8ee1](https://linux-hardware.org/?probe=26da9e8ee1) | Jan 06, 2023 |
| Google        | Stout                       | [5ef816b9a6](https://linux-hardware.org/?probe=5ef816b9a6) | Jan 05, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [3245d27cb7](https://linux-hardware.org/?probe=3245d27cb7) | Jan 05, 2023 |
| HP            | EliteBook 840 Aero G8 No... | [b9f4ca82d2](https://linux-hardware.org/?probe=b9f4ca82d2) | Jan 05, 2023 |
| Acer          | Extensa 2540                | [4442f2c14a](https://linux-hardware.org/?probe=4442f2c14a) | Jan 05, 2023 |
| Acer          | Extensa 2540                | [ec8b49d7b0](https://linux-hardware.org/?probe=ec8b49d7b0) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | [0042419ccb](https://linux-hardware.org/?probe=0042419ccb) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | [82e42c0d42](https://linux-hardware.org/?probe=82e42c0d42) | Jan 04, 2023 |
| Lenovo        | ThinkPad T430s 2356BQ5      | [fdf6545b20](https://linux-hardware.org/?probe=fdf6545b20) | Jan 04, 2023 |
| HP            | 255 G8 Notebook PC          | [b876c5797a](https://linux-hardware.org/?probe=b876c5797a) | Jan 03, 2023 |
| Dell          | Inspiron 5566               | [258412ac0a](https://linux-hardware.org/?probe=258412ac0a) | Jan 03, 2023 |
| ASUSTek       | F5SL                        | [67882c0f69](https://linux-hardware.org/?probe=67882c0f69) | Jan 02, 2023 |
| ASUSTek       | F5SL                        | [42ef1fbf40](https://linux-hardware.org/?probe=42ef1fbf40) | Jan 02, 2023 |
| Acer          | Aspire ES1-711              | [735e062168](https://linux-hardware.org/?probe=735e062168) | Jan 02, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [90603e4ab3](https://linux-hardware.org/?probe=90603e4ab3) | Jan 02, 2023 |
| MSI           | GE75 Raider 8SG             | [b6fa9be350](https://linux-hardware.org/?probe=b6fa9be350) | Jan 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [b54f3aab7b](https://linux-hardware.org/?probe=b54f3aab7b) | Jan 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0D    | [a1f966e5e8](https://linux-hardware.org/?probe=a1f966e5e8) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [08fb8de608](https://linux-hardware.org/?probe=08fb8de608) | Jan 02, 2023 |
| Lenovo        | ThinkPad T430u 33519LC      | [87af3fa7f0](https://linux-hardware.org/?probe=87af3fa7f0) | Jan 02, 2023 |
| ASUSTek       | T100TA                      | [2c33e446d4](https://linux-hardware.org/?probe=2c33e446d4) | Jan 02, 2023 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [3f68b8438c](https://linux-hardware.org/?probe=3f68b8438c) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [bca75efbe5](https://linux-hardware.org/?probe=bca75efbe5) | Jan 02, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [2396307897](https://linux-hardware.org/?probe=2396307897) | Jan 02, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [13df46e700](https://linux-hardware.org/?probe=13df46e700) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [f9db70d551](https://linux-hardware.org/?probe=f9db70d551) | Jan 01, 2023 |
| Lenovo        | G565 20071                  | [e974b446ae](https://linux-hardware.org/?probe=e974b446ae) | Jan 01, 2023 |
| Panasonic     | CF-54-2                     | [dfe3d2e06b](https://linux-hardware.org/?probe=dfe3d2e06b) | Jan 01, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7474151c7e](https://linux-hardware.org/?probe=7474151c7e) | Jan 01, 2023 |
| Dell          | Inspiron 5566               | [9eadf42d31](https://linux-hardware.org/?probe=9eadf42d31) | Jan 01, 2023 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [8d33275e7b](https://linux-hardware.org/?probe=8d33275e7b) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fb22f9430c](https://linux-hardware.org/?probe=fb22f9430c) | Dec 31, 2022 |
| Lenovo        | IdeaPad Y560                | [c9d3a1d0a3](https://linux-hardware.org/?probe=c9d3a1d0a3) | Dec 31, 2022 |
| Acer          | Aspire A514-54              | [5775c77a91](https://linux-hardware.org/?probe=5775c77a91) | Dec 31, 2022 |
| HP            | Compaq 6710b (KE207ES#AB... | [d7d0be3872](https://linux-hardware.org/?probe=d7d0be3872) | Dec 30, 2022 |
| Dell          | Inspiron 5490               | [c8a80649d2](https://linux-hardware.org/?probe=c8a80649d2) | Dec 30, 2022 |
| HP            | 255 G3                      | [89d6bd459c](https://linux-hardware.org/?probe=89d6bd459c) | Dec 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S1JT0... | [4b7bbb186f](https://linux-hardware.org/?probe=4b7bbb186f) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | [5bf3ff5c0e](https://linux-hardware.org/?probe=5bf3ff5c0e) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | [4f63c4474c](https://linux-hardware.org/?probe=4f63c4474c) | Dec 29, 2022 |
| HP            | EliteBook Folio 1040 G3     | [6aad572cd5](https://linux-hardware.org/?probe=6aad572cd5) | Dec 29, 2022 |
| HP            | ZBook 15 G6                 | [af1655497e](https://linux-hardware.org/?probe=af1655497e) | Dec 29, 2022 |
| HP            | ProBook 6570b               | [46fd918b7c](https://linux-hardware.org/?probe=46fd918b7c) | Dec 29, 2022 |
| Dell          | Inspiron 5490               | [457c2ae4ae](https://linux-hardware.org/?probe=457c2ae4ae) | Dec 28, 2022 |
| Dell          | Inspiron 5490               | [fdfd0f21c7](https://linux-hardware.org/?probe=fdfd0f21c7) | Dec 28, 2022 |
| Toshiba       | Satellite L455D             | [35c085aa82](https://linux-hardware.org/?probe=35c085aa82) | Dec 28, 2022 |
| Dell          | Vostro 3400                 | [27f58a8ad1](https://linux-hardware.org/?probe=27f58a8ad1) | Dec 28, 2022 |
| Acer          | Aspire ES1-531              | [c29088a63f](https://linux-hardware.org/?probe=c29088a63f) | Dec 28, 2022 |
| HP            | ProBook 6470b               | [055705b3f2](https://linux-hardware.org/?probe=055705b3f2) | Dec 28, 2022 |
| Apple         | MacBookAir7,2               | [10dce91da1](https://linux-hardware.org/?probe=10dce91da1) | Dec 27, 2022 |
| Apple         | MacBookAir7,1               | [d174ffb318](https://linux-hardware.org/?probe=d174ffb318) | Dec 27, 2022 |
| MSI           | GE62 2QC                    | [dbd69d70ac](https://linux-hardware.org/?probe=dbd69d70ac) | Dec 27, 2022 |
| Panasonic     | FZ55-2                      | [1699b7c3b2](https://linux-hardware.org/?probe=1699b7c3b2) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [78c6c15502](https://linux-hardware.org/?probe=78c6c15502) | Dec 27, 2022 |
| Notebook      | L14xMU                      | [7644bc65e2](https://linux-hardware.org/?probe=7644bc65e2) | Dec 27, 2022 |
| Dell          | Inspiron 1012               | [3dd6b8a416](https://linux-hardware.org/?probe=3dd6b8a416) | Dec 26, 2022 |
| Exo           | Smart Serie M               | [942ee3b035](https://linux-hardware.org/?probe=942ee3b035) | Dec 26, 2022 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [3bb1c5cc47](https://linux-hardware.org/?probe=3bb1c5cc47) | Dec 26, 2022 |
| Acer          | Aspire ES1-533              | [3b5fa6d85a](https://linux-hardware.org/?probe=3b5fa6d85a) | Dec 26, 2022 |
| Lenovo        | ThinkPad X250 20CLS1UB00    | [fc8b2899fa](https://linux-hardware.org/?probe=fc8b2899fa) | Dec 25, 2022 |
| SANTECH       | NHx0DB,DE                   | [a0996d42bd](https://linux-hardware.org/?probe=a0996d42bd) | Dec 25, 2022 |
| HP            | 470 G8 Notebook PC          | [6d77c48324](https://linux-hardware.org/?probe=6d77c48324) | Dec 25, 2022 |
| ASUSTek       | G751JT                      | [16e989ff99](https://linux-hardware.org/?probe=16e989ff99) | Dec 25, 2022 |
| Dell          | Latitude E6520              | [33a51c934d](https://linux-hardware.org/?probe=33a51c934d) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | [ea09a6daa8](https://linux-hardware.org/?probe=ea09a6daa8) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | [45737153e4](https://linux-hardware.org/?probe=45737153e4) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | [42221f61fb](https://linux-hardware.org/?probe=42221f61fb) | Dec 25, 2022 |
| Medion        | E122X                       | [6e4e34bcc3](https://linux-hardware.org/?probe=6e4e34bcc3) | Dec 24, 2022 |
| Medion        | E122X                       | [bf41c45a7d](https://linux-hardware.org/?probe=bf41c45a7d) | Dec 24, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [096d4fc8c2](https://linux-hardware.org/?probe=096d4fc8c2) | Dec 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c5f2f2db53](https://linux-hardware.org/?probe=c5f2f2db53) | Dec 24, 2022 |
| Lenovo        | ThinkPad X270 20HMS16200    | [6ac6e552a8](https://linux-hardware.org/?probe=6ac6e552a8) | Dec 24, 2022 |
| Dell          | Inspiron 5570               | [1c7e7f8dd2](https://linux-hardware.org/?probe=1c7e7f8dd2) | Dec 24, 2022 |
| Dell          | Latitude E7440              | [baae52327d](https://linux-hardware.org/?probe=baae52327d) | Dec 23, 2022 |
| Dell          | Latitude E7440              | [bc5d48b831](https://linux-hardware.org/?probe=bc5d48b831) | Dec 23, 2022 |
| Dell          | Latitude E7440              | [fde483d476](https://linux-hardware.org/?probe=fde483d476) | Dec 23, 2022 |
| Dell          | Latitude E7440              | [a746012ffd](https://linux-hardware.org/?probe=a746012ffd) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [9e5c4705fa](https://linux-hardware.org/?probe=9e5c4705fa) | Dec 23, 2022 |
| Dell          | Latitude D630               | [8175d003ce](https://linux-hardware.org/?probe=8175d003ce) | Dec 23, 2022 |
| Google        | Reks                        | [ecee690e6e](https://linux-hardware.org/?probe=ecee690e6e) | Dec 23, 2022 |
| Toshiba       | Satellite L10W-B-101        | [54d5cca493](https://linux-hardware.org/?probe=54d5cca493) | Dec 23, 2022 |
| Google        | Reks                        | [58b1b4cac1](https://linux-hardware.org/?probe=58b1b4cac1) | Dec 23, 2022 |
| Dell          | Inspiron 3501               | [297651d437](https://linux-hardware.org/?probe=297651d437) | Dec 23, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [79b015dcea](https://linux-hardware.org/?probe=79b015dcea) | Dec 23, 2022 |
| Dell          | Inspiron 3501               | [958ee9d145](https://linux-hardware.org/?probe=958ee9d145) | Dec 23, 2022 |
| Dell          | G3 3590                     | [d75d9e6663](https://linux-hardware.org/?probe=d75d9e6663) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [5f75bb423d](https://linux-hardware.org/?probe=5f75bb423d) | Dec 23, 2022 |
| Acer          | Aspire 4750                 | [3256c282db](https://linux-hardware.org/?probe=3256c282db) | Dec 23, 2022 |
| HP            | 255 G7 Notebook PC          | [5bedf1557b](https://linux-hardware.org/?probe=5bedf1557b) | Dec 23, 2022 |
| Dell          | Inspiron 5490               | [1c424b5f55](https://linux-hardware.org/?probe=1c424b5f55) | Dec 23, 2022 |
| Unknown       | Unknown                     | [f9c4fecaf4](https://linux-hardware.org/?probe=f9c4fecaf4) | Dec 23, 2022 |
| Unknown       | Unknown                     | [3832db2827](https://linux-hardware.org/?probe=3832db2827) | Dec 23, 2022 |
| Toshiba       | Satellite C55Dt-A           | [67294324c5](https://linux-hardware.org/?probe=67294324c5) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [c6d28912f0](https://linux-hardware.org/?probe=c6d28912f0) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [1a14f26bd3](https://linux-hardware.org/?probe=1a14f26bd3) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [db77bb7a3f](https://linux-hardware.org/?probe=db77bb7a3f) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [d2278ed94d](https://linux-hardware.org/?probe=d2278ed94d) | Dec 22, 2022 |
| Apple         | MacBookAir7,1               | [09ba8ccf48](https://linux-hardware.org/?probe=09ba8ccf48) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [f4e79df709](https://linux-hardware.org/?probe=f4e79df709) | Dec 22, 2022 |
| Apple         | MacBookAir7,1               | [2c3febf6fa](https://linux-hardware.org/?probe=2c3febf6fa) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [cddffa9123](https://linux-hardware.org/?probe=cddffa9123) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [5f911806c8](https://linux-hardware.org/?probe=5f911806c8) | Dec 22, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [844f589d20](https://linux-hardware.org/?probe=844f589d20) | Dec 22, 2022 |
| Dell          | Latitude D630               | [e1106d8868](https://linux-hardware.org/?probe=e1106d8868) | Dec 22, 2022 |
| HP            | Stream Notebook PC 13       | [b049c64ff7](https://linux-hardware.org/?probe=b049c64ff7) | Dec 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [5f132c928b](https://linux-hardware.org/?probe=5f132c928b) | Dec 22, 2022 |
| Dell          | G3 3590                     | [8038491eb0](https://linux-hardware.org/?probe=8038491eb0) | Dec 22, 2022 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [16cae3015a](https://linux-hardware.org/?probe=16cae3015a) | Dec 21, 2022 |
| Apple         | MacBookAir7,2               | [b4e828bef3](https://linux-hardware.org/?probe=b4e828bef3) | Dec 21, 2022 |
| Dell          | Vostro 3583                 | [cf3c6eb18b](https://linux-hardware.org/?probe=cf3c6eb18b) | Dec 21, 2022 |
| Apple         | MacBookAir7,2               | [056d76bae8](https://linux-hardware.org/?probe=056d76bae8) | Dec 21, 2022 |
| Sony          | SVE1112M1EB                 | [74e100e63b](https://linux-hardware.org/?probe=74e100e63b) | Dec 21, 2022 |
| HP            | ZBook Power 15.6 inch G8... | [6b202d6cc2](https://linux-hardware.org/?probe=6b202d6cc2) | Dec 21, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [9438c80c85](https://linux-hardware.org/?probe=9438c80c85) | Dec 21, 2022 |
| Dell          | Inspiron 3501               | [449e38a14d](https://linux-hardware.org/?probe=449e38a14d) | Dec 21, 2022 |
| Dell          | G3 3590                     | [8272655600](https://linux-hardware.org/?probe=8272655600) | Dec 21, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [cd4fa20e66](https://linux-hardware.org/?probe=cd4fa20e66) | Dec 20, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e676fe186f](https://linux-hardware.org/?probe=e676fe186f) | Dec 20, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [1e53c20bdd](https://linux-hardware.org/?probe=1e53c20bdd) | Dec 20, 2022 |
| ASUSTek       | T100TA                      | [1dc546e14a](https://linux-hardware.org/?probe=1dc546e14a) | Dec 20, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [2aeb8fd0cd](https://linux-hardware.org/?probe=2aeb8fd0cd) | Dec 19, 2022 |
| ASUSTek       | 900SD                       | [43d2c88062](https://linux-hardware.org/?probe=43d2c88062) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | [956aaecbb9](https://linux-hardware.org/?probe=956aaecbb9) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | [d5ceb48450](https://linux-hardware.org/?probe=d5ceb48450) | Dec 18, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [756263bf48](https://linux-hardware.org/?probe=756263bf48) | Dec 18, 2022 |
| EUROCOM       | SCORPIUS 3D                 | [4fdf299276](https://linux-hardware.org/?probe=4fdf299276) | Dec 18, 2022 |
| Dell          | Latitude E6530              | [198a9bc936](https://linux-hardware.org/?probe=198a9bc936) | Dec 18, 2022 |
| Lenovo        | ThinkPad T470 20HES3JR02    | [f9e4638f19](https://linux-hardware.org/?probe=f9e4638f19) | Dec 18, 2022 |
| Dell          | Inspiron N5110              | [9e4f7a69c9](https://linux-hardware.org/?probe=9e4f7a69c9) | Dec 18, 2022 |
| Dell          | Latitude E4310              | [ace267f47c](https://linux-hardware.org/?probe=ace267f47c) | Dec 18, 2022 |
| Acer          | Aspire E5-573G              | [937a672cb0](https://linux-hardware.org/?probe=937a672cb0) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1e2531fdf1](https://linux-hardware.org/?probe=1e2531fdf1) | Dec 17, 2022 |
| Lenovo        | K14 Gen 1 21CUS02600        | [218654b079](https://linux-hardware.org/?probe=218654b079) | Dec 17, 2022 |
| HP            | Notebook                    | [844d855f78](https://linux-hardware.org/?probe=844d855f78) | Dec 17, 2022 |
| Unknown       | Unknown                     | [208016df07](https://linux-hardware.org/?probe=208016df07) | Dec 17, 2022 |
| Dell          | Inspiron 7590               | [e8fb837cf5](https://linux-hardware.org/?probe=e8fb837cf5) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | [5cc0ff812b](https://linux-hardware.org/?probe=5cc0ff812b) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | [062a6ed428](https://linux-hardware.org/?probe=062a6ed428) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [db670caadd](https://linux-hardware.org/?probe=db670caadd) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d5cf351351](https://linux-hardware.org/?probe=d5cf351351) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e2056deb8a](https://linux-hardware.org/?probe=e2056deb8a) | Dec 16, 2022 |
| Intel         | powered classmate PC        | [e0401225a2](https://linux-hardware.org/?probe=e0401225a2) | Dec 15, 2022 |
| Unknown       | T3 MRD                      | [909e1a1604](https://linux-hardware.org/?probe=909e1a1604) | Dec 15, 2022 |
| Google        | Cyan                        | [2b9f20b7da](https://linux-hardware.org/?probe=2b9f20b7da) | Dec 15, 2022 |
| Lenovo        | ThinkPad T430 2349I62       | [f7590c1a07](https://linux-hardware.org/?probe=f7590c1a07) | Dec 15, 2022 |
| Dell          | Latitude 3490               | [af008f69f1](https://linux-hardware.org/?probe=af008f69f1) | Dec 14, 2022 |
| Acer          | Aspire 5738                 | [c0c4581310](https://linux-hardware.org/?probe=c0c4581310) | Dec 14, 2022 |
| Apple         | MacBook6,1                  | [f19d464a26](https://linux-hardware.org/?probe=f19d464a26) | Dec 14, 2022 |
| ASUSTek       | X302LA                      | [8404a0b0c6](https://linux-hardware.org/?probe=8404a0b0c6) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [14f87b8695](https://linux-hardware.org/?probe=14f87b8695) | Dec 13, 2022 |
| Dell          | Latitude 5520               | [7e5d86eaaf](https://linux-hardware.org/?probe=7e5d86eaaf) | Dec 13, 2022 |
| ASUSTek       | G75VW                       | [8d2a0ec4e4](https://linux-hardware.org/?probe=8d2a0ec4e4) | Dec 13, 2022 |
| Exo           | Smart Serie M               | [7fcf3d09bb](https://linux-hardware.org/?probe=7fcf3d09bb) | Dec 13, 2022 |
| Google        | Terra                       | [765deab389](https://linux-hardware.org/?probe=765deab389) | Dec 12, 2022 |
| HP            | EliteBook 8460p             | [95dc27194a](https://linux-hardware.org/?probe=95dc27194a) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [dc916ac78c](https://linux-hardware.org/?probe=dc916ac78c) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [2bfcc16f6b](https://linux-hardware.org/?probe=2bfcc16f6b) | Dec 12, 2022 |
| Google        | Enguarde                    | [60cce42479](https://linux-hardware.org/?probe=60cce42479) | Dec 12, 2022 |
| Lenovo        | ThinkPad R61e 7650DHU       | [138f60e67c](https://linux-hardware.org/?probe=138f60e67c) | Dec 12, 2022 |
| HP            | EliteBook 8460p             | [99c965b83f](https://linux-hardware.org/?probe=99c965b83f) | Dec 12, 2022 |
| Dell          | Latitude 5411               | [af806502e8](https://linux-hardware.org/?probe=af806502e8) | Dec 12, 2022 |
| Acer          | Nitro AN515-51              | [918c340b04](https://linux-hardware.org/?probe=918c340b04) | Dec 12, 2022 |
| Lenovo        | ThinkPad T470 20HES6HC00    | [ca9d609d9d](https://linux-hardware.org/?probe=ca9d609d9d) | Dec 12, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | [cd7399049b](https://linux-hardware.org/?probe=cd7399049b) | Dec 11, 2022 |
| Intel         | Kabylake Platform           | [b5c2316016](https://linux-hardware.org/?probe=b5c2316016) | Dec 11, 2022 |
| Lenovo        | G770 20089                  | [f6f1441538](https://linux-hardware.org/?probe=f6f1441538) | Dec 11, 2022 |
| Lenovo        | G50-45 80E3                 | [754e028997](https://linux-hardware.org/?probe=754e028997) | Dec 11, 2022 |
| Lenovo        | G50-45 80E3                 | [fb2f97325d](https://linux-hardware.org/?probe=fb2f97325d) | Dec 11, 2022 |
| Dell          | Latitude 5480               | [01c96ca524](https://linux-hardware.org/?probe=01c96ca524) | Dec 11, 2022 |
| Dell          | Inspiron 13-5368            | [b4ea41e00f](https://linux-hardware.org/?probe=b4ea41e00f) | Dec 11, 2022 |
| Lenovo        | ThinkPad X270 20HMS16200    | [89e7835b90](https://linux-hardware.org/?probe=89e7835b90) | Dec 11, 2022 |
| Notebook      | NJ50_70CU                   | [f77f39af95](https://linux-hardware.org/?probe=f77f39af95) | Dec 11, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [4686ea3469](https://linux-hardware.org/?probe=4686ea3469) | Dec 11, 2022 |
| HP            | Laptop 15s-du3xxx           | [400a0b555d](https://linux-hardware.org/?probe=400a0b555d) | Dec 10, 2022 |
| Dell          | Latitude E7240              | [e0aca47e1b](https://linux-hardware.org/?probe=e0aca47e1b) | Dec 10, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [5f72ad2758](https://linux-hardware.org/?probe=5f72ad2758) | Dec 10, 2022 |
| Google        | Peppy                       | [59f9af1c52](https://linux-hardware.org/?probe=59f9af1c52) | Dec 10, 2022 |
| SANTECH       | NHx0DB,DE                   | [89e8d0f23e](https://linux-hardware.org/?probe=89e8d0f23e) | Dec 10, 2022 |
| Lenovo        | ThinkPad 13 20J10046US      | [170accb6cc](https://linux-hardware.org/?probe=170accb6cc) | Dec 09, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [5d96a0484a](https://linux-hardware.org/?probe=5d96a0484a) | Dec 08, 2022 |
| Toshiba       | Satellite C850-1LJ          | [4af2ab112f](https://linux-hardware.org/?probe=4af2ab112f) | Dec 08, 2022 |
| ASUSTek       | N750JV                      | [e06c6025f3](https://linux-hardware.org/?probe=e06c6025f3) | Dec 08, 2022 |
| Lenovo        | ThinkPad T61 889502U        | [b9d0a07e47](https://linux-hardware.org/?probe=b9d0a07e47) | Dec 08, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [09de0ec660](https://linux-hardware.org/?probe=09de0ec660) | Dec 08, 2022 |
| Lenovo        | ThinkPad T60 1953PKK        | [fc308e2f1c](https://linux-hardware.org/?probe=fc308e2f1c) | Dec 08, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | [e13e889312](https://linux-hardware.org/?probe=e13e889312) | Dec 08, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [e56fd20ec9](https://linux-hardware.org/?probe=e56fd20ec9) | Dec 08, 2022 |
| Lenovo        | ThinkPad E495 20NES0J800    | [17182155b5](https://linux-hardware.org/?probe=17182155b5) | Dec 07, 2022 |
| Lenovo        | ThinkPad X230 2320CTO       | [b74f2893d0](https://linux-hardware.org/?probe=b74f2893d0) | Dec 07, 2022 |
| Panasonic     | CFMX4-1                     | [c25c16fc1a](https://linux-hardware.org/?probe=c25c16fc1a) | Dec 06, 2022 |
| Dell          | Latitude 5310               | [06d96a49a1](https://linux-hardware.org/?probe=06d96a49a1) | Dec 06, 2022 |
| HP            | EliteBook 8470p             | [e2be1fe149](https://linux-hardware.org/?probe=e2be1fe149) | Dec 06, 2022 |
| Dell          | Latitude 5411               | [62e5941721](https://linux-hardware.org/?probe=62e5941721) | Dec 06, 2022 |
| Dell          | Latitude 5411               | [e0815067bd](https://linux-hardware.org/?probe=e0815067bd) | Dec 06, 2022 |
| Dell          | Latitude 5310               | [f3801600ff](https://linux-hardware.org/?probe=f3801600ff) | Dec 06, 2022 |
| HP            | EliteBook 2570p             | [fc7d866c16](https://linux-hardware.org/?probe=fc7d866c16) | Dec 06, 2022 |
| Lenovo        | ThinkPad X230 2325SDE       | [4dc49eeb10](https://linux-hardware.org/?probe=4dc49eeb10) | Dec 06, 2022 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [5b72cdbdb8](https://linux-hardware.org/?probe=5b72cdbdb8) | Dec 05, 2022 |
| ASUSTek       | X756UQK                     | [b473216b84](https://linux-hardware.org/?probe=b473216b84) | Dec 05, 2022 |
| MSI           | Creator 15M A9SD            | [f8e6206ba6](https://linux-hardware.org/?probe=f8e6206ba6) | Dec 05, 2022 |
| Acer          | Aspire A315-23G             | [41e6f6a3fa](https://linux-hardware.org/?probe=41e6f6a3fa) | Dec 05, 2022 |
| GMKtec        | NucBox5                     | [cdfbbcc5b2](https://linux-hardware.org/?probe=cdfbbcc5b2) | Dec 04, 2022 |
| ASUSTek       | S500CA                      | [267ffa24d1](https://linux-hardware.org/?probe=267ffa24d1) | Dec 04, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [f5be4eb37d](https://linux-hardware.org/?probe=f5be4eb37d) | Dec 04, 2022 |
| Toshiba       | dynabook R63/P              | [f51571b62c](https://linux-hardware.org/?probe=f51571b62c) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b475911aaf](https://linux-hardware.org/?probe=b475911aaf) | Dec 03, 2022 |
| Dell          | Inspiron 15-5578            | [61f5950e07](https://linux-hardware.org/?probe=61f5950e07) | Dec 03, 2022 |
| ASUSTek       | S500CA                      | [7145280e9e](https://linux-hardware.org/?probe=7145280e9e) | Dec 03, 2022 |
| Acer          | Aspire A315-21              | [91eb1913d7](https://linux-hardware.org/?probe=91eb1913d7) | Dec 03, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [28ab0eb248](https://linux-hardware.org/?probe=28ab0eb248) | Dec 03, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [2085f260e1](https://linux-hardware.org/?probe=2085f260e1) | Dec 03, 2022 |
| Lenovo        | ThinkPad X280 20KE0015BR    | [4c65d4e572](https://linux-hardware.org/?probe=4c65d4e572) | Dec 03, 2022 |
| Dell          | Inspiron 5566               | [54e06d37fc](https://linux-hardware.org/?probe=54e06d37fc) | Dec 02, 2022 |
| ASUSTek       | N750JV                      | [0fc50d63c4](https://linux-hardware.org/?probe=0fc50d63c4) | Dec 02, 2022 |
| Dell          | Latitude 5591               | [f5735acca7](https://linux-hardware.org/?probe=f5735acca7) | Dec 02, 2022 |
| HP            | Unknown                     | [741029c3af](https://linux-hardware.org/?probe=741029c3af) | Dec 02, 2022 |
| Aquarius      | NS585                       | [bbd3bd3ca6](https://linux-hardware.org/?probe=bbd3bd3ca6) | Dec 02, 2022 |
| Aquarius      | NS585                       | [50222418e5](https://linux-hardware.org/?probe=50222418e5) | Dec 02, 2022 |
| Aquarius      | NS585                       | [d55d40681f](https://linux-hardware.org/?probe=d55d40681f) | Dec 02, 2022 |
| Aquarius      | NS585                       | [9013a1cce6](https://linux-hardware.org/?probe=9013a1cce6) | Dec 02, 2022 |
| HP            | 620                         | [6be09298b6](https://linux-hardware.org/?probe=6be09298b6) | Dec 01, 2022 |
| Lenovo        | ThinkPad T440p 20AN0079M... | [79261239c1](https://linux-hardware.org/?probe=79261239c1) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [674157de54](https://linux-hardware.org/?probe=674157de54) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | [73c388fb61](https://linux-hardware.org/?probe=73c388fb61) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | [6d44ef56c9](https://linux-hardware.org/?probe=6d44ef56c9) | Dec 01, 2022 |
| HP            | Pavilion dv5                | [0fc7017b0c](https://linux-hardware.org/?probe=0fc7017b0c) | Nov 30, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [183243daeb](https://linux-hardware.org/?probe=183243daeb) | Nov 30, 2022 |
| Apple         | MacBookAir6,2               | [e0187bc636](https://linux-hardware.org/?probe=e0187bc636) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | [99eb1cfce0](https://linux-hardware.org/?probe=99eb1cfce0) | Nov 29, 2022 |
| Dell          | Latitude 7490               | [8934413cf0](https://linux-hardware.org/?probe=8934413cf0) | Nov 29, 2022 |
| Lenovo        | V310-14IKB 80T2             | [b7c976ef9c](https://linux-hardware.org/?probe=b7c976ef9c) | Nov 29, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [9c45563fb6](https://linux-hardware.org/?probe=9c45563fb6) | Nov 29, 2022 |
| Dell          | XPS 15 9500                 | [9c87ab493e](https://linux-hardware.org/?probe=9c87ab493e) | Nov 29, 2022 |
| Lenovo        | ThinkPad X301 2776LEG       | [ebaea0c805](https://linux-hardware.org/?probe=ebaea0c805) | Nov 28, 2022 |
| Dell          | Precision M6400             | [05f69c6917](https://linux-hardware.org/?probe=05f69c6917) | Nov 28, 2022 |
| ASUSTek       | GL752VW                     | [edc0678b85](https://linux-hardware.org/?probe=edc0678b85) | Nov 28, 2022 |
| Dell          | XPS 15 9500                 | [f149afb5d1](https://linux-hardware.org/?probe=f149afb5d1) | Nov 28, 2022 |
| ASUSTek       | N61Vg                       | [b5cc07b253](https://linux-hardware.org/?probe=b5cc07b253) | Nov 27, 2022 |
| Lenovo        | ThinkPad T450 20BUS03J00    | [8423f90db0](https://linux-hardware.org/?probe=8423f90db0) | Nov 27, 2022 |
| Lenovo        | ThinkPad T520 4243F53       | [8f9e96442a](https://linux-hardware.org/?probe=8f9e96442a) | Nov 27, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [7bd68a8bb1](https://linux-hardware.org/?probe=7bd68a8bb1) | Nov 27, 2022 |
| HP            | Compaq nx9110 (DU432EA#A... | [1b54092e14](https://linux-hardware.org/?probe=1b54092e14) | Nov 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [32bfa52fc1](https://linux-hardware.org/?probe=32bfa52fc1) | Nov 27, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [3d1b8f282a](https://linux-hardware.org/?probe=3d1b8f282a) | Nov 27, 2022 |
| MSI           | Creator 15M A9SD            | [8b47bbf475](https://linux-hardware.org/?probe=8b47bbf475) | Nov 26, 2022 |
| HP            | Laptop 15-da3xxx            | [335fce26dd](https://linux-hardware.org/?probe=335fce26dd) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | [2902b75068](https://linux-hardware.org/?probe=2902b75068) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | [973662f8d5](https://linux-hardware.org/?probe=973662f8d5) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [bede773ce4](https://linux-hardware.org/?probe=bede773ce4) | Nov 26, 2022 |
| ASUSTek       | A6R                         | [68f38deab1](https://linux-hardware.org/?probe=68f38deab1) | Nov 26, 2022 |
| Dell          | Latitude E7240              | [634ebb2a88](https://linux-hardware.org/?probe=634ebb2a88) | Nov 25, 2022 |
| HP            | Pavilion TS Sleekbook 14    | [26440cddbb](https://linux-hardware.org/?probe=26440cddbb) | Nov 25, 2022 |
| MSI           | Creator 15M A9SD            | [a15ef33296](https://linux-hardware.org/?probe=a15ef33296) | Nov 25, 2022 |
| Lenovo        | ThinkPad E14 20RBS3LE00     | [83203a04f2](https://linux-hardware.org/?probe=83203a04f2) | Nov 25, 2022 |
| ASUSTek       | GL752VW                     | [2dfd7f3926](https://linux-hardware.org/?probe=2dfd7f3926) | Nov 25, 2022 |
| Lenovo        | ThinkPad E470 20H2S00700    | [f82ee02c50](https://linux-hardware.org/?probe=f82ee02c50) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | [9e69bdbaff](https://linux-hardware.org/?probe=9e69bdbaff) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | [16acde36ab](https://linux-hardware.org/?probe=16acde36ab) | Nov 25, 2022 |
| HP            | 255 G7 Notebook PC          | [f5a6bcf0fb](https://linux-hardware.org/?probe=f5a6bcf0fb) | Nov 24, 2022 |
| ASUSTek       | X551CAP                     | [f40e3110d0](https://linux-hardware.org/?probe=f40e3110d0) | Nov 24, 2022 |
| Dell          | Latitude 5310               | [8b4ad51670](https://linux-hardware.org/?probe=8b4ad51670) | Nov 24, 2022 |
| Dell          | Latitude 5310               | [a5265c8a0e](https://linux-hardware.org/?probe=a5265c8a0e) | Nov 24, 2022 |
| Dell          | Latitude E6500              | [73d607f9e1](https://linux-hardware.org/?probe=73d607f9e1) | Nov 24, 2022 |
| Aquarius      | NS585                       | [d54530cbcb](https://linux-hardware.org/?probe=d54530cbcb) | Nov 24, 2022 |
| Aquarius      | NS585                       | [64d9bcbcde](https://linux-hardware.org/?probe=64d9bcbcde) | Nov 24, 2022 |
| Apple         | MacBookAir6,2               | [1f43ba0436](https://linux-hardware.org/?probe=1f43ba0436) | Nov 24, 2022 |
| MSI           | Modern 14 A10M              | [0545f4e38b](https://linux-hardware.org/?probe=0545f4e38b) | Nov 23, 2022 |
| Lenovo        | ThinkPad T495 20NK000UUS    | [0e8c0e6f07](https://linux-hardware.org/?probe=0e8c0e6f07) | Nov 23, 2022 |
| Lenovo        | ThinkPad T490 20N3S8T211    | [97ea649145](https://linux-hardware.org/?probe=97ea649145) | Nov 23, 2022 |
| Dell          | Latitude E6530              | [71623eedf3](https://linux-hardware.org/?probe=71623eedf3) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [df91e2d404](https://linux-hardware.org/?probe=df91e2d404) | Nov 23, 2022 |
| HP            | Compaq 6720s                | [63a0e0161c](https://linux-hardware.org/?probe=63a0e0161c) | Nov 22, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [363e0b0149](https://linux-hardware.org/?probe=363e0b0149) | Nov 22, 2022 |
| Unknown       | Unknown                     | [1de34b67e2](https://linux-hardware.org/?probe=1de34b67e2) | Nov 22, 2022 |
| Dell          | Latitude 3420               | [30434de3e9](https://linux-hardware.org/?probe=30434de3e9) | Nov 22, 2022 |
| Unknown       | Wiren Board rev. 7.3.1 (... | [1f9ccab914](https://linux-hardware.org/?probe=1f9ccab914) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0565ef1a0d](https://linux-hardware.org/?probe=0565ef1a0d) | Nov 22, 2022 |
| HP            | Pavilion Sleekbook 15       | [add4f71bc0](https://linux-hardware.org/?probe=add4f71bc0) | Nov 22, 2022 |
| HP            | ENVY 6                      | [feb348843e](https://linux-hardware.org/?probe=feb348843e) | Nov 22, 2022 |
| Lenovo        | Y520-15IKBA 80WY            | [c1cccb2b2a](https://linux-hardware.org/?probe=c1cccb2b2a) | Nov 22, 2022 |
| ASUSTek       | K53SD                       | [c127a0db71](https://linux-hardware.org/?probe=c127a0db71) | Nov 21, 2022 |
| Lenovo        | ThinkPad E14 20RAS04700     | [63d93d05db](https://linux-hardware.org/?probe=63d93d05db) | Nov 21, 2022 |
| MSI           | Creator 15M A9SD            | [e6d5440b09](https://linux-hardware.org/?probe=e6d5440b09) | Nov 21, 2022 |
| Dell          | Latitude 5310               | [9c19a3de68](https://linux-hardware.org/?probe=9c19a3de68) | Nov 21, 2022 |
| HP            | Laptop 15-db0xxx            | [f634446cde](https://linux-hardware.org/?probe=f634446cde) | Nov 21, 2022 |
| Acer          | Popcorn                     | [6f446a097a](https://linux-hardware.org/?probe=6f446a097a) | Nov 20, 2022 |
| ASUSTek       | X550LB                      | [466592b744](https://linux-hardware.org/?probe=466592b744) | Nov 20, 2022 |
| ASUSTek       | X550LB                      | [3ca5ee2f7a](https://linux-hardware.org/?probe=3ca5ee2f7a) | Nov 20, 2022 |
| HP            | Laptop 15s-du3xxx           | [a90cea62ff](https://linux-hardware.org/?probe=a90cea62ff) | Nov 19, 2022 |
| Dell          | XPS 13 9380                 | [d42bddbd11](https://linux-hardware.org/?probe=d42bddbd11) | Nov 19, 2022 |
| Aquarius      | NS585                       | [a0bc8d3f44](https://linux-hardware.org/?probe=a0bc8d3f44) | Nov 19, 2022 |
| Acer          | Aspire ES1-533              | [8c080caac2](https://linux-hardware.org/?probe=8c080caac2) | Nov 19, 2022 |
| Fujitsu       | FMVNQL7PM                   | [28ee68da79](https://linux-hardware.org/?probe=28ee68da79) | Nov 19, 2022 |
| Dell          | Latitude 7410               | [ce222880fe](https://linux-hardware.org/?probe=ce222880fe) | Nov 18, 2022 |
| Dynabook      | TECRA A50-J                 | [c0ae8746e0](https://linux-hardware.org/?probe=c0ae8746e0) | Nov 18, 2022 |
| HP            | 650                         | [43998a620b](https://linux-hardware.org/?probe=43998a620b) | Nov 18, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [0278a1f18d](https://linux-hardware.org/?probe=0278a1f18d) | Nov 18, 2022 |
| Apple         | MacBookAir7,2               | [f0fa194e20](https://linux-hardware.org/?probe=f0fa194e20) | Nov 18, 2022 |
| Google        | Terra                       | [9fcc3fb18a](https://linux-hardware.org/?probe=9fcc3fb18a) | Nov 18, 2022 |
| ASUSTek       | T100TA                      | [871be7733f](https://linux-hardware.org/?probe=871be7733f) | Nov 17, 2022 |
| MPMAN         | CONVERTER8                  | [0c8f7446f7](https://linux-hardware.org/?probe=0c8f7446f7) | Nov 17, 2022 |
| Dell          | Latitude 5310               | [8c9625dc17](https://linux-hardware.org/?probe=8c9625dc17) | Nov 17, 2022 |
| Dell          | Latitude 5310               | [958c48cd54](https://linux-hardware.org/?probe=958c48cd54) | Nov 17, 2022 |
| Lenovo        | B475 Sabine                 | [5be5a7cd5f](https://linux-hardware.org/?probe=5be5a7cd5f) | Nov 17, 2022 |
| HP            | EliteBook 745 G5            | [9d7fefd253](https://linux-hardware.org/?probe=9d7fefd253) | Nov 17, 2022 |
| MSI           | Creator 15M A9SD            | [f1fdc384f9](https://linux-hardware.org/?probe=f1fdc384f9) | Nov 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [814b5d3d2e](https://linux-hardware.org/?probe=814b5d3d2e) | Nov 17, 2022 |
| HP            | Laptop 15-db0xxx            | [5aa50e7f6c](https://linux-hardware.org/?probe=5aa50e7f6c) | Nov 17, 2022 |
| HP            | OMEN by Laptop 15-dh0xxx    | [523e8a1c6b](https://linux-hardware.org/?probe=523e8a1c6b) | Nov 17, 2022 |
| Dell          | Inspiron 13 5310            | [3c9865d86e](https://linux-hardware.org/?probe=3c9865d86e) | Nov 16, 2022 |
| HP            | Laptop 15-db0xxx            | [f6202bb6fa](https://linux-hardware.org/?probe=f6202bb6fa) | Nov 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [8fe0bcfe69](https://linux-hardware.org/?probe=8fe0bcfe69) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [5ea39eac4c](https://linux-hardware.org/?probe=5ea39eac4c) | Nov 16, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [be72c5d9db](https://linux-hardware.org/?probe=be72c5d9db) | Nov 16, 2022 |
| Lenovo        | G470 20078                  | [55f47f2c19](https://linux-hardware.org/?probe=55f47f2c19) | Nov 16, 2022 |
| Unknown       | Unknown                     | [a86465b0f3](https://linux-hardware.org/?probe=a86465b0f3) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [f29e7d7659](https://linux-hardware.org/?probe=f29e7d7659) | Nov 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [867825d906](https://linux-hardware.org/?probe=867825d906) | Nov 15, 2022 |
| Dell          | Inspiron 5558               | [0674cb5916](https://linux-hardware.org/?probe=0674cb5916) | Nov 15, 2022 |
| GPU Compan... | GWTN116-3                   | [f8d8191f69](https://linux-hardware.org/?probe=f8d8191f69) | Nov 15, 2022 |
| ASUSTek       | X550VX                      | [8e55592803](https://linux-hardware.org/?probe=8e55592803) | Nov 15, 2022 |
| Dell          | G7 7700                     | [2440bebe2c](https://linux-hardware.org/?probe=2440bebe2c) | Nov 15, 2022 |
| IBM           | ThinkPad X31 2672JBU        | [ea0c82f4eb](https://linux-hardware.org/?probe=ea0c82f4eb) | Nov 15, 2022 |
| HP            | EliteBook 820 G3            | [fe84036164](https://linux-hardware.org/?probe=fe84036164) | Nov 15, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [862e9a2c25](https://linux-hardware.org/?probe=862e9a2c25) | Nov 15, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [a94cf56482](https://linux-hardware.org/?probe=a94cf56482) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [ee5852d273](https://linux-hardware.org/?probe=ee5852d273) | Nov 15, 2022 |
| Acer          | Aspire A315-23G             | [16e5672a66](https://linux-hardware.org/?probe=16e5672a66) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [1604955bcb](https://linux-hardware.org/?probe=1604955bcb) | Nov 15, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [100714ed23](https://linux-hardware.org/?probe=100714ed23) | Nov 14, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [8267ec6686](https://linux-hardware.org/?probe=8267ec6686) | Nov 14, 2022 |
| Toshiba       | Satellite P50-B-10Q         | [f28064cdad](https://linux-hardware.org/?probe=f28064cdad) | Nov 14, 2022 |
| HP            | 530 Notebook PC(KD092AA#... | [b6c682238c](https://linux-hardware.org/?probe=b6c682238c) | Nov 13, 2022 |
| MSI           | GF63 8RD                    | [0ca4cc20c5](https://linux-hardware.org/?probe=0ca4cc20c5) | Nov 13, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [ff0881b6e4](https://linux-hardware.org/?probe=ff0881b6e4) | Nov 13, 2022 |
| HP            | 250 G8 Notebook PC          | [7e9c7562d6](https://linux-hardware.org/?probe=7e9c7562d6) | Nov 13, 2022 |
| HP            | EliteBook 8460p             | [8cb389e68e](https://linux-hardware.org/?probe=8cb389e68e) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [6677ca6be8](https://linux-hardware.org/?probe=6677ca6be8) | Nov 12, 2022 |
| GPU Compan... | GWTC116-2                   | [978facebde](https://linux-hardware.org/?probe=978facebde) | Nov 12, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [904b7c0e89](https://linux-hardware.org/?probe=904b7c0e89) | Nov 12, 2022 |
| HP            | Notebook                    | [2419e7d149](https://linux-hardware.org/?probe=2419e7d149) | Nov 12, 2022 |
| HP            | Notebook                    | [97c6c3c412](https://linux-hardware.org/?probe=97c6c3c412) | Nov 12, 2022 |
| GPU Compan... | GWTC116-2                   | [9e0c2df66d](https://linux-hardware.org/?probe=9e0c2df66d) | Nov 12, 2022 |
| IBM           | ThinkPad X31 2672JBU        | [9f627ba3f8](https://linux-hardware.org/?probe=9f627ba3f8) | Nov 12, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [22ab694d81](https://linux-hardware.org/?probe=22ab694d81) | Nov 11, 2022 |
| Lenovo        | ThinkPad W700 275236U       | [c79bbe36c5](https://linux-hardware.org/?probe=c79bbe36c5) | Nov 11, 2022 |
| NCA Group     | iRU_Notebook                | [6d22b3942e](https://linux-hardware.org/?probe=6d22b3942e) | Nov 11, 2022 |
| HP            | Spectre x2 Detachable       | [0c480bd74d](https://linux-hardware.org/?probe=0c480bd74d) | Nov 11, 2022 |
| ASUSTek       | K50IE                       | [4bd91fccfa](https://linux-hardware.org/?probe=4bd91fccfa) | Nov 11, 2022 |
| Positivo B... | VJFE53F11X-XXXXXX           | [7e81c7cf85](https://linux-hardware.org/?probe=7e81c7cf85) | Nov 10, 2022 |
| HP            | ENVY 17 Leap Motion SE N... | [ae40e6e5b3](https://linux-hardware.org/?probe=ae40e6e5b3) | Nov 10, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [f8cd836199](https://linux-hardware.org/?probe=f8cd836199) | Nov 10, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [8bb3389cc1](https://linux-hardware.org/?probe=8bb3389cc1) | Nov 10, 2022 |
| Lenovo        | G50-30 80G0                 | [1e0c308a85](https://linux-hardware.org/?probe=1e0c308a85) | Nov 10, 2022 |
| ASUSTek       | X550VXK                     | [f752e7959c](https://linux-hardware.org/?probe=f752e7959c) | Nov 10, 2022 |
| ASUSTek       | K50IE                       | [5176f404f1](https://linux-hardware.org/?probe=5176f404f1) | Nov 10, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [9a69ea4724](https://linux-hardware.org/?probe=9a69ea4724) | Nov 10, 2022 |
| Dell          | Latitude E6530              | [f71e1a930c](https://linux-hardware.org/?probe=f71e1a930c) | Nov 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [9d27997bce](https://linux-hardware.org/?probe=9d27997bce) | Nov 09, 2022 |
| Gigabyte      | Sabre 15                    | [1edede0895](https://linux-hardware.org/?probe=1edede0895) | Nov 09, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [098d4ab9ec](https://linux-hardware.org/?probe=098d4ab9ec) | Nov 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [6b1f5f2c2a](https://linux-hardware.org/?probe=6b1f5f2c2a) | Nov 08, 2022 |
| Aquarius      | NS585                       | [9b20fcc4b8](https://linux-hardware.org/?probe=9b20fcc4b8) | Nov 08, 2022 |
| Dell          | Latitude E7470              | [3938dbeadd](https://linux-hardware.org/?probe=3938dbeadd) | Nov 08, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [da41b87b7c](https://linux-hardware.org/?probe=da41b87b7c) | Nov 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [f3c625be2d](https://linux-hardware.org/?probe=f3c625be2d) | Nov 07, 2022 |
| Unknown       | Unknown                     | [6af513692f](https://linux-hardware.org/?probe=6af513692f) | Nov 07, 2022 |
| Unknown       | Unknown                     | [b4859caaba](https://linux-hardware.org/?probe=b4859caaba) | Nov 07, 2022 |
| Lenovo        | ThinkPad W700 275236U       | [d3580b26c6](https://linux-hardware.org/?probe=d3580b26c6) | Nov 06, 2022 |
| HP            | Laptop 15-db0xxx            | [32b59c7a7d](https://linux-hardware.org/?probe=32b59c7a7d) | Nov 06, 2022 |
| HP            | Laptop 15-db0xxx            | [f0c8aff40f](https://linux-hardware.org/?probe=f0c8aff40f) | Nov 06, 2022 |
| Dell          | Latitude E6520              | [9593951427](https://linux-hardware.org/?probe=9593951427) | Nov 06, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [e872e8551e](https://linux-hardware.org/?probe=e872e8551e) | Nov 06, 2022 |
| Dell          | Latitude E6520              | [53eedbde1f](https://linux-hardware.org/?probe=53eedbde1f) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [55d115647e](https://linux-hardware.org/?probe=55d115647e) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [47dda70950](https://linux-hardware.org/?probe=47dda70950) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [5a2028bd2d](https://linux-hardware.org/?probe=5a2028bd2d) | Nov 05, 2022 |
| Acer          | Aspire V3-572G              | [77f939bab4](https://linux-hardware.org/?probe=77f939bab4) | Nov 05, 2022 |
| ASUSTek       | X756UWK                     | [2d165dd7b0](https://linux-hardware.org/?probe=2d165dd7b0) | Nov 05, 2022 |
| Lenovo        | ThinkPad L380 20M50013MH    | [80ac51627a](https://linux-hardware.org/?probe=80ac51627a) | Nov 05, 2022 |
| ASUSTek       | X756UWK                     | [b89c7882f3](https://linux-hardware.org/?probe=b89c7882f3) | Nov 05, 2022 |
| Dell          | Inspiron 7570               | [158f7b0bcd](https://linux-hardware.org/?probe=158f7b0bcd) | Nov 05, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [605e06c6ad](https://linux-hardware.org/?probe=605e06c6ad) | Nov 04, 2022 |
| Google        | Terra                       | [90518f31df](https://linux-hardware.org/?probe=90518f31df) | Nov 04, 2022 |
| Google        | Terra                       | [46ffa8092b](https://linux-hardware.org/?probe=46ffa8092b) | Nov 04, 2022 |
| Google        | Terra                       | [fc3f4b0ba5](https://linux-hardware.org/?probe=fc3f4b0ba5) | Nov 04, 2022 |
| Google        | Terra                       | [41017e02e4](https://linux-hardware.org/?probe=41017e02e4) | Nov 04, 2022 |
| Google        | Terra                       | [7429a311e4](https://linux-hardware.org/?probe=7429a311e4) | Nov 04, 2022 |
| SK hynix      | HyBook                      | [e758cde5ed](https://linux-hardware.org/?probe=e758cde5ed) | Nov 04, 2022 |
| HP            | ProBook 6450b               | [7e595214cb](https://linux-hardware.org/?probe=7e595214cb) | Nov 04, 2022 |
| Acer          | Nitro AN515-55              | [a1cef4e43d](https://linux-hardware.org/?probe=a1cef4e43d) | Nov 04, 2022 |
| Acer          | Nitro AN515-55              | [b58a40d876](https://linux-hardware.org/?probe=b58a40d876) | Nov 04, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [391881cdd5](https://linux-hardware.org/?probe=391881cdd5) | Nov 03, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [67e9f8d2f4](https://linux-hardware.org/?probe=67e9f8d2f4) | Nov 03, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [ecf54fa708](https://linux-hardware.org/?probe=ecf54fa708) | Nov 03, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [8681693f03](https://linux-hardware.org/?probe=8681693f03) | Nov 03, 2022 |
| HP            | EliteBook 745 G6            | [d4d0f735d4](https://linux-hardware.org/?probe=d4d0f735d4) | Nov 03, 2022 |
| HP            | EliteBook 745 G6            | [04e15fb2d7](https://linux-hardware.org/?probe=04e15fb2d7) | Nov 03, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [c80c7a9048](https://linux-hardware.org/?probe=c80c7a9048) | Nov 03, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [e507b9a974](https://linux-hardware.org/?probe=e507b9a974) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [7a5f1eaf6c](https://linux-hardware.org/?probe=7a5f1eaf6c) | Nov 03, 2022 |
| SAGER         | D900F                       | [7e0d0de36a](https://linux-hardware.org/?probe=7e0d0de36a) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [cecc0cca9d](https://linux-hardware.org/?probe=cecc0cca9d) | Nov 03, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [464cc2acc3](https://linux-hardware.org/?probe=464cc2acc3) | Nov 03, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [d59bd1e8f1](https://linux-hardware.org/?probe=d59bd1e8f1) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [4342ecb0f9](https://linux-hardware.org/?probe=4342ecb0f9) | Nov 02, 2022 |
| Google        | Terra                       | [46299bf228](https://linux-hardware.org/?probe=46299bf228) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [fd32769391](https://linux-hardware.org/?probe=fd32769391) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [d3c1c92563](https://linux-hardware.org/?probe=d3c1c92563) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [0ffaee423b](https://linux-hardware.org/?probe=0ffaee423b) | Nov 02, 2022 |
| ASUSTek       | 1005HA                      | [1d386943d6](https://linux-hardware.org/?probe=1d386943d6) | Nov 02, 2022 |
| HP            | G42                         | [18c487d99d](https://linux-hardware.org/?probe=18c487d99d) | Nov 02, 2022 |
| Digma         | EVE 11 C422 ES1068EW        | [f5177de131](https://linux-hardware.org/?probe=f5177de131) | Nov 02, 2022 |
| Toshiba       | Satellite L755              | [dc3d60731e](https://linux-hardware.org/?probe=dc3d60731e) | Nov 01, 2022 |
| Acer          | Aspire one                  | [bfb9f97d74](https://linux-hardware.org/?probe=bfb9f97d74) | Oct 31, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c9e0b81f80](https://linux-hardware.org/?probe=c9e0b81f80) | Oct 31, 2022 |
| HP            | Compaq nc6320 (EV073AV)     | [b73f359ded](https://linux-hardware.org/?probe=b73f359ded) | Oct 31, 2022 |
| ASUSTek       | G75VW                       | [6f1d41a85c](https://linux-hardware.org/?probe=6f1d41a85c) | Oct 31, 2022 |
| Acer          | Aspire one                  | [82b34552f6](https://linux-hardware.org/?probe=82b34552f6) | Oct 31, 2022 |
| Aquarius      | NS585                       | [e4b4e0456d](https://linux-hardware.org/?probe=e4b4e0456d) | Oct 31, 2022 |
| Apple         | MacBookPro5,5               | [00e1f1f754](https://linux-hardware.org/?probe=00e1f1f754) | Oct 31, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [a872c9888a](https://linux-hardware.org/?probe=a872c9888a) | Oct 30, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [45f670d99f](https://linux-hardware.org/?probe=45f670d99f) | Oct 30, 2022 |
| Acer          | Aspire A515-51G             | [12380f78de](https://linux-hardware.org/?probe=12380f78de) | Oct 30, 2022 |
| ASUSTek       | N751JK                      | [eea92055f3](https://linux-hardware.org/?probe=eea92055f3) | Oct 30, 2022 |
| Dell          | Latitude 5501               | [67f979a26d](https://linux-hardware.org/?probe=67f979a26d) | Oct 29, 2022 |
| Notebook      | W230SD                      | [76ae019222](https://linux-hardware.org/?probe=76ae019222) | Oct 29, 2022 |
| Dell          | Latitude 5590               | [c7fa986fbd](https://linux-hardware.org/?probe=c7fa986fbd) | Oct 29, 2022 |
| ASUSTek       | X75VC                       | [9c1ab509ec](https://linux-hardware.org/?probe=9c1ab509ec) | Oct 29, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [8cc0e0d828](https://linux-hardware.org/?probe=8cc0e0d828) | Oct 29, 2022 |
| Insyde        | Braswell                    | [d98b2d9661](https://linux-hardware.org/?probe=d98b2d9661) | Oct 29, 2022 |
| Samsung       | 300V3A/300V4A/300V5A        | [4acb2d0863](https://linux-hardware.org/?probe=4acb2d0863) | Oct 29, 2022 |
| Dell          | XPS 17 9720                 | [270b988521](https://linux-hardware.org/?probe=270b988521) | Oct 29, 2022 |
| Dell          | Precision 7520              | [30f6ad7a26](https://linux-hardware.org/?probe=30f6ad7a26) | Oct 29, 2022 |
| Dell          | Precision 7520              | [b81923dbd2](https://linux-hardware.org/?probe=b81923dbd2) | Oct 29, 2022 |
| MSI           | Modern 15 A10RBS            | [ddc3eded89](https://linux-hardware.org/?probe=ddc3eded89) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [60d1db050b](https://linux-hardware.org/?probe=60d1db050b) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [2a9f06c2b4](https://linux-hardware.org/?probe=2a9f06c2b4) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [787904d265](https://linux-hardware.org/?probe=787904d265) | Oct 28, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [0971db18ed](https://linux-hardware.org/?probe=0971db18ed) | Oct 28, 2022 |
| Toshiba       | Satellite L755              | [0fa70f29d4](https://linux-hardware.org/?probe=0fa70f29d4) | Oct 28, 2022 |
| Lenovo        | ThinkPad T530 239242U       | [dbf70338e9](https://linux-hardware.org/?probe=dbf70338e9) | Oct 28, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [e34c4fde2c](https://linux-hardware.org/?probe=e34c4fde2c) | Oct 28, 2022 |
| Dell          | Latitude 5280               | [368f237efe](https://linux-hardware.org/?probe=368f237efe) | Oct 28, 2022 |
| Dell          | XPS 17 9700                 | [81121b7762](https://linux-hardware.org/?probe=81121b7762) | Oct 28, 2022 |
| Toshiba       | Satellite C650D             | [0696abd43c](https://linux-hardware.org/?probe=0696abd43c) | Oct 28, 2022 |
| Toshiba       | Satellite C650D             | [d42867d201](https://linux-hardware.org/?probe=d42867d201) | Oct 28, 2022 |
| ASUSTek       | X555QG                      | [bace747804](https://linux-hardware.org/?probe=bace747804) | Oct 28, 2022 |
| Acer          | Aspire A715-75G             | [78b0c55e62](https://linux-hardware.org/?probe=78b0c55e62) | Oct 28, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [02c6d1fe1a](https://linux-hardware.org/?probe=02c6d1fe1a) | Oct 28, 2022 |
| Lenovo        | ThinkPad E470 20H2S00700    | [768c6c8357](https://linux-hardware.org/?probe=768c6c8357) | Oct 28, 2022 |
| SANTECH       | NHx0DB,DE                   | [db8c0489f4](https://linux-hardware.org/?probe=db8c0489f4) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [63565608d1](https://linux-hardware.org/?probe=63565608d1) | Oct 28, 2022 |
| Google        | Boten                       | [2ed6baabf0](https://linux-hardware.org/?probe=2ed6baabf0) | Oct 27, 2022 |
| HP            | ZBook 15 G3                 | [2b886c255e](https://linux-hardware.org/?probe=2b886c255e) | Oct 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [24da197a3a](https://linux-hardware.org/?probe=24da197a3a) | Oct 27, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [3ab1fbc8e8](https://linux-hardware.org/?probe=3ab1fbc8e8) | Oct 27, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [faafe16cfb](https://linux-hardware.org/?probe=faafe16cfb) | Oct 27, 2022 |
| THTF          | CR F860-T1                  | [0e20f4f61a](https://linux-hardware.org/?probe=0e20f4f61a) | Oct 27, 2022 |
| ASUSTek       | X541UAK                     | [87ee863ba2](https://linux-hardware.org/?probe=87ee863ba2) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [bfd570bbef](https://linux-hardware.org/?probe=bfd570bbef) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [58820ca517](https://linux-hardware.org/?probe=58820ca517) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [6b9a3ab27e](https://linux-hardware.org/?probe=6b9a3ab27e) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [a5bd8bebc7](https://linux-hardware.org/?probe=a5bd8bebc7) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [bce3a8b1b3](https://linux-hardware.org/?probe=bce3a8b1b3) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [65a1d5242f](https://linux-hardware.org/?probe=65a1d5242f) | Oct 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a09e3f3669](https://linux-hardware.org/?probe=a09e3f3669) | Oct 26, 2022 |
| ASUSTek       | 1005HA                      | [118fed891f](https://linux-hardware.org/?probe=118fed891f) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [93b8dd8c3e](https://linux-hardware.org/?probe=93b8dd8c3e) | Oct 25, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [5e08852d18](https://linux-hardware.org/?probe=5e08852d18) | Oct 25, 2022 |
| Lenovo        | Z50-70 20354                | [08b673e57b](https://linux-hardware.org/?probe=08b673e57b) | Oct 25, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [438afb4185](https://linux-hardware.org/?probe=438afb4185) | Oct 25, 2022 |
| Toshiba       | dynabook MX/33KBL           | [7ee9057da2](https://linux-hardware.org/?probe=7ee9057da2) | Oct 25, 2022 |
| Dell          | Vostro 5490                 | [6b4c7d3c8b](https://linux-hardware.org/?probe=6b4c7d3c8b) | Oct 24, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [eae727e6a0](https://linux-hardware.org/?probe=eae727e6a0) | Oct 24, 2022 |
| Packard Be... | DOT S                       | [f280a6ccbc](https://linux-hardware.org/?probe=f280a6ccbc) | Oct 24, 2022 |
| Lenovo        | ThinkPad T470 20HES4VB00    | [f7b39d371a](https://linux-hardware.org/?probe=f7b39d371a) | Oct 24, 2022 |
| Packard Be... | H17HV                       | [2e94cfdd84](https://linux-hardware.org/?probe=2e94cfdd84) | Oct 24, 2022 |
| Alienware     | M11xR3                      | [62bf8b7b02](https://linux-hardware.org/?probe=62bf8b7b02) | Oct 24, 2022 |
| HP            | Pavilion g4                 | [3b6666b5ba](https://linux-hardware.org/?probe=3b6666b5ba) | Oct 24, 2022 |
| Lenovo        | V310-14IKB 80T2             | [73f18a6fbb](https://linux-hardware.org/?probe=73f18a6fbb) | Oct 24, 2022 |
| Dell          | Precision 7750              | [dd51bb7ccd](https://linux-hardware.org/?probe=dd51bb7ccd) | Oct 23, 2022 |
| HP            | Pavilion g4                 | [487a972bda](https://linux-hardware.org/?probe=487a972bda) | Oct 23, 2022 |
| Panasonic     | CF-LX3J-50M3                | [949acb4c3a](https://linux-hardware.org/?probe=949acb4c3a) | Oct 22, 2022 |
| HP            | Pavilion TS 11              | [6437fb22e1](https://linux-hardware.org/?probe=6437fb22e1) | Oct 22, 2022 |
| HP            | Pavilion TS 11              | [a19b5987c6](https://linux-hardware.org/?probe=a19b5987c6) | Oct 22, 2022 |
| Dell          | Latitude E6520              | [88af6c857c](https://linux-hardware.org/?probe=88af6c857c) | Oct 22, 2022 |
| Dell          | Latitude E6520              | [246517ceab](https://linux-hardware.org/?probe=246517ceab) | Oct 22, 2022 |
| ASUSTek       | X756UQK                     | [2570a4e51f](https://linux-hardware.org/?probe=2570a4e51f) | Oct 22, 2022 |
| Toshiba       | Satellite P50-B-103         | [011581fdbf](https://linux-hardware.org/?probe=011581fdbf) | Oct 21, 2022 |
| Apple         | MacBook5,2                  | [165ce75570](https://linux-hardware.org/?probe=165ce75570) | Oct 21, 2022 |
| Acer          | Swift SF314-42              | [2449f6a1b7](https://linux-hardware.org/?probe=2449f6a1b7) | Oct 21, 2022 |
| Aquarius      | NS585                       | [c953c5090c](https://linux-hardware.org/?probe=c953c5090c) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1e4d67ad76](https://linux-hardware.org/?probe=1e4d67ad76) | Oct 21, 2022 |
| Lenovo        | V310-14IKB 80T2             | [8a0f6b66e6](https://linux-hardware.org/?probe=8a0f6b66e6) | Oct 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [7acb5493d7](https://linux-hardware.org/?probe=7acb5493d7) | Oct 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [b13dc58884](https://linux-hardware.org/?probe=b13dc58884) | Oct 20, 2022 |
| ASUSTek       | G75VW                       | [194959e65e](https://linux-hardware.org/?probe=194959e65e) | Oct 20, 2022 |
| HP            | EliteBook 745 G3            | [3bfbc8dcac](https://linux-hardware.org/?probe=3bfbc8dcac) | Oct 20, 2022 |
| HP            | Laptop 15-ef2xxx            | [823d998220](https://linux-hardware.org/?probe=823d998220) | Oct 20, 2022 |
| Apple         | MacBook5,2                  | [1e76467975](https://linux-hardware.org/?probe=1e76467975) | Oct 20, 2022 |
| Aquarius      | NS585                       | [a134ed693c](https://linux-hardware.org/?probe=a134ed693c) | Oct 20, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [162e7a20b2](https://linux-hardware.org/?probe=162e7a20b2) | Oct 20, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [35d4f4cf0e](https://linux-hardware.org/?probe=35d4f4cf0e) | Oct 20, 2022 |
| HP            | 245 G7                      | [9ec088c343](https://linux-hardware.org/?probe=9ec088c343) | Oct 19, 2022 |
| ASUSTek       | X541NA                      | [5b61fd3a38](https://linux-hardware.org/?probe=5b61fd3a38) | Oct 19, 2022 |
| Dell          | Inspiron 7590               | [43ec5b2df8](https://linux-hardware.org/?probe=43ec5b2df8) | Oct 19, 2022 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [67ebd92594](https://linux-hardware.org/?probe=67ebd92594) | Oct 19, 2022 |
| Acer          | Aspire A315-23G             | [93584b3b67](https://linux-hardware.org/?probe=93584b3b67) | Oct 19, 2022 |
| Fujitsu       | LIFEBOOK E753               | [1fbb05ae6b](https://linux-hardware.org/?probe=1fbb05ae6b) | Oct 18, 2022 |
| HP            | EliteBook 745 G3            | [e800d683ef](https://linux-hardware.org/?probe=e800d683ef) | Oct 18, 2022 |
| ASUSTek       | G75VW                       | [5ee12be257](https://linux-hardware.org/?probe=5ee12be257) | Oct 18, 2022 |
| UNOWHY        | Y13G010S4EI                 | [f7f13866aa](https://linux-hardware.org/?probe=f7f13866aa) | Oct 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IAH7 82S... | [dfa3140411](https://linux-hardware.org/?probe=dfa3140411) | Oct 17, 2022 |
| Dell          | XPS 17 9700                 | [5368bd3ad6](https://linux-hardware.org/?probe=5368bd3ad6) | Oct 17, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e076f9208c](https://linux-hardware.org/?probe=e076f9208c) | Oct 17, 2022 |
| ASUSTek       | G75VW                       | [10bcc184e7](https://linux-hardware.org/?probe=10bcc184e7) | Oct 17, 2022 |
| ASUSTek       | G75VW                       | [a88a291921](https://linux-hardware.org/?probe=a88a291921) | Oct 16, 2022 |
| Lenovo        | Legion Y545 81Q6            | [b6162e2c5e](https://linux-hardware.org/?probe=b6162e2c5e) | Oct 16, 2022 |
| Dell          | Inspiron 1545               | [d9928a4ee9](https://linux-hardware.org/?probe=d9928a4ee9) | Oct 16, 2022 |
| Dell          | Latitude 3320               | [e4645890b8](https://linux-hardware.org/?probe=e4645890b8) | Oct 16, 2022 |
| Dell          | Inspiron N5110              | [ae7d737ee5](https://linux-hardware.org/?probe=ae7d737ee5) | Oct 16, 2022 |
| Dell          | Inspiron N5110              | [5cbc449f36](https://linux-hardware.org/?probe=5cbc449f36) | Oct 16, 2022 |
| HP            | Laptop 15-ef2xxx            | [fb37bc6617](https://linux-hardware.org/?probe=fb37bc6617) | Oct 15, 2022 |
| HP            | EliteBook Folio 1040 G1     | [81df2d786a](https://linux-hardware.org/?probe=81df2d786a) | Oct 15, 2022 |
| Panasonic     | CF-LX3J-50M3                | [95386977de](https://linux-hardware.org/?probe=95386977de) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | [8cf96a6d0b](https://linux-hardware.org/?probe=8cf96a6d0b) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | [a68e7df338](https://linux-hardware.org/?probe=a68e7df338) | Oct 14, 2022 |
| Dell          | Latitude E6330              | [1b1f5a27f7](https://linux-hardware.org/?probe=1b1f5a27f7) | Oct 14, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [4e29271bab](https://linux-hardware.org/?probe=4e29271bab) | Oct 14, 2022 |
| Dell          | Inspiron 5502               | [41fb5ecf07](https://linux-hardware.org/?probe=41fb5ecf07) | Oct 14, 2022 |
| MSI           | MS-N014                     | [87e6e540be](https://linux-hardware.org/?probe=87e6e540be) | Oct 14, 2022 |
| Google        | Robo                        | [d070697e72](https://linux-hardware.org/?probe=d070697e72) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | [a1b02901a1](https://linux-hardware.org/?probe=a1b02901a1) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | [a0f4cd454d](https://linux-hardware.org/?probe=a0f4cd454d) | Oct 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0ce5415fa5](https://linux-hardware.org/?probe=0ce5415fa5) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [dfc5a5f754](https://linux-hardware.org/?probe=dfc5a5f754) | Oct 13, 2022 |
| Lenovo        | ThinkPad T530 23595JU       | [e560a29570](https://linux-hardware.org/?probe=e560a29570) | Oct 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [00d174fcf4](https://linux-hardware.org/?probe=00d174fcf4) | Oct 12, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [ccee0b66d9](https://linux-hardware.org/?probe=ccee0b66d9) | Oct 12, 2022 |
| MSI           | GE72 2QF                    | [22904f1270](https://linux-hardware.org/?probe=22904f1270) | Oct 12, 2022 |
| MSI           | GE72 2QF                    | [ecd8555f97](https://linux-hardware.org/?probe=ecd8555f97) | Oct 12, 2022 |
| Thomson       | N14C4WH64                   | [bfc16b9ded](https://linux-hardware.org/?probe=bfc16b9ded) | Oct 12, 2022 |
| ASUSTek       | N53Jg                       | [0b4302ed6c](https://linux-hardware.org/?probe=0b4302ed6c) | Oct 11, 2022 |
| Apple         | MacBookAir7,2               | [8b4c66e10a](https://linux-hardware.org/?probe=8b4c66e10a) | Oct 11, 2022 |
| Dell          | Precision 7720              | [2252c7bd79](https://linux-hardware.org/?probe=2252c7bd79) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6ccdbecf19](https://linux-hardware.org/?probe=6ccdbecf19) | Oct 10, 2022 |
| Apple         | MacBook5,2                  | [4687cf8900](https://linux-hardware.org/?probe=4687cf8900) | Oct 10, 2022 |
| Toshiba       | Satellite A100              | [f280857c1c](https://linux-hardware.org/?probe=f280857c1c) | Oct 09, 2022 |
| Dell          | Inspiron 14 5420            | [d9f937a8c4](https://linux-hardware.org/?probe=d9f937a8c4) | Oct 09, 2022 |
| HP            | Pavilion TS 11              | [1a6ea38863](https://linux-hardware.org/?probe=1a6ea38863) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [7785f0ebfb](https://linux-hardware.org/?probe=7785f0ebfb) | Oct 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [487fd1959f](https://linux-hardware.org/?probe=487fd1959f) | Oct 08, 2022 |
| MSI           | Prestige 14Evo A11M         | [68137e0e8d](https://linux-hardware.org/?probe=68137e0e8d) | Oct 07, 2022 |
| HP            | Pavilion dv7                | [4564037395](https://linux-hardware.org/?probe=4564037395) | Oct 07, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [e6eac5c882](https://linux-hardware.org/?probe=e6eac5c882) | Oct 07, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [b27c3b70a7](https://linux-hardware.org/?probe=b27c3b70a7) | Oct 07, 2022 |
| Shanghai Z... | ZXE CRB                     | [479f3d24f2](https://linux-hardware.org/?probe=479f3d24f2) | Oct 06, 2022 |
| Shanghai Z... | ZXE CRB                     | [5bacb77f8b](https://linux-hardware.org/?probe=5bacb77f8b) | Oct 06, 2022 |
| HP            | EliteBook 8470p             | [1b09c0a820](https://linux-hardware.org/?probe=1b09c0a820) | Oct 06, 2022 |
| HP            | EliteBook 8470p             | [0fa7893206](https://linux-hardware.org/?probe=0fa7893206) | Oct 06, 2022 |
| Acer          | Predator PH315-53           | [0f3387ce35](https://linux-hardware.org/?probe=0f3387ce35) | Oct 06, 2022 |
| Toshiba       | Satellite L40               | [0f3e9273a6](https://linux-hardware.org/?probe=0f3e9273a6) | Oct 06, 2022 |
| Google        | Akemi                       | [5a165f46bc](https://linux-hardware.org/?probe=5a165f46bc) | Oct 05, 2022 |
| HP            | EliteBook 8570p             | [3079a45a56](https://linux-hardware.org/?probe=3079a45a56) | Oct 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [96b4cda722](https://linux-hardware.org/?probe=96b4cda722) | Oct 05, 2022 |
| HP            | EliteBook 8460p             | [02d4090cce](https://linux-hardware.org/?probe=02d4090cce) | Oct 05, 2022 |
| HP            | EliteBook 8460p             | [4f037d4c3d](https://linux-hardware.org/?probe=4f037d4c3d) | Oct 05, 2022 |
| Toshiba       | NB505                       | [9de39780b5](https://linux-hardware.org/?probe=9de39780b5) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [dea0d04059](https://linux-hardware.org/?probe=dea0d04059) | Oct 05, 2022 |
| Acer          | Aspire A315-23G             | [ab3508b938](https://linux-hardware.org/?probe=ab3508b938) | Oct 05, 2022 |
| Acer          | Aspire E1-571               | [602710e8d3](https://linux-hardware.org/?probe=602710e8d3) | Oct 04, 2022 |
| HP            | EliteBook 8460p             | [8b9d1152e4](https://linux-hardware.org/?probe=8b9d1152e4) | Oct 04, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [8631c6f717](https://linux-hardware.org/?probe=8631c6f717) | Oct 04, 2022 |
| MSI           | GF65 Thin 10SDR             | [1c2a3b90e2](https://linux-hardware.org/?probe=1c2a3b90e2) | Oct 04, 2022 |
| HP            | EliteBook 735 G6            | [c3f86b0e1a](https://linux-hardware.org/?probe=c3f86b0e1a) | Oct 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | [33b42f3ed1](https://linux-hardware.org/?probe=33b42f3ed1) | Oct 04, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [5b2fac59ea](https://linux-hardware.org/?probe=5b2fac59ea) | Oct 04, 2022 |
| Shanghai Z... | ZXE CRB                     | [b981993409](https://linux-hardware.org/?probe=b981993409) | Oct 04, 2022 |
| Lenovo        | ThinkPad Twist 20C41A3      | [3da96ac399](https://linux-hardware.org/?probe=3da96ac399) | Oct 04, 2022 |
| Acer          | Aspire A315-56              | [e799907aba](https://linux-hardware.org/?probe=e799907aba) | Oct 04, 2022 |
| Dell          | Precision M4800             | [1099761dca](https://linux-hardware.org/?probe=1099761dca) | Oct 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [31fa8b62ff](https://linux-hardware.org/?probe=31fa8b62ff) | Oct 04, 2022 |
| UNOWHY        | Y13G010S4EI                 | [38f5b56e5d](https://linux-hardware.org/?probe=38f5b56e5d) | Oct 04, 2022 |
| Dell          | Inspiron 5590               | [ed3bf1e99b](https://linux-hardware.org/?probe=ed3bf1e99b) | Oct 04, 2022 |
| Dell          | Latitude E7240              | [84ce32d994](https://linux-hardware.org/?probe=84ce32d994) | Oct 03, 2022 |
| Dell          | Latitude E5430 non-vPro     | [81ac41d8b9](https://linux-hardware.org/?probe=81ac41d8b9) | Oct 03, 2022 |
| Dell          | Latitude 2110               | [3fbbac2c8a](https://linux-hardware.org/?probe=3fbbac2c8a) | Oct 03, 2022 |
| ASUSTek       | 1225B                       | [9bb2d54ca7](https://linux-hardware.org/?probe=9bb2d54ca7) | Oct 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [1427143cf0](https://linux-hardware.org/?probe=1427143cf0) | Oct 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [64f2393fde](https://linux-hardware.org/?probe=64f2393fde) | Oct 03, 2022 |
| Toshiba       | Satellite L855              | [66e22581f7](https://linux-hardware.org/?probe=66e22581f7) | Oct 03, 2022 |
| Dell          | Precision 3570              | [f4f047eecf](https://linux-hardware.org/?probe=f4f047eecf) | Oct 03, 2022 |
| Apple         | MacBookAir7,2               | [ae39aea3e9](https://linux-hardware.org/?probe=ae39aea3e9) | Oct 02, 2022 |
| Lenovo        | ThinkPad T460s 20F90060G... | [8d17d38142](https://linux-hardware.org/?probe=8d17d38142) | Oct 02, 2022 |
| ASUSTek       | X71Q                        | [830c8ab6d2](https://linux-hardware.org/?probe=830c8ab6d2) | Oct 02, 2022 |
| Toshiba       | Satellite L45               | [79ff097329](https://linux-hardware.org/?probe=79ff097329) | Oct 02, 2022 |
| Acer          | Aspire A715-41G             | [1a473e9809](https://linux-hardware.org/?probe=1a473e9809) | Oct 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [9cd72ed352](https://linux-hardware.org/?probe=9cd72ed352) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | [5bc67115db](https://linux-hardware.org/?probe=5bc67115db) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | [4758af490a](https://linux-hardware.org/?probe=4758af490a) | Oct 01, 2022 |
| Lenovo        | ThinkPad T440s 20AQCTO1W... | [fbe1e53387](https://linux-hardware.org/?probe=fbe1e53387) | Oct 01, 2022 |
| Lenovo        | ThinkPad L380 20M5SSIN11    | [0cad79b1f7](https://linux-hardware.org/?probe=0cad79b1f7) | Sep 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [786e0c1f5d](https://linux-hardware.org/?probe=786e0c1f5d) | Sep 30, 2022 |
| HP            | Pavilion Notebook           | [ee72cbd627](https://linux-hardware.org/?probe=ee72cbd627) | Sep 29, 2022 |
| HP            | Compaq nx6325 (EY344EA#A... | [8808f98c62](https://linux-hardware.org/?probe=8808f98c62) | Sep 29, 2022 |
| ASUSTek       | N53SV                       | [6652e85ddd](https://linux-hardware.org/?probe=6652e85ddd) | Sep 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS43J0V    | [0453cd781f](https://linux-hardware.org/?probe=0453cd781f) | Sep 28, 2022 |
| HP            | 250 G7 Notebook PC          | [6ad96a2beb](https://linux-hardware.org/?probe=6ad96a2beb) | Sep 28, 2022 |
| Dell          | Vostro 15 5510              | [973307d03b](https://linux-hardware.org/?probe=973307d03b) | Sep 28, 2022 |
| Acer          | Aspire A315-23G             | [3eaaf54d1b](https://linux-hardware.org/?probe=3eaaf54d1b) | Sep 28, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [ca9c7bf57b](https://linux-hardware.org/?probe=ca9c7bf57b) | Sep 28, 2022 |
| Lenovo        | G50-70 20351                | [77c0454f45](https://linux-hardware.org/?probe=77c0454f45) | Sep 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [df5fcf14f9](https://linux-hardware.org/?probe=df5fcf14f9) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | [f3c74059d5](https://linux-hardware.org/?probe=f3c74059d5) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [ac296ea23b](https://linux-hardware.org/?probe=ac296ea23b) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | [f4ea1372b7](https://linux-hardware.org/?probe=f4ea1372b7) | Sep 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [dc6d36a0eb](https://linux-hardware.org/?probe=dc6d36a0eb) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | [ae83bec6ad](https://linux-hardware.org/?probe=ae83bec6ad) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | [d2e3e7736c](https://linux-hardware.org/?probe=d2e3e7736c) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [6527be1bb2](https://linux-hardware.org/?probe=6527be1bb2) | Sep 26, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [56e06deea2](https://linux-hardware.org/?probe=56e06deea2) | Sep 26, 2022 |
| MSI           | GF63 8RD                    | [f6ef1dbd07](https://linux-hardware.org/?probe=f6ef1dbd07) | Sep 25, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [2d7ce63bce](https://linux-hardware.org/?probe=2d7ce63bce) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [f844479504](https://linux-hardware.org/?probe=f844479504) | Sep 25, 2022 |
| Dell          | Inspiron 15-3567            | [9ae6efbc0f](https://linux-hardware.org/?probe=9ae6efbc0f) | Sep 25, 2022 |
| HUAWEI        | RLEF-XX                     | [7bab2cbc57](https://linux-hardware.org/?probe=7bab2cbc57) | Sep 25, 2022 |
| MSI           | GF75 Thin 10SC              | [0bda368d15](https://linux-hardware.org/?probe=0bda368d15) | Sep 24, 2022 |
| Dell          | Inspiron 14 5425            | [209be443ac](https://linux-hardware.org/?probe=209be443ac) | Sep 24, 2022 |
| ASUSTek       | G501VW                      | [550d6e5438](https://linux-hardware.org/?probe=550d6e5438) | Sep 24, 2022 |
| Lenovo        | ThinkPad T530 23595JU       | [0adb7bc0b1](https://linux-hardware.org/?probe=0adb7bc0b1) | Sep 24, 2022 |
| VIT           | P2402                       | [0242b6bb07](https://linux-hardware.org/?probe=0242b6bb07) | Sep 24, 2022 |
| Samsung       | 550XBE/350XBE               | [dec88709ee](https://linux-hardware.org/?probe=dec88709ee) | Sep 23, 2022 |
| Google        | Robo                        | [4772493ae3](https://linux-hardware.org/?probe=4772493ae3) | Sep 23, 2022 |
| Samsung       | 550XBE/350XBE               | [e17fb419bd](https://linux-hardware.org/?probe=e17fb419bd) | Sep 23, 2022 |
| MECHREVO      | Jiaolong Series GM5ZG0O     | [077c05c78d](https://linux-hardware.org/?probe=077c05c78d) | Sep 23, 2022 |
| Acer          | Aspire ES1-732              | [d6ccc5301b](https://linux-hardware.org/?probe=d6ccc5301b) | Sep 23, 2022 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [f77dda559d](https://linux-hardware.org/?probe=f77dda559d) | Sep 23, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [412296c83f](https://linux-hardware.org/?probe=412296c83f) | Sep 22, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [db6f733994](https://linux-hardware.org/?probe=db6f733994) | Sep 22, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [21ba0d8f46](https://linux-hardware.org/?probe=21ba0d8f46) | Sep 22, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [0c4627555a](https://linux-hardware.org/?probe=0c4627555a) | Sep 22, 2022 |
| Dell          | Inspiron 5537               | [7e3170527c](https://linux-hardware.org/?probe=7e3170527c) | Sep 22, 2022 |
| HP            | Notebook                    | [18b9221add](https://linux-hardware.org/?probe=18b9221add) | Sep 22, 2022 |
| Toshiba       | Satellite P745              | [963d04c729](https://linux-hardware.org/?probe=963d04c729) | Sep 22, 2022 |
| Dell          | Vostro 15 5510              | [630b3877c4](https://linux-hardware.org/?probe=630b3877c4) | Sep 22, 2022 |
| MSI           | GS60 2PE                    | [1aaaa99706](https://linux-hardware.org/?probe=1aaaa99706) | Sep 22, 2022 |
| HP            | Presario CQ57               | [322f46c499](https://linux-hardware.org/?probe=322f46c499) | Sep 22, 2022 |
| HP            | Stream Notebook PC 13       | [a5dff5d1f6](https://linux-hardware.org/?probe=a5dff5d1f6) | Sep 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5e7597fb17](https://linux-hardware.org/?probe=5e7597fb17) | Sep 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen2... | [87a3d977b1](https://linux-hardware.org/?probe=87a3d977b1) | Sep 22, 2022 |
| Avell High... | B.ON                        | [95c7e35ef3](https://linux-hardware.org/?probe=95c7e35ef3) | Sep 22, 2022 |
| Lenovo        | G50-45 80E3                 | [41af175db4](https://linux-hardware.org/?probe=41af175db4) | Sep 21, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [080fdb990e](https://linux-hardware.org/?probe=080fdb990e) | Sep 21, 2022 |
| Avell High... | B.ON                        | [aaebcf57bb](https://linux-hardware.org/?probe=aaebcf57bb) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | [6fb7c9c27a](https://linux-hardware.org/?probe=6fb7c9c27a) | Sep 21, 2022 |
| Dell          | Precision 7540              | [fb7472fe87](https://linux-hardware.org/?probe=fb7472fe87) | Sep 21, 2022 |
| Dell          | Inspiron MP061              | [8e6955cbf6](https://linux-hardware.org/?probe=8e6955cbf6) | Sep 21, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [0ada4a5b83](https://linux-hardware.org/?probe=0ada4a5b83) | Sep 20, 2022 |
| Lenovo        | ThinkPad T490 20N2001YUS    | [5861c90514](https://linux-hardware.org/?probe=5861c90514) | Sep 20, 2022 |
| HP            | EliteBook 840 14 inch G9... | [450a86c900](https://linux-hardware.org/?probe=450a86c900) | Sep 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f03ae050eb](https://linux-hardware.org/?probe=f03ae050eb) | Sep 20, 2022 |
| Lenovo        | ThinkPad X260 20F5003EMB    | [302eacc4ff](https://linux-hardware.org/?probe=302eacc4ff) | Sep 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | [317ff73ff5](https://linux-hardware.org/?probe=317ff73ff5) | Sep 20, 2022 |
| Chuwi         | CoreBook X                  | [4c963415cd](https://linux-hardware.org/?probe=4c963415cd) | Sep 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [ba7800b231](https://linux-hardware.org/?probe=ba7800b231) | Sep 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0fa5921ddf](https://linux-hardware.org/?probe=0fa5921ddf) | Sep 20, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [d14a12b8ca](https://linux-hardware.org/?probe=d14a12b8ca) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [04252a0991](https://linux-hardware.org/?probe=04252a0991) | Sep 20, 2022 |
| Acer          | TravelMate P414-51          | [2ebd8f21d3](https://linux-hardware.org/?probe=2ebd8f21d3) | Sep 20, 2022 |
| Lenovo        | ThinkPad SL400 2743AQC      | [beb74c65cc](https://linux-hardware.org/?probe=beb74c65cc) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [b415f7be91](https://linux-hardware.org/?probe=b415f7be91) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | [4a7bdd8ed1](https://linux-hardware.org/?probe=4a7bdd8ed1) | Sep 19, 2022 |
| HP            | 15                          | [50f64276d5](https://linux-hardware.org/?probe=50f64276d5) | Sep 19, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [0f049ae5d6](https://linux-hardware.org/?probe=0f049ae5d6) | Sep 19, 2022 |
| HP            | 15                          | [d74a694eb8](https://linux-hardware.org/?probe=d74a694eb8) | Sep 19, 2022 |
| HP            | G42                         | [3f584eb1af](https://linux-hardware.org/?probe=3f584eb1af) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | [46e9732572](https://linux-hardware.org/?probe=46e9732572) | Sep 19, 2022 |
| Panasonic     | CF-53JAWZYDE                | [f8b1ca10d1](https://linux-hardware.org/?probe=f8b1ca10d1) | Sep 19, 2022 |
| Acer          | Aspire A315-23G             | [9e3edc5b61](https://linux-hardware.org/?probe=9e3edc5b61) | Sep 18, 2022 |
| Lenovo        | IdeaPad 720s-13ARR 81BR     | [fa45602fc5](https://linux-hardware.org/?probe=fa45602fc5) | Sep 18, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [b94564300a](https://linux-hardware.org/?probe=b94564300a) | Sep 18, 2022 |
| Dell          | Latitude E6330              | [bbb0a5f1a1](https://linux-hardware.org/?probe=bbb0a5f1a1) | Sep 18, 2022 |
| Dell          | Latitude 3310               | [4de8502362](https://linux-hardware.org/?probe=4de8502362) | Sep 18, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [87c3b99589](https://linux-hardware.org/?probe=87c3b99589) | Sep 18, 2022 |
| Acer          | Aspire A315-23G             | [3de0a6e725](https://linux-hardware.org/?probe=3de0a6e725) | Sep 17, 2022 |
| HP            | Stream Notebook PC 13       | [589078809b](https://linux-hardware.org/?probe=589078809b) | Sep 17, 2022 |
| ASUSTek       | UX430UAR                    | [a265f6053f](https://linux-hardware.org/?probe=a265f6053f) | Sep 17, 2022 |
| Lenovo        | G50-45 80E3                 | [6c5b0c0659](https://linux-hardware.org/?probe=6c5b0c0659) | Sep 17, 2022 |
| Lenovo        | ThinkPad T450s 20BWS21K0... | [1fa176a244](https://linux-hardware.org/?probe=1fa176a244) | Sep 17, 2022 |
| Lenovo        | G50-45 80E3                 | [8c355ea88e](https://linux-hardware.org/?probe=8c355ea88e) | Sep 17, 2022 |
| HP            | Notebook                    | [9fcfcab16e](https://linux-hardware.org/?probe=9fcfcab16e) | Sep 17, 2022 |
| HP            | Unknown                     | [e87c925eb0](https://linux-hardware.org/?probe=e87c925eb0) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | [197ccf755d](https://linux-hardware.org/?probe=197ccf755d) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | [9e7ef8d86d](https://linux-hardware.org/?probe=9e7ef8d86d) | Sep 16, 2022 |
| HUAWEI        | HN-WX9X                     | [6f29359618](https://linux-hardware.org/?probe=6f29359618) | Sep 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [7e865e8b3f](https://linux-hardware.org/?probe=7e865e8b3f) | Sep 16, 2022 |
| Aquarius      | NS585                       | [84054aaa40](https://linux-hardware.org/?probe=84054aaa40) | Sep 16, 2022 |
| HP            | Stream Laptop 11-y0XX       | [b030fff6bb](https://linux-hardware.org/?probe=b030fff6bb) | Sep 16, 2022 |
| Aquarius      | NS585                       | [c4ad74720a](https://linux-hardware.org/?probe=c4ad74720a) | Sep 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [2c97d43674](https://linux-hardware.org/?probe=2c97d43674) | Sep 16, 2022 |
| Chuwi         | CoreBook X                  | [d5a3bc0015](https://linux-hardware.org/?probe=d5a3bc0015) | Sep 16, 2022 |
| Aquarius      | NS585                       | [400485718e](https://linux-hardware.org/?probe=400485718e) | Sep 16, 2022 |
| Lenovo        | G50-45 80E3                 | [59c06bcd6f](https://linux-hardware.org/?probe=59c06bcd6f) | Sep 16, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_11/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.10.0-8-amd64         | 578       | 18.16%  |
| 5.10.0-10-amd64        | 490       | 15.39%  |
| 5.10.0-18-amd64        | 172       | 5.4%    |
| 5.10.0-9-amd64         | 171       | 5.37%   |
| 5.10.0-7-amd64         | 171       | 5.37%   |
| 5.10.0-16-amd64        | 166       | 5.22%   |
| 5.10.0-19-amd64        | 161       | 5.06%   |
| 5.10.0-20-amd64        | 153       | 4.81%   |
| 5.10.0-13-amd64        | 149       | 4.68%   |
| 5.10.0-11-amd64        | 103       | 3.24%   |
| 5.10.0-21-amd64        | 94        | 2.95%   |
| 5.10.0-14-amd64        | 79        | 2.48%   |
| 5.10.0-17-amd64        | 73        | 2.29%   |
| 5.10.0-15-amd64        | 48        | 1.51%   |
| 5.10.0-12-amd64        | 40        | 1.26%   |
| 5.10.0-2-amd64         | 39        | 1.23%   |
| 5.10.0-6-amd64         | 28        | 0.88%   |
| 5.10.0-13-686-pae      | 26        | 0.82%   |
| 5.18.0-0.deb11.4-amd64 | 22        | 0.69%   |
| 6.0.0-0.deb11.2-amd64  | 19        | 0.6%    |
| 5.14.0-0.bpo.2-amd64   | 17        | 0.53%   |
| 5.16.0-0.bpo.4-amd64   | 14        | 0.44%   |
| 5.15.0-2-amd64         | 14        | 0.44%   |
| 5.10.0-3-amd64         | 13        | 0.41%   |
| 5.19.0-0.deb11.2-amd64 | 10        | 0.31%   |
| 5.10.0-9-686-pae       | 9         | 0.28%   |
| 5.10.0-8-686-pae       | 9         | 0.28%   |
| 5.10.0-13-686          | 9         | 0.28%   |
| 6.0.0-0.deb11.6-amd64  | 8         | 0.25%   |
| 5.18.0-0.bpo.1-amd64   | 8         | 0.25%   |
| 5.15.0-0.bpo.2-amd64   | 8         | 0.25%   |
| 5.19.0-2-amd64         | 7         | 0.22%   |
| 5.10.0-9-686           | 7         | 0.22%   |
| 5.19.0-1-amd64         | 6         | 0.19%   |
| 5.18.0-2-amd64         | 6         | 0.19%   |
| 5.17.0-1-amd64         | 5         | 0.16%   |
| 5.10.0-5-amd64         | 5         | 0.16%   |
| 5.10.0-4-amd64         | 5         | 0.16%   |
| 5.10.0-19-686          | 5         | 0.16%   |
| 5.10.0-18-686-pae      | 5         | 0.16%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 2647      | 89.64%  |
| 5.18.0   | 41        | 1.39%   |
| 5.15.0   | 36        | 1.22%   |
| 5.16.0   | 33        | 1.12%   |
| 6.0.0    | 31        | 1.05%   |
| 5.19.0   | 28        | 0.95%   |
| 5.14.0   | 24        | 0.81%   |
| 5.17.0   | 13        | 0.44%   |
| 4.19.0   | 7         | 0.24%   |
| 6.1.0    | 4         | 0.14%   |
| 5.13.19  | 3         | 0.1%    |
| 5.12.0   | 3         | 0.1%    |
| 5.10.60  | 3         | 0.1%    |
| 6.0.2    | 2         | 0.07%   |
| 5.17.5   | 2         | 0.07%   |
| 5.17.11  | 2         | 0.07%   |
| 5.15.35  | 2         | 0.07%   |
| 5.13.8   | 2         | 0.07%   |
| 5.11.0   | 2         | 0.07%   |
| 5.10.92  | 2         | 0.07%   |
| 5.10.109 | 2         | 0.07%   |
| 4.9.0    | 2         | 0.07%   |
| 6.1.9    | 1         | 0.03%   |
| 6.1.5    | 1         | 0.03%   |
| 6.1.12   | 1         | 0.03%   |
| 6.0.11   | 1         | 0.03%   |
| 5.4.157  | 1         | 0.03%   |
| 5.19.9   | 1         | 0.03%   |
| 5.19.17  | 1         | 0.03%   |
| 5.19.10  | 1         | 0.03%   |
| 5.19.1   | 1         | 0.03%   |
| 5.18.6   | 1         | 0.03%   |
| 5.18.15  | 1         | 0.03%   |
| 5.17.4   | 1         | 0.03%   |
| 5.17.14  | 1         | 0.03%   |
| 5.16.5   | 1         | 0.03%   |
| 5.16.15  | 1         | 0.03%   |
| 5.15.8   | 1         | 0.03%   |
| 5.15.75  | 1         | 0.03%   |
| 5.15.74  | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 2663      | 90.3%   |
| 5.15    | 50        | 1.7%    |
| 5.18    | 43        | 1.46%   |
| 5.16    | 35        | 1.19%   |
| 6.0     | 34        | 1.15%   |
| 5.19    | 32        | 1.09%   |
| 5.14    | 29        | 0.98%   |
| 5.17    | 19        | 0.64%   |
| 5.13    | 9         | 0.31%   |
| 4.19    | 9         | 0.31%   |
| 5.12    | 6         | 0.2%    |
| 5.11    | 6         | 0.2%    |
| 6.1     | 5         | 0.17%   |
| 5.1     | 2         | 0.07%   |
| 4.9     | 2         | 0.07%   |
| 5.4     | 1         | 0.03%   |
| 5.15.6  | 1         | 0.03%   |
| 4.14    | 1         | 0.03%   |
| 3.8     | 1         | 0.03%   |
| 3.10    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 2779      | 95.89%  |
| i686    | 115       | 3.97%   |
| armv7l  | 3         | 0.1%    |
| aarch64 | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Unknown           | 961       | 32.64%  |
| GNOME             | 752       | 25.54%  |
| KDE5              | 352       | 11.96%  |
| XFCE              | 332       | 11.28%  |
| MATE              | 100       | 3.4%    |
| LXDE              | 91        | 3.09%   |
| X-Cinnamon        | 87        | 2.96%   |
| Cinnamon          | 75        | 2.55%   |
| i3                | 39        | 1.32%   |
| LXQt              | 37        | 1.26%   |
| KDE               | 32        | 1.09%   |
| GNOME Flashback   | 24        | 0.82%   |
| lightdm-xsession  | 14        | 0.48%   |
| openbox           | 10        | 0.34%   |
| trinity           | 6         | 0.2%    |
| GNOME Classic     | 6         | 0.2%    |
| Cutefish          | 3         | 0.1%    |
| Budgie            | 3         | 0.1%    |
| x-session-manager | 2         | 0.07%   |
| sway              | 2         | 0.07%   |
| ICEWM             | 2         | 0.07%   |
| Enlightenment     | 2         | 0.07%   |
| DWM               | 2         | 0.07%   |
| awesome           | 2         | 0.07%   |
| xmonad            | 1         | 0.03%   |
| wmaker-common     | 1         | 0.03%   |
| matchbox          | 1         | 0.03%   |
| jwm               | 1         | 0.03%   |
| fluxbox           | 1         | 0.03%   |
| default           | 1         | 0.03%   |
| Deepin            | 1         | 0.03%   |
| BunsenLabs        | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 1382      | 47.01%  |
| Unknown     | 886       | 30.14%  |
| Wayland     | 564       | 19.18%  |
| Tty         | 105       | 3.57%   |
| Unspecified | 2         | 0.07%   |
| Web         | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1290      | 43.92%  |
| GDM     | 646       | 22%     |
| LightDM | 536       | 18.25%  |
| SDDM    | 323       | 11%     |
| TDM     | 70        | 2.38%   |
| GDM3    | 58        | 1.97%   |
| XDM     | 5         | 0.17%   |
| SLiM    | 3         | 0.1%    |
| LXDM    | 3         | 0.1%    |
| NODM    | 1         | 0.03%   |
| Ly      | 1         | 0.03%   |
| KDM     | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 862       | 29.42%  |
| Unknown | 702       | 23.96%  |
| ru_RU   | 238       | 8.12%   |
| de_DE   | 158       | 5.39%   |
| fr_FR   | 143       | 4.88%   |
| en_GB   | 124       | 4.23%   |
| es_ES   | 97        | 3.31%   |
| it_IT   | 76        | 2.59%   |
| pt_BR   | 67        | 2.29%   |
| pl_PL   | 64        | 2.18%   |
| en_CA   | 29        | 0.99%   |
| es_MX   | 28        | 0.96%   |
| en_AU   | 25        | 0.85%   |
| zh_CN   | 19        | 0.65%   |
| en_IN   | 19        | 0.65%   |
| es_AR   | 17        | 0.58%   |
| C       | 17        | 0.58%   |
| hu_HU   | 14        | 0.48%   |
| es_CL   | 12        | 0.41%   |
| en_IE   | 11        | 0.38%   |
| es_VE   | 10        | 0.34%   |
| de_CH   | 10        | 0.34%   |
| pt_PT   | 9         | 0.31%   |
| nl_NL   | 9         | 0.31%   |
| ja_JP   | 9         | 0.31%   |
| fi_FI   | 9         | 0.31%   |
| sv_SE   | 8         | 0.27%   |
| de_AT   | 8         | 0.27%   |
| tr_TR   | 7         | 0.24%   |
| ko_KR   | 7         | 0.24%   |
| cs_CZ   | 7         | 0.24%   |
| nb_NO   | 6         | 0.2%    |
| fr_BE   | 6         | 0.2%    |
| es_CO   | 6         | 0.2%    |
| en_SG   | 6         | 0.2%    |
| zh_TW   | 5         | 0.17%   |
| en_ZA   | 5         | 0.17%   |
| en_NZ   | 5         | 0.17%   |
| uk_UA   | 4         | 0.14%   |
| es_PE   | 4         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1980      | 67.85%  |
| BIOS | 938       | 32.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1804      | 62.08%  |
| Overlay | 972       | 33.45%  |
| Btrfs   | 77        | 2.65%   |
| Xfs     | 25        | 0.86%   |
| Zfs     | 11        | 0.38%   |
| Tmpfs   | 7         | 0.24%   |
| Ext2    | 3         | 0.1%    |
| Unknown | 3         | 0.1%    |
| Ext3    | 2         | 0.07%   |
| Rootfs  | 1         | 0.03%   |
| Aufs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2003      | 68.41%  |
| MBR     | 529       | 18.07%  |
| Unknown | 396       | 13.52%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2289      | 78.39%  |
| Yes       | 631       | 21.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2171      | 74.22%  |
| Yes       | 754       | 25.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 593       | 20.47%  |
| Apple                          | 572       | 19.74%  |
| Hewlett-Packard                | 401       | 13.84%  |
| Dell                           | 346       | 11.94%  |
| ASUSTek Computer               | 251       | 8.66%   |
| Acer                           | 169       | 5.83%   |
| Google                         | 131       | 4.52%   |
| Aquarius                       | 44        | 1.52%   |
| MSI                            | 43        | 1.48%   |
| Toshiba                        | 39        | 1.35%   |
| Samsung Electronics            | 35        | 1.21%   |
| HUAWEI                         | 26        | 0.9%    |
| Unknown                        | 23        | 0.79%   |
| Sony                           | 18        | 0.62%   |
| Notebook                       | 17        | 0.59%   |
| Fujitsu                        | 13        | 0.45%   |
| Packard Bell                   | 10        | 0.35%   |
| Panasonic                      | 9         | 0.31%   |
| Clevo                          | 7         | 0.24%   |
| Timi                           | 6         | 0.21%   |
| Medion                         | 6         | 0.21%   |
| IBM                            | 6         | 0.21%   |
| GPU Company                    | 6         | 0.21%   |
| TUXEDO                         | 5         | 0.17%   |
| SLIMBOOK                       | 5         | 0.17%   |
| Intel                          | 5         | 0.17%   |
| Gigabyte Technology            | 5         | 0.17%   |
| Positivo                       | 4         | 0.14%   |
| LG Electronics                 | 4         | 0.14%   |
| HONOR                          | 4         | 0.14%   |
| Fujitsu Siemens                | 4         | 0.14%   |
| Alienware                      | 4         | 0.14%   |
| System76                       | 3         | 0.1%    |
| SmbiosType1_SystemManufacturer | 3         | 0.1%    |
| PC Specialist                  | 3         | 0.1%    |
| Avell High Performance         | 3         | 0.1%    |
| Shanghai Zhaoxin Semiconductor | 2         | 0.07%   |
| Razer                          | 2         | 0.07%   |
| Jumper                         | 2         | 0.07%   |
| Insyde                         | 2         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBook5,2                      | 306       | 10.56%  |
| Apple MacBookAir7,1                   | 77        | 2.66%   |
| Apple MacBookAir7,2                   | 76        | 2.62%   |
| Google Enguarde                       | 74        | 2.55%   |
| Apple MacBook2,1                      | 55        | 1.9%    |
| Aquarius NS585                        | 44        | 1.52%   |
| Unknown                               | 28        | 0.97%   |
| Lenovo ThinkPad E475 20H40006US       | 24        | 0.83%   |
| Google Terra                          | 23        | 0.79%   |
| Apple MacBook4,1                      | 21        | 0.72%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US | 16        | 0.55%   |
| Acer Aspire A315-23                   | 15        | 0.52%   |
| HP Notebook                           | 14        | 0.48%   |
| ASUS 1005HA                           | 14        | 0.48%   |
| HP Pavilion g6                        | 12        | 0.41%   |
| Google Reks                           | 11        | 0.38%   |
| HP EliteBook 8460p                    | 9         | 0.31%   |
| HP Laptop 15-db0xxx                   | 8         | 0.28%   |
| Dell Latitude E7440                   | 8         | 0.28%   |
| Samsung 300E4C/300E5C/300E7C          | 7         | 0.24%   |
| HP Laptop 15-bw0xx                    | 7         | 0.24%   |
| Dell Latitude E6330                   | 7         | 0.24%   |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 6         | 0.21%   |
| HP Laptop 15-db1xxx                   | 6         | 0.21%   |
| HP 250 G7 Notebook PC                 | 6         | 0.21%   |
| Dell XPS 13 9310                      | 6         | 0.21%   |
| Dell Latitude 7480                    | 6         | 0.21%   |
| Dell Inspiron 5100                    | 6         | 0.21%   |
| Apple MacBook7,1                      | 6         | 0.21%   |
| HUAWEI NBLK-WAX9X                     | 5         | 0.17%   |
| HP Pavilion Gaming Laptop 15-ec2xxx   | 5         | 0.17%   |
| HP EliteBook 840 G8 Notebook PC       | 5         | 0.17%   |
| HP EliteBook 840 G3                   | 5         | 0.17%   |
| HP 255 G8 Notebook PC                 | 5         | 0.17%   |
| Dell Latitude E6520                   | 5         | 0.17%   |
| Dell Latitude E6420                   | 5         | 0.17%   |
| Dell Latitude 5420                    | 5         | 0.17%   |
| Dell Inspiron 15-3567                 | 5         | 0.17%   |
| Acer Aspire A515-56                   | 5         | 0.17%   |
| Lenovo ThinkPad T490 20N2CTO1WW       | 4         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 402       | 13.88%  |
| Apple MacBook5    | 306       | 10.56%  |
| Apple MacBookAir7 | 153       | 5.28%   |
| Dell Latitude     | 140       | 4.83%   |
| Acer Aspire       | 113       | 3.9%    |
| Dell Inspiron     | 104       | 3.59%   |
| Lenovo IdeaPad    | 95        | 3.28%   |
| HP EliteBook      | 77        | 2.66%   |
| Google Enguarde   | 74        | 2.55%   |
| HP Pavilion       | 59        | 2.04%   |
| HP Laptop         | 58        | 2%      |
| Apple MacBook2    | 55        | 1.9%    |
| HP ProBook        | 51        | 1.76%   |
| Aquarius NS585    | 44        | 1.52%   |
| ASUS VivoBook     | 39        | 1.35%   |
| Dell XPS          | 38        | 1.31%   |
| Toshiba Satellite | 32        | 1.1%    |
| HP Compaq         | 28        | 0.97%   |
| Unknown           | 28        | 0.97%   |
| Dell Vostro       | 27        | 0.93%   |
| Dell Precision    | 25        | 0.86%   |
| Google Terra      | 23        | 0.79%   |
| ASUS ZenBook      | 21        | 0.72%   |
| ASUS ASUS         | 21        | 0.72%   |
| Apple MacBook4    | 21        | 0.72%   |
| HP ZBook          | 20        | 0.69%   |
| HP 250            | 18        | 0.62%   |
| HP Notebook       | 14        | 0.48%   |
| ASUS 1005HA       | 14        | 0.48%   |
| Acer Nitro        | 14        | 0.48%   |
| Lenovo Legion     | 13        | 0.45%   |
| Acer Swift        | 13        | 0.45%   |
| Lenovo ThinkBook  | 12        | 0.41%   |
| ASUS ROG          | 12        | 0.41%   |
| Acer TravelMate   | 12        | 0.41%   |
| HP Stream         | 11        | 0.38%   |
| HP ENVY           | 11        | 0.38%   |
| HP 255            | 11        | 0.38%   |
| Google Reks       | 11        | 0.38%   |
| Fujitsu LIFEBOOK  | 11        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2009    | 375       | 12.94%  |
| 2021    | 296       | 10.22%  |
| 2019    | 288       | 9.94%   |
| 2020    | 279       | 9.63%   |
| 2016    | 188       | 6.49%   |
| 2015    | 186       | 6.42%   |
| 2012    | 169       | 5.83%   |
| 2018    | 156       | 5.38%   |
| 2017    | 150       | 5.18%   |
| 2011    | 143       | 4.94%   |
| 2013    | 129       | 4.45%   |
| 2022    | 117       | 4.04%   |
| 2014    | 107       | 3.69%   |
| 2007    | 94        | 3.24%   |
| 2010    | 85        | 2.93%   |
| 2008    | 76        | 2.62%   |
| 2006    | 21        | 0.72%   |
| 2005    | 18        | 0.62%   |
| 2003    | 9         | 0.31%   |
| 2004    | 6         | 0.21%   |
| Unknown | 3         | 0.1%    |
| 2023    | 1         | 0.03%   |
| 2002    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2897      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2668      | 91.75%  |
| Enabled  | 240       | 8.25%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2763      | 95.34%  |
| Yes  | 135       | 4.66%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 788       | 27.05%  |
| 3.01-4.0    | 574       | 19.7%   |
| 1.01-2.0    | 454       | 15.59%  |
| 16.01-24.0  | 417       | 14.32%  |
| 8.01-16.0   | 353       | 12.12%  |
| 32.01-64.0  | 144       | 4.94%   |
| 2.01-3.0    | 61        | 2.09%   |
| 0.51-1.0    | 52        | 1.79%   |
| 64.01-256.0 | 31        | 1.06%   |
| 24.01-32.0  | 27        | 0.93%   |
| 0.01-0.5    | 11        | 0.38%   |
| Unknown     | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1354      | 44.55%  |
| 2.01-3.0   | 568       | 18.69%  |
| 0.51-1.0   | 338       | 11.12%  |
| 4.01-8.0   | 319       | 10.5%   |
| 3.01-4.0   | 280       | 9.21%   |
| 8.01-16.0  | 85        | 2.8%    |
| 0.01-0.5   | 84        | 2.76%   |
| 16.01-24.0 | 5         | 0.16%   |
| 32.01-64.0 | 2         | 0.07%   |
| 24.01-32.0 | 2         | 0.07%   |
| Unknown    | 2         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2399      | 82.05%  |
| 2      | 448       | 15.32%  |
| 3      | 44        | 1.5%    |
| 0      | 20        | 0.68%   |
| 4      | 10        | 0.34%   |
| 5      | 2         | 0.07%   |
| 7      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1868      | 64.37%  |
| Yes       | 1034      | 35.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2305      | 79.4%   |
| No        | 598       | 20.6%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2835      | 97.79%  |
| No        | 64        | 2.21%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2393      | 82.23%  |
| No        | 517       | 17.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 1006      | 34.61%  |
| Russia      | 252       | 8.67%   |
| Germany     | 225       | 7.74%   |
| France      | 175       | 6.02%   |
| Spain       | 123       | 4.23%   |
| Brazil      | 94        | 3.23%   |
| Italy       | 90        | 3.1%    |
| Poland      | 84        | 2.89%   |
| UK          | 64        | 2.2%    |
| Netherlands | 48        | 1.65%   |
| Canada      | 43        | 1.48%   |
| Mexico      | 38        | 1.31%   |
| Switzerland | 32        | 1.1%    |
| China       | 30        | 1.03%   |
| Sweden      | 29        | 1%      |
| Argentina   | 29        | 1%      |
| Australia   | 28        | 0.96%   |
| India       | 25        | 0.86%   |
| Turkey      | 23        | 0.79%   |
| Hungary     | 23        | 0.79%   |
| Ukraine     | 22        | 0.76%   |
| Portugal    | 19        | 0.65%   |
| Belgium     | 19        | 0.65%   |
| Finland     | 18        | 0.62%   |
| Czechia     | 17        | 0.58%   |
| Austria     | 17        | 0.58%   |
| Norway      | 16        | 0.55%   |
| Greece      | 15        | 0.52%   |
| Chile       | 14        | 0.48%   |
| Romania     | 13        | 0.45%   |
| Japan       | 13        | 0.45%   |
| Venezuela   | 12        | 0.41%   |
| Colombia    | 12        | 0.41%   |
| Ireland     | 11        | 0.38%   |
| Indonesia   | 11        | 0.38%   |
| Bulgaria    | 11        | 0.38%   |
| Croatia     | 10        | 0.34%   |
| Thailand    | 8         | 0.28%   |
| Slovenia    | 8         | 0.28%   |
| New Zealand | 8         | 0.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Bangor            | 567       | 18.68%  |
| Dover-Foxcroft    | 229       | 7.55%   |
| Voronezh          | 140       | 4.61%   |
| Seville           | 35        | 1.15%   |
| Paris             | 31        | 1.02%   |
| St Petersburg     | 28        | 0.92%   |
| Berlin            | 24        | 0.79%   |
| Madrid            | 23        | 0.76%   |
| Warsaw            | 20        | 0.66%   |
| Munich            | 19        | 0.63%   |
| Moscow            | 19        | 0.63%   |
| Barcelona         | 15        | 0.49%   |
| Amsterdam         | 15        | 0.49%   |
| Milan             | 14        | 0.46%   |
| London            | 13        | 0.43%   |
| Vienna            | 12        | 0.4%    |
| Sao Paulo         | 11        | 0.36%   |
| Blizniew          | 11        | 0.36%   |
| Istanbul          | 10        | 0.33%   |
| Frankfurt am Main | 10        | 0.33%   |
| Zagreb            | 9         | 0.3%    |
| Toronto           | 9         | 0.3%    |
| Sydney            | 9         | 0.3%    |
| Prague            | 9         | 0.3%    |
| Perm              | 9         | 0.3%    |
| Helsinki          | 9         | 0.3%    |
| Athens            | 9         | 0.3%    |
| Mesa              | 8         | 0.26%   |
| Lyon              | 8         | 0.26%   |
| Hamburg           | 8         | 0.26%   |
| Dublin            | 8         | 0.26%   |
| San Jose          | 7         | 0.23%   |
| Natal             | 7         | 0.23%   |
| Mexico City       | 7         | 0.23%   |
| Iasi              | 7         | 0.23%   |
| Budapest          | 7         | 0.23%   |
| Brisbane          | 7         | 0.23%   |
| Yekaterinburg     | 6         | 0.2%    |
| Seocho-gu         | 6         | 0.2%    |
| Rome              | 6         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 452       | 548    | 13.4%   |
| WDC                       | 334       | 400    | 9.91%   |
| Seagate                   | 268       | 313    | 7.95%   |
| Toshiba                   | 259       | 278    | 7.68%   |
| Unknown                   | 241       | 301    | 7.15%   |
| Fujitsu                   | 240       | 244    | 7.12%   |
| Kingston                  | 187       | 228    | 5.55%   |
| Apple                     | 170       | 199    | 5.04%   |
| SanDisk                   | 151       | 181    | 4.48%   |
| Crucial                   | 130       | 150    | 3.86%   |
| SK hynix                  | 122       | 136    | 3.62%   |
| Hitachi                   | 93        | 107    | 2.76%   |
| A-DATA Technology         | 91        | 175    | 2.7%    |
| Intel                     | 79        | 88     | 2.34%   |
| Micron Technology         | 77        | 79     | 2.28%   |
| HGST                      | 52        | 65     | 1.54%   |
| KIOXIA                    | 38        | 42     | 1.13%   |
| China                     | 25        | 26     | 0.74%   |
| Unknown                   | 24        | 24     | 0.71%   |
| LITEON                    | 21        | 24     | 0.62%   |
| SABRENT                   | 17        | 18     | 0.5%    |
| Transcend                 | 16        | 22     | 0.47%   |
| Phison                    | 14        | 18     | 0.42%   |
| SPCC                      | 13        | 14     | 0.39%   |
| Silicon Motion            | 13        | 15     | 0.39%   |
| Intenso                   | 13        | 16     | 0.39%   |
| PNY                       | 12        | 12     | 0.36%   |
| LITEONIT                  | 12        | 14     | 0.36%   |
| GOODRAM                   | 11        | 12     | 0.33%   |
| Patriot                   | 8         | 8      | 0.24%   |
| Team                      | 7         | 7      | 0.21%   |
| SSSTC                     | 7         | 7      | 0.21%   |
| JMicron Technology        | 7         | 7      | 0.21%   |
| Netac                     | 6         | 6      | 0.18%   |
| Lenovo                    | 6         | 7      | 0.18%   |
| Apacer                    | 6         | 6      | 0.18%   |
| UMIS                      | 5         | 9      | 0.15%   |
| Micron/Crucial Technology | 5         | 5      | 0.15%   |
| KIOXIA-EXCERIA            | 5         | 6      | 0.15%   |
| ASMT                      | 5         | 6      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB     | 202       | 5.87%   |
| Apple SSD AP0128H 121GB            | 77        | 2.24%   |
| Apple SSD SM0128G 121GB            | 70        | 2.03%   |
| Toshiba MK1655GSXF 160GB           | 46        | 1.34%   |
| A-DATA SU800 512GB SSD             | 44        | 1.28%   |
| Toshiba MK1653GSX 160GB            | 43        | 1.25%   |
| Unknown AGND3R  16GB               | 39        | 1.13%   |
| Kingston SA400S37240G 240GB SSD    | 39        | 1.13%   |
| Seagate ST1000LM035-1RK172 1TB     | 38        | 1.1%    |
| Kingston SA400S37120G 120GB SSD    | 34        | 0.99%   |
| Unknown HAG2e  16GB                | 30        | 0.87%   |
| Unknown SDW16G  16GB               | 25        | 0.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 25        | 0.73%   |
| Unknown                            | 24        | 0.7%    |
| Toshiba MQ01ABF050 500GB           | 22        | 0.64%   |
| Toshiba MQ04ABF100 1TB             | 20        | 0.58%   |
| Crucial CT500MX500SSD1 500GB       | 20        | 0.58%   |
| Samsung SSD 860 EVO 500GB          | 19        | 0.55%   |
| HGST HTS721010A9E630 1TB           | 19        | 0.55%   |
| Unknown MMC Card  32GB             | 17        | 0.49%   |
| SABRENT Disk 256GB                 | 17        | 0.49%   |
| Crucial CT1000MX500SSD1 1TB        | 17        | 0.49%   |
| WDC WD1600BUDT-63DPZY0 160GB       | 16        | 0.47%   |
| Samsung SSD 970 EVO Plus 1TB       | 16        | 0.47%   |
| Kingston SV300S37A120G 120GB SSD   | 16        | 0.47%   |
| Toshiba MQ01ABD100 1TB             | 14        | 0.41%   |
| Seagate ST500LT012-1DG142 500GB    | 14        | 0.41%   |
| SanDisk SD8SBAT128G1122 128GB SSD  | 14        | 0.41%   |
| Samsung SSD 860 EVO 250GB          | 12        | 0.35%   |
| Intel SSDPEKNW512G8 512GB          | 12        | 0.35%   |
| Seagate ST980811AS 80GB            | 11        | 0.32%   |
| Samsung SSD 980 1TB                | 11        | 0.32%   |
| Kingston SA400S37480G 480GB SSD    | 11        | 0.32%   |
| Fujitsu MHY2120BH 120GB            | 11        | 0.32%   |
| WDC WD10SPZX-24Z10 1TB             | 10        | 0.29%   |
| Samsung SSD 850 EVO 500GB          | 10        | 0.29%   |
| Samsung MZVLB512HBJQ-000L7 512GB   | 10        | 0.29%   |
| HGST HTS725050A7E630 500GB         | 10        | 0.29%   |
| HGST HTS541010A9E680 1TB           | 10        | 0.29%   |
| Crucial CT240BX500SSD1 240GB       | 10        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 257       | 300    | 23.66%  |
| Fujitsu             | 240       | 244    | 22.1%   |
| Toshiba             | 206       | 219    | 18.97%  |
| WDC                 | 184       | 205    | 16.94%  |
| Hitachi             | 93        | 107    | 8.56%   |
| HGST                | 52        | 65     | 4.79%   |
| SABRENT             | 17        | 18     | 1.57%   |
| Samsung Electronics | 14        | 15     | 1.29%   |
| Unknown             | 9         | 12     | 0.83%   |
| JMicron Technology  | 5         | 5      | 0.46%   |
| Intenso             | 2         | 2      | 0.18%   |
| USB3.0              | 1         | 1      | 0.09%   |
| Unknown (CF)        | 1         | 1      | 0.09%   |
| SILICONMOTION       | 1         | 1      | 0.09%   |
| Maxone              | 1         | 1      | 0.09%   |
| IBM/Hitachi         | 1         | 1      | 0.09%   |
| ASMT109x            | 1         | 1      | 0.09%   |
| ASMT                | 1         | 2      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 203       | 242    | 19.1%   |
| Kingston            | 145       | 184    | 13.64%  |
| Crucial             | 113       | 130    | 10.63%  |
| SanDisk             | 105       | 130    | 9.88%   |
| Apple               | 88        | 95     | 8.28%   |
| A-DATA Technology   | 67        | 139    | 6.3%    |
| WDC                 | 34        | 48     | 3.2%    |
| Micron Technology   | 28        | 29     | 2.63%   |
| China               | 25        | 26     | 2.35%   |
| Intel               | 21        | 23     | 1.98%   |
| SK hynix            | 20        | 25     | 1.88%   |
| LITEON              | 17        | 19     | 1.6%    |
| Transcend           | 15        | 21     | 1.41%   |
| Toshiba             | 15        | 16     | 1.41%   |
| LITEONIT            | 12        | 14     | 1.13%   |
| PNY                 | 11        | 11     | 1.03%   |
| SPCC                | 10        | 11     | 0.94%   |
| Intenso             | 10        | 13     | 0.94%   |
| Patriot             | 8         | 8      | 0.75%   |
| GOODRAM             | 8         | 9      | 0.75%   |
| Team                | 6         | 6      | 0.56%   |
| Netac               | 6         | 6      | 0.56%   |
| Apacer              | 5         | 5      | 0.47%   |
| Unknown             | 5         | 5      | 0.47%   |
| Plextor             | 4         | 4      | 0.38%   |
| Lexar               | 4         | 5      | 0.38%   |
| ASMT                | 4         | 4      | 0.38%   |
| ZTC                 | 3         | 4      | 0.28%   |
| Seagate             | 3         | 3      | 0.28%   |
| OCZ                 | 3         | 3      | 0.28%   |
| KIOXIA-EXCERIA      | 3         | 4      | 0.28%   |
| KingDian            | 3         | 3      | 0.28%   |
| Dogfish             | 3         | 5      | 0.28%   |
| XrayDisk            | 2         | 2      | 0.19%   |
| Unknown             | 2         | 2      | 0.19%   |
| LDLC                | 2         | 2      | 0.19%   |
| Kingchuxing         | 2         | 2      | 0.19%   |
| FORESEE             | 2         | 2      | 0.19%   |
| Fanxiang            | 2         | 2      | 0.19%   |
| Corsair             | 2         | 2      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1056      | 1200   | 32.5%   |
| SSD     | 1007      | 1315   | 30.99%  |
| NVMe    | 895       | 1102   | 27.55%  |
| MMC     | 261       | 318    | 8.03%   |
| Unknown | 30        | 32     | 0.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1893      | 2422   | 60.17%  |
| NVMe | 894       | 1100   | 28.42%  |
| MMC  | 261       | 318    | 8.3%    |
| SAS  | 98        | 127    | 3.12%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1531      | 1857   | 75.27%  |
| 0.51-1.0   | 448       | 591    | 22.03%  |
| 1.01-2.0   | 39        | 47     | 1.92%   |
| 4.01-10.0  | 10        | 13     | 0.49%   |
| 3.01-4.0   | 4         | 4      | 0.2%    |
| 2.01-3.0   | 2         | 3      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 837       | 28.04%  |
| Unknown        | 681       | 22.81%  |
| 251-500        | 513       | 17.19%  |
| 501-1000       | 317       | 10.62%  |
| 1-20           | 187       | 6.26%   |
| 51-100         | 173       | 5.8%    |
| 1001-2000      | 125       | 4.19%   |
| 21-50          | 95        | 3.18%   |
| 2001-3000      | 32        | 1.07%   |
| More than 3000 | 25        | 0.84%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1147      | 37.67%  |
| Unknown        | 681       | 22.36%  |
| 21-50          | 321       | 10.54%  |
| 101-250        | 293       | 9.62%   |
| 51-100         | 277       | 9.1%    |
| 251-500        | 170       | 5.58%   |
| 501-1000       | 99        | 3.25%   |
| 1001-2000      | 33        | 1.08%   |
| 0              | 10        | 0.33%   |
| More than 3000 | 9         | 0.3%    |
| 2001-3000      | 5         | 0.16%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB                      | 20        | 20     | 6.99%   |
| Toshiba MK1653GSX 160GB                             | 9         | 9      | 3.15%   |
| Toshiba MK1655GSXF 160GB                            | 7         | 7      | 2.45%   |
| Seagate ST9500325AS 500GB                           | 7         | 7      | 2.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 7         | 8      | 2.45%   |
| Hitachi HTS543216L9SA02 160GB                       | 6         | 6      | 2.1%    |
| Seagate ST9500420AS 500GB                           | 5         | 5      | 1.75%   |
| Hitachi HTS542512K9SA00 120GB                       | 5         | 6      | 1.75%   |
| WDC WD1600BUDT-63DPZY0 160GB                        | 4         | 4      | 1.4%    |
| Seagate ST500LM021-1KJ152 500GB                     | 4         | 4      | 1.4%    |
| Hitachi HTS545050B9A300 500GB                       | 4         | 4      | 1.4%    |
| HGST HTS541010A9E680 1TB                            | 4         | 4      | 1.4%    |
| SK hynix PC711 HFS512GDE9X073N 512GB                | 3         | 3      | 1.05%   |
| Seagate ST500LT012-9WS142 500GB                     | 3         | 3      | 1.05%   |
| Seagate ST500LT012-1DG142 500GB                     | 3         | 3      | 1.05%   |
| Seagate ST500LM000-SSHD-8GB                         | 3         | 3      | 1.05%   |
| Hitachi HTS547575A9E384 752GB                       | 3         | 3      | 1.05%   |
| HGST HTS725050A7E630 500GB                          | 3         | 4      | 1.05%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 2         | 2      | 0.7%    |
| WDC WD10SPZX-60Z10T0 1TB                            | 2         | 3      | 0.7%    |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 2      | 0.7%    |
| Toshiba MQ04ABF100 1TB                              | 2         | 2      | 0.7%    |
| Toshiba MQ01ABF050 500GB                            | 2         | 2      | 0.7%    |
| SK hynix SH920 mSATA 128GB SSD                      | 2         | 2      | 0.7%    |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 2         | 2      | 0.7%    |
| SK hynix HFS256G39MND-2300A 256GB SSD               | 2         | 2      | 0.7%    |
| Seagate ST980811AS 80GB                             | 2         | 2      | 0.7%    |
| Seagate ST94811A 40GB                               | 2         | 2      | 0.7%    |
| Seagate ST9320325AS 320GB                           | 2         | 2      | 0.7%    |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 2      | 0.7%    |
| Samsung Electronics HM100JC 100GB                   | 2         | 2      | 0.7%    |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 2         | 2      | 0.7%    |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 2      | 0.7%    |
| Kingston SA400S37240G 240GB SSD                     | 2         | 2      | 0.7%    |
| Hitachi HTS545032B9A300 320GB                       | 2         | 4      | 0.7%    |
| Hitachi HTS543225L9A300 250GB                       | 2         | 2      | 0.7%    |
| Hitachi HTS542516K9SA00 160GB                       | 2         | 2      | 0.7%    |
| Hitachi HTS541060G9AT00 64GB                        | 2         | 3      | 0.7%    |
| Hitachi HTS541010G9SA00 100GB                       | 2         | 2      | 0.7%    |
| HGST HTS721010A9E630 1TB                            | 2         | 3      | 0.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 60        | 64     | 21.05%  |
| Hitachi             | 45        | 50     | 15.79%  |
| Toshiba             | 30        | 31     | 10.53%  |
| Fujitsu             | 28        | 28     | 9.82%   |
| WDC                 | 24        | 26     | 8.42%   |
| Samsung Electronics | 15        | 16     | 5.26%   |
| HGST                | 15        | 17     | 5.26%   |
| SK hynix            | 14        | 14     | 4.91%   |
| Kingston            | 10        | 10     | 3.51%   |
| Micron Technology   | 9         | 9      | 3.16%   |
| Intel               | 8         | 9      | 2.81%   |
| Crucial             | 5         | 5      | 1.75%   |
| SanDisk             | 4         | 5      | 1.4%    |
| A-DATA Technology   | 4         | 4      | 1.4%    |
| LITEONIT            | 3         | 4      | 1.05%   |
| LITEON              | 3         | 3      | 1.05%   |
| Unknown             | 2         | 2      | 0.7%    |
| ShiJi               | 1         | 1      | 0.35%   |
| Plextor             | 1         | 1      | 0.35%   |
| Lenovo              | 1         | 1      | 0.35%   |
| IBM/Hitachi         | 1         | 1      | 0.35%   |
| GOODRAM             | 1         | 1      | 0.35%   |
| DGM                 | 1         | 1      | 0.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 60        | 64     | 28.71%  |
| Hitachi             | 45        | 50     | 21.53%  |
| Toshiba             | 30        | 31     | 14.35%  |
| Fujitsu             | 28        | 28     | 13.4%   |
| WDC                 | 24        | 26     | 11.48%  |
| HGST                | 15        | 17     | 7.18%   |
| Samsung Electronics | 6         | 6      | 2.87%   |
| IBM/Hitachi         | 1         | 1      | 0.48%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 209       | 223    | 73.33%  |
| SSD  | 63        | 67     | 22.11%  |
| NVMe | 13        | 13     | 4.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 16.67%  |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 16.67%  |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 16.67%  |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 16.67%  |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 16.67%  |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 33.33%  |
| Samsung Electronics | 2         | 2      | 33.33%  |
| WDC                 | 1         | 1      | 16.67%  |
| Hitachi             | 1         | 2      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2092      | 2669   | 68.17%  |
| Detected | 687       | 987    | 22.39%  |
| Malfunc  | 283       | 303    | 9.22%   |
| Failed   | 6         | 7      | 0.2%    |
| Limited  | 1         | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1603      | 50.49%  |
| Samsung Electronics              | 321       | 10.11%  |
| Nvidia                           | 319       | 10.05%  |
| AMD                              | 278       | 8.76%   |
| SanDisk                          | 153       | 4.82%   |
| SK hynix                         | 97        | 3.06%   |
| Apple                            | 82        | 2.58%   |
| Micron Technology                | 49        | 1.54%   |
| Kingston Technology Company      | 42        | 1.32%   |
| Toshiba America Info Systems     | 41        | 1.29%   |
| KIOXIA                           | 39        | 1.23%   |
| ADATA Technology                 | 27        | 0.85%   |
| Phison Electronics               | 23        | 0.72%   |
| Silicon Motion                   | 22        | 0.69%   |
| Micron/Crucial Technology        | 21        | 0.66%   |
| Solid State Storage Technology   | 12        | 0.38%   |
| Union Memory (Shenzhen)          | 8         | 0.25%   |
| Shenzhen Longsys Electronics     | 4         | 0.13%   |
| Realtek Semiconductor            | 4         | 0.13%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.13%   |
| Lite-On Technology               | 4         | 0.13%   |
| Lenovo                           | 4         | 0.13%   |
| ULi Electronics                  | 3         | 0.09%   |
| Silicon Integrated Systems [SiS] | 3         | 0.09%   |
| Marvell Technology Group         | 2         | 0.06%   |
| Jiangsu Huacun Elec.             | 2         | 0.06%   |
| ASMedia Technology               | 2         | 0.06%   |
| Yangtze Memory Technologies      | 1         | 0.03%   |
| VIA Technologies                 | 1         | 0.03%   |
| Silicon Image                    | 1         | 0.03%   |
| JMicron Technology               | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |
| Unknown                          | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Nvidia MCP79 AHCI Controller                                                   | 311       | 9.1%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 249       | 7.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 193       | 5.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 184       | 5.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 124       | 3.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 113       | 3.31%   |
| Intel Volume Management Device NVMe RAID Controller                            | 101       | 2.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 93        | 2.72%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 86        | 2.52%   |
| Samsung Electronics SATA controller                                            | 79        | 2.31%   |
| Apple S1X NVMe Controller                                                      | 78        | 2.28%   |
| Samsung NVMe SSD Controller 980                                                | 73        | 2.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 73        | 2.14%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 70        | 2.05%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 62        | 1.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 56        | 1.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 55        | 1.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 52        | 1.52%   |
| Micron Non-Volatile memory controller                                          | 49        | 1.43%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 47        | 1.38%   |
| Intel Tiger Lake-LP SATA Controller                                            | 46        | 1.35%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 44        | 1.29%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 44        | 1.29%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 44        | 1.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 41        | 1.2%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 40        | 1.17%   |
| Intel Comet Lake SATA AHCI Controller                                          | 39        | 1.14%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 34        | 0.99%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 33        | 0.97%   |
| Intel SSD 660P Series                                                          | 33        | 0.97%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 33        | 0.97%   |
| SanDisk Non-Volatile memory controller                                         | 32        | 0.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 29        | 0.85%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 28        | 0.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 26        | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 25        | 0.73%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 25        | 0.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 23        | 0.67%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 20        | 0.59%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 20        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1971      | 59.15%  |
| NVMe | 895       | 26.86%  |
| IDE  | 246       | 7.38%   |
| RAID | 220       | 6.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2488      | 85.85%  |
| AMD          | 403       | 13.91%  |
| ARM          | 4         | 0.14%   |
| CentaurHauls | 3         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 308       | 10.62%  |
| Intel Core i5-5250U CPU @ 1.60GHz             | 146       | 5.03%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 88        | 3.03%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 62        | 2.14%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 59        | 2.03%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 55        | 1.9%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 53        | 1.83%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 44        | 1.52%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 41        | 1.41%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 38        | 1.31%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 35        | 1.21%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 33        | 1.14%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 32        | 1.1%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 31        | 1.07%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 26        | 0.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 26        | 0.9%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 24        | 0.83%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 24        | 0.83%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 24        | 0.83%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 24        | 0.83%   |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G    | 24        | 0.83%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 23        | 0.79%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 23        | 0.79%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 23        | 0.79%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 22        | 0.76%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 22        | 0.76%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 20        | 0.69%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 20        | 0.69%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 18        | 0.62%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 18        | 0.62%   |
| Intel Celeron CPU 3865U @ 1.80GHz             | 18        | 0.62%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 17        | 0.59%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 16        | 0.55%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 16        | 0.55%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 16        | 0.55%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 16        | 0.55%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 14        | 0.48%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 14        | 0.48%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 14        | 0.48%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 14        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 701       | 24.19%  |
| Intel Core i7           | 434       | 14.98%  |
| Intel Core 2 Duo        | 410       | 14.15%  |
| Intel Celeron           | 259       | 8.94%   |
| Other                   | 249       | 8.59%   |
| Intel Core i3           | 182       | 6.28%   |
| AMD Ryzen 5             | 129       | 4.45%   |
| Intel Atom              | 74        | 2.55%   |
| Intel Core 2            | 63        | 2.17%   |
| AMD Ryzen 7             | 61        | 2.1%    |
| Intel Pentium           | 53        | 1.83%   |
| AMD Ryzen 7 PRO         | 28        | 0.97%   |
| AMD A6                  | 23        | 0.79%   |
| Intel Pentium M         | 21        | 0.72%   |
| AMD A4                  | 15        | 0.52%   |
| Intel Genuine           | 14        | 0.48%   |
| AMD Ryzen 3             | 13        | 0.45%   |
| Intel Pentium Dual-Core | 12        | 0.41%   |
| AMD Ryzen 9             | 12        | 0.41%   |
| AMD Ryzen 5 PRO         | 11        | 0.38%   |
| Intel Celeron M         | 10        | 0.35%   |
| Intel Pentium Dual      | 9         | 0.31%   |
| AMD A8                  | 9         | 0.31%   |
| AMD A10                 | 9         | 0.31%   |
| AMD E1                  | 8         | 0.28%   |
| Intel Pentium 4         | 7         | 0.24%   |
| Intel Core i9           | 6         | 0.21%   |
| AMD A12                 | 6         | 0.21%   |
| Intel Pentium Silver    | 5         | 0.17%   |
| AMD E2                  | 5         | 0.17%   |
| Intel Xeon              | 4         | 0.14%   |
| AMD C-50                | 4         | 0.14%   |
| Intel Pentium Gold      | 3         | 0.1%    |
| Intel Mobile Pentium 4  | 3         | 0.1%    |
| Intel Core m3           | 3         | 0.1%    |
| AMD Turion 64 Mobile    | 3         | 0.1%    |
| AMD PRO A10             | 3         | 0.1%    |
| AMD E                   | 3         | 0.1%    |
| AMD C-60                | 3         | 0.1%    |
| AMD Athlon              | 3         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1673      | 57.73%  |
| 4      | 794       | 27.4%   |
| 6      | 148       | 5.11%   |
| 1      | 132       | 4.55%   |
| 8      | 124       | 4.28%   |
| 10     | 12        | 0.41%   |
| 14     | 8         | 0.28%   |
| 12     | 7         | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2897      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1788      | 61.7%   |
| 1      | 1109      | 38.27%  |
| 4      | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2812      | 97.07%  |
| 32-bit         | 80        | 2.76%   |
| Unknown        | 5         | 0.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 466       | 15.87%  |
| 0x1067a    | 354       | 12.06%  |
| 0x306d4    | 206       | 7.02%   |
| 0x306a9    | 138       | 4.7%    |
| 0x806c1    | 126       | 4.29%   |
| 0x206a7    | 108       | 3.68%   |
| 0x30678    | 98        | 3.34%   |
| 0x806ec    | 96        | 3.27%   |
| 0x806e9    | 80        | 2.72%   |
| 0x40651    | 69        | 2.35%   |
| 0x406e3    | 65        | 2.21%   |
| 0x806ea    | 63        | 2.15%   |
| 0x6f6      | 63        | 2.15%   |
| 0x406c4    | 53        | 1.81%   |
| 0xa0652    | 48        | 1.63%   |
| 0x906eb    | 44        | 1.5%    |
| 0x306c3    | 44        | 1.5%    |
| 0x08108109 | 43        | 1.46%   |
| 0x08600106 | 39        | 1.33%   |
| 0x906ea    | 38        | 1.29%   |
| 0x20655    | 35        | 1.19%   |
| 0x10676    | 33        | 1.12%   |
| 0x0a50000c | 33        | 1.12%   |
| 0x08608103 | 33        | 1.12%   |
| 0x0600611a | 30        | 1.02%   |
| 0x706e5    | 28        | 0.95%   |
| 0x706a8    | 27        | 0.92%   |
| 0x106c2    | 26        | 0.89%   |
| 0x06006705 | 25        | 0.85%   |
| 0x6fd      | 22        | 0.75%   |
| 0x806eb    | 21        | 0.72%   |
| 0x506c9    | 21        | 0.72%   |
| 0x506e3    | 20        | 0.68%   |
| 0x6d8      | 19        | 0.65%   |
| 0x08108102 | 19        | 0.65%   |
| 0x906e9    | 18        | 0.61%   |
| 0x806d1    | 18        | 0.61%   |
| 0x106ca    | 18        | 0.61%   |
| 0x906a4    | 12        | 0.41%   |
| 0x906a3    | 11        | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 457       | 15.75%  |
| Penryn           | 399       | 13.75%  |
| Broadwell        | 223       | 7.69%   |
| Silvermont       | 178       | 6.14%   |
| IvyBridge        | 176       | 6.07%   |
| TigerLake        | 160       | 5.52%   |
| Haswell          | 146       | 5.03%   |
| SandyBridge      | 142       | 4.89%   |
| Skylake          | 113       | 3.9%    |
| Core             | 108       | 3.72%   |
| Zen+             | 82        | 2.83%   |
| Zen 2            | 73        | 2.52%   |
| Unknown          | 72        | 2.48%   |
| Excavator        | 70        | 2.41%   |
| Westmere         | 62        | 2.14%   |
| CometLake        | 60        | 2.07%   |
| Bonnell          | 50        | 1.72%   |
| IceLake          | 49        | 1.69%   |
| Zen 3            | 46        | 1.59%   |
| P6               | 42        | 1.45%   |
| Goldmont plus    | 42        | 1.45%   |
| Goldmont         | 26        | 0.9%    |
| Zen              | 18        | 0.62%   |
| Bobcat           | 17        | 0.59%   |
| Puma             | 14        | 0.48%   |
| Alderlake Hybrid | 11        | 0.38%   |
| NetBurst         | 10        | 0.34%   |
| Tremont          | 9         | 0.31%   |
| K10 Llano        | 9         | 0.31%   |
| Jaguar           | 9         | 0.31%   |
| Piledriver       | 7         | 0.24%   |
| K8 Hammer        | 7         | 0.24%   |
| K10              | 5         | 0.17%   |
| Nehalem          | 4         | 0.14%   |
| K8 & K10 hybrid  | 4         | 0.14%   |
| Steamroller      | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2042      | 59.8%   |
| Nvidia                           | 838       | 24.54%  |
| AMD                              | 528       | 15.46%  |
| Zhaoxin                          | 3         | 0.09%   |
| Silicon Integrated Systems [SiS] | 2         | 0.06%   |
| VIA Technologies                 | 1         | 0.03%   |
| S3 Graphics                      | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 306       | 8.51%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 161       | 4.48%   |
| Intel HD Graphics 6000                                                                   | 153       | 4.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 145       | 4.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 126       | 3.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 110       | 3.06%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 97        | 2.7%    |
| Intel UHD Graphics 620                                                                   | 86        | 2.39%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 84        | 2.34%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 83        | 2.31%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 80        | 2.22%   |
| Intel HD Graphics 620                                                                    | 78        | 2.17%   |
| AMD Renoir                                                                               | 73        | 2.03%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 70        | 1.95%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 70        | 1.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 69        | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 67        | 1.86%   |
| Intel HD Graphics 5500                                                                   | 63        | 1.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 54        | 1.5%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 51        | 1.42%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 51        | 1.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 50        | 1.39%   |
| Intel Core Processor Integrated Graphics Controller                                      | 49        | 1.36%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 48        | 1.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 44        | 1.22%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 42        | 1.17%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 40        | 1.11%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 38        | 1.06%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 38        | 1.06%   |
| AMD Lucienne                                                                             | 38        | 1.06%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 30        | 0.83%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 27        | 0.75%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 25        | 0.7%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 25        | 0.7%    |
| Intel HD Graphics 630                                                                    | 24        | 0.67%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 23        | 0.64%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 23        | 0.64%   |
| Intel HD Graphics 530                                                                    | 22        | 0.61%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 20        | 0.56%   |
| Intel HD Graphics 610                                                                    | 20        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1564      | 53.91%  |
| Intel + Nvidia  | 402       | 13.86%  |
| 1 x Nvidia      | 386       | 13.31%  |
| 1 x AMD         | 377       | 13%     |
| Intel + AMD     | 68        | 2.34%   |
| AMD + Nvidia    | 52        | 1.79%   |
| 2 x AMD         | 31        | 1.07%   |
| Other           | 13        | 0.45%   |
| 1 x Zhaoxin     | 3         | 0.1%    |
| 1 x SiS         | 2         | 0.07%   |
| 2 x Intel       | 1         | 0.03%   |
| 1 x VIA         | 1         | 0.03%   |
| 1 x S3 Graphics | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2505      | 86.02%  |
| Unknown     | 243       | 8.34%   |
| Proprietary | 164       | 5.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 2104      | 72.01%  |
| 0.01-0.5       | 522       | 17.86%  |
| 1.01-2.0       | 115       | 3.94%   |
| 3.01-4.0       | 76        | 2.6%    |
| 0.51-1.0       | 71        | 2.43%   |
| 5.01-6.0       | 17        | 0.58%   |
| 7.01-8.0       | 9         | 0.31%   |
| 2.01-3.0       | 6         | 0.21%   |
| More than 64.0 | 1         | 0.03%   |
| 8.01-16.0      | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Apple                   | 571       | 18.92%  |
| AU Optronics            | 478       | 15.84%  |
| BOE                     | 402       | 13.32%  |
| LG Display              | 330       | 10.93%  |
| Chimei Innolux          | 325       | 10.77%  |
| Samsung Electronics     | 203       | 6.73%   |
| Lenovo                  | 65        | 2.15%   |
| Dell                    | 58        | 1.92%   |
| Sharp                   | 57        | 1.89%   |
| Chi Mei Optoelectronics | 54        | 1.79%   |
| Goldstar                | 48        | 1.59%   |
| InfoVision              | 44        | 1.46%   |
| Hewlett-Packard         | 32        | 1.06%   |
| PANDA                   | 31        | 1.03%   |
| BenQ                    | 31        | 1.03%   |
| HannStar                | 23        | 0.76%   |
| Unknown                 | 21        | 0.7%    |
| Philips                 | 21        | 0.7%    |
| AOC                     | 19        | 0.63%   |
| Ancor Communications    | 19        | 0.63%   |
| LG Philips              | 18        | 0.6%    |
| Iiyama                  | 17        | 0.56%   |
| ViewSonic               | 15        | 0.5%    |
| CSO                     | 14        | 0.46%   |
| Acer                    | 13        | 0.43%   |
| Sony                    | 7         | 0.23%   |
| Eizo                    | 7         | 0.23%   |
| CPT                     | 6         | 0.2%    |
| Quanta Display          | 5         | 0.17%   |
| NEC Computers           | 5         | 0.17%   |
| Pixio                   | 4         | 0.13%   |
| Panasonic               | 4         | 0.13%   |
| MSI                     | 4         | 0.13%   |
| Toshiba                 | 3         | 0.1%    |
| TMX                     | 3         | 0.1%    |
| SLD                     | 3         | 0.1%    |
| AGO                     | 3         | 0.1%    |
| ___                     | 2         | 0.07%   |
| Vestel Elektronik       | 2         | 0.07%   |
| RTK                     | 2         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                      | 199       | 6.54%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                    | 151       | 4.96%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                      | 52        | 1.71%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 42        | 1.38%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                      | 41        | 1.35%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch             | 39        | 1.28%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                      | 37        | 1.22%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 27        | 0.89%   |
| BOE LCD Monitor BOE06B3 1920x1080                                         | 25        | 0.82%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 24        | 0.79%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 22        | 0.72%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch           | 21        | 0.69%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                      | 21        | 0.69%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 19        | 0.62%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                 | 19        | 0.62%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 18        | 0.59%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 17        | 0.56%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 15        | 0.49%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 14        | 0.46%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 14        | 0.46%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                      | 13        | 0.43%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch            | 12        | 0.39%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch      | 11        | 0.36%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                      | 11        | 0.36%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 10        | 0.33%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 10        | 0.33%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch              | 9         | 0.3%    |
| InfoVision LCD Monitor IVO0533 1366x768 293x165mm 13.2-inch               | 9         | 0.3%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 9         | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 9         | 0.3%    |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                     | 9         | 0.3%    |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 9         | 0.3%    |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch            | 9         | 0.3%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 9         | 0.3%    |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 9         | 0.3%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch             | 9         | 0.3%    |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 9         | 0.3%    |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                      | 9         | 0.3%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 7         | 0.23%   |
| LG Display LCD Monitor LGD034C 1366x768 293x165mm 13.2-inch               | 7         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1011      | 35.25%  |
| 1366x768 (WXGA)    | 779       | 27.16%  |
| 1280x800 (WXGA)    | 460       | 16.04%  |
| 1440x900 (WXGA+)   | 114       | 3.97%   |
| 1600x900 (HD+)     | 107       | 3.73%   |
| 3840x2160 (4K)     | 73        | 2.55%   |
| 2560x1440 (QHD)    | 54        | 1.88%   |
| 1920x1200 (WUXGA)  | 52        | 1.81%   |
| 1024x600           | 44        | 1.53%   |
| 2288x1287          | 19        | 0.66%   |
| 2560x1600          | 18        | 0.63%   |
| 1280x1024 (SXGA)   | 18        | 0.63%   |
| 1024x768 (XGA)     | 14        | 0.49%   |
| 1680x1050 (WSXGA+) | 13        | 0.45%   |
| 2560x1080          | 12        | 0.42%   |
| 1360x768           | 12        | 0.42%   |
| 3840x2400          | 11        | 0.38%   |
| 2880x1800          | 9         | 0.31%   |
| 3440x1440          | 7         | 0.24%   |
| 2160x1440          | 7         | 0.24%   |
| 1400x1050          | 4         | 0.14%   |
| 3840x1080          | 3         | 0.1%    |
| 3200x1800 (QHD+)   | 3         | 0.1%    |
| 1024x576           | 3         | 0.1%    |
| Unknown            | 3         | 0.1%    |
| 3840x1100          | 2         | 0.07%   |
| 2256x1504          | 2         | 0.07%   |
| 1920x1280          | 2         | 0.07%   |
| 1600x1200          | 2         | 0.07%   |
| 3840x1600          | 1         | 0.03%   |
| 3840x1200          | 1         | 0.03%   |
| 3072x1920          | 1         | 0.03%   |
| 2880x1920          | 1         | 0.03%   |
| 2520x1680          | 1         | 0.03%   |
| 2304x1440          | 1         | 0.03%   |
| 2048x1152          | 1         | 0.03%   |
| 1920x540           | 1         | 0.03%   |
| 1920x515           | 1         | 0.03%   |
| 1792x768           | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 841       | 27.88%  |
| 13      | 830       | 27.51%  |
| 14      | 342       | 11.34%  |
| 11      | 243       | 8.05%   |
| 17      | 148       | 4.91%   |
| 12      | 103       | 3.41%   |
| 24      | 95        | 3.15%   |
| 27      | 69        | 2.29%   |
| 23      | 65        | 2.15%   |
| 21      | 48        | 1.59%   |
| 10      | 44        | 1.46%   |
| 18      | 24        | 0.8%    |
| 19      | 20        | 0.66%   |
| 142     | 19        | 0.63%   |
| 31      | 17        | 0.56%   |
| 16      | 15        | 0.5%    |
| Unknown | 15        | 0.5%    |
| 34      | 13        | 0.43%   |
| 25      | 8         | 0.27%   |
| 32      | 7         | 0.23%   |
| 22      | 7         | 0.23%   |
| 72      | 5         | 0.17%   |
| 40      | 5         | 0.17%   |
| 29      | 5         | 0.17%   |
| 20      | 5         | 0.17%   |
| 84      | 4         | 0.13%   |
| 54      | 3         | 0.1%    |
| 8       | 3         | 0.1%    |
| 52      | 2         | 0.07%   |
| 49      | 2         | 0.07%   |
| 46      | 2         | 0.07%   |
| 28      | 2         | 0.07%   |
| 55      | 1         | 0.03%   |
| 47      | 1         | 0.03%   |
| 43      | 1         | 0.03%   |
| 37      | 1         | 0.03%   |
| 33      | 1         | 0.03%   |
| 26      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1397      | 46.63%  |
| 201-300        | 1000      | 33.38%  |
| 501-600        | 214       | 7.14%   |
| 351-400        | 169       | 5.64%   |
| 401-500        | 96        | 3.2%    |
| 601-700        | 36        | 1.2%    |
| 701-800        | 20        | 0.67%   |
| More than 2000 | 19        | 0.63%   |
| Unknown        | 15        | 0.5%    |
| 1001-1500      | 12        | 0.4%    |
| 1501-2000      | 9         | 0.3%    |
| 801-900        | 6         | 0.2%    |
| 101-200        | 3         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1939      | 70.9%   |
| 16/10   | 687       | 25.12%  |
| 4/3     | 22        | 0.8%    |
| 1.00    | 19        | 0.69%   |
| 5/4     | 18        | 0.66%   |
| 3/2     | 18        | 0.66%   |
| 21/9    | 16        | 0.59%   |
| Unknown | 7         | 0.26%   |
| 2.65    | 4         | 0.15%   |
| 3.40    | 2         | 0.07%   |
| 32/9    | 1         | 0.04%   |
| 3.73    | 1         | 0.04%   |
| 3.20    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 983       | 32.67%  |
| 101-110        | 845       | 28.08%  |
| 51-60          | 245       | 8.14%   |
| 71-80          | 184       | 6.11%   |
| 201-250        | 166       | 5.52%   |
| 121-130        | 117       | 3.89%   |
| 61-70          | 99        | 3.29%   |
| 301-350        | 69        | 2.29%   |
| 251-300        | 47        | 1.56%   |
| 41-50          | 44        | 1.46%   |
| 351-500        | 40        | 1.33%   |
| 151-200        | 36        | 1.2%    |
| More than 1000 | 35        | 1.16%   |
| 141-150        | 33        | 1.1%    |
| 131-140        | 20        | 0.66%   |
| Unknown        | 15        | 0.5%    |
| 501-1000       | 10        | 0.33%   |
| 91-100         | 10        | 0.33%   |
| 111-120        | 8         | 0.27%   |
| 1-40           | 3         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1293      | 43.68%  |
| 101-120       | 1032      | 34.86%  |
| 51-100        | 377       | 12.74%  |
| 161-240       | 156       | 5.27%   |
| More than 240 | 49        | 1.66%   |
| 1-50          | 38        | 1.28%   |
| Unknown       | 15        | 0.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2296      | 78.25%  |
| 2     | 356       | 12.13%  |
| 0     | 242       | 8.25%   |
| 3     | 39        | 1.33%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1367      | 29.3%   |
| Realtek Semiconductor             | 1197      | 25.65%  |
| Qualcomm Atheros                  | 547       | 11.72%  |
| Broadcom                          | 525       | 11.25%  |
| Nvidia                            | 317       | 6.79%   |
| Broadcom Limited                  | 213       | 4.56%   |
| Marvell Technology Group          | 105       | 2.25%   |
| MediaTek                          | 46        | 0.99%   |
| Ralink                            | 30        | 0.64%   |
| TP-Link                           | 27        | 0.58%   |
| ASIX Electronics                  | 27        | 0.58%   |
| Samsung Electronics               | 22        | 0.47%   |
| Dell                              | 22        | 0.47%   |
| Sierra Wireless                   | 20        | 0.43%   |
| Ralink Technology                 | 16        | 0.34%   |
| Qualcomm                          | 16        | 0.34%   |
| DisplayLink                       | 15        | 0.32%   |
| Xiaomi                            | 13        | 0.28%   |
| Ericsson Business Mobile Networks | 12        | 0.26%   |
| Lenovo                            | 11        | 0.24%   |
| JMicron Technology                | 9         | 0.19%   |
| Hewlett-Packard                   | 9         | 0.19%   |
| Huawei Technologies               | 8         | 0.17%   |
| NetGear                           | 6         | 0.13%   |
| Fibocom                           | 6         | 0.13%   |
| Cypress Semiconductor             | 6         | 0.13%   |
| ICS Advent                        | 5         | 0.11%   |
| ASUSTek Computer                  | 5         | 0.11%   |
| AMD                               | 5         | 0.11%   |
| Qualcomm Atheros Communications   | 4         | 0.09%   |
| OPPO                              | 4         | 0.09%   |
| Microchip Technology              | 4         | 0.09%   |
| Attansic Technology               | 4         | 0.09%   |
| ULi Electronics                   | 3         | 0.06%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.06%   |
| Apple                             | 3         | 0.06%   |
| Winbond Electronics               | 2         | 0.04%   |
| Spreadtrum Communications         | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.04%   |
| National Semiconductor            | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 743       | 13.57%  |
| Nvidia MCP79 Ethernet                                                                 | 311       | 5.68%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 309       | 5.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 187       | 3.42%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 158       | 2.89%   |
| Intel Wireless 7260                                                                   | 137       | 2.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 128       | 2.34%   |
| Intel Wireless 8265 / 8275                                                            | 116       | 2.12%   |
| Intel Wi-Fi 6 AX201                                                                   | 111       | 2.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 108       | 1.97%   |
| Intel Wireless 7265                                                                   | 106       | 1.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 100       | 1.83%   |
| Intel Wi-Fi 6 AX200                                                                   | 99        | 1.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 76        | 1.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 74        | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 69        | 1.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 65        | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 64        | 1.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 63        | 1.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 62        | 1.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 59        | 1.08%   |
| Intel Wireless 8260                                                                   | 57        | 1.04%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 56        | 1.02%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 56        | 1.02%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 48        | 0.88%   |
| Intel Ethernet Connection (4) I219-V                                                  | 44        | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 43        | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 42        | 0.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 37        | 0.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 36        | 0.66%   |
| Intel Ethernet Connection I218-LM                                                     | 34        | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 33        | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 30        | 0.55%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 29        | 0.53%   |
| Intel Wireless 3165                                                                   | 28        | 0.51%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 28        | 0.51%   |
| Intel Ethernet Connection I219-LM                                                     | 27        | 0.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 27        | 0.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 26        | 0.47%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 26        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1298      | 44.01%  |
| Qualcomm Atheros                      | 499       | 16.92%  |
| Broadcom                              | 453       | 15.36%  |
| Realtek Semiconductor                 | 344       | 11.66%  |
| Broadcom Limited                      | 191       | 6.48%   |
| MediaTek                              | 32        | 1.09%   |
| Ralink                                | 30        | 1.02%   |
| Sierra Wireless                       | 20        | 0.68%   |
| Ralink Technology                     | 16        | 0.54%   |
| TP-Link                               | 13        | 0.44%   |
| Dell                                  | 13        | 0.44%   |
| Qualcomm                              | 7         | 0.24%   |
| NetGear                               | 6         | 0.2%    |
| FIBOCOM                               | 6         | 0.2%    |
| ASUSTek Computer                      | 5         | 0.17%   |
| Qualcomm Atheros Communications       | 4         | 0.14%   |
| Ericsson Business Mobile Networks     | 3         | 0.1%    |
| Edimax Technology                     | 2         | 0.07%   |
| Z-Com                                 | 1         | 0.03%   |
| Winbond Electronics                   | 1         | 0.03%   |
| Wilocity                              | 1         | 0.03%   |
| D-Link System                         | 1         | 0.03%   |
| Belkin Components                     | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |
| 3Com                                  | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 309       | 10.45%  |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 158       | 5.34%   |
| Intel Wireless 7260                                                                   | 137       | 4.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 128       | 4.33%   |
| Intel Wireless 8265 / 8275                                                            | 116       | 3.92%   |
| Intel Wi-Fi 6 AX201                                                                   | 111       | 3.75%   |
| Intel Wireless 7265                                                                   | 106       | 3.58%   |
| Intel Wi-Fi 6 AX200                                                                   | 99        | 3.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 76        | 2.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 74        | 2.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 69        | 2.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 65        | 2.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 64        | 2.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 63        | 2.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 62        | 2.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 59        | 1.99%   |
| Intel Wireless 8260                                                                   | 57        | 1.93%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 56        | 1.89%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 48        | 1.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 43        | 1.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 42        | 1.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 37        | 1.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 30        | 1.01%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 29        | 0.98%   |
| Intel Wireless 3165                                                                   | 28        | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 27        | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 26        | 0.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 26        | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 26        | 0.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 25        | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 24        | 0.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 23        | 0.78%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 23        | 0.78%   |
| Intel Wireless 3160                                                                   | 22        | 0.74%   |
| Intel Centrino Ultimate-N 6300                                                        | 22        | 0.74%   |
| Intel Centrino Advanced-N 6200                                                        | 21        | 0.71%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 20        | 0.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 19        | 0.64%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 18        | 0.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 18        | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1063      | 43.85%  |
| Intel                            | 527       | 21.74%  |
| Nvidia                           | 317       | 13.08%  |
| Qualcomm Atheros                 | 106       | 4.37%   |
| Marvell Technology Group         | 105       | 4.33%   |
| Broadcom                         | 91        | 3.75%   |
| ASIX Electronics                 | 27        | 1.11%   |
| Broadcom Limited                 | 25        | 1.03%   |
| Samsung Electronics              | 22        | 0.91%   |
| DisplayLink                      | 15        | 0.62%   |
| TP-Link                          | 14        | 0.58%   |
| MediaTek                         | 14        | 0.58%   |
| Xiaomi                           | 13        | 0.54%   |
| Lenovo                           | 11        | 0.45%   |
| Qualcomm                         | 9         | 0.37%   |
| JMicron Technology               | 9         | 0.37%   |
| Cypress Semiconductor            | 6         | 0.25%   |
| ICS Advent                       | 5         | 0.21%   |
| Huawei Technologies              | 5         | 0.21%   |
| OPPO                             | 4         | 0.17%   |
| Microchip Technology             | 4         | 0.17%   |
| Attansic Technology              | 4         | 0.17%   |
| Silicon Integrated Systems [SiS] | 3         | 0.12%   |
| Apple                            | 3         | 0.12%   |
| Spreadtrum Communications        | 2         | 0.08%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.08%   |
| National Semiconductor           | 2         | 0.08%   |
| Motorola PCS                     | 2         | 0.08%   |
| Hewlett-Packard                  | 2         | 0.08%   |
| D-Link                           | 2         | 0.08%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.04%   |
| VIA Technologies                 | 1         | 0.04%   |
| ULi Electronics                  | 1         | 0.04%   |
| MosChip Semiconductor            | 1         | 0.04%   |
| Linksys                          | 1         | 0.04%   |
| LG Electronics                   | 1         | 0.04%   |
| Google                           | 1         | 0.04%   |
| Digitech Systems                 | 1         | 0.04%   |
| Davicom Semiconductor            | 1         | 0.04%   |
| 3DSP                             | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 743       | 30.36%  |
| Nvidia MCP79 Ethernet                                             | 311       | 12.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 187       | 7.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 108       | 4.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 100       | 4.09%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 56        | 2.29%   |
| Intel Ethernet Connection (4) I219-V                              | 44        | 1.8%    |
| Intel Ethernet Connection I218-LM                                 | 34        | 1.39%   |
| Intel Ethernet Connection (4) I219-LM                             | 33        | 1.35%   |
| Intel Ethernet Connection (3) I218-LM                             | 28        | 1.14%   |
| Intel Ethernet Connection I219-LM                                 | 27        | 1.1%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 25        | 1.02%   |
| Intel 82577LM Gigabit Network Connection                          | 23        | 0.94%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 22        | 0.9%    |
| ASIX AX88179 Gigabit Ethernet                                     | 21        | 0.86%   |
| Intel Ethernet Connection (6) I219-V                              | 20        | 0.82%   |
| Intel Ethernet Connection (13) I219-V                             | 20        | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18        | 0.74%   |
| Intel Ethernet Connection I219-V                                  | 18        | 0.74%   |
| Intel Ethernet Connection I217-LM                                 | 15        | 0.61%   |
| Intel Ethernet Connection (10) I219-V                             | 15        | 0.61%   |
| Intel 82567LM Gigabit Network Connection                          | 15        | 0.61%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 14        | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 13        | 0.53%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 13        | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 12        | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 12        | 0.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 12        | 0.49%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 11        | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 10        | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 10        | 0.41%   |
| Intel 82566MM Gigabit Network Connection                          | 10        | 0.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9         | 0.37%   |
| Intel Ethernet Connection (13) I219-LM                            | 9         | 0.37%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 8         | 0.33%   |
| Intel Ethernet Connection (7) I219-LM                             | 8         | 0.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 8         | 0.33%   |
| Intel Ethernet Connection (11) I219-LM                            | 8         | 0.33%   |
| Intel 82579V Gigabit Network Connection                           | 8         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2837      | 54.45%  |
| Ethernet | 2303      | 44.2%   |
| Modem    | 67        | 1.29%   |
| Unknown  | 3         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2185      | 71.95%  |
| Ethernet | 852       | 28.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2085      | 71.9%   |
| 1     | 745       | 25.69%  |
| 0     | 40        | 1.38%   |
| 3     | 29        | 1%      |
| 4     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2410      | 82.59%  |
| Yes  | 508       | 17.41%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 995       | 41.29%  |
| Apple                           | 562       | 23.32%  |
| Realtek Semiconductor           | 193       | 8.01%   |
| Qualcomm Atheros Communications | 184       | 7.63%   |
| Broadcom                        | 98        | 4.07%   |
| Lite-On Technology              | 86        | 3.57%   |
| IMC Networks                    | 85        | 3.53%   |
| Foxconn / Hon Hai               | 54        | 2.24%   |
| Dell                            | 34        | 1.41%   |
| Cambridge Silicon Radio         | 30        | 1.24%   |
| Hewlett-Packard                 | 22        | 0.91%   |
| Realtek                         | 14        | 0.58%   |
| Ralink                          | 11        | 0.46%   |
| ASUSTek Computer                | 11        | 0.46%   |
| Toshiba                         | 10        | 0.41%   |
| Ralink Technology               | 4         | 0.17%   |
| Foxconn International           | 4         | 0.17%   |
| Taiyo Yuden                     | 3         | 0.12%   |
| MediaTek                        | 3         | 0.12%   |
| Alps Electric                   | 3         | 0.12%   |
| Fujitsu                         | 2         | 0.08%   |
| Qcom                            | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 439       | 18.21%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 302       | 12.53%  |
| Intel AX201 Bluetooth                               | 202       | 8.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 159       | 6.59%   |
| Apple Bluetooth USB Host Controller                 | 158       | 6.55%   |
| Realtek Bluetooth Radio                             | 122       | 5.06%   |
| Qualcomm Atheros  Bluetooth Device                  | 114       | 4.73%   |
| Intel AX200 Bluetooth                               | 97        | 4.02%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 3.15%   |
| Realtek  Bluetooth 4.2 Adapter                      | 47        | 1.95%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 34        | 1.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 30        | 1.24%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 27        | 1.12%   |
| IMC Networks Bluetooth Radio                        | 27        | 1.12%   |
| Lite-On Bluetooth Device                            | 23        | 0.95%   |
| Apple Bluetooth Host Controller                     | 23        | 0.95%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 22        | 0.91%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 22        | 0.91%   |
| Foxconn / Hon Hai Bluetooth Device                  | 19        | 0.79%   |
| Broadcom BCM2045B (BDC-2.1)                         | 19        | 0.79%   |
| Intel AX210 Bluetooth                               | 17        | 0.71%   |
| IMC Networks Wireless_Device                        | 17        | 0.71%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 16        | 0.66%   |
| Intel Bluetooth Device                              | 16        | 0.66%   |
| IMC Networks Bluetooth Device                       | 16        | 0.66%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 15        | 0.62%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 14        | 0.58%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 14        | 0.58%   |
| Intel Wireless-AC 3168 Bluetooth                    | 14        | 0.58%   |
| Foxconn / Hon Hai Wireless_Device                   | 14        | 0.58%   |
| Dell BCM20702A0 Bluetooth Module                    | 13        | 0.54%   |
| Realtek RTL8723B Bluetooth                          | 12        | 0.5%    |
| Realtek 802.11ac WLAN Adapter                       | 12        | 0.5%    |
| Ralink RT3290 Bluetooth                             | 11        | 0.46%   |
| HP Broadcom 2070 Bluetooth Combo                    | 10        | 0.41%   |
| Lite-On Wireless_Device                             | 9         | 0.37%   |
| Dell DW375 Bluetooth Module                         | 9         | 0.37%   |
| Broadcom HP Portable SoftSailing                    | 9         | 0.37%   |
| Lite-On Atheros AR3012 Bluetooth                    | 8         | 0.33%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 8         | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2136      | 64.65%  |
| Nvidia                                       | 576       | 17.43%  |
| AMD                                          | 433       | 13.11%  |
| C-Media Electronics                          | 21        | 0.64%   |
| Logitech                                     | 14        | 0.42%   |
| Realtek Semiconductor                        | 13        | 0.39%   |
| Generalplus Technology                       | 10        | 0.3%    |
| Lenovo                                       | 9         | 0.27%   |
| Texas Instruments                            | 8         | 0.24%   |
| GN Netcom                                    | 8         | 0.24%   |
| Plantronics                                  | 7         | 0.21%   |
| Hewlett-Packard                              | 7         | 0.21%   |
| Creative Technology                          | 5         | 0.15%   |
| Zoran Co. Personal Media Division (Nogatech) | 4         | 0.12%   |
| ASUSTek Computer                             | 4         | 0.12%   |
| Zhaoxin                                      | 3         | 0.09%   |
| ULi Electronics                              | 3         | 0.09%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.09%   |
| Sennheiser Communications                    | 2         | 0.06%   |
| SAVITECH                                     | 2         | 0.06%   |
| RODE Microphones                             | 2         | 0.06%   |
| Microsoft                                    | 2         | 0.06%   |
| Kingston Technology                          | 2         | 0.06%   |
| JMTek                                        | 2         | 0.06%   |
| CMX Systems                                  | 2         | 0.06%   |
| XMOS                                         | 1         | 0.03%   |
| VIA Technologies                             | 1         | 0.03%   |
| Toshiba                                      | 1         | 0.03%   |
| Thomann                                      | 1         | 0.03%   |
| Tenx Technology                              | 1         | 0.03%   |
| Syntek                                       | 1         | 0.03%   |
| SteelSeries ApS                              | 1         | 0.03%   |
| Samsung Electronics                          | 1         | 0.03%   |
| Razer USA                                    | 1         | 0.03%   |
| Pixart Imaging                               | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)                | 1         | 0.03%   |
| Microdia                                     | 1         | 0.03%   |
| M-Audio                                      | 1         | 0.03%   |
| Focusrite-Novation                           | 1         | 0.03%   |
| ESS Technology                               | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia MCP79 High Definition Audio                                                                | 313       | 7.77%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 275       | 6.82%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 256       | 6.35%   |
| Intel Broadwell-U Audio Controller                                                                | 223       | 5.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 220       | 5.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 211       | 5.24%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 159       | 3.95%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 127       | 3.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 125       | 3.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 107       | 2.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 100       | 2.48%   |
| Intel Cannon Lake PCH cAVS                                                                        | 99        | 2.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 98        | 2.43%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 85        | 2.11%   |
| Intel 8 Series HD Audio Controller                                                                | 85        | 2.11%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 76        | 1.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 72        | 1.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 67        | 1.66%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 65        | 1.61%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 64        | 1.59%   |
| AMD Kabini HDMI/DP Audio                                                                          | 63        | 1.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 61        | 1.51%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 57        | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 56        | 1.39%   |
| Intel Comet Lake PCH cAVS                                                                         | 56        | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 56        | 1.39%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 48        | 1.19%   |
| AMD FCH Azalia Controller                                                                         | 47        | 1.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 42        | 1.04%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 32        | 0.79%   |
| AMD High Definition Audio Controller                                                              | 30        | 0.74%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 29        | 0.72%   |
| Intel CM238 HD Audio Controller                                                                   | 26        | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 26        | 0.65%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 26        | 0.65%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 24        | 0.6%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 24        | 0.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 24        | 0.6%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 20        | 0.5%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 20        | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 892       | 30.71%  |
| Samsung Electronics | 759       | 26.13%  |
| Micron Technology   | 283       | 9.74%   |
| Kingston            | 184       | 6.33%   |
| Unknown             | 169       | 5.82%   |
| Crucial             | 157       | 5.4%    |
| Elpida              | 89        | 3.06%   |
| A-DATA Technology   | 58        | 2%      |
| Ramaxel Technology  | 47        | 1.62%   |
| Nanya Technology    | 34        | 1.17%   |
| Unknown             | 34        | 1.17%   |
| Corsair             | 29        | 1%      |
| Unknown (ABCD)      | 22        | 0.76%   |
| GOODRAM             | 19        | 0.65%   |
| Smart               | 17        | 0.59%   |
| Transcend           | 12        | 0.41%   |
| Team                | 12        | 0.41%   |
| G.Skill             | 10        | 0.34%   |
| Patriot             | 6         | 0.21%   |
| ASint Technology    | 5         | 0.17%   |
| Silicon Power       | 4         | 0.14%   |
| Apacer              | 4         | 0.14%   |
| Wilk                | 3         | 0.1%    |
| Smart Brazil        | 3         | 0.1%    |
| Qimonda             | 3         | 0.1%    |
| PNY                 | 3         | 0.1%    |
| AMD                 | 3         | 0.1%    |
| 48spaces            | 3         | 0.1%    |
| Unknown (89F7)      | 2         | 0.07%   |
| Unifosa             | 2         | 0.07%   |
| Teikon              | 2         | 0.07%   |
| Shenzhen WODPOSIT   | 2         | 0.07%   |
| SHARETRONIC         | 2         | 0.07%   |
| Neo Forza           | 2         | 0.07%   |
| Kllisre             | 2         | 0.07%   |
| Infineon            | 2         | 0.07%   |
| Goldkey             | 2         | 0.07%   |
| ff                  | 2         | 0.07%   |
| fef5                | 2         | 0.07%   |
| Avant               | 2         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 258       | 8.51%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 2.24%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 63        | 2.08%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 60        | 1.98%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 44        | 1.45%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 38        | 1.25%   |
| Unknown                                                          | 34        | 1.12%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 29        | 0.96%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 29        | 0.96%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 29        | 0.96%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 27        | 0.89%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 26        | 0.86%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 25        | 0.83%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.83%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 24        | 0.79%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.79%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 22        | 0.73%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 21        | 0.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 21        | 0.69%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 21        | 0.69%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 21        | 0.69%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 20        | 0.66%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 19        | 0.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 18        | 0.59%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 17        | 0.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 16        | 0.53%   |
| Micron RAM 4KTF25664HZ-1G6E 2GB SODIMM DDR3 1333MT/s             | 16        | 0.53%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.5%    |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                       | 15        | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 14        | 0.46%   |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s            | 14        | 0.46%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 14        | 0.46%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.43%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 13        | 0.43%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 0.43%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.4%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 12        | 0.4%    |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 12        | 0.4%    |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 12        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 943       | 36.98%  |
| DDR3    | 848       | 33.25%  |
| DDR2    | 472       | 18.51%  |
| LPDDR4  | 86        | 3.37%   |
| LPDDR3  | 84        | 3.29%   |
| SDRAM   | 57        | 2.24%   |
| DDR     | 32        | 1.25%   |
| Unknown | 13        | 0.51%   |
| DDR5    | 6         | 0.24%   |
| DRAM    | 5         | 0.2%    |
| LPDDR5  | 4         | 0.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2339      | 91.4%   |
| Row Of Chips | 140       | 5.47%   |
| Unknown      | 46        | 1.8%    |
| Chip         | 23        | 0.9%    |
| DIMM         | 11        | 0.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 767       | 28.05%  |
| 4096  | 695       | 25.42%  |
| 1024  | 476       | 17.41%  |
| 2048  | 439       | 16.06%  |
| 16384 | 258       | 9.44%   |
| 32768 | 55        | 2.01%   |
| 512   | 32        | 1.17%   |
| 256   | 11        | 0.4%    |
| 384   | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 672       | 24.81%  |
| 2667    | 439       | 16.21%  |
| 3200    | 402       | 14.84%  |
| 800     | 318       | 11.74%  |
| 2400    | 150       | 5.54%   |
| 667     | 135       | 4.98%   |
| 1334    | 95        | 3.51%   |
| 2133    | 90        | 3.32%   |
| 1333    | 80        | 2.95%   |
| Unknown | 62        | 2.29%   |
| 1067    | 35        | 1.29%   |
| 4267    | 34        | 1.26%   |
| 1867    | 32        | 1.18%   |
| 3266    | 27        | 1%      |
| 4199    | 20        | 0.74%   |
| 1066    | 14        | 0.52%   |
| 533     | 14        | 0.52%   |
| 2048    | 11        | 0.41%   |
| 975     | 9         | 0.33%   |
| 8400    | 8         | 0.3%    |
| 4800    | 8         | 0.3%    |
| 333     | 8         | 0.3%    |
| 266     | 7         | 0.26%   |
| 4266    | 6         | 0.22%   |
| 3733    | 5         | 0.18%   |
| 400     | 5         | 0.18%   |
| 6400    | 4         | 0.15%   |
| 1866    | 4         | 0.15%   |
| 933     | 3         | 0.11%   |
| 2933    | 2         | 0.07%   |
| 2666    | 2         | 0.07%   |
| 1639    | 2         | 0.07%   |
| 3000    | 1         | 0.04%   |
| 1596    | 1         | 0.04%   |
| 200     | 1         | 0.04%   |
| 166     | 1         | 0.04%   |
| 133     | 1         | 0.04%   |
| 100     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 31.25%  |
| Xerox               | 4         | 25%     |
| Canon               | 3         | 18.75%  |
| Brother Industries  | 3         | 18.75%  |
| Samsung Electronics | 1         | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Xerox B205                          | 4         | 25%     |
| Samsung ML-2010P Mono Laser Printer | 1         | 6.25%   |
| HP LaserJet 1160 series             | 1         | 6.25%   |
| HP LaserJet 1022                    | 1         | 6.25%   |
| HP Ink Tank 110 series              | 1         | 6.25%   |
| HP DeskJet 2620 All-in-One Printer  | 1         | 6.25%   |
| HP DeskJet 2130 series              | 1         | 6.25%   |
| Canon PIXMA MX920 Series            | 1         | 6.25%   |
| Canon LBP3010/LBP3018/LBP3050       | 1         | 6.25%   |
| Canon G3010 series                  | 1         | 6.25%   |
| Brother PT-9500PC                   | 1         | 6.25%   |
| Brother MFC-L2707DW                 | 1         | 6.25%   |
| Brother HL-L2340D series            | 1         | 6.25%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Canon       | 4         | 66.67%  |
| Seiko Epson | 2         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 120                       | 2         | 33.33%  |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 16.67%  |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 16.67%  |
| Canon CanoScan LIDE 25                        | 1         | 16.67%  |
| Canon CanoScan LiDE 220                       | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 502       | 24.08%  |
| IMC Networks                           | 245       | 11.75%  |
| Acer                                   | 218       | 10.46%  |
| Quanta                                 | 204       | 9.78%   |
| Microdia                               | 158       | 7.58%   |
| Realtek Semiconductor                  | 156       | 7.48%   |
| Sunplus Innovation Technology          | 87        | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 69        | 3.31%   |
| Suyin                                  | 60        | 2.88%   |
| Lite-On Technology                     | 50        | 2.4%    |
| Syntek                                 | 46        | 2.21%   |
| Apple                                  | 35        | 1.68%   |
| Luxvisions Innotech Limited            | 34        | 1.63%   |
| Logitech                               | 26        | 1.25%   |
| Silicon Motion                         | 21        | 1.01%   |
| Alcor Micro                            | 20        | 0.96%   |
| Lenovo                                 | 19        | 0.91%   |
| Sonix Technology                       | 12        | 0.58%   |
| Ricoh                                  | 12        | 0.58%   |
| DLEQNA19IFK6G2                         | 12        | 0.58%   |
| Z-Star Microelectronics                | 10        | 0.48%   |
| Primax Electronics                     | 10        | 0.48%   |
| Importek                               | 7         | 0.34%   |
| Intel                                  | 5         | 0.24%   |
| Genesys Logic                          | 5         | 0.24%   |
| ALi                                    | 5         | 0.24%   |
| Y Media                                | 4         | 0.19%   |
| SunplusIT                              | 4         | 0.19%   |
| Samsung Electronics                    | 4         | 0.19%   |
| icSpring                               | 4         | 0.19%   |
| Bison Electronics                      | 4         | 0.19%   |
| Sunplus Technology                     | 2         | 0.1%    |
| Pixart Imaging                         | 2         | 0.1%    |
| OmniVision Technologies                | 2         | 0.1%    |
| Mimaki Engineering                     | 2         | 0.1%    |
| Microsoft                              | 2         | 0.1%    |
| MacroSilicon                           | 2         | 0.1%    |
| ARC International                      | 2         | 0.1%    |
| USB Camera CS                          | 1         | 0.05%   |
| Unknown                                | 1         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 151       | 7.2%    |
| Microdia Integrated_Webcam_HD            | 80        | 3.81%   |
| IMC Networks Integrated Camera           | 76        | 3.62%   |
| Quanta Chromebook HD Camera              | 67        | 3.2%    |
| Acer Integrated Camera                   | 59        | 2.81%   |
| IMC Networks USB2.0 HD UVC WebCam        | 58        | 2.77%   |
| Realtek Integrated_Webcam_HD             | 55        | 2.62%   |
| Acer BisonCam, NB Pro                    | 54        | 2.58%   |
| Chicony HD Webcam                        | 48        | 2.29%   |
| Sunplus Integrated_Webcam_HD             | 32        | 1.53%   |
| Chicony USB2.0 HD UVC WebCam             | 32        | 1.53%   |
| Chicony HP HD Camera                     | 27        | 1.29%   |
| Syntek Integrated Camera                 | 25        | 1.19%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 25        | 1.19%   |
| Quanta HD User Facing                    | 24        | 1.14%   |
| Quanta HP TrueVision HD Camera           | 23        | 1.1%    |
| Quanta VGA WebCam                        | 21        | 1%      |
| Acer SunplusIT Integrated Camera         | 20        | 0.95%   |
| Microdia Integrated Webcam               | 18        | 0.86%   |
| Lite-On Integrated Camera                | 18        | 0.86%   |
| Realtek USB Camera                       | 17        | 0.81%   |
| Quanta HP HD Camera                      | 16        | 0.76%   |
| Chicony HP TrueVision HD Camera          | 16        | 0.76%   |
| Luxvisions Innotech Limited HP HD Camera | 15        | 0.72%   |
| Lite-On HP HD Camera                     | 15        | 0.72%   |
| Chicony HD User Facing                   | 15        | 0.72%   |
| Chicony Chromebook HD Camera             | 15        | 0.72%   |
| Acer Lenovo Integrated Webcam            | 15        | 0.72%   |
| Chicony Integrated Camera (1280x720@30)  | 14        | 0.67%   |
| Acer Lenovo EasyCamera                   | 14        | 0.67%   |
| IMC Networks USB 2.0 Camera              | 13        | 0.62%   |
| DLEQNA19IFK6G2 HP TrueVision HD Camera   | 12        | 0.57%   |
| Chicony Lenovo EasyCamera                | 12        | 0.57%   |
| Chicony HP Webcam                        | 12        | 0.57%   |
| Chicony HP TrueVision HD                 | 12        | 0.57%   |
| Acer BisonCam,NB Pro                     | 12        | 0.57%   |
| Suyin HP TrueVision HD                   | 11        | 0.52%   |
| Sunplus HD WebCam                        | 11        | 0.52%   |
| Sonix USB2.0 HD UVC WebCam               | 11        | 0.52%   |
| Quanta HD Webcam                         | 11        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 154       | 35%     |
| Synaptics                          | 134       | 30.45%  |
| Shenzhen Goodix Technology         | 65        | 14.77%  |
| Upek                               | 24        | 5.45%   |
| AuthenTec                          | 21        | 4.77%   |
| Elan Microelectronics              | 18        | 4.09%   |
| LighTuning Technology              | 14        | 3.18%   |
| STMicroelectronics                 | 9         | 2.05%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 58        | 13.18%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 39        | 8.86%   |
| Shenzhen Goodix  FingerPrint Device                                        | 37        | 8.41%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 29        | 6.59%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 28        | 6.36%   |
| Unknown                                                                    | 28        | 6.36%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 22        | 5%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 21        | 4.77%   |
| Shenzhen Goodix FingerPrint                                                | 15        | 3.41%   |
| Validity Sensors Synaptics WBDI                                            | 14        | 3.18%   |
| Shenzhen Goodix Fingerprint Reader                                         | 13        | 2.95%   |
| Elan ELAN:Fingerprint                                                      | 12        | 2.73%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 11        | 2.5%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 2.5%    |
| Validity Sensors VFS491                                                    | 8         | 1.82%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 8         | 1.82%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 1.59%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.59%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.36%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.36%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 1.36%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 6         | 1.36%   |
| Elan ELAN:ARM-M4                                                           | 6         | 1.36%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 1.14%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.14%   |
| AuthenTec AES2810                                                          | 4         | 0.91%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.68%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.68%   |
| Synaptics  WBDI                                                            | 3         | 0.68%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.45%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.45%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.45%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.45%   |
| STMicroelectronics TouchChipÂ Fingerprint Reader                          | 2         | 0.45%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.45%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.45%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.23%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.23%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.23%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 79        | 35.27%  |
| Alcor Micro               | 79        | 35.27%  |
| Upek                      | 19        | 8.48%   |
| O2 Micro                  | 19        | 8.48%   |
| Lenovo                    | 14        | 6.25%   |
| Gemalto (was Gemplus)     | 3         | 1.34%   |
| Yubico.com                | 2         | 0.89%   |
| SCM Microsystems          | 2         | 0.89%   |
| Aladdin Knowledge Systems | 2         | 0.89%   |
| OmniKey                   | 1         | 0.45%   |
| Clay Logic                | 1         | 0.45%   |
| Cherry                    | 1         | 0.45%   |
| C3PO                      | 1         | 0.45%   |
| Advanced Card Systems     | 1         | 0.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 78        | 34.82%  |
| Broadcom 58200                                                               | 24        | 10.71%  |
| Broadcom BCM5880 Secure Applications Processor                               | 23        | 10.27%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 19        | 8.48%   |
| Broadcom 5880                                                                | 19        | 8.48%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 16        | 7.14%   |
| Lenovo Integrated Smart Card Reader                                          | 14        | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 4.91%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 1.34%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 2         | 0.89%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.89%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.89%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.89%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.45%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.45%   |
| OmniKey CardMan 4321                                                         | 1         | 0.45%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.45%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.45%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.45%   |
| C3PO LTC31v2                                                                 | 1         | 0.45%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.45%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1719      | 58.73%  |
| 1     | 927       | 31.67%  |
| 2     | 221       | 7.55%   |
| 3     | 52        | 1.78%   |
| 4     | 4         | 0.14%   |
| 5     | 3         | 0.1%    |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 438       | 29.24%  |
| Graphics card            | 396       | 26.44%  |
| Chipcard                 | 207       | 13.82%  |
| Multimedia controller    | 195       | 13.02%  |
| Net/wireless             | 135       | 9.01%   |
| Bluetooth                | 28        | 1.87%   |
| Communication controller | 22        | 1.47%   |
| Storage                  | 19        | 1.27%   |
| Card reader              | 16        | 1.07%   |
| Camera                   | 12        | 0.8%    |
| Net/ethernet             | 8         | 0.53%   |
| Sound                    | 7         | 0.47%   |
| Network                  | 4         | 0.27%   |
| Modem                    | 4         | 0.27%   |
| Flash memory             | 3         | 0.2%    |
| Unassigned class         | 2         | 0.13%   |
| Tv card                  | 1         | 0.07%   |
| Firewire controller      | 1         | 0.07%   |

