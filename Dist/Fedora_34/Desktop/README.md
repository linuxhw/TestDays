Fedora 34 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Fedora 34 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=fedora-34

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | GA-990FXA-D3                | [37c4ed4ed7](https://linux-hardware.org/?probe=37c4ed4ed7) | Sep 01, 2021 |
| Gigabyte      | B550M DS3H                  | [20389db1bd](https://linux-hardware.org/?probe=20389db1bd) | Aug 31, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [3ccd4032a1](https://linux-hardware.org/?probe=3ccd4032a1) | Aug 31, 2021 |
| HP            | 2AF7                        | [38b5cbf28d](https://linux-hardware.org/?probe=38b5cbf28d) | Aug 31, 2021 |
| ASRock        | H97M Pro4                   | [96d9d18052](https://linux-hardware.org/?probe=96d9d18052) | Aug 31, 2021 |
| ASRock        | H97M Pro4                   | [fb5e0539da](https://linux-hardware.org/?probe=fb5e0539da) | Aug 31, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [e014d83782](https://linux-hardware.org/?probe=e014d83782) | Aug 31, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [0cdd08839f](https://linux-hardware.org/?probe=0cdd08839f) | Aug 31, 2021 |
| ASUSTek       | P5Q-E                       | [997ce785b2](https://linux-hardware.org/?probe=997ce785b2) | Aug 31, 2021 |
| Gigabyte      | B150M-D3H-CF                | [6f0e81a6d9](https://linux-hardware.org/?probe=6f0e81a6d9) | Aug 31, 2021 |
| Gigabyte      | F2A68HM-S1                  | [dcc0bda879](https://linux-hardware.org/?probe=dcc0bda879) | Aug 30, 2021 |
| Gigabyte      | 970A-DS3P                   | [9a3be042e0](https://linux-hardware.org/?probe=9a3be042e0) | Aug 30, 2021 |
| HP            | 8056                        | [8614fae216](https://linux-hardware.org/?probe=8614fae216) | Aug 30, 2021 |
| HP            | 198E                        | [82d1a8a5a7](https://linux-hardware.org/?probe=82d1a8a5a7) | Aug 29, 2021 |
| Gigabyte      | 970A-DS3P                   | [e539faacf5](https://linux-hardware.org/?probe=e539faacf5) | Aug 29, 2021 |
| Gigabyte      | Z77MX-D3H                   | [d2b4c85e96](https://linux-hardware.org/?probe=d2b4c85e96) | Aug 29, 2021 |
| MSI           | MEG X570 UNIFY              | [cf5f33a843](https://linux-hardware.org/?probe=cf5f33a843) | Aug 28, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [5fd92a80fa](https://linux-hardware.org/?probe=5fd92a80fa) | Aug 28, 2021 |
| Lenovo        | Board                       | [ec9c58b54e](https://linux-hardware.org/?probe=ec9c58b54e) | Aug 28, 2021 |
| Gigabyte      | B450M DS3H-CF               | [4331eedde2](https://linux-hardware.org/?probe=4331eedde2) | Aug 28, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [614ac09d36](https://linux-hardware.org/?probe=614ac09d36) | Aug 28, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [3c31559d95](https://linux-hardware.org/?probe=3c31559d95) | Aug 28, 2021 |
| MSI           | X570-A PRO                  | [830bfb129f](https://linux-hardware.org/?probe=830bfb129f) | Aug 27, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | [f6049274c5](https://linux-hardware.org/?probe=f6049274c5) | Aug 27, 2021 |
| MSI           | X570-A PRO                  | [934d0576e0](https://linux-hardware.org/?probe=934d0576e0) | Aug 27, 2021 |
| MSI           | A320M-A PRO M2              | [fda90307d4](https://linux-hardware.org/?probe=fda90307d4) | Aug 27, 2021 |
| ASUSTek       | P6T                         | [ad049817af](https://linux-hardware.org/?probe=ad049817af) | Aug 27, 2021 |
| HP            | 8056                        | [e64dab1375](https://linux-hardware.org/?probe=e64dab1375) | Aug 27, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | [a0ed3c6558](https://linux-hardware.org/?probe=a0ed3c6558) | Aug 27, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [adde1df1d0](https://linux-hardware.org/?probe=adde1df1d0) | Aug 27, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [63104dc43a](https://linux-hardware.org/?probe=63104dc43a) | Aug 26, 2021 |
| ASUSTek       | PRIME Z390-A                | [6e2699cc9e](https://linux-hardware.org/?probe=6e2699cc9e) | Aug 26, 2021 |
| Gigabyte      | B85M-D3V-A                  | [89dcb140f5](https://linux-hardware.org/?probe=89dcb140f5) | Aug 26, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d97a42e31e](https://linux-hardware.org/?probe=d97a42e31e) | Aug 26, 2021 |
| Gigabyte      | Z87X-D3H-CF                 | [b40ad47903](https://linux-hardware.org/?probe=b40ad47903) | Aug 25, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [3e39cc51a8](https://linux-hardware.org/?probe=3e39cc51a8) | Aug 25, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [74a9538d04](https://linux-hardware.org/?probe=74a9538d04) | Aug 25, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [11d9254c35](https://linux-hardware.org/?probe=11d9254c35) | Aug 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [778e5aa3ae](https://linux-hardware.org/?probe=778e5aa3ae) | Aug 25, 2021 |
| ASRock        | FM2A55M-VG3+                | [c2e1837665](https://linux-hardware.org/?probe=c2e1837665) | Aug 24, 2021 |
| Dell          | 0HH807                      | [fe3659d065](https://linux-hardware.org/?probe=fe3659d065) | Aug 24, 2021 |
| ASRock        | 980DE3/U3S3                 | [e8aadc0af0](https://linux-hardware.org/?probe=e8aadc0af0) | Aug 24, 2021 |
| Biostar       | A68I-450 DELUXE             | [3e0a375af7](https://linux-hardware.org/?probe=3e0a375af7) | Aug 23, 2021 |
| ASUSTek       | PRIME A320M-K               | [847e7f4c1a](https://linux-hardware.org/?probe=847e7f4c1a) | Aug 23, 2021 |
| MSI           | E3M WORKSTATION V5          | [fa6adf65a6](https://linux-hardware.org/?probe=fa6adf65a6) | Aug 23, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [014af10464](https://linux-hardware.org/?probe=014af10464) | Aug 23, 2021 |
| HP            | 8056                        | [d604c95726](https://linux-hardware.org/?probe=d604c95726) | Aug 23, 2021 |
| Dell          | 0F3KHR A01                  | [b5bc473971](https://linux-hardware.org/?probe=b5bc473971) | Aug 23, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [07d9074437](https://linux-hardware.org/?probe=07d9074437) | Aug 23, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [7928c7e6e6](https://linux-hardware.org/?probe=7928c7e6e6) | Aug 23, 2021 |
| ASRock        | H170M Pro4                  | [0cd9bde7b4](https://linux-hardware.org/?probe=0cd9bde7b4) | Aug 23, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [f983e2baca](https://linux-hardware.org/?probe=f983e2baca) | Aug 22, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [b2190e55e8](https://linux-hardware.org/?probe=b2190e55e8) | Aug 22, 2021 |
| ASUSTek       | Z77-A                       | [971dc3b5c7](https://linux-hardware.org/?probe=971dc3b5c7) | Aug 21, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [edc2f605d1](https://linux-hardware.org/?probe=edc2f605d1) | Aug 21, 2021 |
| MSI           | X370 SLI PLUS               | [4a611b712a](https://linux-hardware.org/?probe=4a611b712a) | Aug 21, 2021 |
| HP            | 2AF7                        | [beb4167201](https://linux-hardware.org/?probe=beb4167201) | Aug 21, 2021 |
| ASUSTek       | AM1M-A                      | [433d420dd4](https://linux-hardware.org/?probe=433d420dd4) | Aug 20, 2021 |
| ASUSTek       | P6T                         | [d0495a4765](https://linux-hardware.org/?probe=d0495a4765) | Aug 20, 2021 |
| ASRock        | AD2700-ITX                  | [1d1d8a4620](https://linux-hardware.org/?probe=1d1d8a4620) | Aug 20, 2021 |
| ASRock        | B450 Steel Legend           | [8fdfffdbac](https://linux-hardware.org/?probe=8fdfffdbac) | Aug 20, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [4b37f6047e](https://linux-hardware.org/?probe=4b37f6047e) | Aug 20, 2021 |
| Gigabyte      | Z77MX-D3H                   | [e49dbd40b5](https://linux-hardware.org/?probe=e49dbd40b5) | Aug 20, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [41874518ea](https://linux-hardware.org/?probe=41874518ea) | Aug 20, 2021 |
| Gigabyte      | GA-990FXA-D3                | [78feb5ae08](https://linux-hardware.org/?probe=78feb5ae08) | Aug 20, 2021 |
| BESSTAR Te... | HM80                        | [60fdee03d6](https://linux-hardware.org/?probe=60fdee03d6) | Aug 19, 2021 |
| HP            | 83E9                        | [21b492b0bf](https://linux-hardware.org/?probe=21b492b0bf) | Aug 19, 2021 |
| HP            | 83E9                        | [7cb2c3256a](https://linux-hardware.org/?probe=7cb2c3256a) | Aug 19, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [3eb5c512ad](https://linux-hardware.org/?probe=3eb5c512ad) | Aug 19, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [84153c2a8d](https://linux-hardware.org/?probe=84153c2a8d) | Aug 19, 2021 |
| Gigabyte      | B150M-D3H-CF                | [2aed19ac0a](https://linux-hardware.org/?probe=2aed19ac0a) | Aug 19, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [5c3e90c735](https://linux-hardware.org/?probe=5c3e90c735) | Aug 19, 2021 |
| Gigabyte      | P55-USB3                    | [5e6a1d1926](https://linux-hardware.org/?probe=5e6a1d1926) | Aug 19, 2021 |
| HP            | 8056                        | [44b754f972](https://linux-hardware.org/?probe=44b754f972) | Aug 19, 2021 |
| ASUSTek       | AM1M-A                      | [c0653de55c](https://linux-hardware.org/?probe=c0653de55c) | Aug 18, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [6eaf105bca](https://linux-hardware.org/?probe=6eaf105bca) | Aug 18, 2021 |
| HP            | 2AF7                        | [909c6f5c0a](https://linux-hardware.org/?probe=909c6f5c0a) | Aug 18, 2021 |
| ASRock        | X399 Taichi                 | [efead486a3](https://linux-hardware.org/?probe=efead486a3) | Aug 18, 2021 |
| HP            | 82F2 A01                    | [b6847d9605](https://linux-hardware.org/?probe=b6847d9605) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [33bfc09a3a](https://linux-hardware.org/?probe=33bfc09a3a) | Aug 17, 2021 |
| ASRock        | B460M-ITX/ac                | [2eb3e6f3f6](https://linux-hardware.org/?probe=2eb3e6f3f6) | Aug 17, 2021 |
| Gigabyte      | G41MT-S2P                   | [63a8a28fd9](https://linux-hardware.org/?probe=63a8a28fd9) | Aug 17, 2021 |
| HP            | 8056                        | [5607e09042](https://linux-hardware.org/?probe=5607e09042) | Aug 17, 2021 |
| Dell          | 0Y2YM6 A00                  | [4d3d87b641](https://linux-hardware.org/?probe=4d3d87b641) | Aug 17, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [78a3158393](https://linux-hardware.org/?probe=78a3158393) | Aug 16, 2021 |
| MSI           | MPG Z390I GAMING EDGE AC    | [391c21db23](https://linux-hardware.org/?probe=391c21db23) | Aug 16, 2021 |
| HP            | 198E                        | [d1c56bffb1](https://linux-hardware.org/?probe=d1c56bffb1) | Aug 15, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [86f9693894](https://linux-hardware.org/?probe=86f9693894) | Aug 15, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [419995b0da](https://linux-hardware.org/?probe=419995b0da) | Aug 15, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [f931b86af5](https://linux-hardware.org/?probe=f931b86af5) | Aug 15, 2021 |
| Lenovo        | Board                       | [cd8825c8d0](https://linux-hardware.org/?probe=cd8825c8d0) | Aug 15, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [d34022df3b](https://linux-hardware.org/?probe=d34022df3b) | Aug 15, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9bf7d4afd7](https://linux-hardware.org/?probe=9bf7d4afd7) | Aug 14, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [5f49d58f42](https://linux-hardware.org/?probe=5f49d58f42) | Aug 14, 2021 |
| Dell          | 0NKW6Y A00                  | [7d0c7834be](https://linux-hardware.org/?probe=7d0c7834be) | Aug 14, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [05bfca3339](https://linux-hardware.org/?probe=05bfca3339) | Aug 13, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [32bc94c4e2](https://linux-hardware.org/?probe=32bc94c4e2) | Aug 13, 2021 |
| Intel         | B75                         | [2bac7a8140](https://linux-hardware.org/?probe=2bac7a8140) | Aug 13, 2021 |
| Gigabyte      | Z390 D                      | [8bfd432fba](https://linux-hardware.org/?probe=8bfd432fba) | Aug 13, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [5e9853124d](https://linux-hardware.org/?probe=5e9853124d) | Aug 13, 2021 |
| Gigabyte      | Z77MX-D3H                   | [13558f63ab](https://linux-hardware.org/?probe=13558f63ab) | Aug 13, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [0b46a87be6](https://linux-hardware.org/?probe=0b46a87be6) | Aug 13, 2021 |
| Dell          | 03NVJ6 A01                  | [ef0028e285](https://linux-hardware.org/?probe=ef0028e285) | Aug 12, 2021 |
| MSI           | X570-A PRO                  | [8cc7d05010](https://linux-hardware.org/?probe=8cc7d05010) | Aug 12, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [3ed6340d82](https://linux-hardware.org/?probe=3ed6340d82) | Aug 12, 2021 |
| ASRock        | FM2A88X-ITX+                | [5f70360eea](https://linux-hardware.org/?probe=5f70360eea) | Aug 12, 2021 |
| ASRock        | FM2A88X-ITX+                | [aeec0ec477](https://linux-hardware.org/?probe=aeec0ec477) | Aug 12, 2021 |
| Acer          | Aspire TC-705               | [bbf5c161d3](https://linux-hardware.org/?probe=bbf5c161d3) | Aug 12, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [3fd838012c](https://linux-hardware.org/?probe=3fd838012c) | Aug 12, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [f1eabffafd](https://linux-hardware.org/?probe=f1eabffafd) | Aug 12, 2021 |
| HP            | 8056                        | [afe5072bf8](https://linux-hardware.org/?probe=afe5072bf8) | Aug 12, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [6808748401](https://linux-hardware.org/?probe=6808748401) | Aug 10, 2021 |
| Dell          | 0KWVT8 A02                  | [d8e685c049](https://linux-hardware.org/?probe=d8e685c049) | Aug 10, 2021 |
| MSI           | B75MA-E33                   | [8a1743cb75](https://linux-hardware.org/?probe=8a1743cb75) | Aug 10, 2021 |
| Gigabyte      | Z270-HD3P-CF                | [8ad0df4157](https://linux-hardware.org/?probe=8ad0df4157) | Aug 09, 2021 |
| ASRock        | AD2700-ITX                  | [fac88c2a70](https://linux-hardware.org/?probe=fac88c2a70) | Aug 09, 2021 |
| Biostar       | X370GTN                     | [eeff407867](https://linux-hardware.org/?probe=eeff407867) | Aug 08, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | [ec3a3d05e5](https://linux-hardware.org/?probe=ec3a3d05e5) | Aug 08, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | [795328301d](https://linux-hardware.org/?probe=795328301d) | Aug 08, 2021 |
| Gigabyte      | GA-990FXA-D3                | [a81ec533a8](https://linux-hardware.org/?probe=a81ec533a8) | Aug 08, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [1a68be3ffe](https://linux-hardware.org/?probe=1a68be3ffe) | Aug 08, 2021 |
| Gigabyte      | Z77MX-D3H                   | [feacdb6873](https://linux-hardware.org/?probe=feacdb6873) | Aug 08, 2021 |
| HP            | 1998                        | [38acf34efb](https://linux-hardware.org/?probe=38acf34efb) | Aug 08, 2021 |
| MSI           | MAG B560 TORPEDO            | [8e1e7782d9](https://linux-hardware.org/?probe=8e1e7782d9) | Aug 08, 2021 |
| MSI           | MAG B460M MORTAR WIFI       | [f51ff5d22f](https://linux-hardware.org/?probe=f51ff5d22f) | Aug 07, 2021 |
| MSI           | MAG B560 TORPEDO            | [4d2a5f5d27](https://linux-hardware.org/?probe=4d2a5f5d27) | Aug 07, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [2f7d7bbb1d](https://linux-hardware.org/?probe=2f7d7bbb1d) | Aug 06, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [6e05bc86aa](https://linux-hardware.org/?probe=6e05bc86aa) | Aug 06, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [4c87b2ff27](https://linux-hardware.org/?probe=4c87b2ff27) | Aug 06, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f74df24802](https://linux-hardware.org/?probe=f74df24802) | Aug 05, 2021 |
| ASUSTek       | Z170I PRO GAMING            | [2fbf46c559](https://linux-hardware.org/?probe=2fbf46c559) | Aug 05, 2021 |
| MSI           | B450-A PRO MAX              | [a096b9bb71](https://linux-hardware.org/?probe=a096b9bb71) | Aug 05, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [2c843a3d35](https://linux-hardware.org/?probe=2c843a3d35) | Aug 04, 2021 |
| Gigabyte      | EP45-DS3L                   | [dfb3b0302c](https://linux-hardware.org/?probe=dfb3b0302c) | Aug 04, 2021 |
| ASRockRack    | X470D4U                     | [b3ae79f78f](https://linux-hardware.org/?probe=b3ae79f78f) | Aug 04, 2021 |
| ASRockRack    | X470D4U                     | [a124194272](https://linux-hardware.org/?probe=a124194272) | Aug 04, 2021 |
| ASUSTek       | PRIME X370-PRO              | [dce96ae07e](https://linux-hardware.org/?probe=dce96ae07e) | Aug 04, 2021 |
| ASUSTek       | PRIME X370-PRO              | [345ce8fb64](https://linux-hardware.org/?probe=345ce8fb64) | Aug 04, 2021 |
| HP            | 82F2 A01                    | [b6b124c434](https://linux-hardware.org/?probe=b6b124c434) | Aug 03, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [f776a4eb93](https://linux-hardware.org/?probe=f776a4eb93) | Aug 03, 2021 |
| Gigabyte      | GA-990FXA-D3                | [ad5bc52a88](https://linux-hardware.org/?probe=ad5bc52a88) | Aug 03, 2021 |
| ASUSTek       | PRIME X470-PRO              | [39919aab55](https://linux-hardware.org/?probe=39919aab55) | Aug 02, 2021 |
| ASRock        | B450 Pro4                   | [47a05531da](https://linux-hardware.org/?probe=47a05531da) | Aug 02, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [454fecb7fb](https://linux-hardware.org/?probe=454fecb7fb) | Aug 01, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [c18e0a53fc](https://linux-hardware.org/?probe=c18e0a53fc) | Aug 01, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | [052a6762c4](https://linux-hardware.org/?probe=052a6762c4) | Jul 31, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | [2b00e34271](https://linux-hardware.org/?probe=2b00e34271) | Jul 31, 2021 |
| Lenovo        | MAHOBAY NOK                 | [921bde522e](https://linux-hardware.org/?probe=921bde522e) | Jul 31, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [b5a0d25d72](https://linux-hardware.org/?probe=b5a0d25d72) | Jul 30, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [e842eefc11](https://linux-hardware.org/?probe=e842eefc11) | Jul 29, 2021 |
| Gigabyte      | F2A78M-HD2                  | [ae31c59ee8](https://linux-hardware.org/?probe=ae31c59ee8) | Jul 29, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [20e3d5c8af](https://linux-hardware.org/?probe=20e3d5c8af) | Jul 29, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [21bcfb6822](https://linux-hardware.org/?probe=21bcfb6822) | Jul 29, 2021 |
| ASUSTek       | PRIME Z390-A                | [c6239b2672](https://linux-hardware.org/?probe=c6239b2672) | Jul 28, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [88d668c3ab](https://linux-hardware.org/?probe=88d668c3ab) | Jul 27, 2021 |
| ASUSTek       | M5A97 R2.0                  | [fe0953d7db](https://linux-hardware.org/?probe=fe0953d7db) | Jul 27, 2021 |
| ASRock        | X399 Professional Gaming    | [5e769c8137](https://linux-hardware.org/?probe=5e769c8137) | Jul 26, 2021 |
| Gigabyte      | H61N-USB3                   | [25961dfa1f](https://linux-hardware.org/?probe=25961dfa1f) | Jul 26, 2021 |
| Gigabyte      | Q87M-D2H                    | [4f26f93184](https://linux-hardware.org/?probe=4f26f93184) | Jul 26, 2021 |
| Gigabyte      | H97M-DS3P                   | [c5f1df2581](https://linux-hardware.org/?probe=c5f1df2581) | Jul 26, 2021 |
| HP            | 2AF7                        | [a24b46f292](https://linux-hardware.org/?probe=a24b46f292) | Jul 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [925ddff018](https://linux-hardware.org/?probe=925ddff018) | Jul 25, 2021 |
| Gigabyte      | GA-990FXA-D3                | [f2c2beb7da](https://linux-hardware.org/?probe=f2c2beb7da) | Jul 24, 2021 |
| Lenovo        | MAHOBAY NOK                 | [00614fd705](https://linux-hardware.org/?probe=00614fd705) | Jul 23, 2021 |
| Unknown       | Unknown                     | [0bf537187a](https://linux-hardware.org/?probe=0bf537187a) | Jul 23, 2021 |
| Lenovo        | MAHOBAY NOK                 | [37924533d9](https://linux-hardware.org/?probe=37924533d9) | Jul 23, 2021 |
| Unknown       | Unknown                     | [8681aef84a](https://linux-hardware.org/?probe=8681aef84a) | Jul 23, 2021 |
| Acer          | WG43M                       | [9efd66b779](https://linux-hardware.org/?probe=9efd66b779) | Jul 22, 2021 |
| Dell          | 0W0CHX A01                  | [d4f3e21abc](https://linux-hardware.org/?probe=d4f3e21abc) | Jul 22, 2021 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | [0b87f80aa9](https://linux-hardware.org/?probe=0b87f80aa9) | Jul 22, 2021 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | [114ecaea11](https://linux-hardware.org/?probe=114ecaea11) | Jul 22, 2021 |
| Gigabyte      | GA-990FXA-D3                | [831024faec](https://linux-hardware.org/?probe=831024faec) | Jul 22, 2021 |
| Intel         | H81                         | [166b35fa7f](https://linux-hardware.org/?probe=166b35fa7f) | Jul 21, 2021 |
| ASRock        | 980DE3/U3S3                 | [437aef57fd](https://linux-hardware.org/?probe=437aef57fd) | Jul 21, 2021 |
| ASRock        | 980DE3/U3S3                 | [9ca97016e0](https://linux-hardware.org/?probe=9ca97016e0) | Jul 21, 2021 |
| Gigabyte      | G41M-Combo                  | [785c30284d](https://linux-hardware.org/?probe=785c30284d) | Jul 21, 2021 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | [4dd5b903b6](https://linux-hardware.org/?probe=4dd5b903b6) | Jul 21, 2021 |
| HP            | 83E1                        | [977631dbb5](https://linux-hardware.org/?probe=977631dbb5) | Jul 20, 2021 |
| ASUSTek       | CM1740                      | [bddfad8365](https://linux-hardware.org/?probe=bddfad8365) | Jul 20, 2021 |
| ASUSTek       | CM1740                      | [2dcaee58ab](https://linux-hardware.org/?probe=2dcaee58ab) | Jul 20, 2021 |
| Gigabyte      | B450 AORUS M                | [ebed27d481](https://linux-hardware.org/?probe=ebed27d481) | Jul 20, 2021 |
| Gigabyte      | H61N-USB3                   | [54677110b4](https://linux-hardware.org/?probe=54677110b4) | Jul 20, 2021 |
| ASUSTek       | P8B75-M                     | [ce3ef21b15](https://linux-hardware.org/?probe=ce3ef21b15) | Jul 19, 2021 |
| ASUSTek       | P8B75-M                     | [70e6e81263](https://linux-hardware.org/?probe=70e6e81263) | Jul 19, 2021 |
| Gigabyte      | EP45-DS3L                   | [3e9218d801](https://linux-hardware.org/?probe=3e9218d801) | Jul 19, 2021 |
| ASUSTek       | P5LD2                       | [9e97498649](https://linux-hardware.org/?probe=9e97498649) | Jul 19, 2021 |
| MSI           | Z390-A PRO                  | [811ff5b5d4](https://linux-hardware.org/?probe=811ff5b5d4) | Jul 19, 2021 |
| Gigabyte      | G41M-Combo                  | [5f182f7f80](https://linux-hardware.org/?probe=5f182f7f80) | Jul 18, 2021 |
| HP            | 3646h                       | [b4dd06e5ce](https://linux-hardware.org/?probe=b4dd06e5ce) | Jul 18, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [d51165f3df](https://linux-hardware.org/?probe=d51165f3df) | Jul 17, 2021 |
| Gigabyte      | M61PME-S2P                  | [02dc77286f](https://linux-hardware.org/?probe=02dc77286f) | Jul 17, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [6f6f7c6f5b](https://linux-hardware.org/?probe=6f6f7c6f5b) | Jul 16, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [02c451c80b](https://linux-hardware.org/?probe=02c451c80b) | Jul 16, 2021 |
| Biostar       | X370GTN                     | [22114c765e](https://linux-hardware.org/?probe=22114c765e) | Jul 16, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [15a186d484](https://linux-hardware.org/?probe=15a186d484) | Jul 16, 2021 |
| Gigabyte      | B560M AORUS PRO AX          | [38067d7d6d](https://linux-hardware.org/?probe=38067d7d6d) | Jul 15, 2021 |
| HP            | 8056                        | [bff5c3bb8d](https://linux-hardware.org/?probe=bff5c3bb8d) | Jul 15, 2021 |
| ASRock        | 990FX Extreme3              | [0621ec449f](https://linux-hardware.org/?probe=0621ec449f) | Jul 15, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [24a13881c1](https://linux-hardware.org/?probe=24a13881c1) | Jul 14, 2021 |
| ASRock        | A320M-HDV R4.0              | [663c98e1f6](https://linux-hardware.org/?probe=663c98e1f6) | Jul 13, 2021 |
| HP            | 872B                        | [319ce0e306](https://linux-hardware.org/?probe=319ce0e306) | Jul 13, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [c7fad2195c](https://linux-hardware.org/?probe=c7fad2195c) | Jul 13, 2021 |
| ASRock        | A320M-HD                    | [d3700506ef](https://linux-hardware.org/?probe=d3700506ef) | Jul 13, 2021 |
| SYWZ          | S200 Series                 | [842ae5d4a3](https://linux-hardware.org/?probe=842ae5d4a3) | Jul 12, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [6f04de798d](https://linux-hardware.org/?probe=6f04de798d) | Jul 12, 2021 |
| Dell          | 0C2KJT A00                  | [891d514a94](https://linux-hardware.org/?probe=891d514a94) | Jul 12, 2021 |
| EVGA          | 111-KS-E272                 | [a97173038d](https://linux-hardware.org/?probe=a97173038d) | Jul 12, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [16799202de](https://linux-hardware.org/?probe=16799202de) | Jul 11, 2021 |
| Dell          | 0DF42J A00                  | [8a76db0ada](https://linux-hardware.org/?probe=8a76db0ada) | Jul 11, 2021 |
| ASUSTek       | EX-B250-V7                  | [32e09fdf66](https://linux-hardware.org/?probe=32e09fdf66) | Jul 11, 2021 |
| Gigabyte      | Z270-Gaming K3              | [731361283a](https://linux-hardware.org/?probe=731361283a) | Jul 10, 2021 |
| Gigabyte      | Z77MX-D3H                   | [9a275b8307](https://linux-hardware.org/?probe=9a275b8307) | Jul 10, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [89ed1de959](https://linux-hardware.org/?probe=89ed1de959) | Jul 10, 2021 |
| Dell          | 0VRWRC A00                  | [3ec458e478](https://linux-hardware.org/?probe=3ec458e478) | Jul 10, 2021 |
| Gigabyte      | P31-ES3G                    | [09ec64fc0d](https://linux-hardware.org/?probe=09ec64fc0d) | Jul 10, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [f008db5308](https://linux-hardware.org/?probe=f008db5308) | Jul 10, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [e1049532a5](https://linux-hardware.org/?probe=e1049532a5) | Jul 09, 2021 |
| MSI           | MS-B1711                    | [ad46286aa7](https://linux-hardware.org/?probe=ad46286aa7) | Jul 09, 2021 |
| HP            | 1497                        | [eecafd7c6c](https://linux-hardware.org/?probe=eecafd7c6c) | Jul 09, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [07e45f519d](https://linux-hardware.org/?probe=07e45f519d) | Jul 09, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [413c28caa0](https://linux-hardware.org/?probe=413c28caa0) | Jul 08, 2021 |
| HP            | 8056                        | [c35a7e4e65](https://linux-hardware.org/?probe=c35a7e4e65) | Jul 08, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | [785027f8f6](https://linux-hardware.org/?probe=785027f8f6) | Jul 08, 2021 |
| ASRock        | X399 Phantom Gaming 6       | [d93e096489](https://linux-hardware.org/?probe=d93e096489) | Jul 08, 2021 |
| Unknown       | DH61BR G32662-203           | [9314761de4](https://linux-hardware.org/?probe=9314761de4) | Jul 08, 2021 |
| Unknown       | DH61BR G32662-203           | [c658575abc](https://linux-hardware.org/?probe=c658575abc) | Jul 08, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [f0474e6193](https://linux-hardware.org/?probe=f0474e6193) | Jul 08, 2021 |
| MSI           | B450M MORTAR TITANIUM       | [25fdba4c4f](https://linux-hardware.org/?probe=25fdba4c4f) | Jul 08, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [47e2b55bb5](https://linux-hardware.org/?probe=47e2b55bb5) | Jul 07, 2021 |
| HP            | 8056                        | [f40b845088](https://linux-hardware.org/?probe=f40b845088) | Jul 07, 2021 |
| ASUSTek       | X99-A II                    | [d84c3b80a1](https://linux-hardware.org/?probe=d84c3b80a1) | Jul 07, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [a7ffc7e0dd](https://linux-hardware.org/?probe=a7ffc7e0dd) | Jul 07, 2021 |
| Gigabyte      | H61N-USB3                   | [4533c4325a](https://linux-hardware.org/?probe=4533c4325a) | Jul 07, 2021 |
| Dell          | 0PC5F7 A02                  | [ea43204b3b](https://linux-hardware.org/?probe=ea43204b3b) | Jul 06, 2021 |
| ASUSTek       | Z170-A                      | [04b8667d2e](https://linux-hardware.org/?probe=04b8667d2e) | Jul 06, 2021 |
| Gigabyte      | H61N-USB3                   | [936f2b1169](https://linux-hardware.org/?probe=936f2b1169) | Jul 06, 2021 |
| ASRock        | AD2700-ITX                  | [9b868b0c9b](https://linux-hardware.org/?probe=9b868b0c9b) | Jul 06, 2021 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | [5758df25ec](https://linux-hardware.org/?probe=5758df25ec) | Jul 06, 2021 |
| ASUSTek       | PRIME A320M-K               | [a44525ea2d](https://linux-hardware.org/?probe=a44525ea2d) | Jul 05, 2021 |
| Gigabyte      | Z77MX-D3H                   | [faa3279fc6](https://linux-hardware.org/?probe=faa3279fc6) | Jul 05, 2021 |
| ASUSTek       | Z87-DELUXE                  | [3aa1e79866](https://linux-hardware.org/?probe=3aa1e79866) | Jul 05, 2021 |
| ASUSTek       | PRIME X470-PRO              | [6fdc284c1a](https://linux-hardware.org/?probe=6fdc284c1a) | Jul 05, 2021 |
| MSI           | B450M BAZOOKA V2            | [efe8014efa](https://linux-hardware.org/?probe=efe8014efa) | Jul 05, 2021 |
| Gigabyte      | H61N-USB3                   | [7fe084720d](https://linux-hardware.org/?probe=7fe084720d) | Jul 05, 2021 |
| ASUSTek       | PRIME X470-PRO              | [13f5ecaf06](https://linux-hardware.org/?probe=13f5ecaf06) | Jul 04, 2021 |
| Alienware     | 0N4R4N A00                  | [9219336156](https://linux-hardware.org/?probe=9219336156) | Jul 04, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [9e7e50fd74](https://linux-hardware.org/?probe=9e7e50fd74) | Jul 04, 2021 |
| Gigabyte      | GA-990FXA-UD3               | [cb030b0e9f](https://linux-hardware.org/?probe=cb030b0e9f) | Jul 04, 2021 |
| Gigabyte      | H61N-USB3                   | [5b2d86e06f](https://linux-hardware.org/?probe=5b2d86e06f) | Jul 04, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [de1eb87e32](https://linux-hardware.org/?probe=de1eb87e32) | Jul 04, 2021 |
| HP            | 8056                        | [56f294962a](https://linux-hardware.org/?probe=56f294962a) | Jul 04, 2021 |
| ASUSTek       | ROG ZENITH EXTREME          | [e25c41c312](https://linux-hardware.org/?probe=e25c41c312) | Jul 03, 2021 |
| MSI           | MS-B9321                    | [93243d00da](https://linux-hardware.org/?probe=93243d00da) | Jul 03, 2021 |
| Google        | Panther                     | [043feff8fe](https://linux-hardware.org/?probe=043feff8fe) | Jul 03, 2021 |
| ASRock        | J3160DC-ITX                 | [cfd320c331](https://linux-hardware.org/?probe=cfd320c331) | Jul 03, 2021 |
| Chuwi         | LarkBox Pro                 | [0b050f9b1d](https://linux-hardware.org/?probe=0b050f9b1d) | Jul 03, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [0e5e9b16b8](https://linux-hardware.org/?probe=0e5e9b16b8) | Jul 03, 2021 |
| MSI           | PRESTIGE X570 CREATION      | [f61ba12c20](https://linux-hardware.org/?probe=f61ba12c20) | Jul 03, 2021 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | [36c64a337b](https://linux-hardware.org/?probe=36c64a337b) | Jul 03, 2021 |
| MSI           | H110M PRO-VD                | [55cdedffc2](https://linux-hardware.org/?probe=55cdedffc2) | Jul 03, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [f3ef9d51b3](https://linux-hardware.org/?probe=f3ef9d51b3) | Jul 02, 2021 |
| MSI           | MS-B1711                    | [21ec3e7523](https://linux-hardware.org/?probe=21ec3e7523) | Jul 02, 2021 |
| AMD           | A320IPC VER:1.00            | [f165ce8a70](https://linux-hardware.org/?probe=f165ce8a70) | Jul 01, 2021 |
| HP            | 8056                        | [d10cd539f1](https://linux-hardware.org/?probe=d10cd539f1) | Jul 01, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [48bef18c1a](https://linux-hardware.org/?probe=48bef18c1a) | Jul 01, 2021 |
| Gigabyte      | Z77MX-D3H                   | [ed64b27c12](https://linux-hardware.org/?probe=ed64b27c12) | Jul 01, 2021 |
| Gigabyte      | H61N-USB3                   | [d6bf3eece4](https://linux-hardware.org/?probe=d6bf3eece4) | Jun 30, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [a37dd487ac](https://linux-hardware.org/?probe=a37dd487ac) | Jun 30, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [e6cda3b64b](https://linux-hardware.org/?probe=e6cda3b64b) | Jun 30, 2021 |
| Dell          | 08NPPY A00                  | [28dd0487c3](https://linux-hardware.org/?probe=28dd0487c3) | Jun 30, 2021 |
| ASRock        | A320M-HD                    | [ce332204a6](https://linux-hardware.org/?probe=ce332204a6) | Jun 30, 2021 |
| Gigabyte      | B450M DS3H-CF               | [891b06178e](https://linux-hardware.org/?probe=891b06178e) | Jun 29, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [a8268a0c9d](https://linux-hardware.org/?probe=a8268a0c9d) | Jun 29, 2021 |
| Lenovo        | Board                       | [1e1ba598d3](https://linux-hardware.org/?probe=1e1ba598d3) | Jun 29, 2021 |
| ASUSTek       | PRIME Z370-A                | [1185271556](https://linux-hardware.org/?probe=1185271556) | Jun 29, 2021 |
| ASUSTek       | PRIME Z370-A                | [0369ff2b06](https://linux-hardware.org/?probe=0369ff2b06) | Jun 29, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [353a5052a1](https://linux-hardware.org/?probe=353a5052a1) | Jun 29, 2021 |
| Dell          | 06D7TR A00                  | [52e029b58e](https://linux-hardware.org/?probe=52e029b58e) | Jun 28, 2021 |
| SYWZ          | S200 Series                 | [a848b9e433](https://linux-hardware.org/?probe=a848b9e433) | Jun 28, 2021 |
| Positivo      | POS-MI945AA                 | [fd4be0982e](https://linux-hardware.org/?probe=fd4be0982e) | Jun 27, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | [a6b799f108](https://linux-hardware.org/?probe=a6b799f108) | Jun 27, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [62c1b02c31](https://linux-hardware.org/?probe=62c1b02c31) | Jun 27, 2021 |
| HP            | 8436                        | [617d5e50fd](https://linux-hardware.org/?probe=617d5e50fd) | Jun 27, 2021 |
| MSI           | B450M MORTAR TITANIUM       | [f479cb95d4](https://linux-hardware.org/?probe=f479cb95d4) | Jun 26, 2021 |
| Dell          | 08NPPY A00                  | [3c33ace801](https://linux-hardware.org/?probe=3c33ace801) | Jun 26, 2021 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [c1e9364997](https://linux-hardware.org/?probe=c1e9364997) | Jun 26, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [533712977b](https://linux-hardware.org/?probe=533712977b) | Jun 26, 2021 |
| Unknown       | NF-MCP78                    | [39a0c32be8](https://linux-hardware.org/?probe=39a0c32be8) | Jun 26, 2021 |
| Gigabyte      | Z77MX-D3H                   | [03a472ae41](https://linux-hardware.org/?probe=03a472ae41) | Jun 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [68cd01f446](https://linux-hardware.org/?probe=68cd01f446) | Jun 25, 2021 |
| HP            | 8056                        | [3cce894f08](https://linux-hardware.org/?probe=3cce894f08) | Jun 25, 2021 |
| ASUSTek       | PRIME B460M-A               | [95a80b91fd](https://linux-hardware.org/?probe=95a80b91fd) | Jun 25, 2021 |
| Gigabyte      | B150M-D3H-CF                | [02924c7c01](https://linux-hardware.org/?probe=02924c7c01) | Jun 25, 2021 |
| MSI           | B350M MORTAR ARCTIC         | [7f19e67108](https://linux-hardware.org/?probe=7f19e67108) | Jun 24, 2021 |
| Gigabyte      | H110M-H-CF                  | [f8a74fc57a](https://linux-hardware.org/?probe=f8a74fc57a) | Jun 24, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [b5d17f5b99](https://linux-hardware.org/?probe=b5d17f5b99) | Jun 24, 2021 |
| ASRock        | A320M-HD                    | [121770a05e](https://linux-hardware.org/?probe=121770a05e) | Jun 23, 2021 |
| MSI           | Z97 GAMING 5                | [8edc5f4d03](https://linux-hardware.org/?probe=8edc5f4d03) | Jun 23, 2021 |
| ASRock        | B550M Steel Legend          | [e1346ace5c](https://linux-hardware.org/?probe=e1346ace5c) | Jun 23, 2021 |
| Gigabyte      | Z77MX-D3H                   | [c69a0b8125](https://linux-hardware.org/?probe=c69a0b8125) | Jun 23, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [7a6f9e9890](https://linux-hardware.org/?probe=7a6f9e9890) | Jun 22, 2021 |
| ASRock        | H77 Pro4-M                  | [643c704c39](https://linux-hardware.org/?probe=643c704c39) | Jun 22, 2021 |
| Lenovo        | 3714 SDK0R32862 WIN 3258... | [b20ad5477a](https://linux-hardware.org/?probe=b20ad5477a) | Jun 22, 2021 |
| HP            | 198E                        | [b614ce2528](https://linux-hardware.org/?probe=b614ce2528) | Jun 22, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [ca17e02509](https://linux-hardware.org/?probe=ca17e02509) | Jun 22, 2021 |
| Unknown       | NF-MCP78                    | [b9ad532089](https://linux-hardware.org/?probe=b9ad532089) | Jun 22, 2021 |
| ASRock        | H97M Pro4                   | [b57edde05d](https://linux-hardware.org/?probe=b57edde05d) | Jun 22, 2021 |
| HP            | ProLiant ML150 G5           | [dd931cb4e6](https://linux-hardware.org/?probe=dd931cb4e6) | Jun 21, 2021 |
| ASRock        | Z97 Extreme4                | [9974950d4a](https://linux-hardware.org/?probe=9974950d4a) | Jun 21, 2021 |
| MSI           | B450 TOMAHAWK               | [8513c961a4](https://linux-hardware.org/?probe=8513c961a4) | Jun 21, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [4ac446c37b](https://linux-hardware.org/?probe=4ac446c37b) | Jun 21, 2021 |
| Gigabyte      | H77N-WIFI                   | [0c1eb0be4f](https://linux-hardware.org/?probe=0c1eb0be4f) | Jun 21, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [5af8c6f41c](https://linux-hardware.org/?probe=5af8c6f41c) | Jun 21, 2021 |
| ASUSTek       | PRIME B460M-A               | [5050b7baad](https://linux-hardware.org/?probe=5050b7baad) | Jun 21, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [59fa18019a](https://linux-hardware.org/?probe=59fa18019a) | Jun 20, 2021 |
| ASUSTek       | PRIME A320M-E               | [edb0b62fe0](https://linux-hardware.org/?probe=edb0b62fe0) | Jun 19, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [e3e63b4e4c](https://linux-hardware.org/?probe=e3e63b4e4c) | Jun 19, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | [ed109bbeda](https://linux-hardware.org/?probe=ed109bbeda) | Jun 19, 2021 |
| Dell          | 0F8101                      | [a33d01212c](https://linux-hardware.org/?probe=a33d01212c) | Jun 19, 2021 |
| HP            | 8056                        | [f1b5c0d45e](https://linux-hardware.org/?probe=f1b5c0d45e) | Jun 18, 2021 |
| Gigabyte      | Z270-HD3P-CF                | [8e3aa30f32](https://linux-hardware.org/?probe=8e3aa30f32) | Jun 18, 2021 |
| ASRock        | H97 Killer                  | [acc4773b1b](https://linux-hardware.org/?probe=acc4773b1b) | Jun 18, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [ecdf88f402](https://linux-hardware.org/?probe=ecdf88f402) | Jun 18, 2021 |
| HP            | 81C5 MVB                    | [eb5550cdef](https://linux-hardware.org/?probe=eb5550cdef) | Jun 17, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [419ff5b1e5](https://linux-hardware.org/?probe=419ff5b1e5) | Jun 17, 2021 |
| Gigabyte      | H77N-WIFI                   | [c9cf129666](https://linux-hardware.org/?probe=c9cf129666) | Jun 17, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [d17aa6436e](https://linux-hardware.org/?probe=d17aa6436e) | Jun 17, 2021 |
| Intel         | MIR1 RVP7                   | [b0a36a3845](https://linux-hardware.org/?probe=b0a36a3845) | Jun 17, 2021 |
| ASUSTek       | P5N73-CM                    | [5320c39497](https://linux-hardware.org/?probe=5320c39497) | Jun 16, 2021 |
| ASUSTek       | P5N73-CM                    | [096e520c57](https://linux-hardware.org/?probe=096e520c57) | Jun 16, 2021 |
| ASRock        | Z170 Extreme7+              | [180e2dcad0](https://linux-hardware.org/?probe=180e2dcad0) | Jun 16, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [caee94b554](https://linux-hardware.org/?probe=caee94b554) | Jun 16, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [28f64a2715](https://linux-hardware.org/?probe=28f64a2715) | Jun 15, 2021 |
| Gigabyte      | Z77MX-D3H                   | [6d61e60824](https://linux-hardware.org/?probe=6d61e60824) | Jun 15, 2021 |
| Gigabyte      | Z77MX-D3H                   | [7e4f2022c8](https://linux-hardware.org/?probe=7e4f2022c8) | Jun 15, 2021 |
| Lenovo        | Board                       | [b30a75edb2](https://linux-hardware.org/?probe=b30a75edb2) | Jun 15, 2021 |
| Gigabyte      | H77N-WIFI                   | [8fa18de364](https://linux-hardware.org/?probe=8fa18de364) | Jun 15, 2021 |
| Gigabyte      | EP45-DS3L                   | [a1f4d070a3](https://linux-hardware.org/?probe=a1f4d070a3) | Jun 14, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [692dcceeee](https://linux-hardware.org/?probe=692dcceeee) | Jun 14, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [3b280580e0](https://linux-hardware.org/?probe=3b280580e0) | Jun 14, 2021 |
| Lenovo        | Board                       | [c89aa8ea82](https://linux-hardware.org/?probe=c89aa8ea82) | Jun 13, 2021 |
| ASRock        | B450M-HDV R4.0              | [b5b8d7a195](https://linux-hardware.org/?probe=b5b8d7a195) | Jun 13, 2021 |
| Intel         | SHARKBAY                    | [2b38485e94](https://linux-hardware.org/?probe=2b38485e94) | Jun 13, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [c2803c157e](https://linux-hardware.org/?probe=c2803c157e) | Jun 13, 2021 |
| ASUSTek       | M2N-E SLI                   | [c1805791ab](https://linux-hardware.org/?probe=c1805791ab) | Jun 13, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [3f74265d6d](https://linux-hardware.org/?probe=3f74265d6d) | Jun 12, 2021 |
| Gigabyte      | Z97MX-Gaming 5              | [2dcbc551cd](https://linux-hardware.org/?probe=2dcbc551cd) | Jun 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [0a78275a12](https://linux-hardware.org/?probe=0a78275a12) | Jun 12, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [8081e6a752](https://linux-hardware.org/?probe=8081e6a752) | Jun 12, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [edcaa9a1be](https://linux-hardware.org/?probe=edcaa9a1be) | Jun 12, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [92f48178fc](https://linux-hardware.org/?probe=92f48178fc) | Jun 12, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [94d4ada14e](https://linux-hardware.org/?probe=94d4ada14e) | Jun 11, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [7805e2e2a1](https://linux-hardware.org/?probe=7805e2e2a1) | Jun 11, 2021 |
| HP            | 3397                        | [e171bcda3f](https://linux-hardware.org/?probe=e171bcda3f) | Jun 11, 2021 |
| Gigabyte      | EP41-UD3L                   | [aa273ff14d](https://linux-hardware.org/?probe=aa273ff14d) | Jun 10, 2021 |
| ASRock        | B550 Phantom Gaming-ITX/... | [405b055ebd](https://linux-hardware.org/?probe=405b055ebd) | Jun 10, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [565cd46886](https://linux-hardware.org/?probe=565cd46886) | Jun 10, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [ebca8fe85a](https://linux-hardware.org/?probe=ebca8fe85a) | Jun 09, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [0023c36bb4](https://linux-hardware.org/?probe=0023c36bb4) | Jun 09, 2021 |
| Gigabyte      | Z270-HD3P-CF                | [85ad270405](https://linux-hardware.org/?probe=85ad270405) | Jun 09, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [783d8a89bd](https://linux-hardware.org/?probe=783d8a89bd) | Jun 09, 2021 |
| Gigabyte      | Z77MX-D3H                   | [a1cfc1d335](https://linux-hardware.org/?probe=a1cfc1d335) | Jun 09, 2021 |
| ASRock        | A300M-STX                   | [d5fbd4c05d](https://linux-hardware.org/?probe=d5fbd4c05d) | Jun 08, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [0604956adc](https://linux-hardware.org/?probe=0604956adc) | Jun 08, 2021 |
| MSI           | Z390-A PRO                  | [8d4983662d](https://linux-hardware.org/?probe=8d4983662d) | Jun 08, 2021 |
| HP            | 843C                        | [391865c5a2](https://linux-hardware.org/?probe=391865c5a2) | Jun 08, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | [c493d4cdf9](https://linux-hardware.org/?probe=c493d4cdf9) | Jun 07, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2c66c12e1b](https://linux-hardware.org/?probe=2c66c12e1b) | Jun 07, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | [13eaba8cd2](https://linux-hardware.org/?probe=13eaba8cd2) | Jun 07, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [872d0ecc32](https://linux-hardware.org/?probe=872d0ecc32) | Jun 07, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [521f3e1bde](https://linux-hardware.org/?probe=521f3e1bde) | Jun 07, 2021 |
| Gateway       | DX4860                      | [bd9a842eec](https://linux-hardware.org/?probe=bd9a842eec) | Jun 07, 2021 |
| Gateway       | DX4860                      | [a26d972766](https://linux-hardware.org/?probe=a26d972766) | Jun 07, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [d5b58807dd](https://linux-hardware.org/?probe=d5b58807dd) | Jun 07, 2021 |
| ASRock        | B560M Steel Legend          | [c87d28e8c0](https://linux-hardware.org/?probe=c87d28e8c0) | Jun 07, 2021 |
| ASRock        | H97M Pro4                   | [8ba65755ff](https://linux-hardware.org/?probe=8ba65755ff) | Jun 06, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [7e68daad35](https://linux-hardware.org/?probe=7e68daad35) | Jun 06, 2021 |
| ASUSTek       | Z170-A                      | [ba3e1c4e32](https://linux-hardware.org/?probe=ba3e1c4e32) | Jun 05, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [d94c194ba5](https://linux-hardware.org/?probe=d94c194ba5) | Jun 05, 2021 |
| Intel         | H61                         | [607d6e5e33](https://linux-hardware.org/?probe=607d6e5e33) | Jun 05, 2021 |
| Intel         | H61                         | [8ed3e75d2d](https://linux-hardware.org/?probe=8ed3e75d2d) | Jun 05, 2021 |
| HP            | 8768 A                      | [f239501901](https://linux-hardware.org/?probe=f239501901) | Jun 05, 2021 |
| MSI           | A78M-E35                    | [4d4959df32](https://linux-hardware.org/?probe=4d4959df32) | Jun 04, 2021 |
| MSI           | A78M-E35                    | [7dc4db6092](https://linux-hardware.org/?probe=7dc4db6092) | Jun 04, 2021 |
| ASRock        | AB350 Pro4                  | [557557b4eb](https://linux-hardware.org/?probe=557557b4eb) | Jun 04, 2021 |
| HP            | 0AECh D                     | [0a0a487efe](https://linux-hardware.org/?probe=0a0a487efe) | Jun 04, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [4931426516](https://linux-hardware.org/?probe=4931426516) | Jun 03, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [1cb5b38d5e](https://linux-hardware.org/?probe=1cb5b38d5e) | Jun 03, 2021 |
| ASUSTek       | Z170-A                      | [221e440b21](https://linux-hardware.org/?probe=221e440b21) | Jun 03, 2021 |
| ASUSTek       | PRIME H310M-D               | [5f98fdcb02](https://linux-hardware.org/?probe=5f98fdcb02) | Jun 03, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [1c0016dc30](https://linux-hardware.org/?probe=1c0016dc30) | Jun 03, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [0e54cb2214](https://linux-hardware.org/?probe=0e54cb2214) | Jun 03, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [290d70d292](https://linux-hardware.org/?probe=290d70d292) | Jun 03, 2021 |
| Gigabyte      | H77N-WIFI                   | [ceb72d0ae7](https://linux-hardware.org/?probe=ceb72d0ae7) | Jun 03, 2021 |
| Gigabyte      | Z77MX-D3H                   | [9bae888d70](https://linux-hardware.org/?probe=9bae888d70) | Jun 03, 2021 |
| Lenovo        | Board                       | [4c17a95dc1](https://linux-hardware.org/?probe=4c17a95dc1) | Jun 03, 2021 |
| Dell          | 0427JK A00                  | [0cde3de43d](https://linux-hardware.org/?probe=0cde3de43d) | Jun 03, 2021 |
| ASUSTek       | Maximus VII HERO            | [dbfeab0bb4](https://linux-hardware.org/?probe=dbfeab0bb4) | Jun 02, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [1a7c5aee0e](https://linux-hardware.org/?probe=1a7c5aee0e) | Jun 02, 2021 |
| ASUSTek       | M2N-E SLI                   | [203b62c458](https://linux-hardware.org/?probe=203b62c458) | Jun 02, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [ad37db1da8](https://linux-hardware.org/?probe=ad37db1da8) | Jun 01, 2021 |
| Gigabyte      | A320M-S2H-CF                | [f5dafbe2de](https://linux-hardware.org/?probe=f5dafbe2de) | Jun 01, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [f7ca87e974](https://linux-hardware.org/?probe=f7ca87e974) | Jun 01, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [b8d0e81636](https://linux-hardware.org/?probe=b8d0e81636) | Jun 01, 2021 |
| Gigabyte      | 990XA-UD3                   | [77fcb9cf4a](https://linux-hardware.org/?probe=77fcb9cf4a) | Jun 01, 2021 |
| Gigabyte      | Z97-HD3                     | [e0277e3530](https://linux-hardware.org/?probe=e0277e3530) | May 31, 2021 |
| Dell          | 0R849J A00                  | [7a75936b55](https://linux-hardware.org/?probe=7a75936b55) | May 31, 2021 |
| Dell          | 0GXM1W A01                  | [4daf9fdc0d](https://linux-hardware.org/?probe=4daf9fdc0d) | May 31, 2021 |
| ASUSTek       | PRIME B460M-A               | [5125306d59](https://linux-hardware.org/?probe=5125306d59) | May 31, 2021 |
| MSI           | X570-A PRO                  | [9b20a88d5e](https://linux-hardware.org/?probe=9b20a88d5e) | May 31, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [65310866eb](https://linux-hardware.org/?probe=65310866eb) | May 31, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [ff3d2367ee](https://linux-hardware.org/?probe=ff3d2367ee) | May 30, 2021 |
| HP            | 8056                        | [fc6d4c2e7d](https://linux-hardware.org/?probe=fc6d4c2e7d) | May 30, 2021 |
| Huanan        | X79 VAA1                    | [150afcb2d1](https://linux-hardware.org/?probe=150afcb2d1) | May 30, 2021 |
| ASRock        | FM2A55M-VG3+                | [d9065ac8d1](https://linux-hardware.org/?probe=d9065ac8d1) | May 30, 2021 |
| Dell          | 00V62H A01                  | [73da9f35d4](https://linux-hardware.org/?probe=73da9f35d4) | May 29, 2021 |
| ASUSTek       | A88X-PRO                    | [bdb612797a](https://linux-hardware.org/?probe=bdb612797a) | May 29, 2021 |
| Gigabyte      | H370N WIFI-CF               | [197e319075](https://linux-hardware.org/?probe=197e319075) | May 29, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [06bb083e38](https://linux-hardware.org/?probe=06bb083e38) | May 29, 2021 |
| Gigabyte      | B360M D3H-CF                | [f23de0d726](https://linux-hardware.org/?probe=f23de0d726) | May 28, 2021 |
| Gigabyte      | H61M-S2PH                   | [e88de55691](https://linux-hardware.org/?probe=e88de55691) | May 28, 2021 |
| Dell          | 00V62H A01                  | [927f339e68](https://linux-hardware.org/?probe=927f339e68) | May 28, 2021 |
| ASRock        | B450M Pro4                  | [ccd56acb24](https://linux-hardware.org/?probe=ccd56acb24) | May 27, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | [5474165f7b](https://linux-hardware.org/?probe=5474165f7b) | May 27, 2021 |
| Unknown       | X79                         | [c6dcb137fb](https://linux-hardware.org/?probe=c6dcb137fb) | May 27, 2021 |
| ASRock        | X99 Extreme4                | [6feb0aec47](https://linux-hardware.org/?probe=6feb0aec47) | May 26, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | [172ab027e5](https://linux-hardware.org/?probe=172ab027e5) | May 26, 2021 |
| HP            | 21D0                        | [d6d7cbe7c5](https://linux-hardware.org/?probe=d6d7cbe7c5) | May 26, 2021 |
| HP            | 21D0                        | [68f25edcdd](https://linux-hardware.org/?probe=68f25edcdd) | May 26, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | [a6751fcc02](https://linux-hardware.org/?probe=a6751fcc02) | May 26, 2021 |
| ASRock        | A300M-STX                   | [4e5245a71d](https://linux-hardware.org/?probe=4e5245a71d) | May 25, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | [b07793f86c](https://linux-hardware.org/?probe=b07793f86c) | May 25, 2021 |
| Gigabyte      | Z97N-Gaming 5               | [b1b61b4aa6](https://linux-hardware.org/?probe=b1b61b4aa6) | May 25, 2021 |
| Intel         | H61                         | [5b5682ab2e](https://linux-hardware.org/?probe=5b5682ab2e) | May 25, 2021 |
| ASRock        | A300M-STX                   | [cecc5ad69e](https://linux-hardware.org/?probe=cecc5ad69e) | May 24, 2021 |
| ASUSTek       | PRIME Z370-A                | [cf4e1cb0d6](https://linux-hardware.org/?probe=cf4e1cb0d6) | May 24, 2021 |
| ASUSTek       | PRIME Z370-A                | [e65ad78e90](https://linux-hardware.org/?probe=e65ad78e90) | May 24, 2021 |
| HP            | 198E                        | [45fbf9c1d7](https://linux-hardware.org/?probe=45fbf9c1d7) | May 23, 2021 |
| Unknown       | Unknown                     | [ad90a50d8d](https://linux-hardware.org/?probe=ad90a50d8d) | May 22, 2021 |
| Unknown       | Unknown                     | [acaa4c3731](https://linux-hardware.org/?probe=acaa4c3731) | May 22, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [d3762e2020](https://linux-hardware.org/?probe=d3762e2020) | May 21, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [662203ff7f](https://linux-hardware.org/?probe=662203ff7f) | May 21, 2021 |
| ASRock        | E3C226D2I                   | [195f9748ad](https://linux-hardware.org/?probe=195f9748ad) | May 20, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [a0188a80b1](https://linux-hardware.org/?probe=a0188a80b1) | May 20, 2021 |
| ASUSTek       | ROG STRIX B460-H GAMING     | [7911704f32](https://linux-hardware.org/?probe=7911704f32) | May 19, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | [657fe689d6](https://linux-hardware.org/?probe=657fe689d6) | May 19, 2021 |
| ASUSTek       | Z97-A                       | [0767c99abb](https://linux-hardware.org/?probe=0767c99abb) | May 19, 2021 |
| Unknown       | X79                         | [718089029d](https://linux-hardware.org/?probe=718089029d) | May 18, 2021 |
| Acer          | Veriton X2640G V:1.0        | [6e95528aca](https://linux-hardware.org/?probe=6e95528aca) | May 18, 2021 |
| ASUSTek       | PRIME Z370-A II             | [5a5c05e953](https://linux-hardware.org/?probe=5a5c05e953) | May 18, 2021 |
| ASUSTek       | Z77-A                       | [5569c32840](https://linux-hardware.org/?probe=5569c32840) | May 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | [64c121a751](https://linux-hardware.org/?probe=64c121a751) | May 18, 2021 |
| ASRock        | Z370 Professional Gaming... | [2c915c81d9](https://linux-hardware.org/?probe=2c915c81d9) | May 18, 2021 |
| Dell          | 077RRV A00                  | [c9ed9d5dfa](https://linux-hardware.org/?probe=c9ed9d5dfa) | May 17, 2021 |
| ASRock        | Z270 Pro4                   | [ba92e877c3](https://linux-hardware.org/?probe=ba92e877c3) | May 17, 2021 |
| MSI           | H110I PRO AC                | [17722fe0bf](https://linux-hardware.org/?probe=17722fe0bf) | May 17, 2021 |
| Gigabyte      | Z370N WIFI-CF               | [ca8565e246](https://linux-hardware.org/?probe=ca8565e246) | May 17, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [43bbdc2153](https://linux-hardware.org/?probe=43bbdc2153) | May 16, 2021 |
| MSI           | X570-A PRO                  | [16c877dbfe](https://linux-hardware.org/?probe=16c877dbfe) | May 16, 2021 |
| ASUSTek       | P7P55 LX                    | [35257f4cf0](https://linux-hardware.org/?probe=35257f4cf0) | May 16, 2021 |
| Unknown       | NF-MCP78                    | [4af8e42b5a](https://linux-hardware.org/?probe=4af8e42b5a) | May 16, 2021 |
| ASRock        | FM2A55M-VG3+                | [41e6c088d2](https://linux-hardware.org/?probe=41e6c088d2) | May 16, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [1d398072e8](https://linux-hardware.org/?probe=1d398072e8) | May 15, 2021 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [be75687645](https://linux-hardware.org/?probe=be75687645) | May 15, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [344858ad94](https://linux-hardware.org/?probe=344858ad94) | May 15, 2021 |
| Alienware     | 07HV66 A01                  | [016da6343d](https://linux-hardware.org/?probe=016da6343d) | May 15, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [c85191ea3e](https://linux-hardware.org/?probe=c85191ea3e) | May 15, 2021 |
| MSI           | B560M PRO-VDH WIFI          | [529fdcaf2a](https://linux-hardware.org/?probe=529fdcaf2a) | May 14, 2021 |
| Unknown       | NF-MCP78                    | [a419bff4a3](https://linux-hardware.org/?probe=a419bff4a3) | May 14, 2021 |
| ASRock        | X570 Creator                | [6ac8300ce8](https://linux-hardware.org/?probe=6ac8300ce8) | May 14, 2021 |
| ASUSTek       | M5A97                       | [3853338a60](https://linux-hardware.org/?probe=3853338a60) | May 14, 2021 |
| Acer          | Veriton X2640G V:1.0        | [924b420c67](https://linux-hardware.org/?probe=924b420c67) | May 13, 2021 |
| Dell          | 0HD5W2 A01                  | [3d9373090c](https://linux-hardware.org/?probe=3d9373090c) | May 13, 2021 |
| ASUSTek       | Benicia                     | [d8f52bab1c](https://linux-hardware.org/?probe=d8f52bab1c) | May 12, 2021 |
| ASUSTek       | Benicia                     | [a36fa0a3b4](https://linux-hardware.org/?probe=a36fa0a3b4) | May 12, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [22e9d3f5fd](https://linux-hardware.org/?probe=22e9d3f5fd) | May 12, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [fab7d18783](https://linux-hardware.org/?probe=fab7d18783) | May 12, 2021 |
| ASRock        | FM2A55M-VG3+                | [370eb9dee4](https://linux-hardware.org/?probe=370eb9dee4) | May 12, 2021 |
| ASRock        | FM2A55M-VG3+                | [ada1c4a259](https://linux-hardware.org/?probe=ada1c4a259) | May 12, 2021 |
| MSI           | B350M GAMING PRO            | [565e8ea07c](https://linux-hardware.org/?probe=565e8ea07c) | May 12, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [702de808b0](https://linux-hardware.org/?probe=702de808b0) | May 11, 2021 |
| Gigabyte      | A320M-S2H-CF                | [cff0fbf297](https://linux-hardware.org/?probe=cff0fbf297) | May 11, 2021 |
| MSI           | H170A GAMING PRO            | [a7c97c0108](https://linux-hardware.org/?probe=a7c97c0108) | May 10, 2021 |
| HP            | 1494                        | [26a35b5f46](https://linux-hardware.org/?probe=26a35b5f46) | May 10, 2021 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [a3a6a201cf](https://linux-hardware.org/?probe=a3a6a201cf) | May 10, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [816b6507ca](https://linux-hardware.org/?probe=816b6507ca) | May 09, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [16ae1580d3](https://linux-hardware.org/?probe=16ae1580d3) | May 09, 2021 |
| ASUSTek       | ProArt B550-CREATOR         | [6969c309d4](https://linux-hardware.org/?probe=6969c309d4) | May 09, 2021 |
| Gigabyte      | H310M H                     | [993800d632](https://linux-hardware.org/?probe=993800d632) | May 08, 2021 |
| Gigabyte      | H87-HD3                     | [ef87a640ab](https://linux-hardware.org/?probe=ef87a640ab) | May 08, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [312ad18259](https://linux-hardware.org/?probe=312ad18259) | May 08, 2021 |
| Biostar       | H81MLC                      | [d8da680e51](https://linux-hardware.org/?probe=d8da680e51) | May 08, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [d20858b78f](https://linux-hardware.org/?probe=d20858b78f) | May 08, 2021 |
| ASUSTek       | M5A78L-M LX3                | [d6af9c1156](https://linux-hardware.org/?probe=d6af9c1156) | May 07, 2021 |
| ASRock        | X570 Taichi                 | [a0c245e667](https://linux-hardware.org/?probe=a0c245e667) | May 07, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [73fd34e4a9](https://linux-hardware.org/?probe=73fd34e4a9) | May 07, 2021 |
| Acer          | Veriton S2660G              | [31f3a2c202](https://linux-hardware.org/?probe=31f3a2c202) | May 07, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [bdd3604cd8](https://linux-hardware.org/?probe=bdd3604cd8) | May 07, 2021 |
| HP            | 1497                        | [bd5ee666bd](https://linux-hardware.org/?probe=bd5ee666bd) | May 07, 2021 |
| HP            | 1497                        | [e52c3c2489](https://linux-hardware.org/?probe=e52c3c2489) | May 06, 2021 |
| HP            | 1791                        | [ad7ad34a9d](https://linux-hardware.org/?probe=ad7ad34a9d) | May 06, 2021 |
| ASUSTek       | PRIME X570-P                | [a34826ba77](https://linux-hardware.org/?probe=a34826ba77) | May 06, 2021 |
| Lenovo        | Board                       | [239c4bf44d](https://linux-hardware.org/?probe=239c4bf44d) | May 06, 2021 |
| ASUSTek       | P8H61-M LE R2.0             | [b411cc602f](https://linux-hardware.org/?probe=b411cc602f) | May 06, 2021 |
| Gigabyte      | B75M-D3P                    | [ab4f7cc66d](https://linux-hardware.org/?probe=ab4f7cc66d) | May 06, 2021 |
| ASUSTek       | P5QL-E                      | [1aee0fab6e](https://linux-hardware.org/?probe=1aee0fab6e) | May 05, 2021 |
| MSI           | P55-GD80                    | [e9002ad1ad](https://linux-hardware.org/?probe=e9002ad1ad) | May 04, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [2f8ba8af70](https://linux-hardware.org/?probe=2f8ba8af70) | May 04, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [523fba1dd3](https://linux-hardware.org/?probe=523fba1dd3) | May 04, 2021 |
| ASRock        | H310CM-HDV/M.2              | [af0ec6cab7](https://linux-hardware.org/?probe=af0ec6cab7) | May 04, 2021 |
| MSI           | B350I PRO AC                | [db10576980](https://linux-hardware.org/?probe=db10576980) | May 04, 2021 |
| Gigabyte      | B150M-D3H-CF                | [3ab07ff020](https://linux-hardware.org/?probe=3ab07ff020) | May 03, 2021 |
| Gigabyte      | B450M DS3H WIFI-CF          | [fec58faf85](https://linux-hardware.org/?probe=fec58faf85) | May 03, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [74bff35fdd](https://linux-hardware.org/?probe=74bff35fdd) | May 02, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [3551a877a0](https://linux-hardware.org/?probe=3551a877a0) | May 02, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [d0660819a7](https://linux-hardware.org/?probe=d0660819a7) | May 02, 2021 |
| HP            | 3029h                       | [f0912110eb](https://linux-hardware.org/?probe=f0912110eb) | May 02, 2021 |
| Gigabyte      | B450 AORUS M                | [fe7a0a48f9](https://linux-hardware.org/?probe=fe7a0a48f9) | May 02, 2021 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | [1c48dea9a3](https://linux-hardware.org/?probe=1c48dea9a3) | May 02, 2021 |
| MSI           | P55-GD80                    | [2fc3e6dd6a](https://linux-hardware.org/?probe=2fc3e6dd6a) | May 01, 2021 |
| MSI           | P55-GD80                    | [a950a914fc](https://linux-hardware.org/?probe=a950a914fc) | May 01, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [e019fb0b7a](https://linux-hardware.org/?probe=e019fb0b7a) | May 01, 2021 |
| Biostar       | TB350-BTC                   | [905cd6f7b5](https://linux-hardware.org/?probe=905cd6f7b5) | May 01, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | [ef811a6184](https://linux-hardware.org/?probe=ef811a6184) | May 01, 2021 |
| MSI           | B365M PRO-VDH               | [e0ff71901e](https://linux-hardware.org/?probe=e0ff71901e) | Apr 30, 2021 |
| ASRock        | H81M-HG4 R4.0               | [3fb3ca76ae](https://linux-hardware.org/?probe=3fb3ca76ae) | Apr 30, 2021 |
| Lenovo        | SDK0J40700 WIN              | [000925bf4b](https://linux-hardware.org/?probe=000925bf4b) | Apr 30, 2021 |
| ASUSTek       | PRIME A520M-K               | [9f2a73a4d2](https://linux-hardware.org/?probe=9f2a73a4d2) | Apr 30, 2021 |
| Gigabyte      | B450 AORUS M                | [179e39ba13](https://linux-hardware.org/?probe=179e39ba13) | Apr 30, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [916b016881](https://linux-hardware.org/?probe=916b016881) | Apr 30, 2021 |
| ASRock        | B450 Pro4                   | [e66999f076](https://linux-hardware.org/?probe=e66999f076) | Apr 30, 2021 |
| ASRock        | A320M-HDV R4.0              | [3bb19f53e9](https://linux-hardware.org/?probe=3bb19f53e9) | Apr 30, 2021 |
| HP            | 82F2 A01                    | [abecc29894](https://linux-hardware.org/?probe=abecc29894) | Apr 30, 2021 |
| HP            | 82F2 A01                    | [6c0f1f15f5](https://linux-hardware.org/?probe=6c0f1f15f5) | Apr 30, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [fcfd291a4f](https://linux-hardware.org/?probe=fcfd291a4f) | Apr 30, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [fb11e4cdcc](https://linux-hardware.org/?probe=fb11e4cdcc) | Apr 29, 2021 |
| Gigabyte      | Z87-D3HP-CF                 | [a93721363c](https://linux-hardware.org/?probe=a93721363c) | Apr 29, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [a09dab9f9b](https://linux-hardware.org/?probe=a09dab9f9b) | Apr 29, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [492d410d60](https://linux-hardware.org/?probe=492d410d60) | Apr 29, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [ac1ae66d11](https://linux-hardware.org/?probe=ac1ae66d11) | Apr 29, 2021 |
| MSI           | GF615M-P33                  | [4219571ca8](https://linux-hardware.org/?probe=4219571ca8) | Apr 29, 2021 |
| ASUSTek       | H110M-K                     | [f323b316a2](https://linux-hardware.org/?probe=f323b316a2) | Apr 29, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [2ff23ca44c](https://linux-hardware.org/?probe=2ff23ca44c) | Apr 28, 2021 |
| MSI           | B250 PC MATE                | [4feda9bc8e](https://linux-hardware.org/?probe=4feda9bc8e) | Apr 28, 2021 |
| Medion        | Cattle24 1M                 | [2273e237c4](https://linux-hardware.org/?probe=2273e237c4) | Apr 28, 2021 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | [69827caaf1](https://linux-hardware.org/?probe=69827caaf1) | Apr 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [97016e3ff3](https://linux-hardware.org/?probe=97016e3ff3) | Apr 27, 2021 |
| ASRock        | H81M-HG4 R4.0               | [4a7617821f](https://linux-hardware.org/?probe=4a7617821f) | Apr 25, 2021 |
| ASRock        | K10N78D                     | [9b0a7f242b](https://linux-hardware.org/?probe=9b0a7f242b) | Apr 24, 2021 |
| Gigabyte      | B150M-D3H-CF                | [573385087f](https://linux-hardware.org/?probe=573385087f) | Apr 24, 2021 |
| MSI           | Z370-A PRO                  | [470be454f6](https://linux-hardware.org/?probe=470be454f6) | Apr 23, 2021 |
| Gigabyte      | B150M-D3H-CF                | [4ea82584ae](https://linux-hardware.org/?probe=4ea82584ae) | Apr 23, 2021 |
| eMachines     | EMCP73VT-PM                 | [4e2eabe9ea](https://linux-hardware.org/?probe=4e2eabe9ea) | Apr 21, 2021 |
| MSI           | MEG Z390 GODLIKE            | [320bab5ee4](https://linux-hardware.org/?probe=320bab5ee4) | Apr 21, 2021 |
| Gigabyte      | B450M DS3H V2               | [7b5da54a3b](https://linux-hardware.org/?probe=7b5da54a3b) | Apr 20, 2021 |
| MSI           | B350M PRO-VDH               | [50704a4b1b](https://linux-hardware.org/?probe=50704a4b1b) | Apr 20, 2021 |
| MSI           | B450M MORTAR TITANIUM       | [3aa509bfc6](https://linux-hardware.org/?probe=3aa509bfc6) | Apr 19, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [4046940d3e](https://linux-hardware.org/?probe=4046940d3e) | Apr 19, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [41035d03ea](https://linux-hardware.org/?probe=41035d03ea) | Apr 19, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [2fe3493737](https://linux-hardware.org/?probe=2fe3493737) | Apr 17, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [0691d30eea](https://linux-hardware.org/?probe=0691d30eea) | Apr 16, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [414dee060e](https://linux-hardware.org/?probe=414dee060e) | Apr 15, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [099a3d1264](https://linux-hardware.org/?probe=099a3d1264) | Apr 15, 2021 |
| ASRock        | AB350 Pro4                  | [a0686a3f62](https://linux-hardware.org/?probe=a0686a3f62) | Apr 11, 2021 |
| ASRock        | AB350 Pro4                  | [7e77253d59](https://linux-hardware.org/?probe=7e77253d59) | Apr 11, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [722e60e516](https://linux-hardware.org/?probe=722e60e516) | Apr 10, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [a4b4d5abd6](https://linux-hardware.org/?probe=a4b4d5abd6) | Apr 09, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [0b127087c5](https://linux-hardware.org/?probe=0b127087c5) | Apr 09, 2021 |
| ASUSTek       | H110M-K                     | [b2c194ec6f](https://linux-hardware.org/?probe=b2c194ec6f) | Apr 09, 2021 |
| Lenovo        | Board                       | [d27988d8dd](https://linux-hardware.org/?probe=d27988d8dd) | Apr 09, 2021 |
| Gigabyte      | Z97N-WIFI                   | [6e9360be26](https://linux-hardware.org/?probe=6e9360be26) | Apr 09, 2021 |
| ASUSTek       | Maximus VII HERO            | [f1bdcd63e8](https://linux-hardware.org/?probe=f1bdcd63e8) | Apr 09, 2021 |
| Dell          | 0GWHMW A03                  | [a0ff0f4cf3](https://linux-hardware.org/?probe=a0ff0f4cf3) | Apr 08, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [b3b901029c](https://linux-hardware.org/?probe=b3b901029c) | Apr 07, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [2824275b63](https://linux-hardware.org/?probe=2824275b63) | Apr 07, 2021 |
| MSI           | B350M GAMING PRO            | [de5a14a4f3](https://linux-hardware.org/?probe=de5a14a4f3) | Apr 06, 2021 |
| ASUSTek       | Z87-DELUXE                  | [e4f7f8688b](https://linux-hardware.org/?probe=e4f7f8688b) | Apr 05, 2021 |
| Gigabyte      | H87-HD3                     | [a78f2d8699](https://linux-hardware.org/?probe=a78f2d8699) | Apr 05, 2021 |
| Gigabyte      | H310M H x.x                 | [ec750c2771](https://linux-hardware.org/?probe=ec750c2771) | Apr 05, 2021 |
| Unknown       | Unknown                     | [d38419f785](https://linux-hardware.org/?probe=d38419f785) | Apr 04, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [42b83bbd08](https://linux-hardware.org/?probe=42b83bbd08) | Apr 03, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [9e4b82fb49](https://linux-hardware.org/?probe=9e4b82fb49) | Apr 02, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [ea8316fe72](https://linux-hardware.org/?probe=ea8316fe72) | Apr 01, 2021 |
| Gigabyte      | A520M DS3H                  | [6977cb0073](https://linux-hardware.org/?probe=6977cb0073) | Mar 31, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [e6a1ba54cc](https://linux-hardware.org/?probe=e6a1ba54cc) | Mar 30, 2021 |
| ASUSTek       | H61M-E                      | [fcc9dabb3d](https://linux-hardware.org/?probe=fcc9dabb3d) | Mar 30, 2021 |
| ASUSTek       | H61M-E                      | [ed7f2979b9](https://linux-hardware.org/?probe=ed7f2979b9) | Mar 30, 2021 |
| Alienware     | 0FRTKJ A00                  | [e31c5f36aa](https://linux-hardware.org/?probe=e31c5f36aa) | Mar 28, 2021 |
| MSI           | Z490-A PRO                  | [cf1b5653e8](https://linux-hardware.org/?probe=cf1b5653e8) | Mar 28, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [b41b0c2610](https://linux-hardware.org/?probe=b41b0c2610) | Mar 28, 2021 |
| Gigabyte      | H87-HD3                     | [0f0ff492d9](https://linux-hardware.org/?probe=0f0ff492d9) | Mar 27, 2021 |
| Gigabyte      | H87-HD3                     | [87cb9f98e5](https://linux-hardware.org/?probe=87cb9f98e5) | Mar 27, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [0e12cc8e95](https://linux-hardware.org/?probe=0e12cc8e95) | Mar 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [a0f771669c](https://linux-hardware.org/?probe=a0f771669c) | Mar 24, 2021 |
| Gigabyte      | A320M-H-CF                  | [01c43fc8b4](https://linux-hardware.org/?probe=01c43fc8b4) | Mar 23, 2021 |
| MSI           | 760GM-P21                   | [91a13be8c4](https://linux-hardware.org/?probe=91a13be8c4) | Mar 17, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [6124e0aa83](https://linux-hardware.org/?probe=6124e0aa83) | Mar 17, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [07cd9eac56](https://linux-hardware.org/?probe=07cd9eac56) | Mar 17, 2021 |
| Gigabyte      | Z490 VISION D               | [0ac71fbeba](https://linux-hardware.org/?probe=0ac71fbeba) | Feb 28, 2021 |
| Gigabyte      | B450M DS3H-CF               | [6b611bf344](https://linux-hardware.org/?probe=6b611bf344) | Feb 26, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [fdc4baf022](https://linux-hardware.org/?probe=fdc4baf022) | Feb 23, 2021 |
| ECS           | MCP61M-M3                   | [445f06dbde](https://linux-hardware.org/?probe=445f06dbde) | Jan 29, 2021 |
| ASUSTek       | PRIME X570-PRO              | [e3a5631517](https://linux-hardware.org/?probe=e3a5631517) | Nov 15, 2020 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [f695c35adf](https://linux-hardware.org/?probe=f695c35adf) | Oct 12, 2020 |
| Positivo      | POS-PARS760GCD              | [482e549764](https://linux-hardware.org/?probe=482e549764) | Sep 05, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                              | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| 5.12.13-300.fc34.x86_64                              | 32       | 7.41%   |
| 5.13.12-200.fc34.x86_64                              | 28       | 6.48%   |
| 5.12.8-300.fc34.x86_64                               | 25       | 5.79%   |
| 5.11.16-300.fc34.x86_64                              | 23       | 5.32%   |
| 5.11.12-300.fc34.x86_64                              | 21       | 4.86%   |
| 5.11.17-300.fc34.x86_64                              | 17       | 3.94%   |
| 5.13.6-200.fc34.x86_64                               | 16       | 3.7%    |
| 5.12.9-300.fc34.x86_64                               | 16       | 3.7%    |
| 5.12.7-300.fc34.x86_64                               | 16       | 3.7%    |
| 5.12.15-300.fc34.x86_64                              | 16       | 3.7%    |
| 5.12.12-300.fc34.x86_64                              | 16       | 3.7%    |
| 5.13.9-200.fc34.x86_64                               | 15       | 3.47%   |
| 5.13.4-200.fc34.x86_64                               | 15       | 3.47%   |
| 5.13.8-200.fc34.x86_64                               | 14       | 3.24%   |
| 5.12.14-300.fc34.x86_64                              | 14       | 3.24%   |
| 5.11.19-300.fc34.x86_64                              | 14       | 3.24%   |
| 5.11.20-300.fc34.x86_64                              | 13       | 3.01%   |
| 5.11.18-300.fc34.x86_64                              | 12       | 2.78%   |
| 5.11.11-300.fc34.x86_64                              | 12       | 2.78%   |
| 5.12.11-300.fc34.x86_64                              | 11       | 2.55%   |
| 5.13.10-200.fc34.x86_64                              | 9        | 2.08%   |
| 5.12.6-300.fc34.x86_64                               | 9        | 2.08%   |
| 5.13.7-200.fc34.x86_64                               | 7        | 1.62%   |
| 5.12.10-300.fc34.x86_64                              | 7        | 1.62%   |
| 5.11.3-300.fc34.x86_64                               | 5        | 1.16%   |
| 5.13.5-200.fc34.x86_64                               | 4        | 0.93%   |
| 5.11.15-300.fc34.x86_64                              | 4        | 0.93%   |
| 5.11.10-300.fc34.x86_64                              | 4        | 0.93%   |
| 5.12.17-300.fc34.x86_64                              | 3        | 0.69%   |
| 5.11.9-300.fc34.x86_64                               | 3        | 0.69%   |
| 5.11.14-300.fc34.x86_64                              | 3        | 0.69%   |
| 5.11.13-300.fc34.x86_64                              | 3        | 0.69%   |
| 5.13.1-300.fc34.x86_64                               | 2        | 0.46%   |
| 5.12.5-300.fc34.x86_64                               | 2        | 0.46%   |
| 5.11.8-300.fc34.x86_64                               | 2        | 0.46%   |
| 5.11.21-300.fc34.x86_64                              | 2        | 0.46%   |
| 5.11.0-156.fc34.x86_64                               | 2        | 0.46%   |
| 5.9.0-0.rc8.20201009git7575fdda569b.32.fc34.x86_64   | 1        | 0.23%   |
| 5.13.8-xm1cacule.0.fc34.x86_64                       | 1        | 0.23%   |
| 5.13.4-201.fsync.fc34.x86_64                         | 1        | 0.23%   |
| 5.13.0-xm1.1.fc34.x86_64                             | 1        | 0.23%   |
| 5.12.7-16-Yeoreum                                    | 1        | 0.23%   |
| 5.12.2-300.fc34.x86_64                               | 1        | 0.23%   |
| 5.12.14-300.fc34.x86_64+debug                        | 1        | 0.23%   |
| 5.12.11-200.fc33.x86_64                              | 1        | 0.23%   |
| 5.12.0-xanmod1_cacule.0.fc34                         | 1        | 0.23%   |
| 5.11.6-300.fc34.x86_64                               | 1        | 0.23%   |
| 5.11.2-300.fc34.x86_64                               | 1        | 0.23%   |
| 5.11.0-0.rc5.20210127git2ab38c17aac1.136.fc34.x86_64 | 1        | 0.23%   |
| 5.10.47-1.fc32.qubes.x86_64                          | 1        | 0.23%   |
| 5.10.21-200.fc33.x86_64                              | 1        | 0.23%   |
| 5.10.0-0.rc1.20201028gited8780e3f2ec.57.fc34.x86_64  | 1        | 0.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.12.13 | 32       | 7.41%   |
| 5.13.12 | 28       | 6.48%   |
| 5.12.8  | 25       | 5.79%   |
| 5.11.16 | 23       | 5.32%   |
| 5.11.12 | 21       | 4.86%   |
| 5.12.7  | 17       | 3.94%   |
| 5.11.17 | 17       | 3.94%   |
| 5.13.6  | 16       | 3.7%    |
| 5.13.4  | 16       | 3.7%    |
| 5.12.9  | 16       | 3.7%    |
| 5.12.15 | 16       | 3.7%    |
| 5.12.12 | 16       | 3.7%    |
| 5.13.9  | 15       | 3.47%   |
| 5.13.8  | 15       | 3.47%   |
| 5.12.14 | 15       | 3.47%   |
| 5.11.19 | 14       | 3.24%   |
| 5.11.20 | 13       | 3.01%   |
| 5.12.11 | 12       | 2.78%   |
| 5.11.18 | 12       | 2.78%   |
| 5.11.11 | 12       | 2.78%   |
| 5.13.10 | 9        | 2.08%   |
| 5.12.6  | 9        | 2.08%   |
| 5.13.7  | 7        | 1.62%   |
| 5.12.10 | 7        | 1.62%   |
| 5.11.3  | 5        | 1.16%   |
| 5.13.5  | 4        | 0.93%   |
| 5.11.15 | 4        | 0.93%   |
| 5.11.10 | 4        | 0.93%   |
| 5.12.17 | 3        | 0.69%   |
| 5.11.9  | 3        | 0.69%   |
| 5.11.14 | 3        | 0.69%   |
| 5.11.13 | 3        | 0.69%   |
| 5.11.0  | 3        | 0.69%   |
| 5.13.1  | 2        | 0.46%   |
| 5.12.5  | 2        | 0.46%   |
| 5.11.8  | 2        | 0.46%   |
| 5.11.21 | 2        | 0.46%   |
| 5.9.0   | 1        | 0.23%   |
| 5.13.0  | 1        | 0.23%   |
| 5.12.2  | 1        | 0.23%   |
| 5.12.0  | 1        | 0.23%   |
| 5.11.6  | 1        | 0.23%   |
| 5.11.2  | 1        | 0.23%   |
| 5.10.47 | 1        | 0.23%   |
| 5.10.21 | 1        | 0.23%   |
| 5.10.0  | 1        | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.12    | 158      | 39.01%  |
| 5.11    | 134      | 33.09%  |
| 5.13    | 109      | 26.91%  |
| 5.10    | 3        | 0.74%   |
| 5.9     | 1        | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 367      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 272      | 72.92%  |
| KDE           | 26       | 6.97%   |
| KDE5          | 20       | 5.36%   |
| Cinnamon      | 16       | 4.29%   |
| Unknown       | 14       | 3.75%   |
| X-Cinnamon    | 8        | 2.14%   |
| MATE          | 7        | 1.88%   |
| XFCE          | 4        | 1.07%   |
| GNOME Classic | 2        | 0.54%   |
| openbox       | 1        | 0.27%   |
| NsCDE         | 1        | 0.27%   |
| LXDE          | 1        | 0.27%   |
| Deepin        | 1        | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 203      | 52.86%  |
| X11     | 158      | 41.15%  |
| Tty     | 16       | 4.17%   |
| Unknown | 7        | 1.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 224      | 59.42%  |
| GDM     | 107      | 28.38%  |
| SDDM    | 17       | 4.51%   |
| TDM     | 14       | 3.71%   |
| LightDM | 14       | 3.71%   |
| KDM     | 1        | 0.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 164      | 44.32%  |
| en_GB   | 32       | 8.65%   |
| pt_BR   | 24       | 6.49%   |
| ru_RU   | 20       | 5.41%   |
| en_AU   | 19       | 5.14%   |
| de_DE   | 18       | 4.86%   |
| en_CA   | 17       | 4.59%   |
| fr_FR   | 14       | 3.78%   |
| pl_PL   | 7        | 1.89%   |
| it_IT   | 5        | 1.35%   |
| ja_JP   | 4        | 1.08%   |
| es_ES   | 4        | 1.08%   |
| ru_UA   | 3        | 0.81%   |
| en_IN   | 3        | 0.81%   |
| cs_CZ   | 3        | 0.81%   |
| sk_SK   | 2        | 0.54%   |
| nl_NL   | 2        | 0.54%   |
| nl_BE   | 2        | 0.54%   |
| fr_CH   | 2        | 0.54%   |
| en_SG   | 2        | 0.54%   |
| en_NZ   | 2        | 0.54%   |
| C       | 2        | 0.54%   |
| Unknown | 2        | 0.54%   |
| zh_TW   | 1        | 0.27%   |
| uk_UA   | 1        | 0.27%   |
| ko_KR   | 1        | 0.27%   |
| hu_HU   | 1        | 0.27%   |
| fi_FI   | 1        | 0.27%   |
| es_UY   | 1        | 0.27%   |
| es_PA   | 1        | 0.27%   |
| es_EC   | 1        | 0.27%   |
| es_DO   | 1        | 0.27%   |
| es_CL   | 1        | 0.27%   |
| es_AR   | 1        | 0.27%   |
| en_ZA   | 1        | 0.27%   |
| en_IL   | 1        | 0.27%   |
| da_DK   | 1        | 0.27%   |
| ca_ES   | 1        | 0.27%   |
| ca_AD   | 1        | 0.27%   |
| ar_KW   | 1        | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 239      | 64.95%  |
| BIOS | 129      | 35.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Desktops | Percent |
|---------------------|----------|---------|
| Btrfs               | 239      | 65.12%  |
| Ext4                | 103      | 28.07%  |
| Xfs                 | 22       | 5.99%   |
| Zfs                 | 2        | 0.54%   |
| Fuse.fuse-overlayfs | 1        | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 223      | 59.47%  |
| GPT     | 116      | 30.93%  |
| MBR     | 36       | 9.6%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 327      | 88.14%  |
| Yes       | 44       | 11.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 289      | 77.9%   |
| Yes       | 82       | 22.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 99       | 26.98%  |
| Gigabyte Technology | 82       | 22.34%  |
| MSI                 | 52       | 14.17%  |
| ASRock              | 42       | 11.44%  |
| Hewlett-Packard     | 21       | 5.72%   |
| Dell                | 21       | 5.72%   |
| Lenovo              | 9        | 2.45%   |
| Intel               | 6        | 1.63%   |
| Unknown             | 6        | 1.63%   |
| Biostar             | 5        | 1.36%   |
| Fujitsu             | 4        | 1.09%   |
| Acer                | 4        | 1.09%   |
| Alienware           | 3        | 0.82%   |
| SYWZ                | 1        | 0.27%   |
| Positivo            | 1        | 0.27%   |
| Medion              | 1        | 0.27%   |
| Huanan              | 1        | 0.27%   |
| Google              | 1        | 0.27%   |
| Gateway             | 1        | 0.27%   |
| EVGA                | 1        | 0.27%   |
| eMachines           | 1        | 0.27%   |
| ECS                 | 1        | 0.27%   |
| Chuwi               | 1        | 0.27%   |
| BESSTAR Tech        | 1        | 0.27%   |
| ASRockRack          | 1        | 0.27%   |
| AMD                 | 1        | 0.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| MSI MS-7C37                              | 7        | 1.91%   |
| ASUS All Series                          | 7        | 1.91%   |
| Unknown                                  | 6        | 1.63%   |
| ASUS TUF GAMING X570-PLUS                | 4        | 1.09%   |
| MSI MS-7C84                              | 3        | 0.82%   |
| MSI MS-7C02                              | 3        | 0.82%   |
| Gigabyte B450M DS3H                      | 3        | 0.82%   |
| Gigabyte B450 I AORUS PRO WIFI           | 3        | 0.82%   |
| ASUS TUF GAMING B550M-PLUS               | 3        | 0.82%   |
| ASUS ROG STRIX X570-E GAMING             | 3        | 0.82%   |
| ASUS ROG STRIX B450-F GAMING             | 3        | 0.82%   |
| MSI MS-7B98                              | 2        | 0.54%   |
| MSI MS-7B85                              | 2        | 0.54%   |
| MSI MS-7A38                              | 2        | 0.54%   |
| Intel H61                                | 2        | 0.54%   |
| HP Compaq 6200 Pro SFF PC                | 2        | 0.54%   |
| Gigabyte Z170-D3H                        | 2        | 0.54%   |
| Gigabyte X570 AORUS PRO WIFI             | 2        | 0.54%   |
| Gigabyte X570 AORUS ELITE WIFI           | 2        | 0.54%   |
| Gigabyte B450 AORUS PRO WIFI             | 2        | 0.54%   |
| Gigabyte B250M-DS3H                      | 2        | 0.54%   |
| Gigabyte A320M-S2H                       | 2        | 0.54%   |
| Dell OptiPlex GX620                      | 2        | 0.54%   |
| Dell OptiPlex 9020                       | 2        | 0.54%   |
| Dell OptiPlex 7040                       | 2        | 0.54%   |
| Dell OptiPlex 3050                       | 2        | 0.54%   |
| Biostar X370GTN                          | 2        | 0.54%   |
| ASUS TUF GAMING B550-PLUS                | 2        | 0.54%   |
| ASUS ROG STRIX X570-F GAMING             | 2        | 0.54%   |
| ASUS ROG STRIX B550-I GAMING             | 2        | 0.54%   |
| ASUS ROG Maximus XI FORMULA              | 2        | 0.54%   |
| ASUS ROG CROSSHAIR VIII IMPACT           | 2        | 0.54%   |
| ASUS ROG CROSSHAIR VII HERO              | 2        | 0.54%   |
| ASUS PRIME Z390-A                        | 2        | 0.54%   |
| ASUS PRIME Z370-A                        | 2        | 0.54%   |
| ASUS PRIME B460M-A                       | 2        | 0.54%   |
| ASUS PRIME B450M-GAMING/BR               | 2        | 0.54%   |
| ASUS H110M-K                             | 2        | 0.54%   |
| ASUS A8R32-MVP Deluxe                    | 2        | 0.54%   |
| ASRock B450 Pro4                         | 2        | 0.54%   |
| ASRock AB350 Pro4                        | 2        | 0.54%   |
| ASRock A320M-HDV R4.0                    | 2        | 0.54%   |
| SYWZ S200 Series                         | 1        | 0.27%   |
| Positivo POS-MI945AA                     | 1        | 0.27%   |
| MSI Z390 Gaming Trident X Plus (MS-B926) | 1        | 0.27%   |
| MSI MS-7D18                              | 1        | 0.27%   |
| MSI MS-7D15                              | 1        | 0.27%   |
| MSI MS-7C91                              | 1        | 0.27%   |
| MSI MS-7C90                              | 1        | 0.27%   |
| MSI MS-7C82                              | 1        | 0.27%   |
| MSI MS-7C75                              | 1        | 0.27%   |
| MSI MS-7C39                              | 1        | 0.27%   |
| MSI MS-7C36                              | 1        | 0.27%   |
| MSI MS-7C35                              | 1        | 0.27%   |
| MSI MS-7B89                              | 1        | 0.27%   |
| MSI MS-7B86                              | 1        | 0.27%   |
| MSI MS-7B79                              | 1        | 0.27%   |
| MSI MS-7B48                              | 1        | 0.27%   |
| MSI MS-7B10                              | 1        | 0.27%   |
| MSI MS-7A72                              | 1        | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS ROG             | 30       | 8.17%   |
| ASUS PRIME           | 17       | 4.63%   |
| Dell OptiPlex        | 14       | 3.81%   |
| ASUS TUF             | 11       | 3%      |
| Gigabyte B450        | 8        | 2.18%   |
| MSI MS-7C37          | 7        | 1.91%   |
| ASUS All             | 7        | 1.91%   |
| HP Compaq            | 6        | 1.63%   |
| Gigabyte X570        | 6        | 1.63%   |
| Unknown              | 6        | 1.63%   |
| Lenovo ThinkCentre   | 5        | 1.36%   |
| HP EliteDesk         | 5        | 1.36%   |
| Gigabyte B450M       | 5        | 1.36%   |
| Fujitsu ESPRIMO      | 4        | 1.09%   |
| ASRock B450          | 4        | 1.09%   |
| MSI MS-7C84          | 3        | 0.82%   |
| MSI MS-7C02          | 3        | 0.82%   |
| Gigabyte Z390        | 3        | 0.82%   |
| Dell XPS             | 3        | 0.82%   |
| ASUS P8H61-M         | 3        | 0.82%   |
| ASRock X570          | 3        | 0.82%   |
| ASRock X399          | 3        | 0.82%   |
| MSI MS-7B98          | 2        | 0.54%   |
| MSI MS-7B85          | 2        | 0.54%   |
| MSI MS-7A38          | 2        | 0.54%   |
| Intel H61            | 2        | 0.54%   |
| HP ProDesk           | 2        | 0.54%   |
| HP Pavilion          | 2        | 0.54%   |
| Gigabyte Z170-D3H    | 2        | 0.54%   |
| Gigabyte X470        | 2        | 0.54%   |
| Gigabyte H310M       | 2        | 0.54%   |
| Gigabyte B550        | 2        | 0.54%   |
| Gigabyte B250M-DS3H  | 2        | 0.54%   |
| Gigabyte A320M-S2H   | 2        | 0.54%   |
| Biostar X370GTN      | 2        | 0.54%   |
| ASUS M5A97           | 2        | 0.54%   |
| ASUS M5A78L-M        | 2        | 0.54%   |
| ASUS H110M-K         | 2        | 0.54%   |
| ASUS A8R32-MVP       | 2        | 0.54%   |
| ASRock B550          | 2        | 0.54%   |
| ASRock AB350         | 2        | 0.54%   |
| ASRock A320M-HDV     | 2        | 0.54%   |
| Alienware Area-51    | 2        | 0.54%   |
| Acer Aspire          | 2        | 0.54%   |
| SYWZ S200            | 1        | 0.27%   |
| Positivo POS-MI945AA | 1        | 0.27%   |
| MSI Z390             | 1        | 0.27%   |
| MSI MS-7D18          | 1        | 0.27%   |
| MSI MS-7D15          | 1        | 0.27%   |
| MSI MS-7C91          | 1        | 0.27%   |
| MSI MS-7C90          | 1        | 0.27%   |
| MSI MS-7C82          | 1        | 0.27%   |
| MSI MS-7C75          | 1        | 0.27%   |
| MSI MS-7C39          | 1        | 0.27%   |
| MSI MS-7C36          | 1        | 0.27%   |
| MSI MS-7C35          | 1        | 0.27%   |
| MSI MS-7B89          | 1        | 0.27%   |
| MSI MS-7B86          | 1        | 0.27%   |
| MSI MS-7B79          | 1        | 0.27%   |
| MSI MS-7B48          | 1        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 67       | 18.26%  |
| 2021    | 62       | 16.89%  |
| 2019    | 60       | 16.35%  |
| 2018    | 39       | 10.63%  |
| 2016    | 20       | 5.45%   |
| 2010    | 18       | 4.9%    |
| 2015    | 17       | 4.63%   |
| 2013    | 17       | 4.63%   |
| 2014    | 13       | 3.54%   |
| 2012    | 13       | 3.54%   |
| 2009    | 12       | 3.27%   |
| 2017    | 10       | 2.72%   |
| 2011    | 9        | 2.45%   |
| 2008    | 4        | 1.09%   |
| 2006    | 3        | 0.82%   |
| 2007    | 1        | 0.27%   |
| 2005    | 1        | 0.27%   |
| Unknown | 1        | 0.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 367      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 354      | 95.42%  |
| Enabled  | 17       | 4.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 366      | 99.73%  |
| Yes  | 1        | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 105      | 28.23%  |
| 32.01-64.0  | 92       | 24.73%  |
| 8.01-16.0   | 60       | 16.13%  |
| 4.01-8.0    | 45       | 12.1%   |
| 3.01-4.0    | 28       | 7.53%   |
| 64.01-256.0 | 24       | 6.45%   |
| 24.01-32.0  | 13       | 3.49%   |
| 2.01-3.0    | 3        | 0.81%   |
| 1.01-2.0    | 2        | 0.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 117      | 28.89%  |
| 2.01-3.0   | 91       | 22.47%  |
| 3.01-4.0   | 79       | 19.51%  |
| 1.01-2.0   | 67       | 16.54%  |
| 8.01-16.0  | 24       | 5.93%   |
| 0.51-1.0   | 13       | 3.21%   |
| 16.01-24.0 | 5        | 1.23%   |
| 24.01-32.0 | 4        | 0.99%   |
| 0.01-0.5   | 4        | 0.99%   |
| 32.01-64.0 | 1        | 0.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 103      | 27.39%  |
| 3      | 98       | 26.06%  |
| 1      | 87       | 23.14%  |
| 4      | 44       | 11.7%   |
| 5      | 21       | 5.59%   |
| 8      | 7        | 1.86%   |
| 6      | 7        | 1.86%   |
| 7      | 3        | 0.8%    |
| 0      | 3        | 0.8%    |
| 12     | 2        | 0.53%   |
| 9      | 1        | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 232      | 62.7%   |
| Yes       | 138      | 37.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 360      | 98.09%  |
| No        | 7        | 1.91%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 189      | 50.81%  |
| Yes       | 183      | 49.19%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 196      | 52.97%  |
| Yes       | 174      | 47.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Desktops | Percent |
|--------------------|----------|---------|
| USA                | 80       | 21.74%  |
| Brazil             | 30       | 8.15%   |
| Germany            | 27       | 7.34%   |
| Australia          | 22       | 5.98%   |
| Russia             | 21       | 5.71%   |
| Canada             | 20       | 5.43%   |
| UK                 | 16       | 4.35%   |
| France             | 16       | 4.35%   |
| Spain              | 10       | 2.72%   |
| Poland             | 10       | 2.72%   |
| Italy              | 9        | 2.45%   |
| Switzerland        | 8        | 2.17%   |
| India              | 8        | 2.17%   |
| Ukraine            | 7        | 1.9%    |
| Sweden             | 6        | 1.63%   |
| Belgium            | 6        | 1.63%   |
| Netherlands        | 5        | 1.36%   |
| Czechia            | 5        | 1.36%   |
| Japan              | 4        | 1.09%   |
| Belarus            | 4        | 1.09%   |
| Turkey             | 3        | 0.82%   |
| Slovakia           | 3        | 0.82%   |
| Norway             | 3        | 0.82%   |
| Finland            | 3        | 0.82%   |
| Chile              | 3        | 0.82%   |
| Romania            | 2        | 0.54%   |
| New Zealand        | 2        | 0.54%   |
| Malaysia           | 2        | 0.54%   |
| Hungary            | 2        | 0.54%   |
| Estonia            | 2        | 0.54%   |
| Argentina          | 2        | 0.54%   |
| Uruguay            | 1        | 0.27%   |
| UAE                | 1        | 0.27%   |
| Taiwan             | 1        | 0.27%   |
| South Korea        | 1        | 0.27%   |
| South Africa       | 1        | 0.27%   |
| Slovenia           | 1        | 0.27%   |
| Singapore          | 1        | 0.27%   |
| Serbia             | 1        | 0.27%   |
| Portugal           | 1        | 0.27%   |
| Panama             | 1        | 0.27%   |
| Pakistan           | 1        | 0.27%   |
| Mexico             | 1        | 0.27%   |
| Martinique         | 1        | 0.27%   |
| Luxembourg         | 1        | 0.27%   |
| Kuwait             | 1        | 0.27%   |
| Kenya              | 1        | 0.27%   |
| Iran               | 1        | 0.27%   |
| Indonesia          | 1        | 0.27%   |
| Greece             | 1        | 0.27%   |
| Egypt              | 1        | 0.27%   |
| Ecuador            | 1        | 0.27%   |
| Dominican Republic | 1        | 0.27%   |
| Denmark            | 1        | 0.27%   |
| Croatia            | 1        | 0.27%   |
| Costa Rica         | 1        | 0.27%   |
| China              | 1        | 0.27%   |
| Austria            | 1        | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| Sydney             | 15       | 3.96%   |
| St Petersburg      | 7        | 1.85%   |
| Yekaterinburg      | 3        | 0.79%   |
| Ufa                | 3        | 0.79%   |
| Riverside          | 3        | 0.79%   |
| Pymble             | 3        | 0.79%   |
| Minsk              | 3        | 0.79%   |
| London             | 3        | 0.79%   |
| Kharkiv            | 3        | 0.79%   |
| Brasília          | 3        | 0.79%   |
| Berlin             | 3        | 0.79%   |
| Belo Horizonte     | 3        | 0.79%   |
| Zurich             | 2        | 0.53%   |
| Wroclaw            | 2        | 0.53%   |
| Vijayawada         | 2        | 0.53%   |
| Toronto            | 2        | 0.53%   |
| Tallinn            | 2        | 0.53%   |
| Santiago           | 2        | 0.53%   |
| Saint Paul         | 2        | 0.53%   |
| Porto Alegre       | 2        | 0.53%   |
| Pflugerville       | 2        | 0.53%   |
| Overland Park      | 2        | 0.53%   |
| Naples             | 2        | 0.53%   |
| Moscow             | 2        | 0.53%   |
| Milan              | 2        | 0.53%   |
| Miami              | 2        | 0.53%   |
| Melbourne          | 2        | 0.53%   |
| Madrid             | 2        | 0.53%   |
| Lodz               | 2        | 0.53%   |
| Kota Kinabalu      | 2        | 0.53%   |
| Istanbul           | 2        | 0.53%   |
| Honolulu           | 2        | 0.53%   |
| Hemhofen           | 2        | 0.53%   |
| Fort Worth         | 2        | 0.53%   |
| Cologne            | 2        | 0.53%   |
| Chemnitz           | 2        | 0.53%   |
| Chatel-Saint-Denis | 2        | 0.53%   |
| Brussels           | 2        | 0.53%   |
| Bratislava         | 2        | 0.53%   |
| Zuidwolde          | 1        | 0.26%   |
| Zuccoli            | 1        | 0.26%   |
| Zhukovskiy         | 1        | 0.26%   |
| Zgorzelec          | 1        | 0.26%   |
| Zaporizhzhya       | 1        | 0.26%   |
| Zagreb             | 1        | 0.26%   |
| York               | 1        | 0.26%   |
| Yokohama           | 1        | 0.26%   |
| Yogyakarta         | 1        | 0.26%   |
| Worthing           | 1        | 0.26%   |
| Woodstock          | 1        | 0.26%   |
| Woodbridge         | 1        | 0.26%   |
| Winona             | 1        | 0.26%   |
| Winnipeg           | 1        | 0.26%   |
| Wilhelmshaven      | 1        | 0.26%   |
| Wichita            | 1        | 0.26%   |
| West Henrietta     | 1        | 0.26%   |
| Welland            | 1        | 0.26%   |
| Watsonville        | 1        | 0.26%   |
| Waterville         | 1        | 0.26%   |
| Waterloo           | 1        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 137      | 280    | 18%     |
| WDC                       | 130      | 202    | 17.08%  |
| Seagate                   | 125      | 212    | 16.43%  |
| Kingston                  | 50       | 61     | 6.57%   |
| Crucial                   | 46       | 66     | 6.04%   |
| Toshiba                   | 36       | 58     | 4.73%   |
| SanDisk                   | 35       | 40     | 4.6%    |
| Hitachi                   | 26       | 36     | 3.42%   |
| Intel                     | 22       | 31     | 2.89%   |
| Phison                    | 16       | 21     | 2.1%    |
| A-DATA Technology         | 11       | 14     | 1.45%   |
| Corsair                   | 9        | 12     | 1.18%   |
| Unknown                   | 8        | 10     | 1.05%   |
| Micron Technology         | 8        | 10     | 1.05%   |
| SK Hynix                  | 7        | 10     | 0.92%   |
| PNY                       | 6        | 9      | 0.79%   |
| OCZ                       | 6        | 11     | 0.79%   |
| Micron/Crucial Technology | 6        | 7      | 0.79%   |
| XPG                       | 5        | 6      | 0.66%   |
| SPCC                      | 4        | 4      | 0.53%   |
| Silicon Motion            | 4        | 4      | 0.53%   |
| Patriot                   | 4        | 4      | 0.53%   |
| Maxtor                    | 4        | 5      | 0.53%   |
| HGST                      | 4        | 13     | 0.53%   |
| Team                      | 3        | 4      | 0.39%   |
| SABRENT                   | 3        | 3      | 0.39%   |
| KingSpec                  | 3        | 5      | 0.39%   |
| Gigabyte Technology       | 3        | 4      | 0.39%   |
| Transcend                 | 2        | 2      | 0.26%   |
| Phison Electronics        | 2        | 2      | 0.26%   |
| LITEONIT                  | 2        | 2      | 0.26%   |
| ASMT                      | 2        | 2      | 0.26%   |
| Apple                     | 2        | 2      | 0.26%   |
| Apacer                    | 2        | 3      | 0.26%   |
| USB 3.0                   | 1        | 1      | 0.13%   |
| Union Memory              | 1        | 1      | 0.13%   |
| Ugreen                    | 1        | 1      | 0.13%   |
| Synology                  | 1        | 1      | 0.13%   |
| SSK                       | 1        | 1      | 0.13%   |
| Smartbuy                  | 1        | 1      | 0.13%   |
| SMART                     | 1        | 1      | 0.13%   |
| Realtek Semiconductor     | 1        | 1      | 0.13%   |
| PLEXTOR                   | 1        | 2      | 0.13%   |
| PHD 3.0                   | 1        | 1      | 0.13%   |
| OWC                       | 1        | 1      | 0.13%   |
| Mushkin                   | 1        | 3      | 0.13%   |
| MG                        | 1        | 1      | 0.13%   |
| MaxDigital                | 1        | 1      | 0.13%   |
| LITEON                    | 1        | 1      | 0.13%   |
| Lexar                     | 1        | 1      | 0.13%   |
| KLEVV                     | 1        | 1      | 0.13%   |
| JMicron                   | 1        | 1      | 0.13%   |
| Intenso                   | 1        | 1      | 0.13%   |
| Inateck                   | 1        | 1      | 0.13%   |
| Hoodisk                   | 1        | 2      | 0.13%   |
| Hewlett-Packard           | 1        | 1      | 0.13%   |
| GOODRAM                   | 1        | 1      | 0.13%   |
| DREVO                     | 1        | 1      | 0.13%   |
| DOGFISH                   | 1        | 1      | 0.13%   |
| CT1000P1                  | 1        | 2      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Samsung SSD 860 EVO 1TB            | 18       | 1.93%   |
| Seagate ST2000DM008-2FR102 2TB     | 13       | 1.39%   |
| Samsung SSD 860 EVO 500GB          | 13       | 1.39%   |
| Samsung NVMe SSD Drive 500GB       | 13       | 1.39%   |
| Samsung SSD 850 EVO 250GB          | 11       | 1.18%   |
| Samsung NVMe SSD Drive 250GB       | 11       | 1.18%   |
| Samsung NVMe SSD Drive 1TB         | 11       | 1.18%   |
| Seagate ST500DM002-1BD142 500GB    | 10       | 1.07%   |
| Samsung SSD 850 EVO 500GB          | 10       | 1.07%   |
| Seagate ST1000DM010-2EP102 1TB     | 9        | 0.96%   |
| Sandisk NVMe SSD Drive 500GB       | 9        | 0.96%   |
| Kingston SA400S37240G 240GB SSD    | 8        | 0.86%   |
| Kingston SA400S37120G 120GB SSD    | 8        | 0.86%   |
| Crucial CT500MX500SSD1 500GB       | 8        | 0.86%   |
| Toshiba DT01ACA100 1TB             | 7        | 0.75%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 6        | 0.64%   |
| Seagate ST3500418AS 500GB          | 6        | 0.64%   |
| Seagate ST1000DM003-1ER162 1TB     | 6        | 0.64%   |
| Samsung SSD 840 EVO 250GB          | 6        | 0.64%   |
| Kingston SA400S37480G 480GB SSD    | 6        | 0.64%   |
| WDC WDS100T2B0C-00PXH0 1TB         | 5        | 0.53%   |
| Toshiba DT01ACA200 2TB             | 5        | 0.53%   |
| Seagate ST4000DM004-2CV104 4TB     | 5        | 0.53%   |
| Seagate ST1000DM003-1SB102 1TB     | 5        | 0.53%   |
| Sandisk NVMe SSD Drive 1TB         | 5        | 0.53%   |
| Samsung SSD 970 EVO Plus 1TB       | 5        | 0.53%   |
| Samsung SSD 970 EVO 500GB          | 5        | 0.53%   |
| Samsung SSD 860 QVO 1TB            | 5        | 0.53%   |
| Phison NVMe SSD Drive 1024GB       | 5        | 0.53%   |
| Micron/Crucial NVMe SSD Drive 1TB  | 5        | 0.53%   |
| Kingston SV300S37A120G 120GB SSD   | 5        | 0.53%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 4        | 0.43%   |
| WDC WD10EZEX-08WN4A0 1TB           | 4        | 0.43%   |
| WDC WD10EZEX-00BN5A0 1TB           | 4        | 0.43%   |
| Unknown SD/MMC/MS PRO 128GB        | 4        | 0.43%   |
| Seagate ST2000DM001-1ER164 2TB     | 4        | 0.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4        | 0.43%   |
| Samsung SSD 970 EVO Plus 500GB     | 4        | 0.43%   |
| Samsung SSD 870 EVO 1TB            | 4        | 0.43%   |
| Samsung NVMe SSD Drive 512GB       | 4        | 0.43%   |
| Hitachi HDS721010CLA332 1TB        | 4        | 0.43%   |
| Crucial CT240BX500SSD1 240GB       | 4        | 0.43%   |
| Crucial CT1000MX500SSD1 1TB        | 4        | 0.43%   |
| Crucial CT1000BX500SSD1 1TB        | 4        | 0.43%   |
| XPG NVMe SSD Drive 512GB           | 3        | 0.32%   |
| WDC WDS500G2B0B-00YS70 500GB SSD   | 3        | 0.32%   |
| WDC WDS100T1X0E-00AFY0 1TB         | 3        | 0.32%   |
| WDC WD40EFRX-68N32N0 4TB           | 3        | 0.32%   |
| WDC WD30EFRX-68EUZN0 3TB           | 3        | 0.32%   |
| WDC WD10EZEX-75WN4A0 1TB           | 3        | 0.32%   |
| WDC WD10EZEX-08M2NA0 1TB           | 3        | 0.32%   |
| Toshiba TR200 240GB SSD            | 3        | 0.32%   |
| Toshiba NVMe SSD Drive 512GB       | 3        | 0.32%   |
| Toshiba HDWD120 2TB                | 3        | 0.32%   |
| Toshiba HDWD110 1TB                | 3        | 0.32%   |
| Seagate ST3500413AS 500GB          | 3        | 0.32%   |
| Seagate ST3000DM008-2DM166 3TB     | 3        | 0.32%   |
| Seagate ST1000DM003-1CH162 1TB     | 3        | 0.32%   |
| Samsung SSD 980 PRO 1TB            | 3        | 0.32%   |
| Samsung SSD 970 PRO 512GB          | 3        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 120      | 202    | 38.59%  |
| WDC                 | 107      | 164    | 34.41%  |
| Toshiba             | 26       | 43     | 8.36%   |
| Hitachi             | 26       | 36     | 8.36%   |
| Samsung Electronics | 17       | 27     | 5.47%   |
| HGST                | 4        | 13     | 1.29%   |
| Maxtor              | 3        | 3      | 0.96%   |
| ASMT                | 2        | 2      | 0.64%   |
| Synology            | 1        | 1      | 0.32%   |
| PHD 3.0             | 1        | 1      | 0.32%   |
| MaxDigital          | 1        | 1      | 0.32%   |
| Inateck             | 1        | 1      | 0.32%   |
| Hewlett-Packard     | 1        | 1      | 0.32%   |
| Apple               | 1        | 1      | 0.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 88       | 154    | 29.33%  |
| Crucial             | 41       | 60     | 13.67%  |
| Kingston            | 38       | 47     | 12.67%  |
| WDC                 | 19       | 23     | 6.33%   |
| SanDisk             | 19       | 20     | 6.33%   |
| A-DATA Technology   | 11       | 14     | 3.67%   |
| Intel               | 8        | 13     | 2.67%   |
| Toshiba             | 7        | 8      | 2.33%   |
| PNY                 | 6        | 8      | 2%      |
| OCZ                 | 6        | 11     | 2%      |
| Micron Technology   | 6        | 8      | 2%      |
| SK Hynix            | 4        | 4      | 1.33%   |
| Patriot             | 4        | 4      | 1.33%   |
| Team                | 3        | 4      | 1%      |
| SABRENT             | 3        | 3      | 1%      |
| KingSpec            | 3        | 5      | 1%      |
| Unknown             | 2        | 2      | 0.67%   |
| Transcend           | 2        | 2      | 0.67%   |
| SPCC                | 2        | 2      | 0.67%   |
| LITEONIT            | 2        | 2      | 0.67%   |
| Gigabyte Technology | 2        | 3      | 0.67%   |
| Corsair             | 2        | 3      | 0.67%   |
| Apacer              | 2        | 3      | 0.67%   |
| Smartbuy            | 1        | 1      | 0.33%   |
| SMART               | 1        | 1      | 0.33%   |
| Seagate             | 1        | 1      | 0.33%   |
| PLEXTOR             | 1        | 2      | 0.33%   |
| OWC                 | 1        | 1      | 0.33%   |
| Mushkin             | 1        | 3      | 0.33%   |
| MG                  | 1        | 1      | 0.33%   |
| Maxtor              | 1        | 2      | 0.33%   |
| LITEON              | 1        | 1      | 0.33%   |
| Lexar               | 1        | 1      | 0.33%   |
| KLEVV               | 1        | 1      | 0.33%   |
| JMicron             | 1        | 1      | 0.33%   |
| Intenso             | 1        | 1      | 0.33%   |
| Hoodisk             | 1        | 2      | 0.33%   |
| GOODRAM             | 1        | 1      | 0.33%   |
| DREVO               | 1        | 1      | 0.33%   |
| DOGFISH             | 1        | 1      | 0.33%   |
| CT1000P1            | 1        | 2      | 0.33%   |
| China               | 1        | 1      | 0.33%   |
| Apple               | 1        | 1      | 0.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 243      | 429    | 37.85%  |
| HDD     | 235      | 496    | 36.6%   |
| NVMe    | 151      | 245    | 23.52%  |
| Unknown | 12       | 17     | 1.87%   |
| MMC     | 1        | 1      | 0.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 335      | 897    | 64.18%  |
| NVMe | 151      | 245    | 28.93%  |
| SAS  | 35       | 45     | 6.7%    |
| MMC  | 1        | 1      | 0.19%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 244      | 449    | 44.61%  |
| 0.51-1.0   | 169      | 270    | 30.9%   |
| 1.01-2.0   | 67       | 88     | 12.25%  |
| 3.01-4.0   | 26       | 43     | 4.75%   |
| 4.01-10.0  | 22       | 48     | 4.02%   |
| 2.01-3.0   | 15       | 17     | 2.74%   |
| 10.01-20.0 | 4        | 10     | 0.73%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 68       | 17.75%  |
| 251-500        | 61       | 15.93%  |
| More than 3000 | 59       | 15.4%   |
| 1001-2000      | 58       | 15.14%  |
| 101-250        | 54       | 14.1%   |
| 2001-3000      | 32       | 8.36%   |
| 1-20           | 22       | 5.74%   |
| Unknown        | 16       | 4.18%   |
| 51-100         | 8        | 2.09%   |
| 21-50          | 5        | 1.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 76       | 19.39%  |
| 21-50          | 59       | 15.05%  |
| 101-250        | 54       | 13.78%  |
| 501-1000       | 51       | 13.01%  |
| 251-500        | 39       | 9.95%   |
| 51-100         | 38       | 9.69%   |
| 1001-2000      | 33       | 8.42%   |
| More than 3000 | 16       | 4.08%   |
| Unknown        | 16       | 4.08%   |
| 2001-3000      | 10       | 2.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB    | 3        | 15     | 8.82%   |
| Intel SSDSC2CT120A3 120GB          | 3        | 5      | 8.82%   |
| Toshiba DT01ACA200 2TB             | 2        | 4      | 5.88%   |
| WDC WD60EFAX-68SHWN0 6TB           | 1        | 1      | 2.94%   |
| WDC WD40PURZ-85AKKY0 4TB           | 1        | 1      | 2.94%   |
| WDC WD30EZRX-00AZ6B0 3TB           | 1        | 1      | 2.94%   |
| WDC WD15EARS-00Z5B1 1TB            | 1        | 1      | 2.94%   |
| WDC WD1003FBYX-01Y7B1 1TB          | 1        | 1      | 2.94%   |
| Seagate ST4000DM000-1F2168 4TB     | 1        | 1      | 2.94%   |
| Seagate ST3500630AS 500GB          | 1        | 1      | 2.94%   |
| Seagate ST31000340NS 1TB           | 1        | 1      | 2.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 2.94%   |
| Seagate ST1000DX001-1CM162 1TB     | 1        | 1      | 2.94%   |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 1      | 2.94%   |
| SanDisk SSD U100 64GB              | 1        | 1      | 2.94%   |
| SanDisk SSD PLUS 480GB             | 1        | 1      | 2.94%   |
| SanDisk SDSSDX240GG25 240GB        | 1        | 1      | 2.94%   |
| Samsung Electronics SP2514N 250GB  | 1        | 1      | 2.94%   |
| Samsung Electronics SP2004C 200GB  | 1        | 1      | 2.94%   |
| Samsung Electronics HM160HI 160GB  | 1        | 2      | 2.94%   |
| Samsung Electronics HD501LJ 500GB  | 1        | 6      | 2.94%   |
| Intel SSDSC2BW240A4 240GB          | 1        | 1      | 2.94%   |
| Intel SSDPEKKW128G7 128GB          | 1        | 1      | 2.94%   |
| Hitachi HTS725050A7E630 500GB      | 1        | 1      | 2.94%   |
| Hitachi HDS721050CLA362 500GB      | 1        | 1      | 2.94%   |
| Crucial CT275MX300SSD1 275GB       | 1        | 1      | 2.94%   |
| Crucial CT128MX100SSD1 128GB       | 1        | 1      | 2.94%   |
| A-DATA Technology SP900 256GB SSD  | 1        | 1      | 2.94%   |
| A-DATA Technology SP900 128GB SSD  | 1        | 2      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 21     | 26.47%  |
| WDC                 | 5        | 5      | 14.71%  |
| Intel               | 5        | 7      | 14.71%  |
| Samsung Electronics | 4        | 10     | 11.76%  |
| SanDisk             | 3        | 3      | 8.82%   |
| Toshiba             | 2        | 4      | 5.88%   |
| Hitachi             | 2        | 2      | 5.88%   |
| Crucial             | 2        | 2      | 5.88%   |
| A-DATA Technology   | 2        | 3      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 21     | 40.91%  |
| WDC                 | 5        | 5      | 22.73%  |
| Samsung Electronics | 4        | 10     | 18.18%  |
| Toshiba             | 2        | 4      | 9.09%   |
| Hitachi             | 2        | 2      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 42     | 63.64%  |
| SSD  | 11       | 14     | 33.33%  |
| NVMe | 1        | 1      | 3.03%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Hitachi HDS721010DLE630 1TB | 1        | 4      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 1        | 4      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 234      | 703    | 56.39%  |
| Works    | 148      | 424    | 35.66%  |
| Malfunc  | 32       | 57     | 7.71%   |
| Failed   | 1        | 4      | 0.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 199      | 33.56%  |
| AMD                          | 162      | 27.32%  |
| Samsung Electronics          | 66       | 11.13%  |
| ASMedia Technology           | 28       | 4.72%   |
| Sandisk                      | 27       | 4.55%   |
| Phison Electronics           | 27       | 4.55%   |
| Kingston Technology Company  | 12       | 2.02%   |
| Micron/Crucial Technology    | 11       | 1.85%   |
| Nvidia                       | 8        | 1.35%   |
| JMicron Technology           | 7        | 1.18%   |
| Marvell Technology Group     | 6        | 1.01%   |
| ADATA Technology             | 6        | 1.01%   |
| Toshiba America Info Systems | 5        | 0.84%   |
| Silicon Motion               | 4        | 0.67%   |
| Broadcom / LSI               | 4        | 0.67%   |
| SK Hynix                     | 3        | 0.51%   |
| LSI Logic / Symbios Logic    | 3        | 0.51%   |
| ULi Electronics              | 2        | 0.34%   |
| Silicon Image                | 2        | 0.34%   |
| Seagate Technology           | 2        | 0.34%   |
| Realtek Semiconductor        | 2        | 0.34%   |
| Micron Technology            | 2        | 0.34%   |
| VIA Technologies             | 1        | 0.17%   |
| Union Memory (Shenzhen)      | 1        | 0.17%   |
| Lite-On IT Corp. / Plextor   | 1        | 0.17%   |
| Hewlett-Packard              | 1        | 0.17%   |
| Adaptec                      | 1        | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 112      | 15.62%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 45       | 6.28%   |
| AMD 400 Series Chipset SATA Controller                                                  | 42       | 5.86%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 28       | 3.91%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 26       | 3.63%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 23       | 3.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 22       | 3.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 21       | 2.93%   |
| Intel SATA Controller [RAID mode]                                                       | 16       | 2.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15       | 2.09%   |
| Phison E12 NVMe Controller                                                              | 14       | 1.95%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 13       | 1.81%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 12       | 1.67%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 12       | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 12       | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 12       | 1.67%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 10       | 1.39%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 10       | 1.39%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10       | 1.39%   |
| AMD FCH SATA Controller D                                                               | 10       | 1.39%   |
| AMD 300 Series Chipset SATA Controller                                                  | 10       | 1.39%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 9        | 1.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 9        | 1.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 9        | 1.26%   |
| Kingston Company A2000 NVMe SSD                                                         | 7        | 0.98%   |
| Intel SSD 660P Series                                                                   | 7        | 0.98%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 7        | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7        | 0.98%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 5        | 0.7%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 0.7%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 0.7%    |
| AMD X399 Series Chipset SATA Controller                                                 | 5        | 0.7%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 5        | 0.7%    |
| Sandisk WD Black SN850                                                                  | 4        | 0.56%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 4        | 0.56%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 4        | 0.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 0.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 0.56%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 0.56%   |
| AMD FCH IDE Controller                                                                  | 4        | 0.56%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 0.42%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 0.42%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 0.42%   |
| Nvidia MCP61 IDE                                                                        | 3        | 0.42%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3        | 0.42%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 3        | 0.42%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 3        | 0.42%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 0.42%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 0.42%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 0.42%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 0.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 0.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 0.42%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 0.42%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 0.42%   |
| ULi ULi M5288 SATA                                                                      | 2        | 0.28%   |
| ULi M5229 IDE                                                                           | 2        | 0.28%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2        | 0.28%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 2        | 0.28%   |
| SK Hynix NVMe SSD Controller                                                            | 2        | 0.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 320      | 57.55%  |
| NVMe | 151      | 27.16%  |
| IDE  | 54       | 9.71%   |
| RAID | 26       | 4.68%   |
| SCSI | 3        | 0.54%   |
| SAS  | 2        | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 197      | 53.68%  |
| AMD    | 170      | 46.32%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor               | 14       | 3.8%    |
| AMD Ryzen 9 3900X 12-Core Processor             | 12       | 3.26%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 10       | 2.72%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 9        | 2.45%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 9        | 2.45%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 7        | 1.9%    |
| AMD Ryzen 5 2600 Six-Core Processor             | 7        | 1.9%    |
| Intel Core i7-4790K CPU @ 4.00GHz               | 6        | 1.63%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 6        | 1.63%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 6        | 1.63%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 6        | 1.63%   |
| AMD Ryzen 9 3950X 16-Core Processor             | 6        | 1.63%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 6        | 1.63%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 5        | 1.36%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics     | 5        | 1.36%   |
| Intel Core i9-9900K CPU @ 3.60GHz               | 4        | 1.09%   |
| Intel Core i7-6700K CPU @ 4.00GHz               | 4        | 1.09%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 4        | 1.09%   |
| Intel Core i5-7500 CPU @ 3.40GHz                | 4        | 1.09%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 4        | 1.09%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 4        | 1.09%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 4        | 1.09%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 4        | 1.09%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics     | 4        | 1.09%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 3        | 0.82%   |
| Intel Core i7-10700K CPU @ 3.80GHz              | 3        | 0.82%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 3        | 0.82%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 3        | 0.82%   |
| Intel Core i5-3570 CPU @ 3.40GHz                | 3        | 0.82%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 3        | 0.82%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 3        | 0.82%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 3        | 0.82%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz          | 3        | 0.82%   |
| AMD Ryzen 7 3800X 8-Core Processor              | 3        | 0.82%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 3        | 0.82%   |
| AMD FX-8350 Eight-Core Processor                | 3        | 0.82%   |
| AMD Athlon 64 X2 Dual Core Processor 4400+      | 3        | 0.82%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 3        | 0.82%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz             | 2        | 0.54%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 2        | 0.54%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz     | 2        | 0.54%   |
| Intel Core i9-9900KF CPU @ 3.60GHz              | 2        | 0.54%   |
| Intel Core i7-9700K CPU @ 3.60GHz               | 2        | 0.54%   |
| Intel Core i7-9700 CPU @ 3.00GHz                | 2        | 0.54%   |
| Intel Core i7-8700K CPU @ 3.70GHz               | 2        | 0.54%   |
| Intel Core i7-7700K CPU @ 4.20GHz               | 2        | 0.54%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 2        | 0.54%   |
| Intel Core i7-6800K CPU @ 3.40GHz               | 2        | 0.54%   |
| Intel Core i7-4770 CPU @ 3.40GHz                | 2        | 0.54%   |
| Intel Core i7 CPU 920 @ 2.67GHz                 | 2        | 0.54%   |
| Intel Core i5-9400F CPU @ 2.90GHz               | 2        | 0.54%   |
| Intel Core i5-7600K CPU @ 3.80GHz               | 2        | 0.54%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 2        | 0.54%   |
| Intel Core i5-4690K CPU @ 3.50GHz               | 2        | 0.54%   |
| Intel Core i5-4440 CPU @ 3.10GHz                | 2        | 0.54%   |
| Intel Core i5-3330 CPU @ 3.00GHz                | 2        | 0.54%   |
| Intel Core i5-10400F CPU @ 2.90GHz              | 2        | 0.54%   |
| Intel Core i3-8100 CPU @ 3.60GHz                | 2        | 0.54%   |
| Intel Core i3-4150 CPU @ 3.50GHz                | 2        | 0.54%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 2        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 58       | 15.8%   |
| AMD Ryzen 5             | 58       | 15.8%   |
| Intel Core i7           | 55       | 14.99%  |
| AMD Ryzen 7             | 30       | 8.17%   |
| AMD Ryzen 9             | 29       | 7.9%    |
| Intel Core i3           | 20       | 5.45%   |
| Intel Xeon              | 19       | 5.18%   |
| AMD FX                  | 9        | 2.45%   |
| AMD Ryzen 3             | 8        | 2.18%   |
| Intel Core i9           | 7        | 1.91%   |
| Intel Celeron           | 7        | 1.91%   |
| Intel Core 2 Duo        | 6        | 1.63%   |
| Intel Pentium Dual-Core | 5        | 1.36%   |
| Intel Pentium           | 5        | 1.36%   |
| Intel Core 2 Quad       | 5        | 1.36%   |
| AMD Ryzen Threadripper  | 5        | 1.36%   |
| AMD A10                 | 5        | 1.36%   |
| Other                   | 4        | 1.09%   |
| AMD Athlon 64 X2        | 4        | 1.09%   |
| AMD Phenom II X2        | 3        | 0.82%   |
| Intel Pentium D         | 2        | 0.54%   |
| AMD Ryzen 5 PRO         | 2        | 0.54%   |
| AMD Phenom II X6        | 2        | 0.54%   |
| AMD Phenom II X4        | 2        | 0.54%   |
| AMD Athlon II X2        | 2        | 0.54%   |
| AMD Athlon Dual Core    | 2        | 0.54%   |
| Intel Pentium Dual      | 1        | 0.27%   |
| Intel Pentium 4         | 1        | 0.27%   |
| Intel Core 2            | 1        | 0.27%   |
| Intel Atom              | 1        | 0.27%   |
| AMD Ryzen 7 PRO         | 1        | 0.27%   |
| AMD E2                  | 1        | 0.27%   |
| AMD E                   | 1        | 0.27%   |
| AMD Athlon X2           | 1        | 0.27%   |
| AMD Athlon II X4        | 1        | 0.27%   |
| AMD Athlon              | 1        | 0.27%   |
| AMD A8                  | 1        | 0.27%   |
| AMD A6                  | 1        | 0.27%   |
| AMD A4                  | 1        | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 134      | 36.41%  |
| 6      | 80       | 21.74%  |
| 2      | 62       | 16.85%  |
| 8      | 51       | 13.86%  |
| 12     | 22       | 5.98%   |
| 16     | 12       | 3.26%   |
| 1      | 3        | 0.82%   |
| 3      | 2        | 0.54%   |
| 24     | 1        | 0.27%   |
| 10     | 1        | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 363      | 98.91%  |
| 2      | 4        | 1.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 240      | 65.04%  |
| 1      | 129      | 34.96%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 367      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 32       | 8.67%   |
| 0x08701021 | 32       | 8.67%   |
| Unknown    | 24       | 6.5%    |
| 0x506e3    | 19       | 5.15%   |
| 0x0800820d | 18       | 4.88%   |
| 0x306a9    | 17       | 4.61%   |
| 0x1067a    | 17       | 4.61%   |
| 0x0a201009 | 17       | 4.61%   |
| 0x906e9    | 15       | 4.07%   |
| 0x08701013 | 15       | 4.07%   |
| 0x206a7    | 14       | 3.79%   |
| 0x906ea    | 13       | 3.52%   |
| 0x906ed    | 9        | 2.44%   |
| 0x0a201016 | 8        | 2.17%   |
| 0x08108109 | 8        | 2.17%   |
| 0xa0655    | 7        | 1.9%    |
| 0x08101016 | 6        | 1.63%   |
| 0x08001138 | 5        | 1.36%   |
| 0x08001137 | 5        | 1.36%   |
| 0xa0671    | 4        | 1.08%   |
| 0xa0653    | 4        | 1.08%   |
| 0x906ec    | 4        | 1.08%   |
| 0x906eb    | 3        | 0.81%   |
| 0x106e5    | 3        | 0.81%   |
| 0x106a5    | 3        | 0.81%   |
| 0x0810100b | 3        | 0.81%   |
| 0x06003106 | 3        | 0.81%   |
| 0x06001119 | 3        | 0.81%   |
| 0x010000c8 | 3        | 0.81%   |
| 0xf47      | 2        | 0.54%   |
| 0x806ea    | 2        | 0.54%   |
| 0x50654    | 2        | 0.54%   |
| 0x406f1    | 2        | 0.54%   |
| 0x306f2    | 2        | 0.54%   |
| 0x08600103 | 2        | 0.54%   |
| 0x08108102 | 2        | 0.54%   |
| 0x06000822 | 2        | 0.54%   |
| 0x0600081c | 2        | 0.54%   |
| 0x06000817 | 2        | 0.54%   |
| 0x06000629 | 2        | 0.54%   |
| 0x00000000 | 2        | 0.54%   |
| 0xf43      | 1        | 0.27%   |
| 0x706a8    | 1        | 0.27%   |
| 0x706a1    | 1        | 0.27%   |
| 0x6fd      | 1        | 0.27%   |
| 0x6fb      | 1        | 0.27%   |
| 0x6f6      | 1        | 0.27%   |
| 0x50657    | 1        | 0.27%   |
| 0x406c4    | 1        | 0.27%   |
| 0x40651    | 1        | 0.27%   |
| 0x30661    | 1        | 0.27%   |
| 0x206d7    | 1        | 0.27%   |
| 0x20655    | 1        | 0.27%   |
| 0x106a4    | 1        | 0.27%   |
| 0x10676    | 1        | 0.27%   |
| 0x0a50000c | 1        | 0.27%   |
| 0x08600106 | 1        | 0.27%   |
| 0x08600104 | 1        | 0.27%   |
| 0x0800820b | 1        | 0.27%   |
| 0x08008206 | 1        | 0.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 2         | 52       | 14.17%  |
| KabyLake      | 50       | 13.62%  |
| Haswell       | 38       | 10.35%  |
| Zen+          | 33       | 8.99%   |
| Zen 3         | 26       | 7.08%   |
| Zen           | 22       | 5.99%   |
| Skylake       | 22       | 5.99%   |
| Penryn        | 18       | 4.9%    |
| IvyBridge     | 18       | 4.9%    |
| SandyBridge   | 15       | 4.09%   |
| CometLake     | 12       | 3.27%   |
| K10           | 11       | 3%      |
| Piledriver    | 10       | 2.72%   |
| Nehalem       | 7        | 1.91%   |
| K8 Hammer     | 6        | 1.63%   |
| Icelake       | 4        | 1.09%   |
| Steamroller   | 3        | 0.82%   |
| NetBurst      | 3        | 0.82%   |
| Core          | 3        | 0.82%   |
| Goldmont plus | 2        | 0.54%   |
| Excavator     | 2        | 0.54%   |
| Bulldozer     | 2        | 0.54%   |
| Broadwell     | 2        | 0.54%   |
| Westmere      | 1        | 0.27%   |
| Silvermont    | 1        | 0.27%   |
| Puma          | 1        | 0.27%   |
| Jaguar        | 1        | 0.27%   |
| Bonnell       | 1        | 0.27%   |
| Bobcat        | 1        | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 167      | 41.34%  |
| AMD                        | 143      | 35.4%   |
| Intel                      | 92       | 22.77%  |
| Matrox Electronics Systems | 1        | 0.25%   |
| ASPEED Technology          | 1        | 0.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 36       | 8.74%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 17       | 4.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 15       | 3.64%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 12       | 2.91%   |
| Nvidia GK208B [GeForce GT 710]                                              | 11       | 2.67%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 10       | 2.43%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 10       | 2.43%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 10       | 2.43%   |
| Intel HD Graphics 630                                                       | 9        | 2.18%   |
| Intel HD Graphics 530                                                       | 9        | 2.18%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9        | 2.18%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 9        | 2.18%   |
| AMD Picasso                                                                 | 9        | 2.18%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 7        | 1.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 7        | 1.7%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 6        | 1.46%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 6        | 1.46%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 5        | 1.21%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 5        | 1.21%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 5        | 1.21%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 5        | 1.21%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 5        | 1.21%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 4        | 0.97%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4        | 0.97%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 4        | 0.97%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 4        | 0.97%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 4        | 0.97%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 4        | 0.97%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 0.97%   |
| Nvidia GA106 [GeForce RTX 3060]                                             | 4        | 0.97%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 0.97%   |
| AMD Renoir                                                                  | 4        | 0.97%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 0.97%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 0.73%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 0.73%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 0.73%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 0.73%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 0.73%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 3        | 0.73%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 0.73%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 3        | 0.73%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 0.73%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 3        | 0.73%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 0.49%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 0.49%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 0.49%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.49%   |
| Nvidia GP107GL [Quadro P1000]                                               | 2        | 0.49%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 0.49%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 2        | 0.49%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 0.49%   |
| Nvidia GF108 [GeForce GT 730]                                               | 2        | 0.49%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 2        | 0.49%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 2        | 0.49%   |
| Intel UHD Graphics 620                                                      | 2        | 0.49%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 2        | 0.49%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2        | 0.49%   |
| AMD Vega 20 [Radeon VII]                                                    | 2        | 0.49%   |
| AMD RV530 [Radeon X1600] (Secondary)                                        | 2        | 0.49%   |
| AMD RV530 [Radeon X1600 PRO]                                                | 2        | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 145      | 39.3%   |
| 1 x AMD        | 132      | 35.77%  |
| 1 x Intel      | 62       | 16.8%   |
| Intel + Nvidia | 13       | 3.52%   |
| 2 x Nvidia     | 5        | 1.36%   |
| AMD + Nvidia   | 4        | 1.08%   |
| 2 x AMD        | 3        | 0.81%   |
| Intel + AMD    | 2        | 0.54%   |
| Other          | 1        | 0.27%   |
| 1 x Matrox     | 1        | 0.27%   |
| 1 x ASPEED     | 1        | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 273      | 73.39%  |
| Proprietary | 91       | 24.46%  |
| Unknown     | 8        | 2.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 116      | 30.85%  |
| 7.01-8.0   | 63       | 16.76%  |
| 1.01-2.0   | 50       | 13.3%   |
| 3.01-4.0   | 45       | 11.97%  |
| 0.51-1.0   | 39       | 10.37%  |
| 0.01-0.5   | 22       | 5.85%   |
| 5.01-6.0   | 21       | 5.59%   |
| 8.01-16.0  | 14       | 3.72%   |
| 2.01-3.0   | 5        | 1.33%   |
| 16.01-24.0 | 1        | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 67       | 15.76%  |
| Samsung Electronics  | 63       | 14.82%  |
| Dell                 | 52       | 12.24%  |
| Acer                 | 29       | 6.82%   |
| BenQ                 | 28       | 6.59%   |
| AOC                  | 24       | 5.65%   |
| Iiyama               | 19       | 4.47%   |
| Philips              | 18       | 4.24%   |
| Hewlett-Packard      | 17       | 4%      |
| Ancor Communications | 15       | 3.53%   |
| ViewSonic            | 8        | 1.88%   |
| Lenovo               | 8        | 1.88%   |
| ASUSTek Computer     | 7        | 1.65%   |
| Sceptre Tech         | 6        | 1.41%   |
| ___                  | 5        | 1.18%   |
| Unknown              | 5        | 1.18%   |
| MSI                  | 5        | 1.18%   |
| Vizio                | 4        | 0.94%   |
| Sony                 | 3        | 0.71%   |
| NEC Computers        | 3        | 0.71%   |
| Vestel Elektronik    | 2        | 0.47%   |
| Mi                   | 2        | 0.47%   |
| HannStar             | 2        | 0.47%   |
| eMachines            | 2        | 0.47%   |
| Zoran                | 1        | 0.24%   |
| Unknown (XXX)        | 1        | 0.24%   |
| Toshiba              | 1        | 0.24%   |
| RZR                  | 1        | 0.24%   |
| RIS                  | 1        | 0.24%   |
| Pixio                | 1        | 0.24%   |
| Packard Bell         | 1        | 0.24%   |
| OUT                  | 1        | 0.24%   |
| Onkyo                | 1        | 0.24%   |
| NEW                  | 1        | 0.24%   |
| Mitsubishi           | 1        | 0.24%   |
| Microstep            | 1        | 0.24%   |
| Medion Akoya         | 1        | 0.24%   |
| Medion               | 1        | 0.24%   |
| Marantz              | 1        | 0.24%   |
| LG Electronics       | 1        | 0.24%   |
| KTC                  | 1        | 0.24%   |
| IPS                  | 1        | 0.24%   |
| Insignia             | 1        | 0.24%   |
| IBM                  | 1        | 0.24%   |
| HYO                  | 1        | 0.24%   |
| Huion                | 1        | 0.24%   |
| Hitachi              | 1        | 0.24%   |
| GKK                  | 1        | 0.24%   |
| Gigabyte Technology  | 1        | 0.24%   |
| Fujitsu Siemens      | 1        | 0.24%   |
| Envision Peripherals | 1        | 0.24%   |
| Element              | 1        | 0.24%   |
| Eizo                 | 1        | 0.24%   |
| CHE                  | 1        | 0.24%   |
| Apple                | 1        | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch                           | 6        | 1.29%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                                | 4        | 0.86%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                                | 4        | 0.86%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                                     | 4        | 0.86%   |
| ___ Monitor ranges (GTF): 48-62Hz V, 14-68kHz H, max dotclock 150MHz ___9000 1440x900 | 3        | 0.64%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch                         | 3        | 0.64%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch                     | 3        | 0.64%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch                     | 3        | 0.64%   |
| Goldstar W2442 GSM56D9 1680x1050 530x300mm 24.0-inch                                  | 3        | 0.64%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                                  | 3        | 0.64%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                             | 3        | 0.64%   |
| AOC 2757M AOC2757 1920x1080 598x336mm 27.0-inch                                       | 3        | 0.64%   |
| ___ LCDTV16 ___0101 1600x1200 1600x900mm 72.3-inch                                    | 2        | 0.43%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch                | 2        | 0.43%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                                    | 2        | 0.43%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                                   | 2        | 0.43%   |
| Sceptre Tech E275W-1920 SPT0ABF 1920x1080 443x249mm 20.0-inch                         | 2        | 0.43%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 410x260mm 19.1-inch                   | 2        | 0.43%   |
| Samsung Electronics S24R35x SAM100E 1920x1080 530x300mm 24.0-inch                     | 2        | 0.43%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch                     | 2        | 0.43%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch                | 2        | 0.43%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1190x340mm 48.7-inch                    | 2        | 0.43%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1200x340mm 49.1-inch                    | 2        | 0.43%   |
| Samsung Electronics C27HG7x SAM0E16 2560x1440 598x336mm 27.0-inch                     | 2        | 0.43%   |
| MSI G27C5 MSI3CA9 1920x1080 598x336mm 27.0-inch                                       | 2        | 0.43%   |
| Lenovo LEN LT1712p LEN13B7 1280x1024 338x270mm 17.0-inch                              | 2        | 0.43%   |
| Iiyama PL1906 IVM483C 1280x1024 376x301mm 19.0-inch                                   | 2        | 0.43%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                             | 2        | 0.43%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch                               | 2        | 0.43%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                                 | 2        | 0.43%   |
| eMachines E190HQV EMA0212 1280x1024 440x250mm 19.9-inch                               | 2        | 0.43%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                                     | 2        | 0.43%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                                    | 2        | 0.43%   |
| Dell P2319H DELD0D7 1920x1080 509x286mm 23.0-inch                                     | 2        | 0.43%   |
| Dell P1917S DELD091 1280x1024 375x300mm 18.9-inch                                     | 2        | 0.43%   |
| BenQ ZOWIE XL LCD BNQ7F31 1920x1080 531x298mm 24.0-inch                               | 2        | 0.43%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                                     | 2        | 0.43%   |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                                     | 2        | 0.43%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                                    | 2        | 0.43%   |
| ASUSTek Computer VG27A AUS2722 2560x1440 597x336mm 27.0-inch                          | 2        | 0.43%   |
| AOC 2790 AOC2790 1920x1080 598x336mm 27.0-inch                                        | 2        | 0.43%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                                       | 2        | 0.43%   |
| AOC 2460 AOC2460 1920x1080 531x299mm 24.0-inch                                        | 2        | 0.43%   |
| AOC 22B1W AOC2201 1920x1080 476x268mm 21.5-inch                                       | 2        | 0.43%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch                 | 2        | 0.43%   |
| Acer X223HQ ACR0098 1920x1080 470x270mm 21.3-inch                                     | 2        | 0.43%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                                     | 2        | 0.43%   |
| Zoran ZORAN ZRN02E9 1280x720 440x250mm 19.9-inch                                      | 1        | 0.21%   |
| Vizio V405-H9 VIZ1039 3840x2160 870x480mm 39.1-inch                                   | 1        | 0.21%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                                  | 1        | 0.21%   |
| Vizio E190VA VIZ0067 1360x768 410x230mm 18.5-inch                                     | 1        | 0.21%   |
| Vizio D43-C1 VIZ0098 1920x1080 940x529mm 42.5-inch                                    | 1        | 0.21%   |
| ViewSonic VX3276-UHD VSC5138 3840x2160 697x392mm 31.5-inch                            | 1        | 0.21%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch                             | 1        | 0.21%   |
| ViewSonic VP2770 SERIES VSC832B 2560x1440 597x336mm 27.0-inch                         | 1        | 0.21%   |
| ViewSonic VP2365 SERIES VSC7C28 1920x1080 509x286mm 23.0-inch                         | 1        | 0.21%   |
| ViewSonic VA2265 SERIES VSCB330 1920x1080 476x268mm 21.5-inch                         | 1        | 0.21%   |
| ViewSonic VA2246 SERIES VSC6F2E 1920x1080 477x268mm 21.5-inch                         | 1        | 0.21%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 495x291mm 22.6-inch                             | 1        | 0.21%   |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch                          | 1        | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 192      | 46.38%  |
| 2560x1440 (QHD)    | 54       | 13.04%  |
| 3840x2160 (4K)     | 50       | 12.08%  |
| 1280x1024 (SXGA)   | 17       | 4.11%   |
| 2560x1080          | 16       | 3.86%   |
| 1440x900 (WXGA+)   | 14       | 3.38%   |
| 1366x768 (WXGA)    | 13       | 3.14%   |
| 1920x1200 (WUXGA)  | 11       | 2.66%   |
| 3440x1440          | 7        | 1.69%   |
| 1680x1050 (WSXGA+) | 7        | 1.69%   |
| 1600x900 (HD+)     | 7        | 1.69%   |
| 1360x768           | 6        | 1.45%   |
| 3840x1080          | 5        | 1.21%   |
| Unknown            | 4        | 0.97%   |
| 2048x1152          | 2        | 0.48%   |
| 1024x768 (XGA)     | 2        | 0.48%   |
| 7680x1440          | 1        | 0.24%   |
| 7120x1080          | 1        | 0.24%   |
| 2560x1600          | 1        | 0.24%   |
| 2288x1287          | 1        | 0.24%   |
| 1600x1200          | 1        | 0.24%   |
| 1280x960           | 1        | 0.24%   |
| 1280x720 (HD)      | 1        | 0.24%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 86       | 20%     |
| 24      | 77       | 17.91%  |
| 23      | 51       | 11.86%  |
| 21      | 50       | 11.63%  |
| 19      | 24       | 5.58%   |
| 34      | 22       | 5.12%   |
| 31      | 19       | 4.42%   |
| 18      | 15       | 3.49%   |
| Unknown | 14       | 3.26%   |
| 72      | 10       | 2.33%   |
| 15      | 8        | 1.86%   |
| 20      | 7        | 1.63%   |
| 32      | 6        | 1.4%    |
| 22      | 6        | 1.4%    |
| 84      | 5        | 1.16%   |
| 48      | 4        | 0.93%   |
| 28      | 4        | 0.93%   |
| 25      | 4        | 0.93%   |
| 17      | 4        | 0.93%   |
| 49      | 3        | 0.7%    |
| 42      | 2        | 0.47%   |
| 26      | 2        | 0.47%   |
| 16      | 2        | 0.47%   |
| 54      | 1        | 0.23%   |
| 43      | 1        | 0.23%   |
| 40      | 1        | 0.23%   |
| 33      | 1        | 0.23%   |
| 30      | 1        | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 192      | 47.29%  |
| 401-500     | 82       | 20.2%   |
| 601-700     | 30       | 7.39%   |
| 701-800     | 29       | 7.14%   |
| 351-400     | 20       | 4.93%   |
| 1501-2000   | 15       | 3.69%   |
| Unknown     | 14       | 3.45%   |
| 301-350     | 12       | 2.96%   |
| 1001-1500   | 8        | 1.97%   |
| 901-1000    | 3        | 0.74%   |
| 801-900     | 1        | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 284      | 75.53%  |
| 16/10   | 30       | 7.98%   |
| 21/9    | 23       | 6.12%   |
| 5/4     | 18       | 4.79%   |
| Unknown | 8        | 2.13%   |
| 4/3     | 6        | 1.6%    |
| 32/9    | 4        | 1.06%   |
| 6/5     | 2        | 0.53%   |
| 3/2     | 1        | 0.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 138      | 32.86%  |
| 301-350        | 87       | 20.71%  |
| 351-500        | 52       | 12.38%  |
| 151-200        | 52       | 12.38%  |
| 251-300        | 26       | 6.19%   |
| More than 1000 | 18       | 4.29%   |
| Unknown        | 14       | 3.33%   |
| 141-150        | 12       | 2.86%   |
| 501-1000       | 8        | 1.9%    |
| 101-110        | 6        | 1.43%   |
| 131-140        | 4        | 0.95%   |
| 91-100         | 2        | 0.48%   |
| 111-120        | 1        | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 231      | 57.61%  |
| 101-120 | 105      | 26.18%  |
| 121-160 | 27       | 6.73%   |
| Unknown | 14       | 3.49%   |
| 1-50    | 12       | 2.99%   |
| 161-240 | 12       | 2.99%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 255      | 68.73%  |
| 2     | 92       | 24.8%   |
| 0     | 13       | 3.5%    |
| 3     | 11       | 2.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 208      | 39.62%  |
| Intel                           | 208      | 39.62%  |
| Qualcomm Atheros                | 28       | 5.33%   |
| Broadcom                        | 12       | 2.29%   |
| Ralink Technology               | 11       | 2.1%    |
| Aquantia                        | 9        | 1.71%   |
| TP-Link                         | 6        | 1.14%   |
| Nvidia                          | 5        | 0.95%   |
| Marvell Technology Group        | 4        | 0.76%   |
| Broadcom Limited                | 4        | 0.76%   |
| Ralink                          | 3        | 0.57%   |
| NetGear                         | 3        | 0.57%   |
| Huawei Technologies             | 3        | 0.57%   |
| Xiaomi                          | 2        | 0.38%   |
| ICS Advent                      | 2        | 0.38%   |
| D-Link System                   | 2        | 0.38%   |
| Wilocity                        | 1        | 0.19%   |
| Qualcomm Atheros Communications | 1        | 0.19%   |
| Qualcomm                        | 1        | 0.19%   |
| Oculus VR                       | 1        | 0.19%   |
| Motorola PCS                    | 1        | 0.19%   |
| Microsoft                       | 1        | 0.19%   |
| Microchip Technology            | 1        | 0.19%   |
| Mellanox Technologies           | 1        | 0.19%   |
| Linksys                         | 1        | 0.19%   |
| IMC Networks                    | 1        | 0.19%   |
| D-Link                          | 1        | 0.19%   |
| ASUSTek Computer                | 1        | 0.19%   |
| Arduino SA                      | 1        | 0.19%   |
| Apple                           | 1        | 0.19%   |
| Adafruit                        | 1        | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 157      | 24.61%  |
| Intel Wi-Fi 6 AX200                                                           | 58       | 9.09%   |
| Intel I211 Gigabit Network Connection                                         | 49       | 7.68%   |
| Realtek RTL8125 2.5GbE Controller                                             | 28       | 4.39%   |
| Intel Ethernet Connection (2) I219-V                                          | 26       | 4.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 18       | 2.82%   |
| Intel Wireless-AC 9260                                                        | 14       | 2.19%   |
| Intel Ethernet Controller I225-V                                              | 11       | 1.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 11       | 1.72%   |
| Intel Ethernet Connection (7) I219-V                                          | 10       | 1.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 8        | 1.25%   |
| Intel Ethernet Connection (2) I218-V                                          | 8        | 1.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 7        | 1.1%    |
| Intel Wireless 8260                                                           | 7        | 1.1%    |
| Intel Wireless 7260                                                           | 7        | 1.1%    |
| Intel Ethernet Connection I217-LM                                             | 7        | 1.1%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 6        | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 5        | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 5        | 0.78%   |
| Intel Ethernet Connection I217-V                                              | 5        | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 5        | 0.78%   |
| Intel 82574L Gigabit Network Connection                                       | 5        | 0.78%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 5        | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 4        | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4        | 0.63%   |
| Ralink MT7601U Wireless Adapter                                               | 4        | 0.63%   |
| Intel I210 Gigabit Network Connection                                         | 4        | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4        | 0.63%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 0.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 3        | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 3        | 0.47%   |
| Realtek 802.11ac NIC                                                          | 3        | 0.47%   |
| Ralink RT5370 Wireless Adapter                                                | 3        | 0.47%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                             | 3        | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 3        | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 3        | 0.47%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 3        | 0.47%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 3        | 0.47%   |
| Intel Ethernet Connection (12) I219-V                                         | 3        | 0.47%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 0.47%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 3        | 0.47%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 3        | 0.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 2        | 0.31%   |
| TP-Link Archer T4U ver.3                                                      | 2        | 0.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 0.31%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 2        | 0.31%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 2        | 0.31%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2        | 0.31%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2        | 0.31%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 2        | 0.31%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2        | 0.31%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2        | 0.31%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 2        | 0.31%   |
| Nvidia MCP77 Ethernet                                                         | 2        | 0.31%   |
| NetGear A6210                                                                 | 2        | 0.31%   |
| Intel Wireless 8265 / 8275                                                    | 2        | 0.31%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2        | 0.31%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 0.31%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 2        | 0.31%   |
| Huawei MYA-U29                                                                | 2        | 0.31%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 120      | 60.61%  |
| Realtek Semiconductor           | 27       | 13.64%  |
| Qualcomm Atheros                | 15       | 7.58%   |
| Ralink Technology               | 11       | 5.56%   |
| TP-Link                         | 6        | 3.03%   |
| Broadcom                        | 5        | 2.53%   |
| Ralink                          | 3        | 1.52%   |
| NetGear                         | 3        | 1.52%   |
| Wilocity                        | 1        | 0.51%   |
| Qualcomm Atheros Communications | 1        | 0.51%   |
| Microsoft                       | 1        | 0.51%   |
| Linksys                         | 1        | 0.51%   |
| IMC Networks                    | 1        | 0.51%   |
| D-Link System                   | 1        | 0.51%   |
| Broadcom Limited                | 1        | 0.51%   |
| ASUSTek Computer                | 1        | 0.51%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                    | 58       | 29.15%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 18       | 9.05%   |
| Intel Wireless-AC 9260                                                 | 14       | 7.04%   |
| Intel Wireless 8260                                                    | 7        | 3.52%   |
| Intel Wireless 7260                                                    | 7        | 3.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5        | 2.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5        | 2.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 4        | 2.01%   |
| Ralink MT7601U Wireless Adapter                                        | 4        | 2.01%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 3        | 1.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3        | 1.51%   |
| Realtek 802.11ac NIC                                                   | 3        | 1.51%   |
| Ralink RT5370 Wireless Adapter                                         | 3        | 1.51%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                      | 3        | 1.51%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                     | 3        | 1.51%   |
| TP-Link Archer T4U ver.3                                               | 2        | 1.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2        | 1.01%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 2        | 1.01%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 2        | 1.01%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 2        | 1.01%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2        | 1.01%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 2        | 1.01%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 2        | 1.01%   |
| NetGear A6210                                                          | 2        | 1.01%   |
| Intel Wireless 8265 / 8275                                             | 2        | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2        | 1.01%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                     | 1        | 0.5%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 1        | 0.5%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1        | 0.5%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 1        | 0.5%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1        | 0.5%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 0.5%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 1        | 0.5%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                        | 1        | 0.5%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 1        | 0.5%    |
| Realtek RTL8191SEvB Wireless LAN Controller                            | 1        | 0.5%    |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                   | 1        | 0.5%    |
| Realtek RTL8188EE Wireless Network Adapter                             | 1        | 0.5%    |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 1        | 0.5%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                              | 1        | 0.5%    |
| Ralink RT2760 Wireless 802.11n 1T/2R                                   | 1        | 0.5%    |
| Ralink RT2561/RT61 rev B 802.11g                                       | 1        | 0.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1        | 0.5%    |
| Qualcomm Atheros AR9271 802.11n                                        | 1        | 0.5%    |
| Qualcomm Atheros AR922X Wireless Network Adapter                       | 1        | 0.5%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 1        | 0.5%    |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 1        | 0.5%    |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]       | 1        | 0.5%    |
| Microsoft XBOX ACC                                                     | 1        | 0.5%    |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU] | 1        | 0.5%    |
| Intel Wireless 7265                                                    | 1        | 0.5%    |
| Intel Wireless 3165                                                    | 1        | 0.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 1        | 0.5%    |
| Intel Ultimate N WiFi Link 5300                                        | 1        | 0.5%    |
| Intel Tiger Lake PCH CNVi WiFi                                         | 1        | 0.5%    |
| Intel Gemini Lake PCH CNVi WiFi                                        | 1        | 0.5%    |
| Intel Centrino Wireless-N 2230                                         | 1        | 0.5%    |
| IMC Networks AW-NU137 802.11bgn Wireless Module [Atheros AR9271]       | 1        | 0.5%    |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]   | 1        | 0.5%    |
| Broadcom Limited BCM4321 802.11a/b/g/n                                 | 1        | 0.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 197      | 48.4%   |
| Intel                    | 153      | 37.59%  |
| Qualcomm Atheros         | 17       | 4.18%   |
| Aquantia                 | 9        | 2.21%   |
| Broadcom                 | 7        | 1.72%   |
| Nvidia                   | 5        | 1.23%   |
| Marvell Technology Group | 4        | 0.98%   |
| Broadcom Limited         | 3        | 0.74%   |
| Xiaomi                   | 2        | 0.49%   |
| ICS Advent               | 2        | 0.49%   |
| Huawei Technologies      | 2        | 0.49%   |
| Qualcomm                 | 1        | 0.25%   |
| Motorola PCS             | 1        | 0.25%   |
| Mellanox Technologies    | 1        | 0.25%   |
| D-Link System            | 1        | 0.25%   |
| D-Link                   | 1        | 0.25%   |
| Apple                    | 1        | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 157      | 36.18%  |
| Intel I211 Gigabit Network Connection                                         | 49       | 11.29%  |
| Realtek RTL8125 2.5GbE Controller                                             | 28       | 6.45%   |
| Intel Ethernet Connection (2) I219-V                                          | 26       | 5.99%   |
| Intel Ethernet Controller I225-V                                              | 11       | 2.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 11       | 2.53%   |
| Intel Ethernet Connection (7) I219-V                                          | 10       | 2.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 8        | 1.84%   |
| Intel Ethernet Connection (2) I218-V                                          | 8        | 1.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 7        | 1.61%   |
| Intel Ethernet Connection I217-LM                                             | 7        | 1.61%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 6        | 1.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 5        | 1.15%   |
| Intel Ethernet Connection I217-V                                              | 5        | 1.15%   |
| Intel 82574L Gigabit Network Connection                                       | 5        | 1.15%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 5        | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4        | 0.92%   |
| Intel I210 Gigabit Network Connection                                         | 4        | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4        | 0.92%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 0.92%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 3        | 0.69%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 3        | 0.69%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 3        | 0.69%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 3        | 0.69%   |
| Intel Ethernet Connection (12) I219-V                                         | 3        | 0.69%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 0.69%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 3        | 0.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 2        | 0.46%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2        | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 2        | 0.46%   |
| Nvidia MCP77 Ethernet                                                         | 2        | 0.46%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 0.46%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 2        | 0.46%   |
| Huawei MYA-U29                                                                | 2        | 0.46%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                       | 2        | 0.46%   |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 1        | 0.23%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1        | 0.23%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.23%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1        | 0.23%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.23%   |
| Qualcomm Android                                                              | 1        | 0.23%   |
| Nvidia MCP73 Ethernet                                                         | 1        | 0.23%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 0.23%   |
| Nvidia CK804 Ethernet Controller                                              | 1        | 0.23%   |
| Motorola PCS moto g(30)                                                       | 1        | 0.23%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 1        | 0.23%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.23%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 0.23%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.23%   |
| Intel Ethernet Connection (10) I219-V                                         | 1        | 0.23%   |
| Intel 82567V-2 Gigabit Network Connection                                     | 1        | 0.23%   |
| Intel 82567LF-2 Gigabit Network Connection                                    | 1        | 0.23%   |
| Intel 82546GB Gigabit Ethernet Controller                                     | 1        | 0.23%   |
| Intel 82546EB Gigabit Ethernet Controller (Copper)                            | 1        | 0.23%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                       | 1        | 0.23%   |
| ICS Advent 10/100M LAN                                                        | 1        | 0.23%   |
| D-Link System RTL8139 Ethernet                                                | 1        | 0.23%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                                      | 1        | 0.23%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 360      | 65.81%  |
| WiFi     | 182      | 33.27%  |
| Modem    | 5        | 0.91%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 333      | 70.11%  |
| WiFi     | 142      | 29.89%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 179      | 48.25%  |
| 2     | 146      | 39.35%  |
| 3     | 34       | 9.16%   |
| 4     | 5        | 1.35%   |
| 5     | 3        | 0.81%   |
| 0     | 3        | 0.81%   |
| 9     | 1        | 0.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 282      | 76.22%  |
| Yes  | 88       | 23.78%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 113      | 63.13%  |
| Cambridge Silicon Radio         | 25       | 13.97%  |
| Broadcom                        | 13       | 7.26%   |
| ASUSTek Computer                | 10       | 5.59%   |
| Realtek Semiconductor           | 6        | 3.35%   |
| Qualcomm Atheros Communications | 4        | 2.23%   |
| IMC Networks                    | 3        | 1.68%   |
| Lite-On Technology              | 1        | 0.56%   |
| Edimax Technology               | 1        | 0.56%   |
| Dynex                           | 1        | 0.56%   |
| D-Link System                   | 1        | 0.56%   |
| Apple                           | 1        | 0.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                    | 52       | 29.05%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 25       | 13.97%  |
| Intel Bluetooth Device                                   | 19       | 10.61%  |
| Intel Wireless-AC 3168 Bluetooth                         | 18       | 10.06%  |
| Intel Bluetooth wireless interface                       | 17       | 9.5%    |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 11       | 6.15%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 6        | 3.35%   |
| Realtek Bluetooth Radio                                  | 5        | 2.79%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 4        | 2.23%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 2        | 1.12%   |
| ASUS Bluetooth Radio                                     | 2        | 1.12%   |
| Realtek  Bluetooth 4.2 Adapter                           | 1        | 0.56%   |
| Qualcomm Atheros  Bluetooth Device                       | 1        | 0.56%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 1        | 0.56%   |
| Lite-On Bluetooth Device                                 | 1        | 0.56%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 0.56%   |
| IMC Networks Bluetooth Radio                             | 1        | 0.56%   |
| IMC Networks Bluetooth Module                            | 1        | 0.56%   |
| IMC Networks Bluetooth Device                            | 1        | 0.56%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter  | 1        | 0.56%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 0.56%   |
| D-Link System DBT-122 Bluetooth                          | 1        | 0.56%   |
| Broadcom HP Portable Bumble Bee                          | 1        | 0.56%   |
| Broadcom BCM2045 Bluetooth                               | 1        | 0.56%   |
| ASUS Qualcomm Bluetooth 4.1                              | 1        | 0.56%   |
| ASUS Bluetooth Device                                    | 1        | 0.56%   |
| ASUS BCM20702A0                                          | 1        | 0.56%   |
| ASUS ASUS USB-BT500                                      | 1        | 0.56%   |
| Apple Bluetooth USB Host Controller                      | 1        | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 199      | 29.7%   |
| Intel                       | 191      | 28.51%  |
| Nvidia                      | 162      | 24.18%  |
| C-Media Electronics         | 21       | 3.13%   |
| Logitech                    | 10       | 1.49%   |
| Creative Technology         | 8        | 1.19%   |
| Kingston Technology         | 5        | 0.75%   |
| Focusrite-Novation          | 5        | 0.75%   |
| Creative Labs               | 5        | 0.75%   |
| Corsair                     | 5        | 0.75%   |
| Blue Microphones            | 5        | 0.75%   |
| SteelSeries ApS             | 4        | 0.6%    |
| Razer USA                   | 4        | 0.6%    |
| Samson Technologies         | 3        | 0.45%   |
| RODE Microphones            | 3        | 0.45%   |
| GYROCOM C&C                 | 3        | 0.45%   |
| Generalplus Technology      | 3        | 0.45%   |
| ULi Electronics             | 2        | 0.3%    |
| Tenx Technology             | 2        | 0.3%    |
| Schiit Audio                | 2        | 0.3%    |
| Plantronics                 | 2        | 0.3%    |
| GN Netcom                   | 2        | 0.3%    |
| ASUSTek Computer            | 2        | 0.3%    |
| Yamaha                      | 1        | 0.15%   |
| VIA Technologies            | 1        | 0.15%   |
| Thermaltake                 | 1        | 0.15%   |
| Texas Instruments           | 1        | 0.15%   |
| Sony                        | 1        | 0.15%   |
| Shenzhen Riitek Technology  | 1        | 0.15%   |
| PreSonus Audio Electronics  | 1        | 0.15%   |
| Meridian                    | 1        | 0.15%   |
| Medeli Electronics          | 1        | 0.15%   |
| Lenovo                      | 1        | 0.15%   |
| JMTek                       | 1        | 0.15%   |
| JBL                         | 1        | 0.15%   |
| iPassion Technology         | 1        | 0.15%   |
| iCreate Technologies        | 1        | 0.15%   |
| Griffin Technology          | 1        | 0.15%   |
| FiiO Electronics Technology | 1        | 0.15%   |
| FIFINE Microphones          | 1        | 0.15%   |
| EGO SYStems                 | 1        | 0.15%   |
| Cambridge Silicon Radio     | 1        | 0.15%   |
| Blackstorm Scou             | 1        | 0.15%   |
| Astro Gaming                | 1        | 0.15%   |
| Apogee Electronics          | 1        | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 72       | 9.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 36       | 4.56%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 33       | 4.18%   |
| Intel 200 Series PCH HD Audio                                                     | 30       | 3.8%    |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 25       | 3.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 22       | 2.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 20       | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 19       | 2.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 18       | 2.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 18       | 2.28%   |
| AMD Navi 10 HDMI Audio                                                            | 18       | 2.28%   |
| Intel Cannon Lake PCH cAVS                                                        | 17       | 2.15%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 17       | 2.15%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 16       | 2.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 16       | 2.03%   |
| Nvidia GP106 High Definition Audio Controller                                     | 15       | 1.9%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 15       | 1.9%    |
| Nvidia GP104 High Definition Audio Controller                                     | 13       | 1.65%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 13       | 1.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 13       | 1.65%   |
| Nvidia TU116 High Definition Audio Controller                                     | 12       | 1.52%   |
| Nvidia TU106 High Definition Audio Controller                                     | 12       | 1.52%   |
| Nvidia TU104 HD Audio Controller                                                  | 8        | 1.01%   |
| Nvidia GA104 High Definition Audio Controller                                     | 8        | 1.01%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 8        | 1.01%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller                    | 8        | 1.01%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 8        | 1.01%   |
| AMD FCH Azalia Controller                                                         | 8        | 1.01%   |
| Nvidia GM204 High Definition Audio Controller                                     | 7        | 0.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 7        | 0.89%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 6        | 0.76%   |
| Nvidia High Definition Audio Controller                                           | 5        | 0.63%   |
| Nvidia GP108 High Definition Audio Controller                                     | 5        | 0.63%   |
| Nvidia GM206 High Definition Audio Controller                                     | 5        | 0.63%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 5        | 0.63%   |
| C-Media Electronics USB Audio Device                                              | 5        | 0.63%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 5        | 0.63%   |
| Nvidia TU102 High Definition Audio Controller                                     | 4        | 0.51%   |
| Nvidia GP102 HDMI Audio Controller                                                | 4        | 0.51%   |
| Nvidia GF119 HDMI Audio Controller                                                | 4        | 0.51%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 4        | 0.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4        | 0.51%   |
| C-Media Electronics Blue Snowball                                                 | 4        | 0.51%   |
| Blue Microphones Yeti Stereo Microphone                                           | 4        | 0.51%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                | 4        | 0.51%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 4        | 0.51%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4        | 0.51%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 3        | 0.38%   |
| Nvidia MCP61 High Definition Audio                                                | 3        | 0.38%   |
| Nvidia GK104 HDMI Audio Controller                                                | 3        | 0.38%   |
| Nvidia GF108 High Definition Audio Controller                                     | 3        | 0.38%   |
| Nvidia Audio device                                                               | 3        | 0.38%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3        | 0.38%   |
| Intel Audio device                                                                | 3        | 0.38%   |
| GYROCOM C&C Fiio E10                                                              | 3        | 0.38%   |
| Generalplus Technology USB Audio Device                                           | 3        | 0.38%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 3        | 0.38%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 3        | 0.38%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                         | 3        | 0.38%   |
| ULi Electronics HD Audio Controller                                               | 2        | 0.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 40       | 22.35%  |
| Kingston            | 35       | 19.55%  |
| G.Skill             | 25       | 13.97%  |
| Unknown             | 24       | 13.41%  |
| Samsung Electronics | 12       | 6.7%    |
| Crucial             | 11       | 6.15%   |
| SK Hynix            | 10       | 5.59%   |
| Micron Technology   | 9        | 5.03%   |
| GOODRAM             | 3        | 1.68%   |
| Patriot             | 2        | 1.12%   |
| Elpida              | 2        | 1.12%   |
| A-DATA Technology   | 2        | 1.12%   |
| Unknown (ABCD)      | 1        | 0.56%   |
| Transcend           | 1        | 0.56%   |
| Teikon              | 1        | 0.56%   |
| Silicon Power       | 1        | 0.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM 667MT/s                          | 3        | 1.5%    |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s            | 3        | 1.5%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 3        | 1.5%    |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s        | 3        | 1.5%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s        | 3        | 1.5%    |
| Corsair RAM CMK16GX4M1E3200C16 16GB DIMM DDR4 3000MT/s       | 3        | 1.5%    |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                    | 2        | 1%      |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                      | 2        | 1%      |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 2        | 1%      |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 2        | 1%      |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s       | 2        | 1%      |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s            | 2        | 1%      |
| Kingston RAM KHX2133C14D4/8G 8192MB DIMM DDR4 2667MT/s       | 2        | 1%      |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1867MT/s          | 2        | 1%      |
| G.Skill RAM F4-3600C19-16GVRB 16GB DIMM DDR4 3600MT/s        | 2        | 1%      |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s          | 2        | 1%      |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s       | 2        | 1%      |
| Corsair RAM CMK8GX4M1A2400C16 8192MB DIMM DDR4 2800MT/s      | 2        | 1%      |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s       | 2        | 1%      |
| Corsair RAM CMK32GX4M2B3000C15 16384MB DIMM DDR4 3000MT/s    | 2        | 1%      |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 2        | 1%      |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3200MT/s        | 2        | 1%      |
| Unknown RAM TL48G32S8KGRGB16 8GB DIMM DDR4 3200MT/s          | 1        | 0.5%    |
| Unknown RAM RXD4P12008GA 8GB DIMM DDR4 2400MT/s              | 1        | 0.5%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 1        | 0.5%    |
| Unknown RAM Module 8GB DIMM 1600MT/s                         | 1        | 0.5%    |
| Unknown RAM Module 512MB DIMM SDRAM                          | 1        | 0.5%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 1        | 0.5%    |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                    | 1        | 0.5%    |
| Unknown RAM Module 4GB DIMM 800MT/s                          | 1        | 0.5%    |
| Unknown RAM Module 4GB DIMM 400MT/s                          | 1        | 0.5%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 1        | 0.5%    |
| Unknown RAM Module 4GB DIMM                                  | 1        | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                  | 1        | 0.5%    |
| Unknown RAM Module 2GB DIMM SDRAM                            | 1        | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                    | 1        | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                     | 1        | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                     | 1        | 0.5%    |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 1        | 0.5%    |
| Unknown RAM Module 2GB DIMM 400MT/s                          | 1        | 0.5%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 1        | 0.5%    |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                     | 1        | 0.5%    |
| Unknown RAM Module 1GB DIMM DDR2 1066MT/s                    | 1        | 0.5%    |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 1        | 0.5%    |
| Transcend RAM TS512MLK72V6N 4GB DIMM DDR3 1600MT/s           | 1        | 0.5%    |
| Teikon RAM TMT351U6EFR8C-PBHJ 4GB DIMM DDR3 1600MT/s         | 1        | 0.5%    |
| SK Hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1        | 0.5%    |
| SK Hynix RAM HMT451U7BFR8C-RD 4GB DIMM DDR3 1333MT/s         | 1        | 0.5%    |
| SK Hynix RAM HMT451U7AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1        | 0.5%    |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s      | 1        | 0.5%    |
| SK Hynix RAM HMT325U7BFR8C-H9 2048MB DIMM DDR3 1333MT/s      | 1        | 0.5%    |
| SK Hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1        | 0.5%    |
| SK Hynix RAM HMT125U7BFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1        | 0.5%    |
| SK Hynix RAM HMT112U7BFR8C-G7 1GB DIMM DDR3 1066MT/s         | 1        | 0.5%    |
| SK Hynix RAM HMAA1GU6CJR6N-XN 8GB DIMM DDR4 3200MT/s         | 1        | 0.5%    |
| SK Hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2666MT/s         | 1        | 0.5%    |
| SK Hynix RAM HMA451R7MFR8N-TF 4GB RIMM 2133MT/s              | 1        | 0.5%    |
| Silicon Power RAM SP008GBLTU160N02 8GB DIMM DDR3 1600MT/s    | 1        | 0.5%    |
| Silicon Power RAM DCLT8GN128S 8GB DIMM DDR3 1600MT/s         | 1        | 0.5%    |
| Samsung RAM Module 16GB DIMM DDR4 3200MT/s                   | 1        | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 99       | 61.88%  |
| DDR3    | 42       | 26.25%  |
| Unknown | 8        | 5%      |
| DDR2    | 6        | 3.75%   |
| DDR     | 3        | 1.88%   |
| SDRAM   | 1        | 0.63%   |
| LPDDR4  | 1        | 0.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 153      | 95.63%  |
| SODIMM | 6        | 3.75%   |
| RIMM   | 1        | 0.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 68       | 39.31%  |
| 16384 | 44       | 25.43%  |
| 4096  | 28       | 16.18%  |
| 2048  | 22       | 12.72%  |
| 32768 | 5        | 2.89%   |
| 1024  | 5        | 2.89%   |
| 512   | 1        | 0.58%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 30       | 16.57%  |
| 1600    | 27       | 14.92%  |
| 3600    | 17       | 9.39%   |
| 1333    | 14       | 7.73%   |
| 2400    | 11       | 6.08%   |
| 2667    | 9        | 4.97%   |
| 2133    | 9        | 4.97%   |
| 3000    | 8        | 4.42%   |
| 2800    | 6        | 3.31%   |
| 1067    | 5        | 2.76%   |
| 667     | 5        | 2.76%   |
| 3800    | 3        | 1.66%   |
| 3466    | 3        | 1.66%   |
| 3400    | 3        | 1.66%   |
| 3266    | 3        | 1.66%   |
| 1867    | 3        | 1.66%   |
| 1066    | 3        | 1.66%   |
| 800     | 3        | 1.66%   |
| 333     | 3        | 1.66%   |
| 3533    | 2        | 1.1%    |
| 1800    | 2        | 1.1%    |
| Unknown | 2        | 1.1%    |
| 3866    | 1        | 0.55%   |
| 3733    | 1        | 0.55%   |
| 3666    | 1        | 0.55%   |
| 3100    | 1        | 0.55%   |
| 2933    | 1        | 0.55%   |
| 2666    | 1        | 0.55%   |
| 2134    | 1        | 0.55%   |
| 1866    | 1        | 0.55%   |
| 933     | 1        | 0.55%   |
| 400     | 1        | 0.55%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 10       | 50%     |
| Brother Industries  | 4        | 20%     |
| Canon               | 2        | 10%     |
| Seiko Epson         | 1        | 5%      |
| Samsung Electronics | 1        | 5%      |
| Prolific Technology | 1        | 5%      |
| Dymo-CoStar         | 1        | 5%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| HP OfficeJet 6950                            | 2        | 10%     |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 5%      |
| Samsung M2070 Series                         | 1        | 5%      |
| Prolific PL2305 Parallel Port                | 1        | 5%      |
| HP Neverstop Laser 100x                      | 1        | 5%      |
| HP LaserJet P1006                            | 1        | 5%      |
| HP Ink Tank 310 series                       | 1        | 5%      |
| HP ENVY 5000 series                          | 1        | 5%      |
| HP DeskJet F4100 Printer series              | 1        | 5%      |
| HP Deskjet D2500 series                      | 1        | 5%      |
| HP DeskJet 4530 series                       | 1        | 5%      |
| HP DeskJet 2600 series                       | 1        | 5%      |
| Dymo-CoStar DYMO LabelWriter 4XL             | 1        | 5%      |
| Canon PIXMA MP270 All-In-One Printer         | 1        | 5%      |
| Canon LiDE 300                               | 1        | 5%      |
| Brother MFC-9330CDW                          | 1        | 5%      |
| Brother MFC-9325CW                           | 1        | 5%      |
| Brother HL-1430 Laser Printer                | 1        | 5%      |
| Brother DCP-7040                             | 1        | 5%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Canon       | 4        | 57.14%  |
| Seiko Epson | 3        | 42.86%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1        | 14.29%  |
| Seiko Epson GT-X770 [Perfection V500]                   | 1        | 14.29%  |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 14.29%  |
| Canon CanoScan N1240U/LiDE 30                           | 1        | 14.29%  |
| Canon CanoScan LiDE 70                                  | 1        | 14.29%  |
| Canon CanoScan LiDE 220                                 | 1        | 14.29%  |
| Canon CanoScan 4400F                                    | 1        | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 44       | 44%     |
| Microsoft                     | 6        | 6%      |
| Sunplus Innovation Technology | 5        | 5%      |
| webcam                        | 4        | 4%      |
| Samsung Electronics           | 4        | 4%      |
| Microdia                      | 4        | 4%      |
| Realtek Semiconductor         | 3        | 3%      |
| Z-Star Microelectronics       | 2        | 2%      |
| Razer USA                     | 2        | 2%      |
| Jieli Technology              | 2        | 2%      |
| HD WEBCAM                     | 2        | 2%      |
| Generalplus Technology        | 2        | 2%      |
| AVerMedia Technologies        | 2        | 2%      |
| ARC International             | 2        | 2%      |
| Apple                         | 2        | 2%      |
| Alcor Micro                   | 2        | 2%      |
| Unknown                       | 1        | 1%      |
| Trust                         | 1        | 1%      |
| Sony                          | 1        | 1%      |
| OmniVision Technologies       | 1        | 1%      |
| LG Electronics                | 1        | 1%      |
| Lenovo                        | 1        | 1%      |
| KYE Systems (Mouse Systems)   | 1        | 1%      |
| INOGENI                       | 1        | 1%      |
| Hewlett-Packard               | 1        | 1%      |
| Creative Technology           | 1        | 1%      |
| BUFFALO                       | 1        | 1%      |
| Alcorlink                     | 1        | 1%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Logitech Webcam C270                            | 14       | 13.46%  |
| Logitech HD Pro Webcam C920                     | 10       | 9.62%   |
| Logitech HD Webcam C525                         | 6        | 5.77%   |
| webcam webcam                                   | 4        | 3.85%   |
| Samsung Galaxy series, misc. (MTP mode)         | 4        | 3.85%   |
| Microsoft LifeCam Cinema                        | 3        | 2.88%   |
| Microdia Webcam Vitade AF                       | 3        | 2.88%   |
| Logitech Webcam C925e                           | 3        | 2.88%   |
| Logitech StreamCam                              | 3        | 2.88%   |
| Sunplus HD 720P webcam                          | 2        | 1.92%   |
| Realtek FULL HD 1080P Webcam                    | 2        | 1.92%   |
| Razer USA Razer Kiyo                            | 2        | 1.92%   |
| Logitech Webcam C930e                           | 2        | 1.92%   |
| Jieli USB PHY 2.0                               | 2        | 1.92%   |
| HD WEBCAM NexiGo N660 FHD Webcam                | 2        | 1.92%   |
| Generalplus 808 Camera                          | 2        | 1.92%   |
| ARC International Camera                        | 2        | 1.92%   |
| Apple iPhone 5/5C/5S/6/SE                       | 2        | 1.92%   |
| Alcor Micro USB 2.0 PC Camera                   | 2        | 1.92%   |
| Z-Star Venus USB2.0 Camera                      | 1        | 0.96%   |
| Z-Star A4 TECH USB2.0 PC Camera J               | 1        | 0.96%   |
| Unknown HD 720P                                 | 1        | 0.96%   |
| Trust USB Camera                                | 1        | 0.96%   |
| Sunplus UHD Capture                             | 1        | 0.96%   |
| Sunplus ezcap U3 capture-04                     | 1        | 0.96%   |
| Sunplus EKACOM-K30                              | 1        | 0.96%   |
| Sony CEVCECM                                    | 1        | 0.96%   |
| Realtek AF FULL HD 1080P Webcam                 | 1        | 0.96%   |
| OmniVision Monitor Webcam                       | 1        | 0.96%   |
| Microsoft LifeCam VX-2000                       | 1        | 0.96%   |
| Microsoft LifeCam Studio                        | 1        | 0.96%   |
| Microsoft LifeCam HD-3000                       | 1        | 0.96%   |
| Microdia Integrated Camera                      | 1        | 0.96%   |
| Logitech Webcam C310                            | 1        | 0.96%   |
| Logitech Webcam C210                            | 1        | 0.96%   |
| Logitech Webcam C170                            | 1        | 0.96%   |
| Logitech Webcam C120                            | 1        | 0.96%   |
| Logitech QuickCam Pro for Notebooks             | 1        | 0.96%   |
| Logitech QuickCam Pro 9000                      | 1        | 0.96%   |
| Logitech C922 Pro Stream Webcam                 | 1        | 0.96%   |
| Logitech BRIO Ultra HD Webcam                   | 1        | 0.96%   |
| Logitech BRIO 4K Stream Edition                 | 1        | 0.96%   |
| LG VS996                                        | 1        | 0.96%   |
| Lenovo FHD Webcam                               | 1        | 0.96%   |
| KYE Systems (Mouse Systems) Genius WideCam F100 | 1        | 0.96%   |
| INOGENI 1C3E-INOGENI SDI2USB3                   | 1        | 0.96%   |
| HP HD-4110 Webcam                               | 1        | 0.96%   |
| Creative Live! Cam Sync 1080p                   | 1        | 0.96%   |
| BUFFALO USB 2.0 Camera                          | 1        | 0.96%   |
| BUFFALO BUFFALO BSWHD06M USB Camera             | 1        | 0.96%   |
| AVerMedia Live Streamer CAM 313                 | 1        | 0.96%   |
| AVerMedia Live Gamer Ultra-Video                | 1        | 0.96%   |
| Alcorlink USB 2.0 Camera                        | 1        | 0.96%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| LighTuning EgisTec Touch Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 2        | 50%     |
| OmniKey               | 1        | 25%     |
| Cherry                | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 2        | 50%     |
| OmniKey CardMan 3021 / 3121                       | 1        | 25%     |
| Cherry SmartCard Reader Keyboard KC 1000 SC       | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 329      | 87.97%  |
| 1     | 43       | 11.5%   |
| 2     | 2        | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 15       | 34.09%  |
| Graphics card            | 13       | 29.55%  |
| Unassigned class         | 5        | 11.36%  |
| Camera                   | 3        | 6.82%   |
| Sound                    | 1        | 2.27%   |
| Network                  | 1        | 2.27%   |
| Multimedia controller    | 1        | 2.27%   |
| Fingerprint reader       | 1        | 2.27%   |
| Dvb card                 | 1        | 2.27%   |
| Communication controller | 1        | 2.27%   |
| Card reader              | 1        | 2.27%   |
| Bluetooth                | 1        | 2.27%   |

