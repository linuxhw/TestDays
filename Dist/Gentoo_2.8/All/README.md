Gentoo 2.8 - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Gentoo 2.8.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Gentoo_2.8/Desktop/README.md) and [notebooks](/Dist/Gentoo_2.8/Notebook/README.md).

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

Total: 329

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [21392e76a8](https://linux-hardware.org/?probe=21392e76a8) | Sep 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [e16313490d](https://linux-hardware.org/?probe=e16313490d) | Sep 01, 2022 |
| Toshiba       | Satellite C850D-118         | Notebook    | [1950f0aeac](https://linux-hardware.org/?probe=1950f0aeac) | Aug 31, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d146908413](https://linux-hardware.org/?probe=d146908413) | Aug 31, 2022 |
| Toshiba       | Satellite C850D-118         | Notebook    | [07000e4194](https://linux-hardware.org/?probe=07000e4194) | Aug 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS33R0J     | Notebook    | [72f6962ac8](https://linux-hardware.org/?probe=72f6962ac8) | Aug 30, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [e915bb3a8c](https://linux-hardware.org/?probe=e915bb3a8c) | Aug 29, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [5a51c31ac9](https://linux-hardware.org/?probe=5a51c31ac9) | Aug 29, 2022 |
| Eluktronic... | MAX-17                      | Notebook    | [627ecbeb36](https://linux-hardware.org/?probe=627ecbeb36) | Aug 29, 2022 |
| Dell          | Precision 3570              | Notebook    | [7f7a44c923](https://linux-hardware.org/?probe=7f7a44c923) | Aug 29, 2022 |
| Timi          | A35                         | Notebook    | [df50ea1876](https://linux-hardware.org/?probe=df50ea1876) | Aug 29, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [499889da7e](https://linux-hardware.org/?probe=499889da7e) | Aug 28, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [489691c2e3](https://linux-hardware.org/?probe=489691c2e3) | Aug 28, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [f30320f76e](https://linux-hardware.org/?probe=f30320f76e) | Aug 27, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [a1b7c5d6ab](https://linux-hardware.org/?probe=a1b7c5d6ab) | Aug 27, 2022 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | Desktop     | [7e810b23be](https://linux-hardware.org/?probe=7e810b23be) | Aug 26, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [cf7da7df12](https://linux-hardware.org/?probe=cf7da7df12) | Aug 26, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [76db86107b](https://linux-hardware.org/?probe=76db86107b) | Aug 26, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | Notebook    | [416e5db831](https://linux-hardware.org/?probe=416e5db831) | Aug 26, 2022 |
| Lenovo        | ThinkPad Yoga 460 20EMCT... | Convertible | [73c79e8944](https://linux-hardware.org/?probe=73c79e8944) | Aug 25, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [8a23dbfd36](https://linux-hardware.org/?probe=8a23dbfd36) | Aug 25, 2022 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [294fe7d6c8](https://linux-hardware.org/?probe=294fe7d6c8) | Aug 24, 2022 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [2952e542e1](https://linux-hardware.org/?probe=2952e542e1) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0df091061c](https://linux-hardware.org/?probe=0df091061c) | Aug 24, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [6d0a3e71d7](https://linux-hardware.org/?probe=6d0a3e71d7) | Aug 24, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d22f756c4c](https://linux-hardware.org/?probe=d22f756c4c) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0c80683e2a](https://linux-hardware.org/?probe=0c80683e2a) | Aug 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f38202db0d](https://linux-hardware.org/?probe=f38202db0d) | Aug 21, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [8445aa0041](https://linux-hardware.org/?probe=8445aa0041) | Aug 20, 2022 |
| Timi          | A35                         | Notebook    | [cf89c68d08](https://linux-hardware.org/?probe=cf89c68d08) | Aug 19, 2022 |
| IBM           | 2722BDG                     | Notebook    | [e0fe2162a3](https://linux-hardware.org/?probe=e0fe2162a3) | Aug 18, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1ea309e90c](https://linux-hardware.org/?probe=1ea309e90c) | Aug 17, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [80760b8e4b](https://linux-hardware.org/?probe=80760b8e4b) | Aug 16, 2022 |
| Dell          | G3 3500                     | Notebook    | [6a860d7c0f](https://linux-hardware.org/?probe=6a860d7c0f) | Aug 15, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [48637ddb10](https://linux-hardware.org/?probe=48637ddb10) | Aug 14, 2022 |
| Purism        | Librem 15 v4                | Notebook    | [4448709e50](https://linux-hardware.org/?probe=4448709e50) | Aug 13, 2022 |
| Purism        | Librem 15 v4                | Notebook    | [9e76f9e7ff](https://linux-hardware.org/?probe=9e76f9e7ff) | Aug 13, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [ee6f495403](https://linux-hardware.org/?probe=ee6f495403) | Aug 13, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [289850f128](https://linux-hardware.org/?probe=289850f128) | Aug 13, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [8d95c82a1d](https://linux-hardware.org/?probe=8d95c82a1d) | Aug 12, 2022 |
| Timi          | A35                         | Notebook    | [944f3f0942](https://linux-hardware.org/?probe=944f3f0942) | Aug 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [166edbd7db](https://linux-hardware.org/?probe=166edbd7db) | Aug 12, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [7d7ceef044](https://linux-hardware.org/?probe=7d7ceef044) | Aug 12, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [c374f64c25](https://linux-hardware.org/?probe=c374f64c25) | Aug 11, 2022 |
| Notebook      | N141CU                      | Notebook    | [4d96f7358c](https://linux-hardware.org/?probe=4d96f7358c) | Aug 10, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [0c23760c27](https://linux-hardware.org/?probe=0c23760c27) | Aug 10, 2022 |
| Unknown       | QNAP TS-221                 | Desktop     | [8d3f7ca9cf](https://linux-hardware.org/?probe=8d3f7ca9cf) | Aug 10, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [2781a13b80](https://linux-hardware.org/?probe=2781a13b80) | Aug 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [9b228ae787](https://linux-hardware.org/?probe=9b228ae787) | Aug 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [9f2e51f185](https://linux-hardware.org/?probe=9f2e51f185) | Aug 10, 2022 |
| ASRock        | P67 Extreme4 Gen3           | Desktop     | [b94e1be5ab](https://linux-hardware.org/?probe=b94e1be5ab) | Aug 09, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [0e7d0b5d33](https://linux-hardware.org/?probe=0e7d0b5d33) | Aug 09, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1f10876798](https://linux-hardware.org/?probe=1f10876798) | Aug 08, 2022 |
| Microsoft     | Surface Go 3                | Tablet      | [f97852a196](https://linux-hardware.org/?probe=f97852a196) | Aug 08, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [78f846e0e5](https://linux-hardware.org/?probe=78f846e0e5) | Aug 08, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ac538e23dc](https://linux-hardware.org/?probe=ac538e23dc) | Aug 07, 2022 |
| Microsoft     | Surface Go 3                | Tablet      | [ca880d8154](https://linux-hardware.org/?probe=ca880d8154) | Aug 06, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [3e7a65077d](https://linux-hardware.org/?probe=3e7a65077d) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [2ff6a7fe85](https://linux-hardware.org/?probe=2ff6a7fe85) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [d54acf14ff](https://linux-hardware.org/?probe=d54acf14ff) | Aug 06, 2022 |
| Toshiba       | NB100                       | Notebook    | [b91ee9b36b](https://linux-hardware.org/?probe=b91ee9b36b) | Aug 05, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [019849a487](https://linux-hardware.org/?probe=019849a487) | Aug 04, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [b875ef6dbf](https://linux-hardware.org/?probe=b875ef6dbf) | Aug 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [4caa777a81](https://linux-hardware.org/?probe=4caa777a81) | Aug 04, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [f14436327b](https://linux-hardware.org/?probe=f14436327b) | Aug 04, 2022 |
| Samsung       | 700G7C                      | Notebook    | [cd554f5d17](https://linux-hardware.org/?probe=cd554f5d17) | Aug 03, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [3db1e1ee37](https://linux-hardware.org/?probe=3db1e1ee37) | Aug 03, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [2cea7378e8](https://linux-hardware.org/?probe=2cea7378e8) | Aug 03, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [69188053f5](https://linux-hardware.org/?probe=69188053f5) | Aug 02, 2022 |
| ASRock        | B75M-GL R2.0                | Desktop     | [eed9f05678](https://linux-hardware.org/?probe=eed9f05678) | Aug 01, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [19d2273e6b](https://linux-hardware.org/?probe=19d2273e6b) | Aug 01, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [effa59ed64](https://linux-hardware.org/?probe=effa59ed64) | Aug 01, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [0ac4f27d0f](https://linux-hardware.org/?probe=0ac4f27d0f) | Jul 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f22250f00c](https://linux-hardware.org/?probe=f22250f00c) | Jul 31, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [de9a854095](https://linux-hardware.org/?probe=de9a854095) | Jul 31, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1051593809](https://linux-hardware.org/?probe=1051593809) | Jul 31, 2022 |
| Gigabyte      | 970A-DS3                    | Desktop     | [78f00bd2aa](https://linux-hardware.org/?probe=78f00bd2aa) | Jul 30, 2022 |
| Razer         | Blade 15 Studio Edition ... | Notebook    | [359f708604](https://linux-hardware.org/?probe=359f708604) | Jul 30, 2022 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [d3d824f468](https://linux-hardware.org/?probe=d3d824f468) | Jul 29, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [29a26324b9](https://linux-hardware.org/?probe=29a26324b9) | Jul 29, 2022 |
| ASUSTek       | ROG G703GI_G7BI             | Notebook    | [88a326be83](https://linux-hardware.org/?probe=88a326be83) | Jul 28, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [e7f56631b1](https://linux-hardware.org/?probe=e7f56631b1) | Jul 27, 2022 |
| Supermicro    | X10SRL-FB                   | Server      | [a8dc9cfc07](https://linux-hardware.org/?probe=a8dc9cfc07) | Jul 27, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [5ff32931fa](https://linux-hardware.org/?probe=5ff32931fa) | Jul 27, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [dc7eff27cf](https://linux-hardware.org/?probe=dc7eff27cf) | Jul 26, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [f3972b3a7d](https://linux-hardware.org/?probe=f3972b3a7d) | Jul 26, 2022 |
| Timi          | Mi Laptop Pro 15 2020       | Notebook    | [5455e664e0](https://linux-hardware.org/?probe=5455e664e0) | Jul 26, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [b15fb90c18](https://linux-hardware.org/?probe=b15fb90c18) | Jul 26, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [d2eb8a032b](https://linux-hardware.org/?probe=d2eb8a032b) | Jul 26, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [c98fed5f84](https://linux-hardware.org/?probe=c98fed5f84) | Jul 25, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [dae325b47b](https://linux-hardware.org/?probe=dae325b47b) | Jul 25, 2022 |
| Dell          | 0FKD45 A03                  | Server      | [0caba2e4b0](https://linux-hardware.org/?probe=0caba2e4b0) | Jul 25, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [8f46b7dcca](https://linux-hardware.org/?probe=8f46b7dcca) | Jul 25, 2022 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [64dad58b71](https://linux-hardware.org/?probe=64dad58b71) | Jul 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [6302f1ee8b](https://linux-hardware.org/?probe=6302f1ee8b) | Jul 25, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e1e16aa154](https://linux-hardware.org/?probe=e1e16aa154) | Jul 25, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [153acd77c2](https://linux-hardware.org/?probe=153acd77c2) | Jul 24, 2022 |
| ASRock        | AM1H-ITX                    | Desktop     | [a15c82ba0c](https://linux-hardware.org/?probe=a15c82ba0c) | Jul 24, 2022 |
| TYAN Compu... | S7025                       | Server      | [844d96fcd7](https://linux-hardware.org/?probe=844d96fcd7) | Jul 22, 2022 |
| Unknown       | QNAP TS-221                 | Desktop     | [fb3741faab](https://linux-hardware.org/?probe=fb3741faab) | Jul 21, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [56d5853243](https://linux-hardware.org/?probe=56d5853243) | Jul 19, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [d3d26541f1](https://linux-hardware.org/?probe=d3d26541f1) | Jul 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [8f2f1582e8](https://linux-hardware.org/?probe=8f2f1582e8) | Jul 17, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [056d74f1a9](https://linux-hardware.org/?probe=056d74f1a9) | Jul 17, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [e6b6d3b5e6](https://linux-hardware.org/?probe=e6b6d3b5e6) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [93f8a4ce9f](https://linux-hardware.org/?probe=93f8a4ce9f) | Jul 16, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [e9e0b50bbb](https://linux-hardware.org/?probe=e9e0b50bbb) | Jul 15, 2022 |
| Dell          | Latitude 5289               | Convertible | [a0844cdadd](https://linux-hardware.org/?probe=a0844cdadd) | Jul 15, 2022 |
| ASUSTek       | ROG G703GI_G7BI             | Notebook    | [4d636c74d3](https://linux-hardware.org/?probe=4d636c74d3) | Jul 14, 2022 |
| MSI           | Z87-G45 GAMING              | Desktop     | [8602f7246a](https://linux-hardware.org/?probe=8602f7246a) | Jul 12, 2022 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [0d6de2415e](https://linux-hardware.org/?probe=0d6de2415e) | Jul 11, 2022 |
| MSI           | GS63VR 6RF                  | Notebook    | [30ad17796f](https://linux-hardware.org/?probe=30ad17796f) | Jul 11, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [94e9d2f65a](https://linux-hardware.org/?probe=94e9d2f65a) | Jul 10, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [f67a64f833](https://linux-hardware.org/?probe=f67a64f833) | Jul 10, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [6d15b85193](https://linux-hardware.org/?probe=6d15b85193) | Jul 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [8f36480ad7](https://linux-hardware.org/?probe=8f36480ad7) | Jul 10, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [dccb88852f](https://linux-hardware.org/?probe=dccb88852f) | Jul 10, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0237c9df10](https://linux-hardware.org/?probe=0237c9df10) | Jul 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [85dbd84c37](https://linux-hardware.org/?probe=85dbd84c37) | Jul 09, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [aa87616696](https://linux-hardware.org/?probe=aa87616696) | Jul 09, 2022 |
| Dell          | Latitude D420               | Notebook    | [2e3ded5234](https://linux-hardware.org/?probe=2e3ded5234) | Jul 08, 2022 |
| MSI           | GS63VR 6RF                  | Notebook    | [097cc820d3](https://linux-hardware.org/?probe=097cc820d3) | Jul 08, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [5bdfb575ae](https://linux-hardware.org/?probe=5bdfb575ae) | Jul 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [850003c6da](https://linux-hardware.org/?probe=850003c6da) | Jul 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [1b94ade16a](https://linux-hardware.org/?probe=1b94ade16a) | Jul 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [685e3d36bc](https://linux-hardware.org/?probe=685e3d36bc) | Jul 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [b436712f17](https://linux-hardware.org/?probe=b436712f17) | Jul 04, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [d442c531e8](https://linux-hardware.org/?probe=d442c531e8) | Jul 03, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [cf8784ac23](https://linux-hardware.org/?probe=cf8784ac23) | Jul 03, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [c1e5d91a40](https://linux-hardware.org/?probe=c1e5d91a40) | Jul 02, 2022 |
| Dell          | Latitude D420               | Notebook    | [162b346743](https://linux-hardware.org/?probe=162b346743) | Jul 02, 2022 |
| Supermicro    | X10SRL-FB                   | Server      | [253c441703](https://linux-hardware.org/?probe=253c441703) | Jul 02, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [1af80d1cdb](https://linux-hardware.org/?probe=1af80d1cdb) | Jul 01, 2022 |
| Timi          | RedmiBook 13                | Notebook    | [fb3b3f37d5](https://linux-hardware.org/?probe=fb3b3f37d5) | Jun 30, 2022 |
| Dell          | Latitude D420               | Notebook    | [c531c131ec](https://linux-hardware.org/?probe=c531c131ec) | Jun 28, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4c0fa03f61](https://linux-hardware.org/?probe=4c0fa03f61) | Jun 28, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [0c6dd4c77c](https://linux-hardware.org/?probe=0c6dd4c77c) | Jun 27, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [79dca3a17c](https://linux-hardware.org/?probe=79dca3a17c) | Jun 26, 2022 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | Desktop     | [f03dcf744a](https://linux-hardware.org/?probe=f03dcf744a) | Jun 26, 2022 |
| Dell          | Precision 7550              | Notebook    | [4779d18806](https://linux-hardware.org/?probe=4779d18806) | Jun 24, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [74060af6fc](https://linux-hardware.org/?probe=74060af6fc) | Jun 23, 2022 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [bab7d495b0](https://linux-hardware.org/?probe=bab7d495b0) | Jun 21, 2022 |
| AVITA         | NS14A6                      | Notebook    | [e3169acbbb](https://linux-hardware.org/?probe=e3169acbbb) | Jun 20, 2022 |
| Intel         | S5000XVN                    | Server      | [da50147a63](https://linux-hardware.org/?probe=da50147a63) | Jun 20, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | Notebook    | [b290cf5fe0](https://linux-hardware.org/?probe=b290cf5fe0) | Jun 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [2028b239fc](https://linux-hardware.org/?probe=2028b239fc) | Jun 19, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [20c198dd50](https://linux-hardware.org/?probe=20c198dd50) | Jun 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [27fd147a80](https://linux-hardware.org/?probe=27fd147a80) | Jun 19, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [17b77e3069](https://linux-hardware.org/?probe=17b77e3069) | Jun 17, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [286f8505c9](https://linux-hardware.org/?probe=286f8505c9) | Jun 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [fe7fa5fe7a](https://linux-hardware.org/?probe=fe7fa5fe7a) | Jun 17, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [59350b295e](https://linux-hardware.org/?probe=59350b295e) | Jun 13, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [223b882103](https://linux-hardware.org/?probe=223b882103) | Jun 12, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [7b531e1607](https://linux-hardware.org/?probe=7b531e1607) | Jun 09, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [197f417cea](https://linux-hardware.org/?probe=197f417cea) | Jun 09, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [80a6dc4a46](https://linux-hardware.org/?probe=80a6dc4a46) | Jun 09, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [f237211ddb](https://linux-hardware.org/?probe=f237211ddb) | Jun 09, 2022 |
| Pegatron      | 2ACE                        | Desktop     | [838cad5bc2](https://linux-hardware.org/?probe=838cad5bc2) | Jun 06, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [5745c8b787](https://linux-hardware.org/?probe=5745c8b787) | Jun 06, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [cb81a60917](https://linux-hardware.org/?probe=cb81a60917) | Jun 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [c6f9883076](https://linux-hardware.org/?probe=c6f9883076) | Jun 05, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [f2ca17eb5d](https://linux-hardware.org/?probe=f2ca17eb5d) | Jun 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [4abb49be35](https://linux-hardware.org/?probe=4abb49be35) | Jun 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [0c1909c43b](https://linux-hardware.org/?probe=0c1909c43b) | Jun 03, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [102ed915c5](https://linux-hardware.org/?probe=102ed915c5) | Jun 02, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [d17975e27b](https://linux-hardware.org/?probe=d17975e27b) | Jun 02, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [0a458659f6](https://linux-hardware.org/?probe=0a458659f6) | Jun 01, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [09fcdacb15](https://linux-hardware.org/?probe=09fcdacb15) | Jun 01, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [d33b756434](https://linux-hardware.org/?probe=d33b756434) | Jun 01, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [2c33cbbbe2](https://linux-hardware.org/?probe=2c33cbbbe2) | May 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [1be8c71a37](https://linux-hardware.org/?probe=1be8c71a37) | May 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [2669150033](https://linux-hardware.org/?probe=2669150033) | May 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [77989d3d20](https://linux-hardware.org/?probe=77989d3d20) | May 28, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [86021dcc38](https://linux-hardware.org/?probe=86021dcc38) | May 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e879d3c292](https://linux-hardware.org/?probe=e879d3c292) | May 27, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [0948f30719](https://linux-hardware.org/?probe=0948f30719) | May 26, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [b8603fccc0](https://linux-hardware.org/?probe=b8603fccc0) | May 26, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [1d5fe9025a](https://linux-hardware.org/?probe=1d5fe9025a) | May 25, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [38ac6de56d](https://linux-hardware.org/?probe=38ac6de56d) | May 25, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [af256d7649](https://linux-hardware.org/?probe=af256d7649) | May 24, 2022 |
| Supermicro    | H12SSL-NT                   | Server      | [6492614879](https://linux-hardware.org/?probe=6492614879) | May 21, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | Notebook    | [47297bafb5](https://linux-hardware.org/?probe=47297bafb5) | May 21, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | Notebook    | [7b878500c1](https://linux-hardware.org/?probe=7b878500c1) | May 21, 2022 |
| MSI           | MS-7A34                     | Notebook    | [8956078328](https://linux-hardware.org/?probe=8956078328) | May 21, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f7225b80ed](https://linux-hardware.org/?probe=f7225b80ed) | May 18, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [84a0dc5b83](https://linux-hardware.org/?probe=84a0dc5b83) | May 18, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [56fb967887](https://linux-hardware.org/?probe=56fb967887) | May 16, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [d1a9527039](https://linux-hardware.org/?probe=d1a9527039) | May 16, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [d675d89c8a](https://linux-hardware.org/?probe=d675d89c8a) | May 16, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [07e2cea31c](https://linux-hardware.org/?probe=07e2cea31c) | May 13, 2022 |
| Lenovo        | ThinkPad P73 20QSS09S00     | Notebook    | [8438c92818](https://linux-hardware.org/?probe=8438c92818) | May 12, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [2fcf37c00a](https://linux-hardware.org/?probe=2fcf37c00a) | May 11, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [474578814d](https://linux-hardware.org/?probe=474578814d) | May 10, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [bd6c3ca5b4](https://linux-hardware.org/?probe=bd6c3ca5b4) | May 09, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [b24677a908](https://linux-hardware.org/?probe=b24677a908) | May 01, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [07a115654d](https://linux-hardware.org/?probe=07a115654d) | Apr 30, 2022 |
| Dell          | 0J37VM A00                  | Desktop     | [76f13aa200](https://linux-hardware.org/?probe=76f13aa200) | Apr 28, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [a934bef382](https://linux-hardware.org/?probe=a934bef382) | Apr 24, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [3c1ff82bb0](https://linux-hardware.org/?probe=3c1ff82bb0) | Apr 24, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [b61b2af9eb](https://linux-hardware.org/?probe=b61b2af9eb) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6af0b2a3c9](https://linux-hardware.org/?probe=6af0b2a3c9) | Apr 21, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [4121c8fcc2](https://linux-hardware.org/?probe=4121c8fcc2) | Apr 20, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | Notebook    | [9ffcb6bf7a](https://linux-hardware.org/?probe=9ffcb6bf7a) | Apr 18, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [217905d42a](https://linux-hardware.org/?probe=217905d42a) | Apr 17, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | Notebook    | [00a23bc10c](https://linux-hardware.org/?probe=00a23bc10c) | Apr 17, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [5e6ce90c93](https://linux-hardware.org/?probe=5e6ce90c93) | Apr 13, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [cfd276f151](https://linux-hardware.org/?probe=cfd276f151) | Apr 13, 2022 |
| Dell          | G5 5505                     | Notebook    | [ce1fc33387](https://linux-hardware.org/?probe=ce1fc33387) | Apr 13, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [45472dad72](https://linux-hardware.org/?probe=45472dad72) | Apr 12, 2022 |
| HP            | ProBook 6570b               | Notebook    | [63d922ecdd](https://linux-hardware.org/?probe=63d922ecdd) | Apr 12, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [7a26d3fc81](https://linux-hardware.org/?probe=7a26d3fc81) | Apr 12, 2022 |
| HP            | ProBook 6570b               | Notebook    | [87414e70aa](https://linux-hardware.org/?probe=87414e70aa) | Apr 11, 2022 |
| Gigabyte      | H470 HD3                    | Desktop     | [5ce5c54ecd](https://linux-hardware.org/?probe=5ce5c54ecd) | Apr 09, 2022 |
| System76      | Gazelle                     | Notebook    | [9edcac1b2c](https://linux-hardware.org/?probe=9edcac1b2c) | Apr 09, 2022 |
| System76      | Gazelle                     | Notebook    | [e22baecee4](https://linux-hardware.org/?probe=e22baecee4) | Apr 07, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [68be7a767a](https://linux-hardware.org/?probe=68be7a767a) | Apr 07, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [403a6830d9](https://linux-hardware.org/?probe=403a6830d9) | Apr 04, 2022 |
| ASRock        | Z170A-X1                    | Desktop     | [9e1cc71d24](https://linux-hardware.org/?probe=9e1cc71d24) | Mar 31, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [9ebb4c0fd3](https://linux-hardware.org/?probe=9ebb4c0fd3) | Mar 31, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [5240890472](https://linux-hardware.org/?probe=5240890472) | Mar 29, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [5cde1a4e83](https://linux-hardware.org/?probe=5cde1a4e83) | Mar 24, 2022 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [33f98f8274](https://linux-hardware.org/?probe=33f98f8274) | Mar 23, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [6dddf500c7](https://linux-hardware.org/?probe=6dddf500c7) | Mar 22, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [593bf6f937](https://linux-hardware.org/?probe=593bf6f937) | Mar 21, 2022 |
| Unknown       | Unknown                     | Soc         | [dad2f6c4ba](https://linux-hardware.org/?probe=dad2f6c4ba) | Mar 20, 2022 |
| BANGHO        | MAX G0101                   | Notebook    | [b40c195d54](https://linux-hardware.org/?probe=b40c195d54) | Mar 20, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [6efb7791bb](https://linux-hardware.org/?probe=6efb7791bb) | Mar 19, 2022 |
| MSI           | MS-7A34                     | Notebook    | [27f8a2eb1f](https://linux-hardware.org/?probe=27f8a2eb1f) | Mar 18, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [70021af77a](https://linux-hardware.org/?probe=70021af77a) | Mar 15, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [7c09492e3b](https://linux-hardware.org/?probe=7c09492e3b) | Mar 14, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [f7e85dbf71](https://linux-hardware.org/?probe=f7e85dbf71) | Mar 14, 2022 |
| Framework     | Laptop                      | Notebook    | [8902c057fb](https://linux-hardware.org/?probe=8902c057fb) | Mar 10, 2022 |
| Dell          | 0J37VM A00                  | Desktop     | [a78d4c99e3](https://linux-hardware.org/?probe=a78d4c99e3) | Mar 09, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [7eea4038f0](https://linux-hardware.org/?probe=7eea4038f0) | Mar 09, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [fe3e35f15b](https://linux-hardware.org/?probe=fe3e35f15b) | Mar 09, 2022 |
| Framework     | Laptop                      | Notebook    | [e17db20b1c](https://linux-hardware.org/?probe=e17db20b1c) | Mar 08, 2022 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [bc052daf77](https://linux-hardware.org/?probe=bc052daf77) | Mar 07, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [44656b1bd4](https://linux-hardware.org/?probe=44656b1bd4) | Mar 03, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [a5242ed058](https://linux-hardware.org/?probe=a5242ed058) | Feb 26, 2022 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | Notebook    | [0022f4a8cc](https://linux-hardware.org/?probe=0022f4a8cc) | Feb 26, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [071dd25266](https://linux-hardware.org/?probe=071dd25266) | Feb 24, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [cde7566ecb](https://linux-hardware.org/?probe=cde7566ecb) | Feb 22, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [c7cd5ce50d](https://linux-hardware.org/?probe=c7cd5ce50d) | Feb 21, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [5dea4207b1](https://linux-hardware.org/?probe=5dea4207b1) | Feb 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [5836ccecc2](https://linux-hardware.org/?probe=5836ccecc2) | Feb 10, 2022 |
| MSI           | GS63VR 6RF                  | Notebook    | [c20c87027e](https://linux-hardware.org/?probe=c20c87027e) | Feb 10, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [8f79e4d763](https://linux-hardware.org/?probe=8f79e4d763) | Feb 06, 2022 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [f79196e39c](https://linux-hardware.org/?probe=f79196e39c) | Feb 05, 2022 |
| Gigabyte      | Z490 UD                     | Desktop     | [b571c22d4f](https://linux-hardware.org/?probe=b571c22d4f) | Feb 04, 2022 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [4a717f6348](https://linux-hardware.org/?probe=4a717f6348) | Feb 02, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [d424a8e145](https://linux-hardware.org/?probe=d424a8e145) | Feb 01, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [89dbe92caf](https://linux-hardware.org/?probe=89dbe92caf) | Feb 01, 2022 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [7f7720253e](https://linux-hardware.org/?probe=7f7720253e) | Feb 01, 2022 |
| MSI           | GS63VR 6RF                  | Notebook    | [4873365af6](https://linux-hardware.org/?probe=4873365af6) | Jan 30, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [6b7cf2d570](https://linux-hardware.org/?probe=6b7cf2d570) | Jan 27, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [c021622ad4](https://linux-hardware.org/?probe=c021622ad4) | Jan 27, 2022 |
| Timi          | RedmiBook 13                | Notebook    | [e20538f56a](https://linux-hardware.org/?probe=e20538f56a) | Jan 26, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [656da02110](https://linux-hardware.org/?probe=656da02110) | Jan 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [a4f6a4a38e](https://linux-hardware.org/?probe=a4f6a4a38e) | Jan 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [9e4f498056](https://linux-hardware.org/?probe=9e4f498056) | Jan 24, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [1721bed3e1](https://linux-hardware.org/?probe=1721bed3e1) | Jan 24, 2022 |
| Gigabyte      | Z490 UD                     | Desktop     | [eac4639ad2](https://linux-hardware.org/?probe=eac4639ad2) | Jan 22, 2022 |
| MSI           | GE73 Raider RGB 8RF         | Notebook    | [a5a825a072](https://linux-hardware.org/?probe=a5a825a072) | Jan 22, 2022 |
| Lenovo        | ThinkPad 20FMCT01WW         | Notebook    | [4bd81196a0](https://linux-hardware.org/?probe=4bd81196a0) | Jan 21, 2022 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [65ce2eb070](https://linux-hardware.org/?probe=65ce2eb070) | Jan 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [d786a0b993](https://linux-hardware.org/?probe=d786a0b993) | Jan 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [6af6121c33](https://linux-hardware.org/?probe=6af6121c33) | Jan 17, 2022 |
| Dell          | Precision 3561              | Notebook    | [f5417a1852](https://linux-hardware.org/?probe=f5417a1852) | Jan 16, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [2aa146518a](https://linux-hardware.org/?probe=2aa146518a) | Jan 16, 2022 |
| TYAN Compu... | S7025                       | Server      | [c5f294d367](https://linux-hardware.org/?probe=c5f294d367) | Jan 12, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [5f92f3376e](https://linux-hardware.org/?probe=5f92f3376e) | Jan 11, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [d46da820e0](https://linux-hardware.org/?probe=d46da820e0) | Jan 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [dcf0799dd1](https://linux-hardware.org/?probe=dcf0799dd1) | Jan 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [fb3838c0db](https://linux-hardware.org/?probe=fb3838c0db) | Jan 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [0cf6f2102c](https://linux-hardware.org/?probe=0cf6f2102c) | Jan 03, 2022 |
| Timi          | RedmiBook 13                | Notebook    | [528d0d32b4](https://linux-hardware.org/?probe=528d0d32b4) | Jan 01, 2022 |
| TYAN Compu... | S7025                       | Server      | [4a4fe05b48](https://linux-hardware.org/?probe=4a4fe05b48) | Dec 27, 2021 |
| EVGA          | Z390 DARK                   | Desktop     | [7672395a1c](https://linux-hardware.org/?probe=7672395a1c) | Dec 24, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [1695a19b52](https://linux-hardware.org/?probe=1695a19b52) | Dec 24, 2021 |
| Intel         | S1200RP G62251-406          | Server      | [986c6d1f51](https://linux-hardware.org/?probe=986c6d1f51) | Dec 24, 2021 |
| Framework     | Laptop                      | Notebook    | [33bb6590a6](https://linux-hardware.org/?probe=33bb6590a6) | Dec 21, 2021 |
| TYAN Compu... | S7025                       | Server      | [88ee246f4e](https://linux-hardware.org/?probe=88ee246f4e) | Dec 21, 2021 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [36ad5ef96a](https://linux-hardware.org/?probe=36ad5ef96a) | Dec 16, 2021 |
| BESSTAR Te... | ATB15                       | Server      | [783d1d7b6f](https://linux-hardware.org/?probe=783d1d7b6f) | Dec 16, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [a2ee48eeb1](https://linux-hardware.org/?probe=a2ee48eeb1) | Dec 16, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [ee63a84605](https://linux-hardware.org/?probe=ee63a84605) | Dec 11, 2021 |
| Toshiba       | Satellite C850D-118         | Notebook    | [b15f2e2c92](https://linux-hardware.org/?probe=b15f2e2c92) | Dec 09, 2021 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | Desktop     | [b92f432637](https://linux-hardware.org/?probe=b92f432637) | Dec 07, 2021 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | Desktop     | [d8f50aaa2e](https://linux-hardware.org/?probe=d8f50aaa2e) | Dec 07, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [6649bea1f8](https://linux-hardware.org/?probe=6649bea1f8) | Dec 04, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [723e2a158a](https://linux-hardware.org/?probe=723e2a158a) | Dec 03, 2021 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [e155882ffa](https://linux-hardware.org/?probe=e155882ffa) | Dec 02, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [86f5c0bc34](https://linux-hardware.org/?probe=86f5c0bc34) | Nov 30, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [e06c73ada9](https://linux-hardware.org/?probe=e06c73ada9) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [ad15be0510](https://linux-hardware.org/?probe=ad15be0510) | Nov 29, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | Notebook    | [6eca4a1be2](https://linux-hardware.org/?probe=6eca4a1be2) | Nov 22, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | Notebook    | [6c92c6ecbb](https://linux-hardware.org/?probe=6c92c6ecbb) | Nov 22, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [e2c087b9c7](https://linux-hardware.org/?probe=e2c087b9c7) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | Notebook    | [3ea389d8ff](https://linux-hardware.org/?probe=3ea389d8ff) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | Notebook    | [19f48288ec](https://linux-hardware.org/?probe=19f48288ec) | Nov 20, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [40748c60b0](https://linux-hardware.org/?probe=40748c60b0) | Nov 18, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [eafa22145d](https://linux-hardware.org/?probe=eafa22145d) | Nov 15, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [2900821ed3](https://linux-hardware.org/?probe=2900821ed3) | Nov 14, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4cfb74fb42](https://linux-hardware.org/?probe=4cfb74fb42) | Nov 14, 2021 |
| Lenovo        | ThinkPad E495 20NE000BGE    | Notebook    | [871e0a8d36](https://linux-hardware.org/?probe=871e0a8d36) | Nov 11, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [6f308039a8](https://linux-hardware.org/?probe=6f308039a8) | Nov 06, 2021 |
| Intel         | S1200RP G62251-405          | Server      | [798cf3cc96](https://linux-hardware.org/?probe=798cf3cc96) | Nov 02, 2021 |
| MSI           | H110M PRO-D                 | Desktop     | [cb3dcdd186](https://linux-hardware.org/?probe=cb3dcdd186) | Nov 02, 2021 |
| MSI           | H110M PRO-D                 | Desktop     | [b53420c26a](https://linux-hardware.org/?probe=b53420c26a) | Nov 02, 2021 |
| Dell          | Latitude 7490               | Notebook    | [ea64667f2c](https://linux-hardware.org/?probe=ea64667f2c) | Nov 01, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [161865edb0](https://linux-hardware.org/?probe=161865edb0) | Oct 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a4806aa50f](https://linux-hardware.org/?probe=a4806aa50f) | Oct 30, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [aea7d9561e](https://linux-hardware.org/?probe=aea7d9561e) | Oct 29, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [0f4ae74d8e](https://linux-hardware.org/?probe=0f4ae74d8e) | Oct 29, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [f3f75352e4](https://linux-hardware.org/?probe=f3f75352e4) | Oct 29, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e9cc487951](https://linux-hardware.org/?probe=e9cc487951) | Oct 28, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [6105164e23](https://linux-hardware.org/?probe=6105164e23) | Oct 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [8a34d739fd](https://linux-hardware.org/?probe=8a34d739fd) | Oct 25, 2021 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [5b06944051](https://linux-hardware.org/?probe=5b06944051) | Oct 25, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [58e3f9c07f](https://linux-hardware.org/?probe=58e3f9c07f) | Oct 23, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [eb02a6d4d5](https://linux-hardware.org/?probe=eb02a6d4d5) | Oct 20, 2021 |
| ASRock        | X370 Killer SLI/ac          | Desktop     | [2e4c1c4527](https://linux-hardware.org/?probe=2e4c1c4527) | Oct 17, 2021 |
| Acer          | Aspire A515-55              | Notebook    | [437c8fb96b](https://linux-hardware.org/?probe=437c8fb96b) | Oct 12, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [95cd0c0751](https://linux-hardware.org/?probe=95cd0c0751) | Oct 07, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [3ad4e11bac](https://linux-hardware.org/?probe=3ad4e11bac) | Oct 06, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [18a2385458](https://linux-hardware.org/?probe=18a2385458) | Oct 06, 2021 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [9901023f19](https://linux-hardware.org/?probe=9901023f19) | Oct 03, 2021 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [e2057e68dd](https://linux-hardware.org/?probe=e2057e68dd) | Oct 03, 2021 |
| Dell          | Inspiron 5415               | Notebook    | [a265f8ea5c](https://linux-hardware.org/?probe=a265f8ea5c) | Oct 01, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.15.52-gentoo            | 9         | 3.7%    |
| 5.15.52-gentoo-x86_64     | 8         | 3.29%   |
| 5.15.41-gentoo-x86_64     | 8         | 3.29%   |
| 5.15.41-gentoo            | 6         | 2.47%   |
| 5.19.0-gentoo-x86_64      | 5         | 2.06%   |
| 5.17.1-gentoo-r1          | 5         | 2.06%   |
| 5.15.59-gentoo-x86_64     | 4         | 1.65%   |
| 5.15.59-gentoo            | 4         | 1.65%   |
| 5.15.41-gentoo-dist       | 4         | 1.65%   |
| 5.19.0-gentoo             | 3         | 1.23%   |
| 5.18.7-gentoo             | 3         | 1.23%   |
| 5.18.1-gentoo-r2          | 3         | 1.23%   |
| 5.16.2-gentoo             | 3         | 1.23%   |
| 5.15.52-gentoo-dist       | 3         | 1.23%   |
| 5.15.10-gentoo-x86_64     | 3         | 1.23%   |
| 5.15.10-gentoo            | 3         | 1.23%   |
| 5.14.9-gentoo-x86_64      | 3         | 1.23%   |
| 5.18.9-gentoo             | 2         | 0.82%   |
| 5.18.4-gentoo             | 2         | 0.82%   |
| 5.18.14-gentoo-x86_64     | 2         | 0.82%   |
| 5.18.10-k08               | 2         | 0.82%   |
| 5.18.10-gentoo            | 2         | 0.82%   |
| 5.17.9-gentoo-x86_64      | 2         | 0.82%   |
| 5.17.8-gentoo-x86_64      | 2         | 0.82%   |
| 5.17.3-gentoo             | 2         | 0.82%   |
| 5.17.0-gentoo-x86_64      | 2         | 0.82%   |
| 5.17.0-gentoo             | 2         | 0.82%   |
| 5.16.9-gentoo             | 2         | 0.82%   |
| 5.16.4-gentoo             | 2         | 0.82%   |
| 5.16.11-gentoo-x86_64     | 2         | 0.82%   |
| 5.16.11-gentoo-dist       | 2         | 0.82%   |
| 5.16.0-gentoo-x86_64      | 2         | 0.82%   |
| 5.15.6-gentoo             | 2         | 0.82%   |
| 5.15.12-gentoo-x86_64     | 2         | 0.82%   |
| 5.15.1-gentoo-x86_64      | 2         | 0.82%   |
| 5.14.14-gentoo-x86_64     | 2         | 0.82%   |
| 5.14.14-gentoo-dist       | 2         | 0.82%   |
| 5.14.13-gentoo            | 2         | 0.82%   |
| 5.14.12-gentoo            | 2         | 0.82%   |
| 6.0.0-Phaco-g8f10ff49057f | 1         | 0.41%   |
| 5.19.3-gentoo-x86_64      | 1         | 0.41%   |
| 5.19.1-gentoo-a6          | 1         | 0.41%   |
| 5.19.0-xanmod1-x86_64     | 1         | 0.41%   |
| 5.19.0-xanmod1-elitebook  | 1         | 0.41%   |
| 5.19.0-rc2-p+             | 1         | 0.41%   |
| 5.19.0-gentoo-carbon      | 1         | 0.41%   |
| 5.18.9-gentoo-x86_64      | 1         | 0.41%   |
| 5.18.9-1-MANJARO-ARM      | 1         | 0.41%   |
| 5.18.8-gentoo-dist        | 1         | 0.41%   |
| 5.18.8-gentoo             | 1         | 0.41%   |
| 5.18.6-gentoo-x86_64      | 1         | 0.41%   |
| 5.18.6-gentoo-venus       | 1         | 0.41%   |
| 5.18.6-gentoo             | 1         | 0.41%   |
| 5.18.5-gentoo             | 1         | 0.41%   |
| 5.18.3-zen1               | 1         | 0.41%   |
| 5.18.2-gentoo             | 1         | 0.41%   |
| 5.18.19-gentoo-r1         | 1         | 0.41%   |
| 5.18.16-gentoo-x86_64     | 1         | 0.41%   |
| 5.18.15-gentoo-x86_64     | 1         | 0.41%   |
| 5.18.15-gentoo-dist       | 1         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.52 | 22        | 9.09%   |
| 5.15.41 | 19        | 7.85%   |
| 5.19.0  | 12        | 4.96%   |
| 5.15.59 | 10        | 4.13%   |
| 5.16.0  | 7         | 2.89%   |
| 5.17.1  | 6         | 2.48%   |
| 5.15.10 | 6         | 2.48%   |
| 5.18.10 | 5         | 2.07%   |
| 5.18.1  | 5         | 2.07%   |
| 5.17.9  | 5         | 2.07%   |
| 5.14.14 | 5         | 2.07%   |
| 5.18.9  | 4         | 1.65%   |
| 5.17.7  | 4         | 1.65%   |
| 5.17.0  | 4         | 1.65%   |
| 5.16.2  | 4         | 1.65%   |
| 5.16.14 | 4         | 1.65%   |
| 5.16.11 | 4         | 1.65%   |
| 5.15.12 | 4         | 1.65%   |
| 5.14.9  | 4         | 1.65%   |
| 5.18.7  | 3         | 1.24%   |
| 5.18.6  | 3         | 1.24%   |
| 5.18.15 | 3         | 1.24%   |
| 5.18.14 | 3         | 1.24%   |
| 5.18.0  | 3         | 1.24%   |
| 5.17.8  | 3         | 1.24%   |
| 5.17.3  | 3         | 1.24%   |
| 5.17.2  | 3         | 1.24%   |
| 5.16.9  | 3         | 1.24%   |
| 5.16.10 | 3         | 1.24%   |
| 5.15.5  | 3         | 1.24%   |
| 5.18.8  | 2         | 0.83%   |
| 5.18.4  | 2         | 0.83%   |
| 5.17.6  | 2         | 0.83%   |
| 5.16.8  | 2         | 0.83%   |
| 5.16.5  | 2         | 0.83%   |
| 5.16.4  | 2         | 0.83%   |
| 5.16.1  | 2         | 0.83%   |
| 5.15.6  | 2         | 0.83%   |
| 5.15.55 | 2         | 0.83%   |
| 5.15.4  | 2         | 0.83%   |
| 5.15.33 | 2         | 0.83%   |
| 5.15.32 | 2         | 0.83%   |
| 5.15.2  | 2         | 0.83%   |
| 5.15.13 | 2         | 0.83%   |
| 5.15.1  | 2         | 0.83%   |
| 5.15.0  | 2         | 0.83%   |
| 5.14.13 | 2         | 0.83%   |
| 5.14.12 | 2         | 0.83%   |
| 6.0.0   | 1         | 0.41%   |
| 5.19.3  | 1         | 0.41%   |
| 5.19.1  | 1         | 0.41%   |
| 5.18.5  | 1         | 0.41%   |
| 5.18.3  | 1         | 0.41%   |
| 5.18.2  | 1         | 0.41%   |
| 5.18.19 | 1         | 0.41%   |
| 5.18.16 | 1         | 0.41%   |
| 5.18.12 | 1         | 0.41%   |
| 5.18.11 | 1         | 0.41%   |
| 5.17.5  | 1         | 0.41%   |
| 5.17.13 | 1         | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 83        | 36.73%  |
| 5.18    | 38        | 16.81%  |
| 5.16    | 35        | 15.49%  |
| 5.17    | 29        | 12.83%  |
| 5.14    | 17        | 7.52%   |
| 5.19    | 14        | 6.19%   |
| 5.10    | 7         | 3.1%    |
| 6.0     | 1         | 0.44%   |
| 4.9     | 1         | 0.44%   |
| 4.14    | 1         | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| x86_64   | 198       | 95.65%  |
| i686     | 4         | 1.93%   |
| aarch64  | 3         | 1.45%   |
| ppc      | 1         | 0.48%   |
| armv5tel | 1         | 0.48%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 70        | 33.18%  |
| KDE5          | 67        | 31.75%  |
| GNOME         | 33        | 15.64%  |
| XFCE          | 16        | 7.58%   |
| dwm           | 5         | 2.37%   |
| MATE          | 4         | 1.9%    |
| LXQt          | 3         | 1.42%   |
| sway          | 2         | 0.95%   |
| i3            | 2         | 0.95%   |
| Enlightenment | 2         | 0.95%   |
| Cinnamon      | 2         | 0.95%   |
| xmonad        | 1         | 0.47%   |
| Unity         | 1         | 0.47%   |
| LeftWM        | 1         | 0.47%   |
| KDE           | 1         | 0.47%   |
| fvwm          | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 105       | 48.84%  |
| Wayland | 40        | 18.6%   |
| Unknown | 36        | 16.74%  |
| Tty     | 34        | 15.81%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 80        | 38.1%   |
| SDDM    | 72        | 34.29%  |
| LightDM | 28        | 13.33%  |
| GDM     | 19        | 9.05%   |
| LXDM    | 5         | 2.38%   |
| SLiM    | 3         | 1.43%   |
| XDM     | 2         | 0.95%   |
| GREETD  | 1         | 0.48%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 94        | 45.41%  |
| C.UTF8     | 24        | 11.59%  |
| en_GB      | 19        | 9.18%   |
| Unknown    | 16        | 7.73%   |
| ru_RU      | 9         | 4.35%   |
| de_DE      | 9         | 4.35%   |
| C          | 6         | 2.9%    |
| pl_PL      | 3         | 1.45%   |
| fr_FR      | 3         | 1.45%   |
| zh_CN      | 2         | 0.97%   |
| it_IT      | 2         | 0.97%   |
| es_ES      | 2         | 0.97%   |
| es_AR      | 2         | 0.97%   |
| en_AU      | 2         | 0.97%   |
| el_GR      | 2         | 0.97%   |
| de_CH      | 2         | 0.97%   |
| zh_TW      | 1         | 0.48%   |
| tr_TR      | 1         | 0.48%   |
| sl_SI      | 1         | 0.48%   |
| pt_BR      | 1         | 0.48%   |
| ja_JP      | 1         | 0.48%   |
| fr_CA      | 1         | 0.48%   |
| es_MX      | 1         | 0.48%   |
| en_US.UTF8 | 1         | 0.48%   |
| en_NZ      | 1         | 0.48%   |
| en_CA      | 1         | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 180       | 85.31%  |
| BIOS | 31        | 14.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 119       | 57.49%  |
| Btrfs    | 55        | 26.57%  |
| F2fs     | 10        | 4.83%   |
| Zfs      | 9         | 4.35%   |
| XXXXXXX  | 7         | 3.38%   |
| Xfs      | 3         | 1.45%   |
| XXX      | 1         | 0.48%   |
| Xtrfs    | 1         | 0.48%   |
| Overlay  | 1         | 0.48%   |
| Bcachefs | 1         | 0.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 192       | 91.43%  |
| MBR     | 11        | 5.24%   |
| Unknown | 7         | 3.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 142       | 66.98%  |
| Yes       | 70        | 33.02%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 144       | 69.23%  |
| Yes       | 64        | 30.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 44        | 21.26%  |
| Lenovo                  | 38        | 18.36%  |
| MSI                     | 20        | 9.66%   |
| Dell                    | 19        | 9.18%   |
| Hewlett-Packard         | 13        | 6.28%   |
| Gigabyte Technology     | 13        | 6.28%   |
| ASRock                  | 12        | 5.8%    |
| Intel                   | 6         | 2.9%    |
| Timi                    | 4         | 1.93%   |
| Acer                    | 4         | 1.93%   |
| Toshiba                 | 3         | 1.45%   |
| Unknown                 | 3         | 1.45%   |
| TYAN Computer           | 2         | 0.97%   |
| Supermicro              | 2         | 0.97%   |
| HUAWEI                  | 2         | 0.97%   |
| Framework               | 2         | 0.97%   |
| win element             | 1         | 0.48%   |
| TUXEDO                  | 1         | 0.48%   |
| System76                | 1         | 0.48%   |
| Samsung Electronics     | 1         | 0.48%   |
| Razer                   | 1         | 0.48%   |
| Raspberry Pi Foundation | 1         | 0.48%   |
| Purism                  | 1         | 0.48%   |
| Pine Microsystems       | 1         | 0.48%   |
| Pegatron                | 1         | 0.48%   |
| Notebook                | 1         | 0.48%   |
| Neousys Technology      | 1         | 0.48%   |
| Microsoft               | 1         | 0.48%   |
| IBM                     | 1         | 0.48%   |
| Fujitsu                 | 1         | 0.48%   |
| Fanless Mini PC         | 1         | 0.48%   |
| EVGA                    | 1         | 0.48%   |
| Eluktronics             | 1         | 0.48%   |
| BESSTAR Tech            | 1         | 0.48%   |
| BANGHO                  | 1         | 0.48%   |
| AVITA                   | 1         | 0.48%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Unknown                                   | 3         | 1.45%   |
| TYAN S7025                                | 2         | 0.97%   |
| Toshiba Satellite C850D-118               | 2         | 0.97%   |
| Supermicro Super Server                   | 2         | 0.97%   |
| MSI GS63VR 6RF                            | 2         | 0.97%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ          | 2         | 0.97%   |
| Intel S1200RP                             | 2         | 0.97%   |
| HP Laptop 15s-eq0xxx                      | 2         | 0.97%   |
| Framework Laptop                          | 2         | 0.97%   |
| Dell XPS 15 9570                          | 2         | 0.97%   |
| ASUS Z170-A                               | 2         | 0.97%   |
| ASUS TUF Gaming X570-PLUS                 | 2         | 0.97%   |
| ASUS TUF GAMING B550-PLUS                 | 2         | 0.97%   |
| ASUS ROG STRIX X570-E GAMING              | 2         | 0.97%   |
| ASUS ROG Strix G513QY_G513QY              | 2         | 0.97%   |
| ASUS ROG STRIX B550-F GAMING              | 2         | 0.97%   |
| ASUS ROG CROSSHAIR VIII DARK HERO         | 2         | 0.97%   |
| win element MoreFine S500+                | 1         | 0.48%   |
| TUXEDO InfinityBook Pro 14 Gen6           | 1         | 0.48%   |
| Toshiba NB100                             | 1         | 0.48%   |
| Timi RedmiBook 13                         | 1         | 0.48%   |
| Timi Mi Laptop Pro 15 2020                | 1         | 0.48%   |
| Timi Mi Laptop Pro 15                     | 1         | 0.48%   |
| Timi A35                                  | 1         | 0.48%   |
| System76 Gazelle                          | 1         | 0.48%   |
| Samsung 700G7C                            | 1         | 0.48%   |
| Razer Blade 15 Studio Edition - Late 2019 | 1         | 0.48%   |
| RPi Raspberry Pi                          | 1         | 0.48%   |
| Purism Librem 15 v4                       | 1         | 0.48%   |
| Pine Microsystems Pine64 PinePhonePro     | 1         | 0.48%   |
| Pegatron 810-170st                        | 1         | 0.48%   |
| Notebook N141CU                           | 1         | 0.48%   |
| Neousys Nuvo-8208GC Series                | 1         | 0.48%   |
| MSI MS-7D31                               | 1         | 0.48%   |
| MSI MS-7D25                               | 1         | 0.48%   |
| MSI MS-7D09                               | 1         | 0.48%   |
| MSI MS-7C94                               | 1         | 0.48%   |
| MSI MS-7C56                               | 1         | 0.48%   |
| MSI MS-7C37                               | 1         | 0.48%   |
| MSI MS-7C35                               | 1         | 0.48%   |
| MSI MS-7C02                               | 1         | 0.48%   |
| MSI MS-7B98                               | 1         | 0.48%   |
| MSI MS-7B89                               | 1         | 0.48%   |
| MSI MS-7B86                               | 1         | 0.48%   |
| MSI MS-7B85                               | 1         | 0.48%   |
| MSI MS-7B17                               | 1         | 0.48%   |
| MSI MS-7A34                               | 1         | 0.48%   |
| MSI MS-7996                               | 1         | 0.48%   |
| MSI MS-7821                               | 1         | 0.48%   |
| MSI GE73 Raider RGB 8RF                   | 1         | 0.48%   |
| MSI GE66 Raider 11UE                      | 1         | 0.48%   |
| Microsoft Surface Go 3                    | 1         | 0.48%   |
| Lenovo Yoga Slim 7 14IIL05 82A1           | 1         | 0.48%   |
| Lenovo Yoga S940-14IWL 81Q7               | 1         | 0.48%   |
| Lenovo Yoga S740-14IIL 81RS               | 1         | 0.48%   |
| Lenovo ThinkStation P620 30E0001TGE       | 1         | 0.48%   |
| Lenovo ThinkPad Z16 Gen 1 21D4002GGE      | 1         | 0.48%   |
| Lenovo ThinkPad Yoga 460 20EMCTO1WW       | 1         | 0.48%   |
| Lenovo ThinkPad X390 Yoga 20NN0027MH      | 1         | 0.48%   |
| Lenovo ThinkPad X220 4291QT1              | 1         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| ASUS ROG                 | 20        | 9.66%   |
| Lenovo ThinkPad          | 19        | 9.18%   |
| ASUS TUF                 | 8         | 3.86%   |
| Lenovo Legion            | 6         | 2.9%    |
| Dell XPS                 | 6         | 2.9%    |
| Lenovo IdeaPad           | 5         | 2.42%   |
| ASUS PRIME               | 4         | 1.93%   |
| Lenovo Yoga              | 3         | 1.45%   |
| HP OMEN                  | 3         | 1.45%   |
| HP Laptop                | 3         | 1.45%   |
| HP EliteBook             | 3         | 1.45%   |
| Dell Precision           | 3         | 1.45%   |
| Dell Latitude            | 3         | 1.45%   |
| Unknown                  | 3         | 1.45%   |
| TYAN S7025               | 2         | 0.97%   |
| Toshiba Satellite        | 2         | 0.97%   |
| Timi Mi                  | 2         | 0.97%   |
| Supermicro Super         | 2         | 0.97%   |
| MSI GS63VR               | 2         | 0.97%   |
| Lenovo ThinkBook         | 2         | 0.97%   |
| Intel S1200RP            | 2         | 0.97%   |
| HP Pavilion              | 2         | 0.97%   |
| Gigabyte B450            | 2         | 0.97%   |
| Framework Laptop         | 2         | 0.97%   |
| Dell OptiPlex            | 2         | 0.97%   |
| Dell Inspiron            | 2         | 0.97%   |
| ASUS Z170-A              | 2         | 0.97%   |
| ASUS VivoBook            | 2         | 0.97%   |
| ASRock X370              | 2         | 0.97%   |
| Acer Aspire              | 2         | 0.97%   |
| win element MoreFine     | 1         | 0.48%   |
| TUXEDO InfinityBook      | 1         | 0.48%   |
| Toshiba NB100            | 1         | 0.48%   |
| Timi RedmiBook           | 1         | 0.48%   |
| Timi A35                 | 1         | 0.48%   |
| System76 Gazelle         | 1         | 0.48%   |
| Samsung 700G7C           | 1         | 0.48%   |
| Razer Blade              | 1         | 0.48%   |
| RPi Raspberry            | 1         | 0.48%   |
| Purism Librem            | 1         | 0.48%   |
| Pine Microsystems Pine64 | 1         | 0.48%   |
| Pegatron 810-170st       | 1         | 0.48%   |
| Notebook N141CU          | 1         | 0.48%   |
| Neousys Nuvo-8208GC      | 1         | 0.48%   |
| MSI MS-7D31              | 1         | 0.48%   |
| MSI MS-7D25              | 1         | 0.48%   |
| MSI MS-7D09              | 1         | 0.48%   |
| MSI MS-7C94              | 1         | 0.48%   |
| MSI MS-7C56              | 1         | 0.48%   |
| MSI MS-7C37              | 1         | 0.48%   |
| MSI MS-7C35              | 1         | 0.48%   |
| MSI MS-7C02              | 1         | 0.48%   |
| MSI MS-7B98              | 1         | 0.48%   |
| MSI MS-7B89              | 1         | 0.48%   |
| MSI MS-7B86              | 1         | 0.48%   |
| MSI MS-7B85              | 1         | 0.48%   |
| MSI MS-7B17              | 1         | 0.48%   |
| MSI MS-7A34              | 1         | 0.48%   |
| MSI MS-7996              | 1         | 0.48%   |
| MSI MS-7821              | 1         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 50        | 24.15%  |
| 2019    | 36        | 17.39%  |
| 2020    | 33        | 15.94%  |
| 2018    | 22        | 10.63%  |
| 2017    | 10        | 4.83%   |
| 2012    | 8         | 3.86%   |
| 2022    | 7         | 3.38%   |
| 2016    | 7         | 3.38%   |
| 2015    | 7         | 3.38%   |
| 2014    | 5         | 2.42%   |
| 2013    | 5         | 2.42%   |
| Unknown | 5         | 2.42%   |
| 2011    | 4         | 1.93%   |
| 2008    | 2         | 0.97%   |
| 2006    | 2         | 0.97%   |
| 2010    | 1         | 0.48%   |
| 2009    | 1         | 0.48%   |
| 2007    | 1         | 0.48%   |
| 2005    | 1         | 0.48%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 99        | 47.83%  |
| Desktop        | 84        | 40.58%  |
| Server         | 10        | 4.83%   |
| Convertible    | 7         | 3.38%   |
| System on chip | 2         | 0.97%   |
| Mini pc        | 2         | 0.97%   |
| Phone          | 1         | 0.48%   |
| Stick pc       | 1         | 0.48%   |
| Tablet         | 1         | 0.48%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 203       | 97.13%  |
| Enabled  | 6         | 2.87%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 205       | 99.03%  |
| Yes  | 2         | 0.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 59        | 28.5%   |
| 16.01-24.0  | 43        | 20.77%  |
| 8.01-16.0   | 32        | 15.46%  |
| 64.01-256.0 | 28        | 13.53%  |
| 4.01-8.0    | 23        | 11.11%  |
| 3.01-4.0    | 7         | 3.38%   |
| 24.01-32.0  | 7         | 3.38%   |
| 2.01-3.0    | 4         | 1.93%   |
| 0.51-1.0    | 3         | 1.45%   |
| 1.01-2.0    | 1         | 0.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 59        | 25.54%  |
| 1.01-2.0   | 42        | 18.18%  |
| 2.01-3.0   | 32        | 13.85%  |
| 8.01-16.0  | 32        | 13.85%  |
| 3.01-4.0   | 31        | 13.42%  |
| 0.51-1.0   | 15        | 6.49%   |
| 16.01-24.0 | 8         | 3.46%   |
| 0.01-0.5   | 7         | 3.03%   |
| 32.01-64.0 | 2         | 0.87%   |
| 24.01-32.0 | 2         | 0.87%   |
| 0          | 1         | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 89        | 42.38%  |
| 2      | 57        | 27.14%  |
| 3      | 25        | 11.9%   |
| 4      | 14        | 6.67%   |
| 5      | 12        | 5.71%   |
| 6      | 7         | 3.33%   |
| 7      | 4         | 1.9%    |
| 26     | 1         | 0.48%   |
| 12     | 1         | 0.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 176       | 84.21%  |
| Yes       | 33        | 15.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 165       | 79.33%  |
| No        | 43        | 20.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 152       | 73.08%  |
| No        | 56        | 26.92%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 145       | 68.72%  |
| No        | 66        | 31.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 46        | 22.12%  |
| Germany     | 27        | 12.98%  |
| Russia      | 16        | 7.69%   |
| Poland      | 12        | 5.77%   |
| UK          | 10        | 4.81%   |
| China       | 10        | 4.81%   |
| France      | 8         | 3.85%   |
| Spain       | 7         | 3.37%   |
| Switzerland | 5         | 2.4%    |
| Greece      | 5         | 2.4%    |
| Australia   | 5         | 2.4%    |
| Finland     | 4         | 1.92%   |
| Czechia     | 4         | 1.92%   |
| Belarus     | 4         | 1.92%   |
| Sweden      | 3         | 1.44%   |
| Romania     | 3         | 1.44%   |
| Netherlands | 3         | 1.44%   |
| Mexico      | 3         | 1.44%   |
| India       | 3         | 1.44%   |
| Hong Kong   | 3         | 1.44%   |
| Canada      | 3         | 1.44%   |
| Turkey      | 2         | 0.96%   |
| Taiwan      | 2         | 0.96%   |
| Slovakia    | 2         | 0.96%   |
| Italy       | 2         | 0.96%   |
| Argentina   | 2         | 0.96%   |
| Uruguay     | 1         | 0.48%   |
| Ukraine     | 1         | 0.48%   |
| Tunisia     | 1         | 0.48%   |
| Slovenia    | 1         | 0.48%   |
| Philippines | 1         | 0.48%   |
| Norway      | 1         | 0.48%   |
| New Zealand | 1         | 0.48%   |
| Malaysia    | 1         | 0.48%   |
| Japan       | 1         | 0.48%   |
| Ireland     | 1         | 0.48%   |
| Brazil      | 1         | 0.48%   |
| Belgium     | 1         | 0.48%   |
| Bangladesh  | 1         | 0.48%   |
| Austria     | 1         | 0.48%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Moscow         | 5         | 2.35%   |
| Cieszyn        | 5         | 2.35%   |
| Foshan         | 4         | 1.88%   |
| Warsaw         | 3         | 1.41%   |
| Sydney         | 3         | 1.41%   |
| Swansea        | 3         | 1.41%   |
| Sterling       | 3         | 1.41%   |
| Minsk          | 3         | 1.41%   |
| Los Angeles    | 3         | 1.41%   |
| Central        | 3         | 1.41%   |
| Athens         | 3         | 1.41%   |
| Zurich         | 2         | 0.94%   |
| Yekaterinburg  | 2         | 0.94%   |
| Troisdorf      | 2         | 0.94%   |
| Trnava         | 2         | 0.94%   |
| Seattle        | 2         | 0.94%   |
| Rostock        | 2         | 0.94%   |
| Prague         | 2         | 0.94%   |
| Postbauer-Heng | 2         | 0.94%   |
| Paris          | 2         | 0.94%   |
| Ocala          | 2         | 0.94%   |
| Nuremberg      | 2         | 0.94%   |
| Munich         | 2         | 0.94%   |
| Milan          | 2         | 0.94%   |
| Kulmbach       | 2         | 0.94%   |
| Kallithea      | 2         | 0.94%   |
| Hyderabad      | 2         | 0.94%   |
| Houston        | 2         | 0.94%   |
| Guangzhou      | 2         | 0.94%   |
| Croydon        | 2         | 0.94%   |
| Cluj-Napoca    | 2         | 0.94%   |
| Cherry Hill    | 2         | 0.94%   |
| Berlin         | 2         | 0.94%   |
| Barcelona      | 2         | 0.94%   |
| Zacapu         | 1         | 0.47%   |
| Yunlin         | 1         | 0.47%   |
| Wrentham       | 1         | 0.47%   |
| Winston-Salem  | 1         | 0.47%   |
| West Orange    | 1         | 0.47%   |
| Warren         | 1         | 0.47%   |
| Vladivostok    | 1         | 0.47%   |
| Vigo           | 1         | 0.47%   |
| Vienna         | 1         | 0.47%   |
| Vantaa         | 1         | 0.47%   |
| Vancouver      | 1         | 0.47%   |
| Utrecht        | 1         | 0.47%   |
| Ufa            | 1         | 0.47%   |
| Tunis          | 1         | 0.47%   |
| Thibodaux      | 1         | 0.47%   |
| Texas City     | 1         | 0.47%   |
| Tampere        | 1         | 0.47%   |
| Taichung City  | 1         | 0.47%   |
| Taby           | 1         | 0.47%   |
| Svobodnyy      | 1         | 0.47%   |
| Sundsvall      | 1         | 0.47%   |
| Storsteinnes   | 1         | 0.47%   |
| Stasi Las      | 1         | 0.47%   |
| St. Cloud      | 1         | 0.47%   |
| St Louis       | 1         | 0.47%   |
| Shenzhen       | 1         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 77        | 148    | 21.57%  |
| WDC                            | 68        | 123    | 19.05%  |
| Seagate                        | 38        | 76     | 10.64%  |
| Toshiba                        | 18        | 31     | 5.04%   |
| Intel                          | 18        | 22     | 5.04%   |
| SanDisk                        | 16        | 19     | 4.48%   |
| SK hynix                       | 14        | 15     | 3.92%   |
| Crucial                        | 14        | 29     | 3.92%   |
| Kingston                       | 10        | 11     | 2.8%    |
| Hitachi                        | 10        | 22     | 2.8%    |
| Unknown                        | 8         | 14     | 2.24%   |
| HGST                           | 7         | 9      | 1.96%   |
| Micron Technology              | 6         | 6      | 1.68%   |
| A-DATA Technology              | 6         | 7      | 1.68%   |
| Phison                         | 5         | 7      | 1.4%    |
| KIOXIA-EXCERIA                 | 4         | 7      | 1.12%   |
| Corsair                        | 4         | 5      | 1.12%   |
| Team                           | 3         | 6      | 0.84%   |
| OCZ                            | 3         | 3      | 0.84%   |
| GOODRAM                        | 3         | 7      | 0.84%   |
| Silicon Motion                 | 2         | 3      | 0.56%   |
| Plextor                        | 2         | 3      | 0.56%   |
| KIOXIA                         | 2         | 3      | 0.56%   |
| Kingchuxing                    | 2         | 5      | 0.56%   |
| Fujitsu                        | 2         | 2      | 0.56%   |
| Apacer                         | 2         | 2      | 0.56%   |
| XrayDisk                       | 1         | 1      | 0.28%   |
| Transcend                      | 1         | 1      | 0.28%   |
| T-FORCE                        | 1         | 1      | 0.28%   |
| Super Talent                   | 1         | 1      | 0.28%   |
| Solid State Storage Technology | 1         | 1      | 0.28%   |
| PNY                            | 1         | 1      | 0.28%   |
| OCZ-VERTEX                     | 1         | 1      | 0.28%   |
| Netac                          | 1         | 1      | 0.28%   |
| LITEON                         | 1         | 1      | 0.28%   |
| LaCie                          | 1         | 2      | 0.28%   |
| Hoodisk                        | 1         | 1      | 0.28%   |
| AMD                            | 1         | 1      | 0.28%   |
| 2.5"                           | 1         | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 970 EVO 500GB              | 6         | 1.39%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 4         | 0.93%   |
| Samsung SSD 980 PRO 2TB                | 4         | 0.93%   |
| Samsung SSD 970 PRO 1TB                | 4         | 0.93%   |
| Samsung SSD 970 EVO 250GB              | 4         | 0.93%   |
| Samsung SSD 870 EVO 1TB                | 4         | 0.93%   |
| Intel SSDPEKNW010T8 1TB                | 4         | 0.93%   |
| Crucial CT2000MX500SSD1 2TB            | 4         | 0.93%   |
| WDC WDS500G2B0C-00PXH0 500GB           | 3         | 0.69%   |
| WDC WD10EZEX-08M2NA0 1TB               | 3         | 0.69%   |
| Unknown MMC Card  128GB                | 3         | 0.69%   |
| Toshiba KXG6AZNV512G 512GB             | 3         | 0.69%   |
| Toshiba DT01ACA100 1TB                 | 3         | 0.69%   |
| Seagate ST4000DM004-2CV104 4TB         | 3         | 0.69%   |
| Seagate ST2000DM006-2DM164 2TB         | 3         | 0.69%   |
| Samsung SSD 980 PRO 500GB              | 3         | 0.69%   |
| Samsung SSD 980 1TB                    | 3         | 0.69%   |
| Samsung SSD 970 EVO Plus 500GB         | 3         | 0.69%   |
| Samsung SSD 970 EVO Plus 2TB           | 3         | 0.69%   |
| Samsung SSD 970 EVO Plus 1TB           | 3         | 0.69%   |
| Samsung SSD 860 PRO 4TB                | 3         | 0.69%   |
| Samsung SSD 850 EVO 500GB              | 3         | 0.69%   |
| Samsung SSD 850 EVO 250GB              | 3         | 0.69%   |
| Intel SSDPEKNU512GZ 512GB              | 3         | 0.69%   |
| Crucial CT1000MX500SSD1 1TB            | 3         | 0.69%   |
| WDC WDS500G3X0C-00SJG0 500GB           | 2         | 0.46%   |
| WDC WD40EZRZ-00GXCB0 4TB               | 2         | 0.46%   |
| WDC WD30EFRX-68EUZN0 3TB               | 2         | 0.46%   |
| WDC WD30EFRX-68AX9N0 3TB               | 2         | 0.46%   |
| WDC WD2500BEVS-22UST0 250GB            | 2         | 0.46%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB   | 2         | 0.46%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB   | 2         | 0.46%   |
| Unknown MMC Card  64GB                 | 2         | 0.46%   |
| Team TM8PS7256G 256GB SSD              | 2         | 0.46%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB | 2         | 0.46%   |
| SK hynix PC711 NVMe 512GB              | 2         | 0.46%   |
| SK hynix PC611 NVMe 512GB              | 2         | 0.46%   |
| Seagate ST4000DM005-2DP166 4TB         | 2         | 0.46%   |
| Seagate ST2000LX001-1RG174 2TB         | 2         | 0.46%   |
| Seagate ST2000LM015-2E8174 2TB         | 2         | 0.46%   |
| Seagate ST2000DM001-1ER164 2TB         | 2         | 0.46%   |
| Seagate ST2000DM001-1CH164 2TB         | 2         | 0.46%   |
| SanDisk NVMe SSD Drive 500GB           | 2         | 0.46%   |
| Samsung SSD 980 PRO 1TB                | 2         | 0.46%   |
| Samsung SSD 970 EVO Plus 250GB         | 2         | 0.46%   |
| Samsung SSD 970 EVO 1TB                | 2         | 0.46%   |
| Samsung SSD 870 EVO 500GB              | 2         | 0.46%   |
| Samsung SSD 860 QVO 2TB                | 2         | 0.46%   |
| Samsung SSD 860 QVO 1TB                | 2         | 0.46%   |
| Samsung SSD 850 PRO 256GB              | 2         | 0.46%   |
| Samsung SSD 840 PRO Series 128GB       | 2         | 0.46%   |
| Samsung NVMe SSD Drive 512GB           | 2         | 0.46%   |
| Samsung NVMe SSD Drive 500GB           | 2         | 0.46%   |
| Samsung NVMe SSD Drive 2TB             | 2         | 0.46%   |
| Samsung NVMe SSD Drive 1TB             | 2         | 0.46%   |
| Samsung MZVLB512HBJQ-000L2 512GB       | 2         | 0.46%   |
| Samsung MZALQ512HALU-000L2 512GB       | 2         | 0.46%   |
| Phison Sabrent Rocket 4.0 1TB          | 2         | 0.46%   |
| KIOXIA-EXCERIA SSD 500GB               | 2         | 0.46%   |
| Kingston SA400S37240G 240GB SSD        | 2         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 39        | 87     | 36.79%  |
| Seagate | 35        | 72     | 33.02%  |
| Toshiba | 12        | 20     | 11.32%  |
| Hitachi | 10        | 22     | 9.43%   |
| HGST    | 7         | 9      | 6.6%    |
| Fujitsu | 2         | 2      | 1.89%   |
| LaCie   | 1         | 2      | 0.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 36        | 56     | 34.29%  |
| SanDisk             | 12        | 15     | 11.43%  |
| Crucial             | 11        | 25     | 10.48%  |
| WDC                 | 8         | 10     | 7.62%   |
| Kingston            | 7         | 8      | 6.67%   |
| Intel               | 4         | 4      | 3.81%   |
| OCZ                 | 3         | 3      | 2.86%   |
| GOODRAM             | 3         | 7      | 2.86%   |
| Corsair             | 3         | 4      | 2.86%   |
| A-DATA Technology   | 3         | 3      | 2.86%   |
| Toshiba             | 2         | 3      | 1.9%    |
| Team                | 2         | 3      | 1.9%    |
| XrayDisk            | 1         | 1      | 0.95%   |
| Transcend           | 1         | 1      | 0.95%   |
| Super Talent        | 1         | 1      | 0.95%   |
| SK hynix            | 1         | 1      | 0.95%   |
| PNY                 | 1         | 1      | 0.95%   |
| Plextor             | 1         | 1      | 0.95%   |
| OCZ-VERTEX          | 1         | 1      | 0.95%   |
| Kingchuxing         | 1         | 1      | 0.95%   |
| Hoodisk             | 1         | 1      | 0.95%   |
| Apacer              | 1         | 1      | 0.95%   |
| 2.5"                | 1         | 1      | 0.95%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 141       | 219    | 44.34%  |
| SSD     | 86        | 152    | 27.04%  |
| HDD     | 83        | 214    | 26.1%   |
| MMC     | 6         | 10     | 1.89%   |
| Unknown | 2         | 4      | 0.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 141       | 219    | 50.36%  |
| SATA | 129       | 360    | 46.07%  |
| MMC  | 6         | 10     | 2.14%   |
| SAS  | 4         | 10     | 1.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 69        | 120    | 35.03%  |
| 0.51-1.0   | 57        | 75     | 28.93%  |
| 1.01-2.0   | 33        | 73     | 16.75%  |
| 3.01-4.0   | 16        | 23     | 8.12%   |
| 4.01-10.0  | 12        | 49     | 6.09%   |
| 2.01-3.0   | 7         | 19     | 3.55%   |
| 10.01-20.0 | 3         | 7      | 1.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 45        | 21.13%  |
| 501-1000       | 37        | 17.37%  |
| 101-250        | 32        | 15.02%  |
| More than 3000 | 25        | 11.74%  |
| 1001-2000      | 25        | 11.74%  |
| 2001-3000      | 17        | 7.98%   |
| Unknown        | 11        | 5.16%   |
| 1-20           | 10        | 4.69%   |
| 21-50          | 6         | 2.82%   |
| 51-100         | 5         | 2.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 42        | 19.35%  |
| 101-250        | 30        | 13.82%  |
| 251-500        | 29        | 13.36%  |
| 21-50          | 28        | 12.9%   |
| 1001-2000      | 22        | 10.14%  |
| 51-100         | 19        | 8.76%   |
| 501-1000       | 18        | 8.29%   |
| More than 3000 | 14        | 6.45%   |
| Unknown        | 11        | 5.07%   |
| 2001-3000      | 4         | 1.84%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB              | 1         | 3      | 2.56%   |
| WDC WD40EFRX-68N32N0 4TB              | 1         | 1      | 2.56%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1         | 2      | 2.56%   |
| WDC WD20EZRX-00D8PB0 2TB              | 1         | 1      | 2.56%   |
| WDC WD20EFRX-68AX9N0 2TB              | 1         | 1      | 2.56%   |
| WDC WD20EARS-00J2GB0 2TB              | 1         | 1      | 2.56%   |
| WDC WD1600BEVS-22RST0 160GB           | 1         | 1      | 2.56%   |
| WDC WD10EZEX-08M2NA0 1TB              | 1         | 2      | 2.56%   |
| WDC WD10EFRX-68JCSN0 1TB              | 1         | 1      | 2.56%   |
| WDC WD1002FBYS-18W8B0 1TB             | 1         | 1      | 2.56%   |
| Transcend TS512GSSD720 512GB          | 1         | 1      | 2.56%   |
| Toshiba MK6008GAH 64GB                | 1         | 2      | 2.56%   |
| Toshiba HDWA120 2TB                   | 1         | 1      | 2.56%   |
| Seagate ST320LM010-1KJ15C 320GB       | 1         | 1      | 2.56%   |
| Seagate ST3160023AS 160GB             | 1         | 1      | 2.56%   |
| Seagate ST2000DX001-1CM164 2TB        | 1         | 1      | 2.56%   |
| Seagate ST1000LM049-2GH172 1TB        | 1         | 1      | 2.56%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 2      | 2.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 2.56%   |
| Seagate ST10000VN0004-1ZD101 10TB     | 1         | 4      | 2.56%   |
| SanDisk SSD PLUS 1000GB               | 1         | 1      | 2.56%   |
| Samsung Electronics SSD 980 PRO 2TB   | 1         | 1      | 2.56%   |
| Samsung Electronics SSD 980 1TB       | 1         | 1      | 2.56%   |
| Samsung Electronics SSD 970 EVO 1TB   | 1         | 2      | 2.56%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 2.56%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 2.56%   |
| Samsung Electronics SSD 850 PRO 256GB | 1         | 4      | 2.56%   |
| OCZ VERTEX4 128GB SSD                 | 1         | 1      | 2.56%   |
| Kingston SV100S2128G 128GB SSD        | 1         | 1      | 2.56%   |
| Intel SSDPEKKF256G8L 256GB            | 1         | 1      | 2.56%   |
| Hitachi HUA721010KLA330 1TB           | 1         | 1      | 2.56%   |
| Hitachi HTS541680J9SA00 80GB          | 1         | 1      | 2.56%   |
| Hitachi HDS722020ALA330 2TB           | 1         | 2      | 2.56%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 2.56%   |
| Fujitsu MHW2040AT 40GB                | 1         | 1      | 2.56%   |
| Crucial CT525MX300SSD1 528GB          | 1         | 1      | 2.56%   |
| Crucial CT1000P1SSD8 1TB              | 1         | 1      | 2.56%   |
| A-DATA Technology SP550 240GB SSD     | 1         | 1      | 2.56%   |
| 2.5" SATA SSD 3TG6-P 480GB            | 1         | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 14     | 25.64%  |
| Seagate             | 7         | 11     | 17.95%  |
| Samsung Electronics | 6         | 10     | 15.38%  |
| Hitachi             | 3         | 4      | 7.69%   |
| Toshiba             | 2         | 3      | 5.13%   |
| Crucial             | 2         | 2      | 5.13%   |
| Transcend           | 1         | 1      | 2.56%   |
| SanDisk             | 1         | 1      | 2.56%   |
| OCZ                 | 1         | 1      | 2.56%   |
| Kingston            | 1         | 1      | 2.56%   |
| Intel               | 1         | 1      | 2.56%   |
| HGST                | 1         | 1      | 2.56%   |
| Fujitsu             | 1         | 1      | 2.56%   |
| A-DATA Technology   | 1         | 1      | 2.56%   |
| 2.5"                | 1         | 1      | 2.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 10        | 14     | 41.67%  |
| Seagate | 7         | 11     | 29.17%  |
| Hitachi | 3         | 4      | 12.5%   |
| Toshiba | 2         | 3      | 8.33%   |
| HGST    | 1         | 1      | 4.17%   |
| Fujitsu | 1         | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 34     | 59.46%  |
| SSD  | 10        | 13     | 27.03%  |
| NVMe | 5         | 6      | 13.51%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 187       | 494    | 77.27%  |
| Malfunc  | 35        | 53     | 14.46%  |
| Detected | 19        | 51     | 7.85%   |
| Failed   | 1         | 1      | 0.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 104       | 31.52%  |
| AMD                            | 63        | 19.09%  |
| Samsung Electronics            | 58        | 17.58%  |
| SanDisk                        | 28        | 8.48%   |
| SK hynix                       | 13        | 3.94%   |
| Phison Electronics             | 9         | 2.73%   |
| ASMedia Technology             | 9         | 2.73%   |
| Micron Technology              | 7         | 2.12%   |
| Toshiba America Info Systems   | 6         | 1.82%   |
| Silicon Motion                 | 5         | 1.52%   |
| KIOXIA                         | 5         | 1.52%   |
| Seagate Technology             | 3         | 0.91%   |
| Marvell Technology Group       | 3         | 0.91%   |
| Kingston Technology Company    | 3         | 0.91%   |
| ADATA Technology               | 3         | 0.91%   |
| Solid State Storage Technology | 2         | 0.61%   |
| Micron/Crucial Technology      | 2         | 0.61%   |
| Broadcom / LSI                 | 2         | 0.61%   |
| Unknown                        | 1         | 0.3%    |
| Silicon Image                  | 1         | 0.3%    |
| LSI Logic / Symbios Logic      | 1         | 0.3%    |
| Lite-On Technology             | 1         | 0.3%    |
| JMicron Technology             | 1         | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 48        | 13.26%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 36        | 9.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 14        | 3.87%   |
| AMD 400 Series Chipset SATA Controller                                         | 11        | 3.04%   |
| SK hynix Gold P31 SSD                                                          | 10        | 2.76%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 10        | 2.76%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 9         | 2.49%   |
| AMD 500 Series Chipset SATA Controller                                         | 9         | 2.49%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 2.21%   |
| Intel Comet Lake SATA AHCI Controller                                          | 8         | 2.21%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 8         | 2.21%   |
| Micron Non-Volatile memory controller                                          | 7         | 1.93%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 1.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 7         | 1.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 1.93%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 6         | 1.66%   |
| Samsung NVMe SSD Controller 980                                                | 6         | 1.66%   |
| Intel SSD 660P Series                                                          | 6         | 1.66%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 1.66%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 1.38%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 4         | 1.1%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 4         | 1.1%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 4         | 1.1%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.1%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 4         | 1.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 1.1%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 3         | 0.83%   |
| SanDisk Non-Volatile memory controller                                         | 3         | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.83%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3         | 0.83%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.83%   |
| KIOXIA NVMe SSD                                                                | 3         | 0.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 0.83%   |
| Intel Non-Volatile memory controller                                           | 3         | 0.83%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 0.83%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3         | 0.83%   |
| Solid State Storage Non-Volatile memory controller                             | 2         | 0.55%   |
| SK hynix Non-Volatile memory controller                                        | 2         | 0.55%   |
| Seagate FireCuda 520 SSD                                                       | 2         | 0.55%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 0.55%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 2         | 0.55%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 2         | 0.55%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 0.55%   |
| Phison E7 NVMe Controller                                                      | 2         | 0.55%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2         | 0.55%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 2         | 0.55%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 2         | 0.55%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2         | 0.55%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 0.55%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 0.55%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 0.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 0.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 0.55%   |
| AMD X370 Series Chipset SATA Controller                                        | 2         | 0.55%   |
| Unknown Non-Volatile memory controller                                         | 1         | 0.28%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 0.28%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 0.28%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.28%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.28%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 0.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 142       | 46.1%   |
| NVMe | 141       | 45.78%  |
| RAID | 11        | 3.57%   |
| IDE  | 11        | 3.57%   |
| SAS  | 3         | 0.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 120       | 57.97%  |
| AMD                   | 82        | 39.61%  |
| ARM                   | 3         | 1.45%   |
| PowerBook6,7          | 1         | 0.48%   |
| Marvell Semiconductor | 1         | 0.48%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen 9 5900X 12-Core Processor                                      | 5         | 2.42%   |
| Intel Core i7-8750H CPU @ 2.20GHz                                        | 4         | 1.93%   |
| Intel Core i5-10210U CPU @ 1.60GHz                                       | 4         | 1.93%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz                                  | 4         | 1.93%   |
| AMD Ryzen 9 5950X 16-Core Processor                                      | 4         | 1.93%   |
| AMD Ryzen 9 3950X 16-Core Processor                                      | 4         | 1.93%   |
| AMD Ryzen 7 5800H with Radeon Graphics                                   | 4         | 1.93%   |
| AMD Ryzen 7 5700U with Radeon Graphics                                   | 4         | 1.93%   |
| AMD Ryzen 5 2600 Six-Core Processor                                      | 4         | 1.93%   |
| Intel Core i7-6700K CPU @ 4.00GHz                                        | 3         | 1.45%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz                                  | 3         | 1.45%   |
| ARM Processor                                                            | 3         | 1.45%   |
| AMD Ryzen 9 5900HX with Radeon Graphics                                  | 3         | 1.45%   |
| AMD Ryzen 9 3900X 12-Core Processor                                      | 3         | 1.45%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics                               | 3         | 1.45%   |
| AMD Ryzen 7 4800H with Radeon Graphics                                   | 3         | 1.45%   |
| AMD Ryzen 5 3600 6-Core Processor                                        | 3         | 1.45%   |
| Intel Xeon CPU X5680 @ 3.33GHz                                           | 2         | 0.97%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz                                      | 2         | 0.97%   |
| Intel Core i9-9900K CPU @ 3.60GHz                                        | 2         | 0.97%   |
| Intel Core i7-9750H CPU @ 2.60GHz                                        | 2         | 0.97%   |
| Intel Core i7-8700K CPU @ 3.70GHz                                        | 2         | 0.97%   |
| Intel Core i7-8565U CPU @ 1.80GHz                                        | 2         | 0.97%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz                                       | 2         | 0.97%   |
| Intel Core i7-10850H CPU @ 2.70GHz                                       | 2         | 0.97%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz                                       | 2         | 0.97%   |
| Intel Core i7-10510U CPU @ 1.80GHz                                       | 2         | 0.97%   |
| Intel Core i5-9600K CPU @ 3.70GHz                                        | 2         | 0.97%   |
| Intel Core i5-9300H CPU @ 2.40GHz                                        | 2         | 0.97%   |
| Intel Core i5-8300H CPU @ 2.30GHz                                        | 2         | 0.97%   |
| Intel 12th Gen Core i9-12900K                                            | 2         | 0.97%   |
| Intel 12th Gen Core i7-12700K                                            | 2         | 0.97%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz                                  | 2         | 0.97%   |
| AMD Ryzen 7 3700X 8-Core Processor                                       | 2         | 0.97%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx                            | 2         | 0.97%   |
| AMD Ryzen 7 2700X Eight-Core Processor                                   | 2         | 0.97%   |
| AMD Ryzen 5 5600H with Radeon Graphics                                   | 2         | 0.97%   |
| AMD Ryzen 5 1600 Six-Core Processor                                      | 2         | 0.97%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx                            | 2         | 0.97%   |
| AMD E1-1200 APU with Radeon HD Graphics                                  | 2         | 0.97%   |
| PowerBook6,7 7447A, altivec supported                                    | 1         | 0.48%   |
| Marvell Semiconductor Marvell Kirkwood (Flattened Device Tree) Processor | 1         | 0.48%   |
| Intel Xeon E-2314 CPU @ 2.80GHz                                          | 1         | 0.48%   |
| Intel Xeon CPU X5690 @ 3.47GHz                                           | 1         | 0.48%   |
| Intel Xeon CPU E5335 @ 2.00GHz                                           | 1         | 0.48%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz                                      | 1         | 0.48%   |
| Intel Xeon CPU E3-1275 v6 @ 3.80GHz                                      | 1         | 0.48%   |
| Intel Pentium M processor 1400MHz                                        | 1         | 0.48%   |
| Intel Pentium 4 CPU 3.20GHz                                              | 1         | 0.48%   |
| Intel Core i9-9880H CPU @ 2.30GHz                                        | 1         | 0.48%   |
| Intel Core i9-8950HK CPU @ 2.90GHz                                       | 1         | 0.48%   |
| Intel Core i7-9700 CPU @ 3.00GHz                                         | 1         | 0.48%   |
| Intel Core i7-8809G CPU @ 3.10GHz                                        | 1         | 0.48%   |
| Intel Core i7-8650U CPU @ 1.90GHz                                        | 1         | 0.48%   |
| Intel Core i7-8086K CPU @ 4.00GHz                                        | 1         | 0.48%   |
| Intel Core i7-7820HK CPU @ 2.90GHz                                       | 1         | 0.48%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz                                       | 1         | 0.48%   |
| Intel Core i7-7500U CPU @ 2.70GHz                                        | 1         | 0.48%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz                                       | 1         | 0.48%   |
| Intel Core i7-6500U CPU @ 2.50GHz                                        | 1         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 39        | 18.84%  |
| Intel Core i5          | 33        | 15.94%  |
| Other                  | 31        | 14.98%  |
| AMD Ryzen 7            | 23        | 11.11%  |
| AMD Ryzen 9            | 21        | 10.14%  |
| AMD Ryzen 5            | 19        | 9.18%   |
| Intel Xeon             | 9         | 4.35%   |
| AMD Ryzen 7 PRO        | 6         | 2.9%    |
| Intel Core i9          | 4         | 1.93%   |
| Intel Core i3          | 3         | 1.45%   |
| AMD Ryzen Threadripper | 3         | 1.45%   |
| AMD Ryzen 3            | 3         | 1.45%   |
| Intel Atom             | 2         | 0.97%   |
| AMD E1                 | 2         | 0.97%   |
| Intel Pentium M        | 1         | 0.48%   |
| Intel Pentium 4        | 1         | 0.48%   |
| Intel Core Duo         | 1         | 0.48%   |
| Intel Celeron          | 1         | 0.48%   |
| AMD Sempron            | 1         | 0.48%   |
| AMD Ryzen 5 PRO        | 1         | 0.48%   |
| AMD Phenom II X4       | 1         | 0.48%   |
| AMD FX                 | 1         | 0.48%   |
| AMD EPYC               | 1         | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 61        | 29.47%  |
| 8       | 48        | 23.19%  |
| 6       | 40        | 19.32%  |
| 2       | 23        | 11.11%  |
| 12      | 15        | 7.25%   |
| 16      | 11        | 5.31%   |
| 1       | 6         | 2.9%    |
| 24      | 1         | 0.48%   |
| 14      | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 203       | 98.07%  |
| 2       | 3         | 1.45%   |
| Unknown | 1         | 0.48%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 177       | 85.1%   |
| 1       | 30        | 14.42%  |
| Unknown | 1         | 0.48%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 201       | 97.1%   |
| 32-bit         | 5         | 2.42%   |
| Unknown        | 1         | 0.48%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 11.96%  |
| 0x0a50000c | 14        | 6.7%    |
| 0x906ea    | 13        | 6.22%   |
| 0x08701021 | 10        | 4.78%   |
| 0x806ec    | 9         | 4.31%   |
| 0x806c1    | 7         | 3.35%   |
| 0x506e3    | 7         | 3.35%   |
| 0x0a201016 | 7         | 3.35%   |
| 0x806d1    | 6         | 2.87%   |
| 0x306c3    | 6         | 2.87%   |
| 0xa0671    | 5         | 2.39%   |
| 0x906ed    | 5         | 2.39%   |
| 0x90672    | 5         | 2.39%   |
| 0x08600106 | 5         | 2.39%   |
| 0x0800820d | 5         | 2.39%   |
| 0x906e9    | 4         | 1.91%   |
| 0x806e9    | 4         | 1.91%   |
| 0x206a7    | 4         | 1.91%   |
| 0x08608103 | 4         | 1.91%   |
| 0x08108109 | 4         | 1.91%   |
| 0xa0652    | 3         | 1.44%   |
| 0x306d4    | 3         | 1.44%   |
| 0x306a9    | 3         | 1.44%   |
| 0x206c2    | 3         | 1.44%   |
| 0x08600103 | 3         | 1.44%   |
| 0x08001138 | 3         | 1.44%   |
| 0xa0655    | 2         | 0.96%   |
| 0xa0653    | 2         | 0.96%   |
| 0x906a3    | 2         | 0.96%   |
| 0x706e5    | 2         | 0.96%   |
| 0x406e3    | 2         | 0.96%   |
| 0x0a404102 | 2         | 0.96%   |
| 0x0a201204 | 2         | 0.96%   |
| 0x08301039 | 2         | 0.96%   |
| 0x05000119 | 2         | 0.96%   |
| 0xf43      | 1         | 0.48%   |
| 0xa0660    | 1         | 0.48%   |
| 0x906ec    | 1         | 0.48%   |
| 0x806eb    | 1         | 0.48%   |
| 0x806ea    | 1         | 0.48%   |
| 0x806c2    | 1         | 0.48%   |
| 0x706a8    | 1         | 0.48%   |
| 0x6f7      | 1         | 0.48%   |
| 0x6ec      | 1         | 0.48%   |
| 0x40651    | 1         | 0.48%   |
| 0x306f2    | 1         | 0.48%   |
| 0x306e4    | 1         | 0.48%   |
| 0x0a50000b | 1         | 0.48%   |
| 0x0a404101 | 1         | 0.48%   |
| 0x0a201205 | 1         | 0.48%   |
| 0x0a201009 | 1         | 0.48%   |
| 0x08608102 | 1         | 0.48%   |
| 0x08600102 | 1         | 0.48%   |
| 0x0830104d | 1         | 0.48%   |
| 0x08108102 | 1         | 0.48%   |
| 0x08001137 | 1         | 0.48%   |
| 0x08001105 | 1         | 0.48%   |
| 0x0700010f | 1         | 0.48%   |
| 0x010000db | 1         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 41        | 19.62%  |
| Zen 3            | 26        | 12.44%  |
| Zen 2            | 26        | 12.44%  |
| Unknown          | 15        | 7.18%   |
| Icelake          | 14        | 6.7%    |
| Zen+             | 12        | 5.74%   |
| Skylake          | 10        | 4.78%   |
| TigerLake        | 9         | 4.31%   |
| Haswell          | 9         | 4.31%   |
| CometLake        | 8         | 3.83%   |
| Alderlake Hybrid | 7         | 3.35%   |
| Zen              | 5         | 2.39%   |
| SandyBridge      | 5         | 2.39%   |
| IvyBridge        | 4         | 1.91%   |
| Westmere         | 3         | 1.44%   |
| Broadwell        | 3         | 1.44%   |
| P6               | 2         | 0.96%   |
| Bonnell          | 2         | 0.96%   |
| Bobcat           | 2         | 0.96%   |
| Piledriver       | 1         | 0.48%   |
| NetBurst         | 1         | 0.48%   |
| K10              | 1         | 0.48%   |
| Jaguar           | 1         | 0.48%   |
| Goldmont plus    | 1         | 0.48%   |
| Core             | 1         | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| AMD                        | 86        | 34.82%  |
| Intel                      | 79        | 31.98%  |
| Nvidia                     | 77        | 31.17%  |
| Matrox Electronics Systems | 3         | 1.21%   |
| ASPEED Technology          | 2         | 0.81%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 20        | 7.69%   |
| AMD Cezanne                                                                   | 13        | 5%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 10        | 3.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 9         | 3.46%   |
| AMD Renoir                                                                    | 8         | 3.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 7         | 2.69%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 6         | 2.31%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 5         | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 5         | 1.92%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                | 5         | 1.92%   |
| AMD Lucienne                                                                  | 5         | 1.92%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 4         | 1.54%   |
| Intel HD Graphics 630                                                         | 4         | 1.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 3         | 1.15%   |
| Nvidia GP108M [GeForce MX250]                                                 | 3         | 1.15%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 3         | 1.15%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 3         | 1.15%   |
| Nvidia GM206 [GeForce GTX 960]                                                | 3         | 1.15%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 3         | 1.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 3         | 1.15%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 1.15%   |
| Intel HD Graphics 5500                                                        | 3         | 1.15%   |
| Intel HD Graphics 530                                                         | 3         | 1.15%   |
| AMD Rembrandt [Radeon 680M]                                                   | 3         | 1.15%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                    | 3         | 1.15%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                          | 3         | 1.15%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 2         | 0.77%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                        | 2         | 0.77%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                        | 2         | 0.77%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                     | 2         | 0.77%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                           | 2         | 0.77%   |
| Nvidia GP104 [GeForce GTX 1080]                                               | 2         | 0.77%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                            | 2         | 0.77%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 2         | 0.77%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                            | 2         | 0.77%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)             | 2         | 0.77%   |
| Intel UHD Graphics 620                                                        | 2         | 0.77%   |
| Intel UHD Graphics 615                                                        | 2         | 0.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 0.77%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 2         | 0.77%   |
| Intel Iris Plus Graphics G7                                                   | 2         | 0.77%   |
| Intel HD Graphics 620                                                         | 2         | 0.77%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 2         | 0.77%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 2         | 0.77%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 2         | 0.77%   |
| Intel AlderLake-S GT1                                                         | 2         | 0.77%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 2         | 0.77%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 2         | 0.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 0.77%   |
| ASPEED Technology ASPEED Graphics Family                                      | 2         | 0.77%   |
| AMD Wrestler [Radeon HD 7310]                                                 | 2         | 0.77%   |
| AMD Navi 23 [Radeon RX 6650 XT]                                               | 2         | 0.77%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 2         | 0.77%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 2         | 0.77%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]           | 2         | 0.77%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 1         | 0.38%   |
| Nvidia TU117M                                                                 | 1         | 0.38%   |
| Nvidia TU117GLM [T600 Mobile]                                                 | 1         | 0.38%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                 | 1         | 0.38%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                            | 1         | 0.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 65        | 31.25%  |
| 1 x Intel      | 41        | 19.71%  |
| 1 x Nvidia     | 40        | 19.23%  |
| Intel + Nvidia | 29        | 13.94%  |
| 2 x AMD        | 9         | 4.33%   |
| AMD + Nvidia   | 8         | 3.85%   |
| Other          | 5         | 2.4%    |
| 2 x Intel      | 3         | 1.44%   |
| 1 x Matrox     | 3         | 1.44%   |
| Intel + AMD    | 3         | 1.44%   |
| 1 x ASPEED     | 1         | 0.48%   |
| AMD + ASPEED   | 1         | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 140       | 67.31%  |
| Proprietary | 55        | 26.44%  |
| Unknown     | 13        | 6.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 92        | 43.19%  |
| 7.01-8.0   | 31        | 14.55%  |
| 3.01-4.0   | 21        | 9.86%   |
| 1.01-2.0   | 15        | 7.04%   |
| 8.01-16.0  | 15        | 7.04%   |
| 0.01-0.5   | 15        | 7.04%   |
| 0.51-1.0   | 11        | 5.16%   |
| 5.01-6.0   | 10        | 4.69%   |
| 2.01-3.0   | 3         | 1.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 29        | 11.65%  |
| BOE                     | 26        | 10.44%  |
| AU Optronics            | 20        | 8.03%   |
| Goldstar                | 19        | 7.63%   |
| Chimei Innolux          | 16        | 6.43%   |
| Dell                    | 11        | 4.42%   |
| LG Display              | 10        | 4.02%   |
| Lenovo                  | 9         | 3.61%   |
| Hewlett-Packard         | 9         | 3.61%   |
| ViewSonic               | 8         | 3.21%   |
| Sharp                   | 8         | 3.21%   |
| AOC                     | 7         | 2.81%   |
| BenQ                    | 6         | 2.41%   |
| ASUSTek Computer        | 6         | 2.41%   |
| Ancor Communications    | 6         | 2.41%   |
| Acer                    | 6         | 2.41%   |
| Iiyama                  | 4         | 1.61%   |
| Eizo                    | 4         | 1.61%   |
| Sceptre Tech            | 3         | 1.2%    |
| Philips                 | 3         | 1.2%    |
| CSO                     | 3         | 1.2%    |
| Unknown                 | 2         | 0.8%    |
| Toshiba                 | 2         | 0.8%    |
| PANDA                   | 2         | 0.8%    |
| NEC Computers           | 2         | 0.8%    |
| MSI                     | 2         | 0.8%    |
| HannStar                | 2         | 0.8%    |
| Chi Mei Optoelectronics | 2         | 0.8%    |
| Unknown                 | 2         | 0.8%    |
| ___                     | 1         | 0.4%    |
| Xiaomi                  | 1         | 0.4%    |
| Valve                   | 1         | 0.4%    |
| Sony                    | 1         | 0.4%    |
| Sceptre                 | 1         | 0.4%    |
| PNP                     | 1         | 0.4%    |
| Onkyo                   | 1         | 0.4%    |
| MXX                     | 1         | 0.4%    |
| MStar                   | 1         | 0.4%    |
| Microstep               | 1         | 0.4%    |
| Mi                      | 1         | 0.4%    |
| LYC                     | 1         | 0.4%    |
| LG Electronics          | 1         | 0.4%    |
| KTC                     | 1         | 0.4%    |
| IOC                     | 1         | 0.4%    |
| InfoVision              | 1         | 0.4%    |
| Gigabyte Technology     | 1         | 0.4%    |
| Gateway                 | 1         | 0.4%    |
| Belinea                 | 1         | 0.4%    |
| Apple                   | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                   | 6         | 2.29%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 2         | 0.76%   |
| Sceptre Tech C305W-2560UN SPT0C0D 2560x1080 690x291mm 29.5-inch         | 2         | 0.76%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 2         | 0.76%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch    | 2         | 0.76%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch            | 2         | 0.76%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch                | 2         | 0.76%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                  | 2         | 0.76%   |
| Eizo CS2731 ENC3069 2560x1440 597x336mm 27.0-inch                       | 2         | 0.76%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch         | 2         | 0.76%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 0.76%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                   | 2         | 0.76%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                   | 2         | 0.76%   |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                   | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch          | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch          | 2         | 0.76%   |
| Unknown                                                                 | 2         | 0.76%   |
| ___ LCDTV16 ___9000 1360x768                                            | 1         | 0.38%   |
| Xiaomi Mi TV XMD0002 1920x1080 708x398mm 32.0-inch                      | 1         | 0.38%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 521x293mm 23.5-inch              | 1         | 0.38%   |
| ViewSonic VX2458 Series VSC36AF 1920x1080 521x293mm 23.5-inch           | 1         | 0.38%   |
| ViewSonic VX2370 SERIES VSC342C 1920x1080 509x286mm 23.0-inch           | 1         | 0.38%   |
| ViewSonic VX2363 Series VSC6B2F 1920x1080 509x286mm 23.0-inch           | 1         | 0.38%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch           | 1         | 0.38%   |
| ViewSonic VG1655 VSCD239 1920x1080 340x190mm 15.3-inch                  | 1         | 0.38%   |
| ViewSonic LCD Monitor VSC2034 2560x1440 600x340mm 27.2-inch             | 1         | 0.38%   |
| ViewSonic LCD Monitor VSC1B35 1920x1080 530x300mm 24.0-inch             | 1         | 0.38%   |
| Valve Index HMD VLV91A8                                                 | 1         | 0.38%   |
| Unknown LCDTV 9000 1360x768 1600x900mm 72.3-inch                        | 1         | 0.38%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 1         | 0.38%   |
| Toshiba PA3552 TOS501C 1680x1050 433x270mm 20.1-inch                    | 1         | 0.38%   |
| Toshiba 32FHD_LCD_TV TSB3700 1920x1080 700x400mm 31.7-inch              | 1         | 0.38%   |
| Sony SDMU27M90*30 SNY075A 3840x2160 596x335mm 26.9-inch                 | 1         | 0.38%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                 | 1         | 0.38%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                 | 1         | 0.38%   |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch                 | 1         | 0.38%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                 | 1         | 0.38%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                 | 1         | 0.38%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch                 | 1         | 0.38%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                  | 1         | 0.38%   |
| Sceptre LCD Monitor C305W-2560UN                                        | 1         | 0.38%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch       | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch    | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM0584 2048x1152 510x290mm 23.1-inch    | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM0194 1280x1024 376x301mm 19.0-inch    | 1         | 0.38%   |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 518x324mm 24.1-inch     | 1         | 0.38%   |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch       | 1         | 0.38%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch       | 1         | 0.38%   |
| Samsung Electronics LF24T450F SAM7096 1920x1080 527x296mm 23.8-inch     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch    | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch    | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch    | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch    | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch   | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4165 3840x2400 344x215mm 16.0-inch   | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC415F 3840x2160 344x194mm 15.5-inch   | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC415D 3840x2400 344x215mm 16.0-inch   | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch   | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1872x1053mm 84.6-inch | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 1020x570mm 46.0-inch  | 1         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 106       | 45.11%  |
| 2560x1440 (QHD)    | 36        | 15.32%  |
| 3840x2160 (4K)     | 24        | 10.21%  |
| 1366x768 (WXGA)    | 11        | 4.68%   |
| 1920x1200 (WUXGA)  | 7         | 2.98%   |
| 3440x1440          | 6         | 2.55%   |
| 1280x1024 (SXGA)   | 6         | 2.55%   |
| 2560x1600          | 5         | 2.13%   |
| Unknown            | 4         | 1.7%    |
| 3840x2400          | 3         | 1.28%   |
| 2560x1080          | 3         | 1.28%   |
| 1440x900 (WXGA+)   | 3         | 1.28%   |
| 3840x1080          | 2         | 0.85%   |
| 2256x1504          | 2         | 0.85%   |
| 1680x1050 (WSXGA+) | 2         | 0.85%   |
| 1600x900 (HD+)     | 2         | 0.85%   |
| 1024x600           | 2         | 0.85%   |
| 7680x2160          | 1         | 0.43%   |
| 6400x1080          | 1         | 0.43%   |
| 3456x2160          | 1         | 0.43%   |
| 2880x1920          | 1         | 0.43%   |
| 2880x1800          | 1         | 0.43%   |
| 2288x1287          | 1         | 0.43%   |
| 2048x1152          | 1         | 0.43%   |
| 1920x1280          | 1         | 0.43%   |
| 1360x768           | 1         | 0.43%   |
| 1280x960           | 1         | 0.43%   |
| 1024x768 (XGA)     | 1         | 0.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 51        | 20.56%  |
| 27      | 42        | 16.94%  |
| 23      | 23        | 9.27%   |
| 13      | 19        | 7.66%   |
| 14      | 18        | 7.26%   |
| 24      | 14        | 5.65%   |
| 17      | 13        | 5.24%   |
| 21      | 12        | 4.84%   |
| Unknown | 9         | 3.63%   |
| 34      | 7         | 2.82%   |
| 16      | 7         | 2.82%   |
| 25      | 4         | 1.61%   |
| 19      | 4         | 1.61%   |
| 84      | 3         | 1.21%   |
| 31      | 3         | 1.21%   |
| 72      | 2         | 0.81%   |
| 49      | 2         | 0.81%   |
| 29      | 2         | 0.81%   |
| 12      | 2         | 0.81%   |
| 10      | 2         | 0.81%   |
| 142     | 1         | 0.4%    |
| 65      | 1         | 0.4%    |
| 54      | 1         | 0.4%    |
| 28      | 1         | 0.4%    |
| 26      | 1         | 0.4%    |
| 22      | 1         | 0.4%    |
| 20      | 1         | 0.4%    |
| 18      | 1         | 0.4%    |
| 8       | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 87        | 37.34%  |
| 501-600        | 68        | 29.18%  |
| 401-500        | 17        | 7.3%    |
| 201-300        | 13        | 5.58%   |
| 351-400        | 12        | 5.15%   |
| 601-700        | 9         | 3.86%   |
| Unknown        | 9         | 3.86%   |
| 701-800        | 7         | 3%      |
| 1501-2000      | 5         | 2.15%   |
| 1001-1500      | 4         | 1.72%   |
| More than 2000 | 1         | 0.43%   |
| 101-200        | 1         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 160       | 75.83%  |
| 16/10   | 23        | 10.9%   |
| 21/9    | 9         | 4.27%   |
| 5/4     | 6         | 2.84%   |
| Unknown | 6         | 2.84%   |
| 3/2     | 3         | 1.42%   |
| 4/3     | 2         | 0.95%   |
| 32/9    | 1         | 0.47%   |
| 1.00    | 1         | 0.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 52        | 21.4%   |
| 301-350        | 43        | 17.7%   |
| 201-250        | 39        | 16.05%  |
| 81-90          | 30        | 12.35%  |
| 351-500        | 11        | 4.53%   |
| More than 1000 | 9         | 3.7%    |
| 251-300        | 9         | 3.7%    |
| Unknown        | 9         | 3.7%    |
| 151-200        | 8         | 3.29%   |
| 121-130        | 8         | 3.29%   |
| 71-80          | 6         | 2.47%   |
| 141-150        | 6         | 2.47%   |
| 111-120        | 6         | 2.47%   |
| 61-70          | 2         | 0.82%   |
| 51-60          | 1         | 0.41%   |
| 41-50          | 1         | 0.41%   |
| 1-40           | 1         | 0.41%   |
| 501-1000       | 1         | 0.41%   |
| 91-100         | 1         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 68        | 29.31%  |
| 51-100        | 58        | 25%     |
| 101-120       | 53        | 22.84%  |
| 161-240       | 26        | 11.21%  |
| More than 240 | 13        | 5.6%    |
| Unknown       | 9         | 3.88%   |
| 1-50          | 5         | 2.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 141       | 66.82%  |
| 2     | 44        | 20.85%  |
| 0     | 14        | 6.64%   |
| 3     | 9         | 4.27%   |
| 4     | 3         | 1.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 138       | 47.1%   |
| Realtek Semiconductor             | 89        | 30.38%  |
| Qualcomm Atheros                  | 14        | 4.78%   |
| Aquantia                          | 8         | 2.73%   |
| MediaTek                          | 7         | 2.39%   |
| Broadcom                          | 7         | 2.39%   |
| ASIX Electronics                  | 3         | 1.02%   |
| Samsung Electronics               | 2         | 0.68%   |
| Qualcomm                          | 2         | 0.68%   |
| Microsoft                         | 2         | 0.68%   |
| Marvell Technology Group          | 2         | 0.68%   |
| Lenovo                            | 2         | 0.68%   |
| Broadcom Limited                  | 2         | 0.68%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.34%   |
| Sierra Wireless                   | 1         | 0.34%   |
| Shenzhen Goodix Technology        | 1         | 0.34%   |
| Raspberry Pi                      | 1         | 0.34%   |
| Ralink Technology                 | 1         | 0.34%   |
| Quectel Wireless Solutions        | 1         | 0.34%   |
| NetGear                           | 1         | 0.34%   |
| ICS Advent                        | 1         | 0.34%   |
| Google                            | 1         | 0.34%   |
| Ericsson Business Mobile Networks | 1         | 0.34%   |
| Dresden Elektronik                | 1         | 0.34%   |
| DisplayLink                       | 1         | 0.34%   |
| Dell                              | 1         | 0.34%   |
| D-Link                            | 1         | 0.34%   |
| Apple                             | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 62        | 17.37%  |
| Intel Wi-Fi 6 AX200                                                 | 31        | 8.68%   |
| Realtek RTL8125 2.5GbE Controller                                   | 14        | 3.92%   |
| Intel I211 Gigabit Network Connection                               | 12        | 3.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 10        | 2.8%    |
| Intel Ethernet Controller I225-V                                    | 9         | 2.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                   | 8         | 2.24%   |
| Intel Wi-Fi 6 AX201                                                 | 7         | 1.96%   |
| Intel Ethernet Connection (7) I219-V                                | 7         | 1.96%   |
| Intel Wireless 8265 / 8275                                          | 6         | 1.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 6         | 1.68%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 6         | 1.68%   |
| Intel I210 Gigabit Network Connection                               | 6         | 1.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 5         | 1.4%    |
| Intel Wireless 8260                                                 | 5         | 1.4%    |
| Intel Ethernet Connection (2) I219-V                                | 5         | 1.4%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 4         | 1.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 4         | 1.12%   |
| Intel Wireless-AC 9260                                              | 4         | 1.12%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 4         | 1.12%   |
| Intel 82574L Gigabit Network Connection                             | 4         | 1.12%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 4         | 1.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 3         | 0.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 3         | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 3         | 0.84%   |
| Intel Ethernet Connection (2) I219-LM                               | 3         | 0.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                            | 3         | 0.84%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 3         | 0.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3         | 0.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 2         | 0.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 2         | 0.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 2         | 0.56%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                     | 2         | 0.56%   |
| Qualcomm QCNFA765 Wireless Network Adapter                          | 2         | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 2         | 0.56%   |
| Microsoft XBOX ACC                                                  | 2         | 0.56%   |
| Intel Wireless 7265                                                 | 2         | 0.56%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                    | 2         | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                               | 2         | 0.56%   |
| Intel Ethernet Connection (14) I219-V                               | 2         | 0.56%   |
| Intel Ethernet Connection (11) I219-LM                              | 2         | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 2         | 0.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                                    | 2         | 0.56%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                | 2         | 0.56%   |
| ASIX AX88179 Gigabit Ethernet                                       | 2         | 0.56%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 0.56%   |
| ZTE WCDMA MSM ZTE Mobile Broadband Station                          | 1         | 0.28%   |
| Sierra Wireless EM7455                                              | 1         | 0.28%   |
| Shenzhen Goodix Unknow device                                       | 1         | 0.28%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)         | 1         | 0.28%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1         | 0.28%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1         | 0.28%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 1         | 0.28%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1         | 0.28%   |
| Realtek RTL8723DE Wireless Network Adapter                          | 1         | 0.28%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                          | 1         | 0.28%   |
| Realtek Killer E3000 2.5GbE Controller                              | 1         | 0.28%   |
| Raspberry Pi Pico                                                   | 1         | 0.28%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1         | 0.28%   |
| Quectel Wireless Solutions Quectel EM05-CE                          | 1         | 0.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 108       | 68.79%  |
| Realtek Semiconductor      | 17        | 10.83%  |
| Qualcomm Atheros           | 9         | 5.73%   |
| MediaTek                   | 7         | 4.46%   |
| Broadcom                   | 4         | 2.55%   |
| Qualcomm                   | 2         | 1.27%   |
| Microsoft                  | 2         | 1.27%   |
| Broadcom Limited           | 2         | 1.27%   |
| Sierra Wireless            | 1         | 0.64%   |
| Ralink Technology          | 1         | 0.64%   |
| Quectel Wireless Solutions | 1         | 0.64%   |
| NetGear                    | 1         | 0.64%   |
| Dell                       | 1         | 0.64%   |
| D-Link                     | 1         | 0.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 31        | 19.62%  |
| Intel Cannon Lake PCH CNVi WiFi                                         | 10        | 6.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 5.06%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 4.43%   |
| Intel Wireless 8265 / 8275                                              | 6         | 3.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 6         | 3.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 6         | 3.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 3.16%   |
| Intel Wireless 8260                                                     | 5         | 3.16%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 2.53%   |
| Intel Wireless-AC 9260                                                  | 4         | 2.53%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 2.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 1.9%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 1.9%    |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 3         | 1.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.27%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 1.27%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 2         | 1.27%   |
| Microsoft XBOX ACC                                                      | 2         | 1.27%   |
| Intel Wireless 7265                                                     | 2         | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.27%   |
| Sierra Wireless EM7455                                                  | 1         | 0.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.63%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.63%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.63%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.63%   |
| Quectel Wireless Solutions Quectel EM05-CE                              | 1         | 0.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.63%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 0.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.63%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 1         | 0.63%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 0.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.63%   |
| NetGear A6210                                                           | 1         | 0.63%   |
| MediaTek WLAN controller                                                | 1         | 0.63%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 0.63%   |
| Intel Wireless 3165                                                     | 1         | 0.63%   |
| Intel Wireless 3160                                                     | 1         | 0.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.63%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 0.63%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 0.63%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                    | 1         | 0.63%   |
| D-Link 802.11 n WLAN                                                    | 1         | 0.63%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 0.63%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 1         | 0.63%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1         | 0.63%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller     | 1         | 0.63%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 0.63%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                      | 1         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 83        | 45.86%  |
| Intel                    | 67        | 37.02%  |
| Aquantia                 | 8         | 4.42%   |
| Qualcomm Atheros         | 7         | 3.87%   |
| Broadcom                 | 3         | 1.66%   |
| ASIX Electronics         | 3         | 1.66%   |
| Samsung Electronics      | 2         | 1.1%    |
| Marvell Technology Group | 2         | 1.1%    |
| Lenovo                   | 2         | 1.1%    |
| ICS Advent               | 1         | 0.55%   |
| Google                   | 1         | 0.55%   |
| DisplayLink              | 1         | 0.55%   |
| Apple                    | 1         | 0.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 62        | 32.12%  |
| Realtek RTL8125 2.5GbE Controller                                     | 14        | 7.25%   |
| Intel I211 Gigabit Network Connection                                 | 12        | 6.22%   |
| Intel Ethernet Controller I225-V                                      | 9         | 4.66%   |
| Intel Ethernet Connection (7) I219-V                                  | 7         | 3.63%   |
| Intel I210 Gigabit Network Connection                                 | 6         | 3.11%   |
| Intel Ethernet Connection (2) I219-V                                  | 5         | 2.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 4         | 2.07%   |
| Intel 82574L Gigabit Network Connection                               | 4         | 2.07%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]     | 4         | 2.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 3         | 1.55%   |
| Intel Ethernet Connection (2) I219-LM                                 | 3         | 1.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 3         | 1.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller             | 2         | 1.04%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                      | 2         | 1.04%   |
| Intel Ethernet Connection (7) I219-LM                                 | 2         | 1.04%   |
| Intel Ethernet Connection (14) I219-V                                 | 2         | 1.04%   |
| Intel Ethernet Connection (11) I219-LM                                | 2         | 1.04%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                  | 2         | 1.04%   |
| ASIX AX88179 Gigabit Ethernet                                         | 2         | 1.04%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2         | 1.04%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)           | 1         | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                         | 1         | 0.52%   |
| Realtek Killer E3000 2.5GbE Controller                                | 1         | 0.52%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                | 1         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller             | 1         | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller             | 1         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                         | 1         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                 | 1         | 0.52%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller               | 1         | 0.52%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller               | 1         | 0.52%   |
| Lenovo USB-C Dock Ethernet                                            | 1         | 0.52%   |
| Lenovo ThinkPad TBT 3 Dock                                            | 1         | 0.52%   |
| Intel I350 Gigabit Network Connection                                 | 1         | 0.52%   |
| Intel Ethernet Connection I219-V                                      | 1         | 0.52%   |
| Intel Ethernet Connection I219-LM                                     | 1         | 0.52%   |
| Intel Ethernet Connection I218-V                                      | 1         | 0.52%   |
| Intel Ethernet Connection I217-V                                      | 1         | 0.52%   |
| Intel Ethernet Connection (6) I219-V                                  | 1         | 0.52%   |
| Intel Ethernet Connection (5) I219-V                                  | 1         | 0.52%   |
| Intel Ethernet Connection (4) I219-LM                                 | 1         | 0.52%   |
| Intel Ethernet Connection (16) I219-LM                                | 1         | 0.52%   |
| Intel Ethernet Connection (14) I219-LM                                | 1         | 0.52%   |
| Intel Ethernet Connection (11) I219-V                                 | 1         | 0.52%   |
| Intel Ethernet Connection (10) I219-V                                 | 1         | 0.52%   |
| Intel Ethernet Connection (10) I219-LM                                | 1         | 0.52%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                    | 1         | 0.52%   |
| Intel 82579V Gigabit Network Connection                               | 1         | 0.52%   |
| Intel 82576 Gigabit Network Connection                                | 1         | 0.52%   |
| Intel 82575GB Gigabit Network Connection                              | 1         | 0.52%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                | 1         | 0.52%   |
| ICS Advent DM9601 Fast Ethernet Adapter                               | 1         | 0.52%   |
| Google Nexus/Pixel Device (tether)                                    | 1         | 0.52%   |
| DisplayLink Dell D3100 Docking Station                                | 1         | 0.52%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express               | 1         | 0.52%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 1         | 0.52%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                      | 1         | 0.52%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1         | 0.52%   |
| ASIX AX88772                                                          | 1         | 0.52%   |
| Aquantia Ethernet controller                                          | 1         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 165       | 51.4%   |
| WiFi     | 150       | 46.73%  |
| Modem    | 5         | 1.56%   |
| Unknown  | 1         | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 103       | 50.24%  |
| Ethernet | 102       | 49.76%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 95        | 45.67%  |
| 1     | 87        | 41.83%  |
| 3     | 13        | 6.25%   |
| 4     | 5         | 2.4%    |
| 0     | 5         | 2.4%    |
| 6     | 2         | 0.96%   |
| 5     | 1         | 0.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 155       | 73.11%  |
| Yes  | 57        | 26.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 102       | 69.86%  |
| Realtek Semiconductor           | 12        | 8.22%   |
| Cambridge Silicon Radio         | 7         | 4.79%   |
| IMC Networks                    | 6         | 4.11%   |
| Foxconn / Hon Hai               | 4         | 2.74%   |
| Toshiba                         | 2         | 1.37%   |
| Broadcom                        | 2         | 1.37%   |
| ASUSTek Computer                | 2         | 1.37%   |
| Apple                           | 2         | 1.37%   |
| USI                             | 1         | 0.68%   |
| Qualcomm Atheros Communications | 1         | 0.68%   |
| MediaTek                        | 1         | 0.68%   |
| Lite-On Technology              | 1         | 0.68%   |
| Hewlett-Packard                 | 1         | 0.68%   |
| Foxconn International           | 1         | 0.68%   |
| Edimax Technology               | 1         | 0.68%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 29        | 19.86%  |
| Intel AX201 Bluetooth                               | 23        | 15.75%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 19        | 13.01%  |
| Intel Bluetooth wireless interface                  | 15        | 10.27%  |
| Realtek Bluetooth Radio                             | 8         | 5.48%   |
| Intel AX210 Bluetooth                               | 7         | 4.79%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 4.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 2.74%   |
| IMC Networks Wireless_Device                        | 4         | 2.74%   |
| Intel Bluetooth Device                              | 3         | 2.05%   |
| Toshiba RT Bluetooth Radio                          | 2         | 1.37%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 1.37%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 1.37%   |
| USI Bluetooth Device                                | 1         | 0.68%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.68%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.68%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.68%   |
| MediaTek Wireless_Device                            | 1         | 0.68%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.68%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.68%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.68%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.68%   |
| IMC Networks Bluetooth Device                       | 1         | 0.68%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.68%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.68%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.68%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.68%   |
| Edimax Bluetooth Adapter                            | 1         | 0.68%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.68%   |
| Broadcom BCM20702A0                                 | 1         | 0.68%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 0.68%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 0.68%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.68%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 0.68%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 113       | 32.75%  |
| AMD                                  | 98        | 28.41%  |
| Nvidia                               | 61        | 17.68%  |
| C-Media Electronics                  | 8         | 2.32%   |
| Thesycon Systemsoftware & Consulting | 5         | 1.45%   |
| SteelSeries ApS                      | 4         | 1.16%   |
| ASUSTek Computer                     | 4         | 1.16%   |
| Realtek Semiconductor                | 3         | 0.87%   |
| Razer USA                            | 3         | 0.87%   |
| Logitech                             | 3         | 0.87%   |
| Creative Labs                        | 3         | 0.87%   |
| AudioQuest                           | 3         | 0.87%   |
| Yamaha                               | 2         | 0.58%   |
| Sony                                 | 2         | 0.58%   |
| SAVITECH                             | 2         | 0.58%   |
| RODE Microphones                     | 2         | 0.58%   |
| Lenovo                               | 2         | 0.58%   |
| JMTek                                | 2         | 0.58%   |
| Creative Technology                  | 2         | 0.58%   |
| Blue Microphones                     | 2         | 0.58%   |
| Audio-Technica                       | 2         | 0.58%   |
| Valve Software                       | 1         | 0.29%   |
| Unknown                              | 1         | 0.29%   |
| Texas Instruments                    | 1         | 0.29%   |
| TEAC                                 | 1         | 0.29%   |
| Sennheiser Communications            | 1         | 0.29%   |
| MAG Technology                       | 1         | 0.29%   |
| Kingston Technology                  | 1         | 0.29%   |
| JOUNIVO                              | 1         | 0.29%   |
| Huawei Technologies                  | 1         | 0.29%   |
| Hewlett-Packard                      | 1         | 0.29%   |
| GN Netcom                            | 1         | 0.29%   |
| Generalplus Technology               | 1         | 0.29%   |
| Focusrite-Novation                   | 1         | 0.29%   |
| FiiO Electronics Technology          | 1         | 0.29%   |
| FIFINE Microphones                   | 1         | 0.29%   |
| Corsair                              | 1         | 0.29%   |
| BEHRINGER International              | 1         | 0.29%   |
| Astro Gaming                         | 1         | 0.29%   |
| ACTIONS                              | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 37        | 8.83%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 25        | 5.97%   |
| AMD Starship/Matisse HD Audio Controller                                   | 23        | 5.49%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 21        | 5.01%   |
| Intel Cannon Lake PCH cAVS                                                 | 19        | 4.53%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 13        | 3.1%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 11        | 2.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10        | 2.39%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 2.15%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 9         | 2.15%   |
| Nvidia GP106 High Definition Audio Controller                              | 8         | 1.91%   |
| Intel Sunrise Point-LP HD Audio                                            | 8         | 1.91%   |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 1.91%   |
| Nvidia TU104 HD Audio Controller                                           | 6         | 1.43%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 1.43%   |
| Thesycon Systemsoftware & Consulting U90                                   | 5         | 1.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 1.19%   |
| Nvidia GP104 High Definition Audio Controller                              | 5         | 1.19%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 1.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 1.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 1.19%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 0.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 0.95%   |
| Intel Alder Lake-S HD Audio Controller                                     | 4         | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 0.95%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 0.95%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.72%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 0.72%   |
| Nvidia GM206 High Definition Audio Controller                              | 3         | 0.72%   |
| Nvidia GA102 High Definition Audio Controller                              | 3         | 0.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 0.72%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 0.72%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 0.72%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 0.72%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3         | 0.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 0.72%   |
| ASUSTek Computer USB Audio                                                 | 3         | 0.72%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 0.72%   |
| AMD Navi 10 HDMI Audio                                                     | 3         | 0.72%   |
| AMD FCH Azalia Controller                                                  | 3         | 0.72%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 2         | 0.48%   |
| Realtek Semiconductor USB Condenser Microphone                             | 2         | 0.48%   |
| Nvidia TU102 High Definition Audio Controller                              | 2         | 0.48%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2         | 0.48%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.48%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.48%   |
| Nvidia Audio device                                                        | 2         | 0.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 0.48%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 0.48%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 2         | 0.48%   |
| C-Media Electronics CM108 Audio Controller                                 | 2         | 0.48%   |
| C-Media Electronics Blue Snowball                                          | 2         | 0.48%   |
| Blue Microphones Yeti Stereo Microphone                                    | 2         | 0.48%   |
| AudioQuest DragonFly Red                                                   | 2         | 0.48%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 0.48%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 0.48%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 0.48%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 0.48%   |
| Yamaha Steinberg UR22mkII                                                  | 1         | 0.24%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 59        | 26.94%  |
| SK hynix            | 29        | 13.24%  |
| Kingston            | 25        | 11.42%  |
| Crucial             | 21        | 9.59%   |
| G.Skill             | 19        | 8.68%   |
| Micron Technology   | 16        | 7.31%   |
| Corsair             | 16        | 7.31%   |
| Unknown             | 10        | 4.57%   |
| Patriot             | 4         | 1.83%   |
| A-DATA Technology   | 4         | 1.83%   |
| Team                | 3         | 1.37%   |
| Transcend           | 2         | 0.91%   |
| Unknown             | 2         | 0.91%   |
| Unknown (ABCD)      | 1         | 0.46%   |
| Timetec             | 1         | 0.46%   |
| Ramaxel Technology  | 1         | 0.46%   |
| Qimonda             | 1         | 0.46%   |
| Patriot Memory      | 1         | 0.46%   |
| Nanya Technology    | 1         | 0.46%   |
| Magnum Tech         | 1         | 0.46%   |
| Innodisk            | 1         | 0.46%   |
| GOODRAM             | 1         | 0.46%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 2.16%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 4         | 1.73%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 4         | 1.73%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 3         | 1.3%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 1.3%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 3         | 1.3%    |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 1.3%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 3         | 1.3%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 2         | 0.87%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.87%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.87%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s    | 2         | 0.87%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s               | 2         | 0.87%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 2         | 0.87%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.87%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 2         | 0.87%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 0.87%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 0.87%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s                  | 2         | 0.87%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 2         | 0.87%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s                | 2         | 0.87%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s               | 2         | 0.87%   |
| Kingston RAM 9965487-004.A00LF 4GB DIMM 1066MT/s                    | 2         | 0.87%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s               | 2         | 0.87%   |
| Crucial RAM BL16G36C16U4RL.M8FB1 16GB DIMM DDR4 4000MT/s            | 2         | 0.87%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16GB DIMM DDR4 3200MT/s            | 2         | 0.87%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s              | 2         | 0.87%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s              | 2         | 0.87%   |
| Unknown                                                             | 2         | 0.87%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                           | 1         | 0.43%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                | 1         | 0.43%   |
| Unknown RAM Module 512MB DIMM SDRAM                                 | 1         | 0.43%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR3 1867MT/s                 | 1         | 0.43%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                            | 1         | 0.43%   |
| Unknown RAM Module 1GB SODIMM SDRAM                                 | 1         | 0.43%   |
| Unknown RAM Module 1GB SODIMM DDR                                   | 1         | 0.43%   |
| Unknown RAM Module 1GB DIMM SDRAM                                   | 1         | 0.43%   |
| Unknown RAM Module 16GB DIMM DDR4 3200MT/s                          | 1         | 0.43%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s                          | 1         | 0.43%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s               | 1         | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.43%   |
| Transcend RAM Module 2GB SODIMM DDR2 533MT/s                        | 1         | 0.43%   |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s               | 1         | 0.43%   |
| Timetec RAM SD4-3200 16GB SODIMM DDR4 3200MT/s                      | 1         | 0.43%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s                  | 1         | 0.43%   |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3200MT/s                 | 1         | 0.43%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s                | 1         | 0.43%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s                | 1         | 0.43%   |
| SK hynix RAM HMT425U6AFR6C-PB 2GB DIMM DDR3 1600MT/s                | 1         | 0.43%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.43%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.43%   |
| SK hynix RAM HMCG88MEBSA095N 32GB SODIMM 4800MT/s                   | 1         | 0.43%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s              | 1         | 0.43%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s             | 1         | 0.43%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s          | 1         | 0.43%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 0.43%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 0.43%   |
| SK hynix RAM HMA84GR7CJR4N-XN 32GB DIMM DDR4 3200MT/s               | 1         | 0.43%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 1         | 0.43%   |
| SK hynix RAM HMA81GU7DJR8N-VK 8GB DIMM DDR4 2666MT/s                | 1         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 144       | 73.1%   |
| DDR3    | 25        | 12.69%  |
| LPDDR4  | 6         | 3.05%   |
| LPDDR3  | 6         | 3.05%   |
| Unknown | 6         | 3.05%   |
| DDR5    | 3         | 1.52%   |
| DDR2    | 3         | 1.52%   |
| SDRAM   | 2         | 1.02%   |
| DDR     | 2         | 1.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 95        | 47.98%  |
| DIMM         | 85        | 42.93%  |
| Row Of Chips | 16        | 8.08%   |
| Chip         | 2         | 1.01%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 90        | 43.06%  |
| 16384 | 58        | 27.75%  |
| 4096  | 25        | 11.96%  |
| 32768 | 23        | 11%     |
| 2048  | 8         | 3.83%   |
| 1024  | 3         | 1.44%   |
| 512   | 2         | 0.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 70        | 33.02%  |
| 2667    | 33        | 15.57%  |
| 1600    | 19        | 8.96%   |
| 3600    | 11        | 5.19%   |
| 2133    | 10        | 4.72%   |
| 4800    | 6         | 2.83%   |
| 2400    | 6         | 2.83%   |
| 1333    | 5         | 2.36%   |
| 8400    | 4         | 1.89%   |
| 3400    | 4         | 1.89%   |
| 1867    | 4         | 1.89%   |
| 4267    | 3         | 1.42%   |
| 3733    | 3         | 1.42%   |
| 3466    | 3         | 1.42%   |
| 3000    | 3         | 1.42%   |
| 667     | 3         | 1.42%   |
| Unknown | 3         | 1.42%   |
| 4000    | 2         | 0.94%   |
| 3866    | 2         | 0.94%   |
| 3666    | 2         | 0.94%   |
| 2933    | 2         | 0.94%   |
| 2666    | 2         | 0.94%   |
| 1066    | 2         | 0.94%   |
| 533     | 2         | 0.94%   |
| 6400    | 1         | 0.47%   |
| 3334    | 1         | 0.47%   |
| 3266    | 1         | 0.47%   |
| 2866    | 1         | 0.47%   |
| 2733    | 1         | 0.47%   |
| 2197    | 1         | 0.47%   |
| 1067    | 1         | 0.47%   |
| 800     | 1         | 0.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Computers | Percent |
|---------------------|-----------|---------|
| HP LaserJet M14-M17 | 1         | 50%     |
| Canon LiDE 400      | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 21        | 18.42%  |
| Chicony Electronics                    | 20        | 17.54%  |
| Logitech                               | 11        | 9.65%   |
| Acer                                   | 9         | 7.89%   |
| Realtek Semiconductor                  | 7         | 6.14%   |
| Microdia                               | 7         | 6.14%   |
| Sunplus Innovation Technology          | 6         | 5.26%   |
| Lite-On Technology                     | 6         | 5.26%   |
| Quanta                                 | 5         | 4.39%   |
| Syntek                                 | 3         | 2.63%   |
| Luxvisions Innotech Limited            | 3         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.75%   |
| YGTek                                  | 1         | 0.88%   |
| Xiaomi                                 | 1         | 0.88%   |
| Valve Software                         | 1         | 0.88%   |
| SunplusIT                              | 1         | 0.88%   |
| Sonix Technology                       | 1         | 0.88%   |
| Samsung Electronics                    | 1         | 0.88%   |
| Ruision                                | 1         | 0.88%   |
| MacroSilicon                           | 1         | 0.88%   |
| KYE Systems (Mouse Systems)            | 1         | 0.88%   |
| Generalplus Technology                 | 1         | 0.88%   |
| DigiTech                               | 1         | 0.88%   |
| Cubeternet                             | 1         | 0.88%   |
| Creative Technology                    | 1         | 0.88%   |
| Alcor Micro                            | 1         | 0.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                      | 13        | 11.3%   |
| Chicony Integrated Camera                                           | 7         | 6.09%   |
| Acer Integrated Camera                                              | 6         | 5.22%   |
| Microdia Integrated_Webcam_HD                                       | 5         | 4.35%   |
| IMC Networks USB2.0 HD UVC WebCam                                   | 5         | 4.35%   |
| Realtek Integrated Webcam HD                                        | 3         | 2.61%   |
| Syntek Integrated Camera                                            | 2         | 1.74%   |
| Sunplus Integrated_Webcam_HD                                        | 2         | 1.74%   |
| Quanta RGB-IR Camera                                                | 2         | 1.74%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                 | 2         | 1.74%   |
| Logitech HD Pro Webcam C920                                         | 2         | 1.74%   |
| Logitech BRIO Ultra HD Webcam                                       | 2         | 1.74%   |
| Lite-On TOSHIBA Web Camera - HD                                     | 2         | 1.74%   |
| Lite-On HP Wide Vision HD Camera                                    | 2         | 1.74%   |
| Chicony USB2.0 Camera                                               | 2         | 1.74%   |
| Chicony HD User Facing                                              | 2         | 1.74%   |
| Acer NEC HD WebCam                                                  | 2         | 1.74%   |
| YGTek Webcam                                                        | 1         | 0.87%   |
| Xiaomi Redmi Note 10 Pro                                            | 1         | 0.87%   |
| Valve Software 3D Camera                                            | 1         | 0.87%   |
| Syntek Lenovo EasyCamera                                            | 1         | 0.87%   |
| SunplusIT AUKEY PCÃ¢Â€Â”LM4                                 | 1         | 0.87%   |
| Sunplus NexiGo N940 2K Webcam                                       | 1         | 0.87%   |
| Sunplus HP Wide Vision HD                                           | 1         | 0.87%   |
| Sunplus Full HD webcam                                              | 1         | 0.87%   |
| Sunplus Canyon CNS-CWC5 Webcam                                      | 1         | 0.87%   |
| Sonix USB2.0 HD UVC WebCam                                          | 1         | 0.87%   |
| Samsung Galaxy series, misc. (MTP mode)                             | 1         | 0.87%   |
| Ruision UVC Camera                                                  | 1         | 0.87%   |
| Realtek USB Camera                                                  | 1         | 0.87%   |
| Realtek Laptop Camera                                               | 1         | 0.87%   |
| Realtek Integrated_Webcam_HD                                        | 1         | 0.87%   |
| Realtek Integrated Camera                                           | 1         | 0.87%   |
| Quanta HP Wide Vision HD Camera                                     | 1         | 0.87%   |
| Quanta HD Webcam                                                    | 1         | 0.87%   |
| Quanta HD Camera                                                    | 1         | 0.87%   |
| Microdia USB 2.0 Camera                                             | 1         | 0.87%   |
| Microdia HP Integrated Webcam                                       | 1         | 0.87%   |
| MacroSilicon USB Video                                              | 1         | 0.87%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                | 1         | 0.87%   |
| Logitech Webcam C270                                                | 1         | 0.87%   |
| Logitech Webcam C110                                                | 1         | 0.87%   |
| Logitech StreamCam                                                  | 1         | 0.87%   |
| Logitech QuickCam Orbit/Sphere AF                                   | 1         | 0.87%   |
| Logitech Logi 4K Stream Edition                                     | 1         | 0.87%   |
| Logitech HD Webcam C615                                             | 1         | 0.87%   |
| Logitech HD Webcam C510                                             | 1         | 0.87%   |
| Lite-On Integrated Camera                                           | 1         | 0.87%   |
| Lite-On HP Webcam                                                   | 1         | 0.87%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera                          | 1         | 0.87%   |
| IMC Networks XiaoMi Webcam                                          | 1         | 0.87%   |
| IMC Networks USB2.0 UVC 1.3M WebCam                                 | 1         | 0.87%   |
| IMC Networks Lenovo EasyCamera                                      | 1         | 0.87%   |
| IMC Networks Integrated IR Camera                                   | 1         | 0.87%   |
| Generalplus GENERAL WEBCAM                                          | 1         | 0.87%   |
| DigiTech SC-20FHL11146M                                             | 1         | 0.87%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1         | 0.87%   |
| Creative Live! Cam Sync 1080p                                       | 1         | 0.87%   |
| Chicony XiaoMi USB 2.0 Webcam                                       | 1         | 0.87%   |
| Chicony USB 2.0 Camera                                              | 1         | 0.87%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 33.33%  |
| Synaptics                  | 6         | 33.33%  |
| Elan Microelectronics      | 4         | 22.22%  |
| Shenzhen Goodix Technology | 1         | 5.56%   |
| DigitalPersona             | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 16.67%  |
| Elan ELAN:Fingerprint                             | 3         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 11.11%  |
| Unknown                                           | 2         | 11.11%  |
| Validity Sensors VFS7552 Touch Fingerprint Sensor | 1         | 5.56%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 5.56%   |
| Validity Sensors VFS471 Fingerprint Reader        | 1         | 5.56%   |
| Validity Sensors Synaptics WBDI                   | 1         | 5.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 5.56%   |
| Shenzhen Goodix  FingerPrint Device               | 1         | 5.56%   |
| Elan ELAN:ARM-M4                                  | 1         | 5.56%   |
| DigitalPersona Fingerprint Reader                 | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 44.44%  |
| Alcor Micro | 3         | 33.33%  |
| Yubico.com  | 1         | 11.11%  |
| O2 Micro    | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Broadcom 58200                      | 3         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader | 3         | 33.33%  |
| Yubico.com Yubikey 4 U2F+CCID       | 1         | 11.11%  |
| O2 Micro Oz776 SmartCard Reader     | 1         | 11.11%  |
| Broadcom 5880                       | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 116       | 54.21%  |
| 1     | 49        | 22.9%   |
| 2     | 27        | 12.62%  |
| 3     | 11        | 5.14%   |
| 4     | 8         | 3.74%   |
| 7     | 1         | 0.47%   |
| 6     | 1         | 0.47%   |
| 5     | 1         | 0.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 27        | 15.88%  |
| Bluetooth                | 21        | 12.35%  |
| Graphics card            | 20        | 11.76%  |
| Net/wireless             | 19        | 11.18%  |
| Fingerprint reader       | 18        | 10.59%  |
| Camera                   | 15        | 8.82%   |
| Multimedia controller    | 11        | 6.47%   |
| Sound                    | 9         | 5.29%   |
| Chipcard                 | 7         | 4.12%   |
| Card reader              | 6         | 3.53%   |
| Network                  | 5         | 2.94%   |
| Modem                    | 4         | 2.35%   |
| Storage/ata              | 2         | 1.18%   |
| Firewire controller      | 2         | 1.18%   |
| Unassigned class         | 1         | 0.59%   |
| Storage/raid             | 1         | 0.59%   |
| Storage/ide              | 1         | 0.59%   |
| Net/ethernet             | 1         | 0.59%   |

