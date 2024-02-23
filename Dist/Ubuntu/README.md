Ubuntu - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Ubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu/Desktop/README.md) and [notebooks](/Dist/Ubuntu/Notebook/README.md).

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

Total: 101513

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Unknown       | DH61BR G32662-203           | Desktop     | [06cb46d18c](https://linux-hardware.org/?probe=06cb46d18c) | Feb 02, 2024 |
| XDO.AI        | Pantera Pico PC             | Desktop     | [f5069feac3](https://linux-hardware.org/?probe=f5069feac3) | Feb 02, 2024 |
| Apple         | MacBookPro4,1               | Notebook    | [5d31a31783](https://linux-hardware.org/?probe=5d31a31783) | Feb 02, 2024 |
| Unknown       | DH61BR G32662-203           | Desktop     | [7496b90e09](https://linux-hardware.org/?probe=7496b90e09) | Feb 02, 2024 |
| Dell          | 0D28YY A01                  | Desktop     | [21e722f277](https://linux-hardware.org/?probe=21e722f277) | Feb 02, 2024 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [4bcae97baa](https://linux-hardware.org/?probe=4bcae97baa) | Feb 02, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [1546d8c6bf](https://linux-hardware.org/?probe=1546d8c6bf) | Feb 02, 2024 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | Notebook    | [7b22729e20](https://linux-hardware.org/?probe=7b22729e20) | Feb 02, 2024 |
| HP            | Pavilion dm1                | Notebook    | [f4c8f5a8e6](https://linux-hardware.org/?probe=f4c8f5a8e6) | Feb 02, 2024 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [e05005f76b](https://linux-hardware.org/?probe=e05005f76b) | Feb 02, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 83D... | Notebook    | [2389b9fc2f](https://linux-hardware.org/?probe=2389b9fc2f) | Feb 02, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 83D... | Notebook    | [32facc4f9e](https://linux-hardware.org/?probe=32facc4f9e) | Feb 02, 2024 |
| Dell          | Inspiron 13-7359            | Notebook    | [82a1195ef5](https://linux-hardware.org/?probe=82a1195ef5) | Feb 02, 2024 |
| Apple         | Mac-F221BEC8                | Desktop     | [7e71a3a029](https://linux-hardware.org/?probe=7e71a3a029) | Feb 02, 2024 |
| Dell          | Inspiron 3583               | Notebook    | [3c532c85ec](https://linux-hardware.org/?probe=3c532c85ec) | Feb 02, 2024 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [3aa20161d9](https://linux-hardware.org/?probe=3aa20161d9) | Feb 02, 2024 |
| Acer          | Aspire 5741G                | Notebook    | [935470b35c](https://linux-hardware.org/?probe=935470b35c) | Feb 02, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [a64852fe4a](https://linux-hardware.org/?probe=a64852fe4a) | Feb 02, 2024 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [1f85f107bb](https://linux-hardware.org/?probe=1f85f107bb) | Feb 02, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [97d6952c52](https://linux-hardware.org/?probe=97d6952c52) | Feb 02, 2024 |
| Acer          | Aspire V3-772               | Notebook    | [4a32c0297c](https://linux-hardware.org/?probe=4a32c0297c) | Feb 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [cb15afccd0](https://linux-hardware.org/?probe=cb15afccd0) | Feb 02, 2024 |
| HP            | 859C                        | Desktop     | [bc1cc805c6](https://linux-hardware.org/?probe=bc1cc805c6) | Feb 02, 2024 |
| Dell          | Precision 7550              | Notebook    | [c210fa0d97](https://linux-hardware.org/?probe=c210fa0d97) | Feb 02, 2024 |
| Acer          | Aspire 5741G                | Notebook    | [d598afdbe9](https://linux-hardware.org/?probe=d598afdbe9) | Feb 02, 2024 |
| DEXP          | Atlas M14-I5W303            | Notebook    | [fd14684ed2](https://linux-hardware.org/?probe=fd14684ed2) | Feb 02, 2024 |
| Lenovo        | ThinkPad E590 20NB002BRT    | Notebook    | [283a2fd324](https://linux-hardware.org/?probe=283a2fd324) | Feb 02, 2024 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [0bbbc51a52](https://linux-hardware.org/?probe=0bbbc51a52) | Feb 02, 2024 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | Notebook    | [7cbebba117](https://linux-hardware.org/?probe=7cbebba117) | Feb 02, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [1fe97c9103](https://linux-hardware.org/?probe=1fe97c9103) | Feb 02, 2024 |
| ASRock        | X300-ITX                    | Desktop     | [3390b15018](https://linux-hardware.org/?probe=3390b15018) | Feb 02, 2024 |
| Dell          | 05XGC8 A01                  | Desktop     | [29ae38936a](https://linux-hardware.org/?probe=29ae38936a) | Feb 02, 2024 |
| SLIMBOOK      | HERO-S-TGL-RTX              | Notebook    | [1260457422](https://linux-hardware.org/?probe=1260457422) | Feb 02, 2024 |
| Fujitsu       | D3523-Ax S26361-D3523-Ax    | Desktop     | [fefabce2b4](https://linux-hardware.org/?probe=fefabce2b4) | Feb 02, 2024 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [656bb7827a](https://linux-hardware.org/?probe=656bb7827a) | Feb 02, 2024 |
| Apple         | MacBookAir5,1               | Notebook    | [e25bf95ccb](https://linux-hardware.org/?probe=e25bf95ccb) | Feb 02, 2024 |
| Apple         | MacBookAir5,1               | Notebook    | [058a447435](https://linux-hardware.org/?probe=058a447435) | Feb 02, 2024 |
| Dell          | Inspiron 7577               | Notebook    | [0155afe6f3](https://linux-hardware.org/?probe=0155afe6f3) | Feb 02, 2024 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [0fb22a9b60](https://linux-hardware.org/?probe=0fb22a9b60) | Feb 02, 2024 |
| HP            | 158A                        | Desktop     | [1ec6b139ac](https://linux-hardware.org/?probe=1ec6b139ac) | Feb 02, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [5bc93c37fa](https://linux-hardware.org/?probe=5bc93c37fa) | Feb 02, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [176eee6b84](https://linux-hardware.org/?probe=176eee6b84) | Feb 02, 2024 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [565be02783](https://linux-hardware.org/?probe=565be02783) | Feb 02, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [7f677482ef](https://linux-hardware.org/?probe=7f677482ef) | Feb 02, 2024 |
| Lenovo        | ThinkBook 14 G6 IRL 21KG    | Notebook    | [c01e746574](https://linux-hardware.org/?probe=c01e746574) | Feb 02, 2024 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [5e505eb9f1](https://linux-hardware.org/?probe=5e505eb9f1) | Feb 02, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a64e17ff88](https://linux-hardware.org/?probe=a64e17ff88) | Feb 02, 2024 |
| Pegatron      | Spring Peak                 | Notebook    | [b14f110621](https://linux-hardware.org/?probe=b14f110621) | Feb 02, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [47431ad7d9](https://linux-hardware.org/?probe=47431ad7d9) | Feb 02, 2024 |
| ASUSTek       | N53SV                       | Notebook    | [ee79ea1cbb](https://linux-hardware.org/?probe=ee79ea1cbb) | Feb 01, 2024 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | Notebook    | [74173e2c0a](https://linux-hardware.org/?probe=74173e2c0a) | Feb 01, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [34e8a186d6](https://linux-hardware.org/?probe=34e8a186d6) | Feb 01, 2024 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [50c9a44280](https://linux-hardware.org/?probe=50c9a44280) | Feb 01, 2024 |
| Pegatron      | Spring Peak                 | Notebook    | [4404cfb5c8](https://linux-hardware.org/?probe=4404cfb5c8) | Feb 01, 2024 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [7340c4abd7](https://linux-hardware.org/?probe=7340c4abd7) | Feb 01, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [f0b3157a23](https://linux-hardware.org/?probe=f0b3157a23) | Feb 01, 2024 |
| Dell          | Latitude 5420               | Notebook    | [9ca4bb32d7](https://linux-hardware.org/?probe=9ca4bb32d7) | Feb 01, 2024 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [58f11b08b0](https://linux-hardware.org/?probe=58f11b08b0) | Feb 01, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [151239b938](https://linux-hardware.org/?probe=151239b938) | Feb 01, 2024 |
| Gigabyte      | Z790 AORUS PRO X            | Desktop     | [de6afda636](https://linux-hardware.org/?probe=de6afda636) | Feb 01, 2024 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [910fba93b8](https://linux-hardware.org/?probe=910fba93b8) | Feb 01, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [fb180a9a54](https://linux-hardware.org/?probe=fb180a9a54) | Feb 01, 2024 |
| Lenovo        | ThinkPad X280 20KES4TD0T    | Notebook    | [4af2fc13f4](https://linux-hardware.org/?probe=4af2fc13f4) | Feb 01, 2024 |
| Dell          | Vostro 3525                 | Notebook    | [495877fada](https://linux-hardware.org/?probe=495877fada) | Feb 01, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [04c6362187](https://linux-hardware.org/?probe=04c6362187) | Feb 01, 2024 |
| Dell          | 0T568R A00                  | Desktop     | [4ce5e16aa2](https://linux-hardware.org/?probe=4ce5e16aa2) | Feb 01, 2024 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [7bbfc4d26a](https://linux-hardware.org/?probe=7bbfc4d26a) | Feb 01, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [88448ddf49](https://linux-hardware.org/?probe=88448ddf49) | Feb 01, 2024 |
| ASUSTek       | N53SV                       | Notebook    | [29807f0dfa](https://linux-hardware.org/?probe=29807f0dfa) | Feb 01, 2024 |
| AMI           | Intel                       | Notebook    | [6d3ac84f15](https://linux-hardware.org/?probe=6d3ac84f15) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [6acefbaadc](https://linux-hardware.org/?probe=6acefbaadc) | Feb 01, 2024 |
| Supermicro    | X8DTU                       | Server      | [246a9d76c6](https://linux-hardware.org/?probe=246a9d76c6) | Feb 01, 2024 |
| Acer          | Swift SF314-512             | Notebook    | [28bd75703e](https://linux-hardware.org/?probe=28bd75703e) | Feb 01, 2024 |
| Dell          | 0N0992 A00                  | Desktop     | [b1aae1e53b](https://linux-hardware.org/?probe=b1aae1e53b) | Feb 01, 2024 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [5f2635ae3a](https://linux-hardware.org/?probe=5f2635ae3a) | Feb 01, 2024 |
| Dell          | 0TDG4V A01                  | Desktop     | [d921cc13e3](https://linux-hardware.org/?probe=d921cc13e3) | Feb 01, 2024 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Convertible | [f6d99b6096](https://linux-hardware.org/?probe=f6d99b6096) | Feb 01, 2024 |
| Dell          | Inspiron 7501               | Notebook    | [5c071c25ab](https://linux-hardware.org/?probe=5c071c25ab) | Feb 01, 2024 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [5bd3d39655](https://linux-hardware.org/?probe=5bd3d39655) | Feb 01, 2024 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [a45a2b4f8e](https://linux-hardware.org/?probe=a45a2b4f8e) | Feb 01, 2024 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [aaec148c06](https://linux-hardware.org/?probe=aaec148c06) | Feb 01, 2024 |
| TrekStor      | Primebook P14               | Notebook    | [ffd6c873de](https://linux-hardware.org/?probe=ffd6c873de) | Feb 01, 2024 |
| EBN           | MA1N                        | Desktop     | [302ea43954](https://linux-hardware.org/?probe=302ea43954) | Feb 01, 2024 |
| Dell          | 09KPNV A01                  | Desktop     | [b6ba043767](https://linux-hardware.org/?probe=b6ba043767) | Feb 01, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [8689e993e3](https://linux-hardware.org/?probe=8689e993e3) | Feb 01, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [01332b7a24](https://linux-hardware.org/?probe=01332b7a24) | Feb 01, 2024 |
| Apple         | MacBookPro4,1               | Notebook    | [863b50ad5a](https://linux-hardware.org/?probe=863b50ad5a) | Feb 01, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [5a7e77b4a7](https://linux-hardware.org/?probe=5a7e77b4a7) | Feb 01, 2024 |
| Gigabyte      | B760M GAMING X DDR4         | Desktop     | [855d31073a](https://linux-hardware.org/?probe=855d31073a) | Feb 01, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [c211b49a95](https://linux-hardware.org/?probe=c211b49a95) | Feb 01, 2024 |
| HP            | 8598                        | Desktop     | [cc6faa2bfa](https://linux-hardware.org/?probe=cc6faa2bfa) | Feb 01, 2024 |
| Intel         | NUC8i7HNB J68197-602        | Mini pc     | [b3b6728f99](https://linux-hardware.org/?probe=b3b6728f99) | Feb 01, 2024 |
| Dell          | Precision 5680              | Notebook    | [9d85b2e2ea](https://linux-hardware.org/?probe=9d85b2e2ea) | Feb 01, 2024 |
| MSI           | Z370-A PRO                  | Desktop     | [d012afeb56](https://linux-hardware.org/?probe=d012afeb56) | Feb 01, 2024 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [f6051e0b06](https://linux-hardware.org/?probe=f6051e0b06) | Feb 01, 2024 |
| Toshiba       | Satellite L750              | Notebook    | [a1e1f9075d](https://linux-hardware.org/?probe=a1e1f9075d) | Feb 01, 2024 |
| ASUSTek       | PRIME B760-PLUS D4          | Desktop     | [d9355c6146](https://linux-hardware.org/?probe=d9355c6146) | Feb 01, 2024 |
| Intel         | Alder Lake-H PCH E1.1G      | Desktop     | [fa7a5b2aa3](https://linux-hardware.org/?probe=fa7a5b2aa3) | Jan 31, 2024 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [7cd644d30e](https://linux-hardware.org/?probe=7cd644d30e) | Jan 31, 2024 |
| Sony          | SVE14A1V1EW                 | Notebook    | [0323c38fe4](https://linux-hardware.org/?probe=0323c38fe4) | Jan 31, 2024 |
| ASUSTek       | PN64                        | Mini pc     | [7123543d85](https://linux-hardware.org/?probe=7123543d85) | Jan 31, 2024 |
| Foxconn       | 9657MA                      | Desktop     | [6b2e0b2ae9](https://linux-hardware.org/?probe=6b2e0b2ae9) | Jan 31, 2024 |
| HP            | ENVY dv6                    | Notebook    | [a91621750a](https://linux-hardware.org/?probe=a91621750a) | Jan 31, 2024 |
| Dell          | Latitude 7480               | Notebook    | [268ea50333](https://linux-hardware.org/?probe=268ea50333) | Jan 31, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [539b422b80](https://linux-hardware.org/?probe=539b422b80) | Jan 31, 2024 |
| Supermicro    | X10DRU-i+A                  | Desktop     | [f2881b94b0](https://linux-hardware.org/?probe=f2881b94b0) | Jan 31, 2024 |
| ASUSTek       | X555LD                      | Notebook    | [bc95890dcd](https://linux-hardware.org/?probe=bc95890dcd) | Jan 31, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [a84c65f63e](https://linux-hardware.org/?probe=a84c65f63e) | Jan 31, 2024 |
| HUAWEI        | MCLF-XX                     | Notebook    | [97bfeb35bc](https://linux-hardware.org/?probe=97bfeb35bc) | Jan 31, 2024 |
| Dell          | Latitude E7250              | Notebook    | [24ea631399](https://linux-hardware.org/?probe=24ea631399) | Jan 31, 2024 |
| Gigabyte      | B560M DS3H AC               | Desktop     | [81a39a795c](https://linux-hardware.org/?probe=81a39a795c) | Jan 31, 2024 |
| Dell          | Latitude 5501               | Notebook    | [7c92ef29c9](https://linux-hardware.org/?probe=7c92ef29c9) | Jan 31, 2024 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [36be131f18](https://linux-hardware.org/?probe=36be131f18) | Jan 31, 2024 |
| Dell          | 0R4CNN A02                  | Server      | [1598eeb7c8](https://linux-hardware.org/?probe=1598eeb7c8) | Jan 31, 2024 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [12a68ef8f3](https://linux-hardware.org/?probe=12a68ef8f3) | Jan 31, 2024 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [34c89da9d0](https://linux-hardware.org/?probe=34c89da9d0) | Jan 31, 2024 |
| Dell          | Inspiron 5537               | Notebook    | [600bb8363d](https://linux-hardware.org/?probe=600bb8363d) | Jan 31, 2024 |
| ASUSTek       | X555LD                      | Notebook    | [e65c871d95](https://linux-hardware.org/?probe=e65c871d95) | Jan 31, 2024 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [535ed186d9](https://linux-hardware.org/?probe=535ed186d9) | Jan 31, 2024 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [6a4b856510](https://linux-hardware.org/?probe=6a4b856510) | Jan 31, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [20471f1e71](https://linux-hardware.org/?probe=20471f1e71) | Jan 31, 2024 |
| ASUSTek       | X555LD                      | Notebook    | [1433f11bba](https://linux-hardware.org/?probe=1433f11bba) | Jan 31, 2024 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | Desktop     | [2360c2cf38](https://linux-hardware.org/?probe=2360c2cf38) | Jan 31, 2024 |
| Intel         | DG41AN AAE92991-401         | Desktop     | [5e520c92ca](https://linux-hardware.org/?probe=5e520c92ca) | Jan 31, 2024 |
| MSI           | Modern 14 B5M               | Notebook    | [e41b88a884](https://linux-hardware.org/?probe=e41b88a884) | Jan 31, 2024 |
| Fujitsu       | LIFEBOOK E554               | Notebook    | [ce905760f2](https://linux-hardware.org/?probe=ce905760f2) | Jan 31, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [98de51c101](https://linux-hardware.org/?probe=98de51c101) | Jan 31, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [348c7c4e82](https://linux-hardware.org/?probe=348c7c4e82) | Jan 31, 2024 |
| Minix         | NEO Z83-4A                  | Notebook    | [a563c8089f](https://linux-hardware.org/?probe=a563c8089f) | Jan 31, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [85c2cd9371](https://linux-hardware.org/?probe=85c2cd9371) | Jan 31, 2024 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [bdb06264ab](https://linux-hardware.org/?probe=bdb06264ab) | Jan 31, 2024 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | Notebook    | [4f9b6c7262](https://linux-hardware.org/?probe=4f9b6c7262) | Jan 31, 2024 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [77c6d89192](https://linux-hardware.org/?probe=77c6d89192) | Jan 31, 2024 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | Notebook    | [0e068176e4](https://linux-hardware.org/?probe=0e068176e4) | Jan 31, 2024 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [ab001c7490](https://linux-hardware.org/?probe=ab001c7490) | Jan 31, 2024 |
| Apple         | MacBook8,1                  | Notebook    | [6ef40b726e](https://linux-hardware.org/?probe=6ef40b726e) | Jan 31, 2024 |
| Dell          | Precision 7710              | Notebook    | [6e600ac30e](https://linux-hardware.org/?probe=6e600ac30e) | Jan 31, 2024 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [97575d7173](https://linux-hardware.org/?probe=97575d7173) | Jan 31, 2024 |
| Dell          | XPS 13 9380                 | Notebook    | [479853dd4c](https://linux-hardware.org/?probe=479853dd4c) | Jan 31, 2024 |
| Dell          | 02K9CR A01                  | Desktop     | [72df486f35](https://linux-hardware.org/?probe=72df486f35) | Jan 31, 2024 |
| Dell          | Latitude E6430s             | Notebook    | [6eacf03c08](https://linux-hardware.org/?probe=6eacf03c08) | Jan 31, 2024 |
| Acer          | Swift SF514-56T             | Notebook    | [14b287861f](https://linux-hardware.org/?probe=14b287861f) | Jan 31, 2024 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | Notebook    | [5193f57d67](https://linux-hardware.org/?probe=5193f57d67) | Jan 31, 2024 |
| Acer          | Swift SF314-42              | Notebook    | [32d0112bcd](https://linux-hardware.org/?probe=32d0112bcd) | Jan 30, 2024 |
| HP            | ProBook 450 G8              | Notebook    | [f8d060061c](https://linux-hardware.org/?probe=f8d060061c) | Jan 30, 2024 |
| HP            | ProBook 450 G8              | Notebook    | [4ca13b7d13](https://linux-hardware.org/?probe=4ca13b7d13) | Jan 30, 2024 |
| Dell          | 0T568R A00                  | Desktop     | [56936b64ba](https://linux-hardware.org/?probe=56936b64ba) | Jan 30, 2024 |
| HP            | Pavilion dv6                | Notebook    | [e1e2c04f8c](https://linux-hardware.org/?probe=e1e2c04f8c) | Jan 30, 2024 |
| MACHINIST     | X99-D8-MAX V1.0             | Desktop     | [8ecccf1672](https://linux-hardware.org/?probe=8ecccf1672) | Jan 30, 2024 |
| Alienware     | 15 R3                       | Notebook    | [297db64e3b](https://linux-hardware.org/?probe=297db64e3b) | Jan 30, 2024 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [b51ecf60ef](https://linux-hardware.org/?probe=b51ecf60ef) | Jan 30, 2024 |
| Intel         | NUC7i5BNB J31144-302        | Mini pc     | [b7e8bed4cd](https://linux-hardware.org/?probe=b7e8bed4cd) | Jan 30, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [c737ef78e9](https://linux-hardware.org/?probe=c737ef78e9) | Jan 30, 2024 |
| AZW           | MINI S 10                   | Desktop     | [a209f8ae32](https://linux-hardware.org/?probe=a209f8ae32) | Jan 30, 2024 |
| Apple         | MacBook8,1                  | Notebook    | [9580d3149f](https://linux-hardware.org/?probe=9580d3149f) | Jan 30, 2024 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [13e5919ccf](https://linux-hardware.org/?probe=13e5919ccf) | Jan 30, 2024 |
| Unknown       | Unknown                     | Desktop     | [6928c8eb05](https://linux-hardware.org/?probe=6928c8eb05) | Jan 30, 2024 |
| Lenovo        | Yoga S730-13IWL 81J0        | Notebook    | [87e2c70726](https://linux-hardware.org/?probe=87e2c70726) | Jan 30, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K3C... | Notebook    | [649745f3ae](https://linux-hardware.org/?probe=649745f3ae) | Jan 30, 2024 |
| Dell          | XPS 13 9305                 | Notebook    | [1b2e728298](https://linux-hardware.org/?probe=1b2e728298) | Jan 30, 2024 |
| MSI           | X99A SLI PLUS               | Desktop     | [216026fc45](https://linux-hardware.org/?probe=216026fc45) | Jan 30, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [1669d54762](https://linux-hardware.org/?probe=1669d54762) | Jan 30, 2024 |
| Gigabyte      | H55M-S2HP                   | Desktop     | [a1a4140c7e](https://linux-hardware.org/?probe=a1a4140c7e) | Jan 30, 2024 |
| Unknown       | Unknown                     | Desktop     | [a4eb1c6dda](https://linux-hardware.org/?probe=a4eb1c6dda) | Jan 30, 2024 |
| Unknown       | Unknown                     | Desktop     | [f8b5f64c1e](https://linux-hardware.org/?probe=f8b5f64c1e) | Jan 30, 2024 |
| Lenovo        | ThinkPad T510 43149TG       | Notebook    | [463b653f7a](https://linux-hardware.org/?probe=463b653f7a) | Jan 30, 2024 |
| Medion        | X781X                       | Notebook    | [3665eaa65c](https://linux-hardware.org/?probe=3665eaa65c) | Jan 30, 2024 |
| HP            | 894D                        | Desktop     | [851e68057d](https://linux-hardware.org/?probe=851e68057d) | Jan 30, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [c2ff3b6e2f](https://linux-hardware.org/?probe=c2ff3b6e2f) | Jan 30, 2024 |
| Dell          | 0TDG4V A01                  | Desktop     | [240d51778b](https://linux-hardware.org/?probe=240d51778b) | Jan 30, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [646a977cdd](https://linux-hardware.org/?probe=646a977cdd) | Jan 30, 2024 |
| Intel         | X99 V1.0                    | Desktop     | [202a9720c4](https://linux-hardware.org/?probe=202a9720c4) | Jan 30, 2024 |
| Intel         | NUC7i7DNB J83500-204        | Mini pc     | [2dc40304a3](https://linux-hardware.org/?probe=2dc40304a3) | Jan 30, 2024 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b1b2694b98](https://linux-hardware.org/?probe=b1b2694b98) | Jan 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K370... | Notebook    | [e935a209d7](https://linux-hardware.org/?probe=e935a209d7) | Jan 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K370... | Notebook    | [4a1a726464](https://linux-hardware.org/?probe=4a1a726464) | Jan 30, 2024 |
| Dell          | Latitude 7212 Rugged Ext... | Notebook    | [d21b8c5f4e](https://linux-hardware.org/?probe=d21b8c5f4e) | Jan 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [1ebab4d906](https://linux-hardware.org/?probe=1ebab4d906) | Jan 30, 2024 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | Notebook    | [bf8891bdd5](https://linux-hardware.org/?probe=bf8891bdd5) | Jan 30, 2024 |
| Lenovo        | ThinkPad T410 2537AT1       | Notebook    | [54b5a51811](https://linux-hardware.org/?probe=54b5a51811) | Jan 30, 2024 |
| HP            | Pavilion dv7                | Notebook    | [8aab31766b](https://linux-hardware.org/?probe=8aab31766b) | Jan 30, 2024 |
| ASUSTek       | X540LA                      | Notebook    | [503b80e997](https://linux-hardware.org/?probe=503b80e997) | Jan 30, 2024 |
| HP            | 2AF7                        | Desktop     | [fb8889e84c](https://linux-hardware.org/?probe=fb8889e84c) | Jan 29, 2024 |
| Medion        | B250H4-EM                   | Desktop     | [418b44d0a2](https://linux-hardware.org/?probe=418b44d0a2) | Jan 29, 2024 |
| ASUSTek       | ROG Maximus Z790 DARK HE... | Desktop     | [64433c2a96](https://linux-hardware.org/?probe=64433c2a96) | Jan 29, 2024 |
| Pegatron      | Benicia                     | Desktop     | [b127dc2bc0](https://linux-hardware.org/?probe=b127dc2bc0) | Jan 29, 2024 |
| Intel         | H81                         | Desktop     | [fac0a305d4](https://linux-hardware.org/?probe=fac0a305d4) | Jan 29, 2024 |
| ASUSTek       | UX550VD                     | Notebook    | [3b742650db](https://linux-hardware.org/?probe=3b742650db) | Jan 29, 2024 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [ca9ba6c5ce](https://linux-hardware.org/?probe=ca9ba6c5ce) | Jan 29, 2024 |
| Apple         | MacBookPro4,1               | Notebook    | [2e5f443b99](https://linux-hardware.org/?probe=2e5f443b99) | Jan 29, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [913338a499](https://linux-hardware.org/?probe=913338a499) | Jan 29, 2024 |
| Acer          | Aspire E1-522               | Notebook    | [1dab2e243c](https://linux-hardware.org/?probe=1dab2e243c) | Jan 29, 2024 |
| HP            | ProBook 640 G1              | Notebook    | [7bbe891072](https://linux-hardware.org/?probe=7bbe891072) | Jan 29, 2024 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [dafe3d53e0](https://linux-hardware.org/?probe=dafe3d53e0) | Jan 29, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [a1d3b30464](https://linux-hardware.org/?probe=a1d3b30464) | Jan 29, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [ae5e53e103](https://linux-hardware.org/?probe=ae5e53e103) | Jan 29, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [bc4c195cfe](https://linux-hardware.org/?probe=bc4c195cfe) | Jan 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [3819e0c97d](https://linux-hardware.org/?probe=3819e0c97d) | Jan 29, 2024 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | Desktop     | [21628b2a5b](https://linux-hardware.org/?probe=21628b2a5b) | Jan 29, 2024 |
| ASUSTek       | P5K                         | Desktop     | [2596e1adb2](https://linux-hardware.org/?probe=2596e1adb2) | Jan 29, 2024 |
| Dell          | Latitude 5430 Rugged        | Notebook    | [8708a1170b](https://linux-hardware.org/?probe=8708a1170b) | Jan 29, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [eaf977415d](https://linux-hardware.org/?probe=eaf977415d) | Jan 29, 2024 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | Desktop     | [26ae99cfe2](https://linux-hardware.org/?probe=26ae99cfe2) | Jan 29, 2024 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [856669283d](https://linux-hardware.org/?probe=856669283d) | Jan 29, 2024 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [009120e99a](https://linux-hardware.org/?probe=009120e99a) | Jan 29, 2024 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [fff97c0d16](https://linux-hardware.org/?probe=fff97c0d16) | Jan 29, 2024 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [e6f28cbfba](https://linux-hardware.org/?probe=e6f28cbfba) | Jan 29, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [aeacd97c42](https://linux-hardware.org/?probe=aeacd97c42) | Jan 29, 2024 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [61d19fb0bc](https://linux-hardware.org/?probe=61d19fb0bc) | Jan 29, 2024 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [aa69326408](https://linux-hardware.org/?probe=aa69326408) | Jan 29, 2024 |
| ASUSTek       | G10DK                       | Desktop     | [f5632504cc](https://linux-hardware.org/?probe=f5632504cc) | Jan 29, 2024 |
| ASUSTek       | G10DK                       | Desktop     | [5ef0067e13](https://linux-hardware.org/?probe=5ef0067e13) | Jan 29, 2024 |
| Unknown       | HX90                        | Desktop     | [2d0982fbb6](https://linux-hardware.org/?probe=2d0982fbb6) | Jan 29, 2024 |
| Gigabyte      | Z490 UD                     | Desktop     | [41cff556c1](https://linux-hardware.org/?probe=41cff556c1) | Jan 29, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [0c4fb535dc](https://linux-hardware.org/?probe=0c4fb535dc) | Jan 29, 2024 |
| Dell          | 0C2KJT A00                  | Desktop     | [bc76ac497b](https://linux-hardware.org/?probe=bc76ac497b) | Jan 29, 2024 |
| MSI           | 970A-G46                    | Desktop     | [9a7594f5ae](https://linux-hardware.org/?probe=9a7594f5ae) | Jan 29, 2024 |
| Dell          | 0C2KJT A00                  | Desktop     | [b56c82b709](https://linux-hardware.org/?probe=b56c82b709) | Jan 29, 2024 |
| Foxconn       | 2A8C                        | Desktop     | [042483c307](https://linux-hardware.org/?probe=042483c307) | Jan 29, 2024 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [dc9267becb](https://linux-hardware.org/?probe=dc9267becb) | Jan 29, 2024 |
| Medion        | P15648                      | Notebook    | [d906da0d95](https://linux-hardware.org/?probe=d906da0d95) | Jan 29, 2024 |
| Acer          | TDPS05 R3700                | Desktop     | [d2ef9055f2](https://linux-hardware.org/?probe=d2ef9055f2) | Jan 28, 2024 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [29fcd258c7](https://linux-hardware.org/?probe=29fcd258c7) | Jan 28, 2024 |
| Dell          | 04GJJT A00                  | Desktop     | [5c9882560f](https://linux-hardware.org/?probe=5c9882560f) | Jan 28, 2024 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [5bccdbf478](https://linux-hardware.org/?probe=5bccdbf478) | Jan 28, 2024 |
| HP            | Dragonfly Pro Laptop PC     | Notebook    | [f7605bd832](https://linux-hardware.org/?probe=f7605bd832) | Jan 28, 2024 |
| Biostar       | B550MH                      | Desktop     | [18a98ffa2c](https://linux-hardware.org/?probe=18a98ffa2c) | Jan 28, 2024 |
| Biostar       | B550MH                      | Desktop     | [7e52e1855c](https://linux-hardware.org/?probe=7e52e1855c) | Jan 28, 2024 |
| Unknown       | Unknown                     | Desktop     | [e80d32ade5](https://linux-hardware.org/?probe=e80d32ade5) | Jan 28, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [20b00f9064](https://linux-hardware.org/?probe=20b00f9064) | Jan 28, 2024 |
| Apple         | MacBookAir6,1               | Notebook    | [d508f78053](https://linux-hardware.org/?probe=d508f78053) | Jan 28, 2024 |
| HP            | Notebook                    | Notebook    | [d8a6181633](https://linux-hardware.org/?probe=d8a6181633) | Jan 28, 2024 |
| HP            | ProBook 4530s               | Notebook    | [6135fed286](https://linux-hardware.org/?probe=6135fed286) | Jan 28, 2024 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | Desktop     | [0aa2140ac2](https://linux-hardware.org/?probe=0aa2140ac2) | Jan 28, 2024 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | Desktop     | [752e2156f6](https://linux-hardware.org/?probe=752e2156f6) | Jan 28, 2024 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [7c9fb93a37](https://linux-hardware.org/?probe=7c9fb93a37) | Jan 28, 2024 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [81e9c9a499](https://linux-hardware.org/?probe=81e9c9a499) | Jan 28, 2024 |
| Dell          | 08K0X7 A00                  | Desktop     | [981f5fcf48](https://linux-hardware.org/?probe=981f5fcf48) | Jan 28, 2024 |
| HP            | Pavilion dv6                | Notebook    | [383b87d6a5](https://linux-hardware.org/?probe=383b87d6a5) | Jan 28, 2024 |
| Toshiba       | Satellite P50-B-10Z         | Notebook    | [574103da6a](https://linux-hardware.org/?probe=574103da6a) | Jan 28, 2024 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [cab252fea3](https://linux-hardware.org/?probe=cab252fea3) | Jan 28, 2024 |
| HP            | 82F2 A01                    | Desktop     | [017f111720](https://linux-hardware.org/?probe=017f111720) | Jan 28, 2024 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [f8f08ce899](https://linux-hardware.org/?probe=f8f08ce899) | Jan 28, 2024 |
| Acer          | Aspire VN7-571G             | Notebook    | [b5f8437f3c](https://linux-hardware.org/?probe=b5f8437f3c) | Jan 28, 2024 |
| HP            | ZBook Studio G3             | Notebook    | [136b9a2567](https://linux-hardware.org/?probe=136b9a2567) | Jan 28, 2024 |
| ASRock        | FM2A75M Pro4+               | Desktop     | [d3d40bf0b4](https://linux-hardware.org/?probe=d3d40bf0b4) | Jan 28, 2024 |
| Tyrone Sys... | DIT400TR-48RL Intel Chip... | Server      | [6f84182a9b](https://linux-hardware.org/?probe=6f84182a9b) | Jan 28, 2024 |
| ASUSTek       | P5Q SE2                     | Desktop     | [5aa0059c3f](https://linux-hardware.org/?probe=5aa0059c3f) | Jan 28, 2024 |
| Apple         | MacBookPro14,3              | Notebook    | [1b5bfa9bcb](https://linux-hardware.org/?probe=1b5bfa9bcb) | Jan 28, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [49e891b67d](https://linux-hardware.org/?probe=49e891b67d) | Jan 28, 2024 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [c2d0dabb5e](https://linux-hardware.org/?probe=c2d0dabb5e) | Jan 28, 2024 |
| Dell          | 0D24M8 A01                  | Desktop     | [db11402dbf](https://linux-hardware.org/?probe=db11402dbf) | Jan 28, 2024 |
| Dell          | G15 5511                    | Notebook    | [53225a4d52](https://linux-hardware.org/?probe=53225a4d52) | Jan 28, 2024 |
| Dell          | 03X6X0 A06                  | Server      | [685323f0f3](https://linux-hardware.org/?probe=685323f0f3) | Jan 28, 2024 |
| Dell          | Inspiron 3537               | Notebook    | [e91c3bfd73](https://linux-hardware.org/?probe=e91c3bfd73) | Jan 28, 2024 |
| Dell          | Inspiron 3537               | Notebook    | [0ee7687e3f](https://linux-hardware.org/?probe=0ee7687e3f) | Jan 28, 2024 |
| Acer          | Spin SP314-21N              | Convertible | [e90ff686ca](https://linux-hardware.org/?probe=e90ff686ca) | Jan 28, 2024 |
| Google        | Elemi                       | Notebook    | [f767c4fdbb](https://linux-hardware.org/?probe=f767c4fdbb) | Jan 28, 2024 |
| Medion        | D3F3-EM                     | Desktop     | [b49f3c529a](https://linux-hardware.org/?probe=b49f3c529a) | Jan 28, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3d0d9dce8a](https://linux-hardware.org/?probe=3d0d9dce8a) | Jan 28, 2024 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [465b69ceca](https://linux-hardware.org/?probe=465b69ceca) | Jan 28, 2024 |
| Dell          | Precision M4700             | Notebook    | [ed04788986](https://linux-hardware.org/?probe=ed04788986) | Jan 28, 2024 |
| ASUSTek       | P8B75-M                     | Desktop     | [ad1a5f6757](https://linux-hardware.org/?probe=ad1a5f6757) | Jan 28, 2024 |
| Acer          | Aspire A515-46              | Notebook    | [935246f473](https://linux-hardware.org/?probe=935246f473) | Jan 28, 2024 |
| Acer          | Aspire A515-46              | Notebook    | [f023bc003e](https://linux-hardware.org/?probe=f023bc003e) | Jan 27, 2024 |
| Dell          | Latitude 7490               | Notebook    | [8687d67e07](https://linux-hardware.org/?probe=8687d67e07) | Jan 27, 2024 |
| Dell          | 0VHWTR A02                  | Desktop     | [a40f7ff2de](https://linux-hardware.org/?probe=a40f7ff2de) | Jan 27, 2024 |
| HP            | Notebook                    | Notebook    | [78ffba1358](https://linux-hardware.org/?probe=78ffba1358) | Jan 27, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [8bca4f366d](https://linux-hardware.org/?probe=8bca4f366d) | Jan 27, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [ee59cf62cb](https://linux-hardware.org/?probe=ee59cf62cb) | Jan 27, 2024 |
| Dell          | Inspiron 5570               | Notebook    | [0fce3dbe59](https://linux-hardware.org/?probe=0fce3dbe59) | Jan 27, 2024 |
| HP            | 8105                        | Desktop     | [41fdf37154](https://linux-hardware.org/?probe=41fdf37154) | Jan 27, 2024 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [f914166828](https://linux-hardware.org/?probe=f914166828) | Jan 27, 2024 |
| ABIT          | AB9/AB9RPO                  | Desktop     | [01c28bcaa5](https://linux-hardware.org/?probe=01c28bcaa5) | Jan 27, 2024 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [5f28b98de6](https://linux-hardware.org/?probe=5f28b98de6) | Jan 27, 2024 |
| Dell          | Latitude 7390 2-in-1        | Notebook    | [d57566edb3](https://linux-hardware.org/?probe=d57566edb3) | Jan 27, 2024 |
| Dell          | Latitude 7390 2-in-1        | Notebook    | [26a44b8cab](https://linux-hardware.org/?probe=26a44b8cab) | Jan 27, 2024 |
| Lenovo        | ThinkPad X230 2325BA3       | Notebook    | [700fc5c431](https://linux-hardware.org/?probe=700fc5c431) | Jan 27, 2024 |
| Apple         | Mac-F221BEC8                | Desktop     | [9fb7827c5f](https://linux-hardware.org/?probe=9fb7827c5f) | Jan 27, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [03351f8523](https://linux-hardware.org/?probe=03351f8523) | Jan 27, 2024 |
| MSI           | A320M GRENADE               | Desktop     | [0a605bfdee](https://linux-hardware.org/?probe=0a605bfdee) | Jan 27, 2024 |
| Acer          | Aspire A715-51G             | Notebook    | [e6b8ceb566](https://linux-hardware.org/?probe=e6b8ceb566) | Jan 27, 2024 |
| ASRock        | ION3D-HT                    | Desktop     | [393d01f3c9](https://linux-hardware.org/?probe=393d01f3c9) | Jan 27, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a6b046b2b7](https://linux-hardware.org/?probe=a6b046b2b7) | Jan 27, 2024 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [46b23b4469](https://linux-hardware.org/?probe=46b23b4469) | Jan 27, 2024 |
| Dell          | Latitude E7450              | Notebook    | [d427866522](https://linux-hardware.org/?probe=d427866522) | Jan 27, 2024 |
| Dell          | XPS 9320                    | Notebook    | [0214714fb9](https://linux-hardware.org/?probe=0214714fb9) | Jan 27, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [dfb6b2a1c8](https://linux-hardware.org/?probe=dfb6b2a1c8) | Jan 27, 2024 |
| ASUSTek       | NODUSM3                     | Desktop     | [b7a885758d](https://linux-hardware.org/?probe=b7a885758d) | Jan 27, 2024 |
| HONOR         | FRI-FXX                     | Notebook    | [c9b0b584fc](https://linux-hardware.org/?probe=c9b0b584fc) | Jan 27, 2024 |
| Fujitsu       | FARQ10003                   | Notebook    | [6084280fc9](https://linux-hardware.org/?probe=6084280fc9) | Jan 27, 2024 |
| System76      | Oryx Pro                    | Notebook    | [faac85b51d](https://linux-hardware.org/?probe=faac85b51d) | Jan 27, 2024 |
| Dell          | Latitude E7440              | Notebook    | [8d31059748](https://linux-hardware.org/?probe=8d31059748) | Jan 27, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [2a81d5f313](https://linux-hardware.org/?probe=2a81d5f313) | Jan 27, 2024 |
| ASUSTek       | K52JT                       | Notebook    | [dd44051584](https://linux-hardware.org/?probe=dd44051584) | Jan 27, 2024 |
| JGINYUE       | H97M-VH V2.1                | Desktop     | [f4baebb6b0](https://linux-hardware.org/?probe=f4baebb6b0) | Jan 27, 2024 |
| JGINYUE       | H97M-VH V2.1                | Desktop     | [7983ca3c2d](https://linux-hardware.org/?probe=7983ca3c2d) | Jan 27, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9eeddc4566](https://linux-hardware.org/?probe=9eeddc4566) | Jan 27, 2024 |
| ASUSTek       | PN40                        | Mini pc     | [fe9a58272f](https://linux-hardware.org/?probe=fe9a58272f) | Jan 27, 2024 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [fe40514847](https://linux-hardware.org/?probe=fe40514847) | Jan 27, 2024 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [931f000daf](https://linux-hardware.org/?probe=931f000daf) | Jan 27, 2024 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [bcbec144f6](https://linux-hardware.org/?probe=bcbec144f6) | Jan 27, 2024 |
| Dell          | Inspiron 13-5378            | Notebook    | [a742fdf96d](https://linux-hardware.org/?probe=a742fdf96d) | Jan 27, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [5fac7fde98](https://linux-hardware.org/?probe=5fac7fde98) | Jan 27, 2024 |
| Dell          | 081N4V A07                  | Server      | [fac7b88ba4](https://linux-hardware.org/?probe=fac7b88ba4) | Jan 27, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [9518bd6b03](https://linux-hardware.org/?probe=9518bd6b03) | Jan 27, 2024 |
| Dell          | 081N4V A07                  | Server      | [dcc52ce1cc](https://linux-hardware.org/?probe=dcc52ce1cc) | Jan 27, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [95541e0847](https://linux-hardware.org/?probe=95541e0847) | Jan 27, 2024 |
| Dell          | Latitude E5250              | Notebook    | [29a9f5d01c](https://linux-hardware.org/?probe=29a9f5d01c) | Jan 26, 2024 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [6431000318](https://linux-hardware.org/?probe=6431000318) | Jan 26, 2024 |
| Fujitsu       | LIFEBOOK E548               | Notebook    | [515098ce8f](https://linux-hardware.org/?probe=515098ce8f) | Jan 26, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [5591f82595](https://linux-hardware.org/?probe=5591f82595) | Jan 26, 2024 |
| Dell          | Precision 5680              | Notebook    | [5159fe0624](https://linux-hardware.org/?probe=5159fe0624) | Jan 26, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [fa96de4635](https://linux-hardware.org/?probe=fa96de4635) | Jan 26, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [90c57cfb01](https://linux-hardware.org/?probe=90c57cfb01) | Jan 26, 2024 |
| ECS           | APLD-MINI                   | Desktop     | [51b4a0993d](https://linux-hardware.org/?probe=51b4a0993d) | Jan 26, 2024 |
| HP            | 15 Notebook PC              | Notebook    | [9f12f6bda7](https://linux-hardware.org/?probe=9f12f6bda7) | Jan 26, 2024 |
| Dell          | Latitude 5521               | Notebook    | [0524c08c30](https://linux-hardware.org/?probe=0524c08c30) | Jan 26, 2024 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [a354ee36fe](https://linux-hardware.org/?probe=a354ee36fe) | Jan 26, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [5859ff1ab1](https://linux-hardware.org/?probe=5859ff1ab1) | Jan 26, 2024 |
| ASRock        | X570 Pro4                   | Desktop     | [ca9d92fde3](https://linux-hardware.org/?probe=ca9d92fde3) | Jan 26, 2024 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [27fa584690](https://linux-hardware.org/?probe=27fa584690) | Jan 26, 2024 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [4b630c4e1e](https://linux-hardware.org/?probe=4b630c4e1e) | Jan 26, 2024 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [c639997108](https://linux-hardware.org/?probe=c639997108) | Jan 26, 2024 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [710334dba6](https://linux-hardware.org/?probe=710334dba6) | Jan 26, 2024 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [30193a9845](https://linux-hardware.org/?probe=30193a9845) | Jan 26, 2024 |
| ASRock        | H97 Anniversary             | Desktop     | [b33697ceee](https://linux-hardware.org/?probe=b33697ceee) | Jan 26, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [b010be0d2f](https://linux-hardware.org/?probe=b010be0d2f) | Jan 26, 2024 |
| Lenovo        | ThinkPad T580 20LAS62M07    | Notebook    | [d55ac7557b](https://linux-hardware.org/?probe=d55ac7557b) | Jan 26, 2024 |
| MSI           | B250M BAZOOKA               | Desktop     | [0bd7085870](https://linux-hardware.org/?probe=0bd7085870) | Jan 26, 2024 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [87d6398f5b](https://linux-hardware.org/?probe=87d6398f5b) | Jan 26, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [c2c69a026a](https://linux-hardware.org/?probe=c2c69a026a) | Jan 26, 2024 |
| HP            | 1998                        | Desktop     | [b1431c9048](https://linux-hardware.org/?probe=b1431c9048) | Jan 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [ca9dd04b16](https://linux-hardware.org/?probe=ca9dd04b16) | Jan 26, 2024 |
| HP            | 8719                        | Desktop     | [42bc597317](https://linux-hardware.org/?probe=42bc597317) | Jan 26, 2024 |
| ASUSTek       | B400VC                      | Notebook    | [af39cde6d9](https://linux-hardware.org/?probe=af39cde6d9) | Jan 26, 2024 |
| HP            | 650                         | Notebook    | [d440902ea2](https://linux-hardware.org/?probe=d440902ea2) | Jan 26, 2024 |
| Toshiba       | Satellite C670D-12Q         | Notebook    | [a9a2651adc](https://linux-hardware.org/?probe=a9a2651adc) | Jan 26, 2024 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [42e8e68344](https://linux-hardware.org/?probe=42e8e68344) | Jan 26, 2024 |
| Supermicro    | X10DDW-i                    | Desktop     | [6a9650896a](https://linux-hardware.org/?probe=6a9650896a) | Jan 26, 2024 |
| Dell          | XPS 9320                    | Notebook    | [ed6a1f51f5](https://linux-hardware.org/?probe=ed6a1f51f5) | Jan 26, 2024 |
| HP            | Pavilion 15                 | Notebook    | [3aed9dffe5](https://linux-hardware.org/?probe=3aed9dffe5) | Jan 26, 2024 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [32d1dff107](https://linux-hardware.org/?probe=32d1dff107) | Jan 26, 2024 |
| HP            | Pavilion 15                 | Notebook    | [5d449f9a23](https://linux-hardware.org/?probe=5d449f9a23) | Jan 26, 2024 |
| Dell          | Latitude 5490               | Notebook    | [f1fe39af02](https://linux-hardware.org/?probe=f1fe39af02) | Jan 26, 2024 |
| ASUSTek       | ROG Maximus Z790 DARK HE... | Desktop     | [aa9e38d0e2](https://linux-hardware.org/?probe=aa9e38d0e2) | Jan 26, 2024 |
| Dell          | 02YYK5 A00                  | Desktop     | [60522355ee](https://linux-hardware.org/?probe=60522355ee) | Jan 26, 2024 |
| HP            | Pavilion dv6                | Notebook    | [9a15d7d823](https://linux-hardware.org/?probe=9a15d7d823) | Jan 26, 2024 |
| Google        | Kench                       | Desktop     | [42065dff7f](https://linux-hardware.org/?probe=42065dff7f) | Jan 26, 2024 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [915a8fc837](https://linux-hardware.org/?probe=915a8fc837) | Jan 26, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [6faf9b7c3a](https://linux-hardware.org/?probe=6faf9b7c3a) | Jan 26, 2024 |
| NCR           | Monaco BIOS.9.1             | Desktop     | [98ed4e9a82](https://linux-hardware.org/?probe=98ed4e9a82) | Jan 26, 2024 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [5b803efc86](https://linux-hardware.org/?probe=5b803efc86) | Jan 26, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [e91202934d](https://linux-hardware.org/?probe=e91202934d) | Jan 26, 2024 |
| GEEKOM        | A5                          | Desktop     | [2408e3a6dc](https://linux-hardware.org/?probe=2408e3a6dc) | Jan 26, 2024 |
| Dell          | 04Y8V0 A02                  | Desktop     | [34289f06cd](https://linux-hardware.org/?probe=34289f06cd) | Jan 26, 2024 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [903d800136](https://linux-hardware.org/?probe=903d800136) | Jan 26, 2024 |
| GEEKOM        | A5                          | Desktop     | [4818316c00](https://linux-hardware.org/?probe=4818316c00) | Jan 26, 2024 |
| Google        | Markarth                    | Notebook    | [39dface7d9](https://linux-hardware.org/?probe=39dface7d9) | Jan 26, 2024 |
| Dell          | 0C2XKD A01                  | Desktop     | [f32c18bab1](https://linux-hardware.org/?probe=f32c18bab1) | Jan 25, 2024 |
| ASUSTek       | Z170-K                      | Desktop     | [277fb7b364](https://linux-hardware.org/?probe=277fb7b364) | Jan 25, 2024 |
| Foxconn       | Cinema Series FAB           | Desktop     | [de1e89f80f](https://linux-hardware.org/?probe=de1e89f80f) | Jan 25, 2024 |
| ASRock        | Z77 Extreme4                | Desktop     | [4685f2b1e9](https://linux-hardware.org/?probe=4685f2b1e9) | Jan 25, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [565926342b](https://linux-hardware.org/?probe=565926342b) | Jan 25, 2024 |
| Dell          | Inspiron 3558               | Notebook    | [7972792612](https://linux-hardware.org/?probe=7972792612) | Jan 25, 2024 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [7b16c2c1bc](https://linux-hardware.org/?probe=7b16c2c1bc) | Jan 25, 2024 |
| Lenovo        | ThinkPad X230 2325BA3       | Notebook    | [279854db8e](https://linux-hardware.org/?probe=279854db8e) | Jan 25, 2024 |
| Toshiba       | Satellite P70-B             | Notebook    | [3e21232f45](https://linux-hardware.org/?probe=3e21232f45) | Jan 25, 2024 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [8dd7c2b2aa](https://linux-hardware.org/?probe=8dd7c2b2aa) | Jan 25, 2024 |
| Dell          | 0HHV7N A00                  | Desktop     | [fda3733e63](https://linux-hardware.org/?probe=fda3733e63) | Jan 25, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [41817d480d](https://linux-hardware.org/?probe=41817d480d) | Jan 25, 2024 |
| Dell          | Inspiron 3558               | Notebook    | [4d1b20eaa7](https://linux-hardware.org/?probe=4d1b20eaa7) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [e6681b71bc](https://linux-hardware.org/?probe=e6681b71bc) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [65a3715aa3](https://linux-hardware.org/?probe=65a3715aa3) | Jan 25, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [aac76b979a](https://linux-hardware.org/?probe=aac76b979a) | Jan 25, 2024 |
| Dell          | 0PTTT9 A01                  | Desktop     | [310d107f7d](https://linux-hardware.org/?probe=310d107f7d) | Jan 25, 2024 |
| HP            | ProBook 450 G1              | Notebook    | [97c68df9c0](https://linux-hardware.org/?probe=97c68df9c0) | Jan 25, 2024 |
| HP            | 2129                        | Desktop     | [9617c50324](https://linux-hardware.org/?probe=9617c50324) | Jan 25, 2024 |
| HUAWEI        | BC11HGSA0 V100R003          | Server      | [585e78ced6](https://linux-hardware.org/?probe=585e78ced6) | Jan 25, 2024 |
| Lenovo        | 3106 SDK0J40709 WIN 3259... | Desktop     | [bbc8707e00](https://linux-hardware.org/?probe=bbc8707e00) | Jan 25, 2024 |
| ASRock        | A520M-HDV                   | Desktop     | [db1260e2b7](https://linux-hardware.org/?probe=db1260e2b7) | Jan 25, 2024 |
| Dell          | 0GCY4M A01                  | Desktop     | [7570087915](https://linux-hardware.org/?probe=7570087915) | Jan 25, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [cfa1bbba1a](https://linux-hardware.org/?probe=cfa1bbba1a) | Jan 25, 2024 |
| HUAWEI        | BC11HGSA0 V100R003          | Server      | [234bc0cc22](https://linux-hardware.org/?probe=234bc0cc22) | Jan 25, 2024 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [8e84a9a187](https://linux-hardware.org/?probe=8e84a9a187) | Jan 25, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [e44bf066a4](https://linux-hardware.org/?probe=e44bf066a4) | Jan 25, 2024 |
| ATOPNUC       | MA90                        | Mini pc     | [93bc47fa05](https://linux-hardware.org/?probe=93bc47fa05) | Jan 25, 2024 |
| Shuttle       | FG41 V20                    | Desktop     | [9eeb0902c1](https://linux-hardware.org/?probe=9eeb0902c1) | Jan 25, 2024 |
| Gigabyte      | B450M GAMING                | Desktop     | [01a72ce274](https://linux-hardware.org/?probe=01a72ce274) | Jan 25, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CBA... | Notebook    | [a0b0aa335e](https://linux-hardware.org/?probe=a0b0aa335e) | Jan 25, 2024 |
| Dell          | Inspiron 5521               | Notebook    | [18fc8668de](https://linux-hardware.org/?probe=18fc8668de) | Jan 25, 2024 |
| Acer          | Aspire A317-53              | Notebook    | [9b9d2bfdc3](https://linux-hardware.org/?probe=9b9d2bfdc3) | Jan 25, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [969d0f1bef](https://linux-hardware.org/?probe=969d0f1bef) | Jan 25, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CBA... | Notebook    | [2add8788ab](https://linux-hardware.org/?probe=2add8788ab) | Jan 25, 2024 |
| HP            | 2000                        | Notebook    | [f1e38c4df2](https://linux-hardware.org/?probe=f1e38c4df2) | Jan 25, 2024 |
| GEEKOM        | Mini IT13                   | Desktop     | [db1f38bd8c](https://linux-hardware.org/?probe=db1f38bd8c) | Jan 25, 2024 |
| Dell          | Inspiron 3581               | Notebook    | [7a5cfbd8d3](https://linux-hardware.org/?probe=7a5cfbd8d3) | Jan 25, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [b892b5b8a4](https://linux-hardware.org/?probe=b892b5b8a4) | Jan 25, 2024 |
| Dell          | Inspiron 3581               | Notebook    | [dbf2745f1f](https://linux-hardware.org/?probe=dbf2745f1f) | Jan 25, 2024 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [2851a608c0](https://linux-hardware.org/?probe=2851a608c0) | Jan 25, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [6c409399d4](https://linux-hardware.org/?probe=6c409399d4) | Jan 25, 2024 |
| Lenovo        | 3740 NOK                    | Desktop     | [2bfb559750](https://linux-hardware.org/?probe=2bfb559750) | Jan 25, 2024 |
| Acer          | Nitro AN515-57              | Notebook    | [052f6bc120](https://linux-hardware.org/?probe=052f6bc120) | Jan 25, 2024 |
| ASRock        | H370M-HDV                   | Desktop     | [86e43e96f0](https://linux-hardware.org/?probe=86e43e96f0) | Jan 25, 2024 |
| Acer          | Swift SF314-57              | Notebook    | [352b6edd13](https://linux-hardware.org/?probe=352b6edd13) | Jan 25, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [24a5e0a03c](https://linux-hardware.org/?probe=24a5e0a03c) | Jan 25, 2024 |
| Intel         | B75                         | Desktop     | [b9a4ea0b9b](https://linux-hardware.org/?probe=b9a4ea0b9b) | Jan 25, 2024 |
| Dell          | 0N4YC8 A00                  | Desktop     | [03750ea62c](https://linux-hardware.org/?probe=03750ea62c) | Jan 25, 2024 |
| Gigabyte      | B450M GAMING                | Desktop     | [c25c76b288](https://linux-hardware.org/?probe=c25c76b288) | Jan 25, 2024 |
| MSI           | MEG X399 CREATION           | Desktop     | [b598a0fd29](https://linux-hardware.org/?probe=b598a0fd29) | Jan 25, 2024 |
| Lenovo        | ThinkPad T470 20HES18S02    | Notebook    | [9f18c011e4](https://linux-hardware.org/?probe=9f18c011e4) | Jan 25, 2024 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [8c1fb214b8](https://linux-hardware.org/?probe=8c1fb214b8) | Jan 25, 2024 |
| HP            | ZBook 15v G5                | Notebook    | [8e114d2ba9](https://linux-hardware.org/?probe=8e114d2ba9) | Jan 25, 2024 |
| Lenovo        | ThinkPad L13 Yoga 20R6S0... | Convertible | [b992ee7c54](https://linux-hardware.org/?probe=b992ee7c54) | Jan 25, 2024 |
| Dell          | Latitude E5470              | Notebook    | [25f5da470b](https://linux-hardware.org/?probe=25f5da470b) | Jan 24, 2024 |
| ASUSTek       | N551VW                      | Notebook    | [2a8f1d7cc1](https://linux-hardware.org/?probe=2a8f1d7cc1) | Jan 24, 2024 |
| Acer          | Nitro AN515-52              | Notebook    | [36dc15871c](https://linux-hardware.org/?probe=36dc15871c) | Jan 24, 2024 |
| Lenovo        | IdeaPad 3-15ALC6 82KU       | Notebook    | [c91921bbe1](https://linux-hardware.org/?probe=c91921bbe1) | Jan 24, 2024 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [f3512d75e9](https://linux-hardware.org/?probe=f3512d75e9) | Jan 24, 2024 |
| HP            | 15                          | Notebook    | [6cd885c267](https://linux-hardware.org/?probe=6cd885c267) | Jan 24, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [f904e3ce10](https://linux-hardware.org/?probe=f904e3ce10) | Jan 24, 2024 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [4bcfb579e2](https://linux-hardware.org/?probe=4bcfb579e2) | Jan 24, 2024 |
| Lenovo        | ThinkPad T540p 20BFS2100... | Notebook    | [1bf8988f36](https://linux-hardware.org/?probe=1bf8988f36) | Jan 24, 2024 |
| Lenovo        | ThinkPad T540p 20BFS2100... | Notebook    | [08b929fe37](https://linux-hardware.org/?probe=08b929fe37) | Jan 24, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [606adf78f9](https://linux-hardware.org/?probe=606adf78f9) | Jan 24, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [86ff649a4d](https://linux-hardware.org/?probe=86ff649a4d) | Jan 24, 2024 |
| Acer          | Aspire V3-331               | Notebook    | [002e761d1d](https://linux-hardware.org/?probe=002e761d1d) | Jan 24, 2024 |
| Acer          | Aspire V3-331               | Notebook    | [944c9b110c](https://linux-hardware.org/?probe=944c9b110c) | Jan 24, 2024 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [f917755de4](https://linux-hardware.org/?probe=f917755de4) | Jan 24, 2024 |
| Supermicro    | X8DTU                       | Server      | [c6e21da64a](https://linux-hardware.org/?probe=c6e21da64a) | Jan 24, 2024 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [642c49982c](https://linux-hardware.org/?probe=642c49982c) | Jan 24, 2024 |
| Dell          | Latitude 7490               | Notebook    | [d2085f3674](https://linux-hardware.org/?probe=d2085f3674) | Jan 24, 2024 |
| ASUSTek       | X541UV                      | Notebook    | [7df0d2b4af](https://linux-hardware.org/?probe=7df0d2b4af) | Jan 24, 2024 |
| Google        | Markarth                    | Notebook    | [2258b38e4b](https://linux-hardware.org/?probe=2258b38e4b) | Jan 24, 2024 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [e78a5c9804](https://linux-hardware.org/?probe=e78a5c9804) | Jan 24, 2024 |
| Dell          | Latitude E6500              | Notebook    | [7c35926249](https://linux-hardware.org/?probe=7c35926249) | Jan 24, 2024 |
| HP            | 821D                        | Desktop     | [c56ee90d6b](https://linux-hardware.org/?probe=c56ee90d6b) | Jan 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [88f29ebedf](https://linux-hardware.org/?probe=88f29ebedf) | Jan 24, 2024 |
| Lenovo        | ThinkPad T530 24297XG       | Notebook    | [9b6f11b3a9](https://linux-hardware.org/?probe=9b6f11b3a9) | Jan 24, 2024 |
| Ciara Tech... | Q77M-XG                     | Desktop     | [aba2d99413](https://linux-hardware.org/?probe=aba2d99413) | Jan 24, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [dc91d2aa92](https://linux-hardware.org/?probe=dc91d2aa92) | Jan 24, 2024 |
| Acer          | Aspire A315-57G             | Notebook    | [ed1eb72a6d](https://linux-hardware.org/?probe=ed1eb72a6d) | Jan 24, 2024 |
| ASUSTek       | M4A77T                      | Desktop     | [082bd06cdc](https://linux-hardware.org/?probe=082bd06cdc) | Jan 24, 2024 |
| HP            | 8053                        | Desktop     | [ecca7b4395](https://linux-hardware.org/?probe=ecca7b4395) | Jan 24, 2024 |
| Fujitsu       | D3531-A1 S26361-D3531-A1    | Desktop     | [db6de09144](https://linux-hardware.org/?probe=db6de09144) | Jan 24, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [873da1ef71](https://linux-hardware.org/?probe=873da1ef71) | Jan 24, 2024 |
| Unknown       | NVIDIA Orin NX Developer... | Soc         | [9b332fb795](https://linux-hardware.org/?probe=9b332fb795) | Jan 24, 2024 |
| Dell          | Latitude 7410               | Notebook    | [cbb6638a4d](https://linux-hardware.org/?probe=cbb6638a4d) | Jan 24, 2024 |
| BESSTAR Te... | VB9                         | All in one  | [864cbd6a4c](https://linux-hardware.org/?probe=864cbd6a4c) | Jan 24, 2024 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [7f0a2dd840](https://linux-hardware.org/?probe=7f0a2dd840) | Jan 24, 2024 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [2493ce70f4](https://linux-hardware.org/?probe=2493ce70f4) | Jan 24, 2024 |
| Acer          | Nitro AN515-45              | Notebook    | [decd7eb6dc](https://linux-hardware.org/?probe=decd7eb6dc) | Jan 24, 2024 |
| Lenovo        | ThinkPad L13 Yoga 20R6S0... | Convertible | [612b433dc0](https://linux-hardware.org/?probe=612b433dc0) | Jan 24, 2024 |
| Dell          | 0XKH0D A02                  | Desktop     | [7ed5013174](https://linux-hardware.org/?probe=7ed5013174) | Jan 24, 2024 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [551769e726](https://linux-hardware.org/?probe=551769e726) | Jan 24, 2024 |
| Dell          | Inspiron 7375               | Notebook    | [cd6587d15b](https://linux-hardware.org/?probe=cd6587d15b) | Jan 24, 2024 |
| ASUSTek       | G750JM                      | Notebook    | [82e5873786](https://linux-hardware.org/?probe=82e5873786) | Jan 24, 2024 |
| MSI           | H110M PRO-VD                | Desktop     | [208d27435c](https://linux-hardware.org/?probe=208d27435c) | Jan 24, 2024 |
| Apple         | MacBookAir6,1               | Notebook    | [b687521689](https://linux-hardware.org/?probe=b687521689) | Jan 24, 2024 |
| ASUSTek       | ROG Rampage VI EXTREME E... | Desktop     | [299dd0311b](https://linux-hardware.org/?probe=299dd0311b) | Jan 24, 2024 |
| ASUSTek       | Z97-A-USB31                 | Desktop     | [1fe92d4fbe](https://linux-hardware.org/?probe=1fe92d4fbe) | Jan 24, 2024 |
| Dell          | Inspiron 5570               | Notebook    | [7c453fba6f](https://linux-hardware.org/?probe=7c453fba6f) | Jan 23, 2024 |
| Dell          | Precision 5570              | Notebook    | [e6e937745c](https://linux-hardware.org/?probe=e6e937745c) | Jan 23, 2024 |
| Dell          | Studio 1737                 | Notebook    | [521626cdc5](https://linux-hardware.org/?probe=521626cdc5) | Jan 23, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [0d4e165d3f](https://linux-hardware.org/?probe=0d4e165d3f) | Jan 23, 2024 |
| ASUSTek       | D500SA                      | Desktop     | [91815478a7](https://linux-hardware.org/?probe=91815478a7) | Jan 23, 2024 |
| Dell          | 02YYK5 A01                  | Desktop     | [092dabd325](https://linux-hardware.org/?probe=092dabd325) | Jan 23, 2024 |
| Dell          | 0Y7WYT A00                  | Desktop     | [4069a89cac](https://linux-hardware.org/?probe=4069a89cac) | Jan 23, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [122f69f8c5](https://linux-hardware.org/?probe=122f69f8c5) | Jan 23, 2024 |
| Dell          | Inspiron 5406 2n1           | Convertible | [24312a6f12](https://linux-hardware.org/?probe=24312a6f12) | Jan 23, 2024 |
| ASRock        | H110M-DVS R2.0              | Desktop     | [68583ae434](https://linux-hardware.org/?probe=68583ae434) | Jan 23, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [cf3c2deee4](https://linux-hardware.org/?probe=cf3c2deee4) | Jan 23, 2024 |
| ASRock        | Z490 Extreme4               | Desktop     | [c3fc4d088b](https://linux-hardware.org/?probe=c3fc4d088b) | Jan 23, 2024 |
| Lenovo        | ThinkPad T420s 4174HR1      | Notebook    | [ab4b7bc31f](https://linux-hardware.org/?probe=ab4b7bc31f) | Jan 23, 2024 |
| Lenovo        | ThinkPad W541 20EGS3630P    | Notebook    | [1cca38d87f](https://linux-hardware.org/?probe=1cca38d87f) | Jan 23, 2024 |
| Dell          | 06X1TJ A00                  | Desktop     | [5eb76b0285](https://linux-hardware.org/?probe=5eb76b0285) | Jan 23, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [7ea2706c0f](https://linux-hardware.org/?probe=7ea2706c0f) | Jan 23, 2024 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [85a99e5858](https://linux-hardware.org/?probe=85a99e5858) | Jan 23, 2024 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [7c041036d7](https://linux-hardware.org/?probe=7c041036d7) | Jan 23, 2024 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [a606bceea5](https://linux-hardware.org/?probe=a606bceea5) | Jan 23, 2024 |
| Dell          | Latitude 5521               | Notebook    | [34567d3078](https://linux-hardware.org/?probe=34567d3078) | Jan 23, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [920e34bee4](https://linux-hardware.org/?probe=920e34bee4) | Jan 23, 2024 |
| Acer          | Aspire A315-58              | Notebook    | [286a2dcf7a](https://linux-hardware.org/?probe=286a2dcf7a) | Jan 23, 2024 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [5bd83d3f0c](https://linux-hardware.org/?probe=5bd83d3f0c) | Jan 23, 2024 |
| ASUSTek       | Berkeley                    | Desktop     | [c7d349a7f0](https://linux-hardware.org/?probe=c7d349a7f0) | Jan 23, 2024 |
| HP            | ProBook 455 G1              | Notebook    | [224d863e1d](https://linux-hardware.org/?probe=224d863e1d) | Jan 23, 2024 |
| Dell          | Vostro 5490                 | Notebook    | [ef2aff4ed1](https://linux-hardware.org/?probe=ef2aff4ed1) | Jan 23, 2024 |
| AZW           | Z83 V                       | Notebook    | [eed16e1e68](https://linux-hardware.org/?probe=eed16e1e68) | Jan 23, 2024 |
| Dell          | Latitude 5521               | Notebook    | [76aa51e658](https://linux-hardware.org/?probe=76aa51e658) | Jan 23, 2024 |
| AZW           | Z83 V                       | Notebook    | [b9b8c82621](https://linux-hardware.org/?probe=b9b8c82621) | Jan 23, 2024 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [be74f076bd](https://linux-hardware.org/?probe=be74f076bd) | Jan 23, 2024 |
| Dell          | Precision 5540              | Notebook    | [604697c5db](https://linux-hardware.org/?probe=604697c5db) | Jan 23, 2024 |
| Dell          | Latitude 5480               | Notebook    | [45ac237d79](https://linux-hardware.org/?probe=45ac237d79) | Jan 23, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [c8dc8a63fb](https://linux-hardware.org/?probe=c8dc8a63fb) | Jan 23, 2024 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [c2d6eded11](https://linux-hardware.org/?probe=c2d6eded11) | Jan 23, 2024 |
| Lenovo        | ThinkPad L15 Gen 3 21C4S... | Notebook    | [4f812aeb52](https://linux-hardware.org/?probe=4f812aeb52) | Jan 23, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [b126f7be3d](https://linux-hardware.org/?probe=b126f7be3d) | Jan 23, 2024 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [988f12d3d7](https://linux-hardware.org/?probe=988f12d3d7) | Jan 23, 2024 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [24ff9b0160](https://linux-hardware.org/?probe=24ff9b0160) | Jan 23, 2024 |
| ASUSTek       | X556UAK                     | Notebook    | [bd3a035156](https://linux-hardware.org/?probe=bd3a035156) | Jan 23, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [4e9d2ab8c6](https://linux-hardware.org/?probe=4e9d2ab8c6) | Jan 23, 2024 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [a15d748e41](https://linux-hardware.org/?probe=a15d748e41) | Jan 23, 2024 |
| Google        | Woomax                      | Notebook    | [8b76a06477](https://linux-hardware.org/?probe=8b76a06477) | Jan 23, 2024 |
| AMI           | Intel                       | Desktop     | [5085eba8b2](https://linux-hardware.org/?probe=5085eba8b2) | Jan 23, 2024 |
| Pegatron      | Benicia                     | Desktop     | [eec77bbd70](https://linux-hardware.org/?probe=eec77bbd70) | Jan 23, 2024 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [3d55ffe30d](https://linux-hardware.org/?probe=3d55ffe30d) | Jan 23, 2024 |
| HP            | Pavilion dv5                | Notebook    | [6fdec1f88a](https://linux-hardware.org/?probe=6fdec1f88a) | Jan 23, 2024 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [27878d88fd](https://linux-hardware.org/?probe=27878d88fd) | Jan 23, 2024 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [a84ee0f485](https://linux-hardware.org/?probe=a84ee0f485) | Jan 23, 2024 |
| ASUSTek       | T100HAN                     | Notebook    | [66829eb63f](https://linux-hardware.org/?probe=66829eb63f) | Jan 23, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [19161eac10](https://linux-hardware.org/?probe=19161eac10) | Jan 22, 2024 |
| Acer          | Aspire A315-58              | Notebook    | [d5c1dc774a](https://linux-hardware.org/?probe=d5c1dc774a) | Jan 22, 2024 |
| Dell          | Inspiron 5520               | Notebook    | [6d64beac72](https://linux-hardware.org/?probe=6d64beac72) | Jan 22, 2024 |
| Dell          | Latitude 7430               | Notebook    | [668299aad7](https://linux-hardware.org/?probe=668299aad7) | Jan 22, 2024 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [615b7dc324](https://linux-hardware.org/?probe=615b7dc324) | Jan 22, 2024 |
| Dell          | Inspiron 5557               | Notebook    | [e331563298](https://linux-hardware.org/?probe=e331563298) | Jan 22, 2024 |
| Lenovo        | ThinkPad T460 20FMS0HB00    | Notebook    | [67c8620ffa](https://linux-hardware.org/?probe=67c8620ffa) | Jan 22, 2024 |
| Dell          | Inspiron 5570               | Notebook    | [9fd4f31b80](https://linux-hardware.org/?probe=9fd4f31b80) | Jan 22, 2024 |
| Foxconn       | 2AAF                        | Desktop     | [aa481d37c8](https://linux-hardware.org/?probe=aa481d37c8) | Jan 22, 2024 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ed85e4518e](https://linux-hardware.org/?probe=ed85e4518e) | Jan 22, 2024 |
| Gigabyte      | B360M DS3H                  | Desktop     | [d809dd5290](https://linux-hardware.org/?probe=d809dd5290) | Jan 22, 2024 |
| HP            | Elite x2 1012 G1            | Notebook    | [0528733539](https://linux-hardware.org/?probe=0528733539) | Jan 22, 2024 |
| HP            | 81B4                        | Desktop     | [7de00ed55d](https://linux-hardware.org/?probe=7de00ed55d) | Jan 22, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [79cf6e6101](https://linux-hardware.org/?probe=79cf6e6101) | Jan 22, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [e9bc4f9199](https://linux-hardware.org/?probe=e9bc4f9199) | Jan 22, 2024 |
| Acer          | Swift SFX14-51G             | Notebook    | [ac8dbddf38](https://linux-hardware.org/?probe=ac8dbddf38) | Jan 22, 2024 |
| Fujitsu       | LIFEBOOK U7412              | Notebook    | [e5a97a5300](https://linux-hardware.org/?probe=e5a97a5300) | Jan 22, 2024 |
| Acer          | Aspire E1-570               | Notebook    | [bbe5568412](https://linux-hardware.org/?probe=bbe5568412) | Jan 22, 2024 |
| Dell          | Latitude 5440               | Notebook    | [4ac53b51b3](https://linux-hardware.org/?probe=4ac53b51b3) | Jan 22, 2024 |
| ASRock        | A520M-HDV                   | Desktop     | [34e4549f27](https://linux-hardware.org/?probe=34e4549f27) | Jan 22, 2024 |
| ASUSTek       | X751SA                      | Notebook    | [2da0669a42](https://linux-hardware.org/?probe=2da0669a42) | Jan 22, 2024 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | Desktop     | [bb111f75bd](https://linux-hardware.org/?probe=bb111f75bd) | Jan 22, 2024 |
| HP            | Compaq CQ58                 | Notebook    | [e15554b4ae](https://linux-hardware.org/?probe=e15554b4ae) | Jan 22, 2024 |
| Dell          | Latitude 7280               | Notebook    | [21e6e4a581](https://linux-hardware.org/?probe=21e6e4a581) | Jan 22, 2024 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [59122c1f76](https://linux-hardware.org/?probe=59122c1f76) | Jan 22, 2024 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [5a444c3b35](https://linux-hardware.org/?probe=5a444c3b35) | Jan 22, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [c1e338d0ad](https://linux-hardware.org/?probe=c1e338d0ad) | Jan 22, 2024 |
| Gigabyte      | H310M H x.x                 | Desktop     | [7164188034](https://linux-hardware.org/?probe=7164188034) | Jan 22, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [3566eaf43c](https://linux-hardware.org/?probe=3566eaf43c) | Jan 22, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [99f10901cf](https://linux-hardware.org/?probe=99f10901cf) | Jan 22, 2024 |
| Supermicro    | X11SSD-F                    | Desktop     | [a1b05dae9c](https://linux-hardware.org/?probe=a1b05dae9c) | Jan 22, 2024 |
| Lenovo        | ThinkPad X13 Gen 2i 20WL... | Notebook    | [abe1141b70](https://linux-hardware.org/?probe=abe1141b70) | Jan 22, 2024 |
| Samsung       | 940XGK                      | Notebook    | [786fb90f91](https://linux-hardware.org/?probe=786fb90f91) | Jan 22, 2024 |
| Dell          | Latitude E7470              | Notebook    | [1f052ca954](https://linux-hardware.org/?probe=1f052ca954) | Jan 22, 2024 |
| ASUSTek       | X99-A/USB                   | Desktop     | [c07863641d](https://linux-hardware.org/?probe=c07863641d) | Jan 22, 2024 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [103ecfd1f4](https://linux-hardware.org/?probe=103ecfd1f4) | Jan 22, 2024 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [0b0db0e2ef](https://linux-hardware.org/?probe=0b0db0e2ef) | Jan 22, 2024 |
| Intel         | S1200RP G62251-408          | Server      | [edef37bd3e](https://linux-hardware.org/?probe=edef37bd3e) | Jan 22, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [318e16ffb6](https://linux-hardware.org/?probe=318e16ffb6) | Jan 22, 2024 |
| Lenovo        | ThinkPad T420 4238AC6       | Notebook    | [8c171e6ffa](https://linux-hardware.org/?probe=8c171e6ffa) | Jan 22, 2024 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [5003e3366d](https://linux-hardware.org/?probe=5003e3366d) | Jan 22, 2024 |
| Toshiba       | Satellite P50t-A-11D        | Notebook    | [15428d1f5e](https://linux-hardware.org/?probe=15428d1f5e) | Jan 22, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [50bd62bd8e](https://linux-hardware.org/?probe=50bd62bd8e) | Jan 21, 2024 |
| Dell          | 096JG8 A01                  | Desktop     | [a397efcf1d](https://linux-hardware.org/?probe=a397efcf1d) | Jan 21, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [d10912daa4](https://linux-hardware.org/?probe=d10912daa4) | Jan 21, 2024 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [e83d57317e](https://linux-hardware.org/?probe=e83d57317e) | Jan 21, 2024 |
| AZW           | EQ MINI 10                  | Desktop     | [c6ee420879](https://linux-hardware.org/?probe=c6ee420879) | Jan 21, 2024 |
| Samsung       | R530/R730/R540              | Notebook    | [d781965459](https://linux-hardware.org/?probe=d781965459) | Jan 21, 2024 |
| ASRock        | H570 Steel Legend           | Desktop     | [7c0fb43f23](https://linux-hardware.org/?probe=7c0fb43f23) | Jan 21, 2024 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [f2855cb0d7](https://linux-hardware.org/?probe=f2855cb0d7) | Jan 21, 2024 |
| Intel         | NUC7i5BNB J31144-304        | Mini pc     | [631c308735](https://linux-hardware.org/?probe=631c308735) | Jan 21, 2024 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [161b90d80c](https://linux-hardware.org/?probe=161b90d80c) | Jan 21, 2024 |
| Colorful T... | CVN B550M GAMING FROZEN ... | Desktop     | [1d6e70910a](https://linux-hardware.org/?probe=1d6e70910a) | Jan 21, 2024 |
| Gigabyte      | H81M-D2W                    | Desktop     | [03ec02fab4](https://linux-hardware.org/?probe=03ec02fab4) | Jan 21, 2024 |
| MSI           | Z170A GAMING M5             | Desktop     | [742588d66a](https://linux-hardware.org/?probe=742588d66a) | Jan 21, 2024 |
| Dell          | 0YF8P5 A00                  | Desktop     | [dce46de08f](https://linux-hardware.org/?probe=dce46de08f) | Jan 21, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [97588f48fc](https://linux-hardware.org/?probe=97588f48fc) | Jan 21, 2024 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [3224331d5e](https://linux-hardware.org/?probe=3224331d5e) | Jan 21, 2024 |
| ASRock        | FM2A88X Pro+                | Desktop     | [cf5b1adab5](https://linux-hardware.org/?probe=cf5b1adab5) | Jan 21, 2024 |
| Microsoft     | Surface Book 2              | Tablet      | [de117640ca](https://linux-hardware.org/?probe=de117640ca) | Jan 21, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [0996781568](https://linux-hardware.org/?probe=0996781568) | Jan 21, 2024 |
| Notebook      | W65_W67RZ1                  | Notebook    | [3ad0a034e4](https://linux-hardware.org/?probe=3ad0a034e4) | Jan 21, 2024 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [a06ba088e5](https://linux-hardware.org/?probe=a06ba088e5) | Jan 21, 2024 |
| AZW           | GTR V21                     | Desktop     | [dbc8e08754](https://linux-hardware.org/?probe=dbc8e08754) | Jan 21, 2024 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [bec3659c29](https://linux-hardware.org/?probe=bec3659c29) | Jan 21, 2024 |
| HP            | Pavilion dv6                | Notebook    | [8e6edcce2d](https://linux-hardware.org/?probe=8e6edcce2d) | Jan 21, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [edfd27fb22](https://linux-hardware.org/?probe=edfd27fb22) | Jan 21, 2024 |
| Dell          | Latitude E6420              | Notebook    | [dff8e97b14](https://linux-hardware.org/?probe=dff8e97b14) | Jan 21, 2024 |
| Foxconn       | 2A8C                        | Desktop     | [591fafe62b](https://linux-hardware.org/?probe=591fafe62b) | Jan 21, 2024 |
| AZW           | SER V01                     | Mini pc     | [6db6aa63c2](https://linux-hardware.org/?probe=6db6aa63c2) | Jan 21, 2024 |
| Dell          | 051FJ8 A00                  | Desktop     | [186f951a85](https://linux-hardware.org/?probe=186f951a85) | Jan 21, 2024 |
| Lenovo        | ThinkCentre A62 9486E4S     | Desktop     | [426fe50b95](https://linux-hardware.org/?probe=426fe50b95) | Jan 21, 2024 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [55b2a770eb](https://linux-hardware.org/?probe=55b2a770eb) | Jan 21, 2024 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [9c9338dcfd](https://linux-hardware.org/?probe=9c9338dcfd) | Jan 21, 2024 |
| HP            | EliteBook 8570w             | Notebook    | [bdec3958cd](https://linux-hardware.org/?probe=bdec3958cd) | Jan 21, 2024 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [09c4a32231](https://linux-hardware.org/?probe=09c4a32231) | Jan 21, 2024 |
| Acer          | Aspire A715-51G             | Notebook    | [1053d8db44](https://linux-hardware.org/?probe=1053d8db44) | Jan 21, 2024 |
| Medion        | P15648                      | Notebook    | [1c94d72e42](https://linux-hardware.org/?probe=1c94d72e42) | Jan 21, 2024 |
| AZW           | SER V2.0                    | Mini pc     | [d1c108dc2f](https://linux-hardware.org/?probe=d1c108dc2f) | Jan 21, 2024 |
| Panasonic     | FZG1-4                      | Notebook    | [78a30df588](https://linux-hardware.org/?probe=78a30df588) | Jan 21, 2024 |
| Medion        | P15648                      | Notebook    | [17cd0e622d](https://linux-hardware.org/?probe=17cd0e622d) | Jan 21, 2024 |
| HP            | Laptop 17-by0xxx            | Notebook    | [2e29855bb5](https://linux-hardware.org/?probe=2e29855bb5) | Jan 21, 2024 |
| Lenovo        | ThinkCentre A62 9486E4S     | Desktop     | [9712c9e135](https://linux-hardware.org/?probe=9712c9e135) | Jan 21, 2024 |
| MSI           | Z370-A PRO                  | Desktop     | [0a97ecaa3f](https://linux-hardware.org/?probe=0a97ecaa3f) | Jan 21, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [5728acca29](https://linux-hardware.org/?probe=5728acca29) | Jan 20, 2024 |
| ASUSTek       | X556UAK                     | Notebook    | [1399cc64e8](https://linux-hardware.org/?probe=1399cc64e8) | Jan 20, 2024 |
| Sony          | SVF1421E2EW                 | Notebook    | [b28682a58b](https://linux-hardware.org/?probe=b28682a58b) | Jan 20, 2024 |
| Dell          | 0PWNMR A00                  | All in one  | [8a97ac1dff](https://linux-hardware.org/?probe=8a97ac1dff) | Jan 20, 2024 |
| HONOR         | BMH-WDX9                    | Notebook    | [cc5193ad6b](https://linux-hardware.org/?probe=cc5193ad6b) | Jan 20, 2024 |
| Dell          | 06X1TJ A00                  | Desktop     | [bcd509c9d9](https://linux-hardware.org/?probe=bcd509c9d9) | Jan 20, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [5a96118b34](https://linux-hardware.org/?probe=5a96118b34) | Jan 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [6723cbd4cd](https://linux-hardware.org/?probe=6723cbd4cd) | Jan 20, 2024 |
| Dell          | Latitude 5490               | Notebook    | [06fca2f5b2](https://linux-hardware.org/?probe=06fca2f5b2) | Jan 20, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U3C... | Notebook    | [354671b848](https://linux-hardware.org/?probe=354671b848) | Jan 20, 2024 |
| Foxconn       | H61MXE                      | Desktop     | [0a7a342b95](https://linux-hardware.org/?probe=0a7a342b95) | Jan 20, 2024 |
| Lenovo        | IdeaPad Slim 5 14IRL8 82... | Notebook    | [cf906b4574](https://linux-hardware.org/?probe=cf906b4574) | Jan 20, 2024 |
| Lenovo        | IdeaPad Slim 5 14IRL8 82... | Notebook    | [49a8bb87e1](https://linux-hardware.org/?probe=49a8bb87e1) | Jan 20, 2024 |
| Lenovo        | ThinkPad W550s 20E2CTO1W... | Notebook    | [b3466550df](https://linux-hardware.org/?probe=b3466550df) | Jan 20, 2024 |
| Toshiba       | Satellite L670D             | Notebook    | [4b7547d3d1](https://linux-hardware.org/?probe=4b7547d3d1) | Jan 20, 2024 |
| HP            | 213D A01                    | Desktop     | [37b7fb4c4e](https://linux-hardware.org/?probe=37b7fb4c4e) | Jan 20, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U3C... | Notebook    | [3e339aec48](https://linux-hardware.org/?probe=3e339aec48) | Jan 20, 2024 |
| Gigabyte      | P55-USB3                    | Desktop     | [2ae180284e](https://linux-hardware.org/?probe=2ae180284e) | Jan 20, 2024 |
| Unknown       | HX90                        | Desktop     | [ced9f53d73](https://linux-hardware.org/?probe=ced9f53d73) | Jan 20, 2024 |
| Toshiba       | PORTEGE R700                | Notebook    | [9783d3e6f7](https://linux-hardware.org/?probe=9783d3e6f7) | Jan 20, 2024 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [5df2f7a287](https://linux-hardware.org/?probe=5df2f7a287) | Jan 20, 2024 |
| MSI           | Prestige 16Studio A13VF     | Notebook    | [c345bf4b85](https://linux-hardware.org/?probe=c345bf4b85) | Jan 20, 2024 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [d898d5bac9](https://linux-hardware.org/?probe=d898d5bac9) | Jan 20, 2024 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [c66b9a59bb](https://linux-hardware.org/?probe=c66b9a59bb) | Jan 20, 2024 |
| HONOR         | BMH-WDX9                    | Notebook    | [a244cafad7](https://linux-hardware.org/?probe=a244cafad7) | Jan 20, 2024 |
| HP            | ProBook 455 G3              | Notebook    | [d566a44f9d](https://linux-hardware.org/?probe=d566a44f9d) | Jan 20, 2024 |
| HP            | Laptop 17-by0xxx            | Notebook    | [bad5091b84](https://linux-hardware.org/?probe=bad5091b84) | Jan 20, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [d1e6b15e7c](https://linux-hardware.org/?probe=d1e6b15e7c) | Jan 20, 2024 |
| Panasonic     | CF-52PFN32PE                | Notebook    | [8399ba74d7](https://linux-hardware.org/?probe=8399ba74d7) | Jan 20, 2024 |
| Dell          | 0K068D A00                  | Desktop     | [b268579e9b](https://linux-hardware.org/?probe=b268579e9b) | Jan 20, 2024 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [341a928c78](https://linux-hardware.org/?probe=341a928c78) | Jan 20, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a59b13fe15](https://linux-hardware.org/?probe=a59b13fe15) | Jan 20, 2024 |
| Acer          | Nitro AN515-57              | Notebook    | [3aa29620a4](https://linux-hardware.org/?probe=3aa29620a4) | Jan 20, 2024 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [f5eb92f644](https://linux-hardware.org/?probe=f5eb92f644) | Jan 20, 2024 |
| Sony          | SVF1521G6EW                 | Notebook    | [e795184dd6](https://linux-hardware.org/?probe=e795184dd6) | Jan 20, 2024 |
| Gigabyte      | M68MT-S2                    | Desktop     | [ec13e42e3a](https://linux-hardware.org/?probe=ec13e42e3a) | Jan 20, 2024 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [63e6c0358d](https://linux-hardware.org/?probe=63e6c0358d) | Jan 20, 2024 |
| Alienware     | 14                          | Notebook    | [00828e630d](https://linux-hardware.org/?probe=00828e630d) | Jan 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [bcded7aa47](https://linux-hardware.org/?probe=bcded7aa47) | Jan 20, 2024 |
| Dell          | Latitude 7440               | Notebook    | [2871324f95](https://linux-hardware.org/?probe=2871324f95) | Jan 19, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [a13a3a85d9](https://linux-hardware.org/?probe=a13a3a85d9) | Jan 19, 2024 |
| HP            | 8055                        | Desktop     | [454932f0a1](https://linux-hardware.org/?probe=454932f0a1) | Jan 19, 2024 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d80c69c807](https://linux-hardware.org/?probe=d80c69c807) | Jan 19, 2024 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [aa40e37f96](https://linux-hardware.org/?probe=aa40e37f96) | Jan 19, 2024 |
| Dell          | Latitude 7440               | Notebook    | [5ff30573ae](https://linux-hardware.org/?probe=5ff30573ae) | Jan 19, 2024 |
| Dell          | 08K0X7 A00                  | Desktop     | [454c4af5bc](https://linux-hardware.org/?probe=454c4af5bc) | Jan 19, 2024 |
| Dell          | XPS 17 9700                 | Notebook    | [61c6fd00e2](https://linux-hardware.org/?probe=61c6fd00e2) | Jan 19, 2024 |
| Dell          | 073MMW A02                  | Desktop     | [2e19e7434e](https://linux-hardware.org/?probe=2e19e7434e) | Jan 19, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B5402CBA... | Notebook    | [907588dbd2](https://linux-hardware.org/?probe=907588dbd2) | Jan 19, 2024 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [74b90ddfac](https://linux-hardware.org/?probe=74b90ddfac) | Jan 19, 2024 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [6aa12bd4c7](https://linux-hardware.org/?probe=6aa12bd4c7) | Jan 19, 2024 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [59c00448b4](https://linux-hardware.org/?probe=59c00448b4) | Jan 19, 2024 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [8601fae7df](https://linux-hardware.org/?probe=8601fae7df) | Jan 19, 2024 |
| Dell          | 0M9KCM A01                  | Desktop     | [dd9dc75a4d](https://linux-hardware.org/?probe=dd9dc75a4d) | Jan 19, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [ea1922427f](https://linux-hardware.org/?probe=ea1922427f) | Jan 19, 2024 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [fa525f2f78](https://linux-hardware.org/?probe=fa525f2f78) | Jan 19, 2024 |
| Dell          | 0YGWFV A01                  | Desktop     | [b8474b7f54](https://linux-hardware.org/?probe=b8474b7f54) | Jan 19, 2024 |
| Dell          | 0YGWFV A01                  | Desktop     | [8e54683492](https://linux-hardware.org/?probe=8e54683492) | Jan 19, 2024 |
| Dell          | Precision 7560              | Notebook    | [f5a631a694](https://linux-hardware.org/?probe=f5a631a694) | Jan 19, 2024 |
| Dell          | 02YYK5 A00                  | Desktop     | [0ee138a094](https://linux-hardware.org/?probe=0ee138a094) | Jan 19, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [440bc94322](https://linux-hardware.org/?probe=440bc94322) | Jan 19, 2024 |
| Intel         | JSL MRD                     | Desktop     | [96bcf87520](https://linux-hardware.org/?probe=96bcf87520) | Jan 19, 2024 |
| Dell          | Inspiron 7520               | Notebook    | [5768e68147](https://linux-hardware.org/?probe=5768e68147) | Jan 19, 2024 |
| Acer          | TravelMate 5744Z            | Notebook    | [b03213c22c](https://linux-hardware.org/?probe=b03213c22c) | Jan 19, 2024 |
| Dell          | Precision 5680              | Notebook    | [0a88245ac9](https://linux-hardware.org/?probe=0a88245ac9) | Jan 19, 2024 |
| Biostar       | B450MHP                     | Desktop     | [16584e3717](https://linux-hardware.org/?probe=16584e3717) | Jan 19, 2024 |
| Biostar       | B450MHP                     | Desktop     | [24682bdb1f](https://linux-hardware.org/?probe=24682bdb1f) | Jan 19, 2024 |
| Dell          | 060K5C A06                  | Server      | [1a4d18aac4](https://linux-hardware.org/?probe=1a4d18aac4) | Jan 19, 2024 |
| Google        | Dorp                        | Notebook    | [96f8cf97fb](https://linux-hardware.org/?probe=96f8cf97fb) | Jan 19, 2024 |
| Chuwi         | GemiBook Pro                | Notebook    | [216035484c](https://linux-hardware.org/?probe=216035484c) | Jan 19, 2024 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [4c2aa275e2](https://linux-hardware.org/?probe=4c2aa275e2) | Jan 19, 2024 |
| ASRock        | Z390 Extreme4               | Desktop     | [d81097f203](https://linux-hardware.org/?probe=d81097f203) | Jan 19, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [7bd81f3e89](https://linux-hardware.org/?probe=7bd81f3e89) | Jan 19, 2024 |
| Biostar       | A320MH                      | Desktop     | [9213e79212](https://linux-hardware.org/?probe=9213e79212) | Jan 19, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [91f1ca34ad](https://linux-hardware.org/?probe=91f1ca34ad) | Jan 19, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [986bc58cd9](https://linux-hardware.org/?probe=986bc58cd9) | Jan 19, 2024 |
| Dell          | 05CNYF A01                  | Desktop     | [913528cc80](https://linux-hardware.org/?probe=913528cc80) | Jan 19, 2024 |
| Dell          | 0HJH5X A00                  | All in one  | [6ec2b0a4d4](https://linux-hardware.org/?probe=6ec2b0a4d4) | Jan 19, 2024 |
| ASUSTek       | ROG Maximus Z690 HERO EV... | Desktop     | [7d86aa45c2](https://linux-hardware.org/?probe=7d86aa45c2) | Jan 19, 2024 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [a65c4a4db4](https://linux-hardware.org/?probe=a65c4a4db4) | Jan 19, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [3dfc03f457](https://linux-hardware.org/?probe=3dfc03f457) | Jan 19, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [f3ce87bc3c](https://linux-hardware.org/?probe=f3ce87bc3c) | Jan 19, 2024 |
| Acer          | Aspire F5-573               | Notebook    | [9a2df369e8](https://linux-hardware.org/?probe=9a2df369e8) | Jan 19, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [07332f19ce](https://linux-hardware.org/?probe=07332f19ce) | Jan 19, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [4f33e18c23](https://linux-hardware.org/?probe=4f33e18c23) | Jan 19, 2024 |
| Apple         | MacBookPro15,2              | Notebook    | [b36cb3cc5a](https://linux-hardware.org/?probe=b36cb3cc5a) | Jan 19, 2024 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [cf9f573e23](https://linux-hardware.org/?probe=cf9f573e23) | Jan 19, 2024 |
| ASUSTek       | X541NA                      | Notebook    | [21a49936f0](https://linux-hardware.org/?probe=21a49936f0) | Jan 19, 2024 |
| BESSTAR Te... | HM90                        | Desktop     | [69c4bfff2b](https://linux-hardware.org/?probe=69c4bfff2b) | Jan 19, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [e0368be539](https://linux-hardware.org/?probe=e0368be539) | Jan 19, 2024 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [e4a1c904a1](https://linux-hardware.org/?probe=e4a1c904a1) | Jan 18, 2024 |
| Giga Compu... | MC13-LE1-000 01010101       | Server      | [1f2c7821a0](https://linux-hardware.org/?probe=1f2c7821a0) | Jan 18, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [c7ab1232bb](https://linux-hardware.org/?probe=c7ab1232bb) | Jan 18, 2024 |
| HP            | 1998                        | Desktop     | [b54abe0bef](https://linux-hardware.org/?probe=b54abe0bef) | Jan 18, 2024 |
| Unknown       | Orange Pi 5 Plus            | Soc         | [c6ba3badcb](https://linux-hardware.org/?probe=c6ba3badcb) | Jan 18, 2024 |
| Unknown       | Orange Pi 5 Plus            | Soc         | [342f21a2ff](https://linux-hardware.org/?probe=342f21a2ff) | Jan 18, 2024 |
| Toshiba       | Satellite C70D-A            | Notebook    | [f71a7005de](https://linux-hardware.org/?probe=f71a7005de) | Jan 18, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [8cd9ebc60f](https://linux-hardware.org/?probe=8cd9ebc60f) | Jan 18, 2024 |
| Intel         | HM570                       | Desktop     | [3f05344c2c](https://linux-hardware.org/?probe=3f05344c2c) | Jan 18, 2024 |
| Pegatron      | JESSE                       | Desktop     | [0013445f57](https://linux-hardware.org/?probe=0013445f57) | Jan 18, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [8c923deb75](https://linux-hardware.org/?probe=8c923deb75) | Jan 18, 2024 |
| ASUSTek       | G16CH                       | Desktop     | [a482e4cc60](https://linux-hardware.org/?probe=a482e4cc60) | Jan 18, 2024 |
| Pegatron      | JESSE                       | Desktop     | [c8bf0d253c](https://linux-hardware.org/?probe=c8bf0d253c) | Jan 18, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [6a7b43a5f5](https://linux-hardware.org/?probe=6a7b43a5f5) | Jan 18, 2024 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [977382abab](https://linux-hardware.org/?probe=977382abab) | Jan 18, 2024 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [637e6e463e](https://linux-hardware.org/?probe=637e6e463e) | Jan 18, 2024 |
| Acer          | TM6595T                     | Notebook    | [3183dacf91](https://linux-hardware.org/?probe=3183dacf91) | Jan 18, 2024 |
| HP            | Pavilion 17                 | Notebook    | [eaa179919d](https://linux-hardware.org/?probe=eaa179919d) | Jan 18, 2024 |
| Lenovo        | ThinkPad T490 20N3S8W501    | Notebook    | [399ba4e0e5](https://linux-hardware.org/?probe=399ba4e0e5) | Jan 18, 2024 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [bf4f40eec4](https://linux-hardware.org/?probe=bf4f40eec4) | Jan 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [fb993819da](https://linux-hardware.org/?probe=fb993819da) | Jan 18, 2024 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [459fc53c83](https://linux-hardware.org/?probe=459fc53c83) | Jan 18, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [f0b1918981](https://linux-hardware.org/?probe=f0b1918981) | Jan 18, 2024 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [1aa8c64606](https://linux-hardware.org/?probe=1aa8c64606) | Jan 18, 2024 |
| HP            | ProBook 6560b               | Notebook    | [3be633cf59](https://linux-hardware.org/?probe=3be633cf59) | Jan 18, 2024 |
| HP            | ProBook 6560b               | Notebook    | [4b982008b6](https://linux-hardware.org/?probe=4b982008b6) | Jan 18, 2024 |
| Lenovo        | 3106 SDK0J40709 WIN 3259... | Desktop     | [370e1682cf](https://linux-hardware.org/?probe=370e1682cf) | Jan 18, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [70a816897a](https://linux-hardware.org/?probe=70a816897a) | Jan 18, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [624cf621cc](https://linux-hardware.org/?probe=624cf621cc) | Jan 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [50d318d640](https://linux-hardware.org/?probe=50d318d640) | Jan 18, 2024 |
| Dell          | 0G679R A00                  | Desktop     | [993e7a71b2](https://linux-hardware.org/?probe=993e7a71b2) | Jan 18, 2024 |
| Dell          | 0G679R A00                  | Desktop     | [31f196442f](https://linux-hardware.org/?probe=31f196442f) | Jan 18, 2024 |
| Lenovo        | ThinkPad X260 20F5S0NV00    | Notebook    | [cda7600532](https://linux-hardware.org/?probe=cda7600532) | Jan 18, 2024 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [5455618460](https://linux-hardware.org/?probe=5455618460) | Jan 18, 2024 |
| ASUSTek       | P6T SE                      | Desktop     | [6b60732b39](https://linux-hardware.org/?probe=6b60732b39) | Jan 18, 2024 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [0f17e4ee65](https://linux-hardware.org/?probe=0f17e4ee65) | Jan 18, 2024 |
| Dell          | Inspiron MM061              | Notebook    | [6415c1e543](https://linux-hardware.org/?probe=6415c1e543) | Jan 18, 2024 |
| HP            | ProBook 650 G2              | Notebook    | [4374ba78cb](https://linux-hardware.org/?probe=4374ba78cb) | Jan 18, 2024 |
| AZW           | SEi                         | Notebook    | [b144837b91](https://linux-hardware.org/?probe=b144837b91) | Jan 18, 2024 |
| Samsung       | 940XGK                      | Notebook    | [90cea105a0](https://linux-hardware.org/?probe=90cea105a0) | Jan 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4fe05dec99](https://linux-hardware.org/?probe=4fe05dec99) | Jan 18, 2024 |
| Dell          | Latitude 5300               | Notebook    | [eeaf3326d3](https://linux-hardware.org/?probe=eeaf3326d3) | Jan 18, 2024 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [7f0443badf](https://linux-hardware.org/?probe=7f0443badf) | Jan 18, 2024 |
| UMAX          | VisionBook 14Wr Plus        | Notebook    | [7ce24a39ab](https://linux-hardware.org/?probe=7ce24a39ab) | Jan 18, 2024 |
| Apple         | MacBookPro10,2              | Notebook    | [a819ad5cb5](https://linux-hardware.org/?probe=a819ad5cb5) | Jan 18, 2024 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [234d786dd7](https://linux-hardware.org/?probe=234d786dd7) | Jan 18, 2024 |
| Lenovo        | ThinkPad E580 20KS001JGE    | Notebook    | [079ef185ed](https://linux-hardware.org/?probe=079ef185ed) | Jan 18, 2024 |
| Dell          | 0DR845                      | Desktop     | [f591ac32d9](https://linux-hardware.org/?probe=f591ac32d9) | Jan 18, 2024 |
| MSI           | Prestige 13Evo A13M         | Notebook    | [3b3a0ddd43](https://linux-hardware.org/?probe=3b3a0ddd43) | Jan 18, 2024 |
| Dell          | XPS 9320                    | Notebook    | [eb5df7ed6d](https://linux-hardware.org/?probe=eb5df7ed6d) | Jan 18, 2024 |
| Lenovo        | ThinkPad T460 20FMS08L00    | Notebook    | [4533bec49f](https://linux-hardware.org/?probe=4533bec49f) | Jan 18, 2024 |
| Gigabyte      | B460 HD3                    | Desktop     | [4e6f6c248f](https://linux-hardware.org/?probe=4e6f6c248f) | Jan 18, 2024 |
| Lenovo        | ThinkPad T450 20BV000BUS    | Notebook    | [22de6d6102](https://linux-hardware.org/?probe=22de6d6102) | Jan 18, 2024 |
| ASUSTek       | SABERTOOTH 990FX R3.0       | Desktop     | [207dc59ee3](https://linux-hardware.org/?probe=207dc59ee3) | Jan 18, 2024 |
| Acer          | Aspire A315-42G             | Notebook    | [5f7172f388](https://linux-hardware.org/?probe=5f7172f388) | Jan 18, 2024 |
| Microsoft     | Surface Pro 3               | Tablet      | [1a6e250144](https://linux-hardware.org/?probe=1a6e250144) | Jan 18, 2024 |
| HP            | ZBook 14 G2                 | Notebook    | [e2c1850473](https://linux-hardware.org/?probe=e2c1850473) | Jan 18, 2024 |
| Toshiba       | Satellite C55-C             | Notebook    | [4e861cd5e4](https://linux-hardware.org/?probe=4e861cd5e4) | Jan 18, 2024 |
| Acer          | Swift SFX14-41G             | Notebook    | [e3c95c6c18](https://linux-hardware.org/?probe=e3c95c6c18) | Jan 17, 2024 |
| Dell          | Latitude 7212 Rugged Ext... | Notebook    | [d5cf900cbf](https://linux-hardware.org/?probe=d5cf900cbf) | Jan 17, 2024 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [8f87c80e99](https://linux-hardware.org/?probe=8f87c80e99) | Jan 17, 2024 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [040715bf2d](https://linux-hardware.org/?probe=040715bf2d) | Jan 17, 2024 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [577019511f](https://linux-hardware.org/?probe=577019511f) | Jan 17, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 Ua 82F... | Notebook    | [741f29036a](https://linux-hardware.org/?probe=741f29036a) | Jan 17, 2024 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [fa7b8cb83e](https://linux-hardware.org/?probe=fa7b8cb83e) | Jan 17, 2024 |
| Lenovo        | ThinkPad X240 20AMS31700    | Notebook    | [d5d3c69c94](https://linux-hardware.org/?probe=d5d3c69c94) | Jan 17, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [9353e2bbef](https://linux-hardware.org/?probe=9353e2bbef) | Jan 17, 2024 |
| Unknown       | HP ProLiant m400 Server ... | Desktop     | [adf4650d81](https://linux-hardware.org/?probe=adf4650d81) | Jan 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [d310294e7c](https://linux-hardware.org/?probe=d310294e7c) | Jan 17, 2024 |
| ASUSTek       | P6X58D-E                    | Desktop     | [09a124fcf0](https://linux-hardware.org/?probe=09a124fcf0) | Jan 17, 2024 |
| HP            | Pro x2 612 G2               | Tablet      | [718580847b](https://linux-hardware.org/?probe=718580847b) | Jan 17, 2024 |
| SZMZ          | X99 DUAL Z8                 | Desktop     | [623c2e3113](https://linux-hardware.org/?probe=623c2e3113) | Jan 17, 2024 |
| Gigabyte      | A520M H                     | Desktop     | [2f58464c52](https://linux-hardware.org/?probe=2f58464c52) | Jan 17, 2024 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [dfa4d23039](https://linux-hardware.org/?probe=dfa4d23039) | Jan 17, 2024 |
| Acer          | Extensa 215-55              | Notebook    | [395b2c99b5](https://linux-hardware.org/?probe=395b2c99b5) | Jan 17, 2024 |
| MSI           | Z490-A PRO                  | Desktop     | [57eaf7e4ff](https://linux-hardware.org/?probe=57eaf7e4ff) | Jan 17, 2024 |
| HP            | ZBook 15u G5                | Notebook    | [334b143154](https://linux-hardware.org/?probe=334b143154) | Jan 17, 2024 |
| Dell          | XPS 15 7590                 | Notebook    | [226e37fde1](https://linux-hardware.org/?probe=226e37fde1) | Jan 17, 2024 |
| Medion        | Defender P30                | Notebook    | [d8f109106c](https://linux-hardware.org/?probe=d8f109106c) | Jan 17, 2024 |
| Samsung       | R780                        | Notebook    | [b3adbfa6ae](https://linux-hardware.org/?probe=b3adbfa6ae) | Jan 17, 2024 |
| Apple         | Mac-F2218EA9                | All in one  | [bc4379cee4](https://linux-hardware.org/?probe=bc4379cee4) | Jan 17, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [92ba347e99](https://linux-hardware.org/?probe=92ba347e99) | Jan 17, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402NU... | Notebook    | [9c805e9195](https://linux-hardware.org/?probe=9c805e9195) | Jan 17, 2024 |
| AZW           | GT-R                        | Notebook    | [5c0ce30435](https://linux-hardware.org/?probe=5c0ce30435) | Jan 17, 2024 |
| HP            | 822A                        | Desktop     | [9fa299bc2a](https://linux-hardware.org/?probe=9fa299bc2a) | Jan 17, 2024 |
| HP            | 822A                        | Desktop     | [400eeb3bba](https://linux-hardware.org/?probe=400eeb3bba) | Jan 17, 2024 |
| Sony          | VPCEB46FG                   | Notebook    | [0e2c2caced](https://linux-hardware.org/?probe=0e2c2caced) | Jan 17, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [1bb64ecbb9](https://linux-hardware.org/?probe=1bb64ecbb9) | Jan 17, 2024 |
| Dell          | XPS 9315                    | Notebook    | [2271aed5c7](https://linux-hardware.org/?probe=2271aed5c7) | Jan 17, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [42c4cf9cea](https://linux-hardware.org/?probe=42c4cf9cea) | Jan 17, 2024 |
| HP            | EliteBook 850 G4            | Notebook    | [df8bb12b29](https://linux-hardware.org/?probe=df8bb12b29) | Jan 17, 2024 |
| Lenovo        | ThinkPad T490 20N3S8W501    | Notebook    | [87e440b878](https://linux-hardware.org/?probe=87e440b878) | Jan 17, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [11e51bc70c](https://linux-hardware.org/?probe=11e51bc70c) | Jan 17, 2024 |
| Dell          | G3 3500                     | Notebook    | [0fd2b03a7c](https://linux-hardware.org/?probe=0fd2b03a7c) | Jan 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [2ddefbdd81](https://linux-hardware.org/?probe=2ddefbdd81) | Jan 17, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [123bf2b824](https://linux-hardware.org/?probe=123bf2b824) | Jan 17, 2024 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [a15715468f](https://linux-hardware.org/?probe=a15715468f) | Jan 17, 2024 |
| Lenovo        | ThinkBook 14 G6 IRL 21KG    | Notebook    | [b624f93da2](https://linux-hardware.org/?probe=b624f93da2) | Jan 17, 2024 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [77ada6bc6d](https://linux-hardware.org/?probe=77ada6bc6d) | Jan 17, 2024 |
| Lenovo        | ZHAOYANG K4e-IIL 81Y2       | Notebook    | [a318e3a69e](https://linux-hardware.org/?probe=a318e3a69e) | Jan 17, 2024 |
| Gigabyte      | MH61-HD3-ZB 01000100        | Server      | [43f1cf9244](https://linux-hardware.org/?probe=43f1cf9244) | Jan 17, 2024 |
| Gigabyte      | A520M S2H                   | Desktop     | [cf1f6f18f3](https://linux-hardware.org/?probe=cf1f6f18f3) | Jan 17, 2024 |
| Unknown       | Unknown                     | Soc         | [0bac9adb31](https://linux-hardware.org/?probe=0bac9adb31) | Jan 17, 2024 |
| ASUSTek       | K43E                        | Notebook    | [ac83dcf66b](https://linux-hardware.org/?probe=ac83dcf66b) | Jan 17, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [de44aa3d15](https://linux-hardware.org/?probe=de44aa3d15) | Jan 17, 2024 |
| Lenovo        | ThinkPad P53 20QNS01900     | Notebook    | [205e74d1fe](https://linux-hardware.org/?probe=205e74d1fe) | Jan 17, 2024 |
| Dell          | Inspiron 7348               | Notebook    | [a3c452af85](https://linux-hardware.org/?probe=a3c452af85) | Jan 17, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [e6e63ec982](https://linux-hardware.org/?probe=e6e63ec982) | Jan 17, 2024 |
| HP            | Pavilion 15                 | Notebook    | [8e7f087158](https://linux-hardware.org/?probe=8e7f087158) | Jan 17, 2024 |
| MSI           | PRO B650M-P                 | Desktop     | [13bd535c3f](https://linux-hardware.org/?probe=13bd535c3f) | Jan 17, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [3c194e897a](https://linux-hardware.org/?probe=3c194e897a) | Jan 17, 2024 |
| UNOWHY        | Y13G012S4EI                 | Notebook    | [4fdd521da4](https://linux-hardware.org/?probe=4fdd521da4) | Jan 17, 2024 |
| Dell          | 02YRK5 A02                  | Desktop     | [c24b8d81bb](https://linux-hardware.org/?probe=c24b8d81bb) | Jan 16, 2024 |
| HP            | Pavilion 15                 | Notebook    | [0d78ac3518](https://linux-hardware.org/?probe=0d78ac3518) | Jan 16, 2024 |
| HP            | Laptop 15-db1xxx            | Notebook    | [27df75aa45](https://linux-hardware.org/?probe=27df75aa45) | Jan 16, 2024 |
| Unknown       | HP ProLiant m400 Server ... | Desktop     | [a779728852](https://linux-hardware.org/?probe=a779728852) | Jan 16, 2024 |
| Acer          | Aspire A515-46              | Notebook    | [124e8224a6](https://linux-hardware.org/?probe=124e8224a6) | Jan 16, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [130befb564](https://linux-hardware.org/?probe=130befb564) | Jan 16, 2024 |
| HONOR         | BMH-WDX9                    | Notebook    | [e793aff68b](https://linux-hardware.org/?probe=e793aff68b) | Jan 16, 2024 |
| Dell          | Vostro 16 5635              | Notebook    | [41feffb377](https://linux-hardware.org/?probe=41feffb377) | Jan 16, 2024 |
| Dell          | Vostro 16 5635              | Notebook    | [087ee82354](https://linux-hardware.org/?probe=087ee82354) | Jan 16, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [8906f7de53](https://linux-hardware.org/?probe=8906f7de53) | Jan 16, 2024 |
| Dell          | XPS 13 9380                 | Notebook    | [15a7a78b43](https://linux-hardware.org/?probe=15a7a78b43) | Jan 16, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [d2b4053179](https://linux-hardware.org/?probe=d2b4053179) | Jan 16, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [bf8b95391b](https://linux-hardware.org/?probe=bf8b95391b) | Jan 16, 2024 |
| ASUSTek       | G11CD-K                     | Desktop     | [004aa1092f](https://linux-hardware.org/?probe=004aa1092f) | Jan 16, 2024 |
| LG Electro... | A530-U.BE54P1               | Notebook    | [b396bdcd52](https://linux-hardware.org/?probe=b396bdcd52) | Jan 16, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [fe24385194](https://linux-hardware.org/?probe=fe24385194) | Jan 16, 2024 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [29d7b6841b](https://linux-hardware.org/?probe=29d7b6841b) | Jan 16, 2024 |
| ONDA          | H61V Ver:4.01               | Desktop     | [83030b6f99](https://linux-hardware.org/?probe=83030b6f99) | Jan 16, 2024 |
| Acer          | TravelMate P214-53          | Notebook    | [dbe5ed82b8](https://linux-hardware.org/?probe=dbe5ed82b8) | Jan 16, 2024 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [9fa2ea5f9e](https://linux-hardware.org/?probe=9fa2ea5f9e) | Jan 16, 2024 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [1fdaf6d8ba](https://linux-hardware.org/?probe=1fdaf6d8ba) | Jan 16, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [dc21da33ed](https://linux-hardware.org/?probe=dc21da33ed) | Jan 16, 2024 |
| Notebook      | P15SM-A/SM1-A               | Notebook    | [bc817396a6](https://linux-hardware.org/?probe=bc817396a6) | Jan 16, 2024 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [5827410c25](https://linux-hardware.org/?probe=5827410c25) | Jan 16, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [d88b2acd84](https://linux-hardware.org/?probe=d88b2acd84) | Jan 16, 2024 |
| Acer          | Aspire F5-573G              | Notebook    | [6ba3da1f95](https://linux-hardware.org/?probe=6ba3da1f95) | Jan 16, 2024 |
| Supermicro    | X9DRW                       | Server      | [1b1bb1d866](https://linux-hardware.org/?probe=1b1bb1d866) | Jan 16, 2024 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [cb1fa259a7](https://linux-hardware.org/?probe=cb1fa259a7) | Jan 16, 2024 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [f118eb0043](https://linux-hardware.org/?probe=f118eb0043) | Jan 16, 2024 |
| Dell          | Inspiron 3583               | Notebook    | [385ad48703](https://linux-hardware.org/?probe=385ad48703) | Jan 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [1284a92c36](https://linux-hardware.org/?probe=1284a92c36) | Jan 16, 2024 |
| Infinix       | INBook X1 Pro               | Notebook    | [8fd49f9543](https://linux-hardware.org/?probe=8fd49f9543) | Jan 16, 2024 |
| Dell          | Inspiron 5557               | Notebook    | [938a3ee950](https://linux-hardware.org/?probe=938a3ee950) | Jan 16, 2024 |
| Packard Be... | EasyNote TJ65               | Notebook    | [bcf20a0a9c](https://linux-hardware.org/?probe=bcf20a0a9c) | Jan 16, 2024 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [fd42a66717](https://linux-hardware.org/?probe=fd42a66717) | Jan 16, 2024 |
| Lenovo        | ThinkPad Edge 030253G       | Notebook    | [f5b2d04869](https://linux-hardware.org/?probe=f5b2d04869) | Jan 16, 2024 |
| HP            | 255 G7 Notebook PC          | Notebook    | [efd241e5b8](https://linux-hardware.org/?probe=efd241e5b8) | Jan 16, 2024 |
| Intel         | SKYBAY                      | Desktop     | [defbd49284](https://linux-hardware.org/?probe=defbd49284) | Jan 16, 2024 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [de0ec49312](https://linux-hardware.org/?probe=de0ec49312) | Jan 16, 2024 |
| Lenovo        | ThinkPad E560 20EWS0M900    | Notebook    | [d327440fd5](https://linux-hardware.org/?probe=d327440fd5) | Jan 16, 2024 |
| MSI           | Katana GF66 12UE            | Notebook    | [6864ccb2af](https://linux-hardware.org/?probe=6864ccb2af) | Jan 16, 2024 |
| ASUSTek       | H110M-R                     | Desktop     | [3daca725a3](https://linux-hardware.org/?probe=3daca725a3) | Jan 16, 2024 |
| ASUSTek       | H110M-R                     | Desktop     | [cb598cde50](https://linux-hardware.org/?probe=cb598cde50) | Jan 16, 2024 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [42dd6472c7](https://linux-hardware.org/?probe=42dd6472c7) | Jan 16, 2024 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [3a49e03d57](https://linux-hardware.org/?probe=3a49e03d57) | Jan 16, 2024 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [fae72561ad](https://linux-hardware.org/?probe=fae72561ad) | Jan 16, 2024 |
| MSI           | MAG Z790 TOMAHAWK MAX WI... | Desktop     | [803c2f0bd9](https://linux-hardware.org/?probe=803c2f0bd9) | Jan 16, 2024 |
| Microsoft     | Surface Pro 8               | Tablet      | [0a7cafc47f](https://linux-hardware.org/?probe=0a7cafc47f) | Jan 16, 2024 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [60df96228f](https://linux-hardware.org/?probe=60df96228f) | Jan 16, 2024 |
| Acer          | Aspire A515-43              | Notebook    | [f91e4c897b](https://linux-hardware.org/?probe=f91e4c897b) | Jan 16, 2024 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [5e075fc828](https://linux-hardware.org/?probe=5e075fc828) | Jan 16, 2024 |
| Dell          | Inspiron 7570               | Notebook    | [bdea5ae4df](https://linux-hardware.org/?probe=bdea5ae4df) | Jan 16, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [ccbf148cb3](https://linux-hardware.org/?probe=ccbf148cb3) | Jan 16, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [694f38f139](https://linux-hardware.org/?probe=694f38f139) | Jan 16, 2024 |
| ASUSTek       | H97-PLUS                    | Desktop     | [7d8b50985d](https://linux-hardware.org/?probe=7d8b50985d) | Jan 16, 2024 |
| Intel         | WHITLEY E63448-400          | Server      | [dee94dd20e](https://linux-hardware.org/?probe=dee94dd20e) | Jan 16, 2024 |
| HP            | ProBook 445 G7              | Notebook    | [a9499322c3](https://linux-hardware.org/?probe=a9499322c3) | Jan 15, 2024 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [8d2af876bf](https://linux-hardware.org/?probe=8d2af876bf) | Jan 15, 2024 |
| Medion        | E6417 MD99252               | Notebook    | [02157451d7](https://linux-hardware.org/?probe=02157451d7) | Jan 15, 2024 |
| Unknown       | Orange Pi 5 Plus            | Soc         | [5e5bbb11a4](https://linux-hardware.org/?probe=5e5bbb11a4) | Jan 15, 2024 |
| Unknown       | Orange Pi 5 Plus            | Soc         | [694c6f5c35](https://linux-hardware.org/?probe=694c6f5c35) | Jan 15, 2024 |
| HP            | 8648                        | Desktop     | [b896b4b994](https://linux-hardware.org/?probe=b896b4b994) | Jan 15, 2024 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [4d53425b9f](https://linux-hardware.org/?probe=4d53425b9f) | Jan 15, 2024 |
| Dell          | 04Y8V0 A02                  | Desktop     | [f7b5e8a248](https://linux-hardware.org/?probe=f7b5e8a248) | Jan 15, 2024 |
| ASRock        | B650 PG Lightning           | Desktop     | [ff371f0408](https://linux-hardware.org/?probe=ff371f0408) | Jan 15, 2024 |
| Dell          | Precision 7760              | Notebook    | [43c2c64564](https://linux-hardware.org/?probe=43c2c64564) | Jan 15, 2024 |
| Lenovo        | ThinkPad T460p 20FXS1G70... | Notebook    | [519458acdc](https://linux-hardware.org/?probe=519458acdc) | Jan 15, 2024 |
| Lenovo        | ThinkPad T430 2347AF3       | Notebook    | [c52851e59b](https://linux-hardware.org/?probe=c52851e59b) | Jan 15, 2024 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [2af69fd069](https://linux-hardware.org/?probe=2af69fd069) | Jan 15, 2024 |
| Lenovo        | G770 1037                   | Notebook    | [8cd3704440](https://linux-hardware.org/?probe=8cd3704440) | Jan 15, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [94858d9522](https://linux-hardware.org/?probe=94858d9522) | Jan 15, 2024 |
| MSI           | Katana GF66 12UE            | Notebook    | [cb2a25098e](https://linux-hardware.org/?probe=cb2a25098e) | Jan 15, 2024 |
| Unknown       | Unknown                     | Notebook    | [7cb9c4ae9a](https://linux-hardware.org/?probe=7cb9c4ae9a) | Jan 15, 2024 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [f0466fefa4](https://linux-hardware.org/?probe=f0466fefa4) | Jan 15, 2024 |
| PCWare        | IPMH510E                    | Desktop     | [a52f228033](https://linux-hardware.org/?probe=a52f228033) | Jan 15, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [2c9fe1dad7](https://linux-hardware.org/?probe=2c9fe1dad7) | Jan 15, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [052a070a11](https://linux-hardware.org/?probe=052a070a11) | Jan 15, 2024 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [b1c47d4455](https://linux-hardware.org/?probe=b1c47d4455) | Jan 15, 2024 |
| Lenovo        | ThinkPad X270 20HMS12K00    | Notebook    | [246848e065](https://linux-hardware.org/?probe=246848e065) | Jan 15, 2024 |
| Dell          | Inspiron 3558               | Notebook    | [fc67829f54](https://linux-hardware.org/?probe=fc67829f54) | Jan 15, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [ed413e1907](https://linux-hardware.org/?probe=ed413e1907) | Jan 15, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [0f9eb7d53e](https://linux-hardware.org/?probe=0f9eb7d53e) | Jan 15, 2024 |
| Dell          | 0X8DXD A01                  | Desktop     | [d374bcb1f1](https://linux-hardware.org/?probe=d374bcb1f1) | Jan 15, 2024 |
| Acer          | Aspire V5-552G              | Notebook    | [88a4824eac](https://linux-hardware.org/?probe=88a4824eac) | Jan 15, 2024 |
| Gigabyte      | Z790 UD AC                  | Desktop     | [b823078db1](https://linux-hardware.org/?probe=b823078db1) | Jan 15, 2024 |
| Acer          | Aspire V5-552G              | Notebook    | [9b2eb6e626](https://linux-hardware.org/?probe=9b2eb6e626) | Jan 15, 2024 |
| HP            | 81B4 01                     | Desktop     | [2a8624aed6](https://linux-hardware.org/?probe=2a8624aed6) | Jan 15, 2024 |
| TUXEDO        | Pulse 14 Gen3               | Notebook    | [f5bcb23ecb](https://linux-hardware.org/?probe=f5bcb23ecb) | Jan 15, 2024 |
| Jumper        | EZpad .A002                 | Notebook    | [165b30453c](https://linux-hardware.org/?probe=165b30453c) | Jan 15, 2024 |
| HP            | EliteBook 820 G2            | Notebook    | [913733655d](https://linux-hardware.org/?probe=913733655d) | Jan 15, 2024 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [4532c646e7](https://linux-hardware.org/?probe=4532c646e7) | Jan 15, 2024 |
| HP            | ProLiant DL380 Gen9         | Server      | [8f3bf0ff17](https://linux-hardware.org/?probe=8f3bf0ff17) | Jan 15, 2024 |
| Gigabyte      | P55-USB3                    | Desktop     | [34cc055d6b](https://linux-hardware.org/?probe=34cc055d6b) | Jan 15, 2024 |
| Unknown       | Unknown                     | Desktop     | [1c86716af5](https://linux-hardware.org/?probe=1c86716af5) | Jan 15, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [109e11ec26](https://linux-hardware.org/?probe=109e11ec26) | Jan 15, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e7ff1f64dc](https://linux-hardware.org/?probe=e7ff1f64dc) | Jan 15, 2024 |
| Lenovo        | IdeaPadFlex 3 11ADA05 82... | Convertible | [c0e5f745c6](https://linux-hardware.org/?probe=c0e5f745c6) | Jan 15, 2024 |
| Unknown       | Unknown                     | Desktop     | [5e8d8eb89f](https://linux-hardware.org/?probe=5e8d8eb89f) | Jan 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [ff290c247d](https://linux-hardware.org/?probe=ff290c247d) | Jan 15, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [402af8548c](https://linux-hardware.org/?probe=402af8548c) | Jan 15, 2024 |
| Supermicro    | H12DST-BA                   | Desktop     | [d64a1ee900](https://linux-hardware.org/?probe=d64a1ee900) | Jan 15, 2024 |
| Supermicro    | H12DST-BA                   | Desktop     | [3f83ec793d](https://linux-hardware.org/?probe=3f83ec793d) | Jan 15, 2024 |
| Supermicro    | H12DST-BA                   | Desktop     | [623de08cce](https://linux-hardware.org/?probe=623de08cce) | Jan 15, 2024 |
| Supermicro    | H12DST-BA                   | Desktop     | [e925fa2676](https://linux-hardware.org/?probe=e925fa2676) | Jan 15, 2024 |
| Dell          | 00NH4P A05                  | Server      | [bac383d8ec](https://linux-hardware.org/?probe=bac383d8ec) | Jan 15, 2024 |
| Supermicro    | X9DRT                       | Desktop     | [7ed16ba0a0](https://linux-hardware.org/?probe=7ed16ba0a0) | Jan 15, 2024 |
| Dell          | 0XJ5V0 A01                  | Desktop     | [09e55a9304](https://linux-hardware.org/?probe=09e55a9304) | Jan 15, 2024 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [465e84985e](https://linux-hardware.org/?probe=465e84985e) | Jan 15, 2024 |
| HP            | 18E5                        | Desktop     | [4fb3a76631](https://linux-hardware.org/?probe=4fb3a76631) | Jan 15, 2024 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [a77f0d6a70](https://linux-hardware.org/?probe=a77f0d6a70) | Jan 15, 2024 |
| HP            | ProBook 645 G4              | Notebook    | [b461dec271](https://linux-hardware.org/?probe=b461dec271) | Jan 15, 2024 |
| Acer          | Aspire A115-32              | Notebook    | [d00c5b13f0](https://linux-hardware.org/?probe=d00c5b13f0) | Jan 15, 2024 |
| Medion        | MS-7800                     | Desktop     | [f0e70a4db4](https://linux-hardware.org/?probe=f0e70a4db4) | Jan 15, 2024 |
| AZW           | SEi                         | Notebook    | [b8f32bfbbc](https://linux-hardware.org/?probe=b8f32bfbbc) | Jan 14, 2024 |
| ASUSTek       | ROG Strix G513QC_PX513QC    | Notebook    | [bfecaac2ee](https://linux-hardware.org/?probe=bfecaac2ee) | Jan 14, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [f2164243cd](https://linux-hardware.org/?probe=f2164243cd) | Jan 14, 2024 |
| Dell          | 0HJH5X A00                  | All in one  | [2b6d8227b0](https://linux-hardware.org/?probe=2b6d8227b0) | Jan 14, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [8e97a40404](https://linux-hardware.org/?probe=8e97a40404) | Jan 14, 2024 |
| Lenovo        | ThinkCentre M81 5048E2G     | Desktop     | [d4de0eb368](https://linux-hardware.org/?probe=d4de0eb368) | Jan 14, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [41c79968ee](https://linux-hardware.org/?probe=41c79968ee) | Jan 14, 2024 |
| Lenovo        | ThinkCentre M81 5048E2G     | Desktop     | [b4aecb91bf](https://linux-hardware.org/?probe=b4aecb91bf) | Jan 14, 2024 |
| Dell          | Inspiron 1501               | Notebook    | [b96b5df9e5](https://linux-hardware.org/?probe=b96b5df9e5) | Jan 14, 2024 |
| Gigabyte      | F2A85X-D3H                  | Desktop     | [908d3d7353](https://linux-hardware.org/?probe=908d3d7353) | Jan 14, 2024 |
| Dell          | OptiPlex 7050               | Desktop     | [c0f181142d](https://linux-hardware.org/?probe=c0f181142d) | Jan 14, 2024 |
| MSI           | B150M BAZOOKA               | Desktop     | [44444075fd](https://linux-hardware.org/?probe=44444075fd) | Jan 14, 2024 |
| Acer          | Nitro AN515-52              | Notebook    | [d6885f2fa0](https://linux-hardware.org/?probe=d6885f2fa0) | Jan 14, 2024 |
| HP            | G60                         | Notebook    | [f9fc81d45a](https://linux-hardware.org/?probe=f9fc81d45a) | Jan 14, 2024 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [cd7b830381](https://linux-hardware.org/?probe=cd7b830381) | Jan 14, 2024 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [ef9d738ae9](https://linux-hardware.org/?probe=ef9d738ae9) | Jan 14, 2024 |
| HP            | EliteBook x360 1040 G6      | Convertible | [52e03411d9](https://linux-hardware.org/?probe=52e03411d9) | Jan 14, 2024 |
| Dell          | Inspiron 1501               | Notebook    | [7498db6367](https://linux-hardware.org/?probe=7498db6367) | Jan 14, 2024 |
| Unknown       | A70M                        | Notebook    | [b6a6c2e947](https://linux-hardware.org/?probe=b6a6c2e947) | Jan 14, 2024 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [84ecce6ca6](https://linux-hardware.org/?probe=84ecce6ca6) | Jan 14, 2024 |
| Dell          | 0XCR8D A01                  | Desktop     | [761cd45b4a](https://linux-hardware.org/?probe=761cd45b4a) | Jan 14, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [7a41b077e3](https://linux-hardware.org/?probe=7a41b077e3) | Jan 14, 2024 |
| Notebook      | NH50_70_55_58_ED,EDQ        | Notebook    | [12af552024](https://linux-hardware.org/?probe=12af552024) | Jan 14, 2024 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [7f4b2938a3](https://linux-hardware.org/?probe=7f4b2938a3) | Jan 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3382d92b24](https://linux-hardware.org/?probe=3382d92b24) | Jan 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1d59e1c691](https://linux-hardware.org/?probe=1d59e1c691) | Jan 14, 2024 |
| MSI           | 2AE0                        | Desktop     | [0ad06fb4f8](https://linux-hardware.org/?probe=0ad06fb4f8) | Jan 14, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [1291da44c0](https://linux-hardware.org/?probe=1291da44c0) | Jan 14, 2024 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [857a0ea926](https://linux-hardware.org/?probe=857a0ea926) | Jan 14, 2024 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [a8b182fa35](https://linux-hardware.org/?probe=a8b182fa35) | Jan 14, 2024 |
| Toshiba       | Satellite C55-A-1H9         | Notebook    | [7fa6a6c318](https://linux-hardware.org/?probe=7fa6a6c318) | Jan 14, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [1a33b5b4c6](https://linux-hardware.org/?probe=1a33b5b4c6) | Jan 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [b54faba218](https://linux-hardware.org/?probe=b54faba218) | Jan 14, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [6e1b95e72e](https://linux-hardware.org/?probe=6e1b95e72e) | Jan 14, 2024 |
| MSI           | MS-7377                     | Desktop     | [822d42a921](https://linux-hardware.org/?probe=822d42a921) | Jan 14, 2024 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [a4234528de](https://linux-hardware.org/?probe=a4234528de) | Jan 14, 2024 |
| Samsung       | 700Z5A                      | Notebook    | [847f1c355d](https://linux-hardware.org/?probe=847f1c355d) | Jan 14, 2024 |
| Dell          | Latitude E7250              | Notebook    | [bd9ddc2751](https://linux-hardware.org/?probe=bd9ddc2751) | Jan 14, 2024 |
| MSI           | GF63 Thin 11UC              | Notebook    | [e8e49c344d](https://linux-hardware.org/?probe=e8e49c344d) | Jan 14, 2024 |
| Dell          | 0TDG4V A01                  | Desktop     | [41ac0edbe0](https://linux-hardware.org/?probe=41ac0edbe0) | Jan 14, 2024 |
| Lenovo        | ThinkPad L380 20M6S1MG0X    | Notebook    | [74d87d7f6f](https://linux-hardware.org/?probe=74d87d7f6f) | Jan 14, 2024 |
| HP            | 8906 SMVB                   | Desktop     | [795a059437](https://linux-hardware.org/?probe=795a059437) | Jan 14, 2024 |
| Dell          | XPS 13 9370                 | Notebook    | [ce5a25d2a6](https://linux-hardware.org/?probe=ce5a25d2a6) | Jan 14, 2024 |
| HP            | ProBook 6470b               | Notebook    | [72f830ec88](https://linux-hardware.org/?probe=72f830ec88) | Jan 14, 2024 |
| Lenovo        | ThinkPad T470p 20J6001FU... | Notebook    | [e63baf47a1](https://linux-hardware.org/?probe=e63baf47a1) | Jan 14, 2024 |
| Dell          | 0K068D A00                  | Desktop     | [ef25812c9b](https://linux-hardware.org/?probe=ef25812c9b) | Jan 14, 2024 |
| HP            | 15                          | Notebook    | [7ff82fb4d5](https://linux-hardware.org/?probe=7ff82fb4d5) | Jan 14, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [546e67bcf4](https://linux-hardware.org/?probe=546e67bcf4) | Jan 14, 2024 |
| Medion        | AXIR                        | All in one  | [b1f6b771c8](https://linux-hardware.org/?probe=b1f6b771c8) | Jan 14, 2024 |
| Dell          | 0GWHMW A00                  | Desktop     | [42cd6629f0](https://linux-hardware.org/?probe=42cd6629f0) | Jan 14, 2024 |
| Medion        | AXIR                        | All in one  | [49624b7b7c](https://linux-hardware.org/?probe=49624b7b7c) | Jan 14, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [c5d8eebdd5](https://linux-hardware.org/?probe=c5d8eebdd5) | Jan 14, 2024 |
| Pegatron      | Benicia                     | Desktop     | [12d21b9395](https://linux-hardware.org/?probe=12d21b9395) | Jan 14, 2024 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [74cdfb120c](https://linux-hardware.org/?probe=74cdfb120c) | Jan 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [82f1c7e4f3](https://linux-hardware.org/?probe=82f1c7e4f3) | Jan 14, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [043258f53d](https://linux-hardware.org/?probe=043258f53d) | Jan 14, 2024 |
| Dell          | Vostro 5471                 | Notebook    | [d3ef161a9e](https://linux-hardware.org/?probe=d3ef161a9e) | Jan 14, 2024 |
| HP            | G60                         | Notebook    | [85a5846338](https://linux-hardware.org/?probe=85a5846338) | Jan 14, 2024 |
| Biostar       | B350GT3                     | Desktop     | [d210ea56f8](https://linux-hardware.org/?probe=d210ea56f8) | Jan 14, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [0ab04d0727](https://linux-hardware.org/?probe=0ab04d0727) | Jan 14, 2024 |
| AXDIA Inte... | MYBOOK 14 PRO               | Notebook    | [9fcc01c1e0](https://linux-hardware.org/?probe=9fcc01c1e0) | Jan 14, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [e743e145d7](https://linux-hardware.org/?probe=e743e145d7) | Jan 13, 2024 |
| Sony          | SVF1521H2EW                 | Notebook    | [ef7a3ce205](https://linux-hardware.org/?probe=ef7a3ce205) | Jan 13, 2024 |
| Lenovo        | ThinkPad L380 20M6S1MG0X    | Notebook    | [9551a51d17](https://linux-hardware.org/?probe=9551a51d17) | Jan 13, 2024 |
| MSI           | H110M PRO-VD                | Desktop     | [c8b3437429](https://linux-hardware.org/?probe=c8b3437429) | Jan 13, 2024 |
| Supermicro    | X11SSH-F                    | Server      | [4ec98ce9b3](https://linux-hardware.org/?probe=4ec98ce9b3) | Jan 13, 2024 |
| HP            | 3048h                       | Desktop     | [352c2d797c](https://linux-hardware.org/?probe=352c2d797c) | Jan 13, 2024 |
| Gigabyte      | GA-MA78GM-US2H              | Desktop     | [2dbb9562af](https://linux-hardware.org/?probe=2dbb9562af) | Jan 13, 2024 |
| Framework     | Laptop                      | Notebook    | [ab77469364](https://linux-hardware.org/?probe=ab77469364) | Jan 13, 2024 |
| ASRock        | B660 Pro RS                 | Desktop     | [e7dc825ebd](https://linux-hardware.org/?probe=e7dc825ebd) | Jan 13, 2024 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [5551053ab1](https://linux-hardware.org/?probe=5551053ab1) | Jan 13, 2024 |
| HP            | 3048h                       | Desktop     | [f4972d54fd](https://linux-hardware.org/?probe=f4972d54fd) | Jan 13, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [ae7d5daa8e](https://linux-hardware.org/?probe=ae7d5daa8e) | Jan 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [53a45b597e](https://linux-hardware.org/?probe=53a45b597e) | Jan 13, 2024 |
| ASRock        | 970 Extreme4                | Desktop     | [7c02fff797](https://linux-hardware.org/?probe=7c02fff797) | Jan 13, 2024 |
| ASRock        | 970 Extreme4                | Desktop     | [9956a82d50](https://linux-hardware.org/?probe=9956a82d50) | Jan 13, 2024 |
| Lenovo        | ThinkPad E580 20KS007PMB    | Notebook    | [7284cabc43](https://linux-hardware.org/?probe=7284cabc43) | Jan 13, 2024 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [e2a832747d](https://linux-hardware.org/?probe=e2a832747d) | Jan 13, 2024 |
| ASUSTek       | A88XM-E/USB                 | Desktop     | [3ae14ee6a8](https://linux-hardware.org/?probe=3ae14ee6a8) | Jan 13, 2024 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [bf37fabc09](https://linux-hardware.org/?probe=bf37fabc09) | Jan 13, 2024 |
| BESSTAR Te... | UM700                       | Desktop     | [07e4f86238](https://linux-hardware.org/?probe=07e4f86238) | Jan 13, 2024 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [89eb20dae9](https://linux-hardware.org/?probe=89eb20dae9) | Jan 13, 2024 |
| Microsoft     | Surface Go 3                | Tablet      | [4940f95cf9](https://linux-hardware.org/?probe=4940f95cf9) | Jan 13, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [d00f2b6f83](https://linux-hardware.org/?probe=d00f2b6f83) | Jan 13, 2024 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [177eb57417](https://linux-hardware.org/?probe=177eb57417) | Jan 13, 2024 |
| ASUSTek       | A58M-K                      | Desktop     | [574d526af4](https://linux-hardware.org/?probe=574d526af4) | Jan 13, 2024 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [d15fd25a80](https://linux-hardware.org/?probe=d15fd25a80) | Jan 13, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [ab07a9741b](https://linux-hardware.org/?probe=ab07a9741b) | Jan 13, 2024 |
| Intel         | X79-SERVER V1.1             | Desktop     | [ec275f8de3](https://linux-hardware.org/?probe=ec275f8de3) | Jan 13, 2024 |
| Intel         | DH55TC AAG26116-302         | Desktop     | [593bf4f394](https://linux-hardware.org/?probe=593bf4f394) | Jan 13, 2024 |
| Dell          | Vostro 3500                 | Notebook    | [a6d51704d8](https://linux-hardware.org/?probe=a6d51704d8) | Jan 13, 2024 |
| Intel         | DH55TC AAG26116-302         | Desktop     | [8d503de9a9](https://linux-hardware.org/?probe=8d503de9a9) | Jan 13, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Ubuntu 20.04    | 25719     | 37.03%  |
| Ubuntu 22.04    | 14395     | 20.73%  |
| Ubuntu 18.04    | 13185     | 18.98%  |
| Ubuntu 20.10    | 2231      | 3.21%   |
| Ubuntu 21.10    | 2095      | 3.02%   |
| Ubuntu 19.10    | 2057      | 2.96%   |
| Ubuntu 19.04    | 1903      | 2.74%   |
| Ubuntu 21.04    | 1779      | 2.56%   |
| Ubuntu 22.10    | 1643      | 2.37%   |
| Ubuntu 23.04    | 1636      | 2.36%   |
| Ubuntu 23.10    | 907       | 1.31%   |
| Ubuntu 18.10    | 856       | 1.23%   |
| Ubuntu 16.04    | 758       | 1.09%   |
| Ubuntu          | 73        | 0.11%   |
| Ubuntu 17.10    | 56        | 0.08%   |
| Ubuntu Core 16  | 41        | 0.06%   |
| Ubuntu Core 18  | 34        | 0.05%   |
| Ubuntu 24.04    | 21        | 0.03%   |
| Ubuntu 14.04    | 19        | 0.03%   |
| Ubuntu Core 22  | 15        | 0.02%   |
| Ubuntu 17.04    | 6         | 0.01%   |
| Ubuntu 18.08    | 5         | 0.01%   |
| Ubuntu Core 20  | 3         | 0.004%  |
| Ubuntu 16.10    | 3         | 0.004%  |
| Ubuntu 12.04    | 3         | 0.004%  |
| Ubuntu 9.5      | 1         | 0.001%  |
| Ubuntu 6.1      | 1         | 0.001%  |
| Ubuntu 6.0      | 1         | 0.001%  |
| Ubuntu 6        | 1         | 0.001%  |
| Ubuntu 21.12    | 1         | 0.001%  |
| Ubuntu 2023.3   | 1         | 0.001%  |
| Ubuntu 20.08.3  | 1         | 0.001%  |
| Ubuntu 20.04.3  | 1         | 0.001%  |
| Ubuntu 19.1     | 1         | 0.001%  |
| Ubuntu 18.08.39 | 1         | 0.001%  |
| Ubuntu 18.08.38 | 1         | 0.001%  |
| Ubuntu 18.08.36 | 1         | 0.001%  |
| Ubuntu 18.08.34 | 1         | 0.001%  |
| Ubuntu 10.04    | 1         | 0.001%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Ubuntu | 65906     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 2519      | 3.21%   |
| 5.4.0-26-generic  | 1022      | 1.3%    |
| 5.4.0-48-generic  | 1020      | 1.3%    |
| 5.4.0-29-generic  | 992       | 1.27%   |
| 5.4.0-52-generic  | 971       | 1.24%   |
| 5.15.0-56-generic | 909       | 1.16%   |
| 5.4.0-40-generic  | 849       | 1.08%   |
| 5.8.0-43-generic  | 848       | 1.08%   |
| 5.4.0-58-generic  | 832       | 1.06%   |
| 6.2.0-26-generic  | 807       | 1.03%   |
| 5.4.0-37-generic  | 777       | 0.99%   |
| 5.15.0-52-generic | 769       | 0.98%   |
| 5.15.0-58-generic | 718       | 0.92%   |
| 5.19.0-35-generic | 712       | 0.91%   |
| 5.3.0-40-generic  | 686       | 0.88%   |
| 5.11.0-27-generic | 677       | 0.86%   |
| 6.5.0-14-generic  | 671       | 0.86%   |
| 5.4.0-33-generic  | 671       | 0.86%   |
| 5.15.0-43-generic | 644       | 0.82%   |
| 5.8.0-50-generic  | 643       | 0.82%   |
| 5.19.0-38-generic | 624       | 0.8%    |
| 5.8.0-44-generic  | 617       | 0.79%   |
| 5.3.0-46-generic  | 614       | 0.78%   |
| 5.15.0-46-generic | 608       | 0.78%   |
| 5.15.0-48-generic | 606       | 0.77%   |
| 5.4.0-54-generic  | 603       | 0.77%   |
| 5.11.0-37-generic | 592       | 0.76%   |
| 5.19.0-32-generic | 574       | 0.73%   |
| 5.4.0-31-generic  | 573       | 0.73%   |
| 5.4.0-47-generic  | 565       | 0.72%   |
| 6.2.0-20-generic  | 562       | 0.72%   |
| 5.8.0-48-generic  | 558       | 0.71%   |
| 5.11.0-38-generic | 552       | 0.7%    |
| 5.0.0-23-generic  | 538       | 0.69%   |
| 6.2.0-39-generic  | 521       | 0.66%   |
| 5.0.0-37-generic  | 519       | 0.66%   |
| 5.19.0-46-generic | 518       | 0.66%   |
| 4.18.0-15-generic | 511       | 0.65%   |
| 5.11.0-40-generic | 501       | 0.64%   |
| 5.15.0-47-generic | 492       | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 15796     | 22%     |
| 5.15.0  | 9291      | 12.94%  |
| 5.8.0   | 6733      | 9.38%   |
| 4.15.0  | 6057      | 8.43%   |
| 5.11.0  | 5185      | 7.22%   |
| 5.19.0  | 4803      | 6.69%   |
| 6.2.0   | 4649      | 6.47%   |
| 5.3.0   | 4359      | 6.07%   |
| 5.13.0  | 4234      | 5.9%    |
| 5.0.0   | 3866      | 5.38%   |
| 4.18.0  | 2700      | 3.76%   |
| 6.5.0   | 1331      | 1.85%   |
| 4.4.0   | 286       | 0.4%    |
| 5.14.0  | 206       | 0.29%   |
| 5.10.0  | 127       | 0.18%   |
| 5.17.0  | 104       | 0.14%   |
| 4.13.0  | 101       | 0.14%   |
| 5.6.0   | 80        | 0.11%   |
| 6.1.0   | 63        | 0.09%   |
| 6.0.0   | 42        | 0.06%   |
| 5.9.0   | 33        | 0.05%   |
| 4.10.0  | 29        | 0.04%   |
| 5.7.1   | 27        | 0.04%   |
| 6.0.9   | 23        | 0.03%   |
| 5.18.0  | 22        | 0.03%   |
| 4.9.140 | 21        | 0.03%   |
| 6.4.0   | 19        | 0.03%   |
| 5.12.0  | 19        | 0.03%   |
| 6.3.0   | 18        | 0.03%   |
| 5.7.0   | 18        | 0.03%   |
| 5.2.0   | 17        | 0.02%   |
| 5.16.0  | 17        | 0.02%   |
| 4.19.0  | 17        | 0.02%   |
| 6.6.0   | 15        | 0.02%   |
| 6.2.11  | 14        | 0.02%   |
| 5.19.5  | 14        | 0.02%   |
| 5.10.2  | 13        | 0.02%   |
| 4.8.0   | 13        | 0.02%   |
| 5.17.1  | 12        | 0.02%   |
| 5.15.2  | 12        | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 15849     | 22.09%  |
| 5.15    | 9374      | 13.06%  |
| 5.8     | 6798      | 9.47%   |
| 4.15    | 6065      | 8.45%   |
| 5.11    | 5224      | 7.28%   |
| 5.19    | 4842      | 6.75%   |
| 6.2     | 4730      | 6.59%   |
| 5.3     | 4374      | 6.1%    |
| 5.13    | 4274      | 5.96%   |
| 5.0     | 3905      | 5.44%   |
| 4.18    | 2709      | 3.78%   |
| 6.5     | 1370      | 1.91%   |
| 4.4     | 294       | 0.41%   |
| 5.10    | 254       | 0.35%   |
| 5.14    | 241       | 0.34%   |
| 5.17    | 160       | 0.22%   |
| 6.1     | 129       | 0.18%   |
| 5.6     | 117       | 0.16%   |
| 4.13    | 104       | 0.14%   |
| 6.0     | 103       | 0.14%   |
| 5.9     | 82        | 0.11%   |
| 5.7     | 80        | 0.11%   |
| 6.4     | 62        | 0.09%   |
| 6.3     | 61        | 0.09%   |
| 5.18    | 57        | 0.08%   |
| 4.19    | 50        | 0.07%   |
| 4.9     | 47        | 0.07%   |
| 5.16    | 46        | 0.06%   |
| 6.6     | 44        | 0.06%   |
| 5.1     | 44        | 0.06%   |
| 5.12    | 42        | 0.06%   |
| 5.2     | 40        | 0.06%   |
| 5.5     | 38        | 0.05%   |
| 4.10    | 30        | 0.04%   |
| 4.16    | 18        | 0.03%   |
| 4.8     | 15        | 0.02%   |
| 6.7     | 14        | 0.02%   |
| 4.20    | 14        | 0.02%   |
| 4.17    | 11        | 0.02%   |
| 4.14    | 11        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 64143     | 97.31%  |
| i686    | 1046      | 1.59%   |
| aarch64 | 672       | 1.02%   |
| armv7l  | 45        | 0.07%   |
| Unknown | 3         | 0.005%  |
| riscv64 | 2         | 0.003%  |
| s390x   | 1         | 0.002%  |
| i586    | 1         | 0.002%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 51806     | 77.14%  |
| Unknown           | 13824     | 20.58%  |
| X-Cinnamon        | 487       | 0.73%   |
| GNOME Flashback   | 397       | 0.59%   |
| Cinnamon          | 166       | 0.25%   |
| GNUstep           | 157       | 0.23%   |
| i3                | 85        | 0.13%   |
| GNOME Classic     | 59        | 0.09%   |
| enlightenment     | 57        | 0.08%   |
| awesome           | 18        | 0.03%   |
| openbox           | 14        | 0.02%   |
| sway              | 12        | 0.02%   |
| Pantheon          | 8         | 0.01%   |
| xubuntu           | 7         | 0.01%   |
| Lubuntu           | 7         | 0.01%   |
| Deepin            | 7         | 0.01%   |
| Yaru:ubuntu:GNOME | 5         | 0.01%   |
| dwm               | 5         | 0.01%   |
| ubuntu            | 4         | 0.01%   |
| xmonad            | 3         | 0.004%  |
| Trinity           | 3         | 0.004%  |
| ubuntustudio      | 2         | 0.003%  |
| mwm               | 2         | 0.003%  |
| ICEWM             | 2         | 0.003%  |
| fvwm              | 2         | 0.003%  |
| fluxbox           | 2         | 0.003%  |
| DDE               | 2         | 0.003%  |
| Cutefish          | 2         | 0.003%  |
| Core              | 2         | 0.003%  |
| bspwm             | 2         | 0.003%  |
| xsession          | 1         | 0.001%  |
| wmaker-common     | 1         | 0.001%  |
| ubuntu=GNOME      | 1         | 0.001%  |
| ratflow           | 1         | 0.001%  |
| kde               | 1         | 0.001%  |
| INPT              | 1         | 0.001%  |
| i3-with-shmlog    | 1         | 0.001%  |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 44009     | 64.4%   |
| Wayland     | 15136     | 22.15%  |
| Unknown     | 8047      | 11.78%  |
| Tty         | 1137      | 1.66%   |
| Web         | 7         | 0.01%   |
| Unspecified | 1         | 0.001%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 35730     | 52.6%   |
| GDM3    | 22010     | 32.4%   |
| GDM     | 8914      | 13.12%  |
| LightDM | 865       | 1.27%   |
| TDM     | 257       | 0.38%   |
| SDDM    | 113       | 0.17%   |
| SLiM    | 23        | 0.03%   |
| XDM     | 6         | 0.01%   |
| LXDM    | 3         | 0.004%  |
| NODM    | 2         | 0.003%  |
| Ly      | 2         | 0.003%  |
| GREETD  | 1         | 0.001%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 24332     | 36.3%   |
| Unknown | 10261     | 15.31%  |
| de_DE   | 5092      | 7.6%    |
| fr_FR   | 3295      | 4.92%   |
| en_GB   | 2800      | 4.18%   |
| pt_BR   | 2493      | 3.72%   |
| it_IT   | 1842      | 2.75%   |
| en_IN   | 1670      | 2.49%   |
| ru_RU   | 1582      | 2.36%   |
| es_ES   | 1490      | 2.22%   |
| en_CA   | 1354      | 2.02%   |
| C       | 1240      | 1.85%   |
| pl_PL   | 879       | 1.31%   |
| en_AU   | 869       | 1.3%    |
| nl_NL   | 585       | 0.87%   |
| hu_HU   | 395       | 0.59%   |
| cs_CZ   | 385       | 0.57%   |
| es_MX   | 380       | 0.57%   |
| es_AR   | 330       | 0.49%   |
| zh_CN   | 320       | 0.48%   |
| en_ZA   | 318       | 0.47%   |
| ja_JP   | 312       | 0.47%   |
| de_AT   | 271       | 0.4%    |
| pt_PT   | 256       | 0.38%   |
| tr_TR   | 242       | 0.36%   |
| sv_SE   | 234       | 0.35%   |
| de_CH   | 189       | 0.28%   |
| fi_FI   | 183       | 0.27%   |
| es_CO   | 163       | 0.24%   |
| en_NZ   | 151       | 0.23%   |
| fr_CA   | 150       | 0.22%   |
| en_IL   | 150       | 0.22%   |
| es_CL   | 149       | 0.22%   |
| el_GR   | 142       | 0.21%   |
| ru_UA   | 137       | 0.2%    |
| fr_BE   | 129       | 0.19%   |
| ko_KR   | 122       | 0.18%   |
| da_DK   | 122       | 0.18%   |
| ro_RO   | 119       | 0.18%   |
| en_IE   | 106       | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 37071     | 55.09%  |
| EFI  | 30217     | 44.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type          | Computers | Percent |
|---------------|-----------|---------|
| Ext4          | 56337     | 84.01%  |
| Tmpfs         | 4980      | 7.43%   |
| Overlay       | 2039      | 3.04%   |
| Unknown       | 1371      | 2.04%   |
| Zfs           | 907       | 1.35%   |
| Btrfs         | 708       | 1.06%   |
| Ext2          | 293       | 0.44%   |
| Xfs           | 216       | 0.32%   |
| Ext3          | 167       | 0.25%   |
| Aufs          | 20        | 0.03%   |
| Jfs           | 8         | 0.01%   |
| Reiserfs      | 7         | 0.01%   |
| XXX4          | 3         | 0.004%  |
| XXXXXXX       | 1         | 0.001%  |
| XXXX          | 1         | 0.001%  |
| SquXshfs      | 1         | 0.001%  |
| Nfs           | 1         | 0.001%  |
| Lvm           | 1         | 0.001%  |
| Fuse.snapfuse | 1         | 0.001%  |
| F2fs          | 1         | 0.001%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 40695     | 60.44%  |
| GPT     | 22738     | 33.77%  |
| MBR     | 3899      | 5.79%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 58498     | 87.43%  |
| Yes       | 8410      | 12.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 41652     | 62.25%  |
| Yes       | 25263     | 37.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 10169     | 15.43%  |
| Dell                    | 9849      | 14.94%  |
| Hewlett-Packard         | 9580      | 14.54%  |
| Lenovo                  | 8696      | 13.19%  |
| Gigabyte Technology     | 3963      | 6.01%   |
| Acer                    | 3551      | 5.39%   |
| MSI                     | 3411      | 5.18%   |
| ASRock                  | 1993      | 3.02%   |
| Apple                   | 1543      | 2.34%   |
| Intel                   | 1325      | 2.01%   |
| Toshiba                 | 1114      | 1.69%   |
| Samsung Electronics     | 766       | 1.16%   |
| Unknown                 | 637       | 0.97%   |
| Fujitsu                 | 592       | 0.9%    |
| Sony                    | 583       | 0.88%   |
| Raspberry Pi Foundation | 560       | 0.85%   |
| HUAWEI                  | 465       | 0.71%   |
| Supermicro              | 388       | 0.59%   |
| Medion                  | 372       | 0.56%   |
| Pegatron                | 298       | 0.45%   |
| Foxconn                 | 271       | 0.41%   |
| Packard Bell            | 249       | 0.38%   |
| Positivo                | 241       | 0.37%   |
| Microsoft               | 240       | 0.36%   |
| Biostar                 | 222       | 0.34%   |
| Notebook                | 210       | 0.32%   |
| Alienware               | 193       | 0.29%   |
| Google                  | 191       | 0.29%   |
| ECS                     | 189       | 0.29%   |
| Fujitsu Siemens         | 155       | 0.24%   |
| Timi                    | 153       | 0.23%   |
| Gateway                 | 139       | 0.21%   |
| AMI                     | 128       | 0.19%   |
| LG Electronics          | 121       | 0.18%   |
| TUXEDO                  | 92        | 0.14%   |
| AZW                     | 91        | 0.14%   |
| Chuwi                   | 89        | 0.14%   |
| eMachines               | 86        | 0.13%   |
| System76                | 85        | 0.13%   |
| Clevo                   | 78        | 0.12%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 841       | 1.28%   |
| ASUS All Series                    | 642       | 0.97%   |
| RPi Raspberry Pi                   | 295       | 0.45%   |
| HP Notebook                        | 277       | 0.42%   |
| HP Pavilion dv6                    | 173       | 0.26%   |
| Dell OptiPlex 7010                 | 165       | 0.25%   |
| HP Pavilion g6                     | 148       | 0.22%   |
| HP Pavilion dv7                    | 123       | 0.19%   |
| HP Pavilion Notebook               | 117       | 0.18%   |
| ASUS PRIME A320M-K                 | 115       | 0.17%   |
| HP Pavilion 15                     | 106       | 0.16%   |
| Dell OptiPlex 9020                 | 105       | 0.16%   |
| Dell XPS 15 7590                   | 100       | 0.15%   |
| Dell OptiPlex 790                  | 99        | 0.15%   |
| MSI MS-7C37                        | 96        | 0.15%   |
| Dell Latitude E6420                | 96        | 0.15%   |
| Dell Latitude E6410                | 95        | 0.14%   |
| Gigabyte B450M DS3H                | 91        | 0.14%   |
| Dell XPS 15 9570                   | 90        | 0.14%   |
| HP EliteBook 840 G3                | 87        | 0.13%   |
| Dell OptiPlex 780                  | 86        | 0.13%   |
| MSI MS-7C02                        | 85        | 0.13%   |
| HP 15                              | 84        | 0.13%   |
| Dell Inspiron 15-3567              | 84        | 0.13%   |
| Dell Latitude E6430                | 83        | 0.13%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 81        | 0.12%   |
| Apple MacBookPro9,2                | 80        | 0.12%   |
| Supermicro Super Server            | 78        | 0.12%   |
| MSI MS-7721                        | 78        | 0.12%   |
| ASUS TUF Gaming X570-PLUS          | 78        | 0.12%   |
| ASUS M5A78L-M/USB3                 | 77        | 0.12%   |
| Dell XPS 13 9370                   | 76        | 0.12%   |
| Dell Inspiron 5570                 | 76        | 0.12%   |
| Dell OptiPlex 3020                 | 75        | 0.11%   |
| HP Compaq Elite 8300 SFF           | 73        | 0.11%   |
| Dell XPS 13 7390                   | 73        | 0.11%   |
| Dell Latitude E6400                | 73        | 0.11%   |
| HP Laptop 15-bs0xx                 | 72        | 0.11%   |
| Dell XPS 15 9500                   | 71        | 0.11%   |
| HP Laptop 15-db0xxx                | 70        | 0.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 3734      | 5.67%   |
| Dell Inspiron      | 2510      | 3.81%   |
| Acer Aspire        | 2416      | 3.67%   |
| Dell Latitude      | 2343      | 3.56%   |
| HP Pavilion        | 1718      | 2.61%   |
| Lenovo IdeaPad     | 1673      | 2.54%   |
| Dell OptiPlex      | 1396      | 2.12%   |
| HP EliteBook       | 1306      | 1.98%   |
| Dell XPS           | 1136      | 1.72%   |
| ASUS PRIME         | 1059      | 1.61%   |
| Dell Precision     | 995       | 1.51%   |
| HP ProBook         | 990       | 1.5%    |
| Toshiba Satellite  | 933       | 1.42%   |
| HP Compaq          | 904       | 1.37%   |
| HP Laptop          | 902       | 1.37%   |
| ASUS ROG           | 850       | 1.29%   |
| Unknown            | 841       | 1.28%   |
| ASUS VivoBook      | 684       | 1.04%   |
| ASUS All           | 642       | 0.97%   |
| Dell Vostro        | 623       | 0.95%   |
| Lenovo ThinkCentre | 620       | 0.94%   |
| RPi Raspberry      | 559       | 0.85%   |
| ASUS TUF           | 500       | 0.76%   |
| HP ENVY            | 476       | 0.72%   |
| Lenovo Yoga        | 387       | 0.59%   |
| Acer Swift         | 294       | 0.45%   |
| HP Notebook        | 279       | 0.42%   |
| ASUS ZenBook       | 270       | 0.41%   |
| HP ZBook           | 263       | 0.4%    |
| Lenovo Legion      | 256       | 0.39%   |
| Dell PowerEdge     | 252       | 0.38%   |
| Lenovo ThinkBook   | 249       | 0.38%   |
| Microsoft Surface  | 240       | 0.36%   |
| Fujitsu LIFEBOOK   | 240       | 0.36%   |
| HP EliteDesk       | 225       | 0.34%   |
| ASUS M5A78L-M      | 221       | 0.34%   |
| Fujitsu ESPRIMO    | 201       | 0.3%    |
| Acer Nitro         | 197       | 0.3%    |
| HP ProLiant        | 186       | 0.28%   |
| HP ProDesk         | 178       | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 6172      | 9.36%   |
| 2019    | 5681      | 8.62%   |
| 2012    | 5539      | 8.4%    |
| 2011    | 4993      | 7.58%   |
| 2020    | 4965      | 7.53%   |
| 2013    | 4800      | 7.28%   |
| 2017    | 4532      | 6.88%   |
| 2014    | 3963      | 6.01%   |
| 2010    | 3664      | 5.56%   |
| 2021    | 3536      | 5.37%   |
| 2015    | 3481      | 5.28%   |
| 2016    | 3317      | 5.03%   |
| 2009    | 2749      | 4.17%   |
| 2008    | 2745      | 4.17%   |
| 2022    | 1875      | 2.84%   |
| 2007    | 1635      | 2.48%   |
| 2023    | 699       | 1.06%   |
| Unknown | 638       | 0.97%   |
| 2006    | 631       | 0.96%   |
| 2005    | 219       | 0.33%   |
| 2004    | 51        | 0.08%   |
| 2003    | 8         | 0.01%   |
| 2002    | 7         | 0.01%   |
| 2001    | 4         | 0.01%   |
| 2024    | 1         | 0.002%  |
| 2000    | 1         | 0.002%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 35575     | 53.98%  |
| Desktop        | 24564     | 37.27%  |
| Convertible    | 1644      | 2.49%   |
| Mini pc        | 973       | 1.48%   |
| Server         | 936       | 1.42%   |
| All in one     | 914       | 1.39%   |
| System on chip | 708       | 1.07%   |
| Tablet         | 588       | 0.89%   |
| Stick pc       | 2         | 0.003%  |
| Other          | 1         | 0.002%  |
| Firewall       | 1         | 0.002%  |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 59337     | 89.27%  |
| Enabled  | 7133      | 10.73%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 65646     | 99.61%  |
| Yes  | 260       | 0.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 15538     | 23.24%  |
| 3.01-4.0        | 13639     | 20.4%   |
| 16.01-24.0      | 13048     | 19.52%  |
| 8.01-16.0       | 11834     | 17.7%   |
| 32.01-64.0      | 5798      | 8.67%   |
| 1.01-2.0        | 2517      | 3.76%   |
| 64.01-256.0     | 2029      | 3.03%   |
| 24.01-32.0      | 1034      | 1.55%   |
| 2.01-3.0        | 915       | 1.37%   |
| 0.51-1.0        | 270       | 0.4%    |
| More than 256.0 | 205       | 0.31%   |
| 0.01-0.5        | 27        | 0.04%   |
| Unknown         | 5         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 26674     | 36.97%  |
| 2.01-3.0        | 20487     | 28.4%   |
| 4.01-8.0        | 9624      | 13.34%  |
| 3.01-4.0        | 9352      | 12.96%  |
| 8.01-16.0       | 2680      | 3.71%   |
| 0.51-1.0        | 2181      | 3.02%   |
| 0.01-0.5        | 400       | 0.55%   |
| 16.01-24.0      | 384       | 0.53%   |
| 24.01-32.0      | 149       | 0.21%   |
| 32.01-64.0      | 125       | 0.17%   |
| 64.01-256.0     | 59        | 0.08%   |
| Unknown         | 19        | 0.03%   |
| More than 256.0 | 5         | 0.01%   |
| 0               | 2         | 0.003%  |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 42505     | 62.75%  |
| 2       | 15966     | 23.57%  |
| 3       | 4488      | 6.63%   |
| 4       | 1940      | 2.86%   |
| 0       | 904       | 1.33%   |
| 5       | 879       | 1.3%    |
| 6       | 437       | 0.65%   |
| 7       | 221       | 0.33%   |
| 8       | 98        | 0.14%   |
| 9       | 74        | 0.11%   |
| Unknown | 58        | 0.09%   |
| 10      | 43        | 0.06%   |
| 11      | 37        | 0.05%   |
| 13      | 17        | 0.03%   |
| 12      | 11        | 0.02%   |
| 17      | 7         | 0.01%   |
| 16      | 6         | 0.01%   |
| 25      | 5         | 0.01%   |
| 20      | 5         | 0.01%   |
| 14      | 5         | 0.01%   |
| 18      | 4         | 0.01%   |
| 36      | 3         | 0.004%  |
| 21      | 3         | 0.004%  |
| 32      | 2         | 0.003%  |
| 26      | 2         | 0.003%  |
| 15      | 2         | 0.003%  |
| 101     | 1         | 0.001%  |
| 87      | 1         | 0.001%  |
| 70      | 1         | 0.001%  |
| 45      | 1         | 0.001%  |
| 40      | 1         | 0.001%  |
| 38      | 1         | 0.001%  |
| 27      | 1         | 0.001%  |
| 24      | 1         | 0.001%  |
| 23      | 1         | 0.001%  |
| 22      | 1         | 0.001%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 38886     | 58.54%  |
| Yes       | 27539     | 41.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 57061     | 86.37%  |
| No        | 9008      | 13.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 49424     | 74.53%  |
| No        | 16893     | 25.47%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 37434     | 56.1%   |
| No        | 29288     | 43.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 11646     | 17.59%  |
| Germany      | 7206      | 10.88%  |
| Brazil       | 4131      | 6.24%   |
| France       | 4008      | 6.05%   |
| UK           | 2931      | 4.43%   |
| Italy        | 2856      | 4.31%   |
| Russia       | 2592      | 3.91%   |
| India        | 2129      | 3.22%   |
| Canada       | 2108      | 3.18%   |
| Spain        | 2067      | 3.12%   |
| Netherlands  | 1507      | 2.28%   |
| Poland       | 1473      | 2.22%   |
| Australia    | 1084      | 1.64%   |
| Switzerland  | 943       | 1.42%   |
| Mexico       | 809       | 1.22%   |
| Sweden       | 743       | 1.12%   |
| Czechia      | 723       | 1.09%   |
| Belgium      | 712       | 1.08%   |
| Ukraine      | 703       | 1.06%   |
| Turkey       | 675       | 1.02%   |
| Austria      | 674       | 1.02%   |
| Hungary      | 671       | 1.01%   |
| Argentina    | 663       | 1%      |
| China        | 571       | 0.86%   |
| Portugal     | 559       | 0.84%   |
| Romania      | 546       | 0.82%   |
| Japan        | 510       | 0.77%   |
| Finland      | 496       | 0.75%   |
| Greece       | 471       | 0.71%   |
| Indonesia    | 423       | 0.64%   |
| South Africa | 419       | 0.63%   |
| Denmark      | 377       | 0.57%   |
| Norway       | 373       | 0.56%   |
| Colombia     | 362       | 0.55%   |
| Bulgaria     | 336       | 0.51%   |
| Chile        | 320       | 0.48%   |
| Iran         | 311       | 0.47%   |
| Israel       | 299       | 0.45%   |
| Taiwan       | 271       | 0.41%   |
| South Korea  | 258       | 0.39%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 804       | 1.14%   |
| Berlin            | 708       | 1.01%   |
| Paris             | 627       | 0.89%   |
| Sao Paulo         | 538       | 0.77%   |
| Rome              | 392       | 0.56%   |
| Vienna            | 380       | 0.54%   |
| Milan             | 377       | 0.54%   |
| Warsaw            | 369       | 0.53%   |
| Madrid            | 359       | 0.51%   |
| Munich            | 349       | 0.5%    |
| St Petersburg     | 347       | 0.49%   |
| Budapest          | 302       | 0.43%   |
| Hamburg           | 295       | 0.42%   |
| Zurich            | 286       | 0.41%   |
| Sydney            | 283       | 0.4%    |
| Prague            | 280       | 0.4%    |
| Barcelona         | 276       | 0.39%   |
| Bengaluru         | 268       | 0.38%   |
| Istanbul          | 262       | 0.37%   |
| Athens            | 258       | 0.37%   |
| Amsterdam         | 248       | 0.35%   |
| Melbourne         | 246       | 0.35%   |
| Kyiv              | 244       | 0.35%   |
| Rio de Janeiro    | 242       | 0.34%   |
| Toronto           | 233       | 0.33%   |
| Helsinki          | 232       | 0.33%   |
| Montreal          | 228       | 0.32%   |
| Frankfurt am Main | 209       | 0.3%    |
| Sofia             | 194       | 0.28%   |
| Bucharest         | 187       | 0.27%   |
| Tehran            | 184       | 0.26%   |
| New York          | 181       | 0.26%   |
| Singapore         | 180       | 0.26%   |
| Buenos Aires      | 180       | 0.26%   |
| London            | 173       | 0.25%   |
| Stuttgart         | 170       | 0.24%   |
| Chicago           | 166       | 0.24%   |
| Mexico City       | 164       | 0.23%   |
| Mumbai            | 162       | 0.23%   |
| Chennai           | 158       | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 14293     | 21894  | 15.74%  |
| WDC                         | 14278     | 21562  | 15.73%  |
| Samsung Electronics         | 13684     | 19687  | 15.07%  |
| Toshiba                     | 6387      | 8399   | 7.04%   |
| Kingston                    | 4767      | 6042   | 5.25%   |
| Sandisk                     | 4532      | 5914   | 4.99%   |
| Unknown                     | 3801      | 5135   | 4.19%   |
| Hitachi                     | 3137      | 4146   | 3.46%   |
| Crucial                     | 2810      | 3856   | 3.1%    |
| Intel                       | 2372      | 3319   | 2.61%   |
| SK hynix                    | 2354      | 2876   | 2.59%   |
| HGST                        | 1798      | 2450   | 1.98%   |
| Micron Technology           | 1475      | 1803   | 1.62%   |
| A-DATA Technology           | 1142      | 1415   | 1.26%   |
| Apple                       | 695       | 864    | 0.77%   |
| KIOXIA                      | 685       | 832    | 0.75%   |
| China                       | 666       | 817    | 0.73%   |
| Phison                      | 605       | 799    | 0.67%   |
| Fujitsu                     | 456       | 714    | 0.5%    |
| PNY                         | 447       | 556    | 0.49%   |
| Maxtor                      | 424       | 570    | 0.47%   |
| Silicon Motion              | 416       | 538    | 0.46%   |
| SPCC                        | 415       | 556    | 0.46%   |
| Intenso                     | 414       | 573    | 0.46%   |
| LITEON                      | 397       | 484    | 0.44%   |
| OCZ                         | 373       | 467    | 0.41%   |
| Transcend                   | 344       | 402    | 0.38%   |
| Micron/Crucial Technology   | 330       | 429    | 0.36%   |
| Patriot                     | 272       | 343    | 0.3%    |
| Phison Electronics          | 262       | 336    | 0.29%   |
| Unknown                     | 260       | 298    | 0.29%   |
| Corsair                     | 259       | 342    | 0.29%   |
| JMicron Technology          | 232       | 266    | 0.26%   |
| Hewlett-Packard             | 225       | 439    | 0.25%   |
| GOODRAM                     | 218       | 295    | 0.24%   |
| LITEONIT                    | 202       | 246    | 0.22%   |
| Kingston Technology Company | 187       | 234    | 0.21%   |
| ASMT                        | 181       | 268    | 0.2%    |
| Team                        | 175       | 227    | 0.19%   |
| Apacer                      | 141       | 162    | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 984       | 0.99%   |
| Seagate ST1000LM035-1RK172 1TB                    | 889       | 0.9%    |
| Seagate ST500DM002-1BD142 500GB                   | 761       | 0.77%   |
| Unknown MMC Card  32GB                            | 732       | 0.74%   |
| Samsung SSD 860 EVO 500GB                         | 727       | 0.73%   |
| Toshiba MQ01ABD100 1TB                            | 720       | 0.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 697       | 0.7%    |
| Samsung SSD 850 EVO 250GB                         | 657       | 0.66%   |
| Kingston SA400S37120G 120GB SSD                   | 602       | 0.61%   |
| Unknown MMC Card  64GB                            | 584       | 0.59%   |
| Kingston SA400S37480G 480GB SSD                   | 540       | 0.54%   |
| Seagate ST1000DM010-2EP102 1TB                    | 527       | 0.53%   |
| Samsung NVMe SSD Drive 512GB                      | 507       | 0.51%   |
| Samsung SSD 850 EVO 500GB                         | 503       | 0.51%   |
| Toshiba MQ01ABF050 500GB                          | 467       | 0.47%   |
| Toshiba MQ04ABF100 1TB                            | 464       | 0.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 438       | 0.44%   |
| Toshiba DT01ACA100 1TB                            | 431       | 0.43%   |
| Seagate ST500LT012-1DG142 500GB                   | 424       | 0.43%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 417       | 0.42%   |
| Kingston SV300S37A120G 120GB SSD                  | 414       | 0.42%   |
| HGST HTS721010A9E630 1TB                          | 408       | 0.41%   |
| Seagate ST2000DM008-2FR102 2TB                    | 397       | 0.4%    |
| Seagate ST9500325AS 500GB                         | 390       | 0.39%   |
| Samsung NVMe SSD Drive 500GB                      | 388       | 0.39%   |
| Crucial CT500MX500SSD1 500GB                      | 388       | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 387       | 0.39%   |
| SanDisk NVMe SSD Drive 512GB                      | 372       | 0.37%   |
| Samsung SSD 860 EVO 1TB                           | 369       | 0.37%   |
| Samsung SSD 860 EVO 250GB                         | 365       | 0.37%   |
| Unknown SD/MMC/MS PRO 256GB                       | 343       | 0.35%   |
| Crucial CT240BX500SSD1 240GB                      | 341       | 0.34%   |
| Seagate ST1000DM003-1CH162 1TB                    | 340       | 0.34%   |
| Seagate ST3500418AS 500GB                         | 334       | 0.34%   |
| Unknown MMC Card  128GB                           | 318       | 0.32%   |
| Intel NVMe SSD Drive 512GB                        | 315       | 0.32%   |
| Crucial CT1000MX500SSD1 1TB                       | 284       | 0.29%   |
| Seagate Expansion 1TB                             | 282       | 0.28%   |
| Seagate ST1000DM003-1ER162 1TB                    | 281       | 0.28%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 276       | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14042     | 21419  | 35.29%  |
| WDC                 | 11841     | 18102  | 29.76%  |
| Toshiba             | 4886      | 6421   | 12.28%  |
| Hitachi             | 3133      | 4141   | 7.87%   |
| Samsung Electronics | 1907      | 2654   | 4.79%   |
| HGST                | 1796      | 2420   | 4.51%   |
| Fujitsu             | 450       | 703    | 1.13%   |
| Maxtor              | 402       | 529    | 1.01%   |
| Unknown             | 373       | 486    | 0.94%   |
| Apple               | 223       | 246    | 0.56%   |
| JMicron Technology  | 161       | 188    | 0.4%    |
| Hewlett-Packard     | 70        | 169    | 0.18%   |
| Intenso             | 60        | 81     | 0.15%   |
| TO Exter            | 49        | 59     | 0.12%   |
| ASMT                | 48        | 105    | 0.12%   |
| External            | 47        | 62     | 0.12%   |
| ExcelStor           | 23        | 27     | 0.06%   |
| LaCie               | 22        | 29     | 0.06%   |
| StoreJet            | 21        | 21     | 0.05%   |
| SSK                 | 15        | 16     | 0.04%   |
| HGST HTS            | 14        | 16     | 0.04%   |
| WD MediaMax         | 13        | 15     | 0.03%   |
| MARVELL             | 13        | 17     | 0.03%   |
| IBM/Hitachi         | 12        | 13     | 0.03%   |
| HPE                 | 12        | 22     | 0.03%   |
| USB                 | 11        | 12     | 0.03%   |
| SABRENT             | 11        | 17     | 0.03%   |
| ASMT109x            | 10        | 18     | 0.03%   |
| Inateck             | 9         | 9      | 0.02%   |
| USB3.0              | 8         | 10     | 0.02%   |
| KESU                | 8         | 12     | 0.02%   |
| ASMedia             | 8         | 8      | 0.02%   |
| Quantum             | 7         | 8      | 0.02%   |
| Unknown             | 7         | 9      | 0.02%   |
| Maxone              | 5         | 6      | 0.01%   |
| MARSHAL             | 5         | 5      | 0.01%   |
| TDAS                | 4         | 15     | 0.01%   |
| SAGE                | 4         | 4      | 0.01%   |
| IBM-ESXS            | 4         | 11     | 0.01%   |
| DELLBOSS            | 4         | 4      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6615      | 9165   | 23.35%  |
| Kingston            | 4006      | 5101   | 14.14%  |
| SanDisk             | 2705      | 3566   | 9.55%   |
| Crucial             | 2571      | 3543   | 9.08%   |
| WDC                 | 1672      | 2119   | 5.9%    |
| A-DATA Technology   | 925       | 1161   | 3.27%   |
| Intel               | 921       | 1263   | 3.25%   |
| China               | 654       | 800    | 2.31%   |
| Micron Technology   | 640       | 836    | 2.26%   |
| SK hynix            | 547       | 732    | 1.93%   |
| Toshiba             | 487       | 624    | 1.72%   |
| PNY                 | 419       | 521    | 1.48%   |
| SPCC                | 383       | 519    | 1.35%   |
| LITEON              | 375       | 462    | 1.32%   |
| OCZ                 | 366       | 443    | 1.29%   |
| Transcend           | 321       | 378    | 1.13%   |
| Apple               | 315       | 353    | 1.11%   |
| Intenso             | 275       | 382    | 0.97%   |
| Patriot             | 263       | 333    | 0.93%   |
| GOODRAM             | 213       | 289    | 0.75%   |
| LITEONIT            | 202       | 246    | 0.71%   |
| Corsair             | 191       | 254    | 0.67%   |
| Team                | 161       | 207    | 0.57%   |
| Apacer              | 134       | 154    | 0.47%   |
| KingSpec            | 131       | 161    | 0.46%   |
| ASMT                | 126       | 155    | 0.44%   |
| Netac               | 122       | 152    | 0.43%   |
| Hewlett-Packard     | 121       | 192    | 0.43%   |
| Plextor             | 112       | 145    | 0.4%    |
| Lexar               | 112       | 127    | 0.4%    |
| SABRENT             | 106       | 131    | 0.37%   |
| Gigabyte Technology | 103       | 138    | 0.36%   |
| Seagate             | 97        | 121    | 0.34%   |
| Unknown             | 85        | 92     | 0.3%    |
| KingDian            | 79        | 95     | 0.28%   |
| Mushkin             | 63        | 103    | 0.22%   |
| FORESEE             | 60        | 63     | 0.21%   |
| Unknown             | 57        | 65     | 0.2%    |
| Emtec               | 44        | 52     | 0.16%   |
| Verbatim            | 43        | 54     | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 34127     | 58211  | 41.45%  |
| SSD     | 25403     | 37171  | 30.85%  |
| NVMe    | 18178     | 24651  | 22.08%  |
| MMC     | 3249      | 4223   | 3.95%   |
| Unknown | 1383      | 2091   | 1.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 49422     | 91783  | 66.46%  |
| NVMe | 18163     | 24592  | 24.42%  |
| SAS  | 3532      | 5749   | 4.75%   |
| MMC  | 3249      | 4223   | 4.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 36276     | 55478  | 58.55%  |
| 0.51-1.0        | 17872     | 25642  | 28.85%  |
| 1.01-2.0        | 4380      | 7020   | 7.07%   |
| 3.01-4.0        | 1263      | 2359   | 2.04%   |
| 4.01-10.0       | 983       | 2367   | 1.59%   |
| 2.01-3.0        | 966       | 1785   | 1.56%   |
| 10.01-20.0      | 206       | 723    | 0.33%   |
| 0               | 4         | 4      | 0.01%   |
| More than 100.0 | 2         | 2      | 0.003%  |
| 20.01-50.0      | 1         | 2      | 0.002%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 19808     | 28.76%  |
| 251-500        | 16820     | 24.42%  |
| 501-1000       | 10694     | 15.52%  |
| 51-100         | 4975      | 7.22%   |
| 1001-2000      | 4527      | 6.57%   |
| 1-20           | 3409      | 4.95%   |
| 21-50          | 3154      | 4.58%   |
| More than 3000 | 2618      | 3.8%    |
| 2001-3000      | 1691      | 2.45%   |
| Unknown        | 1189      | 1.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 30334     | 42.23%  |
| 21-50          | 12998     | 18.09%  |
| 101-250        | 8385      | 11.67%  |
| 51-100         | 8175      | 11.38%  |
| 251-500        | 4528      | 6.3%    |
| 501-1000       | 3087      | 4.3%    |
| 1001-2000      | 1607      | 2.24%   |
| Unknown        | 1189      | 1.66%   |
| More than 3000 | 935       | 1.3%    |
| 2001-3000      | 594       | 0.83%   |
| 0              | 4         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB    | 48        | 53     | 1.61%   |
| Seagate ST1000LM035-1RK172 1TB        | 43        | 44     | 1.44%   |
| Toshiba MQ01ABD100 1TB                | 40        | 44     | 1.34%   |
| Seagate ST500DM002-1BD142 500GB       | 40        | 43     | 1.34%   |
| Seagate ST9500325AS 500GB             | 35        | 36     | 1.17%   |
| HGST HTS541010A9E680 1TB              | 32        | 34     | 1.07%   |
| Seagate ST3500418AS 500GB             | 28        | 34     | 0.94%   |
| HGST HTS721010A9E630 1TB              | 28        | 31     | 0.94%   |
| HGST HTS725050A7E630 500GB            | 24        | 24     | 0.8%    |
| Seagate ST1000DM003-1CH162 1TB        | 21        | 23     | 0.7%    |
| Seagate ST500LM021-1KJ152 500GB       | 20        | 22     | 0.67%   |
| Toshiba MQ04ABF100 1TB                | 18        | 18     | 0.6%    |
| Seagate ST500LT012-1DG142 500GB       | 18        | 19     | 0.6%    |
| Kingston SV300S37A120G 120GB SSD      | 18        | 21     | 0.6%    |
| Seagate ST31000528AS 1TB              | 17        | 19     | 0.57%   |
| HGST HTS545050A7E680 500GB            | 17        | 17     | 0.57%   |
| Seagate ST500LT012-9WS142 500GB       | 16        | 18     | 0.54%   |
| Kingston SA400S37240G 240GB SSD       | 16        | 19     | 0.54%   |
| HGST HTS545050A7E380 500GB            | 16        | 17     | 0.54%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 15        | 15     | 0.5%    |
| Seagate ST9500420AS 500GB             | 15        | 15     | 0.5%    |
| Samsung Electronics SSD 870 EVO 500GB | 15        | 15     | 0.5%    |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 14        | 18     | 0.47%   |
| Toshiba MQ01ABF050 500GB              | 13        | 13     | 0.44%   |
| Seagate ST1000DM010-2EP102 1TB        | 13        | 14     | 0.44%   |
| Kingston SA400S37120G 120GB SSD       | 13        | 19     | 0.44%   |
| WDC WD40EFRX-68WT0N0 4TB              | 12        | 19     | 0.4%    |
| WDC WD10EARS-00Y5B1 1TB               | 12        | 16     | 0.4%    |
| SK hynix HFS256G39TND-N210A 256GB SSD | 12        | 12     | 0.4%    |
| Seagate ST2000DM001-1CH164 2TB        | 12        | 12     | 0.4%    |
| Seagate ST1000LX015-1U7172 1TB        | 12        | 12     | 0.4%    |
| Hitachi HTS543232A7A384 320GB         | 12        | 12     | 0.4%    |
| WDC WD5000AAKX-001CA0 500GB           | 11        | 14     | 0.37%   |
| Kingston SA400S37480G 480GB SSD       | 11        | 14     | 0.37%   |
| Hitachi HTS545050A7E380 500GB         | 11        | 12     | 0.37%   |
| WDC WD10EZEX-60ZF5A0 1TB              | 10        | 11     | 0.34%   |
| Toshiba DT01ACA100 1TB                | 10        | 12     | 0.34%   |
| Seagate ST9320423AS 320GB             | 10        | 10     | 0.34%   |
| Seagate ST9320325AS 320GB             | 10        | 10     | 0.34%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 10        | 12     | 0.34%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 741       | 887    | 25.46%  |
| WDC                 | 622       | 736    | 21.37%  |
| Toshiba             | 215       | 238    | 7.39%   |
| Hitachi             | 215       | 237    | 7.39%   |
| Samsung Electronics | 203       | 243    | 6.97%   |
| HGST                | 145       | 156    | 4.98%   |
| SK hynix            | 103       | 112    | 3.54%   |
| Kingston            | 96        | 119    | 3.3%    |
| Intel               | 95        | 120    | 3.26%   |
| SanDisk             | 78        | 93     | 2.68%   |
| Micron Technology   | 57        | 70     | 1.96%   |
| Crucial             | 57        | 66     | 1.96%   |
| A-DATA Technology   | 47        | 57     | 1.61%   |
| Maxtor              | 25        | 35     | 0.86%   |
| Fujitsu             | 17        | 17     | 0.58%   |
| Apple               | 16        | 19     | 0.55%   |
| LITEON              | 15        | 17     | 0.52%   |
| OCZ                 | 12        | 13     | 0.41%   |
| Corsair             | 12        | 13     | 0.41%   |
| China               | 11        | 11     | 0.38%   |
| LITEONIT            | 9         | 11     | 0.31%   |
| Unknown             | 8         | 10     | 0.27%   |
| Hewlett-Packard     | 7         | 7      | 0.24%   |
| Unknown             | 6         | 6      | 0.21%   |
| Patriot             | 5         | 5      | 0.17%   |
| LDLC                | 5         | 6      | 0.17%   |
| KingSpec            | 5         | 5      | 0.17%   |
| Intenso             | 5         | 6      | 0.17%   |
| ASMT                | 5         | 5      | 0.17%   |
| Transcend           | 4         | 4      | 0.14%   |
| SPCC                | 4         | 4      | 0.14%   |
| Mushkin             | 4         | 4      | 0.14%   |
| XPG                 | 3         | 3      | 0.1%    |
| Netac               | 3         | 4      | 0.1%    |
| ASMedia             | 3         | 3      | 0.1%    |
| 2.5"                | 3         | 3      | 0.1%    |
| WD MediaMax         | 2         | 2      | 0.07%   |
| WALRAM              | 2         | 2      | 0.07%   |
| SSSTC               | 2         | 2      | 0.07%   |
| Plextor             | 2         | 2      | 0.07%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 741       | 887    | 36.2%   |
| WDC                 | 578       | 688    | 28.24%  |
| Hitachi             | 215       | 237    | 10.5%   |
| Toshiba             | 203       | 225    | 9.92%   |
| HGST                | 145       | 156    | 7.08%   |
| Samsung Electronics | 94        | 109    | 4.59%   |
| Maxtor              | 25        | 35     | 1.22%   |
| Fujitsu             | 17        | 17     | 0.83%   |
| Apple               | 13        | 16     | 0.64%   |
| Unknown             | 7         | 9      | 0.34%   |
| Hewlett-Packard     | 4         | 4      | 0.2%    |
| WD MediaMax         | 2         | 2      | 0.1%    |
| ASMT                | 2         | 2      | 0.1%    |
| HPE                 | 1         | 1      | 0.05%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1938      | 2388   | 69.31%  |
| SSD     | 713       | 848    | 25.5%   |
| NVMe    | 144       | 161    | 5.15%   |
| Unknown | 1         | 1      | 0.04%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB                                 | 3         | 3      | 4.92%   |
| Samsung Electronics SSD 980 500GB                               | 3         | 3      | 4.92%   |
| HGST HTS721010A9E630 1TB                                        | 3         | 3      | 4.92%   |
| WDC WD7500BPVT-22HXZT1 752GB                                    | 2         | 3      | 3.28%   |
| WDC WD10SPZX-21Z10T0 1TB                                        | 2         | 2      | 3.28%   |
| Samsung Electronics MZVLB1T0HALR-00000 1TB                      | 2         | 3      | 3.28%   |
| WDC WD800BB-00FJA0 80GB                                         | 1         | 1      | 1.64%   |
| WDC WD5000BEVT-22A0RT0 500GB                                    | 1         | 1      | 1.64%   |
| WDC WD40EZRZ-00GXCB0 4TB                                        | 1         | 2      | 1.64%   |
| WDC WD3200BEKT-60PVMT0 320GB                                    | 1         | 1      | 1.64%   |
| WDC WD3200AAJS-22VWA0 320GB                                     | 1         | 1      | 1.64%   |
| WDC WD1500HLFS-01G6U0 150GB                                     | 1         | 1      | 1.64%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB                            | 1         | 1      | 1.64%   |
| Unknown 00000  16GB                                             | 1         | 1      | 1.64%   |
| Toshiba THNSN5256GPUK NVMe 256GB                                | 1         | 1      | 1.64%   |
| Toshiba NVMe SSD Drive 256GB                                    | 1         | 1      | 1.64%   |
| Toshiba MQ02ABF050H 500GB                                       | 1         | 1      | 1.64%   |
| Toshiba MK5065GSXN 500GB                                        | 1         | 1      | 1.64%   |
| Toshiba MK3265GSX 320GB                                         | 1         | 1      | 1.64%   |
| Toshiba DT01ACA200 2TB                                          | 1         | 1      | 1.64%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB                         | 1         | 1      | 1.64%   |
| Seagate ST9500420AS 500GB                                       | 1         | 3      | 1.64%   |
| Seagate ST3500630AS 500GB                                       | 1         | 1      | 1.64%   |
| Seagate ST3500418AS 500GB                                       | 1         | 1      | 1.64%   |
| Seagate ST3300657SS 304GB                                       | 1         | 2      | 1.64%   |
| Seagate ST31000520AS 1TB                                        | 1         | 1      | 1.64%   |
| Seagate ST31000340NS 1TB                                        | 1         | 1      | 1.64%   |
| Seagate ST2000DM001-1CH164 2TB                                  | 1         | 1      | 1.64%   |
| Seagate ST1000LM048-2E7172 1TB                                  | 1         | 1      | 1.64%   |
| Samsung Electronics SSD 960 EVO 250GB                           | 1         | 1      | 1.64%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 1.64%   |
| Samsung Electronics HD502HJ 500GB                               | 1         | 1      | 1.64%   |
| Samsung Electronics HD161GJ 160GB                               | 1         | 1      | 1.64%   |
| Samsung Electronics HD160JJ 160GB                               | 1         | 1      | 1.64%   |
| Samsung Electronics HD103SJ 1TB                                 | 1         | 1      | 1.64%   |
| Mushkin MKNSSDCR120GB-7                                         | 1         | 1      | 1.64%   |
| Maxtor STM380211AS 80GB                                         | 1         | 1      | 1.64%   |
| KingDian S400 120GB                                             | 1         | 1      | 1.64%   |
| JMicron Technology Tech 250GB                                   | 1         | 1      | 1.64%   |
| Intel SSDSCKGF256A5 SATA 256GB                                  | 1         | 1      | 1.64%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 13     | 18.03%  |
| Seagate             | 11        | 14     | 18.03%  |
| Samsung Electronics | 11        | 12     | 18.03%  |
| Toshiba             | 6         | 6      | 9.84%   |
| HGST                | 4         | 4      | 6.56%   |
| Intel               | 3         | 6      | 4.92%   |
| Hitachi             | 3         | 3      | 4.92%   |
| Crucial             | 2         | 2      | 3.28%   |
| Apple               | 2         | 3      | 3.28%   |
| Unknown             | 1         | 1      | 1.64%   |
| SK hynix            | 1         | 1      | 1.64%   |
| Mushkin             | 1         | 1      | 1.64%   |
| Maxtor              | 1         | 1      | 1.64%   |
| KingDian            | 1         | 1      | 1.64%   |
| JMicron Technology  | 1         | 1      | 1.64%   |
| Hewlett-Packard     | 1         | 4      | 1.64%   |
| A-DATA Technology   | 1         | 1      | 1.64%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 48682     | 94742  | 71.18%  |
| Works    | 16939     | 28130  | 24.77%  |
| Malfunc  | 2704      | 3398   | 3.95%   |
| Failed   | 61        | 74     | 0.09%   |
| Limited  | 2         | 2      | 0.003%  |
| Fixed    | 1         | 1      | 0.001%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 45532     | 56.3%   |
| AMD                              | 11085     | 13.71%  |
| Samsung Electronics              | 6334      | 7.83%   |
| SanDisk                          | 2788      | 3.45%   |
| SK hynix                         | 1760      | 2.18%   |
| Nvidia                           | 1257      | 1.55%   |
| ASMedia Technology               | 1200      | 1.48%   |
| Toshiba America Info Systems     | 1120      | 1.38%   |
| Marvell Technology Group         | 1073      | 1.33%   |
| JMicron Technology               | 1025      | 1.27%   |
| Phison Electronics               | 973       | 1.2%    |
| Kingston Technology Company      | 960       | 1.19%   |
| Micron Technology                | 841       | 1.04%   |
| KIOXIA                           | 709       | 0.88%   |
| Micron/Crucial Technology        | 573       | 0.71%   |
| Silicon Motion                   | 520       | 0.64%   |
| ADATA Technology                 | 390       | 0.48%   |
| LSI Logic / Symbios Logic        | 369       | 0.46%   |
| Broadcom / LSI                   | 287       | 0.35%   |
| VIA Technologies                 | 227       | 0.28%   |
| Realtek Semiconductor            | 206       | 0.25%   |
| Apple                            | 166       | 0.21%   |
| Union Memory (Shenzhen)          | 160       | 0.2%    |
| Solid State Storage Technology   | 144       | 0.18%   |
| Silicon Image                    | 128       | 0.16%   |
| Silicon Integrated Systems [SiS] | 126       | 0.16%   |
| Hewlett-Packard                  | 126       | 0.16%   |
| Adaptec                          | 104       | 0.13%   |
| MAXIO Technology (Hangzhou)      | 101       | 0.12%   |
| Lite-On Technology               | 100       | 0.12%   |
| Shenzhen Longsys Electronics     | 73        | 0.09%   |
| Seagate Technology               | 69        | 0.09%   |
| Lenovo                           | 51        | 0.06%   |
| Yangtze Memory Technologies      | 37        | 0.05%   |
| Integrated Technology Express    | 32        | 0.04%   |
| Solidigm                         | 20        | 0.02%   |
| INNOGRIT                         | 20        | 0.02%   |
| Areca Technology                 | 18        | 0.02%   |
| Transcend                        | 14        | 0.02%   |
| HighPoint Technologies           | 14        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 7117      | 7.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3539      | 3.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3060      | 3.24%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2933      | 3.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2924      | 3.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2516      | 2.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2171      | 2.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1556      | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1544      | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1529      | 1.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1527      | 1.62%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1522      | 1.61%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1497      | 1.59%   |
| Intel SATA Controller [RAID Mode]                                                       | 1404      | 1.49%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1271      | 1.35%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1271      | 1.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1266      | 1.34%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1220      | 1.29%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 1190      | 1.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1171      | 1.24%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1143      | 1.21%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1128      | 1.2%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1120      | 1.19%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 1103      | 1.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1045      | 1.11%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 988       | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 925       | 0.98%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 904       | 0.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 886       | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 853       | 0.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 833       | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 757       | 0.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 712       | 0.75%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 706       | 0.75%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 647       | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 646       | 0.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 633       | 0.67%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 630       | 0.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 627       | 0.66%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 620       | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 46724     | 56.71%  |
| NVMe | 18440     | 22.38%  |
| IDE  | 10138     | 12.3%   |
| RAID | 6470      | 7.85%   |
| SAS  | 417       | 0.51%   |
| SCSI | 203       | 0.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 51514     | 78.16%  |
| AMD           | 13657     | 20.72%  |
| ARM           | 702       | 1.07%   |
| CentaurHauls  | 17        | 0.03%   |
| Unknown       | 12        | 0.02%   |
| sifive,u74-mc | 2         | 0.003%  |
| HiSilicon     | 2         | 0.003%  |
| QUALCOMM      | 1         | 0.002%  |
| Phytium       | 1         | 0.002%  |
| IBM/S390      | 1         | 0.002%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 804       | 1.22%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 722       | 1.09%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 657       | 0.99%   |
| ARM Processor                                 | 654       | 0.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 636       | 0.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 618       | 0.94%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 563       | 0.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 542       | 0.82%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 497       | 0.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 454       | 0.69%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 440       | 0.67%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 436       | 0.66%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 414       | 0.63%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 395       | 0.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 394       | 0.6%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 393       | 0.6%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 368       | 0.56%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 363       | 0.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 355       | 0.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 345       | 0.52%   |
| AMD Ryzen 5 3600 6-Core Processor             | 335       | 0.51%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 335       | 0.51%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 334       | 0.51%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 315       | 0.48%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 315       | 0.48%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 296       | 0.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 286       | 0.43%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 278       | 0.42%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 274       | 0.41%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 271       | 0.41%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 271       | 0.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 262       | 0.4%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 260       | 0.39%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 254       | 0.38%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 251       | 0.38%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 247       | 0.37%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 247       | 0.37%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 246       | 0.37%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 244       | 0.37%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 234       | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 14767     | 22.38%  |
| Intel Core i7           | 13087     | 19.83%  |
| Intel Core i3           | 5283      | 8.01%   |
| Other                   | 4773      | 7.23%   |
| Intel Core 2 Duo        | 2938      | 4.45%   |
| AMD Ryzen 5             | 2897      | 4.39%   |
| Intel Celeron           | 2857      | 4.33%   |
| Intel Xeon              | 2141      | 3.24%   |
| AMD Ryzen 7             | 2122      | 3.22%   |
| Intel Pentium           | 1632      | 2.47%   |
| AMD FX                  | 1063      | 1.61%   |
| Intel Atom              | 1020      | 1.55%   |
| Intel Pentium Dual-Core | 848       | 1.28%   |
| AMD Ryzen 9             | 685       | 1.04%   |
| Intel Core 2 Quad       | 678       | 1.03%   |
| AMD Ryzen 3             | 649       | 0.98%   |
| AMD A6                  | 571       | 0.87%   |
| AMD A8                  | 531       | 0.8%    |
| AMD A10                 | 492       | 0.75%   |
| Intel Core i9           | 450       | 0.68%   |
| AMD A4                  | 419       | 0.63%   |
| Intel Core 2            | 412       | 0.62%   |
| AMD Phenom II X4        | 373       | 0.57%   |
| Intel Pentium Dual      | 371       | 0.56%   |
| AMD Athlon II X2        | 343       | 0.52%   |
| AMD Athlon 64 X2        | 320       | 0.48%   |
| AMD E                   | 228       | 0.35%   |
| AMD Ryzen 7 PRO         | 201       | 0.3%    |
| AMD E1                  | 199       | 0.3%    |
| Intel Pentium 4         | 195       | 0.3%    |
| AMD Athlon              | 192       | 0.29%   |
| Intel Genuine           | 182       | 0.28%   |
| AMD E2                  | 181       | 0.27%   |
| Intel Pentium Silver    | 171       | 0.26%   |
| AMD Athlon II X4        | 169       | 0.26%   |
| AMD Ryzen Threadripper  | 162       | 0.25%   |
| AMD Phenom II X6        | 154       | 0.23%   |
| Intel Pentium D         | 125       | 0.19%   |
| AMD Ryzen 5 PRO         | 123       | 0.19%   |
| AMD Phenom              | 101       | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 27048     | 40.98%  |
| 4       | 24422     | 37%     |
| 6       | 5607      | 8.49%   |
| 8       | 3942      | 5.97%   |
| 1       | 1375      | 2.08%   |
| 12      | 1079      | 1.63%   |
| 10      | 536       | 0.81%   |
| 16      | 509       | 0.77%   |
| 3       | 461       | 0.7%    |
| 14      | 394       | 0.6%    |
| 24      | 193       | 0.29%   |
| 20      | 86        | 0.13%   |
| 32      | 75        | 0.11%   |
| Unknown | 62        | 0.09%   |
| 28      | 56        | 0.08%   |
| 40      | 33        | 0.05%   |
| 18      | 24        | 0.04%   |
| 64      | 20        | 0.03%   |
| 48      | 17        | 0.03%   |
| 128     | 14        | 0.02%   |
| 5       | 13        | 0.02%   |
| 36      | 12        | 0.02%   |
| 44      | 8         | 0.01%   |
| 56      | 5         | 0.01%   |
| 52      | 3         | 0.005%  |
| 22      | 3         | 0.005%  |
| 104     | 2         | 0.003%  |
| 96      | 2         | 0.003%  |
| 80      | 2         | 0.003%  |
| 68      | 1         | 0.002%  |
| 26      | 1         | 0.002%  |
| 15      | 1         | 0.002%  |
| 9       | 1         | 0.002%  |
| 7       | 1         | 0.002%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 64735     | 98.21%  |
| 2       | 1071      | 1.62%   |
| Unknown | 60        | 0.09%   |
| 4       | 36        | 0.05%   |
| 3       | 10        | 0.02%   |
| 6       | 1         | 0.002%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 42902     | 65.01%  |
| 1       | 23021     | 34.89%  |
| Unknown | 62        | 0.09%   |
| 4       | 3         | 0.005%  |
| 112     | 1         | 0.002%  |
| 6       | 1         | 0.002%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 64856     | 98.36%  |
| Unknown        | 742       | 1.13%   |
| 32-bit         | 318       | 0.48%   |
| 64-bit         | 22        | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 20089     | 29.4%   |
| 0x206a7    | 3705      | 5.42%   |
| 0x306a9    | 3643      | 5.33%   |
| 0x306c3    | 2707      | 3.96%   |
| 0x1067a    | 2260      | 3.31%   |
| 0x906ea    | 1671      | 2.45%   |
| 0x806ea    | 1587      | 2.32%   |
| 0x806ec    | 1570      | 2.3%    |
| 0x806e9    | 1268      | 1.86%   |
| 0x40651    | 1264      | 1.85%   |
| 0x506e3    | 1205      | 1.76%   |
| 0x806c1    | 1175      | 1.72%   |
| 0x406e3    | 1147      | 1.68%   |
| 0x20655    | 1127      | 1.65%   |
| 0x906e9    | 1071      | 1.57%   |
| 0x306d4    | 1056      | 1.55%   |
| 0x6fd      | 749       | 1.1%    |
| 0x010000c8 | 646       | 0.95%   |
| 0x06000852 | 621       | 0.91%   |
| 0x10676    | 610       | 0.89%   |
| 0x30678    | 557       | 0.82%   |
| 0x08108109 | 543       | 0.79%   |
| 0x406c4    | 535       | 0.78%   |
| 0x06001119 | 522       | 0.76%   |
| 0x706e5    | 496       | 0.73%   |
| 0x20652    | 491       | 0.72%   |
| 0x806eb    | 457       | 0.67%   |
| 0x6fb      | 456       | 0.67%   |
| 0xa0652    | 431       | 0.63%   |
| 0x106e5    | 420       | 0.61%   |
| 0x906ed    | 411       | 0.6%    |
| 0x08701021 | 408       | 0.6%    |
| 0x0a50000c | 393       | 0.58%   |
| 0x0800820d | 361       | 0.53%   |
| 0x08108102 | 352       | 0.52%   |
| 0x08701013 | 323       | 0.47%   |
| 0x506c9    | 313       | 0.46%   |
| 0x706a1    | 310       | 0.45%   |
| 0x0810100b | 304       | 0.44%   |
| 0x08600106 | 299       | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 11047     | 16.74%  |
| Haswell          | 5827      | 8.83%   |
| SandyBridge      | 5139      | 7.79%   |
| IvyBridge        | 5060      | 7.67%   |
| Penryn           | 3748      | 5.68%   |
| Skylake          | 3703      | 5.61%   |
| Unknown          | 2514      | 3.81%   |
| Westmere         | 2406      | 3.64%   |
| Core             | 2105      | 3.19%   |
| Zen 2            | 1992      | 3.02%   |
| Silvermont       | 1936      | 2.93%   |
| TigerLake        | 1844      | 2.79%   |
| Zen+             | 1768      | 2.68%   |
| Broadwell        | 1636      | 2.48%   |
| K10              | 1616      | 2.45%   |
| Piledriver       | 1514      | 2.29%   |
| Zen 3            | 1329      | 2.01%   |
| CometLake        | 1231      | 1.86%   |
| Zen              | 1137      | 1.72%   |
| Icelake          | 1061      | 1.61%   |
| Alderlake Hybrid | 882       | 1.34%   |
| Nehalem          | 863       | 1.31%   |
| Excavator        | 851       | 1.29%   |
| Goldmont plus    | 783       | 1.19%   |
| K8 Hammer        | 614       | 0.93%   |
| Goldmont         | 469       | 0.71%   |
| Puma             | 437       | 0.66%   |
| Bobcat           | 431       | 0.65%   |
| NetBurst         | 380       | 0.58%   |
| Bonnell          | 328       | 0.5%    |
| Jaguar           | 287       | 0.43%   |
| Steamroller      | 275       | 0.42%   |
| K10 Llano        | 238       | 0.36%   |
| Bulldozer        | 213       | 0.32%   |
| P6               | 151       | 0.23%   |
| K8 & K10 hybrid  | 109       | 0.17%   |
| Tremont          | 62        | 0.09%   |
| Gracemont        | 14        | 0.02%   |
| K6               | 6         | 0.01%   |
| Sapphire Rapids  | 1         | 0.002%  |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 39154     | 50.44%  |
| Nvidia                                       | 20951     | 26.99%  |
| AMD                                          | 16336     | 21.04%  |
| Matrox Electronics Systems                   | 555       | 0.71%   |
| ASPEED Technology                            | 377       | 0.49%   |
| Silicon Integrated Systems [SiS]             | 103       | 0.13%   |
| VIA Technologies                             | 64        | 0.08%   |
| ATI Technologies                             | 42        | 0.05%   |
| XGI Technology (eXtreme Graphics Innovation) | 26        | 0.03%   |
| Zhaoxin                                      | 6         | 0.01%   |
| Silicon Motion                               | 6         | 0.01%   |
| Huawei Technologies                          | 6         | 0.01%   |
| S3 Graphics                                  | 2         | 0.003%  |
| NVidia / SGS Thomson (Joint Venture)         | 1         | 0.001%  |
| Moore Threads Technology                     | 1         | 0.001%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3733      | 4.68%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2739      | 3.44%   |
| Intel UHD Graphics 620                                                                   | 1947      | 2.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1672      | 2.1%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1658      | 2.08%   |
| Intel HD Graphics 620                                                                    | 1527      | 1.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1469      | 1.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1420      | 1.78%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1376      | 1.73%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1359      | 1.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1358      | 1.7%    |
| Intel HD Graphics 5500                                                                   | 1186      | 1.49%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1144      | 1.43%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1117      | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1102      | 1.38%   |
| Intel HD Graphics 530                                                                    | 1018      | 1.28%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1007      | 1.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 999       | 1.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 918       | 1.15%   |
| Intel HD Graphics 630                                                                    | 895       | 1.12%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 837       | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 825       | 1.03%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 776       | 0.97%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 704       | 0.88%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 662       | 0.83%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 641       | 0.8%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 641       | 0.8%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 630       | 0.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 550       | 0.69%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 546       | 0.68%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 543       | 0.68%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 491       | 0.62%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 479       | 0.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 464       | 0.58%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 464       | 0.58%   |
| AMD Lucienne                                                                             | 462       | 0.58%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 448       | 0.56%   |
| Nvidia GT218 [GeForce 210]                                                               | 442       | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 438       | 0.55%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 435       | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 28072     | 42.34%  |
| 1 x AMD                  | 12476     | 18.82%  |
| 1 x Nvidia               | 11498     | 17.34%  |
| Intel + Nvidia           | 8203      | 12.37%  |
| Intel + AMD              | 2092      | 3.16%   |
| 2 x AMD                  | 901       | 1.36%   |
| AMD + Nvidia             | 820       | 1.24%   |
| Other                    | 782       | 1.18%   |
| 1 x Matrox               | 473       | 0.71%   |
| 1 x ASPEED               | 253       | 0.38%   |
| 2 x Nvidia               | 196       | 0.3%    |
| Nvidia + ASPEED          | 103       | 0.16%   |
| 1 x SiS                  | 102       | 0.15%   |
| 1 x VIA                  | 63        | 0.1%    |
| Nvidia + Matrox          | 58        | 0.09%   |
| 1 x XGI                  | 22        | 0.03%   |
| 2 x Intel                | 21        | 0.03%   |
| AMD + Matrox             | 20        | 0.03%   |
| Intel + 2 x Nvidia       | 19        | 0.03%   |
| AMD + ASPEED             | 14        | 0.02%   |
| Intel + AMD + 1 x Nvidia | 12        | 0.02%   |
| Intel + 2 x AMD          | 9         | 0.01%   |
| 3 x AMD                  | 6         | 0.01%   |
| 1 x Zhaoxin              | 6         | 0.01%   |
| 1 x Huawei Technologies  | 6         | 0.01%   |
| 3 x Nvidia               | 5         | 0.01%   |
| 2 x Nvidia + 1 x ASPEED  | 5         | 0.01%   |
| 2 x AMD + 1 x Nvidia     | 5         | 0.01%   |
| 1 x Silicon Motion       | 5         | 0.01%   |
| 1 x Intel + 3 x Nvidia   | 5         | 0.01%   |
| AMD + 2 x Nvidia         | 5         | 0.01%   |
| 2 x Nvidia + 1 x Matrox  | 3         | 0.005%  |
| AMD + XGI                | 3         | 0.005%  |
| 4 x Nvidia               | 2         | 0.003%  |
| 3 x Nvidia + 1 x ASPEED  | 2         | 0.003%  |
| 1 x Intel + 4 x Nvidia   | 2         | 0.003%  |
| 1 x Intel + 3 x AMD      | 2         | 0.003%  |
| Intel + ASPEED           | 2         | 0.003%  |
| 6 x Nvidia               | 1         | 0.002%  |
| 5 x AMD                  | 1         | 0.002%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 52231     | 78.11%  |
| Proprietary | 11347     | 16.97%  |
| Unknown     | 3287      | 4.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 39637     | 58.47%  |
| 1.01-2.0   | 8171      | 12.05%  |
| 0.01-0.5   | 7023      | 10.36%  |
| 0.51-1.0   | 5122      | 7.56%   |
| 3.01-4.0   | 4082      | 6.02%   |
| 7.01-8.0   | 1692      | 2.5%    |
| 5.01-6.0   | 1035      | 1.53%   |
| 8.01-16.0  | 506       | 0.75%   |
| 2.01-3.0   | 378       | 0.56%   |
| 16.01-24.0 | 101       | 0.15%   |
| 4.01-5.0   | 25        | 0.04%   |
| 32.01-64.0 | 5         | 0.01%   |
| 24.01-32.0 | 5         | 0.01%   |
| 0          | 2         | 0.003%  |
| 6.01-7.0   | 1         | 0.001%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 9102      | 12.98%  |
| AU Optronics            | 8191      | 11.68%  |
| LG Display              | 6306      | 8.99%   |
| Chimei Innolux          | 5567      | 7.94%   |
| BOE                     | 5533      | 7.89%   |
| Dell                    | 4377      | 6.24%   |
| Goldstar                | 3409      | 4.86%   |
| Hewlett-Packard         | 2649      | 3.78%   |
| Acer                    | 2300      | 3.28%   |
| AOC                     | 1538      | 2.19%   |
| Ancor Communications    | 1480      | 2.11%   |
| Philips                 | 1459      | 2.08%   |
| BenQ                    | 1428      | 2.04%   |
| Sharp                   | 1399      | 1.99%   |
| Apple                   | 1318      | 1.88%   |
| Lenovo                  | 1304      | 1.86%   |
| Chi Mei Optoelectronics | 1059      | 1.51%   |
| Iiyama                  | 733       | 1.05%   |
| ViewSonic               | 698       | 1%      |
| Sony                    | 619       | 0.88%   |
| Unknown                 | 526       | 0.75%   |
| PANDA                   | 509       | 0.73%   |
| LG Electronics          | 504       | 0.72%   |
| InfoVision              | 466       | 0.66%   |
| ASUSTek Computer        | 429       | 0.61%   |
| LG Philips              | 338       | 0.48%   |
| HannStar                | 260       | 0.37%   |
| Panasonic               | 254       | 0.36%   |
| NEC Computers           | 247       | 0.35%   |
| Vizio                   | 244       | 0.35%   |
| Fujitsu Siemens         | 242       | 0.35%   |
| Eizo                    | 227       | 0.32%   |
| Toshiba                 | 198       | 0.28%   |
| CSO                     | 179       | 0.26%   |
| Medion                  | 158       | 0.23%   |
| Sceptre Tech            | 157       | 0.22%   |
| MSI                     | 145       | 0.21%   |
| RTK                     | 118       | 0.17%   |
| Vestel Elektronik       | 110       | 0.16%   |
| CPT                     | 110       | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 343       | 0.47%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 335       | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 306       | 0.42%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 258       | 0.36%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 257       | 0.35%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 245       | 0.34%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 218       | 0.3%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 207       | 0.29%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 187       | 0.26%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 183       | 0.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 167       | 0.23%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 164       | 0.23%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 156       | 0.22%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 146       | 0.2%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 146       | 0.2%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 141       | 0.19%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 140       | 0.19%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 140       | 0.19%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch            | 132       | 0.18%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 129       | 0.18%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 127       | 0.18%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 121       | 0.17%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 119       | 0.16%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 117       | 0.16%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 116       | 0.16%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 112       | 0.15%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 112       | 0.15%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 111       | 0.15%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch     | 110       | 0.15%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 109       | 0.15%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 107       | 0.15%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 106       | 0.15%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 106       | 0.15%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 105       | 0.14%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 104       | 0.14%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 103       | 0.14%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 100       | 0.14%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 97        | 0.13%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 97        | 0.13%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 96        | 0.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 28699     | 42.55%  |
| 1366x768 (WXGA)    | 13354     | 19.8%   |
| 3840x2160 (4K)     | 3806      | 5.64%   |
| 1600x900 (HD+)     | 3146      | 4.66%   |
| 1280x1024 (SXGA)   | 2448      | 3.63%   |
| 2560x1440 (QHD)    | 2329      | 3.45%   |
| 1680x1050 (WSXGA+) | 2004      | 2.97%   |
| 1440x900 (WXGA+)   | 1751      | 2.6%    |
| 1920x1200 (WUXGA)  | 1630      | 2.42%   |
| 1280x800 (WXGA)    | 1504      | 2.23%   |
| Unknown            | 936       | 1.39%   |
| 1360x768           | 612       | 0.91%   |
| 2560x1080          | 529       | 0.78%   |
| 3440x1440          | 493       | 0.73%   |
| 2560x1600          | 471       | 0.7%    |
| 3840x1080          | 383       | 0.57%   |
| 1024x768 (XGA)     | 340       | 0.5%    |
| 1920x540           | 269       | 0.4%    |
| 2880x1800          | 259       | 0.38%   |
| 3840x2400          | 218       | 0.32%   |
| 1600x1200          | 172       | 0.26%   |
| 1024x600           | 169       | 0.25%   |
| 2160x1440          | 165       | 0.24%   |
| 3200x1800 (QHD+)   | 132       | 0.2%    |
| 1280x720 (HD)      | 116       | 0.17%   |
| 2736x1824          | 109       | 0.16%   |
| 3000x2000          | 61        | 0.09%   |
| 1920x1280          | 59        | 0.09%   |
| 3840x1600          | 55        | 0.08%   |
| 1400x1050          | 53        | 0.08%   |
| 3072x1920          | 47        | 0.07%   |
| 2288x1287          | 47        | 0.07%   |
| 2256x1504          | 45        | 0.07%   |
| 4480x1440          | 41        | 0.06%   |
| 3840x1200          | 41        | 0.06%   |
| 2048x1152          | 38        | 0.06%   |
| 3200x2000          | 35        | 0.05%   |
| 1280x960           | 34        | 0.05%   |
| 5760x1080          | 33        | 0.05%   |
| 3200x1080          | 33        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 17748     | 25.39%  |
| 13      | 6505      | 9.31%   |
| 14      | 5345      | 7.65%   |
| 24      | 4622      | 6.61%   |
| Unknown | 4267      | 6.1%    |
| 27      | 4244      | 6.07%   |
| 23      | 4226      | 6.05%   |
| 17      | 4126      | 5.9%    |
| 21      | 3792      | 5.42%   |
| 19      | 2267      | 3.24%   |
| 18      | 1477      | 2.11%   |
| 31      | 1243      | 1.78%   |
| 20      | 1233      | 1.76%   |
| 22      | 1230      | 1.76%   |
| 12      | 1117      | 1.6%    |
| 34      | 818       | 1.17%   |
| 11      | 710       | 1.02%   |
| 16      | 580       | 0.83%   |
| 84      | 507       | 0.73%   |
| 72      | 410       | 0.59%   |
| 40      | 363       | 0.52%   |
| 32      | 363       | 0.52%   |
| 54      | 349       | 0.5%    |
| 10      | 281       | 0.4%    |
| 25      | 237       | 0.34%   |
| 26      | 197       | 0.28%   |
| 28      | 134       | 0.19%   |
| 46      | 119       | 0.17%   |
| 52      | 116       | 0.17%   |
| 48      | 110       | 0.16%   |
| 37      | 110       | 0.16%   |
| 42      | 87        | 0.12%   |
| 65      | 84        | 0.12%   |
| 29      | 72        | 0.1%    |
| 49      | 69        | 0.1%    |
| 43      | 65        | 0.09%   |
| 33      | 64        | 0.09%   |
| 39      | 59        | 0.08%   |
| 36      | 54        | 0.08%   |
| 38      | 38        | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 27265     | 39.53%  |
| 501-600        | 12304     | 17.84%  |
| 401-500        | 8664      | 12.56%  |
| 201-300        | 5323      | 7.72%   |
| 351-400        | 4967      | 7.2%    |
| Unknown        | 4267      | 6.19%   |
| 601-700        | 1965      | 2.85%   |
| 701-800        | 1295      | 1.88%   |
| 1001-1500      | 1065      | 1.54%   |
| 1501-2000      | 993       | 1.44%   |
| 801-900        | 609       | 0.88%   |
| 901-1000       | 182       | 0.26%   |
| 101-200        | 39        | 0.06%   |
| More than 2000 | 26        | 0.04%   |
| 1-100          | 6         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 46987     | 73.89%  |
| 16/10   | 7763      | 12.21%  |
| Unknown | 3754      | 5.9%    |
| 5/4     | 2243      | 3.53%   |
| 21/9    | 972       | 1.53%   |
| 3/2     | 727       | 1.14%   |
| 4/3     | 710       | 1.12%   |
| 32/9    | 156       | 0.25%   |
| 6/5     | 127       | 0.2%    |
| 0.56    | 37        | 0.06%   |
| 1.00    | 30        | 0.05%   |
| 1.96    | 28        | 0.04%   |
| 0.62    | 11        | 0.02%   |
| 3.40    | 8         | 0.01%   |
| 3.20    | 6         | 0.01%   |
| 2.00    | 6         | 0.01%   |
| 3.73    | 5         | 0.01%   |
| 2.12    | 3         | 0.005%  |
| 0.89    | 3         | 0.005%  |
| 11/10   | 2         | 0.003%  |
| 3.76    | 1         | 0.002%  |
| 3.33    | 1         | 0.002%  |
| 2.69    | 1         | 0.002%  |
| 2.50    | 1         | 0.002%  |
| 2.01    | 1         | 0.002%  |
| 0.75    | 1         | 0.002%  |
| 0.67    | 1         | 0.002%  |
| 0.65    | 1         | 0.002%  |
| 0.45    | 1         | 0.002%  |
| 0.00    | 1         | 0.002%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 17623     | 25.4%   |
| 201-250        | 11161     | 16.09%  |
| 81-90          | 9198      | 13.26%  |
| 151-200        | 4676      | 6.74%   |
| 301-350        | 4392      | 6.33%   |
| Unknown        | 4268      | 6.15%   |
| 71-80          | 2691      | 3.88%   |
| 351-500        | 2620      | 3.78%   |
| 121-130        | 2577      | 3.71%   |
| 141-150        | 2276      | 3.28%   |
| More than 1000 | 1826      | 2.63%   |
| 251-300        | 1725      | 2.49%   |
| 501-1000       | 1068      | 1.54%   |
| 61-70          | 961       | 1.39%   |
| 51-60          | 734       | 1.06%   |
| 111-120        | 567       | 0.82%   |
| 131-140        | 535       | 0.77%   |
| 41-50          | 267       | 0.38%   |
| 91-100         | 177       | 0.26%   |
| 1-40           | 42        | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 22214     | 32.83%  |
| 101-120       | 17854     | 26.39%  |
| 121-160       | 16428     | 24.28%  |
| Unknown       | 4267      | 6.31%   |
| 161-240       | 3594      | 5.31%   |
| 1-50          | 1733      | 2.56%   |
| More than 240 | 1575      | 2.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 52971     | 78.54%  |
| 2     | 9511      | 14.1%   |
| 0     | 3835      | 5.69%   |
| 3     | 1041      | 1.54%   |
| 4     | 81        | 0.12%   |
| 5     | 7         | 0.01%   |
| 6     | 2         | 0.003%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 34807     | 35.21%  |
| Intel                             | 31220     | 31.58%  |
| Qualcomm Atheros                  | 11386     | 11.52%  |
| Broadcom                          | 6034      | 6.1%    |
| Ralink Technology                 | 1290      | 1.31%   |
| Broadcom Limited                  | 1254      | 1.27%   |
| Marvell Technology Group          | 1210      | 1.22%   |
| Ralink                            | 1061      | 1.07%   |
| MediaTek                          | 1049      | 1.06%   |
| Nvidia                            | 1024      | 1.04%   |
| TP-Link                           | 1015      | 1.03%   |
| Samsung Electronics               | 478       | 0.48%   |
| ASIX Electronics                  | 462       | 0.47%   |
| Qualcomm Atheros Communications   | 346       | 0.35%   |
| NetGear                           | 346       | 0.35%   |
| Dell                              | 311       | 0.31%   |
| DisplayLink                       | 307       | 0.31%   |
| Xiaomi                            | 274       | 0.28%   |
| D-Link                            | 248       | 0.25%   |
| Huawei Technologies               | 247       | 0.25%   |
| Sierra Wireless                   | 232       | 0.23%   |
| D-Link System                     | 221       | 0.22%   |
| ASUSTek Computer                  | 212       | 0.21%   |
| Ericsson Business Mobile Networks | 211       | 0.21%   |
| Hewlett-Packard                   | 192       | 0.19%   |
| Lenovo                            | 190       | 0.19%   |
| JMicron Technology                | 175       | 0.18%   |
| Microsoft                         | 172       | 0.17%   |
| Aquantia                          | 161       | 0.16%   |
| Edimax Technology                 | 157       | 0.16%   |
| Qualcomm                          | 144       | 0.15%   |
| VIA Technologies                  | 117       | 0.12%   |
| Linksys                           | 114       | 0.12%   |
| Silicon Integrated Systems [SiS]  | 109       | 0.11%   |
| Belkin Components                 | 109       | 0.11%   |
| Motorola PCS                      | 87        | 0.09%   |
| Apple                             | 78        | 0.08%   |
| Arduino SA                        | 72        | 0.07%   |
| IMC Networks                      | 69        | 0.07%   |
| Google                            | 68        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 23539     | 20.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4643      | 4.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2531      | 2.19%   |
| Intel Wi-Fi 6 AX200                                                    | 2079      | 1.8%    |
| Intel Wireless 8265 / 8275                                             | 1839      | 1.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1637      | 1.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1604      | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1510      | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1507      | 1.3%    |
| Intel Wi-Fi 6 AX201                                                    | 1432      | 1.24%   |
| Intel Wireless 7265                                                    | 1343      | 1.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1237      | 1.07%   |
| Intel Wireless 7260                                                    | 1236      | 1.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1191      | 1.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1163      | 1%      |
| Intel I211 Gigabit Network Connection                                  | 1143      | 0.99%   |
| Intel Wireless 8260                                                    | 1055      | 0.91%   |
| Intel Ethernet Connection (2) I219-V                                   | 1009      | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 974       | 0.84%   |
| Realtek RTL8125 2.5GbE Controller                                      | 968       | 0.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 955       | 0.82%   |
| Intel Ethernet Connection I217-LM                                      | 950       | 0.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 935       | 0.81%   |
| Intel Wireless 3165                                                    | 929       | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 906       | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 903       | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 785       | 0.68%   |
| Intel 82579V Gigabit Network Connection                                | 694       | 0.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 683       | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 658       | 0.57%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 655       | 0.57%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 624       | 0.54%   |
| Broadcom BCM43142 802.11b/g/n                                          | 606       | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 580       | 0.5%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 571       | 0.49%   |
| Intel Wireless 3160                                                    | 544       | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 529       | 0.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 516       | 0.45%   |
| Ralink MT7601U Wireless Adapter                                        | 511       | 0.44%   |
| Intel Ethernet Connection (7) I219-V                                   | 509       | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 22595     | 43.36%  |
| Qualcomm Atheros                      | 9066      | 17.4%   |
| Realtek Semiconductor                 | 8557      | 16.42%  |
| Broadcom                              | 3815      | 7.32%   |
| Ralink Technology                     | 1290      | 2.48%   |
| Ralink                                | 1059      | 2.03%   |
| MediaTek                              | 965       | 1.85%   |
| TP-Link                               | 912       | 1.75%   |
| Broadcom Limited                      | 778       | 1.49%   |
| Qualcomm Atheros Communications       | 346       | 0.66%   |
| NetGear                               | 340       | 0.65%   |
| D-Link                                | 239       | 0.46%   |
| Sierra Wireless                       | 232       | 0.45%   |
| ASUSTek Computer                      | 201       | 0.39%   |
| Dell                                  | 182       | 0.35%   |
| Marvell Technology Group              | 163       | 0.31%   |
| Edimax Technology                     | 157       | 0.3%    |
| D-Link System                         | 150       | 0.29%   |
| Microsoft                             | 140       | 0.27%   |
| Belkin Components                     | 106       | 0.2%    |
| Linksys                               | 102       | 0.2%    |
| Qualcomm                              | 85        | 0.16%   |
| IMC Networks                          | 69        | 0.13%   |
| Fibocom                               | 59        | 0.11%   |
| AVM                                   | 52        | 0.1%    |
| Ericsson Business Mobile Networks     | 41        | 0.08%   |
| Hewlett-Packard                       | 40        | 0.08%   |
| Sitecom Europe                        | 32        | 0.06%   |
| ZyDAS                                 | 29        | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 29        | 0.06%   |
| BUFFALO                               | 28        | 0.05%   |
| Gemtek                                | 26        | 0.05%   |
| ZyXEL Communications                  | 25        | 0.05%   |
| Micro Star International              | 21        | 0.04%   |
| Mercucys                              | 18        | 0.03%   |
| Wilocity                              | 14        | 0.03%   |
| Wacom                                 | 11        | 0.02%   |
| TRENDnet                              | 10        | 0.02%   |
| Tenda                                 | 10        | 0.02%   |
| Guillemot                             | 10        | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 2079      | 3.96%   |
| Intel Wireless 8265 / 8275                                     | 1839      | 3.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1637      | 3.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1510      | 2.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1507      | 2.87%   |
| Intel Wi-Fi 6 AX201                                            | 1432      | 2.73%   |
| Intel Wireless 7265                                            | 1343      | 2.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1237      | 2.36%   |
| Intel Wireless 7260                                            | 1236      | 2.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1191      | 2.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1163      | 2.22%   |
| Intel Wireless 8260                                            | 1055      | 2.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 974       | 1.86%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 955       | 1.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 935       | 1.78%   |
| Intel Wireless 3165                                            | 929       | 1.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 906       | 1.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 903       | 1.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 785       | 1.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 683       | 1.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 658       | 1.25%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 655       | 1.25%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 624       | 1.19%   |
| Broadcom BCM43142 802.11b/g/n                                  | 606       | 1.15%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 571       | 1.09%   |
| Intel Wireless 3160                                            | 544       | 1.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 529       | 1.01%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 516       | 0.98%   |
| Ralink MT7601U Wireless Adapter                                | 511       | 0.97%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 472       | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 462       | 0.88%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 441       | 0.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 440       | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 436       | 0.83%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 407       | 0.78%   |
| Intel Centrino Ultimate-N 6300                                 | 401       | 0.76%   |
| Realtek 802.11ac NIC                                           | 400       | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 397       | 0.76%   |
| Intel WiFi Link 5100                                           | 391       | 0.74%   |
| Intel Centrino Advanced-N 6200                                 | 375       | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 31335     | 51.64%  |
| Intel                             | 16609     | 27.37%  |
| Qualcomm Atheros                  | 3398      | 5.6%    |
| Broadcom                          | 3024      | 4.98%   |
| Marvell Technology Group          | 1048      | 1.73%   |
| Nvidia                            | 1018      | 1.68%   |
| Broadcom Limited                  | 500       | 0.82%   |
| Samsung Electronics               | 473       | 0.78%   |
| ASIX Electronics                  | 462       | 0.76%   |
| DisplayLink                       | 307       | 0.51%   |
| Xiaomi                            | 266       | 0.44%   |
| Lenovo                            | 186       | 0.31%   |
| Huawei Technologies               | 181       | 0.3%    |
| JMicron Technology                | 175       | 0.29%   |
| Aquantia                          | 161       | 0.27%   |
| VIA Technologies                  | 114       | 0.19%   |
| Silicon Integrated Systems [SiS]  | 108       | 0.18%   |
| TP-Link                           | 104       | 0.17%   |
| MediaTek                          | 75        | 0.12%   |
| Apple                             | 74        | 0.12%   |
| D-Link System                     | 71        | 0.12%   |
| OPPO Electronics                  | 66        | 0.11%   |
| Google                            | 66        | 0.11%   |
| Motorola PCS                      | 65        | 0.11%   |
| Qualcomm                          | 54        | 0.09%   |
| ICS Advent                        | 54        | 0.09%   |
| Hewlett-Packard                   | 54        | 0.09%   |
| Mellanox Technologies             | 38        | 0.06%   |
| American Megatrends               | 38        | 0.06%   |
| Microchip Technology              | 31        | 0.05%   |
| Microsoft                         | 30        | 0.05%   |
| Attansic Technology               | 30        | 0.05%   |
| 3Com                              | 30        | 0.05%   |
| OnePlus Technology (Shenzhen)     | 28        | 0.05%   |
| IBM                               | 27        | 0.04%   |
| ZTE WCDMA Technologies MSM        | 26        | 0.04%   |
| Dell                              | 20        | 0.03%   |
| HMD Global                        | 19        | 0.03%   |
| Sundance Technology Inc / IC Plus | 18        | 0.03%   |
| LG Electronics                    | 17        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 23539     | 37.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4643      | 7.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2531      | 4.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1604      | 2.58%   |
| Intel I211 Gigabit Network Connection                                  | 1143      | 1.84%   |
| Intel Ethernet Connection (2) I219-V                                   | 1009      | 1.62%   |
| Realtek RTL8125 2.5GbE Controller                                      | 968       | 1.56%   |
| Intel Ethernet Connection I217-LM                                      | 950       | 1.53%   |
| Intel 82579V Gigabit Network Connection                                | 694       | 1.12%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 580       | 0.93%   |
| Intel Ethernet Connection (7) I219-V                                   | 509       | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                                  | 507       | 0.82%   |
| Intel 82577LM Gigabit Network Connection                               | 493       | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                                  | 480       | 0.77%   |
| Intel Ethernet Controller I225-V                                       | 469       | 0.75%   |
| Intel Ethernet Connection I219-LM                                      | 457       | 0.74%   |
| Intel I210 Gigabit Network Connection                                  | 436       | 0.7%    |
| Intel Ethernet Connection I218-LM                                      | 399       | 0.64%   |
| Intel Ethernet Connection I217-V                                       | 386       | 0.62%   |
| Nvidia MCP61 Ethernet                                                  | 377       | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 369       | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                                  | 361       | 0.58%   |
| ASIX AX88179 Gigabit Ethernet                                          | 354       | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 343       | 0.55%   |
| Intel Ethernet Connection (4) I219-V                                   | 340       | 0.55%   |
| Intel Ethernet Connection (6) I219-V                                   | 339       | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 338       | 0.54%   |
| Intel 82574L Gigabit Network Connection                                | 336       | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 334       | 0.54%   |
| Intel Ethernet Connection (3) I218-LM                                  | 333       | 0.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 322       | 0.52%   |
| Intel 82567LM Gigabit Network Connection                               | 309       | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 305       | 0.49%   |
| Intel Ethernet Connection (2) I218-V                                   | 305       | 0.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 294       | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 293       | 0.47%   |
| Intel I350 Gigabit Network Connection                                  | 276       | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 263       | 0.42%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 253       | 0.41%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 252       | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 56956     | 53.01%  |
| WiFi     | 49406     | 45.98%  |
| Modem    | 921       | 0.86%   |
| Unknown  | 168       | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 38833     | 57.04%  |
| Ethernet | 29223     | 42.92%  |
| Unknown  | 22        | 0.03%   |
| Modem    | 4         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 35957     | 54.37%  |
| 1     | 26660     | 40.32%  |
| 0     | 1554      | 2.35%   |
| 3     | 1295      | 1.96%   |
| 4     | 435       | 0.66%   |
| 5     | 84        | 0.13%   |
| 6     | 72        | 0.11%   |
| 8     | 32        | 0.05%   |
| 7     | 15        | 0.02%   |
| 10    | 12        | 0.02%   |
| 12    | 3         | 0.005%  |
| 18    | 2         | 0.003%  |
| 17    | 2         | 0.003%  |
| 13    | 2         | 0.003%  |
| 11    | 2         | 0.003%  |
| 32    | 1         | 0.002%  |
| 9     | 1         | 0.002%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 55883     | 83.36%  |
| Yes     | 11149     | 16.63%  |
| Unknown | 9         | 0.01%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17890     | 47.3%   |
| Realtek Semiconductor           | 3590      | 9.49%   |
| Qualcomm Atheros Communications | 3444      | 9.11%   |
| Cambridge Silicon Radio         | 2067      | 5.46%   |
| Broadcom                        | 1950      | 5.16%   |
| IMC Networks                    | 1465      | 3.87%   |
| Apple                           | 1363      | 3.6%    |
| Lite-On Technology              | 1211      | 3.2%    |
| Foxconn / Hon Hai               | 1191      | 3.15%   |
| ASUSTek Computer                | 612       | 1.62%   |
| Dell                            | 578       | 1.53%   |
| Hewlett-Packard                 | 432       | 1.14%   |
| Toshiba                         | 305       | 0.81%   |
| Ralink                          | 304       | 0.8%    |
| Realtek                         | 267       | 0.71%   |
| MediaTek                        | 165       | 0.44%   |
| Marvell Semiconductor           | 161       | 0.43%   |
| Alps Electric                   | 125       | 0.33%   |
| Foxconn International           | 95        | 0.25%   |
| Ralink Technology               | 70        | 0.19%   |
| TP-Link                         | 64        | 0.17%   |
| Integrated System Solution      | 53        | 0.14%   |
| Belkin Components               | 44        | 0.12%   |
| Dynex                           | 41        | 0.11%   |
| Askey Computer                  | 40        | 0.11%   |
| Micro Star International        | 33        | 0.09%   |
| Edimax Technology               | 32        | 0.08%   |
| USI                             | 27        | 0.07%   |
| Logitech                        | 21        | 0.06%   |
| Chicony Electronics             | 21        | 0.06%   |
| Taiyo Yuden                     | 18        | 0.05%   |
| Smart Modular Technologies      | 17        | 0.04%   |
| Opticis                         | 17        | 0.04%   |
| Qcom                            | 14        | 0.04%   |
| HTC (High Tech Computer)        | 13        | 0.03%   |
| Conwise Technology              | 13        | 0.03%   |
| D-Link System                   | 9         | 0.02%   |
| Primax Electronics              | 7         | 0.02%   |
| Fujitsu                         | 6         | 0.02%   |
| Actions                         | 6         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6774      | 17.9%   |
| Intel AX201 Bluetooth                               | 3251      | 8.59%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2675      | 7.07%   |
| Realtek Bluetooth Radio                             | 2260      | 5.97%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2067      | 5.46%   |
| Intel AX200 Bluetooth                               | 1949      | 5.15%   |
| Qualcomm Atheros  Bluetooth Device                  | 1640      | 4.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1013      | 2.68%   |
| Intel Bluetooth Device                              | 1011      | 2.67%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 659       | 1.74%   |
| Intel Wireless-AC 3168 Bluetooth                    | 645       | 1.7%    |
| Apple Bluetooth Host Controller                     | 579       | 1.53%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 529       | 1.4%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 457       | 1.21%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 451       | 1.19%   |
| IMC Networks Bluetooth Radio                        | 451       | 1.19%   |
| Foxconn / Hon Hai Bluetooth Device                  | 425       | 1.12%   |
| Intel AX210 Bluetooth                               | 413       | 1.09%   |
| IMC Networks Bluetooth Device                       | 404       | 1.07%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 399       | 1.05%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 367       | 0.97%   |
| Lite-On Bluetooth Device                            | 325       | 0.86%   |
| Apple Bluetooth USB Host Controller                 | 323       | 0.85%   |
| IMC Networks Wireless_Device                        | 320       | 0.85%   |
| Ralink RT3290 Bluetooth                             | 304       | 0.8%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 276       | 0.73%   |
| Realtek Bluetooth Radio                             | 267       | 0.71%   |
| Broadcom BCM2045B (BDC-2.1)                         | 267       | 0.71%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 252       | 0.67%   |
| Foxconn / Hon Hai Wireless_Device                   | 251       | 0.66%   |
| HP Broadcom 2070 Bluetooth Combo                    | 250       | 0.66%   |
| Lite-On Atheros AR3012 Bluetooth                    | 238       | 0.63%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 233       | 0.62%   |
| Dell DW375 Bluetooth Module                         | 190       | 0.5%    |
| Apple Bluetooth HCI                                 | 184       | 0.49%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 178       | 0.47%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 168       | 0.44%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 162       | 0.43%   |
| Realtek RTL8723B Bluetooth                          | 152       | 0.4%    |
| Qualcomm Atheros Bluetooth USB Host Controller      | 152       | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 48764     | 55.89%  |
| AMD                              | 16619     | 19.05%  |
| Nvidia                           | 14645     | 16.78%  |
| C-Media Electronics              | 1132      | 1.3%    |
| Logitech                         | 601       | 0.69%   |
| Creative Labs                    | 481       | 0.55%   |
| GN Netcom                        | 313       | 0.36%   |
| Realtek Semiconductor            | 302       | 0.35%   |
| Texas Instruments                | 235       | 0.27%   |
| Plantronics                      | 214       | 0.25%   |
| JMTek                            | 203       | 0.23%   |
| Generalplus Technology           | 199       | 0.23%   |
| ASUSTek Computer                 | 179       | 0.21%   |
| Lenovo                           | 174       | 0.2%    |
| VIA Technologies                 | 165       | 0.19%   |
| Creative Technology              | 152       | 0.17%   |
| Kingston Technology              | 147       | 0.17%   |
| Focusrite-Novation               | 132       | 0.15%   |
| Apple                            | 131       | 0.15%   |
| Silicon Integrated Systems [SiS] | 123       | 0.14%   |
| Corsair                          | 122       | 0.14%   |
| Razer USA                        | 116       | 0.13%   |
| Hewlett-Packard                  | 111       | 0.13%   |
| SteelSeries ApS                  | 95        | 0.11%   |
| Micro Star International         | 75        | 0.09%   |
| Tenx Technology                  | 72        | 0.08%   |
| Sennheiser Communications        | 67        | 0.08%   |
| Blue Microphones                 | 59        | 0.07%   |
| Microsoft                        | 58        | 0.07%   |
| Dell                             | 58        | 0.07%   |
| M-Audio                          | 47        | 0.05%   |
| BEHRINGER International          | 39        | 0.04%   |
| Samson Technologies              | 38        | 0.04%   |
| DSEA A/S                         | 38        | 0.04%   |
| Sony                             | 37        | 0.04%   |
| XMOS                             | 33        | 0.04%   |
| GYROCOM C&C                      | 33        | 0.04%   |
| Conexant Systems                 | 31        | 0.04%   |
| Giga-Byte Technology             | 30        | 0.03%   |
| Cambridge Silicon Radio          | 29        | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 5343      | 5.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4837      | 4.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4661      | 4.54%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4157      | 4.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3260      | 3.18%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2647      | 2.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2526      | 2.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2480      | 2.42%   |
| Intel Cannon Lake PCH cAVS                                                 | 2477      | 2.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2067      | 2.01%   |
| AMD FCH Azalia Controller                                                  | 2067      | 2.01%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1966      | 1.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1847      | 1.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1841      | 1.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1749      | 1.7%    |
| Intel 8 Series HD Audio Controller                                         | 1699      | 1.66%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1696      | 1.65%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1648      | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1595      | 1.55%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1524      | 1.49%   |
| Intel Broadwell-U Audio Controller                                         | 1425      | 1.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1381      | 1.35%   |
| Intel 200 Series PCH HD Audio                                              | 1280      | 1.25%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1264      | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1173      | 1.14%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1108      | 1.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1107      | 1.08%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1011      | 0.99%   |
| AMD Kabini HDMI/DP Audio                                                   | 996       | 0.97%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 950       | 0.93%   |
| Nvidia High Definition Audio Controller                                    | 920       | 0.9%    |
| Nvidia GF108 High Definition Audio Controller                              | 908       | 0.88%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 819       | 0.8%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 804       | 0.78%   |
| Intel Comet Lake PCH cAVS                                                  | 801       | 0.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 783       | 0.76%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 781       | 0.76%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 775       | 0.76%   |
| Nvidia GP106 High Definition Audio Controller                              | 723       | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 698       | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7642      | 23.75%  |
| SK hynix            | 6130      | 19.05%  |
| Kingston            | 3630      | 11.28%  |
| Micron Technology   | 3403      | 10.58%  |
| Unknown             | 2478      | 7.7%    |
| Crucial             | 1813      | 5.63%   |
| Corsair             | 1658      | 5.15%   |
| G.Skill             | 976       | 3.03%   |
| A-DATA Technology   | 675       | 2.1%    |
| Ramaxel Technology  | 510       | 1.59%   |
| Elpida              | 369       | 1.15%   |
| Nanya Technology    | 325       | 1.01%   |
| Unknown (ABCD)      | 275       | 0.85%   |
| Team                | 210       | 0.65%   |
| Unknown             | 207       | 0.64%   |
| Smart               | 198       | 0.62%   |
| Patriot             | 177       | 0.55%   |
| Transcend           | 163       | 0.51%   |
| GOODRAM             | 89        | 0.28%   |
| Apacer              | 72        | 0.22%   |
| Teikon              | 57        | 0.18%   |
| PNY                 | 52        | 0.16%   |
| Hewlett-Packard     | 49        | 0.15%   |
| ASint Technology    | 41        | 0.13%   |
| Silicon Power       | 40        | 0.12%   |
| Avant               | 40        | 0.12%   |
| Smart Brazil        | 33        | 0.1%    |
| Goldkey             | 30        | 0.09%   |
| AMD                 | 30        | 0.09%   |
| Qimonda             | 25        | 0.08%   |
| Neo Forza           | 24        | 0.07%   |
| Unifosa             | 23        | 0.07%   |
| GeIL                | 22        | 0.07%   |
| Timetec             | 21        | 0.07%   |
| ChangXin Memory     | 21        | 0.07%   |
| Innodisk            | 20        | 0.06%   |
| CSX                 | 20        | 0.06%   |
| Lexar               | 19        | 0.06%   |
| High Bridge         | 18        | 0.06%   |
| SHARETRONIC         | 14        | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 329       | 0.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 280       | 0.81%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 266       | 0.77%   |
| Unknown                                                             | 207       | 0.6%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 203       | 0.59%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 195       | 0.57%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 191       | 0.55%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 189       | 0.55%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 181       | 0.53%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 177       | 0.51%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 176       | 0.51%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 175       | 0.51%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 172       | 0.5%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 172       | 0.5%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 168       | 0.49%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 157       | 0.46%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 156       | 0.45%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 155       | 0.45%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 146       | 0.42%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 144       | 0.42%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 139       | 0.4%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 136       | 0.4%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 135       | 0.39%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 133       | 0.39%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 132       | 0.38%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 132       | 0.38%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 132       | 0.38%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 128       | 0.37%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 128       | 0.37%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 123       | 0.36%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 122       | 0.35%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 119       | 0.35%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 116       | 0.34%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 112       | 0.33%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 109       | 0.32%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 109       | 0.32%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 106       | 0.31%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 104       | 0.3%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 102       | 0.3%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 101       | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind            | Computers | Percent |
|-----------------|-----------|---------|
| DDR4            | 14080     | 50.31%  |
| DDR3            | 8484      | 30.32%  |
| LPDDR4          | 1243      | 4.44%   |
| DDR2            | 970       | 3.47%   |
| LPDDR3          | 895       | 3.2%    |
| Unknown         | 666       | 2.38%   |
| SDRAM           | 606       | 2.17%   |
| DDR5            | 550       | 1.97%   |
| LPDDR5          | 274       | 0.98%   |
| DDR             | 146       | 0.52%   |
| DRAM            | 66        | 0.24%   |
| EEPROM          | 2         | 0.01%   |
| Logical non-vol | 1         | 0.004%  |
| DDR2 FB-DIMM    | 1         | 0.004%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 15896     | 57.09%  |
| DIMM            | 9145      | 32.85%  |
| Row Of Chips    | 2480      | 8.91%   |
| Chip            | 137       | 0.49%   |
| Unknown         | 93        | 0.33%   |
| FB-DIMM         | 46        | 0.17%   |
| RIMM            | 40        | 0.14%   |
| Proprietary Car | 5         | 0.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 11818     | 38.93%  |
| 4096    | 7921      | 26.09%  |
| 16384   | 5363      | 17.66%  |
| 2048    | 3147      | 10.37%  |
| 32768   | 1210      | 3.99%   |
| 1024    | 729       | 2.4%    |
| 512     | 85        | 0.28%   |
| 65536   | 48        | 0.16%   |
| 256     | 12        | 0.04%   |
| 49152   | 6         | 0.02%   |
| 1536    | 5         | 0.02%   |
| 6144    | 4         | 0.01%   |
| 131072  | 2         | 0.01%   |
| 129408  | 2         | 0.01%   |
| 12288   | 2         | 0.01%   |
| 1       | 2         | 0.01%   |
| Unknown | 2         | 0.01%   |
| 258496  | 1         | 0.003%  |
| 64      | 1         | 0.003%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 5435      | 18.04%  |
| 2667    | 5038      | 16.72%  |
| 3200    | 4845      | 16.08%  |
| 2400    | 2297      | 7.63%   |
| 1333    | 1975      | 6.56%   |
| 2133    | 1795      | 5.96%   |
| 1334    | 782       | 2.6%    |
| 3600    | 585       | 1.94%   |
| 1867    | 579       | 1.92%   |
| 4267    | 556       | 1.85%   |
| 667     | 495       | 1.64%   |
| 800     | 488       | 1.62%   |
| Unknown | 419       | 1.39%   |
| 4800    | 402       | 1.33%   |
| 1067    | 314       | 1.04%   |
| 3266    | 300       | 1%      |
| 6400    | 283       | 0.94%   |
| 1066    | 247       | 0.82%   |
| 3733    | 210       | 0.7%    |
| 2666    | 210       | 0.7%    |
| 2933    | 178       | 0.59%   |
| 3000    | 177       | 0.59%   |
| 1866    | 175       | 0.58%   |
| 1800    | 164       | 0.54%   |
| 4199    | 135       | 0.45%   |
| 3400    | 131       | 0.43%   |
| 8400    | 130       | 0.43%   |
| 3800    | 128       | 0.42%   |
| 2048    | 103       | 0.34%   |
| 4266    | 90        | 0.3%    |
| 3866    | 86        | 0.29%   |
| 533     | 86        | 0.29%   |
| 3533    | 83        | 0.28%   |
| 3466    | 80        | 0.27%   |
| 5600    | 76        | 0.25%   |
| 400     | 70        | 0.23%   |
| 975     | 68        | 0.23%   |
| 2800    | 64        | 0.21%   |
| 3066    | 54        | 0.18%   |
| 3666    | 41        | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Hewlett-Packard                    | 649       | 34.95%  |
| Brother Industries                 | 320       | 17.23%  |
| Canon                              | 301       | 16.21%  |
| Samsung Electronics                | 211       | 11.36%  |
| Seiko Epson                        | 161       | 8.67%   |
| Prolific Technology                | 34        | 1.83%   |
| Lexmark International              | 23        | 1.24%   |
| Dymo-CoStar                        | 23        | 1.24%   |
| QinHeng Electronics                | 19        | 1.02%   |
| Xerox                              | 17        | 0.92%   |
| Kyocera                            | 13        | 0.7%    |
| Pantum                             | 11        | 0.59%   |
| Oki Data                           | 10        | 0.54%   |
| Zebra                              | 9         | 0.48%   |
| STMicroelectronics                 | 8         | 0.43%   |
| Ricoh                              | 8         | 0.43%   |
| Dell                               | 8         | 0.43%   |
| Fuji Xerox                         | 4         | 0.22%   |
| Citizen                            | 4         | 0.22%   |
| Apple                              | 3         | 0.16%   |
| TSC Auto ID Technology             | 2         | 0.11%   |
| SAT                                | 2         | 0.11%   |
| Konica Minolta                     | 2         | 0.11%   |
| ATEN International                 | 2         | 0.11%   |
| Zhuhai Poskey Technology           | 1         | 0.05%   |
| Xiaomi                             | 1         | 0.05%   |
| Star Micronics                     | 1         | 0.05%   |
| Panasonic (Matsushita)             | 1         | 0.05%   |
| MIIIW                              | 1         | 0.05%   |
| GODEX INTERNATIONAL                | 1         | 0.05%   |
| GCC                                | 1         | 0.05%   |
| Datamax-O'Neil                     | 1         | 0.05%   |
| Custom Engineering SPA             | 1         | 0.05%   |
| BIXOLON                            | 1         | 0.05%   |
| BeiJing LanXum Computer Technology | 1         | 0.05%   |
| ARGOX                              | 1         | 0.05%   |
| Unknown                            | 1         | 0.05%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port        | 34        | 1.8%    |
| HP DeskJet 2600 series               | 30        | 1.59%   |
| Samsung M2020 Series                 | 23        | 1.22%   |
| Canon PIXMA MG2500 Series            | 22        | 1.17%   |
| Brother Printer                      | 21        | 1.11%   |
| HP LaserJet 1020                     | 20        | 1.06%   |
| QinHeng CH340S                       | 19        | 1.01%   |
| HP ENVY 4520 series                  | 19        | 1.01%   |
| HP Deskjet 2540 series               | 19        | 1.01%   |
| Brother HL-2030 Laser Printer        | 19        | 1.01%   |
| HP DeskJet 3700 series               | 18        | 0.96%   |
| HP DeskJet 2130 series               | 17        | 0.9%    |
| Canon PIXMA MX920 Series             | 17        | 0.9%    |
| Samsung M2070 Series                 | 16        | 0.85%   |
| HP LaserJet 1018                     | 16        | 0.85%   |
| Canon PIXMA MG3600 Series            | 16        | 0.85%   |
| Samsung ML-216x Series Laser Printer | 15        | 0.8%    |
| HP DeskJet 3630 series               | 15        | 0.8%    |
| HP LaserJet 3050                     | 14        | 0.74%   |
| HP OfficeJet 3830 series             | 11        | 0.58%   |
| HP LaserJet Professional P1102w      | 11        | 0.58%   |
| HP ENVY 5000 series                  | 11        | 0.58%   |
| HP Deskjet 1050 J410                 | 11        | 0.58%   |
| Canon CanoScan LiDE 300              | 11        | 0.58%   |
| Seiko Epson Printer                  | 10        | 0.53%   |
| Samsung SCX-3400 Series              | 10        | 0.53%   |
| Samsung C48x Series                  | 10        | 0.53%   |
| HP Printing Support                  | 10        | 0.53%   |
| HP ENVY 5540 series                  | 10        | 0.53%   |
| HP DeskJet 2700 series               | 10        | 0.53%   |
| HP Deskjet 2050 J510                 | 10        | 0.53%   |
| Samsung M267x 287x Series            | 9         | 0.48%   |
| Samsung Composite Device             | 9         | 0.48%   |
| Oki Data USB Device                  | 9         | 0.48%   |
| HP LaserJet P1005                    | 9         | 0.48%   |
| Dymo-CoStar LabelWriter 400          | 9         | 0.48%   |
| Canon iP7200 series                  | 9         | 0.48%   |
| Seiko Epson L360 Series              | 8         | 0.42%   |
| Seiko Epson L3150 Series             | 8         | 0.42%   |
| HP Deskjet 3050A                     | 8         | 0.42%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 232       | 60.42%  |
| Seiko Epson                                    | 78        | 20.31%  |
| Hewlett-Packard                                | 43        | 11.2%   |
| Mustek Systems                                 | 9         | 2.34%   |
| Ultima Electronics                             | 6         | 1.56%   |
| Plustek                                        | 5         | 1.3%    |
| AGFA-Gevaert NV                                | 2         | 0.52%   |
| Acer Peripherals (now BenQ)                    | 2         | 0.52%   |
| UMAX                                           | 1         | 0.26%   |
| Syscan                                         | 1         | 0.26%   |
| Siemens Information and Communication Products | 1         | 0.26%   |
| Nikon                                          | 1         | 0.26%   |
| Minolta                                        | 1         | 0.26%   |
| Microtek International                         | 1         | 0.26%   |
| KYE Systems (Mouse Systems)                    | 1         | 0.26%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 35        | 9.07%   |
| Canon CanoScan LiDE 210                                                               | 30        | 7.77%   |
| Canon CanoScan LiDE 220                                                               | 25        | 6.48%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 22        | 5.7%    |
| Canon CanoScan LIDE 25                                                                | 22        | 5.7%    |
| Canon CanoScan LiDE 120                                                               | 15        | 3.89%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 14        | 3.63%   |
| Canon CanoScan LiDE 100                                                               | 14        | 3.63%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 9         | 2.33%   |
| Canon CanoScan LiDE 200                                                               | 9         | 2.33%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 8         | 2.07%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 7         | 1.81%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 7         | 1.81%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 5         | 1.3%    |
| Seiko Epson Scanner                                                                   | 5         | 1.3%    |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                               | 5         | 1.3%    |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 5         | 1.3%    |
| Canon CanoScan 9000F Mark II                                                          | 5         | 1.3%    |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 4         | 1.04%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 4         | 1.04%   |
| Canon CanoScan LiDE 60                                                                | 4         | 1.04%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 3         | 0.78%   |
| Seiko Epson GT-F700 [Perfection V350]                                                 | 3         | 0.78%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 3         | 0.78%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 3         | 0.78%   |
| Mustek Systems SNAPSCAN e22                                                           | 3         | 0.78%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 3         | 0.78%   |
| HP ScanJet G4050                                                                      | 3         | 0.78%   |
| HP ScanJet 3970c                                                                      | 3         | 0.78%   |
| HP ScanJet 3300c                                                                      | 3         | 0.78%   |
| Canon CanoScan LiDE 700F                                                              | 3         | 0.78%   |
| Canon CanoScan LiDE 600F                                                              | 3         | 0.78%   |
| Canon CanoScan 8800F                                                                  | 3         | 0.78%   |
| Canon CanoScan 4400F                                                                  | 3         | 0.78%   |
| Canon CanoScan 4200F                                                                  | 3         | 0.78%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 2         | 0.52%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 2         | 0.52%   |
| Seiko Epson ES-D200 [GT-S50]                                                          | 2         | 0.52%   |
| Plustek 600dpi USB Scanner                                                            | 2         | 0.52%   |
| Mustek Systems BearPaw 2448 CU Pro                                                    | 2         | 0.52%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8203      | 21.09%  |
| Microdia                               | 3772      | 9.7%    |
| IMC Networks                           | 3274      | 8.42%   |
| Realtek Semiconductor                  | 3267      | 8.4%    |
| Sunplus Innovation Technology          | 2247      | 5.78%   |
| Logitech                               | 1932      | 4.97%   |
| Bison Electronics                      | 1807      | 4.65%   |
| Quanta                                 | 1706      | 4.39%   |
| Cheng Uei Precision Industry (Foxlink) | 1537      | 3.95%   |
| Apple                                  | 1367      | 3.51%   |
| Suyin                                  | 1256      | 3.23%   |
| Acer                                   | 883       | 2.27%   |
| Lite-On Technology                     | 873       | 2.24%   |
| Syntek                                 | 849       | 2.18%   |
| Silicon Motion                         | 568       | 1.46%   |
| Alcor Micro                            | 489       | 1.26%   |
| Luxvisions Innotech Limited            | 483       | 1.24%   |
| Samsung Electronics                    | 439       | 1.13%   |
| Microsoft                              | 393       | 1.01%   |
| Ricoh                                  | 382       | 0.98%   |
| Z-Star Microelectronics                | 232       | 0.6%    |
| Lenovo                                 | 221       | 0.57%   |
| Sonix Technology                       | 172       | 0.44%   |
| Importek                               | 142       | 0.37%   |
| Generalplus Technology                 | 129       | 0.33%   |
| Primax Electronics                     | 121       | 0.31%   |
| ALi                                    | 111       | 0.29%   |
| GEMBIRD                                | 89        | 0.23%   |
| SunplusIT                              | 88        | 0.23%   |
| Creative Technology                    | 88        | 0.23%   |
| ARC International                      | 88        | 0.23%   |
| OmniVision Technologies                | 87        | 0.22%   |
| Cubeternet                             | 77        | 0.2%    |
| KYE Systems (Mouse Systems)            | 61        | 0.16%   |
| Jieli Technology                       | 60        | 0.15%   |
| DigiTech                               | 58        | 0.15%   |
| Sunplus Technology                     | 57        | 0.15%   |
| Intel                                  | 53        | 0.14%   |
| USB Camera                             | 51        | 0.13%   |
| MacroSilicon                           | 46        | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD           | 1687      | 4.31%   |
| Chicony Integrated Camera               | 1416      | 3.61%   |
| Realtek Integrated_Webcam_HD            | 1316      | 3.36%   |
| IMC Networks Integrated Camera          | 847       | 2.16%   |
| IMC Networks USB2.0 HD UVC WebCam       | 788       | 2.01%   |
| Chicony HD WebCam                       | 745       | 1.9%    |
| Sunplus Integrated_Webcam_HD            | 632       | 1.61%   |
| Bison Integrated Camera                 | 548       | 1.4%    |
| Syntek Integrated Camera                | 461       | 1.18%   |
| Logitech Webcam C270                    | 443       | 1.13%   |
| Samsung Galaxy series, misc. (MTP mode) | 432       | 1.1%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 432       | 1.1%    |
| Realtek USB Camera                      | 385       | 0.98%   |
| Chicony HP HD Camera                    | 374       | 0.95%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 366       | 0.93%   |
| Apple Built-in iSight                   | 364       | 0.93%   |
| Apple FaceTime HD Camera (Built-in)     | 315       | 0.8%    |
| Logitech HD Pro Webcam C920             | 307       | 0.78%   |
| Microdia Integrated Webcam              | 296       | 0.76%   |
| Chicony HP Truevision HD                | 275       | 0.7%    |
| Sunplus HD WebCam                       | 272       | 0.69%   |
| Lite-On Integrated Camera               | 272       | 0.69%   |
| Chicony HP Truevision HD camera         | 263       | 0.67%   |
| Chicony TOSHIBA Web Camera - HD         | 262       | 0.67%   |
| Bison Lenovo EasyCamera                 | 260       | 0.66%   |
| Chicony USB2.0 HD UVC WebCam            | 251       | 0.64%   |
| Quanta HD User Facing                   | 245       | 0.63%   |
| Chicony EasyCamera                      | 244       | 0.62%   |
| Chicony USB 2.0 Camera                  | 243       | 0.62%   |
| Quanta HP TrueVision HD Camera          | 242       | 0.62%   |
| Chicony HP Wide Vision HD Camera        | 219       | 0.56%   |
| Chicony USB2.0 VGA UVC WebCam           | 217       | 0.55%   |
| Quanta HP HD Camera                     | 216       | 0.55%   |
| Microdia Laptop_Integrated_Webcam_HD    | 216       | 0.55%   |
| Realtek Integrated Webcam               | 213       | 0.54%   |
| Acer SunplusIT Integrated Camera        | 209       | 0.53%   |
| Alcor Micro USB 2.0 Camera              | 206       | 0.53%   |
| Lite-On HP HD Camera                    | 203       | 0.52%   |
| Chicony Lenovo EasyCamera               | 199       | 0.51%   |
| Chicony USB2.0 Camera                   | 198       | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 2687      | 34.59%  |
| Synaptics                          | 2059      | 26.51%  |
| Shenzhen Goodix Technology         | 1214      | 15.63%  |
| AuthenTec                          | 450       | 5.79%   |
| Elan Microelectronics              | 447       | 5.75%   |
| Upek                               | 390       | 5.02%   |
| LighTuning Technology              | 321       | 4.13%   |
| STMicroelectronics                 | 83        | 1.07%   |
| Realtek USB2.0 Finger Print Bridge | 42        | 0.54%   |
| Samsung Electronics                | 28        | 0.36%   |
| Focal-systems.Corp                 | 23        | 0.3%    |
| HOLTEK                             | 6         | 0.08%   |
| DigitalPersona                     | 4         | 0.05%   |
| Dell                               | 4         | 0.05%   |
| Microsoft                          | 3         | 0.04%   |
| GDMicroelectronics                 | 3         | 0.04%   |
| Futronic Technology                | 2         | 0.03%   |
| Suprema                            | 1         | 0.01%   |
| FocalTech                          | 1         | 0.01%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 666       | 8.57%   |
| Shenzhen Goodix  FingerPrint Device                                        | 652       | 8.39%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 491       | 6.32%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 364       | 4.69%   |
| Shenzhen Goodix Fingerprint Reader                                         | 358       | 4.61%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 275       | 3.54%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 256       | 3.3%    |
| Elan ELAN:Fingerprint                                                      | 229       | 2.95%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 222       | 2.86%   |
| Shenzhen Goodix FingerPrint                                                | 204       | 2.63%   |
| Validity Sensors Synaptics WBDI                                            | 200       | 2.57%   |
| Elan ELAN:ARM-M4                                                           | 200       | 2.57%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 197       | 2.54%   |
| Validity Sensors VFS491                                                    | 187       | 2.41%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 183       | 2.36%   |
| Synaptics  WBDI                                                            | 179       | 2.3%    |
| Synaptics WBDI                                                             | 160       | 2.06%   |
| AuthenTec AES2810                                                          | 151       | 1.94%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 146       | 1.88%   |
| Validity Sensors Fingerprint scanner                                       | 144       | 1.85%   |
| Synaptics Fingerprint reader [HP G6]                                       | 144       | 1.85%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 137       | 1.76%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 135       | 1.74%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 131       | 1.69%   |
| Synaptics UWP WBDI                                                         | 130       | 1.67%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 125       | 1.61%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 119       | 1.53%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 114       | 1.47%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 110       | 1.42%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 94        | 1.21%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 85        | 1.09%   |
| STMicroelectronics Fingerprint Reader                                      | 83        | 1.07%   |
| AuthenTec Fingerprint Sensor                                               | 77        | 0.99%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 73        | 0.94%   |
| AuthenTec AES1600                                                          | 60        | 0.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 57        | 0.73%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 56        | 0.72%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 52        | 0.67%   |
| Validity Sensors VFS Fingerprint sensor                                    | 44        | 0.57%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 42        | 0.54%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 1591      | 50.33%  |
| Alcor Micro                       | 760       | 24.04%  |
| O2 Micro                          | 219       | 6.93%   |
| Upek                              | 151       | 4.78%   |
| Lenovo                            | 150       | 4.75%   |
| Gemalto (was Gemplus)             | 58        | 1.83%   |
| Advanced Card Systems             | 41        | 1.3%    |
| SCM Microsystems                  | 38        | 1.2%    |
| OmniKey                           | 19        | 0.6%    |
| Realtek Semiconductor             | 15        | 0.47%   |
| Chicony Electronics               | 11        | 0.35%   |
| Cherry                            | 11        | 0.35%   |
| Bit4id                            | 11        | 0.35%   |
| Aladdin Knowledge Systems         | 11        | 0.35%   |
| Yubico.com                        | 10        | 0.32%   |
| Reiner SCT Kartensysteme          | 10        | 0.32%   |
| Giesecke & Devrient               | 10        | 0.32%   |
| VASCO Data Security International | 9         | 0.28%   |
| Hewlett-Packard                   | 6         | 0.19%   |
| Fujitsu Siemens Computers         | 6         | 0.19%   |
| Watchdata                         | 5         | 0.16%   |
| NXP Semiconductors                | 3         | 0.09%   |
| C3PO                              | 3         | 0.09%   |
| Aladdin R.D.                      | 3         | 0.09%   |
| Clay Logic                        | 2         | 0.06%   |
| Athena Smartcard Solutions        | 2         | 0.06%   |
| Aktiv                             | 2         | 0.06%   |
| SpringCard                        | 1         | 0.03%   |
| Kobil Systems                     | 1         | 0.03%   |
| Integrated Technology Express     | 1         | 0.03%   |
| Feitian Technologies              | 1         | 0.03%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 750       | 23.7%   |
| Broadcom BCM5880 Secure Applications Processor                               | 550       | 17.38%  |
| Broadcom 58200                                                               | 415       | 13.12%  |
| Broadcom 5880                                                                | 368       | 11.63%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 250       | 7.9%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 194       | 6.13%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 151       | 4.77%   |
| Lenovo Integrated Smart Card Reader                                          | 148       | 4.68%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 38        | 1.2%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 26        | 0.82%   |
| O2 Micro Oz776 SmartCard Reader                                              | 25        | 0.79%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 20        | 0.63%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 16        | 0.51%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 15        | 0.47%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 11        | 0.35%   |
| Aladdin Knowledge Systems Token JC                                           | 11        | 0.35%   |
| Advanced Card Systems ACR122U                                                | 11        | 0.35%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 10        | 0.32%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 10        | 0.32%   |
| Bit4id miniLector EVO                                                        | 10        | 0.32%   |
| Alcor Micro Watchdata W 1981                                                 | 10        | 0.32%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 7         | 0.22%   |
| OmniKey CardMan 3021 / 3121                                                  | 6         | 0.19%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 6         | 0.19%   |
| Giesecke & Devrient StarSign CUT S                                           | 6         | 0.19%   |
| Watchdata USB Key                                                            | 5         | 0.16%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 5         | 0.16%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 5         | 0.16%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 5         | 0.16%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 5         | 0.16%   |
| VASCO Data Security International DIGIPASS 870                               | 4         | 0.13%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 4         | 0.13%   |
| Giesecke & Devrient StarSign CUT                                             | 4         | 0.13%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 4         | 0.13%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 4         | 0.13%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 3         | 0.09%   |
| OmniKey CardMan 4321                                                         | 3         | 0.09%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 3         | 0.09%   |
| OmniKey 3x21 Smart Card Reader                                               | 3         | 0.09%   |
| NXP Semiconductors PR533                                                     | 3         | 0.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 46206     | 68.66%  |
| 1     | 16977     | 25.23%  |
| 2     | 3155      | 4.69%   |
| 3     | 561       | 0.83%   |
| 4     | 223       | 0.33%   |
| 5     | 79        | 0.12%   |
| 6     | 45        | 0.07%   |
| 7     | 21        | 0.03%   |
| 8     | 17        | 0.03%   |
| 9     | 7         | 0.01%   |
| 10    | 4         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 7659      | 30.22%  |
| Graphics card            | 5862      | 23.13%  |
| Net/wireless             | 3220      | 12.71%  |
| Chipcard                 | 2953      | 11.65%  |
| Communication controller | 1140      | 4.5%    |
| Multimedia controller    | 889       | 3.51%   |
| Unassigned class         | 750       | 2.96%   |
| Camera                   | 584       | 2.3%    |
| Bluetooth                | 536       | 2.12%   |
| Sound                    | 461       | 1.82%   |
| Storage                  | 380       | 1.5%    |
| Net/ethernet             | 241       | 0.95%   |
| Card reader              | 226       | 0.89%   |
| Network                  | 100       | 0.39%   |
| Modem                    | 92        | 0.36%   |
| Storage/raid             | 87        | 0.34%   |
| Flash memory             | 49        | 0.19%   |
| Dvb card                 | 43        | 0.17%   |
| Storage/ata              | 13        | 0.05%   |
| Storage/nvme             | 12        | 0.05%   |
| Tv card                  | 11        | 0.04%   |
| Storage/ide              | 11        | 0.04%   |
| Firewire controller      | 11        | 0.04%   |
| Video                    | 7         | 0.03%   |
| Wireless                 | 4         | 0.02%   |
| Unclassified device      | 1         | 0.004%  |

