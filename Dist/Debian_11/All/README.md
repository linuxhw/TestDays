Debian 11 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Debian 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian_11/Desktop/README.md) and [notebooks](/Dist/Debian_11/Notebook/README.md).

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

Total: 7847

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Umbrel        | Home                        | Mini pc     | [f4afc80a6c](https://linux-hardware.org/?probe=f4afc80a6c) | Feb 28, 2023 |
| Medion        | TJ4125                      | Desktop     | [2024916642](https://linux-hardware.org/?probe=2024916642) | Feb 28, 2023 |
| CWWK          | CW-J6-6L                    | Desktop     | [46c17d2c14](https://linux-hardware.org/?probe=46c17d2c14) | Feb 28, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [1165717061](https://linux-hardware.org/?probe=1165717061) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [921aebe62a](https://linux-hardware.org/?probe=921aebe62a) | Feb 28, 2023 |
| HP            | 83E2                        | Desktop     | [fdbe4ec1cb](https://linux-hardware.org/?probe=fdbe4ec1cb) | Feb 28, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [19fd766ea6](https://linux-hardware.org/?probe=19fd766ea6) | Feb 28, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [17fcfc2758](https://linux-hardware.org/?probe=17fcfc2758) | Feb 28, 2023 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [26a7db2ed8](https://linux-hardware.org/?probe=26a7db2ed8) | Feb 28, 2023 |
| AZW           | MINI S                      | Desktop     | [e65b0d1ef6](https://linux-hardware.org/?probe=e65b0d1ef6) | Feb 28, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [49205269e7](https://linux-hardware.org/?probe=49205269e7) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | Notebook    | [3fa4d926e0](https://linux-hardware.org/?probe=3fa4d926e0) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [fa2df8125a](https://linux-hardware.org/?probe=fa2df8125a) | Feb 28, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [8cadddf432](https://linux-hardware.org/?probe=8cadddf432) | Feb 28, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [a5469adf59](https://linux-hardware.org/?probe=a5469adf59) | Feb 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b4bfab8974](https://linux-hardware.org/?probe=b4bfab8974) | Feb 28, 2023 |
| HP            | ProBook 6570b               | Notebook    | [3692011e3f](https://linux-hardware.org/?probe=3692011e3f) | Feb 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [4d3d5e02a1](https://linux-hardware.org/?probe=4d3d5e02a1) | Feb 28, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3948048a11](https://linux-hardware.org/?probe=3948048a11) | Feb 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [83a611b1ab](https://linux-hardware.org/?probe=83a611b1ab) | Feb 27, 2023 |
| HP            | 3397                        | Desktop     | [8081d24eb1](https://linux-hardware.org/?probe=8081d24eb1) | Feb 27, 2023 |
| Dell          | 0MH651                      | Desktop     | [7921e9f8bc](https://linux-hardware.org/?probe=7921e9f8bc) | Feb 27, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [ccac327e17](https://linux-hardware.org/?probe=ccac327e17) | Feb 27, 2023 |
| Aquarius      | AQH310CM                    | Desktop     | [a2f4d0f77e](https://linux-hardware.org/?probe=a2f4d0f77e) | Feb 27, 2023 |
| Dell          | Latitude 5400               | Notebook    | [b788c61c95](https://linux-hardware.org/?probe=b788c61c95) | Feb 27, 2023 |
| Dell          | Latitude 3510               | Notebook    | [de938c4962](https://linux-hardware.org/?probe=de938c4962) | Feb 27, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [7a8e478900](https://linux-hardware.org/?probe=7a8e478900) | Feb 27, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [29f6c3c897](https://linux-hardware.org/?probe=29f6c3c897) | Feb 27, 2023 |
| ASUSTek       | K52F                        | Notebook    | [fa30ea101a](https://linux-hardware.org/?probe=fa30ea101a) | Feb 27, 2023 |
| ASUSTek       | H61M-E                      | Desktop     | [ee5b36d127](https://linux-hardware.org/?probe=ee5b36d127) | Feb 27, 2023 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [dd2f99b3ca](https://linux-hardware.org/?probe=dd2f99b3ca) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b4485b65b3](https://linux-hardware.org/?probe=b4485b65b3) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [a52e16df32](https://linux-hardware.org/?probe=a52e16df32) | Feb 27, 2023 |
| HP            | Pavilion g6                 | Notebook    | [41e4ef16e4](https://linux-hardware.org/?probe=41e4ef16e4) | Feb 26, 2023 |
| Olimex        | A20-OLinuXino-LIME          | Soc         | [bcb9e7b9e7](https://linux-hardware.org/?probe=bcb9e7b9e7) | Feb 26, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [787ddfd44c](https://linux-hardware.org/?probe=787ddfd44c) | Feb 26, 2023 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [3c4718f66e](https://linux-hardware.org/?probe=3c4718f66e) | Feb 26, 2023 |
| Panasonic     | CF-31WEUEEBE                | Notebook    | [40782ba0a7](https://linux-hardware.org/?probe=40782ba0a7) | Feb 26, 2023 |
| Supermicro    | X11SDV-8C-TP8F              | Server      | [ffa58f1702](https://linux-hardware.org/?probe=ffa58f1702) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430 2349GUU       | Notebook    | [95cc420bd5](https://linux-hardware.org/?probe=95cc420bd5) | Feb 26, 2023 |
| Medion        | BEAST X25                   | Notebook    | [3263e2862a](https://linux-hardware.org/?probe=3263e2862a) | Feb 26, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9e587033a4](https://linux-hardware.org/?probe=9e587033a4) | Feb 26, 2023 |
| HP            | Compaq 6730b (FU594ES#AB... | Notebook    | [810cdb1ad1](https://linux-hardware.org/?probe=810cdb1ad1) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [28bb1541b4](https://linux-hardware.org/?probe=28bb1541b4) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [8906540d72](https://linux-hardware.org/?probe=8906540d72) | Feb 26, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [9c64d6366e](https://linux-hardware.org/?probe=9c64d6366e) | Feb 26, 2023 |
| Lenovo        | ThinkPad X13s Gen 1 21BX... | Notebook    | [633fb08804](https://linux-hardware.org/?probe=633fb08804) | Feb 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [aaa112feae](https://linux-hardware.org/?probe=aaa112feae) | Feb 26, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b05fb1c01b](https://linux-hardware.org/?probe=b05fb1c01b) | Feb 26, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [3b2a19c835](https://linux-hardware.org/?probe=3b2a19c835) | Feb 26, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [f2671a0f62](https://linux-hardware.org/?probe=f2671a0f62) | Feb 25, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [c8ead0e580](https://linux-hardware.org/?probe=c8ead0e580) | Feb 25, 2023 |
| Unknown       | T3 MRD                      | Notebook    | [ae88920ea5](https://linux-hardware.org/?probe=ae88920ea5) | Feb 25, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [76e7c1c236](https://linux-hardware.org/?probe=76e7c1c236) | Feb 25, 2023 |
| MSI           | B85M-E45                    | Desktop     | [a7748c0e8b](https://linux-hardware.org/?probe=a7748c0e8b) | Feb 25, 2023 |
| HUAWEI        | WRT-WX9                     | Notebook    | [d49316c5e8](https://linux-hardware.org/?probe=d49316c5e8) | Feb 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [67e31f8e42](https://linux-hardware.org/?probe=67e31f8e42) | Feb 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [2bb4e30118](https://linux-hardware.org/?probe=2bb4e30118) | Feb 25, 2023 |
| Medion        | TJ4125                      | Desktop     | [bde9228741](https://linux-hardware.org/?probe=bde9228741) | Feb 25, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [f1db9ad466](https://linux-hardware.org/?probe=f1db9ad466) | Feb 25, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [ff08a846b0](https://linux-hardware.org/?probe=ff08a846b0) | Feb 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [2c5d6ab621](https://linux-hardware.org/?probe=2c5d6ab621) | Feb 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [15b5511875](https://linux-hardware.org/?probe=15b5511875) | Feb 25, 2023 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [b3b189e875](https://linux-hardware.org/?probe=b3b189e875) | Feb 25, 2023 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [d615820c71](https://linux-hardware.org/?probe=d615820c71) | Feb 25, 2023 |
| Intel         | JSL MRD                     | Desktop     | [84a33f3c84](https://linux-hardware.org/?probe=84a33f3c84) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5cde621e0a](https://linux-hardware.org/?probe=5cde621e0a) | Feb 24, 2023 |
| Acer          | AO756                       | Notebook    | [ca83ee78ec](https://linux-hardware.org/?probe=ca83ee78ec) | Feb 24, 2023 |
| Lenovo        | KaiTian N70z G1d            | Notebook    | [cbc8e4e008](https://linux-hardware.org/?probe=cbc8e4e008) | Feb 24, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [62b46afbb8](https://linux-hardware.org/?probe=62b46afbb8) | Feb 24, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [c2ca1fb2f3](https://linux-hardware.org/?probe=c2ca1fb2f3) | Feb 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7fe6e0dcde](https://linux-hardware.org/?probe=7fe6e0dcde) | Feb 24, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [f5b4a5da72](https://linux-hardware.org/?probe=f5b4a5da72) | Feb 24, 2023 |
| HP            | Presario CQ57               | Notebook    | [b41de6d094](https://linux-hardware.org/?probe=b41de6d094) | Feb 24, 2023 |
| HP            | 82F2 A01                    | Desktop     | [efc9b2fdbf](https://linux-hardware.org/?probe=efc9b2fdbf) | Feb 24, 2023 |
| HP            | 82F2 A01                    | Desktop     | [24dc4341d3](https://linux-hardware.org/?probe=24dc4341d3) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [3f28f459bf](https://linux-hardware.org/?probe=3f28f459bf) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [8ed4158090](https://linux-hardware.org/?probe=8ed4158090) | Feb 24, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [1989031eb6](https://linux-hardware.org/?probe=1989031eb6) | Feb 24, 2023 |
| Dell          | Latitude D620               | Notebook    | [fba80b099d](https://linux-hardware.org/?probe=fba80b099d) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5da2f709bb](https://linux-hardware.org/?probe=5da2f709bb) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [bf32299a30](https://linux-hardware.org/?probe=bf32299a30) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [54279e4e30](https://linux-hardware.org/?probe=54279e4e30) | Feb 24, 2023 |
| HP            | EliteBook Folio 9480m       | Notebook    | [788e0929de](https://linux-hardware.org/?probe=788e0929de) | Feb 24, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [52b14c9235](https://linux-hardware.org/?probe=52b14c9235) | Feb 24, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [a09d17dd16](https://linux-hardware.org/?probe=a09d17dd16) | Feb 24, 2023 |
| Samsung       | N150P                       | Notebook    | [662488621d](https://linux-hardware.org/?probe=662488621d) | Feb 24, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e3f8cf325d](https://linux-hardware.org/?probe=e3f8cf325d) | Feb 24, 2023 |
| Unknown       | Unknown                     | Soc         | [23a808c1e1](https://linux-hardware.org/?probe=23a808c1e1) | Feb 24, 2023 |
| Unknown       | Unknown                     | Soc         | [44fdfeedf2](https://linux-hardware.org/?probe=44fdfeedf2) | Feb 24, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [0806dcb9ca](https://linux-hardware.org/?probe=0806dcb9ca) | Feb 24, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [e3cdd0b411](https://linux-hardware.org/?probe=e3cdd0b411) | Feb 24, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [e44618f1c3](https://linux-hardware.org/?probe=e44618f1c3) | Feb 23, 2023 |
| ASUSTek       | KRPA-U16 Series             | Desktop     | [e417ffd8e7](https://linux-hardware.org/?probe=e417ffd8e7) | Feb 23, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [885478dd47](https://linux-hardware.org/?probe=885478dd47) | Feb 23, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [53eb80a44b](https://linux-hardware.org/?probe=53eb80a44b) | Feb 23, 2023 |
| Lenovo        | ThinkPad T410 2537CS0       | Notebook    | [8d4b399341](https://linux-hardware.org/?probe=8d4b399341) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [53d46c67f9](https://linux-hardware.org/?probe=53d46c67f9) | Feb 23, 2023 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [4f19f71811](https://linux-hardware.org/?probe=4f19f71811) | Feb 23, 2023 |
| Dell          | 01V648 A03                  | Server      | [c0b7421a8b](https://linux-hardware.org/?probe=c0b7421a8b) | Feb 23, 2023 |
| LincPlus      | P2                          | Notebook    | [5d4e528621](https://linux-hardware.org/?probe=5d4e528621) | Feb 23, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [a3ea522d78](https://linux-hardware.org/?probe=a3ea522d78) | Feb 23, 2023 |
| Intel         | H61                         | Desktop     | [de757dd659](https://linux-hardware.org/?probe=de757dd659) | Feb 23, 2023 |
| Lenovo        | ThinkPad E14 20RA0036HV     | Notebook    | [eef601ff61](https://linux-hardware.org/?probe=eef601ff61) | Feb 23, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [09070f52bb](https://linux-hardware.org/?probe=09070f52bb) | Feb 23, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [0233d7525d](https://linux-hardware.org/?probe=0233d7525d) | Feb 22, 2023 |
| AZW           | U59                         | Desktop     | [9289537f45](https://linux-hardware.org/?probe=9289537f45) | Feb 22, 2023 |
| Fujitsu       | LIFEBOOK E753               | Notebook    | [8fa3315cca](https://linux-hardware.org/?probe=8fa3315cca) | Feb 22, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9d233c96b5](https://linux-hardware.org/?probe=9d233c96b5) | Feb 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [8227fec538](https://linux-hardware.org/?probe=8227fec538) | Feb 22, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [fb050eaf3c](https://linux-hardware.org/?probe=fb050eaf3c) | Feb 22, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [7cf8754a48](https://linux-hardware.org/?probe=7cf8754a48) | Feb 22, 2023 |
| Acer          | AO756                       | Notebook    | [58f52941c7](https://linux-hardware.org/?probe=58f52941c7) | Feb 22, 2023 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [1d2132b142](https://linux-hardware.org/?probe=1d2132b142) | Feb 22, 2023 |
| AZW           | U59                         | Desktop     | [368562790b](https://linux-hardware.org/?probe=368562790b) | Feb 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [5cf4127d47](https://linux-hardware.org/?probe=5cf4127d47) | Feb 21, 2023 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [30f09c71a1](https://linux-hardware.org/?probe=30f09c71a1) | Feb 21, 2023 |
| ASUSTek       | X556UQ                      | Notebook    | [8f645fa6fc](https://linux-hardware.org/?probe=8f645fa6fc) | Feb 21, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [de56e36164](https://linux-hardware.org/?probe=de56e36164) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470 20HDS1DL03    | Notebook    | [25e1a3f801](https://linux-hardware.org/?probe=25e1a3f801) | Feb 21, 2023 |
| Dell          | Latitude E6430              | Notebook    | [80c9785ef0](https://linux-hardware.org/?probe=80c9785ef0) | Feb 21, 2023 |
| Dell          | 0TT740 A00                  | Server      | [2e77448a7d](https://linux-hardware.org/?probe=2e77448a7d) | Feb 21, 2023 |
| Dell          | 0TT740 A00                  | Server      | [ec75c9762a](https://linux-hardware.org/?probe=ec75c9762a) | Feb 21, 2023 |
| HP            | ProLiant ML110 G7           | Desktop     | [56cbaf4274](https://linux-hardware.org/?probe=56cbaf4274) | Feb 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [1c0772ccd7](https://linux-hardware.org/?probe=1c0772ccd7) | Feb 21, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [6ab7953740](https://linux-hardware.org/?probe=6ab7953740) | Feb 20, 2023 |
| Notebook      | PB50_70RF,RD,RC             | Notebook    | [b24f005b1d](https://linux-hardware.org/?probe=b24f005b1d) | Feb 20, 2023 |
| HP            | Stream 8 Tablet             | Tablet      | [211438a893](https://linux-hardware.org/?probe=211438a893) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | Notebook    | [19d29283ed](https://linux-hardware.org/?probe=19d29283ed) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | Notebook    | [8d1bb46519](https://linux-hardware.org/?probe=8d1bb46519) | Feb 20, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [211cd972f0](https://linux-hardware.org/?probe=211cd972f0) | Feb 20, 2023 |
| Acer          | Extensa 2520G               | Notebook    | [823c5829a9](https://linux-hardware.org/?probe=823c5829a9) | Feb 20, 2023 |
| Lenovo        | ThinkPad T430 2349PZG       | Notebook    | [7bd3c5a555](https://linux-hardware.org/?probe=7bd3c5a555) | Feb 20, 2023 |
| Acer          | Aspire V5-573G              | Notebook    | [376b35f5b6](https://linux-hardware.org/?probe=376b35f5b6) | Feb 20, 2023 |
| Lenovo        | ThinkCentre M58e 7269E3S    | Desktop     | [6b30da3a31](https://linux-hardware.org/?probe=6b30da3a31) | Feb 20, 2023 |
| Dell          | Latitude E7270              | Notebook    | [4eb17c846c](https://linux-hardware.org/?probe=4eb17c846c) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [234358d23e](https://linux-hardware.org/?probe=234358d23e) | Feb 20, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [53ba72d592](https://linux-hardware.org/?probe=53ba72d592) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [1b75d34b95](https://linux-hardware.org/?probe=1b75d34b95) | Feb 20, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [b778aa73ca](https://linux-hardware.org/?probe=b778aa73ca) | Feb 19, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [a2250b4489](https://linux-hardware.org/?probe=a2250b4489) | Feb 19, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [5a296bed7f](https://linux-hardware.org/?probe=5a296bed7f) | Feb 19, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [e259c81376](https://linux-hardware.org/?probe=e259c81376) | Feb 19, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [2e3da97146](https://linux-hardware.org/?probe=2e3da97146) | Feb 19, 2023 |
| Dell          | 0NHNHP A01                  | Server      | [da74244bff](https://linux-hardware.org/?probe=da74244bff) | Feb 19, 2023 |
| Dell          | 073MMW A02                  | Desktop     | [aa198228bc](https://linux-hardware.org/?probe=aa198228bc) | Feb 19, 2023 |
| Dell          | 0T065F A01                  | Desktop     | [c8b1f8651a](https://linux-hardware.org/?probe=c8b1f8651a) | Feb 19, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [34681494ec](https://linux-hardware.org/?probe=34681494ec) | Feb 18, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [537c2d1b64](https://linux-hardware.org/?probe=537c2d1b64) | Feb 18, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [3158f1e0d5](https://linux-hardware.org/?probe=3158f1e0d5) | Feb 18, 2023 |
| Supermicro    | X11SCA-WA                   | Server      | [065427c37f](https://linux-hardware.org/?probe=065427c37f) | Feb 18, 2023 |
| Intel         | JSL MRD                     | Desktop     | [5e021f6a92](https://linux-hardware.org/?probe=5e021f6a92) | Feb 18, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [8907f179e9](https://linux-hardware.org/?probe=8907f179e9) | Feb 18, 2023 |
| Lenovo        | ThinkPad E480 20KN001QGE    | Notebook    | [008f40a707](https://linux-hardware.org/?probe=008f40a707) | Feb 18, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a782ccbba9](https://linux-hardware.org/?probe=a782ccbba9) | Feb 18, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [a2cdf7d471](https://linux-hardware.org/?probe=a2cdf7d471) | Feb 18, 2023 |
| Dell          | Latitude E5450              | Notebook    | [56827b29dc](https://linux-hardware.org/?probe=56827b29dc) | Feb 18, 2023 |
| Gigabyte      | GA-A55M-DS2                 | Desktop     | [3159aede6c](https://linux-hardware.org/?probe=3159aede6c) | Feb 17, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Notebook    | [32f5d5e200](https://linux-hardware.org/?probe=32f5d5e200) | Feb 17, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [bd6636c99d](https://linux-hardware.org/?probe=bd6636c99d) | Feb 17, 2023 |
| Intel         | H61                         | Desktop     | [90e4a9358f](https://linux-hardware.org/?probe=90e4a9358f) | Feb 17, 2023 |
| MSI           | X399 SLI PLUS               | Desktop     | [8741094cd9](https://linux-hardware.org/?probe=8741094cd9) | Feb 17, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [423c7bb57a](https://linux-hardware.org/?probe=423c7bb57a) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | Notebook    | [4bf1ccfe74](https://linux-hardware.org/?probe=4bf1ccfe74) | Feb 17, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [4ab4c99cab](https://linux-hardware.org/?probe=4ab4c99cab) | Feb 17, 2023 |
| Dell          | System XPS L702X            | Notebook    | [81f9738975](https://linux-hardware.org/?probe=81f9738975) | Feb 16, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | Desktop     | [cfdcc68921](https://linux-hardware.org/?probe=cfdcc68921) | Feb 16, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | Desktop     | [7bb3c6268f](https://linux-hardware.org/?probe=7bb3c6268f) | Feb 16, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [8f202b88fa](https://linux-hardware.org/?probe=8f202b88fa) | Feb 16, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [c812182e32](https://linux-hardware.org/?probe=c812182e32) | Feb 16, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [9ad890517a](https://linux-hardware.org/?probe=9ad890517a) | Feb 16, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [63747d1456](https://linux-hardware.org/?probe=63747d1456) | Feb 16, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [cda38b5b9b](https://linux-hardware.org/?probe=cda38b5b9b) | Feb 16, 2023 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [387881f288](https://linux-hardware.org/?probe=387881f288) | Feb 16, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [46aafc59c4](https://linux-hardware.org/?probe=46aafc59c4) | Feb 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bbce6ba3b1](https://linux-hardware.org/?probe=bbce6ba3b1) | Feb 16, 2023 |
| Lenovo        | 1030 SDK0J40705 WIN 3425... | Desktop     | [daed0124f0](https://linux-hardware.org/?probe=daed0124f0) | Feb 16, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [a4fd7cdaa8](https://linux-hardware.org/?probe=a4fd7cdaa8) | Feb 16, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [5398361b68](https://linux-hardware.org/?probe=5398361b68) | Feb 16, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [73787e9141](https://linux-hardware.org/?probe=73787e9141) | Feb 16, 2023 |
| Gigabyte      | H270M-D3H-CF                | Desktop     | [7a58ceb644](https://linux-hardware.org/?probe=7a58ceb644) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [2b25f214e9](https://linux-hardware.org/?probe=2b25f214e9) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [5bf8aa635c](https://linux-hardware.org/?probe=5bf8aa635c) | Feb 15, 2023 |
| Google        | Grunt                       | Notebook    | [89c633c2c1](https://linux-hardware.org/?probe=89c633c2c1) | Feb 15, 2023 |
| Gigabyte      | EP43-S3L                    | Desktop     | [82730ed699](https://linux-hardware.org/?probe=82730ed699) | Feb 15, 2023 |
| Itautec       | ST 4265                     | Desktop     | [84023fa8ac](https://linux-hardware.org/?probe=84023fa8ac) | Feb 15, 2023 |
| ASUSTek       | P5GD1 PRO                   | Desktop     | [043021ca86](https://linux-hardware.org/?probe=043021ca86) | Feb 15, 2023 |
| ASUSTek       | K53U                        | Notebook    | [e9a6a69e01](https://linux-hardware.org/?probe=e9a6a69e01) | Feb 15, 2023 |
| ASRock        | Z77 Extreme6                | Desktop     | [48328ab864](https://linux-hardware.org/?probe=48328ab864) | Feb 15, 2023 |
| Unknown       | T3 MRD                      | Notebook    | [df134a8199](https://linux-hardware.org/?probe=df134a8199) | Feb 14, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [e9faf4ce80](https://linux-hardware.org/?probe=e9faf4ce80) | Feb 14, 2023 |
| Acer          | Aspire V5-572G              | Notebook    | [7f360258ff](https://linux-hardware.org/?probe=7f360258ff) | Feb 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [0ac84e31dd](https://linux-hardware.org/?probe=0ac84e31dd) | Feb 14, 2023 |
| Dell          | 0RN474                      | Desktop     | [5c1bf45372](https://linux-hardware.org/?probe=5c1bf45372) | Feb 14, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [27fa84ce56](https://linux-hardware.org/?probe=27fa84ce56) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [8895a873ab](https://linux-hardware.org/?probe=8895a873ab) | Feb 14, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [0a0e30ba0a](https://linux-hardware.org/?probe=0a0e30ba0a) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [fb00615692](https://linux-hardware.org/?probe=fb00615692) | Feb 14, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [977650806e](https://linux-hardware.org/?probe=977650806e) | Feb 14, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [ae563f7bfe](https://linux-hardware.org/?probe=ae563f7bfe) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [f6bcdb7c6b](https://linux-hardware.org/?probe=f6bcdb7c6b) | Feb 14, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [67b141272c](https://linux-hardware.org/?probe=67b141272c) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [345021f7f6](https://linux-hardware.org/?probe=345021f7f6) | Feb 14, 2023 |
| Lenovo        | ThinkPad P51 20HJS0AR16     | Notebook    | [ad0f22fe34](https://linux-hardware.org/?probe=ad0f22fe34) | Feb 14, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [c69ee15636](https://linux-hardware.org/?probe=c69ee15636) | Feb 14, 2023 |
| Dell          | 0RN474                      | Desktop     | [20f3c37dc2](https://linux-hardware.org/?probe=20f3c37dc2) | Feb 14, 2023 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [4750f3ad3a](https://linux-hardware.org/?probe=4750f3ad3a) | Feb 13, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [55e684c121](https://linux-hardware.org/?probe=55e684c121) | Feb 13, 2023 |
| Dell          | Latitude D630               | Notebook    | [04c083db36](https://linux-hardware.org/?probe=04c083db36) | Feb 13, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [855634fadc](https://linux-hardware.org/?probe=855634fadc) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [6fe738fa6d](https://linux-hardware.org/?probe=6fe738fa6d) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [122eded37e](https://linux-hardware.org/?probe=122eded37e) | Feb 13, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [e83cd923a5](https://linux-hardware.org/?probe=e83cd923a5) | Feb 13, 2023 |
| Google        | Droid                       | Notebook    | [435ab67598](https://linux-hardware.org/?probe=435ab67598) | Feb 12, 2023 |
| retsamarre... | 000-F4423-UK000-2000        | Tablet      | [c24b5a1f84](https://linux-hardware.org/?probe=c24b5a1f84) | Feb 12, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [89c31e6f8c](https://linux-hardware.org/?probe=89c31e6f8c) | Feb 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [72ce8d1929](https://linux-hardware.org/?probe=72ce8d1929) | Feb 12, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [54e092f58f](https://linux-hardware.org/?probe=54e092f58f) | Feb 12, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [09266b8b06](https://linux-hardware.org/?probe=09266b8b06) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [a541cb52eb](https://linux-hardware.org/?probe=a541cb52eb) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [35563886e8](https://linux-hardware.org/?probe=35563886e8) | Feb 12, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [09dff429cd](https://linux-hardware.org/?probe=09dff429cd) | Feb 12, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [b54b603772](https://linux-hardware.org/?probe=b54b603772) | Feb 12, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [52674d23ad](https://linux-hardware.org/?probe=52674d23ad) | Feb 12, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [9fa2cd7dfb](https://linux-hardware.org/?probe=9fa2cd7dfb) | Feb 12, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [4829b991be](https://linux-hardware.org/?probe=4829b991be) | Feb 12, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [4a6ea9bd99](https://linux-hardware.org/?probe=4a6ea9bd99) | Feb 12, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [063d6eb482](https://linux-hardware.org/?probe=063d6eb482) | Feb 12, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [1589cfe790](https://linux-hardware.org/?probe=1589cfe790) | Feb 11, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [22fdde82eb](https://linux-hardware.org/?probe=22fdde82eb) | Feb 11, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [3932889971](https://linux-hardware.org/?probe=3932889971) | Feb 11, 2023 |
| Notebook      | MAM2120                     | Notebook    | [300a622d96](https://linux-hardware.org/?probe=300a622d96) | Feb 11, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [ed3233c97b](https://linux-hardware.org/?probe=ed3233c97b) | Feb 11, 2023 |
| Lenovo        | Z710 20250                  | Notebook    | [94ee6da4d3](https://linux-hardware.org/?probe=94ee6da4d3) | Feb 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [27323a90bb](https://linux-hardware.org/?probe=27323a90bb) | Feb 11, 2023 |
| Acer          | Predator G9-793             | Notebook    | [8c11736bf0](https://linux-hardware.org/?probe=8c11736bf0) | Feb 11, 2023 |
| ASUSTek       | P5VD2-X                     | Desktop     | [32a509e760](https://linux-hardware.org/?probe=32a509e760) | Feb 11, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [2695a9350a](https://linux-hardware.org/?probe=2695a9350a) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [d003016397](https://linux-hardware.org/?probe=d003016397) | Feb 11, 2023 |
| AZW           | U59                         | Desktop     | [24ccf521f0](https://linux-hardware.org/?probe=24ccf521f0) | Feb 11, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [a3f08d08aa](https://linux-hardware.org/?probe=a3f08d08aa) | Feb 11, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [5483d83053](https://linux-hardware.org/?probe=5483d83053) | Feb 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [20a75bea61](https://linux-hardware.org/?probe=20a75bea61) | Feb 11, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [5b2605691d](https://linux-hardware.org/?probe=5b2605691d) | Feb 11, 2023 |
| AMD           | CM-iGLX Platform Board R... | Desktop     | [c256a73072](https://linux-hardware.org/?probe=c256a73072) | Feb 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [35b93693a5](https://linux-hardware.org/?probe=35b93693a5) | Feb 10, 2023 |
| Dell          | Latitude 7370               | Notebook    | [30c62c9e44](https://linux-hardware.org/?probe=30c62c9e44) | Feb 10, 2023 |
| Dell          | Latitude 7370               | Notebook    | [b4e7a5cb63](https://linux-hardware.org/?probe=b4e7a5cb63) | Feb 10, 2023 |
| Maxtang       | EHL30 V1.0                  | Desktop     | [4d133c615c](https://linux-hardware.org/?probe=4d133c615c) | Feb 10, 2023 |
| ASRockRack    | X570D4U                     | Desktop     | [bb2c98768e](https://linux-hardware.org/?probe=bb2c98768e) | Feb 10, 2023 |
| ASUSTek       | N751JX                      | Notebook    | [fd591a3e67](https://linux-hardware.org/?probe=fd591a3e67) | Feb 10, 2023 |
| Novatech      | NL40_50CU                   | Notebook    | [cca307c7db](https://linux-hardware.org/?probe=cca307c7db) | Feb 10, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [7ac6f508b2](https://linux-hardware.org/?probe=7ac6f508b2) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [8239d80ae0](https://linux-hardware.org/?probe=8239d80ae0) | Feb 10, 2023 |
| Intel         | H61                         | Desktop     | [e07896a0a6](https://linux-hardware.org/?probe=e07896a0a6) | Feb 10, 2023 |
| IBM           | ThinkPad T43 18714AG        | Notebook    | [0730c9228d](https://linux-hardware.org/?probe=0730c9228d) | Feb 10, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [8c4ab545de](https://linux-hardware.org/?probe=8c4ab545de) | Feb 09, 2023 |
| Acer          | Veriton N4630G              | Desktop     | [262d8ec347](https://linux-hardware.org/?probe=262d8ec347) | Feb 09, 2023 |
| Acer          | Aspire ES1-111M             | Notebook    | [82eea49fcd](https://linux-hardware.org/?probe=82eea49fcd) | Feb 09, 2023 |
| Acer          | Aspire ES1-111M             | Notebook    | [accbac47d5](https://linux-hardware.org/?probe=accbac47d5) | Feb 09, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [fd0b6a7a49](https://linux-hardware.org/?probe=fd0b6a7a49) | Feb 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [02adcb8587](https://linux-hardware.org/?probe=02adcb8587) | Feb 09, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [fe1dac78bb](https://linux-hardware.org/?probe=fe1dac78bb) | Feb 09, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [209d4693fe](https://linux-hardware.org/?probe=209d4693fe) | Feb 09, 2023 |
| Dell          | Latitude E7250              | Notebook    | [e3c1b1e038](https://linux-hardware.org/?probe=e3c1b1e038) | Feb 09, 2023 |
| Lenovo        | Legion Y520-15IKBN 80WK     | Notebook    | [ec17af9e06](https://linux-hardware.org/?probe=ec17af9e06) | Feb 09, 2023 |
| AMI           | Cherry Trail CR             | Notebook    | [e7eab93323](https://linux-hardware.org/?probe=e7eab93323) | Feb 09, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [a0132107aa](https://linux-hardware.org/?probe=a0132107aa) | Feb 08, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [6231dbe6d4](https://linux-hardware.org/?probe=6231dbe6d4) | Feb 08, 2023 |
| Dell          | Latitude E6330              | Notebook    | [291e0fd64f](https://linux-hardware.org/?probe=291e0fd64f) | Feb 08, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [965758f3ea](https://linux-hardware.org/?probe=965758f3ea) | Feb 08, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [e521c55b1a](https://linux-hardware.org/?probe=e521c55b1a) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [cc897fe72d](https://linux-hardware.org/?probe=cc897fe72d) | Feb 08, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | Notebook    | [9f6079baf2](https://linux-hardware.org/?probe=9f6079baf2) | Feb 08, 2023 |
| Intel         | DH67CL AAG10212-208         | Desktop     | [e53a89d83d](https://linux-hardware.org/?probe=e53a89d83d) | Feb 08, 2023 |
| TYAN Compu... | S4985                       | Server      | [40ea5a6601](https://linux-hardware.org/?probe=40ea5a6601) | Feb 08, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [f5aeb173ba](https://linux-hardware.org/?probe=f5aeb173ba) | Feb 08, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3245fc2fec](https://linux-hardware.org/?probe=3245fc2fec) | Feb 08, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [8fb3a20b27](https://linux-hardware.org/?probe=8fb3a20b27) | Feb 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [def4679f84](https://linux-hardware.org/?probe=def4679f84) | Feb 07, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | Notebook    | [db2f72084a](https://linux-hardware.org/?probe=db2f72084a) | Feb 07, 2023 |
| Panasonic     | CF-54-1                     | Notebook    | [32a2acc07e](https://linux-hardware.org/?probe=32a2acc07e) | Feb 07, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | Desktop     | [69f96bffa5](https://linux-hardware.org/?probe=69f96bffa5) | Feb 07, 2023 |
| Samsung       | R530/R730                   | Notebook    | [f212e58647](https://linux-hardware.org/?probe=f212e58647) | Feb 07, 2023 |
| Samsung       | R530/R730                   | Notebook    | [9ccb976ccd](https://linux-hardware.org/?probe=9ccb976ccd) | Feb 07, 2023 |
| Dell          | Latitude E7250              | Notebook    | [b4a7701aa4](https://linux-hardware.org/?probe=b4a7701aa4) | Feb 07, 2023 |
| Dell          | Precision 5570              | Notebook    | [d279e97c00](https://linux-hardware.org/?probe=d279e97c00) | Feb 07, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7e020b928e](https://linux-hardware.org/?probe=7e020b928e) | Feb 07, 2023 |
| Inspur        | Shuyu                       | Server      | [37c2630b8f](https://linux-hardware.org/?probe=37c2630b8f) | Feb 07, 2023 |
| Toshiba       | Satellite C655              | Notebook    | [a0c2eb7db1](https://linux-hardware.org/?probe=a0c2eb7db1) | Feb 07, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [83380dcad6](https://linux-hardware.org/?probe=83380dcad6) | Feb 07, 2023 |
| Dell          | 08DM12 A00                  | Server      | [4fcfb3fb2a](https://linux-hardware.org/?probe=4fcfb3fb2a) | Feb 07, 2023 |
| Intel         | NUC5CPYB H61145-402         | Mini pc     | [9cb000ed27](https://linux-hardware.org/?probe=9cb000ed27) | Feb 06, 2023 |
| HP            | 3397                        | Desktop     | [2fb7638874](https://linux-hardware.org/?probe=2fb7638874) | Feb 06, 2023 |
| Google        | Terra                       | Notebook    | [edfe00266c](https://linux-hardware.org/?probe=edfe00266c) | Feb 06, 2023 |
| SLIMBOOK      | Essential15L                | Notebook    | [e2af97d5d3](https://linux-hardware.org/?probe=e2af97d5d3) | Feb 06, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [b3169f788f](https://linux-hardware.org/?probe=b3169f788f) | Feb 06, 2023 |
| ASUSTek       | X71Q                        | Notebook    | [c89b078e8f](https://linux-hardware.org/?probe=c89b078e8f) | Feb 06, 2023 |
| Aquarius      | NS585                       | Notebook    | [e9deef3f9e](https://linux-hardware.org/?probe=e9deef3f9e) | Feb 06, 2023 |
| AZW           | U59                         | Desktop     | [b97c4f6277](https://linux-hardware.org/?probe=b97c4f6277) | Feb 06, 2023 |
| Lenovo        | ThinkPad X250 20CLS2TQ22    | Notebook    | [112a65a03e](https://linux-hardware.org/?probe=112a65a03e) | Feb 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2891f201f0](https://linux-hardware.org/?probe=2891f201f0) | Feb 06, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [db292bc714](https://linux-hardware.org/?probe=db292bc714) | Feb 05, 2023 |
| HP            | 0A64h                       | Desktop     | [40ef639345](https://linux-hardware.org/?probe=40ef639345) | Feb 05, 2023 |
| Huanan        | X99-T8D V1.2                | Desktop     | [cb7e750cee](https://linux-hardware.org/?probe=cb7e750cee) | Feb 05, 2023 |
| Gigabyte      | H61MA-D2V                   | Desktop     | [b708cdc12f](https://linux-hardware.org/?probe=b708cdc12f) | Feb 05, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [c3891f43b5](https://linux-hardware.org/?probe=c3891f43b5) | Feb 05, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [413341361a](https://linux-hardware.org/?probe=413341361a) | Feb 05, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [b2247eafed](https://linux-hardware.org/?probe=b2247eafed) | Feb 05, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [6023defc83](https://linux-hardware.org/?probe=6023defc83) | Feb 05, 2023 |
| Intel         | S5500HCV E40912-458         | Server      | [1445c60562](https://linux-hardware.org/?probe=1445c60562) | Feb 05, 2023 |
| Intel         | S5500HCV E40912-458         | Server      | [95ff55d958](https://linux-hardware.org/?probe=95ff55d958) | Feb 05, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [2f56f41681](https://linux-hardware.org/?probe=2f56f41681) | Feb 05, 2023 |
| Google        | Ampton                      | Notebook    | [74d5b6aa4d](https://linux-hardware.org/?probe=74d5b6aa4d) | Feb 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [5a491991ef](https://linux-hardware.org/?probe=5a491991ef) | Feb 05, 2023 |
| Google        | Ampton                      | Notebook    | [2785bde3f9](https://linux-hardware.org/?probe=2785bde3f9) | Feb 05, 2023 |
| HP            | 255 G3                      | Notebook    | [dfa2e96880](https://linux-hardware.org/?probe=dfa2e96880) | Feb 05, 2023 |
| MSI           | A320M PRO-M2                | Desktop     | [3fa2ac81f2](https://linux-hardware.org/?probe=3fa2ac81f2) | Feb 05, 2023 |
| Dell          | 0D4MD1 A00                  | Desktop     | [7198c3d131](https://linux-hardware.org/?probe=7198c3d131) | Feb 05, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [e0a93d257b](https://linux-hardware.org/?probe=e0a93d257b) | Feb 05, 2023 |
| OEM           | Intel H81                   | Desktop     | [806280459d](https://linux-hardware.org/?probe=806280459d) | Feb 05, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [f2423d1d75](https://linux-hardware.org/?probe=f2423d1d75) | Feb 05, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [29d133e858](https://linux-hardware.org/?probe=29d133e858) | Feb 05, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [2543adebba](https://linux-hardware.org/?probe=2543adebba) | Feb 05, 2023 |
| Acer          | Aspire E1-772               | Notebook    | [147ad71a27](https://linux-hardware.org/?probe=147ad71a27) | Feb 05, 2023 |
| Notebook      | W65_67SJ                    | Notebook    | [870af12011](https://linux-hardware.org/?probe=870af12011) | Feb 05, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [229050fbe5](https://linux-hardware.org/?probe=229050fbe5) | Feb 05, 2023 |
| ASUSTek       | F5SL                        | Notebook    | [1e5bb7661e](https://linux-hardware.org/?probe=1e5bb7661e) | Feb 04, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a3cab7679b](https://linux-hardware.org/?probe=a3cab7679b) | Feb 04, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [885ad2ae95](https://linux-hardware.org/?probe=885ad2ae95) | Feb 04, 2023 |
| HP            | 1589                        | Desktop     | [7b3a0cf51b](https://linux-hardware.org/?probe=7b3a0cf51b) | Feb 04, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [4ed27fe851](https://linux-hardware.org/?probe=4ed27fe851) | Feb 04, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [018b3728ea](https://linux-hardware.org/?probe=018b3728ea) | Feb 04, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [52bb20e0b2](https://linux-hardware.org/?probe=52bb20e0b2) | Feb 04, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [0185beaec6](https://linux-hardware.org/?probe=0185beaec6) | Feb 04, 2023 |
| Toshiba       | Satellite P775              | Notebook    | [df8aa8c06a](https://linux-hardware.org/?probe=df8aa8c06a) | Feb 04, 2023 |
| ECS           | A780GM-A                    | Desktop     | [6f6599f880](https://linux-hardware.org/?probe=6f6599f880) | Feb 04, 2023 |
| Lenovo        | ThinkPad T440p 20ANS09W0... | Notebook    | [17f9df8f2c](https://linux-hardware.org/?probe=17f9df8f2c) | Feb 03, 2023 |
| HP            | 3048h                       | Desktop     | [03b28af2be](https://linux-hardware.org/?probe=03b28af2be) | Feb 03, 2023 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [4b85a254bc](https://linux-hardware.org/?probe=4b85a254bc) | Feb 03, 2023 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [142d89a9c0](https://linux-hardware.org/?probe=142d89a9c0) | Feb 03, 2023 |
| AZW           | MINI S                      | Desktop     | [6c746a5f95](https://linux-hardware.org/?probe=6c746a5f95) | Feb 03, 2023 |
| Lenovo        | V310-15IKB 80T3             | Notebook    | [a39fb673c7](https://linux-hardware.org/?probe=a39fb673c7) | Feb 03, 2023 |
| HP            | Pavilion 15                 | Notebook    | [5909dd08e7](https://linux-hardware.org/?probe=5909dd08e7) | Feb 03, 2023 |
| Intel         | AB2L .A004                  | Mini pc     | [568740a6b1](https://linux-hardware.org/?probe=568740a6b1) | Feb 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [c0c511ec65](https://linux-hardware.org/?probe=c0c511ec65) | Feb 03, 2023 |
| Aquarius      | NS585                       | Notebook    | [7e944d88b3](https://linux-hardware.org/?probe=7e944d88b3) | Feb 03, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d0d8e49083](https://linux-hardware.org/?probe=d0d8e49083) | Feb 03, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [ae290fa64e](https://linux-hardware.org/?probe=ae290fa64e) | Feb 03, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [7820377760](https://linux-hardware.org/?probe=7820377760) | Feb 03, 2023 |
| Xunlong       | Orange Pi Zero              | Soc         | [3af57a322f](https://linux-hardware.org/?probe=3af57a322f) | Feb 03, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [534cdba357](https://linux-hardware.org/?probe=534cdba357) | Feb 03, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [656df2cea9](https://linux-hardware.org/?probe=656df2cea9) | Feb 03, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [6d39ef2792](https://linux-hardware.org/?probe=6d39ef2792) | Feb 03, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [c26be60545](https://linux-hardware.org/?probe=c26be60545) | Feb 03, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [2f2c8adb0c](https://linux-hardware.org/?probe=2f2c8adb0c) | Feb 02, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [6d7a27b213](https://linux-hardware.org/?probe=6d7a27b213) | Feb 02, 2023 |
| Google        | Babymega                    | Notebook    | [2a8b81c6f4](https://linux-hardware.org/?probe=2a8b81c6f4) | Feb 02, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3483138f98](https://linux-hardware.org/?probe=3483138f98) | Feb 02, 2023 |
| Intel         | SKYBAY                      | Desktop     | [a75cb78ad9](https://linux-hardware.org/?probe=a75cb78ad9) | Feb 02, 2023 |
| Dell          | Vostro 3580                 | Notebook    | [7efc294bac](https://linux-hardware.org/?probe=7efc294bac) | Feb 02, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [9bb5fabf0b](https://linux-hardware.org/?probe=9bb5fabf0b) | Feb 02, 2023 |
| Lenovo        | ThinkPad E495 20NE001GMX    | Notebook    | [29660bbd04](https://linux-hardware.org/?probe=29660bbd04) | Feb 02, 2023 |
| Dell          | Latitude 7480               | Notebook    | [8a7e0b16d5](https://linux-hardware.org/?probe=8a7e0b16d5) | Feb 02, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [2de08972b9](https://linux-hardware.org/?probe=2de08972b9) | Feb 02, 2023 |
| NEC Comput... | MS9666 011                  | Desktop     | [26a38770fe](https://linux-hardware.org/?probe=26a38770fe) | Feb 02, 2023 |
| Dell          | Latitude E6520              | Notebook    | [548b13cd43](https://linux-hardware.org/?probe=548b13cd43) | Feb 02, 2023 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [9deaff7467](https://linux-hardware.org/?probe=9deaff7467) | Feb 02, 2023 |
| Lenovo        | ThinkPad 13 20J10046US      | Notebook    | [85b9d54087](https://linux-hardware.org/?probe=85b9d54087) | Feb 02, 2023 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [2cb0ec3b98](https://linux-hardware.org/?probe=2cb0ec3b98) | Feb 01, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [b8c8ed32e5](https://linux-hardware.org/?probe=b8c8ed32e5) | Feb 01, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [203e3fe693](https://linux-hardware.org/?probe=203e3fe693) | Feb 01, 2023 |
| Samsung       | 600B4B/600B5B               | Notebook    | [d3cf4446d5](https://linux-hardware.org/?probe=d3cf4446d5) | Feb 01, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [352c998936](https://linux-hardware.org/?probe=352c998936) | Feb 01, 2023 |
| Toshiba       | Satellite P775              | Notebook    | [c03f7668ac](https://linux-hardware.org/?probe=c03f7668ac) | Feb 01, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | Notebook    | [ac78478b3b](https://linux-hardware.org/?probe=ac78478b3b) | Feb 01, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [2f0a18ba6b](https://linux-hardware.org/?probe=2f0a18ba6b) | Feb 01, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [01e8662b39](https://linux-hardware.org/?probe=01e8662b39) | Feb 01, 2023 |
| Gigabyte      | X299 AORUS Gaming 3-CF      | Desktop     | [775a993b3a](https://linux-hardware.org/?probe=775a993b3a) | Feb 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [f2b211ff3a](https://linux-hardware.org/?probe=f2b211ff3a) | Feb 01, 2023 |
| Gigabyte      | Z690M DS3H DDR4             | Desktop     | [8f858cb9b9](https://linux-hardware.org/?probe=8f858cb9b9) | Jan 31, 2023 |
| MSI           | 870A-G54                    | Desktop     | [0aaa012de5](https://linux-hardware.org/?probe=0aaa012de5) | Jan 31, 2023 |
| HP            | Notebook                    | Notebook    | [3cea0a0519](https://linux-hardware.org/?probe=3cea0a0519) | Jan 31, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [daa9bd48c8](https://linux-hardware.org/?probe=daa9bd48c8) | Jan 31, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [7e25d19fae](https://linux-hardware.org/?probe=7e25d19fae) | Jan 31, 2023 |
| ASRock        | G31M-VS2                    | Desktop     | [e12dd528ea](https://linux-hardware.org/?probe=e12dd528ea) | Jan 31, 2023 |
| MSI           | H81M-E34                    | Desktop     | [19b8f90522](https://linux-hardware.org/?probe=19b8f90522) | Jan 31, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [d8f44aeb4c](https://linux-hardware.org/?probe=d8f44aeb4c) | Jan 31, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [35948f3b5e](https://linux-hardware.org/?probe=35948f3b5e) | Jan 31, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [011c3940f9](https://linux-hardware.org/?probe=011c3940f9) | Jan 31, 2023 |
| Dell          | Inspiron 5485 2n1           | Convertible | [e335e7282d](https://linux-hardware.org/?probe=e335e7282d) | Jan 30, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [3f17be7a85](https://linux-hardware.org/?probe=3f17be7a85) | Jan 30, 2023 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [b6a73bd22e](https://linux-hardware.org/?probe=b6a73bd22e) | Jan 30, 2023 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [0ae96c2bbc](https://linux-hardware.org/?probe=0ae96c2bbc) | Jan 30, 2023 |
| NetGear       | ReadyDATA 5200              | Desktop     | [74a68eba33](https://linux-hardware.org/?probe=74a68eba33) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | Desktop     | [f13f4da766](https://linux-hardware.org/?probe=f13f4da766) | Jan 30, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [79e7fde988](https://linux-hardware.org/?probe=79e7fde988) | Jan 30, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d86a1c4fb2](https://linux-hardware.org/?probe=d86a1c4fb2) | Jan 30, 2023 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [a7ef98ea02](https://linux-hardware.org/?probe=a7ef98ea02) | Jan 30, 2023 |
| HP            | 0A64h                       | Desktop     | [da7b36ad47](https://linux-hardware.org/?probe=da7b36ad47) | Jan 30, 2023 |
| Acer          | Aspire 5552                 | Notebook    | [f1168775a7](https://linux-hardware.org/?probe=f1168775a7) | Jan 30, 2023 |
| Sony          | PCG-Z1VA(UC)                | Notebook    | [db4f48132e](https://linux-hardware.org/?probe=db4f48132e) | Jan 29, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [d6faeebd74](https://linux-hardware.org/?probe=d6faeebd74) | Jan 29, 2023 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [55c3e9597c](https://linux-hardware.org/?probe=55c3e9597c) | Jan 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [933e5a5b96](https://linux-hardware.org/?probe=933e5a5b96) | Jan 29, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [6b634c85e8](https://linux-hardware.org/?probe=6b634c85e8) | Jan 29, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [c6163491b5](https://linux-hardware.org/?probe=c6163491b5) | Jan 29, 2023 |
| Medion        | TJ4125                      | Desktop     | [5fb5d01ae9](https://linux-hardware.org/?probe=5fb5d01ae9) | Jan 29, 2023 |
| Gigabyte      | 8IPE1000-G/L                | Desktop     | [6f83e8b57d](https://linux-hardware.org/?probe=6f83e8b57d) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | Notebook    | [7017fcf775](https://linux-hardware.org/?probe=7017fcf775) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | Notebook    | [9afa780018](https://linux-hardware.org/?probe=9afa780018) | Jan 29, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [e91c24c3f9](https://linux-hardware.org/?probe=e91c24c3f9) | Jan 29, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [351106d7e5](https://linux-hardware.org/?probe=351106d7e5) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 42915CG       | Notebook    | [d058eeaad5](https://linux-hardware.org/?probe=d058eeaad5) | Jan 29, 2023 |
| Gigabyte      | M61PME-S2                   | Desktop     | [8227150e0d](https://linux-hardware.org/?probe=8227150e0d) | Jan 29, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [03171e1e33](https://linux-hardware.org/?probe=03171e1e33) | Jan 29, 2023 |
| Gigabyte      | M61PME-S2                   | Desktop     | [813f01976d](https://linux-hardware.org/?probe=813f01976d) | Jan 29, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [eaed78d213](https://linux-hardware.org/?probe=eaed78d213) | Jan 28, 2023 |
| Dell          | 0F8098                      | Desktop     | [d6066c739e](https://linux-hardware.org/?probe=d6066c739e) | Jan 28, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [a1b5cdf1db](https://linux-hardware.org/?probe=a1b5cdf1db) | Jan 28, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [5fa28ba14d](https://linux-hardware.org/?probe=5fa28ba14d) | Jan 28, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a88e343a83](https://linux-hardware.org/?probe=a88e343a83) | Jan 28, 2023 |
| Dell          | 05MW5F A00                  | Mini pc     | [dd56d67fef](https://linux-hardware.org/?probe=dd56d67fef) | Jan 28, 2023 |
| ASUSTek       | UX410UAR                    | Notebook    | [e9ac16c8ef](https://linux-hardware.org/?probe=e9ac16c8ef) | Jan 28, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [8c8db10ac2](https://linux-hardware.org/?probe=8c8db10ac2) | Jan 28, 2023 |
| HP            | ProBook 430 G6              | Notebook    | [24fd7df5b6](https://linux-hardware.org/?probe=24fd7df5b6) | Jan 28, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [bbdf827cef](https://linux-hardware.org/?probe=bbdf827cef) | Jan 27, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [0b05244a15](https://linux-hardware.org/?probe=0b05244a15) | Jan 27, 2023 |
| Dell          | Latitude E7440              | Notebook    | [9ba078f6ab](https://linux-hardware.org/?probe=9ba078f6ab) | Jan 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [c83903fdc8](https://linux-hardware.org/?probe=c83903fdc8) | Jan 27, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [376c580dcb](https://linux-hardware.org/?probe=376c580dcb) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | Notebook    | [d3adeb692c](https://linux-hardware.org/?probe=d3adeb692c) | Jan 27, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [4a83dc2dc2](https://linux-hardware.org/?probe=4a83dc2dc2) | Jan 27, 2023 |
| MSI           | B365M PRO-VDH               | Desktop     | [d5bbfc18d5](https://linux-hardware.org/?probe=d5bbfc18d5) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | Notebook    | [46b1227255](https://linux-hardware.org/?probe=46b1227255) | Jan 27, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [e01e49f162](https://linux-hardware.org/?probe=e01e49f162) | Jan 27, 2023 |
| MSI           | Creator 17 B11UE            | Notebook    | [fcf56cfe4d](https://linux-hardware.org/?probe=fcf56cfe4d) | Jan 27, 2023 |
| Dell          | Latitude 5420               | Notebook    | [379a2dc9ab](https://linux-hardware.org/?probe=379a2dc9ab) | Jan 26, 2023 |
| Dell          | Latitude 5420               | Notebook    | [eec8ef8ddb](https://linux-hardware.org/?probe=eec8ef8ddb) | Jan 26, 2023 |
| Google        | Careena                     | Notebook    | [75ca1a25dd](https://linux-hardware.org/?probe=75ca1a25dd) | Jan 26, 2023 |
| AZW           | MINI S                      | Desktop     | [ce5e6b1504](https://linux-hardware.org/?probe=ce5e6b1504) | Jan 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [d632bd0c9f](https://linux-hardware.org/?probe=d632bd0c9f) | Jan 26, 2023 |
| HP            | 805D                        | Desktop     | [b1996094a9](https://linux-hardware.org/?probe=b1996094a9) | Jan 26, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [2e70086887](https://linux-hardware.org/?probe=2e70086887) | Jan 25, 2023 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [dee0143024](https://linux-hardware.org/?probe=dee0143024) | Jan 25, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [4643f751cf](https://linux-hardware.org/?probe=4643f751cf) | Jan 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [3b96eac8a9](https://linux-hardware.org/?probe=3b96eac8a9) | Jan 25, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [90d383c54e](https://linux-hardware.org/?probe=90d383c54e) | Jan 25, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [e4b50b33a2](https://linux-hardware.org/?probe=e4b50b33a2) | Jan 25, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [e0eefbde94](https://linux-hardware.org/?probe=e0eefbde94) | Jan 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e2d354b9c5](https://linux-hardware.org/?probe=e2d354b9c5) | Jan 25, 2023 |
| Panasonic     | FZ55-2                      | Notebook    | [dd9ddb12b6](https://linux-hardware.org/?probe=dd9ddb12b6) | Jan 25, 2023 |
| Lenovo        | ThinkPad X220 4291IR6       | Notebook    | [cc41fa5174](https://linux-hardware.org/?probe=cc41fa5174) | Jan 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [8780aceeec](https://linux-hardware.org/?probe=8780aceeec) | Jan 25, 2023 |
| Samsung       | R710                        | Notebook    | [17a3e2ddd9](https://linux-hardware.org/?probe=17a3e2ddd9) | Jan 25, 2023 |
| Dell          | 0K3CM7 A00                  | Desktop     | [d3cc219bf7](https://linux-hardware.org/?probe=d3cc219bf7) | Jan 24, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [0bde1ca99a](https://linux-hardware.org/?probe=0bde1ca99a) | Jan 24, 2023 |
| MSI           | H97 PC Mate                 | Desktop     | [d00ec3c042](https://linux-hardware.org/?probe=d00ec3c042) | Jan 24, 2023 |
| Packard Be... | EasyNote MH36               | Notebook    | [07ba548a55](https://linux-hardware.org/?probe=07ba548a55) | Jan 24, 2023 |
| BESSTAR Te... | Cherry Trail CR             | Mini pc     | [9ac0bac56e](https://linux-hardware.org/?probe=9ac0bac56e) | Jan 24, 2023 |
| ECS           | G31T-M9                     | Desktop     | [59747c81ca](https://linux-hardware.org/?probe=59747c81ca) | Jan 24, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [fe1a2d7fc6](https://linux-hardware.org/?probe=fe1a2d7fc6) | Jan 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [fd6d2ec3c2](https://linux-hardware.org/?probe=fd6d2ec3c2) | Jan 23, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [c8ec385a88](https://linux-hardware.org/?probe=c8ec385a88) | Jan 23, 2023 |
| ASRock        | 990FX Killer                | Desktop     | [b6bd3a3bdb](https://linux-hardware.org/?probe=b6bd3a3bdb) | Jan 23, 2023 |
| MSI           | 870A-G54                    | Desktop     | [b1baf04990](https://linux-hardware.org/?probe=b1baf04990) | Jan 23, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [5648fbf4a0](https://linux-hardware.org/?probe=5648fbf4a0) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [62ac206f7e](https://linux-hardware.org/?probe=62ac206f7e) | Jan 23, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [3f3b6c888d](https://linux-hardware.org/?probe=3f3b6c888d) | Jan 23, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [69164f2a61](https://linux-hardware.org/?probe=69164f2a61) | Jan 23, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e7f0c7e0be](https://linux-hardware.org/?probe=e7f0c7e0be) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [5c7625e3f8](https://linux-hardware.org/?probe=5c7625e3f8) | Jan 23, 2023 |
| Supermicro    | X9DRD-iF                    | Server      | [c088868f62](https://linux-hardware.org/?probe=c088868f62) | Jan 22, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [ff727a3560](https://linux-hardware.org/?probe=ff727a3560) | Jan 22, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [df0676ac87](https://linux-hardware.org/?probe=df0676ac87) | Jan 22, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4687e8d062](https://linux-hardware.org/?probe=4687e8d062) | Jan 22, 2023 |
| Intel         | JSL MRD                     | Desktop     | [39dc5a7f96](https://linux-hardware.org/?probe=39dc5a7f96) | Jan 22, 2023 |
| Lenovo        | ThinkCentre M57e 7066W57    | Desktop     | [3ddcdbb616](https://linux-hardware.org/?probe=3ddcdbb616) | Jan 22, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e7afed6351](https://linux-hardware.org/?probe=e7afed6351) | Jan 22, 2023 |
| Dell          | G3 3579                     | Notebook    | [63298dcee9](https://linux-hardware.org/?probe=63298dcee9) | Jan 22, 2023 |
| Danew         | Dbook 131                   | Notebook    | [08911c133e](https://linux-hardware.org/?probe=08911c133e) | Jan 22, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [ef532b60e6](https://linux-hardware.org/?probe=ef532b60e6) | Jan 21, 2023 |
| Clevo         | W150ER                      | Notebook    | [ba5d06437c](https://linux-hardware.org/?probe=ba5d06437c) | Jan 21, 2023 |
| Biostar       | H310MHP                     | Desktop     | [21de314a44](https://linux-hardware.org/?probe=21de314a44) | Jan 21, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [c9d6e1cbb1](https://linux-hardware.org/?probe=c9d6e1cbb1) | Jan 21, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e7f94d5172](https://linux-hardware.org/?probe=e7f94d5172) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [046504c970](https://linux-hardware.org/?probe=046504c970) | Jan 21, 2023 |
| DFI           | CR101-CST                   | Desktop     | [604ce5b10f](https://linux-hardware.org/?probe=604ce5b10f) | Jan 21, 2023 |
| Google        | Phaser                      | Notebook    | [557e69c5f1](https://linux-hardware.org/?probe=557e69c5f1) | Jan 21, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [82b95a8f4e](https://linux-hardware.org/?probe=82b95a8f4e) | Jan 21, 2023 |
| Dell          | 00TD00 A00                  | All in one  | [8d09088848](https://linux-hardware.org/?probe=8d09088848) | Jan 21, 2023 |
| HP            | EliteBook Folio 9480m       | Notebook    | [cf1b67c224](https://linux-hardware.org/?probe=cf1b67c224) | Jan 21, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [06f6499264](https://linux-hardware.org/?probe=06f6499264) | Jan 21, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [9f700f7e19](https://linux-hardware.org/?probe=9f700f7e19) | Jan 21, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [4af2ea2f7f](https://linux-hardware.org/?probe=4af2ea2f7f) | Jan 20, 2023 |
| Dell          | 0VC8RJ X02                  | Desktop     | [313ea92e9c](https://linux-hardware.org/?probe=313ea92e9c) | Jan 20, 2023 |
| Gigabyte      | H410M H V2                  | Desktop     | [5767b63675](https://linux-hardware.org/?probe=5767b63675) | Jan 20, 2023 |
| Dell          | Latitude 5501               | Notebook    | [d31f972a20](https://linux-hardware.org/?probe=d31f972a20) | Jan 20, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [c591d80181](https://linux-hardware.org/?probe=c591d80181) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [28e6aeb27a](https://linux-hardware.org/?probe=28e6aeb27a) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [beec5d3864](https://linux-hardware.org/?probe=beec5d3864) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [6ff84d12be](https://linux-hardware.org/?probe=6ff84d12be) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [002a38370c](https://linux-hardware.org/?probe=002a38370c) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [bbfb85788c](https://linux-hardware.org/?probe=bbfb85788c) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [9d6c73b1c1](https://linux-hardware.org/?probe=9d6c73b1c1) | Jan 20, 2023 |
| HP            | 3397                        | Desktop     | [39391f23c4](https://linux-hardware.org/?probe=39391f23c4) | Jan 20, 2023 |
| HP            | 3397                        | Desktop     | [7b05c1fdf9](https://linux-hardware.org/?probe=7b05c1fdf9) | Jan 20, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [b2c0017481](https://linux-hardware.org/?probe=b2c0017481) | Jan 20, 2023 |
| AZW           | SEi                         | Desktop     | [257b104c3a](https://linux-hardware.org/?probe=257b104c3a) | Jan 20, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d77bf1f32b](https://linux-hardware.org/?probe=d77bf1f32b) | Jan 20, 2023 |
| Gigabyte      | Z690I A ULTRA LITE D4       | Desktop     | [f7cac38f4a](https://linux-hardware.org/?probe=f7cac38f4a) | Jan 20, 2023 |
| AZW           | SEi                         | Desktop     | [481932390b](https://linux-hardware.org/?probe=481932390b) | Jan 20, 2023 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [b9f1f115ba](https://linux-hardware.org/?probe=b9f1f115ba) | Jan 20, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3447d19b00](https://linux-hardware.org/?probe=3447d19b00) | Jan 20, 2023 |
| UMAX          | VisionBook 12Wr             | Notebook    | [0707d617f7](https://linux-hardware.org/?probe=0707d617f7) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490s 20NYS3SX0... | Notebook    | [3e08ab25c6](https://linux-hardware.org/?probe=3e08ab25c6) | Jan 20, 2023 |
| Gigabyte      | Z690I A ULTRA LITE D4       | Desktop     | [abcfca9ea7](https://linux-hardware.org/?probe=abcfca9ea7) | Jan 20, 2023 |
| Lenovo        | 7033EW4                     | Desktop     | [fd4303de2e](https://linux-hardware.org/?probe=fd4303de2e) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [80cb1c8239](https://linux-hardware.org/?probe=80cb1c8239) | Jan 19, 2023 |
| Lenovo        | ThinkPad E470 20H1004SMX    | Notebook    | [0d8528f0d2](https://linux-hardware.org/?probe=0d8528f0d2) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0efa802a32](https://linux-hardware.org/?probe=0efa802a32) | Jan 19, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [606ba17221](https://linux-hardware.org/?probe=606ba17221) | Jan 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [76be7bde5d](https://linux-hardware.org/?probe=76be7bde5d) | Jan 19, 2023 |
| ASUSTek       | P6T                         | Desktop     | [ac42d5a147](https://linux-hardware.org/?probe=ac42d5a147) | Jan 19, 2023 |
| Gigabyte      | B85M-D3V                    | Desktop     | [285dc35475](https://linux-hardware.org/?probe=285dc35475) | Jan 19, 2023 |
| Insyde        | Braswell                    | Notebook    | [18526fdbe2](https://linux-hardware.org/?probe=18526fdbe2) | Jan 19, 2023 |
| ASUSTek       | P5AD2-E-Premium             | Desktop     | [285c0f23f1](https://linux-hardware.org/?probe=285c0f23f1) | Jan 19, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [20749dc72f](https://linux-hardware.org/?probe=20749dc72f) | Jan 19, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [db998abdae](https://linux-hardware.org/?probe=db998abdae) | Jan 19, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [18d521cc55](https://linux-hardware.org/?probe=18d521cc55) | Jan 19, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b6ab71a056](https://linux-hardware.org/?probe=b6ab71a056) | Jan 19, 2023 |
| HP            | 894F                        | Mini pc     | [a671f44480](https://linux-hardware.org/?probe=a671f44480) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [368ed9c856](https://linux-hardware.org/?probe=368ed9c856) | Jan 18, 2023 |
| ASUSTek       | P8H61-M                     | Desktop     | [1ffe9344ff](https://linux-hardware.org/?probe=1ffe9344ff) | Jan 18, 2023 |
| Novatech      | NL40_50CU                   | Notebook    | [395dab7c43](https://linux-hardware.org/?probe=395dab7c43) | Jan 18, 2023 |
| HP            | Compaq 6910p                | Notebook    | [61d820a040](https://linux-hardware.org/?probe=61d820a040) | Jan 18, 2023 |
| Medion        | TJ4125                      | Desktop     | [b4f48c3140](https://linux-hardware.org/?probe=b4f48c3140) | Jan 18, 2023 |
| Lenovo        | 7033EW4                     | Desktop     | [df0d8cd728](https://linux-hardware.org/?probe=df0d8cd728) | Jan 18, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [7b62e27d7a](https://linux-hardware.org/?probe=7b62e27d7a) | Jan 18, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | Notebook    | [393e6cd6d2](https://linux-hardware.org/?probe=393e6cd6d2) | Jan 18, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [84479cfc00](https://linux-hardware.org/?probe=84479cfc00) | Jan 18, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [430b938694](https://linux-hardware.org/?probe=430b938694) | Jan 18, 2023 |
| HP            | EliteBook 2170p             | Notebook    | [46705d578e](https://linux-hardware.org/?probe=46705d578e) | Jan 18, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [952c81c314](https://linux-hardware.org/?probe=952c81c314) | Jan 18, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [e0431daa9c](https://linux-hardware.org/?probe=e0431daa9c) | Jan 18, 2023 |
| Dell          | Latitude 5500               | Notebook    | [e0ae9cb026](https://linux-hardware.org/?probe=e0ae9cb026) | Jan 17, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [4d726dcf9b](https://linux-hardware.org/?probe=4d726dcf9b) | Jan 17, 2023 |
| Huanan        | B75 V10.1 376               | Desktop     | [2703c87348](https://linux-hardware.org/?probe=2703c87348) | Jan 17, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | Notebook    | [99e10e5d0f](https://linux-hardware.org/?probe=99e10e5d0f) | Jan 17, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | Notebook    | [624f47d1e3](https://linux-hardware.org/?probe=624f47d1e3) | Jan 17, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [f9f926e910](https://linux-hardware.org/?probe=f9f926e910) | Jan 17, 2023 |
| MSI           | H81M-E34                    | Desktop     | [db4a6791a0](https://linux-hardware.org/?probe=db4a6791a0) | Jan 17, 2023 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [31b369770d](https://linux-hardware.org/?probe=31b369770d) | Jan 17, 2023 |
| Foxconn       | nT-A3000 series FAB         | Desktop     | [0bdefb0a4f](https://linux-hardware.org/?probe=0bdefb0a4f) | Jan 17, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a35e962cca](https://linux-hardware.org/?probe=a35e962cca) | Jan 17, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7688ac4ec1](https://linux-hardware.org/?probe=7688ac4ec1) | Jan 17, 2023 |
| HP            | Compaq 6730b (GW687AV)      | Notebook    | [e967b291d5](https://linux-hardware.org/?probe=e967b291d5) | Jan 17, 2023 |
| Dell          | Inspiron 5502               | Notebook    | [43c4f532aa](https://linux-hardware.org/?probe=43c4f532aa) | Jan 17, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [a279a876f3](https://linux-hardware.org/?probe=a279a876f3) | Jan 17, 2023 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [d31aea19b2](https://linux-hardware.org/?probe=d31aea19b2) | Jan 16, 2023 |
| Intel         | DH67BL AAG10189-206         | Desktop     | [23e07704eb](https://linux-hardware.org/?probe=23e07704eb) | Jan 16, 2023 |
| Positivo      | CHT14B                      | Notebook    | [ab4518f121](https://linux-hardware.org/?probe=ab4518f121) | Jan 16, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [020e19b05d](https://linux-hardware.org/?probe=020e19b05d) | Jan 16, 2023 |
| Lenovo        | ThinkPad T490s 20NX0076M... | Notebook    | [4c896e2c0e](https://linux-hardware.org/?probe=4c896e2c0e) | Jan 16, 2023 |
| ASRock        | J3455-ITX                   | Desktop     | [6746dfae39](https://linux-hardware.org/?probe=6746dfae39) | Jan 16, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [976f23d99e](https://linux-hardware.org/?probe=976f23d99e) | Jan 16, 2023 |
| Radxa         | ROCK 5B                     | Soc         | [e187058616](https://linux-hardware.org/?probe=e187058616) | Jan 16, 2023 |
| Dell          | Inspiron 5502               | Notebook    | [9403074843](https://linux-hardware.org/?probe=9403074843) | Jan 16, 2023 |
| Intel         | JSL MRD                     | Desktop     | [edbaf7bb5d](https://linux-hardware.org/?probe=edbaf7bb5d) | Jan 16, 2023 |
| Lenovo        | 370A SDK0J40697 WIN 3305... | Desktop     | [deb2b560bc](https://linux-hardware.org/?probe=deb2b560bc) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [47d090108d](https://linux-hardware.org/?probe=47d090108d) | Jan 16, 2023 |
| ASRock        | J3455-ITX                   | Desktop     | [457c7ea5a4](https://linux-hardware.org/?probe=457c7ea5a4) | Jan 16, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [cb3c4b1eb4](https://linux-hardware.org/?probe=cb3c4b1eb4) | Jan 16, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [4572999070](https://linux-hardware.org/?probe=4572999070) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [219091b4e0](https://linux-hardware.org/?probe=219091b4e0) | Jan 15, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [3b4a530695](https://linux-hardware.org/?probe=3b4a530695) | Jan 15, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [f316bddcf2](https://linux-hardware.org/?probe=f316bddcf2) | Jan 15, 2023 |
| Acer          | Swift SF314-510G            | Notebook    | [b929f53536](https://linux-hardware.org/?probe=b929f53536) | Jan 15, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [5426686264](https://linux-hardware.org/?probe=5426686264) | Jan 15, 2023 |
| MSI           | MS-B1711                    | Desktop     | [730b1e7f90](https://linux-hardware.org/?probe=730b1e7f90) | Jan 15, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [0ec206a07d](https://linux-hardware.org/?probe=0ec206a07d) | Jan 15, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [53eb92efda](https://linux-hardware.org/?probe=53eb92efda) | Jan 15, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [202535bce7](https://linux-hardware.org/?probe=202535bce7) | Jan 15, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [ab5933911d](https://linux-hardware.org/?probe=ab5933911d) | Jan 15, 2023 |
| Lenovo        | ThinkPad T470 20HES0MV00    | Notebook    | [7e3b019181](https://linux-hardware.org/?probe=7e3b019181) | Jan 14, 2023 |
| HP            | Pavilion g6                 | Notebook    | [7d44980bca](https://linux-hardware.org/?probe=7d44980bca) | Jan 14, 2023 |
| Lenovo        | ThinkPad W520 4284W2U       | Notebook    | [576a509224](https://linux-hardware.org/?probe=576a509224) | Jan 14, 2023 |
| Dell          | 00TD00 A00                  | All in one  | [d63c9ca908](https://linux-hardware.org/?probe=d63c9ca908) | Jan 14, 2023 |
| Dell          | 00TD00 A00                  | All in one  | [80db2b0301](https://linux-hardware.org/?probe=80db2b0301) | Jan 14, 2023 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [6efb68b8da](https://linux-hardware.org/?probe=6efb68b8da) | Jan 14, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [0899d995dd](https://linux-hardware.org/?probe=0899d995dd) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [d1e2f08907](https://linux-hardware.org/?probe=d1e2f08907) | Jan 14, 2023 |
| Radxa         | ROCK Pi 4B                  | Soc         | [0533348a3f](https://linux-hardware.org/?probe=0533348a3f) | Jan 14, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [f862a7e702](https://linux-hardware.org/?probe=f862a7e702) | Jan 14, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [df889b6674](https://linux-hardware.org/?probe=df889b6674) | Jan 14, 2023 |
| HP            | Pavilion g6                 | Notebook    | [7672e1178a](https://linux-hardware.org/?probe=7672e1178a) | Jan 14, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [8a79dd9e27](https://linux-hardware.org/?probe=8a79dd9e27) | Jan 13, 2023 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [bed628ce8a](https://linux-hardware.org/?probe=bed628ce8a) | Jan 13, 2023 |
| Lenovo        | ThinkCentre M58p 6234A1U    | Desktop     | [63d74a9021](https://linux-hardware.org/?probe=63d74a9021) | Jan 13, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [ed62a9383e](https://linux-hardware.org/?probe=ed62a9383e) | Jan 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [ce69bfd81b](https://linux-hardware.org/?probe=ce69bfd81b) | Jan 13, 2023 |
| Medion        | TJ4125                      | Desktop     | [700f862aa6](https://linux-hardware.org/?probe=700f862aa6) | Jan 13, 2023 |
| HC            | HCAR357-MI V1.0             | Desktop     | [516f1ed052](https://linux-hardware.org/?probe=516f1ed052) | Jan 13, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [810b866ee4](https://linux-hardware.org/?probe=810b866ee4) | Jan 13, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [baf20b6914](https://linux-hardware.org/?probe=baf20b6914) | Jan 13, 2023 |
| Vestel        | 14MB24A                     | Desktop     | [56ee8713e8](https://linux-hardware.org/?probe=56ee8713e8) | Jan 13, 2023 |
| Vestel        | 14MB24A                     | Desktop     | [02c99c8c38](https://linux-hardware.org/?probe=02c99c8c38) | Jan 13, 2023 |
| ASUSTek       | Q325UA                      | Convertible | [1862534df3](https://linux-hardware.org/?probe=1862534df3) | Jan 13, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [efeae454c8](https://linux-hardware.org/?probe=efeae454c8) | Jan 13, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [07a70b62af](https://linux-hardware.org/?probe=07a70b62af) | Jan 13, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [d7c612580f](https://linux-hardware.org/?probe=d7c612580f) | Jan 13, 2023 |
| ASUSTek       | X450LD                      | Notebook    | [859eb05149](https://linux-hardware.org/?probe=859eb05149) | Jan 13, 2023 |
| Chuwi         | UBook Pro                   | Tablet      | [b756ec6728](https://linux-hardware.org/?probe=b756ec6728) | Jan 12, 2023 |
| HP            | 21EF                        | Desktop     | [0d5e3a9354](https://linux-hardware.org/?probe=0d5e3a9354) | Jan 12, 2023 |
| HP            | 21EF                        | Desktop     | [cdeab03273](https://linux-hardware.org/?probe=cdeab03273) | Jan 12, 2023 |
| HP            | Compaq 6735b                | Notebook    | [01878ee027](https://linux-hardware.org/?probe=01878ee027) | Jan 12, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [694d5be301](https://linux-hardware.org/?probe=694d5be301) | Jan 12, 2023 |
| ASUSTek       | P5G41T-M LX V2              | Desktop     | [36a8e226c5](https://linux-hardware.org/?probe=36a8e226c5) | Jan 12, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [4687ae7d43](https://linux-hardware.org/?probe=4687ae7d43) | Jan 12, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [bb85f0bdc7](https://linux-hardware.org/?probe=bb85f0bdc7) | Jan 12, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [d4691b9969](https://linux-hardware.org/?probe=d4691b9969) | Jan 12, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [2316d5dc8b](https://linux-hardware.org/?probe=2316d5dc8b) | Jan 12, 2023 |
| Lenovo        | ThinkPad T470p 20J7S1JT0... | Notebook    | [856d91c1ca](https://linux-hardware.org/?probe=856d91c1ca) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d93218978e](https://linux-hardware.org/?probe=d93218978e) | Jan 12, 2023 |
| MSI           | B350 PC MATE                | Desktop     | [f235ff785b](https://linux-hardware.org/?probe=f235ff785b) | Jan 12, 2023 |
| Dell          | 0KM5PX A06                  | Server      | [63b5c2f7fb](https://linux-hardware.org/?probe=63b5c2f7fb) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [25bd789598](https://linux-hardware.org/?probe=25bd789598) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [c040acffcf](https://linux-hardware.org/?probe=c040acffcf) | Jan 12, 2023 |
| Dell          | Precision M4400             | Notebook    | [27da7825fb](https://linux-hardware.org/?probe=27da7825fb) | Jan 12, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [055d61383e](https://linux-hardware.org/?probe=055d61383e) | Jan 12, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [ba153350d8](https://linux-hardware.org/?probe=ba153350d8) | Jan 11, 2023 |
| ASRock        | X300-ITX                    | Desktop     | [9e74676ba4](https://linux-hardware.org/?probe=9e74676ba4) | Jan 11, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [b60a38ae60](https://linux-hardware.org/?probe=b60a38ae60) | Jan 11, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [204a5e8a8e](https://linux-hardware.org/?probe=204a5e8a8e) | Jan 11, 2023 |
| Acer          | Swift SF314-56              | Notebook    | [46aebbe972](https://linux-hardware.org/?probe=46aebbe972) | Jan 11, 2023 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [ee2147214c](https://linux-hardware.org/?probe=ee2147214c) | Jan 11, 2023 |
| SLIMBOOK      | PRO                         | Notebook    | [551a4bd378](https://linux-hardware.org/?probe=551a4bd378) | Jan 11, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [6c67fc3995](https://linux-hardware.org/?probe=6c67fc3995) | Jan 11, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [54793acf7e](https://linux-hardware.org/?probe=54793acf7e) | Jan 11, 2023 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [18ca1dbf8f](https://linux-hardware.org/?probe=18ca1dbf8f) | Jan 10, 2023 |
| Aquarius      | NS585                       | Notebook    | [6fbcdf4d2f](https://linux-hardware.org/?probe=6fbcdf4d2f) | Jan 10, 2023 |
| HP            | Mini 110-1000               | Notebook    | [05c4656700](https://linux-hardware.org/?probe=05c4656700) | Jan 10, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [81a8002b99](https://linux-hardware.org/?probe=81a8002b99) | Jan 10, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [8367c27d81](https://linux-hardware.org/?probe=8367c27d81) | Jan 10, 2023 |
| HP            | 15                          | Notebook    | [f6b287dae1](https://linux-hardware.org/?probe=f6b287dae1) | Jan 10, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [8ea20821c8](https://linux-hardware.org/?probe=8ea20821c8) | Jan 10, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | Notebook    | [8d0b4a504d](https://linux-hardware.org/?probe=8d0b4a504d) | Jan 09, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [dea6736468](https://linux-hardware.org/?probe=dea6736468) | Jan 09, 2023 |
| Lenovo        | 1059 SDK0T76538 WIN 3556... | Desktop     | [a2660dcbfb](https://linux-hardware.org/?probe=a2660dcbfb) | Jan 09, 2023 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [d665a7f0ff](https://linux-hardware.org/?probe=d665a7f0ff) | Jan 09, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [e336a260d6](https://linux-hardware.org/?probe=e336a260d6) | Jan 09, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [43cc06ef1d](https://linux-hardware.org/?probe=43cc06ef1d) | Jan 09, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [395c417f92](https://linux-hardware.org/?probe=395c417f92) | Jan 09, 2023 |
| Intel         | NUC11ATBC4 M53051-303       | Mini pc     | [fcc9b4bbcc](https://linux-hardware.org/?probe=fcc9b4bbcc) | Jan 09, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [0e51eb7caa](https://linux-hardware.org/?probe=0e51eb7caa) | Jan 09, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [a14e62fdf8](https://linux-hardware.org/?probe=a14e62fdf8) | Jan 09, 2023 |
| Acer          | Predator G3-710             | Desktop     | [d47ca88192](https://linux-hardware.org/?probe=d47ca88192) | Jan 09, 2023 |
| HP            | 8053                        | Desktop     | [b377deb121](https://linux-hardware.org/?probe=b377deb121) | Jan 09, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [92205d303f](https://linux-hardware.org/?probe=92205d303f) | Jan 08, 2023 |
| Acer          | Aspire one 1-131            | Notebook    | [06c3411258](https://linux-hardware.org/?probe=06c3411258) | Jan 08, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [648dcae4c6](https://linux-hardware.org/?probe=648dcae4c6) | Jan 08, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [76c7287e2e](https://linux-hardware.org/?probe=76c7287e2e) | Jan 08, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [2b8206db29](https://linux-hardware.org/?probe=2b8206db29) | Jan 08, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [68fe02a04c](https://linux-hardware.org/?probe=68fe02a04c) | Jan 08, 2023 |
| ASUSTek       | K53U                        | Notebook    | [63849b1b5a](https://linux-hardware.org/?probe=63849b1b5a) | Jan 08, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [a4e777ea7d](https://linux-hardware.org/?probe=a4e777ea7d) | Jan 08, 2023 |
| Hardkernel    | Odroid XU4                  | Soc         | [2188a4a04e](https://linux-hardware.org/?probe=2188a4a04e) | Jan 07, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [84fc096e00](https://linux-hardware.org/?probe=84fc096e00) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [0f0b86d738](https://linux-hardware.org/?probe=0f0b86d738) | Jan 07, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [9119962d1f](https://linux-hardware.org/?probe=9119962d1f) | Jan 07, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [d6a4584809](https://linux-hardware.org/?probe=d6a4584809) | Jan 07, 2023 |
| ASRock        | Q1900-ITX                   | Desktop     | [ac7df499e8](https://linux-hardware.org/?probe=ac7df499e8) | Jan 07, 2023 |
| Dell          | Latitude 2110               | Notebook    | [9910f8985b](https://linux-hardware.org/?probe=9910f8985b) | Jan 07, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [dcca84c5eb](https://linux-hardware.org/?probe=dcca84c5eb) | Jan 07, 2023 |
| Hardkernel    | Odroid XU4                  | Soc         | [5c688c4595](https://linux-hardware.org/?probe=5c688c4595) | Jan 06, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [9776545fc4](https://linux-hardware.org/?probe=9776545fc4) | Jan 06, 2023 |
| Toshiba       | Satellite C55Dt-A           | Notebook    | [f3cfb5dbb5](https://linux-hardware.org/?probe=f3cfb5dbb5) | Jan 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [9b0a8d487e](https://linux-hardware.org/?probe=9b0a8d487e) | Jan 06, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [4ceeb719c2](https://linux-hardware.org/?probe=4ceeb719c2) | Jan 06, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [d930da3de0](https://linux-hardware.org/?probe=d930da3de0) | Jan 06, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [a456485950](https://linux-hardware.org/?probe=a456485950) | Jan 06, 2023 |
| &#er &&       | Aspire 5100                 | Notebook    | [26da9e8ee1](https://linux-hardware.org/?probe=26da9e8ee1) | Jan 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b329d8f40f](https://linux-hardware.org/?probe=b329d8f40f) | Jan 06, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [1edff66d1a](https://linux-hardware.org/?probe=1edff66d1a) | Jan 06, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [999663daee](https://linux-hardware.org/?probe=999663daee) | Jan 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [982de9c98d](https://linux-hardware.org/?probe=982de9c98d) | Jan 06, 2023 |
| Google        | Stout                       | Notebook    | [5ef816b9a6](https://linux-hardware.org/?probe=5ef816b9a6) | Jan 05, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [3245d27cb7](https://linux-hardware.org/?probe=3245d27cb7) | Jan 05, 2023 |
| HP            | EliteBook 840 Aero G8 No... | Notebook    | [b9f4ca82d2](https://linux-hardware.org/?probe=b9f4ca82d2) | Jan 05, 2023 |
| Acer          | Extensa 2540                | Notebook    | [4442f2c14a](https://linux-hardware.org/?probe=4442f2c14a) | Jan 05, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a84ac79f2b](https://linux-hardware.org/?probe=a84ac79f2b) | Jan 05, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6ea90d7af5](https://linux-hardware.org/?probe=6ea90d7af5) | Jan 05, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [bb487db79f](https://linux-hardware.org/?probe=bb487db79f) | Jan 05, 2023 |
| Acer          | Extensa 2540                | Notebook    | [ec8b49d7b0](https://linux-hardware.org/?probe=ec8b49d7b0) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [0042419ccb](https://linux-hardware.org/?probe=0042419ccb) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [82e42c0d42](https://linux-hardware.org/?probe=82e42c0d42) | Jan 04, 2023 |
| ELSKY         | M219FN-6C                   | Desktop     | [95862529f8](https://linux-hardware.org/?probe=95862529f8) | Jan 04, 2023 |
| Lenovo        | ThinkPad T430s 2356BQ5      | Notebook    | [fdf6545b20](https://linux-hardware.org/?probe=fdf6545b20) | Jan 04, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [420373dca1](https://linux-hardware.org/?probe=420373dca1) | Jan 04, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [01edd482a1](https://linux-hardware.org/?probe=01edd482a1) | Jan 04, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Desktop     | [b1771ee07c](https://linux-hardware.org/?probe=b1771ee07c) | Jan 03, 2023 |
| MSI           | MS-7519                     | Desktop     | [3239304aa0](https://linux-hardware.org/?probe=3239304aa0) | Jan 03, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [b876c5797a](https://linux-hardware.org/?probe=b876c5797a) | Jan 03, 2023 |
| Pegatron      | Maureen                     | Desktop     | [071cde04e9](https://linux-hardware.org/?probe=071cde04e9) | Jan 03, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [258412ac0a](https://linux-hardware.org/?probe=258412ac0a) | Jan 03, 2023 |
| ASUSTek       | F5SL                        | Notebook    | [67882c0f69](https://linux-hardware.org/?probe=67882c0f69) | Jan 02, 2023 |
| ASUSTek       | F5SL                        | Notebook    | [42ef1fbf40](https://linux-hardware.org/?probe=42ef1fbf40) | Jan 02, 2023 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [4a37b87ecf](https://linux-hardware.org/?probe=4a37b87ecf) | Jan 02, 2023 |
| Acer          | Aspire ES1-711              | Notebook    | [735e062168](https://linux-hardware.org/?probe=735e062168) | Jan 02, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [90603e4ab3](https://linux-hardware.org/?probe=90603e4ab3) | Jan 02, 2023 |
| MSI           | GE75 Raider 8SG             | Notebook    | [b6fa9be350](https://linux-hardware.org/?probe=b6fa9be350) | Jan 02, 2023 |
| Lenovo        | 31A7 SDK0J40697 WIN 3305... | Mini pc     | [efa2748c95](https://linux-hardware.org/?probe=efa2748c95) | Jan 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [b54f3aab7b](https://linux-hardware.org/?probe=b54f3aab7b) | Jan 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0D    | Notebook    | [a1f966e5e8](https://linux-hardware.org/?probe=a1f966e5e8) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [08fb8de608](https://linux-hardware.org/?probe=08fb8de608) | Jan 02, 2023 |
| Lenovo        | ThinkPad T430u 33519LC      | Notebook    | [87af3fa7f0](https://linux-hardware.org/?probe=87af3fa7f0) | Jan 02, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [2c33e446d4](https://linux-hardware.org/?probe=2c33e446d4) | Jan 02, 2023 |
| Lenovo        | ThinkPad X260 20F5005NAU    | Notebook    | [3f68b8438c](https://linux-hardware.org/?probe=3f68b8438c) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [bca75efbe5](https://linux-hardware.org/?probe=bca75efbe5) | Jan 02, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [2396307897](https://linux-hardware.org/?probe=2396307897) | Jan 02, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [13df46e700](https://linux-hardware.org/?probe=13df46e700) | Jan 02, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [7c72451666](https://linux-hardware.org/?probe=7c72451666) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | Notebook    | [f9db70d551](https://linux-hardware.org/?probe=f9db70d551) | Jan 01, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [8726e38f02](https://linux-hardware.org/?probe=8726e38f02) | Jan 01, 2023 |
| Lenovo        | G565 20071                  | Notebook    | [e974b446ae](https://linux-hardware.org/?probe=e974b446ae) | Jan 01, 2023 |
| Panasonic     | CF-54-2                     | Notebook    | [dfe3d2e06b](https://linux-hardware.org/?probe=dfe3d2e06b) | Jan 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [073d682146](https://linux-hardware.org/?probe=073d682146) | Jan 01, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [d88df3fcee](https://linux-hardware.org/?probe=d88df3fcee) | Jan 01, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [7474151c7e](https://linux-hardware.org/?probe=7474151c7e) | Jan 01, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [9eadf42d31](https://linux-hardware.org/?probe=9eadf42d31) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [b1dc879a16](https://linux-hardware.org/?probe=b1dc879a16) | Jan 01, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [de65f4b654](https://linux-hardware.org/?probe=de65f4b654) | Dec 31, 2022 |
| Google        | Teemo                       | Desktop     | [6f6671a40e](https://linux-hardware.org/?probe=6f6671a40e) | Dec 31, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [500ce7ae28](https://linux-hardware.org/?probe=500ce7ae28) | Dec 31, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [8d33275e7b](https://linux-hardware.org/?probe=8d33275e7b) | Dec 31, 2022 |
| Google        | Teemo                       | Desktop     | [e3c39f29da](https://linux-hardware.org/?probe=e3c39f29da) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [fb22f9430c](https://linux-hardware.org/?probe=fb22f9430c) | Dec 31, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [3710331d81](https://linux-hardware.org/?probe=3710331d81) | Dec 31, 2022 |
| Lenovo        | IdeaPad Y560                | Notebook    | [c9d3a1d0a3](https://linux-hardware.org/?probe=c9d3a1d0a3) | Dec 31, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [5775c77a91](https://linux-hardware.org/?probe=5775c77a91) | Dec 31, 2022 |
| HP            | Compaq 6710b (KE207ES#AB... | Notebook    | [d7d0be3872](https://linux-hardware.org/?probe=d7d0be3872) | Dec 30, 2022 |
| ASRock        | J3455-ITX                   | Desktop     | [4f45d532ac](https://linux-hardware.org/?probe=4f45d532ac) | Dec 30, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [c8a80649d2](https://linux-hardware.org/?probe=c8a80649d2) | Dec 30, 2022 |
| Supermicro    | X11SRA-RF                   | Server      | [2887a82948](https://linux-hardware.org/?probe=2887a82948) | Dec 30, 2022 |
| Supermicro    | X11SRA-RF                   | Server      | [e5f0b1d802](https://linux-hardware.org/?probe=e5f0b1d802) | Dec 30, 2022 |
| Supermicro    | X11SRA-RF                   | Server      | [cd84ddc342](https://linux-hardware.org/?probe=cd84ddc342) | Dec 30, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | Desktop     | [7b55955e2a](https://linux-hardware.org/?probe=7b55955e2a) | Dec 30, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [a295f18c9f](https://linux-hardware.org/?probe=a295f18c9f) | Dec 30, 2022 |
| HP            | 255 G3                      | Notebook    | [89d6bd459c](https://linux-hardware.org/?probe=89d6bd459c) | Dec 30, 2022 |
| HP            | 339A                        | Desktop     | [8e0b785427](https://linux-hardware.org/?probe=8e0b785427) | Dec 29, 2022 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [c38ca6386e](https://linux-hardware.org/?probe=c38ca6386e) | Dec 29, 2022 |
| Lenovo        | ThinkPad T470p 20J7S1JT0... | Notebook    | [4b7bbb186f](https://linux-hardware.org/?probe=4b7bbb186f) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | Notebook    | [5bf3ff5c0e](https://linux-hardware.org/?probe=5bf3ff5c0e) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | Notebook    | [4f63c4474c](https://linux-hardware.org/?probe=4f63c4474c) | Dec 29, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [50149bf9e3](https://linux-hardware.org/?probe=50149bf9e3) | Dec 29, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [b0a40a3ac0](https://linux-hardware.org/?probe=b0a40a3ac0) | Dec 29, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [716ba7f970](https://linux-hardware.org/?probe=716ba7f970) | Dec 29, 2022 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [6aad572cd5](https://linux-hardware.org/?probe=6aad572cd5) | Dec 29, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [af1655497e](https://linux-hardware.org/?probe=af1655497e) | Dec 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [34b6109940](https://linux-hardware.org/?probe=34b6109940) | Dec 29, 2022 |
| HP            | ProBook 6570b               | Notebook    | [46fd918b7c](https://linux-hardware.org/?probe=46fd918b7c) | Dec 29, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [4239e2fa3c](https://linux-hardware.org/?probe=4239e2fa3c) | Dec 29, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [7881f027ea](https://linux-hardware.org/?probe=7881f027ea) | Dec 29, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [c1e5e82fbb](https://linux-hardware.org/?probe=c1e5e82fbb) | Dec 29, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [457c2ae4ae](https://linux-hardware.org/?probe=457c2ae4ae) | Dec 28, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [fdfd0f21c7](https://linux-hardware.org/?probe=fdfd0f21c7) | Dec 28, 2022 |
| Toshiba       | Satellite L455D             | Notebook    | [35c085aa82](https://linux-hardware.org/?probe=35c085aa82) | Dec 28, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [27f58a8ad1](https://linux-hardware.org/?probe=27f58a8ad1) | Dec 28, 2022 |
| HP            | ProLiant ML30 Gen9          | Desktop     | [174e7e831b](https://linux-hardware.org/?probe=174e7e831b) | Dec 28, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [c29088a63f](https://linux-hardware.org/?probe=c29088a63f) | Dec 28, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [7c60cc0210](https://linux-hardware.org/?probe=7c60cc0210) | Dec 28, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [72f770277e](https://linux-hardware.org/?probe=72f770277e) | Dec 28, 2022 |
| HP            | ProBook 6470b               | Notebook    | [055705b3f2](https://linux-hardware.org/?probe=055705b3f2) | Dec 28, 2022 |
| HP            | 158A                        | Desktop     | [c80bfd7c30](https://linux-hardware.org/?probe=c80bfd7c30) | Dec 28, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [ec0ad4d293](https://linux-hardware.org/?probe=ec0ad4d293) | Dec 28, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [2ceb80faeb](https://linux-hardware.org/?probe=2ceb80faeb) | Dec 28, 2022 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [0f71bbaf67](https://linux-hardware.org/?probe=0f71bbaf67) | Dec 28, 2022 |
| ASUSTek       | A4110                       | All in one  | [fa417dc5c7](https://linux-hardware.org/?probe=fa417dc5c7) | Dec 28, 2022 |
| ASRock        | J3455-ITX                   | Desktop     | [6e628aeb01](https://linux-hardware.org/?probe=6e628aeb01) | Dec 28, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [10dce91da1](https://linux-hardware.org/?probe=10dce91da1) | Dec 27, 2022 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [48f161dfc8](https://linux-hardware.org/?probe=48f161dfc8) | Dec 27, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [d174ffb318](https://linux-hardware.org/?probe=d174ffb318) | Dec 27, 2022 |
| MSI           | GE62 2QC                    | Notebook    | [dbd69d70ac](https://linux-hardware.org/?probe=dbd69d70ac) | Dec 27, 2022 |
| Dell          | 0M017G A00                  | Desktop     | [5c41315695](https://linux-hardware.org/?probe=5c41315695) | Dec 27, 2022 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [042fb842d2](https://linux-hardware.org/?probe=042fb842d2) | Dec 27, 2022 |
| Panasonic     | FZ55-2                      | Notebook    | [1699b7c3b2](https://linux-hardware.org/?probe=1699b7c3b2) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [78c6c15502](https://linux-hardware.org/?probe=78c6c15502) | Dec 27, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [06cba3f478](https://linux-hardware.org/?probe=06cba3f478) | Dec 27, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [210f0c0375](https://linux-hardware.org/?probe=210f0c0375) | Dec 27, 2022 |
| ASRock        | Brazos                      | Desktop     | [f5183b395b](https://linux-hardware.org/?probe=f5183b395b) | Dec 27, 2022 |
| Notebook      | L14xMU                      | Notebook    | [7644bc65e2](https://linux-hardware.org/?probe=7644bc65e2) | Dec 27, 2022 |
| Dell          | Inspiron 1012               | Notebook    | [3dd6b8a416](https://linux-hardware.org/?probe=3dd6b8a416) | Dec 26, 2022 |
| Dell          | 02YRK5 A02                  | Desktop     | [56dc5ff1b9](https://linux-hardware.org/?probe=56dc5ff1b9) | Dec 26, 2022 |
| Exo           | Smart Serie M               | Notebook    | [942ee3b035](https://linux-hardware.org/?probe=942ee3b035) | Dec 26, 2022 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [3bb1c5cc47](https://linux-hardware.org/?probe=3bb1c5cc47) | Dec 26, 2022 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [2618b85414](https://linux-hardware.org/?probe=2618b85414) | Dec 26, 2022 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [6ad649ad46](https://linux-hardware.org/?probe=6ad649ad46) | Dec 26, 2022 |
| Gigabyte      | B360M H                     | Desktop     | [2f0d1b1c8d](https://linux-hardware.org/?probe=2f0d1b1c8d) | Dec 26, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d90a9cdcd3](https://linux-hardware.org/?probe=d90a9cdcd3) | Dec 26, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fc0eac877c](https://linux-hardware.org/?probe=fc0eac877c) | Dec 26, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [67fee9ab39](https://linux-hardware.org/?probe=67fee9ab39) | Dec 26, 2022 |
| Acer          | Aspire ES1-533              | Notebook    | [3b5fa6d85a](https://linux-hardware.org/?probe=3b5fa6d85a) | Dec 26, 2022 |
| Lenovo        | ThinkPad X250 20CLS1UB00    | Notebook    | [fc8b2899fa](https://linux-hardware.org/?probe=fc8b2899fa) | Dec 25, 2022 |
| SANTECH       | NHx0DB,DE                   | Notebook    | [a0996d42bd](https://linux-hardware.org/?probe=a0996d42bd) | Dec 25, 2022 |
| HP            | 470 G8 Notebook PC          | Notebook    | [6d77c48324](https://linux-hardware.org/?probe=6d77c48324) | Dec 25, 2022 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [6ac63aca4f](https://linux-hardware.org/?probe=6ac63aca4f) | Dec 25, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [b5eaa2b6aa](https://linux-hardware.org/?probe=b5eaa2b6aa) | Dec 25, 2022 |
| Unknown       | Unknown                     | Soc         | [95c95c980d](https://linux-hardware.org/?probe=95c95c980d) | Dec 25, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [5977afc830](https://linux-hardware.org/?probe=5977afc830) | Dec 25, 2022 |
| ASUSTek       | G751JT                      | Notebook    | [16e989ff99](https://linux-hardware.org/?probe=16e989ff99) | Dec 25, 2022 |
| Dell          | Latitude E6520              | Notebook    | [33a51c934d](https://linux-hardware.org/?probe=33a51c934d) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [ea09a6daa8](https://linux-hardware.org/?probe=ea09a6daa8) | Dec 25, 2022 |
| Dell          | 00TD00 A00                  | All in one  | [84beba0484](https://linux-hardware.org/?probe=84beba0484) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [45737153e4](https://linux-hardware.org/?probe=45737153e4) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [42221f61fb](https://linux-hardware.org/?probe=42221f61fb) | Dec 25, 2022 |
| Medion        | E122X                       | Notebook    | [6e4e34bcc3](https://linux-hardware.org/?probe=6e4e34bcc3) | Dec 24, 2022 |
| Medion        | E122X                       | Notebook    | [bf41c45a7d](https://linux-hardware.org/?probe=bf41c45a7d) | Dec 24, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [096d4fc8c2](https://linux-hardware.org/?probe=096d4fc8c2) | Dec 24, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [f7af4b1164](https://linux-hardware.org/?probe=f7af4b1164) | Dec 24, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [b95892f2dc](https://linux-hardware.org/?probe=b95892f2dc) | Dec 24, 2022 |
| ASUSTek       | WS C422 DC                  | Desktop     | [7be7c81575](https://linux-hardware.org/?probe=7be7c81575) | Dec 24, 2022 |
| Supermicro    | X11SRA-RF                   | Server      | [efdf519660](https://linux-hardware.org/?probe=efdf519660) | Dec 24, 2022 |
| ASUSTek       | WS C422 DC                  | Desktop     | [526414fd8f](https://linux-hardware.org/?probe=526414fd8f) | Dec 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [c5f2f2db53](https://linux-hardware.org/?probe=c5f2f2db53) | Dec 24, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [39f35288d4](https://linux-hardware.org/?probe=39f35288d4) | Dec 24, 2022 |
| Lenovo        | ThinkPad X270 20HMS16200    | Notebook    | [6ac6e552a8](https://linux-hardware.org/?probe=6ac6e552a8) | Dec 24, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [1c7e7f8dd2](https://linux-hardware.org/?probe=1c7e7f8dd2) | Dec 24, 2022 |
| Dell          | Latitude E7440              | Notebook    | [baae52327d](https://linux-hardware.org/?probe=baae52327d) | Dec 23, 2022 |
| Dell          | Latitude E7440              | Notebook    | [bc5d48b831](https://linux-hardware.org/?probe=bc5d48b831) | Dec 23, 2022 |
| Dell          | Latitude E7440              | Notebook    | [fde483d476](https://linux-hardware.org/?probe=fde483d476) | Dec 23, 2022 |
| HP            | 876C SMVB                   | Desktop     | [988b03aae5](https://linux-hardware.org/?probe=988b03aae5) | Dec 23, 2022 |
| Dell          | Latitude E7440              | Notebook    | [a746012ffd](https://linux-hardware.org/?probe=a746012ffd) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [9e5c4705fa](https://linux-hardware.org/?probe=9e5c4705fa) | Dec 23, 2022 |
| Dell          | Latitude D630               | Notebook    | [8175d003ce](https://linux-hardware.org/?probe=8175d003ce) | Dec 23, 2022 |
| Google        | Reks                        | Notebook    | [ecee690e6e](https://linux-hardware.org/?probe=ecee690e6e) | Dec 23, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [54d5cca493](https://linux-hardware.org/?probe=54d5cca493) | Dec 23, 2022 |
| Google        | Reks                        | Notebook    | [58b1b4cac1](https://linux-hardware.org/?probe=58b1b4cac1) | Dec 23, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [297651d437](https://linux-hardware.org/?probe=297651d437) | Dec 23, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [79b015dcea](https://linux-hardware.org/?probe=79b015dcea) | Dec 23, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [d5625e9592](https://linux-hardware.org/?probe=d5625e9592) | Dec 23, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [958ee9d145](https://linux-hardware.org/?probe=958ee9d145) | Dec 23, 2022 |
| Dell          | G3 3590                     | Notebook    | [d75d9e6663](https://linux-hardware.org/?probe=d75d9e6663) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | Notebook    | [5f75bb423d](https://linux-hardware.org/?probe=5f75bb423d) | Dec 23, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [3256c282db](https://linux-hardware.org/?probe=3256c282db) | Dec 23, 2022 |
| Lenovo        | ThinkBook 14s Yoga G2 IA... | Convertible | [3ea5c420b1](https://linux-hardware.org/?probe=3ea5c420b1) | Dec 23, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [5bedf1557b](https://linux-hardware.org/?probe=5bedf1557b) | Dec 23, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [1c424b5f55](https://linux-hardware.org/?probe=1c424b5f55) | Dec 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [f9c4fecaf4](https://linux-hardware.org/?probe=f9c4fecaf4) | Dec 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [3832db2827](https://linux-hardware.org/?probe=3832db2827) | Dec 23, 2022 |
| Toshiba       | Satellite C55Dt-A           | Notebook    | [67294324c5](https://linux-hardware.org/?probe=67294324c5) | Dec 22, 2022 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [7794581d04](https://linux-hardware.org/?probe=7794581d04) | Dec 22, 2022 |
| Dell          | Latitude E7440              | Notebook    | [c6d28912f0](https://linux-hardware.org/?probe=c6d28912f0) | Dec 22, 2022 |
| Dell          | Latitude E7440              | Notebook    | [1a14f26bd3](https://linux-hardware.org/?probe=1a14f26bd3) | Dec 22, 2022 |
| Dell          | Latitude E7440              | Notebook    | [db77bb7a3f](https://linux-hardware.org/?probe=db77bb7a3f) | Dec 22, 2022 |
| Dell          | Latitude E7440              | Notebook    | [d2278ed94d](https://linux-hardware.org/?probe=d2278ed94d) | Dec 22, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [09ba8ccf48](https://linux-hardware.org/?probe=09ba8ccf48) | Dec 22, 2022 |
| Dell          | Latitude E7440              | Notebook    | [f4e79df709](https://linux-hardware.org/?probe=f4e79df709) | Dec 22, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [2c3febf6fa](https://linux-hardware.org/?probe=2c3febf6fa) | Dec 22, 2022 |
| Dell          | Latitude E7440              | Notebook    | [cddffa9123](https://linux-hardware.org/?probe=cddffa9123) | Dec 22, 2022 |
| Dell          | Latitude E7440              | Notebook    | [5f911806c8](https://linux-hardware.org/?probe=5f911806c8) | Dec 22, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | Notebook    | [844f589d20](https://linux-hardware.org/?probe=844f589d20) | Dec 22, 2022 |
| Dell          | Latitude D630               | Notebook    | [e1106d8868](https://linux-hardware.org/?probe=e1106d8868) | Dec 22, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [3d90b10b72](https://linux-hardware.org/?probe=3d90b10b72) | Dec 22, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [b049c64ff7](https://linux-hardware.org/?probe=b049c64ff7) | Dec 22, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [3a87279be6](https://linux-hardware.org/?probe=3a87279be6) | Dec 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [5f132c928b](https://linux-hardware.org/?probe=5f132c928b) | Dec 22, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [ba82bee4c7](https://linux-hardware.org/?probe=ba82bee4c7) | Dec 22, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [a2a2f20ef4](https://linux-hardware.org/?probe=a2a2f20ef4) | Dec 22, 2022 |
| Dell          | G3 3590                     | Notebook    | [8038491eb0](https://linux-hardware.org/?probe=8038491eb0) | Dec 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fe4ef75450](https://linux-hardware.org/?probe=fe4ef75450) | Dec 21, 2022 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [16cae3015a](https://linux-hardware.org/?probe=16cae3015a) | Dec 21, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [b4e828bef3](https://linux-hardware.org/?probe=b4e828bef3) | Dec 21, 2022 |
| Dell          | Vostro 3583                 | Notebook    | [cf3c6eb18b](https://linux-hardware.org/?probe=cf3c6eb18b) | Dec 21, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [056d76bae8](https://linux-hardware.org/?probe=056d76bae8) | Dec 21, 2022 |
| Sony          | SVE1112M1EB                 | Notebook    | [74e100e63b](https://linux-hardware.org/?probe=74e100e63b) | Dec 21, 2022 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [6b202d6cc2](https://linux-hardware.org/?probe=6b202d6cc2) | Dec 21, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [9438c80c85](https://linux-hardware.org/?probe=9438c80c85) | Dec 21, 2022 |
| Dell          | 0020HJ A01                  | Server      | [e266254c60](https://linux-hardware.org/?probe=e266254c60) | Dec 21, 2022 |
| HP            | ProLiant DL360e Gen8        | Server      | [5477e8f714](https://linux-hardware.org/?probe=5477e8f714) | Dec 21, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [428c861575](https://linux-hardware.org/?probe=428c861575) | Dec 21, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [57182d09ed](https://linux-hardware.org/?probe=57182d09ed) | Dec 21, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [449e38a14d](https://linux-hardware.org/?probe=449e38a14d) | Dec 21, 2022 |
| Intel         | DQ77CP AAG67261-300         | Desktop     | [908f619aa7](https://linux-hardware.org/?probe=908f619aa7) | Dec 21, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [363c106fa2](https://linux-hardware.org/?probe=363c106fa2) | Dec 21, 2022 |
| Dell          | G3 3590                     | Notebook    | [8272655600](https://linux-hardware.org/?probe=8272655600) | Dec 21, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [ed29442d39](https://linux-hardware.org/?probe=ed29442d39) | Dec 21, 2022 |
| Supermicro    | X10DRH-iT                   | Server      | [1215ed7cbf](https://linux-hardware.org/?probe=1215ed7cbf) | Dec 21, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [3007d5dd93](https://linux-hardware.org/?probe=3007d5dd93) | Dec 21, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [c4719bd0ac](https://linux-hardware.org/?probe=c4719bd0ac) | Dec 21, 2022 |
| Unknown       | Unknown                     | Soc         | [764115860e](https://linux-hardware.org/?probe=764115860e) | Dec 21, 2022 |
| MSI           | MS-7318                     | Desktop     | [4622016059](https://linux-hardware.org/?probe=4622016059) | Dec 21, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [cd4fa20e66](https://linux-hardware.org/?probe=cd4fa20e66) | Dec 20, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [60b20a8efa](https://linux-hardware.org/?probe=60b20a8efa) | Dec 20, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [e676fe186f](https://linux-hardware.org/?probe=e676fe186f) | Dec 20, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a2c8bb966e](https://linux-hardware.org/?probe=a2c8bb966e) | Dec 20, 2022 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [3cee3ad865](https://linux-hardware.org/?probe=3cee3ad865) | Dec 20, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [1e53c20bdd](https://linux-hardware.org/?probe=1e53c20bdd) | Dec 20, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [68731f4d29](https://linux-hardware.org/?probe=68731f4d29) | Dec 20, 2022 |
| Dell          | 0MN1TX A00                  | Desktop     | [f2ae430663](https://linux-hardware.org/?probe=f2ae430663) | Dec 20, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [1dc546e14a](https://linux-hardware.org/?probe=1dc546e14a) | Dec 20, 2022 |
| Gigabyte      | P75-D3P                     | Desktop     | [ff2420e759](https://linux-hardware.org/?probe=ff2420e759) | Dec 19, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [2aeb8fd0cd](https://linux-hardware.org/?probe=2aeb8fd0cd) | Dec 19, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [a4c5e58eec](https://linux-hardware.org/?probe=a4c5e58eec) | Dec 19, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a79b17ea96](https://linux-hardware.org/?probe=a79b17ea96) | Dec 19, 2022 |
| ASRock        | N68-GS3 UCC                 | Desktop     | [19dad9b5b2](https://linux-hardware.org/?probe=19dad9b5b2) | Dec 19, 2022 |
| Gigabyte      | G41MT-ES2L                  | Desktop     | [d23b58b5da](https://linux-hardware.org/?probe=d23b58b5da) | Dec 19, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [30aec905c0](https://linux-hardware.org/?probe=30aec905c0) | Dec 19, 2022 |
| GIFA Indus... | TM-J3355-2G2L               | Desktop     | [526697a9d0](https://linux-hardware.org/?probe=526697a9d0) | Dec 19, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [493ddb6998](https://linux-hardware.org/?probe=493ddb6998) | Dec 19, 2022 |
| IceWhale T... | ZimaBoard 216 ZMB           | Desktop     | [647bf0e2a7](https://linux-hardware.org/?probe=647bf0e2a7) | Dec 19, 2022 |
| ASUSTek       | 900SD                       | Notebook    | [43d2c88062](https://linux-hardware.org/?probe=43d2c88062) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [956aaecbb9](https://linux-hardware.org/?probe=956aaecbb9) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [d5ceb48450](https://linux-hardware.org/?probe=d5ceb48450) | Dec 18, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [756263bf48](https://linux-hardware.org/?probe=756263bf48) | Dec 18, 2022 |
| EUROCOM       | SCORPIUS 3D                 | Notebook    | [4fdf299276](https://linux-hardware.org/?probe=4fdf299276) | Dec 18, 2022 |
| Dell          | 0UY894 A02                  | Desktop     | [904ee2bb12](https://linux-hardware.org/?probe=904ee2bb12) | Dec 18, 2022 |
| Dell          | 06JWJY A00                  | Desktop     | [89ac693c2c](https://linux-hardware.org/?probe=89ac693c2c) | Dec 18, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [78a6f49d22](https://linux-hardware.org/?probe=78a6f49d22) | Dec 18, 2022 |
| Dell          | Latitude E6530              | Notebook    | [198a9bc936](https://linux-hardware.org/?probe=198a9bc936) | Dec 18, 2022 |
| Lenovo        | ThinkPad T470 20HES3JR02    | Notebook    | [f9e4638f19](https://linux-hardware.org/?probe=f9e4638f19) | Dec 18, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [9e4f7a69c9](https://linux-hardware.org/?probe=9e4f7a69c9) | Dec 18, 2022 |
| Unknown       | Unknown                     | Soc         | [78a211835b](https://linux-hardware.org/?probe=78a211835b) | Dec 18, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [a80a6922d4](https://linux-hardware.org/?probe=a80a6922d4) | Dec 18, 2022 |
| Dell          | Latitude E4310              | Notebook    | [ace267f47c](https://linux-hardware.org/?probe=ace267f47c) | Dec 18, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [0886e650a3](https://linux-hardware.org/?probe=0886e650a3) | Dec 18, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [937a672cb0](https://linux-hardware.org/?probe=937a672cb0) | Dec 17, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [1ec932aa3a](https://linux-hardware.org/?probe=1ec932aa3a) | Dec 17, 2022 |
| ASUSTek       | P8H67-M                     | Desktop     | [cf6fc033d6](https://linux-hardware.org/?probe=cf6fc033d6) | Dec 17, 2022 |
| Intel         | NUC8BEB J72693-303          | Mini pc     | [b882d3e249](https://linux-hardware.org/?probe=b882d3e249) | Dec 17, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ed5d3570ef](https://linux-hardware.org/?probe=ed5d3570ef) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1e2531fdf1](https://linux-hardware.org/?probe=1e2531fdf1) | Dec 17, 2022 |
| Lenovo        | K14 Gen 1 21CUS02600        | Notebook    | [218654b079](https://linux-hardware.org/?probe=218654b079) | Dec 17, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [96ae6bc093](https://linux-hardware.org/?probe=96ae6bc093) | Dec 17, 2022 |
| HP            | Notebook                    | Notebook    | [844d855f78](https://linux-hardware.org/?probe=844d855f78) | Dec 17, 2022 |
| Unknown       | Unknown                     | Notebook    | [208016df07](https://linux-hardware.org/?probe=208016df07) | Dec 17, 2022 |
| Dell          | 0V8F20 A01                  | Desktop     | [d9e3649f12](https://linux-hardware.org/?probe=d9e3649f12) | Dec 16, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [abfa3437b3](https://linux-hardware.org/?probe=abfa3437b3) | Dec 16, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [7b3f9b5af0](https://linux-hardware.org/?probe=7b3f9b5af0) | Dec 16, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [f58cc5bcba](https://linux-hardware.org/?probe=f58cc5bcba) | Dec 16, 2022 |
| Dell          | Inspiron 7590               | Notebook    | [e8fb837cf5](https://linux-hardware.org/?probe=e8fb837cf5) | Dec 16, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [f43049fe6d](https://linux-hardware.org/?probe=f43049fe6d) | Dec 16, 2022 |
| HP            | 876C SMVB                   | Desktop     | [e214378eea](https://linux-hardware.org/?probe=e214378eea) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | Notebook    | [5cc0ff812b](https://linux-hardware.org/?probe=5cc0ff812b) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | Notebook    | [062a6ed428](https://linux-hardware.org/?probe=062a6ed428) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [db670caadd](https://linux-hardware.org/?probe=db670caadd) | Dec 16, 2022 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [3a524796f6](https://linux-hardware.org/?probe=3a524796f6) | Dec 16, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [4676cf2979](https://linux-hardware.org/?probe=4676cf2979) | Dec 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [138cbfa0ba](https://linux-hardware.org/?probe=138cbfa0ba) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [d5cf351351](https://linux-hardware.org/?probe=d5cf351351) | Dec 16, 2022 |
| MSI           | AM1I                        | Desktop     | [0ebd00e848](https://linux-hardware.org/?probe=0ebd00e848) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [e2056deb8a](https://linux-hardware.org/?probe=e2056deb8a) | Dec 16, 2022 |
| MSI           | AM1I                        | Desktop     | [97dfa5ebf8](https://linux-hardware.org/?probe=97dfa5ebf8) | Dec 16, 2022 |
| Intel         | powered classmate PC        | Notebook    | [e0401225a2](https://linux-hardware.org/?probe=e0401225a2) | Dec 15, 2022 |
| HP            | 829E                        | Mini pc     | [dccdfac601](https://linux-hardware.org/?probe=dccdfac601) | Dec 15, 2022 |
| HP            | 876C SMVB                   | Desktop     | [c704265799](https://linux-hardware.org/?probe=c704265799) | Dec 15, 2022 |
| HP            | 876C SMVB                   | Desktop     | [3a6fdcc184](https://linux-hardware.org/?probe=3a6fdcc184) | Dec 15, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [3c6c7c5eb5](https://linux-hardware.org/?probe=3c6c7c5eb5) | Dec 15, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [b184d02286](https://linux-hardware.org/?probe=b184d02286) | Dec 15, 2022 |
| Unknown       | T3 MRD                      | Notebook    | [909e1a1604](https://linux-hardware.org/?probe=909e1a1604) | Dec 15, 2022 |
| Google        | Cyan                        | Notebook    | [2b9f20b7da](https://linux-hardware.org/?probe=2b9f20b7da) | Dec 15, 2022 |
| Lenovo        | ThinkPad T430 2349I62       | Notebook    | [f7590c1a07](https://linux-hardware.org/?probe=f7590c1a07) | Dec 15, 2022 |
| Dell          | Latitude 3490               | Notebook    | [af008f69f1](https://linux-hardware.org/?probe=af008f69f1) | Dec 14, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [4651fa0db3](https://linux-hardware.org/?probe=4651fa0db3) | Dec 14, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [c0c4581310](https://linux-hardware.org/?probe=c0c4581310) | Dec 14, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [f19d464a26](https://linux-hardware.org/?probe=f19d464a26) | Dec 14, 2022 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [47c18717db](https://linux-hardware.org/?probe=47c18717db) | Dec 14, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [516d6f7f12](https://linux-hardware.org/?probe=516d6f7f12) | Dec 14, 2022 |
| Dell          | 0N185P A02                  | Desktop     | [32d47ba775](https://linux-hardware.org/?probe=32d47ba775) | Dec 14, 2022 |
| Dell          | 0N185P A02                  | Desktop     | [ee28e5efa8](https://linux-hardware.org/?probe=ee28e5efa8) | Dec 14, 2022 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [9e8ad3aefd](https://linux-hardware.org/?probe=9e8ad3aefd) | Dec 14, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [eadca468de](https://linux-hardware.org/?probe=eadca468de) | Dec 14, 2022 |
| Dell          | 0H8367                      | Desktop     | [7fff4bfffc](https://linux-hardware.org/?probe=7fff4bfffc) | Dec 14, 2022 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [bdbf3d8792](https://linux-hardware.org/?probe=bdbf3d8792) | Dec 14, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [049fef0294](https://linux-hardware.org/?probe=049fef0294) | Dec 14, 2022 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [88c6ca8956](https://linux-hardware.org/?probe=88c6ca8956) | Dec 14, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [2afff07992](https://linux-hardware.org/?probe=2afff07992) | Dec 14, 2022 |
| ASUSTek       | X302LA                      | Notebook    | [8404a0b0c6](https://linux-hardware.org/?probe=8404a0b0c6) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [14f87b8695](https://linux-hardware.org/?probe=14f87b8695) | Dec 13, 2022 |
| MSI           | MS-7318                     | Desktop     | [420ae8857b](https://linux-hardware.org/?probe=420ae8857b) | Dec 13, 2022 |
| Lenovo        | Aptio CRB SDK0E50510 WIN    | Mini pc     | [ce2a33caff](https://linux-hardware.org/?probe=ce2a33caff) | Dec 13, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [64176404e2](https://linux-hardware.org/?probe=64176404e2) | Dec 13, 2022 |
| Dell          | Latitude 5520               | Notebook    | [7e5d86eaaf](https://linux-hardware.org/?probe=7e5d86eaaf) | Dec 13, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [8d2a0ec4e4](https://linux-hardware.org/?probe=8d2a0ec4e4) | Dec 13, 2022 |
| Exo           | Smart Serie M               | Notebook    | [7fcf3d09bb](https://linux-hardware.org/?probe=7fcf3d09bb) | Dec 13, 2022 |
| MSI           | MS-B1591                    | Desktop     | [33cb107fb9](https://linux-hardware.org/?probe=33cb107fb9) | Dec 13, 2022 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [973e367765](https://linux-hardware.org/?probe=973e367765) | Dec 13, 2022 |
| NetGear       | ReadyDATA 5200              | Desktop     | [2db45cfb13](https://linux-hardware.org/?probe=2db45cfb13) | Dec 13, 2022 |
| Google        | Terra                       | Notebook    | [765deab389](https://linux-hardware.org/?probe=765deab389) | Dec 12, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [95dc27194a](https://linux-hardware.org/?probe=95dc27194a) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [dc916ac78c](https://linux-hardware.org/?probe=dc916ac78c) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [2bfcc16f6b](https://linux-hardware.org/?probe=2bfcc16f6b) | Dec 12, 2022 |
| Google        | Enguarde                    | Notebook    | [60cce42479](https://linux-hardware.org/?probe=60cce42479) | Dec 12, 2022 |
| Lenovo        | ThinkPad R61e 7650DHU       | Notebook    | [138f60e67c](https://linux-hardware.org/?probe=138f60e67c) | Dec 12, 2022 |
| Intel         | NUC6CAYB J23203-410         | Mini pc     | [e9c5ef16cd](https://linux-hardware.org/?probe=e9c5ef16cd) | Dec 12, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [99c965b83f](https://linux-hardware.org/?probe=99c965b83f) | Dec 12, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [22ce155034](https://linux-hardware.org/?probe=22ce155034) | Dec 12, 2022 |
| Dell          | Latitude 5411               | Notebook    | [af806502e8](https://linux-hardware.org/?probe=af806502e8) | Dec 12, 2022 |
| Acer          | Nitro AN515-51              | Notebook    | [918c340b04](https://linux-hardware.org/?probe=918c340b04) | Dec 12, 2022 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [3b9b8bb589](https://linux-hardware.org/?probe=3b9b8bb589) | Dec 12, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [d1b0bc1c03](https://linux-hardware.org/?probe=d1b0bc1c03) | Dec 12, 2022 |
| Lenovo        | ThinkPad T470 20HES6HC00    | Notebook    | [ca9d609d9d](https://linux-hardware.org/?probe=ca9d609d9d) | Dec 12, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_11/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.10.0-8-amd64         | 963       | 15.55%  |
| 5.10.0-7-amd64         | 691       | 11.16%  |
| 5.10.0-10-amd64        | 573       | 9.26%   |
| 5.10.0-16-amd64        | 370       | 5.98%   |
| 5.10.0-9-amd64         | 324       | 5.23%   |
| 5.10.0-19-amd64        | 286       | 4.62%   |
| 5.10.0-18-amd64        | 283       | 4.57%   |
| 5.10.0-13-amd64        | 261       | 4.22%   |
| 5.10.0-20-amd64        | 246       | 3.97%   |
| 5.10.0-11-amd64        | 193       | 3.12%   |
| 5.10.0-21-amd64        | 169       | 2.73%   |
| 5.10.0-2-amd64         | 147       | 2.37%   |
| 5.10.0-14-amd64        | 140       | 2.26%   |
| 5.10.0-17-amd64        | 125       | 2.02%   |
| 5.10.0-15-amd64        | 95        | 1.53%   |
| 5.10.0-12-amd64        | 73        | 1.18%   |
| 5.10.0-6-amd64         | 46        | 0.74%   |
| 5.18.0-0.deb11.4-amd64 | 38        | 0.61%   |
| 5.15.0-2-amd64         | 38        | 0.61%   |
| 5.16.0-0.bpo.4-amd64   | 32        | 0.52%   |
| 5.10.0-13-686-pae      | 30        | 0.48%   |
| 6.0.0-0.deb11.2-amd64  | 28        | 0.45%   |
| 5.18.0-0.bpo.1-amd64   | 25        | 0.4%    |
| 5.14.0-0.bpo.2-amd64   | 25        | 0.4%    |
| 5.13.19-6-pve          | 24        | 0.39%   |
| 5.19.0-0.deb11.2-amd64 | 22        | 0.36%   |
| 6.0.0-0.deb11.6-amd64  | 20        | 0.32%   |
| 5.15.74-1-pve          | 20        | 0.32%   |
| 5.10.0-8-arm64         | 18        | 0.29%   |
| 5.15.32-v8+            | 17        | 0.27%   |
| 5.19.0-2-amd64         | 16        | 0.26%   |
| 5.15.30-2-pve          | 16        | 0.26%   |
| 5.13.19-2-pve          | 16        | 0.26%   |
| 5.15.76-v8+            | 15        | 0.24%   |
| 5.10.0-3-amd64         | 15        | 0.24%   |
| 5.15.53-1-pve          | 14        | 0.23%   |
| 5.10.0-8-686-pae       | 14        | 0.23%   |
| 5.15.61-v8+            | 13        | 0.21%   |
| 5.15.35-1-pve          | 12        | 0.19%   |
| 5.10.92-v8+            | 12        | 0.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 4757      | 83.5%   |
| 5.18.0   | 92        | 1.61%   |
| 5.15.0   | 78        | 1.37%   |
| 5.16.0   | 62        | 1.09%   |
| 6.0.0    | 59        | 1.04%   |
| 5.13.19  | 58        | 1.02%   |
| 5.19.0   | 55        | 0.97%   |
| 5.14.0   | 42        | 0.74%   |
| 5.11.22  | 25        | 0.44%   |
| 5.17.0   | 24        | 0.42%   |
| 5.15.74  | 24        | 0.42%   |
| 5.15.39  | 18        | 0.32%   |
| 5.15.32  | 18        | 0.32%   |
| 5.15.35  | 17        | 0.3%    |
| 5.15.30  | 17        | 0.3%    |
| 5.15.76  | 15        | 0.26%   |
| 5.10.92  | 15        | 0.26%   |
| 5.15.53  | 14        | 0.25%   |
| 5.15.61  | 13        | 0.23%   |
| 5.15.84  | 11        | 0.19%   |
| 4.19.0   | 10        | 0.18%   |
| 6.1.0    | 9         | 0.16%   |
| 5.15.83  | 9         | 0.16%   |
| 5.13.0   | 7         | 0.12%   |
| 5.10.63  | 7         | 0.12%   |
| 5.15.85  | 6         | 0.11%   |
| 5.10.60  | 6         | 0.11%   |
| 5.10.109 | 5         | 0.09%   |
| 6.0.8    | 4         | 0.07%   |
| 5.19.17  | 4         | 0.07%   |
| 5.19.11  | 4         | 0.07%   |
| 5.16.5   | 4         | 0.07%   |
| 5.15.64  | 4         | 0.07%   |
| 5.15.60  | 4         | 0.07%   |
| 5.12.0   | 4         | 0.07%   |
| 5.11.0   | 4         | 0.07%   |
| 5.10.103 | 4         | 0.07%   |
| 5.10     | 4         | 0.07%   |
| 6.1.12   | 3         | 0.05%   |
| 5.9.0    | 3         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 4830      | 85.05%  |
| 5.15    | 279       | 4.91%   |
| 5.18    | 101       | 1.78%   |
| 5.13    | 77        | 1.36%   |
| 5.19    | 73        | 1.29%   |
| 5.16    | 69        | 1.22%   |
| 6.0     | 67        | 1.18%   |
| 5.14    | 49        | 0.86%   |
| 5.17    | 34        | 0.6%    |
| 5.11    | 34        | 0.6%    |
| 6.1     | 12        | 0.21%   |
| 4.19    | 12        | 0.21%   |
| 5.4     | 9         | 0.16%   |
| 5.12    | 9         | 0.16%   |
| 5       | 5         | 0.09%   |
| 5.9     | 3         | 0.05%   |
| 5.1     | 3         | 0.05%   |
| 4.4     | 3         | 0.05%   |
| 4.9     | 2         | 0.04%   |
| 3.18    | 2         | 0.04%   |
| 5.8     | 1         | 0.02%   |
| 5.5     | 1         | 0.02%   |
| 5.15.6  | 1         | 0.02%   |
| 4.14    | 1         | 0.02%   |
| 3.8     | 1         | 0.02%   |
| 3.10    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 5234      | 93.88%  |
| i686    | 167       | 3%      |
| aarch64 | 140       | 2.51%   |
| armv7l  | 28        | 0.5%    |
| riscv64 | 5         | 0.09%   |
| i586    | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 2190      | 38.71%  |
| GNOME             | 1232      | 21.77%  |
| KDE5              | 614       | 10.85%  |
| XFCE              | 609       | 10.76%  |
| MATE              | 197       | 3.48%   |
| LXDE              | 173       | 3.06%   |
| X-Cinnamon        | 163       | 2.88%   |
| Cinnamon          | 131       | 2.32%   |
| LXQt              | 69        | 1.22%   |
| i3                | 64        | 1.13%   |
| KDE               | 46        | 0.81%   |
| openbox           | 35        | 0.62%   |
| GNOME Flashback   | 34        | 0.6%    |
| lightdm-xsession  | 26        | 0.46%   |
| trinity           | 17        | 0.3%    |
| Budgie            | 10        | 0.18%   |
| GNOME Classic     | 9         | 0.16%   |
| sway              | 5         | 0.09%   |
| awesome           | 5         | 0.09%   |
| x-session-manager | 3         | 0.05%   |
| Enlightenment     | 3         | 0.05%   |
| DWM               | 3         | 0.05%   |
| Cutefish          | 3         | 0.05%   |
| icewm             | 2         | 0.04%   |
| xmonad            | 1         | 0.02%   |
| wmaker-common     | 1         | 0.02%   |
| UKUI              | 1         | 0.02%   |
| Phosh:GNOME       | 1         | 0.02%   |
| matchbox          | 1         | 0.02%   |
| jwm               | 1         | 0.02%   |
| GNUstep           | 1         | 0.02%   |
| gnome-xorg        | 1         | 0.02%   |
| fvwm              | 1         | 0.02%   |
| fluxbox           | 1         | 0.02%   |
| e16-session       | 1         | 0.02%   |
| default           | 1         | 0.02%   |
| Deepin            | 1         | 0.02%   |
| BunsenLabs        | 1         | 0.02%   |
| /etc/X11/Xsession | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 2495      | 44.19%  |
| Unknown     | 1715      | 30.38%  |
| Wayland     | 829       | 14.68%  |
| Tty         | 603       | 10.68%  |
| Web         | 2         | 0.04%   |
| Unspecified | 2         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2792      | 49.54%  |
| LightDM | 1015      | 18.01%  |
| GDM     | 990       | 17.57%  |
| SDDM    | 547       | 9.71%   |
| TDM     | 154       | 2.73%   |
| GDM3    | 102       | 1.81%   |
| XDM     | 13        | 0.23%   |
| SLiM    | 10        | 0.18%   |
| LXDM    | 7         | 0.12%   |
| NODM    | 4         | 0.07%   |
| Ly      | 1         | 0.02%   |
| KDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1784      | 31.69%  |
| ru_RU   | 900       | 15.99%  |
| Unknown | 871       | 15.47%  |
| de_DE   | 297       | 5.28%   |
| en_GB   | 268       | 4.76%   |
| fr_FR   | 256       | 4.55%   |
| es_ES   | 163       | 2.9%    |
| it_IT   | 128       | 2.27%   |
| pt_BR   | 116       | 2.06%   |
| pl_PL   | 88        | 1.56%   |
| C       | 63        | 1.12%   |
| en_AU   | 62        | 1.1%    |
| en_CA   | 61        | 1.08%   |
| es_MX   | 40        | 0.71%   |
| zh_CN   | 33        | 0.59%   |
| hu_HU   | 28        | 0.5%    |
| es_AR   | 28        | 0.5%    |
| es_VE   | 26        | 0.46%   |
| en_IN   | 25        | 0.44%   |
| ja_JP   | 23        | 0.41%   |
| en_IE   | 22        | 0.39%   |
| de_CH   | 19        | 0.34%   |
| de_AT   | 18        | 0.32%   |
| pt_PT   | 16        | 0.28%   |
| nl_NL   | 16        | 0.28%   |
| es_CL   | 13        | 0.23%   |
| en_NZ   | 13        | 0.23%   |
| sv_SE   | 12        | 0.21%   |
| fi_FI   | 12        | 0.21%   |
| cs_CZ   | 11        | 0.2%    |
| fr_BE   | 10        | 0.18%   |
| en_ZA   | 10        | 0.18%   |
| nl_BE   | 9         | 0.16%   |
| es_CO   | 9         | 0.16%   |
| uk_UA   | 8         | 0.14%   |
| tr_TR   | 8         | 0.14%   |
| es_PE   | 8         | 0.14%   |
| en_SG   | 8         | 0.14%   |
| nb_NO   | 7         | 0.12%   |
| ko_KR   | 7         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 3204      | 56.89%  |
| BIOS | 2428      | 43.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3498      | 62.51%  |
| Overlay | 1762      | 31.49%  |
| Btrfs   | 165       | 2.95%   |
| Zfs     | 78        | 1.39%   |
| Xfs     | 54        | 0.96%   |
| Ext3    | 12        | 0.21%   |
| Tmpfs   | 11        | 0.2%    |
| Unknown | 7         | 0.13%   |
| Ext2    | 6         | 0.11%   |
| Rootfs  | 2         | 0.04%   |
| Aufs    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 3322      | 58.88%  |
| MBR     | 1570      | 27.83%  |
| Unknown | 750       | 13.29%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4536      | 80.74%  |
| Yes       | 1082      | 19.26%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3854      | 68.52%  |
| Yes       | 1771      | 31.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 831       | 14.91%  |
| Lenovo                  | 816       | 14.64%  |
| Apple                   | 615       | 11.04%  |
| Hewlett-Packard         | 570       | 10.23%  |
| Dell                    | 530       | 9.51%   |
| Gigabyte Technology     | 363       | 6.51%   |
| MSI                     | 259       | 4.65%   |
| ASRock                  | 196       | 3.52%   |
| Acer                    | 188       | 3.37%   |
| Google                  | 135       | 2.42%   |
| Intel                   | 125       | 2.24%   |
| Raspberry Pi Foundation | 106       | 1.9%    |
| Unknown                 | 69        | 1.24%   |
| Supermicro              | 48        | 0.86%   |
| Aquarius                | 47        | 0.84%   |
| ECS                     | 46        | 0.83%   |
| Toshiba                 | 39        | 0.7%    |
| Samsung Electronics     | 38        | 0.68%   |
| Fujitsu                 | 34        | 0.61%   |
| HUAWEI                  | 27        | 0.48%   |
| Foxconn                 | 27        | 0.48%   |
| ASRockRack              | 21        | 0.38%   |
| Sony                    | 18        | 0.32%   |
| Notebook                | 17        | 0.31%   |
| AZW                     | 16        | 0.29%   |
| Pegatron                | 13        | 0.23%   |
| Packard Bell            | 13        | 0.23%   |
| Medion                  | 11        | 0.2%    |
| Biostar                 | 11        | 0.2%    |
| Panasonic               | 9         | 0.16%   |
| Microsoft               | 9         | 0.16%   |
| IBM                     | 9         | 0.16%   |
| Hardkernel              | 9         | 0.16%   |
| Xunlong                 | 8         | 0.14%   |
| Positivo                | 8         | 0.14%   |
| Fujitsu Siemens         | 8         | 0.14%   |
| BESSTAR Tech            | 8         | 0.14%   |
| AMI                     | 8         | 0.14%   |
| sunxi                   | 7         | 0.13%   |
| Inventec                | 7         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Apple MacBook5,2                          | 306       | 5.49%   |
| Lenovo ThinkPad L13 Yoga Gen 2 20VK0019US | 114       | 2.05%   |
| Unknown                                   | 79        | 1.42%   |
| Apple MacBookAir7,1                       | 77        | 1.38%   |
| Apple MacBookAir7,2                       | 76        | 1.36%   |
| Google Enguarde                           | 74        | 1.33%   |
| ASUS All Series                           | 73        | 1.31%   |
| ASUS S20 K29                              | 55        | 0.99%   |
| Apple MacBook2,1                          | 55        | 0.99%   |
| Aquarius NS585                            | 44        | 0.79%   |
| MSI MS-7996                               | 38        | 0.68%   |
| Lenovo ThinkPad E475 20H40006US           | 24        | 0.43%   |
| RPi Raspberry Pi 4 Model B Rev 1.4        | 23        | 0.41%   |
| Google Terra                              | 23        | 0.41%   |
| ECS G31T-M9                               | 21        | 0.38%   |
| Apple MacBook4,1                          | 21        | 0.38%   |
| MSI MS-7817                               | 20        | 0.36%   |
| ASRock H470M-HVS                          | 20        | 0.36%   |
| RPi Raspberry Pi 4 Model B Rev 1.2        | 18        | 0.32%   |
| Gigabyte H81M-S2V                         | 18        | 0.32%   |
| RPi Raspberry Pi 3 Model B Rev 1.2        | 17        | 0.31%   |
| ASUS PRIME H510M-A                        | 17        | 0.31%   |
| Supermicro Super Server                   | 16        | 0.29%   |
| RPi Raspberry Pi 4 Model B Rev 1.1        | 16        | 0.29%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US     | 16        | 0.29%   |
| Gigabyte H410M S2H                        | 16        | 0.29%   |
| ECS H61H2-M13                             | 16        | 0.29%   |
| ASUS P8H61-M LX3 R2.0                     | 15        | 0.27%   |
| Acer Aspire A315-23                       | 15        | 0.27%   |
| HP Notebook                               | 14        | 0.25%   |
| ASUS 1005HA                               | 14        | 0.25%   |
| Dell OptiPlex 7010                        | 13        | 0.23%   |
| HP Pavilion g6                            | 12        | 0.22%   |
| Google Reks                               | 11        | 0.2%    |
| Gigabyte B450M DS3H                       | 10        | 0.18%   |
| ASUS H110M-R                              | 10        | 0.18%   |
| HP EliteBook 8460p                        | 9         | 0.16%   |
| ASUS PRIME B450M-A                        | 9         | 0.16%   |
| ASUS P8H67-M                              | 9         | 0.16%   |
| HP Laptop 15-db0xxx                       | 8         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 528       | 9.47%   |
| Apple MacBook5     | 306       | 5.49%   |
| Apple MacBookAir7  | 153       | 2.75%   |
| Dell Latitude      | 144       | 2.58%   |
| Dell Inspiron      | 122       | 2.19%   |
| Acer Aspire        | 121       | 2.17%   |
| ASUS PRIME         | 109       | 1.96%   |
| RPi Raspberry      | 106       | 1.9%    |
| Lenovo IdeaPad     | 95        | 1.7%    |
| HP EliteBook       | 81        | 1.45%   |
| Unknown            | 79        | 1.42%   |
| Dell OptiPlex      | 75        | 1.35%   |
| Google Enguarde    | 74        | 1.33%   |
| ASUS All           | 73        | 1.31%   |
| HP Pavilion        | 69        | 1.24%   |
| HP Compaq          | 61        | 1.09%   |
| HP Laptop          | 58        | 1.04%   |
| Dell Precision     | 56        | 1%      |
| ASUS S20           | 55        | 0.99%   |
| Apple MacBook2     | 55        | 0.99%   |
| HP ProBook         | 51        | 0.92%   |
| ASUS ROG           | 48        | 0.86%   |
| Lenovo ThinkCentre | 47        | 0.84%   |
| Dell XPS           | 47        | 0.84%   |
| Aquarius NS585     | 44        | 0.79%   |
| ASUS TUF           | 42        | 0.75%   |
| ASUS VivoBook      | 39        | 0.7%    |
| MSI MS-7996        | 38        | 0.68%   |
| Dell Vostro        | 36        | 0.65%   |
| Toshiba Satellite  | 32        | 0.57%   |
| Dell PowerEdge     | 31        | 0.56%   |
| ASUS P8H61-M       | 31        | 0.56%   |
| HP ProLiant        | 29        | 0.52%   |
| Gigabyte B450M     | 24        | 0.43%   |
| Google Terra       | 23        | 0.41%   |
| ASUS ZenBook       | 22        | 0.39%   |
| ECS G31T-M9        | 21        | 0.38%   |
| ASUS Pro           | 21        | 0.38%   |
| ASUS ASUS          | 21        | 0.38%   |
| Apple MacBook4     | 21        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 687       | 12.33%  |
| 2021    | 520       | 9.33%   |
| 2009    | 493       | 8.85%   |
| 2019    | 437       | 7.84%   |
| 2012    | 388       | 6.96%   |
| 2018    | 381       | 6.84%   |
| 2013    | 321       | 5.76%   |
| 2015    | 315       | 5.65%   |
| 2016    | 290       | 5.2%    |
| 2011    | 284       | 5.1%    |
| 2017    | 283       | 5.08%   |
| 2014    | 232       | 4.16%   |
| 2022    | 199       | 3.57%   |
| 2010    | 186       | 3.34%   |
| 2008    | 158       | 2.84%   |
| Unknown | 150       | 2.69%   |
| 2007    | 144       | 2.58%   |
| 2006    | 42        | 0.75%   |
| 2005    | 34        | 0.61%   |
| 2003    | 14        | 0.25%   |
| 2004    | 8         | 0.14%   |
| 2001    | 3         | 0.05%   |
| 2023    | 2         | 0.04%   |
| 2002    | 1         | 0.02%   |
| 2000    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2897      | 51.98%  |
| Desktop        | 2043      | 36.66%  |
| Convertible    | 180       | 3.23%   |
| System on chip | 158       | 2.84%   |
| Mini pc        | 121       | 2.17%   |
| Server         | 99        | 1.78%   |
| All in one     | 43        | 0.77%   |
| Tablet         | 28        | 0.5%    |
| Phone          | 3         | 0.05%   |
| Stick pc       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 5289      | 94.48%  |
| Enabled  | 309       | 5.52%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5429      | 97.4%   |
| Yes  | 145       | 2.6%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1298      | 23.12%  |
| 3.01-4.0        | 1009      | 17.98%  |
| 16.01-24.0      | 1006      | 17.92%  |
| 8.01-16.0       | 700       | 12.47%  |
| 1.01-2.0        | 603       | 10.74%  |
| 32.01-64.0      | 436       | 7.77%   |
| 64.01-256.0     | 236       | 4.2%    |
| 2.01-3.0        | 107       | 1.91%   |
| 0.51-1.0        | 100       | 1.78%   |
| 24.01-32.0      | 74        | 1.32%   |
| 0.01-0.5        | 27        | 0.48%   |
| More than 256.0 | 16        | 0.29%   |
| Unknown         | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 2025      | 34.57%  |
| 0.51-1.0    | 1125      | 19.21%  |
| 2.01-3.0    | 955       | 16.31%  |
| 4.01-8.0    | 640       | 10.93%  |
| 3.01-4.0    | 506       | 8.64%   |
| 0.01-0.5    | 265       | 4.52%   |
| 8.01-16.0   | 206       | 3.52%   |
| 16.01-24.0  | 62        | 1.06%   |
| 32.01-64.0  | 36        | 0.61%   |
| 24.01-32.0  | 24        | 0.41%   |
| 64.01-256.0 | 11        | 0.19%   |
| Unknown     | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3913      | 69.18%  |
| 2      | 985       | 17.42%  |
| 3      | 311       | 5.5%    |
| 4      | 183       | 3.24%   |
| 5      | 83        | 1.47%   |
| 6      | 45        | 0.8%    |
| 0      | 43        | 0.76%   |
| 7      | 31        | 0.55%   |
| 8      | 26        | 0.46%   |
| 10     | 9         | 0.16%   |
| 9      | 6         | 0.11%   |
| 14     | 4         | 0.07%   |
| 13     | 4         | 0.07%   |
| 12     | 4         | 0.07%   |
| 28     | 2         | 0.04%   |
| 11     | 2         | 0.04%   |
| 27     | 1         | 0.02%   |
| 26     | 1         | 0.02%   |
| 21     | 1         | 0.02%   |
| 18     | 1         | 0.02%   |
| 16     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3805      | 68.07%  |
| Yes       | 1785      | 31.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4786      | 85.76%  |
| No        | 795       | 14.24%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3750      | 67.13%  |
| No        | 1836      | 32.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3154      | 56.34%  |
| No        | 2444      | 43.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1519      | 27.19%  |
| Russia       | 943       | 16.88%  |
| Germany      | 469       | 8.4%    |
| France       | 333       | 5.96%   |
| Spain        | 210       | 3.76%   |
| Italy        | 169       | 3.03%   |
| Brazil       | 161       | 2.88%   |
| UK           | 146       | 2.61%   |
| Poland       | 132       | 2.36%   |
| Canada       | 105       | 1.88%   |
| Netherlands  | 86        | 1.54%   |
| Australia    | 82        | 1.47%   |
| Switzerland  | 78        | 1.4%    |
| Mexico       | 65        | 1.16%   |
| China        | 58        | 1.04%   |
| Argentina    | 49        | 0.88%   |
| Sweden       | 47        | 0.84%   |
| Hungary      | 46        | 0.82%   |
| Ukraine      | 44        | 0.79%   |
| Belgium      | 42        | 0.75%   |
| Austria      | 41        | 0.73%   |
| Portugal     | 37        | 0.66%   |
| India        | 35        | 0.63%   |
| Finland      | 35        | 0.63%   |
| Czechia      | 33        | 0.59%   |
| Venezuela    | 30        | 0.54%   |
| Turkey       | 30        | 0.54%   |
| Japan        | 30        | 0.54%   |
| Norway       | 29        | 0.52%   |
| Bulgaria     | 26        | 0.47%   |
| Romania      | 25        | 0.45%   |
| Ireland      | 19        | 0.34%   |
| Greece       | 19        | 0.34%   |
| New Zealand  | 18        | 0.32%   |
| Croatia      | 18        | 0.32%   |
| Chile        | 18        | 0.32%   |
| Colombia     | 17        | 0.3%    |
| South Africa | 16        | 0.29%   |
| Denmark      | 16        | 0.29%   |
| Indonesia    | 15        | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Voronezh          | 706       | 12.13%  |
| Bangor            | 701       | 12.04%  |
| Dover-Foxcroft    | 305       | 5.24%   |
| Paris             | 53        | 0.91%   |
| Moscow            | 52        | 0.89%   |
| Seville           | 50        | 0.86%   |
| St Petersburg     | 45        | 0.77%   |
| Berlin            | 38        | 0.65%   |
| Vienna            | 31        | 0.53%   |
| Madrid            | 31        | 0.53%   |
| Warsaw            | 30        | 0.52%   |
| Munich            | 28        | 0.48%   |
| Zurich            | 27        | 0.46%   |
| Barcelona         | 27        | 0.46%   |
| Milan             | 26        | 0.45%   |
| Amsterdam         | 26        | 0.45%   |
| Sao Paulo         | 23        | 0.4%    |
| London            | 20        | 0.34%   |
| Toronto           | 19        | 0.33%   |
| Sydney            | 19        | 0.33%   |
| Falkenstein       | 19        | 0.33%   |
| Perm              | 18        | 0.31%   |
| Frankfurt am Main | 18        | 0.31%   |
| Hamburg           | 17        | 0.29%   |
| Brisbane          | 17        | 0.29%   |
| Helsinki          | 16        | 0.27%   |
| Melbourne         | 15        | 0.26%   |
| Prague            | 14        | 0.24%   |
| Cologne           | 14        | 0.24%   |
| Budapest          | 14        | 0.24%   |
| San Jose          | 13        | 0.22%   |
| Lyon              | 13        | 0.22%   |
| Istanbul          | 13        | 0.22%   |
| Chicago           | 13        | 0.22%   |
| Caracas           | 13        | 0.22%   |
| Blizniew          | 13        | 0.22%   |
| Zagreb            | 12        | 0.21%   |
| Winterport        | 12        | 0.21%   |
| Leipzig           | 12        | 0.21%   |
| Dublin            | 12        | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1129      | 1638   | 14.95%  |
| WDC                 | 998       | 1548   | 13.21%  |
| Seagate             | 956       | 1583   | 12.66%  |
| Toshiba             | 527       | 763    | 6.98%   |
| Kingston            | 471       | 585    | 6.24%   |
| Unknown             | 432       | 551    | 5.72%   |
| Crucial             | 361       | 432    | 4.78%   |
| SanDisk             | 290       | 359    | 3.84%   |
| Fujitsu             | 246       | 254    | 3.26%   |
| Hitachi             | 225       | 298    | 2.98%   |
| Apple               | 186       | 220    | 2.46%   |
| Intel               | 167       | 209    | 2.21%   |
| SK hynix            | 152       | 186    | 2.01%   |
| A-DATA Technology   | 143       | 243    | 1.89%   |
| HGST                | 105       | 166    | 1.39%   |
| Micron Technology   | 99        | 104    | 1.31%   |
| China               | 80        | 94     | 1.06%   |
| Unknown             | 54        | 56     | 0.71%   |
| SPCC                | 50        | 57     | 0.66%   |
| KIOXIA              | 49        | 55     | 0.65%   |
| PNY                 | 40        | 56     | 0.53%   |
| Transcend           | 38        | 45     | 0.5%    |
| Phison              | 33        | 43     | 0.44%   |
| Netac               | 32        | 91     | 0.42%   |
| Intenso             | 32        | 39     | 0.42%   |
| SABRENT             | 27        | 28     | 0.36%   |
| JMicron Technology  | 27        | 27     | 0.36%   |
| LITEON              | 26        | 30     | 0.34%   |
| Patriot             | 24        | 26     | 0.32%   |
| Corsair             | 23        | 37     | 0.3%    |
| Silicon Motion      | 22        | 27     | 0.29%   |
| GOODRAM             | 22        | 35     | 0.29%   |
| OCZ                 | 21        | 25     | 0.28%   |
| Hewlett-Packard     | 21        | 38     | 0.28%   |
| Maxtor              | 20        | 25     | 0.26%   |
| LITEONIT            | 16        | 20     | 0.21%   |
| Gigabyte Technology | 15        | 17     | 0.2%    |
| Apacer              | 15        | 15     | 0.2%    |
| Team                | 14        | 25     | 0.19%   |
| ASMT                | 13        | 15     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB     | 202       | 2.45%   |
| Samsung MZVLB512HBJQ-000L7 512GB   | 122       | 1.48%   |
| Kingston SA400S37240G 240GB SSD    | 109       | 1.32%   |
| Seagate ST500DM002-1BD142 500GB    | 81        | 0.98%   |
| Apple SSD AP0128H 121GB            | 77        | 0.93%   |
| Crucial CT480BX500SSD1 480GB       | 74        | 0.9%    |
| Apple SSD SM0128G 121GB            | 71        | 0.86%   |
| Kingston SA400S37120G 120GB SSD    | 57        | 0.69%   |
| Toshiba DT01ACA050 500GB           | 56        | 0.68%   |
| Kingston SV300S37A120G 120GB SSD   | 56        | 0.68%   |
| Unknown                            | 54        | 0.66%   |
| Samsung SSD 860 EVO 500GB          | 51        | 0.62%   |
| Samsung SSD 860 EVO 250GB          | 51        | 0.62%   |
| Kingston SA400S37480G 480GB SSD    | 50        | 0.61%   |
| A-DATA SU800 512GB SSD             | 48        | 0.58%   |
| Toshiba MK1655GSXF 160GB           | 47        | 0.57%   |
| Seagate ST1000DM010-2EP102 1TB     | 45        | 0.55%   |
| Seagate ST1000LM035-1RK172 1TB     | 44        | 0.53%   |
| Crucial CT500MX500SSD1 500GB       | 44        | 0.53%   |
| Toshiba MK1653GSX 160GB            | 43        | 0.52%   |
| Samsung SSD 970 EVO Plus 1TB       | 41        | 0.5%    |
| Crucial CT1000MX500SSD1 1TB        | 41        | 0.5%    |
| Unknown AGND3R  16GB               | 39        | 0.47%   |
| Samsung SSD 860 EVO 1TB            | 39        | 0.47%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 36        | 0.44%   |
| Unknown MMC Card  32GB             | 35        | 0.42%   |
| Samsung SSD 970 EVO Plus 500GB     | 35        | 0.42%   |
| Crucial CT240BX500SSD1 240GB       | 34        | 0.41%   |
| Toshiba DT01ACA100 1TB             | 32        | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB           | 31        | 0.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 31        | 0.38%   |
| Hitachi HDS721050CLA362 500GB      | 31        | 0.38%   |
| Unknown HAG2e  16GB                | 30        | 0.36%   |
| Toshiba HDWD110 1TB                | 30        | 0.36%   |
| Samsung SSD 850 EVO 250GB          | 30        | 0.36%   |
| Seagate ST1000DM003-1ER162 1TB     | 29        | 0.35%   |
| Samsung SSD 870 EVO 500GB          | 28        | 0.34%   |
| Samsung SSD 850 EVO 500GB          | 27        | 0.33%   |
| SABRENT Disk 256GB                 | 27        | 0.33%   |
| Unknown SDW16G  16GB               | 25        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 929       | 1530   | 31.99%  |
| WDC                 | 745       | 1192   | 25.65%  |
| Toshiba             | 441       | 660    | 15.19%  |
| Fujitsu             | 246       | 254    | 8.47%   |
| Hitachi             | 225       | 298    | 7.75%   |
| HGST                | 105       | 166    | 3.62%   |
| Samsung Electronics | 72        | 91     | 2.48%   |
| SABRENT             | 27        | 28     | 0.93%   |
| Unknown             | 24        | 33     | 0.83%   |
| Maxtor              | 19        | 21     | 0.65%   |
| JMicron Technology  | 16        | 16     | 0.55%   |
| Apple               | 8         | 10     | 0.28%   |
| Intenso             | 5         | 5      | 0.17%   |
| Hewlett-Packard     | 5         | 14     | 0.17%   |
| ASMedia             | 5         | 5      | 0.17%   |
| USB3.0              | 4         | 4      | 0.14%   |
| IBM/Hitachi         | 2         | 2      | 0.07%   |
| IBM-ESXS            | 2         | 4      | 0.07%   |
| HPE                 | 2         | 6      | 0.07%   |
| ASMT                | 2         | 3      | 0.07%   |
| Unknown (CF)        | 1         | 1      | 0.03%   |
| TrueNAS             | 1         | 1      | 0.03%   |
| Synology            | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| SILICONMOTION       | 1         | 1      | 0.03%   |
| RSH-319             | 1         | 1      | 0.03%   |
| QNAP                | 1         | 1      | 0.03%   |
| pqi                 | 1         | 1      | 0.03%   |
| Pear 2TB            | 1         | 1      | 0.03%   |
| NAS                 | 1         | 5      | 0.03%   |
| Maxone              | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 4      | 0.03%   |
| MARSHAL             | 1         | 1      | 0.03%   |
| Hajaan              | 1         | 1      | 0.03%   |
| China               | 1         | 1      | 0.03%   |
| ASMT109x            | 1         | 1      | 0.03%   |
| AMP                 | 1         | 1      | 0.03%   |
| Advantech           | 1         | 1      | 0.03%   |
| 3ware               | 1         | 4      | 0.03%   |
| 128MB               | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 515       | 688    | 20.49%  |
| Kingston            | 395       | 496    | 15.71%  |
| Crucial             | 321       | 380    | 12.77%  |
| SanDisk             | 200       | 248    | 7.96%   |
| A-DATA Technology   | 108       | 188    | 4.3%    |
| WDC                 | 105       | 125    | 4.18%   |
| Apple               | 93        | 100    | 3.7%    |
| China               | 78        | 92     | 3.1%    |
| Intel               | 68        | 83     | 2.7%    |
| Micron Technology   | 42        | 44     | 1.67%   |
| SPCC                | 41        | 45     | 1.63%   |
| Toshiba             | 35        | 41     | 1.39%   |
| Transcend           | 34        | 41     | 1.35%   |
| PNY                 | 32        | 47     | 1.27%   |
| Netac               | 32        | 91     | 1.27%   |
| SK hynix            | 30        | 39     | 1.19%   |
| Intenso             | 24        | 29     | 0.95%   |
| Patriot             | 21        | 22     | 0.84%   |
| OCZ                 | 21        | 25     | 0.84%   |
| LITEON              | 21        | 24     | 0.84%   |
| GOODRAM             | 18        | 25     | 0.72%   |
| LITEONIT            | 16        | 20     | 0.64%   |
| Apacer              | 13        | 13     | 0.52%   |
| Team                | 12        | 22     | 0.48%   |
| Unknown             | 12        | 13     | 0.48%   |
| ASMT                | 11        | 12     | 0.44%   |
| Seagate             | 10        | 12     | 0.4%    |
| Hewlett-Packard     | 9         | 13     | 0.36%   |
| Gigabyte Technology | 9         | 9      | 0.36%   |
| Plextor             | 8         | 11     | 0.32%   |
| KingDian            | 8         | 8      | 0.32%   |
| Corsair             | 8         | 12     | 0.32%   |
| Unknown             | 7         | 10     | 0.28%   |
| Hajaan              | 7         | 8      | 0.28%   |
| Mushkin             | 6         | 7      | 0.24%   |
| Lexar               | 6         | 8      | 0.24%   |
| LDLC                | 5         | 5      | 0.2%    |
| KIOXIA-EXCERIA      | 5         | 8      | 0.2%    |
| Dogfish             | 5         | 7      | 0.2%    |
| Xinhaike            | 4         | 6      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2505      | 4372   | 36.27%  |
| SSD     | 2245      | 3216   | 32.5%   |
| NVMe    | 1623      | 2229   | 23.5%   |
| MMC     | 451       | 555    | 6.53%   |
| Unknown | 83        | 125    | 1.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3958      | 7187   | 62.7%   |
| NVMe | 1618      | 2218   | 25.63%  |
| MMC  | 451       | 555    | 7.14%   |
| SAS  | 286       | 537    | 4.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB  | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| 0.01-0.5    | 3168      | 4430   | 63.61%  |
| 0.51-1.0    | 1110      | 1689   | 22.29%  |
| 1.01-2.0    | 320       | 547    | 6.43%   |
| 3.01-4.0    | 146       | 344    | 2.93%   |
| 4.01-10.0   | 132       | 324    | 2.65%   |
| 2.01-3.0    | 68        | 117    | 1.37%   |
| 10.01-20.0  | 34        | 132    | 0.68%   |
| 20.01-50.0  | 1         | 1      | 0.02%   |
| 50.01-100.0 | 1         | 4      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 1377      | 24.09%  |
| 101-250        | 1237      | 21.64%  |
| 251-500        | 949       | 16.6%   |
| 501-1000       | 602       | 10.53%  |
| 51-100         | 329       | 5.75%   |
| 1-20           | 322       | 5.63%   |
| 1001-2000      | 301       | 5.26%   |
| More than 3000 | 261       | 4.57%   |
| 21-50          | 223       | 3.9%    |
| 2001-3000      | 116       | 2.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2083      | 35.78%  |
| Unknown        | 1377      | 23.66%  |
| 101-250        | 522       | 8.97%   |
| 21-50          | 513       | 8.81%   |
| 51-100         | 451       | 7.75%   |
| 251-500        | 320       | 5.5%    |
| 501-1000       | 238       | 4.09%   |
| 1001-2000      | 131       | 2.25%   |
| More than 3000 | 108       | 1.86%   |
| 2001-3000      | 57        | 0.98%   |
| 0              | 21        | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB       | 21        | 24     | 2.65%   |
| Seagate ST500DM002-1BD142 500GB    | 20        | 24     | 2.53%   |
| Fujitsu MHZ2160BH FFS G1 160GB     | 20        | 20     | 2.53%   |
| Kingston SV300S37A120G 120GB SSD   | 18        | 18     | 2.28%   |
| Toshiba MK1653GSX 160GB            | 9         | 9      | 1.14%   |
| Seagate ST9500325AS 500GB          | 9         | 11     | 1.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 9         | 10     | 1.14%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 8         | 8      | 1.01%   |
| Toshiba MK1655GSXF 160GB           | 8         | 8      | 1.01%   |
| Hitachi HDS721050CLA362 500GB      | 8         | 8      | 1.01%   |
| Seagate ST250DM000-1BD141 250GB    | 7         | 7      | 0.88%   |
| Seagate ST9500420AS 500GB          | 6         | 6      | 0.76%   |
| Seagate ST3250318AS 250GB          | 6         | 6      | 0.76%   |
| Seagate ST1000DM003-9YN162 1TB     | 6         | 7      | 0.76%   |
| Hitachi HTS543216L9SA02 160GB      | 6         | 6      | 0.76%   |
| Hitachi HDS721050DLE630 500GB      | 6         | 11     | 0.76%   |
| WDC WD10EZEX-08WN4A0 1TB           | 5         | 5      | 0.63%   |
| Toshiba DT01ACA050 500GB           | 5         | 6      | 0.63%   |
| Seagate ST3500418AS 500GB          | 5         | 6      | 0.63%   |
| Seagate ST31500341AS 1TB           | 5         | 7      | 0.63%   |
| Hitachi HTS542512K9SA00 120GB      | 5         | 6      | 0.63%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 4         | 4      | 0.51%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 4         | 5      | 0.51%   |
| WDC WD20EARS-00MVWB0 2TB           | 4         | 4      | 0.51%   |
| WDC WD1600BUDT-63DPZY0 160GB       | 4         | 4      | 0.51%   |
| Seagate ST500LT012-9WS142 500GB    | 4         | 4      | 0.51%   |
| Seagate ST500LT012-1DG142 500GB    | 4         | 4      | 0.51%   |
| Seagate ST500LM021-1KJ152 500GB    | 4         | 4      | 0.51%   |
| Seagate ST3500413AS 500GB          | 4         | 5      | 0.51%   |
| Seagate ST31000528AS 1TB           | 4         | 4      | 0.51%   |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 4      | 0.51%   |
| Seagate ST1000DM003-1CH162 1TB     | 4         | 4      | 0.51%   |
| Hitachi HTS547575A9E384 752GB      | 4         | 4      | 0.51%   |
| Hitachi HTS545050B9A300 500GB      | 4         | 4      | 0.51%   |
| HGST HTS725050A7E630 500GB         | 4         | 5      | 0.51%   |
| HGST HTS541010A9E680 1TB           | 4         | 4      | 0.51%   |
| WDC WD5000AAKX-001CA0 500GB        | 3         | 3      | 0.38%   |
| WDC WD40EFRX-68N32N0 4TB           | 3         | 5      | 0.38%   |
| WDC WD3200AAJS-08L7A0 320GB        | 3         | 3      | 0.38%   |
| WDC WD2500AAJS-00YZCA0 250GB       | 3         | 3      | 0.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 210       | 263    | 27.17%  |
| WDC                 | 174       | 214    | 22.51%  |
| Hitachi             | 81        | 99     | 10.48%  |
| Toshiba             | 49        | 51     | 6.34%   |
| Samsung Electronics | 47        | 50     | 6.08%   |
| Kingston            | 36        | 41     | 4.66%   |
| Fujitsu             | 29        | 30     | 3.75%   |
| Intel               | 28        | 34     | 3.62%   |
| HGST                | 19        | 21     | 2.46%   |
| SK hynix            | 16        | 19     | 2.07%   |
| A-DATA Technology   | 12        | 15     | 1.55%   |
| Micron Technology   | 11        | 11     | 1.42%   |
| Crucial             | 11        | 14     | 1.42%   |
| SanDisk             | 10        | 11     | 1.29%   |
| Maxtor              | 7         | 7      | 0.91%   |
| LITEONIT            | 4         | 5      | 0.52%   |
| LITEON              | 3         | 3      | 0.39%   |
| China               | 3         | 3      | 0.39%   |
| PNY                 | 2         | 4      | 0.26%   |
| OCZ                 | 2         | 2      | 0.26%   |
| Hewlett-Packard     | 2         | 3      | 0.26%   |
| Apacer              | 2         | 2      | 0.26%   |
| Unknown             | 2         | 2      | 0.26%   |
| USB3.0              | 1         | 1      | 0.13%   |
| SPCC                | 1         | 1      | 0.13%   |
| ShiJi               | 1         | 1      | 0.13%   |
| Plextor             | 1         | 1      | 0.13%   |
| Netac               | 1         | 1      | 0.13%   |
| Lenovo              | 1         | 1      | 0.13%   |
| KingDian            | 1         | 1      | 0.13%   |
| JMicron Technology  | 1         | 1      | 0.13%   |
| IBM/Hitachi         | 1         | 1      | 0.13%   |
| GOODRAM             | 1         | 1      | 0.13%   |
| DGM                 | 1         | 1      | 0.13%   |
| ASMedia             | 1         | 1      | 0.13%   |
| Apple               | 1         | 1      | 0.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 210       | 263    | 35.59%  |
| WDC                 | 168       | 207    | 28.47%  |
| Hitachi             | 81        | 99     | 13.73%  |
| Toshiba             | 47        | 49     | 7.97%   |
| Fujitsu             | 29        | 30     | 4.92%   |
| Samsung Electronics | 22        | 22     | 3.73%   |
| HGST                | 19        | 21     | 3.22%   |
| Maxtor              | 7         | 7      | 1.19%   |
| Hewlett-Packard     | 2         | 3      | 0.34%   |
| USB3.0              | 1         | 1      | 0.17%   |
| JMicron Technology  | 1         | 1      | 0.17%   |
| IBM/Hitachi         | 1         | 1      | 0.17%   |
| ASMedia             | 1         | 1      | 0.17%   |
| Apple               | 1         | 1      | 0.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 565       | 706    | 75.64%  |
| SSD  | 153       | 176    | 20.48%  |
| NVMe | 29        | 35     | 3.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                           | Computers | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 5.26%   |
| WDC WD4001FFSX-68JNUN0 4TB                      | 1         | 1      | 5.26%   |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 5.26%   |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 5.26%   |
| Seagate ST500DM005 HD502HJ 500GB                | 1         | 1      | 5.26%   |
| Seagate ST500DM002-1BD142 500GB                 | 1         | 2      | 5.26%   |
| Seagate ST3500830AS 500GB                       | 1         | 1      | 5.26%   |
| Seagate ST3500630A 500GB                        | 1         | 1      | 5.26%   |
| Samsung Electronics SSD 980 1TB                 | 1         | 1      | 5.26%   |
| Samsung Electronics SP0802N 80GB                | 1         | 1      | 5.26%   |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 5.26%   |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 5.26%   |
| Samsung Electronics HD253GJ 250GB               | 1         | 1      | 5.26%   |
| KingDian S400 120GB SSD                         | 1         | 1      | 5.26%   |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 5.26%   |
| HGST HUH728080ALN600 8TB                        | 1         | 1      | 5.26%   |
| HGST HTS725050A7E630 500GB                      | 1         | 2      | 5.26%   |
| HGST HDN724040ALE640 4TB                        | 1         | 1      | 5.26%   |
| Hewlett-Packard SSD S700 500GB                  | 1         | 2      | 5.26%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 7      | 31.58%  |
| Samsung Electronics | 5         | 5      | 26.32%  |
| HGST                | 3         | 4      | 15.79%  |
| WDC                 | 2         | 2      | 10.53%  |
| KingDian            | 1         | 1      | 5.26%   |
| Hitachi             | 1         | 2      | 5.26%   |
| Hewlett-Packard     | 1         | 2      | 5.26%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 4028      | 7001   | 65.99%  |
| Detected | 1326      | 2554   | 21.72%  |
| Malfunc  | 729       | 917    | 11.94%  |
| Failed   | 19        | 23     | 0.31%   |
| Limited  | 2         | 2      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3293      | 50.14%  |
| AMD                              | 839       | 12.78%  |
| Samsung Electronics              | 686       | 10.45%  |
| Nvidia                           | 373       | 5.68%   |
| SanDisk                          | 256       | 3.9%    |
| SK hynix                         | 117       | 1.78%   |
| ASMedia Technology               | 100       | 1.52%   |
| Apple                            | 85        | 1.29%   |
| Phison Electronics               | 83        | 1.26%   |
| Kingston Technology Company      | 82        | 1.25%   |
| Marvell Technology Group         | 64        | 0.97%   |
| JMicron Technology               | 61        | 0.93%   |
| Toshiba America Info Systems     | 58        | 0.88%   |
| Micron Technology                | 58        | 0.88%   |
| Micron/Crucial Technology        | 53        | 0.81%   |
| KIOXIA                           | 53        | 0.81%   |
| LSI Logic / Symbios Logic        | 49        | 0.75%   |
| Silicon Motion                   | 44        | 0.67%   |
| ADATA Technology                 | 43        | 0.65%   |
| Broadcom / LSI                   | 33        | 0.5%    |
| VIA Technologies                 | 26        | 0.4%    |
| Solid State Storage Technology   | 13        | 0.2%    |
| Hewlett-Packard                  | 11        | 0.17%   |
| Adaptec                          | 10        | 0.15%   |
| Union Memory (Shenzhen)          | 8         | 0.12%   |
| Realtek Semiconductor            | 8         | 0.12%   |
| MAXIO Technology (Hangzhou)      | 8         | 0.12%   |
| Silicon Image                    | 7         | 0.11%   |
| Seagate Technology               | 6         | 0.09%   |
| Lite-On Technology               | 6         | 0.09%   |
| Silicon Integrated Systems [SiS] | 5         | 0.08%   |
| Shenzhen Longsys Electronics     | 4         | 0.06%   |
| Lenovo                           | 4         | 0.06%   |
| ULi Electronics                  | 3         | 0.05%   |
| Jiangsu Huacun Elec.             | 3         | 0.05%   |
| 3ware                            | 3         | 0.05%   |
| Integrated Technology Express    | 2         | 0.03%   |
| INNOGRIT                         | 2         | 0.03%   |
| Biwin Storage Technology         | 2         | 0.03%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 576       | 7.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 378       | 5%      |
| Nvidia MCP79 AHCI Controller                                                            | 317       | 4.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 248       | 3.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 222       | 2.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 192       | 2.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 157       | 2.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 139       | 1.84%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 133       | 1.76%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 129       | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 125       | 1.65%   |
| AMD 400 Series Chipset SATA Controller                                                  | 122       | 1.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 118       | 1.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 117       | 1.55%   |
| Samsung NVMe SSD Controller 980                                                         | 103       | 1.36%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 100       | 1.32%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 99        | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 96        | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 93        | 1.23%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 88        | 1.16%   |
| Samsung Electronics SATA controller                                                     | 83        | 1.1%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 81        | 1.07%   |
| Apple S1X NVMe Controller                                                               | 79        | 1.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 77        | 1.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 76        | 1%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 76        | 1%      |
| AMD 500 Series Chipset SATA Controller                                                  | 75        | 0.99%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 70        | 0.93%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 69        | 0.91%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 69        | 0.91%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 67        | 0.89%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 66        | 0.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 66        | 0.87%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 59        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 59        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 59        | 0.78%   |
| Micron Non-Volatile memory controller                                                   | 55        | 0.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 55        | 0.73%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 54        | 0.71%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 52        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3856      | 57.23%  |
| NVMe | 1617      | 24%     |
| IDE  | 797       | 11.83%  |
| RAID | 390       | 5.79%   |
| SAS  | 62        | 0.92%   |
| SCSI | 16        | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 4374      | 78.47%  |
| AMD                   | 1020      | 18.3%   |
| ARM                   | 162       | 2.91%   |
| CentaurHauls          | 7         | 0.13%   |
| sifive,u74-mc         | 3         | 0.05%   |
| Phytium               | 3         | 0.05%   |
| Unknown               | 2         | 0.04%   |
| Qualcomm              | 1         | 0.02%   |
| Marvell Semiconductor | 1         | 0.02%   |
| HISILICON             | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 308       | 5.52%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 177       | 3.17%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 147       | 2.63%   |
| ARM Processor                                 | 131       | 2.35%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 89        | 1.59%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 68        | 1.22%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 61        | 1.09%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 60        | 1.08%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 54        | 0.97%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 45        | 0.81%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 44        | 0.79%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 43        | 0.77%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 42        | 0.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 37        | 0.66%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 35        | 0.63%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 35        | 0.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 33        | 0.59%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 31        | 0.56%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 30        | 0.54%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 28        | 0.5%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 28        | 0.5%    |
| AMD Ryzen 5 3600 6-Core Processor             | 28        | 0.5%    |
| Intel Core i7-10700 CPU @ 2.90GHz             | 27        | 0.48%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 27        | 0.48%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 25        | 0.45%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 25        | 0.45%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 25        | 0.45%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 24        | 0.43%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 24        | 0.43%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 24        | 0.43%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 24        | 0.43%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 24        | 0.43%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 24        | 0.43%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 24        | 0.43%   |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G    | 24        | 0.43%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 23        | 0.41%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 23        | 0.41%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 23        | 0.41%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 22        | 0.39%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 21        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1109      | 19.89%  |
| Intel Core i7           | 653       | 11.71%  |
| Other                   | 604       | 10.83%  |
| Intel Core 2 Duo        | 506       | 9.07%   |
| Intel Core i3           | 416       | 7.46%   |
| Intel Celeron           | 404       | 7.25%   |
| AMD Ryzen 5             | 261       | 4.68%   |
| Intel Pentium           | 218       | 3.91%   |
| Intel Xeon              | 202       | 3.62%   |
| AMD Ryzen 7             | 167       | 2.99%   |
| Intel Atom              | 112       | 2.01%   |
| Intel Core 2            | 75        | 1.35%   |
| AMD Ryzen 9             | 71        | 1.27%   |
| Intel Pentium Dual-Core | 64        | 1.15%   |
| AMD FX                  | 56        | 1%      |
| AMD Ryzen 3             | 46        | 0.82%   |
| Intel Core 2 Quad       | 34        | 0.61%   |
| AMD Ryzen 7 PRO         | 31        | 0.56%   |
| AMD A6                  | 27        | 0.48%   |
| Intel Core i9           | 26        | 0.47%   |
| AMD Ryzen Threadripper  | 24        | 0.43%   |
| AMD A10                 | 24        | 0.43%   |
| AMD Athlon              | 22        | 0.39%   |
| Intel Pentium M         | 21        | 0.38%   |
| Intel Pentium Gold      | 21        | 0.38%   |
| Intel Pentium 4         | 21        | 0.38%   |
| AMD Ryzen 5 PRO         | 21        | 0.38%   |
| AMD A4                  | 20        | 0.36%   |
| Intel Genuine           | 18        | 0.32%   |
| AMD Athlon II X2        | 17        | 0.3%    |
| Intel Pentium Dual      | 16        | 0.29%   |
| AMD Athlon 64 X2        | 16        | 0.29%   |
| AMD A8                  | 15        | 0.27%   |
| ARM Allwinner           | 14        | 0.25%   |
| AMD Phenom II X4        | 14        | 0.25%   |
| Intel Pentium Silver    | 12        | 0.22%   |
| Intel Celeron M         | 10        | 0.18%   |
| AMD Phenom II X6        | 10        | 0.18%   |
| AMD GX                  | 10        | 0.18%   |
| AMD E1                  | 10        | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2447      | 43.86%  |
| 4       | 1853      | 33.21%  |
| 6       | 471       | 8.44%   |
| 8       | 364       | 6.52%   |
| 1       | 195       | 3.5%    |
| 16      | 69        | 1.24%   |
| 12      | 66        | 1.18%   |
| 10      | 29        | 0.52%   |
| 3       | 23        | 0.41%   |
| Unknown | 14        | 0.25%   |
| 32      | 13        | 0.23%   |
| 14      | 9         | 0.16%   |
| 24      | 8         | 0.14%   |
| 20      | 4         | 0.07%   |
| 28      | 3         | 0.05%   |
| 18      | 3         | 0.05%   |
| 48      | 2         | 0.04%   |
| 44      | 2         | 0.04%   |
| 80      | 1         | 0.02%   |
| 64      | 1         | 0.02%   |
| 56      | 1         | 0.02%   |
| 36      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5471      | 98.12%  |
| 2       | 87        | 1.56%   |
| Unknown | 14        | 0.25%   |
| 3       | 2         | 0.04%   |
| 8       | 1         | 0.02%   |
| 4       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3187      | 57.11%  |
| 1       | 2378      | 42.62%  |
| Unknown | 14        | 0.25%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5411      | 97.04%  |
| 32-bit         | 103       | 1.85%   |
| Unknown        | 45        | 0.81%   |
| 64-bit         | 17        | 0.3%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1020      | 18.03%  |
| 0x1067a    | 481       | 8.5%    |
| 0x306a9    | 260       | 4.6%    |
| 0x806c1    | 255       | 4.51%   |
| 0x306c3    | 245       | 4.33%   |
| 0x206a7    | 238       | 4.21%   |
| 0x306d4    | 210       | 3.71%   |
| 0x906ea    | 143       | 2.53%   |
| 0x506e3    | 120       | 2.12%   |
| 0x30678    | 113       | 2%      |
| 0x806ec    | 111       | 1.96%   |
| 0x806e9    | 102       | 1.8%    |
| 0x08108109 | 81        | 1.43%   |
| 0x806ea    | 79        | 1.4%    |
| 0x40651    | 74        | 1.31%   |
| 0x906e9    | 72        | 1.27%   |
| 0x406e3    | 71        | 1.26%   |
| 0x406c4    | 71        | 1.26%   |
| 0xa0653    | 70        | 1.24%   |
| 0x6f6      | 70        | 1.24%   |
| 0x906eb    | 59        | 1.04%   |
| 0x08701021 | 57        | 1.01%   |
| 0x08600106 | 54        | 0.95%   |
| 0x0a50000c | 51        | 0.9%    |
| 0x20655    | 50        | 0.88%   |
| 0xa0652    | 49        | 0.87%   |
| 0x10676    | 47        | 0.83%   |
| 0x706a8    | 46        | 0.81%   |
| 0x6fd      | 41        | 0.72%   |
| 0xa0655    | 40        | 0.71%   |
| 0x506c9    | 38        | 0.67%   |
| 0x906c0    | 37        | 0.65%   |
| 0x0600611a | 36        | 0.64%   |
| 0x0a201016 | 35        | 0.62%   |
| 0x106c2    | 34        | 0.6%    |
| 0x08608103 | 34        | 0.6%    |
| 0xa0671    | 31        | 0.55%   |
| 0x706e5    | 31        | 0.55%   |
| 0x0800820d | 31        | 0.55%   |
| 0x206d7    | 26        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 743       | 13.31%  |
| Penryn           | 561       | 10.05%  |
| Haswell          | 421       | 7.54%   |
| IvyBridge        | 337       | 6.04%   |
| SandyBridge      | 320       | 5.73%   |
| Unknown          | 305       | 5.46%   |
| TigerLake        | 295       | 5.29%   |
| Skylake          | 250       | 4.48%   |
| Broadwell        | 243       | 4.35%   |
| Silvermont       | 233       | 4.17%   |
| Zen 2            | 196       | 3.51%   |
| CometLake        | 189       | 3.39%   |
| Zen+             | 176       | 3.15%   |
| Core             | 171       | 3.06%   |
| Zen 3            | 160       | 2.87%   |
| Westmere         | 111       | 1.99%   |
| Excavator        | 82        | 1.47%   |
| Goldmont plus    | 75        | 1.34%   |
| Zen              | 74        | 1.33%   |
| K10              | 72        | 1.29%   |
| Bonnell          | 66        | 1.18%   |
| Icelake          | 62        | 1.11%   |
| Piledriver       | 57        | 1.02%   |
| Goldmont         | 46        | 0.82%   |
| P6               | 45        | 0.81%   |
| Tremont          | 39        | 0.7%    |
| Nehalem          | 38        | 0.68%   |
| NetBurst         | 36        | 0.65%   |
| K8 Hammer        | 32        | 0.57%   |
| Bobcat           | 28        | 0.5%    |
| Alderlake Hybrid | 25        | 0.45%   |
| Puma             | 21        | 0.38%   |
| Steamroller      | 18        | 0.32%   |
| Jaguar           | 18        | 0.32%   |
| Bulldozer        | 17        | 0.3%    |
| K10 Llano        | 11        | 0.2%    |
| K8 & K10 hybrid  | 4         | 0.07%   |
| K6               | 3         | 0.05%   |
| Geode            | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3290      | 54.14%  |
| Nvidia                                       | 1553      | 25.56%  |
| AMD                                          | 1080      | 17.77%  |
| ASPEED Technology                            | 71        | 1.17%   |
| Matrox Electronics Systems                   | 67        | 1.1%    |
| VIA Technologies                             | 6         | 0.1%    |
| Silicon Integrated Systems [SiS]             | 4         | 0.07%   |
| Zhaoxin                                      | 3         | 0.05%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.02%   |
| S3 Graphics                                  | 1         | 0.02%   |
| ATI Technologies                             | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 306       | 4.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 278       | 4.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 217       | 3.44%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 171       | 2.71%   |
| Intel HD Graphics 6000                                                                   | 154       | 2.44%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 146       | 2.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 138       | 2.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 135       | 2.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 125       | 1.98%   |
| Intel UHD Graphics 620                                                                   | 100       | 1.59%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 98        | 1.55%   |
| AMD Renoir                                                                               | 98        | 1.55%   |
| Intel HD Graphics 620                                                                    | 97        | 1.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 93        | 1.48%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 89        | 1.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 85        | 1.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 82        | 1.3%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 77        | 1.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 76        | 1.21%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 71        | 1.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 71        | 1.13%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 70        | 1.11%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 68        | 1.08%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 67        | 1.06%   |
| Intel HD Graphics 5500                                                                   | 66        | 1.05%   |
| Intel HD Graphics 530                                                                    | 65        | 1.03%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 61        | 0.97%   |
| Intel HD Graphics 630                                                                    | 60        | 0.95%   |
| Intel Core Processor Integrated Graphics Controller                                      | 56        | 0.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 55        | 0.87%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 53        | 0.84%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 53        | 0.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 51        | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 51        | 0.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 51        | 0.81%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 49        | 0.78%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 49        | 0.78%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 41        | 0.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 41        | 0.65%   |
| AMD Lucienne                                                                             | 41        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 2704      | 48.33%  |
| 1 x Nvidia                        | 1022      | 18.27%  |
| 1 x AMD                           | 874       | 15.62%  |
| Intel + Nvidia                    | 444       | 7.94%   |
| Other                             | 190       | 3.4%    |
| Intel + AMD                       | 79        | 1.41%   |
| AMD + Nvidia                      | 65        | 1.16%   |
| 1 x Matrox                        | 64        | 1.14%   |
| 2 x AMD                           | 53        | 0.95%   |
| 1 x ASPEED                        | 53        | 0.95%   |
| Nvidia + ASPEED                   | 9         | 0.16%   |
| AMD + ASPEED                      | 7         | 0.13%   |
| 2 x Nvidia                        | 6         | 0.11%   |
| 1 x VIA                           | 6         | 0.11%   |
| 1 x SiS                           | 4         | 0.07%   |
| 1 x Zhaoxin                       | 3         | 0.05%   |
| Intel + 2 x Nvidia                | 3         | 0.05%   |
| Nvidia + Matrox                   | 2         | 0.04%   |
| 3 x AMD                           | 1         | 0.02%   |
| 2 x Nvidia + 1 x ASPEED           | 1         | 0.02%   |
| 2 x Intel                         | 1         | 0.02%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1         | 0.02%   |
| 1 x S3 Graphics                   | 1         | 0.02%   |
| Nvidia + XGI                      | 1         | 0.02%   |
| AMD + Matrox                      | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3951      | 70.49%  |
| Unknown     | 1209      | 21.57%  |
| Proprietary | 445       | 7.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 4065      | 72.19%  |
| 0.01-0.5       | 676       | 12%     |
| 1.01-2.0       | 288       | 5.11%   |
| 0.51-1.0       | 189       | 3.36%   |
| 3.01-4.0       | 188       | 3.34%   |
| 7.01-8.0       | 106       | 1.88%   |
| 5.01-6.0       | 63        | 1.12%   |
| 2.01-3.0       | 23        | 0.41%   |
| 8.01-16.0      | 23        | 0.41%   |
| 16.01-24.0     | 6         | 0.11%   |
| 4.01-5.0       | 2         | 0.04%   |
| More than 64.0 | 1         | 0.02%   |
| 24.01-32.0     | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 608       | 12.44%  |
| Apple                   | 594       | 12.15%  |
| Samsung Electronics     | 456       | 9.33%   |
| BOE                     | 417       | 8.53%   |
| LG Display              | 346       | 7.08%   |
| Chimei Innolux          | 345       | 7.06%   |
| Dell                    | 245       | 5.01%   |
| Goldstar                | 220       | 4.5%    |
| Hewlett-Packard         | 133       | 2.72%   |
| BenQ                    | 116       | 2.37%   |
| Acer                    | 114       | 2.33%   |
| Lenovo                  | 98        | 2%      |
| AOC                     | 98        | 2%      |
| Ancor Communications    | 91        | 1.86%   |
| Philips                 | 86        | 1.76%   |
| Sharp                   | 64        | 1.31%   |
| Iiyama                  | 58        | 1.19%   |
| Chi Mei Optoelectronics | 58        | 1.19%   |
| ViewSonic               | 55        | 1.13%   |
| Unknown                 | 55        | 1.13%   |
| InfoVision              | 52        | 1.06%   |
| Eizo                    | 37        | 0.76%   |
| ASUSTek Computer        | 34        | 0.7%    |
| PANDA                   | 33        | 0.68%   |
| HannStar                | 26        | 0.53%   |
| NEC Computers           | 24        | 0.49%   |
| Sony                    | 23        | 0.47%   |
| LG Philips              | 18        | 0.37%   |
| LG Electronics          | 18        | 0.37%   |
| CSO                     | 15        | 0.31%   |
| MSI                     | 14        | 0.29%   |
| Vestel Elektronik       | 13        | 0.27%   |
| Panasonic               | 12        | 0.25%   |
| Toshiba                 | 11        | 0.23%   |
| Unknown                 | 10        | 0.2%    |
| Vizio                   | 8         | 0.16%   |
| Medion                  | 8         | 0.16%   |
| Fujitsu Siemens         | 7         | 0.14%   |
| RTK                     | 6         | 0.12%   |
| Gigabyte Technology     | 6         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                 | 199       | 3.98%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 151       | 3.02%   |
| AU Optronics LCD Monitor AUO592D 1920x1080 293x165mm 13.2-inch       | 112       | 2.24%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                 | 52        | 1.04%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 44        | 0.88%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 42        | 0.84%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 41        | 0.82%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 39        | 0.78%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                 | 37        | 0.74%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 27        | 0.54%   |
| BOE LCD Monitor BOE06B3 1920x1080                                    | 25        | 0.5%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 24        | 0.48%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 24        | 0.48%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 21        | 0.42%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                 | 21        | 0.42%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 19        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 19        | 0.38%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 17        | 0.34%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch               | 16        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 15        | 0.3%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 15        | 0.3%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 14        | 0.28%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 13        | 0.26%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch       | 13        | 0.26%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 13        | 0.26%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                     | 12        | 0.24%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 12        | 0.24%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch | 11        | 0.22%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 11        | 0.22%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                 | 11        | 0.22%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 10        | 0.2%    |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 10        | 0.2%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 10        | 0.2%    |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                    | 10        | 0.2%    |
| Unknown                                                              | 10        | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 9         | 0.18%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 9         | 0.18%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x165mm 13.2-inch          | 9         | 0.18%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                | 9         | 0.18%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 9         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1877      | 39.96%  |
| 1366x768 (WXGA)    | 833       | 17.73%  |
| 1280x800 (WXGA)    | 463       | 9.86%   |
| 3840x2160 (4K)     | 242       | 5.15%   |
| 2560x1440 (QHD)    | 176       | 3.75%   |
| 1280x1024 (SXGA)   | 174       | 3.7%    |
| 1440x900 (WXGA+)   | 150       | 3.19%   |
| 1600x900 (HD+)     | 144       | 3.07%   |
| 1920x1200 (WUXGA)  | 100       | 2.13%   |
| 1680x1050 (WSXGA+) | 88        | 1.87%   |
| Unknown            | 50        | 1.06%   |
| 2288x1287          | 46        | 0.98%   |
| 1024x600           | 45        | 0.96%   |
| 1024x768 (XGA)     | 36        | 0.77%   |
| 2560x1080          | 31        | 0.66%   |
| 3440x1440          | 29        | 0.62%   |
| 1360x768           | 29        | 0.62%   |
| 2560x1600          | 23        | 0.49%   |
| 3840x1080          | 20        | 0.43%   |
| 1600x1200          | 19        | 0.4%    |
| 1920x540           | 12        | 0.26%   |
| 3840x2400          | 11        | 0.23%   |
| 2880x1800          | 9         | 0.19%   |
| 2160x1440          | 9         | 0.19%   |
| 1400x1050          | 7         | 0.15%   |
| 4480x1440          | 6         | 0.13%   |
| 1920x1280          | 5         | 0.11%   |
| 5760x1080          | 4         | 0.09%   |
| 2736x1824          | 4         | 0.09%   |
| 2048x1152          | 4         | 0.09%   |
| 3840x1600          | 3         | 0.06%   |
| 3200x1800 (QHD+)   | 3         | 0.06%   |
| 3200x1080          | 3         | 0.06%   |
| 1800x1200          | 3         | 0.06%   |
| 1024x576           | 3         | 0.06%   |
| 5760x2160          | 2         | 0.04%   |
| 5360x1440          | 2         | 0.04%   |
| 3840x1100          | 2         | 0.04%   |
| 3360x1050          | 2         | 0.04%   |
| 2256x1504          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 980       | 20.23%  |
| 15      | 902       | 18.62%  |
| 14      | 362       | 7.47%   |
| 24      | 338       | 6.98%   |
| 27      | 277       | 5.72%   |
| 23      | 269       | 5.55%   |
| 11      | 245       | 5.06%   |
| 17      | 230       | 4.75%   |
| 21      | 209       | 4.31%   |
| Unknown | 141       | 2.91%   |
| 19      | 126       | 2.6%    |
| 12      | 112       | 2.31%   |
| 18      | 86        | 1.78%   |
| 31      | 81        | 1.67%   |
| 22      | 63        | 1.3%    |
| 20      | 52        | 1.07%   |
| 10      | 50        | 1.03%   |
| 142     | 44        | 0.91%   |
| 34      | 44        | 0.91%   |
| 84      | 28        | 0.58%   |
| 32      | 21        | 0.43%   |
| 72      | 20        | 0.41%   |
| 25      | 19        | 0.39%   |
| 16      | 18        | 0.37%   |
| 54      | 14        | 0.29%   |
| 40      | 12        | 0.25%   |
| 29      | 11        | 0.23%   |
| 26      | 11        | 0.23%   |
| 28      | 9         | 0.19%   |
| 52      | 7         | 0.14%   |
| 33      | 6         | 0.12%   |
| 48      | 5         | 0.1%    |
| 65      | 4         | 0.08%   |
| 55      | 4         | 0.08%   |
| 49      | 4         | 0.08%   |
| 47      | 4         | 0.08%   |
| 46      | 4         | 0.08%   |
| 43      | 4         | 0.08%   |
| 42      | 4         | 0.08%   |
| 8       | 4         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1567      | 32.83%  |
| 201-300        | 1158      | 24.26%  |
| 501-600        | 819       | 17.16%  |
| 401-500        | 450       | 9.43%   |
| 351-400        | 251       | 5.26%   |
| Unknown        | 141       | 2.95%   |
| 601-700        | 138       | 2.89%   |
| 701-800        | 71        | 1.49%   |
| 1501-2000      | 50        | 1.05%   |
| 1001-1500      | 50        | 1.05%   |
| More than 2000 | 44        | 0.92%   |
| 801-900        | 22        | 0.46%   |
| 901-1000       | 7         | 0.15%   |
| 101-200        | 5         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3070      | 68.97%  |
| 16/10   | 865       | 19.43%  |
| 5/4     | 162       | 3.64%   |
| Unknown | 113       | 2.54%   |
| 4/3     | 76        | 1.71%   |
| 21/9    | 55        | 1.24%   |
| 1.00    | 46        | 1.03%   |
| 3/2     | 38        | 0.85%   |
| 6/5     | 10        | 0.22%   |
| 2.65    | 5         | 0.11%   |
| 32/9    | 4         | 0.09%   |
| 3.40    | 2         | 0.04%   |
| 3.73    | 1         | 0.02%   |
| 3.20    | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |
| 1.96    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 1015      | 21.15%  |
| 101-110        | 897       | 18.69%  |
| 201-250        | 690       | 14.38%  |
| 71-80          | 326       | 6.79%   |
| 301-350        | 285       | 5.94%   |
| 51-60          | 247       | 5.15%   |
| 151-200        | 244       | 5.08%   |
| 351-500        | 166       | 3.46%   |
| 141-150        | 153       | 3.19%   |
| Unknown        | 141       | 2.94%   |
| 251-300        | 132       | 2.75%   |
| More than 1000 | 131       | 2.73%   |
| 121-130        | 122       | 2.54%   |
| 61-70          | 105       | 2.19%   |
| 41-50          | 50        | 1.04%   |
| 501-1000       | 39        | 0.81%   |
| 131-140        | 25        | 0.52%   |
| 111-120        | 14        | 0.29%   |
| 91-100         | 12        | 0.25%   |
| 1-40           | 5         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 1400      | 29.84%  |
| 51-100        | 1321      | 28.15%  |
| 101-120       | 1307      | 27.86%  |
| 161-240       | 345       | 7.35%   |
| Unknown       | 141       | 3.01%   |
| 1-50          | 115       | 2.45%   |
| More than 240 | 63        | 1.34%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3694      | 65.3%   |
| 0     | 1270      | 22.45%  |
| 2     | 620       | 10.96%  |
| 3     | 70        | 1.24%   |
| 4     | 2         | 0.04%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2596      | 32.5%   |
| Intel                             | 2463      | 30.83%  |
| Qualcomm Atheros                  | 726       | 9.09%   |
| Broadcom                          | 666       | 8.34%   |
| Nvidia                            | 364       | 4.56%   |
| Broadcom Limited                  | 245       | 3.07%   |
| Marvell Technology Group          | 131       | 1.64%   |
| Ralink Technology                 | 66        | 0.83%   |
| MediaTek                          | 64        | 0.8%    |
| TP-Link                           | 58        | 0.73%   |
| Ralink                            | 47        | 0.59%   |
| ASIX Electronics                  | 44        | 0.55%   |
| Samsung Electronics               | 35        | 0.44%   |
| Dell                              | 24        | 0.3%    |
| Microchip Technology              | 23        | 0.29%   |
| Sierra Wireless                   | 22        | 0.28%   |
| Qualcomm                          | 19        | 0.24%   |
| Qualcomm Atheros Communications   | 18        | 0.23%   |
| Huawei Technologies               | 18        | 0.23%   |
| DisplayLink                       | 18        | 0.23%   |
| Xiaomi                            | 17        | 0.21%   |
| Mellanox Technologies             | 16        | 0.2%    |
| NetGear                           | 15        | 0.19%   |
| Lenovo                            | 13        | 0.16%   |
| D-Link System                     | 13        | 0.16%   |
| Aquantia                          | 13        | 0.16%   |
| Ericsson Business Mobile Networks | 12        | 0.15%   |
| Dresden Elektronik                | 12        | 0.15%   |
| D-Link                            | 12        | 0.15%   |
| ASUSTek Computer                  | 11        | 0.14%   |
| Microsoft                         | 10        | 0.13%   |
| Hewlett-Packard                   | 10        | 0.13%   |
| American Megatrends               | 10        | 0.13%   |
| JMicron Technology                | 9         | 0.11%   |
| VIA Technologies                  | 8         | 0.1%    |
| ICS Advent                        | 8         | 0.1%    |
| Fibocom                           | 7         | 0.09%   |
| Edimax Technology                 | 7         | 0.09%   |
| OPPO                              | 6         | 0.08%   |
| Cypress Semiconductor             | 6         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 1859      | 19.96%  |
| Nvidia MCP79 Ethernet                                                                 | 318       | 3.41%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 312       | 3.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 267       | 2.87%   |
| Intel Wi-Fi 6 AX201                                                                   | 242       | 2.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 181       | 1.94%   |
| Intel Wi-Fi 6 AX200                                                                   | 176       | 1.89%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 159       | 1.71%   |
| Intel Wireless 7260                                                                   | 148       | 1.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 139       | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 139       | 1.49%   |
| Intel Wireless 8265 / 8275                                                            | 136       | 1.46%   |
| Intel Ethernet Connection (13) I219-V                                                 | 134       | 1.44%   |
| Intel Wireless 7265                                                                   | 128       | 1.37%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 87        | 0.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 86        | 0.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 84        | 0.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 80        | 0.86%   |
| Intel I211 Gigabit Network Connection                                                 | 78        | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 78        | 0.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 76        | 0.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 72        | 0.77%   |
| Intel I210 Gigabit Network Connection                                                 | 72        | 0.77%   |
| Intel Wireless 8260                                                                   | 71        | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 67        | 0.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 67        | 0.72%   |
| Intel Wireless 3165                                                                   | 64        | 0.69%   |
| Intel Ethernet Controller I225-V                                                      | 60        | 0.64%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 60        | 0.64%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 59        | 0.63%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 57        | 0.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 54        | 0.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 53        | 0.57%   |
| Intel Ethernet Connection (4) I219-V                                                  | 50        | 0.54%   |
| Intel Ethernet Connection (2) I219-V                                                  | 50        | 0.54%   |
| Intel Ethernet Connection I217-LM                                                     | 49        | 0.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 43        | 0.46%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 43        | 0.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 43        | 0.46%   |
| Intel 82579V Gigabit Network Connection                                               | 42        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1770      | 45.31%  |
| Qualcomm Atheros                      | 593       | 15.18%  |
| Broadcom                              | 494       | 12.65%  |
| Realtek Semiconductor                 | 490       | 12.54%  |
| Broadcom Limited                      | 200       | 5.12%   |
| Ralink Technology                     | 66        | 1.69%   |
| Ralink                                | 47        | 1.2%    |
| MediaTek                              | 47        | 1.2%    |
| TP-Link                               | 40        | 1.02%   |
| Sierra Wireless                       | 22        | 0.56%   |
| Qualcomm Atheros Communications       | 18        | 0.46%   |
| NetGear                               | 15        | 0.38%   |
| Dell                                  | 13        | 0.33%   |
| ASUSTek Computer                      | 11        | 0.28%   |
| D-Link                                | 10        | 0.26%   |
| Qualcomm                              | 7         | 0.18%   |
| Microsoft                             | 7         | 0.18%   |
| Fibocom                               | 7         | 0.18%   |
| Edimax Technology                     | 7         | 0.18%   |
| D-Link System                         | 7         | 0.18%   |
| Marvell Technology Group              | 6         | 0.15%   |
| Belkin Components                     | 6         | 0.15%   |
| IMC Networks                          | 3         | 0.08%   |
| Gemtek                                | 3         | 0.08%   |
| Ericsson Business Mobile Networks     | 3         | 0.08%   |
| Wilocity                              | 2         | 0.05%   |
| Linksys                               | 2         | 0.05%   |
| AVM                                   | 2         | 0.05%   |
| Z-Com                                 | 1         | 0.03%   |
| Winbond Electronics                   | 1         | 0.03%   |
| Sitecom Europe                        | 1         | 0.03%   |
| Micro Star International              | 1         | 0.03%   |
| CyberTAN Technology                   | 1         | 0.03%   |
| BUFFALO                               | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |
| 3Com                                  | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 312       | 7.96%   |
| Intel Wi-Fi 6 AX201                                                                   | 242       | 6.18%   |
| Intel Wi-Fi 6 AX200                                                                   | 176       | 4.49%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 159       | 4.06%   |
| Intel Wireless 7260                                                                   | 148       | 3.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 139       | 3.55%   |
| Intel Wireless 8265 / 8275                                                            | 136       | 3.47%   |
| Intel Wireless 7265                                                                   | 128       | 3.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 86        | 2.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 84        | 2.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 80        | 2.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 78        | 1.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 76        | 1.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 72        | 1.84%   |
| Intel Wireless 8260                                                                   | 71        | 1.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 67        | 1.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 67        | 1.71%   |
| Intel Wireless 3165                                                                   | 64        | 1.63%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 60        | 1.53%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 57        | 1.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 54        | 1.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 53        | 1.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 43        | 1.1%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 43        | 1.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 43        | 1.1%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 37        | 0.94%   |
| Intel Wireless-AC 9260                                                                | 35        | 0.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 29        | 0.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 28        | 0.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 28        | 0.71%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 28        | 0.71%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 27        | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 27        | 0.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 26        | 0.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 26        | 0.66%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 26        | 0.66%   |
| Intel Wireless 3160                                                                   | 25        | 0.64%   |
| Realtek 802.11ac NIC                                                                  | 23        | 0.59%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 23        | 0.59%   |
| Intel Centrino Ultimate-N 6300                                                        | 22        | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2399      | 46.86%  |
| Intel                            | 1417      | 27.68%  |
| Nvidia                           | 364       | 7.11%   |
| Broadcom                         | 211       | 4.12%   |
| Qualcomm Atheros                 | 197       | 3.85%   |
| Marvell Technology Group         | 126       | 2.46%   |
| Broadcom Limited                 | 48        | 0.94%   |
| ASIX Electronics                 | 44        | 0.86%   |
| Samsung Electronics              | 35        | 0.68%   |
| Microchip Technology             | 23        | 0.45%   |
| TP-Link                          | 18        | 0.35%   |
| DisplayLink                      | 18        | 0.35%   |
| Xiaomi                           | 17        | 0.33%   |
| MediaTek                         | 16        | 0.31%   |
| Mellanox Technologies            | 14        | 0.27%   |
| Lenovo                           | 13        | 0.25%   |
| Aquantia                         | 13        | 0.25%   |
| Huawei Technologies              | 12        | 0.23%   |
| Qualcomm                         | 11        | 0.21%   |
| American Megatrends              | 10        | 0.2%    |
| JMicron Technology               | 9         | 0.18%   |
| VIA Technologies                 | 8         | 0.16%   |
| ICS Advent                       | 8         | 0.16%   |
| OPPO                             | 6         | 0.12%   |
| D-Link System                    | 6         | 0.12%   |
| Cypress Semiconductor            | 6         | 0.12%   |
| Standard Microsystems            | 5         | 0.1%    |
| Silicon Integrated Systems [SiS] | 5         | 0.1%    |
| ZTE WCDMA Technologies MSM       | 4         | 0.08%   |
| Attansic Technology              | 4         | 0.08%   |
| 3Com                             | 4         | 0.08%   |
| NetXen Incorporated              | 3         | 0.06%   |
| Motorola PCS                     | 3         | 0.06%   |
| Microsoft                        | 3         | 0.06%   |
| IBM                              | 3         | 0.06%   |
| Hewlett-Packard                  | 3         | 0.06%   |
| Apple                            | 3         | 0.06%   |
| Spreadtrum Communications        | 2         | 0.04%   |
| QLogic                           | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1859      | 35.24%  |
| Nvidia MCP79 Ethernet                                             | 318       | 6.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 267       | 5.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 181       | 3.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 139       | 2.63%   |
| Intel Ethernet Connection (13) I219-V                             | 134       | 2.54%   |
| Realtek RTL8125 2.5GbE Controller                                 | 87        | 1.65%   |
| Intel I211 Gigabit Network Connection                             | 78        | 1.48%   |
| Intel I210 Gigabit Network Connection                             | 72        | 1.36%   |
| Intel Ethernet Controller I225-V                                  | 60        | 1.14%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 59        | 1.12%   |
| Intel Ethernet Connection (4) I219-V                              | 50        | 0.95%   |
| Intel Ethernet Connection (2) I219-V                              | 50        | 0.95%   |
| Intel Ethernet Connection I217-LM                                 | 49        | 0.93%   |
| Intel 82579V Gigabit Network Connection                           | 42        | 0.8%    |
| Intel 82574L Gigabit Network Connection                           | 40        | 0.76%   |
| Intel Ethernet Connection (14) I219-V                             | 38        | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 37        | 0.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 35        | 0.66%   |
| Intel Ethernet Connection I218-LM                                 | 34        | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                             | 34        | 0.64%   |
| ASIX AX88179 Gigabit Ethernet                                     | 34        | 0.64%   |
| Intel I350 Gigabit Network Connection                             | 32        | 0.61%   |
| Intel Ethernet Connection I219-LM                                 | 32        | 0.61%   |
| Intel Ethernet Connection (7) I219-V                              | 31        | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 29        | 0.55%   |
| Intel Ethernet Connection (6) I219-V                              | 29        | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                             | 28        | 0.53%   |
| Intel Ethernet Connection (10) I219-V                             | 28        | 0.53%   |
| Nvidia MCP61 Ethernet                                             | 27        | 0.51%   |
| Intel Ethernet Connection I217-V                                  | 26        | 0.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 25        | 0.47%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 25        | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 23        | 0.44%   |
| Intel 82577LM Gigabit Network Connection                          | 23        | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 21        | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 20        | 0.38%   |
| Intel Ethernet Connection (5) I219-LM                             | 20        | 0.38%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 20        | 0.38%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 19        | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4784      | 55.33%  |
| WiFi     | 3746      | 43.33%  |
| Modem    | 106       | 1.23%   |
| Unknown  | 10        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2899      | 52.19%  |
| WiFi     | 2656      | 47.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2843      | 50.9%   |
| 1     | 2277      | 40.77%  |
| 0     | 221       | 3.96%   |
| 3     | 147       | 2.63%   |
| 4     | 50        | 0.9%    |
| 6     | 17        | 0.3%    |
| 5     | 15        | 0.27%   |
| 8     | 7         | 0.13%   |
| 20    | 2         | 0.04%   |
| 7     | 2         | 0.04%   |
| 14    | 1         | 0.02%   |
| 13    | 1         | 0.02%   |
| 12    | 1         | 0.02%   |
| 9     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4623      | 82.39%  |
| Yes  | 988       | 17.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1448      | 45.45%  |
| Apple                           | 601       | 18.86%  |
| Realtek Semiconductor           | 238       | 7.47%   |
| Qualcomm Atheros Communications | 209       | 6.56%   |
| Cambridge Silicon Radio         | 141       | 4.43%   |
| Broadcom                        | 124       | 3.89%   |
| IMC Networks                    | 102       | 3.2%    |
| Lite-On Technology              | 90        | 2.82%   |
| Foxconn / Hon Hai               | 57        | 1.79%   |
| ASUSTek Computer                | 37        | 1.16%   |
| Dell                            | 34        | 1.07%   |
| Hewlett-Packard                 | 23        | 0.72%   |
| Realtek                         | 15        | 0.47%   |
| MediaTek                        | 13        | 0.41%   |
| Toshiba                         | 11        | 0.35%   |
| Ralink                          | 11        | 0.35%   |
| Ralink Technology               | 4         | 0.13%   |
| Foxconn International           | 4         | 0.13%   |
| TP-Link                         | 3         | 0.09%   |
| Taiyo Yuden                     | 3         | 0.09%   |
| Alps Electric                   | 3         | 0.09%   |
| Fujitsu                         | 2         | 0.06%   |
| Edimax Technology               | 2         | 0.06%   |
| Belkin Components               | 2         | 0.06%   |
| USI                             | 1         | 0.03%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Microsoft                       | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Marvell Semiconductor           | 1         | 0.03%   |
| Integrated System Solution      | 1         | 0.03%   |
| Dynex                           | 1         | 0.03%   |
| Unknown                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 548       | 17.19%  |
| Intel AX201 Bluetooth                               | 369       | 11.57%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 317       | 9.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 194       | 6.09%   |
| Apple Bluetooth USB Host Controller                 | 175       | 5.49%   |
| Intel AX200 Bluetooth                               | 168       | 5.27%   |
| Realtek Bluetooth Radio                             | 154       | 4.83%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 141       | 4.42%   |
| Qualcomm Atheros  Bluetooth Device                  | 126       | 3.95%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 2.38%   |
| Realtek  Bluetooth 4.2 Adapter                      | 55        | 1.73%   |
| Intel Wireless-AC 3168 Bluetooth                    | 42        | 1.32%   |
| Intel AX210 Bluetooth                               | 35        | 1.1%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 34        | 1.07%   |
| IMC Networks Bluetooth Radio                        | 32        | 1%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 30        | 0.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 28        | 0.88%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 27        | 0.85%   |
| Lite-On Bluetooth Device                            | 26        | 0.82%   |
| Apple Bluetooth Host Controller                     | 26        | 0.82%   |
| IMC Networks Bluetooth Device                       | 24        | 0.75%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 22        | 0.69%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 21        | 0.66%   |
| Intel Bluetooth Device                              | 21        | 0.66%   |
| IMC Networks Wireless_Device                        | 19        | 0.6%    |
| Foxconn / Hon Hai Bluetooth Device                  | 19        | 0.6%    |
| Broadcom BCM2045B (BDC-2.1)                         | 19        | 0.6%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 17        | 0.53%   |
| Foxconn / Hon Hai Wireless_Device                   | 16        | 0.5%    |
| Realtek RTL8723B Bluetooth                          | 15        | 0.47%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 15        | 0.47%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 14        | 0.44%   |
| Dell BCM20702A0 Bluetooth Module                    | 13        | 0.41%   |
| Realtek 802.11ac WLAN Adapter                       | 12        | 0.38%   |
| MediaTek Wireless_Device                            | 12        | 0.38%   |
| Ralink RT3290 Bluetooth                             | 11        | 0.35%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 11        | 0.35%   |
| HP Broadcom 2070 Bluetooth Combo                    | 10        | 0.31%   |
| Lite-On Wireless_Device                             | 9         | 0.28%   |
| Lite-On Atheros AR3012 Bluetooth                    | 9         | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3806      | 56.47%  |
| Nvidia                                       | 1236      | 18.34%  |
| AMD                                          | 1139      | 16.9%   |
| C-Media Electronics                          | 86        | 1.28%   |
| Logitech                                     | 42        | 0.62%   |
| Creative Labs                                | 28        | 0.42%   |
| Generalplus Technology                       | 24        | 0.36%   |
| Texas Instruments                            | 23        | 0.34%   |
| ASUSTek Computer                             | 23        | 0.34%   |
| Realtek Semiconductor                        | 17        | 0.25%   |
| Plantronics                                  | 16        | 0.24%   |
| Lenovo                                       | 16        | 0.24%   |
| Creative Technology                          | 16        | 0.24%   |
| GN Netcom                                    | 15        | 0.22%   |
| VIA Technologies                             | 13        | 0.19%   |
| Focusrite-Novation                           | 13        | 0.19%   |
| JMTek                                        | 12        | 0.18%   |
| Kingston Technology                          | 11        | 0.16%   |
| RODE Microphones                             | 8         | 0.12%   |
| Micro Star International                     | 8         | 0.12%   |
| Hewlett-Packard                              | 8         | 0.12%   |
| Zoran Co. Personal Media Division (Nogatech) | 7         | 0.1%    |
| SteelSeries ApS                              | 7         | 0.1%    |
| Razer USA                                    | 7         | 0.1%    |
| KTMicro                                      | 7         | 0.1%    |
| GYROCOM C&C                                  | 7         | 0.1%    |
| Dell                                         | 6         | 0.09%   |
| BEHRINGER International                      | 6         | 0.09%   |
| Yamaha                                       | 5         | 0.07%   |
| Silicon Integrated Systems [SiS]             | 5         | 0.07%   |
| Sennheiser Communications                    | 5         | 0.07%   |
| Microsoft                                    | 5         | 0.07%   |
| Cambridge Silicon Radio                      | 5         | 0.07%   |
| Unknown                                      | 4         | 0.06%   |
| Tenx Technology                              | 4         | 0.06%   |
| Blue Microphones                             | 4         | 0.06%   |
| Apple                                        | 4         | 0.06%   |
| Zhaoxin                                      | 3         | 0.04%   |
| XMOS                                         | 3         | 0.04%   |
| ULi Electronics                              | 3         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 389       | 4.87%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 324       | 4.06%   |
| Nvidia MCP79 High Definition Audio                                                                | 320       | 4.01%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 300       | 3.76%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 294       | 3.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 283       | 3.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 261       | 3.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 244       | 3.06%   |
| Intel Broadwell-U Audio Controller                                                                | 228       | 2.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 223       | 2.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 212       | 2.66%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 188       | 2.36%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 163       | 2.04%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 158       | 1.98%   |
| Intel Cannon Lake PCH cAVS                                                                        | 154       | 1.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 147       | 1.84%   |
| Intel 200 Series PCH HD Audio                                                                     | 137       | 1.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 131       | 1.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 121       | 1.52%   |
| Intel Comet Lake PCH cAVS                                                                         | 109       | 1.37%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 106       | 1.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 101       | 1.27%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 93        | 1.17%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 91        | 1.14%   |
| Intel 8 Series HD Audio Controller                                                                | 91        | 1.14%   |
| AMD FCH Azalia Controller                                                                         | 91        | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 87        | 1.09%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 84        | 1.05%   |
| AMD Kabini HDMI/DP Audio                                                                          | 84        | 1.05%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 81        | 1.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 78        | 0.98%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 75        | 0.94%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 75        | 0.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 70        | 0.88%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 69        | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 67        | 0.84%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 63        | 0.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 58        | 0.73%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 57        | 0.71%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 55        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1168      | 21.65%  |
| SK hynix            | 1139      | 21.12%  |
| Kingston            | 568       | 10.53%  |
| Unknown             | 501       | 9.29%   |
| Crucial             | 458       | 8.49%   |
| Micron Technology   | 409       | 7.58%   |
| Corsair             | 189       | 3.5%    |
| G.Skill             | 123       | 2.28%   |
| Elpida              | 105       | 1.95%   |
| A-DATA Technology   | 92        | 1.71%   |
| Ramaxel Technology  | 70        | 1.3%    |
| Unknown             | 69        | 1.28%   |
| Patriot             | 68        | 1.26%   |
| Unknown (ABCD)      | 50        | 0.93%   |
| Nanya Technology    | 49        | 0.91%   |
| Team                | 32        | 0.59%   |
| GOODRAM             | 27        | 0.5%    |
| Smart               | 25        | 0.46%   |
| Transcend           | 21        | 0.39%   |
| Hikvision           | 21        | 0.39%   |
| AMD                 | 20        | 0.37%   |
| Hewlett-Packard     | 11        | 0.2%    |
| Apacer              | 10        | 0.19%   |
| Qimonda             | 8         | 0.15%   |
| Timetec             | 6         | 0.11%   |
| Silicon Power       | 6         | 0.11%   |
| PNY                 | 6         | 0.11%   |
| GeIL                | 6         | 0.11%   |
| ASint Technology    | 6         | 0.11%   |
| Goldkey             | 5         | 0.09%   |
| 48spaces            | 5         | 0.09%   |
| Wilk                | 4         | 0.07%   |
| Unifosa             | 4         | 0.07%   |
| Toshiba             | 4         | 0.07%   |
| Kllisre             | 4         | 0.07%   |
| Infineon            | 4         | 0.07%   |
| Avant               | 4         | 0.07%   |
| Teikon              | 3         | 0.06%   |
| Smart Brazil        | 3         | 0.06%   |
| Neo Forza           | 3         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 258       | 4.49%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 142       | 2.47%   |
| Unknown                                                          | 69        | 1.2%    |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 1.18%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 63        | 1.1%    |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 61        | 1.06%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 44        | 0.77%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 41        | 0.71%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 39        | 0.68%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s            | 35        | 0.61%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 32        | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 32        | 0.56%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s            | 31        | 0.54%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.5%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 29        | 0.5%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 29        | 0.5%    |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s           | 28        | 0.49%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 26        | 0.45%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 26        | 0.45%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 26        | 0.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 26        | 0.45%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 25        | 0.43%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 24        | 0.42%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 24        | 0.42%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s             | 24        | 0.42%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 22        | 0.38%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 22        | 0.38%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 21        | 0.37%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 21        | 0.37%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 21        | 0.37%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 20        | 0.35%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s          | 20        | 0.35%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 19        | 0.33%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 18        | 0.31%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s            | 18        | 0.31%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 18        | 0.31%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 18        | 0.31%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 17        | 0.3%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 17        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 2012      | 42.05%  |
| DDR3         | 1581      | 33.04%  |
| DDR2         | 567       | 11.85%  |
| SDRAM        | 165       | 3.45%   |
| Unknown      | 142       | 2.97%   |
| LPDDR4       | 131       | 2.74%   |
| LPDDR3       | 103       | 2.15%   |
| DDR          | 54        | 1.13%   |
| DDR5         | 17        | 0.36%   |
| DRAM         | 8         | 0.17%   |
| LPDDR5       | 4         | 0.08%   |
| DDR2 FB-DIMM | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2731      | 57.22%  |
| DIMM         | 1777      | 37.23%  |
| Row Of Chips | 181       | 3.79%   |
| Unknown      | 48        | 1.01%   |
| Chip         | 27        | 0.57%   |
| FB-DIMM      | 7         | 0.15%   |
| RIMM         | 2         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 1605      | 31.21%  |
| 4096    | 1253      | 24.37%  |
| 2048    | 810       | 15.75%  |
| 16384   | 602       | 11.71%  |
| 1024    | 588       | 11.44%  |
| 32768   | 200       | 3.89%   |
| 512     | 56        | 1.09%   |
| 256     | 17        | 0.33%   |
| 65536   | 7         | 0.14%   |
| 1536    | 1         | 0.02%   |
| 384     | 1         | 0.02%   |
| 128     | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1081      | 21.17%  |
| 3200    | 726       | 14.22%  |
| 2667    | 634       | 12.42%  |
| 800     | 422       | 8.26%   |
| 1333    | 355       | 6.95%   |
| 2400    | 315       | 6.17%   |
| 2133    | 207       | 4.05%   |
| 667     | 187       | 3.66%   |
| Unknown | 144       | 2.82%   |
| 1334    | 104       | 2.04%   |
| 3600    | 81        | 1.59%   |
| 2666    | 73        | 1.43%   |
| 1867    | 69        | 1.35%   |
| 1866    | 65        | 1.27%   |
| 1067    | 62        | 1.21%   |
| 1066    | 49        | 0.96%   |
| 4267    | 43        | 0.84%   |
| 3266    | 42        | 0.82%   |
| 3400    | 32        | 0.63%   |
| 2933    | 30        | 0.59%   |
| 3000    | 29        | 0.57%   |
| 3733    | 26        | 0.51%   |
| 2866    | 26        | 0.51%   |
| 533     | 24        | 0.47%   |
| 4199    | 21        | 0.41%   |
| 3466    | 20        | 0.39%   |
| 2048    | 17        | 0.33%   |
| 1800    | 17        | 0.33%   |
| 4800    | 16        | 0.31%   |
| 400     | 16        | 0.31%   |
| 333     | 12        | 0.24%   |
| 3800    | 11        | 0.22%   |
| 266     | 11        | 0.22%   |
| 3866    | 10        | 0.2%    |
| 975     | 9         | 0.18%   |
| 8400    | 8         | 0.16%   |
| 3534    | 8         | 0.16%   |
| 4333    | 7         | 0.14%   |
| 4266    | 7         | 0.14%   |
| 3066    | 6         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 36        | 33.64%  |
| Brother Industries     | 21        | 19.63%  |
| Canon                  | 13        | 12.15%  |
| Xerox                  | 8         | 7.48%   |
| Samsung Electronics    | 7         | 6.54%   |
| Seiko Epson            | 5         | 4.67%   |
| Dymo-CoStar            | 4         | 3.74%   |
| Prolific Technology    | 3         | 2.8%    |
| Zebra                  | 2         | 1.87%   |
| Pantum                 | 2         | 1.87%   |
| STMicroelectronics     | 1         | 0.93%   |
| Panasonic (Matsushita) | 1         | 0.93%   |
| Kyocera                | 1         | 0.93%   |
| Konica Minolta         | 1         | 0.93%   |
| GODEX INTERNATIONAL    | 1         | 0.93%   |
| Apple                  | 1         | 0.93%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Xerox B205                                                            | 7         | 6.54%   |
| Prolific PL2305 Parallel Port                                         | 3         | 2.8%    |
| HP LaserJet M101-M106                                                 | 3         | 2.8%    |
| HP LaserJet 1200                                                      | 3         | 2.8%    |
| HP LaserJet 1020                                                      | 3         | 2.8%    |
| Samsung ML-1660 Series                                                | 2         | 1.87%   |
| HP LaserJet P1005                                                     | 2         | 1.87%   |
| HP ENVY 4520 series                                                   | 2         | 1.87%   |
| HP DeskJet 2620 All-in-One Printer                                    | 2         | 1.87%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                                | 2         | 1.87%   |
| Canon PIXMA MX920 Series                                              | 2         | 1.87%   |
| Canon MF4410                                                          | 2         | 1.87%   |
| Canon LiDE 400                                                        | 2         | 1.87%   |
| Canon G3010 series                                                    | 2         | 1.87%   |
| Brother PT-9500PC                                                     | 2         | 1.87%   |
| Zebra ZTC ZP 500 (ZPL)                                                | 1         | 0.93%   |
| Zebra ZTC ZD420-203dpi ZPL                                            | 1         | 0.93%   |
| Xerox Phaser 3250                                                     | 1         | 0.93%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 1         | 0.93%   |
| Seiko Epson XP-200 Series                                             | 1         | 0.93%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 0.93%   |
| Seiko Epson ET-2850 Series                                            | 1         | 0.93%   |
| Seiko Epson ET-2710 Series                                            | 1         | 0.93%   |
| Seiko Epson ET-2700 Series                                            | 1         | 0.93%   |
| Samsung SCX-4650 4x21S Series                                         | 1         | 0.93%   |
| Samsung SCX-3200 Series                                               | 1         | 0.93%   |
| Samsung ML-216x Series Laser Printer                                  | 1         | 0.93%   |
| Samsung ML-2010P Mono Laser Printer                                   | 1         | 0.93%   |
| Samsung ML-1520 Laser Printer                                         | 1         | 0.93%   |
| Pantum P2500W series                                                  | 1         | 0.93%   |
| Pantum M6500-series                                                   | 1         | 0.93%   |
| Panasonic (Matsushita) KX-MB1500RU                                    | 1         | 0.93%   |
| Kyocera ECOSYS M5521cdn                                               | 1         | 0.93%   |
| Konica Minolta bizhub 4402P                                           | 1         | 0.93%   |
| HP Officejet J4500 series                                             | 1         | 0.93%   |
| HP Officejet 7110 series                                              | 1         | 0.93%   |
| HP LaserJet Pro M404-M405                                             | 1         | 0.93%   |
| HP LaserJet Pro M148-M149                                             | 1         | 0.93%   |
| HP LaserJet P2055 series                                              | 1         | 0.93%   |
| HP Laserjet P1505                                                     | 1         | 0.93%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 15        | 55.56%  |
| Seiko Epson     | 7         | 25.93%  |
| Hewlett-Packard | 3         | 11.11%  |
| AGFA-Gevaert NV | 2         | 7.41%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                       | 4         | 14.81%  |
| Canon CanoScan N670U/N676U/LiDE 20                            | 3         | 11.11%  |
| Canon CanoScan LiDE 120                                       | 2         | 7.41%   |
| Canon CanoScan LiDE 110                                       | 2         | 7.41%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 2         | 7.41%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 1         | 3.7%    |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1         | 3.7%    |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]      | 1         | 3.7%    |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                 | 1         | 3.7%    |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 3.7%    |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                 | 1         | 3.7%    |
| Seiko Epson GT-7700U [Perfection 1240U]                       | 1         | 3.7%    |
| HP ScanJet Pro 2500 f1                                        | 1         | 3.7%    |
| HP ScanJet 3970c                                              | 1         | 3.7%    |
| HP Scanjet 300                                                | 1         | 3.7%    |
| Canon CanoScan LIDE 25                                        | 1         | 3.7%    |
| Canon CanoScan LiDE 210                                       | 1         | 3.7%    |
| Canon CanoScan 8800F                                          | 1         | 3.7%    |
| Canon CanoScan 5600F                                          | 1         | 3.7%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 613       | 22.52%  |
| Acer                                   | 298       | 10.95%  |
| IMC Networks                           | 255       | 9.37%   |
| Quanta                                 | 210       | 7.71%   |
| Microdia                               | 186       | 6.83%   |
| Realtek Semiconductor                  | 168       | 6.17%   |
| Logitech                               | 153       | 5.62%   |
| Sunplus Innovation Technology          | 103       | 3.78%   |
| Bison Electronics                      | 77        | 2.83%   |
| Cheng Uei Precision Industry (Foxlink) | 74        | 2.72%   |
| Apple                                  | 69        | 2.53%   |
| Suyin                                  | 62        | 2.28%   |
| Lite-On Technology                     | 52        | 1.91%   |
| Syntek                                 | 50        | 1.84%   |
| Luxvisions Innotech Limited            | 35        | 1.29%   |
| Silicon Motion                         | 23        | 0.84%   |
| Alcor Micro                            | 23        | 0.84%   |
| Lenovo                                 | 20        | 0.73%   |
| Z-Star Microelectronics                | 15        | 0.55%   |
| Microsoft                              | 14        | 0.51%   |
| Generalplus Technology                 | 14        | 0.51%   |
| Sonix Technology                       | 12        | 0.44%   |
| Samsung Electronics                    | 12        | 0.44%   |
| Ricoh                                  | 12        | 0.44%   |
| DLEQNA19IFK6G2                         | 12        | 0.44%   |
| Primax Electronics                     | 10        | 0.37%   |
| Creative Technology                    | 10        | 0.37%   |
| Genesys Logic                          | 9         | 0.33%   |
| KYE Systems (Mouse Systems)            | 7         | 0.26%   |
| Jieli Technology                       | 7         | 0.26%   |
| Importek                               | 7         | 0.26%   |
| ARC International                      | 7         | 0.26%   |
| Unknown                                | 5         | 0.18%   |
| SunplusIT                              | 5         | 0.18%   |
| Intel                                  | 5         | 0.18%   |
| ALi                                    | 5         | 0.18%   |
| Y Media                                | 4         | 0.15%   |
| MacroSilicon                           | 4         | 0.15%   |
| icSpring                               | 4         | 0.15%   |
| GEMBIRD                                | 4         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 197       | 7.18%   |
| Acer Integrated Camera                   | 137       | 4.99%   |
| Microdia Integrated_Webcam_HD            | 84        | 3.06%   |
| IMC Networks Integrated Camera           | 81        | 2.95%   |
| Bison Integrated 5M Camera               | 73        | 2.66%   |
| Quanta Chromebook HD Camera              | 67        | 2.44%   |
| Realtek Integrated_Webcam_HD             | 60        | 2.19%   |
| IMC Networks USB2.0 HD UVC WebCam        | 58        | 2.11%   |
| Acer BisonCam, NB Pro                    | 54        | 1.97%   |
| Chicony HD Webcam                        | 50        | 1.82%   |
| Logitech Webcam C270                     | 47        | 1.71%   |
| Chicony Integrated 5M Camera             | 43        | 1.57%   |
| Sunplus Integrated_Webcam_HD             | 34        | 1.24%   |
| Chicony USB2.0 HD UVC WebCam             | 33        | 1.2%    |
| Chicony HP HD Camera                     | 28        | 1.02%   |
| Syntek Integrated Camera                 | 27        | 0.98%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 27        | 0.98%   |
| Quanta HP TrueVision HD Camera           | 24        | 0.87%   |
| Quanta HD User Facing                    | 24        | 0.87%   |
| Apple Built-in iSight                    | 24        | 0.87%   |
| Quanta VGA WebCam                        | 21        | 0.77%   |
| Apple iPhone 5/5C/5S/6/SE                | 20        | 0.73%   |
| Acer SunplusIT Integrated Camera         | 20        | 0.73%   |
| Microdia Integrated Webcam               | 19        | 0.69%   |
| Realtek USB Camera                       | 18        | 0.66%   |
| Quanta HP HD Camera                      | 18        | 0.66%   |
| Logitech HD Pro Webcam C920              | 18        | 0.66%   |
| Lite-On Integrated Camera                | 18        | 0.66%   |
| Chicony Integrated Camera (1280x720@30)  | 17        | 0.62%   |
| Chicony HP TrueVision HD Camera          | 16        | 0.58%   |
| Apple FaceTime HD Camera (Built-in)      | 16        | 0.58%   |
| Luxvisions Innotech Limited HP HD Camera | 15        | 0.55%   |
| Lite-On HP HD Camera                     | 15        | 0.55%   |
| Chicony HD User Facing                   | 15        | 0.55%   |
| Chicony Chromebook HD Camera             | 15        | 0.55%   |
| Acer Lenovo Integrated Webcam            | 15        | 0.55%   |
| Chicony EasyCamera                       | 14        | 0.51%   |
| Acer Lenovo EasyCamera                   | 14        | 0.51%   |
| Logitech C922 Pro Stream Webcam          | 13        | 0.47%   |
| IMC Networks USB 2.0 Camera              | 13        | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 267       | 45.25%  |
| Validity Sensors                   | 162       | 27.46%  |
| Shenzhen Goodix Technology         | 69        | 11.69%  |
| Upek                               | 24        | 4.07%   |
| Elan Microelectronics              | 22        | 3.73%   |
| AuthenTec                          | 21        | 3.56%   |
| LighTuning Technology              | 14        | 2.37%   |
| STMicroelectronics                 | 9         | 1.53%   |
| Samsung Electronics                | 1         | 0.17%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 174       | 29.49%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 39        | 6.61%   |
| Shenzhen Goodix  FingerPrint Device                                        | 38        | 6.44%   |
| Unknown                                                                    | 36        | 6.1%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 30        | 5.08%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 28        | 4.75%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 22        | 3.73%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 21        | 3.56%   |
| Validity Sensors Synaptics WBDI                                            | 18        | 3.05%   |
| Shenzhen Goodix Fingerprint Reader                                         | 16        | 2.71%   |
| Shenzhen Goodix FingerPrint                                                | 15        | 2.54%   |
| Elan ELAN:Fingerprint                                                      | 14        | 2.37%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 13        | 2.2%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 1.86%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.53%   |
| Validity Sensors VFS491                                                    | 8         | 1.36%   |
| Synaptics  WBDI                                                            | 8         | 1.36%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 8         | 1.36%   |
| Elan ELAN:ARM-M4                                                           | 8         | 1.36%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.19%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.19%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.19%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.02%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 6         | 1.02%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 0.85%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 0.85%   |
| AuthenTec AES2810                                                          | 4         | 0.68%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.51%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.51%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.34%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.34%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.34%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.34%   |
| STMicroelectronics TouchChipÂ Fingerprint Reader                          | 2         | 0.34%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.34%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.34%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.17%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.17%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 83        | 34.02%  |
| Broadcom                  | 82        | 33.61%  |
| Upek                      | 19        | 7.79%   |
| O2 Micro                  | 19        | 7.79%   |
| Lenovo                    | 15        | 6.15%   |
| SCM Microsystems          | 5         | 2.05%   |
| Gemalto (was Gemplus)     | 5         | 2.05%   |
| Yubico.com                | 3         | 1.23%   |
| Clay Logic                | 2         | 0.82%   |
| Cherry                    | 2         | 0.82%   |
| Aladdin Knowledge Systems | 2         | 0.82%   |
| Advanced Card Systems     | 2         | 0.82%   |
| Reiner SCT Kartensysteme  | 1         | 0.41%   |
| OmniKey                   | 1         | 0.41%   |
| Feitian Technologies      | 1         | 0.41%   |
| Chicony Electronics       | 1         | 0.41%   |
| C3PO                      | 1         | 0.41%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 81        | 33.2%   |
| Broadcom 58200                                                               | 27        | 11.07%  |
| Broadcom BCM5880 Secure Applications Processor                               | 23        | 9.43%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 19        | 7.79%   |
| Broadcom 5880                                                                | 19        | 7.79%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 16        | 6.56%   |
| Lenovo Integrated Smart Card Reader                                          | 14        | 5.74%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 4.51%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 1.23%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.23%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 2         | 0.82%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 0.82%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.82%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.82%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.82%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.82%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.82%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.41%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.41%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                  | 1         | 0.41%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.41%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.41%   |
| OmniKey CardMan 4321                                                         | 1         | 0.41%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.41%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.41%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.41%   |
| Feitian Technologies SCR301                                                  | 1         | 0.41%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.41%   |
| Cherry SmartTerminal XX1X                                                    | 1         | 0.41%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.41%   |
| C3PO LTC31v2                                                                 | 1         | 0.41%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3225      | 57.29%  |
| 1     | 1963      | 34.87%  |
| 2     | 359       | 6.38%   |
| 3     | 67        | 1.19%   |
| 4     | 8         | 0.14%   |
| 5     | 5         | 0.09%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1240      | 44.38%  |
| Fingerprint reader       | 588       | 21.05%  |
| Multimedia controller    | 222       | 7.95%   |
| Chipcard                 | 218       | 7.8%    |
| Net/wireless             | 209       | 7.48%   |
| Communication controller | 90        | 3.22%   |
| Unassigned class         | 52        | 1.86%   |
| Bluetooth                | 39        | 1.4%    |
| Card reader              | 23        | 0.82%   |
| Camera                   | 23        | 0.82%   |
| Sound                    | 22        | 0.79%   |
| Storage                  | 20        | 0.72%   |
| Net/ethernet             | 15        | 0.54%   |
| Network                  | 8         | 0.29%   |
| Modem                    | 7         | 0.25%   |
| Storage/raid             | 6         | 0.21%   |
| Tv card                  | 4         | 0.14%   |
| Flash memory             | 3         | 0.11%   |
| Firewire controller      | 2         | 0.07%   |
| Dvb card                 | 2         | 0.07%   |
| Storage/ide              | 1         | 0.04%   |

