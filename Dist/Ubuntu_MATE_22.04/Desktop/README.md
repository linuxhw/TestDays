Ubuntu MATE 22.04 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 221

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B760-PLUS             | [f3149a6f22](https://linux-hardware.org/?probe=f3149a6f22) | Dec 19, 2023 |
| ASUSTek       | PRIME B760-PLUS             | [b7a7aa8d5d](https://linux-hardware.org/?probe=b7a7aa8d5d) | Dec 17, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [991503ccf4](https://linux-hardware.org/?probe=991503ccf4) | Dec 10, 2023 |
| HP            | ProLiant MicroServer        | [5451582602](https://linux-hardware.org/?probe=5451582602) | Dec 08, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [18a5ca0a40](https://linux-hardware.org/?probe=18a5ca0a40) | Dec 07, 2023 |
| Gigabyte      | G41MT-S2                    | [06a0da716b](https://linux-hardware.org/?probe=06a0da716b) | Dec 05, 2023 |
| Gigabyte      | B550 GAMING X V2            | [4c55de5adb](https://linux-hardware.org/?probe=4c55de5adb) | Nov 28, 2023 |
| Gigabyte      | Z590 UD AC                  | [416fbc3923](https://linux-hardware.org/?probe=416fbc3923) | Nov 28, 2023 |
| ASUSTek       | PRIME Z490-P                | [47d33f722e](https://linux-hardware.org/?probe=47d33f722e) | Nov 25, 2023 |
| ASRock        | 970 Extreme3 R2.0           | [502e296060](https://linux-hardware.org/?probe=502e296060) | Nov 23, 2023 |
| ASRock        | X99 Extreme4                | [dfb480c40a](https://linux-hardware.org/?probe=dfb480c40a) | Nov 17, 2023 |
| ASUSTek       | P8P67-M PRO                 | [9d1c329ebb](https://linux-hardware.org/?probe=9d1c329ebb) | Nov 14, 2023 |
| Lenovo        | T530-28ICB                  | [ba883f99a0](https://linux-hardware.org/?probe=ba883f99a0) | Nov 06, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [d2d21dcf50](https://linux-hardware.org/?probe=d2d21dcf50) | Nov 01, 2023 |
| MSI           | A320M PRO-M2 V2             | [9854f25018](https://linux-hardware.org/?probe=9854f25018) | Oct 26, 2023 |
| ASRock        | Z370 Killer SLI             | [b01d80e583](https://linux-hardware.org/?probe=b01d80e583) | Oct 24, 2023 |
| HP            | 3646h                       | [6a679937c4](https://linux-hardware.org/?probe=6a679937c4) | Oct 18, 2023 |
| ASRock        | J4105-ITX                   | [f4d4b23c31](https://linux-hardware.org/?probe=f4d4b23c31) | Oct 02, 2023 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | [b9b34bef50](https://linux-hardware.org/?probe=b9b34bef50) | Oct 02, 2023 |
| 3Logic Gro... | DMB-H510-MCA01              | [b952cdd71d](https://linux-hardware.org/?probe=b952cdd71d) | Sep 29, 2023 |
| HP            | 8643 SMVB                   | [64f1cd854d](https://linux-hardware.org/?probe=64f1cd854d) | Sep 26, 2023 |
| Foxconn       | 2ABF                        | [2be1547618](https://linux-hardware.org/?probe=2be1547618) | Sep 26, 2023 |
| ASUSTek       | M5A78L-M LX                 | [450edd6547](https://linux-hardware.org/?probe=450edd6547) | Sep 24, 2023 |
| ASRock        | A320M-HD                    | [00ce48a639](https://linux-hardware.org/?probe=00ce48a639) | Sep 19, 2023 |
| Unknown       | X79M2-Q                     | [670ca9e147](https://linux-hardware.org/?probe=670ca9e147) | Sep 17, 2023 |
| ASUSTek       | PRIME B450M-A II            | [adff9fb2a8](https://linux-hardware.org/?probe=adff9fb2a8) | Sep 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | [103e7031fe](https://linux-hardware.org/?probe=103e7031fe) | Sep 14, 2023 |
| Intel         | DH67CL AAG10212-210         | [21932b1004](https://linux-hardware.org/?probe=21932b1004) | Sep 14, 2023 |
| ASUSTek       | P8P67-M PRO                 | [799a135aca](https://linux-hardware.org/?probe=799a135aca) | Sep 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | [7cea54ec70](https://linux-hardware.org/?probe=7cea54ec70) | Sep 13, 2023 |
| ASUSTek       | P8P67-M PRO                 | [6ec67cd2f1](https://linux-hardware.org/?probe=6ec67cd2f1) | Sep 08, 2023 |
| ASUSTek       | H61M-K                      | [0e82099e8f](https://linux-hardware.org/?probe=0e82099e8f) | Sep 01, 2023 |
| MSI           | Z97-G43                     | [74492b4424](https://linux-hardware.org/?probe=74492b4424) | Aug 30, 2023 |
| ASRock        | A320M-HD                    | [dcb65a221f](https://linux-hardware.org/?probe=dcb65a221f) | Aug 27, 2023 |
| Dell          | OptiPlex 5050               | [045411a33d](https://linux-hardware.org/?probe=045411a33d) | Aug 21, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [f280fd203e](https://linux-hardware.org/?probe=f280fd203e) | Aug 21, 2023 |
| ASRock        | B450M Pro4                  | [cdbe8c2f04](https://linux-hardware.org/?probe=cdbe8c2f04) | Aug 21, 2023 |
| Dell          | OptiPlex 5050               | [e2c9cecddd](https://linux-hardware.org/?probe=e2c9cecddd) | Aug 18, 2023 |
| HP            | 829D                        | [448bb23145](https://linux-hardware.org/?probe=448bb23145) | Aug 15, 2023 |
| Gigabyte      | B85M-D3H                    | [6602bb3d0a](https://linux-hardware.org/?probe=6602bb3d0a) | Aug 13, 2023 |
| Gigabyte      | B85M-D3H                    | [5a809fe1c3](https://linux-hardware.org/?probe=5a809fe1c3) | Aug 13, 2023 |
| Biostar       | A10N-8800E                  | [5ccf8e7d00](https://linux-hardware.org/?probe=5ccf8e7d00) | Aug 11, 2023 |
| Unknown       | Unknown                     | [78f477986b](https://linux-hardware.org/?probe=78f477986b) | Aug 10, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [0c4903c4d2](https://linux-hardware.org/?probe=0c4903c4d2) | Aug 10, 2023 |
| Gigabyte      | B85M-D3H                    | [32e3874db3](https://linux-hardware.org/?probe=32e3874db3) | Jul 28, 2023 |
| Lenovo        | 3740 NOK                    | [9e156dd92f](https://linux-hardware.org/?probe=9e156dd92f) | Jul 26, 2023 |
| Gigabyte      | B85M-D3H                    | [67daf82d15](https://linux-hardware.org/?probe=67daf82d15) | Jul 24, 2023 |
| Gigabyte      | B550 GAMING X V2            | [0a3cc7970c](https://linux-hardware.org/?probe=0a3cc7970c) | Jul 23, 2023 |
| ASUSTek       | PRIME Z590-P                | [02903e0210](https://linux-hardware.org/?probe=02903e0210) | Jul 22, 2023 |
| Gigabyte      | G41MT-S2                    | [d625267663](https://linux-hardware.org/?probe=d625267663) | Jul 17, 2023 |
| Gigabyte      | B85M-D3H                    | [1e85aec604](https://linux-hardware.org/?probe=1e85aec604) | Jul 09, 2023 |
| Gigabyte      | B85M-D3H                    | [f73623381d](https://linux-hardware.org/?probe=f73623381d) | Jul 08, 2023 |
| Gigabyte      | B85M-D3H                    | [d37d74ba93](https://linux-hardware.org/?probe=d37d74ba93) | Jul 07, 2023 |
| ASRock        | Z370 Killer SLI             | [b7a676e2fc](https://linux-hardware.org/?probe=b7a676e2fc) | Jul 05, 2023 |
| ASRock        | Z370 Killer SLI             | [e7c0ca1bfc](https://linux-hardware.org/?probe=e7c0ca1bfc) | Jul 05, 2023 |
| Unknown       | Unknown                     | [23956fd693](https://linux-hardware.org/?probe=23956fd693) | Jul 04, 2023 |
| Gigabyte      | B85M-D3H                    | [ce2d3b5375](https://linux-hardware.org/?probe=ce2d3b5375) | Jul 02, 2023 |
| Gigabyte      | B85M-D3H                    | [0bb17f7e1b](https://linux-hardware.org/?probe=0bb17f7e1b) | Jul 01, 2023 |
| ASUSTek       | PRIME Z590-P                | [fb7e164f62](https://linux-hardware.org/?probe=fb7e164f62) | Jul 01, 2023 |
| ASUSTek       | PRIME Z590-P                | [2774be84e6](https://linux-hardware.org/?probe=2774be84e6) | Jul 01, 2023 |
| Gigabyte      | B85M-D3H                    | [99b07ae636](https://linux-hardware.org/?probe=99b07ae636) | Jun 30, 2023 |
| Gigabyte      | B85M-D3H                    | [498eb9b539](https://linux-hardware.org/?probe=498eb9b539) | Jun 30, 2023 |
| ASUSTek       | H61M-K                      | [ddc5e387cb](https://linux-hardware.org/?probe=ddc5e387cb) | Jun 24, 2023 |
| ASUSTek       | P7P55 LX                    | [e700828afa](https://linux-hardware.org/?probe=e700828afa) | Jun 23, 2023 |
| ASUSTek       | P7P55 LX                    | [cd9b9aae75](https://linux-hardware.org/?probe=cd9b9aae75) | Jun 23, 2023 |
| Gigabyte      | B85M-D3H                    | [033c027010](https://linux-hardware.org/?probe=033c027010) | Jun 18, 2023 |
| Gigabyte      | B85M-D3H                    | [fe0d892e82](https://linux-hardware.org/?probe=fe0d892e82) | Jun 16, 2023 |
| HP            | 8643 SMVB                   | [db301ecd59](https://linux-hardware.org/?probe=db301ecd59) | Jun 11, 2023 |
| Gigabyte      | B85M-D3H                    | [befd126f43](https://linux-hardware.org/?probe=befd126f43) | Jun 07, 2023 |
| Gigabyte      | B85M-D3H                    | [e146923f12](https://linux-hardware.org/?probe=e146923f12) | Jun 07, 2023 |
| HP            | 1998                        | [c6183bd564](https://linux-hardware.org/?probe=c6183bd564) | Jun 05, 2023 |
| Gigabyte      | B85M-D3H                    | [0bd595e07a](https://linux-hardware.org/?probe=0bd595e07a) | Jun 04, 2023 |
| Gigabyte      | B85M-D3H                    | [908f094e9d](https://linux-hardware.org/?probe=908f094e9d) | Jun 02, 2023 |
| MSI           | H97 GAMING 3                | [f9c0a669c5](https://linux-hardware.org/?probe=f9c0a669c5) | Jun 02, 2023 |
| ASUSTek       | H61M-K                      | [c6ee1e5e32](https://linux-hardware.org/?probe=c6ee1e5e32) | Jun 02, 2023 |
| Unknown       | HX90                        | [d38fff55af](https://linux-hardware.org/?probe=d38fff55af) | May 28, 2023 |
| Gigabyte      | B85M-D3H                    | [67122d7cd6](https://linux-hardware.org/?probe=67122d7cd6) | May 12, 2023 |
| Gigabyte      | B85M-D3H                    | [9c8ffba5f4](https://linux-hardware.org/?probe=9c8ffba5f4) | May 12, 2023 |
| Gigabyte      | B85M-D3H                    | [11a41c975d](https://linux-hardware.org/?probe=11a41c975d) | May 07, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [b6ec076cc6](https://linux-hardware.org/?probe=b6ec076cc6) | May 05, 2023 |
| Acer          | Aspire X1430                | [4bdb74f57e](https://linux-hardware.org/?probe=4bdb74f57e) | May 04, 2023 |
| Gigabyte      | B85M-D3H                    | [f9c27ab898](https://linux-hardware.org/?probe=f9c27ab898) | May 02, 2023 |
| Gigabyte      | B85M-D3H                    | [2fe28d7f43](https://linux-hardware.org/?probe=2fe28d7f43) | Apr 29, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [ef3f4d1ac1](https://linux-hardware.org/?probe=ef3f4d1ac1) | Apr 29, 2023 |
| Gigabyte      | B85M-D3H                    | [c0c226bf8c](https://linux-hardware.org/?probe=c0c226bf8c) | Apr 28, 2023 |
| Gigabyte      | P55-UD3                     | [cb8885f205](https://linux-hardware.org/?probe=cb8885f205) | Apr 25, 2023 |
| Gigabyte      | P55-UD3                     | [cacc141f4f](https://linux-hardware.org/?probe=cacc141f4f) | Apr 25, 2023 |
| Gigabyte      | B85M-D3H                    | [88a6d9040e](https://linux-hardware.org/?probe=88a6d9040e) | Apr 23, 2023 |
| ASUSTek       | Z170-P                      | [b003b5c775](https://linux-hardware.org/?probe=b003b5c775) | Apr 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | [90e0cff0ad](https://linux-hardware.org/?probe=90e0cff0ad) | Apr 22, 2023 |
| AMI           | Intel                       | [b7a63bbfc7](https://linux-hardware.org/?probe=b7a63bbfc7) | Apr 15, 2023 |
| AMI           | Intel                       | [ec0a5e657e](https://linux-hardware.org/?probe=ec0a5e657e) | Apr 14, 2023 |
| Gigabyte      | B85M-D3H                    | [7041b36ac5](https://linux-hardware.org/?probe=7041b36ac5) | Apr 14, 2023 |
| Lenovo        | ThinkStation D20 4158GK1    | [44d9536051](https://linux-hardware.org/?probe=44d9536051) | Apr 14, 2023 |
| HP            | 1494                        | [9c5dc1a221](https://linux-hardware.org/?probe=9c5dc1a221) | Apr 13, 2023 |
| Gigabyte      | B85M-D3H                    | [87be7a6dc0](https://linux-hardware.org/?probe=87be7a6dc0) | Apr 09, 2023 |
| Dell          | 0J3C2F A00                  | [e2c3600e8b](https://linux-hardware.org/?probe=e2c3600e8b) | Apr 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | [248ef68079](https://linux-hardware.org/?probe=248ef68079) | Apr 03, 2023 |
| Gigabyte      | B85M-D3H                    | [77187502c9](https://linux-hardware.org/?probe=77187502c9) | Apr 01, 2023 |
| Gigabyte      | B85M-D3H                    | [a074e581b0](https://linux-hardware.org/?probe=a074e581b0) | Mar 28, 2023 |
| ASUSTek       | M5A97 R2.0                  | [d56f48b9d1](https://linux-hardware.org/?probe=d56f48b9d1) | Mar 27, 2023 |
| Shenzhen M... | HX90G                       | [fb3f1be00d](https://linux-hardware.org/?probe=fb3f1be00d) | Mar 26, 2023 |
| Gigabyte      | B85M-D3H                    | [890cd39d63](https://linux-hardware.org/?probe=890cd39d63) | Mar 26, 2023 |
| ASUSTek       | H61M-K                      | [dcae89c3e5](https://linux-hardware.org/?probe=dcae89c3e5) | Mar 21, 2023 |
| ASUSTek       | H61M-K                      | [9ff80f0344](https://linux-hardware.org/?probe=9ff80f0344) | Mar 21, 2023 |
| CCE           | NM70-I                      | [3e99b6e12d](https://linux-hardware.org/?probe=3e99b6e12d) | Mar 21, 2023 |
| ASUSTek       | M5A78L LE                   | [e18778e282](https://linux-hardware.org/?probe=e18778e282) | Mar 20, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | [bbe02b925a](https://linux-hardware.org/?probe=bbe02b925a) | Mar 19, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | [d376f92f8d](https://linux-hardware.org/?probe=d376f92f8d) | Mar 19, 2023 |
| Gigabyte      | B85M-D3H                    | [605bc3d5b0](https://linux-hardware.org/?probe=605bc3d5b0) | Mar 19, 2023 |
| Gigabyte      | B85M-D3H                    | [4cee2dc95e](https://linux-hardware.org/?probe=4cee2dc95e) | Mar 18, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [7298c4b04b](https://linux-hardware.org/?probe=7298c4b04b) | Mar 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [794bc239ab](https://linux-hardware.org/?probe=794bc239ab) | Mar 17, 2023 |
| ASUSTek       | M5A97 R2.0                  | [526e33e980](https://linux-hardware.org/?probe=526e33e980) | Mar 15, 2023 |
| ASRock        | A320M-HDV R4.0              | [8d2ca6cedc](https://linux-hardware.org/?probe=8d2ca6cedc) | Mar 14, 2023 |
| ASUSTek       | M5A97 R2.0                  | [2f69480899](https://linux-hardware.org/?probe=2f69480899) | Mar 14, 2023 |
| HP            | 339A                        | [fa78907d67](https://linux-hardware.org/?probe=fa78907d67) | Mar 12, 2023 |
| Gigabyte      | B85M-D3H                    | [f9dfd84f86](https://linux-hardware.org/?probe=f9dfd84f86) | Mar 12, 2023 |
| Gigabyte      | B85M-D3H                    | [ee115bdfb8](https://linux-hardware.org/?probe=ee115bdfb8) | Mar 11, 2023 |
| MSI           | X370 SLI PLUS               | [d2ac8dd020](https://linux-hardware.org/?probe=d2ac8dd020) | Mar 07, 2023 |
| Gigabyte      | B85M-D3H                    | [adce83e80e](https://linux-hardware.org/?probe=adce83e80e) | Mar 07, 2023 |
| Gigabyte      | B85M-D3H                    | [9178ffc6f9](https://linux-hardware.org/?probe=9178ffc6f9) | Mar 05, 2023 |
| MSI           | X570-A PRO                  | [7d1b3a73f9](https://linux-hardware.org/?probe=7d1b3a73f9) | Mar 05, 2023 |
| Gigabyte      | B85M-D3H                    | [9f5aaa2900](https://linux-hardware.org/?probe=9f5aaa2900) | Mar 04, 2023 |
| ASUSTek       | M5A78L-M LX                 | [0cd2798326](https://linux-hardware.org/?probe=0cd2798326) | Mar 03, 2023 |
| Gigabyte      | B85M-D3H                    | [b6128fb3e9](https://linux-hardware.org/?probe=b6128fb3e9) | Feb 28, 2023 |
| MSI           | A320M-A PRO MAX             | [64cf10c762](https://linux-hardware.org/?probe=64cf10c762) | Feb 26, 2023 |
| Gigabyte      | B85M-D3H                    | [b1a38edcc2](https://linux-hardware.org/?probe=b1a38edcc2) | Feb 25, 2023 |
| MSI           | A320M-A PRO MAX             | [24b1205b0c](https://linux-hardware.org/?probe=24b1205b0c) | Feb 24, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [1029c7f3bb](https://linux-hardware.org/?probe=1029c7f3bb) | Feb 17, 2023 |
| ASUSTek       | PRIME B360M-C               | [d380600b31](https://linux-hardware.org/?probe=d380600b31) | Feb 15, 2023 |
| Gigabyte      | B85M-D3H                    | [ba06eb3e9c](https://linux-hardware.org/?probe=ba06eb3e9c) | Feb 11, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | [14bde69d96](https://linux-hardware.org/?probe=14bde69d96) | Feb 10, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [190a780b8a](https://linux-hardware.org/?probe=190a780b8a) | Jan 29, 2023 |
| Gigabyte      | B550 GAMING X V2            | [4f24524e7d](https://linux-hardware.org/?probe=4f24524e7d) | Jan 19, 2023 |
| Gigabyte      | H510M H                     | [e8cc3131fc](https://linux-hardware.org/?probe=e8cc3131fc) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [d92a983612](https://linux-hardware.org/?probe=d92a983612) | Jan 12, 2023 |
| Gigabyte      | B85M-D3H                    | [e83827b548](https://linux-hardware.org/?probe=e83827b548) | Jan 11, 2023 |
| Gigabyte      | B85M-D3H                    | [0e81ffb471](https://linux-hardware.org/?probe=0e81ffb471) | Jan 11, 2023 |
| HP            | ProLiant MicroServer        | [4bdffcda7f](https://linux-hardware.org/?probe=4bdffcda7f) | Jan 07, 2023 |
| HP            | ProLiant ML350p Gen8        | [8a7807ff8c](https://linux-hardware.org/?probe=8a7807ff8c) | Jan 03, 2023 |
| HP            | ProLiant ML350p Gen8        | [1b66a8a1a8](https://linux-hardware.org/?probe=1b66a8a1a8) | Jan 02, 2023 |
| ASUSTek       | M5A78L-M LX                 | [b0f7933824](https://linux-hardware.org/?probe=b0f7933824) | Dec 29, 2022 |
| ASUSTek       | H110M-K                     | [4dab06b05f](https://linux-hardware.org/?probe=4dab06b05f) | Dec 29, 2022 |
| Gigabyte      | B85M-D3H                    | [4283e3bb1e](https://linux-hardware.org/?probe=4283e3bb1e) | Dec 27, 2022 |
| Dell          | 0J1C3P A00                  | [b65b20a073](https://linux-hardware.org/?probe=b65b20a073) | Dec 22, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [2ad8b45619](https://linux-hardware.org/?probe=2ad8b45619) | Dec 21, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [0e53e0be48](https://linux-hardware.org/?probe=0e53e0be48) | Dec 21, 2022 |
| ASRock        | B550M-ITX/ac                | [21a91196b1](https://linux-hardware.org/?probe=21a91196b1) | Dec 19, 2022 |
| ASUSTek       | PRIME Z590-P WIFI           | [34ac0b3211](https://linux-hardware.org/?probe=34ac0b3211) | Dec 17, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [ac15fdcc8b](https://linux-hardware.org/?probe=ac15fdcc8b) | Dec 16, 2022 |
| HP            | 2215                        | [78151a5e1b](https://linux-hardware.org/?probe=78151a5e1b) | Dec 16, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [976923f807](https://linux-hardware.org/?probe=976923f807) | Dec 12, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [7ae8aecc25](https://linux-hardware.org/?probe=7ae8aecc25) | Dec 08, 2022 |
| ASRock        | B550M-ITX/ac                | [1d97601be2](https://linux-hardware.org/?probe=1d97601be2) | Dec 08, 2022 |
| ASRock        | B550M-ITX/ac                | [4943e0aa12](https://linux-hardware.org/?probe=4943e0aa12) | Dec 08, 2022 |
| ASUSTek       | P7P55 LX                    | [be0753651f](https://linux-hardware.org/?probe=be0753651f) | Dec 07, 2022 |
| ASRock        | 990FX Extreme3              | [84b8daa5c4](https://linux-hardware.org/?probe=84b8daa5c4) | Nov 20, 2022 |
| HP            | 1998                        | [f9746a4ae0](https://linux-hardware.org/?probe=f9746a4ae0) | Nov 15, 2022 |
| MSI           | B75A-IE35                   | [57b74e4ca2](https://linux-hardware.org/?probe=57b74e4ca2) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [91bf754e64](https://linux-hardware.org/?probe=91bf754e64) | Oct 24, 2022 |
| ASRock        | Z77 Extreme4                | [7d12ed56e5](https://linux-hardware.org/?probe=7d12ed56e5) | Oct 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6e45f7ecd7](https://linux-hardware.org/?probe=6e45f7ecd7) | Oct 15, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [d1a5c91196](https://linux-hardware.org/?probe=d1a5c91196) | Oct 14, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [b69b373cc1](https://linux-hardware.org/?probe=b69b373cc1) | Oct 14, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [175ebd8462](https://linux-hardware.org/?probe=175ebd8462) | Oct 14, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [1ba5f65f98](https://linux-hardware.org/?probe=1ba5f65f98) | Oct 10, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [41dd35ae5f](https://linux-hardware.org/?probe=41dd35ae5f) | Oct 10, 2022 |
| ASUSTek       | M5A78L LE                   | [69023fe30e](https://linux-hardware.org/?probe=69023fe30e) | Oct 09, 2022 |
| Lenovo        | T530-28ICB                  | [b87998cf32](https://linux-hardware.org/?probe=b87998cf32) | Oct 09, 2022 |
| MSI           | B550-A PRO                  | [be6a0fda35](https://linux-hardware.org/?probe=be6a0fda35) | Oct 08, 2022 |
| Lenovo        | T530-28ICB                  | [175a71260e](https://linux-hardware.org/?probe=175a71260e) | Oct 06, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [85eb59fc6d](https://linux-hardware.org/?probe=85eb59fc6d) | Oct 05, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [cb5d0d1945](https://linux-hardware.org/?probe=cb5d0d1945) | Oct 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [3af0c5cc5f](https://linux-hardware.org/?probe=3af0c5cc5f) | Oct 01, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [db15c7b708](https://linux-hardware.org/?probe=db15c7b708) | Oct 01, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [608c715bab](https://linux-hardware.org/?probe=608c715bab) | Sep 26, 2022 |
| MSI           | H81M-P33                    | [108817dc0f](https://linux-hardware.org/?probe=108817dc0f) | Sep 21, 2022 |
| ASRock        | HM55-HT                     | [64fff8f065](https://linux-hardware.org/?probe=64fff8f065) | Sep 20, 2022 |
| MSI           | 870-G45                     | [74af87b0c5](https://linux-hardware.org/?probe=74af87b0c5) | Sep 17, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [081d4b1d50](https://linux-hardware.org/?probe=081d4b1d50) | Sep 16, 2022 |
| ASUSTek       | M2A74-AM                    | [25c30e4e54](https://linux-hardware.org/?probe=25c30e4e54) | Sep 14, 2022 |
| ASUSTek       | M2A74-AM                    | [24e6ffe552](https://linux-hardware.org/?probe=24e6ffe552) | Sep 14, 2022 |
| ASUSTek       | P7P55 LX                    | [cc28ed218f](https://linux-hardware.org/?probe=cc28ed218f) | Sep 13, 2022 |
| Acer          | Aspire X3950                | [22d1319220](https://linux-hardware.org/?probe=22d1319220) | Sep 06, 2022 |
| ASUSTek       | P5GZ-MX                     | [883739db23](https://linux-hardware.org/?probe=883739db23) | Sep 05, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [f16d383b65](https://linux-hardware.org/?probe=f16d383b65) | Sep 05, 2022 |
| HP            | 2ADC                        | [d9e5d2b511](https://linux-hardware.org/?probe=d9e5d2b511) | Sep 04, 2022 |
| HP            | 18E4                        | [c58c0043cb](https://linux-hardware.org/?probe=c58c0043cb) | Sep 03, 2022 |
| HP            | 3397                        | [5cd2349a9c](https://linux-hardware.org/?probe=5cd2349a9c) | Sep 02, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [2be9b66ba1](https://linux-hardware.org/?probe=2be9b66ba1) | Aug 30, 2022 |
| AZW           | GK55                        | [0ae52e1fdf](https://linux-hardware.org/?probe=0ae52e1fdf) | Aug 21, 2022 |
| MSI           | H170M PRO-VDH               | [4d7aa09763](https://linux-hardware.org/?probe=4d7aa09763) | Aug 16, 2022 |
| Dell          | 08NPPY A00                  | [1b78691cac](https://linux-hardware.org/?probe=1b78691cac) | Aug 14, 2022 |
| Dell          | 08NPPY A00                  | [b41823f392](https://linux-hardware.org/?probe=b41823f392) | Aug 14, 2022 |
| MSI           | MS-77311                    | [86b4d71bc0](https://linux-hardware.org/?probe=86b4d71bc0) | Aug 11, 2022 |
| HP            | 8433 11                     | [cd790281b5](https://linux-hardware.org/?probe=cd790281b5) | Aug 02, 2022 |
| Dell          | 0KWVT8 A03                  | [cdca6713e9](https://linux-hardware.org/?probe=cdca6713e9) | Jul 31, 2022 |
| Dell          | 0KWVT8 A03                  | [1444843fcd](https://linux-hardware.org/?probe=1444843fcd) | Jul 31, 2022 |
| MSI           | 2AE0                        | [5c0034d313](https://linux-hardware.org/?probe=5c0034d313) | Jul 22, 2022 |
| MSI           | 2AE0                        | [df441346da](https://linux-hardware.org/?probe=df441346da) | Jul 22, 2022 |
| Medion        | MS-7797                     | [caf13d5392](https://linux-hardware.org/?probe=caf13d5392) | Jul 14, 2022 |
| Dell          | 0GM819                      | [3d18cc2632](https://linux-hardware.org/?probe=3d18cc2632) | Jul 08, 2022 |
| Gigabyte      | Z87-HD3                     | [95e6ec0822](https://linux-hardware.org/?probe=95e6ec0822) | Jul 05, 2022 |
| HP            | 3646h                       | [9e0737f23f](https://linux-hardware.org/?probe=9e0737f23f) | Jul 04, 2022 |
| Gigabyte      | Z87-HD3                     | [28429fdd32](https://linux-hardware.org/?probe=28429fdd32) | Jul 02, 2022 |
| HP            | 8169                        | [18c6ea7678](https://linux-hardware.org/?probe=18c6ea7678) | Jul 01, 2022 |
| HP            | 8169                        | [c479baadc1](https://linux-hardware.org/?probe=c479baadc1) | Jul 01, 2022 |
| Acer          | Aspire X3950                | [81797815d2](https://linux-hardware.org/?probe=81797815d2) | Jun 13, 2022 |
| Unknown       | Unknown                     | [c62add2d70](https://linux-hardware.org/?probe=c62add2d70) | Jun 13, 2022 |
| HP            | 3397                        | [55bcbdbc1f](https://linux-hardware.org/?probe=55bcbdbc1f) | Jun 07, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [5407d4a1f6](https://linux-hardware.org/?probe=5407d4a1f6) | Jun 07, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | [9044b2e4e2](https://linux-hardware.org/?probe=9044b2e4e2) | May 18, 2022 |
| Unknown       | HX90                        | [3a7e2628b0](https://linux-hardware.org/?probe=3a7e2628b0) | May 09, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [246c63d834](https://linux-hardware.org/?probe=246c63d834) | May 06, 2022 |
| HP            | 8433 11                     | [a5b829538b](https://linux-hardware.org/?probe=a5b829538b) | Apr 29, 2022 |
| Gigabyte      | X99P-SLI-CF                 | [19055b80bc](https://linux-hardware.org/?probe=19055b80bc) | Apr 16, 2022 |
| ASUSTek       | PRIME H410M-A               | [9352c21f95](https://linux-hardware.org/?probe=9352c21f95) | Mar 17, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [4368bd67ac](https://linux-hardware.org/?probe=4368bd67ac) | Nov 23, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [686454975b](https://linux-hardware.org/?probe=686454975b) | Nov 23, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [36ac197007](https://linux-hardware.org/?probe=36ac197007) | Nov 17, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.15.0-56-generic    | 13       | 8.72%   |
| 5.15.0-47-generic    | 11       | 7.38%   |
| 6.2.0-26-generic     | 7        | 4.7%    |
| 5.15.0-48-generic    | 7        | 4.7%    |
| 5.15.0-67-generic    | 6        | 4.03%   |
| 5.15.0-60-generic    | 6        | 4.03%   |
| 6.2.0-32-generic     | 5        | 3.36%   |
| 5.15.0-76-generic    | 5        | 3.36%   |
| 5.15.0-50-generic    | 5        | 3.36%   |
| 5.19.0-32-generic    | 4        | 2.68%   |
| 5.15.0-52-generic    | 4        | 2.68%   |
| 5.15.0-25-generic    | 4        | 2.68%   |
| 6.2.0-37-generic     | 3        | 2.01%   |
| 5.19.0-38-generic    | 3        | 2.01%   |
| 5.15.0-89-generic    | 3        | 2.01%   |
| 5.15.0-46-generic    | 3        | 2.01%   |
| 5.15.0-40-generic    | 3        | 2.01%   |
| 5.15.0-27-generic    | 3        | 2.01%   |
| 6.2.0-35-generic     | 2        | 1.34%   |
| 6.2.0-33-generic     | 2        | 1.34%   |
| 5.19.0-35-generic    | 2        | 1.34%   |
| 5.15.0-84-generic    | 2        | 1.34%   |
| 5.15.0-82-generic    | 2        | 1.34%   |
| 5.15.0-71-generic    | 2        | 1.34%   |
| 5.15.0-70-generic    | 2        | 1.34%   |
| 5.15.0-69-generic    | 2        | 1.34%   |
| 5.15.0-58-generic    | 2        | 1.34%   |
| 5.15.0-57-generic    | 2        | 1.34%   |
| 5.15.0-41-generic    | 2        | 1.34%   |
| 5.15.0-37-generic    | 2        | 1.34%   |
| 6.4.0-060400-generic | 1        | 0.67%   |
| 6.2.0-39-generic     | 1        | 0.67%   |
| 6.2.0-36-generic     | 1        | 0.67%   |
| 5.19.0-50-generic    | 1        | 0.67%   |
| 5.19.0-43-generic    | 1        | 0.67%   |
| 5.19.0-42-generic    | 1        | 0.67%   |
| 5.19.0-41-generic    | 1        | 0.67%   |
| 5.19.0-40-generic    | 1        | 0.67%   |
| 5.19.0-37-generic    | 1        | 0.67%   |
| 5.18.0-1-generic     | 1        | 0.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 91       | 69.47%  |
| 6.2.0   | 20       | 15.27%  |
| 5.19.0  | 15       | 11.45%  |
| 5.13.0  | 2        | 1.53%   |
| 6.4.0   | 1        | 0.76%   |
| 5.18.0  | 1        | 0.76%   |
| 5.14.0  | 1        | 0.76%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 91       | 69.47%  |
| 6.2     | 20       | 15.27%  |
| 5.19    | 15       | 11.45%  |
| 5.13    | 2        | 1.53%   |
| 6.4     | 1        | 0.76%   |
| 5.18    | 1        | 0.76%   |
| 5.14    | 1        | 0.76%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 126      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| MATE   | 123      | 97.62%  |
| KDE5   | 1        | 0.79%   |
| GNOME  | 1        | 0.79%   |
| Budgie | 1        | 0.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 118      | 93.65%  |
| Wayland | 5        | 3.97%   |
| Tty     | 3        | 2.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 101      | 78.91%  |
| GDM3    | 15       | 11.72%  |
| Unknown | 12       | 9.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 47       | 37.3%   |
| fr_FR | 16       | 12.7%   |
| it_IT | 13       | 10.32%  |
| de_DE | 12       | 9.52%   |
| en_AU | 5        | 3.97%   |
| pt_BR | 4        | 3.17%   |
| ru_RU | 2        | 1.59%   |
| hr_HR | 2        | 1.59%   |
| es_AR | 2        | 1.59%   |
| en_GB | 2        | 1.59%   |
| en_CA | 2        | 1.59%   |
| de_CH | 2        | 1.59%   |
| C     | 2        | 1.59%   |
| zh_TW | 1        | 0.79%   |
| tr_TR | 1        | 0.79%   |
| nl_NL | 1        | 0.79%   |
| hu_HU | 1        | 0.79%   |
| fi_FI | 1        | 0.79%   |
| et_EE | 1        | 0.79%   |
| es_VE | 1        | 0.79%   |
| es_PE | 1        | 0.79%   |
| es_MX | 1        | 0.79%   |
| es_ES | 1        | 0.79%   |
| en_IL | 1        | 0.79%   |
| de_AT | 1        | 0.79%   |
| da_DK | 1        | 0.79%   |
| cs_CZ | 1        | 0.79%   |
| ar_KW | 1        | 0.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 76       | 59.38%  |
| EFI  | 52       | 40.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 100      | 75.76%  |
| Tmpfs   | 17       | 12.88%  |
| Overlay | 6        | 4.55%   |
| Btrfs   | 5        | 3.79%   |
| Xfs     | 2        | 1.52%   |
| Zfs     | 1        | 0.76%   |
| Ext2    | 1        | 0.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 86       | 67.19%  |
| Unknown | 24       | 18.75%  |
| MBR     | 18       | 14.06%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 100      | 78.74%  |
| Yes       | 27       | 21.26%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 75       | 59.06%  |
| Yes       | 52       | 40.94%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 36       | 28.57%  |
| Hewlett-Packard                      | 18       | 14.29%  |
| MSI                                  | 16       | 12.7%   |
| Gigabyte Technology                  | 13       | 10.32%  |
| ASRock                               | 12       | 9.52%   |
| Lenovo                               | 7        | 5.56%   |
| Dell                                 | 6        | 4.76%   |
| Unknown                              | 6        | 4.76%   |
| Acer                                 | 2        | 1.59%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.79%   |
| Medion                               | 1        | 0.79%   |
| MACHINIST                            | 1        | 0.79%   |
| Intel                                | 1        | 0.79%   |
| Foxconn                              | 1        | 0.79%   |
| CCE                                  | 1        | 0.79%   |
| Biostar                              | 1        | 0.79%   |
| AZW                                  | 1        | 0.79%   |
| AMI                                  | 1        | 0.79%   |
| 3Logic Group                         | 1        | 0.79%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Unknown                                    | 6        | 4.76%   |
| HP EliteDesk 800 G1 SFF                    | 2        | 1.59%   |
| HP Desktop M01-F0xxx                       | 2        | 1.59%   |
| HP Compaq Elite 8300 SFF                   | 2        | 1.59%   |
| HP Compaq 8000 Elite SFF PC                | 2        | 1.59%   |
| Gigabyte B85M-D3H                          | 2        | 1.59%   |
| ASUS M5A78L LE                             | 2        | 1.59%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.79%   |
| MSI p6-2330                                | 1        | 0.79%   |
| MSI MS-7D43                                | 1        | 0.79%   |
| MSI MS-7C56                                | 1        | 0.79%   |
| MSI MS-7C52                                | 1        | 0.79%   |
| MSI MS-7C37                                | 1        | 0.79%   |
| MSI MS-7C09                                | 1        | 0.79%   |
| MSI MS-7C02                                | 1        | 0.79%   |
| MSI MS-7B84                                | 1        | 0.79%   |
| MSI MS-7A33                                | 1        | 0.79%   |
| MSI MS-7982                                | 1        | 0.79%   |
| MSI MS-7918                                | 1        | 0.79%   |
| MSI MS-7817                                | 1        | 0.79%   |
| MSI MS-7816                                | 1        | 0.79%   |
| MSI MS-7758                                | 1        | 0.79%   |
| MSI MS-7599                                | 1        | 0.79%   |
| MSI B02311                                 | 1        | 0.79%   |
| Medion MS-7797                             | 1        | 0.79%   |
| MACHINIST E5 MR9A PRO MAX V1.1             | 1        | 0.79%   |
| Lenovo ThinkStation D20 4158GK1            | 1        | 0.79%   |
| Lenovo ThinkCentre neo 50t Gen 3 11SE      | 1        | 0.79%   |
| Lenovo ThinkCentre M710q 10MQSC0N00        | 1        | 0.79%   |
| Lenovo T530-28ICB                          | 1        | 0.79%   |
| Lenovo IdeaCentre 510S-07ICB 90K800H1BF    | 1        | 0.79%   |
| Lenovo IdeaCentre 5 14IAB7 90T2000SUS      | 1        | 0.79%   |
| Lenovo H50-55 90BG000TFR                   | 1        | 0.79%   |
| Intel DH67CL AAG10212-210                  | 1        | 0.79%   |
| HP ProLiant ML350p Gen8                    | 1        | 0.79%   |
| HP ProLiant MicroServer                    | 1        | 0.79%   |
| HP ProDesk 600 G3 MT                       | 1        | 0.79%   |
| HP ProDesk 600 G2 DM                       | 1        | 0.79%   |
| HP Pavilion 590-p0049 3LC38AA              | 1        | 0.79%   |
| HP EliteDesk 800 G1 TWR                    | 1        | 0.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 10       | 7.94%   |
| HP Compaq                                  | 6        | 4.76%   |
| Unknown                                    | 6        | 4.76%   |
| ASUS ROG                                   | 5        | 3.97%   |
| HP EliteDesk                               | 4        | 3.17%   |
| Dell OptiPlex                              | 4        | 3.17%   |
| Lenovo ThinkCentre                         | 2        | 1.59%   |
| Lenovo IdeaCentre                          | 2        | 1.59%   |
| HP ProLiant                                | 2        | 1.59%   |
| HP ProDesk                                 | 2        | 1.59%   |
| HP Desktop                                 | 2        | 1.59%   |
| Gigabyte B85M-D3H                          | 2        | 1.59%   |
| ASUS TUF                                   | 2        | 1.59%   |
| ASUS P8Z77-V                               | 2        | 1.59%   |
| ASUS M5A78L-M                              | 2        | 1.59%   |
| ASUS M5A78L                                | 2        | 1.59%   |
| Acer Aspire                                | 2        | 1.59%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.79%   |
| MSI p6-2330                                | 1        | 0.79%   |
| MSI MS-7D43                                | 1        | 0.79%   |
| MSI MS-7C56                                | 1        | 0.79%   |
| MSI MS-7C52                                | 1        | 0.79%   |
| MSI MS-7C37                                | 1        | 0.79%   |
| MSI MS-7C09                                | 1        | 0.79%   |
| MSI MS-7C02                                | 1        | 0.79%   |
| MSI MS-7B84                                | 1        | 0.79%   |
| MSI MS-7A33                                | 1        | 0.79%   |
| MSI MS-7982                                | 1        | 0.79%   |
| MSI MS-7918                                | 1        | 0.79%   |
| MSI MS-7817                                | 1        | 0.79%   |
| MSI MS-7816                                | 1        | 0.79%   |
| MSI MS-7758                                | 1        | 0.79%   |
| MSI MS-7599                                | 1        | 0.79%   |
| MSI B02311                                 | 1        | 0.79%   |
| Medion MS-7797                             | 1        | 0.79%   |
| MACHINIST E5                               | 1        | 0.79%   |
| Lenovo ThinkStation                        | 1        | 0.79%   |
| Lenovo T530-28ICB                          | 1        | 0.79%   |
| Lenovo H50-55                              | 1        | 0.79%   |
| Intel DH67CL                               | 1        | 0.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 16       | 12.7%   |
| 2018 | 15       | 11.9%   |
| 2021 | 13       | 10.32%  |
| 2011 | 11       | 8.73%   |
| 2022 | 9        | 7.14%   |
| 2020 | 8        | 6.35%   |
| 2019 | 8        | 6.35%   |
| 2013 | 8        | 6.35%   |
| 2014 | 7        | 5.56%   |
| 2017 | 6        | 4.76%   |
| 2009 | 6        | 4.76%   |
| 2015 | 5        | 3.97%   |
| 2010 | 5        | 3.97%   |
| 2023 | 3        | 2.38%   |
| 2016 | 3        | 2.38%   |
| 2008 | 1        | 0.79%   |
| 2007 | 1        | 0.79%   |
| 2006 | 1        | 0.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 126      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 120      | 94.49%  |
| Enabled  | 7        | 5.51%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 126      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 26       | 20.63%  |
| 8.01-16.0   | 25       | 19.84%  |
| 16.01-24.0  | 22       | 17.46%  |
| 4.01-8.0    | 20       | 15.87%  |
| 3.01-4.0    | 16       | 12.7%   |
| 64.01-256.0 | 10       | 7.94%   |
| 24.01-32.0  | 5        | 3.97%   |
| 2.01-3.0    | 1        | 0.79%   |
| 1.01-2.0    | 1        | 0.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 42       | 31.58%  |
| 1.01-2.0   | 36       | 27.07%  |
| 4.01-8.0   | 24       | 18.05%  |
| 3.01-4.0   | 15       | 11.28%  |
| 8.01-16.0  | 11       | 8.27%   |
| 0.51-1.0   | 2        | 1.5%    |
| 32.01-64.0 | 1        | 0.75%   |
| 24.01-32.0 | 1        | 0.75%   |
| 16.01-24.0 | 1        | 0.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 42       | 33.33%  |
| 2      | 37       | 29.37%  |
| 3      | 19       | 15.08%  |
| 4      | 12       | 9.52%   |
| 6      | 6        | 4.76%   |
| 5      | 4        | 3.17%   |
| 0      | 2        | 1.59%   |
| 20     | 1        | 0.79%   |
| 9      | 1        | 0.79%   |
| 8      | 1        | 0.79%   |
| 7      | 1        | 0.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 68       | 53.97%  |
| No        | 58       | 46.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 126      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 69       | 54.76%  |
| Yes       | 57       | 45.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 85       | 67.46%  |
| Yes       | 41       | 32.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 20       | 15.87%  |
| France       | 15       | 11.9%   |
| Italy        | 14       | 11.11%  |
| Germany      | 13       | 10.32%  |
| Brazil       | 6        | 4.76%   |
| Australia    | 5        | 3.97%   |
| Switzerland  | 3        | 2.38%   |
| Russia       | 3        | 2.38%   |
| Portugal     | 3        | 2.38%   |
| Croatia      | 3        | 2.38%   |
| Canada       | 3        | 2.38%   |
| Belgium      | 3        | 2.38%   |
| Austria      | 3        | 2.38%   |
| Argentina    | 3        | 2.38%   |
| UK           | 2        | 1.59%   |
| Poland       | 2        | 1.59%   |
| Hungary      | 2        | 1.59%   |
| Finland      | 2        | 1.59%   |
| Denmark      | 2        | 1.59%   |
| Vietnam      | 1        | 0.79%   |
| Venezuela    | 1        | 0.79%   |
| Ukraine      | 1        | 0.79%   |
| Turkey       | 1        | 0.79%   |
| Taiwan       | 1        | 0.79%   |
| Spain        | 1        | 0.79%   |
| Saudi Arabia | 1        | 0.79%   |
| Peru         | 1        | 0.79%   |
| New Zealand  | 1        | 0.79%   |
| Netherlands  | 1        | 0.79%   |
| Morocco      | 1        | 0.79%   |
| Moldova      | 1        | 0.79%   |
| Mexico       | 1        | 0.79%   |
| Israel       | 1        | 0.79%   |
| Isle of Man  | 1        | 0.79%   |
| Greece       | 1        | 0.79%   |
| Estonia      | 1        | 0.79%   |
| Czechia      | 1        | 0.79%   |
| Algeria      | 1        | 0.79%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Rome             | 3        | 2.21%   |
| Zagreb           | 2        | 1.47%   |
| Melbourne        | 2        | 1.47%   |
| Lansdale         | 2        | 1.47%   |
| Forlì           | 2        | 1.47%   |
| Bologna          | 2        | 1.47%   |
| Zottegem         | 1        | 0.74%   |
| York             | 1        | 0.74%   |
| Yonkers          | 1        | 0.74%   |
| Wuelfrath        | 1        | 0.74%   |
| Wittingen        | 1        | 0.74%   |
| Whanganui        | 1        | 0.74%   |
| Washington       | 1        | 0.74%   |
| Warsaw           | 1        | 0.74%   |
| Villefontaine    | 1        | 0.74%   |
| Viljandi         | 1        | 0.74%   |
| Viana do Castelo | 1        | 0.74%   |
| Versailles       | 1        | 0.74%   |
| Velyki Mosty     | 1        | 0.74%   |
| Vancouver        | 1        | 0.74%   |
| Untersiggenthal  | 1        | 0.74%   |
| Uberaba          | 1        | 0.74%   |
| Turku            | 1        | 0.74%   |
| Toulon           | 1        | 0.74%   |
| Torring          | 1        | 0.74%   |
| Tighina          | 1        | 0.74%   |
| Terrace          | 1        | 0.74%   |
| Tel Aviv         | 1        | 0.74%   |
| Taranto          | 1        | 0.74%   |
| Tampere          | 1        | 0.74%   |
| Talence          | 1        | 0.74%   |
| Stuttgart        | 1        | 0.74%   |
| St Petersburg    | 1        | 0.74%   |
| Split            | 1        | 0.74%   |
| Singen           | 1        | 0.74%   |
| Seia             | 1        | 0.74%   |
| Schmelz          | 1        | 0.74%   |
| Santo André     | 1        | 0.74%   |
| Samara           | 1        | 0.74%   |
| Saint-Etienne    | 1        | 0.74%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 48       | 84     | 21.62%  |
| Seagate               | 35       | 65     | 15.77%  |
| Samsung Electronics   | 34       | 73     | 15.32%  |
| Kingston              | 14       | 20     | 6.31%   |
| Crucial               | 13       | 17     | 5.86%   |
| SanDisk               | 10       | 13     | 4.5%    |
| Toshiba               | 7        | 31     | 3.15%   |
| Hitachi               | 6        | 8      | 2.7%    |
| Unknown               | 5        | 10     | 2.25%   |
| A-DATA Technology     | 5        | 6      | 2.25%   |
| Intel                 | 4        | 4      | 1.8%    |
| SPCC                  | 3        | 5      | 1.35%   |
| Phison Electronics    | 3        | 3      | 1.35%   |
| Phison                | 3        | 3      | 1.35%   |
| SK hynix              | 2        | 2      | 0.9%    |
| KingSpec              | 2        | 2      | 0.9%    |
| KingFast              | 2        | 2      | 0.9%    |
| China                 | 2        | 2      | 0.9%    |
| ASMT                  | 2        | 3      | 0.9%    |
| Apacer                | 2        | 2      | 0.9%    |
| Transcend             | 1        | 5      | 0.45%   |
| Team                  | 1        | 1      | 0.45%   |
| RZX                   | 1        | 1      | 0.45%   |
| Realtek Semiconductor | 1        | 1      | 0.45%   |
| PNY                   | 1        | 1      | 0.45%   |
| Pichau                | 1        | 1      | 0.45%   |
| OCZ                   | 1        | 1      | 0.45%   |
| NGFF                  | 1        | 1      | 0.45%   |
| Maxtor                | 1        | 1      | 0.45%   |
| LDLC                  | 1        | 1      | 0.45%   |
| KIOXIA-EXCERIA        | 1        | 1      | 0.45%   |
| Kimtigo               | 1        | 1      | 0.45%   |
| KESU                  | 1        | 1      | 0.45%   |
| Intenso               | 1        | 1      | 0.45%   |
| Hewlett-Packard       | 1        | 4      | 0.45%   |
| GOODRAM               | 1        | 1      | 0.45%   |
| DAS                   | 1        | 6      | 0.45%   |
| Corsair               | 1        | 1      | 0.45%   |
| BAITITON              | 1        | 1      | 0.45%   |
| Unknown               | 1        | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                            | 5        | 1.79%   |
| Seagate ST500DM002-1BD142 500GB                     | 5        | 1.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 5        | 1.79%   |
| Seagate ST1000DM003-1ER162 1TB                      | 4        | 1.43%   |
| Kingston SA400S37120G 120GB SSD                     | 4        | 1.43%   |
| WDC WD5003AZEX-00K3CA0 500GB                        | 3        | 1.07%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 3        | 1.07%   |
| Unknown SD/MMC 2GB                                  | 3        | 1.07%   |
| Unknown M.S./M.S.Pro/HG 16GB                        | 3        | 1.07%   |
| Seagate ST2000DM008-2FR102 2TB                      | 3        | 1.07%   |
| Seagate ST2000DM001-1ER164 2TB                      | 3        | 1.07%   |
| Samsung SSD 870 QVO 1TB                             | 3        | 1.07%   |
| Samsung SSD 870 EVO 500GB                           | 3        | 1.07%   |
| Kingston SA400S37480G 480GB SSD                     | 3        | 1.07%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 2        | 0.71%   |
| WDC WD40EZAZ-00SF3B0 4TB                            | 2        | 0.71%   |
| Toshiba DT01ACA100 1TB                              | 2        | 0.71%   |
| Seagate ST4000DM004-2CV104 4TB                      | 2        | 0.71%   |
| Seagate ST1000DM003-1SB102 1TB                      | 2        | 0.71%   |
| Samsung SSD 980 PRO 1TB                             | 2        | 0.71%   |
| Samsung SSD 980 1TB                                 | 2        | 0.71%   |
| Samsung SSD 870 QVO 2TB                             | 2        | 0.71%   |
| Samsung SSD 860 QVO 1TB                             | 2        | 0.71%   |
| Samsung SSD 860 PRO 256GB                           | 2        | 0.71%   |
| Samsung SSD 860 EVO 500GB                           | 2        | 0.71%   |
| Samsung SSD 840 Series 120GB                        | 2        | 0.71%   |
| Samsung NVMe SSD Drive 1TB                          | 2        | 0.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 2        | 0.71%   |
| Samsung HD103SI 1TB                                 | 2        | 0.71%   |
| Kingston SNVS500G 500GB                             | 2        | 0.71%   |
| Crucial CT480BX500SSD1 480GB                        | 2        | 0.71%   |
| Crucial CT240BX500SSD1 240GB                        | 2        | 0.71%   |
| Crucial CT2000MX500SSD1 2TB                         | 2        | 0.71%   |
| Crucial CT1000BX500SSD1 1TB                         | 2        | 0.71%   |
| A-DATA SU800 256GB SSD                              | 2        | 0.71%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1        | 0.36%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1        | 0.36%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1        | 0.36%   |
| WDC WD8001FZBX-00ASYA0 8TB                          | 1        | 0.36%   |
| WDC WD6400AAKS-00E4A0 640GB                         | 1        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 46       | 79     | 44.23%  |
| Seagate             | 35       | 65     | 33.65%  |
| Toshiba             | 7        | 31     | 6.73%   |
| Hitachi             | 6        | 8      | 5.77%   |
| Samsung Electronics | 5        | 11     | 4.81%   |
| Maxtor              | 1        | 1      | 0.96%   |
| KESU                | 1        | 1      | 0.96%   |
| Hewlett-Packard     | 1        | 4      | 0.96%   |
| DAS                 | 1        | 6      | 0.96%   |
| ASMT                | 1        | 2      | 0.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 21       | 37     | 25.93%  |
| Crucial             | 12       | 16     | 14.81%  |
| Kingston            | 10       | 16     | 12.35%  |
| SanDisk             | 6        | 8      | 7.41%   |
| WDC                 | 3        | 3      | 3.7%    |
| SPCC                | 3        | 5      | 3.7%    |
| A-DATA Technology   | 3        | 3      | 3.7%    |
| KingSpec            | 2        | 2      | 2.47%   |
| KingFast            | 2        | 2      | 2.47%   |
| China               | 2        | 2      | 2.47%   |
| Apacer              | 2        | 2      | 2.47%   |
| Unknown             | 1        | 1      | 1.23%   |
| Transcend           | 1        | 5      | 1.23%   |
| Team                | 1        | 1      | 1.23%   |
| RZX                 | 1        | 1      | 1.23%   |
| PNY                 | 1        | 1      | 1.23%   |
| Pichau              | 1        | 1      | 1.23%   |
| OCZ                 | 1        | 1      | 1.23%   |
| NGFF                | 1        | 1      | 1.23%   |
| LDLC                | 1        | 1      | 1.23%   |
| KIOXIA-EXCERIA      | 1        | 1      | 1.23%   |
| Intel               | 1        | 1      | 1.23%   |
| GOODRAM             | 1        | 1      | 1.23%   |
| BAITITON            | 1        | 1      | 1.23%   |
| ASMT                | 1        | 1      | 1.23%   |
| Unknown             | 1        | 1      | 1.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 83       | 208    | 43.01%  |
| SSD     | 68       | 115    | 35.23%  |
| NVMe    | 38       | 54     | 19.69%  |
| Unknown | 3        | 9      | 1.55%   |
| MMC     | 1        | 1      | 0.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 111      | 306    | 69.38%  |
| NVMe | 38       | 54     | 23.75%  |
| SAS  | 10       | 26     | 6.25%   |
| MMC  | 1        | 1      | 0.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 83       | 138    | 46.37%  |
| 0.51-1.0   | 50       | 94     | 27.93%  |
| 1.01-2.0   | 23       | 30     | 12.85%  |
| 3.01-4.0   | 12       | 17     | 6.7%    |
| 4.01-10.0  | 6        | 35     | 3.35%   |
| 2.01-3.0   | 5        | 9      | 2.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 25       | 19.23%  |
| 501-1000       | 24       | 18.46%  |
| 251-500        | 23       | 17.69%  |
| More than 3000 | 22       | 16.92%  |
| 1001-2000      | 15       | 11.54%  |
| 2001-3000      | 6        | 4.62%   |
| 1-20           | 5        | 3.85%   |
| 21-50          | 4        | 3.08%   |
| 51-100         | 4        | 3.08%   |
| Unknown        | 2        | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 30       | 22.39%  |
| 101-250        | 21       | 15.67%  |
| 21-50          | 18       | 13.43%  |
| 51-100         | 14       | 10.45%  |
| 501-1000       | 13       | 9.7%    |
| More than 3000 | 12       | 8.96%   |
| 1001-2000      | 11       | 8.21%   |
| 251-500        | 9        | 6.72%   |
| 2001-3000      | 4        | 2.99%   |
| Unknown        | 2        | 1.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                 | Desktops | Drives | Percent |
|-------------------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                       | 2        | 2      | 11.76%  |
| WDC WD5000AAKX-22ERMA0 500GB                          | 1        | 1      | 5.88%   |
| WDC WD5000AADS-00S9B0 500GB                           | 1        | 1      | 5.88%   |
| WDC WD10EAVS-00D7B0 1TB                               | 1        | 1      | 5.88%   |
| WDC WD1003FZEX-00MK2A0 1TB                            | 1        | 1      | 5.88%   |
| Seagate ST3250312AS 250GB                             | 1        | 1      | 5.88%   |
| Seagate ST2000DM001-1ER164 2TB                        | 1        | 1      | 5.88%   |
| Seagate ST1000DM003-1ER162 1TB                        | 1        | 1      | 5.88%   |
| Samsung Electronics SSD 970 EVO 500GB S466NX0K863648L | 1        | 1      | 5.88%   |
| Samsung Electronics SSD 960 PRO 1TB                   | 1        | 1      | 5.88%   |
| OCZ AGILITY3 240GB SSD                                | 1        | 1      | 5.88%   |
| NGFF 2280 256GB SSD                                   | 1        | 1      | 5.88%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD               | 1        | 1      | 5.88%   |
| Hitachi HTS721080G9SA00 80GB                          | 1        | 1      | 5.88%   |
| DAS TerraMaster 6TB                                   | 1        | 3      | 5.88%   |
| China SSD 180GB                                       | 1        | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 5      | 29.41%  |
| WDC                 | 4        | 4      | 23.53%  |
| Samsung Electronics | 2        | 2      | 11.76%  |
| OCZ                 | 1        | 1      | 5.88%   |
| NGFF                | 1        | 1      | 5.88%   |
| Kingston            | 1        | 1      | 5.88%   |
| Hitachi             | 1        | 1      | 5.88%   |
| DAS                 | 1        | 3      | 5.88%   |
| China               | 1        | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 5        | 5      | 45.45%  |
| WDC     | 4        | 4      | 36.36%  |
| Hitachi | 1        | 1      | 9.09%   |
| DAS     | 1        | 3      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 13     | 62.5%   |
| SSD  | 4        | 4      | 25%     |
| NVMe | 2        | 2      | 12.5%   |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 72       | 211    | 49.66%  |
| Detected | 57       | 157    | 39.31%  |
| Malfunc  | 16       | 19     | 11.03%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 81       | 46.02%  |
| AMD                         | 45       | 25.57%  |
| Samsung Electronics         | 14       | 7.95%   |
| ASMedia Technology          | 8        | 4.55%   |
| Phison Electronics          | 7        | 3.98%   |
| SanDisk                     | 5        | 2.84%   |
| Kingston Technology Company | 4        | 2.27%   |
| SK hynix                    | 2        | 1.14%   |
| Marvell Technology Group    | 2        | 1.14%   |
| JMicron Technology          | 2        | 1.14%   |
| ADATA Technology            | 2        | 1.14%   |
| Silicon Motion              | 1        | 0.57%   |
| Realtek Semiconductor       | 1        | 0.57%   |
| Micron/Crucial Technology   | 1        | 0.57%   |
| Hewlett-Packard             | 1        | 0.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 28       | 12.5%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 11       | 4.91%   |
| AMD 400 Series Chipset SATA Controller                                         | 9        | 4.02%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 8        | 3.57%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 8        | 3.57%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 8        | 3.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7        | 3.13%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 7        | 3.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 7        | 3.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6        | 2.68%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 6        | 2.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6        | 2.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5        | 2.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5        | 2.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 1.79%   |
| AMD FCH SATA Controller D                                                      | 4        | 1.79%   |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 1.79%   |
| Kingston Company NV1 NVMe SSD SM2263XT                                         | 3        | 1.34%   |
| Intel SATA Controller [RAID mode]                                              | 3        | 1.34%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3        | 1.34%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3        | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3        | 1.34%   |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 1.34%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 0.89%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2        | 0.89%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2        | 0.89%   |
| Phison E8 PCIe3 NVMe Controller                                                | 2        | 0.89%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 0.89%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2        | 0.89%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 0.89%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2        | 0.89%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]  | 2        | 0.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2        | 0.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2        | 0.89%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2        | 0.89%   |
| AMD X370 Series Chipset SATA Controller                                        | 2        | 0.89%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1        | 0.45%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1        | 0.45%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1        | 0.45%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 109      | 59.56%  |
| NVMe | 38       | 20.77%  |
| IDE  | 25       | 13.66%  |
| RAID | 11       | 6.01%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 81       | 64.29%  |
| AMD    | 45       | 35.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz              | 3        | 2.38%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3        | 2.38%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 3        | 2.38%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 3        | 2.38%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2        | 1.59%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2        | 1.59%   |
| Intel Core i5-6600 CPU @ 3.30GHz              | 2        | 1.59%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2        | 1.59%   |
| Intel Core i5-2320 CPU @ 3.00GHz              | 2        | 1.59%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 2        | 1.59%   |
| Intel Celeron J4105 CPU @ 1.50GHz             | 2        | 1.59%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz       | 2        | 1.59%   |
| Intel 11th Gen Core i5-11600K @ 3.90GHz       | 2        | 1.59%   |
| AMD Ryzen 7 7700 8-Core Processor             | 2        | 1.59%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2        | 1.59%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 2        | 1.59%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 2        | 1.59%   |
| AMD FX-6300 Six-Core Processor                | 2        | 1.59%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G | 2        | 1.59%   |
| Intel Xeon D-2796TE CPU @ 2.00GHz             | 1        | 0.79%   |
| Intel Xeon CPU E5620 @ 2.40GHz                | 1        | 0.79%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz           | 1        | 0.79%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz           | 1        | 0.79%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz            | 1        | 0.79%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz            | 1        | 0.79%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz           | 1        | 0.79%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz   | 1        | 0.79%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 1        | 0.79%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 1        | 0.79%   |
| Intel Pentium CPU G3240 @ 3.10GHz             | 1        | 0.79%   |
| Intel Pentium CPU G3220 @ 3.00GHz             | 1        | 0.79%   |
| Intel Pentium CPU G2020 @ 2.90GHz             | 1        | 0.79%   |
| Intel Pentium 4 CPU 3.06GHz                   | 1        | 0.79%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1        | 0.79%   |
| Intel Core i7-6800K CPU @ 3.40GHz             | 1        | 0.79%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1        | 0.79%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1        | 0.79%   |
| Intel Core i7-4770K CPU @ 3.50GHz             | 1        | 0.79%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 1        | 0.79%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 1        | 0.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 28       | 22.22%  |
| AMD Ryzen 5             | 14       | 11.11%  |
| Other                   | 12       | 9.52%   |
| Intel Core i7           | 12       | 9.52%   |
| Intel Xeon              | 7        | 5.56%   |
| Intel Core i3           | 7        | 5.56%   |
| AMD FX                  | 6        | 4.76%   |
| Intel Celeron           | 5        | 3.97%   |
| AMD Ryzen 7             | 5        | 3.97%   |
| Intel Pentium           | 4        | 3.17%   |
| AMD Ryzen 9             | 3        | 2.38%   |
| AMD Ryzen 3             | 3        | 2.38%   |
| AMD A8                  | 3        | 2.38%   |
| Intel Pentium Dual-Core | 2        | 1.59%   |
| Intel Core 2 Duo        | 2        | 1.59%   |
| AMD E                   | 2        | 1.59%   |
| AMD Athlon II X2        | 2        | 1.59%   |
| Intel Pentium 4         | 1        | 0.79%   |
| Intel Core 2 Quad       | 1        | 0.79%   |
| AMD Turion II Neo       | 1        | 0.79%   |
| AMD Phenom II X6        | 1        | 0.79%   |
| AMD Athlon II X4        | 1        | 0.79%   |
| AMD Athlon              | 1        | 0.79%   |
| AMD A6                  | 1        | 0.79%   |
| AMD A4                  | 1        | 0.79%   |
| AMD A10                 | 1        | 0.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 44       | 34.92%  |
| 2      | 28       | 22.22%  |
| 6      | 26       | 20.63%  |
| 8      | 13       | 10.32%  |
| 3      | 3        | 2.38%   |
| 1      | 3        | 2.38%   |
| 20     | 2        | 1.59%   |
| 16     | 2        | 1.59%   |
| 12     | 2        | 1.59%   |
| 10     | 2        | 1.59%   |
| 14     | 1        | 0.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 124      | 98.41%  |
| 2      | 2        | 1.59%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 74       | 58.73%  |
| 1      | 52       | 41.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 126      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 61       | 47.29%  |
| 0x206a7    | 6        | 4.65%   |
| 0xa0671    | 5        | 3.88%   |
| 0x506e3    | 5        | 3.88%   |
| 0x306c3    | 5        | 3.88%   |
| 0x306a9    | 4        | 3.1%    |
| 0x0a50000c | 4        | 3.1%    |
| 0x906ea    | 3        | 2.33%   |
| 0x08108109 | 3        | 2.33%   |
| 0x0800820d | 3        | 2.33%   |
| 0xa0653    | 2        | 1.55%   |
| 0x20655    | 2        | 1.55%   |
| 0x0a50000d | 2        | 1.55%   |
| 0x0600611a | 2        | 1.55%   |
| 0x06001119 | 2        | 1.55%   |
| 0x06000852 | 2        | 1.55%   |
| 0x05000119 | 2        | 1.55%   |
| 0x906ed    | 1        | 0.78%   |
| 0x90672    | 1        | 0.78%   |
| 0x706a1    | 1        | 0.78%   |
| 0x6fd      | 1        | 0.78%   |
| 0x606c1    | 1        | 0.78%   |
| 0x306f2    | 1        | 0.78%   |
| 0x206d7    | 1        | 0.78%   |
| 0x106e5    | 1        | 0.78%   |
| 0x1067a    | 1        | 0.78%   |
| 0x10677    | 1        | 0.78%   |
| 0x0a601203 | 1        | 0.78%   |
| 0x0810100b | 1        | 0.78%   |
| 0x06003106 | 1        | 0.78%   |
| 0x0600063e | 1        | 0.78%   |
| 0x010000dc | 1        | 0.78%   |
| 0x010000c8 | 1        | 0.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 12       | 9.45%   |
| Unknown          | 11       | 8.66%   |
| SandyBridge      | 9        | 7.09%   |
| IvyBridge        | 9        | 7.09%   |
| Zen 3            | 8        | 6.3%    |
| Skylake          | 8        | 6.3%    |
| KabyLake         | 8        | 6.3%    |
| Zen+             | 7        | 5.51%   |
| Zen              | 6        | 4.72%   |
| Piledriver       | 6        | 4.72%   |
| K10              | 5        | 3.94%   |
| Icelake          | 5        | 3.94%   |
| Westmere         | 4        | 3.15%   |
| Penryn           | 4        | 3.15%   |
| CometLake        | 4        | 3.15%   |
| Zen 2            | 3        | 2.36%   |
| Goldmont plus    | 3        | 2.36%   |
| Excavator        | 3        | 2.36%   |
| Bulldozer        | 2        | 1.57%   |
| Broadwell        | 2        | 1.57%   |
| Bobcat           | 2        | 1.57%   |
| Tremont          | 1        | 0.79%   |
| Steamroller      | 1        | 0.79%   |
| NetBurst         | 1        | 0.79%   |
| Nehalem          | 1        | 0.79%   |
| Core             | 1        | 0.79%   |
| Alderlake Hybrid | 1        | 0.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 46       | 34.33%  |
| AMD                        | 46       | 34.33%  |
| Nvidia                     | 40       | 29.85%  |
| Matrox Electronics Systems | 1        | 0.75%   |
| ASPEED Technology          | 1        | 0.75%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 5.15%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 7        | 5.15%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 4.41%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 5        | 3.68%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 3.68%   |
| Intel HD Graphics 530                                                       | 5        | 3.68%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 3.68%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 2.94%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 2.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 2.94%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 2.21%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3        | 2.21%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 3        | 2.21%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 2.21%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.47%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 1.47%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 1.47%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 2        | 1.47%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.47%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.47%   |
| AMD Redwood PRO [Radeon HD 5550/5570/5630/6510/6610/7570]                   | 2        | 1.47%   |
| AMD Raphael                                                                 | 2        | 1.47%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.47%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 1.47%   |
| Nvidia TU117GL [T400 4GB]                                                   | 1        | 0.74%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.74%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.74%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.74%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.74%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 0.74%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.74%   |
| Nvidia GM206GL [Quadro M2000]                                               | 1        | 0.74%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 0.74%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 0.74%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.74%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 0.74%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 0.74%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 0.74%   |
| Nvidia GF110 [GeForce GTX 580]                                              | 1        | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 42       | 33.33%  |
| 1 x Intel      | 39       | 30.95%  |
| 1 x Nvidia     | 36       | 28.57%  |
| Intel + Nvidia | 3        | 2.38%   |
| 2 x AMD        | 2        | 1.59%   |
| 1 x Matrox     | 1        | 0.79%   |
| Intel + AMD    | 1        | 0.79%   |
| 1 x ASPEED     | 1        | 0.79%   |
| AMD + Nvidia   | 1        | 0.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 95       | 74.8%   |
| Proprietary | 30       | 23.62%  |
| Unknown     | 2        | 1.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 68       | 53.54%  |
| 0.51-1.0   | 14       | 11.02%  |
| 1.01-2.0   | 12       | 9.45%   |
| 0.01-0.5   | 12       | 9.45%   |
| 3.01-4.0   | 8        | 6.3%    |
| 5.01-6.0   | 6        | 4.72%   |
| 7.01-8.0   | 4        | 3.15%   |
| 2.01-3.0   | 1        | 0.79%   |
| 16.01-24.0 | 1        | 0.79%   |
| 8.01-16.0  | 1        | 0.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 28       | 19.72%  |
| Goldstar             | 20       | 14.08%  |
| Philips              | 12       | 8.45%   |
| Hewlett-Packard      | 11       | 7.75%   |
| Dell                 | 11       | 7.75%   |
| Acer                 | 10       | 7.04%   |
| Iiyama               | 7        | 4.93%   |
| BenQ                 | 5        | 3.52%   |
| Ancor Communications | 4        | 2.82%   |
| ViewSonic            | 3        | 2.11%   |
| AOC                  | 3        | 2.11%   |
| Sony                 | 2        | 1.41%   |
| NEC Computers        | 2        | 1.41%   |
| Lenovo               | 2        | 1.41%   |
| Westinghouse         | 1        | 0.7%    |
| VMO                  | 1        | 0.7%    |
| Vizio                | 1        | 0.7%    |
| Vita                 | 1        | 0.7%    |
| SNC                  | 1        | 0.7%    |
| SGX                  | 1        | 0.7%    |
| Sceptre Tech         | 1        | 0.7%    |
| PXO                  | 1        | 0.7%    |
| Packard Bell         | 1        | 0.7%    |
| Medion               | 1        | 0.7%    |
| LG Electronics       | 1        | 0.7%    |
| Lenovo Group Limited | 1        | 0.7%    |
| Kogan                | 1        | 0.7%    |
| Insignia             | 1        | 0.7%    |
| Idek Iiyama          | 1        | 0.7%    |
| HPN                  | 1        | 0.7%    |
| Gateway              | 1        | 0.7%    |
| Fujitsu Siemens      | 1        | 0.7%    |
| Envision Peripherals | 1        | 0.7%    |
| D&T                  | 1        | 0.7%    |
| CHR                  | 1        | 0.7%    |
| ASUSTek Computer     | 1        | 0.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM01E1 1280x1024 380x300mm 19.1-inch | 2        | 1.32%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x290mm 23.1-inch    | 2        | 1.32%   |
| Philips PHL 272B8Q PHL0918 2560x1440 597x336mm 27.0-inch             | 2        | 1.32%   |
| Goldstar E2240 GSM57A3 1920x1080 477x268mm 21.5-inch                 | 2        | 1.32%   |
| Dell U2715H DELD066 2560x1440 600x340mm 27.2-inch                    | 2        | 1.32%   |
| Acer ET322QU ACR0687 2560x1440 698x393mm 31.5-inch                   | 2        | 1.32%   |
| Westinghouse DWM40F1D1 WDT7811 1920x1080 890x500mm 40.2-inch         | 1        | 0.66%   |
| VMO LCD WQXGA HDM VMO1506 2560x1600 1600x1000mm 74.3-inch            | 1        | 0.66%   |
| Vizio M470NV VIZ0063 1920x1080 1040x585mm 47.0-inch                  | 1        | 0.66%   |
| Vita LCD Monitor VIT0780 1920x1080                                   | 1        | 0.66%   |
| ViewSonic VX2776-4K-mhd VSC7137 3840x2160 608x355mm 27.7-inch        | 1        | 0.66%   |
| ViewSonic VA2431 Series VSCD824 1920x1080 521x293mm 23.5-inch        | 1        | 0.66%   |
| ViewSonic VA2046 SERIES VSC6D2E 1600x900 430x240mm 19.4-inch         | 1        | 0.66%   |
| Sony TV SNY3002 1920x1080 1018x573mm 46.0-inch                       | 1        | 0.66%   |
| Sony LCD Monitor TV 3840x1080                                        | 1        | 0.66%   |
| Sony LCD Monitor TV                                                  | 1        | 0.66%   |
| SNC SKP_E20-32 SNC3200 1920x1080 477x268mm 21.5-inch                 | 1        | 0.66%   |
| SGX LCD Monitor SGX1000 1280x1024                                    | 1        | 0.66%   |
| Sceptre Tech Sceptre H40 SPT0FF1 1920x1080 575x323mm 26.0-inch       | 1        | 0.66%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch    | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM0225 1440x900 410x257mm 19.1-inch  | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch  | 1        | 0.66%   |
| Samsung Electronics SyncMaster SAM006A 1280x1024 338x270mm 17.0-inch | 1        | 0.66%   |
| Samsung Electronics SMS22A300B SAM078E 1920x1080 477x268mm 21.5-inch | 1        | 0.66%   |
| Samsung Electronics SMBX2440 SAM068A 1920x1080 531x299mm 24.0-inch   | 1        | 0.66%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 1        | 0.66%   |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch     | 1        | 0.66%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 1        | 0.66%   |
| Samsung Electronics S32F351 SAM0D24 1920x1080 698x393mm 31.5-inch    | 1        | 0.66%   |
| Samsung Electronics S27F358 SAM0D72 1920x1080 598x336mm 27.0-inch    | 1        | 0.66%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch    | 1        | 0.66%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch    | 1        | 0.66%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 1        | 0.66%   |
| Samsung Electronics S22E450 SAM0C79 1920x1080 477x268mm 21.5-inch    | 1        | 0.66%   |
| Samsung Electronics S19C301 SAM0B07 1366x768 410x230mm 18.5-inch     | 1        | 0.66%   |
| Samsung Electronics LCD Monitor SyncMaster 3840x1080                 | 1        | 0.66%   |
| Samsung Electronics LCD Monitor SMBX2440                             | 1        | 0.66%   |
| Samsung Electronics LCD Monitor SAM0D4B 1366x768 609x347mm 27.6-inch | 1        | 0.66%   |
| Samsung Electronics LCD Monitor SAM08FE 1920x1080                    | 1        | 0.66%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 68       | 50.75%  |
| 2560x1440 (QHD)    | 11       | 8.21%   |
| 1280x1024 (SXGA)   | 11       | 8.21%   |
| 3840x2160 (4K)     | 8        | 5.97%   |
| 1680x1050 (WSXGA+) | 5        | 3.73%   |
| 1440x900 (WXGA+)   | 4        | 2.99%   |
| 1366x768 (WXGA)    | 4        | 2.99%   |
| Unknown            | 4        | 2.99%   |
| 3440x1440          | 3        | 2.24%   |
| 1920x1200 (WUXGA)  | 3        | 2.24%   |
| 1600x900 (HD+)     | 3        | 2.24%   |
| 3840x1080          | 2        | 1.49%   |
| 1360x768           | 2        | 1.49%   |
| 4480x1440          | 1        | 0.75%   |
| 3840x1600          | 1        | 0.75%   |
| 3840x1200          | 1        | 0.75%   |
| 2560x1600          | 1        | 0.75%   |
| 2560x1080          | 1        | 0.75%   |
| 1280x720 (HD)      | 1        | 0.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 25       | 17.99%  |
| 21      | 20       | 14.39%  |
| 24      | 17       | 12.23%  |
| 23      | 15       | 10.79%  |
| Unknown | 12       | 8.63%   |
| 31      | 8        | 5.76%   |
| 19      | 8        | 5.76%   |
| 17      | 7        | 5.04%   |
| 34      | 5        | 3.6%    |
| 18      | 5        | 3.6%    |
| 22      | 3        | 2.16%   |
| 46      | 2        | 1.44%   |
| 38      | 2        | 1.44%   |
| 26      | 2        | 1.44%   |
| 74      | 1        | 0.72%   |
| 72      | 1        | 0.72%   |
| 54      | 1        | 0.72%   |
| 40      | 1        | 0.72%   |
| 33      | 1        | 0.72%   |
| 25      | 1        | 0.72%   |
| 20      | 1        | 0.72%   |
| 15      | 1        | 0.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 50       | 37.04%  |
| 401-500     | 34       | 25.19%  |
| 601-700     | 13       | 9.63%   |
| Unknown     | 12       | 8.89%   |
| 301-350     | 8        | 5.93%   |
| 701-800     | 6        | 4.44%   |
| 351-400     | 4        | 2.96%   |
| 801-900     | 3        | 2.22%   |
| 1001-1500   | 3        | 2.22%   |
| 1501-2000   | 2        | 1.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 86       | 67.19%  |
| 16/10   | 16       | 12.5%   |
| 5/4     | 12       | 9.38%   |
| Unknown | 8        | 6.25%   |
| 21/9    | 6        | 4.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 43       | 31.85%  |
| 301-350        | 25       | 18.52%  |
| 351-500        | 14       | 10.37%  |
| 151-200        | 14       | 10.37%  |
| Unknown        | 12       | 8.89%   |
| 141-150        | 10       | 7.41%   |
| 251-300        | 8        | 5.93%   |
| 501-1000       | 5        | 3.7%    |
| More than 1000 | 3        | 2.22%   |
| 101-110        | 1        | 0.74%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 77       | 59.23%  |
| 101-120 | 31       | 23.85%  |
| Unknown | 12       | 9.23%   |
| 1-50    | 5        | 3.85%   |
| 121-160 | 5        | 3.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 92       | 71.88%  |
| 2     | 33       | 25.78%  |
| 0     | 3        | 2.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 87       | 50%     |
| Intel                           | 53       | 30.46%  |
| Broadcom                        | 8        | 4.6%    |
| Qualcomm Atheros                | 7        | 4.02%   |
| MediaTek                        | 5        | 2.87%   |
| TP-Link                         | 3        | 1.72%   |
| Ralink                          | 3        | 1.72%   |
| Xiaomi                          | 1        | 0.57%   |
| Qualcomm Atheros Communications | 1        | 0.57%   |
| NetXen Incorporated             | 1        | 0.57%   |
| NetGear                         | 1        | 0.57%   |
| Motorola PCS                    | 1        | 0.57%   |
| Marvell Technology Group        | 1        | 0.57%   |
| Broadcom Limited                | 1        | 0.57%   |
| ASUSTek Computer                | 1        | 0.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 67       | 34.18%  |
| Realtek RTL8125 2.5GbE Controller                                 | 10       | 5.1%    |
| Intel Ethernet Controller I225-V                                  | 9        | 4.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 2.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4        | 2.04%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.04%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3        | 1.53%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.53%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 3        | 1.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2        | 1.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.02%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2        | 1.02%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2        | 1.02%   |
| Realtek 802.11ac NIC                                              | 2        | 1.02%   |
| Intel Wireless 7265                                               | 2        | 1.02%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2        | 1.02%   |
| Intel I211 Gigabit Network Connection                             | 2        | 1.02%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 1.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2        | 1.02%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.02%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.02%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 2        | 1.02%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.51%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.51%   |
| TP-Link Archer T4U ver.3                                          | 1        | 0.51%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.51%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.51%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1        | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 0.51%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 0.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1        | 0.51%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.51%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.51%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 20       | 35.09%  |
| Realtek Semiconductor           | 18       | 31.58%  |
| MediaTek                        | 5        | 8.77%   |
| TP-Link                         | 3        | 5.26%   |
| Ralink                          | 3        | 5.26%   |
| Qualcomm Atheros                | 3        | 5.26%   |
| Broadcom                        | 2        | 3.51%   |
| Qualcomm Atheros Communications | 1        | 1.75%   |
| NetGear                         | 1        | 1.75%   |
| ASUSTek Computer                | 1        | 1.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4        | 7.02%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3        | 5.26%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 3        | 5.26%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2        | 3.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2        | 3.51%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 2        | 3.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2        | 3.51%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 2        | 3.51%   |
| Realtek 802.11ac NIC                                           | 2        | 3.51%   |
| Intel Wireless 7265                                            | 2        | 3.51%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2        | 3.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2        | 3.51%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2        | 3.51%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1        | 1.75%   |
| TP-Link Archer T4U ver.3                                       | 1        | 1.75%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 1.75%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1        | 1.75%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1        | 1.75%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1        | 1.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1        | 1.75%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 1.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1        | 1.75%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1        | 1.75%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1        | 1.75%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 1        | 1.75%   |
| Qualcomm Atheros AR9271 802.11n                                | 1        | 1.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1        | 1.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1        | 1.75%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 1.75%   |
| NetGear A6150                                                  | 1        | 1.75%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 1        | 1.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1        | 1.75%   |
| Intel Wireless 3165                                            | 1        | 1.75%   |
| Intel Wireless 3160                                            | 1        | 1.75%   |
| Intel Wi-Fi 6 AX200                                            | 1        | 1.75%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1        | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1        | 1.75%   |
| Broadcom Network controller                                    | 1        | 1.75%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1        | 1.75%   |
| ASUS 802.11ac NIC                                              | 1        | 1.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 80       | 59.7%   |
| Intel                    | 39       | 29.1%   |
| Broadcom                 | 6        | 4.48%   |
| Qualcomm Atheros         | 4        | 2.99%   |
| Xiaomi                   | 1        | 0.75%   |
| NetXen Incorporated      | 1        | 0.75%   |
| Motorola PCS             | 1        | 0.75%   |
| Marvell Technology Group | 1        | 0.75%   |
| Broadcom Limited         | 1        | 0.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 67       | 48.2%   |
| Realtek RTL8125 2.5GbE Controller                                    | 10       | 7.19%   |
| Intel Ethernet Controller I225-V                                     | 9        | 6.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 5        | 3.6%    |
| Intel Ethernet Connection (2) I219-V                                 | 4        | 2.88%   |
| Intel Ethernet Connection I217-LM                                    | 3        | 2.16%   |
| Intel I211 Gigabit Network Connection                                | 2        | 1.44%   |
| Intel Ethernet Connection (2) I218-V                                 | 2        | 1.44%   |
| Intel 82579V Gigabit Network Connection                              | 2        | 1.44%   |
| Intel 82567LM-3 Gigabit Network Connection                           | 2        | 1.44%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                      | 2        | 1.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1        | 0.72%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                      | 1        | 0.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 1        | 0.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                                | 1        | 0.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 1        | 0.72%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1        | 0.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller            | 1        | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 1        | 0.72%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                        | 1        | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                             | 1        | 0.72%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1        | 0.72%   |
| Motorola PCS motorola edge 40                                        | 1        | 0.72%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                    | 1        | 0.72%   |
| Intel I210 Gigabit Network Connection                                | 1        | 0.72%   |
| Intel Ethernet Controller I225-IT                                    | 1        | 0.72%   |
| Intel Ethernet Connection I217-V                                     | 1        | 0.72%   |
| Intel Ethernet Connection E823-C for SFP                             | 1        | 0.72%   |
| Intel Ethernet Connection (7) I219-V                                 | 1        | 0.72%   |
| Intel Ethernet Connection (5) I219-V                                 | 1        | 0.72%   |
| Intel Ethernet Connection (5) I219-LM                                | 1        | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                                | 1        | 0.72%   |
| Intel Ethernet Connection (17) I219-V                                | 1        | 0.72%   |
| Intel Ethernet Connection (17) I219-LM                               | 1        | 0.72%   |
| Intel Ethernet Connection (14) I219-V                                | 1        | 0.72%   |
| Intel 82576 Gigabit Network Connection                               | 1        | 0.72%   |
| Intel 82566DM-2 Gigabit Network Connection                           | 1        | 0.72%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                     | 1        | 0.72%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express              | 1        | 0.72%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                     | 1        | 0.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 126      | 68.85%  |
| WiFi     | 57       | 31.15%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 106      | 82.81%  |
| WiFi     | 22       | 17.19%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 69       | 54.76%  |
| 2     | 50       | 39.68%  |
| 3     | 3        | 2.38%   |
| 4     | 2        | 1.59%   |
| 6     | 1        | 0.79%   |
| 5     | 1        | 0.79%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 95       | 74.22%  |
| Yes  | 33       | 25.78%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 17       | 40.48%  |
| Realtek Semiconductor   | 6        | 14.29%  |
| Cambridge Silicon Radio | 5        | 11.9%   |
| MediaTek                | 4        | 9.52%   |
| TP-Link                 | 2        | 4.76%   |
| IMC Networks            | 2        | 4.76%   |
| Broadcom                | 2        | 4.76%   |
| Belkin Components       | 2        | 4.76%   |
| Ralink                  | 1        | 2.38%   |
| ASUSTek Computer        | 1        | 2.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 5        | 11.9%   |
| MediaTek Wireless_Device                              | 4        | 9.52%   |
| Intel Bluetooth wireless interface                    | 4        | 9.52%   |
| Intel Bluetooth Device                                | 4        | 9.52%   |
| Realtek  Bluetooth 4.2 Adapter                        | 3        | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3        | 7.14%   |
| Intel AX210 Bluetooth                                 | 3        | 7.14%   |
| TP-Link UB500 Adapter                                 | 2        | 4.76%   |
| Realtek RTL8723B Bluetooth                            | 2        | 4.76%   |
| Intel Wireless-AC 3168 Bluetooth                      | 2        | 4.76%   |
| Realtek Bluetooth Radio                               | 1        | 2.38%   |
| Ralink RT3290 Bluetooth                               | 1        | 2.38%   |
| Intel AX200 Bluetooth                                 | 1        | 2.38%   |
| IMC Networks Wireless_Device                          | 1        | 2.38%   |
| IMC Networks Bluetooth Radio                          | 1        | 2.38%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 2.38%   |
| Broadcom BCM43142 Bluetooth 4.0                       | 1        | 2.38%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 1        | 2.38%   |
| Belkin Components F8T013 Bluetooth Adapter            | 1        | 2.38%   |
| ASUS Bluetooth Radio                                  | 1        | 2.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 77       | 37.56%  |
| AMD                     | 55       | 26.83%  |
| Nvidia                  | 40       | 19.51%  |
| C-Media Electronics     | 10       | 4.88%   |
| ASUSTek Computer        | 4        | 1.95%   |
| Generalplus Technology  | 3        | 1.46%   |
| GN Netcom               | 2        | 0.98%   |
| Texas Instruments       | 1        | 0.49%   |
| TerraTec Electronic     | 1        | 0.49%   |
| Tenx Technology         | 1        | 0.49%   |
| SteelSeries ApS         | 1        | 0.49%   |
| ONN                     | 1        | 0.49%   |
| Kingston Technology     | 1        | 0.49%   |
| JMTek                   | 1        | 0.49%   |
| Focusrite-Novation      | 1        | 0.49%   |
| DSEA A/S                | 1        | 0.49%   |
| Creative Technology     | 1        | 0.49%   |
| Corsair                 | 1        | 0.49%   |
| Cambridge Silicon Radio | 1        | 0.49%   |
| Anlya.cn                | 1        | 0.49%   |
| Alesis                  | 1        | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 17       | 6.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10       | 4.05%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 10       | 4.05%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 9        | 3.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 3.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8        | 3.24%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8        | 3.24%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8        | 3.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7        | 2.83%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6        | 2.43%   |
| Intel Alder Lake-S HD Audio Controller                                     | 6        | 2.43%   |
| Intel 200 Series PCH HD Audio                                              | 6        | 2.43%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 2.43%   |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 2.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 2.02%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 1.62%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 1.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 1.62%   |
| ASUSTek Computer USB Audio                                                 | 4        | 1.62%   |
| AMD FCH Azalia Controller                                                  | 4        | 1.62%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 1.62%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 1.21%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 1.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3        | 1.21%   |
| Generalplus Technology USB Audio Device                                    | 3        | 1.21%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 1.21%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 1.21%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 3        | 1.21%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3        | 1.21%   |
| AMD Kabini HDMI/DP Audio                                                   | 3        | 1.21%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3        | 1.21%   |
| Nvidia High Definition Audio Controller                                    | 2        | 0.81%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 0.81%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 0.81%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 2        | 0.81%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 0.81%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 0.81%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2        | 0.81%   |
| C-Media Electronics USB Audio Device                                       | 2        | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 16       | 16.84%  |
| Corsair             | 15       | 15.79%  |
| Unknown             | 11       | 11.58%  |
| SK hynix            | 10       | 10.53%  |
| Samsung Electronics | 10       | 10.53%  |
| Crucial             | 9        | 9.47%   |
| G.Skill             | 8        | 8.42%   |
| Micron Technology   | 4        | 4.21%   |
| Team                | 2        | 2.11%   |
| Unknown (ABCD)      | 1        | 1.05%   |
| Unknown (0x7FFF)    | 1        | 1.05%   |
| Unifosa             | 1        | 1.05%   |
| Ramaxel Technology  | 1        | 1.05%   |
| Hewlett-Packard     | 1        | 1.05%   |
| HBS                 | 1        | 1.05%   |
| GOODRAM             | 1        | 1.05%   |
| Elpida              | 1        | 1.05%   |
| Atermiter           | 1        | 1.05%   |
| A-DATA Technology   | 1        | 1.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                       | 2        | 2.02%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s             | 2        | 2.02%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s             | 2        | 2.02%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 3733MT/s           | 2        | 2.02%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM 6400MT/s                 | 2        | 2.02%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s           | 2        | 2.02%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s           | 2        | 2.02%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s           | 2        | 2.02%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                       | 1        | 1.01%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                        | 1        | 1.01%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                        | 1        | 1.01%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                            | 1        | 1.01%   |
| Unknown RAM Module 4GB DIMM                                     | 1        | 1.01%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                        | 1        | 1.01%   |
| Unknown RAM Module 2GB DIMM 667MT/s                             | 1        | 1.01%   |
| Unknown RAM DDR4 NB 8G 2400 8192MB SODIMM DDR4 2667MT/s         | 1        | 1.01%   |
| Unknown RAM DDR4 NB 16G 2666 16384MB SODIMM DDR4 2667MT/s       | 1        | 1.01%   |
| Unknown RAM 1866 CL10 Series 8192MB DIMM DDR3 933MT/s           | 1        | 1.01%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s  | 1        | 1.01%   |
| Unknown (0x7FFF) RAM GRAVITON 8GB-288P01 8GB DIMM DDR4 2667MT/s | 1        | 1.01%   |
| Unifosa RAM GU512303EP0202 2048MB DIMM DDR3 1333MT/s            | 1        | 1.01%   |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3800MT/s             | 1        | 1.01%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                      | 1        | 1.01%   |
| SK hynix RAM Module 8GB DIMM DDR4 2133MT/s                      | 1        | 1.01%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 1.01%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s             | 1        | 1.01%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s            | 1        | 1.01%   |
| SK hynix RAM HMT351U7BFR8C-H9 4GB DIMM DDR3 1333MT/s            | 1        | 1.01%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s            | 1        | 1.01%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s            | 1        | 1.01%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s            | 1        | 1.01%   |
| SK hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s            | 1        | 1.01%   |
| SK hynix RAM HMABAGL7ABR4N-XN 128GB DIMM DDR4 3200MT/s          | 1        | 1.01%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s           | 1        | 1.01%   |
| Samsung RAM Module 4GB DIMM DDR3 1333MT/s                       | 1        | 1.01%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s          | 1        | 1.01%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR2 2133MT/s          | 1        | 1.01%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s             | 1        | 1.01%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s             | 1        | 1.01%   |
| Samsung RAM M378A5244CB0-CTD 4GB DIMM DDR4 3334MT/s             | 1        | 1.01%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 42       | 51.22%  |
| DDR3    | 29       | 35.37%  |
| DDR5    | 4        | 4.88%   |
| Unknown | 3        | 3.66%   |
| DDR2    | 2        | 2.44%   |
| LPDDR4  | 1        | 1.22%   |
| DDR     | 1        | 1.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 74       | 90.24%  |
| SODIMM | 8        | 9.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Desktops | Percent |
|--------|----------|---------|
| 8192   | 30       | 32.26%  |
| 4096   | 26       | 27.96%  |
| 16384  | 24       | 25.81%  |
| 32768  | 5        | 5.38%   |
| 2048   | 5        | 5.38%   |
| 1024   | 2        | 2.15%   |
| 131072 | 1        | 1.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 14       | 15.56%  |
| 1333    | 13       | 14.44%  |
| 3200    | 7        | 7.78%   |
| 2400    | 7        | 7.78%   |
| 3600    | 5        | 5.56%   |
| 2667    | 5        | 5.56%   |
| 3400    | 3        | 3.33%   |
| 2133    | 3        | 3.33%   |
| 1800    | 3        | 3.33%   |
| 6400    | 2        | 2.22%   |
| 3733    | 2        | 2.22%   |
| 3533    | 2        | 2.22%   |
| 3266    | 2        | 2.22%   |
| 3000    | 2        | 2.22%   |
| 1866    | 2        | 2.22%   |
| 800     | 2        | 2.22%   |
| 5808    | 1        | 1.11%   |
| 4802    | 1        | 1.11%   |
| 4000    | 1        | 1.11%   |
| 3933    | 1        | 1.11%   |
| 3800    | 1        | 1.11%   |
| 3466    | 1        | 1.11%   |
| 3334    | 1        | 1.11%   |
| 3333    | 1        | 1.11%   |
| 3100    | 1        | 1.11%   |
| 2933    | 1        | 1.11%   |
| 2800    | 1        | 1.11%   |
| 2747    | 1        | 1.11%   |
| 1867    | 1        | 1.11%   |
| 1648    | 1        | 1.11%   |
| 667     | 1        | 1.11%   |
| Unknown | 1        | 1.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Seiko Epson        | 2        | 28.57%  |
| Hewlett-Packard    | 2        | 28.57%  |
| Brother Industries | 2        | 28.57%  |
| Graphtec America   | 1        | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seiko Epson XP-4100 Series        | 1        | 14.29%  |
| Seiko Epson Printer               | 1        | 14.29%  |
| HP LaserJet Professional P1102w   | 1        | 14.29%  |
| HP DeskJet 2700 series            | 1        | 14.29%  |
| Graphtec America Graphtec Printer | 1        | 14.29%  |
| Brother HL-3140CW series          | 1        | 14.29%  |
| Brother DCP-L5500DN series        | 1        | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 2        | 66.67%  |
| Hewlett-Packard | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| HP ScanJet G4010        | 1        | 33.33%  |
| Canon CanoScan LiDE 120 | 1        | 33.33%  |
| Canon CanoScan LiDE 110 | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 9        | 31.03%  |
| Microdia                      | 4        | 13.79%  |
| Z-Star Microelectronics       | 2        | 6.9%    |
| Samsung Electronics           | 2        | 6.9%    |
| Generalplus Technology        | 2        | 6.9%    |
| Sunplus Innovation Technology | 1        | 3.45%   |
| Realtek Semiconductor         | 1        | 3.45%   |
| Razer USA                     | 1        | 3.45%   |
| Microsoft                     | 1        | 3.45%   |
| LeCroy                        | 1        | 3.45%   |
| KYE Systems (Mouse Systems)   | 1        | 3.45%   |
| ARC International             | 1        | 3.45%   |
| Apple                         | 1        | 3.45%   |
| Alcorlink                     | 1        | 3.45%   |
| Alcor Micro                   | 1        | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech Webcam C270                      | 3        | 10.34%  |
| Samsung Galaxy series, misc. (MTP mode)   | 2        | 6.9%    |
| Microdia Webcam Vitade AF                 | 2        | 6.9%    |
| Microdia USB Camera                       | 2        | 6.9%    |
| Logitech HD Pro Webcam C920               | 2        | 6.9%    |
| Z-Star Venus USB2.0 Camera                | 1        | 3.45%   |
| Z-Star HP 3-MegaPixel Webcam GX607AA      | 1        | 3.45%   |
| Sunplus Integrated_Webcam_HD              | 1        | 3.45%   |
| Realtek HP 1.0MP High Definition Webcam   | 1        | 3.45%   |
| Razer USA Gaming Webcam [Kiyo]            | 1        | 3.45%   |
| Microsoft LifeCam VX-500 [1357]           | 1        | 3.45%   |
| Logitech Webcam C925e                     | 1        | 3.45%   |
| Logitech QuickCam E 3500                  | 1        | 3.45%   |
| Logitech Quickcam 3000 For Business       | 1        | 3.45%   |
| Logitech C920 PRO HD Webcam               | 1        | 3.45%   |
| LeCroy USB 2.0 PC Camera                  | 1        | 3.45%   |
| KYE Systems (Mouse Systems) Genius Webcam | 1        | 3.45%   |
| Generalplus GENERAL WEBCAM                | 1        | 3.45%   |
| Generalplus 808 Camera #9 (web-cam mode)  | 1        | 3.45%   |
| ARC International Camera                  | 1        | 3.45%   |
| Apple iPhone 5/5C/5S/6/SE                 | 1        | 3.45%   |
| Alcorlink USB 2.0 Camera                  | 1        | 3.45%   |
| Alcor Micro USB 2.0 PC Camera             | 1        | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| SCM Microsystems | 1        | 50%     |
| OmniKey          | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| SCM Microsystems Identiv SmartOS Reader | 1        | 50%     |
| OmniKey CardMan 1021                    | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 114      | 89.76%  |
| 1     | 11       | 8.66%   |
| 3     | 1        | 0.79%   |
| 2     | 1        | 0.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 5        | 35.71%  |
| Unassigned class         | 3        | 21.43%  |
| Graphics card            | 2        | 14.29%  |
| Communication controller | 1        | 7.14%   |
| Chipcard                 | 1        | 7.14%   |
| Card reader              | 1        | 7.14%   |
| Bluetooth                | 1        | 7.14%   |

