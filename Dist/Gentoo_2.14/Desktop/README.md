Gentoo 2.14 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for Gentoo 2.14.

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

Total: 270

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | Z170A GAMING M7             | [e1892a119b](https://linux-hardware.org/?probe=e1892a119b) | May 08, 2024 |
| ASUSTek       | M3A78-CM                    | [0bcef3f207](https://linux-hardware.org/?probe=0bcef3f207) | May 06, 2024 |
| ASUSTek       | M5A99FX PRO R2.0            | [9dcdf5a463](https://linux-hardware.org/?probe=9dcdf5a463) | Apr 29, 2024 |
| ASUSTek       | M3A78-CM                    | [cdc42c64dd](https://linux-hardware.org/?probe=cdc42c64dd) | Apr 22, 2024 |
| Gigabyte      | B75-D3V                     | [4ddc5c0d0d](https://linux-hardware.org/?probe=4ddc5c0d0d) | Apr 21, 2024 |
| MSI           | PRO B650M-P                 | [90165c7480](https://linux-hardware.org/?probe=90165c7480) | Apr 18, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [25c95d871e](https://linux-hardware.org/?probe=25c95d871e) | Apr 16, 2024 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [8a95e3759a](https://linux-hardware.org/?probe=8a95e3759a) | Apr 15, 2024 |
| Gigabyte      | B560M AORUS PRO             | [6e49d2f74b](https://linux-hardware.org/?probe=6e49d2f74b) | Apr 13, 2024 |
| HP            | 1589                        | [fd455c0623](https://linux-hardware.org/?probe=fd455c0623) | Apr 12, 2024 |
| ASUSTek       | P6X58D-E                    | [143efb64e8](https://linux-hardware.org/?probe=143efb64e8) | Apr 12, 2024 |
| Gigabyte      | AB350-Gaming-CF             | [f15f757ee9](https://linux-hardware.org/?probe=f15f757ee9) | Apr 11, 2024 |
| HP            | 1589                        | [bf38ba715e](https://linux-hardware.org/?probe=bf38ba715e) | Apr 10, 2024 |
| Gigabyte      | A520 AORUS ELITE            | [bef494961d](https://linux-hardware.org/?probe=bef494961d) | Apr 09, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [6d013c64d2](https://linux-hardware.org/?probe=6d013c64d2) | Apr 08, 2024 |
| Gigabyte      | AB350-Gaming-CF             | [30921e196b](https://linux-hardware.org/?probe=30921e196b) | Apr 03, 2024 |
| ASUSTek       | X99-E                       | [f9f01b1a69](https://linux-hardware.org/?probe=f9f01b1a69) | Apr 03, 2024 |
| ASUSTek       | X99-E                       | [e87752dc61](https://linux-hardware.org/?probe=e87752dc61) | Apr 03, 2024 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [ebc630507b](https://linux-hardware.org/?probe=ebc630507b) | Apr 02, 2024 |
| Gigabyte      | A520 AORUS ELITE            | [3186452a8d](https://linux-hardware.org/?probe=3186452a8d) | Apr 02, 2024 |
| Unknown       | Unknown                     | [e4035a3519](https://linux-hardware.org/?probe=e4035a3519) | Mar 25, 2024 |
| ASUSTek       | M3A78-CM                    | [73b0c5faa2](https://linux-hardware.org/?probe=73b0c5faa2) | Mar 25, 2024 |
| ASUSTek       | P6X58D PREMIUM              | [3e42f1f6bb](https://linux-hardware.org/?probe=3e42f1f6bb) | Mar 24, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [e4e9866823](https://linux-hardware.org/?probe=e4e9866823) | Mar 22, 2024 |
| ASRockRack    | X470D4U2/1N1                | [f406391d1a](https://linux-hardware.org/?probe=f406391d1a) | Mar 20, 2024 |
| MSI           | B550 GAMING GEN3            | [b3056c47f2](https://linux-hardware.org/?probe=b3056c47f2) | Mar 19, 2024 |
| Colorful T... | CVN Z790M FROZEN D5 V20     | [05f6953852](https://linux-hardware.org/?probe=05f6953852) | Mar 17, 2024 |
| ASRock        | N68C-GS UCC                 | [d723eedac0](https://linux-hardware.org/?probe=d723eedac0) | Mar 15, 2024 |
| Colorful T... | CVN Z790M FROZEN D5 V20     | [d43454b637](https://linux-hardware.org/?probe=d43454b637) | Mar 15, 2024 |
| MSI           | PRO B650-P WIFI             | [b8a3fe05f4](https://linux-hardware.org/?probe=b8a3fe05f4) | Mar 13, 2024 |
| Google        | Panther                     | [f2c3361edf](https://linux-hardware.org/?probe=f2c3361edf) | Mar 10, 2024 |
| transtec      | GE2 Series                  | [c6ff6cabae](https://linux-hardware.org/?probe=c6ff6cabae) | Mar 08, 2024 |
| transtec      | GE2 Series                  | [10d18de264](https://linux-hardware.org/?probe=10d18de264) | Mar 08, 2024 |
| HP            | 8767 A                      | [3775377131](https://linux-hardware.org/?probe=3775377131) | Mar 05, 2024 |
| HP            | 8767 A                      | [5903e66479](https://linux-hardware.org/?probe=5903e66479) | Mar 04, 2024 |
| ASRock        | N68C-GS UCC                 | [044465e0aa](https://linux-hardware.org/?probe=044465e0aa) | Mar 04, 2024 |
| Dell          | 042P49 A02                  | [f02e3ceba7](https://linux-hardware.org/?probe=f02e3ceba7) | Mar 02, 2024 |
| ASRock        | B450M Steel Legend          | [aad04111a4](https://linux-hardware.org/?probe=aad04111a4) | Mar 01, 2024 |
| ASUSTek       | PRIME B550M-A WIFI II       | [cce884f287](https://linux-hardware.org/?probe=cce884f287) | Mar 01, 2024 |
| ASUSTek       | PRIME H510M-E               | [32c850d7a0](https://linux-hardware.org/?probe=32c850d7a0) | Feb 28, 2024 |
| ASUSTek       | PRIME H510M-E               | [3ccf63844b](https://linux-hardware.org/?probe=3ccf63844b) | Feb 27, 2024 |
| Dell          | 0K240Y A01                  | [8ac39746cc](https://linux-hardware.org/?probe=8ac39746cc) | Feb 26, 2024 |
| Gigabyte      | AB350-Gaming-CF             | [f88143daa2](https://linux-hardware.org/?probe=f88143daa2) | Feb 26, 2024 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [98c285762c](https://linux-hardware.org/?probe=98c285762c) | Feb 25, 2024 |
| Gigabyte      | A520 AORUS ELITE            | [2d34bf7198](https://linux-hardware.org/?probe=2d34bf7198) | Feb 23, 2024 |
| ASUSTek       | M3A78-CM                    | [9ff0ddca4e](https://linux-hardware.org/?probe=9ff0ddca4e) | Feb 23, 2024 |
| ASUSTek       | PRIME H510M-E               | [5e789b17a4](https://linux-hardware.org/?probe=5e789b17a4) | Feb 22, 2024 |
| ASUSTek       | PRIME H310M-E/BR            | [f3d1efb331](https://linux-hardware.org/?probe=f3d1efb331) | Feb 22, 2024 |
| Gigabyte      | AB350-Gaming-CF             | [acc39c2774](https://linux-hardware.org/?probe=acc39c2774) | Feb 19, 2024 |
| ASUSTek       | PRIME H510M-E               | [82ae92e9ec](https://linux-hardware.org/?probe=82ae92e9ec) | Feb 18, 2024 |
| Dell          | 0K240Y A01                  | [7987e39eb7](https://linux-hardware.org/?probe=7987e39eb7) | Feb 18, 2024 |
| ASUSTek       | PRIME H310M-E/BR            | [233bfc2f43](https://linux-hardware.org/?probe=233bfc2f43) | Feb 18, 2024 |
| Gigabyte      | A520 AORUS ELITE            | [95950fa2f0](https://linux-hardware.org/?probe=95950fa2f0) | Feb 16, 2024 |
| Unknown       | Unknown                     | [b579279ced](https://linux-hardware.org/?probe=b579279ced) | Feb 16, 2024 |
| Gigabyte      | X570 AORUS MASTER           | [04f68f7039](https://linux-hardware.org/?probe=04f68f7039) | Feb 16, 2024 |
| ASUSTek       | M3A78-CM                    | [c7fd8dfb5c](https://linux-hardware.org/?probe=c7fd8dfb5c) | Feb 14, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [8ec5fdc816](https://linux-hardware.org/?probe=8ec5fdc816) | Feb 12, 2024 |
| Gigabyte      | X670E AORUS MASTER          | [833f48af30](https://linux-hardware.org/?probe=833f48af30) | Feb 12, 2024 |
| Gigabyte      | X670E AORUS MASTER          | [35afc5314f](https://linux-hardware.org/?probe=35afc5314f) | Feb 12, 2024 |
| MSI           | B450 TOMAHAWK MAX           | [38cf6f3eff](https://linux-hardware.org/?probe=38cf6f3eff) | Feb 11, 2024 |
| ASRock        | B450 Pro4                   | [9c2f5e83e3](https://linux-hardware.org/?probe=9c2f5e83e3) | Feb 11, 2024 |
| MSI           | B450 TOMAHAWK MAX           | [b49ffe659b](https://linux-hardware.org/?probe=b49ffe659b) | Feb 11, 2024 |
| ASUSTek       | PRIME B650-PLUS             | [c7ab9b0fc5](https://linux-hardware.org/?probe=c7ab9b0fc5) | Feb 11, 2024 |
| ASUSTek       | PRIME B650-PLUS             | [847f271141](https://linux-hardware.org/?probe=847f271141) | Feb 11, 2024 |
| Gigabyte      | A520 AORUS ELITE            | [db94db2244](https://linux-hardware.org/?probe=db94db2244) | Feb 09, 2024 |
| ASUSTek       | Pro WS X570-ACE             | [40f5ce16c1](https://linux-hardware.org/?probe=40f5ce16c1) | Feb 08, 2024 |
| ASUSTek       | PRIME B550M-K               | [016a8ba655](https://linux-hardware.org/?probe=016a8ba655) | Feb 07, 2024 |
| ASUSTek       | M3A78-CM                    | [c2d2eb2434](https://linux-hardware.org/?probe=c2d2eb2434) | Feb 06, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [671e98c249](https://linux-hardware.org/?probe=671e98c249) | Feb 06, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [12792a9fa5](https://linux-hardware.org/?probe=12792a9fa5) | Feb 06, 2024 |
| Gigabyte      | AB350-Gaming-CF             | [a6b7480c05](https://linux-hardware.org/?probe=a6b7480c05) | Feb 04, 2024 |
| Unknown       | Unknown                     | [48a88ebbfb](https://linux-hardware.org/?probe=48a88ebbfb) | Feb 04, 2024 |
| ASRock        | B550M Pro4                  | [66ad35082d](https://linux-hardware.org/?probe=66ad35082d) | Feb 04, 2024 |
| Gigabyte      | A520 AORUS ELITE            | [075ee0ca67](https://linux-hardware.org/?probe=075ee0ca67) | Feb 02, 2024 |
| MSI           | MAG B550M MORTAR            | [7ad6a0ecce](https://linux-hardware.org/?probe=7ad6a0ecce) | Jan 31, 2024 |
| Unknown       | Unknown                     | [4690cc047a](https://linux-hardware.org/?probe=4690cc047a) | Jan 30, 2024 |
| ASUSTek       | M5A78L-M/USB3               | [cc38ac2dfc](https://linux-hardware.org/?probe=cc38ac2dfc) | Jan 29, 2024 |
| Gigabyte      | AB350-Gaming-CF             | [8949a81c2e](https://linux-hardware.org/?probe=8949a81c2e) | Jan 29, 2024 |
| ASUSTek       | M5A78L-M/USB3               | [76a1ecf2ba](https://linux-hardware.org/?probe=76a1ecf2ba) | Jan 29, 2024 |
| ASUSTek       | M3A78-CM                    | [e17793cd71](https://linux-hardware.org/?probe=e17793cd71) | Jan 28, 2024 |
| ASUSTek       | PRIME B660-PLUS D4          | [19c619ae3f](https://linux-hardware.org/?probe=19c619ae3f) | Jan 27, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [999ea9c685](https://linux-hardware.org/?probe=999ea9c685) | Jan 26, 2024 |
| Gigabyte      | A520 AORUS ELITE            | [9b7cbb57c7](https://linux-hardware.org/?probe=9b7cbb57c7) | Jan 26, 2024 |
| HP            | 1589                        | [d731924276](https://linux-hardware.org/?probe=d731924276) | Jan 25, 2024 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [ff2fc44691](https://linux-hardware.org/?probe=ff2fc44691) | Jan 23, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [13086bc4ce](https://linux-hardware.org/?probe=13086bc4ce) | Jan 19, 2024 |
| Gigabyte      | B650M D3HP                  | [fdc83ca691](https://linux-hardware.org/?probe=fdc83ca691) | Jan 18, 2024 |
| ASUSTek       | PRIME H610M-E D4            | [409e7e4e42](https://linux-hardware.org/?probe=409e7e4e42) | Jan 17, 2024 |
| Gigabyte      | X570 AORUS ELITE            | [ed6bfe4f8f](https://linux-hardware.org/?probe=ed6bfe4f8f) | Jan 16, 2024 |
| Dell          | 0VHRW1 A03                  | [668e361f20](https://linux-hardware.org/?probe=668e361f20) | Jan 15, 2024 |
| ASRock        | X399 Taichi                 | [e509920598](https://linux-hardware.org/?probe=e509920598) | Jan 14, 2024 |
| HP            | 1589                        | [194b5a119c](https://linux-hardware.org/?probe=194b5a119c) | Jan 13, 2024 |
| Dell          | 030VXY A01                  | [50a18e5eba](https://linux-hardware.org/?probe=50a18e5eba) | Jan 10, 2024 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [7bef06dee9](https://linux-hardware.org/?probe=7bef06dee9) | Jan 10, 2024 |
| Gigabyte      | Z590 UD                     | [6953296967](https://linux-hardware.org/?probe=6953296967) | Jan 10, 2024 |
| Gigabyte      | Z77X-UD5H                   | [ca5d4c7c00](https://linux-hardware.org/?probe=ca5d4c7c00) | Jan 07, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | [3b6e799f22](https://linux-hardware.org/?probe=3b6e799f22) | Jan 06, 2024 |
| ASUSTek       | M3A78-CM                    | [7bf93755f2](https://linux-hardware.org/?probe=7bf93755f2) | Jan 04, 2024 |
| Gigabyte      | A520 AORUS ELITE            | [da0c7ff210](https://linux-hardware.org/?probe=da0c7ff210) | Jan 04, 2024 |
| ASUSTek       | P8H67-M                     | [06843ca788](https://linux-hardware.org/?probe=06843ca788) | Jan 04, 2024 |
| Gigabyte      | AB350-Gaming-CF             | [a0e025d32d](https://linux-hardware.org/?probe=a0e025d32d) | Jan 02, 2024 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [ee3998d501](https://linux-hardware.org/?probe=ee3998d501) | Jan 02, 2024 |
| ASUSTek       | PRIME B660-PLUS D4          | [0e7bbb6dea](https://linux-hardware.org/?probe=0e7bbb6dea) | Dec 30, 2023 |
| Gigabyte      | X79-UP4                     | [618dfee965](https://linux-hardware.org/?probe=618dfee965) | Dec 29, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [619ddf5210](https://linux-hardware.org/?probe=619ddf5210) | Dec 27, 2023 |
| ASUSTek       | M3A78-CM                    | [983d2046a3](https://linux-hardware.org/?probe=983d2046a3) | Dec 27, 2023 |
| ASUSTek       | D500MD                      | [21870febdd](https://linux-hardware.org/?probe=21870febdd) | Dec 25, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [47255f4ba3](https://linux-hardware.org/?probe=47255f4ba3) | Dec 25, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [646b9af5a9](https://linux-hardware.org/?probe=646b9af5a9) | Dec 24, 2023 |
| MSI           | MPG B650 EDGE WIFI          | [8503d79f6c](https://linux-hardware.org/?probe=8503d79f6c) | Dec 24, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [391ef34135](https://linux-hardware.org/?probe=391ef34135) | Dec 23, 2023 |
| ASUSTek       | M3A78-CM                    | [89fd7ee431](https://linux-hardware.org/?probe=89fd7ee431) | Dec 18, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [3504b628f1](https://linux-hardware.org/?probe=3504b628f1) | Dec 18, 2023 |
| ASRock        | X399 Taichi                 | [877c79184e](https://linux-hardware.org/?probe=877c79184e) | Dec 18, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [e0b7c61c9f](https://linux-hardware.org/?probe=e0b7c61c9f) | Dec 18, 2023 |
| ASRock        | X399 Taichi                 | [776cc9f3bb](https://linux-hardware.org/?probe=776cc9f3bb) | Dec 17, 2023 |
| MSI           | B450 TOMAHAWK               | [f02dc20ac0](https://linux-hardware.org/?probe=f02dc20ac0) | Dec 16, 2023 |
| HP            | 8592                        | [511feb6066](https://linux-hardware.org/?probe=511feb6066) | Dec 15, 2023 |
| HP            | 8592                        | [c5817452fd](https://linux-hardware.org/?probe=c5817452fd) | Dec 15, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ba4e95a15e](https://linux-hardware.org/?probe=ba4e95a15e) | Dec 13, 2023 |
| ASRock        | X399 Taichi                 | [8524c9dcd5](https://linux-hardware.org/?probe=8524c9dcd5) | Dec 13, 2023 |
| ASRock        | B650M PG Riptide            | [9b92833e92](https://linux-hardware.org/?probe=9b92833e92) | Dec 12, 2023 |
| Foxconn       | TPS01                       | [a417ff19ae](https://linux-hardware.org/?probe=a417ff19ae) | Dec 12, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [e07d68d658](https://linux-hardware.org/?probe=e07d68d658) | Dec 11, 2023 |
| ASUSTek       | M3A78-CM                    | [8bf4107eed](https://linux-hardware.org/?probe=8bf4107eed) | Dec 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [b87d7c1c10](https://linux-hardware.org/?probe=b87d7c1c10) | Dec 10, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [ba355033b7](https://linux-hardware.org/?probe=ba355033b7) | Dec 08, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [d57960be0a](https://linux-hardware.org/?probe=d57960be0a) | Dec 05, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [1fe1dc7462](https://linux-hardware.org/?probe=1fe1dc7462) | Dec 04, 2023 |
| Gigabyte      | 970A-DS3P FX                | [675f997c0b](https://linux-hardware.org/?probe=675f997c0b) | Dec 03, 2023 |
| Gigabyte      | 970A-DS3P FX                | [358a92be0d](https://linux-hardware.org/?probe=358a92be0d) | Dec 03, 2023 |
| Lenovo        | 0B98401 PRO                 | [3f49a16307](https://linux-hardware.org/?probe=3f49a16307) | Dec 02, 2023 |
| ASRock        | A300M-STX                   | [7f49fad2c7](https://linux-hardware.org/?probe=7f49fad2c7) | Dec 02, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | [fc87fb1112](https://linux-hardware.org/?probe=fc87fb1112) | Dec 01, 2023 |
| MSI           | MEG X570 UNIFY              | [f9175866ae](https://linux-hardware.org/?probe=f9175866ae) | Nov 30, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | [f16bc78368](https://linux-hardware.org/?probe=f16bc78368) | Nov 29, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | [879c59cf41](https://linux-hardware.org/?probe=879c59cf41) | Nov 29, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [1d71979dbb](https://linux-hardware.org/?probe=1d71979dbb) | Nov 27, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [68644f2689](https://linux-hardware.org/?probe=68644f2689) | Nov 27, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [6fcbd9b64c](https://linux-hardware.org/?probe=6fcbd9b64c) | Nov 27, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [2a04ec7adc](https://linux-hardware.org/?probe=2a04ec7adc) | Nov 27, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [26b99168f7](https://linux-hardware.org/?probe=26b99168f7) | Nov 26, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [9e8f9907bb](https://linux-hardware.org/?probe=9e8f9907bb) | Nov 24, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [fde8cf07ef](https://linux-hardware.org/?probe=fde8cf07ef) | Nov 24, 2023 |
| Intel         | DH77EB AAG39073-304         | [c397c51bfb](https://linux-hardware.org/?probe=c397c51bfb) | Nov 24, 2023 |
| ASUSTek       | M3A78-CM                    | [4eae08c59f](https://linux-hardware.org/?probe=4eae08c59f) | Nov 22, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [2305a057a8](https://linux-hardware.org/?probe=2305a057a8) | Nov 22, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [8d33a8020d](https://linux-hardware.org/?probe=8d33a8020d) | Nov 20, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [ac6d14ae8d](https://linux-hardware.org/?probe=ac6d14ae8d) | Nov 20, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [fc7f2d74b8](https://linux-hardware.org/?probe=fc7f2d74b8) | Nov 19, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [a868498279](https://linux-hardware.org/?probe=a868498279) | Nov 18, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [477c710fe1](https://linux-hardware.org/?probe=477c710fe1) | Nov 15, 2023 |
| Gigabyte      | Z590 UD                     | [76092ba872](https://linux-hardware.org/?probe=76092ba872) | Nov 15, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [6a5b4cf051](https://linux-hardware.org/?probe=6a5b4cf051) | Nov 15, 2023 |
| ASUSTek       | P10S-I Series               | [f27cfbe5ca](https://linux-hardware.org/?probe=f27cfbe5ca) | Nov 15, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [1105d135a2](https://linux-hardware.org/?probe=1105d135a2) | Nov 14, 2023 |
| ASUSTek       | M3A78-CM                    | [8080101e6f](https://linux-hardware.org/?probe=8080101e6f) | Nov 13, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [de369665dc](https://linux-hardware.org/?probe=de369665dc) | Nov 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [9d2aeb3f90](https://linux-hardware.org/?probe=9d2aeb3f90) | Nov 13, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [ab65845e2f](https://linux-hardware.org/?probe=ab65845e2f) | Nov 12, 2023 |
| Medion        | B360H4-EM V1.0              | [3efb188b16](https://linux-hardware.org/?probe=3efb188b16) | Nov 12, 2023 |
| Gigabyte      | Z590 UD                     | [4c763ba78a](https://linux-hardware.org/?probe=4c763ba78a) | Nov 09, 2023 |
| ASUSTek       | PRIME Z270-P                | [1de1299edf](https://linux-hardware.org/?probe=1de1299edf) | Nov 08, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7ecc25dda7](https://linux-hardware.org/?probe=7ecc25dda7) | Nov 08, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [715aee0ee7](https://linux-hardware.org/?probe=715aee0ee7) | Nov 08, 2023 |
| ASUSTek       | Z10PA-D8 Series             | [b865e2f52d](https://linux-hardware.org/?probe=b865e2f52d) | Nov 07, 2023 |
| Gigabyte      | H110M-H-CF                  | [d0570de821](https://linux-hardware.org/?probe=d0570de821) | Nov 06, 2023 |
| Gigabyte      | H110M-H-CF                  | [29f3c0c25f](https://linux-hardware.org/?probe=29f3c0c25f) | Nov 06, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [4d3a7373ae](https://linux-hardware.org/?probe=4d3a7373ae) | Nov 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [ff44a3299b](https://linux-hardware.org/?probe=ff44a3299b) | Nov 06, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [8e8cfaa103](https://linux-hardware.org/?probe=8e8cfaa103) | Nov 05, 2023 |
| ASUSTek       | M3A78-CM                    | [0e493c7b85](https://linux-hardware.org/?probe=0e493c7b85) | Nov 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | [fc6336fedd](https://linux-hardware.org/?probe=fc6336fedd) | Nov 02, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [40deedc435](https://linux-hardware.org/?probe=40deedc435) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [57d643d36b](https://linux-hardware.org/?probe=57d643d36b) | Oct 31, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7b6fe38982](https://linux-hardware.org/?probe=7b6fe38982) | Oct 31, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [f6e8c279ef](https://linux-hardware.org/?probe=f6e8c279ef) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [af050c4fa2](https://linux-hardware.org/?probe=af050c4fa2) | Oct 29, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [bee59e348e](https://linux-hardware.org/?probe=bee59e348e) | Oct 28, 2023 |
| ASUSTek       | M3A78-CM                    | [54aa16ef1e](https://linux-hardware.org/?probe=54aa16ef1e) | Oct 27, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [50b77f9f9e](https://linux-hardware.org/?probe=50b77f9f9e) | Oct 26, 2023 |
| SZMZ          | X99M-G2                     | [78bdbc6419](https://linux-hardware.org/?probe=78bdbc6419) | Oct 25, 2023 |
| HP            | 3397                        | [1344d9d38b](https://linux-hardware.org/?probe=1344d9d38b) | Oct 23, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [9a65857d3c](https://linux-hardware.org/?probe=9a65857d3c) | Oct 23, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [001c668695](https://linux-hardware.org/?probe=001c668695) | Oct 23, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [def0406ec0](https://linux-hardware.org/?probe=def0406ec0) | Oct 23, 2023 |
| Unknown       | Unknown                     | [95d6dab241](https://linux-hardware.org/?probe=95d6dab241) | Oct 23, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [6ef12aa776](https://linux-hardware.org/?probe=6ef12aa776) | Oct 23, 2023 |
| Dell          | 0J3C2F A02                  | [4b93c11bcb](https://linux-hardware.org/?probe=4b93c11bcb) | Oct 21, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [62ae73f967](https://linux-hardware.org/?probe=62ae73f967) | Oct 21, 2023 |
| ASUSTek       | M3A78-CM                    | [e8d5f9186c](https://linux-hardware.org/?probe=e8d5f9186c) | Oct 20, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [b677f99638](https://linux-hardware.org/?probe=b677f99638) | Oct 19, 2023 |
| ASRock        | H170 Pro4S                  | [e3960f114d](https://linux-hardware.org/?probe=e3960f114d) | Oct 18, 2023 |
| Dell          | 0MNPJ9 A03                  | [36e7a1e261](https://linux-hardware.org/?probe=36e7a1e261) | Oct 18, 2023 |
| Gigabyte      | Z590 UD                     | [1e2597a152](https://linux-hardware.org/?probe=1e2597a152) | Oct 17, 2023 |
| Gigabyte      | B450M DS3H-CF               | [acd4052588](https://linux-hardware.org/?probe=acd4052588) | Oct 16, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [cc5a77d2c3](https://linux-hardware.org/?probe=cc5a77d2c3) | Oct 16, 2023 |
| Gigabyte      | Z590 UD                     | [65277f3f01](https://linux-hardware.org/?probe=65277f3f01) | Oct 16, 2023 |
| MSI           | MEG X570S ACE MAX           | [d3cf683bad](https://linux-hardware.org/?probe=d3cf683bad) | Oct 15, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [f0f128becf](https://linux-hardware.org/?probe=f0f128becf) | Oct 09, 2023 |
| SZMZ          | X99M-G2                     | [212f394b32](https://linux-hardware.org/?probe=212f394b32) | Oct 09, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [078d4619a6](https://linux-hardware.org/?probe=078d4619a6) | Oct 09, 2023 |
| SZMZ          | X99M-G2                     | [586d5eef76](https://linux-hardware.org/?probe=586d5eef76) | Oct 08, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [6f6e394cdf](https://linux-hardware.org/?probe=6f6e394cdf) | Oct 05, 2023 |
| MSI           | PRO X670-P WIFI             | [c5d7f755ac](https://linux-hardware.org/?probe=c5d7f755ac) | Oct 05, 2023 |
| HP            | 1589                        | [75f8ba109d](https://linux-hardware.org/?probe=75f8ba109d) | Oct 04, 2023 |
| ASUSTek       | M3A78-CM                    | [27d781a357](https://linux-hardware.org/?probe=27d781a357) | Oct 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [e705d58ab0](https://linux-hardware.org/?probe=e705d58ab0) | Oct 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [d5de51003e](https://linux-hardware.org/?probe=d5de51003e) | Oct 03, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [8fd9631bea](https://linux-hardware.org/?probe=8fd9631bea) | Oct 03, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [ea10bf8eab](https://linux-hardware.org/?probe=ea10bf8eab) | Oct 02, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [cbd8df2f8a](https://linux-hardware.org/?probe=cbd8df2f8a) | Oct 02, 2023 |
| ASUSTek       | PRIME X670-P                | [25c3794b84](https://linux-hardware.org/?probe=25c3794b84) | Oct 01, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [ff0e651b1b](https://linux-hardware.org/?probe=ff0e651b1b) | Oct 01, 2023 |
| ASUSTek       | M3A78-CM                    | [4ef9eaaaba](https://linux-hardware.org/?probe=4ef9eaaaba) | Sep 27, 2023 |
| HP            | 1589                        | [1063a6e665](https://linux-hardware.org/?probe=1063a6e665) | Sep 27, 2023 |
| Supermicro    | X10SDE-DF                   | [c2ba80af3b](https://linux-hardware.org/?probe=c2ba80af3b) | Sep 26, 2023 |
| BESSTAR Te... | HM90                        | [a85d516a80](https://linux-hardware.org/?probe=a85d516a80) | Sep 25, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [32a39c6a01](https://linux-hardware.org/?probe=32a39c6a01) | Sep 25, 2023 |
| Supermicro    | X10SDE-DF                   | [fb93d199f3](https://linux-hardware.org/?probe=fb93d199f3) | Sep 25, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [4c68092d28](https://linux-hardware.org/?probe=4c68092d28) | Sep 25, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | [d17427680f](https://linux-hardware.org/?probe=d17427680f) | Sep 24, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | [1c0c7815dd](https://linux-hardware.org/?probe=1c0c7815dd) | Sep 24, 2023 |
| Supermicro    | X10SDE-DF                   | [b0297cff82](https://linux-hardware.org/?probe=b0297cff82) | Sep 24, 2023 |
| Dell          | 0RY206                      | [11a31518a3](https://linux-hardware.org/?probe=11a31518a3) | Sep 20, 2023 |
| ASUSTek       | M3A78-CM                    | [0748266b0a](https://linux-hardware.org/?probe=0748266b0a) | Sep 19, 2023 |
| ASRock        | B85M                        | [8a3dc73931](https://linux-hardware.org/?probe=8a3dc73931) | Sep 18, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [5680b32e39](https://linux-hardware.org/?probe=5680b32e39) | Sep 18, 2023 |
| ASUSTek       | PRIME B550M-K               | [524eb9d966](https://linux-hardware.org/?probe=524eb9d966) | Sep 17, 2023 |
| ASUSTek       | PRIME B550M-K               | [2f86649b91](https://linux-hardware.org/?probe=2f86649b91) | Sep 17, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [cd5cabf48f](https://linux-hardware.org/?probe=cd5cabf48f) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [d23a7d46f3](https://linux-hardware.org/?probe=d23a7d46f3) | Sep 15, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [12f4431262](https://linux-hardware.org/?probe=12f4431262) | Sep 12, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | [0dabf67d5f](https://linux-hardware.org/?probe=0dabf67d5f) | Sep 11, 2023 |
| ASUSTek       | M3A78-CM                    | [77105eb7da](https://linux-hardware.org/?probe=77105eb7da) | Sep 11, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [a25f4b1c5c](https://linux-hardware.org/?probe=a25f4b1c5c) | Sep 11, 2023 |
| ASUSTek       | PRIME N100I-D D4            | [ce24c28731](https://linux-hardware.org/?probe=ce24c28731) | Sep 10, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | [87971ac772](https://linux-hardware.org/?probe=87971ac772) | Sep 09, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [dffd28975a](https://linux-hardware.org/?probe=dffd28975a) | Sep 09, 2023 |
| Gigabyte      | B75M-D2V                    | [8f6631088b](https://linux-hardware.org/?probe=8f6631088b) | Sep 08, 2023 |
| HP            | 1589                        | [550b95765c](https://linux-hardware.org/?probe=550b95765c) | Sep 06, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | [48e1f16931](https://linux-hardware.org/?probe=48e1f16931) | Sep 05, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [f51b98f4cd](https://linux-hardware.org/?probe=f51b98f4cd) | Sep 04, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [e6df46a4a8](https://linux-hardware.org/?probe=e6df46a4a8) | Sep 03, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [32a90ea48e](https://linux-hardware.org/?probe=32a90ea48e) | Sep 02, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [9f3df2894e](https://linux-hardware.org/?probe=9f3df2894e) | Sep 02, 2023 |
| HP            | 1589                        | [447cae1b4c](https://linux-hardware.org/?probe=447cae1b4c) | Sep 01, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [f0e20e0089](https://linux-hardware.org/?probe=f0e20e0089) | Aug 31, 2023 |
| Loongson      | 3A6000-HV-7A2000-1w-EVB-... | [a99a5ccc55](https://linux-hardware.org/?probe=a99a5ccc55) | Aug 30, 2023 |
| Loongson      | LS3A6000-7A2000-1w-EVB-V... | [ad154077da](https://linux-hardware.org/?probe=ad154077da) | Aug 28, 2023 |
| ASRock        | AB350M Pro4                 | [e3ca221ba9](https://linux-hardware.org/?probe=e3ca221ba9) | Aug 28, 2023 |
| Dell          | 0RY206                      | [fff4c01588](https://linux-hardware.org/?probe=fff4c01588) | Aug 27, 2023 |
| ASUSTek       | M3A78-CM                    | [e6e9efdb61](https://linux-hardware.org/?probe=e6e9efdb61) | Aug 26, 2023 |
| ASUSTek       | M3A78-CM                    | [1f69210d69](https://linux-hardware.org/?probe=1f69210d69) | Aug 25, 2023 |
| ASUSTek       | M3A78-CM                    | [d1af143bed](https://linux-hardware.org/?probe=d1af143bed) | Aug 19, 2023 |
| Gigabyte      | Z77X-UD5H                   | [63a0a35452](https://linux-hardware.org/?probe=63a0a35452) | Aug 18, 2023 |
| Dell          | 0RY206                      | [f060a8a559](https://linux-hardware.org/?probe=f060a8a559) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [dfae10b78d](https://linux-hardware.org/?probe=dfae10b78d) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [23d9892448](https://linux-hardware.org/?probe=23d9892448) | Aug 13, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [aa4c1f2237](https://linux-hardware.org/?probe=aa4c1f2237) | Aug 13, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [ae8c13e17e](https://linux-hardware.org/?probe=ae8c13e17e) | Aug 12, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [e280c00c8b](https://linux-hardware.org/?probe=e280c00c8b) | Aug 12, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [4fe5238f21](https://linux-hardware.org/?probe=4fe5238f21) | Aug 12, 2023 |
| Gigabyte      | Z370P D3-CF                 | [ed5ccc8efb](https://linux-hardware.org/?probe=ed5ccc8efb) | Aug 08, 2023 |
| ASUSTek       | PRIME X570-P                | [7e6ad75fc4](https://linux-hardware.org/?probe=7e6ad75fc4) | Jul 28, 2023 |
| MSI           | TRX40 PRO 10G               | [6391114079](https://linux-hardware.org/?probe=6391114079) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [60d9839bbe](https://linux-hardware.org/?probe=60d9839bbe) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [45149f899d](https://linux-hardware.org/?probe=45149f899d) | Jul 26, 2023 |
| Gigabyte      | Z590 UD                     | [8504edcacf](https://linux-hardware.org/?probe=8504edcacf) | Jul 21, 2023 |
| ASUSTek       | PRIME X370-PRO              | [4884c4b183](https://linux-hardware.org/?probe=4884c4b183) | Jul 18, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 6.1.57-gentoo              | 10       | 5.62%   |
| 6.6.13-gentoo              | 8        | 4.49%   |
| 6.1.67-gentoo              | 7        | 3.93%   |
| 6.1.57-gentoo-x86_64       | 7        | 3.93%   |
| 6.1.53-gentoo-r1           | 7        | 3.93%   |
| 6.6.13-gentoo-x86_64       | 6        | 3.37%   |
| 6.6.13-gentoo-dist         | 5        | 2.81%   |
| 6.1.67-gentoo-x86_64       | 5        | 2.81%   |
| 6.6.21-gentoo-x86_64       | 4        | 2.25%   |
| 6.6.21-gentoo              | 4        | 2.25%   |
| 6.1.41-gentoo              | 4        | 2.25%   |
| 6.6.21-gentoo-dist         | 3        | 1.69%   |
| 6.5.7-gentoo               | 3        | 1.69%   |
| 6.4.10-gentoo-x86_64       | 3        | 1.69%   |
| 6.1.46-gentoo              | 3        | 1.69%   |
| 6.7.4-gentoo-dist          | 2        | 1.12%   |
| 6.6.8-gentoo-x86_64        | 2        | 1.12%   |
| 6.6.8-gentoo               | 2        | 1.12%   |
| 6.6.2-gentoo               | 2        | 1.12%   |
| 6.6.16-gentoo-dist         | 2        | 1.12%   |
| 6.6.0-gentoo               | 2        | 1.12%   |
| 6.5.9-gentoo-x86_64        | 2        | 1.12%   |
| 6.5.0-gentoo               | 2        | 1.12%   |
| 6.4.3-gentoo               | 2        | 1.12%   |
| 6.1.69-gentoo-dist         | 2        | 1.12%   |
| 6.9.0-rc1-git              | 1        | 0.56%   |
| 6.8.1-arch1-1              | 1        | 0.56%   |
| 6.7.6-gentoo               | 1        | 0.56%   |
| 6.7.6-dist                 | 1        | 0.56%   |
| 6.7.4-gentoo-NVIDIA        | 1        | 0.56%   |
| 6.7.3-gentoo-dist-hardened | 1        | 0.56%   |
| 6.7.3-gentoo               | 1        | 0.56%   |
| 6.7.2-gentoo-r1            | 1        | 0.56%   |
| 6.7.1-gentoo-r1-x86_64     | 1        | 0.56%   |
| 6.7.0-rc6                  | 1        | 0.56%   |
| 6.7.0-rc1                  | 1        | 0.56%   |
| 6.7.0-gentoo-x86_64        | 1        | 0.56%   |
| 6.6.9-xanmod1              | 1        | 0.56%   |
| 6.6.8-zen1                 | 1        | 0.56%   |
| 6.6.8-gentoo-HJ0x7E8.02    | 1        | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1.57  | 20       | 11.3%   |
| 6.6.13  | 19       | 10.73%  |
| 6.1.67  | 13       | 7.34%   |
| 6.6.21  | 11       | 6.21%   |
| 6.1.53  | 10       | 5.65%   |
| 6.6.8   | 7        | 3.95%   |
| 6.1.46  | 6        | 3.39%   |
| 6.5.7   | 5        | 2.82%   |
| 6.4.10  | 5        | 2.82%   |
| 6.6.0   | 4        | 2.26%   |
| 6.5.9   | 4        | 2.26%   |
| 6.5.0   | 4        | 2.26%   |
| 6.1.41  | 4        | 2.26%   |
| 6.7.4   | 3        | 1.69%   |
| 6.7.0   | 3        | 1.69%   |
| 6.6.2   | 3        | 1.69%   |
| 6.6.16  | 3        | 1.69%   |
| 6.5.5   | 3        | 1.69%   |
| 6.4.3   | 3        | 1.69%   |
| 6.7.6   | 2        | 1.13%   |
| 6.7.3   | 2        | 1.13%   |
| 6.6.6   | 2        | 1.13%   |
| 6.6.4   | 2        | 1.13%   |
| 6.6.3   | 2        | 1.13%   |
| 6.6.1   | 2        | 1.13%   |
| 6.5.8   | 2        | 1.13%   |
| 6.5.3   | 2        | 1.13%   |
| 6.4.8   | 2        | 1.13%   |
| 6.1.74  | 2        | 1.13%   |
| 6.1.69  | 2        | 1.13%   |
| 6.1.66  | 2        | 1.13%   |
| 6.9.0   | 1        | 0.56%   |
| 6.8.1   | 1        | 0.56%   |
| 6.7.2   | 1        | 0.56%   |
| 6.7.1   | 1        | 0.56%   |
| 6.6.9   | 1        | 0.56%   |
| 6.6.7   | 1        | 0.56%   |
| 6.6.22  | 1        | 0.56%   |
| 6.5.6   | 1        | 0.56%   |
| 6.5.2   | 1        | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.6     | 55       | 34.81%  |
| 6.1     | 50       | 31.65%  |
| 6.5     | 19       | 12.03%  |
| 6.4     | 14       | 8.86%   |
| 6.7     | 12       | 7.59%   |
| 6.3     | 3        | 1.9%    |
| 5.15    | 2        | 1.27%   |
| 6.9     | 1        | 0.63%   |
| 6.8     | 1        | 0.63%   |
| 5.14    | 1        | 0.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| x86_64      | 139      | 97.89%  |
| loongarch64 | 2        | 1.41%   |
| i686        | 1        | 0.7%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 50       | 34.01%  |
| KDE5       | 42       | 28.57%  |
| XFCE       | 19       | 12.93%  |
| GNOME      | 15       | 10.2%   |
| MATE       | 5        | 3.4%    |
| X-Cinnamon | 3        | 2.04%   |
| LXQt       | 3        | 2.04%   |
| i3         | 3        | 2.04%   |
| Hyprland   | 3        | 2.04%   |
| KDE        | 2        | 1.36%   |
| dwm        | 2        | 1.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 61       | 40.94%  |
| Unknown | 35       | 23.49%  |
| Wayland | 33       | 22.15%  |
| Tty     | 20       | 13.42%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 63       | 43.75%  |
| SDDM    | 42       | 29.17%  |
| LightDM | 23       | 15.97%  |
| GDM     | 9        | 6.25%   |
| SLiM    | 3        | 2.08%   |
| LXDM    | 2        | 1.39%   |
| XDM     | 1        | 0.69%   |
| GREETD  | 1        | 0.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 53       | 36.81%  |
| C.UTF8     | 23       | 15.97%  |
| en_GB      | 14       | 9.72%   |
| Unknown    | 10       | 6.94%   |
| de_DE      | 7        | 4.86%   |
| ru_RU      | 6        | 4.17%   |
| it_IT      | 5        | 3.47%   |
| fr_FR      | 4        | 2.78%   |
| C          | 3        | 2.08%   |
| pt_BR      | 2        | 1.39%   |
| zh_TW      | 1        | 0.69%   |
| zh_CN      | 1        | 0.69%   |
| ru_RU.UTF8 | 1        | 0.69%   |
| POSIX      | 1        | 0.69%   |
| nl_NL      | 1        | 0.69%   |
| lt_LT      | 1        | 0.69%   |
| fr_CA      | 1        | 0.69%   |
| es_ES.UTF8 | 1        | 0.69%   |
| es_ES      | 1        | 0.69%   |
| es_AR      | 1        | 0.69%   |
| en_IE@euro | 1        | 0.69%   |
| en_IE      | 1        | 0.69%   |
| en_DK      | 1        | 0.69%   |
| en         | 1        | 0.69%   |
| de_CH      | 1        | 0.69%   |
| ca_ES      | 1        | 0.69%   |
| bg_BG      | 1        | 0.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 116      | 80.56%  |
| BIOS | 28       | 19.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 81       | 56.25%  |
| Btrfs    | 26       | 18.06%  |
| Xfs      | 15       | 10.42%  |
| F2fs     | 11       | 7.64%   |
| Zfs      | 6        | 4.17%   |
| XXXXXXX  | 3        | 2.08%   |
| Reiserfs | 1        | 0.69%   |
| Ext2     | 1        | 0.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 124      | 87.32%  |
| Unknown | 10       | 7.04%   |
| MBR     | 8        | 5.63%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 94       | 63.95%  |
| Yes       | 53       | 36.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 98       | 68.06%  |
| Yes       | 46       | 31.94%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 52       | 36.62%  |
| Gigabyte Technology | 27       | 19.01%  |
| MSI                 | 19       | 13.38%  |
| ASRock              | 11       | 7.75%   |
| Dell                | 7        | 4.93%   |
| Hewlett-Packard     | 5        | 3.52%   |
| Unknown             | 5        | 3.52%   |
| Loongson            | 2        | 1.41%   |
| Lenovo              | 2        | 1.41%   |
| Fujitsu             | 2        | 1.41%   |
| transtec            | 1        | 0.7%    |
| SZMZ                | 1        | 0.7%    |
| Supermicro          | 1        | 0.7%    |
| Medion              | 1        | 0.7%    |
| Intel               | 1        | 0.7%    |
| Google              | 1        | 0.7%    |
| Foxconn             | 1        | 0.7%    |
| Colorful Technology | 1        | 0.7%    |
| BESSTAR Tech        | 1        | 0.7%    |
| ASRockRack          | 1        | 0.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Desktops | Percent |
|---------------------------------------|----------|---------|
| Unknown                               | 5        | 3.52%   |
| ASUS TUF Gaming B550-PLUS             | 3        | 2.11%   |
| MSI MS-7C02                           | 2        | 1.41%   |
| HP Z420 Workstation                   | 2        | 1.41%   |
| Gigabyte X570 AORUS ELITE             | 2        | 1.41%   |
| Gigabyte B550 AORUS ELITE V2          | 2        | 1.41%   |
| Gigabyte B450M DS3H                   | 2        | 1.41%   |
| ASUS ROG STRIX X670E-E GAMING WIFI    | 2        | 1.41%   |
| ASUS ROG STRIX X570-E GAMING          | 2        | 1.41%   |
| ASUS PRIME H510M-E                    | 2        | 1.41%   |
| ASUS PRIME B660-PLUS D4               | 2        | 1.41%   |
| ASUS M3A78-CM                         | 2        | 1.41%   |
| transtec GE2 Series                   | 1        | 0.7%    |
| SZMZ X99M-G2                          | 1        | 0.7%    |
| Supermicro SYS-5038MD-H24TRF-OS012    | 1        | 0.7%    |
| MSI MS-7E27                           | 1        | 0.7%    |
| MSI MS-7E10                           | 1        | 0.7%    |
| MSI MS-7D89                           | 1        | 0.7%    |
| MSI MS-7D78                           | 1        | 0.7%    |
| MSI MS-7D67                           | 1        | 0.7%    |
| MSI MS-7D50                           | 1        | 0.7%    |
| MSI MS-7C94                           | 1        | 0.7%    |
| MSI MS-7C91                           | 1        | 0.7%    |
| MSI MS-7C84                           | 1        | 0.7%    |
| MSI MS-7C79                           | 1        | 0.7%    |
| MSI MS-7C60                           | 1        | 0.7%    |
| MSI MS-7C56                           | 1        | 0.7%    |
| MSI MS-7C37                           | 1        | 0.7%    |
| MSI MS-7C35                           | 1        | 0.7%    |
| MSI MS-7C09                           | 1        | 0.7%    |
| MSI MS-7B86                           | 1        | 0.7%    |
| MSI MS-7976                           | 1        | 0.7%    |
| Medion MD34100/2543                   | 1        | 0.7%    |
| Loongson 3A6000-HV-7A2000-1w-V0.1-EVB | 1        | 0.7%    |
| Loongson 3A6000-7A2000-1w-V0.1-EVB    | 1        | 0.7%    |
| Lenovo ThinkStation S30 4351B20       | 1        | 0.7%    |
| Lenovo ThinkCentre M73 10AY008JGE     | 1        | 0.7%    |
| Intel DH77EB AAG39073-304             | 1        | 0.7%    |
| HP Pavilion Gaming Desktop TG01-1xxx  | 1        | 0.7%    |
| HP EliteDesk 800 G5 SFF               | 1        | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                  | Desktops | Percent |
|---------------------------------------|----------|---------|
| ASUS PRIME                            | 17       | 11.97%  |
| ASUS ROG                              | 14       | 9.86%   |
| ASUS TUF                              | 8        | 5.63%   |
| Unknown                               | 5        | 3.52%   |
| Gigabyte X570                         | 3        | 2.11%   |
| Gigabyte B550                         | 3        | 2.11%   |
| Dell Precision                        | 3        | 2.11%   |
| Dell OptiPlex                         | 3        | 2.11%   |
| MSI MS-7C02                           | 2        | 1.41%   |
| HP Z420                               | 2        | 1.41%   |
| Gigabyte B560M                        | 2        | 1.41%   |
| Gigabyte B450M                        | 2        | 1.41%   |
| ASUS M3A78-CM                         | 2        | 1.41%   |
| transtec GE2                          | 1        | 0.7%    |
| SZMZ X99M-G2                          | 1        | 0.7%    |
| Supermicro SYS-5038MD-H24TRF-OS012    | 1        | 0.7%    |
| MSI MS-7E27                           | 1        | 0.7%    |
| MSI MS-7E10                           | 1        | 0.7%    |
| MSI MS-7D89                           | 1        | 0.7%    |
| MSI MS-7D78                           | 1        | 0.7%    |
| MSI MS-7D67                           | 1        | 0.7%    |
| MSI MS-7D50                           | 1        | 0.7%    |
| MSI MS-7C94                           | 1        | 0.7%    |
| MSI MS-7C91                           | 1        | 0.7%    |
| MSI MS-7C84                           | 1        | 0.7%    |
| MSI MS-7C79                           | 1        | 0.7%    |
| MSI MS-7C60                           | 1        | 0.7%    |
| MSI MS-7C56                           | 1        | 0.7%    |
| MSI MS-7C37                           | 1        | 0.7%    |
| MSI MS-7C35                           | 1        | 0.7%    |
| MSI MS-7C09                           | 1        | 0.7%    |
| MSI MS-7B86                           | 1        | 0.7%    |
| MSI MS-7976                           | 1        | 0.7%    |
| Medion MD34100                        | 1        | 0.7%    |
| Loongson 3A6000-HV-7A2000-1w-V0.1-EVB | 1        | 0.7%    |
| Loongson 3A6000-7A2000-1w-V0.1-EVB    | 1        | 0.7%    |
| Lenovo ThinkStation                   | 1        | 0.7%    |
| Lenovo ThinkCentre                    | 1        | 0.7%    |
| Intel DH77EB                          | 1        | 0.7%    |
| HP Pavilion                           | 1        | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 20       | 14.08%  |
| 2022    | 17       | 11.97%  |
| 2021    | 15       | 10.56%  |
| 2018    | 15       | 10.56%  |
| 2019    | 14       | 9.86%   |
| 2023    | 10       | 7.04%   |
| 2012    | 10       | 7.04%   |
| 2017    | 8        | 5.63%   |
| Unknown | 5        | 3.52%   |
| 2016    | 4        | 2.82%   |
| 2014    | 4        | 2.82%   |
| 2010    | 4        | 2.82%   |
| 2015    | 3        | 2.11%   |
| 2013    | 3        | 2.11%   |
| 2011    | 3        | 2.11%   |
| 2009    | 2        | 1.41%   |
| 2008    | 2        | 1.41%   |
| 2007    | 2        | 1.41%   |
| 2024    | 1        | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 142      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 139      | 97.89%  |
| Enabled  | 3        | 2.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 141      | 99.3%   |
| Yes  | 1        | 0.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 50       | 35.21%  |
| 64.01-256.0 | 37       | 26.06%  |
| 16.01-24.0  | 29       | 20.42%  |
| 24.01-32.0  | 9        | 6.34%   |
| 4.01-8.0    | 7        | 4.93%   |
| 8.01-16.0   | 4        | 2.82%   |
| 3.01-4.0    | 3        | 2.11%   |
| 2.01-3.0    | 1        | 0.7%    |
| 1.01-2.0    | 1        | 0.7%    |
| 0.01-0.5    | 1        | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 33       | 21.15%  |
| 3.01-4.0   | 24       | 15.38%  |
| 2.01-3.0   | 24       | 15.38%  |
| 1.01-2.0   | 24       | 15.38%  |
| 8.01-16.0  | 19       | 12.18%  |
| 0.51-1.0   | 12       | 7.69%   |
| 16.01-24.0 | 10       | 6.41%   |
| 0.01-0.5   | 6        | 3.85%   |
| 32.01-64.0 | 2        | 1.28%   |
| 24.01-32.0 | 2        | 1.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 44       | 30.14%  |
| 1      | 29       | 19.86%  |
| 3      | 23       | 15.75%  |
| 4      | 21       | 14.38%  |
| 5      | 9        | 6.16%   |
| 6      | 8        | 5.48%   |
| 7      | 5        | 3.42%   |
| 8      | 3        | 2.05%   |
| 31     | 1        | 0.68%   |
| 19     | 1        | 0.68%   |
| 14     | 1        | 0.68%   |
| 13     | 1        | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 102      | 71.33%  |
| Yes       | 41       | 28.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 141      | 98.6%   |
| No        | 2        | 1.4%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 72       | 50.7%   |
| No        | 70       | 49.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 76       | 53.52%  |
| Yes       | 66       | 46.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 29       | 20.42%  |
| Germany     | 17       | 11.97%  |
| UK          | 9        | 6.34%   |
| Russia      | 9        | 6.34%   |
| Italy       | 8        | 5.63%   |
| Poland      | 7        | 4.93%   |
| France      | 7        | 4.93%   |
| China       | 5        | 3.52%   |
| Brazil      | 5        | 3.52%   |
| Belgium     | 5        | 3.52%   |
| Spain       | 4        | 2.82%   |
| Ireland     | 4        | 2.82%   |
| Finland     | 4        | 2.82%   |
| Canada      | 4        | 2.82%   |
| Sweden      | 3        | 2.11%   |
| Greece      | 3        | 2.11%   |
| Czechia     | 2        | 1.41%   |
| Austria     | 2        | 1.41%   |
| Argentina   | 2        | 1.41%   |
| Turkey      | 1        | 0.7%    |
| Taiwan      | 1        | 0.7%    |
| Switzerland | 1        | 0.7%    |
| Slovakia    | 1        | 0.7%    |
| Netherlands | 1        | 0.7%    |
| Luxembourg  | 1        | 0.7%    |
| Latvia      | 1        | 0.7%    |
| Japan       | 1        | 0.7%    |
| Hungary     | 1        | 0.7%    |
| Denmark     | 1        | 0.7%    |
| Colombia    | 1        | 0.7%    |
| Bulgaria    | 1        | 0.7%    |
| Belarus     | 1        | 0.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Milano           | 5        | 3.45%   |
| Warsaw           | 4        | 2.76%   |
| Dublin           | 4        | 2.76%   |
| Louvain-la-Neuve | 3        | 2.07%   |
| Helsinki         | 3        | 2.07%   |
| Athens           | 3        | 2.07%   |
| Vienna           | 2        | 1.38%   |
| Stockholm        | 2        | 1.38%   |
| St Petersburg    | 2        | 1.38%   |
| Rostov-on-Don    | 2        | 1.38%   |
| Oulx             | 2        | 1.38%   |
| New York         | 2        | 1.38%   |
| Le Boulou        | 2        | 1.38%   |
| Colchester       | 2        | 1.38%   |
| Cieszyn          | 2        | 1.38%   |
| Berlin           | 2        | 1.38%   |
| Beijing          | 2        | 1.38%   |
| Wrentham         | 1        | 0.69%   |
| Woburn           | 1        | 0.69%   |
| West Hartford    | 1        | 0.69%   |
| Weifang          | 1        | 0.69%   |
| Vladivostok      | 1        | 0.69%   |
| Ufa              | 1        | 0.69%   |
| Toulouse         | 1        | 0.69%   |
| Torredembarra    | 1        | 0.69%   |
| Tokyo            | 1        | 0.69%   |
| The Hague        | 1        | 0.69%   |
| Teufen AR        | 1        | 0.69%   |
| Swift Current    | 1        | 0.69%   |
| Suwanee          | 1        | 0.69%   |
| Stade            | 1        | 0.69%   |
| Springfield      | 1        | 0.69%   |
| Sofia            | 1        | 0.69%   |
| Slough           | 1        | 0.69%   |
| Sherwood Park    | 1        | 0.69%   |
| Seattle          | 1        | 0.69%   |
| Schmoelln        | 1        | 0.69%   |
| San Diego        | 1        | 0.69%   |
| Rio de Janeiro   | 1        | 0.69%   |
| Riga             | 1        | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 61       | 129    | 18.65%  |
| WDC                         | 44       | 83     | 13.46%  |
| Seagate                     | 44       | 85     | 13.46%  |
| Sandisk                     | 21       | 26     | 6.42%   |
| Phison Electronics          | 17       | 23     | 5.2%    |
| Toshiba                     | 15       | 55     | 4.59%   |
| Micron/Crucial Technology   | 11       | 13     | 3.36%   |
| Kingston                    | 11       | 11     | 3.36%   |
| Crucial                     | 11       | 19     | 3.36%   |
| Intel                       | 9        | 11     | 2.75%   |
| Hitachi                     | 8        | 30     | 2.45%   |
| Kingston Technology Company | 6        | 6      | 1.83%   |
| Realtek Semiconductor       | 5        | 5      | 1.53%   |
| GOODRAM                     | 4        | 25     | 1.22%   |
| A-DATA Technology           | 4        | 4      | 1.22%   |
| Unknown                     | 4        | 4      | 1.22%   |
| Yangtze Memory Technologies | 3        | 5      | 0.92%   |
| Silicon Motion              | 3        | 3      | 0.92%   |
| OCZ                         | 3        | 3      | 0.92%   |
| MAXIO Technology (Hangzhou) | 3        | 3      | 0.92%   |
| China                       | 3        | 4      | 0.92%   |
| Unknown                     | 2        | 5      | 0.61%   |
| Transcend                   | 2        | 2      | 0.61%   |
| SK hynix                    | 2        | 2      | 0.61%   |
| SABRENT                     | 2        | 2      | 0.61%   |
| Patriot                     | 2        | 4      | 0.61%   |
| KIOXIA                      | 2        | 3      | 0.61%   |
| HGST                        | 2        | 2      | 0.61%   |
| ADATA Technology            | 2        | 2      | 0.61%   |
| Verbatim                    | 1        | 1      | 0.31%   |
| Team                        | 1        | 1      | 0.31%   |
| SPCC                        | 1        | 3      | 0.31%   |
| Seagate Technology          | 1        | 1      | 0.31%   |
| PNY                         | 1        | 1      | 0.31%   |
| Phison                      | 1        | 1      | 0.31%   |
| NETAPP                      | 1        | 3      | 0.31%   |
| Micron Technology           | 1        | 1      | 0.31%   |
| Maxtor                      | 1        | 1      | 0.31%   |
| LITEON                      | 1        | 1      | 0.31%   |
| Lenovo                      | 1        | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 21       | 5.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 12       | 3.07%   |
| Samsung SSD 980 1TB                                   | 8        | 2.05%   |
| Seagate ST4000DM004-2CV104 4TB                        | 6        | 1.53%   |
| Seagate ST2000DM008-2FR102 2TB                        | 6        | 1.53%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                   | 6        | 1.53%   |
| Seagate ST2000DM006-2DM164 2TB                        | 5        | 1.28%   |
| Phison E12 NVMe Controller 2TB                        | 5        | 1.28%   |
| Kingston Company A2000 NVMe SSD 500GB                 | 5        | 1.28%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 4        | 1.02%   |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 4        | 1.02%   |
| Seagate ST2000DM008-2UB102 2TB                        | 4        | 1.02%   |
| Samsung SSD 860 EVO 1TB                               | 4        | 1.02%   |
| Samsung SSD 850 EVO 500GB                             | 4        | 1.02%   |
| Unknown                                               | 4        | 1.02%   |
| WDC WD30EFRX-68EUZN0 3TB                              | 3        | 0.77%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 3        | 0.77%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 3        | 0.77%   |
| Seagate ST500DM002-1BD142 500GB                       | 3        | 0.77%   |
| SanDisk SSD PLUS 240GB                                | 3        | 0.77%   |
| Samsung SSD 870 EVO 1TB                               | 3        | 0.77%   |
| Samsung SSD 860 EVO 500GB                             | 3        | 0.77%   |
| Samsung SSD 860 EVO 250GB                             | 3        | 0.77%   |
| Samsung SSD 850 PRO 512GB                             | 3        | 0.77%   |
| Phison E16 PCIe4 NVMe Controller 1TB                  | 3        | 0.77%   |
| Micron/Crucial CT1000P5PSSD8 1TB                      | 3        | 0.77%   |
| Kingston SKC3000D2048G 2TB                            | 3        | 0.77%   |
| Kingston SA400S37480G 480GB SSD                       | 3        | 0.77%   |
| GOODRAM SSDPR-CL100-480-G2 480GB                      | 3        | 0.77%   |
| Crucial CT1000MX500SSD1 1TB                           | 3        | 0.77%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 2        | 0.51%   |
| WDC WD10EZEX-00WN4A0 1TB                              | 2        | 0.51%   |
| WDC WD10EZEX-00BBHA0 1TB                              | 2        | 0.51%   |
| WDC WD102KRYZ-01A5AB0 10TB                            | 2        | 0.51%   |
| Toshiba MG06ACA800E 8TB                               | 2        | 0.51%   |
| Toshiba HDWE150 5TB                                   | 2        | 0.51%   |
| Toshiba DT01ACA100 1TB                                | 2        | 0.51%   |
| Seagate ST4000VN008-2DR166 4TB                        | 2        | 0.51%   |
| Seagate ST3000DM008-2DM166 3TB                        | 2        | 0.51%   |
| Seagate ST2000DL003-9VT166 2TB                        | 2        | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 44       | 84     | 37.61%  |
| WDC                 | 40       | 74     | 34.19%  |
| Toshiba             | 14       | 54     | 11.97%  |
| Hitachi             | 8        | 30     | 6.84%   |
| Samsung Electronics | 2        | 3      | 1.71%   |
| SABRENT             | 2        | 2      | 1.71%   |
| HGST                | 2        | 2      | 1.71%   |
| NETAPP              | 1        | 3      | 0.85%   |
| Maxtor              | 1        | 1      | 0.85%   |
| Fujitsu             | 1        | 1      | 0.85%   |
| FC-1307             | 1        | 1      | 0.85%   |
| Unknown             | 1        | 1      | 0.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 31       | 50     | 29.52%  |
| Crucial             | 11       | 19     | 10.48%  |
| WDC                 | 8        | 9      | 7.62%   |
| SanDisk             | 8        | 9      | 7.62%   |
| Kingston            | 7        | 7      | 6.67%   |
| GOODRAM             | 4        | 25     | 3.81%   |
| A-DATA Technology   | 4        | 4      | 3.81%   |
| OCZ                 | 3        | 3      | 2.86%   |
| Intel               | 3        | 3      | 2.86%   |
| China               | 3        | 4      | 2.86%   |
| Unknown             | 3        | 3      | 2.86%   |
| Transcend           | 2        | 2      | 1.9%    |
| Patriot             | 2        | 4      | 1.9%    |
| Verbatim            | 1        | 1      | 0.95%   |
| Toshiba             | 1        | 1      | 0.95%   |
| Team                | 1        | 1      | 0.95%   |
| SPCC                | 1        | 3      | 0.95%   |
| SK hynix            | 1        | 1      | 0.95%   |
| PNY                 | 1        | 1      | 0.95%   |
| LITEON              | 1        | 1      | 0.95%   |
| Lenovo              | 1        | 1      | 0.95%   |
| KingSpec            | 1        | 1      | 0.95%   |
| Kingchuxing         | 1        | 5      | 0.95%   |
| Intenso             | 1        | 1      | 0.95%   |
| Hewlett-Packard     | 1        | 1      | 0.95%   |
| FREEBSD             | 1        | 12     | 0.95%   |
| Apple               | 1        | 1      | 0.95%   |
| Apacer              | 1        | 1      | 0.95%   |
| AGI                 | 1        | 1      | 0.95%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| NVMe    | 93       | 174    | 35.09%  |
| HDD     | 87       | 256    | 32.83%  |
| SSD     | 84       | 175    | 31.7%   |
| Unknown | 1        | 4      | 0.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 116      | 427    | 54.46%  |
| NVMe | 93       | 174    | 43.66%  |
| SAS  | 4        | 8      | 1.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 73       | 135    | 36.14%  |
| 0.51-1.0   | 54       | 90     | 26.73%  |
| 1.01-2.0   | 28       | 54     | 13.86%  |
| 3.01-4.0   | 20       | 52     | 9.9%    |
| 4.01-10.0  | 11       | 45     | 5.45%   |
| 2.01-3.0   | 10       | 35     | 4.95%   |
| 10.01-20.0 | 6        | 20     | 2.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 41       | 27.89%  |
| 1001-2000      | 22       | 14.97%  |
| 501-1000       | 22       | 14.97%  |
| 101-250        | 17       | 11.56%  |
| 1-20           | 13       | 8.84%   |
| 251-500        | 12       | 8.16%   |
| 2001-3000      | 10       | 6.8%    |
| Unknown        | 5        | 3.4%    |
| 21-50          | 3        | 2.04%   |
| 51-100         | 2        | 1.36%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 36       | 24%     |
| 1001-2000      | 21       | 14%     |
| 101-250        | 18       | 12%     |
| 251-500        | 17       | 11.33%  |
| More than 3000 | 16       | 10.67%  |
| 501-1000       | 14       | 9.33%   |
| 51-100         | 11       | 7.33%   |
| 21-50          | 7        | 4.67%   |
| 2001-3000      | 5        | 3.33%   |
| Unknown        | 5        | 3.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD20EZRZ-00Z5HB0 2TB            | 2        | 2      | 6.9%    |
| WDC WD3200BEVT-22ZCT0 320GB         | 1        | 1      | 3.45%   |
| WDC WD30EFRX-68EUZN0 3TB            | 1        | 4      | 3.45%   |
| WDC WD2002FAEX-007BA0 2TB           | 1        | 1      | 3.45%   |
| WDC WD10EZEX-00RKKA0 1TB            | 1        | 1      | 3.45%   |
| WDC WD10EFRX-68PJCN0 1TB            | 1        | 1      | 3.45%   |
| WDC WD10EADS-00M2B0 1TB             | 1        | 1      | 3.45%   |
| Toshiba HDWE150 5TB                 | 1        | 4      | 3.45%   |
| Toshiba HDWD240 4TB                 | 1        | 2      | 3.45%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 3.45%   |
| Seagate ST500DM002-1BC142 500GB     | 1        | 1      | 3.45%   |
| Seagate ST3160811AS 160GB           | 1        | 1      | 3.45%   |
| Seagate ST31000524AS 1TB            | 1        | 1      | 3.45%   |
| Seagate ST3000DM008-2DM166 3TB      | 1        | 2      | 3.45%   |
| Seagate ST2000DM005-2CW102 2TB      | 1        | 1      | 3.45%   |
| Seagate ST1000DM010-2EP102 1TB      | 1        | 1      | 3.45%   |
| Samsung Electronics SSD 980 1TB     | 1        | 1      | 3.45%   |
| PNY SSD2SC120G1LC763C121S459P 120GB | 1        | 1      | 3.45%   |
| OCZ AGILITY3 128GB SSD              | 1        | 1      | 3.45%   |
| Maxtor STM3160215A 160GB            | 1        | 1      | 3.45%   |
| Kingston SV300S37A240G 240GB SSD    | 1        | 1      | 3.45%   |
| Kingston SV300S37A 120G SSD         | 1        | 1      | 3.45%   |
| Intel SSDSCKKF180G8L 180GB          | 1        | 1      | 3.45%   |
| Hitachi HUS724030ALE641 3TB         | 1        | 1      | 3.45%   |
| Hitachi HDS722020ALA330 2TB         | 1        | 1      | 3.45%   |
| HGST HTS721010A9E630 1TB            | 1        | 1      | 3.45%   |
| A-DATA Technology SP900 128GB SSD   | 1        | 1      | 3.45%   |
| Unknown                             | 1        | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 11     | 27.59%  |
| Seagate             | 7        | 8      | 24.14%  |
| Toshiba             | 2        | 6      | 6.9%    |
| Kingston            | 2        | 2      | 6.9%    |
| Hitachi             | 2        | 2      | 6.9%    |
| Samsung Electronics | 1        | 1      | 3.45%   |
| PNY                 | 1        | 1      | 3.45%   |
| OCZ                 | 1        | 1      | 3.45%   |
| Maxtor              | 1        | 1      | 3.45%   |
| Intel               | 1        | 1      | 3.45%   |
| HGST                | 1        | 1      | 3.45%   |
| A-DATA Technology   | 1        | 1      | 3.45%   |
| Unknown             | 1        | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 8        | 11     | 36.36%  |
| Seagate | 7        | 8      | 31.82%  |
| Toshiba | 2        | 6      | 9.09%   |
| Hitachi | 2        | 2      | 9.09%   |
| Maxtor  | 1        | 1      | 4.55%   |
| HGST    | 1        | 1      | 4.55%   |
| Unknown | 1        | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 30     | 75%     |
| SSD  | 6        | 6      | 21.43%  |
| NVMe | 1        | 1      | 3.57%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| Hitachi HTS723232L9A360 320GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 131      | 515    | 75.72%  |
| Malfunc  | 27       | 37     | 15.61%  |
| Detected | 14       | 56     | 8.09%   |
| Failed   | 1        | 1      | 0.58%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| AMD                              | 70       | 25.18%  |
| Intel                            | 66       | 23.74%  |
| Samsung Electronics              | 39       | 14.03%  |
| Phison Electronics               | 18       | 6.47%   |
| SanDisk                          | 14       | 5.04%   |
| Micron/Crucial Technology        | 11       | 3.96%   |
| ASMedia Technology               | 11       | 3.96%   |
| Kingston Technology Company      | 10       | 3.6%    |
| Realtek Semiconductor            | 5        | 1.8%    |
| Marvell Technology Group         | 4        | 1.44%   |
| Yangtze Memory Technologies      | 3        | 1.08%   |
| Silicon Motion                   | 3        | 1.08%   |
| Nvidia                           | 3        | 1.08%   |
| MAXIO Technology (Hangzhou)      | 3        | 1.08%   |
| LSI Logic / Symbios Logic        | 3        | 1.08%   |
| Loongson Technology              | 2        | 0.72%   |
| KIOXIA                           | 2        | 0.72%   |
| JMicron Technology               | 2        | 0.72%   |
| ADATA Technology                 | 2        | 0.72%   |
| VIA Technologies                 | 1        | 0.36%   |
| SK hynix                         | 1        | 0.36%   |
| Silicon Integrated Systems [SiS] | 1        | 0.36%   |
| Seagate Technology               | 1        | 0.36%   |
| Micron Technology                | 1        | 0.36%   |
| INNOGRIT                         | 1        | 0.36%   |
| Broadcom / LSI                   | 1        | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 24       | 7.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 21       | 6.4%    |
| AMD 500 Series Chipset SATA Controller                                         | 19       | 5.79%   |
| AMD 600 Series Chipset SATA Controller                                         | 14       | 4.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 12       | 3.66%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 11       | 3.35%   |
| AMD 400 Series Chipset SATA Controller                                         | 9        | 2.74%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 8        | 2.44%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 7        | 2.13%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 7        | 2.13%   |
| Phison E18 PCIe4 NVMe Controller                                               | 6        | 1.83%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 6        | 1.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6        | 1.83%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 6        | 1.83%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 5        | 1.52%   |
| Phison E12 NVMe Controller                                                     | 5        | 1.52%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 5        | 1.52%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 5        | 1.52%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 4        | 1.22%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4        | 1.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 1.22%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4        | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4        | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4        | 1.22%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3        | 0.91%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 3        | 0.91%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 3        | 0.91%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3        | 0.91%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 3        | 0.91%   |
| Intel SATA Controller [RAID Mode]                                              | 3        | 0.91%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 3        | 0.91%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 3        | 0.91%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 3        | 0.91%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 3        | 0.91%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 0.91%   |
| ASMedia ASM1064 Serial ATA Controller                                          | 3        | 0.91%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3        | 0.91%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2        | 0.61%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2        | 0.61%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 135      | 52.12%  |
| NVMe | 93       | 35.91%  |
| IDE  | 15       | 5.79%   |
| RAID | 11       | 4.25%   |
| SAS  | 5        | 1.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| AMD          | 72       | 50.7%   |
| Intel        | 67       | 47.18%  |
| Loongson     | 2        | 1.41%   |
| CyrixInstead | 1        | 0.7%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| AMD Ryzen 9 5900X 12-Core Processor     | 9        | 6.29%   |
| AMD Ryzen 9 7950X 16-Core Processor     | 4        | 2.8%    |
| AMD Ryzen 9 3950X 16-Core Processor     | 4        | 2.8%    |
| AMD Ryzen 9 3900X 12-Core Processor     | 4        | 2.8%    |
| AMD Ryzen 5 5600X 6-Core Processor      | 4        | 2.8%    |
| AMD Ryzen 5 3600 6-Core Processor       | 4        | 2.8%    |
| AMD Ryzen 7 5800X3D 8-Core Processor    | 3        | 2.1%    |
| AMD Ryzen 7 5800X 8-Core Processor      | 3        | 2.1%    |
| Loongson 3A6000                         | 2        | 1.4%    |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz     | 2        | 1.4%    |
| Intel N100                              | 2        | 1.4%    |
| Intel Core i9-9900K CPU @ 3.60GHz       | 2        | 1.4%    |
| Intel Core i7-8700 CPU @ 3.20GHz        | 2        | 1.4%    |
| Intel Core i7-3770 CPU @ 3.40GHz        | 2        | 1.4%    |
| Intel Core i5-8400 CPU @ 2.80GHz        | 2        | 1.4%    |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2        | 1.4%    |
| Intel 12th Gen Core i5-12600K           | 2        | 1.4%    |
| Intel 12th Gen Core i5-12400            | 2        | 1.4%    |
| Intel 11th Gen Core i9-11900K @ 3.50GHz | 2        | 1.4%    |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 2        | 1.4%    |
| AMD Ryzen 9 7950X3D 16-Core Processor   | 2        | 1.4%    |
| AMD Ryzen 9 7900X 12-Core Processor     | 2        | 1.4%    |
| AMD Ryzen 9 5950X 16-Core Processor     | 2        | 1.4%    |
| AMD Ryzen 7 7800X3D 8-Core Processor    | 2        | 1.4%    |
| AMD Ryzen 5 7600X 6-Core Processor      | 2        | 1.4%    |
| AMD Ryzen 5 7600 6-Core Processor       | 2        | 1.4%    |
| AMD Ryzen 5 5600G with Radeon Graphics  | 2        | 1.4%    |
| AMD Ryzen 5 5500                        | 2        | 1.4%    |
| AMD Ryzen 5 2600 Six-Core Processor     | 2        | 1.4%    |
| AMD Phenom II X4 955 Processor          | 2        | 1.4%    |
| AMD FX-8350 Eight-Core Processor        | 2        | 1.4%    |
| Loongson 3A6000-HV                      | 1        | 0.7%    |
| Intel Xeon CPU X5690 @ 3.47GHz          | 1        | 0.7%    |
| Intel Xeon CPU E5-2690 v3 @ 2.60GHz     | 1        | 0.7%    |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz      | 1        | 0.7%    |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz     | 1        | 0.7%    |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz      | 1        | 0.7%    |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz     | 1        | 0.7%    |
| Intel Xeon CPU E5-1680 v2 @ 3.00GHz     | 1        | 0.7%    |
| Intel Xeon CPU E3-1240L v5 @ 2.10GHz    | 1        | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 9            | 29       | 20.42%  |
| Other                  | 20       | 14.08%  |
| AMD Ryzen 5            | 19       | 13.38%  |
| Intel Core i7          | 17       | 11.97%  |
| AMD Ryzen 7            | 13       | 9.15%   |
| Intel Xeon             | 11       | 7.75%   |
| Intel Core i5          | 10       | 7.04%   |
| Intel Core i3          | 4        | 2.82%   |
| AMD FX                 | 4        | 2.82%   |
| Intel Core i9          | 3        | 2.11%   |
| Intel Atom             | 2        | 1.41%   |
| AMD Ryzen Threadripper | 2        | 1.41%   |
| AMD Phenom II X4       | 2        | 1.41%   |
| Intel Pentium          | 1        | 0.7%    |
| Intel Core 2           | 1        | 0.7%    |
| Intel Celeron          | 1        | 0.7%    |
| AMD Ryzen 3            | 1        | 0.7%    |
| AMD Phenom II X6       | 1        | 0.7%    |
| AMD Athlon 64 X2       | 1        | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 36       | 25.35%  |
| 4      | 30       | 21.13%  |
| 8      | 25       | 17.61%  |
| 12     | 19       | 13.38%  |
| 16     | 16       | 11.27%  |
| 2      | 9        | 6.34%   |
| 10     | 3        | 2.11%   |
| 32     | 1        | 0.7%    |
| 24     | 1        | 0.7%    |
| 20     | 1        | 0.7%    |
| 1      | 1        | 0.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 140      | 98.59%  |
| 2      | 2        | 1.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 119      | 83.8%   |
| 1      | 23       | 16.2%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 141      | 99.3%   |
| 32-bit         | 1        | 0.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 60       | 40.54%  |
| 0x0a20120a | 9        | 6.08%   |
| 0x0a601206 | 7        | 4.73%   |
| 0x0a601203 | 6        | 4.05%   |
| 0x08701021 | 6        | 4.05%   |
| 0x0a201016 | 5        | 3.38%   |
| 0x906ea    | 3        | 2.03%   |
| 0x90672    | 3        | 2.03%   |
| 0x306e4    | 3        | 2.03%   |
| 0x306a9    | 3        | 2.03%   |
| 0x08701030 | 3        | 2.03%   |
| 0x0800820d | 3        | 2.03%   |
| 0xb06e0    | 2        | 1.35%   |
| 0x506e3    | 2        | 1.35%   |
| 0x306f2    | 2        | 1.35%   |
| 0x206d7    | 2        | 1.35%   |
| 0x206a7    | 2        | 1.35%   |
| 0x0a50000f | 2        | 1.35%   |
| 0x0a50000d | 2        | 1.35%   |
| 0x010000db | 2        | 1.35%   |
| 0xb0671    | 1        | 0.68%   |
| 0xa0671    | 1        | 0.68%   |
| 0x906ed    | 1        | 0.68%   |
| 0x906e9    | 1        | 0.68%   |
| 0x90675    | 1        | 0.68%   |
| 0x50663    | 1        | 0.68%   |
| 0x40651    | 1        | 0.68%   |
| 0x106c2    | 1        | 0.68%   |
| 0x0a20120e | 1        | 0.68%   |
| 0x0a201205 | 1        | 0.68%   |
| 0x0a20102b | 1        | 0.68%   |
| 0x0a201025 | 1        | 0.68%   |
| 0x08701013 | 1        | 0.68%   |
| 0x08301072 | 1        | 0.68%   |
| 0x08108102 | 1        | 0.68%   |
| 0x0800820b | 1        | 0.68%   |
| 0x08001138 | 1        | 0.68%   |
| 0x06000852 | 1        | 0.68%   |
| 0x06000822 | 1        | 0.68%   |
| 0x0600062e | 1        | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 27       | 18.75%  |
| Unknown          | 19       | 13.19%  |
| Zen 2            | 17       | 11.81%  |
| KabyLake         | 14       | 9.72%   |
| IvyBridge        | 9        | 6.25%   |
| Alderlake Hybrid | 9        | 6.25%   |
| Icelake          | 7        | 4.86%   |
| SandyBridge      | 6        | 4.17%   |
| Zen+             | 5        | 3.47%   |
| Haswell          | 5        | 3.47%   |
| Skylake          | 4        | 2.78%   |
| Piledriver       | 3        | 2.08%   |
| K10              | 3        | 2.08%   |
| CometLake        | 3        | 2.08%   |
| Broadwell        | 3        | 2.08%   |
| Gracemont        | 2        | 1.39%   |
| Bonnell          | 2        | 1.39%   |
| Zen              | 1        | 0.69%   |
| Westmere         | 1        | 0.69%   |
| Nehalem          | 1        | 0.69%   |
| K8 Hammer        | 1        | 0.69%   |
| Core             | 1        | 0.69%   |
| Bulldozer        | 1        | 0.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| AMD                              | 69       | 44.81%  |
| Nvidia                           | 54       | 35.06%  |
| Intel                            | 24       | 15.58%  |
| ASPEED Technology                | 4        | 2.6%    |
| Loongson Technology              | 2        | 1.3%    |
| Silicon Integrated Systems [SiS] | 1        | 0.65%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]       | 13       | 7.83%   |
| AMD Raphael                                                   | 11       | 6.63%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT] | 10       | 6.02%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                | 7        | 4.22%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                     | 5        | 3.01%   |
| ASPEED Technology ASPEED Graphics Family                      | 4        | 2.41%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                    | 4        | 2.41%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]       | 4        | 2.41%   |
| Nvidia GT218 [GeForce 210]                                    | 3        | 1.81%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                            | 3        | 1.81%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                            | 3        | 1.81%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                            | 3        | 1.81%   |
| Intel HD Graphics 530                                         | 3        | 1.81%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900M]                | 3        | 1.81%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]    | 3        | 1.81%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]  | 3        | 1.81%   |
| Nvidia GP108 [GeForce GT 1030]                                | 2        | 1.2%    |
| Nvidia GP107GL [Quadro P620]                                  | 2        | 1.2%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                            | 2        | 1.2%    |
| Nvidia GM204 [GeForce GTX 970]                                | 2        | 1.2%    |
| Nvidia GK208B [GeForce GT 710]                                | 2        | 1.2%    |
| Nvidia GF119 [GeForce GT 610]                                 | 2        | 1.2%    |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                | 2        | 1.2%    |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                | 2        | 1.2%    |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]             | 2        | 1.2%    |
| Loongson Technology Display Controller                        | 2        | 1.2%    |
| Intel RocketLake-S GT1 [UHD Graphics 750]                     | 2        | 1.2%    |
| Intel Alder Lake-N [UHD Graphics]                             | 2        | 1.2%    |
| AMD RS780C [Radeon 3100]                                      | 2        | 1.2%    |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                    | 2        | 1.2%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]              | 2        | 1.2%    |
| Silicon Integrated Systems [SiS] 5597/5598/6326 VGA           | 1        | 0.6%    |
| Nvidia TU116 [GeForce GTX 1660]                               | 1        | 0.6%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                         | 1        | 0.6%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                         | 1        | 0.6%    |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                         | 1        | 0.6%    |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                        | 1        | 0.6%    |
| Nvidia GP107GL [Quadro P400]                                  | 1        | 0.6%    |
| Nvidia GP107 [GeForce GTX 1050]                               | 1        | 0.6%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                           | 1        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| 1 x AMD                   | 55       | 38.19%  |
| 1 x Nvidia                | 45       | 31.25%  |
| 1 x Intel                 | 17       | 11.81%  |
| 2 x AMD                   | 7        | 4.86%   |
| Intel + Nvidia            | 4        | 2.78%   |
| 1 x ASPEED                | 4        | 2.78%   |
| AMD + Nvidia              | 4        | 2.78%   |
| Intel + AMD               | 2        | 1.39%   |
| AMD + Loongson Technology | 2        | 1.39%   |
| Other                     | 1        | 0.69%   |
| 2 x Nvidia                | 1        | 0.69%   |
| 2 x Intel                 | 1        | 0.69%   |
| 1 x SiS                   | 1        | 0.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 92       | 64.34%  |
| Proprietary | 36       | 25.17%  |
| Unknown     | 15       | 10.49%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 54       | 36.24%  |
| 7.01-8.0   | 26       | 17.45%  |
| 8.01-16.0  | 23       | 15.44%  |
| 1.01-2.0   | 13       | 8.72%   |
| 3.01-4.0   | 10       | 6.71%   |
| 0.01-0.5   | 8        | 5.37%   |
| 0.51-1.0   | 7        | 4.7%    |
| 16.01-24.0 | 4        | 2.68%   |
| 5.01-6.0   | 3        | 2.01%   |
| 2.01-3.0   | 1        | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 23       | 14.56%  |
| Goldstar             | 16       | 10.13%  |
| Dell                 | 15       | 9.49%   |
| BenQ                 | 14       | 8.86%   |
| Acer                 | 10       | 6.33%   |
| Philips              | 9        | 5.7%    |
| ViewSonic            | 6        | 3.8%    |
| ASUSTek Computer     | 6        | 3.8%    |
| AOC                  | 6        | 3.8%    |
| Iiyama               | 5        | 3.16%   |
| Hewlett-Packard      | 5        | 3.16%   |
| Lenovo               | 4        | 2.53%   |
| Gigabyte Technology  | 4        | 2.53%   |
| Ancor Communications | 4        | 2.53%   |
| Unknown              | 3        | 1.9%    |
| UGD                  | 2        | 1.27%   |
| Mi                   | 2        | 1.27%   |
| YZA                  | 1        | 0.63%   |
| VDO                  | 1        | 0.63%   |
| Valve                | 1        | 0.63%   |
| Toshiba              | 1        | 0.63%   |
| SuperFrame           | 1        | 0.63%   |
| Sceptre Tech         | 1        | 0.63%   |
| NEC Computers        | 1        | 0.63%   |
| MSI                  | 1        | 0.63%   |
| Monoprice            | 1        | 0.63%   |
| Microstep            | 1        | 0.63%   |
| Medion Akoya         | 1        | 0.63%   |
| LG Electronics       | 1        | 0.63%   |
| JRY                  | 1        | 0.63%   |
| Idek Iiyama          | 1        | 0.63%   |
| IBM                  | 1        | 0.63%   |
| Huion                | 1        | 0.63%   |
| HUAWEI               | 1        | 0.63%   |
| HJW                  | 1        | 0.63%   |
| Fujitsu Siemens      | 1        | 0.63%   |
| Element              | 1        | 0.63%   |
| Eizo                 | 1        | 0.63%   |
| EDI                  | 1        | 0.63%   |
| Chimei Innolux       | 1        | 0.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 3        | 1.74%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 3        | 1.74%   |
| BenQ PD2700U BNQ802E 3840x2160 597x336mm 27.0-inch                   | 3        | 1.74%   |
| AOC 24B2W1 AOC2402 1920x1080 527x296mm 23.8-inch                     | 3        | 1.74%   |
| UGD Artist13.3pro UGD1302 1920x1080 294x165mm 13.3-inch              | 2        | 1.16%   |
| Samsung Electronics U32H85x SAM0E3C 3840x2160 697x392mm 31.5-inch    | 2        | 1.16%   |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch | 2        | 1.16%   |
| Samsung Electronics SMS27A650 SAM082E 1920x1080 598x336mm 27.0-inch  | 2        | 1.16%   |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch    | 2        | 1.16%   |
| Philips 17S PHL0877 1280x1024 337x270mm 17.0-inch                    | 2        | 1.16%   |
| Mi 27 NFGL XMIB004 1920x1080 598x336mm 27.0-inch                     | 2        | 1.16%   |
| Iiyama PL2783Q IVM661F 2560x1440 597x336mm 27.0-inch                 | 2        | 1.16%   |
| Hewlett-Packard S230tm HWP3115 1920x1080 509x286mm 23.0-inch         | 2        | 1.16%   |
| Hewlett-Packard LA2206 HWP2946 1920x1080 476x268mm 21.5-inch         | 2        | 1.16%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                | 2        | 1.16%   |
| Dell U2719D DEL415A 2560x1440 597x336mm 27.0-inch                    | 2        | 1.16%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 2        | 1.16%   |
| BenQ GW2780 BNQ78E6 1920x1080 598x336mm 27.0-inch                    | 2        | 1.16%   |
| BenQ GL2780 BNQ78EC 1920x1080 598x336mm 27.0-inch                    | 2        | 1.16%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 527x296mm 23.8-inch         | 2        | 1.16%   |
| YZA WINGCOOL YZA0001 1920x1280 222x148mm 10.5-inch                   | 1        | 0.58%   |
| ViewSonic VX3276-UHD VSC5138 3840x2160 700x390mm 31.5-inch           | 1        | 0.58%   |
| ViewSonic VX2458 series VSC0437 1920x1080 521x293mm 23.5-inch        | 1        | 0.58%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch        | 1        | 0.58%   |
| ViewSonic VX2418C SER VSC1A3D 1920x1080 521x293mm 23.5-inch          | 1        | 0.58%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch        | 1        | 0.58%   |
| ViewSonic VA2231 Series VSCBB25 1920x1080 477x268mm 21.5-inch        | 1        | 0.58%   |
| VDO PATH.HDR VDO6666 2048x1152 600x340mm 27.2-inch                   | 1        | 0.58%   |
| Valve Index HMD VLV91A8 2880x1600                                    | 1        | 0.58%   |
| Toshiba TV TSB0108 1360x768 698x393mm 31.5-inch                      | 1        | 0.58%   |
| SuperFrame SFV2409 SUE2409 1920x1080 597x336mm 27.0-inch             | 1        | 0.58%   |
| Sceptre Tech E24 SPT099D 1920x1080 530x300mm 24.0-inch               | 1        | 0.58%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 1        | 0.58%   |
| Samsung Electronics SyncMaster SAM03E3 1680x1050 433x271mm 20.1-inch | 1        | 0.58%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch  | 1        | 0.58%   |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 520x320mm 24.0-inch  | 1        | 0.58%   |
| Samsung Electronics SMB2430L SAM0645 1920x1080 521x293mm 23.5-inch   | 1        | 0.58%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch    | 1        | 0.58%   |
| Samsung Electronics S22E200 SAM0C70 1680x1050 473x291mm 21.9-inch    | 1        | 0.58%   |
| Samsung Electronics S19B300 SAM08A6 1366x768 410x230mm 18.5-inch     | 1        | 0.58%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 56       | 40%     |
| 3840x2160 (4K)     | 26       | 18.57%  |
| 2560x1440 (QHD)    | 24       | 17.14%  |
| 1280x1024 (SXGA)   | 7        | 5%      |
| 2560x1080          | 4        | 2.86%   |
| 1920x1200 (WUXGA)  | 4        | 2.86%   |
| 3440x1440          | 3        | 2.14%   |
| 2288x1287          | 3        | 2.14%   |
| 3840x1080          | 2        | 1.43%   |
| 1366x768 (WXGA)    | 2        | 1.43%   |
| 7680x2160          | 1        | 0.71%   |
| 2048x1152          | 1        | 0.71%   |
| 1920x540           | 1        | 0.71%   |
| 1920x1280          | 1        | 0.71%   |
| 1680x1050 (WSXGA+) | 1        | 0.71%   |
| 1600x900 (HD+)     | 1        | 0.71%   |
| 1600x1200          | 1        | 0.71%   |
| 1400x1050          | 1        | 0.71%   |
| Unknown            | 1        | 0.71%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 46       | 29.87%  |
| 24      | 22       | 14.29%  |
| 23      | 19       | 12.34%  |
| 21      | 16       | 10.39%  |
| 31      | 9        | 5.84%   |
| 34      | 7        | 4.55%   |
| 17      | 6        | 3.9%    |
| 19      | 4        | 2.6%    |
| Unknown | 4        | 2.6%    |
| 142     | 3        | 1.95%   |
| 84      | 2        | 1.3%    |
| 48      | 2        | 1.3%    |
| 28      | 2        | 1.3%    |
| 20      | 2        | 1.3%    |
| 13      | 2        | 1.3%    |
| 72      | 1        | 0.65%   |
| 38      | 1        | 0.65%   |
| 36      | 1        | 0.65%   |
| 32      | 1        | 0.65%   |
| 26      | 1        | 0.65%   |
| 25      | 1        | 0.65%   |
| 18      | 1        | 0.65%   |
| 10      | 1        | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 75       | 52.45%  |
| 401-500        | 19       | 13.29%  |
| 601-700        | 16       | 11.19%  |
| 701-800        | 9        | 6.29%   |
| 301-350        | 5        | 3.5%    |
| Unknown        | 4        | 2.8%    |
| More than 2000 | 3        | 2.1%    |
| 351-400        | 3        | 2.1%    |
| 201-300        | 3        | 2.1%    |
| 1501-2000      | 3        | 2.1%    |
| 1001-1500      | 2        | 1.4%    |
| 801-900        | 1        | 0.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 97       | 75.19%  |
| 5/4     | 7        | 5.43%   |
| 21/9    | 7        | 5.43%   |
| 16/10   | 7        | 5.43%   |
| Unknown | 4        | 3.1%    |
| 1.00    | 3        | 2.33%   |
| 32/9    | 2        | 1.55%   |
| 4/3     | 1        | 0.78%   |
| 3/2     | 1        | 0.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 47       | 32.19%  |
| 201-250        | 37       | 25.34%  |
| 351-500        | 17       | 11.64%  |
| 251-300        | 12       | 8.22%   |
| 151-200        | 9        | 6.16%   |
| More than 1000 | 6        | 4.11%   |
| 141-150        | 6        | 4.11%   |
| 501-1000       | 4        | 2.74%   |
| Unknown        | 4        | 2.74%   |
| 71-80          | 2        | 1.37%   |
| 51-60          | 1        | 0.68%   |
| 121-130        | 1        | 0.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 70       | 49.3%   |
| 101-120 | 34       | 23.94%  |
| 121-160 | 17       | 11.97%  |
| 161-240 | 12       | 8.45%   |
| 1-50    | 5        | 3.52%   |
| Unknown | 4        | 2.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 88       | 60.27%  |
| 2     | 26       | 17.81%  |
| 0     | 21       | 14.38%  |
| 3     | 7        | 4.79%   |
| 4     | 4        | 2.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 88       | 41.12%  |
| Intel                           | 84       | 39.25%  |
| MediaTek                        | 9        | 4.21%   |
| Qualcomm Atheros                | 7        | 3.27%   |
| Nvidia                          | 3        | 1.4%    |
| Broadcom                        | 3        | 1.4%    |
| TP-Link                         | 2        | 0.93%   |
| Ralink Technology               | 2        | 0.93%   |
| Marvell Technology Group        | 2        | 0.93%   |
| Loongson Technology             | 2        | 0.93%   |
| U-Blox                          | 1        | 0.47%   |
| Qualcomm Atheros Communications | 1        | 0.47%   |
| QinHeng Electronics             | 1        | 0.47%   |
| Prusa                           | 1        | 0.47%   |
| NetGear                         | 1        | 0.47%   |
| Microsoft                       | 1        | 0.47%   |
| Mellanox Technologies           | 1        | 0.47%   |
| Huawei Technologies             | 1        | 0.47%   |
| D-Link System                   | 1        | 0.47%   |
| Broadcom Limited                | 1        | 0.47%   |
| ASIX Electronics                | 1        | 0.47%   |
| American Megatrends             | 1        | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 47       | 19.11%  |
| Realtek RTL8125 2.5GbE Controller                                             | 37       | 15.04%  |
| Intel Wi-Fi 6 AX200                                                           | 14       | 5.69%   |
| Intel I211 Gigabit Network Connection                                         | 12       | 4.88%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 11       | 4.47%   |
| Intel Ethernet Controller I225-V                                              | 9        | 3.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 8        | 3.25%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 5        | 2.03%   |
| Intel Ethernet Connection (7) I219-V                                          | 5        | 2.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 4        | 1.63%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                             | 3        | 1.22%   |
| Intel I210 Gigabit Network Connection                                         | 3        | 1.22%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 1.22%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 2        | 0.81%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 2        | 0.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 0.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2        | 0.81%   |
| Nvidia MCP61 Ethernet                                                         | 2        | 0.81%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 2        | 0.81%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                 | 2        | 0.81%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 2        | 0.81%   |
| Loongson Ethernet controller                                                  | 2        | 0.81%   |
| Intel Wireless 7265                                                           | 2        | 0.81%   |
| Intel Ethernet Controller I226-V                                              | 2        | 0.81%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 0.81%   |
| Intel Ethernet Connection (14) I219-V                                         | 2        | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2        | 0.81%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 2        | 0.81%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.81%   |
| U-Blox [u-blox 8]                                                             | 1        | 0.41%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 0.41%   |
| TP-Link 802.11ac NIC                                                          | 1        | 0.41%   |
| Realtek USB 10/100/1G/2.5G LAN                                                | 1        | 0.41%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.41%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 0.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 0.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.41%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1        | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.41%   |
| Ralink RT5572 Wireless Adapter                                                | 1        | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 41       | 56.94%  |
| Realtek Semiconductor           | 9        | 12.5%   |
| MediaTek                        | 9        | 12.5%   |
| Qualcomm Atheros                | 4        | 5.56%   |
| TP-Link                         | 2        | 2.78%   |
| Ralink Technology               | 2        | 2.78%   |
| Qualcomm Atheros Communications | 1        | 1.39%   |
| NetGear                         | 1        | 1.39%   |
| Microsoft                       | 1        | 1.39%   |
| Broadcom Limited                | 1        | 1.39%   |
| Broadcom                        | 1        | 1.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                         | 14       | 19.18%  |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                   | 11       | 15.07%  |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                     | 5        | 6.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 4        | 5.48%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                           | 3        | 4.11%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                          | 2        | 2.74%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                 | 2        | 2.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2        | 2.74%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter               | 2        | 2.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter               | 2        | 2.74%   |
| Intel Wireless 7265                                                         | 2        | 2.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 2        | 2.74%   |
| Intel Alder Lake-S PCH CNVi WiFi                                            | 2        | 2.74%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                      | 1        | 1.37%   |
| TP-Link 802.11ac NIC                                                        | 1        | 1.37%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                    | 1        | 1.37%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                             | 1        | 1.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1        | 1.37%   |
| Ralink RT5572 Wireless Adapter                                              | 1        | 1.37%   |
| Ralink MT7601U Wireless Adapter                                             | 1        | 1.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1        | 1.37%   |
| Qualcomm Atheros AR9271 802.11n                                             | 1        | 1.37%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 1        | 1.37%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)              | 1        | 1.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 1        | 1.37%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                         | 1        | 1.37%   |
| Microsoft XBOX ACC                                                          | 1        | 1.37%   |
| Intel Wireless 8265 / 8275                                                  | 1        | 1.37%   |
| Intel Tiger Lake PCH CNVi WiFi                                              | 1        | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                              | 1        | 1.37%   |
| Intel Centrino Ultimate-N 6300                                              | 1        | 1.37%   |
| Broadcom Network controller                                                 | 1        | 1.37%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1        | 1.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 86       | 52.44%  |
| Intel                    | 61       | 37.2%   |
| Qualcomm Atheros         | 3        | 1.83%   |
| Nvidia                   | 3        | 1.83%   |
| Marvell Technology Group | 2        | 1.22%   |
| Loongson Technology      | 2        | 1.22%   |
| Broadcom                 | 2        | 1.22%   |
| Mellanox Technologies    | 1        | 0.61%   |
| Huawei Technologies      | 1        | 0.61%   |
| D-Link System            | 1        | 0.61%   |
| ASIX Electronics         | 1        | 0.61%   |
| American Megatrends      | 1        | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 47       | 27.65%  |
| Realtek RTL8125 2.5GbE Controller                                             | 37       | 21.76%  |
| Intel I211 Gigabit Network Connection                                         | 12       | 7.06%   |
| Intel Ethernet Controller I225-V                                              | 9        | 5.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 8        | 4.71%   |
| Intel Ethernet Connection (7) I219-V                                          | 5        | 2.94%   |
| Intel I210 Gigabit Network Connection                                         | 3        | 1.76%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 1.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2        | 1.18%   |
| Nvidia MCP61 Ethernet                                                         | 2        | 1.18%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 2        | 1.18%   |
| Loongson Ethernet controller                                                  | 2        | 1.18%   |
| Intel Ethernet Controller I226-V                                              | 2        | 1.18%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 1.18%   |
| Intel Ethernet Connection (14) I219-V                                         | 2        | 1.18%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 1.18%   |
| Realtek USB 10/100/1G/2.5G LAN                                                | 1        | 0.59%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.59%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1        | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.59%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 1        | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.59%   |
| Nvidia MCP79 Ethernet                                                         | 1        | 0.59%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 1        | 0.59%   |
| Intel I350 Gigabit Network Connection                                         | 1        | 0.59%   |
| Intel Ethernet Controller X550                                                | 1        | 0.59%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1        | 0.59%   |
| Intel Ethernet Connection I217-V                                              | 1        | 0.59%   |
| Intel Ethernet Connection I217-LM                                             | 1        | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 0.59%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 0.59%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 0.59%   |
| Intel Ethernet Connection (17) I219-V                                         | 1        | 0.59%   |
| Intel Ethernet 10G 2P X520 Adapter                                            | 1        | 0.59%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 0.59%   |
| Intel 82576 Gigabit Network Connection                                        | 1        | 0.59%   |
| Intel 82575EB Gigabit Network Connection                                      | 1        | 0.59%   |
| Intel 82574L Gigabit Network Connection                                       | 1        | 0.59%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                             | 1        | 0.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 141      | 65.58%  |
| WiFi     | 71       | 33.02%  |
| Modem    | 3        | 1.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 108      | 76.06%  |
| WiFi     | 34       | 23.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 63       | 44.06%  |
| 1     | 62       | 43.36%  |
| 3     | 12       | 8.39%   |
| 4     | 3        | 2.1%    |
| 7     | 1        | 0.7%    |
| 5     | 1        | 0.7%    |
| 0     | 1        | 0.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 96       | 66.67%  |
| Yes  | 48       | 33.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 36       | 54.55%  |
| Cambridge Silicon Radio | 10       | 15.15%  |
| MediaTek                | 7        | 10.61%  |
| Realtek Semiconductor   | 5        | 7.58%   |
| IMC Networks            | 2        | 3.03%   |
| Broadcom                | 2        | 3.03%   |
| TP-Link                 | 1        | 1.52%   |
| Lite-On Technology      | 1        | 1.52%   |
| Edimax Technology       | 1        | 1.52%   |
| Actions                 | 1        | 1.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 13       | 19.7%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10       | 15.15%  |
| Intel AX210 Bluetooth                               | 9        | 13.64%  |
| MediaTek Wireless_Device                            | 7        | 10.61%  |
| Intel AX201 Bluetooth                               | 5        | 7.58%   |
| Realtek Bluetooth Radio                             | 4        | 6.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4        | 6.06%   |
| Intel Bluetooth wireless interface                  | 2        | 3.03%   |
| TP-Link UB500 Adapter                               | 1        | 1.52%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 1.52%   |
| Lite-On Bluetooth Device                            | 1        | 1.52%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 1.52%   |
| Intel Bluetooth Device                              | 1        | 1.52%   |
| Intel AX211 Bluetooth                               | 1        | 1.52%   |
| IMC Networks Wireless_Device                        | 1        | 1.52%   |
| IMC Networks Bluetooth Radio                        | 1        | 1.52%   |
| Edimax Edimax Bluetooth Adapter                     | 1        | 1.52%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1        | 1.52%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 1.52%   |
| Actions general adapter                             | 1        | 1.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| AMD                                          | 88       | 31.65%  |
| Intel                                        | 58       | 20.86%  |
| Nvidia                                       | 54       | 19.42%  |
| C-Media Electronics                          | 10       | 3.6%    |
| Micro Star International                     | 5        | 1.8%    |
| ASUSTek Computer                             | 5        | 1.8%    |
| Texas Instruments                            | 4        | 1.44%   |
| SteelSeries ApS                              | 4        | 1.44%   |
| Logitech                                     | 4        | 1.44%   |
| Kingston Technology                          | 4        | 1.44%   |
| Plantronics                                  | 3        | 1.08%   |
| GN Netcom                                    | 3        | 1.08%   |
| Generalplus Technology                       | 3        | 1.08%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.72%   |
| Razer USA                                    | 2        | 0.72%   |
| Mark of the Unicorn                          | 2        | 0.72%   |
| Loongson Technology                          | 2        | 0.72%   |
| JMTek                                        | 2        | 0.72%   |
| Creative Labs                                | 2        | 0.72%   |
| Audient                                      | 2        | 0.72%   |
| Valve Software                               | 1        | 0.36%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.36%   |
| Microsoft                                    | 1        | 0.36%   |
| MAG Technology                               | 1        | 0.36%   |
| M-Audio                                      | 1        | 0.36%   |
| JOUNIVO                                      | 1        | 0.36%   |
| iCreate Technologies                         | 1        | 0.36%   |
| Huawei Technologies                          | 1        | 0.36%   |
| Hewlett-Packard                              | 1        | 0.36%   |
| Focusrite-Novation                           | 1        | 0.36%   |
| FIFINE Microphones                           | 1        | 0.36%   |
| Elgato Systems                               | 1        | 0.36%   |
| Conexant Systems                             | 1        | 0.36%   |
| BY EDIFIER                                   | 1        | 0.36%   |
| Barco Display Systems                        | 1        | 0.36%   |
| Asahi Kasei Microsystems                     | 1        | 0.36%   |
| AKG C44-USB Microphone                       | 1        | 0.36%   |
| AKAI Professional M.I.                       | 1        | 0.36%   |
| Unknown                                      | 1        | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 36       | 10.84%  |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 25       | 7.53%   |
| AMD Family 17h/19h HD Audio Controller                                     | 14       | 4.22%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 14       | 4.22%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 10       | 3.01%   |
| Nvidia GA104 High Definition Audio Controller                              | 9        | 2.71%   |
| Intel Cannon Lake PCH cAVS                                                 | 8        | 2.41%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7        | 2.11%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 7        | 2.11%   |
| Intel Alder Lake-S HD Audio Controller                                     | 6        | 1.81%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6        | 1.81%   |
| Micro Star International USB Audio                                         | 5        | 1.51%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5        | 1.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 1.51%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 1.51%   |
| AMD Navi 10 HDMI Audio                                                     | 5        | 1.51%   |
| Nvidia GA106 High Definition Audio Controller                              | 4        | 1.2%    |
| Nvidia GA102 High Definition Audio Controller                              | 4        | 1.2%    |
| Nvidia Audio device                                                        | 4        | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 1.2%    |
| Intel 200 Series PCH HD Audio                                              | 4        | 1.2%    |
| ASUSTek Computer USB Audio                                                 | 4        | 1.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4        | 1.2%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 1.2%    |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 0.9%    |
| Nvidia High Definition Audio Controller                                    | 3        | 0.9%    |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 0.9%    |
| Intel Raptor Lake High Definition Audio Controller                         | 3        | 0.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 0.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 0.9%    |
| Generalplus Technology USB Audio Device                                    | 3        | 0.9%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 0.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 0.9%    |
| AMD Navi 31 HDMI/DP Audio                                                  | 3        | 0.9%    |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 2        | 0.6%    |
| Texas Instruments PCM2902 Audio Codec                                      | 2        | 0.6%    |
| SteelSeries ApS SteelSeries Arctis 5                                       | 2        | 0.6%    |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.6%    |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.6%    |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| G.Skill                      | 26       | 18.44%  |
| Corsair                      | 25       | 17.73%  |
| Kingston                     | 22       | 15.6%   |
| Crucial                      | 13       | 9.22%   |
| Unknown                      | 11       | 7.8%    |
| SK hynix                     | 8        | 5.67%   |
| Samsung Electronics          | 8        | 5.67%   |
| Micron Technology            | 6        | 4.26%   |
| Team                         | 4        | 2.84%   |
| Patriot                      | 4        | 2.84%   |
| A-DATA Technology            | 4        | 2.84%   |
| Unknown                      | 4        | 2.84%   |
| Unknown (0x0B92)             | 1        | 0.71%   |
| Transcend                    | 1        | 0.71%   |
| Patriot Memory (PDP Systems) | 1        | 0.71%   |
| Mushkin                      | 1        | 0.71%   |
| Kllisre                      | 1        | 0.71%   |
| Foxline                      | 1        | 0.71%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown                                                | 4        | 2.52%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s    | 3        | 1.89%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s   | 3        | 1.89%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 3        | 1.89%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s               | 2        | 1.26%   |
| Kingston RAM KF556C36-32 32GB DIMM DDR5 5600MT/s       | 2        | 1.26%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 1.26%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s   | 2        | 1.26%   |
| G.Skill RAM F4-3600C18-32GVK 32GB DIMM DDR4 3600MT/s   | 2        | 1.26%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3866MT/s | 2        | 1.26%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 2        | 1.26%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s     | 2        | 1.26%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s | 2        | 1.26%   |
| Corsair RAM CMK16GX4M2Z3200C16 8GB DIMM DDR4 3200MT/s  | 2        | 1.26%   |
| Unknown RAM Module 8GB DIMM 400MT/s                    | 1        | 0.63%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                   | 1        | 0.63%   |
| Unknown RAM Module 4GB DIMM 400MT/s                    | 1        | 0.63%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                   | 1        | 0.63%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s             | 1        | 0.63%   |
| Unknown RAM Module 2GB SODIMM DDR2                     | 1        | 0.63%   |
| Unknown RAM Module 16GB DIMM DDR4 2400MT/s             | 1        | 0.63%   |
| Unknown RAM 991527 (996527) 1024MB DIMM SDRAM 2048MT/s | 1        | 0.63%   |
| Unknown RAM 3200 C18 Series 16384MB DIMM DDR4 2400MT/s | 1        | 0.63%   |
| Unknown RAM 1866 CL10 Series 8192MB DIMM DDR3 933MT/s  | 1        | 0.63%   |
| Unknown (0x0B92) RAM Module 8GB DIMM DDR4 3400MT/s     | 1        | 0.63%   |
| Transcend RAM JM2666HLE-16G 16GB DIMM DDR4 2666MT/s    | 1        | 0.63%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s    | 1        | 0.63%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s  | 1        | 0.63%   |
| SK hynix RAM HMT451U7BFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.63%   |
| SK hynix RAM HMT41GU7BFR8C-PB 8GB DIMM DDR3 1600MT/s   | 1        | 0.63%   |
| SK hynix RAM HMT41GU7AFR8C-RD 8GB DIMM DDR3 1866MT/s   | 1        | 0.63%   |
| SK hynix RAM HMT351U6EFR8A-PB 8GB DIMM DDR3 1600MT/s   | 1        | 0.63%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s   | 1        | 0.63%   |
| SK hynix RAM HMAG68EXNUA076N 8GB DIMM DDR4 3200MT/s    | 1        | 0.63%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s | 1        | 0.63%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB DIMM DDR4 2133MT/s   | 1        | 0.63%   |
| SK hynix RAM HMA42GR7AFR4N-UH 16GB DIMM DDR4 2400MT/s  | 1        | 0.63%   |
| SK hynix RAM HMA41GR7MFR4N-TF 8GB DIMM DDR4 2667MT/s   | 1        | 0.63%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR5 6400MT/s    | 1        | 0.63%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s | 1        | 0.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 84       | 65.12%  |
| DDR3    | 19       | 14.73%  |
| DDR5    | 16       | 12.4%   |
| DDR2    | 5        | 3.88%   |
| Unknown | 3        | 2.33%   |
| SDRAM   | 1        | 0.78%   |
| LPDDR5  | 1        | 0.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 121      | 93.8%   |
| SODIMM       | 7        | 5.43%   |
| Row Of Chips | 1        | 0.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 45       | 32.14%  |
| 8192  | 45       | 32.14%  |
| 32768 | 27       | 19.29%  |
| 4096  | 14       | 10%     |
| 2048  | 7        | 5%      |
| 1024  | 2        | 1.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 27       | 18%     |
| 3600    | 17       | 11.33%  |
| 1600    | 14       | 9.33%   |
| 2667    | 10       | 6.67%   |
| 2133    | 9        | 6%      |
| 3733    | 6        | 4%      |
| 2400    | 6        | 4%      |
| 4800    | 5        | 3.33%   |
| 1866    | 5        | 3.33%   |
| 6400    | 4        | 2.67%   |
| 5600    | 4        | 2.67%   |
| 3866    | 4        | 2.67%   |
| 6000    | 3        | 2%      |
| 667     | 3        | 2%      |
| 4000    | 2        | 1.33%   |
| 3800    | 2        | 1.33%   |
| 3666    | 2        | 1.33%   |
| 3534    | 2        | 1.33%   |
| 3400    | 2        | 1.33%   |
| 3000    | 2        | 1.33%   |
| 2666    | 2        | 1.33%   |
| 1333    | 2        | 1.33%   |
| 800     | 2        | 1.33%   |
| 49926   | 1        | 0.67%   |
| 5200    | 1        | 0.67%   |
| 3500    | 1        | 0.67%   |
| 3466    | 1        | 0.67%   |
| 3333    | 1        | 0.67%   |
| 3066    | 1        | 0.67%   |
| 3007    | 1        | 0.67%   |
| 2933    | 1        | 0.67%   |
| 2800    | 1        | 0.67%   |
| 2134    | 1        | 0.67%   |
| 2048    | 1        | 0.67%   |
| 1800    | 1        | 0.67%   |
| 1066    | 1        | 0.67%   |
| 400     | 1        | 0.67%   |
| Unknown | 1        | 0.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 3        | 33.33%  |
| Brother Industries  | 3        | 33.33%  |
| Prolific Technology | 1        | 11.11%  |
| NXP Semiconductors  | 1        | 11.11%  |
| Canon               | 1        | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| HP HP LaserJet M14-M17        | 2        | 22.22%  |
| Prolific PL2305 Parallel Port | 1        | 11.11%  |
| NXP Semiconductors Printer-80 | 1        | 11.11%  |
| HP Deskjet 9800               | 1        | 11.11%  |
| Canon PIXMA MG2900 Series     | 1        | 11.11%  |
| Brother QL-500 label printer  | 1        | 11.11%  |
| Brother MFC-9340CDW           | 1        | 11.11%  |
| Brother HL-L2370DW series     | 1        | 11.11%  |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 15       | 40.54%  |
| Microdia                      | 4        | 10.81%  |
| Samsung Electronics           | 2        | 5.41%   |
| Realtek Semiconductor         | 2        | 5.41%   |
| Chicony Electronics           | 2        | 5.41%   |
| Zhejiang Dahua Technology     | 1        | 2.7%    |
| Valve Software                | 1        | 2.7%    |
| Sunplus Innovation Technology | 1        | 2.7%    |
| Microsoft                     | 1        | 2.7%    |
| Google                        | 1        | 2.7%    |
| Generalplus Technology        | 1        | 2.7%    |
| Elgato Systems                | 1        | 2.7%    |
| Creative Technology           | 1        | 2.7%    |
| BTF-230906-J                  | 1        | 2.7%    |
| Arkmicro Technologies         | 1        | 2.7%    |
| ARC International             | 1        | 2.7%    |
| A4Tech                        | 1        | 2.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech Webcam C270                      | 6        | 15.79%  |
| Logitech C922 Pro Stream Webcam           | 3        | 7.89%   |
| Samsung Galaxy series, misc. (MTP mode)   | 2        | 5.26%   |
| Microdia Webcam Vitade AF                 | 2        | 5.26%   |
| Logitech HD Pro Webcam C920               | 2        | 5.26%   |
| Chicony HP 720p HD Monitor Webcam         | 2        | 5.26%   |
| Zhejiang Dahua HTI-UC325                  | 1        | 2.63%   |
| Valve Software 3D Camera                  | 1        | 2.63%   |
| Sunplus USB 2.0 Camera                    | 1        | 2.63%   |
| Realtek Integrated_Webcam_FHD             | 1        | 2.63%   |
| Realtek FULL HD 1080P Webcam              | 1        | 2.63%   |
| Microsoft LifeCam Cinema                  | 1        | 2.63%   |
| Microdia USB 2.0 Camera                   | 1        | 2.63%   |
| Microdia Camera                           | 1        | 2.63%   |
| Logitech Webcam C310                      | 1        | 2.63%   |
| Logitech QuickCam Orbit/Sphere AF         | 1        | 2.63%   |
| Logitech Logitech Webcam C100             | 1        | 2.63%   |
| Logitech HD Webcam C525                   | 1        | 2.63%   |
| Logitech BRIO 4K Stream Edition           | 1        | 2.63%   |
| Google HD USB Camera                      | 1        | 2.63%   |
| Generalplus WEB CAM                       | 1        | 2.63%   |
| Elgato Systems Game Capture HD60 X        | 1        | 2.63%   |
| Creative VF0690 Live! Cam Socialize HD AF | 1        | 2.63%   |
| BTF-230906-J Hy-UXGA(B5M2)-Camera         | 1        | 2.63%   |
| Arkmicro USB2.0 PC CAMERA                 | 1        | 2.63%   |
| ARC International Camera                  | 1        | 2.63%   |
| A4Tech REDRAGON Live Camera               | 1        | 2.63%   |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Clay Logic            | 2        | 50%     |
| Gemalto (was Gemplus) | 1        | 25%     |
| Alcor Micro           | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Clay Logic Nitrokey Pro                 | 2        | 50%     |
| Gemalto (was Gemplus) eToken 5110+ FIPS | 1        | 25%     |
| Alcor Micro AU9540 Smartcard Reader     | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 82       | 55.03%  |
| 1     | 35       | 23.49%  |
| 2     | 17       | 11.41%  |
| 3     | 12       | 8.05%   |
| 4     | 2        | 1.34%   |
| 5     | 1        | 0.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 27       | 25.71%  |
| Graphics card            | 26       | 24.76%  |
| Bluetooth                | 11       | 10.48%  |
| Net/wireless             | 10       | 9.52%   |
| Sound                    | 6        | 5.71%   |
| Net/ethernet             | 5        | 4.76%   |
| Unassigned class         | 4        | 3.81%   |
| Storage/ide              | 4        | 3.81%   |
| Network                  | 2        | 1.9%    |
| Multimedia controller    | 2        | 1.9%    |
| Firewire controller      | 2        | 1.9%    |
| Chipcard                 | 2        | 1.9%    |
| Storage/raid             | 1        | 0.95%   |
| Storage/nvme             | 1        | 0.95%   |
| Storage/ata              | 1        | 0.95%   |
| Camera                   | 1        | 0.95%   |

