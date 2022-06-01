Fedora 35 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Fedora 35.

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

Total: 696

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | FM2A88X Extreme6+           | [dd51d706e3](https://linux-hardware.org/?probe=dd51d706e3) | Jun 01, 2022 |
| MSI           | X99A RAIDER                 | [0b16a52ca1](https://linux-hardware.org/?probe=0b16a52ca1) | Jun 01, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [0faa61f3a9](https://linux-hardware.org/?probe=0faa61f3a9) | May 31, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [9f5906337b](https://linux-hardware.org/?probe=9f5906337b) | May 31, 2022 |
| MSI           | X99A RAIDER                 | [8794ca2ca9](https://linux-hardware.org/?probe=8794ca2ca9) | May 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [85a456dd94](https://linux-hardware.org/?probe=85a456dd94) | May 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [ff73ff1ea6](https://linux-hardware.org/?probe=ff73ff1ea6) | May 30, 2022 |
| MSI           | X99A RAIDER                 | [e6fc3ad487](https://linux-hardware.org/?probe=e6fc3ad487) | May 30, 2022 |
| MSI           | MEG X570 UNIFY              | [b86f47e828](https://linux-hardware.org/?probe=b86f47e828) | May 29, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | [96cd8abf05](https://linux-hardware.org/?probe=96cd8abf05) | May 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [3487c76d47](https://linux-hardware.org/?probe=3487c76d47) | May 29, 2022 |
| MSI           | X99A RAIDER                 | [1783c56618](https://linux-hardware.org/?probe=1783c56618) | May 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [db4eade79e](https://linux-hardware.org/?probe=db4eade79e) | May 28, 2022 |
| MSI           | X99A RAIDER                 | [d83c99fb0e](https://linux-hardware.org/?probe=d83c99fb0e) | May 28, 2022 |
| MSI           | X99A RAIDER                 | [8226c07ba6](https://linux-hardware.org/?probe=8226c07ba6) | May 27, 2022 |
| Gigabyte      | H77N-WIFI                   | [ac41fb756c](https://linux-hardware.org/?probe=ac41fb756c) | May 26, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [aea91adcbf](https://linux-hardware.org/?probe=aea91adcbf) | May 25, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [c2eb6bb974](https://linux-hardware.org/?probe=c2eb6bb974) | May 25, 2022 |
| Gigabyte      | G41MT-D3                    | [89927eb8f5](https://linux-hardware.org/?probe=89927eb8f5) | May 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [19d23eb25f](https://linux-hardware.org/?probe=19d23eb25f) | May 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f5ea71aeb2](https://linux-hardware.org/?probe=f5ea71aeb2) | May 21, 2022 |
| HP            | 8053                        | [53c0148d64](https://linux-hardware.org/?probe=53c0148d64) | May 20, 2022 |
| ECS           | P67H2-A3                    | [2bc21b9c81](https://linux-hardware.org/?probe=2bc21b9c81) | May 20, 2022 |
| MSI           | B450M PRO-VDH MAX           | [76c661d512](https://linux-hardware.org/?probe=76c661d512) | May 18, 2022 |
| Shuttle       | FZ87                        | [ce4198da70](https://linux-hardware.org/?probe=ce4198da70) | May 17, 2022 |
| Gigabyte      | MQLP7AP-00                  | [3c99b8d861](https://linux-hardware.org/?probe=3c99b8d861) | May 16, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [d85be75174](https://linux-hardware.org/?probe=d85be75174) | May 14, 2022 |
| Gigabyte      | G41MT-D3                    | [78c64b498b](https://linux-hardware.org/?probe=78c64b498b) | May 13, 2022 |
| ASRock        | G41C-GS R2.0                | [9c3a386393](https://linux-hardware.org/?probe=9c3a386393) | May 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | [41ee4b77ce](https://linux-hardware.org/?probe=41ee4b77ce) | May 10, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [eaa10a050b](https://linux-hardware.org/?probe=eaa10a050b) | May 10, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [3e3acb2430](https://linux-hardware.org/?probe=3e3acb2430) | May 10, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [e44c7da45a](https://linux-hardware.org/?probe=e44c7da45a) | May 09, 2022 |
| Ruckus Wir... | SCG-100                     | [781560aa15](https://linux-hardware.org/?probe=781560aa15) | May 09, 2022 |
| HP            | 212A                        | [acd660910f](https://linux-hardware.org/?probe=acd660910f) | May 09, 2022 |
| ASRock        | FM2A88X-ITX+                | [c0fa8189f0](https://linux-hardware.org/?probe=c0fa8189f0) | May 08, 2022 |
| ASUSTek       | AM1M-A                      | [537def711a](https://linux-hardware.org/?probe=537def711a) | May 08, 2022 |
| MSI           | H55M-P33                    | [0f6b0dc134](https://linux-hardware.org/?probe=0f6b0dc134) | May 07, 2022 |
| ASRock        | 970M Pro3                   | [1983ed1d48](https://linux-hardware.org/?probe=1983ed1d48) | May 07, 2022 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | [d4e02db7d2](https://linux-hardware.org/?probe=d4e02db7d2) | May 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [35cfe55dac](https://linux-hardware.org/?probe=35cfe55dac) | May 07, 2022 |
| ASUSTek       | P5N7A-VM                    | [44d168e79c](https://linux-hardware.org/?probe=44d168e79c) | May 07, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | [7e14e0a766](https://linux-hardware.org/?probe=7e14e0a766) | May 07, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | [047f75af38](https://linux-hardware.org/?probe=047f75af38) | May 07, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [5a08eb1919](https://linux-hardware.org/?probe=5a08eb1919) | May 06, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [0021b7ff7f](https://linux-hardware.org/?probe=0021b7ff7f) | May 05, 2022 |
| ASUSTek       | PRIME X370-PRO              | [b0a2114a0f](https://linux-hardware.org/?probe=b0a2114a0f) | May 05, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [60d50d3190](https://linux-hardware.org/?probe=60d50d3190) | May 05, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [fa5e301933](https://linux-hardware.org/?probe=fa5e301933) | May 05, 2022 |
| ASUSTek       | Rampage III Extreme         | [30ff3d44b0](https://linux-hardware.org/?probe=30ff3d44b0) | May 04, 2022 |
| Gigabyte      | G41MT-S2P                   | [c3ae8f35f9](https://linux-hardware.org/?probe=c3ae8f35f9) | May 04, 2022 |
| ASUSTek       | Z170-E                      | [99d850c205](https://linux-hardware.org/?probe=99d850c205) | May 04, 2022 |
| ASUSTek       | VM65N-K                     | [9df63c1d99](https://linux-hardware.org/?probe=9df63c1d99) | May 04, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [1d475f29ce](https://linux-hardware.org/?probe=1d475f29ce) | May 03, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [7d9a2b425f](https://linux-hardware.org/?probe=7d9a2b425f) | May 03, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [9fa64d179d](https://linux-hardware.org/?probe=9fa64d179d) | May 03, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [a134998640](https://linux-hardware.org/?probe=a134998640) | May 03, 2022 |
| MSI           | H97 GAMING 3                | [c3694433d0](https://linux-hardware.org/?probe=c3694433d0) | May 03, 2022 |
| Dell          | 0YNVJG A01                  | [7a6aa0c236](https://linux-hardware.org/?probe=7a6aa0c236) | May 03, 2022 |
| JINGSHA       | Unknown                     | [94dd890d71](https://linux-hardware.org/?probe=94dd890d71) | May 02, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [b7709ed1c5](https://linux-hardware.org/?probe=b7709ed1c5) | May 02, 2022 |
| ASRock        | X399 Taichi                 | [510cfcefd5](https://linux-hardware.org/?probe=510cfcefd5) | May 02, 2022 |
| ASUSTek       | PRIME B450M-A               | [fac138a25c](https://linux-hardware.org/?probe=fac138a25c) | May 02, 2022 |
| HP            | 8459                        | [21d5d92fda](https://linux-hardware.org/?probe=21d5d92fda) | May 01, 2022 |
| Gigabyte      | H97-Gaming 3                | [150f5a4bd0](https://linux-hardware.org/?probe=150f5a4bd0) | Apr 30, 2022 |
| ASUSTek       | A55M-E                      | [eed78fb5ab](https://linux-hardware.org/?probe=eed78fb5ab) | Apr 30, 2022 |
| JINGSHA       | Unknown                     | [e1b9c4eab0](https://linux-hardware.org/?probe=e1b9c4eab0) | Apr 30, 2022 |
| ASUSTek       | PRIME X470-PRO              | [8c1bf73769](https://linux-hardware.org/?probe=8c1bf73769) | Apr 28, 2022 |
| Gigabyte      | B450 AORUS M                | [de4ae72708](https://linux-hardware.org/?probe=de4ae72708) | Apr 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | [185c64fa0d](https://linux-hardware.org/?probe=185c64fa0d) | Apr 27, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [11a6c8f173](https://linux-hardware.org/?probe=11a6c8f173) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [80792ef9d7](https://linux-hardware.org/?probe=80792ef9d7) | Apr 27, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | [93c883ef59](https://linux-hardware.org/?probe=93c883ef59) | Apr 26, 2022 |
| Unknown       | 1.0                         | [7c17b2186e](https://linux-hardware.org/?probe=7c17b2186e) | Apr 26, 2022 |
| Biostar       | G31M+                       | [b756b9bc9f](https://linux-hardware.org/?probe=b756b9bc9f) | Apr 26, 2022 |
| Gigabyte      | H77N-WIFI                   | [205ae74d07](https://linux-hardware.org/?probe=205ae74d07) | Apr 26, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [35975b7d55](https://linux-hardware.org/?probe=35975b7d55) | Apr 25, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [b24ac490a1](https://linux-hardware.org/?probe=b24ac490a1) | Apr 25, 2022 |
| HP            | 212B                        | [f202f01728](https://linux-hardware.org/?probe=f202f01728) | Apr 25, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [c0af99fa7e](https://linux-hardware.org/?probe=c0af99fa7e) | Apr 24, 2022 |
| Lenovo        | SDK0E50510 WIN              | [de010dfc55](https://linux-hardware.org/?probe=de010dfc55) | Apr 24, 2022 |
| MSI           | B250M PRO-VDH               | [a1ff9cf092](https://linux-hardware.org/?probe=a1ff9cf092) | Apr 24, 2022 |
| HP            | 821D                        | [6a70c646a5](https://linux-hardware.org/?probe=6a70c646a5) | Apr 24, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | [e686789a94](https://linux-hardware.org/?probe=e686789a94) | Apr 24, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [3f1d42f10f](https://linux-hardware.org/?probe=3f1d42f10f) | Apr 24, 2022 |
| Dell          | 04GJJT A00                  | [73fe079eb6](https://linux-hardware.org/?probe=73fe079eb6) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [2bcb31328e](https://linux-hardware.org/?probe=2bcb31328e) | Apr 23, 2022 |
| HP            | 8053                        | [f214dbdf74](https://linux-hardware.org/?probe=f214dbdf74) | Apr 23, 2022 |
| HP            | 8768 A                      | [a939560d30](https://linux-hardware.org/?probe=a939560d30) | Apr 22, 2022 |
| AMI           | Cherry Trail Tablet         | [a2179e3116](https://linux-hardware.org/?probe=a2179e3116) | Apr 22, 2022 |
| Gateway       | SX2185                      | [d22bb794a1](https://linux-hardware.org/?probe=d22bb794a1) | Apr 22, 2022 |
| Dell          | 06NWYK A00                  | [e67d861aba](https://linux-hardware.org/?probe=e67d861aba) | Apr 22, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [bb2195b690](https://linux-hardware.org/?probe=bb2195b690) | Apr 21, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [074f40a67b](https://linux-hardware.org/?probe=074f40a67b) | Apr 21, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [8034b9ae8c](https://linux-hardware.org/?probe=8034b9ae8c) | Apr 21, 2022 |
| Dell          | 04GJJT A00                  | [5f2f4d715e](https://linux-hardware.org/?probe=5f2f4d715e) | Apr 21, 2022 |
| ASUSTek       | Z170-P                      | [aa004d1627](https://linux-hardware.org/?probe=aa004d1627) | Apr 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [93a5ff0ad9](https://linux-hardware.org/?probe=93a5ff0ad9) | Apr 21, 2022 |
| MSI           | Z170A GAMING M3             | [84f6645ca5](https://linux-hardware.org/?probe=84f6645ca5) | Apr 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4daf24b44d](https://linux-hardware.org/?probe=4daf24b44d) | Apr 20, 2022 |
| Foxconn       | 2AB1                        | [f32b27ae86](https://linux-hardware.org/?probe=f32b27ae86) | Apr 20, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [7969fc986b](https://linux-hardware.org/?probe=7969fc986b) | Apr 20, 2022 |
| MSI           | B550-A PRO                  | [3af8357ab9](https://linux-hardware.org/?probe=3af8357ab9) | Apr 20, 2022 |
| Lenovo        | 3098 NOK                    | [a9126e3886](https://linux-hardware.org/?probe=a9126e3886) | Apr 19, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [0e53d4286d](https://linux-hardware.org/?probe=0e53d4286d) | Apr 19, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [14fa81fab9](https://linux-hardware.org/?probe=14fa81fab9) | Apr 18, 2022 |
| ASUSTek       | WS C422 SAGE/10G            | [27db6c7db6](https://linux-hardware.org/?probe=27db6c7db6) | Apr 18, 2022 |
| ECS           | H310H5-M2                   | [653fae2086](https://linux-hardware.org/?probe=653fae2086) | Apr 18, 2022 |
| ASRock        | Z87 Extreme6                | [d7e24821ee](https://linux-hardware.org/?probe=d7e24821ee) | Apr 18, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [cc4a1b8b6f](https://linux-hardware.org/?probe=cc4a1b8b6f) | Apr 17, 2022 |
| Intel         | DH61BE AAG14062-206         | [4816f51374](https://linux-hardware.org/?probe=4816f51374) | Apr 17, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [4dbd302f8c](https://linux-hardware.org/?probe=4dbd302f8c) | Apr 17, 2022 |
| Dell          | 0DN075                      | [05bd1b50f1](https://linux-hardware.org/?probe=05bd1b50f1) | Apr 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | [0ce9091731](https://linux-hardware.org/?probe=0ce9091731) | Apr 16, 2022 |
| Unknown       | HX90                        | [a9b1d5a579](https://linux-hardware.org/?probe=a9b1d5a579) | Apr 15, 2022 |
| ASRock        | H110M-DGS R3.0              | [aa36281de8](https://linux-hardware.org/?probe=aa36281de8) | Apr 15, 2022 |
| Biostar       | G31M+                       | [bbc349a405](https://linux-hardware.org/?probe=bbc349a405) | Apr 15, 2022 |
| ASUSTek       | A55M-E                      | [76a80df275](https://linux-hardware.org/?probe=76a80df275) | Apr 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [edca3eae97](https://linux-hardware.org/?probe=edca3eae97) | Apr 15, 2022 |
| ASUSTek       | A55M-E                      | [74b8687993](https://linux-hardware.org/?probe=74b8687993) | Apr 15, 2022 |
| Dell          | 0WMJ54 A01                  | [d113301081](https://linux-hardware.org/?probe=d113301081) | Apr 14, 2022 |
| Fujitsu       | D3513-A1 S26361-D3513-A1    | [72b9c04a51](https://linux-hardware.org/?probe=72b9c04a51) | Apr 14, 2022 |
| BESSTAR Te... | HM80                        | [80b368187a](https://linux-hardware.org/?probe=80b368187a) | Apr 14, 2022 |
| MSI           | B250M MORTAR                | [8bf9715804](https://linux-hardware.org/?probe=8bf9715804) | Apr 14, 2022 |
| Lenovo        | 3098 NOK                    | [45b5664eb1](https://linux-hardware.org/?probe=45b5664eb1) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f28318e17b](https://linux-hardware.org/?probe=f28318e17b) | Apr 14, 2022 |
| Foxconn       | 2AB1                        | [0276364302](https://linux-hardware.org/?probe=0276364302) | Apr 14, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [43aa5ccd47](https://linux-hardware.org/?probe=43aa5ccd47) | Apr 14, 2022 |
| ASUSTek       | Crosshair V Formula         | [3b66db6997](https://linux-hardware.org/?probe=3b66db6997) | Apr 14, 2022 |
| Gigabyte      | A320M-S2H-CF                | [a5c9b7fc78](https://linux-hardware.org/?probe=a5c9b7fc78) | Apr 14, 2022 |
| ASUSTek       | X79-DELUXE                  | [77d75fd5b2](https://linux-hardware.org/?probe=77d75fd5b2) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [7e080e5205](https://linux-hardware.org/?probe=7e080e5205) | Apr 14, 2022 |
| MSI           | MEG B550 UNIFY              | [8ebb61ef39](https://linux-hardware.org/?probe=8ebb61ef39) | Apr 14, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [cf0c239670](https://linux-hardware.org/?probe=cf0c239670) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [9af096ef7f](https://linux-hardware.org/?probe=9af096ef7f) | Apr 13, 2022 |
| ASUSTek       | M5A97 R2.0                  | [0dddcf5626](https://linux-hardware.org/?probe=0dddcf5626) | Apr 13, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [6ac57575d9](https://linux-hardware.org/?probe=6ac57575d9) | Apr 13, 2022 |
| System76      | Thelio Mira thelio-mira-... | [70b154b039](https://linux-hardware.org/?probe=70b154b039) | Apr 13, 2022 |
| ASUSTek       | H97-PLUS                    | [234fd15d56](https://linux-hardware.org/?probe=234fd15d56) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [18a9612e64](https://linux-hardware.org/?probe=18a9612e64) | Apr 13, 2022 |
| MSI           | Z390-A PRO                  | [bfec30bf8d](https://linux-hardware.org/?probe=bfec30bf8d) | Apr 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [dc6799506a](https://linux-hardware.org/?probe=dc6799506a) | Apr 13, 2022 |
| System76      | Thelio Mira thelio-mira-... | [46ce27bfa6](https://linux-hardware.org/?probe=46ce27bfa6) | Apr 13, 2022 |
| HP            | 805D                        | [56634964fb](https://linux-hardware.org/?probe=56634964fb) | Apr 13, 2022 |
| MSI           | B450M PRO-VDH MAX           | [3656e85663](https://linux-hardware.org/?probe=3656e85663) | Apr 12, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [52828f419f](https://linux-hardware.org/?probe=52828f419f) | Apr 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [be0d616e99](https://linux-hardware.org/?probe=be0d616e99) | Apr 12, 2022 |
| Foxconn       | 2AB1                        | [e43f2609cc](https://linux-hardware.org/?probe=e43f2609cc) | Apr 12, 2022 |
| Lenovo        | ThinkCentre M91P 7034A2U    | [a5b9a57a64](https://linux-hardware.org/?probe=a5b9a57a64) | Apr 12, 2022 |
| Gigabyte      | X99-UD4-CF                  | [70644a292c](https://linux-hardware.org/?probe=70644a292c) | Apr 12, 2022 |
| Gigabyte      | X99-UD4-CF                  | [d08d83ac3a](https://linux-hardware.org/?probe=d08d83ac3a) | Apr 12, 2022 |
| MSI           | G31TM-P21                   | [8879fa758a](https://linux-hardware.org/?probe=8879fa758a) | Apr 11, 2022 |
| ASRock        | EP2C602-4L/D16              | [938b601307](https://linux-hardware.org/?probe=938b601307) | Apr 11, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [222189213d](https://linux-hardware.org/?probe=222189213d) | Apr 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [285b194f70](https://linux-hardware.org/?probe=285b194f70) | Apr 11, 2022 |
| ASRock        | B560M Steel Legend          | [90a9483531](https://linux-hardware.org/?probe=90a9483531) | Apr 10, 2022 |
| Dell          | 0DN075                      | [043e18273e](https://linux-hardware.org/?probe=043e18273e) | Apr 10, 2022 |
| Dell          | 0DN075                      | [759d8d5556](https://linux-hardware.org/?probe=759d8d5556) | Apr 10, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [1638359c7b](https://linux-hardware.org/?probe=1638359c7b) | Apr 10, 2022 |
| ASRock        | Z270 Professional Gaming... | [9129317f19](https://linux-hardware.org/?probe=9129317f19) | Apr 10, 2022 |
| Alienware     | 0J560M A00                  | [a0b422480a](https://linux-hardware.org/?probe=a0b422480a) | Apr 09, 2022 |
| ASUSTek       | AM1M-A                      | [1a910e93c5](https://linux-hardware.org/?probe=1a910e93c5) | Apr 09, 2022 |
| ASUSTek       | AM1M-A                      | [2d350f40d2](https://linux-hardware.org/?probe=2d350f40d2) | Apr 09, 2022 |
| ASRock        | FM2A75 Pro4                 | [e6281eef7f](https://linux-hardware.org/?probe=e6281eef7f) | Apr 09, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [fe293471a7](https://linux-hardware.org/?probe=fe293471a7) | Apr 08, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [d42f8f3535](https://linux-hardware.org/?probe=d42f8f3535) | Apr 08, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | [cdf784520e](https://linux-hardware.org/?probe=cdf784520e) | Apr 08, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [7438fcdda2](https://linux-hardware.org/?probe=7438fcdda2) | Apr 08, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [7305c4d766](https://linux-hardware.org/?probe=7305c4d766) | Apr 08, 2022 |
| ASUSTek       | B85M-G                      | [f812d0803f](https://linux-hardware.org/?probe=f812d0803f) | Apr 08, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | [10458d0000](https://linux-hardware.org/?probe=10458d0000) | Apr 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6eb6b5ebaf](https://linux-hardware.org/?probe=6eb6b5ebaf) | Apr 08, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [e50ab269b2](https://linux-hardware.org/?probe=e50ab269b2) | Apr 06, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [56244d6def](https://linux-hardware.org/?probe=56244d6def) | Apr 06, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [05e3166f60](https://linux-hardware.org/?probe=05e3166f60) | Apr 06, 2022 |
| ASRock        | X570 Phantom Gaming 4 Wi... | [e20e2247c0](https://linux-hardware.org/?probe=e20e2247c0) | Apr 06, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [b1050b51ec](https://linux-hardware.org/?probe=b1050b51ec) | Apr 05, 2022 |
| ASRock        | B450 Pro4                   | [65e855a6a5](https://linux-hardware.org/?probe=65e855a6a5) | Apr 05, 2022 |
| HP            | 1494                        | [5d81c1dd3c](https://linux-hardware.org/?probe=5d81c1dd3c) | Apr 05, 2022 |
| ASUSTek       | ROG STRIX Z590-I GAMING ... | [770088302a](https://linux-hardware.org/?probe=770088302a) | Apr 05, 2022 |
| ASUSTek       | A55BM-K                     | [c0832d15d0](https://linux-hardware.org/?probe=c0832d15d0) | Apr 03, 2022 |
| ASRock        | C2750D4I                    | [b328ff82c5](https://linux-hardware.org/?probe=b328ff82c5) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [a5c5028fde](https://linux-hardware.org/?probe=a5c5028fde) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [d978436f5f](https://linux-hardware.org/?probe=d978436f5f) | Apr 03, 2022 |
| MSI           | H81M-E34                    | [fad24f9efc](https://linux-hardware.org/?probe=fad24f9efc) | Apr 03, 2022 |
| Lenovo        | ThinkCentre M91p 7033HS8    | [0fab8669e0](https://linux-hardware.org/?probe=0fab8669e0) | Apr 02, 2022 |
| MSI           | Z97 GAMING 5                | [8bd2b269ff](https://linux-hardware.org/?probe=8bd2b269ff) | Apr 02, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [1de292a85c](https://linux-hardware.org/?probe=1de292a85c) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [3bcc5c9790](https://linux-hardware.org/?probe=3bcc5c9790) | Apr 02, 2022 |
| Acer          | Aspire TC-895 V:1.0         | [6b2cbca4b2](https://linux-hardware.org/?probe=6b2cbca4b2) | Apr 02, 2022 |
| ASRock        | X399 Taichi                 | [4696339b4e](https://linux-hardware.org/?probe=4696339b4e) | Apr 02, 2022 |
| MSI           | Z590-A PRO                  | [cafa6713f0](https://linux-hardware.org/?probe=cafa6713f0) | Apr 01, 2022 |
| Gigabyte      | B460M D3H                   | [7c159eefd8](https://linux-hardware.org/?probe=7c159eefd8) | Apr 01, 2022 |
| ASUSTek       | B85M-E                      | [b81a77ca49](https://linux-hardware.org/?probe=b81a77ca49) | Apr 01, 2022 |
| MSI           | B85-G43 GAMING              | [70574c396b](https://linux-hardware.org/?probe=70574c396b) | Mar 31, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [b08e7d8589](https://linux-hardware.org/?probe=b08e7d8589) | Mar 31, 2022 |
| ASRock        | H510M-HVS R2.0              | [a4ad860e3d](https://linux-hardware.org/?probe=a4ad860e3d) | Mar 31, 2022 |
| MSI           | X570-A PRO                  | [0813d4bc9e](https://linux-hardware.org/?probe=0813d4bc9e) | Mar 31, 2022 |
| MSI           | X570-A PRO                  | [defac75126](https://linux-hardware.org/?probe=defac75126) | Mar 31, 2022 |
| ASUSTek       | M5A97 EVO                   | [96cd3f3a03](https://linux-hardware.org/?probe=96cd3f3a03) | Mar 31, 2022 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | [a9cf0523c2](https://linux-hardware.org/?probe=a9cf0523c2) | Mar 31, 2022 |
| Gigabyte      | M68MT-S2P                   | [c2daebfd60](https://linux-hardware.org/?probe=c2daebfd60) | Mar 30, 2022 |
| ASUSTek       | PRIME X470-PRO              | [3cd8bdb60c](https://linux-hardware.org/?probe=3cd8bdb60c) | Mar 30, 2022 |
| Gigabyte      | X99-UD4-CF                  | [e6075f51f5](https://linux-hardware.org/?probe=e6075f51f5) | Mar 30, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [2491111c9d](https://linux-hardware.org/?probe=2491111c9d) | Mar 30, 2022 |
| HP            | 82A2                        | [5736762c06](https://linux-hardware.org/?probe=5736762c06) | Mar 28, 2022 |
| ASUSTek       | P8Z68-V GEN3                | [e4c1632bc2](https://linux-hardware.org/?probe=e4c1632bc2) | Mar 28, 2022 |
| ASUSTek       | P5Q-PRO                     | [c5d26f3dc7](https://linux-hardware.org/?probe=c5d26f3dc7) | Mar 27, 2022 |
| ASUSTek       | P5Q-PRO                     | [53da8c0cdf](https://linux-hardware.org/?probe=53da8c0cdf) | Mar 27, 2022 |
| Gigabyte      | B450 AORUS M                | [51c0f63296](https://linux-hardware.org/?probe=51c0f63296) | Mar 27, 2022 |
| AAEON         | IMBA-H110A V1.0             | [9c0577803f](https://linux-hardware.org/?probe=9c0577803f) | Mar 27, 2022 |
| AAEON         | IMBA-H110A V1.0             | [a296d4597c](https://linux-hardware.org/?probe=a296d4597c) | Mar 27, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [e04592bee1](https://linux-hardware.org/?probe=e04592bee1) | Mar 27, 2022 |
| Dell          | 0M6C7G A00                  | [d214df0c57](https://linux-hardware.org/?probe=d214df0c57) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [8252c302e2](https://linux-hardware.org/?probe=8252c302e2) | Mar 27, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [ce82ab584b](https://linux-hardware.org/?probe=ce82ab584b) | Mar 26, 2022 |
| ASUSTek       | PRIME Z490-A                | [91b7f328b1](https://linux-hardware.org/?probe=91b7f328b1) | Mar 26, 2022 |
| ASUSTek       | PRIME Z490-A                | [48ce1c3bd8](https://linux-hardware.org/?probe=48ce1c3bd8) | Mar 26, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [029e0a790e](https://linux-hardware.org/?probe=029e0a790e) | Mar 26, 2022 |
| ASUSTek       | STRIX B250F GAMING          | [c8acfed97a](https://linux-hardware.org/?probe=c8acfed97a) | Mar 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [a68ce8edaf](https://linux-hardware.org/?probe=a68ce8edaf) | Mar 26, 2022 |
| ASUSTek       | P8H61-MX USB3               | [949d5ffcf5](https://linux-hardware.org/?probe=949d5ffcf5) | Mar 26, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [90299bc344](https://linux-hardware.org/?probe=90299bc344) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [6190e57794](https://linux-hardware.org/?probe=6190e57794) | Mar 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | [49853bb240](https://linux-hardware.org/?probe=49853bb240) | Mar 25, 2022 |
| ASRock        | G41M-VS3                    | [34ccbe7db2](https://linux-hardware.org/?probe=34ccbe7db2) | Mar 25, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [2424807acb](https://linux-hardware.org/?probe=2424807acb) | Mar 24, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [d6d6620190](https://linux-hardware.org/?probe=d6d6620190) | Mar 24, 2022 |
| BESSTAR Te... | UM700                       | [b1ff998755](https://linux-hardware.org/?probe=b1ff998755) | Mar 24, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [25d5cba9dc](https://linux-hardware.org/?probe=25d5cba9dc) | Mar 24, 2022 |
| Gigabyte      | B450M DS3H-CF               | [c10b664e4e](https://linux-hardware.org/?probe=c10b664e4e) | Mar 24, 2022 |
| Intel         | DH61BE AAG14062-206         | [08a352b1d2](https://linux-hardware.org/?probe=08a352b1d2) | Mar 24, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [6136cfa920](https://linux-hardware.org/?probe=6136cfa920) | Mar 24, 2022 |
| Dell          | 08HPGT A01                  | [440e4d8b48](https://linux-hardware.org/?probe=440e4d8b48) | Mar 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [86c831ce79](https://linux-hardware.org/?probe=86c831ce79) | Mar 23, 2022 |
| Gigabyte      | G1.Sniper Z97               | [3024cce066](https://linux-hardware.org/?probe=3024cce066) | Mar 23, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [188fb139c3](https://linux-hardware.org/?probe=188fb139c3) | Mar 21, 2022 |
| ABIT          | IP35-E                      | [9d6e95572e](https://linux-hardware.org/?probe=9d6e95572e) | Mar 21, 2022 |
| ABIT          | IP35-E                      | [3d93ef42c9](https://linux-hardware.org/?probe=3d93ef42c9) | Mar 21, 2022 |
| MSI           | A320M BAZOOKA               | [0c12287476](https://linux-hardware.org/?probe=0c12287476) | Mar 21, 2022 |
| MACHINIST     | X99-G7 V1.0                 | [70a784f09c](https://linux-hardware.org/?probe=70a784f09c) | Mar 21, 2022 |
| ASUSTek       | P8P67                       | [c294e20164](https://linux-hardware.org/?probe=c294e20164) | Mar 21, 2022 |
| ASUSTek       | P8P67                       | [5b9b7903ad](https://linux-hardware.org/?probe=5b9b7903ad) | Mar 21, 2022 |
| ASRock        | Z270 Extreme4               | [0f3a8eb166](https://linux-hardware.org/?probe=0f3a8eb166) | Mar 21, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [279bb03666](https://linux-hardware.org/?probe=279bb03666) | Mar 21, 2022 |
| ASUSTek       | PRIME Z370-P                | [a5937e694a](https://linux-hardware.org/?probe=a5937e694a) | Mar 20, 2022 |
| Gigabyte      | X99-UD4-CF                  | [cdbd9842e1](https://linux-hardware.org/?probe=cdbd9842e1) | Mar 20, 2022 |
| MSI           | B550-A PRO                  | [2f713e8db8](https://linux-hardware.org/?probe=2f713e8db8) | Mar 19, 2022 |
| MACHINIST     | X99-G7 V1.0                 | [ebc42c3206](https://linux-hardware.org/?probe=ebc42c3206) | Mar 19, 2022 |
| MSI           | B550-A PRO                  | [b4a188ad90](https://linux-hardware.org/?probe=b4a188ad90) | Mar 19, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [5415b5f876](https://linux-hardware.org/?probe=5415b5f876) | Mar 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [dc3b3ab391](https://linux-hardware.org/?probe=dc3b3ab391) | Mar 18, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [6f4835e78d](https://linux-hardware.org/?probe=6f4835e78d) | Mar 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [b928348a02](https://linux-hardware.org/?probe=b928348a02) | Mar 17, 2022 |
| ASRock        | B550 Steel Legend           | [c6b6cc1f1d](https://linux-hardware.org/?probe=c6b6cc1f1d) | Mar 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [a3444ce232](https://linux-hardware.org/?probe=a3444ce232) | Mar 16, 2022 |
| Gigabyte      | H61M-USB3V                  | [d5afbde22c](https://linux-hardware.org/?probe=d5afbde22c) | Mar 16, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [b0d9828f83](https://linux-hardware.org/?probe=b0d9828f83) | Mar 16, 2022 |
| ASUSTek       | PRIME B450M-A               | [75a7099e71](https://linux-hardware.org/?probe=75a7099e71) | Mar 15, 2022 |
| ASRock        | H470M-HDV                   | [72a6f7ef1b](https://linux-hardware.org/?probe=72a6f7ef1b) | Mar 13, 2022 |
| Dell          | 08HPGT A02                  | [79211f85fd](https://linux-hardware.org/?probe=79211f85fd) | Mar 13, 2022 |
| MSI           | B85M-E45 2015-08-19         | [90f5d4247e](https://linux-hardware.org/?probe=90f5d4247e) | Mar 13, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [d5d90a423a](https://linux-hardware.org/?probe=d5d90a423a) | Mar 13, 2022 |
| MSI           | 2A9C                        | [99c139f47b](https://linux-hardware.org/?probe=99c139f47b) | Mar 12, 2022 |
| MSI           | X570-A PRO                  | [2bb86501da](https://linux-hardware.org/?probe=2bb86501da) | Mar 12, 2022 |
| ASUSTek       | P8Z77-V LK                  | [21c958ad5f](https://linux-hardware.org/?probe=21c958ad5f) | Mar 12, 2022 |
| HP            | 8767 A                      | [6eca88e86f](https://linux-hardware.org/?probe=6eca88e86f) | Mar 12, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [889e5fe7a3](https://linux-hardware.org/?probe=889e5fe7a3) | Mar 11, 2022 |
| ASUSTek       | PRIME Z390-A                | [dc38e0d85a](https://linux-hardware.org/?probe=dc38e0d85a) | Mar 10, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [4d16610cf3](https://linux-hardware.org/?probe=4d16610cf3) | Mar 10, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [c4d9b11074](https://linux-hardware.org/?probe=c4d9b11074) | Mar 10, 2022 |
| MSI           | 2A9C                        | [2f6380807c](https://linux-hardware.org/?probe=2f6380807c) | Mar 09, 2022 |
| MSI           | 2A9C                        | [4702507c0f](https://linux-hardware.org/?probe=4702507c0f) | Mar 09, 2022 |
| Gigabyte      | H410M H                     | [13a9aa4fb3](https://linux-hardware.org/?probe=13a9aa4fb3) | Mar 08, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [c935c59d99](https://linux-hardware.org/?probe=c935c59d99) | Mar 08, 2022 |
| Gigabyte      | Z68XP-UD3                   | [5fb0149650](https://linux-hardware.org/?probe=5fb0149650) | Mar 08, 2022 |
| ASUSTek       | PRIME X370-A                | [cec3d7b058](https://linux-hardware.org/?probe=cec3d7b058) | Mar 08, 2022 |
| ASUSTek       | M5A78L-M LX3                | [ae9c8e47e2](https://linux-hardware.org/?probe=ae9c8e47e2) | Mar 07, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [f0a65362c5](https://linux-hardware.org/?probe=f0a65362c5) | Mar 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [a544689bd5](https://linux-hardware.org/?probe=a544689bd5) | Mar 06, 2022 |
| Dell          | 0KWVT8 A03                  | [e29f709958](https://linux-hardware.org/?probe=e29f709958) | Mar 05, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [91bb2e28fe](https://linux-hardware.org/?probe=91bb2e28fe) | Mar 05, 2022 |
| Dell          | 0WR7PY A00                  | [19895058a5](https://linux-hardware.org/?probe=19895058a5) | Mar 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [55d8863b7b](https://linux-hardware.org/?probe=55d8863b7b) | Mar 05, 2022 |
| Dell          | 01TN68 A01                  | [f57cafd9b1](https://linux-hardware.org/?probe=f57cafd9b1) | Mar 03, 2022 |
| Dell          | 01TN68 A01                  | [a93c073676](https://linux-hardware.org/?probe=a93c073676) | Mar 03, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [d2e96e523e](https://linux-hardware.org/?probe=d2e96e523e) | Mar 03, 2022 |
| Acer          | Veriton X6620G v1.0         | [01922bdee0](https://linux-hardware.org/?probe=01922bdee0) | Mar 02, 2022 |
| ASUSTek       | PRIME B450M-A               | [eb61ea7985](https://linux-hardware.org/?probe=eb61ea7985) | Mar 02, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [7af526bbb7](https://linux-hardware.org/?probe=7af526bbb7) | Mar 01, 2022 |
| HP            | 212B                        | [c183489268](https://linux-hardware.org/?probe=c183489268) | Mar 01, 2022 |
| Dell          | 0M5DCD A00                  | [884adfefd3](https://linux-hardware.org/?probe=884adfefd3) | Mar 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9d178352ca](https://linux-hardware.org/?probe=9d178352ca) | Mar 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [8a51a8730b](https://linux-hardware.org/?probe=8a51a8730b) | Feb 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [78cc2173d9](https://linux-hardware.org/?probe=78cc2173d9) | Feb 27, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [7ce556e43a](https://linux-hardware.org/?probe=7ce556e43a) | Feb 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [9cdd0eea43](https://linux-hardware.org/?probe=9cdd0eea43) | Feb 26, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [03f2fa46f2](https://linux-hardware.org/?probe=03f2fa46f2) | Feb 26, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [f0692aebbe](https://linux-hardware.org/?probe=f0692aebbe) | Feb 25, 2022 |
| ASUSTek       | H97M-E                      | [d8dec986e8](https://linux-hardware.org/?probe=d8dec986e8) | Feb 25, 2022 |
| ASUSTek       | H97M-E                      | [7b58208c52](https://linux-hardware.org/?probe=7b58208c52) | Feb 25, 2022 |
| MSI           | B350 TOMAHAWK               | [e1ddcb9f9a](https://linux-hardware.org/?probe=e1ddcb9f9a) | Feb 24, 2022 |
| Gigabyte      | B450 AORUS M                | [b94d0c6e20](https://linux-hardware.org/?probe=b94d0c6e20) | Feb 24, 2022 |
| MSI           | B550-A PRO                  | [9d3f01a706](https://linux-hardware.org/?probe=9d3f01a706) | Feb 23, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [228e9e9d0c](https://linux-hardware.org/?probe=228e9e9d0c) | Feb 23, 2022 |
| Lenovo        | 30D2 NOK                    | [108296cf9b](https://linux-hardware.org/?probe=108296cf9b) | Feb 22, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [d32c812d2b](https://linux-hardware.org/?probe=d32c812d2b) | Feb 22, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [0d69aa634e](https://linux-hardware.org/?probe=0d69aa634e) | Feb 22, 2022 |
| ASRock        | B450M Pro4                  | [5825d4fcaf](https://linux-hardware.org/?probe=5825d4fcaf) | Feb 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [67deab7343](https://linux-hardware.org/?probe=67deab7343) | Feb 22, 2022 |
| ASUSTek       | P5QL                        | [2714d59901](https://linux-hardware.org/?probe=2714d59901) | Feb 22, 2022 |
| Gigabyte      | Z690 UD DDR4                | [6c4ff21b02](https://linux-hardware.org/?probe=6c4ff21b02) | Feb 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c8223731dc](https://linux-hardware.org/?probe=c8223731dc) | Feb 21, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [ebca133032](https://linux-hardware.org/?probe=ebca133032) | Feb 21, 2022 |
| Gigabyte      | A320M-S2H-CF                | [558ef9e9d4](https://linux-hardware.org/?probe=558ef9e9d4) | Feb 20, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [34e4b434b4](https://linux-hardware.org/?probe=34e4b434b4) | Feb 20, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [eccaa1c72e](https://linux-hardware.org/?probe=eccaa1c72e) | Feb 19, 2022 |
| Gateway       | DX4860                      | [d28784e189](https://linux-hardware.org/?probe=d28784e189) | Feb 19, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [3d816cc71a](https://linux-hardware.org/?probe=3d816cc71a) | Feb 19, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [b2c662bad6](https://linux-hardware.org/?probe=b2c662bad6) | Feb 18, 2022 |
| Gigabyte      | F2A68HM-S1                  | [83e6228c44](https://linux-hardware.org/?probe=83e6228c44) | Feb 17, 2022 |
| MSI           | A520M-A PRO                 | [dbe8ddd097](https://linux-hardware.org/?probe=dbe8ddd097) | Feb 17, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [f2d47f2d8b](https://linux-hardware.org/?probe=f2d47f2d8b) | Feb 17, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [a74d65bfe6](https://linux-hardware.org/?probe=a74d65bfe6) | Feb 16, 2022 |
| HP            | 82A2                        | [5efad9b732](https://linux-hardware.org/?probe=5efad9b732) | Feb 16, 2022 |
| MSI           | B450-A PRO MAX              | [538072f18d](https://linux-hardware.org/?probe=538072f18d) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e3eee22fef](https://linux-hardware.org/?probe=e3eee22fef) | Feb 16, 2022 |
| Dell          | 08HPGT A02                  | [a6c76eb5f6](https://linux-hardware.org/?probe=a6c76eb5f6) | Feb 15, 2022 |
| Dell          | 08HPGT A02                  | [6d024608a5](https://linux-hardware.org/?probe=6d024608a5) | Feb 15, 2022 |
| MSI           | B450M MORTAR MAX            | [68f6b7dd88](https://linux-hardware.org/?probe=68f6b7dd88) | Feb 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [890fea8813](https://linux-hardware.org/?probe=890fea8813) | Feb 15, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [a82c9b223f](https://linux-hardware.org/?probe=a82c9b223f) | Feb 14, 2022 |
| ECS           | A58F2P-M4                   | [bae5185ab0](https://linux-hardware.org/?probe=bae5185ab0) | Feb 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | [84005ca8f9](https://linux-hardware.org/?probe=84005ca8f9) | Feb 12, 2022 |
| Biostar       | AM1ML                       | [54e50bd790](https://linux-hardware.org/?probe=54e50bd790) | Feb 12, 2022 |
| Biostar       | AM1ML                       | [e933dbc718](https://linux-hardware.org/?probe=e933dbc718) | Feb 12, 2022 |
| ASUSTek       | Maximus VIII HERO           | [359fac7afc](https://linux-hardware.org/?probe=359fac7afc) | Feb 12, 2022 |
| Gigabyte      | B550 GAMING X V2            | [60ee5faa6c](https://linux-hardware.org/?probe=60ee5faa6c) | Feb 10, 2022 |
| Gigabyte      | G41MT-D3                    | [ac4b2855c6](https://linux-hardware.org/?probe=ac4b2855c6) | Feb 10, 2022 |
| ASUSTek       | STRIX B250F GAMING          | [1b903af2df](https://linux-hardware.org/?probe=1b903af2df) | Feb 10, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [87d3fd2916](https://linux-hardware.org/?probe=87d3fd2916) | Feb 09, 2022 |
| ASRock        | Z87 Pro3                    | [dea0b07f08](https://linux-hardware.org/?probe=dea0b07f08) | Feb 08, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [ab81e91207](https://linux-hardware.org/?probe=ab81e91207) | Feb 08, 2022 |
| ASUSTek       | PRIME B450M-K               | [24a7621237](https://linux-hardware.org/?probe=24a7621237) | Feb 08, 2022 |
| Gigabyte      | EP45-DS3L                   | [7966e303e6](https://linux-hardware.org/?probe=7966e303e6) | Feb 07, 2022 |
| ASRock        | X570 Taichi                 | [e7b3bb2161](https://linux-hardware.org/?probe=e7b3bb2161) | Feb 07, 2022 |
| ASRock        | X570 Taichi                 | [97a6c42f5f](https://linux-hardware.org/?probe=97a6c42f5f) | Feb 07, 2022 |
| Gigabyte      | H310M M.2 x.x               | [824af874a4](https://linux-hardware.org/?probe=824af874a4) | Feb 06, 2022 |
| ASRock        | B560M Steel Legend          | [e2a7b380d8](https://linux-hardware.org/?probe=e2a7b380d8) | Feb 06, 2022 |
| MSI           | B450-A PRO MAX              | [830c0232b6](https://linux-hardware.org/?probe=830c0232b6) | Feb 06, 2022 |
| MSI           | Z77A-GD65 GAMING            | [8d2cf11a20](https://linux-hardware.org/?probe=8d2cf11a20) | Feb 06, 2022 |
| Dell          | 0200DY A00                  | [5714dfdd29](https://linux-hardware.org/?probe=5714dfdd29) | Feb 06, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [d7796dd19f](https://linux-hardware.org/?probe=d7796dd19f) | Feb 05, 2022 |
| Supermicro    | X9DRW                       | [432d4db3ea](https://linux-hardware.org/?probe=432d4db3ea) | Feb 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [63a70836f3](https://linux-hardware.org/?probe=63a70836f3) | Feb 05, 2022 |
| Gigabyte      | D525TUD                     | [08962dc9f9](https://linux-hardware.org/?probe=08962dc9f9) | Feb 05, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [cd81e5ce82](https://linux-hardware.org/?probe=cd81e5ce82) | Feb 05, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [cab5335d99](https://linux-hardware.org/?probe=cab5335d99) | Feb 04, 2022 |
| ASUSTek       | M5A97 R2.0                  | [548f756c0e](https://linux-hardware.org/?probe=548f756c0e) | Feb 04, 2022 |
| Gigabyte      | 970A-DS3P                   | [e799f33b3f](https://linux-hardware.org/?probe=e799f33b3f) | Feb 04, 2022 |
| ASUSTek       | PRIME B250M-A               | [9a45aba28e](https://linux-hardware.org/?probe=9a45aba28e) | Feb 03, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | [4df88dcf23](https://linux-hardware.org/?probe=4df88dcf23) | Feb 03, 2022 |
| Gigabyte      | 970A-DS3P                   | [9da6b947f5](https://linux-hardware.org/?probe=9da6b947f5) | Feb 03, 2022 |
| Gigabyte      | D525TUD                     | [83678f76fc](https://linux-hardware.org/?probe=83678f76fc) | Feb 03, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [104c871438](https://linux-hardware.org/?probe=104c871438) | Feb 03, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [dca1097e4a](https://linux-hardware.org/?probe=dca1097e4a) | Feb 02, 2022 |
| Dell          | 0X4H68 A00                  | [3ecad8d7e4](https://linux-hardware.org/?probe=3ecad8d7e4) | Feb 02, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [813bec5fe7](https://linux-hardware.org/?probe=813bec5fe7) | Feb 02, 2022 |
| ASUSTek       | PRIME Z270-P                | [26a4917db5](https://linux-hardware.org/?probe=26a4917db5) | Feb 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7ea870fff3](https://linux-hardware.org/?probe=7ea870fff3) | Feb 02, 2022 |
| ASRock        | A320M-HD R4.0               | [f2dfa50076](https://linux-hardware.org/?probe=f2dfa50076) | Feb 02, 2022 |
| ASUSTek       | P8Z77-V LK                  | [a6321e237c](https://linux-hardware.org/?probe=a6321e237c) | Feb 01, 2022 |
| ASUSTek       | PRIME B360M-A               | [c60e8a85c4](https://linux-hardware.org/?probe=c60e8a85c4) | Feb 01, 2022 |
| Gigabyte      | B450 AORUS M                | [fb9c5fac50](https://linux-hardware.org/?probe=fb9c5fac50) | Feb 01, 2022 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [9ba4b1306f](https://linux-hardware.org/?probe=9ba4b1306f) | Jan 31, 2022 |
| ASUSTek       | H97M-E                      | [d8cbfade46](https://linux-hardware.org/?probe=d8cbfade46) | Jan 31, 2022 |
| MSI           | X99A GAMING PRO CARBON      | [49bd28cbf5](https://linux-hardware.org/?probe=49bd28cbf5) | Jan 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [dc652a6ac4](https://linux-hardware.org/?probe=dc652a6ac4) | Jan 30, 2022 |
| Dell          | 0X4H68 A00                  | [0e6a0c4725](https://linux-hardware.org/?probe=0e6a0c4725) | Jan 29, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [83cdfa61a4](https://linux-hardware.org/?probe=83cdfa61a4) | Jan 28, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [e422d19fb3](https://linux-hardware.org/?probe=e422d19fb3) | Jan 27, 2022 |
| PCWare        | IPMH110G                    | [82ee6777f1](https://linux-hardware.org/?probe=82ee6777f1) | Jan 26, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [267ee0e693](https://linux-hardware.org/?probe=267ee0e693) | Jan 26, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [a72f036b05](https://linux-hardware.org/?probe=a72f036b05) | Jan 26, 2022 |
| Gigabyte      | P55A-UD7                    | [084f158a19](https://linux-hardware.org/?probe=084f158a19) | Jan 26, 2022 |
| MSI           | Z270M MORTAR                | [2493fd0195](https://linux-hardware.org/?probe=2493fd0195) | Jan 26, 2022 |
| ASUSTek       | PRIME B250M-A               | [875671a912](https://linux-hardware.org/?probe=875671a912) | Jan 25, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [ec67e898bd](https://linux-hardware.org/?probe=ec67e898bd) | Jan 24, 2022 |
| HP            | 1497                        | [7761e5755c](https://linux-hardware.org/?probe=7761e5755c) | Jan 24, 2022 |
| MSI           | MEG Z390 GODLIKE            | [dd33a742c9](https://linux-hardware.org/?probe=dd33a742c9) | Jan 24, 2022 |
| Gigabyte      | H110M-H-CF                  | [f8afc9746e](https://linux-hardware.org/?probe=f8afc9746e) | Jan 24, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [3ceffb0902](https://linux-hardware.org/?probe=3ceffb0902) | Jan 24, 2022 |
| MSI           | B450M MORTAR MAX            | [619b081f40](https://linux-hardware.org/?probe=619b081f40) | Jan 23, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [79e2d3dc48](https://linux-hardware.org/?probe=79e2d3dc48) | Jan 23, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [937ad3940c](https://linux-hardware.org/?probe=937ad3940c) | Jan 23, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [1bea66eb77](https://linux-hardware.org/?probe=1bea66eb77) | Jan 23, 2022 |
| Gigabyte      | GA-880GM-UD2H               | [38c5a8b4f6](https://linux-hardware.org/?probe=38c5a8b4f6) | Jan 23, 2022 |
| Gigabyte      | H77N-WIFI                   | [b006be0c8b](https://linux-hardware.org/?probe=b006be0c8b) | Jan 22, 2022 |
| Gigabyte      | D525TUD                     | [db0a0adc46](https://linux-hardware.org/?probe=db0a0adc46) | Jan 22, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [992e0c224c](https://linux-hardware.org/?probe=992e0c224c) | Jan 22, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | [ada27693c4](https://linux-hardware.org/?probe=ada27693c4) | Jan 21, 2022 |
| MSI           | H310M PRO-VH                | [68c71dac17](https://linux-hardware.org/?probe=68c71dac17) | Jan 21, 2022 |
| Gigabyte      | H97-D3H-CF                  | [8e39cc0d01](https://linux-hardware.org/?probe=8e39cc0d01) | Jan 21, 2022 |
| BESSTAR Te... | HM50                        | [ddc2e44fcc](https://linux-hardware.org/?probe=ddc2e44fcc) | Jan 21, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [1b1004081a](https://linux-hardware.org/?probe=1b1004081a) | Jan 21, 2022 |
| Gigabyte      | H81M-S2H                    | [5a010a60d7](https://linux-hardware.org/?probe=5a010a60d7) | Jan 20, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [04926d5643](https://linux-hardware.org/?probe=04926d5643) | Jan 20, 2022 |
| ASUSTek       | ROG Maximus XI FORMULA      | [af3563e3e7](https://linux-hardware.org/?probe=af3563e3e7) | Jan 20, 2022 |
| Gigabyte      | B450 AORUS M                | [a846ee2ac3](https://linux-hardware.org/?probe=a846ee2ac3) | Jan 19, 2022 |
| MSI           | B450-A PRO MAX              | [72415f94c8](https://linux-hardware.org/?probe=72415f94c8) | Jan 19, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [87c1802929](https://linux-hardware.org/?probe=87c1802929) | Jan 19, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [ca82eeb3d3](https://linux-hardware.org/?probe=ca82eeb3d3) | Jan 19, 2022 |
| MSI           | H310M PRO-VH                | [844791ed3e](https://linux-hardware.org/?probe=844791ed3e) | Jan 19, 2022 |
| Dell          | 0PP150 A00                  | [851a920599](https://linux-hardware.org/?probe=851a920599) | Jan 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [c4103d5c5a](https://linux-hardware.org/?probe=c4103d5c5a) | Jan 19, 2022 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | [3dd363739d](https://linux-hardware.org/?probe=3dd363739d) | Jan 18, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [01e009ebd0](https://linux-hardware.org/?probe=01e009ebd0) | Jan 18, 2022 |
| ASUSTek       | Maximus IV GENE-Z           | [e4489c39b8](https://linux-hardware.org/?probe=e4489c39b8) | Jan 18, 2022 |
| Gigabyte      | Z590 AORUS MASTER           | [db8f93ad4a](https://linux-hardware.org/?probe=db8f93ad4a) | Jan 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [7451fd2f02](https://linux-hardware.org/?probe=7451fd2f02) | Jan 17, 2022 |
| HP            | 1494                        | [c03b887753](https://linux-hardware.org/?probe=c03b887753) | Jan 16, 2022 |
| ASUSTek       | PRIME B250-PLUS             | [6a024b63f0](https://linux-hardware.org/?probe=6a024b63f0) | Jan 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [01f17fdaa9](https://linux-hardware.org/?probe=01f17fdaa9) | Jan 16, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [ef86d029ff](https://linux-hardware.org/?probe=ef86d029ff) | Jan 16, 2022 |
| Acer          | Veriton X6620G v1.0         | [8ef5b3632a](https://linux-hardware.org/?probe=8ef5b3632a) | Jan 16, 2022 |
| Dell          | 09M8Y8 A01                  | [d5bd08abac](https://linux-hardware.org/?probe=d5bd08abac) | Jan 16, 2022 |
| Gigabyte      | B250M-D3H-CF                | [339d7aa470](https://linux-hardware.org/?probe=339d7aa470) | Jan 15, 2022 |
| ASUSTek       | PRIME X299-DELUXE           | [6903f0230f](https://linux-hardware.org/?probe=6903f0230f) | Jan 15, 2022 |
| ASUSTek       | PRIME X299-DELUXE           | [c458fb3c47](https://linux-hardware.org/?probe=c458fb3c47) | Jan 15, 2022 |
| ASUSTek       | Q87M-E                      | [30309c0416](https://linux-hardware.org/?probe=30309c0416) | Jan 15, 2022 |
| Dell          | 0NDYHG A01                  | [cc3a8808e7](https://linux-hardware.org/?probe=cc3a8808e7) | Jan 15, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [4151d78b0a](https://linux-hardware.org/?probe=4151d78b0a) | Jan 14, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [322291a7b1](https://linux-hardware.org/?probe=322291a7b1) | Jan 14, 2022 |
| MSI           | B450-A PRO MAX              | [7bf06ab6f0](https://linux-hardware.org/?probe=7bf06ab6f0) | Jan 14, 2022 |
| Gigabyte      | Z490 AORUS MASTER           | [7de1f8971f](https://linux-hardware.org/?probe=7de1f8971f) | Jan 14, 2022 |
| ASUSTek       | Maximus IV GENE-Z           | [e1d5a4a319](https://linux-hardware.org/?probe=e1d5a4a319) | Jan 14, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [bef980429e](https://linux-hardware.org/?probe=bef980429e) | Jan 14, 2022 |
| Gigabyte      | F2A68HM-H                   | [f8b504601e](https://linux-hardware.org/?probe=f8b504601e) | Jan 13, 2022 |
| MSI           | MAG B550M MORTAR            | [c7567b5c29](https://linux-hardware.org/?probe=c7567b5c29) | Jan 13, 2022 |
| Gigabyte      | GA-A55M-DS2                 | [f05cc95e99](https://linux-hardware.org/?probe=f05cc95e99) | Jan 11, 2022 |
| ASRock        | B360M IB-R1                 | [afb5a134ce](https://linux-hardware.org/?probe=afb5a134ce) | Jan 11, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [63db2e4ecc](https://linux-hardware.org/?probe=63db2e4ecc) | Jan 10, 2022 |
| ASRock        | B450 Pro4                   | [3b3b0c2855](https://linux-hardware.org/?probe=3b3b0c2855) | Jan 10, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [132d4e0b47](https://linux-hardware.org/?probe=132d4e0b47) | Jan 10, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [5d7aaea168](https://linux-hardware.org/?probe=5d7aaea168) | Jan 10, 2022 |
| ASUSTek       | H81-GAMER                   | [e123597c40](https://linux-hardware.org/?probe=e123597c40) | Jan 09, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [02fe041d02](https://linux-hardware.org/?probe=02fe041d02) | Jan 09, 2022 |
| MSI           | B350M MORTAR ARCTIC         | [8d51630dcf](https://linux-hardware.org/?probe=8d51630dcf) | Jan 09, 2022 |
| Lenovo        | 369A SDK0F82993 WIN         | [e1141045bf](https://linux-hardware.org/?probe=e1141045bf) | Jan 08, 2022 |
| Gigabyte      | X570S AERO G                | [fc3f2a485a](https://linux-hardware.org/?probe=fc3f2a485a) | Jan 08, 2022 |
| Dell          | 04Y8V0 A02                  | [fa29ca9b4b](https://linux-hardware.org/?probe=fa29ca9b4b) | Jan 08, 2022 |
| Dell          | 04Y8V0 A02                  | [2564a1e4de](https://linux-hardware.org/?probe=2564a1e4de) | Jan 08, 2022 |
| ASUSTek       | Maximus IX CODE             | [32c7db26bd](https://linux-hardware.org/?probe=32c7db26bd) | Jan 08, 2022 |
| Gigabyte      | B75M-D3V                    | [faa71fac97](https://linux-hardware.org/?probe=faa71fac97) | Jan 06, 2022 |
| ASUSTek       | PRIME B360M-A               | [3b6e3858d5](https://linux-hardware.org/?probe=3b6e3858d5) | Jan 06, 2022 |
| ASUSTek       | Z77-A                       | [627b0162be](https://linux-hardware.org/?probe=627b0162be) | Jan 06, 2022 |
| Gigabyte      | B450 AORUS M                | [9ebb75d7a4](https://linux-hardware.org/?probe=9ebb75d7a4) | Jan 06, 2022 |
| XFX           | nForce 780i 3-Way SLI 1     | [b56f576ff8](https://linux-hardware.org/?probe=b56f576ff8) | Jan 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [75db843d7d](https://linux-hardware.org/?probe=75db843d7d) | Jan 04, 2022 |
| ASRock        | H110M-HDV R3.0              | [90fe76c900](https://linux-hardware.org/?probe=90fe76c900) | Jan 03, 2022 |
| HP            | 1495                        | [6298747a55](https://linux-hardware.org/?probe=6298747a55) | Jan 03, 2022 |
| ASRock        | H81M-HG4 R4.0               | [282277fa58](https://linux-hardware.org/?probe=282277fa58) | Jan 02, 2022 |
| MSI           | Z97S SLI Krait Edition      | [abff969a99](https://linux-hardware.org/?probe=abff969a99) | Jan 02, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [b4049969e7](https://linux-hardware.org/?probe=b4049969e7) | Jan 02, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [c5e569b5c7](https://linux-hardware.org/?probe=c5e569b5c7) | Jan 02, 2022 |
| ASRock        | B360M IB-R1                 | [f300f71e62](https://linux-hardware.org/?probe=f300f71e62) | Jan 02, 2022 |
| Gigabyte      | EP45-DS3L                   | [5d9026b1c0](https://linux-hardware.org/?probe=5d9026b1c0) | Jan 01, 2022 |
| Gigabyte      | G41MT-D3                    | [9c2f65c964](https://linux-hardware.org/?probe=9c2f65c964) | Jan 01, 2022 |
| Dell          | 0T7D40 A01                  | [4fce685dae](https://linux-hardware.org/?probe=4fce685dae) | Jan 01, 2022 |
| Dell          | 0T7D40 A01                  | [4ce7ea3bb0](https://linux-hardware.org/?probe=4ce7ea3bb0) | Dec 31, 2021 |
| Intel         | SKYBAY                      | [043f80cded](https://linux-hardware.org/?probe=043f80cded) | Dec 31, 2021 |
| ASUSTek       | PRIME B450M-A               | [58cb628601](https://linux-hardware.org/?probe=58cb628601) | Dec 31, 2021 |
| Gigabyte      | F2A88XM-DS2P                | [75eea6ae2f](https://linux-hardware.org/?probe=75eea6ae2f) | Dec 30, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [00f3b181b3](https://linux-hardware.org/?probe=00f3b181b3) | Dec 30, 2021 |
| MSI           | X370 GAMING PLUS            | [49f7093e8c](https://linux-hardware.org/?probe=49f7093e8c) | Dec 29, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [47edce55a4](https://linux-hardware.org/?probe=47edce55a4) | Dec 29, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [e3297eb51f](https://linux-hardware.org/?probe=e3297eb51f) | Dec 29, 2021 |
| Gigabyte      | TRX40 AORUS XTREME          | [cbf9ee4a86](https://linux-hardware.org/?probe=cbf9ee4a86) | Dec 28, 2021 |
| MSI           | H81M-E33                    | [a7e25b05e2](https://linux-hardware.org/?probe=a7e25b05e2) | Dec 27, 2021 |
| XFX           | nForce 780i 3-Way SLI 1     | [36da2e6d4e](https://linux-hardware.org/?probe=36da2e6d4e) | Dec 26, 2021 |
| ASUSTek       | M2N-E                       | [3a08145f4b](https://linux-hardware.org/?probe=3a08145f4b) | Dec 24, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [ca0f62a716](https://linux-hardware.org/?probe=ca0f62a716) | Dec 24, 2021 |
| MSI           | MEG Z390 GODLIKE            | [f1e535b5ba](https://linux-hardware.org/?probe=f1e535b5ba) | Dec 24, 2021 |
| Gigabyte      | Z390 M-CF                   | [6efc5bede0](https://linux-hardware.org/?probe=6efc5bede0) | Dec 23, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [4cd052492e](https://linux-hardware.org/?probe=4cd052492e) | Dec 23, 2021 |
| MSI           | A320M PRO-VH PLUS           | [27379a7599](https://linux-hardware.org/?probe=27379a7599) | Dec 22, 2021 |
| MSI           | PRO Z690-A WIFI DDR4        | [51a7e08e9a](https://linux-hardware.org/?probe=51a7e08e9a) | Dec 22, 2021 |
| MSI           | X470 GAMING M7 AC           | [9b2acc6ea1](https://linux-hardware.org/?probe=9b2acc6ea1) | Dec 22, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [dd197ecb62](https://linux-hardware.org/?probe=dd197ecb62) | Dec 21, 2021 |
| ASUSTek       | P5G41-M                     | [09352ecc24](https://linux-hardware.org/?probe=09352ecc24) | Dec 21, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [03abaff4ae](https://linux-hardware.org/?probe=03abaff4ae) | Dec 21, 2021 |
| Dell          | 0YJPT1 A00                  | [a92e152a7c](https://linux-hardware.org/?probe=a92e152a7c) | Dec 20, 2021 |
| ASRock        | X399 Taichi                 | [16e27617b9](https://linux-hardware.org/?probe=16e27617b9) | Dec 20, 2021 |
| Gigabyte      | H61M-USB3V                  | [d05d2fe462](https://linux-hardware.org/?probe=d05d2fe462) | Dec 20, 2021 |
| ASUSTek       | PRIME H270-PLUS             | [9c1cf57d74](https://linux-hardware.org/?probe=9c1cf57d74) | Dec 20, 2021 |
| Dell          | 0C522T A03                  | [58f36b9637](https://linux-hardware.org/?probe=58f36b9637) | Dec 20, 2021 |
| Dell          | 0YXT71 A03                  | [0a48d9579b](https://linux-hardware.org/?probe=0a48d9579b) | Dec 19, 2021 |
| MSI           | X370 SLI PLUS               | [adb27f9347](https://linux-hardware.org/?probe=adb27f9347) | Dec 19, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [e2ce1d7284](https://linux-hardware.org/?probe=e2ce1d7284) | Dec 19, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [6653477f61](https://linux-hardware.org/?probe=6653477f61) | Dec 18, 2021 |
| JINGSHA       | Unknown                     | [13da82798c](https://linux-hardware.org/?probe=13da82798c) | Dec 18, 2021 |
| Gigabyte      | H370 HD3-CF                 | [2497b24eda](https://linux-hardware.org/?probe=2497b24eda) | Dec 18, 2021 |
| Gigabyte      | F2A88XM-DS2P                | [c18ddabc8d](https://linux-hardware.org/?probe=c18ddabc8d) | Dec 18, 2021 |
| ASUSTek       | P5G41-M                     | [c073d4a4e9](https://linux-hardware.org/?probe=c073d4a4e9) | Dec 17, 2021 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [b86150c4bd](https://linux-hardware.org/?probe=b86150c4bd) | Dec 16, 2021 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [923f77a787](https://linux-hardware.org/?probe=923f77a787) | Dec 16, 2021 |
| HP            | 805D                        | [dfdc70512c](https://linux-hardware.org/?probe=dfdc70512c) | Dec 16, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [45a411c9fe](https://linux-hardware.org/?probe=45a411c9fe) | Dec 15, 2021 |
| Gigabyte      | TRX40 AORUS MASTER          | [5915e986de](https://linux-hardware.org/?probe=5915e986de) | Dec 15, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [60a7206b05](https://linux-hardware.org/?probe=60a7206b05) | Dec 15, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [660ce7fc74](https://linux-hardware.org/?probe=660ce7fc74) | Dec 15, 2021 |
| Dell          | 0RY007                      | [f3cb490147](https://linux-hardware.org/?probe=f3cb490147) | Dec 14, 2021 |
| Gigabyte      | Z270P-D3-CF                 | [b2dc7c9e05](https://linux-hardware.org/?probe=b2dc7c9e05) | Dec 14, 2021 |
| HP            | 2B2B                        | [bf929a4359](https://linux-hardware.org/?probe=bf929a4359) | Dec 14, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [53523a4ea7](https://linux-hardware.org/?probe=53523a4ea7) | Dec 14, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [3030fcf474](https://linux-hardware.org/?probe=3030fcf474) | Dec 13, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [3616fc5b0e](https://linux-hardware.org/?probe=3616fc5b0e) | Dec 12, 2021 |
| Gigabyte      | B560M DS3H V2               | [169e6793c2](https://linux-hardware.org/?probe=169e6793c2) | Dec 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [021525201e](https://linux-hardware.org/?probe=021525201e) | Dec 12, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [bd4a0c5d2f](https://linux-hardware.org/?probe=bd4a0c5d2f) | Dec 12, 2021 |
| ASUSTek       | P6T                         | [b789a1151e](https://linux-hardware.org/?probe=b789a1151e) | Dec 11, 2021 |
| Gigabyte      | X570 AORUS PRO              | [8ae1043ce6](https://linux-hardware.org/?probe=8ae1043ce6) | Dec 10, 2021 |
| Gigabyte      | 990FXA-UD3                  | [b76ef07c59](https://linux-hardware.org/?probe=b76ef07c59) | Dec 10, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [bf533d0378](https://linux-hardware.org/?probe=bf533d0378) | Dec 09, 2021 |
| Gigabyte      | Z690 UD DDR4                | [d0070c39c4](https://linux-hardware.org/?probe=d0070c39c4) | Dec 09, 2021 |
| Gigabyte      | Z77-D3H                     | [c486c9645b](https://linux-hardware.org/?probe=c486c9645b) | Dec 09, 2021 |
| Dell          | 040DDP A01                  | [b8e92a4957](https://linux-hardware.org/?probe=b8e92a4957) | Dec 09, 2021 |
| ASUSTek       | P6T                         | [d04f9d16a8](https://linux-hardware.org/?probe=d04f9d16a8) | Dec 08, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [82926e68a4](https://linux-hardware.org/?probe=82926e68a4) | Dec 08, 2021 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [bd8742e075](https://linux-hardware.org/?probe=bd8742e075) | Dec 08, 2021 |
| Apple         | Mac-F221BEC8                | [809152313d](https://linux-hardware.org/?probe=809152313d) | Dec 07, 2021 |
| ASUSTek       | SABERTOOTH X79              | [58c6a86730](https://linux-hardware.org/?probe=58c6a86730) | Dec 07, 2021 |
| Gigabyte      | Z97P-D3                     | [abc89c9b78](https://linux-hardware.org/?probe=abc89c9b78) | Dec 07, 2021 |
| XFX           | MI-A78S-8209 Ver1.1         | [5393b5ad7a](https://linux-hardware.org/?probe=5393b5ad7a) | Dec 06, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9e878d83a3](https://linux-hardware.org/?probe=9e878d83a3) | Dec 06, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [0a06cba7c5](https://linux-hardware.org/?probe=0a06cba7c5) | Dec 06, 2021 |
| Lenovo        | 3642 SDK0J40700 WIN 3258... | [82cd98ea5a](https://linux-hardware.org/?probe=82cd98ea5a) | Dec 06, 2021 |
| Lenovo        | 3642 SDK0J40700 WIN 3258... | [07f484651e](https://linux-hardware.org/?probe=07f484651e) | Dec 06, 2021 |
| Gigabyte      | B450 AORUS M                | [18ae64d44d](https://linux-hardware.org/?probe=18ae64d44d) | Dec 05, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [b296e2a320](https://linux-hardware.org/?probe=b296e2a320) | Dec 05, 2021 |
| Dell          | 0M859N A00                  | [f254ee88c6](https://linux-hardware.org/?probe=f254ee88c6) | Dec 05, 2021 |
| MSI           | Z87M GAMING                 | [4ef67e0560](https://linux-hardware.org/?probe=4ef67e0560) | Dec 04, 2021 |
| ASUSTek       | Z87-A                       | [e7d4963834](https://linux-hardware.org/?probe=e7d4963834) | Dec 04, 2021 |
| XFX           | MI-A78S-8209 Ver1.1         | [ce556a2535](https://linux-hardware.org/?probe=ce556a2535) | Dec 04, 2021 |
| Dell          | 0J3C2F A00                  | [bfead2c865](https://linux-hardware.org/?probe=bfead2c865) | Dec 04, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [511a349d7f](https://linux-hardware.org/?probe=511a349d7f) | Dec 03, 2021 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [fd20b7fc56](https://linux-hardware.org/?probe=fd20b7fc56) | Dec 03, 2021 |
| Dell          | 06D7TR A00                  | [8c6244cb77](https://linux-hardware.org/?probe=8c6244cb77) | Dec 03, 2021 |
| MSI           | MEG Z390 GODLIKE            | [ca1727f54a](https://linux-hardware.org/?probe=ca1727f54a) | Dec 02, 2021 |
| Gateway       | SX2185                      | [70e907b207](https://linux-hardware.org/?probe=70e907b207) | Dec 02, 2021 |
| Dell          | 040DDP A01                  | [b108ae97c2](https://linux-hardware.org/?probe=b108ae97c2) | Dec 02, 2021 |
| MSI           | X370 XPOWER GAMING TITAN... | [56bd9b515c](https://linux-hardware.org/?probe=56bd9b515c) | Dec 02, 2021 |
| ASUSTek       | H81M-C                      | [ffecd77f3a](https://linux-hardware.org/?probe=ffecd77f3a) | Dec 02, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [508352ad4a](https://linux-hardware.org/?probe=508352ad4a) | Dec 02, 2021 |
| Gigabyte      | B85M-D3V-A                  | [7304efa5d7](https://linux-hardware.org/?probe=7304efa5d7) | Dec 01, 2021 |
| Huanan        | X99-F8 V2.0                 | [1b4de261b3](https://linux-hardware.org/?probe=1b4de261b3) | Nov 30, 2021 |
| Apple         | Mac-F221BEC8                | [2ceb61c052](https://linux-hardware.org/?probe=2ceb61c052) | Nov 30, 2021 |
| Gigabyte      | EX58-UD3R                   | [8ece12c9e6](https://linux-hardware.org/?probe=8ece12c9e6) | Nov 28, 2021 |
| ECS           | H61H2-CM                    | [525be50825](https://linux-hardware.org/?probe=525be50825) | Nov 28, 2021 |
| Gigabyte      | H170-Gaming 3               | [e83680db56](https://linux-hardware.org/?probe=e83680db56) | Nov 28, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [d813ffb878](https://linux-hardware.org/?probe=d813ffb878) | Nov 28, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [5d5d624d8c](https://linux-hardware.org/?probe=5d5d624d8c) | Nov 27, 2021 |
| MSI           | B450-A PRO MAX              | [d949cb9963](https://linux-hardware.org/?probe=d949cb9963) | Nov 27, 2021 |
| Dell          | 06D7TR A00                  | [d980b32136](https://linux-hardware.org/?probe=d980b32136) | Nov 27, 2021 |
| ASRock        | H81M-HG4 R4.0               | [c23e7e890b](https://linux-hardware.org/?probe=c23e7e890b) | Nov 27, 2021 |
| ASUSTek       | M4A77T/USB3                 | [e23dea02cf](https://linux-hardware.org/?probe=e23dea02cf) | Nov 26, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [1e4799819e](https://linux-hardware.org/?probe=1e4799819e) | Nov 26, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [faf9c22988](https://linux-hardware.org/?probe=faf9c22988) | Nov 26, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | [89729fef47](https://linux-hardware.org/?probe=89729fef47) | Nov 25, 2021 |
| Apple         | Mac-F221BEC8                | [f4f5c37779](https://linux-hardware.org/?probe=f4f5c37779) | Nov 25, 2021 |
| Gigabyte      | Z690 UD DDR4                | [b6ffc90d4e](https://linux-hardware.org/?probe=b6ffc90d4e) | Nov 25, 2021 |
| MSI           | B550-A PRO                  | [b90083da69](https://linux-hardware.org/?probe=b90083da69) | Nov 24, 2021 |
| Apple         | Mac-F221BEC8                | [e606757d4a](https://linux-hardware.org/?probe=e606757d4a) | Nov 24, 2021 |
| Gigabyte      | B550 AORUS PRO              | [35801f40df](https://linux-hardware.org/?probe=35801f40df) | Nov 24, 2021 |
| MSI           | A55M-E33                    | [e6616870b6](https://linux-hardware.org/?probe=e6616870b6) | Nov 24, 2021 |
| HP            | 1906                        | [8ec5c16fc7](https://linux-hardware.org/?probe=8ec5c16fc7) | Nov 24, 2021 |
| HP            | 83E1                        | [7598ac7e6c](https://linux-hardware.org/?probe=7598ac7e6c) | Nov 23, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | [dab6e17223](https://linux-hardware.org/?probe=dab6e17223) | Nov 23, 2021 |
| Lenovo        | 3731 SDK0J40697 WIN 3305... | [c50601fb76](https://linux-hardware.org/?probe=c50601fb76) | Nov 23, 2021 |
| HP            | 0B4Ch D                     | [0c3c7c6bb3](https://linux-hardware.org/?probe=0c3c7c6bb3) | Nov 23, 2021 |
| HP            | 1906                        | [90499fe34d](https://linux-hardware.org/?probe=90499fe34d) | Nov 23, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [91a66a7648](https://linux-hardware.org/?probe=91a66a7648) | Nov 22, 2021 |
| Gigabyte      | GA-MA790X-UD4               | [0a19a35ac4](https://linux-hardware.org/?probe=0a19a35ac4) | Nov 22, 2021 |
| ASRock        | G41M-VS3                    | [35277b1155](https://linux-hardware.org/?probe=35277b1155) | Nov 22, 2021 |
| Pegatron      | 2AD5                        | [8fc4f44be5](https://linux-hardware.org/?probe=8fc4f44be5) | Nov 22, 2021 |
| Gigabyte      | F2A85XM-D3H                 | [1c41d8c34c](https://linux-hardware.org/?probe=1c41d8c34c) | Nov 22, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [683697e6ee](https://linux-hardware.org/?probe=683697e6ee) | Nov 21, 2021 |
| MSI           | B450M-A PRO MAX             | [92375d0ecc](https://linux-hardware.org/?probe=92375d0ecc) | Nov 21, 2021 |
| Dell          | 0M859N A00                  | [2fa52f3236](https://linux-hardware.org/?probe=2fa52f3236) | Nov 21, 2021 |
| Gigabyte      | B450M DS3H-CF               | [faec9a8f8b](https://linux-hardware.org/?probe=faec9a8f8b) | Nov 21, 2021 |
| HP            | 3048h                       | [e38eb769b5](https://linux-hardware.org/?probe=e38eb769b5) | Nov 20, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [44d1a95b0b](https://linux-hardware.org/?probe=44d1a95b0b) | Nov 20, 2021 |
| ASUSTek       | A68HM-K                     | [8bf7660808](https://linux-hardware.org/?probe=8bf7660808) | Nov 19, 2021 |
| ASUSTek       | H87-PRO                     | [02b2e4cb00](https://linux-hardware.org/?probe=02b2e4cb00) | Nov 19, 2021 |
| ASUSTek       | H87-PRO                     | [181c56512d](https://linux-hardware.org/?probe=181c56512d) | Nov 19, 2021 |
| Dell          | 0YNVJG A01                  | [00f5cc73fe](https://linux-hardware.org/?probe=00f5cc73fe) | Nov 19, 2021 |
| Pegatron      | 2AD5                        | [839b5c24aa](https://linux-hardware.org/?probe=839b5c24aa) | Nov 19, 2021 |
| MSI           | B450 TOMAHAWK               | [6a1607ab9d](https://linux-hardware.org/?probe=6a1607ab9d) | Nov 18, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [c8a6893780](https://linux-hardware.org/?probe=c8a6893780) | Nov 18, 2021 |
| MSI           | A320M-A PRO MAX             | [d9f71fda8f](https://linux-hardware.org/?probe=d9f71fda8f) | Nov 18, 2021 |
| Dell          | 0C27VV A01                  | [34aff3ab72](https://linux-hardware.org/?probe=34aff3ab72) | Nov 18, 2021 |
| Gigabyte      | B450M DS3H-CF               | [f35f04cabd](https://linux-hardware.org/?probe=f35f04cabd) | Nov 18, 2021 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | [50535d277c](https://linux-hardware.org/?probe=50535d277c) | Nov 18, 2021 |
| ASUSTek       | PRIME B360M-K               | [3b2165faa8](https://linux-hardware.org/?probe=3b2165faa8) | Nov 18, 2021 |
| Gigabyte      | B550M DS3H                  | [93c3ab9ed1](https://linux-hardware.org/?probe=93c3ab9ed1) | Nov 18, 2021 |
| Gigabyte      | H97M-D3H                    | [f6dc8337e7](https://linux-hardware.org/?probe=f6dc8337e7) | Nov 18, 2021 |
| MSI           | Z77A-G43                    | [04db0a2350](https://linux-hardware.org/?probe=04db0a2350) | Nov 17, 2021 |
| ASRock        | X470 Master SLI             | [c48f95d233](https://linux-hardware.org/?probe=c48f95d233) | Nov 17, 2021 |
| Gigabyte      | H370M DS3H-CF               | [c69f79e654](https://linux-hardware.org/?probe=c69f79e654) | Nov 17, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [ddfb1c2b1a](https://linux-hardware.org/?probe=ddfb1c2b1a) | Nov 17, 2021 |
| Dell          | 0GY6Y8 A02                  | [61734716ea](https://linux-hardware.org/?probe=61734716ea) | Nov 16, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [9404dfb1fe](https://linux-hardware.org/?probe=9404dfb1fe) | Nov 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [3412d5cf0b](https://linux-hardware.org/?probe=3412d5cf0b) | Nov 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [bdd9599f2f](https://linux-hardware.org/?probe=bdd9599f2f) | Nov 16, 2021 |
| ASUSTek       | M2N-E                       | [8da42387a5](https://linux-hardware.org/?probe=8da42387a5) | Nov 15, 2021 |
| Gigabyte      | B560M DS3H                  | [97ed26b846](https://linux-hardware.org/?probe=97ed26b846) | Nov 15, 2021 |
| ASRock        | B450 Pro4                   | [098387cb9c](https://linux-hardware.org/?probe=098387cb9c) | Nov 15, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [bc6a3771aa](https://linux-hardware.org/?probe=bc6a3771aa) | Nov 13, 2021 |
| ASUSTek       | M3A78-EM                    | [e1cc8b1ee3](https://linux-hardware.org/?probe=e1cc8b1ee3) | Nov 13, 2021 |
| ASUSTek       | H61M-CS                     | [22858e9ab9](https://linux-hardware.org/?probe=22858e9ab9) | Nov 13, 2021 |
| Apple         | Mac-F221BEC8                | [5991ba5f44](https://linux-hardware.org/?probe=5991ba5f44) | Nov 12, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [e85856bbef](https://linux-hardware.org/?probe=e85856bbef) | Nov 12, 2021 |
| Dell          | 0DXJD9 A00                  | [e9abfeb7a2](https://linux-hardware.org/?probe=e9abfeb7a2) | Nov 11, 2021 |
| Intel         | D33217GKE G69901-205        | [a922d5f3fc](https://linux-hardware.org/?probe=a922d5f3fc) | Nov 10, 2021 |
| MSI           | Z390-A PRO                  | [ca1489298b](https://linux-hardware.org/?probe=ca1489298b) | Nov 10, 2021 |
| Gigabyte      | X570 UD                     | [c5ae0c1fca](https://linux-hardware.org/?probe=c5ae0c1fca) | Nov 09, 2021 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [189e19c60d](https://linux-hardware.org/?probe=189e19c60d) | Nov 09, 2021 |
| Dell          | 040DDP A01                  | [3587a95d63](https://linux-hardware.org/?probe=3587a95d63) | Nov 09, 2021 |
| Intel         | D33217GKE G69901-205        | [dd1ddaf74f](https://linux-hardware.org/?probe=dd1ddaf74f) | Nov 09, 2021 |
| Dell          | 0HD5W2 A00                  | [09cae8a245](https://linux-hardware.org/?probe=09cae8a245) | Nov 09, 2021 |
| HP            | 2215                        | [4e65fa6078](https://linux-hardware.org/?probe=4e65fa6078) | Nov 09, 2021 |
| Gigabyte      | H97M-D3H                    | [74b5acd6cd](https://linux-hardware.org/?probe=74b5acd6cd) | Nov 08, 2021 |
| ASRock        | A300M-STX                   | [a7510caa6d](https://linux-hardware.org/?probe=a7510caa6d) | Nov 08, 2021 |
| ASRock        | A300M-STX                   | [2eebb6842a](https://linux-hardware.org/?probe=2eebb6842a) | Nov 08, 2021 |
| Seco          | C40 C                       | [27bff03d0c](https://linux-hardware.org/?probe=27bff03d0c) | Nov 08, 2021 |
| MSI           | X570-A PRO                  | [0e47ec7819](https://linux-hardware.org/?probe=0e47ec7819) | Nov 08, 2021 |
| ASUSTek       | PRIME B550M-A               | [ef16e3ad0f](https://linux-hardware.org/?probe=ef16e3ad0f) | Nov 07, 2021 |
| Gigabyte      | EP45-DS3L                   | [3533adc65b](https://linux-hardware.org/?probe=3533adc65b) | Nov 07, 2021 |
| Dell          | 0C522T A03                  | [43d8e3d9d8](https://linux-hardware.org/?probe=43d8e3d9d8) | Nov 07, 2021 |
| ABIT          | AX78                        | [3d56ae3738](https://linux-hardware.org/?probe=3d56ae3738) | Nov 06, 2021 |
| MSI           | MEG X570 UNIFY              | [37685b5198](https://linux-hardware.org/?probe=37685b5198) | Nov 06, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6cce11439f](https://linux-hardware.org/?probe=6cce11439f) | Nov 06, 2021 |
| ASUSTek       | M5A97                       | [f8ce8bca36](https://linux-hardware.org/?probe=f8ce8bca36) | Nov 05, 2021 |
| MSI           | Z97M-G43                    | [7b0e15a051](https://linux-hardware.org/?probe=7b0e15a051) | Nov 05, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [ad6e327cf5](https://linux-hardware.org/?probe=ad6e327cf5) | Nov 05, 2021 |
| ASRock        | G41M-VS3                    | [bf54c2ee53](https://linux-hardware.org/?probe=bf54c2ee53) | Nov 04, 2021 |
| Gigabyte      | H97M-D3H                    | [fa84d0d544](https://linux-hardware.org/?probe=fa84d0d544) | Nov 04, 2021 |
| ASUSTek       | PRIME Z370-P                | [50301dd3e3](https://linux-hardware.org/?probe=50301dd3e3) | Nov 04, 2021 |
| Gigabyte      | B150M-D3H-CF                | [f5ef935897](https://linux-hardware.org/?probe=f5ef935897) | Nov 04, 2021 |
| Gigabyte      | H61M-S2V-B3                 | [5baf0ce3af](https://linux-hardware.org/?probe=5baf0ce3af) | Nov 04, 2021 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [14c9dda4cd](https://linux-hardware.org/?probe=14c9dda4cd) | Nov 04, 2021 |
| MSI           | B450M MORTAR                | [00a97d0eba](https://linux-hardware.org/?probe=00a97d0eba) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | [0243b19a08](https://linux-hardware.org/?probe=0243b19a08) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | [f7d58b572d](https://linux-hardware.org/?probe=f7d58b572d) | Nov 03, 2021 |
| ASUSTek       | P8Z77-V                     | [c7a18968cf](https://linux-hardware.org/?probe=c7a18968cf) | Nov 03, 2021 |
| ASUSTek       | Z87M-PLUS                   | [c26ea680eb](https://linux-hardware.org/?probe=c26ea680eb) | Nov 03, 2021 |
| MSI           | MAG B550M MORTAR            | [10a45363fe](https://linux-hardware.org/?probe=10a45363fe) | Nov 03, 2021 |
| ASRock        | G41M-VS3                    | [2ee1cbdc82](https://linux-hardware.org/?probe=2ee1cbdc82) | Nov 03, 2021 |
| MSI           | B365M PRO-VH                | [c2976ad59c](https://linux-hardware.org/?probe=c2976ad59c) | Nov 03, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [c8716ec9a6](https://linux-hardware.org/?probe=c8716ec9a6) | Nov 03, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [93de1508cb](https://linux-hardware.org/?probe=93de1508cb) | Oct 31, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [136c409f1a](https://linux-hardware.org/?probe=136c409f1a) | Oct 27, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [ae8daa788a](https://linux-hardware.org/?probe=ae8daa788a) | Oct 27, 2021 |
| MSI           | B550-A PRO                  | [91c5853577](https://linux-hardware.org/?probe=91c5853577) | Oct 25, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [fac95138dc](https://linux-hardware.org/?probe=fac95138dc) | Oct 23, 2021 |
| Foxconn       | H81MXV FAB A                | [b030daf542](https://linux-hardware.org/?probe=b030daf542) | Oct 20, 2021 |
| ASUSTek       | PRIME B460M-A               | [6db5e9be6b](https://linux-hardware.org/?probe=6db5e9be6b) | Oct 19, 2021 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | [746401b748](https://linux-hardware.org/?probe=746401b748) | Oct 18, 2021 |
| MSI           | B350 PC MATE                | [bc716e921b](https://linux-hardware.org/?probe=bc716e921b) | Oct 15, 2021 |
| Dell          | 0WMJ54 A01                  | [01ce3b252c](https://linux-hardware.org/?probe=01ce3b252c) | Oct 14, 2021 |
| ASUSTek       | PRIME B550M-A               | [2ff2eb607a](https://linux-hardware.org/?probe=2ff2eb607a) | Oct 14, 2021 |
| ASUSTek       | PRIME A320I-K               | [eee2a960f5](https://linux-hardware.org/?probe=eee2a960f5) | Oct 11, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [7b26df9bc4](https://linux-hardware.org/?probe=7b26df9bc4) | Oct 10, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [f850c51db9](https://linux-hardware.org/?probe=f850c51db9) | Oct 10, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [cfbe862160](https://linux-hardware.org/?probe=cfbe862160) | Oct 10, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [a9ceb4591e](https://linux-hardware.org/?probe=a9ceb4591e) | Oct 09, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [7c210a60ab](https://linux-hardware.org/?probe=7c210a60ab) | Oct 09, 2021 |
| Gigabyte      | H61N-USB3                   | [43ded3a853](https://linux-hardware.org/?probe=43ded3a853) | Oct 09, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b3d0295208](https://linux-hardware.org/?probe=b3d0295208) | Oct 08, 2021 |
| Gigabyte      | H61N-USB3                   | [75d34f09c4](https://linux-hardware.org/?probe=75d34f09c4) | Oct 06, 2021 |
| MSI           | B550-A PRO                  | [17a03c217e](https://linux-hardware.org/?probe=17a03c217e) | Oct 04, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [b6f5c877d4](https://linux-hardware.org/?probe=b6f5c877d4) | Sep 29, 2021 |
| Gigabyte      | H81M-S2H                    | [b8c27bd56c](https://linux-hardware.org/?probe=b8c27bd56c) | Sep 28, 2021 |
| ASRock        | B450M-HDV R4.0              | [2f771e8271](https://linux-hardware.org/?probe=2f771e8271) | Sep 24, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [e75373a634](https://linux-hardware.org/?probe=e75373a634) | Sep 23, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [3875512e39](https://linux-hardware.org/?probe=3875512e39) | Sep 14, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [4fb9ed180b](https://linux-hardware.org/?probe=4fb9ed180b) | Sep 14, 2021 |
| Dell          | 0WMJ54 A01                  | [a94ad8a323](https://linux-hardware.org/?probe=a94ad8a323) | Aug 22, 2021 |
| HP            | 8055                        | [29f5b9a7ab](https://linux-hardware.org/?probe=29f5b9a7ab) | Aug 12, 2021 |
| Dell          | 0KC9NP A01                  | [142e0703fb](https://linux-hardware.org/?probe=142e0703fb) | Aug 12, 2021 |
| ASUSTek       | Maximus V FORMULA           | [466ef3bd27](https://linux-hardware.org/?probe=466ef3bd27) | Jul 29, 2021 |
| Dell          | 0KC9NP A01                  | [6687380bd7](https://linux-hardware.org/?probe=6687380bd7) | Jun 18, 2021 |
| Gigabyte      | F2A88XN-WIFI                | [c22e6d8669](https://linux-hardware.org/?probe=c22e6d8669) | May 25, 2021 |
| ASUSTek       | Maximus V FORMULA           | [3e15dd7136](https://linux-hardware.org/?probe=3e15dd7136) | May 19, 2021 |
| ECS           | MCP61M-M3                   | [2e5b21af19](https://linux-hardware.org/?probe=2e5b21af19) | Apr 17, 2021 |
| ASUSTek       | PRIME X570-PRO              | [3f7cbcea74](https://linux-hardware.org/?probe=3f7cbcea74) | Apr 14, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                       | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| 5.16.18-200.fc35.x86_64                                       | 56       | 9.79%   |
| 5.14.10-300.fc35.x86_64                                       | 35       | 6.12%   |
| 5.15.6-200.fc35.x86_64                                        | 29       | 5.07%   |
| 5.16.16-200.fc35.x86_64                                       | 25       | 4.37%   |
| 5.16.9-200.fc35.x86_64                                        | 22       | 3.85%   |
| 5.17.4-200.fc35.x86_64                                        | 21       | 3.67%   |
| 5.15.12-200.fc35.x86_64                                       | 21       | 3.67%   |
| 5.16.12-200.fc35.x86_64                                       | 20       | 3.5%    |
| 5.14.18-300.fc35.x86_64                                       | 20       | 3.5%    |
| 5.16.20-200.fc35.x86_64                                       | 19       | 3.32%   |
| 5.15.16-200.fc35.x86_64                                       | 17       | 2.97%   |
| 5.14.17-301.fc35.x86_64                                       | 17       | 2.97%   |
| 5.14.16-301.fc35.x86_64                                       | 17       | 2.97%   |
| 5.16.19-200.fc35.x86_64                                       | 14       | 2.45%   |
| 5.15.18-200.fc35.x86_64                                       | 14       | 2.45%   |
| 5.15.14-200.fc35.x86_64                                       | 14       | 2.45%   |
| 5.17.5-200.fc35.x86_64                                        | 13       | 2.27%   |
| 5.16.11-200.fc35.x86_64                                       | 13       | 2.27%   |
| 5.14.14-300.fc35.x86_64                                       | 13       | 2.27%   |
| 5.16.5-200.fc35.x86_64                                        | 12       | 2.1%    |
| 5.16.15-201.fc35.x86_64                                       | 11       | 1.92%   |
| 5.15.8-200.fc35.x86_64                                        | 11       | 1.92%   |
| 5.14.15-300.fc35.x86_64                                       | 11       | 1.92%   |
| 5.15.13-200.fc35.x86_64                                       | 10       | 1.75%   |
| 5.15.11-200.fc35.x86_64                                       | 9        | 1.57%   |
| 5.16.8-200.fc35.x86_64                                        | 7        | 1.22%   |
| 5.15.15-200.fc35.x86_64                                       | 7        | 1.22%   |
| 5.15.10-200.fc35.x86_64                                       | 7        | 1.22%   |
| 5.16.7-200.fc35.x86_64                                        | 6        | 1.05%   |
| 5.15.5-200.fc35.x86_64                                        | 6        | 1.05%   |
| 5.15.17-200.fc35.x86_64                                       | 6        | 1.05%   |
| 5.15.4-201.fc35.x86_64                                        | 5        | 0.87%   |
| 5.14.9-300.fc35.x86_64                                        | 5        | 0.87%   |
| 5.16.14-200.fc35.x86_64                                       | 4        | 0.7%    |
| 5.16.13-200.fc35.x86_64                                       | 4        | 0.7%    |
| 5.15.7-200.fc35.x86_64                                        | 4        | 0.7%    |
| 5.14.0-60.fc35.x86_64                                         | 3        | 0.52%   |
| 5.17.9-200.fc35.x86_64                                        | 2        | 0.35%   |
| 5.17.7-200.fc35.x86_64                                        | 2        | 0.35%   |
| 5.17.6-200.fc35.x86_64                                        | 2        | 0.35%   |
| 5.17.11-200.fc35.x86_64                                       | 2        | 0.35%   |
| 5.16.18-201.fsync.fc35.x86_64                                 | 2        | 0.35%   |
| 5.14.20-300.fc35.x86_64                                       | 2        | 0.35%   |
| 5.12.0-0.rc7.189.fc35.x86_64                                  | 2        | 0.35%   |
| 5.8.18-100.fc31.x86_64                                        | 1        | 0.17%   |
| 5.8.15-301.fc33.x86_64                                        | 1        | 0.17%   |
| 5.17.4-302.fsync.fc35.x86_64                                  | 1        | 0.17%   |
| 5.16.4-200.fc35.x86_64                                        | 1        | 0.17%   |
| 5.16.2-225.vanilla.1.fc35.x86_64                              | 1        | 0.17%   |
| 5.16.2-200.fc35.x86_64                                        | 1        | 0.17%   |
| 5.16.17-200.fc35.x86_64                                       | 1        | 0.17%   |
| 5.16.11-xm1.0.fc35.x86_64                                     | 1        | 0.17%   |
| 5.16.0-0.rc6.41.vanilla.1.fc35.x86_64                         | 1        | 0.17%   |
| 5.16.0-0.rc2.18.vanilla.1.fc35.x86_64                         | 1        | 0.17%   |
| 5.16.0-0.rc1.20211115git8ab774587903.14.vanilla.1.fc35.x86_64 | 1        | 0.17%   |
| 5.15.5-xm1tt.0.fc35.x86_64                                    | 1        | 0.17%   |
| 5.15.4-xm1.0.fc35.x86_64                                      | 1        | 0.17%   |
| 5.15.2_tkg_bmq                                                | 1        | 0.17%   |
| 5.15.0-500.chinfo.fc35.x86_64                                 | 1        | 0.17%   |
| 5.15.0-0.rc7.20211028git1fc596a56b33.56.vanilla.1.fc35.x86_64 | 1        | 0.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.16.18 | 58       | 10.18%  |
| 5.14.10 | 35       | 6.14%   |
| 5.15.6  | 29       | 5.09%   |
| 5.16.16 | 25       | 4.39%   |
| 5.17.4  | 22       | 3.86%   |
| 5.16.9  | 22       | 3.86%   |
| 5.15.12 | 21       | 3.68%   |
| 5.14.18 | 21       | 3.68%   |
| 5.16.12 | 20       | 3.51%   |
| 5.16.20 | 19       | 3.33%   |
| 5.15.16 | 17       | 2.98%   |
| 5.14.17 | 17       | 2.98%   |
| 5.14.16 | 17       | 2.98%   |
| 5.16.19 | 14       | 2.46%   |
| 5.16.11 | 14       | 2.46%   |
| 5.15.18 | 14       | 2.46%   |
| 5.15.14 | 14       | 2.46%   |
| 5.17.5  | 13       | 2.28%   |
| 5.14.14 | 13       | 2.28%   |
| 5.16.5  | 12       | 2.11%   |
| 5.16.15 | 11       | 1.93%   |
| 5.15.8  | 11       | 1.93%   |
| 5.14.15 | 11       | 1.93%   |
| 5.15.13 | 10       | 1.75%   |
| 5.15.11 | 9        | 1.58%   |
| 5.16.8  | 7        | 1.23%   |
| 5.15.5  | 7        | 1.23%   |
| 5.15.15 | 7        | 1.23%   |
| 5.15.10 | 7        | 1.23%   |
| 5.16.7  | 6        | 1.05%   |
| 5.15.4  | 6        | 1.05%   |
| 5.15.17 | 6        | 1.05%   |
| 5.14.9  | 5        | 0.88%   |
| 5.16.14 | 4        | 0.7%    |
| 5.16.13 | 4        | 0.7%    |
| 5.15.7  | 4        | 0.7%    |
| 5.14.0  | 4        | 0.7%    |
| 5.13.0  | 3        | 0.53%   |
| 5.17.9  | 2        | 0.35%   |
| 5.17.7  | 2        | 0.35%   |
| 5.17.6  | 2        | 0.35%   |
| 5.17.11 | 2        | 0.35%   |
| 5.16.2  | 2        | 0.35%   |
| 5.16.0  | 2        | 0.35%   |
| 5.15.0  | 2        | 0.35%   |
| 5.14.20 | 2        | 0.35%   |
| 5.12.0  | 2        | 0.35%   |
| 5.8.18  | 1        | 0.18%   |
| 5.8.15  | 1        | 0.18%   |
| 5.16.4  | 1        | 0.18%   |
| 5.16.17 | 1        | 0.18%   |
| 5.15.2  | 1        | 0.18%   |
| 5.14.8  | 1        | 0.18%   |
| 5.14.7  | 1        | 0.18%   |
| 5.14.6  | 1        | 0.18%   |
| 5.14.13 | 1        | 0.18%   |
| 5.14.1  | 1        | 0.18%   |
| 5.13.7  | 1        | 0.18%   |
| 5.11.13 | 1        | 0.18%   |
| 5.10.15 | 1        | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.16    | 205      | 38.03%  |
| 5.15    | 153      | 28.39%  |
| 5.14    | 129      | 23.93%  |
| 5.17    | 42       | 7.79%   |
| 5.13    | 4        | 0.74%   |
| 5.8     | 2        | 0.37%   |
| 5.12    | 2        | 0.37%   |
| 5.11    | 1        | 0.19%   |
| 5.10    | 1        | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 499      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 371      | 73.61%  |
| KDE5          | 58       | 11.51%  |
| Unknown       | 27       | 5.36%   |
| X-Cinnamon    | 13       | 2.58%   |
| XFCE          | 12       | 2.38%   |
| Cinnamon      | 8        | 1.59%   |
| MATE          | 6        | 1.19%   |
| KDE           | 4        | 0.79%   |
| GNOME Classic | 3        | 0.6%    |
| openbox       | 1        | 0.2%    |
| LXDE          | 1        | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 263      | 50.97%  |
| X11     | 221      | 42.83%  |
| Tty     | 18       | 3.49%   |
| Unknown | 13       | 2.52%   |
| Web     | 1        | 0.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 278      | 55.38%  |
| GDM     | 149      | 29.68%  |
| LightDM | 40       | 7.97%   |
| SDDM    | 35       | 6.97%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 239      | 47.61%  |
| en_GB      | 35       | 6.97%   |
| ru_RU      | 30       | 5.98%   |
| pt_BR      | 24       | 4.78%   |
| de_DE      | 21       | 4.18%   |
| fr_FR      | 20       | 3.98%   |
| en_AU      | 17       | 3.39%   |
| en_CA      | 12       | 2.39%   |
| es_ES      | 11       | 2.19%   |
| pl_PL      | 10       | 1.99%   |
| it_IT      | 9        | 1.79%   |
| nl_BE      | 6        | 1.2%    |
| es_MX      | 6        | 1.2%    |
| cs_CZ      | 6        | 1.2%    |
| es_CO      | 5        | 1%      |
| en_IE      | 5        | 1%      |
| fr_CH      | 3        | 0.6%    |
| C          | 3        | 0.6%    |
| tr_TR      | 2        | 0.4%    |
| sv_SE      | 2        | 0.4%    |
| ru_UA      | 2        | 0.4%    |
| nl_NL      | 2        | 0.4%    |
| hu_HU      | 2        | 0.4%    |
| fr_BE      | 2        | 0.4%    |
| fi_FI      | 2        | 0.4%    |
| es_CL      | 2        | 0.4%    |
| en_NZ      | 2        | 0.4%    |
| de_AT      | 2        | 0.4%    |
| ar_SA      | 2        | 0.4%    |
| Unknown    | 2        | 0.4%    |
| zh_CN      | 1        | 0.2%    |
| sr_RS      | 1        | 0.2%    |
| ro_RO      | 1        | 0.2%    |
| pt_PT      | 1        | 0.2%    |
| pa_IN      | 1        | 0.2%    |
| nb_NO      | 1        | 0.2%    |
| ja_JP      | 1        | 0.2%    |
| es_VE      | 1        | 0.2%    |
| en_US.UTF8 | 1        | 0.2%    |
| en_PH      | 1        | 0.2%    |
| en_IN      | 1        | 0.2%    |
| en_IL      | 1        | 0.2%    |
| el_GR      | 1        | 0.2%    |
| de_CH      | 1        | 0.2%    |
| ca_ES      | 1        | 0.2%    |
| bs_BA      | 1        | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 343      | 68.06%  |
| BIOS | 161      | 31.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 346      | 68.79%  |
| Ext4    | 129      | 25.65%  |
| Xfs     | 24       | 4.77%   |
| Overlay | 3        | 0.6%    |
| Ext3    | 1        | 0.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 275      | 54.46%  |
| GPT     | 189      | 37.43%  |
| MBR     | 41       | 8.12%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 421      | 83.86%  |
| Yes       | 81       | 16.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 396      | 78.11%  |
| Yes       | 111      | 21.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 145      | 29.06%  |
| Gigabyte Technology | 107      | 21.44%  |
| MSI                 | 89       | 17.84%  |
| ASRock              | 36       | 7.21%   |
| Dell                | 33       | 6.61%   |
| Hewlett-Packard     | 23       | 4.61%   |
| Lenovo              | 19       | 3.81%   |
| Fujitsu             | 5        | 1%      |
| ECS                 | 5        | 1%      |
| Intel               | 3        | 0.6%    |
| BESSTAR Tech        | 3        | 0.6%    |
| XFX                 | 2        | 0.4%    |
| System76            | 2        | 0.4%    |
| Supermicro          | 2        | 0.4%    |
| JINGSHA             | 2        | 0.4%    |
| Gateway             | 2        | 0.4%    |
| Foxconn             | 2        | 0.4%    |
| Biostar             | 2        | 0.4%    |
| Apple               | 2        | 0.4%    |
| ABIT                | 2        | 0.4%    |
| Unknown             | 2        | 0.4%    |
| Shuttle             | 1        | 0.2%    |
| Seco                | 1        | 0.2%    |
| Ruckus Wireless     | 1        | 0.2%    |
| Pegatron            | 1        | 0.2%    |
| PCWare              | 1        | 0.2%    |
| MACHINIST           | 1        | 0.2%    |
| Huanan              | 1        | 0.2%    |
| AMI                 | 1        | 0.2%    |
| Alienware           | 1        | 0.2%    |
| Acer                | 1        | 0.2%    |
| AAEON               | 1        | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 11       | 2.2%    |
| MSI MS-7C37                    | 7        | 1.4%    |
| MSI MS-7C56                    | 5        | 1%      |
| ASUS ROG STRIX B550-I GAMING   | 5        | 1%      |
| ASUS ROG STRIX B450-F GAMING   | 5        | 1%      |
| MSI MS-7B93                    | 4        | 0.8%    |
| Gigabyte X570 I AORUS PRO WIFI | 4        | 0.8%    |
| Gigabyte B450M DS3H            | 4        | 0.8%    |
| Gigabyte B450 AORUS M          | 4        | 0.8%    |
| ASUS ROG STRIX B550-F GAMING   | 4        | 0.8%    |
| ASUS ROG CROSSHAIR VII HERO    | 4        | 0.8%    |
| Unknown                        | 4        | 0.8%    |
| MSI MS-7D25                    | 3        | 0.6%    |
| MSI MS-7C91                    | 3        | 0.6%    |
| MSI MS-7C84                    | 3        | 0.6%    |
| MSI MS-7B89                    | 3        | 0.6%    |
| MSI MS-7B86                    | 3        | 0.6%    |
| MSI MS-7B79                    | 3        | 0.6%    |
| MSI MS-7A38                    | 3        | 0.6%    |
| Gigabyte X570 AORUS MASTER     | 3        | 0.6%    |
| Gigabyte B550 AORUS PRO AC     | 3        | 0.6%    |
| Dell Precision T3600           | 3        | 0.6%    |
| Dell OptiPlex 7010             | 3        | 0.6%    |
| Dell OptiPlex 3020             | 3        | 0.6%    |
| ASUS ROG STRIX X570-F GAMING   | 3        | 0.6%    |
| ASRock B450 Pro4               | 3        | 0.6%    |
| System76 Thelio Mira           | 2        | 0.4%    |
| MSI MS-7C95                    | 2        | 0.4%    |
| MSI MS-7C94                    | 2        | 0.4%    |
| MSI MS-7C52                    | 2        | 0.4%    |
| MSI MS-7C35                    | 2        | 0.4%    |
| MSI MS-7B98                    | 2        | 0.4%    |
| MSI MS-7B85                    | 2        | 0.4%    |
| MSI MS-7B10                    | 2        | 0.4%    |
| MSI MS-7A69                    | 2        | 0.4%    |
| MSI MS-7A34                    | 2        | 0.4%    |
| MSI MS-7A33                    | 2        | 0.4%    |
| MSI MS-7817                    | 2        | 0.4%    |
| HP Z440 Workstation            | 2        | 0.4%    |
| HP ProDesk 600 G2 SFF          | 2        | 0.4%    |
| HP EliteDesk 800 G2 TWR        | 2        | 0.4%    |
| HP Compaq 8200 Elite CMT PC    | 2        | 0.4%    |
| Gigabyte Z690 UD DDR4          | 2        | 0.4%    |
| Gigabyte Z390 I AORUS PRO WIFI | 2        | 0.4%    |
| Gigabyte Z390 AORUS MASTER     | 2        | 0.4%    |
| Gigabyte X570 AORUS ELITE      | 2        | 0.4%    |
| Gigabyte TRX40 AORUS MASTER    | 2        | 0.4%    |
| Gigabyte H97M-D3H              | 2        | 0.4%    |
| Gigabyte GB-BRR7H-4800         | 2        | 0.4%    |
| Gigabyte GA-78LMT-USB3         | 2        | 0.4%    |
| Gigabyte B450 AORUS ELITE      | 2        | 0.4%    |
| Gigabyte AB350-Gaming 3        | 2        | 0.4%    |
| Gigabyte A320M-S2H             | 2        | 0.4%    |
| ASUS Z170 PRO GAMING           | 2        | 0.4%    |
| ASUS TUF Gaming X570-PLUS      | 2        | 0.4%    |
| ASUS TUF Gaming B550M-PLUS     | 2        | 0.4%    |
| ASUS TUF Gaming B550-PLUS      | 2        | 0.4%    |
| ASUS ROG STRIX X570-I GAMING   | 2        | 0.4%    |
| ASUS ROG Maximus XI HERO       | 2        | 0.4%    |
| ASUS ROG Maximus XI FORMULA    | 2        | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 48       | 9.62%   |
| ASUS PRIME             | 29       | 5.81%   |
| Dell OptiPlex          | 18       | 3.61%   |
| Lenovo ThinkCentre     | 15       | 3.01%   |
| ASUS TUF               | 14       | 2.81%   |
| Gigabyte X570          | 12       | 2.4%    |
| ASUS All               | 11       | 2.2%    |
| Dell Precision         | 8        | 1.6%    |
| MSI MS-7C37            | 7        | 1.4%    |
| Gigabyte B550          | 6        | 1.2%    |
| Gigabyte B450          | 6        | 1.2%    |
| MSI MS-7C56            | 5        | 1%      |
| HP EliteDesk           | 5        | 1%      |
| Gigabyte Z390          | 5        | 1%      |
| MSI MS-7B93            | 4        | 0.8%    |
| HP Compaq              | 4        | 0.8%    |
| Gigabyte B450M         | 4        | 0.8%    |
| ASUS Maximus           | 4        | 0.8%    |
| ASRock X570            | 4        | 0.8%    |
| ASRock B450            | 4        | 0.8%    |
| Unknown                | 4        | 0.8%    |
| MSI MS-7D25            | 3        | 0.6%    |
| MSI MS-7C91            | 3        | 0.6%    |
| MSI MS-7C84            | 3        | 0.6%    |
| MSI MS-7B89            | 3        | 0.6%    |
| MSI MS-7B86            | 3        | 0.6%    |
| MSI MS-7B79            | 3        | 0.6%    |
| MSI MS-7A38            | 3        | 0.6%    |
| HP ProDesk             | 3        | 0.6%    |
| Gigabyte TRX40         | 3        | 0.6%    |
| Fujitsu ESPRIMO        | 3        | 0.6%    |
| Dell XPS               | 3        | 0.6%    |
| ASUS M5A97             | 3        | 0.6%    |
| System76 Thelio        | 2        | 0.4%    |
| MSI MS-7C95            | 2        | 0.4%    |
| MSI MS-7C94            | 2        | 0.4%    |
| MSI MS-7C52            | 2        | 0.4%    |
| MSI MS-7C35            | 2        | 0.4%    |
| MSI MS-7B98            | 2        | 0.4%    |
| MSI MS-7B85            | 2        | 0.4%    |
| MSI MS-7B10            | 2        | 0.4%    |
| MSI MS-7A69            | 2        | 0.4%    |
| MSI MS-7A34            | 2        | 0.4%    |
| MSI MS-7A33            | 2        | 0.4%    |
| MSI MS-7817            | 2        | 0.4%    |
| HP Z440                | 2        | 0.4%    |
| HP Slim                | 2        | 0.4%    |
| Gigabyte Z690          | 2        | 0.4%    |
| Gigabyte H97M-D3H      | 2        | 0.4%    |
| Gigabyte GB-BRR7H-4800 | 2        | 0.4%    |
| Gigabyte GA-78LMT-USB3 | 2        | 0.4%    |
| Gigabyte G1.Sniper     | 2        | 0.4%    |
| Gigabyte AB350-Gaming  | 2        | 0.4%    |
| Gigabyte A320M-S2H     | 2        | 0.4%    |
| Dell Inspiron          | 2        | 0.4%    |
| Dell G5                | 2        | 0.4%    |
| ASUS Z170              | 2        | 0.4%    |
| ASUS STRIX             | 2        | 0.4%    |
| ASUS P8Z77-V           | 2        | 0.4%    |
| ASUS M5A78L-M          | 2        | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 71       | 14.23%  |
| 2019 | 67       | 13.43%  |
| 2018 | 65       | 13.03%  |
| 2021 | 47       | 9.42%   |
| 2014 | 43       | 8.62%   |
| 2017 | 38       | 7.62%   |
| 2013 | 35       | 7.01%   |
| 2011 | 24       | 4.81%   |
| 2012 | 23       | 4.61%   |
| 2016 | 21       | 4.21%   |
| 2015 | 20       | 4.01%   |
| 2010 | 19       | 3.81%   |
| 2008 | 11       | 2.2%    |
| 2009 | 9        | 1.8%    |
| 2006 | 3        | 0.6%    |
| 2007 | 2        | 0.4%    |
| 2022 | 1        | 0.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 499      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 469      | 93.61%  |
| Enabled  | 32       | 6.39%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 499      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 149      | 29.68%  |
| 32.01-64.0  | 124      | 24.7%   |
| 8.01-16.0   | 71       | 14.14%  |
| 64.01-256.0 | 53       | 10.56%  |
| 4.01-8.0    | 51       | 10.16%  |
| 3.01-4.0    | 33       | 6.57%   |
| 24.01-32.0  | 16       | 3.19%   |
| 2.01-3.0    | 4        | 0.8%    |
| 1.01-2.0    | 1        | 0.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 163      | 29.53%  |
| 2.01-3.0    | 139      | 25.18%  |
| 3.01-4.0    | 97       | 17.57%  |
| 1.01-2.0    | 67       | 12.14%  |
| 8.01-16.0   | 54       | 9.78%   |
| 0.51-1.0    | 12       | 2.17%   |
| 16.01-24.0  | 9        | 1.63%   |
| 24.01-32.0  | 7        | 1.27%   |
| 32.01-64.0  | 2        | 0.36%   |
| 64.01-256.0 | 1        | 0.18%   |
| 0.01-0.5    | 1        | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 160      | 31.37%  |
| 1      | 130      | 25.49%  |
| 3      | 102      | 20%     |
| 4      | 53       | 10.39%  |
| 5      | 31       | 6.08%   |
| 6      | 16       | 3.14%   |
| 7      | 12       | 2.35%   |
| 8      | 3        | 0.59%   |
| 9      | 2        | 0.39%   |
| 14     | 1        | 0.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 349      | 69.52%  |
| Yes       | 153      | 30.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 498      | 99.6%   |
| No        | 2        | 0.4%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 256      | 51.3%   |
| Yes       | 243      | 48.7%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 270      | 53.68%  |
| Yes       | 233      | 46.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 111      | 22.2%   |
| Germany      | 36       | 7.2%    |
| Russia       | 32       | 6.4%    |
| Brazil       | 28       | 5.6%    |
| France       | 26       | 5.2%    |
| Canada       | 21       | 4.2%    |
| Australia    | 20       | 4%      |
| UK           | 18       | 3.6%    |
| Spain        | 18       | 3.6%    |
| Poland       | 16       | 3.2%    |
| Italy        | 13       | 2.6%    |
| Belgium      | 12       | 2.4%    |
| Czechia      | 10       | 2%      |
| Mexico       | 9        | 1.8%    |
| Switzerland  | 8        | 1.6%    |
| Netherlands  | 8        | 1.6%    |
| Austria      | 8        | 1.6%    |
| Ukraine      | 7        | 1.4%    |
| Norway       | 7        | 1.4%    |
| Sweden       | 6        | 1.2%    |
| India        | 6        | 1.2%    |
| Turkey       | 5        | 1%      |
| Romania      | 5        | 1%      |
| Colombia     | 5        | 1%      |
| Indonesia    | 4        | 0.8%    |
| Hungary      | 4        | 0.8%    |
| Hong Kong    | 4        | 0.8%    |
| Greece       | 4        | 0.8%    |
| Belarus      | 4        | 0.8%    |
| Ireland      | 3        | 0.6%    |
| Chile        | 3        | 0.6%    |
| Slovenia     | 2        | 0.4%    |
| Saudi Arabia | 2        | 0.4%    |
| New Zealand  | 2        | 0.4%    |
| Latvia       | 2        | 0.4%    |
| Kyrgyzstan   | 2        | 0.4%    |
| Israel       | 2        | 0.4%    |
| Finland      | 2        | 0.4%    |
| Egypt        | 2        | 0.4%    |
| Argentina    | 2        | 0.4%    |
| Yemen        | 1        | 0.2%    |
| Venezuela    | 1        | 0.2%    |
| Uzbekistan   | 1        | 0.2%    |
| Thailand     | 1        | 0.2%    |
| Taiwan       | 1        | 0.2%    |
| Slovakia     | 1        | 0.2%    |
| Philippines  | 1        | 0.2%    |
| Myanmar      | 1        | 0.2%    |
| Moldova      | 1        | 0.2%    |
| Kuwait       | 1        | 0.2%    |
| Kazakhstan   | 1        | 0.2%    |
| Japan        | 1        | 0.2%    |
| Guam         | 1        | 0.2%    |
| Estonia      | 1        | 0.2%    |
| Ecuador      | 1        | 0.2%    |
| Denmark      | 1        | 0.2%    |
| Cyprus       | 1        | 0.2%    |
| Cambodia     | 1        | 0.2%    |
| Bulgaria     | 1        | 0.2%    |
| Bolivia      | 1        | 0.2%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Sydney            | 10       | 1.93%   |
| Moscow            | 8        | 1.55%   |
| Berlin            | 8        | 1.55%   |
| Vienna            | 5        | 0.97%   |
| Madrid            | 5        | 0.97%   |
| Melbourne         | 4        | 0.77%   |
| Launceston        | 4        | 0.77%   |
| Athens            | 4        | 0.77%   |
| Yekaterinburg     | 3        | 0.58%   |
| Warsaw            | 3        | 0.58%   |
| Seattle           | 3        | 0.58%   |
| Minsk             | 3        | 0.58%   |
| Los Angeles       | 3        | 0.58%   |
| Krakow            | 3        | 0.58%   |
| Amsterdam         | 3        | 0.58%   |
| Zurich            | 2        | 0.39%   |
| Yverdon-les-Bains | 2        | 0.39%   |
| Weinsberg         | 2        | 0.39%   |
| Vancouver         | 2        | 0.39%   |
| Ufa               | 2        | 0.39%   |
| Toronto           | 2        | 0.39%   |
| The Hague         | 2        | 0.39%   |
| St Petersburg     | 2        | 0.39%   |
| Springfield       | 2        | 0.39%   |
| Sautron           | 2        | 0.39%   |
| Sao Paulo         | 2        | 0.39%   |
| Santiago          | 2        | 0.39%   |
| Rome              | 2        | 0.39%   |
| Rio de Janeiro    | 2        | 0.39%   |
| Riga              | 2        | 0.39%   |
| Raleigh           | 2        | 0.39%   |
| Pompano Beach     | 2        | 0.39%   |
| Pittsburgh        | 2        | 0.39%   |
| Pennsville        | 2        | 0.39%   |
| Paris             | 2        | 0.39%   |
| New Haven         | 2        | 0.39%   |
| Minneapolis       | 2        | 0.39%   |
| Milan             | 2        | 0.39%   |
| Mexico City       | 2        | 0.39%   |
| Medellín         | 2        | 0.39%   |
| Louisville        | 2        | 0.39%   |
| London            | 2        | 0.39%   |
| Kyiv              | 2        | 0.39%   |
| Kristiansand      | 2        | 0.39%   |
| Jakarta           | 2        | 0.39%   |
| Istanbul          | 2        | 0.39%   |
| Houston           | 2        | 0.39%   |
| Guadalajara       | 2        | 0.39%   |
| Goiânia          | 2        | 0.39%   |
| Ghent             | 2        | 0.39%   |
| Edinburgh         | 2        | 0.39%   |
| Dublin            | 2        | 0.39%   |
| Dallas            | 2        | 0.39%   |
| Częstochowa      | 2        | 0.39%   |
| Calgary           | 2        | 0.39%   |
| Cairo             | 2        | 0.39%   |
| Buenos Aires      | 2        | 0.39%   |
| Brussels          | 2        | 0.39%   |
| Brisbane          | 2        | 0.39%   |
| Brasília         | 2        | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| Samsung Electronics            | 201      | 354    | 19.82%  |
| WDC                            | 181      | 318    | 17.85%  |
| Seagate                        | 164      | 287    | 16.17%  |
| Kingston                       | 67       | 87     | 6.61%   |
| Crucial                        | 61       | 75     | 6.02%   |
| SanDisk                        | 51       | 61     | 5.03%   |
| Toshiba                        | 45       | 60     | 4.44%   |
| Phison                         | 23       | 33     | 2.27%   |
| Intel                          | 23       | 31     | 2.27%   |
| A-DATA Technology              | 23       | 29     | 2.27%   |
| Hitachi                        | 20       | 26     | 1.97%   |
| SPCC                           | 12       | 15     | 1.18%   |
| Unknown                        | 8        | 11     | 0.79%   |
| Silicon Motion                 | 8        | 10     | 0.79%   |
| Patriot                        | 8        | 11     | 0.79%   |
| Corsair                        | 8        | 9      | 0.79%   |
| XPG                            | 7        | 11     | 0.69%   |
| PNY                            | 6        | 7      | 0.59%   |
| SK Hynix                       | 5        | 6      | 0.49%   |
| Micron/Crucial Technology      | 5        | 6      | 0.49%   |
| MAXTOR                         | 5        | 5      | 0.49%   |
| HGST                           | 5        | 10     | 0.49%   |
| SABRENT                        | 4        | 4      | 0.39%   |
| Realtek Semiconductor          | 4        | 5      | 0.39%   |
| OCZ                            | 4        | 4      | 0.39%   |
| Micron Technology              | 4        | 5      | 0.39%   |
| Hewlett-Packard                | 4        | 4      | 0.39%   |
| GOODRAM                        | 4        | 4      | 0.39%   |
| China                          | 4        | 5      | 0.39%   |
| SSK                            | 3        | 3      | 0.3%    |
| Lexar                          | 3        | 4      | 0.3%    |
| KingSpec                       | 3        | 3      | 0.3%    |
| Intenso                        | 3        | 6      | 0.3%    |
| Apacer                         | 3        | 4      | 0.3%    |
| Verbatim                       | 2        | 2      | 0.2%    |
| MAXIO Technology (Hangzhou)    | 2        | 2      | 0.2%    |
| Unknown                        | 2        | 2      | 0.2%    |
| Zheino                         | 1        | 1      | 0.1%    |
| USB 3.0                        | 1        | 2      | 0.1%    |
| Transcend                      | 1        | 1      | 0.1%    |
| Team                           | 1        | 4      | 0.1%    |
| T-FORCE                        | 1        | 1      | 0.1%    |
| SUNEAST                        | 1        | 1      | 0.1%    |
| Solid State Storage Technology | 1        | 1      | 0.1%    |
| sobetter                       | 1        | 1      | 0.1%    |
| PLEXTOR                        | 1        | 1      | 0.1%    |
| Pioneer                        | 1        | 1      | 0.1%    |
| Phison Electronics             | 1        | 1      | 0.1%    |
| OWC                            | 1        | 1      | 0.1%    |
| OCZ-VERTEX                     | 1        | 1      | 0.1%    |
| Mushkin                        | 1        | 1      | 0.1%    |
| MaxDigital                     | 1        | 1      | 0.1%    |
| LS600                          | 1        | 1      | 0.1%    |
| LITEONIT                       | 1        | 1      | 0.1%    |
| LITEON                         | 1        | 2      | 0.1%    |
| LDLC                           | 1        | 3      | 0.1%    |
| KUIJIA                         | 1        | 1      | 0.1%    |
| KIOXIA                         | 1        | 2      | 0.1%    |
| KingDian                       | 1        | 1      | 0.1%    |
| HS-SSD-C100                    | 1        | 1      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB     | 29       | 2.32%   |
| Seagate ST2000DM008-2FR102 2TB   | 18       | 1.44%   |
| Samsung SSD 860 EVO 500GB        | 18       | 1.44%   |
| Samsung NVMe SSD Drive 1TB       | 17       | 1.36%   |
| Samsung SSD 860 EVO 1TB          | 16       | 1.28%   |
| Seagate ST1000DM010-2EP102 1TB   | 14       | 1.12%   |
| Kingston SA400S37240G 240GB SSD  | 14       | 1.12%   |
| Samsung SSD 850 EVO 500GB        | 13       | 1.04%   |
| Samsung SSD 850 EVO 250GB        | 13       | 1.04%   |
| Crucial CT1000MX500SSD1 1TB      | 12       | 0.96%   |
| Seagate ST500DM002-1BD142 500GB  | 11       | 0.88%   |
| Seagate ST4000DM004-2CV104 4TB   | 11       | 0.88%   |
| Sandisk NVMe SSD Drive 1TB       | 11       | 0.88%   |
| Samsung SSD 970 EVO Plus 500GB   | 11       | 0.88%   |
| Kingston SA400S37480G 480GB SSD  | 10       | 0.8%    |
| Crucial CT500MX500SSD1 500GB     | 9        | 0.72%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 8        | 0.64%   |
| Seagate ST3500418AS 500GB        | 8        | 0.64%   |
| Seagate ST1000DM003-1CH162 1TB   | 8        | 0.64%   |
| Sandisk NVMe SSD Drive 500GB     | 8        | 0.64%   |
| Samsung NVMe SSD Drive 250GB     | 8        | 0.64%   |
| Kingston SV300S37A120G 120GB SSD | 8        | 0.64%   |
| Seagate ST1000DM003-1ER162 1TB   | 7        | 0.56%   |
| Samsung SSD 970 EVO Plus 1TB     | 7        | 0.56%   |
| Samsung SSD 870 EVO 1TB          | 7        | 0.56%   |
| Samsung SSD 860 EVO 250GB        | 7        | 0.56%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 6        | 0.48%   |
| Toshiba HDWD110 1TB              | 6        | 0.48%   |
| Seagate ST4000DM005-2DP166 4TB   | 6        | 0.48%   |
| Samsung NVMe SSD Drive 2TB       | 6        | 0.48%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 5        | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD | 5        | 0.4%    |
| WDC WD30EFRX-68EUZN0 3TB         | 5        | 0.4%    |
| WDC WD10EZEX-60WN4A0 1TB         | 5        | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB         | 5        | 0.4%    |
| WDC WD10EZEX-00WN4A0 1TB         | 5        | 0.4%    |
| Toshiba DT01ACA050 500GB         | 5        | 0.4%    |
| Seagate ST1000DM003-1SB102 1TB   | 5        | 0.4%    |
| Samsung SSD 980 1TB              | 5        | 0.4%    |
| Samsung SSD 970 EVO 250GB        | 5        | 0.4%    |
| Samsung SSD 870 EVO 500GB        | 5        | 0.4%    |
| Samsung SSD 860 QVO 1TB          | 5        | 0.4%    |
| Phison Sabrent 1TB               | 5        | 0.4%    |
| Kingston SUV400S37240G 240GB SSD | 5        | 0.4%    |
| Kingston SA400S37120G 120GB SSD  | 5        | 0.4%    |
| Crucial CT240BX500SSD1 240GB     | 5        | 0.4%    |
| WDC WDS100T1X0E-00AFY0 1TB       | 4        | 0.32%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 4        | 0.32%   |
| WDC WD40EFRX-68N32N0 4TB         | 4        | 0.32%   |
| WDC WD20EARS-00MVWB0 2TB         | 4        | 0.32%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 4        | 0.32%   |
| Toshiba MQ01ABD100 1TB           | 4        | 0.32%   |
| Toshiba HDWD120 2TB              | 4        | 0.32%   |
| Seagate ST8000DM004-2CX188 8TB   | 4        | 0.32%   |
| Seagate ST2000DM001-1CH164 2TB   | 4        | 0.32%   |
| Samsung SSD 980 PRO 1TB          | 4        | 0.32%   |
| Samsung SSD 970 EVO Plus 2TB     | 4        | 0.32%   |
| Samsung SSD 870 QVO 1TB          | 4        | 0.32%   |
| Phison NVMe SSD Drive 2TB        | 4        | 0.32%   |
| Phison NVMe SSD Drive 1024GB     | 4        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 159      | 276    | 41.09%  |
| WDC                 | 143      | 256    | 36.95%  |
| Toshiba             | 36       | 46     | 9.3%    |
| Hitachi             | 20       | 26     | 5.17%   |
| Samsung Electronics | 11       | 15     | 2.84%   |
| MAXTOR              | 5        | 5      | 1.29%   |
| HGST                | 5        | 10     | 1.29%   |
| SABRENT             | 3        | 3      | 0.78%   |
| USB 3.0             | 1        | 2      | 0.26%   |
| MaxDigital          | 1        | 1      | 0.26%   |
| Hewlett-Packard     | 1        | 1      | 0.26%   |
| Fujitsu             | 1        | 1      | 0.26%   |
| ASMT                | 1        | 1      | 0.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 113      | 185    | 28.32%  |
| Kingston            | 55       | 68     | 13.78%  |
| Crucial             | 52       | 64     | 13.03%  |
| WDC                 | 35       | 43     | 8.77%   |
| SanDisk             | 29       | 31     | 7.27%   |
| A-DATA Technology   | 18       | 23     | 4.51%   |
| Intel               | 10       | 13     | 2.51%   |
| SPCC                | 9        | 11     | 2.26%   |
| Toshiba             | 7        | 9      | 1.75%   |
| Patriot             | 7        | 9      | 1.75%   |
| PNY                 | 6        | 7      | 1.5%    |
| OCZ                 | 4        | 4      | 1%      |
| GOODRAM             | 4        | 4      | 1%      |
| China               | 4        | 5      | 1%      |
| Micron Technology   | 3        | 3      | 0.75%   |
| KingSpec            | 3        | 3      | 0.75%   |
| Intenso             | 3        | 6      | 0.75%   |
| Corsair             | 3        | 4      | 0.75%   |
| Apacer              | 3        | 4      | 0.75%   |
| Verbatim            | 2        | 2      | 0.5%    |
| Lexar               | 2        | 2      | 0.5%    |
| Hewlett-Packard     | 2        | 2      | 0.5%    |
| XPG                 | 1        | 2      | 0.25%   |
| Unknown             | 1        | 1      | 0.25%   |
| Transcend           | 1        | 1      | 0.25%   |
| Team                | 1        | 4      | 0.25%   |
| T-FORCE             | 1        | 1      | 0.25%   |
| SUNEAST             | 1        | 1      | 0.25%   |
| SK Hynix            | 1        | 2      | 0.25%   |
| Seagate             | 1        | 2      | 0.25%   |
| SABRENT             | 1        | 1      | 0.25%   |
| PLEXTOR             | 1        | 1      | 0.25%   |
| Pioneer             | 1        | 1      | 0.25%   |
| OWC                 | 1        | 1      | 0.25%   |
| OCZ-VERTEX          | 1        | 1      | 0.25%   |
| Mushkin             | 1        | 1      | 0.25%   |
| LS600               | 1        | 1      | 0.25%   |
| LITEONIT            | 1        | 1      | 0.25%   |
| LITEON              | 1        | 2      | 0.25%   |
| KUIJIA              | 1        | 1      | 0.25%   |
| KingDian            | 1        | 1      | 0.25%   |
| HS-SSD-C100         | 1        | 1      | 0.25%   |
| Gigabyte Technology | 1        | 2      | 0.25%   |
| Dahua               | 1        | 1      | 0.25%   |
| BIWIN               | 1        | 1      | 0.25%   |
| AMD                 | 1        | 2      | 0.25%   |
| Unknown             | 1        | 1      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 320      | 536    | 36.66%  |
| HDD     | 316      | 643    | 36.2%   |
| NVMe    | 215      | 350    | 24.63%  |
| Unknown | 17       | 23     | 1.95%   |
| MMC     | 5        | 6      | 0.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 431      | 1164   | 63.29%  |
| NVMe | 215      | 350    | 31.57%  |
| SAS  | 30       | 38     | 4.41%   |
| MMC  | 5        | 6      | 0.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 318      | 546    | 44.66%  |
| 0.51-1.0   | 211      | 328    | 29.63%  |
| 1.01-2.0   | 80       | 120    | 11.24%  |
| 3.01-4.0   | 48       | 75     | 6.74%   |
| 2.01-3.0   | 26       | 54     | 3.65%   |
| 4.01-10.0  | 22       | 43     | 3.09%   |
| 10.01-20.0 | 7        | 13     | 0.98%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 108      | 21.05%  |
| 501-1000       | 99       | 19.3%   |
| More than 3000 | 80       | 15.59%  |
| 251-500        | 78       | 15.2%   |
| 101-250        | 52       | 10.14%  |
| 2001-3000      | 38       | 7.41%   |
| 1-20           | 29       | 5.65%   |
| Unknown        | 15       | 2.92%   |
| 51-100         | 11       | 2.14%   |
| 21-50          | 3        | 0.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 97       | 18.1%   |
| 251-500        | 77       | 14.37%  |
| 501-1000       | 67       | 12.5%   |
| 101-250        | 65       | 12.13%  |
| 21-50          | 64       | 11.94%  |
| 51-100         | 56       | 10.45%  |
| 1001-2000      | 49       | 9.14%   |
| More than 3000 | 27       | 5.04%   |
| 2001-3000      | 19       | 3.54%   |
| Unknown        | 15       | 2.8%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Desktops | Drives | Percent |
|-----------------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 5        | 12     | 7.14%   |
| Seagate ST3500418AS 500GB                           | 3        | 4      | 4.29%   |
| Seagate ST2000DM001-1CH164 2TB                      | 2        | 2      | 2.86%   |
| Samsung Electronics SSD 870 EVO 500GB               | 2        | 2      | 2.86%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1        | 1      | 1.43%   |
| WDC WD5000AAKS-00UU3A0 500GB                        | 1        | 1      | 1.43%   |
| WDC WD3200BEVT-24A23T0 320GB                        | 1        | 1      | 1.43%   |
| WDC WD30EZRX-00MMMB0 3TB                            | 1        | 1      | 1.43%   |
| WDC WD30EFRX-68AX9N0 3TB                            | 1        | 1      | 1.43%   |
| WDC WD2500AAKX-753CA1 250GB                         | 1        | 1      | 1.43%   |
| WDC WD1600AAJS-00Z4A0 160GB                         | 1        | 1      | 1.43%   |
| WDC WD15EARS-00S0XB0 1TB                            | 1        | 1      | 1.43%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 1        | 1      | 1.43%   |
| WDC WD10EFRX-68JCSN0 1TB                            | 1        | 1      | 1.43%   |
| WDC WD10EALX-009BA0 1TB                             | 1        | 1      | 1.43%   |
| WDC WD10EADS-65P6B0 1TB                             | 1        | 1      | 1.43%   |
| WDC WD1003FBYX-01Y7B1 1TB                           | 1        | 1      | 1.43%   |
| WDC WD1002FAEX-00Z3A0 1TB                           | 1        | 1      | 1.43%   |
| Toshiba MQ01ABD050 500GB                            | 1        | 1      | 1.43%   |
| Toshiba MK6476GSX 640GB                             | 1        | 1      | 1.43%   |
| Team T2535T480G 480GB SSD                           | 1        | 4      | 1.43%   |
| Seagate ST9750420AS 752GB                           | 1        | 1      | 1.43%   |
| Seagate ST9500325AS 500GB                           | 1        | 1      | 1.43%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1        | 1      | 1.43%   |
| Seagate ST500LM000-1EJ162-SSHD 500GB                | 1        | 1      | 1.43%   |
| Seagate ST500DM009-2F110A 500GB                     | 1        | 1      | 1.43%   |
| Seagate ST3500630AS 500GB                           | 1        | 1      | 1.43%   |
| Seagate ST3200822A 200GB                            | 1        | 1      | 1.43%   |
| Seagate ST31500341AS 1TB                            | 1        | 1      | 1.43%   |
| Seagate ST31000528AS 1TB                            | 1        | 1      | 1.43%   |
| Seagate ST31000524AS 1TB                            | 1        | 1      | 1.43%   |
| Seagate ST3000DM001-1ER166 3TB                      | 1        | 1      | 1.43%   |
| Seagate ST3000DM001-1CH166 3TB                      | 1        | 5      | 1.43%   |
| Seagate ST2000DM008-2FR102 2TB                      | 1        | 1      | 1.43%   |
| Seagate ST2000DL003-9VT166 2TB                      | 1        | 1      | 1.43%   |
| Seagate ST1500DM003-9YN16G 1TB                      | 1        | 1      | 1.43%   |
| Seagate ST1000DX001-1CM162 1TB                      | 1        | 1      | 1.43%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1        | 1      | 1.43%   |
| Seagate ST1000DM003-1ER162 1TB                      | 1        | 1      | 1.43%   |
| SanDisk SSD PLUS 1000GB                             | 1        | 1      | 1.43%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD                 | 1        | 1      | 1.43%   |
| Samsung Electronics SSD 980 PRO 2TB                 | 1        | 1      | 1.43%   |
| Samsung Electronics SSD 970 EVO 250GB               | 1        | 1      | 1.43%   |
| Samsung Electronics SSD 970 EVO 1TB                 | 1        | 1      | 1.43%   |
| Samsung Electronics SSD 850 PRO 2TB                 | 1        | 1      | 1.43%   |
| Samsung Electronics HD501LJ 500GB                   | 1        | 4      | 1.43%   |
| Samsung Electronics HD103UJ 1TB                     | 1        | 1      | 1.43%   |
| PNY CS1311 960GB SSD                                | 1        | 1      | 1.43%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1        | 1      | 1.43%   |
| MAXTOR 6Y080M0 81GB                                 | 1        | 1      | 1.43%   |
| Kingston SV300S37A240G 240GB SSD                    | 1        | 1      | 1.43%   |
| Kingston SV300S37A120G 120GB SSD                    | 1        | 1      | 1.43%   |
| Intel SSDSC2CT120A3 120GB                           | 1        | 3      | 1.43%   |
| Intel SSDPEKKW256G7 256GB                           | 1        | 1      | 1.43%   |
| Hitachi HTS723232A7A364 320GB                       | 1        | 1      | 1.43%   |
| Hitachi HDS5C3020ALA632 2TB                         | 1        | 2      | 1.43%   |
| Crucial CT250BX100SSD1 250GB                        | 1        | 1      | 1.43%   |
| Crucial CT240M500SSD1 240GB                         | 1        | 1      | 1.43%   |
| Crucial CT128MX100SSD1 128GB                        | 1        | 1      | 1.43%   |
| Corsair Force LS SSD 480GB                          | 1        | 1      | 1.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 26       | 40     | 38.24%  |
| WDC                 | 14       | 14     | 20.59%  |
| Samsung Electronics | 8        | 11     | 11.76%  |
| Crucial             | 3        | 3      | 4.41%   |
| Toshiba             | 2        | 2      | 2.94%   |
| SanDisk             | 2        | 2      | 2.94%   |
| Kingston            | 2        | 2      | 2.94%   |
| Intel               | 2        | 4      | 2.94%   |
| Hitachi             | 2        | 3      | 2.94%   |
| A-DATA Technology   | 2        | 2      | 2.94%   |
| Team                | 1        | 4      | 1.47%   |
| PNY                 | 1        | 1      | 1.47%   |
| Micron Technology   | 1        | 1      | 1.47%   |
| MAXTOR              | 1        | 1      | 1.47%   |
| Corsair             | 1        | 1      | 1.47%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 26       | 40     | 56.52%  |
| WDC                 | 13       | 13     | 28.26%  |
| Toshiba             | 2        | 2      | 4.35%   |
| Samsung Electronics | 2        | 5      | 4.35%   |
| Hitachi             | 2        | 3      | 4.35%   |
| MAXTOR              | 1        | 1      | 2.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 43       | 64     | 66.15%  |
| SSD  | 17       | 22     | 26.15%  |
| NVMe | 5        | 5      | 7.69%   |

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
| Detected | 287      | 861    | 49.83%  |
| Works    | 225      | 606    | 39.06%  |
| Malfunc  | 64       | 91     | 11.11%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 269      | 33.09%  |
| AMD                            | 226      | 27.8%   |
| Samsung Electronics            | 106      | 13.04%  |
| Sandisk                        | 36       | 4.43%   |
| ASMedia Technology             | 32       | 3.94%   |
| Phison Electronics             | 29       | 3.57%   |
| Marvell Technology Group       | 17       | 2.09%   |
| Kingston Technology Company    | 17       | 2.09%   |
| Micron/Crucial Technology      | 14       | 1.72%   |
| JMicron Technology             | 11       | 1.35%   |
| ADATA Technology               | 10       | 1.23%   |
| Silicon Motion                 | 9        | 1.11%   |
| Nvidia                         | 7        | 0.86%   |
| Realtek Semiconductor          | 5        | 0.62%   |
| SK Hynix                       | 4        | 0.49%   |
| Toshiba America Info Systems   | 3        | 0.37%   |
| Silicon Image                  | 3        | 0.37%   |
| Micron Technology              | 2        | 0.25%   |
| MAXIO Technology (Hangzhou)    | 2        | 0.25%   |
| LSI Logic / Symbios Logic      | 2        | 0.25%   |
| KIOXIA                         | 2        | 0.25%   |
| Broadcom / LSI                 | 2        | 0.25%   |
| VIA Technologies               | 1        | 0.12%   |
| ULi Electronics                | 1        | 0.12%   |
| Solid State Storage Technology | 1        | 0.12%   |
| Seagate Technology             | 1        | 0.12%   |
| Adaptec                        | 1        | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 152      | 15.72%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 67       | 6.93%   |
| AMD 400 Series Chipset SATA Controller                                                  | 54       | 5.58%   |
| AMD 500 Series Chipset SATA Controller                                                  | 40       | 4.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 33       | 3.41%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 30       | 3.1%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 29       | 3%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 26       | 2.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 21       | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 21       | 2.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 18       | 1.86%   |
| Phison E12 NVMe Controller                                                              | 17       | 1.76%   |
| Intel SATA Controller [RAID mode]                                                       | 17       | 1.76%   |
| Samsung NVMe SSD Controller 980                                                         | 14       | 1.45%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 14       | 1.45%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 13       | 1.34%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 12       | 1.24%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 11       | 1.14%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 11       | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 11       | 1.14%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 10       | 1.03%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 10       | 1.03%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 10       | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 10       | 1.03%   |
| AMD 300 Series Chipset SATA Controller                                                  | 10       | 1.03%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 10       | 1.03%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 9        | 0.93%   |
| AMD FCH IDE Controller                                                                  | 9        | 0.93%   |
| Kingston Company A2000 NVMe SSD                                                         | 8        | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 0.83%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 7        | 0.72%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 7        | 0.72%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 0.72%   |
| AMD FCH SATA Controller D                                                               | 7        | 0.72%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                              | 6        | 0.62%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 6        | 0.62%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 6        | 0.62%   |
| Intel SSD 660P Series                                                                   | 6        | 0.62%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6        | 0.62%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 6        | 0.62%   |
| AMD X370 Series Chipset SATA Controller                                                 | 6        | 0.62%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 5        | 0.52%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 5        | 0.52%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 0.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 0.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 0.52%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4        | 0.41%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4        | 0.41%   |
| Intel SSD 600P Series                                                                   | 4        | 0.41%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4        | 0.41%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 0.41%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 4        | 0.41%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 3        | 0.31%   |
| Sandisk WD Blue SN570 NVMe SSD                                                          | 3        | 0.31%   |
| Sandisk Non-Volatile memory controller                                                  | 3        | 0.31%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 3        | 0.31%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 3        | 0.31%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 3        | 0.31%   |
| Kingston Company Company Non-Volatile memory controller                                 | 3        | 0.31%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 455      | 59.17%  |
| NVMe | 215      | 27.96%  |
| IDE  | 59       | 7.67%   |
| RAID | 30       | 3.9%    |
| SAS  | 10       | 1.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 266      | 53.31%  |
| AMD    | 233      | 46.69%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 19       | 3.81%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 12       | 2.4%    |
| AMD Ryzen 9 5950X 16-Core Processor         | 11       | 2.2%    |
| AMD Ryzen 5 3600 6-Core Processor           | 11       | 2.2%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 9        | 1.8%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 9        | 1.8%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 9        | 1.8%    |
| AMD Ryzen 7 5800X 8-Core Processor          | 9        | 1.8%    |
| AMD Ryzen 7 2700X Eight-Core Processor      | 9        | 1.8%    |
| AMD Ryzen 5 5600X 6-Core Processor          | 9        | 1.8%    |
| Intel Core i9-9900K CPU @ 3.60GHz           | 8        | 1.6%    |
| AMD Ryzen 5 3600X 6-Core Processor          | 8        | 1.6%    |
| AMD Ryzen 5 1600 Six-Core Processor         | 8        | 1.6%    |
| AMD Ryzen 7 5700G with Radeon Graphics      | 7        | 1.4%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 6        | 1.2%    |
| Intel Core i5-4460 CPU @ 3.20GHz            | 6        | 1.2%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 6        | 1.2%    |
| AMD Ryzen 5 2600X Six-Core Processor        | 6        | 1.2%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 6        | 1.2%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 5        | 1%      |
| AMD Ryzen 5 5600G with Radeon Graphics      | 5        | 1%      |
| AMD Ryzen 5 2600 Six-Core Processor         | 5        | 1%      |
| Intel Core i7-6700 CPU @ 3.40GHz            | 4        | 0.8%    |
| Intel Core i3-6100 CPU @ 3.70GHz            | 4        | 0.8%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 0.8%    |
| Intel 12th Gen Core i5-12600K               | 4        | 0.8%    |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 4        | 0.8%    |
| AMD Ryzen 7 2700 Eight-Core Processor       | 4        | 0.8%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 3        | 0.6%    |
| Intel Core i7-6700K CPU @ 4.00GHz           | 3        | 0.6%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 0.6%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 0.6%    |
| Intel Core i7-3770K CPU @ 3.50GHz           | 3        | 0.6%    |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 0.6%    |
| Intel Core i5-9600K CPU @ 3.70GHz           | 3        | 0.6%    |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 0.6%    |
| Intel Core i5-7600K CPU @ 3.80GHz           | 3        | 0.6%    |
| Intel Core i5-7500 CPU @ 3.40GHz            | 3        | 0.6%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 0.6%    |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3        | 0.6%    |
| Intel Core i5-2500 CPU @ 3.30GHz            | 3        | 0.6%    |
| Intel Core i5-10400 CPU @ 2.90GHz           | 3        | 0.6%    |
| Intel 12th Gen Core i9-12900K               | 3        | 0.6%    |
| AMD Ryzen 7 4800U with Radeon Graphics      | 3        | 0.6%    |
| AMD Ryzen 7 1700X Eight-Core Processor      | 3        | 0.6%    |
| AMD Ryzen 7 1700 Eight-Core Processor       | 3        | 0.6%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 0.6%    |
| AMD Ryzen 3 1200 Quad-Core Processor        | 3        | 0.6%    |
| AMD A4-5300 APU with Radeon HD Graphics     | 3        | 0.6%    |
| Intel Xeon CPU X5680 @ 3.33GHz              | 2        | 0.4%    |
| Intel Xeon CPU X5460 @ 3.16GHz              | 2        | 0.4%    |
| Intel Xeon CPU E5-2673 v3 @ 2.40GHz         | 2        | 0.4%    |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 2        | 0.4%    |
| Intel Core i7-9700F CPU @ 3.00GHz           | 2        | 0.4%    |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2        | 0.4%    |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 0.4%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 0.4%    |
| Intel Core i7 CPU 920 @ 2.67GHz             | 2        | 0.4%    |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 0.4%    |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 85       | 17.03%  |
| Intel Core i7           | 69       | 13.83%  |
| AMD Ryzen 5             | 65       | 13.03%  |
| AMD Ryzen 7             | 61       | 12.22%  |
| AMD Ryzen 9             | 37       | 7.41%   |
| Intel Xeon              | 29       | 5.81%   |
| Intel Core i3           | 22       | 4.41%   |
| Other                   | 18       | 3.61%   |
| Intel Core i9           | 13       | 2.61%   |
| Intel Core 2 Duo        | 10       | 2%      |
| AMD Ryzen 3             | 10       | 2%      |
| AMD FX                  | 10       | 2%      |
| AMD Ryzen Threadripper  | 7        | 1.4%    |
| AMD A4                  | 6        | 1.2%    |
| AMD A10                 | 5        | 1%      |
| Intel Pentium           | 4        | 0.8%    |
| Intel Core 2 Quad       | 4        | 0.8%    |
| AMD Athlon X4           | 4        | 0.8%    |
| AMD Athlon              | 4        | 0.8%    |
| Intel Pentium Dual-Core | 3        | 0.6%    |
| Intel Celeron           | 3        | 0.6%    |
| Intel Atom              | 3        | 0.6%    |
| AMD Phenom              | 3        | 0.6%    |
| AMD Athlon II X2        | 3        | 0.6%    |
| AMD A8                  | 3        | 0.6%    |
| AMD A6                  | 3        | 0.6%    |
| AMD Phenom II X4        | 2        | 0.4%    |
| AMD Phenom II X2        | 2        | 0.4%    |
| AMD Athlon 64 X2        | 2        | 0.4%    |
| Intel Pentium Gold      | 1        | 0.2%    |
| Intel Core 2 Extreme    | 1        | 0.2%    |
| Intel Core 2            | 1        | 0.2%    |
| AMD Ryzen Embedded      | 1        | 0.2%    |
| AMD Ryzen 7 PRO         | 1        | 0.2%    |
| AMD Ryzen 3 PRO         | 1        | 0.2%    |
| AMD Phenom II X6        | 1        | 0.2%    |
| AMD Athlon X2           | 1        | 0.2%    |
| AMD Athlon II X4        | 1        | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 170      | 34.07%  |
| 6      | 100      | 20.04%  |
| 8      | 84       | 16.83%  |
| 2      | 69       | 13.83%  |
| 12     | 28       | 5.61%   |
| 16     | 22       | 4.41%   |
| 10     | 9        | 1.8%    |
| 1      | 6        | 1.2%    |
| 24     | 5        | 1%      |
| 3      | 4        | 0.8%    |
| 32     | 1        | 0.2%    |
| 14     | 1        | 0.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 493      | 98.8%   |
| 2      | 6        | 1.2%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 348      | 69.6%   |
| 1      | 152      | 30.4%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 499      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 46       | 9.15%   |
| 0x08701021 | 46       | 9.15%   |
| Unknown    | 29       | 5.77%   |
| 0x506e3    | 20       | 3.98%   |
| 0x206a7    | 20       | 3.98%   |
| 0x306a9    | 19       | 3.78%   |
| 0x906ea    | 18       | 3.58%   |
| 0x0a201016 | 18       | 3.58%   |
| 0x0a201009 | 16       | 3.18%   |
| 0x0800820d | 16       | 3.18%   |
| 0x906e9    | 15       | 2.98%   |
| 0x906ed    | 12       | 2.39%   |
| 0x08001138 | 12       | 2.39%   |
| 0x1067a    | 11       | 2.19%   |
| 0x0a50000c | 11       | 2.19%   |
| 0x06001119 | 11       | 2.19%   |
| 0x90672    | 10       | 1.99%   |
| 0x08701013 | 9        | 1.79%   |
| 0xa0653    | 7        | 1.39%   |
| 0x206d7    | 7        | 1.39%   |
| 0x08108109 | 7        | 1.39%   |
| 0x0800820b | 7        | 1.39%   |
| 0x08001137 | 7        | 1.39%   |
| 0xa0671    | 6        | 1.19%   |
| 0xa0655    | 6        | 1.19%   |
| 0x906ec    | 6        | 1.19%   |
| 0x306f2    | 6        | 1.19%   |
| 0x106a5    | 5        | 0.99%   |
| 0x10676    | 5        | 0.99%   |
| 0x08101016 | 5        | 0.99%   |
| 0x08008206 | 5        | 0.99%   |
| 0x06003106 | 5        | 0.99%   |
| 0x0810100b | 4        | 0.8%    |
| 0x406f1    | 3        | 0.6%    |
| 0x306e4    | 3        | 0.6%    |
| 0x010000b6 | 3        | 0.6%    |
| 0x00000000 | 3        | 0.6%    |
| 0x6fb      | 2        | 0.4%    |
| 0x206c2    | 2        | 0.4%    |
| 0x20655    | 2        | 0.4%    |
| 0x106e5    | 2        | 0.4%    |
| 0x0a50000b | 2        | 0.4%    |
| 0x0a201204 | 2        | 0.4%    |
| 0x08600106 | 2        | 0.4%    |
| 0x08600103 | 2        | 0.4%    |
| 0x0700010b | 2        | 0.4%    |
| 0x06000822 | 2        | 0.4%    |
| 0x0600081c | 2        | 0.4%    |
| 0x010000c8 | 2        | 0.4%    |
| 0x010000bf | 2        | 0.4%    |
| 0x906eb    | 1        | 0.2%    |
| 0x90675    | 1        | 0.2%    |
| 0x806e9    | 1        | 0.2%    |
| 0x6fd      | 1        | 0.2%    |
| 0x6f2      | 1        | 0.2%    |
| 0x506c9    | 1        | 0.2%    |
| 0x50654    | 1        | 0.2%    |
| 0x406d8    | 1        | 0.2%    |
| 0x406c4    | 1        | 0.2%    |
| 0x406c3    | 1        | 0.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 65       | 13%     |
| KabyLake         | 60       | 12%     |
| Zen 3            | 55       | 11%     |
| Haswell          | 53       | 10.6%   |
| Zen+             | 36       | 7.2%    |
| Zen              | 29       | 5.8%    |
| SandyBridge      | 29       | 5.8%    |
| Skylake          | 25       | 5%      |
| IvyBridge        | 25       | 5%      |
| Piledriver       | 18       | 3.6%    |
| Penryn           | 17       | 3.4%    |
| CometLake        | 13       | 2.6%    |
| K10              | 12       | 2.4%    |
| Alderlake Hybrid | 11       | 2.2%    |
| Nehalem          | 7        | 1.4%    |
| Steamroller      | 6        | 1.2%    |
| Icelake          | 6        | 1.2%    |
| Westmere         | 5        | 1%      |
| Broadwell        | 5        | 1%      |
| Core             | 4        | 0.8%    |
| Silvermont       | 3        | 0.6%    |
| Jaguar           | 3        | 0.6%    |
| Bulldozer        | 3        | 0.6%    |
| K8 Hammer        | 2        | 0.4%    |
| Excavator        | 2        | 0.4%    |
| Unknown          | 2        | 0.4%    |
| Puma             | 1        | 0.2%    |
| K10 Llano        | 1        | 0.2%    |
| Goldmont         | 1        | 0.2%    |
| Bonnell          | 1        | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 211      | 38.93%  |
| AMD                        | 196      | 36.16%  |
| Intel                      | 132      | 24.35%  |
| ASPEED Technology          | 2        | 0.37%   |
| Matrox Electronics Systems | 1        | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 45       | 8.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 24       | 4.36%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 18       | 3.27%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 17       | 3.09%   |
| Intel HD Graphics 530                                                       | 16       | 2.91%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 14       | 2.55%   |
| Nvidia GK208B [GeForce GT 710]                                              | 14       | 2.55%   |
| AMD Cezanne                                                                 | 14       | 2.55%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 13       | 2.36%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 12       | 2.18%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 10       | 1.82%   |
| Intel HD Graphics 630                                                       | 8        | 1.45%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 8        | 1.45%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 8        | 1.45%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 7        | 1.27%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 7        | 1.27%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 7        | 1.27%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 7        | 1.27%   |
| Intel AlderLake-S GT1                                                       | 7        | 1.27%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 7        | 1.27%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 6        | 1.09%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 6        | 1.09%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 6        | 1.09%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 6        | 1.09%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 6        | 1.09%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 6        | 1.09%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 6        | 1.09%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 5        | 0.91%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 5        | 0.91%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 5        | 0.91%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 0.91%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 5        | 0.91%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 0.91%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 4        | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 4        | 0.73%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 4        | 0.73%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 4        | 0.73%   |
| AMD Renoir                                                                  | 4        | 0.73%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 0.55%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 0.55%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 3        | 0.55%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 0.55%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 0.55%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 0.55%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 3        | 0.55%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 3        | 0.55%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 3        | 0.55%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 3        | 0.55%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 0.55%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 3        | 0.55%   |
| AMD Navi 21 [Radeon RX 6900 XT]                                             | 3        | 0.55%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 3        | 0.55%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 3        | 0.55%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 0.36%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 2        | 0.36%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.36%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 0.36%   |
| Nvidia GP107GL [Quadro P400]                                                | 2        | 0.36%   |
| Nvidia GP107GL [Quadro P1000]                                               | 2        | 0.36%   |
| Nvidia GM107GL [Quadro K620]                                                | 2        | 0.36%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 190      | 38%     |
| 1 x AMD            | 187      | 37.4%   |
| 1 x Intel          | 93       | 18.6%   |
| Intel + Nvidia     | 14       | 2.8%    |
| 2 x AMD            | 5        | 1%      |
| 2 x Nvidia         | 2        | 0.4%    |
| Intel + AMD        | 2        | 0.4%    |
| 1 x ASPEED         | 2        | 0.4%    |
| Other              | 1        | 0.2%    |
| Nvidia + Matrox    | 1        | 0.2%    |
| Intel + 2 x Nvidia | 1        | 0.2%    |
| Intel + 2 x AMD    | 1        | 0.2%    |
| AMD + Nvidia       | 1        | 0.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 369      | 73.07%  |
| Proprietary | 123      | 24.36%  |
| Unknown     | 13       | 2.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 194      | 38.34%  |
| 7.01-8.0   | 72       | 14.23%  |
| 1.01-2.0   | 59       | 11.66%  |
| 3.01-4.0   | 52       | 10.28%  |
| 0.51-1.0   | 41       | 8.1%    |
| 0.01-0.5   | 37       | 7.31%   |
| 8.01-16.0  | 28       | 5.53%   |
| 5.01-6.0   | 18       | 3.56%   |
| 2.01-3.0   | 5        | 0.99%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 102      | 17.41%  |
| Goldstar             | 69       | 11.77%  |
| Dell                 | 69       | 11.77%  |
| Acer                 | 43       | 7.34%   |
| AOC                  | 38       | 6.48%   |
| Hewlett-Packard      | 35       | 5.97%   |
| Ancor Communications | 30       | 5.12%   |
| BenQ                 | 26       | 4.44%   |
| Philips              | 25       | 4.27%   |
| ViewSonic            | 20       | 3.41%   |
| Lenovo               | 16       | 2.73%   |
| Iiyama               | 15       | 2.56%   |
| ASUSTek Computer     | 14       | 2.39%   |
| Eizo                 | 7        | 1.19%   |
| HannStar             | 6        | 1.02%   |
| MSI                  | 5        | 0.85%   |
| Unknown              | 4        | 0.68%   |
| Vizio                | 3        | 0.51%   |
| Sony                 | 3        | 0.51%   |
| Sceptre Tech         | 3        | 0.51%   |
| Panasonic            | 3        | 0.51%   |
| NEC Computers        | 3        | 0.51%   |
| Insignia             | 3        | 0.51%   |
| Fujitsu Siemens      | 3        | 0.51%   |
| ___                  | 2        | 0.34%   |
| TCL                  | 2        | 0.34%   |
| Sharp                | 2        | 0.34%   |
| ONN                  | 2        | 0.34%   |
| Mi                   | 2        | 0.34%   |
| LG Electronics       | 2        | 0.34%   |
| Gigabyte Technology  | 2        | 0.34%   |
| DENON                | 2        | 0.34%   |
| Arnos Instruments    | 2        | 0.34%   |
| YUK                  | 1        | 0.17%   |
| Westinghouse         | 1        | 0.17%   |
| Valve                | 1        | 0.17%   |
| Unknown (XXX)        | 1        | 0.17%   |
| UGD                  | 1        | 0.17%   |
| Toshiba              | 1        | 0.17%   |
| TCT                  | 1        | 0.17%   |
| SHX                  | 1        | 0.17%   |
| RTK                  | 1        | 0.17%   |
| PRISM+               | 1        | 0.17%   |
| Plain Tree Systems   | 1        | 0.17%   |
| Pixio                | 1        | 0.17%   |
| Packard Bell         | 1        | 0.17%   |
| Hedy                 | 1        | 0.17%   |
| Haier                | 1        | 0.17%   |
| Gateway              | 1        | 0.17%   |
| Denver               | 1        | 0.17%   |
| Daewoo               | 1        | 0.17%   |
| CHE                  | 1        | 0.17%   |
| Belinea              | 1        | 0.17%   |
| Apple                | 1        | 0.17%   |
| AMT International    | 1        | 0.17%   |
| AGO                  | 1        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch              | 7        | 1.13%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5        | 0.81%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 4        | 0.65%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4        | 0.65%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 4        | 0.65%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 3        | 0.48%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 890x500mm 40.2-inch | 3        | 0.48%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch     | 3        | 0.48%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 3        | 0.48%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch           | 3        | 0.48%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                     | 3        | 0.48%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                     | 3        | 0.48%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 3        | 0.48%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 3        | 0.48%   |
| AOC 24G1WG4 AOC2401 1920x1080 521x293mm 23.5-inch                     | 3        | 0.48%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 3        | 0.48%   |
| Acer XF270HU ACR0549 2560x1440 597x336mm 27.0-inch                    | 3        | 0.48%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch         | 2        | 0.32%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 2        | 0.32%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch     | 2        | 0.32%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch   | 2        | 0.32%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 2        | 0.32%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 2        | 0.32%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2        | 0.32%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch     | 2        | 0.32%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 2        | 0.32%   |
| Samsung Electronics S22C350 SAM0A32 1920x1080 477x268mm 21.5-inch     | 2        | 0.32%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 2        | 0.32%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 2        | 0.32%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch | 2        | 0.32%   |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 890x500mm 40.2-inch | 2        | 0.32%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1196x336mm 48.9-inch    | 2        | 0.32%   |
| Samsung Electronics C27HG7x SAM0E16 2560x1440 598x336mm 27.0-inch     | 2        | 0.32%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 2        | 0.32%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 2        | 0.32%   |
| Philips PHL 223V7 PHLC154 1920x1080 476x268mm 21.5-inch               | 2        | 0.32%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 2        | 0.32%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 2        | 0.32%   |
| Insignia NS-19D310NA19 BBY0050 1680x1050 708x398mm 32.0-inch          | 2        | 0.32%   |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                 | 2        | 0.32%   |
| Iiyama PL2282H IVM5632 1920x1080 476x268mm 21.5-inch                  | 2        | 0.32%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 2        | 0.32%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 2        | 0.32%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch              | 2        | 0.32%   |
| Goldstar ULTRAGEAR GSM5BB4 2560x1440 597x336mm 27.0-inch              | 2        | 0.32%   |
| Goldstar LG HDR 4K GSM7750 3840x2160 700x400mm 31.7-inch              | 2        | 0.32%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 2        | 0.32%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                 | 2        | 0.32%   |
| Dell U2720Q DEL41B3 3840x2160 597x336mm 27.0-inch                     | 2        | 0.32%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                     | 2        | 0.32%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 2        | 0.32%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                   | 2        | 0.32%   |
| BenQ RL2455 BNQ7F1C 1920x1080 531x298mm 24.0-inch                     | 2        | 0.32%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                     | 2        | 0.32%   |
| ASUSTek Computer VG27A AUS2722 2560x1440 597x336mm 27.0-inch          | 2        | 0.32%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch          | 2        | 0.32%   |
| AOC U34G2G1 AOC3402 3440x1440 797x334mm 34.0-inch                     | 2        | 0.32%   |
| AOC AG273QS3R4 AOC2730 2560x1440 597x336mm 27.0-inch                  | 2        | 0.32%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 2        | 0.32%   |
| AOC 27B1 AOC2701 1920x1080 598x336mm 27.0-inch                        | 2        | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 262      | 46.45%  |
| 2560x1440 (QHD)    | 81       | 14.36%  |
| 3840x2160 (4K)     | 71       | 12.59%  |
| 1280x1024 (SXGA)   | 22       | 3.9%    |
| 1920x1200 (WUXGA)  | 19       | 3.37%   |
| 1680x1050 (WSXGA+) | 19       | 3.37%   |
| 1366x768 (WXGA)    | 18       | 3.19%   |
| 3440x1440          | 15       | 2.66%   |
| 1440x900 (WXGA+)   | 12       | 2.13%   |
| 1600x900 (HD+)     | 10       | 1.77%   |
| 2560x1080          | 8        | 1.42%   |
| 1600x1200          | 4        | 0.71%   |
| 1360x768           | 4        | 0.71%   |
| Unknown            | 4        | 0.71%   |
| 3840x1080          | 3        | 0.53%   |
| 2560x1600          | 3        | 0.53%   |
| 1920x540           | 2        | 0.35%   |
| 6784x2160          | 1        | 0.18%   |
| 4480x1200          | 1        | 0.18%   |
| 4480x1080          | 1        | 0.18%   |
| 3840x1600          | 1        | 0.18%   |
| 1280x960           | 1        | 0.18%   |
| 1280x720 (HD)      | 1        | 0.18%   |
| 1024x768 (XGA)     | 1        | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 133      | 22.43%  |
| 24      | 104      | 17.54%  |
| 21      | 76       | 12.82%  |
| 23      | 66       | 11.13%  |
| 31      | 34       | 5.73%   |
| 34      | 22       | 3.71%   |
| 19      | 21       | 3.54%   |
| 18      | 19       | 3.2%    |
| 22      | 17       | 2.87%   |
| 20      | 11       | 1.85%   |
| 17      | 10       | 1.69%   |
| Unknown | 10       | 1.69%   |
| 54      | 7        | 1.18%   |
| 25      | 7        | 1.18%   |
| 72      | 6        | 1.01%   |
| 84      | 5        | 0.84%   |
| 42      | 5        | 0.84%   |
| 32      | 5        | 0.84%   |
| 15      | 5        | 0.84%   |
| 48      | 4        | 0.67%   |
| 28      | 4        | 0.67%   |
| 65      | 2        | 0.34%   |
| 49      | 2        | 0.34%   |
| 47      | 2        | 0.34%   |
| 40      | 2        | 0.34%   |
| 37      | 2        | 0.34%   |
| 30      | 2        | 0.34%   |
| 26      | 2        | 0.34%   |
| 74      | 1        | 0.17%   |
| 52      | 1        | 0.17%   |
| 46      | 1        | 0.17%   |
| 35      | 1        | 0.17%   |
| 29      | 1        | 0.17%   |
| 16      | 1        | 0.17%   |
| 13      | 1        | 0.17%   |
| 12      | 1        | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 273      | 48.23%  |
| 401-500     | 127      | 22.44%  |
| 601-700     | 54       | 9.54%   |
| 701-800     | 27       | 4.77%   |
| 1001-1500   | 19       | 3.36%   |
| 351-400     | 18       | 3.18%   |
| 301-350     | 14       | 2.47%   |
| 1501-2000   | 12       | 2.12%   |
| Unknown     | 10       | 1.77%   |
| 801-900     | 5        | 0.88%   |
| 901-1000    | 5        | 0.88%   |
| 201-300     | 2        | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 402      | 76.43%  |
| 16/10   | 60       | 11.41%  |
| 5/4     | 23       | 4.37%   |
| 21/9    | 22       | 4.18%   |
| 4/3     | 6        | 1.14%   |
| Unknown | 6        | 1.14%   |
| 32/9    | 4        | 0.76%   |
| 6/5     | 2        | 0.38%   |
| 3/2     | 1        | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 196      | 33.73%  |
| 301-350        | 134      | 23.06%  |
| 351-500        | 67       | 11.53%  |
| 151-200        | 59       | 10.15%  |
| 251-300        | 39       | 6.71%   |
| 141-150        | 26       | 4.48%   |
| More than 1000 | 24       | 4.13%   |
| 501-1000       | 17       | 2.93%   |
| Unknown        | 10       | 1.72%   |
| 101-110        | 5        | 0.86%   |
| 71-80          | 2        | 0.34%   |
| 131-140        | 1        | 0.17%   |
| 121-130        | 1        | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 310      | 56.88%  |
| 101-120 | 149      | 27.34%  |
| 121-160 | 34       | 6.24%   |
| 161-240 | 22       | 4.04%   |
| 1-50    | 20       | 3.67%   |
| Unknown | 10       | 1.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 360      | 71.43%  |
| 2     | 117      | 23.21%  |
| 0     | 16       | 3.17%   |
| 3     | 10       | 1.98%   |
| 4     | 1        | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 279      | 39.24%  |
| Intel                           | 271      | 38.12%  |
| Qualcomm Atheros                | 36       | 5.06%   |
| TP-Link                         | 19       | 2.67%   |
| Broadcom                        | 14       | 1.97%   |
| Ralink Technology               | 13       | 1.83%   |
| Aquantia                        | 9        | 1.27%   |
| Nvidia                          | 6        | 0.84%   |
| Microsoft                       | 6        | 0.84%   |
| ASUSTek Computer                | 4        | 0.56%   |
| Xiaomi                          | 3        | 0.42%   |
| Samsung Electronics             | 3        | 0.42%   |
| Ralink                          | 3        | 0.42%   |
| NetGear                         | 3        | 0.42%   |
| Marvell Technology Group        | 3        | 0.42%   |
| Google                          | 3        | 0.42%   |
| D-Link                          | 3        | 0.42%   |
| Belkin Components               | 3        | 0.42%   |
| AVM                             | 3        | 0.42%   |
| Wilocity                        | 2        | 0.28%   |
| OpenMoko                        | 2        | 0.28%   |
| Linksys                         | 2        | 0.28%   |
| InterBiometrics                 | 2        | 0.28%   |
| ICS Advent                      | 2        | 0.28%   |
| Edimax Technology               | 2        | 0.28%   |
| Xilinx                          | 1        | 0.14%   |
| Winbond Electronics             | 1        | 0.14%   |
| Unknown                         | 1        | 0.14%   |
| U-Blox                          | 1        | 0.14%   |
| Sigma Designs                   | 1        | 0.14%   |
| RetroFreak PCB                  | 1        | 0.14%   |
| Qualcomm Atheros Communications | 1        | 0.14%   |
| Mellanox Technologies           | 1        | 0.14%   |
| MediaTek                        | 1        | 0.14%   |
| Huawei Technologies             | 1        | 0.14%   |
| HMD Global                      | 1        | 0.14%   |
| DisplayLink                     | 1        | 0.14%   |
| Broadcom Limited                | 1        | 0.14%   |
| ASIX Electronics                | 1        | 0.14%   |
| Apple                           | 1        | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 213      | 25.06%  |
| Intel Wi-Fi 6 AX200                                               | 70       | 8.24%   |
| Intel I211 Gigabit Network Connection                             | 65       | 7.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 41       | 4.82%   |
| Intel Ethernet Controller I225-V                                  | 28       | 3.29%   |
| Intel Ethernet Connection (7) I219-V                              | 21       | 2.47%   |
| Intel Ethernet Connection (2) I219-V                              | 21       | 2.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17       | 2%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 15       | 1.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10       | 1.18%   |
| Intel Wireless-AC 9260                                            | 10       | 1.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 10       | 1.18%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 9        | 1.06%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 8        | 0.94%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8        | 0.94%   |
| Intel Ethernet Connection I217-LM                                 | 8        | 0.94%   |
| Intel Ethernet Connection (2) I219-LM                             | 8        | 0.94%   |
| Intel 82579V Gigabit Network Connection                           | 8        | 0.94%   |
| Intel 82574L Gigabit Network Connection                           | 8        | 0.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6        | 0.71%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 6        | 0.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5        | 0.59%   |
| Ralink RT5370 Wireless Adapter                                    | 5        | 0.59%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4        | 0.47%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 4        | 0.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 0.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4        | 0.47%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 4        | 0.47%   |
| Intel Wireless 8260                                               | 4        | 0.47%   |
| Intel I350 Gigabit Network Connection                             | 4        | 0.47%   |
| Intel Ethernet Connection I217-V                                  | 4        | 0.47%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 0.47%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4        | 0.47%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 4        | 0.47%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 0.47%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3        | 0.35%   |
| TP-Link 802.11ac WLAN Adapter                                     | 3        | 0.35%   |
| TP-Link 802.11ac NIC                                              | 3        | 0.35%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.35%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 3        | 0.35%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 3        | 0.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 0.35%   |
| Realtek 802.11ac NIC                                              | 3        | 0.35%   |
| Ralink RT5372 Wireless Adapter                                    | 3        | 0.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3        | 0.35%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3        | 0.35%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3        | 0.35%   |
| Microsoft XBOX ACC                                                | 3        | 0.35%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3        | 0.35%   |
| Intel I210 Gigabit Network Connection                             | 3        | 0.35%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.35%   |
| Intel Ethernet Connection (2) I218-LM                             | 3        | 0.35%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 3        | 0.35%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.24%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                | 2        | 0.24%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.24%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 0.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2        | 0.24%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 142      | 53.18%  |
| Realtek Semiconductor           | 34       | 12.73%  |
| TP-Link                         | 19       | 7.12%   |
| Qualcomm Atheros                | 17       | 6.37%   |
| Ralink Technology               | 13       | 4.87%   |
| Broadcom                        | 10       | 3.75%   |
| Microsoft                       | 6        | 2.25%   |
| Ralink                          | 3        | 1.12%   |
| NetGear                         | 3        | 1.12%   |
| D-Link                          | 3        | 1.12%   |
| Belkin Components               | 3        | 1.12%   |
| AVM                             | 3        | 1.12%   |
| ASUSTek Computer                | 3        | 1.12%   |
| Wilocity                        | 2        | 0.75%   |
| Linksys                         | 2        | 0.75%   |
| Edimax Technology               | 2        | 0.75%   |
| Qualcomm Atheros Communications | 1        | 0.37%   |
| MediaTek                        | 1        | 0.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                              | 70       | 25.83%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                 | 15       | 5.54%   |
| Intel Wireless-AC 9260                                           | 10       | 3.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 10       | 3.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                           | 9        | 3.32%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                      | 8        | 2.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter              | 6        | 2.21%   |
| Intel Alder Lake-S PCH CNVi WiFi                                 | 6        | 2.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter         | 5        | 1.85%   |
| Ralink RT5370 Wireless Adapter                                   | 5        | 1.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 4        | 1.48%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                  | 4        | 1.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 4        | 1.48%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                 | 4        | 1.48%   |
| Intel Wireless 8260                                              | 4        | 1.48%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter               | 4        | 1.48%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter               | 4        | 1.48%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                     | 3        | 1.11%   |
| TP-Link 802.11ac WLAN Adapter                                    | 3        | 1.11%   |
| TP-Link 802.11ac NIC                                             | 3        | 1.11%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                       | 3        | 1.11%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                           | 3        | 1.11%   |
| Realtek 802.11ac NIC                                             | 3        | 1.11%   |
| Ralink RT5372 Wireless Adapter                                   | 3        | 1.11%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)   | 3        | 1.11%   |
| Microsoft XBOX ACC                                               | 3        | 1.11%   |
| Intel Tiger Lake PCH CNVi WiFi                                   | 3        | 1.11%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter               | 2        | 0.74%   |
| Ralink MT7601U Wireless Adapter                                  | 2        | 0.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 2        | 0.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 2        | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                 | 2        | 0.74%   |
| Microsoft Wireless XBox Controller Dongle                        | 2        | 0.74%   |
| Intel Wireless 7265                                              | 2        | 0.74%   |
| Intel Wireless 7260                                              | 2        | 0.74%   |
| Intel Wireless 3165                                              | 2        | 0.74%   |
| Intel Wireless 3160                                              | 2        | 0.74%   |
| Intel Centrino Wireless-N 2230                                   | 2        | 0.74%   |
| Broadcom BCM43228 802.11a/b/g/n                                  | 2        | 0.74%   |
| AVM FRITZ!WLAN AC 860                                            | 2        | 0.74%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                            | 1        | 0.37%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                              | 1        | 0.37%   |
| Realtek RTL88x2bu [AC1200 Techkey]                               | 1        | 0.37%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter         | 1        | 0.37%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                  | 1        | 0.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 1        | 0.37%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                  | 1        | 0.37%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                  | 1        | 0.37%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                           | 1        | 0.37%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter            | 1        | 0.37%   |
| Ralink RT2870/RT3070 Wireless Adapter                            | 1        | 0.37%   |
| Ralink RT2501/RT2573 Wireless Adapter                            | 1        | 0.37%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                | 1        | 0.37%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                        | 1        | 0.37%   |
| Ralink RT2800 802.11n PCI                                        | 1        | 0.37%   |
| Ralink RT2500 Wireless 802.11bg                                  | 1        | 0.37%   |
| Qualcomm Atheros AR5523                                          | 1        | 0.37%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter       | 1        | 0.37%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]            | 1        | 0.37%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101] | 1        | 0.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 263      | 48.79%  |
| Intel                    | 213      | 39.52%  |
| Qualcomm Atheros         | 21       | 3.9%    |
| Aquantia                 | 9        | 1.67%   |
| Nvidia                   | 6        | 1.11%   |
| Broadcom                 | 4        | 0.74%   |
| Xiaomi                   | 3        | 0.56%   |
| Samsung Electronics      | 3        | 0.56%   |
| Marvell Technology Group | 3        | 0.56%   |
| ICS Advent               | 2        | 0.37%   |
| Xilinx                   | 1        | 0.19%   |
| Unknown                  | 1        | 0.19%   |
| OpenMoko                 | 1        | 0.19%   |
| Mellanox Technologies    | 1        | 0.19%   |
| Huawei Technologies      | 1        | 0.19%   |
| HMD Global               | 1        | 0.19%   |
| Google                   | 1        | 0.19%   |
| DisplayLink              | 1        | 0.19%   |
| Broadcom Limited         | 1        | 0.19%   |
| ASUSTek Computer         | 1        | 0.19%   |
| ASIX Electronics         | 1        | 0.19%   |
| Apple                    | 1        | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 213      | 37.43%  |
| Intel I211 Gigabit Network Connection                                         | 65       | 11.42%  |
| Realtek RTL8125 2.5GbE Controller                                             | 41       | 7.21%   |
| Intel Ethernet Controller I225-V                                              | 28       | 4.92%   |
| Intel Ethernet Connection (7) I219-V                                          | 21       | 3.69%   |
| Intel Ethernet Connection (2) I219-V                                          | 21       | 3.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 17       | 2.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 10       | 1.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 8        | 1.41%   |
| Intel Ethernet Connection I217-LM                                             | 8        | 1.41%   |
| Intel Ethernet Connection (2) I219-LM                                         | 8        | 1.41%   |
| Intel 82579V Gigabit Network Connection                                       | 8        | 1.41%   |
| Intel 82574L Gigabit Network Connection                                       | 8        | 1.41%   |
| Intel Ethernet Connection (2) I218-V                                          | 5        | 0.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4        | 0.7%    |
| Intel I350 Gigabit Network Connection                                         | 4        | 0.7%    |
| Intel Ethernet Connection I217-V                                              | 4        | 0.7%    |
| Intel 82567LM-3 Gigabit Network Connection                                    | 4        | 0.7%    |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 4        | 0.7%    |
| Samsung Galaxy series, misc. (tethering mode)                                 | 3        | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3        | 0.53%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 3        | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 3        | 0.53%   |
| Intel I210 Gigabit Network Connection                                         | 3        | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 0.53%   |
| Intel Ethernet Connection (2) I218-LM                                         | 3        | 0.53%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3        | 0.53%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 3        | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 2        | 0.35%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2        | 0.35%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2        | 0.35%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2        | 0.35%   |
| Nvidia MCP61 Ethernet                                                         | 2        | 0.35%   |
| Nvidia MCP55 Ethernet                                                         | 2        | 0.35%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 2        | 0.35%   |
| Intel Ethernet Controller X550                                                | 2        | 0.35%   |
| Intel Ethernet Connection (14) I219-LM                                        | 2        | 0.35%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 0.35%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.35%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                       | 2        | 0.35%   |
| Xilinx Smart JTAG Cable                                                       | 1        | 0.18%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1        | 0.18%   |
| Unknown Ceton InfiniTV Network                                                | 1        | 0.18%   |
| Realtek USB 10/100/1G/2.5G LAN                                                | 1        | 0.18%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1        | 0.18%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1        | 0.18%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 1        | 0.18%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1        | 0.18%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1        | 0.18%   |
| OpenMoko Duet 2 WiFi or Duet 2 Ethernet 3D printer control electronics        | 1        | 0.18%   |
| Nvidia MCP79 Ethernet                                                         | 1        | 0.18%   |
| Nvidia MCP51 Ethernet Controller                                              | 1        | 0.18%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 1        | 0.18%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1        | 0.18%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1        | 0.18%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 0.18%   |
| Intel 82583V Gigabit Network Connection                                       | 1        | 0.18%   |
| Intel 82578DM Gigabit Network Connection                                      | 1        | 0.18%   |
| Intel 82576 Gigabit Network Connection                                        | 1        | 0.18%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 0.18%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 497      | 66.36%  |
| WiFi     | 243      | 32.44%  |
| Modem    | 8        | 1.07%   |
| Unknown  | 1        | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 399      | 75.57%  |
| WiFi     | 129      | 24.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 274      | 54.58%  |
| 2     | 180      | 35.86%  |
| 3     | 32       | 6.37%   |
| 4     | 6        | 1.2%    |
| 0     | 4        | 0.8%    |
| 6     | 3        | 0.6%    |
| 5     | 3        | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 363      | 72.6%   |
| Yes  | 137      | 27.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 136      | 56.67%  |
| Cambridge Silicon Radio         | 44       | 18.33%  |
| ASUSTek Computer                | 19       | 7.92%   |
| Broadcom                        | 11       | 4.58%   |
| Realtek Semiconductor           | 10       | 4.17%   |
| Qualcomm Atheros Communications | 7        | 2.92%   |
| Apple                           | 4        | 1.67%   |
| TP-Link                         | 3        | 1.25%   |
| Belkin Components               | 2        | 0.83%   |
| Lite-On Technology              | 1        | 0.42%   |
| IMC Networks                    | 1        | 0.42%   |
| Edimax Technology               | 1        | 0.42%   |
| Dell                            | 1        | 0.42%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                 | 67       | 27.92%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 44       | 18.33%  |
| Intel Wireless-AC 3168 Bluetooth                      | 15       | 6.25%   |
| Intel Bluetooth wireless interface                    | 13       | 5.42%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 10       | 4.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 10       | 4.17%   |
| Intel AX210 Bluetooth                                 | 9        | 3.75%   |
| Realtek Bluetooth Radio                               | 8        | 3.33%   |
| Intel AX201 Bluetooth                                 | 8        | 3.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 7        | 2.92%   |
| ASUS Bluetooth Radio                                  | 5        | 2.08%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 4        | 1.67%   |
| TP-Link UB500 Adapter                                 | 3        | 1.25%   |
| ASUS ASUS USB-BT500                                   | 3        | 1.25%   |
| Realtek  Bluetooth 4.2 Adapter                        | 2        | 0.83%   |
| Qualcomm Atheros  Bluetooth Device                    | 2        | 0.83%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 2        | 0.83%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 2        | 0.83%   |
| ASUS Bluetooth Device                                 | 2        | 0.83%   |
| ASUS Bluetooth Adapter                                | 2        | 0.83%   |
| ASUS BCM20702A0                                       | 2        | 0.83%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 2        | 0.83%   |
| Apple Bluetooth USB Host Controller                   | 2        | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1        | 0.42%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1        | 0.42%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1        | 0.42%   |
| Lite-On Bluetooth Device                              | 1        | 0.42%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 1        | 0.42%   |
| Intel Bluetooth Device                                | 1        | 0.42%   |
| IMC Networks Bluetooth Device                         | 1        | 0.42%   |
| Edimax Bluetooth Device                               | 1        | 0.42%   |
| Dell Wireless 365 Bluetooth                           | 1        | 0.42%   |
| Broadcom HP Portable Bumble Bee                       | 1        | 0.42%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle    | 1        | 0.42%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 0.42%   |
| Broadcom BCM2045 Bluetooth                            | 1        | 0.42%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 1        | 0.42%   |
| Belkin Components F8T012 Bluetooth Adapter            | 1        | 0.42%   |
| ASUS Qualcomm Bluetooth 4.1                           | 1        | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 276      | 29.05%  |
| Intel                                | 252      | 26.53%  |
| Nvidia                               | 200      | 21.05%  |
| C-Media Electronics                  | 23       | 2.42%   |
| Logitech                             | 14       | 1.47%   |
| Creative Labs                        | 13       | 1.37%   |
| SteelSeries ApS                      | 10       | 1.05%   |
| JMTek                                | 10       | 1.05%   |
| Texas Instruments                    | 9        | 0.95%   |
| Focusrite-Novation                   | 9        | 0.95%   |
| Plantronics                          | 8        | 0.84%   |
| Kingston Technology                  | 8        | 0.84%   |
| Corsair                              | 8        | 0.84%   |
| Razer USA                            | 7        | 0.74%   |
| GN Netcom                            | 6        | 0.63%   |
| Blue Microphones                     | 5        | 0.53%   |
| Tenx Technology                      | 4        | 0.42%   |
| Sony                                 | 4        | 0.42%   |
| Sennheiser Communications            | 4        | 0.42%   |
| Realtek Semiconductor                | 4        | 0.42%   |
| Generalplus Technology               | 4        | 0.42%   |
| Creative Technology                  | 4        | 0.42%   |
| Samson Technologies                  | 3        | 0.32%   |
| RODE Microphones                     | 3        | 0.32%   |
| Giga-Byte Technology                 | 3        | 0.32%   |
| ASUSTek Computer                     | 3        | 0.32%   |
| Apogee Electronics                   | 3        | 0.32%   |
| Yamaha                               | 2        | 0.21%   |
| Unknown                              | 2        | 0.21%   |
| SAVITECH                             | 2        | 0.21%   |
| GYROCOM C&C                          | 2        | 0.21%   |
| Drop                                 | 2        | 0.21%   |
| Cambridge Silicon Radio              | 2        | 0.21%   |
| Audio-Technica                       | 2        | 0.21%   |
| Apple                                | 2        | 0.21%   |
| Unknown                              | 2        | 0.21%   |
| XMOS                                 | 1        | 0.11%   |
| Valve Software                       | 1        | 0.11%   |
| ULi Electronics                      | 1        | 0.11%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.11%   |
| Thermaltake                          | 1        | 0.11%   |
| ShareWave                            | 1        | 0.11%   |
| Schiit Audio                         | 1        | 0.11%   |
| Roland                               | 1        | 0.11%   |
| RME                                  | 1        | 0.11%   |
| Quanta                               | 1        | 0.11%   |
| PreSonus Audio Electronics           | 1        | 0.11%   |
| Native Instruments                   | 1        | 0.11%   |
| Microsoft                            | 1        | 0.11%   |
| Microdia                             | 1        | 0.11%   |
| Micro Star International             | 1        | 0.11%   |
| Meizu                                | 1        | 0.11%   |
| Mark of the Unicorn                  | 1        | 0.11%   |
| Lenovo                               | 1        | 0.11%   |
| Jieli Technology                     | 1        | 0.11%   |
| Huawei Technologies                  | 1        | 0.11%   |
| HiFimeDIY Audio                      | 1        | 0.11%   |
| Goldvish                             | 1        | 0.11%   |
| FiiO Electronics Technology          | 1        | 0.11%   |
| FIFINE Microphones                   | 1        | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 97       | 8.62%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 47       | 4.18%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 45       | 4%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 35       | 3.11%   |
| AMD Family 17h/19h HD Audio Controller                                     | 35       | 3.11%   |
| Intel Cannon Lake PCH cAVS                                                 | 32       | 2.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 26       | 2.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 26       | 2.31%   |
| Intel 200 Series PCH HD Audio                                              | 26       | 2.31%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 26       | 2.31%   |
| Nvidia GP107GL High Definition Audio Controller                            | 25       | 2.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 22       | 1.96%   |
| AMD Navi 10 HDMI Audio                                                     | 22       | 1.96%   |
| AMD FCH Azalia Controller                                                  | 21       | 1.87%   |
| Nvidia GP106 High Definition Audio Controller                              | 19       | 1.69%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 19       | 1.69%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 18       | 1.6%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 18       | 1.6%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 17       | 1.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 17       | 1.51%   |
| Nvidia TU106 High Definition Audio Controller                              | 14       | 1.24%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 13       | 1.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 13       | 1.16%   |
| Nvidia TU104 HD Audio Controller                                           | 11       | 0.98%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 11       | 0.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 10       | 0.89%   |
| Intel Alder Lake-S HD Audio Controller                                     | 10       | 0.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 10       | 0.89%   |
| Nvidia GA102 High Definition Audio Controller                              | 9        | 0.8%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 9        | 0.8%    |
| Nvidia GP104 High Definition Audio Controller                              | 8        | 0.71%   |
| Nvidia GM206 High Definition Audio Controller                              | 8        | 0.71%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 8        | 0.71%   |
| Nvidia TU116 High Definition Audio Controller                              | 7        | 0.62%   |
| Nvidia GP102 HDMI Audio Controller                                         | 7        | 0.62%   |
| Nvidia GK107 HDMI Audio Controller                                         | 7        | 0.62%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 7        | 0.62%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 7        | 0.62%   |
| Nvidia TU102 High Definition Audio Controller                              | 6        | 0.53%   |
| Nvidia GP108 High Definition Audio Controller                              | 6        | 0.53%   |
| Nvidia GA104 High Definition Audio Controller                              | 6        | 0.53%   |
| Intel Comet Lake PCH cAVS                                                  | 6        | 0.53%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 6        | 0.53%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 6        | 0.53%   |
| Texas Instruments PCM2902 Audio Codec                                      | 5        | 0.44%   |
| Nvidia High Definition Audio Controller                                    | 5        | 0.44%   |
| Nvidia GK104 HDMI Audio Controller                                         | 5        | 0.44%   |
| JMTek USB PnP Audio Device                                                 | 5        | 0.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5        | 0.44%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 4        | 0.36%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4        | 0.36%   |
| Nvidia GM204 High Definition Audio Controller                              | 4        | 0.36%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 0.36%   |
| Intel USB PnP Sound Device                                                 | 4        | 0.36%   |
| Intel Comet Lake PCH-V cAVS                                                | 4        | 0.36%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 4        | 0.36%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 4        | 0.36%   |
| C-Media Electronics SADES Luna                                             | 4        | 0.36%   |
| AMD Trinity HDMI Audio Controller                                          | 4        | 0.36%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 4        | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 52       | 18.71%  |
| Corsair             | 52       | 18.71%  |
| G.Skill             | 34       | 12.23%  |
| Crucial             | 33       | 11.87%  |
| Unknown             | 31       | 11.15%  |
| Samsung Electronics | 20       | 7.19%   |
| SK Hynix            | 19       | 6.83%   |
| Team                | 6        | 2.16%   |
| Micron Technology   | 6        | 2.16%   |
| Unknown             | 4        | 1.44%   |
| A-DATA Technology   | 3        | 1.08%   |
| Ramaxel Technology  | 2        | 0.72%   |
| Patriot             | 2        | 0.72%   |
| GOODRAM             | 2        | 0.72%   |
| V-GeN               | 1        | 0.36%   |
| Unknown (ABCD)      | 1        | 0.36%   |
| Unknown (AB)        | 1        | 0.36%   |
| Toshiba             | 1        | 0.36%   |
| TIMETEC             | 1        | 0.36%   |
| Qumo                | 1        | 0.36%   |
| PLEXHD              | 1        | 0.36%   |
| Patriot Memory      | 1        | 0.36%   |
| OLOY                | 1        | 0.36%   |
| OCZ                 | 1        | 0.36%   |
| Apacer              | 1        | 0.36%   |
| AMD                 | 1        | 0.36%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s          | 7        | 2.34%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s         | 5        | 1.67%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 4        | 1.34%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3533MT/s        | 4        | 1.34%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 4        | 1.34%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 4        | 1.34%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 4        | 1.34%   |
| Unknown                                                        | 4        | 1.34%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s        | 3        | 1%      |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 3        | 1%      |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3600MT/s          | 3        | 1%      |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s            | 3        | 1%      |
| Unknown RAM Module 8GB DIMM 1600MT/s                           | 2        | 0.67%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 2        | 0.67%   |
| Unknown RAM Module 4GB DIMM 800MT/s                            | 2        | 0.67%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 2        | 0.67%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 2        | 0.67%   |
| Unknown RAM 3600 C18 Series 16GB DIMM DDR4 2933MT/s            | 2        | 0.67%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1066MT/s                     | 2        | 0.67%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                      | 2        | 0.67%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s           | 2        | 0.67%   |
| Kingston RAM Module 4GB DIMM DDR3 1066MT/s                     | 2        | 0.67%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 2        | 0.67%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s            | 2        | 0.67%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s         | 2        | 0.67%   |
| Kingston RAM KHX1600C10D3/8G 4096MB DIMM DDR3 1600MT/s         | 2        | 0.67%   |
| Kingston RAM CBD32D4S2S8ME-16 16GB SODIMM DDR4 3200MT/s        | 2        | 0.67%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s          | 2        | 0.67%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s         | 2        | 0.67%   |
| G.Skill RAM F4-3200C14-16GVK 16GB DIMM DDR4 3200MT/s           | 2        | 0.67%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s       | 2        | 0.67%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s          | 2        | 0.67%   |
| Crucial RAM BLS16G4D32AESB.M16FE 16GB DIMM DDR4 3600MT/s       | 2        | 0.67%   |
| Crucial RAM BL8G32C16U4B.8FE 8GB DIMM DDR4 3466MT/s            | 2        | 0.67%   |
| Corsair RAM CMX4GX3M2A1600C9 2GB DIMM DDR3 1600MT/s            | 2        | 0.67%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s          | 2        | 0.67%   |
| Corsair RAM CMW16GX4M2C3000C15 8GB DIMM DDR4 3200MT/s          | 2        | 0.67%   |
| Corsair RAM CML16GX3M2A1600C9 8GB DIMM DDR3 2133MT/s           | 2        | 0.67%   |
| Corsair RAM CMK64GX4M4B3200C16 16GB DIMM DDR4 3200MT/s         | 2        | 0.67%   |
| V-GeN RAM D4H8GL32A8TS 8GB DIMM DDR4 3200MT/s                  | 1        | 0.33%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1        | 0.33%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                      | 1        | 0.33%   |
| Unknown RAM Module 4GB DIMM 400MT/s                            | 1        | 0.33%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1        | 0.33%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                           | 1        | 0.33%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 1        | 0.33%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                      | 1        | 0.33%   |
| Unknown RAM Module 2GB DIMM 667MT/s                            | 1        | 0.33%   |
| Unknown RAM Module 2GB DIMM 400MT/s                            | 1        | 0.33%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.33%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                           | 1        | 0.33%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                   | 1        | 0.33%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                       | 1        | 0.33%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                        | 1        | 0.33%   |
| Unknown RAM Module 16GB SODIMM DDR4 2667MT/s                   | 1        | 0.33%   |
| Unknown RAM CL19-19-19 D4-2666 8192MB DIMM DDR4 2400MT/s       | 1        | 0.33%   |
| Unknown RAM 3733 C17 Series 8192MB DIMM DDR4 2133MT/s          | 1        | 0.33%   |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s             | 1        | 0.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 0.33%   |
| Unknown (AB) RAM Module 2GB DIMM LPDDR3 1333MT/s               | 1        | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 156      | 62.4%   |
| DDR3    | 68       | 27.2%   |
| Unknown | 15       | 6%      |
| DDR2    | 5        | 2%      |
| SDRAM   | 2        | 0.8%    |
| DDR     | 2        | 0.8%    |
| LPDDR4  | 1        | 0.4%    |
| LPDDR3  | 1        | 0.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 236      | 95.16%  |
| SODIMM | 12       | 4.84%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 106      | 40.3%   |
| 16384 | 62       | 23.57%  |
| 4096  | 48       | 18.25%  |
| 2048  | 26       | 9.89%   |
| 32768 | 18       | 6.84%   |
| 1024  | 3        | 1.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 43       | 15.87%  |
| 3200    | 42       | 15.5%   |
| 3600    | 30       | 11.07%  |
| 1333    | 24       | 8.86%   |
| 2400    | 17       | 6.27%   |
| 2667    | 16       | 5.9%    |
| 3466    | 15       | 5.54%   |
| 2133    | 13       | 4.8%    |
| 2933    | 7        | 2.58%   |
| 800     | 7        | 2.58%   |
| 1867    | 6        | 2.21%   |
| 3000    | 5        | 1.85%   |
| 2666    | 5        | 1.85%   |
| 3733    | 4        | 1.48%   |
| 3533    | 4        | 1.48%   |
| 3400    | 4        | 1.48%   |
| 1066    | 4        | 1.48%   |
| 3800    | 3        | 1.11%   |
| 1067    | 3        | 1.11%   |
| 4800    | 2        | 0.74%   |
| 3266    | 2        | 0.74%   |
| 2800    | 2        | 0.74%   |
| 400     | 2        | 0.74%   |
| 4000    | 1        | 0.37%   |
| 3866    | 1        | 0.37%   |
| 3500    | 1        | 0.37%   |
| 2802    | 1        | 0.37%   |
| 2134    | 1        | 0.37%   |
| 1866    | 1        | 0.37%   |
| 1024    | 1        | 0.37%   |
| 667     | 1        | 0.37%   |
| 533     | 1        | 0.37%   |
| 333     | 1        | 0.37%   |
| Unknown | 1        | 0.37%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 7        | 30.43%  |
| Brother Industries  | 7        | 30.43%  |
| Canon               | 3        | 13.04%  |
| Kyocera             | 2        | 8.7%    |
| Seiko Epson         | 1        | 4.35%   |
| Samsung Electronics | 1        | 4.35%   |
| QinHeng Electronics | 1        | 4.35%   |
| Prolific Technology | 1        | 4.35%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| HP DeskJet 2130 series        | 2        | 8.7%    |
| Brother HL-L2340D series      | 2        | 8.7%    |
| Seiko Epson WF-2510 Series    | 1        | 4.35%   |
| Samsung M2070 Series          | 1        | 4.35%   |
| QinHeng CH340S                | 1        | 4.35%   |
| Prolific PL2305 Parallel Port | 1        | 4.35%   |
| Kyocera TASKalfa 250ci        | 1        | 4.35%   |
| Kyocera ECOSYS M5521cdw       | 1        | 4.35%   |
| HP Officejet 6600             | 1        | 4.35%   |
| HP LaserJet CM1415fnw         | 1        | 4.35%   |
| HP DeskJet F300 series        | 1        | 4.35%   |
| HP DeskJet F2492 All-in-One   | 1        | 4.35%   |
| HP DeskJet 3700 series        | 1        | 4.35%   |
| Canon TR4500 series           | 1        | 4.35%   |
| Canon MF4010 series           | 1        | 4.35%   |
| Canon G3010 series            | 1        | 4.35%   |
| Brother Printer               | 1        | 4.35%   |
| Brother MFC-J485DW            | 1        | 4.35%   |
| Brother HL-L2360D series      | 1        | 4.35%   |
| Brother HL-2030 Laser Printer | 1        | 4.35%   |
| Brother HL-1440 Laser Printer | 1        | 4.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 3        | 42.86%  |
| Canon           | 3        | 42.86%  |
| Hewlett-Packard | 1        | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Seiko Epson GT-X770 [Perfection V500]       | 2        | 28.57%  |
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 1        | 14.29%  |
| HP ScanJet 5590                             | 1        | 14.29%  |
| Canon CanoScan LiDE 220                     | 1        | 14.29%  |
| Canon CanoScan LiDE 210                     | 1        | 14.29%  |
| Canon CanoScan LiDE 120                     | 1        | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 66       | 50.38%  |
| Microsoft                              | 8        | 6.11%   |
| Microdia                               | 7        | 5.34%   |
| Apple                                  | 5        | 3.82%   |
| Generalplus Technology                 | 4        | 3.05%   |
| Sunplus Innovation Technology          | 3        | 2.29%   |
| Jieli Technology                       | 3        | 2.29%   |
| Cubeternet                             | 3        | 2.29%   |
| Z-Star Microelectronics                | 2        | 1.53%   |
| Trust                                  | 2        | 1.53%   |
| Samsung Electronics                    | 2        | 1.53%   |
| Lenovo                                 | 2        | 1.53%   |
| KYE Systems (Mouse Systems)            | 2        | 1.53%   |
| Genesys Logic                          | 2        | 1.53%   |
| Creative Technology                    | 2        | 1.53%   |
| Unknown                                | 1        | 0.76%   |
| Tobii Technology AB                    | 1        | 0.76%   |
| Sonix Technology                       | 1        | 0.76%   |
| Quanta                                 | 1        | 0.76%   |
| Nokia Mobile Phones                    | 1        | 0.76%   |
| Micro Star International               | 1        | 0.76%   |
| MacroSilicon                           | 1        | 0.76%   |
| Linux Foundation                       | 1        | 0.76%   |
| LG Electronics                         | 1        | 0.76%   |
| Hewlett-Packard                        | 1        | 0.76%   |
| Guillemot                              | 1        | 0.76%   |
| Google                                 | 1        | 0.76%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 0.76%   |
| Arkmicro Technologies                  | 1        | 0.76%   |
| ARC International                      | 1        | 0.76%   |
| Anker                                  | 1        | 0.76%   |
| Acer                                   | 1        | 0.76%   |
| A4Tech                                 | 1        | 0.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                   | 16       | 12.21%  |
| Logitech Webcam C270                          | 14       | 10.69%  |
| Microsoft LifeCam HD-3000                     | 4        | 3.05%   |
| Microdia Webcam Vitade AF                     | 4        | 3.05%   |
| Logitech StreamCam                            | 4        | 3.05%   |
| Logitech HD Webcam C525                       | 4        | 3.05%   |
| Logitech C922 Pro Stream Webcam               | 4        | 3.05%   |
| Apple iPhone 5/5C/5S/6/SE                     | 4        | 3.05%   |
| Logitech HD Webcam C615                       | 3        | 2.29%   |
| Logitech C920 PRO HD Webcam                   | 3        | 2.29%   |
| Jieli USB PHY 2.0                             | 3        | 2.29%   |
| Generalplus CAMERA - UVC                      | 3        | 2.29%   |
| Samsung Galaxy A5 (MTP)                       | 2        | 1.53%   |
| Microsoft LifeCam Cinema                      | 2        | 1.53%   |
| Logitech Webcam Pro 9000                      | 2        | 1.53%   |
| Logitech Webcam C310                          | 2        | 1.53%   |
| Logitech Webcam C170                          | 2        | 1.53%   |
| Logitech QuickCam Pro 9000                    | 2        | 1.53%   |
| Logitech BRIO Ultra HD Webcam                 | 2        | 1.53%   |
| Genesys Logic Camera                          | 2        | 1.53%   |
| Creative Live! Cam Sync HD [VF0770]           | 2        | 1.53%   |
| Z-Star Venus USB2.0 Camera                    | 1        | 0.76%   |
| Z-Star Sirius USB 2.0 Camera                  | 1        | 0.76%   |
| Unknown HD camera                             | 1        | 0.76%   |
| Trust USB Camera                              | 1        | 0.76%   |
| Trust Full HD Webcam                          | 1        | 0.76%   |
| Tobii AB EyeChip                              | 1        | 0.76%   |
| Sunplus HD 720P webcam                        | 1        | 0.76%   |
| Sunplus ezcap U3 capture-04                   | 1        | 0.76%   |
| Sunplus Aukey-PC-LM1E Camera                  | 1        | 0.76%   |
| Sonix USB Camera                              | 1        | 0.76%   |
| Quanta HD Camera                              | 1        | 0.76%   |
| Nokia Mobile Phones Lumia 620/920             | 1        | 0.76%   |
| Microsoft Xbox NUI Camera                     | 1        | 0.76%   |
| Microsoft LifeCam VX-5000                     | 1        | 0.76%   |
| Microdia USB Camera                           | 1        | 0.76%   |
| Microdia USB 2.0 Camera                       | 1        | 0.76%   |
| Microdia CyberTrack H6                        | 1        | 0.76%   |
| Micro Star International MSI USB Device       | 1        | 0.76%   |
| MacroSilicon MS210x Video Grabber [EasierCAP] | 1        | 0.76%   |
| Logitech Webcam C930e                         | 1        | 0.76%   |
| Logitech Webcam C925e                         | 1        | 0.76%   |
| Logitech QuickCam Ultra Vision                | 1        | 0.76%   |
| Logitech QuickCam Communicate Deluxe          | 1        | 0.76%   |
| Logitech Logitech Webcam C160                 | 1        | 0.76%   |
| Logitech HD Webcam C510                       | 1        | 0.76%   |
| Logitech CrystalCam                           | 1        | 0.76%   |
| Logitech BRIO 4K Stream Edition               | 1        | 0.76%   |
| Linux Foundation EEM Gadget                   | 1        | 0.76%   |
| LG AN-VC500 Camera                            | 1        | 0.76%   |
| Lenovo FULL HD 1080P Webcam                   | 1        | 0.76%   |
| Lenovo 500 RGB Camera                         | 1        | 0.76%   |
| KYE Systems (Mouse Systems) Genius iSlim 330  | 1        | 0.76%   |
| KYE Systems (Mouse Systems) FaceCam 1000X     | 1        | 0.76%   |
| HP Webcam 1300                                | 1        | 0.76%   |
| Guillemot Hercules Dualpix Exchange           | 1        | 0.76%   |
| Google Nexus/Pixel Device (MTP + debug)       | 1        | 0.76%   |
| Generalplus WEB CAM                           | 1        | 0.76%   |
| Cubeternet WebCam                             | 1        | 0.76%   |
| Cubeternet HDMI to U3 capture                 | 1        | 0.76%   |

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


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Yubico.com                        | 3        | 60%     |
| VASCO Data Security International | 1        | 20%     |
| Clay Logic                        | 1        | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Yubico.com Yubikey 4/5 U2F+CCID                | 2        | 40%     |
| Yubico.com Yubikey 4/5 CCID                    | 1        | 20%     |
| VASCO Data Security International DIGIPASS 870 | 1        | 20%     |
| Clay Logic Nitrokey Pro                        | 1        | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 447      | 87.82%  |
| 1     | 53       | 10.41%  |
| 2     | 7        | 1.38%   |
| 5     | 1        | 0.2%    |
| 3     | 1        | 0.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 20       | 29.85%  |
| Net/wireless             | 18       | 26.87%  |
| Unassigned class         | 8        | 11.94%  |
| Communication controller | 7        | 10.45%  |
| Camera                   | 5        | 7.46%   |
| Sound                    | 3        | 4.48%   |
| Modem                    | 3        | 4.48%   |
| Storage/raid             | 1        | 1.49%   |
| Firewire controller      | 1        | 1.49%   |
| Bluetooth                | 1        | 1.49%   |

