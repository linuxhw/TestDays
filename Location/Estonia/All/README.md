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

Total: 345

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04      | 31        | 12.2%   |
| Ubuntu 18.04      | 22        | 8.66%   |
| ROSA R11          | 10        | 3.94%   |
| Arch              | 10        | 3.94%   |
| Fedora 34         | 8         | 3.15%   |
| Ubuntu 19.04      | 7         | 2.76%   |
| ROSA R8.1         | 7         | 2.76%   |
| OpenMandriva 4.3  | 7         | 2.76%   |
| Kubuntu 20.04     | 7         | 2.76%   |
| Linux Mint 20.1   | 6         | 2.36%   |
| ArcoLinux Rolling | 6         | 2.36%   |
| Arch Rolling      | 6         | 2.36%   |
| OpenMandriva 4.2  | 5         | 1.97%   |
| Manjaro           | 5         | 1.97%   |
| Fedora 35         | 5         | 1.97%   |
| Ubuntu 22.04      | 4         | 1.57%   |
| ROSA R9           | 4         | 1.57%   |
| ROSA 12.2         | 4         | 1.57%   |
| KDE neon 20.04    | 4         | 1.57%   |
| Fedora 36         | 4         | 1.57%   |
| Ubuntu 21.10      | 3         | 1.18%   |
| Ubuntu 19.10      | 3         | 1.18%   |
| ROSA R10          | 3         | 1.18%   |
| Pop!_OS 20.04     | 3         | 1.18%   |
| Gentoo 2.6        | 3         | 1.18%   |
| Fedora 31         | 3         | 1.18%   |
| Debian Testing    | 3         | 1.18%   |
| Xubuntu 20.04     | 2         | 0.79%   |
| Xubuntu 18.04     | 2         | 0.79%   |
| Ubuntu MATE 20.04 | 2         | 0.79%   |
| Ubuntu 21.04      | 2         | 0.79%   |
| Ubuntu 20.10      | 2         | 0.79%   |
| Ubuntu 16.04      | 2         | 0.79%   |
| Reborn OS         | 2         | 0.79%   |
| Pop!_OS 21.10     | 2         | 0.79%   |
| Pop!_OS 21.04     | 2         | 0.79%   |
| Manjaro 20.1      | 2         | 0.79%   |
| LMDE 4            | 2         | 0.79%   |
| Linux Mint 20.2   | 2         | 0.79%   |
| Linux Mint 19.3   | 2         | 0.79%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 76        | 30.52%  |
| ROSA         | 30        | 12.05%  |
| Fedora       | 21        | 8.43%   |
| Arch         | 16        | 6.43%   |
| Linux Mint   | 14        | 5.62%   |
| OpenMandriva | 13        | 5.22%   |
| Manjaro      | 13        | 5.22%   |
| Kubuntu      | 9         | 3.61%   |
| Pop!_OS      | 7         | 2.81%   |
| Debian       | 7         | 2.81%   |
| ArcoLinux    | 6         | 2.41%   |
| Xubuntu      | 5         | 2.01%   |
| KDE neon     | 4         | 1.61%   |
| Gentoo       | 4         | 1.61%   |
| Elementary   | 4         | 1.61%   |
| Ubuntu MATE  | 3         | 1.2%    |
| Endless      | 3         | 1.2%    |
| Clear Linux  | 3         | 1.2%    |
| Zorin        | 2         | 0.8%    |
| Reborn OS    | 2         | 0.8%    |
| LMDE         | 2         | 0.8%    |
| Ubuntu Unity | 1         | 0.4%    |
| SteamOS      | 1         | 0.4%    |
| openSUSE     | 1         | 0.4%    |
| MX           | 1         | 0.4%    |
| Lubuntu      | 1         | 0.4%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 5.4.0-42-generic                    | 8         | 2.91%   |
| 5.16.7-desktop-1omv4003             | 7         | 2.55%   |
| 5.10.14-desktop-1omv4002            | 5         | 1.82%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 4         | 1.45%   |
| 5.4.0-65-generic                    | 3         | 1.09%   |
| 5.4.0-47-generic                    | 3         | 1.09%   |
| 5.4.0-28-generic                    | 3         | 1.09%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 3         | 1.09%   |
| 5.8.0-63-generic                    | 2         | 0.73%   |
| 5.8.0-53-generic                    | 2         | 0.73%   |
| 5.5.2-1-MANJARO                     | 2         | 0.73%   |
| 5.4.0-88-generic                    | 2         | 0.73%   |
| 5.4.0-58-generic                    | 2         | 0.73%   |
| 5.4.0-53-generic                    | 2         | 0.73%   |
| 5.4.0-45-generic                    | 2         | 0.73%   |
| 5.4.0-33-generic                    | 2         | 0.73%   |
| 5.4.0-29-generic                    | 2         | 0.73%   |
| 5.4.0-26-generic                    | 2         | 0.73%   |
| 5.3.0-40-generic                    | 2         | 0.73%   |
| 5.15.5-76051505-generic             | 2         | 0.73%   |
| 5.15.2-arch1-1                      | 2         | 0.73%   |
| 5.15.0-46-generic                   | 2         | 0.73%   |
| 5.15.0-41-generic                   | 2         | 0.73%   |
| 5.13.12-200.fc34.x86_64             | 2         | 0.73%   |
| 5.13.0-39-generic                   | 2         | 0.73%   |
| 5.11.0-37-generic                   | 2         | 0.73%   |
| 5.11.0-34-generic                   | 2         | 0.73%   |
| 5.11.0-27-generic                   | 2         | 0.73%   |
| 5.11.0-25-generic                   | 2         | 0.73%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 2         | 0.73%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 2         | 0.73%   |
| 5.0.0-23-generic                    | 2         | 0.73%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 2         | 0.73%   |
| 4.18.0-15-generic                   | 2         | 0.73%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 2         | 0.73%   |
| 4.15.0-desktop-45.1rosa-i586        | 2         | 0.73%   |
| 4.15.0-50-generic                   | 2         | 0.73%   |
| 4.15.0-46-generic                   | 2         | 0.73%   |
| 4.15.0-45-generic                   | 2         | 0.73%   |
| 5.9.16-1-MANJARO                    | 1         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.0    | 46        | 17.42%  |
| 4.15.0   | 26        | 9.85%   |
| 5.11.0   | 14        | 5.3%    |
| 5.8.0    | 11        | 4.17%   |
| 5.13.0   | 11        | 4.17%   |
| 5.0.0    | 10        | 3.79%   |
| 5.15.0   | 9         | 3.41%   |
| 5.16.7   | 7         | 2.65%   |
| 5.3.0    | 6         | 2.27%   |
| 4.18.0   | 6         | 2.27%   |
| 5.10.14  | 5         | 1.89%   |
| 4.9.20   | 5         | 1.89%   |
| 5.15.2   | 3         | 1.14%   |
| 5.13.12  | 3         | 1.14%   |
| 5.10.0   | 3         | 1.14%   |
| 4.9.9    | 3         | 1.14%   |
| 5.8.10   | 2         | 0.76%   |
| 5.5.2    | 2         | 0.76%   |
| 5.17.1   | 2         | 0.76%   |
| 5.15.5   | 2         | 0.76%   |
| 5.13.13  | 2         | 0.76%   |
| 5.11.12  | 2         | 0.76%   |
| 5.11.11  | 2         | 0.76%   |
| 5.10.74  | 2         | 0.76%   |
| 5.10.118 | 2         | 0.76%   |
| 4.9.60   | 2         | 0.76%   |
| 4.19.0   | 2         | 0.76%   |
| 5.9.16   | 1         | 0.38%   |
| 5.9.13   | 1         | 0.38%   |
| 5.9.10   | 1         | 0.38%   |
| 5.9.0    | 1         | 0.38%   |
| 5.8.6    | 1         | 0.38%   |
| 5.7.0    | 1         | 0.38%   |
| 5.6.13   | 1         | 0.38%   |
| 5.6.11   | 1         | 0.38%   |
| 5.6.10   | 1         | 0.38%   |
| 5.5.9    | 1         | 0.38%   |
| 5.5.6    | 1         | 0.38%   |
| 5.4.8    | 1         | 0.38%   |
| 5.4.64   | 1         | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 52        | 19.7%   |
| 4.15    | 26        | 9.85%   |
| 5.13    | 23        | 8.71%   |
| 5.10    | 20        | 7.58%   |
| 5.11    | 19        | 7.2%    |
| 5.15    | 16        | 6.06%   |
| 5.8     | 14        | 5.3%    |
| 4.9     | 14        | 5.3%    |
| 5.16    | 12        | 4.55%   |
| 5.0     | 11        | 4.17%   |
| 5.3     | 8         | 3.03%   |
| 5.14    | 7         | 2.65%   |
| 5.17    | 6         | 2.27%   |
| 4.18    | 6         | 2.27%   |
| 5.9     | 4         | 1.52%   |
| 5.5     | 4         | 1.52%   |
| 5.12    | 4         | 1.52%   |
| 4.19    | 4         | 1.52%   |
| 5.6     | 3         | 1.14%   |
| 5.18    | 3         | 1.14%   |
| 4.1     | 2         | 0.76%   |
| 5.7     | 1         | 0.38%   |
| 5.19    | 1         | 0.38%   |
| 5.1     | 1         | 0.38%   |
| 4.4     | 1         | 0.38%   |
| 4.10    | 1         | 0.38%   |
| 3.16    | 1         | 0.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 232       | 95.47%  |
| i686   | 11        | 4.53%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 82        | 33.06%  |
| KDE5       | 42        | 16.94%  |
| Unknown    | 42        | 16.94%  |
| KDE4       | 19        | 7.66%   |
| XFCE       | 18        | 7.26%   |
| X-Cinnamon | 12        | 4.84%   |
| MATE       | 9         | 3.63%   |
| KDE        | 5         | 2.02%   |
| Pantheon   | 4         | 1.61%   |
| LXQt       | 3         | 1.21%   |
| i3         | 3         | 1.21%   |
| Unity      | 2         | 0.81%   |
| awesome    | 2         | 0.81%   |
| sway       | 1         | 0.4%    |
| openbox    | 1         | 0.4%    |
| LXDE       | 1         | 0.4%    |
| Cinnamon   | 1         | 0.4%    |
| Budgie     | 1         | 0.4%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 195       | 79.59%  |
| Wayland | 32        | 13.06%  |
| Unknown | 16        | 6.53%   |
| Tty     | 2         | 0.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 119       | 48.57%  |
| SDDM    | 44        | 17.96%  |
| GDM     | 31        | 12.65%  |
| KDM     | 19        | 7.76%   |
| TDM     | 12        | 4.9%    |
| GDM3    | 11        | 4.49%   |
| LightDM | 9         | 3.67%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| en_US           | 109       | 43.95%  |
| Unknown         | 59        | 23.79%  |
| et_EE           | 37        | 14.92%  |
| ru_RU           | 23        | 9.27%   |
| en_GB           | 8         | 3.23%   |
| de_DE           | 3         | 1.21%   |
| fr_FR           | 2         | 0.81%   |
| en_DK           | 2         | 0.81%   |
| uk_UA           | 1         | 0.4%    |
| ru_UA           | 1         | 0.4%    |
| pl_PL           | 1         | 0.4%    |
| en_US.iso885915 | 1         | 0.4%    |
| C               | 1         | 0.4%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 137       | 55.02%  |
| EFI  | 112       | 44.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 181       | 74.18%  |
| Btrfs   | 26        | 10.66%  |
| Unknown | 19        | 7.79%   |
| Overlay | 12        | 4.92%   |
| Xfs     | 3         | 1.23%   |
| Ext3    | 2         | 0.82%   |
| Zfs     | 1         | 0.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 125       | 51.44%  |
| GPT     | 80        | 32.92%  |
| MBR     | 38        | 15.64%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 205       | 83.33%  |
| Yes       | 41        | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 175       | 70.85%  |
| Yes       | 72        | 29.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 48        | 19.75%  |
| ASUSTek Computer    | 37        | 15.23%  |
| Hewlett-Packard     | 35        | 14.4%   |
| Dell                | 29        | 11.93%  |
| MSI                 | 22        | 9.05%   |
| Gigabyte Technology | 21        | 8.64%   |
| Samsung Electronics | 7         | 2.88%   |
| Intel               | 6         | 2.47%   |
| ASRock              | 6         | 2.47%   |
| Acer                | 5         | 2.06%   |
| ECS                 | 3         | 1.23%   |
| Timi                | 2         | 0.82%   |
| Quanta              | 2         | 0.82%   |
| Fujitsu             | 2         | 0.82%   |
| Apple               | 2         | 0.82%   |
| ZOTAC               | 1         | 0.41%   |
| Valve               | 1         | 0.41%   |
| TUXEDO              | 1         | 0.41%   |
| Toshiba             | 1         | 0.41%   |
| Supermicro          | 1         | 0.41%   |
| Prestigio           | 1         | 0.41%   |
| OEM                 | 1         | 0.41%   |
| Notebook            | 1         | 0.41%   |
| mPTech              | 1         | 0.41%   |
| Huanan              | 1         | 0.41%   |
| Getac               | 1         | 0.41%   |
| Fujitsu Siemens     | 1         | 0.41%   |
| Framework           | 1         | 0.41%   |
| Chuwi               | 1         | 0.41%   |
| Alienware           | 1         | 0.41%   |
| ABIT                | 1         | 0.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| ASUS All Series                                       | 3         | 1.23%   |
| Quanta TWH                                            | 2         | 0.82%   |
| MSI MS-7758                                           | 2         | 0.82%   |
| Lenovo Y50-70 20378                                   | 2         | 0.82%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2                     | 2         | 0.82%   |
| HP Pavilion Gaming Laptop 15-ec1xxx                   | 2         | 0.82%   |
| HP Pavilion dv7                                       | 2         | 0.82%   |
| HP ENVY Laptop 13-ah0xxx                              | 2         | 0.82%   |
| HP EliteBook 8470p                                    | 2         | 0.82%   |
| HP EliteBook 8460p                                    | 2         | 0.82%   |
| HP EliteBook 840 G2                                   | 2         | 0.82%   |
| Gigabyte X570 AORUS PRO                               | 2         | 0.82%   |
| Gigabyte Q87M-D2H                                     | 2         | 0.82%   |
| Dell Inspiron N5110                                   | 2         | 0.82%   |
| ZOTAC B410                                            | 1         | 0.41%   |
| Valve Jupiter                                         | 1         | 0.41%   |
| TUXEDO Book BA1510                                    | 1         | 0.41%   |
| Toshiba Satellite L855                                | 1         | 0.41%   |
| Timi RedmiBook 16                                     | 1         | 0.41%   |
| Timi RedmiBook 14 II                                  | 1         | 0.41%   |
| Supermicro X10SLH-F/X10SLM+-F                         | 1         | 0.41%   |
| Samsung R410                                          | 1         | 0.41%   |
| Samsung 900X3C/900X3D/900X4C/900X4D                   | 1         | 0.41%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D            | 1         | 0.41%   |
| Samsung 770Z5E/780Z5E                                 | 1         | 0.41%   |
| Samsung 535U3C                                        | 1         | 0.41%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.41%   |
| Samsung 275E4E/275E5E                                 | 1         | 0.41%   |
| Prestigio PNT10131DEDB                                | 1         | 0.41%   |
| OEM Intel H81                                         | 1         | 0.41%   |
| Notebook W35xSS_370SS                                 | 1         | 0.41%   |
| MSI MS-B90111                                         | 1         | 0.41%   |
| MSI MS-7C91                                           | 1         | 0.41%   |
| MSI MS-7C83                                           | 1         | 0.41%   |
| MSI MS-7C37                                           | 1         | 0.41%   |
| MSI MS-7C02                                           | 1         | 0.41%   |
| MSI MS-7B98                                           | 1         | 0.41%   |
| MSI MS-7B79                                           | 1         | 0.41%   |
| MSI MS-7B22                                           | 1         | 0.41%   |
| MSI MS-7B18                                           | 1         | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 29        | 11.93%  |
| HP EliteBook        | 13        | 5.35%   |
| HP Pavilion         | 7         | 2.88%   |
| Dell Inspiron       | 7         | 2.88%   |
| Dell Latitude       | 6         | 2.47%   |
| HP Compaq           | 5         | 2.06%   |
| Dell OptiPlex       | 5         | 2.06%   |
| Lenovo IdeaPad      | 4         | 1.65%   |
| Gigabyte X570       | 4         | 1.65%   |
| Dell XPS            | 4         | 1.65%   |
| Dell Precision      | 4         | 1.65%   |
| ASUS PRIME          | 4         | 1.65%   |
| Acer Aspire         | 4         | 1.65%   |
| Lenovo ThinkCentre  | 3         | 1.23%   |
| Lenovo IdeaPadFlex  | 3         | 1.23%   |
| ASUS VivoBook       | 3         | 1.23%   |
| ASUS All            | 3         | 1.23%   |
| Timi RedmiBook      | 2         | 0.82%   |
| Samsung 900X3C      | 2         | 0.82%   |
| Quanta TWH          | 2         | 0.82%   |
| MSI MS-7758         | 2         | 0.82%   |
| Lenovo Y50-70       | 2         | 0.82%   |
| HP ProDesk          | 2         | 0.82%   |
| HP Presario         | 2         | 0.82%   |
| HP OMEN             | 2         | 0.82%   |
| HP ENVY             | 2         | 0.82%   |
| Gigabyte Q87M-D2H   | 2         | 0.82%   |
| Fujitsu LIFEBOOK    | 2         | 0.82%   |
| ASUS ZenBook        | 2         | 0.82%   |
| ASUS TUF            | 2         | 0.82%   |
| ASUS ROG            | 2         | 0.82%   |
| ZOTAC B410          | 1         | 0.41%   |
| Valve Jupiter       | 1         | 0.41%   |
| TUXEDO Book         | 1         | 0.41%   |
| Toshiba Satellite   | 1         | 0.41%   |
| Supermicro X10SLH-F | 1         | 0.41%   |
| Samsung R410        | 1         | 0.41%   |
| Samsung 770Z5E      | 1         | 0.41%   |
| Samsung 535U3C      | 1         | 0.41%   |
| Samsung 300E5EV     | 1         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 28        | 11.52%  |
| 2019 | 24        | 9.88%   |
| 2020 | 23        | 9.47%   |
| 2013 | 20        | 8.23%   |
| 2014 | 19        | 7.82%   |
| 2011 | 19        | 7.82%   |
| 2017 | 16        | 6.58%   |
| 2015 | 16        | 6.58%   |
| 2012 | 16        | 6.58%   |
| 2016 | 12        | 4.94%   |
| 2010 | 10        | 4.12%   |
| 2009 | 9         | 3.7%    |
| 2008 | 8         | 3.29%   |
| 2007 | 8         | 3.29%   |
| 2021 | 7         | 2.88%   |
| 2006 | 4         | 1.65%   |
| 2005 | 2         | 0.82%   |
| 2022 | 1         | 0.41%   |
| 2004 | 1         | 0.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 139       | 57.2%   |
| Desktop     | 91        | 37.45%  |
| Convertible | 8         | 3.29%   |
| Mini pc     | 3         | 1.23%   |
| All in one  | 1         | 0.41%   |
| Server      | 1         | 0.41%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 228       | 93.06%  |
| Enabled  | 17        | 6.94%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 243       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 51        | 20.73%  |
| 8.01-16.0   | 48        | 19.51%  |
| 4.01-8.0    | 47        | 19.11%  |
| 3.01-4.0    | 41        | 16.67%  |
| 32.01-64.0  | 28        | 11.38%  |
| 24.01-32.0  | 8         | 3.25%   |
| 2.01-3.0    | 8         | 3.25%   |
| 1.01-2.0    | 8         | 3.25%   |
| 64.01-256.0 | 5         | 2.03%   |
| 0.51-1.0    | 2         | 0.81%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 85        | 32.44%  |
| 2.01-3.0   | 60        | 22.9%   |
| 4.01-8.0   | 43        | 16.41%  |
| 3.01-4.0   | 25        | 9.54%   |
| 0.51-1.0   | 25        | 9.54%   |
| 8.01-16.0  | 16        | 6.11%   |
| 24.01-32.0 | 3         | 1.15%   |
| 0.01-0.5   | 3         | 1.15%   |
| 16.01-24.0 | 2         | 0.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 150       | 60.24%  |
| 2      | 57        | 22.89%  |
| 3      | 22        | 8.84%   |
| 6      | 7         | 2.81%   |
| 4      | 7         | 2.81%   |
| 5      | 3         | 1.2%    |
| 0      | 2         | 0.8%    |
| 7      | 1         | 0.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 144       | 58.78%  |
| Yes       | 101       | 41.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 219       | 89.39%  |
| No        | 26        | 10.61%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 180       | 74.07%  |
| No        | 63        | 25.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 142       | 57.72%  |
| No        | 104       | 42.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Estonia | 243       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Tallinn           | 155       | 62.25%  |
| Tartu             | 26        | 10.44%  |
| Pärnu            | 9         | 3.61%   |
| Rapla             | 7         | 2.81%   |
| Rakvere           | 5         | 2.01%   |
| Narva             | 4         | 1.61%   |
| Haapsalu          | 4         | 1.61%   |
| Maardu            | 3         | 1.2%    |
| Vinni             | 2         | 0.8%    |
| Põlva            | 2         | 0.8%    |
| Paldiski          | 2         | 0.8%    |
| Otepaeae          | 2         | 0.8%    |
| Kohtla-Järve     | 2         | 0.8%    |
| Keila             | 2         | 0.8%    |
| Jõhvi            | 2         | 0.8%    |
| Viljandi          | 1         | 0.4%    |
| Vatla             | 1         | 0.4%    |
| Vaidasoo          | 1         | 0.4%    |
| Türi             | 1         | 0.4%    |
| Tapa              | 1         | 0.4%    |
| Tabasalu          | 1         | 0.4%    |
| Sindi             | 1         | 0.4%    |
| Sauga             | 1         | 0.4%    |
| Saku              | 1         | 0.4%    |
| Rae Parish        | 1         | 0.4%    |
| Pohja-Sakala vald | 1         | 0.4%    |
| Paide             | 1         | 0.4%    |
| Laagri            | 1         | 0.4%    |
| Kuressaare        | 1         | 0.4%    |
| Kose              | 1         | 0.4%    |
| Kiviõli          | 1         | 0.4%    |
| Kärdla           | 1         | 0.4%    |
| Kaeina            | 1         | 0.4%    |
| Jõgeva           | 1         | 0.4%    |
| Jaerva vald       | 1         | 0.4%    |
| Hiiumaa           | 1         | 0.4%    |
| Haabneeme         | 1         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 76        | 103    | 21.35%  |
| Seagate                   | 46        | 60     | 12.92%  |
| WDC                       | 43        | 67     | 12.08%  |
| Kingston                  | 28        | 40     | 7.87%   |
| Toshiba                   | 22        | 23     | 6.18%   |
| Hitachi                   | 15        | 18     | 4.21%   |
| SK hynix                  | 14        | 18     | 3.93%   |
| SanDisk                   | 12        | 14     | 3.37%   |
| Crucial                   | 12        | 21     | 3.37%   |
| HGST                      | 11        | 15     | 3.09%   |
| Unknown                   | 10        | 10     | 2.81%   |
| Intel                     | 9         | 11     | 2.53%   |
| A-DATA Technology         | 9         | 13     | 2.53%   |
| Gigabyte Technology       | 4         | 5      | 1.12%   |
| China                     | 4         | 4      | 1.12%   |
| Transcend                 | 3         | 5      | 0.84%   |
| Micron Technology         | 3         | 3      | 0.84%   |
| KingSpec                  | 3         | 4      | 0.84%   |
| Apacer                    | 3         | 3      | 0.84%   |
| Patriot                   | 2         | 2      | 0.56%   |
| Maxtor                    | 2         | 2      | 0.56%   |
| Lenovo                    | 2         | 2      | 0.56%   |
| Fujitsu                   | 2         | 2      | 0.56%   |
| Corsair                   | 2         | 2      | 0.56%   |
| Apple                     | 2         | 2      | 0.56%   |
| XPG                       | 1         | 1      | 0.28%   |
| Team                      | 1         | 2      | 0.28%   |
| Silicon Motion            | 1         | 2      | 0.28%   |
| Plextor                   | 1         | 1      | 0.28%   |
| Phison                    | 1         | 1      | 0.28%   |
| Micron/Crucial Technology | 1         | 1      | 0.28%   |
| LITEONIT                  | 1         | 1      | 0.28%   |
| Lexar                     | 1         | 1      | 0.28%   |
| KIOXIA                    | 1         | 2      | 0.28%   |
| Intenso                   | 1         | 1      | 0.28%   |
| Integral                  | 1         | 1      | 0.28%   |
| Inateck                   | 1         | 1      | 0.28%   |
| i-FlashDisk               | 1         | 1      | 0.28%   |
| HUAWEI                    | 1         | 1      | 0.28%   |
| ASMT109x                  | 1         | 2      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB            | 6         | 1.52%   |
| Samsung NVMe SSD Drive 1TB           | 6         | 1.52%   |
| Seagate ST2000DM008-2FR102 2TB       | 4         | 1.01%   |
| Samsung NVMe SSD Drive 512GB         | 4         | 1.01%   |
| Samsung HD103SJ 1TB                  | 4         | 1.01%   |
| Kingston SA400S37240G 240GB SSD      | 4         | 1.01%   |
| SK hynix NVMe SSD Drive 256GB        | 3         | 0.76%   |
| Seagate ST500LT012-9WS142 500GB      | 3         | 0.76%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 0.76%   |
| Samsung SSD 960 PRO 512GB            | 3         | 0.76%   |
| Samsung SSD 850 EVO 500GB            | 3         | 0.76%   |
| Samsung MZ7TY128HDHP-000L1 128GB SSD | 3         | 0.76%   |
| Kingston SV300S37A120G 120GB SSD     | 3         | 0.76%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 0.76%   |
| HGST HTS721010A9E630 1TB             | 3         | 0.76%   |
| HGST HTS541010A9E680 1TB             | 3         | 0.76%   |
| WDC WD10EADS-00M2B0 1TB              | 2         | 0.51%   |
| Unknown MMC Card  16GB               | 2         | 0.51%   |
| Unknown ArtisanTribute-512GB         | 2         | 0.51%   |
| Toshiba NVMe SSD Drive 512GB         | 2         | 0.51%   |
| Toshiba MQ01ABF050 500GB             | 2         | 0.51%   |
| Toshiba HDWD130 3TB                  | 2         | 0.51%   |
| SK hynix NVMe SSD Drive 512GB        | 2         | 0.51%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 0.51%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 0.51%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 0.51%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.51%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 0.51%   |
| Seagate ST1000DM003-1SB102 1TB       | 2         | 0.51%   |
| Seagate ST1000DM003-1ER162 1TB       | 2         | 0.51%   |
| SanDisk SD8SBAT256G1122 256GB SSD    | 2         | 0.51%   |
| SanDisk SD7SB3Q128G1001 128GB SSD    | 2         | 0.51%   |
| Samsung SSD 970 EVO Plus 500GB       | 2         | 0.51%   |
| Samsung SSD 860 EVO 500GB            | 2         | 0.51%   |
| Samsung SSD 860 EVO 250GB            | 2         | 0.51%   |
| Samsung SSD 860 EVO 1TB              | 2         | 0.51%   |
| Samsung SSD 850 PRO 256GB            | 2         | 0.51%   |
| Samsung SSD 850 EVO M.2 500GB        | 2         | 0.51%   |
| Samsung SSD 840 PRO Series 128GB     | 2         | 0.51%   |
| Samsung SP0802N 80GB                 | 2         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 45        | 59     | 33.09%  |
| WDC                 | 34        | 51     | 25%     |
| Hitachi             | 15        | 18     | 11.03%  |
| Toshiba             | 13        | 13     | 9.56%   |
| Samsung Electronics | 12        | 14     | 8.82%   |
| HGST                | 11        | 15     | 8.09%   |
| Maxtor              | 2         | 2      | 1.47%   |
| Fujitsu             | 2         | 2      | 1.47%   |
| Unknown             | 1         | 1      | 0.74%   |
| Apple               | 1         | 1      | 0.74%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 42        | 51     | 29.58%  |
| Kingston            | 22        | 31     | 15.49%  |
| Crucial             | 12        | 21     | 8.45%   |
| SanDisk             | 11        | 13     | 7.75%   |
| WDC                 | 7         | 10     | 4.93%   |
| A-DATA Technology   | 7         | 11     | 4.93%   |
| SK hynix            | 4         | 4      | 2.82%   |
| China               | 4         | 4      | 2.82%   |
| Transcend           | 3         | 5      | 2.11%   |
| Toshiba             | 3         | 4      | 2.11%   |
| Micron Technology   | 3         | 3      | 2.11%   |
| KingSpec            | 3         | 4      | 2.11%   |
| Intel               | 3         | 4      | 2.11%   |
| Apacer              | 3         | 3      | 2.11%   |
| Patriot             | 2         | 2      | 1.41%   |
| Gigabyte Technology | 2         | 3      | 1.41%   |
| Corsair             | 2         | 2      | 1.41%   |
| Team                | 1         | 2      | 0.7%    |
| Plextor             | 1         | 1      | 0.7%    |
| LITEONIT            | 1         | 1      | 0.7%    |
| Lexar               | 1         | 1      | 0.7%    |
| Intenso             | 1         | 1      | 0.7%    |
| Integral            | 1         | 1      | 0.7%    |
| i-FlashDisk         | 1         | 1      | 0.7%    |
| ASMT                | 1         | 1      | 0.7%    |
| Apple               | 1         | 1      | 0.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 115       | 185    | 36.62%  |
| HDD     | 113       | 176    | 35.99%  |
| NVMe    | 72        | 94     | 22.93%  |
| MMC     | 8         | 8      | 2.55%   |
| Unknown | 6         | 7      | 1.91%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 190       | 355    | 67.14%  |
| NVMe | 72        | 94     | 25.44%  |
| SAS  | 13        | 13     | 4.59%   |
| MMC  | 8         | 8      | 2.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 157       | 237    | 63.31%  |
| 0.51-1.0   | 61        | 82     | 24.6%   |
| 1.01-2.0   | 15        | 20     | 6.05%   |
| 2.01-3.0   | 5         | 12     | 2.02%   |
| 4.01-10.0  | 5         | 5      | 2.02%   |
| 3.01-4.0   | 4         | 4      | 1.61%   |
| 10.01-20.0 | 1         | 1      | 0.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 76        | 30.04%  |
| 251-500        | 52        | 20.55%  |
| 501-1000       | 28        | 11.07%  |
| 1-20           | 26        | 10.28%  |
| 1001-2000      | 22        | 8.7%    |
| 51-100         | 17        | 6.72%   |
| More than 3000 | 13        | 5.14%   |
| Unknown        | 8         | 3.16%   |
| 21-50          | 7         | 2.77%   |
| 2001-3000      | 4         | 1.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 109       | 42.25%  |
| 21-50          | 38        | 14.73%  |
| 101-250        | 34        | 13.18%  |
| 51-100         | 25        | 9.69%   |
| 251-500        | 15        | 5.81%   |
| 501-1000       | 14        | 5.43%   |
| More than 3000 | 9         | 3.49%   |
| Unknown        | 8         | 3.1%    |
| 1001-2000      | 5         | 1.94%   |
| 2001-3000      | 1         | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


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
| Hitachi HDS721680PLA380 82GB                        | 1         | 1      | 2.86%   |
| Hitachi HDS721010DLE630 1TB                         | 1         | 1      | 2.86%   |
| Fujitsu MHT2040AH PL 40GB                           | 1         | 1      | 2.86%   |
| Crucial CT480M500SSD3 480GB                         | 1         | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 31     | 78.13%  |
| SSD  | 7         | 9      | 21.88%  |

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
| Detected | 131       | 251    | 49.25%  |
| Works    | 102       | 178    | 38.35%  |
| Malfunc  | 32        | 40     | 12.03%  |
| Failed   | 1         | 1      | 0.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 171       | 54.63%  |
| AMD                          | 48        | 15.34%  |
| Samsung Electronics          | 32        | 10.22%  |
| SK hynix                     | 10        | 3.19%   |
| SanDisk                      | 7         | 2.24%   |
| Kingston Technology Company  | 7         | 2.24%   |
| Marvell Technology Group     | 6         | 1.92%   |
| Nvidia                       | 5         | 1.6%    |
| Toshiba America Info Systems | 4         | 1.28%   |
| VIA Technologies             | 3         | 0.96%   |
| Phison Electronics           | 3         | 0.96%   |
| KIOXIA                       | 3         | 0.96%   |
| ASMedia Technology           | 3         | 0.96%   |
| Silicon Motion               | 2         | 0.64%   |
| Lenovo                       | 2         | 0.64%   |
| JMicron Technology           | 2         | 0.64%   |
| ADATA Technology             | 2         | 0.64%   |
| Silicon Image                | 1         | 0.32%   |
| Micron/Crucial Technology    | 1         | 0.32%   |
| Adaptec                      | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 35        | 9.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 21        | 5.87%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 21        | 5.87%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 14        | 3.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 3.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 2.51%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 8         | 2.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 1.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 1.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 1.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 1.96%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 6         | 1.68%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 6         | 1.68%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 6         | 1.68%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 1.4%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 1.4%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 1.4%    |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 1.4%    |
| AMD 400 Series Chipset SATA Controller                                         | 5         | 1.4%    |
| Samsung NVMe SSD Controller 980                                                | 4         | 1.12%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.12%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 1.12%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 3         | 0.84%   |
| SK hynix Non-Volatile memory controller                                        | 3         | 0.84%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 0.84%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 0.84%   |
| Kingston Company A2000 NVMe SSD                                                | 3         | 0.84%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 0.84%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 0.84%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 0.84%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 3         | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 0.84%   |
| VIA VT6415 PATA IDE Host Controller                                            | 2         | 0.56%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.56%   |
| SK hynix Gold P31 SSD                                                          | 2         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 195       | 62.1%   |
| NVMe | 74        | 23.57%  |
| IDE  | 35        | 11.15%  |
| RAID | 9         | 2.87%   |
| SCSI | 1         | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 186       | 76.54%  |
| AMD    | 57        | 23.46%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 2.47%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.65%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.65%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.23%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.23%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 3         | 1.23%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 3         | 1.23%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 3         | 1.23%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.23%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 3         | 1.23%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 1.23%   |
| AMD Ryzen 5 3600 6-Core Processor             | 3         | 1.23%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz           | 2         | 0.82%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 0.82%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.82%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 0.82%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 0.82%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 0.82%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 0.82%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.82%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.82%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 2         | 0.82%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 0.82%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.82%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 2         | 0.82%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.82%   |
| Intel Core i5-2500 CPU @ 3.30GHz              | 2         | 0.82%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.82%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 0.82%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 0.82%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 0.82%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 2         | 0.82%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics    | 2         | 0.82%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 0.82%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 0.82%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 0.82%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+    | 2         | 0.82%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz            | 1         | 0.41%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz           | 1         | 0.41%   |
| Intel Pentium M processor 2.13GHz             | 1         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 61        | 25.1%   |
| Intel Core i7                  | 53        | 21.81%  |
| Intel Core i3                  | 18        | 7.41%   |
| AMD Ryzen 5                    | 15        | 6.17%   |
| Intel Core 2 Duo               | 12        | 4.94%   |
| Intel Celeron                  | 11        | 4.53%   |
| AMD Ryzen 7                    | 11        | 4.53%   |
| Intel Pentium                  | 7         | 2.88%   |
| Other                          | 5         | 2.06%   |
| Intel Xeon                     | 4         | 1.65%   |
| AMD Ryzen 9                    | 4         | 1.65%   |
| AMD Ryzen 7 PRO                | 4         | 1.65%   |
| AMD Athlon 64 X2               | 4         | 1.65%   |
| Intel Core i9                  | 3         | 1.23%   |
| Intel Atom                     | 3         | 1.23%   |
| Intel Pentium M                | 2         | 0.82%   |
| Intel Celeron Dual-Core        | 2         | 0.82%   |
| AMD Phenom II X4               | 2         | 0.82%   |
| AMD FX                         | 2         | 0.82%   |
| AMD A10                        | 2         | 0.82%   |
| Intel Pentium Gold             | 1         | 0.41%   |
| Intel Pentium Dual-Core        | 1         | 0.41%   |
| Intel Pentium Dual             | 1         | 0.41%   |
| Intel Pentium D                | 1         | 0.41%   |
| Intel Pentium 4                | 1         | 0.41%   |
| Intel Core 2                   | 1         | 0.41%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.41%   |
| AMD Ryzen 3 PRO                | 1         | 0.41%   |
| AMD Ryzen 3                    | 1         | 0.41%   |
| AMD Phenom II X6               | 1         | 0.41%   |
| AMD E2                         | 1         | 0.41%   |
| AMD E                          | 1         | 0.41%   |
| AMD C-60                       | 1         | 0.41%   |
| AMD Athlon XP                  | 1         | 0.41%   |
| AMD Athlon II Dual-Core        | 1         | 0.41%   |
| AMD A8                         | 1         | 0.41%   |
| AMD A6                         | 1         | 0.41%   |
| AMD A4                         | 1         | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 106       | 43.62%  |
| 4       | 78        | 32.1%   |
| 6       | 24        | 9.88%   |
| 8       | 18        | 7.41%   |
| 1       | 8         | 3.29%   |
| 12      | 3         | 1.23%   |
| Unknown | 3         | 1.23%   |
| 16      | 1         | 0.41%   |
| 14      | 1         | 0.41%   |
| 3       | 1         | 0.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 243       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 162       | 66.39%  |
| 1       | 79        | 32.38%  |
| Unknown | 3         | 1.23%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 238       | 97.54%  |
| 32-bit         | 3         | 1.23%   |
| Unknown        | 3         | 1.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 49        | 19.52%  |
| 0x306c3    | 20        | 7.97%   |
| 0x306a9    | 18        | 7.17%   |
| 0x206a7    | 16        | 6.37%   |
| 0x906e9    | 9         | 3.59%   |
| 0x806ea    | 8         | 3.19%   |
| 0x1067a    | 7         | 2.79%   |
| 0x906ea    | 6         | 2.39%   |
| 0x40651    | 6         | 2.39%   |
| 0x306d4    | 6         | 2.39%   |
| 0x08600106 | 6         | 2.39%   |
| 0x806ec    | 5         | 1.99%   |
| 0x806e9    | 5         | 1.99%   |
| 0x6fb      | 5         | 1.99%   |
| 0x506e3    | 5         | 1.99%   |
| 0x08701021 | 5         | 1.99%   |
| 0x08701013 | 5         | 1.99%   |
| 0x6fd      | 4         | 1.59%   |
| 0x20655    | 4         | 1.59%   |
| 0xa0652    | 3         | 1.2%    |
| 0x806c1    | 3         | 1.2%    |
| 0x406e3    | 3         | 1.2%    |
| 0x08108102 | 3         | 1.2%    |
| 0x05000119 | 3         | 1.2%    |
| 0x906ed    | 2         | 0.8%    |
| 0x706a1    | 2         | 0.8%    |
| 0x6d8      | 2         | 0.8%    |
| 0x30678    | 2         | 0.8%    |
| 0x08600103 | 2         | 0.8%    |
| 0x0810100b | 2         | 0.8%    |
| 0x08001138 | 2         | 0.8%    |
| 0x06003106 | 2         | 0.8%    |
| 0x06000852 | 2         | 0.8%    |
| 0xf64      | 1         | 0.4%    |
| 0xf4a      | 1         | 0.4%    |
| 0xa0671    | 1         | 0.4%    |
| 0xa0655    | 1         | 0.4%    |
| 0xa0653    | 1         | 0.4%    |
| 0x906eb    | 1         | 0.4%    |
| 0x806eb    | 1         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 46        | 18.93%  |
| Haswell         | 32        | 13.17%  |
| Zen 2           | 23        | 9.47%   |
| SandyBridge     | 20        | 8.23%   |
| IvyBridge       | 20        | 8.23%   |
| Skylake         | 11        | 4.53%   |
| Core            | 11        | 4.53%   |
| Penryn          | 8         | 3.29%   |
| Westmere        | 7         | 2.88%   |
| Broadwell       | 7         | 2.88%   |
| Zen             | 5         | 2.06%   |
| CometLake       | 5         | 2.06%   |
| Zen+            | 4         | 1.65%   |
| Zen 3           | 4         | 1.65%   |
| Silvermont      | 4         | 1.65%   |
| K8 Hammer       | 4         | 1.65%   |
| K10             | 4         | 1.65%   |
| TigerLake       | 3         | 1.23%   |
| Steamroller     | 3         | 1.23%   |
| Piledriver      | 3         | 1.23%   |
| Goldmont plus   | 3         | 1.23%   |
| Bobcat          | 3         | 1.23%   |
| P6              | 2         | 0.82%   |
| NetBurst        | 2         | 0.82%   |
| Icelake         | 2         | 0.82%   |
| Bonnell         | 2         | 0.82%   |
| K8 & K10 hybrid | 1         | 0.41%   |
| K6              | 1         | 0.41%   |
| Goldmont        | 1         | 0.41%   |
| Excavator       | 1         | 0.41%   |
| Unknown         | 1         | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 146       | 47.56%  |
| Nvidia            | 102       | 33.22%  |
| AMD               | 57        | 18.57%  |
| VIA Technologies  | 1         | 0.33%   |
| ASPEED Technology | 1         | 0.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 14        | 4.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 14        | 4.44%   |
| AMD Renoir                                                                    | 11        | 3.49%   |
| Intel UHD Graphics 620                                                        | 10        | 3.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 8         | 2.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 8         | 2.54%   |
| Intel HD Graphics 630                                                         | 7         | 2.22%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 7         | 2.22%   |
| Intel Core Processor Integrated Graphics Controller                           | 6         | 1.9%    |
| Nvidia GP108M [GeForce MX150]                                                 | 5         | 1.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 5         | 1.59%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 5         | 1.59%   |
| Intel HD Graphics 620                                                         | 5         | 1.59%   |
| Intel HD Graphics 5500                                                        | 5         | 1.59%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 5         | 1.59%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 4         | 1.27%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 4         | 1.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 4         | 1.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 4         | 1.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 4         | 1.27%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 4         | 1.27%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 3         | 0.95%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                            | 3         | 0.95%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 3         | 0.95%   |
| Intel HD Graphics 530                                                         | 3         | 0.95%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 0.95%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 0.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 3         | 0.95%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 3         | 0.95%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 0.95%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 0.95%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 0.95%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 0.63%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 2         | 0.63%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                         | 2         | 0.63%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 2         | 0.63%   |
| Nvidia TU106 [GeForce RTX 2070]                                               | 2         | 0.63%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                         | 2         | 0.63%   |
| Nvidia GP108GLM [Quadro P520]                                                 | 2         | 0.63%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 2         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 88        | 36.07%  |
| 1 x Nvidia     | 50        | 20.49%  |
| Intel + Nvidia | 48        | 19.67%  |
| 1 x AMD        | 44        | 18.03%  |
| Intel + AMD    | 7         | 2.87%   |
| AMD + Nvidia   | 3         | 1.23%   |
| 2 x AMD        | 2         | 0.82%   |
| 1 x VIA        | 1         | 0.41%   |
| AMD + ASPEED   | 1         | 0.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 176       | 70.97%  |
| Proprietary | 65        | 26.21%  |
| Unknown     | 7         | 2.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 104       | 41.94%  |
| 1.01-2.0   | 48        | 19.35%  |
| 0.01-0.5   | 30        | 12.1%   |
| 3.01-4.0   | 23        | 9.27%   |
| 7.01-8.0   | 15        | 6.05%   |
| 0.51-1.0   | 13        | 5.24%   |
| 5.01-6.0   | 7         | 2.82%   |
| 8.01-16.0  | 5         | 2.02%   |
| 2.01-3.0   | 2         | 0.81%   |
| 4.01-5.0   | 1         | 0.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 35        | 12.54%  |
| Dell                    | 33        | 11.83%  |
| Chimei Innolux          | 30        | 10.75%  |
| AU Optronics            | 29        | 10.39%  |
| LG Display              | 19        | 6.81%   |
| Goldstar                | 19        | 6.81%   |
| BOE                     | 17        | 6.09%   |
| Chi Mei Optoelectronics | 10        | 3.58%   |
| Hewlett-Packard         | 9         | 3.23%   |
| ViewSonic               | 7         | 2.51%   |
| Sharp                   | 7         | 2.51%   |
| Philips                 | 7         | 2.51%   |
| Lenovo                  | 7         | 2.51%   |
| AOC                     | 7         | 2.51%   |
| BenQ                    | 5         | 1.79%   |
| Sony                    | 3         | 1.08%   |
| PANDA                   | 3         | 1.08%   |
| LG Philips              | 3         | 1.08%   |
| Hitachi                 | 3         | 1.08%   |
| Unknown                 | 2         | 0.72%   |
| RoverScan               | 2         | 0.72%   |
| Fujitsu Siemens         | 2         | 0.72%   |
| Apple                   | 2         | 0.72%   |
| Ancor Communications    | 2         | 0.72%   |
| Acer                    | 2         | 0.72%   |
| Toshiba                 | 1         | 0.36%   |
| Tech Concepts           | 1         | 0.36%   |
| Seiko/Epson             | 1         | 0.36%   |
| LG Electronics          | 1         | 0.36%   |
| Lenovo Group Limited    | 1         | 0.36%   |
| KDB                     | 1         | 0.36%   |
| InfoVision              | 1         | 0.36%   |
| Eizo                    | 1         | 0.36%   |
| CSO                     | 1         | 0.36%   |
| CPT                     | 1         | 0.36%   |
| Belinea                 | 1         | 0.36%   |
| ASUSTek Computer        | 1         | 0.36%   |
| ANX                     | 1         | 0.36%   |
| Unknown                 | 1         | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Goldstar 27GL850 GSM5B80 2560x1440 697x392mm 31.5-inch                    | 3         | 1.01%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 3         | 1.01%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 3         | 1.01%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 3         | 1.01%   |
| ViewSonic VA703-4Series VSC6A1E 1280x1024 341x274mm 17.2-inch             | 2         | 0.68%   |
| Sony TV SNYDB01 1920x1080 1600x900mm 72.3-inch                            | 2         | 0.68%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 2         | 0.68%   |
| Samsung Electronics S32D850 SAM0BCB 2560x1440 708x398mm 32.0-inch         | 2         | 0.68%   |
| Samsung Electronics S24C650 SAM0B18 1920x1200 518x324mm 24.1-inch         | 2         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch      | 2         | 0.68%   |
| LG Display LCD Monitor LGD0685 1920x1080 309x174mm 14.0-inch              | 2         | 0.68%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                   | 2         | 0.68%   |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch                   | 2         | 0.68%   |
| Hewlett-Packard ZR24w HWP2869 1920x1200 518x324mm 24.1-inch               | 2         | 0.68%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                      | 2         | 0.68%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 2         | 0.68%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                         | 2         | 0.68%   |
| Dell U2312HM DEL4073 1920x1080 510x287mm 23.0-inch                        | 2         | 0.68%   |
| Dell P2314H DEL4098 1920x1080 510x290mm 23.1-inch                         | 2         | 0.68%   |
| Dell 2407WFP DELA017 1920x1200 520x330mm 24.2-inch                        | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch           | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch          | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch          | 2         | 0.68%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.68%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 2         | 0.68%   |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch  | 2         | 0.68%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 2         | 0.68%   |
| BOE LCD Monitor BOE077A 1920x1080 294x165mm 13.3-inch                     | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch             | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 2         | 0.68%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                       | 2         | 0.68%   |
| ViewSonic VP2030 SERIES VSC131C 1600x1200 408x306mm 20.1-inch             | 1         | 0.34%   |
| ViewSonic VG2428wm VSCA426 1920x1080 520x290mm 23.4-inch                  | 1         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 109       | 41.13%  |
| 1366x768 (WXGA)    | 40        | 15.09%  |
| 3840x2160 (4K)     | 20        | 7.55%   |
| 1920x1200 (WUXGA)  | 19        | 7.17%   |
| 1280x1024 (SXGA)   | 19        | 7.17%   |
| 2560x1440 (QHD)    | 15        | 5.66%   |
| 1600x900 (HD+)     | 12        | 4.53%   |
| 1280x800 (WXGA)    | 9         | 3.4%    |
| 3440x1440          | 6         | 2.26%   |
| 1680x1050 (WSXGA+) | 5         | 1.89%   |
| 2560x1600          | 3         | 1.13%   |
| 1440x900 (WXGA+)   | 3         | 1.13%   |
| 800x1280           | 1         | 0.38%   |
| 2560x1080          | 1         | 0.38%   |
| 2256x1504          | 1         | 0.38%   |
| 1920x540           | 1         | 0.38%   |
| 1600x1200          | 1         | 0.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 69        | 24.38%  |
| 13      | 26        | 9.19%   |
| 24      | 24        | 8.48%   |
| 17      | 22        | 7.77%   |
| 14      | 22        | 7.77%   |
| 27      | 21        | 7.42%   |
| 23      | 16        | 5.65%   |
| 21      | 14        | 4.95%   |
| Unknown | 12        | 4.24%   |
| 12      | 8         | 2.83%   |
| 19      | 6         | 2.12%   |
| 34      | 5         | 1.77%   |
| 84      | 4         | 1.41%   |
| 31      | 4         | 1.41%   |
| 72      | 3         | 1.06%   |
| 25      | 3         | 1.06%   |
| 22      | 3         | 1.06%   |
| 18      | 3         | 1.06%   |
| 54      | 2         | 0.71%   |
| 40      | 2         | 0.71%   |
| 33      | 2         | 0.71%   |
| 32      | 2         | 0.71%   |
| 20      | 2         | 0.71%   |
| 16      | 2         | 0.71%   |
| 65      | 1         | 0.35%   |
| 43      | 1         | 0.35%   |
| 29      | 1         | 0.35%   |
| 26      | 1         | 0.35%   |
| 11      | 1         | 0.35%   |
| 10      | 1         | 0.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 111       | 40.22%  |
| 501-600     | 54        | 19.57%  |
| 201-300     | 26        | 9.42%   |
| 401-500     | 23        | 8.33%   |
| 351-400     | 17        | 6.16%   |
| Unknown     | 12        | 4.35%   |
| 601-700     | 11        | 3.99%   |
| 701-800     | 9         | 3.26%   |
| 1501-2000   | 7         | 2.54%   |
| 1001-1500   | 3         | 1.09%   |
| 801-900     | 2         | 0.72%   |
| 901-1000    | 1         | 0.36%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 175       | 68.9%   |
| 16/10   | 40        | 15.75%  |
| 5/4     | 15        | 5.91%   |
| Unknown | 10        | 3.94%   |
| 21/9    | 5         | 1.97%   |
| 4/3     | 3         | 1.18%   |
| 6/5     | 2         | 0.79%   |
| 3/2     | 2         | 0.79%   |
| 32/9    | 1         | 0.39%   |
| 0.62    | 1         | 0.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 69        | 24.56%  |
| 201-250        | 36        | 12.81%  |
| 81-90          | 34        | 12.1%   |
| 301-350        | 22        | 7.83%   |
| 251-300        | 19        | 6.76%   |
| 71-80          | 14        | 4.98%   |
| 351-500        | 14        | 4.98%   |
| 141-150        | 14        | 4.98%   |
| 151-200        | 12        | 4.27%   |
| Unknown        | 12        | 4.27%   |
| More than 1000 | 10        | 3.56%   |
| 121-130        | 9         | 3.2%    |
| 61-70          | 8         | 2.85%   |
| 501-1000       | 3         | 1.07%   |
| 111-120        | 2         | 0.71%   |
| 51-60          | 1         | 0.36%   |
| 41-50          | 1         | 0.36%   |
| 131-140        | 1         | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 92        | 33.7%   |
| 121-160       | 75        | 27.47%  |
| 101-120       | 65        | 23.81%  |
| 161-240       | 19        | 6.96%   |
| Unknown       | 12        | 4.4%    |
| 1-50          | 6         | 2.2%    |
| More than 240 | 4         | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 192       | 77.11%  |
| 2     | 42        | 16.87%  |
| 3     | 8         | 3.21%   |
| 0     | 6         | 2.41%   |
| 4     | 1         | 0.4%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 129       | 35.83%  |
| Realtek Semiconductor             | 119       | 33.06%  |
| Qualcomm Atheros                  | 39        | 10.83%  |
| Broadcom                          | 12        | 3.33%   |
| TP-Link                           | 8         | 2.22%   |
| Ralink                            | 7         | 1.94%   |
| Nvidia                            | 5         | 1.39%   |
| MediaTek                          | 4         | 1.11%   |
| Ralink Technology                 | 3         | 0.83%   |
| Marvell Technology Group          | 3         | 0.83%   |
| Hewlett-Packard                   | 3         | 0.83%   |
| FIBOCOM                           | 3         | 0.83%   |
| Broadcom Limited                  | 3         | 0.83%   |
| Sierra Wireless                   | 2         | 0.56%   |
| Microsoft                         | 2         | 0.56%   |
| Lenovo                            | 2         | 0.56%   |
| Huawei Technologies               | 2         | 0.56%   |
| Ericsson Business Mobile Networks | 2         | 0.56%   |
| D-Link System                     | 2         | 0.56%   |
| VIA Technologies                  | 1         | 0.28%   |
| Van Ooijen Technische Informatica | 1         | 0.28%   |
| Samsung Electronics               | 1         | 0.28%   |
| Qualcomm Atheros Communications   | 1         | 0.28%   |
| JMicron Technology                | 1         | 0.28%   |
| DisplayLink                       | 1         | 0.28%   |
| D-Link                            | 1         | 0.28%   |
| ASUSTek Computer                  | 1         | 0.28%   |
| ASIX Electronics                  | 1         | 0.28%   |
| Aquantia                          | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 76        | 17.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 4.58%   |
| Intel Wireless 8265 / 8275                                        | 12        | 2.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 2.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 2.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 1.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 1.83%   |
| Intel Wi-Fi 6 AX200                                               | 8         | 1.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.6%    |
| Intel Wireless 7265                                               | 7         | 1.6%    |
| Intel I211 Gigabit Network Connection                             | 7         | 1.6%    |
| Intel Wireless 7260                                               | 6         | 1.37%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.14%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 5         | 1.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.14%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 1.14%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.92%   |
| Intel Wireless 8260                                               | 4         | 0.92%   |
| Intel Wireless 3165                                               | 4         | 0.92%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 0.92%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.92%   |
| Intel 82566MM Gigabit Network Connection                          | 4         | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.69%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.69%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.69%   |
| Intel Wireless 3160                                               | 3         | 0.69%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 3         | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.69%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.69%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.69%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 97        | 50.52%  |
| Qualcomm Atheros                | 29        | 15.1%   |
| Realtek Semiconductor           | 25        | 13.02%  |
| Broadcom                        | 8         | 4.17%   |
| TP-Link                         | 7         | 3.65%   |
| Ralink                          | 7         | 3.65%   |
| Ralink Technology               | 3         | 1.56%   |
| MediaTek                        | 3         | 1.56%   |
| FIBOCOM                         | 3         | 1.56%   |
| Sierra Wireless                 | 2         | 1.04%   |
| Microsoft                       | 2         | 1.04%   |
| Broadcom Limited                | 2         | 1.04%   |
| Qualcomm Atheros Communications | 1         | 0.52%   |
| Hewlett-Packard                 | 1         | 0.52%   |
| D-Link System                   | 1         | 0.52%   |
| D-Link                          | 1         | 0.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 12        | 6.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 5.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 4.12%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 4.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 3.61%   |
| Intel Wireless 7265                                                     | 7         | 3.61%   |
| Intel Wireless 7260                                                     | 6         | 3.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 2.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 2.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 2.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 2.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 2.06%   |
| Intel Wireless 8260                                                     | 4         | 2.06%   |
| Intel Wireless 3165                                                     | 4         | 2.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.55%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.55%   |
| Intel Wireless 3160                                                     | 3         | 1.55%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.55%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.55%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.55%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.55%   |
| FIBOCOM L830-EB                                                         | 3         | 1.55%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 2         | 1.03%   |
| TP-Link Archer T4U ver.3                                                | 2         | 1.03%   |
| TP-Link 802.11n NIC                                                     | 2         | 1.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.03%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.03%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.03%   |
| Ralink RT2500 Wireless 802.11bg                                         | 2         | 1.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.03%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                      | 2         | 1.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.03%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.03%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 1.03%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 106       | 46.29%  |
| Intel                    | 79        | 34.5%   |
| Qualcomm Atheros         | 16        | 6.99%   |
| Broadcom                 | 6         | 2.62%   |
| Nvidia                   | 5         | 2.18%   |
| Marvell Technology Group | 3         | 1.31%   |
| Lenovo                   | 2         | 0.87%   |
| VIA Technologies         | 1         | 0.44%   |
| TP-Link                  | 1         | 0.44%   |
| Samsung Electronics      | 1         | 0.44%   |
| MediaTek                 | 1         | 0.44%   |
| JMicron Technology       | 1         | 0.44%   |
| Hewlett-Packard          | 1         | 0.44%   |
| DisplayLink              | 1         | 0.44%   |
| D-Link System            | 1         | 0.44%   |
| Broadcom Limited         | 1         | 0.44%   |
| ASUSTek Computer         | 1         | 0.44%   |
| ASIX Electronics         | 1         | 0.44%   |
| Aquantia                 | 1         | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 76        | 32.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 8.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 5.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 3.4%    |
| Intel I211 Gigabit Network Connection                             | 7         | 2.98%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 2.55%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 2.13%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 2.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.7%    |
| Intel Ethernet Connection (6) I219-V                              | 4         | 1.7%    |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.7%    |
| Intel 82566MM Gigabit Network Connection                          | 4         | 1.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 1.28%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.28%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.28%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.28%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.85%   |
| Nvidia CK804 Ethernet Controller                                  | 2         | 0.85%   |
| Lenovo ThinkPad TBT3 LAN                                          | 2         | 0.85%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.85%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.85%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.85%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.85%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.43%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.43%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.43%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.43%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.43%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.43%   |
| Nvidia nForce2 Ethernet Controller                                | 1         | 0.43%   |
| Nvidia MCP77 Ethernet                                             | 1         | 0.43%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.43%   |
| MediaTek Nokia 5.1 Plus                                           | 1         | 0.43%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.43%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 218       | 53.69%  |
| WiFi     | 180       | 44.33%  |
| Modem    | 8         | 1.97%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 138       | 55.65%  |
| Ethernet | 110       | 44.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 134       | 55.14%  |
| 1     | 99        | 40.74%  |
| 0     | 5         | 2.06%   |
| 3     | 4         | 1.65%   |
| 6     | 1         | 0.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 220       | 89.43%  |
| Yes  | 26        | 10.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 68        | 47.89%  |
| Cambridge Silicon Radio         | 15        | 10.56%  |
| Qualcomm Atheros Communications | 12        | 8.45%   |
| Realtek Semiconductor           | 11        | 7.75%   |
| Broadcom                        | 11        | 7.75%   |
| IMC Networks                    | 8         | 5.63%   |
| Hewlett-Packard                 | 4         | 2.82%   |
| Realtek                         | 2         | 1.41%   |
| ASUSTek Computer                | 2         | 1.41%   |
| Apple                           | 2         | 1.41%   |
| Toshiba                         | 1         | 0.7%    |
| Ralink                          | 1         | 0.7%    |
| Lite-On Technology              | 1         | 0.7%    |
| Integrated System Solution      | 1         | 0.7%    |
| Foxconn / Hon Hai               | 1         | 0.7%    |
| Dell                            | 1         | 0.7%    |
| Askey Computer                  | 1         | 0.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 36        | 25.35%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 15        | 10.56%  |
| Realtek Bluetooth Radio                               | 8         | 5.63%   |
| Intel AX201 Bluetooth                                 | 8         | 5.63%   |
| Intel AX200 Bluetooth                                 | 7         | 4.93%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 6         | 4.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 6         | 4.23%   |
| IMC Networks Bluetooth Device                         | 5         | 3.52%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3         | 2.11%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 3         | 2.11%   |
| HP Broadcom 2070 Bluetooth Combo                      | 3         | 2.11%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]      | 3         | 2.11%   |
| Realtek RTL8723B Bluetooth                            | 2         | 1.41%   |
| Realtek Bluetooth Radio                               | 2         | 1.41%   |
| Qualcomm Atheros  Bluetooth Device                    | 2         | 1.41%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 2         | 1.41%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 2         | 1.41%   |
| Intel AX210 Bluetooth                                 | 2         | 1.41%   |
| Broadcom BCM43142 Bluetooth 4.0                       | 2         | 1.41%   |
| Broadcom BCM2045B (BDC-2.1)                           | 2         | 1.41%   |
| Broadcom BCM2045 Bluetooth                            | 2         | 1.41%   |
| Apple Bluetooth Host Controller                       | 2         | 1.41%   |
| Toshiba Bluetooth USB Host Controller                 | 1         | 0.7%    |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 0.7%    |
| Ralink RT3290 Bluetooth                               | 1         | 0.7%    |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 0.7%    |
| Qualcomm Atheros AR3012 Bluetooth                     | 1         | 0.7%    |
| Lite-On Bluetooth Device                              | 1         | 0.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1         | 0.7%    |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.7%    |
| IMC Networks BCM20702A0                               | 1         | 0.7%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 1         | 0.7%    |
| IMC Networks 802.11ac WLAN Adapter                    | 1         | 0.7%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 1         | 0.7%    |
| Foxconn / Hon Hai Wireless_Device                     | 1         | 0.7%    |
| Dell BCM20702A0 Bluetooth Module                      | 1         | 0.7%    |
| Broadcom HP Portable SoftSailing                      | 1         | 0.7%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                  | 1         | 0.7%    |
| ASUS Bluetooth Radio                                  | 1         | 0.7%    |
| ASUS ASUS USB-BT500                                   | 1         | 0.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 181       | 52.01%  |
| AMD                     | 66        | 18.97%  |
| Nvidia                  | 65        | 18.68%  |
| C-Media Electronics     | 7         | 2.01%   |
| Razer USA               | 3         | 0.86%   |
| Lenovo                  | 3         | 0.86%   |
| Kingston Technology     | 3         | 0.86%   |
| SteelSeries ApS         | 2         | 0.57%   |
| Realtek Semiconductor   | 2         | 0.57%   |
| Logitech                | 2         | 0.57%   |
| Focusrite-Novation      | 2         | 0.57%   |
| VIA Technologies        | 1         | 0.29%   |
| Texas Instruments       | 1         | 0.29%   |
| TerraTec Electronic     | 1         | 0.29%   |
| Syntek                  | 1         | 0.29%   |
| Samson Technologies     | 1         | 0.29%   |
| Roland                  | 1         | 0.29%   |
| Micronas                | 1         | 0.29%   |
| Mark of the Unicorn     | 1         | 0.29%   |
| M-Audio                 | 1         | 0.29%   |
| JMTek                   | 1         | 0.29%   |
| Creative Labs           | 1         | 0.29%   |
| BEHRINGER International | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 21        | 5.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 20        | 4.95%   |
| AMD Family 17h/19h HD Audio Controller                                     | 19        | 4.7%    |
| Intel Sunrise Point-LP HD Audio                                            | 18        | 4.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18        | 4.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13        | 3.22%   |
| AMD Starship/Matisse HD Audio Controller                                   | 12        | 2.97%   |
| Intel Cannon Lake PCH cAVS                                                 | 10        | 2.48%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 2.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8         | 1.98%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 1.98%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 1.98%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8         | 1.98%   |
| Nvidia TU106 High Definition Audio Controller                              | 7         | 1.73%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 1.73%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 1.73%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 1.73%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 1.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 1.73%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7         | 1.73%   |
| Nvidia GP104 High Definition Audio Controller                              | 6         | 1.49%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 1.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 1.49%   |
| AMD FCH Azalia Controller                                                  | 6         | 1.49%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.24%   |
| Intel CM238 HD Audio Controller                                            | 5         | 1.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.24%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 1.24%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 0.99%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.74%   |
| Nvidia GP108 High Definition Audio Controller                              | 3         | 0.74%   |
| Nvidia GP102 HDMI Audio Controller                                         | 3         | 0.74%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3         | 0.74%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3         | 0.74%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 0.74%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 0.74%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 0.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 35        | 20.71%  |
| SK hynix            | 24        | 14.2%   |
| Kingston            | 21        | 12.43%  |
| Unknown             | 17        | 10.06%  |
| Micron Technology   | 17        | 10.06%  |
| G.Skill             | 15        | 8.88%   |
| Crucial             | 13        | 7.69%   |
| Corsair             | 5         | 2.96%   |
| Ramaxel Technology  | 4         | 2.37%   |
| A-DATA Technology   | 3         | 1.78%   |
| Unknown (ABCD)      | 2         | 1.18%   |
| Patriot             | 2         | 1.18%   |
| Elpida              | 2         | 1.18%   |
| Apacer              | 2         | 1.18%   |
| Unifosa             | 1         | 0.59%   |
| Team                | 1         | 0.59%   |
| Silicon Power       | 1         | 0.59%   |
| Nanya Technology    | 1         | 0.59%   |
| ASint Technology    | 1         | 0.59%   |
| Aeneon              | 1         | 0.59%   |
| Unknown             | 1         | 0.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 2.16%   |
| Unknown RAM Module 512MB DIMM SDRAM                              | 2         | 1.08%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 1.08%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 2         | 1.08%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s         | 2         | 1.08%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.08%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 1.08%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.08%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.08%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.08%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.08%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s              | 2         | 1.08%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 2         | 1.08%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 0.54%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                     | 1         | 0.54%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.54%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 0.54%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR3 1867MT/s           | 1         | 0.54%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.54%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.54%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.54%   |
| Unknown RAM Module 256MB DIMM                                    | 1         | 0.54%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.54%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.54%   |
| Unknown RAM Module 2048MB DIMM DDR3 800MT/s                      | 1         | 0.54%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.54%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 1         | 0.54%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                      | 1         | 0.54%   |
| Unknown RAM Module 1024MB DIMM                                   | 1         | 0.54%   |
| Unifosa RAM GU332G0AJEPR8H2L 2048MB SODIMM DDR2 667MT/s          | 1         | 0.54%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s              | 1         | 0.54%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                  | 1         | 0.54%   |
| SK hynix RAM Module 8192MB DIMM DDR3 1333MT/s                    | 1         | 0.54%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                     | 1         | 0.54%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2133MT/s                  | 1         | 0.54%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1333MT/s                    | 1         | 0.54%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s            | 1         | 0.54%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 0.54%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.54%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 68        | 47.55%  |
| DDR3    | 48        | 33.57%  |
| DDR2    | 8         | 5.59%   |
| SDRAM   | 7         | 4.9%    |
| LPDDR4  | 4         | 2.8%    |
| Unknown | 4         | 2.8%    |
| LPDDR3  | 2         | 1.4%    |
| DDR     | 2         | 1.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 75        | 53.19%  |
| DIMM         | 60        | 42.55%  |
| Row Of Chips | 6         | 4.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 53        | 33.97%  |
| 4096  | 46        | 29.49%  |
| 16384 | 22        | 14.1%   |
| 2048  | 17        | 10.9%   |
| 1024  | 7         | 4.49%   |
| 32768 | 5         | 3.21%   |
| 512   | 5         | 3.21%   |
| 256   | 1         | 0.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 30        | 19.11%  |
| 2667    | 25        | 15.92%  |
| 3200    | 19        | 12.1%   |
| 1333    | 13        | 8.28%   |
| 2400    | 9         | 5.73%   |
| 3600    | 7         | 4.46%   |
| 2133    | 7         | 4.46%   |
| Unknown | 7         | 4.46%   |
| 1334    | 6         | 3.82%   |
| 800     | 4         | 2.55%   |
| 1067    | 3         | 1.91%   |
| 667     | 3         | 1.91%   |
| 4267    | 2         | 1.27%   |
| 4199    | 2         | 1.27%   |
| 3666    | 2         | 1.27%   |
| 3266    | 2         | 1.27%   |
| 2666    | 2         | 1.27%   |
| 1867    | 2         | 1.27%   |
| 3800    | 1         | 0.64%   |
| 3334    | 1         | 0.64%   |
| 3000    | 1         | 0.64%   |
| 2933    | 1         | 0.64%   |
| 2733    | 1         | 0.64%   |
| 1866    | 1         | 0.64%   |
| 1800    | 1         | 0.64%   |
| 1400    | 1         | 0.64%   |
| 1066    | 1         | 0.64%   |
| 975     | 1         | 0.64%   |
| 533     | 1         | 0.64%   |
| 400     | 1         | 0.64%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


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

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Seiko Epson Perfection 660 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 31        | 21.83%  |
| Microdia                               | 14        | 9.86%   |
| Realtek Semiconductor                  | 13        | 9.15%   |
| IMC Networks                           | 12        | 8.45%   |
| Sunplus Innovation Technology          | 11        | 7.75%   |
| Acer                                   | 11        | 7.75%   |
| Logitech                               | 10        | 7.04%   |
| Silicon Motion                         | 5         | 3.52%   |
| Lite-On Technology                     | 5         | 3.52%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.52%   |
| Syntek                                 | 4         | 2.82%   |
| Suyin                                  | 4         | 2.82%   |
| Apple                                  | 3         | 2.11%   |
| Quanta                                 | 2         | 1.41%   |
| Luxvisions Innotech Limited            | 2         | 1.41%   |
| Arkmicro Technologies                  | 2         | 1.41%   |
| Z-Star Microelectronics                | 1         | 0.7%    |
| Samsung Electronics                    | 1         | 0.7%    |
| Microsoft                              | 1         | 0.7%    |
| Lenovo                                 | 1         | 0.7%    |
| Importek                               | 1         | 0.7%    |
| Huddly                                 | 1         | 0.7%    |
| Creative Technology                    | 1         | 0.7%    |
| Alcor Micro                            | 1         | 0.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 9         | 6.21%   |
| Chicony Integrated Camera                               | 5         | 3.45%   |
| Realtek USB Camera                                      | 4         | 2.76%   |
| Lite-On Integrated Camera                               | 4         | 2.76%   |
| Logitech Webcam C930e                                   | 3         | 2.07%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 2.07%   |
| IMC Networks Integrated Camera                          | 3         | 2.07%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 3         | 2.07%   |
| Chicony Integrated HP HD Webcam                         | 3         | 2.07%   |
| Acer Integrated Camera                                  | 3         | 2.07%   |
| Syntek Integrated Camera                                | 2         | 1.38%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 1.38%   |
| Sunplus ASUS USB2.0 Webcam                              | 2         | 1.38%   |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.] | 2         | 1.38%   |
| Realtek Lenovo EasyCamera                               | 2         | 1.38%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.38%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 1.38%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 1.38%   |
| Logitech Webcam C270                                    | 2         | 1.38%   |
| Logitech HD Webcam C525                                 | 2         | 1.38%   |
| Logitech HD Pro Webcam C920                             | 2         | 1.38%   |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 1.38%   |
| Chicony ThinkPad T490 Webcam                            | 2         | 1.38%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 1.38%   |
| Chicony HP Wide Vision HD Camera                        | 2         | 1.38%   |
| Chicony HP HD Webcam                                    | 2         | 1.38%   |
| Chicony FJ Camera                                       | 2         | 1.38%   |
| Arkmicro USB2.0 PC CAMERA                               | 2         | 1.38%   |
| Apple iPhone5/5C/5S/6                                   | 2         | 1.38%   |
| Z-Star A4 TECH USB2.0 PC Camera E                       | 1         | 0.69%   |
| Syntek USB2.0 UVC PC Camera                             | 1         | 0.69%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.69%   |
| Suyin USB Webcam                                        | 1         | 0.69%   |
| Suyin Integrated_Webcam_HD                              | 1         | 0.69%   |
| Suyin HD WebCam                                         | 1         | 0.69%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 1         | 0.69%   |
| Sunplus Laptop_Integrated_Webcam_HD                     | 1         | 0.69%   |
| Sunplus Integrated Webcam                               | 1         | 0.69%   |
| Sunplus HP Wide Vision HD                               | 1         | 0.69%   |
| Sunplus HP Universal Camera                             | 1         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| OmniKey               | 17        | 37.78%  |
| Alcor Micro           | 17        | 37.78%  |
| Lenovo                | 3         | 6.67%   |
| Gemalto (was Gemplus) | 3         | 6.67%   |
| Broadcom              | 3         | 6.67%   |
| SCM Microsystems      | 1         | 2.22%   |
| O2 Micro              | 1         | 2.22%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| OmniKey CardMan 1021                                   | 14        | 31.11%  |
| Alcor Micro AU9540 Smartcard Reader                    | 14        | 31.11%  |
| OmniKey CardMan 4321                                   | 3         | 6.67%   |
| Lenovo Integrated Smart Card Reader                    | 3         | 6.67%   |
| Broadcom 58200                                         | 3         | 6.67%   |
| Alcor Micro Watchdata W 1981                           | 3         | 6.67%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader      | 2         | 4.44%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1         | 2.22%   |
| O2 Micro OZ776 CCID Smartcard Reader                   | 1         | 2.22%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer | 1         | 2.22%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 160       | 64.26%  |
| 1     | 70        | 28.11%  |
| 2     | 19        | 7.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 38        | 35.51%  |
| Graphics card            | 25        | 23.36%  |
| Chipcard                 | 24        | 22.43%  |
| Net/wireless             | 6         | 5.61%   |
| Multimedia controller    | 3         | 2.8%    |
| Communication controller | 3         | 2.8%    |
| Net/ethernet             | 2         | 1.87%   |
| Camera                   | 2         | 1.87%   |
| Sound                    | 1         | 0.93%   |
| Modem                    | 1         | 0.93%   |
| Card reader              | 1         | 0.93%   |
| Bluetooth                | 1         | 0.93%   |

