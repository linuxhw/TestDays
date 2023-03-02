Debian - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Debian.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian/Desktop/README.md) and [notebooks](/Dist/Debian/Notebook/README.md).

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

Total: 12464

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Umbrel        | Home                        | Mini pc     | [f4afc80a6c](https://linux-hardware.org/?probe=f4afc80a6c) | Feb 28, 2023 |
| Medion        | TJ4125                      | Desktop     | [2024916642](https://linux-hardware.org/?probe=2024916642) | Feb 28, 2023 |
| CWWK          | CW-J6-6L                    | Desktop     | [46c17d2c14](https://linux-hardware.org/?probe=46c17d2c14) | Feb 28, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [1165717061](https://linux-hardware.org/?probe=1165717061) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [921aebe62a](https://linux-hardware.org/?probe=921aebe62a) | Feb 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [89822406cc](https://linux-hardware.org/?probe=89822406cc) | Feb 28, 2023 |
| HP            | 83E2                        | Desktop     | [fdbe4ec1cb](https://linux-hardware.org/?probe=fdbe4ec1cb) | Feb 28, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [19fd766ea6](https://linux-hardware.org/?probe=19fd766ea6) | Feb 28, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [17fcfc2758](https://linux-hardware.org/?probe=17fcfc2758) | Feb 28, 2023 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [26a7db2ed8](https://linux-hardware.org/?probe=26a7db2ed8) | Feb 28, 2023 |
| AZW           | MINI S                      | Desktop     | [e65b0d1ef6](https://linux-hardware.org/?probe=e65b0d1ef6) | Feb 28, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [e56350a1c1](https://linux-hardware.org/?probe=e56350a1c1) | Feb 28, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [49205269e7](https://linux-hardware.org/?probe=49205269e7) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | Notebook    | [3fa4d926e0](https://linux-hardware.org/?probe=3fa4d926e0) | Feb 28, 2023 |
| Intel         | D945GCPE AAD97209-201       | Desktop     | [672684e416](https://linux-hardware.org/?probe=672684e416) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [fa2df8125a](https://linux-hardware.org/?probe=fa2df8125a) | Feb 28, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [8cadddf432](https://linux-hardware.org/?probe=8cadddf432) | Feb 28, 2023 |
| Intel         | D945GCPE AAD97209-201       | Desktop     | [edf2240a74](https://linux-hardware.org/?probe=edf2240a74) | Feb 28, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [a5469adf59](https://linux-hardware.org/?probe=a5469adf59) | Feb 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b4bfab8974](https://linux-hardware.org/?probe=b4bfab8974) | Feb 28, 2023 |
| HP            | ProBook 6570b               | Notebook    | [3692011e3f](https://linux-hardware.org/?probe=3692011e3f) | Feb 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [4d3d5e02a1](https://linux-hardware.org/?probe=4d3d5e02a1) | Feb 28, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3948048a11](https://linux-hardware.org/?probe=3948048a11) | Feb 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [83a611b1ab](https://linux-hardware.org/?probe=83a611b1ab) | Feb 27, 2023 |
| ASRock        | X370 Professional Gaming    | Desktop     | [3a670fbd63](https://linux-hardware.org/?probe=3a670fbd63) | Feb 27, 2023 |
| HP            | 3397                        | Desktop     | [8081d24eb1](https://linux-hardware.org/?probe=8081d24eb1) | Feb 27, 2023 |
| IBM           | 00D4062                     | Server      | [16c68a28d8](https://linux-hardware.org/?probe=16c68a28d8) | Feb 27, 2023 |
| Dell          | 0MH651                      | Desktop     | [7921e9f8bc](https://linux-hardware.org/?probe=7921e9f8bc) | Feb 27, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [56654a2659](https://linux-hardware.org/?probe=56654a2659) | Feb 27, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [ccac327e17](https://linux-hardware.org/?probe=ccac327e17) | Feb 27, 2023 |
| Aquarius      | AQH310CM                    | Desktop     | [a2f4d0f77e](https://linux-hardware.org/?probe=a2f4d0f77e) | Feb 27, 2023 |
| Dell          | Latitude 5400               | Notebook    | [b788c61c95](https://linux-hardware.org/?probe=b788c61c95) | Feb 27, 2023 |
| Dell          | Latitude 3510               | Notebook    | [de938c4962](https://linux-hardware.org/?probe=de938c4962) | Feb 27, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [7a8e478900](https://linux-hardware.org/?probe=7a8e478900) | Feb 27, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [29f6c3c897](https://linux-hardware.org/?probe=29f6c3c897) | Feb 27, 2023 |
| ASUSTek       | K52F                        | Notebook    | [fa30ea101a](https://linux-hardware.org/?probe=fa30ea101a) | Feb 27, 2023 |
| ASUSTek       | H61M-E                      | Desktop     | [ee5b36d127](https://linux-hardware.org/?probe=ee5b36d127) | Feb 27, 2023 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [dd2f99b3ca](https://linux-hardware.org/?probe=dd2f99b3ca) | Feb 27, 2023 |
| Dell          | G3 3590                     | Notebook    | [eb9009fad9](https://linux-hardware.org/?probe=eb9009fad9) | Feb 27, 2023 |
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
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [7d7953a826](https://linux-hardware.org/?probe=7d7953a826) | Feb 26, 2023 |
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
| Unknown       | Unknown                     | Desktop     | [3d8e9cb31b](https://linux-hardware.org/?probe=3d8e9cb31b) | Feb 24, 2023 |
| Intel         | JSL MRD                     | Desktop     | [84a33f3c84](https://linux-hardware.org/?probe=84a33f3c84) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5cde621e0a](https://linux-hardware.org/?probe=5cde621e0a) | Feb 24, 2023 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | Notebook    | [27e2d41750](https://linux-hardware.org/?probe=27e2d41750) | Feb 24, 2023 |
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
| Unknown       | Unknown                     | Desktop     | [5070b384cc](https://linux-hardware.org/?probe=5070b384cc) | Feb 24, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [1989031eb6](https://linux-hardware.org/?probe=1989031eb6) | Feb 24, 2023 |
| Dell          | Latitude D620               | Notebook    | [fba80b099d](https://linux-hardware.org/?probe=fba80b099d) | Feb 24, 2023 |
| Dell          | 0CNWVK A02                  | Desktop     | [1fd825c3df](https://linux-hardware.org/?probe=1fd825c3df) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5da2f709bb](https://linux-hardware.org/?probe=5da2f709bb) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [bf32299a30](https://linux-hardware.org/?probe=bf32299a30) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [54279e4e30](https://linux-hardware.org/?probe=54279e4e30) | Feb 24, 2023 |
| HP            | EliteBook Folio 9480m       | Notebook    | [788e0929de](https://linux-hardware.org/?probe=788e0929de) | Feb 24, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [52b14c9235](https://linux-hardware.org/?probe=52b14c9235) | Feb 24, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [a09d17dd16](https://linux-hardware.org/?probe=a09d17dd16) | Feb 24, 2023 |
| Samsung       | N150P                       | Notebook    | [662488621d](https://linux-hardware.org/?probe=662488621d) | Feb 24, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e3f8cf325d](https://linux-hardware.org/?probe=e3f8cf325d) | Feb 24, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [478a4b921f](https://linux-hardware.org/?probe=478a4b921f) | Feb 24, 2023 |
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
| ASUSTek       | PRIME X399-A                | Desktop     | [4009d82fc8](https://linux-hardware.org/?probe=4009d82fc8) | Feb 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [5cf4127d47](https://linux-hardware.org/?probe=5cf4127d47) | Feb 21, 2023 |
| Dell          | Latitude 7530               | Notebook    | [4844568edb](https://linux-hardware.org/?probe=4844568edb) | Feb 21, 2023 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [30f09c71a1](https://linux-hardware.org/?probe=30f09c71a1) | Feb 21, 2023 |
| ASUSTek       | X556UQ                      | Notebook    | [8f645fa6fc](https://linux-hardware.org/?probe=8f645fa6fc) | Feb 21, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [de56e36164](https://linux-hardware.org/?probe=de56e36164) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470 20HDS1DL03    | Notebook    | [25e1a3f801](https://linux-hardware.org/?probe=25e1a3f801) | Feb 21, 2023 |
| Dell          | Inspiron 3468               | Notebook    | [e5977ee094](https://linux-hardware.org/?probe=e5977ee094) | Feb 21, 2023 |
| Dell          | Latitude E6430              | Notebook    | [80c9785ef0](https://linux-hardware.org/?probe=80c9785ef0) | Feb 21, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJA0... | Convertible | [aba497a637](https://linux-hardware.org/?probe=aba497a637) | Feb 21, 2023 |
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
| HP            | EliteBook 830 G5            | Notebook    | [0cb773d407](https://linux-hardware.org/?probe=0cb773d407) | Feb 20, 2023 |
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
| Dell          | XPS 13 9370                 | Notebook    | [e710561f68](https://linux-hardware.org/?probe=e710561f68) | Feb 19, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [2e3da97146](https://linux-hardware.org/?probe=2e3da97146) | Feb 19, 2023 |
| Dell          | 0NHNHP A01                  | Server      | [da74244bff](https://linux-hardware.org/?probe=da74244bff) | Feb 19, 2023 |
| Dell          | 073MMW A02                  | Desktop     | [aa198228bc](https://linux-hardware.org/?probe=aa198228bc) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [5300c136fd](https://linux-hardware.org/?probe=5300c136fd) | Feb 19, 2023 |
| Dell          | 0T065F A01                  | Desktop     | [c8b1f8651a](https://linux-hardware.org/?probe=c8b1f8651a) | Feb 19, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [d442995b00](https://linux-hardware.org/?probe=d442995b00) | Feb 19, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [22fdba9212](https://linux-hardware.org/?probe=22fdba9212) | Feb 19, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [34681494ec](https://linux-hardware.org/?probe=34681494ec) | Feb 18, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [537c2d1b64](https://linux-hardware.org/?probe=537c2d1b64) | Feb 18, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [3158f1e0d5](https://linux-hardware.org/?probe=3158f1e0d5) | Feb 18, 2023 |
| Supermicro    | X11SCA-WA                   | Server      | [065427c37f](https://linux-hardware.org/?probe=065427c37f) | Feb 18, 2023 |
| Intel         | JSL MRD                     | Desktop     | [5e021f6a92](https://linux-hardware.org/?probe=5e021f6a92) | Feb 18, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [8907f179e9](https://linux-hardware.org/?probe=8907f179e9) | Feb 18, 2023 |
| Lenovo        | ThinkPad E480 20KN001QGE    | Notebook    | [008f40a707](https://linux-hardware.org/?probe=008f40a707) | Feb 18, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a782ccbba9](https://linux-hardware.org/?probe=a782ccbba9) | Feb 18, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [22b75dc114](https://linux-hardware.org/?probe=22b75dc114) | Feb 18, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [a2cdf7d471](https://linux-hardware.org/?probe=a2cdf7d471) | Feb 18, 2023 |
| Dell          | Latitude E5450              | Notebook    | [56827b29dc](https://linux-hardware.org/?probe=56827b29dc) | Feb 18, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [cc805e31b0](https://linux-hardware.org/?probe=cc805e31b0) | Feb 17, 2023 |
| Gigabyte      | GA-A55M-DS2                 | Desktop     | [3159aede6c](https://linux-hardware.org/?probe=3159aede6c) | Feb 17, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Notebook    | [32f5d5e200](https://linux-hardware.org/?probe=32f5d5e200) | Feb 17, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [bd6636c99d](https://linux-hardware.org/?probe=bd6636c99d) | Feb 17, 2023 |
| Intel         | H61                         | Desktop     | [90e4a9358f](https://linux-hardware.org/?probe=90e4a9358f) | Feb 17, 2023 |
| MSI           | X399 SLI PLUS               | Desktop     | [8741094cd9](https://linux-hardware.org/?probe=8741094cd9) | Feb 17, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [423c7bb57a](https://linux-hardware.org/?probe=423c7bb57a) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | Notebook    | [02e6818311](https://linux-hardware.org/?probe=02e6818311) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | Notebook    | [4bf1ccfe74](https://linux-hardware.org/?probe=4bf1ccfe74) | Feb 17, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [4ab4c99cab](https://linux-hardware.org/?probe=4ab4c99cab) | Feb 17, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [288e753767](https://linux-hardware.org/?probe=288e753767) | Feb 17, 2023 |
| Dell          | System XPS L702X            | Notebook    | [81f9738975](https://linux-hardware.org/?probe=81f9738975) | Feb 16, 2023 |
| Lenovo        | 3164 NOK                    | Desktop     | [f69ff4a8c8](https://linux-hardware.org/?probe=f69ff4a8c8) | Feb 16, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | Desktop     | [cfdcc68921](https://linux-hardware.org/?probe=cfdcc68921) | Feb 16, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | Desktop     | [7bb3c6268f](https://linux-hardware.org/?probe=7bb3c6268f) | Feb 16, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [8f202b88fa](https://linux-hardware.org/?probe=8f202b88fa) | Feb 16, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [c812182e32](https://linux-hardware.org/?probe=c812182e32) | Feb 16, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [9ad890517a](https://linux-hardware.org/?probe=9ad890517a) | Feb 16, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [63747d1456](https://linux-hardware.org/?probe=63747d1456) | Feb 16, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [cda38b5b9b](https://linux-hardware.org/?probe=cda38b5b9b) | Feb 16, 2023 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [387881f288](https://linux-hardware.org/?probe=387881f288) | Feb 16, 2023 |
| Dell          | Precision 5570              | Notebook    | [d5f9d13ae3](https://linux-hardware.org/?probe=d5f9d13ae3) | Feb 16, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [46aafc59c4](https://linux-hardware.org/?probe=46aafc59c4) | Feb 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bbce6ba3b1](https://linux-hardware.org/?probe=bbce6ba3b1) | Feb 16, 2023 |
| Lenovo        | 1030 SDK0J40705 WIN 3425... | Desktop     | [daed0124f0](https://linux-hardware.org/?probe=daed0124f0) | Feb 16, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [a4fd7cdaa8](https://linux-hardware.org/?probe=a4fd7cdaa8) | Feb 16, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [940563622b](https://linux-hardware.org/?probe=940563622b) | Feb 16, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [5398361b68](https://linux-hardware.org/?probe=5398361b68) | Feb 16, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [73787e9141](https://linux-hardware.org/?probe=73787e9141) | Feb 16, 2023 |
| Gigabyte      | H270M-D3H-CF                | Desktop     | [7a58ceb644](https://linux-hardware.org/?probe=7a58ceb644) | Feb 15, 2023 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [c5b8952fdb](https://linux-hardware.org/?probe=c5b8952fdb) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [2b25f214e9](https://linux-hardware.org/?probe=2b25f214e9) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [5bf8aa635c](https://linux-hardware.org/?probe=5bf8aa635c) | Feb 15, 2023 |
| Dell          | Precision 5570              | Notebook    | [d0f2fa25c3](https://linux-hardware.org/?probe=d0f2fa25c3) | Feb 15, 2023 |
| HUAWEI        | WRT-WX9                     | Notebook    | [13866e78a2](https://linux-hardware.org/?probe=13866e78a2) | Feb 15, 2023 |
| Google        | Grunt                       | Notebook    | [89c633c2c1](https://linux-hardware.org/?probe=89c633c2c1) | Feb 15, 2023 |
| Gigabyte      | EP43-S3L                    | Desktop     | [82730ed699](https://linux-hardware.org/?probe=82730ed699) | Feb 15, 2023 |
| Itautec       | ST 4265                     | Desktop     | [84023fa8ac](https://linux-hardware.org/?probe=84023fa8ac) | Feb 15, 2023 |
| ASUSTek       | P5GD1 PRO                   | Desktop     | [043021ca86](https://linux-hardware.org/?probe=043021ca86) | Feb 15, 2023 |
| ASUSTek       | K53U                        | Notebook    | [e9a6a69e01](https://linux-hardware.org/?probe=e9a6a69e01) | Feb 15, 2023 |
| ASRock        | Z77 Extreme6                | Desktop     | [48328ab864](https://linux-hardware.org/?probe=48328ab864) | Feb 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [fe12f077df](https://linux-hardware.org/?probe=fe12f077df) | Feb 15, 2023 |
| Unknown       | T3 MRD                      | Notebook    | [df134a8199](https://linux-hardware.org/?probe=df134a8199) | Feb 14, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [e9faf4ce80](https://linux-hardware.org/?probe=e9faf4ce80) | Feb 14, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [5ebd73227b](https://linux-hardware.org/?probe=5ebd73227b) | Feb 14, 2023 |
| Acer          | Aspire V5-572G              | Notebook    | [7f360258ff](https://linux-hardware.org/?probe=7f360258ff) | Feb 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [0ac84e31dd](https://linux-hardware.org/?probe=0ac84e31dd) | Feb 14, 2023 |
| Dell          | 0RN474                      | Desktop     | [5c1bf45372](https://linux-hardware.org/?probe=5c1bf45372) | Feb 14, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [27fa84ce56](https://linux-hardware.org/?probe=27fa84ce56) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [8895a873ab](https://linux-hardware.org/?probe=8895a873ab) | Feb 14, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [0a0e30ba0a](https://linux-hardware.org/?probe=0a0e30ba0a) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [fb00615692](https://linux-hardware.org/?probe=fb00615692) | Feb 14, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [977650806e](https://linux-hardware.org/?probe=977650806e) | Feb 14, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [ae563f7bfe](https://linux-hardware.org/?probe=ae563f7bfe) | Feb 14, 2023 |
| HP            | 3648h                       | Desktop     | [18eb122bc9](https://linux-hardware.org/?probe=18eb122bc9) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [f6bcdb7c6b](https://linux-hardware.org/?probe=f6bcdb7c6b) | Feb 14, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [67b141272c](https://linux-hardware.org/?probe=67b141272c) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [345021f7f6](https://linux-hardware.org/?probe=345021f7f6) | Feb 14, 2023 |
| Lenovo        | ThinkPad P51 20HJS0AR16     | Notebook    | [ad0f22fe34](https://linux-hardware.org/?probe=ad0f22fe34) | Feb 14, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [c69ee15636](https://linux-hardware.org/?probe=c69ee15636) | Feb 14, 2023 |
| Dell          | 0RN474                      | Desktop     | [20f3c37dc2](https://linux-hardware.org/?probe=20f3c37dc2) | Feb 14, 2023 |
| ASUSTek       | X505BP                      | Notebook    | [579388a539](https://linux-hardware.org/?probe=579388a539) | Feb 13, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [34ad4bac16](https://linux-hardware.org/?probe=34ad4bac16) | Feb 13, 2023 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [4750f3ad3a](https://linux-hardware.org/?probe=4750f3ad3a) | Feb 13, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [55e684c121](https://linux-hardware.org/?probe=55e684c121) | Feb 13, 2023 |
| Dell          | Latitude D630               | Notebook    | [04c083db36](https://linux-hardware.org/?probe=04c083db36) | Feb 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [c49317ce12](https://linux-hardware.org/?probe=c49317ce12) | Feb 13, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [855634fadc](https://linux-hardware.org/?probe=855634fadc) | Feb 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [b1d1f36f51](https://linux-hardware.org/?probe=b1d1f36f51) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [6fe738fa6d](https://linux-hardware.org/?probe=6fe738fa6d) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [122eded37e](https://linux-hardware.org/?probe=122eded37e) | Feb 13, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [517a5a9e81](https://linux-hardware.org/?probe=517a5a9e81) | Feb 13, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [e83cd923a5](https://linux-hardware.org/?probe=e83cd923a5) | Feb 13, 2023 |
| Google        | Droid                       | Notebook    | [435ab67598](https://linux-hardware.org/?probe=435ab67598) | Feb 12, 2023 |
| retsamarre... | 000-F4423-UK000-2000        | Tablet      | [c24b5a1f84](https://linux-hardware.org/?probe=c24b5a1f84) | Feb 12, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [89c31e6f8c](https://linux-hardware.org/?probe=89c31e6f8c) | Feb 12, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [124d65cd04](https://linux-hardware.org/?probe=124d65cd04) | Feb 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [72ce8d1929](https://linux-hardware.org/?probe=72ce8d1929) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [c0d18ab501](https://linux-hardware.org/?probe=c0d18ab501) | Feb 12, 2023 |
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
| Dell          | Latitude E6330              | Notebook    | [1b5cdf846f](https://linux-hardware.org/?probe=1b5cdf846f) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [d003016397](https://linux-hardware.org/?probe=d003016397) | Feb 11, 2023 |
| AZW           | U59                         | Desktop     | [24ccf521f0](https://linux-hardware.org/?probe=24ccf521f0) | Feb 11, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [a3f08d08aa](https://linux-hardware.org/?probe=a3f08d08aa) | Feb 11, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [5483d83053](https://linux-hardware.org/?probe=5483d83053) | Feb 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [20a75bea61](https://linux-hardware.org/?probe=20a75bea61) | Feb 11, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [5b2605691d](https://linux-hardware.org/?probe=5b2605691d) | Feb 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [7b6a31ec69](https://linux-hardware.org/?probe=7b6a31ec69) | Feb 11, 2023 |
| AMD           | CM-iGLX Platform Board R... | Desktop     | [c256a73072](https://linux-hardware.org/?probe=c256a73072) | Feb 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [35b93693a5](https://linux-hardware.org/?probe=35b93693a5) | Feb 10, 2023 |
| Dell          | Latitude 7370               | Notebook    | [30c62c9e44](https://linux-hardware.org/?probe=30c62c9e44) | Feb 10, 2023 |
| Dell          | Latitude 7370               | Notebook    | [b4e7a5cb63](https://linux-hardware.org/?probe=b4e7a5cb63) | Feb 10, 2023 |
| Maxtang       | EHL30 V1.0                  | Desktop     | [4d133c615c](https://linux-hardware.org/?probe=4d133c615c) | Feb 10, 2023 |
| ASRockRack    | X570D4U                     | Desktop     | [bb2c98768e](https://linux-hardware.org/?probe=bb2c98768e) | Feb 10, 2023 |
| ASUSTek       | N751JX                      | Notebook    | [fd591a3e67](https://linux-hardware.org/?probe=fd591a3e67) | Feb 10, 2023 |
| Novatech      | NL40_50CU                   | Notebook    | [cca307c7db](https://linux-hardware.org/?probe=cca307c7db) | Feb 10, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [7ac6f508b2](https://linux-hardware.org/?probe=7ac6f508b2) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [65e66dbf71](https://linux-hardware.org/?probe=65e66dbf71) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [8239d80ae0](https://linux-hardware.org/?probe=8239d80ae0) | Feb 10, 2023 |
| Intel         | H61                         | Desktop     | [e07896a0a6](https://linux-hardware.org/?probe=e07896a0a6) | Feb 10, 2023 |
| ASUSTek       | M4N78                       | Desktop     | [34ddf02a41](https://linux-hardware.org/?probe=34ddf02a41) | Feb 10, 2023 |
| Lenovo        | ThinkPad SL510 28477MG      | Notebook    | [8f22e1beaa](https://linux-hardware.org/?probe=8f22e1beaa) | Feb 10, 2023 |
| Samsung       | 550XDA                      | Notebook    | [45d947c9f9](https://linux-hardware.org/?probe=45d947c9f9) | Feb 10, 2023 |
| IBM           | ThinkPad T43 18714AG        | Notebook    | [0730c9228d](https://linux-hardware.org/?probe=0730c9228d) | Feb 10, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [84eb5f0ad8](https://linux-hardware.org/?probe=84eb5f0ad8) | Feb 09, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [8c4ab545de](https://linux-hardware.org/?probe=8c4ab545de) | Feb 09, 2023 |
| Acer          | Veriton N4630G              | Desktop     | [262d8ec347](https://linux-hardware.org/?probe=262d8ec347) | Feb 09, 2023 |
| Acer          | Aspire ES1-111M             | Notebook    | [82eea49fcd](https://linux-hardware.org/?probe=82eea49fcd) | Feb 09, 2023 |
| Acer          | Aspire ES1-111M             | Notebook    | [accbac47d5](https://linux-hardware.org/?probe=accbac47d5) | Feb 09, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [fd0b6a7a49](https://linux-hardware.org/?probe=fd0b6a7a49) | Feb 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [02adcb8587](https://linux-hardware.org/?probe=02adcb8587) | Feb 09, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [fe1dac78bb](https://linux-hardware.org/?probe=fe1dac78bb) | Feb 09, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [209d4693fe](https://linux-hardware.org/?probe=209d4693fe) | Feb 09, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [82173d3b08](https://linux-hardware.org/?probe=82173d3b08) | Feb 09, 2023 |
| Dell          | Latitude E7250              | Notebook    | [e3c1b1e038](https://linux-hardware.org/?probe=e3c1b1e038) | Feb 09, 2023 |
| Lenovo        | Legion Y520-15IKBN 80WK     | Notebook    | [ec17af9e06](https://linux-hardware.org/?probe=ec17af9e06) | Feb 09, 2023 |
| AMI           | Cherry Trail CR             | Notebook    | [e7eab93323](https://linux-hardware.org/?probe=e7eab93323) | Feb 09, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [a0132107aa](https://linux-hardware.org/?probe=a0132107aa) | Feb 08, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [6231dbe6d4](https://linux-hardware.org/?probe=6231dbe6d4) | Feb 08, 2023 |
| Dell          | Latitude E6330              | Notebook    | [291e0fd64f](https://linux-hardware.org/?probe=291e0fd64f) | Feb 08, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [965758f3ea](https://linux-hardware.org/?probe=965758f3ea) | Feb 08, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [bbaa8165e4](https://linux-hardware.org/?probe=bbaa8165e4) | Feb 08, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [e521c55b1a](https://linux-hardware.org/?probe=e521c55b1a) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [cc897fe72d](https://linux-hardware.org/?probe=cc897fe72d) | Feb 08, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | Notebook    | [9f6079baf2](https://linux-hardware.org/?probe=9f6079baf2) | Feb 08, 2023 |
| Lenovo        | 3164 NOK                    | Desktop     | [750d30cb48](https://linux-hardware.org/?probe=750d30cb48) | Feb 08, 2023 |
| Intel         | DH67CL AAG10212-208         | Desktop     | [e53a89d83d](https://linux-hardware.org/?probe=e53a89d83d) | Feb 08, 2023 |
| Dell          | Precision 5570              | Notebook    | [6c257e667d](https://linux-hardware.org/?probe=6c257e667d) | Feb 08, 2023 |
| TYAN Compu... | S4985                       | Server      | [40ea5a6601](https://linux-hardware.org/?probe=40ea5a6601) | Feb 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [d37cc19110](https://linux-hardware.org/?probe=d37cc19110) | Feb 08, 2023 |
| Dell          | Precision 5570              | Notebook    | [e81b3de663](https://linux-hardware.org/?probe=e81b3de663) | Feb 08, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [f5aeb173ba](https://linux-hardware.org/?probe=f5aeb173ba) | Feb 08, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3245fc2fec](https://linux-hardware.org/?probe=3245fc2fec) | Feb 08, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [8fb3a20b27](https://linux-hardware.org/?probe=8fb3a20b27) | Feb 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [def4679f84](https://linux-hardware.org/?probe=def4679f84) | Feb 07, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | Notebook    | [db2f72084a](https://linux-hardware.org/?probe=db2f72084a) | Feb 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [eca3a05d41](https://linux-hardware.org/?probe=eca3a05d41) | Feb 07, 2023 |
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
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [4b19274da1](https://linux-hardware.org/?probe=4b19274da1) | Feb 06, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [bc5b9a2c5d](https://linux-hardware.org/?probe=bc5b9a2c5d) | Feb 06, 2023 |
| HP            | 3397                        | Desktop     | [2fb7638874](https://linux-hardware.org/?probe=2fb7638874) | Feb 06, 2023 |
| Google        | Terra                       | Notebook    | [edfe00266c](https://linux-hardware.org/?probe=edfe00266c) | Feb 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [7d2d46a579](https://linux-hardware.org/?probe=7d2d46a579) | Feb 06, 2023 |
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
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [55402fea35](https://linux-hardware.org/?probe=55402fea35) | Feb 05, 2023 |
| Gigabyte      | H61MA-D2V                   | Desktop     | [b708cdc12f](https://linux-hardware.org/?probe=b708cdc12f) | Feb 05, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [7b81bb188c](https://linux-hardware.org/?probe=7b81bb188c) | Feb 05, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [c3891f43b5](https://linux-hardware.org/?probe=c3891f43b5) | Feb 05, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [413341361a](https://linux-hardware.org/?probe=413341361a) | Feb 05, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [b2247eafed](https://linux-hardware.org/?probe=b2247eafed) | Feb 05, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [6023defc83](https://linux-hardware.org/?probe=6023defc83) | Feb 05, 2023 |
| Intel         | S5500HCV E40912-458         | Server      | [1445c60562](https://linux-hardware.org/?probe=1445c60562) | Feb 05, 2023 |
| Intel         | S5500HCV E40912-458         | Server      | [95ff55d958](https://linux-hardware.org/?probe=95ff55d958) | Feb 05, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [2f56f41681](https://linux-hardware.org/?probe=2f56f41681) | Feb 05, 2023 |
| Google        | Ampton                      | Notebook    | [74d5b6aa4d](https://linux-hardware.org/?probe=74d5b6aa4d) | Feb 05, 2023 |
| HP            | 2B36                        | Desktop     | [dde1352d90](https://linux-hardware.org/?probe=dde1352d90) | Feb 05, 2023 |
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
| ECS           | A780GM-A                    | Desktop     | [2cb7086ff1](https://linux-hardware.org/?probe=2cb7086ff1) | Feb 04, 2023 |
| Toshiba       | Satellite P775              | Notebook    | [df8aa8c06a](https://linux-hardware.org/?probe=df8aa8c06a) | Feb 04, 2023 |
| ECS           | A780GM-A                    | Desktop     | [6f6599f880](https://linux-hardware.org/?probe=6f6599f880) | Feb 04, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [78ca889e8d](https://linux-hardware.org/?probe=78ca889e8d) | Feb 04, 2023 |
| Lenovo        | ThinkPad T440p 20ANS09W0... | Notebook    | [17f9df8f2c](https://linux-hardware.org/?probe=17f9df8f2c) | Feb 03, 2023 |
| HP            | 3048h                       | Desktop     | [03b28af2be](https://linux-hardware.org/?probe=03b28af2be) | Feb 03, 2023 |
| ASUSTek       | PN50-E1                     | Mini pc     | [063a4bb843](https://linux-hardware.org/?probe=063a4bb843) | Feb 03, 2023 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [4b85a254bc](https://linux-hardware.org/?probe=4b85a254bc) | Feb 03, 2023 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [142d89a9c0](https://linux-hardware.org/?probe=142d89a9c0) | Feb 03, 2023 |
| AZW           | MINI S                      | Desktop     | [6c746a5f95](https://linux-hardware.org/?probe=6c746a5f95) | Feb 03, 2023 |
| Lenovo        | V310-15IKB 80T3             | Notebook    | [a39fb673c7](https://linux-hardware.org/?probe=a39fb673c7) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [4de96841bf](https://linux-hardware.org/?probe=4de96841bf) | Feb 03, 2023 |
| HP            | Pavilion 15                 | Notebook    | [5909dd08e7](https://linux-hardware.org/?probe=5909dd08e7) | Feb 03, 2023 |
| Intel         | AB2L .A004                  | Mini pc     | [568740a6b1](https://linux-hardware.org/?probe=568740a6b1) | Feb 03, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [fe381cbbfe](https://linux-hardware.org/?probe=fe381cbbfe) | Feb 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [c0c511ec65](https://linux-hardware.org/?probe=c0c511ec65) | Feb 03, 2023 |
| Dell          | 05WNJ2 A02                  | Desktop     | [4619f572c5](https://linux-hardware.org/?probe=4619f572c5) | Feb 03, 2023 |
| Aquarius      | NS585                       | Notebook    | [7e944d88b3](https://linux-hardware.org/?probe=7e944d88b3) | Feb 03, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d0d8e49083](https://linux-hardware.org/?probe=d0d8e49083) | Feb 03, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [ae290fa64e](https://linux-hardware.org/?probe=ae290fa64e) | Feb 03, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [7820377760](https://linux-hardware.org/?probe=7820377760) | Feb 03, 2023 |
| Xunlong       | Orange Pi Zero              | Soc         | [3af57a322f](https://linux-hardware.org/?probe=3af57a322f) | Feb 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [c122070f4f](https://linux-hardware.org/?probe=c122070f4f) | Feb 03, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [534cdba357](https://linux-hardware.org/?probe=534cdba357) | Feb 03, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [656df2cea9](https://linux-hardware.org/?probe=656df2cea9) | Feb 03, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [6d39ef2792](https://linux-hardware.org/?probe=6d39ef2792) | Feb 03, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [c26be60545](https://linux-hardware.org/?probe=c26be60545) | Feb 03, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [2f2c8adb0c](https://linux-hardware.org/?probe=2f2c8adb0c) | Feb 02, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [6d7a27b213](https://linux-hardware.org/?probe=6d7a27b213) | Feb 02, 2023 |
| Google        | Babymega                    | Notebook    | [2a8b81c6f4](https://linux-hardware.org/?probe=2a8b81c6f4) | Feb 02, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3483138f98](https://linux-hardware.org/?probe=3483138f98) | Feb 02, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [52d7e2f51f](https://linux-hardware.org/?probe=52d7e2f51f) | Feb 02, 2023 |
| Intel         | SKYBAY                      | Desktop     | [a75cb78ad9](https://linux-hardware.org/?probe=a75cb78ad9) | Feb 02, 2023 |
| Dell          | Vostro 3580                 | Notebook    | [7efc294bac](https://linux-hardware.org/?probe=7efc294bac) | Feb 02, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [9bb5fabf0b](https://linux-hardware.org/?probe=9bb5fabf0b) | Feb 02, 2023 |
| Lenovo        | ThinkPad E495 20NE001GMX    | Notebook    | [29660bbd04](https://linux-hardware.org/?probe=29660bbd04) | Feb 02, 2023 |
| Dell          | Latitude 7480               | Notebook    | [8a7e0b16d5](https://linux-hardware.org/?probe=8a7e0b16d5) | Feb 02, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [2de08972b9](https://linux-hardware.org/?probe=2de08972b9) | Feb 02, 2023 |
| NEC Comput... | MS9666 011                  | Desktop     | [26a38770fe](https://linux-hardware.org/?probe=26a38770fe) | Feb 02, 2023 |
| Lenovo        | 300w Gen 3 82J1             | Convertible | [1d26f2fcbc](https://linux-hardware.org/?probe=1d26f2fcbc) | Feb 02, 2023 |
| Lenovo        | 300w Gen 3 82J1             | Convertible | [895cb06490](https://linux-hardware.org/?probe=895cb06490) | Feb 02, 2023 |
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
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [142f5fcb2d](https://linux-hardware.org/?probe=142f5fcb2d) | Feb 01, 2023 |
| ASRock        | X570 Pro4                   | Desktop     | [81b19ff917](https://linux-hardware.org/?probe=81b19ff917) | Feb 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [f2b211ff3a](https://linux-hardware.org/?probe=f2b211ff3a) | Feb 01, 2023 |
| Gigabyte      | Z690M DS3H DDR4             | Desktop     | [8f858cb9b9](https://linux-hardware.org/?probe=8f858cb9b9) | Jan 31, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [6e8d45f76b](https://linux-hardware.org/?probe=6e8d45f76b) | Jan 31, 2023 |
| MSI           | 870A-G54                    | Desktop     | [0aaa012de5](https://linux-hardware.org/?probe=0aaa012de5) | Jan 31, 2023 |
| HP            | Notebook                    | Notebook    | [3cea0a0519](https://linux-hardware.org/?probe=3cea0a0519) | Jan 31, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [daa9bd48c8](https://linux-hardware.org/?probe=daa9bd48c8) | Jan 31, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [7e25d19fae](https://linux-hardware.org/?probe=7e25d19fae) | Jan 31, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a2c87504d6](https://linux-hardware.org/?probe=a2c87504d6) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [1c798340db](https://linux-hardware.org/?probe=1c798340db) | Jan 31, 2023 |
| ASRock        | G31M-VS2                    | Desktop     | [e12dd528ea](https://linux-hardware.org/?probe=e12dd528ea) | Jan 31, 2023 |
| MSI           | H81M-E34                    | Desktop     | [19b8f90522](https://linux-hardware.org/?probe=19b8f90522) | Jan 31, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [d8f44aeb4c](https://linux-hardware.org/?probe=d8f44aeb4c) | Jan 31, 2023 |
| ASUSTek       | PRIME B250-A                | Desktop     | [c686d3d123](https://linux-hardware.org/?probe=c686d3d123) | Jan 31, 2023 |
| ASRock        | X570 Pro4                   | Desktop     | [37999411ed](https://linux-hardware.org/?probe=37999411ed) | Jan 31, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [35948f3b5e](https://linux-hardware.org/?probe=35948f3b5e) | Jan 31, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [011c3940f9](https://linux-hardware.org/?probe=011c3940f9) | Jan 31, 2023 |
| Dell          | Inspiron 5485 2n1           | Convertible | [e335e7282d](https://linux-hardware.org/?probe=e335e7282d) | Jan 30, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [3f17be7a85](https://linux-hardware.org/?probe=3f17be7a85) | Jan 30, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [ed57a59e39](https://linux-hardware.org/?probe=ed57a59e39) | Jan 30, 2023 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [b6a73bd22e](https://linux-hardware.org/?probe=b6a73bd22e) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [3ecd91770e](https://linux-hardware.org/?probe=3ecd91770e) | Jan 30, 2023 |
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
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [eb551b5ec0](https://linux-hardware.org/?probe=eb551b5ec0) | Jan 29, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [e91c24c3f9](https://linux-hardware.org/?probe=e91c24c3f9) | Jan 29, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [351106d7e5](https://linux-hardware.org/?probe=351106d7e5) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 42915CG       | Notebook    | [d058eeaad5](https://linux-hardware.org/?probe=d058eeaad5) | Jan 29, 2023 |
| Gigabyte      | M61PME-S2                   | Desktop     | [8227150e0d](https://linux-hardware.org/?probe=8227150e0d) | Jan 29, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [03171e1e33](https://linux-hardware.org/?probe=03171e1e33) | Jan 29, 2023 |
| Gigabyte      | M61PME-S2                   | Desktop     | [813f01976d](https://linux-hardware.org/?probe=813f01976d) | Jan 29, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [eaed78d213](https://linux-hardware.org/?probe=eaed78d213) | Jan 28, 2023 |
| Dell          | 0F8098                      | Desktop     | [d6066c739e](https://linux-hardware.org/?probe=d6066c739e) | Jan 28, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [a1b5cdf1db](https://linux-hardware.org/?probe=a1b5cdf1db) | Jan 28, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [e9fc2c87df](https://linux-hardware.org/?probe=e9fc2c87df) | Jan 28, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [5fa28ba14d](https://linux-hardware.org/?probe=5fa28ba14d) | Jan 28, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a88e343a83](https://linux-hardware.org/?probe=a88e343a83) | Jan 28, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [6e55ab69b8](https://linux-hardware.org/?probe=6e55ab69b8) | Jan 28, 2023 |
| Dell          | 05MW5F A00                  | Mini pc     | [dd56d67fef](https://linux-hardware.org/?probe=dd56d67fef) | Jan 28, 2023 |
| ASUSTek       | UX410UAR                    | Notebook    | [e9ac16c8ef](https://linux-hardware.org/?probe=e9ac16c8ef) | Jan 28, 2023 |
| HP            | 1998                        | Desktop     | [81da484cc4](https://linux-hardware.org/?probe=81da484cc4) | Jan 28, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [8c8db10ac2](https://linux-hardware.org/?probe=8c8db10ac2) | Jan 28, 2023 |
| HP            | ProBook 430 G6              | Notebook    | [24fd7df5b6](https://linux-hardware.org/?probe=24fd7df5b6) | Jan 28, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [bbdf827cef](https://linux-hardware.org/?probe=bbdf827cef) | Jan 27, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [0b05244a15](https://linux-hardware.org/?probe=0b05244a15) | Jan 27, 2023 |
| Dell          | Latitude E7440              | Notebook    | [9ba078f6ab](https://linux-hardware.org/?probe=9ba078f6ab) | Jan 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [8ef4f014f2](https://linux-hardware.org/?probe=8ef4f014f2) | Jan 27, 2023 |
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
| Lenovo        | ThinkPad T440 20B7S0JC0P    | Notebook    | [1a36af70e8](https://linux-hardware.org/?probe=1a36af70e8) | Jan 26, 2023 |
| Google        | Careena                     | Notebook    | [75ca1a25dd](https://linux-hardware.org/?probe=75ca1a25dd) | Jan 26, 2023 |
| AZW           | MINI S                      | Desktop     | [ce5e6b1504](https://linux-hardware.org/?probe=ce5e6b1504) | Jan 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [d632bd0c9f](https://linux-hardware.org/?probe=d632bd0c9f) | Jan 26, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [0093f9df93](https://linux-hardware.org/?probe=0093f9df93) | Jan 26, 2023 |
| HP            | 805D                        | Desktop     | [b1996094a9](https://linux-hardware.org/?probe=b1996094a9) | Jan 26, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [2e70086887](https://linux-hardware.org/?probe=2e70086887) | Jan 25, 2023 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [dee0143024](https://linux-hardware.org/?probe=dee0143024) | Jan 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [a780c8d844](https://linux-hardware.org/?probe=a780c8d844) | Jan 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [e6a1506275](https://linux-hardware.org/?probe=e6a1506275) | Jan 25, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [4643f751cf](https://linux-hardware.org/?probe=4643f751cf) | Jan 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [3b96eac8a9](https://linux-hardware.org/?probe=3b96eac8a9) | Jan 25, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [90d383c54e](https://linux-hardware.org/?probe=90d383c54e) | Jan 25, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [e4b50b33a2](https://linux-hardware.org/?probe=e4b50b33a2) | Jan 25, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [e0eefbde94](https://linux-hardware.org/?probe=e0eefbde94) | Jan 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e2d354b9c5](https://linux-hardware.org/?probe=e2d354b9c5) | Jan 25, 2023 |
| Panasonic     | FZ55-2                      | Notebook    | [dd9ddb12b6](https://linux-hardware.org/?probe=dd9ddb12b6) | Jan 25, 2023 |
| Lenovo        | ThinkPad X220 4291IR6       | Notebook    | [cc41fa5174](https://linux-hardware.org/?probe=cc41fa5174) | Jan 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [8780aceeec](https://linux-hardware.org/?probe=8780aceeec) | Jan 25, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [bfd4198155](https://linux-hardware.org/?probe=bfd4198155) | Jan 25, 2023 |
| Samsung       | R710                        | Notebook    | [17a3e2ddd9](https://linux-hardware.org/?probe=17a3e2ddd9) | Jan 25, 2023 |
| Dell          | 0K3CM7 A00                  | Desktop     | [d3cc219bf7](https://linux-hardware.org/?probe=d3cc219bf7) | Jan 24, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [0bde1ca99a](https://linux-hardware.org/?probe=0bde1ca99a) | Jan 24, 2023 |
| MSI           | H97 PC Mate                 | Desktop     | [d00ec3c042](https://linux-hardware.org/?probe=d00ec3c042) | Jan 24, 2023 |
| Packard Be... | EasyNote MH36               | Notebook    | [07ba548a55](https://linux-hardware.org/?probe=07ba548a55) | Jan 24, 2023 |
| BESSTAR Te... | Cherry Trail CR             | Mini pc     | [9ac0bac56e](https://linux-hardware.org/?probe=9ac0bac56e) | Jan 24, 2023 |
| ECS           | G31T-M9                     | Desktop     | [59747c81ca](https://linux-hardware.org/?probe=59747c81ca) | Jan 24, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [fe1a2d7fc6](https://linux-hardware.org/?probe=fe1a2d7fc6) | Jan 24, 2023 |
| HP            | 82B4                        | Desktop     | [29e2d03c1a](https://linux-hardware.org/?probe=29e2d03c1a) | Jan 24, 2023 |
| HP            | 82B4                        | Desktop     | [3df98736a1](https://linux-hardware.org/?probe=3df98736a1) | Jan 24, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [bf21a44322](https://linux-hardware.org/?probe=bf21a44322) | Jan 23, 2023 |
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
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [ae270718a7](https://linux-hardware.org/?probe=ae270718a7) | Jan 22, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [91ef58d8a0](https://linux-hardware.org/?probe=91ef58d8a0) | Jan 22, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e7afed6351](https://linux-hardware.org/?probe=e7afed6351) | Jan 22, 2023 |
| Dell          | G3 3579                     | Notebook    | [63298dcee9](https://linux-hardware.org/?probe=63298dcee9) | Jan 22, 2023 |
| Danew         | Dbook 131                   | Notebook    | [08911c133e](https://linux-hardware.org/?probe=08911c133e) | Jan 22, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0c65146f4c](https://linux-hardware.org/?probe=0c65146f4c) | Jan 21, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [ef532b60e6](https://linux-hardware.org/?probe=ef532b60e6) | Jan 21, 2023 |
| Clevo         | W150ER                      | Notebook    | [ba5d06437c](https://linux-hardware.org/?probe=ba5d06437c) | Jan 21, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [68847eb1e6](https://linux-hardware.org/?probe=68847eb1e6) | Jan 21, 2023 |
| Biostar       | H310MHP                     | Desktop     | [21de314a44](https://linux-hardware.org/?probe=21de314a44) | Jan 21, 2023 |
| ASUSTek       | H170I-PLUS D3               | Desktop     | [b8d373b07e](https://linux-hardware.org/?probe=b8d373b07e) | Jan 21, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [c9d6e1cbb1](https://linux-hardware.org/?probe=c9d6e1cbb1) | Jan 21, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [4b9d2e6e26](https://linux-hardware.org/?probe=4b9d2e6e26) | Jan 21, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [15dde971f3](https://linux-hardware.org/?probe=15dde971f3) | Jan 21, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [f5bb76ae13](https://linux-hardware.org/?probe=f5bb76ae13) | Jan 21, 2023 |
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
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [27e484698b](https://linux-hardware.org/?probe=27e484698b) | Jan 20, 2023 |
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
| Dell          | Latitude E6540              | Notebook    | [34c018d211](https://linux-hardware.org/?probe=34c018d211) | Jan 20, 2023 |
| Gigabyte      | Z690I A ULTRA LITE D4       | Desktop     | [abcfca9ea7](https://linux-hardware.org/?probe=abcfca9ea7) | Jan 20, 2023 |
| TI            | OMAP3 BeagleBoard xM        | Soc         | [c081cbef0c](https://linux-hardware.org/?probe=c081cbef0c) | Jan 20, 2023 |
| Lenovo        | 7033EW4                     | Desktop     | [fd4303de2e](https://linux-hardware.org/?probe=fd4303de2e) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [80cb1c8239](https://linux-hardware.org/?probe=80cb1c8239) | Jan 19, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [7ecc4d20c3](https://linux-hardware.org/?probe=7ecc4d20c3) | Jan 19, 2023 |
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
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [e3d0558aee](https://linux-hardware.org/?probe=e3d0558aee) | Jan 19, 2023 |
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
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [6dab459ed2](https://linux-hardware.org/?probe=6dab459ed2) | Jan 18, 2023 |
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
| Lenovo        | IdeaPad 3 14ARE05 81W3      | Notebook    | [804fe39b80](https://linux-hardware.org/?probe=804fe39b80) | Jan 16, 2023 |
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
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [a09ace045e](https://linux-hardware.org/?probe=a09ace045e) | Jan 15, 2023 |
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
| Apple         | MacBookPro12,1              | Notebook    | [1402c185c7](https://linux-hardware.org/?probe=1402c185c7) | Jan 14, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [f862a7e702](https://linux-hardware.org/?probe=f862a7e702) | Jan 14, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [df889b6674](https://linux-hardware.org/?probe=df889b6674) | Jan 14, 2023 |
| HONOR         | HLYL-WXX9                   | Notebook    | [e5b02d94cd](https://linux-hardware.org/?probe=e5b02d94cd) | Jan 14, 2023 |
| Dell          | Inspiron 11 - 3147          | Notebook    | [7193100d05](https://linux-hardware.org/?probe=7193100d05) | Jan 14, 2023 |
| HP            | Pavilion g6                 | Notebook    | [7672e1178a](https://linux-hardware.org/?probe=7672e1178a) | Jan 14, 2023 |
| Panasonic     | CFSZ6-2                     | Notebook    | [7a9f534294](https://linux-hardware.org/?probe=7a9f534294) | Jan 13, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [8a79dd9e27](https://linux-hardware.org/?probe=8a79dd9e27) | Jan 13, 2023 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [bed628ce8a](https://linux-hardware.org/?probe=bed628ce8a) | Jan 13, 2023 |
| Lenovo        | ThinkCentre M58p 6234A1U    | Desktop     | [63d74a9021](https://linux-hardware.org/?probe=63d74a9021) | Jan 13, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [8cffa1360f](https://linux-hardware.org/?probe=8cffa1360f) | Jan 13, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [ed62a9383e](https://linux-hardware.org/?probe=ed62a9383e) | Jan 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [ce69bfd81b](https://linux-hardware.org/?probe=ce69bfd81b) | Jan 13, 2023 |
| Medion        | TJ4125                      | Desktop     | [700f862aa6](https://linux-hardware.org/?probe=700f862aa6) | Jan 13, 2023 |
| HC            | HCAR357-MI V1.0             | Desktop     | [516f1ed052](https://linux-hardware.org/?probe=516f1ed052) | Jan 13, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [810b866ee4](https://linux-hardware.org/?probe=810b866ee4) | Jan 13, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [baf20b6914](https://linux-hardware.org/?probe=baf20b6914) | Jan 13, 2023 |
| Lenovo        | ThinkPad L390 Yoga 20NTC... | Convertible | [03e4d52b2d](https://linux-hardware.org/?probe=03e4d52b2d) | Jan 13, 2023 |
| Vestel        | 14MB24A                     | Desktop     | [56ee8713e8](https://linux-hardware.org/?probe=56ee8713e8) | Jan 13, 2023 |
| Vestel        | 14MB24A                     | Desktop     | [02c99c8c38](https://linux-hardware.org/?probe=02c99c8c38) | Jan 13, 2023 |
| ASUSTek       | Q325UA                      | Convertible | [1862534df3](https://linux-hardware.org/?probe=1862534df3) | Jan 13, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [efeae454c8](https://linux-hardware.org/?probe=efeae454c8) | Jan 13, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [a4fb531cc9](https://linux-hardware.org/?probe=a4fb531cc9) | Jan 13, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [07a70b62af](https://linux-hardware.org/?probe=07a70b62af) | Jan 13, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [d7c612580f](https://linux-hardware.org/?probe=d7c612580f) | Jan 13, 2023 |
| ASUSTek       | X450LD                      | Notebook    | [859eb05149](https://linux-hardware.org/?probe=859eb05149) | Jan 13, 2023 |
| Dell          | Latitude 3320               | Notebook    | [f10d2a0741](https://linux-hardware.org/?probe=f10d2a0741) | Jan 13, 2023 |
| Dell          | Latitude 3320               | Notebook    | [613d7d50eb](https://linux-hardware.org/?probe=613d7d50eb) | Jan 13, 2023 |
| AZW           | Green G3                    | Desktop     | [be99013601](https://linux-hardware.org/?probe=be99013601) | Jan 13, 2023 |
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
| Gateway       | M-6854m                     | Notebook    | [76f293b62b](https://linux-hardware.org/?probe=76f293b62b) | Jan 12, 2023 |
| Dell          | Precision M4400             | Notebook    | [27da7825fb](https://linux-hardware.org/?probe=27da7825fb) | Jan 12, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [32acfb0bee](https://linux-hardware.org/?probe=32acfb0bee) | Jan 12, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [055d61383e](https://linux-hardware.org/?probe=055d61383e) | Jan 12, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [0001dd4164](https://linux-hardware.org/?probe=0001dd4164) | Jan 12, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [ba153350d8](https://linux-hardware.org/?probe=ba153350d8) | Jan 11, 2023 |
| ASRock        | X300-ITX                    | Desktop     | [9e74676ba4](https://linux-hardware.org/?probe=9e74676ba4) | Jan 11, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [b60a38ae60](https://linux-hardware.org/?probe=b60a38ae60) | Jan 11, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [204a5e8a8e](https://linux-hardware.org/?probe=204a5e8a8e) | Jan 11, 2023 |
| Acer          | Swift SF314-56              | Notebook    | [46aebbe972](https://linux-hardware.org/?probe=46aebbe972) | Jan 11, 2023 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [ee2147214c](https://linux-hardware.org/?probe=ee2147214c) | Jan 11, 2023 |
| HP            | ProLiant DL360p Gen8        | Server      | [9a698e2879](https://linux-hardware.org/?probe=9a698e2879) | Jan 11, 2023 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [c00918a4c8](https://linux-hardware.org/?probe=c00918a4c8) | Jan 11, 2023 |
| SLIMBOOK      | PRO                         | Notebook    | [551a4bd378](https://linux-hardware.org/?probe=551a4bd378) | Jan 11, 2023 |
| HP            | ProBook 430 G5              | Notebook    | [6403930d67](https://linux-hardware.org/?probe=6403930d67) | Jan 11, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [6c67fc3995](https://linux-hardware.org/?probe=6c67fc3995) | Jan 11, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [54793acf7e](https://linux-hardware.org/?probe=54793acf7e) | Jan 11, 2023 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [18ca1dbf8f](https://linux-hardware.org/?probe=18ca1dbf8f) | Jan 10, 2023 |
| Aquarius      | NS585                       | Notebook    | [6fbcdf4d2f](https://linux-hardware.org/?probe=6fbcdf4d2f) | Jan 10, 2023 |
| Medion        | TJ4125                      | Desktop     | [a82000e2e9](https://linux-hardware.org/?probe=a82000e2e9) | Jan 10, 2023 |
| HP            | Mini 110-1000               | Notebook    | [05c4656700](https://linux-hardware.org/?probe=05c4656700) | Jan 10, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [81a8002b99](https://linux-hardware.org/?probe=81a8002b99) | Jan 10, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [8367c27d81](https://linux-hardware.org/?probe=8367c27d81) | Jan 10, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [69ceed18f7](https://linux-hardware.org/?probe=69ceed18f7) | Jan 10, 2023 |
| Aquarius      | NS585                       | Notebook    | [2d37eb6524](https://linux-hardware.org/?probe=2d37eb6524) | Jan 10, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [286d590fda](https://linux-hardware.org/?probe=286d590fda) | Jan 10, 2023 |
| MPMAN         | CONVERTER 102               | Notebook    | [cc1eb56fbc](https://linux-hardware.org/?probe=cc1eb56fbc) | Jan 10, 2023 |
| HP            | 15                          | Notebook    | [f6b287dae1](https://linux-hardware.org/?probe=f6b287dae1) | Jan 10, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [8ea20821c8](https://linux-hardware.org/?probe=8ea20821c8) | Jan 10, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | Notebook    | [8d0b4a504d](https://linux-hardware.org/?probe=8d0b4a504d) | Jan 09, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [dea6736468](https://linux-hardware.org/?probe=dea6736468) | Jan 09, 2023 |
| Lenovo        | 1059 SDK0T76538 WIN 3556... | Desktop     | [a2660dcbfb](https://linux-hardware.org/?probe=a2660dcbfb) | Jan 09, 2023 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [d665a7f0ff](https://linux-hardware.org/?probe=d665a7f0ff) | Jan 09, 2023 |
| ASUSTek       | M2N-E                       | Desktop     | [2a7342c2cb](https://linux-hardware.org/?probe=2a7342c2cb) | Jan 09, 2023 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [d5c81ffaec](https://linux-hardware.org/?probe=d5c81ffaec) | Jan 09, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [e336a260d6](https://linux-hardware.org/?probe=e336a260d6) | Jan 09, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [43cc06ef1d](https://linux-hardware.org/?probe=43cc06ef1d) | Jan 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [e85e91a7f2](https://linux-hardware.org/?probe=e85e91a7f2) | Jan 09, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [395c417f92](https://linux-hardware.org/?probe=395c417f92) | Jan 09, 2023 |
| Intel         | NUC11ATBC4 M53051-303       | Mini pc     | [fcc9b4bbcc](https://linux-hardware.org/?probe=fcc9b4bbcc) | Jan 09, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [0e51eb7caa](https://linux-hardware.org/?probe=0e51eb7caa) | Jan 09, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [a14e62fdf8](https://linux-hardware.org/?probe=a14e62fdf8) | Jan 09, 2023 |
| Acer          | Predator G3-710             | Desktop     | [d47ca88192](https://linux-hardware.org/?probe=d47ca88192) | Jan 09, 2023 |
| HP            | 8053                        | Desktop     | [b377deb121](https://linux-hardware.org/?probe=b377deb121) | Jan 09, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [92205d303f](https://linux-hardware.org/?probe=92205d303f) | Jan 08, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [0e302b3507](https://linux-hardware.org/?probe=0e302b3507) | Jan 08, 2023 |
| Acer          | Aspire one 1-131            | Notebook    | [06c3411258](https://linux-hardware.org/?probe=06c3411258) | Jan 08, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [648dcae4c6](https://linux-hardware.org/?probe=648dcae4c6) | Jan 08, 2023 |
| Tactus        | GeoFlex 110                 | Convertible | [7aed5d93ba](https://linux-hardware.org/?probe=7aed5d93ba) | Jan 08, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [76c7287e2e](https://linux-hardware.org/?probe=76c7287e2e) | Jan 08, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [2b8206db29](https://linux-hardware.org/?probe=2b8206db29) | Jan 08, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [68fe02a04c](https://linux-hardware.org/?probe=68fe02a04c) | Jan 08, 2023 |
| ASUSTek       | K53U                        | Notebook    | [63849b1b5a](https://linux-hardware.org/?probe=63849b1b5a) | Jan 08, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [a4e777ea7d](https://linux-hardware.org/?probe=a4e777ea7d) | Jan 08, 2023 |
| Digma         | Pro Fortis M DN15P3-8CXN... | Notebook    | [077fd44029](https://linux-hardware.org/?probe=077fd44029) | Jan 08, 2023 |
| Hardkernel    | Odroid XU4                  | Soc         | [2188a4a04e](https://linux-hardware.org/?probe=2188a4a04e) | Jan 07, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2SX1... | Notebook    | [3c35917c78](https://linux-hardware.org/?probe=3c35917c78) | Jan 07, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [84fc096e00](https://linux-hardware.org/?probe=84fc096e00) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [0f0b86d738](https://linux-hardware.org/?probe=0f0b86d738) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | Notebook    | [e546680389](https://linux-hardware.org/?probe=e546680389) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | Notebook    | [d556eedbbf](https://linux-hardware.org/?probe=d556eedbbf) | Jan 07, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [9119962d1f](https://linux-hardware.org/?probe=9119962d1f) | Jan 07, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [d6a4584809](https://linux-hardware.org/?probe=d6a4584809) | Jan 07, 2023 |
| ASRock        | Q1900-ITX                   | Desktop     | [ac7df499e8](https://linux-hardware.org/?probe=ac7df499e8) | Jan 07, 2023 |
| Dell          | Latitude 2110               | Notebook    | [9910f8985b](https://linux-hardware.org/?probe=9910f8985b) | Jan 07, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [dcca84c5eb](https://linux-hardware.org/?probe=dcca84c5eb) | Jan 07, 2023 |
| HP            | Elite x2 1011 G1 Tablet     | Notebook    | [28c9b60939](https://linux-hardware.org/?probe=28c9b60939) | Jan 07, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [fa91397209](https://linux-hardware.org/?probe=fa91397209) | Jan 07, 2023 |
| Hardkernel    | Odroid XU4                  | Soc         | [5c688c4595](https://linux-hardware.org/?probe=5c688c4595) | Jan 06, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [9776545fc4](https://linux-hardware.org/?probe=9776545fc4) | Jan 06, 2023 |
| Toshiba       | Satellite C55Dt-A           | Notebook    | [f3cfb5dbb5](https://linux-hardware.org/?probe=f3cfb5dbb5) | Jan 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [9b0a8d487e](https://linux-hardware.org/?probe=9b0a8d487e) | Jan 06, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [4ceeb719c2](https://linux-hardware.org/?probe=4ceeb719c2) | Jan 06, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [d930da3de0](https://linux-hardware.org/?probe=d930da3de0) | Jan 06, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [a456485950](https://linux-hardware.org/?probe=a456485950) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [d069cbd46b](https://linux-hardware.org/?probe=d069cbd46b) | Jan 06, 2023 |
| &#er &&       | Aspire 5100                 | Notebook    | [26da9e8ee1](https://linux-hardware.org/?probe=26da9e8ee1) | Jan 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b329d8f40f](https://linux-hardware.org/?probe=b329d8f40f) | Jan 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1608711aa0](https://linux-hardware.org/?probe=1608711aa0) | Jan 06, 2023 |
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
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [b063be9f2e](https://linux-hardware.org/?probe=b063be9f2e) | Jan 04, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [872a58377f](https://linux-hardware.org/?probe=872a58377f) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [0042419ccb](https://linux-hardware.org/?probe=0042419ccb) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [82e42c0d42](https://linux-hardware.org/?probe=82e42c0d42) | Jan 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8f519746c2](https://linux-hardware.org/?probe=8f519746c2) | Jan 04, 2023 |
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
| Acer          | Aspire V3-574G              | Notebook    | [a889bba557](https://linux-hardware.org/?probe=a889bba557) | Jan 02, 2023 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [4a37b87ecf](https://linux-hardware.org/?probe=4a37b87ecf) | Jan 02, 2023 |
| Acer          | Aspire ES1-711              | Notebook    | [735e062168](https://linux-hardware.org/?probe=735e062168) | Jan 02, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [90603e4ab3](https://linux-hardware.org/?probe=90603e4ab3) | Jan 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [70c50fe035](https://linux-hardware.org/?probe=70c50fe035) | Jan 02, 2023 |
| MSI           | GE75 Raider 8SG             | Notebook    | [b6fa9be350](https://linux-hardware.org/?probe=b6fa9be350) | Jan 02, 2023 |
| Lenovo        | 31A7 SDK0J40697 WIN 3305... | Mini pc     | [efa2748c95](https://linux-hardware.org/?probe=efa2748c95) | Jan 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [b54f3aab7b](https://linux-hardware.org/?probe=b54f3aab7b) | Jan 02, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [42e877ed10](https://linux-hardware.org/?probe=42e877ed10) | Jan 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [8d4934bc09](https://linux-hardware.org/?probe=8d4934bc09) | Jan 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0D    | Notebook    | [a1f966e5e8](https://linux-hardware.org/?probe=a1f966e5e8) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [08fb8de608](https://linux-hardware.org/?probe=08fb8de608) | Jan 02, 2023 |
| Lenovo        | ThinkPad T430u 33519LC      | Notebook    | [87af3fa7f0](https://linux-hardware.org/?probe=87af3fa7f0) | Jan 02, 2023 |
| ASUSTek       | ZenBook UX333FN_U3300FN     | Notebook    | [750a40a3cc](https://linux-hardware.org/?probe=750a40a3cc) | Jan 02, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [2c33e446d4](https://linux-hardware.org/?probe=2c33e446d4) | Jan 02, 2023 |
| Lenovo        | ThinkPad X260 20F5005NAU    | Notebook    | [3f68b8438c](https://linux-hardware.org/?probe=3f68b8438c) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [bca75efbe5](https://linux-hardware.org/?probe=bca75efbe5) | Jan 02, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [2396307897](https://linux-hardware.org/?probe=2396307897) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c96c7d74fe](https://linux-hardware.org/?probe=c96c7d74fe) | Jan 02, 2023 |
| Gigabyte      | AX370-Gaming K5-CF          | Desktop     | [8b0b477726](https://linux-hardware.org/?probe=8b0b477726) | Jan 02, 2023 |
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
| ASRock        | A320M-DGS                   | Desktop     | [a9df519d4f](https://linux-hardware.org/?probe=a9df519d4f) | Dec 31, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [3710331d81](https://linux-hardware.org/?probe=3710331d81) | Dec 31, 2022 |
| Lenovo        | IdeaPad Y560                | Notebook    | [c9d3a1d0a3](https://linux-hardware.org/?probe=c9d3a1d0a3) | Dec 31, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [5775c77a91](https://linux-hardware.org/?probe=5775c77a91) | Dec 31, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [b1220a23ad](https://linux-hardware.org/?probe=b1220a23ad) | Dec 31, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [31343e35f0](https://linux-hardware.org/?probe=31343e35f0) | Dec 31, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [dff8a56537](https://linux-hardware.org/?probe=dff8a56537) | Dec 30, 2022 |
| HP            | Compaq 6710b (KE207ES#AB... | Notebook    | [d7d0be3872](https://linux-hardware.org/?probe=d7d0be3872) | Dec 30, 2022 |
| ASRock        | J3455-ITX                   | Desktop     | [4f45d532ac](https://linux-hardware.org/?probe=4f45d532ac) | Dec 30, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [4ea88219d8](https://linux-hardware.org/?probe=4ea88219d8) | Dec 30, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [c8a80649d2](https://linux-hardware.org/?probe=c8a80649d2) | Dec 30, 2022 |
| Supermicro    | X11SRA-RF                   | Server      | [2887a82948](https://linux-hardware.org/?probe=2887a82948) | Dec 30, 2022 |
| Supermicro    | X11SRA-RF                   | Server      | [e5f0b1d802](https://linux-hardware.org/?probe=e5f0b1d802) | Dec 30, 2022 |
| Supermicro    | X11SRA-RF                   | Server      | [cd84ddc342](https://linux-hardware.org/?probe=cd84ddc342) | Dec 30, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | Desktop     | [7b55955e2a](https://linux-hardware.org/?probe=7b55955e2a) | Dec 30, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [a295f18c9f](https://linux-hardware.org/?probe=a295f18c9f) | Dec 30, 2022 |
| HP            | 255 G3                      | Notebook    | [89d6bd459c](https://linux-hardware.org/?probe=89d6bd459c) | Dec 30, 2022 |
| Toshiba       | Satellite L775-12V          | Notebook    | [2c601f6366](https://linux-hardware.org/?probe=2c601f6366) | Dec 29, 2022 |
| HP            | 339A                        | Desktop     | [8e0b785427](https://linux-hardware.org/?probe=8e0b785427) | Dec 29, 2022 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [c38ca6386e](https://linux-hardware.org/?probe=c38ca6386e) | Dec 29, 2022 |
| Lenovo        | ThinkPad T470p 20J7S1JT0... | Notebook    | [4b7bbb186f](https://linux-hardware.org/?probe=4b7bbb186f) | Dec 29, 2022 |
| Supermicro    | H8SCM                       | Server      | [9ee42dcf6f](https://linux-hardware.org/?probe=9ee42dcf6f) | Dec 29, 2022 |
| MACHCREATO... | AB                          | Notebook    | [52a6beb872](https://linux-hardware.org/?probe=52a6beb872) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | Notebook    | [5bf3ff5c0e](https://linux-hardware.org/?probe=5bf3ff5c0e) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | Notebook    | [4f63c4474c](https://linux-hardware.org/?probe=4f63c4474c) | Dec 29, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [50149bf9e3](https://linux-hardware.org/?probe=50149bf9e3) | Dec 29, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [b0a40a3ac0](https://linux-hardware.org/?probe=b0a40a3ac0) | Dec 29, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [716ba7f970](https://linux-hardware.org/?probe=716ba7f970) | Dec 29, 2022 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [6aad572cd5](https://linux-hardware.org/?probe=6aad572cd5) | Dec 29, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [af1655497e](https://linux-hardware.org/?probe=af1655497e) | Dec 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [34b6109940](https://linux-hardware.org/?probe=34b6109940) | Dec 29, 2022 |
| HP            | ProBook 6570b               | Notebook    | [46fd918b7c](https://linux-hardware.org/?probe=46fd918b7c) | Dec 29, 2022 |
| HP            | Pavilion g7                 | Notebook    | [444363b7ec](https://linux-hardware.org/?probe=444363b7ec) | Dec 29, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [4239e2fa3c](https://linux-hardware.org/?probe=4239e2fa3c) | Dec 29, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [7881f027ea](https://linux-hardware.org/?probe=7881f027ea) | Dec 29, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [c1e5e82fbb](https://linux-hardware.org/?probe=c1e5e82fbb) | Dec 29, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [457c2ae4ae](https://linux-hardware.org/?probe=457c2ae4ae) | Dec 28, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [fdfd0f21c7](https://linux-hardware.org/?probe=fdfd0f21c7) | Dec 28, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [41c7a16579](https://linux-hardware.org/?probe=41c7a16579) | Dec 28, 2022 |
| Toshiba       | Satellite L455D             | Notebook    | [35c085aa82](https://linux-hardware.org/?probe=35c085aa82) | Dec 28, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [27f58a8ad1](https://linux-hardware.org/?probe=27f58a8ad1) | Dec 28, 2022 |
| HP            | ProLiant ML30 Gen9          | Desktop     | [174e7e831b](https://linux-hardware.org/?probe=174e7e831b) | Dec 28, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [c29088a63f](https://linux-hardware.org/?probe=c29088a63f) | Dec 28, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [422238387a](https://linux-hardware.org/?probe=422238387a) | Dec 28, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [7c60cc0210](https://linux-hardware.org/?probe=7c60cc0210) | Dec 28, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [72f770277e](https://linux-hardware.org/?probe=72f770277e) | Dec 28, 2022 |
| HP            | ProBook 6470b               | Notebook    | [055705b3f2](https://linux-hardware.org/?probe=055705b3f2) | Dec 28, 2022 |
| HP            | 158A                        | Desktop     | [c80bfd7c30](https://linux-hardware.org/?probe=c80bfd7c30) | Dec 28, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [ec0ad4d293](https://linux-hardware.org/?probe=ec0ad4d293) | Dec 28, 2022 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [c4d1d971d1](https://linux-hardware.org/?probe=c4d1d971d1) | Dec 28, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [2ceb80faeb](https://linux-hardware.org/?probe=2ceb80faeb) | Dec 28, 2022 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [0f71bbaf67](https://linux-hardware.org/?probe=0f71bbaf67) | Dec 28, 2022 |
| ASUSTek       | A4110                       | All in one  | [fa417dc5c7](https://linux-hardware.org/?probe=fa417dc5c7) | Dec 28, 2022 |
| ASRock        | J3455-ITX                   | Desktop     | [6e628aeb01](https://linux-hardware.org/?probe=6e628aeb01) | Dec 28, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [10dce91da1](https://linux-hardware.org/?probe=10dce91da1) | Dec 27, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [321cc72064](https://linux-hardware.org/?probe=321cc72064) | Dec 27, 2022 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [48f161dfc8](https://linux-hardware.org/?probe=48f161dfc8) | Dec 27, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [d174ffb318](https://linux-hardware.org/?probe=d174ffb318) | Dec 27, 2022 |
| MSI           | GE62 2QC                    | Notebook    | [dbd69d70ac](https://linux-hardware.org/?probe=dbd69d70ac) | Dec 27, 2022 |
| Dell          | 0M017G A00                  | Desktop     | [5c41315695](https://linux-hardware.org/?probe=5c41315695) | Dec 27, 2022 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [042fb842d2](https://linux-hardware.org/?probe=042fb842d2) | Dec 27, 2022 |
| Panasonic     | FZ55-2                      | Notebook    | [1699b7c3b2](https://linux-hardware.org/?probe=1699b7c3b2) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [78c6c15502](https://linux-hardware.org/?probe=78c6c15502) | Dec 27, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [06cba3f478](https://linux-hardware.org/?probe=06cba3f478) | Dec 27, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [210f0c0375](https://linux-hardware.org/?probe=210f0c0375) | Dec 27, 2022 |
| Gigabyte      | 990FXA-UD3 R5               | Desktop     | [734c3742b1](https://linux-hardware.org/?probe=734c3742b1) | Dec 27, 2022 |
| Gigabyte      | 990FXA-UD3 R5               | Desktop     | [bb6dddc780](https://linux-hardware.org/?probe=bb6dddc780) | Dec 27, 2022 |
| ASRock        | Brazos                      | Desktop     | [f5183b395b](https://linux-hardware.org/?probe=f5183b395b) | Dec 27, 2022 |
| Notebook      | L14xMU                      | Notebook    | [7644bc65e2](https://linux-hardware.org/?probe=7644bc65e2) | Dec 27, 2022 |
| Dell          | Inspiron 1012               | Notebook    | [3dd6b8a416](https://linux-hardware.org/?probe=3dd6b8a416) | Dec 26, 2022 |
| Dell          | 02YRK5 A02                  | Desktop     | [56dc5ff1b9](https://linux-hardware.org/?probe=56dc5ff1b9) | Dec 26, 2022 |
| Exo           | Smart Serie M               | Notebook    | [942ee3b035](https://linux-hardware.org/?probe=942ee3b035) | Dec 26, 2022 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [3bb1c5cc47](https://linux-hardware.org/?probe=3bb1c5cc47) | Dec 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [29a54c4976](https://linux-hardware.org/?probe=29a54c4976) | Dec 26, 2022 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [2618b85414](https://linux-hardware.org/?probe=2618b85414) | Dec 26, 2022 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [6ad649ad46](https://linux-hardware.org/?probe=6ad649ad46) | Dec 26, 2022 |
| Gigabyte      | B360M H                     | Desktop     | [2f0d1b1c8d](https://linux-hardware.org/?probe=2f0d1b1c8d) | Dec 26, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d90a9cdcd3](https://linux-hardware.org/?probe=d90a9cdcd3) | Dec 26, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fc0eac877c](https://linux-hardware.org/?probe=fc0eac877c) | Dec 26, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [67fee9ab39](https://linux-hardware.org/?probe=67fee9ab39) | Dec 26, 2022 |
| Acer          | Aspire ES1-533              | Notebook    | [3b5fa6d85a](https://linux-hardware.org/?probe=3b5fa6d85a) | Dec 26, 2022 |
| ASUSTek       | M3A32-MVP DELUXE            | Desktop     | [0fa5809533](https://linux-hardware.org/?probe=0fa5809533) | Dec 26, 2022 |
| Matrox Ele... | 4GPMOBIL 7449-03-0          | Desktop     | [c02a37a124](https://linux-hardware.org/?probe=c02a37a124) | Dec 26, 2022 |
| Lenovo        | ThinkPad X250 20CLS1UB00    | Notebook    | [fc8b2899fa](https://linux-hardware.org/?probe=fc8b2899fa) | Dec 25, 2022 |
| SANTECH       | NHx0DB,DE                   | Notebook    | [a0996d42bd](https://linux-hardware.org/?probe=a0996d42bd) | Dec 25, 2022 |
| HP            | 470 G8 Notebook PC          | Notebook    | [6d77c48324](https://linux-hardware.org/?probe=6d77c48324) | Dec 25, 2022 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [6ac63aca4f](https://linux-hardware.org/?probe=6ac63aca4f) | Dec 25, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [8855d29d69](https://linux-hardware.org/?probe=8855d29d69) | Dec 25, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [b5eaa2b6aa](https://linux-hardware.org/?probe=b5eaa2b6aa) | Dec 25, 2022 |
| Unknown       | Unknown                     | Soc         | [95c95c980d](https://linux-hardware.org/?probe=95c95c980d) | Dec 25, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [5977afc830](https://linux-hardware.org/?probe=5977afc830) | Dec 25, 2022 |
| ASUSTek       | G751JT                      | Notebook    | [16e989ff99](https://linux-hardware.org/?probe=16e989ff99) | Dec 25, 2022 |
| Dell          | Latitude E6520              | Notebook    | [33a51c934d](https://linux-hardware.org/?probe=33a51c934d) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [ea09a6daa8](https://linux-hardware.org/?probe=ea09a6daa8) | Dec 25, 2022 |
| Dell          | 00TD00 A00                  | All in one  | [84beba0484](https://linux-hardware.org/?probe=84beba0484) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [45737153e4](https://linux-hardware.org/?probe=45737153e4) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [42221f61fb](https://linux-hardware.org/?probe=42221f61fb) | Dec 25, 2022 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [8a5b919c91](https://linux-hardware.org/?probe=8a5b919c91) | Dec 24, 2022 |
| Medion        | E122X                       | Notebook    | [6e4e34bcc3](https://linux-hardware.org/?probe=6e4e34bcc3) | Dec 24, 2022 |
| Medion        | E122X                       | Notebook    | [bf41c45a7d](https://linux-hardware.org/?probe=bf41c45a7d) | Dec 24, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [096d4fc8c2](https://linux-hardware.org/?probe=096d4fc8c2) | Dec 24, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [4d19273307](https://linux-hardware.org/?probe=4d19273307) | Dec 24, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [f7af4b1164](https://linux-hardware.org/?probe=f7af4b1164) | Dec 24, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [b95892f2dc](https://linux-hardware.org/?probe=b95892f2dc) | Dec 24, 2022 |
| ASUSTek       | WS C422 DC                  | Desktop     | [7be7c81575](https://linux-hardware.org/?probe=7be7c81575) | Dec 24, 2022 |
| Supermicro    | X11SRA-RF                   | Server      | [efdf519660](https://linux-hardware.org/?probe=efdf519660) | Dec 24, 2022 |
| ASUSTek       | WS C422 DC                  | Desktop     | [526414fd8f](https://linux-hardware.org/?probe=526414fd8f) | Dec 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [c5f2f2db53](https://linux-hardware.org/?probe=c5f2f2db53) | Dec 24, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [39f35288d4](https://linux-hardware.org/?probe=39f35288d4) | Dec 24, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Debian 11                       | 5573      | 62.83%  |
| Debian 10                       | 1746      | 19.68%  |
| Debian Testing                  | 644       | 7.26%   |
| Debian 9                        | 321       | 3.62%   |
| Debian Unstable                 | 263       | 2.97%   |
| Debian                          | 219       | 2.47%   |
| Debian 11-updates               | 46        | 0.52%   |
| Debian 8                        | 38        | 0.43%   |
| Debian Testing/unstable         | 5         | 0.06%   |
| Debian Sid                      | 5         | 0.06%   |
| Debian 7                        | 5         | 0.06%   |
| Debian Testing-proposed-updates | 3         | 0.03%   |
| Debian 99                       | 1         | 0.01%   |
| Debian 6                        | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Debian | 8625      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Computers | Percent |
|-----------------|-----------|---------|
| 5.10.0-8-amd64  | 979       | 9.95%   |
| 5.10.0-7-amd64  | 691       | 7.02%   |
| 5.10.0-10-amd64 | 575       | 5.85%   |
| 5.10.0-16-amd64 | 370       | 3.76%   |
| 5.10.0-9-amd64  | 327       | 3.32%   |
| 5.10.0-19-amd64 | 287       | 2.92%   |
| 5.10.0-18-amd64 | 284       | 2.89%   |
| 5.10.0-13-amd64 | 261       | 2.65%   |
| 5.10.0-20-amd64 | 247       | 2.51%   |
| 5.10.0-11-amd64 | 194       | 1.97%   |
| 5.10.0-21-amd64 | 169       | 1.72%   |
| 5.10.0-2-amd64  | 156       | 1.59%   |
| 4.19.0-6-amd64  | 145       | 1.47%   |
| 4.19.0-9-amd64  | 143       | 1.45%   |
| 5.10.0-14-amd64 | 141       | 1.43%   |
| 5.10.0-17-amd64 | 125       | 1.27%   |
| 4.19.0-13-amd64 | 125       | 1.27%   |
| 4.19.0-8-amd64  | 120       | 1.22%   |
| 4.19.0-16-amd64 | 109       | 1.11%   |
| 4.19.0-14-amd64 | 104       | 1.06%   |
| 5.10.0-15-amd64 | 96        | 0.98%   |
| 5.15.0-2-amd64  | 95        | 0.97%   |
| 4.19.0-17-amd64 | 94        | 0.96%   |
| 4.19.0-12-amd64 | 88        | 0.89%   |
| 4.19.0-10-amd64 | 87        | 0.88%   |
| 5.10.0-12-amd64 | 73        | 0.74%   |
| 4.9.0-8-amd64   | 70        | 0.71%   |
| 5.10.0-6-amd64  | 66        | 0.67%   |
| 5.6.0-2-amd64   | 53        | 0.54%   |
| 5.18.0-2-amd64  | 52        | 0.53%   |
| 6.0.0-6-amd64   | 49        | 0.5%    |
| 4.19.0-5-amd64  | 48        | 0.49%   |
| 5.4.0-4-amd64   | 45        | 0.46%   |
| 5.7.0-1-amd64   | 44        | 0.45%   |
| 5.10.0-3-amd64  | 44        | 0.45%   |
| 5.17.0-1-amd64  | 42        | 0.43%   |
| 5.19.0-2-amd64  | 41        | 0.42%   |
| 6.0.0-2-amd64   | 40        | 0.41%   |
| 5.19.0-1-amd64  | 40        | 0.41%   |
| 4.19.0-11-amd64 | 40        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 4987      | 54.42%  |
| 4.19.0  | 1233      | 13.45%  |
| 4.9.0   | 241       | 2.63%   |
| 6.0.0   | 213       | 2.32%   |
| 5.18.0  | 197       | 2.15%   |
| 5.15.0  | 161       | 1.76%   |
| 5.9.0   | 150       | 1.64%   |
| 5.16.0  | 130       | 1.42%   |
| 5.7.0   | 121       | 1.32%   |
| 5.8.0   | 120       | 1.31%   |
| 5.4.0   | 118       | 1.29%   |
| 5.19.0  | 115       | 1.25%   |
| 5.6.0   | 100       | 1.09%   |
| 5.14.0  | 91        | 0.99%   |
| 6.1.0   | 73        | 0.8%    |
| 5.17.0  | 71        | 0.77%   |
| 5.13.19 | 58        | 0.63%   |
| 5.3.0   | 39        | 0.43%   |
| 5.5.0   | 32        | 0.35%   |
| 5.11.22 | 27        | 0.29%   |
| 5.15.74 | 25        | 0.27%   |
| 5.2.0   | 21        | 0.23%   |
| 4.18.0  | 21        | 0.23%   |
| 5.15.32 | 19        | 0.21%   |
| 5.15.39 | 18        | 0.2%    |
| 3.16.0  | 18        | 0.2%    |
| 5.15.35 | 17        | 0.19%   |
| 5.15.30 | 17        | 0.19%   |
| 5.4.106 | 15        | 0.16%   |
| 5.15.76 | 15        | 0.16%   |
| 5.10.92 | 15        | 0.16%   |
| 5.15.53 | 14        | 0.15%   |
| 4.15.18 | 14        | 0.15%   |
| 5.15.61 | 13        | 0.14%   |
| 5.4.78  | 11        | 0.12%   |
| 5.15.84 | 11        | 0.12%   |
| 5.13.0  | 10        | 0.11%   |
| 5.4.65  | 9         | 0.1%    |
| 5.15.83 | 9         | 0.1%    |
| 5.12.0  | 9         | 0.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 5092      | 55.82%  |
| 4.19    | 1251      | 13.71%  |
| 5.15    | 368       | 4.03%   |
| 4.9     | 252       | 2.76%   |
| 6.0     | 227       | 2.49%   |
| 5.4     | 218       | 2.39%   |
| 5.18    | 210       | 2.3%    |
| 5.9     | 159       | 1.74%   |
| 5.16    | 140       | 1.53%   |
| 5.19    | 134       | 1.47%   |
| 5.8     | 132       | 1.45%   |
| 5.7     | 129       | 1.41%   |
| 5.6     | 110       | 1.21%   |
| 5.14    | 101       | 1.11%   |
| 5.17    | 86        | 0.94%   |
| 6.1     | 81        | 0.89%   |
| 5.13    | 81        | 0.89%   |
| 5.3     | 64        | 0.7%    |
| 5.11    | 50        | 0.55%   |
| 5.5     | 38        | 0.42%   |
| 5.2     | 26        | 0.29%   |
| 4.18    | 22        | 0.24%   |
| 4.15    | 19        | 0.21%   |
| 3.16    | 18        | 0.2%    |
| 5.12    | 16        | 0.18%   |
| 5.0     | 13        | 0.14%   |
| 4.4     | 12        | 0.13%   |
| 5       | 11        | 0.12%   |
| 4.17    | 8         | 0.09%   |
| 4.1     | 8         | 0.09%   |
| 4.14    | 7         | 0.08%   |
| 5.1     | 6         | 0.07%   |
| 3.10    | 4         | 0.04%   |
| 4.8     | 3         | 0.03%   |
| 4.20    | 3         | 0.03%   |
| 4.16    | 3         | 0.03%   |
| 4.13    | 3         | 0.03%   |
| 4.10    | 2         | 0.02%   |
| 3.18    | 2         | 0.02%   |
| 5.4.104 | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 8075      | 93.6%   |
| i686    | 293       | 3.4%    |
| aarch64 | 182       | 2.11%   |
| armv7l  | 51        | 0.59%   |
| riscv64 | 9         | 0.1%    |
| ppc64   | 7         | 0.08%   |
| i586    | 3         | 0.03%   |
| ppc64le | 2         | 0.02%   |
| mips64  | 2         | 0.02%   |
| sparc64 | 1         | 0.01%   |
| sh4a    | 1         | 0.01%   |
| armv6l  | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 2830      | 32.06%  |
| GNOME             | 1968      | 22.29%  |
| XFCE              | 1090      | 12.35%  |
| KDE5              | 1007      | 11.41%  |
| MATE              | 368       | 4.17%   |
| X-Cinnamon        | 288       | 3.26%   |
| LXDE              | 262       | 2.97%   |
| Cinnamon          | 251       | 2.84%   |
| KDE               | 209       | 2.37%   |
| LXQt              | 131       | 1.48%   |
| i3                | 125       | 1.42%   |
| openbox           | 56        | 0.63%   |
| GNOME Flashback   | 52        | 0.59%   |
| lightdm-xsession  | 44        | 0.5%    |
| Budgie            | 24        | 0.27%   |
| Trinity           | 23        | 0.26%   |
| GNOME Classic     | 22        | 0.25%   |
| awesome           | 9         | 0.1%    |
| fluxbox           | 8         | 0.09%   |
| sway              | 7         | 0.08%   |
| KDE4              | 6         | 0.07%   |
| Enlightenment     | 5         | 0.06%   |
| ICEWM             | 4         | 0.05%   |
| DWM               | 4         | 0.05%   |
| bspwm             | 4         | 0.05%   |
| xmonad            | 3         | 0.03%   |
| x-session-manager | 3         | 0.03%   |
| default           | 3         | 0.03%   |
| Cutefish          | 3         | 0.03%   |
| Unity             | 2         | 0.02%   |
| Phosh:GNOME       | 2         | 0.02%   |
| GNUstep           | 2         | 0.02%   |
| fvwm              | 2         | 0.02%   |
| wmaker-common     | 1         | 0.01%   |
| UKUI              | 1         | 0.01%   |
| matchbox          | 1         | 0.01%   |
| jwm               | 1         | 0.01%   |
| i3-with-shmlog    | 1         | 0.01%   |
| i3-gaps           | 1         | 0.01%   |
| gnome-xorg        | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 4671      | 53.17%  |
| Unknown     | 1926      | 21.92%  |
| Wayland     | 1299      | 14.79%  |
| Tty         | 885       | 10.07%  |
| Web         | 2         | 0.02%   |
| Unspecified | 2         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4043      | 45.83%  |
| GDM     | 1425      | 16.15%  |
| LightDM | 1350      | 15.3%   |
| SDDM    | 976       | 11.06%  |
| TDM     | 597       | 6.77%   |
| GDM3    | 326       | 3.7%    |
| XDM     | 37        | 0.42%   |
| SLiM    | 28        | 0.32%   |
| NODM    | 16        | 0.18%   |
| KDM     | 12        | 0.14%   |
| LXDM    | 8         | 0.09%   |
| WDM     | 2         | 0.02%   |
| Ly      | 2         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2795      | 31.88%  |
| Unknown | 1393      | 15.89%  |
| ru_RU   | 1058      | 12.07%  |
| de_DE   | 507       | 5.78%   |
| fr_FR   | 426       | 4.86%   |
| en_GB   | 420       | 4.79%   |
| pt_BR   | 266       | 3.03%   |
| es_ES   | 240       | 2.74%   |
| it_IT   | 209       | 2.38%   |
| C       | 128       | 1.46%   |
| pl_PL   | 127       | 1.45%   |
| en_CA   | 111       | 1.27%   |
| en_AU   | 105       | 1.2%    |
| zh_CN   | 60        | 0.68%   |
| es_MX   | 58        | 0.66%   |
| en_IN   | 56        | 0.64%   |
| en_IE   | 47        | 0.54%   |
| es_AR   | 45        | 0.51%   |
| hu_HU   | 43        | 0.49%   |
| es_VE   | 37        | 0.42%   |
| es_CL   | 35        | 0.4%    |
| de_CH   | 33        | 0.38%   |
| ja_JP   | 31        | 0.35%   |
| pt_PT   | 30        | 0.34%   |
| de_AT   | 30        | 0.34%   |
| nl_NL   | 25        | 0.29%   |
| cs_CZ   | 24        | 0.27%   |
| en_NZ   | 23        | 0.26%   |
| en_ZA   | 21        | 0.24%   |
| sv_SE   | 19        | 0.22%   |
| fi_FI   | 19        | 0.22%   |
| nl_BE   | 16        | 0.18%   |
| fr_BE   | 16        | 0.18%   |
| ru_UA   | 15        | 0.17%   |
| es_CO   | 15        | 0.17%   |
| ca_ES   | 14        | 0.16%   |
| uk_UA   | 12        | 0.14%   |
| ko_KR   | 12        | 0.14%   |
| fr_CH   | 12        | 0.14%   |
| en_SG   | 12        | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 4561      | 52.23%  |
| BIOS | 4172      | 47.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type       | Computers | Percent |
|------------|-----------|---------|
| Ext4       | 6094      | 70.08%  |
| Overlay    | 1806      | 20.77%  |
| Btrfs      | 301       | 3.46%   |
| Unknown    | 168       | 1.93%   |
| Zfs        | 120       | 1.38%   |
| Xfs        | 105       | 1.21%   |
| Ext3       | 28        | 0.32%   |
| Ext2       | 24        | 0.28%   |
| Tmpfs      | 16        | 0.18%   |
| Rootfs     | 14        | 0.16%   |
| Aufs       | 7         | 0.08%   |
| F2fs       | 6         | 0.07%   |
| XXXXXXX    | 2         | 0.02%   |
| Ubifs      | 2         | 0.02%   |
| Jfs        | 2         | 0.02%   |
| Fuse.sshfs | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 4845      | 55.13%  |
| MBR     | 2242      | 25.51%  |
| Unknown | 1701      | 19.36%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 7117      | 81.54%  |
| Yes       | 1611      | 18.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 6147      | 70.44%  |
| Yes       | 2580      | 29.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1356      | 15.72%  |
| Lenovo                  | 1271      | 14.74%  |
| Hewlett-Packard         | 923       | 10.7%   |
| Dell                    | 919       | 10.66%  |
| Apple                   | 660       | 7.65%   |
| Gigabyte Technology     | 571       | 6.62%   |
| MSI                     | 413       | 4.79%   |
| ASRock                  | 346       | 4.01%   |
| Acer                    | 316       | 3.66%   |
| Intel                   | 199       | 2.31%   |
| Google                  | 146       | 1.69%   |
| Raspberry Pi Foundation | 122       | 1.41%   |
| Unknown                 | 119       | 1.38%   |
| Supermicro              | 83        | 0.96%   |
| Toshiba                 | 73        | 0.85%   |
| Samsung Electronics     | 73        | 0.85%   |
| Fujitsu                 | 52        | 0.6%    |
| ECS                     | 51        | 0.59%   |
| Aquarius                | 47        | 0.54%   |
| HUAWEI                  | 42        | 0.49%   |
| Sony                    | 39        | 0.45%   |
| Foxconn                 | 37        | 0.43%   |
| Notebook                | 27        | 0.31%   |
| AZW                     | 26        | 0.3%    |
| Positivo                | 25        | 0.29%   |
| ASRockRack              | 25        | 0.29%   |
| Medion                  | 23        | 0.27%   |
| IBM                     | 22        | 0.26%   |
| Pegatron                | 20        | 0.23%   |
| Biostar                 | 19        | 0.22%   |
| Fujitsu Siemens         | 18        | 0.21%   |
| Microsoft               | 17        | 0.2%    |
| Alienware               | 17        | 0.2%    |
| Panasonic               | 14        | 0.16%   |
| Packard Bell            | 14        | 0.16%   |
| sunxi                   | 13        | 0.15%   |
| Hardkernel              | 13        | 0.15%   |
| AMI                     | 13        | 0.15%   |
| Pine Microsystems       | 12        | 0.14%   |
| Huanan                  | 12        | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Apple MacBook5,2                          | 307       | 3.56%   |
| Unknown                                   | 147       | 1.7%    |
| ASUS All Series                           | 115       | 1.33%   |
| Lenovo ThinkPad L13 Yoga Gen 2 20VK0019US | 114       | 1.32%   |
| Apple MacBookAir7,2                       | 77        | 0.89%   |
| Apple MacBookAir7,1                       | 77        | 0.89%   |
| Google Enguarde                           | 74        | 0.86%   |
| Apple MacBook2,1                          | 56        | 0.65%   |
| ASUS S20 K29                              | 55        | 0.64%   |
| Aquarius NS585                            | 44        | 0.51%   |
| MSI MS-7996                               | 38        | 0.44%   |
| RPi Raspberry Pi 4 Model B Rev 1.4        | 26        | 0.3%    |
| Lenovo ThinkPad E475 20H40006US           | 24        | 0.28%   |
| Supermicro Super Server                   | 23        | 0.27%   |
| MSI MS-7817                               | 23        | 0.27%   |
| Google Terra                              | 23        | 0.27%   |
| Apple MacBook4,1                          | 23        | 0.27%   |
| HP Notebook                               | 22        | 0.26%   |
| ECS G31T-M9                               | 21        | 0.24%   |
| RPi Raspberry Pi 4 Model B Rev 1.2        | 20        | 0.23%   |
| RPi Raspberry Pi 3 Model B Rev 1.2        | 20        | 0.23%   |
| ASRock H470M-HVS                          | 20        | 0.23%   |
| Dell OptiPlex 7010                        | 19        | 0.22%   |
| ASUS PRIME H510M-A                        | 19        | 0.22%   |
| RPi Raspberry Pi 4 Model B Rev 1.1        | 18        | 0.21%   |
| Gigabyte H81M-S2V                         | 18        | 0.21%   |
| HP Pavilion g6                            | 17        | 0.2%    |
| Lenovo ThinkPad 13 2nd Gen 20J10046US     | 16        | 0.19%   |
| Gigabyte H410M S2H                        | 16        | 0.19%   |
| Gigabyte B450M DS3H                       | 16        | 0.19%   |
| ECS H61H2-M13                             | 16        | 0.19%   |
| Acer Aspire A315-23                       | 16        | 0.19%   |
| ASUS P8H61-M LX3 R2.0                     | 15        | 0.17%   |
| ASUS 1005HA                               | 15        | 0.17%   |
| ASUS TUF Gaming X570-PLUS                 | 14        | 0.16%   |
| ASUS PRIME A320M-K                        | 13        | 0.15%   |
| ASRock B450M Pro4                         | 13        | 0.15%   |
| MSI MS-7C56                               | 12        | 0.14%   |
| Dell Latitude E7440                       | 12        | 0.14%   |
| ASUS PRIME B450M-A                        | 12        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 784       | 9.09%   |
| Apple MacBook5     | 308       | 3.57%   |
| Dell Latitude      | 250       | 2.9%    |
| Dell Inspiron      | 224       | 2.6%    |
| Acer Aspire        | 202       | 2.34%   |
| ASUS PRIME         | 178       | 2.06%   |
| Lenovo IdeaPad     | 174       | 2.02%   |
| Apple MacBookAir7  | 154       | 1.79%   |
| Unknown            | 147       | 1.7%    |
| HP EliteBook       | 139       | 1.61%   |
| RPi Raspberry      | 122       | 1.41%   |
| Dell OptiPlex      | 119       | 1.38%   |
| HP Pavilion        | 115       | 1.33%   |
| ASUS All           | 115       | 1.33%   |
| HP Compaq          | 96        | 1.11%   |
| Dell Precision     | 89        | 1.03%   |
| ASUS ROG           | 88        | 1.02%   |
| HP ProBook         | 85        | 0.99%   |
| HP Laptop          | 85        | 0.99%   |
| Dell XPS           | 79        | 0.92%   |
| Google Enguarde    | 74        | 0.86%   |
| Dell Vostro        | 68        | 0.79%   |
| ASUS TUF           | 66        | 0.77%   |
| Lenovo ThinkCentre | 64        | 0.74%   |
| ASUS VivoBook      | 59        | 0.68%   |
| Toshiba Satellite  | 56        | 0.65%   |
| Apple MacBook2     | 56        | 0.65%   |
| ASUS S20           | 55        | 0.64%   |
| Dell PowerEdge     | 49        | 0.57%   |
| HP ProLiant        | 45        | 0.52%   |
| Aquarius NS585     | 44        | 0.51%   |
| MSI MS-7996        | 38        | 0.44%   |
| Gigabyte B450M     | 36        | 0.42%   |
| ASUS P8H61-M       | 34        | 0.39%   |
| Lenovo Yoga        | 32        | 0.37%   |
| ASUS ZenBook       | 32        | 0.37%   |
| HP 250             | 29        | 0.34%   |
| Lenovo Legion      | 28        | 0.32%   |
| HP ENVY            | 28        | 0.32%   |
| HP ZBook           | 27        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 928       | 10.76%  |
| 2019    | 756       | 8.77%   |
| 2018    | 693       | 8.03%   |
| 2021    | 633       | 7.34%   |
| 2009    | 632       | 7.33%   |
| 2012    | 623       | 7.22%   |
| 2017    | 521       | 6.04%   |
| 2011    | 520       | 6.03%   |
| 2013    | 514       | 5.96%   |
| 2015    | 481       | 5.58%   |
| 2016    | 452       | 5.24%   |
| 2014    | 393       | 4.56%   |
| 2010    | 335       | 3.88%   |
| 2008    | 270       | 3.13%   |
| 2022    | 267       | 3.1%    |
| Unknown | 222       | 2.57%   |
| 2007    | 220       | 2.55%   |
| 2006    | 74        | 0.86%   |
| 2005    | 46        | 0.53%   |
| 2004    | 19        | 0.22%   |
| 2003    | 16        | 0.19%   |
| 2002    | 3         | 0.03%   |
| 2001    | 3         | 0.03%   |
| 2023    | 2         | 0.02%   |
| 2000    | 2         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 4414      | 51.18%  |
| Desktop        | 3291      | 38.16%  |
| Convertible    | 251       | 2.91%   |
| System on chip | 202       | 2.34%   |
| Mini pc        | 173       | 2.01%   |
| Server         | 169       | 1.96%   |
| All in one     | 68        | 0.79%   |
| Tablet         | 47        | 0.54%   |
| Phone          | 9         | 0.1%    |
| Stick pc       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 8207      | 94.66%  |
| Enabled  | 463       | 5.34%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 8458      | 98.05%  |
| Yes  | 168       | 1.95%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1847      | 21.19%  |
| 16.01-24.0      | 1614      | 18.52%  |
| 3.01-4.0        | 1517      | 17.41%  |
| 8.01-16.0       | 1306      | 14.99%  |
| 32.01-64.0      | 775       | 8.89%   |
| 1.01-2.0        | 739       | 8.48%   |
| 64.01-256.0     | 363       | 4.17%   |
| 2.01-3.0        | 171       | 1.96%   |
| 0.51-1.0        | 151       | 1.73%   |
| 24.01-32.0      | 139       | 1.59%   |
| 0.01-0.5        | 47        | 0.54%   |
| More than 256.0 | 27        | 0.31%   |
| Unknown         | 18        | 0.21%   |
| 0               | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 2912      | 31.42%  |
| 2.01-3.0        | 1686      | 18.19%  |
| 0.51-1.0        | 1438      | 15.51%  |
| 4.01-8.0        | 1223      | 13.19%  |
| 3.01-4.0        | 918       | 9.9%    |
| 8.01-16.0       | 430       | 4.64%   |
| 0.01-0.5        | 397       | 4.28%   |
| 16.01-24.0      | 120       | 1.29%   |
| 32.01-64.0      | 57        | 0.61%   |
| 24.01-32.0      | 41        | 0.44%   |
| Unknown         | 26        | 0.28%   |
| 64.01-256.0     | 19        | 0.2%    |
| More than 256.0 | 1         | 0.01%   |
| 0               | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5600      | 63.59%  |
| 2       | 1788      | 20.3%   |
| 3       | 592       | 6.72%   |
| 4       | 340       | 3.86%   |
| 5       | 163       | 1.85%   |
| 6       | 87        | 0.99%   |
| 0       | 65        | 0.74%   |
| 7       | 59        | 0.67%   |
| 8       | 42        | 0.48%   |
| 9       | 20        | 0.23%   |
| 10      | 15        | 0.17%   |
| 14      | 6         | 0.07%   |
| 11      | 6         | 0.07%   |
| 13      | 5         | 0.06%   |
| 12      | 5         | 0.06%   |
| Unknown | 3         | 0.03%   |
| 28      | 2         | 0.02%   |
| 16      | 2         | 0.02%   |
| 46      | 1         | 0.01%   |
| 27      | 1         | 0.01%   |
| 26      | 1         | 0.01%   |
| 21      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |
| 17      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 5810      | 67%     |
| Yes       | 2862      | 33%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7490      | 86.67%  |
| No        | 1152      | 13.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5817      | 67.18%  |
| No        | 2842      | 32.82%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4779      | 54.98%  |
| No        | 3913      | 45.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1940      | 22.39%  |
| Russia       | 1216      | 14.03%  |
| Germany      | 814       | 9.39%   |
| France       | 564       | 6.51%   |
| Brazil       | 415       | 4.79%   |
| Spain        | 348       | 4.02%   |
| Italy        | 313       | 3.61%   |
| UK           | 243       | 2.8%    |
| Poland       | 201       | 2.32%   |
| Canada       | 177       | 2.04%   |
| Switzerland  | 143       | 1.65%   |
| Netherlands  | 139       | 1.6%    |
| Australia    | 132       | 1.52%   |
| China        | 110       | 1.27%   |
| Mexico       | 94        | 1.08%   |
| Ukraine      | 90        | 1.04%   |
| India        | 84        | 0.97%   |
| Hungary      | 80        | 0.92%   |
| Sweden       | 78        | 0.9%    |
| Belgium      | 77        | 0.89%   |
| Argentina    | 75        | 0.87%   |
| Austria      | 74        | 0.85%   |
| Portugal     | 68        | 0.78%   |
| Finland      | 64        | 0.74%   |
| Czechia      | 58        | 0.67%   |
| Turkey       | 53        | 0.61%   |
| Norway       | 48        | 0.55%   |
| Romania      | 45        | 0.52%   |
| Japan        | 45        | 0.52%   |
| Chile        | 45        | 0.52%   |
| Venezuela    | 43        | 0.5%    |
| Greece       | 38        | 0.44%   |
| Bulgaria     | 38        | 0.44%   |
| Ireland      | 35        | 0.4%    |
| New Zealand  | 32        | 0.37%   |
| Denmark      | 30        | 0.35%   |
| South Africa | 29        | 0.33%   |
| Indonesia    | 29        | 0.33%   |
| Colombia     | 29        | 0.33%   |
| Belarus      | 26        | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Voronezh          | 718       | 7.87%   |
| Bangor            | 703       | 7.71%   |
| Dover-Foxcroft    | 305       | 3.35%   |
| Moscow            | 125       | 1.37%   |
| St Petersburg     | 111       | 1.22%   |
| Paris             | 94        | 1.03%   |
| Berlin            | 73        | 0.8%    |
| Sao Paulo         | 67        | 0.73%   |
| Seville           | 57        | 0.63%   |
| Madrid            | 56        | 0.61%   |
| Vienna            | 55        | 0.6%    |
| Zurich            | 51        | 0.56%   |
| Warsaw            | 49        | 0.54%   |
| Munich            | 44        | 0.48%   |
| Amsterdam         | 44        | 0.48%   |
| Milan             | 43        | 0.47%   |
| Hamburg           | 37        | 0.41%   |
| Barcelona         | 37        | 0.41%   |
| Sydney            | 34        | 0.37%   |
| Budapest          | 34        | 0.37%   |
| Perm              | 31        | 0.34%   |
| Frankfurt am Main | 31        | 0.34%   |
| Helsinki          | 30        | 0.33%   |
| Toronto           | 29        | 0.32%   |
| London            | 29        | 0.32%   |
| Rio de Janeiro    | 27        | 0.3%    |
| Prague            | 27        | 0.3%    |
| Falkenstein       | 27        | 0.3%    |
| Melbourne         | 26        | 0.29%   |
| Brisbane          | 26        | 0.29%   |
| Cologne           | 24        | 0.26%   |
| Kyiv              | 23        | 0.25%   |
| Yekaterinburg     | 22        | 0.24%   |
| San Jose          | 22        | 0.24%   |
| Rome              | 22        | 0.24%   |
| New York          | 22        | 0.24%   |
| Dublin            | 22        | 0.24%   |
| Istanbul          | 21        | 0.23%   |
| Athens            | 21        | 0.23%   |
| Lisbon            | 20        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1869      | 2772   | 15.21%  |
| WDC                 | 1790      | 2943   | 14.57%  |
| Seagate             | 1681      | 2808   | 13.68%  |
| Toshiba             | 839       | 1242   | 6.83%   |
| Kingston            | 736       | 942    | 5.99%   |
| Unknown             | 656       | 867    | 5.34%   |
| Crucial             | 558       | 719    | 4.54%   |
| SanDisk             | 494       | 633    | 4.02%   |
| Hitachi             | 372       | 519    | 3.03%   |
| Intel               | 276       | 374    | 2.25%   |
| Fujitsu             | 262       | 273    | 2.13%   |
| SK hynix            | 247       | 315    | 2.01%   |
| A-DATA Technology   | 224       | 350    | 1.82%   |
| Apple               | 210       | 260    | 1.71%   |
| HGST                | 202       | 323    | 1.64%   |
| Micron Technology   | 145       | 158    | 1.18%   |
| China               | 105       | 124    | 0.85%   |
| SPCC                | 73        | 83     | 0.59%   |
| Transcend           | 71        | 81     | 0.58%   |
| Phison              | 69        | 98     | 0.56%   |
| KIOXIA              | 66        | 80     | 0.54%   |
| Unknown             | 63        | 66     | 0.51%   |
| OCZ                 | 59        | 72     | 0.48%   |
| PNY                 | 57        | 85     | 0.46%   |
| Intenso             | 51        | 67     | 0.42%   |
| Corsair             | 49        | 69     | 0.4%    |
| Hewlett-Packard     | 46        | 75     | 0.37%   |
| LITEON              | 45        | 52     | 0.37%   |
| Patriot             | 44        | 53     | 0.36%   |
| Maxtor              | 43        | 56     | 0.35%   |
| JMicron Technology  | 40        | 41     | 0.33%   |
| Silicon Motion      | 37        | 44     | 0.3%    |
| Netac               | 35        | 98     | 0.28%   |
| GOODRAM             | 32        | 47     | 0.26%   |
| SABRENT             | 31        | 33     | 0.25%   |
| Gigabyte Technology | 30        | 36     | 0.24%   |
| Team                | 23        | 37     | 0.19%   |
| ASMT                | 23        | 33     | 0.19%   |
| XPG                 | 21        | 31     | 0.17%   |
| LITEONIT            | 21        | 26     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB     | 203       | 1.49%   |
| Kingston SA400S37240G 240GB SSD    | 161       | 1.18%   |
| Samsung MZVLB512HBJQ-000L7 512GB   | 132       | 0.97%   |
| Seagate ST500DM002-1BD142 500GB    | 106       | 0.78%   |
| Kingston SA400S37120G 120GB SSD    | 100       | 0.74%   |
| Crucial CT480BX500SSD1 480GB       | 84        | 0.62%   |
| Samsung SSD 860 EVO 500GB          | 83        | 0.61%   |
| Seagate ST1000DM010-2EP102 1TB     | 78        | 0.57%   |
| Kingston SV300S37A120G 120GB SSD   | 78        | 0.57%   |
| Kingston SA400S37480G 480GB SSD    | 78        | 0.57%   |
| Apple SSD AP0128H 121GB            | 77        | 0.57%   |
| Samsung SSD 860 EVO 1TB            | 75        | 0.55%   |
| Apple SSD SM0128G 121GB            | 74        | 0.54%   |
| Samsung SSD 860 EVO 250GB          | 73        | 0.54%   |
| Samsung SSD 850 EVO 250GB          | 73        | 0.54%   |
| Seagate ST1000LM035-1RK172 1TB     | 72        | 0.53%   |
| Toshiba DT01ACA050 500GB           | 69        | 0.51%   |
| Crucial CT500MX500SSD1 500GB       | 69        | 0.51%   |
| Samsung SSD 970 EVO Plus 1TB       | 65        | 0.48%   |
| Unknown MMC Card  32GB             | 63        | 0.46%   |
| Unknown                            | 63        | 0.46%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 62        | 0.46%   |
| Crucial CT240BX500SSD1 240GB       | 57        | 0.42%   |
| Crucial CT1000MX500SSD1 1TB        | 57        | 0.42%   |
| Samsung SSD 970 EVO Plus 500GB     | 53        | 0.39%   |
| Samsung SSD 850 EVO 500GB          | 52        | 0.38%   |
| Toshiba DT01ACA100 1TB             | 51        | 0.38%   |
| A-DATA SU800 512GB SSD             | 51        | 0.38%   |
| Toshiba MK1655GSXF 160GB           | 47        | 0.35%   |
| HGST HTS721010A9E630 1TB           | 47        | 0.35%   |
| WDC WD10EZEX-08WN4A0 1TB           | 46        | 0.34%   |
| Toshiba MQ01ABD100 1TB             | 46        | 0.34%   |
| Toshiba HDWD110 1TB                | 45        | 0.33%   |
| Toshiba MK1653GSX 160GB            | 43        | 0.32%   |
| Unknown MMC Card  64GB             | 41        | 0.3%    |
| Seagate ST2000DM008-2FR102 2TB     | 41        | 0.3%    |
| WDC WD5000AAKX-60U6AA0 500GB       | 40        | 0.29%   |
| Unknown AGND3R  16GB               | 40        | 0.29%   |
| Seagate ST1000DM003-1ER162 1TB     | 40        | 0.29%   |
| Seagate ST1000DM003-1CH162 1TB     | 40        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1636      | 2726   | 33.1%   |
| WDC                 | 1380      | 2342   | 27.92%  |
| Toshiba             | 670       | 1027   | 13.56%  |
| Hitachi             | 371       | 517    | 7.51%   |
| Fujitsu             | 262       | 273    | 5.3%    |
| HGST                | 202       | 323    | 4.09%   |
| Samsung Electronics | 178       | 235    | 3.6%    |
| Maxtor              | 42        | 49     | 0.85%   |
| Unknown             | 37        | 51     | 0.75%   |
| SABRENT             | 31        | 33     | 0.63%   |
| JMicron Technology  | 23        | 24     | 0.47%   |
| Apple               | 20        | 24     | 0.4%    |
| Hewlett-Packard     | 9         | 23     | 0.18%   |
| Intenso             | 8         | 10     | 0.16%   |
| ASMT                | 8         | 16     | 0.16%   |
| ASMedia             | 7         | 7      | 0.14%   |
| IBM/Hitachi         | 6         | 7      | 0.12%   |
| HPE                 | 5         | 10     | 0.1%    |
| USB3.0              | 4         | 4      | 0.08%   |
| IBM-ESXS            | 3         | 6      | 0.06%   |
| SILICONMOTION       | 2         | 2      | 0.04%   |
| QNAP                | 2         | 3      | 0.04%   |
| Pear 2TB            | 2         | 2      | 0.04%   |
| NETAPP              | 2         | 6      | 0.04%   |
| IET                 | 2         | 2      | 0.04%   |
| USB 3.0             | 1         | 2      | 0.02%   |
| Unknown (CF)        | 1         | 1      | 0.02%   |
| TrueNAS             | 1         | 1      | 0.02%   |
| Synology            | 1         | 1      | 0.02%   |
| StoreJet            | 1         | 1      | 0.02%   |
| SAGE                | 1         | 1      | 0.02%   |
| RSH-319             | 1         | 1      | 0.02%   |
| Quantum             | 1         | 1      | 0.02%   |
| pqi                 | 1         | 1      | 0.02%   |
| PHD 3.0             | 1         | 1      | 0.02%   |
| NAS                 | 1         | 10     | 0.02%   |
| Maxone              | 1         | 1      | 0.02%   |
| MaxDigital          | 1         | 4      | 0.02%   |
| MARSHAL             | 1         | 1      | 0.02%   |
| Magnetic Data       | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 891       | 1231   | 21.63%  |
| Kingston            | 623       | 802    | 15.13%  |
| Crucial             | 503       | 646    | 12.21%  |
| SanDisk             | 359       | 464    | 8.72%   |
| WDC                 | 193       | 240    | 4.69%   |
| A-DATA Technology   | 167       | 269    | 4.05%   |
| Intel               | 115       | 152    | 2.79%   |
| Apple               | 104       | 112    | 2.52%   |
| China               | 103       | 122    | 2.5%    |
| Micron Technology   | 70        | 77     | 1.7%    |
| Toshiba             | 65        | 83     | 1.58%   |
| Transcend           | 64        | 74     | 1.55%   |
| SPCC                | 59        | 65     | 1.43%   |
| OCZ                 | 59        | 72     | 1.43%   |
| SK hynix            | 55        | 68     | 1.34%   |
| PNY                 | 44        | 67     | 1.07%   |
| Intenso             | 39        | 50     | 0.95%   |
| Patriot             | 36        | 42     | 0.87%   |
| Netac               | 35        | 98     | 0.85%   |
| LITEON              | 34        | 40     | 0.83%   |
| GOODRAM             | 27        | 36     | 0.66%   |
| LITEONIT            | 21        | 26     | 0.51%   |
| Corsair             | 21        | 26     | 0.51%   |
| Team                | 20        | 33     | 0.49%   |
| KingDian            | 19        | 20     | 0.46%   |
| Plextor             | 18        | 24     | 0.44%   |
| Seagate             | 17        | 20     | 0.41%   |
| Hewlett-Packard     | 17        | 22     | 0.41%   |
| Gigabyte Technology | 15        | 17     | 0.36%   |
| Apacer              | 15        | 15     | 0.36%   |
| Unknown             | 14        | 15     | 0.34%   |
| Unknown             | 13        | 16     | 0.32%   |
| ASMT                | 13        | 14     | 0.32%   |
| LDLC                | 12        | 12     | 0.29%   |
| KingSpec            | 10        | 11     | 0.24%   |
| Mushkin             | 9         | 10     | 0.22%   |
| Lexar               | 8         | 11     | 0.19%   |
| Hajaan              | 8         | 11     | 0.19%   |
| FORESEE             | 7         | 8      | 0.17%   |
| Dogfish             | 7         | 11     | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 4158      | 7778   | 37.64%  |
| SSD     | 3631      | 5392   | 32.87%  |
| NVMe    | 2459      | 3505   | 22.26%  |
| MMC     | 661       | 848    | 5.98%   |
| Unknown | 137       | 204    | 1.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6331      | 12566  | 63.96%  |
| NVMe | 2454      | 3491   | 24.79%  |
| MMC  | 661       | 848    | 6.68%   |
| SAS  | 453       | 822    | 4.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB  | Computers | Drives  | Percent |
|-------------|-----------|---------|---------|
| 0.01-0.5    | 4940      | 7316    | 59.95%  |
| 0.51-1.0    | 2017      | 3116    | 24.48%  |
| 1.01-2.0    | 585       | 1040    | 7.1%    |
| 3.01-4.0    | 263       | 610     | 3.19%   |
| 4.01-10.0   | 226       | 587     | 2.74%   |
| 2.01-3.0    | 156       | 288     | 1.89%   |
| 10.01-20.0  | 50        | 208     | 0.61%   |
| 20.01-50.0  | 1         | 1       | 0.01%   |
| 50.01-100.0 | 1         | 4       | 0.01%   |
| 0           | 1         | Unknown | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2003      | 22.43%  |
| 251-500        | 1624      | 18.19%  |
| Unknown        | 1545      | 17.3%   |
| 501-1000       | 1095      | 12.26%  |
| 1001-2000      | 582       | 6.52%   |
| 51-100         | 582       | 6.52%   |
| More than 3000 | 482       | 5.4%    |
| 1-20           | 425       | 4.76%   |
| 21-50          | 358       | 4.01%   |
| 2001-3000      | 234       | 2.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3049      | 33.26%  |
| Unknown        | 1545      | 16.85%  |
| 101-250        | 1027      | 11.2%   |
| 21-50          | 974       | 10.62%  |
| 51-100         | 808       | 8.81%   |
| 251-500        | 646       | 7.05%   |
| 501-1000       | 486       | 5.3%    |
| 1001-2000      | 289       | 3.15%   |
| More than 3000 | 205       | 2.24%   |
| 2001-3000      | 116       | 1.27%   |
| 0              | 23        | 0.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 26        | 30     | 2.03%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 21        | 24     | 1.64%   |
| Kingston SV300S37A120G 120GB SSD    | 21        | 21     | 1.64%   |
| Fujitsu MHZ2160BH FFS G1 160GB      | 20        | 20     | 1.56%   |
| Seagate ST9500325AS 500GB           | 13        | 15     | 1.01%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 13        | 16     | 1.01%   |
| Hitachi HDS721050CLA362 500GB       | 10        | 10     | 0.78%   |
| Toshiba MK1653GSX 160GB             | 9         | 9      | 0.7%    |
| Seagate ST9500420AS 500GB           | 9         | 9      | 0.7%    |
| Seagate ST31500341AS 1TB            | 9         | 15     | 0.7%    |
| Seagate ST1000DM003-9YN162 1TB      | 9         | 10     | 0.7%    |
| WDC WD5000AAKX-08U6AA0 500GB        | 8         | 8      | 0.62%   |
| Toshiba MK1655GSXF 160GB            | 8         | 8      | 0.62%   |
| Seagate ST3500418AS 500GB           | 8         | 12     | 0.62%   |
| Seagate ST1000LM035-1RK172 1TB      | 8         | 8      | 0.62%   |
| Toshiba MQ01ABD100 1TB              | 7         | 7      | 0.55%   |
| Toshiba DT01ACA100 1TB              | 7         | 8      | 0.55%   |
| Seagate ST500LT012-9WS142 500GB     | 7         | 8      | 0.55%   |
| Seagate ST3250318AS 250GB           | 7         | 8      | 0.55%   |
| Seagate ST31000528AS 1TB            | 7         | 7      | 0.55%   |
| Seagate ST250DM000-1BD141 250GB     | 7         | 7      | 0.55%   |
| Seagate ST1000DM003-1CH162 1TB      | 7         | 7      | 0.55%   |
| HGST HTS725050A7E630 500GB          | 7         | 9      | 0.55%   |
| WDC WD5000AAKX-001CA0 500GB         | 6         | 8      | 0.47%   |
| Toshiba DT01ACA050 500GB            | 6         | 7      | 0.47%   |
| Seagate ST500LM021-1KJ152 500GB     | 6         | 6      | 0.47%   |
| Seagate ST3160815AS 160GB           | 6         | 8      | 0.47%   |
| Hitachi HTS545050B9A300 500GB       | 6         | 6      | 0.47%   |
| Hitachi HTS543216L9SA02 160GB       | 6         | 6      | 0.47%   |
| Hitachi HDS721050DLE630 500GB       | 6         | 11     | 0.47%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 5         | 5      | 0.39%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 5         | 6      | 0.39%   |
| WDC WD20EFRX-68EUZN0 2TB            | 5         | 16     | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB            | 5         | 5      | 0.39%   |
| WDC WD10EARS-00Y5B1 1TB             | 5         | 5      | 0.39%   |
| WDC WD10EADS-00M2B0 1TB             | 5         | 5      | 0.39%   |
| Seagate ST3500413AS 500GB           | 5         | 6      | 0.39%   |
| Seagate ST3320613AS 320GB           | 5         | 5      | 0.39%   |
| Seagate ST31000524AS 1TB            | 5         | 5      | 0.39%   |
| Samsung Electronics SSD 850 EVO 1TB | 5         | 6      | 0.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 336       | 440    | 27.05%  |
| WDC                 | 270       | 355    | 21.74%  |
| Hitachi             | 120       | 150    | 9.66%   |
| Samsung Electronics | 95        | 105    | 7.65%   |
| Toshiba             | 83        | 93     | 6.68%   |
| Kingston            | 52        | 58     | 4.19%   |
| Intel               | 38        | 48     | 3.06%   |
| Fujitsu             | 35        | 36     | 2.82%   |
| HGST                | 31        | 34     | 2.5%    |
| Crucial             | 24        | 29     | 1.93%   |
| A-DATA Technology   | 23        | 31     | 1.85%   |
| SK hynix            | 21        | 26     | 1.69%   |
| SanDisk             | 18        | 23     | 1.45%   |
| Micron Technology   | 16        | 16     | 1.29%   |
| Maxtor              | 14        | 15     | 1.13%   |
| OCZ                 | 8         | 9      | 0.64%   |
| LITEONIT            | 5         | 6      | 0.4%    |
| KingDian            | 5         | 5      | 0.4%    |
| China               | 5         | 5      | 0.4%    |
| LITEON              | 4         | 4      | 0.32%   |
| Corsair             | 4         | 4      | 0.32%   |
| Unknown             | 2         | 2      | 0.16%   |
| PNY                 | 2         | 4      | 0.16%   |
| Plextor             | 2         | 3      | 0.16%   |
| JMicron Technology  | 2         | 2      | 0.16%   |
| IBM/Hitachi         | 2         | 2      | 0.16%   |
| Hewlett-Packard     | 2         | 3      | 0.16%   |
| Apple               | 2         | 2      | 0.16%   |
| Apacer              | 2         | 2      | 0.16%   |
| Unknown             | 2         | 2      | 0.16%   |
| Zheino              | 1         | 1      | 0.08%   |
| USB3.0              | 1         | 1      | 0.08%   |
| Teclast             | 1         | 1      | 0.08%   |
| Team                | 1         | 1      | 0.08%   |
| SSSTC               | 1         | 1      | 0.08%   |
| SPCC                | 1         | 1      | 0.08%   |
| ShiJi               | 1         | 1      | 0.08%   |
| Netac               | 1         | 1      | 0.08%   |
| Lenovo              | 1         | 1      | 0.08%   |
| KingSpec            | 1         | 1      | 0.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 336       | 440    | 35.56%  |
| WDC                 | 261       | 345    | 27.62%  |
| Hitachi             | 120       | 150    | 12.7%   |
| Toshiba             | 80        | 90     | 8.47%   |
| Samsung Electronics | 56        | 61     | 5.93%   |
| Fujitsu             | 35        | 36     | 3.7%    |
| HGST                | 31        | 34     | 3.28%   |
| Maxtor              | 14        | 15     | 1.48%   |
| JMicron Technology  | 2         | 2      | 0.21%   |
| IBM/Hitachi         | 2         | 2      | 0.21%   |
| Hewlett-Packard     | 2         | 3      | 0.21%   |
| USB3.0              | 1         | 1      | 0.11%   |
| Unknown             | 1         | 1      | 0.11%   |
| IBM                 | 1         | 1      | 0.11%   |
| ASMT                | 1         | 2      | 0.11%   |
| ASMedia             | 1         | 1      | 0.11%   |
| Apple               | 1         | 1      | 0.11%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 888       | 1185   | 75%     |
| SSD  | 259       | 304    | 21.88%  |
| NVMe | 37        | 43     | 3.13%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 2         | 3      | 7.14%   |
| Samsung Electronics MZ7LN512HAJQ-00000 512GB SSD | 2         | 5      | 7.14%   |
| WDC WD5000BEVT-35A0RT0 500GB                     | 1         | 1      | 3.57%   |
| WDC WD4001FFSX-68JNUN0 4TB                       | 1         | 1      | 3.57%   |
| WDC WD30EZRS-00J99B0 3TB                         | 1         | 1      | 3.57%   |
| Toshiba MK6465GSX 640GB                          | 1         | 1      | 3.57%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 3.57%   |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 1      | 3.57%   |
| Seagate ST500DM005 HD502HJ 500GB                 | 1         | 1      | 3.57%   |
| Seagate ST3500830AS 500GB                        | 1         | 1      | 3.57%   |
| Seagate ST3500630A 500GB                         | 1         | 1      | 3.57%   |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 3.57%   |
| Samsung Electronics SP0802N 80GB                 | 1         | 1      | 3.57%   |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB     | 1         | 1      | 3.57%   |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD  | 1         | 1      | 3.57%   |
| Samsung Electronics HE103SJ 1TB                  | 1         | 2      | 3.57%   |
| Samsung Electronics HD253GJ 250GB                | 1         | 1      | 3.57%   |
| Samsung Electronics HD103SJ 1TB                  | 1         | 1      | 3.57%   |
| KingDian S400 120GB SSD                          | 1         | 1      | 3.57%   |
| IBM-ESXS ST9300605SS 304GB                       | 1         | 2      | 3.57%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 2      | 3.57%   |
| HGST HUH728080ALN600 8TB                         | 1         | 1      | 3.57%   |
| HGST HTS725050A7E630 500GB                       | 1         | 2      | 3.57%   |
| HGST HDN724040ALE640 4TB                         | 1         | 1      | 3.57%   |
| Hewlett-Packard SSD S700 500GB                   | 1         | 2      | 3.57%   |
| Crucial CT1000P1SSD8 1TB                         | 1         | 1      | 3.57%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 13     | 32.14%  |
| Seagate             | 7         | 8      | 25%     |
| WDC                 | 3         | 3      | 10.71%  |
| HGST                | 3         | 4      | 10.71%  |
| Toshiba             | 1         | 1      | 3.57%   |
| KingDian            | 1         | 1      | 3.57%   |
| IBM-ESXS            | 1         | 2      | 3.57%   |
| Hitachi             | 1         | 2      | 3.57%   |
| Hewlett-Packard     | 1         | 2      | 3.57%   |
| Crucial             | 1         | 1      | 3.57%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 5904      | 11148  | 61.35%  |
| Detected | 2543      | 5008   | 26.42%  |
| Malfunc  | 1147      | 1532   | 11.92%  |
| Failed   | 28        | 37     | 0.29%   |
| Limited  | 2         | 2      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5278      | 50.86%  |
| AMD                              | 1435      | 13.83%  |
| Samsung Electronics              | 1011      | 9.74%   |
| Nvidia                           | 420       | 4.05%   |
| SanDisk                          | 375       | 3.61%   |
| ASMedia Technology               | 184       | 1.77%   |
| SK hynix                         | 179       | 1.72%   |
| Phison Electronics               | 154       | 1.48%   |
| Marvell Technology Group         | 138       | 1.33%   |
| Kingston Technology Company      | 125       | 1.2%    |
| Toshiba America Info Systems     | 115       | 1.11%   |
| JMicron Technology               | 97        | 0.93%   |
| LSI Logic / Symbios Logic        | 88        | 0.85%   |
| Apple                            | 87        | 0.84%   |
| Micron/Crucial Technology        | 81        | 0.78%   |
| Silicon Motion                   | 80        | 0.77%   |
| ADATA Technology                 | 77        | 0.74%   |
| Micron Technology                | 76        | 0.73%   |
| KIOXIA                           | 72        | 0.69%   |
| Broadcom / LSI                   | 52        | 0.5%    |
| VIA Technologies                 | 41        | 0.4%    |
| Silicon Image                    | 22        | 0.21%   |
| Solid State Storage Technology   | 19        | 0.18%   |
| Hewlett-Packard                  | 19        | 0.18%   |
| Adaptec                          | 19        | 0.18%   |
| Lite-On Technology               | 16        | 0.15%   |
| Silicon Integrated Systems [SiS] | 15        | 0.14%   |
| Seagate Technology               | 15        | 0.14%   |
| Realtek Semiconductor            | 15        | 0.14%   |
| Union Memory (Shenzhen)          | 13        | 0.13%   |
| MAXIO Technology (Hangzhou)      | 8         | 0.08%   |
| Shenzhen Longsys Electronics     | 6         | 0.06%   |
| Lenovo                           | 5         | 0.05%   |
| IBM                              | 5         | 0.05%   |
| ULi Electronics                  | 4         | 0.04%   |
| Jiangsu Huacun Elec.             | 4         | 0.04%   |
| Integrated Technology Express    | 4         | 0.04%   |
| Biwin Storage Technology         | 4         | 0.04%   |
| 3ware                            | 4         | 0.04%   |
| OCZ Technology Group             | 2         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 967       | 8.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 560       | 4.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 400       | 3.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 375       | 3.11%   |
| Nvidia MCP79 AHCI Controller                                                            | 322       | 2.67%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 314       | 2.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 213       | 1.77%   |
| AMD 400 Series Chipset SATA Controller                                                  | 210       | 1.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 209       | 1.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 199       | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 195       | 1.62%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 189       | 1.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 187       | 1.55%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 180       | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 171       | 1.42%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 165       | 1.37%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 159       | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 152       | 1.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 149       | 1.24%   |
| Samsung NVMe SSD Controller 980                                                         | 144       | 1.2%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 142       | 1.18%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 133       | 1.1%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 126       | 1.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 119       | 0.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 110       | 0.91%   |
| AMD 500 Series Chipset SATA Controller                                                  | 109       | 0.91%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 104       | 0.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 102       | 0.85%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 101       | 0.84%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 99        | 0.82%   |
| Samsung Electronics SATA controller                                                     | 91        | 0.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 91        | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 89        | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 87        | 0.72%   |
| Intel SATA Controller [RAID mode]                                                       | 87        | 0.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 86        | 0.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 84        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 84        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 83        | 0.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 82        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 6062      | 57.33%  |
| NVMe | 2468      | 23.34%  |
| IDE  | 1283      | 12.13%  |
| RAID | 627       | 5.93%   |
| SAS  | 95        | 0.9%    |
| SCSI | 38        | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 6637      | 76.94%  |
| AMD                   | 1721      | 19.95%  |
| ARM                   | 224       | 2.6%    |
| CentaurHauls          | 11        | 0.13%   |
| Unknown               | 9         | 0.1%    |
| CHRP IBM,8233-E8B     | 5         | 0.06%   |
| sifive,u74-mc         | 4         | 0.05%   |
| sifive,bullet0        | 3         | 0.03%   |
| Phytium               | 3         | 0.03%   |
| Qualcomm              | 2         | 0.02%   |
| CHRP IBM,9131-52A     | 2         | 0.02%   |
| PowerNV FP5466G2      | 1         | 0.01%   |
| PowerNV C829UAG3      | 1         | 0.01%   |
| Marvell Semiconductor | 1         | 0.01%   |
| HISILICON             | 1         | 0.01%   |
| AppliedMicro          | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 309       | 3.58%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 190       | 2.2%    |
| ARM Processor                                 | 164       | 1.9%    |
| Intel Core i5-5250U CPU @ 1.60GHz             | 148       | 1.71%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 93        | 1.08%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 89        | 1.03%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 82        | 0.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 79        | 0.91%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 75        | 0.87%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 67        | 0.78%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 66        | 0.76%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 64        | 0.74%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 64        | 0.74%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 62        | 0.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 59        | 0.68%   |
| AMD Ryzen 5 3600 6-Core Processor             | 57        | 0.66%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 56        | 0.65%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 52        | 0.6%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 51        | 0.59%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 49        | 0.57%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 48        | 0.56%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 47        | 0.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 42        | 0.49%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 38        | 0.44%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 37        | 0.43%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 37        | 0.43%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 37        | 0.43%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 35        | 0.41%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 35        | 0.41%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 33        | 0.38%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 33        | 0.38%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 33        | 0.38%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 31        | 0.36%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 31        | 0.36%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 30        | 0.35%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 30        | 0.35%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 30        | 0.35%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 30        | 0.35%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 30        | 0.35%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 29        | 0.34%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1723      | 19.96%  |
| Intel Core i7           | 1247      | 14.45%  |
| Other                   | 783       | 9.07%   |
| Intel Core 2 Duo        | 632       | 7.32%   |
| Intel Core i3           | 624       | 7.23%   |
| Intel Celeron           | 556       | 6.44%   |
| AMD Ryzen 5             | 412       | 4.77%   |
| Intel Xeon              | 338       | 3.92%   |
| AMD Ryzen 7             | 299       | 3.46%   |
| Intel Pentium           | 275       | 3.19%   |
| Intel Atom              | 195       | 2.26%   |
| AMD Ryzen 9             | 116       | 1.34%   |
| AMD FX                  | 110       | 1.27%   |
| Intel Core 2            | 101       | 1.17%   |
| Intel Pentium Dual-Core | 90        | 1.04%   |
| AMD Ryzen 3             | 76        | 0.88%   |
| Intel Core 2 Quad       | 61        | 0.71%   |
| AMD Ryzen 7 PRO         | 49        | 0.57%   |
| AMD A8                  | 42        | 0.49%   |
| Intel Core i9           | 39        | 0.45%   |
| AMD A6                  | 38        | 0.44%   |
| AMD A10                 | 38        | 0.44%   |
| AMD Ryzen Threadripper  | 36        | 0.42%   |
| Intel Pentium Dual      | 34        | 0.39%   |
| Intel Pentium 4         | 34        | 0.39%   |
| AMD A4                  | 34        | 0.39%   |
| AMD Athlon              | 33        | 0.38%   |
| Intel Pentium M         | 32        | 0.37%   |
| AMD Athlon II X2        | 32        | 0.37%   |
| AMD Athlon 64 X2        | 32        | 0.37%   |
| AMD Ryzen 5 PRO         | 30        | 0.35%   |
| AMD Phenom II X4        | 30        | 0.35%   |
| Intel Pentium Gold      | 28        | 0.32%   |
| Intel Genuine           | 27        | 0.31%   |
| ARM Allwinner           | 21        | 0.24%   |
| AMD E1                  | 21        | 0.24%   |
| AMD E                   | 21        | 0.24%   |
| Intel Pentium Silver    | 20        | 0.23%   |
| AMD Phenom II X6        | 16        | 0.19%   |
| AMD GX                  | 15        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3645      | 42.19%  |
| 4       | 2947      | 34.11%  |
| 6       | 740       | 8.56%   |
| 8       | 567       | 6.56%   |
| 1       | 318       | 3.68%   |
| 12      | 127       | 1.47%   |
| 16      | 103       | 1.19%   |
| 10      | 47        | 0.54%   |
| 3       | 39        | 0.45%   |
| 14      | 23        | 0.27%   |
| Unknown | 21        | 0.24%   |
| 32      | 19        | 0.22%   |
| 24      | 14        | 0.16%   |
| 20      | 11        | 0.13%   |
| 18      | 4         | 0.05%   |
| 44      | 3         | 0.03%   |
| 28      | 3         | 0.03%   |
| 64      | 2         | 0.02%   |
| 48      | 2         | 0.02%   |
| 22      | 2         | 0.02%   |
| 80      | 1         | 0.01%   |
| 56      | 1         | 0.01%   |
| 36      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 8448      | 97.88%  |
| 2       | 155       | 1.8%    |
| Unknown | 21        | 0.24%   |
| 4       | 4         | 0.05%   |
| 3       | 2         | 0.02%   |
| 8       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5175      | 59.92%  |
| 1       | 3433      | 39.75%  |
| Unknown | 21        | 0.24%   |
| 4       | 7         | 0.08%   |
| 8       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 8236      | 95.36%  |
| Unknown        | 230       | 2.66%   |
| 32-bit         | 151       | 1.75%   |
| 64-bit         | 20        | 0.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2030      | 22.97%  |
| 0x1067a    | 573       | 6.48%   |
| 0x306a9    | 387       | 4.38%   |
| 0x206a7    | 380       | 4.3%    |
| 0x306c3    | 363       | 4.11%   |
| 0x806c1    | 300       | 3.39%   |
| 0x306d4    | 257       | 2.91%   |
| 0x906ea    | 204       | 2.31%   |
| 0x806ec    | 204       | 2.31%   |
| 0x506e3    | 167       | 1.89%   |
| 0x806e9    | 162       | 1.83%   |
| 0x806ea    | 148       | 1.67%   |
| 0x30678    | 139       | 1.57%   |
| 0x40651    | 129       | 1.46%   |
| 0x406e3    | 114       | 1.29%   |
| 0x906e9    | 113       | 1.28%   |
| 0x08701021 | 110       | 1.24%   |
| 0x08108109 | 103       | 1.17%   |
| 0x406c4    | 89        | 1.01%   |
| 0xa0653    | 82        | 0.93%   |
| 0x6f6      | 79        | 0.89%   |
| 0x20655    | 79        | 0.89%   |
| 0x08600106 | 75        | 0.85%   |
| 0x0a50000c | 74        | 0.84%   |
| 0x906eb    | 67        | 0.76%   |
| 0x10676    | 66        | 0.75%   |
| 0xa0652    | 65        | 0.74%   |
| 0x6fd      | 64        | 0.72%   |
| 0x706a8    | 61        | 0.69%   |
| 0x0800820d | 58        | 0.66%   |
| 0x506c9    | 56        | 0.63%   |
| 0xa0655    | 53        | 0.6%    |
| 0x08108102 | 52        | 0.59%   |
| 0x706e5    | 48        | 0.54%   |
| 0x0a201016 | 48        | 0.54%   |
| 0x906ed    | 45        | 0.51%   |
| 0x206d7    | 45        | 0.51%   |
| 0x106c2    | 45        | 0.51%   |
| 0x08608103 | 44        | 0.5%    |
| 0x906c0    | 42        | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1267      | 14.67%  |
| Penryn           | 723       | 8.37%   |
| Haswell          | 685       | 7.93%   |
| SandyBridge      | 550       | 6.37%   |
| IvyBridge        | 542       | 6.27%   |
| Unknown          | 423       | 4.9%    |
| Skylake          | 411       | 4.76%   |
| TigerLake        | 344       | 3.98%   |
| Zen 2            | 336       | 3.89%   |
| Silvermont       | 325       | 3.76%   |
| Broadwell        | 317       | 3.67%   |
| Zen+             | 285       | 3.3%    |
| Core             | 260       | 3.01%   |
| CometLake        | 244       | 2.82%   |
| Zen 3            | 215       | 2.49%   |
| Westmere         | 199       | 2.3%    |
| Zen              | 158       | 1.83%   |
| K10              | 140       | 1.62%   |
| Piledriver       | 117       | 1.35%   |
| Bonnell          | 112       | 1.3%    |
| Goldmont plus    | 111       | 1.29%   |
| Excavator        | 105       | 1.22%   |
| Icelake          | 87        | 1.01%   |
| Goldmont         | 81        | 0.94%   |
| Nehalem          | 73        | 0.85%   |
| K8 Hammer        | 71        | 0.82%   |
| P6               | 67        | 0.78%   |
| Alderlake Hybrid | 64        | 0.74%   |
| NetBurst         | 58        | 0.67%   |
| Bobcat           | 52        | 0.6%    |
| Tremont          | 44        | 0.51%   |
| Steamroller      | 38        | 0.44%   |
| Jaguar           | 35        | 0.41%   |
| Puma             | 33        | 0.38%   |
| Bulldozer        | 31        | 0.36%   |
| K10 Llano        | 21        | 0.24%   |
| K8 & K10 hybrid  | 7         | 0.08%   |
| K6               | 6         | 0.07%   |
| Geode            | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 5007      | 52.55%  |
| Nvidia                                       | 2434      | 25.55%  |
| AMD                                          | 1825      | 19.15%  |
| Matrox Electronics Systems                   | 128       | 1.34%   |
| ASPEED Technology                            | 101       | 1.06%   |
| VIA Technologies                             | 11        | 0.12%   |
| Silicon Integrated Systems [SiS]             | 9         | 0.09%   |
| Zhaoxin                                      | 4         | 0.04%   |
| S3 Graphics                                  | 2         | 0.02%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| Silicon Motion                               | 1         | 0.01%   |
| Neomagic                                     | 1         | 0.01%   |
| Loongson Technology                          | 1         | 0.01%   |
| Huawei Technologies                          | 1         | 0.01%   |
| Cirrus Logic                                 | 1         | 0.01%   |
| ATI Technologies                             | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 366       | 3.71%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 322       | 3.27%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 307       | 3.11%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 283       | 2.87%   |
| Intel UHD Graphics 620                                                                   | 203       | 2.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 194       | 1.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 186       | 1.89%   |
| Intel HD Graphics 620                                                                    | 183       | 1.86%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 174       | 1.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 174       | 1.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 166       | 1.68%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 157       | 1.59%   |
| Intel HD Graphics 6000                                                                   | 156       | 1.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 149       | 1.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 146       | 1.48%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 141       | 1.43%   |
| AMD Renoir                                                                               | 139       | 1.41%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 129       | 1.31%   |
| Intel HD Graphics 5500                                                                   | 122       | 1.24%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 117       | 1.19%   |
| Intel HD Graphics 530                                                                    | 106       | 1.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 104       | 1.05%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 101       | 1.02%   |
| Intel HD Graphics 630                                                                    | 100       | 1.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 99        | 1%      |
| Intel GeminiLake [UHD Graphics 600]                                                      | 98        | 0.99%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 96        | 0.97%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 95        | 0.96%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 93        | 0.94%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 88        | 0.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 86        | 0.87%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 83        | 0.84%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 80        | 0.81%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 75        | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 73        | 0.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 73        | 0.74%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 70        | 0.71%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 69        | 0.7%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 69        | 0.7%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 64        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 3992      | 46.04%  |
| 1 x Nvidia                        | 1551      | 17.89%  |
| 1 x AMD                           | 1475      | 17.01%  |
| Intel + Nvidia                    | 762       | 8.79%   |
| Other                             | 268       | 3.09%   |
| Intel + AMD                       | 164       | 1.89%   |
| 1 x Matrox                        | 121       | 1.4%    |
| 2 x AMD                           | 91        | 1.05%   |
| AMD + Nvidia                      | 83        | 0.96%   |
| 1 x ASPEED                        | 79        | 0.91%   |
| 2 x Nvidia                        | 14        | 0.16%   |
| Nvidia + ASPEED                   | 13        | 0.15%   |
| 1 x VIA                           | 11        | 0.13%   |
| 1 x SiS                           | 9         | 0.1%    |
| AMD + ASPEED                      | 7         | 0.08%   |
| Nvidia + Matrox                   | 5         | 0.06%   |
| Intel + 2 x Nvidia                | 5         | 0.06%   |
| 2 x Intel                         | 4         | 0.05%   |
| 1 x Zhaoxin                       | 4         | 0.05%   |
| 1 x S3 Graphics                   | 2         | 0.02%   |
| AMD + Matrox                      | 2         | 0.02%   |
| 3 x AMD                           | 1         | 0.01%   |
| 2 x Nvidia + 1 x ASPEED           | 1         | 0.01%   |
| 2 x Loongson Technology           | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1         | 0.01%   |
| 1 x Silicon Motion                | 1         | 0.01%   |
| Nvidia + XGI                      | 1         | 0.01%   |
| Nvidia + Huawei Technologies      | 1         | 0.01%   |
| 1 x Neomagic                      | 1         | 0.01%   |
| 1 x Cirrus Logic                  | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 6337      | 72.86%  |
| Unknown     | 1442      | 16.58%  |
| Proprietary | 918       | 10.56%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 6099      | 69.61%  |
| 0.01-0.5       | 924       | 10.55%  |
| 1.01-2.0       | 575       | 6.56%   |
| 0.51-1.0       | 390       | 4.45%   |
| 3.01-4.0       | 338       | 3.86%   |
| 7.01-8.0       | 210       | 2.4%    |
| 5.01-6.0       | 119       | 1.36%   |
| 8.01-16.0      | 47        | 0.54%   |
| 2.01-3.0       | 44        | 0.5%    |
| 16.01-24.0     | 12        | 0.14%   |
| 4.01-5.0       | 2         | 0.02%   |
| More than 64.0 | 1         | 0.01%   |
| 24.01-32.0     | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 998       | 12.33%  |
| Samsung Electronics     | 868       | 10.73%  |
| BOE                     | 664       | 8.21%   |
| Apple                   | 630       | 7.79%   |
| LG Display              | 606       | 7.49%   |
| Chimei Innolux          | 557       | 6.88%   |
| Dell                    | 490       | 6.06%   |
| Goldstar                | 387       | 4.78%   |
| Hewlett-Packard         | 250       | 3.09%   |
| BenQ                    | 221       | 2.73%   |
| Acer                    | 213       | 2.63%   |
| Philips                 | 190       | 2.35%   |
| AOC                     | 187       | 2.31%   |
| Lenovo                  | 166       | 2.05%   |
| Ancor Communications    | 155       | 1.92%   |
| Iiyama                  | 111       | 1.37%   |
| Sharp                   | 106       | 1.31%   |
| ViewSonic               | 93        | 1.15%   |
| Chi Mei Optoelectronics | 88        | 1.09%   |
| Unknown                 | 80        | 0.99%   |
| InfoVision              | 80        | 0.99%   |
| PANDA                   | 53        | 0.65%   |
| Eizo                    | 53        | 0.65%   |
| ASUSTek Computer        | 53        | 0.65%   |
| Sony                    | 43        | 0.53%   |
| HannStar                | 41        | 0.51%   |
| NEC Computers           | 38        | 0.47%   |
| LG Electronics          | 37        | 0.46%   |
| LG Philips              | 29        | 0.36%   |
| CSO                     | 26        | 0.32%   |
| Fujitsu Siemens         | 19        | 0.23%   |
| MSI                     | 18        | 0.22%   |
| Panasonic               | 17        | 0.21%   |
| Medion                  | 17        | 0.21%   |
| Vestel Elektronik       | 16        | 0.2%    |
| Vizio                   | 15        | 0.19%   |
| CPT                     | 15        | 0.19%   |
| Toshiba                 | 14        | 0.17%   |
| Unknown                 | 12        | 0.15%   |
| RTK                     | 11        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                 | 200       | 2.39%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 153       | 1.83%   |
| AU Optronics LCD Monitor AUO592D 1920x1080 293x165mm 13.2-inch       | 112       | 1.34%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                 | 52        | 0.62%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 44        | 0.53%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 44        | 0.53%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 43        | 0.51%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 41        | 0.49%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 41        | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 38        | 0.46%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 37        | 0.44%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                 | 37        | 0.44%   |
| BOE LCD Monitor BOE06B3 1920x1080                                    | 29        | 0.35%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 28        | 0.34%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 27        | 0.32%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 26        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 25        | 0.3%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 24        | 0.29%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 23        | 0.28%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch | 22        | 0.26%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 21        | 0.25%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                 | 21        | 0.25%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch       | 20        | 0.24%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 19        | 0.23%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch               | 18        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 17        | 0.2%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 17        | 0.2%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 16        | 0.19%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 16        | 0.19%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 16        | 0.19%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 16        | 0.19%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 16        | 0.19%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                     | 15        | 0.18%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 15        | 0.18%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 15        | 0.18%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 15        | 0.18%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 14        | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 14        | 0.17%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 14        | 0.17%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 13        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3147      | 40.43%  |
| 1366x768 (WXGA)    | 1380      | 17.73%  |
| 1280x800 (WXGA)    | 521       | 6.69%   |
| 3840x2160 (4K)     | 423       | 5.43%   |
| 2560x1440 (QHD)    | 314       | 4.03%   |
| 1280x1024 (SXGA)   | 314       | 4.03%   |
| 1600x900 (HD+)     | 269       | 3.46%   |
| 1920x1200 (WUXGA)  | 223       | 2.87%   |
| 1440x900 (WXGA+)   | 216       | 2.78%   |
| 1680x1050 (WSXGA+) | 190       | 2.44%   |
| Unknown            | 97        | 1.25%   |
| 2560x1080          | 75        | 0.96%   |
| 1024x600           | 67        | 0.86%   |
| 3440x1440          | 55        | 0.71%   |
| 1024x768 (XGA)     | 53        | 0.68%   |
| 1360x768           | 51        | 0.66%   |
| 2288x1287          | 46        | 0.59%   |
| 2560x1600          | 44        | 0.57%   |
| 3840x1080          | 38        | 0.49%   |
| 1600x1200          | 35        | 0.45%   |
| 3840x2400          | 21        | 0.27%   |
| 1920x540           | 20        | 0.26%   |
| 2880x1800          | 17        | 0.22%   |
| 2160x1440          | 13        | 0.17%   |
| 3200x1800 (QHD+)   | 10        | 0.13%   |
| 1280x720 (HD)      | 9         | 0.12%   |
| 4480x1440          | 8         | 0.1%    |
| 2736x1824          | 8         | 0.1%    |
| 1400x1050          | 8         | 0.1%    |
| 5760x2160          | 6         | 0.08%   |
| 5760x1080          | 6         | 0.08%   |
| 3840x1600          | 6         | 0.08%   |
| 3200x1080          | 6         | 0.08%   |
| 1920x1280          | 6         | 0.08%   |
| 7680x2160          | 5         | 0.06%   |
| 2048x1152          | 5         | 0.06%   |
| 2240x1400          | 4         | 0.05%   |
| 3840x1100          | 3         | 0.04%   |
| 3360x1050          | 3         | 0.04%   |
| 2256x1504          | 3         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1563      | 19.4%   |
| 13      | 1263      | 15.67%  |
| 14      | 649       | 8.05%   |
| 24      | 602       | 7.47%   |
| 27      | 511       | 6.34%   |
| 23      | 474       | 5.88%   |
| 17      | 404       | 5.01%   |
| 21      | 396       | 4.91%   |
| Unknown | 314       | 3.9%    |
| 11      | 283       | 3.51%   |
| 19      | 234       | 2.9%    |
| 12      | 198       | 2.46%   |
| 18      | 153       | 1.9%    |
| 22      | 125       | 1.55%   |
| 31      | 121       | 1.5%    |
| 20      | 106       | 1.32%   |
| 34      | 104       | 1.29%   |
| 10      | 72        | 0.89%   |
| 84      | 49        | 0.61%   |
| 25      | 48        | 0.6%    |
| 142     | 44        | 0.55%   |
| 72      | 39        | 0.48%   |
| 16      | 35        | 0.43%   |
| 54      | 30        | 0.37%   |
| 32      | 30        | 0.37%   |
| 40      | 28        | 0.35%   |
| 26      | 21        | 0.26%   |
| 29      | 19        | 0.24%   |
| 52      | 14        | 0.17%   |
| 28      | 14        | 0.17%   |
| 48      | 11        | 0.14%   |
| 46      | 9         | 0.11%   |
| 49      | 8         | 0.1%    |
| 43      | 8         | 0.1%    |
| 8       | 8         | 0.1%    |
| 65      | 7         | 0.09%   |
| 39      | 7         | 0.09%   |
| 33      | 7         | 0.09%   |
| 37      | 6         | 0.07%   |
| 55      | 5         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2706      | 34.14%  |
| 501-600        | 1483      | 18.71%  |
| 201-300        | 1439      | 18.15%  |
| 401-500        | 856       | 10.8%   |
| 351-400        | 457       | 5.77%   |
| Unknown        | 314       | 3.96%   |
| 601-700        | 224       | 2.83%   |
| 701-800        | 142       | 1.79%   |
| 1001-1500      | 99        | 1.25%   |
| 1501-2000      | 90        | 1.14%   |
| 801-900        | 49        | 0.62%   |
| More than 2000 | 44        | 0.56%   |
| 901-1000       | 13        | 0.16%   |
| 101-200        | 11        | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5155      | 70.24%  |
| 16/10   | 1236      | 16.84%  |
| 5/4     | 292       | 3.98%   |
| Unknown | 257       | 3.5%    |
| 21/9    | 123       | 1.68%   |
| 4/3     | 120       | 1.64%   |
| 3/2     | 66        | 0.9%    |
| 1.00    | 46        | 0.63%   |
| 6/5     | 14        | 0.19%   |
| 32/9    | 13        | 0.18%   |
| 2.65    | 5         | 0.07%   |
| 3.40    | 3         | 0.04%   |
| 3.20    | 2         | 0.03%   |
| 2.00    | 2         | 0.03%   |
| 1.96    | 2         | 0.03%   |
| 3.73    | 1         | 0.01%   |
| 0.62    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1548      | 19.39%  |
| 81-90          | 1463      | 18.32%  |
| 201-250        | 1242      | 15.55%  |
| 301-350        | 525       | 6.57%   |
| 151-200        | 461       | 5.77%   |
| 71-80          | 453       | 5.67%   |
| Unknown        | 314       | 3.93%   |
| 351-500        | 289       | 3.62%   |
| 51-60          | 286       | 3.58%   |
| 251-300        | 268       | 3.36%   |
| 141-150        | 265       | 3.32%   |
| 121-130        | 219       | 2.74%   |
| More than 1000 | 207       | 2.59%   |
| 61-70          | 182       | 2.28%   |
| 501-1000       | 84        | 1.05%   |
| 41-50          | 72        | 0.9%    |
| 131-140        | 43        | 0.54%   |
| 111-120        | 31        | 0.39%   |
| 91-100         | 22        | 0.28%   |
| 1-40           | 11        | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2386      | 30.74%  |
| 121-160       | 2164      | 27.88%  |
| 101-120       | 2065      | 26.61%  |
| 161-240       | 530       | 6.83%   |
| Unknown       | 315       | 4.06%   |
| 1-50          | 184       | 2.37%   |
| More than 240 | 117       | 1.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5953      | 67.66%  |
| 0     | 1578      | 17.94%  |
| 2     | 1132      | 12.87%  |
| 3     | 129       | 1.47%   |
| 4     | 5         | 0.06%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4118      | 32.98%  |
| Intel                             | 3968      | 31.77%  |
| Qualcomm Atheros                  | 1250      | 10.01%  |
| Broadcom                          | 894       | 7.16%   |
| Nvidia                            | 401       | 3.21%   |
| Broadcom Limited                  | 303       | 2.43%   |
| Marvell Technology Group          | 194       | 1.55%   |
| Ralink Technology                 | 114       | 0.91%   |
| Ralink                            | 95        | 0.76%   |
| TP-Link                           | 93        | 0.74%   |
| MediaTek                          | 93        | 0.74%   |
| ASIX Electronics                  | 74        | 0.59%   |
| Samsung Electronics               | 54        | 0.43%   |
| Dell                              | 39        | 0.31%   |
| Lenovo                            | 35        | 0.28%   |
| Huawei Technologies               | 34        | 0.27%   |
| Microchip Technology              | 33        | 0.26%   |
| Sierra Wireless                   | 31        | 0.25%   |
| JMicron Technology                | 28        | 0.22%   |
| Qualcomm Atheros Communications   | 27        | 0.22%   |
| D-Link System                     | 26        | 0.21%   |
| Aquantia                          | 26        | 0.21%   |
| Xiaomi                            | 25        | 0.2%    |
| Qualcomm                          | 24        | 0.19%   |
| Mellanox Technologies             | 24        | 0.19%   |
| Ericsson Business Mobile Networks | 24        | 0.19%   |
| DisplayLink                       | 23        | 0.18%   |
| Microsoft                         | 21        | 0.17%   |
| NetGear                           | 20        | 0.16%   |
| ASUSTek Computer                  | 19        | 0.15%   |
| D-Link                            | 18        | 0.14%   |
| Hewlett-Packard                   | 17        | 0.14%   |
| VIA Technologies                  | 16        | 0.13%   |
| IBM                               | 15        | 0.12%   |
| Silicon Integrated Systems [SiS]  | 14        | 0.11%   |
| FIBOCOM                           | 14        | 0.11%   |
| American Megatrends               | 13        | 0.1%    |
| Edimax Technology                 | 12        | 0.1%    |
| Dresden Elektronik                | 12        | 0.1%    |
| 3Com                              | 11        | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2923      | 20%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 443       | 3.03%   |
| Nvidia MCP79 Ethernet                                             | 323       | 2.21%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 318       | 2.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 284       | 1.94%   |
| Intel Wi-Fi 6 AX200                                               | 280       | 1.92%   |
| Intel Wi-Fi 6 AX201                                               | 278       | 1.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 227       | 1.55%   |
| Intel Wireless 8265 / 8275                                        | 222       | 1.52%   |
| Intel Wireless 7260                                               | 215       | 1.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 211       | 1.44%   |
| Intel Wireless 7265                                               | 195       | 1.33%   |
| Intel I211 Gigabit Network Connection                             | 187       | 1.28%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 165       | 1.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 155       | 1.06%   |
| Intel Ethernet Connection (13) I219-V                             | 141       | 0.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 139       | 0.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 136       | 0.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 131       | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 129       | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 128       | 0.88%   |
| Intel Wireless 8260                                               | 119       | 0.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 119       | 0.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 119       | 0.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 115       | 0.79%   |
| Intel Wireless 3165                                               | 110       | 0.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 104       | 0.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 103       | 0.7%    |
| Intel I210 Gigabit Network Connection                             | 102       | 0.7%    |
| Intel Ethernet Connection (2) I219-V                              | 97        | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 87        | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 84        | 0.57%   |
| Intel 82579V Gigabit Network Connection                           | 84        | 0.57%   |
| Intel Wireless-AC 9260                                            | 83        | 0.57%   |
| Intel Ethernet Connection I217-LM                                 | 83        | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 74        | 0.51%   |
| Intel Ethernet Controller I225-V                                  | 73        | 0.5%    |
| Intel 82574L Gigabit Network Connection                           | 73        | 0.5%    |
| Intel Ethernet Connection (4) I219-V                              | 69        | 0.47%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 65        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2798      | 46.22%  |
| Qualcomm Atheros                      | 1016      | 16.78%  |
| Realtek Semiconductor                 | 785       | 12.97%  |
| Broadcom                              | 620       | 10.24%  |
| Broadcom Limited                      | 230       | 3.8%    |
| Ralink Technology                     | 114       | 1.88%   |
| Ralink                                | 95        | 1.57%   |
| TP-Link                               | 68        | 1.12%   |
| MediaTek                              | 66        | 1.09%   |
| Sierra Wireless                       | 31        | 0.51%   |
| Qualcomm Atheros Communications       | 27        | 0.45%   |
| NetGear                               | 20        | 0.33%   |
| Dell                                  | 20        | 0.33%   |
| ASUSTek Computer                      | 19        | 0.31%   |
| D-Link                                | 16        | 0.26%   |
| D-Link System                         | 15        | 0.25%   |
| Marvell Technology Group              | 14        | 0.23%   |
| Microsoft                             | 13        | 0.21%   |
| Fibocom                               | 13        | 0.21%   |
| Edimax Technology                     | 12        | 0.2%    |
| Qualcomm                              | 9         | 0.15%   |
| Belkin Components                     | 9         | 0.15%   |
| IMC Networks                          | 5         | 0.08%   |
| Gemtek                                | 5         | 0.08%   |
| Wilocity                              | 4         | 0.07%   |
| Linksys                               | 4         | 0.07%   |
| Ericsson Business Mobile Networks     | 4         | 0.07%   |
| Hewlett-Packard                       | 3         | 0.05%   |
| Micro Star International              | 2         | 0.03%   |
| AVM                                   | 2         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.03%   |
| 3Com                                  | 2         | 0.03%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| Z-Com                                 | 1         | 0.02%   |
| Winbond Electronics                   | 1         | 0.02%   |
| TRENDnet                              | 1         | 0.02%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Quectel Wireless Solutions            | 1         | 0.02%   |
| PLANEX                                | 1         | 0.02%   |
| Fiberline                             | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 318       | 5.23%   |
| Intel Wi-Fi 6 AX200                                                                   | 280       | 4.6%    |
| Intel Wi-Fi 6 AX201                                                                   | 278       | 4.57%   |
| Intel Wireless 8265 / 8275                                                            | 222       | 3.65%   |
| Intel Wireless 7260                                                                   | 215       | 3.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 211       | 3.47%   |
| Intel Wireless 7265                                                                   | 195       | 3.2%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 165       | 2.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 155       | 2.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 136       | 2.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 131       | 2.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 129       | 2.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 128       | 2.1%    |
| Intel Wireless 8260                                                                   | 119       | 1.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 119       | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 119       | 1.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 115       | 1.89%   |
| Intel Wireless 3165                                                                   | 110       | 1.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 104       | 1.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 103       | 1.69%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 87        | 1.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 84        | 1.38%   |
| Intel Wireless-AC 9260                                                                | 83        | 1.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 74        | 1.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 62        | 1.02%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 61        | 1%      |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 60        | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 58        | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 57        | 0.94%   |
| Intel Wireless 3160                                                                   | 45        | 0.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 45        | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 45        | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 44        | 0.72%   |
| Ralink MT7601U Wireless Adapter                                                       | 42        | 0.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 42        | 0.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 41        | 0.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 41        | 0.67%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 40        | 0.66%   |
| Intel Centrino Ultimate-N 6300                                                        | 40        | 0.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 37        | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3809      | 47.18%  |
| Intel                             | 2306      | 28.56%  |
| Nvidia                            | 401       | 4.97%   |
| Qualcomm Atheros                  | 351       | 4.35%   |
| Broadcom                          | 332       | 4.11%   |
| Marvell Technology Group          | 181       | 2.24%   |
| Broadcom Limited                  | 76        | 0.94%   |
| ASIX Electronics                  | 74        | 0.92%   |
| Samsung Electronics               | 54        | 0.67%   |
| Lenovo                            | 35        | 0.43%   |
| Microchip Technology              | 32        | 0.4%    |
| JMicron Technology                | 28        | 0.35%   |
| MediaTek                          | 26        | 0.32%   |
| Aquantia                          | 26        | 0.32%   |
| Xiaomi                            | 25        | 0.31%   |
| TP-Link                           | 25        | 0.31%   |
| Huawei Technologies               | 24        | 0.3%    |
| DisplayLink                       | 23        | 0.28%   |
| Mellanox Technologies             | 22        | 0.27%   |
| VIA Technologies                  | 16        | 0.2%    |
| IBM                               | 15        | 0.19%   |
| Silicon Integrated Systems [SiS]  | 14        | 0.17%   |
| Qualcomm                          | 13        | 0.16%   |
| American Megatrends               | 13        | 0.16%   |
| D-Link System                     | 11        | 0.14%   |
| ICS Advent                        | 9         | 0.11%   |
| 3Com                              | 9         | 0.11%   |
| Microsoft                         | 8         | 0.1%    |
| Cypress Semiconductor             | 8         | 0.1%    |
| OPPO                              | 7         | 0.09%   |
| Motorola PCS                      | 7         | 0.09%   |
| Standard Microsystems             | 6         | 0.07%   |
| Hewlett-Packard                   | 6         | 0.07%   |
| Attansic Technology               | 6         | 0.07%   |
| Apple                             | 6         | 0.07%   |
| Sundance Technology Inc / IC Plus | 5         | 0.06%   |
| ZTE WCDMA Technologies MSM        | 4         | 0.05%   |
| Spreadtrum Communications         | 4         | 0.05%   |
| NetXen Incorporated               | 4         | 0.05%   |
| Google                            | 4         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2923      | 35.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 443       | 5.32%   |
| Nvidia MCP79 Ethernet                                             | 323       | 3.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 284       | 3.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 227       | 2.73%   |
| Intel I211 Gigabit Network Connection                             | 187       | 2.25%   |
| Intel Ethernet Connection (13) I219-V                             | 141       | 1.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 139       | 1.67%   |
| Intel I210 Gigabit Network Connection                             | 102       | 1.22%   |
| Intel Ethernet Connection (2) I219-V                              | 97        | 1.16%   |
| Intel 82579V Gigabit Network Connection                           | 84        | 1.01%   |
| Intel Ethernet Connection I217-LM                                 | 83        | 1%      |
| Intel Ethernet Controller I225-V                                  | 73        | 0.88%   |
| Intel 82574L Gigabit Network Connection                           | 73        | 0.88%   |
| Intel Ethernet Connection (4) I219-V                              | 69        | 0.83%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 65        | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 63        | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 60        | 0.72%   |
| Intel Ethernet Connection (6) I219-V                              | 58        | 0.7%    |
| Intel Ethernet Connection I219-LM                                 | 57        | 0.68%   |
| Intel Ethernet Connection I218-LM                                 | 57        | 0.68%   |
| Intel I350 Gigabit Network Connection                             | 55        | 0.66%   |
| Intel Ethernet Connection (7) I219-V                              | 55        | 0.66%   |
| ASIX AX88179 Gigabit Ethernet                                     | 54        | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 53        | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                             | 52        | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 48        | 0.58%   |
| Intel Ethernet Connection I217-V                                  | 45        | 0.54%   |
| Intel Ethernet Connection (14) I219-V                             | 44        | 0.53%   |
| Nvidia MCP61 Ethernet                                             | 43        | 0.52%   |
| Intel 82577LM Gigabit Network Connection                          | 42        | 0.5%    |
| Intel Ethernet Connection (10) I219-V                             | 41        | 0.49%   |
| Intel Ethernet Connection (2) I218-V                              | 39        | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 36        | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 34        | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 34        | 0.41%   |
| Intel 82567LM Gigabit Network Connection                          | 33        | 0.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 32        | 0.38%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 32        | 0.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 31        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 7484      | 55.49%  |
| WiFi     | 5804      | 43.04%  |
| Modem    | 180       | 1.33%   |
| Unknown  | 18        | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4529      | 52.26%  |
| WiFi     | 4137      | 47.74%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 4482      | 51.81%  |
| 1     | 3441      | 39.78%  |
| 0     | 334       | 3.86%   |
| 3     | 237       | 2.74%   |
| 4     | 89        | 1.03%   |
| 6     | 27        | 0.31%   |
| 5     | 18        | 0.21%   |
| 8     | 11        | 0.13%   |
| 20    | 2         | 0.02%   |
| 10    | 2         | 0.02%   |
| 9     | 2         | 0.02%   |
| 7     | 2         | 0.02%   |
| 21    | 1         | 0.01%   |
| 14    | 1         | 0.01%   |
| 13    | 1         | 0.01%   |
| 12    | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 7400      | 84.75%  |
| Yes     | 1331      | 15.24%  |
| Unknown | 1         | 0.01%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2257      | 46.65%  |
| Apple                           | 642       | 13.27%  |
| Realtek Semiconductor           | 380       | 7.85%   |
| Qualcomm Atheros Communications | 371       | 7.67%   |
| Cambridge Silicon Radio         | 233       | 4.82%   |
| Broadcom                        | 232       | 4.8%    |
| IMC Networks                    | 154       | 3.18%   |
| Lite-On Technology              | 135       | 2.79%   |
| Foxconn / Hon Hai               | 94        | 1.94%   |
| ASUSTek Computer                | 89        | 1.84%   |
| Dell                            | 61        | 1.26%   |
| Hewlett-Packard                 | 42        | 0.87%   |
| Realtek                         | 24        | 0.5%    |
| Toshiba                         | 23        | 0.48%   |
| MediaTek                        | 20        | 0.41%   |
| Ralink                          | 19        | 0.39%   |
| Foxconn International           | 9         | 0.19%   |
| Alps Electric                   | 6         | 0.12%   |
| TP-Link                         | 5         | 0.1%    |
| Ralink Technology               | 5         | 0.1%    |
| Marvell Semiconductor           | 5         | 0.1%    |
| Edimax Technology               | 4         | 0.08%   |
| Belkin Components               | 4         | 0.08%   |
| Taiyo Yuden                     | 3         | 0.06%   |
| USI                             | 2         | 0.04%   |
| Unknown                         | 2         | 0.04%   |
| Qcom                            | 2         | 0.04%   |
| Micro Star International        | 2         | 0.04%   |
| Integrated System Solution      | 2         | 0.04%   |
| Fujitsu                         | 2         | 0.04%   |
| Sitecom Europe                  | 1         | 0.02%   |
| Opticis                         | 1         | 0.02%   |
| Microsoft                       | 1         | 0.02%   |
| Kensington                      | 1         | 0.02%   |
| Dynex                           | 1         | 0.02%   |
| Com One                         | 1         | 0.02%   |
| Chicony Electronics             | 1         | 0.02%   |
| Askey Computer                  | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 860       | 17.75%  |
| Intel AX201 Bluetooth                               | 476       | 9.83%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 323       | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 322       | 6.65%   |
| Intel AX200 Bluetooth                               | 269       | 5.55%   |
| Realtek Bluetooth Radio                             | 238       | 4.91%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 233       | 4.81%   |
| Qualcomm Atheros  Bluetooth Device                  | 206       | 4.25%   |
| Apple Bluetooth USB Host Controller                 | 184       | 3.8%    |
| Realtek  Bluetooth 4.2 Adapter                      | 92        | 1.9%    |
| Intel Wireless-AC 3168 Bluetooth                    | 82        | 1.69%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 79        | 1.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 78        | 1.61%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 51        | 1.05%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 49        | 1.01%   |
| Intel AX210 Bluetooth                               | 49        | 1.01%   |
| IMC Networks Bluetooth Radio                        | 47        | 0.97%   |
| Intel Bluetooth Device                              | 46        | 0.95%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 45        | 0.93%   |
| IMC Networks Bluetooth Device                       | 45        | 0.93%   |
| Apple Bluetooth Host Controller                     | 42        | 0.87%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 40        | 0.83%   |
| Broadcom BCM2045B (BDC-2.1)                         | 39        | 0.81%   |
| Lite-On Bluetooth Device                            | 37        | 0.76%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 37        | 0.76%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 35        | 0.72%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 33        | 0.68%   |
| Foxconn / Hon Hai Bluetooth Device                  | 32        | 0.66%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 29        | 0.6%    |
| Foxconn / Hon Hai Wireless_Device                   | 25        | 0.52%   |
| IMC Networks Wireless_Device                        | 24        | 0.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 24        | 0.5%    |
| Dell DW375 Bluetooth Module                         | 21        | 0.43%   |
| Realtek RTL8723B Bluetooth                          | 20        | 0.41%   |
| Realtek 802.11ac WLAN Adapter                       | 19        | 0.39%   |
| Ralink RT3290 Bluetooth                             | 19        | 0.39%   |
| MediaTek Wireless_Device                            | 19        | 0.39%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 18        | 0.37%   |
| Lite-On Atheros AR3012 Bluetooth                    | 18        | 0.37%   |
| HP Broadcom 2070 Bluetooth Combo                    | 18        | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 5878      | 54.95%  |
| AMD                                          | 1941      | 18.15%  |
| Nvidia                                       | 1861      | 17.4%   |
| C-Media Electronics                          | 154       | 1.44%   |
| Logitech                                     | 82        | 0.77%   |
| Creative Labs                                | 56        | 0.52%   |
| Texas Instruments                            | 43        | 0.4%    |
| ASUSTek Computer                             | 36        | 0.34%   |
| Realtek Semiconductor                        | 35        | 0.33%   |
| GN Netcom                                    | 35        | 0.33%   |
| Lenovo                                       | 34        | 0.32%   |
| Plantronics                                  | 32        | 0.3%    |
| Generalplus Technology                       | 32        | 0.3%    |
| JMTek                                        | 24        | 0.22%   |
| Creative Technology                          | 24        | 0.22%   |
| Focusrite-Novation                           | 23        | 0.22%   |
| VIA Technologies                             | 20        | 0.19%   |
| Kingston Technology                          | 20        | 0.19%   |
| Silicon Integrated Systems [SiS]             | 15        | 0.14%   |
| Micro Star International                     | 15        | 0.14%   |
| Hewlett-Packard                              | 15        | 0.14%   |
| Dell                                         | 15        | 0.14%   |
| RODE Microphones                             | 13        | 0.12%   |
| BEHRINGER International                      | 13        | 0.12%   |
| Razer USA                                    | 12        | 0.11%   |
| SteelSeries ApS                              | 11        | 0.1%    |
| Microsoft                                    | 11        | 0.1%    |
| GYROCOM C&C                                  | 10        | 0.09%   |
| Blue Microphones                             | 10        | 0.09%   |
| KTMicro                                      | 9         | 0.08%   |
| Corsair                                      | 8         | 0.07%   |
| Zoran Co. Personal Media Division (Nogatech) | 7         | 0.07%   |
| Yamaha                                       | 7         | 0.07%   |
| Sennheiser Communications                    | 7         | 0.07%   |
| M-Audio                                      | 7         | 0.07%   |
| Tenx Technology                              | 6         | 0.06%   |
| DSEA A/S                                     | 6         | 0.06%   |
| Cambridge Silicon Radio                      | 6         | 0.06%   |
| XMOS                                         | 5         | 0.05%   |
| Samsung Electronics                          | 5         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 595       | 4.71%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 574       | 4.54%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 490       | 3.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 474       | 3.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 388       | 3.07%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 349       | 2.76%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 342       | 2.7%    |
| Nvidia MCP79 High Definition Audio                                                                | 325       | 2.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 312       | 2.47%   |
| Intel Broadwell-U Audio Controller                                                                | 293       | 2.32%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 288       | 2.28%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 276       | 2.18%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 266       | 2.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 258       | 2.04%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 257       | 2.03%   |
| Intel Cannon Lake PCH cAVS                                                                        | 241       | 1.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 209       | 1.65%   |
| Intel 200 Series PCH HD Audio                                                                     | 190       | 1.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 182       | 1.44%   |
| AMD FCH Azalia Controller                                                                         | 177       | 1.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 175       | 1.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 175       | 1.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 168       | 1.33%   |
| Intel 8 Series HD Audio Controller                                                                | 168       | 1.33%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 157       | 1.24%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 157       | 1.24%   |
| Intel Comet Lake PCH cAVS                                                                         | 146       | 1.15%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 144       | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 143       | 1.13%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 134       | 1.06%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 131       | 1.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 125       | 0.99%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 122       | 0.96%   |
| AMD Kabini HDMI/DP Audio                                                                          | 116       | 0.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 110       | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 100       | 0.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 95        | 0.75%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 88        | 0.7%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 82        | 0.65%   |
| Nvidia High Definition Audio Controller                                                           | 81        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1676      | 21.06%  |
| SK hynix            | 1558      | 19.58%  |
| Kingston            | 933       | 11.72%  |
| Unknown             | 831       | 10.44%  |
| Micron Technology   | 623       | 7.83%   |
| Crucial             | 603       | 7.58%   |
| Corsair             | 318       | 4%      |
| G.Skill             | 224       | 2.81%   |
| Elpida              | 147       | 1.85%   |
| A-DATA Technology   | 141       | 1.77%   |
| Ramaxel Technology  | 105       | 1.32%   |
| Patriot             | 84        | 1.06%   |
| Unknown             | 78        | 0.98%   |
| Unknown (ABCD)      | 75        | 0.94%   |
| Nanya Technology    | 71        | 0.89%   |
| Smart               | 47        | 0.59%   |
| Team                | 42        | 0.53%   |
| Transcend           | 38        | 0.48%   |
| GOODRAM             | 31        | 0.39%   |
| AMD                 | 27        | 0.34%   |
| Hikvision           | 21        | 0.26%   |
| Apacer              | 17        | 0.21%   |
| Hewlett-Packard     | 16        | 0.2%    |
| Teikon              | 13        | 0.16%   |
| Silicon Power       | 11        | 0.14%   |
| Qimonda             | 11        | 0.14%   |
| 48spaces            | 11        | 0.14%   |
| PNY                 | 9         | 0.11%   |
| GeIL                | 8         | 0.1%    |
| ASint Technology    | 8         | 0.1%    |
| Timetec             | 7         | 0.09%   |
| Smart Brazil        | 6         | 0.08%   |
| Goldkey             | 6         | 0.08%   |
| Avant               | 6         | 0.08%   |
| Wilk                | 5         | 0.06%   |
| Unifosa             | 4         | 0.05%   |
| Toshiba             | 4         | 0.05%   |
| Neo Forza           | 4         | 0.05%   |
| Kllisre             | 4         | 0.05%   |
| Infineon            | 4         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 258       | 3.02%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 154       | 1.8%    |
| Unknown                                                          | 78        | 0.91%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 0.8%    |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 67        | 0.78%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 63        | 0.74%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 46        | 0.54%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 44        | 0.51%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 43        | 0.5%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 43        | 0.5%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 42        | 0.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 41        | 0.48%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 41        | 0.48%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 40        | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 39        | 0.46%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 38        | 0.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 38        | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 36        | 0.42%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s            | 36        | 0.42%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 34        | 0.4%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 33        | 0.39%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 33        | 0.39%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 31        | 0.36%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 31        | 0.36%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s            | 31        | 0.36%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 30        | 0.35%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 30        | 0.35%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.34%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 29        | 0.34%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s           | 28        | 0.33%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 27        | 0.32%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 27        | 0.32%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 26        | 0.3%    |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 25        | 0.29%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 25        | 0.29%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.29%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 24        | 0.28%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 24        | 0.28%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s             | 24        | 0.28%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 24        | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 2979      | 42.34%  |
| DDR3         | 2385      | 33.9%   |
| DDR2         | 714       | 10.15%  |
| SDRAM        | 227       | 3.23%   |
| Unknown      | 224       | 3.18%   |
| LPDDR4       | 201       | 2.86%   |
| LPDDR3       | 161       | 2.29%   |
| DDR          | 74        | 1.05%   |
| DDR5         | 37        | 0.53%   |
| LPDDR5       | 17        | 0.24%   |
| DRAM         | 15        | 0.21%   |
| RAM          | 1         | 0.01%   |
| DDR2 FB-DIMM | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 3861      | 55.13%  |
| DIMM         | 2715      | 38.77%  |
| Row Of Chips | 312       | 4.46%   |
| Unknown      | 62        | 0.89%   |
| Chip         | 35        | 0.5%    |
| FB-DIMM      | 14        | 0.2%    |
| RIMM         | 4         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 2456      | 32.26%  |
| 4096    | 1915      | 25.16%  |
| 2048    | 1160      | 15.24%  |
| 16384   | 1002      | 13.16%  |
| 1024    | 695       | 9.13%   |
| 32768   | 271       | 3.56%   |
| 512     | 74        | 0.97%   |
| 256     | 22        | 0.29%   |
| 65536   | 7         | 0.09%   |
| 1536    | 4         | 0.05%   |
| 128     | 4         | 0.05%   |
| 384     | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1616      | 21.41%  |
| 2667    | 976       | 12.93%  |
| 3200    | 963       | 12.76%  |
| 1333    | 531       | 7.03%   |
| 800     | 493       | 6.53%   |
| 2400    | 492       | 6.52%   |
| 2133    | 363       | 4.81%   |
| 667     | 272       | 3.6%    |
| Unknown | 209       | 2.77%   |
| 1334    | 174       | 2.31%   |
| 3600    | 147       | 1.95%   |
| 1867    | 110       | 1.46%   |
| 2666    | 94        | 1.25%   |
| 1067    | 91        | 1.21%   |
| 1866    | 87        | 1.15%   |
| 1066    | 75        | 0.99%   |
| 4267    | 66        | 0.87%   |
| 3266    | 62        | 0.82%   |
| 3400    | 53        | 0.7%    |
| 2933    | 48        | 0.64%   |
| 3000    | 47        | 0.62%   |
| 533     | 41        | 0.54%   |
| 3733    | 37        | 0.49%   |
| 4199    | 32        | 0.42%   |
| 3466    | 32        | 0.42%   |
| 4800    | 29        | 0.38%   |
| 400     | 29        | 0.38%   |
| 2866    | 27        | 0.36%   |
| 2048    | 27        | 0.36%   |
| 1800    | 22        | 0.29%   |
| 3800    | 20        | 0.26%   |
| 975     | 19        | 0.25%   |
| 6400    | 18        | 0.24%   |
| 333     | 17        | 0.23%   |
| 8400    | 16        | 0.21%   |
| 3866    | 14        | 0.19%   |
| 4266    | 13        | 0.17%   |
| 266     | 13        | 0.17%   |
| 3666    | 9         | 0.12%   |
| 3534    | 9         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 57        | 32.2%   |
| Brother Industries     | 34        | 19.21%  |
| Canon                  | 21        | 11.86%  |
| Samsung Electronics    | 12        | 6.78%   |
| Seiko Epson            | 10        | 5.65%   |
| Xerox                  | 8         | 4.52%   |
| Prolific Technology    | 5         | 2.82%   |
| Dymo-CoStar            | 5         | 2.82%   |
| Kyocera                | 4         | 2.26%   |
| Zebra                  | 3         | 1.69%   |
| Pantum                 | 3         | 1.69%   |
| STMicroelectronics     | 2         | 1.13%   |
| Lexmark International  | 2         | 1.13%   |
| Datamax-O'Neil         | 2         | 1.13%   |
| Xiaomi                 | 1         | 0.56%   |
| Ricoh                  | 1         | 0.56%   |
| QinHeng Electronics    | 1         | 0.56%   |
| Panasonic (Matsushita) | 1         | 0.56%   |
| Oki Data               | 1         | 0.56%   |
| Konica Minolta         | 1         | 0.56%   |
| GODEX INTERNATIONAL    | 1         | 0.56%   |
| Dell                   | 1         | 0.56%   |
| Apple                  | 1         | 0.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Xerox B205                                                            | 7         | 3.91%   |
| HP LaserJet 1020                                                      | 7         | 3.91%   |
| Prolific PL2305 Parallel Port                                         | 5         | 2.79%   |
| HP LaserJet 1200                                                      | 4         | 2.23%   |
| HP LaserJet M101-M106                                                 | 3         | 1.68%   |
| HP DeskJet 2130 series                                                | 3         | 1.68%   |
| Brother HL-52x0 series                                                | 3         | 1.68%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 2         | 1.12%   |
| Samsung ML-216x Series Laser Printer                                  | 2         | 1.12%   |
| Samsung ML-1660 Series                                                | 2         | 1.12%   |
| Pantum P2500W series                                                  | 2         | 1.12%   |
| Lexmark International CS417dn                                         | 2         | 1.12%   |
| HP LaserJet Pro M404-M405                                             | 2         | 1.12%   |
| HP LaserJet P1005                                                     | 2         | 1.12%   |
| HP LaserJet M14-M17                                                   | 2         | 1.12%   |
| HP LaserJet 400 M401n                                                 | 2         | 1.12%   |
| HP ENVY Photo 6200 series                                             | 2         | 1.12%   |
| HP ENVY 4520 series                                                   | 2         | 1.12%   |
| HP DeskJet Plus 4100 series                                           | 2         | 1.12%   |
| HP DeskJet 2620 All-in-One Printer                                    | 2         | 1.12%   |
| Dymo-CoStar LabelWriter 450                                           | 2         | 1.12%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                                | 2         | 1.12%   |
| Datamax-O'Neil Datamax E-4304                                         | 2         | 1.12%   |
| Canon PIXMA MX920 Series                                              | 2         | 1.12%   |
| Canon PIXMA MG3600 Series                                             | 2         | 1.12%   |
| Canon MF4410                                                          | 2         | 1.12%   |
| Canon LiDE 400                                                        | 2         | 1.12%   |
| Canon G3010 series                                                    | 2         | 1.12%   |
| Brother PT-9500PC                                                     | 2         | 1.12%   |
| Brother Printer                                                       | 2         | 1.12%   |
| Brother HL-3040CN series                                              | 2         | 1.12%   |
| Zebra ZTC ZP 500 (ZPL)                                                | 1         | 0.56%   |
| Zebra ZTC ZD420-203dpi ZPL                                            | 1         | 0.56%   |
| Zebra ZTC S4M-200dpi ZPL                                              | 1         | 0.56%   |
| Xiaomi MiMouse 2                                                      | 1         | 0.56%   |
| Xerox Phaser 3250                                                     | 1         | 0.56%   |
| Seiko Epson XP-200 Series                                             | 1         | 0.56%   |
| Seiko Epson XP-15000 Series                                           | 1         | 0.56%   |
| Seiko Epson Printer                                                   | 1         | 0.56%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 0.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 30        | 56.6%   |
| Seiko Epson        | 12        | 22.64%  |
| Hewlett-Packard    | 6         | 11.32%  |
| Mustek Systems     | 2         | 3.77%   |
| AGFA-Gevaert NV    | 2         | 3.77%   |
| Ultima Electronics | 1         | 1.89%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 8         | 15.09%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 6         | 11.32%  |
| Canon CanoScan LiDE 220                                                               | 4         | 7.55%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 2         | 3.77%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2         | 3.77%   |
| Canon CanoScan LIDE 25                                                                | 2         | 3.77%   |
| Canon CanoScan LiDE 210                                                               | 2         | 3.77%   |
| Canon CanoScan LiDE 120                                                               | 2         | 3.77%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 2         | 3.77%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 1.89%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1         | 1.89%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1         | 1.89%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 1         | 1.89%   |
| Seiko Epson GT-9800F [Perfection 3200]                                                | 1         | 1.89%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 1.89%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1         | 1.89%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO]                         | 1         | 1.89%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 1         | 1.89%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]                           | 1         | 1.89%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 1         | 1.89%   |
| Mustek Systems SNAPSCAN e22                                                           | 1         | 1.89%   |
| Mustek Systems BearPaw 2448 TA Pro                                                    | 1         | 1.89%   |
| HP ScanJet Pro 2500 f1                                                                | 1         | 1.89%   |
| HP ScanJet 82x0C                                                                      | 1         | 1.89%   |
| HP ScanJet 7650                                                                       | 1         | 1.89%   |
| HP ScanJet 3970c                                                                      | 1         | 1.89%   |
| HP Scanjet 300                                                                        | 1         | 1.89%   |
| HP Scanjet 200                                                                        | 1         | 1.89%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 1         | 1.89%   |
| Canon CanoScan 9000F Mark II                                                          | 1         | 1.89%   |
| Canon CanoScan 8800F                                                                  | 1         | 1.89%   |
| Canon CanoScan 5600F                                                                  | 1         | 1.89%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 952       | 21.69%  |
| IMC Networks                           | 415       | 9.45%   |
| Acer                                   | 413       | 9.41%   |
| Microdia                               | 335       | 7.63%   |
| Realtek Semiconductor                  | 307       | 6.99%   |
| Logitech                               | 283       | 6.45%   |
| Quanta                                 | 265       | 6.04%   |
| Sunplus Innovation Technology          | 205       | 4.67%   |
| Cheng Uei Precision Industry (Foxlink) | 114       | 2.6%    |
| Suyin                                  | 113       | 2.57%   |
| Apple                                  | 104       | 2.37%   |
| Lite-On Technology                     | 89        | 2.03%   |
| Syntek                                 | 88        | 2%      |
| Bison Electronics                      | 81        | 1.85%   |
| Luxvisions Innotech Limited            | 52        | 1.18%   |
| Silicon Motion                         | 49        | 1.12%   |
| Alcor Micro                            | 49        | 1.12%   |
| Samsung Electronics                    | 36        | 0.82%   |
| Microsoft                              | 36        | 0.82%   |
| Z-Star Microelectronics                | 34        | 0.77%   |
| Lenovo                                 | 32        | 0.73%   |
| Ricoh                                  | 30        | 0.68%   |
| Generalplus Technology                 | 23        | 0.52%   |
| Primax Electronics                     | 18        | 0.41%   |
| Creative Technology                    | 16        | 0.36%   |
| Sonix Technology                       | 14        | 0.32%   |
| DLEQNA19IFK6G2                         | 14        | 0.32%   |
| Genesys Logic                          | 13        | 0.3%    |
| GEMBIRD                                | 12        | 0.27%   |
| ARC International                      | 12        | 0.27%   |
| Jieli Technology                       | 11        | 0.25%   |
| KYE Systems (Mouse Systems)            | 10        | 0.23%   |
| ALi                                    | 10        | 0.23%   |
| Unknown                                | 9         | 0.21%   |
| Importek                               | 9         | 0.21%   |
| MacroSilicon                           | 8         | 0.18%   |
| SunplusIT                              | 7         | 0.16%   |
| icSpring                               | 7         | 0.16%   |
| Cubeternet                             | 7         | 0.16%   |
| Intel                                  | 6         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 274       | 6.19%   |
| Acer Integrated Camera                  | 167       | 3.77%   |
| Microdia Integrated_Webcam_HD           | 138       | 3.12%   |
| IMC Networks Integrated Camera          | 137       | 3.09%   |
| Realtek Integrated_Webcam_HD            | 116       | 2.62%   |
| IMC Networks USB2.0 HD UVC WebCam       | 92        | 2.08%   |
| Chicony HD Webcam                       | 82        | 1.85%   |
| Logitech Webcam C270                    | 73        | 1.65%   |
| Bison Integrated 5M Camera              | 73        | 1.65%   |
| Sunplus Integrated_Webcam_HD            | 69        | 1.56%   |
| Quanta Chromebook HD Camera             | 68        | 1.54%   |
| Acer BisonCam, NB Pro                   | 60        | 1.35%   |
| Syntek Integrated Camera                | 48        | 1.08%   |
| Chicony HP HD Camera                    | 46        | 1.04%   |
| Chicony Integrated 5M Camera            | 43        | 0.97%   |
| Logitech HD Pro Webcam C920             | 42        | 0.95%   |
| Chicony USB2.0 HD UVC WebCam            | 42        | 0.95%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 40        | 0.9%    |
| Quanta HP TrueVision HD Camera          | 36        | 0.81%   |
| Samsung Galaxy A5 (MTP)                 | 35        | 0.79%   |
| Lite-On Integrated Camera               | 34        | 0.77%   |
| Microdia Integrated Webcam              | 33        | 0.75%   |
| Apple iPhone 5/5C/5S/6/SE               | 33        | 0.75%   |
| Acer SunplusIT Integrated Camera        | 32        | 0.72%   |
| Apple Built-in iSight                   | 31        | 0.7%    |
| Chicony Integrated Camera (1280x720@30) | 30        | 0.68%   |
| Quanta HD User Facing                   | 29        | 0.65%   |
| Acer Lenovo EasyCamera                  | 28        | 0.63%   |
| Quanta HP HD Camera                     | 27        | 0.61%   |
| Chicony EasyCamera                      | 26        | 0.59%   |
| Logitech C922 Pro Stream Webcam         | 25        | 0.56%   |
| Chicony HP TrueVision HD Camera         | 25        | 0.56%   |
| Apple FaceTime HD Camera (Built-in)     | 25        | 0.56%   |
| Realtek USB Camera                      | 23        | 0.52%   |
| Quanta VGA WebCam                       | 23        | 0.52%   |
| Sunplus HD WebCam                       | 22        | 0.5%    |
| Chicony HD User Facing                  | 22        | 0.5%    |
| Lite-On HP HD Camera                    | 21        | 0.47%   |
| Acer Lenovo Integrated Webcam           | 21        | 0.47%   |
| Realtek USB2.0 HD UVC WebCam            | 19        | 0.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 375       | 41.12%  |
| Validity Sensors                   | 254       | 27.85%  |
| Shenzhen Goodix Technology         | 109       | 11.95%  |
| AuthenTec                          | 44        | 4.82%   |
| Upek                               | 43        | 4.71%   |
| Elan Microelectronics              | 42        | 4.61%   |
| LighTuning Technology              | 22        | 2.41%   |
| STMicroelectronics                 | 16        | 1.75%   |
| Samsung Electronics                | 4         | 0.44%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.22%   |
| Microsoft                          | 1         | 0.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 218       | 23.9%   |
| Shenzhen Goodix  FingerPrint Device                                        | 61        | 6.69%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 55        | 6.03%   |
| Unknown                                                                    | 54        | 5.92%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 49        | 5.37%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 44        | 4.82%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 39        | 4.28%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 31        | 3.4%    |
| Shenzhen Goodix Fingerprint Reader                                         | 30        | 3.29%   |
| Elan ELAN:Fingerprint                                                      | 26        | 2.85%   |
| Validity Sensors Synaptics WBDI                                            | 24        | 2.63%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 22        | 2.41%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 19        | 2.08%   |
| Shenzhen Goodix FingerPrint                                                | 18        | 1.97%   |
| AuthenTec AES2810                                                          | 18        | 1.97%   |
| Synaptics  WBDI                                                            | 16        | 1.75%   |
| Elan ELAN:ARM-M4                                                           | 15        | 1.64%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 14        | 1.54%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 14        | 1.54%   |
| STMicroelectronics Fingerprint Reader                                      | 14        | 1.54%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 1.54%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 1.54%   |
| Validity Sensors VFS491                                                    | 12        | 1.32%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 1.1%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 0.99%   |
| Validity Sensors VFS Fingerprint sensor                                    | 9         | 0.99%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 0.99%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 0.66%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 0.55%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 0.55%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 0.44%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.44%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.44%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.44%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 3         | 0.33%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.33%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.22%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.22%   |
| STMicroelectronics TouchChipÂ Fingerprint Reader                          | 2         | 0.22%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.22%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 145       | 34.69%  |
| Alcor Micro                | 143       | 34.21%  |
| Lenovo                     | 28        | 6.7%    |
| O2 Micro                   | 27        | 6.46%   |
| Upek                       | 26        | 6.22%   |
| Gemalto (was Gemplus)      | 8         | 1.91%   |
| SCM Microsystems           | 7         | 1.67%   |
| Clay Logic                 | 6         | 1.44%   |
| Yubico.com                 | 5         | 1.2%    |
| Cherry                     | 4         | 0.96%   |
| Aladdin Knowledge Systems  | 4         | 0.96%   |
| Advanced Card Systems      | 4         | 0.96%   |
| Reiner SCT Kartensysteme   | 2         | 0.48%   |
| Realtek Semiconductor      | 2         | 0.48%   |
| Chicony Electronics        | 2         | 0.48%   |
| OmniKey                    | 1         | 0.24%   |
| Hewlett-Packard            | 1         | 0.24%   |
| Feitian Technologies       | 1         | 0.24%   |
| C3PO                       | 1         | 0.24%   |
| Athena Smartcard Solutions | 1         | 0.24%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 140       | 33.49%  |
| Broadcom BCM5880 Secure Applications Processor                               | 45        | 10.77%  |
| Broadcom 58200                                                               | 39        | 9.33%   |
| Broadcom 5880                                                                | 37        | 8.85%   |
| Lenovo Integrated Smart Card Reader                                          | 27        | 6.46%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 26        | 6.22%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 5.5%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 22        | 5.26%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 5         | 1.2%    |
| Yubico.com Yubikey 4 U2F+CCID                                                | 4         | 0.96%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 0.96%   |
| Aladdin Knowledge Systems Token JC                                           | 4         | 0.96%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 3         | 0.72%   |
| Clay Logic Nitrokey Start                                                    | 3         | 0.72%   |
| Clay Logic Nitrokey Pro                                                      | 3         | 0.72%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 0.72%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.48%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.48%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.48%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 0.48%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 2         | 0.48%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.48%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.48%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 0.48%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.24%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.24%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                  | 1         | 0.24%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.24%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.24%   |
| OmniKey CardMan 4321                                                         | 1         | 0.24%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.24%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.24%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.24%   |
| Feitian Technologies SCR301                                                  | 1         | 0.24%   |
| Cherry SmartTerminal XX1X                                                    | 1         | 0.24%   |
| Cherry Cherry GmbH CHERRY SECURE BOARD 1.0                                   | 1         | 0.24%   |
| C3PO LTC31v2                                                                 | 1         | 0.24%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 0.24%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5327      | 60.78%  |
| 1     | 2721      | 31.04%  |
| 2     | 566       | 6.46%   |
| 3     | 117       | 1.33%   |
| 4     | 20        | 0.23%   |
| 5     | 9         | 0.1%    |
| 6     | 3         | 0.03%   |
| 7     | 2         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1581      | 38.59%  |
| Fingerprint reader       | 908       | 22.16%  |
| Chipcard                 | 365       | 8.91%   |
| Net/wireless             | 333       | 8.13%   |
| Multimedia controller    | 287       | 7.01%   |
| Communication controller | 158       | 3.86%   |
| Unassigned class         | 95        | 2.32%   |
| Bluetooth                | 73        | 1.78%   |
| Camera                   | 64        | 1.56%   |
| Card reader              | 50        | 1.22%   |
| Sound                    | 47        | 1.15%   |
| Storage                  | 37        | 0.9%    |
| Net/ethernet             | 37        | 0.9%    |
| Network                  | 18        | 0.44%   |
| Modem                    | 11        | 0.27%   |
| Storage/raid             | 8         | 0.2%    |
| Storage/ide              | 7         | 0.17%   |
| Flash memory             | 5         | 0.12%   |
| Tv card                  | 4         | 0.1%    |
| Dvb card                 | 4         | 0.1%    |
| Firewire controller      | 3         | 0.07%   |
| Wireless                 | 1         | 0.02%   |
| Storage/ata              | 1         | 0.02%   |

