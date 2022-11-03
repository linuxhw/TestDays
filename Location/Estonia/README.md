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

Total: 361

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 31        | 11.7%   |
| Ubuntu 18.04      | 22        | 8.3%    |
| ROSA R11          | 10        | 3.77%   |
| Arch              | 10        | 3.77%   |
| Fedora 34         | 8         | 3.02%   |
| Ubuntu 19.04      | 7         | 2.64%   |
| ROSA R8.1         | 7         | 2.64%   |
| OpenMandriva 4.3  | 7         | 2.64%   |
| Kubuntu 20.04     | 7         | 2.64%   |
| Arch Rolling      | 7         | 2.64%   |
| Ubuntu 22.04      | 6         | 2.26%   |
| Linux Mint 20.1   | 6         | 2.26%   |
| ArcoLinux Rolling | 6         | 2.26%   |
| ROSA 12.2         | 5         | 1.89%   |
| OpenMandriva 4.2  | 5         | 1.89%   |
| Manjaro           | 5         | 1.89%   |
| Fedora 35         | 5         | 1.89%   |
| ROSA R9           | 4         | 1.51%   |
| Kubuntu 22.04     | 4         | 1.51%   |
| KDE neon 20.04    | 4         | 1.51%   |
| Fedora 36         | 4         | 1.51%   |
| Ubuntu 21.10      | 3         | 1.13%   |
| Ubuntu 19.10      | 3         | 1.13%   |
| ROSA R10          | 3         | 1.13%   |
| Pop!_OS 20.04     | 3         | 1.13%   |
| Gentoo 2.6        | 3         | 1.13%   |
| Fedora 31         | 3         | 1.13%   |
| Debian Testing    | 3         | 1.13%   |
| Debian 11         | 3         | 1.13%   |
| Zorin 16          | 2         | 0.75%   |
| Xubuntu 20.04     | 2         | 0.75%   |
| Xubuntu 18.04     | 2         | 0.75%   |
| Ubuntu MATE 20.04 | 2         | 0.75%   |
| Ubuntu 21.04      | 2         | 0.75%   |
| Ubuntu 20.10      | 2         | 0.75%   |
| Ubuntu 16.04      | 2         | 0.75%   |
| Reborn OS         | 2         | 0.75%   |
| Pop!_OS 21.10     | 2         | 0.75%   |
| Pop!_OS 21.04     | 2         | 0.75%   |
| Manjaro 22.0.0    | 2         | 0.75%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 78        | 30.12%  |
| ROSA         | 31        | 11.97%  |
| Fedora       | 21        | 8.11%   |
| Arch         | 17        | 6.56%   |
| Manjaro      | 15        | 5.79%   |
| Linux Mint   | 15        | 5.79%   |
| OpenMandriva | 13        | 5.02%   |
| Kubuntu      | 10        | 3.86%   |
| Debian       | 8         | 3.09%   |
| Pop!_OS      | 7         | 2.7%    |
| ArcoLinux    | 6         | 2.32%   |
| Xubuntu      | 5         | 1.93%   |
| KDE neon     | 4         | 1.54%   |
| Gentoo       | 4         | 1.54%   |
| Elementary   | 4         | 1.54%   |
| Zorin        | 3         | 1.16%   |
| Ubuntu MATE  | 3         | 1.16%   |
| Endless      | 3         | 1.16%   |
| Clear Linux  | 3         | 1.16%   |
| Reborn OS    | 2         | 0.77%   |
| LMDE         | 2         | 0.77%   |
| Ubuntu Unity | 1         | 0.39%   |
| SteamOS      | 1         | 0.39%   |
| openSUSE     | 1         | 0.39%   |
| MX           | 1         | 0.39%   |
| Lubuntu      | 1         | 0.39%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 5.4.0-42-generic                    | 8         | 2.79%   |
| 5.16.7-desktop-1omv4003             | 7         | 2.44%   |
| 5.10.14-desktop-1omv4002            | 5         | 1.74%   |
| 5.15.0-52-generic                   | 4         | 1.39%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 4         | 1.39%   |
| 5.4.0-65-generic                    | 3         | 1.05%   |
| 5.4.0-47-generic                    | 3         | 1.05%   |
| 5.4.0-28-generic                    | 3         | 1.05%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 3         | 1.05%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 3         | 1.05%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 3         | 1.05%   |
| 5.8.0-63-generic                    | 2         | 0.7%    |
| 5.8.0-53-generic                    | 2         | 0.7%    |
| 5.5.2-1-MANJARO                     | 2         | 0.7%    |
| 5.4.0-88-generic                    | 2         | 0.7%    |
| 5.4.0-58-generic                    | 2         | 0.7%    |
| 5.4.0-53-generic                    | 2         | 0.7%    |
| 5.4.0-45-generic                    | 2         | 0.7%    |
| 5.4.0-33-generic                    | 2         | 0.7%    |
| 5.4.0-29-generic                    | 2         | 0.7%    |
| 5.4.0-26-generic                    | 2         | 0.7%    |
| 5.3.0-40-generic                    | 2         | 0.7%    |
| 5.15.5-76051505-generic             | 2         | 0.7%    |
| 5.15.2-arch1-1                      | 2         | 0.7%    |
| 5.15.0-46-generic                   | 2         | 0.7%    |
| 5.15.0-41-generic                   | 2         | 0.7%    |
| 5.13.12-200.fc34.x86_64             | 2         | 0.7%    |
| 5.13.0-39-generic                   | 2         | 0.7%    |
| 5.11.0-37-generic                   | 2         | 0.7%    |
| 5.11.0-34-generic                   | 2         | 0.7%    |
| 5.11.0-27-generic                   | 2         | 0.7%    |
| 5.11.0-25-generic                   | 2         | 0.7%    |
| 5.0.0-23-generic                    | 2         | 0.7%    |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 2         | 0.7%    |
| 4.18.0-15-generic                   | 2         | 0.7%    |
| 4.15.0-desktop-68.5rosa-x86_64      | 2         | 0.7%    |
| 4.15.0-desktop-45.1rosa-i586        | 2         | 0.7%    |
| 4.15.0-50-generic                   | 2         | 0.7%    |
| 4.15.0-46-generic                   | 2         | 0.7%    |
| 4.15.0-45-generic                   | 2         | 0.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.0    | 47        | 17.03%  |
| 4.15.0   | 26        | 9.42%   |
| 5.15.0   | 14        | 5.07%   |
| 5.11.0   | 14        | 5.07%   |
| 5.8.0    | 11        | 3.99%   |
| 5.13.0   | 11        | 3.99%   |
| 5.0.0    | 10        | 3.62%   |
| 5.16.7   | 7         | 2.54%   |
| 5.3.0    | 6         | 2.17%   |
| 4.18.0   | 6         | 2.17%   |
| 5.10.14  | 5         | 1.81%   |
| 4.9.20   | 5         | 1.81%   |
| 5.10.0   | 4         | 1.45%   |
| 5.15.2   | 3         | 1.09%   |
| 5.13.12  | 3         | 1.09%   |
| 5.10.74  | 3         | 1.09%   |
| 5.10.118 | 3         | 1.09%   |
| 4.9.9    | 3         | 1.09%   |
| 5.8.10   | 2         | 0.72%   |
| 5.5.2    | 2         | 0.72%   |
| 5.17.1   | 2         | 0.72%   |
| 5.15.5   | 2         | 0.72%   |
| 5.13.13  | 2         | 0.72%   |
| 5.11.12  | 2         | 0.72%   |
| 5.11.11  | 2         | 0.72%   |
| 4.9.60   | 2         | 0.72%   |
| 4.19.0   | 2         | 0.72%   |
| 6.0.2    | 1         | 0.36%   |
| 6.0.1    | 1         | 0.36%   |
| 5.9.16   | 1         | 0.36%   |
| 5.9.13   | 1         | 0.36%   |
| 5.9.10   | 1         | 0.36%   |
| 5.9.0    | 1         | 0.36%   |
| 5.8.6    | 1         | 0.36%   |
| 5.7.0    | 1         | 0.36%   |
| 5.6.13   | 1         | 0.36%   |
| 5.6.11   | 1         | 0.36%   |
| 5.6.10   | 1         | 0.36%   |
| 5.5.9    | 1         | 0.36%   |
| 5.5.6    | 1         | 0.36%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 53        | 19.27%  |
| 4.15    | 26        | 9.45%   |
| 5.13    | 23        | 8.36%   |
| 5.10    | 22        | 8%      |
| 5.15    | 21        | 7.64%   |
| 5.11    | 19        | 6.91%   |
| 5.8     | 14        | 5.09%   |
| 4.9     | 14        | 5.09%   |
| 5.16    | 12        | 4.36%   |
| 5.0     | 11        | 4%      |
| 5.3     | 8         | 2.91%   |
| 5.14    | 7         | 2.55%   |
| 5.17    | 6         | 2.18%   |
| 4.18    | 6         | 2.18%   |
| 5.9     | 4         | 1.45%   |
| 5.5     | 4         | 1.45%   |
| 5.12    | 4         | 1.45%   |
| 4.19    | 4         | 1.45%   |
| 5.6     | 3         | 1.09%   |
| 5.18    | 3         | 1.09%   |
| 6.0     | 2         | 0.73%   |
| 5.19    | 2         | 0.73%   |
| 4.1     | 2         | 0.73%   |
| 5.7     | 1         | 0.36%   |
| 5.1     | 1         | 0.36%   |
| 4.4     | 1         | 0.36%   |
| 4.10    | 1         | 0.36%   |
| 3.16    | 1         | 0.36%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 241       | 95.26%  |
| i686   | 11        | 4.35%   |
| armv7l | 1         | 0.4%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 88        | 33.85%  |
| KDE5       | 45        | 17.31%  |
| Unknown    | 43        | 16.54%  |
| KDE4       | 19        | 7.31%   |
| XFCE       | 18        | 6.92%   |
| X-Cinnamon | 14        | 5.38%   |
| MATE       | 9         | 3.46%   |
| KDE        | 5         | 1.92%   |
| Pantheon   | 4         | 1.54%   |
| LXQt       | 3         | 1.15%   |
| i3         | 3         | 1.15%   |
| Unity      | 2         | 0.77%   |
| awesome    | 2         | 0.77%   |
| sway       | 1         | 0.38%   |
| openbox    | 1         | 0.38%   |
| LXDE       | 1         | 0.38%   |
| Cinnamon   | 1         | 0.38%   |
| Budgie     | 1         | 0.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 201       | 78.82%  |
| Wayland | 35        | 13.73%  |
| Unknown | 16        | 6.27%   |
| Tty     | 2         | 0.78%   |
| Web     | 1         | 0.39%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 121       | 47.08%  |
| SDDM    | 47        | 18.29%  |
| GDM     | 35        | 13.62%  |
| KDM     | 19        | 7.39%   |
| TDM     | 12        | 4.67%   |
| GDM3    | 12        | 4.67%   |
| LightDM | 11        | 4.28%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| en_US           | 115       | 44.57%  |
| Unknown         | 59        | 22.87%  |
| et_EE           | 37        | 14.34%  |
| ru_RU           | 25        | 9.69%   |
| en_GB           | 10        | 3.88%   |
| de_DE           | 3         | 1.16%   |
| fr_FR           | 2         | 0.78%   |
| en_DK           | 2         | 0.78%   |
| uk_UA           | 1         | 0.39%   |
| ru_UA           | 1         | 0.39%   |
| pl_PL           | 1         | 0.39%   |
| en_US.iso885915 | 1         | 0.39%   |
| C               | 1         | 0.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 141       | 54.44%  |
| EFI  | 118       | 45.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 188       | 74.02%  |
| Btrfs   | 28        | 11.02%  |
| Unknown | 19        | 7.48%   |
| Overlay | 13        | 5.12%   |
| Xfs     | 3         | 1.18%   |
| Ext3    | 2         | 0.79%   |
| Zfs     | 1         | 0.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 126       | 49.61%  |
| GPT     | 89        | 35.04%  |
| MBR     | 39        | 15.35%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 212       | 82.49%  |
| Yes       | 45        | 17.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 181       | 70.43%  |
| Yes       | 76        | 29.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 50        | 19.76%  |
| ASUSTek Computer    | 38        | 15.02%  |
| Hewlett-Packard     | 36        | 14.23%  |
| Dell                | 29        | 11.46%  |
| MSI                 | 24        | 9.49%   |
| Gigabyte Technology | 22        | 8.7%    |
| Samsung Electronics | 7         | 2.77%   |
| ASRock              | 7         | 2.77%   |
| Intel               | 6         | 2.37%   |
| Acer                | 5         | 1.98%   |
| ECS                 | 3         | 1.19%   |
| Timi                | 2         | 0.79%   |
| Quanta              | 2         | 0.79%   |
| Fujitsu             | 2         | 0.79%   |
| Apple               | 2         | 0.79%   |
| ZOTAC               | 1         | 0.4%    |
| Valve               | 1         | 0.4%    |
| TUXEDO              | 1         | 0.4%    |
| Toshiba             | 1         | 0.4%    |
| Supermicro          | 1         | 0.4%    |
| Prestigio           | 1         | 0.4%    |
| OEM                 | 1         | 0.4%    |
| Notebook            | 1         | 0.4%    |
| mPTech              | 1         | 0.4%    |
| HUAWEI              | 1         | 0.4%    |
| Huanan              | 1         | 0.4%    |
| Getac               | 1         | 0.4%    |
| Fujitsu Siemens     | 1         | 0.4%    |
| Framework           | 1         | 0.4%    |
| Chuwi               | 1         | 0.4%    |
| Alienware           | 1         | 0.4%    |
| ABIT                | 1         | 0.4%    |
| Unknown             | 1         | 0.4%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| ASUS All Series                                       | 3         | 1.19%   |
| Quanta TWH                                            | 2         | 0.79%   |
| MSI MS-7C02                                           | 2         | 0.79%   |
| MSI MS-7758                                           | 2         | 0.79%   |
| Lenovo Y50-70 20378                                   | 2         | 0.79%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2                     | 2         | 0.79%   |
| HP Pavilion Gaming Laptop 15-ec1xxx                   | 2         | 0.79%   |
| HP Pavilion dv7                                       | 2         | 0.79%   |
| HP ENVY Laptop 13-ah0xxx                              | 2         | 0.79%   |
| HP EliteBook 8470p                                    | 2         | 0.79%   |
| HP EliteBook 8460p                                    | 2         | 0.79%   |
| HP EliteBook 840 G2                                   | 2         | 0.79%   |
| Gigabyte X570 AORUS PRO                               | 2         | 0.79%   |
| Gigabyte Q87M-D2H                                     | 2         | 0.79%   |
| Dell Inspiron N5110                                   | 2         | 0.79%   |
| ZOTAC B410                                            | 1         | 0.4%    |
| Valve Jupiter                                         | 1         | 0.4%    |
| TUXEDO Book BA1510                                    | 1         | 0.4%    |
| Toshiba Satellite L855                                | 1         | 0.4%    |
| Timi RedmiBook 16                                     | 1         | 0.4%    |
| Timi RedmiBook 14 II                                  | 1         | 0.4%    |
| Supermicro X10SLH-F/X10SLM+-F                         | 1         | 0.4%    |
| Samsung R410                                          | 1         | 0.4%    |
| Samsung 900X3C/900X3D/900X4C/900X4D                   | 1         | 0.4%    |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D            | 1         | 0.4%    |
| Samsung 770Z5E/780Z5E                                 | 1         | 0.4%    |
| Samsung 535U3C                                        | 1         | 0.4%    |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.4%    |
| Samsung 275E4E/275E5E                                 | 1         | 0.4%    |
| Prestigio PNT10131DEDB                                | 1         | 0.4%    |
| OEM Intel H81                                         | 1         | 0.4%    |
| Notebook W35xSS_370SS                                 | 1         | 0.4%    |
| MSI MS-B90111                                         | 1         | 0.4%    |
| MSI MS-7C91                                           | 1         | 0.4%    |
| MSI MS-7C83                                           | 1         | 0.4%    |
| MSI MS-7C37                                           | 1         | 0.4%    |
| MSI MS-7B98                                           | 1         | 0.4%    |
| MSI MS-7B79                                           | 1         | 0.4%    |
| MSI MS-7B22                                           | 1         | 0.4%    |
| MSI MS-7B18                                           | 1         | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 31        | 12.25%  |
| HP EliteBook        | 13        | 5.14%   |
| HP Pavilion         | 7         | 2.77%   |
| Dell Inspiron       | 7         | 2.77%   |
| Dell Latitude       | 6         | 2.37%   |
| HP Compaq           | 5         | 1.98%   |
| Dell OptiPlex       | 5         | 1.98%   |
| Lenovo IdeaPad      | 4         | 1.58%   |
| Gigabyte X570       | 4         | 1.58%   |
| Dell XPS            | 4         | 1.58%   |
| Dell Precision      | 4         | 1.58%   |
| ASUS PRIME          | 4         | 1.58%   |
| Acer Aspire         | 4         | 1.58%   |
| Lenovo ThinkCentre  | 3         | 1.19%   |
| Lenovo IdeaPadFlex  | 3         | 1.19%   |
| HP ENVY             | 3         | 1.19%   |
| ASUS VivoBook       | 3         | 1.19%   |
| ASUS All            | 3         | 1.19%   |
| Timi RedmiBook      | 2         | 0.79%   |
| Samsung 900X3C      | 2         | 0.79%   |
| Quanta TWH          | 2         | 0.79%   |
| MSI MS-7C02         | 2         | 0.79%   |
| MSI MS-7758         | 2         | 0.79%   |
| Lenovo Y50-70       | 2         | 0.79%   |
| HP ProDesk          | 2         | 0.79%   |
| HP Presario         | 2         | 0.79%   |
| HP OMEN             | 2         | 0.79%   |
| Gigabyte Q87M-D2H   | 2         | 0.79%   |
| Fujitsu LIFEBOOK    | 2         | 0.79%   |
| ASUS ZenBook        | 2         | 0.79%   |
| ASUS TUF            | 2         | 0.79%   |
| ASUS ROG            | 2         | 0.79%   |
| ZOTAC B410          | 1         | 0.4%    |
| Valve Jupiter       | 1         | 0.4%    |
| TUXEDO Book         | 1         | 0.4%    |
| Toshiba Satellite   | 1         | 0.4%    |
| Supermicro X10SLH-F | 1         | 0.4%    |
| Samsung R410        | 1         | 0.4%    |
| Samsung 770Z5E      | 1         | 0.4%    |
| Samsung 535U3C      | 1         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 28        | 11.07%  |
| 2020    | 27        | 10.67%  |
| 2019    | 25        | 9.88%   |
| 2013    | 20        | 7.91%   |
| 2014    | 19        | 7.51%   |
| 2011    | 19        | 7.51%   |
| 2017    | 16        | 6.32%   |
| 2015    | 16        | 6.32%   |
| 2012    | 16        | 6.32%   |
| 2016    | 13        | 5.14%   |
| 2010    | 10        | 3.95%   |
| 2009    | 10        | 3.95%   |
| 2008    | 9         | 3.56%   |
| 2021    | 8         | 3.16%   |
| 2007    | 8         | 3.16%   |
| 2006    | 4         | 1.58%   |
| 2005    | 2         | 0.79%   |
| 2022    | 1         | 0.4%    |
| 2004    | 1         | 0.4%    |
| Unknown | 1         | 0.4%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 143       | 56.52%  |
| Desktop     | 96        | 37.94%  |
| Convertible | 9         | 3.56%   |
| Mini pc     | 3         | 1.19%   |
| All in one  | 1         | 0.4%    |
| Server      | 1         | 0.4%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 237       | 92.94%  |
| Enabled  | 18        | 7.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 253       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 54        | 21.09%  |
| 8.01-16.0   | 52        | 20.31%  |
| 4.01-8.0    | 48        | 18.75%  |
| 3.01-4.0    | 41        | 16.02%  |
| 32.01-64.0  | 29        | 11.33%  |
| 24.01-32.0  | 8         | 3.13%   |
| 2.01-3.0    | 8         | 3.13%   |
| 1.01-2.0    | 8         | 3.13%   |
| 64.01-256.0 | 5         | 1.95%   |
| 0.51-1.0    | 2         | 0.78%   |
| 0.01-0.5    | 1         | 0.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 87        | 31.99%  |
| 2.01-3.0   | 60        | 22.06%  |
| 4.01-8.0   | 47        | 17.28%  |
| 3.01-4.0   | 27        | 9.93%   |
| 0.51-1.0   | 25        | 9.19%   |
| 8.01-16.0  | 17        | 6.25%   |
| 0.01-0.5   | 4         | 1.47%   |
| 24.01-32.0 | 3         | 1.1%    |
| 16.01-24.0 | 2         | 0.74%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 154       | 59.23%  |
| 2      | 59        | 22.69%  |
| 3      | 26        | 10%     |
| 4      | 8         | 3.08%   |
| 6      | 7         | 2.69%   |
| 5      | 3         | 1.15%   |
| 0      | 2         | 0.77%   |
| 7      | 1         | 0.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 155       | 60.78%  |
| Yes       | 100       | 39.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 226       | 88.63%  |
| No        | 29        | 11.37%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 185       | 73.12%  |
| No        | 68        | 26.88%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 148       | 57.81%  |
| No        | 108       | 42.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Estonia | 253       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Tallinn           | 161       | 61.92%  |
| Tartu             | 27        | 10.38%  |
| Pärnu            | 10        | 3.85%   |
| Rapla             | 7         | 2.69%   |
| Rakvere           | 5         | 1.92%   |
| Narva             | 4         | 1.54%   |
| Haapsalu          | 4         | 1.54%   |
| Maardu            | 3         | 1.15%   |
| Vinni             | 2         | 0.77%   |
| Tapa              | 2         | 0.77%   |
| Põlva            | 2         | 0.77%   |
| Paldiski          | 2         | 0.77%   |
| Otepaeae          | 2         | 0.77%   |
| Kohtla-Järve     | 2         | 0.77%   |
| Keila             | 2         | 0.77%   |
| Jõhvi            | 2         | 0.77%   |
| Viljandi          | 1         | 0.38%   |
| Vatla             | 1         | 0.38%   |
| Vaidasoo          | 1         | 0.38%   |
| Türi             | 1         | 0.38%   |
| Tabasalu          | 1         | 0.38%   |
| Sindi             | 1         | 0.38%   |
| Sauga             | 1         | 0.38%   |
| Saku              | 1         | 0.38%   |
| Rae Parish        | 1         | 0.38%   |
| Pohja-Sakala vald | 1         | 0.38%   |
| Paide             | 1         | 0.38%   |
| Laagri            | 1         | 0.38%   |
| Kuressaare        | 1         | 0.38%   |
| Kose              | 1         | 0.38%   |
| Kiviõli          | 1         | 0.38%   |
| Kärdla           | 1         | 0.38%   |
| Kaeina            | 1         | 0.38%   |
| Kadrina           | 1         | 0.38%   |
| Jõgeva           | 1         | 0.38%   |
| Jaerva vald       | 1         | 0.38%   |
| Hiiumaa           | 1         | 0.38%   |
| Haabneeme         | 1         | 0.38%   |
| AEaesmaee         | 1         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 80        | 108    | 21.22%  |
| Seagate                   | 51        | 66     | 13.53%  |
| WDC                       | 44        | 68     | 11.67%  |
| Kingston                  | 29        | 42     | 7.69%   |
| Toshiba                   | 24        | 25     | 6.37%   |
| Hitachi                   | 16        | 19     | 4.24%   |
| SK hynix                  | 14        | 18     | 3.71%   |
| SanDisk                   | 13        | 15     | 3.45%   |
| Crucial                   | 13        | 22     | 3.45%   |
| HGST                      | 12        | 16     | 3.18%   |
| Unknown                   | 10        | 10     | 2.65%   |
| Intel                     | 9         | 11     | 2.39%   |
| A-DATA Technology         | 9         | 15     | 2.39%   |
| Gigabyte Technology       | 4         | 5      | 1.06%   |
| China                     | 4         | 4      | 1.06%   |
| Transcend                 | 3         | 5      | 0.8%    |
| Patriot                   | 3         | 3      | 0.8%    |
| Micron Technology         | 3         | 3      | 0.8%    |
| KingSpec                  | 3         | 4      | 0.8%    |
| Apacer                    | 3         | 3      | 0.8%    |
| Maxtor                    | 2         | 2      | 0.53%   |
| Lenovo                    | 2         | 2      | 0.53%   |
| Fujitsu                   | 2         | 2      | 0.53%   |
| Corsair                   | 2         | 2      | 0.53%   |
| Apple                     | 2         | 2      | 0.53%   |
| XPG                       | 1         | 1      | 0.27%   |
| Team                      | 1         | 2      | 0.27%   |
| Silicon Motion            | 1         | 2      | 0.27%   |
| PNY                       | 1         | 1      | 0.27%   |
| Plextor                   | 1         | 1      | 0.27%   |
| Phison Electronics        | 1         | 1      | 0.27%   |
| Phison                    | 1         | 1      | 0.27%   |
| Micron/Crucial Technology | 1         | 1      | 0.27%   |
| LITEONIT                  | 1         | 1      | 0.27%   |
| Lexar                     | 1         | 1      | 0.27%   |
| KIOXIA                    | 1         | 2      | 0.27%   |
| Intenso                   | 1         | 1      | 0.27%   |
| Integral                  | 1         | 1      | 0.27%   |
| Inateck                   | 1         | 1      | 0.27%   |
| i-FlashDisk               | 1         | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB            | 6         | 1.43%   |
| Samsung NVMe SSD Drive 1TB           | 6         | 1.43%   |
| Seagate ST2000DM008-2FR102 2TB       | 4         | 0.95%   |
| Samsung NVMe SSD Drive 512GB         | 4         | 0.95%   |
| Samsung HD103SJ 1TB                  | 4         | 0.95%   |
| Kingston SA400S37240G 240GB SSD      | 4         | 0.95%   |
| HGST HTS541010A9E680 1TB             | 4         | 0.95%   |
| SK hynix NVMe SSD Drive 256GB        | 3         | 0.72%   |
| Seagate ST500LT012-9WS142 500GB      | 3         | 0.72%   |
| Seagate ST500LM021-1KJ152 500GB      | 3         | 0.72%   |
| Seagate ST1000DM010-2EP102 1TB       | 3         | 0.72%   |
| Samsung SSD 970 EVO Plus 500GB       | 3         | 0.72%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 0.72%   |
| Samsung SSD 960 PRO 512GB            | 3         | 0.72%   |
| Samsung SSD 860 EVO 250GB            | 3         | 0.72%   |
| Samsung SSD 850 EVO 500GB            | 3         | 0.72%   |
| Samsung MZ7TY128HDHP-000L1 128GB SSD | 3         | 0.72%   |
| Kingston SV300S37A120G 120GB SSD     | 3         | 0.72%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 0.72%   |
| HGST HTS721010A9E630 1TB             | 3         | 0.72%   |
| Crucial CT500MX500SSD1 500GB         | 3         | 0.72%   |
| A-DATA SX8200PNP 512GB               | 3         | 0.72%   |
| WDC WD10EADS-00M2B0 1TB              | 2         | 0.48%   |
| Unknown MMC Card  16GB               | 2         | 0.48%   |
| Unknown ArtisanTribute-512GB         | 2         | 0.48%   |
| Toshiba NVMe SSD Drive 512GB         | 2         | 0.48%   |
| Toshiba MQ01ABF050 500GB             | 2         | 0.48%   |
| Toshiba HDWD130 3TB                  | 2         | 0.48%   |
| SK hynix NVMe SSD Drive 512GB        | 2         | 0.48%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 0.48%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 0.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.48%   |
| Seagate ST1000DM003-1SB102 1TB       | 2         | 0.48%   |
| Seagate ST1000DM003-1ER162 1TB       | 2         | 0.48%   |
| SanDisk SD8SBAT256G1122 256GB SSD    | 2         | 0.48%   |
| SanDisk SD7SB3Q128G1001 128GB SSD    | 2         | 0.48%   |
| Samsung SSD 860 QVO 1TB              | 2         | 0.48%   |
| Samsung SSD 860 EVO 500GB            | 2         | 0.48%   |
| Samsung SSD 860 EVO 1TB              | 2         | 0.48%   |
| Samsung SSD 850 PRO 256GB            | 2         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 50        | 65     | 34.48%  |
| WDC                 | 35        | 52     | 24.14%  |
| Hitachi             | 16        | 19     | 11.03%  |
| Toshiba             | 14        | 14     | 9.66%   |
| Samsung Electronics | 12        | 14     | 8.28%   |
| HGST                | 12        | 16     | 8.28%   |
| Maxtor              | 2         | 2      | 1.38%   |
| Fujitsu             | 2         | 2      | 1.38%   |
| Unknown             | 1         | 1      | 0.69%   |
| Apple               | 1         | 1      | 0.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 45        | 54     | 30.41%  |
| Kingston            | 23        | 32     | 15.54%  |
| Crucial             | 13        | 22     | 8.78%   |
| SanDisk             | 11        | 13     | 7.43%   |
| WDC                 | 7         | 10     | 4.73%   |
| A-DATA Technology   | 7         | 12     | 4.73%   |
| SK hynix            | 4         | 4      | 2.7%    |
| China               | 4         | 4      | 2.7%    |
| Transcend           | 3         | 5      | 2.03%   |
| Toshiba             | 3         | 4      | 2.03%   |
| Patriot             | 3         | 3      | 2.03%   |
| Micron Technology   | 3         | 3      | 2.03%   |
| KingSpec            | 3         | 4      | 2.03%   |
| Intel               | 3         | 4      | 2.03%   |
| Apacer              | 3         | 3      | 2.03%   |
| Gigabyte Technology | 2         | 3      | 1.35%   |
| Corsair             | 2         | 2      | 1.35%   |
| Team                | 1         | 2      | 0.68%   |
| Plextor             | 1         | 1      | 0.68%   |
| LITEONIT            | 1         | 1      | 0.68%   |
| Lexar               | 1         | 1      | 0.68%   |
| Intenso             | 1         | 1      | 0.68%   |
| Integral            | 1         | 1      | 0.68%   |
| i-FlashDisk         | 1         | 1      | 0.68%   |
| ASMT                | 1         | 1      | 0.68%   |
| Apple               | 1         | 1      | 0.68%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 121       | 192    | 36.56%  |
| HDD     | 119       | 186    | 35.95%  |
| NVMe    | 77        | 103    | 23.26%  |
| MMC     | 8         | 8      | 2.42%   |
| Unknown | 6         | 7      | 1.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 197       | 371    | 66.55%  |
| NVMe | 77        | 103    | 26.01%  |
| SAS  | 14        | 14     | 4.73%   |
| MMC  | 8         | 8      | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 161       | 243    | 61.45%  |
| 0.51-1.0   | 67        | 88     | 25.57%  |
| 1.01-2.0   | 18        | 24     | 6.87%   |
| 3.01-4.0   | 5         | 5      | 1.91%   |
| 2.01-3.0   | 5         | 12     | 1.91%   |
| 4.01-10.0  | 5         | 5      | 1.91%   |
| 10.01-20.0 | 1         | 1      | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 78        | 29.55%  |
| 251-500        | 55        | 20.83%  |
| 501-1000       | 29        | 10.98%  |
| 1-20           | 27        | 10.23%  |
| 1001-2000      | 23        | 8.71%   |
| 51-100         | 17        | 6.44%   |
| More than 3000 | 14        | 5.3%    |
| Unknown        | 8         | 3.03%   |
| 21-50          | 7         | 2.65%   |
| 2001-3000      | 6         | 2.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 111       | 41.26%  |
| 21-50          | 39        | 14.5%   |
| 101-250        | 35        | 13.01%  |
| 51-100         | 27        | 10.04%  |
| 251-500        | 16        | 5.95%   |
| 501-1000       | 16        | 5.95%   |
| More than 3000 | 9         | 3.35%   |
| Unknown        | 8         | 2.97%   |
| 1001-2000      | 7         | 2.6%    |
| 2001-3000      | 1         | 0.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Crucial CT128MX100SSD1 128GB                        | 2         | 3      | 5.26%   |
| WDC WD60EFRX-68MYMN1 6TB                            | 1         | 1      | 2.63%   |
| WDC WD5002AALX-00J37A0 500GB                        | 1         | 1      | 2.63%   |
| WDC WD5000BPVT-00HXZT1 500GB                        | 1         | 1      | 2.63%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 1         | 1      | 2.63%   |
| WDC WD2500BEVT-80A23T0 250GB                        | 1         | 1      | 2.63%   |
| WDC WD20EZRX-00DC0B0 2TB                            | 1         | 2      | 2.63%   |
| WDC WD20EARX-00PASB0 2TB                            | 1         | 1      | 2.63%   |
| WDC WD10PURX-64E5EY0 1TB                            | 1         | 1      | 2.63%   |
| WDC WD10EAVS-00D7B1 1TB                             | 1         | 1      | 2.63%   |
| WDC WD10EADS-00M2B0 1TB                             | 1         | 2      | 2.63%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD            | 1         | 2      | 2.63%   |
| Seagate ST98823AS 80GB                              | 1         | 1      | 2.63%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 2.63%   |
| Seagate ST9160412AS 160GB                           | 1         | 1      | 2.63%   |
| Seagate ST750LX003-1AC154 752GB                     | 1         | 1      | 2.63%   |
| Seagate ST500DM002-1BD142 500GB                     | 1         | 1      | 2.63%   |
| Seagate ST340016A 40GB                              | 1         | 2      | 2.63%   |
| Seagate ST320LT012-9WS14C 320GB                     | 1         | 1      | 2.63%   |
| Seagate ST31000528AS 1TB                            | 1         | 1      | 2.63%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 2.63%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1      | 2.63%   |
| Samsung Electronics SSD 840 PRO Series 128GB        | 1         | 1      | 2.63%   |
| Samsung Electronics SP0802N 80GB                    | 1         | 1      | 2.63%   |
| Samsung Electronics HD642JJ 640GB                   | 1         | 1      | 2.63%   |
| Samsung Electronics HD501LJ 500GB                   | 1         | 1      | 2.63%   |
| Samsung Electronics HD103SJ 1TB                     | 1         | 1      | 2.63%   |
| Patriot P210 256GB SSD                              | 1         | 1      | 2.63%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 2.63%   |
| Maxtor STM3250310AS 250GB                           | 1         | 1      | 2.63%   |
| Kingston RBU-SNS8152S3256GG2 256GB SSD              | 1         | 1      | 2.63%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 1      | 2.63%   |
| Hitachi HDS721680PLA380 82GB                        | 1         | 1      | 2.63%   |
| Hitachi HDS721010DLE630 1TB                         | 1         | 1      | 2.63%   |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 2.63%   |
| Fujitsu MHT2040AH PL 40GB                           | 1         | 1      | 2.63%   |
| Crucial CT480M500SSD3 480GB                         | 1         | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 27.78%  |
| WDC                 | 9         | 12     | 25%     |
| Samsung Electronics | 4         | 5      | 11.11%  |
| Hitachi             | 3         | 3      | 8.33%   |
| Crucial             | 3         | 4      | 8.33%   |
| Toshiba             | 1         | 2      | 2.78%   |
| Patriot             | 1         | 1      | 2.78%   |
| Micron Technology   | 1         | 1      | 2.78%   |
| Maxtor              | 1         | 1      | 2.78%   |
| Kingston            | 1         | 1      | 2.78%   |
| HGST                | 1         | 1      | 2.78%   |
| Fujitsu             | 1         | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 35.71%  |
| WDC                 | 9         | 12     | 32.14%  |
| Samsung Electronics | 3         | 4      | 10.71%  |
| Hitachi             | 3         | 3      | 10.71%  |
| Maxtor              | 1         | 1      | 3.57%   |
| HGST                | 1         | 1      | 3.57%   |
| Fujitsu             | 1         | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 33     | 77.14%  |
| SSD  | 8         | 10     | 22.86%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 134       | 256    | 47.86%  |
| Works    | 111       | 196    | 39.64%  |
| Malfunc  | 34        | 43     | 12.14%  |
| Failed   | 1         | 1      | 0.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 174       | 53.54%  |
| AMD                          | 51        | 15.69%  |
| Samsung Electronics          | 33        | 10.15%  |
| SK hynix                     | 10        | 3.08%   |
| SanDisk                      | 8         | 2.46%   |
| Kingston Technology Company  | 7         | 2.15%   |
| Marvell Technology Group     | 6         | 1.85%   |
| Toshiba America Info Systems | 5         | 1.54%   |
| Nvidia                       | 5         | 1.54%   |
| Phison Electronics           | 4         | 1.23%   |
| ADATA Technology             | 4         | 1.23%   |
| VIA Technologies             | 3         | 0.92%   |
| KIOXIA                       | 3         | 0.92%   |
| ASMedia Technology           | 3         | 0.92%   |
| Silicon Motion               | 2         | 0.62%   |
| Lenovo                       | 2         | 0.62%   |
| JMicron Technology           | 2         | 0.62%   |
| Silicon Image                | 1         | 0.31%   |
| Micron/Crucial Technology    | 1         | 0.31%   |
| Adaptec                      | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 35        | 9.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 22        | 5.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 22        | 5.91%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 14        | 3.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 3.49%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 2.42%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 8         | 2.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 1.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 1.88%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 1.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 1.88%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 1.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 6         | 1.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 6         | 1.61%   |
| AMD 400 Series Chipset SATA Controller                                         | 6         | 1.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.34%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 1.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 1.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 1.34%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5         | 1.34%   |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 1.34%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 1.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 4         | 1.08%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 4         | 1.08%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 0.81%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 3         | 0.81%   |
| SK hynix Non-Volatile memory controller                                        | 3         | 0.81%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 0.81%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 0.81%   |
| Kingston Company A2000 NVMe SSD                                                | 3         | 0.81%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 0.81%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 0.81%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 0.81%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 201       | 61.28%  |
| NVMe | 79        | 24.09%  |
| IDE  | 38        | 11.59%  |
| RAID | 9         | 2.74%   |
| SCSI | 1         | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 190       | 75.1%   |
| AMD                   | 62        | 24.51%  |
| Marvell Semiconductor | 1         | 0.4%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz                                   | 6         | 2.37%   |
| Intel Core i7-8565U CPU @ 1.80GHz                                   | 4         | 1.58%   |
| Intel Core i5-2520M CPU @ 2.50GHz                                   | 4         | 1.58%   |
| AMD Ryzen 7 3700X 8-Core Processor                                  | 4         | 1.58%   |
| Intel Core i7-8550U CPU @ 1.80GHz                                   | 3         | 1.19%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz                                  | 3         | 1.19%   |
| Intel Core i5-7300U CPU @ 2.60GHz                                   | 3         | 1.19%   |
| Intel Core i3-4130 CPU @ 3.40GHz                                    | 3         | 1.19%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz                                | 3         | 1.19%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz                             | 3         | 1.19%   |
| AMD Ryzen 7 4700U with Radeon Graphics                              | 3         | 1.19%   |
| AMD Ryzen 5 4500U with Radeon Graphics                              | 3         | 1.19%   |
| AMD Ryzen 5 3600 6-Core Processor                                   | 3         | 1.19%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz                                 | 2         | 0.79%   |
| Intel Core i7-7700 CPU @ 3.60GHz                                    | 2         | 0.79%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz                                  | 2         | 0.79%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz                                  | 2         | 0.79%   |
| Intel Core i7-5600U CPU @ 2.60GHz                                   | 2         | 0.79%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz                                  | 2         | 0.79%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz                                  | 2         | 0.79%   |
| Intel Core i7-4500U CPU @ 1.80GHz                                   | 2         | 0.79%   |
| Intel Core i7-2620M CPU @ 2.70GHz                                   | 2         | 0.79%   |
| Intel Core i7-10750H CPU @ 2.60GHz                                  | 2         | 0.79%   |
| Intel Core i7-10510U CPU @ 1.80GHz                                  | 2         | 0.79%   |
| Intel Core i5-9600K CPU @ 3.70GHz                                   | 2         | 0.79%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz                                  | 2         | 0.79%   |
| Intel Core i5-5200U CPU @ 2.20GHz                                   | 2         | 0.79%   |
| Intel Core i5-4590 CPU @ 3.30GHz                                    | 2         | 0.79%   |
| Intel Core i5-3320M CPU @ 2.60GHz                                   | 2         | 0.79%   |
| Intel Core i5-2500 CPU @ 3.30GHz                                    | 2         | 0.79%   |
| Intel Core i3-6006U CPU @ 2.00GHz                                   | 2         | 0.79%   |
| Intel Core i3-3217U CPU @ 1.80GHz                                   | 2         | 0.79%   |
| Intel Core i3-2350M CPU @ 2.30GHz                                   | 2         | 0.79%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz                                | 2         | 0.79%   |
| AMD Ryzen 9 3900X 12-Core Processor                                 | 2         | 0.79%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics                          | 2         | 0.79%   |
| AMD Ryzen 5 4600H with Radeon Graphics                              | 2         | 0.79%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx                       | 2         | 0.79%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+                          | 2         | 0.79%   |
| Marvell Semiconductor Marvell Armada 370/XP (Device Tree) Processor | 1         | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 62        | 24.51%  |
| Intel Core i7                  | 55        | 21.74%  |
| Intel Core i3                  | 18        | 7.11%   |
| AMD Ryzen 5                    | 16        | 6.32%   |
| AMD Ryzen 7                    | 13        | 5.14%   |
| Intel Core 2 Duo               | 12        | 4.74%   |
| Intel Celeron                  | 11        | 4.35%   |
| Other                          | 7         | 2.77%   |
| Intel Pentium                  | 7         | 2.77%   |
| Intel Xeon                     | 4         | 1.58%   |
| AMD Ryzen 9                    | 4         | 1.58%   |
| AMD Ryzen 7 PRO                | 4         | 1.58%   |
| AMD Phenom II X4               | 4         | 1.58%   |
| AMD Athlon 64 X2               | 4         | 1.58%   |
| Intel Core i9                  | 3         | 1.19%   |
| Intel Atom                     | 3         | 1.19%   |
| Intel Pentium M                | 2         | 0.79%   |
| Intel Celeron Dual-Core        | 2         | 0.79%   |
| AMD FX                         | 2         | 0.79%   |
| AMD A10                        | 2         | 0.79%   |
| Intel Pentium Gold             | 1         | 0.4%    |
| Intel Pentium Dual-Core        | 1         | 0.4%    |
| Intel Pentium Dual             | 1         | 0.4%    |
| Intel Pentium D                | 1         | 0.4%    |
| Intel Pentium 4                | 1         | 0.4%    |
| Intel Core 2                   | 1         | 0.4%    |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.4%    |
| AMD Ryzen 3 PRO                | 1         | 0.4%    |
| AMD Ryzen 3                    | 1         | 0.4%    |
| AMD Phenom II X6               | 1         | 0.4%    |
| AMD E2                         | 1         | 0.4%    |
| AMD E                          | 1         | 0.4%    |
| AMD C-60                       | 1         | 0.4%    |
| AMD Athlon XP                  | 1         | 0.4%    |
| AMD Athlon II Dual-Core        | 1         | 0.4%    |
| AMD A8                         | 1         | 0.4%    |
| AMD A6                         | 1         | 0.4%    |
| AMD A4                         | 1         | 0.4%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 106       | 41.9%   |
| 4       | 83        | 32.81%  |
| 6       | 26        | 10.28%  |
| 8       | 20        | 7.91%   |
| 1       | 9         | 3.56%   |
| 12      | 3         | 1.19%   |
| Unknown | 3         | 1.19%   |
| 16      | 1         | 0.4%    |
| 14      | 1         | 0.4%    |
| 3       | 1         | 0.4%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 253       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 168       | 66.14%  |
| 1       | 83        | 32.68%  |
| Unknown | 3         | 1.18%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 247       | 97.24%  |
| Unknown        | 4         | 1.57%   |
| 32-bit         | 3         | 1.18%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 54        | 20.69%  |
| 0x306c3    | 21        | 8.05%   |
| 0x306a9    | 18        | 6.9%    |
| 0x206a7    | 16        | 6.13%   |
| 0x906e9    | 9         | 3.45%   |
| 0x806ea    | 8         | 3.07%   |
| 0x1067a    | 7         | 2.68%   |
| 0x08600106 | 7         | 2.68%   |
| 0x906ea    | 6         | 2.3%    |
| 0x40651    | 6         | 2.3%    |
| 0x306d4    | 6         | 2.3%    |
| 0x08701021 | 6         | 2.3%    |
| 0x806ec    | 5         | 1.92%   |
| 0x806e9    | 5         | 1.92%   |
| 0x6fb      | 5         | 1.92%   |
| 0x506e3    | 5         | 1.92%   |
| 0x08701013 | 5         | 1.92%   |
| 0x6fd      | 4         | 1.53%   |
| 0x20655    | 4         | 1.53%   |
| 0xa0652    | 3         | 1.15%   |
| 0x806c1    | 3         | 1.15%   |
| 0x406e3    | 3         | 1.15%   |
| 0x08108102 | 3         | 1.15%   |
| 0x05000119 | 3         | 1.15%   |
| 0xa0655    | 2         | 0.77%   |
| 0x906ed    | 2         | 0.77%   |
| 0x706a1    | 2         | 0.77%   |
| 0x6d8      | 2         | 0.77%   |
| 0x30678    | 2         | 0.77%   |
| 0x08600103 | 2         | 0.77%   |
| 0x0810100b | 2         | 0.77%   |
| 0x08001138 | 2         | 0.77%   |
| 0x06003106 | 2         | 0.77%   |
| 0x06000852 | 2         | 0.77%   |
| 0x010000db | 2         | 0.77%   |
| 0xf64      | 1         | 0.38%   |
| 0xf4a      | 1         | 0.38%   |
| 0xa0671    | 1         | 0.38%   |
| 0xa0653    | 1         | 0.38%   |
| 0x906eb    | 1         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 46        | 18.18%  |
| Haswell         | 33        | 13.04%  |
| Zen 2           | 25        | 9.88%   |
| SandyBridge     | 20        | 7.91%   |
| IvyBridge       | 20        | 7.91%   |
| Skylake         | 12        | 4.74%   |
| Core            | 11        | 4.35%   |
| Penryn          | 8         | 3.16%   |
| Westmere        | 7         | 2.77%   |
| Broadwell       | 7         | 2.77%   |
| K10             | 6         | 2.37%   |
| CometLake       | 6         | 2.37%   |
| Zen             | 5         | 1.98%   |
| Zen+            | 4         | 1.58%   |
| Zen 3           | 4         | 1.58%   |
| TigerLake       | 4         | 1.58%   |
| Silvermont      | 4         | 1.58%   |
| K8 Hammer       | 4         | 1.58%   |
| Steamroller     | 3         | 1.19%   |
| Piledriver      | 3         | 1.19%   |
| Goldmont plus   | 3         | 1.19%   |
| Bobcat          | 3         | 1.19%   |
| Unknown         | 3         | 1.19%   |
| P6              | 2         | 0.79%   |
| NetBurst        | 2         | 0.79%   |
| Icelake         | 2         | 0.79%   |
| Bonnell         | 2         | 0.79%   |
| K8 & K10 hybrid | 1         | 0.4%    |
| K6              | 1         | 0.4%    |
| Goldmont        | 1         | 0.4%    |
| Excavator       | 1         | 0.4%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 149       | 46.86%  |
| Nvidia            | 106       | 33.33%  |
| AMD               | 61        | 19.18%  |
| VIA Technologies  | 1         | 0.31%   |
| ASPEED Technology | 1         | 0.31%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 14        | 4.29%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 14        | 4.29%   |
| AMD Renoir                                                                    | 12        | 3.68%   |
| Intel UHD Graphics 620                                                        | 10        | 3.07%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 9         | 2.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 8         | 2.45%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 8         | 2.45%   |
| Intel HD Graphics 630                                                         | 7         | 2.15%   |
| Intel Core Processor Integrated Graphics Controller                           | 6         | 1.84%   |
| Nvidia GP108M [GeForce MX150]                                                 | 5         | 1.53%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 5         | 1.53%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 5         | 1.53%   |
| Intel HD Graphics 620                                                         | 5         | 1.53%   |
| Intel HD Graphics 5500                                                        | 5         | 1.53%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 5         | 1.53%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 4         | 1.23%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 4         | 1.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 4         | 1.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 4         | 1.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 4         | 1.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 4         | 1.23%   |
| Intel HD Graphics 530                                                         | 4         | 1.23%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 4         | 1.23%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 3         | 0.92%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                            | 3         | 0.92%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 3         | 0.92%   |
| Nvidia GK208B [GeForce GT 710]                                                | 3         | 0.92%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 0.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 0.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 3         | 0.92%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 3         | 0.92%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 0.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 0.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 0.92%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 0.61%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 2         | 0.61%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                         | 2         | 0.61%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 2         | 0.61%   |
| Nvidia TU106 [GeForce RTX 2070]                                               | 2         | 0.61%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                         | 2         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 89        | 35.04%  |
| 1 x Nvidia     | 52        | 20.47%  |
| Intel + Nvidia | 50        | 19.69%  |
| 1 x AMD        | 48        | 18.9%   |
| Intel + AMD    | 7         | 2.76%   |
| AMD + Nvidia   | 3         | 1.18%   |
| 2 x AMD        | 2         | 0.79%   |
| Other          | 1         | 0.39%   |
| 1 x VIA        | 1         | 0.39%   |
| AMD + ASPEED   | 1         | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 182       | 70.27%  |
| Proprietary | 68        | 26.25%  |
| Unknown     | 9         | 3.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 110       | 42.64%  |
| 1.01-2.0   | 49        | 18.99%  |
| 0.01-0.5   | 31        | 12.02%  |
| 3.01-4.0   | 23        | 8.91%   |
| 7.01-8.0   | 16        | 6.2%    |
| 0.51-1.0   | 13        | 5.04%   |
| 5.01-6.0   | 7         | 2.71%   |
| 8.01-16.0  | 6         | 2.33%   |
| 2.01-3.0   | 2         | 0.78%   |
| 4.01-5.0   | 1         | 0.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 35        | 12.07%  |
| Dell                    | 34        | 11.72%  |
| Chimei Innolux          | 33        | 11.38%  |
| AU Optronics            | 29        | 10%     |
| LG Display              | 20        | 6.9%    |
| Goldstar                | 20        | 6.9%    |
| BOE                     | 18        | 6.21%   |
| Hewlett-Packard         | 10        | 3.45%   |
| Chi Mei Optoelectronics | 10        | 3.45%   |
| Philips                 | 8         | 2.76%   |
| AOC                     | 8         | 2.76%   |
| ViewSonic               | 7         | 2.41%   |
| Sharp                   | 7         | 2.41%   |
| Lenovo                  | 7         | 2.41%   |
| BenQ                    | 5         | 1.72%   |
| Sony                    | 3         | 1.03%   |
| PANDA                   | 3         | 1.03%   |
| LG Philips              | 3         | 1.03%   |
| Hitachi                 | 3         | 1.03%   |
| Unknown                 | 2         | 0.69%   |
| RoverScan               | 2         | 0.69%   |
| Fujitsu Siemens         | 2         | 0.69%   |
| Apple                   | 2         | 0.69%   |
| Ancor Communications    | 2         | 0.69%   |
| Acer                    | 2         | 0.69%   |
| Toshiba                 | 1         | 0.34%   |
| Tech Concepts           | 1         | 0.34%   |
| Seiko/Epson             | 1         | 0.34%   |
| Plain Tree Systems      | 1         | 0.34%   |
| LG Electronics          | 1         | 0.34%   |
| Lenovo Group Limited    | 1         | 0.34%   |
| KDB                     | 1         | 0.34%   |
| InfoVision              | 1         | 0.34%   |
| Eizo                    | 1         | 0.34%   |
| CSO                     | 1         | 0.34%   |
| CPT                     | 1         | 0.34%   |
| Belinea                 | 1         | 0.34%   |
| ASUSTek Computer        | 1         | 0.34%   |
| ANX                     | 1         | 0.34%   |
| Unknown                 | 1         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Goldstar LG ULTRAGEAR GSM5B80 2560x1440 600x340mm 27.2-inch               | 3         | 0.98%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 3         | 0.98%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 3         | 0.98%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 3         | 0.98%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 3         | 0.98%   |
| ViewSonic VA703-4Series VSC6A1E 1280x1024 341x274mm 17.2-inch             | 2         | 0.65%   |
| Sony TV SNYDB01 1920x1080 1600x900mm 72.3-inch                            | 2         | 0.65%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 2         | 0.65%   |
| Samsung Electronics S32D850 SAM0BCB 2560x1440 708x398mm 32.0-inch         | 2         | 0.65%   |
| Samsung Electronics S24C650 SAM0B18 1920x1200 518x324mm 24.1-inch         | 2         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch      | 2         | 0.65%   |
| LG Display LCD Monitor LGD0685 1920x1080 309x174mm 14.0-inch              | 2         | 0.65%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                   | 2         | 0.65%   |
| Hitachi HISENSE HEC0030 3840x2160 1095x616mm 49.5-inch                    | 2         | 0.65%   |
| Hewlett-Packard ZR24w HWP2869 1920x1200 518x324mm 24.1-inch               | 2         | 0.65%   |
| Hewlett-Packard 27es HWP3325 1920x1080 598x336mm 27.0-inch                | 2         | 0.65%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                      | 2         | 0.65%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 2         | 0.65%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                         | 2         | 0.65%   |
| Dell U2312HM DEL4073 1920x1080 510x287mm 23.0-inch                        | 2         | 0.65%   |
| Dell P2314H DEL4098 1920x1080 509x286mm 23.0-inch                         | 2         | 0.65%   |
| Dell 2407WFP DELA017 1920x1200 520x330mm 24.2-inch                        | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch           | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch          | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch          | 2         | 0.65%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.65%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 2         | 0.65%   |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch  | 2         | 0.65%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 2         | 0.65%   |
| BOE LCD Monitor BOE077A 1920x1080 294x165mm 13.3-inch                     | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch             | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 2         | 0.65%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                       | 2         | 0.65%   |
| ViewSonic VP2030 SERIES VSC131C 1600x1200 408x306mm 20.1-inch             | 1         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 116       | 42.34%  |
| 1366x768 (WXGA)    | 40        | 14.6%   |
| 3840x2160 (4K)     | 21        | 7.66%   |
| 1280x1024 (SXGA)   | 20        | 7.3%    |
| 1920x1200 (WUXGA)  | 19        | 6.93%   |
| 2560x1440 (QHD)    | 15        | 5.47%   |
| 1600x900 (HD+)     | 12        | 4.38%   |
| 1280x800 (WXGA)    | 9         | 3.28%   |
| 3440x1440          | 6         | 2.19%   |
| 1680x1050 (WSXGA+) | 5         | 1.82%   |
| 2560x1600          | 3         | 1.09%   |
| 1440x900 (WXGA+)   | 3         | 1.09%   |
| 800x1280           | 1         | 0.36%   |
| 2560x1080          | 1         | 0.36%   |
| 2256x1504          | 1         | 0.36%   |
| 1920x540           | 1         | 0.36%   |
| 1600x1200          | 1         | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 70        | 23.81%  |
| 13      | 28        | 9.52%   |
| 24      | 25        | 8.5%    |
| 17      | 24        | 8.16%   |
| 27      | 23        | 7.82%   |
| 14      | 23        | 7.82%   |
| 23      | 17        | 5.78%   |
| 21      | 14        | 4.76%   |
| Unknown | 12        | 4.08%   |
| 12      | 8         | 2.72%   |
| 19      | 6         | 2.04%   |
| 34      | 5         | 1.7%    |
| 31      | 5         | 1.7%    |
| 84      | 4         | 1.36%   |
| 72      | 3         | 1.02%   |
| 25      | 3         | 1.02%   |
| 22      | 3         | 1.02%   |
| 18      | 3         | 1.02%   |
| 54      | 2         | 0.68%   |
| 40      | 2         | 0.68%   |
| 33      | 2         | 0.68%   |
| 32      | 2         | 0.68%   |
| 20      | 2         | 0.68%   |
| 16      | 2         | 0.68%   |
| 65      | 1         | 0.34%   |
| 43      | 1         | 0.34%   |
| 29      | 1         | 0.34%   |
| 26      | 1         | 0.34%   |
| 11      | 1         | 0.34%   |
| 10      | 1         | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 115       | 40.07%  |
| 501-600     | 58        | 20.21%  |
| 201-300     | 27        | 9.41%   |
| 401-500     | 23        | 8.01%   |
| 351-400     | 18        | 6.27%   |
| 601-700     | 12        | 4.18%   |
| Unknown     | 12        | 4.18%   |
| 701-800     | 9         | 3.14%   |
| 1501-2000   | 7         | 2.44%   |
| 1001-1500   | 3         | 1.05%   |
| 801-900     | 2         | 0.7%    |
| 901-1000    | 1         | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 182       | 69.47%  |
| 16/10   | 40        | 15.27%  |
| 5/4     | 16        | 6.11%   |
| Unknown | 10        | 3.82%   |
| 21/9    | 5         | 1.91%   |
| 4/3     | 3         | 1.15%   |
| 6/5     | 2         | 0.76%   |
| 3/2     | 2         | 0.76%   |
| 32/9    | 1         | 0.38%   |
| 0.62    | 1         | 0.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 70        | 23.97%  |
| 201-250        | 38        | 13.01%  |
| 81-90          | 36        | 12.33%  |
| 301-350        | 24        | 8.22%   |
| 251-300        | 19        | 6.51%   |
| 71-80          | 15        | 5.14%   |
| 351-500        | 15        | 5.14%   |
| 141-150        | 15        | 5.14%   |
| 151-200        | 12        | 4.11%   |
| Unknown        | 12        | 4.11%   |
| More than 1000 | 10        | 3.42%   |
| 121-130        | 10        | 3.42%   |
| 61-70          | 8         | 2.74%   |
| 501-1000       | 3         | 1.03%   |
| 111-120        | 2         | 0.68%   |
| 51-60          | 1         | 0.34%   |
| 41-50          | 1         | 0.34%   |
| 131-140        | 1         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 96        | 33.92%  |
| 121-160       | 80        | 28.27%  |
| 101-120       | 65        | 22.97%  |
| 161-240       | 20        | 7.07%   |
| Unknown       | 12        | 4.24%   |
| 1-50          | 6         | 2.12%   |
| More than 240 | 4         | 1.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 197       | 75.77%  |
| 2     | 46        | 17.69%  |
| 3     | 8         | 3.08%   |
| 0     | 8         | 3.08%   |
| 4     | 1         | 0.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 131       | 35.31%  |
| Realtek Semiconductor             | 126       | 33.96%  |
| Qualcomm Atheros                  | 40        | 10.78%  |
| Broadcom                          | 12        | 3.23%   |
| TP-Link                           | 8         | 2.16%   |
| Ralink                            | 7         | 1.89%   |
| Nvidia                            | 5         | 1.35%   |
| MediaTek                          | 4         | 1.08%   |
| Ralink Technology                 | 3         | 0.81%   |
| Marvell Technology Group          | 3         | 0.81%   |
| Hewlett-Packard                   | 3         | 0.81%   |
| FIBOCOM                           | 3         | 0.81%   |
| Ericsson Business Mobile Networks | 3         | 0.81%   |
| Broadcom Limited                  | 3         | 0.81%   |
| Sierra Wireless                   | 2         | 0.54%   |
| Microsoft                         | 2         | 0.54%   |
| Lenovo                            | 2         | 0.54%   |
| Huawei Technologies               | 2         | 0.54%   |
| D-Link System                     | 2         | 0.54%   |
| VIA Technologies                  | 1         | 0.27%   |
| Van Ooijen Technische Informatica | 1         | 0.27%   |
| Samsung Electronics               | 1         | 0.27%   |
| Qualcomm Atheros Communications   | 1         | 0.27%   |
| JMicron Technology                | 1         | 0.27%   |
| DisplayLink                       | 1         | 0.27%   |
| D-Link                            | 1         | 0.27%   |
| ASUSTek Computer                  | 1         | 0.27%   |
| ASIX Electronics                  | 1         | 0.27%   |
| Aquantia                          | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 79        | 17.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 4.44%   |
| Intel Wireless 8265 / 8275                                        | 12        | 2.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 2.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 2.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 10        | 2.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 2%      |
| Intel Wi-Fi 6 AX200                                               | 8         | 1.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.56%   |
| Intel Wireless 7265                                               | 7         | 1.56%   |
| Intel Wireless 7260                                               | 7         | 1.56%   |
| Intel I211 Gigabit Network Connection                             | 7         | 1.56%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 1.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 5         | 1.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.11%   |
| Intel Wireless 3165                                               | 5         | 1.11%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 1.11%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 0.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.89%   |
| Intel Wireless 8260                                               | 4         | 0.89%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 0.89%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.89%   |
| Intel 82566MM Gigabit Network Connection                          | 4         | 0.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.67%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.67%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.67%   |
| Intel Wireless 3160                                               | 3         | 0.67%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 3         | 0.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.67%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.67%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.67%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 99        | 50.25%  |
| Qualcomm Atheros                | 29        | 14.72%  |
| Realtek Semiconductor           | 28        | 14.21%  |
| Broadcom                        | 8         | 4.06%   |
| TP-Link                         | 7         | 3.55%   |
| Ralink                          | 7         | 3.55%   |
| Ralink Technology               | 3         | 1.52%   |
| MediaTek                        | 3         | 1.52%   |
| FIBOCOM                         | 3         | 1.52%   |
| Sierra Wireless                 | 2         | 1.02%   |
| Microsoft                       | 2         | 1.02%   |
| Broadcom Limited                | 2         | 1.02%   |
| Qualcomm Atheros Communications | 1         | 0.51%   |
| Hewlett-Packard                 | 1         | 0.51%   |
| D-Link System                   | 1         | 0.51%   |
| D-Link                          | 1         | 0.51%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 12        | 6.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 5.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 5.03%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 4.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 3.52%   |
| Intel Wireless 7265                                                     | 7         | 3.52%   |
| Intel Wireless 7260                                                     | 7         | 3.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.51%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 2.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 2.51%   |
| Intel Wireless 3165                                                     | 5         | 2.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 2.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 2.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 2.01%   |
| Intel Wireless 8260                                                     | 4         | 2.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.51%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.51%   |
| Intel Wireless 3160                                                     | 3         | 1.51%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.51%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.51%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.51%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.51%   |
| FIBOCOM L830-EB                                                         | 3         | 1.51%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 2         | 1.01%   |
| TP-Link Archer T4U ver.3                                                | 2         | 1.01%   |
| TP-Link 802.11n NIC                                                     | 2         | 1.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.01%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.01%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.01%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.01%   |
| Ralink RT2500 Wireless 802.11bg                                         | 2         | 1.01%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.01%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                      | 2         | 1.01%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.01%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.01%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.01%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 1.01%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.01%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 111       | 47.03%  |
| Intel                    | 80        | 33.9%   |
| Qualcomm Atheros         | 17        | 7.2%    |
| Broadcom                 | 6         | 2.54%   |
| Nvidia                   | 5         | 2.12%   |
| Marvell Technology Group | 3         | 1.27%   |
| Lenovo                   | 2         | 0.85%   |
| VIA Technologies         | 1         | 0.42%   |
| TP-Link                  | 1         | 0.42%   |
| Samsung Electronics      | 1         | 0.42%   |
| MediaTek                 | 1         | 0.42%   |
| JMicron Technology       | 1         | 0.42%   |
| Hewlett-Packard          | 1         | 0.42%   |
| DisplayLink              | 1         | 0.42%   |
| D-Link System            | 1         | 0.42%   |
| Broadcom Limited         | 1         | 0.42%   |
| ASUSTek Computer         | 1         | 0.42%   |
| ASIX Electronics         | 1         | 0.42%   |
| Aquantia                 | 1         | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 79        | 32.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 8.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 4.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 3.72%   |
| Intel I211 Gigabit Network Connection                             | 7         | 2.89%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 2.89%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 2.07%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 2.07%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.65%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 1.65%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.65%   |
| Intel 82566MM Gigabit Network Connection                          | 4         | 1.65%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 1.24%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.24%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.24%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.24%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.24%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.83%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.83%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.83%   |
| Nvidia CK804 Ethernet Controller                                  | 2         | 0.83%   |
| Lenovo ThinkPad TBT3 LAN                                          | 2         | 0.83%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.83%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.83%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.83%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.83%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.41%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.41%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.41%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.41%   |
| Nvidia nForce2 Ethernet Controller                                | 1         | 0.41%   |
| Nvidia MCP77 Ethernet                                             | 1         | 0.41%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.41%   |
| MediaTek TECNO Pouvoir 3 Air                                      | 1         | 0.41%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 225       | 53.7%   |
| WiFi     | 185       | 44.15%  |
| Modem    | 9         | 2.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 143       | 55.64%  |
| Ethernet | 114       | 44.36%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 136       | 53.75%  |
| 1     | 106       | 41.9%   |
| 0     | 6         | 2.37%   |
| 3     | 4         | 1.58%   |
| 6     | 1         | 0.4%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 226       | 88.28%  |
| Yes  | 30        | 11.72%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 69        | 46.31%  |
| Cambridge Silicon Radio         | 16        | 10.74%  |
| Realtek Semiconductor           | 13        | 8.72%   |
| Qualcomm Atheros Communications | 12        | 8.05%   |
| Broadcom                        | 11        | 7.38%   |
| IMC Networks                    | 8         | 5.37%   |
| Hewlett-Packard                 | 4         | 2.68%   |
| Realtek                         | 3         | 2.01%   |
| ASUSTek Computer                | 3         | 2.01%   |
| Apple                           | 2         | 1.34%   |
| TP-Link                         | 1         | 0.67%   |
| Toshiba                         | 1         | 0.67%   |
| Ralink                          | 1         | 0.67%   |
| Lite-On Technology              | 1         | 0.67%   |
| Integrated System Solution      | 1         | 0.67%   |
| Foxconn / Hon Hai               | 1         | 0.67%   |
| Dell                            | 1         | 0.67%   |
| Askey Computer                  | 1         | 0.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 37        | 24.83%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 16        | 10.74%  |
| Realtek Bluetooth Radio                               | 9         | 6.04%   |
| Intel AX201 Bluetooth                                 | 8         | 5.37%   |
| Intel AX200 Bluetooth                                 | 7         | 4.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 6         | 4.03%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 6         | 4.03%   |
| IMC Networks Bluetooth Device                         | 5         | 3.36%   |
| Realtek Bluetooth Radio                               | 3         | 2.01%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3         | 2.01%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 3         | 2.01%   |
| HP Broadcom 2070 Bluetooth Combo                      | 3         | 2.01%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]      | 3         | 2.01%   |
| Realtek RTL8723B Bluetooth                            | 2         | 1.34%   |
| Qualcomm Atheros  Bluetooth Device                    | 2         | 1.34%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 2         | 1.34%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 2         | 1.34%   |
| Intel AX210 Bluetooth                                 | 2         | 1.34%   |
| Broadcom BCM43142 Bluetooth 4.0                       | 2         | 1.34%   |
| Broadcom BCM2045B (BDC-2.1)                           | 2         | 1.34%   |
| Broadcom BCM2045 Bluetooth                            | 2         | 1.34%   |
| ASUS ASUS USB-BT500                                   | 2         | 1.34%   |
| Apple Bluetooth Host Controller                       | 2         | 1.34%   |
| TP-Link TPuLink UB500 Adapter                         | 1         | 0.67%   |
| Toshiba Bluetooth USB Host Controller                 | 1         | 0.67%   |
| Realtek RTL8821A Bluetooth                            | 1         | 0.67%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 0.67%   |
| Ralink RT3290 Bluetooth                               | 1         | 0.67%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 0.67%   |
| Qualcomm Atheros AR3012 Bluetooth                     | 1         | 0.67%   |
| Lite-On Bluetooth Device                              | 1         | 0.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1         | 0.67%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.67%   |
| IMC Networks Bluetooth Radio                          | 1         | 0.67%   |
| IMC Networks BCM20702A0                               | 1         | 0.67%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 1         | 0.67%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 1         | 0.67%   |
| Foxconn / Hon Hai Wireless_Device                     | 1         | 0.67%   |
| Dell BCM20702A0 Bluetooth Module                      | 1         | 0.67%   |
| Broadcom HP Portable SoftSailing                      | 1         | 0.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 185       | 51.1%   |
| AMD                     | 72        | 19.89%  |
| Nvidia                  | 66        | 18.23%  |
| C-Media Electronics     | 8         | 2.21%   |
| Razer USA               | 3         | 0.83%   |
| Lenovo                  | 3         | 0.83%   |
| Kingston Technology     | 3         | 0.83%   |
| TerraTec Electronic     | 2         | 0.55%   |
| SteelSeries ApS         | 2         | 0.55%   |
| Realtek Semiconductor   | 2         | 0.55%   |
| Logitech                | 2         | 0.55%   |
| JMTek                   | 2         | 0.55%   |
| Focusrite-Novation      | 2         | 0.55%   |
| VIA Technologies        | 1         | 0.28%   |
| Texas Instruments       | 1         | 0.28%   |
| Syntek                  | 1         | 0.28%   |
| Samson Technologies     | 1         | 0.28%   |
| Roland                  | 1         | 0.28%   |
| Micronas                | 1         | 0.28%   |
| Mark of the Unicorn     | 1         | 0.28%   |
| M-Audio                 | 1         | 0.28%   |
| Creative Labs           | 1         | 0.28%   |
| BEHRINGER International | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 21        | 4.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 21        | 4.99%   |
| AMD Family 17h/19h HD Audio Controller                                     | 20        | 4.75%   |
| Intel Sunrise Point-LP HD Audio                                            | 18        | 4.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18        | 4.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14        | 3.33%   |
| AMD Starship/Matisse HD Audio Controller                                   | 13        | 3.09%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 2.61%   |
| Intel Cannon Lake PCH cAVS                                                 | 10        | 2.38%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 10        | 2.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8         | 1.9%    |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 1.9%    |
| Intel 8 Series HD Audio Controller                                         | 8         | 1.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 1.9%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 8         | 1.9%    |
| Nvidia TU106 High Definition Audio Controller                              | 7         | 1.66%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 1.66%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 1.66%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 1.66%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 1.66%   |
| Nvidia GP104 High Definition Audio Controller                              | 6         | 1.43%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 1.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 1.43%   |
| AMD FCH Azalia Controller                                                  | 6         | 1.43%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.19%   |
| Intel CM238 HD Audio Controller                                            | 5         | 1.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.19%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 1.19%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 0.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 0.95%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.71%   |
| Nvidia GP108 High Definition Audio Controller                              | 3         | 0.71%   |
| Nvidia GP102 HDMI Audio Controller                                         | 3         | 0.71%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 0.71%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3         | 0.71%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3         | 0.71%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.71%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 0.71%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 36        | 20.22%  |
| SK hynix            | 27        | 15.17%  |
| Kingston            | 21        | 11.8%   |
| Unknown             | 18        | 10.11%  |
| Micron Technology   | 18        | 10.11%  |
| G.Skill             | 17        | 9.55%   |
| Crucial             | 13        | 7.3%    |
| Corsair             | 5         | 2.81%   |
| Ramaxel Technology  | 4         | 2.25%   |
| A-DATA Technology   | 3         | 1.69%   |
| Unknown (ABCD)      | 2         | 1.12%   |
| Patriot             | 2         | 1.12%   |
| Elpida              | 2         | 1.12%   |
| Apacer              | 2         | 1.12%   |
| Unifosa             | 1         | 0.56%   |
| Team                | 1         | 0.56%   |
| Silicon Power       | 1         | 0.56%   |
| Nanya Technology    | 1         | 0.56%   |
| ASint Technology    | 1         | 0.56%   |
| AMD                 | 1         | 0.56%   |
| Aeneon              | 1         | 0.56%   |
| Unknown             | 1         | 0.56%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 2.06%   |
| Unknown RAM Module 512MB DIMM SDRAM                              | 2         | 1.03%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 1.03%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.03%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 2         | 1.03%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.03%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.03%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.03%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.03%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.03%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.03%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s              | 2         | 1.03%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 2         | 1.03%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 0.52%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                     | 1         | 0.52%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.52%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 0.52%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR3 1867MT/s           | 1         | 0.52%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                           | 1         | 0.52%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.52%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.52%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.52%   |
| Unknown RAM Module 256MB DIMM                                    | 1         | 0.52%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.52%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.52%   |
| Unknown RAM Module 2048MB DIMM DDR3 800MT/s                      | 1         | 0.52%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.52%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 1         | 0.52%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                      | 1         | 0.52%   |
| Unknown RAM Module 1024MB DIMM                                   | 1         | 0.52%   |
| Unifosa RAM GU332G0AJEPR8H2L 2048MB SODIMM DDR2 667MT/s          | 1         | 0.52%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s              | 1         | 0.52%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                  | 1         | 0.52%   |
| SK hynix RAM Module 8192MB DIMM DDR3 1333MT/s                    | 1         | 0.52%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                     | 1         | 0.52%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2133MT/s                  | 1         | 0.52%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1333MT/s                    | 1         | 0.52%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s            | 1         | 0.52%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 0.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 73        | 48.67%  |
| DDR3    | 49        | 32.67%  |
| DDR2    | 8         | 5.33%   |
| SDRAM   | 7         | 4.67%   |
| Unknown | 5         | 3.33%   |
| LPDDR4  | 4         | 2.67%   |
| LPDDR3  | 2         | 1.33%   |
| DDR     | 2         | 1.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 78        | 52.7%   |
| DIMM         | 63        | 42.57%  |
| Row Of Chips | 7         | 4.73%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 58        | 35.37%  |
| 4096  | 48        | 29.27%  |
| 16384 | 23        | 14.02%  |
| 2048  | 17        | 10.37%  |
| 1024  | 7         | 4.27%   |
| 32768 | 5         | 3.05%   |
| 512   | 5         | 3.05%   |
| 256   | 1         | 0.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 32        | 19.28%  |
| 2667    | 26        | 15.66%  |
| 3200    | 22        | 13.25%  |
| 1333    | 13        | 7.83%   |
| 2400    | 10        | 6.02%   |
| 3600    | 8         | 4.82%   |
| 2133    | 7         | 4.22%   |
| Unknown | 7         | 4.22%   |
| 1334    | 6         | 3.61%   |
| 800     | 4         | 2.41%   |
| 667     | 4         | 2.41%   |
| 1067    | 3         | 1.81%   |
| 4267    | 2         | 1.2%    |
| 4199    | 2         | 1.2%    |
| 3666    | 2         | 1.2%    |
| 3266    | 2         | 1.2%    |
| 2666    | 2         | 1.2%    |
| 1867    | 2         | 1.2%    |
| 4133    | 1         | 0.6%    |
| 3800    | 1         | 0.6%    |
| 3334    | 1         | 0.6%    |
| 3000    | 1         | 0.6%    |
| 2933    | 1         | 0.6%    |
| 2733    | 1         | 0.6%    |
| 1866    | 1         | 0.6%    |
| 1800    | 1         | 0.6%    |
| 1066    | 1         | 0.6%    |
| 975     | 1         | 0.6%    |
| 533     | 1         | 0.6%    |
| 400     | 1         | 0.6%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Seiko Epson                     | 1         | 20%     |
| Samsung Electronics             | 1         | 20%     |
| Konica Minolta                  | 1         | 20%     |
| cab Produkttechnik GmbH & Co KG | 1         | 20%     |
| Brother Industries              | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Seiko Epson TM-T20                       | 1         | 20%     |
| Samsung SCX-3400 Series                  | 1         | 20%     |
| Konica Minolta Printer                   | 1         | 20%     |
| cab Produkttechnik GmbH & Co KG EOS2/300 | 1         | 20%     |
| Brother HL-4140CN series                 | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Seiko Epson Perfection 660 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 31        | 21.23%  |
| Microdia                               | 14        | 9.59%   |
| Realtek Semiconductor                  | 13        | 8.9%    |
| IMC Networks                           | 13        | 8.9%    |
| Acer                                   | 12        | 8.22%   |
| Sunplus Innovation Technology          | 11        | 7.53%   |
| Logitech                               | 11        | 7.53%   |
| Silicon Motion                         | 5         | 3.42%   |
| Lite-On Technology                     | 5         | 3.42%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.42%   |
| Syntek                                 | 4         | 2.74%   |
| Suyin                                  | 4         | 2.74%   |
| Luxvisions Innotech Limited            | 3         | 2.05%   |
| Apple                                  | 3         | 2.05%   |
| Quanta                                 | 2         | 1.37%   |
| Arkmicro Technologies                  | 2         | 1.37%   |
| Z-Star Microelectronics                | 1         | 0.68%   |
| Samsung Electronics                    | 1         | 0.68%   |
| Microsoft                              | 1         | 0.68%   |
| Lenovo                                 | 1         | 0.68%   |
| Importek                               | 1         | 0.68%   |
| Huddly                                 | 1         | 0.68%   |
| Creative Technology                    | 1         | 0.68%   |
| Alcor Micro                            | 1         | 0.68%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 9         | 6.04%   |
| Chicony Integrated Camera                               | 5         | 3.36%   |
| Realtek USB Camera                                      | 4         | 2.68%   |
| Lite-On Integrated Camera                               | 4         | 2.68%   |
| Logitech Webcam C930e                                   | 3         | 2.01%   |
| Logitech HD Webcam C525                                 | 3         | 2.01%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 2.01%   |
| IMC Networks Integrated Camera                          | 3         | 2.01%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 3         | 2.01%   |
| Chicony Integrated HP HD Webcam                         | 3         | 2.01%   |
| Acer Integrated Camera                                  | 3         | 2.01%   |
| Syntek Integrated Camera                                | 2         | 1.34%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 1.34%   |
| Sunplus Asus Webcam                                     | 2         | 1.34%   |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.] | 2         | 1.34%   |
| Realtek Lenovo EasyCamera                               | 2         | 1.34%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.34%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 1.34%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 1.34%   |
| Logitech Webcam C270                                    | 2         | 1.34%   |
| Logitech HD Pro Webcam C920                             | 2         | 1.34%   |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 1.34%   |
| Chicony ThinkPad T490 Webcam                            | 2         | 1.34%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 1.34%   |
| Chicony HP Wide Vision HD Camera                        | 2         | 1.34%   |
| Chicony HP HD Webcam                                    | 2         | 1.34%   |
| Chicony FJ Camera                                       | 2         | 1.34%   |
| Arkmicro USB2.0 PC CAMERA                               | 2         | 1.34%   |
| Apple iPhone 5/5C/5S/6/SE                               | 2         | 1.34%   |
| Z-Star USB2.0 Camera                                    | 1         | 0.67%   |
| Syntek USB2.0 UVC PC Camera                             | 1         | 0.67%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.67%   |
| Suyin USB Webcam                                        | 1         | 0.67%   |
| Suyin Integrated_Webcam_HD                              | 1         | 0.67%   |
| Suyin HD WebCam                                         | 1         | 0.67%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 1         | 0.67%   |
| Sunplus Laptop_Integrated_Webcam_HD                     | 1         | 0.67%   |
| Sunplus Integrated Webcam                               | 1         | 0.67%   |
| Sunplus HP Wide Vision HD                               | 1         | 0.67%   |
| Sunplus HP Universal Camera                             | 1         | 0.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 18        | 43.9%   |
| Synaptics                  | 10        | 24.39%  |
| Upek                       | 4         | 9.76%   |
| STMicroelectronics         | 4         | 9.76%   |
| Shenzhen Goodix Technology | 3         | 7.32%   |
| Elan Microelectronics      | 1         | 2.44%   |
| AuthenTec                  | 1         | 2.44%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                  | 5         | 12.2%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 4         | 9.76%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 4         | 9.76%   |
| STMicroelectronics Fingerprint Reader                       | 4         | 9.76%   |
| Validity Sensors VFS471 Fingerprint Reader                  | 3         | 7.32%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 3         | 7.32%   |
| Synaptics Metallica MIS Touch Fingerprint Reader            | 3         | 7.32%   |
| Unknown                                                     | 3         | 7.32%   |
| Validity Sensors VFS5011 Fingerprint Reader                 | 2         | 4.88%   |
| Shenzhen Goodix FingerPrint                                 | 2         | 4.88%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor           | 1         | 2.44%   |
| Validity Sensors VFS101 Fingerprint Reader                  | 1         | 2.44%   |
| Validity Sensors Synaptics WBDI                             | 1         | 2.44%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 2.44%   |
| Validity Sensors Fingerprint scanner                        | 1         | 2.44%   |
| Shenzhen Goodix  Fingerprint Device                         | 1         | 2.44%   |
| Elan ELAN:Fingerprint                                       | 1         | 2.44%   |
| AuthenTec AES2550 Fingerprint Sensor                        | 1         | 2.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 19        | 39.58%  |
| OmniKey               | 18        | 37.5%   |
| Lenovo                | 3         | 6.25%   |
| Gemalto (was Gemplus) | 3         | 6.25%   |
| Broadcom              | 3         | 6.25%   |
| SCM Microsystems      | 1         | 2.08%   |
| O2 Micro              | 1         | 2.08%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                    | 16        | 33.33%  |
| OmniKey CardMan 1021                                   | 15        | 31.25%  |
| OmniKey CardMan 4321                                   | 3         | 6.25%   |
| Lenovo Integrated Smart Card Reader                    | 3         | 6.25%   |
| Broadcom 58200                                         | 3         | 6.25%   |
| Alcor Micro Watchdata W 1981                           | 3         | 6.25%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader      | 2         | 4.17%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1         | 2.08%   |
| O2 Micro OZ776 CCID Smartcard Reader                   | 1         | 2.08%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer | 1         | 2.08%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 165       | 63.46%  |
| 1     | 76        | 29.23%  |
| 2     | 18        | 6.92%   |
| 3     | 1         | 0.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 41        | 36.28%  |
| Graphics card            | 27        | 23.89%  |
| Chipcard                 | 25        | 22.12%  |
| Net/wireless             | 6         | 5.31%   |
| Multimedia controller    | 3         | 2.65%   |
| Communication controller | 3         | 2.65%   |
| Net/ethernet             | 2         | 1.77%   |
| Camera                   | 2         | 1.77%   |
| Sound                    | 1         | 0.88%   |
| Modem                    | 1         | 0.88%   |
| Card reader              | 1         | 0.88%   |
| Bluetooth                | 1         | 0.88%   |

