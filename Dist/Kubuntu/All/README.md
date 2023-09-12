Kubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Kubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kubuntu/Desktop/README.md) and [notebooks](/Dist/Kubuntu/Notebook/README.md).

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

Total: 5869

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [81a5f77f1c](https://linux-hardware.org/?probe=81a5f77f1c) | Sep 07, 2023 |
| Dell          | Latitude 7420               | Notebook    | [77df1805f6](https://linux-hardware.org/?probe=77df1805f6) | Sep 07, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [7ce5ebe4bc](https://linux-hardware.org/?probe=7ce5ebe4bc) | Sep 07, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [48cc912b75](https://linux-hardware.org/?probe=48cc912b75) | Sep 06, 2023 |
| Lenovo        | 3708 NOK                    | Desktop     | [153f0dfa9d](https://linux-hardware.org/?probe=153f0dfa9d) | Sep 06, 2023 |
| ASUSTek       | G551JM                      | Notebook    | [784e1f216e](https://linux-hardware.org/?probe=784e1f216e) | Sep 06, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [eb92b04384](https://linux-hardware.org/?probe=eb92b04384) | Sep 06, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [989134a7c5](https://linux-hardware.org/?probe=989134a7c5) | Sep 06, 2023 |
| Alienware     | 0H869M A00                  | Desktop     | [64132daa63](https://linux-hardware.org/?probe=64132daa63) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [cf9c65c6f4](https://linux-hardware.org/?probe=cf9c65c6f4) | Sep 06, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [d2ae9b900d](https://linux-hardware.org/?probe=d2ae9b900d) | Sep 06, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [f081f44bda](https://linux-hardware.org/?probe=f081f44bda) | Sep 05, 2023 |
| Dell          | Latitude 7490               | Notebook    | [2a945e76de](https://linux-hardware.org/?probe=2a945e76de) | Sep 05, 2023 |
| Samsung       | 950QED                      | Convertible | [e15539dd35](https://linux-hardware.org/?probe=e15539dd35) | Sep 05, 2023 |
| Dell          | Inspiron 3480               | Notebook    | [3d639d27ba](https://linux-hardware.org/?probe=3d639d27ba) | Sep 05, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [07429e910f](https://linux-hardware.org/?probe=07429e910f) | Sep 05, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [1cd7fc15b1](https://linux-hardware.org/?probe=1cd7fc15b1) | Sep 05, 2023 |
| AZW           | SER V01                     | Mini pc     | [b744dfb20a](https://linux-hardware.org/?probe=b744dfb20a) | Sep 05, 2023 |
| ASUSTek       | S400CA                      | Notebook    | [453335f199](https://linux-hardware.org/?probe=453335f199) | Sep 04, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [7944dc4ca2](https://linux-hardware.org/?probe=7944dc4ca2) | Sep 04, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [71da9ea288](https://linux-hardware.org/?probe=71da9ea288) | Sep 04, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [2dff249b45](https://linux-hardware.org/?probe=2dff249b45) | Sep 04, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [31cb6a887e](https://linux-hardware.org/?probe=31cb6a887e) | Sep 04, 2023 |
| Dell          | Latitude E6500              | Notebook    | [6199709334](https://linux-hardware.org/?probe=6199709334) | Sep 04, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [515a81a0d1](https://linux-hardware.org/?probe=515a81a0d1) | Sep 03, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [c8978cf811](https://linux-hardware.org/?probe=c8978cf811) | Sep 03, 2023 |
| HP            | Notebook                    | Notebook    | [9be8a6b0e7](https://linux-hardware.org/?probe=9be8a6b0e7) | Sep 03, 2023 |
| HP            | Notebook                    | Notebook    | [d038b7106e](https://linux-hardware.org/?probe=d038b7106e) | Sep 03, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [cdf37a1590](https://linux-hardware.org/?probe=cdf37a1590) | Sep 03, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [62ac121b13](https://linux-hardware.org/?probe=62ac121b13) | Sep 03, 2023 |
| Dell          | Latitude E6500              | Notebook    | [308d8d0f19](https://linux-hardware.org/?probe=308d8d0f19) | Sep 03, 2023 |
| Fujitsu Si... | LIFEBOOK E8410              | Notebook    | [31618d06c6](https://linux-hardware.org/?probe=31618d06c6) | Sep 02, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [85cc9860f3](https://linux-hardware.org/?probe=85cc9860f3) | Sep 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [2fc5b41456](https://linux-hardware.org/?probe=2fc5b41456) | Sep 02, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [1aeb1ffd17](https://linux-hardware.org/?probe=1aeb1ffd17) | Sep 02, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [9028ba6c0f](https://linux-hardware.org/?probe=9028ba6c0f) | Sep 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7dabe0d117](https://linux-hardware.org/?probe=7dabe0d117) | Sep 01, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [d646fdb00d](https://linux-hardware.org/?probe=d646fdb00d) | Sep 01, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [b132ff749e](https://linux-hardware.org/?probe=b132ff749e) | Sep 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [d80ee341d8](https://linux-hardware.org/?probe=d80ee341d8) | Sep 01, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [ac52854722](https://linux-hardware.org/?probe=ac52854722) | Aug 31, 2023 |
| Dell          | XPS 9315                    | Notebook    | [5676f0c210](https://linux-hardware.org/?probe=5676f0c210) | Aug 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [3384884acc](https://linux-hardware.org/?probe=3384884acc) | Aug 31, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [17e971c3fb](https://linux-hardware.org/?probe=17e971c3fb) | Aug 31, 2023 |
| Sony          | VPCEC390X                   | Notebook    | [ddad567e2a](https://linux-hardware.org/?probe=ddad567e2a) | Aug 31, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [d9a8673516](https://linux-hardware.org/?probe=d9a8673516) | Aug 31, 2023 |
| AZW           | MINI S                      | Desktop     | [fb828c24eb](https://linux-hardware.org/?probe=fb828c24eb) | Aug 31, 2023 |
| Avell High... | C62 MOB                     | Notebook    | [04e247a3d3](https://linux-hardware.org/?probe=04e247a3d3) | Aug 30, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [27e226b6d4](https://linux-hardware.org/?probe=27e226b6d4) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2906fc34f6](https://linux-hardware.org/?probe=2906fc34f6) | Aug 30, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [5a4e0650a2](https://linux-hardware.org/?probe=5a4e0650a2) | Aug 30, 2023 |
| Toshiba       | Satellite P850              | Notebook    | [a129c031fa](https://linux-hardware.org/?probe=a129c031fa) | Aug 29, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [a9d960e012](https://linux-hardware.org/?probe=a9d960e012) | Aug 29, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [ca4ddb2663](https://linux-hardware.org/?probe=ca4ddb2663) | Aug 29, 2023 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [a2f18f43e4](https://linux-hardware.org/?probe=a2f18f43e4) | Aug 29, 2023 |
| HP            | 212B                        | Desktop     | [80b2496334](https://linux-hardware.org/?probe=80b2496334) | Aug 29, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [a4bd03aafc](https://linux-hardware.org/?probe=a4bd03aafc) | Aug 29, 2023 |
| Fujitsu       | LIFEBOOK U9312              | Notebook    | [891b276812](https://linux-hardware.org/?probe=891b276812) | Aug 28, 2023 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [ae73127da5](https://linux-hardware.org/?probe=ae73127da5) | Aug 28, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [5b0183001d](https://linux-hardware.org/?probe=5b0183001d) | Aug 28, 2023 |
| Dell          | Vostro 3501                 | Notebook    | [0211379a67](https://linux-hardware.org/?probe=0211379a67) | Aug 27, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [19f07f081f](https://linux-hardware.org/?probe=19f07f081f) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [c437fa21b3](https://linux-hardware.org/?probe=c437fa21b3) | Aug 27, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [69a4a078cd](https://linux-hardware.org/?probe=69a4a078cd) | Aug 27, 2023 |
| HP            | 18E7                        | Desktop     | [0b94065a0f](https://linux-hardware.org/?probe=0b94065a0f) | Aug 27, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [fa48902a10](https://linux-hardware.org/?probe=fa48902a10) | Aug 27, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [cf2cba5c59](https://linux-hardware.org/?probe=cf2cba5c59) | Aug 26, 2023 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [4167149587](https://linux-hardware.org/?probe=4167149587) | Aug 26, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [efa1e38911](https://linux-hardware.org/?probe=efa1e38911) | Aug 26, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [1f47bfe737](https://linux-hardware.org/?probe=1f47bfe737) | Aug 26, 2023 |
| MSI           | 990FXA GAMING               | Desktop     | [813d9c9c10](https://linux-hardware.org/?probe=813d9c9c10) | Aug 26, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [65b6b29fc7](https://linux-hardware.org/?probe=65b6b29fc7) | Aug 26, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [5004de7897](https://linux-hardware.org/?probe=5004de7897) | Aug 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [e4200e4c9a](https://linux-hardware.org/?probe=e4200e4c9a) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [d0de544ecd](https://linux-hardware.org/?probe=d0de544ecd) | Aug 25, 2023 |
| HP            | ZBook 14 G2                 | Notebook    | [7fcd619af1](https://linux-hardware.org/?probe=7fcd619af1) | Aug 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3acc953bde](https://linux-hardware.org/?probe=3acc953bde) | Aug 24, 2023 |
| Lenovo        | IdeaPad Z580                | Notebook    | [b84eb0a6fa](https://linux-hardware.org/?probe=b84eb0a6fa) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ccdc0814a8](https://linux-hardware.org/?probe=ccdc0814a8) | Aug 24, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [bc15f84b8c](https://linux-hardware.org/?probe=bc15f84b8c) | Aug 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0161911081](https://linux-hardware.org/?probe=0161911081) | Aug 24, 2023 |
| Dell          | Precision 7780              | Notebook    | [a0627634fc](https://linux-hardware.org/?probe=a0627634fc) | Aug 23, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [7bd62bca50](https://linux-hardware.org/?probe=7bd62bca50) | Aug 23, 2023 |
| Intel         | H55                         | Desktop     | [8320e0c758](https://linux-hardware.org/?probe=8320e0c758) | Aug 22, 2023 |
| MSI           | GL65 9SE                    | Notebook    | [aa162e5634](https://linux-hardware.org/?probe=aa162e5634) | Aug 22, 2023 |
| Irbis         | NB123                       | Notebook    | [6bfbd824c3](https://linux-hardware.org/?probe=6bfbd824c3) | Aug 22, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [aee37b4a93](https://linux-hardware.org/?probe=aee37b4a93) | Aug 21, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [8c6f4a2e1c](https://linux-hardware.org/?probe=8c6f4a2e1c) | Aug 21, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [4d631eed0e](https://linux-hardware.org/?probe=4d631eed0e) | Aug 21, 2023 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [bb5a7dc0d8](https://linux-hardware.org/?probe=bb5a7dc0d8) | Aug 21, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [bb21bd2dbc](https://linux-hardware.org/?probe=bb21bd2dbc) | Aug 21, 2023 |
| Fujitsu       | D3602-A1 S26361-D3602-A1    | Desktop     | [8144c6d466](https://linux-hardware.org/?probe=8144c6d466) | Aug 21, 2023 |
| Dell          | Latitude E6520              | Notebook    | [923d01a34f](https://linux-hardware.org/?probe=923d01a34f) | Aug 21, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [7463f81c62](https://linux-hardware.org/?probe=7463f81c62) | Aug 20, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [c78c246642](https://linux-hardware.org/?probe=c78c246642) | Aug 20, 2023 |
| Schenker      | XMG PRO (E23)               | Notebook    | [9b1639077c](https://linux-hardware.org/?probe=9b1639077c) | Aug 20, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [3911bdd51d](https://linux-hardware.org/?probe=3911bdd51d) | Aug 20, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [1979db3345](https://linux-hardware.org/?probe=1979db3345) | Aug 20, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [9a7f33c81b](https://linux-hardware.org/?probe=9a7f33c81b) | Aug 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [df48f3ca66](https://linux-hardware.org/?probe=df48f3ca66) | Aug 19, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [3b3ae781c6](https://linux-hardware.org/?probe=3b3ae781c6) | Aug 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [ed75b0702f](https://linux-hardware.org/?probe=ed75b0702f) | Aug 19, 2023 |
| Toshiba       | Satellite P850              | Notebook    | [8d00e88e1c](https://linux-hardware.org/?probe=8d00e88e1c) | Aug 19, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [93530d7cb1](https://linux-hardware.org/?probe=93530d7cb1) | Aug 18, 2023 |
| Dell          | XPS 17 9730                 | Notebook    | [e9ddab2ebc](https://linux-hardware.org/?probe=e9ddab2ebc) | Aug 18, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [b5973b3c67](https://linux-hardware.org/?probe=b5973b3c67) | Aug 18, 2023 |
| MSI           | B250M MORTAR                | Desktop     | [fc97ccab18](https://linux-hardware.org/?probe=fc97ccab18) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | Desktop     | [1962f7a581](https://linux-hardware.org/?probe=1962f7a581) | Aug 17, 2023 |
| Intel         | D53427RKE G87971-402        | Desktop     | [433dcaffa6](https://linux-hardware.org/?probe=433dcaffa6) | Aug 17, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [a925a31ef1](https://linux-hardware.org/?probe=a925a31ef1) | Aug 17, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [ace741b68a](https://linux-hardware.org/?probe=ace741b68a) | Aug 17, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [2da4b77f8a](https://linux-hardware.org/?probe=2da4b77f8a) | Aug 17, 2023 |
| Lenovo        | ThinkBook 14s Yoga G3 IR... | Convertible | [74da3f5482](https://linux-hardware.org/?probe=74da3f5482) | Aug 16, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [ef53482168](https://linux-hardware.org/?probe=ef53482168) | Aug 16, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [aaec4c4fe1](https://linux-hardware.org/?probe=aaec4c4fe1) | Aug 16, 2023 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | Notebook    | [a94c8dc31f](https://linux-hardware.org/?probe=a94c8dc31f) | Aug 16, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [e9f564475b](https://linux-hardware.org/?probe=e9f564475b) | Aug 16, 2023 |
| HP            | EliteBook x360 830 G8 No... | Convertible | [8e409a97d7](https://linux-hardware.org/?probe=8e409a97d7) | Aug 15, 2023 |
| AZW           | SER V01                     | Mini pc     | [f0d325d7d3](https://linux-hardware.org/?probe=f0d325d7d3) | Aug 15, 2023 |
| AZW           | SER V01                     | Mini pc     | [a395628119](https://linux-hardware.org/?probe=a395628119) | Aug 15, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [e338ac8876](https://linux-hardware.org/?probe=e338ac8876) | Aug 14, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [37086c4564](https://linux-hardware.org/?probe=37086c4564) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ed6e0727b2](https://linux-hardware.org/?probe=ed6e0727b2) | Aug 14, 2023 |
| AMI           | INTEL                       | Convertible | [21596eaf06](https://linux-hardware.org/?probe=21596eaf06) | Aug 14, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [41b9b0bfc9](https://linux-hardware.org/?probe=41b9b0bfc9) | Aug 14, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [8643d609f2](https://linux-hardware.org/?probe=8643d609f2) | Aug 14, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [29aa72820d](https://linux-hardware.org/?probe=29aa72820d) | Aug 14, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [83dd0f7fe7](https://linux-hardware.org/?probe=83dd0f7fe7) | Aug 14, 2023 |
| LG Electro... | 17Z90N-V.AA72A8             | Notebook    | [28e815418c](https://linux-hardware.org/?probe=28e815418c) | Aug 13, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [7ad086cf8b](https://linux-hardware.org/?probe=7ad086cf8b) | Aug 13, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [e2fe66aca4](https://linux-hardware.org/?probe=e2fe66aca4) | Aug 13, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [7dd490a028](https://linux-hardware.org/?probe=7dd490a028) | Aug 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [307eb30c27](https://linux-hardware.org/?probe=307eb30c27) | Aug 13, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [0c8514df53](https://linux-hardware.org/?probe=0c8514df53) | Aug 13, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [760a5d6077](https://linux-hardware.org/?probe=760a5d6077) | Aug 13, 2023 |
| Dell          | 0GNVHC A00                  | Desktop     | [27e3be4942](https://linux-hardware.org/?probe=27e3be4942) | Aug 12, 2023 |
| ASUSTek       | CM1630                      | Desktop     | [dfd52e2852](https://linux-hardware.org/?probe=dfd52e2852) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b4b9fa2d17](https://linux-hardware.org/?probe=b4b9fa2d17) | Aug 12, 2023 |
| ASUSTek       | CM1630                      | Desktop     | [d8f56bcdaf](https://linux-hardware.org/?probe=d8f56bcdaf) | Aug 12, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [97c78c17bd](https://linux-hardware.org/?probe=97c78c17bd) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [181db8cf87](https://linux-hardware.org/?probe=181db8cf87) | Aug 11, 2023 |
| Medion        | P651x series                | Notebook    | [46505da47d](https://linux-hardware.org/?probe=46505da47d) | Aug 11, 2023 |
| AZW           | SER V01                     | Mini pc     | [542d8da36c](https://linux-hardware.org/?probe=542d8da36c) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [ba03034ac5](https://linux-hardware.org/?probe=ba03034ac5) | Aug 10, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [be6c815f39](https://linux-hardware.org/?probe=be6c815f39) | Aug 10, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [0dee84c129](https://linux-hardware.org/?probe=0dee84c129) | Aug 10, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [f28a198267](https://linux-hardware.org/?probe=f28a198267) | Aug 10, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [767792bf33](https://linux-hardware.org/?probe=767792bf33) | Aug 09, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [d255d00dc8](https://linux-hardware.org/?probe=d255d00dc8) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [352fd5fea3](https://linux-hardware.org/?probe=352fd5fea3) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [76bbb6695d](https://linux-hardware.org/?probe=76bbb6695d) | Aug 09, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [d97ae334a3](https://linux-hardware.org/?probe=d97ae334a3) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f28e4b71d6](https://linux-hardware.org/?probe=f28e4b71d6) | Aug 09, 2023 |
| Google        | Dragonair                   | Notebook    | [45d7954a65](https://linux-hardware.org/?probe=45d7954a65) | Aug 08, 2023 |
| Google        | Dragonair                   | Notebook    | [d78af70cf3](https://linux-hardware.org/?probe=d78af70cf3) | Aug 08, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [58d7c4be4c](https://linux-hardware.org/?probe=58d7c4be4c) | Aug 08, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [1d117f6031](https://linux-hardware.org/?probe=1d117f6031) | Aug 07, 2023 |
| Lenovo        | ThinkPad W510 4391EC4       | Notebook    | [5e9baa223d](https://linux-hardware.org/?probe=5e9baa223d) | Aug 07, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [e03fdd9f60](https://linux-hardware.org/?probe=e03fdd9f60) | Aug 07, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [6d2ab6eef6](https://linux-hardware.org/?probe=6d2ab6eef6) | Aug 07, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [068b8c5a6f](https://linux-hardware.org/?probe=068b8c5a6f) | Aug 07, 2023 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [a71dc0067b](https://linux-hardware.org/?probe=a71dc0067b) | Aug 07, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [ebe7ed3f69](https://linux-hardware.org/?probe=ebe7ed3f69) | Aug 07, 2023 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [df59aff876](https://linux-hardware.org/?probe=df59aff876) | Aug 07, 2023 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [8c8e1cef1c](https://linux-hardware.org/?probe=8c8e1cef1c) | Aug 06, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [3d156d18e6](https://linux-hardware.org/?probe=3d156d18e6) | Aug 06, 2023 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [a0a289f4ee](https://linux-hardware.org/?probe=a0a289f4ee) | Aug 06, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [ced0647d42](https://linux-hardware.org/?probe=ced0647d42) | Aug 06, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [cb3d78955a](https://linux-hardware.org/?probe=cb3d78955a) | Aug 05, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [8c56195933](https://linux-hardware.org/?probe=8c56195933) | Aug 05, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [ec1bd43523](https://linux-hardware.org/?probe=ec1bd43523) | Aug 05, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [00b2c0458a](https://linux-hardware.org/?probe=00b2c0458a) | Aug 05, 2023 |
| GPD           | G1621-02                    | Notebook    | [7e37b7bbee](https://linux-hardware.org/?probe=7e37b7bbee) | Aug 04, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [838f543301](https://linux-hardware.org/?probe=838f543301) | Aug 04, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [1b9b10c938](https://linux-hardware.org/?probe=1b9b10c938) | Aug 04, 2023 |
| HP            | 2AF7                        | Desktop     | [655c896815](https://linux-hardware.org/?probe=655c896815) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L50000MC    | Notebook    | [341698801e](https://linux-hardware.org/?probe=341698801e) | Aug 04, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [848ed7bc51](https://linux-hardware.org/?probe=848ed7bc51) | Aug 04, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [6bef2ead01](https://linux-hardware.org/?probe=6bef2ead01) | Aug 04, 2023 |
| Dell          | Precision 7670              | Notebook    | [09797bd60c](https://linux-hardware.org/?probe=09797bd60c) | Aug 04, 2023 |
| HP            | 158A                        | Desktop     | [ae8ecc3ee7](https://linux-hardware.org/?probe=ae8ecc3ee7) | Aug 04, 2023 |
| HP            | 3031h                       | Desktop     | [95b5c80f67](https://linux-hardware.org/?probe=95b5c80f67) | Aug 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [178bed5f56](https://linux-hardware.org/?probe=178bed5f56) | Aug 03, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [de1addc70b](https://linux-hardware.org/?probe=de1addc70b) | Aug 03, 2023 |
| Dell          | Latitude 5530               | Notebook    | [dd85033508](https://linux-hardware.org/?probe=dd85033508) | Aug 03, 2023 |
| HPE           | ML10Gen9                    | Server      | [f5115c8a74](https://linux-hardware.org/?probe=f5115c8a74) | Aug 03, 2023 |
| HP            | 3031h                       | Desktop     | [04c8ac1eee](https://linux-hardware.org/?probe=04c8ac1eee) | Aug 03, 2023 |
| AZW           | SER V01                     | Mini pc     | [5e552472e5](https://linux-hardware.org/?probe=5e552472e5) | Aug 03, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [4d21c35777](https://linux-hardware.org/?probe=4d21c35777) | Aug 03, 2023 |
| System76      | Galago Pro                  | Notebook    | [2677fc9a99](https://linux-hardware.org/?probe=2677fc9a99) | Aug 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [3bb1942723](https://linux-hardware.org/?probe=3bb1942723) | Aug 02, 2023 |
| Alienware     | 14                          | Notebook    | [90512d5e80](https://linux-hardware.org/?probe=90512d5e80) | Aug 02, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [c0de5c7032](https://linux-hardware.org/?probe=c0de5c7032) | Aug 02, 2023 |
| HP            | 158A                        | Desktop     | [bac95226bd](https://linux-hardware.org/?probe=bac95226bd) | Aug 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7748df9ae9](https://linux-hardware.org/?probe=7748df9ae9) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [25dd387c2c](https://linux-hardware.org/?probe=25dd387c2c) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [7f5c70c059](https://linux-hardware.org/?probe=7f5c70c059) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [6519784d61](https://linux-hardware.org/?probe=6519784d61) | Aug 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [48c7912f46](https://linux-hardware.org/?probe=48c7912f46) | Aug 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cb493cc8c8](https://linux-hardware.org/?probe=cb493cc8c8) | Aug 01, 2023 |
| MSI           | PRO Z690-A                  | Desktop     | [19f4cb0c69](https://linux-hardware.org/?probe=19f4cb0c69) | Jul 31, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [be7baf7741](https://linux-hardware.org/?probe=be7baf7741) | Jul 31, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [3b0862f434](https://linux-hardware.org/?probe=3b0862f434) | Jul 31, 2023 |
| Dell          | Precision 3571              | Notebook    | [83a85ddae5](https://linux-hardware.org/?probe=83a85ddae5) | Jul 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [9371aa866b](https://linux-hardware.org/?probe=9371aa866b) | Jul 30, 2023 |
| Google        | Zako                        | Desktop     | [66946b6b49](https://linux-hardware.org/?probe=66946b6b49) | Jul 30, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [65a741810c](https://linux-hardware.org/?probe=65a741810c) | Jul 30, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [e5ad011556](https://linux-hardware.org/?probe=e5ad011556) | Jul 30, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [e7befe5a64](https://linux-hardware.org/?probe=e7befe5a64) | Jul 29, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [0ed7dfdf32](https://linux-hardware.org/?probe=0ed7dfdf32) | Jul 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [22b080cd6b](https://linux-hardware.org/?probe=22b080cd6b) | Jul 29, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [8102a251ad](https://linux-hardware.org/?probe=8102a251ad) | Jul 29, 2023 |
| MSI           | X99S SLI PLUS               | Desktop     | [edf7fd3a91](https://linux-hardware.org/?probe=edf7fd3a91) | Jul 28, 2023 |
| Gigabyte      | EP45T-UD3LR                 | Desktop     | [c2928283bd](https://linux-hardware.org/?probe=c2928283bd) | Jul 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [6e4e0bebde](https://linux-hardware.org/?probe=6e4e0bebde) | Jul 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [63c601695f](https://linux-hardware.org/?probe=63c601695f) | Jul 28, 2023 |
| MSI           | PRO Z690-A                  | Desktop     | [f1a5d69727](https://linux-hardware.org/?probe=f1a5d69727) | Jul 28, 2023 |
| Acer          | Aspire 5560                 | Notebook    | [86868232f0](https://linux-hardware.org/?probe=86868232f0) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4a34b9da9b](https://linux-hardware.org/?probe=4a34b9da9b) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a26bbadd26](https://linux-hardware.org/?probe=a26bbadd26) | Jul 27, 2023 |
| Supermicro    | C7H61                       | Desktop     | [57c9a4eeff](https://linux-hardware.org/?probe=57c9a4eeff) | Jul 27, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [810ff8bbd6](https://linux-hardware.org/?probe=810ff8bbd6) | Jul 26, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [3548050f99](https://linux-hardware.org/?probe=3548050f99) | Jul 26, 2023 |
| Lenovo        | ThinkPad E580 20KS003LLM    | Notebook    | [9bc92a8ef2](https://linux-hardware.org/?probe=9bc92a8ef2) | Jul 26, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [7b7287762f](https://linux-hardware.org/?probe=7b7287762f) | Jul 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7c5e9b6bc6](https://linux-hardware.org/?probe=7c5e9b6bc6) | Jul 26, 2023 |
| HP            | G60                         | Notebook    | [4d64158286](https://linux-hardware.org/?probe=4d64158286) | Jul 26, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3b05aaff82](https://linux-hardware.org/?probe=3b05aaff82) | Jul 25, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [914560761d](https://linux-hardware.org/?probe=914560761d) | Jul 25, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [834378c125](https://linux-hardware.org/?probe=834378c125) | Jul 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4a1a31cb65](https://linux-hardware.org/?probe=4a1a31cb65) | Jul 25, 2023 |
| Acer          | Aspire X3990                | Desktop     | [7b6b27241f](https://linux-hardware.org/?probe=7b6b27241f) | Jul 24, 2023 |
| AZW           | SER V01                     | Mini pc     | [440a88b8bf](https://linux-hardware.org/?probe=440a88b8bf) | Jul 24, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [273533f7f8](https://linux-hardware.org/?probe=273533f7f8) | Jul 24, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [26f325a346](https://linux-hardware.org/?probe=26f325a346) | Jul 23, 2023 |
| Gigabyte      | P67A-UD3-B3                 | Desktop     | [26e7657871](https://linux-hardware.org/?probe=26e7657871) | Jul 23, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [881853b4dc](https://linux-hardware.org/?probe=881853b4dc) | Jul 23, 2023 |
| Dell          | 0757V0 A00                  | Desktop     | [e367a3740a](https://linux-hardware.org/?probe=e367a3740a) | Jul 23, 2023 |
| MSI           | Z87 MPOWER                  | Desktop     | [dcbda0f556](https://linux-hardware.org/?probe=dcbda0f556) | Jul 23, 2023 |
| HP            | G62                         | Notebook    | [003a68db8b](https://linux-hardware.org/?probe=003a68db8b) | Jul 23, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [751e776113](https://linux-hardware.org/?probe=751e776113) | Jul 23, 2023 |
| HP            | Presario CQ62               | Notebook    | [b736890f88](https://linux-hardware.org/?probe=b736890f88) | Jul 23, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [25fd4c6993](https://linux-hardware.org/?probe=25fd4c6993) | Jul 22, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [e07c3205da](https://linux-hardware.org/?probe=e07c3205da) | Jul 22, 2023 |
| Medion        | H110H4-EM2                  | Desktop     | [443b61cb44](https://linux-hardware.org/?probe=443b61cb44) | Jul 22, 2023 |
| Acer          | Predator PT516-52s          | Notebook    | [957a1037ee](https://linux-hardware.org/?probe=957a1037ee) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [e948334857](https://linux-hardware.org/?probe=e948334857) | Jul 22, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [1a39665e1c](https://linux-hardware.org/?probe=1a39665e1c) | Jul 22, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [38a01d299e](https://linux-hardware.org/?probe=38a01d299e) | Jul 21, 2023 |
| Intel         | DQ57TM AAE70931-402         | Desktop     | [01621f8578](https://linux-hardware.org/?probe=01621f8578) | Jul 21, 2023 |
| Dell          | Latitude 5289               | Convertible | [eeb009e8f5](https://linux-hardware.org/?probe=eeb009e8f5) | Jul 21, 2023 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [3e6dc436dd](https://linux-hardware.org/?probe=3e6dc436dd) | Jul 21, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [620c7f4aec](https://linux-hardware.org/?probe=620c7f4aec) | Jul 21, 2023 |
| Acer          | ConceptD CN715-71           | Notebook    | [ae4de8c5b2](https://linux-hardware.org/?probe=ae4de8c5b2) | Jul 21, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [df9e2bd667](https://linux-hardware.org/?probe=df9e2bd667) | Jul 20, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [4f438fcc8b](https://linux-hardware.org/?probe=4f438fcc8b) | Jul 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c5028381e5](https://linux-hardware.org/?probe=c5028381e5) | Jul 20, 2023 |
| HP            | ENVY Notebook               | Notebook    | [0055da01e2](https://linux-hardware.org/?probe=0055da01e2) | Jul 19, 2023 |
| Dell          | Latitude 5511               | Notebook    | [9dcb3c30b2](https://linux-hardware.org/?probe=9dcb3c30b2) | Jul 19, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [26695664a7](https://linux-hardware.org/?probe=26695664a7) | Jul 18, 2023 |
| HP            | 83E9                        | Desktop     | [35c7f631ac](https://linux-hardware.org/?probe=35c7f631ac) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [fd59d670e2](https://linux-hardware.org/?probe=fd59d670e2) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6a903d2c2f](https://linux-hardware.org/?probe=6a903d2c2f) | Jul 18, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [b29b313957](https://linux-hardware.org/?probe=b29b313957) | Jul 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [d4a4fec7c0](https://linux-hardware.org/?probe=d4a4fec7c0) | Jul 17, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [392b85a82b](https://linux-hardware.org/?probe=392b85a82b) | Jul 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [15ef7f9ce4](https://linux-hardware.org/?probe=15ef7f9ce4) | Jul 16, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [164e93a53b](https://linux-hardware.org/?probe=164e93a53b) | Jul 16, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [8fb3c405c0](https://linux-hardware.org/?probe=8fb3c405c0) | Jul 16, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [0b447416c6](https://linux-hardware.org/?probe=0b447416c6) | Jul 15, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [ded2ed05d8](https://linux-hardware.org/?probe=ded2ed05d8) | Jul 15, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d64ea4b9cd](https://linux-hardware.org/?probe=d64ea4b9cd) | Jul 15, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [bf8b4001a4](https://linux-hardware.org/?probe=bf8b4001a4) | Jul 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [3caf271d7c](https://linux-hardware.org/?probe=3caf271d7c) | Jul 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [689d391a1d](https://linux-hardware.org/?probe=689d391a1d) | Jul 15, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [0008f72dbf](https://linux-hardware.org/?probe=0008f72dbf) | Jul 15, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [745fa6a1b4](https://linux-hardware.org/?probe=745fa6a1b4) | Jul 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c453f1df6b](https://linux-hardware.org/?probe=c453f1df6b) | Jul 14, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [8ea38146c1](https://linux-hardware.org/?probe=8ea38146c1) | Jul 14, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [87a3354fc2](https://linux-hardware.org/?probe=87a3354fc2) | Jul 13, 2023 |
| HP            | Pavilion 15                 | Notebook    | [81ca680697](https://linux-hardware.org/?probe=81ca680697) | Jul 13, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [8e53be597f](https://linux-hardware.org/?probe=8e53be597f) | Jul 13, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [dcb1a242c5](https://linux-hardware.org/?probe=dcb1a242c5) | Jul 13, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [b5374c8055](https://linux-hardware.org/?probe=b5374c8055) | Jul 12, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [93b2067918](https://linux-hardware.org/?probe=93b2067918) | Jul 11, 2023 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [6f62e1063c](https://linux-hardware.org/?probe=6f62e1063c) | Jul 11, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [0d59e226ae](https://linux-hardware.org/?probe=0d59e226ae) | Jul 10, 2023 |
| Lenovo        | ThinkPad T460 20FMS43Q00    | Notebook    | [3f0c520d07](https://linux-hardware.org/?probe=3f0c520d07) | Jul 10, 2023 |
| Dell          | G3 3779                     | Notebook    | [2cdd1427c9](https://linux-hardware.org/?probe=2cdd1427c9) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [975668f4f1](https://linux-hardware.org/?probe=975668f4f1) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [7bc8c956fd](https://linux-hardware.org/?probe=7bc8c956fd) | Jul 10, 2023 |
| Dell          | Latitude E5420              | Notebook    | [6dba8e523b](https://linux-hardware.org/?probe=6dba8e523b) | Jul 09, 2023 |
| Lenovo        | B560 43308UG                | Notebook    | [20ea6219d4](https://linux-hardware.org/?probe=20ea6219d4) | Jul 09, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [41ede144c1](https://linux-hardware.org/?probe=41ede144c1) | Jul 09, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [17c907528f](https://linux-hardware.org/?probe=17c907528f) | Jul 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [95b195418f](https://linux-hardware.org/?probe=95b195418f) | Jul 09, 2023 |
| HP            | Notebook                    | Notebook    | [40226d935a](https://linux-hardware.org/?probe=40226d935a) | Jul 09, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [9400bf75de](https://linux-hardware.org/?probe=9400bf75de) | Jul 09, 2023 |
| HP            | 2B3E                        | All in one  | [9ec58b6284](https://linux-hardware.org/?probe=9ec58b6284) | Jul 09, 2023 |
| Acer          | Predator G3-572             | Notebook    | [fe7753845c](https://linux-hardware.org/?probe=fe7753845c) | Jul 09, 2023 |
| MSI           | B360M MORTAR TITANIUM       | Desktop     | [31b2aa5991](https://linux-hardware.org/?probe=31b2aa5991) | Jul 08, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [978a7ef06f](https://linux-hardware.org/?probe=978a7ef06f) | Jul 08, 2023 |
| Dell          | G3 3779                     | Notebook    | [9274552475](https://linux-hardware.org/?probe=9274552475) | Jul 08, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [7c39787112](https://linux-hardware.org/?probe=7c39787112) | Jul 08, 2023 |
| Pegatron      | 2AC3                        | Desktop     | [a2981d590e](https://linux-hardware.org/?probe=a2981d590e) | Jul 08, 2023 |
| AWOW          | AR40S                       | Stick pc    | [35b286ba6b](https://linux-hardware.org/?probe=35b286ba6b) | Jul 08, 2023 |
| AWOW          | AR40S                       | Stick pc    | [44eaa3f5c1](https://linux-hardware.org/?probe=44eaa3f5c1) | Jul 08, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [2f16685519](https://linux-hardware.org/?probe=2f16685519) | Jul 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [46132f9b9c](https://linux-hardware.org/?probe=46132f9b9c) | Jul 07, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [c0b828ddc4](https://linux-hardware.org/?probe=c0b828ddc4) | Jul 07, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [43cb92095e](https://linux-hardware.org/?probe=43cb92095e) | Jul 07, 2023 |
| Toshiba       | Satellite L745              | Notebook    | [cda3474ee7](https://linux-hardware.org/?probe=cda3474ee7) | Jul 07, 2023 |
| HP            | 240 G7 Notebook PC          | Notebook    | [e7d87f5a64](https://linux-hardware.org/?probe=e7d87f5a64) | Jul 07, 2023 |
| AZW           | SER V01                     | Mini pc     | [49552e2240](https://linux-hardware.org/?probe=49552e2240) | Jul 07, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [e5d4d7b4a7](https://linux-hardware.org/?probe=e5d4d7b4a7) | Jul 06, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [e566cda2af](https://linux-hardware.org/?probe=e566cda2af) | Jul 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | Notebook    | [397adc6b70](https://linux-hardware.org/?probe=397adc6b70) | Jul 06, 2023 |
| Dell          | Latitude E6530              | Notebook    | [16581ade55](https://linux-hardware.org/?probe=16581ade55) | Jul 06, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [b1f7c9aea2](https://linux-hardware.org/?probe=b1f7c9aea2) | Jul 06, 2023 |
| Lenovo        | ThinkPad T550 20CK000GCA    | Notebook    | [889e120cd5](https://linux-hardware.org/?probe=889e120cd5) | Jul 06, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [5800dc6fbf](https://linux-hardware.org/?probe=5800dc6fbf) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [335f69285d](https://linux-hardware.org/?probe=335f69285d) | Jul 05, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [6b250aabab](https://linux-hardware.org/?probe=6b250aabab) | Jul 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [d55667dbf0](https://linux-hardware.org/?probe=d55667dbf0) | Jul 05, 2023 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [46bfb7c0ff](https://linux-hardware.org/?probe=46bfb7c0ff) | Jul 05, 2023 |
| Gigabyte      | Z87-D3HP-CF                 | Desktop     | [7502eb638e](https://linux-hardware.org/?probe=7502eb638e) | Jul 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [673c5bfa9a](https://linux-hardware.org/?probe=673c5bfa9a) | Jul 04, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [61c278235a](https://linux-hardware.org/?probe=61c278235a) | Jul 03, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [8805bd2666](https://linux-hardware.org/?probe=8805bd2666) | Jul 03, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [48f79dc803](https://linux-hardware.org/?probe=48f79dc803) | Jul 03, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [9d47ca40b8](https://linux-hardware.org/?probe=9d47ca40b8) | Jul 03, 2023 |
| Dell          | Latitude 7530               | Notebook    | [0d03a052d8](https://linux-hardware.org/?probe=0d03a052d8) | Jul 03, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [947d2ff164](https://linux-hardware.org/?probe=947d2ff164) | Jul 03, 2023 |
| Notebook      | PC5x_7xHP_HR_HS             | Notebook    | [e76be78ba9](https://linux-hardware.org/?probe=e76be78ba9) | Jul 02, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b5a7ef8997](https://linux-hardware.org/?probe=b5a7ef8997) | Jul 02, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [22ca0e18f4](https://linux-hardware.org/?probe=22ca0e18f4) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [07c8a86c16](https://linux-hardware.org/?probe=07c8a86c16) | Jul 02, 2023 |
| Gateway       | IPISB-VR                    | Desktop     | [73ab7736ca](https://linux-hardware.org/?probe=73ab7736ca) | Jul 02, 2023 |
| Dell          | G3 3779                     | Notebook    | [bcae1c7195](https://linux-hardware.org/?probe=bcae1c7195) | Jul 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [1c976fee39](https://linux-hardware.org/?probe=1c976fee39) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [51d5b7d342](https://linux-hardware.org/?probe=51d5b7d342) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [0571943e1f](https://linux-hardware.org/?probe=0571943e1f) | Jul 01, 2023 |
| ASUSTek       | Strix GL704GW_GL704GW       | Notebook    | [cb42a3f59d](https://linux-hardware.org/?probe=cb42a3f59d) | Jul 01, 2023 |
| Fujitsu       | LIFEBOOK U757               | Notebook    | [f7bac40ab1](https://linux-hardware.org/?probe=f7bac40ab1) | Jul 01, 2023 |
| Gigabyte      | B85-HD3                     | Desktop     | [ed2ea8b876](https://linux-hardware.org/?probe=ed2ea8b876) | Jul 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [9beb3b7196](https://linux-hardware.org/?probe=9beb3b7196) | Jul 01, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7e7099c099](https://linux-hardware.org/?probe=7e7099c099) | Jul 01, 2023 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [f953c21e8e](https://linux-hardware.org/?probe=f953c21e8e) | Jul 01, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [cb6f37ea2b](https://linux-hardware.org/?probe=cb6f37ea2b) | Jul 01, 2023 |
| Dell          | G3 3779                     | Notebook    | [a6c5553133](https://linux-hardware.org/?probe=a6c5553133) | Jun 30, 2023 |
| Dell          | Latitude E5450              | Notebook    | [e0826ab83a](https://linux-hardware.org/?probe=e0826ab83a) | Jun 30, 2023 |
| Schenker      | XMG PRO (E23)               | Notebook    | [c70da63bd9](https://linux-hardware.org/?probe=c70da63bd9) | Jun 30, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [581282a150](https://linux-hardware.org/?probe=581282a150) | Jun 29, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [171e61b165](https://linux-hardware.org/?probe=171e61b165) | Jun 29, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [b52c0ac96a](https://linux-hardware.org/?probe=b52c0ac96a) | Jun 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [bbd13c14eb](https://linux-hardware.org/?probe=bbd13c14eb) | Jun 29, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [791bfd25bf](https://linux-hardware.org/?probe=791bfd25bf) | Jun 29, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [802b3686d4](https://linux-hardware.org/?probe=802b3686d4) | Jun 28, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0081fa215e](https://linux-hardware.org/?probe=0081fa215e) | Jun 28, 2023 |
| Huanan        | Unknown                     | Desktop     | [397d33202e](https://linux-hardware.org/?probe=397d33202e) | Jun 28, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [7dd7d8e8ea](https://linux-hardware.org/?probe=7dd7d8e8ea) | Jun 28, 2023 |
| MSI           | H81M-P32                    | Desktop     | [c0c2f3ba48](https://linux-hardware.org/?probe=c0c2f3ba48) | Jun 28, 2023 |
| MSI           | H81M-P32                    | Desktop     | [75cbcde6b8](https://linux-hardware.org/?probe=75cbcde6b8) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [9619e6fb09](https://linux-hardware.org/?probe=9619e6fb09) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [abf9b9909f](https://linux-hardware.org/?probe=abf9b9909f) | Jun 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [1726bb80ec](https://linux-hardware.org/?probe=1726bb80ec) | Jun 27, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [7a5a27ddd7](https://linux-hardware.org/?probe=7a5a27ddd7) | Jun 27, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [42e304c777](https://linux-hardware.org/?probe=42e304c777) | Jun 26, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [77d2d3d01b](https://linux-hardware.org/?probe=77d2d3d01b) | Jun 26, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [16c312b7be](https://linux-hardware.org/?probe=16c312b7be) | Jun 26, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [e5c848cc49](https://linux-hardware.org/?probe=e5c848cc49) | Jun 25, 2023 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [bd98bbb8c0](https://linux-hardware.org/?probe=bd98bbb8c0) | Jun 25, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [589dd91af9](https://linux-hardware.org/?probe=589dd91af9) | Jun 25, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [aab1616d0e](https://linux-hardware.org/?probe=aab1616d0e) | Jun 25, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [1c4e016f20](https://linux-hardware.org/?probe=1c4e016f20) | Jun 25, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [f043aedf3c](https://linux-hardware.org/?probe=f043aedf3c) | Jun 24, 2023 |
| ASUSTek       | G551JM                      | Notebook    | [04f17cc1d0](https://linux-hardware.org/?probe=04f17cc1d0) | Jun 24, 2023 |
| Google        | Kohaku                      | Notebook    | [f9c3a3efb6](https://linux-hardware.org/?probe=f9c3a3efb6) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [852dad5b6a](https://linux-hardware.org/?probe=852dad5b6a) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [bf18f8c7dc](https://linux-hardware.org/?probe=bf18f8c7dc) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [ed127d8c21](https://linux-hardware.org/?probe=ed127d8c21) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [e4f7f39784](https://linux-hardware.org/?probe=e4f7f39784) | Jun 23, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [e5efed1ac5](https://linux-hardware.org/?probe=e5efed1ac5) | Jun 23, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [aa50925a16](https://linux-hardware.org/?probe=aa50925a16) | Jun 23, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [f224dfda17](https://linux-hardware.org/?probe=f224dfda17) | Jun 22, 2023 |
| HP            | Pavilion Laptop 14-ce2xx... | Notebook    | [419687b31f](https://linux-hardware.org/?probe=419687b31f) | Jun 22, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [dda587b759](https://linux-hardware.org/?probe=dda587b759) | Jun 22, 2023 |
| Dell          | G3 3590                     | Notebook    | [14ab83043b](https://linux-hardware.org/?probe=14ab83043b) | Jun 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [014c851c43](https://linux-hardware.org/?probe=014c851c43) | Jun 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | Notebook    | [c5f46a6955](https://linux-hardware.org/?probe=c5f46a6955) | Jun 21, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [3dffeb35fa](https://linux-hardware.org/?probe=3dffeb35fa) | Jun 20, 2023 |
| HP            | Notebook                    | Notebook    | [db641e216c](https://linux-hardware.org/?probe=db641e216c) | Jun 20, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [29e7fc8e13](https://linux-hardware.org/?probe=29e7fc8e13) | Jun 20, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [233b6c3412](https://linux-hardware.org/?probe=233b6c3412) | Jun 20, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [fa33088329](https://linux-hardware.org/?probe=fa33088329) | Jun 20, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [37292d4c84](https://linux-hardware.org/?probe=37292d4c84) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [7d00ddf4fc](https://linux-hardware.org/?probe=7d00ddf4fc) | Jun 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [bfa769b311](https://linux-hardware.org/?probe=bfa769b311) | Jun 20, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [7cb19a32ac](https://linux-hardware.org/?probe=7cb19a32ac) | Jun 20, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | Notebook    | [9e06717237](https://linux-hardware.org/?probe=9e06717237) | Jun 19, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [5daecd88f5](https://linux-hardware.org/?probe=5daecd88f5) | Jun 19, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [260297ab72](https://linux-hardware.org/?probe=260297ab72) | Jun 19, 2023 |
| XFX           | MI-9300-7AS9                | Desktop     | [e2c3a51177](https://linux-hardware.org/?probe=e2c3a51177) | Jun 18, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [ac41230354](https://linux-hardware.org/?probe=ac41230354) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [ce819ae3d3](https://linux-hardware.org/?probe=ce819ae3d3) | Jun 18, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [83d17fd3bd](https://linux-hardware.org/?probe=83d17fd3bd) | Jun 17, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [739c466bf0](https://linux-hardware.org/?probe=739c466bf0) | Jun 17, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [587c48c954](https://linux-hardware.org/?probe=587c48c954) | Jun 17, 2023 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [945376fe33](https://linux-hardware.org/?probe=945376fe33) | Jun 17, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [75eeeb7917](https://linux-hardware.org/?probe=75eeeb7917) | Jun 16, 2023 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [6ecfbb88a0](https://linux-hardware.org/?probe=6ecfbb88a0) | Jun 16, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [e2e55f5267](https://linux-hardware.org/?probe=e2e55f5267) | Jun 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a1c36c44b1](https://linux-hardware.org/?probe=a1c36c44b1) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [8d88084588](https://linux-hardware.org/?probe=8d88084588) | Jun 15, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [b8d24f1cc8](https://linux-hardware.org/?probe=b8d24f1cc8) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [e0a00a71de](https://linux-hardware.org/?probe=e0a00a71de) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [76433ab03f](https://linux-hardware.org/?probe=76433ab03f) | Jun 15, 2023 |
| HP            | 86F0 11000                  | All in one  | [45026f50ef](https://linux-hardware.org/?probe=45026f50ef) | Jun 15, 2023 |
| HP            | 86F0 11000                  | All in one  | [f074cca59a](https://linux-hardware.org/?probe=f074cca59a) | Jun 15, 2023 |
| Dell          | Latitude 3310               | Notebook    | [40aa328d98](https://linux-hardware.org/?probe=40aa328d98) | Jun 15, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [39d273ec86](https://linux-hardware.org/?probe=39d273ec86) | Jun 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [f7049b2256](https://linux-hardware.org/?probe=f7049b2256) | Jun 15, 2023 |
| Proline       | V1165C4                     | Notebook    | [89f6135da3](https://linux-hardware.org/?probe=89f6135da3) | Jun 14, 2023 |
| Dell          | Latitude E6420              | Notebook    | [f05e0e10e5](https://linux-hardware.org/?probe=f05e0e10e5) | Jun 14, 2023 |
| Fujitsu       | D3222-B1 S26361-D3222-B1    | Desktop     | [01f33d2c9b](https://linux-hardware.org/?probe=01f33d2c9b) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [b1eabf98f6](https://linux-hardware.org/?probe=b1eabf98f6) | Jun 14, 2023 |
| Lenovo        | ThinkPad T440p 20AN009CU... | Notebook    | [54fd87b596](https://linux-hardware.org/?probe=54fd87b596) | Jun 14, 2023 |
| Irbis         | NB123                       | Notebook    | [f6dae4c3c4](https://linux-hardware.org/?probe=f6dae4c3c4) | Jun 14, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [a0cdda9a4d](https://linux-hardware.org/?probe=a0cdda9a4d) | Jun 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [f616cb77b5](https://linux-hardware.org/?probe=f616cb77b5) | Jun 13, 2023 |
| Gigabyte      | C246-WU4-CF                 | Desktop     | [8babb9b5f1](https://linux-hardware.org/?probe=8babb9b5f1) | Jun 13, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [0ec1b06d0c](https://linux-hardware.org/?probe=0ec1b06d0c) | Jun 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [7f974cd282](https://linux-hardware.org/?probe=7f974cd282) | Jun 12, 2023 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [787fa3215e](https://linux-hardware.org/?probe=787fa3215e) | Jun 12, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [679fb4f6ab](https://linux-hardware.org/?probe=679fb4f6ab) | Jun 11, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [36f0bbcb6d](https://linux-hardware.org/?probe=36f0bbcb6d) | Jun 11, 2023 |
| Lenovo        | 312A SDK0R32862 WIN 3258... | Desktop     | [1e8ab337a5](https://linux-hardware.org/?probe=1e8ab337a5) | Jun 11, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [b599a55609](https://linux-hardware.org/?probe=b599a55609) | Jun 10, 2023 |
| Dell          | G3 3779                     | Notebook    | [0190c87b35](https://linux-hardware.org/?probe=0190c87b35) | Jun 10, 2023 |
| Lenovo        | ThinkPad T570 20H9000UUS    | Notebook    | [606989ab70](https://linux-hardware.org/?probe=606989ab70) | Jun 10, 2023 |
| Seco          | C40 C                       | Desktop     | [4d990c8a0c](https://linux-hardware.org/?probe=4d990c8a0c) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [53ba4689ae](https://linux-hardware.org/?probe=53ba4689ae) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [58f4272bee](https://linux-hardware.org/?probe=58f4272bee) | Jun 10, 2023 |
| Dell          | XPS 13 9333                 | Notebook    | [88020aee75](https://linux-hardware.org/?probe=88020aee75) | Jun 09, 2023 |
| Supermicro    | C7H61                       | Desktop     | [7eef5b7873](https://linux-hardware.org/?probe=7eef5b7873) | Jun 08, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [cbf7ed91a7](https://linux-hardware.org/?probe=cbf7ed91a7) | Jun 08, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [e8b6d763e4](https://linux-hardware.org/?probe=e8b6d763e4) | Jun 08, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S5... | Notebook    | [0372aa0747](https://linux-hardware.org/?probe=0372aa0747) | Jun 08, 2023 |
| HP            | Notebook                    | Notebook    | [1b099710b7](https://linux-hardware.org/?probe=1b099710b7) | Jun 08, 2023 |
| HP            | Notebook                    | Notebook    | [9bf82397c3](https://linux-hardware.org/?probe=9bf82397c3) | Jun 08, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [610c9c318f](https://linux-hardware.org/?probe=610c9c318f) | Jun 08, 2023 |
| PC Special... | Initia Ii 15                | Notebook    | [36a16c2890](https://linux-hardware.org/?probe=36a16c2890) | Jun 08, 2023 |
| AZW           | SER V01                     | Mini pc     | [6b694e4b4a](https://linux-hardware.org/?probe=6b694e4b4a) | Jun 08, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [62418abec4](https://linux-hardware.org/?probe=62418abec4) | Jun 08, 2023 |
| AZW           | SER V01                     | Mini pc     | [0b7fb76a0b](https://linux-hardware.org/?probe=0b7fb76a0b) | Jun 08, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [810e331444](https://linux-hardware.org/?probe=810e331444) | Jun 07, 2023 |
| Gigabyte      | GA-MA770-US3                | Desktop     | [c22850601d](https://linux-hardware.org/?probe=c22850601d) | Jun 07, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [f02195de51](https://linux-hardware.org/?probe=f02195de51) | Jun 07, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [cb8797fce5](https://linux-hardware.org/?probe=cb8797fce5) | Jun 07, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [646e1db08d](https://linux-hardware.org/?probe=646e1db08d) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [f4e4a4b982](https://linux-hardware.org/?probe=f4e4a4b982) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [7948f267c2](https://linux-hardware.org/?probe=7948f267c2) | Jun 07, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [53341e2d0d](https://linux-hardware.org/?probe=53341e2d0d) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [1139c69312](https://linux-hardware.org/?probe=1139c69312) | Jun 06, 2023 |
| MSI           | 2AE0                        | Desktop     | [15b3c478d3](https://linux-hardware.org/?probe=15b3c478d3) | Jun 06, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [b06a0c9b89](https://linux-hardware.org/?probe=b06a0c9b89) | Jun 06, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [1b78246ef7](https://linux-hardware.org/?probe=1b78246ef7) | Jun 06, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [776a9fb064](https://linux-hardware.org/?probe=776a9fb064) | Jun 05, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5e9fd3f392](https://linux-hardware.org/?probe=5e9fd3f392) | Jun 05, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [693fdb51d3](https://linux-hardware.org/?probe=693fdb51d3) | Jun 05, 2023 |
| Biostar       | B350GT3                     | Desktop     | [b425f8d45a](https://linux-hardware.org/?probe=b425f8d45a) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b9cd465d98](https://linux-hardware.org/?probe=b9cd465d98) | Jun 05, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | Notebook    | [3bcc239452](https://linux-hardware.org/?probe=3bcc239452) | Jun 04, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [9636642e65](https://linux-hardware.org/?probe=9636642e65) | Jun 04, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [8ef447b2f3](https://linux-hardware.org/?probe=8ef447b2f3) | Jun 03, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [fc8a306ca0](https://linux-hardware.org/?probe=fc8a306ca0) | Jun 03, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [b7a585d1f1](https://linux-hardware.org/?probe=b7a585d1f1) | Jun 03, 2023 |
| Dell          | Latitude E6500              | Notebook    | [4053ff5676](https://linux-hardware.org/?probe=4053ff5676) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [767241151a](https://linux-hardware.org/?probe=767241151a) | Jun 03, 2023 |
| Lenovo        | ThinkPad T460 20FN004BMN    | Notebook    | [dafbbaeb0f](https://linux-hardware.org/?probe=dafbbaeb0f) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [6ae18b11ab](https://linux-hardware.org/?probe=6ae18b11ab) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [05a99cf128](https://linux-hardware.org/?probe=05a99cf128) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [963b30ca7f](https://linux-hardware.org/?probe=963b30ca7f) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [23e94c534e](https://linux-hardware.org/?probe=23e94c534e) | Jun 01, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [906dbab25c](https://linux-hardware.org/?probe=906dbab25c) | Jun 01, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7baed02e0e](https://linux-hardware.org/?probe=7baed02e0e) | Jun 01, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [16c536cda1](https://linux-hardware.org/?probe=16c536cda1) | Jun 01, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [d936c663d3](https://linux-hardware.org/?probe=d936c663d3) | Jun 01, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8720e6163e](https://linux-hardware.org/?probe=8720e6163e) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [fc4e2630c0](https://linux-hardware.org/?probe=fc4e2630c0) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [f02c7845e5](https://linux-hardware.org/?probe=f02c7845e5) | Jun 01, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [8f8afcc010](https://linux-hardware.org/?probe=8f8afcc010) | Jun 01, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [0586d2c0e2](https://linux-hardware.org/?probe=0586d2c0e2) | Jun 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ebd7782079](https://linux-hardware.org/?probe=ebd7782079) | May 31, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [e936e44332](https://linux-hardware.org/?probe=e936e44332) | May 31, 2023 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [2723d218b7](https://linux-hardware.org/?probe=2723d218b7) | May 31, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [c677ff5b2d](https://linux-hardware.org/?probe=c677ff5b2d) | May 31, 2023 |
| AZW           | GTR V02                     | Desktop     | [bd1740c7b2](https://linux-hardware.org/?probe=bd1740c7b2) | May 31, 2023 |
| AZW           | GTR V02                     | Desktop     | [cab90f1838](https://linux-hardware.org/?probe=cab90f1838) | May 31, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [2667cb67a3](https://linux-hardware.org/?probe=2667cb67a3) | May 30, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [2ac99b8909](https://linux-hardware.org/?probe=2ac99b8909) | May 30, 2023 |
| Dell          | G15 5525                    | Notebook    | [f7e5d0ae57](https://linux-hardware.org/?probe=f7e5d0ae57) | May 30, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [0568aa067a](https://linux-hardware.org/?probe=0568aa067a) | May 30, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [4f23de2827](https://linux-hardware.org/?probe=4f23de2827) | May 30, 2023 |
| MSI           | Titan GT77HX 13VH           | Notebook    | [7c3b8ed81d](https://linux-hardware.org/?probe=7c3b8ed81d) | May 29, 2023 |
| Packard Be... | MCP73                       | Desktop     | [e180017a10](https://linux-hardware.org/?probe=e180017a10) | May 29, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [bca463af6d](https://linux-hardware.org/?probe=bca463af6d) | May 28, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [cdc924595c](https://linux-hardware.org/?probe=cdc924595c) | May 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [8fd2003b01](https://linux-hardware.org/?probe=8fd2003b01) | May 28, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [70714d71f5](https://linux-hardware.org/?probe=70714d71f5) | May 28, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [e429db5b0b](https://linux-hardware.org/?probe=e429db5b0b) | May 27, 2023 |
| Dell          | Precision 5530              | Notebook    | [cb116bdfd2](https://linux-hardware.org/?probe=cb116bdfd2) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [2b9c4431c2](https://linux-hardware.org/?probe=2b9c4431c2) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [f5b571be32](https://linux-hardware.org/?probe=f5b571be32) | May 26, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [a8fd95ce79](https://linux-hardware.org/?probe=a8fd95ce79) | May 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [1c62418caf](https://linux-hardware.org/?probe=1c62418caf) | May 25, 2023 |
| Alienware     | 04VWF2 A00                  | Desktop     | [0d6c86d757](https://linux-hardware.org/?probe=0d6c86d757) | May 25, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [3e1fb6f93b](https://linux-hardware.org/?probe=3e1fb6f93b) | May 25, 2023 |
| Google        | Bluebird                    | Notebook    | [5b41bdf767](https://linux-hardware.org/?probe=5b41bdf767) | May 25, 2023 |
| Acer          | Aspire M3920                | Desktop     | [5e61c22a26](https://linux-hardware.org/?probe=5e61c22a26) | May 24, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [2ef3c0b337](https://linux-hardware.org/?probe=2ef3c0b337) | May 24, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [174a3139c4](https://linux-hardware.org/?probe=174a3139c4) | May 24, 2023 |
| Dell          | Inspiron 14 5401            | Notebook    | [16d8b1c945](https://linux-hardware.org/?probe=16d8b1c945) | May 24, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [9568d26302](https://linux-hardware.org/?probe=9568d26302) | May 24, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [3eb016e8c7](https://linux-hardware.org/?probe=3eb016e8c7) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3d4cdd163c](https://linux-hardware.org/?probe=3d4cdd163c) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c3251b8c63](https://linux-hardware.org/?probe=c3251b8c63) | May 23, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [b880d4f8c1](https://linux-hardware.org/?probe=b880d4f8c1) | May 23, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [27819563b9](https://linux-hardware.org/?probe=27819563b9) | May 23, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [7f3dae82d3](https://linux-hardware.org/?probe=7f3dae82d3) | May 23, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [185b65bf34](https://linux-hardware.org/?probe=185b65bf34) | May 22, 2023 |
| Packard Be... | MCP73                       | Desktop     | [1203dc5301](https://linux-hardware.org/?probe=1203dc5301) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [8d8c13c10c](https://linux-hardware.org/?probe=8d8c13c10c) | May 22, 2023 |
| ASRock        | X99 Extreme6/ac             | Desktop     | [8e255dc13b](https://linux-hardware.org/?probe=8e255dc13b) | May 22, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [434372d228](https://linux-hardware.org/?probe=434372d228) | May 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [1c178d1658](https://linux-hardware.org/?probe=1c178d1658) | May 21, 2023 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [a8d8e219a2](https://linux-hardware.org/?probe=a8d8e219a2) | May 21, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [80c62a0473](https://linux-hardware.org/?probe=80c62a0473) | May 21, 2023 |
| Alienware     | 04VWF2 A00                  | Desktop     | [7c09c55150](https://linux-hardware.org/?probe=7c09c55150) | May 21, 2023 |
| HP            | 350 G1                      | Notebook    | [7629c78328](https://linux-hardware.org/?probe=7629c78328) | May 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [71ac41efb8](https://linux-hardware.org/?probe=71ac41efb8) | May 20, 2023 |
| MSI           | X370 GAMING PLUS            | Desktop     | [610c8c1a42](https://linux-hardware.org/?probe=610c8c1a42) | May 19, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [1e7af790ed](https://linux-hardware.org/?probe=1e7af790ed) | May 19, 2023 |
| BOSGAME       | B95                         | Notebook    | [3d1805a2eb](https://linux-hardware.org/?probe=3d1805a2eb) | May 19, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [26e8deafbf](https://linux-hardware.org/?probe=26e8deafbf) | May 19, 2023 |
| Acer          | Aspire E5-521               | Notebook    | [05227be8bc](https://linux-hardware.org/?probe=05227be8bc) | May 18, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [e0300907f0](https://linux-hardware.org/?probe=e0300907f0) | May 18, 2023 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | Notebook    | [61b0585530](https://linux-hardware.org/?probe=61b0585530) | May 18, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | Desktop     | [166ec29ce0](https://linux-hardware.org/?probe=166ec29ce0) | May 18, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [7da21ce089](https://linux-hardware.org/?probe=7da21ce089) | May 18, 2023 |
| Unknown       | V00                         | Mini pc     | [79cb590ea8](https://linux-hardware.org/?probe=79cb590ea8) | May 17, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [28b96d7d6a](https://linux-hardware.org/?probe=28b96d7d6a) | May 17, 2023 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [0906223758](https://linux-hardware.org/?probe=0906223758) | May 17, 2023 |
| Samsung       | 730QFG                      | Convertible | [134377c283](https://linux-hardware.org/?probe=134377c283) | May 17, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [7c05862259](https://linux-hardware.org/?probe=7c05862259) | May 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [8cb1f28963](https://linux-hardware.org/?probe=8cb1f28963) | May 16, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [0331ab9725](https://linux-hardware.org/?probe=0331ab9725) | May 16, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [c8250719d9](https://linux-hardware.org/?probe=c8250719d9) | May 16, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [14edb35e71](https://linux-hardware.org/?probe=14edb35e71) | May 15, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [98ebdcd589](https://linux-hardware.org/?probe=98ebdcd589) | May 15, 2023 |
| HP            | 3397                        | Desktop     | [17d9dcc121](https://linux-hardware.org/?probe=17d9dcc121) | May 15, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [f90de81324](https://linux-hardware.org/?probe=f90de81324) | May 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [5f508efff4](https://linux-hardware.org/?probe=5f508efff4) | May 14, 2023 |
| ASUSTek       | F1A75-V PRO                 | Desktop     | [9ee8a0ca50](https://linux-hardware.org/?probe=9ee8a0ca50) | May 14, 2023 |
| AMI           | Intel                       | Desktop     | [569d80a4a0](https://linux-hardware.org/?probe=569d80a4a0) | May 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [e81d6a8a69](https://linux-hardware.org/?probe=e81d6a8a69) | May 14, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [0df5818390](https://linux-hardware.org/?probe=0df5818390) | May 14, 2023 |
| Dell          | Latitude E6500              | Notebook    | [b223b17c87](https://linux-hardware.org/?probe=b223b17c87) | May 14, 2023 |
| PC Special... | P65_67RSRP                  | Notebook    | [892b6d56c8](https://linux-hardware.org/?probe=892b6d56c8) | May 13, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [0701f94970](https://linux-hardware.org/?probe=0701f94970) | May 13, 2023 |
| Dell          | G3 3590                     | Notebook    | [696d2d38df](https://linux-hardware.org/?probe=696d2d38df) | May 13, 2023 |
| Samsung       | R425/R525                   | Notebook    | [a7719ea5d3](https://linux-hardware.org/?probe=a7719ea5d3) | May 13, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [f8c0bd3176](https://linux-hardware.org/?probe=f8c0bd3176) | May 12, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [9ca71ebd01](https://linux-hardware.org/?probe=9ca71ebd01) | May 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [58557ae6a2](https://linux-hardware.org/?probe=58557ae6a2) | May 12, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [d8c0bd3bff](https://linux-hardware.org/?probe=d8c0bd3bff) | May 12, 2023 |
| Dell          | Latitude 7490               | Notebook    | [a187ae7b7e](https://linux-hardware.org/?probe=a187ae7b7e) | May 12, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [9448d89bb6](https://linux-hardware.org/?probe=9448d89bb6) | May 12, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [094fd8b39a](https://linux-hardware.org/?probe=094fd8b39a) | May 12, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [c071e02f0d](https://linux-hardware.org/?probe=c071e02f0d) | May 12, 2023 |
| Dell          | Latitude E5470              | Notebook    | [59c95182ec](https://linux-hardware.org/?probe=59c95182ec) | May 11, 2023 |
| Intel         | H61                         | Desktop     | [57ef0f0f97](https://linux-hardware.org/?probe=57ef0f0f97) | May 11, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [e360693145](https://linux-hardware.org/?probe=e360693145) | May 11, 2023 |
| Dell          | Latitude 5420               | Notebook    | [a3c2a7c9bf](https://linux-hardware.org/?probe=a3c2a7c9bf) | May 11, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [63e082c879](https://linux-hardware.org/?probe=63e082c879) | May 10, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [c85cc0e79c](https://linux-hardware.org/?probe=c85cc0e79c) | May 10, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d567c1f954](https://linux-hardware.org/?probe=d567c1f954) | May 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c80f41d509](https://linux-hardware.org/?probe=c80f41d509) | May 09, 2023 |
| IBM           | 00AM544                     | Server      | [4c011ef794](https://linux-hardware.org/?probe=4c011ef794) | May 09, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [c941da38cd](https://linux-hardware.org/?probe=c941da38cd) | May 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [cbafd29abc](https://linux-hardware.org/?probe=cbafd29abc) | May 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [8d1f016621](https://linux-hardware.org/?probe=8d1f016621) | May 08, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [8f08aa189f](https://linux-hardware.org/?probe=8f08aa189f) | May 08, 2023 |
| Dell          | Latitude 3570               | Notebook    | [8209fc06f4](https://linux-hardware.org/?probe=8209fc06f4) | May 08, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [c075073dd8](https://linux-hardware.org/?probe=c075073dd8) | May 07, 2023 |
| TerraQue      | W65_W67RB                   | Notebook    | [842f203ec5](https://linux-hardware.org/?probe=842f203ec5) | May 07, 2023 |
| Acer          | Aspire M3920                | Desktop     | [aed14c1e20](https://linux-hardware.org/?probe=aed14c1e20) | May 07, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [a062cb2ab6](https://linux-hardware.org/?probe=a062cb2ab6) | May 07, 2023 |
| Biostar       | AM1MHP                      | Desktop     | [1f21e13fcd](https://linux-hardware.org/?probe=1f21e13fcd) | May 07, 2023 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | Notebook    | [4229be0afa](https://linux-hardware.org/?probe=4229be0afa) | May 07, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | Notebook    | [3cf83f50f0](https://linux-hardware.org/?probe=3cf83f50f0) | May 07, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [7bbdc5e568](https://linux-hardware.org/?probe=7bbdc5e568) | May 07, 2023 |
| Google        | Lars                        | Notebook    | [db3ba59095](https://linux-hardware.org/?probe=db3ba59095) | May 06, 2023 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [167229560a](https://linux-hardware.org/?probe=167229560a) | May 05, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [68b1e1e6cb](https://linux-hardware.org/?probe=68b1e1e6cb) | May 05, 2023 |
| Razer         | Blade Pro 17 (2019)         | Notebook    | [4b2265c354](https://linux-hardware.org/?probe=4b2265c354) | May 05, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [f6251eeeb1](https://linux-hardware.org/?probe=f6251eeeb1) | May 05, 2023 |
| Medion        | E11201                      | Notebook    | [f0bfd835f8](https://linux-hardware.org/?probe=f0bfd835f8) | May 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [1f2d88bfae](https://linux-hardware.org/?probe=1f2d88bfae) | May 04, 2023 |
| Dell          | Latitude 5480               | Notebook    | [1ab8b910e4](https://linux-hardware.org/?probe=1ab8b910e4) | May 04, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [00a1158a86](https://linux-hardware.org/?probe=00a1158a86) | May 04, 2023 |
| ASUSTek       | X750JB                      | Notebook    | [02a5481254](https://linux-hardware.org/?probe=02a5481254) | May 03, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [ae1618c708](https://linux-hardware.org/?probe=ae1618c708) | May 03, 2023 |
| Gigabyte      | H87-HD3                     | Desktop     | [f0e4057e5f](https://linux-hardware.org/?probe=f0e4057e5f) | May 03, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [63015eecb0](https://linux-hardware.org/?probe=63015eecb0) | May 03, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [861ca2dca3](https://linux-hardware.org/?probe=861ca2dca3) | May 03, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [36574d4502](https://linux-hardware.org/?probe=36574d4502) | May 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [2da8ff7129](https://linux-hardware.org/?probe=2da8ff7129) | May 03, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [263099c212](https://linux-hardware.org/?probe=263099c212) | May 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [ee8e81add2](https://linux-hardware.org/?probe=ee8e81add2) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [e8ce8c11c0](https://linux-hardware.org/?probe=e8ce8c11c0) | May 01, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [1846ea93e7](https://linux-hardware.org/?probe=1846ea93e7) | May 01, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [a3c89effff](https://linux-hardware.org/?probe=a3c89effff) | May 01, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [45a7e28db1](https://linux-hardware.org/?probe=45a7e28db1) | Apr 30, 2023 |
| HP            | 828A                        | Desktop     | [f1590b355f](https://linux-hardware.org/?probe=f1590b355f) | Apr 30, 2023 |
| Intel         | H81                         | Desktop     | [c70b10516b](https://linux-hardware.org/?probe=c70b10516b) | Apr 30, 2023 |
| Acer          | Aspire M5-481T              | Notebook    | [d215d36b64](https://linux-hardware.org/?probe=d215d36b64) | Apr 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [1ccae7d268](https://linux-hardware.org/?probe=1ccae7d268) | Apr 28, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [a31fa8f985](https://linux-hardware.org/?probe=a31fa8f985) | Apr 28, 2023 |
| ASUSTek       | X51RL                       | Notebook    | [0d18de9922](https://linux-hardware.org/?probe=0d18de9922) | Apr 28, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [dd76e10243](https://linux-hardware.org/?probe=dd76e10243) | Apr 28, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7feb43607e](https://linux-hardware.org/?probe=7feb43607e) | Apr 27, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [44c5943019](https://linux-hardware.org/?probe=44c5943019) | Apr 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [442a827555](https://linux-hardware.org/?probe=442a827555) | Apr 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [a6845d78e4](https://linux-hardware.org/?probe=a6845d78e4) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [812906148b](https://linux-hardware.org/?probe=812906148b) | Apr 27, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [fee636a549](https://linux-hardware.org/?probe=fee636a549) | Apr 26, 2023 |
| Samsung       | 950XED                      | Notebook    | [02586ee1ba](https://linux-hardware.org/?probe=02586ee1ba) | Apr 26, 2023 |
| ASUSTek       | P5K/EPU                     | Desktop     | [33ef71c7e7](https://linux-hardware.org/?probe=33ef71c7e7) | Apr 26, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [f9d337a0a1](https://linux-hardware.org/?probe=f9d337a0a1) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430s 23539MU      | Notebook    | [83a1144be6](https://linux-hardware.org/?probe=83a1144be6) | Apr 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [4285b1a3d9](https://linux-hardware.org/?probe=4285b1a3d9) | Apr 25, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [b03c4808b0](https://linux-hardware.org/?probe=b03c4808b0) | Apr 25, 2023 |
| Alienware     | Aurora R15 AMD              | Desktop     | [f2e22848d1](https://linux-hardware.org/?probe=f2e22848d1) | Apr 25, 2023 |
| MSI           | FM2-A75MA-E35               | Desktop     | [011f691ce1](https://linux-hardware.org/?probe=011f691ce1) | Apr 25, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [76646ac40d](https://linux-hardware.org/?probe=76646ac40d) | Apr 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [3d8d7c49f8](https://linux-hardware.org/?probe=3d8d7c49f8) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [e9a3b8f1d1](https://linux-hardware.org/?probe=e9a3b8f1d1) | Apr 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [38806ed70c](https://linux-hardware.org/?probe=38806ed70c) | Apr 24, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [2a8a92135b](https://linux-hardware.org/?probe=2a8a92135b) | Apr 24, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [0fde788ea5](https://linux-hardware.org/?probe=0fde788ea5) | Apr 24, 2023 |
| Foxconn       | H67M-S/H67M-V/H67           | Desktop     | [92fa61186f](https://linux-hardware.org/?probe=92fa61186f) | Apr 23, 2023 |
| Dell          | Inspiron 5521               | Notebook    | [8de2e801a3](https://linux-hardware.org/?probe=8de2e801a3) | Apr 23, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [fa5d5b4733](https://linux-hardware.org/?probe=fa5d5b4733) | Apr 23, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [d7648edaab](https://linux-hardware.org/?probe=d7648edaab) | Apr 23, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [bee14868f2](https://linux-hardware.org/?probe=bee14868f2) | Apr 23, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [10cd21aba6](https://linux-hardware.org/?probe=10cd21aba6) | Apr 23, 2023 |
| Dell          | 00V16R A00                  | All in one  | [cb94924faa](https://linux-hardware.org/?probe=cb94924faa) | Apr 23, 2023 |
| Dell          | Precision 5520              | Notebook    | [4d1dd8b673](https://linux-hardware.org/?probe=4d1dd8b673) | Apr 23, 2023 |
| Dell          | Precision 7550              | Notebook    | [31830a82c6](https://linux-hardware.org/?probe=31830a82c6) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c4a5aad8a1](https://linux-hardware.org/?probe=c4a5aad8a1) | Apr 22, 2023 |
| Gigabyte      | AORUS 15P XD                | Notebook    | [22925aa0c9](https://linux-hardware.org/?probe=22925aa0c9) | Apr 22, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [475a4d151d](https://linux-hardware.org/?probe=475a4d151d) | Apr 22, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [f7528e9759](https://linux-hardware.org/?probe=f7528e9759) | Apr 22, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [0dcc2eaa50](https://linux-hardware.org/?probe=0dcc2eaa50) | Apr 22, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [3165ab3194](https://linux-hardware.org/?probe=3165ab3194) | Apr 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [918115dc84](https://linux-hardware.org/?probe=918115dc84) | Apr 21, 2023 |
| HP            | 82F2 A01                    | Desktop     | [fbcf679bae](https://linux-hardware.org/?probe=fbcf679bae) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [a02462f614](https://linux-hardware.org/?probe=a02462f614) | Apr 21, 2023 |
| Supermicro    | C7H61                       | Desktop     | [f5e17f37d4](https://linux-hardware.org/?probe=f5e17f37d4) | Apr 21, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [3d241113f4](https://linux-hardware.org/?probe=3d241113f4) | Apr 21, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [cb295448b6](https://linux-hardware.org/?probe=cb295448b6) | Apr 21, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [af5e3d750a](https://linux-hardware.org/?probe=af5e3d750a) | Apr 20, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [970c4dfa6f](https://linux-hardware.org/?probe=970c4dfa6f) | Apr 20, 2023 |
| Supermicro    | C7H61                       | Desktop     | [d975325f4b](https://linux-hardware.org/?probe=d975325f4b) | Apr 20, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [f83e11ca39](https://linux-hardware.org/?probe=f83e11ca39) | Apr 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cd58803d5c](https://linux-hardware.org/?probe=cd58803d5c) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [7adb4b2000](https://linux-hardware.org/?probe=7adb4b2000) | Apr 19, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [d96138627b](https://linux-hardware.org/?probe=d96138627b) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [cccb2ff44c](https://linux-hardware.org/?probe=cccb2ff44c) | Apr 18, 2023 |
| HP            | 630                         | Notebook    | [daeae9f12e](https://linux-hardware.org/?probe=daeae9f12e) | Apr 18, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [26a430e092](https://linux-hardware.org/?probe=26a430e092) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [cc18450a32](https://linux-hardware.org/?probe=cc18450a32) | Apr 17, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [7ed9078ed9](https://linux-hardware.org/?probe=7ed9078ed9) | Apr 17, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [d76555e7e6](https://linux-hardware.org/?probe=d76555e7e6) | Apr 16, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [7aef52516b](https://linux-hardware.org/?probe=7aef52516b) | Apr 16, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [af72ecc689](https://linux-hardware.org/?probe=af72ecc689) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [073b59d558](https://linux-hardware.org/?probe=073b59d558) | Apr 16, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [c34c2e032c](https://linux-hardware.org/?probe=c34c2e032c) | Apr 15, 2023 |
| AXIOO         | SlimBook 11                 | Notebook    | [b0c639ab77](https://linux-hardware.org/?probe=b0c639ab77) | Apr 15, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [00526690c9](https://linux-hardware.org/?probe=00526690c9) | Apr 15, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [ffa823032e](https://linux-hardware.org/?probe=ffa823032e) | Apr 14, 2023 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [c17cfe4d6d](https://linux-hardware.org/?probe=c17cfe4d6d) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [9518f3e6d8](https://linux-hardware.org/?probe=9518f3e6d8) | Apr 13, 2023 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [91946b965a](https://linux-hardware.org/?probe=91946b965a) | Apr 13, 2023 |
| Lenovo        | S21e-20 80M4                | Notebook    | [8d235a410a](https://linux-hardware.org/?probe=8d235a410a) | Apr 13, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [d21971f30f](https://linux-hardware.org/?probe=d21971f30f) | Apr 13, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [5e772c9376](https://linux-hardware.org/?probe=5e772c9376) | Apr 13, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [624fa75f43](https://linux-hardware.org/?probe=624fa75f43) | Apr 12, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [139f5f3aca](https://linux-hardware.org/?probe=139f5f3aca) | Apr 12, 2023 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [674533c5cd](https://linux-hardware.org/?probe=674533c5cd) | Apr 12, 2023 |
| Dell          | Latitude E5450              | Notebook    | [f98cdf4da0](https://linux-hardware.org/?probe=f98cdf4da0) | Apr 11, 2023 |
| Dell          | Latitude E5450              | Notebook    | [7bf04cdb7d](https://linux-hardware.org/?probe=7bf04cdb7d) | Apr 11, 2023 |
| ASUSTek       | X51RL                       | Notebook    | [ca3fb7f6d5](https://linux-hardware.org/?probe=ca3fb7f6d5) | Apr 11, 2023 |
| HP            | 829C                        | All in one  | [91f5a10ba1](https://linux-hardware.org/?probe=91f5a10ba1) | Apr 11, 2023 |
| Dell          | 0RW199                      | Desktop     | [8c41f4ff91](https://linux-hardware.org/?probe=8c41f4ff91) | Apr 11, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [5875837a8d](https://linux-hardware.org/?probe=5875837a8d) | Apr 10, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6b6b2a8633](https://linux-hardware.org/?probe=6b6b2a8633) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [00489240d2](https://linux-hardware.org/?probe=00489240d2) | Apr 09, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [e42bdc9769](https://linux-hardware.org/?probe=e42bdc9769) | Apr 09, 2023 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [0ddbf6cc2e](https://linux-hardware.org/?probe=0ddbf6cc2e) | Apr 07, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [8187fc54a3](https://linux-hardware.org/?probe=8187fc54a3) | Apr 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [0bf91f3219](https://linux-hardware.org/?probe=0bf91f3219) | Apr 06, 2023 |
| Lenovo        | ThinkPad T420 4177RVU       | Notebook    | [994fccf5d0](https://linux-hardware.org/?probe=994fccf5d0) | Apr 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [ec673ad1c1](https://linux-hardware.org/?probe=ec673ad1c1) | Apr 06, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [917714b1be](https://linux-hardware.org/?probe=917714b1be) | Apr 06, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [ad148ede52](https://linux-hardware.org/?probe=ad148ede52) | Apr 06, 2023 |
| Gigabyte      | M61SME-S2                   | Desktop     | [25d436d2cb](https://linux-hardware.org/?probe=25d436d2cb) | Apr 06, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [b7d43d9e23](https://linux-hardware.org/?probe=b7d43d9e23) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [edd397551c](https://linux-hardware.org/?probe=edd397551c) | Apr 05, 2023 |
| HP            | 0A9Ch                       | Desktop     | [178046626f](https://linux-hardware.org/?probe=178046626f) | Apr 05, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [6ec3c125d5](https://linux-hardware.org/?probe=6ec3c125d5) | Apr 05, 2023 |
| HP            | 3397                        | Desktop     | [175b460d57](https://linux-hardware.org/?probe=175b460d57) | Apr 05, 2023 |
| HP            | 3397                        | Desktop     | [b512b25055](https://linux-hardware.org/?probe=b512b25055) | Apr 05, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [32f708c916](https://linux-hardware.org/?probe=32f708c916) | Apr 05, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [0779903086](https://linux-hardware.org/?probe=0779903086) | Apr 05, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [7cce222ce2](https://linux-hardware.org/?probe=7cce222ce2) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [7eeea6ba29](https://linux-hardware.org/?probe=7eeea6ba29) | Apr 04, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [62f7197973](https://linux-hardware.org/?probe=62f7197973) | Apr 04, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [6e750dfaa5](https://linux-hardware.org/?probe=6e750dfaa5) | Apr 04, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | Notebook    | [1c9d684eba](https://linux-hardware.org/?probe=1c9d684eba) | Apr 04, 2023 |
| Alienware     | 0VDT73 A00                  | Desktop     | [ed92305da6](https://linux-hardware.org/?probe=ed92305da6) | Apr 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFS... | Notebook    | [0cff652e48](https://linux-hardware.org/?probe=0cff652e48) | Apr 03, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [72dc18dacb](https://linux-hardware.org/?probe=72dc18dacb) | Apr 03, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [8ba82ca424](https://linux-hardware.org/?probe=8ba82ca424) | Apr 03, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [f8e61fd850](https://linux-hardware.org/?probe=f8e61fd850) | Apr 03, 2023 |
| ASUSTek       | ASUS ExpertBook P2451FA_... | Notebook    | [05261a9b98](https://linux-hardware.org/?probe=05261a9b98) | Apr 03, 2023 |
| Google        | Eve                         | Convertible | [551ff8d7c2](https://linux-hardware.org/?probe=551ff8d7c2) | Apr 03, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [35c3ae13c5](https://linux-hardware.org/?probe=35c3ae13c5) | Apr 02, 2023 |
| WeiBu         | ADL-N Prod                  | Desktop     | [9b96a245f1](https://linux-hardware.org/?probe=9b96a245f1) | Apr 02, 2023 |
| Thomson       | SPNEOX13-4RD64              | Notebook    | [bf3eb39804](https://linux-hardware.org/?probe=bf3eb39804) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [e800b0ff2e](https://linux-hardware.org/?probe=e800b0ff2e) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [a0dddcbb95](https://linux-hardware.org/?probe=a0dddcbb95) | Apr 02, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [12647b9601](https://linux-hardware.org/?probe=12647b9601) | Apr 02, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [46e8dbcdc8](https://linux-hardware.org/?probe=46e8dbcdc8) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [37beaa5cbb](https://linux-hardware.org/?probe=37beaa5cbb) | Apr 02, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | Notebook    | [4809c76aba](https://linux-hardware.org/?probe=4809c76aba) | Apr 02, 2023 |
| AAEON         | MF-001 V1.0                 | Desktop     | [ddceb8b5b0](https://linux-hardware.org/?probe=ddceb8b5b0) | Apr 02, 2023 |
| Lenovo        | ThinkPad X280 20KF001UUS    | Notebook    | [49e740bc77](https://linux-hardware.org/?probe=49e740bc77) | Apr 02, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [0fbed59931](https://linux-hardware.org/?probe=0fbed59931) | Apr 02, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [98f2b162e1](https://linux-hardware.org/?probe=98f2b162e1) | Apr 01, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [bc77efa103](https://linux-hardware.org/?probe=bc77efa103) | Apr 01, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [93f1374055](https://linux-hardware.org/?probe=93f1374055) | Apr 01, 2023 |
| MSI           | MAG A520M VECTOR WIFI       | Desktop     | [3c08cf9aba](https://linux-hardware.org/?probe=3c08cf9aba) | Apr 01, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [4a1b8f3f21](https://linux-hardware.org/?probe=4a1b8f3f21) | Apr 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [89ca656f30](https://linux-hardware.org/?probe=89ca656f30) | Apr 01, 2023 |
| Lenovo        | ThinkCentre M58 9728AHG     | Desktop     | [cb0fa70953](https://linux-hardware.org/?probe=cb0fa70953) | Apr 01, 2023 |
| Gigabyte      | A7 K1                       | Notebook    | [e5e7751054](https://linux-hardware.org/?probe=e5e7751054) | Mar 31, 2023 |
| Chuwi         | CoreBook XPro               | Notebook    | [85ad17d246](https://linux-hardware.org/?probe=85ad17d246) | Mar 31, 2023 |
| Intel         | Whiskey Platform            | Notebook    | [36b9d4d898](https://linux-hardware.org/?probe=36b9d4d898) | Mar 31, 2023 |
| Samsung       | 950QDB                      | Convertible | [09717388fb](https://linux-hardware.org/?probe=09717388fb) | Mar 31, 2023 |
| ASUSTek       | EB1036                      | Desktop     | [955d389e06](https://linux-hardware.org/?probe=955d389e06) | Mar 30, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [3636f7f999](https://linux-hardware.org/?probe=3636f7f999) | Mar 30, 2023 |
| Motion Com... | J3600                       | Notebook    | [0980fe0a37](https://linux-hardware.org/?probe=0980fe0a37) | Mar 30, 2023 |
| Intel         | Whiskey Platform            | Notebook    | [a96edb2321](https://linux-hardware.org/?probe=a96edb2321) | Mar 30, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [278ed0e013](https://linux-hardware.org/?probe=278ed0e013) | Mar 30, 2023 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [49f246c5e7](https://linux-hardware.org/?probe=49f246c5e7) | Mar 29, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4f9eed1de2](https://linux-hardware.org/?probe=4f9eed1de2) | Mar 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | Notebook    | [cf75eeabd5](https://linux-hardware.org/?probe=cf75eeabd5) | Mar 29, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b72701d99c](https://linux-hardware.org/?probe=b72701d99c) | Mar 29, 2023 |
| Intel         | DQ67OW AAG28716-309         | Desktop     | [3a82d680e5](https://linux-hardware.org/?probe=3a82d680e5) | Mar 29, 2023 |
| Dell          | 0200DY A01                  | Desktop     | [722b28547b](https://linux-hardware.org/?probe=722b28547b) | Mar 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [548224967e](https://linux-hardware.org/?probe=548224967e) | Mar 28, 2023 |
| HP            | 0AACh                       | Desktop     | [e313c99b98](https://linux-hardware.org/?probe=e313c99b98) | Mar 28, 2023 |
| MSI           | B85-G43                     | Desktop     | [3dac8c76c2](https://linux-hardware.org/?probe=3dac8c76c2) | Mar 28, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [fd1273ed2e](https://linux-hardware.org/?probe=fd1273ed2e) | Mar 28, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [046b4b7497](https://linux-hardware.org/?probe=046b4b7497) | Mar 28, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [0f38ea375f](https://linux-hardware.org/?probe=0f38ea375f) | Mar 28, 2023 |
| Lenovo        | SHARKBAY SDK0J40709 WIN ... | Desktop     | [22e3e1831c](https://linux-hardware.org/?probe=22e3e1831c) | Mar 28, 2023 |
| HP            | 0AACh                       | Desktop     | [f354a2f03e](https://linux-hardware.org/?probe=f354a2f03e) | Mar 27, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [84092aca44](https://linux-hardware.org/?probe=84092aca44) | Mar 27, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [ccae23c5a7](https://linux-hardware.org/?probe=ccae23c5a7) | Mar 27, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [d18cb08996](https://linux-hardware.org/?probe=d18cb08996) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [6553d2c85a](https://linux-hardware.org/?probe=6553d2c85a) | Mar 26, 2023 |
| HP            | 1998                        | Desktop     | [346f37956b](https://linux-hardware.org/?probe=346f37956b) | Mar 26, 2023 |
| Lenovo        | ThinkPad SL 2743NSC         | Notebook    | [48d6301eaa](https://linux-hardware.org/?probe=48d6301eaa) | Mar 26, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [ffb310e799](https://linux-hardware.org/?probe=ffb310e799) | Mar 26, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | Notebook    | [369363c3a9](https://linux-hardware.org/?probe=369363c3a9) | Mar 26, 2023 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [fac3426827](https://linux-hardware.org/?probe=fac3426827) | Mar 26, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [cdc4b03fe2](https://linux-hardware.org/?probe=cdc4b03fe2) | Mar 26, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [2246abad85](https://linux-hardware.org/?probe=2246abad85) | Mar 25, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [4262f0e159](https://linux-hardware.org/?probe=4262f0e159) | Mar 25, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [ad4b4f6a8f](https://linux-hardware.org/?probe=ad4b4f6a8f) | Mar 25, 2023 |
| Intel         | Whiskey Platform            | Notebook    | [e90c029740](https://linux-hardware.org/?probe=e90c029740) | Mar 25, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [30d5652df2](https://linux-hardware.org/?probe=30d5652df2) | Mar 25, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [a0bba69c40](https://linux-hardware.org/?probe=a0bba69c40) | Mar 25, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [98d0daa764](https://linux-hardware.org/?probe=98d0daa764) | Mar 25, 2023 |
| Dell          | Latitude E6420              | Notebook    | [2613e5a6ef](https://linux-hardware.org/?probe=2613e5a6ef) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [bf5cc186ea](https://linux-hardware.org/?probe=bf5cc186ea) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [c37a546614](https://linux-hardware.org/?probe=c37a546614) | Mar 25, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [e7f9195a1d](https://linux-hardware.org/?probe=e7f9195a1d) | Mar 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [e7b44d994b](https://linux-hardware.org/?probe=e7b44d994b) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [444375922e](https://linux-hardware.org/?probe=444375922e) | Mar 25, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [9a8b9b917f](https://linux-hardware.org/?probe=9a8b9b917f) | Mar 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c114580013](https://linux-hardware.org/?probe=c114580013) | Mar 24, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [1f256fa102](https://linux-hardware.org/?probe=1f256fa102) | Mar 24, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [c7ec617422](https://linux-hardware.org/?probe=c7ec617422) | Mar 24, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [63fafca0ac](https://linux-hardware.org/?probe=63fafca0ac) | Mar 24, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [2d8268e40f](https://linux-hardware.org/?probe=2d8268e40f) | Mar 24, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [c50deee021](https://linux-hardware.org/?probe=c50deee021) | Mar 24, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [4e2b8b9de9](https://linux-hardware.org/?probe=4e2b8b9de9) | Mar 24, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [6d1a1f7bd2](https://linux-hardware.org/?probe=6d1a1f7bd2) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | Notebook    | [16b93bfe5d](https://linux-hardware.org/?probe=16b93bfe5d) | Mar 24, 2023 |
| Dell          | Latitude 5420               | Notebook    | [42d5b573c4](https://linux-hardware.org/?probe=42d5b573c4) | Mar 24, 2023 |
| Dell          | Latitude E7470              | Notebook    | [ca8a2d9579](https://linux-hardware.org/?probe=ca8a2d9579) | Mar 24, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [9b048b064d](https://linux-hardware.org/?probe=9b048b064d) | Mar 24, 2023 |
| Dell          | 0W13NR A08                  | Server      | [13bd99e4bc](https://linux-hardware.org/?probe=13bd99e4bc) | Mar 23, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [43113791e9](https://linux-hardware.org/?probe=43113791e9) | Mar 23, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [4077bee378](https://linux-hardware.org/?probe=4077bee378) | Mar 23, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [529a2febf7](https://linux-hardware.org/?probe=529a2febf7) | Mar 23, 2023 |
| Notebook      | NV4xPZ                      | Notebook    | [74d70a3568](https://linux-hardware.org/?probe=74d70a3568) | Mar 23, 2023 |
| Lenovo        | ThinkCentre M58 9728AHG     | Desktop     | [e1cfc1c76d](https://linux-hardware.org/?probe=e1cfc1c76d) | Mar 23, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [84f93bfcf1](https://linux-hardware.org/?probe=84f93bfcf1) | Mar 23, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [631968d54b](https://linux-hardware.org/?probe=631968d54b) | Mar 23, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [61dcde6523](https://linux-hardware.org/?probe=61dcde6523) | Mar 22, 2023 |
| Dell          | Latitude E7470              | Notebook    | [9595c39422](https://linux-hardware.org/?probe=9595c39422) | Mar 22, 2023 |
| Sony          | VGN-NW270F                  | Notebook    | [48080babd0](https://linux-hardware.org/?probe=48080babd0) | Mar 22, 2023 |
| MSI           | GE70 2PE                    | Notebook    | [5e68fcc30d](https://linux-hardware.org/?probe=5e68fcc30d) | Mar 22, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [ae63ffa582](https://linux-hardware.org/?probe=ae63ffa582) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [2da4187f91](https://linux-hardware.org/?probe=2da4187f91) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [d9c0447b0d](https://linux-hardware.org/?probe=d9c0447b0d) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [293e9a941a](https://linux-hardware.org/?probe=293e9a941a) | Mar 20, 2023 |
| HP            | ProBook 640 G4              | Notebook    | [2787c4bf42](https://linux-hardware.org/?probe=2787c4bf42) | Mar 20, 2023 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [0cfaf0934d](https://linux-hardware.org/?probe=0cfaf0934d) | Mar 20, 2023 |
| HP            | 21F5                        | Desktop     | [865a85e5bc](https://linux-hardware.org/?probe=865a85e5bc) | Mar 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [83fbe3a3d6](https://linux-hardware.org/?probe=83fbe3a3d6) | Mar 20, 2023 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [ede048bc5d](https://linux-hardware.org/?probe=ede048bc5d) | Mar 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [a71c5a4629](https://linux-hardware.org/?probe=a71c5a4629) | Mar 19, 2023 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [619a36ed2f](https://linux-hardware.org/?probe=619a36ed2f) | Mar 19, 2023 |
| Intel         | DH67BL AAG10189-208         | Desktop     | [420f476f82](https://linux-hardware.org/?probe=420f476f82) | Mar 19, 2023 |
| ASUSTek       | T300CHI                     | Notebook    | [371961ad53](https://linux-hardware.org/?probe=371961ad53) | Mar 19, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [5e5fd3788e](https://linux-hardware.org/?probe=5e5fd3788e) | Mar 19, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [efaf7d4a30](https://linux-hardware.org/?probe=efaf7d4a30) | Mar 18, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [99e92fa4df](https://linux-hardware.org/?probe=99e92fa4df) | Mar 18, 2023 |
| Avell High... | C62 MOB                     | Notebook    | [7eaededaac](https://linux-hardware.org/?probe=7eaededaac) | Mar 18, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [8cf99eb521](https://linux-hardware.org/?probe=8cf99eb521) | Mar 18, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [c70e1d7e98](https://linux-hardware.org/?probe=c70e1d7e98) | Mar 18, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [5a429f93a7](https://linux-hardware.org/?probe=5a429f93a7) | Mar 18, 2023 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [ef3e267972](https://linux-hardware.org/?probe=ef3e267972) | Mar 18, 2023 |
| Clevo         | W340EU                      | Notebook    | [b90ad98b0a](https://linux-hardware.org/?probe=b90ad98b0a) | Mar 18, 2023 |
| HP            | 8266                        | Desktop     | [8bac7f79e8](https://linux-hardware.org/?probe=8bac7f79e8) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [786fded1ce](https://linux-hardware.org/?probe=786fded1ce) | Mar 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e0fa4709db](https://linux-hardware.org/?probe=e0fa4709db) | Mar 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3e5167941c](https://linux-hardware.org/?probe=3e5167941c) | Mar 17, 2023 |
| Clevo         | W340EU                      | Notebook    | [240779648a](https://linux-hardware.org/?probe=240779648a) | Mar 17, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [9ca1015389](https://linux-hardware.org/?probe=9ca1015389) | Mar 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [1ed7ccd033](https://linux-hardware.org/?probe=1ed7ccd033) | Mar 16, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [d1edfbc4b3](https://linux-hardware.org/?probe=d1edfbc4b3) | Mar 16, 2023 |
| Acer          | Aspire M3920                | Desktop     | [bb2e9ec8a1](https://linux-hardware.org/?probe=bb2e9ec8a1) | Mar 16, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [697914b165](https://linux-hardware.org/?probe=697914b165) | Mar 16, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [69f39892c4](https://linux-hardware.org/?probe=69f39892c4) | Mar 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [b20f8089c3](https://linux-hardware.org/?probe=b20f8089c3) | Mar 15, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [0ace5375f4](https://linux-hardware.org/?probe=0ace5375f4) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [fbbcc2d2c5](https://linux-hardware.org/?probe=fbbcc2d2c5) | Mar 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [b0b8ac79d9](https://linux-hardware.org/?probe=b0b8ac79d9) | Mar 15, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [8fff8ca97d](https://linux-hardware.org/?probe=8fff8ca97d) | Mar 15, 2023 |
| Lenovo        | ThinkPad E480 20KNA01HIG    | Notebook    | [c8054d1090](https://linux-hardware.org/?probe=c8054d1090) | Mar 15, 2023 |
| Supermicro    | X9DRD-C/iT+                 | Desktop     | [57c78aa4db](https://linux-hardware.org/?probe=57c78aa4db) | Mar 15, 2023 |
| Toshiba       | QOSMIO X70-A                | Notebook    | [f85336fbca](https://linux-hardware.org/?probe=f85336fbca) | Mar 15, 2023 |
| HP            | ZBook 15                    | Notebook    | [ebc4b1e01e](https://linux-hardware.org/?probe=ebc4b1e01e) | Mar 14, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [f424a1dc42](https://linux-hardware.org/?probe=f424a1dc42) | Mar 14, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [b5ef4ae548](https://linux-hardware.org/?probe=b5ef4ae548) | Mar 14, 2023 |
| HP            | 2B52                        | Desktop     | [b541e6085e](https://linux-hardware.org/?probe=b541e6085e) | Mar 14, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [783ff991d4](https://linux-hardware.org/?probe=783ff991d4) | Mar 14, 2023 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [c5a25ab496](https://linux-hardware.org/?probe=c5a25ab496) | Mar 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [21fc92246e](https://linux-hardware.org/?probe=21fc92246e) | Mar 13, 2023 |
| MSI           | B85-G43                     | Desktop     | [7e9ce07cb8](https://linux-hardware.org/?probe=7e9ce07cb8) | Mar 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [3c4e911c6d](https://linux-hardware.org/?probe=3c4e911c6d) | Mar 13, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e79cdeaf10](https://linux-hardware.org/?probe=e79cdeaf10) | Mar 13, 2023 |
| MSI           | B85-G43                     | Desktop     | [9a9a70ade3](https://linux-hardware.org/?probe=9a9a70ade3) | Mar 13, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [007f595264](https://linux-hardware.org/?probe=007f595264) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [57000f8a86](https://linux-hardware.org/?probe=57000f8a86) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [456057e6af](https://linux-hardware.org/?probe=456057e6af) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [7ee93079fb](https://linux-hardware.org/?probe=7ee93079fb) | Mar 13, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [11116a9517](https://linux-hardware.org/?probe=11116a9517) | Mar 13, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [6a0673f946](https://linux-hardware.org/?probe=6a0673f946) | Mar 13, 2023 |
| ASRockRack    | ROMED6U-2L2T                | Desktop     | [1af076312d](https://linux-hardware.org/?probe=1af076312d) | Mar 12, 2023 |
| Dell          | Latitude E6420              | Notebook    | [6fe2914b41](https://linux-hardware.org/?probe=6fe2914b41) | Mar 12, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [60bc8c1ef5](https://linux-hardware.org/?probe=60bc8c1ef5) | Mar 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [4ee87a1213](https://linux-hardware.org/?probe=4ee87a1213) | Mar 12, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [77b7a9348b](https://linux-hardware.org/?probe=77b7a9348b) | Mar 12, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [d550e765ac](https://linux-hardware.org/?probe=d550e765ac) | Mar 12, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [f2ffca7459](https://linux-hardware.org/?probe=f2ffca7459) | Mar 12, 2023 |
| MSI           | MAG B660M BAZOOKA DDR4      | Desktop     | [cb1be19cd3](https://linux-hardware.org/?probe=cb1be19cd3) | Mar 11, 2023 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | Notebook    | [bcbf6544cd](https://linux-hardware.org/?probe=bcbf6544cd) | Mar 11, 2023 |
| MSI           | B85-G43                     | Desktop     | [47ac638c2e](https://linux-hardware.org/?probe=47ac638c2e) | Mar 11, 2023 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [1b49e21822](https://linux-hardware.org/?probe=1b49e21822) | Mar 11, 2023 |
| HP            | 0AACh                       | Desktop     | [83f0c7df93](https://linux-hardware.org/?probe=83f0c7df93) | Mar 10, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [d039d459d7](https://linux-hardware.org/?probe=d039d459d7) | Mar 10, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [9f02108ada](https://linux-hardware.org/?probe=9f02108ada) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [5a0eb5bfed](https://linux-hardware.org/?probe=5a0eb5bfed) | Mar 09, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [2750a8a462](https://linux-hardware.org/?probe=2750a8a462) | Mar 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [b7fd2dfa30](https://linux-hardware.org/?probe=b7fd2dfa30) | Mar 09, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f658e58c98](https://linux-hardware.org/?probe=f658e58c98) | Mar 09, 2023 |
| Dell          | Inspiron 15-3565            | Notebook    | [a71845e346](https://linux-hardware.org/?probe=a71845e346) | Mar 09, 2023 |
| ASUSTek       | ZenBook UX463FL_UX463FL     | Convertible | [8fbb4566ac](https://linux-hardware.org/?probe=8fbb4566ac) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [2b74ad2ed1](https://linux-hardware.org/?probe=2b74ad2ed1) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [e777d1af00](https://linux-hardware.org/?probe=e777d1af00) | Mar 08, 2023 |
| Maibenben     | JinMai6 series              | Notebook    | [ace44d9872](https://linux-hardware.org/?probe=ace44d9872) | Mar 08, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [fdc9f52c81](https://linux-hardware.org/?probe=fdc9f52c81) | Mar 08, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [7bd6e95116](https://linux-hardware.org/?probe=7bd6e95116) | Mar 08, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [d3cd7ae3e8](https://linux-hardware.org/?probe=d3cd7ae3e8) | Mar 07, 2023 |
| Lenovo        | IdeaPad C340-14IWL 81RL     | Convertible | [9625716631](https://linux-hardware.org/?probe=9625716631) | Mar 07, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [b48c76be97](https://linux-hardware.org/?probe=b48c76be97) | Mar 07, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [22569ee1f4](https://linux-hardware.org/?probe=22569ee1f4) | Mar 07, 2023 |
| HP            | ENVY TS 17                  | Notebook    | [c915d51f5e](https://linux-hardware.org/?probe=c915d51f5e) | Mar 07, 2023 |
| Datto         | 1000                        | Notebook    | [9df2913c36](https://linux-hardware.org/?probe=9df2913c36) | Mar 07, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [2f8d0ff7f5](https://linux-hardware.org/?probe=2f8d0ff7f5) | Mar 06, 2023 |
| ASUSTek       | K52JT                       | Notebook    | [802fe86b5c](https://linux-hardware.org/?probe=802fe86b5c) | Mar 06, 2023 |
| Alienware     | x14                         | Notebook    | [a1665c85ab](https://linux-hardware.org/?probe=a1665c85ab) | Mar 06, 2023 |
| Alienware     | x14                         | Notebook    | [8f12fe3ee5](https://linux-hardware.org/?probe=8f12fe3ee5) | Mar 06, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [ca2ad0edee](https://linux-hardware.org/?probe=ca2ad0edee) | Mar 05, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [6db57d4d9f](https://linux-hardware.org/?probe=6db57d4d9f) | Mar 05, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [28dbdcfbb7](https://linux-hardware.org/?probe=28dbdcfbb7) | Mar 05, 2023 |
| Dell          | Latitude E6420              | Notebook    | [569d016799](https://linux-hardware.org/?probe=569d016799) | Mar 05, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [2311f1da09](https://linux-hardware.org/?probe=2311f1da09) | Mar 05, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [483a11d21e](https://linux-hardware.org/?probe=483a11d21e) | Mar 05, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [8805f0bce5](https://linux-hardware.org/?probe=8805f0bce5) | Mar 05, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7d43df02db](https://linux-hardware.org/?probe=7d43df02db) | Mar 04, 2023 |
| HP            | 89B5 A                      | Desktop     | [b1f4e34d2d](https://linux-hardware.org/?probe=b1f4e34d2d) | Mar 04, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [63e9a399f8](https://linux-hardware.org/?probe=63e9a399f8) | Mar 04, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [8a4cc5192e](https://linux-hardware.org/?probe=8a4cc5192e) | Mar 04, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [a7860ee046](https://linux-hardware.org/?probe=a7860ee046) | Mar 04, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [c654c1809d](https://linux-hardware.org/?probe=c654c1809d) | Mar 04, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [5a15c4c2b0](https://linux-hardware.org/?probe=5a15c4c2b0) | Mar 03, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [9a3c215b30](https://linux-hardware.org/?probe=9a3c215b30) | Mar 03, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [fdee05953f](https://linux-hardware.org/?probe=fdee05953f) | Mar 03, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [a5939aa47c](https://linux-hardware.org/?probe=a5939aa47c) | Mar 03, 2023 |
| Dell          | Latitude 5420               | Notebook    | [b763e54ded](https://linux-hardware.org/?probe=b763e54ded) | Mar 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [4d68c19c3e](https://linux-hardware.org/?probe=4d68c19c3e) | Mar 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [6c007c983c](https://linux-hardware.org/?probe=6c007c983c) | Mar 02, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [82847b3b1f](https://linux-hardware.org/?probe=82847b3b1f) | Mar 02, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [cc8c299b5d](https://linux-hardware.org/?probe=cc8c299b5d) | Mar 01, 2023 |
| Dell          | 05R2TK A01                  | All in one  | [efa9d9069d](https://linux-hardware.org/?probe=efa9d9069d) | Mar 01, 2023 |
| Pegatron      | SM3330B 0500B               | Desktop     | [7ec6d4d881](https://linux-hardware.org/?probe=7ec6d4d881) | Mar 01, 2023 |
| Gigabyte      | X58A-UD7                    | Desktop     | [727ce4b27e](https://linux-hardware.org/?probe=727ce4b27e) | Mar 01, 2023 |
| Gigabyte      | X58A-UD7                    | Desktop     | [bbc9bc409c](https://linux-hardware.org/?probe=bbc9bc409c) | Mar 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [131f94f213](https://linux-hardware.org/?probe=131f94f213) | Mar 01, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ecfa5f6c27](https://linux-hardware.org/?probe=ecfa5f6c27) | Mar 01, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [8fd450db03](https://linux-hardware.org/?probe=8fd450db03) | Feb 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [41439f6b61](https://linux-hardware.org/?probe=41439f6b61) | Feb 28, 2023 |
| Dell          | Latitude 5530               | Notebook    | [f892221e4c](https://linux-hardware.org/?probe=f892221e4c) | Feb 27, 2023 |
| ASRock        | Z790 PG Lightning           | Desktop     | [86c7144757](https://linux-hardware.org/?probe=86c7144757) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [003aa3d3e9](https://linux-hardware.org/?probe=003aa3d3e9) | Feb 27, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [aa26becbb1](https://linux-hardware.org/?probe=aa26becbb1) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [ad20f98122](https://linux-hardware.org/?probe=ad20f98122) | Feb 27, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [a2af33e0e3](https://linux-hardware.org/?probe=a2af33e0e3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [a5f5bdc903](https://linux-hardware.org/?probe=a5f5bdc903) | Feb 26, 2023 |
| Gigabyte      | B360M HD3                   | Desktop     | [d3821bdbab](https://linux-hardware.org/?probe=d3821bdbab) | Feb 26, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [d6e0c6c0ac](https://linux-hardware.org/?probe=d6e0c6c0ac) | Feb 26, 2023 |
| ASRock        | G41C-GS                     | Desktop     | [6a698dda57](https://linux-hardware.org/?probe=6a698dda57) | Feb 26, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [575e6a8c55](https://linux-hardware.org/?probe=575e6a8c55) | Feb 26, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [8bfe7e434d](https://linux-hardware.org/?probe=8bfe7e434d) | Feb 26, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | Notebook    | [b410d220e6](https://linux-hardware.org/?probe=b410d220e6) | Feb 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [67b8b5ad09](https://linux-hardware.org/?probe=67b8b5ad09) | Feb 26, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [c872892cfd](https://linux-hardware.org/?probe=c872892cfd) | Feb 26, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c6ca9e8499](https://linux-hardware.org/?probe=c6ca9e8499) | Feb 26, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [bd6c07d84d](https://linux-hardware.org/?probe=bd6c07d84d) | Feb 26, 2023 |
| HP            | G62                         | Notebook    | [871207750c](https://linux-hardware.org/?probe=871207750c) | Feb 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [2943aa6cd7](https://linux-hardware.org/?probe=2943aa6cd7) | Feb 25, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [0b9491b3a0](https://linux-hardware.org/?probe=0b9491b3a0) | Feb 25, 2023 |
| ASRock        | H97 Pro4                    | Desktop     | [f703af2e6b](https://linux-hardware.org/?probe=f703af2e6b) | Feb 25, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [844de888cd](https://linux-hardware.org/?probe=844de888cd) | Feb 25, 2023 |
| System76      | Gazelle                     | Notebook    | [64fcb063eb](https://linux-hardware.org/?probe=64fcb063eb) | Feb 25, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e7bf168729](https://linux-hardware.org/?probe=e7bf168729) | Feb 25, 2023 |
| Alienware     | m15 R7 AMD                  | Notebook    | [0a44dcc29e](https://linux-hardware.org/?probe=0a44dcc29e) | Feb 24, 2023 |
| Dell          | Latitude 5530               | Notebook    | [8ad26dd8a0](https://linux-hardware.org/?probe=8ad26dd8a0) | Feb 24, 2023 |
| Alienware     | m15 R7 AMD                  | Notebook    | [3ba05d49d8](https://linux-hardware.org/?probe=3ba05d49d8) | Feb 24, 2023 |
| ASRock        | M3A770DE                    | Desktop     | [b025c7a092](https://linux-hardware.org/?probe=b025c7a092) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [463265c999](https://linux-hardware.org/?probe=463265c999) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [4aec81f692](https://linux-hardware.org/?probe=4aec81f692) | Feb 24, 2023 |
| MSI           | GE75 Raider 9SE             | Notebook    | [6d0782da8e](https://linux-hardware.org/?probe=6d0782da8e) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [471b84b6d4](https://linux-hardware.org/?probe=471b84b6d4) | Feb 23, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [2f9c2ec647](https://linux-hardware.org/?probe=2f9c2ec647) | Feb 23, 2023 |
| Samsung       | 950QDB                      | Convertible | [2545626207](https://linux-hardware.org/?probe=2545626207) | Feb 23, 2023 |
| Dell          | 0PC5F7 A03                  | Desktop     | [27f07447f7](https://linux-hardware.org/?probe=27f07447f7) | Feb 23, 2023 |
| Shuttle       | FL10J                       | Desktop     | [943316a9c5](https://linux-hardware.org/?probe=943316a9c5) | Feb 22, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [c81213c25e](https://linux-hardware.org/?probe=c81213c25e) | Feb 22, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [4a3b8e0755](https://linux-hardware.org/?probe=4a3b8e0755) | Feb 22, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [acb8644ede](https://linux-hardware.org/?probe=acb8644ede) | Feb 21, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d6ec8781f4](https://linux-hardware.org/?probe=d6ec8781f4) | Feb 21, 2023 |
| MSI           | B85-G43                     | Desktop     | [62273631b2](https://linux-hardware.org/?probe=62273631b2) | Feb 21, 2023 |
| Dell          | 01TN68 A02                  | Desktop     | [ce7bdb1ddf](https://linux-hardware.org/?probe=ce7bdb1ddf) | Feb 21, 2023 |
| Lenovo        | ThinkPad T440p 20AWS3E20... | Notebook    | [012b54b31c](https://linux-hardware.org/?probe=012b54b31c) | Feb 21, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [0d286f12f4](https://linux-hardware.org/?probe=0d286f12f4) | Feb 21, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [5fa20b737f](https://linux-hardware.org/?probe=5fa20b737f) | Feb 21, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [39718b8983](https://linux-hardware.org/?probe=39718b8983) | Feb 20, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [6033e6cb63](https://linux-hardware.org/?probe=6033e6cb63) | Feb 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [63de5bef96](https://linux-hardware.org/?probe=63de5bef96) | Feb 20, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Kubuntu 20.04   | 1412      | 33.44%  |
| Kubuntu 22.04   | 1000      | 23.69%  |
| Kubuntu 22.10   | 297       | 7.03%   |
| Kubuntu 20.10   | 256       | 6.06%   |
| Kubuntu 21.10   | 242       | 5.73%   |
| Kubuntu 23.04   | 230       | 5.45%   |
| Kubuntu 21.04   | 214       | 5.07%   |
| Kubuntu 18.04   | 201       | 4.76%   |
| Kubuntu 19.10   | 178       | 4.22%   |
| Kubuntu 11      | 95        | 2.25%   |
| Kubuntu 11.1    | 26        | 0.62%   |
| Kubuntu 19.04   | 22        | 0.52%   |
| Kubuntu 16.04   | 13        | 0.31%   |
| Kubuntu         | 8         | 0.19%   |
| Kubuntu 18.10   | 7         | 0.17%   |
| Kubuntu 23.10   | 6         | 0.14%   |
| Kubuntu 2.0     | 6         | 0.14%   |
| Kubuntu 17.10   | 3         | 0.07%   |
| Kubuntu 17.04   | 2         | 0.05%   |
| Kubuntu 14.04   | 2         | 0.05%   |
| Kubuntu 20.08.3 | 1         | 0.02%   |
| Kubuntu 12.04   | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Kubuntu | 4029      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 103       | 2.22%   |
| 5.15.0-52-generic | 84        | 1.81%   |
| 5.15.0-56-generic | 80        | 1.72%   |
| 6.2.0-20-generic  | 78        | 1.68%   |
| 5.19.0-35-generic | 70        | 1.51%   |
| 5.4.0-52-generic  | 68        | 1.47%   |
| 5.4.0-58-generic  | 59        | 1.27%   |
| 5.4.0-48-generic  | 59        | 1.27%   |
| 5.15.0-48-generic | 58        | 1.25%   |
| 5.15.0-46-generic | 53        | 1.14%   |
| 5.13.0-39-generic | 53        | 1.14%   |
| 5.19.0-23-generic | 52        | 1.12%   |
| 6.2.0-26-generic  | 49        | 1.06%   |
| 5.4.0-40-generic  | 47        | 1.01%   |
| 5.19.0-38-generic | 47        | 1.01%   |
| 5.13.0-28-generic | 44        | 0.95%   |
| 5.19.0-31-generic | 43        | 0.93%   |
| 5.19.0-26-generic | 42        | 0.91%   |
| 5.15.0-58-generic | 42        | 0.91%   |
| 5.15.0-43-generic | 42        | 0.91%   |
| 5.15.0-47-generic | 41        | 0.88%   |
| 5.15.0-41-generic | 39        | 0.84%   |
| 5.11.0-37-generic | 38        | 0.82%   |
| 5.11.0-25-generic | 38        | 0.82%   |
| 5.15.0-53-generic | 37        | 0.8%    |
| 5.13.0-30-generic | 37        | 0.8%    |
| 5.4.0-47-generic  | 36        | 0.78%   |
| 5.4.0-65-generic  | 35        | 0.75%   |
| 5.8.0-48-generic  | 34        | 0.73%   |
| 5.3.0-40-generic  | 34        | 0.73%   |
| 5.4.0-37-generic  | 33        | 0.71%   |
| 5.4.0-29-generic  | 33        | 0.71%   |
| 5.19.0-29-generic | 32        | 0.69%   |
| 5.15.0-60-generic | 32        | 0.69%   |
| 5.13.0-22-generic | 32        | 0.69%   |
| 5.4.0-45-generic  | 30        | 0.65%   |
| 5.8.0-50-generic  | 29        | 0.63%   |
| 5.15.0-67-generic | 29        | 0.63%   |
| 5.13.0-35-generic | 29        | 0.63%   |
| 5.8.0-63-generic  | 28        | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 943       | 21.93%  |
| 5.15.0  | 853       | 19.84%  |
| 5.19.0  | 444       | 10.33%  |
| 5.13.0  | 409       | 9.51%   |
| 5.8.0   | 406       | 9.44%   |
| 5.11.0  | 327       | 7.6%    |
| 6.2.0   | 239       | 5.56%   |
| 5.3.0   | 224       | 5.21%   |
| 4.15.0  | 69        | 1.6%    |
| 5.0.0   | 36        | 0.84%   |
| 5.17.0  | 21        | 0.49%   |
| 5.10.0  | 18        | 0.42%   |
| 5.6.0   | 15        | 0.35%   |
| 4.4.0   | 10        | 0.23%   |
| 6.1.0   | 9         | 0.21%   |
| 6.0.0   | 9         | 0.21%   |
| 5.14.0  | 8         | 0.19%   |
| 4.18.0  | 8         | 0.19%   |
| 6.0.9   | 6         | 0.14%   |
| 6.3.0   | 5         | 0.12%   |
| 5.9.0   | 5         | 0.12%   |
| 6.4.0   | 4         | 0.09%   |
| 5.7.0   | 4         | 0.09%   |
| 6.4.8   | 3         | 0.07%   |
| 6.4.10  | 3         | 0.07%   |
| 6.3.8   | 3         | 0.07%   |
| 6.3.6   | 3         | 0.07%   |
| 6.3.1   | 3         | 0.07%   |
| 6.1.5   | 3         | 0.07%   |
| 5.8.18  | 3         | 0.07%   |
| 5.18.4  | 3         | 0.07%   |
| 5.18.10 | 3         | 0.07%   |
| 5.16.0  | 3         | 0.07%   |
| 5.12.8  | 3         | 0.07%   |
| 5.12.0  | 3         | 0.07%   |
| 4.13.0  | 3         | 0.07%   |
| 4.10.0  | 3         | 0.07%   |
| 6.3.7   | 2         | 0.05%   |
| 6.3.4   | 2         | 0.05%   |
| 6.2.5   | 2         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 950       | 22.13%  |
| 5.15    | 867       | 20.2%   |
| 5.19    | 450       | 10.48%  |
| 5.8     | 422       | 9.83%   |
| 5.13    | 419       | 9.76%   |
| 5.11    | 333       | 7.76%   |
| 6.2     | 247       | 5.75%   |
| 5.3     | 227       | 5.29%   |
| 4.15    | 70        | 1.63%   |
| 5.0     | 37        | 0.86%   |
| 5.10    | 30        | 0.7%    |
| 5.17    | 28        | 0.65%   |
| 6.1     | 25        | 0.58%   |
| 6.3     | 22        | 0.51%   |
| 6.0     | 21        | 0.49%   |
| 5.6     | 20        | 0.47%   |
| 5.14    | 17        | 0.4%    |
| 6.4     | 13        | 0.3%    |
| 5.9     | 13        | 0.3%    |
| 5.12    | 13        | 0.3%    |
| 5.18    | 12        | 0.28%   |
| 5.7     | 11        | 0.26%   |
| 5.16    | 10        | 0.23%   |
| 4.4     | 10        | 0.23%   |
| 4.18    | 10        | 0.23%   |
| 5.5     | 5         | 0.12%   |
| 4.13    | 3         | 0.07%   |
| 4.10    | 3         | 0.07%   |
| 5.1     | 2         | 0.05%   |
| 4.17    | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |
| 3.13    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4010      | 99.53%  |
| i686    | 12        | 0.3%    |
| aarch64 | 5         | 0.12%   |
| riscv64 | 2         | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 3120      | 76.13%  |
| KDE        | 918       | 22.4%   |
| GNOME      | 21        | 0.51%   |
| Cinnamon   | 11        | 0.27%   |
| Budgie     | 8         | 0.2%    |
| MATE       | 6         | 0.15%   |
| XFCE       | 3         | 0.07%   |
| LXQt       | 3         | 0.07%   |
| KDE4       | 3         | 0.07%   |
| X-Cinnamon | 1         | 0.02%   |
| Unity      | 1         | 0.02%   |
| i3         | 1         | 0.02%   |
| GNUstep    | 1         | 0.02%   |
| Unknown    | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3846      | 94.87%  |
| Wayland | 160       | 3.95%   |
| Tty     | 47        | 1.16%   |
| Web     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 2421      | 58.95%  |
| Unknown | 1403      | 34.16%  |
| GDM     | 112       | 2.73%   |
| GDM3    | 77        | 1.87%   |
| LightDM | 70        | 1.7%    |
| TDM     | 21        | 0.51%   |
| SLiM    | 2         | 0.05%   |
| LXDM    | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1742      | 42.85%  |
| de_DE   | 342       | 8.41%   |
| ru_RU   | 207       | 5.09%   |
| en_GB   | 199       | 4.9%    |
| fr_FR   | 181       | 4.45%   |
| pt_BR   | 172       | 4.23%   |
| it_IT   | 166       | 4.08%   |
| en_CA   | 84        | 2.07%   |
| es_ES   | 81        | 1.99%   |
| Unknown | 77        | 1.89%   |
| en_AU   | 76        | 1.87%   |
| pl_PL   | 74        | 1.82%   |
| en_IN   | 72        | 1.77%   |
| C       | 46        | 1.13%   |
| hu_HU   | 30        | 0.74%   |
| es_MX   | 27        | 0.66%   |
| en_ZA   | 24        | 0.59%   |
| cs_CZ   | 24        | 0.59%   |
| ru_UA   | 23        | 0.57%   |
| nl_NL   | 23        | 0.57%   |
| es_AR   | 23        | 0.57%   |
| de_AT   | 21        | 0.52%   |
| en_NZ   | 18        | 0.44%   |
| tr_TR   | 15        | 0.37%   |
| de_CH   | 14        | 0.34%   |
| zh_CN   | 13        | 0.32%   |
| sv_SE   | 13        | 0.32%   |
| pt_PT   | 12        | 0.3%    |
| es_CO   | 12        | 0.3%    |
| es_CL   | 11        | 0.27%   |
| en_IE   | 11        | 0.27%   |
| el_GR   | 11        | 0.27%   |
| fr_BE   | 10        | 0.25%   |
| fi_FI   | 10        | 0.25%   |
| en_PH   | 10        | 0.25%   |
| es_VE   | 9         | 0.22%   |
| en_IL   | 9         | 0.22%   |
| uk_UA   | 8         | 0.2%    |
| nl_BE   | 8         | 0.2%    |
| sl_SI   | 7         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2236      | 54.62%  |
| BIOS | 1858      | 45.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3619      | 88.98%  |
| Btrfs    | 162       | 3.98%   |
| Overlay  | 102       | 2.51%   |
| Tmpfs    | 97        | 2.39%   |
| Xfs      | 40        | 0.98%   |
| Zfs      | 21        | 0.52%   |
| Unknown  | 12        | 0.3%    |
| Ext3     | 5         | 0.12%   |
| Ext2     | 4         | 0.1%    |
| XXXX     | 1         | 0.02%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |
| F2fs     | 1         | 0.02%   |
| ExX4     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2096      | 51.1%   |
| Unknown | 1642      | 40.03%  |
| MBR     | 364       | 8.87%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3536      | 86.79%  |
| Yes       | 538       | 13.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2530      | 62.07%  |
| Yes       | 1546      | 37.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 662       | 16.43%  |
| Lenovo              | 617       | 15.31%  |
| Dell                | 550       | 13.65%  |
| Hewlett-Packard     | 535       | 13.28%  |
| Gigabyte Technology | 321       | 7.97%   |
| MSI                 | 273       | 6.78%   |
| Acer                | 187       | 4.64%   |
| ASRock              | 142       | 3.52%   |
| Apple               | 61        | 1.51%   |
| Intel               | 49        | 1.22%   |
| Samsung Electronics | 48        | 1.19%   |
| HUAWEI              | 46        | 1.14%   |
| Unknown             | 32        | 0.79%   |
| Toshiba             | 27        | 0.67%   |
| Notebook            | 25        | 0.62%   |
| Google              | 25        | 0.62%   |
| Fujitsu             | 25        | 0.62%   |
| Sony                | 22        | 0.55%   |
| TUXEDO              | 19        | 0.47%   |
| Alienware           | 17        | 0.42%   |
| Pegatron            | 15        | 0.37%   |
| Medion              | 15        | 0.37%   |
| Timi                | 13        | 0.32%   |
| Positivo            | 13        | 0.32%   |
| Biostar             | 13        | 0.32%   |
| AZW                 | 13        | 0.32%   |
| Packard Bell        | 10        | 0.25%   |
| Microsoft           | 10        | 0.25%   |
| Foxconn             | 10        | 0.25%   |
| Supermicro          | 9         | 0.22%   |
| ZOTAC               | 8         | 0.2%    |
| System76            | 8         | 0.2%    |
| PC Specialist       | 8         | 0.2%    |
| ECS                 | 8         | 0.2%    |
| Chuwi               | 8         | 0.2%    |
| LG Electronics      | 7         | 0.17%   |
| GPU Company         | 7         | 0.17%   |
| Shuttle             | 6         | 0.15%   |
| Razer               | 6         | 0.15%   |
| Huanan              | 6         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 47        | 1.17%   |
| Unknown                            | 46        | 1.14%   |
| ASUS ROG STRIX B550-F GAMING       | 12        | 0.3%    |
| Gigabyte B450M DS3H                | 11        | 0.27%   |
| HP Notebook                        | 10        | 0.25%   |
| MSI MS-7C37                        | 9         | 0.22%   |
| MSI MS-7B79                        | 9         | 0.22%   |
| HP Pavilion g6                     | 9         | 0.22%   |
| HP Pavilion dv6                    | 9         | 0.22%   |
| Dell XPS 15 9560                   | 9         | 0.22%   |
| Dell OptiPlex 9020                 | 9         | 0.22%   |
| Dell OptiPlex 7010                 | 9         | 0.22%   |
| HUAWEI NBLK-WAX9X                  | 8         | 0.2%    |
| Gigabyte A320M-S2H                 | 8         | 0.2%    |
| ASUS ROG STRIX X570-E GAMING       | 8         | 0.2%    |
| ASUS PRIME B350-PLUS               | 8         | 0.2%    |
| ASUS PRIME A320M-K                 | 8         | 0.2%    |
| MSI MS-7C91                        | 7         | 0.17%   |
| MSI MS-7817                        | 7         | 0.17%   |
| HP Pavilion dv7                    | 7         | 0.17%   |
| HP Pavilion 15                     | 7         | 0.17%   |
| HP ENVY x360 Convertible 13-ay0xxx | 7         | 0.17%   |
| HP EliteBook 840 G5                | 7         | 0.17%   |
| Gigabyte X570 AORUS MASTER         | 7         | 0.17%   |
| Gigabyte 970A-DS3P                 | 7         | 0.17%   |
| Dell XPS 15 9570                   | 7         | 0.17%   |
| ASUS TUF Gaming B550-PLUS          | 7         | 0.17%   |
| ASUS PRIME B450M-A                 | 7         | 0.17%   |
| MSI MS-7C56                        | 6         | 0.15%   |
| MSI MS-7A34                        | 6         | 0.15%   |
| MSI MS-7693                        | 6         | 0.15%   |
| HUAWEI HVY-WXX9                    | 6         | 0.15%   |
| HP EliteBook 840 G6                | 6         | 0.15%   |
| HP EliteBook 840 G3                | 6         | 0.15%   |
| Dell XPS 15 7590                   | 6         | 0.15%   |
| Dell Latitude 5480                 | 6         | 0.15%   |
| AZW SER                            | 6         | 0.15%   |
| ASUS TUF Gaming X570-PLUS          | 6         | 0.15%   |
| ASRock A320M-HDV R4.0              | 6         | 0.15%   |
| MSI MS-7C95                        | 5         | 0.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 282       | 7%      |
| Dell Latitude      | 149       | 3.7%    |
| Dell Inspiron      | 131       | 3.25%   |
| Acer Aspire        | 119       | 2.95%   |
| Lenovo IdeaPad     | 116       | 2.88%   |
| HP Pavilion        | 105       | 2.61%   |
| ASUS PRIME         | 93        | 2.31%   |
| ASUS ROG           | 92        | 2.28%   |
| Dell XPS           | 82        | 2.04%   |
| HP EliteBook       | 67        | 1.66%   |
| HP ProBook         | 66        | 1.64%   |
| Dell Precision     | 60        | 1.49%   |
| HP Laptop          | 55        | 1.37%   |
| Dell OptiPlex      | 55        | 1.37%   |
| ASUS VivoBook      | 54        | 1.34%   |
| ASUS TUF           | 49        | 1.22%   |
| ASUS All           | 47        | 1.17%   |
| Unknown            | 46        | 1.14%   |
| Lenovo ThinkCentre | 37        | 0.92%   |
| HP ENVY            | 35        | 0.87%   |
| HP Compaq          | 33        | 0.82%   |
| Lenovo Yoga        | 32        | 0.79%   |
| Dell Vostro        | 32        | 0.79%   |
| Lenovo Legion      | 29        | 0.72%   |
| Acer Nitro         | 26        | 0.65%   |
| ASUS ASUS          | 25        | 0.62%   |
| Toshiba Satellite  | 23        | 0.57%   |
| Lenovo ThinkBook   | 23        | 0.57%   |
| ASUS ZenBook       | 20        | 0.5%    |
| Gigabyte B450M     | 19        | 0.47%   |
| Gigabyte X570      | 18        | 0.45%   |
| Acer Swift         | 18        | 0.45%   |
| HP ZBook           | 16        | 0.4%    |
| Gigabyte B550      | 14        | 0.35%   |
| HP Spectre         | 12        | 0.3%    |
| HP EliteDesk       | 12        | 0.3%    |
| Gigabyte A320M-S2H | 12        | 0.3%    |
| Dell G3            | 12        | 0.3%    |
| Fujitsu ESPRIMO    | 11        | 0.27%   |
| ASUS M5A78L-M      | 11        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 497       | 12.34%  |
| 2019    | 467       | 11.59%  |
| 2018    | 435       | 10.8%   |
| 2021    | 370       | 9.18%   |
| 2017    | 292       | 7.25%   |
| 2012    | 273       | 6.78%   |
| 2013    | 264       | 6.55%   |
| 2014    | 237       | 5.88%   |
| 2011    | 231       | 5.73%   |
| 2016    | 189       | 4.69%   |
| 2015    | 183       | 4.54%   |
| 2022    | 174       | 4.32%   |
| 2010    | 133       | 3.3%    |
| 2008    | 100       | 2.48%   |
| 2009    | 96        | 2.38%   |
| 2007    | 39        | 0.97%   |
| 2023    | 29        | 0.72%   |
| 2006    | 9         | 0.22%   |
| Unknown | 7         | 0.17%   |
| 2005    | 3         | 0.07%   |
| 2004    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2225      | 55.22%  |
| Desktop        | 1506      | 37.38%  |
| Convertible    | 141       | 3.5%    |
| Mini pc        | 63        | 1.56%   |
| All in one     | 44        | 1.09%   |
| Tablet         | 28        | 0.69%   |
| Server         | 16        | 0.4%    |
| System on chip | 5         | 0.12%   |
| Stick pc       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3698      | 91.2%   |
| Enabled  | 357       | 8.8%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3997      | 99.21%  |
| Yes  | 32        | 0.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1046      | 25.72%  |
| 4.01-8.0        | 893       | 21.96%  |
| 8.01-16.0       | 748       | 18.39%  |
| 32.01-64.0      | 574       | 14.11%  |
| 3.01-4.0        | 462       | 11.36%  |
| 64.01-256.0     | 149       | 3.66%   |
| 24.01-32.0      | 113       | 2.78%   |
| 1.01-2.0        | 55        | 1.35%   |
| 2.01-3.0        | 24        | 0.59%   |
| More than 256.0 | 3         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 1121      | 25.71%  |
| 4.01-8.0    | 1045      | 23.97%  |
| 1.01-2.0    | 955       | 21.9%   |
| 3.01-4.0    | 744       | 17.06%  |
| 8.01-16.0   | 322       | 7.39%   |
| 0.51-1.0    | 88        | 2.02%   |
| 16.01-24.0  | 50        | 1.15%   |
| 24.01-32.0  | 16        | 0.37%   |
| 32.01-64.0  | 10        | 0.23%   |
| 0.01-0.5    | 7         | 0.16%   |
| 64.01-256.0 | 1         | 0.02%   |
| Unknown     | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2209      | 53.41%  |
| 2      | 1117      | 27.01%  |
| 3      | 383       | 9.26%   |
| 4      | 212       | 5.13%   |
| 5      | 106       | 2.56%   |
| 6      | 47        | 1.14%   |
| 7      | 28        | 0.68%   |
| 0      | 13        | 0.31%   |
| 8      | 8         | 0.19%   |
| 9      | 5         | 0.12%   |
| 10     | 3         | 0.07%   |
| 12     | 2         | 0.05%   |
| 11     | 2         | 0.05%   |
| 13     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2778      | 68.47%  |
| Yes       | 1279      | 31.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3394      | 84.11%  |
| No        | 641       | 15.89%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3145      | 77.71%  |
| No        | 902       | 22.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2710      | 66.68%  |
| No        | 1354      | 33.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 790       | 19.56%  |
| Germany      | 460       | 11.39%  |
| Russia       | 278       | 6.88%   |
| France       | 227       | 5.62%   |
| Brazil       | 225       | 5.57%   |
| Italy        | 211       | 5.22%   |
| UK           | 189       | 4.68%   |
| Spain        | 118       | 2.92%   |
| Canada       | 104       | 2.57%   |
| Poland       | 102       | 2.53%   |
| Netherlands  | 95        | 2.35%   |
| India        | 76        | 1.88%   |
| Australia    | 74        | 1.83%   |
| Ukraine      | 63        | 1.56%   |
| Mexico       | 51        | 1.26%   |
| Switzerland  | 50        | 1.24%   |
| Hungary      | 50        | 1.24%   |
| Czechia      | 44        | 1.09%   |
| Belgium      | 38        | 0.94%   |
| Argentina    | 36        | 0.89%   |
| Austria      | 34        | 0.84%   |
| Turkey       | 33        | 0.82%   |
| Sweden       | 30        | 0.74%   |
| Indonesia    | 27        | 0.67%   |
| Finland      | 27        | 0.67%   |
| South Africa | 26        | 0.64%   |
| Greece       | 26        | 0.64%   |
| Bulgaria     | 25        | 0.62%   |
| Portugal     | 23        | 0.57%   |
| Slovenia     | 22        | 0.54%   |
| Romania      | 22        | 0.54%   |
| Denmark      | 22        | 0.54%   |
| Serbia       | 20        | 0.5%    |
| Colombia     | 19        | 0.47%   |
| New Zealand  | 18        | 0.45%   |
| China        | 18        | 0.45%   |
| Slovakia     | 16        | 0.4%    |
| Belarus      | 16        | 0.4%    |
| Norway       | 15        | 0.37%   |
| Chile        | 15        | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 77        | 1.82%   |
| Berlin            | 48        | 1.14%   |
| Paris             | 38        | 0.9%    |
| St Petersburg     | 33        | 0.78%   |
| Hamburg           | 32        | 0.76%   |
| Milan             | 30        | 0.71%   |
| Warsaw            | 29        | 0.69%   |
| Sao Paulo         | 26        | 0.62%   |
| Rome              | 26        | 0.62%   |
| Budapest          | 23        | 0.54%   |
| Madrid            | 22        | 0.52%   |
| Munich            | 21        | 0.5%    |
| Amsterdam         | 21        | 0.5%    |
| Vienna            | 20        | 0.47%   |
| Sydney            | 20        | 0.47%   |
| London            | 20        | 0.47%   |
| Cologne           | 20        | 0.47%   |
| Rio de Janeiro    | 19        | 0.45%   |
| Zurich            | 18        | 0.43%   |
| Melbourne         | 18        | 0.43%   |
| Kyiv              | 18        | 0.43%   |
| Frankfurt am Main | 17        | 0.4%    |
| Prague            | 16        | 0.38%   |
| Dallas            | 14        | 0.33%   |
| Belgrade          | 14        | 0.33%   |
| Sofia             | 13        | 0.31%   |
| Montreal          | 13        | 0.31%   |
| Minsk             | 13        | 0.31%   |
| Seattle           | 12        | 0.28%   |
| Novosibirsk       | 12        | 0.28%   |
| Krakow            | 12        | 0.28%   |
| Jakarta           | 12        | 0.28%   |
| Athens            | 12        | 0.28%   |
| San Francisco     | 11        | 0.26%   |
| Los Angeles       | 11        | 0.26%   |
| Leipzig           | 11        | 0.26%   |
| Helsinki          | 11        | 0.26%   |
| Auckland          | 11        | 0.26%   |
| Wroclaw           | 10        | 0.24%   |
| Phoenix           | 10        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1136      | 1759   | 17.83%  |
| WDC                         | 919       | 1451   | 14.42%  |
| Seagate                     | 806       | 1237   | 12.65%  |
| Kingston                    | 372       | 447    | 5.84%   |
| Toshiba                     | 366       | 497    | 5.74%   |
| SanDisk                     | 359       | 451    | 5.63%   |
| Crucial                     | 262       | 326    | 4.11%   |
| Unknown                     | 209       | 261    | 3.28%   |
| Intel                       | 191       | 252    | 3%      |
| SK hynix                    | 167       | 200    | 2.62%   |
| Hitachi                     | 159       | 198    | 2.49%   |
| Micron Technology           | 120       | 135    | 1.88%   |
| HGST                        | 116       | 150    | 1.82%   |
| A-DATA Technology           | 96        | 105    | 1.51%   |
| KIOXIA                      | 57        | 65     | 0.89%   |
| Phison                      | 53        | 68     | 0.83%   |
| China                       | 52        | 69     | 0.82%   |
| Silicon Motion              | 42        | 47     | 0.66%   |
| PNY                         | 38        | 52     | 0.6%    |
| Apple                       | 38        | 44     | 0.6%    |
| SPCC                        | 37        | 46     | 0.58%   |
| Patriot                     | 32        | 43     | 0.5%    |
| Intenso                     | 32        | 38     | 0.5%    |
| Phison Electronics          | 30        | 30     | 0.47%   |
| Transcend                   | 29        | 31     | 0.46%   |
| OCZ                         | 26        | 33     | 0.41%   |
| LITEON                      | 26        | 28     | 0.41%   |
| Maxtor                      | 25        | 28     | 0.39%   |
| Corsair                     | 25        | 38     | 0.39%   |
| Micron/Crucial Technology   | 23        | 32     | 0.36%   |
| Unknown                     | 23        | 24     | 0.36%   |
| JMicron Technology          | 20        | 22     | 0.31%   |
| GOODRAM                     | 19        | 34     | 0.3%    |
| Kingston Technology Company | 18        | 20     | 0.28%   |
| Team                        | 16        | 17     | 0.25%   |
| XPG                         | 15        | 16     | 0.24%   |
| SABRENT                     | 14        | 17     | 0.22%   |
| LITEONIT                    | 14        | 16     | 0.22%   |
| KingSpec                    | 13        | 15     | 0.2%    |
| Gigabyte Technology         | 13        | 14     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 65        | 0.91%   |
| Kingston SA400S37240G 240GB SSD                     | 61        | 0.85%   |
| Samsung SSD 850 EVO 500GB                           | 53        | 0.74%   |
| Samsung SSD 850 EVO 250GB                           | 53        | 0.74%   |
| Kingston SA400S37480G 480GB SSD                     | 47        | 0.66%   |
| Seagate ST1000LM035-1RK172 1TB                      | 43        | 0.6%    |
| Samsung SSD 860 EVO 1TB                             | 41        | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 37        | 0.52%   |
| Crucial CT1000MX500SSD1 1TB                         | 36        | 0.5%    |
| Unknown MMC Card  32GB                              | 34        | 0.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 34        | 0.48%   |
| Unknown MMC Card  64GB                              | 33        | 0.46%   |
| Samsung NVMe SSD Drive 500GB                        | 33        | 0.46%   |
| Toshiba MQ04ABF100 1TB                              | 32        | 0.45%   |
| Samsung SSD 970 EVO Plus 1TB                        | 32        | 0.45%   |
| Toshiba MQ01ABD100 1TB                              | 31        | 0.43%   |
| Samsung SSD 970 EVO Plus 500GB                      | 31        | 0.43%   |
| HGST HTS721010A9E630 1TB                            | 31        | 0.43%   |
| Samsung NVMe SSD Drive 1TB                          | 30        | 0.42%   |
| Samsung NVMe SSD Drive 512GB                        | 28        | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 27        | 0.38%   |
| Samsung SSD 860 EVO 250GB                           | 27        | 0.38%   |
| Seagate ST4000DM004-2CV104 4TB                      | 26        | 0.36%   |
| Seagate ST1000DM010-2EP102 1TB                      | 26        | 0.36%   |
| Toshiba HDWD110 1TB                                 | 25        | 0.35%   |
| Seagate ST2000DM008-2FR102 2TB                      | 25        | 0.35%   |
| Seagate ST1000DM003-1CH162 1TB                      | 25        | 0.35%   |
| Toshiba DT01ACA100 1TB                              | 24        | 0.34%   |
| Seagate ST500DM002-1BD142 500GB                     | 24        | 0.34%   |
| Seagate ST1000DM003-1ER162 1TB                      | 23        | 0.32%   |
| Unknown                                             | 23        | 0.32%   |
| Seagate Expansion 2TB                               | 22        | 0.31%   |
| SanDisk SSD PLUS 240GB                              | 22        | 0.31%   |
| Kingston SA400S37120G 120GB SSD                     | 22        | 0.31%   |
| Seagate ST500LT012-1DG142 500GB                     | 21        | 0.29%   |
| Crucial CT500MX500SSD1 500GB                        | 21        | 0.29%   |
| Seagate ST2000DM001-1ER164 2TB                      | 20        | 0.28%   |
| SanDisk NVMe SSD Drive 512GB                        | 20        | 0.28%   |
| Samsung SSD 840 EVO 250GB                           | 20        | 0.28%   |
| Crucial CT240BX500SSD1 240GB                        | 20        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 784       | 1195   | 35.36%  |
| WDC                 | 686       | 1120   | 30.94%  |
| Toshiba             | 255       | 350    | 11.5%   |
| Hitachi             | 159       | 198    | 7.17%   |
| HGST                | 115       | 149    | 5.19%   |
| Samsung Electronics | 106       | 166    | 4.78%   |
| Maxtor              | 24        | 27     | 1.08%   |
| Unknown             | 22        | 26     | 0.99%   |
| Apple               | 15        | 15     | 0.68%   |
| SABRENT             | 14        | 17     | 0.63%   |
| Fujitsu             | 10        | 13     | 0.45%   |
| External            | 5         | 6      | 0.23%   |
| Hewlett-Packard     | 3         | 5      | 0.14%   |
| USB3.0              | 2         | 2      | 0.09%   |
| SAGE                | 2         | 2      | 0.09%   |
| JMicron Technology  | 2         | 2      | 0.09%   |
| ASMT                | 2         | 2      | 0.09%   |
| WD MediaMax         | 1         | 1      | 0.05%   |
| USB                 | 1         | 1      | 0.05%   |
| PHD 3.0             | 1         | 1      | 0.05%   |
| Magnetic Data       | 1         | 2      | 0.05%   |
| LIO-ORG             | 1         | 1      | 0.05%   |
| LaCie               | 1         | 1      | 0.05%   |
| KESU                | 1         | 1      | 0.05%   |
| ipTIME              | 1         | 1      | 0.05%   |
| IET                 | 1         | 1      | 0.05%   |
| HPE                 | 1         | 6      | 0.05%   |
| HGST HTS            | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 571       | 823    | 26.28%  |
| Kingston            | 271       | 323    | 12.47%  |
| Crucial             | 218       | 277    | 10.03%  |
| SanDisk             | 213       | 258    | 9.8%    |
| WDC                 | 116       | 156    | 5.34%   |
| A-DATA Technology   | 68        | 74     | 3.13%   |
| Intel               | 57        | 73     | 2.62%   |
| China               | 51        | 68     | 2.35%   |
| Micron Technology   | 40        | 44     | 1.84%   |
| Toshiba             | 35        | 50     | 1.61%   |
| PNY                 | 34        | 48     | 1.56%   |
| Patriot             | 32        | 43     | 1.47%   |
| SPCC                | 30        | 38     | 1.38%   |
| SK hynix            | 27        | 29     | 1.24%   |
| Intenso             | 27        | 31     | 1.24%   |
| OCZ                 | 26        | 33     | 1.2%    |
| Transcend           | 23        | 23     | 1.06%   |
| LITEON              | 21        | 22     | 0.97%   |
| GOODRAM             | 19        | 34     | 0.87%   |
| Team                | 14        | 14     | 0.64%   |
| LITEONIT            | 14        | 16     | 0.64%   |
| Corsair             | 14        | 25     | 0.64%   |
| KingSpec            | 13        | 15     | 0.6%    |
| Apple               | 13        | 13     | 0.6%    |
| Apacer              | 11        | 16     | 0.51%   |
| Mushkin             | 10        | 11     | 0.46%   |
| JMicron Technology  | 10        | 11     | 0.46%   |
| Emtec               | 8         | 9      | 0.37%   |
| Seagate             | 7         | 12     | 0.32%   |
| Plextor             | 7         | 8      | 0.32%   |
| Lexar               | 7         | 8      | 0.32%   |
| Unknown             | 7         | 7      | 0.32%   |
| Verbatim            | 6         | 8      | 0.28%   |
| Netac               | 6         | 7      | 0.28%   |
| Hewlett-Packard     | 6         | 6      | 0.28%   |
| Dogfish             | 6         | 6      | 0.28%   |
| ASMT                | 6         | 7      | 0.28%   |
| Gigabyte Technology | 5         | 5      | 0.23%   |
| Unknown             | 4         | 4      | 0.18%   |
| KingDian            | 4         | 5      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1856      | 2802   | 32.95%  |
| HDD     | 1785      | 3312   | 31.69%  |
| NVMe    | 1714      | 2331   | 30.43%  |
| MMC     | 187       | 229    | 3.32%   |
| Unknown | 91        | 127    | 1.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2794      | 5890   | 56.54%  |
| NVMe | 1714      | 2327   | 34.68%  |
| SAS  | 247       | 355    | 5%      |
| MMC  | 187       | 229    | 3.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1963      | 3105   | 50.14%  |
| 0.51-1.0   | 1224      | 1829   | 31.26%  |
| 1.01-2.0   | 418       | 659    | 10.68%  |
| 3.01-4.0   | 137       | 249    | 3.5%    |
| 2.01-3.0   | 82        | 118    | 2.09%   |
| 4.01-10.0  | 79        | 131    | 2.02%   |
| 10.01-20.0 | 12        | 23     | 0.31%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1016      | 24.3%   |
| 251-500        | 1000      | 23.92%  |
| 501-1000       | 773       | 18.49%  |
| 1001-2000      | 443       | 10.6%   |
| More than 3000 | 325       | 7.77%   |
| 51-100         | 208       | 4.97%   |
| 2001-3000      | 194       | 4.64%   |
| 1-20           | 113       | 2.7%    |
| 21-50          | 91        | 2.18%   |
| Unknown        | 18        | 0.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 959       | 22.28%  |
| 101-250        | 753       | 17.49%  |
| 21-50          | 670       | 15.56%  |
| 51-100         | 572       | 13.29%  |
| 251-500        | 505       | 11.73%  |
| 501-1000       | 381       | 8.85%   |
| 1001-2000      | 223       | 5.18%   |
| More than 3000 | 150       | 3.48%   |
| 2001-3000      | 74        | 1.72%   |
| Unknown        | 18        | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB   | 6         | 12     | 1.35%   |
| HGST HTS721010A9E630 1TB             | 6         | 7      | 1.35%   |
| Seagate ST500DM002-1BD142 500GB      | 5         | 5      | 1.13%   |
| Seagate ST31000524AS 1TB             | 5         | 6      | 1.13%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 5      | 1.13%   |
| Toshiba MQ04ABF100 1TB               | 4         | 4      | 0.9%    |
| Seagate ST500LT012-9WS142 500GB      | 4         | 4      | 0.9%    |
| Seagate ST3500418AS 500GB            | 4         | 4      | 0.9%    |
| Seagate ST1000DM003-1CH162 1TB       | 4         | 10     | 0.9%    |
| Crucial CT1050MX300SSD1 1TB          | 4         | 4      | 0.9%    |
| WDC WD5000AAKS-00V1A0 500GB          | 3         | 4      | 0.68%   |
| WDC WD30EZRX-00MMMB0 3TB             | 3         | 3      | 0.68%   |
| WDC WD20EFRX-68EUZN0 2TB             | 3         | 6      | 0.68%   |
| Toshiba MQ01ABD100 1TB               | 3         | 5      | 0.68%   |
| Seagate ST9500325AS 500GB            | 3         | 4      | 0.68%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 3      | 0.68%   |
| Seagate ST31000528AS 1TB             | 3         | 3      | 0.68%   |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 3      | 0.68%   |
| SanDisk SSD PLUS 240GB               | 3         | 3      | 0.68%   |
| Kingston SV300S37A120G 120GB SSD     | 3         | 3      | 0.68%   |
| Hitachi HTS547564A9E384 640GB        | 3         | 3      | 0.68%   |
| HGST HTS545050A7E680 500GB           | 3         | 3      | 0.68%   |
| HGST HTS541010A9E680 1TB             | 3         | 4      | 0.68%   |
| Crucial CT525MX300SSD1 528GB         | 3         | 3      | 0.68%   |
| WDC WD5000AAKS-00A7B0 500GB          | 2         | 2      | 0.45%   |
| WDC WD40EZRZ-00GXCB0 4TB             | 2         | 2      | 0.45%   |
| WDC WD40EFRX-68N32N0 4TB             | 2         | 4      | 0.45%   |
| WDC WD3200JD-22KLB0 320GB            | 2         | 2      | 0.45%   |
| WDC WD20EARX-00PASB0 2TB             | 2         | 2      | 0.45%   |
| WDC WD15EARS-00Z5B1 1TB              | 2         | 2      | 0.45%   |
| WDC WD10EZEX-22MFCA0 1TB             | 2         | 3      | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 2      | 0.45%   |
| WDC WD10EZEX-00BN5A0 1TB             | 2         | 2      | 0.45%   |
| WDC WD10EARS-00MVWB0 1TB             | 2         | 4      | 0.45%   |
| WDC WD10EADS-00L5B1 1TB              | 2         | 2      | 0.45%   |
| WDC WD1001FALS-40U9B0 1TB            | 2         | 2      | 0.45%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD | 2         | 2      | 0.45%   |
| Toshiba MQ01ABD075 752GB             | 2         | 4      | 0.45%   |
| Toshiba MK1652GSX 160GB              | 2         | 2      | 0.45%   |
| Toshiba HDWD110 1TB                  | 2         | 2      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 96        | 120    | 22.38%  |
| Seagate             | 94        | 120    | 21.91%  |
| Samsung Electronics | 42        | 57     | 9.79%   |
| Toshiba             | 34        | 40     | 7.93%   |
| Hitachi             | 28        | 28     | 6.53%   |
| Crucial             | 19        | 23     | 4.43%   |
| SanDisk             | 16        | 17     | 3.73%   |
| HGST                | 15        | 17     | 3.5%    |
| Intel               | 14        | 18     | 3.26%   |
| SK hynix            | 11        | 11     | 2.56%   |
| Kingston            | 10        | 10     | 2.33%   |
| Maxtor              | 6         | 7      | 1.4%    |
| A-DATA Technology   | 6         | 6      | 1.4%    |
| Micron Technology   | 5         | 5      | 1.17%   |
| OCZ                 | 4         | 4      | 0.93%   |
| Apple               | 4         | 4      | 0.93%   |
| Neo                 | 2         | 2      | 0.47%   |
| LITEONIT            | 2         | 2      | 0.47%   |
| Intenso             | 2         | 2      | 0.47%   |
| Fujitsu             | 2         | 2      | 0.47%   |
| Zheino              | 1         | 2      | 0.23%   |
| XPG                 | 1         | 1      | 0.23%   |
| VISIPRO             | 1         | 2      | 0.23%   |
| VENO                | 1         | 1      | 0.23%   |
| tecmiyo             | 1         | 3      | 0.23%   |
| Team                | 1         | 1      | 0.23%   |
| T-FORCE             | 1         | 1      | 0.23%   |
| SPCC                | 1         | 1      | 0.23%   |
| R580                | 1         | 1      | 0.23%   |
| Phison Electronics  | 1         | 1      | 0.23%   |
| ORTIAL              | 1         | 1      | 0.23%   |
| Mushkin             | 1         | 1      | 0.23%   |
| LITEON              | 1         | 1      | 0.23%   |
| Drevo               | 1         | 1      | 0.23%   |
| BAITITON            | 1         | 3      | 0.23%   |
| ASMT                | 1         | 1      | 0.23%   |
| ASENNO              | 1         | 1      | 0.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 94        | 120    | 32.53%  |
| WDC                 | 93        | 117    | 32.18%  |
| Toshiba             | 29        | 35     | 10.03%  |
| Hitachi             | 28        | 28     | 9.69%   |
| Samsung Electronics | 17        | 30     | 5.88%   |
| HGST                | 15        | 17     | 5.19%   |
| Maxtor              | 6         | 7      | 2.08%   |
| Apple               | 4         | 4      | 1.38%   |
| Fujitsu             | 2         | 2      | 0.69%   |
| ASMT                | 1         | 1      | 0.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 262       | 361    | 65.66%  |
| SSD  | 111       | 131    | 27.82%  |
| NVMe | 26        | 26     | 6.52%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB             | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 2      | 14.29%  |
| Samsung Electronics HD502IJ 500GB     | 1         | 1      | 14.29%  |
| OCZ VERTEX460A 480GB SSD              | 1         | 1      | 14.29%  |
| Intel SSDSC2KB960G8 960GB             | 1         | 1      | 14.29%  |
| Hitachi HTS547550A9E384 500GB         | 1         | 1      | 14.29%  |
| Acer SSD FA100 256GB                  | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 28.57%  |
| Seagate             | 1         | 1      | 14.29%  |
| OCZ                 | 1         | 1      | 14.29%  |
| Intel               | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 1      | 14.29%  |
| Acer                | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2079      | 4614   | 45.83%  |
| Works    | 2063      | 3661   | 45.48%  |
| Malfunc  | 388       | 518    | 8.55%   |
| Failed   | 6         | 8      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2534      | 46.58%  |
| AMD                              | 907       | 16.67%  |
| Samsung Electronics              | 558       | 10.26%  |
| SanDisk                          | 295       | 5.42%   |
| SK hynix                         | 139       | 2.56%   |
| Kingston Technology Company      | 120       | 2.21%   |
| Phison Electronics               | 102       | 1.88%   |
| ASMedia Technology               | 93        | 1.71%   |
| Toshiba America Info Systems     | 87        | 1.6%    |
| Micron Technology                | 80        | 1.47%   |
| Micron/Crucial Technology        | 67        | 1.23%   |
| Silicon Motion                   | 58        | 1.07%   |
| KIOXIA                           | 54        | 0.99%   |
| JMicron Technology               | 53        | 0.97%   |
| Marvell Technology Group         | 45        | 0.83%   |
| ADATA Technology                 | 44        | 0.81%   |
| Nvidia                           | 42        | 0.77%   |
| Realtek Semiconductor            | 27        | 0.5%    |
| Solid State Storage Technology   | 17        | 0.31%   |
| Union Memory (Shenzhen)          | 15        | 0.28%   |
| Broadcom / LSI                   | 13        | 0.24%   |
| LSI Logic / Symbios Logic        | 12        | 0.22%   |
| Lite-On Technology               | 10        | 0.18%   |
| Silicon Image                    | 9         | 0.17%   |
| Seagate Technology               | 8         | 0.15%   |
| Apple                            | 8         | 0.15%   |
| VIA Technologies                 | 7         | 0.13%   |
| Lenovo                           | 5         | 0.09%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.07%   |
| Shenzhen Longsys Electronics     | 3         | 0.06%   |
| Netac Technology                 | 3         | 0.06%   |
| INNOGRIT                         | 3         | 0.06%   |
| Yangtze Memory Technologies      | 2         | 0.04%   |
| Silicon Integrated Systems [SiS] | 2         | 0.04%   |
| Integrated Technology Express    | 2         | 0.04%   |
| Biwin Storage Technology         | 2         | 0.04%   |
| Adaptec                          | 2         | 0.04%   |
| Zhaoxin                          | 1         | 0.02%   |
| Solidigm                         | 1         | 0.02%   |
| Promise Technology               | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 643       | 10.42%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 307       | 4.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 214       | 3.47%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 198       | 3.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 165       | 2.67%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 157       | 2.54%   |
| Intel Volume Management Device NVMe RAID Controller                            | 135       | 2.19%   |
| AMD 400 Series Chipset SATA Controller                                         | 126       | 2.04%   |
| Samsung NVMe SSD Controller 980                                                | 101       | 1.64%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 100       | 1.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 100       | 1.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 95        | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 89        | 1.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 87        | 1.41%   |
| AMD 500 Series Chipset SATA Controller                                         | 87        | 1.41%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 86        | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 80        | 1.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 79        | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 79        | 1.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 77        | 1.25%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 74        | 1.2%    |
| Intel SSD 660P Series                                                          | 68        | 1.1%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 67        | 1.09%   |
| Intel Comet Lake SATA AHCI Controller                                          | 62        | 1%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 61        | 0.99%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 61        | 0.99%   |
| Intel SATA Controller [RAID mode]                                              | 59        | 0.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 56        | 0.91%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 55        | 0.89%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 54        | 0.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 49        | 0.79%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 48        | 0.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 48        | 0.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 44        | 0.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 44        | 0.71%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 43        | 0.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 43        | 0.7%    |
| AMD FCH SATA Controller D                                                      | 43        | 0.7%    |
| AMD 300 Series Chipset SATA Controller                                         | 43        | 0.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 40        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2947      | 54.24%  |
| NVMe | 1708      | 31.44%  |
| RAID | 406       | 7.47%   |
| IDE  | 349       | 6.42%   |
| SAS  | 15        | 0.28%   |
| SCSI | 8         | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 2886      | 71.63%  |
| AMD           | 1135      | 28.17%  |
| ARM           | 3         | 0.07%   |
| sifive,u74-mc | 2         | 0.05%   |
| QUALCOMM      | 1         | 0.02%   |
| Phytium       | 1         | 0.02%   |
| CentaurHauls  | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 65        | 1.61%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 52        | 1.29%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 48        | 1.19%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 47        | 1.16%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 43        | 1.07%   |
| AMD Ryzen 5 3600 6-Core Processor             | 42        | 1.04%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 41        | 1.02%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 41        | 1.02%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 39        | 0.97%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 39        | 0.97%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 39        | 0.97%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 38        | 0.94%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 36        | 0.89%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 36        | 0.89%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 33        | 0.82%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 32        | 0.79%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 31        | 0.77%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 30        | 0.74%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 30        | 0.74%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 29        | 0.72%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 28        | 0.69%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 27        | 0.67%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 26        | 0.64%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 25        | 0.62%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 25        | 0.62%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 25        | 0.62%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 24        | 0.59%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 23        | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 21        | 0.52%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 21        | 0.52%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 21        | 0.52%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 20        | 0.5%    |
| Intel Core i7-6700K CPU @ 4.00GHz             | 19        | 0.47%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 19        | 0.47%   |
| AMD FX-8350 Eight-Core Processor              | 19        | 0.47%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 18        | 0.45%   |
| Intel 12th Gen Core i7-12700H                 | 18        | 0.45%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 18        | 0.45%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 18        | 0.45%   |
| Intel 12th Gen Core i7-1260P                  | 17        | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 919       | 22.76%  |
| Intel Core i5           | 860       | 21.3%   |
| Other                   | 349       | 8.65%   |
| AMD Ryzen 5             | 325       | 8.05%   |
| AMD Ryzen 7             | 273       | 6.76%   |
| Intel Core i3           | 211       | 5.23%   |
| Intel Celeron           | 142       | 3.52%   |
| AMD Ryzen 9             | 97        | 2.4%    |
| Intel Core 2 Duo        | 93        | 2.3%    |
| Intel Xeon              | 87        | 2.16%   |
| AMD FX                  | 70        | 1.73%   |
| Intel Pentium           | 69        | 1.71%   |
| AMD Ryzen 3             | 47        | 1.16%   |
| Intel Core i9           | 38        | 0.94%   |
| AMD A6                  | 32        | 0.79%   |
| AMD A10                 | 32        | 0.79%   |
| AMD Ryzen 7 PRO         | 30        | 0.74%   |
| AMD A8                  | 28        | 0.69%   |
| Intel Atom              | 27        | 0.67%   |
| Intel Pentium Dual-Core | 26        | 0.64%   |
| Intel Core 2 Quad       | 24        | 0.59%   |
| AMD Phenom II X4        | 23        | 0.57%   |
| AMD Ryzen 5 PRO         | 18        | 0.45%   |
| Intel Pentium Silver    | 17        | 0.42%   |
| AMD Athlon II X4        | 14        | 0.35%   |
| AMD A4                  | 14        | 0.35%   |
| AMD Athlon              | 13        | 0.32%   |
| AMD Ryzen Threadripper  | 11        | 0.27%   |
| AMD Athlon II X2        | 9         | 0.22%   |
| AMD Athlon 64 X2        | 9         | 0.22%   |
| Intel Pentium Dual      | 8         | 0.2%    |
| Intel Genuine           | 8         | 0.2%    |
| AMD E1                  | 8         | 0.2%    |
| AMD E                   | 8         | 0.2%    |
| Intel Core m3           | 6         | 0.15%   |
| AMD Phenom II X6        | 6         | 0.15%   |
| AMD E2                  | 6         | 0.15%   |
| Intel Core 2            | 5         | 0.12%   |
| Intel Celeron Dual-Core | 5         | 0.12%   |
| AMD Sempron             | 5         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1599      | 39.62%  |
| 2       | 1230      | 30.48%  |
| 6       | 534       | 13.23%  |
| 8       | 396       | 9.81%   |
| 12      | 91        | 2.25%   |
| 16      | 49        | 1.21%   |
| 1       | 38        | 0.94%   |
| 10      | 31        | 0.77%   |
| 14      | 30        | 0.74%   |
| 24      | 11        | 0.27%   |
| 3       | 11        | 0.27%   |
| 32      | 5         | 0.12%   |
| 20      | 3         | 0.07%   |
| Unknown | 3         | 0.07%   |
| 18      | 2         | 0.05%   |
| 64      | 1         | 0.02%   |
| 36      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3997      | 99.21%  |
| 2       | 26        | 0.65%   |
| Unknown | 3         | 0.07%   |
| 4       | 2         | 0.05%   |
| 3       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3046      | 75.4%   |
| 1       | 991       | 24.53%  |
| Unknown | 3         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4023      | 99.85%  |
| Unknown        | 3         | 0.07%   |
| 32-bit         | 2         | 0.05%   |
| 64-bit         | 1         | 0.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1237      | 29.81%  |
| 0x306a9    | 178       | 4.29%   |
| 0x306c3    | 165       | 3.98%   |
| 0x206a7    | 157       | 3.78%   |
| 0x906ea    | 127       | 3.06%   |
| 0x806ec    | 111       | 2.67%   |
| 0x806c1    | 108       | 2.6%    |
| 0x806ea    | 102       | 2.46%   |
| 0x40651    | 81        | 1.95%   |
| 0x1067a    | 80        | 1.93%   |
| 0x906e9    | 78        | 1.88%   |
| 0x08701021 | 77        | 1.86%   |
| 0x806e9    | 76        | 1.83%   |
| 0x506e3    | 74        | 1.78%   |
| 0x406e3    | 62        | 1.49%   |
| 0x0a50000c | 61        | 1.47%   |
| 0x08108109 | 55        | 1.33%   |
| 0x08600106 | 47        | 1.13%   |
| 0x306d4    | 46        | 1.11%   |
| 0x0800820d | 46        | 1.11%   |
| 0x906a3    | 41        | 0.99%   |
| 0x06000852 | 40        | 0.96%   |
| 0x706e5    | 39        | 0.94%   |
| 0x08701013 | 38        | 0.92%   |
| 0x08108102 | 38        | 0.92%   |
| 0xa0652    | 36        | 0.87%   |
| 0x906ed    | 32        | 0.77%   |
| 0x806eb    | 32        | 0.77%   |
| 0x20655    | 29        | 0.7%    |
| 0x08608103 | 29        | 0.7%    |
| 0x706a1    | 28        | 0.67%   |
| 0x010000c8 | 28        | 0.67%   |
| 0x706a8    | 24        | 0.58%   |
| 0x406c4    | 23        | 0.55%   |
| 0x08600104 | 22        | 0.53%   |
| 0x806d1    | 20        | 0.48%   |
| 0x30678    | 20        | 0.48%   |
| 0x06001119 | 20        | 0.48%   |
| 0xa0653    | 19        | 0.46%   |
| 0x506c9    | 19        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 761       | 18.84%  |
| Haswell          | 380       | 9.41%   |
| IvyBridge        | 271       | 6.71%   |
| Zen 2            | 260       | 6.44%   |
| SandyBridge      | 230       | 5.69%   |
| Skylake          | 197       | 4.88%   |
| Zen+             | 196       | 4.85%   |
| Zen 3            | 175       | 4.33%   |
| Unknown          | 170       | 4.21%   |
| TigerLake        | 167       | 4.13%   |
| Penryn           | 131       | 3.24%   |
| CometLake        | 107       | 2.65%   |
| Zen              | 94        | 2.33%   |
| Piledriver       | 88        | 2.18%   |
| Icelake          | 88        | 2.18%   |
| Alderlake Hybrid | 77        | 1.91%   |
| Goldmont plus    | 75        | 1.86%   |
| Westmere         | 72        | 1.78%   |
| K10              | 72        | 1.78%   |
| Broadwell        | 70        | 1.73%   |
| Silvermont       | 62        | 1.53%   |
| Core             | 54        | 1.34%   |
| Excavator        | 46        | 1.14%   |
| Nehalem          | 44        | 1.09%   |
| Goldmont         | 26        | 0.64%   |
| Steamroller      | 19        | 0.47%   |
| Puma             | 19        | 0.47%   |
| K10 Llano        | 19        | 0.47%   |
| K8 Hammer        | 16        | 0.4%    |
| Jaguar           | 15        | 0.37%   |
| Bobcat           | 14        | 0.35%   |
| Bulldozer        | 8         | 0.2%    |
| NetBurst         | 7         | 0.17%   |
| Bonnell          | 5         | 0.12%   |
| Tremont          | 2         | 0.05%   |
| K8 & K10 hybrid  | 2         | 0.05%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2238      | 45.79%  |
| Nvidia                           | 1465      | 29.97%  |
| AMD                              | 1164      | 23.81%  |
| ASPEED Technology                | 9         | 0.18%   |
| Matrox Electronics Systems       | 8         | 0.16%   |
| ATI Technologies                 | 2         | 0.04%   |
| Zhaoxin                          | 1         | 0.02%   |
| Silicon Integrated Systems [SiS] | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 159       | 3.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 153       | 3.06%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 153       | 3.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 132       | 2.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 127       | 2.54%   |
| AMD Renoir                                                                               | 116       | 2.32%   |
| Intel UHD Graphics 620                                                                   | 114       | 2.28%   |
| Intel HD Graphics 620                                                                    | 99        | 1.98%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 95        | 1.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 92        | 1.84%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 89        | 1.78%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 85        | 1.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 84        | 1.68%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 84        | 1.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 79        | 1.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 76        | 1.52%   |
| Intel HD Graphics 630                                                                    | 63        | 1.26%   |
| Intel HD Graphics 530                                                                    | 62        | 1.24%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 60        | 1.2%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 56        | 1.12%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 54        | 1.08%   |
| Intel HD Graphics 5500                                                                   | 54        | 1.08%   |
| AMD Lucienne                                                                             | 51        | 1.02%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 50        | 1%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 48        | 0.96%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 43        | 0.86%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 40        | 0.8%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 38        | 0.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 37        | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 34        | 0.68%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 33        | 0.66%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 31        | 0.62%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 31        | 0.62%   |
| Intel Core Processor Integrated Graphics Controller                                      | 31        | 0.62%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 29        | 0.58%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 29        | 0.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 28        | 0.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 26        | 0.52%   |
| Intel Iris Plus Graphics G7                                                              | 26        | 0.52%   |
| AMD Rembrandt [Radeon 680M]                                                              | 26        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1477      | 36.51%  |
| 1 x AMD                  | 910       | 22.5%   |
| 1 x Nvidia               | 749       | 18.52%  |
| Intel + Nvidia           | 604       | 14.93%  |
| Intel + AMD              | 105       | 2.6%    |
| AMD + Nvidia             | 87        | 2.15%   |
| 2 x AMD                  | 62        | 1.53%   |
| 2 x Nvidia               | 17        | 0.42%   |
| Other                    | 9         | 0.22%   |
| 1 x ASPEED               | 5         | 0.12%   |
| Nvidia + ASPEED          | 4         | 0.1%    |
| Nvidia + Matrox          | 3         | 0.07%   |
| 1 x Matrox               | 3         | 0.07%   |
| 3 x Nvidia               | 2         | 0.05%   |
| 2 x Intel                | 2         | 0.05%   |
| AMD + Matrox             | 2         | 0.05%   |
| 1 x Zhaoxin              | 1         | 0.02%   |
| 1 x SiS                  | 1         | 0.02%   |
| Intel + 2 x AMD          | 1         | 0.02%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2937      | 72%     |
| Proprietary | 1059      | 25.96%  |
| Unknown     | 83        | 2.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2276      | 55.11%  |
| 1.01-2.0   | 467       | 11.31%  |
| 0.01-0.5   | 360       | 8.72%   |
| 3.01-4.0   | 311       | 7.53%   |
| 0.51-1.0   | 284       | 6.88%   |
| 7.01-8.0   | 209       | 5.06%   |
| 5.01-6.0   | 116       | 2.81%   |
| 8.01-16.0  | 56        | 1.36%   |
| 2.01-3.0   | 36        | 0.87%   |
| 16.01-24.0 | 11        | 0.27%   |
| 4.01-5.0   | 3         | 0.07%   |
| 32.01-64.0 | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 597       | 12.57%  |
| AU Optronics            | 506       | 10.65%  |
| BOE                     | 429       | 9.03%   |
| LG Display              | 403       | 8.49%   |
| Chimei Innolux          | 381       | 8.02%   |
| Dell                    | 314       | 6.61%   |
| Goldstar                | 260       | 5.47%   |
| Hewlett-Packard         | 168       | 3.54%   |
| Acer                    | 168       | 3.54%   |
| BenQ                    | 122       | 2.57%   |
| Philips                 | 118       | 2.48%   |
| AOC                     | 116       | 2.44%   |
| Sharp                   | 114       | 2.4%    |
| Ancor Communications    | 114       | 2.4%    |
| Lenovo                  | 64        | 1.35%   |
| ASUSTek Computer        | 62        | 1.31%   |
| Iiyama                  | 60        | 1.26%   |
| ViewSonic               | 56        | 1.18%   |
| Apple                   | 50        | 1.05%   |
| PANDA                   | 48        | 1.01%   |
| Chi Mei Optoelectronics | 45        | 0.95%   |
| InfoVision              | 38        | 0.8%    |
| LG Electronics          | 31        | 0.65%   |
| Sony                    | 25        | 0.53%   |
| Unknown                 | 24        | 0.51%   |
| NEC Computers           | 21        | 0.44%   |
| Panasonic               | 19        | 0.4%    |
| CSO                     | 17        | 0.36%   |
| Sceptre Tech            | 15        | 0.32%   |
| HannStar                | 15        | 0.32%   |
| Eizo                    | 15        | 0.32%   |
| MSI                     | 12        | 0.25%   |
| Medion                  | 11        | 0.23%   |
| Vizio                   | 10        | 0.21%   |
| Toshiba                 | 10        | 0.21%   |
| Gigabyte Technology     | 9         | 0.19%   |
| Vestel Elektronik       | 8         | 0.17%   |
| Idek Iiyama             | 8         | 0.17%   |
| LG Philips              | 7         | 0.15%   |
| RTK                     | 6         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 21        | 0.42%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 21        | 0.42%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 20        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 20        | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 20        | 0.4%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 19        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 17        | 0.34%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 16        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 16        | 0.32%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 14        | 0.28%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 13        | 0.26%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 13        | 0.26%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 13        | 0.26%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 13        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 12        | 0.24%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 12        | 0.24%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 12        | 0.24%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 11        | 0.22%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 10        | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 10        | 0.2%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 9         | 0.18%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 9         | 0.18%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 9         | 0.18%   |
| AOC 27G2WG3 AOC2702 1920x1080 598x336mm 27.0-inch                     | 9         | 0.18%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 8         | 0.16%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 8         | 0.16%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 8         | 0.16%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 8         | 0.16%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 8         | 0.16%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 8         | 0.16%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 8         | 0.16%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 8         | 0.16%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 8         | 0.16%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 8         | 0.16%   |
| Vestel Elektronik 40W_LCD_TV VES3700 1920x540                         | 7         | 0.14%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 7         | 0.14%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 7         | 0.14%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 7         | 0.14%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch   | 7         | 0.14%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 7         | 0.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2152      | 48.19%  |
| 1366x768 (WXGA)    | 630       | 14.11%  |
| 3840x2160 (4K)     | 327       | 7.32%   |
| 2560x1440 (QHD)    | 241       | 5.4%    |
| 1600x900 (HD+)     | 155       | 3.47%   |
| 1920x1200 (WUXGA)  | 146       | 3.27%   |
| 1680x1050 (WSXGA+) | 107       | 2.4%    |
| 1280x1024 (SXGA)   | 84        | 1.88%   |
| Unknown            | 76        | 1.7%    |
| 1440x900 (WXGA+)   | 60        | 1.34%   |
| 3440x1440          | 59        | 1.32%   |
| 2560x1080          | 50        | 1.12%   |
| 1280x800 (WXGA)    | 40        | 0.9%    |
| 2560x1600          | 37        | 0.83%   |
| 3840x1080          | 34        | 0.76%   |
| 1360x768           | 31        | 0.69%   |
| 2880x1800          | 29        | 0.65%   |
| 3840x2400          | 20        | 0.45%   |
| 2160x1440          | 20        | 0.45%   |
| 1920x540           | 14        | 0.31%   |
| 1600x1200          | 13        | 0.29%   |
| 1024x768 (XGA)     | 12        | 0.27%   |
| 3840x1200          | 9         | 0.2%    |
| 2240x1400          | 9         | 0.2%    |
| 3200x1800 (QHD+)   | 7         | 0.16%   |
| 2256x1504          | 7         | 0.16%   |
| 4480x1440          | 6         | 0.13%   |
| 1920x1280          | 6         | 0.13%   |
| 3840x1600          | 5         | 0.11%   |
| 2736x1824          | 5         | 0.11%   |
| 1280x720 (HD)      | 5         | 0.11%   |
| 5760x1080          | 4         | 0.09%   |
| 3456x2160          | 4         | 0.09%   |
| 3072x1920          | 4         | 0.09%   |
| 2520x1680          | 4         | 0.09%   |
| 2288x1287          | 4         | 0.09%   |
| 5760x2160          | 3         | 0.07%   |
| 3600x1080          | 3         | 0.07%   |
| 3200x1080          | 3         | 0.07%   |
| 7680x2160          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1122      | 23.73%  |
| 27      | 413       | 8.73%   |
| 24      | 405       | 8.56%   |
| 13      | 385       | 8.14%   |
| 14      | 375       | 7.93%   |
| 23      | 331       | 7%      |
| 17      | 271       | 5.73%   |
| 21      | 264       | 5.58%   |
| Unknown | 241       | 5.1%    |
| 31      | 113       | 2.39%   |
| 34      | 95        | 2.01%   |
| 19      | 90        | 1.9%    |
| 22      | 67        | 1.42%   |
| 20      | 59        | 1.25%   |
| 12      | 55        | 1.16%   |
| 16      | 54        | 1.14%   |
| 11      | 54        | 1.14%   |
| 18      | 51        | 1.08%   |
| 32      | 30        | 0.63%   |
| 54      | 29        | 0.61%   |
| 84      | 28        | 0.59%   |
| 72      | 24        | 0.51%   |
| 25      | 24        | 0.51%   |
| 40      | 20        | 0.42%   |
| 26      | 16        | 0.34%   |
| 46      | 9         | 0.19%   |
| 28      | 9         | 0.19%   |
| 48      | 8         | 0.17%   |
| 42      | 7         | 0.15%   |
| 37      | 7         | 0.15%   |
| 65      | 6         | 0.13%   |
| 10      | 6         | 0.13%   |
| 52      | 5         | 0.11%   |
| 36      | 5         | 0.11%   |
| 69      | 4         | 0.08%   |
| 60      | 4         | 0.08%   |
| 49      | 4         | 0.08%   |
| 39      | 4         | 0.08%   |
| 35      | 4         | 0.08%   |
| 33      | 4         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1731      | 37.57%  |
| 501-600        | 1048      | 22.74%  |
| 401-500        | 475       | 10.31%  |
| 351-400        | 320       | 6.94%   |
| 201-300        | 304       | 6.6%    |
| Unknown        | 241       | 5.23%   |
| 601-700        | 171       | 3.71%   |
| 701-800        | 132       | 2.86%   |
| 1001-1500      | 73        | 1.58%   |
| 1501-2000      | 60        | 1.3%    |
| 801-900        | 37        | 0.8%    |
| 901-1000       | 9         | 0.2%    |
| More than 2000 | 3         | 0.07%   |
| 101-200        | 2         | 0.04%   |
| 1-100          | 2         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3157      | 76.5%   |
| 16/10   | 464       | 11.24%  |
| Unknown | 210       | 5.09%   |
| 21/9    | 107       | 2.59%   |
| 5/4     | 80        | 1.94%   |
| 3/2     | 54        | 1.31%   |
| 4/3     | 30        | 0.73%   |
| 32/9    | 14        | 0.34%   |
| 1.00    | 3         | 0.07%   |
| 6/5     | 2         | 0.05%   |
| 1.96    | 2         | 0.05%   |
| 3.40    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |
| 0.25    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1121      | 24.13%  |
| 201-250        | 807       | 17.37%  |
| 81-90          | 599       | 12.89%  |
| 301-350        | 426       | 9.17%   |
| 351-500        | 250       | 5.38%   |
| Unknown        | 241       | 5.19%   |
| 151-200        | 214       | 4.61%   |
| 121-130        | 205       | 4.41%   |
| 71-80          | 166       | 3.57%   |
| 251-300        | 157       | 3.38%   |
| More than 1000 | 115       | 2.48%   |
| 141-150        | 81        | 1.74%   |
| 501-1000       | 66        | 1.42%   |
| 51-60          | 55        | 1.18%   |
| 111-120        | 48        | 1.03%   |
| 61-70          | 46        | 0.99%   |
| 131-140        | 27        | 0.58%   |
| 91-100         | 12        | 0.26%   |
| 41-50          | 6         | 0.13%   |
| 1-40           | 4         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1415      | 31.37%  |
| 121-160       | 1319      | 29.25%  |
| 101-120       | 986       | 21.86%  |
| 161-240       | 304       | 6.74%   |
| Unknown       | 241       | 5.34%   |
| More than 240 | 139       | 3.08%   |
| 1-50          | 106       | 2.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3035      | 73.84%  |
| 2     | 866       | 21.07%  |
| 3     | 108       | 2.63%   |
| 0     | 88        | 2.14%   |
| 4     | 13        | 0.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2283      | 37.48%  |
| Intel                             | 2082      | 34.18%  |
| Qualcomm Atheros                  | 594       | 9.75%   |
| Broadcom                          | 254       | 4.17%   |
| MediaTek                          | 130       | 2.13%   |
| TP-Link                           | 73        | 1.2%    |
| Ralink Technology                 | 66        | 1.08%   |
| Ralink                            | 55        | 0.9%    |
| Broadcom Limited                  | 44        | 0.72%   |
| Nvidia                            | 34        | 0.56%   |
| ASIX Electronics                  | 33        | 0.54%   |
| Marvell Technology Group          | 32        | 0.53%   |
| Samsung Electronics               | 28        | 0.46%   |
| Aquantia                          | 23        | 0.38%   |
| Lenovo                            | 21        | 0.34%   |
| Qualcomm Atheros Communications   | 20        | 0.33%   |
| NetGear                           | 19        | 0.31%   |
| Xiaomi                            | 18        | 0.3%    |
| Microsoft                         | 18        | 0.3%    |
| DisplayLink                       | 18        | 0.3%    |
| Qualcomm                          | 17        | 0.28%   |
| Huawei Technologies               | 17        | 0.28%   |
| Sierra Wireless                   | 16        | 0.26%   |
| D-Link                            | 15        | 0.25%   |
| Dell                              | 12        | 0.2%    |
| ASUSTek Computer                  | 11        | 0.18%   |
| Ericsson Business Mobile Networks | 10        | 0.16%   |
| Edimax Technology                 | 10        | 0.16%   |
| Hewlett-Packard                   | 9         | 0.15%   |
| JMicron Technology                | 8         | 0.13%   |
| Linksys                           | 7         | 0.11%   |
| Apple                             | 7         | 0.11%   |
| Google                            | 6         | 0.1%    |
| D-Link System                     | 6         | 0.1%    |
| Belkin Components                 | 6         | 0.1%    |
| Fibocom                           | 5         | 0.08%   |
| AVM                               | 5         | 0.08%   |
| ZTE WCDMA Technologies MSM        | 4         | 0.07%   |
| VIA Technologies                  | 4         | 0.07%   |
| Wacom                             | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1557      | 21.84%  |
| Intel Wi-Fi 6 AX200                                               | 233       | 3.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 197       | 2.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 143       | 2.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 140       | 1.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 132       | 1.85%   |
| Intel Wireless 8265 / 8275                                        | 129       | 1.81%   |
| Intel I211 Gigabit Network Connection                             | 124       | 1.74%   |
| Intel Wi-Fi 6 AX201                                               | 117       | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 107       | 1.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 101       | 1.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 94        | 1.32%   |
| Intel Wireless 7260                                               | 93        | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 90        | 1.26%   |
| Intel Wireless 7265                                               | 88        | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 85        | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 76        | 1.07%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 74        | 1.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 74        | 1.04%   |
| Intel Ethernet Connection (2) I219-V                              | 71        | 1%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 64        | 0.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 64        | 0.9%    |
| Intel Wireless 3165                                               | 62        | 0.87%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 62        | 0.87%   |
| Intel Ethernet Connection I217-LM                                 | 59        | 0.83%   |
| Intel Wireless 8260                                               | 58        | 0.81%   |
| Intel Ethernet Controller I225-V                                  | 57        | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 55        | 0.77%   |
| Intel Wireless-AC 9260                                            | 51        | 0.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 51        | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 48        | 0.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 44        | 0.62%   |
| Intel Ethernet Connection (7) I219-V                              | 42        | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 42        | 0.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 38        | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                             | 38        | 0.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 37        | 0.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 34        | 0.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 33        | 0.46%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 33        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1599      | 48.24%  |
| Realtek Semiconductor                 | 545       | 16.44%  |
| Qualcomm Atheros                      | 468       | 14.12%  |
| Broadcom                              | 168       | 5.07%   |
| MediaTek                              | 125       | 3.77%   |
| Ralink Technology                     | 66        | 1.99%   |
| TP-Link                               | 65        | 1.96%   |
| Ralink                                | 55        | 1.66%   |
| Broadcom Limited                      | 34        | 1.03%   |
| Qualcomm Atheros Communications       | 20        | 0.6%    |
| NetGear                               | 19        | 0.57%   |
| Microsoft                             | 17        | 0.51%   |
| Sierra Wireless                       | 16        | 0.48%   |
| D-Link                                | 15        | 0.45%   |
| Qualcomm                              | 12        | 0.36%   |
| ASUSTek Computer                      | 11        | 0.33%   |
| Edimax Technology                     | 10        | 0.3%    |
| Dell                                  | 7         | 0.21%   |
| Marvell Technology Group              | 6         | 0.18%   |
| Linksys                               | 6         | 0.18%   |
| Belkin Components                     | 6         | 0.18%   |
| Fibocom                               | 5         | 0.15%   |
| AVM                                   | 5         | 0.15%   |
| Ericsson Business Mobile Networks     | 4         | 0.12%   |
| D-Link System                         | 4         | 0.12%   |
| Wacom                                 | 3         | 0.09%   |
| Hewlett-Packard                       | 3         | 0.09%   |
| ZyXEL Communications                  | 2         | 0.06%   |
| ZyDAS                                 | 2         | 0.06%   |
| Wilocity                              | 2         | 0.06%   |
| Mercucys                              | 2         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.06%   |
| Texas Instruments                     | 1         | 0.03%   |
| Tenda                                 | 1         | 0.03%   |
| Sitecom Europe                        | 1         | 0.03%   |
| Philips (or NXP)                      | 1         | 0.03%   |
| Micro Star International              | 1         | 0.03%   |
| LG Electronics                        | 1         | 0.03%   |
| IMC Networks                          | 1         | 0.03%   |
| Guillemot                             | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 233       | 6.97%   |
| Intel Wireless 8265 / 8275                                     | 129       | 3.86%   |
| Intel Wi-Fi 6 AX201                                            | 117       | 3.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 107       | 3.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 101       | 3.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 94        | 2.81%   |
| Intel Wireless 7260                                            | 93        | 2.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 90        | 2.69%   |
| Intel Wireless 7265                                            | 88        | 2.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 85        | 2.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 76        | 2.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 74        | 2.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 74        | 2.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 64        | 1.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 64        | 1.91%   |
| Intel Wireless 3165                                            | 62        | 1.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 62        | 1.85%   |
| Intel Wireless 8260                                            | 58        | 1.73%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 55        | 1.65%   |
| Intel Wireless-AC 9260                                         | 51        | 1.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 51        | 1.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 48        | 1.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 44        | 1.32%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 38        | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 37        | 1.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 34        | 1.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 33        | 0.99%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 33        | 0.99%   |
| Ralink MT7601U Wireless Adapter                                | 30        | 0.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 29        | 0.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 28        | 0.84%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 28        | 0.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 28        | 0.84%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 26        | 0.78%   |
| Intel Wireless 3160                                            | 26        | 0.78%   |
| Realtek 802.11ac NIC                                           | 25        | 0.75%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 25        | 0.75%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 24        | 0.72%   |
| Broadcom BCM43142 802.11b/g/n                                  | 24        | 0.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 23        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2040      | 56.04%  |
| Intel                            | 1024      | 28.13%  |
| Qualcomm Atheros                 | 166       | 4.56%   |
| Broadcom                         | 110       | 3.02%   |
| Nvidia                           | 34        | 0.93%   |
| ASIX Electronics                 | 33        | 0.91%   |
| Samsung Electronics              | 28        | 0.77%   |
| Marvell Technology Group         | 26        | 0.71%   |
| Aquantia                         | 23        | 0.63%   |
| Lenovo                           | 21        | 0.58%   |
| Xiaomi                           | 18        | 0.49%   |
| DisplayLink                      | 18        | 0.49%   |
| Huawei Technologies              | 14        | 0.38%   |
| Broadcom Limited                 | 11        | 0.3%    |
| TP-Link                          | 8         | 0.22%   |
| JMicron Technology               | 8         | 0.22%   |
| Apple                            | 7         | 0.19%   |
| Google                           | 6         | 0.16%   |
| Qualcomm                         | 5         | 0.14%   |
| MediaTek                         | 5         | 0.14%   |
| ZTE WCDMA Technologies MSM       | 4         | 0.11%   |
| VIA Technologies                 | 4         | 0.11%   |
| T & A Mobile Phones              | 3         | 0.08%   |
| Silicon Integrated Systems [SiS] | 2         | 0.05%   |
| Motorola PCS                     | 2         | 0.05%   |
| Mellanox Technologies            | 2         | 0.05%   |
| D-Link System                    | 2         | 0.05%   |
| 3Com                             | 2         | 0.05%   |
| Solarflare Communications        | 1         | 0.03%   |
| QNAP System                      | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.03%   |
| Motorola BCS                     | 1         | 0.03%   |
| Microsoft                        | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| ICS Advent                       | 1         | 0.03%   |
| IBM                              | 1         | 0.03%   |
| HMD Global                       | 1         | 0.03%   |
| Hewlett-Packard                  | 1         | 0.03%   |
| Elecom                           | 1         | 0.03%   |
| Davicom Semiconductor            | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1557      | 41.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 197       | 5.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 143       | 3.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 140       | 3.74%   |
| Realtek RTL8125 2.5GbE Controller                                 | 132       | 3.53%   |
| Intel I211 Gigabit Network Connection                             | 124       | 3.31%   |
| Intel Ethernet Connection (2) I219-V                              | 71        | 1.9%    |
| Intel Ethernet Connection I217-LM                                 | 59        | 1.58%   |
| Intel Ethernet Controller I225-V                                  | 57        | 1.52%   |
| Intel Ethernet Connection (7) I219-V                              | 42        | 1.12%   |
| Intel Ethernet Connection (4) I219-LM                             | 42        | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                             | 38        | 1.02%   |
| Intel 82579V Gigabit Network Connection                           | 32        | 0.86%   |
| ASIX AX88179 Gigabit Ethernet                                     | 30        | 0.8%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 28        | 0.75%   |
| Intel Ethernet Connection (2) I218-V                              | 27        | 0.72%   |
| Intel Ethernet Connection I219-LM                                 | 25        | 0.67%   |
| Intel Ethernet Connection I218-LM                                 | 25        | 0.67%   |
| Intel I210 Gigabit Network Connection                             | 24        | 0.64%   |
| Intel Ethernet Connection I217-V                                  | 22        | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 21        | 0.56%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 20        | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20        | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                             | 20        | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 19        | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 19        | 0.51%   |
| Intel Ethernet Connection (6) I219-V                              | 19        | 0.51%   |
| Intel 82574L Gigabit Network Connection                           | 19        | 0.51%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 19        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 18        | 0.48%   |
| Intel Ethernet Connection (4) I219-V                              | 18        | 0.48%   |
| Intel Ethernet Connection (3) I218-LM                             | 18        | 0.48%   |
| Intel Ethernet Connection (10) I219-V                             | 17        | 0.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 16        | 0.43%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 16        | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 15        | 0.4%    |
| Intel Ethernet Connection (13) I219-V                             | 15        | 0.4%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 15        | 0.4%    |
| Intel 82577LM Gigabit Network Connection                          | 14        | 0.37%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 14        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3387      | 51.51%  |
| WiFi     | 3145      | 47.83%  |
| Modem    | 40        | 0.61%   |
| Unknown  | 4         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2455      | 57.55%  |
| Ethernet | 1810      | 42.43%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2157      | 53.47%  |
| 1     | 1702      | 42.19%  |
| 3     | 91        | 2.26%   |
| 0     | 63        | 1.56%   |
| 4     | 15        | 0.37%   |
| 6     | 4         | 0.1%    |
| 5     | 2         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 3263      | 79.82%  |
| Yes     | 824       | 20.16%  |
| Unknown | 1         | 0.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1383      | 50.29%  |
| Realtek Semiconductor           | 282       | 10.25%  |
| Qualcomm Atheros Communications | 209       | 7.6%    |
| Cambridge Silicon Radio         | 188       | 6.84%   |
| Broadcom                        | 123       | 4.47%   |
| IMC Networks                    | 110       | 4%      |
| Lite-On Technology              | 86        | 3.13%   |
| Foxconn / Hon Hai               | 84        | 3.05%   |
| Apple                           | 53        | 1.93%   |
| ASUSTek Computer                | 43        | 1.56%   |
| Dell                            | 34        | 1.24%   |
| Realtek                         | 31        | 1.13%   |
| MediaTek                        | 18        | 0.65%   |
| Ralink                          | 15        | 0.55%   |
| Hewlett-Packard                 | 13        | 0.47%   |
| Toshiba                         | 11        | 0.4%    |
| TP-Link                         | 9         | 0.33%   |
| Foxconn International           | 8         | 0.29%   |
| Marvell Semiconductor           | 7         | 0.25%   |
| Ralink Technology               | 5         | 0.18%   |
| Dynex                           | 5         | 0.18%   |
| ISSC                            | 4         | 0.15%   |
| Edimax Technology               | 4         | 0.15%   |
| Alps Electric                   | 4         | 0.15%   |
| USI                             | 2         | 0.07%   |
| Taiyo Yuden                     | 2         | 0.07%   |
| Smart Modular Technologies      | 2         | 0.07%   |
| Micro Star International        | 2         | 0.07%   |
| Integrated System Solution      | 2         | 0.07%   |
| D-Link                          | 2         | 0.07%   |
| Belkin Components               | 2         | 0.07%   |
| SINO WEALTH                     | 1         | 0.04%   |
| Kensington                      | 1         | 0.04%   |
| Creative Technology             | 1         | 0.04%   |
| Corsair                         | 1         | 0.04%   |
| Conwise Technology              | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |
| AboCom Systems                  | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 442       | 16.06%  |
| Intel AX201 Bluetooth                               | 277       | 10.06%  |
| Intel AX200 Bluetooth                               | 227       | 8.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 198       | 7.19%   |
| Realtek Bluetooth Radio                             | 189       | 6.87%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 188       | 6.83%   |
| Qualcomm Atheros  Bluetooth Device                  | 110       | 4%      |
| Intel Bluetooth Device                              | 106       | 3.85%   |
| Realtek  Bluetooth 4.2 Adapter                      | 77        | 2.8%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 49        | 1.78%   |
| Intel AX210 Bluetooth                               | 38        | 1.38%   |
| IMC Networks Bluetooth Radio                        | 35        | 1.27%   |
| IMC Networks Wireless_Device                        | 34        | 1.24%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 32        | 1.16%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 32        | 1.16%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 29        | 1.05%   |
| Lite-On Bluetooth Device                            | 28        | 1.02%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 28        | 1.02%   |
| Realtek 802.11ac WLAN Adapter                       | 24        | 0.87%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 23        | 0.84%   |
| Foxconn / Hon Hai Bluetooth Device                  | 23        | 0.84%   |
| Apple Bluetooth Host Controller                     | 23        | 0.84%   |
| Lite-On Wireless_Device                             | 20        | 0.73%   |
| IMC Networks Bluetooth Device                       | 20        | 0.73%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 20        | 0.73%   |
| MediaTek Wireless_Device                            | 18        | 0.65%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 18        | 0.65%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 17        | 0.62%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.58%   |
| Apple Bluetooth USB Host Controller                 | 16        | 0.58%   |
| Ralink RT3290 Bluetooth                             | 15        | 0.54%   |
| Foxconn / Hon Hai Wireless_Device                   | 14        | 0.51%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 13        | 0.47%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 13        | 0.47%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 12        | 0.44%   |
| Dell BCM20702A0 Bluetooth Module                    | 12        | 0.44%   |
| Broadcom HP Portable SoftSailing                    | 12        | 0.44%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 12        | 0.44%   |
| ASUS ASUS USB-BT500                                 | 12        | 0.44%   |
| Dell DW375 Bluetooth Module                         | 10        | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 2810      | 47.35%  |
| AMD                        | 1331      | 22.43%  |
| Nvidia                     | 1069      | 18.01%  |
| C-Media Electronics        | 113       | 1.9%    |
| Logitech                   | 44        | 0.74%   |
| GN Netcom                  | 39        | 0.66%   |
| Creative Labs              | 37        | 0.62%   |
| JMTek                      | 32        | 0.54%   |
| Realtek Semiconductor      | 31        | 0.52%   |
| Texas Instruments          | 25        | 0.42%   |
| Corsair                    | 20        | 0.34%   |
| ASUSTek Computer           | 20        | 0.34%   |
| Generalplus Technology     | 19        | 0.32%   |
| Razer USA                  | 18        | 0.3%    |
| Lenovo                     | 18        | 0.3%    |
| Hewlett-Packard            | 17        | 0.29%   |
| Creative Technology        | 17        | 0.29%   |
| Focusrite-Novation         | 16        | 0.27%   |
| Plantronics                | 14        | 0.24%   |
| SteelSeries ApS            | 13        | 0.22%   |
| Kingston Technology        | 12        | 0.2%    |
| VIA Technologies           | 9         | 0.15%   |
| Blue Microphones           | 9         | 0.15%   |
| Tenx Technology            | 8         | 0.13%   |
| Sony                       | 7         | 0.12%   |
| Dell                       | 7         | 0.12%   |
| SAVITECH                   | 6         | 0.1%    |
| Micro Star International   | 6         | 0.1%    |
| Yamaha                     | 4         | 0.07%   |
| Trust                      | 4         | 0.07%   |
| Sennheiser Communications  | 4         | 0.07%   |
| PreSonus Audio Electronics | 4         | 0.07%   |
| M-Audio                    | 4         | 0.07%   |
| GYROCOM C&C                | 4         | 0.07%   |
| BEHRINGER International    | 4         | 0.07%   |
| ZOOM                       | 3         | 0.05%   |
| TerraTec Electronic        | 3         | 0.05%   |
| TEAC                       | 3         | 0.05%   |
| Samson Technologies        | 3         | 0.05%   |
| Roland                     | 3         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 473       | 6.67%   |
| Intel Sunrise Point-LP HD Audio                                            | 313       | 4.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 249       | 3.51%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 242       | 3.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 222       | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 219       | 3.09%   |
| AMD Starship/Matisse HD Audio Controller                                   | 205       | 2.89%   |
| Intel Cannon Lake PCH cAVS                                                 | 202       | 2.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 174       | 2.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 167       | 2.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 154       | 2.17%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 133       | 1.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 123       | 1.73%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 115       | 1.62%   |
| Nvidia GP107GL High Definition Audio Controller                            | 113       | 1.59%   |
| AMD FCH Azalia Controller                                                  | 104       | 1.47%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 101       | 1.42%   |
| Intel Haswell-ULT HD Audio Controller                                      | 94        | 1.33%   |
| Intel 8 Series HD Audio Controller                                         | 93        | 1.31%   |
| Intel Comet Lake PCH-LP cAVS                                               | 91        | 1.28%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 87        | 1.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 85        | 1.2%    |
| Intel 200 Series PCH HD Audio                                              | 79        | 1.11%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 76        | 1.07%   |
| Intel Comet Lake PCH cAVS                                                  | 75        | 1.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 74        | 1.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 73        | 1.03%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 71        | 1%      |
| Nvidia TU116 High Definition Audio Controller                              | 69        | 0.97%   |
| Nvidia TU106 High Definition Audio Controller                              | 68        | 0.96%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 65        | 0.92%   |
| Nvidia GP106 High Definition Audio Controller                              | 62        | 0.87%   |
| Intel Broadwell-U Audio Controller                                         | 62        | 0.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 61        | 0.86%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 60        | 0.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 55        | 0.78%   |
| Nvidia GP104 High Definition Audio Controller                              | 53        | 0.75%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 53        | 0.75%   |
| Nvidia GF108 High Definition Audio Controller                              | 52        | 0.73%   |
| AMD Kabini HDMI/DP Audio                                                   | 51        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 652       | 21.73%  |
| SK hynix            | 479       | 15.97%  |
| Kingston            | 384       | 12.8%   |
| Micron Technology   | 313       | 10.43%  |
| Crucial             | 222       | 7.4%    |
| Unknown             | 198       | 6.6%    |
| Corsair             | 187       | 6.23%   |
| G.Skill             | 135       | 4.5%    |
| A-DATA Technology   | 59        | 1.97%   |
| Ramaxel Technology  | 50        | 1.67%   |
| Unknown (ABCD)      | 41        | 1.37%   |
| Nanya Technology    | 32        | 1.07%   |
| Elpida              | 32        | 1.07%   |
| Team                | 25        | 0.83%   |
| Patriot             | 20        | 0.67%   |
| Unknown             | 19        | 0.63%   |
| Transcend           | 16        | 0.53%   |
| Smart               | 16        | 0.53%   |
| GOODRAM             | 9         | 0.3%    |
| Silicon Power       | 8         | 0.27%   |
| AMD                 | 8         | 0.27%   |
| Apacer              | 6         | 0.2%    |
| Wilk                | 5         | 0.17%   |
| Teikon              | 5         | 0.17%   |
| Smart Brazil        | 5         | 0.17%   |
| Avant               | 5         | 0.17%   |
| PNY                 | 4         | 0.13%   |
| ASint Technology    | 4         | 0.13%   |
| SHARETRONIC         | 3         | 0.1%    |
| Goldkey             | 3         | 0.1%    |
| CSX                 | 3         | 0.1%    |
| V-GeN               | 2         | 0.07%   |
| Unifosa             | 2         | 0.07%   |
| Reboto              | 2         | 0.07%   |
| Kllisre             | 2         | 0.07%   |
| Kingmax             | 2         | 0.07%   |
| Imation             | 2         | 0.07%   |
| Hewlett-Packard     | 2         | 0.07%   |
| GLOWAY              | 2         | 0.07%   |
| GeIL                | 2         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 33        | 1.03%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 29        | 0.9%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 27        | 0.84%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 26        | 0.81%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 0.72%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 23        | 0.72%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 22        | 0.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 20        | 0.62%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 20        | 0.62%   |
| Unknown                                                          | 19        | 0.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 18        | 0.56%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 18        | 0.56%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 17        | 0.53%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 0.53%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 16        | 0.5%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 16        | 0.5%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.47%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 15        | 0.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.47%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 15        | 0.47%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.44%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 13        | 0.4%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.4%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 13        | 0.4%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 13        | 0.4%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 13        | 0.4%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 13        | 0.4%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 12        | 0.37%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.37%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 11        | 0.34%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.34%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 10        | 0.31%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 10        | 0.31%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 10        | 0.31%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.31%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 10        | 0.31%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.28%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.28%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1463      | 56.95%  |
| DDR3    | 694       | 27.01%  |
| LPDDR4  | 116       | 4.52%   |
| Unknown | 61        | 2.37%   |
| LPDDR3  | 58        | 2.26%   |
| DDR5    | 51        | 1.99%   |
| DDR2    | 50        | 1.95%   |
| SDRAM   | 38        | 1.48%   |
| LPDDR5  | 26        | 1.01%   |
| DDR     | 10        | 0.39%   |
| DRAM    | 2         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1474      | 57.15%  |
| DIMM         | 869       | 33.7%   |
| Row Of Chips | 207       | 8.03%   |
| Chip         | 15        | 0.58%   |
| Unknown      | 9         | 0.35%   |
| FB-DIMM      | 3         | 0.12%   |
| RIMM         | 2         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1233      | 43.86%  |
| 4096  | 677       | 24.08%  |
| 16384 | 536       | 19.07%  |
| 2048  | 225       | 8%      |
| 32768 | 107       | 3.81%   |
| 1024  | 29        | 1.03%   |
| 12288 | 1         | 0.04%   |
| 512   | 1         | 0.04%   |
| 256   | 1         | 0.04%   |
| 128   | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 495       | 17.76%  |
| 2667    | 491       | 17.62%  |
| 1600    | 469       | 16.83%  |
| 2400    | 243       | 8.72%   |
| 1333    | 164       | 5.88%   |
| 2133    | 136       | 4.88%   |
| 3600    | 94        | 3.37%   |
| 1334    | 61        | 2.19%   |
| 4267    | 50        | 1.79%   |
| 1867    | 41        | 1.47%   |
| 4800    | 36        | 1.29%   |
| 800     | 35        | 1.26%   |
| 3266    | 30        | 1.08%   |
| 667     | 29        | 1.04%   |
| 6400    | 28        | 1%      |
| 2666    | 24        | 0.86%   |
| 3000    | 23        | 0.83%   |
| Unknown | 23        | 0.83%   |
| 3800    | 21        | 0.75%   |
| 3400    | 21        | 0.75%   |
| 2933    | 20        | 0.72%   |
| 3733    | 19        | 0.68%   |
| 1067    | 16        | 0.57%   |
| 1066    | 16        | 0.57%   |
| 8400    | 14        | 0.5%    |
| 1866    | 13        | 0.47%   |
| 3866    | 12        | 0.43%   |
| 1800    | 12        | 0.43%   |
| 2800    | 11        | 0.39%   |
| 4199    | 10        | 0.36%   |
| 400     | 9         | 0.32%   |
| 4266    | 8         | 0.29%   |
| 3666    | 8         | 0.29%   |
| 3533    | 8         | 0.29%   |
| 3333    | 7         | 0.25%   |
| 3066    | 7         | 0.25%   |
| 3466    | 6         | 0.22%   |
| 2048    | 6         | 0.22%   |
| 5600    | 5         | 0.18%   |
| 3151    | 5         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 48        | 38.1%   |
| Brother Industries     | 28        | 22.22%  |
| Seiko Epson            | 14        | 11.11%  |
| Samsung Electronics    | 11        | 8.73%   |
| Canon                  | 10        | 7.94%   |
| Xerox                  | 2         | 1.59%   |
| Prolific Technology    | 2         | 1.59%   |
| Dymo-CoStar            | 2         | 1.59%   |
| Zebra                  | 1         | 0.79%   |
| QinHeng Electronics    | 1         | 0.79%   |
| Pantum                 | 1         | 0.79%   |
| Panasonic (Matsushita) | 1         | 0.79%   |
| Kyocera                | 1         | 0.79%   |
| ICS Advent             | 1         | 0.79%   |
| Datamax-O'Neil         | 1         | 0.79%   |
| BESTEASY               | 1         | 0.79%   |
| Apple                  | 1         | 0.79%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| HP OfficeJet Pro 8020 series                           | 3         | 2.34%   |
| Seiko Epson L360 Series                                | 2         | 1.56%   |
| Seiko Epson L3110 Series                               | 2         | 1.56%   |
| Samsung M2070 Series                                   | 2         | 1.56%   |
| Prolific PL2305 Parallel Port                          | 2         | 1.56%   |
| HP OfficeJet Pro 7740 series                           | 2         | 1.56%   |
| HP LaserJet P2015 series                               | 2         | 1.56%   |
| HP LaserJet 1020                                       | 2         | 1.56%   |
| HP LaserJet 1018                                       | 2         | 1.56%   |
| HP ENVY 4500 series                                    | 2         | 1.56%   |
| HP DeskJet 2700 series                                 | 2         | 1.56%   |
| HP DeskJet 2600 series                                 | 2         | 1.56%   |
| Brother MFC-J460DW                                     | 2         | 1.56%   |
| Brother HL-L2320D series                               | 2         | 1.56%   |
| Brother HL-2230 series                                 | 2         | 1.56%   |
| Zebra ZTC LP2844-Z-200dpi                              | 1         | 0.78%   |
| Xerox Phaser 6500DN                                    | 1         | 0.78%   |
| Xerox Phaser 3140 and 3155                             | 1         | 0.78%   |
| Seiko Epson XP-7100 Series                             | 1         | 0.78%   |
| Seiko Epson XP-3100 Series                             | 1         | 0.78%   |
| Seiko Epson XP-2200 Series                             | 1         | 0.78%   |
| Seiko Epson XP-2100 Series                             | 1         | 0.78%   |
| Seiko Epson WF-2530 Series                             | 1         | 0.78%   |
| Seiko Epson Printer                                    | 1         | 0.78%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 0.78%   |
| Seiko Epson L120 Series                                | 1         | 0.78%   |
| Seiko Epson ET-2710 Series                             | 1         | 0.78%   |
| Seiko Epson ET-2700 Series                             | 1         | 0.78%   |
| Samsung Xerox Phaser 3117 Laser Printer                | 1         | 0.78%   |
| Samsung SCX-3200 Series                                | 1         | 0.78%   |
| Samsung ML-2250 Series                                 | 1         | 0.78%   |
| Samsung ML-216x Series Laser Printer                   | 1         | 0.78%   |
| Samsung M262x/M282x Xpress Series Laser Printer        | 1         | 0.78%   |
| Samsung M2020 Series                                   | 1         | 0.78%   |
| Samsung CLX-3180 Series                                | 1         | 0.78%   |
| Samsung CLX-3170 Series                                | 1         | 0.78%   |
| Samsung CLP-360 Series                                 | 1         | 0.78%   |
| QinHeng CH340S                                         | 1         | 0.78%   |
| Pantum P2200 series                                    | 1         | 0.78%   |
| Panasonic (Matsushita) KX-MB1500RU                     | 1         | 0.78%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 14        | 51.85%  |
| Seiko Epson     | 7         | 25.93%  |
| Mustek Systems  | 3         | 11.11%  |
| Hewlett-Packard | 3         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 3         | 11.11%  |
| Canon CanoScan N670U/N676U/LiDE 20                      | 3         | 11.11%  |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 2         | 7.41%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 2         | 7.41%   |
| Canon CanoScan LiDE 220                                 | 2         | 7.41%   |
| Canon CanoScan LiDE 210                                 | 2         | 7.41%   |
| Canon CanoScan LiDE 110                                 | 2         | 7.41%   |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 3.7%    |
| Seiko Epson ES-D200 [GT-S50]                            | 1         | 3.7%    |
| Mustek Systems SNAPSCAN e22                             | 1         | 3.7%    |
| Mustek Systems ScanExpress A3 USB 1200 PRO              | 1         | 3.7%    |
| Mustek Systems BearPaw 1200 CU Plus                     | 1         | 3.7%    |
| HP ScanJet G4010                                        | 1         | 3.7%    |
| HP ScanJet 82x0C                                        | 1         | 3.7%    |
| HP ScanJet 3770                                         | 1         | 3.7%    |
| Canon CanoScan LiDE 60                                  | 1         | 3.7%    |
| Canon CanoScan LIDE 25                                  | 1         | 3.7%    |
| Canon CanoScan LiDE 120                                 | 1         | 3.7%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 496       | 18.47%  |
| IMC Networks                           | 270       | 10.05%  |
| Microdia                               | 245       | 9.12%   |
| Logitech                               | 204       | 7.59%   |
| Realtek Semiconductor                  | 202       | 7.52%   |
| Bison Electronics                      | 176       | 6.55%   |
| Quanta                                 | 145       | 5.4%    |
| Sunplus Innovation Technology          | 141       | 5.25%   |
| Cheng Uei Precision Industry (Foxlink) | 107       | 3.98%   |
| Syntek                                 | 61        | 2.27%   |
| Apple                                  | 52        | 1.94%   |
| Acer                                   | 49        | 1.82%   |
| Suyin                                  | 48        | 1.79%   |
| Silicon Motion                         | 44        | 1.64%   |
| Luxvisions Innotech Limited            | 44        | 1.64%   |
| Lite-On Technology                     | 42        | 1.56%   |
| Microsoft                              | 34        | 1.27%   |
| Alcor Micro                            | 31        | 1.15%   |
| Samsung Electronics                    | 30        | 1.12%   |
| Generalplus Technology                 | 18        | 0.67%   |
| Ricoh                                  | 16        | 0.6%    |
| Sonix Technology                       | 14        | 0.52%   |
| Lenovo                                 | 14        | 0.52%   |
| Z-Star Microelectronics                | 13        | 0.48%   |
| SunplusIT                              | 10        | 0.37%   |
| KYE Systems (Mouse Systems)            | 9         | 0.34%   |
| ARC International                      | 9         | 0.34%   |
| Genesys Logic                          | 8         | 0.3%    |
| Y Media                                | 7         | 0.26%   |
| MacroSilicon                           | 7         | 0.26%   |
| Huawei Technologies                    | 7         | 0.26%   |
| GEMBIRD                                | 7         | 0.26%   |
| Sunplus Technology                     | 6         | 0.22%   |
| icSpring                               | 6         | 0.22%   |
| Cubeternet                             | 6         | 0.22%   |
| LG Electronics                         | 5         | 0.19%   |
| Importek                               | 5         | 0.19%   |
| Creative Technology                    | 5         | 0.19%   |
| USB Camera CS                          | 4         | 0.15%   |
| Razer USA                              | 4         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 117       | 4.32%   |
| Microdia Integrated_Webcam_HD                                              | 107       | 3.95%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 84        | 3.1%    |
| Realtek Integrated_Webcam_HD                                               | 82        | 3.03%   |
| IMC Networks Integrated Camera                                             | 81        | 2.99%   |
| Bison Integrated Camera                                                    | 68        | 2.51%   |
| Sunplus Integrated_Webcam_HD                                               | 58        | 2.14%   |
| Logitech HD Pro Webcam C920                                                | 53        | 1.96%   |
| Chicony HD WebCam                                                          | 47        | 1.73%   |
| Syntek Integrated Camera                                                   | 43        | 1.59%   |
| Logitech Webcam C270                                                       | 40        | 1.48%   |
| Chicony HP HD Camera                                                       | 33        | 1.22%   |
| Chicony USB2.0 Camera                                                      | 31        | 1.14%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 29        | 1.07%   |
| Quanta HD User Facing                                                      | 29        | 1.07%   |
| Chicony HD User Facing                                                     | 26        | 0.96%   |
| Bison HD Webcam                                                            | 25        | 0.92%   |
| Microdia Integrated Webcam                                                 | 22        | 0.81%   |
| Quanta HP TrueVision HD Camera                                             | 20        | 0.74%   |
| Microdia Webcam Vitade AF                                                  | 20        | 0.74%   |
| Chicony HP Wide Vision HD Camera                                           | 20        | 0.74%   |
| Chicony Integrated Camera (1280x720@30)                                    | 19        | 0.7%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 19        | 0.7%    |
| Quanta HP HD Camera                                                        | 18        | 0.66%   |
| Lite-On Integrated Camera                                                  | 17        | 0.63%   |
| IMC Networks HD Camera                                                     | 17        | 0.63%   |
| Chicony HP TrueVision HD                                                   | 16        | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 16        | 0.59%   |
| Quanta HD Webcam                                                           | 15        | 0.55%   |
| Microdia Integrated_Webcam_FHD                                             | 15        | 0.55%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 15        | 0.55%   |
| Realtek Integrated Webcam                                                  | 14        | 0.52%   |
| Microsoft LifeCam HD-3000                                                  | 14        | 0.52%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 14        | 0.52%   |
| Logitech C922 Pro Stream Webcam                                            | 14        | 0.52%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 14        | 0.52%   |
| Sunplus HD WebCam                                                          | 13        | 0.48%   |
| Logitech HD Webcam C615                                                    | 13        | 0.48%   |
| Chicony HP TrueVision HD Camera                                            | 13        | 0.48%   |
| Bison Lenovo EasyCamera                                                    | 13        | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 181       | 33.21%  |
| Validity Sensors                   | 140       | 25.69%  |
| Shenzhen Goodix Technology         | 110       | 20.18%  |
| Elan Microelectronics              | 38        | 6.97%   |
| AuthenTec                          | 22        | 4.04%   |
| Upek                               | 21        | 3.85%   |
| LighTuning Technology              | 21        | 3.85%   |
| STMicroelectronics                 | 6         | 1.1%    |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.55%   |
| Focal-systems.Corp                 | 2         | 0.37%   |
| DigitalPersona                     | 1         | 0.18%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 63        | 11.56%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 56        | 10.28%  |
| Shenzhen Goodix Fingerprint Reader                                         | 30        | 5.5%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 24        | 4.4%    |
| Synaptics UWP WBDI                                                         | 23        | 4.22%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 3.85%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 21        | 3.85%   |
| Shenzhen Goodix FingerPrint                                                | 17        | 3.12%   |
| Validity Sensors Synaptics WBDI                                            | 16        | 2.94%   |
| Elan ELAN:Fingerprint                                                      | 15        | 2.75%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 14        | 2.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 14        | 2.57%   |
| Elan ELAN:ARM-M4                                                           | 14        | 2.57%   |
| Synaptics WBDI                                                             | 13        | 2.39%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 13        | 2.39%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 2.2%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 2.02%   |
| Synaptics  WBDI                                                            | 11        | 2.02%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 2.02%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 10        | 1.83%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 9         | 1.65%   |
| Synaptics Fingerprint reader [HP G6]                                       | 9         | 1.65%   |
| AuthenTec AES2810                                                          | 8         | 1.47%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.28%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 7         | 1.28%   |
| Elan WBF Fingerprint Sensor                                                | 7         | 1.28%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 1.1%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.1%    |
| Validity Sensors VFS491                                                    | 6         | 1.1%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.1%    |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.1%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.1%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 0.92%   |
| Unknown                                                                    | 5         | 0.92%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.73%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 0.73%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.73%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.73%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.55%   |
| Synaptics WBDI Device                                                      | 2         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 97        | 41.63%  |
| Alcor Micro               | 68        | 29.18%  |
| Upek                      | 14        | 6.01%   |
| O2 Micro                  | 9         | 3.86%   |
| Lenovo                    | 8         | 3.43%   |
| Advanced Card Systems     | 6         | 2.58%   |
| SCM Microsystems          | 4         | 1.72%   |
| Yubico.com                | 3         | 1.29%   |
| OmniKey                   | 3         | 1.29%   |
| Gemalto (was Gemplus)     | 3         | 1.29%   |
| Reiner SCT Kartensysteme  | 2         | 0.86%   |
| Realtek Semiconductor     | 2         | 0.86%   |
| Fujitsu Siemens Computers | 2         | 0.86%   |
| Clay Logic                | 2         | 0.86%   |
| BIT4ID                    | 2         | 0.86%   |
| Aladdin R.D.              | 2         | 0.86%   |
| Watchdata                 | 1         | 0.43%   |
| In Focus Systems          | 1         | 0.43%   |
| Giesecke & Devrient       | 1         | 0.43%   |
| Chicony Electronics       | 1         | 0.43%   |
| Aladdin Knowledge Systems | 1         | 0.43%   |
| Aktiv                     | 1         | 0.43%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 66        | 28.33%  |
| Broadcom 5880                                                                | 27        | 11.59%  |
| Broadcom 58200                                                               | 27        | 11.59%  |
| Broadcom BCM5880 Secure Applications Processor                               | 26        | 11.16%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 15        | 6.44%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 6.01%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 9         | 3.86%   |
| Lenovo Integrated Smart Card Reader                                          | 8         | 3.43%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 4         | 1.72%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 1.29%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.29%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 2         | 0.86%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.86%   |
| OmniKey CardMan 1021                                                         | 2         | 0.86%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.86%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.86%   |
| BIT4ID miniLector EVO                                                        | 2         | 0.86%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.86%   |
| Aladdin R.D. JaCarta                                                         | 2         | 0.86%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.86%   |
| Watchdata USB Key                                                            | 1         | 0.43%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.43%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.43%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.43%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.43%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.43%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.43%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.43%   |
| Fujitsu Siemens Computers Smartcard Reader D323                              | 1         | 0.43%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.43%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.43%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.43%   |
| Aktiv Rutoken lite                                                           | 1         | 0.43%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2804      | 68.27%  |
| 1     | 1050      | 25.57%  |
| 2     | 211       | 5.14%   |
| 3     | 22        | 0.54%   |
| 4     | 9         | 0.22%   |
| 6     | 4         | 0.1%    |
| 7     | 3         | 0.07%   |
| 5     | 3         | 0.07%   |
| 9     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 536       | 34.29%  |
| Graphics card            | 267       | 17.08%  |
| Chipcard                 | 201       | 12.86%  |
| Net/wireless             | 183       | 11.71%  |
| Camera                   | 76        | 4.86%   |
| Multimedia controller    | 66        | 4.22%   |
| Sound                    | 43        | 2.75%   |
| Bluetooth                | 43        | 2.75%   |
| Communication controller | 36        | 2.3%    |
| Unassigned class         | 35        | 2.24%   |
| Card reader              | 22        | 1.41%   |
| Storage                  | 19        | 1.22%   |
| Net/ethernet             | 10        | 0.64%   |
| Network                  | 8         | 0.51%   |
| Modem                    | 6         | 0.38%   |
| Storage/ide              | 5         | 0.32%   |
| Firewire controller      | 4         | 0.26%   |
| Dvb card                 | 3         | 0.19%   |

