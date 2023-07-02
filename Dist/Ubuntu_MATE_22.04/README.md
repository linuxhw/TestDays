Ubuntu MATE 22.04 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_MATE_22.04/Desktop/README.md) and [notebooks](/Dist/Ubuntu_MATE_22.04/Notebook/README.md).

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

Total: 481

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | B85M-D3H                    | Desktop     | [99b07ae636](https://linux-hardware.org/?probe=99b07ae636) | Jun 30, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [498eb9b539](https://linux-hardware.org/?probe=498eb9b539) | Jun 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [136060092c](https://linux-hardware.org/?probe=136060092c) | Jun 30, 2023 |
| Lenovo        | ThinkPad T580 20LAS0DL00    | Notebook    | [5d27a44710](https://linux-hardware.org/?probe=5d27a44710) | Jun 28, 2023 |
| HP            | Pavilion 17                 | Notebook    | [01c3ae7698](https://linux-hardware.org/?probe=01c3ae7698) | Jun 28, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [235e541e2d](https://linux-hardware.org/?probe=235e541e2d) | Jun 28, 2023 |
| Acer          | Extensa 2519                | Notebook    | [1a8a4ee11e](https://linux-hardware.org/?probe=1a8a4ee11e) | Jun 27, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [47a0ae93f4](https://linux-hardware.org/?probe=47a0ae93f4) | Jun 25, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [1fe939429c](https://linux-hardware.org/?probe=1fe939429c) | Jun 24, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [ddc5e387cb](https://linux-hardware.org/?probe=ddc5e387cb) | Jun 24, 2023 |
| ASUSTek       | P7P55 LX                    | Desktop     | [e700828afa](https://linux-hardware.org/?probe=e700828afa) | Jun 23, 2023 |
| ASUSTek       | P7P55 LX                    | Desktop     | [cd9b9aae75](https://linux-hardware.org/?probe=cd9b9aae75) | Jun 23, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [033c027010](https://linux-hardware.org/?probe=033c027010) | Jun 18, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [ac006b8cb7](https://linux-hardware.org/?probe=ac006b8cb7) | Jun 18, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [fe0d892e82](https://linux-hardware.org/?probe=fe0d892e82) | Jun 16, 2023 |
| HP            | 625 (WT144EA#ABD)           | Notebook    | [352eaf6ce7](https://linux-hardware.org/?probe=352eaf6ce7) | Jun 11, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [db301ecd59](https://linux-hardware.org/?probe=db301ecd59) | Jun 11, 2023 |
| HP            | 625 (WT144EA#ABD)           | Notebook    | [673ab1f0a9](https://linux-hardware.org/?probe=673ab1f0a9) | Jun 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c610b3b9fe](https://linux-hardware.org/?probe=c610b3b9fe) | Jun 10, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [88d3849db5](https://linux-hardware.org/?probe=88d3849db5) | Jun 10, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [befd126f43](https://linux-hardware.org/?probe=befd126f43) | Jun 07, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [e146923f12](https://linux-hardware.org/?probe=e146923f12) | Jun 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [0f91c977f0](https://linux-hardware.org/?probe=0f91c977f0) | Jun 06, 2023 |
| HP            | 1998                        | Desktop     | [c6183bd564](https://linux-hardware.org/?probe=c6183bd564) | Jun 05, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ce1569ee48](https://linux-hardware.org/?probe=ce1569ee48) | Jun 05, 2023 |
| Dell          | Latitude E5540              | Notebook    | [d2bde0e098](https://linux-hardware.org/?probe=d2bde0e098) | Jun 04, 2023 |
| Dell          | Latitude E5540              | Notebook    | [f9483c219e](https://linux-hardware.org/?probe=f9483c219e) | Jun 04, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [0bd595e07a](https://linux-hardware.org/?probe=0bd595e07a) | Jun 04, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [908f094e9d](https://linux-hardware.org/?probe=908f094e9d) | Jun 02, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [f9c0a669c5](https://linux-hardware.org/?probe=f9c0a669c5) | Jun 02, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [c6ee1e5e32](https://linux-hardware.org/?probe=c6ee1e5e32) | Jun 02, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [46f5148174](https://linux-hardware.org/?probe=46f5148174) | Jun 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [dab4e98680](https://linux-hardware.org/?probe=dab4e98680) | May 31, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [643710864a](https://linux-hardware.org/?probe=643710864a) | May 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c0ec67e3b1](https://linux-hardware.org/?probe=c0ec67e3b1) | May 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [f46b9b1b6a](https://linux-hardware.org/?probe=f46b9b1b6a) | May 29, 2023 |
| Unknown       | HX90                        | Desktop     | [d38fff55af](https://linux-hardware.org/?probe=d38fff55af) | May 28, 2023 |
| Sony          | SVF13N2J2ES                 | Notebook    | [978ae98d6e](https://linux-hardware.org/?probe=978ae98d6e) | May 24, 2023 |
| Sony          | SVF13N2J2ES                 | Notebook    | [01e2285654](https://linux-hardware.org/?probe=01e2285654) | May 24, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1ff1bde0f0](https://linux-hardware.org/?probe=1ff1bde0f0) | May 23, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [98473b6b1e](https://linux-hardware.org/?probe=98473b6b1e) | May 22, 2023 |
| HP            | Pavilion dv6                | Notebook    | [1b931dc36f](https://linux-hardware.org/?probe=1b931dc36f) | May 17, 2023 |
| Dell          | Latitude E7270              | Notebook    | [c3b39e55f4](https://linux-hardware.org/?probe=c3b39e55f4) | May 17, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [7feff56d1d](https://linux-hardware.org/?probe=7feff56d1d) | May 15, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [41c5120619](https://linux-hardware.org/?probe=41c5120619) | May 14, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b14b7c3725](https://linux-hardware.org/?probe=b14b7c3725) | May 13, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [9759b380bb](https://linux-hardware.org/?probe=9759b380bb) | May 13, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [67122d7cd6](https://linux-hardware.org/?probe=67122d7cd6) | May 12, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9c8ffba5f4](https://linux-hardware.org/?probe=9c8ffba5f4) | May 12, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [af88b26379](https://linux-hardware.org/?probe=af88b26379) | May 09, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [9e877e8df9](https://linux-hardware.org/?probe=9e877e8df9) | May 08, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [11a41c975d](https://linux-hardware.org/?probe=11a41c975d) | May 07, 2023 |
| Dell          | Vostro 14-3468              | Notebook    | [0a096de0e1](https://linux-hardware.org/?probe=0a096de0e1) | May 06, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b6ec076cc6](https://linux-hardware.org/?probe=b6ec076cc6) | May 05, 2023 |
| Acer          | Aspire X1430                | Desktop     | [4bdb74f57e](https://linux-hardware.org/?probe=4bdb74f57e) | May 04, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [f9c27ab898](https://linux-hardware.org/?probe=f9c27ab898) | May 02, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b7ff999133](https://linux-hardware.org/?probe=b7ff999133) | May 02, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c56afa707e](https://linux-hardware.org/?probe=c56afa707e) | May 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [99a39f6696](https://linux-hardware.org/?probe=99a39f6696) | May 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [66a3f8bc3a](https://linux-hardware.org/?probe=66a3f8bc3a) | May 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [193fb3ba91](https://linux-hardware.org/?probe=193fb3ba91) | Apr 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [5fd8f6db6e](https://linux-hardware.org/?probe=5fd8f6db6e) | Apr 30, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [2fe28d7f43](https://linux-hardware.org/?probe=2fe28d7f43) | Apr 29, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [ef3f4d1ac1](https://linux-hardware.org/?probe=ef3f4d1ac1) | Apr 29, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [c0c226bf8c](https://linux-hardware.org/?probe=c0c226bf8c) | Apr 28, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [2306f31aa2](https://linux-hardware.org/?probe=2306f31aa2) | Apr 27, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a660a768ce](https://linux-hardware.org/?probe=a660a768ce) | Apr 26, 2023 |
| Gigabyte      | P55-UD3                     | Desktop     | [cb8885f205](https://linux-hardware.org/?probe=cb8885f205) | Apr 25, 2023 |
| Gigabyte      | P55-UD3                     | Desktop     | [cacc141f4f](https://linux-hardware.org/?probe=cacc141f4f) | Apr 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C6S... | Notebook    | [554f32b909](https://linux-hardware.org/?probe=554f32b909) | Apr 25, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [88a6d9040e](https://linux-hardware.org/?probe=88a6d9040e) | Apr 23, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [b003b5c775](https://linux-hardware.org/?probe=b003b5c775) | Apr 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [90e0cff0ad](https://linux-hardware.org/?probe=90e0cff0ad) | Apr 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [f0353d1327](https://linux-hardware.org/?probe=f0353d1327) | Apr 16, 2023 |
| AMI           | Intel                       | Desktop     | [b7a63bbfc7](https://linux-hardware.org/?probe=b7a63bbfc7) | Apr 15, 2023 |
| AMI           | Intel                       | Desktop     | [ec0a5e657e](https://linux-hardware.org/?probe=ec0a5e657e) | Apr 14, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [7041b36ac5](https://linux-hardware.org/?probe=7041b36ac5) | Apr 14, 2023 |
| Lenovo        | ThinkStation D20 4158GK1    | Desktop     | [44d9536051](https://linux-hardware.org/?probe=44d9536051) | Apr 14, 2023 |
| HP            | 1494                        | Desktop     | [9c5dc1a221](https://linux-hardware.org/?probe=9c5dc1a221) | Apr 13, 2023 |
| Google        | Chell                       | Notebook    | [64cecf4575](https://linux-hardware.org/?probe=64cecf4575) | Apr 12, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [2bb9767ca7](https://linux-hardware.org/?probe=2bb9767ca7) | Apr 10, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [681be67c93](https://linux-hardware.org/?probe=681be67c93) | Apr 09, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [87be7a6dc0](https://linux-hardware.org/?probe=87be7a6dc0) | Apr 09, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [e2c3600e8b](https://linux-hardware.org/?probe=e2c3600e8b) | Apr 07, 2023 |
| HUAWEI        | NDZ-WXX9                    | Notebook    | [707d59612f](https://linux-hardware.org/?probe=707d59612f) | Apr 05, 2023 |
| HUAWEI        | NDZ-WXX9                    | Notebook    | [058290755b](https://linux-hardware.org/?probe=058290755b) | Apr 05, 2023 |
| RCA           | W101AS23T2                  | Tablet      | [21e469a8a9](https://linux-hardware.org/?probe=21e469a8a9) | Apr 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [248ef68079](https://linux-hardware.org/?probe=248ef68079) | Apr 03, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [77187502c9](https://linux-hardware.org/?probe=77187502c9) | Apr 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [207edc0a25](https://linux-hardware.org/?probe=207edc0a25) | Apr 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [14751f18b3](https://linux-hardware.org/?probe=14751f18b3) | Apr 01, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [53a11e07e8](https://linux-hardware.org/?probe=53a11e07e8) | Mar 31, 2023 |
| MSI           | MS-AA5E 0A                  | All in one  | [36d66ad0a2](https://linux-hardware.org/?probe=36d66ad0a2) | Mar 29, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [a074e581b0](https://linux-hardware.org/?probe=a074e581b0) | Mar 28, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [832b434c38](https://linux-hardware.org/?probe=832b434c38) | Mar 28, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [7e283bfa25](https://linux-hardware.org/?probe=7e283bfa25) | Mar 28, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d56f48b9d1](https://linux-hardware.org/?probe=d56f48b9d1) | Mar 27, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [bd4eec08fb](https://linux-hardware.org/?probe=bd4eec08fb) | Mar 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [4cc097dbcf](https://linux-hardware.org/?probe=4cc097dbcf) | Mar 26, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [fb3f1be00d](https://linux-hardware.org/?probe=fb3f1be00d) | Mar 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [5a95cd6ad5](https://linux-hardware.org/?probe=5a95cd6ad5) | Mar 26, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [890cd39d63](https://linux-hardware.org/?probe=890cd39d63) | Mar 26, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [50387b06e7](https://linux-hardware.org/?probe=50387b06e7) | Mar 26, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2a9ae9d859](https://linux-hardware.org/?probe=2a9ae9d859) | Mar 26, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [182b5af958](https://linux-hardware.org/?probe=182b5af958) | Mar 22, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [e46c856c11](https://linux-hardware.org/?probe=e46c856c11) | Mar 22, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [dcae89c3e5](https://linux-hardware.org/?probe=dcae89c3e5) | Mar 21, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [9ff80f0344](https://linux-hardware.org/?probe=9ff80f0344) | Mar 21, 2023 |
| CCE           | NM70-I                      | Desktop     | [3e99b6e12d](https://linux-hardware.org/?probe=3e99b6e12d) | Mar 21, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [e18778e282](https://linux-hardware.org/?probe=e18778e282) | Mar 20, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [bbe02b925a](https://linux-hardware.org/?probe=bbe02b925a) | Mar 19, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [d376f92f8d](https://linux-hardware.org/?probe=d376f92f8d) | Mar 19, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [605bc3d5b0](https://linux-hardware.org/?probe=605bc3d5b0) | Mar 19, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [cd8f53a887](https://linux-hardware.org/?probe=cd8f53a887) | Mar 19, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [45a412e241](https://linux-hardware.org/?probe=45a412e241) | Mar 18, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4cee2dc95e](https://linux-hardware.org/?probe=4cee2dc95e) | Mar 18, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [7298c4b04b](https://linux-hardware.org/?probe=7298c4b04b) | Mar 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [794bc239ab](https://linux-hardware.org/?probe=794bc239ab) | Mar 17, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [105acd2203](https://linux-hardware.org/?probe=105acd2203) | Mar 16, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [526e33e980](https://linux-hardware.org/?probe=526e33e980) | Mar 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [8d2ca6cedc](https://linux-hardware.org/?probe=8d2ca6cedc) | Mar 14, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2f69480899](https://linux-hardware.org/?probe=2f69480899) | Mar 14, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [aa66f39ad6](https://linux-hardware.org/?probe=aa66f39ad6) | Mar 13, 2023 |
| HP            | 339A                        | Desktop     | [fa78907d67](https://linux-hardware.org/?probe=fa78907d67) | Mar 12, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [f9dfd84f86](https://linux-hardware.org/?probe=f9dfd84f86) | Mar 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [406d19d44f](https://linux-hardware.org/?probe=406d19d44f) | Mar 12, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [d5426d5f1e](https://linux-hardware.org/?probe=d5426d5f1e) | Mar 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [729d9395f0](https://linux-hardware.org/?probe=729d9395f0) | Mar 11, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [ee115bdfb8](https://linux-hardware.org/?probe=ee115bdfb8) | Mar 11, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [7a7e8bc855](https://linux-hardware.org/?probe=7a7e8bc855) | Mar 09, 2023 |
| HP            | Presario CQ61               | Notebook    | [0eab7ae44e](https://linux-hardware.org/?probe=0eab7ae44e) | Mar 09, 2023 |
| MSI           | X370 SLI PLUS               | Desktop     | [d2ac8dd020](https://linux-hardware.org/?probe=d2ac8dd020) | Mar 07, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [adce83e80e](https://linux-hardware.org/?probe=adce83e80e) | Mar 07, 2023 |
| HP            | Stream Laptop 11-ah1XX      | Notebook    | [61e3840465](https://linux-hardware.org/?probe=61e3840465) | Mar 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [cb7ac03a2a](https://linux-hardware.org/?probe=cb7ac03a2a) | Mar 07, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9178ffc6f9](https://linux-hardware.org/?probe=9178ffc6f9) | Mar 05, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [48cf9d748f](https://linux-hardware.org/?probe=48cf9d748f) | Mar 05, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [7d1b3a73f9](https://linux-hardware.org/?probe=7d1b3a73f9) | Mar 05, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9f5aaa2900](https://linux-hardware.org/?probe=9f5aaa2900) | Mar 04, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [05934ca860](https://linux-hardware.org/?probe=05934ca860) | Mar 04, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [bd1f7da7bc](https://linux-hardware.org/?probe=bd1f7da7bc) | Mar 03, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [be909f0882](https://linux-hardware.org/?probe=be909f0882) | Mar 03, 2023 |
| Intel         | NUC12EDBi7 M27908-302       | Mini pc     | [bb51e864a7](https://linux-hardware.org/?probe=bb51e864a7) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [0cd2798326](https://linux-hardware.org/?probe=0cd2798326) | Mar 03, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [dbc8fc4b0d](https://linux-hardware.org/?probe=dbc8fc4b0d) | Mar 03, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [884979d592](https://linux-hardware.org/?probe=884979d592) | Mar 01, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [b6128fb3e9](https://linux-hardware.org/?probe=b6128fb3e9) | Feb 28, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [fd4d00d935](https://linux-hardware.org/?probe=fd4d00d935) | Feb 28, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [64cf10c762](https://linux-hardware.org/?probe=64cf10c762) | Feb 26, 2023 |
| Sony          | VGN-Z21WRN_B                | Notebook    | [c1b765e164](https://linux-hardware.org/?probe=c1b765e164) | Feb 26, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [b1a38edcc2](https://linux-hardware.org/?probe=b1a38edcc2) | Feb 25, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ec82e38ab0](https://linux-hardware.org/?probe=ec82e38ab0) | Feb 25, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [6ebe283b1c](https://linux-hardware.org/?probe=6ebe283b1c) | Feb 25, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [24b1205b0c](https://linux-hardware.org/?probe=24b1205b0c) | Feb 24, 2023 |
| HP            | Pavilion dv6000 (GF657EA... | Notebook    | [fe52d35d1a](https://linux-hardware.org/?probe=fe52d35d1a) | Feb 24, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [ea8027e95b](https://linux-hardware.org/?probe=ea8027e95b) | Feb 24, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [2cc3513ca3](https://linux-hardware.org/?probe=2cc3513ca3) | Feb 24, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [e1a9b1b0fa](https://linux-hardware.org/?probe=e1a9b1b0fa) | Feb 21, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [fa50111733](https://linux-hardware.org/?probe=fa50111733) | Feb 20, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [76d6c3ad48](https://linux-hardware.org/?probe=76d6c3ad48) | Feb 19, 2023 |
| Dell          | Inspiron 14-3452            | Notebook    | [e08dcd6c59](https://linux-hardware.org/?probe=e08dcd6c59) | Feb 19, 2023 |
| Dell          | Inspiron 14-3452            | Notebook    | [e2cc024607](https://linux-hardware.org/?probe=e2cc024607) | Feb 18, 2023 |
| Sony          | VPCEB2Z1E                   | Notebook    | [5c172121ab](https://linux-hardware.org/?probe=5c172121ab) | Feb 17, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [1029c7f3bb](https://linux-hardware.org/?probe=1029c7f3bb) | Feb 17, 2023 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [741b7c300c](https://linux-hardware.org/?probe=741b7c300c) | Feb 17, 2023 |
| SLIMBOOK      | TITAN                       | Notebook    | [4638729e72](https://linux-hardware.org/?probe=4638729e72) | Feb 17, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [90fb04bc05](https://linux-hardware.org/?probe=90fb04bc05) | Feb 17, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ebca46331e](https://linux-hardware.org/?probe=ebca46331e) | Feb 16, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [f3d6e20575](https://linux-hardware.org/?probe=f3d6e20575) | Feb 16, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [d380600b31](https://linux-hardware.org/?probe=d380600b31) | Feb 15, 2023 |
| Lenovo        | ThinkPad SL 2746AHG         | Notebook    | [c141867fa3](https://linux-hardware.org/?probe=c141867fa3) | Feb 15, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [9565a9f43b](https://linux-hardware.org/?probe=9565a9f43b) | Feb 11, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [ba06eb3e9c](https://linux-hardware.org/?probe=ba06eb3e9c) | Feb 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [8a16d2e4bb](https://linux-hardware.org/?probe=8a16d2e4bb) | Feb 11, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [14bde69d96](https://linux-hardware.org/?probe=14bde69d96) | Feb 10, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [fb254cca56](https://linux-hardware.org/?probe=fb254cca56) | Feb 10, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [647f120e0b](https://linux-hardware.org/?probe=647f120e0b) | Feb 08, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [0f01d55766](https://linux-hardware.org/?probe=0f01d55766) | Feb 08, 2023 |
| HP            | 240 G3                      | Notebook    | [e3a0318824](https://linux-hardware.org/?probe=e3a0318824) | Feb 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ac340725d3](https://linux-hardware.org/?probe=ac340725d3) | Feb 07, 2023 |
| Sony          | VPCEH1E1E                   | Notebook    | [76589a7570](https://linux-hardware.org/?probe=76589a7570) | Feb 05, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a55eba93cc](https://linux-hardware.org/?probe=a55eba93cc) | Feb 04, 2023 |
| Dell          | Precision 7550              | Notebook    | [392db977df](https://linux-hardware.org/?probe=392db977df) | Feb 03, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1a189b08ea](https://linux-hardware.org/?probe=1a189b08ea) | Feb 03, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a174385328](https://linux-hardware.org/?probe=a174385328) | Feb 02, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c402e9c063](https://linux-hardware.org/?probe=c402e9c063) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [eb152c7d4e](https://linux-hardware.org/?probe=eb152c7d4e) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [58d5bdaa2d](https://linux-hardware.org/?probe=58d5bdaa2d) | Jan 31, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [10cdf2558f](https://linux-hardware.org/?probe=10cdf2558f) | Jan 29, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [09bbe80125](https://linux-hardware.org/?probe=09bbe80125) | Jan 29, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [3b4dd13d9f](https://linux-hardware.org/?probe=3b4dd13d9f) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [4333734c92](https://linux-hardware.org/?probe=4333734c92) | Jan 29, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [190a780b8a](https://linux-hardware.org/?probe=190a780b8a) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [a4ded61661](https://linux-hardware.org/?probe=a4ded61661) | Jan 27, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [26e692f7de](https://linux-hardware.org/?probe=26e692f7de) | Jan 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [7c19df8c01](https://linux-hardware.org/?probe=7c19df8c01) | Jan 25, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [54d0592fb2](https://linux-hardware.org/?probe=54d0592fb2) | Jan 24, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [206e04bc7d](https://linux-hardware.org/?probe=206e04bc7d) | Jan 23, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [eb2e4b24cc](https://linux-hardware.org/?probe=eb2e4b24cc) | Jan 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3a542dd368](https://linux-hardware.org/?probe=3a542dd368) | Jan 22, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [9e9dcb9883](https://linux-hardware.org/?probe=9e9dcb9883) | Jan 22, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [fdca7d69cd](https://linux-hardware.org/?probe=fdca7d69cd) | Jan 22, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [9536b9eedc](https://linux-hardware.org/?probe=9536b9eedc) | Jan 22, 2023 |
| Google        | Relm                        | Notebook    | [44fb1d9db1](https://linux-hardware.org/?probe=44fb1d9db1) | Jan 21, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [571389ffa0](https://linux-hardware.org/?probe=571389ffa0) | Jan 21, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [edee5aee7a](https://linux-hardware.org/?probe=edee5aee7a) | Jan 21, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c7ab1c1990](https://linux-hardware.org/?probe=c7ab1c1990) | Jan 20, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [4f24524e7d](https://linux-hardware.org/?probe=4f24524e7d) | Jan 19, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [e652633643](https://linux-hardware.org/?probe=e652633643) | Jan 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5a1bee99ee](https://linux-hardware.org/?probe=5a1bee99ee) | Jan 18, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [98f8255c15](https://linux-hardware.org/?probe=98f8255c15) | Jan 18, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [c2b8de2fdf](https://linux-hardware.org/?probe=c2b8de2fdf) | Jan 17, 2023 |
| Dell          | Latitude 5410               | Notebook    | [c97379d747](https://linux-hardware.org/?probe=c97379d747) | Jan 17, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [e76a4c32dc](https://linux-hardware.org/?probe=e76a4c32dc) | Jan 17, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [e8cc3131fc](https://linux-hardware.org/?probe=e8cc3131fc) | Jan 15, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6S... | Notebook    | [b4629bd83f](https://linux-hardware.org/?probe=b4629bd83f) | Jan 14, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [cdd815de42](https://linux-hardware.org/?probe=cdd815de42) | Jan 14, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [d412367e44](https://linux-hardware.org/?probe=d412367e44) | Jan 13, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [196ba30ef7](https://linux-hardware.org/?probe=196ba30ef7) | Jan 13, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ff52c2505f](https://linux-hardware.org/?probe=ff52c2505f) | Jan 13, 2023 |
| HP            | 15                          | Notebook    | [b06a589496](https://linux-hardware.org/?probe=b06a589496) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [d92a983612](https://linux-hardware.org/?probe=d92a983612) | Jan 12, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [e83827b548](https://linux-hardware.org/?probe=e83827b548) | Jan 11, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [0e81ffb471](https://linux-hardware.org/?probe=0e81ffb471) | Jan 11, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [433ba8749a](https://linux-hardware.org/?probe=433ba8749a) | Jan 10, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [03505c402c](https://linux-hardware.org/?probe=03505c402c) | Jan 08, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [7ee7875a97](https://linux-hardware.org/?probe=7ee7875a97) | Jan 08, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [1ad8a2f766](https://linux-hardware.org/?probe=1ad8a2f766) | Jan 08, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [efd4eaee02](https://linux-hardware.org/?probe=efd4eaee02) | Jan 07, 2023 |
| Dell          | Inspiron 5520               | Notebook    | [9b4925d88d](https://linux-hardware.org/?probe=9b4925d88d) | Jan 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [8b7d2f1a46](https://linux-hardware.org/?probe=8b7d2f1a46) | Jan 07, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [4bdffcda7f](https://linux-hardware.org/?probe=4bdffcda7f) | Jan 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [05c69304bb](https://linux-hardware.org/?probe=05c69304bb) | Jan 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [2cb5d2f306](https://linux-hardware.org/?probe=2cb5d2f306) | Jan 05, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [fc365670d0](https://linux-hardware.org/?probe=fc365670d0) | Jan 05, 2023 |
| Dell          | Precision 7520              | Notebook    | [10c791a9f5](https://linux-hardware.org/?probe=10c791a9f5) | Jan 05, 2023 |
| Acer          | Aspire 5530                 | Notebook    | [8c12909b0a](https://linux-hardware.org/?probe=8c12909b0a) | Jan 04, 2023 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [8a7807ff8c](https://linux-hardware.org/?probe=8a7807ff8c) | Jan 03, 2023 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [1b66a8a1a8](https://linux-hardware.org/?probe=1b66a8a1a8) | Jan 02, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [501b47c258](https://linux-hardware.org/?probe=501b47c258) | Jan 02, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [0eb54f1078](https://linux-hardware.org/?probe=0eb54f1078) | Jan 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [43923d1e98](https://linux-hardware.org/?probe=43923d1e98) | Jan 01, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [48c688033a](https://linux-hardware.org/?probe=48c688033a) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [8540c1c554](https://linux-hardware.org/?probe=8540c1c554) | Dec 30, 2022 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [82cbc15539](https://linux-hardware.org/?probe=82cbc15539) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [b4c615f28c](https://linux-hardware.org/?probe=b4c615f28c) | Dec 30, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [531e60d101](https://linux-hardware.org/?probe=531e60d101) | Dec 30, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [b0f7933824](https://linux-hardware.org/?probe=b0f7933824) | Dec 29, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [4dab06b05f](https://linux-hardware.org/?probe=4dab06b05f) | Dec 29, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [4a26556b6b](https://linux-hardware.org/?probe=4a26556b6b) | Dec 29, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [7ac222385a](https://linux-hardware.org/?probe=7ac222385a) | Dec 28, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [faf2c0e5d7](https://linux-hardware.org/?probe=faf2c0e5d7) | Dec 28, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [870deddfbe](https://linux-hardware.org/?probe=870deddfbe) | Dec 27, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4283e3bb1e](https://linux-hardware.org/?probe=4283e3bb1e) | Dec 27, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [db1c25cde3](https://linux-hardware.org/?probe=db1c25cde3) | Dec 27, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [037841f71c](https://linux-hardware.org/?probe=037841f71c) | Dec 25, 2022 |
| ASUSTek       | X550LN                      | Notebook    | [207f82e19c](https://linux-hardware.org/?probe=207f82e19c) | Dec 25, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f113c7d475](https://linux-hardware.org/?probe=f113c7d475) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [cc49bb2ef6](https://linux-hardware.org/?probe=cc49bb2ef6) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [838eb1f6fa](https://linux-hardware.org/?probe=838eb1f6fa) | Dec 24, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2995a5ea20](https://linux-hardware.org/?probe=2995a5ea20) | Dec 24, 2022 |
| Acer          | TravelMate 7730             | Notebook    | [8d166266b9](https://linux-hardware.org/?probe=8d166266b9) | Dec 23, 2022 |
| HP            | Compaq Presario CQ61        | Notebook    | [a85b255853](https://linux-hardware.org/?probe=a85b255853) | Dec 22, 2022 |
| Dell          | 0J1C3P A00                  | Desktop     | [b65b20a073](https://linux-hardware.org/?probe=b65b20a073) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [c1d47a051f](https://linux-hardware.org/?probe=c1d47a051f) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [0410be2105](https://linux-hardware.org/?probe=0410be2105) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [d1dc69cc49](https://linux-hardware.org/?probe=d1dc69cc49) | Dec 22, 2022 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [2ad8b45619](https://linux-hardware.org/?probe=2ad8b45619) | Dec 21, 2022 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [0e53e0be48](https://linux-hardware.org/?probe=0e53e0be48) | Dec 21, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [ae1cc3b6c0](https://linux-hardware.org/?probe=ae1cc3b6c0) | Dec 21, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2f3edb2954](https://linux-hardware.org/?probe=2f3edb2954) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5542739f1e](https://linux-hardware.org/?probe=5542739f1e) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [0d03f7978b](https://linux-hardware.org/?probe=0d03f7978b) | Dec 20, 2022 |
| Acer          | TravelMate 7730             | Notebook    | [8078925015](https://linux-hardware.org/?probe=8078925015) | Dec 20, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [21a91196b1](https://linux-hardware.org/?probe=21a91196b1) | Dec 19, 2022 |
| Lenovo        | ThinkPad T430 2347G5U       | Notebook    | [ac787dc7dc](https://linux-hardware.org/?probe=ac787dc7dc) | Dec 17, 2022 |
| ASUSTek       | PRIME Z590-P WIFI           | Desktop     | [34ac0b3211](https://linux-hardware.org/?probe=34ac0b3211) | Dec 17, 2022 |
| Lenovo        | ThinkPad T430 2347G5U       | Notebook    | [e47e7c18c9](https://linux-hardware.org/?probe=e47e7c18c9) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [e3ac894e13](https://linux-hardware.org/?probe=e3ac894e13) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [987d96714a](https://linux-hardware.org/?probe=987d96714a) | Dec 17, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [ac15fdcc8b](https://linux-hardware.org/?probe=ac15fdcc8b) | Dec 16, 2022 |
| HP            | 2215                        | Desktop     | [78151a5e1b](https://linux-hardware.org/?probe=78151a5e1b) | Dec 16, 2022 |
| ASUSTek       | X550LN                      | Notebook    | [d09c34a000](https://linux-hardware.org/?probe=d09c34a000) | Dec 16, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [7f2f68d436](https://linux-hardware.org/?probe=7f2f68d436) | Dec 16, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [8caca0975b](https://linux-hardware.org/?probe=8caca0975b) | Dec 15, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2c5167b360](https://linux-hardware.org/?probe=2c5167b360) | Dec 14, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [ca7464eb3f](https://linux-hardware.org/?probe=ca7464eb3f) | Dec 14, 2022 |
| HP            | 14                          | Notebook    | [4794938b36](https://linux-hardware.org/?probe=4794938b36) | Dec 14, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [976923f807](https://linux-hardware.org/?probe=976923f807) | Dec 12, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [345eb47090](https://linux-hardware.org/?probe=345eb47090) | Dec 09, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [7ae8aecc25](https://linux-hardware.org/?probe=7ae8aecc25) | Dec 08, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [1d97601be2](https://linux-hardware.org/?probe=1d97601be2) | Dec 08, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [4943e0aa12](https://linux-hardware.org/?probe=4943e0aa12) | Dec 08, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [bb704e1b90](https://linux-hardware.org/?probe=bb704e1b90) | Dec 08, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [be0753651f](https://linux-hardware.org/?probe=be0753651f) | Dec 07, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [c458ba13c3](https://linux-hardware.org/?probe=c458ba13c3) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [bd9f0dc967](https://linux-hardware.org/?probe=bd9f0dc967) | Dec 05, 2022 |
| HP            | 14                          | Notebook    | [868daee488](https://linux-hardware.org/?probe=868daee488) | Dec 03, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [bd06d3a448](https://linux-hardware.org/?probe=bd06d3a448) | Dec 03, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [c9e94d483e](https://linux-hardware.org/?probe=c9e94d483e) | Nov 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [d53007b0b3](https://linux-hardware.org/?probe=d53007b0b3) | Nov 30, 2022 |
| Acer          | TravelMate P614-51T-G2      | Notebook    | [37e14fc1c1](https://linux-hardware.org/?probe=37e14fc1c1) | Nov 30, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [d62cc93587](https://linux-hardware.org/?probe=d62cc93587) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [8d8fc0d4d4](https://linux-hardware.org/?probe=8d8fc0d4d4) | Nov 28, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [4cec4d0e04](https://linux-hardware.org/?probe=4cec4d0e04) | Nov 27, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [05d0bf9d8d](https://linux-hardware.org/?probe=05d0bf9d8d) | Nov 25, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9e22e08aa1](https://linux-hardware.org/?probe=9e22e08aa1) | Nov 25, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [ce586530e4](https://linux-hardware.org/?probe=ce586530e4) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [cf30d2df93](https://linux-hardware.org/?probe=cf30d2df93) | Nov 24, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [bc690a128e](https://linux-hardware.org/?probe=bc690a128e) | Nov 23, 2022 |
| ASRock        | 990FX Extreme3              | Desktop     | [84b8daa5c4](https://linux-hardware.org/?probe=84b8daa5c4) | Nov 20, 2022 |
| Toshiba       | Satellite P50-B-10Z         | Notebook    | [c5413ac393](https://linux-hardware.org/?probe=c5413ac393) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [96d82e20c4](https://linux-hardware.org/?probe=96d82e20c4) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [f5fd517d69](https://linux-hardware.org/?probe=f5fd517d69) | Nov 19, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [d4b8ffffe1](https://linux-hardware.org/?probe=d4b8ffffe1) | Nov 19, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [f2e60e58dc](https://linux-hardware.org/?probe=f2e60e58dc) | Nov 17, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [fe43edb930](https://linux-hardware.org/?probe=fe43edb930) | Nov 16, 2022 |
| HP            | 1998                        | Desktop     | [f9746a4ae0](https://linux-hardware.org/?probe=f9746a4ae0) | Nov 15, 2022 |
| Dell          | Latitude D630               | Notebook    | [3a15603bd6](https://linux-hardware.org/?probe=3a15603bd6) | Nov 13, 2022 |
| Dell          | Latitude D630               | Notebook    | [3e964fdd59](https://linux-hardware.org/?probe=3e964fdd59) | Nov 12, 2022 |
| ASUSTek       | K93SV                       | Notebook    | [8511ee86ad](https://linux-hardware.org/?probe=8511ee86ad) | Nov 12, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2dc75b76f4](https://linux-hardware.org/?probe=2dc75b76f4) | Nov 12, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [01a339fb27](https://linux-hardware.org/?probe=01a339fb27) | Nov 11, 2022 |
| Microsoft     | Surface 2                   | Tablet      | [0cab1d9501](https://linux-hardware.org/?probe=0cab1d9501) | Nov 10, 2022 |
| Lenovo        | ThinkPad T420 4238LY7       | Notebook    | [c5cf611a37](https://linux-hardware.org/?probe=c5cf611a37) | Nov 07, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [7818a033c6](https://linux-hardware.org/?probe=7818a033c6) | Nov 06, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [b59f9dcf48](https://linux-hardware.org/?probe=b59f9dcf48) | Nov 05, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [e56aa65a39](https://linux-hardware.org/?probe=e56aa65a39) | Nov 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [8fdaec6b5a](https://linux-hardware.org/?probe=8fdaec6b5a) | Nov 04, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [4f5b04e8d9](https://linux-hardware.org/?probe=4f5b04e8d9) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5c0b61dfb6](https://linux-hardware.org/?probe=5c0b61dfb6) | Nov 03, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [d17e8e8e36](https://linux-hardware.org/?probe=d17e8e8e36) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [342c7609c9](https://linux-hardware.org/?probe=342c7609c9) | Nov 02, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5b45883fef](https://linux-hardware.org/?probe=5b45883fef) | Nov 02, 2022 |
| MSI           | B75A-IE35                   | Desktop     | [57b74e4ca2](https://linux-hardware.org/?probe=57b74e4ca2) | Nov 01, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [6b2b490208](https://linux-hardware.org/?probe=6b2b490208) | Nov 01, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [1b626eed02](https://linux-hardware.org/?probe=1b626eed02) | Oct 31, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [1b03bb8445](https://linux-hardware.org/?probe=1b03bb8445) | Oct 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [f27aa95917](https://linux-hardware.org/?probe=f27aa95917) | Oct 29, 2022 |
| Dell          | Precision 7760              | Notebook    | [b8fce270db](https://linux-hardware.org/?probe=b8fce270db) | Oct 27, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2474ff9baf](https://linux-hardware.org/?probe=2474ff9baf) | Oct 27, 2022 |
| Toshiba       | Satellite C50D-A-133        | Notebook    | [c1ba737ccc](https://linux-hardware.org/?probe=c1ba737ccc) | Oct 25, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [4785b7f6f6](https://linux-hardware.org/?probe=4785b7f6f6) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [91bf754e64](https://linux-hardware.org/?probe=91bf754e64) | Oct 24, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [7d12ed56e5](https://linux-hardware.org/?probe=7d12ed56e5) | Oct 19, 2022 |
| HP            | ENVY Sleekbook 6            | Notebook    | [a197375e26](https://linux-hardware.org/?probe=a197375e26) | Oct 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6e45f7ecd7](https://linux-hardware.org/?probe=6e45f7ecd7) | Oct 15, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [d1a5c91196](https://linux-hardware.org/?probe=d1a5c91196) | Oct 14, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [b69b373cc1](https://linux-hardware.org/?probe=b69b373cc1) | Oct 14, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [175ebd8462](https://linux-hardware.org/?probe=175ebd8462) | Oct 14, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [e0c71d09bb](https://linux-hardware.org/?probe=e0c71d09bb) | Oct 11, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [1ba5f65f98](https://linux-hardware.org/?probe=1ba5f65f98) | Oct 10, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [41dd35ae5f](https://linux-hardware.org/?probe=41dd35ae5f) | Oct 10, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [02170aab85](https://linux-hardware.org/?probe=02170aab85) | Oct 09, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [69023fe30e](https://linux-hardware.org/?probe=69023fe30e) | Oct 09, 2022 |
| Lenovo        | T530-28ICB                  | Desktop     | [b87998cf32](https://linux-hardware.org/?probe=b87998cf32) | Oct 09, 2022 |
| Dell          | 0DPRF9 A00                  | All in one  | [3d0b820b58](https://linux-hardware.org/?probe=3d0b820b58) | Oct 08, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [1a165faedb](https://linux-hardware.org/?probe=1a165faedb) | Oct 08, 2022 |
| HP            | ENVY x360                   | Convertible | [b299af0bca](https://linux-hardware.org/?probe=b299af0bca) | Oct 08, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [be6a0fda35](https://linux-hardware.org/?probe=be6a0fda35) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [bc1f7e7d02](https://linux-hardware.org/?probe=bc1f7e7d02) | Oct 06, 2022 |
| Lenovo        | T530-28ICB                  | Desktop     | [175a71260e](https://linux-hardware.org/?probe=175a71260e) | Oct 06, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [85eb59fc6d](https://linux-hardware.org/?probe=85eb59fc6d) | Oct 05, 2022 |
| Lenovo        | ThinkPad T460p 20FW002CP... | Notebook    | [b7cd76d0b6](https://linux-hardware.org/?probe=b7cd76d0b6) | Oct 05, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [0bea9d8673](https://linux-hardware.org/?probe=0bea9d8673) | Oct 05, 2022 |
| Lenovo        | ThinkPad X230 2325Y5L       | Notebook    | [7c5c62cc90](https://linux-hardware.org/?probe=7c5c62cc90) | Oct 03, 2022 |
| Dell          | Latitude 7300               | Notebook    | [d9acb6ec9c](https://linux-hardware.org/?probe=d9acb6ec9c) | Oct 03, 2022 |
| Sony          | VGN-SZ3XP_C                 | Notebook    | [6e9671dd1a](https://linux-hardware.org/?probe=6e9671dd1a) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [ccf9b69093](https://linux-hardware.org/?probe=ccf9b69093) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [7b89b5d0cf](https://linux-hardware.org/?probe=7b89b5d0cf) | Oct 02, 2022 |
| HP            | ZBook 14 G2                 | Notebook    | [ac14cbda52](https://linux-hardware.org/?probe=ac14cbda52) | Oct 02, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [cb5d0d1945](https://linux-hardware.org/?probe=cb5d0d1945) | Oct 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [3af0c5cc5f](https://linux-hardware.org/?probe=3af0c5cc5f) | Oct 01, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [db15c7b708](https://linux-hardware.org/?probe=db15c7b708) | Oct 01, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [608c715bab](https://linux-hardware.org/?probe=608c715bab) | Sep 26, 2022 |
| Intel         | H81U                        | Notebook    | [9e4458528b](https://linux-hardware.org/?probe=9e4458528b) | Sep 25, 2022 |
| Dell          | Precision 7760              | Notebook    | [f6600a1244](https://linux-hardware.org/?probe=f6600a1244) | Sep 22, 2022 |
| Intel         | Kabylake Platform           | Notebook    | [8b1c5eb5bf](https://linux-hardware.org/?probe=8b1c5eb5bf) | Sep 21, 2022 |
| MSI           | H81M-P33                    | Desktop     | [108817dc0f](https://linux-hardware.org/?probe=108817dc0f) | Sep 21, 2022 |
| ASRock        | HM55-HT                     | Desktop     | [64fff8f065](https://linux-hardware.org/?probe=64fff8f065) | Sep 20, 2022 |
| Intel         | NUC8i7HNB J68197-502        | Mini pc     | [1573d65d2d](https://linux-hardware.org/?probe=1573d65d2d) | Sep 18, 2022 |
| MSI           | 870-G45                     | Desktop     | [74af87b0c5](https://linux-hardware.org/?probe=74af87b0c5) | Sep 17, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [081d4b1d50](https://linux-hardware.org/?probe=081d4b1d50) | Sep 16, 2022 |
| ASUSTek       | M2A74-AM                    | Desktop     | [25c30e4e54](https://linux-hardware.org/?probe=25c30e4e54) | Sep 14, 2022 |
| ASUSTek       | M2A74-AM                    | Desktop     | [24e6ffe552](https://linux-hardware.org/?probe=24e6ffe552) | Sep 14, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [cc28ed218f](https://linux-hardware.org/?probe=cc28ed218f) | Sep 13, 2022 |
| Acer          | Aspire 5050                 | Notebook    | [1961d1c468](https://linux-hardware.org/?probe=1961d1c468) | Sep 13, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a86e9d966b](https://linux-hardware.org/?probe=a86e9d966b) | Sep 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [64b8914cb2](https://linux-hardware.org/?probe=64b8914cb2) | Sep 12, 2022 |
| LG Electro... | 17Z990-R.AAS8U1             | Notebook    | [2df5aeabed](https://linux-hardware.org/?probe=2df5aeabed) | Sep 08, 2022 |
| Acer          | Aspire X3950                | Desktop     | [22d1319220](https://linux-hardware.org/?probe=22d1319220) | Sep 06, 2022 |
| ASUSTek       | P5GZ-MX                     | Desktop     | [883739db23](https://linux-hardware.org/?probe=883739db23) | Sep 05, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [f16d383b65](https://linux-hardware.org/?probe=f16d383b65) | Sep 05, 2022 |
| Dell          | Precision 7760              | Notebook    | [e920197599](https://linux-hardware.org/?probe=e920197599) | Sep 05, 2022 |
| HP            | Pavilion 15                 | Notebook    | [194bb33f3d](https://linux-hardware.org/?probe=194bb33f3d) | Sep 04, 2022 |
| HP            | 2ADC                        | Desktop     | [d9e5d2b511](https://linux-hardware.org/?probe=d9e5d2b511) | Sep 04, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [0749c352d0](https://linux-hardware.org/?probe=0749c352d0) | Sep 03, 2022 |
| HP            | 18E4                        | Desktop     | [c58c0043cb](https://linux-hardware.org/?probe=c58c0043cb) | Sep 03, 2022 |
| HP            | 3397                        | Desktop     | [5cd2349a9c](https://linux-hardware.org/?probe=5cd2349a9c) | Sep 02, 2022 |
| Dell          | Latitude 5285               | Tablet      | [4e75bec854](https://linux-hardware.org/?probe=4e75bec854) | Sep 01, 2022 |
| HP            | Notebook                    | Notebook    | [573d359faf](https://linux-hardware.org/?probe=573d359faf) | Aug 31, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [1109650747](https://linux-hardware.org/?probe=1109650747) | Aug 31, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [2be9b66ba1](https://linux-hardware.org/?probe=2be9b66ba1) | Aug 30, 2022 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [2d66cac294](https://linux-hardware.org/?probe=2d66cac294) | Aug 28, 2022 |
| LincPlus      | LINNCPLUS P1                | Notebook    | [516427e0e9](https://linux-hardware.org/?probe=516427e0e9) | Aug 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [5028378988](https://linux-hardware.org/?probe=5028378988) | Aug 23, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [7a86bdf14e](https://linux-hardware.org/?probe=7a86bdf14e) | Aug 22, 2022 |
| AZW           | GK55                        | Desktop     | [0ae52e1fdf](https://linux-hardware.org/?probe=0ae52e1fdf) | Aug 21, 2022 |
| Dell          | Latitude 7420               | Notebook    | [d599ef65fd](https://linux-hardware.org/?probe=d599ef65fd) | Aug 20, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [4efd818377](https://linux-hardware.org/?probe=4efd818377) | Aug 19, 2022 |
| MSI           | H170M PRO-VDH               | Desktop     | [4d7aa09763](https://linux-hardware.org/?probe=4d7aa09763) | Aug 16, 2022 |
| HP            | EliteBook 745 G5            | Notebook    | [7e8d33a07f](https://linux-hardware.org/?probe=7e8d33a07f) | Aug 16, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [1b78691cac](https://linux-hardware.org/?probe=1b78691cac) | Aug 14, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [b41823f392](https://linux-hardware.org/?probe=b41823f392) | Aug 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [644fbe551a](https://linux-hardware.org/?probe=644fbe551a) | Aug 13, 2022 |
| Dell          | Latitude E7470              | Notebook    | [61d0b104e9](https://linux-hardware.org/?probe=61d0b104e9) | Aug 13, 2022 |
| MSI           | MS-77311                    | Desktop     | [86b4d71bc0](https://linux-hardware.org/?probe=86b4d71bc0) | Aug 11, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [46aa83aeb4](https://linux-hardware.org/?probe=46aa83aeb4) | Aug 07, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [3d426cb1de](https://linux-hardware.org/?probe=3d426cb1de) | Aug 04, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [40099f2516](https://linux-hardware.org/?probe=40099f2516) | Aug 03, 2022 |
| HP            | 8433 11                     | Desktop     | [cd790281b5](https://linux-hardware.org/?probe=cd790281b5) | Aug 02, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [b44bebcab6](https://linux-hardware.org/?probe=b44bebcab6) | Aug 01, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [cdca6713e9](https://linux-hardware.org/?probe=cdca6713e9) | Jul 31, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [1444843fcd](https://linux-hardware.org/?probe=1444843fcd) | Jul 31, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [4f2ba69c49](https://linux-hardware.org/?probe=4f2ba69c49) | Jul 27, 2022 |
| MSI           | 2AE0                        | Desktop     | [5c0034d313](https://linux-hardware.org/?probe=5c0034d313) | Jul 22, 2022 |
| MSI           | 2AE0                        | Desktop     | [df441346da](https://linux-hardware.org/?probe=df441346da) | Jul 22, 2022 |
| Dell          | Latitude E4200              | Notebook    | [6cc0415a8a](https://linux-hardware.org/?probe=6cc0415a8a) | Jul 21, 2022 |
| Medion        | MS-7797                     | Desktop     | [caf13d5392](https://linux-hardware.org/?probe=caf13d5392) | Jul 14, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [3e74ebae5a](https://linux-hardware.org/?probe=3e74ebae5a) | Jul 14, 2022 |
| Compaq        | Presario CQ-23              | Notebook    | [589a41e629](https://linux-hardware.org/?probe=589a41e629) | Jul 14, 2022 |
| Dell          | 0GM819                      | Desktop     | [3d18cc2632](https://linux-hardware.org/?probe=3d18cc2632) | Jul 08, 2022 |
| Dell          | Latitude 7320 Detachable    | Tablet      | [5f1b339a57](https://linux-hardware.org/?probe=5f1b339a57) | Jul 07, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [95e6ec0822](https://linux-hardware.org/?probe=95e6ec0822) | Jul 05, 2022 |
| HP            | 3646h                       | Desktop     | [9e0737f23f](https://linux-hardware.org/?probe=9e0737f23f) | Jul 04, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [e0c6593aee](https://linux-hardware.org/?probe=e0c6593aee) | Jul 04, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [28429fdd32](https://linux-hardware.org/?probe=28429fdd32) | Jul 02, 2022 |
| HP            | 8169                        | Desktop     | [18c6ea7678](https://linux-hardware.org/?probe=18c6ea7678) | Jul 01, 2022 |
| HP            | 8169                        | Desktop     | [c479baadc1](https://linux-hardware.org/?probe=c479baadc1) | Jul 01, 2022 |
| MicroByte     | ezbook                      | Notebook    | [91b1fc169b](https://linux-hardware.org/?probe=91b1fc169b) | Jun 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [6e16eed17c](https://linux-hardware.org/?probe=6e16eed17c) | Jun 26, 2022 |
| ASUSTek       | S550CM                      | Notebook    | [c7262ada04](https://linux-hardware.org/?probe=c7262ada04) | Jun 25, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [a8c98b76b4](https://linux-hardware.org/?probe=a8c98b76b4) | Jun 24, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [10de805cb0](https://linux-hardware.org/?probe=10de805cb0) | Jun 24, 2022 |
| Google        | Kled                        | Notebook    | [5f47e6d3e3](https://linux-hardware.org/?probe=5f47e6d3e3) | Jun 16, 2022 |
| Google        | Kled                        | Notebook    | [6a566134c4](https://linux-hardware.org/?probe=6a566134c4) | Jun 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [f7abc9fae0](https://linux-hardware.org/?probe=f7abc9fae0) | Jun 14, 2022 |
| Acer          | Aspire X3950                | Desktop     | [81797815d2](https://linux-hardware.org/?probe=81797815d2) | Jun 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [c62add2d70](https://linux-hardware.org/?probe=c62add2d70) | Jun 13, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [efc9e12c05](https://linux-hardware.org/?probe=efc9e12c05) | Jun 12, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [e956f6b0b8](https://linux-hardware.org/?probe=e956f6b0b8) | Jun 09, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [9bfdb902ce](https://linux-hardware.org/?probe=9bfdb902ce) | Jun 08, 2022 |
| HP            | 3397                        | Desktop     | [55bcbdbc1f](https://linux-hardware.org/?probe=55bcbdbc1f) | Jun 07, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [5407d4a1f6](https://linux-hardware.org/?probe=5407d4a1f6) | Jun 07, 2022 |
| Intel         | Kabylake Platform           | Notebook    | [074fd90c6a](https://linux-hardware.org/?probe=074fd90c6a) | Jun 06, 2022 |
| TrekStor      | Surfbook A13B               | Notebook    | [a42b3de31a](https://linux-hardware.org/?probe=a42b3de31a) | Jun 05, 2022 |
| Dell          | Precision M6500             | Notebook    | [1b68d2ca74](https://linux-hardware.org/?probe=1b68d2ca74) | Jun 01, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [74e6dbe9af](https://linux-hardware.org/?probe=74e6dbe9af) | May 23, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [a53d746d08](https://linux-hardware.org/?probe=a53d746d08) | May 23, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [9044b2e4e2](https://linux-hardware.org/?probe=9044b2e4e2) | May 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5107890ffd](https://linux-hardware.org/?probe=5107890ffd) | May 15, 2022 |
| Sony          | VPCEA36FG                   | Notebook    | [0161a27629](https://linux-hardware.org/?probe=0161a27629) | May 13, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [e6c4aaa3d8](https://linux-hardware.org/?probe=e6c4aaa3d8) | May 12, 2022 |
| Unknown       | HX90                        | Desktop     | [3a7e2628b0](https://linux-hardware.org/?probe=3a7e2628b0) | May 09, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [e99cdba363](https://linux-hardware.org/?probe=e99cdba363) | May 07, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [a53b09a7f3](https://linux-hardware.org/?probe=a53b09a7f3) | May 07, 2022 |
| HYPERPC       | PLAY                        | Notebook    | [408e86d04f](https://linux-hardware.org/?probe=408e86d04f) | May 06, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [246c63d834](https://linux-hardware.org/?probe=246c63d834) | May 06, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [ebaaf4a69b](https://linux-hardware.org/?probe=ebaaf4a69b) | May 01, 2022 |
| HP            | 8433 11                     | Desktop     | [a5b829538b](https://linux-hardware.org/?probe=a5b829538b) | Apr 29, 2022 |
| TYAN Compu... | S7012                       | Server      | [018f293210](https://linux-hardware.org/?probe=018f293210) | Apr 28, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [35b3b3ae30](https://linux-hardware.org/?probe=35b3b3ae30) | Apr 26, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [faf447a067](https://linux-hardware.org/?probe=faf447a067) | Apr 24, 2022 |
| Gigabyte      | X99P-SLI-CF                 | Desktop     | [19055b80bc](https://linux-hardware.org/?probe=19055b80bc) | Apr 16, 2022 |
| Lenovo        | IdeaPadFlex 6-14IKB 81EM    | Convertible | [5e31d89c28](https://linux-hardware.org/?probe=5e31d89c28) | Apr 09, 2022 |
| IPASON        | MaxBook P1                  | Notebook    | [d66d062f54](https://linux-hardware.org/?probe=d66d062f54) | Apr 05, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [9352c21f95](https://linux-hardware.org/?probe=9352c21f95) | Mar 17, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | Notebook    | [b746a25ff1](https://linux-hardware.org/?probe=b746a25ff1) | Jan 28, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [4368bd67ac](https://linux-hardware.org/?probe=4368bd67ac) | Nov 23, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [686454975b](https://linux-hardware.org/?probe=686454975b) | Nov 23, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [36ac197007](https://linux-hardware.org/?probe=36ac197007) | Nov 17, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.15.0-56-generic    | 27        | 10%     |
| 5.15.0-47-generic    | 18        | 6.67%   |
| 5.15.0-48-generic    | 14        | 5.19%   |
| 5.15.0-60-generic    | 12        | 4.44%   |
| 5.15.0-58-generic    | 12        | 4.44%   |
| 5.15.0-52-generic    | 11        | 4.07%   |
| 5.15.0-46-generic    | 11        | 4.07%   |
| 5.15.0-67-generic    | 10        | 3.7%    |
| 5.15.0-25-generic    | 10        | 3.7%    |
| 5.15.0-40-generic    | 9         | 3.33%   |
| 5.19.0-38-generic    | 8         | 2.96%   |
| 5.19.0-32-generic    | 8         | 2.96%   |
| 5.15.0-43-generic    | 8         | 2.96%   |
| 5.15.0-53-generic    | 7         | 2.59%   |
| 5.15.0-27-generic    | 7         | 2.59%   |
| 5.15.0-50-generic    | 6         | 2.22%   |
| 5.15.0-41-generic    | 6         | 2.22%   |
| 5.19.0-35-generic    | 5         | 1.85%   |
| 5.15.0-69-generic    | 5         | 1.85%   |
| 5.15.0-57-generic    | 5         | 1.85%   |
| 5.19.0-42-generic    | 4         | 1.48%   |
| 5.15.0-30-generic    | 4         | 1.48%   |
| 5.19.0-43-generic    | 3         | 1.11%   |
| 5.15.0-37-generic    | 3         | 1.11%   |
| 5.19.0-41-generic    | 2         | 0.74%   |
| 5.19.0-40-generic    | 2         | 0.74%   |
| 5.15.0-73-generic    | 2         | 0.74%   |
| 5.15.0-71-generic    | 2         | 0.74%   |
| 5.15.0-70-generic    | 2         | 0.74%   |
| 5.15.0-58-lowlatency | 2         | 0.74%   |
| 5.15.0-56-lowlatency | 2         | 0.74%   |
| 5.15.0-52-lowlatency | 2         | 0.74%   |
| 5.15.0-39-generic    | 2         | 0.74%   |
| 5.15.0-35-generic    | 2         | 0.74%   |
| 5.15.0-1024-raspi    | 2         | 0.74%   |
| 5.14.0-1054-oem      | 2         | 0.74%   |
| 6.2.3-x64v1-xanmod1  | 1         | 0.37%   |
| 6.1.8-x64v1-xanmod1  | 1         | 0.37%   |
| 6.0.8-x64v1-xanmod1  | 1         | 0.37%   |
| 5.19.0-46-generic    | 1         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 193       | 80.08%  |
| 5.19.0  | 34        | 14.11%  |
| 5.18.0  | 3         | 1.24%   |
| 5.17.0  | 2         | 0.83%   |
| 5.14.0  | 2         | 0.83%   |
| 5.13.0  | 2         | 0.83%   |
| 6.2.3   | 1         | 0.41%   |
| 6.1.8   | 1         | 0.41%   |
| 6.0.8   | 1         | 0.41%   |
| 5.17.1  | 1         | 0.41%   |
| 4.9.337 | 1         | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 193       | 80.08%  |
| 5.19    | 34        | 14.11%  |
| 5.18    | 3         | 1.24%   |
| 5.17    | 3         | 1.24%   |
| 5.14    | 2         | 0.83%   |
| 5.13    | 2         | 0.83%   |
| 6.2     | 1         | 0.41%   |
| 6.1     | 1         | 0.41%   |
| 6.0     | 1         | 0.41%   |
| 4.9     | 1         | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 229       | 97.45%  |
| aarch64 | 4         | 1.7%    |
| armv7l  | 2         | 0.85%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| MATE   | 230       | 97.87%  |
| KDE5   | 2         | 0.85%   |
| GNOME  | 2         | 0.85%   |
| Budgie | 1         | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 226       | 96.17%  |
| Wayland | 5         | 2.13%   |
| Tty     | 4         | 1.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 195       | 81.93%  |
| GDM3    | 21        | 8.82%   |
| Unknown | 20        | 8.4%    |
| SDDM    | 2         | 0.84%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 82        | 34.6%   |
| fr_FR | 33        | 13.92%  |
| de_DE | 31        | 13.08%  |
| it_IT | 16        | 6.75%   |
| ru_RU | 8         | 3.38%   |
| en_CA | 8         | 3.38%   |
| en_AU | 8         | 3.38%   |
| pt_BR | 6         | 2.53%   |
| es_ES | 5         | 2.11%   |
| en_GB | 5         | 2.11%   |
| C     | 5         | 2.11%   |
| fi_FI | 3         | 1.27%   |
| de_CH | 3         | 1.27%   |
| zh_TW | 2         | 0.84%   |
| pl_PL | 2         | 0.84%   |
| hu_HU | 2         | 0.84%   |
| hr_HR | 2         | 0.84%   |
| es_MX | 2         | 0.84%   |
| es_AR | 2         | 0.84%   |
| el_GR | 2         | 0.84%   |
| cs_CZ | 2         | 0.84%   |
| zh_CN | 1         | 0.42%   |
| pt_PT | 1         | 0.42%   |
| nl_NL | 1         | 0.42%   |
| et_EE | 1         | 0.42%   |
| es_PE | 1         | 0.42%   |
| en_IL | 1         | 0.42%   |
| de_AT | 1         | 0.42%   |
| da_DK | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 121       | 50%     |
| EFI  | 121       | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 206       | 87.29%  |
| Overlay | 8         | 3.39%   |
| Btrfs   | 8         | 3.39%   |
| Tmpfs   | 5         | 2.12%   |
| Zfs     | 4         | 1.69%   |
| Xfs     | 3         | 1.27%   |
| Jfs     | 1         | 0.42%   |
| Ext2    | 1         | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 169       | 70.42%  |
| Unknown | 42        | 17.5%   |
| MBR     | 29        | 12.08%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 197       | 83.47%  |
| Yes       | 39        | 16.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 151       | 63.45%  |
| Yes       | 87        | 36.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Hewlett-Packard                      | 45        | 19.15%  |
| ASUSTek Computer                     | 42        | 17.87%  |
| Lenovo                               | 29        | 12.34%  |
| Dell                                 | 24        | 10.21%  |
| MSI                                  | 15        | 6.38%   |
| Acer                                 | 10        | 4.26%   |
| Gigabyte Technology                  | 9         | 3.83%   |
| Apple                                | 7         | 2.98%   |
| Intel                                | 6         | 2.55%   |
| ASRock                               | 6         | 2.55%   |
| Sony                                 | 5         | 2.13%   |
| HUAWEI                               | 4         | 1.7%    |
| Raspberry Pi Foundation              | 3         | 1.28%   |
| Google                               | 3         | 1.28%   |
| Unknown                              | 3         | 1.28%   |
| Toshiba                              | 2         | 0.85%   |
| Hardkernel                           | 2         | 0.85%   |
| TYAN Computer                        | 1         | 0.43%   |
| TrekStor                             | 1         | 0.43%   |
| SLIMBOOK                             | 1         | 0.43%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.43%   |
| Samsung Electronics                  | 1         | 0.43%   |
| RCA                                  | 1         | 0.43%   |
| Notebook                             | 1         | 0.43%   |
| Microsoft                            | 1         | 0.43%   |
| MicroByte                            | 1         | 0.43%   |
| Medion                               | 1         | 0.43%   |
| LincPlus                             | 1         | 0.43%   |
| LG Electronics                       | 1         | 0.43%   |
| IPASON                               | 1         | 0.43%   |
| HYPERPC                              | 1         | 0.43%   |
| HONOR                                | 1         | 0.43%   |
| Compaq                               | 1         | 0.43%   |
| Chuwi                                | 1         | 0.43%   |
| CCE                                  | 1         | 0.43%   |
| AZW                                  | 1         | 0.43%   |
| AMI                                  | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 3         | 1.28%   |
| RPi Raspberry Pi                           | 2         | 0.85%   |
| HP EliteDesk 800 G1 SFF                    | 2         | 0.85%   |
| HP Compaq Elite 8300 SFF                   | 2         | 0.85%   |
| Hardkernel ODROID-N2Plus                   | 2         | 0.85%   |
| ASUS M5A78L LE                             | 2         | 0.85%   |
| TYAN S7012                                 | 1         | 0.43%   |
| TrekStor Surfbook A13B                     | 1         | 0.43%   |
| Toshiba Satellite P50-B-10Z                | 1         | 0.43%   |
| Toshiba Satellite C50D-A-133               | 1         | 0.43%   |
| Sony VPCEH1E1E                             | 1         | 0.43%   |
| Sony VPCEB2Z1E                             | 1         | 0.43%   |
| Sony VPCEA36FG                             | 1         | 0.43%   |
| Sony VGN-Z21WRN_B                          | 1         | 0.43%   |
| Sony SVF13N2J2ES                           | 1         | 0.43%   |
| SLIMBOOK TITAN                             | 1         | 0.43%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1         | 0.43%   |
| Samsung 905S3G/906S3G/915S3G/9305SG        | 1         | 0.43%   |
| RCA W101AS23T2                             | 1         | 0.43%   |
| RPi Raspberry Pi 400 Rev 1.1               | 1         | 0.43%   |
| Notebook NJx0MU                            | 1         | 0.43%   |
| MSI p6-2330                                | 1         | 0.43%   |
| MSI MS-AA5E                                | 1         | 0.43%   |
| MSI MS-7D43                                | 1         | 0.43%   |
| MSI MS-7C56                                | 1         | 0.43%   |
| MSI MS-7C52                                | 1         | 0.43%   |
| MSI MS-7C37                                | 1         | 0.43%   |
| MSI MS-7C09                                | 1         | 0.43%   |
| MSI MS-7C02                                | 1         | 0.43%   |
| MSI MS-7A33                                | 1         | 0.43%   |
| MSI MS-7982                                | 1         | 0.43%   |
| MSI MS-7918                                | 1         | 0.43%   |
| MSI MS-7817                                | 1         | 0.43%   |
| MSI MS-7758                                | 1         | 0.43%   |
| MSI MS-7599                                | 1         | 0.43%   |
| MSI B02311                                 | 1         | 0.43%   |
| Microsoft Surface 2                        | 1         | 0.43%   |
| MicroByte ezbook                           | 1         | 0.43%   |
| Medion MS-7797                             | 1         | 0.43%   |
| LincPlus LINNCPLUS P1                      | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 11        | 4.68%   |
| HP Pavilion              | 8         | 3.4%    |
| Dell Latitude            | 8         | 3.4%    |
| Lenovo IdeaPad           | 6         | 2.55%   |
| HP Compaq                | 6         | 2.55%   |
| ASUS PRIME               | 6         | 2.55%   |
| Acer Aspire              | 6         | 2.55%   |
| Dell Precision           | 5         | 2.13%   |
| Dell Inspiron            | 5         | 2.13%   |
| HP EliteDesk             | 4         | 1.7%    |
| HP EliteBook             | 4         | 1.7%    |
| ASUS ROG                 | 4         | 1.7%    |
| RPi Raspberry            | 3         | 1.28%   |
| HP Laptop                | 3         | 1.28%   |
| Dell OptiPlex            | 3         | 1.28%   |
| ASUS VivoBook            | 3         | 1.28%   |
| ASUS ASUS                | 3         | 1.28%   |
| Unknown                  | 3         | 1.28%   |
| Toshiba Satellite        | 2         | 0.85%   |
| Lenovo ThinkCentre       | 2         | 0.85%   |
| Lenovo ThinkBook         | 2         | 0.85%   |
| HP ZBook                 | 2         | 0.85%   |
| HP Stream                | 2         | 0.85%   |
| HP ProLiant              | 2         | 0.85%   |
| HP ProBook               | 2         | 0.85%   |
| HP ENVY                  | 2         | 0.85%   |
| HP 15                    | 2         | 0.85%   |
| Hardkernel ODROID-N2Plus | 2         | 0.85%   |
| Dell XPS                 | 2         | 0.85%   |
| ASUS TUF                 | 2         | 0.85%   |
| ASUS M5A78L-M            | 2         | 0.85%   |
| ASUS M5A78L              | 2         | 0.85%   |
| Apple iMac12             | 2         | 0.85%   |
| Acer TravelMate          | 2         | 0.85%   |
| TYAN S7012               | 1         | 0.43%   |
| TrekStor Surfbook        | 1         | 0.43%   |
| Sony VPCEH1E1E           | 1         | 0.43%   |
| Sony VPCEB2Z1E           | 1         | 0.43%   |
| Sony VPCEA36FG           | 1         | 0.43%   |
| Sony VGN-Z21WRN          | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 33        | 14.04%  |
| 2018    | 23        | 9.79%   |
| 2012    | 20        | 8.51%   |
| 2020    | 17        | 7.23%   |
| 2013    | 17        | 7.23%   |
| 2019    | 16        | 6.81%   |
| 2011    | 16        | 6.81%   |
| 2022    | 15        | 6.38%   |
| 2014    | 12        | 5.11%   |
| 2010    | 11        | 4.68%   |
| 2015    | 10        | 4.26%   |
| 2017    | 9         | 3.83%   |
| 2016    | 9         | 3.83%   |
| 2009    | 9         | 3.83%   |
| 2008    | 7         | 2.98%   |
| Unknown | 5         | 2.13%   |
| 2007    | 3         | 1.28%   |
| 2006    | 2         | 0.85%   |
| 2023    | 1         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 118       | 50.21%  |
| Desktop        | 92        | 39.15%  |
| All in one     | 6         | 2.55%   |
| System on chip | 5         | 2.13%   |
| Mini pc        | 5         | 2.13%   |
| Tablet         | 4         | 1.7%    |
| Convertible    | 4         | 1.7%    |
| Server         | 1         | 0.43%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 221       | 92.86%  |
| Enabled  | 17        | 7.14%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 232       | 98.72%  |
| Yes  | 3         | 1.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 53        | 22.55%  |
| 3.01-4.0    | 47        | 20%     |
| 8.01-16.0   | 43        | 18.3%   |
| 16.01-24.0  | 40        | 17.02%  |
| 32.01-64.0  | 26        | 11.06%  |
| 64.01-256.0 | 11        | 4.68%   |
| 24.01-32.0  | 7         | 2.98%   |
| 1.01-2.0    | 5         | 2.13%   |
| 2.01-3.0    | 3         | 1.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 80        | 31.87%  |
| 2.01-3.0   | 73        | 29.08%  |
| 4.01-8.0   | 39        | 15.54%  |
| 3.01-4.0   | 31        | 12.35%  |
| 8.01-16.0  | 15        | 5.98%   |
| 0.51-1.0   | 10        | 3.98%   |
| 24.01-32.0 | 2         | 0.8%    |
| 32.01-64.0 | 1         | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 139       | 59.15%  |
| 2      | 49        | 20.85%  |
| 3      | 25        | 10.64%  |
| 4      | 11        | 4.68%   |
| 6      | 5         | 2.13%   |
| 5      | 2         | 0.85%   |
| 20     | 1         | 0.43%   |
| 8      | 1         | 0.43%   |
| 7      | 1         | 0.43%   |
| 0      | 1         | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 128       | 54.47%  |
| Yes       | 107       | 45.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 193       | 82.13%  |
| No        | 42        | 17.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 181       | 77.02%  |
| No        | 54        | 22.98%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 151       | 63.98%  |
| No        | 85        | 36.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 35        | 14.89%  |
| Germany     | 33        | 14.04%  |
| France      | 31        | 13.19%  |
| Italy       | 20        | 8.51%   |
| Brazil      | 10        | 4.26%   |
| Spain       | 8         | 3.4%    |
| Russia      | 8         | 3.4%    |
| Canada      | 7         | 2.98%   |
| Australia   | 7         | 2.98%   |
| UK          | 5         | 2.13%   |
| Turkey      | 4         | 1.7%    |
| Portugal    | 4         | 1.7%    |
| Hungary     | 4         | 1.7%    |
| Greece      | 4         | 1.7%    |
| Finland     | 4         | 1.7%    |
| Belgium     | 4         | 1.7%    |
| Switzerland | 3         | 1.28%   |
| Poland      | 3         | 1.28%   |
| Estonia     | 3         | 1.28%   |
| Croatia     | 3         | 1.28%   |
| Austria     | 3         | 1.28%   |
| Ukraine     | 2         | 0.85%   |
| Serbia      | 2         | 0.85%   |
| Netherlands | 2         | 0.85%   |
| Mexico      | 2         | 0.85%   |
| Denmark     | 2         | 0.85%   |
| Czechia     | 2         | 0.85%   |
| Argentina   | 2         | 0.85%   |
| Thailand    | 1         | 0.43%   |
| Taiwan      | 1         | 0.43%   |
| Slovenia    | 1         | 0.43%   |
| Romania     | 1         | 0.43%   |
| Peru        | 1         | 0.43%   |
| Paraguay    | 1         | 0.43%   |
| New Zealand | 1         | 0.43%   |
| Morocco     | 1         | 0.43%   |
| Libya       | 1         | 0.43%   |
| Israel      | 1         | 0.43%   |
| Isle of Man | 1         | 0.43%   |
| India       | 1         | 0.43%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Paris             | 4         | 1.63%   |
| Berlin            | 4         | 1.63%   |
| Wittingen         | 3         | 1.22%   |
| Rome              | 3         | 1.22%   |
| Moscow            | 3         | 1.22%   |
| Mannheim          | 3         | 1.22%   |
| Zagreb            | 2         | 0.82%   |
| West Stockbridge  | 2         | 0.82%   |
| Warsaw            | 2         | 0.82%   |
| Vancouver         | 2         | 0.82%   |
| Turku             | 2         | 0.82%   |
| Sao Paulo         | 2         | 0.82%   |
| Olathe            | 2         | 0.82%   |
| Melbourne         | 2         | 0.82%   |
| Madrid            | 2         | 0.82%   |
| Macon             | 2         | 0.82%   |
| Lansdale          | 2         | 0.82%   |
| Frankfurt am Main | 2         | 0.82%   |
| Cologne           | 2         | 0.82%   |
| Belgrade          | 2         | 0.82%   |
| Zottegem          | 1         | 0.41%   |
| Zográfos         | 1         | 0.41%   |
| York              | 1         | 0.41%   |
| Xining            | 1         | 0.41%   |
| Wuelfrath         | 1         | 0.41%   |
| Whanganui         | 1         | 0.41%   |
| Wellin            | 1         | 0.41%   |
| Weiden            | 1         | 0.41%   |
| Washington        | 1         | 0.41%   |
| Voronezh          | 1         | 0.41%   |
| Viroflay          | 1         | 0.41%   |
| Villeurbanne      | 1         | 0.41%   |
| Villefontaine     | 1         | 0.41%   |
| Viljandi          | 1         | 0.41%   |
| Victoria          | 1         | 0.41%   |
| Viana do Castelo  | 1         | 0.41%   |
| Versailles        | 1         | 0.41%   |
| Velyki Mosty      | 1         | 0.41%   |
| Vaudoy-en-Brie    | 1         | 0.41%   |
| Varna             | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 56        | 97     | 16.09%  |
| Seagate               | 45        | 71     | 12.93%  |
| WDC                   | 42        | 63     | 12.07%  |
| Unknown               | 22        | 31     | 6.32%   |
| Crucial               | 21        | 27     | 6.03%   |
| SanDisk               | 18        | 23     | 5.17%   |
| Toshiba               | 17        | 42     | 4.89%   |
| Kingston              | 17        | 23     | 4.89%   |
| SK hynix              | 9         | 9      | 2.59%   |
| A-DATA Technology     | 8         | 8      | 2.3%    |
| Hitachi               | 7         | 8      | 2.01%   |
| Phison                | 6         | 6      | 1.72%   |
| China                 | 5         | 5      | 1.44%   |
| SPCC                  | 4         | 8      | 1.15%   |
| KIOXIA                | 4         | 4      | 1.15%   |
| Intel                 | 4         | 4      | 1.15%   |
| Phison Electronics    | 3         | 3      | 0.86%   |
| Micron Technology     | 3         | 3      | 0.86%   |
| KingSpec              | 3         | 3      | 0.86%   |
| Intenso               | 3         | 3      | 0.86%   |
| HGST                  | 3         | 3      | 0.86%   |
| Unknown               | 3         | 3      | 0.86%   |
| OCZ                   | 2         | 2      | 0.57%   |
| Netac                 | 2         | 2      | 0.57%   |
| Hewlett-Packard       | 2         | 3      | 0.57%   |
| Corsair               | 2         | 2      | 0.57%   |
| ZXIC MMC              | 1         | 1      | 0.29%   |
| WDC WDS2              | 1         | 1      | 0.29%   |
| Verbatim              | 1         | 4      | 0.29%   |
| UMIS                  | 1         | 2      | 0.29%   |
| Transcend             | 1         | 4      | 0.29%   |
| Team                  | 1         | 1      | 0.29%   |
| SSSTC                 | 1         | 1      | 0.29%   |
| Silicon Motion        | 1         | 1      | 0.29%   |
| RZX                   | 1         | 1      | 0.29%   |
| Realtek Semiconductor | 1         | 2      | 0.29%   |
| PNY                   | 1         | 1      | 0.29%   |
| Pichau                | 1         | 1      | 0.29%   |
| Patriot               | 1         | 1      | 0.29%   |
| NGFF                  | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 6         | 1.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 5         | 1.27%   |
| Unknown MMC Card  32GB                              | 4         | 1.01%   |
| Kingston SA400S37480G 480GB SSD                     | 4         | 1.01%   |
| Crucial CT240BX500SSD1 240GB                        | 4         | 1.01%   |
| Crucial CT2000MX500SSD1 2TB                         | 4         | 1.01%   |
| Crucial CT1000BX500SSD1 1TB                         | 4         | 1.01%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 3         | 0.76%   |
| Toshiba MQ01ABF050 500GB                            | 3         | 0.76%   |
| Seagate ST2000DM008-2FR102 2TB                      | 3         | 0.76%   |
| Seagate ST2000DM001-1ER164 2TB                      | 3         | 0.76%   |
| Seagate ST1000DM003-1ER162 1TB                      | 3         | 0.76%   |
| Samsung SSD 870 QVO 1TB                             | 3         | 0.76%   |
| Samsung SSD 870 EVO 500GB                           | 3         | 0.76%   |
| Samsung NVMe SSD Drive 1TB                          | 3         | 0.76%   |
| Kingston SA400S37120G 120GB SSD                     | 3         | 0.76%   |
| Unknown                                             | 3         | 0.76%   |
| WDC WD40EZAZ-00SF3B0 4TB                            | 2         | 0.51%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 2         | 0.51%   |
| Unknown SD/MMC 2GB                                  | 2         | 0.51%   |
| Unknown M.S./M.S.Pro/HG 16GB                        | 2         | 0.51%   |
| Seagate ST9500325AS 500GB                           | 2         | 0.51%   |
| Seagate ST4000DM004-2CV104 4TB                      | 2         | 0.51%   |
| Seagate ST2000LM015-2E8174 2TB                      | 2         | 0.51%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 0.51%   |
| SanDisk SSD PLUS 480GB                              | 2         | 0.51%   |
| Samsung SSD 980 PRO 500GB                           | 2         | 0.51%   |
| Samsung SSD 980 PRO 1TB                             | 2         | 0.51%   |
| Samsung SSD 980 1TB                                 | 2         | 0.51%   |
| Samsung SSD 970 EVO Plus 250GB                      | 2         | 0.51%   |
| Samsung SSD 870 QVO 2TB                             | 2         | 0.51%   |
| Samsung SSD 860 QVO 1TB                             | 2         | 0.51%   |
| Samsung SSD 860 EVO 500GB                           | 2         | 0.51%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.51%   |
| Samsung SSD 850 EVO 250GB                           | 2         | 0.51%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                    | 2         | 0.51%   |
| Crucial CT480BX500SSD1 480GB                        | 2         | 0.51%   |
| A-DATA SU800 256GB SSD                              | 2         | 0.51%   |
| ZXIC MMC Storage 2.31 128GB                         | 1         | 0.25%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 45        | 71     | 39.47%  |
| WDC                 | 38        | 57     | 33.33%  |
| Toshiba             | 13        | 37     | 11.4%   |
| Hitachi             | 7         | 8      | 6.14%   |
| Samsung Electronics | 3         | 8      | 2.63%   |
| HGST                | 3         | 3      | 2.63%   |
| Maxtor              | 1         | 1      | 0.88%   |
| KESU                | 1         | 1      | 0.88%   |
| Hewlett-Packard     | 1         | 2      | 0.88%   |
| DAS                 | 1         | 6      | 0.88%   |
| ASMedia             | 1         | 1      | 0.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 42     | 24.03%  |
| Crucial             | 20        | 26     | 15.5%   |
| Kingston            | 12        | 17     | 9.3%    |
| SanDisk             | 11        | 14     | 8.53%   |
| A-DATA Technology   | 7         | 7      | 5.43%   |
| China               | 5         | 5      | 3.88%   |
| WDC                 | 3         | 3      | 2.33%   |
| SPCC                | 3         | 7      | 2.33%   |
| KingSpec            | 3         | 3      | 2.33%   |
| Toshiba             | 2         | 3      | 1.55%   |
| OCZ                 | 2         | 2      | 1.55%   |
| Intenso             | 2         | 2      | 1.55%   |
| WDC WDS2            | 1         | 1      | 0.78%   |
| Verbatim            | 1         | 4      | 0.78%   |
| Unknown             | 1         | 1      | 0.78%   |
| Transcend           | 1         | 4      | 0.78%   |
| Team                | 1         | 1      | 0.78%   |
| SK hynix            | 1         | 1      | 0.78%   |
| RZX                 | 1         | 1      | 0.78%   |
| PNY                 | 1         | 1      | 0.78%   |
| Pichau              | 1         | 1      | 0.78%   |
| Patriot             | 1         | 1      | 0.78%   |
| NGFF                | 1         | 1      | 0.78%   |
| Netac               | 1         | 1      | 0.78%   |
| Micron Technology   | 1         | 1      | 0.78%   |
| LITEONIT            | 1         | 1      | 0.78%   |
| LITEON              | 1         | 1      | 0.78%   |
| LDLC                | 1         | 1      | 0.78%   |
| Kston               | 1         | 1      | 0.78%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.78%   |
| KingFast            | 1         | 1      | 0.78%   |
| Intel               | 1         | 1      | 0.78%   |
| GOODRAM             | 1         | 1      | 0.78%   |
| Corsair             | 1         | 1      | 0.78%   |
| BAITITON            | 1         | 1      | 0.78%   |
| ASMT                | 1         | 1      | 0.78%   |
| Apple               | 1         | 1      | 0.78%   |
| Apacer              | 1         | 1      | 0.78%   |
| addlink             | 1         | 1      | 0.78%   |
| Unknown             | 1         | 1      | 0.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 112       | 165    | 35.44%  |
| HDD     | 97        | 195    | 30.7%   |
| NVMe    | 82        | 110    | 25.95%  |
| MMC     | 19        | 26     | 6.01%   |
| Unknown | 6         | 10     | 1.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 162       | 335    | 57.04%  |
| NVMe | 81        | 109    | 28.52%  |
| SAS  | 22        | 36     | 7.75%   |
| MMC  | 19        | 26     | 6.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 125       | 182    | 54.59%  |
| 0.51-1.0   | 59        | 96     | 25.76%  |
| 1.01-2.0   | 23        | 32     | 10.04%  |
| 3.01-4.0   | 11        | 13     | 4.8%    |
| 4.01-10.0  | 7         | 29     | 3.06%   |
| 2.01-3.0   | 4         | 8      | 1.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 67        | 27.57%  |
| 251-500        | 54        | 22.22%  |
| 501-1000       | 33        | 13.58%  |
| 1001-2000      | 19        | 7.82%   |
| More than 3000 | 18        | 7.41%   |
| 21-50          | 15        | 6.17%   |
| 51-100         | 13        | 5.35%   |
| 1-20           | 11        | 4.53%   |
| 2001-3000      | 10        | 4.12%   |
| Unknown        | 3         | 1.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 68        | 28.22%  |
| 21-50          | 42        | 17.43%  |
| 101-250        | 36        | 14.94%  |
| 51-100         | 29        | 12.03%  |
| 501-1000       | 18        | 7.47%   |
| 251-500        | 16        | 6.64%   |
| 1001-2000      | 12        | 4.98%   |
| More than 3000 | 11        | 4.56%   |
| 2001-3000      | 6         | 2.49%   |
| Unknown        | 3         | 1.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB              | 3         | 3      | 10.34%  |
| WDC WD5000AADS-00S9B0 500GB                  | 1         | 1      | 3.45%   |
| WDC WD10EAVS-00D7B0 1TB                      | 1         | 1      | 3.45%   |
| WDC WD1001FALS-40Y6A0 1TB                    | 1         | 1      | 3.45%   |
| Toshiba MK3263GSXN 320GB                     | 1         | 1      | 3.45%   |
| SK hynix BC711 HFM512GD3JX013N 512GB         | 1         | 1      | 3.45%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 3.45%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 3.45%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 3.45%   |
| Seagate ST3250312AS 250GB                    | 1         | 1      | 3.45%   |
| Seagate ST2000DM001-1ER164 2TB               | 1         | 1      | 3.45%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 3.45%   |
| Seagate ST1000DM003-1ER162 1TB               | 1         | 1      | 3.45%   |
| Samsung Electronics SSD 960 PRO 1TB          | 1         | 1      | 3.45%   |
| Samsung Electronics SSD 870 EVO 500GB        | 1         | 1      | 3.45%   |
| Samsung Electronics MZVLQ512HBLU-00BH1 512GB | 1         | 1      | 3.45%   |
| OCZ VERTEX3 240GB SSD                        | 1         | 1      | 3.45%   |
| OCZ AGILITY3 240GB SSD                       | 1         | 1      | 3.45%   |
| NGFF 2280 256GB SSD                          | 1         | 1      | 3.45%   |
| Netac SSD 256GB                              | 1         | 1      | 3.45%   |
| Kingston SA400S37240G 240GB SSD              | 1         | 1      | 3.45%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD      | 1         | 1      | 3.45%   |
| Intel SSDSC2KW512G8 512GB                    | 1         | 1      | 3.45%   |
| Hitachi HTS725032A9A364 320GB                | 1         | 1      | 3.45%   |
| Hitachi HTS721080G9SA00 80GB                 | 1         | 1      | 3.45%   |
| DAS TerraMaster 500GB                        | 1         | 3      | 3.45%   |
| China SSD 180GB                              | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 34.48%  |
| WDC                 | 3         | 3      | 10.34%  |
| Samsung Electronics | 3         | 3      | 10.34%  |
| OCZ                 | 2         | 2      | 6.9%    |
| Kingston            | 2         | 2      | 6.9%    |
| Hitachi             | 2         | 2      | 6.9%    |
| Toshiba             | 1         | 1      | 3.45%   |
| SK hynix            | 1         | 1      | 3.45%   |
| NGFF                | 1         | 1      | 3.45%   |
| Netac               | 1         | 1      | 3.45%   |
| Intel               | 1         | 1      | 3.45%   |
| DAS                 | 1         | 3      | 3.45%   |
| China               | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 10     | 58.82%  |
| WDC     | 3         | 3      | 17.65%  |
| Hitachi | 2         | 2      | 11.76%  |
| Toshiba | 1         | 1      | 5.88%   |
| DAS     | 1         | 3      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 19     | 57.14%  |
| SSD  | 9         | 9      | 32.14%  |
| NVMe | 3         | 3      | 10.71%  |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 138       | 276    | 51.69%  |
| Detected | 101       | 199    | 37.83%  |
| Malfunc  | 28        | 31     | 10.49%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 137       | 47.4%   |
| AMD                            | 56        | 19.38%  |
| Samsung Electronics            | 28        | 9.69%   |
| Phison Electronics             | 11        | 3.81%   |
| SanDisk                        | 10        | 3.46%   |
| SK hynix                       | 7         | 2.42%   |
| Kingston Technology Company    | 6         | 2.08%   |
| ASMedia Technology             | 5         | 1.73%   |
| Silicon Motion                 | 4         | 1.38%   |
| KIOXIA                         | 4         | 1.38%   |
| Toshiba America Info Systems   | 3         | 1.04%   |
| Nvidia                         | 2         | 0.69%   |
| Micron Technology              | 2         | 0.69%   |
| Marvell Technology Group       | 2         | 0.69%   |
| JMicron Technology             | 2         | 0.69%   |
| ADATA Technology               | 2         | 0.69%   |
| Union Memory (Shenzhen)        | 1         | 0.35%   |
| Solid State Storage Technology | 1         | 0.35%   |
| Realtek Semiconductor          | 1         | 0.35%   |
| Micron/Crucial Technology      | 1         | 0.35%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.35%   |
| Lenovo                         | 1         | 0.35%   |
| Hewlett-Packard                | 1         | 0.35%   |
| Unknown                        | 1         | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 35        | 10.42%  |
| Samsung NVMe SSD Controller 980                                                | 12        | 3.57%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 10        | 2.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 2.68%   |
| Intel Volume Management Device NVMe RAID Controller                            | 9         | 2.68%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 9         | 2.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 7         | 2.08%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 2.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7         | 2.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 1.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 1.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 1.79%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 6         | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 6         | 1.79%   |
| AMD 400 Series Chipset SATA Controller                                         | 6         | 1.79%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 5         | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 1.49%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5         | 1.49%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 1.49%   |
| Phison E16 PCIe4 NVMe Controller                                               | 4         | 1.19%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.19%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 1.19%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 1.19%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 1.19%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.19%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 1.19%   |
| Phison PS5013 E13 NVMe Controller                                              | 3         | 0.89%   |
| Kingston Company NVMe Controller                                               | 3         | 0.89%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 0.89%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.89%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 0.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 0.89%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 0.89%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 2         | 0.6%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 0.6%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 0.6%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 168       | 56.38%  |
| NVMe | 81        | 27.18%  |
| IDE  | 28        | 9.4%    |
| RAID | 21        | 7.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 160       | 68.09%  |
| AMD    | 69        | 29.36%  |
| ARM    | 6         | 2.55%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 9 5900HX with Radeon Graphics       | 5         | 2.13%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.7%    |
| ARM Processor                                 | 4         | 1.7%    |
| Intel Core i7-3517U CPU @ 1.90GHz             | 3         | 1.28%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3         | 1.28%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 3         | 1.28%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.85%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 0.85%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.85%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.85%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 0.85%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.85%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 0.85%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 2         | 0.85%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.85%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 0.85%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 0.85%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.85%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 2         | 0.85%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 0.85%   |
| Intel 11th Gen Core i5-11600K @ 3.90GHz       | 2         | 0.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 0.85%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 0.85%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 0.85%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 0.85%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 0.85%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 2         | 0.85%   |
| AMD FX-6300 Six-Core Processor                | 2         | 0.85%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G | 2         | 0.85%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 2         | 0.85%   |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1         | 0.43%   |
| Intel Xeon CPU E5620 @ 2.40GHz                | 1         | 0.43%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz           | 1         | 0.43%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz            | 1         | 0.43%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.43%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz           | 1         | 0.43%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 46        | 19.57%  |
| Other                   | 29        | 12.34%  |
| Intel Core i7           | 29        | 12.34%  |
| Intel Core i3           | 17        | 7.23%   |
| AMD Ryzen 5             | 17        | 7.23%   |
| Intel Celeron           | 14        | 5.96%   |
| Intel Core 2 Duo        | 10        | 4.26%   |
| Intel Pentium           | 8         | 3.4%    |
| AMD Ryzen 7             | 8         | 3.4%    |
| Intel Xeon              | 6         | 2.55%   |
| AMD Ryzen 9             | 5         | 2.13%   |
| AMD FX                  | 4         | 1.7%    |
| AMD A8                  | 4         | 1.7%    |
| AMD A6                  | 4         | 1.7%    |
| AMD Ryzen 3             | 3         | 1.28%   |
| AMD Athlon II X2        | 3         | 1.28%   |
| AMD A4                  | 3         | 1.28%   |
| AMD Ryzen 7 PRO         | 2         | 0.85%   |
| AMD E                   | 2         | 0.85%   |
| Intel Pentium Silver    | 1         | 0.43%   |
| Intel Pentium Dual-Core | 1         | 0.43%   |
| Intel Pentium 4         | 1         | 0.43%   |
| Intel Core m5           | 1         | 0.43%   |
| Intel Core 2 Quad       | 1         | 0.43%   |
| Intel Atom              | 1         | 0.43%   |
| ARM BCM                 | 1         | 0.43%   |
| AMD Turion II Neo       | 1         | 0.43%   |
| AMD Turion 64 X2 Mobile | 1         | 0.43%   |
| AMD Turion 64 Mobile    | 1         | 0.43%   |
| AMD Sempron             | 1         | 0.43%   |
| AMD Ryzen 5 PRO         | 1         | 0.43%   |
| AMD Quad-Core           | 1         | 0.43%   |
| AMD Phenom II X6        | 1         | 0.43%   |
| AMD E2                  | 1         | 0.43%   |
| AMD E1                  | 1         | 0.43%   |
| AMD Athlon X2           | 1         | 0.43%   |
| AMD Athlon II X4        | 1         | 0.43%   |
| AMD Athlon II           | 1         | 0.43%   |
| AMD Athlon              | 1         | 0.43%   |
| AMD A10                 | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 88        | 37.45%  |
| 2       | 85        | 36.17%  |
| 6       | 24        | 10.21%  |
| 8       | 18        | 7.66%   |
| 1       | 5         | 2.13%   |
| 12      | 4         | 1.7%    |
| 10      | 3         | 1.28%   |
| 3       | 3         | 1.28%   |
| 14      | 2         | 0.85%   |
| Unknown | 2         | 0.85%   |
| 16      | 1         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 230       | 97.87%  |
| 2       | 3         | 1.28%   |
| Unknown | 2         | 0.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 145       | 61.7%   |
| 1       | 88        | 37.45%  |
| Unknown | 2         | 0.85%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 233       | 99.15%  |
| Unknown        | 2         | 0.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 92        | 38.02%  |
| 0x306a9    | 10        | 4.13%   |
| 0x206a7    | 9         | 3.72%   |
| 0x806c1    | 8         | 3.31%   |
| 0x0a50000c | 7         | 2.89%   |
| 0x806ec    | 6         | 2.48%   |
| 0x40651    | 6         | 2.48%   |
| 0x506e3    | 5         | 2.07%   |
| 0x306c3    | 5         | 2.07%   |
| 0x08108109 | 5         | 2.07%   |
| 0x806ea    | 4         | 1.65%   |
| 0xa0671    | 3         | 1.24%   |
| 0x906ea    | 3         | 1.24%   |
| 0x906e9    | 3         | 1.24%   |
| 0x806d1    | 3         | 1.24%   |
| 0x406e3    | 3         | 1.24%   |
| 0x406c4    | 3         | 1.24%   |
| 0x30678    | 3         | 1.24%   |
| 0x20655    | 3         | 1.24%   |
| 0x1067a    | 3         | 1.24%   |
| 0x0800820d | 3         | 1.24%   |
| 0x0700010f | 3         | 1.24%   |
| 0x05000119 | 3         | 1.24%   |
| 0x906a3    | 2         | 0.83%   |
| 0x90672    | 2         | 0.83%   |
| 0x806eb    | 2         | 0.83%   |
| 0x806e9    | 2         | 0.83%   |
| 0x706e5    | 2         | 0.83%   |
| 0x706a8    | 2         | 0.83%   |
| 0x706a1    | 2         | 0.83%   |
| 0x6fd      | 2         | 0.83%   |
| 0x506c9    | 2         | 0.83%   |
| 0x106e5    | 2         | 0.83%   |
| 0x10676    | 2         | 0.83%   |
| 0x0a50000d | 2         | 0.83%   |
| 0x08608103 | 2         | 0.83%   |
| 0x06001119 | 2         | 0.83%   |
| 0x010000c8 | 2         | 0.83%   |
| 0xa0653    | 1         | 0.41%   |
| 0x906ed    | 1         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 28        | 11.81%  |
| Haswell          | 18        | 7.59%   |
| IvyBridge        | 17        | 7.17%   |
| Unknown          | 17        | 7.17%   |
| SandyBridge      | 14        | 5.91%   |
| Zen 3            | 12        | 5.06%   |
| Zen+             | 10        | 4.22%   |
| Skylake          | 10        | 4.22%   |
| TigerLake        | 9         | 3.8%    |
| Icelake          | 9         | 3.8%    |
| Westmere         | 8         | 3.38%   |
| Silvermont       | 8         | 3.38%   |
| Penryn           | 8         | 3.38%   |
| K10              | 8         | 3.38%   |
| Zen 2            | 6         | 2.53%   |
| Zen              | 6         | 2.53%   |
| Goldmont plus    | 6         | 2.53%   |
| Piledriver       | 5         | 2.11%   |
| Excavator        | 5         | 2.11%   |
| Alderlake Hybrid | 5         | 2.11%   |
| Core             | 4         | 1.69%   |
| Nehalem          | 3         | 1.27%   |
| Jaguar           | 3         | 1.27%   |
| CometLake        | 3         | 1.27%   |
| Bobcat           | 3         | 1.27%   |
| Puma             | 2         | 0.84%   |
| K8 Hammer        | 2         | 0.84%   |
| Goldmont         | 2         | 0.84%   |
| Bulldozer        | 2         | 0.84%   |
| Steamroller      | 1         | 0.42%   |
| NetBurst         | 1         | 0.42%   |
| K8 & K10 hybrid  | 1         | 0.42%   |
| Broadwell        | 1         | 0.42%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 125       | 46.99%  |
| AMD                        | 78        | 29.32%  |
| Nvidia                     | 61        | 22.93%  |
| Matrox Electronics Systems | 1         | 0.38%   |
| ASPEED Technology          | 1         | 0.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 3.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 3.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 9         | 3.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 2.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.22%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 2.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 1.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 1.85%   |
| Intel HD Graphics 530                                                                    | 5         | 1.85%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 4         | 1.48%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 1.48%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 1.48%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.48%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.48%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1.48%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 3         | 1.11%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.11%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.11%   |
| Intel HD Graphics 620                                                                    | 3         | 1.11%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.11%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.11%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 3         | 1.11%   |
| AMD Renoir                                                                               | 3         | 1.11%   |
| AMD Lucienne                                                                             | 3         | 1.11%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 1.11%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.74%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.74%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.74%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 0.74%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.74%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 0.74%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 2         | 0.74%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 0.74%   |
| Intel HD Graphics 630                                                                    | 2         | 0.74%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 95        | 40.43%  |
| 1 x AMD        | 61        | 25.96%  |
| 1 x Nvidia     | 36        | 15.32%  |
| Intel + Nvidia | 19        | 8.09%   |
| Intel + AMD    | 7         | 2.98%   |
| Other          | 6         | 2.55%   |
| AMD + Nvidia   | 6         | 2.55%   |
| 2 x AMD        | 3         | 1.28%   |
| 1 x Matrox     | 1         | 0.43%   |
| AMD + ASPEED   | 1         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 184       | 78.3%   |
| Proprietary | 39        | 16.6%   |
| Unknown     | 12        | 5.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 154       | 65.25%  |
| 0.01-0.5   | 27        | 11.44%  |
| 0.51-1.0   | 19        | 8.05%   |
| 1.01-2.0   | 16        | 6.78%   |
| 3.01-4.0   | 8         | 3.39%   |
| 7.01-8.0   | 5         | 2.12%   |
| 5.01-6.0   | 5         | 2.12%   |
| 2.01-3.0   | 1         | 0.42%   |
| 8.01-16.0  | 1         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 39        | 14.83%  |
| BOE                     | 24        | 9.13%   |
| Chimei Innolux          | 23        | 8.75%   |
| Goldstar                | 18        | 6.84%   |
| AU Optronics            | 17        | 6.46%   |
| LG Display              | 15        | 5.7%    |
| Dell                    | 15        | 5.7%    |
| Philips                 | 10        | 3.8%    |
| Hewlett-Packard         | 10        | 3.8%    |
| Acer                    | 10        | 3.8%    |
| Iiyama                  | 7         | 2.66%   |
| BenQ                    | 7         | 2.66%   |
| Apple                   | 7         | 2.66%   |
| Ancor Communications    | 7         | 2.66%   |
| Lenovo                  | 4         | 1.52%   |
| Chi Mei Optoelectronics | 4         | 1.52%   |
| AOC                     | 4         | 1.52%   |
| ViewSonic               | 3         | 1.14%   |
| Sony                    | 3         | 1.14%   |
| Sharp                   | 3         | 1.14%   |
| PANDA                   | 3         | 1.14%   |
| Vizio                   | 2         | 0.76%   |
| Westinghouse            | 1         | 0.38%   |
| VMO                     | 1         | 0.38%   |
| Vita                    | 1         | 0.38%   |
| Unknown                 | 1         | 0.38%   |
| Toshiba                 | 1         | 0.38%   |
| SNC                     | 1         | 0.38%   |
| Sceptre Tech            | 1         | 0.38%   |
| Quanta Display          | 1         | 0.38%   |
| Panasonic               | 1         | 0.38%   |
| Packard Bell            | 1         | 0.38%   |
| NEC Computers           | 1         | 0.38%   |
| MSI                     | 1         | 0.38%   |
| Medion                  | 1         | 0.38%   |
| LGD                     | 1         | 0.38%   |
| LG Philips              | 1         | 0.38%   |
| Lenovo Group Limited    | 1         | 0.38%   |
| Kogan                   | 1         | 0.38%   |
| Insignia                | 1         | 0.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch        | 3         | 1.12%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                 | 2         | 0.75%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch  | 2         | 0.75%   |
| Goldstar E2240 GSM57A3 1920x1080 477x268mm 21.5-inch                  | 2         | 0.75%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                 | 2         | 0.75%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                     | 2         | 0.75%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.75%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                 | 2         | 0.75%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 2         | 0.75%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 2         | 0.75%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 2         | 0.75%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                | 2         | 0.75%   |
| Acer K272HL H ACR087E 1920x1080 597x336mm 27.0-inch                   | 2         | 0.75%   |
| Acer ET322QU ACR0687 2560x1440 698x393mm 31.5-inch                    | 2         | 0.75%   |
| Westinghouse DWM40F1D1 WDT7811 1920x1080 890x500mm 40.2-inch          | 1         | 0.37%   |
| VMO LCD WQXGA HDM VMO1506 2560x1600 1600x1000mm 74.3-inch             | 1         | 0.37%   |
| Vizio M470NV VIZ0063 1920x1080 1040x585mm 47.0-inch                   | 1         | 0.37%   |
| Vizio D32x-D1 VIZ1005 1920x1080 698x392mm 31.5-inch                   | 1         | 0.37%   |
| Vita LCD Monitor VIT0780 1920x1080                                    | 1         | 0.37%   |
| ViewSonic VP2765 SERIES VSC9F28 1920x1080 598x336mm 27.0-inch         | 1         | 0.37%   |
| ViewSonic VA2431 Series VSCD824 1920x1080 521x293mm 23.5-inch         | 1         | 0.37%   |
| ViewSonic VA2046 SERIES VSC6D2E 1600x900 432x240mm 19.5-inch          | 1         | 0.37%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                  | 1         | 0.37%   |
| Toshiba LCD Monitor LCD2109 1280x800 261x163mm 12.1-inch              | 1         | 0.37%   |
| Sony LCD Monitor TV 3840x1080                                         | 1         | 0.37%   |
| Sony LCD Monitor TV                                                   | 1         | 0.37%   |
| SNC SKP_E20-32 SNC3200 1920x1080 477x268mm 21.5-inch                  | 1         | 0.37%   |
| Sharp LQ156M1JW26 SHP1532 1920x1080 344x194mm 15.5-inch               | 1         | 0.37%   |
| Sharp LCD Monitor SHP1526 1920x1280 274x183mm 13.0-inch               | 1         | 0.37%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 0.37%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                | 1         | 0.37%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch  | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM0225 1440x900 410x257mm 19.1-inch   | 1         | 0.37%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 598x336mm 27.0-inch   | 1         | 0.37%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch    | 1         | 0.37%   |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 477x268mm 21.5-inch    | 1         | 0.37%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch | 1         | 0.37%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 1         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 114       | 47.3%   |
| 1366x768 (WXGA)    | 42        | 17.43%  |
| 2560x1440 (QHD)    | 15        | 6.22%   |
| 3840x2160 (4K)     | 14        | 5.81%   |
| 1440x900 (WXGA+)   | 8         | 3.32%   |
| 1680x1050 (WSXGA+) | 7         | 2.9%    |
| 1600x900 (HD+)     | 5         | 2.07%   |
| 1280x800 (WXGA)    | 5         | 2.07%   |
| 3440x1440          | 4         | 1.66%   |
| 1280x1024 (SXGA)   | 4         | 1.66%   |
| 2560x1600          | 3         | 1.24%   |
| Unknown            | 3         | 1.24%   |
| 3840x2400          | 2         | 0.83%   |
| 3840x1080          | 2         | 0.83%   |
| 2160x1440          | 2         | 0.83%   |
| 1920x1280          | 2         | 0.83%   |
| 1920x1200 (WUXGA)  | 2         | 0.83%   |
| 1360x768           | 2         | 0.83%   |
| 3840x1600          | 1         | 0.41%   |
| 3840x1200          | 1         | 0.41%   |
| 2880x1620          | 1         | 0.41%   |
| 2560x1080          | 1         | 0.41%   |
| 1280x720 (HD)      | 1         | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 59        | 22.96%  |
| 27      | 31        | 12.06%  |
| 21      | 22        | 8.56%   |
| 23      | 20        | 7.78%   |
| 24      | 19        | 7.39%   |
| 13      | 18        | 7%      |
| 17      | 17        | 6.61%   |
| 14      | 16        | 6.23%   |
| 31      | 10        | 3.89%   |
| Unknown | 7         | 2.72%   |
| 34      | 5         | 1.95%   |
| 19      | 5         | 1.95%   |
| 22      | 4         | 1.56%   |
| 18      | 4         | 1.56%   |
| 12      | 4         | 1.56%   |
| 54      | 3         | 1.17%   |
| 11      | 3         | 1.17%   |
| 38      | 2         | 0.78%   |
| 25      | 2         | 0.78%   |
| 84      | 1         | 0.39%   |
| 74      | 1         | 0.39%   |
| 72      | 1         | 0.39%   |
| 40      | 1         | 0.39%   |
| 28      | 1         | 0.39%   |
| 16      | 1         | 0.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 91        | 35.97%  |
| 501-600     | 64        | 25.3%   |
| 401-500     | 35        | 13.83%  |
| 601-700     | 16        | 6.32%   |
| 201-300     | 14        | 5.53%   |
| 351-400     | 12        | 4.74%   |
| Unknown     | 7         | 2.77%   |
| 701-800     | 5         | 1.98%   |
| 801-900     | 3         | 1.19%   |
| 1501-2000   | 3         | 1.19%   |
| 1001-1500   | 3         | 1.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 171       | 77.38%  |
| 16/10   | 30        | 13.57%  |
| 21/9    | 6         | 2.71%   |
| 5/4     | 5         | 2.26%   |
| Unknown | 5         | 2.26%   |
| 3/2     | 4         | 1.81%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 57        | 22.44%  |
| 201-250        | 51        | 20.08%  |
| 301-350        | 31        | 12.2%   |
| 81-90          | 29        | 11.42%  |
| 351-500        | 16        | 6.3%    |
| 151-200        | 11        | 4.33%   |
| 121-130        | 10        | 3.94%   |
| 141-150        | 9         | 3.54%   |
| 251-300        | 7         | 2.76%   |
| Unknown        | 7         | 2.76%   |
| More than 1000 | 6         | 2.36%   |
| 71-80          | 5         | 1.97%   |
| 61-70          | 4         | 1.57%   |
| 51-60          | 3         | 1.18%   |
| 501-1000       | 3         | 1.18%   |
| 131-140        | 2         | 0.79%   |
| 91-100         | 2         | 0.79%   |
| 111-120        | 1         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 90        | 36.89%  |
| 101-120       | 68        | 27.87%  |
| 121-160       | 56        | 22.95%  |
| 161-240       | 15        | 6.15%   |
| Unknown       | 7         | 2.87%   |
| 1-50          | 5         | 2.05%   |
| More than 240 | 3         | 1.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 177       | 74.37%  |
| 2     | 49        | 20.59%  |
| 0     | 7         | 2.94%   |
| 3     | 4         | 1.68%   |
| 4     | 1         | 0.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 139       | 41%     |
| Intel                             | 111       | 32.74%  |
| Qualcomm Atheros                  | 24        | 7.08%   |
| Broadcom                          | 22        | 6.49%   |
| Ralink                            | 5         | 1.47%   |
| MediaTek                          | 5         | 1.47%   |
| Broadcom Limited                  | 4         | 1.18%   |
| ASIX Electronics                  | 4         | 1.18%   |
| TP-Link                           | 3         | 0.88%   |
| Marvell Technology Group          | 3         | 0.88%   |
| Qualcomm Atheros Communications   | 2         | 0.59%   |
| Nvidia                            | 2         | 0.59%   |
| Ericsson Business Mobile Networks | 2         | 0.59%   |
| Xiaomi                            | 1         | 0.29%   |
| Raspberry Pi                      | 1         | 0.29%   |
| Quectel Wireless Solutions        | 1         | 0.29%   |
| Prolific Technology               | 1         | 0.29%   |
| NetGear                           | 1         | 0.29%   |
| Motorola PCS                      | 1         | 0.29%   |
| Microchip Technology              | 1         | 0.29%   |
| Lenovo                            | 1         | 0.29%   |
| DisplayLink                       | 1         | 0.29%   |
| D-Link System                     | 1         | 0.29%   |
| AVM                               | 1         | 0.29%   |
| ASUSTek Computer                  | 1         | 0.29%   |
| Aquantia                          | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 84        | 20.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 3.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 9         | 2.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 2.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 2.23%   |
| Intel Wireless 8265 / 8275                                        | 8         | 1.99%   |
| Realtek 802.11ac NIC                                              | 7         | 1.74%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 1.74%   |
| Intel Ethernet Controller I225-V                                  | 7         | 1.74%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 1.24%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.24%   |
| Intel Wireless 7265                                               | 5         | 1.24%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 1.24%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 0.99%   |
| Intel Wireless 7260                                               | 4         | 0.99%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.99%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 4         | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 0.99%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.99%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 0.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 0.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.74%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3         | 0.74%   |
| Intel Wireless 3165                                               | 3         | 0.74%   |
| Intel Wireless 3160                                               | 3         | 0.74%   |
| Intel WiFi Link 5100                                              | 3         | 0.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.74%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.74%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.74%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.74%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 0.74%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 87        | 45.79%  |
| Realtek Semiconductor           | 51        | 26.84%  |
| Qualcomm Atheros                | 19        | 10%     |
| Broadcom                        | 11        | 5.79%   |
| Ralink                          | 5         | 2.63%   |
| MediaTek                        | 5         | 2.63%   |
| TP-Link                         | 3         | 1.58%   |
| Qualcomm Atheros Communications | 2         | 1.05%   |
| Broadcom Limited                | 2         | 1.05%   |
| Quectel Wireless Solutions      | 1         | 0.53%   |
| NetGear                         | 1         | 0.53%   |
| D-Link System                   | 1         | 0.53%   |
| AVM                             | 1         | 0.53%   |
| ASUSTek Computer                | 1         | 0.53%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 4.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 4.71%   |
| Intel Wireless 8265 / 8275                                              | 8         | 4.19%   |
| Realtek 802.11ac NIC                                                    | 7         | 3.66%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 3.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 3.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 2.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 2.62%   |
| Intel Wireless 7265                                                     | 5         | 2.62%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 5         | 2.62%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 2.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 2.09%   |
| Intel Wireless 7260                                                     | 4         | 2.09%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 4         | 2.09%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 2.09%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.57%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 1.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 1.57%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 3         | 1.57%   |
| Intel Wireless 3165                                                     | 3         | 1.57%   |
| Intel Wireless 3160                                                     | 3         | 1.57%   |
| Intel WiFi Link 5100                                                    | 3         | 1.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 1.57%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 1.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 1.57%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.05%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.05%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.05%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 2         | 1.05%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.05%   |
| Intel Wireless 8260                                                     | 2         | 1.05%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 1.05%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.05%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.05%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.05%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 111       | 54.68%  |
| Intel                    | 56        | 27.59%  |
| Broadcom                 | 13        | 6.4%    |
| Qualcomm Atheros         | 6         | 2.96%   |
| ASIX Electronics         | 4         | 1.97%   |
| Marvell Technology Group | 3         | 1.48%   |
| Nvidia                   | 2         | 0.99%   |
| Broadcom Limited         | 2         | 0.99%   |
| Xiaomi                   | 1         | 0.49%   |
| Motorola PCS             | 1         | 0.49%   |
| Microchip Technology     | 1         | 0.49%   |
| Lenovo                   | 1         | 0.49%   |
| DisplayLink              | 1         | 0.49%   |
| Aquantia                 | 1         | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 84        | 40.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 15        | 7.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9         | 4.33%   |
| Intel Ethernet Controller I225-V                                               | 7         | 3.37%   |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 2.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 2.4%    |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 1.92%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 4         | 1.92%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.44%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 1.44%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 1.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 1.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 0.96%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.96%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.96%   |
| Intel I211 Gigabit Network Connection                                          | 2         | 0.96%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.96%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.96%   |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 0.96%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.96%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.96%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                | 2         | 0.96%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.48%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.48%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.48%   |
| Motorola PCS moto g(30)                                                        | 1         | 0.48%   |
| Microchip LAN7500 Ethernet 10/100/1000 Adapter                                 | 1         | 0.48%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 1         | 0.48%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.48%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.48%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.48%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.48%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.48%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 193       | 51.06%  |
| WiFi     | 181       | 47.88%  |
| Modem    | 4         | 1.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 134       | 55.14%  |
| Ethernet | 109       | 44.86%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 130       | 55.32%  |
| 1     | 91        | 38.72%  |
| 0     | 8         | 3.4%    |
| 3     | 4         | 1.7%    |
| 4     | 2         | 0.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 159       | 67.37%  |
| Yes  | 77        | 32.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 69        | 45.39%  |
| Realtek Semiconductor           | 27        | 17.76%  |
| Broadcom                        | 13        | 8.55%   |
| IMC Networks                    | 7         | 4.61%   |
| Apple                           | 7         | 4.61%   |
| Cambridge Silicon Radio         | 5         | 3.29%   |
| Qualcomm Atheros Communications | 4         | 2.63%   |
| Ralink                          | 3         | 1.97%   |
| MediaTek                        | 3         | 1.97%   |
| Foxconn / Hon Hai               | 3         | 1.97%   |
| TP-Link                         | 2         | 1.32%   |
| Lite-On Technology              | 2         | 1.32%   |
| Belkin Components               | 2         | 1.32%   |
| Toshiba                         | 1         | 0.66%   |
| Integrated System Solution      | 1         | 0.66%   |
| Hewlett-Packard                 | 1         | 0.66%   |
| Foxconn International           | 1         | 0.66%   |
| ASUSTek Computer                | 1         | 0.66%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 21        | 13.82%  |
| Intel AX201 Bluetooth                                                               | 20        | 13.16%  |
| Realtek Bluetooth Radio                                                             | 17        | 11.18%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 10        | 6.58%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 4.61%   |
| Intel AX200 Bluetooth                                                               | 5         | 3.29%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 3.29%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 2.63%   |
| Intel AX210 Bluetooth                                                               | 4         | 2.63%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 2.63%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 1.97%   |
| MediaTek Wireless_Device                                                            | 3         | 1.97%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 3         | 1.97%   |
| TP-Link UB500 Adapter                                                               | 2         | 1.32%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 1.32%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.32%   |
| Intel Bluetooth Device                                                              | 2         | 1.32%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.32%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.32%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 2         | 1.32%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 1.32%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.32%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 1.32%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.32%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.32%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.66%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.66%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 0.66%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.66%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.66%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.66%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.66%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.66%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.66%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 1         | 0.66%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.66%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.66%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.66%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.66%   |
| Broadcom Bluetooth 3.0 USB Dongle                                                   | 1         | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 155       | 47.26%  |
| AMD                       | 82        | 25%     |
| Nvidia                    | 50        | 15.24%  |
| C-Media Electronics       | 11        | 3.35%   |
| ASUSTek Computer          | 4         | 1.22%   |
| Generalplus Technology    | 3         | 0.91%   |
| Logitech                  | 2         | 0.61%   |
| JMTek                     | 2         | 0.61%   |
| GN Netcom                 | 2         | 0.61%   |
| Cambridge Silicon Radio   | 2         | 0.61%   |
| TerraTec Electronic       | 1         | 0.3%    |
| SteelSeries ApS           | 1         | 0.3%    |
| Sennheiser Communications | 1         | 0.3%    |
| Realtek Semiconductor     | 1         | 0.3%    |
| Plantronics               | 1         | 0.3%    |
| Meizu                     | 1         | 0.3%    |
| Lenovo                    | 1         | 0.3%    |
| Kingston Technology       | 1         | 0.3%    |
| Focusrite-Novation        | 1         | 0.3%    |
| DSEA A/S                  | 1         | 0.3%    |
| Creative Technology       | 1         | 0.3%    |
| Corsair                   | 1         | 0.3%    |
| Best Buy                  | 1         | 0.3%    |
| Anlya.cn                  | 1         | 0.3%    |
| Alesis                    | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 28        | 7.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 4.55%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 15        | 3.79%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 14        | 3.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 3.03%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 2.78%   |
| AMD FCH Azalia Controller                                                                         | 10        | 2.53%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 2.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 2.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 2.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 9         | 2.27%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7         | 1.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 1.77%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 7         | 1.77%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 1.77%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 1.77%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.77%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 1.52%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6         | 1.52%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 5         | 1.26%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 5         | 1.26%   |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 1.26%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 5         | 1.26%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 1.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.01%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 4         | 1.01%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 1.01%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.01%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.01%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 4         | 1.01%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.76%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 0.76%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 0.76%   |
| ASUSTek Computer USB Audio                                                                        | 3         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 36        | 18.27%  |
| Samsung Electronics | 36        | 18.27%  |
| Kingston            | 24        | 12.18%  |
| Micron Technology   | 23        | 11.68%  |
| Unknown             | 22        | 11.17%  |
| Crucial             | 15        | 7.61%   |
| Corsair             | 12        | 6.09%   |
| G.Skill             | 6         | 3.05%   |
| Unknown (ABCD)      | 5         | 2.54%   |
| Ramaxel Technology  | 4         | 2.03%   |
| Nanya Technology    | 4         | 2.03%   |
| Team                | 2         | 1.02%   |
| A-DATA Technology   | 2         | 1.02%   |
| Unifosa             | 1         | 0.51%   |
| Hewlett-Packard     | 1         | 0.51%   |
| HBS                 | 1         | 0.51%   |
| GOODRAM             | 1         | 0.51%   |
| Atermiter           | 1         | 0.51%   |
| Unknown             | 1         | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 4         | 1.89%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.89%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 1.42%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.42%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 2         | 0.94%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 0.94%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.94%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.94%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.94%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.94%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.94%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 2         | 0.94%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.94%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.94%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.94%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.94%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 2         | 0.94%   |
| Micron RAM 8ATF2G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 2         | 0.94%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.94%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 2         | 0.94%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                         | 1         | 0.47%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1         | 0.47%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.47%   |
| Unknown RAM Module 4GB DIMM                                      | 1         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM DDR2                            | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM 1067MT/s                           | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                         | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 0.47%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.47%   |
| Unknown RAM DDR4 NB 8G 2400 8192MB SODIMM DDR4 2667MT/s          | 1         | 0.47%   |
| Unknown RAM DDR4 NB 16G 2666 16384MB SODIMM DDR4 2667MT/s        | 1         | 0.47%   |
| Unknown RAM 1866 CL10 Series 8192MB DIMM DDR3 933MT/s            | 1         | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 0.47%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s                | 1         | 0.47%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 1         | 0.47%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s            | 1         | 0.47%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 82        | 47.67%  |
| DDR3    | 62        | 36.05%  |
| DDR2    | 9         | 5.23%   |
| LPDDR4  | 8         | 4.65%   |
| Unknown | 4         | 2.33%   |
| SDRAM   | 2         | 1.16%   |
| LPDDR3  | 2         | 1.16%   |
| DDR5    | 2         | 1.16%   |
| DDR     | 1         | 0.58%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 104       | 59.43%  |
| DIMM         | 57        | 32.57%  |
| Row Of Chips | 11        | 6.29%   |
| Unknown      | 2         | 1.14%   |
| Chip         | 1         | 0.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 66        | 34.2%   |
| 4096  | 56        | 29.02%  |
| 16384 | 37        | 19.17%  |
| 2048  | 22        | 11.4%   |
| 32768 | 7         | 3.63%   |
| 1024  | 5         | 2.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 38        | 20.65%  |
| 3200    | 36        | 19.57%  |
| 2667    | 20        | 10.87%  |
| 2400    | 19        | 10.33%  |
| 1333    | 16        | 8.7%    |
| Unknown | 6         | 3.26%   |
| 2133    | 5         | 2.72%   |
| 1334    | 5         | 2.72%   |
| 667     | 4         | 2.17%   |
| 800     | 3         | 1.63%   |
| 4267    | 2         | 1.09%   |
| 3600    | 2         | 1.09%   |
| 3533    | 2         | 1.09%   |
| 3400    | 2         | 1.09%   |
| 2048    | 2         | 1.09%   |
| 1867    | 2         | 1.09%   |
| 1866    | 2         | 1.09%   |
| 1800    | 2         | 1.09%   |
| 1067    | 2         | 1.09%   |
| 4802    | 1         | 0.54%   |
| 4800    | 1         | 0.54%   |
| 4000    | 1         | 0.54%   |
| 3933    | 1         | 0.54%   |
| 3800    | 1         | 0.54%   |
| 3333    | 1         | 0.54%   |
| 3266    | 1         | 0.54%   |
| 3100    | 1         | 0.54%   |
| 2800    | 1         | 0.54%   |
| 2747    | 1         | 0.54%   |
| 2666    | 1         | 0.54%   |
| 1648    | 1         | 0.54%   |
| 1066    | 1         | 0.54%   |
| 975     | 1         | 0.54%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 22.22%  |
| Dymo-CoStar         | 2         | 22.22%  |
| Brother Industries  | 2         | 22.22%  |
| Seiko Epson         | 1         | 11.11%  |
| Samsung Electronics | 1         | 11.11%  |
| Graphtec America    | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Seiko Epson XP-4100 Series        | 1         | 11.11%  |
| Samsung M2070 Series              | 1         | 11.11%  |
| HP LaserJet Professional P1102w   | 1         | 11.11%  |
| HP DeskJet 2700 series            | 1         | 11.11%  |
| Graphtec America Graphtec Printer | 1         | 11.11%  |
| Dymo-CoStar LabelWriter 450       | 1         | 11.11%  |
| Dymo-CoStar LabelWriter 310       | 1         | 11.11%  |
| Brother HL-3140CW series          | 1         | 11.11%  |
| Brother DCP-L5500DN series        | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 2         | 50%     |
| Siemens Information and Communication Products | 1         | 25%     |
| Hewlett-Packard                                | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Siemens Information and Communication Products ID-Mouse with Fingerprint Reader | 1         | 25%     |
| HP ScanJet G4010                                                                | 1         | 25%     |
| Canon CanoScan LiDE 120                                                         | 1         | 25%     |
| Canon CanoScan LiDE 110                                                         | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 33        | 22.92%  |
| Realtek Semiconductor                  | 18        | 12.5%   |
| Quanta                                 | 11        | 7.64%   |
| IMC Networks                           | 11        | 7.64%   |
| Microdia                               | 9         | 6.25%   |
| Logitech                               | 9         | 6.25%   |
| Apple                                  | 7         | 4.86%   |
| Bison Electronics                      | 6         | 4.17%   |
| Syntek                                 | 5         | 3.47%   |
| Suyin                                  | 5         | 3.47%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.47%   |
| Sunplus Innovation Technology          | 2         | 1.39%   |
| Silicon Motion                         | 2         | 1.39%   |
| Ricoh                                  | 2         | 1.39%   |
| Razer USA                              | 2         | 1.39%   |
| Luxvisions Innotech Limited            | 2         | 1.39%   |
| Lite-On Technology                     | 2         | 1.39%   |
| Lenovo                                 | 2         | 1.39%   |
| Generalplus Technology                 | 2         | 1.39%   |
| ARC International                      | 2         | 1.39%   |
| Z-Star Microelectronics                | 1         | 0.69%   |
| SunplusIT                              | 1         | 0.69%   |
| Sonix Technology                       | 1         | 0.69%   |
| Samsung Electronics                    | 1         | 0.69%   |
| Microsoft                              | 1         | 0.69%   |
| Alcorlink                              | 1         | 0.69%   |
| Alcor Micro                            | 1         | 0.69%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                  | 5         | 3.47%   |
| IMC Networks USB2.0 HD UVC WebCam             | 5         | 3.47%   |
| Chicony HP HD Camera                          | 5         | 3.47%   |
| Syntek Integrated Camera                      | 4         | 2.78%   |
| Microdia Webcam Vitade AF                     | 4         | 2.78%   |
| Chicony Integrated Camera                     | 4         | 2.78%   |
| Realtek USB Camera                            | 3         | 2.08%   |
| IMC Networks Integrated Camera                | 3         | 2.08%   |
| Chicony HP Webcam                             | 3         | 2.08%   |
| Chicony HP Truevision HD camera               | 3         | 2.08%   |
| Bison Integrated Camera                       | 3         | 2.08%   |
| Apple Built-in iSight                         | 3         | 2.08%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 2         | 1.39%   |
| Realtek USB2.0 camera                         | 2         | 1.39%   |
| Realtek Integrated Webcam HD                  | 2         | 1.39%   |
| Razer USA Gaming Webcam [Kiyo]                | 2         | 1.39%   |
| Quanta ov9734_techfront_camera                | 2         | 1.39%   |
| Quanta HP TrueVision HD Camera                | 2         | 1.39%   |
| Quanta HD User Facing                         | 2         | 1.39%   |
| Microdia Integrated Webcam                    | 2         | 1.39%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 1.39%   |
| Logitech Webcam C270                          | 2         | 1.39%   |
| Lenovo CNF7237&CNF7238                        | 2         | 1.39%   |
| Chicony USB2.0 Camera                         | 2         | 1.39%   |
| Chicony Integrated IR Camera                  | 2         | 1.39%   |
| Chicony HD User Facing                        | 2         | 1.39%   |
| Chicony EasyCamera                            | 2         | 1.39%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 2         | 1.39%   |
| ARC International Camera                      | 2         | 1.39%   |
| Apple FaceTime HD Camera (Built-in)           | 2         | 1.39%   |
| Z-Star HP 3-MegaPixel Webcam GX607AA          | 1         | 0.69%   |
| Syntek Lenovo EasyCamera                      | 1         | 0.69%   |
| Suyin USB 2.0 Camera                          | 1         | 0.69%   |
| Suyin Laptop_Integrated_Webcam_HD             | 1         | 0.69%   |
| Suyin HP TrueVision HD Integrated Webcam      | 1         | 0.69%   |
| SunplusIT PC Camera                           | 1         | 0.69%   |
| Sunplus Integrated_Webcam_FHD                 | 1         | 0.69%   |
| Sunplus HP Truevision HD                      | 1         | 0.69%   |
| Sonix USB2.0 HD UVC WebCam                    | 1         | 0.69%   |
| Silicon Motion WebCam SC-10HDD13335N          | 1         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 29.17%  |
| Validity Sensors           | 5         | 20.83%  |
| Shenzhen Goodix Technology | 5         | 20.83%  |
| Upek                       | 4         | 16.67%  |
| Elan Microelectronics      | 2         | 8.33%   |
| AuthenTec                  | 1         | 4.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 20.83%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 16.67%  |
| Elan ELAN:ARM-M4                                                           | 2         | 8.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 4.17%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 4.17%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 4.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 4.17%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 4.17%   |
| Synaptics UWP WBDI Device                                                  | 1         | 4.17%   |
| Synaptics UWP WBDI                                                         | 1         | 4.17%   |
| Synaptics  WBDI                                                            | 1         | 4.17%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 4.17%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 4.17%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 4.17%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 4.17%   |
| AuthenTec AES1600                                                          | 1         | 4.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 9         | 50%     |
| Alcor Micro           | 4         | 22.22%  |
| Upek                  | 1         | 5.56%   |
| SCM Microsystems      | 1         | 5.56%   |
| OmniKey               | 1         | 5.56%   |
| O2 Micro              | 1         | 5.56%   |
| Advanced Card Systems | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 5         | 27.78%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 22.22%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 11.11%  |
| Broadcom 5880                                                                | 2         | 11.11%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 5.56%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 5.56%   |
| OmniKey CardMan 1021                                                         | 1         | 5.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.56%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 175       | 73.84%  |
| 1     | 48        | 20.25%  |
| 2     | 11        | 4.64%   |
| 3     | 3         | 1.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 24        | 32.43%  |
| Chipcard              | 17        | 22.97%  |
| Net/wireless          | 8         | 10.81%  |
| Graphics card         | 8         | 10.81%  |
| Bluetooth             | 6         | 8.11%   |
| Camera                | 4         | 5.41%   |
| Card reader           | 2         | 2.7%    |
| Unassigned class      | 1         | 1.35%   |
| Network               | 1         | 1.35%   |
| Multimedia controller | 1         | 1.35%   |
| Flash memory          | 1         | 1.35%   |
| Dvb card              | 1         | 1.35%   |

