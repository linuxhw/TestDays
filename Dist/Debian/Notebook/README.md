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

Total: 6278

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [1165717061](https://linux-hardware.org/?probe=1165717061) | Feb 28, 2023 |
| TUXEDO        | Aura 15 Gen2                | [26a7db2ed8](https://linux-hardware.org/?probe=26a7db2ed8) | Feb 28, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [e56350a1c1](https://linux-hardware.org/?probe=e56350a1c1) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [3fa4d926e0](https://linux-hardware.org/?probe=3fa4d926e0) | Feb 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | [b4bfab8974](https://linux-hardware.org/?probe=b4bfab8974) | Feb 28, 2023 |
| HP            | ProBook 6570b               | [3692011e3f](https://linux-hardware.org/?probe=3692011e3f) | Feb 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [83a611b1ab](https://linux-hardware.org/?probe=83a611b1ab) | Feb 27, 2023 |
| ASUSTek       | UX31A                       | [56654a2659](https://linux-hardware.org/?probe=56654a2659) | Feb 27, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [ccac327e17](https://linux-hardware.org/?probe=ccac327e17) | Feb 27, 2023 |
| Dell          | Latitude 5400               | [b788c61c95](https://linux-hardware.org/?probe=b788c61c95) | Feb 27, 2023 |
| Dell          | Latitude 3510               | [de938c4962](https://linux-hardware.org/?probe=de938c4962) | Feb 27, 2023 |
| ASUSTek       | K52F                        | [fa30ea101a](https://linux-hardware.org/?probe=fa30ea101a) | Feb 27, 2023 |
| Dell          | G3 3590                     | [eb9009fad9](https://linux-hardware.org/?probe=eb9009fad9) | Feb 27, 2023 |
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
| ASUSTek       | Zenbook UX535QE_UM535QE     | [7d7953a826](https://linux-hardware.org/?probe=7d7953a826) | Feb 26, 2023 |
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
| Lenovo        | ThinkPad T440s 20AQ009DG... | [27e2d41750](https://linux-hardware.org/?probe=27e2d41750) | Feb 24, 2023 |
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
| Shanghai Z... | ZXE CRB                     | [478a4b921f](https://linux-hardware.org/?probe=478a4b921f) | Feb 24, 2023 |
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
| Dell          | Latitude 7530               | [4844568edb](https://linux-hardware.org/?probe=4844568edb) | Feb 21, 2023 |
| ASUSTek       | X556UQ                      | [8f645fa6fc](https://linux-hardware.org/?probe=8f645fa6fc) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470 20HDS1DL03    | [25e1a3f801](https://linux-hardware.org/?probe=25e1a3f801) | Feb 21, 2023 |
| Dell          | Inspiron 3468               | [e5977ee094](https://linux-hardware.org/?probe=e5977ee094) | Feb 21, 2023 |
| Dell          | Latitude E6430              | [80c9785ef0](https://linux-hardware.org/?probe=80c9785ef0) | Feb 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | [1c0772ccd7](https://linux-hardware.org/?probe=1c0772ccd7) | Feb 21, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [6ab7953740](https://linux-hardware.org/?probe=6ab7953740) | Feb 20, 2023 |
| Notebook      | PB50_70RF,RD,RC             | [b24f005b1d](https://linux-hardware.org/?probe=b24f005b1d) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | [19d29283ed](https://linux-hardware.org/?probe=19d29283ed) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | [8d1bb46519](https://linux-hardware.org/?probe=8d1bb46519) | Feb 20, 2023 |
| Acer          | Extensa 2520G               | [823c5829a9](https://linux-hardware.org/?probe=823c5829a9) | Feb 20, 2023 |
| HP            | EliteBook 830 G5            | [0cb773d407](https://linux-hardware.org/?probe=0cb773d407) | Feb 20, 2023 |
| Lenovo        | ThinkPad T430 2349PZG       | [7bd3c5a555](https://linux-hardware.org/?probe=7bd3c5a555) | Feb 20, 2023 |
| Acer          | Aspire V5-573G              | [376b35f5b6](https://linux-hardware.org/?probe=376b35f5b6) | Feb 20, 2023 |
| Dell          | Latitude E7270              | [4eb17c846c](https://linux-hardware.org/?probe=4eb17c846c) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | [234358d23e](https://linux-hardware.org/?probe=234358d23e) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | [1b75d34b95](https://linux-hardware.org/?probe=1b75d34b95) | Feb 20, 2023 |
| Notebook      | W54_55SU1,SUW               | [5a296bed7f](https://linux-hardware.org/?probe=5a296bed7f) | Feb 19, 2023 |
| Dell          | XPS 13 9370                 | [e710561f68](https://linux-hardware.org/?probe=e710561f68) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [5300c136fd](https://linux-hardware.org/?probe=5300c136fd) | Feb 19, 2023 |
| Acer          | Nitro AN515-55              | [3158f1e0d5](https://linux-hardware.org/?probe=3158f1e0d5) | Feb 18, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [8907f179e9](https://linux-hardware.org/?probe=8907f179e9) | Feb 18, 2023 |
| Lenovo        | ThinkPad E480 20KN001QGE    | [008f40a707](https://linux-hardware.org/?probe=008f40a707) | Feb 18, 2023 |
| Dell          | Latitude E5450              | [56827b29dc](https://linux-hardware.org/?probe=56827b29dc) | Feb 18, 2023 |
| HP            | Laptop 17-bs0xx             | [cc805e31b0](https://linux-hardware.org/?probe=cc805e31b0) | Feb 17, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | [32f5d5e200](https://linux-hardware.org/?probe=32f5d5e200) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [02e6818311](https://linux-hardware.org/?probe=02e6818311) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [4bf1ccfe74](https://linux-hardware.org/?probe=4bf1ccfe74) | Feb 17, 2023 |
| Apple         | MacBookPro9,1               | [4ab4c99cab](https://linux-hardware.org/?probe=4ab4c99cab) | Feb 17, 2023 |
| Dell          | System XPS L702X            | [81f9738975](https://linux-hardware.org/?probe=81f9738975) | Feb 16, 2023 |
| Dell          | Precision 5570              | [d5f9d13ae3](https://linux-hardware.org/?probe=d5f9d13ae3) | Feb 16, 2023 |
| Apple         | MacBookAir6,2               | [46aafc59c4](https://linux-hardware.org/?probe=46aafc59c4) | Feb 16, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [a4fd7cdaa8](https://linux-hardware.org/?probe=a4fd7cdaa8) | Feb 16, 2023 |
| HP            | EliteBook 2530p             | [5398361b68](https://linux-hardware.org/?probe=5398361b68) | Feb 16, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [73787e9141](https://linux-hardware.org/?probe=73787e9141) | Feb 16, 2023 |
| Dell          | Precision 5570              | [d0f2fa25c3](https://linux-hardware.org/?probe=d0f2fa25c3) | Feb 15, 2023 |
| HUAWEI        | WRT-WX9                     | [13866e78a2](https://linux-hardware.org/?probe=13866e78a2) | Feb 15, 2023 |
| Google        | Grunt                       | [89c633c2c1](https://linux-hardware.org/?probe=89c633c2c1) | Feb 15, 2023 |
| ASUSTek       | K53U                        | [e9a6a69e01](https://linux-hardware.org/?probe=e9a6a69e01) | Feb 15, 2023 |
| Unknown       | T3 MRD                      | [df134a8199](https://linux-hardware.org/?probe=df134a8199) | Feb 14, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [e9faf4ce80](https://linux-hardware.org/?probe=e9faf4ce80) | Feb 14, 2023 |
| Acer          | Aspire V5-572G              | [7f360258ff](https://linux-hardware.org/?probe=7f360258ff) | Feb 14, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [977650806e](https://linux-hardware.org/?probe=977650806e) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [f6bcdb7c6b](https://linux-hardware.org/?probe=f6bcdb7c6b) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [345021f7f6](https://linux-hardware.org/?probe=345021f7f6) | Feb 14, 2023 |
| Lenovo        | ThinkPad P51 20HJS0AR16     | [ad0f22fe34](https://linux-hardware.org/?probe=ad0f22fe34) | Feb 14, 2023 |
| ASUSTek       | X505BP                      | [579388a539](https://linux-hardware.org/?probe=579388a539) | Feb 13, 2023 |
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
| Dell          | Latitude E6330              | [1b5cdf846f](https://linux-hardware.org/?probe=1b5cdf846f) | Feb 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [20a75bea61](https://linux-hardware.org/?probe=20a75bea61) | Feb 11, 2023 |
| HP            | Pavilion g6                 | [35b93693a5](https://linux-hardware.org/?probe=35b93693a5) | Feb 10, 2023 |
| Dell          | Latitude 7370               | [30c62c9e44](https://linux-hardware.org/?probe=30c62c9e44) | Feb 10, 2023 |
| Dell          | Latitude 7370               | [b4e7a5cb63](https://linux-hardware.org/?probe=b4e7a5cb63) | Feb 10, 2023 |
| ASUSTek       | N751JX                      | [fd591a3e67](https://linux-hardware.org/?probe=fd591a3e67) | Feb 10, 2023 |
| Novatech      | NL40_50CU                   | [cca307c7db](https://linux-hardware.org/?probe=cca307c7db) | Feb 10, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [7ac6f508b2](https://linux-hardware.org/?probe=7ac6f508b2) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [8239d80ae0](https://linux-hardware.org/?probe=8239d80ae0) | Feb 10, 2023 |
| Lenovo        | ThinkPad SL510 28477MG      | [8f22e1beaa](https://linux-hardware.org/?probe=8f22e1beaa) | Feb 10, 2023 |
| Samsung       | 550XDA                      | [45d947c9f9](https://linux-hardware.org/?probe=45d947c9f9) | Feb 10, 2023 |
| IBM           | ThinkPad T43 18714AG        | [0730c9228d](https://linux-hardware.org/?probe=0730c9228d) | Feb 10, 2023 |
| HP            | Laptop 17-bs0xx             | [84eb5f0ad8](https://linux-hardware.org/?probe=84eb5f0ad8) | Feb 09, 2023 |
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
| Dell          | Precision 5570              | [6c257e667d](https://linux-hardware.org/?probe=6c257e667d) | Feb 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [d37cc19110](https://linux-hardware.org/?probe=d37cc19110) | Feb 08, 2023 |
| Dell          | Precision 5570              | [e81b3de663](https://linux-hardware.org/?probe=e81b3de663) | Feb 08, 2023 |
| Dell          | Inspiron 5555               | [f5aeb173ba](https://linux-hardware.org/?probe=f5aeb173ba) | Feb 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [def4679f84](https://linux-hardware.org/?probe=def4679f84) | Feb 07, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | [db2f72084a](https://linux-hardware.org/?probe=db2f72084a) | Feb 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [eca3a05d41](https://linux-hardware.org/?probe=eca3a05d41) | Feb 07, 2023 |
| Panasonic     | CF-54-1                     | [32a2acc07e](https://linux-hardware.org/?probe=32a2acc07e) | Feb 07, 2023 |
| Samsung       | R530/R730                   | [f212e58647](https://linux-hardware.org/?probe=f212e58647) | Feb 07, 2023 |
| Samsung       | R530/R730                   | [9ccb976ccd](https://linux-hardware.org/?probe=9ccb976ccd) | Feb 07, 2023 |
| Dell          | Latitude E7250              | [b4a7701aa4](https://linux-hardware.org/?probe=b4a7701aa4) | Feb 07, 2023 |
| Dell          | Precision 5570              | [d279e97c00](https://linux-hardware.org/?probe=d279e97c00) | Feb 07, 2023 |
| Toshiba       | Satellite C655              | [a0c2eb7db1](https://linux-hardware.org/?probe=a0c2eb7db1) | Feb 07, 2023 |
| Google        | Terra                       | [edfe00266c](https://linux-hardware.org/?probe=edfe00266c) | Feb 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | [7d2d46a579](https://linux-hardware.org/?probe=7d2d46a579) | Feb 06, 2023 |
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
| HP            | Laptop 17-bs0xx             | [78ca889e8d](https://linux-hardware.org/?probe=78ca889e8d) | Feb 04, 2023 |
| Lenovo        | ThinkPad T440p 20ANS09W0... | [17f9df8f2c](https://linux-hardware.org/?probe=17f9df8f2c) | Feb 03, 2023 |
| Lenovo        | V310-15IKB 80T3             | [a39fb673c7](https://linux-hardware.org/?probe=a39fb673c7) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [4de96841bf](https://linux-hardware.org/?probe=4de96841bf) | Feb 03, 2023 |
| HP            | Pavilion 15                 | [5909dd08e7](https://linux-hardware.org/?probe=5909dd08e7) | Feb 03, 2023 |
| Acer          | Predator PH315-54           | [fe381cbbfe](https://linux-hardware.org/?probe=fe381cbbfe) | Feb 03, 2023 |
| Aquarius      | NS585                       | [7e944d88b3](https://linux-hardware.org/?probe=7e944d88b3) | Feb 03, 2023 |
| HP            | ProBook 450 G7              | [ae290fa64e](https://linux-hardware.org/?probe=ae290fa64e) | Feb 03, 2023 |
| HP            | ProBook 450 G7              | [7820377760](https://linux-hardware.org/?probe=7820377760) | Feb 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [c122070f4f](https://linux-hardware.org/?probe=c122070f4f) | Feb 03, 2023 |
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
| HUAWEI        | HLYL-WXX9                   | [6e8d45f76b](https://linux-hardware.org/?probe=6e8d45f76b) | Jan 31, 2023 |
| HP            | Notebook                    | [3cea0a0519](https://linux-hardware.org/?probe=3cea0a0519) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [1c798340db](https://linux-hardware.org/?probe=1c798340db) | Jan 31, 2023 |
| Fujitsu       | LIFEBOOK S751               | [35948f3b5e](https://linux-hardware.org/?probe=35948f3b5e) | Jan 31, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [3f17be7a85](https://linux-hardware.org/?probe=3f17be7a85) | Jan 30, 2023 |
| HP            | Laptop 17-bs0xx             | [ed57a59e39](https://linux-hardware.org/?probe=ed57a59e39) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [3ecd91770e](https://linux-hardware.org/?probe=3ecd91770e) | Jan 30, 2023 |
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
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [8ef4f014f2](https://linux-hardware.org/?probe=8ef4f014f2) | Jan 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | [c83903fdc8](https://linux-hardware.org/?probe=c83903fdc8) | Jan 27, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [376c580dcb](https://linux-hardware.org/?probe=376c580dcb) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [d3adeb692c](https://linux-hardware.org/?probe=d3adeb692c) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [46b1227255](https://linux-hardware.org/?probe=46b1227255) | Jan 27, 2023 |
| MSI           | Creator 17 B11UE            | [fcf56cfe4d](https://linux-hardware.org/?probe=fcf56cfe4d) | Jan 27, 2023 |
| Dell          | Latitude 5420               | [379a2dc9ab](https://linux-hardware.org/?probe=379a2dc9ab) | Jan 26, 2023 |
| Dell          | Latitude 5420               | [eec8ef8ddb](https://linux-hardware.org/?probe=eec8ef8ddb) | Jan 26, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0P    | [1a36af70e8](https://linux-hardware.org/?probe=1a36af70e8) | Jan 26, 2023 |
| Google        | Careena                     | [75ca1a25dd](https://linux-hardware.org/?probe=75ca1a25dd) | Jan 26, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [a780c8d844](https://linux-hardware.org/?probe=a780c8d844) | Jan 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [e6a1506275](https://linux-hardware.org/?probe=e6a1506275) | Jan 25, 2023 |
| Apple         | MacBookPro10,1              | [4643f751cf](https://linux-hardware.org/?probe=4643f751cf) | Jan 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [3b96eac8a9](https://linux-hardware.org/?probe=3b96eac8a9) | Jan 25, 2023 |
| Panasonic     | FZ55-2                      | [dd9ddb12b6](https://linux-hardware.org/?probe=dd9ddb12b6) | Jan 25, 2023 |
| Lenovo        | ThinkPad X220 4291IR6       | [cc41fa5174](https://linux-hardware.org/?probe=cc41fa5174) | Jan 25, 2023 |
| Dell          | Vostro 5470                 | [bfd4198155](https://linux-hardware.org/?probe=bfd4198155) | Jan 25, 2023 |
| Samsung       | R710                        | [17a3e2ddd9](https://linux-hardware.org/?probe=17a3e2ddd9) | Jan 25, 2023 |
| HP            | ZBook 15 G3                 | [0bde1ca99a](https://linux-hardware.org/?probe=0bde1ca99a) | Jan 24, 2023 |
| Packard Be... | EasyNote MH36               | [07ba548a55](https://linux-hardware.org/?probe=07ba548a55) | Jan 24, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [bf21a44322](https://linux-hardware.org/?probe=bf21a44322) | Jan 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [fd6d2ec3c2](https://linux-hardware.org/?probe=fd6d2ec3c2) | Jan 23, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [c8ec385a88](https://linux-hardware.org/?probe=c8ec385a88) | Jan 23, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [5648fbf4a0](https://linux-hardware.org/?probe=5648fbf4a0) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [62ac206f7e](https://linux-hardware.org/?probe=62ac206f7e) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [5c7625e3f8](https://linux-hardware.org/?probe=5c7625e3f8) | Jan 23, 2023 |
| Fujitsu       | LIFEBOOK S751               | [ff727a3560](https://linux-hardware.org/?probe=ff727a3560) | Jan 22, 2023 |
| Fujitsu       | LIFEBOOK S751               | [df0676ac87](https://linux-hardware.org/?probe=df0676ac87) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [ae270718a7](https://linux-hardware.org/?probe=ae270718a7) | Jan 22, 2023 |
| Dell          | G3 3579                     | [63298dcee9](https://linux-hardware.org/?probe=63298dcee9) | Jan 22, 2023 |
| Danew         | Dbook 131                   | [08911c133e](https://linux-hardware.org/?probe=08911c133e) | Jan 22, 2023 |
| Clevo         | W150ER                      | [ba5d06437c](https://linux-hardware.org/?probe=ba5d06437c) | Jan 21, 2023 |
| Acer          | Aspire F5-573G              | [68847eb1e6](https://linux-hardware.org/?probe=68847eb1e6) | Jan 21, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [4b9d2e6e26](https://linux-hardware.org/?probe=4b9d2e6e26) | Jan 21, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [15dde971f3](https://linux-hardware.org/?probe=15dde971f3) | Jan 21, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [f5bb76ae13](https://linux-hardware.org/?probe=f5bb76ae13) | Jan 21, 2023 |
| Google        | Phaser                      | [557e69c5f1](https://linux-hardware.org/?probe=557e69c5f1) | Jan 21, 2023 |
| HP            | EliteBook Folio 9480m       | [cf1b67c224](https://linux-hardware.org/?probe=cf1b67c224) | Jan 21, 2023 |
| HP            | EliteBook 840 G3            | [06f6499264](https://linux-hardware.org/?probe=06f6499264) | Jan 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [27e484698b](https://linux-hardware.org/?probe=27e484698b) | Jan 20, 2023 |
| Dell          | Latitude 5501               | [d31f972a20](https://linux-hardware.org/?probe=d31f972a20) | Jan 20, 2023 |
| Lenovo        | G505 20240                  | [c591d80181](https://linux-hardware.org/?probe=c591d80181) | Jan 20, 2023 |
| UMAX          | VisionBook 12Wr             | [0707d617f7](https://linux-hardware.org/?probe=0707d617f7) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490s 20NYS3SX0... | [3e08ab25c6](https://linux-hardware.org/?probe=3e08ab25c6) | Jan 20, 2023 |
| Dell          | Latitude E6540              | [34c018d211](https://linux-hardware.org/?probe=34c018d211) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [80cb1c8239](https://linux-hardware.org/?probe=80cb1c8239) | Jan 19, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [7ecc4d20c3](https://linux-hardware.org/?probe=7ecc4d20c3) | Jan 19, 2023 |
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
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [6dab459ed2](https://linux-hardware.org/?probe=6dab459ed2) | Jan 18, 2023 |
| HP            | EliteBook 820 G4            | [430b938694](https://linux-hardware.org/?probe=430b938694) | Jan 18, 2023 |
| HP            | EliteBook 2170p             | [46705d578e](https://linux-hardware.org/?probe=46705d578e) | Jan 18, 2023 |
| HP            | EliteBook 840 G4            | [952c81c314](https://linux-hardware.org/?probe=952c81c314) | Jan 18, 2023 |
| Dell          | Latitude 5500               | [e0ae9cb026](https://linux-hardware.org/?probe=e0ae9cb026) | Jan 17, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [99e10e5d0f](https://linux-hardware.org/?probe=99e10e5d0f) | Jan 17, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [624f47d1e3](https://linux-hardware.org/?probe=624f47d1e3) | Jan 17, 2023 |
| HP            | Compaq 6730b (GW687AV)      | [e967b291d5](https://linux-hardware.org/?probe=e967b291d5) | Jan 17, 2023 |
| Dell          | Inspiron 5502               | [43c4f532aa](https://linux-hardware.org/?probe=43c4f532aa) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [804fe39b80](https://linux-hardware.org/?probe=804fe39b80) | Jan 16, 2023 |
| Positivo      | CHT14B                      | [ab4518f121](https://linux-hardware.org/?probe=ab4518f121) | Jan 16, 2023 |
| Dell          | Inspiron 15-3567            | [020e19b05d](https://linux-hardware.org/?probe=020e19b05d) | Jan 16, 2023 |
| Lenovo        | ThinkPad T490s 20NX0076M... | [4c896e2c0e](https://linux-hardware.org/?probe=4c896e2c0e) | Jan 16, 2023 |
| Dell          | Inspiron 5502               | [9403074843](https://linux-hardware.org/?probe=9403074843) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [47d090108d](https://linux-hardware.org/?probe=47d090108d) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [219091b4e0](https://linux-hardware.org/?probe=219091b4e0) | Jan 15, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [a09ace045e](https://linux-hardware.org/?probe=a09ace045e) | Jan 15, 2023 |
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
| Apple         | MacBookPro12,1              | [1402c185c7](https://linux-hardware.org/?probe=1402c185c7) | Jan 14, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [f862a7e702](https://linux-hardware.org/?probe=f862a7e702) | Jan 14, 2023 |
| HONOR         | HLYL-WXX9                   | [e5b02d94cd](https://linux-hardware.org/?probe=e5b02d94cd) | Jan 14, 2023 |
| Dell          | Inspiron 11 - 3147          | [7193100d05](https://linux-hardware.org/?probe=7193100d05) | Jan 14, 2023 |
| HP            | Pavilion g6                 | [7672e1178a](https://linux-hardware.org/?probe=7672e1178a) | Jan 14, 2023 |
| Panasonic     | CFSZ6-2                     | [7a9f534294](https://linux-hardware.org/?probe=7a9f534294) | Jan 13, 2023 |
| Unknown       | Unknown                     | [ce69bfd81b](https://linux-hardware.org/?probe=ce69bfd81b) | Jan 13, 2023 |
| HP            | ProBook 445 G7              | [baf20b6914](https://linux-hardware.org/?probe=baf20b6914) | Jan 13, 2023 |
| ASUSTek       | X450LD                      | [859eb05149](https://linux-hardware.org/?probe=859eb05149) | Jan 13, 2023 |
| Dell          | Latitude 3320               | [f10d2a0741](https://linux-hardware.org/?probe=f10d2a0741) | Jan 13, 2023 |
| Dell          | Latitude 3320               | [613d7d50eb](https://linux-hardware.org/?probe=613d7d50eb) | Jan 13, 2023 |
| HP            | Compaq 6735b                | [01878ee027](https://linux-hardware.org/?probe=01878ee027) | Jan 12, 2023 |
| Dell          | Inspiron 3521               | [694d5be301](https://linux-hardware.org/?probe=694d5be301) | Jan 12, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [d4691b9969](https://linux-hardware.org/?probe=d4691b9969) | Jan 12, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [2316d5dc8b](https://linux-hardware.org/?probe=2316d5dc8b) | Jan 12, 2023 |
| Lenovo        | ThinkPad T470p 20J7S1JT0... | [856d91c1ca](https://linux-hardware.org/?probe=856d91c1ca) | Jan 12, 2023 |
| Gateway       | M-6854m                     | [76f293b62b](https://linux-hardware.org/?probe=76f293b62b) | Jan 12, 2023 |
| Dell          | Precision M4400             | [27da7825fb](https://linux-hardware.org/?probe=27da7825fb) | Jan 12, 2023 |
| Dell          | Inspiron 3421               | [055d61383e](https://linux-hardware.org/?probe=055d61383e) | Jan 12, 2023 |
| Acer          | Swift SF314-56              | [46aebbe972](https://linux-hardware.org/?probe=46aebbe972) | Jan 11, 2023 |
| Lenovo        | V110-15ISK 80TL             | [c00918a4c8](https://linux-hardware.org/?probe=c00918a4c8) | Jan 11, 2023 |
| SLIMBOOK      | PRO                         | [551a4bd378](https://linux-hardware.org/?probe=551a4bd378) | Jan 11, 2023 |
| HP            | ProBook 430 G5              | [6403930d67](https://linux-hardware.org/?probe=6403930d67) | Jan 11, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [6c67fc3995](https://linux-hardware.org/?probe=6c67fc3995) | Jan 11, 2023 |
| Aquarius      | NS585                       | [6fbcdf4d2f](https://linux-hardware.org/?probe=6fbcdf4d2f) | Jan 10, 2023 |
| HP            | Mini 110-1000               | [05c4656700](https://linux-hardware.org/?probe=05c4656700) | Jan 10, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [8367c27d81](https://linux-hardware.org/?probe=8367c27d81) | Jan 10, 2023 |
| Aquarius      | NS585                       | [2d37eb6524](https://linux-hardware.org/?probe=2d37eb6524) | Jan 10, 2023 |
| MPMAN         | CONVERTER 102               | [cc1eb56fbc](https://linux-hardware.org/?probe=cc1eb56fbc) | Jan 10, 2023 |
| HP            | 15                          | [f6b287dae1](https://linux-hardware.org/?probe=f6b287dae1) | Jan 10, 2023 |
| Acer          | Nitro AN517-54              | [8ea20821c8](https://linux-hardware.org/?probe=8ea20821c8) | Jan 10, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | [8d0b4a504d](https://linux-hardware.org/?probe=8d0b4a504d) | Jan 09, 2023 |
| Acer          | Aspire A515-54G             | [dea6736468](https://linux-hardware.org/?probe=dea6736468) | Jan 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e85e91a7f2](https://linux-hardware.org/?probe=e85e91a7f2) | Jan 09, 2023 |
| Acer          | Aspire one 1-131            | [06c3411258](https://linux-hardware.org/?probe=06c3411258) | Jan 08, 2023 |
| HP            | ZBook 15 G3                 | [648dcae4c6](https://linux-hardware.org/?probe=648dcae4c6) | Jan 08, 2023 |
| ASUSTek       | K53U                        | [63849b1b5a](https://linux-hardware.org/?probe=63849b1b5a) | Jan 08, 2023 |
| Apple         | MacBookAir7,2               | [a4e777ea7d](https://linux-hardware.org/?probe=a4e777ea7d) | Jan 08, 2023 |
| Digma         | Pro Fortis M DN15P3-8CXN... | [077fd44029](https://linux-hardware.org/?probe=077fd44029) | Jan 08, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2SX1... | [3c35917c78](https://linux-hardware.org/?probe=3c35917c78) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | [e546680389](https://linux-hardware.org/?probe=e546680389) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | [d556eedbbf](https://linux-hardware.org/?probe=d556eedbbf) | Jan 07, 2023 |
| Acer          | Aspire 7745G                | [9119962d1f](https://linux-hardware.org/?probe=9119962d1f) | Jan 07, 2023 |
| Gigabyte      | G5 GE                       | [d6a4584809](https://linux-hardware.org/?probe=d6a4584809) | Jan 07, 2023 |
| Dell          | Latitude 2110               | [9910f8985b](https://linux-hardware.org/?probe=9910f8985b) | Jan 07, 2023 |
| HP            | Elite x2 1011 G1 Tablet     | [28c9b60939](https://linux-hardware.org/?probe=28c9b60939) | Jan 07, 2023 |
| TUXEDO        | Aura 15 Gen1                | [fa91397209](https://linux-hardware.org/?probe=fa91397209) | Jan 07, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [9776545fc4](https://linux-hardware.org/?probe=9776545fc4) | Jan 06, 2023 |
| Toshiba       | Satellite C55Dt-A           | [f3cfb5dbb5](https://linux-hardware.org/?probe=f3cfb5dbb5) | Jan 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [9b0a8d487e](https://linux-hardware.org/?probe=9b0a8d487e) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [d069cbd46b](https://linux-hardware.org/?probe=d069cbd46b) | Jan 06, 2023 |
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
| Acer          | Aspire V3-574G              | [a889bba557](https://linux-hardware.org/?probe=a889bba557) | Jan 02, 2023 |
| Acer          | Aspire ES1-711              | [735e062168](https://linux-hardware.org/?probe=735e062168) | Jan 02, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [90603e4ab3](https://linux-hardware.org/?probe=90603e4ab3) | Jan 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [70c50fe035](https://linux-hardware.org/?probe=70c50fe035) | Jan 02, 2023 |
| MSI           | GE75 Raider 8SG             | [b6fa9be350](https://linux-hardware.org/?probe=b6fa9be350) | Jan 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [b54f3aab7b](https://linux-hardware.org/?probe=b54f3aab7b) | Jan 02, 2023 |
| HP            | 250 G8 Notebook PC          | [42e877ed10](https://linux-hardware.org/?probe=42e877ed10) | Jan 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [8d4934bc09](https://linux-hardware.org/?probe=8d4934bc09) | Jan 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0D    | [a1f966e5e8](https://linux-hardware.org/?probe=a1f966e5e8) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [08fb8de608](https://linux-hardware.org/?probe=08fb8de608) | Jan 02, 2023 |
| Lenovo        | ThinkPad T430u 33519LC      | [87af3fa7f0](https://linux-hardware.org/?probe=87af3fa7f0) | Jan 02, 2023 |
| ASUSTek       | ZenBook UX333FN_U3300FN     | [750a40a3cc](https://linux-hardware.org/?probe=750a40a3cc) | Jan 02, 2023 |
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
| Toshiba       | Satellite L775-12V          | [2c601f6366](https://linux-hardware.org/?probe=2c601f6366) | Dec 29, 2022 |
| Lenovo        | ThinkPad T470p 20J7S1JT0... | [4b7bbb186f](https://linux-hardware.org/?probe=4b7bbb186f) | Dec 29, 2022 |
| MACHCREATO... | AB                          | [52a6beb872](https://linux-hardware.org/?probe=52a6beb872) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | [5bf3ff5c0e](https://linux-hardware.org/?probe=5bf3ff5c0e) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | [4f63c4474c](https://linux-hardware.org/?probe=4f63c4474c) | Dec 29, 2022 |
| HP            | EliteBook Folio 1040 G3     | [6aad572cd5](https://linux-hardware.org/?probe=6aad572cd5) | Dec 29, 2022 |
| HP            | ZBook 15 G6                 | [af1655497e](https://linux-hardware.org/?probe=af1655497e) | Dec 29, 2022 |
| HP            | ProBook 6570b               | [46fd918b7c](https://linux-hardware.org/?probe=46fd918b7c) | Dec 29, 2022 |
| HP            | Pavilion g7                 | [444363b7ec](https://linux-hardware.org/?probe=444363b7ec) | Dec 29, 2022 |
| Dell          | Inspiron 5490               | [457c2ae4ae](https://linux-hardware.org/?probe=457c2ae4ae) | Dec 28, 2022 |
| Dell          | Inspiron 5490               | [fdfd0f21c7](https://linux-hardware.org/?probe=fdfd0f21c7) | Dec 28, 2022 |
| Dell          | Inspiron 3583               | [41c7a16579](https://linux-hardware.org/?probe=41c7a16579) | Dec 28, 2022 |
| Toshiba       | Satellite L455D             | [35c085aa82](https://linux-hardware.org/?probe=35c085aa82) | Dec 28, 2022 |
| Dell          | Vostro 3400                 | [27f58a8ad1](https://linux-hardware.org/?probe=27f58a8ad1) | Dec 28, 2022 |
| Acer          | Aspire ES1-531              | [c29088a63f](https://linux-hardware.org/?probe=c29088a63f) | Dec 28, 2022 |
| HP            | ProBook 6470b               | [055705b3f2](https://linux-hardware.org/?probe=055705b3f2) | Dec 28, 2022 |
| Apple         | MacBookAir7,2               | [10dce91da1](https://linux-hardware.org/?probe=10dce91da1) | Dec 27, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [321cc72064](https://linux-hardware.org/?probe=321cc72064) | Dec 27, 2022 |
| Apple         | MacBookAir7,1               | [d174ffb318](https://linux-hardware.org/?probe=d174ffb318) | Dec 27, 2022 |
| MSI           | GE62 2QC                    | [dbd69d70ac](https://linux-hardware.org/?probe=dbd69d70ac) | Dec 27, 2022 |
| Panasonic     | FZ55-2                      | [1699b7c3b2](https://linux-hardware.org/?probe=1699b7c3b2) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [78c6c15502](https://linux-hardware.org/?probe=78c6c15502) | Dec 27, 2022 |
| Notebook      | L14xMU                      | [7644bc65e2](https://linux-hardware.org/?probe=7644bc65e2) | Dec 27, 2022 |
| Dell          | Inspiron 1012               | [3dd6b8a416](https://linux-hardware.org/?probe=3dd6b8a416) | Dec 26, 2022 |
| Exo           | Smart Serie M               | [942ee3b035](https://linux-hardware.org/?probe=942ee3b035) | Dec 26, 2022 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [3bb1c5cc47](https://linux-hardware.org/?probe=3bb1c5cc47) | Dec 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [29a54c4976](https://linux-hardware.org/?probe=29a54c4976) | Dec 26, 2022 |
| Acer          | Aspire ES1-533              | [3b5fa6d85a](https://linux-hardware.org/?probe=3b5fa6d85a) | Dec 26, 2022 |
| Lenovo        | ThinkPad X250 20CLS1UB00    | [fc8b2899fa](https://linux-hardware.org/?probe=fc8b2899fa) | Dec 25, 2022 |
| SANTECH       | NHx0DB,DE                   | [a0996d42bd](https://linux-hardware.org/?probe=a0996d42bd) | Dec 25, 2022 |
| HP            | 470 G8 Notebook PC          | [6d77c48324](https://linux-hardware.org/?probe=6d77c48324) | Dec 25, 2022 |
| ASUSTek       | G751JT                      | [16e989ff99](https://linux-hardware.org/?probe=16e989ff99) | Dec 25, 2022 |
| Dell          | Latitude E6520              | [33a51c934d](https://linux-hardware.org/?probe=33a51c934d) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | [ea09a6daa8](https://linux-hardware.org/?probe=ea09a6daa8) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | [45737153e4](https://linux-hardware.org/?probe=45737153e4) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | [42221f61fb](https://linux-hardware.org/?probe=42221f61fb) | Dec 25, 2022 |
| Unknown       | Apple MacBook Pro (14-in... | [8a5b919c91](https://linux-hardware.org/?probe=8a5b919c91) | Dec 24, 2022 |
| Medion        | E122X                       | [6e4e34bcc3](https://linux-hardware.org/?probe=6e4e34bcc3) | Dec 24, 2022 |
| Medion        | E122X                       | [bf41c45a7d](https://linux-hardware.org/?probe=bf41c45a7d) | Dec 24, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [096d4fc8c2](https://linux-hardware.org/?probe=096d4fc8c2) | Dec 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c5f2f2db53](https://linux-hardware.org/?probe=c5f2f2db53) | Dec 24, 2022 |
| Lenovo        | ThinkPad X270 20HMS16200    | [6ac6e552a8](https://linux-hardware.org/?probe=6ac6e552a8) | Dec 24, 2022 |
| Dell          | Inspiron 5570               | [1c7e7f8dd2](https://linux-hardware.org/?probe=1c7e7f8dd2) | Dec 24, 2022 |
| HP            | Laptop 15-dy2xxx            | [df787f1286](https://linux-hardware.org/?probe=df787f1286) | Dec 24, 2022 |
| HP            | Laptop 15-dy2xxx            | [0a2ed74cfd](https://linux-hardware.org/?probe=0a2ed74cfd) | Dec 23, 2022 |
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
| Packard Be... | DOT S                       | [c26f1d77e6](https://linux-hardware.org/?probe=c26f1d77e6) | Dec 22, 2022 |
| HP            | Stream Notebook PC 13       | [b049c64ff7](https://linux-hardware.org/?probe=b049c64ff7) | Dec 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [5f132c928b](https://linux-hardware.org/?probe=5f132c928b) | Dec 22, 2022 |
| Dell          | G3 3590                     | [8038491eb0](https://linux-hardware.org/?probe=8038491eb0) | Dec 22, 2022 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [16cae3015a](https://linux-hardware.org/?probe=16cae3015a) | Dec 21, 2022 |
| Apple         | MacBookAir7,2               | [b4e828bef3](https://linux-hardware.org/?probe=b4e828bef3) | Dec 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [28013105ef](https://linux-hardware.org/?probe=28013105ef) | Dec 21, 2022 |
| Dell          | Vostro 3583                 | [cf3c6eb18b](https://linux-hardware.org/?probe=cf3c6eb18b) | Dec 21, 2022 |
| Apple         | MacBookAir7,2               | [056d76bae8](https://linux-hardware.org/?probe=056d76bae8) | Dec 21, 2022 |
| Sony          | SVE1112M1EB                 | [74e100e63b](https://linux-hardware.org/?probe=74e100e63b) | Dec 21, 2022 |
| HP            | ZBook Power 15.6 inch G8... | [6b202d6cc2](https://linux-hardware.org/?probe=6b202d6cc2) | Dec 21, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [9438c80c85](https://linux-hardware.org/?probe=9438c80c85) | Dec 21, 2022 |
| Dell          | Inspiron 3501               | [449e38a14d](https://linux-hardware.org/?probe=449e38a14d) | Dec 21, 2022 |
| Dell          | G3 3590                     | [8272655600](https://linux-hardware.org/?probe=8272655600) | Dec 21, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [cd4fa20e66](https://linux-hardware.org/?probe=cd4fa20e66) | Dec 20, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e676fe186f](https://linux-hardware.org/?probe=e676fe186f) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [658e730bd3](https://linux-hardware.org/?probe=658e730bd3) | Dec 20, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [1e53c20bdd](https://linux-hardware.org/?probe=1e53c20bdd) | Dec 20, 2022 |
| ASUSTek       | T100TA                      | [1dc546e14a](https://linux-hardware.org/?probe=1dc546e14a) | Dec 20, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [2aeb8fd0cd](https://linux-hardware.org/?probe=2aeb8fd0cd) | Dec 19, 2022 |
| HP            | 255 G8 Notebook PC          | [08800ce691](https://linux-hardware.org/?probe=08800ce691) | Dec 19, 2022 |
| ASUSTek       | 900SD                       | [43d2c88062](https://linux-hardware.org/?probe=43d2c88062) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | [956aaecbb9](https://linux-hardware.org/?probe=956aaecbb9) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | [d5ceb48450](https://linux-hardware.org/?probe=d5ceb48450) | Dec 18, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [756263bf48](https://linux-hardware.org/?probe=756263bf48) | Dec 18, 2022 |
| EUROCOM       | SCORPIUS 3D                 | [4fdf299276](https://linux-hardware.org/?probe=4fdf299276) | Dec 18, 2022 |
| Acer          | TravelMate P253             | [97d650e93f](https://linux-hardware.org/?probe=97d650e93f) | Dec 18, 2022 |
| Dell          | Latitude E6530              | [198a9bc936](https://linux-hardware.org/?probe=198a9bc936) | Dec 18, 2022 |
| HP            | Pavilion g7                 | [9829a799a0](https://linux-hardware.org/?probe=9829a799a0) | Dec 18, 2022 |
| Lenovo        | ThinkPad T470 20HES3JR02    | [f9e4638f19](https://linux-hardware.org/?probe=f9e4638f19) | Dec 18, 2022 |
| Dell          | Inspiron N5110              | [9e4f7a69c9](https://linux-hardware.org/?probe=9e4f7a69c9) | Dec 18, 2022 |
| Dell          | Latitude E4310              | [ace267f47c](https://linux-hardware.org/?probe=ace267f47c) | Dec 18, 2022 |
| Acer          | Aspire E5-573G              | [937a672cb0](https://linux-hardware.org/?probe=937a672cb0) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1e2531fdf1](https://linux-hardware.org/?probe=1e2531fdf1) | Dec 17, 2022 |
| Lenovo        | K14 Gen 1 21CUS02600        | [218654b079](https://linux-hardware.org/?probe=218654b079) | Dec 17, 2022 |
| Dell          | Inspiron 14 5425            | [e7d96ccda5](https://linux-hardware.org/?probe=e7d96ccda5) | Dec 17, 2022 |
| HP            | Notebook                    | [844d855f78](https://linux-hardware.org/?probe=844d855f78) | Dec 17, 2022 |
| Unknown       | Unknown                     | [208016df07](https://linux-hardware.org/?probe=208016df07) | Dec 17, 2022 |
| Acer          | TravelMate P253             | [80188fd5bf](https://linux-hardware.org/?probe=80188fd5bf) | Dec 16, 2022 |
| Dell          | Inspiron 7590               | [e8fb837cf5](https://linux-hardware.org/?probe=e8fb837cf5) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | [5cc0ff812b](https://linux-hardware.org/?probe=5cc0ff812b) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | [062a6ed428](https://linux-hardware.org/?probe=062a6ed428) | Dec 16, 2022 |
| Google        | Laser14                     | [b07a01ffe4](https://linux-hardware.org/?probe=b07a01ffe4) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [db670caadd](https://linux-hardware.org/?probe=db670caadd) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d5cf351351](https://linux-hardware.org/?probe=d5cf351351) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e2056deb8a](https://linux-hardware.org/?probe=e2056deb8a) | Dec 16, 2022 |
| Intel         | powered classmate PC        | [e0401225a2](https://linux-hardware.org/?probe=e0401225a2) | Dec 15, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [13ee187e45](https://linux-hardware.org/?probe=13ee187e45) | Dec 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [bec79890c8](https://linux-hardware.org/?probe=bec79890c8) | Dec 15, 2022 |
| Unknown       | T3 MRD                      | [909e1a1604](https://linux-hardware.org/?probe=909e1a1604) | Dec 15, 2022 |
| Google        | Cyan                        | [2b9f20b7da](https://linux-hardware.org/?probe=2b9f20b7da) | Dec 15, 2022 |
| Lenovo        | ThinkPad T430 2349I62       | [f7590c1a07](https://linux-hardware.org/?probe=f7590c1a07) | Dec 15, 2022 |
| Dell          | Latitude 3490               | [af008f69f1](https://linux-hardware.org/?probe=af008f69f1) | Dec 14, 2022 |
| Acer          | Aspire 5738                 | [c0c4581310](https://linux-hardware.org/?probe=c0c4581310) | Dec 14, 2022 |
| Apple         | MacBook6,1                  | [f19d464a26](https://linux-hardware.org/?probe=f19d464a26) | Dec 14, 2022 |
| ASUSTek       | M3N                         | [4e9f8e4c01](https://linux-hardware.org/?probe=4e9f8e4c01) | Dec 14, 2022 |
| ASUSTek       | X302LA                      | [8404a0b0c6](https://linux-hardware.org/?probe=8404a0b0c6) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [14f87b8695](https://linux-hardware.org/?probe=14f87b8695) | Dec 13, 2022 |
| ASUSTek       | M3N                         | [ff772de294](https://linux-hardware.org/?probe=ff772de294) | Dec 13, 2022 |
| Dell          | Latitude 5520               | [7e5d86eaaf](https://linux-hardware.org/?probe=7e5d86eaaf) | Dec 13, 2022 |
| ASUSTek       | G75VW                       | [8d2a0ec4e4](https://linux-hardware.org/?probe=8d2a0ec4e4) | Dec 13, 2022 |
| Exo           | Smart Serie M               | [7fcf3d09bb](https://linux-hardware.org/?probe=7fcf3d09bb) | Dec 13, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [49fad98b7b](https://linux-hardware.org/?probe=49fad98b7b) | Dec 12, 2022 |
| Google        | Terra                       | [765deab389](https://linux-hardware.org/?probe=765deab389) | Dec 12, 2022 |
| HP            | EliteBook 8460p             | [95dc27194a](https://linux-hardware.org/?probe=95dc27194a) | Dec 12, 2022 |
| MSI           | GP73 Leopard 8RD            | [548de8bdae](https://linux-hardware.org/?probe=548de8bdae) | Dec 12, 2022 |
| Acer          | Aspire A515-56              | [5437de2b1b](https://linux-hardware.org/?probe=5437de2b1b) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [dc916ac78c](https://linux-hardware.org/?probe=dc916ac78c) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [2bfcc16f6b](https://linux-hardware.org/?probe=2bfcc16f6b) | Dec 12, 2022 |
| Google        | Enguarde                    | [60cce42479](https://linux-hardware.org/?probe=60cce42479) | Dec 12, 2022 |
| Lenovo        | ThinkPad R61e 7650DHU       | [138f60e67c](https://linux-hardware.org/?probe=138f60e67c) | Dec 12, 2022 |
| HP            | EliteBook 8460p             | [99c965b83f](https://linux-hardware.org/?probe=99c965b83f) | Dec 12, 2022 |
| Dell          | Latitude 5411               | [af806502e8](https://linux-hardware.org/?probe=af806502e8) | Dec 12, 2022 |
| Acer          | Nitro AN515-51              | [918c340b04](https://linux-hardware.org/?probe=918c340b04) | Dec 12, 2022 |
| Lenovo        | ThinkPad T470 20HES6HC00    | [ca9d609d9d](https://linux-hardware.org/?probe=ca9d609d9d) | Dec 12, 2022 |
| HP            | Laptop 15-db1xxx            | [3dcbd61f9e](https://linux-hardware.org/?probe=3dcbd61f9e) | Dec 12, 2022 |
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
| Toshiba       | TECRA A11                   | [766f95a2dd](https://linux-hardware.org/?probe=766f95a2dd) | Dec 10, 2022 |
| SANTECH       | NHx0DB,DE                   | [89e8d0f23e](https://linux-hardware.org/?probe=89e8d0f23e) | Dec 10, 2022 |
| Lenovo        | ThinkPad 13 20J10046US      | [170accb6cc](https://linux-hardware.org/?probe=170accb6cc) | Dec 09, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [5d96a0484a](https://linux-hardware.org/?probe=5d96a0484a) | Dec 08, 2022 |
| HUAWEI        | KLVL-WXXW                   | [adea8bc8d8](https://linux-hardware.org/?probe=adea8bc8d8) | Dec 08, 2022 |
| Toshiba       | Satellite C850-1LJ          | [4af2ab112f](https://linux-hardware.org/?probe=4af2ab112f) | Dec 08, 2022 |
| ASUSTek       | N750JV                      | [e06c6025f3](https://linux-hardware.org/?probe=e06c6025f3) | Dec 08, 2022 |
| Lenovo        | ThinkPad T61 889502U        | [b9d0a07e47](https://linux-hardware.org/?probe=b9d0a07e47) | Dec 08, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [09de0ec660](https://linux-hardware.org/?probe=09de0ec660) | Dec 08, 2022 |
| Lenovo        | ThinkPad T60 1953PKK        | [fc308e2f1c](https://linux-hardware.org/?probe=fc308e2f1c) | Dec 08, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | [e13e889312](https://linux-hardware.org/?probe=e13e889312) | Dec 08, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [b0f77fed1f](https://linux-hardware.org/?probe=b0f77fed1f) | Dec 08, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [e56fd20ec9](https://linux-hardware.org/?probe=e56fd20ec9) | Dec 08, 2022 |
| Lenovo        | ThinkPad E495 20NES0J800    | [17182155b5](https://linux-hardware.org/?probe=17182155b5) | Dec 07, 2022 |
| Lenovo        | ThinkPad X230 2320CTO       | [b74f2893d0](https://linux-hardware.org/?probe=b74f2893d0) | Dec 07, 2022 |
| Panasonic     | CFMX4-1                     | [c25c16fc1a](https://linux-hardware.org/?probe=c25c16fc1a) | Dec 06, 2022 |
| Dell          | Latitude 5310               | [06d96a49a1](https://linux-hardware.org/?probe=06d96a49a1) | Dec 06, 2022 |
| HP            | EliteBook 8470p             | [e2be1fe149](https://linux-hardware.org/?probe=e2be1fe149) | Dec 06, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [4e43c26029](https://linux-hardware.org/?probe=4e43c26029) | Dec 06, 2022 |
| Dell          | Latitude 5411               | [62e5941721](https://linux-hardware.org/?probe=62e5941721) | Dec 06, 2022 |
| Dell          | Latitude 5411               | [e0815067bd](https://linux-hardware.org/?probe=e0815067bd) | Dec 06, 2022 |
| Dell          | Latitude 5310               | [f3801600ff](https://linux-hardware.org/?probe=f3801600ff) | Dec 06, 2022 |
| HP            | EliteBook 2570p             | [fc7d866c16](https://linux-hardware.org/?probe=fc7d866c16) | Dec 06, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [03aba4d315](https://linux-hardware.org/?probe=03aba4d315) | Dec 06, 2022 |
| Lenovo        | ThinkPad X230 2325SDE       | [4dc49eeb10](https://linux-hardware.org/?probe=4dc49eeb10) | Dec 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0e42e5cbeb](https://linux-hardware.org/?probe=0e42e5cbeb) | Dec 06, 2022 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [5b72cdbdb8](https://linux-hardware.org/?probe=5b72cdbdb8) | Dec 05, 2022 |
| ASUSTek       | X756UQK                     | [b473216b84](https://linux-hardware.org/?probe=b473216b84) | Dec 05, 2022 |
| HUAWEI        | BOD-WXX9                    | [3027fc2c2f](https://linux-hardware.org/?probe=3027fc2c2f) | Dec 05, 2022 |
| HUAWEI        | BOD-WXX9                    | [a07d55ca40](https://linux-hardware.org/?probe=a07d55ca40) | Dec 05, 2022 |
| MSI           | Creator 15M A9SD            | [f8e6206ba6](https://linux-hardware.org/?probe=f8e6206ba6) | Dec 05, 2022 |
| ASUSTek       | PU403UA                     | [20007b4296](https://linux-hardware.org/?probe=20007b4296) | Dec 05, 2022 |
| Acer          | Aspire A315-23G             | [41e6f6a3fa](https://linux-hardware.org/?probe=41e6f6a3fa) | Dec 05, 2022 |
| GMKtec        | NucBox5                     | [cdfbbcc5b2](https://linux-hardware.org/?probe=cdfbbcc5b2) | Dec 04, 2022 |
| ASUSTek       | S500CA                      | [267ffa24d1](https://linux-hardware.org/?probe=267ffa24d1) | Dec 04, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [f5be4eb37d](https://linux-hardware.org/?probe=f5be4eb37d) | Dec 04, 2022 |
| Toshiba       | dynabook R63/P              | [f51571b62c](https://linux-hardware.org/?probe=f51571b62c) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b475911aaf](https://linux-hardware.org/?probe=b475911aaf) | Dec 03, 2022 |
| Dell          | Inspiron 15-5578            | [61f5950e07](https://linux-hardware.org/?probe=61f5950e07) | Dec 03, 2022 |
| HP            | Laptop 15-da0xxx            | [9053b5cb8a](https://linux-hardware.org/?probe=9053b5cb8a) | Dec 03, 2022 |
| ASUSTek       | S500CA                      | [7145280e9e](https://linux-hardware.org/?probe=7145280e9e) | Dec 03, 2022 |
| Acer          | Aspire A315-21              | [91eb1913d7](https://linux-hardware.org/?probe=91eb1913d7) | Dec 03, 2022 |
| Unknown       | Unknown                     | [40917baf56](https://linux-hardware.org/?probe=40917baf56) | Dec 03, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [28ab0eb248](https://linux-hardware.org/?probe=28ab0eb248) | Dec 03, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [2085f260e1](https://linux-hardware.org/?probe=2085f260e1) | Dec 03, 2022 |
| Lenovo        | ThinkPad X280 20KE0015BR    | [4c65d4e572](https://linux-hardware.org/?probe=4c65d4e572) | Dec 03, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | [c99bd4ef76](https://linux-hardware.org/?probe=c99bd4ef76) | Dec 03, 2022 |
| Dell          | Inspiron 5566               | [54e06d37fc](https://linux-hardware.org/?probe=54e06d37fc) | Dec 02, 2022 |
| ASUSTek       | N750JV                      | [0fc50d63c4](https://linux-hardware.org/?probe=0fc50d63c4) | Dec 02, 2022 |
| Dell          | Latitude 5591               | [f5735acca7](https://linux-hardware.org/?probe=f5735acca7) | Dec 02, 2022 |
| HP            | Unknown                     | [741029c3af](https://linux-hardware.org/?probe=741029c3af) | Dec 02, 2022 |
| Aquarius      | NS585                       | [bbd3bd3ca6](https://linux-hardware.org/?probe=bbd3bd3ca6) | Dec 02, 2022 |
| Aquarius      | NS585                       | [50222418e5](https://linux-hardware.org/?probe=50222418e5) | Dec 02, 2022 |
| Aquarius      | NS585                       | [d55d40681f](https://linux-hardware.org/?probe=d55d40681f) | Dec 02, 2022 |
| Aquarius      | NS585                       | [9013a1cce6](https://linux-hardware.org/?probe=9013a1cce6) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [38ce706249](https://linux-hardware.org/?probe=38ce706249) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [546f2b82c9](https://linux-hardware.org/?probe=546f2b82c9) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [000d536e95](https://linux-hardware.org/?probe=000d536e95) | Dec 02, 2022 |
| HP            | 620                         | [6be09298b6](https://linux-hardware.org/?probe=6be09298b6) | Dec 01, 2022 |
| Lenovo        | ThinkPad T440p 20AN0079M... | [79261239c1](https://linux-hardware.org/?probe=79261239c1) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [674157de54](https://linux-hardware.org/?probe=674157de54) | Dec 01, 2022 |
| Lenovo        | V330-15IKB 81AX             | [becc2328fd](https://linux-hardware.org/?probe=becc2328fd) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | [73c388fb61](https://linux-hardware.org/?probe=73c388fb61) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | [6d44ef56c9](https://linux-hardware.org/?probe=6d44ef56c9) | Dec 01, 2022 |
| HP            | Pavilion dv5                | [0fc7017b0c](https://linux-hardware.org/?probe=0fc7017b0c) | Nov 30, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [183243daeb](https://linux-hardware.org/?probe=183243daeb) | Nov 30, 2022 |
| Notebook      | RIM2520                     | [5f66abbb8b](https://linux-hardware.org/?probe=5f66abbb8b) | Nov 30, 2022 |
| HP            | Elite x2 1011 G1 Tablet     | [1a00258de3](https://linux-hardware.org/?probe=1a00258de3) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | [e0187bc636](https://linux-hardware.org/?probe=e0187bc636) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | [99eb1cfce0](https://linux-hardware.org/?probe=99eb1cfce0) | Nov 29, 2022 |
| Dell          | Latitude 7490               | [8934413cf0](https://linux-hardware.org/?probe=8934413cf0) | Nov 29, 2022 |
| Lenovo        | V310-14IKB 80T2             | [b7c976ef9c](https://linux-hardware.org/?probe=b7c976ef9c) | Nov 29, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [9c45563fb6](https://linux-hardware.org/?probe=9c45563fb6) | Nov 29, 2022 |
| Dell          | XPS 15 9500                 | [9c87ab493e](https://linux-hardware.org/?probe=9c87ab493e) | Nov 29, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [1e52ea39e4](https://linux-hardware.org/?probe=1e52ea39e4) | Nov 28, 2022 |
| Lenovo        | ThinkPad X301 2776LEG       | [ebaea0c805](https://linux-hardware.org/?probe=ebaea0c805) | Nov 28, 2022 |
| Dell          | Precision M6400             | [05f69c6917](https://linux-hardware.org/?probe=05f69c6917) | Nov 28, 2022 |
| HP            | ProBook 450 G5              | [e94fd64204](https://linux-hardware.org/?probe=e94fd64204) | Nov 28, 2022 |
| ASUSTek       | GL752VW                     | [edc0678b85](https://linux-hardware.org/?probe=edc0678b85) | Nov 28, 2022 |
| Dell          | XPS 15 9500                 | [f149afb5d1](https://linux-hardware.org/?probe=f149afb5d1) | Nov 28, 2022 |
| ASUSTek       | N61Vg                       | [b5cc07b253](https://linux-hardware.org/?probe=b5cc07b253) | Nov 27, 2022 |
| Lenovo        | ThinkPad T450 20BUS03J00    | [8423f90db0](https://linux-hardware.org/?probe=8423f90db0) | Nov 27, 2022 |
| Lenovo        | ThinkPad T520 4243F53       | [8f9e96442a](https://linux-hardware.org/?probe=8f9e96442a) | Nov 27, 2022 |
| Tactus        | GeoBook 140                 | [e3f4d734da](https://linux-hardware.org/?probe=e3f4d734da) | Nov 27, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [7bd68a8bb1](https://linux-hardware.org/?probe=7bd68a8bb1) | Nov 27, 2022 |
| HP            | Compaq nx9110 (DU432EA#A... | [1b54092e14](https://linux-hardware.org/?probe=1b54092e14) | Nov 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [32bfa52fc1](https://linux-hardware.org/?probe=32bfa52fc1) | Nov 27, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [3d1b8f282a](https://linux-hardware.org/?probe=3d1b8f282a) | Nov 27, 2022 |
| HP            | Laptop 15s-fq5xxx           | [f1ef96a2e6](https://linux-hardware.org/?probe=f1ef96a2e6) | Nov 26, 2022 |
| MSI           | Creator 15M A9SD            | [8b47bbf475](https://linux-hardware.org/?probe=8b47bbf475) | Nov 26, 2022 |
| HP            | Laptop 15-da3xxx            | [335fce26dd](https://linux-hardware.org/?probe=335fce26dd) | Nov 26, 2022 |
| HP            | 255 G7 Notebook PC          | [8c389cf5d6](https://linux-hardware.org/?probe=8c389cf5d6) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | [2902b75068](https://linux-hardware.org/?probe=2902b75068) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | [973662f8d5](https://linux-hardware.org/?probe=973662f8d5) | Nov 26, 2022 |
| Lenovo        | ThinkPad T495 20NJS0L100    | [1e9e7f34df](https://linux-hardware.org/?probe=1e9e7f34df) | Nov 26, 2022 |
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
| ASUSTek       | Zenbook UX535QE_UM535QE     | [299634697d](https://linux-hardware.org/?probe=299634697d) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [ef378a135b](https://linux-hardware.org/?probe=ef378a135b) | Nov 24, 2022 |
| Aquarius      | NS585                       | [d54530cbcb](https://linux-hardware.org/?probe=d54530cbcb) | Nov 24, 2022 |
| Aquarius      | NS585                       | [64d9bcbcde](https://linux-hardware.org/?probe=64d9bcbcde) | Nov 24, 2022 |
| Apple         | MacBookAir6,2               | [1f43ba0436](https://linux-hardware.org/?probe=1f43ba0436) | Nov 24, 2022 |
| MSI           | Modern 14 A10M              | [0545f4e38b](https://linux-hardware.org/?probe=0545f4e38b) | Nov 23, 2022 |
| Lenovo        | ThinkPad T495 20NK000UUS    | [0e8c0e6f07](https://linux-hardware.org/?probe=0e8c0e6f07) | Nov 23, 2022 |
| Lenovo        | ThinkPad T490 20N3S8T211    | [97ea649145](https://linux-hardware.org/?probe=97ea649145) | Nov 23, 2022 |
| HP            | ProBook 450 G7              | [52d46ed47e](https://linux-hardware.org/?probe=52d46ed47e) | Nov 23, 2022 |
| Dell          | Latitude E6530              | [71623eedf3](https://linux-hardware.org/?probe=71623eedf3) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [df91e2d404](https://linux-hardware.org/?probe=df91e2d404) | Nov 23, 2022 |
| MPMAN         | CONVERTER 102               | [cab847edc0](https://linux-hardware.org/?probe=cab847edc0) | Nov 23, 2022 |
| HP            | Compaq 6720s                | [63a0e0161c](https://linux-hardware.org/?probe=63a0e0161c) | Nov 22, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [363e0b0149](https://linux-hardware.org/?probe=363e0b0149) | Nov 22, 2022 |
| Unknown       | Unknown                     | [1de34b67e2](https://linux-hardware.org/?probe=1de34b67e2) | Nov 22, 2022 |
| Dell          | Latitude 3420               | [30434de3e9](https://linux-hardware.org/?probe=30434de3e9) | Nov 22, 2022 |
| Unknown       | Wiren Board rev. 7.3.1 (... | [1f9ccab914](https://linux-hardware.org/?probe=1f9ccab914) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0565ef1a0d](https://linux-hardware.org/?probe=0565ef1a0d) | Nov 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [71c464a407](https://linux-hardware.org/?probe=71c464a407) | Nov 22, 2022 |
| HP            | Pavilion Sleekbook 15       | [add4f71bc0](https://linux-hardware.org/?probe=add4f71bc0) | Nov 22, 2022 |
| HP            | ENVY 6                      | [feb348843e](https://linux-hardware.org/?probe=feb348843e) | Nov 22, 2022 |
| Lenovo        | Y520-15IKBA 80WY            | [c1cccb2b2a](https://linux-hardware.org/?probe=c1cccb2b2a) | Nov 22, 2022 |
| HP            | 255 G6 Notebook PC          | [149cee1720](https://linux-hardware.org/?probe=149cee1720) | Nov 22, 2022 |
| ASUSTek       | K53SD                       | [c127a0db71](https://linux-hardware.org/?probe=c127a0db71) | Nov 21, 2022 |
| Lenovo        | ThinkPad E14 20RAS04700     | [63d93d05db](https://linux-hardware.org/?probe=63d93d05db) | Nov 21, 2022 |
| MSI           | Creator 15M A9SD            | [e6d5440b09](https://linux-hardware.org/?probe=e6d5440b09) | Nov 21, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [b58bad1779](https://linux-hardware.org/?probe=b58bad1779) | Nov 21, 2022 |
| Dell          | Latitude 5310               | [9c19a3de68](https://linux-hardware.org/?probe=9c19a3de68) | Nov 21, 2022 |
| Micro Elec... | MG-VCTR002-2060             | [3ba115909e](https://linux-hardware.org/?probe=3ba115909e) | Nov 21, 2022 |
| HP            | Laptop 15-db0xxx            | [f634446cde](https://linux-hardware.org/?probe=f634446cde) | Nov 21, 2022 |
| Acer          | Popcorn                     | [6f446a097a](https://linux-hardware.org/?probe=6f446a097a) | Nov 20, 2022 |
| ASUSTek       | X550LB                      | [466592b744](https://linux-hardware.org/?probe=466592b744) | Nov 20, 2022 |
| ASUSTek       | X550LB                      | [3ca5ee2f7a](https://linux-hardware.org/?probe=3ca5ee2f7a) | Nov 20, 2022 |
| Chuwi         | LarkBook                    | [bef3087526](https://linux-hardware.org/?probe=bef3087526) | Nov 20, 2022 |
| MPMAN         | CONVERTER 102               | [845925720b](https://linux-hardware.org/?probe=845925720b) | Nov 20, 2022 |
| HP            | Laptop 15s-du3xxx           | [a90cea62ff](https://linux-hardware.org/?probe=a90cea62ff) | Nov 19, 2022 |
| Dell          | XPS 13 9380                 | [d42bddbd11](https://linux-hardware.org/?probe=d42bddbd11) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1af7bd26fd](https://linux-hardware.org/?probe=1af7bd26fd) | Nov 19, 2022 |
| Dell          | Inspiron 15-3567            | [5d6f9e57c5](https://linux-hardware.org/?probe=5d6f9e57c5) | Nov 19, 2022 |
| Tactus        | GeoBook 140                 | [127ec68044](https://linux-hardware.org/?probe=127ec68044) | Nov 19, 2022 |
| Aquarius      | NS585                       | [a0bc8d3f44](https://linux-hardware.org/?probe=a0bc8d3f44) | Nov 19, 2022 |
| Acer          | Aspire ES1-533              | [8c080caac2](https://linux-hardware.org/?probe=8c080caac2) | Nov 19, 2022 |
| Fujitsu       | FMVNQL7PM                   | [28ee68da79](https://linux-hardware.org/?probe=28ee68da79) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ad7abfb8cb](https://linux-hardware.org/?probe=ad7abfb8cb) | Nov 19, 2022 |
| Dell          | Latitude 7410               | [ce222880fe](https://linux-hardware.org/?probe=ce222880fe) | Nov 18, 2022 |
| Dynabook      | TECRA A50-J                 | [c0ae8746e0](https://linux-hardware.org/?probe=c0ae8746e0) | Nov 18, 2022 |
| HP            | 650                         | [43998a620b](https://linux-hardware.org/?probe=43998a620b) | Nov 18, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [0278a1f18d](https://linux-hardware.org/?probe=0278a1f18d) | Nov 18, 2022 |
| Apple         | MacBookAir7,2               | [f0fa194e20](https://linux-hardware.org/?probe=f0fa194e20) | Nov 18, 2022 |
| Google        | Terra                       | [9fcc3fb18a](https://linux-hardware.org/?probe=9fcc3fb18a) | Nov 18, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [3b33d1989a](https://linux-hardware.org/?probe=3b33d1989a) | Nov 18, 2022 |
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
| Dell          | Latitude 3320               | [fbaf8e5ab9](https://linux-hardware.org/?probe=fbaf8e5ab9) | Nov 16, 2022 |
| Dell          | Latitude 3320               | [377fbd3b41](https://linux-hardware.org/?probe=377fbd3b41) | Nov 16, 2022 |
| Dell          | Inspiron 13 5310            | [3c9865d86e](https://linux-hardware.org/?probe=3c9865d86e) | Nov 16, 2022 |
| HP            | Laptop 15-db0xxx            | [f6202bb6fa](https://linux-hardware.org/?probe=f6202bb6fa) | Nov 16, 2022 |
| MSI           | Prestige 14Evo A11M         | [78601d078c](https://linux-hardware.org/?probe=78601d078c) | Nov 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [8fe0bcfe69](https://linux-hardware.org/?probe=8fe0bcfe69) | Nov 16, 2022 |
| Lenovo        | IdeaPad Z470                | [bc0980a6df](https://linux-hardware.org/?probe=bc0980a6df) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [5ea39eac4c](https://linux-hardware.org/?probe=5ea39eac4c) | Nov 16, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [be72c5d9db](https://linux-hardware.org/?probe=be72c5d9db) | Nov 16, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [c38c6ddff6](https://linux-hardware.org/?probe=c38c6ddff6) | Nov 16, 2022 |
| Lenovo        | G470 20078                  | [55f47f2c19](https://linux-hardware.org/?probe=55f47f2c19) | Nov 16, 2022 |
| Unknown       | Unknown                     | [a86465b0f3](https://linux-hardware.org/?probe=a86465b0f3) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [b5eb364ac6](https://linux-hardware.org/?probe=b5eb364ac6) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [f29e7d7659](https://linux-hardware.org/?probe=f29e7d7659) | Nov 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [2cc4a2cf6d](https://linux-hardware.org/?probe=2cc4a2cf6d) | Nov 16, 2022 |
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
| Lenovo        | V14-ADA 82C6                | [7971c5cda7](https://linux-hardware.org/?probe=7971c5cda7) | Nov 14, 2022 |
| Toshiba       | Satellite P50-B-10Q         | [f28064cdad](https://linux-hardware.org/?probe=f28064cdad) | Nov 14, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [233791ab06](https://linux-hardware.org/?probe=233791ab06) | Nov 14, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [c6e254c4ed](https://linux-hardware.org/?probe=c6e254c4ed) | Nov 14, 2022 |
| HP            | 530 Notebook PC(KD092AA#... | [b6c682238c](https://linux-hardware.org/?probe=b6c682238c) | Nov 13, 2022 |
| Chuwi         | LarkBook                    | [8c33c61e14](https://linux-hardware.org/?probe=8c33c61e14) | Nov 13, 2022 |
| HP            | Laptop 15s-eq2xxx           | [36df61fb32](https://linux-hardware.org/?probe=36df61fb32) | Nov 13, 2022 |
| Unknown       | Unknown                     | [344e5842d1](https://linux-hardware.org/?probe=344e5842d1) | Nov 13, 2022 |
| Dell          | Inspiron 3521               | [c644f80930](https://linux-hardware.org/?probe=c644f80930) | Nov 13, 2022 |
| MSI           | GF63 8RD                    | [0ca4cc20c5](https://linux-hardware.org/?probe=0ca4cc20c5) | Nov 13, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [ff0881b6e4](https://linux-hardware.org/?probe=ff0881b6e4) | Nov 13, 2022 |
| HP            | 250 G8 Notebook PC          | [7e9c7562d6](https://linux-hardware.org/?probe=7e9c7562d6) | Nov 13, 2022 |
| HP            | EliteBook 8460p             | [8cb389e68e](https://linux-hardware.org/?probe=8cb389e68e) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1067cba3cc](https://linux-hardware.org/?probe=1067cba3cc) | Nov 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [6677ca6be8](https://linux-hardware.org/?probe=6677ca6be8) | Nov 12, 2022 |
| GPU Compan... | GWTC116-2                   | [978facebde](https://linux-hardware.org/?probe=978facebde) | Nov 12, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [904b7c0e89](https://linux-hardware.org/?probe=904b7c0e89) | Nov 12, 2022 |
| HP            | Notebook                    | [2419e7d149](https://linux-hardware.org/?probe=2419e7d149) | Nov 12, 2022 |
| HP            | Notebook                    | [97c6c3c412](https://linux-hardware.org/?probe=97c6c3c412) | Nov 12, 2022 |
| GPU Compan... | GWTC116-2                   | [9e0c2df66d](https://linux-hardware.org/?probe=9e0c2df66d) | Nov 12, 2022 |
| IBM           | ThinkPad X31 2672JBU        | [9f627ba3f8](https://linux-hardware.org/?probe=9f627ba3f8) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [59aa7d31d8](https://linux-hardware.org/?probe=59aa7d31d8) | Nov 11, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [22ab694d81](https://linux-hardware.org/?probe=22ab694d81) | Nov 11, 2022 |
| Lenovo        | ThinkPad W700 275236U       | [c79bbe36c5](https://linux-hardware.org/?probe=c79bbe36c5) | Nov 11, 2022 |
| NCA Group     | iRU_Notebook                | [6d22b3942e](https://linux-hardware.org/?probe=6d22b3942e) | Nov 11, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [1681f97433](https://linux-hardware.org/?probe=1681f97433) | Nov 11, 2022 |
| HP            | Spectre x2 Detachable       | [0c480bd74d](https://linux-hardware.org/?probe=0c480bd74d) | Nov 11, 2022 |
| ASUSTek       | K50IE                       | [4bd91fccfa](https://linux-hardware.org/?probe=4bd91fccfa) | Nov 11, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [139c944b07](https://linux-hardware.org/?probe=139c944b07) | Nov 11, 2022 |
| Positivo B... | VJFE53F11X-XXXXXX           | [7e81c7cf85](https://linux-hardware.org/?probe=7e81c7cf85) | Nov 10, 2022 |
| HP            | ENVY 17 Leap Motion SE N... | [ae40e6e5b3](https://linux-hardware.org/?probe=ae40e6e5b3) | Nov 10, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [f8cd836199](https://linux-hardware.org/?probe=f8cd836199) | Nov 10, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [8bb3389cc1](https://linux-hardware.org/?probe=8bb3389cc1) | Nov 10, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [24c5edc9f9](https://linux-hardware.org/?probe=24c5edc9f9) | Nov 10, 2022 |
| Lenovo        | G50-30 80G0                 | [1e0c308a85](https://linux-hardware.org/?probe=1e0c308a85) | Nov 10, 2022 |
| ASUSTek       | X550VXK                     | [f752e7959c](https://linux-hardware.org/?probe=f752e7959c) | Nov 10, 2022 |
| ASUSTek       | K50IE                       | [5176f404f1](https://linux-hardware.org/?probe=5176f404f1) | Nov 10, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [9a69ea4724](https://linux-hardware.org/?probe=9a69ea4724) | Nov 10, 2022 |
| Dell          | Latitude E6530              | [f71e1a930c](https://linux-hardware.org/?probe=f71e1a930c) | Nov 10, 2022 |
| HP            | Pavilion g7                 | [ae04263783](https://linux-hardware.org/?probe=ae04263783) | Nov 09, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [9d27997bce](https://linux-hardware.org/?probe=9d27997bce) | Nov 09, 2022 |
| ASUSTek       | UX31A                       | [e9bc780ce8](https://linux-hardware.org/?probe=e9bc780ce8) | Nov 09, 2022 |
| Gigabyte      | Sabre 15                    | [1edede0895](https://linux-hardware.org/?probe=1edede0895) | Nov 09, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [098d4ab9ec](https://linux-hardware.org/?probe=098d4ab9ec) | Nov 09, 2022 |
| Lenovo        | ThinkPad T420 4180PEM       | [ad4d7f338d](https://linux-hardware.org/?probe=ad4d7f338d) | Nov 09, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [52080bf6ef](https://linux-hardware.org/?probe=52080bf6ef) | Nov 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [6b1f5f2c2a](https://linux-hardware.org/?probe=6b1f5f2c2a) | Nov 08, 2022 |
| HP            | Pavilion g7                 | [47c2e96181](https://linux-hardware.org/?probe=47c2e96181) | Nov 08, 2022 |
| Aquarius      | NS585                       | [9b20fcc4b8](https://linux-hardware.org/?probe=9b20fcc4b8) | Nov 08, 2022 |
| Razer         | Blade 15 Advanced Model ... | [0596fa3f71](https://linux-hardware.org/?probe=0596fa3f71) | Nov 08, 2022 |
| Dell          | Latitude E7470              | [3938dbeadd](https://linux-hardware.org/?probe=3938dbeadd) | Nov 08, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [da41b87b7c](https://linux-hardware.org/?probe=da41b87b7c) | Nov 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [f3c625be2d](https://linux-hardware.org/?probe=f3c625be2d) | Nov 07, 2022 |
| Unknown       | Unknown                     | [6af513692f](https://linux-hardware.org/?probe=6af513692f) | Nov 07, 2022 |
| Unknown       | Unknown                     | [b4859caaba](https://linux-hardware.org/?probe=b4859caaba) | Nov 07, 2022 |
| Lenovo        | G50-70 20351                | [0d4536a010](https://linux-hardware.org/?probe=0d4536a010) | Nov 07, 2022 |
| Lenovo        | ThinkPad W700 275236U       | [d3580b26c6](https://linux-hardware.org/?probe=d3580b26c6) | Nov 06, 2022 |
| HP            | Laptop 15-db0xxx            | [32b59c7a7d](https://linux-hardware.org/?probe=32b59c7a7d) | Nov 06, 2022 |
| HP            | Laptop 15-db0xxx            | [f0c8aff40f](https://linux-hardware.org/?probe=f0c8aff40f) | Nov 06, 2022 |
| Dell          | Latitude E6520              | [9593951427](https://linux-hardware.org/?probe=9593951427) | Nov 06, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [e872e8551e](https://linux-hardware.org/?probe=e872e8551e) | Nov 06, 2022 |
| Dell          | Latitude E6520              | [53eedbde1f](https://linux-hardware.org/?probe=53eedbde1f) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [55d115647e](https://linux-hardware.org/?probe=55d115647e) | Nov 06, 2022 |
| ASUSTek       | GL752VW                     | [cc373f85e7](https://linux-hardware.org/?probe=cc373f85e7) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [47dda70950](https://linux-hardware.org/?probe=47dda70950) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [5a2028bd2d](https://linux-hardware.org/?probe=5a2028bd2d) | Nov 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [3ec96d66bb](https://linux-hardware.org/?probe=3ec96d66bb) | Nov 05, 2022 |
| Acer          | Aspire 5741G                | [10c1cb72e2](https://linux-hardware.org/?probe=10c1cb72e2) | Nov 05, 2022 |
| Acer          | Aspire V3-572G              | [77f939bab4](https://linux-hardware.org/?probe=77f939bab4) | Nov 05, 2022 |
| ASUSTek       | X756UWK                     | [2d165dd7b0](https://linux-hardware.org/?probe=2d165dd7b0) | Nov 05, 2022 |
| Lenovo        | ThinkPad L380 20M50013MH    | [80ac51627a](https://linux-hardware.org/?probe=80ac51627a) | Nov 05, 2022 |
| ASUSTek       | X756UWK                     | [b89c7882f3](https://linux-hardware.org/?probe=b89c7882f3) | Nov 05, 2022 |
| Dell          | Inspiron 7570               | [158f7b0bcd](https://linux-hardware.org/?probe=158f7b0bcd) | Nov 05, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [605e06c6ad](https://linux-hardware.org/?probe=605e06c6ad) | Nov 04, 2022 |
| ASUSTek       | K53SD                       | [809577d2bb](https://linux-hardware.org/?probe=809577d2bb) | Nov 04, 2022 |
| Google        | Terra                       | [90518f31df](https://linux-hardware.org/?probe=90518f31df) | Nov 04, 2022 |
| Google        | Terra                       | [46ffa8092b](https://linux-hardware.org/?probe=46ffa8092b) | Nov 04, 2022 |
| Google        | Terra                       | [fc3f4b0ba5](https://linux-hardware.org/?probe=fc3f4b0ba5) | Nov 04, 2022 |
| Google        | Terra                       | [41017e02e4](https://linux-hardware.org/?probe=41017e02e4) | Nov 04, 2022 |
| Google        | Terra                       | [7429a311e4](https://linux-hardware.org/?probe=7429a311e4) | Nov 04, 2022 |
| SK hynix      | HyBook                      | [e758cde5ed](https://linux-hardware.org/?probe=e758cde5ed) | Nov 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [f0be03da28](https://linux-hardware.org/?probe=f0be03da28) | Nov 04, 2022 |
| Juana Mans... | SF20GM7                     | [8e8c4f52f4](https://linux-hardware.org/?probe=8e8c4f52f4) | Nov 04, 2022 |
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
| ASUSTek       | VivoBook_ASUSLaptop M350... | [455bdc6c45](https://linux-hardware.org/?probe=455bdc6c45) | Nov 03, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [e507b9a974](https://linux-hardware.org/?probe=e507b9a974) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [7a5f1eaf6c](https://linux-hardware.org/?probe=7a5f1eaf6c) | Nov 03, 2022 |
| SAGER         | D900F                       | [7e0d0de36a](https://linux-hardware.org/?probe=7e0d0de36a) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [cecc0cca9d](https://linux-hardware.org/?probe=cecc0cca9d) | Nov 03, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [464cc2acc3](https://linux-hardware.org/?probe=464cc2acc3) | Nov 03, 2022 |
| Lenovo        | ThinkPad T430 23501B6       | [f059837f31](https://linux-hardware.org/?probe=f059837f31) | Nov 03, 2022 |
| Dell          | Latitude 5420               | [717e0e6d40](https://linux-hardware.org/?probe=717e0e6d40) | Nov 03, 2022 |
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
| MSI           | Pulse GL76 12UEK            | [76a2d8c304](https://linux-hardware.org/?probe=76a2d8c304) | Oct 31, 2022 |
| ASUSTek       | ZenBook UX431FAC_UX431FA    | [95554a578b](https://linux-hardware.org/?probe=95554a578b) | Oct 31, 2022 |
| Aquarius      | NS585                       | [e4b4e0456d](https://linux-hardware.org/?probe=e4b4e0456d) | Oct 31, 2022 |
| Apple         | MacBookPro5,5               | [00e1f1f754](https://linux-hardware.org/?probe=00e1f1f754) | Oct 31, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [a872c9888a](https://linux-hardware.org/?probe=a872c9888a) | Oct 30, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [45f670d99f](https://linux-hardware.org/?probe=45f670d99f) | Oct 30, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [209fa66bb9](https://linux-hardware.org/?probe=209fa66bb9) | Oct 30, 2022 |
| Acer          | Aspire A515-51G             | [12380f78de](https://linux-hardware.org/?probe=12380f78de) | Oct 30, 2022 |
| HP            | x2 210                      | [8ed0a97ee9](https://linux-hardware.org/?probe=8ed0a97ee9) | Oct 30, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [e8a1f8f6bf](https://linux-hardware.org/?probe=e8a1f8f6bf) | Oct 30, 2022 |
| Dell          | XPS L322X                   | [cacebfe41e](https://linux-hardware.org/?probe=cacebfe41e) | Oct 30, 2022 |
| ASUSTek       | N751JK                      | [eea92055f3](https://linux-hardware.org/?probe=eea92055f3) | Oct 30, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [89595b2fa9](https://linux-hardware.org/?probe=89595b2fa9) | Oct 30, 2022 |
| Chuwi         | LarkBook                    | [3ff2ff69ce](https://linux-hardware.org/?probe=3ff2ff69ce) | Oct 30, 2022 |
| Dell          | Latitude 5501               | [67f979a26d](https://linux-hardware.org/?probe=67f979a26d) | Oct 29, 2022 |
| Notebook      | W230SD                      | [76ae019222](https://linux-hardware.org/?probe=76ae019222) | Oct 29, 2022 |
| Dell          | Precision 7520              | [f54f6d6354](https://linux-hardware.org/?probe=f54f6d6354) | Oct 29, 2022 |
| Dell          | Latitude 5590               | [c7fa986fbd](https://linux-hardware.org/?probe=c7fa986fbd) | Oct 29, 2022 |
| ASUSTek       | X75VC                       | [9c1ab509ec](https://linux-hardware.org/?probe=9c1ab509ec) | Oct 29, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [8cc0e0d828](https://linux-hardware.org/?probe=8cc0e0d828) | Oct 29, 2022 |
| Dell          | Latitude E4310              | [fe6c65dd77](https://linux-hardware.org/?probe=fe6c65dd77) | Oct 29, 2022 |
| Insyde        | Braswell                    | [d98b2d9661](https://linux-hardware.org/?probe=d98b2d9661) | Oct 29, 2022 |
| Samsung       | 300V3A/300V4A/300V5A        | [4acb2d0863](https://linux-hardware.org/?probe=4acb2d0863) | Oct 29, 2022 |
| Dell          | Latitude E4310              | [7a610ca46d](https://linux-hardware.org/?probe=7a610ca46d) | Oct 29, 2022 |
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
| ASUSTek       | N501VW                      | [07f7d43f09](https://linux-hardware.org/?probe=07f7d43f09) | Oct 27, 2022 |
| HP            | ZBook 15 G3                 | [2b886c255e](https://linux-hardware.org/?probe=2b886c255e) | Oct 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [24da197a3a](https://linux-hardware.org/?probe=24da197a3a) | Oct 27, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [3ab1fbc8e8](https://linux-hardware.org/?probe=3ab1fbc8e8) | Oct 27, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [faafe16cfb](https://linux-hardware.org/?probe=faafe16cfb) | Oct 27, 2022 |
| Acer          | Aspire A515-45              | [3a09f9ee6b](https://linux-hardware.org/?probe=3a09f9ee6b) | Oct 27, 2022 |
| THTF          | CR F860-T1                  | [0e20f4f61a](https://linux-hardware.org/?probe=0e20f4f61a) | Oct 27, 2022 |
| Acer          | Aspire ES1-131              | [f0edf4897a](https://linux-hardware.org/?probe=f0edf4897a) | Oct 26, 2022 |
| ASUSTek       | X541UAK                     | [87ee863ba2](https://linux-hardware.org/?probe=87ee863ba2) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [bfd570bbef](https://linux-hardware.org/?probe=bfd570bbef) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [58820ca517](https://linux-hardware.org/?probe=58820ca517) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [6b9a3ab27e](https://linux-hardware.org/?probe=6b9a3ab27e) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [a5bd8bebc7](https://linux-hardware.org/?probe=a5bd8bebc7) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [bce3a8b1b3](https://linux-hardware.org/?probe=bce3a8b1b3) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [65a1d5242f](https://linux-hardware.org/?probe=65a1d5242f) | Oct 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a09e3f3669](https://linux-hardware.org/?probe=a09e3f3669) | Oct 26, 2022 |
| ASUSTek       | 1005HA                      | [118fed891f](https://linux-hardware.org/?probe=118fed891f) | Oct 26, 2022 |
| HP            | Pavilion g6                 | [353259fad4](https://linux-hardware.org/?probe=353259fad4) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [93b8dd8c3e](https://linux-hardware.org/?probe=93b8dd8c3e) | Oct 25, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [5e08852d18](https://linux-hardware.org/?probe=5e08852d18) | Oct 25, 2022 |
| Lenovo        | Z50-70 20354                | [08b673e57b](https://linux-hardware.org/?probe=08b673e57b) | Oct 25, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [438afb4185](https://linux-hardware.org/?probe=438afb4185) | Oct 25, 2022 |
| Lenovo        | Yoga 900S-12ISK 80ML        | [0c13fbf129](https://linux-hardware.org/?probe=0c13fbf129) | Oct 25, 2022 |
| Toshiba       | dynabook MX/33KBL           | [7ee9057da2](https://linux-hardware.org/?probe=7ee9057da2) | Oct 25, 2022 |
| Dell          | Vostro 5490                 | [6b4c7d3c8b](https://linux-hardware.org/?probe=6b4c7d3c8b) | Oct 24, 2022 |
| Dell          | Latitude E6430              | [3fbd9c277d](https://linux-hardware.org/?probe=3fbd9c277d) | Oct 24, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [eae727e6a0](https://linux-hardware.org/?probe=eae727e6a0) | Oct 24, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [52701ec9f4](https://linux-hardware.org/?probe=52701ec9f4) | Oct 24, 2022 |
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
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [45d7e6a1aa](https://linux-hardware.org/?probe=45d7e6a1aa) | Oct 21, 2022 |
| Apple         | MacBook5,2                  | [165ce75570](https://linux-hardware.org/?probe=165ce75570) | Oct 21, 2022 |
| MSI           | Prestige 14Evo A11M         | [c63a7ccdeb](https://linux-hardware.org/?probe=c63a7ccdeb) | Oct 21, 2022 |
| Acer          | Swift SF314-42              | [2449f6a1b7](https://linux-hardware.org/?probe=2449f6a1b7) | Oct 21, 2022 |
| Aquarius      | NS585                       | [c953c5090c](https://linux-hardware.org/?probe=c953c5090c) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1e4d67ad76](https://linux-hardware.org/?probe=1e4d67ad76) | Oct 21, 2022 |
| Lenovo        | V310-14IKB 80T2             | [8a0f6b66e6](https://linux-hardware.org/?probe=8a0f6b66e6) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1dc7719a4d](https://linux-hardware.org/?probe=1dc7719a4d) | Oct 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [7acb5493d7](https://linux-hardware.org/?probe=7acb5493d7) | Oct 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [b13dc58884](https://linux-hardware.org/?probe=b13dc58884) | Oct 20, 2022 |
| ASUSTek       | G75VW                       | [194959e65e](https://linux-hardware.org/?probe=194959e65e) | Oct 20, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [914bab2302](https://linux-hardware.org/?probe=914bab2302) | Oct 20, 2022 |
| HP            | EliteBook 745 G3            | [3bfbc8dcac](https://linux-hardware.org/?probe=3bfbc8dcac) | Oct 20, 2022 |
| HP            | Laptop 15-ef2xxx            | [823d998220](https://linux-hardware.org/?probe=823d998220) | Oct 20, 2022 |
| HP            | EliteBook 840 Aero G8 No... | [80738ede80](https://linux-hardware.org/?probe=80738ede80) | Oct 20, 2022 |
| Apple         | MacBook5,2                  | [1e76467975](https://linux-hardware.org/?probe=1e76467975) | Oct 20, 2022 |
| Aquarius      | NS585                       | [a134ed693c](https://linux-hardware.org/?probe=a134ed693c) | Oct 20, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [162e7a20b2](https://linux-hardware.org/?probe=162e7a20b2) | Oct 20, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [35d4f4cf0e](https://linux-hardware.org/?probe=35d4f4cf0e) | Oct 20, 2022 |
| HP            | 245 G7                      | [9ec088c343](https://linux-hardware.org/?probe=9ec088c343) | Oct 19, 2022 |
| ASUSTek       | X541NA                      | [5b61fd3a38](https://linux-hardware.org/?probe=5b61fd3a38) | Oct 19, 2022 |

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
| Debian 11                       | 2897      | 63.81%  |
| Debian 10                       | 848       | 18.68%  |
| Debian Testing                  | 357       | 7.86%   |
| Debian 9                        | 146       | 3.22%   |
| Debian Unstable                 | 128       | 2.82%   |
| Debian                          | 121       | 2.67%   |
| Debian 11-updates               | 26        | 0.57%   |
| Debian 8                        | 10        | 0.22%   |
| Debian Sid                      | 3         | 0.07%   |
| Debian Testing/unstable         | 2         | 0.04%   |
| Debian Testing-proposed-updates | 1         | 0.02%   |
| Debian 99                       | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Debian | 4414      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.10.0-8-amd64         | 583       | 11.66%  |
| 5.10.0-10-amd64        | 491       | 9.82%   |
| 5.10.0-18-amd64        | 173       | 3.46%   |
| 5.10.0-9-amd64         | 172       | 3.44%   |
| 5.10.0-7-amd64         | 171       | 3.42%   |
| 5.10.0-16-amd64        | 166       | 3.32%   |
| 5.10.0-19-amd64        | 161       | 3.22%   |
| 5.10.0-20-amd64        | 154       | 3.08%   |
| 5.10.0-13-amd64        | 149       | 2.98%   |
| 5.10.0-11-amd64        | 103       | 2.06%   |
| 5.10.0-21-amd64        | 94        | 1.88%   |
| 4.19.0-9-amd64         | 85        | 1.7%    |
| 4.19.0-6-amd64         | 82        | 1.64%   |
| 5.10.0-14-amd64        | 80        | 1.6%    |
| 5.10.0-17-amd64        | 73        | 1.46%   |
| 4.19.0-13-amd64        | 69        | 1.38%   |
| 4.19.0-8-amd64         | 68        | 1.36%   |
| 4.19.0-16-amd64        | 52        | 1.04%   |
| 4.19.0-10-amd64        | 52        | 1.04%   |
| 5.15.0-2-amd64         | 51        | 1.02%   |
| 5.10.0-15-amd64        | 49        | 0.98%   |
| 4.19.0-12-amd64        | 47        | 0.94%   |
| 5.10.0-2-amd64         | 46        | 0.92%   |
| 4.19.0-14-amd64        | 42        | 0.84%   |
| 5.10.0-6-amd64         | 41        | 0.82%   |
| 5.10.0-12-amd64        | 40        | 0.8%    |
| 4.19.0-17-amd64        | 40        | 0.8%    |
| 4.9.0-8-amd64          | 39        | 0.78%   |
| 5.18.0-2-amd64         | 31        | 0.62%   |
| 5.10.0-3-amd64         | 31        | 0.62%   |
| 5.19.0-1-amd64         | 27        | 0.54%   |
| 6.0.0-6-amd64          | 26        | 0.52%   |
| 5.10.0-13-686-pae      | 26        | 0.52%   |
| 5.4.0-4-amd64          | 25        | 0.5%    |
| 5.17.0-1-amd64         | 24        | 0.48%   |
| 5.18.0-4-amd64         | 23        | 0.46%   |
| 6.0.0-2-amd64          | 22        | 0.44%   |
| 5.19.0-2-amd64         | 22        | 0.44%   |
| 5.18.0-0.deb11.4-amd64 | 22        | 0.44%   |
| 5.16.0-6-amd64         | 22        | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 2761      | 59.16%  |
| 4.19.0  | 651       | 13.95%  |
| 6.0.0   | 120       | 2.57%   |
| 4.9.0   | 120       | 2.57%   |
| 5.18.0  | 106       | 2.27%   |
| 5.15.0  | 91        | 1.95%   |
| 5.9.0   | 74        | 1.59%   |
| 5.16.0  | 67        | 1.44%   |
| 5.19.0  | 65        | 1.39%   |
| 5.4.0   | 64        | 1.37%   |
| 5.7.0   | 59        | 1.26%   |
| 5.8.0   | 56        | 1.2%    |
| 5.14.0  | 53        | 1.14%   |
| 5.6.0   | 45        | 0.96%   |
| 6.1.0   | 39        | 0.84%   |
| 5.17.0  | 39        | 0.84%   |
| 5.3.0   | 19        | 0.41%   |
| 5.5.0   | 16        | 0.34%   |
| 5.2.0   | 12        | 0.26%   |
| 4.18.0  | 12        | 0.26%   |
| 3.16.0  | 8         | 0.17%   |
| 5.12.0  | 6         | 0.13%   |
| 5.17.5  | 3         | 0.06%   |
| 5.13.19 | 3         | 0.06%   |
| 5.13.0  | 3         | 0.06%   |
| 5.11.0  | 3         | 0.06%   |
| 5.10.60 | 3         | 0.06%   |
| 5.10.10 | 3         | 0.06%   |
| 5.0.0   | 3         | 0.06%   |
| 6.0.2   | 2         | 0.04%   |
| 5.8.2   | 2         | 0.04%   |
| 5.8.16  | 2         | 0.04%   |
| 5.4.21  | 2         | 0.04%   |
| 5.3.5   | 2         | 0.04%   |
| 5.18.15 | 2         | 0.04%   |
| 5.17.11 | 2         | 0.04%   |
| 5.16.12 | 2         | 0.04%   |
| 5.15.5  | 2         | 0.04%   |
| 5.15.35 | 2         | 0.04%   |
| 5.15.32 | 2         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 2784      | 59.78%  |
| 4.19    | 655       | 14.06%  |
| 6.0     | 126       | 2.71%   |
| 4.9     | 123       | 2.64%   |
| 5.18    | 111       | 2.38%   |
| 5.15    | 108       | 2.32%   |
| 5.9     | 80        | 1.72%   |
| 5.4     | 76        | 1.63%   |
| 5.16    | 71        | 1.52%   |
| 5.19    | 70        | 1.5%    |
| 5.7     | 62        | 1.33%   |
| 5.8     | 61        | 1.31%   |
| 5.14    | 58        | 1.25%   |
| 5.6     | 49        | 1.05%   |
| 5.17    | 48        | 1.03%   |
| 6.1     | 41        | 0.88%   |
| 5.3     | 23        | 0.49%   |
| 5.5     | 19        | 0.41%   |
| 5.2     | 17        | 0.37%   |
| 5.13    | 12        | 0.26%   |
| 4.18    | 12        | 0.26%   |
| 5.12    | 9         | 0.19%   |
| 5.11    | 9         | 0.19%   |
| 3.16    | 8         | 0.17%   |
| 3.10    | 4         | 0.09%   |
| 5.1     | 3         | 0.06%   |
| 5.0     | 3         | 0.06%   |
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
| 3.8     | 1         | 0.02%   |
| 3.0     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 4205      | 95.24%  |
| i686    | 197       | 4.46%   |
| armv7l  | 9         | 0.2%    |
| aarch64 | 3         | 0.07%   |
| i586    | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 1200      | 26.54%  |
| Unknown           | 1155      | 25.54%  |
| XFCE              | 587       | 12.98%  |
| KDE5              | 553       | 12.23%  |
| MATE              | 188       | 4.16%   |
| X-Cinnamon        | 154       | 3.41%   |
| LXDE              | 140       | 3.1%    |
| Cinnamon          | 133       | 2.94%   |
| KDE               | 111       | 2.45%   |
| i3                | 87        | 1.92%   |
| LXQt              | 64        | 1.42%   |
| GNOME Flashback   | 32        | 0.71%   |
| lightdm-xsession  | 25        | 0.55%   |
| Openbox           | 13        | 0.29%   |
| Budgie            | 13        | 0.29%   |
| trinity           | 11        | 0.24%   |
| GNOME Classic     | 10        | 0.22%   |
| sway              | 4         | 0.09%   |
| ICEWM             | 4         | 0.09%   |
| Fluxbox           | 4         | 0.09%   |
| bspwm             | 4         | 0.09%   |
| awesome           | 4         | 0.09%   |
| Enlightenment     | 3         | 0.07%   |
| DWM               | 3         | 0.07%   |
| Cutefish          | 3         | 0.07%   |
| xmonad            | 2         | 0.04%   |
| x-session-manager | 2         | 0.04%   |
| Unity             | 2         | 0.04%   |
| KDE4              | 2         | 0.04%   |
| default           | 2         | 0.04%   |
| wmaker-common     | 1         | 0.02%   |
| matchbox          | 1         | 0.02%   |
| jwm               | 1         | 0.02%   |
| i3-gaps           | 1         | 0.02%   |
| GNUstep           | 1         | 0.02%   |
| Deepin            | 1         | 0.02%   |
| BunsenLabs        | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 2531      | 56.21%  |
| Unknown     | 927       | 20.59%  |
| Wayland     | 866       | 19.23%  |
| Tty         | 176       | 3.91%   |
| Unspecified | 2         | 0.04%   |
| Web         | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1803      | 39.82%  |
| GDM     | 904       | 19.96%  |
| LightDM | 709       | 15.66%  |
| SDDM    | 538       | 11.88%  |
| TDM     | 310       | 6.85%   |
| GDM3    | 213       | 4.7%    |
| XDM     | 18        | 0.4%    |
| SLiM    | 13        | 0.29%   |
| NODM    | 8         | 0.18%   |
| KDM     | 7         | 0.15%   |
| LXDM    | 3         | 0.07%   |
| WDM     | 1         | 0.02%   |
| Ly      | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1338      | 29.81%  |
| Unknown | 939       | 20.92%  |
| ru_RU   | 303       | 6.75%   |
| de_DE   | 271       | 6.04%   |
| fr_FR   | 241       | 5.37%   |
| en_GB   | 189       | 4.21%   |
| pt_BR   | 150       | 3.34%   |
| es_ES   | 133       | 2.96%   |
| it_IT   | 124       | 2.76%   |
| pl_PL   | 89        | 1.98%   |
| en_CA   | 51        | 1.14%   |
| C       | 47        | 1.05%   |
| es_MX   | 43        | 0.96%   |
| en_AU   | 40        | 0.89%   |
| en_IN   | 38        | 0.85%   |
| zh_CN   | 37        | 0.82%   |
| es_CL   | 28        | 0.62%   |
| es_AR   | 28        | 0.62%   |
| en_IE   | 26        | 0.58%   |
| hu_HU   | 24        | 0.53%   |
| de_CH   | 19        | 0.42%   |
| pt_PT   | 18        | 0.4%    |
| fi_FI   | 15        | 0.33%   |
| es_VE   | 15        | 0.33%   |
| nl_NL   | 14        | 0.31%   |
| cs_CZ   | 14        | 0.31%   |
| en_NZ   | 13        | 0.29%   |
| ja_JP   | 12        | 0.27%   |
| de_AT   | 12        | 0.27%   |
| sv_SE   | 11        | 0.25%   |
| es_CO   | 11        | 0.25%   |
| en_ZA   | 11        | 0.25%   |
| tr_TR   | 10        | 0.22%   |
| ko_KR   | 10        | 0.22%   |
| fr_BE   | 9         | 0.2%    |
| en_SG   | 9         | 0.2%    |
| ru_UA   | 8         | 0.18%   |
| ca_ES   | 8         | 0.18%   |
| da_DK   | 7         | 0.16%   |
| zh_TW   | 6         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2731      | 61.23%  |
| BIOS | 1729      | 38.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 3137      | 70.68%  |
| Overlay | 991       | 22.33%  |
| Btrfs   | 138       | 3.11%   |
| Unknown | 78        | 1.76%   |
| Xfs     | 41        | 0.92%   |
| Ext2    | 14        | 0.32%   |
| Zfs     | 13        | 0.29%   |
| Tmpfs   | 8         | 0.18%   |
| Rootfs  | 7         | 0.16%   |
| Ext3    | 6         | 0.14%   |
| Aufs    | 4         | 0.09%   |
| F2fs    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2752      | 61.33%  |
| Unknown | 880       | 19.61%  |
| MBR     | 855       | 19.06%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3642      | 81.55%  |
| Yes       | 824       | 18.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3300      | 73.89%  |
| Yes       | 1166      | 26.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 980       | 22.2%   |
| Hewlett-Packard        | 647       | 14.66%  |
| Dell                   | 630       | 14.27%  |
| Apple                  | 593       | 13.43%  |
| ASUSTek Computer       | 413       | 9.36%   |
| Acer                   | 280       | 6.34%   |
| Google                 | 140       | 3.17%   |
| Toshiba                | 73        | 1.65%   |
| MSI                    | 69        | 1.56%   |
| Samsung Electronics    | 67        | 1.52%   |
| Aquarius               | 44        | 1%      |
| HUAWEI                 | 40        | 0.91%   |
| Sony                   | 39        | 0.88%   |
| Unknown                | 36        | 0.82%   |
| Notebook               | 27        | 0.61%   |
| Fujitsu                | 19        | 0.43%   |
| Panasonic              | 14        | 0.32%   |
| Medion                 | 14        | 0.32%   |
| Alienware              | 13        | 0.29%   |
| Intel                  | 12        | 0.27%   |
| IBM                    | 12        | 0.27%   |
| Timi                   | 11        | 0.25%   |
| Positivo               | 11        | 0.25%   |
| TUXEDO                 | 10        | 0.23%   |
| Packard Bell           | 10        | 0.23%   |
| Clevo                  | 9         | 0.2%    |
| LG Electronics         | 8         | 0.18%   |
| Fujitsu Siemens        | 8         | 0.18%   |
| Razer                  | 7         | 0.16%   |
| SLIMBOOK               | 6         | 0.14%   |
| PC Specialist          | 6         | 0.14%   |
| GPU Company            | 6         | 0.14%   |
| Gigabyte Technology    | 6         | 0.14%   |
| HONOR                  | 5         | 0.11%   |
| Chuwi                  | 5         | 0.11%   |
| Avell High Performance | 5         | 0.11%   |
| System76               | 4         | 0.09%   |
| Insyde                 | 4         | 0.09%   |
| Gateway                | 4         | 0.09%   |
| eMachines              | 4         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBook5,2                      | 307       | 6.96%   |
| Apple MacBookAir7,2                   | 77        | 1.74%   |
| Apple MacBookAir7,1                   | 77        | 1.74%   |
| Google Enguarde                       | 74        | 1.68%   |
| Apple MacBook2,1                      | 56        | 1.27%   |
| Unknown                               | 48        | 1.09%   |
| Aquarius NS585                        | 44        | 1%      |
| Lenovo ThinkPad E475 20H40006US       | 24        | 0.54%   |
| Google Terra                          | 23        | 0.52%   |
| Apple MacBook4,1                      | 23        | 0.52%   |
| HP Notebook                           | 22        | 0.5%    |
| HP Pavilion g6                        | 17        | 0.39%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US | 16        | 0.36%   |
| Acer Aspire A315-23                   | 16        | 0.36%   |
| ASUS 1005HA                           | 15        | 0.34%   |
| Dell Latitude E7440                   | 12        | 0.27%   |
| HP EliteBook 8460p                    | 11        | 0.25%   |
| Google Reks                           | 11        | 0.25%   |
| HP Laptop 15-db0xxx                   | 10        | 0.23%   |
| HP 250 G7 Notebook PC                 | 9         | 0.2%    |
| Samsung 300E4C/300E5C/300E7C          | 8         | 0.18%   |
| Dell XPS 13 9310                      | 8         | 0.18%   |
| Dell Latitude E7450                   | 8         | 0.18%   |
| Dell Latitude E6430                   | 8         | 0.18%   |
| Dell Latitude E6420                   | 8         | 0.18%   |
| Dell Latitude E6330                   | 8         | 0.18%   |
| Dell Latitude 7480                    | 8         | 0.18%   |
| Dell Inspiron 5570                    | 8         | 0.18%   |
| Dell Inspiron 15-3567                 | 8         | 0.18%   |
| Lenovo IdeaPad S145-15API 81V7        | 7         | 0.16%   |
| HP Stream Notebook PC 13              | 7         | 0.16%   |
| HP Pavilion Notebook                  | 7         | 0.16%   |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 7         | 0.16%   |
| HP Pavilion dv6                       | 7         | 0.16%   |
| HP Laptop 15-db1xxx                   | 7         | 0.16%   |
| HP Laptop 15-bw0xx                    | 7         | 0.16%   |
| HP EliteBook 8470p                    | 7         | 0.16%   |
| HP EliteBook 840 G8 Notebook PC       | 7         | 0.16%   |
| HP EliteBook 840 G3                   | 7         | 0.16%   |
| Dell Latitude E7470                   | 7         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 649       | 14.7%   |
| Apple MacBook5    | 308       | 6.98%   |
| Dell Latitude     | 241       | 5.46%   |
| Dell Inspiron     | 196       | 4.44%   |
| Acer Aspire       | 183       | 4.15%   |
| Lenovo IdeaPad    | 172       | 3.9%    |
| Apple MacBookAir7 | 154       | 3.49%   |
| HP EliteBook      | 132       | 2.99%   |
| HP Pavilion       | 98        | 2.22%   |
| HP ProBook        | 85        | 1.93%   |
| HP Laptop         | 85        | 1.93%   |
| Google Enguarde   | 74        | 1.68%   |
| Dell XPS          | 66        | 1.5%    |
| ASUS VivoBook     | 58        | 1.31%   |
| Toshiba Satellite | 56        | 1.27%   |
| Apple MacBook2    | 56        | 1.27%   |
| Dell Vostro       | 54        | 1.22%   |
| Unknown           | 48        | 1.09%   |
| Dell Precision    | 47        | 1.06%   |
| Aquarius NS585    | 44        | 1%      |
| HP Compaq         | 40        | 0.91%   |
| HP 250            | 29        | 0.66%   |
| ASUS ZenBook      | 29        | 0.66%   |
| HP ZBook          | 27        | 0.61%   |
| Lenovo Legion     | 25        | 0.57%   |
| ASUS ASUS         | 24        | 0.54%   |
| Google Terra      | 23        | 0.52%   |
| Apple MacBook4    | 23        | 0.52%   |
| HP Notebook       | 22        | 0.5%    |
| Lenovo ThinkBook  | 21        | 0.48%   |
| Acer Swift        | 21        | 0.48%   |
| Acer Nitro        | 21        | 0.48%   |
| HP 255            | 18        | 0.41%   |
| Acer TravelMate   | 18        | 0.41%   |
| ASUS ROG          | 17        | 0.39%   |
| HP OMEN           | 16        | 0.36%   |
| HP ENVY           | 16        | 0.36%   |
| Fujitsu LIFEBOOK  | 16        | 0.36%   |
| ASUS 1005HA       | 15        | 0.34%   |
| HP Stream         | 14        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 449       | 10.17%  |
| 2009    | 438       | 9.92%   |
| 2020    | 399       | 9.04%   |
| 2021    | 370       | 8.38%   |
| 2018    | 285       | 6.46%   |
| 2016    | 285       | 6.46%   |
| 2012    | 282       | 6.39%   |
| 2011    | 278       | 6.3%    |
| 2017    | 275       | 6.23%   |
| 2015    | 271       | 6.14%   |
| 2013    | 217       | 4.92%   |
| 2014    | 189       | 4.28%   |
| 2010    | 165       | 3.74%   |
| 2022    | 159       | 3.6%    |
| 2008    | 136       | 3.08%   |
| 2007    | 124       | 2.81%   |
| 2006    | 30        | 0.68%   |
| 2005    | 23        | 0.52%   |
| Unknown | 14        | 0.32%   |
| 2004    | 11        | 0.25%   |
| 2003    | 11        | 0.25%   |
| 2002    | 2         | 0.05%   |
| 2023    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4414      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4081      | 92%     |
| Enabled  | 355       | 8%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4261      | 96.51%  |
| Yes  | 154       | 3.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1159      | 26.02%  |
| 3.01-4.0    | 854       | 19.17%  |
| 16.01-24.0  | 704       | 15.8%   |
| 8.01-16.0   | 676       | 15.17%  |
| 1.01-2.0    | 537       | 12.05%  |
| 32.01-64.0  | 244       | 5.48%   |
| 2.01-3.0    | 93        | 2.09%   |
| 0.51-1.0    | 77        | 1.73%   |
| 64.01-256.0 | 45        | 1.01%   |
| 24.01-32.0  | 43        | 0.97%   |
| 0.01-0.5    | 21        | 0.47%   |
| Unknown     | 2         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1858      | 39.29%  |
| 2.01-3.0   | 960       | 20.3%   |
| 4.01-8.0   | 609       | 12.88%  |
| 3.01-4.0   | 498       | 10.53%  |
| 0.51-1.0   | 491       | 10.38%  |
| 8.01-16.0  | 163       | 3.45%   |
| 0.01-0.5   | 123       | 2.6%    |
| 16.01-24.0 | 13        | 0.27%   |
| Unknown    | 7         | 0.15%   |
| 32.01-64.0 | 3         | 0.06%   |
| 24.01-32.0 | 3         | 0.06%   |
| 0          | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3511      | 78.46%  |
| 2      | 826       | 18.46%  |
| 3      | 90        | 2.01%   |
| 0      | 27        | 0.6%    |
| 4      | 15        | 0.34%   |
| 5      | 4         | 0.09%   |
| 7      | 2         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2889      | 65.21%  |
| Yes       | 1541      | 34.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3598      | 81.26%  |
| No        | 830       | 18.74%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4308      | 97.51%  |
| No        | 110       | 2.49%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3542      | 79.69%  |
| No        | 903       | 20.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 1188      | 26.73%  |
| Germany      | 404       | 9.09%   |
| Russia       | 352       | 7.92%   |
| France       | 304       | 6.84%   |
| Brazil       | 225       | 5.06%   |
| Spain        | 189       | 4.25%   |
| Italy        | 168       | 3.78%   |
| Poland       | 125       | 2.81%   |
| UK           | 99        | 2.23%   |
| Netherlands  | 75        | 1.69%   |
| Canada       | 71        | 1.6%    |
| Switzerland  | 64        | 1.44%   |
| Mexico       | 61        | 1.37%   |
| India        | 56        | 1.26%   |
| China        | 51        | 1.15%   |
| Ukraine      | 50        | 1.13%   |
| Argentina    | 49        | 1.1%    |
| Australia    | 45        | 1.01%   |
| Sweden       | 41        | 0.92%   |
| Portugal     | 41        | 0.92%   |
| Hungary      | 40        | 0.9%    |
| Turkey       | 38        | 0.86%   |
| Belgium      | 36        | 0.81%   |
| Chile        | 34        | 0.77%   |
| Czechia      | 31        | 0.7%    |
| Austria      | 30        | 0.68%   |
| Greece       | 29        | 0.65%   |
| Finland      | 29        | 0.65%   |
| Norway       | 26        | 0.59%   |
| Romania      | 23        | 0.52%   |
| Ireland      | 22        | 0.5%    |
| Indonesia    | 22        | 0.5%    |
| Japan        | 21        | 0.47%   |
| Colombia     | 21        | 0.47%   |
| Venezuela    | 18        | 0.41%   |
| New Zealand  | 17        | 0.38%   |
| Thailand     | 16        | 0.36%   |
| Denmark      | 16        | 0.36%   |
| Bulgaria     | 16        | 0.36%   |
| South Africa | 13        | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Bangor            | 567       | 12.08%  |
| Dover-Foxcroft    | 229       | 4.88%   |
| Voronezh          | 145       | 3.09%   |
| Paris             | 57        | 1.21%   |
| Moscow            | 52        | 1.11%   |
| St Petersburg     | 50        | 1.06%   |
| Berlin            | 43        | 0.92%   |
| Seville           | 36        | 0.77%   |
| Madrid            | 36        | 0.77%   |
| Sao Paulo         | 35        | 0.75%   |
| Warsaw            | 32        | 0.68%   |
| Munich            | 30        | 0.64%   |
| Milan             | 24        | 0.51%   |
| Amsterdam         | 23        | 0.49%   |
| Vienna            | 22        | 0.47%   |
| Hamburg           | 22        | 0.47%   |
| Barcelona         | 19        | 0.4%    |
| Prague            | 18        | 0.38%   |
| London            | 18        | 0.38%   |
| Frankfurt am Main | 18        | 0.38%   |
| Zurich            | 17        | 0.36%   |
| Budapest          | 17        | 0.36%   |
| Istanbul          | 16        | 0.34%   |
| Athens            | 16        | 0.34%   |
| Sydney            | 15        | 0.32%   |
| Mexico City       | 15        | 0.32%   |
| Helsinki          | 15        | 0.32%   |
| Lisbon            | 14        | 0.3%    |
| Dublin            | 14        | 0.3%    |
| Perm              | 13        | 0.28%   |
| Singapore         | 12        | 0.26%   |
| Brasília         | 12        | 0.26%   |
| Zagreb            | 11        | 0.23%   |
| Toronto           | 11        | 0.23%   |
| Rome              | 11        | 0.23%   |
| Cologne           | 11        | 0.23%   |
| Blizniew          | 11        | 0.23%   |
| Bangkok           | 11        | 0.23%   |
| Turin             | 10        | 0.21%   |
| San José         | 10        | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 766       | 973    | 14.48%  |
| WDC                       | 594       | 726    | 11.23%  |
| Seagate                   | 500       | 595    | 9.45%   |
| Toshiba                   | 409       | 457    | 7.73%   |
| Unknown                   | 356       | 459    | 6.73%   |
| Kingston                  | 294       | 357    | 5.56%   |
| SanDisk                   | 257       | 311    | 4.86%   |
| Fujitsu                   | 253       | 260    | 4.78%   |
| Crucial                   | 204       | 248    | 3.86%   |
| SK hynix                  | 198       | 243    | 3.74%   |
| Apple                     | 181       | 220    | 3.42%   |
| Hitachi                   | 148       | 172    | 2.8%    |
| Intel                     | 123       | 147    | 2.33%   |
| A-DATA Technology         | 122       | 212    | 2.31%   |
| Micron Technology         | 116       | 123    | 2.19%   |
| HGST                      | 106       | 124    | 2%      |
| KIOXIA                    | 50        | 62     | 0.95%   |
| LITEON                    | 32        | 37     | 0.6%    |
| China                     | 30        | 33     | 0.57%   |
| Unknown                   | 29        | 30     | 0.55%   |
| Transcend                 | 27        | 34     | 0.51%   |
| Silicon Motion            | 22        | 24     | 0.42%   |
| Intenso                   | 22        | 29     | 0.42%   |
| PNY                       | 21        | 24     | 0.4%    |
| Phison                    | 21        | 29     | 0.4%    |
| SPCC                      | 20        | 24     | 0.38%   |
| SABRENT                   | 17        | 18     | 0.32%   |
| Patriot                   | 16        | 18     | 0.3%    |
| LITEONIT                  | 15        | 17     | 0.28%   |
| SSSTC                     | 14        | 14     | 0.26%   |
| Team                      | 13        | 15     | 0.25%   |
| GOODRAM                   | 13        | 15     | 0.25%   |
| OCZ                       | 12        | 14     | 0.23%   |
| JMicron Technology        | 12        | 12     | 0.23%   |
| Micron/Crucial Technology | 11        | 11     | 0.21%   |
| LDLC                      | 9         | 9      | 0.17%   |
| Plextor                   | 8         | 8      | 0.15%   |
| Netac                     | 8         | 12     | 0.15%   |
| Lenovo                    | 8         | 10     | 0.15%   |
| Hewlett-Packard           | 8         | 8      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB       | 202       | 3.73%   |
| Apple SSD AP0128H 121GB              | 77        | 1.42%   |
| Apple SSD SM0128G 121GB              | 72        | 1.33%   |
| Seagate ST1000LM035-1RK172 1TB       | 64        | 1.18%   |
| Kingston SA400S37240G 240GB SSD      | 61        | 1.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 53        | 0.98%   |
| Kingston SA400S37120G 120GB SSD      | 51        | 0.94%   |
| Toshiba MK1655GSXF 160GB             | 46        | 0.85%   |
| A-DATA SU800 512GB SSD               | 46        | 0.85%   |
| Toshiba MK1653GSX 160GB              | 43        | 0.79%   |
| Unknown AGND3R  16GB                 | 39        | 0.72%   |
| HGST HTS721010A9E630 1TB             | 39        | 0.72%   |
| Toshiba MQ01ABD100 1TB               | 38        | 0.7%    |
| Toshiba MQ01ABF050 500GB             | 33        | 0.61%   |
| Toshiba MQ04ABF100 1TB               | 32        | 0.59%   |
| Crucial CT500MX500SSD1 500GB         | 32        | 0.59%   |
| Unknown MMC Card  32GB               | 31        | 0.57%   |
| Unknown HAG2e  16GB                  | 31        | 0.57%   |
| Unknown                              | 29        | 0.54%   |
| Samsung SSD 860 EVO 500GB            | 26        | 0.48%   |
| Unknown SDW16G  16GB                 | 25        | 0.46%   |
| Samsung SSD 850 EVO 250GB            | 25        | 0.46%   |
| Seagate ST500LT012-1DG142 500GB      | 24        | 0.44%   |
| Seagate ST1000LM048-2E7172 1TB       | 24        | 0.44%   |
| Kingston SA400S37480G 480GB SSD      | 24        | 0.44%   |
| Samsung SSD 970 EVO Plus 1TB         | 23        | 0.43%   |
| Samsung SSD 860 EVO 1TB              | 22        | 0.41%   |
| Crucial CT1000MX500SSD1 1TB          | 22        | 0.41%   |
| Samsung SSD 860 EVO 250GB            | 21        | 0.39%   |
| Kingston SV300S37A120G 120GB SSD     | 21        | 0.39%   |
| Unknown MMC Card  64GB               | 20        | 0.37%   |
| Seagate ST9500325AS 500GB            | 20        | 0.37%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 19        | 0.35%   |
| Crucial CT240BX500SSD1 240GB         | 19        | 0.35%   |
| WDC WD10SPZX-24Z10 1TB               | 18        | 0.33%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 18        | 0.33%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 18        | 0.33%   |
| HGST HTS725050A7E630 500GB           | 18        | 0.33%   |
| Seagate ST1000LM049-2GH172 1TB       | 17        | 0.31%   |
| SABRENT Disk 256GB                   | 17        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 482       | 574    | 27.88%  |
| WDC                 | 348       | 395    | 20.13%  |
| Toshiba             | 300       | 330    | 17.35%  |
| Fujitsu             | 253       | 260    | 14.63%  |
| Hitachi             | 148       | 172    | 8.56%   |
| HGST                | 106       | 124    | 6.13%   |
| Samsung Electronics | 33        | 35     | 1.91%   |
| SABRENT             | 17        | 18     | 0.98%   |
| Unknown             | 12        | 15     | 0.69%   |
| JMicron Technology  | 7         | 7      | 0.4%    |
| IBM/Hitachi         | 5         | 6      | 0.29%   |
| Intenso             | 4         | 5      | 0.23%   |
| SILICONMOTION       | 2         | 2      | 0.12%   |
| ASMT                | 2         | 7      | 0.12%   |
| USB3.0              | 1         | 1      | 0.06%   |
| Unknown (CF)        | 1         | 1      | 0.06%   |
| SAGE                | 1         | 1      | 0.06%   |
| QNAP                | 1         | 2      | 0.06%   |
| PHD 3.0             | 1         | 1      | 0.06%   |
| Maxone              | 1         | 1      | 0.06%   |
| IBM                 | 1         | 1      | 0.06%   |
| Hewlett-Packard     | 1         | 1      | 0.06%   |
| ASMT109x            | 1         | 1      | 0.06%   |
| Apple               | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 352       | 445    | 20.35%  |
| Kingston            | 232       | 291    | 13.41%  |
| SanDisk             | 191       | 237    | 11.04%  |
| Crucial             | 184       | 225    | 10.64%  |
| Apple               | 95        | 102    | 5.49%   |
| A-DATA Technology   | 90        | 168    | 5.2%    |
| WDC                 | 67        | 88     | 3.87%   |
| Micron Technology   | 51        | 54     | 2.95%   |
| SK hynix            | 39        | 47     | 2.25%   |
| Intel               | 37        | 41     | 2.14%   |
| China               | 30        | 33     | 1.73%   |
| Toshiba             | 29        | 32     | 1.68%   |
| LITEON              | 26        | 30     | 1.5%    |
| Transcend           | 25        | 32     | 1.45%   |
| PNY                 | 17        | 19     | 0.98%   |
| SPCC                | 16        | 19     | 0.92%   |
| Intenso             | 16        | 21     | 0.92%   |
| Patriot             | 15        | 17     | 0.87%   |
| LITEONIT            | 15        | 17     | 0.87%   |
| Team                | 12        | 14     | 0.69%   |
| OCZ                 | 12        | 14     | 0.69%   |
| GOODRAM             | 10        | 12     | 0.58%   |
| Plextor             | 8         | 8      | 0.46%   |
| Netac               | 8         | 12     | 0.46%   |
| LDLC                | 8         | 8      | 0.46%   |
| KingSpec            | 7         | 7      | 0.4%    |
| KingDian            | 6         | 6      | 0.35%   |
| Unknown             | 6         | 6      | 0.35%   |
| Seagate             | 5         | 5      | 0.29%   |
| Lexar               | 5         | 6      | 0.29%   |
| Corsair             | 5         | 5      | 0.29%   |
| ASMT                | 5         | 5      | 0.29%   |
| Apacer              | 5         | 5      | 0.29%   |
| Hewlett-Packard     | 4         | 5      | 0.23%   |
| Dogfish             | 4         | 7      | 0.23%   |
| BIWIN               | 4         | 4      | 0.23%   |
| ASUS-PHISON         | 4         | 5      | 0.23%   |
| ZTC                 | 3         | 7      | 0.17%   |
| KIOXIA-EXCERIA      | 3         | 4      | 0.17%   |
| Kingchuxing         | 3         | 3      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1678      | 1961   | 33.06%  |
| SSD     | 1620      | 2161   | 31.92%  |
| NVMe    | 1346      | 1744   | 26.52%  |
| MMC     | 381       | 486    | 7.51%   |
| Unknown | 50        | 56     | 0.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2977      | 3979   | 61.31%  |
| NVMe | 1345      | 1739   | 27.7%   |
| MMC  | 381       | 486    | 7.85%   |
| SAS  | 153       | 204    | 3.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2332      | 2929   | 71.8%   |
| 0.51-1.0   | 821       | 1065   | 25.28%  |
| 1.01-2.0   | 73        | 93     | 2.25%   |
| 4.01-10.0  | 14        | 21     | 0.43%   |
| 3.01-4.0   | 5         | 6      | 0.15%   |
| 2.01-3.0   | 3         | 8      | 0.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1297      | 28.37%  |
| 251-500        | 934       | 20.43%  |
| Unknown        | 732       | 16.01%  |
| 501-1000       | 584       | 12.78%  |
| 51-100         | 302       | 6.61%   |
| 1001-2000      | 229       | 5.01%   |
| 1-20           | 228       | 4.99%   |
| 21-50          | 168       | 3.68%   |
| 2001-3000      | 54        | 1.18%   |
| More than 3000 | 43        | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1661      | 35.24%  |
| Unknown        | 732       | 15.53%  |
| 101-250        | 604       | 12.82%  |
| 21-50          | 601       | 12.75%  |
| 51-100         | 492       | 10.44%  |
| 251-500        | 325       | 6.9%    |
| 501-1000       | 193       | 4.1%    |
| 1001-2000      | 65        | 1.38%   |
| More than 3000 | 16        | 0.34%   |
| 2001-3000      | 13        | 0.28%   |
| 0              | 11        | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB        | 20        | 20     | 4.58%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 11        | 13     | 2.52%   |
| Seagate ST9500325AS 500GB             | 10        | 10     | 2.29%   |
| Toshiba MK1653GSX 160GB               | 9         | 9      | 2.06%   |
| Toshiba MK1655GSXF 160GB              | 7         | 7      | 1.6%    |
| Seagate ST9500420AS 500GB             | 7         | 7      | 1.6%    |
| Seagate ST1000LM035-1RK172 1TB        | 6         | 6      | 1.37%   |
| Hitachi HTS545050B9A300 500GB         | 6         | 6      | 1.37%   |
| Hitachi HTS543216L9SA02 160GB         | 6         | 6      | 1.37%   |
| Toshiba MQ01ABD100 1TB                | 5         | 5      | 1.14%   |
| Seagate ST500LT012-9WS142 500GB       | 5         | 6      | 1.14%   |
| Seagate ST500LM021-1KJ152 500GB       | 5         | 5      | 1.14%   |
| Hitachi HTS542512K9SA00 120GB         | 5         | 6      | 1.14%   |
| HGST HTS725050A7E630 500GB            | 5         | 6      | 1.14%   |
| WDC WD1600BUDT-63DPZY0 160GB          | 4         | 4      | 0.92%   |
| Toshiba MQ01ABF050 500GB              | 4         | 4      | 0.92%   |
| Seagate ST500LM000-SSHD-8GB           | 4         | 4      | 0.92%   |
| Seagate ST320LT007-9ZV142 320GB       | 4         | 6      | 0.92%   |
| Hitachi HTS547575A9E384 752GB         | 4         | 4      | 0.92%   |
| HGST HTS541010A9E680 1TB              | 4         | 4      | 0.92%   |
| Toshiba MQ04ABF100 1TB                | 3         | 3      | 0.69%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 3         | 3      | 0.69%   |
| SK hynix HFS256G39MND-2300A 256GB SSD | 3         | 4      | 0.69%   |
| Seagate ST9320325AS 320GB             | 3         | 3      | 0.69%   |
| Seagate ST9250315AS 250GB             | 3         | 4      | 0.69%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 0.69%   |
| Kingston SA400S37240G 240GB SSD       | 3         | 3      | 0.69%   |
| Hitachi HTS547550A9E384 500GB         | 3         | 3      | 0.69%   |
| Hitachi HTS542516K9SA00 160GB         | 3         | 3      | 0.69%   |
| HGST HTS721010A9E630 1TB              | 3         | 4      | 0.69%   |
| Crucial CT275MX300SSD1 275GB          | 3         | 3      | 0.69%   |
| WDC WD7500BPVX-22JC3T0 752GB          | 2         | 2      | 0.46%   |
| WDC WD7500BPKT-75PK4T0 752GB          | 2         | 2      | 0.46%   |
| WDC WD5000LPVX-75V0TT0 500GB          | 2         | 2      | 0.46%   |
| WDC WD10SPZX-60Z10T0 1TB              | 2         | 3      | 0.46%   |
| WDC WD10JPVX-22JC3T0 1TB              | 2         | 2      | 0.46%   |
| WDC WD10JPCX-24UE4T0 1TB              | 2         | 3      | 0.46%   |
| Toshiba MQ01ACF050 500GB              | 2         | 2      | 0.46%   |
| Toshiba MQ01ABD050 500GB              | 2         | 2      | 0.46%   |
| SK hynix SH920 mSATA 128GB SSD        | 2         | 2      | 0.46%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 94        | 102    | 21.56%  |
| Hitachi             | 65        | 70     | 14.91%  |
| Toshiba             | 50        | 51     | 11.47%  |
| WDC                 | 42        | 44     | 9.63%   |
| Fujitsu             | 34        | 34     | 7.8%    |
| Samsung Electronics | 25        | 27     | 5.73%   |
| HGST                | 23        | 25     | 5.28%   |
| SK hynix            | 17        | 18     | 3.9%    |
| Kingston            | 13        | 14     | 2.98%   |
| Micron Technology   | 12        | 12     | 2.75%   |
| Intel               | 10        | 11     | 2.29%   |
| SanDisk             | 9         | 11     | 2.06%   |
| A-DATA Technology   | 9         | 10     | 2.06%   |
| Crucial             | 8         | 9      | 1.83%   |
| LITEONIT            | 3         | 4      | 0.69%   |
| LITEON              | 3         | 3      | 0.69%   |
| IBM/Hitachi         | 2         | 2      | 0.46%   |
| Corsair             | 2         | 2      | 0.46%   |
| Unknown             | 2         | 2      | 0.46%   |
| Team                | 1         | 1      | 0.23%   |
| SSSTC               | 1         | 1      | 0.23%   |
| ShiJi               | 1         | 1      | 0.23%   |
| Plextor             | 1         | 1      | 0.23%   |
| Lenovo              | 1         | 1      | 0.23%   |
| KingSpec            | 1         | 1      | 0.23%   |
| KingDian            | 1         | 1      | 0.23%   |
| JMicron Technology  | 1         | 1      | 0.23%   |
| IBM                 | 1         | 1      | 0.23%   |
| GOODRAM             | 1         | 1      | 0.23%   |
| DGM                 | 1         | 1      | 0.23%   |
| China               | 1         | 1      | 0.23%   |
| Apple               | 1         | 1      | 0.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 94        | 102    | 29.1%   |
| Hitachi             | 65        | 70     | 20.12%  |
| Toshiba             | 49        | 50     | 15.17%  |
| WDC                 | 41        | 43     | 12.69%  |
| Fujitsu             | 34        | 34     | 10.53%  |
| HGST                | 23        | 25     | 7.12%   |
| Samsung Electronics | 13        | 13     | 4.02%   |
| IBM/Hitachi         | 2         | 2      | 0.62%   |
| JMicron Technology  | 1         | 1      | 0.31%   |
| IBM                 | 1         | 1      | 0.31%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 320       | 341    | 73.9%   |
| SSD  | 98        | 108    | 22.63%  |
| NVMe | 15        | 15     | 3.46%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 14.29%  |
| Toshiba MK6465GSX 640GB                         | 1         | 1      | 14.29%  |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 14.29%  |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 14.29%  |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 14.29%  |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 14.29%  |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 28.57%  |
| Samsung Electronics | 2         | 2      | 28.57%  |
| WDC                 | 1         | 1      | 14.29%  |
| Toshiba             | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 2      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3001      | 4001   | 63.33%  |
| Detected | 1300      | 1934   | 27.43%  |
| Malfunc  | 430       | 464    | 9.07%   |
| Failed   | 7         | 8      | 0.15%   |
| Limited  | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2694      | 55.23%  |
| Samsung Electronics              | 480       | 9.84%   |
| AMD                              | 416       | 8.53%   |
| Nvidia                           | 328       | 6.72%   |
| SanDisk                          | 231       | 4.74%   |
| SK hynix                         | 148       | 3.03%   |
| Toshiba America Info Systems     | 85        | 1.74%   |
| Apple                            | 84        | 1.72%   |
| Micron Technology                | 65        | 1.33%   |
| Kingston Technology Company      | 62        | 1.27%   |
| KIOXIA                           | 51        | 1.05%   |
| Phison Electronics               | 39        | 0.8%    |
| ADATA Technology                 | 39        | 0.8%    |
| Silicon Motion                   | 33        | 0.68%   |
| Micron/Crucial Technology        | 31        | 0.64%   |
| Solid State Storage Technology   | 18        | 0.37%   |
| Union Memory (Shenzhen)          | 12        | 0.25%   |
| Silicon Integrated Systems [SiS] | 12        | 0.25%   |
| Lite-On Technology               | 7         | 0.14%   |
| Shenzhen Longsys Electronics     | 5         | 0.1%    |
| Realtek Semiconductor            | 5         | 0.1%    |
| Lenovo                           | 5         | 0.1%    |
| MAXIO Technology (Hangzhou)      | 4         | 0.08%   |
| ULi Electronics                  | 3         | 0.06%   |
| Silicon Image                    | 3         | 0.06%   |
| Seagate Technology               | 3         | 0.06%   |
| Jiangsu Huacun Elec.             | 3         | 0.06%   |
| VIA Technologies                 | 2         | 0.04%   |
| Marvell Technology Group         | 2         | 0.04%   |
| Biwin Storage Technology         | 2         | 0.04%   |
| ASMedia Technology               | 2         | 0.04%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| JMicron Technology               | 1         | 0.02%   |
| Adaptec                          | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 361       | 6.9%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 354       | 6.76%   |
| Nvidia MCP79 AHCI Controller                                                   | 314       | 6%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 302       | 5.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 205       | 3.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 201       | 3.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 189       | 3.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 136       | 2.6%    |
| Intel Volume Management Device NVMe RAID Controller                            | 127       | 2.43%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 113       | 2.16%   |
| Samsung NVMe SSD Controller 980                                                | 103       | 1.97%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 101       | 1.93%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 95        | 1.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 86        | 1.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 84        | 1.6%    |
| Samsung Electronics SATA controller                                            | 83        | 1.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 82        | 1.57%   |
| Apple S1X NVMe Controller                                                      | 78        | 1.49%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 77        | 1.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 76        | 1.45%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 73        | 1.39%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 71        | 1.36%   |
| Intel Comet Lake SATA AHCI Controller                                          | 66        | 1.26%   |
| Micron Non-Volatile memory controller                                          | 65        | 1.24%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 59        | 1.13%   |
| Intel Tiger Lake-LP SATA Controller                                            | 59        | 1.13%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 56        | 1.07%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 54        | 1.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 52        | 0.99%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 51        | 0.97%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 47        | 0.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 45        | 0.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 45        | 0.86%   |
| Intel SSD 660P Series                                                          | 44        | 0.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 44        | 0.84%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 42        | 0.8%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 40        | 0.76%   |
| SanDisk Non-Volatile memory controller                                         | 38        | 0.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 36        | 0.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 36        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3036      | 59.56%  |
| NVMe | 1354      | 26.56%  |
| IDE  | 372       | 7.3%    |
| RAID | 334       | 6.55%   |
| SCSI | 1         | 0.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 3795      | 85.96%  |
| AMD          | 602       | 13.64%  |
| ARM          | 11        | 0.25%   |
| CentaurHauls | 5         | 0.11%   |
| Unknown      | 2         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 309       | 6.99%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 146       | 3.3%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 92        | 2.08%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 81        | 1.83%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 72        | 1.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 71        | 1.61%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 65        | 1.47%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 64        | 1.45%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 64        | 1.45%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 61        | 1.38%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 59        | 1.34%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 56        | 1.27%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 56        | 1.27%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 54        | 1.22%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 50        | 1.13%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 47        | 1.06%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 47        | 1.06%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 44        | 1%      |
| Intel Core i7-7500U CPU @ 2.70GHz             | 40        | 0.91%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 40        | 0.91%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 38        | 0.86%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 35        | 0.79%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 34        | 0.77%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 33        | 0.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 30        | 0.68%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 30        | 0.68%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 30        | 0.68%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 28        | 0.63%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 28        | 0.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 27        | 0.61%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 27        | 0.61%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 26        | 0.59%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 26        | 0.59%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 25        | 0.57%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 25        | 0.57%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 24        | 0.54%   |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G    | 24        | 0.54%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 22        | 0.5%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 22        | 0.5%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 22        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1099      | 24.88%  |
| Intel Core i7           | 840       | 19.02%  |
| Intel Core 2 Duo        | 486       | 11%     |
| Other                   | 340       | 7.7%    |
| Intel Celeron           | 328       | 7.43%   |
| Intel Core i3           | 297       | 6.72%   |
| AMD Ryzen 5             | 171       | 3.87%   |
| Intel Atom              | 132       | 2.99%   |
| AMD Ryzen 7             | 101       | 2.29%   |
| Intel Pentium           | 82        | 1.86%   |
| Intel Core 2            | 71        | 1.61%   |
| AMD Ryzen 7 PRO         | 44        | 1%      |
| Intel Pentium M         | 32        | 0.72%   |
| AMD A6                  | 30        | 0.68%   |
| Intel Pentium Dual-Core | 26        | 0.59%   |
| AMD A4                  | 25        | 0.57%   |
| AMD Ryzen 3             | 22        | 0.5%    |
| Intel Genuine           | 21        | 0.48%   |
| Intel Pentium Dual      | 20        | 0.45%   |
| AMD A8                  | 19        | 0.43%   |
| AMD E1                  | 16        | 0.36%   |
| AMD Ryzen 9             | 15        | 0.34%   |
| AMD Ryzen 5 PRO         | 15        | 0.34%   |
| Intel Celeron M         | 13        | 0.29%   |
| AMD A10                 | 13        | 0.29%   |
| AMD E2                  | 11        | 0.25%   |
| AMD E                   | 10        | 0.23%   |
| Intel Pentium Silver    | 9         | 0.2%    |
| Intel Pentium 4         | 9         | 0.2%    |
| Intel Core i9           | 9         | 0.2%    |
| Intel Core m3           | 7         | 0.16%   |
| AMD A12                 | 7         | 0.16%   |
| AMD Turion 64 X2 Mobile | 6         | 0.14%   |
| AMD Athlon              | 6         | 0.14%   |
| Intel Xeon              | 5         | 0.11%   |
| Intel Celeron Dual-Core | 5         | 0.11%   |
| ARM ARMv7               | 5         | 0.11%   |
| AMD C-60                | 5         | 0.11%   |
| AMD C-50                | 5         | 0.11%   |
| Intel Mobile Pentium 4  | 4         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2460      | 55.68%  |
| 4      | 1297      | 29.36%  |
| 6      | 230       | 5.21%   |
| 1      | 194       | 4.39%   |
| 8      | 179       | 4.05%   |
| 14     | 22        | 0.5%    |
| 10     | 20        | 0.45%   |
| 12     | 15        | 0.34%   |
| 3      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4413      | 99.98%  |
| 2      | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2927      | 66.27%  |
| 1      | 1489      | 33.71%  |
| 4      | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4229      | 95.77%  |
| 32-bit         | 114       | 2.58%   |
| Unknown        | 71        | 1.61%   |
| 64-bit         | 2         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 936       | 20.74%  |
| 0x1067a    | 398       | 8.82%   |
| 0x306d4    | 247       | 5.47%   |
| 0x306a9    | 216       | 4.79%   |
| 0x206a7    | 195       | 4.32%   |
| 0x806ec    | 181       | 4.01%   |
| 0x806c1    | 165       | 3.66%   |
| 0x806e9    | 126       | 2.79%   |
| 0x806ea    | 119       | 2.64%   |
| 0x40651    | 118       | 2.61%   |
| 0x30678    | 117       | 2.59%   |
| 0x406e3    | 104       | 2.3%    |
| 0x906ea    | 73        | 1.62%   |
| 0x306c3    | 69        | 1.53%   |
| 0x6f6      | 67        | 1.48%   |
| 0x406c4    | 65        | 1.44%   |
| 0xa0652    | 63        | 1.4%    |
| 0x20655    | 60        | 1.33%   |
| 0x08600106 | 53        | 1.17%   |
| 0x0a50000c | 52        | 1.15%   |
| 0x08108109 | 50        | 1.11%   |
| 0x10676    | 45        | 1%      |
| 0x906eb    | 44        | 0.97%   |
| 0x08108102 | 43        | 0.95%   |
| 0x706e5    | 42        | 0.93%   |
| 0x08608103 | 41        | 0.91%   |
| 0x6fd      | 38        | 0.84%   |
| 0x806eb    | 37        | 0.82%   |
| 0x706a8    | 35        | 0.78%   |
| 0x106ca    | 35        | 0.78%   |
| 0x906a3    | 34        | 0.75%   |
| 0x106c2    | 33        | 0.73%   |
| 0x906e9    | 32        | 0.71%   |
| 0x506e3    | 32        | 0.71%   |
| 0x06006705 | 30        | 0.66%   |
| 0x0600611a | 30        | 0.66%   |
| 0x506c9    | 29        | 0.64%   |
| 0x6d8      | 27        | 0.6%    |
| 0x20652    | 24        | 0.53%   |
| 0x406c3    | 23        | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 828       | 18.74%  |
| Penryn           | 478       | 10.82%  |
| IvyBridge        | 291       | 6.59%   |
| Broadwell        | 280       | 6.34%   |
| SandyBridge      | 267       | 6.04%   |
| Haswell          | 253       | 5.73%   |
| Silvermont       | 234       | 5.3%    |
| TigerLake        | 201       | 4.55%   |
| Skylake          | 197       | 4.46%   |
| Core             | 147       | 3.33%   |
| Zen+             | 116       | 2.63%   |
| Westmere         | 115       | 2.6%    |
| Zen 2            | 103       | 2.33%   |
| Unknown          | 100       | 2.26%   |
| CometLake        | 86        | 1.95%   |
| Bonnell          | 85        | 1.92%   |
| Excavator        | 83        | 1.88%   |
| Zen 3            | 68        | 1.54%   |
| IceLake          | 67        | 1.52%   |
| P6               | 63        | 1.43%   |
| Goldmont plus    | 61        | 1.38%   |
| Alderlake Hybrid | 40        | 0.91%   |
| Goldmont         | 39        | 0.88%   |
| Zen              | 35        | 0.79%   |
| Bobcat           | 32        | 0.72%   |
| Puma             | 24        | 0.54%   |
| K8 Hammer        | 18        | 0.41%   |
| Jaguar           | 18        | 0.41%   |
| K10 Llano        | 16        | 0.36%   |
| NetBurst         | 14        | 0.32%   |
| Nehalem          | 13        | 0.29%   |
| Tremont          | 12        | 0.27%   |
| Piledriver       | 12        | 0.27%   |
| K10              | 10        | 0.23%   |
| K8 & K10 hybrid  | 7         | 0.16%   |
| Steamroller      | 6         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3229      | 60.83%  |
| Nvidia                           | 1223      | 23.04%  |
| AMD                              | 840       | 15.83%  |
| Silicon Integrated Systems [SiS] | 7         | 0.13%   |
| Zhaoxin                          | 4         | 0.08%   |
| VIA Technologies                 | 2         | 0.04%   |
| S3 Graphics                      | 2         | 0.04%   |
| Neomagic                         | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 307       | 5.53%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 268       | 4.83%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 238       | 4.29%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 183       | 3.3%    |
| Intel UHD Graphics 620                                                                   | 180       | 3.24%   |
| Intel HD Graphics 6000                                                                   | 154       | 2.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 151       | 2.72%   |
| Intel HD Graphics 620                                                                    | 147       | 2.65%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 141       | 2.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 139       | 2.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 135       | 2.43%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 124       | 2.24%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 119       | 2.14%   |
| Intel HD Graphics 5500                                                                   | 114       | 2.05%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 111       | 2%      |
| AMD Renoir                                                                               | 102       | 1.84%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 98        | 1.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 98        | 1.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 88        | 1.59%   |
| Intel Core Processor Integrated Graphics Controller                                      | 88        | 1.59%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 85        | 1.53%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 77        | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 73        | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 73        | 1.32%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 67        | 1.21%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 62        | 1.12%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 56        | 1.01%   |
| AMD Lucienne                                                                             | 48        | 0.87%   |
| Intel HD Graphics 630                                                                    | 45        | 0.81%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 44        | 0.79%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 43        | 0.78%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 43        | 0.78%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 43        | 0.78%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 40        | 0.72%   |
| Intel HD Graphics 530                                                                    | 39        | 0.7%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 35        | 0.63%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 34        | 0.61%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 34        | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 33        | 0.59%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 33        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2379      | 53.79%  |
| Intel + Nvidia     | 697       | 15.76%  |
| 1 x AMD            | 587       | 13.27%  |
| 1 x Nvidia         | 464       | 10.49%  |
| Intel + AMD        | 142       | 3.21%   |
| AMD + Nvidia       | 62        | 1.4%    |
| 2 x AMD            | 49        | 1.11%   |
| Other              | 22        | 0.5%    |
| 1 x SiS            | 7         | 0.16%   |
| 1 x Zhaoxin        | 4         | 0.09%   |
| 2 x Intel          | 2         | 0.05%   |
| 1 x VIA            | 2         | 0.05%   |
| 1 x S3 Graphics    | 2         | 0.05%   |
| Intel + 2 x Nvidia | 2         | 0.05%   |
| 2 x Nvidia         | 1         | 0.02%   |
| 1 x Neomagic       | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3840      | 86.35%  |
| Proprietary | 311       | 6.99%   |
| Unknown     | 296       | 6.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 3268      | 73.09%  |
| 0.01-0.5       | 653       | 14.61%  |
| 1.01-2.0       | 241       | 5.39%   |
| 0.51-1.0       | 126       | 2.82%   |
| 3.01-4.0       | 125       | 2.8%    |
| 5.01-6.0       | 27        | 0.6%    |
| 7.01-8.0       | 21        | 0.47%   |
| 2.01-3.0       | 8         | 0.18%   |
| More than 64.0 | 1         | 0.02%   |
| 8.01-16.0      | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 851       | 17.83%  |
| BOE                     | 624       | 13.08%  |
| Apple                   | 591       | 12.38%  |
| LG Display              | 575       | 12.05%  |
| Chimei Innolux          | 528       | 11.06%  |
| Samsung Electronics     | 385       | 8.07%   |
| Dell                    | 130       | 2.72%   |
| Lenovo                  | 113       | 2.37%   |
| Goldstar                | 97        | 2.03%   |
| Sharp                   | 96        | 2.01%   |
| Chi Mei Optoelectronics | 83        | 1.74%   |
| InfoVision              | 66        | 1.38%   |
| Hewlett-Packard         | 57        | 1.19%   |
| PANDA                   | 46        | 0.96%   |
| Philips                 | 43        | 0.9%    |
| BenQ                    | 43        | 0.9%    |
| AOC                     | 35        | 0.73%   |
| Iiyama                  | 33        | 0.69%   |
| HannStar                | 32        | 0.67%   |
| Ancor Communications    | 30        | 0.63%   |
| LG Philips              | 29        | 0.61%   |
| Acer                    | 29        | 0.61%   |
| CSO                     | 25        | 0.52%   |
| Unknown                 | 22        | 0.46%   |
| ViewSonic               | 18        | 0.38%   |
| Sony                    | 17        | 0.36%   |
| CPT                     | 15        | 0.31%   |
| Eizo                    | 14        | 0.29%   |
| Quanta Display          | 9         | 0.19%   |
| ASUSTek Computer        | 8         | 0.17%   |
| NEC Computers           | 7         | 0.15%   |
| Panasonic               | 6         | 0.13%   |
| MSI                     | 5         | 0.1%    |
| LGD                     | 5         | 0.1%    |
| Pixio                   | 4         | 0.08%   |
| InnoLux Display         | 4         | 0.08%   |
| AGO                     | 4         | 0.08%   |
| Toshiba                 | 3         | 0.06%   |
| TMX                     | 3         | 0.06%   |
| SLD                     | 3         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                 | 200       | 4.14%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 153       | 3.17%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                 | 52        | 1.08%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 44        | 0.91%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 43        | 0.89%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 41        | 0.85%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 41        | 0.85%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                 | 37        | 0.77%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 32        | 0.66%   |
| BOE LCD Monitor BOE06B3 1920x1080                                    | 29        | 0.6%    |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 28        | 0.58%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 27        | 0.56%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 26        | 0.54%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 24        | 0.5%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 24        | 0.5%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 23        | 0.48%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch | 22        | 0.46%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                 | 21        | 0.43%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 19        | 0.39%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 19        | 0.39%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch       | 18        | 0.37%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 16        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 16        | 0.33%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 16        | 0.33%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 16        | 0.33%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 15        | 0.31%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 15        | 0.31%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 15        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 14        | 0.29%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 14        | 0.29%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 14        | 0.29%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 13        | 0.27%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 12        | 0.25%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                | 12        | 0.25%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 12        | 0.25%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch        | 12        | 0.25%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 12        | 0.25%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 12        | 0.25%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 11        | 0.23%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch     | 11        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1699      | 37.69%  |
| 1366x768 (WXGA)    | 1267      | 28.11%  |
| 1280x800 (WXGA)    | 517       | 11.47%  |
| 1600x900 (HD+)     | 189       | 4.19%   |
| 1440x900 (WXGA+)   | 137       | 3.04%   |
| 3840x2160 (4K)     | 132       | 2.93%   |
| 2560x1440 (QHD)    | 96        | 2.13%   |
| 1920x1200 (WUXGA)  | 93        | 2.06%   |
| 1024x600           | 66        | 1.46%   |
| 1280x1024 (SXGA)   | 33        | 0.73%   |
| 2560x1600          | 32        | 0.71%   |
| 1680x1050 (WSXGA+) | 30        | 0.67%   |
| 2560x1080          | 26        | 0.58%   |
| 1360x768           | 21        | 0.47%   |
| 3840x2400          | 20        | 0.44%   |
| 2288x1287          | 19        | 0.42%   |
| 1024x768 (XGA)     | 18        | 0.4%    |
| 2880x1800          | 16        | 0.35%   |
| 3440x1440          | 15        | 0.33%   |
| 3200x1800 (QHD+)   | 10        | 0.22%   |
| 2160x1440          | 9         | 0.2%    |
| 1600x1200          | 7         | 0.16%   |
| 3840x1080          | 6         | 0.13%   |
| Unknown            | 6         | 0.13%   |
| 1400x1050          | 5         | 0.11%   |
| 3840x1100          | 3         | 0.07%   |
| 2256x1504          | 3         | 0.07%   |
| 2240x1400          | 3         | 0.07%   |
| 1280x720 (HD)      | 3         | 0.07%   |
| 1024x576           | 3         | 0.07%   |
| 3840x1200          | 2         | 0.04%   |
| 3072x1920          | 2         | 0.04%   |
| 2880x1920          | 2         | 0.04%   |
| 2304x1440          | 2         | 0.04%   |
| 1920x540           | 2         | 0.04%   |
| 1920x1280          | 2         | 0.04%   |
| 800x1280           | 1         | 0.02%   |
| 7680x2160          | 1         | 0.02%   |
| 640x480            | 1         | 0.02%   |
| 3840x1600          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1461      | 30.58%  |
| 13      | 1079      | 22.59%  |
| 14      | 605       | 12.66%  |
| 11      | 277       | 5.8%    |
| 17      | 262       | 5.48%   |
| 12      | 179       | 3.75%   |
| 24      | 164       | 3.43%   |
| 27      | 127       | 2.66%   |
| 23      | 118       | 2.47%   |
| 21      | 94        | 1.97%   |
| 10      | 66        | 1.38%   |
| 18      | 42        | 0.88%   |
| Unknown | 39        | 0.82%   |
| 34      | 35        | 0.73%   |
| 19      | 29        | 0.61%   |
| 16      | 28        | 0.59%   |
| 31      | 24        | 0.5%    |
| 142     | 19        | 0.4%    |
| 22      | 17        | 0.36%   |
| 25      | 15        | 0.31%   |
| 20      | 12        | 0.25%   |
| 72      | 10        | 0.21%   |
| 40      | 10        | 0.21%   |
| 32      | 9         | 0.19%   |
| 54      | 7         | 0.15%   |
| 8       | 7         | 0.15%   |
| 29      | 6         | 0.13%   |
| 84      | 5         | 0.1%    |
| 46      | 4         | 0.08%   |
| 28      | 4         | 0.08%   |
| 52      | 3         | 0.06%   |
| 49      | 3         | 0.06%   |
| 48      | 3         | 0.06%   |
| 43      | 3         | 0.06%   |
| 33      | 2         | 0.04%   |
| 26      | 2         | 0.04%   |
| 58      | 1         | 0.02%   |
| 55      | 1         | 0.02%   |
| 47      | 1         | 0.02%   |
| 41      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2406      | 50.81%  |
| 201-300        | 1243      | 26.25%  |
| 501-600        | 387       | 8.17%   |
| 351-400        | 306       | 6.46%   |
| 401-500        | 176       | 3.72%   |
| 601-700        | 52        | 1.1%    |
| 701-800        | 45        | 0.95%   |
| Unknown        | 39        | 0.82%   |
| 1001-1500      | 25        | 0.53%   |
| More than 2000 | 19        | 0.4%    |
| 1501-2000      | 15        | 0.32%   |
| 801-900        | 12        | 0.25%   |
| 101-200        | 8         | 0.17%   |
| 901-1000       | 2         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3224      | 75.59%  |
| 16/10   | 852       | 19.98%  |
| 21/9    | 38        | 0.89%   |
| 4/3     | 34        | 0.8%    |
| 5/4     | 33        | 0.77%   |
| 3/2     | 27        | 0.63%   |
| Unknown | 22        | 0.52%   |
| 1.00    | 19        | 0.45%   |
| 32/9    | 5         | 0.12%   |
| 2.65    | 4         | 0.09%   |
| 3.40    | 3         | 0.07%   |
| 3.20    | 2         | 0.05%   |
| 3.73    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1459      | 30.64%  |
| 81-90          | 1395      | 29.29%  |
| 201-250        | 301       | 6.32%   |
| 71-80          | 283       | 5.94%   |
| 51-60          | 280       | 5.88%   |
| 121-130        | 209       | 4.39%   |
| 61-70          | 173       | 3.63%   |
| 301-350        | 128       | 2.69%   |
| 251-300        | 77        | 1.62%   |
| 351-500        | 75        | 1.57%   |
| 41-50          | 66        | 1.39%   |
| 151-200        | 66        | 1.39%   |
| 141-150        | 58        | 1.22%   |
| More than 1000 | 48        | 1.01%   |
| Unknown        | 39        | 0.82%   |
| 131-140        | 33        | 0.69%   |
| 501-1000       | 24        | 0.5%    |
| 111-120        | 20        | 0.42%   |
| 91-100         | 20        | 0.42%   |
| 1-40           | 8         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1962      | 42.03%  |
| 101-120       | 1564      | 33.5%   |
| 51-100        | 669       | 14.33%  |
| 161-240       | 286       | 6.13%   |
| More than 240 | 91        | 1.95%   |
| 1-50          | 57        | 1.22%   |
| Unknown       | 39        | 0.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3505      | 77.68%  |
| 2     | 648       | 14.36%  |
| 0     | 286       | 6.34%   |
| 3     | 71        | 1.57%   |
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
| Intel                             | 2213      | 31.14%  |
| Realtek Semiconductor             | 1926      | 27.1%   |
| Qualcomm Atheros                  | 945       | 13.3%   |
| Broadcom                          | 657       | 9.24%   |
| Nvidia                            | 324       | 4.56%   |
| Broadcom Limited                  | 249       | 3.5%    |
| Marvell Technology Group          | 143       | 2.01%   |
| MediaTek                          | 64        | 0.9%    |
| Ralink                            | 56        | 0.79%   |
| ASIX Electronics                  | 45        | 0.63%   |
| TP-Link                           | 44        | 0.62%   |
| Dell                              | 35        | 0.49%   |
| Lenovo                            | 32        | 0.45%   |
| Samsung Electronics               | 31        | 0.44%   |
| Sierra Wireless                   | 29        | 0.41%   |
| JMicron Technology                | 26        | 0.37%   |
| Ericsson Business Mobile Networks | 24        | 0.34%   |
| Ralink Technology                 | 22        | 0.31%   |
| Qualcomm                          | 20        | 0.28%   |
| Xiaomi                            | 18        | 0.25%   |
| DisplayLink                       | 18        | 0.25%   |
| Huawei Technologies               | 17        | 0.24%   |
| Hewlett-Packard                   | 15        | 0.21%   |
| Fibocom                           | 13        | 0.18%   |
| Silicon Integrated Systems [SiS]  | 11        | 0.15%   |
| Qualcomm Atheros Communications   | 8         | 0.11%   |
| NetGear                           | 8         | 0.11%   |
| Cypress Semiconductor             | 8         | 0.11%   |
| ICS Advent                        | 6         | 0.08%   |
| Attansic Technology               | 6         | 0.08%   |
| ASUSTek Computer                  | 6         | 0.08%   |
| OPPO                              | 5         | 0.07%   |
| Microchip Technology              | 5         | 0.07%   |
| Apple                             | 5         | 0.07%   |
| AMD                               | 5         | 0.07%   |
| Motorola PCS                      | 4         | 0.06%   |
| Edimax Technology                 | 4         | 0.06%   |
| D-Link                            | 4         | 0.06%   |
| ULi Electronics                   | 3         | 0.04%   |
| U-Blox                            | 3         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 1173      | 13.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 341       | 4.03%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 315       | 3.73%   |
| Nvidia MCP79 Ethernet                                                                 | 314       | 3.71%   |
| Intel Wireless 7260                                                                   | 197       | 2.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 194       | 2.29%   |
| Intel Wireless 8265 / 8275                                                            | 178       | 2.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 178       | 2.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 174       | 2.06%   |
| Intel Wi-Fi 6 AX200                                                                   | 164       | 1.94%   |
| Intel Wireless 7265                                                                   | 163       | 1.93%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 160       | 1.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 144       | 1.7%    |
| Intel Wi-Fi 6 AX201                                                                   | 140       | 1.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 121       | 1.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 113       | 1.34%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 112       | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 110       | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 101       | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 99        | 1.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 95        | 1.12%   |
| Intel Wireless 8260                                                                   | 94        | 1.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 90        | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 77        | 0.91%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 69        | 0.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 67        | 0.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 61        | 0.72%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 59        | 0.7%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 58        | 0.69%   |
| Intel Ethernet Connection (4) I219-V                                                  | 58        | 0.69%   |
| Intel Wireless 3165                                                                   | 57        | 0.67%   |
| Intel Ethernet Connection I218-LM                                                     | 57        | 0.67%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 56        | 0.66%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 54        | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 52        | 0.62%   |
| Intel Ethernet Connection I219-LM                                                     | 51        | 0.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 50        | 0.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 46        | 0.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 45        | 0.53%   |
| Intel Wireless-AC 9260                                                                | 42        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2090      | 46.55%  |
| Qualcomm Atheros                      | 846       | 18.84%  |
| Broadcom                              | 552       | 12.29%  |
| Realtek Semiconductor                 | 524       | 11.67%  |
| Broadcom Limited                      | 212       | 4.72%   |
| Ralink                                | 56        | 1.25%   |
| MediaTek                              | 43        | 0.96%   |
| Sierra Wireless                       | 29        | 0.65%   |
| TP-Link                               | 25        | 0.56%   |
| Ralink Technology                     | 22        | 0.49%   |
| Dell                                  | 20        | 0.45%   |
| Fibocom                               | 12        | 0.27%   |
| Qualcomm                              | 9         | 0.2%    |
| Qualcomm Atheros Communications       | 8         | 0.18%   |
| NetGear                               | 8         | 0.18%   |
| ASUSTek Computer                      | 6         | 0.13%   |
| Ericsson Business Mobile Networks     | 4         | 0.09%   |
| Edimax Technology                     | 4         | 0.09%   |
| Hewlett-Packard                       | 3         | 0.07%   |
| Wilocity                              | 2         | 0.04%   |
| D-Link System                         | 2         | 0.04%   |
| D-Link                                | 2         | 0.04%   |
| Belkin Components                     | 2         | 0.04%   |
| 3Com                                  | 2         | 0.04%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| Z-Com                                 | 1         | 0.02%   |
| Winbond Electronics                   | 1         | 0.02%   |
| Quectel Wireless Solutions            | 1         | 0.02%   |
| Microsoft                             | 1         | 0.02%   |
| Cinterion                             | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 315       | 6.98%   |
| Intel Wireless 7260                                                                   | 197       | 4.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 194       | 4.3%    |
| Intel Wireless 8265 / 8275                                                            | 178       | 3.95%   |
| Intel Wi-Fi 6 AX200                                                                   | 164       | 3.63%   |
| Intel Wireless 7265                                                                   | 163       | 3.61%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 160       | 3.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 144       | 3.19%   |
| Intel Wi-Fi 6 AX201                                                                   | 140       | 3.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 121       | 2.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 113       | 2.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 112       | 2.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 110       | 2.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 101       | 2.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 99        | 2.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 95        | 2.11%   |
| Intel Wireless 8260                                                                   | 94        | 2.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 90        | 1.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 77        | 1.71%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 69        | 1.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 67        | 1.48%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 61        | 1.35%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 59        | 1.31%   |
| Intel Wireless 3165                                                                   | 57        | 1.26%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 54        | 1.2%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 46        | 1.02%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 45        | 1%      |
| Intel Wireless-AC 9260                                                                | 42        | 0.93%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 41        | 0.91%   |
| Intel Centrino Ultimate-N 6300                                                        | 39        | 0.86%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 38        | 0.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 37        | 0.82%   |
| Intel Wireless 3160                                                                   | 37        | 0.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 33        | 0.73%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 32        | 0.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 32        | 0.71%   |
| Intel Centrino Advanced-N 6200                                                        | 32        | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 30        | 0.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 30        | 0.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 30        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1732      | 45.8%   |
| Intel                            | 892       | 23.59%  |
| Nvidia                           | 324       | 8.57%   |
| Qualcomm Atheros                 | 205       | 5.42%   |
| Marvell Technology Group         | 143       | 3.78%   |
| Broadcom                         | 139       | 3.68%   |
| ASIX Electronics                 | 45        | 1.19%   |
| Broadcom Limited                 | 40        | 1.06%   |
| Lenovo                           | 32        | 0.85%   |
| Samsung Electronics              | 31        | 0.82%   |
| JMicron Technology               | 26        | 0.69%   |
| MediaTek                         | 21        | 0.56%   |
| TP-Link                          | 19        | 0.5%    |
| Xiaomi                           | 18        | 0.48%   |
| DisplayLink                      | 18        | 0.48%   |
| Silicon Integrated Systems [SiS] | 11        | 0.29%   |
| Huawei Technologies              | 11        | 0.29%   |
| Qualcomm                         | 10        | 0.26%   |
| Cypress Semiconductor            | 8         | 0.21%   |
| ICS Advent                       | 6         | 0.16%   |
| Attansic Technology              | 6         | 0.16%   |
| OPPO                             | 5         | 0.13%   |
| Microchip Technology             | 5         | 0.13%   |
| Apple                            | 5         | 0.13%   |
| Hewlett-Packard                  | 4         | 0.11%   |
| Spreadtrum Communications        | 3         | 0.08%   |
| Motorola PCS                     | 3         | 0.08%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.05%   |
| National Semiconductor           | 2         | 0.05%   |
| LG Electronics                   | 2         | 0.05%   |
| D-Link                           | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.03%   |
| VIA Technologies                 | 1         | 0.03%   |
| ULi Electronics                  | 1         | 0.03%   |
| MosChip Semiconductor            | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| HTC (High Tech Computer)         | 1         | 0.03%   |
| Google                           | 1         | 0.03%   |
| Foxconn / Hon Hai                | 1         | 0.03%   |
| Digitech Systems                 | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1173      | 30.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 341       | 8.92%   |
| Nvidia MCP79 Ethernet                                             | 314       | 8.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 178       | 4.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 174       | 4.55%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 58        | 1.52%   |
| Intel Ethernet Connection (4) I219-V                              | 58        | 1.52%   |
| Intel Ethernet Connection I218-LM                                 | 57        | 1.49%   |
| Intel Ethernet Connection (4) I219-LM                             | 56        | 1.47%   |
| Intel Ethernet Connection (3) I218-LM                             | 52        | 1.36%   |
| Intel Ethernet Connection I219-LM                                 | 51        | 1.33%   |
| Intel 82577LM Gigabit Network Connection                          | 42        | 1.1%    |
| Intel Ethernet Connection (6) I219-V                              | 39        | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 36        | 0.94%   |
| ASIX AX88179 Gigabit Ethernet                                     | 36        | 0.94%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 35        | 0.92%   |
| Intel 82567LM Gigabit Network Connection                          | 33        | 0.86%   |
| Intel Ethernet Connection I219-V                                  | 29        | 0.76%   |
| Intel Ethernet Connection (10) I219-V                             | 26        | 0.68%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 26        | 0.68%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 25        | 0.65%   |
| Intel Ethernet Connection (13) I219-V                             | 25        | 0.65%   |
| Intel Ethernet Connection I217-LM                                 | 24        | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 23        | 0.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 22        | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 19        | 0.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 19        | 0.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 18        | 0.47%   |
| Intel 82579V Gigabit Network Connection                           | 18        | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 17        | 0.44%   |
| Intel Ethernet Connection (6) I219-LM                             | 17        | 0.44%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 16        | 0.42%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 16        | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                             | 16        | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 15        | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 15        | 0.39%   |
| Intel 82566MM Gigabit Network Connection                          | 15        | 0.39%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 14        | 0.37%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 14        | 0.37%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 13        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4310      | 53.7%   |
| Ethernet | 3594      | 44.78%  |
| Modem    | 114       | 1.42%   |
| Unknown  | 8         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3356      | 72.08%  |
| Ethernet | 1300      | 27.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3247      | 73.41%  |
| 1     | 1063      | 24.03%  |
| 0     | 70        | 1.58%   |
| 3     | 41        | 0.93%   |
| 5     | 1         | 0.02%   |
| 4     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3782      | 84.57%  |
| Yes  | 690       | 15.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1575      | 44.08%  |
| Apple                           | 581       | 16.26%  |
| Qualcomm Atheros Communications | 322       | 9.01%   |
| Realtek Semiconductor           | 298       | 8.34%   |
| Broadcom                        | 177       | 4.95%   |
| Lite-On Technology              | 131       | 3.67%   |
| IMC Networks                    | 130       | 3.64%   |
| Foxconn / Hon Hai               | 88        | 2.46%   |
| Dell                            | 61        | 1.71%   |
| Cambridge Silicon Radio         | 43        | 1.2%    |
| Hewlett-Packard                 | 41        | 1.15%   |
| ASUSTek Computer                | 26        | 0.73%   |
| Realtek                         | 23        | 0.64%   |
| Toshiba                         | 22        | 0.62%   |
| Ralink                          | 19        | 0.53%   |
| Foxconn International           | 9         | 0.25%   |
| Alps Electric                   | 6         | 0.17%   |
| Ralink Technology               | 5         | 0.14%   |
| Taiyo Yuden                     | 3         | 0.08%   |
| MediaTek                        | 3         | 0.08%   |
| Unknown                         | 2         | 0.06%   |
| Fujitsu                         | 2         | 0.06%   |
| USI                             | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |
| Askey Computer                  | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 681       | 19.03%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 304       | 8.5%    |
| Intel AX201 Bluetooth                               | 286       | 7.99%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 260       | 7.27%   |
| Qualcomm Atheros  Bluetooth Device                  | 184       | 5.14%   |
| Realtek Bluetooth Radio                             | 181       | 5.06%   |
| Apple Bluetooth USB Host Controller                 | 160       | 4.47%   |
| Intel AX200 Bluetooth                               | 156       | 4.36%   |
| Realtek  Bluetooth 4.2 Adapter                      | 76        | 2.12%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 2.12%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 49        | 1.37%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 44        | 1.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 43        | 1.2%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 42        | 1.17%   |
| IMC Networks Bluetooth Radio                        | 39        | 1.09%   |
| Broadcom BCM2045B (BDC-2.1)                         | 39        | 1.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 37        | 1.03%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 35        | 0.98%   |
| Lite-On Bluetooth Device                            | 34        | 0.95%   |
| Intel Bluetooth Device                              | 34        | 0.95%   |
| Apple Bluetooth Host Controller                     | 34        | 0.95%   |
| IMC Networks Bluetooth Device                       | 33        | 0.92%   |
| Foxconn / Hon Hai Bluetooth Device                  | 32        | 0.89%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 31        | 0.87%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 30        | 0.84%   |
| Intel Wireless-AC 3168 Bluetooth                    | 29        | 0.81%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 29        | 0.81%   |
| Intel AX210 Bluetooth                               | 23        | 0.64%   |
| IMC Networks Wireless_Device                        | 22        | 0.61%   |
| Foxconn / Hon Hai Wireless_Device                   | 21        | 0.59%   |
| Dell DW375 Bluetooth Module                         | 21        | 0.59%   |
| Realtek 802.11ac WLAN Adapter                       | 19        | 0.53%   |
| Ralink RT3290 Bluetooth                             | 19        | 0.53%   |
| HP Broadcom 2070 Bluetooth Combo                    | 18        | 0.5%    |
| Realtek RTL8723B Bluetooth                          | 17        | 0.48%   |
| Lite-On Atheros AR3012 Bluetooth                    | 17        | 0.48%   |
| Dell BCM20702A0 Bluetooth Module                    | 17        | 0.48%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 16        | 0.45%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 13        | 0.36%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 13        | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3406      | 66.45%  |
| Nvidia                                       | 739       | 14.42%  |
| AMD                                          | 669       | 13.05%  |
| C-Media Electronics                          | 37        | 0.72%   |
| Logitech                                     | 28        | 0.55%   |
| Realtek Semiconductor                        | 26        | 0.51%   |
| Lenovo                                       | 26        | 0.51%   |
| Texas Instruments                            | 17        | 0.33%   |
| GN Netcom                                    | 16        | 0.31%   |
| Plantronics                                  | 15        | 0.29%   |
| Silicon Integrated Systems [SiS]             | 12        | 0.23%   |
| Hewlett-Packard                              | 12        | 0.23%   |
| Generalplus Technology                       | 10        | 0.2%    |
| ASUSTek Computer                             | 7         | 0.14%   |
| Creative Technology                          | 6         | 0.12%   |
| Focusrite-Novation                           | 5         | 0.1%    |
| Zoran Co. Personal Media Division (Nogatech) | 4         | 0.08%   |
| Zhaoxin                                      | 4         | 0.08%   |
| RODE Microphones                             | 4         | 0.08%   |
| Kingston Technology                          | 4         | 0.08%   |
| JMTek                                        | 4         | 0.08%   |
| Dell                                         | 4         | 0.08%   |
| ULi Electronics                              | 3         | 0.06%   |
| Sennheiser Communications                    | 3         | 0.06%   |
| Razer USA                                    | 3         | 0.06%   |
| Microsoft                                    | 3         | 0.06%   |
| BEHRINGER International                      | 3         | 0.06%   |
| XMOS                                         | 2         | 0.04%   |
| VIA Technologies                             | 2         | 0.04%   |
| SteelSeries ApS                              | 2         | 0.04%   |
| SAVITECH                                     | 2         | 0.04%   |
| M-Audio                                      | 2         | 0.04%   |
| ESS Technology                               | 2         | 0.04%   |
| Conexant Systems                             | 2         | 0.04%   |
| CMX Systems                                  | 2         | 0.04%   |
| Blue Microphones                             | 2         | 0.04%   |
| Beyerdynamic                                 | 2         | 0.04%   |
| Apple                                        | 2         | 0.04%   |
| Yamaha                                       | 1         | 0.02%   |
| Veho                                         | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 509       | 8.23%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 367       | 5.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 342       | 5.53%   |
| Nvidia MCP79 High Definition Audio                                                                | 316       | 5.11%   |
| Intel Broadwell-U Audio Controller                                                                | 280       | 4.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 276       | 4.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 215       | 3.48%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 199       | 3.22%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 183       | 2.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 168       | 2.72%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 153       | 2.47%   |
| Intel Cannon Lake PCH cAVS                                                                        | 153       | 2.47%   |
| Intel 8 Series HD Audio Controller                                                                | 153       | 2.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 147       | 2.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 144       | 2.33%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 134       | 2.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 127       | 2.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 126       | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 112       | 1.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 99        | 1.6%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 93        | 1.5%    |
| AMD FCH Azalia Controller                                                                         | 89        | 1.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 86        | 1.39%   |
| AMD Kabini HDMI/DP Audio                                                                          | 85        | 1.37%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 79        | 1.28%   |
| Intel Comet Lake PCH cAVS                                                                         | 78        | 1.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 78        | 1.26%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 61        | 0.99%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 59        | 0.95%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 56        | 0.91%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 49        | 0.79%   |
| Intel CM238 HD Audio Controller                                                                   | 49        | 0.79%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 47        | 0.76%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 44        | 0.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 41        | 0.66%   |
| AMD High Definition Audio Controller                                                              | 40        | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 39        | 0.63%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 38        | 0.61%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 31        | 0.5%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 30        | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 1212      | 28.67%  |
| Samsung Electronics | 1120      | 26.5%   |
| Micron Technology   | 438       | 10.36%  |
| Kingston            | 290       | 6.86%   |
| Unknown             | 281       | 6.65%   |
| Crucial             | 209       | 4.94%   |
| Elpida              | 122       | 2.89%   |
| A-DATA Technology   | 89        | 2.11%   |
| Ramaxel Technology  | 75        | 1.77%   |
| Nanya Technology    | 47        | 1.11%   |
| Corsair             | 40        | 0.95%   |
| Unknown             | 38        | 0.9%    |
| Smart               | 34        | 0.8%    |
| Unknown (ABCD)      | 33        | 0.78%   |
| GOODRAM             | 21        | 0.5%    |
| G.Skill             | 19        | 0.45%   |
| Transcend           | 18        | 0.43%   |
| Team                | 16        | 0.38%   |
| Teikon              | 10        | 0.24%   |
| 48spaces            | 8         | 0.19%   |
| Silicon Power       | 7         | 0.17%   |
| Patriot             | 7         | 0.17%   |
| ASint Technology    | 7         | 0.17%   |
| Apacer              | 7         | 0.17%   |
| Smart Brazil        | 6         | 0.14%   |
| Qimonda             | 4         | 0.09%   |
| PNY                 | 4         | 0.09%   |
| AMD                 | 4         | 0.09%   |
| Wilk                | 3         | 0.07%   |
| Neo Forza           | 3         | 0.07%   |
| Goldkey             | 3         | 0.07%   |
| Avant               | 3         | 0.07%   |
| Unknown (89F7)      | 2         | 0.05%   |
| Unifosa             | 2         | 0.05%   |
| TEXTORM             | 2         | 0.05%   |
| Shenzhen WODPOSIT   | 2         | 0.05%   |
| SHARETRONIC         | 2         | 0.05%   |
| PUSKILL             | 2         | 0.05%   |
| Kllisre             | 2         | 0.05%   |
| Infineon            | 2         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 258       | 5.8%    |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 1.53%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 66        | 1.48%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 63        | 1.42%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 44        | 0.99%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 43        | 0.97%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 41        | 0.92%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 39        | 0.88%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 39        | 0.88%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 39        | 0.88%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 38        | 0.85%   |
| Unknown                                                          | 38        | 0.85%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 37        | 0.83%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 37        | 0.83%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 33        | 0.74%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 33        | 0.74%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 30        | 0.67%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 29        | 0.65%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 29        | 0.65%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.65%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 29        | 0.65%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 27        | 0.61%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 25        | 0.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 25        | 0.56%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 25        | 0.56%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 23        | 0.52%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 23        | 0.52%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 0.52%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 23        | 0.52%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 22        | 0.49%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 22        | 0.49%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 22        | 0.49%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 0.45%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 20        | 0.45%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 19        | 0.43%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 19        | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 18        | 0.4%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 18        | 0.4%    |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 17        | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1435      | 39.11%  |
| DDR3    | 1250      | 34.07%  |
| DDR2    | 540       | 14.72%  |
| LPDDR4  | 133       | 3.62%   |
| LPDDR3  | 127       | 3.46%   |
| SDRAM   | 81        | 2.21%   |
| DDR     | 41        | 1.12%   |
| Unknown | 21        | 0.57%   |
| DDR5    | 17        | 0.46%   |
| LPDDR5  | 14        | 0.38%   |
| DRAM    | 9         | 0.25%   |
| RAM     | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 3335      | 90.77%  |
| Row Of Chips | 240       | 6.53%   |
| Unknown      | 56        | 1.52%   |
| Chip         | 30        | 0.82%   |
| DIMM         | 13        | 0.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1211      | 30.46%  |
| 4096  | 1068      | 26.86%  |
| 2048  | 602       | 15.14%  |
| 1024  | 534       | 13.43%  |
| 16384 | 417       | 10.49%  |
| 32768 | 82        | 2.06%   |
| 512   | 43        | 1.08%   |
| 256   | 16        | 0.4%    |
| 128   | 2         | 0.05%   |
| 384   | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 956       | 24.34%  |
| 2667    | 693       | 17.65%  |
| 3200    | 553       | 14.08%  |
| 800     | 336       | 8.56%   |
| 2400    | 244       | 6.21%   |
| 667     | 175       | 4.46%   |
| 2133    | 168       | 4.28%   |
| 1334    | 159       | 4.05%   |
| 1333    | 127       | 3.23%   |
| Unknown | 100       | 2.55%   |
| 1067    | 55        | 1.4%    |
| 4267    | 51        | 1.3%    |
| 1867    | 43        | 1.09%   |
| 3266    | 37        | 0.94%   |
| 4199    | 29        | 0.74%   |
| 1066    | 22        | 0.56%   |
| 533     | 21        | 0.53%   |
| 4800    | 20        | 0.51%   |
| 975     | 19        | 0.48%   |
| 2048    | 18        | 0.46%   |
| 8400    | 15        | 0.38%   |
| 6400    | 13        | 0.33%   |
| 4266    | 11        | 0.28%   |
| 400     | 11        | 0.28%   |
| 333     | 9         | 0.23%   |
| 266     | 8         | 0.2%    |
| 1866    | 7         | 0.18%   |
| 3733    | 6         | 0.15%   |
| 933     | 4         | 0.1%    |
| 2933    | 3         | 0.08%   |
| 2666    | 3         | 0.08%   |
| 1776    | 2         | 0.05%   |
| 1639    | 2         | 0.05%   |
| 3000    | 1         | 0.03%   |
| 2134    | 1         | 0.03%   |
| 1596    | 1         | 0.03%   |
| 200     | 1         | 0.03%   |
| 166     | 1         | 0.03%   |
| 133     | 1         | 0.03%   |
| 100     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 37.04%  |
| Xerox               | 4         | 14.81%  |
| Canon               | 3         | 11.11%  |
| Brother Industries  | 3         | 11.11%  |
| Samsung Electronics | 2         | 7.41%   |
| Kyocera             | 2         | 7.41%   |
| Xiaomi              | 1         | 3.7%    |
| STMicroelectronics  | 1         | 3.7%    |
| Pantum              | 1         | 3.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Xerox B205                                                | 4         | 14.29%  |
| Xiaomi MiMouse 2                                          | 1         | 3.57%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.57%   |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 3.57%   |
| Samsung CLX-3300 Series                                   | 1         | 3.57%   |
| Pantum P2500W series                                      | 1         | 3.57%   |
| Kyocera FS-1120MFP                                        | 1         | 3.57%   |
| Kyocera ECOSYS P2335d                                     | 1         | 3.57%   |
| HP OfficeJet 3830 series                                  | 1         | 3.57%   |
| HP LaserJet P1102                                         | 1         | 3.57%   |
| HP LaserJet 1200                                          | 1         | 3.57%   |
| HP LaserJet 1160 series                                   | 1         | 3.57%   |
| HP LaserJet 1022                                          | 1         | 3.57%   |
| HP LaserJet 1020                                          | 1         | 3.57%   |
| HP Ink Tank 110 series                                    | 1         | 3.57%   |
| HP EWS UPD                                                | 1         | 3.57%   |
| HP DeskJet 2620 All-in-One Printer                        | 1         | 3.57%   |
| HP Deskjet 2540 series                                    | 1         | 3.57%   |
| HP DeskJet 2130 series                                    | 1         | 3.57%   |
| Canon PIXMA MX920 Series                                  | 1         | 3.57%   |
| Canon LBP3010/LBP3018/LBP3050                             | 1         | 3.57%   |
| Canon G3010 series                                        | 1         | 3.57%   |
| Brother PT-9500PC                                         | 1         | 3.57%   |
| Brother MFC-L2707DW                                       | 1         | 3.57%   |
| Brother HL-L2340D series                                  | 1         | 3.57%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 45.45%  |
| Seiko Epson     | 4         | 36.36%  |
| Mustek Systems  | 1         | 9.09%   |
| Hewlett-Packard | 1         | 9.09%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 120                           | 2         | 18.18%  |
| Seiko Epson GT-9800F [Perfection 3200]            | 1         | 9.09%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]     | 1         | 9.09%   |
| Seiko Epson GT-7700U [Perfection 1240U]           | 1         | 9.09%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 9.09%   |
| Mustek Systems SNAPSCAN e22                       | 1         | 9.09%   |
| HP Scanjet 200                                    | 1         | 9.09%   |
| Canon CanoScan LIDE 25                            | 1         | 9.09%   |
| Canon CanoScan LiDE 220                           | 1         | 9.09%   |
| Canon CanoScan LiDE 110                           | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 825       | 24.09%  |
| IMC Networks                           | 397       | 11.59%  |
| Acer                                   | 323       | 9.43%   |
| Realtek Semiconductor                  | 289       | 8.44%   |
| Microdia                               | 283       | 8.27%   |
| Quanta                                 | 254       | 7.42%   |
| Sunplus Innovation Technology          | 180       | 5.26%   |
| Suyin                                  | 110       | 3.21%   |
| Cheng Uei Precision Industry (Foxlink) | 104       | 3.04%   |
| Lite-On Technology                     | 83        | 2.42%   |
| Syntek                                 | 74        | 2.16%   |
| Apple                                  | 54        | 1.58%   |
| Luxvisions Innotech Limited            | 50        | 1.46%   |
| Logitech                               | 49        | 1.43%   |
| Silicon Motion                         | 47        | 1.37%   |
| Alcor Micro                            | 38        | 1.11%   |
| Lenovo                                 | 31        | 0.91%   |
| Ricoh                                  | 30        | 0.88%   |
| Z-Star Microelectronics                | 19        | 0.55%   |
| Primax Electronics                     | 18        | 0.53%   |
| Sonix Technology                       | 14        | 0.41%   |
| Samsung Electronics                    | 14        | 0.41%   |
| DLEQNA19IFK6G2                         | 14        | 0.41%   |
| ALi                                    | 10        | 0.29%   |
| Importek                               | 9         | 0.26%   |
| Genesys Logic                          | 8         | 0.23%   |
| Bison Electronics                      | 8         | 0.23%   |
| icSpring                               | 7         | 0.2%    |
| SunplusIT                              | 6         | 0.18%   |
| Intel                                  | 5         | 0.15%   |
| Y Media                                | 4         | 0.12%   |
| OmniVision Technologies                | 4         | 0.12%   |
| MacroSilicon                           | 4         | 0.12%   |
| Sunplus Technology                     | 3         | 0.09%   |
| Pixart Imaging                         | 3         | 0.09%   |
| Microsoft                              | 3         | 0.09%   |
| Generalplus Technology                 | 3         | 0.09%   |
| GEMBIRD                                | 3         | 0.09%   |
| ARC International                      | 3         | 0.09%   |
| Unknown                                | 2         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 227       | 6.59%   |
| Microdia Integrated_Webcam_HD            | 132       | 3.83%   |
| IMC Networks Integrated Camera           | 131       | 3.8%    |
| Realtek Integrated_Webcam_HD             | 109       | 3.16%   |
| IMC Networks USB2.0 HD UVC WebCam        | 90        | 2.61%   |
| Acer Integrated Camera                   | 84        | 2.44%   |
| Chicony HD Webcam                        | 79        | 2.29%   |
| Quanta Chromebook HD Camera              | 68        | 1.97%   |
| Sunplus Integrated_Webcam_HD             | 65        | 1.89%   |
| Acer BisonCam, NB Pro                    | 59        | 1.71%   |
| Chicony HP HD Camera                     | 45        | 1.31%   |
| Chicony USB2.0 HD UVC WebCam             | 41        | 1.19%   |
| Syntek Integrated Camera                 | 39        | 1.13%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 36        | 1.04%   |
| Quanta HP TrueVision HD Camera           | 34        | 0.99%   |
| Lite-On Integrated Camera                | 33        | 0.96%   |
| Microdia Integrated Webcam               | 32        | 0.93%   |
| Acer SunplusIT Integrated Camera         | 31        | 0.9%    |
| Quanta HD User Facing                    | 29        | 0.84%   |
| Acer Lenovo EasyCamera                   | 28        | 0.81%   |
| Quanta HP HD Camera                      | 25        | 0.73%   |
| Chicony Integrated Camera (1280x720@30)  | 25        | 0.73%   |
| Chicony HP TrueVision HD Camera          | 24        | 0.7%    |
| Quanta VGA WebCam                        | 23        | 0.67%   |
| Sunplus HD WebCam                        | 22        | 0.64%   |
| Realtek USB Camera                       | 22        | 0.64%   |
| Chicony HD User Facing                   | 22        | 0.64%   |
| Lite-On HP HD Camera                     | 21        | 0.61%   |
| Chicony EasyCamera                       | 21        | 0.61%   |
| Acer Lenovo Integrated Webcam            | 21        | 0.61%   |
| Apple iPhone 5/5C/5S/6/SE                | 20        | 0.58%   |
| Realtek USB2.0 HD UVC WebCam             | 19        | 0.55%   |
| Realtek Integrated Webcam                | 19        | 0.55%   |
| Chicony USB2.0 Camera                    | 19        | 0.55%   |
| Chicony HP TrueVision HD                 | 19        | 0.55%   |
| Chicony Lenovo EasyCamera                | 18        | 0.52%   |
| Acer BisonCam,NB Pro                     | 18        | 0.52%   |
| Suyin HP TrueVision HD                   | 17        | 0.49%   |
| Luxvisions Innotech Limited HP HD Camera | 17        | 0.49%   |
| Acer HD Webcam                           | 17        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 240       | 32.88%  |
| Synaptics                          | 224       | 30.68%  |
| Shenzhen Goodix Technology         | 101       | 13.84%  |
| AuthenTec                          | 44        | 6.03%   |
| Upek                               | 43        | 5.89%   |
| Elan Microelectronics              | 36        | 4.93%   |
| LighTuning Technology              | 22        | 3.01%   |
| STMicroelectronics                 | 16        | 2.19%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.27%   |
| Samsung Electronics                | 1         | 0.14%   |
| Microsoft                          | 1         | 0.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 101       | 13.84%  |
| Shenzhen Goodix  FingerPrint Device                                        | 60        | 8.22%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 55        | 7.53%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 48        | 6.58%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 44        | 6.03%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 39        | 5.34%   |
| Unknown                                                                    | 37        | 5.07%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 29        | 3.97%   |
| Shenzhen Goodix Fingerprint Reader                                         | 23        | 3.15%   |
| Elan ELAN:Fingerprint                                                      | 23        | 3.15%   |
| Shenzhen Goodix FingerPrint                                                | 18        | 2.47%   |
| AuthenTec AES2810                                                          | 18        | 2.47%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 17        | 2.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 17        | 2.33%   |
| Validity Sensors Synaptics WBDI                                            | 16        | 2.19%   |
| STMicroelectronics Fingerprint Reader                                      | 14        | 1.92%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 1.92%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 1.92%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 13        | 1.78%   |
| Elan ELAN:ARM-M4                                                           | 13        | 1.78%   |
| Validity Sensors VFS491                                                    | 12        | 1.64%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 1.64%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 1.37%   |
| Validity Sensors VFS Fingerprint sensor                                    | 9         | 1.23%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 1.23%   |
| Synaptics  WBDI                                                            | 9         | 1.23%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 1.1%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 0.82%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 0.68%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 0.68%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.55%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.55%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.55%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.41%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.27%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.27%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.27%   |
| STMicroelectronics TouchChipÂ Fingerprint Reader                          | 2         | 0.27%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.27%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 141       | 37.6%   |
| Alcor Micro               | 135       | 36%     |
| O2 Micro                  | 27        | 7.2%    |
| Lenovo                    | 27        | 7.2%    |
| Upek                      | 26        | 6.93%   |
| Gemalto (was Gemplus)     | 4         | 1.07%   |
| Yubico.com                | 3         | 0.8%    |
| Clay Logic                | 3         | 0.8%    |
| SCM Microsystems          | 2         | 0.53%   |
| Aladdin Knowledge Systems | 2         | 0.53%   |
| Advanced Card Systems     | 2         | 0.53%   |
| OmniKey                   | 1         | 0.27%   |
| Cherry                    | 1         | 0.27%   |
| C3PO                      | 1         | 0.27%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 133       | 35.47%  |
| Broadcom BCM5880 Secure Applications Processor                               | 45        | 12%     |
| Broadcom 5880                                                                | 37        | 9.87%   |
| Broadcom 58200                                                               | 35        | 9.33%   |
| Lenovo Integrated Smart Card Reader                                          | 27        | 7.2%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 26        | 6.93%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 6.13%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 22        | 5.87%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.07%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 3         | 0.8%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.53%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.53%   |
| Clay Logic Nitrokey Start                                                    | 2         | 0.53%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.53%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.53%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.53%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.27%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.27%   |
| OmniKey CardMan 4321                                                         | 1         | 0.27%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.27%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.27%   |
| C3PO LTC31v2                                                                 | 1         | 0.27%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.27%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.27%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2602      | 57.78%  |
| 1     | 1431      | 31.78%  |
| 2     | 366       | 8.13%   |
| 3     | 88        | 1.95%   |
| 4     | 9         | 0.2%    |
| 5     | 6         | 0.13%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 726       | 30.65%  |
| Graphics card            | 588       | 24.82%  |
| Chipcard                 | 343       | 14.48%  |
| Multimedia controller    | 236       | 9.96%   |
| Net/wireless             | 206       | 8.7%    |
| Bluetooth                | 57        | 2.41%   |
| Camera                   | 46        | 1.94%   |
| Card reader              | 38        | 1.6%    |
| Storage                  | 34        | 1.44%   |
| Communication controller | 33        | 1.39%   |
| Sound                    | 18        | 0.76%   |
| Net/ethernet             | 17        | 0.72%   |
| Network                  | 8         | 0.34%   |
| Modem                    | 7         | 0.3%    |
| Flash memory             | 5         | 0.21%   |
| Unassigned class         | 2         | 0.08%   |
| Firewire controller      | 2         | 0.08%   |
| Wireless                 | 1         | 0.04%   |
| Tv card                  | 1         | 0.04%   |
| Storage/ide              | 1         | 0.04%   |

