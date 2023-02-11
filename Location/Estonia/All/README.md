Linux in Estonia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Estonia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Estonia/Desktop/README.md) and [notebooks](/Location/Estonia/Notebook/README.md).

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

Total: 389

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Packard Be... | EasyNote TK87               | Notebook    | [82ce911f26](https://linux-hardware.org/?probe=82ce911f26) | Jan 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [2141789e3a](https://linux-hardware.org/?probe=2141789e3a) | Jan 14, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [f1c4c8b89e](https://linux-hardware.org/?probe=f1c4c8b89e) | Jan 13, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8674044a95](https://linux-hardware.org/?probe=8674044a95) | Jan 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [ff12fe840d](https://linux-hardware.org/?probe=ff12fe840d) | Jan 12, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [146f307b8e](https://linux-hardware.org/?probe=146f307b8e) | Jan 10, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [aa21c2b75f](https://linux-hardware.org/?probe=aa21c2b75f) | Jan 06, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [efa2d6986f](https://linux-hardware.org/?probe=efa2d6986f) | Dec 28, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [4a85ebbc33](https://linux-hardware.org/?probe=4a85ebbc33) | Dec 26, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [70436ae3c3](https://linux-hardware.org/?probe=70436ae3c3) | Dec 15, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [4c5bac90eb](https://linux-hardware.org/?probe=4c5bac90eb) | Dec 15, 2022 |
| ASRock        | Z490M Pro4                  | Desktop     | [2ace77f72c](https://linux-hardware.org/?probe=2ace77f72c) | Dec 14, 2022 |
| ASRock        | Z490M Pro4                  | Desktop     | [0b91c8c70f](https://linux-hardware.org/?probe=0b91c8c70f) | Dec 14, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [d8b614d1ca](https://linux-hardware.org/?probe=d8b614d1ca) | Dec 12, 2022 |
| MSI           | MAG B660M BAZOOKA DDR4      | Desktop     | [280f28a486](https://linux-hardware.org/?probe=280f28a486) | Dec 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1f904e68af](https://linux-hardware.org/?probe=1f904e68af) | Nov 29, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [6f3bf3fe46](https://linux-hardware.org/?probe=6f3bf3fe46) | Nov 28, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [e4dc6e5cd9](https://linux-hardware.org/?probe=e4dc6e5cd9) | Nov 27, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | Notebook    | [b792955af6](https://linux-hardware.org/?probe=b792955af6) | Nov 27, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | Notebook    | [033e206fab](https://linux-hardware.org/?probe=033e206fab) | Nov 25, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [9154fdbc9e](https://linux-hardware.org/?probe=9154fdbc9e) | Nov 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [0e77de9dba](https://linux-hardware.org/?probe=0e77de9dba) | Nov 20, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [96d82e20c4](https://linux-hardware.org/?probe=96d82e20c4) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [f5fd517d69](https://linux-hardware.org/?probe=f5fd517d69) | Nov 19, 2022 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [b8dae15ebf](https://linux-hardware.org/?probe=b8dae15ebf) | Nov 09, 2022 |
| Alienware     | 17                          | Notebook    | [91358a0bec](https://linux-hardware.org/?probe=91358a0bec) | Nov 09, 2022 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [c479fc2cea](https://linux-hardware.org/?probe=c479fc2cea) | Nov 06, 2022 |
| HP            | Unknown                     | Notebook    | [aa28b92716](https://linux-hardware.org/?probe=aa28b92716) | Nov 06, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | Notebook    | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | Notebook    | [36d7199821](https://linux-hardware.org/?probe=36d7199821) | Nov 01, 2022 |
| ASUSTek       | M4A78                       | Desktop     | [8eb1316a14](https://linux-hardware.org/?probe=8eb1316a14) | Oct 31, 2022 |
| ASUSTek       | M4A78                       | Desktop     | [81374a561c](https://linux-hardware.org/?probe=81374a561c) | Oct 31, 2022 |
| ASUSTek       | M4A78                       | Desktop     | [d88d101a3c](https://linux-hardware.org/?probe=d88d101a3c) | Oct 29, 2022 |
| MSI           | GL72 6QD                    | Notebook    | [2f7c223f5a](https://linux-hardware.org/?probe=2f7c223f5a) | Oct 29, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [5405caf9dc](https://linux-hardware.org/?probe=5405caf9dc) | Oct 28, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [5548027da3](https://linux-hardware.org/?probe=5548027da3) | Oct 27, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [26d539c606](https://linux-hardware.org/?probe=26d539c606) | Oct 26, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [dbb72f4c00](https://linux-hardware.org/?probe=dbb72f4c00) | Oct 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [8b459ac79b](https://linux-hardware.org/?probe=8b459ac79b) | Oct 20, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| ASRock        | B460 Steel Legend           | Desktop     | [ca98840e23](https://linux-hardware.org/?probe=ca98840e23) | Oct 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7a1b08d912](https://linux-hardware.org/?probe=7a1b08d912) | Oct 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3f808f36a0](https://linux-hardware.org/?probe=3f808f36a0) | Oct 13, 2022 |
| Unknown       | Seagate Personal Cloud (... | Desktop     | [40ea197650](https://linux-hardware.org/?probe=40ea197650) | Oct 09, 2022 |
| Dell          | Latitude 7390               | Notebook    | [268add52b3](https://linux-hardware.org/?probe=268add52b3) | Sep 19, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9a7d178f1b](https://linux-hardware.org/?probe=9a7d178f1b) | Sep 15, 2022 |
| ASUSTek       | 1225C                       | Notebook    | [91f049c977](https://linux-hardware.org/?probe=91f049c977) | Sep 09, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [d805aa67b2](https://linux-hardware.org/?probe=d805aa67b2) | Sep 09, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [f6c6b627f7](https://linux-hardware.org/?probe=f6c6b627f7) | Aug 28, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [7332174749](https://linux-hardware.org/?probe=7332174749) | Aug 24, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [8c56960243](https://linux-hardware.org/?probe=8c56960243) | Aug 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [ced35212a7](https://linux-hardware.org/?probe=ced35212a7) | Aug 07, 2022 |
| MSI           | MAG B460M BAZOOKA           | Desktop     | [5dae076f42](https://linux-hardware.org/?probe=5dae076f42) | Jul 27, 2022 |
| ECS           | G41T-M7                     | Desktop     | [a531a754a8](https://linux-hardware.org/?probe=a531a754a8) | Jul 23, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| HP            | 3646h                       | Desktop     | [88b38da161](https://linux-hardware.org/?probe=88b38da161) | Jul 11, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [cdb4149eba](https://linux-hardware.org/?probe=cdb4149eba) | Jun 27, 2022 |
| MSI           | Z77A-G41                    | Desktop     | [d0f55f3c0b](https://linux-hardware.org/?probe=d0f55f3c0b) | Jun 22, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [d8f9374e6c](https://linux-hardware.org/?probe=d8f9374e6c) | Jun 22, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [00495646c1](https://linux-hardware.org/?probe=00495646c1) | Jun 22, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [208e447fe1](https://linux-hardware.org/?probe=208e447fe1) | Jun 17, 2022 |
| ASUSTek       | E502NA                      | Notebook    | [d65dd8fc52](https://linux-hardware.org/?probe=d65dd8fc52) | Jun 09, 2022 |
| ASUSTek       | E502NA                      | Notebook    | [d3d64dcb5b](https://linux-hardware.org/?probe=d3d64dcb5b) | Jun 09, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [a068a18649](https://linux-hardware.org/?probe=a068a18649) | Jun 08, 2022 |
| Dell          | 088DT1 A00                  | Desktop     | [b585cb1f70](https://linux-hardware.org/?probe=b585cb1f70) | Jun 07, 2022 |
| HP            | Presario CQ57               | Notebook    | [9f87592293](https://linux-hardware.org/?probe=9f87592293) | Jun 02, 2022 |
| Intel         | DP67BG AAG10491-305         | Desktop     | [714722d24b](https://linux-hardware.org/?probe=714722d24b) | Jun 01, 2022 |
| Intel         | DP67BG AAG10491-305         | Desktop     | [966ab11802](https://linux-hardware.org/?probe=966ab11802) | May 31, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [49223fe44b](https://linux-hardware.org/?probe=49223fe44b) | May 21, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [40cb336486](https://linux-hardware.org/?probe=40cb336486) | May 21, 2022 |
| Gigabyte      | H55M-S2                     | Desktop     | [4d68acc78c](https://linux-hardware.org/?probe=4d68acc78c) | May 18, 2022 |
| Dell          | Latitude 5520               | Notebook    | [320ed1c4fc](https://linux-hardware.org/?probe=320ed1c4fc) | May 17, 2022 |
| Dell          | Latitude 5520               | Notebook    | [18823f33fb](https://linux-hardware.org/?probe=18823f33fb) | May 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5107890ffd](https://linux-hardware.org/?probe=5107890ffd) | May 15, 2022 |
| Lenovo        | ThinkCentre M58 7360WQK     | Desktop     | [9002375046](https://linux-hardware.org/?probe=9002375046) | May 13, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [0773b6244e](https://linux-hardware.org/?probe=0773b6244e) | May 11, 2022 |
| Gigabyte      | B560 HD3                    | Desktop     | [34fd3f60c4](https://linux-hardware.org/?probe=34fd3f60c4) | May 11, 2022 |
| Lenovo        | ThinkPad T490s 20NX000AM... | Notebook    | [f07b38c5f9](https://linux-hardware.org/?probe=f07b38c5f9) | May 10, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [92637583b8](https://linux-hardware.org/?probe=92637583b8) | May 10, 2022 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [aafa7cb1cb](https://linux-hardware.org/?probe=aafa7cb1cb) | May 07, 2022 |
| Dell          | Precision 7540              | Notebook    | [8b1b7dd8da](https://linux-hardware.org/?probe=8b1b7dd8da) | Apr 30, 2022 |
| Lenovo        | ThinkPad T520 4243RT9       | Notebook    | [a10fb9fe10](https://linux-hardware.org/?probe=a10fb9fe10) | Apr 23, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [b963507390](https://linux-hardware.org/?probe=b963507390) | Apr 19, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [fff8ad361e](https://linux-hardware.org/?probe=fff8ad361e) | Apr 19, 2022 |
| Lenovo        | ThinkPad T520 4243RT9       | Notebook    | [d948d987b4](https://linux-hardware.org/?probe=d948d987b4) | Apr 18, 2022 |
| Framework     | Laptop                      | Notebook    | [d4a02dfec9](https://linux-hardware.org/?probe=d4a02dfec9) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | Notebook    | [8444b44333](https://linux-hardware.org/?probe=8444b44333) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5S84400    | Notebook    | [69e1c25b4c](https://linux-hardware.org/?probe=69e1c25b4c) | Apr 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [8af8994f80](https://linux-hardware.org/?probe=8af8994f80) | Apr 02, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [ccf4457b51](https://linux-hardware.org/?probe=ccf4457b51) | Mar 28, 2022 |
| HP            | 18E9                        | Desktop     | [5a223b8722](https://linux-hardware.org/?probe=5a223b8722) | Mar 23, 2022 |
| Dell          | Latitude 5520               | Notebook    | [a8e30b61c6](https://linux-hardware.org/?probe=a8e30b61c6) | Mar 21, 2022 |
| Dell          | Latitude 5520               | Notebook    | [02b408b5f6](https://linux-hardware.org/?probe=02b408b5f6) | Mar 21, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [ee3693d6a7](https://linux-hardware.org/?probe=ee3693d6a7) | Mar 09, 2022 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [7fb04e6c7d](https://linux-hardware.org/?probe=7fb04e6c7d) | Mar 03, 2022 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [0f27bdf5a8](https://linux-hardware.org/?probe=0f27bdf5a8) | Mar 02, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [d34e3c79a0](https://linux-hardware.org/?probe=d34e3c79a0) | Mar 01, 2022 |
| Lenovo        | ThinkPad X220 429136G       | Notebook    | [324d66c0fc](https://linux-hardware.org/?probe=324d66c0fc) | Feb 23, 2022 |
| ECS           | G41T-M7                     | Desktop     | [c4aca5bc12](https://linux-hardware.org/?probe=c4aca5bc12) | Feb 20, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [5f3cd9e8d5](https://linux-hardware.org/?probe=5f3cd9e8d5) | Feb 16, 2022 |
| MSI           | B150M PRO-VD                | Desktop     | [b46943492e](https://linux-hardware.org/?probe=b46943492e) | Feb 15, 2022 |
| HP            | 304Ah                       | Desktop     | [078b605c39](https://linux-hardware.org/?probe=078b605c39) | Feb 09, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [96f97ed2d6](https://linux-hardware.org/?probe=96f97ed2d6) | Jan 23, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [c9b246d9a8](https://linux-hardware.org/?probe=c9b246d9a8) | Jan 12, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [49234f883d](https://linux-hardware.org/?probe=49234f883d) | Jan 12, 2022 |
| Huanan        | X79 V2.47                   | Desktop     | [a27e7cdbef](https://linux-hardware.org/?probe=a27e7cdbef) | Jan 09, 2022 |
| Dell          | 0KH290                      | Desktop     | [e8c0e16dfb](https://linux-hardware.org/?probe=e8c0e16dfb) | Dec 28, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [ca26ae6ff8](https://linux-hardware.org/?probe=ca26ae6ff8) | Dec 22, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [f6789bc7ac](https://linux-hardware.org/?probe=f6789bc7ac) | Dec 18, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [5c0550c1e8](https://linux-hardware.org/?probe=5c0550c1e8) | Dec 09, 2021 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [db552307a3](https://linux-hardware.org/?probe=db552307a3) | Dec 07, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [142cab14c6](https://linux-hardware.org/?probe=142cab14c6) | Dec 02, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [0b2751c5c1](https://linux-hardware.org/?probe=0b2751c5c1) | Dec 02, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [dbbe56da66](https://linux-hardware.org/?probe=dbbe56da66) | Dec 01, 2021 |
| Gigabyte      | X570 UD                     | Desktop     | [79c117738b](https://linux-hardware.org/?probe=79c117738b) | Dec 01, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [dc981a1604](https://linux-hardware.org/?probe=dc981a1604) | Nov 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [362a840c47](https://linux-hardware.org/?probe=362a840c47) | Nov 20, 2021 |
| Alienware     | 17                          | Notebook    | [d3460bdfd1](https://linux-hardware.org/?probe=d3460bdfd1) | Nov 20, 2021 |
| Dell          | Precision 5550              | Notebook    | [f7853ec2b6](https://linux-hardware.org/?probe=f7853ec2b6) | Nov 18, 2021 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [6eb5a4107e](https://linux-hardware.org/?probe=6eb5a4107e) | Nov 10, 2021 |
| Intel         | D33217GKE G69901-205        | Desktop     | [a922d5f3fc](https://linux-hardware.org/?probe=a922d5f3fc) | Nov 10, 2021 |
| ZOTAC         | ZBOX-CA621NANO              | Mini pc     | [e540507afc](https://linux-hardware.org/?probe=e540507afc) | Nov 10, 2021 |
| Intel         | D33217GKE G69901-205        | Desktop     | [dd1ddaf74f](https://linux-hardware.org/?probe=dd1ddaf74f) | Nov 09, 2021 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [201bc8d044](https://linux-hardware.org/?probe=201bc8d044) | Oct 17, 2021 |
| Getac         | B300G4                      | Notebook    | [78b2fab1e0](https://linux-hardware.org/?probe=78b2fab1e0) | Oct 17, 2021 |
| HP            | Pavilion dv7                | Notebook    | [6c14033e55](https://linux-hardware.org/?probe=6c14033e55) | Oct 16, 2021 |
| HP            | Pavilion dv7                | Notebook    | [f93789f29a](https://linux-hardware.org/?probe=f93789f29a) | Oct 16, 2021 |
| Acer          | Extensa 5620                | Notebook    | [5cae4fe0fa](https://linux-hardware.org/?probe=5cae4fe0fa) | Oct 11, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [95d389bfe5](https://linux-hardware.org/?probe=95d389bfe5) | Oct 07, 2021 |
| Huanan        | X79 V2.47                   | Desktop     | [326b3f5892](https://linux-hardware.org/?probe=326b3f5892) | Oct 07, 2021 |
| Huanan        | X79 V2.47                   | Desktop     | [c2c6287186](https://linux-hardware.org/?probe=c2c6287186) | Oct 07, 2021 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [9cd559605c](https://linux-hardware.org/?probe=9cd559605c) | Sep 27, 2021 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [68f4ff7431](https://linux-hardware.org/?probe=68f4ff7431) | Sep 27, 2021 |
| Lenovo        | ThinkPad E14 20RA0036MX     | Notebook    | [b2183edddf](https://linux-hardware.org/?probe=b2183edddf) | Sep 24, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [d339553d59](https://linux-hardware.org/?probe=d339553d59) | Sep 19, 2021 |
| Prestigio     | PNT10131DEDB                | Convertible | [39dc1df1df](https://linux-hardware.org/?probe=39dc1df1df) | Sep 18, 2021 |
| Alienware     | 17                          | Notebook    | [c97b201719](https://linux-hardware.org/?probe=c97b201719) | Sep 17, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [47fb03fde8](https://linux-hardware.org/?probe=47fb03fde8) | Sep 17, 2021 |
| MSI           | MS-B901                     | All in one  | [282992f343](https://linux-hardware.org/?probe=282992f343) | Sep 14, 2021 |
| MSI           | MS-B901                     | All in one  | [3a288bcc81](https://linux-hardware.org/?probe=3a288bcc81) | Sep 14, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4f393c5347](https://linux-hardware.org/?probe=4f393c5347) | Sep 13, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [1240138d48](https://linux-hardware.org/?probe=1240138d48) | Sep 11, 2021 |
| ASUSTek       | UX530UX                     | Notebook    | [c713dcf9e2](https://linux-hardware.org/?probe=c713dcf9e2) | Sep 08, 2021 |
| ASUSTek       | X510UA                      | Notebook    | [0a8045cc4f](https://linux-hardware.org/?probe=0a8045cc4f) | Sep 05, 2021 |
| ASUSTek       | X550ZA                      | Notebook    | [210ca88228](https://linux-hardware.org/?probe=210ca88228) | Aug 30, 2021 |
| Lenovo        | ThinkPad X201 3680CG7       | Notebook    | [9565bae9c3](https://linux-hardware.org/?probe=9565bae9c3) | Aug 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [75619baa6e](https://linux-hardware.org/?probe=75619baa6e) | Aug 29, 2021 |
| ASUSTek       | X550ZA                      | Notebook    | [0a21d3b326](https://linux-hardware.org/?probe=0a21d3b326) | Aug 27, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [bf81c78371](https://linux-hardware.org/?probe=bf81c78371) | Aug 26, 2021 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [b40ad47903](https://linux-hardware.org/?probe=b40ad47903) | Aug 25, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | Notebook    | [e5d8500e1c](https://linux-hardware.org/?probe=e5d8500e1c) | Aug 21, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | Notebook    | [67b971a2dd](https://linux-hardware.org/?probe=67b971a2dd) | Aug 21, 2021 |
| Lenovo        | ThinkPad W541 20EF001TMS    | Notebook    | [bc2879c7e5](https://linux-hardware.org/?probe=bc2879c7e5) | Aug 19, 2021 |
| Lenovo        | ThinkPad 20AY001DMH         | Notebook    | [d3f7b62a42](https://linux-hardware.org/?probe=d3f7b62a42) | Aug 19, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [559742f4d7](https://linux-hardware.org/?probe=559742f4d7) | Aug 19, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [f21459caa1](https://linux-hardware.org/?probe=f21459caa1) | Aug 19, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | Notebook    | [5f9d1cd1a6](https://linux-hardware.org/?probe=5f9d1cd1a6) | Aug 18, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d28cc83aed](https://linux-hardware.org/?probe=d28cc83aed) | Aug 17, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [be5db43316](https://linux-hardware.org/?probe=be5db43316) | Aug 17, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [0ce69e02fa](https://linux-hardware.org/?probe=0ce69e02fa) | Aug 17, 2021 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [286d06cd5e](https://linux-hardware.org/?probe=286d06cd5e) | Aug 15, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | Notebook    | [fcd91a58e2](https://linux-hardware.org/?probe=fcd91a58e2) | Aug 13, 2021 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [b2db3ea0a9](https://linux-hardware.org/?probe=b2db3ea0a9) | Aug 10, 2021 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [c086b1441c](https://linux-hardware.org/?probe=c086b1441c) | Aug 09, 2021 |
| HP            | Pavilion dv7                | Notebook    | [a56935a751](https://linux-hardware.org/?probe=a56935a751) | Aug 09, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2a9fe5f63c](https://linux-hardware.org/?probe=2a9fe5f63c) | Jul 31, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1c5dccfd22](https://linux-hardware.org/?probe=1c5dccfd22) | Jul 31, 2021 |
| MSI           | GP62M 7RDX                  | Notebook    | [f02c96473f](https://linux-hardware.org/?probe=f02c96473f) | Jul 30, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [19a4054ab4](https://linux-hardware.org/?probe=19a4054ab4) | Jul 28, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [bc64d314a1](https://linux-hardware.org/?probe=bc64d314a1) | Jul 28, 2021 |
| ASUSTek       | M3N78                       | Desktop     | [810e386d8b](https://linux-hardware.org/?probe=810e386d8b) | Jul 26, 2021 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [4f26f93184](https://linux-hardware.org/?probe=4f26f93184) | Jul 26, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [932c4de6ce](https://linux-hardware.org/?probe=932c4de6ce) | Jul 18, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | Notebook    | [7207e6aa0f](https://linux-hardware.org/?probe=7207e6aa0f) | Jul 08, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [a47fb764b4](https://linux-hardware.org/?probe=a47fb764b4) | Jul 01, 2021 |
| ASUSTek       | N3050I-C                    | Desktop     | [e9cd0640f7](https://linux-hardware.org/?probe=e9cd0640f7) | Jun 30, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [7a01d3d232](https://linux-hardware.org/?probe=7a01d3d232) | Jun 28, 2021 |
| ASUSTek       | N3050I-C                    | Desktop     | [c42e493962](https://linux-hardware.org/?probe=c42e493962) | Jun 26, 2021 |
| ASUSTek       | N3050I-C                    | Desktop     | [9834731c15](https://linux-hardware.org/?probe=9834731c15) | Jun 26, 2021 |
| Lenovo        | IdeaPadFlex 10 20324        | Notebook    | [d96aea9f90](https://linux-hardware.org/?probe=d96aea9f90) | Jun 26, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [cb4242a344](https://linux-hardware.org/?probe=cb4242a344) | Jun 15, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [7bf0e678ea](https://linux-hardware.org/?probe=7bf0e678ea) | Jun 13, 2021 |
| Lenovo        | ThinkPad T450s 20BWS1RG0... | Notebook    | [79d386a567](https://linux-hardware.org/?probe=79d386a567) | Jun 08, 2021 |
| Dell          | Latitude 5511               | Notebook    | [933fb253d4](https://linux-hardware.org/?probe=933fb253d4) | Jun 07, 2021 |
| Dell          | Latitude 5511               | Notebook    | [7b5e6276c0](https://linux-hardware.org/?probe=7b5e6276c0) | Jun 07, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [6a7fe6469a](https://linux-hardware.org/?probe=6a7fe6469a) | Jun 06, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [8700a7eaed](https://linux-hardware.org/?probe=8700a7eaed) | May 31, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [1ba665b0b3](https://linux-hardware.org/?probe=1ba665b0b3) | May 24, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [3ae2f83c9f](https://linux-hardware.org/?probe=3ae2f83c9f) | May 23, 2021 |
| Dell          | G5 5587                     | Notebook    | [39be80ad79](https://linux-hardware.org/?probe=39be80ad79) | May 19, 2021 |
| Dell          | Precision 5530              | Notebook    | [aa0aa77e62](https://linux-hardware.org/?probe=aa0aa77e62) | May 16, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [6f3d7a9d3f](https://linux-hardware.org/?probe=6f3d7a9d3f) | May 15, 2021 |
| Dell          | Vostro V131                 | Notebook    | [43fe3f190f](https://linux-hardware.org/?probe=43fe3f190f) | May 14, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [426f99f758](https://linux-hardware.org/?probe=426f99f758) | May 14, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [fe95dd9355](https://linux-hardware.org/?probe=fe95dd9355) | May 11, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [f5f418c337](https://linux-hardware.org/?probe=f5f418c337) | May 02, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [1bbe4079c5](https://linux-hardware.org/?probe=1bbe4079c5) | Apr 27, 2021 |
| HP            | Compaq nx6120 (PV170PA#U... | Notebook    | [5f105dda68](https://linux-hardware.org/?probe=5f105dda68) | Apr 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f84cf26650](https://linux-hardware.org/?probe=f84cf26650) | Apr 10, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [a677fe0972](https://linux-hardware.org/?probe=a677fe0972) | Apr 08, 2021 |
| MSI           | B250M PRO-VD                | Desktop     | [20ff770033](https://linux-hardware.org/?probe=20ff770033) | Apr 07, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ed6b3b5754](https://linux-hardware.org/?probe=ed6b3b5754) | Apr 04, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [218092e59f](https://linux-hardware.org/?probe=218092e59f) | Apr 03, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [18ec5d54a4](https://linux-hardware.org/?probe=18ec5d54a4) | Apr 02, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [6e6dc77b21](https://linux-hardware.org/?probe=6e6dc77b21) | Mar 29, 2021 |
| Samsung       | R410                        | Notebook    | [331d909654](https://linux-hardware.org/?probe=331d909654) | Mar 27, 2021 |
| ASUSTek       | P5LD2                       | Desktop     | [72b40a39d4](https://linux-hardware.org/?probe=72b40a39d4) | Mar 25, 2021 |
| Samsung       | R410                        | Notebook    | [5aa6fee818](https://linux-hardware.org/?probe=5aa6fee818) | Mar 25, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [f555918663](https://linux-hardware.org/?probe=f555918663) | Mar 24, 2021 |
| Samsung       | R410                        | Notebook    | [d3f94bcc8c](https://linux-hardware.org/?probe=d3f94bcc8c) | Mar 24, 2021 |
| OEM           | Intel H81                   | Desktop     | [385b6ee448](https://linux-hardware.org/?probe=385b6ee448) | Mar 19, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [013a785195](https://linux-hardware.org/?probe=013a785195) | Mar 18, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [fb33c2e9b9](https://linux-hardware.org/?probe=fb33c2e9b9) | Mar 17, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9b991380f9](https://linux-hardware.org/?probe=9b991380f9) | Mar 17, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [273fba9fd2](https://linux-hardware.org/?probe=273fba9fd2) | Mar 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [75a661f9f8](https://linux-hardware.org/?probe=75a661f9f8) | Mar 14, 2021 |
| Notebook      | W35xSS_370SS                | Notebook    | [0e98472f08](https://linux-hardware.org/?probe=0e98472f08) | Mar 02, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [ff698cacf3](https://linux-hardware.org/?probe=ff698cacf3) | Feb 27, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [116202ee88](https://linux-hardware.org/?probe=116202ee88) | Feb 27, 2021 |
| Lenovo        | ThinkPad T61 766112G        | Notebook    | [04ec7d5efd](https://linux-hardware.org/?probe=04ec7d5efd) | Feb 25, 2021 |
| Acer          | Aspire V5-572P              | Notebook    | [61834c786c](https://linux-hardware.org/?probe=61834c786c) | Feb 24, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [4c935ce981](https://linux-hardware.org/?probe=4c935ce981) | Feb 18, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [69090d5f4c](https://linux-hardware.org/?probe=69090d5f4c) | Feb 17, 2021 |
| MSI           | MS-7267                     | Desktop     | [b987c1ad14](https://linux-hardware.org/?probe=b987c1ad14) | Feb 15, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [e1dc5a8ea7](https://linux-hardware.org/?probe=e1dc5a8ea7) | Feb 14, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [d3004980ee](https://linux-hardware.org/?probe=d3004980ee) | Feb 09, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [8652b51903](https://linux-hardware.org/?probe=8652b51903) | Jan 20, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [77be7c1164](https://linux-hardware.org/?probe=77be7c1164) | Jan 18, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [59aaeda6a9](https://linux-hardware.org/?probe=59aaeda6a9) | Dec 28, 2020 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [81daeffb49](https://linux-hardware.org/?probe=81daeffb49) | Dec 28, 2020 |
| MSI           | Z77A-G41                    | Desktop     | [171be87aa0](https://linux-hardware.org/?probe=171be87aa0) | Dec 27, 2020 |
| Timi          | RedmiBook 16                | Notebook    | [34bc3ceb48](https://linux-hardware.org/?probe=34bc3ceb48) | Dec 24, 2020 |
| MSI           | GT70 2OC/2OD                | Notebook    | [e52bbc40aa](https://linux-hardware.org/?probe=e52bbc40aa) | Dec 19, 2020 |
| Lenovo        | ThinkPad T61 64665DG        | Notebook    | [95355fcff6](https://linux-hardware.org/?probe=95355fcff6) | Dec 17, 2020 |
| Lenovo        | ThinkPad T61 64665DG        | Notebook    | [3ee030e6ac](https://linux-hardware.org/?probe=3ee030e6ac) | Dec 17, 2020 |
| Lenovo        | ThinkPad T61 765912G        | Notebook    | [9651814a46](https://linux-hardware.org/?probe=9651814a46) | Dec 08, 2020 |
| MSI           | H81I                        | Desktop     | [772ce7ff24](https://linux-hardware.org/?probe=772ce7ff24) | Dec 03, 2020 |
| MSI           | Boston                      | Desktop     | [9843e15faa](https://linux-hardware.org/?probe=9843e15faa) | Dec 01, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [07c05e281b](https://linux-hardware.org/?probe=07c05e281b) | Nov 29, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [4defcea6f8](https://linux-hardware.org/?probe=4defcea6f8) | Nov 24, 2020 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [1280ebbedf](https://linux-hardware.org/?probe=1280ebbedf) | Nov 17, 2020 |
| Intel         | D425KT AAE93083-400         | Mini pc     | [e1f6c727d9](https://linux-hardware.org/?probe=e1f6c727d9) | Oct 14, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [f61cacc391](https://linux-hardware.org/?probe=f61cacc391) | Oct 05, 2020 |
| Notebook      | W35xSS_370SS                | Notebook    | [ed0e6634d4](https://linux-hardware.org/?probe=ed0e6634d4) | Sep 29, 2020 |
| HP            | EliteBook 745 G5            | Notebook    | [e9d2889a6d](https://linux-hardware.org/?probe=e9d2889a6d) | Sep 28, 2020 |
| MSI           | X470 GAMING PRO             | Desktop     | [6b818c1352](https://linux-hardware.org/?probe=6b818c1352) | Sep 28, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [3255a17583](https://linux-hardware.org/?probe=3255a17583) | Sep 28, 2020 |
| MSI           | Z170-A PRO                  | Desktop     | [bcf22d328e](https://linux-hardware.org/?probe=bcf22d328e) | Sep 28, 2020 |
| Dell          | Latitude 7490               | Notebook    | [cfd6c8dcc4](https://linux-hardware.org/?probe=cfd6c8dcc4) | Sep 28, 2020 |
| Intel         | DX79TO AAG28805-400         | Desktop     | [d4cdc0726f](https://linux-hardware.org/?probe=d4cdc0726f) | Sep 26, 2020 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [118729faeb](https://linux-hardware.org/?probe=118729faeb) | Sep 23, 2020 |
| TUXEDO        | Book BA1510                 | Notebook    | [d89436074e](https://linux-hardware.org/?probe=d89436074e) | Sep 23, 2020 |
| Lenovo        | ThinkPad E495 20NE001GMX    | Notebook    | [3399940dd9](https://linux-hardware.org/?probe=3399940dd9) | Sep 17, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [5bd6ca5aba](https://linux-hardware.org/?probe=5bd6ca5aba) | Sep 15, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [83263681eb](https://linux-hardware.org/?probe=83263681eb) | Sep 15, 2020 |
| Notebook      | W35xSS_370SS                | Notebook    | [5b35813fca](https://linux-hardware.org/?probe=5b35813fca) | Sep 10, 2020 |
| HP            | ZBook 17                    | Notebook    | [605dfd3279](https://linux-hardware.org/?probe=605dfd3279) | Sep 08, 2020 |
| HP            | ZBook 17                    | Notebook    | [09e5bd8eb6](https://linux-hardware.org/?probe=09e5bd8eb6) | Sep 08, 2020 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [0dd7682249](https://linux-hardware.org/?probe=0dd7682249) | Sep 08, 2020 |
| ASUSTek       | X542UQR                     | Notebook    | [7782f01f3c](https://linux-hardware.org/?probe=7782f01f3c) | Sep 04, 2020 |
| ASUSTek       | E502MA                      | Notebook    | [1eb9e7db73](https://linux-hardware.org/?probe=1eb9e7db73) | Sep 01, 2020 |
| ASUSTek       | X501U                       | Notebook    | [006dc7a8d6](https://linux-hardware.org/?probe=006dc7a8d6) | Aug 15, 2020 |
| ASRock        | P45DE3                      | Desktop     | [3fce267079](https://linux-hardware.org/?probe=3fce267079) | Aug 11, 2020 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | Desktop     | [5b48876c88](https://linux-hardware.org/?probe=5b48876c88) | Aug 11, 2020 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | Desktop     | [420e531d0c](https://linux-hardware.org/?probe=420e531d0c) | Aug 11, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [fd8d68081e](https://linux-hardware.org/?probe=fd8d68081e) | Aug 08, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [30d102a39e](https://linux-hardware.org/?probe=30d102a39e) | Aug 07, 2020 |
| Lenovo        | ThinkPad X220 4291R30       | Notebook    | [bdf2c40591](https://linux-hardware.org/?probe=bdf2c40591) | Aug 06, 2020 |
| Lenovo        | ThinkPad T490 20N2000NMX    | Notebook    | [8f21de6e06](https://linux-hardware.org/?probe=8f21de6e06) | Aug 05, 2020 |
| Acer          | Extensa 5620                | Notebook    | [dba48971a3](https://linux-hardware.org/?probe=dba48971a3) | Jul 24, 2020 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [f6f1267e91](https://linux-hardware.org/?probe=f6f1267e91) | Jul 23, 2020 |
| Lenovo        | ThinkPad T480s 20L7001VU... | Notebook    | [03bcc8865c](https://linux-hardware.org/?probe=03bcc8865c) | Jul 23, 2020 |
| ASRock        | B250M Pro4                  | Desktop     | [3ad9bafdc1](https://linux-hardware.org/?probe=3ad9bafdc1) | Jul 19, 2020 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [43684f5ded](https://linux-hardware.org/?probe=43684f5ded) | Jul 15, 2020 |
| ASUSTek       | P5LD2                       | Desktop     | [caa5d2a038](https://linux-hardware.org/?probe=caa5d2a038) | Jul 13, 2020 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [751ba49889](https://linux-hardware.org/?probe=751ba49889) | Jul 09, 2020 |
| ASRock        | Z170 Pro4S                  | Desktop     | [71665893c0](https://linux-hardware.org/?probe=71665893c0) | Jul 08, 2020 |
| ASRock        | Z170 Pro4S                  | Desktop     | [2d7a70bd54](https://linux-hardware.org/?probe=2d7a70bd54) | Jul 06, 2020 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [3149f0037a](https://linux-hardware.org/?probe=3149f0037a) | Jul 03, 2020 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [9bd5a64d0d](https://linux-hardware.org/?probe=9bd5a64d0d) | Jun 25, 2020 |
| HP            | Presario CQ56               | Notebook    | [f668bc59f5](https://linux-hardware.org/?probe=f668bc59f5) | Jun 23, 2020 |
| HP            | Presario CQ56               | Notebook    | [b8db4c3694](https://linux-hardware.org/?probe=b8db4c3694) | Jun 23, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [867ca870fd](https://linux-hardware.org/?probe=867ca870fd) | Jun 14, 2020 |
| ASUSTek       | WS X299 SAGE                | Desktop     | [bfc9505d4b](https://linux-hardware.org/?probe=bfc9505d4b) | Jun 05, 2020 |
| MSI           | Boston                      | Desktop     | [48a3bf1932](https://linux-hardware.org/?probe=48a3bf1932) | Jun 02, 2020 |
| Samsung       | 535U3C                      | Notebook    | [e7bc13b354](https://linux-hardware.org/?probe=e7bc13b354) | May 30, 2020 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | Notebook    | [26c8949a0a](https://linux-hardware.org/?probe=26c8949a0a) | May 29, 2020 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [869444acf6](https://linux-hardware.org/?probe=869444acf6) | May 26, 2020 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [d4e3d725fa](https://linux-hardware.org/?probe=d4e3d725fa) | May 19, 2020 |
| ASUSTek       | Z97-A                       | Desktop     | [32fc505cab](https://linux-hardware.org/?probe=32fc505cab) | May 17, 2020 |
| MSI           | Z170A GAMING M3             | Desktop     | [369ce228c3](https://linux-hardware.org/?probe=369ce228c3) | May 16, 2020 |
| Lenovo        | ThinkPad T540p 20BFS4510... | Notebook    | [6c5bf8bfbe](https://linux-hardware.org/?probe=6c5bf8bfbe) | May 05, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [e1602a8c0e](https://linux-hardware.org/?probe=e1602a8c0e) | May 04, 2020 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [a1a1ce6e00](https://linux-hardware.org/?probe=a1a1ce6e00) | May 02, 2020 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [e3321de949](https://linux-hardware.org/?probe=e3321de949) | May 02, 2020 |
| Samsung       | 900X3C/900X3D/900X4C/900... | Notebook    | [35b95432ac](https://linux-hardware.org/?probe=35b95432ac) | Apr 30, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [eea0fa4941](https://linux-hardware.org/?probe=eea0fa4941) | Apr 25, 2020 |
| MSI           | B360-A PRO                  | Desktop     | [c42cb75770](https://linux-hardware.org/?probe=c42cb75770) | Apr 24, 2020 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [91770bcd78](https://linux-hardware.org/?probe=91770bcd78) | Apr 22, 2020 |
| MSI           | GS75 Stealth 8SE            | Notebook    | [1c50333136](https://linux-hardware.org/?probe=1c50333136) | Apr 07, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [cdca82a043](https://linux-hardware.org/?probe=cdca82a043) | Apr 05, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [61c4420d0e](https://linux-hardware.org/?probe=61c4420d0e) | Mar 22, 2020 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [76af4a7e0b](https://linux-hardware.org/?probe=76af4a7e0b) | Mar 21, 2020 |
| ASRock        | P45DE3                      | Desktop     | [fffef664cd](https://linux-hardware.org/?probe=fffef664cd) | Mar 18, 2020 |
| MSI           | B75A-G43                    | Desktop     | [9683ec9bd4](https://linux-hardware.org/?probe=9683ec9bd4) | Mar 16, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [95eb08349e](https://linux-hardware.org/?probe=95eb08349e) | Mar 15, 2020 |
| Samsung       | 275E4E/275E5E               | Notebook    | [6b624f1079](https://linux-hardware.org/?probe=6b624f1079) | Mar 12, 2020 |
| Lenovo        | ThinkPad A285 20MXS0BG00    | Notebook    | [4dabcb8d3f](https://linux-hardware.org/?probe=4dabcb8d3f) | Mar 11, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [e30b449cc4](https://linux-hardware.org/?probe=e30b449cc4) | Mar 08, 2020 |
| ASUSTek       | Z97-A                       | Desktop     | [8bc7b7979a](https://linux-hardware.org/?probe=8bc7b7979a) | Mar 01, 2020 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [63e19ed1f4](https://linux-hardware.org/?probe=63e19ed1f4) | Feb 28, 2020 |
| MSI           | 990FXA-GD65                 | Desktop     | [adc15c7147](https://linux-hardware.org/?probe=adc15c7147) | Feb 24, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b17f2abd3e](https://linux-hardware.org/?probe=b17f2abd3e) | Feb 20, 2020 |
| Lenovo        | ThinkPad P50 20EN0006MS     | Notebook    | [c71def9148](https://linux-hardware.org/?probe=c71def9148) | Feb 18, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [ed5efcdf48](https://linux-hardware.org/?probe=ed5efcdf48) | Feb 03, 2020 |
| Gigabyte      | H81M-S1                     | Desktop     | [754bdf88c1](https://linux-hardware.org/?probe=754bdf88c1) | Jan 26, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [1eb5f177d1](https://linux-hardware.org/?probe=1eb5f177d1) | Jan 13, 2020 |
| Dell          | 0D28YY A01                  | Desktop     | [be51211fe3](https://linux-hardware.org/?probe=be51211fe3) | Dec 09, 2019 |
| Dell          | Latitude 5289               | Convertible | [dfdc8c484f](https://linux-hardware.org/?probe=dfdc8c484f) | Dec 04, 2019 |
| Gigabyte      | H81M-S1                     | Desktop     | [57524ab581](https://linux-hardware.org/?probe=57524ab581) | Dec 03, 2019 |
| Dell          | Precision 5510              | Notebook    | [68c56e0ab4](https://linux-hardware.org/?probe=68c56e0ab4) | Dec 02, 2019 |
| ASUSTek       | VM60                        | Desktop     | [4842363a0b](https://linux-hardware.org/?probe=4842363a0b) | Nov 14, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [c4917de06e](https://linux-hardware.org/?probe=c4917de06e) | Oct 17, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [9f867b307a](https://linux-hardware.org/?probe=9f867b307a) | Oct 12, 2019 |
| ASRock        | B250M Pro4                  | Desktop     | [8beb57338d](https://linux-hardware.org/?probe=8beb57338d) | Oct 02, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [f3f1a208c1](https://linux-hardware.org/?probe=f3f1a208c1) | Sep 26, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [0639ef182a](https://linux-hardware.org/?probe=0639ef182a) | Sep 20, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [3b99dff2c2](https://linux-hardware.org/?probe=3b99dff2c2) | Sep 19, 2019 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [abc398724a](https://linux-hardware.org/?probe=abc398724a) | Sep 16, 2019 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [f6acac9fc8](https://linux-hardware.org/?probe=f6acac9fc8) | Sep 15, 2019 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [d2b5c32d2f](https://linux-hardware.org/?probe=d2b5c32d2f) | Sep 15, 2019 |
| Dell          | Inspiron 5748               | Notebook    | [75647e5457](https://linux-hardware.org/?probe=75647e5457) | Sep 03, 2019 |
| Acer          | Aspire V3-771               | Notebook    | [335c3fea78](https://linux-hardware.org/?probe=335c3fea78) | Aug 10, 2019 |
| Quanta        | TWH                         | Notebook    | [b6c3554305](https://linux-hardware.org/?probe=b6c3554305) | Aug 05, 2019 |
| Quanta        | TWH                         | Notebook    | [243be58298](https://linux-hardware.org/?probe=243be58298) | Aug 05, 2019 |
| HP            | OMEN by Laptop              | Notebook    | [4a247c1234](https://linux-hardware.org/?probe=4a247c1234) | Aug 03, 2019 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [15bfdc0f25](https://linux-hardware.org/?probe=15bfdc0f25) | Aug 03, 2019 |
| HP            | OMEN by Laptop              | Notebook    | [cd37f24ff8](https://linux-hardware.org/?probe=cd37f24ff8) | Aug 01, 2019 |
| HP            | 1495                        | Desktop     | [3d9e77ae8a](https://linux-hardware.org/?probe=3d9e77ae8a) | Jul 23, 2019 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [46e1a9fc55](https://linux-hardware.org/?probe=46e1a9fc55) | Jul 04, 2019 |
| Dell          | Inspiron 5558               | Notebook    | [f26b9a5e36](https://linux-hardware.org/?probe=f26b9a5e36) | Jun 29, 2019 |
| ASUSTek       | N56VZ                       | Notebook    | [02928f6b1e](https://linux-hardware.org/?probe=02928f6b1e) | Jun 25, 2019 |
| ASRock        | B250M Pro4                  | Desktop     | [3a8d19c8fc](https://linux-hardware.org/?probe=3a8d19c8fc) | Jun 22, 2019 |
| Gigabyte      | 970-GAMING                  | Desktop     | [aa1385d100](https://linux-hardware.org/?probe=aa1385d100) | Jun 03, 2019 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [1edb7b5f96](https://linux-hardware.org/?probe=1edb7b5f96) | May 25, 2019 |
| HP            | Pavilion dv4000 (EK980EA... | Notebook    | [837230178b](https://linux-hardware.org/?probe=837230178b) | May 23, 2019 |
| Intel         | DQ35JO AAD82085-807         | Desktop     | [7f57ad053d](https://linux-hardware.org/?probe=7f57ad053d) | May 20, 2019 |
| Lenovo        | G50-70 20351                | Notebook    | [84c3544bb2](https://linux-hardware.org/?probe=84c3544bb2) | May 20, 2019 |
| Samsung       | 275E4E/275E5E               | Notebook    | [60cb87eeb6](https://linux-hardware.org/?probe=60cb87eeb6) | May 11, 2019 |
| Dell          | Latitude 5289               | Convertible | [e28d069f05](https://linux-hardware.org/?probe=e28d069f05) | May 07, 2019 |
| Lenovo        | ThinkPad T61 76641FG        | Notebook    | [cfcb3e3b82](https://linux-hardware.org/?probe=cfcb3e3b82) | May 02, 2019 |
| Lenovo        | ThinkPad T61 76641FG        | Notebook    | [c577dfbf17](https://linux-hardware.org/?probe=c577dfbf17) | May 02, 2019 |
| Samsung       | 770Z5E/780Z5E               | Notebook    | [e07529a7fc](https://linux-hardware.org/?probe=e07529a7fc) | Apr 14, 2019 |
| Dell          | 0KP561                      | Desktop     | [bba0fe2672](https://linux-hardware.org/?probe=bba0fe2672) | Apr 05, 2019 |
| Dell          | 0KP561                      | Desktop     | [f3085d1ae9](https://linux-hardware.org/?probe=f3085d1ae9) | Apr 04, 2019 |
| Fujitsu Si... | AMILO La1703                | Notebook    | [4530891733](https://linux-hardware.org/?probe=4530891733) | Apr 01, 2019 |
| ASRock        | H370M-ITX/ac                | Desktop     | [ba39531b87](https://linux-hardware.org/?probe=ba39531b87) | Mar 31, 2019 |
| Dell          | Inspiron 3543               | Notebook    | [e411551975](https://linux-hardware.org/?probe=e411551975) | Mar 21, 2019 |
| Dell          | Inspiron 3543               | Notebook    | [f85fec55bb](https://linux-hardware.org/?probe=f85fec55bb) | Mar 19, 2019 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [bee48cd1c5](https://linux-hardware.org/?probe=bee48cd1c5) | Mar 09, 2019 |
| Lenovo        | ThinkPad T580 20L90026MX    | Notebook    | [14afd9ea12](https://linux-hardware.org/?probe=14afd9ea12) | Feb 27, 2019 |
| HP            | 18E7                        | Desktop     | [19df4fb560](https://linux-hardware.org/?probe=19df4fb560) | Feb 22, 2019 |
| HP            | ProBook 470 G1              | Notebook    | [268414d1b5](https://linux-hardware.org/?probe=268414d1b5) | Feb 07, 2019 |
| ABIT          | KN9 Series                  | Desktop     | [10015b723b](https://linux-hardware.org/?probe=10015b723b) | Feb 04, 2019 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [f1a9b27e5c](https://linux-hardware.org/?probe=f1a9b27e5c) | Feb 04, 2019 |
| ASRock        | B250M Pro4                  | Desktop     | [b702949950](https://linux-hardware.org/?probe=b702949950) | Dec 19, 2018 |
| Lenovo        | ThinkPad T480 20L5000BMX    | Notebook    | [5357d8ad3a](https://linux-hardware.org/?probe=5357d8ad3a) | Dec 04, 2018 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [158fb83dcc](https://linux-hardware.org/?probe=158fb83dcc) | Nov 13, 2018 |
| ASRock        | B250M Pro4                  | Desktop     | [a00ad66604](https://linux-hardware.org/?probe=a00ad66604) | Oct 24, 2018 |
| ASRock        | B250M Pro4                  | Desktop     | [9c47ffacd5](https://linux-hardware.org/?probe=9c47ffacd5) | Oct 24, 2018 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [a075fc73d3](https://linux-hardware.org/?probe=a075fc73d3) | Oct 09, 2018 |
| ASUSTek       | X55A                        | Notebook    | [403b1aa1d7](https://linux-hardware.org/?probe=403b1aa1d7) | May 08, 2018 |
| ASUSTek       | K40IJ                       | Notebook    | [24366329c2](https://linux-hardware.org/?probe=24366329c2) | May 07, 2018 |
| ECS           | H55H-3.8L                   | Desktop     | [7e782321c8](https://linux-hardware.org/?probe=7e782321c8) | Mar 31, 2018 |
| Dell          | Inspiron N5110              | Notebook    | [d7b2f7f719](https://linux-hardware.org/?probe=d7b2f7f719) | Oct 05, 2017 |
| ASUSTek       | M2N-MX SE                   | Desktop     | [78791d4918](https://linux-hardware.org/?probe=78791d4918) | Sep 13, 2017 |
| Acer          | Aspire 6530G                | Notebook    | [2f88dba791](https://linux-hardware.org/?probe=2f88dba791) | Aug 13, 2017 |
| ASUSTek       | P8H67                       | Desktop     | [e36d00c6f9](https://linux-hardware.org/?probe=e36d00c6f9) | Jul 21, 2017 |
| HP            | Compaq nx7400 (RH387EA#A... | Notebook    | [116c8bc9de](https://linux-hardware.org/?probe=116c8bc9de) | Jun 03, 2017 |
| Toshiba       | Satellite L855              | Notebook    | [de2e163003](https://linux-hardware.org/?probe=de2e163003) | May 17, 2017 |
| ECS           | nVidia-nForce               | Desktop     | [db8fd734f9](https://linux-hardware.org/?probe=db8fd734f9) | May 16, 2017 |
| HP            | Pavilion dv5                | Notebook    | [3191678465](https://linux-hardware.org/?probe=3191678465) | May 04, 2017 |
| HP            | Pavilion dv5                | Notebook    | [1f21f421ed](https://linux-hardware.org/?probe=1f21f421ed) | May 02, 2017 |
| Quanta        | TWH                         | Notebook    | [4807bd6702](https://linux-hardware.org/?probe=4807bd6702) | Apr 28, 2017 |
| Quanta        | TWH                         | Notebook    | [0105619fb7](https://linux-hardware.org/?probe=0105619fb7) | Apr 27, 2017 |
| Acer          | Aspire 5541                 | Notebook    | [efa45ad21c](https://linux-hardware.org/?probe=efa45ad21c) | Nov 14, 2016 |
| Acer          | Aspire 5541                 | Notebook    | [b61eb7bcb0](https://linux-hardware.org/?probe=b61eb7bcb0) | Nov 13, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 31        | 10.92%  |
| Ubuntu 18.04      | 22        | 7.75%   |
| Ubuntu 22.04      | 12        | 4.23%   |
| ROSA R11          | 10        | 3.52%   |
| Arch              | 10        | 3.52%   |
| Fedora 34         | 8         | 2.82%   |
| Arch Rolling      | 8         | 2.82%   |
| Ubuntu 19.04      | 7         | 2.46%   |
| ROSA R8.1         | 7         | 2.46%   |
| OpenMandriva 4.3  | 7         | 2.46%   |
| Kubuntu 20.04     | 7         | 2.46%   |
| ArcoLinux Rolling | 7         | 2.46%   |
| Linux Mint 20.1   | 6         | 2.11%   |
| ROSA 12.2         | 5         | 1.76%   |
| OpenMandriva 4.2  | 5         | 1.76%   |
| Manjaro           | 5         | 1.76%   |
| Fedora 36         | 5         | 1.76%   |
| Fedora 35         | 5         | 1.76%   |
| ROSA R9           | 4         | 1.41%   |
| Kubuntu 22.04     | 4         | 1.41%   |
| KDE neon 20.04    | 4         | 1.41%   |
| Zorin 16          | 3         | 1.06%   |
| Ubuntu 21.10      | 3         | 1.06%   |
| Ubuntu 19.10      | 3         | 1.06%   |
| ROSA R10          | 3         | 1.06%   |
| Pop!_OS 20.04     | 3         | 1.06%   |
| Gentoo 2.6        | 3         | 1.06%   |
| Fedora 31         | 3         | 1.06%   |
| Debian Testing    | 3         | 1.06%   |
| Debian 11         | 3         | 1.06%   |
| Xubuntu 20.04     | 2         | 0.7%    |
| Xubuntu 18.04     | 2         | 0.7%    |
| Ubuntu MATE 22.04 | 2         | 0.7%    |
| Ubuntu MATE 20.04 | 2         | 0.7%    |
| Ubuntu 21.04      | 2         | 0.7%    |
| Ubuntu 20.10      | 2         | 0.7%    |
| Ubuntu 16.04      | 2         | 0.7%    |
| Reborn OS         | 2         | 0.7%    |
| Pop!_OS 21.10     | 2         | 0.7%    |
| Pop!_OS 21.04     | 2         | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 84        | 30.22%  |
| ROSA         | 31        | 11.15%  |
| Fedora       | 23        | 8.27%   |
| Arch         | 18        | 6.47%   |
| OpenMandriva | 15        | 5.4%    |
| Manjaro      | 15        | 5.4%    |
| Linux Mint   | 15        | 5.4%    |
| Kubuntu      | 10        | 3.6%    |
| Debian       | 8         | 2.88%   |
| Pop!_OS      | 7         | 2.52%   |
| ArcoLinux    | 7         | 2.52%   |
| Xubuntu      | 6         | 2.16%   |
| KDE neon     | 5         | 1.8%    |
| Zorin        | 4         | 1.44%   |
| Ubuntu MATE  | 4         | 1.44%   |
| Gentoo       | 4         | 1.44%   |
| Elementary   | 4         | 1.44%   |
| Endless      | 3         | 1.08%   |
| Clear Linux  | 3         | 1.08%   |
| SteamOS      | 2         | 0.72%   |
| Reborn OS    | 2         | 0.72%   |
| openSUSE     | 2         | 0.72%   |
| LMDE         | 2         | 0.72%   |
| Ubuntu Unity | 1         | 0.36%   |
| MX           | 1         | 0.36%   |
| Lubuntu      | 1         | 0.36%   |
| EndeavourOS  | 1         | 0.36%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 5.4.0-42-generic                    | 8         | 2.59%   |
| 5.16.7-desktop-1omv4003             | 7         | 2.27%   |
| 5.15.0-52-generic                   | 5         | 1.62%   |
| 5.10.14-desktop-1omv4002            | 5         | 1.62%   |
| 5.15.0-53-generic                   | 4         | 1.29%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 4         | 1.29%   |
| 5.4.0-65-generic                    | 3         | 0.97%   |
| 5.4.0-47-generic                    | 3         | 0.97%   |
| 5.4.0-28-generic                    | 3         | 0.97%   |
| 5.15.0-56-generic                   | 3         | 0.97%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 3         | 0.97%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 3         | 0.97%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 3         | 0.97%   |
| 6.1.1-desktop-1omv2290              | 2         | 0.65%   |
| 5.8.0-63-generic                    | 2         | 0.65%   |
| 5.8.0-53-generic                    | 2         | 0.65%   |
| 5.5.2-1-MANJARO                     | 2         | 0.65%   |
| 5.4.0-88-generic                    | 2         | 0.65%   |
| 5.4.0-58-generic                    | 2         | 0.65%   |
| 5.4.0-53-generic                    | 2         | 0.65%   |
| 5.4.0-45-generic                    | 2         | 0.65%   |
| 5.4.0-33-generic                    | 2         | 0.65%   |
| 5.4.0-29-generic                    | 2         | 0.65%   |
| 5.4.0-26-generic                    | 2         | 0.65%   |
| 5.3.0-40-generic                    | 2         | 0.65%   |
| 5.15.5-76051505-generic             | 2         | 0.65%   |
| 5.15.2-arch1-1                      | 2         | 0.65%   |
| 5.15.0-46-generic                   | 2         | 0.65%   |
| 5.15.0-41-generic                   | 2         | 0.65%   |
| 5.13.12-200.fc34.x86_64             | 2         | 0.65%   |
| 5.13.0-39-generic                   | 2         | 0.65%   |
| 5.11.0-37-generic                   | 2         | 0.65%   |
| 5.11.0-34-generic                   | 2         | 0.65%   |
| 5.11.0-27-generic                   | 2         | 0.65%   |
| 5.11.0-25-generic                   | 2         | 0.65%   |
| 5.0.0-23-generic                    | 2         | 0.65%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 2         | 0.65%   |
| 4.18.0-15-generic                   | 2         | 0.65%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 2         | 0.65%   |
| 4.15.0-desktop-45.1rosa-i586        | 2         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.0    | 47        | 15.77%  |
| 4.15.0   | 26        | 8.72%   |
| 5.15.0   | 23        | 7.72%   |
| 5.11.0   | 14        | 4.7%    |
| 5.13.0   | 12        | 4.03%   |
| 5.8.0    | 11        | 3.69%   |
| 5.0.0    | 10        | 3.36%   |
| 5.16.7   | 7         | 2.35%   |
| 5.3.0    | 6         | 2.01%   |
| 4.18.0   | 6         | 2.01%   |
| 5.10.14  | 5         | 1.68%   |
| 4.9.20   | 5         | 1.68%   |
| 5.10.0   | 4         | 1.34%   |
| 5.15.2   | 3         | 1.01%   |
| 5.13.12  | 3         | 1.01%   |
| 5.10.74  | 3         | 1.01%   |
| 5.10.118 | 3         | 1.01%   |
| 4.9.9    | 3         | 1.01%   |
| 6.1.1    | 2         | 0.67%   |
| 6.0.9    | 2         | 0.67%   |
| 6.0.11   | 2         | 0.67%   |
| 5.8.10   | 2         | 0.67%   |
| 5.5.2    | 2         | 0.67%   |
| 5.17.1   | 2         | 0.67%   |
| 5.15.5   | 2         | 0.67%   |
| 5.13.13  | 2         | 0.67%   |
| 5.11.12  | 2         | 0.67%   |
| 5.11.11  | 2         | 0.67%   |
| 4.9.60   | 2         | 0.67%   |
| 4.19.0   | 2         | 0.67%   |
| 6.1.5    | 1         | 0.34%   |
| 6.1.4    | 1         | 0.34%   |
| 6.0.8    | 1         | 0.34%   |
| 6.0.5    | 1         | 0.34%   |
| 6.0.2    | 1         | 0.34%   |
| 6.0.1    | 1         | 0.34%   |
| 5.9.16   | 1         | 0.34%   |
| 5.9.13   | 1         | 0.34%   |
| 5.9.10   | 1         | 0.34%   |
| 5.9.0    | 1         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 53        | 17.85%  |
| 5.15    | 30        | 10.1%   |
| 4.15    | 26        | 8.75%   |
| 5.13    | 24        | 8.08%   |
| 5.10    | 22        | 7.41%   |
| 5.11    | 19        | 6.4%    |
| 5.8     | 14        | 4.71%   |
| 4.9     | 14        | 4.71%   |
| 5.16    | 12        | 4.04%   |
| 5.0     | 11        | 3.7%    |
| 6.0     | 8         | 2.69%   |
| 5.3     | 8         | 2.69%   |
| 5.14    | 8         | 2.69%   |
| 5.17    | 6         | 2.02%   |
| 4.18    | 6         | 2.02%   |
| 6.1     | 4         | 1.35%   |
| 5.9     | 4         | 1.35%   |
| 5.5     | 4         | 1.35%   |
| 5.12    | 4         | 1.35%   |
| 4.19    | 4         | 1.35%   |
| 5.6     | 3         | 1.01%   |
| 5.19    | 3         | 1.01%   |
| 5.18    | 3         | 1.01%   |
| 4.1     | 2         | 0.67%   |
| 5.7     | 1         | 0.34%   |
| 5.1     | 1         | 0.34%   |
| 4.4     | 1         | 0.34%   |
| 4.10    | 1         | 0.34%   |
| 3.16    | 1         | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 260       | 95.59%  |
| i686   | 11        | 4.04%   |
| armv7l | 1         | 0.37%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 96        | 34.29%  |
| KDE5       | 50        | 17.86%  |
| Unknown    | 43        | 15.36%  |
| XFCE       | 20        | 7.14%   |
| KDE4       | 19        | 6.79%   |
| X-Cinnamon | 14        | 5%      |
| MATE       | 10        | 3.57%   |
| KDE        | 5         | 1.79%   |
| i3         | 5         | 1.79%   |
| Pantheon   | 4         | 1.43%   |
| LXQt       | 3         | 1.07%   |
| Unity      | 2         | 0.71%   |
| sway       | 2         | 0.71%   |
| LXDE       | 2         | 0.71%   |
| awesome    | 2         | 0.71%   |
| openbox    | 1         | 0.36%   |
| Cinnamon   | 1         | 0.36%   |
| Budgie     | 1         | 0.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 212       | 77.37%  |
| Wayland | 43        | 15.69%  |
| Unknown | 16        | 5.84%   |
| Tty     | 2         | 0.73%   |
| Web     | 1         | 0.36%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 125       | 45.13%  |
| SDDM    | 51        | 18.41%  |
| GDM     | 37        | 13.36%  |
| KDM     | 19        | 6.86%   |
| GDM3    | 18        | 6.5%    |
| LightDM | 15        | 5.42%   |
| TDM     | 12        | 4.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| en_US           | 126       | 45.49%  |
| Unknown         | 59        | 21.3%   |
| et_EE           | 42        | 15.16%  |
| ru_RU           | 26        | 9.39%   |
| en_GB           | 11        | 3.97%   |
| de_DE           | 3         | 1.08%   |
| fr_FR           | 2         | 0.72%   |
| en_DK           | 2         | 0.72%   |
| uk_UA           | 1         | 0.36%   |
| ru_UA           | 1         | 0.36%   |
| pl_PL           | 1         | 0.36%   |
| en_US.iso885915 | 1         | 0.36%   |
| en_DE           | 1         | 0.36%   |
| C               | 1         | 0.36%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 150       | 53.96%  |
| EFI  | 128       | 46.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 198       | 72.53%  |
| Btrfs   | 34        | 12.45%  |
| Unknown | 19        | 6.96%   |
| Overlay | 16        | 5.86%   |
| Xfs     | 3         | 1.1%    |
| Ext3    | 2         | 0.73%   |
| Zfs     | 1         | 0.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 130       | 47.62%  |
| GPT     | 103       | 37.73%  |
| MBR     | 40        | 14.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 228       | 82.31%  |
| Yes       | 49        | 17.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 192       | 69.57%  |
| Yes       | 84        | 30.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 56        | 20.59%  |
| ASUSTek Computer    | 41        | 15.07%  |
| Hewlett-Packard     | 37        | 13.6%   |
| Dell                | 29        | 10.66%  |
| MSI                 | 26        | 9.56%   |
| Gigabyte Technology | 22        | 8.09%   |
| ASRock              | 8         | 2.94%   |
| Samsung Electronics | 7         | 2.57%   |
| Intel               | 6         | 2.21%   |
| Acer                | 6         | 2.21%   |
| Fujitsu             | 4         | 1.47%   |
| ECS                 | 3         | 1.1%    |
| Valve               | 2         | 0.74%   |
| Timi                | 2         | 0.74%   |
| Quanta              | 2         | 0.74%   |
| Apple               | 2         | 0.74%   |
| Alienware           | 2         | 0.74%   |
| ZOTAC               | 1         | 0.37%   |
| TUXEDO              | 1         | 0.37%   |
| Toshiba             | 1         | 0.37%   |
| Supermicro          | 1         | 0.37%   |
| Prestigio           | 1         | 0.37%   |
| Packard Bell        | 1         | 0.37%   |
| OEM                 | 1         | 0.37%   |
| Notebook            | 1         | 0.37%   |
| mPTech              | 1         | 0.37%   |
| HUAWEI              | 1         | 0.37%   |
| Huanan              | 1         | 0.37%   |
| Getac               | 1         | 0.37%   |
| Fujitsu Siemens     | 1         | 0.37%   |
| Framework           | 1         | 0.37%   |
| Chuwi               | 1         | 0.37%   |
| ABIT                | 1         | 0.37%   |
| Unknown             | 1         | 0.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| ASUS All Series                                       | 3         | 1.1%    |
| Valve Jupiter                                         | 2         | 0.74%   |
| Quanta TWH                                            | 2         | 0.74%   |
| MSI MS-7C02                                           | 2         | 0.74%   |
| MSI MS-7758                                           | 2         | 0.74%   |
| Lenovo Y50-70 20378                                   | 2         | 0.74%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2                     | 2         | 0.74%   |
| HP Pavilion Gaming Laptop 15-ec1xxx                   | 2         | 0.74%   |
| HP Pavilion dv7                                       | 2         | 0.74%   |
| HP ENVY Laptop 13-ah0xxx                              | 2         | 0.74%   |
| HP EliteBook 8470p                                    | 2         | 0.74%   |
| HP EliteBook 8460p                                    | 2         | 0.74%   |
| HP EliteBook 840 G2                                   | 2         | 0.74%   |
| Gigabyte X570 AORUS PRO                               | 2         | 0.74%   |
| Gigabyte Q87M-D2H                                     | 2         | 0.74%   |
| Dell Inspiron N5110                                   | 2         | 0.74%   |
| Alienware 17                                          | 2         | 0.74%   |
| Unknown                                               | 2         | 0.74%   |
| ZOTAC B410                                            | 1         | 0.37%   |
| TUXEDO Book BA1510                                    | 1         | 0.37%   |
| Toshiba Satellite L855                                | 1         | 0.37%   |
| Timi RedmiBook 16                                     | 1         | 0.37%   |
| Timi RedmiBook 14 II                                  | 1         | 0.37%   |
| Supermicro X10SLH-F/X10SLM+-F                         | 1         | 0.37%   |
| Samsung R410                                          | 1         | 0.37%   |
| Samsung 900X3C/900X3D/900X4C/900X4D                   | 1         | 0.37%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D            | 1         | 0.37%   |
| Samsung 770Z5E/780Z5E                                 | 1         | 0.37%   |
| Samsung 535U3C                                        | 1         | 0.37%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.37%   |
| Samsung 275E4E/275E5E                                 | 1         | 0.37%   |
| Prestigio PNT10131DEDB                                | 1         | 0.37%   |
| Packard Bell EasyNote TK87                            | 1         | 0.37%   |
| OEM Intel H81                                         | 1         | 0.37%   |
| Notebook W35xSS_370SS                                 | 1         | 0.37%   |
| MSI MS-B90111                                         | 1         | 0.37%   |
| MSI MS-7D43                                           | 1         | 0.37%   |
| MSI MS-7C91                                           | 1         | 0.37%   |
| MSI MS-7C83                                           | 1         | 0.37%   |
| MSI MS-7C75                                           | 1         | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 36        | 13.24%  |
| HP EliteBook        | 13        | 4.78%   |
| HP Pavilion         | 7         | 2.57%   |
| Dell Inspiron       | 7         | 2.57%   |
| Dell Latitude       | 6         | 2.21%   |
| ASUS PRIME          | 6         | 2.21%   |
| HP Compaq           | 5         | 1.84%   |
| Dell OptiPlex       | 5         | 1.84%   |
| Lenovo IdeaPad      | 4         | 1.47%   |
| Gigabyte X570       | 4         | 1.47%   |
| Dell XPS            | 4         | 1.47%   |
| Dell Precision      | 4         | 1.47%   |
| Acer Aspire         | 4         | 1.47%   |
| Lenovo ThinkCentre  | 3         | 1.1%    |
| Lenovo IdeaPadFlex  | 3         | 1.1%    |
| HP ENVY             | 3         | 1.1%    |
| Fujitsu LIFEBOOK    | 3         | 1.1%    |
| ASUS VivoBook       | 3         | 1.1%    |
| ASUS All            | 3         | 1.1%    |
| Valve Jupiter       | 2         | 0.74%   |
| Timi RedmiBook      | 2         | 0.74%   |
| Samsung 900X3C      | 2         | 0.74%   |
| Quanta TWH          | 2         | 0.74%   |
| MSI MS-7C02         | 2         | 0.74%   |
| MSI MS-7758         | 2         | 0.74%   |
| Lenovo Y50-70       | 2         | 0.74%   |
| Lenovo Legion       | 2         | 0.74%   |
| HP ProDesk          | 2         | 0.74%   |
| HP Presario         | 2         | 0.74%   |
| HP OMEN             | 2         | 0.74%   |
| Gigabyte Q87M-D2H   | 2         | 0.74%   |
| ASUS ZenBook        | 2         | 0.74%   |
| ASUS TUF            | 2         | 0.74%   |
| ASUS ROG            | 2         | 0.74%   |
| Alienware 17        | 2         | 0.74%   |
| Unknown             | 2         | 0.74%   |
| ZOTAC B410          | 1         | 0.37%   |
| TUXEDO Book         | 1         | 0.37%   |
| Toshiba Satellite   | 1         | 0.37%   |
| Supermicro X10SLH-F | 1         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 32        | 11.76%  |
| 2018    | 30        | 11.03%  |
| 2019    | 24        | 8.82%   |
| 2013    | 24        | 8.82%   |
| 2011    | 20        | 7.35%   |
| 2014    | 19        | 6.99%   |
| 2017    | 17        | 6.25%   |
| 2012    | 17        | 6.25%   |
| 2015    | 16        | 5.88%   |
| 2016    | 13        | 4.78%   |
| 2010    | 11        | 4.04%   |
| 2008    | 10        | 3.68%   |
| 2021    | 9         | 3.31%   |
| 2009    | 9         | 3.31%   |
| 2007    | 9         | 3.31%   |
| 2022    | 4         | 1.47%   |
| 2006    | 4         | 1.47%   |
| 2005    | 2         | 0.74%   |
| 2004    | 1         | 0.37%   |
| Unknown | 1         | 0.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 155       | 56.99%  |
| Desktop     | 102       | 37.5%   |
| Convertible | 10        | 3.68%   |
| Mini pc     | 3         | 1.1%    |
| All in one  | 1         | 0.37%   |
| Server      | 1         | 0.37%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 255       | 93.07%  |
| Enabled  | 19        | 6.93%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 272       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 57        | 20.73%  |
| 16.01-24.0  | 55        | 20%     |
| 4.01-8.0    | 52        | 18.91%  |
| 3.01-4.0    | 45        | 16.36%  |
| 32.01-64.0  | 33        | 12%     |
| 2.01-3.0    | 9         | 3.27%   |
| 24.01-32.0  | 8         | 2.91%   |
| 1.01-2.0    | 8         | 2.91%   |
| 64.01-256.0 | 5         | 1.82%   |
| 0.51-1.0    | 2         | 0.73%   |
| 0.01-0.5    | 1         | 0.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 93        | 31.74%  |
| 2.01-3.0   | 67        | 22.87%  |
| 4.01-8.0   | 51        | 17.41%  |
| 3.01-4.0   | 30        | 10.24%  |
| 0.51-1.0   | 25        | 8.53%   |
| 8.01-16.0  | 18        | 6.14%   |
| 0.01-0.5   | 4         | 1.37%   |
| 24.01-32.0 | 3         | 1.02%   |
| 16.01-24.0 | 2         | 0.68%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 162       | 57.86%  |
| 2      | 65        | 23.21%  |
| 3      | 29        | 10.36%  |
| 4      | 10        | 3.57%   |
| 6      | 7         | 2.5%    |
| 5      | 4         | 1.43%   |
| 0      | 2         | 0.71%   |
| 7      | 1         | 0.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 166       | 60.36%  |
| Yes       | 109       | 39.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 243       | 88.69%  |
| No        | 31        | 11.31%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 201       | 73.9%   |
| No        | 71        | 26.1%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 162       | 58.91%  |
| No        | 113       | 41.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Estonia | 272       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Tallinn           | 173       | 62.01%  |
| Tartu             | 30        | 10.75%  |
| Pärnu            | 11        | 3.94%   |
| Rapla             | 7         | 2.51%   |
| Rakvere           | 6         | 2.15%   |
| Haapsalu          | 5         | 1.79%   |
| Narva             | 4         | 1.43%   |
| Maardu            | 3         | 1.08%   |
| Vinni             | 2         | 0.72%   |
| Tapa              | 2         | 0.72%   |
| Saku              | 2         | 0.72%   |
| Põlva            | 2         | 0.72%   |
| Paldiski          | 2         | 0.72%   |
| Otepaeae          | 2         | 0.72%   |
| Kohtla-Järve     | 2         | 0.72%   |
| Keila             | 2         | 0.72%   |
| Jõhvi            | 2         | 0.72%   |
| Viljandi          | 1         | 0.36%   |
| Vatla             | 1         | 0.36%   |
| Vaidasoo          | 1         | 0.36%   |
| Türi             | 1         | 0.36%   |
| Tabasalu          | 1         | 0.36%   |
| Sindi             | 1         | 0.36%   |
| Sauga             | 1         | 0.36%   |
| Rae Parish        | 1         | 0.36%   |
| Pohja-Sakala vald | 1         | 0.36%   |
| Paide             | 1         | 0.36%   |
| Laagri            | 1         | 0.36%   |
| Kuressaare        | 1         | 0.36%   |
| Kose              | 1         | 0.36%   |
| Kiviõli          | 1         | 0.36%   |
| Kärdla           | 1         | 0.36%   |
| Kaeina            | 1         | 0.36%   |
| Kadrina           | 1         | 0.36%   |
| Jõgeva           | 1         | 0.36%   |
| Jaerva vald       | 1         | 0.36%   |
| Hiiumaa           | 1         | 0.36%   |
| Haabneeme         | 1         | 0.36%   |
| AEaesmaee         | 1         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 89        | 118    | 21.45%  |
| Seagate                   | 57        | 72     | 13.73%  |
| WDC                       | 46        | 70     | 11.08%  |
| Kingston                  | 33        | 46     | 7.95%   |
| Toshiba                   | 27        | 28     | 6.51%   |
| Hitachi                   | 16        | 19     | 3.86%   |
| Sandisk                   | 15        | 17     | 3.61%   |
| Crucial                   | 15        | 24     | 3.61%   |
| SK hynix                  | 14        | 18     | 3.37%   |
| HGST                      | 12        | 16     | 2.89%   |
| Unknown                   | 11        | 11     | 2.65%   |
| Intel                     | 9         | 11     | 2.17%   |
| A-DATA Technology         | 9         | 15     | 2.17%   |
| Patriot                   | 4         | 4      | 0.96%   |
| KingSpec                  | 4         | 6      | 0.96%   |
| Gigabyte Technology       | 4         | 5      | 0.96%   |
| China                     | 4         | 4      | 0.96%   |
| Apacer                    | 4         | 5      | 0.96%   |
| Transcend                 | 3         | 6      | 0.72%   |
| Micron Technology         | 3         | 3      | 0.72%   |
| Maxtor                    | 2         | 2      | 0.48%   |
| LITEONIT                  | 2         | 2      | 0.48%   |
| Lenovo                    | 2         | 2      | 0.48%   |
| Fujitsu                   | 2         | 2      | 0.48%   |
| Corsair                   | 2         | 2      | 0.48%   |
| Apple                     | 2         | 2      | 0.48%   |
| ADATA Technology          | 2         | 2      | 0.48%   |
| ZADAK                     | 1         | 1      | 0.24%   |
| XPG                       | 1         | 1      | 0.24%   |
| Team                      | 1         | 2      | 0.24%   |
| SPCC                      | 1         | 1      | 0.24%   |
| Silicon Motion            | 1         | 2      | 0.24%   |
| PNY                       | 1         | 1      | 0.24%   |
| Plextor                   | 1         | 1      | 0.24%   |
| Phison Electronics        | 1         | 1      | 0.24%   |
| Phison                    | 1         | 1      | 0.24%   |
| Netac                     | 1         | 1      | 0.24%   |
| Micron/Crucial Technology | 1         | 1      | 0.24%   |
| Lexar                     | 1         | 1      | 0.24%   |
| KIOXIA                    | 1         | 2      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                           | 6         | 1.31%   |
| Samsung NVMe SSD Drive 1TB                          | 6         | 1.31%   |
| Seagate ST500LT012-9WS142 500GB                     | 4         | 0.87%   |
| Seagate ST2000DM008-2FR102 2TB                      | 4         | 0.87%   |
| Samsung SSD 850 EVO 500GB                           | 4         | 0.87%   |
| Samsung NVMe SSD Drive 512GB                        | 4         | 0.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 4         | 0.87%   |
| Samsung HD103SJ 1TB                                 | 4         | 0.87%   |
| Kingston SA400S37240G 240GB SSD                     | 4         | 0.87%   |
| HGST HTS541010A9E680 1TB                            | 4         | 0.87%   |
| SK hynix NVMe SSD Drive 256GB                       | 3         | 0.65%   |
| Seagate ST500LM021-1KJ152 500GB                     | 3         | 0.65%   |
| Seagate ST1000DM010-2EP102 1TB                      | 3         | 0.65%   |
| Samsung SSD 970 EVO Plus 500GB                      | 3         | 0.65%   |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 0.65%   |
| Samsung SSD 960 PRO 512GB                           | 3         | 0.65%   |
| Samsung SSD 860 EVO 250GB                           | 3         | 0.65%   |
| Samsung MZ7TY128HDHP-000L1 128GB SSD                | 3         | 0.65%   |
| Kingston SV300S37A120G 120GB SSD                    | 3         | 0.65%   |
| Kingston SUV400S37240G 240GB SSD                    | 3         | 0.65%   |
| Kingston SA400S37120G 120GB SSD                     | 3         | 0.65%   |
| HGST HTS721010A9E630 1TB                            | 3         | 0.65%   |
| Crucial CT500MX500SSD1 500GB                        | 3         | 0.65%   |
| Apacer AS350 512GB SSD                              | 3         | 0.65%   |
| A-DATA SX8200PNP 512GB                              | 3         | 0.65%   |
| WDC WD10EADS-00M2B0 1TB                             | 2         | 0.44%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                | 2         | 0.44%   |
| Unknown MMC Card  16GB                              | 2         | 0.44%   |
| Unknown ArtisanTribute-512GB                        | 2         | 0.44%   |
| Toshiba NVMe SSD Drive 512GB                        | 2         | 0.44%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 0.44%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 0.44%   |
| Toshiba HDWD130 3TB                                 | 2         | 0.44%   |
| Toshiba DT01ACA100 1TB                              | 2         | 0.44%   |
| SK hynix NVMe SSD Drive 512GB                       | 2         | 0.44%   |
| Seagate ST500LT012-1DG142 500GB                     | 2         | 0.44%   |
| Seagate ST500DM002-1BD142 500GB                     | 2         | 0.44%   |
| Seagate ST3250318AS 249GB                           | 2         | 0.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 0.44%   |
| Seagate ST1000DM003-1SB102 1TB                      | 2         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 56        | 71     | 35.9%   |
| WDC                 | 35        | 52     | 22.44%  |
| Toshiba             | 17        | 17     | 10.9%   |
| Hitachi             | 16        | 19     | 10.26%  |
| Samsung Electronics | 13        | 15     | 8.33%   |
| HGST                | 12        | 16     | 7.69%   |
| Maxtor              | 2         | 2      | 1.28%   |
| Fujitsu             | 2         | 2      | 1.28%   |
| Unknown             | 1         | 1      | 0.64%   |
| ASMT                | 1         | 1      | 0.64%   |
| Apple               | 1         | 1      | 0.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 48        | 57     | 29.81%  |
| Kingston            | 25        | 34     | 15.53%  |
| Crucial             | 15        | 24     | 9.32%   |
| SanDisk             | 11        | 13     | 6.83%   |
| WDC                 | 8         | 11     | 4.97%   |
| A-DATA Technology   | 7         | 12     | 4.35%   |
| SK hynix            | 4         | 4      | 2.48%   |
| Patriot             | 4         | 4      | 2.48%   |
| KingSpec            | 4         | 6      | 2.48%   |
| China               | 4         | 4      | 2.48%   |
| Apacer              | 4         | 5      | 2.48%   |
| Transcend           | 3         | 6      | 1.86%   |
| Toshiba             | 3         | 4      | 1.86%   |
| Micron Technology   | 3         | 3      | 1.86%   |
| Intel               | 3         | 4      | 1.86%   |
| LITEONIT            | 2         | 2      | 1.24%   |
| Gigabyte Technology | 2         | 3      | 1.24%   |
| Corsair             | 2         | 2      | 1.24%   |
| Team                | 1         | 2      | 0.62%   |
| SPCC                | 1         | 1      | 0.62%   |
| Plextor             | 1         | 1      | 0.62%   |
| Netac               | 1         | 1      | 0.62%   |
| Lexar               | 1         | 1      | 0.62%   |
| Intenso             | 1         | 1      | 0.62%   |
| Integral            | 1         | 1      | 0.62%   |
| i-FlashDisk         | 1         | 1      | 0.62%   |
| Apple               | 1         | 1      | 0.62%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 130       | 208    | 36.21%  |
| HDD     | 127       | 197    | 35.38%  |
| NVMe    | 86        | 116    | 23.96%  |
| MMC     | 9         | 9      | 2.51%   |
| Unknown | 7         | 8      | 1.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 209       | 398    | 65.52%  |
| NVMe | 86        | 116    | 26.96%  |
| SAS  | 15        | 15     | 4.7%    |
| MMC  | 9         | 9      | 2.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 171       | 262    | 61.96%  |
| 0.51-1.0   | 69        | 90     | 25%     |
| 1.01-2.0   | 19        | 29     | 6.88%   |
| 4.01-10.0  | 7         | 7      | 2.54%   |
| 2.01-3.0   | 5         | 12     | 1.81%   |
| 3.01-4.0   | 4         | 4      | 1.45%   |
| 10.01-20.0 | 1         | 1      | 0.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 82        | 28.87%  |
| 251-500        | 56        | 19.72%  |
| 501-1000       | 33        | 11.62%  |
| 1-20           | 29        | 10.21%  |
| 1001-2000      | 24        | 8.45%   |
| More than 3000 | 18        | 6.34%   |
| 51-100         | 18        | 6.34%   |
| Unknown        | 9         | 3.17%   |
| 21-50          | 8         | 2.82%   |
| 2001-3000      | 7         | 2.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 119       | 41.03%  |
| 21-50          | 41        | 14.14%  |
| 101-250        | 37        | 12.76%  |
| 51-100         | 27        | 9.31%   |
| 251-500        | 18        | 6.21%   |
| 501-1000       | 18        | 6.21%   |
| More than 3000 | 9         | 3.1%    |
| 1001-2000      | 9         | 3.1%    |
| Unknown        | 9         | 3.1%    |
| 2001-3000      | 3         | 1.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Crucial CT128MX100SSD1 128GB                        | 2         | 3      | 4.76%   |
| WDC WD60EFRX-68MYMN1 6TB                            | 1         | 1      | 2.38%   |
| WDC WD5002AALX-00J37A0 500GB                        | 1         | 1      | 2.38%   |
| WDC WD5000BPVT-00HXZT1 500GB                        | 1         | 1      | 2.38%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 1         | 1      | 2.38%   |
| WDC WD2500BEVT-80A23T0 250GB                        | 1         | 1      | 2.38%   |
| WDC WD20EZRX-00DC0B0 2TB                            | 1         | 2      | 2.38%   |
| WDC WD20EARX-00PASB0 2TB                            | 1         | 1      | 2.38%   |
| WDC WD10PURX-64E5EY0 1TB                            | 1         | 1      | 2.38%   |
| WDC WD10EAVS-00D7B1 1TB                             | 1         | 1      | 2.38%   |
| WDC WD10EADS-00M2B0 1TB                             | 1         | 2      | 2.38%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD            | 1         | 2      | 2.38%   |
| Seagate ST98823AS 80GB                              | 1         | 1      | 2.38%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 2.38%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 2.38%   |
| Seagate ST9160412AS 160GB                           | 1         | 1      | 2.38%   |
| Seagate ST750LX003-1AC154 752GB                     | 1         | 1      | 2.38%   |
| Seagate ST500DM002-1BD142 500GB                     | 1         | 1      | 2.38%   |
| Seagate ST340016A 40GB                              | 1         | 2      | 2.38%   |
| Seagate ST320LT012-9WS14C 320GB                     | 1         | 1      | 2.38%   |
| Seagate ST31000528AS 1TB                            | 1         | 1      | 2.38%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 2.38%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 840 PRO Series 128GB        | 1         | 1      | 2.38%   |
| Samsung Electronics SP0802N 80GB                    | 1         | 1      | 2.38%   |
| Samsung Electronics HD642JJ 640GB                   | 1         | 1      | 2.38%   |
| Samsung Electronics HD501LJ 500GB                   | 1         | 1      | 2.38%   |
| Samsung Electronics HD103SJ 1TB                     | 1         | 1      | 2.38%   |
| Patriot P210 256GB SSD                              | 1         | 1      | 2.38%   |
| Patriot Burst 480GB SSD                             | 1         | 1      | 2.38%   |
| Netac SSD 720GB                                     | 1         | 1      | 2.38%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 2.38%   |
| Maxtor STM3250310AS 250GB                           | 1         | 1      | 2.38%   |
| Kingston RBU-SNS8152S3256GG2 256GB SSD              | 1         | 1      | 2.38%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 1      | 2.38%   |
| Hitachi HDS721680PLA380 80GB                        | 1         | 1      | 2.38%   |
| Hitachi HDS721010DLE630 1TB                         | 1         | 1      | 2.38%   |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 2.38%   |
| Fujitsu MHT2040AH PL 40GB                           | 1         | 1      | 2.38%   |
| Crucial CT480M500SSD3 480GB                         | 1         | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 27.5%   |
| WDC                 | 9         | 12     | 22.5%   |
| Samsung Electronics | 4         | 5      | 10%     |
| Crucial             | 4         | 5      | 10%     |
| Hitachi             | 3         | 3      | 7.5%    |
| Patriot             | 2         | 2      | 5%      |
| Toshiba             | 1         | 2      | 2.5%    |
| Netac               | 1         | 1      | 2.5%    |
| Micron Technology   | 1         | 1      | 2.5%    |
| Maxtor              | 1         | 1      | 2.5%    |
| Kingston            | 1         | 1      | 2.5%    |
| HGST                | 1         | 1      | 2.5%    |
| Fujitsu             | 1         | 1      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 37.93%  |
| WDC                 | 9         | 12     | 31.03%  |
| Samsung Electronics | 3         | 4      | 10.34%  |
| Hitachi             | 3         | 3      | 10.34%  |
| Maxtor              | 1         | 1      | 3.45%   |
| HGST                | 1         | 1      | 3.45%   |
| Fujitsu             | 1         | 1      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 34     | 73.68%  |
| SSD  | 10        | 13     | 26.32%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 144       | 280    | 48%     |
| Works    | 118       | 210    | 39.33%  |
| Malfunc  | 37        | 47     | 12.33%  |
| Failed   | 1         | 1      | 0.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 186       | 53.3%   |
| AMD                          | 51        | 14.61%  |
| Samsung Electronics          | 39        | 11.17%  |
| SK hynix                     | 10        | 2.87%   |
| SanDisk                      | 10        | 2.87%   |
| Kingston Technology Company  | 10        | 2.87%   |
| Marvell Technology Group     | 6         | 1.72%   |
| Toshiba America Info Systems | 5         | 1.43%   |
| Nvidia                       | 5         | 1.43%   |
| ADATA Technology             | 5         | 1.43%   |
| Phison Electronics           | 4         | 1.15%   |
| VIA Technologies             | 3         | 0.86%   |
| KIOXIA                       | 3         | 0.86%   |
| ASMedia Technology           | 3         | 0.86%   |
| Silicon Motion               | 2         | 0.57%   |
| Lenovo                       | 2         | 0.57%   |
| JMicron Technology           | 2         | 0.57%   |
| Silicon Image                | 1         | 0.29%   |
| Micron/Crucial Technology    | 1         | 0.29%   |
| Adaptec                      | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 35        | 8.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 26        | 6.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 22        | 5.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 3.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 3.27%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 2.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 8         | 2.02%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 2.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 1.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 1.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 1.76%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 1.76%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 6         | 1.51%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 6         | 1.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 1.51%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 6         | 1.51%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 1.51%   |
| AMD 400 Series Chipset SATA Controller                                         | 6         | 1.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 1.26%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5         | 1.26%   |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 1.26%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 5         | 1.26%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4         | 1.01%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 1.01%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 4         | 1.01%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 0.76%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 3         | 0.76%   |
| SK hynix Non-Volatile memory controller                                        | 3         | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 0.76%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 0.76%   |
| Kingston Company A2000 NVMe SSD                                                | 3         | 0.76%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 0.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 212       | 60.57%  |
| NVMe | 88        | 25.14%  |
| IDE  | 39        | 11.14%  |
| RAID | 10        | 2.86%   |
| SCSI | 1         | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 205       | 75.37%  |
| AMD                   | 66        | 24.26%  |
| Marvell Semiconductor | 1         | 0.37%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 6         | 2.21%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 5         | 1.84%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 1.47%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 4         | 1.47%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 4         | 1.47%   |
| AMD Ryzen 5 4500U with Radeon Graphics  | 4         | 1.47%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 3         | 1.1%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 3         | 1.1%    |
| Intel Core i5-7300U CPU @ 2.60GHz       | 3         | 1.1%    |
| Intel Core i3-4130 CPU @ 3.40GHz        | 3         | 1.1%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 3         | 1.1%    |
| AMD Ryzen 7 4700U with Radeon Graphics  | 3         | 1.1%    |
| AMD Ryzen 5 3600 6-Core Processor       | 3         | 1.1%    |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz     | 2         | 0.74%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 2         | 0.74%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 0.74%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 2         | 0.74%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 2         | 0.74%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 2         | 0.74%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz      | 2         | 0.74%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 2         | 0.74%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 2         | 0.74%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 2         | 0.74%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 0.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 0.74%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 2         | 0.74%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz      | 2         | 0.74%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 2         | 0.74%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 2         | 0.74%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 2         | 0.74%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 2         | 0.74%   |
| Intel Core i5-2500 CPU @ 3.30GHz        | 2         | 0.74%   |
| Intel Core i5 CPU M 460 @ 2.53GHz       | 2         | 0.74%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 2         | 0.74%   |
| Intel Core i3-3217U CPU @ 1.80GHz       | 2         | 0.74%   |
| Intel Core i3-2350M CPU @ 2.30GHz       | 2         | 0.74%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 2         | 0.74%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz    | 2         | 0.74%   |
| Intel Celeron CPU 1000M @ 1.80GHz       | 2         | 0.74%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 2         | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 67        | 24.63%  |
| Intel Core i7                  | 57        | 20.96%  |
| Intel Core i3                  | 19        | 6.99%   |
| AMD Ryzen 5                    | 17        | 6.25%   |
| AMD Ryzen 7                    | 14        | 5.15%   |
| Other                          | 12        | 4.41%   |
| Intel Core 2 Duo               | 12        | 4.41%   |
| Intel Celeron                  | 12        | 4.41%   |
| Intel Pentium                  | 7         | 2.57%   |
| Intel Xeon                     | 4         | 1.47%   |
| AMD Ryzen 9                    | 4         | 1.47%   |
| AMD Ryzen 7 PRO                | 4         | 1.47%   |
| AMD Phenom II X4               | 4         | 1.47%   |
| AMD Athlon 64 X2               | 4         | 1.47%   |
| Intel Core i9                  | 3         | 1.1%    |
| Intel Atom                     | 3         | 1.1%    |
| Intel Pentium M                | 2         | 0.74%   |
| Intel Celeron Dual-Core        | 2         | 0.74%   |
| AMD FX                         | 2         | 0.74%   |
| AMD A10                        | 2         | 0.74%   |
| Intel Pentium Silver           | 1         | 0.37%   |
| Intel Pentium Gold             | 1         | 0.37%   |
| Intel Pentium Dual-Core        | 1         | 0.37%   |
| Intel Pentium Dual             | 1         | 0.37%   |
| Intel Pentium D                | 1         | 0.37%   |
| Intel Pentium 4                | 1         | 0.37%   |
| Intel Core 2                   | 1         | 0.37%   |
| Intel Celeron M                | 1         | 0.37%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.37%   |
| AMD Ryzen 5 PRO                | 1         | 0.37%   |
| AMD Ryzen 3 PRO                | 1         | 0.37%   |
| AMD Ryzen 3                    | 1         | 0.37%   |
| AMD Phenom II X6               | 1         | 0.37%   |
| AMD E2                         | 1         | 0.37%   |
| AMD E                          | 1         | 0.37%   |
| AMD C-60                       | 1         | 0.37%   |
| AMD Athlon XP                  | 1         | 0.37%   |
| AMD Athlon II Dual-Core        | 1         | 0.37%   |
| AMD A8                         | 1         | 0.37%   |
| AMD A6                         | 1         | 0.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 110       | 40.44%  |
| 4       | 89        | 32.72%  |
| 6       | 33        | 12.13%  |
| 8       | 21        | 7.72%   |
| 1       | 10        | 3.68%   |
| 12      | 3         | 1.1%    |
| Unknown | 3         | 1.1%    |
| 16      | 1         | 0.37%   |
| 14      | 1         | 0.37%   |
| 3       | 1         | 0.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 272       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 180       | 65.93%  |
| 1       | 90        | 32.97%  |
| Unknown | 3         | 1.1%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 266       | 97.44%  |
| Unknown        | 4         | 1.47%   |
| 32-bit         | 3         | 1.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 21.43%  |
| 0x306c3    | 21        | 7.5%    |
| 0x306a9    | 19        | 6.79%   |
| 0x206a7    | 16        | 5.71%   |
| 0x906e9    | 9         | 3.21%   |
| 0x806ea    | 8         | 2.86%   |
| 0x08600106 | 8         | 2.86%   |
| 0x906ea    | 7         | 2.5%    |
| 0x40651    | 7         | 2.5%    |
| 0x1067a    | 7         | 2.5%    |
| 0x306d4    | 6         | 2.14%   |
| 0x20655    | 6         | 2.14%   |
| 0x08701021 | 6         | 2.14%   |
| 0x806ec    | 5         | 1.79%   |
| 0x806e9    | 5         | 1.79%   |
| 0x806c1    | 5         | 1.79%   |
| 0x6fb      | 5         | 1.79%   |
| 0x506e3    | 5         | 1.79%   |
| 0x08701013 | 5         | 1.79%   |
| 0x6fd      | 4         | 1.43%   |
| 0xa0655    | 3         | 1.07%   |
| 0xa0652    | 3         | 1.07%   |
| 0x406e3    | 3         | 1.07%   |
| 0x08108102 | 3         | 1.07%   |
| 0x05000119 | 3         | 1.07%   |
| 0xa0671    | 2         | 0.71%   |
| 0x906ed    | 2         | 0.71%   |
| 0x706a1    | 2         | 0.71%   |
| 0x6d8      | 2         | 0.71%   |
| 0x30678    | 2         | 0.71%   |
| 0x08600103 | 2         | 0.71%   |
| 0x0810100b | 2         | 0.71%   |
| 0x08001138 | 2         | 0.71%   |
| 0x06003106 | 2         | 0.71%   |
| 0x06000852 | 2         | 0.71%   |
| 0x010000db | 2         | 0.71%   |
| 0xf64      | 1         | 0.36%   |
| 0xf4a      | 1         | 0.36%   |
| 0xa0653    | 1         | 0.36%   |
| 0x906eb    | 1         | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 48        | 17.65%  |
| Haswell          | 35        | 12.87%  |
| Zen 2            | 27        | 9.93%   |
| IvyBridge        | 22        | 8.09%   |
| SandyBridge      | 20        | 7.35%   |
| Skylake          | 12        | 4.41%   |
| Core             | 12        | 4.41%   |
| Westmere         | 9         | 3.31%   |
| Penryn           | 8         | 2.94%   |
| CometLake        | 7         | 2.57%   |
| Broadwell        | 7         | 2.57%   |
| TigerLake        | 6         | 2.21%   |
| K10              | 6         | 2.21%   |
| Unknown          | 6         | 2.21%   |
| Zen              | 5         | 1.84%   |
| Zen+             | 4         | 1.47%   |
| Zen 3            | 4         | 1.47%   |
| Silvermont       | 4         | 1.47%   |
| K8 Hammer        | 4         | 1.47%   |
| Steamroller      | 3         | 1.1%    |
| Piledriver       | 3         | 1.1%    |
| IceLake          | 3         | 1.1%    |
| Goldmont plus    | 3         | 1.1%    |
| Bobcat           | 3         | 1.1%    |
| P6               | 2         | 0.74%   |
| NetBurst         | 2         | 0.74%   |
| Bonnell          | 2         | 0.74%   |
| K8 & K10 hybrid  | 1         | 0.37%   |
| K6               | 1         | 0.37%   |
| Goldmont         | 1         | 0.37%   |
| Excavator        | 1         | 0.37%   |
| Alderlake Hybrid | 1         | 0.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 161       | 47.35%  |
| Nvidia            | 110       | 32.35%  |
| AMD               | 67        | 19.71%  |
| VIA Technologies  | 1         | 0.29%   |
| ASPEED Technology | 1         | 0.29%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 15        | 4.29%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 14        | 4%      |
| AMD Renoir                                                                    | 14        | 4%      |
| Intel UHD Graphics 620                                                        | 10        | 2.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 9         | 2.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 9         | 2.57%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 9         | 2.57%   |
| Intel Core Processor Integrated Graphics Controller                           | 8         | 2.29%   |
| Intel HD Graphics 630                                                         | 7         | 2%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 6         | 1.71%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 6         | 1.71%   |
| Nvidia GP108M [GeForce MX150]                                                 | 5         | 1.43%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 5         | 1.43%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 5         | 1.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 5         | 1.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 5         | 1.43%   |
| Intel HD Graphics 620                                                         | 5         | 1.43%   |
| Intel HD Graphics 5500                                                        | 5         | 1.43%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 5         | 1.43%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 4         | 1.14%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 4         | 1.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 4         | 1.14%   |
| Intel HD Graphics 530                                                         | 4         | 1.14%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 3         | 0.86%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                            | 3         | 0.86%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 3         | 0.86%   |
| Nvidia GK208B [GeForce GT 710]                                                | 3         | 0.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 3         | 0.86%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 0.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 0.86%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 3         | 0.86%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 3         | 0.86%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 0.86%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 0.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 0.86%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 0.57%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 2         | 0.57%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                         | 2         | 0.57%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 2         | 0.57%   |
| Nvidia TU106 [GeForce RTX 2070]                                               | 2         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 98        | 35.9%   |
| 1 x Nvidia     | 54        | 19.78%  |
| Intel + Nvidia | 52        | 19.05%  |
| 1 x AMD        | 52        | 19.05%  |
| Intel + AMD    | 8         | 2.93%   |
| 2 x AMD        | 3         | 1.1%    |
| AMD + Nvidia   | 3         | 1.1%    |
| Other          | 1         | 0.37%   |
| 1 x VIA        | 1         | 0.37%   |
| AMD + ASPEED   | 1         | 0.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 198       | 71.22%  |
| Proprietary | 70        | 25.18%  |
| Unknown     | 10        | 3.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 124       | 44.77%  |
| 1.01-2.0   | 49        | 17.69%  |
| 0.01-0.5   | 32        | 11.55%  |
| 3.01-4.0   | 23        | 8.3%    |
| 7.01-8.0   | 17        | 6.14%   |
| 0.51-1.0   | 15        | 5.42%   |
| 5.01-6.0   | 7         | 2.53%   |
| 8.01-16.0  | 7         | 2.53%   |
| 2.01-3.0   | 2         | 0.72%   |
| 4.01-5.0   | 1         | 0.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 41        | 12.97%  |
| Dell                    | 37        | 11.71%  |
| Chimei Innolux          | 34        | 10.76%  |
| AU Optronics            | 31        | 9.81%   |
| LG Display              | 23        | 7.28%   |
| Goldstar                | 23        | 7.28%   |
| BOE                     | 21        | 6.65%   |
| Hewlett-Packard         | 11        | 3.48%   |
| Chi Mei Optoelectronics | 11        | 3.48%   |
| ViewSonic               | 8         | 2.53%   |
| Philips                 | 8         | 2.53%   |
| AOC                     | 8         | 2.53%   |
| Sharp                   | 7         | 2.22%   |
| Lenovo                  | 7         | 2.22%   |
| BenQ                    | 5         | 1.58%   |
| Sony                    | 3         | 0.95%   |
| PANDA                   | 3         | 0.95%   |
| LG Philips              | 3         | 0.95%   |
| Hitachi                 | 3         | 0.95%   |
| Unknown                 | 2         | 0.63%   |
| RoverScan               | 2         | 0.63%   |
| Fujitsu Siemens         | 2         | 0.63%   |
| ASUSTek Computer        | 2         | 0.63%   |
| Apple                   | 2         | 0.63%   |
| Ancor Communications    | 2         | 0.63%   |
| Acer                    | 2         | 0.63%   |
| Toshiba                 | 1         | 0.32%   |
| Tech Concepts           | 1         | 0.32%   |
| Seiko/Epson             | 1         | 0.32%   |
| Plain Tree Systems      | 1         | 0.32%   |
| LG Electronics          | 1         | 0.32%   |
| Lenovo Group Limited    | 1         | 0.32%   |
| KDB                     | 1         | 0.32%   |
| InfoVision              | 1         | 0.32%   |
| Eizo                    | 1         | 0.32%   |
| CSO                     | 1         | 0.32%   |
| CPT                     | 1         | 0.32%   |
| Belinea                 | 1         | 0.32%   |
| ANX                     | 1         | 0.32%   |
| Analogix                | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Goldstar ULTRAGEAR GSM5B80 2560x1440 597x336mm 27.0-inch                  | 3         | 0.9%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 3         | 0.9%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 3         | 0.9%    |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 3         | 0.9%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 3         | 0.9%    |
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 338x270mm 17.0-inch             | 2         | 0.6%    |
| Sony TV SNYDB01 1920x1080 1600x900mm 72.3-inch                            | 2         | 0.6%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 2         | 0.6%    |
| Samsung Electronics S32D850 SAM0BCB 2560x1440 708x398mm 32.0-inch         | 2         | 0.6%    |
| Samsung Electronics S24C650 SAM0B18 1920x1200 518x324mm 24.1-inch         | 2         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch      | 2         | 0.6%    |
| LG Display LCD Monitor LGD0685 1920x1080 309x174mm 14.0-inch              | 2         | 0.6%    |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                   | 2         | 0.6%    |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch                   | 2         | 0.6%    |
| Hewlett-Packard ZR24w HWP2869 1920x1200 546x352mm 25.6-inch               | 2         | 0.6%    |
| Hewlett-Packard 27es HWP3325 1920x1080 598x336mm 27.0-inch                | 2         | 0.6%    |
| Goldstar ULTRAWIDE GSM7768 3440x1440 800x334mm 34.1-inch                  | 2         | 0.6%    |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                      | 2         | 0.6%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 2         | 0.6%    |
| Dell U2719D DEL415A 2560x1440 597x336mm 27.0-inch                         | 2         | 0.6%    |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                         | 2         | 0.6%    |
| Dell U2312HM DEL4073 1920x1080 510x287mm 23.0-inch                        | 2         | 0.6%    |
| Dell P2314H DEL4098 1920x1080 509x286mm 23.0-inch                         | 2         | 0.6%    |
| Dell 2407WFP DELA017 1920x1200 520x330mm 24.2-inch                        | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch           | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch          | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch          | 2         | 0.6%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.6%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 2         | 0.6%    |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 2         | 0.6%    |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch  | 2         | 0.6%    |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 2         | 0.6%    |
| BOE LCD Monitor BOE077A 1920x1080 294x165mm 13.3-inch                     | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch             | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 2         | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 126       | 42.14%  |
| 1366x768 (WXGA)    | 44        | 14.72%  |
| 3840x2160 (4K)     | 22        | 7.36%   |
| 1920x1200 (WUXGA)  | 20        | 6.69%   |
| 1280x1024 (SXGA)   | 20        | 6.69%   |
| 2560x1440 (QHD)    | 16        | 5.35%   |
| 1600x900 (HD+)     | 13        | 4.35%   |
| 1280x800 (WXGA)    | 10        | 3.34%   |
| 3440x1440          | 8         | 2.68%   |
| 1680x1050 (WSXGA+) | 7         | 2.34%   |
| 2560x1600          | 4         | 1.34%   |
| 1440x900 (WXGA+)   | 3         | 1%      |
| 800x1280           | 2         | 0.67%   |
| 2560x1080          | 1         | 0.33%   |
| 2256x1504          | 1         | 0.33%   |
| 1920x540           | 1         | 0.33%   |
| 1600x1200          | 1         | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 75        | 23.36%  |
| 24      | 30        | 9.35%   |
| 13      | 30        | 9.35%   |
| 14      | 26        | 8.1%    |
| 17      | 25        | 7.79%   |
| 27      | 23        | 7.17%   |
| 23      | 17        | 5.3%    |
| 21      | 14        | 4.36%   |
| Unknown | 14        | 4.36%   |
| 12      | 9         | 2.8%    |
| 34      | 7         | 2.18%   |
| 19      | 6         | 1.87%   |
| 31      | 5         | 1.56%   |
| 84      | 4         | 1.25%   |
| 72      | 3         | 0.93%   |
| 54      | 3         | 0.93%   |
| 40      | 3         | 0.93%   |
| 25      | 3         | 0.93%   |
| 22      | 3         | 0.93%   |
| 20      | 3         | 0.93%   |
| 18      | 3         | 0.93%   |
| 16      | 3         | 0.93%   |
| 43      | 2         | 0.62%   |
| 33      | 2         | 0.62%   |
| 32      | 2         | 0.62%   |
| 65      | 1         | 0.31%   |
| 38      | 1         | 0.31%   |
| 29      | 1         | 0.31%   |
| 26      | 1         | 0.31%   |
| 11      | 1         | 0.31%   |
| 10      | 1         | 0.31%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 124       | 39.49%  |
| 501-600     | 64        | 20.38%  |
| 201-300     | 30        | 9.55%   |
| 401-500     | 24        | 7.64%   |
| 351-400     | 19        | 6.05%   |
| Unknown     | 14        | 4.46%   |
| 701-800     | 11        | 3.5%    |
| 601-700     | 11        | 3.5%    |
| 1501-2000   | 7         | 2.23%   |
| 801-900     | 4         | 1.27%   |
| 1001-1500   | 4         | 1.27%   |
| 901-1000    | 2         | 0.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 198       | 69.23%  |
| 16/10   | 45        | 15.73%  |
| 5/4     | 16        | 5.59%   |
| Unknown | 10        | 3.5%    |
| 21/9    | 7         | 2.45%   |
| 4/3     | 3         | 1.05%   |
| 6/5     | 2         | 0.7%    |
| 3/2     | 2         | 0.7%    |
| 0.62    | 2         | 0.7%    |
| 32/9    | 1         | 0.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 75        | 23.51%  |
| 201-250        | 42        | 13.17%  |
| 81-90          | 39        | 12.23%  |
| 301-350        | 24        | 7.52%   |
| 251-300        | 20        | 6.27%   |
| 71-80          | 17        | 5.33%   |
| 351-500        | 17        | 5.33%   |
| 141-150        | 15        | 4.7%    |
| Unknown        | 14        | 4.39%   |
| 151-200        | 13        | 4.08%   |
| More than 1000 | 11        | 3.45%   |
| 121-130        | 11        | 3.45%   |
| 61-70          | 9         | 2.82%   |
| 501-1000       | 6         | 1.88%   |
| 111-120        | 3         | 0.94%   |
| 51-60          | 1         | 0.31%   |
| 41-50          | 1         | 0.31%   |
| 131-140        | 1         | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 105       | 33.87%  |
| 121-160       | 85        | 27.42%  |
| 101-120       | 71        | 22.9%   |
| 161-240       | 24        | 7.74%   |
| Unknown       | 14        | 4.52%   |
| 1-50          | 7         | 2.26%   |
| More than 240 | 4         | 1.29%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 208       | 74.55%  |
| 2     | 52        | 18.64%  |
| 3     | 9         | 3.23%   |
| 0     | 9         | 3.23%   |
| 4     | 1         | 0.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 143       | 35.22%  |
| Realtek Semiconductor             | 136       | 33.5%   |
| Qualcomm Atheros                  | 42        | 10.34%  |
| Broadcom                          | 13        | 3.2%    |
| TP-Link                           | 9         | 2.22%   |
| Ralink                            | 7         | 1.72%   |
| Nvidia                            | 5         | 1.23%   |
| MediaTek                          | 5         | 1.23%   |
| Ralink Technology                 | 4         | 0.99%   |
| Lenovo                            | 4         | 0.99%   |
| Ericsson Business Mobile Networks | 4         | 0.99%   |
| Broadcom Limited                  | 4         | 0.99%   |
| Marvell Technology Group          | 3         | 0.74%   |
| Hewlett-Packard                   | 3         | 0.74%   |
| Fibocom                           | 3         | 0.74%   |
| ASIX Electronics                  | 3         | 0.74%   |
| Sierra Wireless                   | 2         | 0.49%   |
| Microsoft                         | 2         | 0.49%   |
| Huawei Technologies               | 2         | 0.49%   |
| D-Link System                     | 2         | 0.49%   |
| VIA Technologies                  | 1         | 0.25%   |
| Van Ooijen Technische Informatica | 1         | 0.25%   |
| Samsung Electronics               | 1         | 0.25%   |
| Qualcomm Atheros Communications   | 1         | 0.25%   |
| JMicron Technology                | 1         | 0.25%   |
| DisplayLink                       | 1         | 0.25%   |
| D-Link                            | 1         | 0.25%   |
| ASUSTek Computer                  | 1         | 0.25%   |
| Aquantia                          | 1         | 0.25%   |
| Apple                             | 1         | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 83        | 16.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 4.09%   |
| Intel Wireless 8265 / 8275                                        | 12        | 2.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 2.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 11        | 2.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 2.25%   |
| Intel Wi-Fi 6 AX200                                               | 10        | 2.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 1.84%   |
| Intel Wireless 7260                                               | 9         | 1.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.43%   |
| Intel Wireless 7265                                               | 7         | 1.43%   |
| Intel I211 Gigabit Network Connection                             | 7         | 1.43%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 1.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.23%   |
| Intel Ethernet Connection (7) I219-V                              | 6         | 1.23%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 5         | 1.02%   |
| Intel Wireless 3165                                               | 5         | 1.02%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 0.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.82%   |
| Intel Wireless 8260                                               | 4         | 0.82%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 0.82%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 0.82%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.82%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 0.82%   |
| Intel 82566MM Gigabit Network Connection                          | 4         | 0.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.61%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.61%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.61%   |
| Intel Wireless 3160                                               | 3         | 0.61%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 3         | 0.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.61%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 108       | 50%     |
| Realtek Semiconductor             | 31        | 14.35%  |
| Qualcomm Atheros                  | 30        | 13.89%  |
| Broadcom                          | 9         | 4.17%   |
| TP-Link                           | 8         | 3.7%    |
| Ralink                            | 7         | 3.24%   |
| Ralink Technology                 | 4         | 1.85%   |
| MediaTek                          | 4         | 1.85%   |
| Fibocom                           | 3         | 1.39%   |
| Sierra Wireless                   | 2         | 0.93%   |
| Microsoft                         | 2         | 0.93%   |
| Ericsson Business Mobile Networks | 2         | 0.93%   |
| Broadcom Limited                  | 2         | 0.93%   |
| Qualcomm Atheros Communications   | 1         | 0.46%   |
| Hewlett-Packard                   | 1         | 0.46%   |
| D-Link System                     | 1         | 0.46%   |
| D-Link                            | 1         | 0.46%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 12        | 5.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 5.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 5.05%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 4.59%   |
| Intel Wireless 7260                                                     | 9         | 4.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 3.21%   |
| Intel Wireless 7265                                                     | 7         | 3.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 2.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.29%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 2.29%   |
| Intel Wireless 3165                                                     | 5         | 2.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 2.29%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 1.83%   |
| Intel Wireless 8260                                                     | 4         | 1.83%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.83%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.38%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.38%   |
| Intel Wireless 3160                                                     | 3         | 1.38%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.38%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.38%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.38%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 3         | 1.38%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 2         | 0.92%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.92%   |
| TP-Link Archer T4U ver.3                                                | 2         | 0.92%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                               | 2         | 0.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.92%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.92%   |
| Ralink RT2500 Wireless 802.11bg                                         | 2         | 0.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.92%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                      | 2         | 0.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.92%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.92%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 118       | 46.09%  |
| Intel                    | 86        | 33.59%  |
| Qualcomm Atheros         | 19        | 7.42%   |
| Broadcom                 | 6         | 2.34%   |
| Nvidia                   | 5         | 1.95%   |
| Marvell Technology Group | 3         | 1.17%   |
| Lenovo                   | 3         | 1.17%   |
| ASIX Electronics         | 3         | 1.17%   |
| Broadcom Limited         | 2         | 0.78%   |
| VIA Technologies         | 1         | 0.39%   |
| TP-Link                  | 1         | 0.39%   |
| Samsung Electronics      | 1         | 0.39%   |
| MediaTek                 | 1         | 0.39%   |
| JMicron Technology       | 1         | 0.39%   |
| Hewlett-Packard          | 1         | 0.39%   |
| DisplayLink              | 1         | 0.39%   |
| D-Link System            | 1         | 0.39%   |
| ASUSTek Computer         | 1         | 0.39%   |
| Aquantia                 | 1         | 0.39%   |
| Apple                    | 1         | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 83        | 31.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 7.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 4.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 3.44%   |
| Intel I211 Gigabit Network Connection                             | 7         | 2.67%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 2.67%   |
| Intel Ethernet Connection (7) I219-V                              | 6         | 2.29%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.91%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.53%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 1.53%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.53%   |
| Intel 82566MM Gigabit Network Connection                          | 4         | 1.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 1.15%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 1.15%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.15%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.15%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.15%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.15%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.76%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.76%   |
| Nvidia CK804 Ethernet Controller                                  | 2         | 0.76%   |
| Lenovo ThinkPad TBT3 LAN                                          | 2         | 0.76%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.76%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.76%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.76%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.76%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.76%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.76%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.76%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.38%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.38%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.38%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.38%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 242       | 53.54%  |
| WiFi     | 201       | 44.47%  |
| Modem    | 9         | 1.99%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 156       | 55.71%  |
| Ethernet | 124       | 44.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 147       | 54.04%  |
| 1     | 114       | 41.91%  |
| 0     | 6         | 2.21%   |
| 3     | 4         | 1.47%   |
| 6     | 1         | 0.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 238       | 86.23%  |
| Yes  | 38        | 13.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 78        | 47.85%  |
| Cambridge Silicon Radio         | 17        | 10.43%  |
| Realtek Semiconductor           | 13        | 7.98%   |
| Qualcomm Atheros Communications | 12        | 7.36%   |
| Broadcom                        | 11        | 6.75%   |
| IMC Networks                    | 9         | 5.52%   |
| Hewlett-Packard                 | 4         | 2.45%   |
| Realtek                         | 3         | 1.84%   |
| ASUSTek Computer                | 3         | 1.84%   |
| TP-Link                         | 2         | 1.23%   |
| Foxconn / Hon Hai               | 2         | 1.23%   |
| Apple                           | 2         | 1.23%   |
| Toshiba                         | 1         | 0.61%   |
| Ralink                          | 1         | 0.61%   |
| Lite-On Technology              | 1         | 0.61%   |
| Integrated System Solution      | 1         | 0.61%   |
| Edimax Technology               | 1         | 0.61%   |
| Dell                            | 1         | 0.61%   |
| Askey Computer                  | 1         | 0.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 39        | 23.93%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 17        | 10.43%  |
| Intel Bluetooth Device                                | 11        | 6.75%   |
| Realtek Bluetooth Radio                               | 9         | 5.52%   |
| Intel AX200 Bluetooth                                 | 9         | 5.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 7         | 4.29%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 6         | 3.68%   |
| IMC Networks Bluetooth Device                         | 5         | 3.07%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 4         | 2.45%   |
| Realtek Bluetooth Radio                               | 3         | 1.84%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3         | 1.84%   |
| HP Broadcom 2070 Bluetooth Combo                      | 3         | 1.84%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]      | 3         | 1.84%   |
| TP-Link TPuLink UB500 Adapter                         | 2         | 1.23%   |
| Realtek RTL8723B Bluetooth                            | 2         | 1.23%   |
| Qualcomm Atheros  Bluetooth Device                    | 2         | 1.23%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 2         | 1.23%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 2         | 1.23%   |
| Intel AX210 Bluetooth                                 | 2         | 1.23%   |
| IMC Networks Bluetooth Radio                          | 2         | 1.23%   |
| Foxconn / Hon Hai Wireless_Device                     | 2         | 1.23%   |
| Broadcom BCM43142 Bluetooth 4.0                       | 2         | 1.23%   |
| Broadcom BCM2045B (BDC-2.1)                           | 2         | 1.23%   |
| Broadcom BCM2045 Bluetooth                            | 2         | 1.23%   |
| ASUS ASUS USB-BT500                                   | 2         | 1.23%   |
| Apple Bluetooth Host Controller                       | 2         | 1.23%   |
| Toshiba Bluetooth USB Host Controller                 | 1         | 0.61%   |
| Realtek RTL8821A Bluetooth                            | 1         | 0.61%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 0.61%   |
| Ralink RT3290 Bluetooth                               | 1         | 0.61%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 0.61%   |
| Qualcomm Atheros AR3012 Bluetooth                     | 1         | 0.61%   |
| Lite-On Bluetooth Device                              | 1         | 0.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1         | 0.61%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.61%   |
| IMC Networks BCM20702A0                               | 1         | 0.61%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 1         | 0.61%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 1         | 0.61%   |
| Edimax Bluetooth Adapter                              | 1         | 0.61%   |
| Dell BCM20702A0 Bluetooth Module                      | 1         | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 200       | 51.41%  |
| AMD                     | 78        | 20.05%  |
| Nvidia                  | 69        | 17.74%  |
| C-Media Electronics     | 8         | 2.06%   |
| Lenovo                  | 4         | 1.03%   |
| Kingston Technology     | 4         | 1.03%   |
| Razer USA               | 3         | 0.77%   |
| Logitech                | 3         | 0.77%   |
| TerraTec Electronic     | 2         | 0.51%   |
| SteelSeries ApS         | 2         | 0.51%   |
| Realtek Semiconductor   | 2         | 0.51%   |
| JMTek                   | 2         | 0.51%   |
| Focusrite-Novation      | 2         | 0.51%   |
| VIA Technologies        | 1         | 0.26%   |
| Texas Instruments       | 1         | 0.26%   |
| Syntek                  | 1         | 0.26%   |
| Samson Technologies     | 1         | 0.26%   |
| Roland                  | 1         | 0.26%   |
| Micronas                | 1         | 0.26%   |
| Mark of the Unicorn     | 1         | 0.26%   |
| M-Audio                 | 1         | 0.26%   |
| Creative Labs           | 1         | 0.26%   |
| BEHRINGER International | 1         | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 23        | 5.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 22        | 4.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 21        | 4.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 20        | 4.41%   |
| Intel Sunrise Point-LP HD Audio                                            | 18        | 3.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14        | 3.08%   |
| AMD Starship/Matisse HD Audio Controller                                   | 13        | 2.86%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 13        | 2.86%   |
| Intel Cannon Lake PCH cAVS                                                 | 12        | 2.64%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 10        | 2.2%    |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 1.98%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 1.98%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 9         | 1.98%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9         | 1.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8         | 1.76%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 1.76%   |
| Nvidia TU106 High Definition Audio Controller                              | 7         | 1.54%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 1.54%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 1.54%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 1.54%   |
| Nvidia GP104 High Definition Audio Controller                              | 6         | 1.32%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 1.32%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 1.32%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 1.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 1.32%   |
| AMD FCH Azalia Controller                                                  | 6         | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.1%    |
| Intel CM238 HD Audio Controller                                            | 5         | 1.1%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.1%    |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 0.88%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 0.88%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 0.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.66%   |
| Nvidia GP108 High Definition Audio Controller                              | 3         | 0.66%   |
| Nvidia GP102 HDMI Audio Controller                                         | 3         | 0.66%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 0.66%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3         | 0.66%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3         | 0.66%   |
| Kingston Technology HyperX 7.1 Audio                                       | 3         | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 38        | 19.79%  |
| SK hynix            | 31        | 16.15%  |
| Kingston            | 23        | 11.98%  |
| Unknown             | 18        | 9.38%   |
| Micron Technology   | 18        | 9.38%   |
| G.Skill             | 17        | 8.85%   |
| Crucial             | 14        | 7.29%   |
| Corsair             | 5         | 2.6%    |
| Ramaxel Technology  | 4         | 2.08%   |
| A-DATA Technology   | 3         | 1.56%   |
| Unknown (ABCD)      | 2         | 1.04%   |
| Patriot             | 2         | 1.04%   |
| Nanya Technology    | 2         | 1.04%   |
| Elpida              | 2         | 1.04%   |
| ASint Technology    | 2         | 1.04%   |
| Apacer              | 2         | 1.04%   |
| Wilk                | 1         | 0.52%   |
| Unifosa             | 1         | 0.52%   |
| Team                | 1         | 0.52%   |
| Silicon Power       | 1         | 0.52%   |
| Qimonda             | 1         | 0.52%   |
| GOODRAM             | 1         | 0.52%   |
| AMD                 | 1         | 0.52%   |
| Aeneon              | 1         | 0.52%   |
| Unknown             | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 2.37%   |
| Unknown RAM Module 512MB DIMM SDRAM                              | 2         | 0.95%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 0.95%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.95%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s                 | 2         | 0.95%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.95%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.95%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.95%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.95%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.95%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.95%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.95%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.95%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s              | 2         | 0.95%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.95%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB Row Of Chips DDR4 3200MT/s   | 2         | 0.95%   |
| Crucial RAM BLS8G4D240FSB.16FBR2 8GB DIMM DDR4 2400MT/s          | 2         | 0.95%   |
| Wilk RAM IRX3200D464L16SA/8G 8GB DIMM DDR4 3200MT/s              | 1         | 0.47%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 0.47%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                     | 1         | 0.47%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.47%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 0.47%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR3 1867MT/s           | 1         | 0.47%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                           | 1         | 0.47%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.47%   |
| Unknown RAM Module 256MB DIMM                                    | 1         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.47%   |
| Unknown RAM Module 2048MB DIMM DDR3 800MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 1         | 0.47%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 1024MB DIMM                                   | 1         | 0.47%   |
| Unifosa RAM GU332G0AJEPR8H2L.. 2GB SODIMM DDR2 667MT/s           | 1         | 0.47%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s              | 1         | 0.47%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                  | 1         | 0.47%   |
| SK hynix RAM Module 8192MB DIMM DDR3 1333MT/s                    | 1         | 0.47%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                     | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 79        | 48.77%  |
| DDR3    | 53        | 32.72%  |
| DDR2    | 9         | 5.56%   |
| SDRAM   | 7         | 4.32%   |
| LPDDR4  | 5         | 3.09%   |
| Unknown | 5         | 3.09%   |
| LPDDR3  | 2         | 1.23%   |
| DDR     | 2         | 1.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 84        | 52.5%   |
| DIMM         | 68        | 42.5%   |
| Row Of Chips | 8         | 5%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 67        | 37.85%  |
| 4096  | 48        | 27.12%  |
| 16384 | 23        | 12.99%  |
| 2048  | 20        | 11.3%   |
| 1024  | 8         | 4.52%   |
| 32768 | 5         | 2.82%   |
| 512   | 5         | 2.82%   |
| 256   | 1         | 0.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 35        | 19.34%  |
| 2667    | 27        | 14.92%  |
| 3200    | 25        | 13.81%  |
| 1333    | 14        | 7.73%   |
| 2400    | 11        | 6.08%   |
| 3600    | 8         | 4.42%   |
| 2133    | 7         | 3.87%   |
| 1334    | 7         | 3.87%   |
| Unknown | 7         | 3.87%   |
| 667     | 5         | 2.76%   |
| 800     | 4         | 2.21%   |
| 4267    | 3         | 1.66%   |
| 3266    | 3         | 1.66%   |
| 1067    | 3         | 1.66%   |
| 4199    | 2         | 1.1%    |
| 3666    | 2         | 1.1%    |
| 2666    | 2         | 1.1%    |
| 1867    | 2         | 1.1%    |
| 4133    | 1         | 0.55%   |
| 3800    | 1         | 0.55%   |
| 3733    | 1         | 0.55%   |
| 3334    | 1         | 0.55%   |
| 3000    | 1         | 0.55%   |
| 2933    | 1         | 0.55%   |
| 2733    | 1         | 0.55%   |
| 2134    | 1         | 0.55%   |
| 1866    | 1         | 0.55%   |
| 1800    | 1         | 0.55%   |
| 1066    | 1         | 0.55%   |
| 975     | 1         | 0.55%   |
| 533     | 1         | 0.55%   |
| 400     | 1         | 0.55%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Brother Industries              | 2         | 25%     |
| Seiko Epson                     | 1         | 12.5%   |
| Samsung Electronics             | 1         | 12.5%   |
| QinHeng Electronics             | 1         | 12.5%   |
| Konica Minolta                  | 1         | 12.5%   |
| Hewlett-Packard                 | 1         | 12.5%   |
| cab Produkttechnik GmbH & Co KG | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Seiko Epson TM-T20                       | 1         | 12.5%   |
| Samsung SCX-3400 Series                  | 1         | 12.5%   |
| QinHeng CH340S                           | 1         | 12.5%   |
| Konica Minolta Printer                   | 1         | 12.5%   |
| HP Smart Tank 750 series                 | 1         | 12.5%   |
| cab Produkttechnik GmbH & Co KG EOS2/300 | 1         | 12.5%   |
| Brother HL-4140CN series                 | 1         | 12.5%   |
| Brother DCP-L2510D series                | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seiko Epson Perfection 660                          | 1         | 50%     |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO] | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 35        | 22.01%  |
| Microdia                               | 14        | 8.81%   |
| IMC Networks                           | 14        | 8.81%   |
| Realtek Semiconductor                  | 13        | 8.18%   |
| Acer                                   | 13        | 8.18%   |
| Sunplus Innovation Technology          | 12        | 7.55%   |
| Logitech                               | 11        | 6.92%   |
| Lite-On Technology                     | 6         | 3.77%   |
| Silicon Motion                         | 5         | 3.14%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.14%   |
| Syntek                                 | 4         | 2.52%   |
| Suyin                                  | 4         | 2.52%   |
| Luxvisions Innotech Limited            | 4         | 2.52%   |
| Apple                                  | 3         | 1.89%   |
| Quanta                                 | 2         | 1.26%   |
| Lenovo                                 | 2         | 1.26%   |
| Arkmicro Technologies                  | 2         | 1.26%   |
| Alcor Micro                            | 2         | 1.26%   |
| Z-Star Microelectronics                | 1         | 0.63%   |
| Xiaomi                                 | 1         | 0.63%   |
| Samsung Electronics                    | 1         | 0.63%   |
| Microsoft                              | 1         | 0.63%   |
| LG Electronics                         | 1         | 0.63%   |
| Importek                               | 1         | 0.63%   |
| Huddly                                 | 1         | 0.63%   |
| Creative Technology                    | 1         | 0.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 9         | 5.56%   |
| Chicony Integrated Camera                               | 7         | 4.32%   |
| Lite-On Integrated Camera                               | 5         | 3.09%   |
| Realtek USB Camera                                      | 4         | 2.47%   |
| Acer Integrated Camera                                  | 4         | 2.47%   |
| Logitech Webcam C930e                                   | 3         | 1.85%   |
| Logitech HD Webcam C525                                 | 3         | 1.85%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 1.85%   |
| IMC Networks Integrated Camera                          | 3         | 1.85%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 3         | 1.85%   |
| Chicony Integrated HP HD Webcam                         | 3         | 1.85%   |
| Chicony FJ Camera                                       | 3         | 1.85%   |
| Syntek Integrated Camera                                | 2         | 1.23%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 1.23%   |
| Sunplus Asus Webcam                                     | 2         | 1.23%   |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.] | 2         | 1.23%   |
| Realtek Lenovo EasyCamera                               | 2         | 1.23%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.23%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 1.23%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 1.23%   |
| Logitech Webcam C270                                    | 2         | 1.23%   |
| Logitech HD Pro Webcam C920                             | 2         | 1.23%   |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 1.23%   |
| Chicony ThinkPad T490 Webcam                            | 2         | 1.23%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 1.23%   |
| Chicony HP Wide Vision HD Camera                        | 2         | 1.23%   |
| Chicony HP HD Webcam                                    | 2         | 1.23%   |
| Arkmicro USB2.0 PC CAMERA                               | 2         | 1.23%   |
| Apple iPhone 5/5C/5S/6/SE                               | 2         | 1.23%   |
| Z-Star Vimicro USB Camera (Altair)                      | 1         | 0.62%   |
| Xiaomi Mi 10 Lite 5G                                    | 1         | 0.62%   |
| Syntek USB2.0 UVC PC Camera                             | 1         | 0.62%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.62%   |
| Suyin USB Webcam                                        | 1         | 0.62%   |
| Suyin Integrated_Webcam_HD                              | 1         | 0.62%   |
| Suyin HD WebCam                                         | 1         | 0.62%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 1         | 0.62%   |
| Sunplus Laptop_Integrated_Webcam_HD                     | 1         | 0.62%   |
| Sunplus Laptop Integrated Webcam FHD                    | 1         | 0.62%   |
| Sunplus Integrated Webcam                               | 1         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 19        | 44.19%  |
| Synaptics                  | 11        | 25.58%  |
| Upek                       | 4         | 9.3%    |
| STMicroelectronics         | 4         | 9.3%    |
| Shenzhen Goodix Technology | 3         | 6.98%   |
| Elan Microelectronics      | 1         | 2.33%   |
| AuthenTec                  | 1         | 2.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                  | 5         | 11.63%  |
| Validity Sensors VFS 5011 fingerprint sensor                | 4         | 9.3%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 4         | 9.3%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 4         | 9.3%    |
| STMicroelectronics Fingerprint Reader                       | 4         | 9.3%    |
| Unknown                                                     | 4         | 9.3%    |
| Validity Sensors VFS471 Fingerprint Reader                  | 3         | 6.98%   |
| Synaptics Metallica MIS Touch Fingerprint Reader            | 3         | 6.98%   |
| Validity Sensors VFS5011 Fingerprint Reader                 | 2         | 4.65%   |
| Shenzhen Goodix FingerPrint                                 | 2         | 4.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor           | 1         | 2.33%   |
| Validity Sensors VFS101 Fingerprint Reader                  | 1         | 2.33%   |
| Validity Sensors Synaptics WBDI                             | 1         | 2.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 2.33%   |
| Validity Sensors Fingerprint scanner                        | 1         | 2.33%   |
| Shenzhen Goodix  Fingerprint Device                         | 1         | 2.33%   |
| Elan ELAN:Fingerprint                                       | 1         | 2.33%   |
| AuthenTec AES2550 Fingerprint Sensor                        | 1         | 2.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 23        | 41.07%  |
| OmniKey               | 18        | 32.14%  |
| Gemalto (was Gemplus) | 6         | 10.71%  |
| Lenovo                | 3         | 5.36%   |
| Broadcom              | 3         | 5.36%   |
| SCM Microsystems      | 1         | 1.79%   |
| O2 Micro              | 1         | 1.79%   |
| Clay Logic            | 1         | 1.79%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                    | 19        | 33.93%  |
| OmniKey CardMan 1021                                   | 15        | 26.79%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader      | 5         | 8.93%   |
| Alcor Micro Watchdata W 1981                           | 4         | 7.14%   |
| OmniKey CardMan 4321                                   | 3         | 5.36%   |
| Lenovo Integrated Smart Card Reader                    | 3         | 5.36%   |
| Broadcom 58200                                         | 3         | 5.36%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1         | 1.79%   |
| O2 Micro OZ776 CCID Smartcard Reader                   | 1         | 1.79%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer | 1         | 1.79%   |
| Clay Logic Nitrokey Start                              | 1         | 1.79%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 180       | 64.52%  |
| 1     | 75        | 26.88%  |
| 2     | 21        | 7.53%   |
| 3     | 3         | 1.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 43        | 34.68%  |
| Graphics card            | 32        | 25.81%  |
| Chipcard                 | 28        | 22.58%  |
| Net/wireless             | 6         | 4.84%   |
| Multimedia controller    | 3         | 2.42%   |
| Communication controller | 3         | 2.42%   |
| Net/ethernet             | 2         | 1.61%   |
| Card reader              | 2         | 1.61%   |
| Camera                   | 2         | 1.61%   |
| Sound                    | 1         | 0.81%   |
| Modem                    | 1         | 0.81%   |
| Bluetooth                | 1         | 0.81%   |

