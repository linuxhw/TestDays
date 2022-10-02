Gentoo - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Gentoo.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Gentoo/Desktop/README.md) and [notebooks](/Dist/Gentoo/Notebook/README.md).

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

Total: 1967

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [1cfda531dd](https://linux-hardware.org/?probe=1cfda531dd) | Oct 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6d9c960574](https://linux-hardware.org/?probe=6d9c960574) | Sep 28, 2022 |
| HP            | EliteBook 8770w             | Notebook    | [e5ec559da4](https://linux-hardware.org/?probe=e5ec559da4) | Sep 28, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [4479784a2e](https://linux-hardware.org/?probe=4479784a2e) | Sep 28, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [d0808e8abe](https://linux-hardware.org/?probe=d0808e8abe) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [b3b8d3e04f](https://linux-hardware.org/?probe=b3b8d3e04f) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [9795d4f9aa](https://linux-hardware.org/?probe=9795d4f9aa) | Sep 26, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [6d3f575c3d](https://linux-hardware.org/?probe=6d3f575c3d) | Sep 26, 2022 |
| Sony          | PCG-GRT230(UC)              | Notebook    | [af843c265c](https://linux-hardware.org/?probe=af843c265c) | Sep 26, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c447921f07](https://linux-hardware.org/?probe=c447921f07) | Sep 25, 2022 |
| Lenovo        | ThinkPad P73 20QRS0G700     | Notebook    | [b32a413aa9](https://linux-hardware.org/?probe=b32a413aa9) | Sep 25, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [6c8a53f608](https://linux-hardware.org/?probe=6c8a53f608) | Sep 25, 2022 |
| Lenovo        | ThinkPad P73 20QRS0G700     | Notebook    | [6ea4c40a80](https://linux-hardware.org/?probe=6ea4c40a80) | Sep 25, 2022 |
| ASRock        | J3160M                      | Desktop     | [c9cc54f48e](https://linux-hardware.org/?probe=c9cc54f48e) | Sep 25, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [cdbc7c7949](https://linux-hardware.org/?probe=cdbc7c7949) | Sep 25, 2022 |
| Supermicro    | H11SSL-i                    | Server      | [dd3ce003e4](https://linux-hardware.org/?probe=dd3ce003e4) | Sep 25, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [907383d255](https://linux-hardware.org/?probe=907383d255) | Sep 25, 2022 |
| Matsushita... | CF-29LTQGZBM                | Notebook    | [29f52f862c](https://linux-hardware.org/?probe=29f52f862c) | Sep 24, 2022 |
| Acer          | Predator PH315-51           | Notebook    | [24ae1f3fb8](https://linux-hardware.org/?probe=24ae1f3fb8) | Sep 23, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [de7c138e21](https://linux-hardware.org/?probe=de7c138e21) | Sep 22, 2022 |
| Lenovo        | ThinkPad L580 20LWCTO1WW    | Notebook    | [a80367f777](https://linux-hardware.org/?probe=a80367f777) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [d22f082243](https://linux-hardware.org/?probe=d22f082243) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [e4f1a8245a](https://linux-hardware.org/?probe=e4f1a8245a) | Sep 21, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [a6e61a9993](https://linux-hardware.org/?probe=a6e61a9993) | Sep 19, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [eb1c0556c3](https://linux-hardware.org/?probe=eb1c0556c3) | Sep 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5a9ab0de04](https://linux-hardware.org/?probe=5a9ab0de04) | Sep 18, 2022 |
| System76      | Gazelle Professional        | Notebook    | [95f19a0c4c](https://linux-hardware.org/?probe=95f19a0c4c) | Sep 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d4d8cc3f34](https://linux-hardware.org/?probe=d4d8cc3f34) | Sep 16, 2022 |
| Dell          | G7 7588                     | Notebook    | [583c4a4c91](https://linux-hardware.org/?probe=583c4a4c91) | Sep 16, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [475ed7f917](https://linux-hardware.org/?probe=475ed7f917) | Sep 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7ad1180946](https://linux-hardware.org/?probe=7ad1180946) | Sep 14, 2022 |
| Timi          | TM1604                      | Notebook    | [80f52c9545](https://linux-hardware.org/?probe=80f52c9545) | Sep 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [7bc7cbca76](https://linux-hardware.org/?probe=7bc7cbca76) | Sep 12, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [225bd59ba7](https://linux-hardware.org/?probe=225bd59ba7) | Sep 12, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ed5273b278](https://linux-hardware.org/?probe=ed5273b278) | Sep 11, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [3cb7aa6549](https://linux-hardware.org/?probe=3cb7aa6549) | Sep 11, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [2e0d41f272](https://linux-hardware.org/?probe=2e0d41f272) | Sep 10, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [06ee689632](https://linux-hardware.org/?probe=06ee689632) | Sep 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [5cfe072b9c](https://linux-hardware.org/?probe=5cfe072b9c) | Sep 10, 2022 |
| ASRock        | Z390 Phantom Gaming 4S      | Desktop     | [146e7ebf49](https://linux-hardware.org/?probe=146e7ebf49) | Sep 08, 2022 |
| Gigabyte      | B660 GAMING X AX DDR4       | Desktop     | [3d12a72937](https://linux-hardware.org/?probe=3d12a72937) | Sep 06, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [cc1fde17e8](https://linux-hardware.org/?probe=cc1fde17e8) | Sep 06, 2022 |
| Dell          | Latitude D410               | Notebook    | [6782e0a28f](https://linux-hardware.org/?probe=6782e0a28f) | Sep 05, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [12fbd247f5](https://linux-hardware.org/?probe=12fbd247f5) | Sep 05, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [1d90e3b685](https://linux-hardware.org/?probe=1d90e3b685) | Sep 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [88392a79f5](https://linux-hardware.org/?probe=88392a79f5) | Sep 04, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [d02a951b89](https://linux-hardware.org/?probe=d02a951b89) | Sep 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [8320ded55c](https://linux-hardware.org/?probe=8320ded55c) | Sep 02, 2022 |
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
| Fujitsu       | LIFEBOOK U758               | Notebook    | [fa1566785a](https://linux-hardware.org/?probe=fa1566785a) | Aug 03, 2022 |
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
| Toshiba       | Satellite A200              | Notebook    | [d030e357db](https://linux-hardware.org/?probe=d030e357db) | Jul 02, 2022 |
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
| ASRock        | B450 Pro4                   | Desktop     | [9d03e8cba7](https://linux-hardware.org/?probe=9d03e8cba7) | Jun 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [17b77e3069](https://linux-hardware.org/?probe=17b77e3069) | Jun 17, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [286f8505c9](https://linux-hardware.org/?probe=286f8505c9) | Jun 17, 2022 |
| Dell          | G3 3500                     | Notebook    | [396a536231](https://linux-hardware.org/?probe=396a536231) | Jun 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [fe7fa5fe7a](https://linux-hardware.org/?probe=fe7fa5fe7a) | Jun 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [6fa09c2dd0](https://linux-hardware.org/?probe=6fa09c2dd0) | Jun 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [d3f9fd8f0c](https://linux-hardware.org/?probe=d3f9fd8f0c) | Jun 16, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [59350b295e](https://linux-hardware.org/?probe=59350b295e) | Jun 13, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [223b882103](https://linux-hardware.org/?probe=223b882103) | Jun 12, 2022 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | Notebook    | [283958f1a4](https://linux-hardware.org/?probe=283958f1a4) | Jun 12, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [7b531e1607](https://linux-hardware.org/?probe=7b531e1607) | Jun 09, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [197f417cea](https://linux-hardware.org/?probe=197f417cea) | Jun 09, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [80a6dc4a46](https://linux-hardware.org/?probe=80a6dc4a46) | Jun 09, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [f237211ddb](https://linux-hardware.org/?probe=f237211ddb) | Jun 09, 2022 |
| Pegatron      | 2ACE                        | Desktop     | [838cad5bc2](https://linux-hardware.org/?probe=838cad5bc2) | Jun 06, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [5745c8b787](https://linux-hardware.org/?probe=5745c8b787) | Jun 06, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [fd5c0c6f83](https://linux-hardware.org/?probe=fd5c0c6f83) | Jun 06, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [cb81a60917](https://linux-hardware.org/?probe=cb81a60917) | Jun 05, 2022 |
| Dell          | G3 3500                     | Notebook    | [edbd452524](https://linux-hardware.org/?probe=edbd452524) | Jun 05, 2022 |
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
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [6e43e1d4f1](https://linux-hardware.org/?probe=6e43e1d4f1) | May 30, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [bd36f27f9b](https://linux-hardware.org/?probe=bd36f27f9b) | May 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [2669150033](https://linux-hardware.org/?probe=2669150033) | May 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [77989d3d20](https://linux-hardware.org/?probe=77989d3d20) | May 28, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [641c79318b](https://linux-hardware.org/?probe=641c79318b) | May 27, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [86021dcc38](https://linux-hardware.org/?probe=86021dcc38) | May 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e879d3c292](https://linux-hardware.org/?probe=e879d3c292) | May 27, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [ecebcc6033](https://linux-hardware.org/?probe=ecebcc6033) | May 26, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [0948f30719](https://linux-hardware.org/?probe=0948f30719) | May 26, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [b8603fccc0](https://linux-hardware.org/?probe=b8603fccc0) | May 26, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [1d5fe9025a](https://linux-hardware.org/?probe=1d5fe9025a) | May 25, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [38ac6de56d](https://linux-hardware.org/?probe=38ac6de56d) | May 25, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [af256d7649](https://linux-hardware.org/?probe=af256d7649) | May 24, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [59eda31291](https://linux-hardware.org/?probe=59eda31291) | May 24, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [b253c6e007](https://linux-hardware.org/?probe=b253c6e007) | May 24, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [add67dab1a](https://linux-hardware.org/?probe=add67dab1a) | May 24, 2022 |
| ASRockRack    | E3C232D2I                   | Desktop     | [0442460b97](https://linux-hardware.org/?probe=0442460b97) | May 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e370a75aa](https://linux-hardware.org/?probe=4e370a75aa) | May 23, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [e254f29ffd](https://linux-hardware.org/?probe=e254f29ffd) | May 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [93700a286d](https://linux-hardware.org/?probe=93700a286d) | May 23, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [6f78dba14b](https://linux-hardware.org/?probe=6f78dba14b) | May 23, 2022 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [ce350dd874](https://linux-hardware.org/?probe=ce350dd874) | May 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f129f3b1d5](https://linux-hardware.org/?probe=f129f3b1d5) | May 22, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [32b5f99569](https://linux-hardware.org/?probe=32b5f99569) | May 22, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [8f47f3a71c](https://linux-hardware.org/?probe=8f47f3a71c) | May 22, 2022 |
| Supermicro    | H12SSL-NT                   | Server      | [6492614879](https://linux-hardware.org/?probe=6492614879) | May 21, 2022 |
| HP            | ProBook 430 G7              | Notebook    | [04a6359630](https://linux-hardware.org/?probe=04a6359630) | May 21, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | Notebook    | [47297bafb5](https://linux-hardware.org/?probe=47297bafb5) | May 21, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | Notebook    | [7b878500c1](https://linux-hardware.org/?probe=7b878500c1) | May 21, 2022 |
| MSI           | MS-7A34                     | Notebook    | [8956078328](https://linux-hardware.org/?probe=8956078328) | May 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [bdc04b3c5d](https://linux-hardware.org/?probe=bdc04b3c5d) | May 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f7225b80ed](https://linux-hardware.org/?probe=f7225b80ed) | May 18, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [84a0dc5b83](https://linux-hardware.org/?probe=84a0dc5b83) | May 18, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [a49d97c9e6](https://linux-hardware.org/?probe=a49d97c9e6) | May 17, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [1dbb37fcd0](https://linux-hardware.org/?probe=1dbb37fcd0) | May 17, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d5477b3bb9](https://linux-hardware.org/?probe=d5477b3bb9) | May 17, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [818ee286b7](https://linux-hardware.org/?probe=818ee286b7) | May 17, 2022 |
| Dell          | Vostro 5568                 | Notebook    | [c7075dab69](https://linux-hardware.org/?probe=c7075dab69) | May 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [0de514cd0b](https://linux-hardware.org/?probe=0de514cd0b) | May 16, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [56fb967887](https://linux-hardware.org/?probe=56fb967887) | May 16, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [f64f274146](https://linux-hardware.org/?probe=f64f274146) | May 16, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [d1a9527039](https://linux-hardware.org/?probe=d1a9527039) | May 16, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [d675d89c8a](https://linux-hardware.org/?probe=d675d89c8a) | May 16, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [9afc74ed46](https://linux-hardware.org/?probe=9afc74ed46) | May 16, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [28b47bc364](https://linux-hardware.org/?probe=28b47bc364) | May 15, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [49a3292018](https://linux-hardware.org/?probe=49a3292018) | May 15, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [020e862674](https://linux-hardware.org/?probe=020e862674) | May 15, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | Notebook    | [59c5dbcb22](https://linux-hardware.org/?probe=59c5dbcb22) | May 15, 2022 |
| ASUSTek       | Z8NR-D12                    | Desktop     | [e65adcd0da](https://linux-hardware.org/?probe=e65adcd0da) | May 14, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [07e2cea31c](https://linux-hardware.org/?probe=07e2cea31c) | May 13, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [cf73bc12e8](https://linux-hardware.org/?probe=cf73bc12e8) | May 13, 2022 |
| Lenovo        | ThinkPad P73 20QSS09S00     | Notebook    | [8438c92818](https://linux-hardware.org/?probe=8438c92818) | May 12, 2022 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [df570dd8e0](https://linux-hardware.org/?probe=df570dd8e0) | May 12, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [8328bbecb9](https://linux-hardware.org/?probe=8328bbecb9) | May 12, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [2fcf37c00a](https://linux-hardware.org/?probe=2fcf37c00a) | May 11, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [474578814d](https://linux-hardware.org/?probe=474578814d) | May 10, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [5ccbf39183](https://linux-hardware.org/?probe=5ccbf39183) | May 10, 2022 |
| HP            | 8704                        | Desktop     | [b66f290b02](https://linux-hardware.org/?probe=b66f290b02) | May 09, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [0f04e6b439](https://linux-hardware.org/?probe=0f04e6b439) | May 09, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [bd6c3ca5b4](https://linux-hardware.org/?probe=bd6c3ca5b4) | May 09, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [81aa293c77](https://linux-hardware.org/?probe=81aa293c77) | May 08, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [ee92f88374](https://linux-hardware.org/?probe=ee92f88374) | May 07, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [67dbf0ac88](https://linux-hardware.org/?probe=67dbf0ac88) | May 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [8919eebaa3](https://linux-hardware.org/?probe=8919eebaa3) | May 05, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [b51c7ae18b](https://linux-hardware.org/?probe=b51c7ae18b) | May 04, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [48fa5d3b93](https://linux-hardware.org/?probe=48fa5d3b93) | May 04, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [01369642f4](https://linux-hardware.org/?probe=01369642f4) | May 03, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [83ca73d4cd](https://linux-hardware.org/?probe=83ca73d4cd) | May 03, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [8df6782398](https://linux-hardware.org/?probe=8df6782398) | May 02, 2022 |
| Dell          | Precision 3520              | Notebook    | [caae9a5055](https://linux-hardware.org/?probe=caae9a5055) | May 02, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [fcca76f1e5](https://linux-hardware.org/?probe=fcca76f1e5) | May 01, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [b24677a908](https://linux-hardware.org/?probe=b24677a908) | May 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [55402e38ae](https://linux-hardware.org/?probe=55402e38ae) | May 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [df7b5507c1](https://linux-hardware.org/?probe=df7b5507c1) | Apr 30, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [07a115654d](https://linux-hardware.org/?probe=07a115654d) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [970d30df6d](https://linux-hardware.org/?probe=970d30df6d) | Apr 29, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [94d74e9b78](https://linux-hardware.org/?probe=94d74e9b78) | Apr 29, 2022 |
| ASRock        | A520M Pro4                  | Desktop     | [45630a42df](https://linux-hardware.org/?probe=45630a42df) | Apr 29, 2022 |
| Dell          | 0J37VM A00                  | Desktop     | [76f13aa200](https://linux-hardware.org/?probe=76f13aa200) | Apr 28, 2022 |
| Dell          | G3 3500                     | Notebook    | [e3f0210b87](https://linux-hardware.org/?probe=e3f0210b87) | Apr 24, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [a934bef382](https://linux-hardware.org/?probe=a934bef382) | Apr 24, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [3c1ff82bb0](https://linux-hardware.org/?probe=3c1ff82bb0) | Apr 24, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [b61b2af9eb](https://linux-hardware.org/?probe=b61b2af9eb) | Apr 23, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [82b11931ed](https://linux-hardware.org/?probe=82b11931ed) | Apr 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6af0b2a3c9](https://linux-hardware.org/?probe=6af0b2a3c9) | Apr 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [8273c9ecb4](https://linux-hardware.org/?probe=8273c9ecb4) | Apr 20, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [4121c8fcc2](https://linux-hardware.org/?probe=4121c8fcc2) | Apr 20, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | Notebook    | [9ffcb6bf7a](https://linux-hardware.org/?probe=9ffcb6bf7a) | Apr 18, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [fb3e0b6b22](https://linux-hardware.org/?probe=fb3e0b6b22) | Apr 18, 2022 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [fa96d5405d](https://linux-hardware.org/?probe=fa96d5405d) | Apr 17, 2022 |
| ASRockRack    | X470D4U                     | Desktop     | [1b9b990e65](https://linux-hardware.org/?probe=1b9b990e65) | Apr 17, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [217905d42a](https://linux-hardware.org/?probe=217905d42a) | Apr 17, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | Notebook    | [00a23bc10c](https://linux-hardware.org/?probe=00a23bc10c) | Apr 17, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [47fc027d41](https://linux-hardware.org/?probe=47fc027d41) | Apr 17, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [9eac0ebbce](https://linux-hardware.org/?probe=9eac0ebbce) | Apr 17, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [46dd37cb4b](https://linux-hardware.org/?probe=46dd37cb4b) | Apr 16, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [2a3f36f9c0](https://linux-hardware.org/?probe=2a3f36f9c0) | Apr 16, 2022 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [474bb81b18](https://linux-hardware.org/?probe=474bb81b18) | Apr 15, 2022 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [f6a1a50a75](https://linux-hardware.org/?probe=f6a1a50a75) | Apr 15, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [d14605acc1](https://linux-hardware.org/?probe=d14605acc1) | Apr 15, 2022 |
| ASUSTek       | Z97-K/USB                   | Desktop     | [16aaadda77](https://linux-hardware.org/?probe=16aaadda77) | Apr 14, 2022 |
| Gigabyte      | B460 HD3                    | Desktop     | [c3c9ea3a20](https://linux-hardware.org/?probe=c3c9ea3a20) | Apr 14, 2022 |
| ASRock        | A320M-ITX                   | Desktop     | [eaf6bbd74e](https://linux-hardware.org/?probe=eaf6bbd74e) | Apr 13, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [8d091affca](https://linux-hardware.org/?probe=8d091affca) | Apr 13, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [5e6ce90c93](https://linux-hardware.org/?probe=5e6ce90c93) | Apr 13, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [cfd276f151](https://linux-hardware.org/?probe=cfd276f151) | Apr 13, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [5620bf468d](https://linux-hardware.org/?probe=5620bf468d) | Apr 13, 2022 |
| Dell          | 084YMW A05                  | Server      | [f08f5999ac](https://linux-hardware.org/?probe=f08f5999ac) | Apr 13, 2022 |
| Dell          | G5 5505                     | Notebook    | [ce1fc33387](https://linux-hardware.org/?probe=ce1fc33387) | Apr 13, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [dccdc2c9f5](https://linux-hardware.org/?probe=dccdc2c9f5) | Apr 12, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [68dd0c90a1](https://linux-hardware.org/?probe=68dd0c90a1) | Apr 12, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [45472dad72](https://linux-hardware.org/?probe=45472dad72) | Apr 12, 2022 |
| HP            | ProBook 6570b               | Notebook    | [63d922ecdd](https://linux-hardware.org/?probe=63d922ecdd) | Apr 12, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [7a26d3fc81](https://linux-hardware.org/?probe=7a26d3fc81) | Apr 12, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [2202a95625](https://linux-hardware.org/?probe=2202a95625) | Apr 12, 2022 |
| HP            | ProBook 6570b               | Notebook    | [87414e70aa](https://linux-hardware.org/?probe=87414e70aa) | Apr 11, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [51c96e48de](https://linux-hardware.org/?probe=51c96e48de) | Apr 10, 2022 |
| Dell          | Precision 7560              | Notebook    | [f8641cc115](https://linux-hardware.org/?probe=f8641cc115) | Apr 10, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [212412e4d5](https://linux-hardware.org/?probe=212412e4d5) | Apr 09, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [1bd70fbd59](https://linux-hardware.org/?probe=1bd70fbd59) | Apr 09, 2022 |
| Gigabyte      | H470 HD3                    | Desktop     | [5ce5c54ecd](https://linux-hardware.org/?probe=5ce5c54ecd) | Apr 09, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [ed2dd10e6e](https://linux-hardware.org/?probe=ed2dd10e6e) | Apr 09, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [18fb9eceac](https://linux-hardware.org/?probe=18fb9eceac) | Apr 09, 2022 |
| System76      | Gazelle                     | Notebook    | [9edcac1b2c](https://linux-hardware.org/?probe=9edcac1b2c) | Apr 09, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [b7b2d796d9](https://linux-hardware.org/?probe=b7b2d796d9) | Apr 08, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [ce26da001a](https://linux-hardware.org/?probe=ce26da001a) | Apr 07, 2022 |
| System76      | Gazelle                     | Notebook    | [e22baecee4](https://linux-hardware.org/?probe=e22baecee4) | Apr 07, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [68be7a767a](https://linux-hardware.org/?probe=68be7a767a) | Apr 07, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [30cd3d5d00](https://linux-hardware.org/?probe=30cd3d5d00) | Apr 06, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [8aad15d96c](https://linux-hardware.org/?probe=8aad15d96c) | Apr 06, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [d51c68f84e](https://linux-hardware.org/?probe=d51c68f84e) | Apr 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [3f086610fc](https://linux-hardware.org/?probe=3f086610fc) | Apr 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [403a6830d9](https://linux-hardware.org/?probe=403a6830d9) | Apr 04, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [5bcff46ee9](https://linux-hardware.org/?probe=5bcff46ee9) | Apr 04, 2022 |
| Timi          | A35                         | Notebook    | [90a30461d2](https://linux-hardware.org/?probe=90a30461d2) | Apr 03, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [368a64422d](https://linux-hardware.org/?probe=368a64422d) | Apr 03, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [348ccc5750](https://linux-hardware.org/?probe=348ccc5750) | Apr 01, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [32eabd9ac8](https://linux-hardware.org/?probe=32eabd9ac8) | Apr 01, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [04f5858a30](https://linux-hardware.org/?probe=04f5858a30) | Apr 01, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [b47301d663](https://linux-hardware.org/?probe=b47301d663) | Mar 31, 2022 |
| ASRock        | Z170A-X1                    | Desktop     | [9e1cc71d24](https://linux-hardware.org/?probe=9e1cc71d24) | Mar 31, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [11ca55cd73](https://linux-hardware.org/?probe=11ca55cd73) | Mar 31, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [9ebb4c0fd3](https://linux-hardware.org/?probe=9ebb4c0fd3) | Mar 31, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [5240890472](https://linux-hardware.org/?probe=5240890472) | Mar 29, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [27768b901a](https://linux-hardware.org/?probe=27768b901a) | Mar 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6af3c57a8a](https://linux-hardware.org/?probe=6af3c57a8a) | Mar 24, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [e0ae9fa252](https://linux-hardware.org/?probe=e0ae9fa252) | Mar 24, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [801fa902d0](https://linux-hardware.org/?probe=801fa902d0) | Mar 24, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [69919648c7](https://linux-hardware.org/?probe=69919648c7) | Mar 24, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [5cde1a4e83](https://linux-hardware.org/?probe=5cde1a4e83) | Mar 24, 2022 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [33f98f8274](https://linux-hardware.org/?probe=33f98f8274) | Mar 23, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [4b3bd32143](https://linux-hardware.org/?probe=4b3bd32143) | Mar 23, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | Notebook    | [282dfe7eb0](https://linux-hardware.org/?probe=282dfe7eb0) | Mar 23, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [6dddf500c7](https://linux-hardware.org/?probe=6dddf500c7) | Mar 22, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [e39c413976](https://linux-hardware.org/?probe=e39c413976) | Mar 21, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [593bf6f937](https://linux-hardware.org/?probe=593bf6f937) | Mar 21, 2022 |
| Unknown       | Unknown                     | Soc         | [dad2f6c4ba](https://linux-hardware.org/?probe=dad2f6c4ba) | Mar 20, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [906f450dd5](https://linux-hardware.org/?probe=906f450dd5) | Mar 20, 2022 |
| BANGHO        | MAX G0101                   | Notebook    | [b40c195d54](https://linux-hardware.org/?probe=b40c195d54) | Mar 20, 2022 |
| Dell          | XPS 12-9Q33                 | Notebook    | [f4829632f8](https://linux-hardware.org/?probe=f4829632f8) | Mar 20, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [6efb7791bb](https://linux-hardware.org/?probe=6efb7791bb) | Mar 19, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [a2b06f49d3](https://linux-hardware.org/?probe=a2b06f49d3) | Mar 18, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [9e32abccd6](https://linux-hardware.org/?probe=9e32abccd6) | Mar 18, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [3be092b600](https://linux-hardware.org/?probe=3be092b600) | Mar 18, 2022 |
| MSI           | MS-7A34                     | Notebook    | [27f8a2eb1f](https://linux-hardware.org/?probe=27f8a2eb1f) | Mar 18, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [70021af77a](https://linux-hardware.org/?probe=70021af77a) | Mar 15, 2022 |
| MSI           | B560M PRO-VDH WIFI          | Desktop     | [c15007b668](https://linux-hardware.org/?probe=c15007b668) | Mar 15, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [adad5f6ce0](https://linux-hardware.org/?probe=adad5f6ce0) | Mar 15, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [7c09492e3b](https://linux-hardware.org/?probe=7c09492e3b) | Mar 14, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [f7e85dbf71](https://linux-hardware.org/?probe=f7e85dbf71) | Mar 14, 2022 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [707cb5ce3b](https://linux-hardware.org/?probe=707cb5ce3b) | Mar 14, 2022 |
| Intel         | DH61WW AAG23116-302         | Desktop     | [20682db2fa](https://linux-hardware.org/?probe=20682db2fa) | Mar 14, 2022 |
| Alienware     | 0TYR0X A00                  | Desktop     | [b82ab5d2d7](https://linux-hardware.org/?probe=b82ab5d2d7) | Mar 14, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [9bd0fc9e48](https://linux-hardware.org/?probe=9bd0fc9e48) | Mar 14, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [6b45f989ae](https://linux-hardware.org/?probe=6b45f989ae) | Mar 13, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [624daf4b10](https://linux-hardware.org/?probe=624daf4b10) | Mar 12, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [3f58a0f2a4](https://linux-hardware.org/?probe=3f58a0f2a4) | Mar 11, 2022 |
| Framework     | Laptop                      | Notebook    | [8902c057fb](https://linux-hardware.org/?probe=8902c057fb) | Mar 10, 2022 |
| Dell          | 0J37VM A00                  | Desktop     | [a78d4c99e3](https://linux-hardware.org/?probe=a78d4c99e3) | Mar 09, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [7eea4038f0](https://linux-hardware.org/?probe=7eea4038f0) | Mar 09, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [fe3e35f15b](https://linux-hardware.org/?probe=fe3e35f15b) | Mar 09, 2022 |
| Framework     | Laptop                      | Notebook    | [e17db20b1c](https://linux-hardware.org/?probe=e17db20b1c) | Mar 08, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [b3ba67d085](https://linux-hardware.org/?probe=b3ba67d085) | Mar 08, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [d6d94816fc](https://linux-hardware.org/?probe=d6d94816fc) | Mar 08, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f50abf2114](https://linux-hardware.org/?probe=f50abf2114) | Mar 08, 2022 |
| Timi          | RedmiBook Air 13            | Notebook    | [cb1fd6a511](https://linux-hardware.org/?probe=cb1fd6a511) | Mar 08, 2022 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [bc052daf77](https://linux-hardware.org/?probe=bc052daf77) | Mar 07, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [f89153c3e1](https://linux-hardware.org/?probe=f89153c3e1) | Mar 05, 2022 |
| Toshiba       | Satellite L50-C             | Notebook    | [0e6289a2ad](https://linux-hardware.org/?probe=0e6289a2ad) | Mar 04, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f1b0d6e847](https://linux-hardware.org/?probe=f1b0d6e847) | Mar 03, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [d9c28765e7](https://linux-hardware.org/?probe=d9c28765e7) | Mar 03, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [44656b1bd4](https://linux-hardware.org/?probe=44656b1bd4) | Mar 03, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [ca53435b36](https://linux-hardware.org/?probe=ca53435b36) | Mar 03, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [5c95114871](https://linux-hardware.org/?probe=5c95114871) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6931b9fe82](https://linux-hardware.org/?probe=6931b9fe82) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [842379fc35](https://linux-hardware.org/?probe=842379fc35) | Mar 01, 2022 |
| Alienware     | 0TYR0X A00                  | Desktop     | [17eda5de26](https://linux-hardware.org/?probe=17eda5de26) | Feb 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [ee935ed8be](https://linux-hardware.org/?probe=ee935ed8be) | Feb 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [875e06d62c](https://linux-hardware.org/?probe=875e06d62c) | Feb 27, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [c97a79e04f](https://linux-hardware.org/?probe=c97a79e04f) | Feb 27, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [a7fbe4b7c8](https://linux-hardware.org/?probe=a7fbe4b7c8) | Feb 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [6d4c3afa7f](https://linux-hardware.org/?probe=6d4c3afa7f) | Feb 27, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [a5242ed058](https://linux-hardware.org/?probe=a5242ed058) | Feb 26, 2022 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | Notebook    | [0022f4a8cc](https://linux-hardware.org/?probe=0022f4a8cc) | Feb 26, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [071dd25266](https://linux-hardware.org/?probe=071dd25266) | Feb 24, 2022 |
| Alienware     | 0TYR0X A00                  | Desktop     | [892e886901](https://linux-hardware.org/?probe=892e886901) | Feb 23, 2022 |
| Alienware     | 0TYR0X A00                  | Desktop     | [71cac3ebdd](https://linux-hardware.org/?probe=71cac3ebdd) | Feb 22, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [cde7566ecb](https://linux-hardware.org/?probe=cde7566ecb) | Feb 22, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [302433b9e3](https://linux-hardware.org/?probe=302433b9e3) | Feb 21, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [6d5688db26](https://linux-hardware.org/?probe=6d5688db26) | Feb 21, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [c7cd5ce50d](https://linux-hardware.org/?probe=c7cd5ce50d) | Feb 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [160ecaffd8](https://linux-hardware.org/?probe=160ecaffd8) | Feb 21, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [5dea4207b1](https://linux-hardware.org/?probe=5dea4207b1) | Feb 20, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [1998552d88](https://linux-hardware.org/?probe=1998552d88) | Feb 20, 2022 |
| MSI           | H81I                        | Desktop     | [c556e9c713](https://linux-hardware.org/?probe=c556e9c713) | Feb 20, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [1429fd9ed5](https://linux-hardware.org/?probe=1429fd9ed5) | Feb 20, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [5c3eba73d5](https://linux-hardware.org/?probe=5c3eba73d5) | Feb 20, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [8b0dc90a9e](https://linux-hardware.org/?probe=8b0dc90a9e) | Feb 19, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [859adc5b97](https://linux-hardware.org/?probe=859adc5b97) | Feb 19, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [9df089b1ef](https://linux-hardware.org/?probe=9df089b1ef) | Feb 19, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [eddf69336b](https://linux-hardware.org/?probe=eddf69336b) | Feb 18, 2022 |
| Gigabyte      | B460 HD3                    | Desktop     | [661166a163](https://linux-hardware.org/?probe=661166a163) | Feb 17, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [6278830433](https://linux-hardware.org/?probe=6278830433) | Feb 17, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [018fa00447](https://linux-hardware.org/?probe=018fa00447) | Feb 17, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [7737b54f68](https://linux-hardware.org/?probe=7737b54f68) | Feb 16, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [e54664c1be](https://linux-hardware.org/?probe=e54664c1be) | Feb 15, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [92456282bc](https://linux-hardware.org/?probe=92456282bc) | Feb 14, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [c1227bf037](https://linux-hardware.org/?probe=c1227bf037) | Feb 14, 2022 |
| YANYU         | H17SL                       | Desktop     | [0a6638d9c9](https://linux-hardware.org/?probe=0a6638d9c9) | Feb 14, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [27dad40db4](https://linux-hardware.org/?probe=27dad40db4) | Feb 13, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [8286f26e6e](https://linux-hardware.org/?probe=8286f26e6e) | Feb 12, 2022 |
| Supermicro    | X10SDV-2C-TP4F              | Server      | [e60ec405af](https://linux-hardware.org/?probe=e60ec405af) | Feb 12, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [a8d3ef29f1](https://linux-hardware.org/?probe=a8d3ef29f1) | Feb 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [5836ccecc2](https://linux-hardware.org/?probe=5836ccecc2) | Feb 10, 2022 |
| Supermicro    | X10SDV-2C-TP4F              | Server      | [e761a368c3](https://linux-hardware.org/?probe=e761a368c3) | Feb 10, 2022 |
| MSI           | GS63VR 6RF                  | Notebook    | [c20c87027e](https://linux-hardware.org/?probe=c20c87027e) | Feb 10, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [9f05ddfb03](https://linux-hardware.org/?probe=9f05ddfb03) | Feb 08, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [49cf4eba76](https://linux-hardware.org/?probe=49cf4eba76) | Feb 08, 2022 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [661baafcd7](https://linux-hardware.org/?probe=661baafcd7) | Feb 07, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [68c1afd184](https://linux-hardware.org/?probe=68c1afd184) | Feb 06, 2022 |
| YANYU         | H17SL                       | Desktop     | [cd763ca612](https://linux-hardware.org/?probe=cd763ca612) | Feb 06, 2022 |
| ASUSTek       | 900                         | Notebook    | [88ce413793](https://linux-hardware.org/?probe=88ce413793) | Feb 06, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [8f79e4d763](https://linux-hardware.org/?probe=8f79e4d763) | Feb 06, 2022 |
| Supermicro    | A1SRM-2758F                 | Desktop     | [33b8806332](https://linux-hardware.org/?probe=33b8806332) | Feb 05, 2022 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [f79196e39c](https://linux-hardware.org/?probe=f79196e39c) | Feb 05, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [59d4e2a5b2](https://linux-hardware.org/?probe=59d4e2a5b2) | Feb 04, 2022 |
| Gigabyte      | Z490 UD                     | Desktop     | [b571c22d4f](https://linux-hardware.org/?probe=b571c22d4f) | Feb 04, 2022 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [4a717f6348](https://linux-hardware.org/?probe=4a717f6348) | Feb 02, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [d424a8e145](https://linux-hardware.org/?probe=d424a8e145) | Feb 01, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [89dbe92caf](https://linux-hardware.org/?probe=89dbe92caf) | Feb 01, 2022 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [7f7720253e](https://linux-hardware.org/?probe=7f7720253e) | Feb 01, 2022 |
| Samsung       | RC530/RC730                 | Notebook    | [c4651bdbc6](https://linux-hardware.org/?probe=c4651bdbc6) | Jan 31, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02E0... | Notebook    | [e35fffc0dd](https://linux-hardware.org/?probe=e35fffc0dd) | Jan 30, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [2f36ebcc7e](https://linux-hardware.org/?probe=2f36ebcc7e) | Jan 30, 2022 |
| MSI           | GS63VR 6RF                  | Notebook    | [4873365af6](https://linux-hardware.org/?probe=4873365af6) | Jan 30, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [f49f9dddd2](https://linux-hardware.org/?probe=f49f9dddd2) | Jan 29, 2022 |
| Dell          | Precision 7520              | Notebook    | [4cdcfc0e31](https://linux-hardware.org/?probe=4cdcfc0e31) | Jan 29, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [cd1ab231e7](https://linux-hardware.org/?probe=cd1ab231e7) | Jan 28, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02E0... | Notebook    | [999e47c570](https://linux-hardware.org/?probe=999e47c570) | Jan 28, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [6b7cf2d570](https://linux-hardware.org/?probe=6b7cf2d570) | Jan 27, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [c021622ad4](https://linux-hardware.org/?probe=c021622ad4) | Jan 27, 2022 |
| ASRock        | A88M-G                      | Desktop     | [bb3847af5e](https://linux-hardware.org/?probe=bb3847af5e) | Jan 27, 2022 |
| ASRock        | A88M-G                      | Desktop     | [7f86f91b8f](https://linux-hardware.org/?probe=7f86f91b8f) | Jan 27, 2022 |
| Timi          | RedmiBook 13                | Notebook    | [e20538f56a](https://linux-hardware.org/?probe=e20538f56a) | Jan 26, 2022 |
| Lenovo        | Legion 5P 15IMH05 82AW      | Notebook    | [1abbb329fa](https://linux-hardware.org/?probe=1abbb329fa) | Jan 26, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [656da02110](https://linux-hardware.org/?probe=656da02110) | Jan 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [a4f6a4a38e](https://linux-hardware.org/?probe=a4f6a4a38e) | Jan 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [9e4f498056](https://linux-hardware.org/?probe=9e4f498056) | Jan 24, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [1721bed3e1](https://linux-hardware.org/?probe=1721bed3e1) | Jan 24, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [db8b77c1ff](https://linux-hardware.org/?probe=db8b77c1ff) | Jan 23, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [1ccb1fd970](https://linux-hardware.org/?probe=1ccb1fd970) | Jan 23, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [7e7edbe447](https://linux-hardware.org/?probe=7e7edbe447) | Jan 23, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [3c430f09c4](https://linux-hardware.org/?probe=3c430f09c4) | Jan 23, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [ab4793dc5e](https://linux-hardware.org/?probe=ab4793dc5e) | Jan 22, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [7a52dda8cc](https://linux-hardware.org/?probe=7a52dda8cc) | Jan 22, 2022 |
| Gigabyte      | Z490 UD                     | Desktop     | [eac4639ad2](https://linux-hardware.org/?probe=eac4639ad2) | Jan 22, 2022 |
| MSI           | GE73 Raider RGB 8RF         | Notebook    | [a5a825a072](https://linux-hardware.org/?probe=a5a825a072) | Jan 22, 2022 |
| Lenovo        | ThinkPad 20FMCT01WW         | Notebook    | [4bd81196a0](https://linux-hardware.org/?probe=4bd81196a0) | Jan 21, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [0799e18f8b](https://linux-hardware.org/?probe=0799e18f8b) | Jan 20, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [d1697052d6](https://linux-hardware.org/?probe=d1697052d6) | Jan 20, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [597fae9cb6](https://linux-hardware.org/?probe=597fae9cb6) | Jan 19, 2022 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [65ce2eb070](https://linux-hardware.org/?probe=65ce2eb070) | Jan 19, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [5f904131f5](https://linux-hardware.org/?probe=5f904131f5) | Jan 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [d786a0b993](https://linux-hardware.org/?probe=d786a0b993) | Jan 17, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [81642886bd](https://linux-hardware.org/?probe=81642886bd) | Jan 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [6af6121c33](https://linux-hardware.org/?probe=6af6121c33) | Jan 17, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [93dfa22733](https://linux-hardware.org/?probe=93dfa22733) | Jan 17, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [1612c5ca91](https://linux-hardware.org/?probe=1612c5ca91) | Jan 17, 2022 |
| Dell          | Precision 3561              | Notebook    | [f5417a1852](https://linux-hardware.org/?probe=f5417a1852) | Jan 16, 2022 |
| ASRock        | AM1H-ITX                    | Desktop     | [d22612635e](https://linux-hardware.org/?probe=d22612635e) | Jan 16, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [2aa146518a](https://linux-hardware.org/?probe=2aa146518a) | Jan 16, 2022 |
| Gigabyte      | AX370-Gaming 3-CF           | Desktop     | [73773b7de6](https://linux-hardware.org/?probe=73773b7de6) | Jan 16, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [a3711dfcf9](https://linux-hardware.org/?probe=a3711dfcf9) | Jan 15, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [c973a9bc0d](https://linux-hardware.org/?probe=c973a9bc0d) | Jan 15, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [e69fb99ebf](https://linux-hardware.org/?probe=e69fb99ebf) | Jan 14, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [cdb65d6460](https://linux-hardware.org/?probe=cdb65d6460) | Jan 13, 2022 |
| TYAN Compu... | S7025                       | Server      | [c5f294d367](https://linux-hardware.org/?probe=c5f294d367) | Jan 12, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [175b161d3f](https://linux-hardware.org/?probe=175b161d3f) | Jan 11, 2022 |
| Samsung       | 700T1C                      | Notebook    | [349d306d37](https://linux-hardware.org/?probe=349d306d37) | Jan 11, 2022 |
| Dell          | Inspiron 5402               | Notebook    | [6b764029b7](https://linux-hardware.org/?probe=6b764029b7) | Jan 11, 2022 |
| Dell          | Inspiron 5402               | Notebook    | [60f264617e](https://linux-hardware.org/?probe=60f264617e) | Jan 11, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [5f92f3376e](https://linux-hardware.org/?probe=5f92f3376e) | Jan 11, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [d46da820e0](https://linux-hardware.org/?probe=d46da820e0) | Jan 10, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [f6376ab7d5](https://linux-hardware.org/?probe=f6376ab7d5) | Jan 10, 2022 |
| ASRock        | AM1H-ITX                    | Desktop     | [32aec4ead0](https://linux-hardware.org/?probe=32aec4ead0) | Jan 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [dcf0799dd1](https://linux-hardware.org/?probe=dcf0799dd1) | Jan 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [fb3838c0db](https://linux-hardware.org/?probe=fb3838c0db) | Jan 10, 2022 |
| ASRock        | Q1900-ITX                   | Desktop     | [a0983541e3](https://linux-hardware.org/?probe=a0983541e3) | Jan 08, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [a519d3f9af](https://linux-hardware.org/?probe=a519d3f9af) | Jan 07, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [596fafa091](https://linux-hardware.org/?probe=596fafa091) | Jan 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [639c7cbb68](https://linux-hardware.org/?probe=639c7cbb68) | Jan 06, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [d4b7cd87ac](https://linux-hardware.org/?probe=d4b7cd87ac) | Jan 05, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [8107f2613f](https://linux-hardware.org/?probe=8107f2613f) | Jan 05, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [704e9c09ad](https://linux-hardware.org/?probe=704e9c09ad) | Jan 05, 2022 |
| ASRock        | Q1900-ITX                   | Desktop     | [e7b19454b7](https://linux-hardware.org/?probe=e7b19454b7) | Jan 04, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [75edf90312](https://linux-hardware.org/?probe=75edf90312) | Jan 03, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [519b9f223e](https://linux-hardware.org/?probe=519b9f223e) | Jan 03, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [0cf6f2102c](https://linux-hardware.org/?probe=0cf6f2102c) | Jan 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [08b04c15d3](https://linux-hardware.org/?probe=08b04c15d3) | Jan 03, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [87bdd946c8](https://linux-hardware.org/?probe=87bdd946c8) | Jan 02, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [cd39962883](https://linux-hardware.org/?probe=cd39962883) | Jan 02, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [6a1f7a20cf](https://linux-hardware.org/?probe=6a1f7a20cf) | Jan 02, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [bd7de25478](https://linux-hardware.org/?probe=bd7de25478) | Jan 02, 2022 |
| Dell          | Precision 7560              | Notebook    | [158ff657e7](https://linux-hardware.org/?probe=158ff657e7) | Jan 02, 2022 |
| Timi          | RedmiBook 13                | Notebook    | [528d0d32b4](https://linux-hardware.org/?probe=528d0d32b4) | Jan 01, 2022 |
| Timi          | A35                         | Notebook    | [253959bb70](https://linux-hardware.org/?probe=253959bb70) | Dec 30, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [64743b9e56](https://linux-hardware.org/?probe=64743b9e56) | Dec 30, 2021 |
| TYAN Compu... | S7025                       | Server      | [4a4fe05b48](https://linux-hardware.org/?probe=4a4fe05b48) | Dec 27, 2021 |
| Dell          | XPS 17 9710                 | Notebook    | [ac139db0b3](https://linux-hardware.org/?probe=ac139db0b3) | Dec 27, 2021 |
| MSI           | Delta 15 A5EFK              | Notebook    | [e874b85848](https://linux-hardware.org/?probe=e874b85848) | Dec 26, 2021 |
| Lenovo        | ThinkPad T480s 20L7001MR... | Notebook    | [199482a1fe](https://linux-hardware.org/?probe=199482a1fe) | Dec 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [913bb7bf0b](https://linux-hardware.org/?probe=913bb7bf0b) | Dec 25, 2021 |
| Timi          | A35                         | Notebook    | [66e9c6919d](https://linux-hardware.org/?probe=66e9c6919d) | Dec 24, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [83ff6966e1](https://linux-hardware.org/?probe=83ff6966e1) | Dec 24, 2021 |
| Apple         | MacBook10,1                 | Notebook    | [4b98d2c8ba](https://linux-hardware.org/?probe=4b98d2c8ba) | Dec 24, 2021 |
| EVGA          | Z390 DARK                   | Desktop     | [7672395a1c](https://linux-hardware.org/?probe=7672395a1c) | Dec 24, 2021 |
| Dell          | Inspiron 15 5510            | Notebook    | [060d274be1](https://linux-hardware.org/?probe=060d274be1) | Dec 24, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [1695a19b52](https://linux-hardware.org/?probe=1695a19b52) | Dec 24, 2021 |
| Intel         | S1200RP G62251-406          | Server      | [986c6d1f51](https://linux-hardware.org/?probe=986c6d1f51) | Dec 24, 2021 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [2144a3a32c](https://linux-hardware.org/?probe=2144a3a32c) | Dec 23, 2021 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [53288b1a8b](https://linux-hardware.org/?probe=53288b1a8b) | Dec 23, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [a450e584b2](https://linux-hardware.org/?probe=a450e584b2) | Dec 22, 2021 |
| Dell          | Inspiron 15 5510            | Notebook    | [e4d91f5636](https://linux-hardware.org/?probe=e4d91f5636) | Dec 21, 2021 |
| Framework     | Laptop                      | Notebook    | [33bb6590a6](https://linux-hardware.org/?probe=33bb6590a6) | Dec 21, 2021 |
| Dell          | Inspiron 15 5510            | Notebook    | [2018752b06](https://linux-hardware.org/?probe=2018752b06) | Dec 21, 2021 |
| TYAN Compu... | S7025                       | Server      | [88ee246f4e](https://linux-hardware.org/?probe=88ee246f4e) | Dec 21, 2021 |
| Samsung       | 950QDB                      | Convertible | [1b6565f7a5](https://linux-hardware.org/?probe=1b6565f7a5) | Dec 21, 2021 |
| Samsung       | 950QDB                      | Convertible | [307042119a](https://linux-hardware.org/?probe=307042119a) | Dec 21, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [201e93fd24](https://linux-hardware.org/?probe=201e93fd24) | Dec 20, 2021 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [b03f7a8ab8](https://linux-hardware.org/?probe=b03f7a8ab8) | Dec 20, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [fbd0755545](https://linux-hardware.org/?probe=fbd0755545) | Dec 19, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [d01abdcb39](https://linux-hardware.org/?probe=d01abdcb39) | Dec 19, 2021 |
| Dell          | Latitude 5420               | Notebook    | [f8313f07c4](https://linux-hardware.org/?probe=f8313f07c4) | Dec 18, 2021 |
| Samsung       | 700T1C                      | Notebook    | [f63266db56](https://linux-hardware.org/?probe=f63266db56) | Dec 18, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ce3508ebb4](https://linux-hardware.org/?probe=ce3508ebb4) | Dec 17, 2021 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [36ad5ef96a](https://linux-hardware.org/?probe=36ad5ef96a) | Dec 16, 2021 |
| BESSTAR Te... | ATB15                       | Server      | [783d1d7b6f](https://linux-hardware.org/?probe=783d1d7b6f) | Dec 16, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [a2ee48eeb1](https://linux-hardware.org/?probe=a2ee48eeb1) | Dec 16, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [bf884733a1](https://linux-hardware.org/?probe=bf884733a1) | Dec 16, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [b6d326beab](https://linux-hardware.org/?probe=b6d326beab) | Dec 16, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [61d4bff2bd](https://linux-hardware.org/?probe=61d4bff2bd) | Dec 15, 2021 |
| MSI           | Z87-G45 GAMING              | Desktop     | [882428b431](https://linux-hardware.org/?probe=882428b431) | Dec 15, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [d94711b81b](https://linux-hardware.org/?probe=d94711b81b) | Dec 13, 2021 |
| Dell          | XPS 17 9710                 | Notebook    | [ade9c0e3ec](https://linux-hardware.org/?probe=ade9c0e3ec) | Dec 13, 2021 |
| ASUSTek       | M3N78-EM                    | Desktop     | [bf180c5c33](https://linux-hardware.org/?probe=bf180c5c33) | Dec 11, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [ee63a84605](https://linux-hardware.org/?probe=ee63a84605) | Dec 11, 2021 |
| Dell          | XPS 17 9710                 | Notebook    | [fd6cff7345](https://linux-hardware.org/?probe=fd6cff7345) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c62460798a](https://linux-hardware.org/?probe=c62460798a) | Dec 09, 2021 |
| Toshiba       | Satellite C850D-118         | Notebook    | [b15f2e2c92](https://linux-hardware.org/?probe=b15f2e2c92) | Dec 09, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4b39700892](https://linux-hardware.org/?probe=4b39700892) | Dec 09, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [53fb790458](https://linux-hardware.org/?probe=53fb790458) | Dec 08, 2021 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [87c78340f0](https://linux-hardware.org/?probe=87c78340f0) | Dec 07, 2021 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [208868fbae](https://linux-hardware.org/?probe=208868fbae) | Dec 07, 2021 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | Desktop     | [b92f432637](https://linux-hardware.org/?probe=b92f432637) | Dec 07, 2021 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | Desktop     | [d8f50aaa2e](https://linux-hardware.org/?probe=d8f50aaa2e) | Dec 07, 2021 |
| ASUSTek       | X200MA                      | Notebook    | [c81483b4db](https://linux-hardware.org/?probe=c81483b4db) | Dec 04, 2021 |
| Samsung       | RC530/RC730                 | Notebook    | [6105853b97](https://linux-hardware.org/?probe=6105853b97) | Dec 04, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [6649bea1f8](https://linux-hardware.org/?probe=6649bea1f8) | Dec 04, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [723e2a158a](https://linux-hardware.org/?probe=723e2a158a) | Dec 03, 2021 |
| Dell          | 0J584C A00                  | Desktop     | [d443412bd4](https://linux-hardware.org/?probe=d443412bd4) | Dec 03, 2021 |
| Samsung       | 950QCG                      | Convertible | [9c9a02c704](https://linux-hardware.org/?probe=9c9a02c704) | Dec 03, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [903f3e93ee](https://linux-hardware.org/?probe=903f3e93ee) | Dec 03, 2021 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [e155882ffa](https://linux-hardware.org/?probe=e155882ffa) | Dec 02, 2021 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [5c530c94b3](https://linux-hardware.org/?probe=5c530c94b3) | Dec 02, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [7a8a79d813](https://linux-hardware.org/?probe=7a8a79d813) | Dec 02, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [86f5c0bc34](https://linux-hardware.org/?probe=86f5c0bc34) | Nov 30, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [e06c73ada9](https://linux-hardware.org/?probe=e06c73ada9) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [ad15be0510](https://linux-hardware.org/?probe=ad15be0510) | Nov 29, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [baa3bf4a04](https://linux-hardware.org/?probe=baa3bf4a04) | Nov 27, 2021 |
| Timi          | A35                         | Notebook    | [d1461858c8](https://linux-hardware.org/?probe=d1461858c8) | Nov 27, 2021 |
| Toshiba       | Satellite C850D-118         | Notebook    | [db07af607f](https://linux-hardware.org/?probe=db07af607f) | Nov 26, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [8876123555](https://linux-hardware.org/?probe=8876123555) | Nov 26, 2021 |
| Timi          | A35                         | Notebook    | [ce66e74002](https://linux-hardware.org/?probe=ce66e74002) | Nov 25, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [b0329b0b3f](https://linux-hardware.org/?probe=b0329b0b3f) | Nov 25, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [4492677869](https://linux-hardware.org/?probe=4492677869) | Nov 24, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [1bb2b21d60](https://linux-hardware.org/?probe=1bb2b21d60) | Nov 24, 2021 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [58684dd498](https://linux-hardware.org/?probe=58684dd498) | Nov 23, 2021 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [8145468390](https://linux-hardware.org/?probe=8145468390) | Nov 22, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | Notebook    | [6eca4a1be2](https://linux-hardware.org/?probe=6eca4a1be2) | Nov 22, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | Notebook    | [6c92c6ecbb](https://linux-hardware.org/?probe=6c92c6ecbb) | Nov 22, 2021 |
| SIEMENS       | SIMATIC Field PG M6         | Notebook    | [a0e1ef3935](https://linux-hardware.org/?probe=a0e1ef3935) | Nov 22, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [89c87a0f8c](https://linux-hardware.org/?probe=89c87a0f8c) | Nov 21, 2021 |
| HP            | Compaq 6730b (KE717AV)      | Notebook    | [71527b8152](https://linux-hardware.org/?probe=71527b8152) | Nov 21, 2021 |
| Supermicro    | A2SDV-4C-LN8F               | Server      | [f96b0cfda0](https://linux-hardware.org/?probe=f96b0cfda0) | Nov 21, 2021 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [674bb00d63](https://linux-hardware.org/?probe=674bb00d63) | Nov 21, 2021 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [47908fe107](https://linux-hardware.org/?probe=47908fe107) | Nov 21, 2021 |
| HP            | ProLiant ML150 G6           | Desktop     | [ddb6ba2a2b](https://linux-hardware.org/?probe=ddb6ba2a2b) | Nov 21, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [f8501c9239](https://linux-hardware.org/?probe=f8501c9239) | Nov 21, 2021 |
| HP            | ProLiant ML150 G6           | Desktop     | [734028d2b9](https://linux-hardware.org/?probe=734028d2b9) | Nov 21, 2021 |
| Supermicro    | A2SDV-4C-LN8F               | Server      | [48a89bb904](https://linux-hardware.org/?probe=48a89bb904) | Nov 21, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [e2c087b9c7](https://linux-hardware.org/?probe=e2c087b9c7) | Nov 21, 2021 |
| Intel         | DP35DP AAD81073-205         | Desktop     | [be9ba487cd](https://linux-hardware.org/?probe=be9ba487cd) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | Notebook    | [3ea389d8ff](https://linux-hardware.org/?probe=3ea389d8ff) | Nov 21, 2021 |
| Intel         | DP35DP AAD81073-205         | Desktop     | [d8c73031f1](https://linux-hardware.org/?probe=d8c73031f1) | Nov 20, 2021 |
| Acer          | Aspire A715-42G             | Notebook    | [19f48288ec](https://linux-hardware.org/?probe=19f48288ec) | Nov 20, 2021 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [10578c9535](https://linux-hardware.org/?probe=10578c9535) | Nov 18, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [40748c60b0](https://linux-hardware.org/?probe=40748c60b0) | Nov 18, 2021 |
| HP            | ProBook 430 G5              | Notebook    | [634b7c7102](https://linux-hardware.org/?probe=634b7c7102) | Nov 18, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [cf48db68a3](https://linux-hardware.org/?probe=cf48db68a3) | Nov 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [05879919b0](https://linux-hardware.org/?probe=05879919b0) | Nov 17, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6d93d44cf9](https://linux-hardware.org/?probe=6d93d44cf9) | Nov 17, 2021 |
| Gigabyte      | B150M-HD3-CF                | Desktop     | [c35117afe2](https://linux-hardware.org/?probe=c35117afe2) | Nov 17, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [5f0f191f13](https://linux-hardware.org/?probe=5f0f191f13) | Nov 16, 2021 |
| MOTILE        | M142                        | Notebook    | [d56931cbc6](https://linux-hardware.org/?probe=d56931cbc6) | Nov 15, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [eafa22145d](https://linux-hardware.org/?probe=eafa22145d) | Nov 15, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [2900821ed3](https://linux-hardware.org/?probe=2900821ed3) | Nov 14, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4cfb74fb42](https://linux-hardware.org/?probe=4cfb74fb42) | Nov 14, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [5c55a759db](https://linux-hardware.org/?probe=5c55a759db) | Nov 13, 2021 |
| HP            | EliteBook 745 G6            | Notebook    | [a4bc523c79](https://linux-hardware.org/?probe=a4bc523c79) | Nov 12, 2021 |
| HP            | EliteBook 745 G6            | Notebook    | [faa7680568](https://linux-hardware.org/?probe=faa7680568) | Nov 12, 2021 |
| Lenovo        | ThinkPad E495 20NE000BGE    | Notebook    | [871e0a8d36](https://linux-hardware.org/?probe=871e0a8d36) | Nov 11, 2021 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [49148de6c4](https://linux-hardware.org/?probe=49148de6c4) | Nov 09, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | Notebook    | [531b838f59](https://linux-hardware.org/?probe=531b838f59) | Nov 09, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | Notebook    | [8ea29d23df](https://linux-hardware.org/?probe=8ea29d23df) | Nov 09, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [97e66fa893](https://linux-hardware.org/?probe=97e66fa893) | Nov 09, 2021 |
| ASUSTek       | 900                         | Notebook    | [b3f1475dcf](https://linux-hardware.org/?probe=b3f1475dcf) | Nov 08, 2021 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [efd3dadc76](https://linux-hardware.org/?probe=efd3dadc76) | Nov 08, 2021 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [76d6e63da5](https://linux-hardware.org/?probe=76d6e63da5) | Nov 07, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [fada2e4c02](https://linux-hardware.org/?probe=fada2e4c02) | Nov 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8cf09365a4](https://linux-hardware.org/?probe=8cf09365a4) | Nov 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [10faa36c81](https://linux-hardware.org/?probe=10faa36c81) | Nov 06, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [6f308039a8](https://linux-hardware.org/?probe=6f308039a8) | Nov 06, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [d1dcf79c72](https://linux-hardware.org/?probe=d1dcf79c72) | Nov 05, 2021 |
| Dell          | Latitude E7440              | Notebook    | [96a92b3d98](https://linux-hardware.org/?probe=96a92b3d98) | Nov 04, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3691e08d6d](https://linux-hardware.org/?probe=3691e08d6d) | Nov 03, 2021 |
| Samsung       | RC530/RC730                 | Notebook    | [a4d9d06231](https://linux-hardware.org/?probe=a4d9d06231) | Nov 02, 2021 |
| Intel         | S1200RP G62251-405          | Server      | [798cf3cc96](https://linux-hardware.org/?probe=798cf3cc96) | Nov 02, 2021 |
| MSI           | H110M PRO-D                 | Desktop     | [cb3dcdd186](https://linux-hardware.org/?probe=cb3dcdd186) | Nov 02, 2021 |
| MSI           | H110M PRO-D                 | Desktop     | [b53420c26a](https://linux-hardware.org/?probe=b53420c26a) | Nov 02, 2021 |
| Dell          | Latitude 7490               | Notebook    | [ea64667f2c](https://linux-hardware.org/?probe=ea64667f2c) | Nov 01, 2021 |
| Dell          | Latitude 5520               | Notebook    | [49a6b5ef90](https://linux-hardware.org/?probe=49a6b5ef90) | Nov 01, 2021 |
| Purism        | librem_15v4                 | Notebook    | [f3e5eba0c2](https://linux-hardware.org/?probe=f3e5eba0c2) | Oct 31, 2021 |
| Purism        | librem_15v4                 | Notebook    | [c74129a618](https://linux-hardware.org/?probe=c74129a618) | Oct 31, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [1719b2dc9d](https://linux-hardware.org/?probe=1719b2dc9d) | Oct 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [161865edb0](https://linux-hardware.org/?probe=161865edb0) | Oct 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a4806aa50f](https://linux-hardware.org/?probe=a4806aa50f) | Oct 30, 2021 |
| ASUSTek       | X556URK                     | Notebook    | [212240b258](https://linux-hardware.org/?probe=212240b258) | Oct 29, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [aea7d9561e](https://linux-hardware.org/?probe=aea7d9561e) | Oct 29, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [0f4ae74d8e](https://linux-hardware.org/?probe=0f4ae74d8e) | Oct 29, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [f3f75352e4](https://linux-hardware.org/?probe=f3f75352e4) | Oct 29, 2021 |
| Gigabyte      | B460 HD3                    | Desktop     | [d3aa74a821](https://linux-hardware.org/?probe=d3aa74a821) | Oct 29, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [df8ab9effb](https://linux-hardware.org/?probe=df8ab9effb) | Oct 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e9cc487951](https://linux-hardware.org/?probe=e9cc487951) | Oct 28, 2021 |
| Supermicro    | X10SRA                      | Server      | [6a333a499d](https://linux-hardware.org/?probe=6a333a499d) | Oct 28, 2021 |
| Dell          | Latitude E6530              | Notebook    | [fd1375d5f1](https://linux-hardware.org/?probe=fd1375d5f1) | Oct 28, 2021 |
| Dell          | Latitude E6530              | Notebook    | [f37394899f](https://linux-hardware.org/?probe=f37394899f) | Oct 28, 2021 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [6f6e5daf18](https://linux-hardware.org/?probe=6f6e5daf18) | Oct 28, 2021 |
| HP            | ProLiant DL380 G7           | Server      | [a9c87c6c9c](https://linux-hardware.org/?probe=a9c87c6c9c) | Oct 27, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [4b691f2884](https://linux-hardware.org/?probe=4b691f2884) | Oct 27, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [eb0c052885](https://linux-hardware.org/?probe=eb0c052885) | Oct 26, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [740c97fb1c](https://linux-hardware.org/?probe=740c97fb1c) | Oct 26, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [6105164e23](https://linux-hardware.org/?probe=6105164e23) | Oct 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [8a34d739fd](https://linux-hardware.org/?probe=8a34d739fd) | Oct 25, 2021 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [5b06944051](https://linux-hardware.org/?probe=5b06944051) | Oct 25, 2021 |
| ASUSTek       | M3A78-CM                    | Desktop     | [aa48dedaf3](https://linux-hardware.org/?probe=aa48dedaf3) | Oct 25, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [58e3f9c07f](https://linux-hardware.org/?probe=58e3f9c07f) | Oct 23, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [ba339b925b](https://linux-hardware.org/?probe=ba339b925b) | Oct 21, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [7ffce9bbc2](https://linux-hardware.org/?probe=7ffce9bbc2) | Oct 21, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [eb02a6d4d5](https://linux-hardware.org/?probe=eb02a6d4d5) | Oct 20, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [b37e349828](https://linux-hardware.org/?probe=b37e349828) | Oct 19, 2021 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [21110235eb](https://linux-hardware.org/?probe=21110235eb) | Oct 18, 2021 |
| ASRock        | X370 Killer SLI/ac          | Desktop     | [2e4c1c4527](https://linux-hardware.org/?probe=2e4c1c4527) | Oct 17, 2021 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | Desktop     | [8b5c674cb9](https://linux-hardware.org/?probe=8b5c674cb9) | Oct 17, 2021 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [e7ab53c038](https://linux-hardware.org/?probe=e7ab53c038) | Oct 15, 2021 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [42b4e70ef9](https://linux-hardware.org/?probe=42b4e70ef9) | Oct 15, 2021 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | Desktop     | [38a6005914](https://linux-hardware.org/?probe=38a6005914) | Oct 15, 2021 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | Desktop     | [a6457a6f8e](https://linux-hardware.org/?probe=a6457a6f8e) | Oct 15, 2021 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [5d6b978099](https://linux-hardware.org/?probe=5d6b978099) | Oct 14, 2021 |
| Timi          | RedmiBook 13 R              | Notebook    | [18263076ea](https://linux-hardware.org/?probe=18263076ea) | Oct 14, 2021 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [d2b877508b](https://linux-hardware.org/?probe=d2b877508b) | Oct 13, 2021 |
| Acer          | Aspire A515-55              | Notebook    | [437c8fb96b](https://linux-hardware.org/?probe=437c8fb96b) | Oct 12, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [10d09b7d77](https://linux-hardware.org/?probe=10d09b7d77) | Oct 12, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [d7a870e424](https://linux-hardware.org/?probe=d7a870e424) | Oct 11, 2021 |
| ASRock        | Z390 Extreme4               | Desktop     | [2da9a06ef2](https://linux-hardware.org/?probe=2da9a06ef2) | Oct 11, 2021 |
| Acer          | TravelMate P648-M           | Notebook    | [03350be971](https://linux-hardware.org/?probe=03350be971) | Oct 11, 2021 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [7fbd3218a8](https://linux-hardware.org/?probe=7fbd3218a8) | Oct 11, 2021 |
| Acer          | TravelMate P648-M           | Notebook    | [6e6d3fe55c](https://linux-hardware.org/?probe=6e6d3fe55c) | Oct 10, 2021 |
| IBM           | ThinkPad T43 2668Z3S        | Notebook    | [67510cc1aa](https://linux-hardware.org/?probe=67510cc1aa) | Oct 10, 2021 |
| Timi          | RedmiBook 13 R              | Notebook    | [e6c38e5b79](https://linux-hardware.org/?probe=e6c38e5b79) | Oct 10, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [2e312a734f](https://linux-hardware.org/?probe=2e312a734f) | Oct 08, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [8319b2b5c6](https://linux-hardware.org/?probe=8319b2b5c6) | Oct 08, 2021 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [bc9337f46e](https://linux-hardware.org/?probe=bc9337f46e) | Oct 07, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [95cd0c0751](https://linux-hardware.org/?probe=95cd0c0751) | Oct 07, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [a8ea4ccbef](https://linux-hardware.org/?probe=a8ea4ccbef) | Oct 06, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [233f451319](https://linux-hardware.org/?probe=233f451319) | Oct 06, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [02b5492901](https://linux-hardware.org/?probe=02b5492901) | Oct 06, 2021 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [634113d340](https://linux-hardware.org/?probe=634113d340) | Oct 06, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [666f9cb875](https://linux-hardware.org/?probe=666f9cb875) | Oct 06, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [3ad4e11bac](https://linux-hardware.org/?probe=3ad4e11bac) | Oct 06, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [18a2385458](https://linux-hardware.org/?probe=18a2385458) | Oct 06, 2021 |
| Samsung       | RC530/RC730                 | Notebook    | [931664ed89](https://linux-hardware.org/?probe=931664ed89) | Oct 04, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [67fc73c11e](https://linux-hardware.org/?probe=67fc73c11e) | Oct 04, 2021 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [9901023f19](https://linux-hardware.org/?probe=9901023f19) | Oct 03, 2021 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [e2057e68dd](https://linux-hardware.org/?probe=e2057e68dd) | Oct 03, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [e7742aa472](https://linux-hardware.org/?probe=e7742aa472) | Oct 03, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [5ce182d7ae](https://linux-hardware.org/?probe=5ce182d7ae) | Oct 01, 2021 |
| ASUSTek       | Unknown                     | Notebook    | [9b357ee9bb](https://linux-hardware.org/?probe=9b357ee9bb) | Oct 01, 2021 |
| Dell          | Inspiron 5415               | Notebook    | [a265f8ea5c](https://linux-hardware.org/?probe=a265f8ea5c) | Oct 01, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [4044b3b3b2](https://linux-hardware.org/?probe=4044b3b3b2) | Oct 01, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | Notebook    | [fbade9e61e](https://linux-hardware.org/?probe=fbade9e61e) | Oct 01, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [6b625a8736](https://linux-hardware.org/?probe=6b625a8736) | Oct 01, 2021 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [1fce457ac6](https://linux-hardware.org/?probe=1fce457ac6) | Oct 01, 2021 |
| ASUSTek       | X555LJ                      | Notebook    | [dea4201e98](https://linux-hardware.org/?probe=dea4201e98) | Oct 01, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [27707fb954](https://linux-hardware.org/?probe=27707fb954) | Oct 01, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [87f779767d](https://linux-hardware.org/?probe=87f779767d) | Oct 01, 2021 |
| Acer          | Aspire XC-780               | Desktop     | [f723ac396a](https://linux-hardware.org/?probe=f723ac396a) | Oct 01, 2021 |
| HP            | 255 G6 Notebook PC          | Notebook    | [9823c616ed](https://linux-hardware.org/?probe=9823c616ed) | Sep 30, 2021 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [a30ab1431c](https://linux-hardware.org/?probe=a30ab1431c) | Sep 30, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [f7cc61788a](https://linux-hardware.org/?probe=f7cc61788a) | Sep 30, 2021 |
| HP            | ProBook 430 G5              | Notebook    | [6ee2943500](https://linux-hardware.org/?probe=6ee2943500) | Sep 30, 2021 |
| Dell          | Inspiron 5577               | Notebook    | [f5ec85dd12](https://linux-hardware.org/?probe=f5ec85dd12) | Sep 29, 2021 |
| Dell          | Inspiron 5577               | Notebook    | [80e36f9785](https://linux-hardware.org/?probe=80e36f9785) | Sep 29, 2021 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [de13c8f3fa](https://linux-hardware.org/?probe=de13c8f3fa) | Sep 29, 2021 |
| TYAN Compu... | S7025                       | Server      | [6b7a9d9bdb](https://linux-hardware.org/?probe=6b7a9d9bdb) | Sep 29, 2021 |
| ASRock        | H170 Pro4                   | Desktop     | [a0d0f5002e](https://linux-hardware.org/?probe=a0d0f5002e) | Sep 29, 2021 |
| ASRock        | H170 Pro4                   | Desktop     | [5a3652f38b](https://linux-hardware.org/?probe=5a3652f38b) | Sep 29, 2021 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [c3bb6d3afa](https://linux-hardware.org/?probe=c3bb6d3afa) | Sep 29, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [88104169a4](https://linux-hardware.org/?probe=88104169a4) | Sep 28, 2021 |
| Lenovo        | ThinkPad X240 20AMS1LN00    | Notebook    | [71d301cc84](https://linux-hardware.org/?probe=71d301cc84) | Sep 26, 2021 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [241866fa37](https://linux-hardware.org/?probe=241866fa37) | Sep 26, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [116e97036b](https://linux-hardware.org/?probe=116e97036b) | Sep 25, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [8b939aae88](https://linux-hardware.org/?probe=8b939aae88) | Sep 25, 2021 |
| ASUSTek       | GX501VIK                    | Notebook    | [b36bf17cc2](https://linux-hardware.org/?probe=b36bf17cc2) | Sep 24, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 O... | Notebook    | [f40c18c3b8](https://linux-hardware.org/?probe=f40c18c3b8) | Sep 23, 2021 |
| ASRock        | X370 Professional Gaming    | Desktop     | [546f692061](https://linux-hardware.org/?probe=546f692061) | Sep 23, 2021 |
| Samsung       | RC530/RC730                 | Notebook    | [4aa6a34c0c](https://linux-hardware.org/?probe=4aa6a34c0c) | Sep 23, 2021 |
| Intel         | DG31PR AAD97573-205         | Desktop     | [2c022c21f0](https://linux-hardware.org/?probe=2c022c21f0) | Sep 22, 2021 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [ec47ffaeac](https://linux-hardware.org/?probe=ec47ffaeac) | Sep 22, 2021 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y3C... | Notebook    | [4698844ec0](https://linux-hardware.org/?probe=4698844ec0) | Sep 20, 2021 |
| Lenovo        | B51-80 80LM                 | Notebook    | [320ab41cbb](https://linux-hardware.org/?probe=320ab41cbb) | Sep 17, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | Desktop     | [86d356f643](https://linux-hardware.org/?probe=86d356f643) | Sep 16, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [2f9b27ad89](https://linux-hardware.org/?probe=2f9b27ad89) | Sep 16, 2021 |
| Dell          | 0YJPT1 A00                  | Desktop     | [69d571e9f5](https://linux-hardware.org/?probe=69d571e9f5) | Sep 15, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [4c18c08616](https://linux-hardware.org/?probe=4c18c08616) | Sep 15, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [d406b31a3a](https://linux-hardware.org/?probe=d406b31a3a) | Sep 15, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [3d0115d011](https://linux-hardware.org/?probe=3d0115d011) | Sep 15, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [308d39b0dc](https://linux-hardware.org/?probe=308d39b0dc) | Sep 15, 2021 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [21e3d9bccb](https://linux-hardware.org/?probe=21e3d9bccb) | Sep 14, 2021 |
| Notebook      | P65xHP                      | Notebook    | [12a7ec2b86](https://linux-hardware.org/?probe=12a7ec2b86) | Sep 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [b1c5ad62b3](https://linux-hardware.org/?probe=b1c5ad62b3) | Sep 13, 2021 |
| Dell          | Latitude 5410               | Notebook    | [97ed647d4c](https://linux-hardware.org/?probe=97ed647d4c) | Sep 10, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [9dcddb807d](https://linux-hardware.org/?probe=9dcddb807d) | Sep 10, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [572c0c5198](https://linux-hardware.org/?probe=572c0c5198) | Sep 10, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [36bf3dd55d](https://linux-hardware.org/?probe=36bf3dd55d) | Sep 09, 2021 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [c18b4f0dab](https://linux-hardware.org/?probe=c18b4f0dab) | Sep 09, 2021 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [35ee76ca1b](https://linux-hardware.org/?probe=35ee76ca1b) | Sep 08, 2021 |
| ASUSTek       | ZenBook UX425IA_U4700IA     | Notebook    | [fa970f7a80](https://linux-hardware.org/?probe=fa970f7a80) | Sep 08, 2021 |
| HP            | Pavilion g6                 | Notebook    | [1161032a20](https://linux-hardware.org/?probe=1161032a20) | Sep 08, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [19555ed132](https://linux-hardware.org/?probe=19555ed132) | Sep 07, 2021 |
| Dell          | Precision 7560              | Notebook    | [03d7773132](https://linux-hardware.org/?probe=03d7773132) | Sep 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [a629879646](https://linux-hardware.org/?probe=a629879646) | Sep 06, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [78fc85808c](https://linux-hardware.org/?probe=78fc85808c) | Sep 05, 2021 |
| ASUSTek       | P5P41C                      | Desktop     | [e68f372c7b](https://linux-hardware.org/?probe=e68f372c7b) | Sep 05, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | Desktop     | [f63a2003ab](https://linux-hardware.org/?probe=f63a2003ab) | Sep 05, 2021 |
| ASUSTek       | X550ZA                      | Notebook    | [0d41969b6b](https://linux-hardware.org/?probe=0d41969b6b) | Sep 02, 2021 |
| Dell          | Latitude E6510              | Notebook    | [2ab208b5cd](https://linux-hardware.org/?probe=2ab208b5cd) | Sep 02, 2021 |
| HP            | 255 G6 Notebook PC          | Notebook    | [4f71a8ad02](https://linux-hardware.org/?probe=4f71a8ad02) | Sep 01, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [d6872bd9e9](https://linux-hardware.org/?probe=d6872bd9e9) | Sep 01, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [40d01ef03e](https://linux-hardware.org/?probe=40d01ef03e) | Aug 31, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | Notebook    | [f1b58d72ac](https://linux-hardware.org/?probe=f1b58d72ac) | Aug 31, 2021 |
| Packard Be... | FMCP7AM                     | Desktop     | [6872ae9fb4](https://linux-hardware.org/?probe=6872ae9fb4) | Aug 31, 2021 |
| Gigabyte      | EP43-DS3                    | Desktop     | [0eaf518e06](https://linux-hardware.org/?probe=0eaf518e06) | Aug 29, 2021 |
| Dell          | 0U1325                      | Desktop     | [0a58fab188](https://linux-hardware.org/?probe=0a58fab188) | Aug 28, 2021 |
| IBM           | ThinkPad T42 2373V4F        | Notebook    | [2362291c05](https://linux-hardware.org/?probe=2362291c05) | Aug 28, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [00b0f43680](https://linux-hardware.org/?probe=00b0f43680) | Aug 28, 2021 |
| IBM           | ThinkPad T43 2668Z3S        | Notebook    | [5a606b504c](https://linux-hardware.org/?probe=5a606b504c) | Aug 28, 2021 |
| Packard Be... | FMCP7AM                     | Desktop     | [07fb4f5678](https://linux-hardware.org/?probe=07fb4f5678) | Aug 28, 2021 |
| MSI           | MS-7369                     | Desktop     | [0c6668dee5](https://linux-hardware.org/?probe=0c6668dee5) | Aug 28, 2021 |
| IBM           | ThinkPad T43 2668Z3S        | Notebook    | [2af8736235](https://linux-hardware.org/?probe=2af8736235) | Aug 28, 2021 |
| Dell          | 0U1325                      | Desktop     | [1b5dfb4b59](https://linux-hardware.org/?probe=1b5dfb4b59) | Aug 28, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [aabbe0dbcc](https://linux-hardware.org/?probe=aabbe0dbcc) | Aug 26, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | Notebook    | [cf76a62cf4](https://linux-hardware.org/?probe=cf76a62cf4) | Aug 26, 2021 |
| HP            | 255 G6 Notebook PC          | Notebook    | [b776f7f3b7](https://linux-hardware.org/?probe=b776f7f3b7) | Aug 26, 2021 |
| ASUSTek       | P9X79 WS                    | Desktop     | [0569365ea0](https://linux-hardware.org/?probe=0569365ea0) | Aug 26, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | Notebook    | [62ba09ac38](https://linux-hardware.org/?probe=62ba09ac38) | Aug 26, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | Notebook    | [994e94defa](https://linux-hardware.org/?probe=994e94defa) | Aug 26, 2021 |
| Lenovo        | ThinkPad X230 23259H1       | Notebook    | [fb125d2779](https://linux-hardware.org/?probe=fb125d2779) | Aug 25, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [f521a0c69c](https://linux-hardware.org/?probe=f521a0c69c) | Aug 25, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [c09944da60](https://linux-hardware.org/?probe=c09944da60) | Aug 24, 2021 |
| Supermicro    | X10SAE                      | Server      | [019914cc29](https://linux-hardware.org/?probe=019914cc29) | Aug 24, 2021 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [c6aaf9451f](https://linux-hardware.org/?probe=c6aaf9451f) | Aug 22, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [ae02b6e88b](https://linux-hardware.org/?probe=ae02b6e88b) | Aug 19, 2021 |
| ASUSTek       | P5P41C                      | Desktop     | [0eb4111089](https://linux-hardware.org/?probe=0eb4111089) | Aug 18, 2021 |
| NZXT          | N7 Z370                     | Desktop     | [4eb4c77752](https://linux-hardware.org/?probe=4eb4c77752) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5ffe57957d](https://linux-hardware.org/?probe=5ffe57957d) | Aug 18, 2021 |
| NZXT          | N7 Z370                     | Desktop     | [40f0739800](https://linux-hardware.org/?probe=40f0739800) | Aug 17, 2021 |
| Dell          | Inspiron 5415               | Notebook    | [909e2cdc93](https://linux-hardware.org/?probe=909e2cdc93) | Aug 15, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | Desktop     | [211803a510](https://linux-hardware.org/?probe=211803a510) | Aug 15, 2021 |
| MSI           | B550-A PRO                  | Desktop     | [b3ff3985c5](https://linux-hardware.org/?probe=b3ff3985c5) | Aug 13, 2021 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [843279faa7](https://linux-hardware.org/?probe=843279faa7) | Aug 13, 2021 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [28ecd70483](https://linux-hardware.org/?probe=28ecd70483) | Aug 12, 2021 |
| HP            | 158B                        | Desktop     | [d47aa82b20](https://linux-hardware.org/?probe=d47aa82b20) | Aug 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [711599ea49](https://linux-hardware.org/?probe=711599ea49) | Aug 11, 2021 |
| Intel         | D525MW AAE93082-301         | Desktop     | [fc72f0a0ea](https://linux-hardware.org/?probe=fc72f0a0ea) | Aug 11, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [21b619d91b](https://linux-hardware.org/?probe=21b619d91b) | Aug 11, 2021 |
| Dell          | Inspiron 5415               | Notebook    | [63594290cf](https://linux-hardware.org/?probe=63594290cf) | Aug 11, 2021 |
| TUXEDO        | Book XC1711                 | Notebook    | [806e284c8a](https://linux-hardware.org/?probe=806e284c8a) | Aug 11, 2021 |
| Jumper        | EZpad                       | Notebook    | [da2436c208](https://linux-hardware.org/?probe=da2436c208) | Aug 11, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [d74d9e37ce](https://linux-hardware.org/?probe=d74d9e37ce) | Aug 10, 2021 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [aaef52aca2](https://linux-hardware.org/?probe=aaef52aca2) | Aug 10, 2021 |
| Jumper        | EZpad                       | Notebook    | [6215ba7396](https://linux-hardware.org/?probe=6215ba7396) | Aug 10, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | Desktop     | [33fffaf1c3](https://linux-hardware.org/?probe=33fffaf1c3) | Aug 07, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [ddf6a2277a](https://linux-hardware.org/?probe=ddf6a2277a) | Aug 07, 2021 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [0fac51313a](https://linux-hardware.org/?probe=0fac51313a) | Aug 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [30131c51fb](https://linux-hardware.org/?probe=30131c51fb) | Aug 05, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ef7a0635f4](https://linux-hardware.org/?probe=ef7a0635f4) | Aug 04, 2021 |
| ASUSTek       | X510UR                      | Notebook    | [8e08727583](https://linux-hardware.org/?probe=8e08727583) | Aug 03, 2021 |
| TUXEDO        | Book_XA1510                 | Notebook    | [f4f777ed12](https://linux-hardware.org/?probe=f4f777ed12) | Aug 03, 2021 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [51a1b8132e](https://linux-hardware.org/?probe=51a1b8132e) | Aug 01, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [754750effc](https://linux-hardware.org/?probe=754750effc) | Jul 31, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0f19cc3c0e](https://linux-hardware.org/?probe=0f19cc3c0e) | Jul 31, 2021 |
| Dell          | 09WH54 A00                  | Desktop     | [9885d45d4f](https://linux-hardware.org/?probe=9885d45d4f) | Jul 28, 2021 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [380758e335](https://linux-hardware.org/?probe=380758e335) | Jul 28, 2021 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [a5a11a0de1](https://linux-hardware.org/?probe=a5a11a0de1) | Jul 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [46b71409d7](https://linux-hardware.org/?probe=46b71409d7) | Jul 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c824226d1e](https://linux-hardware.org/?probe=c824226d1e) | Jul 26, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [f22f34ea9a](https://linux-hardware.org/?probe=f22f34ea9a) | Jul 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [3de3129139](https://linux-hardware.org/?probe=3de3129139) | Jul 22, 2021 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [5a32ec902e](https://linux-hardware.org/?probe=5a32ec902e) | Jul 22, 2021 |
| Gigabyte      | H110-D3-CF                  | Desktop     | [7d25217f50](https://linux-hardware.org/?probe=7d25217f50) | Jul 22, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [c6a7c7d9d8](https://linux-hardware.org/?probe=c6a7c7d9d8) | Jul 19, 2021 |
| Gigabyte      | B460 HD3                    | Desktop     | [a43624a24b](https://linux-hardware.org/?probe=a43624a24b) | Jul 18, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [236639a923](https://linux-hardware.org/?probe=236639a923) | Jul 16, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | Notebook    | [4b6bb5e980](https://linux-hardware.org/?probe=4b6bb5e980) | Jul 16, 2021 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | Notebook    | [483690e890](https://linux-hardware.org/?probe=483690e890) | Jul 14, 2021 |
| Dell          | Latitude E6430              | Notebook    | [3dc281ca01](https://linux-hardware.org/?probe=3dc281ca01) | Jul 13, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [9356542b15](https://linux-hardware.org/?probe=9356542b15) | Jul 12, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [6835266a32](https://linux-hardware.org/?probe=6835266a32) | Jul 10, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [4d378eb681](https://linux-hardware.org/?probe=4d378eb681) | Jul 10, 2021 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [517a612c58](https://linux-hardware.org/?probe=517a612c58) | Jul 10, 2021 |
| Dell          | Latitude E6430              | Notebook    | [f5a73f4d90](https://linux-hardware.org/?probe=f5a73f4d90) | Jul 09, 2021 |
| Dell          | Latitude E6430              | Notebook    | [8d685287ce](https://linux-hardware.org/?probe=8d685287ce) | Jul 09, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [68c41ed42b](https://linux-hardware.org/?probe=68c41ed42b) | Jul 08, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [5a6fca486a](https://linux-hardware.org/?probe=5a6fca486a) | Jul 08, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [ab93056d13](https://linux-hardware.org/?probe=ab93056d13) | Jul 08, 2021 |
| Acer          | Aspire A315-32              | Notebook    | [3a9edbefac](https://linux-hardware.org/?probe=3a9edbefac) | Jul 06, 2021 |
| Acer          | Aspire A315-32              | Notebook    | [09f71bed72](https://linux-hardware.org/?probe=09f71bed72) | Jul 06, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [50d75ad77d](https://linux-hardware.org/?probe=50d75ad77d) | Jul 03, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [4ef1e3ccac](https://linux-hardware.org/?probe=4ef1e3ccac) | Jul 03, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [4e618f85f9](https://linux-hardware.org/?probe=4e618f85f9) | Jul 03, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a2acbde7fd](https://linux-hardware.org/?probe=a2acbde7fd) | Jul 02, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [cbb60edb8c](https://linux-hardware.org/?probe=cbb60edb8c) | Jul 02, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [26a655c4b4](https://linux-hardware.org/?probe=26a655c4b4) | Jul 02, 2021 |
| Intel         | DZ77BH-55K AAG39008-400     | Desktop     | [04692a4293](https://linux-hardware.org/?probe=04692a4293) | Jul 02, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [ac2a4b3aea](https://linux-hardware.org/?probe=ac2a4b3aea) | Jul 01, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b8cc7c380d](https://linux-hardware.org/?probe=b8cc7c380d) | Jun 28, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2831e5a8cf](https://linux-hardware.org/?probe=2831e5a8cf) | Jun 28, 2021 |
| HP            | Pro Tablet 608 G1           | Notebook    | [c1a115b721](https://linux-hardware.org/?probe=c1a115b721) | Jun 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d442a66371](https://linux-hardware.org/?probe=d442a66371) | Jun 27, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [5d9bde452b](https://linux-hardware.org/?probe=5d9bde452b) | Jun 27, 2021 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [69f9da2ac3](https://linux-hardware.org/?probe=69f9da2ac3) | Jun 26, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [c9180096a8](https://linux-hardware.org/?probe=c9180096a8) | Jun 26, 2021 |
| Apple         | MacBookPro8,3               | Notebook    | [1453a09197](https://linux-hardware.org/?probe=1453a09197) | Jun 25, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [84bf6743c1](https://linux-hardware.org/?probe=84bf6743c1) | Jun 25, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [ced7e0d00d](https://linux-hardware.org/?probe=ced7e0d00d) | Jun 25, 2021 |
| Apple         | MacBookPro8,3               | Notebook    | [94f589e95c](https://linux-hardware.org/?probe=94f589e95c) | Jun 25, 2021 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [4add1f32e4](https://linux-hardware.org/?probe=4add1f32e4) | Jun 23, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | Notebook    | [e1fe98a9de](https://linux-hardware.org/?probe=e1fe98a9de) | Jun 23, 2021 |
| Unknown       | Unknown                     | Desktop     | [bb64d32fdf](https://linux-hardware.org/?probe=bb64d32fdf) | Jun 21, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [8ac09d11a4](https://linux-hardware.org/?probe=8ac09d11a4) | Jun 20, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [70c10f988f](https://linux-hardware.org/?probe=70c10f988f) | Jun 20, 2021 |
| Dell          | Latitude E7440              | Notebook    | [9302b47a78](https://linux-hardware.org/?probe=9302b47a78) | Jun 19, 2021 |
| MSI           | GS66 Stealth 10SFS          | Notebook    | [7535868db2](https://linux-hardware.org/?probe=7535868db2) | Jun 18, 2021 |
| MSI           | GS66 Stealth 10SFS          | Notebook    | [c095a4437c](https://linux-hardware.org/?probe=c095a4437c) | Jun 17, 2021 |
| ASUSTek       | PRIME TRX40-PRO             | Desktop     | [f0c7a3a628](https://linux-hardware.org/?probe=f0c7a3a628) | Jun 15, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [8d612e77f2](https://linux-hardware.org/?probe=8d612e77f2) | Jun 14, 2021 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [9a91c78c7a](https://linux-hardware.org/?probe=9a91c78c7a) | Jun 14, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | Notebook    | [8d5844241c](https://linux-hardware.org/?probe=8d5844241c) | Jun 13, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [3013608130](https://linux-hardware.org/?probe=3013608130) | Jun 12, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [704bf0bba3](https://linux-hardware.org/?probe=704bf0bba3) | Jun 12, 2021 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [9b07d82840](https://linux-hardware.org/?probe=9b07d82840) | Jun 12, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [efab65cf1d](https://linux-hardware.org/?probe=efab65cf1d) | Jun 12, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [293537d794](https://linux-hardware.org/?probe=293537d794) | Jun 11, 2021 |
| Lenovo        | ThinkPad X390 20Q0000KRT    | Notebook    | [f1d0d2bda6](https://linux-hardware.org/?probe=f1d0d2bda6) | Jun 09, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [ab9da369c0](https://linux-hardware.org/?probe=ab9da369c0) | Jun 09, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [407abb051f](https://linux-hardware.org/?probe=407abb051f) | Jun 09, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [5e6aba1341](https://linux-hardware.org/?probe=5e6aba1341) | Jun 09, 2021 |
| Dell          | Inspiron 7375               | Notebook    | [7704e5289b](https://linux-hardware.org/?probe=7704e5289b) | Jun 07, 2021 |
| ZOTAC         | ZBOX EN970                  | Mini pc     | [493278d567](https://linux-hardware.org/?probe=493278d567) | Jun 05, 2021 |
| Lenovo        | ThinkPad L450 20DTS01R00    | Notebook    | [f8e58be450](https://linux-hardware.org/?probe=f8e58be450) | Jun 03, 2021 |
| Lenovo        | ThinkPad X390 20Q0000KRT    | Notebook    | [b571e885e2](https://linux-hardware.org/?probe=b571e885e2) | Jun 03, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [f3f3c323ab](https://linux-hardware.org/?probe=f3f3c323ab) | Jun 03, 2021 |
| MSI           | Z97 PC Mate                 | Desktop     | [73ece6c322](https://linux-hardware.org/?probe=73ece6c322) | Jun 02, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [e85b21841c](https://linux-hardware.org/?probe=e85b21841c) | Jun 01, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [024ffa0922](https://linux-hardware.org/?probe=024ffa0922) | Jun 01, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [eed35a825a](https://linux-hardware.org/?probe=eed35a825a) | May 31, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [a04eb698f8](https://linux-hardware.org/?probe=a04eb698f8) | May 30, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [4f69bed2ff](https://linux-hardware.org/?probe=4f69bed2ff) | May 28, 2021 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | Desktop     | [2767965856](https://linux-hardware.org/?probe=2767965856) | May 27, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [052b95ba1d](https://linux-hardware.org/?probe=052b95ba1d) | May 27, 2021 |
| Dell          | Inspiron 5415               | Notebook    | [bbf1e95976](https://linux-hardware.org/?probe=bbf1e95976) | May 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [83d261308f](https://linux-hardware.org/?probe=83d261308f) | May 26, 2021 |
| Dell          | Inspiron 5415               | Notebook    | [abc4464787](https://linux-hardware.org/?probe=abc4464787) | May 26, 2021 |
| Dell          | Inspiron 5415               | Notebook    | [27c5c40e12](https://linux-hardware.org/?probe=27c5c40e12) | May 26, 2021 |
| Lenovo        | ThinkPad X230 2325BF1       | Notebook    | [0d334af224](https://linux-hardware.org/?probe=0d334af224) | May 26, 2021 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | Desktop     | [843f1d9b38](https://linux-hardware.org/?probe=843f1d9b38) | May 25, 2021 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | Desktop     | [5794d366c2](https://linux-hardware.org/?probe=5794d366c2) | May 25, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e1cf7f4599](https://linux-hardware.org/?probe=e1cf7f4599) | May 24, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [49458a2df1](https://linux-hardware.org/?probe=49458a2df1) | May 24, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [73ff247804](https://linux-hardware.org/?probe=73ff247804) | May 24, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [61a5d17b5b](https://linux-hardware.org/?probe=61a5d17b5b) | May 22, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [b74e96d4be](https://linux-hardware.org/?probe=b74e96d4be) | May 22, 2021 |
| Unknown       | Cubietech Cubieboard2       | Desktop     | [d777d4b535](https://linux-hardware.org/?probe=d777d4b535) | May 22, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [455915e23a](https://linux-hardware.org/?probe=455915e23a) | May 21, 2021 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | Desktop     | [95fb77ceae](https://linux-hardware.org/?probe=95fb77ceae) | May 21, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [1c2f94847e](https://linux-hardware.org/?probe=1c2f94847e) | May 20, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [5104abb7a7](https://linux-hardware.org/?probe=5104abb7a7) | May 20, 2021 |
| ASUSTek       | X550ZA                      | Notebook    | [aef8ea73d8](https://linux-hardware.org/?probe=aef8ea73d8) | May 20, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [72904aba23](https://linux-hardware.org/?probe=72904aba23) | May 20, 2021 |
| HP            | 8643 SMVB                   | Desktop     | [b183baddef](https://linux-hardware.org/?probe=b183baddef) | May 19, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [4f3165b957](https://linux-hardware.org/?probe=4f3165b957) | May 19, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [2679a5931a](https://linux-hardware.org/?probe=2679a5931a) | May 19, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [089c319771](https://linux-hardware.org/?probe=089c319771) | May 18, 2021 |
| Lenovo        | ThinkPad T61p 8891CTO       | Notebook    | [8a05529e0c](https://linux-hardware.org/?probe=8a05529e0c) | May 18, 2021 |
| Lenovo        | ThinkPad T61p 8891CTO       | Notebook    | [6daf66a738](https://linux-hardware.org/?probe=6daf66a738) | May 18, 2021 |
| Raspberry ... | Raspberry Pi Model B Rev... | Soc         | [7a83ffc7d8](https://linux-hardware.org/?probe=7a83ffc7d8) | May 18, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [7ae6a0f74b](https://linux-hardware.org/?probe=7ae6a0f74b) | May 18, 2021 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [2b97441fb1](https://linux-hardware.org/?probe=2b97441fb1) | May 17, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [8110fad44d](https://linux-hardware.org/?probe=8110fad44d) | May 17, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [9a767f85c2](https://linux-hardware.org/?probe=9a767f85c2) | May 17, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [50b75a0212](https://linux-hardware.org/?probe=50b75a0212) | May 17, 2021 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [d75aff5a0a](https://linux-hardware.org/?probe=d75aff5a0a) | May 16, 2021 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [f9420a7960](https://linux-hardware.org/?probe=f9420a7960) | May 16, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [b2cc4333b0](https://linux-hardware.org/?probe=b2cc4333b0) | May 16, 2021 |
| Samsung       | RC530/RC730                 | Notebook    | [1da22350d7](https://linux-hardware.org/?probe=1da22350d7) | May 15, 2021 |
| HP            | Unknown                     | Notebook    | [554d7cd528](https://linux-hardware.org/?probe=554d7cd528) | May 14, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [065d69be16](https://linux-hardware.org/?probe=065d69be16) | May 13, 2021 |
| ZOTAC         | ZBOX EN970                  | Mini pc     | [d125abf69e](https://linux-hardware.org/?probe=d125abf69e) | May 12, 2021 |
| Dell          | Inspiron 3135               | Notebook    | [2773a72a9b](https://linux-hardware.org/?probe=2773a72a9b) | May 10, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [6c504fbdf0](https://linux-hardware.org/?probe=6c504fbdf0) | May 10, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [46242d579f](https://linux-hardware.org/?probe=46242d579f) | May 09, 2021 |
| HP            | Pavilion ZV6100 (EE984EA... | Notebook    | [5b8198d382](https://linux-hardware.org/?probe=5b8198d382) | May 08, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [0b6b9eab78](https://linux-hardware.org/?probe=0b6b9eab78) | May 07, 2021 |
| Dell          | Inspiron 3135               | Notebook    | [9bcfced245](https://linux-hardware.org/?probe=9bcfced245) | May 07, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [c3e8ad6826](https://linux-hardware.org/?probe=c3e8ad6826) | May 07, 2021 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [0b4a5c33ef](https://linux-hardware.org/?probe=0b4a5c33ef) | May 06, 2021 |
| Dell          | G3 3500                     | Notebook    | [f6624959c4](https://linux-hardware.org/?probe=f6624959c4) | May 05, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [70bb3aecd9](https://linux-hardware.org/?probe=70bb3aecd9) | May 05, 2021 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e305a7301f](https://linux-hardware.org/?probe=e305a7301f) | May 05, 2021 |
| ASUSTek       | P5LD2-Deluxe                | Desktop     | [193ecc62cf](https://linux-hardware.org/?probe=193ecc62cf) | May 03, 2021 |
| QDI           | P4I865A                     | Desktop     | [a3df896b35](https://linux-hardware.org/?probe=a3df896b35) | May 03, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1d95f1feca](https://linux-hardware.org/?probe=1d95f1feca) | May 02, 2021 |
| Toshiba       | NB100                       | Notebook    | [9540e0d0d5](https://linux-hardware.org/?probe=9540e0d0d5) | May 02, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [ae4420d3a9](https://linux-hardware.org/?probe=ae4420d3a9) | May 01, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [aa72a49a15](https://linux-hardware.org/?probe=aa72a49a15) | Apr 30, 2021 |
| Lenovo        | ThinkPad P50 20EN0006UK     | Notebook    | [6f9d0f45bb](https://linux-hardware.org/?probe=6f9d0f45bb) | Apr 30, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [aff27ae264](https://linux-hardware.org/?probe=aff27ae264) | Apr 29, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [fe32c3d470](https://linux-hardware.org/?probe=fe32c3d470) | Apr 29, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [ff1723016b](https://linux-hardware.org/?probe=ff1723016b) | Apr 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [0bbb4df743](https://linux-hardware.org/?probe=0bbb4df743) | Apr 27, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [02dae8d8ba](https://linux-hardware.org/?probe=02dae8d8ba) | Apr 24, 2021 |
| Unknown       | Freecom Silverstore HNCN... | Desktop     | [c54d9f2c0c](https://linux-hardware.org/?probe=c54d9f2c0c) | Apr 23, 2021 |
| Unknown       | Unknown                     | Desktop     | [160f692db0](https://linux-hardware.org/?probe=160f692db0) | Apr 23, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Gentoo/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Gentoo 2.7     | 555       | 44.29%  |
| Gentoo 2.6     | 412       | 32.88%  |
| Gentoo 2.8     | 238       | 18.99%  |
| Gentoo 2.4.1   | 14        | 1.12%   |
| Gentoo         | 10        | 0.8%    |
| Gentoo 2.3     | 9         | 0.72%   |
| Gentoo 2.2     | 7         | 0.56%   |
| Gentoo 1       | 3         | 0.24%   |
| Gentoo Pelikan | 1         | 0.08%   |
| Gentoo 22      | 1         | 0.08%   |
| Gentoo 2.9     | 1         | 0.08%   |
| Gentoo 2.1     | 1         | 0.08%   |
| Gentoo 13.0    | 1         | 0.08%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Gentoo | 1139      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.38-gentoo            | 26        | 1.76%   |
| 5.10.27-gentoo           | 25        | 1.69%   |
| 5.10.61-gentoo           | 23        | 1.56%   |
| 5.15.32-gentoo-r1        | 18        | 1.22%   |
| 5.4.80-gentoo-r1         | 15        | 1.01%   |
| 5.4.48-gentoo            | 15        | 1.01%   |
| 5.4.97-gentoo            | 14        | 0.95%   |
| 5.4.28-gentoo            | 14        | 0.95%   |
| 5.10.76-gentoo-r1        | 13        | 0.88%   |
| 5.10.27-gentoo-x86_64    | 13        | 0.88%   |
| 5.15.32-gentoo-r1-x86_64 | 12        | 0.81%   |
| 5.10.61-gentoo-x86_64    | 12        | 0.81%   |
| 5.10.52-gentoo           | 12        | 0.81%   |
| 5.7.0-gentoo             | 11        | 0.74%   |
| 5.4.60-gentoo            | 11        | 0.74%   |
| 5.4.38-gentoo-x86_64     | 10        | 0.68%   |
| 5.15.59-gentoo-x86_64    | 10        | 0.68%   |
| 5.15.59-gentoo           | 9         | 0.61%   |
| 5.15.52-gentoo           | 9         | 0.61%   |
| 5.10.76-gentoo-r1-x86_64 | 9         | 0.61%   |
| 5.6.15-gentoo            | 8         | 0.54%   |
| 5.4.66-gentoo            | 8         | 0.54%   |
| 5.4.48-gentoo-x86_64     | 8         | 0.54%   |
| 5.15.52-gentoo-x86_64    | 8         | 0.54%   |
| 5.15.41-gentoo-x86_64    | 8         | 0.54%   |
| 4.19.86-gentoo           | 8         | 0.54%   |
| 5.4.97-gentoo-x86_64     | 7         | 0.47%   |
| 5.4.66-gentoo-x86_64     | 7         | 0.47%   |
| 5.17.1-gentoo-r1         | 7         | 0.47%   |
| 5.15.41-gentoo           | 7         | 0.47%   |
| 5.15.11-gentoo-x86_64    | 7         | 0.47%   |
| 4.19.97-gentoo           | 7         | 0.47%   |
| 4.14.65-gentoo           | 7         | 0.47%   |
| 5.8.0-gentoo-r1          | 6         | 0.41%   |
| 5.15.26-gentoo           | 6         | 0.41%   |
| 5.15.23-gentoo           | 6         | 0.41%   |
| 5.9.8-gentoo             | 5         | 0.34%   |
| 5.6.11-gentoo            | 5         | 0.34%   |
| 5.4.72-gentoo            | 5         | 0.34%   |
| 5.19.0-gentoo-x86_64     | 5         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.27 | 46        | 3.12%   |
| 5.4.38  | 45        | 3.05%   |
| 5.15.32 | 40        | 2.71%   |
| 5.10.61 | 38        | 2.57%   |
| 5.4.48  | 33        | 2.24%   |
| 5.10.76 | 31        | 2.1%    |
| 5.4.97  | 25        | 1.69%   |
| 5.4.28  | 25        | 1.69%   |
| 5.15.52 | 23        | 1.56%   |
| 5.10.52 | 23        | 1.56%   |
| 5.4.80  | 22        | 1.49%   |
| 5.15.59 | 22        | 1.49%   |
| 5.15.41 | 20        | 1.36%   |
| 5.15.11 | 19        | 1.29%   |
| 5.4.66  | 17        | 1.15%   |
| 5.6.15  | 16        | 1.08%   |
| 5.4.60  | 16        | 1.08%   |
| 5.7.0   | 15        | 1.02%   |
| 5.17.1  | 15        | 1.02%   |
| 5.15.23 | 14        | 0.95%   |
| 5.4.72  | 13        | 0.88%   |
| 4.19.97 | 13        | 0.88%   |
| 5.9.11  | 12        | 0.81%   |
| 5.19.0  | 12        | 0.81%   |
| 5.15.26 | 12        | 0.81%   |
| 5.15.10 | 12        | 0.81%   |
| 5.9.8   | 10        | 0.68%   |
| 5.8.0   | 10        | 0.68%   |
| 4.19.86 | 10        | 0.68%   |
| 5.16.0  | 9         | 0.61%   |
| 5.9.0   | 8         | 0.54%   |
| 5.6.11  | 8         | 0.54%   |
| 5.15.16 | 8         | 0.54%   |
| 5.14.14 | 8         | 0.54%   |
| 5.13.12 | 8         | 0.54%   |
| 5.11.6  | 8         | 0.54%   |
| 5.11.0  | 8         | 0.54%   |
| 5.10.4  | 8         | 0.54%   |
| 4.19.57 | 8         | 0.54%   |
| 5.9.1   | 7         | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 230       | 16.68%  |
| 5.10    | 220       | 15.95%  |
| 5.15    | 210       | 15.23%  |
| 4.19    | 66        | 4.79%   |
| 5.6     | 64        | 4.64%   |
| 5.9     | 58        | 4.21%   |
| 5.8     | 54        | 3.92%   |
| 5.7     | 49        | 3.55%   |
| 5.14    | 48        | 3.48%   |
| 5.17    | 47        | 3.41%   |
| 5.16    | 47        | 3.41%   |
| 5.11    | 41        | 2.97%   |
| 5.18    | 40        | 2.9%    |
| 5.13    | 36        | 2.61%   |
| 5.12    | 30        | 2.18%   |
| 5.19    | 26        | 1.89%   |
| 5.5     | 17        | 1.23%   |
| 4.14    | 17        | 1.23%   |
| 5.2     | 12        | 0.87%   |
| 5.1     | 10        | 0.73%   |
| 5.3     | 9         | 0.65%   |
| 5.0     | 9         | 0.65%   |
| 4.9     | 8         | 0.58%   |
| 4.4     | 8         | 0.58%   |
| 4.18    | 7         | 0.51%   |
| 4.6     | 3         | 0.22%   |
| 4.12    | 3         | 0.22%   |
| 4.20    | 2         | 0.15%   |
| 4.10    | 2         | 0.15%   |
| 6.0     | 1         | 0.07%   |
| 4.5     | 1         | 0.07%   |
| 4.16    | 1         | 0.07%   |
| 4.13    | 1         | 0.07%   |
| 4.1     | 1         | 0.07%   |
| 3.18    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| x86_64   | 1088      | 95.52%  |
| i686     | 24        | 2.11%   |
| aarch64  | 10        | 0.88%   |
| ppc      | 7         | 0.61%   |
| armv7l   | 3         | 0.26%   |
| armv6l   | 3         | 0.26%   |
| armv5tel | 2         | 0.18%   |
| ppc64le  | 1         | 0.09%   |
| ppc64    | 1         | 0.09%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 566       | 46.39%  |
| KDE5           | 233       | 19.1%   |
| GNOME          | 151       | 12.38%  |
| XFCE           | 98        | 8.03%   |
| KDE            | 56        | 4.59%   |
| MATE           | 29        | 2.38%   |
| DWM            | 16        | 1.31%   |
| LXQt           | 11        | 0.9%    |
| sway           | 8         | 0.66%   |
| X-Cinnamon     | 7         | 0.57%   |
| Enlightenment  | 7         | 0.57%   |
| LXDE           | 6         | 0.49%   |
| XSession       | 5         | 0.41%   |
| i3             | 5         | 0.41%   |
| Cinnamon       | 5         | 0.41%   |
| openbox        | 4         | 0.33%   |
| awesome        | 3         | 0.25%   |
| GNOME Classic  | 2         | 0.16%   |
| xmonad         | 1         | 0.08%   |
| Unity          | 1         | 0.08%   |
| qt5ct          | 1         | 0.08%   |
| LeftWM         | 1         | 0.08%   |
| i3-with-shmlog | 1         | 0.08%   |
| fvwm           | 1         | 0.08%   |
| fluxbox        | 1         | 0.08%   |
| bspwm          | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 681       | 55.77%  |
| Unknown | 243       | 19.9%   |
| Tty     | 182       | 14.91%  |
| Wayland | 115       | 9.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 619       | 51.76%  |
| SDDM    | 281       | 23.49%  |
| LightDM | 124       | 10.37%  |
| GDM     | 105       | 8.78%   |
| XDM     | 24        | 2.01%   |
| SLiM    | 19        | 1.59%   |
| LXDM    | 15        | 1.25%   |
| GREETD  | 4         | 0.33%   |
| TDM     | 3         | 0.25%   |
| KDM     | 1         | 0.08%   |
| GDM3    | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 438       | 36.65%  |
| Unknown    | 199       | 16.65%  |
| C.UTF8     | 91        | 7.62%   |
| de_DE      | 84        | 7.03%   |
| en_GB      | 78        | 6.53%   |
| ru_RU      | 49        | 4.1%    |
| C          | 26        | 2.18%   |
| es_ES      | 22        | 1.84%   |
| fr_FR      | 20        | 1.67%   |
| en_CA      | 17        | 1.42%   |
| pl_PL      | 14        | 1.17%   |
| it_IT      | 12        | 1%      |
| en_AU      | 12        | 1%      |
| pt_BR      | 9         | 0.75%   |
| zh_CN      | 8         | 0.67%   |
| cs_CZ      | 7         | 0.59%   |
| sv_SE      | 6         | 0.5%    |
| POSIX      | 6         | 0.5%    |
| nl_NL      | 6         | 0.5%    |
| el_GR      | 6         | 0.5%    |
| ru_RU.UTF8 | 5         | 0.42%   |
| en_US.UTF8 | 5         | 0.42%   |
| nl_BE      | 4         | 0.33%   |
| ja_JP      | 4         | 0.33%   |
| fi_FI      | 4         | 0.33%   |
| de_CH      | 4         | 0.33%   |
| zh_TW      | 3         | 0.25%   |
| uk_UA      | 3         | 0.25%   |
| fr_CA      | 3         | 0.25%   |
| es_AR      | 3         | 0.25%   |
| en_ZA      | 3         | 0.25%   |
| en_IE      | 3         | 0.25%   |
| ca_ES      | 3         | 0.25%   |
| ru_UA      | 2         | 0.17%   |
| ro_RO      | 2         | 0.17%   |
| es_CL      | 2         | 0.17%   |
| en_NZ      | 2         | 0.17%   |
| en_MX      | 2         | 0.17%   |
| en_DK      | 2         | 0.17%   |
| de_DE.UTF8 | 2         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 814       | 69.99%  |
| BIOS | 349       | 30.01%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 705       | 60.57%  |
| Btrfs    | 243       | 20.88%  |
| Zfs      | 47        | 4.04%   |
| Xfs      | 47        | 4.04%   |
| Unknown  | 46        | 3.95%   |
| F2fs     | 43        | 3.69%   |
| XXXXXXX  | 10        | 0.86%   |
| Reiserfs | 10        | 0.86%   |
| Overlay  | 3         | 0.26%   |
| Ext3     | 3         | 0.26%   |
| XXX      | 2         | 0.17%   |
| Jfs      | 2         | 0.17%   |
| Xtrfs    | 1         | 0.09%   |
| Ext2     | 1         | 0.09%   |
| Bcachefs | 1         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 949       | 81.95%  |
| MBR     | 138       | 11.92%  |
| Unknown | 71        | 6.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 801       | 67.65%  |
| Yes       | 383       | 32.35%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 791       | 67.72%  |
| Yes       | 377       | 32.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 247       | 21.69%  |
| Lenovo                  | 174       | 15.28%  |
| Dell                    | 117       | 10.27%  |
| MSI                     | 99        | 8.69%   |
| Hewlett-Packard         | 99        | 8.69%   |
| ASRock                  | 76        | 6.67%   |
| Gigabyte Technology     | 72        | 6.32%   |
| Acer                    | 35        | 3.07%   |
| Intel                   | 26        | 2.28%   |
| Unknown                 | 21        | 1.84%   |
| Apple                   | 20        | 1.76%   |
| Supermicro              | 13        | 1.14%   |
| Raspberry Pi Foundation | 12        | 1.05%   |
| Timi                    | 10        | 0.88%   |
| Samsung Electronics     | 10        | 0.88%   |
| Fujitsu                 | 10        | 0.88%   |
| HUAWEI                  | 9         | 0.79%   |
| TUXEDO                  | 7         | 0.61%   |
| Toshiba                 | 7         | 0.61%   |
| ASRockRack              | 5         | 0.44%   |
| Razer                   | 4         | 0.35%   |
| TYAN Computer           | 3         | 0.26%   |
| Tekram Technology       | 3         | 0.26%   |
| System76                | 3         | 0.26%   |
| Medion                  | 3         | 0.26%   |
| IBM                     | 3         | 0.26%   |
| win element             | 2         | 0.18%   |
| Sony                    | 2         | 0.18%   |
| Purism                  | 2         | 0.18%   |
| Positivo                | 2         | 0.18%   |
| Pegatron                | 2         | 0.18%   |
| Notebook                | 2         | 0.18%   |
| Framework               | 2         | 0.18%   |
| Foxconn                 | 2         | 0.18%   |
| Chuwi                   | 2         | 0.18%   |
| BESSTAR Tech            | 2         | 0.18%   |
| ZOTAC                   | 1         | 0.09%   |
| YANYU                   | 1         | 0.09%   |
| XMG                     | 1         | 0.09%   |
| Wortmann AG             | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 28        | 2.46%   |
| ASUS All Series                         | 18        | 1.58%   |
| ASUS TUF Gaming X570-PLUS               | 7         | 0.61%   |
| ASUS PRIME X570-PRO                     | 7         | 0.61%   |
| ASUS PRIME X470-PRO                     | 7         | 0.61%   |
| Supermicro Super Server                 | 6         | 0.53%   |
| MSI MS-7C02                             | 6         | 0.53%   |
| MSI MS-7C35                             | 5         | 0.44%   |
| Dell XPS 15 9570                        | 5         | 0.44%   |
| ASUS PRIME X370-PRO                     | 5         | 0.44%   |
| ASRock B450 Pro4                        | 5         | 0.44%   |
| MSI MS-7B89                             | 4         | 0.35%   |
| MSI MS-7B86                             | 4         | 0.35%   |
| MSI MS-7A38                             | 4         | 0.35%   |
| HP Pavilion Notebook                    | 4         | 0.35%   |
| HP OMEN by Laptop                       | 4         | 0.35%   |
| Dell XPS 17 9710                        | 4         | 0.35%   |
| Dell XPS 13 9310                        | 4         | 0.35%   |
| ASUS Z170 PRO GAMING                    | 4         | 0.35%   |
| ASUS TUF GAMING B550-PLUS               | 4         | 0.35%   |
| ASUS ROG STRIX X570-E GAMING            | 4         | 0.35%   |
| ASUS ROG STRIX B550-F GAMING            | 4         | 0.35%   |
| ASUS ROG STRIX B450-F GAMING            | 4         | 0.35%   |
| ASUS ROG CROSSHAIR VIII HERO            | 4         | 0.35%   |
| ASRock B550M Steel Legend               | 4         | 0.35%   |
| TYAN S7025                              | 3         | 0.26%   |
| Tekram P6B40-A4X-i440BX Rev             | 3         | 0.26%   |
| Supermicro X10SAE                       | 3         | 0.26%   |
| RPi Raspberry Pi Model B Rev 2          | 3         | 0.26%   |
| RPi Raspberry Pi 3 Model B Plus Rev 1.3 | 3         | 0.26%   |
| MSI MS-7C37                             | 3         | 0.26%   |
| MSI MS-7B79                             | 3         | 0.26%   |
| MSI MS-7A34                             | 3         | 0.26%   |
| MSI MS-7693                             | 3         | 0.26%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013GE    | 3         | 0.26%   |
| Lenovo Legion Y530-15ICH 81FV           | 3         | 0.26%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ        | 3         | 0.26%   |
| Intel S1200RP                           | 3         | 0.26%   |
| HP ProLiant MicroServer Gen8            | 3         | 0.26%   |
| HP Pavilion Gaming Laptop 15-ec1xxx     | 3         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 96        | 8.43%   |
| ASUS ROG          | 53        | 4.65%   |
| ASUS PRIME        | 41        | 3.6%    |
| Dell Latitude     | 37        | 3.25%   |
| Dell XPS          | 34        | 2.99%   |
| ASUS TUF          | 28        | 2.46%   |
| Unknown           | 28        | 2.46%   |
| Lenovo Legion     | 23        | 2.02%   |
| Acer Aspire       | 23        | 2.02%   |
| Lenovo IdeaPad    | 20        | 1.76%   |
| HP Pavilion       | 19        | 1.67%   |
| ASUS All          | 18        | 1.58%   |
| HP EliteBook      | 15        | 1.32%   |
| Dell Inspiron     | 14        | 1.23%   |
| RPi Raspberry     | 12        | 1.05%   |
| HP Laptop         | 12        | 1.05%   |
| Lenovo Yoga       | 11        | 0.97%   |
| HP OMEN           | 11        | 0.97%   |
| Dell Precision    | 11        | 0.97%   |
| ASRock X570       | 10        | 0.88%   |
| HP ProBook        | 9         | 0.79%   |
| Gigabyte X570     | 9         | 0.79%   |
| ASUS ZenBook      | 8         | 0.7%    |
| Gigabyte B450     | 7         | 0.61%   |
| Dell OptiPlex     | 7         | 0.61%   |
| ASRock X370       | 7         | 0.61%   |
| Supermicro Super  | 6         | 0.53%   |
| MSI MS-7C02       | 6         | 0.53%   |
| HP ProLiant       | 6         | 0.53%   |
| Gigabyte B450M    | 6         | 0.53%   |
| ASUS VivoBook     | 6         | 0.53%   |
| ASRock B450       | 6         | 0.53%   |
| Toshiba Satellite | 5         | 0.44%   |
| Timi RedmiBook    | 5         | 0.44%   |
| MSI MS-7C35       | 5         | 0.44%   |
| HP ZBook          | 5         | 0.44%   |
| HP ENVY           | 5         | 0.44%   |
| HP Compaq         | 5         | 0.44%   |
| Acer Swift        | 5         | 0.44%   |
| Acer Nitro        | 5         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 189       | 16.59%  |
| 2020    | 166       | 14.57%  |
| 2018    | 156       | 13.7%   |
| 2021    | 102       | 8.96%   |
| 2017    | 75        | 6.58%   |
| 2015    | 61        | 5.36%   |
| 2012    | 58        | 5.09%   |
| 2016    | 55        | 4.83%   |
| 2014    | 50        | 4.39%   |
| 2013    | 46        | 4.04%   |
| 2011    | 38        | 3.34%   |
| 2010    | 28        | 2.46%   |
| 2008    | 26        | 2.28%   |
| 2009    | 25        | 2.19%   |
| Unknown | 25        | 2.19%   |
| 2022    | 11        | 0.97%   |
| 2007    | 10        | 0.88%   |
| 2006    | 6         | 0.53%   |
| 2005    | 5         | 0.44%   |
| 2000    | 3         | 0.26%   |
| 2004    | 2         | 0.18%   |
| 2003    | 2         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 529       | 46.44%  |
| Desktop        | 521       | 45.74%  |
| Server         | 31        | 2.72%   |
| Convertible    | 25        | 2.19%   |
| Mini pc        | 14        | 1.23%   |
| System on chip | 13        | 1.14%   |
| All in one     | 3         | 0.26%   |
| Phone          | 1         | 0.09%   |
| Stick pc       | 1         | 0.09%   |
| Tablet         | 1         | 0.09%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1120      | 97.9%   |
| Enabled  | 24        | 2.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1133      | 99.47%  |
| Yes  | 6         | 0.53%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 288       | 24.68%  |
| 32.01-64.0      | 278       | 23.82%  |
| 8.01-16.0       | 181       | 15.51%  |
| 4.01-8.0        | 146       | 12.51%  |
| 64.01-256.0     | 112       | 9.6%    |
| 3.01-4.0        | 63        | 5.4%    |
| 24.01-32.0      | 37        | 3.17%   |
| 1.01-2.0        | 24        | 2.06%   |
| 0.51-1.0        | 18        | 1.54%   |
| 2.01-3.0        | 13        | 1.11%   |
| 0.01-0.5        | 6         | 0.51%   |
| More than 256.0 | 1         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 283       | 21.03%  |
| 4.01-8.0    | 259       | 19.24%  |
| 2.01-3.0    | 224       | 16.64%  |
| 3.01-4.0    | 146       | 10.85%  |
| 0.01-0.5    | 133       | 9.88%   |
| 8.01-16.0   | 132       | 9.81%   |
| 0.51-1.0    | 111       | 8.25%   |
| 16.01-24.0  | 35        | 2.6%    |
| 32.01-64.0  | 11        | 0.82%   |
| 24.01-32.0  | 8         | 0.59%   |
| 64.01-256.0 | 3         | 0.22%   |
| 0           | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 515       | 43.02%  |
| 2      | 319       | 26.65%  |
| 3      | 146       | 12.2%   |
| 4      | 85        | 7.1%    |
| 5      | 57        | 4.76%   |
| 6      | 26        | 2.17%   |
| 7      | 19        | 1.59%   |
| 0      | 11        | 0.92%   |
| 8      | 6         | 0.5%    |
| 13     | 3         | 0.25%   |
| 9      | 3         | 0.25%   |
| 12     | 2         | 0.17%   |
| 26     | 1         | 0.08%   |
| 18     | 1         | 0.08%   |
| 17     | 1         | 0.08%   |
| 11     | 1         | 0.08%   |
| 10     | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 894       | 77.2%   |
| Yes       | 264       | 22.8%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 989       | 86.22%  |
| No        | 158       | 13.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 765       | 66.7%   |
| No        | 382       | 33.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 701       | 60.75%  |
| No        | 453       | 39.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 223       | 19.43%  |
| Germany      | 183       | 15.94%  |
| Russia       | 101       | 8.8%    |
| UK           | 58        | 5.05%   |
| France       | 47        | 4.09%   |
| Spain        | 41        | 3.57%   |
| Poland       | 38        | 3.31%   |
| Canada       | 38        | 3.31%   |
| China        | 36        | 3.14%   |
| Sweden       | 26        | 2.26%   |
| Netherlands  | 25        | 2.18%   |
| Finland      | 25        | 2.18%   |
| Italy        | 24        | 2.09%   |
| Australia    | 23        | 2%      |
| Czechia      | 22        | 1.92%   |
| Ukraine      | 21        | 1.83%   |
| Switzerland  | 15        | 1.31%   |
| Greece       | 15        | 1.31%   |
| Brazil       | 14        | 1.22%   |
| Belgium      | 12        | 1.05%   |
| Austria      | 12        | 1.05%   |
| Belarus      | 10        | 0.87%   |
| Norway       | 9         | 0.78%   |
| Mexico       | 9         | 0.78%   |
| Japan        | 9         | 0.78%   |
| Turkey       | 8         | 0.7%    |
| Romania      | 8         | 0.7%    |
| Hong Kong    | 8         | 0.7%    |
| India        | 7         | 0.61%   |
| Argentina    | 6         | 0.52%   |
| Taiwan       | 5         | 0.44%   |
| Slovenia     | 5         | 0.44%   |
| Slovakia     | 5         | 0.44%   |
| Hungary      | 5         | 0.44%   |
| South Africa | 4         | 0.35%   |
| Portugal     | 4         | 0.35%   |
| Estonia      | 4         | 0.35%   |
| New Zealand  | 3         | 0.26%   |
| Ireland      | 3         | 0.26%   |
| Chile        | 3         | 0.26%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 44        | 3.55%   |
| Moscow            | 35        | 2.82%   |
| St Petersburg     | 18        | 1.45%   |
| Athens            | 15        | 1.21%   |
| Munich            | 13        | 1.05%   |
| Warsaw            | 12        | 0.97%   |
| Sydney            | 11        | 0.89%   |
| Helsinki          | 11        | 0.89%   |
| Kyiv              | 10        | 0.81%   |
| Los Angeles       | 9         | 0.73%   |
| Cieszyn           | 9         | 0.73%   |
| Amsterdam         | 9         | 0.73%   |
| Wuelfrath         | 8         | 0.65%   |
| Vladivostok       | 8         | 0.65%   |
| Prague            | 8         | 0.65%   |
| Paris             | 8         | 0.65%   |
| Frankfurt am Main | 8         | 0.65%   |
| Ottawa            | 7         | 0.56%   |
| Minsk             | 7         | 0.56%   |
| Melbourne         | 7         | 0.56%   |
| Guangzhou         | 7         | 0.56%   |
| Woolwich          | 6         | 0.48%   |
| Vienna            | 6         | 0.48%   |
| Oulu              | 6         | 0.48%   |
| Manitowoc         | 6         | 0.48%   |
| Hamburg           | 6         | 0.48%   |
| Dienheim          | 6         | 0.48%   |
| Beijing           | 6         | 0.48%   |
| Zurich            | 5         | 0.4%    |
| Vancouver         | 5         | 0.4%    |
| Swansea           | 5         | 0.4%    |
| Sao Paulo         | 5         | 0.4%    |
| San Jose          | 5         | 0.4%    |
| Nuremberg         | 5         | 0.4%    |
| Milan             | 5         | 0.4%    |
| London            | 5         | 0.4%    |
| Falkenstein       | 5         | 0.4%    |
| Combrit           | 5         | 0.4%    |
| Weatherford       | 4         | 0.32%   |
| Utrecht           | 4         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 429       | 844    | 22.29%  |
| WDC                 | 353       | 746    | 18.34%  |
| Seagate             | 244       | 506    | 12.68%  |
| Kingston            | 103       | 138    | 5.35%   |
| Toshiba             | 95        | 140    | 4.94%   |
| Intel               | 90        | 146    | 4.68%   |
| SanDisk             | 74        | 100    | 3.84%   |
| Crucial             | 58        | 98     | 3.01%   |
| SK hynix            | 52        | 63     | 2.7%    |
| Unknown             | 51        | 75     | 2.65%   |
| Hitachi             | 51        | 108    | 2.65%   |
| HGST                | 47        | 75     | 2.44%   |
| A-DATA Technology   | 32        | 47     | 1.66%   |
| Micron Technology   | 22        | 26     | 1.14%   |
| Phison              | 19        | 29     | 0.99%   |
| Corsair             | 17        | 31     | 0.88%   |
| KIOXIA              | 14        | 18     | 0.73%   |
| OCZ                 | 12        | 15     | 0.62%   |
| Transcend           | 7         | 12     | 0.36%   |
| Plextor             | 7         | 8      | 0.36%   |
| GOODRAM             | 7         | 21     | 0.36%   |
| Fujitsu             | 7         | 10     | 0.36%   |
| Apple               | 7         | 9      | 0.36%   |
| SPCC                | 6         | 6      | 0.31%   |
| Patriot             | 6         | 9      | 0.31%   |
| Mushkin             | 6         | 6      | 0.31%   |
| XPG                 | 5         | 6      | 0.26%   |
| Team                | 5         | 12     | 0.26%   |
| LITEONIT            | 5         | 6      | 0.26%   |
| LITEON              | 5         | 8      | 0.26%   |
| IBM                 | 5         | 6      | 0.26%   |
| PNY                 | 4         | 4      | 0.21%   |
| KIOXIA-EXCERIA      | 4         | 8      | 0.21%   |
| China               | 4         | 6      | 0.21%   |
| Apacer              | 4         | 5      | 0.21%   |
| Netac               | 3         | 3      | 0.16%   |
| Lenovo              | 3         | 5      | 0.16%   |
| Hewlett-Packard     | 3         | 5      | 0.16%   |
| Gigabyte Technology | 3         | 4      | 0.16%   |
| TO Exter            | 2         | 2      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB        | 27        | 1.17%   |
| Samsung SSD 860 EVO 1TB          | 21        | 0.91%   |
| Samsung SSD 850 EVO 500GB        | 20        | 0.86%   |
| Samsung SSD 970 EVO Plus 500GB   | 19        | 0.82%   |
| HGST HTS721010A9E630 1TB         | 19        | 0.82%   |
| WDC WD30EFRX-68EUZN0 3TB         | 18        | 0.78%   |
| Samsung SSD 860 EVO 250GB        | 18        | 0.78%   |
| Samsung SSD 860 EVO 500GB        | 17        | 0.73%   |
| Kingston SA400S37240G 240GB SSD  | 16        | 0.69%   |
| Samsung SSD 970 EVO Plus 1TB     | 15        | 0.65%   |
| Samsung SSD 970 EVO 500GB        | 15        | 0.65%   |
| Samsung SSD 970 EVO 250GB        | 13        | 0.56%   |
| Samsung SSD 970 EVO 1TB          | 13        | 0.56%   |
| Samsung SSD 980 PRO 1TB          | 12        | 0.52%   |
| Seagate ST1000DM010-2EP102 1TB   | 11        | 0.47%   |
| Samsung SSD 970 PRO 512GB        | 11        | 0.47%   |
| Samsung SSD 840 EVO 120GB        | 11        | 0.47%   |
| Intel SSDPEKNW010T8 1TB          | 11        | 0.47%   |
| Seagate ST500DM002-1BD142 500GB  | 10        | 0.43%   |
| Seagate ST2000DM001-1ER164 2TB   | 10        | 0.43%   |
| Samsung SSD 970 PRO 1TB          | 10        | 0.43%   |
| Samsung SSD 970 EVO Plus 250GB   | 10        | 0.43%   |
| Samsung MZVLB512HBJQ-000L2 512GB | 10        | 0.43%   |
| Kingston SA400S37480G 480GB SSD  | 10        | 0.43%   |
| WDC WD40EFRX-68WT0N0 4TB         | 9         | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB         | 9         | 0.39%   |
| Seagate ST4000DM004-2CV104 4TB   | 9         | 0.39%   |
| Seagate ST3500418AS 500GB        | 9         | 0.39%   |
| Seagate ST2000DM006-2DM164 2TB   | 9         | 0.39%   |
| Samsung SSD 850 EVO 1TB          | 9         | 0.39%   |
| Samsung SSD 840 EVO 250GB        | 9         | 0.39%   |
| Samsung NVMe SSD Drive 512GB     | 9         | 0.39%   |
| Kingston SA400S37120G 120GB SSD  | 9         | 0.39%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 8         | 0.35%   |
| WDC WD20EFRX-68EUZN0 2TB         | 8         | 0.35%   |
| Unknown MMC Card  64GB           | 8         | 0.35%   |
| Unknown MMC Card  32GB           | 8         | 0.35%   |
| Toshiba DT01ACA100 1TB           | 8         | 0.35%   |
| Seagate ST1000DM003-1CH162 1TB   | 8         | 0.35%   |
| Samsung SSD 980 PRO 2TB          | 8         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 254       | 577    | 36.44%  |
| Seagate             | 236       | 493    | 33.86%  |
| Toshiba             | 61        | 95     | 8.75%   |
| Hitachi             | 51        | 108    | 7.32%   |
| HGST                | 47        | 75     | 6.74%   |
| Samsung Electronics | 25        | 36     | 3.59%   |
| Fujitsu             | 7         | 10     | 1%      |
| IBM                 | 5         | 6      | 0.72%   |
| Unknown             | 3         | 4      | 0.43%   |
| MDT                 | 2         | 2      | 0.29%   |
| LaCie               | 2         | 12     | 0.29%   |
| IBM/Hitachi         | 2         | 2      | 0.29%   |
| Hewlett-Packard     | 1         | 2      | 0.14%   |
| Apple               | 1         | 1      | 0.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 223       | 391    | 34.05%  |
| Kingston            | 75        | 99     | 11.45%  |
| SanDisk             | 60        | 86     | 9.16%   |
| Crucial             | 50        | 83     | 7.63%   |
| WDC                 | 40        | 54     | 6.11%   |
| Intel               | 34        | 43     | 5.19%   |
| A-DATA Technology   | 18        | 27     | 2.75%   |
| SK hynix            | 12        | 13     | 1.83%   |
| OCZ                 | 11        | 14     | 1.68%   |
| Micron Technology   | 11        | 14     | 1.68%   |
| Toshiba             | 10        | 12     | 1.53%   |
| Corsair             | 10        | 16     | 1.53%   |
| GOODRAM             | 7         | 21     | 1.07%   |
| Transcend           | 6         | 11     | 0.92%   |
| Plextor             | 6         | 6      | 0.92%   |
| SPCC                | 5         | 5      | 0.76%   |
| Mushkin             | 5         | 5      | 0.76%   |
| LITEONIT            | 5         | 6      | 0.76%   |
| Team                | 4         | 6      | 0.61%   |
| Patriot             | 4         | 7      | 0.61%   |
| China               | 4         | 6      | 0.61%   |
| Apple               | 4         | 5      | 0.61%   |
| PNY                 | 3         | 3      | 0.46%   |
| TO Exter            | 2         | 2      | 0.31%   |
| Seagate             | 2         | 5      | 0.31%   |
| Netac               | 2         | 2      | 0.31%   |
| MyDigitalSSD        | 2         | 2      | 0.31%   |
| LITEON              | 2         | 3      | 0.31%   |
| Linux               | 2         | 2      | 0.31%   |
| KingDian            | 2         | 2      | 0.31%   |
| Intenso             | 2         | 3      | 0.31%   |
| Apacer              | 2         | 3      | 0.31%   |
| Zheino              | 1         | 1      | 0.15%   |
| XrayDisk            | 1         | 1      | 0.15%   |
| Verbatim            | 1         | 1      | 0.15%   |
| Unknown             | 1         | 1      | 0.15%   |
| Super Talent        | 1         | 1      | 0.15%   |
| Smartbuy            | 1         | 1      | 0.15%   |
| ShanDianZhe         | 1         | 2      | 0.15%   |
| RevuAhn             | 1         | 1      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 581       | 958    | 33.82%  |
| HDD     | 545       | 1423   | 31.72%  |
| SSD     | 542       | 994    | 31.55%  |
| MMC     | 45        | 66     | 2.62%   |
| Unknown | 5         | 7      | 0.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 798       | 2366   | 54.81%  |
| NVMe | 580       | 957    | 39.84%  |
| MMC  | 45        | 66     | 3.09%   |
| SAS  | 33        | 59     | 2.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 553       | 1029   | 45.63%  |
| 0.51-1.0   | 345       | 558    | 28.47%  |
| 1.01-2.0   | 147       | 336    | 12.13%  |
| 3.01-4.0   | 71        | 162    | 5.86%   |
| 2.01-3.0   | 46        | 118    | 3.8%    |
| 4.01-10.0  | 42        | 194    | 3.47%   |
| 10.01-20.0 | 7         | 19     | 0.58%   |
| 20.01-50.0 | 1         | 1      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 247       | 20.05%  |
| 101-250        | 229       | 18.59%  |
| 501-1000       | 191       | 15.5%   |
| 1001-2000      | 144       | 11.69%  |
| More than 3000 | 123       | 9.98%   |
| Unknown        | 74        | 6.01%   |
| 2001-3000      | 70        | 5.68%   |
| 51-100         | 63        | 5.11%   |
| 1-20           | 58        | 4.71%   |
| 21-50          | 33        | 2.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 265       | 20.54%  |
| 101-250        | 185       | 14.34%  |
| 21-50          | 179       | 13.88%  |
| 251-500        | 167       | 12.95%  |
| 51-100         | 123       | 9.53%   |
| 501-1000       | 114       | 8.84%   |
| 1001-2000      | 90        | 6.98%   |
| Unknown        | 74        | 5.74%   |
| More than 3000 | 59        | 4.57%   |
| 2001-3000      | 34        | 2.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB                    | 6         | 7      | 2.65%   |
| HGST HTS721010A9E630 1TB                     | 5         | 6      | 2.21%   |
| WDC WD40EFRX-68WT0N0 4TB                     | 4         | 14     | 1.77%   |
| Seagate ST8000AS0002-1NA17Z 8TB              | 3         | 15     | 1.33%   |
| Seagate ST500DM002-1BD142 500GB              | 3         | 3      | 1.33%   |
| Seagate ST500DM002-1BC142 500GB              | 3         | 3      | 1.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 3         | 4      | 1.33%   |
| Samsung Electronics SSD 850 EVO 1TB          | 3         | 3      | 1.33%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD      | 3         | 3      | 1.33%   |
| IBM DJSA-220 12GB                            | 3         | 3      | 1.33%   |
| WDC WD60EFRX-68MYMN1 6TB                     | 2         | 5      | 0.88%   |
| WDC WD40EFRX-68N32N0 4TB                     | 2         | 2      | 0.88%   |
| WDC WD30EFRX-68AX9N0 3TB                     | 2         | 3      | 0.88%   |
| WDC WD20EZRX-00D8PB0 2TB                     | 2         | 3      | 0.88%   |
| WDC WD20EARS-00MVWB0 2TB                     | 2         | 2      | 0.88%   |
| WDC WD2002FAEX-007BA0 2TB                    | 2         | 2      | 0.88%   |
| WDC WD1600AAJS-75B4A0 160GB                  | 2         | 2      | 0.88%   |
| WDC WD15EARS-00Z5B1 1TB                      | 2         | 2      | 0.88%   |
| SK hynix HFS256G39TND-N210A 256GB SSD        | 2         | 2      | 0.88%   |
| Seagate ST4000DM000-1F2168 4TB               | 2         | 2      | 0.88%   |
| Seagate ST31000340NS 1TB                     | 2         | 3      | 0.88%   |
| Seagate ST3000DM001-9YN166 3TB               | 2         | 2      | 0.88%   |
| Seagate ST2000LX001-1RG174 2TB               | 2         | 2      | 0.88%   |
| Seagate ST2000DL003-9VT166 2TB               | 2         | 3      | 0.88%   |
| Seagate ST1000NM0011 1TB                     | 2         | 6      | 0.88%   |
| SanDisk SSD PLUS 1000GB                      | 2         | 2      | 0.88%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD          | 2         | 2      | 0.88%   |
| Samsung Electronics SSD 870 EVO 500GB        | 2         | 3      | 0.88%   |
| Samsung Electronics SSD 840 PRO Series 512GB | 2         | 4      | 0.88%   |
| Samsung Electronics HD103UJ 1TB              | 2         | 2      | 0.88%   |
| MDT MD2000KS-00MJB0 200GB                    | 2         | 2      | 0.88%   |
| Hitachi HDS722020ALA330 2TB                  | 2         | 16     | 0.88%   |
| Crucial CT525MX300SSD1 528GB                 | 2         | 2      | 0.88%   |
| WDC WD80EFZX-68UW8N0 8TB                     | 1         | 2      | 0.44%   |
| WDC WD7501AALS-00J7B0 752GB                  | 1         | 1      | 0.44%   |
| WDC WD6401AALS-00J7B0 640GB                  | 1         | 1      | 0.44%   |
| WDC WD6400AAKS-65A7B2 640GB                  | 1         | 1      | 0.44%   |
| WDC WD60EFRX-68L0BN1 6TB                     | 1         | 18     | 0.44%   |
| WDC WD5000BEVT-22ZAT0 500GB                  | 1         | 1      | 0.44%   |
| WDC WD5000AZRX-00A8LB0 500GB                 | 1         | 1      | 0.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 83     | 25.12%  |
| WDC                 | 48        | 89     | 22.33%  |
| Samsung Electronics | 24        | 35     | 11.16%  |
| Hitachi             | 15        | 30     | 6.98%   |
| Toshiba             | 11        | 13     | 5.12%   |
| SanDisk             | 8         | 10     | 3.72%   |
| HGST                | 8         | 10     | 3.72%   |
| Kingston            | 6         | 6      | 2.79%   |
| Crucial             | 6         | 6      | 2.79%   |
| Intel               | 5         | 5      | 2.33%   |
| SK hynix            | 4         | 4      | 1.86%   |
| IBM                 | 4         | 4      | 1.86%   |
| Fujitsu             | 4         | 4      | 1.86%   |
| Plextor             | 2         | 2      | 0.93%   |
| OCZ                 | 2         | 2      | 0.93%   |
| MDT                 | 2         | 2      | 0.93%   |
| Corsair             | 2         | 4      | 0.93%   |
| A-DATA Technology   | 2         | 2      | 0.93%   |
| Transcend           | 1         | 1      | 0.47%   |
| SPCC                | 1         | 1      | 0.47%   |
| Mushkin             | 1         | 1      | 0.47%   |
| LITEON              | 1         | 2      | 0.47%   |
| IBM/Hitachi         | 1         | 1      | 0.47%   |
| EMTEC               | 1         | 2      | 0.47%   |
| Apple               | 1         | 1      | 0.47%   |
| 2.5"                | 1         | 1      | 0.47%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 83     | 35.76%  |
| WDC                 | 48        | 89     | 31.79%  |
| Hitachi             | 15        | 30     | 9.93%   |
| Toshiba             | 10        | 12     | 6.62%   |
| HGST                | 8         | 10     | 5.3%    |
| Samsung Electronics | 4         | 5      | 2.65%   |
| IBM                 | 4         | 4      | 2.65%   |
| Fujitsu             | 4         | 4      | 2.65%   |
| MDT                 | 2         | 2      | 1.32%   |
| IBM/Hitachi         | 1         | 1      | 0.66%   |
| Apple               | 1         | 1      | 0.66%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 143       | 241    | 68.75%  |
| SSD  | 54        | 66     | 25.96%  |
| NVMe | 11        | 14     | 5.29%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB                 | 2         | 2      | 28.57%  |
| WDC WD6400BEVT-22A0RT0 640GB                     | 1         | 1      | 14.29%  |
| Seagate ST3500630AS 500GB                        | 1         | 2      | 14.29%  |
| Seagate ST31500341AS 1TB                         | 1         | 1      | 14.29%  |
| Samsung Electronics MZ7LN256HCHP-00000 256GB SSD | 1         | 2      | 14.29%  |
| Hitachi HTS721010G9SA00 100GB                    | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 2      | 28.57%  |
| Seagate             | 2         | 3      | 28.57%  |
| WDC                 | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 2      | 14.29%  |
| Hitachi             | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 987       | 2790   | 72.79%  |
| Malfunc  | 199       | 321    | 14.68%  |
| Detected | 163       | 328    | 12.02%  |
| Failed   | 7         | 9      | 0.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 613       | 36.64%  |
| AMD                              | 332       | 19.84%  |
| Samsung Electronics              | 264       | 15.78%  |
| SanDisk                          | 92        | 5.5%    |
| ASMedia Technology               | 54        | 3.23%   |
| SK hynix                         | 40        | 2.39%   |
| Phison Electronics               | 36        | 2.15%   |
| Kingston Technology Company      | 30        | 1.79%   |
| Toshiba America Info Systems     | 29        | 1.73%   |
| Marvell Technology Group         | 23        | 1.37%   |
| Nvidia                           | 19        | 1.14%   |
| ADATA Technology                 | 18        | 1.08%   |
| KIOXIA                           | 17        | 1.02%   |
| Micron Technology                | 12        | 0.72%   |
| JMicron Technology               | 12        | 0.72%   |
| Silicon Motion                   | 11        | 0.66%   |
| Micron/Crucial Technology        | 11        | 0.66%   |
| LSI Logic / Symbios Logic        | 11        | 0.66%   |
| Broadcom / LSI                   | 9         | 0.54%   |
| Adaptec                          | 6         | 0.36%   |
| Seagate Technology               | 5         | 0.3%    |
| Solid State Storage Technology   | 3         | 0.18%   |
| Silicon Image                    | 3         | 0.18%   |
| Realtek Semiconductor            | 3         | 0.18%   |
| Lite-On Technology               | 3         | 0.18%   |
| Union Memory (Shenzhen)          | 2         | 0.12%   |
| Silicon Integrated Systems [SiS] | 2         | 0.12%   |
| Lenovo                           | 2         | 0.12%   |
| Apple                            | 2         | 0.12%   |
| 3ware                            | 2         | 0.12%   |
| VIA Technologies                 | 1         | 0.06%   |
| Unknown                          | 1         | 0.06%   |
| OCZ Technology Group             | 1         | 0.06%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.06%   |
| Integrated Technology Express    | 1         | 0.06%   |
| Hewlett-Packard                  | 1         | 0.06%   |
| Broadcom                         | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 256       | 13.4%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 168       | 8.79%   |
| AMD 400 Series Chipset SATA Controller                                         | 80        | 4.19%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 51        | 2.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 50        | 2.62%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 45        | 2.35%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 37        | 1.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 36        | 1.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 35        | 1.83%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 34        | 1.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 34        | 1.78%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 33        | 1.73%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 28        | 1.47%   |
| AMD 500 Series Chipset SATA Controller                                         | 27        | 1.41%   |
| Intel SSD 660P Series                                                          | 26        | 1.36%   |
| Samsung NVMe SSD Controller 980                                                | 23        | 1.2%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 23        | 1.2%    |
| SK hynix Gold P31 SSD                                                          | 21        | 1.1%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 21        | 1.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 21        | 1.1%    |
| Intel Volume Management Device NVMe RAID Controller                            | 19        | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 19        | 0.99%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 18        | 0.94%   |
| Intel Comet Lake SATA AHCI Controller                                          | 18        | 0.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 18        | 0.94%   |
| AMD X370 Series Chipset SATA Controller                                        | 18        | 0.94%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 18        | 0.94%   |
| Phison E12 NVMe Controller                                                     | 15        | 0.78%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 15        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 15        | 0.78%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 15        | 0.78%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 14        | 0.73%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 14        | 0.73%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 14        | 0.73%   |
| Intel SATA Controller [RAID mode]                                              | 13        | 0.68%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 13        | 0.68%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 13        | 0.68%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 13        | 0.68%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 12        | 0.63%   |
| Micron Non-Volatile memory controller                                          | 12        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 835       | 51.58%  |
| NVMe | 586       | 36.2%   |
| IDE  | 96        | 5.93%   |
| RAID | 78        | 4.82%   |
| SAS  | 17        | 1.05%   |
| SCSI | 7         | 0.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 706       | 61.98%  |
| AMD                      | 406       | 35.65%  |
| ARM                      | 15        | 1.32%   |
| Marvell Semiconductor    | 3         | 0.26%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.09%   |
| PowerMac8,1              | 1         | 0.09%   |
| PowerMac3,6              | 1         | 0.09%   |
| PowerMac10,2             | 1         | 0.09%   |
| PowerBook6,7             | 1         | 0.09%   |
| PowerBook5,6             | 1         | 0.09%   |
| PowerBook5,5             | 1         | 0.09%   |
| PowerBook5,4             | 1         | 0.09%   |
| PowerBook3,4             | 1         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor            | 23        | 2.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 20        | 1.75%   |
| AMD Ryzen 5 3600 6-Core Processor             | 19        | 1.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 18        | 1.57%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 16        | 1.4%    |
| AMD Ryzen 7 2700X Eight-Core Processor        | 16        | 1.4%    |
| AMD Ryzen 9 3950X 16-Core Processor           | 14        | 1.22%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 13        | 1.14%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 13        | 1.14%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 13        | 1.14%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 13        | 1.14%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 12        | 1.05%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 1.05%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 12        | 1.05%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 12        | 1.05%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 12        | 1.05%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 12        | 1.05%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 11        | 0.96%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 11        | 0.96%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 11        | 0.96%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 11        | 0.96%   |
| ARM Processor                                 | 10        | 0.87%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 10        | 0.87%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 9         | 0.79%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 9         | 0.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 9         | 0.79%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 9         | 0.79%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 0.79%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 9         | 0.79%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 0.7%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 0.7%    |
| AMD FX-8350 Eight-Core Processor              | 8         | 0.7%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 0.61%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 7         | 0.61%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 6         | 0.52%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 6         | 0.52%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 6         | 0.52%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 6         | 0.52%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 6         | 0.52%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 6         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 283       | 24.76%  |
| Intel Core i5          | 171       | 14.96%  |
| AMD Ryzen 7            | 135       | 11.81%  |
| AMD Ryzen 5            | 98        | 8.57%   |
| Other                  | 84        | 7.35%   |
| AMD Ryzen 9            | 56        | 4.9%    |
| Intel Xeon             | 48        | 4.2%    |
| AMD Ryzen 7 PRO        | 23        | 2.01%   |
| Intel Celeron          | 22        | 1.92%   |
| AMD FX                 | 21        | 1.84%   |
| Intel Core i9          | 18        | 1.57%   |
| Intel Core 2 Duo       | 18        | 1.57%   |
| Intel Atom             | 18        | 1.57%   |
| Intel Pentium          | 14        | 1.22%   |
| AMD Ryzen 3            | 14        | 1.22%   |
| Intel Core i3          | 13        | 1.14%   |
| Intel Core 2 Quad      | 10        | 0.87%   |
| AMD Phenom II X4       | 8         | 0.7%    |
| Intel Pentium M        | 7         | 0.61%   |
| AMD Ryzen Threadripper | 7         | 0.61%   |
| Intel Pentium 4        | 5         | 0.44%   |
| AMD Ryzen 5 PRO        | 5         | 0.44%   |
| AMD A6                 | 5         | 0.44%   |
| ARM BCM                | 4         | 0.35%   |
| AMD Sempron            | 4         | 0.35%   |
| AMD A10                | 4         | 0.35%   |
| Intel Pentium III      | 3         | 0.26%   |
| Intel Core m3          | 3         | 0.26%   |
| Intel Core 2           | 3         | 0.26%   |
| AMD Phenom II X6       | 3         | 0.26%   |
| AMD E                  | 3         | 0.26%   |
| AMD Athlon II X3       | 3         | 0.26%   |
| AMD Athlon 64 X2       | 3         | 0.26%   |
| AMD Athlon             | 3         | 0.26%   |
| AMD A8                 | 3         | 0.26%   |
| Intel Pentium Silver   | 2         | 0.17%   |
| Intel Genuine          | 2         | 0.17%   |
| AMD EPYC               | 2         | 0.17%   |
| AMD E1                 | 2         | 0.17%   |
| Intel Xeon Silver      | 1         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 414       | 36.19%  |
| 8       | 211       | 18.44%  |
| 2       | 190       | 16.61%  |
| 6       | 186       | 16.26%  |
| 12      | 44        | 3.85%   |
| 1       | 39        | 3.41%   |
| 16      | 31        | 2.71%   |
| Unknown | 9         | 0.79%   |
| 3       | 7         | 0.61%   |
| 14      | 3         | 0.26%   |
| 10      | 3         | 0.26%   |
| 32      | 2         | 0.17%   |
| 64      | 1         | 0.09%   |
| 24      | 1         | 0.09%   |
| 22      | 1         | 0.09%   |
| 20      | 1         | 0.09%   |
| 18      | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1113      | 97.55%  |
| 2       | 20        | 1.75%   |
| Unknown | 8         | 0.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 877       | 76.59%  |
| 1       | 258       | 22.53%  |
| Unknown | 9         | 0.79%   |
| 4       | 1         | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1097      | 96.31%  |
| 32-bit         | 28        | 2.46%   |
| Unknown        | 14        | 1.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 169       | 14.3%   |
| 0x906ea    | 56        | 4.74%   |
| 0x08701021 | 50        | 4.23%   |
| 0x506e3    | 47        | 3.98%   |
| 0x306a9    | 42        | 3.55%   |
| 0x306c3    | 40        | 3.38%   |
| 0x0800820d | 36        | 3.05%   |
| 0x806ec    | 34        | 2.88%   |
| 0x08701013 | 34        | 2.88%   |
| 0x906e9    | 33        | 2.79%   |
| 0x806ea    | 31        | 2.62%   |
| 0x0a50000c | 28        | 2.37%   |
| 0x206a7    | 26        | 2.2%    |
| 0x08600106 | 25        | 2.12%   |
| 0x806e9    | 24        | 2.03%   |
| 0x806c1    | 24        | 2.03%   |
| 0x906ed    | 20        | 1.69%   |
| 0x08001138 | 20        | 1.69%   |
| 0x0a201016 | 18        | 1.52%   |
| 0x0a201009 | 17        | 1.44%   |
| 0x40651    | 16        | 1.35%   |
| 0x1067a    | 16        | 1.35%   |
| 0x08108109 | 16        | 1.35%   |
| 0xa0652    | 15        | 1.27%   |
| 0x806d1    | 13        | 1.1%    |
| 0x08600103 | 13        | 1.1%    |
| 0x406e3    | 12        | 1.02%   |
| 0x306d4    | 12        | 1.02%   |
| 0x206c2    | 11        | 0.93%   |
| 0xa0671    | 10        | 0.85%   |
| 0xa0655    | 10        | 0.85%   |
| 0x08108102 | 10        | 0.85%   |
| 0x306f2    | 9         | 0.76%   |
| 0x306e4    | 8         | 0.68%   |
| 0x30678    | 8         | 0.68%   |
| 0x08608103 | 8         | 0.68%   |
| 0x90672    | 7         | 0.59%   |
| 0x806eb    | 7         | 0.59%   |
| 0x706e5    | 7         | 0.59%   |
| 0x706a1    | 6         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 238       | 20.77%  |
| Zen 2            | 146       | 12.74%  |
| Zen+             | 74        | 6.46%   |
| Haswell          | 73        | 6.37%   |
| Zen 3            | 71        | 6.2%    |
| Skylake          | 67        | 5.85%   |
| IvyBridge        | 53        | 4.62%   |
| Unknown          | 52        | 4.54%   |
| Zen              | 38        | 3.32%   |
| SandyBridge      | 34        | 2.97%   |
| CometLake        | 30        | 2.62%   |
| TigerLake        | 28        | 2.44%   |
| Icelake          | 27        | 2.36%   |
| Penryn           | 21        | 1.83%   |
| Westmere         | 19        | 1.66%   |
| Silvermont       | 19        | 1.66%   |
| Piledriver       | 18        | 1.57%   |
| Broadwell        | 18        | 1.57%   |
| K10              | 15        | 1.31%   |
| P6               | 14        | 1.22%   |
| Core             | 13        | 1.13%   |
| Alderlake Hybrid | 11        | 0.96%   |
| Bonnell          | 10        | 0.87%   |
| Nehalem          | 8         | 0.7%    |
| Goldmont plus    | 8         | 0.7%    |
| K8 Hammer        | 7         | 0.61%   |
| NetBurst         | 5         | 0.44%   |
| Bulldozer        | 5         | 0.44%   |
| Bobcat           | 5         | 0.44%   |
| Steamroller      | 4         | 0.35%   |
| Jaguar           | 4         | 0.35%   |
| Goldmont         | 4         | 0.35%   |
| Excavator        | 3         | 0.26%   |
| Puma             | 2         | 0.17%   |
| K10 Llano        | 2         | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 472       | 35.15%  |
| Nvidia                           | 447       | 33.28%  |
| AMD                              | 391       | 29.11%  |
| ASPEED Technology                | 18        | 1.34%   |
| Matrox Electronics Systems       | 14        | 1.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 74        | 5.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 51        | 3.67%   |
| AMD Renoir                                                                  | 49        | 3.53%   |
| Intel UHD Graphics 620                                                      | 38        | 2.74%   |
| Intel HD Graphics 530                                                       | 29        | 2.09%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 28        | 2.02%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 28        | 2.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 27        | 1.94%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 27        | 1.94%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 26        | 1.87%   |
| AMD Cezanne                                                                 | 25        | 1.8%    |
| Intel HD Graphics 620                                                       | 20        | 1.44%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 19        | 1.37%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 18        | 1.3%    |
| ASPEED Technology ASPEED Graphics Family                                    | 18        | 1.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 17        | 1.22%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 17        | 1.22%   |
| Intel HD Graphics 630                                                       | 16        | 1.15%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 14        | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 13        | 0.94%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 13        | 0.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 13        | 0.94%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 12        | 0.86%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 12        | 0.86%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 12        | 0.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 12        | 0.86%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 12        | 0.86%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 11        | 0.79%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 11        | 0.79%   |
| Intel HD Graphics 5500                                                      | 11        | 0.79%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 11        | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 10        | 0.72%   |
| Nvidia GK208B [GeForce GT 710]                                              | 10        | 0.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10        | 0.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 10        | 0.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 10        | 0.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 10        | 0.72%   |
| Nvidia GP108M [GeForce MX150]                                               | 9         | 0.65%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 9         | 0.65%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                     | 9         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x AMD                  | 327       | 28.39%  |
| 1 x Intel                | 284       | 24.65%  |
| 1 x Nvidia               | 258       | 22.4%   |
| Intel + Nvidia           | 155       | 13.45%  |
| AMD + Nvidia             | 28        | 2.43%   |
| Other                    | 22        | 1.91%   |
| Intel + AMD              | 17        | 1.48%   |
| 2 x AMD                  | 16        | 1.39%   |
| 1 x ASPEED               | 16        | 1.39%   |
| 1 x Matrox               | 12        | 1.04%   |
| 2 x Nvidia               | 6         | 0.52%   |
| 2 x Intel                | 5         | 0.43%   |
| AMD + ASPEED             | 2         | 0.17%   |
| 1 x SiS                  | 1         | 0.09%   |
| Nvidia + Matrox          | 1         | 0.09%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.09%   |
| AMD + Matrox             | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 804       | 68.66%  |
| Proprietary | 275       | 23.48%  |
| Unknown     | 92        | 7.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 533       | 44.87%  |
| 7.01-8.0   | 139       | 11.7%   |
| 0.01-0.5   | 129       | 10.86%  |
| 1.01-2.0   | 117       | 9.85%   |
| 3.01-4.0   | 110       | 9.26%   |
| 0.51-1.0   | 56        | 4.71%   |
| 5.01-6.0   | 47        | 3.96%   |
| 8.01-16.0  | 40        | 3.37%   |
| 2.01-3.0   | 13        | 1.09%   |
| 16.01-24.0 | 3         | 0.25%   |
| 4.01-5.0   | 1         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 142       | 10.73%  |
| Dell                    | 116       | 8.77%   |
| AU Optronics            | 115       | 8.69%   |
| BOE                     | 97        | 7.33%   |
| LG Display              | 93        | 7.03%   |
| Chimei Innolux          | 81        | 6.12%   |
| Goldstar                | 77        | 5.82%   |
| Ancor Communications    | 47        | 3.55%   |
| Hewlett-Packard         | 43        | 3.25%   |
| AOC                     | 43        | 3.25%   |
| BenQ                    | 42        | 3.17%   |
| Sharp                   | 41        | 3.1%    |
| Iiyama                  | 33        | 2.49%   |
| Acer                    | 33        | 2.49%   |
| Lenovo                  | 30        | 2.27%   |
| ViewSonic               | 28        | 2.12%   |
| Philips                 | 25        | 1.89%   |
| ASUSTek Computer        | 24        | 1.81%   |
| Apple                   | 24        | 1.81%   |
| Eizo                    | 16        | 1.21%   |
| Chi Mei Optoelectronics | 15        | 1.13%   |
| LG Electronics          | 9         | 0.68%   |
| Unknown                 | 8         | 0.6%    |
| MSI                     | 8         | 0.6%    |
| Fujitsu Siemens         | 8         | 0.6%    |
| CSO                     | 8         | 0.6%    |
| PANDA                   | 7         | 0.53%   |
| NEC Computers           | 6         | 0.45%   |
| InfoVision              | 6         | 0.45%   |
| Idek Iiyama             | 6         | 0.45%   |
| Sony                    | 5         | 0.38%   |
| Gigabyte Technology     | 5         | 0.38%   |
| Sceptre Tech            | 4         | 0.3%    |
| HannStar                | 4         | 0.3%    |
| Unknown                 | 4         | 0.3%    |
| Toshiba                 | 3         | 0.23%   |
| Panasonic               | 3         | 0.23%   |
| Envision Peripherals    | 3         | 0.23%   |
| AUS                     | 3         | 0.23%   |
| Yamaha                  | 2         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                 | 8         | 0.57%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 8         | 0.57%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.57%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 7         | 0.5%    |
| Goldstar 27GL850 GSM5B7F 2560x1440 600x340mm 27.2-inch                | 7         | 0.5%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 7         | 0.5%    |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                 | 6         | 0.43%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 6         | 0.43%   |
| Fujitsu Siemens P24W-6 IPS FUS07EA 1920x1200 518x324mm 24.1-inch      | 6         | 0.43%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.43%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 5         | 0.36%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 5         | 0.36%   |
| Dell U2715H DELD066 2560x1440 600x340mm 27.2-inch                     | 5         | 0.36%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                     | 5         | 0.36%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 5         | 0.36%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch      | 4         | 0.29%   |
| Unknown                                                               | 4         | 0.29%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 3         | 0.21%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 3         | 0.21%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 3         | 0.21%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 3         | 0.21%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 3         | 0.21%   |
| Sceptre Tech C305W-2560UN SPT0C0D 2560x1080 690x291mm 29.5-inch       | 3         | 0.21%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 3         | 0.21%   |
| Samsung Electronics SyncMaster SAM0584 2048x1152 510x290mm 23.1-inch  | 3         | 0.21%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3         | 0.21%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch  | 3         | 0.21%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 3         | 0.21%   |
| MSI MAG272QR MSI3CA8 2560x1440 597x336mm 27.0-inch                    | 3         | 0.21%   |
| LG Electronics LCD Monitor LG HDR 4K 7680x2160                        | 3         | 0.21%   |
| LG Electronics LCD Monitor LG HDR 4K                                  | 3         | 0.21%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch          | 3         | 0.21%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 3         | 0.21%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 3         | 0.21%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 3         | 0.21%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch              | 3         | 0.21%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3         | 0.21%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 800x330mm 34.1-inch      | 3         | 0.21%   |
| Envision Peripherals LCD2361 ENV2361 1920x1080 521x293mm 23.5-inch    | 3         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 593       | 47.06%  |
| 2560x1440 (QHD)    | 122       | 9.68%   |
| 3840x2160 (4K)     | 114       | 9.05%   |
| 1366x768 (WXGA)    | 76        | 6.03%   |
| 1920x1200 (WUXGA)  | 44        | 3.49%   |
| 1280x1024 (SXGA)   | 37        | 2.94%   |
| 1680x1050 (WSXGA+) | 31        | 2.46%   |
| 3440x1440          | 30        | 2.38%   |
| 1600x900 (HD+)     | 26        | 2.06%   |
| Unknown            | 24        | 1.9%    |
| 1440x900 (WXGA+)   | 21        | 1.67%   |
| 2560x1600          | 15        | 1.19%   |
| 3840x2400          | 14        | 1.11%   |
| 3840x1080          | 14        | 1.11%   |
| 2560x1080          | 14        | 1.11%   |
| 1280x800 (WXGA)    | 9         | 0.71%   |
| 2880x1800          | 5         | 0.4%    |
| 1600x1200          | 5         | 0.4%    |
| 1024x600           | 5         | 0.4%    |
| 3200x1800 (QHD+)   | 4         | 0.32%   |
| 2048x1152          | 4         | 0.32%   |
| 7680x2160          | 3         | 0.24%   |
| 3840x1200          | 3         | 0.24%   |
| 2160x1440          | 3         | 0.24%   |
| 1280x960           | 3         | 0.24%   |
| 1280x854           | 3         | 0.24%   |
| 2288x1287          | 2         | 0.16%   |
| 2256x1504          | 2         | 0.16%   |
| 2160x1200          | 2         | 0.16%   |
| 1920x540           | 2         | 0.16%   |
| 1920x1280          | 2         | 0.16%   |
| 1400x1050          | 2         | 0.16%   |
| 1024x768 (XGA)     | 2         | 0.16%   |
| 6720x2160          | 1         | 0.08%   |
| 6400x2160          | 1         | 0.08%   |
| 6400x1080          | 1         | 0.08%   |
| 5760x2160          | 1         | 0.08%   |
| 5120x1600          | 1         | 0.08%   |
| 5040x1080          | 1         | 0.08%   |
| 4880x1080          | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 245       | 18.73%  |
| 27      | 178       | 13.61%  |
| 24      | 129       | 9.86%   |
| 23      | 113       | 8.64%   |
| 13      | 107       | 8.18%   |
| 14      | 79        | 6.04%   |
| Unknown | 74        | 5.66%   |
| 17      | 66        | 5.05%   |
| 21      | 65        | 4.97%   |
| 34      | 35        | 2.68%   |
| 19      | 34        | 2.6%    |
| 12      | 28        | 2.14%   |
| 22      | 20        | 1.53%   |
| 31      | 16        | 1.22%   |
| 25      | 14        | 1.07%   |
| 16      | 12        | 0.92%   |
| 11      | 11        | 0.84%   |
| 20      | 10        | 0.76%   |
| 84      | 9         | 0.69%   |
| 18      | 8         | 0.61%   |
| 32      | 7         | 0.54%   |
| 48      | 5         | 0.38%   |
| 72      | 4         | 0.31%   |
| 54      | 4         | 0.31%   |
| 49      | 4         | 0.31%   |
| 40      | 4         | 0.31%   |
| 29      | 4         | 0.31%   |
| 26      | 4         | 0.31%   |
| 10      | 4         | 0.31%   |
| 142     | 2         | 0.15%   |
| 47      | 2         | 0.15%   |
| 43      | 2         | 0.15%   |
| 8       | 2         | 0.15%   |
| 75      | 1         | 0.08%   |
| 65      | 1         | 0.08%   |
| 50      | 1         | 0.08%   |
| 37      | 1         | 0.08%   |
| 33      | 1         | 0.08%   |
| 30      | 1         | 0.08%   |
| 28      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 393       | 31.12%  |
| 501-600        | 368       | 29.14%  |
| 401-500        | 116       | 9.18%   |
| 201-300        | 101       | 8%      |
| 351-400        | 77        | 6.1%    |
| Unknown        | 74        | 5.86%   |
| 601-700        | 49        | 3.88%   |
| 701-800        | 43        | 3.4%    |
| 1001-1500      | 18        | 1.43%   |
| 1501-2000      | 14        | 1.11%   |
| 801-900        | 5         | 0.4%    |
| More than 2000 | 2         | 0.16%   |
| 101-200        | 2         | 0.16%   |
| 901-1000       | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 815       | 71.18%  |
| 16/10   | 150       | 13.1%   |
| Unknown | 65        | 5.68%   |
| 21/9    | 38        | 3.32%   |
| 5/4     | 36        | 3.14%   |
| 3/2     | 16        | 1.4%    |
| 4/3     | 10        | 0.87%   |
| 32/9    | 9         | 0.79%   |
| 6/5     | 2         | 0.17%   |
| 1.00    | 2         | 0.17%   |
| 3.40    | 1         | 0.09%   |
| 3.20    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 243       | 18.82%  |
| 101-110        | 243       | 18.82%  |
| 301-350        | 180       | 13.94%  |
| 81-90          | 133       | 10.3%   |
| Unknown        | 74        | 5.73%   |
| 251-300        | 69        | 5.34%   |
| 351-500        | 62        | 4.8%    |
| 151-200        | 61        | 4.73%   |
| 71-80          | 53        | 4.11%   |
| 121-130        | 43        | 3.33%   |
| 61-70          | 25        | 1.94%   |
| More than 1000 | 24        | 1.86%   |
| 141-150        | 23        | 1.78%   |
| 501-1000       | 16        | 1.24%   |
| 51-60          | 13        | 1.01%   |
| 111-120        | 13        | 1.01%   |
| 131-140        | 6         | 0.46%   |
| 91-100         | 5         | 0.39%   |
| 41-50          | 3         | 0.23%   |
| 1-40           | 2         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 398       | 32.1%   |
| 121-160       | 357       | 28.79%  |
| 101-120       | 236       | 19.03%  |
| 161-240       | 106       | 8.55%   |
| Unknown       | 74        | 5.97%   |
| More than 240 | 52        | 4.19%   |
| 1-50          | 17        | 1.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 810       | 67.78%  |
| 2     | 233       | 19.5%   |
| 0     | 105       | 8.79%   |
| 3     | 40        | 3.35%   |
| 4     | 7         | 0.59%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 707       | 43.08%  |
| Realtek Semiconductor             | 521       | 31.75%  |
| Qualcomm Atheros                  | 120       | 7.31%   |
| Broadcom                          | 71        | 4.33%   |
| Aquantia                          | 17        | 1.04%   |
| Marvell Technology Group          | 16        | 0.98%   |
| Nvidia                            | 15        | 0.91%   |
| MediaTek                          | 15        | 0.91%   |
| ASIX Electronics                  | 15        | 0.91%   |
| Lenovo                            | 12        | 0.73%   |
| Apple                             | 10        | 0.61%   |
| TP-Link                           | 8         | 0.49%   |
| Dell                              | 8         | 0.49%   |
| Broadcom Limited                  | 7         | 0.43%   |
| Sierra Wireless                   | 6         | 0.37%   |
| Qualcomm Atheros Communications   | 6         | 0.37%   |
| Ralink Technology                 | 5         | 0.3%    |
| Qualcomm                          | 5         | 0.3%    |
| Microsoft                         | 5         | 0.3%    |
| Ericsson Business Mobile Networks | 5         | 0.3%    |
| Samsung Electronics               | 4         | 0.24%   |
| FIBOCOM                           | 4         | 0.24%   |
| D-Link System                     | 4         | 0.24%   |
| Standard Microsystems             | 3         | 0.18%   |
| Ralink                            | 3         | 0.18%   |
| Microchip Technology              | 3         | 0.18%   |
| Huawei Technologies               | 3         | 0.18%   |
| D-Link                            | 3         | 0.18%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.12%   |
| Xiaomi                            | 2         | 0.12%   |
| QLogic                            | 2         | 0.12%   |
| NetGear                           | 2         | 0.12%   |
| Netchip Technology                | 2         | 0.12%   |
| Metrologic Instruments            | 2         | 0.12%   |
| Google                            | 2         | 0.12%   |
| DisplayLink                       | 2         | 0.12%   |
| 3Com                              | 2         | 0.12%   |
| U-Blox                            | 1         | 0.06%   |
| Texas Instruments                 | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 390       | 19.7%   |
| Intel Wi-Fi 6 AX200                                               | 124       | 6.26%   |
| Intel I211 Gigabit Network Connection                             | 94        | 4.75%   |
| Intel Wireless 8265 / 8275                                        | 52        | 2.63%   |
| Realtek RTL8125 2.5GbE Controller                                 | 41        | 2.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 41        | 2.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 35        | 1.77%   |
| Intel I210 Gigabit Network Connection                             | 30        | 1.52%   |
| Intel Ethernet Connection (2) I219-V                              | 27        | 1.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25        | 1.26%   |
| Intel Wi-Fi 6 AX201                                               | 23        | 1.16%   |
| Intel Ethernet Controller I225-V                                  | 23        | 1.16%   |
| Intel 82574L Gigabit Network Connection                           | 23        | 1.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 22        | 1.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 1.11%   |
| Intel Wireless 8260                                               | 22        | 1.11%   |
| Intel Wireless 7265                                               | 21        | 1.06%   |
| Intel Ethernet Connection (2) I219-LM                             | 21        | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 20        | 1.01%   |
| Intel Wireless-AC 9260                                            | 19        | 0.96%   |
| Intel Ethernet Connection (7) I219-V                              | 19        | 0.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 18        | 0.91%   |
| Intel Wireless 7260                                               | 18        | 0.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 18        | 0.91%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 18        | 0.91%   |
| Intel Ethernet Connection (4) I219-LM                             | 16        | 0.81%   |
| Intel Wireless 3165                                               | 14        | 0.71%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 14        | 0.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 14        | 0.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 13        | 0.66%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 13        | 0.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 13        | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 12        | 0.61%   |
| Intel Ethernet Connection (2) I218-V                              | 12        | 0.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 11        | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 11        | 0.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 0.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 0.56%   |
| Intel Ethernet Connection (4) I219-V                              | 11        | 0.56%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 10        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 498       | 61.79%  |
| Qualcomm Atheros                  | 94        | 11.66%  |
| Realtek Semiconductor             | 89        | 11.04%  |
| Broadcom                          | 48        | 5.96%   |
| MediaTek                          | 13        | 1.61%   |
| TP-Link                           | 7         | 0.87%   |
| Sierra Wireless                   | 6         | 0.74%   |
| Qualcomm Atheros Communications   | 6         | 0.74%   |
| Dell                              | 6         | 0.74%   |
| Ralink Technology                 | 5         | 0.62%   |
| Qualcomm                          | 5         | 0.62%   |
| Microsoft                         | 5         | 0.62%   |
| FIBOCOM                           | 4         | 0.5%    |
| Broadcom Limited                  | 4         | 0.5%    |
| Ralink                            | 3         | 0.37%   |
| D-Link System                     | 3         | 0.37%   |
| D-Link                            | 3         | 0.37%   |
| NetGear                           | 2         | 0.25%   |
| Ericsson Business Mobile Networks | 2         | 0.25%   |
| Texas Instruments                 | 1         | 0.12%   |
| Quectel Wireless Solutions        | 1         | 0.12%   |
| BUFFALO                           | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 124       | 15.33%  |
| Intel Wireless 8265 / 8275                                              | 52        | 6.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 41        | 5.07%   |
| Intel Wi-Fi 6 AX201                                                     | 23        | 2.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 22        | 2.72%   |
| Intel Wireless 8260                                                     | 22        | 2.72%   |
| Intel Wireless 7265                                                     | 21        | 2.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 20        | 2.47%   |
| Intel Wireless-AC 9260                                                  | 19        | 2.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 18        | 2.22%   |
| Intel Wireless 7260                                                     | 18        | 2.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 18        | 2.22%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 18        | 2.22%   |
| Intel Wireless 3165                                                     | 14        | 1.73%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 14        | 1.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 1.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 13        | 1.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 13        | 1.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 13        | 1.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 1.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 11        | 1.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 1.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 1.36%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 10        | 1.24%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 9         | 1.11%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 9         | 1.11%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 9         | 1.11%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 8         | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 0.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 0.87%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.87%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 7         | 0.87%   |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                      | 6         | 0.74%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.62%   |
| Qualcomm Atheros AR9271 802.11n                                         | 5         | 0.62%   |
| Intel Wireless 3160                                                     | 5         | 0.62%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 0.62%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 5         | 0.62%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 5         | 0.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 489       | 45.36%  |
| Intel                            | 404       | 37.48%  |
| Qualcomm Atheros                 | 36        | 3.34%   |
| Broadcom                         | 30        | 2.78%   |
| Aquantia                         | 17        | 1.58%   |
| Marvell Technology Group         | 16        | 1.48%   |
| Nvidia                           | 15        | 1.39%   |
| ASIX Electronics                 | 15        | 1.39%   |
| Lenovo                           | 12        | 1.11%   |
| Apple                            | 10        | 0.93%   |
| Standard Microsystems            | 3         | 0.28%   |
| Samsung Electronics              | 3         | 0.28%   |
| Microchip Technology             | 3         | 0.28%   |
| Broadcom Limited                 | 3         | 0.28%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.19%   |
| Xiaomi                           | 2         | 0.19%   |
| QLogic                           | 2         | 0.19%   |
| Google                           | 2         | 0.19%   |
| DisplayLink                      | 2         | 0.19%   |
| 3Com                             | 2         | 0.19%   |
| TP-Link                          | 1         | 0.09%   |
| Silicon Integrated Systems [SiS] | 1         | 0.09%   |
| NetXen Incorporated              | 1         | 0.09%   |
| MediaTek                         | 1         | 0.09%   |
| JMicron Technology               | 1         | 0.09%   |
| ICS Advent                       | 1         | 0.09%   |
| Huawei Technologies              | 1         | 0.09%   |
| Davicom Semiconductor            | 1         | 0.09%   |
| D-Link System                    | 1         | 0.09%   |
| American Megatrends              | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 390       | 34.3%   |
| Intel I211 Gigabit Network Connection                             | 94        | 8.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 41        | 3.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 35        | 3.08%   |
| Intel I210 Gigabit Network Connection                             | 30        | 2.64%   |
| Intel Ethernet Connection (2) I219-V                              | 27        | 2.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25        | 2.2%    |
| Intel Ethernet Controller I225-V                                  | 23        | 2.02%   |
| Intel 82574L Gigabit Network Connection                           | 23        | 2.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 1.93%   |
| Intel Ethernet Connection (2) I219-LM                             | 21        | 1.85%   |
| Intel Ethernet Connection (7) I219-V                              | 19        | 1.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 16        | 1.41%   |
| Intel Ethernet Connection (2) I218-V                              | 12        | 1.06%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 11        | 0.97%   |
| Intel Ethernet Connection (4) I219-V                              | 11        | 0.97%   |
| Intel I350 Gigabit Network Connection                             | 10        | 0.88%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 0.88%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                             | 9         | 0.79%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 9         | 0.79%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.62%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 7         | 0.62%   |
| Intel 82579V Gigabit Network Connection                           | 7         | 0.62%   |
| Nvidia MCP77 Ethernet                                             | 6         | 0.53%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                   | 6         | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 0.44%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 0.44%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.44%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 5         | 0.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 4         | 0.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.35%   |
| Nvidia MCP79 Ethernet                                             | 4         | 0.35%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 4         | 0.35%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 4         | 0.35%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 4         | 0.35%   |
| Lenovo USB-C Dock Ethernet                                        | 4         | 0.35%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 4         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 989       | 55.41%  |
| WiFi     | 763       | 42.75%  |
| Modem    | 32        | 1.79%   |
| Unknown  | 1         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 654       | 55%     |
| WiFi     | 535       | 45%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 563       | 48.91%  |
| 1     | 470       | 40.83%  |
| 3     | 61        | 5.3%    |
| 0     | 24        | 2.09%   |
| 4     | 18        | 1.56%   |
| 5     | 6         | 0.52%   |
| 6     | 5         | 0.43%   |
| 8     | 2         | 0.17%   |
| 12    | 1         | 0.09%   |
| 9     | 1         | 0.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1015      | 86.75%  |
| Yes  | 155       | 13.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 444       | 62.01%  |
| Realtek Semiconductor           | 54        | 7.54%   |
| Cambridge Silicon Radio         | 48        | 6.7%    |
| Apple                           | 27        | 3.77%   |
| Qualcomm Atheros Communications | 23        | 3.21%   |
| Broadcom                        | 18        | 2.51%   |
| ASUSTek Computer                | 18        | 2.51%   |
| Lite-On Technology              | 17        | 2.37%   |
| Foxconn / Hon Hai               | 15        | 2.09%   |
| IMC Networks                    | 14        | 1.96%   |
| Realtek                         | 7         | 0.98%   |
| Dell                            | 7         | 0.98%   |
| Toshiba                         | 5         | 0.7%    |
| Hewlett-Packard                 | 4         | 0.56%   |
| MediaTek                        | 2         | 0.28%   |
| HTC (High Tech Computer)        | 2         | 0.28%   |
| Foxconn International           | 2         | 0.28%   |
| Belkin Components               | 2         | 0.28%   |
| USI                             | 1         | 0.14%   |
| Ralink Technology               | 1         | 0.14%   |
| Opticis                         | 1         | 0.14%   |
| Edimax Technology               | 1         | 0.14%   |
| Dynex                           | 1         | 0.14%   |
| Chicony Electronics             | 1         | 0.14%   |
| Askey Computer                  | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 127       | 17.74%  |
| Intel AX200 Bluetooth                               | 125       | 17.46%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 70        | 9.78%   |
| Intel AX201 Bluetooth                               | 67        | 9.36%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 48        | 6.7%    |
| Realtek Bluetooth Radio                             | 31        | 4.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 19        | 2.65%   |
| Intel AX210 Bluetooth                               | 14        | 1.96%   |
| Realtek  Bluetooth 4.2 Adapter                      | 13        | 1.82%   |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 1.68%   |
| Apple Bluetooth Host Controller                     | 10        | 1.4%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 9         | 1.26%   |
| Foxconn / Hon Hai Bluetooth Device                  | 8         | 1.12%   |
| Realtek Bluetooth Radio                             | 7         | 0.98%   |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 0.98%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.98%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 6         | 0.84%   |
| IMC Networks Wireless_Device                        | 6         | 0.84%   |
| Apple Bluetooth USB Host Controller                 | 6         | 0.84%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 5         | 0.7%    |
| Realtek RTL8723B Bluetooth                          | 5         | 0.7%    |
| Lite-On Bluetooth Device                            | 5         | 0.7%    |
| Intel Bluetooth Device                              | 5         | 0.7%    |
| IMC Networks Bluetooth Radio                        | 5         | 0.7%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 5         | 0.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 0.56%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 0.56%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 0.56%   |
| Apple Bluetooth HCI                                 | 4         | 0.56%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 3         | 0.42%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.42%   |
| IMC Networks Bluetooth Device                       | 3         | 0.42%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.42%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.42%   |
| Dell BCM20702A0 Bluetooth Module                    | 3         | 0.42%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 0.42%   |
| Toshiba RT Bluetooth Radio                          | 2         | 0.28%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 2         | 0.28%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.28%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 637       | 36.67%  |
| AMD                                  | 455       | 26.19%  |
| Nvidia                               | 343       | 19.75%  |
| C-Media Electronics                  | 43        | 2.48%   |
| Logitech                             | 22        | 1.27%   |
| Creative Labs                        | 16        | 0.92%   |
| Realtek Semiconductor                | 13        | 0.75%   |
| Creative Technology                  | 13        | 0.75%   |
| Lenovo                               | 12        | 0.69%   |
| SteelSeries ApS                      | 11        | 0.63%   |
| Texas Instruments                    | 10        | 0.58%   |
| Razer USA                            | 8         | 0.46%   |
| Plantronics                          | 8         | 0.46%   |
| JMTek                                | 8         | 0.46%   |
| Kingston Technology                  | 7         | 0.4%    |
| GYROCOM C&C                          | 7         | 0.4%    |
| Focusrite-Novation                   | 7         | 0.4%    |
| Blue Microphones                     | 7         | 0.4%    |
| Thesycon Systemsoftware & Consulting | 6         | 0.35%   |
| AudioQuest                           | 6         | 0.35%   |
| ASUSTek Computer                     | 6         | 0.35%   |
| RODE Microphones                     | 5         | 0.29%   |
| Dell                                 | 5         | 0.29%   |
| BEHRINGER International              | 5         | 0.29%   |
| Samson Technologies                  | 4         | 0.23%   |
| GN Netcom                            | 4         | 0.23%   |
| Corsair                              | 4         | 0.23%   |
| SAVITECH                             | 3         | 0.17%   |
| Generalplus Technology               | 3         | 0.17%   |
| FiiO Electronics Technology          | 3         | 0.17%   |
| Yamaha                               | 2         | 0.12%   |
| Sony                                 | 2         | 0.12%   |
| Silicon Integrated Systems [SiS]     | 2         | 0.12%   |
| Sennheiser Communications            | 2         | 0.12%   |
| No brand                             | 2         | 0.12%   |
| Nektar                               | 2         | 0.12%   |
| Native Instruments                   | 2         | 0.12%   |
| Microsoft                            | 2         | 0.12%   |
| Hewlett-Packard                      | 2         | 0.12%   |
| DSEA A/S                             | 2         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 133       | 6.34%   |
| AMD Starship/Matisse HD Audio Controller                                   | 120       | 5.72%   |
| Intel Cannon Lake PCH cAVS                                                 | 81        | 3.86%   |
| Intel Sunrise Point-LP HD Audio                                            | 79        | 3.77%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 76        | 3.62%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 76        | 3.62%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 70        | 3.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 49        | 2.34%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 37        | 1.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 36        | 1.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 34        | 1.62%   |
| AMD Navi 10 HDMI Audio                                                     | 34        | 1.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 30        | 1.43%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 29        | 1.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 28        | 1.34%   |
| Nvidia GP106 High Definition Audio Controller                              | 28        | 1.34%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 28        | 1.34%   |
| Nvidia TU106 High Definition Audio Controller                              | 26        | 1.24%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 26        | 1.24%   |
| Nvidia GP107GL High Definition Audio Controller                            | 25        | 1.19%   |
| Nvidia GP104 High Definition Audio Controller                              | 24        | 1.14%   |
| Intel Comet Lake PCH cAVS                                                  | 23        | 1.1%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 23        | 1.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 22        | 1.05%   |
| Nvidia TU104 HD Audio Controller                                           | 21        | 1%      |
| Intel Tiger Lake-H HD Audio Controller                                     | 21        | 1%      |
| Intel Comet Lake PCH-LP cAVS                                               | 20        | 0.95%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 20        | 0.95%   |
| Nvidia TU116 High Definition Audio Controller                              | 19        | 0.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 18        | 0.86%   |
| Intel CM238 HD Audio Controller                                            | 18        | 0.86%   |
| Intel Haswell-ULT HD Audio Controller                                      | 17        | 0.81%   |
| Intel 8 Series HD Audio Controller                                         | 17        | 0.81%   |
| Nvidia GM206 High Definition Audio Controller                              | 16        | 0.76%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 16        | 0.76%   |
| Intel 200 Series PCH HD Audio                                              | 16        | 0.76%   |
| AMD FCH Azalia Controller                                                  | 16        | 0.76%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 15        | 0.72%   |
| Nvidia GM204 High Definition Audio Controller                              | 14        | 0.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 14        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 245       | 20.3%   |
| Kingston                     | 166       | 13.75%  |
| SK hynix                     | 162       | 13.42%  |
| Micron Technology            | 107       | 8.86%   |
| Unknown                      | 106       | 8.78%   |
| Corsair                      | 104       | 8.62%   |
| Crucial                      | 95        | 7.87%   |
| G.Skill                      | 94        | 7.79%   |
| Ramaxel Technology           | 18        | 1.49%   |
| A-DATA Technology            | 13        | 1.08%   |
| Team                         | 12        | 0.99%   |
| Patriot                      | 12        | 0.99%   |
| Transcend                    | 9         | 0.75%   |
| Goodram                      | 8         | 0.66%   |
| Elpida                       | 8         | 0.66%   |
| Nanya Technology             | 7         | 0.58%   |
| Unknown                      | 6         | 0.5%    |
| Unknown (ABCD)               | 3         | 0.25%   |
| AMD                          | 3         | 0.25%   |
| Toshiba                      | 2         | 0.17%   |
| Timetec                      | 2         | 0.17%   |
| Avant                        | 2         | 0.17%   |
| Unknown (0x5D00000000000000) | 1         | 0.08%   |
| Thermaltake                  | 1         | 0.08%   |
| Teikon                       | 1         | 0.08%   |
| T-FORCE                      | 1         | 0.08%   |
| Saikano                      | 1         | 0.08%   |
| Qimonda                      | 1         | 0.08%   |
| PUSKILL                      | 1         | 0.08%   |
| Patriot Memory (PDP Systems) | 1         | 0.08%   |
| Patriot Memory               | 1         | 0.08%   |
| Magnum Tech                  | 1         | 0.08%   |
| Kllisre                      | 1         | 0.08%   |
| KLEVV                        | 1         | 0.08%   |
| Kimtigo                      | 1         | 0.08%   |
| Innodisk                     | 1         | 0.08%   |
| Hewlett-Packard              | 1         | 0.08%   |
| Goldkey                      | 1         | 0.08%   |
| Golden Empire                | 1         | 0.08%   |
| GeIL                         | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s   | 11        | 0.86%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 11        | 0.86%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s      | 11        | 0.86%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s       | 10        | 0.78%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 9         | 0.7%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 9         | 0.7%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 9         | 0.7%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 9         | 0.7%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 8         | 0.62%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 8         | 0.62%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 8         | 0.62%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 8         | 0.62%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s        | 8         | 0.62%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 7         | 0.54%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s     | 7         | 0.54%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s      | 7         | 0.54%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s      | 7         | 0.54%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 7         | 0.54%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 7         | 0.54%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s      | 7         | 0.54%   |
| Unknown RAM Module 1GB SODIMM DDR                           | 6         | 0.47%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 6         | 0.47%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s      | 6         | 0.47%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s   | 6         | 0.47%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s    | 6         | 0.47%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 6         | 0.47%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s         | 6         | 0.47%   |
| Unknown                                                     | 6         | 0.47%   |
| Unknown RAM Module 1024MB DIMM SDRAM                        | 5         | 0.39%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 5         | 0.39%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s      | 5         | 0.39%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 5         | 0.39%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s       | 5         | 0.39%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s       | 5         | 0.39%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s       | 5         | 0.39%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s           | 5         | 0.39%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s      | 5         | 0.39%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s          | 5         | 0.39%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s       | 5         | 0.39%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s   | 4         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 674       | 62.87%  |
| DDR3    | 244       | 22.76%  |
| DDR2    | 40        | 3.73%   |
| LPDDR4  | 30        | 2.8%    |
| Unknown | 26        | 2.43%   |
| LPDDR3  | 23        | 2.15%   |
| SDRAM   | 17        | 1.59%   |
| DDR     | 11        | 1.03%   |
| DDR5    | 4         | 0.37%   |
| LPDDR5  | 2         | 0.19%   |
| DRAM    | 1         | 0.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 508       | 47.39%  |
| SODIMM       | 497       | 46.36%  |
| Row Of Chips | 60        | 5.6%    |
| Chip         | 6         | 0.56%   |
| RIMM         | 1         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 479       | 41.36%  |
| 16384 | 286       | 24.7%   |
| 4096  | 204       | 17.62%  |
| 2048  | 75        | 6.48%   |
| 32768 | 73        | 6.3%    |
| 1024  | 31        | 2.68%   |
| 512   | 7         | 0.6%    |
| 256   | 3         | 0.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 214       | 18.38%  |
| 2667    | 190       | 16.32%  |
| 1600    | 152       | 13.06%  |
| 2400    | 84        | 7.22%   |
| 2133    | 68        | 5.84%   |
| 3600    | 65        | 5.58%   |
| 1333    | 55        | 4.73%   |
| 667     | 28        | 2.41%   |
| 3000    | 27        | 2.32%   |
| 800     | 26        | 2.23%   |
| 3733    | 23        | 1.98%   |
| Unknown | 22        | 1.89%   |
| 3400    | 19        | 1.63%   |
| 1867    | 18        | 1.55%   |
| 4267    | 17        | 1.46%   |
| 2933    | 16        | 1.37%   |
| 3466    | 15        | 1.29%   |
| 1334    | 12        | 1.03%   |
| 2666    | 10        | 0.86%   |
| 3266    | 9         | 0.77%   |
| 1066    | 9         | 0.77%   |
| 8400    | 8         | 0.69%   |
| 4800    | 7         | 0.6%    |
| 1067    | 7         | 0.6%    |
| 1866    | 6         | 0.52%   |
| 3800    | 5         | 0.43%   |
| 4000    | 4         | 0.34%   |
| 400     | 4         | 0.34%   |
| 4266    | 3         | 0.26%   |
| 3333    | 3         | 0.26%   |
| 3100    | 3         | 0.26%   |
| 3066    | 3         | 0.26%   |
| 2048    | 3         | 0.26%   |
| 533     | 3         | 0.26%   |
| 6400    | 2         | 0.17%   |
| 3866    | 2         | 0.17%   |
| 3666    | 2         | 0.17%   |
| 3334    | 2         | 0.17%   |
| 2800    | 2         | 0.17%   |
| 2465    | 2         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 9         | 39.13%  |
| Seiko Epson           | 3         | 13.04%  |
| Samsung Electronics   | 3         | 13.04%  |
| Canon                 | 3         | 13.04%  |
| Brother Industries    | 2         | 8.7%    |
| Xiaomi                | 1         | 4.35%   |
| Lexmark International | 1         | 4.35%   |
| Konica Minolta        | 1         | 4.35%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Canon LiDE 400                        | 2         | 8.7%    |
| Xiaomi MiMouse 2                      | 1         | 4.35%   |
| Seiko Epson WF-3520 Series            | 1         | 4.35%   |
| Seiko Epson WF-2510 Series            | 1         | 4.35%   |
| Seiko Epson AL-M310DN                 | 1         | 4.35%   |
| Samsung ML-191x/ML-252x Laser Printer | 1         | 4.35%   |
| Samsung CLP-325 Color Laser Printer   | 1         | 4.35%   |
| Samsung C460 Series                   | 1         | 4.35%   |
| Lexmark International Lexmark E352dn  | 1         | 4.35%   |
| Konica Minolta magicolor 1680MF scan  | 1         | 4.35%   |
| HP PhotoSmart 130                     | 1         | 4.35%   |
| HP LaserJet M14-M17                   | 1         | 4.35%   |
| HP LaserJet 1020                      | 1         | 4.35%   |
| HP LaserJet 1018                      | 1         | 4.35%   |
| HP LaserJet 1010                      | 1         | 4.35%   |
| HP Deskjet D1500 series               | 1         | 4.35%   |
| HP DeskJet 5440                       | 1         | 4.35%   |
| HP DeskJet 3630 series                | 1         | 4.35%   |
| HP Deskjet 2050 J510                  | 1         | 4.35%   |
| Canon LiDE 300                        | 1         | 4.35%   |
| Brother MFC-L2700DW                   | 1         | 4.35%   |
| Brother MFC-9130CW                    | 1         | 4.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 5         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 2         | 40%     |
| Canon CanoScan LiDE 600F      | 1         | 20%     |
| Canon CanoScan LiDE 220       | 1         | 20%     |
| Canon CanoScan LiDE 110       | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 132       | 21.36%  |
| Logitech                               | 83        | 13.43%  |
| IMC Networks                           | 67        | 10.84%  |
| Microdia                               | 51        | 8.25%   |
| Realtek Semiconductor                  | 43        | 6.96%   |
| Acer                                   | 40        | 6.47%   |
| Sunplus Innovation Technology          | 31        | 5.02%   |
| Quanta                                 | 23        | 3.72%   |
| Cheng Uei Precision Industry (Foxlink) | 20        | 3.24%   |
| Lite-On Technology                     | 19        | 3.07%   |
| Syntek                                 | 14        | 2.27%   |
| Apple                                  | 13        | 2.1%    |
| Samsung Electronics                    | 9         | 1.46%   |
| Luxvisions Innotech Limited            | 9         | 1.46%   |
| Z-Star Microelectronics                | 8         | 1.29%   |
| DigiTech                               | 4         | 0.65%   |
| Microsoft                              | 3         | 0.49%   |
| MacroSilicon                           | 3         | 0.49%   |
| Creative Technology                    | 3         | 0.49%   |
| ARC International                      | 3         | 0.49%   |
| Unknown                                | 2         | 0.32%   |
| Suyin                                  | 2         | 0.32%   |
| Silicon Motion                         | 2         | 0.32%   |
| Razer USA                              | 2         | 0.32%   |
| LG Electronics                         | 2         | 0.32%   |
| KYE Systems (Mouse Systems)            | 2         | 0.32%   |
| Cubeternet                             | 2         | 0.32%   |
| AVerMedia Technologies                 | 2         | 0.32%   |
| Alcor Micro                            | 2         | 0.32%   |
| YGTek                                  | 1         | 0.16%   |
| Xiaomi                                 | 1         | 0.16%   |
| Valve Software                         | 1         | 0.16%   |
| USB3.0 HD Audio Capture                | 1         | 0.16%   |
| SunplusIT                              | 1         | 0.16%   |
| Sonix Technology                       | 1         | 0.16%   |
| SiGma Micro                            | 1         | 0.16%   |
| ShineTech                              | 1         | 0.16%   |
| Ruision                                | 1         | 0.16%   |
| Ricoh                                  | 1         | 0.16%   |
| Omnivision                             | 1         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 40        | 6.37%   |
| IMC Networks Integrated Camera                                 | 32        | 5.1%    |
| Microdia Integrated_Webcam_HD                                  | 29        | 4.62%   |
| Logitech HD Pro Webcam C920                                    | 22        | 3.5%    |
| Realtek Integrated_Webcam_HD                                   | 18        | 2.87%   |
| Acer Integrated Camera                                         | 18        | 2.87%   |
| Logitech Webcam C270                                           | 14        | 2.23%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 14        | 2.23%   |
| Chicony HD Webcam                                              | 14        | 2.23%   |
| Sunplus Integrated_Webcam_HD                                   | 10        | 1.59%   |
| Syntek Integrated Camera                                       | 9         | 1.43%   |
| Samsung Galaxy A5 (MTP)                                        | 9         | 1.43%   |
| Chicony HP HD Camera                                           | 9         | 1.43%   |
| Lite-On Integrated Camera                                      | 8         | 1.27%   |
| Logitech Webcam C310                                           | 7         | 1.11%   |
| Realtek Integrated Webcam HD                                   | 6         | 0.96%   |
| Quanta HP Wide Vision HD Camera                                | 6         | 0.96%   |
| Chicony USB2.0 Camera                                          | 6         | 0.96%   |
| Sunplus HD WebCam                                              | 5         | 0.8%    |
| Logitech C922 Pro Stream Webcam                                | 5         | 0.8%    |
| Logitech BRIO Ultra HD Webcam                                  | 5         | 0.8%    |
| Chicony Integrated Camera (1280x720@30)                        | 5         | 0.8%    |
| Chicony HD User Facing                                         | 5         | 0.8%    |
| Z-Star Venus USB2.0 Camera                                     | 4         | 0.64%   |
| Sunplus HP Wide Vision HD                                      | 4         | 0.64%   |
| Microdia Integrated Webcam                                     | 4         | 0.64%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 4         | 0.64%   |
| Lite-On TOSHIBA Web Camera - HD                                | 4         | 0.64%   |
| IMC Networks USB2.0 HD IR UVC WebCam                           | 4         | 0.64%   |
| IMC Networks ov9734_azurewave_camera                           | 4         | 0.64%   |
| Chicony ThinkPad T490 Webcam                                   | 4         | 0.64%   |
| Chicony Lenovo EasyCamera                                      | 4         | 0.64%   |
| Chicony EasyCamera                                             | 4         | 0.64%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 4         | 0.64%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 4         | 0.64%   |
| Apple FaceTime HD Camera                                       | 4         | 0.64%   |
| Acer SunplusIT Integrated Camera                               | 4         | 0.64%   |
| Acer BisonCam, NB Pro                                          | 4         | 0.64%   |
| Syntek Lenovo EasyCamera                                       | 3         | 0.48%   |
| Realtek USB2.0 HD UVC WebCam                                   | 3         | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 57        | 47.11%  |
| Validity Sensors           | 27        | 22.31%  |
| Shenzhen Goodix Technology | 17        | 14.05%  |
| Elan Microelectronics      | 7         | 5.79%   |
| AuthenTec                  | 4         | 3.31%   |
| STMicroelectronics         | 3         | 2.48%   |
| LighTuning Technology      | 2         | 1.65%   |
| DigitalPersona             | 2         | 1.65%   |
| Upek                       | 1         | 0.83%   |
| Samsung Electronics        | 1         | 0.83%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 23        | 19.01%  |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 15        | 12.4%   |
| Unknown                                                    | 11        | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 6         | 4.96%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 6         | 4.96%   |
| Shenzhen Goodix  Fingerprint Device                        | 6         | 4.96%   |
| Shenzhen Goodix Fingerprint Reader                         | 6         | 4.96%   |
| Elan ELAN:Fingerprint                                      | 6         | 4.96%   |
| Validity Sensors Synaptics WBDI                            | 5         | 4.13%   |
| Shenzhen Goodix FingerPrint                                | 5         | 4.13%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 3         | 2.48%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 2.48%   |
| STMicroelectronics Fingerprint Reader                      | 3         | 2.48%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor          | 2         | 1.65%   |
| Validity Sensors Fingerprint scanner                       | 2         | 1.65%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 2         | 1.65%   |
| DigitalPersona Fingerprint Reader                          | 2         | 1.65%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 2         | 1.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 0.83%   |
| Validity Sensors VFS491                                    | 1         | 0.83%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 0.83%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 1         | 0.83%   |
| Synaptics WBDI Device                                      | 1         | 0.83%   |
| Synaptics  WBDI                                            | 1         | 0.83%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 0.83%   |
| Samsung Fingerprint Sensor Device - 730B                   | 1         | 0.83%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 0.83%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 0.83%   |
| Elan ELAN:ARM-M4                                           | 1         | 0.83%   |
| AuthenTec Fingerprint Sensor                               | 1         | 0.83%   |
| AuthenTec AES2550 Fingerprint Sensor                       | 1         | 0.83%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 34        | 39.08%  |
| Broadcom                          | 29        | 33.33%  |
| Upek                              | 4         | 4.6%    |
| Clay Logic                        | 4         | 4.6%    |
| O2 Micro                          | 3         | 3.45%   |
| Yubico.com                        | 2         | 2.3%    |
| Gemalto (was Gemplus)             | 2         | 2.3%    |
| VASCO Data Security International | 1         | 1.15%   |
| SCM Microsystems                  | 1         | 1.15%   |
| Purism, SPC                       | 1         | 1.15%   |
| Microchip Technology              | 1         | 1.15%   |
| Hewlett-Packard                   | 1         | 1.15%   |
| Feitian Technologies              | 1         | 1.15%   |
| Aladdin Knowledge Systems         | 1         | 1.15%   |
| Aktiv                             | 1         | 1.15%   |
| Advanced Card Systems             | 1         | 1.15%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 34        | 39.08%  |
| Broadcom 5880                                                                | 10        | 11.49%  |
| Broadcom 58200                                                               | 9         | 10.34%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 6.9%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 4.6%    |
| Clay Logic Nitrokey Pro                                                      | 4         | 4.6%    |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 4.6%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 2.3%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 2.3%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 2.3%    |
| VASCO Data Security International DIGIPASS 870                               | 1         | 1.15%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 1.15%   |
| Purism, SPC Librem Key                                                       | 1         | 1.15%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.15%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 1.15%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 1.15%   |
| Feitian Technologies U2F CCID KB                                             | 1         | 1.15%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.15%   |
| Aktiv Rutoken lite                                                           | 1         | 1.15%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 1.15%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 549       | 43.81%  |
| 1     | 346       | 27.61%  |
| 2     | 172       | 13.73%  |
| 3     | 95        | 7.58%   |
| 4     | 53        | 4.23%   |
| 5     | 23        | 1.84%   |
| 6     | 10        | 0.8%    |
| 7     | 4         | 0.32%   |
| 8     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 242       | 18.95%  |
| Graphics card            | 162       | 12.69%  |
| Bluetooth                | 154       | 12.06%  |
| Camera                   | 134       | 10.49%  |
| Fingerprint reader       | 120       | 9.4%    |
| Net/wireless             | 83        | 6.5%    |
| Chipcard                 | 66        | 5.17%   |
| Card reader              | 63        | 4.93%   |
| Sound                    | 56        | 4.39%   |
| Multimedia controller    | 56        | 4.39%   |
| Firewire controller      | 25        | 1.96%   |
| Network                  | 19        | 1.49%   |
| Net/ethernet             | 18        | 1.41%   |
| Unassigned class         | 15        | 1.17%   |
| Modem                    | 15        | 1.17%   |
| Storage/ide              | 13        | 1.02%   |
| Storage/ata              | 11        | 0.86%   |
| Storage/raid             | 6         | 0.47%   |
| Storage                  | 6         | 0.47%   |
| Tv card                  | 5         | 0.39%   |
| Dvb card                 | 4         | 0.31%   |
| Storage/nvme             | 2         | 0.16%   |
| Wireless                 | 1         | 0.08%   |
| Unclassified device      | 1         | 0.08%   |

