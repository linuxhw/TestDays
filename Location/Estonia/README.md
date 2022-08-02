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

Total: 335

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 31        | 12.65%  |
| Ubuntu 18.04       | 22        | 8.98%   |
| ROSA R11           | 10        | 4.08%   |
| Arch               | 9         | 3.67%   |
| Fedora 34          | 8         | 3.27%   |
| Ubuntu 19.04       | 7         | 2.86%   |
| ROSA R8.1          | 7         | 2.86%   |
| Linux Mint 20.1    | 6         | 2.45%   |
| Kubuntu 20.04      | 6         | 2.45%   |
| ArcoLinux Rolling  | 6         | 2.45%   |
| Arch Rolling       | 6         | 2.45%   |
| OpenMandriva 4.3   | 5         | 2.04%   |
| OpenMandriva 4.2   | 5         | 2.04%   |
| Manjaro            | 5         | 2.04%   |
| Fedora 35          | 5         | 2.04%   |
| ROSA R9            | 4         | 1.63%   |
| KDE neon 20.04     | 4         | 1.63%   |
| Fedora 36          | 4         | 1.63%   |
| Ubuntu 22.04       | 3         | 1.22%   |
| Ubuntu 21.10       | 3         | 1.22%   |
| Ubuntu 19.10       | 3         | 1.22%   |
| Ubuntu 16.04       | 3         | 1.22%   |
| ROSA R10           | 3         | 1.22%   |
| Pop!_OS 20.04      | 3         | 1.22%   |
| Gentoo 2.6         | 3         | 1.22%   |
| Fedora 31          | 3         | 1.22%   |
| Debian Testing     | 3         | 1.22%   |
| Xubuntu 20.04      | 2         | 0.82%   |
| Xubuntu 18.04      | 2         | 0.82%   |
| Ubuntu MATE 20.04  | 2         | 0.82%   |
| Ubuntu 21.04       | 2         | 0.82%   |
| Ubuntu 20.10       | 2         | 0.82%   |
| ROSA 12.2          | 2         | 0.82%   |
| Reborn OS          | 2         | 0.82%   |
| Pop!_OS 21.10      | 2         | 0.82%   |
| Pop!_OS 21.04      | 2         | 0.82%   |
| Manjaro 20.1       | 2         | 0.82%   |
| LMDE 4             | 2         | 0.82%   |
| Linux Mint 20.2    | 2         | 0.82%   |
| Linux Mint 19.3    | 2         | 0.82%   |
| Linux Mint 18.3    | 2         | 0.82%   |
| Fedora 33          | 2         | 0.82%   |
| Elementary 6.1     | 2         | 0.82%   |
| Elementary 6       | 2         | 0.82%   |
| Debian 11          | 2         | 0.82%   |
| Zorin 16           | 1         | 0.41%   |
| Zorin 15           | 1         | 0.41%   |
| Xubuntu 21.04      | 1         | 0.41%   |
| Ubuntu MATE 22.04  | 1         | 0.41%   |
| ROSA R8            | 1         | 0.41%   |
| ROSA 12            | 1         | 0.41%   |
| Pop!_OS 20.10      | 1         | 0.41%   |
| openSUSE Leap-15.3 | 1         | 0.41%   |
| OpenMandriva 4.90  | 1         | 0.41%   |
| MX 21              | 1         | 0.41%   |
| Manjaro 21.2.3     | 1         | 0.41%   |
| Manjaro 21.1.0     | 1         | 0.41%   |
| Manjaro 21.0.7     | 1         | 0.41%   |
| Manjaro 19.0.0     | 1         | 0.41%   |
| Manjaro 19.0       | 1         | 0.41%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 76        | 31.67%  |
| ROSA         | 28        | 11.67%  |
| Fedora       | 21        | 8.75%   |
| Arch         | 15        | 6.25%   |
| Linux Mint   | 14        | 5.83%   |
| Manjaro      | 13        | 5.42%   |
| OpenMandriva | 11        | 4.58%   |
| Pop!_OS      | 7         | 2.92%   |
| Kubuntu      | 7         | 2.92%   |
| Debian       | 7         | 2.92%   |
| ArcoLinux    | 6         | 2.5%    |
| Xubuntu      | 5         | 2.08%   |
| KDE neon     | 4         | 1.67%   |
| Gentoo       | 4         | 1.67%   |
| Elementary   | 4         | 1.67%   |
| Ubuntu MATE  | 3         | 1.25%   |
| Endless      | 3         | 1.25%   |
| Clear Linux  | 3         | 1.25%   |
| Zorin        | 2         | 0.83%   |
| Reborn OS    | 2         | 0.83%   |
| LMDE         | 2         | 0.83%   |
| openSUSE     | 1         | 0.42%   |
| MX           | 1         | 0.42%   |
| Lubuntu      | 1         | 0.42%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.4.0-42-generic                | 8         | 3.01%   |
| 5.16.7-desktop-1omv4003         | 5         | 1.88%   |
| 5.10.14-desktop-1omv4002        | 5         | 1.88%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 4         | 1.5%    |
| 5.4.0-65-generic                | 3         | 1.13%   |
| 5.4.0-47-generic                | 3         | 1.13%   |
| 5.4.0-28-generic                | 3         | 1.13%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 3         | 1.13%   |
| 5.8.0-63-generic                | 2         | 0.75%   |
| 5.8.0-53-generic                | 2         | 0.75%   |
| 5.5.2-1-MANJARO                 | 2         | 0.75%   |
| 5.4.0-88-generic                | 2         | 0.75%   |
| 5.4.0-58-generic                | 2         | 0.75%   |
| 5.4.0-53-generic                | 2         | 0.75%   |
| 5.4.0-45-generic                | 2         | 0.75%   |
| 5.4.0-33-generic                | 2         | 0.75%   |
| 5.4.0-29-generic                | 2         | 0.75%   |
| 5.4.0-26-generic                | 2         | 0.75%   |
| 5.3.0-40-generic                | 2         | 0.75%   |
| 5.15.5-76051505-generic         | 2         | 0.75%   |
| 5.15.2-arch1-1                  | 2         | 0.75%   |
| 5.15.0-41-generic               | 2         | 0.75%   |
| 5.13.12-200.fc34.x86_64         | 2         | 0.75%   |
| 5.13.0-39-generic               | 2         | 0.75%   |
| 5.11.0-37-generic               | 2         | 0.75%   |
| 5.11.0-34-generic               | 2         | 0.75%   |
| 5.11.0-27-generic               | 2         | 0.75%   |
| 5.11.0-25-generic               | 2         | 0.75%   |
| 5.0.0-23-generic                | 2         | 0.75%   |
| 4.9.9-nrj-desktop-1rosa-x86_64  | 2         | 0.75%   |
| 4.18.0-15-generic               | 2         | 0.75%   |
| 4.15.0-desktop-68.5rosa-x86_64  | 2         | 0.75%   |
| 4.15.0-desktop-45.1rosa-i586    | 2         | 0.75%   |
| 4.15.0-50-generic               | 2         | 0.75%   |
| 4.15.0-46-generic               | 2         | 0.75%   |
| 4.15.0-45-generic               | 2         | 0.75%   |
| 5.9.16-1-MANJARO                | 1         | 0.38%   |
| 5.9.13-200.fc33.x86_64          | 1         | 0.38%   |
| 5.9.10-zen1-1-zen               | 1         | 0.38%   |
| 5.9.0-050900rc5-lowlatency      | 1         | 0.38%   |
| 5.8.6-1-MANJARO                 | 1         | 0.38%   |
| 5.8.10-zen1-1-zen               | 1         | 0.38%   |
| 5.8.10-arch1-1                  | 1         | 0.38%   |
| 5.8.0-7630-generic              | 1         | 0.38%   |
| 5.8.0-59-generic                | 1         | 0.38%   |
| 5.8.0-54-generic                | 1         | 0.38%   |
| 5.8.0-50-generic                | 1         | 0.38%   |
| 5.8.0-45-generic                | 1         | 0.38%   |
| 5.8.0-44-generic                | 1         | 0.38%   |
| 5.8.0-38-generic                | 1         | 0.38%   |
| 5.8.0-29-generic                | 1         | 0.38%   |
| 5.8.0-14-generic                | 1         | 0.38%   |
| 5.8.0-1-tkg-pds                 | 1         | 0.38%   |
| 5.7.0-2-amd64                   | 1         | 0.38%   |
| 5.6.13-100.fc30.x86_64          | 1         | 0.38%   |
| 5.6.11-gentoo                   | 1         | 0.38%   |
| 5.6.10-947.native               | 1         | 0.38%   |
| 5.5.9-200.fc31.x86_64           | 1         | 0.38%   |
| 5.5.6-1-MANJARO                 | 1         | 0.38%   |
| 5.4.8-200.fc31.x86_64           | 1         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 46        | 18.04%  |
| 4.15.0  | 26        | 10.2%   |
| 5.11.0  | 14        | 5.49%   |
| 5.8.0   | 11        | 4.31%   |
| 5.13.0  | 10        | 3.92%   |
| 5.0.0   | 10        | 3.92%   |
| 5.3.0   | 6         | 2.35%   |
| 5.15.0  | 6         | 2.35%   |
| 4.18.0  | 6         | 2.35%   |
| 5.16.7  | 5         | 1.96%   |
| 5.10.14 | 5         | 1.96%   |
| 4.9.20  | 5         | 1.96%   |
| 5.15.2  | 3         | 1.18%   |
| 5.13.12 | 3         | 1.18%   |
| 5.10.0  | 3         | 1.18%   |
| 4.9.9   | 3         | 1.18%   |
| 5.8.10  | 2         | 0.78%   |
| 5.5.2   | 2         | 0.78%   |
| 5.17.1  | 2         | 0.78%   |
| 5.15.5  | 2         | 0.78%   |
| 5.13.13 | 2         | 0.78%   |
| 5.11.12 | 2         | 0.78%   |
| 5.11.11 | 2         | 0.78%   |
| 4.9.60  | 2         | 0.78%   |
| 4.19.0  | 2         | 0.78%   |
| 5.9.16  | 1         | 0.39%   |
| 5.9.13  | 1         | 0.39%   |
| 5.9.10  | 1         | 0.39%   |
| 5.9.0   | 1         | 0.39%   |
| 5.8.6   | 1         | 0.39%   |
| 5.7.0   | 1         | 0.39%   |
| 5.6.13  | 1         | 0.39%   |
| 5.6.11  | 1         | 0.39%   |
| 5.6.10  | 1         | 0.39%   |
| 5.5.9   | 1         | 0.39%   |
| 5.5.6   | 1         | 0.39%   |
| 5.4.8   | 1         | 0.39%   |
| 5.4.64  | 1         | 0.39%   |
| 5.4.48  | 1         | 0.39%   |
| 5.4.38  | 1         | 0.39%   |
| 5.4.17  | 1         | 0.39%   |
| 5.4.13  | 1         | 0.39%   |
| 5.3.18  | 1         | 0.39%   |
| 5.3.13  | 1         | 0.39%   |
| 5.18.3  | 1         | 0.39%   |
| 5.18.12 | 1         | 0.39%   |
| 5.18.10 | 1         | 0.39%   |
| 5.17.8  | 1         | 0.39%   |
| 5.17.6  | 1         | 0.39%   |
| 5.17.4  | 1         | 0.39%   |
| 5.17.11 | 1         | 0.39%   |
| 5.16.9  | 1         | 0.39%   |
| 5.16.5  | 1         | 0.39%   |
| 5.16.18 | 1         | 0.39%   |
| 5.16.15 | 1         | 0.39%   |
| 5.16.0  | 1         | 0.39%   |
| 5.15.19 | 1         | 0.39%   |
| 5.15.15 | 1         | 0.39%   |
| 5.14.3  | 1         | 0.39%   |
| 5.14.21 | 1         | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 52        | 20.39%  |
| 4.15    | 26        | 10.2%   |
| 5.13    | 22        | 8.63%   |
| 5.11    | 19        | 7.45%   |
| 5.10    | 18        | 7.06%   |
| 5.8     | 14        | 5.49%   |
| 4.9     | 14        | 5.49%   |
| 5.15    | 13        | 5.1%    |
| 5.0     | 11        | 4.31%   |
| 5.16    | 10        | 3.92%   |
| 5.3     | 8         | 3.14%   |
| 5.14    | 7         | 2.75%   |
| 5.17    | 6         | 2.35%   |
| 4.18    | 6         | 2.35%   |
| 5.9     | 4         | 1.57%   |
| 5.5     | 4         | 1.57%   |
| 5.12    | 4         | 1.57%   |
| 4.19    | 4         | 1.57%   |
| 5.6     | 3         | 1.18%   |
| 5.18    | 3         | 1.18%   |
| 4.1     | 2         | 0.78%   |
| 5.7     | 1         | 0.39%   |
| 5.1     | 1         | 0.39%   |
| 4.4     | 1         | 0.39%   |
| 4.10    | 1         | 0.39%   |
| 3.16    | 1         | 0.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 223       | 95.3%   |
| i686   | 11        | 4.7%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 79        | 33.05%  |
| Unknown    | 42        | 17.57%  |
| KDE5       | 37        | 15.48%  |
| KDE4       | 19        | 7.95%   |
| XFCE       | 18        | 7.53%   |
| X-Cinnamon | 12        | 5.02%   |
| MATE       | 9         | 3.77%   |
| KDE        | 5         | 2.09%   |
| Pantheon   | 4         | 1.67%   |
| i3         | 3         | 1.26%   |
| Unity      | 2         | 0.84%   |
| LXQt       | 2         | 0.84%   |
| awesome    | 2         | 0.84%   |
| sway       | 1         | 0.42%   |
| openbox    | 1         | 0.42%   |
| LXDE       | 1         | 0.42%   |
| Cinnamon   | 1         | 0.42%   |
| Budgie     | 1         | 0.42%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 190       | 80.51%  |
| Wayland | 28        | 11.86%  |
| Unknown | 16        | 6.78%   |
| Tty     | 2         | 0.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 116       | 49.15%  |
| SDDM    | 41        | 17.37%  |
| GDM     | 29        | 12.29%  |
| KDM     | 19        | 8.05%   |
| TDM     | 12        | 5.08%   |
| GDM3    | 10        | 4.24%   |
| LightDM | 9         | 3.81%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| en_US           | 106       | 44.35%  |
| Unknown         | 59        | 24.69%  |
| et_EE           | 33        | 13.81%  |
| ru_RU           | 22        | 9.21%   |
| en_GB           | 8         | 3.35%   |
| de_DE           | 3         | 1.26%   |
| en_DK           | 2         | 0.84%   |
| uk_UA           | 1         | 0.42%   |
| ru_UA           | 1         | 0.42%   |
| pl_PL           | 1         | 0.42%   |
| fr_FR           | 1         | 0.42%   |
| en_US.iso885915 | 1         | 0.42%   |
| C               | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 131       | 54.58%  |
| EFI  | 109       | 45.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 177       | 75.32%  |
| Btrfs   | 23        | 9.79%   |
| Unknown | 19        | 8.09%   |
| Overlay | 10        | 4.26%   |
| Xfs     | 3         | 1.28%   |
| Ext3    | 2         | 0.85%   |
| Zfs     | 1         | 0.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 121       | 51.71%  |
| GPT     | 76        | 32.48%  |
| MBR     | 37        | 15.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 197       | 83.12%  |
| Yes       | 40        | 16.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 168       | 70.59%  |
| Yes       | 70        | 29.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 48        | 20.51%  |
| Hewlett-Packard     | 35        | 14.96%  |
| ASUSTek Computer    | 35        | 14.96%  |
| Dell                | 28        | 11.97%  |
| MSI                 | 22        | 9.4%    |
| Gigabyte Technology | 19        | 8.12%   |
| Samsung Electronics | 7         | 2.99%   |
| Intel               | 6         | 2.56%   |
| ASRock              | 6         | 2.56%   |
| Acer                | 5         | 2.14%   |
| ECS                 | 3         | 1.28%   |
| Timi                | 2         | 0.85%   |
| Quanta              | 2         | 0.85%   |
| ZOTAC               | 1         | 0.43%   |
| TUXEDO              | 1         | 0.43%   |
| Toshiba             | 1         | 0.43%   |
| Supermicro          | 1         | 0.43%   |
| Prestigio           | 1         | 0.43%   |
| OEM                 | 1         | 0.43%   |
| Notebook            | 1         | 0.43%   |
| mPTech              | 1         | 0.43%   |
| Huanan              | 1         | 0.43%   |
| Getac               | 1         | 0.43%   |
| Fujitsu Siemens     | 1         | 0.43%   |
| Fujitsu             | 1         | 0.43%   |
| Framework           | 1         | 0.43%   |
| Apple               | 1         | 0.43%   |
| Alienware           | 1         | 0.43%   |
| ABIT                | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| ASUS All Series                                       | 3         | 1.28%   |
| Quanta TWH                                            | 2         | 0.85%   |
| MSI MS-7758                                           | 2         | 0.85%   |
| Lenovo Y50-70 20378                                   | 2         | 0.85%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2                     | 2         | 0.85%   |
| HP Pavilion Gaming Laptop 15-ec1xxx                   | 2         | 0.85%   |
| HP Pavilion dv7                                       | 2         | 0.85%   |
| HP ENVY Laptop 13-ah0xxx                              | 2         | 0.85%   |
| HP EliteBook 8470p                                    | 2         | 0.85%   |
| HP EliteBook 8460p                                    | 2         | 0.85%   |
| HP EliteBook 840 G2                                   | 2         | 0.85%   |
| Gigabyte X570 AORUS PRO                               | 2         | 0.85%   |
| Dell Inspiron N5110                                   | 2         | 0.85%   |
| ZOTAC B410                                            | 1         | 0.43%   |
| TUXEDO Book BA1510                                    | 1         | 0.43%   |
| Toshiba Satellite L855                                | 1         | 0.43%   |
| Timi RedmiBook 16                                     | 1         | 0.43%   |
| Timi RedmiBook 14 II                                  | 1         | 0.43%   |
| Supermicro X10SLH-F/X10SLM+-F                         | 1         | 0.43%   |
| Samsung R410                                          | 1         | 0.43%   |
| Samsung 900X3C/900X3D/900X4C/900X4D                   | 1         | 0.43%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D            | 1         | 0.43%   |
| Samsung 770Z5E/780Z5E                                 | 1         | 0.43%   |
| Samsung 535U3C                                        | 1         | 0.43%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.43%   |
| Samsung 275E4E/275E5E                                 | 1         | 0.43%   |
| Prestigio PNT10131DEDB                                | 1         | 0.43%   |
| OEM Intel H81                                         | 1         | 0.43%   |
| Notebook W35xSS_370SS                                 | 1         | 0.43%   |
| MSI MS-B90111                                         | 1         | 0.43%   |
| MSI MS-7C91                                           | 1         | 0.43%   |
| MSI MS-7C83                                           | 1         | 0.43%   |
| MSI MS-7C37                                           | 1         | 0.43%   |
| MSI MS-7C02                                           | 1         | 0.43%   |
| MSI MS-7B98                                           | 1         | 0.43%   |
| MSI MS-7B79                                           | 1         | 0.43%   |
| MSI MS-7B22                                           | 1         | 0.43%   |
| MSI MS-7B18                                           | 1         | 0.43%   |
| MSI MS-7A74                                           | 1         | 0.43%   |
| MSI MS-7996                                           | 1         | 0.43%   |
| MSI MS-7978                                           | 1         | 0.43%   |
| MSI MS-7971                                           | 1         | 0.43%   |
| MSI MS-7851                                           | 1         | 0.43%   |
| MSI MS-7640                                           | 1         | 0.43%   |
| MSI MS-7267                                           | 1         | 0.43%   |
| MSI GT70 2OC/2OD                                      | 1         | 0.43%   |
| MSI GS75 Stealth 8SE                                  | 1         | 0.43%   |
| MSI GP62M 7RDX                                        | 1         | 0.43%   |
| MSI FJ418AA-UUW a6522.SC                              | 1         | 0.43%   |
| mPTech ARC 11.6 128GB HD                              | 1         | 0.43%   |
| Lenovo Y720-15IKB 80VR                                | 1         | 0.43%   |
| Lenovo Y520-15IKBN 80WK                               | 1         | 0.43%   |
| Lenovo V110-15ISK 80TL                                | 1         | 0.43%   |
| Lenovo ThinkPad Yoga 370 20JJS01S1D                   | 1         | 0.43%   |
| Lenovo ThinkPad X260 20F5S84400                       | 1         | 0.43%   |
| Lenovo ThinkPad X220 4291R30                          | 1         | 0.43%   |
| Lenovo ThinkPad X220 429136G                          | 1         | 0.43%   |
| Lenovo ThinkPad X201 3680CG7                          | 1         | 0.43%   |
| Lenovo ThinkPad W541 20EF001TMS                       | 1         | 0.43%   |
| Lenovo ThinkPad T61 76641FG                           | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 29        | 12.39%  |
| HP EliteBook           | 13        | 5.56%   |
| HP Pavilion            | 7         | 2.99%   |
| Dell Inspiron          | 7         | 2.99%   |
| HP Compaq              | 5         | 2.14%   |
| Dell OptiPlex          | 5         | 2.14%   |
| Dell Latitude          | 5         | 2.14%   |
| Lenovo IdeaPad         | 4         | 1.71%   |
| Gigabyte X570          | 4         | 1.71%   |
| Dell XPS               | 4         | 1.71%   |
| Dell Precision         | 4         | 1.71%   |
| ASUS PRIME             | 4         | 1.71%   |
| Acer Aspire            | 4         | 1.71%   |
| Lenovo ThinkCentre     | 3         | 1.28%   |
| Lenovo IdeaPadFlex     | 3         | 1.28%   |
| ASUS VivoBook          | 3         | 1.28%   |
| ASUS All               | 3         | 1.28%   |
| Timi RedmiBook         | 2         | 0.85%   |
| Samsung 900X3C         | 2         | 0.85%   |
| Quanta TWH             | 2         | 0.85%   |
| MSI MS-7758            | 2         | 0.85%   |
| Lenovo Y50-70          | 2         | 0.85%   |
| HP ProDesk             | 2         | 0.85%   |
| HP Presario            | 2         | 0.85%   |
| HP OMEN                | 2         | 0.85%   |
| HP ENVY                | 2         | 0.85%   |
| ASUS ZenBook           | 2         | 0.85%   |
| ASUS ROG               | 2         | 0.85%   |
| ZOTAC B410             | 1         | 0.43%   |
| TUXEDO Book            | 1         | 0.43%   |
| Toshiba Satellite      | 1         | 0.43%   |
| Supermicro X10SLH-F    | 1         | 0.43%   |
| Samsung R410           | 1         | 0.43%   |
| Samsung 770Z5E         | 1         | 0.43%   |
| Samsung 535U3C         | 1         | 0.43%   |
| Samsung 300E5EV        | 1         | 0.43%   |
| Samsung 275E4E         | 1         | 0.43%   |
| Prestigio PNT10131DEDB | 1         | 0.43%   |
| OEM Intel              | 1         | 0.43%   |
| Notebook W35xSS        | 1         | 0.43%   |
| MSI MS-B90111          | 1         | 0.43%   |
| MSI MS-7C91            | 1         | 0.43%   |
| MSI MS-7C83            | 1         | 0.43%   |
| MSI MS-7C37            | 1         | 0.43%   |
| MSI MS-7C02            | 1         | 0.43%   |
| MSI MS-7B98            | 1         | 0.43%   |
| MSI MS-7B79            | 1         | 0.43%   |
| MSI MS-7B22            | 1         | 0.43%   |
| MSI MS-7B18            | 1         | 0.43%   |
| MSI MS-7A74            | 1         | 0.43%   |
| MSI MS-7996            | 1         | 0.43%   |
| MSI MS-7978            | 1         | 0.43%   |
| MSI MS-7971            | 1         | 0.43%   |
| MSI MS-7851            | 1         | 0.43%   |
| MSI MS-7640            | 1         | 0.43%   |
| MSI MS-7267            | 1         | 0.43%   |
| MSI GT70               | 1         | 0.43%   |
| MSI GS75               | 1         | 0.43%   |
| MSI GP62M              | 1         | 0.43%   |
| MSI FJ418AA-UUW        | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 27        | 11.54%  |
| 2020 | 23        | 9.83%   |
| 2019 | 22        | 9.4%    |
| 2013 | 19        | 8.12%   |
| 2011 | 19        | 8.12%   |
| 2014 | 18        | 7.69%   |
| 2017 | 17        | 7.26%   |
| 2015 | 16        | 6.84%   |
| 2012 | 15        | 6.41%   |
| 2016 | 11        | 4.7%    |
| 2010 | 9         | 3.85%   |
| 2009 | 8         | 3.42%   |
| 2008 | 8         | 3.42%   |
| 2007 | 8         | 3.42%   |
| 2021 | 7         | 2.99%   |
| 2006 | 4         | 1.71%   |
| 2005 | 2         | 0.85%   |
| 2004 | 1         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 133       | 56.84%  |
| Desktop     | 88        | 37.61%  |
| Convertible | 8         | 3.42%   |
| Mini pc     | 3         | 1.28%   |
| All in one  | 1         | 0.43%   |
| Server      | 1         | 0.43%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 219       | 92.8%   |
| Enabled  | 17        | 7.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 234       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 48        | 20.25%  |
| 8.01-16.0   | 47        | 19.83%  |
| 4.01-8.0    | 44        | 18.57%  |
| 3.01-4.0    | 41        | 17.3%   |
| 32.01-64.0  | 27        | 11.39%  |
| 24.01-32.0  | 8         | 3.38%   |
| 2.01-3.0    | 8         | 3.38%   |
| 1.01-2.0    | 7         | 2.95%   |
| 64.01-256.0 | 5         | 2.11%   |
| 0.51-1.0    | 2         | 0.84%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 80        | 31.62%  |
| 2.01-3.0   | 58        | 22.92%  |
| 4.01-8.0   | 43        | 17%     |
| 3.01-4.0   | 25        | 9.88%   |
| 0.51-1.0   | 24        | 9.49%   |
| 8.01-16.0  | 15        | 5.93%   |
| 24.01-32.0 | 3         | 1.19%   |
| 0.01-0.5   | 3         | 1.19%   |
| 16.01-24.0 | 2         | 0.79%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 145       | 60.42%  |
| 2      | 55        | 22.92%  |
| 3      | 20        | 8.33%   |
| 6      | 7         | 2.92%   |
| 4      | 7         | 2.92%   |
| 5      | 3         | 1.25%   |
| 0      | 2         | 0.83%   |
| 7      | 1         | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 137       | 58.05%  |
| Yes       | 99        | 41.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 212       | 89.83%  |
| No        | 24        | 10.17%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 174       | 74.36%  |
| No        | 60        | 25.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 137       | 57.81%  |
| No        | 100       | 42.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Estonia | 234       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Tallinn           | 150       | 62.5%   |
| Tartu             | 25        | 10.42%  |
| Pärnu            | 8         | 3.33%   |
| Rapla             | 7         | 2.92%   |
| Rakvere           | 5         | 2.08%   |
| Haapsalu          | 4         | 1.67%   |
| Narva             | 3         | 1.25%   |
| Maardu            | 3         | 1.25%   |
| Vinni             | 2         | 0.83%   |
| Põlva            | 2         | 0.83%   |
| Paldiski          | 2         | 0.83%   |
| Otepaeae          | 2         | 0.83%   |
| Kohtla-Järve     | 2         | 0.83%   |
| Keila             | 2         | 0.83%   |
| Jõhvi            | 2         | 0.83%   |
| Viljandi          | 1         | 0.42%   |
| Vatla             | 1         | 0.42%   |
| Vaidasoo          | 1         | 0.42%   |
| Türi             | 1         | 0.42%   |
| Tapa              | 1         | 0.42%   |
| Tabasalu          | 1         | 0.42%   |
| Sindi             | 1         | 0.42%   |
| Sauga             | 1         | 0.42%   |
| Saku              | 1         | 0.42%   |
| Rae Parish        | 1         | 0.42%   |
| Pohja-Sakala vald | 1         | 0.42%   |
| Paide             | 1         | 0.42%   |
| Laagri            | 1         | 0.42%   |
| Kuressaare        | 1         | 0.42%   |
| Kose              | 1         | 0.42%   |
| Kärdla           | 1         | 0.42%   |
| Kaeina            | 1         | 0.42%   |
| Jõgeva           | 1         | 0.42%   |
| Jaerva vald       | 1         | 0.42%   |
| Hiiumaa           | 1         | 0.42%   |
| Haabneeme         | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 74        | 100    | 21.57%  |
| Seagate                   | 46        | 60     | 13.41%  |
| WDC                       | 42        | 66     | 12.24%  |
| Kingston                  | 25        | 37     | 7.29%   |
| Toshiba                   | 21        | 22     | 6.12%   |
| Hitachi                   | 15        | 18     | 4.37%   |
| SK hynix                  | 14        | 18     | 4.08%   |
| SanDisk                   | 12        | 14     | 3.5%    |
| Crucial                   | 12        | 21     | 3.5%    |
| Unknown                   | 10        | 10     | 2.92%   |
| HGST                      | 10        | 14     | 2.92%   |
| Intel                     | 9         | 11     | 2.62%   |
| A-DATA Technology         | 7         | 11     | 2.04%   |
| Gigabyte Technology       | 4         | 5      | 1.17%   |
| Transcend                 | 3         | 5      | 0.87%   |
| Micron Technology         | 3         | 3      | 0.87%   |
| KingSpec                  | 3         | 4      | 0.87%   |
| China                     | 3         | 3      | 0.87%   |
| Apacer                    | 3         | 3      | 0.87%   |
| Patriot                   | 2         | 2      | 0.58%   |
| Maxtor                    | 2         | 2      | 0.58%   |
| Lenovo                    | 2         | 2      | 0.58%   |
| Fujitsu                   | 2         | 2      | 0.58%   |
| Corsair                   | 2         | 2      | 0.58%   |
| XPG                       | 1         | 1      | 0.29%   |
| Team                      | 1         | 2      | 0.29%   |
| Silicon Motion            | 1         | 2      | 0.29%   |
| Plextor                   | 1         | 1      | 0.29%   |
| Phison                    | 1         | 1      | 0.29%   |
| Micron/Crucial Technology | 1         | 1      | 0.29%   |
| LITEONIT                  | 1         | 1      | 0.29%   |
| Lexar                     | 1         | 1      | 0.29%   |
| KIOXIA                    | 1         | 2      | 0.29%   |
| Intenso                   | 1         | 1      | 0.29%   |
| Integral                  | 1         | 1      | 0.29%   |
| Inateck                   | 1         | 1      | 0.29%   |
| i-FlashDisk               | 1         | 1      | 0.29%   |
| HUAWEI                    | 1         | 1      | 0.29%   |
| ASMT109x                  | 1         | 2      | 0.29%   |
| ASMT                      | 1         | 1      | 0.29%   |
| Apple                     | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB            | 6         | 1.57%   |
| Samsung NVMe SSD Drive 1TB           | 6         | 1.57%   |
| Seagate ST2000DM008-2FR102 2TB       | 4         | 1.05%   |
| Samsung NVMe SSD Drive 512GB         | 4         | 1.05%   |
| Samsung HD103SJ 1TB                  | 4         | 1.05%   |
| SK hynix NVMe SSD Drive 256GB        | 3         | 0.79%   |
| Seagate ST500LT012-9WS142 500GB      | 3         | 0.79%   |
| Samsung SSD 960 PRO 512GB            | 3         | 0.79%   |
| Samsung SSD 850 EVO 500GB            | 3         | 0.79%   |
| Samsung MZ7TY128HDHP-000L1 128GB SSD | 3         | 0.79%   |
| Kingston SV300S37A120G 120GB SSD     | 3         | 0.79%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 0.79%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 0.79%   |
| HGST HTS721010A9E630 1TB             | 3         | 0.79%   |
| HGST HTS541010A9E680 1TB             | 3         | 0.79%   |
| WDC WD10EADS-00M2B0 1TB              | 2         | 0.52%   |
| Unknown MMC Card  16GB               | 2         | 0.52%   |
| Unknown ArtisanTribute-512GB         | 2         | 0.52%   |
| Toshiba NVMe SSD Drive 512GB         | 2         | 0.52%   |
| Toshiba MQ01ABF050 500GB             | 2         | 0.52%   |
| Toshiba HDWD130 3TB                  | 2         | 0.52%   |
| SK hynix NVMe SSD Drive 512GB        | 2         | 0.52%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 0.52%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 0.52%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.52%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 0.52%   |
| Seagate ST1000DM003-1SB102 1TB       | 2         | 0.52%   |
| Seagate ST1000DM003-1ER162 1TB       | 2         | 0.52%   |
| SanDisk SD8SBAT256G1122 256GB SSD    | 2         | 0.52%   |
| SanDisk SD7SB3Q128G1001 128GB SSD    | 2         | 0.52%   |
| Samsung SSD 970 EVO Plus 500GB       | 2         | 0.52%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 0.52%   |
| Samsung SSD 860 EVO 250GB            | 2         | 0.52%   |
| Samsung SSD 860 EVO 1TB              | 2         | 0.52%   |
| Samsung SSD 850 PRO 256GB            | 2         | 0.52%   |
| Samsung SSD 850 EVO M.2 500GB        | 2         | 0.52%   |
| Samsung SSD 840 PRO Series 128GB     | 2         | 0.52%   |
| Samsung SP0802N 80GB                 | 2         | 0.52%   |
| Samsung NVMe SSD Drive 1024GB        | 2         | 0.52%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 2         | 0.52%   |
| Samsung MZALQ512HALU-000L2 512GB     | 2         | 0.52%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD | 2         | 0.52%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD  | 2         | 0.52%   |
| Kingston SUV400S37240G 240GB SSD     | 2         | 0.52%   |
| Kingston SA400S37960G 960GB SSD      | 2         | 0.52%   |
| Intel SSDPEKKF256G8L 256GB           | 2         | 0.52%   |
| Hitachi HTS723225L9A360 250GB        | 2         | 0.52%   |
| Hitachi HTS547550A9E384 500GB        | 2         | 0.52%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 0.52%   |
| Crucial CT2000MX500SSD1 2TB          | 2         | 0.52%   |
| Crucial CT128MX100SSD1 128GB         | 2         | 0.52%   |
| Apacer AS350 512GB SSD               | 2         | 0.52%   |
| A-DATA SU800 128GB SSD               | 2         | 0.52%   |
| A-DATA SP550 120GB SSD               | 2         | 0.52%   |
| XPG GAMMIX S11 480GB                 | 1         | 0.26%   |
| WDC WDS500G2B0B 500GB SSD            | 1         | 0.26%   |
| WDC WDS500G1X0E-00AFY0 500GB         | 1         | 0.26%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD     | 1         | 0.26%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 45        | 59     | 33.58%  |
| WDC                 | 33        | 50     | 24.63%  |
| Hitachi             | 15        | 18     | 11.19%  |
| Toshiba             | 13        | 13     | 9.7%    |
| Samsung Electronics | 11        | 13     | 8.21%   |
| HGST                | 10        | 14     | 7.46%   |
| Maxtor              | 2         | 2      | 1.49%   |
| Fujitsu             | 2         | 2      | 1.49%   |
| Unknown             | 1         | 1      | 0.75%   |
| ASMT                | 1         | 1      | 0.75%   |
| Apple               | 1         | 1      | 0.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 41        | 50     | 30.37%  |
| Kingston            | 20        | 29     | 14.81%  |
| Crucial             | 12        | 21     | 8.89%   |
| SanDisk             | 11        | 13     | 8.15%   |
| WDC                 | 7         | 10     | 5.19%   |
| A-DATA Technology   | 6         | 10     | 4.44%   |
| SK hynix            | 4         | 4      | 2.96%   |
| Transcend           | 3         | 5      | 2.22%   |
| Toshiba             | 3         | 4      | 2.22%   |
| Micron Technology   | 3         | 3      | 2.22%   |
| KingSpec            | 3         | 4      | 2.22%   |
| Intel               | 3         | 4      | 2.22%   |
| China               | 3         | 3      | 2.22%   |
| Apacer              | 3         | 3      | 2.22%   |
| Patriot             | 2         | 2      | 1.48%   |
| Gigabyte Technology | 2         | 3      | 1.48%   |
| Corsair             | 2         | 2      | 1.48%   |
| Team                | 1         | 2      | 0.74%   |
| Plextor             | 1         | 1      | 0.74%   |
| LITEONIT            | 1         | 1      | 0.74%   |
| Lexar               | 1         | 1      | 0.74%   |
| Intenso             | 1         | 1      | 0.74%   |
| Integral            | 1         | 1      | 0.74%   |
| i-FlashDisk         | 1         | 1      | 0.74%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 111       | 174    | 36.75%  |
| SSD     | 109       | 178    | 36.09%  |
| NVMe    | 69        | 90     | 22.85%  |
| MMC     | 7         | 7      | 2.32%   |
| Unknown | 6         | 7      | 1.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 183       | 346    | 67.28%  |
| NVMe | 69        | 90     | 25.37%  |
| SAS  | 13        | 13     | 4.78%   |
| MMC  | 7         | 7      | 2.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 150       | 230    | 62.76%  |
| 0.51-1.0   | 59        | 78     | 24.69%  |
| 1.01-2.0   | 16        | 23     | 6.69%   |
| 2.01-3.0   | 5         | 12     | 2.09%   |
| 4.01-10.0  | 5         | 5      | 2.09%   |
| 3.01-4.0   | 3         | 3      | 1.26%   |
| 10.01-20.0 | 1         | 1      | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 73        | 29.92%  |
| 251-500        | 51        | 20.9%   |
| 501-1000       | 28        | 11.48%  |
| 1-20           | 24        | 9.84%   |
| 1001-2000      | 21        | 8.61%   |
| 51-100         | 16        | 6.56%   |
| More than 3000 | 12        | 4.92%   |
| Unknown        | 8         | 3.28%   |
| 21-50          | 7         | 2.87%   |
| 2001-3000      | 4         | 1.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 104       | 41.77%  |
| 21-50          | 37        | 14.86%  |
| 101-250        | 34        | 13.65%  |
| 51-100         | 25        | 10.04%  |
| 251-500        | 14        | 5.62%   |
| 501-1000       | 13        | 5.22%   |
| More than 3000 | 8         | 3.21%   |
| Unknown        | 8         | 3.21%   |
| 1001-2000      | 5         | 2.01%   |
| 2001-3000      | 1         | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Crucial CT128MX100SSD1 128GB                        | 2         | 3      | 5.71%   |
| WDC WD60EFRX-68MYMN1 6TB                            | 1         | 1      | 2.86%   |
| WDC WD5002AALX-00J37A0 500GB                        | 1         | 1      | 2.86%   |
| WDC WD5000BPVT-00HXZT1 500GB                        | 1         | 1      | 2.86%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 1         | 1      | 2.86%   |
| WDC WD2500BEVT-80A23T0 250GB                        | 1         | 1      | 2.86%   |
| WDC WD20EZRX-00DC0B0 2TB                            | 1         | 2      | 2.86%   |
| WDC WD20EARX-00PASB0 2TB                            | 1         | 1      | 2.86%   |
| WDC WD10PURX-64E5EY0 1TB                            | 1         | 1      | 2.86%   |
| WDC WD10EAVS-00D7B1 1TB                             | 1         | 1      | 2.86%   |
| WDC WD10EADS-00M2B0 1TB                             | 1         | 2      | 2.86%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD            | 1         | 2      | 2.86%   |
| Seagate ST98823AS 80GB                              | 1         | 1      | 2.86%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 2.86%   |
| Seagate ST9160412AS 160GB                           | 1         | 1      | 2.86%   |
| Seagate ST750LX003-1AC154 752GB                     | 1         | 1      | 2.86%   |
| Seagate ST500DM002-1BD142 500GB                     | 1         | 1      | 2.86%   |
| Seagate ST340016A 40GB                              | 1         | 2      | 2.86%   |
| Seagate ST320LT012-9WS14C 320GB                     | 1         | 1      | 2.86%   |
| Seagate ST31000528AS 1TB                            | 1         | 1      | 2.86%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 2.86%   |
| Samsung Electronics SSD 840 PRO Series 128GB        | 1         | 1      | 2.86%   |
| Samsung Electronics SP0802N 80GB                    | 1         | 1      | 2.86%   |
| Samsung Electronics HD642JJ 640GB                   | 1         | 1      | 2.86%   |
| Samsung Electronics HD501LJ 500GB                   | 1         | 1      | 2.86%   |
| Samsung Electronics HD103SJ 1TB                     | 1         | 1      | 2.86%   |
| Patriot P210 256GB SSD                              | 1         | 1      | 2.86%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 2.86%   |
| Maxtor STM3250310AS 250GB                           | 1         | 1      | 2.86%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 1      | 2.86%   |
| Hitachi HDS721680PLA380 80GB                        | 1         | 1      | 2.86%   |
| Hitachi HDS721010DLE630 1TB                         | 1         | 1      | 2.86%   |
| Fujitsu MHT2040AH PL 40GB                           | 1         | 1      | 2.86%   |
| Crucial CT480M500SSD3 480GB                         | 1         | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 12     | 27.27%  |
| Seagate             | 9         | 10     | 27.27%  |
| Samsung Electronics | 4         | 5      | 12.12%  |
| Hitachi             | 3         | 3      | 9.09%   |
| Crucial             | 3         | 4      | 9.09%   |
| Toshiba             | 1         | 2      | 3.03%   |
| Patriot             | 1         | 1      | 3.03%   |
| Micron Technology   | 1         | 1      | 3.03%   |
| Maxtor              | 1         | 1      | 3.03%   |
| Fujitsu             | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 12     | 34.62%  |
| Seagate             | 9         | 10     | 34.62%  |
| Samsung Electronics | 3         | 4      | 11.54%  |
| Hitachi             | 3         | 3      | 11.54%  |
| Maxtor              | 1         | 1      | 3.85%   |
| Fujitsu             | 1         | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 31     | 78.13%  |
| SSD  | 7         | 9      | 21.88%  |

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
| Detected | 127       | 246    | 49.42%  |
| Works    | 97        | 169    | 37.74%  |
| Malfunc  | 32        | 40     | 12.45%  |
| Failed   | 1         | 1      | 0.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 167       | 55.3%   |
| AMD                          | 46        | 15.23%  |
| Samsung Electronics          | 31        | 10.26%  |
| SK hynix                     | 10        | 3.31%   |
| SanDisk                      | 7         | 2.32%   |
| Kingston Technology Company  | 6         | 1.99%   |
| Nvidia                       | 5         | 1.66%   |
| Marvell Technology Group     | 5         | 1.66%   |
| VIA Technologies             | 3         | 0.99%   |
| Toshiba America Info Systems | 3         | 0.99%   |
| Phison Electronics           | 3         | 0.99%   |
| KIOXIA                       | 3         | 0.99%   |
| ASMedia Technology           | 3         | 0.99%   |
| Silicon Motion               | 2         | 0.66%   |
| Lenovo                       | 2         | 0.66%   |
| JMicron Technology           | 2         | 0.66%   |
| Silicon Image                | 1         | 0.33%   |
| Micron/Crucial Technology    | 1         | 0.33%   |
| ADATA Technology             | 1         | 0.33%   |
| Adaptec                      | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 34        | 9.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 20        | 5.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 20        | 5.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 14        | 4.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 13        | 3.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 9         | 2.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 8         | 2.32%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 7         | 2.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7         | 2.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 7         | 2.03%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7         | 2.03%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6         | 1.74%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 6         | 1.74%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 1.74%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 5         | 1.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 5         | 1.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 5         | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 1.45%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5         | 1.45%   |
| Samsung NVMe SSD Controller 980                                                         | 4         | 1.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4         | 1.16%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 4         | 1.16%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 1.16%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 1.16%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                             | 3         | 0.87%   |
| SK hynix Non-Volatile memory controller                                                 | 3         | 0.87%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3         | 0.87%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 3         | 0.87%   |
| Kingston Company A2000 NVMe SSD                                                         | 3         | 0.87%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 3         | 0.87%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 0.87%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3         | 0.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 0.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3         | 0.87%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 2         | 0.58%   |
| SK hynix Gold P31 SSD                                                                   | 2         | 0.58%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 2         | 0.58%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2         | 0.58%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2         | 0.58%   |
| Nvidia CK804 Serial ATA Controller                                                      | 2         | 0.58%   |
| Nvidia CK804 IDE                                                                        | 2         | 0.58%   |
| Lenovo Non-Volatile memory controller                                                   | 2         | 0.58%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 2         | 0.58%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2         | 0.58%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 0.58%   |
| Intel SSD 660P Series                                                                   | 2         | 0.58%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 0.58%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 2         | 0.58%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 0.58%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2         | 0.58%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2         | 0.58%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                                | 2         | 0.58%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.58%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 0.58%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 0.58%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 0.58%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2         | 0.58%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 0.58%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2         | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 188       | 61.84%  |
| NVMe | 71        | 23.36%  |
| IDE  | 35        | 11.51%  |
| RAID | 9         | 2.96%   |
| SCSI | 1         | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 180       | 76.92%  |
| AMD    | 54        | 23.08%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.14%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.71%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.71%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.28%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.28%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 3         | 1.28%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 3         | 1.28%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 3         | 1.28%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.28%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 3         | 1.28%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 1.28%   |
| AMD Ryzen 5 3600 6-Core Processor             | 3         | 1.28%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz           | 2         | 0.85%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 0.85%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.85%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 0.85%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 0.85%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 0.85%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 0.85%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.85%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 2         | 0.85%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 0.85%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.85%   |
| Intel Core i5-2500 CPU @ 3.30GHz              | 2         | 0.85%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.85%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 0.85%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 0.85%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 0.85%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 2         | 0.85%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics    | 2         | 0.85%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 0.85%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 0.85%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 0.85%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+    | 2         | 0.85%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz            | 1         | 0.43%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz           | 1         | 0.43%   |
| Intel Pentium M processor 2.13GHz             | 1         | 0.43%   |
| Intel Pentium M processor 1.50GHz             | 1         | 0.43%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 1         | 0.43%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 1         | 0.43%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.43%   |
| Intel Pentium D CPU 2.80GHz                   | 1         | 0.43%   |
| Intel Pentium CPU G850 @ 2.90GHz              | 1         | 0.43%   |
| Intel Pentium CPU G4560T @ 2.90GHz            | 1         | 0.43%   |
| Intel Pentium CPU G2120 @ 3.10GHz             | 1         | 0.43%   |
| Intel Pentium CPU G2030 @ 3.00GHz             | 1         | 0.43%   |
| Intel Pentium CPU B940 @ 2.00GHz              | 1         | 0.43%   |
| Intel Pentium CPU 2127U @ 1.90GHz             | 1         | 0.43%   |
| Intel Pentium 4 CPU 3.00GHz                   | 1         | 0.43%   |
| Intel Pentium 3805U @ 1.90GHz                 | 1         | 0.43%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 1         | 0.43%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.43%   |
| Intel Core i9-7940X CPU @ 3.10GHz             | 1         | 0.43%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 0.43%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.43%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.43%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 0.43%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 57        | 24.36%  |
| Intel Core i7                  | 53        | 22.65%  |
| Intel Core i3                  | 18        | 7.69%   |
| AMD Ryzen 5                    | 15        | 6.41%   |
| Intel Core 2 Duo               | 12        | 5.13%   |
| Intel Celeron                  | 10        | 4.27%   |
| AMD Ryzen 7                    | 10        | 4.27%   |
| Intel Pentium                  | 7         | 2.99%   |
| Other                          | 4         | 1.71%   |
| Intel Xeon                     | 4         | 1.71%   |
| AMD Ryzen 9                    | 4         | 1.71%   |
| AMD Ryzen 7 PRO                | 4         | 1.71%   |
| AMD Athlon 64 X2               | 4         | 1.71%   |
| Intel Core i9                  | 3         | 1.28%   |
| Intel Pentium M                | 2         | 0.85%   |
| Intel Celeron Dual-Core        | 2         | 0.85%   |
| Intel Atom                     | 2         | 0.85%   |
| AMD FX                         | 2         | 0.85%   |
| AMD A10                        | 2         | 0.85%   |
| Intel Pentium Gold             | 1         | 0.43%   |
| Intel Pentium Dual-Core        | 1         | 0.43%   |
| Intel Pentium Dual             | 1         | 0.43%   |
| Intel Pentium D                | 1         | 0.43%   |
| Intel Pentium 4                | 1         | 0.43%   |
| Intel Core 2                   | 1         | 0.43%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.43%   |
| AMD Ryzen 3 PRO                | 1         | 0.43%   |
| AMD Ryzen 3                    | 1         | 0.43%   |
| AMD Phenom II X6               | 1         | 0.43%   |
| AMD Phenom II X4               | 1         | 0.43%   |
| AMD E2                         | 1         | 0.43%   |
| AMD E                          | 1         | 0.43%   |
| AMD C-60                       | 1         | 0.43%   |
| AMD Athlon XP                  | 1         | 0.43%   |
| AMD Athlon II Dual-Core        | 1         | 0.43%   |
| AMD A8                         | 1         | 0.43%   |
| AMD A6                         | 1         | 0.43%   |
| AMD A4                         | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 102       | 43.59%  |
| 4       | 74        | 31.62%  |
| 6       | 24        | 10.26%  |
| 8       | 17        | 7.26%   |
| 1       | 8         | 3.42%   |
| 12      | 3         | 1.28%   |
| Unknown | 3         | 1.28%   |
| 16      | 1         | 0.43%   |
| 14      | 1         | 0.43%   |
| 3       | 1         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 234       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 156       | 66.38%  |
| 1       | 76        | 32.34%  |
| Unknown | 3         | 1.28%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 229       | 97.45%  |
| 32-bit         | 3         | 1.28%   |
| Unknown        | 3         | 1.28%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 18.6%   |
| 0x306c3    | 19        | 7.85%   |
| 0x306a9    | 18        | 7.44%   |
| 0x206a7    | 16        | 6.61%   |
| 0x906e9    | 9         | 3.72%   |
| 0x806ea    | 8         | 3.31%   |
| 0x1067a    | 7         | 2.89%   |
| 0x906ea    | 6         | 2.48%   |
| 0x40651    | 6         | 2.48%   |
| 0x306d4    | 6         | 2.48%   |
| 0x08600106 | 6         | 2.48%   |
| 0x806ec    | 5         | 2.07%   |
| 0x806e9    | 5         | 2.07%   |
| 0x6fb      | 5         | 2.07%   |
| 0x506e3    | 5         | 2.07%   |
| 0x08701021 | 5         | 2.07%   |
| 0x08701013 | 5         | 2.07%   |
| 0x6fd      | 4         | 1.65%   |
| 0x20655    | 4         | 1.65%   |
| 0xa0652    | 3         | 1.24%   |
| 0x806c1    | 3         | 1.24%   |
| 0x406e3    | 3         | 1.24%   |
| 0x08108102 | 3         | 1.24%   |
| 0x05000119 | 3         | 1.24%   |
| 0x906ed    | 2         | 0.83%   |
| 0x6d8      | 2         | 0.83%   |
| 0x30678    | 2         | 0.83%   |
| 0x08600103 | 2         | 0.83%   |
| 0x0810100b | 2         | 0.83%   |
| 0x08001138 | 2         | 0.83%   |
| 0x06003106 | 2         | 0.83%   |
| 0x06000852 | 2         | 0.83%   |
| 0xf64      | 1         | 0.41%   |
| 0xf4a      | 1         | 0.41%   |
| 0xa0671    | 1         | 0.41%   |
| 0xa0655    | 1         | 0.41%   |
| 0xa0653    | 1         | 0.41%   |
| 0x906eb    | 1         | 0.41%   |
| 0x806eb    | 1         | 0.41%   |
| 0x706e5    | 1         | 0.41%   |
| 0x706a8    | 1         | 0.41%   |
| 0x706a1    | 1         | 0.41%   |
| 0x6f6      | 1         | 0.41%   |
| 0x50654    | 1         | 0.41%   |
| 0x406c4    | 1         | 0.41%   |
| 0x406c3    | 1         | 0.41%   |
| 0x206d7    | 1         | 0.41%   |
| 0x20652    | 1         | 0.41%   |
| 0x106ca    | 1         | 0.41%   |
| 0x10676    | 1         | 0.41%   |
| 0x10661    | 1         | 0.41%   |
| 0x0a50000c | 1         | 0.41%   |
| 0x0a201016 | 1         | 0.41%   |
| 0x0a201009 | 1         | 0.41%   |
| 0x08600102 | 1         | 0.41%   |
| 0x06001119 | 1         | 0.41%   |
| 0x02000032 | 1         | 0.41%   |
| 0x010000db | 1         | 0.41%   |
| 0x01000098 | 1         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 45        | 19.23%  |
| Haswell         | 30        | 12.82%  |
| Zen 2           | 23        | 9.83%   |
| SandyBridge     | 20        | 8.55%   |
| IvyBridge       | 20        | 8.55%   |
| Skylake         | 11        | 4.7%    |
| Core            | 11        | 4.7%    |
| Penryn          | 8         | 3.42%   |
| Broadwell       | 7         | 2.99%   |
| Westmere        | 6         | 2.56%   |
| Zen             | 5         | 2.14%   |
| CometLake       | 5         | 2.14%   |
| Zen 3           | 4         | 1.71%   |
| Silvermont      | 4         | 1.71%   |
| K8 Hammer       | 4         | 1.71%   |
| Zen+            | 3         | 1.28%   |
| TigerLake       | 3         | 1.28%   |
| Steamroller     | 3         | 1.28%   |
| Piledriver      | 3         | 1.28%   |
| K10             | 3         | 1.28%   |
| Bobcat          | 3         | 1.28%   |
| P6              | 2         | 0.85%   |
| NetBurst        | 2         | 0.85%   |
| Icelake         | 2         | 0.85%   |
| Goldmont plus   | 2         | 0.85%   |
| K8 & K10 hybrid | 1         | 0.43%   |
| K6              | 1         | 0.43%   |
| Goldmont        | 1         | 0.43%   |
| Excavator       | 1         | 0.43%   |
| Bonnell         | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 141       | 47.32%  |
| Nvidia            | 99        | 33.22%  |
| AMD               | 56        | 18.79%  |
| VIA Technologies  | 1         | 0.34%   |
| ASPEED Technology | 1         | 0.34%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 4.58%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 4.58%   |
| AMD Renoir                                                                               | 11        | 3.59%   |
| Intel UHD Graphics 620                                                                   | 9         | 2.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 2.61%   |
| Intel HD Graphics 630                                                                    | 7         | 2.29%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.29%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 2.29%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 1.63%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 1.63%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.63%   |
| Intel HD Graphics 620                                                                    | 5         | 1.63%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.63%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.63%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 4         | 1.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 1.31%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 1.31%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 1.31%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 1.31%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3         | 0.98%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 3         | 0.98%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.98%   |
| Intel HD Graphics 530                                                                    | 3         | 0.98%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.98%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.98%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 0.98%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.98%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 0.98%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.65%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.65%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 2         | 0.65%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.65%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 2         | 0.65%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 2         | 0.65%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 2         | 0.65%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.65%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.65%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 2         | 0.65%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 0.65%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 2         | 0.65%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.65%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 2         | 0.65%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.65%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 0.65%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 2         | 0.65%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.65%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 0.65%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.65%   |
| AMD Tonga PRO [Radeon R9 285/380]                                                        | 2         | 0.65%   |
| AMD RV610 [Radeon HD 2400 PRO]                                                           | 2         | 0.65%   |
| VIA Technologies K8M890CE/K8N890CE [Chrome 9]                                            | 1         | 0.33%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.33%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 0.33%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 0.33%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 83        | 35.32%  |
| Intel + Nvidia | 48        | 20.43%  |
| 1 x Nvidia     | 47        | 20%     |
| 1 x AMD        | 43        | 18.3%   |
| Intel + AMD    | 7         | 2.98%   |
| AMD + Nvidia   | 3         | 1.28%   |
| 2 x AMD        | 2         | 0.85%   |
| 1 x VIA        | 1         | 0.43%   |
| AMD + ASPEED   | 1         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 168       | 70.29%  |
| Proprietary | 64        | 26.78%  |
| Unknown     | 7         | 2.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 98        | 41%     |
| 1.01-2.0   | 47        | 19.67%  |
| 0.01-0.5   | 30        | 12.55%  |
| 3.01-4.0   | 21        | 8.79%   |
| 7.01-8.0   | 15        | 6.28%   |
| 0.51-1.0   | 13        | 5.44%   |
| 5.01-6.0   | 7         | 2.93%   |
| 8.01-16.0  | 5         | 2.09%   |
| 2.01-3.0   | 2         | 0.84%   |
| 4.01-5.0   | 1         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 33        | 12.27%  |
| Dell                    | 33        | 12.27%  |
| Chimei Innolux          | 29        | 10.78%  |
| AU Optronics            | 29        | 10.78%  |
| LG Display              | 18        | 6.69%   |
| Goldstar                | 18        | 6.69%   |
| BOE                     | 16        | 5.95%   |
| Chi Mei Optoelectronics | 10        | 3.72%   |
| Hewlett-Packard         | 9         | 3.35%   |
| ViewSonic               | 7         | 2.6%    |
| Sharp                   | 7         | 2.6%    |
| Philips                 | 7         | 2.6%    |
| Lenovo                  | 7         | 2.6%    |
| AOC                     | 6         | 2.23%   |
| BenQ                    | 5         | 1.86%   |
| Sony                    | 3         | 1.12%   |
| PANDA                   | 3         | 1.12%   |
| LG Philips              | 3         | 1.12%   |
| Hitachi                 | 3         | 1.12%   |
| Unknown                 | 2         | 0.74%   |
| RoverScan               | 2         | 0.74%   |
| Fujitsu Siemens         | 2         | 0.74%   |
| Ancor Communications    | 2         | 0.74%   |
| Acer                    | 2         | 0.74%   |
| Toshiba                 | 1         | 0.37%   |
| Tech Concepts           | 1         | 0.37%   |
| Seiko/Epson             | 1         | 0.37%   |
| LG Electronics          | 1         | 0.37%   |
| Lenovo Group Limited    | 1         | 0.37%   |
| KDB                     | 1         | 0.37%   |
| Eizo                    | 1         | 0.37%   |
| CSO                     | 1         | 0.37%   |
| CPT                     | 1         | 0.37%   |
| Belinea                 | 1         | 0.37%   |
| ASUSTek Computer        | 1         | 0.37%   |
| Apple                   | 1         | 0.37%   |
| Unknown                 | 1         | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Goldstar 27GL850 GSM5B80 2560x1440 697x392mm 31.5-inch                    | 3         | 1.05%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 3         | 1.05%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 3         | 1.05%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 3         | 1.05%   |
| ViewSonic VA703-4Series VSC6A1E 1280x1024 341x274mm 17.2-inch             | 2         | 0.7%    |
| Sony TV SNYDB01 1920x1080 1600x900mm 72.3-inch                            | 2         | 0.7%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 2         | 0.7%    |
| Samsung Electronics S32D850 SAM0BCB 2560x1440 708x398mm 32.0-inch         | 2         | 0.7%    |
| Samsung Electronics S24C650 SAM0B18 1920x1200 518x324mm 24.1-inch         | 2         | 0.7%    |
| Samsung Electronics LCD Monitor SEC3046 1366x768 340x190mm 15.3-inch      | 2         | 0.7%    |
| LG Display LCD Monitor LGD0685 1920x1080 309x174mm 14.0-inch              | 2         | 0.7%    |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                   | 2         | 0.7%    |
| Hitachi HISENSE HEC0030 3840x2160 1210x680mm 54.6-inch                    | 2         | 0.7%    |
| Hewlett-Packard ZR24w HWP2869 1920x1200 546x352mm 25.6-inch               | 2         | 0.7%    |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                      | 2         | 0.7%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 2         | 0.7%    |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                         | 2         | 0.7%    |
| Dell U2312HM DEL4073 1920x1080 510x290mm 23.1-inch                        | 2         | 0.7%    |
| Dell P2314H DEL4098 1920x1080 509x286mm 23.0-inch                         | 2         | 0.7%    |
| Dell 2407WFP DELA017 1920x1200 520x330mm 24.2-inch                        | 2         | 0.7%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.7%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 0.7%    |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch           | 2         | 0.7%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 0.7%    |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch          | 2         | 0.7%    |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch          | 2         | 0.7%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.7%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x194mm 15.5-inch  | 2         | 0.7%    |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch  | 2         | 0.7%    |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 2         | 0.7%    |
| BOE LCD Monitor BOE077A 1920x1080 294x165mm 13.3-inch                     | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch             | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 2         | 0.7%    |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                       | 2         | 0.7%    |
| ViewSonic VP2030 SERIES VSC131C 1600x1200 408x306mm 20.1-inch             | 1         | 0.35%   |
| ViewSonic VG2428wm VSCA426 1920x1080 520x290mm 23.4-inch                  | 1         | 0.35%   |
| ViewSonic VG170m VSCBF0C 1280x1024 338x270mm 17.0-inch                    | 1         | 0.35%   |
| ViewSonic VE902m VSC491B 1280x1024 376x301mm 19.0-inch                    | 1         | 0.35%   |
| ViewSonic VA2445 SERIES VSC712E 1920x1080 521x293mm 23.5-inch             | 1         | 0.35%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                     | 1         | 0.35%   |
| Unknown LCD Monitor GBT G34WQC 3440x1440                                  | 1         | 0.35%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                     | 1         | 0.35%   |
| Tech Concepts LCD Monitor MT5531 1920x1080                                | 1         | 0.35%   |
| Sony TV SNY7001 1920x1080                                                 | 1         | 0.35%   |
| Sharp LQ133M1JW40 SHP10CD 1920x1080 294x165mm 13.3-inch                   | 1         | 0.35%   |
| Sharp LCD Monitor SHP14AF 1920x1200 288x180mm 13.4-inch                   | 1         | 0.35%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 1         | 0.35%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                   | 1         | 0.35%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                   | 1         | 0.35%   |
| Seiko/Epson LCD Monitor 1920x1080                                         | 1         | 0.35%   |
| Samsung Electronics U28H75x SAM0E00 3840x2160 607x345mm 27.5-inch         | 1         | 0.35%   |
| Samsung Electronics U28H75x SAM0DFF 3840x2160 608x345mm 27.5-inch         | 1         | 0.35%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 1         | 0.35%   |
| Samsung Electronics TV SAM0289 1920x540                                   | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch      | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch      | 1         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 105       | 41.02%  |
| 1366x768 (WXGA)    | 39        | 15.23%  |
| 3840x2160 (4K)     | 20        | 7.81%   |
| 1920x1200 (WUXGA)  | 19        | 7.42%   |
| 1280x1024 (SXGA)   | 19        | 7.42%   |
| 2560x1440 (QHD)    | 15        | 5.86%   |
| 1600x900 (HD+)     | 12        | 4.69%   |
| 1280x800 (WXGA)    | 9         | 3.52%   |
| 3440x1440          | 5         | 1.95%   |
| 1680x1050 (WSXGA+) | 4         | 1.56%   |
| 1440x900 (WXGA+)   | 3         | 1.17%   |
| 2560x1600          | 2         | 0.78%   |
| 2560x1080          | 1         | 0.39%   |
| 2256x1504          | 1         | 0.39%   |
| 1920x540           | 1         | 0.39%   |
| 1600x1200          | 1         | 0.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 67        | 24.54%  |
| 13      | 24        | 8.79%   |
| 24      | 23        | 8.42%   |
| 17      | 22        | 8.06%   |
| 27      | 21        | 7.69%   |
| 14      | 21        | 7.69%   |
| 23      | 15        | 5.49%   |
| 21      | 13        | 4.76%   |
| Unknown | 11        | 4.03%   |
| 12      | 8         | 2.93%   |
| 19      | 6         | 2.2%    |
| 84      | 4         | 1.47%   |
| 34      | 4         | 1.47%   |
| 31      | 4         | 1.47%   |
| 72      | 3         | 1.1%    |
| 25      | 3         | 1.1%    |
| 22      | 3         | 1.1%    |
| 18      | 3         | 1.1%    |
| 54      | 2         | 0.73%   |
| 40      | 2         | 0.73%   |
| 33      | 2         | 0.73%   |
| 32      | 2         | 0.73%   |
| 20      | 2         | 0.73%   |
| 16      | 2         | 0.73%   |
| 65      | 1         | 0.37%   |
| 43      | 1         | 0.37%   |
| 29      | 1         | 0.37%   |
| 26      | 1         | 0.37%   |
| 11      | 1         | 0.37%   |
| 10      | 1         | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 108       | 40.6%   |
| 501-600     | 52        | 19.55%  |
| 201-300     | 24        | 9.02%   |
| 401-500     | 22        | 8.27%   |
| 351-400     | 17        | 6.39%   |
| 601-700     | 11        | 4.14%   |
| Unknown     | 11        | 4.14%   |
| 701-800     | 8         | 3.01%   |
| 1501-2000   | 7         | 2.63%   |
| 1001-1500   | 3         | 1.13%   |
| 801-900     | 2         | 0.75%   |
| 901-1000    | 1         | 0.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 170       | 69.39%  |
| 16/10   | 38        | 15.51%  |
| 5/4     | 15        | 6.12%   |
| Unknown | 10        | 4.08%   |
| 21/9    | 4         | 1.63%   |
| 4/3     | 3         | 1.22%   |
| 6/5     | 2         | 0.82%   |
| 3/2     | 2         | 0.82%   |
| 32/9    | 1         | 0.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 67        | 24.72%  |
| 81-90          | 33        | 12.18%  |
| 201-250        | 33        | 12.18%  |
| 301-350        | 22        | 8.12%   |
| 251-300        | 19        | 7.01%   |
| 141-150        | 14        | 5.17%   |
| 351-500        | 13        | 4.8%    |
| 71-80          | 12        | 4.43%   |
| 151-200        | 12        | 4.43%   |
| Unknown        | 11        | 4.06%   |
| More than 1000 | 10        | 3.69%   |
| 121-130        | 9         | 3.32%   |
| 61-70          | 8         | 2.95%   |
| 501-1000       | 3         | 1.11%   |
| 111-120        | 2         | 0.74%   |
| 51-60          | 1         | 0.37%   |
| 41-50          | 1         | 0.37%   |
| 131-140        | 1         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 90        | 34.22%  |
| 121-160       | 73        | 27.76%  |
| 101-120       | 62        | 23.57%  |
| 161-240       | 17        | 6.46%   |
| Unknown       | 11        | 4.18%   |
| 1-50          | 6         | 2.28%   |
| More than 240 | 4         | 1.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 184       | 76.67%  |
| 2     | 41        | 17.08%  |
| 3     | 8         | 3.33%   |
| 0     | 6         | 2.5%    |
| 4     | 1         | 0.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 126       | 36.1%   |
| Realtek Semiconductor             | 114       | 32.66%  |
| Qualcomm Atheros                  | 38        | 10.89%  |
| Broadcom                          | 12        | 3.44%   |
| TP-Link                           | 7         | 2.01%   |
| Ralink                            | 7         | 2.01%   |
| Nvidia                            | 5         | 1.43%   |
| MediaTek                          | 4         | 1.15%   |
| Ralink Technology                 | 3         | 0.86%   |
| Marvell Technology Group          | 3         | 0.86%   |
| Hewlett-Packard                   | 3         | 0.86%   |
| Fibocom                           | 3         | 0.86%   |
| Sierra Wireless                   | 2         | 0.57%   |
| Microsoft                         | 2         | 0.57%   |
| Lenovo                            | 2         | 0.57%   |
| Huawei Technologies               | 2         | 0.57%   |
| Ericsson Business Mobile Networks | 2         | 0.57%   |
| D-Link System                     | 2         | 0.57%   |
| Broadcom Limited                  | 2         | 0.57%   |
| VIA Technologies                  | 1         | 0.29%   |
| Van Ooijen Technische Informatica | 1         | 0.29%   |
| Samsung Electronics               | 1         | 0.29%   |
| Qualcomm Atheros Communications   | 1         | 0.29%   |
| JMicron Technology                | 1         | 0.29%   |
| DisplayLink                       | 1         | 0.29%   |
| D-Link                            | 1         | 0.29%   |
| ASUSTek Computer                  | 1         | 0.29%   |
| ASIX Electronics                  | 1         | 0.29%   |
| Aquantia                          | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 75        | 17.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 19        | 4.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 12        | 2.83%   |
| Intel Wireless 8265 / 8275                                              | 11        | 2.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 2.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 8         | 1.89%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 1.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 1.65%   |
| Intel Wireless 7265                                                     | 7         | 1.65%   |
| Intel I211 Gigabit Network Connection                                   | 7         | 1.65%   |
| Intel Wireless 7260                                                     | 6         | 1.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 1.18%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 1.18%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 1.18%   |
| Intel Ethernet Connection (7) I219-V                                    | 5         | 1.18%   |
| Intel Ethernet Connection (3) I218-LM                                   | 5         | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 1.18%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 0.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 0.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 0.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 4         | 0.94%   |
| Intel Wireless 8260                                                     | 4         | 0.94%   |
| Intel Wireless 3165                                                     | 4         | 0.94%   |
| Intel Ethernet Connection (6) I219-V                                    | 4         | 0.94%   |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 0.94%   |
| Intel 82566MM Gigabit Network Connection                                | 4         | 0.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.71%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.71%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 3         | 0.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 3         | 0.71%   |
| Intel Wireless 3160                                                     | 3         | 0.71%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.71%   |
| Intel Ethernet Connection (2) I219-V                                    | 3         | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 0.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 0.71%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.71%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.71%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 3         | 0.71%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 2         | 0.47%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                               | 2         | 0.47%   |
| TP-Link 802.11ac NIC                                                    | 2         | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.47%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.47%   |
| Ralink RT2500 Wireless 802.11bg                                         | 2         | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 2         | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 0.47%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.47%   |
| Nvidia CK804 Ethernet Controller                                        | 2         | 0.47%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                      | 2         | 0.47%   |
| Lenovo ThinkPad TBT3 LAN                                                | 2         | 0.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.47%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 0.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.47%   |
| Intel I210 Gigabit Network Connection                                   | 2         | 0.47%   |
| Intel Ethernet Connection I217-V                                        | 2         | 0.47%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 95        | 51.08%  |
| Qualcomm Atheros                | 28        | 15.05%  |
| Realtek Semiconductor           | 23        | 12.37%  |
| Broadcom                        | 8         | 4.3%    |
| TP-Link                         | 7         | 3.76%   |
| Ralink                          | 7         | 3.76%   |
| Ralink Technology               | 3         | 1.61%   |
| MediaTek                        | 3         | 1.61%   |
| Fibocom                         | 3         | 1.61%   |
| Sierra Wireless                 | 2         | 1.08%   |
| Microsoft                       | 2         | 1.08%   |
| Qualcomm Atheros Communications | 1         | 0.54%   |
| Hewlett-Packard                 | 1         | 0.54%   |
| D-Link System                   | 1         | 0.54%   |
| D-Link                          | 1         | 0.54%   |
| Broadcom Limited                | 1         | 0.54%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 11        | 5.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 5.85%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 4.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 3.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 3.72%   |
| Intel Wireless 7265                                                     | 7         | 3.72%   |
| Intel Wireless 7260                                                     | 6         | 3.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.66%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 2.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 2.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 2.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 2.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.13%   |
| Intel Wireless 8260                                                     | 4         | 2.13%   |
| Intel Wireless 3165                                                     | 4         | 2.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.6%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.6%    |
| Intel Wireless 3160                                                     | 3         | 1.6%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.6%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.6%    |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.6%    |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 3         | 1.6%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 2         | 1.06%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                               | 2         | 1.06%   |
| TP-Link 802.11ac NIC                                                    | 2         | 1.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.06%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.06%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.06%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.06%   |
| Ralink RT2500 Wireless 802.11bg                                         | 2         | 1.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.06%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                      | 2         | 1.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.06%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.06%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.06%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.06%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.06%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.53%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 0.53%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.53%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 0.53%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.53%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.53%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.53%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.53%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.53%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.53%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.53%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.53%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.53%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1         | 0.53%   |
| Microsoft Wireless XBox Controller Dongle                               | 1         | 0.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.53%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.53%   |
| Intel WiFi Link 5100                                                    | 1         | 0.53%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 103       | 46.4%   |
| Intel                    | 76        | 34.23%  |
| Qualcomm Atheros         | 16        | 7.21%   |
| Broadcom                 | 6         | 2.7%    |
| Nvidia                   | 5         | 2.25%   |
| Marvell Technology Group | 3         | 1.35%   |
| Lenovo                   | 2         | 0.9%    |
| VIA Technologies         | 1         | 0.45%   |
| Samsung Electronics      | 1         | 0.45%   |
| MediaTek                 | 1         | 0.45%   |
| JMicron Technology       | 1         | 0.45%   |
| Hewlett-Packard          | 1         | 0.45%   |
| DisplayLink              | 1         | 0.45%   |
| D-Link System            | 1         | 0.45%   |
| Broadcom Limited         | 1         | 0.45%   |
| ASUSTek Computer         | 1         | 0.45%   |
| ASIX Electronics         | 1         | 0.45%   |
| Aquantia                 | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 75        | 32.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 19        | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 12        | 5.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 8         | 3.51%   |
| Intel I211 Gigabit Network Connection                                         | 7         | 3.07%   |
| Intel Ethernet Connection I217-LM                                             | 5         | 2.19%   |
| Intel Ethernet Connection (7) I219-V                                          | 5         | 2.19%   |
| Intel Ethernet Connection (3) I218-LM                                         | 5         | 2.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 4         | 1.75%   |
| Intel Ethernet Connection (6) I219-V                                          | 4         | 1.75%   |
| Intel Ethernet Connection (4) I219-V                                          | 4         | 1.75%   |
| Intel 82566MM Gigabit Network Connection                                      | 4         | 1.75%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 3         | 1.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 3         | 1.32%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 1.32%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2         | 0.88%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 0.88%   |
| Nvidia CK804 Ethernet Controller                                              | 2         | 0.88%   |
| Lenovo ThinkPad TBT3 LAN                                                      | 2         | 0.88%   |
| Intel I210 Gigabit Network Connection                                         | 2         | 0.88%   |
| Intel Ethernet Connection I217-V                                              | 2         | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2         | 0.88%   |
| Intel Ethernet Connection (2) I218-V                                          | 2         | 0.88%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 0.88%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2         | 0.88%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1         | 0.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1         | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 1         | 0.44%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 0.44%   |
| Nvidia nForce2 Ethernet Controller                                            | 1         | 0.44%   |
| Nvidia MCP77 Ethernet                                                         | 1         | 0.44%   |
| Nvidia MCP61 Ethernet                                                         | 1         | 0.44%   |
| MediaTek moto e(6) plus                                                       | 1         | 0.44%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                       | 1         | 0.44%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1         | 0.44%   |
| Marvell Group 88E8052 PCI-E ASF Gigabit Ethernet Controller                   | 1         | 0.44%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 1         | 0.44%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 0.44%   |
| Intel Ethernet Controller I225-V                                              | 1         | 0.44%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.44%   |
| Intel Ethernet Connection I218-V                                              | 1         | 0.44%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 0.44%   |
| Intel Ethernet Connection (5) I219-LM                                         | 1         | 0.44%   |
| Intel Ethernet Connection (13) I219-V                                         | 1         | 0.44%   |
| Intel Ethernet Connection (11) I219-LM                                        | 1         | 0.44%   |
| Intel Ethernet Connection (10) I219-V                                         | 1         | 0.44%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1         | 0.44%   |
| Intel 82579V Gigabit Network Connection                                       | 1         | 0.44%   |
| Intel 82578DM Gigabit Network Connection                                      | 1         | 0.44%   |
| Intel 82574L Gigabit Network Connection                                       | 1         | 0.44%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.44%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1         | 0.44%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1         | 0.44%   |
| HP lt4120 Snapdragon X5 LTE                                                   | 1         | 0.44%   |
| DisplayLink Dell Universal Dock D6000                                         | 1         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 211       | 53.69%  |
| WiFi     | 174       | 44.27%  |
| Modem    | 8         | 2.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 134       | 56.07%  |
| Ethernet | 105       | 43.93%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 131       | 55.98%  |
| 1     | 94        | 40.17%  |
| 3     | 4         | 1.71%   |
| 0     | 4         | 1.71%   |
| 6     | 1         | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 212       | 89.45%  |
| Yes  | 25        | 10.55%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 67        | 48.91%  |
| Cambridge Silicon Radio         | 15        | 10.95%  |
| Qualcomm Atheros Communications | 12        | 8.76%   |
| Realtek Semiconductor           | 11        | 8.03%   |
| Broadcom                        | 11        | 8.03%   |
| IMC Networks                    | 7         | 5.11%   |
| Hewlett-Packard                 | 4         | 2.92%   |
| Realtek                         | 2         | 1.46%   |
| Toshiba                         | 1         | 0.73%   |
| Ralink                          | 1         | 0.73%   |
| Lite-On Technology              | 1         | 0.73%   |
| Integrated System Solution      | 1         | 0.73%   |
| Foxconn / Hon Hai               | 1         | 0.73%   |
| Dell                            | 1         | 0.73%   |
| ASUSTek Computer                | 1         | 0.73%   |
| Apple                           | 1         | 0.73%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 35        | 25.55%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 15        | 10.95%  |
| Intel AX201 Bluetooth                                 | 8         | 5.84%   |
| Realtek Bluetooth Radio                               | 7         | 5.11%   |
| Intel AX200 Bluetooth                                 | 7         | 5.11%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 6         | 4.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 6         | 4.38%   |
| IMC Networks Bluetooth Device                         | 5         | 3.65%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3         | 2.19%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 3         | 2.19%   |
| Intel Bluetooth Device                                | 3         | 2.19%   |
| HP Broadcom 2070 Bluetooth Combo                      | 3         | 2.19%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]      | 3         | 2.19%   |
| Realtek RTL8723B Bluetooth                            | 2         | 1.46%   |
| Realtek Bluetooth Radio                               | 2         | 1.46%   |
| Qualcomm Atheros  Bluetooth Device                    | 2         | 1.46%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 2         | 1.46%   |
| Intel AX210 Bluetooth                                 | 2         | 1.46%   |
| Broadcom BCM43142 Bluetooth 4.0                       | 2         | 1.46%   |
| Broadcom BCM2045B (BDC-2.1)                           | 2         | 1.46%   |
| Broadcom BCM2045 Bluetooth                            | 2         | 1.46%   |
| Toshiba Bluetooth USB Host Controller                 | 1         | 0.73%   |
| Realtek RTL8821A Bluetooth                            | 1         | 0.73%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 0.73%   |
| Ralink RT3290 Bluetooth                               | 1         | 0.73%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 0.73%   |
| Qualcomm Atheros AR3012 Bluetooth                     | 1         | 0.73%   |
| Lite-On Bluetooth Device                              | 1         | 0.73%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.73%   |
| IMC Networks BCM20702A0                               | 1         | 0.73%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 1         | 0.73%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 1         | 0.73%   |
| Foxconn / Hon Hai Wireless_Device                     | 1         | 0.73%   |
| Dell BCM20702A0 Bluetooth Module                      | 1         | 0.73%   |
| Broadcom HP Portable SoftSailing                      | 1         | 0.73%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                  | 1         | 0.73%   |
| ASUS Bluetooth Radio                                  | 1         | 0.73%   |
| Apple Bluetooth Host Controller                       | 1         | 0.73%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 175       | 52.24%  |
| AMD                     | 63        | 18.81%  |
| Nvidia                  | 62        | 18.51%  |
| C-Media Electronics     | 7         | 2.09%   |
| Razer USA               | 3         | 0.9%    |
| Lenovo                  | 3         | 0.9%    |
| SteelSeries ApS         | 2         | 0.6%    |
| Realtek Semiconductor   | 2         | 0.6%    |
| Logitech                | 2         | 0.6%    |
| Kingston Technology     | 2         | 0.6%    |
| Focusrite-Novation      | 2         | 0.6%    |
| VIA Technologies        | 1         | 0.3%    |
| Texas Instruments       | 1         | 0.3%    |
| TerraTec Electronic     | 1         | 0.3%    |
| Syntek                  | 1         | 0.3%    |
| Samson Technologies     | 1         | 0.3%    |
| Roland                  | 1         | 0.3%    |
| Micronas                | 1         | 0.3%    |
| Mark of the Unicorn     | 1         | 0.3%    |
| M-Audio                 | 1         | 0.3%    |
| JMTek                   | 1         | 0.3%    |
| Creative Labs           | 1         | 0.3%    |
| BEHRINGER International | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 21        | 5.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 19        | 4.87%   |
| AMD Family 17h/19h HD Audio Controller                                     | 19        | 4.87%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18        | 4.62%   |
| Intel Sunrise Point-LP HD Audio                                            | 17        | 4.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13        | 3.33%   |
| AMD Starship/Matisse HD Audio Controller                                   | 12        | 3.08%   |
| Intel Cannon Lake PCH cAVS                                                 | 10        | 2.56%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 2.31%   |
| Nvidia TU106 High Definition Audio Controller                              | 7         | 1.79%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 1.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7         | 1.79%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 1.79%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 1.79%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 1.79%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 1.79%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 1.79%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7         | 1.79%   |
| Nvidia GP104 High Definition Audio Controller                              | 6         | 1.54%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 1.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 1.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 1.54%   |
| AMD FCH Azalia Controller                                                  | 6         | 1.54%   |
| Intel CM238 HD Audio Controller                                            | 5         | 1.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.28%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 1.28%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.03%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 1.03%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.77%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.77%   |
| Nvidia GP108 High Definition Audio Controller                              | 3         | 0.77%   |
| Nvidia GP102 HDMI Audio Controller                                         | 3         | 0.77%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3         | 0.77%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.77%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 0.77%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 0.77%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 0.77%   |
| C-Media Electronics Blue Snowball                                          | 3         | 0.77%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.51%   |
| Razer USA Gaming Headset [Kraken USB]                                      | 2         | 0.51%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.51%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.51%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.51%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.51%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 0.51%   |
| Nvidia CK804 AC'97 Audio Controller                                        | 2         | 0.51%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                   | 2         | 0.51%   |
| Kingston Technology HyperX 7.1 Audio                                       | 2         | 0.51%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.51%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2         | 0.51%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2         | 0.51%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 2         | 0.51%   |
| C-Media Electronics USB Audio Device                                       | 2         | 0.51%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 0.51%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 0.51%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 2         | 0.51%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2         | 0.51%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 34        | 20.86%  |
| SK hynix            | 24        | 14.72%  |
| Kingston            | 20        | 12.27%  |
| Micron Technology   | 17        | 10.43%  |
| Unknown             | 16        | 9.82%   |
| G.Skill             | 15        | 9.2%    |
| Crucial             | 12        | 7.36%   |
| Corsair             | 5         | 3.07%   |
| Ramaxel Technology  | 4         | 2.45%   |
| A-DATA Technology   | 3         | 1.84%   |
| Patriot             | 2         | 1.23%   |
| Elpida              | 2         | 1.23%   |
| Apacer              | 2         | 1.23%   |
| Unknown (ABCD)      | 1         | 0.61%   |
| Unifosa             | 1         | 0.61%   |
| Silicon Power       | 1         | 0.61%   |
| Nanya Technology    | 1         | 0.61%   |
| ASint Technology    | 1         | 0.61%   |
| Aeneon              | 1         | 0.61%   |
| Unknown             | 1         | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                        | 4         | 2.25%   |
| Unknown RAM Module 512MB DIMM SDRAM                                          | 2         | 1.12%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                         | 2         | 1.12%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s                        | 2         | 1.12%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                        | 2         | 1.12%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s                        | 2         | 1.12%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s                     | 2         | 1.12%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s                       | 2         | 1.12%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s                     | 2         | 1.12%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s                        | 2         | 1.12%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s                  | 2         | 1.12%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                                    | 1         | 0.56%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                                 | 1         | 0.56%   |
| Unknown RAM Module 512MB SODIMM DDR2                                         | 1         | 0.56%   |
| Unknown RAM Module 512MB DIMM                                                | 1         | 0.56%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR3 1867MT/s                       | 1         | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                     | 1         | 0.56%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                         | 1         | 0.56%   |
| Unknown RAM Module 256MB DIMM                                                | 1         | 0.56%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                                | 1         | 0.56%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                        | 1         | 0.56%   |
| Unknown RAM Module 2048MB DIMM DDR3 800MT/s                                  | 1         | 0.56%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                                  | 1         | 0.56%   |
| Unknown RAM Module 1GB DIMM SDRAM                                            | 1         | 0.56%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                                  | 1         | 0.56%   |
| Unknown RAM Module 1024MB DIMM                                               | 1         | 0.56%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s             | 1         | 0.56%   |
| Unifosa RAM GU332G0AJEPR8H2L 2048MB SODIMM DDR2 667MT/s                      | 1         | 0.56%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                              | 1         | 0.56%   |
| SK hynix RAM Module 8192MB DIMM DDR3 1333MT/s                                | 1         | 0.56%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                                 | 1         | 0.56%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2133MT/s                              | 1         | 0.56%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1333MT/s                                | 1         | 0.56%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s                        | 1         | 0.56%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s                         | 1         | 0.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.56%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s                    | 1         | 0.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                       | 1         | 0.56%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s                      | 1         | 0.56%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s                         | 1         | 0.56%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s                    | 1         | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                       | 1         | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1334MT/s                    | 1         | 0.56%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s                       | 1         | 0.56%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                       | 1         | 0.56%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s                      | 1         | 0.56%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s                      | 1         | 0.56%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                       | 1         | 0.56%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s                       | 1         | 0.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                       | 1         | 0.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                       | 1         | 0.56%   |
| SK hynix RAM 5A5A5A5A5A5A5A5A5A5A5A5A5A5A5A5A5A5A 4096MB SODIMM DDR2 800MT/s | 1         | 0.56%   |
| SK hynix RAM 262626262626262626262626262626262626 4096MB SODIMM DDR2 800MT/s | 1         | 0.56%   |
| Silicon Power RAM SP008GBLTU160N02 8192MB DIMM DDR3 1600MT/s                 | 1         | 0.56%   |
| Silicon Power RAM DCLT8GN128S 8GB DIMM DDR3 1600MT/s                         | 1         | 0.56%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2400MT/s                              | 1         | 0.56%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                        | 1         | 0.56%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s                        | 1         | 0.56%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                        | 1         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 67        | 48.2%   |
| DDR3    | 47        | 33.81%  |
| DDR2    | 8         | 5.76%   |
| SDRAM   | 7         | 5.04%   |
| LPDDR4  | 3         | 2.16%   |
| Unknown | 3         | 2.16%   |
| LPDDR3  | 2         | 1.44%   |
| DDR     | 2         | 1.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 74        | 54.01%  |
| DIMM         | 57        | 41.61%  |
| Row Of Chips | 6         | 4.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 53        | 34.87%  |
| 4096  | 43        | 28.29%  |
| 16384 | 22        | 14.47%  |
| 2048  | 17        | 11.18%  |
| 1024  | 7         | 4.61%   |
| 512   | 5         | 3.29%   |
| 32768 | 4         | 2.63%   |
| 256   | 1         | 0.66%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 29        | 18.95%  |
| 2667    | 24        | 15.69%  |
| 3200    | 19        | 12.42%  |
| 1333    | 12        | 7.84%   |
| 2400    | 8         | 5.23%   |
| 2133    | 7         | 4.58%   |
| Unknown | 7         | 4.58%   |
| 3600    | 6         | 3.92%   |
| 1334    | 6         | 3.92%   |
| 800     | 4         | 2.61%   |
| 2666    | 3         | 1.96%   |
| 1067    | 3         | 1.96%   |
| 667     | 3         | 1.96%   |
| 4267    | 2         | 1.31%   |
| 4199    | 2         | 1.31%   |
| 3666    | 2         | 1.31%   |
| 3266    | 2         | 1.31%   |
| 1867    | 2         | 1.31%   |
| 3800    | 1         | 0.65%   |
| 3334    | 1         | 0.65%   |
| 3000    | 1         | 0.65%   |
| 2933    | 1         | 0.65%   |
| 2733    | 1         | 0.65%   |
| 1866    | 1         | 0.65%   |
| 1800    | 1         | 0.65%   |
| 1400    | 1         | 0.65%   |
| 1066    | 1         | 0.65%   |
| 975     | 1         | 0.65%   |
| 533     | 1         | 0.65%   |
| 400     | 1         | 0.65%   |

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
| Chicony Electronics                    | 30        | 21.58%  |
| Microdia                               | 14        | 10.07%  |
| Realtek Semiconductor                  | 12        | 8.63%   |
| Sunplus Innovation Technology          | 11        | 7.91%   |
| IMC Networks                           | 11        | 7.91%   |
| Acer                                   | 11        | 7.91%   |
| Logitech                               | 10        | 7.19%   |
| Silicon Motion                         | 5         | 3.6%    |
| Lite-On Technology                     | 5         | 3.6%    |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.6%    |
| Syntek                                 | 4         | 2.88%   |
| Suyin                                  | 4         | 2.88%   |
| Apple                                  | 3         | 2.16%   |
| Quanta                                 | 2         | 1.44%   |
| Luxvisions Innotech Limited            | 2         | 1.44%   |
| Arkmicro Technologies                  | 2         | 1.44%   |
| Z-Star Microelectronics                | 1         | 0.72%   |
| Samsung Electronics                    | 1         | 0.72%   |
| Microsoft                              | 1         | 0.72%   |
| Lenovo                                 | 1         | 0.72%   |
| Importek                               | 1         | 0.72%   |
| Huddly                                 | 1         | 0.72%   |
| Creative Technology                    | 1         | 0.72%   |
| Alcor Micro                            | 1         | 0.72%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 9         | 6.34%   |
| Chicony Integrated Camera                               | 5         | 3.52%   |
| Lite-On Integrated Camera                               | 4         | 2.82%   |
| Realtek USB Camera                                      | 3         | 2.11%   |
| Logitech Webcam C930e                                   | 3         | 2.11%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 2.11%   |
| IMC Networks Integrated Camera                          | 3         | 2.11%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 3         | 2.11%   |
| Chicony Integrated HP HD Webcam                         | 3         | 2.11%   |
| Acer Integrated Camera                                  | 3         | 2.11%   |
| Syntek Integrated Camera                                | 2         | 1.41%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 1.41%   |
| Sunplus ASUS USB2.0 Webcam                              | 2         | 1.41%   |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.] | 2         | 1.41%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.41%   |
| Realtek Lenovo EasyCamera                               | 2         | 1.41%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.41%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 1.41%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 1.41%   |
| Logitech Webcam C270                                    | 2         | 1.41%   |
| Logitech HD Webcam C525                                 | 2         | 1.41%   |
| Logitech HD Pro Webcam C920                             | 2         | 1.41%   |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 1.41%   |
| Chicony ThinkPad T490 Webcam                            | 2         | 1.41%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 1.41%   |
| Chicony HP Wide Vision HD Camera                        | 2         | 1.41%   |
| Chicony HP HD Webcam                                    | 2         | 1.41%   |
| Arkmicro USB2.0 PC CAMERA                               | 2         | 1.41%   |
| Apple iPhone 5/5C/5S/6/SE                               | 2         | 1.41%   |
| Z-Star Vimicro USB Camera (Altair)                      | 1         | 0.7%    |
| Syntek USB2.0 UVC PC Camera                             | 1         | 0.7%    |
| Syntek Lenovo EasyCamera                                | 1         | 0.7%    |
| Suyin USB Webcam                                        | 1         | 0.7%    |
| Suyin Integrated_Webcam_HD                              | 1         | 0.7%    |
| Suyin HD WebCam                                         | 1         | 0.7%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 1         | 0.7%    |
| Sunplus Laptop_Integrated_Webcam_HD                     | 1         | 0.7%    |
| Sunplus Integrated Webcam                               | 1         | 0.7%    |
| Sunplus HP Wide Vision HD                               | 1         | 0.7%    |
| Sunplus HP Universal Camera                             | 1         | 0.7%    |
| Sunplus HD Webcam                                       | 1         | 0.7%    |
| Sunplus Dell HD Webcam                                  | 1         | 0.7%    |
| Sunplus Aukey-PC-LM1E Camera                            | 1         | 0.7%    |
| Silicon Motion WebCam SC-13HDL11431N                    | 1         | 0.7%    |
| Silicon Motion WebCam SC-10HDP12631N                    | 1         | 0.7%    |
| Silicon Motion WebCam SC-10HDD12636N                    | 1         | 0.7%    |
| Samsung Galaxy A5 (MTP)                                 | 1         | 0.7%    |
| Realtek Integrated Webcam HD                            | 1         | 0.7%    |
| Realtek Integrated Camera                               | 1         | 0.7%    |
| Realtek EasyCamera                                      | 1         | 0.7%    |
| Quanta HP Webcam                                        | 1         | 0.7%    |
| Quanta HP HD Camera                                     | 1         | 0.7%    |
| Microsoft LifeCam HD-3000                               | 1         | 0.7%    |
| Microdia Webcam SC-10HDD12636P                          | 1         | 0.7%    |
| Microdia Sonix USB 2.0 Camera                           | 1         | 0.7%    |
| Microdia Laptop_Integrated_Webcam_FHD                   | 1         | 0.7%    |
| Logitech B525 HD Webcam                                 | 1         | 0.7%    |
| Lite-On HP HD Webcam                                    | 1         | 0.7%    |
| Lenovo Integrated Webcam [R5U877]                       | 1         | 0.7%    |
| Importek TOSHIBA Web Camera - HD                        | 1         | 0.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 44.74%  |
| Synaptics                  | 9         | 23.68%  |
| Upek                       | 4         | 10.53%  |
| STMicroelectronics         | 4         | 10.53%  |
| Shenzhen Goodix Technology | 2         | 5.26%   |
| Elan Microelectronics      | 1         | 2.63%   |
| AuthenTec                  | 1         | 2.63%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                  | 5         | 13.16%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 4         | 10.53%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 4         | 10.53%  |
| STMicroelectronics Fingerprint Reader                       | 4         | 10.53%  |
| Validity Sensors VFS471 Fingerprint Reader                  | 3         | 7.89%   |
| Synaptics Metallica MIS Touch Fingerprint Reader            | 3         | 7.89%   |
| Validity Sensors VFS5011 Fingerprint Reader                 | 2         | 5.26%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 2         | 5.26%   |
| Shenzhen Goodix FingerPrint                                 | 2         | 5.26%   |
| Unknown                                                     | 2         | 5.26%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor           | 1         | 2.63%   |
| Validity Sensors VFS101 Fingerprint Reader                  | 1         | 2.63%   |
| Validity Sensors Synaptics WBDI                             | 1         | 2.63%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 2.63%   |
| Validity Sensors Fingerprint scanner                        | 1         | 2.63%   |
| Elan ELAN:Fingerprint                                       | 1         | 2.63%   |
| AuthenTec AES2550 Fingerprint Sensor                        | 1         | 2.63%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| OmniKey               | 17        | 39.53%  |
| Alcor Micro           | 17        | 39.53%  |
| Lenovo                | 3         | 6.98%   |
| Broadcom              | 3         | 6.98%   |
| Gemalto (was Gemplus) | 2         | 4.65%   |
| O2 Micro              | 1         | 2.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| OmniKey CardMan 1021                              | 14        | 32.56%  |
| Alcor Micro AU9540 Smartcard Reader               | 14        | 32.56%  |
| OmniKey CardMan 4321                              | 3         | 6.98%   |
| Lenovo Integrated Smart Card Reader               | 3         | 6.98%   |
| Broadcom 58200                                    | 3         | 6.98%   |
| Alcor Micro Watchdata W 1981                      | 3         | 6.98%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 2         | 4.65%   |
| O2 Micro OZ776 CCID Smartcard Reader              | 1         | 2.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 154       | 64.17%  |
| 1     | 67        | 27.92%  |
| 2     | 19        | 7.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 38        | 36.54%  |
| Graphics card            | 24        | 23.08%  |
| Chipcard                 | 24        | 23.08%  |
| Net/wireless             | 6         | 5.77%   |
| Communication controller | 3         | 2.88%   |
| Net/ethernet             | 2         | 1.92%   |
| Multimedia controller    | 2         | 1.92%   |
| Camera                   | 2         | 1.92%   |
| Sound                    | 1         | 0.96%   |
| Modem                    | 1         | 0.96%   |
| Bluetooth                | 1         | 0.96%   |

